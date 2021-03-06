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
<div class="prompt input_prompt">In&nbsp;[17]:</div>
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
<div class="prompt input_prompt">In&nbsp;[18]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">tentmap</span>      <span class="o">=</span> <span class="n">pyEDM</span><span class="o">.</span><span class="n">sampleData</span><span class="p">[</span><span class="s1">&#39;TentMap&#39;</span><span class="p">]</span>
<span class="n">tentmapNoise</span> <span class="o">=</span> <span class="n">pyEDM</span><span class="o">.</span><span class="n">sampleData</span><span class="p">[</span><span class="s1">&#39;TentMapNoise&#39;</span><span class="p">]</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[19]:</div>
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
<h2 id="Evaluate-optimal-embedding-dimension-(via-Simplex)">Evaluate optimal embedding dimension (via Simplex)<a class="anchor-link" href="#Evaluate-optimal-embedding-dimension-(via-Simplex)">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[22]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">pyEDM</span><span class="o">.</span><span class="n">EmbedDimension</span><span class="p">(</span> <span class="n">dataFrame</span> <span class="o">=</span> <span class="n">tentmap</span><span class="p">,</span> <span class="n">lib</span><span class="o">=</span><span class="s2">&quot;1 100&quot;</span><span class="p">,</span> <span class="n">pred</span><span class="o">=</span><span class="s2">&quot;201 500&quot;</span><span class="p">,</span> <span class="n">columns</span><span class="o">=</span><span class="s2">&quot;TentMap&quot;</span> <span class="p">);</span>
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
<h3 id="The-optimal-embedding-dimension-is-2">The optimal embedding dimension is 2<a class="anchor-link" href="#The-optimal-embedding-dimension-is-2">&#182;</a></h3>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Evaluate-the-optimal-theta-value-(how-nonlinear-the-system-is)">Evaluate optimal theta value indicating state-dependence and extent of nonlinearity<a class="anchor-link" href="#Evaluate-the-optimal-theta-value-(how-nonlinear-the-system-is)">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[23]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">pyEDM</span><span class="o">.</span><span class="n">PredictNonlinear</span><span class="p">(</span> <span class="n">dataFrame</span> <span class="o">=</span> <span class="n">tentmapNoise</span><span class="p">,</span> <span class="n">lib</span><span class="o">=</span><span class="s2">&quot;1 100&quot;</span><span class="p">,</span> <span class="n">pred</span><span class="o">=</span><span class="s2">&quot;201 500&quot;</span><span class="p">,</span> <span class="n">columns</span><span class="o">=</span><span class="s2">&quot;TentMap&quot;</span><span class="p">,</span> <span class="n">E</span><span class="o">=</span><span class="mi">2</span> <span class="p">);</span>
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
<h3 id="The-optimal-theta-value-peaks-around-3">The optimal theta value peaks around 3<a class="anchor-link" href="#The-optimal-theta-value-peaks-around-3">&#182;</a></h3>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="System-prediction-with-SMap">System prediction with SMap<a class="anchor-link" href="#System-prediction-with-SMap">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[24]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">pyEDM</span><span class="o">.</span><span class="n">SMap</span><span class="p">(</span> <span class="n">dataFrame</span> <span class="o">=</span> <span class="n">tentmapNoise</span><span class="p">,</span>
            <span class="n">lib</span><span class="o">=</span><span class="s2">&quot;1 500&quot;</span><span class="p">,</span> <span class="n">pred</span><span class="o">=</span><span class="s2">&quot;501 550&quot;</span><span class="p">,</span> 
            <span class="n">columns</span><span class="o">=</span><span class="s2">&quot;TentMap&quot;</span><span class="p">,</span> <span class="n">E</span><span class="o">=</span><span class="mi">2</span><span class="p">,</span> <span class="n">theta</span><span class="o">=</span><span class="mi">3</span><span class="p">,</span> <span class="n">showPlot</span><span class="o">=</span><span class="kc">True</span> <span class="p">);</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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Lw0NDcydO5dLLrmEzs7OnD/r+eefZ+XKlQA8/vjj3HrrrWmPbWlp4d///d8Tr999910uvvjinL9boyklQiYtQecwFBctGHIgFAqxadMmtmzZQiAQ4K677rK8r5QiGo1m/bnnnXceN954Y9r37YJhwoQJKeU5NBq3YjEl6V4MRcXVtZL4Tu0wfnbroA479dRTee2112hqauLss8/mpJNOYsOGDTzxxBNs376dm2++mZ6eHo499ljuueceqqqqePLJJ/niF79IOBzmlFNOSXzWunXraGxs5Kc//Sl79+7lqquuYteuXQDceeed/OQnP2Hnzp00NDSwYsUKPv/5z7Ny5Uq2bNlCd3c3V199NY2Njfh8Pn74wx9yxhlnsG7dOh5//HE6OzvZuXMnF154If/yL/9CJBLhM5/5DI2NjYgIV1xxBV/60peGZSg1msEQ8ienI21KKi7uFgxFpr+/n9///vecc845ALz55pvce++9LF26lAMHDrBmzRqeffZZKisr+cEPfsAPf/hDvva1r/HZz36W5557juOOO85S4sLMF77wBU477TQeeeQRIpEI7e3t3HrrrWzZsoVNmzYBJCqgAtxxxx2ICJs3b2bbtm2cddZZ7NixA4BNmzbxt7/9jYqKCmbNmsW1117Lvn372LNnD1u2GAFiLS0twzhSGs3AaOdz6aBHPwe6urpoaGhg0aJFTJ48mc985jMATJkyhaVLlwLw8ssvs3XrVpYtW0ZDQwP33nsvu3fvZtu2bUybNo0ZM2YgIqxevdrxO5577jmuvvpqwPBp1NZm1o5eeumlxGfNnj2bKVOmJATD8uXLqa2tJRgMMmfOHHbv3s306dPZtWsX1157LU8++SQ1NTVDMjYaTa6YfQxaYygu7tYYBmnuGWriPgY75lLZSilWrFjBL3/5S8sxTn833MTLaUOypHZdXR2vvvoqTz31FHfddRe/+c1vuPvuuwt+bhpNHJ3HUDpojWGYWLp0KX/6058SJa47OjrYsWMHs2fPpqmpKVH11C444ixfvjzRXS0SidDa2pq2nDYYvo546e0dO3bw9ttvM2tW+kbxBw4cIBqNctFFF7FmzRo2btyY87VqNENBUJuSSgY9+sPE2LFjWbduHZ/85CeZP38+J598Mtu2bSMYDLJ27VrOPfdcTjzxRI466ijHv//xj3/MH//4R+bNm8fChQvZ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
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
<div class="prompt input_prompt">In&nbsp;[14]:</div>
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
<div class="prompt input_prompt">In&nbsp;[15]:</div>
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
<div class="prompt input_prompt">In&nbsp;[16]:</div>
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
<p>This CCM result anchovy::np_sst is interpreted as 'sea surface temperature (np_sst) influences anchovy population', as you would expect since sea surface temperature can influence anchovy population size.  The reverse direction (np_sst::anchovy) indicates no link, consistent with the fact that anchovy population does not influence sea surface temperature.</p>

</div>
</div>
</div>

</body>

</html>
