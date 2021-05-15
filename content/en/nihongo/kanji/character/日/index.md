---
title: "日 SUN, JAPAN"
toc_hide: false
description: >

---
`NICHI, JITSU` `hi, ka` [`JLPT:5`](../../jlpt/5/) [`Grade:1`](../../grade/1/) [`Strokes:4`](../../strokes/#4-strokes) `Freq:24`

{{% pageinfo %}}
 <img src="日.png" class="grade1" alt="日"> Ang 日 ang pinakamadalas na gamitin na *kanji* (base sa gamit sa mga dyaryo). Hindi nakapagtataka dahil ito ang *kanji* na ginagamit sa pagsulat ng araw sa petsa: 2011年3月11日 (March 11, 2011) at mga araw sa isang linggo.

 Ang 日曜日 (nichiyōbi Sunday ) ay may dalawang 日 na magkaiba ang reading, bukod pa sa radical na 日 sa gitnang kanji (曜).

 Ito rin siyempre ang kanji ng Japan: 日本 (Nihon=Nippon "Land of the Rising Sun"). 日比関係 (*nichihi kankei* Japan-Philippines relations), 日中貿易 (nitchū bōeki) Japan-China trade, etc.
{{% /pageinfo %}}

<span class="kanjih">Sentences</span>

{{< tabpane >}}
  {{< tab header="Nihongo" >}}
    1. 今日は月曜日です。
    2. 誕生日は2001年2月17日です。
    3. いつ来日しましたか。
  {{< /tab >}}
    {{< tab header="Romaji" >}}
    1. Kyō wa getsuyōbi desu.
    2. Tanjōbi wa nisen-ichinen nigatsu jūshichinichi desu.
    3. Itsu rainichi shimashita ka?
  {{< /tab >}}
  {{< tab header="Tagalog" >}}
    1. Ngayon ay Lunes.
    2. Ang (aking) birthday ay February 17, 2001.
    3. Kailan (ka) dumating sa Japan?
  {{< /tab >}}
{{< /tabpane >}}

<span class="kanjih">Words</span>

|Word|Reading|Meaning|
|--------|---------|---------|
|富士日|ふじさん|Mount Fuji|
|登日|とざん|mountain climbing|
|日林|さんりん|forest, woodland|
|日脈|さんみゃく|mountain range|
|日小屋|やまごや|mountain hut|
|日登り|やまのぼり|mountain climbing|
|雪日|ゆきやま|snowy mountain|

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