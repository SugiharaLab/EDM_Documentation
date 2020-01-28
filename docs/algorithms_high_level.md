<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />

<title>EDM_Examples</title>


<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
  width:100% !important;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.7.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.7.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.7.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff2?v=4.7.0') format('woff2'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.7.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.7.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.7.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.fa-pull-left {
  float: left;
}
.fa-pull-right {
  float: right;
}
.fa.fa-pull-left {
  margin-right: .3em;
}
.fa.fa-pull-right {
  margin-left: .3em;
}
/* Deprecated as of 4.4.0 */
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8);
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=1)";
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2)";
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=3)";
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)";
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)";
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook-f:before,
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-feed:before,
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before,
.fa-gratipay:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper-pp:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-resistance:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-y-combinator-square:before,
.fa-yc-square:before,
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
.fa-buysellads:before {
  content: "\f20d";
}
.fa-connectdevelop:before {
  content: "\f20e";
}
.fa-dashcube:before {
  content: "\f210";
}
.fa-forumbee:before {
  content: "\f211";
}
.fa-leanpub:before {
  content: "\f212";
}
.fa-sellsy:before {
  content: "\f213";
}
.fa-shirtsinbulk:before {
  content: "\f214";
}
.fa-simplybuilt:before {
  content: "\f215";
}
.fa-skyatlas:before {
  content: "\f216";
}
.fa-cart-plus:before {
  content: "\f217";
}
.fa-cart-arrow-down:before {
  content: "\f218";
}
.fa-diamond:before {
  content: "\f219";
}
.fa-ship:before {
  content: "\f21a";
}
.fa-user-secret:before {
  content: "\f21b";
}
.fa-motorcycle:before {
  content: "\f21c";
}
.fa-street-view:before {
  content: "\f21d";
}
.fa-heartbeat:before {
  content: "\f21e";
}
.fa-venus:before {
  content: "\f221";
}
.fa-mars:before {
  content: "\f222";
}
.fa-mercury:before {
  content: "\f223";
}
.fa-intersex:before,
.fa-transgender:before {
  content: "\f224";
}
.fa-transgender-alt:before {
  content: "\f225";
}
.fa-venus-double:before {
  content: "\f226";
}
.fa-mars-double:before {
  content: "\f227";
}
.fa-venus-mars:before {
  content: "\f228";
}
.fa-mars-stroke:before {
  content: "\f229";
}
.fa-mars-stroke-v:before {
  content: "\f22a";
}
.fa-mars-stroke-h:before {
  content: "\f22b";
}
.fa-neuter:before {
  content: "\f22c";
}
.fa-genderless:before {
  content: "\f22d";
}
.fa-facebook-official:before {
  content: "\f230";
}
.fa-pinterest-p:before {
  content: "\f231";
}
.fa-whatsapp:before {
  content: "\f232";
}
.fa-server:before {
  content: "\f233";
}
.fa-user-plus:before {
  content: "\f234";
}
.fa-user-times:before {
  content: "\f235";
}
.fa-hotel:before,
.fa-bed:before {
  content: "\f236";
}
.fa-viacoin:before {
  content: "\f237";
}
.fa-train:before {
  content: "\f238";
}
.fa-subway:before {
  content: "\f239";
}
.fa-medium:before {
  content: "\f23a";
}
.fa-yc:before,
.fa-y-combinator:before {
  content: "\f23b";
}
.fa-optin-monster:before {
  content: "\f23c";
}
.fa-opencart:before {
  content: "\f23d";
}
.fa-expeditedssl:before {
  content: "\f23e";
}
.fa-battery-4:before,
.fa-battery:before,
.fa-battery-full:before {
  content: "\f240";
}
.fa-battery-3:before,
.fa-battery-three-quarters:before {
  content: "\f241";
}
.fa-battery-2:before,
.fa-battery-half:before {
  content: "\f242";
}
.fa-battery-1:before,
.fa-battery-quarter:before {
  content: "\f243";
}
.fa-battery-0:before,
.fa-battery-empty:before {
  content: "\f244";
}
.fa-mouse-pointer:before {
  content: "\f245";
}
.fa-i-cursor:before {
  content: "\f246";
}
.fa-object-group:before {
  content: "\f247";
}
.fa-object-ungroup:before {
  content: "\f248";
}
.fa-sticky-note:before {
  content: "\f249";
}
.fa-sticky-note-o:before {
  content: "\f24a";
}
.fa-cc-jcb:before {
  content: "\f24b";
}
.fa-cc-diners-club:before {
  content: "\f24c";
}
.fa-clone:before {
  content: "\f24d";
}
.fa-balance-scale:before {
  content: "\f24e";
}
.fa-hourglass-o:before {
  content: "\f250";
}
.fa-hourglass-1:before,
.fa-hourglass-start:before {
  content: "\f251";
}
.fa-hourglass-2:before,
.fa-hourglass-half:before {
  content: "\f252";
}
.fa-hourglass-3:before,
.fa-hourglass-end:before {
  content: "\f253";
}
.fa-hourglass:before {
  content: "\f254";
}
.fa-hand-grab-o:before,
.fa-hand-rock-o:before {
  content: "\f255";
}
.fa-hand-stop-o:before,
.fa-hand-paper-o:before {
  content: "\f256";
}
.fa-hand-scissors-o:before {
  content: "\f257";
}
.fa-hand-lizard-o:before {
  content: "\f258";
}
.fa-hand-spock-o:before {
  content: "\f259";
}
.fa-hand-pointer-o:before {
  content: "\f25a";
}
.fa-hand-peace-o:before {
  content: "\f25b";
}
.fa-trademark:before {
  content: "\f25c";
}
.fa-registered:before {
  content: "\f25d";
}
.fa-creative-commons:before {
  content: "\f25e";
}
.fa-gg:before {
  content: "\f260";
}
.fa-gg-circle:before {
  content: "\f261";
}
.fa-tripadvisor:before {
  content: "\f262";
}
.fa-odnoklassniki:before {
  content: "\f263";
}
.fa-odnoklassniki-square:before {
  content: "\f264";
}
.fa-get-pocket:before {
  content: "\f265";
}
.fa-wikipedia-w:before {
  content: "\f266";
}
.fa-safari:before {
  content: "\f267";
}
.fa-chrome:before {
  content: "\f268";
}
.fa-firefox:before {
  content: "\f269";
}
.fa-opera:before {
  content: "\f26a";
}
.fa-internet-explorer:before {
  content: "\f26b";
}
.fa-tv:before,
.fa-television:before {
  content: "\f26c";
}
.fa-contao:before {
  content: "\f26d";
}
.fa-500px:before {
  content: "\f26e";
}
.fa-amazon:before {
  content: "\f270";
}
.fa-calendar-plus-o:before {
  content: "\f271";
}
.fa-calendar-minus-o:before {
  content: "\f272";
}
.fa-calendar-times-o:before {
  content: "\f273";
}
.fa-calendar-check-o:before {
  content: "\f274";
}
.fa-industry:before {
  content: "\f275";
}
.fa-map-pin:before {
  content: "\f276";
}
.fa-map-signs:before {
  content: "\f277";
}
.fa-map-o:before {
  content: "\f278";
}
.fa-map:before {
  content: "\f279";
}
.fa-commenting:before {
  content: "\f27a";
}
.fa-commenting-o:before {
  content: "\f27b";
}
.fa-houzz:before {
  content: "\f27c";
}
.fa-vimeo:before {
  content: "\f27d";
}
.fa-black-tie:before {
  content: "\f27e";
}
.fa-fonticons:before {
  content: "\f280";
}
.fa-reddit-alien:before {
  content: "\f281";
}
.fa-edge:before {
  content: "\f282";
}
.fa-credit-card-alt:before {
  content: "\f283";
}
.fa-codiepie:before {
  content: "\f284";
}
.fa-modx:before {
  content: "\f285";
}
.fa-fort-awesome:before {
  content: "\f286";
}
.fa-usb:before {
  content: "\f287";
}
.fa-product-hunt:before {
  content: "\f288";
}
.fa-mixcloud:before {
  content: "\f289";
}
.fa-scribd:before {
  content: "\f28a";
}
.fa-pause-circle:before {
  content: "\f28b";
}
.fa-pause-circle-o:before {
  content: "\f28c";
}
.fa-stop-circle:before {
  content: "\f28d";
}
.fa-stop-circle-o:before {
  content: "\f28e";
}
.fa-shopping-bag:before {
  content: "\f290";
}
.fa-shopping-basket:before {
  content: "\f291";
}
.fa-hashtag:before {
  content: "\f292";
}
.fa-bluetooth:before {
  content: "\f293";
}
.fa-bluetooth-b:before {
  content: "\f294";
}
.fa-percent:before {
  content: "\f295";
}
.fa-gitlab:before {
  content: "\f296";
}
.fa-wpbeginner:before {
  content: "\f297";
}
.fa-wpforms:before {
  content: "\f298";
}
.fa-envira:before {
  content: "\f299";
}
.fa-universal-access:before {
  content: "\f29a";
}
.fa-wheelchair-alt:before {
  content: "\f29b";
}
.fa-question-circle-o:before {
  content: "\f29c";
}
.fa-blind:before {
  content: "\f29d";
}
.fa-audio-description:before {
  content: "\f29e";
}
.fa-volume-control-phone:before {
  content: "\f2a0";
}
.fa-braille:before {
  content: "\f2a1";
}
.fa-assistive-listening-systems:before {
  content: "\f2a2";
}
.fa-asl-interpreting:before,
.fa-american-sign-language-interpreting:before {
  content: "\f2a3";
}
.fa-deafness:before,
.fa-hard-of-hearing:before,
.fa-deaf:before {
  content: "\f2a4";
}
.fa-glide:before {
  content: "\f2a5";
}
.fa-glide-g:before {
  content: "\f2a6";
}
.fa-signing:before,
.fa-sign-language:before {
  content: "\f2a7";
}
.fa-low-vision:before {
  content: "\f2a8";
}
.fa-viadeo:before {
  content: "\f2a9";
}
.fa-viadeo-square:before {
  content: "\f2aa";
}
.fa-snapchat:before {
  content: "\f2ab";
}
.fa-snapchat-ghost:before {
  content: "\f2ac";
}
.fa-snapchat-square:before {
  content: "\f2ad";
}
.fa-pied-piper:before {
  content: "\f2ae";
}
.fa-first-order:before {
  content: "\f2b0";
}
.fa-yoast:before {
  content: "\f2b1";
}
.fa-themeisle:before {
  content: "\f2b2";
}
.fa-google-plus-circle:before,
.fa-google-plus-official:before {
  content: "\f2b3";
}
.fa-fa:before,
.fa-font-awesome:before {
  content: "\f2b4";
}
.fa-handshake-o:before {
  content: "\f2b5";
}
.fa-envelope-open:before {
  content: "\f2b6";
}
.fa-envelope-open-o:before {
  content: "\f2b7";
}
.fa-linode:before {
  content: "\f2b8";
}
.fa-address-book:before {
  content: "\f2b9";
}
.fa-address-book-o:before {
  content: "\f2ba";
}
.fa-vcard:before,
.fa-address-card:before {
  content: "\f2bb";
}
.fa-vcard-o:before,
.fa-address-card-o:before {
  content: "\f2bc";
}
.fa-user-circle:before {
  content: "\f2bd";
}
.fa-user-circle-o:before {
  content: "\f2be";
}
.fa-user-o:before {
  content: "\f2c0";
}
.fa-id-badge:before {
  content: "\f2c1";
}
.fa-drivers-license:before,
.fa-id-card:before {
  content: "\f2c2";
}
.fa-drivers-license-o:before,
.fa-id-card-o:before {
  content: "\f2c3";
}
.fa-quora:before {
  content: "\f2c4";
}
.fa-free-code-camp:before {
  content: "\f2c5";
}
.fa-telegram:before {
  content: "\f2c6";
}
.fa-thermometer-4:before,
.fa-thermometer:before,
.fa-thermometer-full:before {
  content: "\f2c7";
}
.fa-thermometer-3:before,
.fa-thermometer-three-quarters:before {
  content: "\f2c8";
}
.fa-thermometer-2:before,
.fa-thermometer-half:before {
  content: "\f2c9";
}
.fa-thermometer-1:before,
.fa-thermometer-quarter:before {
  content: "\f2ca";
}
.fa-thermometer-0:before,
.fa-thermometer-empty:before {
  content: "\f2cb";
}
.fa-shower:before {
  content: "\f2cc";
}
.fa-bathtub:before,
.fa-s15:before,
.fa-bath:before {
  content: "\f2cd";
}
.fa-podcast:before {
  content: "\f2ce";
}
.fa-window-maximize:before {
  content: "\f2d0";
}
.fa-window-minimize:before {
  content: "\f2d1";
}
.fa-window-restore:before {
  content: "\f2d2";
}
.fa-times-rectangle:before,
.fa-window-close:before {
  content: "\f2d3";
}
.fa-times-rectangle-o:before,
.fa-window-close-o:before {
  content: "\f2d4";
}
.fa-bandcamp:before {
  content: "\f2d5";
}
.fa-grav:before {
  content: "\f2d6";
}
.fa-etsy:before {
  content: "\f2d7";
}
.fa-imdb:before {
  content: "\f2d8";
}
.fa-ravelry:before {
  content: "\f2d9";
}
.fa-eercast:before {
  content: "\f2da";
}
.fa-microchip:before {
  content: "\f2db";
}
.fa-snowflake-o:before {
  content: "\f2dc";
}
.fa-superpowers:before {
  content: "\f2dd";
}
.fa-wpexplorer:before {
  content: "\f2de";
}
.fa-meetup:before {
  content: "\f2e0";
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
div.traceback-wrapper pre.traceback {
  max-height: 600px;
  overflow: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 5px;
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
[dir="rtl"] #ipython_notebook {
  margin-right: 10px;
  margin-left: 0;
}
[dir="rtl"] #ipython_notebook.pull-left {
  float: right !important;
  float: right;
}
.flex-spacer {
  flex: 1;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#kernel_logo_widget {
  margin: 0 10px;
}
span#login_widget {
  float: right;
}
[dir="rtl"] span#login_widget {
  float: left;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
.modal-header {
  cursor: move;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
[dir="rtl"] .center-nav form.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] .center-nav .navbar-text {
  float: right;
}
[dir="rtl"] .navbar-inner {
  text-align: right;
}
[dir="rtl"] div.text-left {
  text-align: right;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  position: absolute;
  display: block;
  width: 100%;
  height: 100%;
  overflow: hidden;
  cursor: pointer;
  opacity: 0;
  z-index: 2;
}
.alternate_upload .btn-xs > input.fileinput {
  margin: -1px -5px;
}
.alternate_upload .btn-upload {
  position: relative;
  height: 22px;
}
::-webkit-file-upload-button {
  cursor: pointer;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
ul#tabs {
  margin-bottom: 4px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
[dir="rtl"] ul#tabs.nav-tabs > li {
  float: right;
}
[dir="rtl"] ul#tabs.nav.nav-tabs {
  padding-right: 0;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons .pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .list_toolbar .col-sm-4,
