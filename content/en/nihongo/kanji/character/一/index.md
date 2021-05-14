---
title: "一 ONE"
toc_hide: false
description: >

---
`ICHI, ITSU` `hito, hito(tsu)` [`JLPT:5`](../../jlpt/5/) [`Grade:1`](../../grade/1/) [`Strokes:1`](../../strokes/#1-stroke) `Freq:2`

{{% pageinfo %}}
 <img src="一.png" class="grade1" alt="一"> Pinakasimpleng *kanji* sa lahat, isang pahalang na linya na ibig sabihin ay "isa". Ang 一 ay isa sa pinakamadalas na ginagamit na *kanji*, pangalawa lang sa [日](../日/) sa popularidad.

Ang pinagsamang 一 at 日 (一日) ay binabasa nang "ichinichi" kung ang ibig sabihin ay isang araw, pero "tsuitachi" kung ang ibig sabihin ay unang araw ng isang buwan.

Isa pang hindi pangkaraniwang reading na may 一 ay ang salitang "hitori" (一人).

Isulat ang 一 nang pataas nang kaunti at hindi tuwid na tuwid na parang dash.

{{% /pageinfo %}}

<span class="kanjih">Paggamit</span>

{{< tabpane >}}
  {{< tab header="Nihongo" >}}
    1. 寿司を一口で食べます。
    2. 私はペンを一本買いました。
    3. 一番好きなバンドはスピッツです。
  {{< /tab >}}
  {{< tab header="Furigana" >}}
    1. すしを　ひとくちで　たべます。
    2. わたしは　ぺんを　いっぽん　かいました。
    3. いちばん　すきな　バンドは　スピッツです。
  {{< /tab >}}
    {{< tab header="Romaji" >}}
    1. Sushi wo hitokuchi de tabemasu.
    2. Watashi wa pen wo ippon kaimashita.
    3. Ichiban sukina bando wa Supittsu desu.
  {{< /tab >}}
  {{< tab header="Tagalog" >}}
    1. Kainin nang isang subo ang sushi.
    2. Ako ay bumili ng isang ballpen.
    3. Ang pinakapaborito kong banda ay Spitz.
  {{< /tab >}}
{{< /tabpane >}}

<span class="kanjih">Gamit sa salita</span>

|Nihongo|Furigana|Kahulugan|
|--------|---------|---------|
|一個|いっこ|isang bagay|
|一本|いっぽん|isang (mahabang) bagay|
|一枚|いちまい|isang (manipis na) bagay|
|一番|いちばん|una, pinaka-|
|一位|いちい|unang posisyon|
|日本一|にっぽんいち|una sa Japan|
|同一|どういち|pareho|

<span class="kanjih">Paano isulat</span>

<div id="myvideo"></div>

<script async src="https://www.youtube.com/iframe_api"></script>
<script>
var player;
var videoId='BqIEOf81jBk';
var startSeconds = 1;  // set your own video start time when loop play
var endSeconds = 5;   // set your own video end time when loop play
var playerConfig = {
  height: '315',
  width: '560',
  videoId: videoId,
  playerVars: {

    autoplay: 0,            // Auto-play the video on load
    controls: 1,            // Show pause/play buttons in player
    showinfo: 0,            // Hide the video title
    modestbranding: 0,      // Hide the Youtube Logo
    fs: 1,                  // Hide the full screen button
    cc_load_policy: 0,      // Hide closed captions
    iv_load_policy: 3,      // Hide the Video Annotations
    start: startSeconds,
    end: endSeconds,
    autohide: 1, // Hide video controls when playing
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