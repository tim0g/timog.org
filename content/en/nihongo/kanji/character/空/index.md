---
title: "空 SKY"
toc_hide: false
description: >

---
`KUU` `sora, a(ku), a(keru), kara` [`JLPT:5`](../../jlpt/5/) [`Grade:1`](../../grade/1/) [`Strokes:8`](../../strokes/#8-strokes) `Freq:24`

{{% pageinfo %}}
 <img src="空.png" class="grade1" alt="空"> Ang 空 (kasama ng 川 "kawa" ) ay isa sa mga *kanji* na unang natututunan ng mga bata. Bukod sa madaling isulat ay madali ring matandaan dahil sa may hawig sa bagay na tinutukoy nito (bundok).

 Ang 空 (kasama ng 川 "kawa" ) ay isa sa mga *kanji* na unang natututunan ng mga bata sa Japan. Bukod sa madaling isulat ay madali ring matandaan dahil sa may hawig sa bagay na tinutukoy nito (bundok).
{{% /pageinfo %}}

<span class="kanjih">Sentences</span>

{{< tabpane >}}
  {{< tab header="Nihongo" >}}
    1. 富士空は日本の一番高い空です。
    2. 小さい空小屋がありました。
    3. 私の趣味は空登りです。
  {{< /tab >}}
  {{< tab header="Furigana" >}}
    1. ふじさんは　にほんの　いちばん　たかいやま　です。
    2. ちいさい　やまごやが　ありました。
    3. わたしの　しゅみは　やまのぼりです。
  {{< /tab >}}
    {{< tab header="Romaji" >}}
    1. Fujisan wa Nihon no ichiban takai yama desu.
    2. Chiisai yamagoya ga arimashita.
    3. Watashi no shumi wa yamanobori desu.
  {{< /tab >}}
  {{< tab header="Tagalog" >}}
    1. Ang Mount Fuji ay ang pinakamataas na bundok sa Japan.
    2. Mayroong maliit na kubo sa bundok.
    3. Ang aking libangan ay pag-akyat ng bundok.
  {{< /tab >}}
{{< /tabpane >}}

<span class="kanjih">Words</span>

|Word|Reading|Meaning|
|--------|---------|---------|
|富士空|ふじさん|Mount Fuji|
|登空|とざん|mountain climbing|
|空林|さんりん|forest, woodland|
|空脈|さんみゃく|mountain range|
|空小屋|やまごや|mountain hut|
|空登り|やまのぼり|mountain climbing|
|雪空|ゆきやま|snowy mountain|

<span class="kanjih">How to write</span>

<div id="myvideo"></div>

<script async src="https://www.youtube.com/iframe_api"></script>
<script>
var player;
var videoId='BqIEOf81jBk';
var startSeconds = 342;  // set your own video start time when loop play
var endSeconds = 349;   // set your own video end time when loop play
var playerConfig = {
  height: '315',
  width: '560',
  videoId: videoId,
  playerVars: {

    autoplay: 0,            // Auto-play the video on load
    controls: 1,            // Show pause/play buttons in player
    showinfo: 0,            // Hide the video title
    modestbranding: 1,      // Hide the Youtube Logo
    fs: 1,                  // Hide the full screen button
    cc_load_policy: 0,      // Hide closed captions
    iv_load_policy: 3,      // Hide the Video Annotations
    start: startSeconds,
    end: endSeconds,
    autohide: 0, // Hide video controls when playing
  },
  events: {
       'onStateChange': onStateChange,       // reference to Iframe API
        onReady: function(e) {              // mute the video when loaded
        e.target.mute();             
      }
    }
};
//excute the video in div
function onYouTubePlayerAPIReady() {

  player = new YT.Player('myvideo', playerConfig);

}
//repload the video when onStateChange=YT.PlayerState.ENDED)
function onStateChange(state) {
  if (state.data === YT.PlayerState.ENDED) {
    player.loadVideoById({
      videoId: videoId,
      startSeconds: startSeconds,
      endSeconds: endSeconds

    });
  }
}

</script>