[dir="rtl"] .list_toolbar .col-sm-8 {
  float: right;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: text-bottom;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
[dir="rtl"] .list_item > div input {
  margin-right: 0;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_modified {
  margin-right: 7px;
  margin-left: 7px;
}
[dir="rtl"] .item_modified.pull-right {
  float: left !important;
  float: left;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
[dir="rtl"] .item_buttons.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .item_buttons .kernel-name {
  margin-left: 7px;
  float: right;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
.sort_button {
  display: inline-block;
  padding-left: 7px;
}
[dir="rtl"] .sort_button.pull-right {
  float: left !important;
  float: left;
}
#tree-selector {
  padding-right: 0px;
}
#button-select-all {
  min-width: 50px;
}
[dir="rtl"] #button-select-all.btn {
  float: right ;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
  margin-top: 2px;
  height: 16px;
}
[dir="rtl"] #select-all.pull-left {
  float: right !important;
  float: right;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.fa-pull-left {
  margin-right: .3em;
}
.folder_icon:before.fa-pull-right {
  margin-left: .3em;
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.fa-pull-left {
  margin-right: .3em;
}
.file_icon:before.fa-pull-right {
  margin-left: .3em;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
#new-menu .dropdown-header {
  font-size: 10px;
  border-bottom: 1px solid #e5e5e5;
  padding: 0 0 3px;
  margin: -3px 20px 0;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.move-button {
  display: none;
}
.download-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
.CodeMirror-dialog {
  background-color: #fff;
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI escape sequences */
/* The color values are a mix of
   http://www.xcolors.net/dl/baskerville-ivorylight and
   http://www.xcolors.net/dl/euphrasia */
.ansi-black-fg {
  color: #3E424D;
}
.ansi-black-bg {
  background-color: #3E424D;
}
.ansi-black-intense-fg {
  color: #282C36;
}
.ansi-black-intense-bg {
  background-color: #282C36;
}
.ansi-red-fg {
  color: #E75C58;
}
.ansi-red-bg {
  background-color: #E75C58;
}
.ansi-red-intense-fg {
  color: #B22B31;
}
.ansi-red-intense-bg {
  background-color: #B22B31;
}
.ansi-green-fg {
  color: #00A250;
}
.ansi-green-bg {
  background-color: #00A250;
}
.ansi-green-intense-fg {
  color: #007427;
}
.ansi-green-intense-bg {
  background-color: #007427;
}
.ansi-yellow-fg {
  color: #DDB62B;
}
.ansi-yellow-bg {
  background-color: #DDB62B;
}
.ansi-yellow-intense-fg {
  color: #B27D12;
}
.ansi-yellow-intense-bg {
  background-color: #B27D12;
}
.ansi-blue-fg {
  color: #208FFB;
}
.ansi-blue-bg {
  background-color: #208FFB;
}
.ansi-blue-intense-fg {
  color: #0065CA;
}
.ansi-blue-intense-bg {
  background-color: #0065CA;
}
.ansi-magenta-fg {
  color: #D160C4;
}
.ansi-magenta-bg {
  background-color: #D160C4;
}
.ansi-magenta-intense-fg {
  color: #A03196;
}
.ansi-magenta-intense-bg {
  background-color: #A03196;
}
.ansi-cyan-fg {
  color: #60C6C8;
}
.ansi-cyan-bg {
  background-color: #60C6C8;
}
.ansi-cyan-intense-fg {
  color: #258F8F;
}
.ansi-cyan-intense-bg {
  background-color: #258F8F;
}
.ansi-white-fg {
  color: #C5C1B4;
}
.ansi-white-bg {
  background-color: #C5C1B4;
}
.ansi-white-intense-fg {
  color: #A1A6B2;
}
.ansi-white-intense-bg {
  background-color: #A1A6B2;
}
.ansi-default-inverse-fg {
  color: #FFFFFF;
}
.ansi-default-inverse-bg {
  background-color: #000000;
}
.ansi-bold {
  font-weight: bold;
}
.ansi-underline {
  text-decoration: underline;
}
/* The following styles are deprecated an will be removed in a future version */
.ansibold {
  font-weight: bold;
}
.ansi-inverse {
  outline: 0.5px dotted;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  position: relative;
  overflow: visible;
}
div.cell:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: transparent;
}
div.cell.jupyter-soft-selected {
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected,
div.cell.selected.jupyter-soft-selected {
  border-color: #ababab;
}
div.cell.selected:before,
div.cell.selected.jupyter-soft-selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #42A5F5;
}
@media print {
  div.cell.selected,
  div.cell.selected.jupyter-soft-selected {
    border-color: transparent;
  }
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
}
.edit_mode div.cell.selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #66BB6A;
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  /* Note that this should set vertical padding only, since CodeMirror assumes
       that horizontal padding will be set on CodeMirror pre */
  padding: 0.4em 0;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. This sets horizontal padding only,
    use .CodeMirror-lines for vertical */
  padding: 0 0.4em;
  border: 0;
  border-radius: 0;
}
.CodeMirror-cursor {
  border-left: 1.4px solid black;
}
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .CodeMirror-cursor {
    border-left: 2px solid black;
  }
}
@media screen and (min-width: 4320px) {
  .CodeMirror-cursor {
    border-left: 4px solid black;
  }
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
div.output_area .mglyph > img {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 1px 0 1px 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul:not(.list-inline),
.rendered_html ol:not(.list-inline) {
  padding-left: 2em;
}
.rendered_html ul {
  list-style: disc;
}
.rendered_html ul ul {
  list-style: square;
  margin-top: 0;
}
.rendered_html ul ul ul {
  list-style: circle;
}
.rendered_html ol {
  list-style: decimal;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin-top: 0;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
  padding: 0px;
  background-color: #fff;
}
.rendered_html code {
  background-color: #eff0f1;
}
.rendered_html p code {
  padding: 1px 5px;
}
.rendered_html pre code {
  background-color: #fff;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  color: #000;
  font-size: 100%;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: none;
  border-collapse: collapse;
  border-spacing: 0;
  color: black;
  font-size: 12px;
  table-layout: fixed;
}
.rendered_html thead {
  border-bottom: 1px solid black;
  vertical-align: bottom;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  text-align: right;
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html tbody tr:nth-child(odd) {
  background: #f5f5f5;
}
.rendered_html tbody tr:hover {
  background: rgba(66, 165, 245, 0.2);
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
.rendered_html .alert {
  margin-bottom: initial;
}
.rendered_html * + .alert {
  margin-top: 1em;
}
[dir="rtl"] .rendered_html p {
  text-align: right;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.rendered .rendered_html tr,
.text_cell.rendered .rendered_html th,
.text_cell.rendered .rendered_html td {
  max-width: none;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.text_cell .dropzone .input_area {
  border: 2px dashed #bababa;
  margin: -1px;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
.jupyter-keybindings {
  padding: 1px;
  line-height: 24px;
  border-bottom: 1px solid gray;
}
.jupyter-keybindings input {
  margin: 0;
  padding: 0;
  border: none;
}
.jupyter-keybindings i {
  padding: 6px;
}
.well code {
  background-color: #ffffff;
  border-color: #ababab;
  border-width: 1px;
  border-style: solid;
  padding: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.tags_button_container {
  width: 100%;
  display: flex;
}
.tag-container {
  display: flex;
  flex-direction: row;
  flex-grow: 1;
  overflow: hidden;
  position: relative;
}
.tag-container > * {
  margin: 0 4px;
}
.remove-tag-btn {
  margin-left: 4px;
}
.tags-input {
  display: flex;
}
.cell-tag:last-child:after {
  content: "";
  position: absolute;
  right: 0;
  width: 40px;
  height: 100%;
  /* Fade to background color of cell toolbar */
  background: linear-gradient(to right, rgba(0, 0, 0, 0), #EEE);
}
.tags-input > * {
  margin-left: 4px;
}
.cell-tag,
.tags-input input,
.tags-input button {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  box-shadow: none;
  width: inherit;
  font-size: inherit;
  height: 22px;
  line-height: 22px;
  padding: 0px 4px;
  display: inline-block;
}
.cell-tag:focus,
.tags-input input:focus,
.tags-input button:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.cell-tag::-moz-placeholder,
.tags-input input::-moz-placeholder,
.tags-input button::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.cell-tag:-ms-input-placeholder,
.tags-input input:-ms-input-placeholder,
.tags-input button:-ms-input-placeholder {
  color: #999;
}
.cell-tag::-webkit-input-placeholder,
.tags-input input::-webkit-input-placeholder,
.tags-input button::-webkit-input-placeholder {
  color: #999;
}
.cell-tag::-ms-expand,
.tags-input input::-ms-expand,
.tags-input button::-ms-expand {
  border: 0;
  background-color: transparent;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
.cell-tag[readonly],
.tags-input input[readonly],
.tags-input button[readonly],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  background-color: #eeeeee;
  opacity: 1;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  cursor: not-allowed;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button {
  height: auto;
}
select.cell-tag,
select.tags-input input,
select.tags-input button {
  height: 30px;
  line-height: 30px;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button,
select[multiple].cell-tag,
select[multiple].tags-input input,
select[multiple].tags-input button {
  height: auto;
}
.cell-tag,
.tags-input button {
  padding: 0px 4px;
}
.cell-tag {
  background-color: #fff;
  white-space: nowrap;
}
.tags-input input[type=text]:focus {
  outline: none;
  box-shadow: none;
  border-color: #ccc;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
[dir="rtl"] #kernel_logo_widget {
  float: left !important;
  float: left;
}
.modal .modal-body .move-path {
  display: flex;
  flex-direction: row;
  justify-content: space;
  align-items: center;
}
.modal .modal-body .move-path .server-root {
  padding-right: 20px;
}
.modal .modal-body .move-path .path-input {
  flex: 1;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
[dir="rtl"] #menubar .navbar-toggle {
  float: right;
}
[dir="rtl"] #menubar .navbar-collapse {
  clear: right;
}
[dir="rtl"] #menubar .navbar-nav {
  float: right;
}
[dir="rtl"] #menubar .nav {
  padding-right: 0px;
}
[dir="rtl"] #menubar .navbar-nav > li {
  float: right;
}
[dir="rtl"] #menubar .navbar-right {
  float: left !important;
}
[dir="rtl"] ul.dropdown-menu {
  text-align: right;
  left: auto;
}
[dir="rtl"] ul#new-menu.dropdown-menu {
  right: auto;
  left: 0;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
[dir="rtl"] i.menu-icon.pull-right {
  float: left !important;
  float: left;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
[dir="rtl"] ul#help_menu li a {
  padding-left: 2.2em;
}
[dir="rtl"] ul#help_menu li a i {
  margin-right: 0;
  margin-left: -1.2em;
}
[dir="rtl"] ul#help_menu li a i.pull-right {
  float: left !important;
  float: left;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
[dir="rtl"] .dropdown-submenu > .dropdown-menu {
  right: 100%;
  margin-right: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.fa-pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.fa-pull-right {
  margin-left: .3em;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
[dir="rtl"] .dropdown-submenu > a:after {
  float: left;
  content: "\f0d9";
  margin-right: 0;
  margin-left: -10px;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
[dir="rtl"] #notification_area {
  float: left !important;
  float: left;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] .indicator_area {
  float: left !important;
  float: left;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
[dir="rtl"] #kernel_indicator {
  float: left !important;
  float: left;
  border-left: 0;
  border-right: 1px solid;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] #modal_indicator {
  float: left !important;
  float: left;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  height: 30px;
  margin-top: 4px;
  display: flex;
  justify-content: flex-start;
  align-items: baseline;
  width: 50%;
  flex: 1;
}
span.save_widget span.filename {
  height: 100%;
  line-height: 1em;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
[dir="rtl"] span.save_widget.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] span.save_widget span.filename {
  margin-left: 0;
  margin-right: 16px;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
  white-space: nowrap;
  padding: 0 5px;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
    padding: 0 0 0 5px;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
.toolbar-btn-label {
  margin-left: 6px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
[dir="rtl"] .btn-group > .btn,
.btn-group-vertical > .btn {
  float: right;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
[dir="rtl"] ul.typeahead-list i {
  margin-left: 0;
  margin-right: -10px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
ul.typeahead-list  > li > a.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .typeahead-list {
  text-align: right;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  min-width: 20px;
  color: transparent;
}
[dir="rtl"] .no-shortcut.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .command-shortcut.pull-right {
  float: left !important;
  float: left;
}
.command-shortcut:before {
  content: "(command mode)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
[dir="rtl"] .edit-shortcut.pull-right {
  float: left !important;
  float: left;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
[dir="ltr"] #find-and-replace .input-group-btn + .form-control {
  border-left: none;
}
[dir="rtl"] #find-and-replace .input-group-btn + .form-control {
  border-right: none;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[3]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">pyEDM</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Tent-map-sample-dataset">Tent map sample dataset<a class="anchor-link" href="#Tent-map-sample-dataset">&#182;</a></h3>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[4]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">tentmap</span> <span class="o">=</span> <span class="n">pyEDM</span><span class="o">.</span><span class="n">sampleData</span><span class="p">[</span><span class="s1">&#39;TentMapNoise&#39;</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[5]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span> <span class="n">tentmap</span><span class="p">[</span><span class="s1">&#39;TentMap&#39;</span><span class="p">][</span><span class="mi">1</span><span class="p">:</span><span class="mi">40</span><span class="p">]</span> <span class="p">);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Evaluate-optimal-embedding-dimension-(via-Simplex)">Evaluate optimal embedding dimension (via Simplex)<a class="anchor-link" href="#Evaluate-optimal-embedding-dimension-(via-Simplex)">&#182;</a></h3>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[6]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">pyEDM</span><span class="o">.</span><span class="n">EmbedDimension</span><span class="p">(</span> <span class="n">dataFrame</span> <span class="o">=</span> <span class="n">tentmap</span><span class="p">,</span> <span class="n">lib</span><span class="o">=</span><span class="s2">&quot;1 500&quot;</span><span class="p">,</span> <span class="n">pred</span><span class="o">=</span><span class="s2">&quot;501 550&quot;</span><span class="p">,</span> <span class="n">columns</span><span class="o">=</span><span class="s2">&quot;TentMap&quot;</span> <span class="p">);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The optimal embedding dimension is 3</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Evaluate-the-optimal-theta-value-(how-nonlinear-the-system-is)">Evaluate the optimal theta value (how nonlinear the system is)<a class="anchor-link" href="#Evaluate-the-optimal-theta-value-(how-nonlinear-the-system-is)">&#182;</a></h3>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[7]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">pyEDM</span><span class="o">.</span><span class="n">PredictNonlinear</span><span class="p">(</span> <span class="n">dataFrame</span> <span class="o">=</span> <span class="n">tentmap</span><span class="p">,</span> <span class="n">lib</span><span class="o">=</span><span class="s2">&quot;1 500&quot;</span><span class="p">,</span> <span class="n">pred</span><span class="o">=</span><span class="s2">&quot;501 550&quot;</span><span class="p">,</span> <span class="n">columns</span><span class="o">=</span><span class="s2">&quot;TentMap&quot;</span><span class="p">,</span> <span class="n">E</span><span class="o">=</span><span class="mi">3</span> <span class="p">);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The optimal theta value peaks around 3 as well (coincidentally), and begins to decline thereafter.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="System-prediction-with-SMap">System prediction with SMap<a class="anchor-link" href="#System-prediction-with-SMap">&#182;</a></h3>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[8]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">pyEDM</span><span class="o">.</span><span class="n">SMap</span><span class="p">(</span> <span class="n">dataFrame</span> <span class="o">=</span> <span class="n">tentmap</span><span class="p">,</span> <span class="n">lib</span><span class="o">=</span><span class="s2">&quot;1 500&quot;</span><span class="p">,</span> <span class="n">pred</span><span class="o">=</span><span class="s2">&quot;501 550&quot;</span><span class="p">,</span> <span class="n">columns</span><span class="o">=</span><span class="s2">&quot;TentMap&quot;</span><span class="p">,</span> <span class="n">E</span><span class="o">=</span><span class="mi">3</span><span class="p">,</span> <span class="n">theta</span><span class="o">=</span><span class="mi">3</span><span class="p">,</span> <span class="n">showPlot</span><span class="o">=</span><span class="kc">True</span> <span class="p">);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAYYAAAElCAYAAADgCEWlAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4xLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy8li6FKAAAgAElEQVR4nOydd5wkZZ3/30/nnu7JOzO7bAZ2WZYoWQUJImD2DCjmgP7O0/P0Tj3vTj30PM90qHenqBgQA4KKgoqiiICkhYXdJW1gc56d1NM51vP7o7q7nqqu6jAzO4n6vF7zmuqu6uqq6qrn83w/3ySklLhw4cKFCxcVeGb6AFy4cOHCxeyCSwwuXLhw4cIElxhcuHDhwoUJLjG4cOHChQsTXGJw4cKFCxcmuMTgwoULFy5McInBhQsXLlyY4BKDCxcuXLgwwSUGFy5cuHBhgksMLly4cOHCBJcYXLhw4cKFCS4xuHDhwoULE1xicOHChQsXJrjE4MKFCxcuTHCJwYULFy5cmOASgwsXLly4MMElBhcuXLhwYYJLDC5cuHDhwgSXGFy4cOHChQkuMbhw4cKFCxNcYnDhwoULFya4xODChQsXLkxwiWEeQAixWwiREUIklb//a3EfFwshnhRCxIQQI0KIXwkhFjtsq36PZvnut0zNWYEQ4oNCiPVCiJwQ4oap2m+Lx9BTvhYpIcQeIcSb62zbJYT4oRDiSPnvGsv6/yhf46J1nc2+rhFCFMrXNCaEeFAI8Xxl/UVCCCmE+JXlc6eV379Hee/VQoiNQoi4EGJYCHG3EGKlzfdU/mItXSR9PyuEEH8RQqSFEFuEEJfW2fYrQohnhRCJ8rZvt6y/RAjxePl4dwoh3tfq8biYHFximD94pZQyqvx9sMXPPwNcLqXsAo4BngWus9tQ/R5gr+W7fzKpszDjIPA54PtTuM9W8Q0gDwwAbwGuE0Kc5LDtV4E2YAVwDvA2IcS7lPXbgY8Dv2vyu28uX+MFwF+An1vWDwHPF0L0Ku+9A9hWeSGEOB64EfgnoBNYWT6nkvV7lL+uJo9PxU3ABqAX+DfgF0KIPodtU8Ary8fzDuDrQogXlI/XD/wK+HZ5/RuBa4UQp03gmFxMEC4xuABASjkopTyovFUCjp/Ivsqz0F8IIW4uzwofn8iDLaW8VUr5a2BkgsdxuhDiifIsdn2rxyCEiACvAz4lpUxKKe8Hbgfe5vCRVwJfklKmpZS7ge8B71bO54dSyt8DiVaOQ0pZBH4CLLYMtnng18CbysfrRR9IVXI+Hdglpfyz1JGQUv5SSrm3lWOoByHEauAM4N+llBkp5S+BJ9Gvnd35/LuUcouUUpNSrgP+ClSsoR6gA/hR+XgfBTYDa6fqeF00hksM8xxCiPPLUoTT3/nKtsvKMkIG+CjwpUl89avRZ7g9wE+BX5dngwghflvneH47ie+sQgjRBvwe+Cz6zPNnEziG1UBRSrlN2fUmwMliABCW5ZOn4FwCwNvRCXLMsvrG8jqAy4Gn0C2tCh4H1gghvip0uTDa4nc/Uec6fbO82UnATimlSniNrlNl/2HgbOBp0Cco6NbHu4QQ3rJ8thy4v5XjdjE5+Gb6AFxMGX4thCgqrz8mpby+PMttShoozyK7hBA9wHuBLZM4nseklL8AEEJciy5lnAf8VUr5iknst1m8AtgzyWOIAnHLe+NAu8P2fwA+IYR4B7r09G50aWmiuFII8Yry98WA15WthyqklA8K3Q9yAjpB3AiElfU7hRAXAf8I3AK0CyF+BnxQSpm0fE8FG6SUF5c/f2oTxxlFvy4qxgFbH5UF30InkTuV924Cvgt8vfz6/VLKfU3sy8UUwbUY5g9eI6XsUv6un+iOpJSjwA+B24QQE508VB9kKaUG7Ef3XUwXVk7BMSTRZQ0VHThLQR9Ct7aeBW5DH+D2t/B9VtxS1vsH0C2BMx22+xHwQeBidH3eBCnlw1LKK6WUfcAFwIvQ/QCm71H+Lm7xOFu9TgAIIb6MblFdKaWU5ffWoFt3bwcC6FbHx4UQL2/xmFxMAi4xzHMIIS6wRJxY/y5w+KgP6Kf2gW8WS5Vj8ABLKEscQojf1zme30/w+6wIT8ExbAN8QohVyn5Poyx7WCGlHJVSvkVKuVBKeRL68/XIZE9ESjkMvA+4RgixyGaTHwF/B9whpUw32NejwK00KXEJIZ6uc52+Vd7saeBYIYRqSTlep/J+PwO8FLhMSqlaZScD26SUd5Z9EFvRnfUvbeZ4XUwNXClpnkNK+Vd0U78uhBCvRX+Qn0WPLLkWXVIYneBXn1ne5+3oM+kc8HD5mJp6yMvWig/wAl4hRAhd8y/W/+TUHIOUMiWEuBX4rBDianRH7quBFzgc73Hokk8MuAx9ML9QWe8vn4sHnXBCQEFKWbLZnfVYtgoh7kSPavqIZd0uIcSFwE6bYzofOBG4TUp5pDwjfxW6RdgQZYJrtM02IcRG4N+FEJ9EH8RPxcH5LIT4F+DNwAVSSmtgwQZglRDiEvRIrGPRZcHJ+LtctAoppfs3x/+A3egSRlL5+1WL+/h7YBd6KOFhdHN+eZPffanlvWuAXwA3o8sJG4AzJnBe1wDS8ndNC5+dimPoQY/8SaGH5r5ZWXcBkFReX4lukaSBjejhv+q+brA5n3fWOf4fW947t3wc/cBFwH6Hz14N3FNePhn4DTBYvi92A18E/Mr3FCz3ThLob/E6rQDuKd+HW9V7Aj3M92nltUQnafX7/tVyHZ8q/277y8frmenn7Ln0J8o/hAsXUwahJ28dL6V863P5GFy4mKtwfQwuXLhw4cIElxhcuHDhwoUJrpTkwoULFy5McC0GFy5cuHBhwqwOV12wYIFcsWLFTB+GCxcuXMwZPPbYY8NST2acMGY1MaxYsYL169fP9GG4cOHCxZyBEGLPZPfhSkkuXLhw4cIElxhcuHDhwoUJLjG4cOHChQsTXGJw4cKFCxcmuMTgwoULFy5McInBhQsXLlyY4BKDCxcu5gZGdkAxN9NH8ZyASwwuXLiY/Xjgf+B/z4D/O9slh2mASwwuXLiY/Xj6Vv1/bA/sm3RTPBcN4BKDCxcuZj9ySWM5OThzx/EcgUsMLly4mP3Ip4zlxKGZO47nCGY1MTx9MI5bFtyFCxdmYjg8c8fxHMGsJgZNSsYzhZk+DBcuXMwkpIS8KyVNJ2Y1MQAMxt0IBBcuntMo5kCWjNeuxXDUMeuJ4XA8O9OH4MKFi5lEIW1+7RLDUcesJ4ZBlxhcuHhuQ5WRwJWSpgGznxjGXWJw4eI5DdXxDJCLQz5tv62LKcHsJ4aESwwuXDynYSUGgKQrJx1NzHpiODzuOp9duHhOwyolgetnOMqYEmIQQnxfCHFECPGUw3ohhPgfIcR2IcQTQogzmt2362Nw4aJFJI/A4NMzfRRTBzuLYZ4Qw40P7eYDP32cbYOJmT4UE6bKYrgBuKLO+pcCq8p/7wOua3bHLjG4cNEC4ofga6fAdS+AjTfN9NFMDez8CfPAAb1vNM2nb3ua3z1xiC/8fstMH44JU0IMUsr7gNE6m7wauFHqeBjoEkIsambfw8kcxZI2FYfpwsX8x857oFieTG2+fUYPZcowT6WkfWMG4W0/YnOOM4jp8jEsBvYpr/eX36uBEOJ9Qoj1Qoj1AJqE4WR+Gg7RxWzH9+7fxQu/cDc3PLBrpg9l9iKnSBLxgzN3HFOJeSolZfJG0t5QIjeryv/MOuezlPI7UsqzpJRnVd5zk9xclDTJV+7cyoFYhi/+YSslbfY8RLMK+flHDFrOZjY9D6KSUgoxZAol0+uZxnQRwwFgqfJ6Sfm9pnDYzWWwhaZJEtnnRi2pVL5IpqA/OJlCibG0a0XaQh1EU0NQnPvXqWRHDIm572NI54osFYNc7nmEIHmGErMnAnO6iOF24O3l6KTzgHEpZdO1c4+4uQw1yBc1Xvr1v3Lmf9zFbzbNj5lhPaRyRdPrEVdetIdJj5fzYmZdytYSg5wH51VIj/O7wL/y7cDX+ITvpvlHDEKIm4CHgBOEEPuFEO8RQvytEOJvy5vcAewEtgPXA3/Xyv5di6EWj+waZetggnxJ46ZH9s704Rx1WIlhODl7HqJZBevsOj73exfYSUkiMwaFuT0uREefokNkALjA8+Ssuqd9U7ETKeVVDdZL4AMT3b9bYbUWcUVCmk0zjaOFVM6sv86mh2hWIW+Jh483rdjOWsicjfMZ9JDV7uXTezBTCJmNV5f7xRgPzKLneNY5n+3g5jLUIqnMoEdT819WqbUY5v85TwjW2fU86HYm7cJVYc7nMnhysepyh8gQi43N4NGYMSeIwY1KqkVaGSjH0vl5H6WTrPExzJ7Z1ayCdRCdD5FJSrhqTEaM9+c46XkUiwEgPzZ7rLs5QQyuxVALNbRNkxCb51E6qbzrfG4KNT6GuU8MQiGG3XKhsWKORyb5CuOm13IW/VazmhhE+X8iWyRtGRjmInYMJXlwxzDaFMzuk9k8/+f/OvcEPsI5YvO8l5NcH0OTsFoMc3xWDeApGMSwSyWGOR6ZFCiYLQZfavacz6wmBp/XOLy57oDeM5LiJdfey5uvX8dPpiCKqG/0cV7hXccKzyDv993OyBwjhsf2jHHXM4NNS2A1PoY5dr7ThZoInnngfPYUM9Xl3dr8sRgCRXOgQDAze85nVhOD3yuqy3M9ZHXdjmH+0Xsz1/q/yaNPTL7ypT99pLq8TByZUxbDUwfGed11D3L1jev5+fp9jT+ADTHMogiOWYWcJSopcRi0uV1rzFtULQalxNoct4ZCFmJozw9NiZowFZjlxKBaDHObGDoO3c8HfbfxWu/9vOjITya9P1/eiGhYKEZnzBn7ly1HeOEX7uafbtnUdK2XR3cb9RYf2V2v9qKBZK7EGrGXj/pu5gSxl5HU7KotMytQzOGRFsm1lIf0yMwcz1RA0/CVFItBDhjr5nhUUlgzW3d9jDKemR2VDFximCYE43uqywvzu8kXJzeL8+YNfTIiciTGmxtgpxrf+Mt2DsQy/PLx/WxtsqZ8ImsMXslsc76jdK7At/xf5YO+27jO/zWys6y2zNHCnpEU2UKT52lXOgIgMXucmi2jYFQgzcgAh2WPsW6OF9KLWIhhQIwxNEt8Z7OaGHweRUqabmLQNNjwE3jk+impNyOUmOV+xkwldyeCoCWioRSbGS35kCLxNZtop9Z3soahOqGUGWeFR58hHus5TDuZeR+y+qOHdnPhl+/hwi//pTlysCa3VTCLol0AvnPfDt58/cOsb8ZaVCKSUoQYoQNNlseF9DCUZscMeyKISBtimCUS6awmBtViODIJ5/NwMsd3/7qTJ/bHGm9cwfa74La/gzs+Cht/POHvrsCTNQbyATHG7mGHbM4mYdUnZ2JWKKU0RQclmpz9myyGJonBmxk2ve4TsXkfmXTbRv03HYznWL+7ieQnJ4thFhHD/rE0//X7LTy4Y4Qv37m18QeUiKS0DFLCyzCdxvo5KidJKemQ5jGgnxjDiYzDJ6YXs5wYpsZi+PRtT/G5323mLdeva74a6aGNxvL+xyb83RX4lNC0TpFm7+Bwna0bI1Q0h7r5ZyDULZ0vkVMksXiT+uhEiMGXNQ+M/SI277Of1Uizpq6TU4bwLHLS7h1NU3ENNfVMWywGgCOyy1g/RyOT8rkMYWG+f/2iRHJkdvxWs5oYfFPkY9iwV7cUErkiu4eblHCUGf5UxEtbY5ZHDzcXjeOEiGa2GMIzEOpmjYRq1mJIZdJ8xf8tvu//Em2Z5q5tMG+WHfqY/xaDKpU1lcczBywG9Z7JNOMjUoghbUcMczSXIRO3l9FysyT7eUqK6B0tqBbDkbgehSKEqPMJe6g3Y9MWQ1aRnaZgVmKVflIjkyOGqEwaGYBANH/EeeOjBGvuRLPXdm38fl7vvQ+A3YXfAm9q+JlQ3mwx9InxeZ39XChpxBWibcrRrvgYMjJQnZHK+EFaf2qODtTfLNOU38Qgu7QM4vUIi8UwN4khl7QnBm18dpD4rLYYPELQHtK5K1/SJhSrn7HIHYkmpYupthhCJfNsrhibuMlYKGm0Y9Ynu0tTk1HdCkZT5hl7vEmLoSNnnPti7VBTSW7hotk/NN99DGOWez3dzH2rWAw75DHV5cLY/ik7rslCnUw051A3WwyLOkMM0m2sn6PEkE/YE4N3lmQ/z2piAFjYEaouTyT7eTQ9MblDKsQgU8NQmlxJjjaL9BPIHG4+DNGCdK5Ep4UYBmYgBto6Y2/22voLxgDWK+JN6efRkpkY+kVsXlsMVmss3ZTFYE8MYhb5GFR5rFCSFEoNwrYtPoal3W0MzQMpKZ+yDyYIpmeHz2TWE8OAiRha9zNYZ17Nyh2pcSMpSCD1NomTQLslNK2fGHtHJxaymsxkiArztRgQY9NeFqPWx9DctfUrmay9jNdkNVuhaZJ2zRye20ds1sR8Hw1Yr22rPoYDcgE56QfAX0zWZkTPEKxk3lBOypujkpb2hOeF87mUtieGSH5y48xUYd4Tw0QdpKW0JbR1MjMTTSMizWFoA2KMXRMMWc3FazNZF4g4o+Nxm62PHqzXNt4EMRRKGm1KmF4zFkMqX6QX88Cm+xjmLzFYZbJWfQxJGeawVCSXWdLJzXrPZBudl43FcEQ9rzlqMWjK+DLq7a0ud5WGKTayoqYBc4AYgtXliYSsWpvGNz2rLZgHovwkfAK51BgeYdbRJ0MM2aR9iYP0yPRGNNQ6nxuTbjJbpB3DUuoQGZJJh2iaMlK5Ej3CTHp98zxctcZiaNHHkCTEYZQs4VlSTG/Y4pdqzWIIsbSnjUE5930MMmNYDIeDK6vLA4zNirpns54YFnZOtZTUxAMmZY2zeM+enS1/dwXp8dqchX4mnuRWdIhoyI1OLtKpVUzEGktYiAEgH68fUZXKF+kRZqLuIUEqk5l0aZHZilopqTUfQ0qGTeUj0iOzwwFtPa+WiAFdSlIT3GRqCLQ5WBpFadIzHD62urxQjHJkFmQ/z3piGJi089lsITRFDPkkHswDzuEDu1v+7gqyNhEIA2KMXUP1Z8pOKDg4rqY71G0i4arxbIGoMMtqhUbEkCvSi9li8AhJD4lZMbs6GpiI81kqfoQkIXJho+DcyKHdU3VoE0ahpBGzPI8Nz0sNVyVETyRIIBBkRLYDIKQ2af/fTMCTM3xm8bblFPEC0CVSjMbGnT42bZhTxDCR0ttWi6EZHdwUqlpGcnjiprhdzHJE5BgamVj2s+bguPIkp1dHtmr8iWyxYcXTZK7WYpANyhqkk/GaLFGY3yGroxaZzNrBzg5qL4acpw1/9xLj80OT7wEyWVifRWjRxyBDhPwe+tqDcz6XwavUTiuFukj4DD9Dcnh6LX87zHpiUMNVjyQm4HyeSLiqDTF4Ukcm3D6z4CD9iOThCXWmU/VJFdNdFsM6Wy9qkmyhvrSTyBZpt1gMpOoTZCFhPyPsn8/EUONjaMJiyBoWg+ZvI9q31Hg9C7Kf7aLmGkpJSnXVNEFCPm+ZGOa2n8Gn+jBDXaSC/dWXsyH7edYTw4JogEqR1eFkvmVN2TqYN+V8ztQW2+sXMR7eObG69sWUffG+fhFrvkSHAqEc32GPcUO15aYvdC9bKNnKAI2ubyJbqLEYPOn6xKAl7df3zeNchhGLkzZdaDyBkIrsovki9C02nJrB9MwPnna/VWMfg+I3IUTI7621GOZgZJJaIscT7iTfZsh+2rhLDA3h83pYEDUik1q1GkZTE/Ax2FgMfSLG/dsnKP04zPAHmFhkkkcxQw+Hjqsud0xjDLRTzkQjqS6VShEU5t/Al2lADA4ach/jrsWgQpGStGA7S5cdX33dURhquo3q0YKV7KBxvSRpiUoK+jz0t4c4wtzOZQgqJXI8bd1o7UZnOjELzmfWEwNMzgE9oagkO2IgxgPPTowYpI0FAuXy2yOtE4NPcVwlO1ZXl7tLk6vY2gqsGngFjcpi5G2sp0CuQV3+lL2l1j8DSX3TgZImiVmy2JvxMXiUEtUEovQuXEqp/Ij3iXH2DrVQdv4oYCIWg1TILu9tw+MRtVLSHLQYwiWDGLxt3Xg7jEz1QJOFJY8mpoQYhBBXCCG2CiG2CyE+YbP+nUKIISHExvLf1a3sf6JJblLKGh9DplBqmIZfsHHuBkWRsZFBDsRar5culNC0WMBoZr5QjE7IYvArZmhpwZrq8gI5hlaantA9u9kfNCbegjVxEAjl6xODJ2MQQ8pvhGD2ifF52ft5LJ3H6sPPFrT6M34p8SilRkQwCl4/cY8xs969a8dUH2pLsIsga1hhVbEYNF8YgL5ocG7nMmgaIc04r2C0i1DP4urrSG76C2JaMWliEEJ4gW8ALwXWAlcJIdbabHqzlPL08t93W/mOhZ2GlNQKMaTzJVufRKN2kvmkvfTTL2I8MAE5yZs3ZvhjESNmuX+CDXsCSi8Gb+ciYjIK6PXcEyPT42R0ChNt5GMopmuzsyPF+k1ofFmDOMaiq6rLfSLG8Dy0GJz8JnUDFQoZPXQTyEk/waA+mcooIauD+yeeizMVsJWSWshjKPnaAOZ+VFIujged5BMyTCgYItK3rLq6szh9lr8TpsJiOAfYLqXcKaXMAz8DXj0F+61ioF0JWW2BGKxZzxU0nNU65An0TZAYfAoxJNoN3XdAxCYkJYUVYvBFehj2LKi+jg9NT6ibMzE0qHuUrbUY2hsQgyo1JRTprJ/YvCyL4WSN1Z1d581Zz20BPS6edkOiGD8ysyGrdpnqrUQlaf4IUCYG1ccw17q4Kc9AnDYiQS/RBUYE2QJtdMIFNqcKU0EMiwF1NNpffs+K1wkhnhBC/EIIsdRmPQBCiPcJIdYLIdYPDelOxwE1+7mFXIaxlP3stZGDtKZOUhn9xHhg+0jDWH0r1PIamS5jxjvAGMPJfHO5FQpUfdIf7WHcbxBDdmR6Hn4nbb9h1Fe2tphbhxajRjtRoPZiyPQY0pkuJU1zL/BpgBPp1q2XpCS3paRBDKFe41HLz3D57cp5LRFDXO55hCD5+nkMpQKekk6SJSnw+PVxoK89aKmwOqj3aJ8rUHyYcRmhLeDD02E4nwdEbMbv6+lyPv8GWCGlPBX4E/BDpw2llN+RUp4lpTyrr68PmLjz2epfqKDRrFZmjB9u2GuEg1bi5rcNtpaxrLbhzPecoOxvDJAty0kRzfj+UHsvSSUGOj9NMdCq81mtZxXP1L+2IlcrJfkomRsjWRBWLIpi5wpkWWtuEzmyqXjLRD3bURlA/RS52LOBJULXnOtWoTWFdYZpC+h9TDr6DYkilBlsvlHVUcBIMkeEDL8KfJpvB77GZ3w31LcYLAX0QuVz6okEyIsAMalbEGhFSE8slHxGoASjjBPRSTwYJSV0qSwoCowOz6w8NhXEcABQLYAl5feqkFKOSCkrI/p3gTNb+YKFE3Q+22VaQhOzWiXqZzC4vLrcL/QftNWwVVMEQtdiCHYAukO7i2RrDuhChiD6eeWll1Ck3VT6gGkqi6FaDMt7I9XlRtfWm3co/1wnyS1SNH4Pf3sfImoQYbccm/Y+FEcbFR/DP/h+yQ8CX+aPgX+mi0T98hE5eynJ12UY7wvFKFsPz1z57ZFUnjM8z9In9N/zPM/m+udkadIT8uvn5Pd66GkLzN1cBpPF0EakTHgxn2H5p2Y4+3kqiOFRYJUQYqUQIoDep/F2dQMhxCLl5auAza18gTojbYkYJmgxeJRZ7Wh4RXVZn+HDg60Qg5SElQiEUHsvtBuRSQNirLUkN8tsIxryU4wYl3e6ymIY3dskZ0dHqmTV6Nr6ivbWlkw6R2KovRj8Hf0QNYiwn/lXZbViMVzheRTQLaPTPdvrO58tBfQiwXLXXiUMcqEYZfOh6S3NXkGuWCKRLbJGGFJnl0jW19ItvRgqxAB2Dui542dQKxeMywjhMomnAsaEJzs6s0lukyYGKWUR+CBwJ/qAf4uU8mkhxGeFEK8qb/YhIcTTQohNwIeAd7byHZ1hP0GffqipfKlpc3iiFoMvbzw8iaiRPVqxGB7eOdK481QFhTR+9Ac6J/20RSK1xNCKA1p1XEndDBXKwx+cphjoisXwd97b+Nizb+FPgY/hp9gwj8HvQAyFhAMxFPNEy/0bSlIQ6ugFxWLoE/MvyW00lSdInhXC+C27SDWwGMwF9ML+WufzQsbYPEMWQ4Xs1ngMYuggTTZfh9QtBfRCPmO46msPWlp8zo5+E82gqITDJ0WEQPm88m3GfV2KzWwJE99U7ERKeQdwh+W9TyvL/wL8y0T3L4RgYWeIPSP6zHownqM95G/4OdXHEAl4q867RrNa1Vmc7jSiiBZ5dcJI5Uts2hfjrBU9NZ+tgXWGH/RBu+poGuPZFqQkLTVaZfMYUVYGfPi7pz8GuuJjeJP3LwAs8wxxqthBItvv+JmSJgmVUtW7rogHX7mKbT52mIDdhxTteIx2IiG/iVjnY1mMkVSO48RBfMKYfHSJZPM+Bhk2opJMTs1Rth6cmSS3ym90ojAkEo+QeOp1llMiklKKlAR6LsPQHE1yK6ZiVEavjLe9+n4pshDKSf4iObPEMCcyn8EcstqsnFSJSuoiwfsj91TN2ES9B0zTCCo+gWK3QQwViwHgge1NOrsUPXFcRmgPmge2floLWc2ljNDNpIji8QhT5ElnYahuhM9UIFcskShXSV3mMcpVdIlkXdJNZou0C+NhPyQMSajoVHpbqaM0Ktt1iUSVkuZhIb3RVJ7VwhxB1CWSTfsYUoRoq0hJgQhaUO9fEBAlBgcPos1AaYyRVB4fRY63nJcayl2DGilJsRg65q6UpLb1zPoMYvB0KtnPqZk9n7lDDJ2tl9+umK+f83+fD2au4+bAZ4mQqW8x5BPV5JOkDOFv7wev7uMIaWnC6N/dbD6DqidWYpatFkMsXXCUvawoKL0dUh79purs6iMj9fl2SGbBJvJnKlEhXFUvBl3uSOScZbp4tkCHUkDvsNd4EEpJ+3pIagG9UTp0R50qJc3DXIbRVJ41HrPzsbORlGTNY1Bm16LTsCg7C0PsG5tYr/HJYDSV41hxiIAwn0MgX8eCsSmgV0FfdO4W0tMUFSGnEENQKZMezs1sj4m5QwztigO6yRjfivP5hZ6nAegUaQ7pL04AACAASURBVI4TB+v7GNSIAdroaAvUzFABHt871rCJPZh7MSREFJ/XY7IYFgp9/a4mrYa8YjFUzNCe9iCHpNrG8ejqrZUErBM9e0zvd4lk3XDVRLZoatIzHFDSXRwK5and3WKiA69HQFSVksYZmkdSkqZJRlN5TrCQbrdI1Hc+m/IYwrQFFWJQJiK6A3r6/QwjyXzNRAIgWKwzibEU0LM6n+dsWQyFGAoBoxtdZIFBDB0FlxiawsIJJLmNpfN0kKRbGDOPXhGvbzFYkk86Qj5oN4jhrF59ECpqkkd2Nyj+BuSU8hrp8gxftRgqkU7N5jJoKdUM1cNeeyMBBhVikEe5v2/FEjvR8qB3iiTJnHOzHr3ktkEMoyFDAnMqva12d0tU6v6YnM/zy2KIZQpoElZ7LFISKVL1KqxaZteVPAbA5GdYKMZmJDJpJJXnRE8tMYSbJQaCNc7n2VhhtZmcGqGMMSW/YTF0Dhih8b1a64m0U4k5Qwz9LSa5SSkZSxVYLszatU4MzVsM7SG/yWJ4Qb/x2WaqreYV6Sfn02samaOS9NlD08Sg6JMFv04MIb+XYY9BDJmj3N+3QgxrrRYDKUqadJQ8EhYfQ7zNSL7yZe19NkVFSkr5KsQwf30Mo6kcHaRYLMzXQ/cx1LMYVOdziEjAmF3TYc5l2HJ4BoghmbO1GNpK9YjBHJUUVCyGfrueDDM4kG4bTPCiL/2Fv/nmgw2jHoWSJ1UKGucQ6VlESerNZ3pFnFR6+iW/CuYMMahJbs3US0rlS+RLGsuFeSbRQ/MWw7iM0BE2OztP6TIGoWYS3VRHU648wzdJIcTwoLFrpLmbQCrhqnnFDB339xnfM3p0iWEkmcdLiROEWQfvKltmTtfX2tYzEVlRXQ7k7IlB9TGkfbUWQw9xxpKtV7ydrRhJ5lklan+/TpL1S2JYLIawSgyqlMQoW2YgZHUkWes3AYhqSYpOod95JSrJKiVFQ2QIkZB6FjylPDj0PZkO/O/d29k7mmbjvhh3Pl3felEd7jJkPMPC62dUGPLY2ODMlTCZk8TQTFRSxZlrJYaWpCTa6Aibo4hWBBP4yi3lthxONJytqo6mfMVs9IcgrM/wfUKjl3jTFoMna9z8paBxU6VDBnkVjnJNnNGUHmMfEuaZURcVYrCfMSXTGSJCv14aglLH4uoMKViIQ9HGV6BITLlA2Sry+tHCeo9cr5COHd7mIuwcz6A3ic/UTXAz7p8k4Wo2LVBjMewZSZNswj82lcgnhlkkaqXXLpF0LothlZKUqKSOsI+A1zMrqqxKKXlohzGxGWpQCl4NhxehLtO6mNL7OTGDfbrnDDH0d6hd3HINQ+4qjudaYkjUNfXUgTwhI0QDZoshkB7ilCXGgLylgSNPbdJTUmb4Vj/D7uFUU5qiVzFDUczQfNggr6Od7DOSynOS2FPzfqfQH2SnJLdsSqkZ5W0jEgoxSoexgY2fQe3FkFfOVyh+n2hhpHFd/zmCkVS+xhKDclRSPYnCUkTPZDFYfAzAtJfG6Eo+a/t+Z5PEkCJEyKc41MXsadizczhlmiDWLdFSyODV9LEpJ334gm2m1amAYflnj7LlXw9zhhhCfi9dbXpaSEmTDDuUJq6gooMv99RKSal8ybHpidqLIevT8wRUi4HkYRYpjnCnshsVCEX6kUGVGMzZz4lcsanSDmpWthY2BkpNkaf8qaNLDKOpXE1EEhgWg1O1WLVJT8EXJRr0MSwVYrCJTFJ9D8WwMZsSFgf0fPEzjKbynGBjMXiENNXwskLtdJYRbdVKAUCNxQDw1IE6+QNHAQszRpMgTfkdu0iRzTtJSYqPwUp2wIJZ4oC29oKvSwwWRSISMucYZ5W6Z8XYzJXFmDPEAOYktyMNHNDOFoM+sDo161F7MeQrMcaKxUBikK42I0e3ETGodZekajZachmAphLdAgXjxvK2GbMl0aWWxZjEA1JoLNONJPM1EUnQ2MdQVIih6G8nGvIx0oAY/Ip0JkPGgGIOWY3Nmxafo8mcyWLQfMY9762TDCaV4oSaP4IQwlgZ7q7m4rSLDFF0LXy6kMmXOFYzJhJixQuryxOVkmD25DI8vNMskcXrEYOiIFRKbqtQ656Joxx2Xg9zixhaSHIbTRUIkq+azhVUiMFpVmsevCrOYoUYkofpUYnBoedDBX5lIBdhlRjMFgPQuMqqlKa4b0/YIIZQ1yKKUv852wpjUGxxBl3Mww9fCf+1GB79Xt1NR1P5mogkgHYyeNAcpToto1g7gXaiQR8jKFaUtcKqViJYUAawiFF90pzkNn9afBbHD9JVluQKvijFHqN/R7BeMphiMWiBiHmdEKZiegNirCViGIxneWTXaP3WonUwksqZQlXFiguqy100SwxmKQl0eXmmcxmklKxryWKwKbmtQO3L4EvPXAjunCKGhYqfoVFkUiydZ5moLbPQgz6zcprVqr0YtHJ5bCJ9QHkGlh6h2+CnhhaDP692W1NuYlNZjCZzGfIpvFJ/iDIyQLjN0Ce7o20MmczqFmcbz9wGu+7Ta9vf+8W6oX8yeaSa6Cd9bRDQLSuPkLSTdr62Su9rWSGGehZDZgxRzkIfl22EQ8bvr5K1bjHMD2KIxrdVl9NdqxGK7KJaiyZoGp6Cce+IQLR2G0uV1V3Dqaay7YcSOS699l6u/PZD/M+f7f0EjTCayJhLfCgWQ6dIOYfhKueUkuZwVbCxGGaAGHYNpzhimZTEMnWuqyVPKmKxGAJK7+dw1iWGpqA27DnSgBhGU/kaGQn0EsZhss4OaLVhTCWUzOsrk4OORV7DbG9EDMGSMZMzE4O5YxM0ISWp5XqJGKWV0ZPcDk8m+/nR643l5CAMPmW7WaGksSSvNJUfWAttxvfq9ZLsr62pSU+og2iogY9BKaA3IjtM52stpDdfSm/3JrdXl0sLTsSj3DOhgkPMf8FSUyhoU47QFLKq30cb9ze2Gu7aPFgl+psf3TehpKv04A7aytFoMU8P9Br1x7pIknUihkZSUnvQMhmafmJYt6s20qquxWBt0hM0k12bUvesozBz0XZzlhgaWQxj6TzLhf2Nokcm2d+MHsXBZwola68ti6F/T52boFQgqOkx9iUpCLYpg6ClTAHArkZ9GVQz1KJP9kYDHFbN6laynw9tgn3rzO9t/7PtpmPpPCcqEUli4cm6hl1GF86F9DyKDu4Jd9Ee9DGsSknWekkpS50klRjmaentRbld1WXPopPwKKQblQn7cu/WAnoWeQKosRgANu5tTAyqTHI4np1QDoQ8bEwyDoePA1+QrNCfZZ/QKKQdCC9vthhCVovBmuS272H45vPh7s/BwY3TkvBmdTwDjNcbEyxNeqy/ldpxr0cbnrGkvTlMDI2jkqxZzxX0EHcs9uY1ST/KTac4O7ulMUuoa46rjiYiRELKTE6VkpSyGHVnZMr+YuhRPRX0WC2GVqSkR66vfW+HPTGMWksbLDzFTAwi5UgMPiV+29fW2dj5bK2sqj5EpmY9Y/PCYpBSsqJkkG548SkIE+k6FNJTC+jJEGGLPAHYE0MDP4OUsmZG/JetrZd1D4w8U10ejeo+k4zX+N1LaYfSMg4d3Croaw+yX/YRl0rI55Fn4L4vw3cuhK+eDHd8HPZaJj1TBN2/UHvsiVzROZy+xsdg/q0W9C4gLctFO8mbwuenE3OKGNQw0QMNKkTq5TAUKUkYp9pTJ8ktYBq87C2GzqJCDPWkJGvJ7ZB1xqv7LfpEHB9FMoVS/XIfaqVWaTZDeyNBEzHI8SYthswYPPmL2vf3PGSaiVYwmsyzVs1hGDATQydJx6gMf9F40ANtnWUfg+p8rmMxVEpuV2CxGGZFvaTBZ+C3/wg3vw1++kb40d/AD14O330JfPtCfXn3A44fj6dyprLUwWMs1phTWQw1h4GwmUArcCCGehORfaMZDlmCPO7Z2npxt+i44jfpXgMYdb4AZNomY1lKS0kMc60k0H0MOQK8M/9x/uo5qxp5VUV8Pzzybfj+ZbDhJy0fdyPsGUlXlYv2oK963aWs0/MlY7b6rT6GUMDHEYznODE0My0+5xQxLO81Zgb7RjN1oyR0KUkhhoGTqosLnIhB0wiUjMErGFWkmaiaUGUMWLG6ZqNqMbSZZvh4/TWRNdAgMsky21D3Fw54GfUajspis72fN/wEiuWSEgOnQH/5OmkF2H1/zeZj8QTHCWXfA2trBi+7a6tpkqBmPOiBSBeRgI9hJcFNWqOSFB/DKB3m6xfqQisPBFGRJZmYmZkVoI8Ej1wP37kI1n8PNt8O2/4AO+6GPffD/kfg0EZ9+db3gWYftx8/tLWaTT4sunXfjUq6ImlfSK9eOYwKlE5ui736QDyeKdS93x7eVSuTPLZnzDGizwm9SnJbqW8tADm/UgrCrpRFMQtSv0456aOIz9ZiAHhcruZd2X9C+9gOuPJHcOobDf9g9cB/0NIxN4N1yvU5a0W3KYzd0c9gymOI2P5WY7Mg+3lOEUN7yE9PRL/4+ZLm6GeQUhJPZ1gslIFm8VnVxR7i9jd3Ll6NgonLMO1tahSMIf0Es8N6+Wf0+j/5okOCjmV2ELUks9iFrB6M1an7o0pJ0ux8BsgoZTFKsSayJjUNHv2u8fqcq+H4S4zXNnKSdmRLtbPYcGAJBNstPoaU7bVN5s11kjzhTjweQdavkG/K0mRIIYoRq8UgBDJiEKuo0zP6qCI9Cje/Fe74KJSasFri+2GPvdWQO2Bo8ft85ZayqmMfhwienColhWtmoYDJYljsMQbienKSnUxS0mRTxSONY0uwoKBPJArSi69ftxjyCjHY1jhS6iSl0ZUCKzGE/N6qFV7UJLFSENa+Cl77HfjYDnjrrSDKn9n/KMSntiuamr9w3rG9dIaNrpLOxGCxGIK1xJBU6p5lj3JBTCfMKWIAs9WwxyGKJ5kr0qcN4a80BYkuhC7D29/j5Hy2sLmpfagiJYnkIN1txrqYk5xUZ4av77M2ya2uNGVpIm6VDAoRg2hEMxEaO+6GsbKzM9gJp7wBjr/UWL/9rpqPBIafri6PRlfrC01YDIls0VRym3IosDcUrWqqopQzySJmH0NHzfmqZTEC2SHnYmxHC3segm9dAFt+a7y38BR43ffgTTfBW34J7/gNvPtO/dpW8OQt9vs7stlYDB+nLyjXtlskmrIYbJ3P0YGqnNqpxap9yOsSgzIjPv94I4ekJTlJOacd8hi6O/VQ2oJSBcCbszkGyzn5vaI6GVPRp/RpMdUo8vrh+BfDivON97b8rvnjbgAppcnx3DwxmDOfrT4GgGzYmPAUZij7eW4RQ3KIV/vW8WnfjbzGcz97HSqSjqUKrFBlpJ5joc24sR2lJOVHS8g2OlRiiKq1iA6bzMbRJoghLttsiKHWAV0vg1daQ90sN5WMGkTjTw86ShZVqCGqz3sLBCKw7PngL5Pv6E4Y3WX6SHvMeNCT3SfqCxa5wy5cNZEtmJr0ENRzH+qWxagXlQR4lOu3gPH6EWJTCa0E934ZbniZbgFUcM7/g/fcBae8Hta8DFZdCitfBMvOg7OvNrZ75jbbBMTA6JbqcixaDuk0+W9SZAr1fQxJGbIdbPSQa2PAqUxENjhEJh2IZdg/pv9eYb+XD15ihJjeu22o+bBVJex5i1zKgog+kJcChv/OZ0sMlhBcnw3ZofsZKrAtXnfiK41llcAnCdX/Eg36OOmYDhMxOOUySMvkzo7Ei8oET85Q9vPcIoatd/DOg5/h3b4/8DLvOnY7EYPVv9Cz0pSHoJfethlEaiqrqnHzavaz2WJwyn5WS27HidbeBHYWQx1i0JSbKinaCVicce3tHYxJfUbmkUXHrmj6F+2GbXcarysDly9onmVZ5KQFScORWOgr+yMsUpJds55Etmhq60lIJ4NoyG/JflaOWYlWqZGSoLZhz3QkuWXj8KPXwF8+V9XACXXBm34KL/uSXjnXDkvPha5yKGJ2HJ79Y80m7aqTtucEfcFijTW2GML2FgOYs5/Rr+3mQ3GyNpnHapjqmcu7OXtFT3XgayVsVR42LMwt2jJ6ovqESlPOy29X6sMakeRwTiaLIWkjLa95ubG8+37TPTUZqNbCWSu68Xk9zVkMyuQu42nH760dgoXyO/lSM1PmY24Rw7LzqotneJ5l70ht1AzoM3hT1nP3SlM5BceoJEtWoklKipqJoUchDScpqZAyboKsr91cvwbMPgYaWwwq0eT9HTXra3IZEnU01Ue/B2V/Cse9GHqPM9aZ5CSFGKRkcc5IbvMsOkVfsAxemqSmd0AiWzA16alISdGg19FikA2kpJqGPYlpCFn906f0DPEKlj0f3v+AeQCygxBwypXG6ycsclIhQ2dGj0DRpEDrLct0Si5NF0nSOZtzzKnRO6GapKkqlAHnnA79XipqkqcP1g7Mqn/h3JU9eD2CC1a1LidpSg7DDs9yI3InZNwzthndpgJ6tcltFfQr9dNsLYaOYwz/olY0T4YmAdUxf+5K3Vnc1daYGKQyxhQC7bbb+LvU7OeZ8Z3NLWLoXUWxXLp6gYiTH9phu9lYuV9AFT0roc3w9C9w6uJmtRhUZ7E/rOvwAFqRxUGlRaUDMRSV/sx5n81NYGMxjNbLi2hEDDXZzw7EUMjAhh8Zr895LwA/fHA3V/9wPVuj5xjrdt1n9EkY30dE6jO5mIwQ7Su3IrQkuEFtITHdx6BaDPq1dCyLIaVJSkr5OvV+2SosUV1H3WIYfAYev9F4fcE/wTt+C51LnD+j4lSFGLbdaZo9MrQVD7oFslsO0NlRvtd8AXIeXdrzCkneLhnMksfgaDEsPqO6eFnQGLDt5CTVv3Dusfqzc9EJxvVuKp9BSsQRw2I40rbKmBwpBSBt+z7XKbmtwtHHoOLEVxjLUyQnrTM5nvVnrqORxaCVqkmemhRofntiCPca91M0PzO9n+cWMXg8lBafXX3ZH9toq3WOpiwWQ42UlLCtriotPgGTxQAmOWmx3zClnUJWzU16agdys49B37ZuwpxyfKbeDmXUJLk5EcNTtxqO7M5lsOoyNu2L8e+3P81dmwf5xD0pQ/bIJ/VwS4DDT1Z3sVlbTm9F3zX5GPQH2mqRxTMFotj5GPyMqD0ZKmSQiyM0/bqmZRBf0FIYDmoqrDoNDEOJ3NQ0pvnjJw356LhL4JJP6dp9E7jpkb28+3dxUj1l+a2U08NaK1CctFvlUnojhg+rYcy/JY/B1scAsPqK6uJJ6UfxlR3QGywO6MPj2apMG/R5OG2pfq9duNp4hpoKWx3fVx0Ix2QUTdHO1QKQbXbEUDBHJVkjkipoihjWKH6G7X82RTw1RPwQbP0D3PMF+Omb4L9PpPTl1bwzeT2LGKEt4OXkxfr1UaUk21weZeKZJEw4ZFO6BOjsM4ihQ4tBaXqbKsFcIwYgsMKQk04ubbGdYY+lcmYfQ/dKCLYjvfoP0SZyFLO1MlRB6cWQ9kRrNHxVuljoUcpiOA3mSkG+os1AblcWo56UpJbrKFk6P0FFSmoi+1l1Op/9bvB4+ek6I176iQNxiitfbGxTjk7SDinEIJfRXRm8wma5A2SNRZZJxfEKncQLnqAeNQK0hxyS3EyOZxv/AtRISXbX7g9PHeKcz9/F2Z+7ixse2NWwwZMjnr3L8LcID1z2OV0eagKbD8X5l1uf5O4tR/hxWrHGVDlJmVlvlUurYdlgbuEq7TRytXtbPYuhfy106tF5gWKCM4WeX2AtjaFaC89b1kWwPFvvaw9ySnkQbCpsddDsX+hVBnFv1LhPbfs+q36TOlKS2cfgQAwLjoc+PUyWYsYxq7+K3ffrCYpfWQ3XroGb3gj3/Bds+z0kDuJNDfJe3x3cF/ww327/Lv6RrQCNfQzWUFWH36m3s52hshXtRdNrl00zpoQYhBBXCCG2CiG2CyE+YbM+KIS4ubx+nRBixYS/a9m51eUzPM/aOqCL8cOERblLkq9DjwUXwhSZFMiP1QwStr0YVJiiYIwf2UlKMjfpsbEY2hZU46y7RIogecYzBfuwS00zd2+zJvAAPZEgh2lgMex/DA5u0Je9QXje20lkC9y+ydi2pEl2dhkEXPEzFA4+UX1rp+9Yw3HmC4Jfn9H7hEaUTI3FoJYzz3uN6p+OUUn1CuhVP2xp1mOZMWYLJa65/RmkhEyhxDW/eYarrn/YMZrNEaUi/PHfjNdnvN2UMNkINzywu7r8/diZyEql3t33G7/RoFE2YqtmJoaCEsGjtnatoiZc1cFiEAJWXVZ9eZlfvw8OxDKm2fbDJv+C0gMDuOgEw2po6GewRCSp5+SLGPuNaDaO7AblMCpQo5K2Hk7y2B4H5/IaRU7aXEdOShzWSWHbHxoOyH5R4oLUn+Cb58FP38jSxCYqfjt7YlAqITgkt4E+wRtUJnjFZqsYTCEmTQxCCC/wDeClwFrgKiHEWstm7wHGpJTHA18FvjjhLzzmDErlw14t9nNosHZWHBjfXV3ORI2iVEJ1QBMnmXcevGwdQ8oMtUczbkAnKUmd4UubGT4ej23Iqm3YpZJ8l5QhQsHa6JfeSMBcn95KDMU83PsF4/XJr4VIL7/eeLCmJv4DpRPBUx5gDj8BySMI5UE/El5l2t5aL8kqMxTTivWkaKvRkEMhPWs5DNvYfIMYeokzmjQnB/7wwd01SZDrdo1yxdfv40cP72neenj8hzBUDiUNROHif6u/vYLRVJ5fbzQe7EF6iA1USFdWy5FIq5QUNQbRohLzr042qsg1GZUEJjnpcv+m6rKaz2D2LygTDczE0DBsVSG7zXIZC5RBPNBuLg5YUyzO4mMIOvgY1DI5w8kcr7vuId7wrQf58+ZB8++rhq1u+z2UHGSwu64xES3+cgj3uX8Lr/kWvP8hPh74V9Zpa8yf2/YHTr/rTfzY/3kiZOzHhIxZqrZNRAT8Xg9jHuP6JIemP8ltKiyGc4DtUsqdUso88DPg1ZZtXg38sLz8C+DFoiZEp0kEoxxp0wclj5AU9jxas0k4acgixc7lxooGkUmqT6AUtJN+jEG8o6iUa3CQf3xKmWRTkx7TPhUHNHWS3JQBIUbUNvKkNxrgkFovSSWG1Ajc+GpzmOTZ70VKaZKRKnj0UFEPsazgmdsIxPUaSQXpJd5+rPkDlnpJtddWkcGUfgERJ+dzun4OAwC+IMVyH2if0MgnjM+Mpwt84y9GCevzj19QTZBK50t86tdP8dbvrWPfaKOKtnH4y+eN1+d/xERIjXDTI3vJWTLjH+tQor6evEXvO1GOIMtJP4O+RaZZvxY0rq19zL85j8FpwAFg5QXgCwOwpLSPZWXJdcNe/d47ksiyc0gflANeD2cs6zZ9/PSl3c2HrVqlJMViCIWjZKW+nwBFk09BPyelVWkdKak7EuDq81ea3nt09xjv+eF6rvj6ffzisf16ZYJFp+n+NNBn7rv/WruzfY/CppuM12/8MfzLPnj3H+ClX4TTr2J/YAW3xE/mjflPc1XpP9BOMEejne99mpd51zWWkojQZndPlxFXej+nh2ubYh1tTAUxLAbUSk/7y+/ZbiOlLALjQC82EEK8TwixXgixfmjI3lSN951ZXW4bfKxmfVdWYdgeZQCrSXIz/3hCMfUI2gzkisUQyav1kmwGck0zF+SLOBGDWhZDv3FG7CqFWgro1STLAW0BHzGf0uUsflCfiR3ZAtdfDHsfNNadfTUsOZMn9o+z+ZBOYCpVb9gb0x2sFTz0jeridnkMHVFLMxjVzyCSNRaDZmrSYxBBu1MhPYuUZHe+AJqStOVRTP/r7t1BvExOK3rb+MG7zubW97+A4/uN435wxwhXfO0+fr2hjql+/7UGSXUsged/wHlbCwoljR89VPtQ35Y/0yj4dvhJePpX1XXPysV0RcwN4tVrG7CL+bdYDE4SBaBH1x17YfXlJR5dTqpYDI8o1VRPX9pVI+E0HbZayMKI7sPQpGCbXGKSksJ+LzGUe8haFkNxEKfqSEkAn3zFWv70kRfx+jOX4PcaN/G2wSQf/fkmLv7KPWzcP24OKbbKSZoGv/+48XrNK3Qrw2P+XjUaybfiXDxX/RQ+8KjpWVkr9jSUkuIyQludcxoPG0pHeMfv0TRJLJ1n51CSx/aMcdczg9yyfp9tDspUYNY5n6WU35FSniWlPKuvr89+o6WGA2/h+Kaa1b1540H39ynx+RYpyTqrNTeSsbEYFGII5gxiaEb6iYQcEp+aLYthrcroMFD62nrISP0BFIUUPH0rfO8lEKsMUAIu/Qy87CuAPqOt4NWnHUO4fLMeGs8ysshowVgtnQFslstNUgdQk+RWc22zyswyZBBDNOhjjCiaLD/QmVFd06+prGr/EHk7DGL1ZnRp4/B4lh88YBzvRy8/Ab/Xw2lLu/jt35/P3154HJXqCql8iX+8ZSOP7rbRpsf2wEPfNF5feo0+sDaJ3z91uCplhZVB4KEDJeTqy40N7/1SddEqI+kfNqzAQLF+zH9d53MFyndXiOGJ/eOUNHMZaauMVIEatnqPU9jq0JZqBNcuuZAsQZOUFA54icl6xKBmPoccLYYKVg2085U3nMZ9H7+Yq89faZIeD8QyvO2769jee5HxgS2/M1cG2PRTOPi4vuwNwuX/afs91jIYAPSthrPeYxyL2E8iW6wt8tmgSY+KrQsuq7bq7T6yjpd+8juc/tk/ccl/38vrrnuQq29cz8d/8YRzJNYkMRXEcABYqrxeUn7PdhshhA/oBGpLNzaJjlVGa8DjC1v0EgVlSClZWDJyGMIDRiq/WUpK1FgMai8Gr90MX5nd+9JHqjNsW4exxdHkNJA3XRbDJCU5RzT0RIPmJLdfvBsqhOeP6Obx+R8GIWqczm97/nJOWWIQ4qPZpSYrq4JntOWm2R9gUy/JYo0p19ajkG405KOElzF19pgeMVsMdDg6VNWyGN2lMZK5Il//87aqfHPK4k5edrJBviG/l0+8dA2/eP8LOHaB7jDXJHz4YI8DOQAAIABJREFUZxtrG6z8+TNGYbxjzoCTX2d7DE5Qyem9Lzq2avUMJ3OMHvcaY0MlemyrtqTm2nrVLm42oZ3SajHUmYkCJgf0ed7NtJElmSuyYyhp9i+stDXqmwtbHTRHWQGm8wr6PIxjhCCXUhZitjjUnfIYrFjUGeaTr1jLg594MR+7/ISq7JXIFXn9HZJiqEx2ycNwoKw2ZMfhrs8YO3nhh6B7he3+1f4U565UiLP/xOriCR5dsajJlbKU4a8n+QV7l/JHzSj8+RbPn2y3a9RBcqKYCmJ4FFglhFgphAgAbwJut2xzO/CO8vLrgbvlRHoEltG/5PhqWGaELOn9RrRMIlc0dW4L9CnE0KBekl/xCfjbzNoqYLIYRGKwfniatU6StbJqBXZJbg2kpHoWQ280wCA2M72OJbpWqiT73L7pYLXxy+qBKGcs6+Z5Sw1C3Lg/bpaTytgsl9ETsdS+V+QOOx+D2qTH26YQQ/k8avwMisUwJtsdpSSh6P39IsYju0a5Zb0hJf7zFWvw2BRfO2NZNz+++lwWhYp0kGIwluBff/Wk4Uzd9yg89UvjA5d/Xg8WaBIb98WqiWMBr4e3nbecU1XS9Z1la5VulctqiEGN4KmJ+S8VEeWy6ZoUSH+b7fma0LlEL7GOru+f79HDkP+8+QjbBvUB2ecRnLG8/JsWMqb7r689yMmL9d+r6BS2avEvACZLSAhBQhhBCIWkZZ5Y09azOWKonmKbnw9cfDw/e9951YzkWFbj9uzpxkaVPJJ7vwSpsuXTsVj3I1mwazjFl/6whb1ln1TI7+HUJcrksXsF+HRVoE+M00Wi/phAW12L4W+et5ibMQj8td6/MhAqsKynjdOWdnHRCX289nmLaydMz9oTSKuYNDGUfQYfBO4ENgO3SCmfFkJ8VgjxqvJm3wN6hRDbgX8EakJaW4HX62GL32Do2Fajb8D4yBG6yklWWQKmGblVSoqrg5dWIljuxaBJQSBiIyWFOqs/PoUUx4SNz9cwt6V7m9PAZlcWo6GUhPNsoydidkADekmA994Ni041va3KSFedswwhBKcrxLBh75heodKCzdpykyMRaNjFzVc0ZoB+hRgqZZNr/AzW7m1O108h6z4R45rfPF014c8/fgHnr6q1eCo4Zv0XeYi380TovWwPvZ1rt72E/OeXwbVr4SeKdbD21bD8+Y77scMNirXwitMW0dce5DT12h5Mw9rX1Hxui7a05tr62+uEdlpm1o7XyYrVxqBTkZNueNA45lOXdOqDTvKI3mToiytMzW4uWq3KSTZ+BkuoKujNpFQkPSoxWC0Gc1vPun6TOjhxUQc/fs+51Uncb/KGf5Itv4XhZ2Hdt4z3XvJZvZgk+oz/Z4/s5fXXPcjFX7mHb95jVFo4a3mPOc/J44UFq6svV4v9tcRgkYPr+RhOXNTBdZ/8MLluPdAmKrKse9kQ9338Ym77wAu54V3ncO0bTzf5zMin9EZRU4Ap8TFIKe+QUq6WUh4npfzP8nufllLeXl7OSinfIKU8Xkp5jpRy52S/82C7MchJpXVfatCIRBn0LjJ7VNXsZ6vzWfEvJAnT0WaZEYO+L2UgWhk0HtIaP0O97m0qbCyGRlLSuIw6WwyRAOs0gzQ55Q3wzt+ZiwACT+4f56kD+jkHfR5e+zw92/L0Zcbg9eSBcUorLzZ97rDsZpSO+lISZilJSklQIYaAItNVzmMYq8VglpKiTrMrhVj7RIx9o0bI6j9fscbuEzr2PQL3f9X0VlAUCRbier/syu/nDei+hRZwJJ7ld08a8tC7X6hHzZymzDA37ouZS2QA47KNQbprrLFgu0Fu7bI+MTQ9gCphq5d4NyLQTN0DK2Uw+OOnYFhP4OLeL1TDSuuGrRayhkyDbmG2Bbw1x5ZWiKFWSjLnMQStyaYt4OTFnfz4PefSHvLxoHYSSVme3I3uhFveoddQAuSy57Nz4HJ+tWE/H/7ZBs7+z7v4xK1Psn6P2f+xIBrgHy5dZf0ak5y02mNDDNaS2w1IvC3oJ3je+4w3Hv1u/R7Q930Fxqemsc+scz43i1S/wfztQ49Xl0tK/aThgCU4SqmX1IulJ0O9OkkqFGJYFlCIwTqYZ80Wg6Oe2GxZDFVKquO46okE+XnpQj6U/yA3r/oKvPZ624qfP1WshZefuojOsrm9qDPMwnJv7XS+xLZUGBYaJLy5LAvUI4ZOi8WQypdoV0pue8O1UtJwXYvB2cdgbfGpnpPqLzFBK8EdH6u+lB4/Gg7yy4X/bI5sawI/fngPhZL+AJ+9ortaMkG1xp48ME5p6fN1ia+MLXIZIGoshlCHcd92yIR5EFb9C41CVVUsPrP6PPSLGCeJ3abV567s0RPwnviZ8WZsb9USOH1pV/UZqQlb3XVvlbB2aQPsk/21DnUgo5T60KwZ3YXJSUlWnLKkkx+951wCwTbu0RQ5qZxxriF4497XcMm19/GRmzfx640HyRYMv6HPI3jJ2gG+/bYzefATL+bsFTZybZ8xEVkl9tfmMpjk5fo+hipOe2M1eZShLY5NnhjaCg/+b+P9NYk5Swz+JadVo286sgf0jEVAKv0D4iFLcTNFSuq1WgyWULIOa52kCpSZ9zFew8qoJyXZdm+rINxdDV1sFxkiZOwtBuv+6lgMJbzcrr2Adb6zbcs2JHNFbleSrt58zjLTenUA27gvBqteUn39pNRnv3WjkoS573MiW7AU0DMGhKDPg98rzD6G2N5qXHteekkQbk5KKmej+zyCj152gv32ABt+rLfaBPCFEH//GFveu4dTCjdyevbbvCD7P3zr5Jvgw0/phfJaQLZQ4idKXsg7X2DE2C/sDDHQof/W6XyJ7UNpOMWQrJxI1x8xBqFOUuTUEEU1IqlRqKoKjxeON37XF5flJNBDUs9a2g6/szn3crMbn9fDBYoT+k/PKFnCSqG6O7WzAVHrkwKyPrXUR6OopMkRA+j39Q3vPod7xDk1635WvJhHsktr3l+zsJ1PvWItD//ri7n+7Wdx+UkLa0vlVKBaDOJAXYtB76fSxDmFOnVyqOCR62u3kVL/rbSp60cyZ4lhWV8nT0hlJrdPL/Tmjxtx4+mo5YcOdqAJfYBpEzmyaSXDMWN2DJl6MahQCrcNqPWSGklJQQeiEaKmxaetxWBJcHOabagDtlPdpd9sOlgti72qP8qZyy1JTMssfobnfxC54gIe0dZwY1EPdaxrMVjCVRPZom0BPdCdkNGgz1xIr5JljJ7cBsLZR2PxMQC88eylrFxgU3QP9N/5z2oEyj9A93LWLu7kIy89lRjtHGQBX1gvufdIqOl6SBX8ZtPB6nU/pjPE5SeZJTzVYblpXwxe8CFYdDoHPMdwY0nX/XuspOsPkUEfWP2iRCalOKDVAnqtWAxgClu92GsQw8nHdBDd8B3T71CFMuhfttY4t98+UY5u00qw9ffV9/9Y0iNrFljvFyCnFpa0lvqwVldtEK7aLM5c3s1Vb72avDSuU1y28ZWiLut1t/m5+IQ+PnzpKn779+fzhw+/iPecv9IUausI1WKwk5IyZouhKWIAc5OnLb/VC/upePLnRsKemDyBwlwmhp4Ij2mGs4d9up+hLWkQQ7FzhflDQpAPGWa5UEIizRaDTWXVChSLQa2XVGMxWCIQHC0GMDdQEWOMpvK1pQZqopKcpCSls5wDMaiZzhWns4oai6Gth/Erb+XK/KcZppP2oK+2RIHFYkjmi9WSBLW9GMwSTzRkyX4+ohBD+X2n8yXcjSb036pDZOj2F/mHF9vovxXc819GKGznUnjhh6ur3vXCFVysaOf/dMsmfrPpIA/uGGbr4QRDiVzd9qFSSn6g1EV62/NX1JQKN13b/THdiv1/93Jl4BvslPp9UOPYR2/0VEE2rjh7LU16WnLSHndJdSA53bOzanFdurgI9yhVay78Z93XAnpC3pj+jF164kB1wN42mGTr4YQ+QSsnKWYCvWyQelRgzUQCKCjFAT1qqQ+tZMqEzhBoOly1GZy5ejmpZRdVXz+47P9xzVUXct/HLubxT72EH7zrHD586eqqBNg0upZT8Ogy7AIRpxhXrCgpa8aEpgMFBk6CZS/Ql7WiXqKlgkwM7lRKtJz3/taO2QEtTC9mF5b2hHlcGgOAtm8dHqAjY4QqShttuBTqhYz+g3kzygNmmeE7SklRNW7e0EWts3yZiVVV63oDOWByQC8XgzxUOolkrmgmp0xzeRFq5IcdMTy5f5wnD+j7Cvg8vPYMa5K6HvvvEXp8/7NHdEeyan3UzGihxvksJSTzRTpCfuLZIiscpCSASMBn9jEkjXDjEalbF44PkRDIaD8kdGnsYy/sor/DIZlw8BmzKX7Z5yBgZBkLIfjyG07jiq/9leFkjuFkjr+/aUPNbjrDfnojAXoiAXqjAXoiQRZEA2hS8kw5izzk93DVObXShOqAfmK/MVCovSTsBtGkp50BTSe0fELR4005DEHH/BZbhLtg+Quqs82LvBv5eeki3jjyTUPj718LL/oYHHgctpdDIbfeAee9n0jQx4tPHOB3T+gz2N9sOsgJGBbFjp4XIeM6cfTazLiLSnFAU99nhRRSMojEMyVSkoru1/8P3PkvsGA1V1z4iabLp9eFx0O8/Th6x3W/RTj2LFDOuSqkq07urPSTI9AaiZ9ztVG5YP0PdInT64e7P2eE2rYfAxd9Avi8426aPpVJ72GGEPR5ORg1nKLi4CZIj9JZ1J2WRekh0LOs5nNScUD7VfPV5HyOOEtJiuzTrtRLskpJat2llCfqWAQM0BvIl3G60KOqatqFqlJSHcdVj0lKypksj2yhxP/e/Wz19ctPWWTqXV1BJOjjhIX64C2lTiYqydgNXPjbqrPKkCgQJF+VkxLZosn5jKXSbLu1kJ6CUSoWg/OD61WsuDevdSAFKfWSB7Ksz6+4QA9DtWBBNMi1V57m+F2g56zsHE6xfs8Ydz49yE2P7OV/797ON/5iBD78zfOW2F5b1SG+5VCCbKFEOl+sOjoDPo+tbJb2GvJbXo35N5WnDhNuRUqCmizoF/ueoH+/0uXs5f+tD0BqOYmynwHgVacZ1u5vNh1AKlLTxojRInaBzWRCLR3vUysHWyKSgCmTkqroXAxX3giXfHJqSKGMdKcxWe1IGBGS1nBzoDXZb80rjZ7dycO6pHRwgx6pVMEV/2WSaSeDOUsMAF0LFrJD02fbQsvDM7+urjsgF9DV3lbzGRE1pIJg3ph5lZTKqgnanLNHlSiYNqVektVi0BRnWjFgHghrsMRoPnS6Rx9cTN3ISsVqOK0mBSnR5vigRALeamhftqBVE9g2H4rzmm88wB8VJ+FV59QSZ/U41Jj7fTFT/SY7qQMhHENWa5zPlpu3poubgtGyxRCt9xCpuSpOpZKfuc2sw770S47+gxet7uMH7zybq85ZxuUnDXD2im6O64vQ3eZvyuXgEbosZYfOsJ9j+/SBQW+rGa+5tnb1JdNeg1BMoZ2KjyFJqDWLAWCVQQwX+Z7i6x1GrgKnvVm3KABOeBlUbOA9D1R7J1+4uo/2MpGFxrYixnbr2wTaedxjTHjsJhMlpThgoKBYDCbHs25pTLXFcLRQ6DWCHhZklKh8iyIB1E1wq4EvAGe+03i97jvlnAWlPa/NRGeimLNSEsDy3jYe37OK4zxlZ8ymm6vr9sgB+m1uRq9CDOGC0n8hNUalCk7eb9OfuQJFSgpmDSnK6mOQygzBtkmPimOepzd/kRqrxX4iZMz7U26qBGHagvaDB+hySG8kwMFxvUbPcDLHjx/ew3//cRt5RR9/zenHcPYKm+zuMp63tKuaALdhb4xuZfZrazGATgzlgVmPTNIthlQ6TVDoyyXhxWupNxQN+UkRIiv9hITZUqoQQ92HSK12akcM+bTefa2Cc94LA9bK8GZcvKafi9fUVlEtljRimQKjqTwjybz+P5WrLidzRS5bO8DqAeeZ2+lLuqoVTDfti5mc/07XNuvvgHIFcakSg8ViaNqhWcGCVXojq7FdhGUG0uV6mKFOPdmrgvYBfQKz/xG9BtK2P8Dpbybk93LZSQv55eP7ucyz3th+1UsYHDesVTspyRuMUpBe/KKEr5TV8x/8oemxGI4SRL/hgF6Y222ssISvA3UT3Gxx5jvhr/+tW71qQUxvEF725ZYDJephThPDsp4I6+UJvIFyc/Z9D1fX7ZEDrLEx5f0dBjFEizE0TeLxCFMvhqJdG84KIguqg7g3O4afIgV8NTHLakE+za6Et4pgFPpOhCNP4xGSUz07GUkqJa9NMpJzclsFPVGDGN75g0fZNWw8aCG/h397+Vreem6t01mFGpm0cV+M0xQJxC70ELAppKdfE1MDJG+UsOV7/397Zx4mV1Um/N9b+9JLViAhZCErmJAGQlgCAhMCKJEliLjgwOCoICIjLqCoOMIoDnwojorD52gQ+UYFhkVFkEU2lZFOSCCEJJCYQAdIQpLu9N5d1ef749Zy7617q5fqVNXpPr/n6aerbt2quvfUvec9726ZToR3qWcKzvIKe6gjEgrkmwJ5YYtM8hQMf/4+tGQmvMR4OOUr/p/VD6FggAk1mYJwB/a/vxcLDxnD/2Qquq5tanZEUPkJhp6wLbSz0y4YnNE7Ewfq0MwiYpmT7Nm/YLUttS2iAMuclG3zuuH30PBRAD6wcBL3rW7ijGCjY9/dTxTXMhPREM0kmUjmXulqhvBBBecEFDfFVhHhg/INnA5JbbNMmCIFGkMkFCjsYd4f9QfDvPfDq791bj/pahg/0/s9Q0QPMezD9PEJVvV5R6BsUwd62niDttXlOPbRnmnW4+zFUEQwBIJ5Wx/52Pm9HT35xiBK9dttrYAp+YS9Btns1Bjc5TD6UUHtE7ddKCycUs/vP3cSHz9uWlGhADBzYo2j6NtL2/Pn42lKAo9CetbY9rbn39vr0QA9XxajcNyLldzOYRcMz94KN02D7y2AHx8PP10Gz30///rS6x11nSqBvTTG2jedLUn9xtYeweNo1tPtzGMYtMYADj8DAJMaYNGlhfvZu6DZeicvmTWBw+PNzA9sBaAvEIbZpzvPy8PHEI8EafGqsKqxKanmgOm5zOp62qySIlAQDj9ok1+WYz7pfD52hiOybrjQWjBMHZ9gs5pMiyr0JewITfZORClIcsvE29uiflR/K3ybs/PQaNb2T/6zejsJ9GVai6oQkZhPTL2dg/OVFBsCrztzEAZYQC+Le3IJBoSrls7m3stPYObEGp93OQkGJNcEHuA5W6G0oqakDPW2CquOJj3hwu/POuG8BEOxkts5xtiaMam0tfJseQN2rrdWuNkKqZMa4MiLin9WGThsUm2ub8DW3R1s2ZWf3P20Mbs93hHa2ePMY+i3sqoX05bYQogFlt9a0IcAsHonT8jY0FOdsOVPgNVx7PJJG3O7vZ48mr5IrcPv5nXNxMKuqro5weAs8wEMuVZSuamNR3hd5SP90jsynflc/Z59M/n7Y8Z7LetClvff4lnZoFS0FgzTxidRBFjtoTW0xAvDMAFHhVV7FzexrfDFqw2nHVsYbEMk36Mot8p3RTjV+IW+2pniFAx77Y3NHZ2f/JPbshw2Kb8qnzEhyb2XHc/nl80pbo7xwO6Atrf+9AxXhQLnc7ZIYZ+tF4PycMTXFNMYqOs/euPQUzJNVYqMcygGZ/lMeGUmGgpy2KT8uf7JVoTOa2UN0GeP4Onx0xgGUUTPTigKK+6AGSdb/w8+2n9fn+ik96bz9cruaTuCPR09pDIatGfeC5lmPf1pDFkfQwm1kspJMCD8PZAPU+5+K1NMcChZz16IWKXzF34Ezr0dZp/W/3uGgNY+hppoiAk1EVZ1zuHUoLNhT2eyMIYccGoMtLKz21rV2nsxBOL9aAwHL8p13Toy8DpgdcTa09HDdJIDL7ltZ+I8UqEEoVQHB0ozat92IFPTZYDJbVk+duw02rrTJCJB/vH4aUNenTQc4u2c9jcl2bu4teer1zrMaoWTf22ukF7huO9RtRza32QXDFk3C0Cq25ose1qtiJ3uNmuimTgHxvhHYZWbhVPG8FKTNS7ZDnpQRBuL5X+LsL2LW0G46hAnnLlnWn/9MW+51dUOrAznTMRc3U7L99CnhAe6GjjY1ufDT9jFIwFavDQGWx5Dh4oSCsjg7fEVZHt4OmRcjul3Mn2vXf2e+yugV5QJs+C8n/S/XwloLRgApo5LsKppjmPbO2osyRofP4HLlPR6ZvIK2/oFhJP+0TqAI7z0sPSm3ONci0+XT6BfGzlAIEjHhIXUvfNXAA5oeRk4y/Pz+lsVJqMhrl42p+g+A8GuMdgZiClpDG1sz5iSAraQSvEQDFnB+a5LY0grsTSkwdxEoaj1Z+thUI0sPGQMdz1f2PbTb2zF1h8k2msTDN1Os8ugYuOHwuQjrUSq1resbntvPg97tyGZbm0vqlnsYgy/sLU09TuneDhEk7KZWX1MSbr4F7LsjM3ICYbAu5ksfpcVYdARSWVGHzHsw7TxSdb2zcy1wQPL8TzOw/EMQLSOFPl6SR1trZBOEbH1Yoh69WKwM+mInNlicupNy8kE7MkmpbkiEAYkGID0pLwKP7Vjff4Fd3JbKauNQTCxNsrBYwpbWbrr6udw+RiyGkPQ1gApGPcQDLlmPc5xb6aGPgL+Jbc1puEQ72vMTxuTRL6QXtze3rPHnscwROfzYAgErMiYLBt+7zApZWsjbbEFPXiFqkKR9p6DbOtZbexN5iOEons3FZbDGIDWX2n0GnEPpo1P0EGMV1XeTPBG3wGeEUkAiNAeyq+Ee1t3OnoxtBKnNu7z3izhuDNbOZOUltMYXDHLAxUMoWl5TWRWKu/Mc2oMNUOPaBgCR051ag1edfVz+ISrhlL5Gz2UKNRCsoLOUUiPfJ2kITvqqphDJ9R4Xhd+k6i9WU881Zqvy+8qu73fBQM4/QzrH4TNT+ae2rOds/gJu3g4SLOjpWsmDNcRrhrVJlQ1S7pmEvuUtaAK9bZarVvd/Z6r/JoeEYIBoLEvn3G4RU1mXNLfEdkZyU9g6dZ3CyIG6uIDcRbnJ/EjA1aZib1epqRiJbddJGbkcxcOV1vo7ck4oAcZlTScuM1JvmYk8AxXLdakJ4tfuOoeMlnPZTzfchEIiKPVZxa/8Y3Fk3Qp67oM05u3w/e4w1XLMFbTTsxHMe3bbkUoAUycx5FHLirY3dfHEA7msoABT1NSxzBWVi0X9YkIrylbyf+drxZYEcoiwEtArxH3YOo468L6aer9vNZ3MOv7pvGb9MmMLTKB9UTyarlq31lg//PttmbHLhgy9Y08TUmD0BiC9ZN4G8sHEpceWt/I9LLucvkYyrjacGsMvo5n8GjW00tnb5qkyjsTQ4nCydCzWQ95QVHtavdQWegSuuGg+DaISkRCztV1515I9UDaWoykVIBuwoMrszBUQhFHa9Ac85bzgYWTCjb7mR7jkUDhOUFBW0/dfAx18TCb+myCYdeGgoAUozHsZ6ZnNIbtTGRZz828v+fb7Kbe38cA9MbygiHQsbug5LZvZVU7rvBSoc/blKQSg1rxbgrlNZ+ebZksU5cGUk6N4T2T6wnZmssPWGPA0hisAnr2Okn+zueshpBlT3+VVTVnoUtjGJvwL3WS8LLHF8T7S/mcmnZzkm3b4ZPqcrWgsvhHJYV8fAz2ktuld28rN/XxcHGNYQBJqpVGe8EwLhlxTbzWjeXrYwD64vnIpGDXnoFXVrUzdnouJ6JeOjhU3s5XIHVHJQ3QlASwLZ6v4RPI9s0dZLjqcBILO2PufcthAERqUWJdUjXSRWdXV6aAnn9lVcgnuKUIsdc2UWR9DuXUkMqJW2MoJnST0VCuKidgXRPdTsfzkMosDJVZp+V7NADUHQyTj0REHBVXoYjGEA7S7DinzH1TEJWk1zRVHw+zyS4YdqzLnVNayeB6c1cIvUbcAxFh6rjCzOdiN5myhaxGu4eoMYi4/Ayv5+sluXwWtYNY8e6onZ97HN/5YsHnFevetr+wm5P8Vn+AFbHiKqXc3OFq0uMRrhoMSM6hbvcz5Jv0jEzBcFBdjANq85NmsbFN9qMxdJTL8ZwlWmslFmaZd1auiNvyI5yCwT9cdSAlMWLD2qSnHNTHw2y0m5Lefin3cB9WUm61L3a0FwwA0ycUCoaxRZzPAbtg6Nnr0hgGKBjAYU46Ul73zXwezMTWNv49udDb2rYt0LYr52hMqYAVq17mifJDiw4hGBDCQeHM+QcV3VdcIatvt3T1qzGAd2RSruR2lavdQ0VEHFpDMW0sEfUwu5Q7h8HN8VdYBSXDCUf7yVkH1LAoUzG2NhbyvD/B6vfdSpy0ypjPeloh3evR1lOv339MPMIuxtCcdayrfNWAXMntKtcYqltsDZCsA9rO2CKmpHCtradCqtnRbW3fIKKI3BrD3g6rJae4ersOxpRUW1PHBjWV+bLV2mALBbRMCVJ2++T8g+v521eXku5T/t3Rsrj8DG81d3JMPxoDWH6Gna3dNPbN4djABtIEWKOsePCRqjGAFfX1WKZHxkF1/oIh7qor1Ne+h0C9zZSkKmCeOPQU+MJGK6HQVSjyhx89ivtWN3HirAm+jtZAQIiGLRPZuEwuEJ3NBUX0dBMM9fEwIGxSU1gsGx2v7cMSktXufK7uoxsgWQd0ltpYqGhdoEh9XjDUpvbS095M9pbsDtUQDAywrvnBR2H5NBRz5Q3C6U7ae9Iku2xtPQcZRTQuGeHFvlm5SpW8/njuteyKsRITpV98fQGuyKS3mjuLNunJkjW3/TB1Lh84+QRuXxfgzR1WscJqv4lK4WPHTuWRde/Q3p3iw0UaJwUDQnsgP3bpjj0EHBpDvKz5LTlqCntWABxUH+OKU2f1+/Z4OEhzqoZxkhUMhU51HX0MAK/1TWFxwCkYhtSkpwLoNeI+THUJhmLaAkBsTL46ar1qIWXrtuZVFtqXaK3VExdUxzBoAAAgAElEQVQIZvoo7G3vcfgEUuHagQsaLMGwps92Q21+Ivcw2+CjquP63RrD3naSYuVjKAQi3uOb1ao6ibFt+gd5QeUbnlT1+ZbImESE3155Ik984eR+K992BvPaVrp9jyuHofodml4kIqHCekm9+kclAU4HdIasxjCifQwiMk5EHhOR1zL/PYsMiUhaRNZk/h4q5Tu9mDbeaUoqlsMAkBybt5OPUfvoszXp6bepjhu3n6GtHenJl9dQPhOhH+OSkZwJBYCOfH9fLeyTjiS3dlr25pvK9AQTloPaA/vk39aVor07lXte7aF9w0F//TEAum0NpPra97iynsuU3DbMxMKBvC0erEZLrtwM3TSG2lgIEW/BoMU9TOkaw7XAE0qp2cATmededCqlGjJ/Z5f4nQVMqos5ei+MSxR3HkeSY+hR1g+TlG5ofSf3Wl+xJj1euDKg25rzE/k+EiT7K6/hYlwywhY1iX0ePSay4YpVPQG4ezK05MejN+QvJO3msdZup2AYyRrDYOh2dHHb6+zFQJmjkoaJeMRVFmPf9tzDjkxuhm5RSYGAUBsN8Vqfl8ZgnWu1/1alCoZzgDszj+8Ezi3x84ZEICAcMjZf7K0/jQERmiV/k0X3bc2/1l8vBjcuB3S7bSLcpxKDClUFSzAoAqzpK2zV16ySxMPBQZmmyo7LlGSvQ+XVpCeLfZxau1K09+QjOapaEJYRZxe3vQ4nbdtQ+j1XAQU9GVqacg/bc/2e9Tuv+kSYd6ljj3Je89kFX7UHVJQqGA5USr2defwO/l1wYyLSKCLPi0hR4SEin8rs27hr165iuzqwm5OKZT1n2RfI32TZyqoAwYSnNcyfCXPoCljfPVFaCO18OffSYJPbIB/z7TAn2T6v2i8otympxhaq2ufjeAYc47SnvZt0pslLJBjw7sQ3CumzdXELdjUXhKvqKEBj4aAzcS/bmxt7W0/9fv98ZJKzL0z2XKvdH9TviIvI4yKyzuPvHPt+SikFKJ+PmaaUWgR8FPi+iPh2rlZK3aGUWqSUWjRx4kS/3QqwN1SfUNt/BE1r0FszCHrU8ilKIMA7dfmktIk7ns09blGDr2sUCwdJRIK86NWVToNyvW6NwZ7cpoqY6WqiefPfOy357nVVf75lJO3o4tZSEL2jo8ZQUOrDQ2OIaqgxjMmYkDe5zElZjaHa+zH0O2sppXx7x4nIDhGZpJR6W0QmATt9PmN75v8WEXkKOBLYPLRD9uajx07lobVvEQkGClLyvegIjck108iSVkJssIIBaB67EJqt1obT9vw1t33fEDQGsLSGtXu9NIbyZz0PGpePwR6qKjH/sbWP087WrtzjqteQykg4VkO3ChGVFMF0F7TnNeo2FWe6hmNVaErK+xg6yWoM1T2JeuEXmdRCkmg5S5cMkVKP7iHg4szji4EH3TuIyFgRiWYeTwCWAOvd+5XKzIk1PP+VpTzz5VOZ7NFcxk13pNBktI8ktQMpue2i88Ajc49rU84oosH6GMASDHuoY1ufM0Z8ME1/KoarJ0Ot5E1JwZi/Kck+Tu+02ARDtQvCMhKPukI7m/Nml3ZixDWcQC3nsz0qKR8I0q706vdsp86Wy2BHh5LbULpguAlYJiKvAadlniMii0Tkp5l9DgMaRWQt8CfgJqXUsAsGsJKABuqY7YmOK9i2TyUG1ovBRd/BhTXoYWg+BrD7GZwJQi0qWfWJMe6eDPZyGF5NerLYNYN39tk1hio/3zJi1Uvytse3qbiWYxVz10uy0aGz8zmnMRzs2L5PgyY9UGLms1JqN7DUY3sj8M+Zx38BFrj3qTQpW4XVLIOqk2SjbuyBbOk7iEMD7zi2D7bkdpas83xN30zOCf4lt72ZGiZWu8ZgMxfV0UG95B37YY8mPVlqXFFJWYwpKU9BTwZbIphVsVO/sSro4mYjpzFoLBj2UkdL5CDqe96hW4XYpeqZrIEA109HGyZUorBZ/D41wCY9LsYkwrzoWt1DxjQ1RFMS4MyAJuvMrvKLKhgiHbGczAFRHCx5O3i4iMbgN+5VbzorI8mo/+q6YiUxSiTh1oJsdGR8DDqayOptlof7Jn2etgOP4YbUx2kjoYUAH7WCgaSPxjAEU9LYZMQ3imgopqRsHsYrajopsR73KGtlpcMKWtmiZw6xCQa/OkngLwB0ULvLhdXYxnsSrUgRvWHAClf1E3ZZjUG/acouGP43tIg1p/2KX6aXAWghwPUb8WEi6FH8a59K+rZWLEYyEmQdcwo/j6QjDHOgZNtn9hDmdwd+mo7wOP4jdR7duJsSVSdiywWZYhcMPpVVAV8BOlJLbg+FpDtL2IalMVT/teEmHgnSR4AWj0z/fB6DfteAXTC0dPbS3pM3j+qw2Bm1giFSV5gjsY8EtUPwMYgIO+KH0qmciXVDzTuwNzZ5KHYOtx35MP+RXgFoclEl8o79CZLPfPbrxQD+GoMOGlK5SEScHe6y9KggvYS0iHZxkzUTNXucV0cuj0G/acopGFJ0OjL5q/930m/Eh4l47bhcvaQsLUP0MQDU1yR4SR3q/DyS1A5BY7ALht3tPbQ56gZV/0Vlb9bjoIjGEA0FHL2lsxjBkCcZ9Ta7tGOFZ+toSsoJBs/z0tf5PMZWr22fS2PQIXps1AqG2niYva7m8x2B5JAvwjGJMC+6nMX7VKKkcFWAve09dOhWN8hPMBTRGETEc6x0sMeWi4Is4QzZCVRHU1Is8/u2ePhOOnJ5DPpdA3ZfZXNHDx3det3Do1cwxMLsVs5M3N7wICur2hibiBQIhhaGlpBmFwx7XBqDFivoIQgG8DYnaXG+ZcIKVy2cQNuUvhpDoqjGECUgEA5WcdFIH2qjoWwLbNp70uzrypdZMKakKqY2FmK3cmoM6cGW3LbhjkxqVklShIYkGOpi4VyiXlt3iuZsL2n0UEOJ+4SlFjElgbdg0MHZXi6SkZCvxhAMCFENM4SzwszTx6Csfs8D6VVRbQQC4siJetuWzW80hiqmNhZiD86JatBNemyMTYTZyVjuSJ1Fq4rzw9S5BAMypFC7QEAYa7NRNu3NZw9rsYL20Bh6A1EIFve3ePl3tDjfMpHw8zGoGAlNJ9C8j6FQE7LaemqwEPLB7oB2lHnRYHE3au+6aCjIXnEKAilFY8hkK3879TG+k/oIigD18dCQb9ZxyQjvtlmagr1EhBYraC/BEKqlPze8lxDQ4SYqF0mfPIY24tVfKsWH7MTvlbjXSVTLOklZ7ILhrZb84k6HhD19R30Y6Ag5TR6BwfZisGHvM60yw1rKJG73MyhbMXMd7JNegiFVpElPFuNjKE4sHKBd4vS6ounalZ69GKC4KaldjRyN4e1mvSoGG8FgIzSEkttZxiYL18PDJRiG6zPLhodg6BtA72tPU5KmE97+QERIhAsd0G3o2b0N8gsdL1NSBzEtezFksQuGzl6Tx6AN3dF8vaSUChBLlG5KsjOUUNUsfoJBi5Whh2Ao1qQni3E+908iGiowu+japAfyoajeCW5R4homt2Wp9+k9r8M9rO+oDwO9ttLb+0hQN4CWoH54CoZSNAaPz9OmzaVX3+x+IpIAz/IhutrO9xdeZTHaVVyLycaLQCaayn1OXSpMmuCIMSXZ0UGIazDL7D+6EgflHu9QY4ec9Qzl0Ri0ccSGY6SCzmZJwYEIBtd4hYNCVMPkpv2JVyG9No01BrD8DF5aEOiZ9ZzFTzAYH0OVk6qdwn+mzmJb3wHcljp/SL0YstTGQgVNgmpKWMWN9RAMOq0KUxGnv2Yg/ht3uQ8dbqByk4wUhqzq7HwGK0qnxeVjyLf11HeKMhqDptTGQnwn9TFO7vk+j/Qtpi4+9JsrEBDGuC6EUjSG8clowTad7O19LnNSsV4MWdymJON4LiQRLUxya9fY+QyWxtBLiLZMCQywt/XU97yMYNAUdyXVoVRWteNe5ZcykXtFOWllb3c5oAekMbgEqTamszJS0N6TjClJ47HyKqSXr6yq73n5C4bqX/CMasHg7r1QiikJcGQrg39XsoGgu8ZgL70NIANyPrsFgz7nWy4K2nuScT6H9R2reC7JLS/w2tXINCXFwoEB96WvJPqO+jDgnrhLMSUBjHE5oEuZ2Lw0Bp1MK7E6V+vUAYSrun8PnQRhufCqsDoSnM/gDFntGKHOZx20BRj1gmF4TUnuENNSJrZoKFjwfq3MBe5chgFoDG5BqvNkt79IRAvDVTuU3qakmEe9pFxUks4+Bo88Bl2u6VEuGPITUUBKr/0/Jjl8zmcoDFnVagXtFgwDKFBoTEn941VhVXuNwaNeUucIMCXVREK4rUa6aP36jvowYNcQamPhkqtTujWG2hInNrczWxc1FPAQDP2XxHALBq0EYZlIRIIF5SOsqCR9xypfFiMvGEZCHkMgII6GPaBPz4xRLRjsE7lfCYrB4E5yK3XFO75AY9DjogKGZEoKBsSx8jUaQyFW3+e8kG1TMdIEtdYYspP/ur7puW0b1SGZ1/Seotx+Bl0i7fQe9RKZOj7BGe85kHBQuOSE6SV/3hiXTbHUFa9b0Gi1KizQGAZWh8o+ZqatZyHJaJA2EvwqdQppJaxMnwFodm24yK6iH+lbzNOzruHeiVfwYHoJoLfGAIWCQZffqaSjFJELgG8ChwGLlVKNPvudCdwGBIGfKqVuKuV7h5P//PgiunrTw3IBurWOUsJVAcbXjBAfQyAE4bj/vjZqYiF2tnYDRmPwIjuxXJv6FN9K/WMuekdnjSHrY+gjwAsTz2dDupVedgAjUTDocT6lagzrgBXAM347iEgQ+BHwPuBw4CMicniJ3zusDNfFN5zhqlAoaLSaKOO2PIZYPQzQf+PQGHQ63zJh16KyQsHaru9Y2RvXdPam6U7lS1TrLhjcPgZdNIaSBINS6lWl1MZ+dlsMvK6U2qKU6gF+BZxTyvdWK/aJPBYOEA6WJnfdzmytQhLrJsOM91qPF35kwG+zCwatNKQykfAZE12cml7Yj72jJ02XrXeBzh3cwMPHoMnvVI5RPxh40/a8KbPNExH5lIg0ikjjrl279vvBDSfjkhGOO9RaKb9v/qRh+Tw7Wk2UIvDxB+Gql+CMfxvw2+YfXJ97+7yD+o9kGm34mSJ0cWp6YdcYunrTdPX25Z7rrjHoakrqd6YRkceBgzxeuk4p9eBwH5BS6g7gDoBFixapfnavOn75iWPZuKOVww4aetOfLIXhqnpcVDkCARg7bVBvueLUWYxPRph9YA2HTuy/Hehow+8a0DkRzK4xdPakHd3OdBcM7sKafhpftdHvUSqlTivxO7YDh9ieT8lsG5GEggHeM3noLULtFIar6nFRlUJ9PMynT55Z6cOoWrx8CYlIkIAG9Xf8cPsYHKakkRauqsnirhyj/gIwW0RmiEgE+DDwUBm+V3vcGoNxxhq8/EzaaZIuYgWCYeSakuKjwfksIueJSBNwPPB7EXk0s32yiDwMoJRKAZ8FHgVeBX6jlHqltMMeHdTFQrkVUzAgo0JjMBQnEiyszqlLpIsfdlNSV2+abofzeWQJhlGhMSil7ldKTVFKRZVSByqlzshsf0sp9X7bfg8rpeYopWYqpQbuiRzliAiffu9MIsEAFx8/XfvVk6F0RKRAQ9BdY0i4o5Js4apRzU1JBeGqmizu9DjKUcznl83hilNnEdE8bM8wfCQjIVq7UrnnOoeqgtPH0N6dojdtxZyIQFTz617XqCS9R32UYISCwY7bz6Bzchs4/Qh7O3pyj6OhQMmFLSuNu/S2EQwGg2G/4J5ctNcYHD6GvOM5PgJMp+7S27oIcSMYDAbNcDubdXFo+uEnAEaCTy0QEMbZ2vSWWj+tXBjBYDBohlsQ6BIC6UcwIJ7m0pEgGAD++aQZhIPC+UdNYXxNYS/3akTvK8pgGIW4I1t01xjA0hp6Un2Obbo7nrNcdvJMLjlBr6jCkTHyBsMowi0IdHFoFsPLnKTTRNofup2LEQwGg2a4fQy6xMYXw8uBrns5DJ0xI28waMZIS3AD7xW1bqvskYQRDAaDZrhrZuleEgO8hZvu5TB0xggGg0EzRqLG4O1jMNNTpTAjbzBoxkgUDMaUVF0YwWAwaEaB83kEmJK8nc9GMFQKIxgMBs1wt/EcCRpD3MNspHtlVZ3RbqnR29tLU1MTXV1dlT4UAxCLxZgyZQrhcLj/nQ3DQqHGMBIEQ+E5jIRaSbqinWBoamqitraW6dOna195UXeUUuzevZumpiZmzJhR6cMZNbgLsY0MU1LhORhTUuXQTlfr6upi/PjxRihUASLC+PHjjfZWZtz2eK92n7rhGZU0Qkpi6IiWI2+EQvVgfovyU+BjGAEr63hk5BbR0xEtBYPBMJqxm44ioQChoP638UivlaQb+l9RFaCpqYlzzjmH2bNnM3PmTK666ip6enpYuXIln/3sZyt9eDzwwAOsX78+9/wb3/gGjz/+eAWPyDCc1MfDLJ4+DoBlhx1Y4aMZHrzzGMz0VCnMyA8SpRQrVqzg3HPP5bXXXmPTpk20tbVx3XXX7ZfvS6VS/e/kwi0YvvWtb3HaaacN52EZKswv//lY/uczJ3DbhxsqfSjDgpcDPWo0hoqhdTjD9Gt/v98+e+tNZ3luf/LJJ4nFYvzTP/0TAMFgkO9973vMmDGDG264gTfffJNTTjmF7du3c9FFF3H99dfT3t7Ohz70IZqamkin03z961/nwgsvZNWqVVx99dW0tbUxYcIEVq5cyaRJkzjllFNoaGjgueee4wMf+AA/+9nP+Pvf/04gEKC9vZ158+axZcsWVq5cyR133EFPTw+zZs3irrvuYs2aNTz00EM8/fTT3Hjjjdx3333ccMMNLF++nA9+8IM88cQTfPGLXySVSnHMMcdw++23E41GmT59OhdffDG//e1v6e3t5Z577mHevHk8/fTTXHXVVYDlT3jmmWeora3db+NuGBiRUICjpo6t9GEMG54+BlMrqWIYjWGQvPLKKxx99NGObXV1dUydOpVUKsXf/vY37rvvPl566SXuueceGhsbeeSRR5g8eTJr165l3bp1nHnmmfT29nLllVdy7733smrVKi699FKH1tHT00NjYyPXX389DQ0NPP300wD87ne/44wzziAcDrNixQpeeOEF1q5dy2GHHcZ//dd/ccIJJ3D22Wdz8803s2bNGmbOnJn7zK6uLi655BJ+/etf8/LLL5NKpbj99ttzr0+YMIHVq1dz+eWXc8sttwBwyy238KMf/Yg1a9bw7LPPEo/H9+fwGkYpxpRUXZiRH2aWLVvG+PHjicfjrFixgueee44FCxbw2GOPcc011/Dss89SX1/Pxo0bWbduHcuWLaOhoYEbb7yRpqam3OdceOGFjse//vWvAfjVr36Ve23dunWcdNJJLFiwgLvvvptXXnml6LFt3LiRGTNmMGfOHAAuvvhinnnmmdzrK1asAODoo49m69atACxZsoSrr76aH/zgBzQ3NxMKaa1kGqoU43yuLrS+y/3MPfuTww8/nHvvvdexbd++fbzxxhuEQqGC8E0RYc6cOaxevZqHH36Yr33tayxdupTzzjuP97znPfz1r3/1/J5kMpl7fPbZZ/PVr36VPXv2sGrVKv7hH/4BgEsuuYQHHniAhQsXsnLlSp566qmSzi0atfrRBoPBnG/j2muv5ayzzuLhhx9myZIlPProo8ybN6+k7zEY3JhaSdVFSRqDiFwgIq+ISJ+ILCqy31YReVlE1ohIYynfWWmWLl1KR0cHv/jFLwBIp9N84Qtf4JJLLiGRSPDYY4+xZ88eOjs7eeCBB1iyZAlvvfUWiUSCiy66iC996Uus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
"
>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Determining-system-causality-via-Convergent-Cross-Mapping-(CCM)">Determining system causality via Convergent Cross Mapping (CCM)<a class="anchor-link" href="#Determining-system-causality-via-Convergent-Cross-Mapping-(CCM)">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h3 id="Sardine-Anchovy-Temperature-Data">Sardine-Anchovy-Temperature Data<a class="anchor-link" href="#Sardine-Anchovy-Temperature-Data">&#182;</a></h3>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[9]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">sardine_anchovy_sst</span> <span class="o">=</span> <span class="n">pyEDM</span><span class="o">.</span><span class="n">sampleData</span><span class="p">[</span><span class="s1">&#39;sardine_anchovy_sst&#39;</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[13]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">sardine_anchovy_sst</span><span class="p">[[</span><span class="s1">&#39;anchovy&#39;</span><span class="p">,</span><span class="s1">&#39;np_sst&#39;</span><span class="p">]]</span><span class="o">.</span><span class="n">plot</span><span class="p">();</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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1KlTmTZtGh0dHRw9epRTTz3Vs/+qVau4//776e7uZurUqSxZsuS4/Hxq0ywVleOEkpGHyra9A3woHf2E55P74diOxB6zcBIs/lPEzYK1oQXo6upi69atrFy5kptuuomdO3cG3f8vf/kLTzzxBPPmzcNsNmMymXjqqac4++yz+eUvf4nT6aSrq4v58+fz97//na1btyb0xwyHmpGrqBwHbA4XLV12IIxGrkorfUqwNrQAV199NQCnnnoq7e3ttLa2Bt1/3rx53Hvvvfztb3+jtbUVnU7HzJkzee655/j1r3/Njh07SEtLOy4/iz9qRq6ichxoMFs9/w/tWvEO5INUWokic+4rQrWh9e9pE6rHzf333895553Hxx9/zLx58/jss8849dRTWblyJR999BE33HAD9957L9ddd13f/RAhUAO5ispxoL7d4vl/aNeKt0auZuTHi9dff51FixaxevVqMjIyPIMk/Nm/fz+TJk1i0qRJbNy4kT179pCUlERRURG33norVquVLVu2cN1116HX67Hb7ej1+uPyM6iBXEXlOFDf0ZORR6ORD9qMfABiMpmYNm0adrudZ599NuR2jz76KMuXL0ej0TBhwgQWL17Ma6+9xp///Gf0ej2pqam88MILANx2221MnjyZk046iZdffrnPfwY1kKuoHAe8A3lo14p4XKeR1MrOBFNSUuKziHnfffcBsHDhQq699loeffTRiMd4/PHHAx67/vrruf766wMef/jhh3n44YfjuOLYUAO5ispxoMFHWgld2WnQaTBqNaq0ohITaiBXUTkO1HdY0UjgkkP3UbE5XBh1Gow6rSqtHCe+/vrrgMeee+45HnvsMZ/H5s2bxxNPPHGcrip21ECuohIFL66tZlReKvPKcnu1f32HlSEZSRxu7fYpxffG6nBh1Gkx6TUhqz9V+p4bb7wxYbM0jxeqj1xFJQr+9tU+/hWmc2Ek6jssFGcnA6EzcqtdZOQmvXbQaeTxjpT8vhHr70sN5CoqUWC2OKis7+j1/vXtVoqykoBwBUFOjHoNJr1mUEkrJpOJpqYmNZhHiSzLNDU1YTKZot5HlVZUVCLgcLrotjupbemmy+Yg2RDb28bpkmk0WylIN2HQacIWBBl1Wkw67aBa7CwqKqK2thZ1oEz0mEwmioqKot5eDeQqKhHotIqgKstwoKGTicOCF4yEoqnT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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[17]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">pyEDM</span><span class="o">.</span><span class="n">CCM</span><span class="p">(</span> <span class="n">dataFrame</span> <span class="o">=</span> <span class="n">sardine_anchovy_sst</span><span class="p">,</span> <span class="n">E</span><span class="o">=</span><span class="mi">3</span><span class="p">,</span> <span class="n">columns</span><span class="o">=</span><span class="s2">&quot;anchovy&quot;</span><span class="p">,</span> <span class="n">target</span><span class="o">=</span><span class="s2">&quot;np_sst&quot;</span><span class="p">,</span>
           <span class="n">libSizes</span>  <span class="o">=</span> <span class="s2">&quot;10 70 10&quot;</span><span class="p">,</span> <span class="n">showPlot</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span> <span class="n">sample</span><span class="o">=</span><span class="mi">100</span><span class="p">);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>This CCM results is interpreted as 'anchovy predicts sea surface temperature', as you would expect (since sea surface temperature drives anchovy population size), and the reverse direction predicts poorly since anchovy population size obviously does not drive sea surface temperature.</p>

</div>
</div>
</div>
  </div>
</body>

 


</html>
