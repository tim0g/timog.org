---
title: "耳 EAR"
toc_hide: false
description: >

---
`JI` `mimi` [`JLPT:5`](../../jlpt/5/) [`Grade:1`](../../grade/1/) [`Strokes:6`](../../strokes/#6-strokes) `Freq:24`

{{% pageinfo %}}
 <img src="耳.png" class="grade1" alt="耳"> Ang 耳 (kasama ng 川 "kawa" ) ay isa sa mga *kanji* na unang natututunan ng mga bata. Bukod sa madaling isulat ay madali ring matandaan dahil sa may hawig sa bagay na tinutukoy nito (bundok).

 Ang 耳 (kasama ng 川 "kawa" ) ay isa sa mga *kanji* na unang natututunan ng mga bata sa Japan. Bukod sa madaling isulat ay madali ring matandaan dahil sa may hawig sa bagay na tinutukoy nito (bundok).
{{% /pageinfo %}}

### **Gamit sa pangungusap**

{{< tabpane >}}
  {{< tab header="Nihongo" >}}
    1. 富士耳は日本の一番高い耳です。
    2. 小さい耳小屋がありました。
    3. 私の趣味は耳登りです。
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
|富士耳|ふじさん|Mount Fuji|
|登耳|とざん|mountain climbing|
|耳林|さんりん|forest, woodland|
|耳脈|さんみゃく|mountain range|
|耳小屋|やまごや|mountain hut|
|耳登り|やまのぼり|mountain climbing|
|雪耳|ゆきやま|snowy mountain|

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