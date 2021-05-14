---
title: "千 THOUSAND"
toc_hide: false
description: >

---
`SEN` `chi` [`JLPT:5`](../../jlpt/5/) [`Grade:1`](../../grade/1/) [`Strokes:3`](../../strokes/#3-strokes) `Freq:24`

{{% pageinfo %}}
 <img src="千.png" class="grade1" alt="千"> Ang 千 (kasama ng 川 "kawa" ) ay isa sa mga *kanji* na unang natututunan ng mga bata. Bukod sa madaling isulat ay madali ring matandaan dahil sa may hawig sa bagay na tinutukoy nito (bundok).

 Ang 千 (kasama ng 川 "kawa" ) ay isa sa mga *kanji* na unang natututunan ng mga bata sa Japan. Bukod sa madaling isulat ay madali ring matandaan dahil sa may hawig sa bagay na tinutukoy nito (bundok).
{{% /pageinfo %}}

### **Gamit sa pangungusap**

{{< tabpane >}}
  {{< tab header="Nihongo" >}}
    1. 富士千は日本の一番高い千です。
    2. 小さい千小屋がありました。
    3. 私の趣味は千登りです。
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

### **Gamit sa salita**

|Nihongo|Furigana|Kahulugan|
|--------|---------|---------|
|富士千|ふじさん|Mount Fuji|
|登千|とざん|mountain climbing|
|千林|さんりん|forest, woodland|
|千脈|さんみゃく|mountain range|
|千小屋|やまごや|mountain hut|
|千登り|やまのぼり|mountain climbing|
|雪千|ゆきやま|snowy mountain|

### **Paano isulat**

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