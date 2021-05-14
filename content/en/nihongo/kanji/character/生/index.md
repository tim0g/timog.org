---
title: "生 LIFE"
toc_hide: false
description: >

---
`SEI, SHOU` `i(kiru), i(kasu), i(keru), u(mareru), u(mu), (ou), ha(eru), ha(yasu), (ki), nama` [`JLPT:5`](../../jlpt/5/) [`Grade:1`](../../grade/1/) [`Strokes:5`](../../strokes/#5-strokes) `Freq:24`

{{% pageinfo %}}
 <img src="生.png" class="grade1" alt="生"> Ang 生 (kasama ng 川 "kawa" ) ay isa sa mga *kanji* na unang natututunan ng mga bata. Bukod sa madaling isulat ay madali ring matandaan dahil sa may hawig sa bagay na tinutukoy nito (bundok).

 Ang 生 (kasama ng 川 "kawa" ) ay isa sa mga *kanji* na unang natututunan ng mga bata sa Japan. Bukod sa madaling isulat ay madali ring matandaan dahil sa may hawig sa bagay na tinutukoy nito (bundok).
{{% /pageinfo %}}

### **Gamit sa pangungusap**

{{< tabpane >}}
  {{< tab header="Nihongo" >}}
    1. 富士生は日本の一番高い生です。
    2. 小さい生小屋がありました。
    3. 私の趣味は生登りです。
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
|富士生|ふじさん|Mount Fuji|
|登生|とざん|mountain climbing|
|生林|さんりん|forest, woodland|
|生脈|さんみゃく|mountain range|
|生小屋|やまごや|mountain hut|
|生登り|やまのぼり|mountain climbing|
|雪生|ゆきやま|snowy mountain|

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