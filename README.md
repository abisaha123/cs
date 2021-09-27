*, :after, :before {
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}
body, html {
    margin: 0;
    width: 100%;
    height: 100%;
}
body {
    background-color: #2a2a2a;
    font-family: OpenSans,sans-serif;
    font-size: 16px;
    text-rendering: optimizeLegibility;
    line-height: 1.42857143;
    color: #333;
}
body * {
    text-rendering: optimizeLegibility;
    -webkit-font-feature-settings: "kern" 1;
    font-feature-settings: "kern" 1;
}
.lds-facebook {
    display: none;
    position: relative;
    width: 80px;
    height: 80px;
}
.lds-facebook div {
    display: inline-block;
    position: absolute;
    left: 8px;
    width: 16px;
    background: #fff;
    animation: lds-facebook 1.2s cubic-bezier(0, 0.5, 0.5, 1) infinite;
}
.lds-facebook div:nth-child(1) {
    left: 8px;
    animation-delay: -0.24s;
}
.lds-facebook div:nth-child(2) {
    left: 32px;
    animation-delay: -0.12s;
}
.lds-facebook div:nth-child(3) {
    left: 56px;
    animation-delay: 0;
}
@keyframes lds-facebook {
    0% {
        top: 8px;
        height: 64px;
    }
    50%, 100% {
        top: 24px;
        height: 32px;
    }
}
.verify {
    transition: .3s;
    animation: enlarge 3s;
    -webkit-animation: enlarge 3s;
    -webkit-animation-iteration-count: infinite;
    animation-iteration-count: infinite;
}
.errorMsg {
    text-align: center;
    display: none;
}
@keyframes enlarge {
    0% {
        transform: scale(0.8)
    }
    50% {
        transform: scale(1.2);
    }
    100% {
        transform: scale(0.8)
    }
}
.status {
    display: none;
}
.successText {
    color: #43d133;
}
.errorText {
    color: #d13333;
}
#wrapper, #wrapper > div {
    height: 100%;
}
#wrapper {
    background-color: #2a2a2a;
}
.generate_main_platform {
    margin-bottom: 50px;
    text-align: center;
}
.generate_main_platform h1 {
    margin: 20px auto 0 auto;
    text-align: center;
    color: #fff;
    font-size: 28px !important;
}
.generate_main_platform ul, .player-stats ul {
    padding: 0;
    margin: 0;
    list-style: none;
    text-align: center;
}
.generate_main_platform ul li {
    display: inline-block;
    margin: 10px;
    background: #fff;
    width: 30%;
    font-family: 'BurbankBigCondensed-Black' !important;
    font-size: 26px;
    position: relative;
    -webkit-clip-path: polygon(0 10%,100% 0,100% 98%,0 95%);
    clip-path: polygon(0 10%,100% 0,100% 98%,0 95%);
    color: #000;
    transition: .15s;
}
.generate_main_platform ul li:hover {
    background: #21aadb;
    color: #fff;
    cursor: pointer;
}
.platform-active {
    background: #21aadb!important;
    color: #fff!important;
}
.generate_main_platform ul .platform-active::before {
    color: #FFF;
    content: "";
    position: absolute;
    top: 0;
    right: 0;
    width: 50%;
    height: 100%;
    background: url(../css/img/btn_hover.html) no-repeat 100% 0;
    background-size: 100% 100%;
}
.generate_main_platform ul li:hover > i {
    color: #fff;
}
.generate_main_platform ul li i {
    font-size: 42px;
    margin-top: 15px;
    color: #21aadb;
}
.platform-active i {
    color: #FFF!important;
}
.holderInput {
    position: relative;
    display: table;
    border-collapse: separate;
    width: 350px;
    margin: auto;
}
.icon {
    background: #fff;
    border: none;
    font-size: 23px;
    font-weight: 400;
    line-height: 1;
    color: #757575;
    text-align: center;
    padding: 5px 0px 5px 15px;
    width: 1%;
    white-space: nowrap;
    vertical-align: middle;
    display: table-cell;
}

@font-face {
    font-family: 'Burbank';
    src: url('BurbankBigCondensed-Bold.html') format('woff2'), url('BurbankBigCondensed-Bold-2.html') format('woff');
    font-weight: 700;
    font-style: normal
}
body {
    font-family: 'Burbank', sans-serif;
    color: #FFF;
    font-size: 32px;
    background-image: url(../img/bg.html);
    background-position: top center;
    background-size: 100% 100%;
    width: 100%;
    height: 100%;
    /* overflow: hidden */
}
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
    font-family: sans-serif;
    -webkit-text-size-adjust: 100%;
    -ms-text-size-adjust: 100%
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
    display: block
}
audio,
canvas,
progress,
video {
    display: inline-block;
    vertical-align: baseline
}
audio:not([controls]) {
    display: none;
    height: 0
}
[hidden],
template {
    display: none
}

a {
    background-color: transparent
}

a:active,
a:hover {
    outline: 0
}

abbr[title] {
    border-bottom: 1px dotted
}

b,
strong {
    font-weight: 700
}

dfn {
    font-style: italic
}

h1 {
    margin: .67em 0;
    font-size: 2em
}

mark {
    color: #000;
    background: #ff0
}

small {
    font-size: 80%
}

sub,
sup {
    position: relative;
    font-size: 75%;
    line-height: 0;
    vertical-align: baseline
}

sup {
    top: -.5em
}

sub {
    bottom: -.25em
}

img {
    border: 0
}

svg:not(:root) {
    overflow: hidden
}

figure {
    margin: 1em 40px
}

hr {
    height: 0;
    -webkit-box-sizing: content-box;
    box-sizing: content-box
}

pre {
    overflow: auto
}

code,
kbd,
pre,
samp {
    font-family: monospace, monospace;
    font-size: 1em
}

button,
input,
optgroup,
select,
textarea {
    margin: 0;
    font: inherit;
    color: inherit
}

button {
    overflow: visible
}

button,
select {
    text-transform: none
}

button,
html input[type=button],
input[type=reset],
input[type=submit] {
    -webkit-appearance: button;
    cursor: pointer
}

button[disabled],
html input[disabled] {
    cursor: default
}

button::-moz-focus-inner,
input::-moz-focus-inner {
    padding: 0;
    border: 0
}

input {
    line-height: normal
}

input[type=checkbox],
input[type=radio] {
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
    padding: 0
}

input[type=number]::-webkit-inner-spin-button,
input[type=number]::-webkit-outer-spin-button {
    height: auto
}

input[type=search] {
    -webkit-box-sizing: content-box;
    box-sizing: content-box;
    -webkit-appearance: textfield
}

input[type=search]::-webkit-search-cancel-button,
input[type=search]::-webkit-search-decoration {
    -webkit-appearance: none
}

fieldset {
    padding: .35em .625em .75em;
    margin: 0 2px;
    border: 1px solid silver
}

textarea {
    overflow: auto
}

optgroup {
    font-weight: 700
}

table {
    border-spacing: 0;
    border-collapse: collapse
}

td,
th {
    padding: 0
}

/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {

    *,
    :after,
    :before {
        color: #000 !important;
        text-shadow: none !important;
        background: transparent !important;
        -webkit-box-shadow: none !important;
        box-shadow: none !important
    }

    a,
    a:visited {
        text-decoration: underline
    }

    a[href]:after {
        content: " ("attr(href) ")"
    }

    abbr[title]:after {
        content: " ("attr(title) ")"
    }

    a[href^="#"]:after,
    a[href^="javascript:"]:after {
        content: ""
    }

    blockquote,
    pre {
        border: 1px solid #999;
        page-break-inside: avoid
    }

    thead {
        display: table-header-group
    }

    img,
    tr {
        page-break-inside: avoid
    }

    img {
        max-width: 100% !important
    }

    h2,
    h3,
    p {
        orphans: 3;
        widows: 3
    }

    h2,
    h3 {
        page-break-after: avoid
    }

    .navbar {
        display: none
    }

    .btn>.caret,
    .dropup>.btn>.caret {
        border-top-color: #000 !important
    }

    .label {
        border: 1px solid #000
    }

    .table {
        border-collapse: collapse !important
    }

    .table td,
    .table th {
        background-color: #fff !important
    }

    .table-bordered td,
    .table-bordered th {
        border: 1px solid #ddd !important
    }
}

@font-face {
    font-family: Glyphicons Halflings;
    src: url(f4769f9bdb7466be65088239c12046d1.html);
    src: url(f4769f9bdb7466be65088239c12046d1d41d.html?#iefix) format("embedded-opentype"), url(448c34a56d699c29117adc64c43affeb.html) format("woff2"), url(fa2772327f55d8198301fdb8bcfc8158.html) format("woff"), url(e18bbf611f2a2e43afc071aa2f4e1512.html) format("truetype"), url(89889688147bd7575d6327160d64e760.html#glyphicons_halflingsregular) format("svg")
}

.glyphicon {
    position: relative;
    top: 1px;
    display: inline-block;
    font-family: Glyphicons Halflings;
    font-style: normal;
    font-weight: 400;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale
}

.glyphicon-asterisk:before {
    content: "*"
}

.glyphicon-plus:before {
    content: "+"
}

.glyphicon-eur:before,
.glyphicon-euro:before {
    content: "\20AC"
}

.glyphicon-minus:before {
    content: "\2212"
}

.glyphicon-cloud:before {
    content: "\2601"
}

.glyphicon-envelope:before {
    content: "\2709"
}

.glyphicon-pencil:before {
    content: "\270F"
}

.glyphicon-glass:before {
    content: "\E001"
}

.glyphicon-music:before {
    content: "\E002"
}

.glyphicon-search:before {
    content: "\E003"
}

.glyphicon-heart:before {
    content: "\E005"
}

.glyphicon-star:before {
    content: "\E006"
}

.glyphicon-star-empty:before {
    content: "\E007"
}

.glyphicon-user:before {
    content: "\E008"
}

.glyphicon-film:before {
    content: "\E009"
}

.glyphicon-th-large:before {
    content: "\E010"
}

.glyphicon-th:before {
    content: "\E011"
}

.glyphicon-th-list:before {
    content: "\E012"
}

.glyphicon-ok:before {
    content: "\E013"
}

.glyphicon-remove:before {
    content: "\E014"
}

.glyphicon-zoom-in:before {
    content: "\E015"
}

.glyphicon-zoom-out:before {
    content: "\E016"
}

.glyphicon-off:before {
    content: "\E017"
}

.glyphicon-signal:before {
    content: "\E018"
}

.glyphicon-cog:before {
    content: "\E019"
}

.glyphicon-trash:before {
    content: "\E020"
}

.glyphicon-home:before {
    content: "\E021"
}

.glyphicon-file:before {
    content: "\E022"
}

.glyphicon-time:before {
    content: "\E023"
}

.glyphicon-road:before {
    content: "\E024"
}

.glyphicon-download-alt:before {
    content: "\E025"
}

.glyphicon-download:before {
    content: "\E026"
}

.glyphicon-upload:before {
    content: "\E027"
}

.glyphicon-inbox:before {
    content: "\E028"
}

.glyphicon-play-circle:before {
    content: "\E029"
}

.glyphicon-repeat:before {
    content: "\E030"
}

.glyphicon-refresh:before {
    content: "\E031"
}

.glyphicon-list-alt:before {
    content: "\E032"
}

.glyphicon-lock:before {
    content: "\E033"
}

.glyphicon-flag:before {
    content: "\E034"
}

.glyphicon-headphones:before {
    content: "\E035"
}

.glyphicon-volume-off:before {
    content: "\E036"
}

.glyphicon-volume-down:before {
    content: "\E037"
}

.glyphicon-volume-up:before {
    content: "\E038"
}

.glyphicon-qrcode:before {
    content: "\E039"
}

.glyphicon-barcode:before {
    content: "\E040"
}

.glyphicon-tag:before {
    content: "\E041"
}

.glyphicon-tags:before {
    content: "\E042"
}

.glyphicon-book:before {
    content: "\E043"
}

.glyphicon-bookmark:before {
    content: "\E044"
}

.glyphicon-print:before {
    content: "\E045"
}

.glyphicon-camera:before {
    content: "\E046"
}

.glyphicon-font:before {
    content: "\E047"
}

.glyphicon-bold:before {
    content: "\E048"
}

.glyphicon-italic:before {
    content: "\E049"
}

.glyphicon-text-height:before {
    content: "\E050"
}

.glyphicon-text-width:before {
    content: "\E051"
}

.glyphicon-align-left:before {
    content: "\E052"
}

.glyphicon-align-center:before {
    content: "\E053"
}

.glyphicon-align-right:before {
    content: "\E054"
}

.glyphicon-align-justify:before {
    content: "\E055"
}

.glyphicon-list:before {
    content: "\E056"
}

.glyphicon-indent-left:before {
    content: "\E057"
}

.glyphicon-indent-right:before {
    content: "\E058"
}

.glyphicon-facetime-video:before {
    content: "\E059"
}

.glyphicon-picture:before {
    content: "\E060"
}

.glyphicon-map-marker:before {
    content: "\E062"
}

.glyphicon-adjust:before {
    content: "\E063"
}

.glyphicon-tint:before {
    content: "\E064"
}

.glyphicon-edit:before {
    content: "\E065"
}

.glyphicon-share:before {
    content: "\E066"
}

.glyphicon-check:before {
    content: "\E067"
}

.glyphicon-move:before {
    content: "\E068"
}

.glyphicon-step-backward:before {
    content: "\E069"
}

.glyphicon-fast-backward:before {
    content: "\E070"
}

.glyphicon-backward:before {
    content: "\E071"
}

.glyphicon-play:before {
    content: "\E072"
}

.glyphicon-pause:before {
    content: "\E073"
}

.glyphicon-stop:before {
    content: "\E074"
}

.glyphicon-forward:before {
    content: "\E075"
}

.glyphicon-fast-forward:before {
    content: "\E076"
}

.glyphicon-step-forward:before {
    content: "\E077"
}

.glyphicon-eject:before {
    content: "\E078"
}

.glyphicon-chevron-left:before {
    content: "\E079"
}

.glyphicon-chevron-right:before {
    content: "\E080"
}

.glyphicon-plus-sign:before {
    content: "\E081"
}

.glyphicon-minus-sign:before {
    content: "\E082"
}

.glyphicon-remove-sign:before {
    content: "\E083"
}

.glyphicon-ok-sign:before {
    content: "\E084"
}

.glyphicon-question-sign:before {
    content: "\E085"
}

.glyphicon-info-sign:before {
    content: "\E086"
}

.glyphicon-screenshot:before {
    content: "\E087"
}

.glyphicon-remove-circle:before {
    content: "\E088"
}

.glyphicon-ok-circle:before {
    content: "\E089"
}

.glyphicon-ban-circle:before {
    content: "\E090"
}

.glyphicon-arrow-left:before {
    content: "\E091"
}

.glyphicon-arrow-right:before {
    content: "\E092"
}

.glyphicon-arrow-up:before {
    content: "\E093"
}

.glyphicon-arrow-down:before {
    content: "\E094"
}

.glyphicon-share-alt:before {
    content: "\E095"
}

.glyphicon-resize-full:before {
    content: "\E096"
}

.glyphicon-resize-small:before {
    content: "\E097"
}

.glyphicon-exclamation-sign:before {
    content: "\E101"
}

.glyphicon-gift:before {
    content: "\E102"
}

.glyphicon-leaf:before {
    content: "\E103"
}

.glyphicon-fire:before {
    content: "\E104"
}

.glyphicon-eye-open:before {
    content: "\E105"
}

.glyphicon-eye-close:before {
    content: "\E106"
}

.glyphicon-warning-sign:before {
    content: "\E107"
}

.glyphicon-plane:before {
    content: "\E108"
}

.glyphicon-calendar:before {
    content: "\E109"
}

.glyphicon-random:before {
    content: "\E110"
}

.glyphicon-comment:before {
    content: "\E111"
}

.glyphicon-magnet:before {
    content: "\E112"
}

.glyphicon-chevron-up:before {
    content: "\E113"
}

.glyphicon-chevron-down:before {
    content: "\E114"
}

.glyphicon-retweet:before {
    content: "\E115"
}

.glyphicon-shopping-cart:before {
    content: "\E116"
}

.glyphicon-folder-close:before {
    content: "\E117"
}

.glyphicon-folder-open:before {
    content: "\E118"
}

.glyphicon-resize-vertical:before {
    content: "\E119"
}

.glyphicon-resize-horizontal:before {
    content: "\E120"
}

.glyphicon-hdd:before {
    content: "\E121"
}

.glyphicon-bullhorn:before {
    content: "\E122"
}

.glyphicon-bell:before {
    content: "\E123"
}

.glyphicon-certificate:before {
    content: "\E124"
}

.glyphicon-thumbs-up:before {
    content: "\E125"
}

.glyphicon-thumbs-down:before {
    content: "\E126"
}

.glyphicon-hand-right:before {
    content: "\E127"
}

.glyphicon-hand-left:before {
    content: "\E128"
}

.glyphicon-hand-up:before {
    content: "\E129"
}

.glyphicon-hand-down:before {
    content: "\E130"
}

.glyphicon-circle-arrow-right:before {
    content: "\E131"
}

.glyphicon-circle-arrow-left:before {
    content: "\E132"
}

.glyphicon-circle-arrow-up:before {
    content: "\E133"
}

.glyphicon-circle-arrow-down:before {
    content: "\E134"
}

.glyphicon-globe:before {
    content: "\E135"
}

.glyphicon-wrench:before {
    content: "\E136"
}

.glyphicon-tasks:before {
    content: "\E137"
}

.glyphicon-filter:before {
    content: "\E138"
}

.glyphicon-briefcase:before {
    content: "\E139"
}

.glyphicon-fullscreen:before {
    content: "\E140"
}

.glyphicon-dashboard:before {
    content: "\E141"
}

.glyphicon-paperclip:before {
    content: "\E142"
}

.glyphicon-heart-empty:before {
    content: "\E143"
}

.glyphicon-link:before {
    content: "\E144"
}

.glyphicon-phone:before {
    content: "\E145"
}

.glyphicon-pushpin:before {
    content: "\E146"
}

.glyphicon-usd:before {
    content: "\E148"
}

.glyphicon-gbp:before {
    content: "\E149"
}

.glyphicon-sort:before {
    content: "\E150"
}

.glyphicon-sort-by-alphabet:before {
    content: "\E151"
}

.glyphicon-sort-by-alphabet-alt:before {
    content: "\E152"
}

.glyphicon-sort-by-order:before {
    content: "\E153"
}

.glyphicon-sort-by-order-alt:before {
    content: "\E154"
}

.glyphicon-sort-by-attributes:before {
    content: "\E155"
}

.glyphicon-sort-by-attributes-alt:before {
    content: "\E156"
}

.glyphicon-unchecked:before {
    content: "\E157"
}

.glyphicon-expand:before {
    content: "\E158"
}

.glyphicon-collapse-down:before {
    content: "\E159"
}

.glyphicon-collapse-up:before {
    content: "\E160"
}

.glyphicon-log-in:before {
    content: "\E161"
}

.glyphicon-flash:before {
    content: "\E162"
}

.glyphicon-log-out:before {
    content: "\E163"
}

.glyphicon-new-window:before {
    content: "\E164"
}

.glyphicon-record:before {
    content: "\E165"
}

.glyphicon-save:before {
    content: "\E166"
}

.glyphicon-open:before {
    content: "\E167"
}

.glyphicon-saved:before {
    content: "\E168"
}

.glyphicon-import:before {
    content: "\E169"
}

.glyphicon-export:before {
    content: "\E170"
}

.glyphicon-send:before {
    content: "\E171"
}

.glyphicon-floppy-disk:before {
    content: "\E172"
}

.glyphicon-floppy-saved:before {
    content: "\E173"
}

.glyphicon-floppy-remove:before {
    content: "\E174"
}

.glyphicon-floppy-save:before {
    content: "\E175"
}

.glyphicon-floppy-open:before {
    content: "\E176"
}

.glyphicon-credit-card:before {
    content: "\E177"
}

.glyphicon-transfer:before {
    content: "\E178"
}

.glyphicon-cutlery:before {
    content: "\E179"
}

.glyphicon-header:before {
    content: "\E180"
}

.glyphicon-compressed:before {
    content: "\E181"
}

.glyphicon-earphone:before {
    content: "\E182"
}

.glyphicon-phone-alt:before {
    content: "\E183"
}

.glyphicon-tower:before {
    content: "\E184"
}

.glyphicon-stats:before {
    content: "\E185"
}

.glyphicon-sd-video:before {
    content: "\E186"
}

.glyphicon-hd-video:before {
    content: "\E187"
}

.glyphicon-subtitles:before {
    content: "\E188"
}

.glyphicon-sound-stereo:before {
    content: "\E189"
}

.glyphicon-sound-dolby:before {
    content: "\E190"
}

.glyphicon-sound-5-1:before {
    content: "\E191"
}

.glyphicon-sound-6-1:before {
    content: "\E192"
}

.glyphicon-sound-7-1:before {
    content: "\E193"
}

.glyphicon-copyright-mark:before {
    content: "\E194"
}

.glyphicon-registration-mark:before {
    content: "\E195"
}

.glyphicon-cloud-download:before {
    content: "\E197"
}

.glyphicon-cloud-upload:before {
    content: "\E198"
}

.glyphicon-tree-conifer:before {
    content: "\E199"
}

.glyphicon-tree-deciduous:before {
    content: "\E200"
}

.glyphicon-cd:before {
    content: "\E201"
}

.glyphicon-save-file:before {
    content: "\E202"
}

.glyphicon-open-file:before {
    content: "\E203"
}

.glyphicon-level-up:before {
    content: "\E204"
}

.glyphicon-copy:before {
    content: "\E205"
}

.glyphicon-paste:before {
    content: "\E206"
}

.glyphicon-alert:before {
    content: "\E209"
}

.glyphicon-equalizer:before {
    content: "\E210"
}

.glyphicon-king:before {
    content: "\E211"
}

.glyphicon-queen:before {
    content: "\E212"
}

.glyphicon-pawn:before {
    content: "\E213"
}

.glyphicon-bishop:before {
    content: "\E214"
}

.glyphicon-knight:before {
    content: "\E215"
}

.glyphicon-baby-formula:before {
    content: "\E216"
}

.glyphicon-tent:before {
    content: "\26FA"
}

.glyphicon-blackboard:before {
    content: "\E218"
}

.glyphicon-bed:before {
    content: "\E219"
}

.glyphicon-apple:before {
    content: "\F8FF"
}

.glyphicon-erase:before {
    content: "\E221"
}

.glyphicon-hourglass:before {
    content: "\231B"
}

.glyphicon-lamp:before {
    content: "\E223"
}

.glyphicon-duplicate:before {
    content: "\E224"
}

.glyphicon-piggy-bank:before {
    content: "\E225"
}

.glyphicon-scissors:before {
    content: "\E226"
}

.glyphicon-bitcoin:before,
.glyphicon-btc:before,
.glyphicon-xbt:before {
    content: "\E227"
}

.glyphicon-jpy:before,
.glyphicon-yen:before {
    content: "\A5"
}

.glyphicon-rub:before,
.glyphicon-ruble:before {
    content: "\20BD"
}

.glyphicon-scale:before {
    content: "\E230"
}

.glyphicon-ice-lolly:before {
    content: "\E231"
}

.glyphicon-ice-lolly-tasted:before {
    content: "\E232"
}

.glyphicon-education:before {
    content: "\E233"
}

.glyphicon-option-horizontal:before {
    content: "\E234"
}

.glyphicon-option-vertical:before {
    content: "\E235"
}

.glyphicon-menu-hamburger:before {
    content: "\E236"
}

.glyphicon-modal-window:before {
    content: "\E237"
}

.glyphicon-oil:before {
    content: "\E238"
}

.glyphicon-grain:before {
    content: "\E239"
}

.glyphicon-sunglasses:before {
    content: "\E240"
}

.glyphicon-text-size:before {
    content: "\E241"
}

.glyphicon-text-color:before {
    content: "\E242"
}

.glyphicon-text-background:before {
    content: "\E243"
}

.glyphicon-object-align-top:before {
    content: "\E244"
}

.glyphicon-object-align-bottom:before {
    content: "\E245"
}

.glyphicon-object-align-horizontal:before {
    content: "\E246"
}

.glyphicon-object-align-left:before {
    content: "\E247"
}

.glyphicon-object-align-vertical:before {
    content: "\E248"
}

.glyphicon-object-align-right:before {
    content: "\E249"
}

.glyphicon-triangle-right:before {
    content: "\E250"
}

.glyphicon-triangle-left:before {
    content: "\E251"
}

.glyphicon-triangle-bottom:before {
    content: "\E252"
}

.glyphicon-triangle-top:before {
    content: "\E253"
}

.glyphicon-console:before {
    content: "\E254"
}

.glyphicon-superscript:before {
    content: "\E255"
}

.glyphicon-subscript:before {
    content: "\E256"
}

.glyphicon-menu-left:before {
    content: "\E257"
}

.glyphicon-menu-right:before {
    content: "\E258"
}

.glyphicon-menu-down:before {
    content: "\E259"
}

.glyphicon-menu-up:before {
    content: "\E260"
}

*,
:after,
:before {
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}

html {
    font-size: 10px;
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0)
}

body {
    font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
    font-size: 14px;
    line-height: 1.42857143;
    color: #333;
    background-color: #fff
}

button,
input,
select,
textarea {
    font-family: inherit;
    font-size: inherit;
    line-height: inherit
}

a {
    color: #337ab7;
    text-decoration: none
}

a:focus,
a:hover {
    color: #23527c;
    text-decoration: underline
}

a:focus {
    outline: 5px auto -webkit-focus-ring-color;
    outline-offset: -2px
}

figure {
    margin: 0
}

img {
    vertical-align: middle
}

.carousel-inner>.item>a>img,
.carousel-inner>.item>img,
.img-responsive,
.thumbnail>img,
.thumbnail a>img {
    display: block;
    max-width: 100%;
    height: auto
}

.img-rounded {
    border-radius: 6px
}

.img-thumbnail {
    display: inline-block;
    max-width: 100%;
    height: auto;
    padding: 4px;
    line-height: 1.42857143;
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 4px;
    -webkit-transition: all .2s ease-in-out;
    -o-transition: all .2s ease-in-out;
    transition: all .2s ease-in-out
}

.img-circle {
    border-radius: 50%
}

hr {
    margin-top: 20px;
    margin-bottom: 20px;
    border: 0;
    border-top: 1px solid #eee
}

.sr-only {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0
}

.sr-only-focusable:active,
.sr-only-focusable:focus {
    position: static;
    width: auto;
    height: auto;
    margin: 0;
    overflow: visible;
    clip: auto
}

[role=button] {
    cursor: pointer
}

.h1,
.h2,
.h3,
.h4,
.h5,
.h6,
h1,
h2,
h3,
h4,
h5,
h6 {
    font-family: inherit;
    font-weight: 500;
    line-height: 1.1;
    color: inherit
}

.h1 .small,
.h1 small,
.h2 .small,
.h2 small,
.h3 .small,
.h3 small,
.h4 .small,
.h4 small,
.h5 .small,
.h5 small,
.h6 .small,
.h6 small,
h1 .small,
h1 small,
h2 .small,
h2 small,
h3 .small,
h3 small,
h4 .small,
h4 small,
h5 .small,
h5 small,
h6 .small,
h6 small {
    font-weight: 400;
    line-height: 1;
    color: #777
}

.h1,
.h2,
.h3,
h1,
h2,
h3 {
    margin-top: 20px;
    margin-bottom: 10px
}

.h1 .small,
.h1 small,
.h2 .small,
.h2 small,
.h3 .small,
.h3 small,
h1 .small,
h1 small,
h2 .small,
h2 small,
h3 .small,
h3 small {
    font-size: 65%
}

.h4,
.h5,
.h6,
h4,
h5,
h6 {
    margin-top: 10px;
    margin-bottom: 10px
}

.h4 .small,
.h4 small,
.h5 .small,
.h5 small,
.h6 .small,
.h6 small,
h4 .small,
h4 small,
h5 .small,
h5 small,
h6 .small,
h6 small {
    font-size: 75%
}

.h1,
h1 {
    font-size: 36px
}

.h2,
h2 {
    font-size: 30px
}

.h3,
h3 {
    font-size: 24px
}

.h4,
h4 {
    font-size: 18px
}

.h5,
h5 {
    font-size: 14px
}

.h6,
h6 {
    font-size: 12px
}

p {
    margin: 0 0 10px
}

.lead {
    margin-bottom: 20px;
    font-size: 16px;
    font-weight: 300;
    line-height: 1.4
}

@media (min-width:768px) {
    .lead {
        font-size: 21px
    }
}

.small,
small {
    font-size: 85%
}

.mark,
mark {
    padding: .2em;
    background-color: #fcf8e3
}

.text-left {
    text-align: left
}

.text-right {
    text-align: right
}

.text-center {
    text-align: center
}

.text-justify {
    text-align: justify
}

.text-nowrap {
    white-space: nowrap
}

.text-lowercase {
    text-transform: lowercase
}

.text-uppercase {
    text-transform: uppercase
}

.text-capitalize {
    text-transform: capitalize
}

.text-muted {
    color: #777
}

.text-primary {
    color: #337ab7
}

a.text-primary:focus,
a.text-primary:hover {
    color: #286090
}

.text-success {
    color: #3c763d
}

a.text-success:focus,
a.text-success:hover {
    color: #2b542c
}

.text-info {
    color: #31708f
}

a.text-info:focus,
a.text-info:hover {
    color: #245269
}

.text-warning {
    color: #8a6d3b
}

a.text-warning:focus,
a.text-warning:hover {
    color: #66512c
}

.text-danger {
    color: #a94442
}

a.text-danger:focus,
a.text-danger:hover {
    color: #843534
}

.bg-primary {
    color: #fff;
    background-color: #337ab7
}

a.bg-primary:focus,
a.bg-primary:hover {
    background-color: #286090
}

.bg-success {
    background-color: #dff0d8
}

a.bg-success:focus,
a.bg-success:hover {
    background-color: #c1e2b3
}

.bg-info {
    background-color: #d9edf7
}

a.bg-info:focus,
a.bg-info:hover {
    background-color: #afd9ee
}

.bg-warning {
    background-color: #fcf8e3
}

a.bg-warning:focus,
a.bg-warning:hover {
    background-color: #f7ecb5
}

.bg-danger {
    background-color: #f2dede
}

a.bg-danger:focus,
a.bg-danger:hover {
    background-color: #e4b9b9
}

.page-header {
    padding-bottom: 9px;
    margin: 40px 0 20px;
    border-bottom: 1px solid #eee
}

ol,
ul {
    margin-top: 0;
    margin-bottom: 10px
}

ol ol,
ol ul,
ul ol,
ul ul {
    margin-bottom: 0
}

.list-inline,
.list-unstyled {
    padding-left: 0;
    list-style: none
}

.list-inline {
    margin-left: -5px
}

.list-inline>li {
    display: inline-block;
    padding-right: 5px;
    padding-left: 5px
}

dl {
    margin-top: 0;
    margin-bottom: 20px
}

dd,
dt {
    line-height: 1.42857143
}

dt {
    font-weight: 700
}

dd {
    margin-left: 0
}

@media (min-width:768px) {
    .dl-horizontal dt {
        float: left;
        width: 160px;
        overflow: hidden;
        clear: left;
        text-align: right;
        -o-text-overflow: ellipsis;
        text-overflow: ellipsis;
        white-space: nowrap
    }

    .dl-horizontal dd {
        margin-left: 180px
    }
}

abbr[data-original-title],
abbr[title] {
    cursor: help;
    border-bottom: 1px dotted #777
}

.initialism {
    font-size: 90%;
    text-transform: uppercase
}

blockquote {
    padding: 10px 20px;
    margin: 0 0 20px;
    font-size: 17.5px;
    border-left: 5px solid #eee
}

blockquote ol:last-child,
blockquote p:last-child,
blockquote ul:last-child {
    margin-bottom: 0
}

blockquote .small,
blockquote footer,
blockquote small {
    display: block;
    font-size: 80%;
    line-height: 1.42857143;
    color: #777
}

blockquote .small:before,
blockquote footer:before,
blockquote small:before {
    content: "\2014   \A0"
}

.blockquote-reverse,
blockquote.pull-right {
    padding-right: 15px;
    padding-left: 0;
    text-align: right;
    border-right: 5px solid #eee;
    border-left: 0
}

.blockquote-reverse .small:before,
.blockquote-reverse footer:before,
.blockquote-reverse small:before,
blockquote.pull-right .small:before,
blockquote.pull-right footer:before,
blockquote.pull-right small:before {
    content: ""
}

.blockquote-reverse .small:after,
.blockquote-reverse footer:after,
.blockquote-reverse small:after,
blockquote.pull-right .small:after,
blockquote.pull-right footer:after,
blockquote.pull-right small:after {
    content: "\A0   \2014"
}

address {
    margin-bottom: 20px;
    font-style: normal;
    line-height: 1.42857143
}

code,
kbd,
pre,
samp {
    font-family: Menlo, Monaco, Consolas, Courier New, monospace
}

code {
    color: #c7254e;
    background-color: #f9f2f4;
    border-radius: 4px
}

code,
kbd {
    padding: 2px 4px;
    font-size: 90%
}

kbd {
    color: #fff;
    background-color: #333;
    border-radius: 3px;
    -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, .25);
    box-shadow: inset 0 -1px 0 rgba(0, 0, 0, .25)
}

kbd kbd {
    padding: 0;
    font-size: 100%;
    font-weight: 700;
    -webkit-box-shadow: none;
    box-shadow: none
}

pre {
    display: block;
    padding: 9.5px;
    margin: 0 0 10px;
    font-size: 13px;
    line-height: 1.42857143;
    color: #333;
    word-break: break-all;
    word-wrap: break-word;
    background-color: #f5f5f5;
    border: 1px solid #ccc;
    border-radius: 4px
}

pre code {
    padding: 0;
    font-size: inherit;
    color: inherit;
    white-space: pre-wrap;
    background-color: transparent;
    border-radius: 0
}

.pre-scrollable {
    max-height: 340px;
    overflow-y: scroll
}

.container {
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto
}

@media (min-width:768px) {
    .container {
        width: 750px
    }
}

@media (min-width:992px) {
    .container {
        width: 970px
    }
}

@media (min-width:1200px) {
    .container {
        width: 1170px
    }
}

.container-fluid {
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto
}

.row {
    margin-right: -15px;
    margin-left: -15px
}

.col-lg-1,
.col-lg-2,
.col-lg-3,
.col-lg-4,
.col-lg-5,
.col-lg-6,
.col-lg-7,
.col-lg-8,
.col-lg-9,
.col-lg-10,
.col-lg-11,
.col-lg-12,
.col-md-1,
.col-md-2,
.col-md-3,
.col-md-4,
.col-md-5,
.col-md-6,
.col-md-7,
.col-md-8,
.col-md-9,
.col-md-10,
.col-md-11,
.col-md-12,
.col-sm-1,
.col-sm-2,
.col-sm-3,
.col-sm-4,
.col-sm-5,
.col-sm-6,
.col-sm-7,
.col-sm-8,
.col-sm-9,
.col-sm-10,
.col-sm-11,
.col-sm-12,
.col-xs-1,
.col-xs-2,
.col-xs-3,
.col-xs-4,
.col-xs-5,
.col-xs-6,
.col-xs-7,
.col-xs-8,
.col-xs-9,
.col-xs-10,
.col-xs-11,
.col-xs-12 {
    position: relative;
    min-height: 1px;
    padding-right: 15px;
    padding-left: 15px
}

.col-xs-1,
.col-xs-2,
.col-xs-3,
.col-xs-4,
.col-xs-5,
.col-xs-6,
.col-xs-7,
.col-xs-8,
.col-xs-9,
.col-xs-10,
.col-xs-11,
.col-xs-12 {
    float: left
}

.col-xs-12 {
    width: 100%
}

.col-xs-11 {
    width: 91.66666667%
}

.col-xs-10 {
    width: 83.33333333%
}

.col-xs-9 {
    width: 75%
}

.col-xs-8 {
    width: 66.66666667%
}

.col-xs-7 {
    width: 58.33333333%
}

.col-xs-6 {
    width: 50%
}

.col-xs-5 {
    width: 41.66666667%
}

.col-xs-4 {
    width: 33.33333333%
}

.col-xs-3 {
    width: 25%
}

.col-xs-2 {
    width: 16.66666667%
}

.col-xs-1 {
    width: 8.33333333%
}

.col-xs-pull-12 {
    right: 100%
}

.col-xs-pull-11 {
    right: 91.66666667%
}

.col-xs-pull-10 {
    right: 83.33333333%
}

.col-xs-pull-9 {
    right: 75%
}

.col-xs-pull-8 {
    right: 66.66666667%
}

.col-xs-pull-7 {
    right: 58.33333333%
}

.col-xs-pull-6 {
    right: 50%
}

.col-xs-pull-5 {
    right: 41.66666667%
}

.col-xs-pull-4 {
    right: 33.33333333%
}

.col-xs-pull-3 {
    right: 25%
}

.col-xs-pull-2 {
    right: 16.66666667%
}

.col-xs-pull-1 {
    right: 8.33333333%
}

.col-xs-pull-0 {
    right: auto
}

.col-xs-push-12 {
    left: 100%
}

.col-xs-push-11 {
    left: 91.66666667%
}

.col-xs-push-10 {
    left: 83.33333333%
}

.col-xs-push-9 {
    left: 75%
}

.col-xs-push-8 {
    left: 66.66666667%
}

.col-xs-push-7 {
    left: 58.33333333%
}

.col-xs-push-6 {
    left: 50%
}

.col-xs-push-5 {
    left: 41.66666667%
}

.col-xs-push-4 {
    left: 33.33333333%
}

.col-xs-push-3 {
    left: 25%
}

.col-xs-push-2 {
    left: 16.66666667%
}

.col-xs-push-1 {
    left: 8.33333333%
}

.col-xs-push-0 {
    left: auto
}

.col-xs-offset-12 {
    margin-left: 100%
}

.col-xs-offset-11 {
    margin-left: 91.66666667%
}

.col-xs-offset-10 {
    margin-left: 83.33333333%
}

.col-xs-offset-9 {
    margin-left: 75%
}

.col-xs-offset-8 {
    margin-left: 66.66666667%
}

.col-xs-offset-7 {
    margin-left: 58.33333333%
}

.col-xs-offset-6 {
    margin-left: 50%
}

.col-xs-offset-5 {
    margin-left: 41.66666667%
}

.col-xs-offset-4 {
    margin-left: 33.33333333%
}

.col-xs-offset-3 {
    margin-left: 25%
}

.col-xs-offset-2 {
    margin-left: 16.66666667%
}

.col-xs-offset-1 {
    margin-left: 8.33333333%
}

.col-xs-offset-0 {
    margin-left: 0
}

@media (min-width:768px) {

    .col-sm-1,
    .col-sm-2,
    .col-sm-3,
    .col-sm-4,
    .col-sm-5,
    .col-sm-6,
    .col-sm-7,
    .col-sm-8,
    .col-sm-9,
    .col-sm-10,
    .col-sm-11,
    .col-sm-12 {
        float: left
    }

    .col-sm-12 {
        width: 100%
    }

    .col-sm-11 {
        width: 91.66666667%
    }

    .col-sm-10 {
        width: 83.33333333%
    }

    .col-sm-9 {
        width: 75%
    }

    .col-sm-8 {
        width: 66.66666667%
    }

    .col-sm-7 {
        width: 58.33333333%
    }

    .col-sm-6 {
        width: 50%
    }

    .col-sm-5 {
        width: 41.66666667%
    }

    .col-sm-4 {
        width: 33.33333333%
    }

    .col-sm-3 {
        width: 25%
    }

    .col-sm-2 {
        width: 16.66666667%
    }

    .col-sm-1 {
        width: 8.33333333%
    }

    .col-sm-pull-12 {
        right: 100%
    }

    .col-sm-pull-11 {
        right: 91.66666667%
    }

    .col-sm-pull-10 {
        right: 83.33333333%
    }

    .col-sm-pull-9 {
        right: 75%
    }

    .col-sm-pull-8 {
        right: 66.66666667%
    }

    .col-sm-pull-7 {
        right: 58.33333333%
    }

    .col-sm-pull-6 {
        right: 50%
    }

    .col-sm-pull-5 {
        right: 41.66666667%
    }

    .col-sm-pull-4 {
        right: 33.33333333%
    }

    .col-sm-pull-3 {
        right: 25%
    }

    .col-sm-pull-2 {
        right: 16.66666667%
    }

    .col-sm-pull-1 {
        right: 8.33333333%
    }

    .col-sm-pull-0 {
        right: auto
    }

    .col-sm-push-12 {
        left: 100%
    }

    .col-sm-push-11 {
        left: 91.66666667%
    }

    .col-sm-push-10 {
        left: 83.33333333%
    }

    .col-sm-push-9 {
        left: 75%
    }

    .col-sm-push-8 {
        left: 66.66666667%
    }

    .col-sm-push-7 {
        left: 58.33333333%
    }

    .col-sm-push-6 {
        left: 50%
    }

    .col-sm-push-5 {
        left: 41.66666667%
    }

    .col-sm-push-4 {
        left: 33.33333333%
    }

    .col-sm-push-3 {
        left: 25%
    }

    .col-sm-push-2 {
        left: 16.66666667%
    }

    .col-sm-push-1 {
        left: 8.33333333%
    }

    .col-sm-push-0 {
        left: auto
    }

    .col-sm-offset-12 {
        margin-left: 100%
    }

    .col-sm-offset-11 {
        margin-left: 91.66666667%
    }

    .col-sm-offset-10 {
        margin-left: 83.33333333%
    }

    .col-sm-offset-9 {
        margin-left: 75%
    }

    .col-sm-offset-8 {
        margin-left: 66.66666667%
    }

    .col-sm-offset-7 {
        margin-left: 58.33333333%
    }

    .col-sm-offset-6 {
        margin-left: 50%
    }

    .col-sm-offset-5 {
        margin-left: 41.66666667%
    }

    .col-sm-offset-4 {
        margin-left: 33.33333333%
    }

    .col-sm-offset-3 {
        margin-left: 25%
    }

    .col-sm-offset-2 {
        margin-left: 16.66666667%
    }

    .col-sm-offset-1 {
        margin-left: 8.33333333%
    }

    .col-sm-offset-0 {
        margin-left: 0
    }
}

@media (min-width:992px) {

    .col-md-1,
    .col-md-2,
    .col-md-3,
    .col-md-4,
    .col-md-5,
    .col-md-6,
    .col-md-7,
    .col-md-8,
    .col-md-9,
    .col-md-10,
    .col-md-11,
    .col-md-12 {
        float: left
    }

    .col-md-12 {
        width: 100%
    }

    .col-md-11 {
        width: 91.66666667%
    }

    .col-md-10 {
        width: 83.33333333%
    }

    .col-md-9 {
        width: 75%
    }

    .col-md-8 {
        width: 66.66666667%
    }

    .col-md-7 {
        width: 58.33333333%
    }

    .col-md-6 {
        width: 50%
    }

    .col-md-5 {
        width: 41.66666667%
    }

    .col-md-4 {
        width: 33.33333333%
    }

    .col-md-3 {
        width: 25%
    }

    .col-md-2 {
        width: 16.66666667%
    }

    .col-md-1 {
        width: 8.33333333%
    }

    .col-md-pull-12 {
        right: 100%
    }

    .col-md-pull-11 {
        right: 91.66666667%
    }

    .col-md-pull-10 {
        right: 83.33333333%
    }

    .col-md-pull-9 {
        right: 75%
    }

    .col-md-pull-8 {
        right: 66.66666667%
    }

    .col-md-pull-7 {
        right: 58.33333333%
    }

    .col-md-pull-6 {
        right: 50%
    }

    .col-md-pull-5 {
        right: 41.66666667%
    }

    .col-md-pull-4 {
        right: 33.33333333%
    }

    .col-md-pull-3 {
        right: 25%
    }

    .col-md-pull-2 {
        right: 16.66666667%
    }

    .col-md-pull-1 {
        right: 8.33333333%
    }

    .col-md-pull-0 {
        right: auto
    }

    .col-md-push-12 {
        left: 100%
    }

    .col-md-push-11 {
        left: 91.66666667%
    }

    .col-md-push-10 {
        left: 83.33333333%
    }

    .col-md-push-9 {
        left: 75%
    }

    .col-md-push-8 {
        left: 66.66666667%
    }

    .col-md-push-7 {
        left: 58.33333333%
    }

    .col-md-push-6 {
        left: 50%
    }

    .col-md-push-5 {
        left: 41.66666667%
    }

    .col-md-push-4 {
        left: 33.33333333%
    }

    .col-md-push-3 {
        left: 25%
    }

    .col-md-push-2 {
        left: 16.66666667%
    }

    .col-md-push-1 {
        left: 8.33333333%
    }

    .col-md-push-0 {
        left: auto
    }

    .col-md-offset-12 {
        margin-left: 100%
    }

    .col-md-offset-11 {
        margin-left: 91.66666667%
    }

    .col-md-offset-10 {
        margin-left: 83.33333333%
    }

    .col-md-offset-9 {
        margin-left: 75%
    }

    .col-md-offset-8 {
        margin-left: 66.66666667%
    }

    .col-md-offset-7 {
        margin-left: 58.33333333%
    }

    .col-md-offset-6 {
        margin-left: 50%
    }

    .col-md-offset-5 {
        margin-left: 41.66666667%
    }

    .col-md-offset-4 {
        margin-left: 33.33333333%
    }

    .col-md-offset-3 {
        margin-left: 25%
    }

    .col-md-offset-2 {
        margin-left: 16.66666667%
    }

    .col-md-offset-1 {
        margin-left: 8.33333333%
    }

    .col-md-offset-0 {
        margin-left: 0
    }
}

@media (min-width:1200px) {

    .col-lg-1,
    .col-lg-2,
    .col-lg-3,
    .col-lg-4,
    .col-lg-5,
    .col-lg-6,
    .col-lg-7,
    .col-lg-8,
    .col-lg-9,
    .col-lg-10,
    .col-lg-11,
    .col-lg-12 {
        float: left
    }

    .col-lg-12 {
        width: 100%
    }

    .col-lg-11 {
        width: 91.66666667%
    }

    .col-lg-10 {
        width: 83.33333333%
    }

    .col-lg-9 {
        width: 75%
    }

    .col-lg-8 {
        width: 66.66666667%
    }

    .col-lg-7 {
        width: 58.33333333%
    }

    .col-lg-6 {
        width: 50%
    }

    .col-lg-5 {
        width: 41.66666667%
    }

    .col-lg-4 {
        width: 33.33333333%
    }

    .col-lg-3 {
        width: 25%
    }

    .col-lg-2 {
        width: 16.66666667%
    }

    .col-lg-1 {
        width: 8.33333333%
    }

    .col-lg-pull-12 {
        right: 100%
    }

    .col-lg-pull-11 {
        right: 91.66666667%
    }

    .col-lg-pull-10 {
        right: 83.33333333%
    }

    .col-lg-pull-9 {
        right: 75%
    }

    .col-lg-pull-8 {
        right: 66.66666667%
    }

    .col-lg-pull-7 {
        right: 58.33333333%
    }

    .col-lg-pull-6 {
        right: 50%
    }

    .col-lg-pull-5 {
        right: 41.66666667%
    }

    .col-lg-pull-4 {
        right: 33.33333333%
    }

    .col-lg-pull-3 {
        right: 25%
    }

    .col-lg-pull-2 {
        right: 16.66666667%
    }

    .col-lg-pull-1 {
        right: 8.33333333%
    }

    .col-lg-pull-0 {
        right: auto
    }

    .col-lg-push-12 {
        left: 100%
    }

    .col-lg-push-11 {
        left: 91.66666667%
    }

    .col-lg-push-10 {
        left: 83.33333333%
    }

    .col-lg-push-9 {
        left: 75%
    }

    .col-lg-push-8 {
        left: 66.66666667%
    }

    .col-lg-push-7 {
        left: 58.33333333%
    }

    .col-lg-push-6 {
        left: 50%
    }

    .col-lg-push-5 {
        left: 41.66666667%
    }

    .col-lg-push-4 {
        left: 33.33333333%
    }

    .col-lg-push-3 {
        left: 25%
    }

    .col-lg-push-2 {
        left: 16.66666667%
    }

    .col-lg-push-1 {
        left: 8.33333333%
    }

    .col-lg-push-0 {
        left: auto
    }

    .col-lg-offset-12 {
        margin-left: 100%
    }

    .col-lg-offset-11 {
        margin-left: 91.66666667%
    }

    .col-lg-offset-10 {
        margin-left: 83.33333333%
    }

    .col-lg-offset-9 {
        margin-left: 75%
    }

    .col-lg-offset-8 {
        margin-left: 66.66666667%
    }

    .col-lg-offset-7 {
        margin-left: 58.33333333%
    }

    .col-lg-offset-6 {
        margin-left: 50%
    }

    .col-lg-offset-5 {
        margin-left: 41.66666667%
    }

    .col-lg-offset-4 {
        margin-left: 33.33333333%
    }

    .col-lg-offset-3 {
        margin-left: 25%
    }

    .col-lg-offset-2 {
        margin-left: 16.66666667%
    }

    .col-lg-offset-1 {
        margin-left: 8.33333333%
    }

    .col-lg-offset-0 {
        margin-left: 0
    }
}

table {
    background-color: transparent
}

caption {
    padding-top: 8px;
    padding-bottom: 8px;
    color: #777
}

caption,
th {
    text-align: left
}

.table {
    width: 100%;
    max-width: 100%;
    margin-bottom: 20px
}

.table>tbody>tr>td,
.table>tbody>tr>th,
.table>tfoot>tr>td,
.table>tfoot>tr>th,
.table>thead>tr>td,
.table>thead>tr>th {
    padding: 8px;
    line-height: 1.42857143;
    vertical-align: top;
    border-top: 1px solid #ddd
}

.table>thead>tr>th {
    vertical-align: bottom;
    border-bottom: 2px solid #ddd
}

.table>caption+thead>tr:first-child>td,
.table>caption+thead>tr:first-child>th,
.table>colgroup+thead>tr:first-child>td,
.table>colgroup+thead>tr:first-child>th,
.table>thead:first-child>tr:first-child>td,
.table>thead:first-child>tr:first-child>th {
    border-top: 0
}

.table>tbody+tbody {
    border-top: 2px solid #ddd
}

.table .table {
    background-color: #fff
}

.table-condensed>tbody>tr>td,
.table-condensed>tbody>tr>th,
.table-condensed>tfoot>tr>td,
.table-condensed>tfoot>tr>th,
.table-condensed>thead>tr>td,
.table-condensed>thead>tr>th {
    padding: 5px
}

.table-bordered,
.table-bordered>tbody>tr>td,
.table-bordered>tbody>tr>th,
.table-bordered>tfoot>tr>td,
.table-bordered>tfoot>tr>th,
.table-bordered>thead>tr>td,
.table-bordered>thead>tr>th {
    border: 1px solid #ddd
}

.table-bordered>thead>tr>td,
.table-bordered>thead>tr>th {
    border-bottom-width: 2px
}

.table-striped>tbody>tr:nth-of-type(odd) {
    background-color: #f9f9f9
}

.table-hover>tbody>tr:hover {
    background-color: #f5f5f5
}

table col[class*=col-] {
    position: static;
    display: table-column;
    float: none
}

table td[class*=col-],
table th[class*=col-] {
    position: static;
    display: table-cell;
    float: none
}

.table>tbody>tr.active>td,
.table>tbody>tr.active>th,
.table>tbody>tr>td.active,
.table>tbody>tr>th.active,
.table>tfoot>tr.active>td,
.table>tfoot>tr.active>th,
.table>tfoot>tr>td.active,
.table>tfoot>tr>th.active,
.table>thead>tr.active>td,
.table>thead>tr.active>th,
.table>thead>tr>td.active,
.table>thead>tr>th.active {
    background-color: #f5f5f5
}

.table-hover>tbody>tr.active:hover>td,
.table-hover>tbody>tr.active:hover>th,
.table-hover>tbody>tr:hover>.active,
.table-hover>tbody>tr>td.active:hover,
.table-hover>tbody>tr>th.active:hover {
    background-color: #e8e8e8
}

.table>tbody>tr.success>td,
.table>tbody>tr.success>th,
.table>tbody>tr>td.success,
.table>tbody>tr>th.success,
.table>tfoot>tr.success>td,
.table>tfoot>tr.success>th,
.table>tfoot>tr>td.success,
.table>tfoot>tr>th.success,
.table>thead>tr.success>td,
.table>thead>tr.success>th,
.table>thead>tr>td.success,
.table>thead>tr>th.success {
    background-color: #dff0d8
}

.table-hover>tbody>tr.success:hover>td,
.table-hover>tbody>tr.success:hover>th,
.table-hover>tbody>tr:hover>.success,
.table-hover>tbody>tr>td.success:hover,
.table-hover>tbody>tr>th.success:hover {
    background-color: #d0e9c6
}

.table>tbody>tr.info>td,
.table>tbody>tr.info>th,
.table>tbody>tr>td.info,
.table>tbody>tr>th.info,
.table>tfoot>tr.info>td,
.table>tfoot>tr.info>th,
.table>tfoot>tr>td.info,
.table>tfoot>tr>th.info,
.table>thead>tr.info>td,
.table>thead>tr.info>th,
.table>thead>tr>td.info,
.table>thead>tr>th.info {
    background-color: #d9edf7
}

.table-hover>tbody>tr.info:hover>td,
.table-hover>tbody>tr.info:hover>th,
.table-hover>tbody>tr:hover>.info,
.table-hover>tbody>tr>td.info:hover,
.table-hover>tbody>tr>th.info:hover {
    background-color: #c4e3f3
}

.table>tbody>tr.warning>td,
.table>tbody>tr.warning>th,
.table>tbody>tr>td.warning,
.table>tbody>tr>th.warning,
.table>tfoot>tr.warning>td,
.table>tfoot>tr.warning>th,
.table>tfoot>tr>td.warning,
.table>tfoot>tr>th.warning,
.table>thead>tr.warning>td,
.table>thead>tr.warning>th,
.table>thead>tr>td.warning,
.table>thead>tr>th.warning {
    background-color: #fcf8e3
}

.table-hover>tbody>tr.warning:hover>td,
.table-hover>tbody>tr.warning:hover>th,
.table-hover>tbody>tr:hover>.warning,
.table-hover>tbody>tr>td.warning:hover,
.table-hover>tbody>tr>th.warning:hover {
    background-color: #faf2cc
}

.table>tbody>tr.danger>td,
.table>tbody>tr.danger>th,
.table>tbody>tr>td.danger,
.table>tbody>tr>th.danger,
.table>tfoot>tr.danger>td,
.table>tfoot>tr.danger>th,
.table>tfoot>tr>td.danger,
.table>tfoot>tr>th.danger,
.table>thead>tr.danger>td,
.table>thead>tr.danger>th,
.table>thead>tr>td.danger,
.table>thead>tr>th.danger {
    background-color: #f2dede
}

.table-hover>tbody>tr.danger:hover>td,
.table-hover>tbody>tr.danger:hover>th,
.table-hover>tbody>tr:hover>.danger,
.table-hover>tbody>tr>td.danger:hover,
.table-hover>tbody>tr>th.danger:hover {
    background-color: #ebcccc
}

.table-responsive {
    min-height: .01%;
    overflow-x: auto
}

@media screen and (max-width:767px) {
    .table-responsive {
        width: 100%;
        margin-bottom: 15px;
        overflow-y: hidden;
        -ms-overflow-style: -ms-autohiding-scrollbar;
        border: 1px solid #ddd
    }

    .table-responsive>.table {
        margin-bottom: 0
    }

    .table-responsive>.table>tbody>tr>td,
    .table-responsive>.table>tbody>tr>th,
    .table-responsive>.table>tfoot>tr>td,
    .table-responsive>.table>tfoot>tr>th,
    .table-responsive>.table>thead>tr>td,
    .table-responsive>.table>thead>tr>th {
        white-space: nowrap
    }

    .table-responsive>.table-bordered {
        border: 0
    }

    .table-responsive>.table-bordered>tbody>tr>td:first-child,
    .table-responsive>.table-bordered>tbody>tr>th:first-child,
    .table-responsive>.table-bordered>tfoot>tr>td:first-child,
    .table-responsive>.table-bordered>tfoot>tr>th:first-child,
    .table-responsive>.table-bordered>thead>tr>td:first-child,
    .table-responsive>.table-bordered>thead>tr>th:first-child {
        border-left: 0
    }

    .table-responsive>.table-bordered>tbody>tr>td:last-child,
    .table-responsive>.table-bordered>tbody>tr>th:last-child,
    .table-responsive>.table-bordered>tfoot>tr>td:last-child,
    .table-responsive>.table-bordered>tfoot>tr>th:last-child,
    .table-responsive>.table-bordered>thead>tr>td:last-child,
    .table-responsive>.table-bordered>thead>tr>th:last-child {
        border-right: 0
    }

    .table-responsive>.table-bordered>tbody>tr:last-child>td,
    .table-responsive>.table-bordered>tbody>tr:last-child>th,
    .table-responsive>.table-bordered>tfoot>tr:last-child>td,
    .table-responsive>.table-bordered>tfoot>tr:last-child>th {
        border-bottom: 0
    }
}

fieldset {
    min-width: 0;
    margin: 0
}

fieldset,
legend {
    padding: 0;
    border: 0
}

legend {
    display: block;
    width: 100%;
    margin-bottom: 20px;
    font-size: 21px;
    line-height: inherit;
    color: #333;
    border-bottom: 1px solid #e5e5e5
}

label {
    display: inline-block;
    max-width: 100%;
    margin-bottom: 5px;
    font-weight: 700
}

input[type=search] {
    -webkit-box-sizing: border-box;
    box-sizing: border-box
}

input[type=checkbox],
input[type=radio] {
    margin: 4px 0 0;
    margin-top: 1px\9;
    line-height: normal
}

input[type=file] {
    display: block
}

input[type=range] {
    display: block;
    width: 100%
}

select[multiple],
select[size] {
    height: auto
}

input[type=checkbox]:focus,
input[type=file]:focus,
input[type=radio]:focus {
    outline: 5px auto -webkit-focus-ring-color;
    outline-offset: -2px
}

output {
    padding-top: 7px
}

.form-control,
output {
    display: block;
    font-size: 14px;
    line-height: 1.42857143;
    color: #555
}

.form-control {
    width: 100%;
    height: 34px;
    padding: 6px 12px;
    background-color: #fff;
    background-image: none;
    border: 1px solid #ccc;
    border-radius: 4px;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    -webkit-transition: border-color .15s ease-in-out, -webkit-box-shadow .15s ease-in-out;
    -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
    transition: border-color .15s ease-in-out, -webkit-box-shadow .15s ease-in-out;
    transition: border-color .15s ease-in-out, box-shadow .15s ease-in-out;
    transition: border-color .15s ease-in-out, box-shadow .15s ease-in-out, -webkit-box-shadow .15s ease-in-out
}

.form-control:focus {
    border-color: #66afe9;
    outline: 0;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 8px rgba(102, 175, 233, .6);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 8px rgba(102, 175, 233, .6)
}

.form-control::-moz-placeholder {
    color: #999;
    opacity: 1
}

.form-control:-ms-input-placeholder {
    color: #999
}

.form-control::-webkit-input-placeholder {
    color: #999
}

.form-control::-ms-expand {
    background-color: transparent;
    border: 0
}

.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
    background-color: #eee;
    opacity: 1
}

.form-control[disabled],
fieldset[disabled] .form-control {
    cursor: not-allowed
}

textarea.form-control {
    height: auto
}

input[type=search] {
    -webkit-appearance: none
}

@media screen and (-webkit-min-device-pixel-ratio:0) {

    input[type=date].form-control,
    input[type=datetime-local].form-control,
    input[type=month].form-control,
    input[type=time].form-control {
        line-height: 34px
    }

    .input-group-sm input[type=date],
    .input-group-sm input[type=datetime-local],
    .input-group-sm input[type=month],
    .input-group-sm input[type=time],
    input[type=date].input-sm,
    input[type=datetime-local].input-sm,
    input[type=month].input-sm,
    input[type=time].input-sm {
        line-height: 30px
    }

    .input-group-lg input[type=date],
    .input-group-lg input[type=datetime-local],
    .input-group-lg input[type=month],
    .input-group-lg input[type=time],
    input[type=date].input-lg,
    input[type=datetime-local].input-lg,
    input[type=month].input-lg,
    input[type=time].input-lg {
        line-height: 46px
    }
}

.form-group {
    margin-bottom: 15px
}

.checkbox,
.radio {
    position: relative;
    display: block;
    margin-top: 10px;
    margin-bottom: 10px
}

.checkbox label,
.radio label {
    min-height: 20px;
    padding-left: 20px;
    margin-bottom: 0;
    font-weight: 400;
    cursor: pointer
}

.checkbox-inline input[type=checkbox],
.checkbox input[type=checkbox],
.radio-inline input[type=radio],
.radio input[type=radio] {
    position: absolute;
    margin-top: 4px\9;
    margin-left: -20px
}

.checkbox+.checkbox,
.radio+.radio {
    margin-top: -5px
}

.checkbox-inline,
.radio-inline {
    position: relative;
    display: inline-block;
    padding-left: 20px;
    margin-bottom: 0;
    font-weight: 400;
    vertical-align: middle;
    cursor: pointer
}

.checkbox-inline+.checkbox-inline,
.radio-inline+.radio-inline {
    margin-top: 0;
    margin-left: 10px
}

.checkbox-inline.disabled,
.checkbox.disabled label,
.radio-inline.disabled,
.radio.disabled label,
fieldset[disabled] .checkbox-inline,
fieldset[disabled] .checkbox label,
fieldset[disabled] .radio-inline,
fieldset[disabled] .radio label,
fieldset[disabled] input[type=checkbox],
fieldset[disabled] input[type=radio],
input[type=checkbox].disabled,
input[type=checkbox][disabled],
input[type=radio].disabled,
input[type=radio][disabled] {
    cursor: not-allowed
}

.form-control-static {
    min-height: 34px;
    padding-top: 7px;
    padding-bottom: 7px;
    margin-bottom: 0
}

.form-control-static.input-lg,
.form-control-static.input-sm {
    padding-right: 0;
    padding-left: 0
}

.input-sm {
    height: 30px;
    padding: 5px 10px;
    font-size: 12px;
    line-height: 1.5;
    border-radius: 3px
}

select.input-sm {
    height: 30px;
    line-height: 30px
}

select[multiple].input-sm,
textarea.input-sm {
    height: auto
}

.form-group-sm .form-control {
    height: 30px;
    padding: 5px 10px;
    font-size: 12px;
    line-height: 1.5;
    border-radius: 3px
}

.form-group-sm select.form-control {
    height: 30px;
    line-height: 30px
}

.form-group-sm select[multiple].form-control,
.form-group-sm textarea.form-control {
    height: auto
}

.form-group-sm .form-control-static {
    height: 30px;
    min-height: 32px;
    padding: 6px 10px;
    font-size: 12px;
    line-height: 1.5
}

.input-lg {
    height: 46px;
    padding: 10px 16px;
    font-size: 18px;
    line-height: 1.3333333;
    border-radius: 6px
}

select.input-lg {
    height: 46px;
    line-height: 46px
}

select[multiple].input-lg,
textarea.input-lg {
    height: auto
}

.form-group-lg .form-control {
    height: 46px;
    padding: 10px 16px;
    font-size: 18px;
    line-height: 1.3333333;
    border-radius: 6px
}

.form-group-lg select.form-control {
    height: 46px;
    line-height: 46px
}

.form-group-lg select[multiple].form-control,
.form-group-lg textarea.form-control {
    height: auto
}

.form-group-lg .form-control-static {
    height: 46px;
    min-height: 38px;
    padding: 11px 16px;
    font-size: 18px;
    line-height: 1.3333333
}

.has-feedback {
    position: relative
}

.has-feedback .form-control {
    padding-right: 42.5px
}

.form-control-feedback {
    position: absolute;
    top: 0;
    right: 0;
    z-index: 2;
    display: block;
    width: 34px;
    height: 34px;
    line-height: 34px;
    text-align: center;
    pointer-events: none
}

.form-group-lg .form-control+.form-control-feedback,
.input-group-lg+.form-control-feedback,
.input-lg+.form-control-feedback {
    width: 46px;
    height: 46px;
    line-height: 46px
}

.form-group-sm .form-control+.form-control-feedback,
.input-group-sm+.form-control-feedback,
.input-sm+.form-control-feedback {
    width: 30px;
    height: 30px;
    line-height: 30px
}

.has-success .checkbox,
.has-success .checkbox-inline,
.has-success.checkbox-inline label,
.has-success.checkbox label,
.has-success .control-label,
.has-success .help-block,
.has-success .radio,
.has-success .radio-inline,
.has-success.radio-inline label,
.has-success.radio label {
    color: #3c763d
}

.has-success .form-control {
    border-color: #3c763d;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075)
}

.has-success .form-control:focus {
    border-color: #2b542c;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 6px #67b168;
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 6px #67b168
}

.has-success .input-group-addon {
    color: #3c763d;
    background-color: #dff0d8;
    border-color: #3c763d
}

.has-success .form-control-feedback {
    color: #3c763d
}

.has-warning .checkbox,
.has-warning .checkbox-inline,
.has-warning.checkbox-inline label,
.has-warning.checkbox label,
.has-warning .control-label,
.has-warning .help-block,
.has-warning .radio,
.has-warning .radio-inline,
.has-warning.radio-inline label,
.has-warning.radio label {
    color: #8a6d3b
}

.has-warning .form-control {
    border-color: #8a6d3b;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075)
}

.has-warning .form-control:focus {
    border-color: #66512c;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 6px #c0a16b;
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 6px #c0a16b
}

.has-warning .input-group-addon {
    color: #8a6d3b;
    background-color: #fcf8e3;
    border-color: #8a6d3b
}

.has-warning .form-control-feedback {
    color: #8a6d3b
}

.has-error .checkbox,
.has-error .checkbox-inline,
.has-error.checkbox-inline label,
.has-error.checkbox label,
.has-error .control-label,
.has-error .help-block,
.has-error .radio,
.has-error .radio-inline,
.has-error.radio-inline label,
.has-error.radio label {
    color: #a94442
}

.has-error .form-control {
    border-color: #a94442;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075)
}

.has-error .form-control:focus {
    border-color: #843534;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 6px #ce8483;
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .075), 0 0 6px #ce8483
}

.has-error .input-group-addon {
    color: #a94442;
    background-color: #f2dede;
    border-color: #a94442
}

.has-error .form-control-feedback {
    color: #a94442
}

.has-feedback label~.form-control-feedback {
    top: 25px
}

.has-feedback label.sr-only~.form-control-feedback {
    top: 0
}

.help-block {
    display: block;
    margin-top: 5px;
    margin-bottom: 10px;
    color: #737373
}

@media (min-width:768px) {
    .form-inline .form-group {
        display: inline-block;
        margin-bottom: 0;
        vertical-align: middle
    }

    .form-inline .form-control {
        display: inline-block;
        width: auto;
        vertical-align: middle
    }

    .form-inline .form-control-static {
        display: inline-block
    }

    .form-inline .input-group {
        display: inline-table;
        vertical-align: middle
    }

    .form-inline .input-group .form-control,
    .form-inline .input-group .input-group-addon,
    .form-inline .input-group .input-group-btn {
        width: auto
    }

    .form-inline .input-group>.form-control {
        width: 100%
    }

    .form-inline .control-label {
        margin-bottom: 0;
        vertical-align: middle
    }

    .form-inline .checkbox,
    .form-inline .radio {
        display: inline-block;
        margin-top: 0;
        margin-bottom: 0;
        vertical-align: middle
    }

    .form-inline .checkbox label,
    .form-inline .radio label {
        padding-left: 0
    }

    .form-inline .checkbox input[type=checkbox],
    .form-inline .radio input[type=radio] {
        position: relative;
        margin-left: 0
    }

    .form-inline .has-feedback .form-control-feedback {
        top: 0
    }
}

.form-horizontal .checkbox,
.form-horizontal .checkbox-inline,
.form-horizontal .radio,
.form-horizontal .radio-inline {
    padding-top: 7px;
    margin-top: 0;
    margin-bottom: 0
}

.form-horizontal .checkbox,
.form-horizontal .radio {
    min-height: 27px
}

.form-horizontal .form-group {
    margin-right: -15px;
    margin-left: -15px
}

@media (min-width:768px) {
    .form-horizontal .control-label {
        padding-top: 7px;
        margin-bottom: 0;
        text-align: right
    }
}

.form-horizontal .has-feedback .form-control-feedback {
    right: 15px
}

@media (min-width:768px) {
    .form-horizontal .form-group-lg .control-label {
        padding-top: 11px;
        font-size: 18px
    }
}

@media (min-width:768px) {
    .form-horizontal .form-group-sm .control-label {
        padding-top: 6px;
        font-size: 12px
    }
}

.btn {
    display: inline-block;
    padding: 6px 12px;
    margin-bottom: 0;
    font-size: 14px;
    font-weight: 400;
    line-height: 1.42857143;
    text-align: center;
    white-space: nowrap;
    vertical-align: middle;
    -ms-touch-action: manipulation;
    touch-action: manipulation;
    cursor: pointer;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    background-image: none;
    border: 1px solid transparent;
    border-radius: 4px
}

.btn.active.focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn:active:focus,
.btn:focus {
    outline: 5px auto -webkit-focus-ring-color;
    outline-offset: -2px
}

.btn.focus,
.btn:focus,
.btn:hover {
    color: #333;
    text-decoration: none
}

.btn.active,
.btn:active {
    background-image: none;
    outline: 0;
    -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125);
    box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125)
}

.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
    cursor: not-allowed;
    filter: alpha(opacity=65);
    -webkit-box-shadow: none;
    box-shadow: none;
    opacity: .65
}

a.btn.disabled,
fieldset[disabled] a.btn {
    pointer-events: none
}

.btn-default {
    color: #333;
    background-color: #fff;
    border-color: #ccc
}

.btn-default.focus,
.btn-default:focus {
    color: #333;
    background-color: #e6e6e6;
    border-color: #8c8c8c
}

.btn-default.active,
.btn-default:active,
.btn-default:hover,
.open>.dropdown-toggle.btn-default {
    color: #333;
    background-color: #e6e6e6;
    border-color: #adadad
}

.btn-default.active.focus,
.btn-default.active:focus,
.btn-default.active:hover,
.btn-default:active.focus,
.btn-default:active:focus,
.btn-default:active:hover,
.open>.dropdown-toggle.btn-default.focus,
.open>.dropdown-toggle.btn-default:focus,
.open>.dropdown-toggle.btn-default:hover {
    color: #333;
    background-color: #d4d4d4;
    border-color: #8c8c8c
}

.btn-default.active,
.btn-default:active,
.open>.dropdown-toggle.btn-default {
    background-image: none
}

.btn-default.disabled.focus,
.btn-default.disabled:focus,
.btn-default.disabled:hover,
.btn-default[disabled].focus,
.btn-default[disabled]:focus,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default.focus,
fieldset[disabled] .btn-default:focus,
fieldset[disabled] .btn-default:hover {
    background-color: #fff;
    border-color: #ccc
}

.btn-default .badge {
    color: #fff;
    background-color: #333
}

.btn-primary {
    color: #fff;
    background-color: #337ab7;
    border-color: #2e6da4
}

.btn-primary.focus,
.btn-primary:focus {
    color: #fff;
    background-color: #286090;
    border-color: #122b40
}

.btn-primary.active,
.btn-primary:active,
.btn-primary:hover,
.open>.dropdown-toggle.btn-primary {
    color: #fff;
    background-color: #286090;
    border-color: #204d74
}

.btn-primary.active.focus,
.btn-primary.active:focus,
.btn-primary.active:hover,
.btn-primary:active.focus,
.btn-primary:active:focus,
.btn-primary:active:hover,
.open>.dropdown-toggle.btn-primary.focus,
.open>.dropdown-toggle.btn-primary:focus,
.open>.dropdown-toggle.btn-primary:hover {
    color: #fff;
    background-color: #204d74;
    border-color: #122b40
}

.btn-primary.active,
.btn-primary:active,
.open>.dropdown-toggle.btn-primary {
    background-image: none
}

.btn-primary.disabled.focus,
.btn-primary.disabled:focus,
.btn-primary.disabled:hover,
.btn-primary[disabled].focus,
.btn-primary[disabled]:focus,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary.focus,
fieldset[disabled] .btn-primary:focus,
fieldset[disabled] .btn-primary:hover {
    background-color: #337ab7;
    border-color: #2e6da4
}

.btn-primary .badge {
    color: #337ab7;
    background-color: #fff
}

.btn-success {
    color: #fff;
    background-color: #5cb85c;
    border-color: #4cae4c
}

.btn-success.focus,
.btn-success:focus {
    color: #fff;
    background-color: #449d44;
    border-color: #255625
}

.btn-success.active,
.btn-success:active,
.btn-success:hover,
.open>.dropdown-toggle.btn-success {
    color: #fff;
    background-color: #449d44;
    border-color: #398439
}

.btn-success.active.focus,
.btn-success.active:focus,
.btn-success.active:hover,
.btn-success:active.focus,
.btn-success:active:focus,
.btn-success:active:hover,
.open>.dropdown-toggle.btn-success.focus,
.open>.dropdown-toggle.btn-success:focus,
.open>.dropdown-toggle.btn-success:hover {
    color: #fff;
    background-color: #398439;
    border-color: #255625
}

.btn-success.active,
.btn-success:active,
.open>.dropdown-toggle.btn-success {
    background-image: none
}

.btn-success.disabled.focus,
.btn-success.disabled:focus,
.btn-success.disabled:hover,
.btn-success[disabled].focus,
.btn-success[disabled]:focus,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success.focus,
fieldset[disabled] .btn-success:focus,
fieldset[disabled] .btn-success:hover {
    background-color: #5cb85c;
    border-color: #4cae4c
}

.btn-success .badge {
    color: #5cb85c;
    background-color: #fff
}

.btn-info {
    color: #fff;
    background-color: #5bc0de;
    border-color: #46b8da
}

.btn-info.focus,
.btn-info:focus {
    color: #fff;
    background-color: #31b0d5;
    border-color: #1b6d85
}

.btn-info.active,
.btn-info:active,
.btn-info:hover,
.open>.dropdown-toggle.btn-info {
    color: #fff;
    background-color: #31b0d5;
    border-color: #269abc
}

.btn-info.active.focus,
.btn-info.active:focus,
.btn-info.active:hover,
.btn-info:active.focus,
.btn-info:active:focus,
.btn-info:active:hover,
.open>.dropdown-toggle.btn-info.focus,
.open>.dropdown-toggle.btn-info:focus,
.open>.dropdown-toggle.btn-info:hover {
    color: #fff;
    background-color: #269abc;
    border-color: #1b6d85
}

.btn-info.active,
.btn-info:active,
.open>.dropdown-toggle.btn-info {
    background-image: none
}

.btn-info.disabled.focus,
.btn-info.disabled:focus,
.btn-info.disabled:hover,
.btn-info[disabled].focus,
.btn-info[disabled]:focus,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info.focus,
fieldset[disabled] .btn-info:focus,
fieldset[disabled] .btn-info:hover {
    background-color: #5bc0de;
    border-color: #46b8da
}

.btn-info .badge {
    color: #5bc0de;
    background-color: #fff
}

.btn-warning {
    color: #fff;
    background-color: #f0ad4e;
    border-color: #eea236
}

.btn-warning.focus,
.btn-warning:focus {
    color: #fff;
    background-color: #ec971f;
    border-color: #985f0d
}

.btn-warning.active,
.btn-warning:active,
.btn-warning:hover,
.open>.dropdown-toggle.btn-warning {
    color: #fff;
    background-color: #ec971f;
    border-color: #d58512
}

.btn-warning.active.focus,
.btn-warning.active:focus,
.btn-warning.active:hover,
.btn-warning:active.focus,
.btn-warning:active:focus,
.btn-warning:active:hover,
.open>.dropdown-toggle.btn-warning.focus,
.open>.dropdown-toggle.btn-warning:focus,
.open>.dropdown-toggle.btn-warning:hover {
    color: #fff;
    background-color: #d58512;
    border-color: #985f0d
}

.btn-warning.active,
.btn-warning:active,
.open>.dropdown-toggle.btn-warning {
    background-image: none
}

.btn-warning.disabled.focus,
.btn-warning.disabled:focus,
.btn-warning.disabled:hover,
.btn-warning[disabled].focus,
.btn-warning[disabled]:focus,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning.focus,
fieldset[disabled] .btn-warning:focus,
fieldset[disabled] .btn-warning:hover {
    background-color: #f0ad4e;
    border-color: #eea236
}

.btn-warning .badge {
    color: #f0ad4e;
    background-color: #fff
}

.btn-danger {
    color: #fff;
    background-color: #d9534f;
    border-color: #d43f3a
}

.btn-danger.focus,
.btn-danger:focus {
    color: #fff;
    background-color: #c9302c;
    border-color: #761c19
}

.btn-danger.active,
.btn-danger:active,
.btn-danger:hover,
.open>.dropdown-toggle.btn-danger {
    color: #fff;
    background-color: #c9302c;
    border-color: #ac2925
}

.btn-danger.active.focus,
.btn-danger.active:focus,
.btn-danger.active:hover,
.btn-danger:active.focus,
.btn-danger:active:focus,
.btn-danger:active:hover,
.open>.dropdown-toggle.btn-danger.focus,
.open>.dropdown-toggle.btn-danger:focus,
.open>.dropdown-toggle.btn-danger:hover {
    color: #fff;
    background-color: #ac2925;
    border-color: #761c19
}

.btn-danger.active,
.btn-danger:active,
.open>.dropdown-toggle.btn-danger {
    background-image: none
}

.btn-danger.disabled.focus,
.btn-danger.disabled:focus,
.btn-danger.disabled:hover,
.btn-danger[disabled].focus,
.btn-danger[disabled]:focus,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger.focus,
fieldset[disabled] .btn-danger:focus,
fieldset[disabled] .btn-danger:hover {
    background-color: #d9534f;
    border-color: #d43f3a
}

.btn-danger .badge {
    color: #d9534f;
    background-color: #fff
}

.btn-link {
    font-weight: 400;
    color: #337ab7;
    border-radius: 0
}

.btn-link,
.btn-link.active,
.btn-link:active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
    background-color: transparent;
    -webkit-box-shadow: none;
    box-shadow: none
}

.btn-link,
.btn-link:active,
.btn-link:focus,
.btn-link:hover {
    border-color: transparent
}

.btn-link:focus,
.btn-link:hover {
    color: #23527c;
    text-decoration: underline;
    background-color: transparent
}

.btn-link[disabled]:focus,
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:focus,
fieldset[disabled] .btn-link:hover {
    color: #777;
    text-decoration: none
}

.btn-group-lg>.btn,
.btn-lg {
    padding: 10px 16px;
    font-size: 18px;
    line-height: 1.3333333;
    border-radius: 6px
}

.btn-group-sm>.btn,
.btn-sm {
    padding: 5px 10px;
    font-size: 12px;
    line-height: 1.5;
    border-radius: 3px
}

.btn-group-xs>.btn,
.btn-xs {
    padding: 1px 5px;
    font-size: 12px;
    line-height: 1.5;
    border-radius: 3px
}

.btn-block {
    display: block;
    width: 100%
}

.btn-block+.btn-block {
    margin-top: 5px
}

input[type=button].btn-block,
input[type=reset].btn-block,
input[type=submit].btn-block {
    width: 100%
}

.fade {
    opacity: 0;
    -webkit-transition: opacity .15s linear;
    -o-transition: opacity .15s linear;
    transition: opacity .15s linear
}

.fade.in {
    opacity: 1
}

.collapse {
    display: none
}

.collapse.in {
    display: block
}

tr.collapse.in {
    display: table-row
}

tbody.collapse.in {
    display: table-row-group
}

.collapsing {
    position: relative;
    height: 0;
    overflow: hidden;
    -webkit-transition-timing-function: ease;
    -o-transition-timing-function: ease;
    transition-timing-function: ease;
    -webkit-transition-duration: .35s;
    -o-transition-duration: .35s;
    transition-duration: .35s;
    -webkit-transition-property: height, visibility;
    -o-transition-property: height, visibility;
    transition-property: height, visibility
}

.caret {
    display: inline-block;
    width: 0;
    height: 0;
    margin-left: 2px;
    vertical-align: middle;
    border-top: 4px dashed;
    border-top: 4px solid\9;
    border-right: 4px solid transparent;
    border-left: 4px solid transparent
}

.dropdown,
.dropup {
    position: relative
}

.dropdown-toggle:focus {
    outline: 0
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
    font-size: 14px;
    text-align: left;
    list-style: none;
    background-color: #fff;
    background-clip: padding-box;
    border: 1px solid #ccc;
    border: 1px solid rgba(0, 0, 0, .15);
    border-radius: 4px;
    -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, .175);
    box-shadow: 0 6px 12px rgba(0, 0, 0, .175)
}

.dropdown-menu.pull-right {
    right: 0;
    left: auto
}

.dropdown-menu .divider {
    height: 1px;
    margin: 9px 0;
    overflow: hidden;
    background-color: #e5e5e5
}

.dropdown-menu>li>a {
    display: block;
    padding: 3px 20px;
    clear: both;
    font-weight: 400;
    line-height: 1.42857143;
    color: #333;
    white-space: nowrap
}

.dropdown-menu>li>a:focus,
.dropdown-menu>li>a:hover {
    color: #262626;
    text-decoration: none;
    background-color: #f5f5f5
}

.dropdown-menu>.active>a,
.dropdown-menu>.active>a:focus,
.dropdown-menu>.active>a:hover {
    color: #fff;
    text-decoration: none;
    background-color: #337ab7;
    outline: 0
}

.dropdown-menu>.disabled>a,
.dropdown-menu>.disabled>a:focus,
.dropdown-menu>.disabled>a:hover {
    color: #777
}

.dropdown-menu>.disabled>a:focus,
.dropdown-menu>.disabled>a:hover {
    text-decoration: none;
    cursor: not-allowed;
    background-color: transparent;
    background-image: none;
    filter: progid:DXImageTransform.Microsoft.gradient(enabled=false)
}

.open>.dropdown-menu {
    display: block
}

.open>a {
    outline: 0
}

.dropdown-menu-right {
    right: 0;
    left: auto
}

.dropdown-menu-left {
    right: auto;
    left: 0
}

.dropdown-header {
    display: block;
    padding: 3px 20px;
    font-size: 12px;
    line-height: 1.42857143;
    color: #777;
    white-space: nowrap
}

.dropdown-backdrop {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    z-index: 990
}

.pull-right>.dropdown-menu {
    right: 0;
    left: auto
}

.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
    content: "";
    border-top: 0;
    border-bottom: 4px dashed;
    border-bottom: 4px solid\9
}

.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
    top: auto;
    bottom: 100%;
    margin-bottom: 2px
}

@media (min-width:768px) {
    .navbar-right .dropdown-menu {
        right: 0;
        left: auto
    }

    .navbar-right .dropdown-menu-left {
        right: auto;
        left: 0
    }
}

.btn-group,
.btn-group-vertical {
    position: relative;
    display: inline-block;
    vertical-align: middle
}

.btn-group-vertical>.btn,
.btn-group>.btn {
    position: relative;
    float: left
}

.btn-group-vertical>.btn.active,
.btn-group-vertical>.btn:active,
.btn-group-vertical>.btn:focus,
.btn-group-vertical>.btn:hover,
.btn-group>.btn.active,
.btn-group>.btn:active,
.btn-group>.btn:focus,
.btn-group>.btn:hover {
    z-index: 2
}

.btn-group .btn+.btn,
.btn-group .btn+.btn-group,
.btn-group .btn-group+.btn,
.btn-group .btn-group+.btn-group {
    margin-left: -1px
}

.btn-toolbar {
    margin-left: -5px
}

.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
    float: left
}

.btn-toolbar>.btn,
.btn-toolbar>.btn-group,
.btn-toolbar>.input-group {
    margin-left: 5px
}

.btn-group>.btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
    border-radius: 0
}

.btn-group>.btn:first-child {
    margin-left: 0
}

.btn-group>.btn:first-child:not(:last-child):not(.dropdown-toggle) {
    border-top-right-radius: 0;
    border-bottom-right-radius: 0
}

.btn-group>.btn:last-child:not(:first-child),
.btn-group>.dropdown-toggle:not(:first-child) {
    border-top-left-radius: 0;
    border-bottom-left-radius: 0
}

.btn-group>.btn-group {
    float: left
}

.btn-group>.btn-group:not(:first-child):not(:last-child)>.btn {
    border-radius: 0
}

.btn-group>.btn-group:first-child:not(:last-child)>.btn:last-child,
.btn-group>.btn-group:first-child:not(:last-child)>.dropdown-toggle {
    border-top-right-radius: 0;
    border-bottom-right-radius: 0
}

.btn-group>.btn-group:last-child:not(:first-child)>.btn:first-child {
    border-top-left-radius: 0;
    border-bottom-left-radius: 0
}

.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
    outline: 0
}

.btn-group>.btn+.dropdown-toggle {
    padding-right: 8px;
    padding-left: 8px
}

.btn-group>.btn-lg+.dropdown-toggle {
    padding-right: 12px;
    padding-left: 12px
}

.btn-group.open .dropdown-toggle {
    -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125);
    box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125)
}

.btn-group.open .dropdown-toggle.btn-link {
    -webkit-box-shadow: none;
    box-shadow: none
}

.btn .caret {
    margin-left: 0
}

.btn-lg .caret {
    border-width: 5px 5px 0
}

.dropup .btn-lg .caret {
    border-width: 0 5px 5px
}

.btn-group-vertical>.btn,
.btn-group-vertical>.btn-group,
.btn-group-vertical>.btn-group>.btn {
    display: block;
    float: none;
    width: 100%;
    max-width: 100%
}

.btn-group-vertical>.btn-group>.btn {
    float: none
}

.btn-group-vertical>.btn+.btn,
.btn-group-vertical>.btn+.btn-group,
.btn-group-vertical>.btn-group+.btn,
.btn-group-vertical>.btn-group+.btn-group {
    margin-top: -1px;
    margin-left: 0
}

.btn-group-vertical>.btn:not(:first-child):not(:last-child) {
    border-radius: 0
}

.btn-group-vertical>.btn:first-child:not(:last-child) {
    border-top-left-radius: 4px;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 0
}

.btn-group-vertical>.btn:last-child:not(:first-child) {
    border-top-left-radius: 0;
    border-top-right-radius: 0;
    border-bottom-right-radius: 4px;
    border-bottom-left-radius: 4px
}

.btn-group-vertical>.btn-group:not(:first-child):not(:last-child)>.btn {
    border-radius: 0
}

.btn-group-vertical>.btn-group:first-child:not(:last-child)>.btn:last-child,
.btn-group-vertical>.btn-group:first-child:not(:last-child)>.dropdown-toggle {
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 0
}

.btn-group-vertical>.btn-group:last-child:not(:first-child)>.btn:first-child {
    border-top-left-radius: 0;
    border-top-right-radius: 0
}

.btn-group-justified {
    display: table;
    width: 100%;
    table-layout: fixed;
    border-collapse: separate
}

.btn-group-justified>.btn,
.btn-group-justified>.btn-group {
    display: table-cell;
    float: none;
    width: 1%
}

.btn-group-justified>.btn-group .btn {
    width: 100%
}

.btn-group-justified>.btn-group .dropdown-menu {
    left: auto
}

[data-toggle=buttons]>.btn-group>.btn input[type=checkbox],
[data-toggle=buttons]>.btn-group>.btn input[type=radio],
[data-toggle=buttons]>.btn input[type=checkbox],
[data-toggle=buttons]>.btn input[type=radio] {
    position: absolute;
    clip: rect(0, 0, 0, 0);
    pointer-events: none
}

.input-group {
    position: relative;
    display: table;
    border-collapse: separate
}

.input-group[class*=col-] {
    float: none;
    padding-right: 0;
    padding-left: 0
}

.input-group .form-control {
    position: relative;
    z-index: 2;
    float: left;
    width: 100%;
    margin-bottom: 0
}

.input-group .form-control:focus {
    z-index: 3
}

.input-group-lg>.form-control,
.input-group-lg>.input-group-addon,
.input-group-lg>.input-group-btn>.btn {
    height: 46px;
    padding: 10px 16px;
    font-size: 18px;
    line-height: 1.3333333;
    border-radius: 6px
}

select.input-group-lg>.form-control,
select.input-group-lg>.input-group-addon,
select.input-group-lg>.input-group-btn>.btn {
    height: 46px;
    line-height: 46px
}

select[multiple].input-group-lg>.form-control,
select[multiple].input-group-lg>.input-group-addon,
select[multiple].input-group-lg>.input-group-btn>.btn,
textarea.input-group-lg>.form-control,
textarea.input-group-lg>.input-group-addon,
textarea.input-group-lg>.input-group-btn>.btn {
    height: auto
}

.input-group-sm>.form-control,
.input-group-sm>.input-group-addon,
.input-group-sm>.input-group-btn>.btn {
    height: 30px;
    padding: 5px 10px;
    font-size: 12px;
    line-height: 1.5;
    border-radius: 3px
}

select.input-group-sm>.form-control,
select.input-group-sm>.input-group-addon,
select.input-group-sm>.input-group-btn>.btn {
    height: 30px;
    line-height: 30px
}

select[multiple].input-group-sm>.form-control,
select[multiple].input-group-sm>.input-group-addon,
select[multiple].input-group-sm>.input-group-btn>.btn,
textarea.input-group-sm>.form-control,
textarea.input-group-sm>.input-group-addon,
textarea.input-group-sm>.input-group-btn>.btn {
    height: auto
}

.input-group-addon,
.input-group-btn,
.input-group .form-control {
    display: table-cell
}

.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
    border-radius: 0
}

.input-group-addon,
.input-group-btn {
    width: 1%;
    white-space: nowrap;
    vertical-align: middle
}

.input-group-addon {
    padding: 6px 12px;
    font-size: 14px;
    font-weight: 400;
    line-height: 1;
    color: #555;
    text-align: center;
    background-color: #eee;
    border: 1px solid #ccc;
    border-radius: 4px
}

.input-group-addon.input-sm {
    padding: 5px 10px;
    font-size: 12px;
    border-radius: 3px
}

.input-group-addon.input-lg {
    padding: 10px 16px;
    font-size: 18px;
    border-radius: 6px
}

.input-group-addon input[type=checkbox],
.input-group-addon input[type=radio] {
    margin-top: 0
}

.input-group-addon:first-child,
.input-group-btn:first-child>.btn,
.input-group-btn:first-child>.btn-group>.btn,
.input-group-btn:first-child>.dropdown-toggle,
.input-group-btn:last-child>.btn-group:not(:last-child)>.btn,
.input-group-btn:last-child>.btn:not(:last-child):not(.dropdown-toggle),
.input-group .form-control:first-child {
    border-top-right-radius: 0;
    border-bottom-right-radius: 0
}

.input-group-addon:first-child {
    border-right: 0
}

.input-group-addon:last-child,
.input-group-btn:first-child>.btn-group:not(:first-child)>.btn,
.input-group-btn:first-child>.btn:not(:first-child),
.input-group-btn:last-child>.btn,
.input-group-btn:last-child>.btn-group>.btn,
.input-group-btn:last-child>.dropdown-toggle,
.input-group .form-control:last-child {
    border-top-left-radius: 0;
    border-bottom-left-radius: 0
}

.input-group-addon:last-child {
    border-left: 0
}

.input-group-btn {
    font-size: 0;
    white-space: nowrap
}

.input-group-btn,
.input-group-btn>.btn {
    position: relative
}

.input-group-btn>.btn+.btn {
    margin-left: -1px
}

.input-group-btn>.btn:active,
.input-group-btn>.btn:focus,
.input-group-btn>.btn:hover {
    z-index: 2
}

.input-group-btn:first-child>.btn,
.input-group-btn:first-child>.btn-group {
    margin-right: -1px
}

.input-group-btn:last-child>.btn,
.input-group-btn:last-child>.btn-group {
    z-index: 2;
    margin-left: -1px
}

.nav {
    padding-left: 0;
    margin-bottom: 0;
    list-style: none
}

.nav>li,
.nav>li>a {
    position: relative;
    display: block
}

.nav>li>a {
    padding: 10px 15px
}

.nav>li>a:focus,
.nav>li>a:hover {
    text-decoration: none;
    background-color: #eee
}

.nav>li.disabled>a {
    color: #777
}

.nav>li.disabled>a:focus,
.nav>li.disabled>a:hover {
    color: #777;
    text-decoration: none;
    cursor: not-allowed;
    background-color: transparent
}

.nav .open>a,
.nav .open>a:focus,
.nav .open>a:hover {
    background-color: #eee;
    border-color: #337ab7
}

.nav .nav-divider {
    height: 1px;
    margin: 9px 0;
    overflow: hidden;
    background-color: #e5e5e5
}

.nav>li>a>img {
    max-width: none
}

.nav-tabs {
    border-bottom: 1px solid #ddd
}

.nav-tabs>li {
    float: left;
    margin-bottom: -1px
}

.nav-tabs>li>a {
    margin-right: 2px;
    line-height: 1.42857143;
    border: 1px solid transparent;
    border-radius: 4px 4px 0 0
}

.nav-tabs>li>a:hover {
    border-color: #eee #eee #ddd
}

.nav-tabs>li.active>a,
.nav-tabs>li.active>a:focus,
.nav-tabs>li.active>a:hover {
    color: #555;
    cursor: default;
    background-color: #fff;
    border: 1px solid;
    border-color: #ddd #ddd transparent
}

.nav-tabs.nav-justified {
    width: 100%;
    border-bottom: 0
}

.nav-tabs.nav-justified>li {
    float: none
}

.nav-tabs.nav-justified>li>a {
    margin-bottom: 5px;
    text-align: center
}

.nav-tabs.nav-justified>.dropdown .dropdown-menu {
    top: auto;
    left: auto
}

@media (min-width:768px) {
    .nav-tabs.nav-justified>li {
        display: table-cell;
        width: 1%
    }

    .nav-tabs.nav-justified>li>a {
        margin-bottom: 0
    }
}

.nav-tabs.nav-justified>li>a {
    margin-right: 0;
    border-radius: 4px
}

.nav-tabs.nav-justified>.active>a,
.nav-tabs.nav-justified>.active>a:focus,
.nav-tabs.nav-justified>.active>a:hover {
    border: 1px solid #ddd
}

@media (min-width:768px) {
    .nav-tabs.nav-justified>li>a {
        border-bottom: 1px solid #ddd;
        border-radius: 4px 4px 0 0
    }

    .nav-tabs.nav-justified>.active>a,
    .nav-tabs.nav-justified>.active>a:focus,
    .nav-tabs.nav-justified>.active>a:hover {
        border-bottom-color: #fff
    }
}

.nav-pills>li {
    float: left
}

.nav-pills>li>a {
    border-radius: 4px
}

.nav-pills>li+li {
    margin-left: 2px
}

.nav-pills>li.active>a,
.nav-pills>li.active>a:focus,
.nav-pills>li.active>a:hover {
    color: #fff;
    background-color: #337ab7
}

.nav-stacked>li {
    float: none
}

.nav-stacked>li+li {
    margin-top: 2px;
    margin-left: 0
}

.nav-justified {
    width: 100%
}

.nav-justified>li {
    float: none
}

.nav-justified>li>a {
    margin-bottom: 5px;
    text-align: center
}

.nav-justified>.dropdown .dropdown-menu {
    top: auto;
    left: auto
}

@media (min-width:768px) {
    .nav-justified>li {
        display: table-cell;
        width: 1%
    }

    .nav-justified>li>a {
        margin-bottom: 0
    }
}

.nav-tabs-justified {
    border-bottom: 0
}

.nav-tabs-justified>li>a {
    margin-right: 0;
    border-radius: 4px
}

.nav-tabs-justified>.active>a,
.nav-tabs-justified>.active>a:focus,
.nav-tabs-justified>.active>a:hover {
    border: 1px solid #ddd
}

@media (min-width:768px) {
    .nav-tabs-justified>li>a {
        border-bottom: 1px solid #ddd;
        border-radius: 4px 4px 0 0
    }

    .nav-tabs-justified>.active>a,
    .nav-tabs-justified>.active>a:focus,
    .nav-tabs-justified>.active>a:hover {
        border-bottom-color: #fff
    }
}

.tab-content>.tab-pane {
    display: none
}

.tab-content>.active {
    display: block
}

.nav-tabs .dropdown-menu {
    margin-top: -1px;
    border-top-left-radius: 0;
    border-top-right-radius: 0
}

.navbar {
    position: relative;
    min-height: 50px;
    margin-bottom: 20px;
    border: 1px solid transparent
}

@media (min-width:768px) {
    .navbar {
        border-radius: 4px
    }
}

@media (min-width:768px) {
    .navbar-header {
        float: left
    }
}

.navbar-collapse {
    padding-right: 15px;
    padding-left: 15px;
    overflow-x: visible;
    -webkit-overflow-scrolling: touch;
    border-top: 1px solid transparent;
    -webkit-box-shadow: inset 0 1px 0 hsla(0, 0%, 100%, .1);
    box-shadow: inset 0 1px 0 hsla(0, 0%, 100%, .1)
}

.navbar-collapse.in {
    overflow-y: auto
}

@media (min-width:768px) {
    .navbar-collapse {
        width: auto;
        border-top: 0;
        -webkit-box-shadow: none;
        box-shadow: none
    }

    .navbar-collapse.collapse {
        display: block !important;
        height: auto !important;
        padding-bottom: 0;
        overflow: visible !important
    }

    .navbar-collapse.in {
        overflow-y: visible
    }

    .navbar-fixed-bottom .navbar-collapse,
    .navbar-fixed-top .navbar-collapse,
    .navbar-static-top .navbar-collapse {
        padding-right: 0;
        padding-left: 0
    }
}

.navbar-fixed-bottom .navbar-collapse,
.navbar-fixed-top .navbar-collapse {
    max-height: 340px
}

@media (max-device-width:480px) and (orientation:landscape) {

    .navbar-fixed-bottom .navbar-collapse,
    .navbar-fixed-top .navbar-collapse {
        max-height: 200px
    }
}

.container-fluid>.navbar-collapse,
.container-fluid>.navbar-header,
.container>.navbar-collapse,
.container>.navbar-header {
    margin-right: -15px;
    margin-left: -15px
}

@media (min-width:768px) {

    .container-fluid>.navbar-collapse,
    .container-fluid>.navbar-header,
    .container>.navbar-collapse,
    .container>.navbar-header {
        margin-right: 0;
        margin-left: 0
    }
}

.navbar-static-top {
    z-index: 1000;
    border-width: 0 0 1px
}

@media (min-width:768px) {
    .navbar-static-top {
        border-radius: 0
    }
}

.navbar-fixed-bottom,
.navbar-fixed-top {
    position: fixed;
    right: 0;
    left: 0;
    z-index: 1030
}

@media (min-width:768px) {

    .navbar-fixed-bottom,
    .navbar-fixed-top {
        border-radius: 0
    }
}

.navbar-fixed-top {
    top: 0;
    border-width: 0 0 1px
}

.navbar-fixed-bottom {
    bottom: 0;
    margin-bottom: 0;
    border-width: 1px 0 0
}

.navbar-brand {
    float: left;
    height: 50px;
    padding: 15px;
    font-size: 18px;
    line-height: 20px
}

.navbar-brand:focus,
.navbar-brand:hover {
    text-decoration: none
}

.navbar-brand>img {
    display: block
}

@media (min-width:768px) {

    .navbar>.container-fluid .navbar-brand,
    .navbar>.container .navbar-brand {
        margin-left: -15px
    }
}

.navbar-toggle {
    position: relative;
    float: right;
    padding: 9px 10px;
    margin-top: 8px;
    margin-right: 15px;
    margin-bottom: 8px;
    background-color: transparent;
    background-image: none;
    border: 1px solid transparent;
    border-radius: 4px
}

.navbar-toggle:focus {
    outline: 0
}

.navbar-toggle .icon-bar {
    display: block;
    width: 22px;
    height: 2px;
    border-radius: 1px
}

.navbar-toggle .icon-bar+.icon-bar {
    margin-top: 4px
}

@media (min-width:768px) {
    .navbar-toggle {
        display: none
    }
}

.navbar-nav {
    margin: 7.5px -15px
}

.navbar-nav>li>a {
    padding-top: 10px;
    padding-bottom: 10px;
    line-height: 20px
}

@media (max-width:767px) {
    .navbar-nav .open .dropdown-menu {
        position: static;
        float: none;
        width: auto;
        margin-top: 0;
        background-color: transparent;
        border: 0;
        -webkit-box-shadow: none;
        box-shadow: none
    }

    .navbar-nav .open .dropdown-menu .dropdown-header,
    .navbar-nav .open .dropdown-menu>li>a {
        padding: 5px 15px 5px 25px
    }

    .navbar-nav .open .dropdown-menu>li>a {
        line-height: 20px
    }

    .navbar-nav .open .dropdown-menu>li>a:focus,
    .navbar-nav .open .dropdown-menu>li>a:hover {
        background-image: none
    }
}

@media (min-width:768px) {
    .navbar-nav {
        float: left;
        margin: 0
    }

    .navbar-nav>li {
        float: left
    }

    .navbar-nav>li>a {
        padding-top: 15px;
        padding-bottom: 15px
    }
}

.navbar-form {
    padding: 10px 15px;
    margin: 8px -15px;
    border-top: 1px solid transparent;
    border-bottom: 1px solid transparent;
    -webkit-box-shadow: inset 0 1px 0 hsla(0, 0%, 100%, .1), 0 1px 0 hsla(0, 0%, 100%, .1);
    box-shadow: inset 0 1px 0 hsla(0, 0%, 100%, .1), 0 1px 0 hsla(0, 0%, 100%, .1)
}

@media (min-width:768px) {
    .navbar-form .form-group {
        display: inline-block;
        margin-bottom: 0;
        vertical-align: middle
    }

    .navbar-form .form-control {
        display: inline-block;
        width: auto;
        vertical-align: middle
    }

    .navbar-form .form-control-static {
        display: inline-block
    }

    .navbar-form .input-group {
        display: inline-table;
        vertical-align: middle
    }

    .navbar-form .input-group .form-control,
    .navbar-form .input-group .input-group-addon,
    .navbar-form .input-group .input-group-btn {
        width: auto
    }

    .navbar-form .input-group>.form-control {
        width: 100%
    }

    .navbar-form .control-label {
        margin-bottom: 0;
        vertical-align: middle
    }

    .navbar-form .checkbox,
    .navbar-form .radio {
        display: inline-block;
        margin-top: 0;
        margin-bottom: 0;
        vertical-align: middle
    }

    .navbar-form .checkbox label,
    .navbar-form .radio label {
        padding-left: 0
    }

    .navbar-form .checkbox input[type=checkbox],
    .navbar-form .radio input[type=radio] {
        position: relative;
        margin-left: 0
    }

    .navbar-form .has-feedback .form-control-feedback {
        top: 0
    }
}

@media (max-width:767px) {
    .navbar-form .form-group {
        margin-bottom: 5px
    }

    .navbar-form .form-group:last-child {
        margin-bottom: 0
    }
}

@media (min-width:768px) {
    .navbar-form {
        width: auto;
        padding-top: 0;
        padding-bottom: 0;
        margin-right: 0;
        margin-left: 0;
        border: 0;
        -webkit-box-shadow: none;
        box-shadow: none
    }
}

.navbar-nav>li>.dropdown-menu {
    margin-top: 0;
    border-top-left-radius: 0;
    border-top-right-radius: 0
}

.navbar-fixed-bottom .navbar-nav>li>.dropdown-menu {
    margin-bottom: 0;
    border-top-left-radius: 4px;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 0
}

.navbar-btn {
    margin-top: 8px;
    margin-bottom: 8px
}

.navbar-btn.btn-sm {
    margin-top: 10px;
    margin-bottom: 10px
}

.navbar-btn.btn-xs {
    margin-top: 14px;
    margin-bottom: 14px
}

.navbar-text {
    margin-top: 15px;
    margin-bottom: 15px
}

@media (min-width:768px) {
    .navbar-text {
        float: left;
        margin-right: 15px;
        margin-left: 15px
    }
}

@media (min-width:768px) {
    .navbar-left {
        float: left !important
    }

    .navbar-right {
        float: right !important;
        margin-right: -15px
    }

    .navbar-right~.navbar-right {
        margin-right: 0
    }
}

.navbar-default {
    background-color: #f8f8f8;
    border-color: #e7e7e7
}

.navbar-default .navbar-brand {
    color: #777
}

.navbar-default .navbar-brand:focus,
.navbar-default .navbar-brand:hover {
    color: #5e5e5e;
    background-color: transparent
}

.navbar-default .navbar-nav>li>a,
.navbar-default .navbar-text {
    color: #777
}

.navbar-default .navbar-nav>li>a:focus,
.navbar-default .navbar-nav>li>a:hover {
    color: #333;
    background-color: transparent
}

.navbar-default .navbar-nav>.active>a,
.navbar-default .navbar-nav>.active>a:focus,
.navbar-default .navbar-nav>.active>a:hover {
    color: #555;
    background-color: #e7e7e7
}

.navbar-default .navbar-nav>.disabled>a,
.navbar-default .navbar-nav>.disabled>a:focus,
.navbar-default .navbar-nav>.disabled>a:hover {
    color: #ccc;
    background-color: transparent
}

.navbar-default .navbar-toggle {
    border-color: #ddd
}

.navbar-default .navbar-toggle:focus,
.navbar-default .navbar-toggle:hover {
    background-color: #ddd
}

.navbar-default .navbar-toggle .icon-bar {
    background-color: #888
}

.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
    border-color: #e7e7e7
}

.navbar-default .navbar-nav>.open>a,
.navbar-default .navbar-nav>.open>a:focus,
.navbar-default .navbar-nav>.open>a:hover {
    color: #555;
    background-color: #e7e7e7
}

@media (max-width:767px) {
    .navbar-default .navbar-nav .open .dropdown-menu>li>a {
        color: #777
    }

    .navbar-default .navbar-nav .open .dropdown-menu>li>a:focus,
    .navbar-default .navbar-nav .open .dropdown-menu>li>a:hover {
        color: #333;
        background-color: transparent
    }

    .navbar-default .navbar-nav .open .dropdown-menu>.active>a,
    .navbar-default .navbar-nav .open .dropdown-menu>.active>a:focus,
    .navbar-default .navbar-nav .open .dropdown-menu>.active>a:hover {
        color: #555;
        background-color: #e7e7e7
    }

    .navbar-default .navbar-nav .open .dropdown-menu>.disabled>a,
    .navbar-default .navbar-nav .open .dropdown-menu>.disabled>a:focus,
    .navbar-default .navbar-nav .open .dropdown-menu>.disabled>a:hover {
        color: #ccc;
        background-color: transparent
    }
}

.navbar-default .navbar-link {
    color: #777
}

.navbar-default .navbar-link:hover {
    color: #333
}

.navbar-default .btn-link {
    color: #777
}

.navbar-default .btn-link:focus,
.navbar-default .btn-link:hover {
    color: #333
}

.navbar-default .btn-link[disabled]:focus,
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:focus,
fieldset[disabled] .navbar-default .btn-link:hover {
    color: #ccc
}

.navbar-inverse {
    background-color: #222;
    border-color: #080808
}

.navbar-inverse .navbar-brand {
    color: #9d9d9d
}

.navbar-inverse .navbar-brand:focus,
.navbar-inverse .navbar-brand:hover {
    color: #fff;
    background-color: transparent
}

.navbar-inverse .navbar-nav>li>a,
.navbar-inverse .navbar-text {
    color: #9d9d9d
}

.navbar-inverse .navbar-nav>li>a:focus,
.navbar-inverse .navbar-nav>li>a:hover {
    color: #fff;
    background-color: transparent
}

.navbar-inverse .navbar-nav>.active>a,
.navbar-inverse .navbar-nav>.active>a:focus,
.navbar-inverse .navbar-nav>.active>a:hover {
    color: #fff;
    background-color: #080808
}

.navbar-inverse .navbar-nav>.disabled>a,
.navbar-inverse .navbar-nav>.disabled>a:focus,
.navbar-inverse .navbar-nav>.disabled>a:hover {
    color: #444;
    background-color: transparent
}

.navbar-inverse .navbar-toggle {
    border-color: #333
}

.navbar-inverse .navbar-toggle:focus,
.navbar-inverse .navbar-toggle:hover {
    background-color: #333
}

.navbar-inverse .navbar-toggle .icon-bar {
    background-color: #fff
}

.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
    border-color: #101010
}

.navbar-inverse .navbar-nav>.open>a,
.navbar-inverse .navbar-nav>.open>a:focus,
.navbar-inverse .navbar-nav>.open>a:hover {
    color: #fff;
    background-color: #080808
}

@media (max-width:767px) {
    .navbar-inverse .navbar-nav .open .dropdown-menu>.dropdown-header {
        border-color: #080808
    }

    .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
        background-color: #080808
    }

    .navbar-inverse .navbar-nav .open .dropdown-menu>li>a {
        color: #9d9d9d
    }

    .navbar-inverse .navbar-nav .open .dropdown-menu>li>a:focus,
    .navbar-inverse .navbar-nav .open .dropdown-menu>li>a:hover {
        color: #fff;
        background-color: transparent
    }

    .navbar-inverse .navbar-nav .open .dropdown-menu>.active>a,
    .navbar-inverse .navbar-nav .open .dropdown-menu>.active>a:focus,
    .navbar-inverse .navbar-nav .open .dropdown-menu>.active>a:hover {
        color: #fff;
        background-color: #080808
    }

    .navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a,
    .navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a:focus,
    .navbar-inverse .navbar-nav .open .dropdown-menu>.disabled>a:hover {
        color: #444;
        background-color: transparent
    }
}

.navbar-inverse .navbar-link {
    color: #9d9d9d
}

.navbar-inverse .navbar-link:hover {
    color: #fff
}

.navbar-inverse .btn-link {
    color: #9d9d9d
}

.navbar-inverse .btn-link:focus,
.navbar-inverse .btn-link:hover {
    color: #fff
}

.navbar-inverse .btn-link[disabled]:focus,
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:focus,
fieldset[disabled] .navbar-inverse .btn-link:hover {
    color: #444
}

.breadcrumb {
    padding: 8px 15px;
    margin-bottom: 20px;
    list-style: none;
    background-color: #f5f5f5;
    border-radius: 4px
}

.breadcrumb>li {
    display: inline-block
}

.breadcrumb>li+li:before {
    padding: 0 5px;
    color: #ccc;
    content: "/\A0"
}

.breadcrumb>.active {
    color: #777
}

.pagination {
    display: inline-block;
    padding-left: 0;
    margin: 20px 0;
    border-radius: 4px
}

.pagination>li {
    display: inline
}

.pagination>li>a,
.pagination>li>span {
    position: relative;
    float: left;
    padding: 6px 12px;
    margin-left: -1px;
    line-height: 1.42857143;
    color: #337ab7;
    text-decoration: none;
    background-color: #fff;
    border: 1px solid #ddd
}

.pagination>li:first-child>a,
.pagination>li:first-child>span {
    margin-left: 0;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px
}

.pagination>li:last-child>a,
.pagination>li:last-child>span {
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px
}

.pagination>li>a:focus,
.pagination>li>a:hover,
.pagination>li>span:focus,
.pagination>li>span:hover {
    z-index: 2;
    color: #23527c;
    background-color: #eee;
    border-color: #ddd
}

.pagination>.active>a,
.pagination>.active>a:focus,
.pagination>.active>a:hover,
.pagination>.active>span,
.pagination>.active>span:focus,
.pagination>.active>span:hover {
    z-index: 3;
    color: #fff;
    cursor: default;
    background-color: #337ab7;
    border-color: #337ab7
}

.pagination>.disabled>a,
.pagination>.disabled>a:focus,
.pagination>.disabled>a:hover,
.pagination>.disabled>span,
.pagination>.disabled>span:focus,
.pagination>.disabled>span:hover {
    color: #777;
    cursor: not-allowed;
    background-color: #fff;
    border-color: #ddd
}

.pagination-lg>li>a,
.pagination-lg>li>span {
    padding: 10px 16px;
    font-size: 18px;
    line-height: 1.3333333
}

.pagination-lg>li:first-child>a,
.pagination-lg>li:first-child>span {
    border-top-left-radius: 6px;
    border-bottom-left-radius: 6px
}

.pagination-lg>li:last-child>a,
.pagination-lg>li:last-child>span {
    border-top-right-radius: 6px;
    border-bottom-right-radius: 6px
}

.pagination-sm>li>a,
.pagination-sm>li>span {
    padding: 5px 10px;
    font-size: 12px;
    line-height: 1.5
}

.pagination-sm>li:first-child>a,
.pagination-sm>li:first-child>span {
    border-top-left-radius: 3px;
    border-bottom-left-radius: 3px
}

.pagination-sm>li:last-child>a,
.pagination-sm>li:last-child>span {
    border-top-right-radius: 3px;
    border-bottom-right-radius: 3px
}

.pager {
    padding-left: 0;
    margin: 20px 0;
    text-align: center;
    list-style: none
}

.pager li {
    display: inline
}

.pager li>a,
.pager li>span {
    display: inline-block;
    padding: 5px 14px;
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 15px
}

.pager li>a:focus,
.pager li>a:hover {
    text-decoration: none;
    background-color: #eee
}

.pager .next>a,
.pager .next>span {
    float: right
}

.pager .previous>a,
.pager .previous>span {
    float: left
}

.pager .disabled>a,
.pager .disabled>a:focus,
.pager .disabled>a:hover,
.pager .disabled>span {
    color: #777;
    cursor: not-allowed;
    background-color: #fff
}

.label {
    display: inline;
    padding: .2em .6em .3em;
    font-size: 75%;
    font-weight: 700;
    line-height: 1;
    color: #fff;
    text-align: center;
    white-space: nowrap;
    vertical-align: baseline;
    border-radius: .25em
}

a.label:focus,
a.label:hover {
    color: #fff;
    text-decoration: none;
    cursor: pointer
}

.label:empty {
    display: none
}

.btn .label {
    position: relative;
    top: -1px
}

.label-default {
    background-color: #777
}

.label-default[href]:focus,
.label-default[href]:hover {
    background-color: #5e5e5e
}

.label-primary {
    background-color: #337ab7
}

.label-primary[href]:focus,
.label-primary[href]:hover {
    background-color: #286090
}

.label-success {
    background-color: #5cb85c
}

.label-success[href]:focus,
.label-success[href]:hover {
    background-color: #449d44
}

.label-info {
    background-color: #5bc0de
}

.label-info[href]:focus,
.label-info[href]:hover {
    background-color: #31b0d5
}

.label-warning {
    background-color: #f0ad4e
}

.label-warning[href]:focus,
.label-warning[href]:hover {
    background-color: #ec971f
}

.label-danger {
    background-color: #d9534f
}

.label-danger[href]:focus,
.label-danger[href]:hover {
    background-color: #c9302c
}

.badge {
    display: inline-block;
    min-width: 10px;
    padding: 3px 7px;
    font-size: 12px;
    font-weight: 700;
    line-height: 1;
    color: #fff;
    text-align: center;
    white-space: nowrap;
    vertical-align: middle;
    background-color: #777;
    border-radius: 10px
}

.badge:empty {
    display: none
}

.btn .badge {
    position: relative;
    top: -1px
}

.btn-group-xs>.btn .badge,
.btn-xs .badge {
    top: 0;
    padding: 1px 5px
}

a.badge:focus,
a.badge:hover {
    color: #fff;
    text-decoration: none;
    cursor: pointer
}

.list-group-item.active>.badge,
.nav-pills>.active>a>.badge {
    color: #337ab7;
    background-color: #fff
}

.list-group-item>.badge {
    float: right
}

.list-group-item>.badge+.badge {
    margin-right: 5px
}

.nav-pills>li>a>.badge {
    margin-left: 3px
}

.jumbotron {
    padding-top: 30px;
    padding-bottom: 30px;
    margin-bottom: 30px;
    background-color: #eee
}

.jumbotron,
.jumbotron .h1,
.jumbotron h1 {
    color: inherit
}

.jumbotron p {
    margin-bottom: 15px;
    font-size: 21px;
    font-weight: 200
}

.jumbotron>hr {
    border-top-color: #d5d5d5
}

.container-fluid .jumbotron,
.container .jumbotron {
    padding-right: 15px;
    padding-left: 15px;
    border-radius: 6px
}

.jumbotron .container {
    max-width: 100%
}

@media screen and (min-width:768px) {
    .jumbotron {
        padding-top: 48px;
        padding-bottom: 48px
    }

    .container-fluid .jumbotron,
    .container .jumbotron {
        padding-right: 60px;
        padding-left: 60px
    }

    .jumbotron .h1,
    .jumbotron h1 {
        font-size: 63px
    }
}

.thumbnail {
    display: block;
    padding: 4px;
    margin-bottom: 20px;
    line-height: 1.42857143;
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 4px;
    -webkit-transition: border .2s ease-in-out;
    -o-transition: border .2s ease-in-out;
    transition: border .2s ease-in-out
}

.thumbnail>img,
.thumbnail a>img {
    margin-right: auto;
    margin-left: auto
}

a.thumbnail.active,
a.thumbnail:focus,
a.thumbnail:hover {
    border-color: #337ab7
}

.thumbnail .caption {
    padding: 9px;
    color: #333
}

.alert {
    padding: 15px;
    margin-bottom: 20px;
    border: 1px solid transparent;
    border-radius: 4px
}

.alert h4 {
    margin-top: 0;
    color: inherit
}

.alert .alert-link {
    font-weight: 700
}

.alert>p,
.alert>ul {
    margin-bottom: 0
}

.alert>p+p {
    margin-top: 5px
}

.alert-dismissable,
.alert-dismissible {
    padding-right: 35px
}

.alert-dismissable .close,
.alert-dismissible .close {
    position: relative;
    top: -2px;
    right: -21px;
    color: inherit
}

.alert-success {
    color: #3c763d;
    background-color: #dff0d8;
    border-color: #d6e9c6
}

.alert-success hr {
    border-top-color: #c9e2b3
}

.alert-success .alert-link {
    color: #2b542c
}

.alert-info {
    color: #31708f;
    background-color: #d9edf7;
    border-color: #bce8f1
}

.alert-info hr {
    border-top-color: #a6e1ec
}

.alert-info .alert-link {
    color: #245269
}

.alert-warning {
    color: #8a6d3b;
    background-color: #fcf8e3;
    border-color: #faebcc
}

.alert-warning hr {
    border-top-color: #f7e1b5
}

.alert-warning .alert-link {
    color: #66512c
}

.alert-danger {
    color: #a94442;
    background-color: #f2dede;
    border-color: #ebccd1
}

.alert-danger hr {
    border-top-color: #e4b9c0
}

.alert-danger .alert-link {
    color: #843534
}

@-webkit-keyframes progress-bar-stripes {
    0% {
        background-position: 40px 0
    }

    to {
        background-position: 0 0
    }
}

@keyframes progress-bar-stripes {
    0% {
        background-position: 40px 0
    }

    to {
        background-position: 0 0
    }
}

.progress {
    height: 20px;
    margin-bottom: 20px;
    overflow: hidden;
    background-color: #f5f5f5;
    border-radius: 4px;
    -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, .1);
    box-shadow: inset 0 1px 2px rgba(0, 0, 0, .1)
}

.progress-bar {
    float: left;
    width: 0;
    height: 100%;
    font-size: 12px;
    line-height: 20px;
    color: #fff;
    text-align: center;
    background-color: #337ab7;
    -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, .15);
    box-shadow: inset 0 -1px 0 rgba(0, 0, 0, .15);
    -webkit-transition: width .6s ease;
    -o-transition: width .6s ease;
    transition: width .6s ease
}

.progress-bar-striped,
.progress-striped .progress-bar {
    background-image: -webkit-linear-gradient(45deg, hsla(0, 0%, 100%, .15) 25%, transparent 0, transparent 50%, hsla(0, 0%, 100%, .15) 0, hsla(0, 0%, 100%, .15) 75%, transparent 0, transparent);
    background-image: -o-linear-gradient(45deg, hsla(0, 0%, 100%, .15) 25%, transparent 25%, transparent 50%, hsla(0, 0%, 100%, .15) 50%, hsla(0, 0%, 100%, .15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, hsla(0, 0%, 100%, .15) 25%, transparent 0, transparent 50%, hsla(0, 0%, 100%, .15) 0, hsla(0, 0%, 100%, .15) 75%, transparent 0, transparent);
    background-size: 40px 40px
}

.progress-bar.active,
.progress.active .progress-bar {
    -webkit-animation: progress-bar-stripes 2s linear infinite;
    animation: progress-bar-stripes 2s linear infinite
}

.progress-bar-success {
    background-color: #5cb85c
}

.progress-striped .progress-bar-success {
    background-image: -webkit-linear-gradient(45deg, hsla(0, 0%, 100%, .15) 25%, transparent 0, transparent 50%, hsla(0, 0%, 100%, .15) 0, hsla(0, 0%, 100%, .15) 75%, transparent 0, transparent);
    background-image: -o-linear-gradient(45deg, hsla(0, 0%, 100%, .15) 25%, transparent 25%, transparent 50%, hsla(0, 0%, 100%, .15) 50%, hsla(0, 0%, 100%, .15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, hsla(0, 0%, 100%, .15) 25%, transparent 0, transparent 50%, hsla(0, 0%, 100%, .15) 0, hsla(0, 0%, 100%, .15) 75%, transparent 0, transparent)
}

.progress-bar-info {
    background-color: #5bc0de
}

.progress-striped .progress-bar-info {
    background-image: -webkit-linear-gradient(45deg, hsla(0, 0%, 100%, .15) 25%, transparent 0, transparent 50%, hsla(0, 0%, 100%, .15) 0, hsla(0, 0%, 100%, .15) 75%, transparent 0, transparent);
    background-image: -o-linear-gradient(45deg, hsla(0, 0%, 100%, .15) 25%, transparent 25%, transparent 50%, hsla(0, 0%, 100%, .15) 50%, hsla(0, 0%, 100%, .15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, hsla(0, 0%, 100%, .15) 25%, transparent 0, transparent 50%, hsla(0, 0%, 100%, .15) 0, hsla(0, 0%, 100%, .15) 75%, transparent 0, transparent)
}

.progress-bar-warning {
    background-color: #f0ad4e
}

.progress-striped .progress-bar-warning {
    background-image: -webkit-linear-gradient(45deg, hsla(0, 0%, 100%, .15) 25%, transparent 0, transparent 50%, hsla(0, 0%, 100%, .15) 0, hsla(0, 0%, 100%, .15) 75%, transparent 0, transparent);
    background-image: -o-linear-gradient(45deg, hsla(0, 0%, 100%, .15) 25%, transparent 25%, transparent 50%, hsla(0, 0%, 100%, .15) 50%, hsla(0, 0%, 100%, .15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, hsla(0, 0%, 100%, .15) 25%, transparent 0, transparent 50%, hsla(0, 0%, 100%, .15) 0, hsla(0, 0%, 100%, .15) 75%, transparent 0, transparent)
}

.progress-bar-danger {
    background-color: #d9534f
}

.progress-striped .progress-bar-danger {
    background-image: -webkit-linear-gradient(45deg, hsla(0, 0%, 100%, .15) 25%, transparent 0, transparent 50%, hsla(0, 0%, 100%, .15) 0, hsla(0, 0%, 100%, .15) 75%, transparent 0, transparent);
    background-image: -o-linear-gradient(45deg, hsla(0, 0%, 100%, .15) 25%, transparent 25%, transparent 50%, hsla(0, 0%, 100%, .15) 50%, hsla(0, 0%, 100%, .15) 75%, transparent 75%, transparent);
    background-image: linear-gradient(45deg, hsla(0, 0%, 100%, .15) 25%, transparent 0, transparent 50%, hsla(0, 0%, 100%, .15) 0, hsla(0, 0%, 100%, .15) 75%, transparent 0, transparent)
}

.media {
    margin-top: 15px
}

.media:first-child {
    margin-top: 0
}

.media,
.media-body {
    overflow: hidden;
    zoom: 1
}

.media-body {
    width: 10000px
}

.media-object {
    display: block
}

.media-object.img-thumbnail {
    max-width: none
}

.media-right,
.media>.pull-right {
    padding-left: 10px
}

.media-left,
.media>.pull-left {
    padding-right: 10px
}

.media-body,
.media-left,
.media-right {
    display: table-cell;
    vertical-align: top
}

.media-middle {
    vertical-align: middle
}

.media-bottom {
    vertical-align: bottom
}

.media-heading {
    margin-top: 0;
    margin-bottom: 5px
}

.media-list {
    padding-left: 0;
    list-style: none
}

.list-group {
    padding-left: 0;
    margin-bottom: 20px
}

.list-group-item {
    position: relative;
    display: block;
    padding: 10px 15px;
    margin-bottom: -1px;
    background-color: #fff;
    border: 1px solid #ddd
}

.list-group-item:first-child {
    border-top-left-radius: 4px;
    border-top-right-radius: 4px
}

.list-group-item:last-child {
    margin-bottom: 0;
    border-bottom-right-radius: 4px;
    border-bottom-left-radius: 4px
}

a.list-group-item,
button.list-group-item {
    color: #555
}

a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
    color: #333
}

a.list-group-item:focus,
a.list-group-item:hover,
button.list-group-item:focus,
button.list-group-item:hover {
    color: #555;
    text-decoration: none;
    background-color: #f5f5f5
}

button.list-group-item {
    width: 100%;
    text-align: left
}

.list-group-item.disabled,
.list-group-item.disabled:focus,
.list-group-item.disabled:hover {
    color: #777;
    cursor: not-allowed;
    background-color: #eee
}

.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading {
    color: inherit
}

.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text {
    color: #777
}

.list-group-item.active,
.list-group-item.active:focus,
.list-group-item.active:hover {
    z-index: 2;
    color: #fff;
    background-color: #337ab7;
    border-color: #337ab7
}

.list-group-item.active .list-group-item-heading,
.list-group-item.active .list-group-item-heading>.small,
.list-group-item.active .list-group-item-heading>small,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading>.small,
.list-group-item.active:focus .list-group-item-heading>small,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading>.small,
.list-group-item.active:hover .list-group-item-heading>small {
    color: inherit
}

.list-group-item.active .list-group-item-text,
.list-group-item.active:focus .list-group-item-text,
.list-group-item.active:hover .list-group-item-text {
    color: #c7ddef
}

.list-group-item-success {
    color: #3c763d;
    background-color: #dff0d8
}

a.list-group-item-success,
button.list-group-item-success {
    color: #3c763d
}

a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
    color: inherit
}

a.list-group-item-success:focus,
a.list-group-item-success:hover,
button.list-group-item-success:focus,
button.list-group-item-success:hover {
    color: #3c763d;
    background-color: #d0e9c6
}

a.list-group-item-success.active,
a.list-group-item-success.active:focus,
a.list-group-item-success.active:hover,
button.list-group-item-success.active,
button.list-group-item-success.active:focus,
button.list-group-item-success.active:hover {
    color: #fff;
    background-color: #3c763d;
    border-color: #3c763d
}

.list-group-item-info {
    color: #31708f;
    background-color: #d9edf7
}

a.list-group-item-info,
button.list-group-item-info {
    color: #31708f
}

a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
    color: inherit
}

a.list-group-item-info:focus,
a.list-group-item-info:hover,
button.list-group-item-info:focus,
button.list-group-item-info:hover {
    color: #31708f;
    background-color: #c4e3f3
}

a.list-group-item-info.active,
a.list-group-item-info.active:focus,
a.list-group-item-info.active:hover,
button.list-group-item-info.active,
button.list-group-item-info.active:focus,
button.list-group-item-info.active:hover {
    color: #fff;
    background-color: #31708f;
    border-color: #31708f
}

.list-group-item-warning {
    color: #8a6d3b;
    background-color: #fcf8e3
}

a.list-group-item-warning,
button.list-group-item-warning {
    color: #8a6d3b
}

a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
    color: inherit
}

a.list-group-item-warning:focus,
a.list-group-item-warning:hover,
button.list-group-item-warning:focus,
button.list-group-item-warning:hover {
    color: #8a6d3b;
    background-color: #faf2cc
}

a.list-group-item-warning.active,
a.list-group-item-warning.active:focus,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active,
button.list-group-item-warning.active:focus,
button.list-group-item-warning.active:hover {
    color: #fff;
    background-color: #8a6d3b;
    border-color: #8a6d3b
}

.list-group-item-danger {
    color: #a94442;
    background-color: #f2dede
}

a.list-group-item-danger,
button.list-group-item-danger {
    color: #a94442
}

a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
    color: inherit
}

a.list-group-item-danger:focus,
a.list-group-item-danger:hover,
button.list-group-item-danger:focus,
button.list-group-item-danger:hover {
    color: #a94442;
    background-color: #ebcccc
}

a.list-group-item-danger.active,
a.list-group-item-danger.active:focus,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active,
button.list-group-item-danger.active:focus,
button.list-group-item-danger.active:hover {
    color: #fff;
    background-color: #a94442;
    border-color: #a94442
}

.list-group-item-heading {
    margin-top: 0;
    margin-bottom: 5px
}

.list-group-item-text {
    margin-bottom: 0;
    line-height: 1.3
}

.panel {
    margin-bottom: 20px;
    background-color: #fff;
    border: 1px solid transparent;
    border-radius: 4px;
    -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, .05);
    box-shadow: 0 1px 1px rgba(0, 0, 0, .05)
}

.panel-body {
    padding: 15px
}

.panel-heading {
    padding: 10px 15px;
    border-bottom: 1px solid transparent;
    border-top-left-radius: 3px;
    border-top-right-radius: 3px
}

.panel-heading>.dropdown .dropdown-toggle,
.panel-title {
    color: inherit
}

.panel-title {
    margin-top: 0;
    margin-bottom: 0;
    font-size: 16px
}

.panel-title>.small,
.panel-title>.small>a,
.panel-title>a,
.panel-title>small,
.panel-title>small>a {
    color: inherit
}

.panel-footer {
    padding: 10px 15px;
    background-color: #f5f5f5;
    border-top: 1px solid #ddd;
    border-bottom-right-radius: 3px;
    border-bottom-left-radius: 3px
}

.panel>.list-group,
.panel>.panel-collapse>.list-group {
    margin-bottom: 0
}

.panel>.list-group .list-group-item,
.panel>.panel-collapse>.list-group .list-group-item {
    border-width: 1px 0;
    border-radius: 0
}

.panel>.list-group:first-child .list-group-item:first-child,
.panel>.panel-collapse>.list-group:first-child .list-group-item:first-child {
    border-top: 0;
    border-top-left-radius: 3px;
    border-top-right-radius: 3px
}

.panel>.list-group:last-child .list-group-item:last-child,
.panel>.panel-collapse>.list-group:last-child .list-group-item:last-child {
    border-bottom: 0;
    border-bottom-right-radius: 3px;
    border-bottom-left-radius: 3px
}

.panel>.panel-heading+.panel-collapse>.list-group .list-group-item:first-child {
    border-top-left-radius: 0;
    border-top-right-radius: 0
}

.list-group+.panel-footer,
.panel-heading+.list-group .list-group-item:first-child {
    border-top-width: 0
}

.panel>.panel-collapse>.table,
.panel>.table,
.panel>.table-responsive>.table {
    margin-bottom: 0
}

.panel>.panel-collapse>.table caption,
.panel>.table-responsive>.table caption,
.panel>.table caption {
    padding-right: 15px;
    padding-left: 15px
}

.panel>.table-responsive:first-child>.table:first-child,
.panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child,
.panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child,
.panel>.table:first-child,
.panel>.table:first-child>tbody:first-child>tr:first-child,
.panel>.table:first-child>thead:first-child>tr:first-child {
    border-top-left-radius: 3px;
    border-top-right-radius: 3px
}

.panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child td:first-child,
.panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child th:first-child,
.panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child td:first-child,
.panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child th:first-child,
.panel>.table:first-child>tbody:first-child>tr:first-child td:first-child,
.panel>.table:first-child>tbody:first-child>tr:first-child th:first-child,
.panel>.table:first-child>thead:first-child>tr:first-child td:first-child,
.panel>.table:first-child>thead:first-child>tr:first-child th:first-child {
    border-top-left-radius: 3px
}

.panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child td:last-child,
.panel>.table-responsive:first-child>.table:first-child>tbody:first-child>tr:first-child th:last-child,
.panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child td:last-child,
.panel>.table-responsive:first-child>.table:first-child>thead:first-child>tr:first-child th:last-child,
.panel>.table:first-child>tbody:first-child>tr:first-child td:last-child,
.panel>.table:first-child>tbody:first-child>tr:first-child th:last-child,
.panel>.table:first-child>thead:first-child>tr:first-child td:last-child,
.panel>.table:first-child>thead:first-child>tr:first-child th:last-child {
    border-top-right-radius: 3px
}

.panel>.table-responsive:last-child>.table:last-child,
.panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child,
.panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child,
.panel>.table:last-child,
.panel>.table:last-child>tbody:last-child>tr:last-child,
.panel>.table:last-child>tfoot:last-child>tr:last-child {
    border-bottom-right-radius: 3px;
    border-bottom-left-radius: 3px
}

.panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child td:first-child,
.panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child th:first-child,
.panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child td:first-child,
.panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child th:first-child,
.panel>.table:last-child>tbody:last-child>tr:last-child td:first-child,
.panel>.table:last-child>tbody:last-child>tr:last-child th:first-child,
.panel>.table:last-child>tfoot:last-child>tr:last-child td:first-child,
.panel>.table:last-child>tfoot:last-child>tr:last-child th:first-child {
    border-bottom-left-radius: 3px
}

.panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child td:last-child,
.panel>.table-responsive:last-child>.table:last-child>tbody:last-child>tr:last-child th:last-child,
.panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child td:last-child,
.panel>.table-responsive:last-child>.table:last-child>tfoot:last-child>tr:last-child th:last-child,
.panel>.table:last-child>tbody:last-child>tr:last-child td:last-child,
.panel>.table:last-child>tbody:last-child>tr:last-child th:last-child,
.panel>.table:last-child>tfoot:last-child>tr:last-child td:last-child,
.panel>.table:last-child>tfoot:last-child>tr:last-child th:last-child {
    border-bottom-right-radius: 3px
}

.panel>.panel-body+.table,
.panel>.panel-body+.table-responsive,
.panel>.table+.panel-body,
.panel>.table-responsive+.panel-body {
    border-top: 1px solid #ddd
}

.panel>.table>tbody:first-child>tr:first-child td,
.panel>.table>tbody:first-child>tr:first-child th {
    border-top: 0
}

.panel>.table-bordered,
.panel>.table-responsive>.table-bordered {
    border: 0
}

.panel>.table-bordered>tbody>tr>td:first-child,
.panel>.table-bordered>tbody>tr>th:first-child,
.panel>.table-bordered>tfoot>tr>td:first-child,
.panel>.table-bordered>tfoot>tr>th:first-child,
.panel>.table-bordered>thead>tr>td:first-child,
.panel>.table-bordered>thead>tr>th:first-child,
.panel>.table-responsive>.table-bordered>tbody>tr>td:first-child,
.panel>.table-responsive>.table-bordered>tbody>tr>th:first-child,
.panel>.table-responsive>.table-bordered>tfoot>tr>td:first-child,
.panel>.table-responsive>.table-bordered>tfoot>tr>th:first-child,
.panel>.table-responsive>.table-bordered>thead>tr>td:first-child,
.panel>.table-responsive>.table-bordered>thead>tr>th:first-child {
    border-left: 0
}

.panel>.table-bordered>tbody>tr>td:last-child,
.panel>.table-bordered>tbody>tr>th:last-child,
.panel>.table-bordered>tfoot>tr>td:last-child,
.panel>.table-bordered>tfoot>tr>th:last-child,
.panel>.table-bordered>thead>tr>td:last-child,
.panel>.table-bordered>thead>tr>th:last-child,
.panel>.table-responsive>.table-bordered>tbody>tr>td:last-child,
.panel>.table-responsive>.table-bordered>tbody>tr>th:last-child,
.panel>.table-responsive>.table-bordered>tfoot>tr>td:last-child,
.panel>.table-responsive>.table-bordered>tfoot>tr>th:last-child,
.panel>.table-responsive>.table-bordered>thead>tr>td:last-child,
.panel>.table-responsive>.table-bordered>thead>tr>th:last-child {
    border-right: 0
}

.panel>.table-bordered>tbody>tr:first-child>td,
.panel>.table-bordered>tbody>tr:first-child>th,
.panel>.table-bordered>tbody>tr:last-child>td,
.panel>.table-bordered>tbody>tr:last-child>th,
.panel>.table-bordered>tfoot>tr:last-child>td,
.panel>.table-bordered>tfoot>tr:last-child>th,
.panel>.table-bordered>thead>tr:first-child>td,
.panel>.table-bordered>thead>tr:first-child>th,
.panel>.table-responsive>.table-bordered>tbody>tr:first-child>td,
.panel>.table-responsive>.table-bordered>tbody>tr:first-child>th,
.panel>.table-responsive>.table-bordered>tbody>tr:last-child>td,
.panel>.table-responsive>.table-bordered>tbody>tr:last-child>th,
.panel>.table-responsive>.table-bordered>tfoot>tr:last-child>td,
.panel>.table-responsive>.table-bordered>tfoot>tr:last-child>th,
.panel>.table-responsive>.table-bordered>thead>tr:first-child>td,
.panel>.table-responsive>.table-bordered>thead>tr:first-child>th {
    border-bottom: 0
}

.panel>.table-responsive {
    margin-bottom: 0;
    border: 0
}

.panel-group {
    margin-bottom: 20px
}

.panel-group .panel {
    margin-bottom: 0;
    border-radius: 4px
}

.panel-group .panel+.panel {
    margin-top: 5px
}

.panel-group .panel-heading {
    border-bottom: 0
}

.panel-group .panel-heading+.panel-collapse>.list-group,
.panel-group .panel-heading+.panel-collapse>.panel-body {
    border-top: 1px solid #ddd
}

.panel-group .panel-footer {
    border-top: 0
}

.panel-group .panel-footer+.panel-collapse .panel-body {
    border-bottom: 1px solid #ddd
}

.panel-default {
    border-color: #ddd
}

.panel-default>.panel-heading {
    color: #333;
    background-color: #f5f5f5;
    border-color: #ddd
}

.panel-default>.panel-heading+.panel-collapse>.panel-body {
    border-top-color: #ddd
}

.panel-default>.panel-heading .badge {
    color: #f5f5f5;
    background-color: #333
}

.panel-default>.panel-footer+.panel-collapse>.panel-body {
    border-bottom-color: #ddd
}

.panel-primary {
    border-color: #337ab7
}

.panel-primary>.panel-heading {
    color: #fff;
    background-color: #337ab7;
    border-color: #337ab7
}

.panel-primary>.panel-heading+.panel-collapse>.panel-body {
    border-top-color: #337ab7
}

.panel-primary>.panel-heading .badge {
    color: #337ab7;
    background-color: #fff
}

.panel-primary>.panel-footer+.panel-collapse>.panel-body {
    border-bottom-color: #337ab7
}

.panel-success {
    border-color: #d6e9c6
}

.panel-success>.panel-heading {
    color: #3c763d;
    background-color: #dff0d8;
    border-color: #d6e9c6
}

.panel-success>.panel-heading+.panel-collapse>.panel-body {
    border-top-color: #d6e9c6
}

.panel-success>.panel-heading .badge {
    color: #dff0d8;
    background-color: #3c763d
}

.panel-success>.panel-footer+.panel-collapse>.panel-body {
    border-bottom-color: #d6e9c6
}

.panel-info {
    border-color: #bce8f1
}

.panel-info>.panel-heading {
    color: #31708f;
    background-color: #d9edf7;
    border-color: #bce8f1
}

.panel-info>.panel-heading+.panel-collapse>.panel-body {
    border-top-color: #bce8f1
}

.panel-info>.panel-heading .badge {
    color: #d9edf7;
    background-color: #31708f
}

.panel-info>.panel-footer+.panel-collapse>.panel-body {
    border-bottom-color: #bce8f1
}

.panel-warning {
    border-color: #faebcc
}

.panel-warning>.panel-heading {
    color: #8a6d3b;
    background-color: #fcf8e3;
    border-color: #faebcc
}

.panel-warning>.panel-heading+.panel-collapse>.panel-body {
    border-top-color: #faebcc
}

.panel-warning>.panel-heading .badge {
    color: #fcf8e3;
    background-color: #8a6d3b
}

.panel-warning>.panel-footer+.panel-collapse>.panel-body {
    border-bottom-color: #faebcc
}

.panel-danger {
    border-color: #ebccd1
}

.panel-danger>.panel-heading {
    color: #a94442;
    background-color: #f2dede;
    border-color: #ebccd1
}

.panel-danger>.panel-heading+.panel-collapse>.panel-body {
    border-top-color: #ebccd1
}

.panel-danger>.panel-heading .badge {
    color: #f2dede;
    background-color: #a94442
}

.panel-danger>.panel-footer+.panel-collapse>.panel-body {
    border-bottom-color: #ebccd1
}

.embed-responsive-4by3 {
    padding-bottom: 75%
}

.well {
    min-height: 20px;
    padding: 19px;
    margin-bottom: 20px;
    background-color: #f5f5f5;
    border: 1px solid #e3e3e3;
    border-radius: 4px;
    -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, .05);
    box-shadow: inset 0 1px 1px rgba(0, 0, 0, .05)
}

.well blockquote {
    border-color: #ddd;
    border-color: rgba(0, 0, 0, .15)
}

.well-lg {
    padding: 24px;
    border-radius: 6px
}

.well-sm {
    padding: 9px;
    border-radius: 3px
}

.close {
    float: right;
    font-size: 21px;
    font-weight: 700;
    line-height: 1;
    color: #000;
    text-shadow: 0 1px 0 #fff;
    filter: alpha(opacity=20);
    opacity: .2
}

.close:focus,
.close:hover {
    color: #000;
    text-decoration: none;
    cursor: pointer;
    filter: alpha(opacity=50);
    opacity: .5
}

button.close {
    -webkit-appearance: none;
    padding: 0;
    cursor: pointer;
    background: transparent;
    border: 0
}

.modal,
.modal-open {
    overflow: hidden
}

.modal {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    z-index: 1050;
    display: none;
    -webkit-overflow-scrolling: touch;
    outline: 0
}

.modal.fade .modal-dialog {
    -webkit-transition: -webkit-transform .3s ease-out;
    -o-transition: -o-transform .3s ease-out;
    transition: -webkit-transform .3s ease-out;
    -o-transition: transform .3s ease-out;
    transition: transform .3s ease-out;
    transition: transform .3s ease-out, -webkit-transform .3s ease-out;
    -webkit-transform: translateY(-25%);
    -ms-transform: translateY(-25%);
    transform: translateY(-25%)
}

.modal.in .modal-dialog {
    -webkit-transform: translate(0);
    -ms-transform: translate(0);
    transform: translate(0)
}

.modal-open .modal {
    overflow-x: hidden;
    overflow-y: auto
}

.modal-dialog {
    position: relative;
    width: auto;
    margin: 10px
}

.modal-content {
    position: relative;
    background-color: #fff;
    background-clip: padding-box;
    border: 1px solid #999;
    border: 1px solid rgba(0, 0, 0, .2);
    border-radius: 6px;
    outline: 0;
    -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, .5);
    box-shadow: 0 3px 9px rgba(0, 0, 0, .5)
}

.modal-backdrop {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    z-index: 1040;
    background-color: #000
}

.modal-backdrop.fade {
    filter: alpha(opacity=0);
    opacity: 0
}

.modal-backdrop.in {
    filter: alpha(opacity=50);
    opacity: .5
}

.modal-header {
    padding: 15px;
    border-bottom: 1px solid #e5e5e5
}

.modal-header .close {
    margin-top: -2px
}

.modal-title {
    margin: 0;
    line-height: 1.42857143
}

.modal-body {
    position: relative;
    padding: 15px
}

.modal-footer {
    padding: 15px;
    text-align: right;
    border-top: 1px solid #e5e5e5
}

.modal-footer .btn+.btn {
    margin-bottom: 0;
    margin-left: 5px
}

.modal-footer .btn-group .btn+.btn {
    margin-left: -1px
}

.modal-footer .btn-block+.btn-block {
    margin-left: 0
}

.modal-scrollbar-measure {
    position: absolute;
    top: -9999px;
    width: 50px;
    height: 50px;
    overflow: scroll
}

@media (min-width:768px) {
    .modal-dialog {
        width: 600px;
        margin: 30px auto
    }

    .modal-content {
        -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, .5);
        box-shadow: 0 5px 15px rgba(0, 0, 0, .5)
    }

    .modal-sm {
        width: 300px
    }
}

@media (min-width:992px) {
    .modal-lg {
        width: 900px
    }
}

.tooltip {
    position: absolute;
    z-index: 1070;
    display: block;
    font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
    font-size: 12px;
    font-style: normal;
    font-weight: 400;
    line-height: 1.42857143
}

.tooltip,
[dir=ltr] .tooltip {
    text-align: left
}

[dir=rtl] .tooltip {
    text-align: right
}

.tooltip {
    text-decoration: none;
    text-shadow: none;
    text-transform: none;
    letter-spacing: normal;
    word-break: normal;
    word-spacing: normal;
    word-wrap: normal;
    white-space: normal;
    filter: alpha(opacity=0);
    opacity: 0;
    line-break: auto
}

.tooltip.in {
    filter: alpha(opacity=90);
    opacity: .9
}

.tooltip.top {
    padding: 5px 0;
    margin-top: -3px
}

.tooltip.right {
    padding: 0 5px;
    margin-left: 3px
}

.tooltip.bottom {
    padding: 5px 0;
    margin-top: 3px
}

.tooltip.left {
    padding: 0 5px;
    margin-left: -3px
}

.tooltip-inner {
    max-width: 200px;
    padding: 3px 8px;
    color: #fff;
    text-align: center;
    background-color: #000;
    border-radius: 4px
}

.tooltip-arrow {
    position: absolute;
    width: 0;
    height: 0;
    border-color: transparent;
    border-style: solid
}

.tooltip.top .tooltip-arrow {
    bottom: 0;
    left: 50%;
    margin-left: -5px;
    border-width: 5px 5px 0;
    border-top-color: #000
}

.tooltip.top-left .tooltip-arrow {
    right: 5px
}

.tooltip.top-left .tooltip-arrow,
.tooltip.top-right .tooltip-arrow {
    bottom: 0;
    margin-bottom: -5px;
    border-width: 5px 5px 0;
    border-top-color: #000
}

.tooltip.top-right .tooltip-arrow {
    left: 5px
}

.tooltip.right .tooltip-arrow {
    top: 50%;
    left: 0;
    margin-top: -5px;
    border-width: 5px 5px 5px 0;
    border-right-color: #000
}

.tooltip.left .tooltip-arrow {
    top: 50%;
    right: 0;
    margin-top: -5px;
    border-width: 5px 0 5px 5px;
    border-left-color: #000
}

.tooltip.bottom .tooltip-arrow {
    top: 0;
    left: 50%;
    margin-left: -5px;
    border-width: 0 5px 5px;
    border-bottom-color: #000
}

.tooltip.bottom-left .tooltip-arrow {
    top: 0;
    right: 5px;
    margin-top: -5px;
    border-width: 0 5px 5px;
    border-bottom-color: #000
}

.tooltip.bottom-right .tooltip-arrow {
    top: 0;
    left: 5px;
    margin-top: -5px;
    border-width: 0 5px 5px;
    border-bottom-color: #000
}

.popover {
    position: absolute;
    top: 0;
    left: 0;
    z-index: 1060;
    display: none;
    max-width: 276px;
    padding: 1px;
    font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 1.42857143
}

.popover,
[dir=ltr] .popover {
    text-align: left
}

[dir=rtl] .popover {
    text-align: right
}

.popover {
    text-decoration: none;
    text-shadow: none;
    text-transform: none;
    letter-spacing: normal;
    word-break: normal;
    word-spacing: normal;
    word-wrap: normal;
    white-space: normal;
    background-color: #fff;
    background-clip: padding-box;
    border: 1px solid #ccc;
    border: 1px solid rgba(0, 0, 0, .2);
    border-radius: 6px;
    -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, .2);
    box-shadow: 0 5px 10px rgba(0, 0, 0, .2);
    line-break: auto
}

.popover.top {
    margin-top: -10px
}

.popover.right {
    margin-left: 10px
}

.popover.bottom {
    margin-top: 10px
}

.popover.left {
    margin-left: -10px
}

.popover-title {
    padding: 8px 14px;
    margin: 0;
    font-size: 14px;
    background-color: #f7f7f7;
    border-bottom: 1px solid #ebebeb;
    border-radius: 5px 5px 0 0
}

.popover-content {
    padding: 9px 14px
}

.popover>.arrow,
.popover>.arrow:after {
    position: absolute;
    display: block;
    width: 0;
    height: 0;
    border-color: transparent;
    border-style: solid
}

.popover>.arrow {
    border-width: 11px
}

.popover>.arrow:after {
    content: "";
    border-width: 10px
}

.popover.top>.arrow {
    bottom: -11px;
    left: 50%;
    margin-left: -11px;
    border-top-color: #999;
    border-top-color: rgba(0, 0, 0, .25);
    border-bottom-width: 0
}

.popover.top>.arrow:after {
    bottom: 1px;
    margin-left: -10px;
    content: " ";
    border-top-color: #fff;
    border-bottom-width: 0
}

.popover.right>.arrow {
    top: 50%;
    left: -11px;
    margin-top: -11px;
    border-right-color: #999;
    border-right-color: rgba(0, 0, 0, .25);
    border-left-width: 0
}

.popover.right>.arrow:after {
    bottom: -10px;
    left: 1px;
    content: " ";
    border-right-color: #fff;
    border-left-width: 0
}

.popover.bottom>.arrow {
    top: -11px;
    left: 50%;
    margin-left: -11px;
    border-top-width: 0;
    border-bottom-color: #999;
    border-bottom-color: rgba(0, 0, 0, .25)
}

.popover.bottom>.arrow:after {
    top: 1px;
    margin-left: -10px;
    content: " ";
    border-top-width: 0;
    border-bottom-color: #fff
}

.popover.left>.arrow {
    top: 50%;
    right: -11px;
    margin-top: -11px;
    border-right-width: 0;
    border-left-color: #999;
    border-left-color: rgba(0, 0, 0, .25)
}

.popover.left>.arrow:after {
    right: 1px;
    bottom: -10px;
    content: " ";
    border-right-width: 0;
    border-left-color: #fff
}

.carousel,
.carousel-inner {
    position: relative
}

.carousel-inner {
    width: 100%;
    overflow: hidden
}

.carousel-inner>.item {
    position: relative;
    display: none;
    -webkit-transition: left .6s ease-in-out;
    -o-transition: .6s ease-in-out left;
    transition: left .6s ease-in-out
}

.carousel-inner>.item>a>img,
.carousel-inner>.item>img {
    line-height: 1
}

@media (-webkit-transform-3d),
(transform-3d) {
    .carousel-inner>.item {
        -webkit-transition: -webkit-transform .6s ease-in-out;
        -o-transition: -o-transform .6s ease-in-out;
        transition: -webkit-transform .6s ease-in-out;
        -o-transition: transform .6s ease-in-out;
        transition: transform .6s ease-in-out;
        transition: transform .6s ease-in-out, -webkit-transform .6s ease-in-out;
        -webkit-backface-visibility: hidden;
        backface-visibility: hidden;
        -webkit-perspective: 1000px;
        perspective: 1000px
    }

    .carousel-inner>.item.active.right,
    .carousel-inner>.item.next {
        left: 0;
        -webkit-transform: translate3d(100%, 0, 0);
        transform: translate3d(100%, 0, 0)
    }

    .carousel-inner>.item.active.left,
    .carousel-inner>.item.prev {
        left: 0;
        -webkit-transform: translate3d(-100%, 0, 0);
        transform: translate3d(-100%, 0, 0)
    }

    .carousel-inner>.item.active,
    .carousel-inner>.item.next.left,
    .carousel-inner>.item.prev.right {
        left: 0;
        -webkit-transform: translateZ(0);
        transform: translateZ(0)
    }
}

.carousel-inner>.active,
.carousel-inner>.next,
.carousel-inner>.prev {
    display: block
}

.carousel-inner>.active {
    left: 0
}

.carousel-inner>.next,
.carousel-inner>.prev {
    position: absolute;
    top: 0;
    width: 100%
}

.carousel-inner>.next {
    left: 100%
}

.carousel-inner>.prev {
    left: -100%
}

.carousel-inner>.next.left,
.carousel-inner>.prev.right {
    left: 0
}

.carousel-inner>.active.left {
    left: -100%
}

.carousel-inner>.active.right {
    left: 100%
}

.carousel-control {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    width: 15%;
    font-size: 20px;
    color: #fff;
    text-align: center;
    text-shadow: 0 1px 2px rgba(0, 0, 0, .6);
    background-color: transparent;
    filter: alpha(opacity=50);
    opacity: .5
}

.carousel-control.left {
    background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, .5), rgba(0, 0, 0, .0001));
    background-image: -o-linear-gradient(left, rgba(0, 0, 0, .5) 0, rgba(0, 0, 0, .0001) 100%);
    background-image: -webkit-gradient(linear, left top, right top, from(rgba(0, 0, 0, .5)), to(rgba(0, 0, 0, .0001)));
    background-image: linear-gradient(90deg, rgba(0, 0, 0, .5) 0, rgba(0, 0, 0, .0001));
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="rgba(128, 0, 0, 0)", endColorstr="rgba(0, 0, 0, 0)", GradientType=1);
    background-repeat: repeat-x
}

.carousel-control.right {
    right: 0;
    left: auto;
    background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, .0001), rgba(0, 0, 0, .5));
    background-image: -o-linear-gradient(left, rgba(0, 0, 0, .0001) 0, rgba(0, 0, 0, .5) 100%);
    background-image: -webkit-gradient(linear, left top, right top, from(rgba(0, 0, 0, .0001)), to(rgba(0, 0, 0, .5)));
    background-image: linear-gradient(90deg, rgba(0, 0, 0, .0001) 0, rgba(0, 0, 0, .5));
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="rgba(0, 0, 0, 0)", endColorstr="rgba(128, 0, 0, 0)", GradientType=1);
    background-repeat: repeat-x
}

.carousel-control:focus,
.carousel-control:hover {
    color: #fff;
    text-decoration: none;
    filter: alpha(opacity=90);
    outline: 0;
    opacity: .9
}

.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right,
.carousel-control .icon-next,
.carousel-control .icon-prev {
    position: absolute;
    top: 50%;
    z-index: 5;
    display: inline-block;
    margin-top: -10px
}

.carousel-control .glyphicon-chevron-left,
.carousel-control .icon-prev {
    left: 50%;
    margin-left: -10px
}

.carousel-control .glyphicon-chevron-right,
.carousel-control .icon-next {
    right: 50%;
    margin-right: -10px
}

.carousel-control .icon-next,
.carousel-control .icon-prev {
    width: 20px;
    height: 20px;
    font-family: serif;
    line-height: 1
}

.carousel-control .icon-prev:before {
    content: "\2039"
}

.carousel-control .icon-next:before {
    content: "\203A"
}

.carousel-indicators {
    position: absolute;
    bottom: 10px;
    left: 50%;
    z-index: 15;
    width: 60%;
    padding-left: 0;
    margin-left: -30%;
    text-align: center;
    list-style: none
}

.carousel-indicators li {
    display: inline-block;
    width: 10px;
    height: 10px;
    margin: 1px;
    text-indent: -999px;
    cursor: pointer;
    background-color: #000;
    background-color: transparent;
    border: 1px solid #fff;
    border-radius: 10px
}

.carousel-indicators .active {
    width: 12px;
    height: 12px;
    margin: 0;
    background-color: #fff
}

.carousel-caption {
    position: absolute;
    right: 15%;
    bottom: 20px;
    left: 15%;
    z-index: 10;
    padding-top: 20px;
    padding-bottom: 20px;
    color: #fff;
    text-align: center;
    text-shadow: 0 1px 2px rgba(0, 0, 0, .6)
}

.carousel-caption .btn {
    text-shadow: none
}

@media screen and (min-width:768px) {

    .carousel-control .glyphicon-chevron-left,
    .carousel-control .glyphicon-chevron-right,
    .carousel-control .icon-next,
    .carousel-control .icon-prev {
        width: 30px;
        height: 30px;
        margin-top: -10px;
        font-size: 30px
    }

    .carousel-control .glyphicon-chevron-left,
    .carousel-control .icon-prev {
        margin-left: -10px
    }

    .carousel-control .glyphicon-chevron-right,
    .carousel-control .icon-next {
        margin-right: -10px
    }

    .carousel-caption {
        right: 20%;
        left: 20%;
        padding-bottom: 30px
    }

    .carousel-indicators {
        bottom: 20px
    }
}

.btn-group-vertical>.btn-group:after,
.btn-group-vertical>.btn-group:before,
.btn-toolbar:after,
.btn-toolbar:before,
.clearfix:after,
.clearfix:before,
.container-fluid:after,
.container-fluid:before,
.container:after,
.container:before,
.dl-horizontal dd:after,
.dl-horizontal dd:before,
.form-horizontal .form-group:after,
.form-horizontal .form-group:before,
.modal-footer:after,
.modal-footer:before,
.modal-header:after,
.modal-header:before,
.nav:after,
.nav:before,
.navbar-collapse:after,
.navbar-collapse:before,
.navbar-header:after,
.navbar-header:before,
.navbar:after,
.navbar:before,
.pager:after,
.pager:before,
.panel-body:after,
.panel-body:before,
.row:after,
.row:before {
    display: table;
    content: " "
}

.btn-group-vertical>.btn-group:after,
.btn-toolbar:after,
.clearfix:after,
.container-fluid:after,
.container:after,
.dl-horizontal dd:after,
.form-horizontal .form-group:after,
.modal-footer:after,
.modal-header:after,
.nav:after,
.navbar-collapse:after,
.navbar-header:after,
.navbar:after,
.pager:after,
.panel-body:after,
.row:after {
    clear: both
}

.center-block {
    display: block;
    margin-right: auto;
    margin-left: auto
}

.pull-right {
    float: right !important
}

.pull-left {
    float: left !important
}

.hide {
    display: none !important
}

.show {
    display: block !important
}

.invisible {
    visibility: hidden
}

.text-hide {
    font: 0/0 a;
    color: transparent;
    text-shadow: none;
    background-color: transparent;
    border: 0
}

.hidden {
    display: none !important
}

.affix {
    position: fixed
}

@-ms-viewport {
    width: device-width
}

.visible-lg,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block,
.visible-md,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-sm,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-xs,
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block {
    display: none !important
}

@media (max-width:767px) {
    .visible-xs {
        display: block !important
    }

    table.visible-xs {
        display: table !important
    }

    tr.visible-xs {
        display: table-row !important
    }

    td.visible-xs,
    th.visible-xs {
        display: table-cell !important
    }
}

@media (max-width:767px) {
    .visible-xs-block {
        display: block !important
    }
}

@media (max-width:767px) {
    .visible-xs-inline {
        display: inline !important
    }
}

@media (max-width:767px) {
    .visible-xs-inline-block {
        display: inline-block !important
    }
}

@media (min-width:768px) and (max-width:991px) {
    .visible-sm {
        display: block !important
    }

    table.visible-sm {
        display: table !important
    }

    tr.visible-sm {
        display: table-row !important
    }

    td.visible-sm,
    th.visible-sm {
        display: table-cell !important
    }
}

@media (min-width:768px) and (max-width:991px) {
    .visible-sm-block {
        display: block !important
    }
}

@media (min-width:768px) and (max-width:991px) {
    .visible-sm-inline {
        display: inline !important
    }
}

@media (min-width:768px) and (max-width:991px) {
    .visible-sm-inline-block {
        display: inline-block !important
    }
}

@media (min-width:992px) and (max-width:1199px) {
    .visible-md {
        display: block !important
    }

    table.visible-md {
        display: table !important
    }

    tr.visible-md {
        display: table-row !important
    }

    td.visible-md,
    th.visible-md {
        display: table-cell !important
    }
}

@media (min-width:992px) and (max-width:1199px) {
    .visible-md-block {
        display: block !important
    }
}

@media (min-width:992px) and (max-width:1199px) {
    .visible-md-inline {
        display: inline !important
    }
}

@media (min-width:992px) and (max-width:1199px) {
    .visible-md-inline-block {
        display: inline-block !important
    }
}

@media (min-width:1200px) {
    .visible-lg {
        display: block !important
    }

    table.visible-lg {
        display: table !important
    }

    tr.visible-lg {
        display: table-row !important
    }

    td.visible-lg,
    th.visible-lg {
        display: table-cell !important
    }
}

@media (min-width:1200px) {
    .visible-lg-block {
        display: block !important
    }
}

@media (min-width:1200px) {
    .visible-lg-inline {
        display: inline !important
    }
}

@media (min-width:1200px) {
    .visible-lg-inline-block {
        display: inline-block !important
    }
}

@media (max-width:767px) {
    .hidden-xs {
        display: none !important
    }
}

@media (min-width:768px) and (max-width:991px) {
    .hidden-sm {
        display: none !important
    }
}

@media (min-width:992px) and (max-width:1199px) {
    .hidden-md {
        display: none !important
    }
}

@media (min-width:1200px) {
    .hidden-lg {
        display: none !important
    }
}

.visible-print {
    display: none !important
}

@media print {
    .visible-print {
        display: block !important
    }

    table.visible-print {
        display: table !important
    }

    tr.visible-print {
        display: table-row !important
    }

    td.visible-print,
    th.visible-print {
        display: table-cell !important
    }
}

.visible-print-block {
    display: none !important
}

@media print {
    .visible-print-block {
        display: block !important
    }
}

.visible-print-inline {
    display: none !important
}

@media print {
    .visible-print-inline {
        display: inline !important
    }
}

.visible-print-inline-block {
    display: none !important
}

@media print {
    .visible-print-inline-block {
        display: inline-block !important
    }
}

@media print {
    .hidden-print {
        display: none !important
    }
}

.prevent-scroll-mobile {
    overflow-y: hidden !important
}

@media only screen and (max-width:767px) {
    .prevent-scroll-mobile {
        height: 0 !important
    }
}

.webPurchaseBg {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    z-index: 99998;
    opacity: 1;
    background-color: rgba(0, 0, 0, .5)
}

.webPurchaseBg.loading {
    margin: 0 !important;
    background: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzMiIgaGVpZ2h0PSIzMiIgZmlsbD0iI2Y5ZmJmZiI+PHBhdGggb3BhY2l0eT0iLjI1IiBkPSJNMTYgMGExNiAxNiAwIDAwMCAzMiAxNiAxNiAwIDAwMC0zMm0wIDRhMTIgMTIgMCAwMTAgMjQgMTIgMTIgMCAwMTAtMjQiLz48cGF0aCBkPSJNMTYgMGExNiAxNiAwIDAxMTYgMTZoLTRBMTIgMTIgMCAwMDE2IDR6Ij48YW5pbWF0ZVRyYW5zZm9ybSBhdHRyaWJ1dGVOYW1lPSJ0cmFuc2Zvcm0iIHR5cGU9InJvdGF0ZSIgZnJvbT0iMCAxNiAxNiIgdG89IjM2MCAxNiAxNiIgZHVyPSIwLjhzIiByZXBlYXRDb3VudD0iaW5kZWZpbml0ZSIvPjwvcGF0aD48L3N2Zz4=) no-repeat 50%;
    background-size: 6em
}

.webPurchaseContainer {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    z-index: 99999;
    max-width: 1200px;
    width: 100vw;
    margin-left: auto;
    margin-right: auto;
    margin-top: 10vh;
    height: 80vh;
    background-color: #1e1e1e
}

@media only screen and (max-width:767px) {
    .webPurchaseContainer {
        margin: 0;
        height: 100vh;
        bottom: auto;
        border: none
    }
}

.webPurchaseContainer .purchase-app-container {
    height: 100%;
    min-height: 100%
}

@media only screen and (max-width:767px) {
    .webPurchaseContainer .purchase-app-container {
        height: auto;
        max-height: 100vh;
        overflow-y: auto
    }
}

.webPurchaseContainer .purchase-app-container .purchase-page {
    min-height: 100%;
    border: 2px solid #4d4d4d;
    background-color: #1e1e1e
}

.webPurchaseContainer .purchase-app-container .purchase-page .loading-message {
    max-width: 1200px;
    text-align: center;
    margin-left: auto;
    margin-right: auto
}

.webPurchaseContainer .purchase-app-container .purchase-page .loading-message img {
    margin-top: 12%;
    margin-bottom: 20px;
    vertical-align: middle;
    height: 90px
}

.webPurchaseContainer .purchase-app-container .purchase-page .loading-message p {
    font-size: 26px;
    margin: 0 0 10px
}

.webPurchaseContainer .purchase-app-container .purchase-page .loading-close-btn-container {
    text-align: right;
    display: block
}

.webPurchaseContainer .purchase-app-container .purchase-page .loading-close-btn-container>.loading-close {
    display: inline-block;
    font-size: 32px;
    cursor: pointer;
    padding: .5em;
    margin-right: .5em
}

.webPurchaseContainer .purchase-app-container #purchase-app .app-content-container .scroll-container {
    height: calc(80vh - 6em)
}

@media only screen and (max-width:767px) {
    .webPurchaseContainer .purchase-app-container #purchase-app .app-content-container .scroll-container {
        height: auto
    }
}

.webPurchaseContainer .purchase-app-container #purchase-app .overlay-container {
    top: calc(10vh + 5.5em);
    bottom: auto;
    height: calc(80vh - 5.5em);
    width: 100vw;
    max-width: 1200px;
    margin-left: auto;
    margin-right: auto
}

@media only screen and (max-width:767px) {
    .webPurchaseContainer .purchase-app-container #purchase-app .overlay-container {
        top: 0;
        height: 100vh
    }

    .webPurchaseContainer .purchase-app-container #purchase-app .overlay-container .modal-frame-overlay+.overlay-content {
        margin-top: 0;
        min-height: 100vh;
        max-height: 100vh
    }
}

@media only screen and (max-height:840px) {
    .webPurchaseContainer .purchase-app-container #purchase-app .item-summary {
        margin-bottom: .5em
    }

    .webPurchaseContainer .purchase-app-container #purchase-app .item-summary .item-summary-media-container {
        display: inline-block;
        width: 40%;
        vertical-align: bottom
    }

    .webPurchaseContainer .purchase-app-container #purchase-app .item-summary .item-summary-media-container .featured-image-container {
        margin-bottom: 0 !important
    }

    .webPurchaseContainer .purchase-app-container #purchase-app .item-summary .item-summary-media-container .featured-image-container img {
        width: auto;
        max-height: 8em !important;
        max-width: 8em !important;
        margin-left: auto;
        margin-right: auto
    }

    .webPurchaseContainer .purchase-app-container #purchase-app .item-summary .order-summary-title {
        width: 60%;
        margin-top: 1em;
        display: inline-block;
        position: static;
        background-color: transparent;
        vertical-align: top
    }

    .webPurchaseContainer .purchase-app-container #purchase-app .item-summary .order-summary-title h3 {
        font-weight: 600;
        text-transform: none
    }

    .webPurchaseContainer .purchase-app-container #purchase-app .item-summary .order-summary-title p {
        font-size: .8em
    }
}

.quick-purchase-loading {
    position: relative;
    top: calc(50% - 30px);
    left: calc(50% - 30px);
    width: 60px
}

@media only screen and (orientation:landscape) and (min-aspect-ratio:1/1) {
    #egh .shrink #cta {
        display: none
    }
}

#egh #cta.cta a {
    opacity: 1
}

@media only screen and (min-width:768px) {
    #egh .cta {
        height: 100%
    }

    #egh .cta a {
        width: auto;
        border-radius: 0
    }

    #egh .cta i,
    #egh .cta span {
        padding: 0
    }

    #egh .cta:before {
        content: "";
        background-color: transparent;
        height: 0
    }

    #egh #cta a {
        padding: 0 1em;
        height: 100%
    }
}

@media only screen and (min-width:768px) and (min-width:768px) and (max-width:1199px) {
    #egh #cta a {
        padding: 0 .5em
    }
}

@media only screen and (min-width:768px) {
    #egh #cta a span {
        white-space: nowrap;
        -o-text-overflow: ellipsis;
        text-overflow: ellipsis;
        overflow: hidden;
        max-width: 220px;
        min-width: 100px;
        position: relative;
        top: 50%;
        -webkit-transform: translateY(-50%);
        -ms-transform: translateY(-50%);
        transform: translateY(-50%);
        display: block
    }
}

@media only screen and (min-width:768px) and (min-width:768px) and (max-width:1199px) {
    #egh #cta a span {
        min-width: 80px
    }
}

@media only screen and (min-width:768px) {

    #egh #cta i,
    #egh #cta span {
        margin: 0
    }

    #egh #cta:hover:before {
        height: 0
    }
}

@media only screen and (max-width:767px) {
    #egh .cta {
        padding: 0
    }

    #egh .cta a {
        margin: 0;
        border-radius: 0;
        height: 6em
    }

    #egh .cta a span {
        margin: 0;
        padding: 0
    }

    #egh .right-col .rightNav #cta {
        display: none
    }

    #egh .right-col.active .rightNav #cta {
        display: block;
        position: absolute;
        bottom: 0;
        width: 100%;
        right: 0;
        height: 56px;
        z-index: 5
    }

    #egh .right-col.active .rightNav #cta a {
        display: block;
        font-family: OpenSans, sans-serif, arial;
        text-transform: uppercase;
        letter-spacing: .075em;
        cursor: pointer;
        padding: 0 .5em;
        text-align: center;
        min-width: 50px;
        margin: 0 auto;
        height: 40px
    }

    #egh .right-col.active .rightNav #cta a:active,
    #egh .right-col.active .rightNav #cta a:hover,
    #egh .right-col.active .rightNav #cta a:link,
    #egh .right-col.active .rightNav #cta a:visited {
        text-decoration: none
    }

    #egh .right-col.active .rightNav #cta a i {
        display: inline-block;
        font-size: 2em;
        width: auto;
        margin: .4em
    }

    #egh .right-col.active .rightNav #cta a span {
        font-size: .625em;
        position: relative;
        top: 50%;
        -webkit-transform: translateY(-50%);
        -ms-transform: translateY(-50%);
        transform: translateY(-50%)
    }
}

#egh .nav-line {
    pointer-events: auto;
    display: inline-block;
    -webkit-transition: .1s;
    -o-transition: .1s;
    transition: .1s;
    padding: 0 30px;
    position: relative;
    height: 100%
}

#egh .nav-line.active .lines {
    background-color: transparent !important;
    opacity: 1
}

#egh .nav-line.active .lines:after,
#egh .nav-line.active .lines:before {
    top: 0;
    -webkit-transition: top .1s ease-in-out, -webkit-transform .2s ease-in-out;
    transition: top .1s ease-in-out, -webkit-transform .2s ease-in-out;
    -o-transition: top .1s ease-in-out, transform .2s ease-in-out;
    transition: top .1s ease-in-out, transform .2s ease-in-out;
    transition: top .1s ease-in-out, transform .2s ease-in-out, -webkit-transform .2s ease-in-out
}

#egh .nav-line.active .lines:before {
    -webkit-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    transform: rotate(45deg)
}

#egh .nav-line.active .lines:after {
    -webkit-transform: rotate(-45deg);
    -ms-transform: rotate(-45deg);
    transform: rotate(-45deg)
}

#egh nav.desktop .nav-line,
#egh nav.desktop .nav-line .lines {
    display: none
}

#egh nav.tablet .nav-line {
    cursor: pointer;
    opacity: 1
}

#egh nav.tablet .nav-line,
#egh nav.tablet .nav-line.search-active {
    -webkit-transition: opacity .2s ease-in-out;
    -o-transition: opacity .2s ease-in-out;
    transition: opacity .2s ease-in-out
}

#egh nav.tablet .nav-line.search-active {
    opacity: 0;
    height: 0;
    overflow: hidden
}

#egh nav.tablet .nav-line .lines {
    position: absolute;
    top: 50%;
    left: 50%;
    margin-left: -15px;
    margin-top: -1px;
    display: inline-block;
    width: 30px;
    height: 3px;
    border-radius: 2.14286px;
    -webkit-transition: .1s;
    -o-transition: .1s;
    transition: .1s
}

#egh nav.tablet .nav-line .lines:after,
#egh nav.tablet .nav-line .lines:before {
    display: inline-block;
    width: 30px;
    height: 3px;
    border-radius: 2.14286px;
    position: absolute;
    left: 0;
    content: "";
    -webkit-transform-origin: 50% 50%;
    -ms-transform-origin: 50% 50%;
    transform-origin: 50% 50%
}

#egh nav.tablet .nav-line:not(.active) .lines:after,
#egh nav.tablet .nav-line:not(.active) .lines:before {
    -webkit-transition: top .1s ease, -webkit-transform .15s ease;
    transition: top .1s ease, -webkit-transform .15s ease;
    -o-transition: top .1s ease, transform .15s ease;
    transition: top .1s ease, transform .15s ease;
    transition: top .1s ease, transform .15s ease, -webkit-transform .15s ease
}

#egh nav.tablet .nav-line:not(.active) .lines:before {
    top: 8px
}

#egh nav.tablet .nav-line:not(.active) .lines:after {
    top: -8px
}

@media only screen and (max-width:767px) {
    #egh .nav-line {
        display: none !important;
        height: 3.7em
    }
}

#egh .egLogo {
    width: 5em;
    height: 3.7em;
    float: left;
    overflow: hidden
}

#egh .egLogo .shieldLogo {
    width: 3.7em;
    height: 3.7em;
    position: relative;
    float: left;
    margin-left: .5em
}

#egh .mobile .egLogo {
    width: 5em;
    margin-left: 0
}

#egh .mobile .egLogo .shieldLogo:after {
    right: 0
}

@media only screen and (min-width:768px) and (max-width:1199px) {
    #egh .egLogo {
        width: 4.75em
    }

    #egh .egLogo .shieldLogo:after {
        right: -.25em
    }
}

#egh .egLogo {
    opacity: .9
}

#egh .egLogo,
#egh .egLogo:hover {
    -webkit-transition: opacity .2s ease-out;
    -o-transition: .2s opacity ease-out;
    -o-transition: opacity .2s ease-out;
    transition: opacity .2s ease-out
}

#egh .egLogo:hover {
    opacity: 1
}

#euCookie {
    position: fixed;
    width: 100%;
    bottom: 0;
    padding: .9em .9em 0;
    text-align: center;
    z-index: 1000;
    font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
    font-size: .9em
}

@media only screen and (max-width:767px) {
    #euCookie {
        font-size: .8em
    }
}

#euCookie .policy-link {
    text-decoration: underline
}

#euCookie .cookie-msg {
    display: inline-block;
    padding-bottom: 1em
}

#euCookie .cookie-accept {
    display: inline-block;
    margin-left: 1em;
    border: none;
    font-family: OpenSans, sans-serif, arial;
    letter-spacing: .075em;
    text-transform: uppercase;
    font-size: .8em;
    padding: .3em 2em;
    margin-bottom: 1em
}

@media only screen and (max-width:767px) {
    #euCookie .cookie-accept {
        font-size: 1em
    }
}

#egh #locale .eg-header-icon-locale {
    margin-left: 3px
}

@media only screen and (max-width:950px) and (min-width:768px) {

    #egh #locale,
    #egh #locale a {
        width: 60px;
        min-width: 60px
    }

    #egh #locale a .label {
        display: none
    }

    #egh #locale:after {
        right: 12px
    }
}

@media only screen and (min-width:768px) {
    #egh #locale {
        padding: 0
    }

    #egh #locale ul {
        opacity: 0;
        visibility: hidden;
        overflow: hidden;
        height: 0;
        padding: .5em 0;
        width: auto;
        position: absolute;
        top: 3.7em;
        left: -60px;
        min-width: 180px;
        z-index: 4
    }
}

@media only screen and (min-width:768px) and (min-width:768px) and (max-width:1199px) {
    #egh #locale ul {
        right: -48px;
        left: auto
    }
}

@media only screen and (min-width:768px) {
    #egh #locale ul.ul-right {
        right: -60px;
        left: auto
    }

    #egh #locale ul.ul-right.ul-right-0 {
        right: 0
    }

    #egh #locale ul li {
        float: none;
        display: block;
        width: 100%;
        margin: .1em 0;
        height: 2em
    }

    #egh #locale ul li a {
        padding: 0 .9em;
        text-align: center;
        width: auto
    }

    #egh #locale ul li a p,
    #egh #locale ul li a span {
        font-size: .625em;
        line-height: 12px;
        height: 100%;
        position: relative;
        top: 50%;
        -webkit-transform: translateY(-50%);
        -ms-transform: translateY(-50%);
        transform: translateY(-50%)
    }

    #egh #locale:hover a {
        opacity: 1
    }

    #egh #locale:hover ul {
        opacity: 1;
        height: auto;
        visibility: visible;
        -webkit-transition: all .1s ease-in-out;
        -o-transition: all .1s ease-in-out;
        transition: all .1s ease-in-out
    }
}

@media only screen and (max-width:767px) {
    #egh ul.locale-list.mobile-list {
        overflow-y: auto
    }

    #egh ul.mobile-list li.mobile-list-item:nth-child(2) {
        padding-top: .58em !important
    }

    #egh .icon-bar #locale {
        display: block;
        position: fixed;
        top: 0;
        right: 0;
        width: 100%;
        height: 100%;
        z-index: 5;
        -webkit-transform: translate3d(100%, 0, 0);
        transform: translate3d(100%, 0, 0);
        -webkit-transition: -webkit-transform .2s cubic-bezier(.075, .82, 1, 1);
        transition: -webkit-transform .2s cubic-bezier(.075, .82, 1, 1);
        -o-transition: transform .2s cubic-bezier(.075, .82, 1, 1);
        transition: transform .2s cubic-bezier(.075, .82, 1, 1);
        transition: transform .2s cubic-bezier(.075, .82, 1, 1), -webkit-transform .2s cubic-bezier(.075, .82, 1, 1)
    }

    #egh .icon-bar #locale ul.locale-list {
        width: 100%;
        height: 100%;
        padding: 0
    }

    #egh .icon-bar #locale.active {
        -webkit-transform: translateZ(0);
        transform: translateZ(0)
    }
}

@media only screen and (min-width:768px) and (max-width:1199px) {

    #egh #locale,
    #egh #locale>a {
        width: 48px !important;
        min-width: 48px !important
    }
}

#egh .propLogo {
    background-size: contain;
    background-position: 50%;
    background-repeat: no-repeat;
    position: relative;
    float: left;
    min-width: 1px;
    height: 1.85em;
    opacity: .92;
    height: 100%;
    opacity: 1;
    height: auto;
    -webkit-transition: opacity .4s ease-in-out;
    -o-transition: opacity .4s ease-in-out;
    transition: opacity .4s ease-in-out
}

#egh .propLogo i {
    display: none
}

#egh .propLogo:hover {
    opacity: 1;
    -webkit-transition: opacity .2s ease-in;
    -o-transition: .2s opacity ease-in;
    -o-transition: opacity .2s ease-in;
    transition: opacity .2s ease-in
}

#egh .propLogo.tablet.search-active {
    -webkit-transition: opacity .4s ease-in-out;
    -o-transition: opacity .4s ease-in-out;
    transition: opacity .4s ease-in-out;
    opacity: 0;
    height: 0;
    overflow: hidden
}

@media only screen and (max-width:767px) {

    #egh .right-col.active .rightNav .icon-bar-toggle,
    #egh .right-col .rightNav .icon-bar-wrapper {
        display: none
    }
}

@media only screen and (max-width:767px) and (orientation:landscape) and (min-aspect-ratio:1/1) {
    #egh .right-col.active .rightNav .icon-bar-toggle {
        cursor: pointer;
        display: block;
        position: relative;
        height: 20px;
        width: 100%;
        z-index: 5;
        border-top: 1px solid
    }

    #egh .right-col.active .rightNav .icon-bar-toggle .toggle:after {
        content: "";
        display: block;
        margin: 0 auto;
        position: absolute;
        right: 0;
        left: 0;
        width: 10px;
        height: 10px;
        border-top: 2px solid;
        border-right: 2px solid;
        opacity: 1
    }

    #egh .right-col.active .rightNav .icon-bar-toggle.t-up {
        position: absolute;
        bottom: -58px;
        width: 30px;
        left: 0;
        right: 0;
        margin: 0 auto;
        border-top: none
    }

    #egh .right-col.active .rightNav .icon-bar-toggle.t-up .toggle:after {
        -webkit-transform: rotate(315deg);
        -ms-transform: rotate(315deg);
        transform: rotate(315deg);
        top: 8px
    }

    #egh .right-col.active .rightNav .icon-bar-toggle.t-down .toggle:after {
        -webkit-transform: rotate(135deg);
        -ms-transform: rotate(135deg);
        transform: rotate(135deg);
        top: 2px
    }
}

@media only screen and (max-width:767px) {
    #egh .right-col.active .rightNav .icon-bar-wrapper {
        display: block;
        width: 100%;
        height: auto;
        position: fixed;
        bottom: 56px;
        z-index: 5;
        -webkit-box-shadow: 0 -4px 15px -4px rgba(0, 0, 0, .5);
        box-shadow: 0 -4px 15px -4px rgba(0, 0, 0, .5)
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper.cta-hidden {
        bottom: 1px
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper.cta-hidden .t-up {
        bottom: 0
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper #searchIcon .eg-header-icon-close {
        -webkit-transform: scale(1.5);
        -ms-transform: scale(1.5);
        transform: scale(1.5)
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper #user .eg-header-icon-close {
        margin: .5em
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar {
        height: 100%;
        width: 100%
    }
}

@media only screen and (max-width:767px) and (orientation:landscape) and (min-aspect-ratio:1/1) {
    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar.shrink {
        display: none
    }
}

@media only screen and (max-width:767px) {
    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar .mobile-buttons {
        display: table;
        width: 100%
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar .mobile-buttons>a {
        display: table-cell;
        border-top: 1px solid
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar .mobile-buttons>a i {
        width: 30px
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar .mobile-buttons>a:first-child {
        border-right: 1px solid
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar .mobile-buttons .is-logged-in .eg-header-icon-user {
        position: relative
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar .mobile-buttons .is-logged-in .eg-header-icon-user:after {
        content: "";
        display: block;
        position: absolute;
        right: 5px;
        bottom: 0;
        width: 11px;
        height: 11px;
        border-radius: 50%;
        background-color: #52971c
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar #form.search.active {
        width: 90%;
        text-align: center;
        margin: 0 0 30px
    }
}

@media only screen and (max-width:767px) and (orientation:landscape) and (min-aspect-ratio:1/1) {
    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar #form.search.active {
        width: 80%
    }
}

@media only screen and (max-width:767px) {
    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar #form.search.active .search-btn .eg-header-icon-search {
        margin: 10px;
        font-size: 1.5em
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar>div {
        position: relative;
        -webkit-transform: translateZ(0);
        transform: translateZ(0);
        overflow: visible;
        display: table-cell
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar>div.dropdown:after {
        display: none
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar>div.active {
        overflow: visible
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar>div a {
        display: block;
        font-family: OpenSans, sans-serif, arial;
        text-transform: uppercase;
        letter-spacing: .075em;
        cursor: pointer;
        padding: 0 .5em;
        text-align: center;
        min-width: 50px;
        margin: 0 auto;
        height: 40px
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar>div a:active,
    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar>div a:hover,
    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar>div a:link,
    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar>div a:visited {
        text-decoration: none
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar>div a i {
        display: inline-block;
        font-size: 2em;
        width: auto;
        margin: .4em
    }

    #egh .right-col.active .rightNav .icon-bar-wrapper .icon-bar>div a span {
        font-size: .65em
    }
}

#egh.resizing #rightNav:not(.active) .rightNav {
    -webkit-transition: none !important;
    -o-transition: none !important;
    transition: none !important
}

#egh:not(.init) #rightNav,
#egh:not(.init) .right-col,
#egh:not(.init) .rightNav {
    display: none
}

@media only screen and (min-width:768px) {
    #egh .right-col {
        position: absolute;
        right: 0;
        top: 0;
        z-index: 6;
        list-style: none;
        padding: 0 0 0 1em;
        height: 3.7em;
        width: auto
    }
}

@media only screen and (min-width:768px) and (min-width:768px) and (max-width:1199px) {
    #egh .right-col {
        padding-left: .2em
    }
}

@media only screen and (min-width:768px) {
    #egh .right-col .rightNav {
        -webkit-transition: -webkit-transform .2s ease-in-out;
        transition: -webkit-transform .2s ease-in-out;
        -o-transition: transform .2s ease-in-out;
        transition: transform .2s ease-in-out;
        transition: transform .2s ease-in-out, -webkit-transform .2s ease-in-out;
        float: right;
        height: 3.7em
    }

    #egh .right-col .rightNav #searchIcon,
    #egh .right-col .rightNav>div {
        float: left;
        position: relative;
        -webkit-transform: translateZ(0);
        transform: translateZ(0);
        height: 100%;
        overflow: visible
    }

    #egh .right-col .rightNav #searchIcon.active,
    #egh .right-col .rightNav>div.active {
        overflow: visible;
        min-width: 60px
    }

    #egh .right-col .rightNav #searchIcon.active .eg-header-icon-close,
    #egh .right-col .rightNav #searchIcon.active i:not(.eg-header-icon-close),
    #egh .right-col .rightNav #searchIcon.active span,
    #egh .right-col .rightNav>div.active .eg-header-icon-close,
    #egh .right-col .rightNav>div.active i:not(.eg-header-icon-close),
    #egh .right-col .rightNav>div.active span {
        display: none
    }

    #egh .right-col .rightNav #searchIcon:not(.no-before):before,
    #egh .right-col .rightNav>div:not(.no-before):before {
        content: "";
        display: block;
        position: absolute;
        bottom: 0;
        left: 0;
        width: 100%;
        height: 0;
        z-index: -1;
        -webkit-transition: height .2s ease-in-out;
        -o-transition: height .2s ease-in-out;
        transition: height .2s ease-in-out
    }

    #egh .right-col .rightNav #searchIcon.active:before,
    #egh .right-col .rightNav #searchIcon:not(.no-before):hover:before,
    #egh .right-col .rightNav>div.active:before,
    #egh .right-col .rightNav>div:not(.no-before):hover:before {
        content: "";
        height: 5px
    }

    #egh .right-col .rightNav #searchIcon a,
    #egh .right-col .rightNav>div a {
        display: block;
        font-family: OpenSans, sans-serif, arial;
        text-transform: uppercase;
        letter-spacing: .075em;
        padding: 0 1em;
        text-align: center;
        min-width: 60px;
        height: 100%
    }
}

@media only screen and (min-width:768px) and (min-width:768px) and (max-width:1199px) {

    #egh .right-col .rightNav #searchIcon a,
    #egh .right-col .rightNav>div a {
        min-width: 40px
    }
}

@media only screen and (min-width:768px) {

    #egh .right-col .rightNav #searchIcon a:active,
    #egh .right-col .rightNav #searchIcon a:hover,
    #egh .right-col .rightNav #searchIcon a:link,
    #egh .right-col .rightNav #searchIcon a:visited,
    #egh .right-col .rightNav>div a:active,
    #egh .right-col .rightNav>div a:hover,
    #egh .right-col .rightNav>div a:link,
    #egh .right-col .rightNav>div a:visited {
        text-decoration: none
    }

    #egh .right-col .rightNav #searchIcon a i,
    #egh .right-col .rightNav>div a i {
        display: block;
        font-size: 1.25em;
        float: left;
        -webkit-transition: .3s;
        -o-transition: .3s;
        transition: .3s;
        position: relative;
        top: 50%;
        -webkit-transform: translateY(-50%);
        -ms-transform: translateY(-50%);
        transform: translateY(-50%)
    }

    #egh .right-col .rightNav #searchIcon a i.eg-header-icon-close,
    #egh .right-col .rightNav>div a i.eg-header-icon-close {
        display: none
    }

    #egh .right-col .rightNav #searchIcon a p,
    #egh .right-col .rightNav #searchIcon a span,
    #egh .right-col .rightNav>div a p,
    #egh .right-col .rightNav>div a span {
        font-size: .625em;
        display: inline-block;
        margin: 0;
        line-height: 22px;
        position: relative;
        top: 50%;
        -webkit-transform: translateY(-50%);
        -ms-transform: translateY(-50%);
        transform: translateY(-50%)
    }
}

@media only screen and (max-width:767px) {
    #egh .mobile-list-item .eg-header-icon-user {
        display: none !important
    }

    #egh .menu-icon {
        position: absolute;
        right: 0;
        z-index: 9999999;
        height: 3.7em;
        top: -3.7em;
        width: 3.7em;
        cursor: pointer;
        display: block
    }

    #egh .menu-icon .lines {
        top: 50%;
        right: 0;
        width: 32px;
        margin: 0 auto;
        -webkit-transition: background-color .15s ease-in-out 0s;
        -o-transition: background-color .15s 0s ease-in-out;
        -o-transition: background-color .15s ease-in-out 0s;
        transition: background-color .15s ease-in-out 0s;
        cursor: pointer;
        position: absolute;
        left: 0;
        display: inline-block;
        height: 2px
    }

    #egh .menu-icon .lines:after,
    #egh .menu-icon .lines:before {
        content: "";
        display: inline-block;
        position: absolute;
        left: 0;
        width: 100%;
        height: 2px;
        -webkit-transform-origin: 50% 50%;
        -ms-transform-origin: 50% 50%;
        transform-origin: 50% 50%;
        -webkit-transition: top .15s ease-in-out 0s, -webkit-transform .07s ease-in-out;
        transition: top .15s ease-in-out 0s, -webkit-transform .07s ease-in-out;
        -o-transition: top .15s 0s ease-in-out, transform .07s ease-in-out;
        -o-transition: top .15s ease-in-out 0s, transform .07s ease-in-out;
        transition: top .15s ease-in-out 0s, transform .07s ease-in-out;
        transition: top .15s ease-in-out 0s, transform .07s ease-in-out, -webkit-transform .07s ease-in-out
    }

    #egh .menu-icon .lines:before {
        top: 8px
    }

    #egh .menu-icon .lines:after {
        top: -8px
    }

    #egh .right-col {
        position: relative;
        overflow: visible;
        float: right;
        width: 20%
    }

    #egh .right-col .rightNav {
        display: block;
        position: fixed;
        top: 3.7em;
        right: 0;
        width: 90.75vw;
        max-width: 100%;
        height: calc(100% - 51px);
        max-height: 100vh;
        opacity: 1;
        margin: 0;
        padding: 0;
        overflow: hidden;
        -webkit-transform: translate3d(200%, 0, 0);
        transform: translate3d(200%, 0, 0);
        -webkit-transition: -webkit-transform .2s cubic-bezier(.075, .82, 1, 1);
        transition: -webkit-transform .2s cubic-bezier(.075, .82, 1, 1);
        -o-transition: transform .2s cubic-bezier(.075, .82, 1, 1);
        transition: transform .2s cubic-bezier(.075, .82, 1, 1);
        transition: transform .2s cubic-bezier(.075, .82, 1, 1), -webkit-transform .2s cubic-bezier(.075, .82, 1, 1)
    }

    #egh .right-col.active,
    #egh .right-col.active .menu-icon .lines {
        -webkit-transition: none !important;
        -o-transition: none !important;
        transition: none !important
    }

    #egh .right-col.active .menu-icon .lines {
        background-color: transparent !important;
        opacity: 1
    }

    #egh .right-col.active .menu-icon .lines:after,
    #egh .right-col.active .menu-icon .lines:before {
        top: 0;
        -webkit-transition: top .1s ease-in-out, -webkit-transform .2s ease-in-out;
        transition: top .1s ease-in-out, -webkit-transform .2s ease-in-out;
        -o-transition: top .1s ease-in-out, transform .2s ease-in-out;
        transition: top .1s ease-in-out, transform .2s ease-in-out;
        transition: top .1s ease-in-out, transform .2s ease-in-out, -webkit-transform .2s ease-in-out
    }

    #egh .right-col.active .menu-icon .lines:before {
        -webkit-transform: rotate(45deg);
        -ms-transform: rotate(45deg);
        transform: rotate(45deg)
    }

    #egh .right-col.active .menu-icon .lines:after {
        -webkit-transform: rotate(-45deg);
        -ms-transform: rotate(-45deg);
        transform: rotate(-45deg)
    }

    #egh .right-col.active .rightNav {
        -webkit-transform: translateZ(0);
        transform: translateZ(0)
    }

    #egh .right-col.active .rightNav.search-focus #form.search {
        border: 1px solid
    }

    #egh .right-col.active .rightNav.search-focus .icon-bar-wrapper {
        bottom: 52px
    }

    #egh .right-col.active .rightNav.search-focus .icon-bar-wrapper .icon-bar #cta,
    #egh .right-col.active .rightNav.search-focus .icon-bar-wrapper .icon-bar-toggle,
    #egh .right-col.active .rightNav.search-focus .icon-bar-wrapper .icon-bar .mobile-buttons {
        display: none
    }

    #egh .right-col.active .rightNav .mobile-links ul li {
        width: 100%;
        padding: .25em 2em .5em;
        float: none;
        clear: both;
        height: auto;
        margin: 0
    }

    #egh .right-col.active .rightNav .mobile-links ul li:not(.mobile-heading) a {
        line-height: 22px
    }

    #egh .right-col.active .rightNav .mobile-links ul li a {
        padding: 0;
        text-align: left
    }

    #egh .right-col.active .rightNav .mobile-links ul li a span {
        font-size: .625em
    }
}

@media only screen and (max-width:767px) and (orientation:landscape) and (min-aspect-ratio:1/1) {
    #egh .right-col.active .rightNav .mobile-links li {
        padding: .35em 2em !important
    }

    #egh .right-col.active .rightNav .mobile-links li:not(.mobile-heading) a {
        line-height: 20px
    }
}

@media only screen and (max-width:767px) {
    #egh .right-col.active #form {
        position: relative;
        margin: 0;
        padding: 20px;
        top: 6em;
        height: 100vh;
        left: 0;
        right: 0;
        width: 90.75vw;
        max-width: 100%;
        background: transparent
    }

    #egh .right-col.active #form.search {
        position: static;
        top: 0
    }

    #egh .right-col.active #form.search .search-btn {
        position: absolute;
        top: 0;
        right: 0
    }
}

@media only screen and (min-width:768px) {
    #egh #searchIcon.active {
        display: none
    }
}

@media only screen and (max-width:767px) {
    #egh #searchIcon {
        height: auto
    }

    #egh #searchIcon .item-label {
        display: none
    }

    #egh .right-col .rightNav #form.search,
    #egh .right-col .rightNav #form.search.active {
        -webkit-transition: none !important;
        -o-transition: none !important;
        transition: none !important
    }

    #egh .right-col .rightNav #form.search.active {
        position: absolute;
        top: 15px !important;
        left: 50% !important;
        -webkit-transform: translateX(-50%) !important;
        -ms-transform: translateX(-50%) !important;
        transform: translateX(-50%) !important;
        width: 80%
    }
}

#egh .right-col .rightNav #form.search {
    position: absolute;
    pointer-events: none;
    right: 20px;
    opacity: 0;
    width: 0;
    padding: 0;
    border-radius: 3px;
    z-index: 3;
    top: 5px
}

#egh .right-col .rightNav #form.search,
#egh .right-col .rightNav #form.search.active {
    height: 3em;
    -webkit-transition: width .4s cubic-bezier(.075, .82, 1, 1), opacity .4s cubic-bezier(.075, .82, 1, 1);
    -o-transition: width .4s cubic-bezier(.075, .82, 1, 1), opacity .4s cubic-bezier(.075, .82, 1, 1);
    transition: width .4s cubic-bezier(.075, .82, 1, 1), opacity .4s cubic-bezier(.075, .82, 1, 1)
}

#egh .right-col .rightNav #form.search.active {
    pointer-events: auto;
    width: 400px;
    right: 0;
    margin-right: 20px;
    left: 0;
    display: block;
    opacity: 1;
    position: relative;
    top: 50%;
    -webkit-transform: translateY(-50%);
    -ms-transform: translateY(-50%);
    transform: translateY(-50%)
}

#egh .right-col .rightNav #form.search .form-group {
    right: 75px;
    padding: 6px 10px;
    position: absolute;
    left: 0
}

#egh .right-col .rightNav #form.search .form-inline {
    height: 100%
}

#egh .right-col .rightNav #form.search .search-input {
    font-family: Arial;
    position: relative;
    bottom: 2px;
    vertical-align: middle;
    width: 100%;
    background: none;
    font-size: 1.2em;
    height: 2em;
    border: none
}

#egh .right-col .rightNav #form.search .search-input:focus {
    outline: none;
    -webkit-box-shadow: none;
    box-shadow: none
}

#egh .right-col .rightNav #form.search.closed .search-btns {
    display: none
}

#egh .right-col .rightNav #form.search .search-btns {
    display: block;
    position: absolute;
    height: 100%;
    margin: 0;
    top: 0
}

#egh .right-col .rightNav #form.search .search-btns a {
    position: relative;
    top: 50%;
    -webkit-transform: translateY(-50%);
    -ms-transform: translateY(-50%);
    transform: translateY(-50%);
    width: 36px;
    min-width: 36px;
    padding: 0 .5em;
    cursor: pointer
}

#egh .right-col .rightNav #form.search .close-btn {
    right: 0
}

#egh .right-col .rightNav #form.search .close-btn a {
    border-top-right-radius: 3px;
    border-bottom-right-radius: 3px;
    -webkit-transition: outline .3s ease-in-out;
    -o-transition: outline .3s ease-in-out;
    transition: outline .3s ease-in-out
}

#egh .right-col .rightNav #form.search .close-btn a .eg-header-icon-close {
    display: block;
    font-size: 1.5em
}

#egh .right-col .rightNav #form.search .close-btn a:hover,
#egh .right-col .rightNav #form.search .search-btn {
    -webkit-transition: outline .3s ease-in-out;
    -o-transition: outline .3s ease-in-out;
    transition: outline .3s ease-in-out
}

#egh .right-col .rightNav #form.search .search-btn {
    right: 36px
}

#egh .right-col .rightNav #form.search .search-btn:hover {
    -webkit-transition: outline .3s ease-in-out;
    -o-transition: outline .3s ease-in-out;
    transition: outline .3s ease-in-out
}

#egh .right-col .rightNav #form.search .search-btn a {
    width: auto;
    text-decoration: none
}

#egh .right-col .rightNav #form.search .search-btn a:hover {
    text-decoration: none
}

#egh .right-col .rightNav #form.search .search-btn i,
#egh .right-col .rightNav #form.search .search-btn span {
    padding: 0
}

#egh .right-col .rightNav #form.search .search-btn:before {
    content: "";
    background-color: transparent;
    height: 0
}

#egh nav.tablet #searchIcon {
    opacity: 1;
    height: auto;
    -webkit-transition: opacity .3s ease-in-out .4s;
    -o-transition: opacity .3s ease-in-out .4s;
    transition: opacity .3s ease-in-out .4s
}

#egh nav.tablet #searchIcon.active {
    height: 0;
    visibility: hidden;
    opacity: 0
}

#egh #user>ul {
    line-height: 12px
}

#egh #user>ul li {
    line-height: 18px
}

@media only screen and (min-width:768px) {
    #egh #user.dropdown {
        padding-right: 0
    }

    #egh #user.dropdown .eg-header-icon-user {
        position: relative;
        margin-left: 5px
    }

    #egh #user.dropdown ul {
        height: 0;
        position: absolute;
        visibility: hidden;
        overflow: hidden;
        top: 3.7em;
        opacity: 0;
        right: 0;
        min-width: 130px;
        padding: .5em 0;
        margin: 0
    }

    #egh #user.dropdown ul.ul-right {
        right: 0;
        left: auto
    }

    #egh #user.dropdown ul li {
        display: block;
        clear: both;
        width: 100%;
        float: none;
        height: 2em;
        margin: .1em 0
    }

    #egh #user.dropdown ul li:hover:before {
        background: transparent
    }

    #egh #user.dropdown ul li a {
        text-align: center;
        padding: 0 .9em
    }

    #egh #user.dropdown ul li a p,
    #egh #user.dropdown ul li a span {
        font-size: .625em;
        line-height: 1.5em;
        height: 100%
    }

    #egh #user.dropdown:hover ul {
        height: auto;
        opacity: 1;
        visibility: visible;
        -webkit-transition: all .1s ease-in-out;
        -o-transition: all .1s ease-in-out;
        transition: all .1s ease-in-out
    }
}

#egh nav.tablet #user.signed-in .eg-header-icon-user:after {
    right: 2px;
    bottom: -1px
}

#egh #user.signed-in .eg-header-icon-user:after {
    content: "";
    display: block;
    position: absolute;
    right: 2px;
    bottom: -1px;
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background-color: #52971c
}

#egh .display-name {
    padding: 0 10px
}

@media only screen and (max-width:767px) {
    #egh .display-name {
        vertical-align: top;
        margin: 20px 0 0;
        display: inline-block
    }
}

@media only screen and (max-width:767px) {
    #egh #user.signed-in {
        position: fixed;
        top: 0;
        right: 0;
        padding: 0;
        -webkit-transform: translate3d(100%, 0, 0);
        transform: translate3d(100%, 0, 0);
        -webkit-transition: -webkit-transform .2s cubic-bezier(.075, .82, 1, 1);
        transition: -webkit-transform .2s cubic-bezier(.075, .82, 1, 1);
        -o-transition: transform .2s cubic-bezier(.075, .82, 1, 1);
        transition: transform .2s cubic-bezier(.075, .82, 1, 1);
        transition: transform .2s cubic-bezier(.075, .82, 1, 1), -webkit-transform .2s cubic-bezier(.075, .82, 1, 1)
    }

    #egh #user.signed-in,
    #egh #user.signed-in ul {
        display: block;
        width: 100%;
        height: 100%;
        z-index: 5
    }

    #egh #user.signed-in ul {
        margin: 0;
        padding: 0 0 1em
    }

    #egh #user.signed-in ul li {
        float: none;
        display: block;
        width: 100%;
        height: auto
    }

    #egh #user.signed-in ul li a {
        text-align: left;
        height: auto
    }

    #egh #user.signed-in.active {
        -webkit-transform: translateZ(0);
        transform: translateZ(0)
    }
}

@media only screen and (min-width:480px) {
    #egh #user.sign-in.dropdown ul li a .eg-header-icon-user {
        display: none
    }
}

@media only screen and (min-width:768px) {
    #egh #user.sign-in.dropdown>ul {
        min-width: 110px
    }
}

#egh nav.desktop #user:not(.dropdown) ul,
#egh nav.tablet #user:not(.dropdown) ul {
    padding-left: 0;
    height: 100%;
    margin: 0
}

#egh nav.desktop #user:not(.dropdown) ul li,
#egh nav.tablet #user:not(.dropdown) ul li {
    height: 100%
}

#egh nav.desktop #user:not(.dropdown) .eg-header-icon-user,
#egh nav.tablet #user:not(.dropdown) .eg-header-icon-user {
    position: relative;
    margin-left: 5px
}

@media only screen and (max-width:767px) {
    #egh #user.sign-in {
        display: none
    }

    #egh #user.sign-in.dropdown {
        position: fixed;
        display: block;
        top: 0;
        right: 0;
        width: 100%;
        height: 100%;
        padding: 0;
        z-index: 5;
        -webkit-transform: translate3d(100%, 0, 0);
        transform: translate3d(100%, 0, 0);
        -webkit-transition: -webkit-transform .3s cubic-bezier(.075, .82, 1, 1);
        transition: -webkit-transform .3s cubic-bezier(.075, .82, 1, 1);
        -o-transition: transform .3s cubic-bezier(.075, .82, 1, 1);
        transition: transform .3s cubic-bezier(.075, .82, 1, 1);
        transition: transform .3s cubic-bezier(.075, .82, 1, 1), -webkit-transform .3s cubic-bezier(.075, .82, 1, 1)
    }

    #egh #user.sign-in.dropdown ul {
        padding: 0
    }

    #egh #user.sign-in.dropdown.active {
        -webkit-transform: translateZ(0);
        transform: translateZ(0)
    }
}

#egh #user.sign-in.dropdown li {
    margin: .4em 0
}

#egh #user.sign-in.dropdown li .sign-text.item-label {
    line-height: 15px;
    padding-bottom: 3px
}

#egh #user .sign-in a {
    cursor: default
}

#egh #user li {
    list-style: none
}

#egh #user li.mobile-heading a:before {
    top: 7px
}

#egh.resizing #siteNav,
#egh.resizing #siteNav ul li,
#egh.resizing .siteNav,
#egh.resizing .sitenav-wrap,
#egh.resizing .siteNavKids {
    -webkit-transition: none !important;
    -o-transition: none !important;
    transition: none !important
}

#egh:not(.init) #siteNav,
#egh:not(.init) .siteNav,
#egh:not(.init) .sitenav-wrap,
#egh:not(.init) .siteNavKids {
    display: none
}

#egh ul.siteNav {
    line-height: 18px
}

#egh nav.desktop .link-bar-divider {
    width: 40px
}

#egh nav.desktop .link-bar-divider:after {
    content: "";
    height: 30px;
    width: 1px;
    position: absolute;
    display: block;
    margin: 10px;
    opacity: .55;
    right: 10px
}

#egh nav.desktop .link-bar-divider:hover:before,
#egh nav.mobile .link-bar-divider,
#egh nav.tablet .link-bar-divider {
    display: none
}

#egh .sitenav-wrap {
    opacity: 1;
    height: 3.7em;
    max-height: 3.7em;
    overflow: hidden
}

#egh .sitenav-wrap:hover {
    overflow: visible
}

#egh .sitenav-img {
    max-height: 3.7em;
    padding: 12px 5px
}

#egh .sitenav-wrap.search-active {
    -webkit-transition: opacity .4s ease-in-out;
    -o-transition: opacity .4s ease-in-out;
    transition: opacity .4s ease-in-out;
    opacity: 0;
    height: 0;
    overflow: hidden
}

#egh .siteNav.active li a {
    cursor: pointer
}

#egh .siteNav li {
    float: left
}

@media only screen and (min-width:1200px) {
    #egh .siteNav .siteNavKids {
        display: none
    }
}

#egh .desktop .siteNavKids li a p,
#egh .desktop .siteNavKids li a span,
#egh .desktop .siteNav li a p,
#egh .desktop .siteNav li a span {
    position: relative;
    top: 50%;
    -webkit-transform: translateY(-50%);
    -ms-transform: translateY(-50%);
    transform: translateY(-50%);
    font-size: .75em
}

#egh .siteNav,
#egh .siteNavKids {
    float: left;
    list-style: none;
    margin: 0;
    padding: 0;
    height: 3.7em
}

#egh .siteNavKids li,
#egh .siteNav li {
    display: inline-block;
    *zoom: 1;
    *display: inline;
    position: relative;
    -webkit-transform: translateZ(0);
    transform: translateZ(0);
    height: 100%;
    padding-right: 0 !important
}

#egh .siteNavKids li.active:before,
#egh .siteNav li.active:before {
    height: 5px
}

#egh .siteNavKids li:before,
#egh .siteNav li:before {
    content: "";
    display: block;
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 0;
    z-index: -1;
    -webkit-transition: height .2s ease-in-out;
    -o-transition: height .2s ease-in-out;
    transition: height .2s ease-in-out
}

#egh .siteNavKids li a,
#egh .siteNav li a {
    display: block;
    font-family: OpenSans, sans-serif, arial;
    text-transform: uppercase;
    letter-spacing: .075em;
    padding: 0 1em;
    height: 100%;
    max-height: 3.7em
}

#egh .siteNavKids li a p,
#egh .siteNavKids li a span,
#egh .siteNav li a p,
#egh .siteNav li a span {
    font-size: .75em
}

#egh .siteNavKids li a:active,
#egh .siteNavKids li a:hover,
#egh .siteNavKids li a:link,
#egh .siteNavKids li a:visited,
#egh .siteNav li a:active,
#egh .siteNav li a:hover,
#egh .siteNav li a:link,
#egh .siteNav li a:visited {
    text-decoration: none
}

#egh .siteNavKids li:hover:before,
#egh .siteNav li:hover:before {
    height: 5px
}

#egh .siteNavKids li.dropdown,
#egh .siteNav li.dropdown {
    height: 3.7em
}

#egh .siteNavKids li.dropdown>a>span,
#egh .siteNavKids li.dropdown>span,
#egh .siteNav li.dropdown>a>span,
#egh .siteNav li.dropdown>span {
    padding: 2.5em 2em 2.5em 0;
    text-transform: uppercase;
    font-size: 1em
}

#egh .siteNavKids li.dropdown>a>span:before,
#egh .siteNavKids li.dropdown>span:before,
#egh .siteNav li.dropdown>a>span:before,
#egh .siteNav li.dropdown>span:before {
    -webkit-transition: height .1s ease-in-out;
    -o-transition: height .1s ease-in-out;
    transition: height .1s ease-in-out;
    content: "";
    bottom: 0;
    left: 0;
    width: 100%;
    z-index: -1;
    height: 0;
    position: absolute
}

#egh .siteNavKids li.dropdown>a>span:after,
#egh .siteNavKids li.dropdown>span:after,
#egh .siteNav li.dropdown>a>span:after,
#egh .siteNav li.dropdown>span:after {
    right: 16px;
    top: 42px
}

#egh .siteNavKids li.dropdown:hover span:before,
#egh .siteNav li.dropdown:hover span:before {
    height: 200%
}

#egh .siteNavKids li.dropdown:hover ul,
#egh .siteNav li.dropdown:hover ul {
    padding-bottom: 1em;
    opacity: 1;
    height: auto;
    visibility: visible;
    -webkit-transition: all .1s ease-in-out;
    -o-transition: all .1s ease-in-out;
    transition: all .1s ease-in-out
}

#egh .siteNavKids li ul,
#egh .siteNav li ul {
    opacity: 0;
    visibility: hidden;
    display: block;
    overflow: hidden;
    height: 0;
    padding: 0;
    width: auto;
    position: absolute;
    top: 50.8px;
    left: 0;
    min-width: 160px
}

#egh .siteNavKids li ul.show-grandkid,
#egh .siteNav li ul.show-grandkid {
    overflow: visible
}

@media only screen and (max-width:767px) {

    #egh .siteNavKids li ul,
    #egh .siteNav li ul {
        height: 3.7em
    }
}

#egh .siteNavKids li ul li,
#egh .siteNav li ul li {
    float: none;
    display: block;
    width: 100%
}

#egh .siteNavKids li ul li:hover:before,
#egh .siteNav li ul li:hover:before {
    background: transparent;
    height: 0
}

#egh .siteNavKids li ul li:hover:before a,
#egh .siteNavKids li ul li:hover:before span,
#egh .siteNav li ul li:hover:before a,
#egh .siteNav li ul li:hover:before span {
    opacity: 1
}

#egh .siteNavKids li ul li:before,
#egh .siteNav li ul li:before {
    background: transparent
}

#egh .siteNavKids li ul li a,
#egh .siteNav li ul li a {
    padding: .5em .8em;
    text-align: left
}

#egh .siteNav.active,
#egh .siteNavKids.active {
    display: block
}

#egh .sitenav-wrap:not(.active) .siteNavKids.tablet {
    display: none
}

@media only screen and (min-width:768px) and (max-width:1199px) {
    #egh .siteNav li a {
        padding: 0 .75em
    }
}

@media only screen and (max-width:767px) {
    #egh .right-col.active .rightNav .mobile-links .siteNavKids.mobile.active {
        z-index: 11
    }
}

#egh .siteNav.tablet,
#egh .siteNavKids.tablet {
    top: 3.7em;
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    -webkit-transition: -webkit-transform .2s cubic-bezier(.075, .82, 1, 1);
    transition: -webkit-transform .2s cubic-bezier(.075, .82, 1, 1);
    -o-transition: transform .2s cubic-bezier(.075, .82, 1, 1);
    transition: transform .2s cubic-bezier(.075, .82, 1, 1);
    transition: transform .2s cubic-bezier(.075, .82, 1, 1), -webkit-transform .2s cubic-bezier(.075, .82, 1, 1)
}

#egh .siteNav.tablet.active,
#egh .siteNavKids.tablet.active {
    -webkit-transform: translateZ(0);
    transform: translateZ(0)
}

#egh .siteNav.mobile,
#egh .siteNavKids.mobile {
    top: 0;
    border: none
}

#egh .siteNav.mobile {
    -webkit-transform: translateZ(0);
    transform: translateZ(0);
    -webkit-transition: none !important;
    -o-transition: none !important;
    transition: none !important
}

#egh .siteNav.mobile li {
    padding: .5em 2em !important
}

#egh .siteNav.mobile .site-nav-kids-desktop {
    display: none
}

#egh .siteNavKids.mobile {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    -webkit-transition: -webkit-transform .2s cubic-bezier(.075, .82, 1, 1);
    transition: -webkit-transform .2s cubic-bezier(.075, .82, 1, 1);
    -o-transition: transform .2s cubic-bezier(.075, .82, 1, 1);
    transition: transform .2s cubic-bezier(.075, .82, 1, 1);
    transition: transform .2s cubic-bezier(.075, .82, 1, 1), -webkit-transform .2s cubic-bezier(.075, .82, 1, 1);
    width: 100%
}

#egh .siteNavKids.mobile li.mobile-heading a:before {
    top: 12px
}

#egh .siteNavKids.mobile.active {
    -webkit-transform: translateZ(0);
    transform: translateZ(0)
}

#egh .siteNav.mobile,
#egh .siteNav.tablet,
#egh .siteNavKids.mobile,
#egh .siteNavKids.tablet {
    position: absolute;
    height: 100vh;
    opacity: 1;
    width: 90.75vw;
    max-width: 100%;
    right: 0;
    margin: 0;
    z-index: 3;
    overflow-y: auto;
    overflow-x: hidden;
    padding: 0
}

#egh .siteNav.mobile li:not(.sub-heading),
#egh .siteNav.tablet li:not(.sub-heading),
#egh .siteNavKids.mobile li:not(.sub-heading),
#egh .siteNavKids.tablet li:not(.sub-heading) {
    padding: 1em 2em;
    border-bottom: 1px solid
}

#egh .siteNav.mobile li,
#egh .siteNav.tablet li,
#egh .siteNavKids.mobile li,
#egh .siteNavKids.tablet li {
    width: 100%;
    clear: both;
    visibility: hidden;
    display: block;
    float: none;
    height: auto
}

#egh .siteNav.mobile li.dropdown,
#egh .siteNav.tablet li.dropdown,
#egh .siteNavKids.mobile li.dropdown,
#egh .siteNavKids.tablet li.dropdown {
    height: auto
}

#egh .siteNav.mobile li.dropdown>a>span,
#egh .siteNav.tablet li.dropdown>a>span,
#egh .siteNavKids.mobile li.dropdown>a>span,
#egh .siteNavKids.tablet li.dropdown>a>span {
    cursor: default
}

#egh .siteNav.mobile li.dropdown ul,
#egh .siteNav.tablet li.dropdown ul,
#egh .siteNavKids.mobile li.dropdown ul,
#egh .siteNavKids.tablet li.dropdown ul {
    padding: 1em 0;
    display: block;
    width: 100%;
    opacity: 1;
    visibility: visible;
    position: relative;
    top: auto;
    height: auto
}

#egh .siteNav.mobile li.dropdown ul li,
#egh .siteNav.tablet li.dropdown ul li,
#egh .siteNavKids.mobile li.dropdown ul li,
#egh .siteNavKids.tablet li.dropdown ul li {
    width: 100%
}

#egh .siteNav.mobile li.dropdown ul li a,
#egh .siteNav.tablet li.dropdown ul li a,
#egh .siteNavKids.mobile li.dropdown ul li a,
#egh .siteNavKids.tablet li.dropdown ul li a {
    text-align: center
}

#egh .siteNav.mobile li:before,
#egh .siteNav.tablet li:before,
#egh .siteNavKids.mobile li:before,
#egh .siteNavKids.tablet li:before {
    background-color: transparent !important
}

#egh .siteNav.mobile li a,
#egh .siteNav.tablet li a,
#egh .siteNavKids.mobile li a,
#egh .siteNavKids.tablet li a {
    text-align: left;
    width: 100%;
    font-size: 1.5em;
    max-height: 40px;
    height: 20px
}

#egh .siteNav.mobile .sub-link-item,
#egh .siteNav.tablet .sub-link-item,
#egh .siteNavKids.mobile .sub-link-item,
#egh .siteNavKids.tablet .sub-link-item {
    position: relative
}

#egh .siteNav.mobile .sub-link-item span,
#egh .siteNav.tablet .sub-link-item span,
#egh .siteNavKids.mobile .sub-link-item span,
#egh .siteNavKids.tablet .sub-link-item span {
    position: relative;
    display: inline-block;
    width: 100%
}

#egh .siteNav.mobile .sub-link-item span:after,
#egh .siteNav.tablet .sub-link-item span:after,
#egh .siteNavKids.mobile .sub-link-item span:after,
#egh .siteNavKids.tablet .sub-link-item span:after {
    content: "";
    display: block;
    position: absolute;
    right: 3px;
    top: 7px;
    width: .5em;
    height: .5em;
    border-top: 2px solid;
    border-right: 2px solid;
    opacity: 1;
    -webkit-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    transform: rotate(45deg)
}

#egh .siteNav.mobile.active li,
#egh .siteNav.tablet.active li,
#egh .siteNavKids.mobile.active li,
#egh .siteNavKids.tablet.active li {
    visibility: visible
}

#egh li.kid.active,
#egh li.kid.active a,
#egh li.kid:hover {
    opacity: 1
}

#egh li.kid.active:before {
    height: 0 !important
}

#egh li.kid.spread-arrow:after {
    content: "";
    display: block;
    position: absolute;
    top: 1em;
    right: 1.5em;
    width: .5em;
    height: .5em;
    border-top: 2px solid;
    border-right: 2px solid;
    opacity: .6;
    -webkit-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    transform: rotate(45deg)
}

#egh li.kid.spread-arrow:hover .grand-kids {
    display: block
}

#egh li.kid.spread-arrow .grand-kids {
    display: none;
    left: 99%;
    float: right;
    top: 0
}

#egh {
    /*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
    font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
    font-size: 14px !important;
    line-height: 1.42857143;
    background-color: #2a2a2a;
    background: #2a2a2a;
    -webkit-font-smoothing: auto;
    text-shadow: 1px 1px 1px rgba(0, 0, 0, .004);
    text-rendering: optimizeLegibility;
    -webkit-font-feature-settings: "kern"1;
    font-feature-settings: "kern"1;
    height: 3.7em;
    position: static !important;
    -moz-text-size-adjust: 100%;
    text-size-adjust: 100%
}

#egh,
#egh html {
    -webkit-text-size-adjust: 100%;
    -ms-text-size-adjust: 100%
}

#egh html {
    font-family: sans-serif
}

#egh body {
    margin: 0
}

#egh article,
#egh aside,
#egh details,
#egh figcaption,
#egh figure,
#egh footer,
#egh header,
#egh hgroup,
#egh main,
#egh menu,
#egh nav,
#egh section,
#egh summary {
    display: block
}

#egh audio,
#egh canvas,
#egh progress,
#egh video {
    display: inline-block;
    vertical-align: baseline
}

#egh audio:not([controls]) {
    display: none;
    height: 0
}

#egh [hidden],
#egh template {
    display: none
}

#egh a {
    background-color: transparent
}

#egh a:active,
#egh a:hover {
    outline: 0
}

#egh abbr[title] {
    border-bottom: none;
    text-decoration: underline;
    -webkit-text-decoration: underline dotted;
    text-decoration: underline dotted
}

#egh b,
#egh strong {
    font-weight: 700
}

#egh dfn {
    font-style: italic
}

#egh h1 {
    font-size: 2em;
    margin: .67em 0
}

#egh mark {
    background: #ff0;
    color: #000
}

#egh small {
    font-size: 80%
}

#egh sub,
#egh sup {
    font-size: 75%;
    line-height: 0;
    position: relative;
    vertical-align: baseline
}

#egh sup {
    top: -.5em
}

#egh sub {
    bottom: -.25em
}

#egh img {
    border: 0
}

#egh svg:not(:root) {
    overflow: hidden
}

#egh figure {
    margin: 1em 40px
}

#egh hr {
    -webkit-box-sizing: content-box;
    box-sizing: content-box;
    height: 0
}

#egh pre {
    overflow: auto
}

#egh code,
#egh kbd,
#egh pre,
#egh samp {
    font-family: monospace, monospace;
    font-size: 1em
}

#egh button,
#egh input,
#egh optgroup,
#egh select,
#egh textarea {
    color: inherit;
    font: inherit;
    margin: 0
}

#egh button {
    overflow: visible
}

#egh button,
#egh select {
    text-transform: none
}

#egh button,
#egh html input[type=button],
#egh input[type=reset],
#egh input[type=submit] {
    -webkit-appearance: button;
    cursor: pointer
}

#egh button[disabled],
#egh html input[disabled] {
    cursor: default
}

#egh button::-moz-focus-inner,
#egh input::-moz-focus-inner {
    border: 0;
    padding: 0
}

#egh input {
    line-height: normal
}

#egh input[type=checkbox],
#egh input[type=radio] {
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
    padding: 0
}

#egh input[type=number]::-webkit-inner-spin-button,
#egh input[type=number]::-webkit-outer-spin-button {
    height: auto
}

#egh input[type=search] {
    -webkit-appearance: textfield;
    -webkit-box-sizing: content-box;
    box-sizing: content-box
}

#egh input[type=search]::-webkit-search-cancel-button,
#egh input[type=search]::-webkit-search-decoration {
    -webkit-appearance: none
}

#egh fieldset {
    border: 1px solid silver;
    margin: 0 2px;
    padding: .35em .625em .75em
}

#egh legend {
    border: 0;
    padding: 0
}

#egh textarea {
    overflow: auto
}

#egh optgroup {
    font-weight: 700
}

#egh table {
    border-collapse: collapse;
    border-spacing: 0
}

#egh td,
#egh th {
    padding: 0
}

#egh *,
#egh :after,
#egh :before {
    -webkit-box-sizing: border-box;
    box-sizing: border-box
}

#egh ul {
    margin: 0
}

#egh a {
    outline: 0 !important
}

#egh ul {
    line-height: normal
}

#egh a,
#egh span {
    text-shadow: none;
    font-weight: 400
}

#egh [role=button],
#egh a {
    cursor: pointer
}

#egh [role=button]:active,
#egh [role=button]:focus,
#egh [role=button]:visited,
#egh a:active,
#egh a:focus,
#egh a:visited {
    text-decoration: none;
    outline: none
}

#egh p {
    margin: 0;
    padding: 0
}

#egh .cursor-default {
    cursor: default
}

#egh .cursor-pointer {
    cursor: pointer
}

#egh .hidden {
    display: none !important
}

body {
    margin: 0
}

body.egh-hide-overflow {
    height: 100%;
    width: 100%;
    overflow: hidden;
    position: fixed
}

@font-face {
    font-family: OpenSans;
    font-weight: 400;
    font-style: normal;
    font-display: auto;
    src: url(83efe33660ab6a7fe428c8078d47485f.html);
    src: url(83efe33660ab6a7fe428c8078d47485fd41d.html?#iefix) format("embedded-opentype"), url(55b8ce1f9a32bb0f83f14813eac0b7ca.html) format("woff"), url(c7571df954bd2b7ffcd78628a24ff2ed.html) format("truetype"), url(23f7b507a6be9b830ab998998fe39cdd.html#open_sansregular) format("svg")
}

@font-face {
    font-family: OpenSans;
    font-weight: 500;
    font-style: normal;
    font-display: auto;
    src: url(3055c832e06d4423d110734ab7526880.html);
    src: url(3055c832e06d4423d110734ab7526880d41d.html?#iefix) format("embedded-opentype"), url(834e3616d9e57f3f027e96394f43efa0.html) format("woff"), url(a503b79af3e35504c7b322dbc84cac2d.html) format("truetype"), url(9402324d7a636082de85243c07329258.html#open_sanssemibold) format("svg")
}

@font-face {
    font-family: eg-header-icomoon;
    src: url(data:application/vnd.ms-fontobject;base64,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AgUCCQEBAQICAQEBAQEBAQEBAQIBAwMBBQEBBwQDAQIBAgECAgEDAhYCAwQCAQEGAQIBAgIFAgEDAQMBBQEDAQIHAQMBAwEEAQQDAgUCAwQDAQQBAQEBAQIBAgEFBQUGDQMCAQIBAgIYNhgNAgEEAQEBBAEEAQMCAgEDAQEDAQMBAQMCAQEEAQIeAgEDAQEEAQEBBAQBAQYBAQMBBAEBAgMBAQMDIQEBAQENAgEBAS4BAQECAgEBAZioAVYdX14/OTlAQBISJB0lERI6BQYMCgwFBgUGDAsMBQY6EhIkHiQSErABAQEBBAUCAQECAgQDAQIDAwISAgQGAwMCAgECBQIBAgMCBAICAQEEAQQBAgICAgIBAQUBAgMBBQIMAwIBAgEBAwECAQIDAQIBAgIBAgICAQIDBgUBAgEEBAIBAQEBAQEBAQECAQQBAgEEAQICAgIBAQMDBQ4CAwICAwECAwECAwECAQMBAgUCAgEBBQEEAgICAgEBAgEBAgIDBQoCAQEBAwEBAgIBAQQCAQMBBgIBAgIBAgECAwIBBgQDAQMBAQEBAQEIAgECAQICAQIBAwIBCgICAQECAgYBAwECAwECAQIDAgECAYJiDAUGkQYGAUISEiz9NAUECgkKCwEEBQICAgKVBwIDAgMHlQICAgIFBQsJCgoEBQUEAsMsEhKI/neNAQECAgICAgICAQICAgICAQECAQICAgEBAgICAXdHAQICAgEBAgMCAQECAgIBAQICAgEBAgICAQMCAgIBAgICAgIBAQICAgECAgICAgECAQECAgIBRncCAgICAgEDAgIBAgICAgICAgICAQIBAQICFBISJWglEhKPAYk2cDZ2N5MzAQYDAQEBAQIBAQEBAQEBAQMCBAEJAgEDAgIDAQECAwECAQUFCQEFAgECAgECAQIDAQIFAwIFAwUDAQEBAQEBAQEBAQEBAwEBAQIEAQEDAgMCBQIDAgIFAQEBAQEBAQIBAwICBAIBAQMCAwIMBAIBAQMDBQQCAgEBAQIBDxgEQwQCAQgDAQMIAQIHAgEGAgICAwEGAgECBwIHAgECBAIEAQIBCAEFBQECBgEDCAECAwEIAQgBAwwBAgEIAQgBAgEFAQUBAQIHBgECAQIBAgECAwECAQIBAQIBAgEDAgMBAgECAcY5phl3GxQZFAEB/SUSEhISJFBNCwYGBgYL+AwF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);
    src: url(data:application/vnd.ms-fontobject;base64,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AgUCCQEBAQICAQEBAQEBAQEBAQIBAwMBBQEBBwQDAQIBAgECAgEDAhYCAwQCAQEGAQIBAgIFAgEDAQMBBQEDAQIHAQMBAwEEAQQDAgUCAwQDAQQBAQEBAQIBAgEFBQUGDQMCAQIBAgIYNhgNAgEEAQEBBAEEAQMCAgEDAQEDAQMBAQMCAQEEAQIeAgEDAQEEAQEBBAQBAQYBAQMBBAEBAgMBAQMDIQEBAQENAgEBAS4BAQECAgEBAZioAVYdX14/OTlAQBISJB0lERI6BQYMCgwFBgUGDAsMBQY6EhIkHiQSErABAQEBBAUCAQECAgQDAQIDAwISAgQGAwMCAgECBQIBAgMCBAICAQEEAQQBAgICAgIBAQUBAgMBBQIMAwIBAgEBAwECAQIDAQIBAgIBAgICAQIDBgUBAgEEBAIBAQEBAQEBAQECAQQBAgEEAQICAgIBAQMDBQ4CAwICAwECAwECAwECAQMBAgUCAgEBBQEEAgICAgEBAgEBAgIDBQoCAQEBAwEBAgIBAQQCAQMBBgIBAgIBAgECAwIBBgQDAQMBAQEBAQEIAgECAQICAQIBAwIBCgICAQECAgYBAwECAwECAQIDAgECAYJiDAUGkQYGAUISEiz9NAUECgkKCwEEBQICAgKVBwIDAgMHlQICAgIFBQsJCgoEBQUEAsMsEhKI/neNAQECAgICAgICAQICAgICAQECAQICAgEBAgICAXdHAQICAgEBAgMCAQECAgIBAQICAgEBAgICAQMCAgIBAgICAgIBAQICAgECAgICAgECAQECAgIBRncCAgICAgEDAgIBAgICAgICAgICAQIBAQICFBISJWglEhKPAYk2cDZ2N5MzAQYDAQEBAQIBAQEBAQEBAQMCBAEJAgEDAgIDAQECAwECAQUFCQEFAgECAgECAQIDAQIFAwIFAwUDAQEBAQEBAQEBAQEBAwEBAQIEAQEDAgMCBQIDAgIFAQEBAQEBAQIBAwICBAIBAQMCAwIMBAIBAQMDBQQCAgEBAQIBDxgEQwQCAQgDAQMIAQIHAgEGAgICAwEGAgECBwIHAgECBAIEAQIBCAEFBQECBgEDCAECAwEIAQgBAwwBAgEIAQgBAgEFAQUBAQIHBgECAQIBAgECAwECAQIBAQIBAgEDAgMBAgECAcY5phl3GxQZFAEB/SUSEhISJFBNCwYGBgYL+AwF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?#iefix3jialc) format("embedded-opentype"), url(data:font/ttf;base64,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AyEBAQEBDQIBAQEuAQEBAgIBAQGYqAFWHV9ePzk5QEASEiQdJRESOgUGDAoMBQYFBgwLDAUGOhISJB4kEhKwAQEBAQQFAgEBAgIEAwECAwMCEgIEBgMDAgIBAgUCAQIDAgQCAgEBBAEEAQICAgICAQEFAQIDAQUCDAMCAQIBAQMBAgECAwECAQICAQICAgECAwYFAQIBBAQCAQEBAQEBAQEBAgEEAQIBBAECAgICAQEDAwUOAgMCAgMBAgMBAgMBAgEDAQIFAgIBAQUBBAICAgIBAQIBAQICAwUKAgEBAQMBAQICAQEEAgEDAQYCAQICAQIBAgMCAQYEAwEDAQEBAQEBCAIBAgECAgECAQMCAQoCAgEBAgIGAQMBAgMBAgECAwIBAgGCYgwFBpEGBgFCEhIs/TQFBAoJCgsBBAUCAgIClQcCAwIDB5UCAgICBQULCQoKBAUFBALDLBISiP53jQEBAgICAgICAgECAgICAgEBAgECAgIBAQICAgF3RwECAgIBAQIDAgEBAgICAQECAgIBAQICAgEDAgICAQICAgICAQECAgIBAgICAgIBAgEBAgICAUZ3AgICAgIBAwICAQICAgICAgICAgECAQECAhQSEiVoJRISjwGJNnA2djeTMwEGAwEBAQECAQEBAQEBAQEDAgQBCQIBAwICAwEBAgMBAgEFBQkBBQIBAgIBAgECAwECBQMCBQMFAwEBAQEBAQEBAQEBAQMBAQECBAEBAwIDAgUCAwICBQEBAQEBAQECAQMCAgQCAQEDAgMCDAQCAQEDAwUEAgIBAQECAQ8YBEMEAgEIAwEDCAECBwIBBgICAgMBBgIBAgcCBwIBAgQCBAECAQgBBQUBAgYBAwgBAgMBCAEIAQMMAQIBCAEIAQIBBQEFAQECBwYBAgECAQIBAgMBAgECAQECAQIBAwIDAQIBAgHGOaYZdxsUGRQBAf0lEhISEiRQTQsGBgYGC/gMBQYFBgxYWyUSEhIS0ggCAQIBAgEBBgUBAQECAQEBAQEBAgIBAQMBAQECAQQBAgEBAQECBAIEAgECAQIBAQIBAQEBAQEBAgIFAgMBAQEBAQEBAQEDAgEBAQIEAwECAQMCBQIDAQMDAgEGAgQCAQECAQECAQEBAQEBAQEBAQEBAQEBAQEEAgMBAgcCBQIBAgEBAQEBAQIBAQMCAQECAgIBAQIBAQEB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) format("truetype"), url(data:font/woff;base64,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AgECAQUFBQYNAwIBAgECAhg2GA0CAQQBAQEEAQQBAwICAQMBAQMBAwEBAwIBAQQBAh4CAQMBAQQBAQEEBAEBBgEBAwEEAQECAwEBAwMhAQEBAQ0CAQEBLgEBAQICAQEBmKgBVh1fXj85OUBAEhIkHSUREjoFBgwKDAUGBQYMCwwFBjoSEiQeJBISsAEBAQEEBQIBAQICBAMBAgMDAhICBAYDAwICAQIFAgECAwIEAgIBAQQBBAECAgICAgEBBQECAwEFAgwDAgECAQEDAQIBAgMBAgECAgECAgIBAgMGBQECAQQEAgEBAQEBAQEBAQIBBAECAQQBAgICAgEBAwMFDgIDAgIDAQIDAQIDAQIBAwECBQICAQEFAQQCAgICAQECAQECAgMFCgIBAQEDAQECAgEBBAIBAwEGAgECAgECAQIDAgEGBAMBAwEBAQEBAQgCAQIBAgIBAgEDAgEKAgIBAQICBgEDAQIDAQIBAgMCAQIBgmIMBQaRBgYBQhISLP00BQQKCQoLAQQFAgICApUHAgMCAweVAgICAgUFCwkKCgQFBQQCwywSEoj+d40BAQICAgICAgIBAgICAgIBAQIBAgICAQECAgIBd0cBAgICAQECAwIBAQICAgEBAgICAQECAgIBAwICAgECAgICAgEBAgICAQICAgICAQIBAQICAgFGdwICAgICAQMCAgECAgICAgICAgIBAgEBAgIUEhIlaCUSEo8BiTZwNnY3kzMBBgMBAQEBAgEBAQEBAQEBAwIEAQkCAQMCAgMBAQIDAQIBBQUJAQUCAQICAQIBAgMBAgUDAgUDBQMBAQEBAQEBAQEBAQEDAQEBAgQBAQMCAwIFAgMCAgUBAQEBAQEBAgEDAgIEAgEBAwIDAgwEAgEBAwMFBAICAQEBAgEPGARDBAIBCAMBAwgBAgcCAQYCAgIDAQYCAQIHAgcCAQIEAgQBAgEIAQUFAQIGAQMIAQIDAQgBCAEDDAECAQgBCAECAQUBBQEBAgcGAQIBAgECAQIDAQIBAgEBAgECAQMCAwECAQIBxjmmGXcbFBkUAQH9JRISEhIkUE0LBgYGBgv4DAUGBQYMWFslEhISEtIIAgECAQIBAQYFAQEBAgEBAQEBAQICAQEDAQEBAgEEAQIBAQEBAgQCBAIBAgECAQECAQEBAQEBAQICBQIDAQEBAQEBAQEBAwIBAQEC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) format("woff"), url(6636fdbd1e4ad70952270cb757d8eb7d.svg#icomoon) format("svg");
    font-weight: 400;
    font-style: normal;
    font-display: auto
}

[class*=" eg-header-icon-"],
[class^=eg-header-icon-] {
    font-family: eg-header-icomoon;
    font-style: normal;
    font-weight: 400;
    -webkit-font-feature-settings: normal;
    font-feature-settings: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale
}

.eg-header-icon-locale:before {
    content: "\E603"
}

.eg-header-icon-user:before {
    content: "\E901"
}

.eg-header-icon-close:before {
    content: "\E902"
}

.eg-header-icon-search:before {
    content: "\E903"
}

.eg-header-icon-download:before {
    content: "\E904"
}

#egh.resizing nav {
    -webkit-transition: none !important;
    -o-transition: none !important;
    transition: none !important
}

#egh.menu-open.pos-fixed,
#egh nav {
    height: 3.7em
}

#egh nav {
    position: absolute;
    overflow: visible;
    max-width: 100%;
    top: 0;
    left: 0;
    right: 0;
    z-index: 99998;
    font-size: 100%
}

#egh nav.menu-open.mobile,
#egh nav.menu-open.tablet {
    width: 100vw;
    max-width: 100vw
}

#egh nav.menu-open.pos-fixed {
    position: fixed;
    height: 3.7em;
    -webkit-transition: none !important;
    -o-transition: none !important;
    transition: none !important;
    top: 0 !important
}

#egh nav #propNav {
    height: 3.7em;
    padding: 0
}

#egh nav .dropdown {
    padding-right: 2em
}

@media only screen and (max-width:767px) {
    #egh nav .dropdown {
        padding-right: 0
    }
}

#egh nav .dropdown:hover:before {
    height: 0 !important
}

#egh nav .dropdown ul {
    margin-left: 0
}

#egh nav .dropdown ul a:hover {
    opacity: 1
}

body.ja #egh .siteNav li a span,
body.ko #egh .siteNav li a span,
body.zh-CN #egh .siteNav li a span {
    font-size: 1em
}

body.ja #egh #locale ul li a span,
body.ja #egh #user.dropdown ul li a span,
body.ja #egh .desktop .siteNav li a p,
body.ja #egh .right-col .rightNav>div a span,
body.ko #egh #locale ul li a span,
body.ko #egh #user.dropdown ul li a span,
body.ko #egh .desktop .siteNav li a p,
body.ko #egh .right-col .rightNav>div a span,
body.zh-CN #egh #locale ul li a span,
body.zh-CN #egh #user.dropdown ul li a span,
body.zh-CN #egh .desktop .siteNav li a p,
body.zh-CN #egh .right-col .rightNav>div a span {
    font-size: .9em
}

body.zh-CN #egh .siteNavKids li a,
body.zh-CN #egh .siteNav li a {
    font-family: OpenSans, Microsoft Yahei, STHeiti Light, Verdana, sans-serif
}

body.ar #egh #eg-properties,
body.ar #egh #form.search input,
body.ar #egh #user .mobile-list-item a,
body.ar #egh .locale-list .mobile-list-item a {
    text-align: right !important
}

#egh .mobile-overlay {
    position: fixed;
    top: 3.7em;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, .75);
    opacity: 0;
    z-index: -99999;
    visibility: hidden;
    display: none;
    -webkit-transition: opacity .3s cubic-bezier(.075, .82, 1, 1);
    -o-transition: opacity .3s cubic-bezier(.075, .82, 1, 1);
    transition: opacity .3s cubic-bezier(.075, .82, 1, 1);
    cursor: default
}

#egh .mobile-overlay.active {
    display: block;
    visibility: visible;
    opacity: 1;
    z-index: -1
}

#egh .desktop .mobile-overlay {
    display: none
}

#egh .tablet li.mobile-heading {
    width: 100%;
    display: block;
    padding: .6em 1em;
    cursor: pointer;
    opacity: .85;
    text-align: center;
    margin: 0 !important
}

#egh .tablet li.mobile-heading>a {
    margin: 0 auto;
    text-align: center !important;
    letter-spacing: 2px;
    text-transform: uppercase;
    font-weight: 400;
    position: relative;
    width: 100%;
    font-size: 1.25em;
    height: auto !important;
    padding: 0
}

#egh .tablet li.mobile-heading>a span {
    font-size: .8em !important
}

#egh .tablet li.mobile-heading>a:before {
    content: "";
    display: block;
    position: absolute;
    left: 0;
    top: 10px;
    width: .4em;
    height: .4em;
    border-top: 2px solid;
    border-left: 2px solid;
    -webkit-transform: rotate(-45deg);
    -ms-transform: rotate(-45deg);
    transform: rotate(-45deg)
}

@media only screen and (max-width:767px) {
    #egh li.mobile-heading {
        width: 100%;
        display: block;
        padding: .6em 1em;
        cursor: pointer;
        opacity: .85;
        text-align: center;
        margin: 0 !important
    }

    #egh li.mobile-heading>a {
        margin: 0 auto;
        text-align: center !important;
        letter-spacing: 2px;
        text-transform: uppercase;
        font-weight: 400;
        position: relative;
        width: 100%;
        font-size: 1.25em;
        height: auto !important;
        padding: 0
    }

    #egh li.mobile-heading>a span {
        font-size: .8em !important
    }

    #egh li.mobile-heading>a:before {
        content: "";
        display: block;
        position: absolute;
        left: 0;
        top: 10px;
        width: .4em;
        height: .4em;
        border-top: 2px solid;
        border-left: 2px solid;
        -webkit-transform: rotate(-45deg);
        -ms-transform: rotate(-45deg);
        transform: rotate(-45deg)
    }
}

@media only screen and (max-width:767px) {
    #egh li.mobile-list-item {
        width: 100%;
        display: block;
        margin: 0 !important;
        border-bottom: 1px solid;
        padding: .25em 2em .5em
    }

    #egh li.mobile-list-item a {
        text-align: left !important;
        width: 100%;
        font-size: 1.25em;
        height: auto !important;
        padding: 0
    }

    #egh li.mobile-list-item a span {
        font-size: .65em
    }
}

.egh-theme.battle_breakers .accent-bg-color,
.egh-theme.battle_breakers .accent-bg-color-before:before {
    background: #431374
}

.egh-theme.battle_breakers .accent-bg-color-hover:hover {
    background: #48147d
}

.egh-theme.battle_breakers .accent-text-color {
    color: #fff
}

.egh-theme.battle_breakers .accent-text-before-after:after,
.egh-theme.battle_breakers .accent-text-before-after:before,
.egh-theme.battle_breakers .accent-text-color-bg {
    background: #fff
}

.egh-theme.battle_breakers .accent-text-color-hover:hover {
    color: #fff !important
}

.egh-theme.battle_breakers .accent-color {
    color: #431374
}

.egh-theme.battle_breakers .accent-color-hover:hover {
    color: #431374 !important
}

.egh-theme.battle_breakers .accent-text-color-hover-border:hover,
.egh-theme.battle_breakers .accent-text-color-hover-border:hover>.accent-text-color-hover-border {
    border-color: #fff !important
}

.egh-theme.battle_breakers .accent-text-color-hover-border:hover>.accent-text-color-hover {
    color: #fff !important
}

.egh-theme.battle_breakers .accent-color-hover-border:hover,
.egh-theme.battle_breakers .accent-color-hover-border:hover>.accent-color-hover-border {
    border-color: #431374 !important
}

.egh-theme.battle_breakers .accent-color-hover-border:hover>.accent-color-hover {
    color: #431374 !important
}

.egh-theme.battle_breakers .text-color,
.egh-theme.battle_breakers a,
.egh-theme.battle_breakers nav {
    color: #262626
}

.egh-theme.battle_breakers i {
    color: #595959
}

.egh-theme.battle_breakers .text-color-before-after:after,
.egh-theme.battle_breakers .text-color-before-after:before,
.egh-theme.battle_breakers .text-color-bg {
    background-color: #262626
}

.egh-theme.battle_breakers .text-color-border {
    border-color: #262626 !important
}

.egh-theme.battle_breakers .text-color-hover-border:hover {
    border-color: #000 !important
}

.egh-theme.battle_breakers .text-color-nonactive-border {
    border-color: #595959 !important
}

.egh-theme.battle_breakers .text-color-dark-nonactive-border {
    border-color: grey !important
}

.egh-theme.battle_breakers .text-color-border-after:hover:after {
    border-color: #000 !important
}

.egh-theme.battle_breakers .text-color-border-after:after {
    border-color: #262626 !important
}

.egh-theme.battle_breakers .text-color-active {
    color: #000
}

.egh-theme.battle_breakers .text-color-hover:hover,
.egh-theme.battle_breakers .text-color-hover:hover>i,
.egh-theme.battle_breakers i:hover {
    color: #000 !important
}

.egh-theme.battle_breakers .text-color-nonactive {
    color: #595959
}

.egh-theme.battle_breakers .text-color-dark-nonactive {
    color: grey
}

.egh-theme.battle_breakers .bg-color,
.egh-theme.battle_breakers nav,
.egh-theme.battle_breakers ul {
    background-color: #f6f7f9
}

.egh-theme.battle_breakers .rightnav-bg-color {
    background-color: #eaecf1
}

.egh-theme.battle_breakers .icon-bar-toggle,
.egh-theme.battle_breakers .icon-bar-wrapper {
    background: #f0f2f5
}

.egh-theme.battle_breakers .bg-color-before-after:after,
.egh-theme.battle_breakers .bg-color-before-after:before {
    background-color: #f6f7f9
}

.egh-theme.battle_breakers .right-col .rightNav #form.search {
    background-color: #e4e7ed
}

.egh-theme.battle_breakers .grandkid {
    background-color: #f0f2f5
}

.egh-theme.battle_breakers .back-arrow-before-after:after,
.egh-theme.battle_breakers .back-arrow-before-after:before,
.egh-theme.battle_breakers .mobile-heading li a span:before {
    border-color: #262626 !important
}

.egh-theme.battle_breakers .mobile-border-color {
    border-color: #e7e7e7 !important
}

.egh-theme.battle_breakers .mobile-heading,
.egh-theme.battle_breakers .mobile-heading>a {
    border-color: #e7e7e7 !important;
    color: #f6f7f9;
    background-color: #360f5e
}

.egh-theme.battle_breakers .mobile-list-item {
    border-color: #e7e7e7 !important
}

.egh-theme.battle_breakers .icon-bar-toggle,
.egh-theme.battle_breakers .icon-bar>div,
.egh-theme.battle_breakers .mobile-buttons>a {
    border-color: #e2e2e2 !important
}

.egh-theme.battle_breakers .close-btn:hover,
.egh-theme.battle_breakers .search-btn:hover {
    background-color: #d7dce5
}

.egh-theme.epic_games .accent-bg-color,
.egh-theme.epic_games .accent-bg-color-before:before {
    background: #0078f2
}

.egh-theme.epic_games .accent-bg-color-hover:hover {
    background: #007dfc
}

.egh-theme.epic_games .accent-text-color {
    color: #fff
}

.egh-theme.epic_games .accent-text-before-after:after,
.egh-theme.epic_games .accent-text-before-after:before,
.egh-theme.epic_games .accent-text-color-bg {
    background: #fff
}

.egh-theme.epic_games .accent-text-color-hover:hover {
    color: #fff !important
}

.egh-theme.epic_games .accent-color {
    color: #0078f2
}

.egh-theme.epic_games .accent-color-hover:hover {
    color: #0078f2 !important
}

.egh-theme.epic_games .accent-text-color-hover-border:hover,
.egh-theme.epic_games .accent-text-color-hover-border:hover>.accent-text-color-hover-border {
    border-color: #fff !important
}

.egh-theme.epic_games .accent-text-color-hover-border:hover>.accent-text-color-hover {
    color: #fff !important
}

.egh-theme.epic_games .accent-color-hover-border:hover,
.egh-theme.epic_games .accent-color-hover-border:hover>.accent-color-hover-border {
    border-color: #0078f2 !important
}

.egh-theme.epic_games .accent-color-hover-border:hover>.accent-color-hover {
    color: #0078f2 !important
}

.egh-theme.epic_games .text-color,
.egh-theme.epic_games a,
.egh-theme.epic_games nav {
    color: #e7e7e7
}

.egh-theme.epic_games i {
    color: #ccc
}

.egh-theme.epic_games .text-color-before-after:after,
.egh-theme.epic_games .text-color-before-after:before,
.egh-theme.epic_games .text-color-bg {
    background-color: #e7e7e7
}

.egh-theme.epic_games .text-color-border {
    border-color: #e7e7e7 !important
}

.egh-theme.epic_games .text-color-hover-border:hover {
    border-color: #fff !important
}

.egh-theme.epic_games .text-color-nonactive-border {
    border-color: #ccc !important
}

.egh-theme.epic_games .text-color-dark-nonactive-border {
    border-color: #999 !important
}

.egh-theme.epic_games .text-color-border-after:hover:after {
    border-color: #fff !important
}

.egh-theme.epic_games .text-color-border-after:after {
    border-color: #e7e7e7 !important
}

.egh-theme.epic_games .text-color-active {
    color: #fff
}

.egh-theme.epic_games .text-color-hover:hover,
.egh-theme.epic_games .text-color-hover:hover>i,
.egh-theme.epic_games i:hover {
    color: #fff !important
}

.egh-theme.epic_games .text-color-nonactive {
    color: #ccc
}

.egh-theme.epic_games .text-color-dark-nonactive {
    color: #999
}

.egh-theme.epic_games .bg-color,
.egh-theme.epic_games nav,
.egh-theme.epic_games ul {
    background-color: #2a2a2a
}

.egh-theme.epic_games .rightnav-bg-color {
    background-color: #252525
}

.egh-theme.epic_games .icon-bar-toggle,
.egh-theme.epic_games .icon-bar-wrapper {
    background: #2f2f2f
}

.egh-theme.epic_games .bg-color-before-after:after,
.egh-theme.epic_games .bg-color-before-after:before {
    background-color: #2a2a2a
}

.egh-theme.epic_games .right-col .rightNav #form.search {
    background-color: #393939
}

.egh-theme.epic_games .grandkid {
    background-color: #252525
}

.egh-theme.epic_games .back-arrow-before-after:after,
.egh-theme.epic_games .back-arrow-before-after:before,
.egh-theme.epic_games .mobile-heading li a span:before {
    border-color: #e7e7e7 !important
}

.egh-theme.epic_games .mobile-border-color {
    border-color: #333 !important
}

.egh-theme.epic_games .mobile-heading,
.egh-theme.epic_games .mobile-heading>a {
    border-color: #333 !important;
    color: #8e8e8e;
    background-color: #1d1d1d
}

.egh-theme.epic_games .mobile-list-item {
    border-color: #333 !important
}

.egh-theme.epic_games .icon-bar-toggle,
.egh-theme.epic_games .icon-bar>div,
.egh-theme.epic_games .mobile-buttons>a {
    border-color: #464646 !important
}

.egh-theme.epic_games .icon-bar-toggle.t-up {
    background: #000
}

.egh-theme.epic_games .close-btn:hover,
.egh-theme.epic_games .search-btn:hover {
    background-color: #505050
}

.egh-theme.dev_epic_games .accent-bg-color,
.egh-theme.dev_epic_games .accent-bg-color-before:before {
    background: #0078f2
}

.egh-theme.dev_epic_games .accent-bg-color-hover:hover {
    background: #007dfc
}

.egh-theme.dev_epic_games .accent-text-color {
    color: #fff
}

.egh-theme.dev_epic_games .accent-text-before-after:after,
.egh-theme.dev_epic_games .accent-text-before-after:before,
.egh-theme.dev_epic_games .accent-text-color-bg {
    background: #fff
}

.egh-theme.dev_epic_games .accent-text-color-hover:hover {
    color: #fff !important
}

.egh-theme.dev_epic_games .accent-color {
    color: #0078f2
}

.egh-theme.dev_epic_games .accent-color-hover:hover {
    color: #0078f2 !important
}

.egh-theme.dev_epic_games .accent-text-color-hover-border:hover,
.egh-theme.dev_epic_games .accent-text-color-hover-border:hover>.accent-text-color-hover-border {
    border-color: #fff !important
}

.egh-theme.dev_epic_games .accent-text-color-hover-border:hover>.accent-text-color-hover {
    color: #fff !important
}

.egh-theme.dev_epic_games .accent-color-hover-border:hover,
.egh-theme.dev_epic_games .accent-color-hover-border:hover>.accent-color-hover-border {
    border-color: #0078f2 !important
}

.egh-theme.dev_epic_games .accent-color-hover-border:hover>.accent-color-hover {
    color: #0078f2 !important
}

.egh-theme.dev_epic_games .text-color,
.egh-theme.dev_epic_games a,
.egh-theme.dev_epic_games nav {
    color: #e7e7e7
}

.egh-theme.dev_epic_games i {
    color: #ccc
}

.egh-theme.dev_epic_games .text-color-before-after:after,
.egh-theme.dev_epic_games .text-color-before-after:before,
.egh-theme.dev_epic_games .text-color-bg {
    background-color: #e7e7e7
}

.egh-theme.dev_epic_games .text-color-border {
    border-color: #e7e7e7 !important
}

.egh-theme.dev_epic_games .text-color-hover-border:hover {
    border-color: #fff !important
}

.egh-theme.dev_epic_games .text-color-nonactive-border {
    border-color: #ccc !important
}

.egh-theme.dev_epic_games .text-color-dark-nonactive-border {
    border-color: #999 !important
}

.egh-theme.dev_epic_games .text-color-border-after:hover:after {
    border-color: #fff !important
}

.egh-theme.dev_epic_games .text-color-border-after:after {
    border-color: #e7e7e7 !important
}

.egh-theme.dev_epic_games .text-color-active {
    color: #fff
}

.egh-theme.dev_epic_games .text-color-hover:hover,
.egh-theme.dev_epic_games .text-color-hover:hover>i,
.egh-theme.dev_epic_games i:hover {
    color: #fff !important
}

.egh-theme.dev_epic_games .text-color-nonactive {
    color: #ccc
}

.egh-theme.dev_epic_games .text-color-dark-nonactive {
    color: #999
}

.egh-theme.dev_epic_games .bg-color,
.egh-theme.dev_epic_games nav,
.egh-theme.dev_epic_games ul {
    background-color: #2a2a2a
}

.egh-theme.dev_epic_games .rightnav-bg-color {
    background-color: #252525
}

.egh-theme.dev_epic_games .icon-bar-toggle,
.egh-theme.dev_epic_games .icon-bar-wrapper {
    background: #2f2f2f
}

.egh-theme.dev_epic_games .bg-color-before-after:after,
.egh-theme.dev_epic_games .bg-color-before-after:before {
    background-color: #2a2a2a
}

.egh-theme.dev_epic_games .right-col .rightNav #form.search {
    background-color: #393939
}

.egh-theme.dev_epic_games .grandkid {
    background-color: #252525
}

.egh-theme.dev_epic_games .back-arrow-before-after:after,
.egh-theme.dev_epic_games .back-arrow-before-after:before,
.egh-theme.dev_epic_games .mobile-heading li a span:before {
    border-color: #e7e7e7 !important
}

.egh-theme.dev_epic_games .mobile-border-color {
    border-color: #333 !important
}

.egh-theme.dev_epic_games .mobile-heading,
.egh-theme.dev_epic_games .mobile-heading>a {
    border-color: #333 !important;
    color: #8e8e8e;
    background-color: #1d1d1d
}

.egh-theme.dev_epic_games .mobile-list-item {
    border-color: #333 !important
}

.egh-theme.dev_epic_games .icon-bar-toggle,
.egh-theme.dev_epic_games .icon-bar>div,
.egh-theme.dev_epic_games .mobile-buttons>a {
    border-color: #464646 !important
}

.egh-theme.dev_epic_games .icon-bar-toggle.t-up {
    background: #000
}

.egh-theme.dev_epic_games .close-btn:hover,
.egh-theme.dev_epic_games .search-btn:hover {
    background-color: #505050
}

.egh-theme.fortnite .accent-bg-color,
.egh-theme.fortnite .accent-bg-color-before:before {
    background: #ff0
}

.egh-theme.fortnite .accent-bg-color-hover:hover {
    background: #f5f500
}

.egh-theme.fortnite .accent-text-color {
    color: #000
}

.egh-theme.fortnite .accent-text-before-after:after,
.egh-theme.fortnite .accent-text-before-after:before,
.egh-theme.fortnite .accent-text-color-bg {
    background: #000
}

.egh-theme.fortnite .accent-text-color-hover:hover {
    color: #000 !important
}

.egh-theme.fortnite .accent-color {
    color: #ff0
}

.egh-theme.fortnite .accent-color-hover:hover {
    color: #ff0 !important
}

.egh-theme.fortnite .accent-text-color-hover-border:hover,
.egh-theme.fortnite .accent-text-color-hover-border:hover>.accent-text-color-hover-border {
    border-color: #000 !important
}

.egh-theme.fortnite .accent-text-color-hover-border:hover>.accent-text-color-hover {
    color: #000 !important
}

.egh-theme.fortnite .accent-color-hover-border:hover,
.egh-theme.fortnite .accent-color-hover-border:hover>.accent-color-hover-border {
    border-color: #ff0 !important
}

.egh-theme.fortnite .accent-color-hover-border:hover>.accent-color-hover {
    color: #ff0 !important
}

.egh-theme.fortnite .text-color,
.egh-theme.fortnite a,
.egh-theme.fortnite nav {
    color: #e7e7e7
}

.egh-theme.fortnite i {
    color: #ccc
}

.egh-theme.fortnite .text-color-before-after:after,
.egh-theme.fortnite .text-color-before-after:before,
.egh-theme.fortnite .text-color-bg {
    background-color: #e7e7e7
}

.egh-theme.fortnite .text-color-border {
    border-color: #e7e7e7 !important
}

.egh-theme.fortnite .text-color-hover-border:hover {
    border-color: #fff !important
}

.egh-theme.fortnite .text-color-nonactive-border {
    border-color: #ccc !important
}

.egh-theme.fortnite .text-color-dark-nonactive-border {
    border-color: #999 !important
}

.egh-theme.fortnite .text-color-border-after:hover:after {
    border-color: #fff !important
}

.egh-theme.fortnite .text-color-border-after:after {
    border-color: #e7e7e7 !important
}

.egh-theme.fortnite .text-color-active {
    color: #fff
}

.egh-theme.fortnite .text-color-hover:hover,
.egh-theme.fortnite .text-color-hover:hover>i,
.egh-theme.fortnite i:hover {
    color: #fff !important
}

.egh-theme.fortnite .text-color-nonactive {
    color: #ccc
}

.egh-theme.fortnite .text-color-dark-nonactive {
    color: #999
}

.egh-theme.fortnite .bg-color,
.egh-theme.fortnite nav,
.egh-theme.fortnite ul {
    background-color: #2a2a2a
}

.egh-theme.fortnite .rightnav-bg-color {
    background-color: #252525
}

.egh-theme.fortnite .icon-bar-toggle,
.egh-theme.fortnite .icon-bar-wrapper {
    background: #2f2f2f
}

.egh-theme.fortnite .bg-color-before-after:after,
.egh-theme.fortnite .bg-color-before-after:before {
    background-color: #2a2a2a
}

.egh-theme.fortnite .right-col .rightNav #form.search {
    background-color: #393939
}

.egh-theme.fortnite .grandkid {
    background-color: #252525
}

.egh-theme.fortnite .back-arrow-before-after:after,
.egh-theme.fortnite .back-arrow-before-after:before,
.egh-theme.fortnite .mobile-heading li a span:before {
    border-color: #e7e7e7 !important
}

.egh-theme.fortnite .mobile-border-color {
    border-color: #333 !important
}

.egh-theme.fortnite .mobile-heading,
.egh-theme.fortnite .mobile-heading>a {
    border-color: #333 !important;
    color: #8e8e8e;
    background-color: #1d1d1d
}

.egh-theme.fortnite .mobile-list-item {
    border-color: #333 !important
}

.egh-theme.fortnite .icon-bar-toggle,
.egh-theme.fortnite .icon-bar>div,
.egh-theme.fortnite .mobile-buttons>a {
    border-color: #464646 !important
}

.egh-theme.fortnite .icon-bar-toggle.t-up {
    background: #000
}

.egh-theme.fortnite .close-btn:hover,
.egh-theme.fortnite .search-btn:hover {
    background-color: #505050
}

.egh-theme.odin .accent-bg-color,
.egh-theme.odin .accent-bg-color-before:before {
    background: #f2c82d
}

.egh-theme.odin .accent-bg-color-hover:hover {
    background: #f3cb37
}

.egh-theme.odin .accent-text-color {
    color: #000
}

.egh-theme.odin .accent-text-before-after:after,
.egh-theme.odin .accent-text-before-after:before,
.egh-theme.odin .accent-text-color-bg {
    background: #000
}

.egh-theme.odin .accent-text-color-hover:hover {
    color: #000 !important
}

.egh-theme.odin .accent-color {
    color: #f2c82d
}

.egh-theme.odin .accent-color-hover:hover {
    color: #f2c82d !important
}

.egh-theme.odin .accent-text-color-hover-border:hover,
.egh-theme.odin .accent-text-color-hover-border:hover>.accent-text-color-hover-border {
    border-color: #000 !important
}

.egh-theme.odin .accent-text-color-hover-border:hover>.accent-text-color-hover {
    color: #000 !important
}

.egh-theme.odin .accent-color-hover-border:hover,
.egh-theme.odin .accent-color-hover-border:hover>.accent-color-hover-border {
    border-color: #f2c82d !important
}

.egh-theme.odin .accent-color-hover-border:hover>.accent-color-hover {
    color: #f2c82d !important
}

.egh-theme.odin .text-color,
.egh-theme.odin a,
.egh-theme.odin nav {
    color: #e7e7e7
}

.egh-theme.odin i {
    color: #ccc
}

.egh-theme.odin .text-color-before-after:after,
.egh-theme.odin .text-color-before-after:before,
.egh-theme.odin .text-color-bg {
    background-color: #e7e7e7
}

.egh-theme.odin .text-color-border {
    border-color: #e7e7e7 !important
}

.egh-theme.odin .text-color-hover-border:hover {
    border-color: #fff !important
}

.egh-theme.odin .text-color-nonactive-border {
    border-color: #ccc !important
}

.egh-theme.odin .text-color-dark-nonactive-border {
    border-color: #999 !important
}

.egh-theme.odin .text-color-border-after:hover:after {
    border-color: #fff !important
}

.egh-theme.odin .text-color-border-after:after {
    border-color: #e7e7e7 !important
}

.egh-theme.odin .text-color-active {
    color: #fff
}

.egh-theme.odin .text-color-hover:hover,
.egh-theme.odin .text-color-hover:hover>i,
.egh-theme.odin i:hover {
    color: #fff !important
}

.egh-theme.odin .text-color-nonactive {
    color: #ccc
}

.egh-theme.odin .text-color-dark-nonactive {
    color: #999
}

.egh-theme.odin .bg-color,
.egh-theme.odin nav,
.egh-theme.odin ul {
    background-color: #1b1c1a
}

.egh-theme.odin .rightnav-bg-color {
    background-color: #252525
}

.egh-theme.odin .icon-bar-toggle,
.egh-theme.odin .icon-bar-wrapper {
    background: #2f2f2f
}

.egh-theme.odin .bg-color-before-after:after,
.egh-theme.odin .bg-color-before-after:before {
    background-color: #1b1c1a
}

.egh-theme.odin .right-col .rightNav #form.search {
    background-color: #393939
}

.egh-theme.odin .grandkid {
    background-color: #161715
}

.egh-theme.odin .back-arrow-before-after:after,
.egh-theme.odin .back-arrow-before-after:before,
.egh-theme.odin .mobile-heading li a span:before {
    border-color: #e7e7e7 !important
}

.egh-theme.odin .mobile-border-color {
    border-color: #333 !important
}

.egh-theme.odin .mobile-heading,
.egh-theme.odin .mobile-heading>a {
    border-color: #333 !important;
    color: #8e8e8e;
    background-color: #1d1d1d
}

.egh-theme.odin .mobile-list-item {
    border-color: #333 !important
}

.egh-theme.odin .icon-bar-toggle,
.egh-theme.odin .icon-bar>div,
.egh-theme.odin .mobile-buttons>a {
    border-color: #464646 !important
}

.egh-theme.odin .icon-bar-toggle.t-up {
    background: #000
}

.egh-theme.odin .close-btn:hover,
.egh-theme.odin .search-btn:hover {
    background-color: #505050
}

.egh-theme.shadow_complex .accent-bg-color,
.egh-theme.shadow_complex .accent-bg-color-before:before {
    background: #c62626
}

.egh-theme.shadow_complex .accent-bg-color-hover:hover {
    background: #cf2828
}

.egh-theme.shadow_complex .accent-text-color {
    color: #fff
}

.egh-theme.shadow_complex .accent-text-before-after:after,
.egh-theme.shadow_complex .accent-text-before-after:before,
.egh-theme.shadow_complex .accent-text-color-bg {
    background: #fff
}

.egh-theme.shadow_complex .accent-text-color-hover:hover {
    color: #fff !important
}

.egh-theme.shadow_complex .accent-color {
    color: #c62626
}

.egh-theme.shadow_complex .accent-color-hover:hover {
    color: #c62626 !important
}

.egh-theme.shadow_complex .accent-text-color-hover-border:hover,
.egh-theme.shadow_complex .accent-text-color-hover-border:hover>.accent-text-color-hover-border {
    border-color: #fff !important
}

.egh-theme.shadow_complex .accent-text-color-hover-border:hover>.accent-text-color-hover {
    color: #fff !important
}

.egh-theme.shadow_complex .accent-color-hover-border:hover,
.egh-theme.shadow_complex .accent-color-hover-border:hover>.accent-color-hover-border {
    border-color: #c62626 !important
}

.egh-theme.shadow_complex .accent-color-hover-border:hover>.accent-color-hover {
    color: #c62626 !important
}

.egh-theme.shadow_complex .text-color,
.egh-theme.shadow_complex a,
.egh-theme.shadow_complex nav {
    color: #e7e7e7
}

.egh-theme.shadow_complex i {
    color: #ccc
}

.egh-theme.shadow_complex .text-color-before-after:after,
.egh-theme.shadow_complex .text-color-before-after:before,
.egh-theme.shadow_complex .text-color-bg {
    background-color: #e7e7e7
}

.egh-theme.shadow_complex .text-color-border {
    border-color: #e7e7e7 !important
}

.egh-theme.shadow_complex .text-color-hover-border:hover {
    border-color: #fff !important
}

.egh-theme.shadow_complex .text-color-nonactive-border {
    border-color: #ccc !important
}

.egh-theme.shadow_complex .text-color-dark-nonactive-border {
    border-color: #999 !important
}

.egh-theme.shadow_complex .text-color-border-after:hover:after {
    border-color: #fff !important
}

.egh-theme.shadow_complex .text-color-border-after:after {
    border-color: #e7e7e7 !important
}

.egh-theme.shadow_complex .text-color-active {
    color: #fff
}

.egh-theme.shadow_complex .text-color-hover:hover,
.egh-theme.shadow_complex .text-color-hover:hover>i,
.egh-theme.shadow_complex i:hover {
    color: #fff !important
}

.egh-theme.shadow_complex .text-color-nonactive {
    color: #ccc
}

.egh-theme.shadow_complex .text-color-dark-nonactive {
    color: #999
}

.egh-theme.shadow_complex .bg-color,
.egh-theme.shadow_complex nav,
.egh-theme.shadow_complex ul {
    background-color: #2a2a2a
}

.egh-theme.shadow_complex .rightnav-bg-color {
    background-color: #252525
}

.egh-theme.shadow_complex .icon-bar-toggle,
.egh-theme.shadow_complex .icon-bar-wrapper {
    background: #2f2f2f
}

.egh-theme.shadow_complex .bg-color-before-after:after,
.egh-theme.shadow_complex .bg-color-before-after:before {
    background-color: #2a2a2a
}

.egh-theme.shadow_complex .right-col .rightNav #form.search {
    background-color: #393939
}

.egh-theme.shadow_complex .grandkid {
    background-color: #252525
}

.egh-theme.shadow_complex .back-arrow-before-after:after,
.egh-theme.shadow_complex .back-arrow-before-after:before,
.egh-theme.shadow_complex .mobile-heading li a span:before {
    border-color: #e7e7e7 !important
}

.egh-theme.shadow_complex .mobile-border-color {
    border-color: #333 !important
}

.egh-theme.shadow_complex .mobile-heading,
.egh-theme.shadow_complex .mobile-heading>a {
    border-color: #333 !important;
    color: #8e8e8e;
    background-color: #1d1d1d
}

.egh-theme.shadow_complex .mobile-list-item {
    border-color: #333 !important
}

.egh-theme.shadow_complex .icon-bar-toggle,
.egh-theme.shadow_complex .icon-bar>div,
.egh-theme.shadow_complex .mobile-buttons>a {
    border-color: #464646 !important
}

.egh-theme.shadow_complex .icon-bar-toggle.t-up {
    background: #000
}

.egh-theme.shadow_complex .close-btn:hover,
.egh-theme.shadow_complex .search-btn:hover {
    background-color: #505050
}

.egh-theme.spy_jinx .accent-bg-color,
.egh-theme.spy_jinx .accent-bg-color-before:before {
    background: #f9bc0d
}

.egh-theme.spy_jinx .accent-bg-color-hover:hover {
    background: #eba700
}

.egh-theme.spy_jinx .accent-text-color {
    color: #fff
}

.egh-theme.spy_jinx .accent-text-before-after:after,
.egh-theme.spy_jinx .accent-text-before-after:before,
.egh-theme.spy_jinx .accent-text-color-bg {
    background: #fff
}

.egh-theme.spy_jinx .accent-text-color-hover:hover {
    color: #fff !important
}

.egh-theme.spy_jinx .accent-color {
    color: #f9bc0d
}

.egh-theme.spy_jinx .accent-color-hover:hover {
    color: #f9bc0d !important
}

.egh-theme.spy_jinx .accent-text-color-hover-border:hover,
.egh-theme.spy_jinx .accent-text-color-hover-border:hover>.accent-text-color-hover-border {
    border-color: #fff !important
}

.egh-theme.spy_jinx .accent-text-color-hover-border:hover>.accent-text-color-hover {
    color: #fff !important
}

.egh-theme.spy_jinx .accent-color-hover-border:hover,
.egh-theme.spy_jinx .accent-color-hover-border:hover>.accent-color-hover-border {
    border-color: #f9bc0d !important
}

.egh-theme.spy_jinx .accent-color-hover-border:hover>.accent-color-hover {
    color: #f9bc0d !important
}

.egh-theme.spy_jinx .text-color,
.egh-theme.spy_jinx a,
.egh-theme.spy_jinx i,
.egh-theme.spy_jinx nav {
    color: #018ac4
}

.egh-theme.spy_jinx .text-color-before-after:after,
.egh-theme.spy_jinx .text-color-before-after:before,
.egh-theme.spy_jinx .text-color-bg {
    background-color: #018ac4
}

.egh-theme.spy_jinx .text-color-border {
    border-color: #018ac4 !important
}

.egh-theme.spy_jinx .text-color-hover-border:hover {
    border-color: #999 !important
}

.egh-theme.spy_jinx .text-color-dark-nonactive-border,
.egh-theme.spy_jinx .text-color-nonactive-border {
    border-color: #018ac4 !important
}

.egh-theme.spy_jinx .text-color-border-after:hover:after {
    border-color: #999 !important
}

.egh-theme.spy_jinx .text-color-border-after:after {
    border-color: #018ac4 !important
}

.egh-theme.spy_jinx .text-color-active {
    color: #999
}

.egh-theme.spy_jinx .text-color-hover:hover,
.egh-theme.spy_jinx .text-color-hover:hover>i,
.egh-theme.spy_jinx i:hover {
    color: #999 !important
}

.egh-theme.spy_jinx .text-color-dark-nonactive,
.egh-theme.spy_jinx .text-color-nonactive {
    color: #018ac4
}

.egh-theme.spy_jinx .bg-color,
.egh-theme.spy_jinx nav,
.egh-theme.spy_jinx ul {
    background-color: #fff
}

.egh-theme.spy_jinx .rightnav-bg-color {
    background-color: #e7e7e7
}

.egh-theme.spy_jinx .icon-bar-toggle,
.egh-theme.spy_jinx .icon-bar-wrapper {
    background: #fafafa
}

.egh-theme.spy_jinx .bg-color-before-after:after,
.egh-theme.spy_jinx .bg-color-before-after:before {
    background-color: #fff
}

.egh-theme.spy_jinx .right-col .rightNav #form.search {
    background-color: #f0f0f0
}

.egh-theme.spy_jinx .grandkid {
    background-color: #fafafa
}

.egh-theme.spy_jinx .back-arrow-before-after:after,
.egh-theme.spy_jinx .back-arrow-before-after:before,
.egh-theme.spy_jinx .mobile-heading li a span:before {
    border-color: #018ac4 !important
}

.egh-theme.spy_jinx .mobile-border-color {
    border-color: #e7e7e7 !important
}

.egh-theme.spy_jinx .mobile-heading,
.egh-theme.spy_jinx .mobile-heading>a {
    border-color: #e7e7e7 !important;
    color: #fff;
    background-color: #009bdc
}

.egh-theme.spy_jinx .mobile-list-item {
    border-color: #e7e7e7 !important
}

.egh-theme.spy_jinx .icon-bar-toggle,
.egh-theme.spy_jinx .icon-bar>div,
.egh-theme.spy_jinx .mobile-buttons>a {
    border-color: #e2e2e2 !important
}

.egh-theme.spy_jinx .close-btn:hover,
.egh-theme.spy_jinx .search-btn:hover {
    background-color: #e6e6e6
}

.egh-theme.unreal_engine .accent-bg-color,
.egh-theme.unreal_engine .accent-bg-color-before:before {
    background: #0aaff1
}

.egh-theme.unreal_engine .accent-bg-color-hover:hover {
    background: #10b4f5
}

.egh-theme.unreal_engine .accent-text-color {
    color: #fff
}

.egh-theme.unreal_engine .accent-text-before-after:after,
.egh-theme.unreal_engine .accent-text-before-after:before,
.egh-theme.unreal_engine .accent-text-color-bg {
    background: #fff
}

.egh-theme.unreal_engine .accent-text-color-hover:hover {
    color: #fff !important
}

.egh-theme.unreal_engine .accent-color {
    color: #0aaff1
}

.egh-theme.unreal_engine .accent-color-hover:hover {
    color: #0aaff1 !important
}

.egh-theme.unreal_engine .accent-text-color-hover-border:hover,
.egh-theme.unreal_engine .accent-text-color-hover-border:hover>.accent-text-color-hover-border {
    border-color: #fff !important
}

.egh-theme.unreal_engine .accent-text-color-hover-border:hover>.accent-text-color-hover {
    color: #fff !important
}

.egh-theme.unreal_engine .accent-color-hover-border:hover,
.egh-theme.unreal_engine .accent-color-hover-border:hover>.accent-color-hover-border {
    border-color: #0aaff1 !important
}

.egh-theme.unreal_engine .accent-color-hover-border:hover>.accent-color-hover {
    color: #0aaff1 !important
}

.egh-theme.unreal_engine .text-color,
.egh-theme.unreal_engine a,
.egh-theme.unreal_engine nav {
    color: #e7e7e7
}

.egh-theme.unreal_engine i {
    color: #ccc
}

.egh-theme.unreal_engine .text-color-before-after:after,
.egh-theme.unreal_engine .text-color-before-after:before,
.egh-theme.unreal_engine .text-color-bg {
    background-color: #e7e7e7
}

.egh-theme.unreal_engine .text-color-border {
    border-color: #e7e7e7 !important
}

.egh-theme.unreal_engine .text-color-hover-border:hover {
    border-color: #fff !important
}

.egh-theme.unreal_engine .text-color-nonactive-border {
    border-color: #ccc !important
}

.egh-theme.unreal_engine .text-color-dark-nonactive-border {
    border-color: #999 !important
}

.egh-theme.unreal_engine .text-color-border-after:hover:after {
    border-color: #fff !important
}

.egh-theme.unreal_engine .text-color-border-after:after {
    border-color: #e7e7e7 !important
}

.egh-theme.unreal_engine .text-color-active {
    color: #fff
}

.egh-theme.unreal_engine .text-color-hover:hover,
.egh-theme.unreal_engine .text-color-hover:hover>i,
.egh-theme.unreal_engine i:hover {
    color: #fff !important
}

.egh-theme.unreal_engine .text-color-nonactive {
    color: #ccc
}

.egh-theme.unreal_engine .text-color-dark-nonactive {
    color: #999
}

.egh-theme.unreal_engine .bg-color,
.egh-theme.unreal_engine nav,
.egh-theme.unreal_engine ul {
    background-color: #2a2a2a
}

.egh-theme.unreal_engine .rightnav-bg-color {
    background-color: #252525
}

.egh-theme.unreal_engine .icon-bar-toggle,
.egh-theme.unreal_engine .icon-bar-wrapper {
    background: #2f2f2f
}

.egh-theme.unreal_engine .bg-color-before-after:after,
.egh-theme.unreal_engine .bg-color-before-after:before {
    background-color: #2a2a2a
}

.egh-theme.unreal_engine .right-col .rightNav #form.search {
    background-color: #393939
}

.egh-theme.unreal_engine .grandkid {
    background-color: #252525
}

.egh-theme.unreal_engine .back-arrow-before-after:after,
.egh-theme.unreal_engine .back-arrow-before-after:before,
.egh-theme.unreal_engine .mobile-heading li a span:before {
    border-color: #e7e7e7 !important
}

.egh-theme.unreal_engine .mobile-border-color {
    border-color: #333 !important
}

.egh-theme.unreal_engine .mobile-heading,
.egh-theme.unreal_engine .mobile-heading>a {
    border-color: #333 !important;
    color: #8e8e8e;
    background-color: #1d1d1d
}

.egh-theme.unreal_engine .mobile-list-item {
    border-color: #333 !important
}

.egh-theme.unreal_engine .icon-bar-toggle,
.egh-theme.unreal_engine .icon-bar>div,
.egh-theme.unreal_engine .mobile-buttons>a {
    border-color: #464646 !important
}

.egh-theme.unreal_engine .icon-bar-toggle.t-up {
    background: #000
}

.egh-theme.unreal_engine .close-btn:hover,
.egh-theme.unreal_engine .search-btn:hover {
    background-color: #505050
}

.egh-theme.unreal_tournament .accent-bg-color,
.egh-theme.unreal_tournament .accent-bg-color-before:before {
    background: #8b8b8b
}

.egh-theme.unreal_tournament .accent-bg-color-hover:hover {
    background: #909090
}

.egh-theme.unreal_tournament .accent-text-color {
    color: #fff
}

.egh-theme.unreal_tournament .accent-text-before-after:after,
.egh-theme.unreal_tournament .accent-text-before-after:before,
.egh-theme.unreal_tournament .accent-text-color-bg {
    background: #fff
}

.egh-theme.unreal_tournament .accent-text-color-hover:hover {
    color: #fff !important
}

.egh-theme.unreal_tournament .accent-color {
    color: #8b8b8b
}

.egh-theme.unreal_tournament .accent-color-hover:hover {
    color: #8b8b8b !important
}

.egh-theme.unreal_tournament .accent-text-color-hover-border:hover,
.egh-theme.unreal_tournament .accent-text-color-hover-border:hover>.accent-text-color-hover-border {
    border-color: #fff !important
}

.egh-theme.unreal_tournament .accent-text-color-hover-border:hover>.accent-text-color-hover {
    color: #fff !important
}

.egh-theme.unreal_tournament .accent-color-hover-border:hover,
.egh-theme.unreal_tournament .accent-color-hover-border:hover>.accent-color-hover-border {
    border-color: #8b8b8b !important
}

.egh-theme.unreal_tournament .accent-color-hover-border:hover>.accent-color-hover {
    color: #8b8b8b !important
}

.egh-theme.unreal_tournament .text-color,
.egh-theme.unreal_tournament a,
.egh-theme.unreal_tournament nav {
    color: #e7e7e7
}

.egh-theme.unreal_tournament i {
    color: #ccc
}

.egh-theme.unreal_tournament .text-color-before-after:after,
.egh-theme.unreal_tournament .text-color-before-after:before,
.egh-theme.unreal_tournament .text-color-bg {
    background-color: #e7e7e7
}

.egh-theme.unreal_tournament .text-color-border {
    border-color: #e7e7e7 !important
}

.egh-theme.unreal_tournament .text-color-hover-border:hover {
    border-color: #fff !important
}

.egh-theme.unreal_tournament .text-color-nonactive-border {
    border-color: #ccc !important
}

.egh-theme.unreal_tournament .text-color-dark-nonactive-border {
    border-color: #999 !important
}

.egh-theme.unreal_tournament .text-color-border-after:hover:after {
    border-color: #fff !important
}

.egh-theme.unreal_tournament .text-color-border-after:after {
    border-color: #e7e7e7 !important
}

.egh-theme.unreal_tournament .text-color-active {
    color: #fff
}

.egh-theme.unreal_tournament .text-color-hover:hover,
.egh-theme.unreal_tournament .text-color-hover:hover>i,
.egh-theme.unreal_tournament i:hover {
    color: #fff !important
}

.egh-theme.unreal_tournament .text-color-nonactive {
    color: #ccc
}

.egh-theme.unreal_tournament .text-color-dark-nonactive {
    color: #999
}

.egh-theme.unreal_tournament .bg-color,
.egh-theme.unreal_tournament nav,
.egh-theme.unreal_tournament ul {
    background-color: #2a2a2a
}

.egh-theme.unreal_tournament .rightnav-bg-color {
    background-color: #252525
}

.egh-theme.unreal_tournament .icon-bar-toggle,
.egh-theme.unreal_tournament .icon-bar-wrapper {
    background: #2f2f2f
}

.egh-theme.unreal_tournament .bg-color-before-after:after,
.egh-theme.unreal_tournament .bg-color-before-after:before {
    background-color: #2a2a2a
}

.egh-theme.unreal_tournament .right-col .rightNav #form.search {
    background-color: #393939
}

.egh-theme.unreal_tournament .grandkid {
    background-color: #252525
}

.egh-theme.unreal_tournament .back-arrow-before-after:after,
.egh-theme.unreal_tournament .back-arrow-before-after:before,
.egh-theme.unreal_tournament .mobile-heading li a span:before {
    border-color: #e7e7e7 !important
}

.egh-theme.unreal_tournament .mobile-border-color {
    border-color: #333 !important
}

.egh-theme.unreal_tournament .mobile-heading,
.egh-theme.unreal_tournament .mobile-heading>a {
    border-color: #333 !important;
    color: #8e8e8e;
    background-color: #1d1d1d
}

.egh-theme.unreal_tournament .mobile-list-item {
    border-color: #333 !important
}

.egh-theme.unreal_tournament .icon-bar-toggle,
.egh-theme.unreal_tournament .icon-bar>div,
.egh-theme.unreal_tournament .mobile-buttons>a {
    border-color: #464646 !important
}

.egh-theme.unreal_tournament .icon-bar-toggle.t-up {
    background: #000
}

.egh-theme.unreal_tournament .close-btn:hover,
.egh-theme.unreal_tournament .search-btn:hover {
    background-color: #505050
}

#egh.fortnite .shieldLogo {
    background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGQAAAB0CAMAAABE6mf9AAAB7FBMVEVMaXH////////n5+dwcHD///////////97e3v////////////////8/Pz+/v7///////+xsbH////////+/v7+/v7+/v729vbS0tLOzs7e3t6wsLD///8YGBjPz8/9/f3////7+/v////////8/Pzf39/4+Phubm7+/v7///85OTmSkpLLy8v////+/v7////Z2dn////6+vr39/fU1NT+/v6enp6lpaX9/f3////+/v719fX39/f8/Pz////////AwMD9/f3////9/f38/Pzb29v4+Pj39/f///////+3t7f8/Pze3t77+/uTk5P8/Pz4+Pjx8fH+/v7c3Nz5+fni4uL6+vr////5+fn///+qqqr09PT9/f3+/v7e3t7////8/Pz6+vr9/f3////7+/vn5+f6+vr+/v65ubn29vbMzMyhoaHb29vr6+vExMS2trb8/Pz7+/v7+/u2tra7u7vm5ub+/v6enp77+/v////////5+fn7+/v5+fmpqana2trZ2dnOzs76+vrLy8vl5eXW1tbJycnS0tL5+fn7+/vn5+f19fW9vb3Hx8f5+fn4+PjNzc3+/v7AwMDZ2dm1tbX5+fm2trb29vbe3t7p6em9vb3y8vLKysrT09Pc3Nz09PTh4eHIyMjm5ub///+stlOlAAAAo3RSTlMA9vsEAf3l/gL5UvDtEgnz7wP0wqWEijAcGiUJgAQUJNzOq+jrKOQIG64JUlTsmuKN3+AZDdkGFpbV4ToQIVC7Cg3SY3AgHgfEsh4VZcgOlAondSO7LCqo17YwNY6gj2hLRX/N0i/mWpnvElQ6Qj4+VnzpaBJP5UTCgcqqvIs6Fh5krSyESEZZ3dp3tzR68qOAh1CHS4VBS0pacG8hhHZdoqdl1QdEjAAACP1JREFUeF7tmvtf08gaxpNJ0iEkJb0BKEhDs0B7zmlrLRQoLZS0tmAFaFlABeQu53CABQQFkEXA+3W97eqq657tP3pmUjSUSitCPZ+zy/NTMszkyzvvO88kAwRBRUfqZTKRG5Gyo8lNEZT/lawjYY4gkNQ1FJoJd6ETJHIp4HQQIzJI5FYMRzh0iZyLaGC/AYSF3wCSSPyJIMeQYwjg+N0SALY49Z4jmR3jY5WOH50VsrxmRzwJs0CA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) 50% no-repeat;
    background-size: 30px auto
}

#egh.fortnite .accent-bg-color,
#egh.fortnite .accent-bg-color-before:before {
    background: #ff0
}

#egh.fortnite .accent-bg-color-hover:hover {
    background: #f5f500
}

#egh.fortnite .accent-text-color {
    color: #000
}

#egh.fortnite .accent-text-before-after:after,
#egh.fortnite .accent-text-before-after:before,
#egh.fortnite .accent-text-color-bg {
    background: #000
}

#egh.fortnite .accent-text-color-hover:hover {
    color: #000 !important
}

#egh.fortnite .accent-color {
    color: #ff0
}

#egh.fortnite .accent-color-hover:hover {
    color: #ff0 !important
}

#egh.fortnite .accent-text-color-hover-border:hover,
#egh.fortnite .accent-text-color-hover-border:hover>.accent-text-color-hover-border {
    border-color: #000 !important
}

#egh.fortnite .accent-text-color-hover-border:hover>.accent-text-color-hover {
    color: #000 !important
}

#egh.fortnite .accent-color-hover-border:hover,
#egh.fortnite .accent-color-hover-border:hover>.accent-color-hover-border {
    border-color: #ff0 !important
}

#egh.fortnite .accent-color-hover-border:hover>.accent-color-hover {
    color: #ff0 !important
}

#egh.fortnite .text-color,
#egh.fortnite a,
#egh.fortnite nav {
    color: #e7e7e7
}

#egh.fortnite i {
    color: #ccc
}

#egh.fortnite .text-color-before-after:after,
#egh.fortnite .text-color-before-after:before,
#egh.fortnite .text-color-bg {
    background-color: #e7e7e7
}

#egh.fortnite .text-color-border {
    border-color: #e7e7e7 !important
}

#egh.fortnite .text-color-hover-border:hover {
    border-color: #fff !important
}

#egh.fortnite .text-color-nonactive-border {
    border-color: #ccc !important
}

#egh.fortnite .text-color-dark-nonactive-border {
    border-color: #999 !important
}

#egh.fortnite .text-color-border-after:hover:after {
    border-color: #fff !important
}

#egh.fortnite .text-color-border-after:after {
    border-color: #e7e7e7 !important
}

#egh.fortnite .text-color-active {
    color: #fff
}

#egh.fortnite .text-color-hover:hover,
#egh.fortnite .text-color-hover:hover>i,
#egh.fortnite i:hover {
    color: #fff !important
}

#egh.fortnite .text-color-nonactive {
    color: #ccc
}

#egh.fortnite .text-color-dark-nonactive {
    color: #999
}

#egh.fortnite .back-arrow-before-after:after,
#egh.fortnite .back-arrow-before-after:before,
#egh.fortnite .mobile-heading li a span:before {
    border-color: #e7e7e7 !important
}

#egh.fortnite .mobile-border-color {
    border-color: #333 !important
}

#egh.fortnite .mobile-heading,
#egh.fortnite .mobile-heading>a {
    border-color: #333 !important;
    color: #8e8e8e;
    background-color: #1d1d1d
}

#egh.fortnite .mobile-list-item {
    border-color: #333 !important
}

#egh.fortnite .icon-bar-toggle,
#egh.fortnite .icon-bar>div,
#egh.fortnite .mobile-buttons>a {
    border-color: #464646 !important
}

#egh.fortnite .icon-bar-toggle.t-up {
    background: #000
}

#egh.fortnite .close-btn:hover,
#egh.fortnite .search-btn:hover {
    background-color: #505050
}

#egh.fortnite .bg-color,
#egh.fortnite nav,
#egh.fortnite ul {
    background-color: #2a2a2a
}

#egh.fortnite .rightnav-bg-color {
    background-color: #252525
}

#egh.fortnite .icon-bar-toggle,
#egh.fortnite .icon-bar-wrapper {
    background: #2f2f2f
}

#egh.fortnite .bg-color-before-after:after,
#egh.fortnite .bg-color-before-after:before {
    background-color: #2a2a2a
}

#egh.fortnite .right-col .rightNav #form.search {
    background-color: #393939
}

#egh.fortnite .grandkid {
    background-color: #252525
}

#egh.fortnite .lines.accent-text-color,
#egh.fortnite .lines.accent-text-color:after,
#egh.fortnite .lines.accent-text-color:before {
    background-color: #000
}

#egh.fortnite .propLogo {
    background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAASwAAABgCAMAAACQTr/kAAAAllBMVEVMaXH///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////9QwCw4AAAAMXRSTlMAJNvv5QlSrfcbEYAB/voZDgXW9ekoH/LttBUHC+AzV0qhdMWoLV9ql8x7QodPOo+8n4r4ZAAACndJREFUeF7s1dsKgkAQgOFRHGunqXWzrMzItFAzhd7/5YI2oA1YBG8C97vbw9XPwIDjOI7jOACMUtilCjRH9fXMrpYwXawQIyLF7xN2fmzXJNMMJIVIvG3fnat7sVU6Vhg8reYHMYVA+BWo7c7F4nGZHcq1fwqCzX6d47BY8VXCn2Bm0JgSz5BkDCMw5eEnUOPrQPtdPF8tdYMgHBhrV6fmjGakV4KkTDGYWL/9kkRofmVFlKFxacXHKBXeDUGLqsY3lC3CCC927nQ9VV0NADDBoABJkBldMombqija+7+5I7UY6xcqB2ofzjr7+9lGAq8ZB1HS3Q0IEnTHCg39/hFRVRjZrI7MKCpf/9pV6uvNTBCbw34am/dfvuWt98X0GCPka+ZS1+eKAuTvvh7NK98OM/vskQbLhY/TL4DCIKz9DcsyS+Ms44t/HUGI5cU6Xt5zmZvQEUUYYjsrEOdSUjvEGEeynS82W8NYJ8fSQ6guhPdFjii6Vn89MztyJw7Fb/PPjycYPo61BCV6Tn4XCxerzxufVyc7ZPSdB1Vd+xDf3ZE2c9quQwN8Tnzr8e4oUy/soVvDyfbiUggNXuTmq9KY7SIcOtdcnZnf9OECLBMMgrJk3qnvs4ZhwYREK/IJhQZhXpjkWyxOG21jhXyTLVXrQngrclmCMuywu//L5VXbKiN4l8h2HgLvdSBzCf0Sy7px9RGq+75jpf8U1rXbJOggM2ECJhuIiLGg7CKdk6fZNkUO7/95uN7kcO1tiCcLsGRBewtkptNkbxjGaTP7GBrUfZ+89X8IS/bIh9UJ05YUDJ98ArDEAk5+nJO2bOGzPmKxXXzNCXXE0spaZnsnc4nw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);
    width: 100px;
    margin: 0 40px 0 20px;
    height: 100%
}

@media only screen and (max-width:767px) {
    #egh.fortnite .propLogo {
        height: 32px;
        margin-top: 10px
    }
}

@media only screen and (min-width:768px) and (max-width:1199px) {
    #egh.fortnite .propLogo {
        margin: 0 10px 0 5px
    }
}

#egh.fortnite .cta span {
    font-weight: 500
}

@font-face {
    font-family: OpenSans;
    font-weight: 400;
    font-style: normal;
    font-display: auto;
    src: url(83efe33660ab6a7fe428c8078d47485f.html);
    src: url(83efe33660ab6a7fe428c8078d47485fd41d.html?#iefix) format("embedded-opentype"), url(55b8ce1f9a32bb0f83f14813eac0b7ca.html) format("woff"), url(c7571df954bd2b7ffcd78628a24ff2ed.html) format("truetype"), url(bdcfdd6f83b4fd26b9b75e61dd01c109.html#open_sansregular) format("svg")
}

[class*=" eg-footer-icon-"],
[class^=eg-footer-icon-] {
    font-family: eg-footer-icomoon !important;
    font-style: normal;
    font-weight: 400;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    letter-spacing: 0;
    -webkit-font-feature-settings: "liga";
    -ms-font-feature-settings: "liga"1;
    font-feature-settings: "liga", normal, "dlig", normal, "dlig";
    -webkit-font-variant-ligatures: discretionary-ligatures;
    font-variant-ligatures: discretionary-ligatures;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale
}

.eg-footer-icon-android:before {
    content: "\E913"
}

.eg-footer-icon-iOS:before {
    content: "\E914"
}

.eg-footer-icon-switch:before {
    content: "\E915"
}

.eg-footer-icon-mac-logo:before {
    content: "\E90D"
}

.eg-footer-icon-xbox-type:before {
    content: "\E90A"
}

.eg-footer-icon-xbox-logo:before {
    content: "\E90B"
}

.eg-footer-icon-snapchat:before {
    content: "\E900"
}

.eg-footer-icon-carrot:before {
    content: "\E901"
}

.eg-footer-icon-sony:before {
    content: "\E902"
}

.eg-footer-icon-badRobot:before {
    content: "\E903"
}

.eg-footer-icon-chair:before {
    content: "\E904"
}

.eg-footer-icon-pc:before,
.eg-footer-icon-pcGame:before {
    content: "\E905"
}

.eg-footer-icon-ps:before {
    content: "\E906"
}

.eg-footer-icon-ps4:before {
    content: "\E907"
}

.eg-footer-icon-ue:before {
    content: "\E912"
}

.eg-footer-icon-oculus:before {
    content: "\E911"
}

.eg-footer-icon-twitch:before {
    content: "\E908"
}

.eg-footer-icon-youtube:before {
    content: "\E90C"
}

.eg-footer-icon-google-plus:before {
    content: "\E910"
}

.eg-footer-icon-facebook:before {
    content: "\E918"
}

.eg-footer-icon-vk:before {
    content: "\EA98"
}

.eg-footer-icon-instagram:before {
    content: "\E91B"
}

.eg-footer-icon-twitter:before {
    content: "\E91C"
}

.eg-footer-icon-eg:before {
    content: "\E909"
}

.eg-footer-icon-rss:before {
    content: "\EA9B"
}

.eg-footer-icon-weibo:before {
    content: "\EA9A"
}

.eg-footer-icon-wechat:before {
    content: "\F1D7"
}

.eg-footer-icon-discord:before {
    content: "\E90E"
}

.eg-footer-icon-naver-cafe:before {
    content: "\E90F"
}

.eg-footer-icon-telegram:before {
    content: "\E916"
}

body.ar .egf [class*=col-],
body.ar .egf h3,
body.ar .egf h5,
body.ar .egf i {
    float: right
}

body.ar .egf .footer-cta-btn,
body.ar .egf .tags,
body.ar .egf .up-button,
body.ar .egf ul.logos {
    float: left
}

body.ar .egf ul.footerLinks,
body.ar .egf ul.links,
body.ar .egf ul.social {
    float: right
}

body.ar .egf .copyright p,
body.ar .egf ul.footerLinks li {
    text-align: right
}

@media only screen and (max-width:767px) {
    body.ar .egf .tags {
        float: none
    }
}

@media only screen and (max-width:991px) {
    body.ar .egf ul.links {
        float: none
    }

    body.ar .egf ul.footerLinks.first-column {
        padding-left: 1em
    }
}

body.ar .egf .three .footerLinks.first-column,
body.ar .egf .three .footerLinks.second-column,
body.ar .egf .three .footerLinks.third-column {
    float: right
}

body.ar .egf .three .footerLinks.second-column {
    padding-left: 1em
}

body.ar .egf .footerLink-wrapper {
    float: right
}

body.ar .egf .footerLink-wrapper .footerLinks {
    padding-right: 0;
    padding-left: 2.6em
}

.egf {
    /*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
    background: #2a2a2a;
    border-top: 1px solid #ccc
}

.egf html {
    font-family: sans-serif;
    -ms-text-size-adjust: 100%;
    -webkit-text-size-adjust: 100%
}

.egf body {
    margin: 0
}

.egf article,
.egf aside,
.egf details,
.egf figcaption,
.egf figure,
.egf footer,
.egf header,
.egf hgroup,
.egf main,
.egf menu,
.egf nav,
.egf section,
.egf summary {
    display: block
}

.egf audio,
.egf canvas,
.egf progress,
.egf video {
    display: inline-block;
    vertical-align: baseline
}

.egf audio:not([controls]) {
    display: none;
    height: 0
}

.egf [hidden],
.egf template {
    display: none
}

.egf a {
    background-color: transparent
}

.egf a:active,
.egf a:hover {
    outline: 0
}

.egf abbr[title] {
    border-bottom: none;
    text-decoration: underline;
    -webkit-text-decoration: underline dotted;
    text-decoration: underline dotted
}

.egf b,
.egf strong {
    font-weight: 700
}

.egf dfn {
    font-style: italic
}

.egf h1 {
    font-size: 2em;
    margin: .67em 0
}

.egf mark {
    background: #ff0;
    color: #000
}

.egf small {
    font-size: 80%
}

.egf sub,
.egf sup {
    font-size: 75%;
    line-height: 0;
    position: relative;
    vertical-align: baseline
}

.egf sup {
    top: -.5em
}

.egf sub {
    bottom: -.25em
}

.egf img {
    border: 0
}

.egf svg:not(:root) {
    overflow: hidden
}

.egf figure {
    margin: 1em 40px
}

.egf hr {
    -webkit-box-sizing: content-box;
    box-sizing: content-box;
    height: 0
}

.egf pre {
    overflow: auto
}

.egf code,
.egf kbd,
.egf pre,
.egf samp {
    font-family: monospace, monospace;
    font-size: 1em
}

.egf button,
.egf input,
.egf optgroup,
.egf select,
.egf textarea {
    color: inherit;
    font: inherit;
    margin: 0
}

.egf button {
    overflow: visible
}

.egf button,
.egf select {
    text-transform: none
}

.egf button,
.egf html input[type=button],
.egf input[type=reset],
.egf input[type=submit] {
    -webkit-appearance: button;
    cursor: pointer
}

.egf button[disabled],
.egf html input[disabled] {
    cursor: default
}

.egf button::-moz-focus-inner,
.egf input::-moz-focus-inner {
    border: 0;
    padding: 0
}

.egf input {
    line-height: normal
}

.egf input[type=checkbox],
.egf input[type=radio] {
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
    padding: 0
}

.egf input[type=number]::-webkit-inner-spin-button,
.egf input[type=number]::-webkit-outer-spin-button {
    height: auto
}

.egf input[type=search] {
    -webkit-appearance: textfield;
    -webkit-box-sizing: content-box;
    box-sizing: content-box
}

.egf input[type=search]::-webkit-search-cancel-button,
.egf input[type=search]::-webkit-search-decoration {
    -webkit-appearance: none
}

.egf fieldset {
    border: 1px solid silver;
    margin: 0 2px;
    padding: .35em .625em .75em
}

.egf legend {
    border: 0;
    padding: 0
}

.egf textarea {
    overflow: auto
}

.egf optgroup {
    font-weight: 700
}

.egf table {
    border-collapse: collapse;
    border-spacing: 0
}

.egf td,
.egf th {
    padding: 0
}

.egf a {
    color: #ccc
}

.egf a:hover {
    color: #fff
}

.egf i,
.egf span {
    color: #ccc
}

.egf hr {
    border-style: solid none none
}

#egf {
    font-size: 16px;
    font-family: OpenSans, sans-serif;
    -webkit-text-size-adjust: 100%;
    -moz-text-size-adjust: 100%;
    -ms-text-size-adjust: 100%;
    text-size-adjust: 100%;
    position: relative;
    padding: 1.25em 4.5em 2.5em;
    z-index: 10
}

#egf .no-padding {
    padding-left: 0;
    padding-right: 0
}

@media only screen and (max-width:991px) {
    #egf {
        padding: 1em 1.5em
    }
}

@media only screen and (device-max-width:768px) and (orientation:landscape) and (-webkit-min-device-pixel-ratio:1) {
    #egf {
        padding: 1em 2em
    }
}

#egf a:active,
#egf a:focus,
#egf a:hover,
#egf a:visited,
#egf i:focus,
#egf i:visited {
    outline-color: transparent;
    outline: none;
    border: none;
    text-decoration: none
}

#egf button:active,
#egf button:focus,
#egf button:visited {
    outline-color: transparent;
    outline: none;
    text-decoration: none
}

#egf .row {
    margin-top: 0;
    margin-bottom: 0
}

#egf hr {
    margin: 1em 0
}

@media only screen and (max-width:767px) {
    #egf hr {
        margin: 1em 0 .5em
    }
}

.forum-theme .egf a,
.forum-theme .egf ol,
.forum-theme .egf ul {
    font-family: OpenSans, sans-serif;
    font-size: 1em;
    line-height: 2em
}

.forum-theme .egf p {
    line-height: 2em
}

.egf .logos,
.egf .social {
    padding: 0
}

.egf .logos li,
.egf .social li {
    display: inline-block
}

.egf .logos li i,
.egf .social li i {
    font-size: 1.75em;
    -webkit-transition: color .3s ease-in-out;
    -o-transition: color .3s ease-in-out;
    transition: color .3s ease-in-out
}

.egf .logos li:first-child,
.egf .social li:first-child {
    padding-left: 0
}

.egf .logos {
    margin: 0
}

.egf .social {
    margin: 1em 0 0;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none
}

.egf .social li {
    padding: 0 .15em;
    margin: 0 0 .5em
}

@media only screen and (max-width:991px) {
    .egf .social li {
        padding: 0 .1em
    }
}

.egf .social #rss {
    position: relative;
    top: -3px
}

.egf .social #rss i {
    font-size: 1.3em
}

.egf .social #twitch i {
    font-size: 1.6em
}

.egf .social button.qr-opener {
    background: transparent;
    border: none;
    padding: 0
}

.egf .social button.qr-opener .image-container {
    display: none
}

.egf .social button.qr-opener .image-container.display {
    display: block
}

.egf .social button.qr-opener .qrcode-bg {
    background-size: contain;
    width: 200px;
    height: 200px;
    position: absolute;
    z-index: 11;
    border-radius: 5px
}

@media only screen and (max-width:991px) {
    .egf .social button.qr-opener .qrcode-bg {
        width: 120px;
        height: 120px
    }
}

.egf .copyright {
    padding: 1em;
    margin-top: 0;
    border-top: #dfdfdf;
    -webkit-text-size-adjust: 100%;
    -moz-text-size-adjust: 100%;
    -ms-text-size-adjust: 100%;
    text-size-adjust: 100%
}

@media only screen and (max-width:991px) {
    .egf .copyright {
        padding: .4em 1em
    }
}

.egf .copyright .copyright-paragraph {
    margin: 0;
    padding-top: .5em;
    font-size: .71em;
    color: #fff;
    font-family: OpenSans, sans-serif;
    font-weight: 400;
    line-height: 2em
}

.egf .legal {
    padding: 1em 0 0 1em
}

@media only screen and (max-width:767px) {
    .egf .legal {
        padding: .25em 0 0;
        text-align: center
    }
}

.egf .legal .links {
    float: none;
    width: auto;
    padding: 0;
    font-family: OpenSans, sans-serif
}

.egf .legal .links li {
    padding: 0 1em 0 0;
    display: inline
}

@media only screen and (max-width:767px) {
    .egf .legal .links li {
        padding: 0;
        display: block
    }
}

.egf .legal .links li a {
    font-size: .75em;
    -webkit-transition: color .2s ease-in-out;
    -o-transition: color .2s ease-in-out;
    transition: color .2s ease-in-out
}

.egf .logos {
    text-align: right;
    padding-bottom: .5em
}

@media only screen and (max-width:767px) {
    .egf .logos {
        text-align: center;
        margin-left: 1em;
        padding-top: .5em
    }
}

.egf .logos li {
    margin-right: .75em
}

.egf .logos li i {
    font-size: 2em;
    opacity: .92;
    vertical-align: middle
}

@media only screen and (max-width:767px) {
    .egf .logos li i {
        font-size: 1.5em
    }
}

.egf .tags {
    -webkit-transform-style: preserve-3d;
    transform-style: preserve-3d;
    -webkit-transform: translateZ(0);
    transform: translateZ(0);
    padding: 0;
    margin: 2em 0 0;
    float: right;
    text-align: right;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none
}

.egf .tags img {
    max-height: 5.2em;
    background-size: contain;
    margin: .2em .3em
}

@media only screen and (max-width:767px) {
    .egf .tags img {
        max-height: 4.4em
    }
}

.egf .tags .tag-title {
    font-size: .6em;
    font-weight: 500;
    text-align: center;
    margin: 0;
    text-transform: uppercase
}

@media only screen and (max-width:767px) {
    .egf .tags {
        margin: 1em auto 0;
        float: none;
        text-align: center;
        max-width: 90%
    }

    .egf .tags li {
        float: none !important;
        text-align: center;
        display: inline-block
    }
}

.egf .tags li {
    list-style-type: none;
    display: inline-block
}

.egf .tags li img,
.egf .up-button {
    text-align: center
}

.egf .up-button {
    cursor: pointer;
    float: right;
    width: 2.1em;
    height: 2.1em;
    border: 2px solid #fff;
    padding: .25em;
    border-radius: 2px;
    margin: 1.25em 1em 0 0;
    -webkit-transition: border .3s ease-in-out;
    -o-transition: border .3s ease-in-out;
    transition: border .3s ease-in-out;
    background-color: transparent;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none
}

@media only screen and (max-width:767px) {
    .egf .up-button {
        margin: .75em 0 0
    }
}

.egf .up-button.bot-margin {
    margin-bottom: 1.25em
}

.egf .up-button span {
    display: block;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    font-size: 1.5em;
    -webkit-transition: color .3s ease-in-out;
    -o-transition: color .3s ease-in-out;
    transition: color .3s ease-in-out
}

.egf .up-button:hover {
    border-color: #fff
}

.egf .up-button:hover span {
    color: #fff
}

.egf .footer-cta-btn {
    margin: 3em 0 1em;
    padding: .7em 1em;
    text-transform: uppercase;
    font-size: .8em;
    display: inline-block;
    cursor: pointer
}

@media only screen and (max-width:1199px) {
    .egf .footer-cta-btn {
        font-size: .7em;
        padding: 1em
    }
}

@media only screen and (max-width:767px) {
    .egf .footer-cta-btn {
        padding: 1em;
        margin: 3em auto 2em 0;
        font-size: .65em;
        float: none
    }
}

.egf .subtitle {
    display: block;
    padding-top: 1.5em;
    font-size: .86em;
    font-weight: 700;
    margin-bottom: 4px
}

@media only screen and (max-width:767px) {
    .egf .subtitle {
        font-size: .9em;
        margin-bottom: 0;
        padding-top: 0
    }
}

.egf .subtitle span {
    opacity: .4
}

.egf .footerLink-wrapper {
    float: left
}

@media only screen and (max-width:767px) {
    .egf .footerLink-wrapper {
        margin: 1em auto;
        width: 100%
    }

    .egf .footerLink-wrapper .inner-wrap {
        margin: 0 auto
    }

    .egf .footerLink-wrapper .footerLinks.first-column {
        padding-bottom: 0
    }

    .egf .footerLink-wrapper .footerLinks.second-column,
    .egf .footerLink-wrapper .footerLinks.third-column {
        margin-top: 0 !important
    }
}

.egf .footerLinks {
    float: left;
    list-style: none;
    margin: 0;
    padding: 0 2.6em .5em 0
}

@media only screen and (device-max-width:768px) and (orientation:landscape) and (-webkit-min-device-pixel-ratio:1) {
    .egf .footerLinks {
        font-size: 1.05em
    }
}

.egf .footerLinks li {
    line-height: 1.5em
}

.egf .footerLinks li a {
    font-size: .86em;
    font-family: OpenSans, sans-serif;
    cursor: pointer;
    -webkit-transition: color .3s ease-in-out;
    -o-transition: color .3s ease-in-out;
    transition: color .3s ease-in-out
}

@media only screen and (max-width:767px) {
    .egf .one:not(.two):not(.three) .footerLinks {
        padding: 0;
        margin: 0 auto 1em
    }
}

@media only screen and (max-width:767px) {
    .egf .two:not(.three) .footerLinks {
        padding-right: 1em
    }
}

@media only screen and (max-width:767px) {
    .egf .two:not(.three) .footerLinks.second-column {
        padding: 0;
        margin-top: 1.25em
    }
}

.egf .three .footerLinks {
    padding-right: 1.5em
}

@media only screen and (device-max-width:568px) and (orientation:portrait) and (-webkit-min-device-pixel-ratio:1) {
    .egf .three .footerLinks {
        padding-right: 1em;
        font-size: .8em
    }
}

@media only screen and (max-width:767px) {
    .egf .three .footerLinks.second-column {
        float: left
    }
}

.egf .three .footerLinks.third-column {
    padding-top: 0
}

.footer-news-letter-modal .footer-news-letter-content {
    outline: none;
    font-size: 16px
}

.footer-news-letter-modal .footer-news-letter-content .legal-notice {
    margin-bottom: 5px;
    font-style: italic
}

.footer-news-letter-modal .footer-news-letter-content .legal-notice,
.footer-news-letter-modal .footer-news-letter-content .privacy-link {
    -webkit-transition: color .3s ease-in-out;
    -o-transition: color .3s ease-in-out;
    transition: color .3s ease-in-out;
    text-align: center;
    font-size: .8em;
    font-family: OpenSans, sans-serif;
    color: #333
}

.footer-news-letter-modal .footer-news-letter-content .privacy-link {
    margin-top: 0
}

.footer-news-letter-modal .footer-news-letter-content .privacy-link a {
    color: inherit
}

.footer-news-letter-modal .footer-news-letter-content .box-bg {
    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0
}

.footer-news-letter-modal .footer-news-letter-content .close-btn {
    position: absolute;
    top: 0;
    right: 20px;
    cursor: pointer;
    color: #333;
    font-size: .9em;
    font-weight: 700;
    opacity: .5;
    -webkit-transition: opacity .2s;
    -o-transition: opacity .2s;
    transition: opacity .2s
}

.footer-news-letter-modal .footer-news-letter-content .close-btn:before {
    content: "\2A2F";
    font-size: 3em
}

.footer-news-letter-modal .footer-news-letter-content .close-btn:hover {
    opacity: 1;
    -webkit-transition: opacity .2s;
    -o-transition: opacity .2s;
    transition: opacity .2s;
    background: none
}

.footer-news-letter-modal .footer-news-letter-content .signup-title {
    font-family: inherit;
    font-size: 1.1em;
    text-align: center;
    margin: 1.5em 0;
    color: #333
}

.footer-news-letter-modal .footer-news-letter-content .newsletter-logo {
    width: 130px;
    height: 130px;
    background-size: 100%;
    position: absolute;
    top: -60px;
    left: calc(50% - 65px);
    max-width: 130px
}

@media only screen and (max-height:500px) and (orientation:landscape) {
    .footer-news-letter-modal .footer-news-letter-content .newsletter-logo {
        position: static;
        width: 50px;
        height: 50px;
        display: block;
        margin: -50px auto 0
    }
}

.footer-news-letter-modal .footer-news-letter-content .loading {
    width: 60px;
    height: 60px;
    text-align: center;
    background: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzMiIgaGVpZ2h0PSIzMiIgZmlsbD0iIzBhYWZmMSI+PHBhdGggb3BhY2l0eT0iLjI1IiBkPSJNMTYgMGExNiAxNiAwIDAwMCAzMiAxNiAxNiAwIDAwMC0zMm0wIDRhMTIgMTIgMCAwMTAgMjQgMTIgMTIgMCAwMTAtMjQiLz48cGF0aCBkPSJNMTYgMGExNiAxNiAwIDAxMTYgMTZoLTRBMTIgMTIgMCAwMDE2IDR6Ij48YW5pbWF0ZVRyYW5zZm9ybSBhdHRyaWJ1dGVOYW1lPSJ0cmFuc2Zvcm0iIHR5cGU9InJvdGF0ZSIgZnJvbT0iMCAxNiAxNiIgdG89IjM2MCAxNiAxNiIgZHVyPSIwLjhzIiByZXBlYXRDb3VudD0iaW5kZWZpbml0ZSIvPjwvcGF0aD48L3N2Zz4=) no-repeat;
    margin: 25% auto auto
}

.footer-news-letter-modal .footer-news-letter-content .close-btn {
    background: transparent;
    border: none;
    outline: 0;
    padding: 0
}

.footer-news-letter-modal .footer-news-letter-content .modal-btn {
    position: relative;
    margin: 1.5em auto 1em;
    display: block;
    width: 140px;
    height: auto;
    width: auto;
    padding: 8px 30px;
    border-radius: 0;
    font-size: .9em;
    line-height: 32px;
    text-align: center;
    text-transform: uppercase;
    border: none;
    outline: none;
    cursor: pointer;
    -webkit-transition: all .3s ease-in;
    -o-transition: .3s all ease-in;
    -o-transition: all .3s ease-in;
    transition: all .3s ease-in
}

.footer-news-letter-modal .footer-news-letter-content .modal-btn.invalid {
    cursor: auto
}

.footer-news-letter-modal .footer-news-letter-content .modal-btn:disabled {
    background-color: grey;
    cursor: not-allowed
}

.footer-news-letter-modal .footer-news-letter-content .sign-up-form-box {
    display: block
}

.footer-news-letter-modal .footer-news-letter-content .newsletter-form .sign-up-form-field {
    list-style-type: none;
    position: relative
}

.footer-news-letter-modal .footer-news-letter-content .newsletter-form .sign-up-form-field.invalid {
    border: 1px solid #f73131;
    border-radius: 3px
}

.footer-news-letter-modal .footer-news-letter-content .newsletter-form .sign-up-form-field .email-label {
    position: absolute;
    padding-left: 10px;
    font-family: Lato, Helvetica, Arial, sans-serif;
    font-size: 12px;
    text-transform: uppercase;
    color: #a9aaaa;
    z-index: 1;
    top: 17px;
    font-weight: 300
}

.footer-news-letter-modal .footer-news-letter-content .newsletter-form .sign-up-form-field .input-field {
    display: block;
    width: 100%;
    padding: 8px 20px 10px 60px;
    margin: 0;
    height: 50px;
    border: 1px solid #ddd;
    border-radius: 1px;
    border-top-left-radius: 1px;
    border-top-right-radius: 1px;
    border-bottom-right-radius: 1px;
    border-bottom-left-radius: 1px;
    outline: none;
    font-size: 14px;
    font-family: Lato, Helvetica, Arial, sans-serif;
    font-weight: 400;
    text-align: left;
    background-color: #f2f2f2;
    color: #000
}

.footer-news-letter-modal .footer-news-letter-content .newsletter-form .errorMsg {
    padding-top: 10px;
    display: block;
    color: #f73131;
    font-size: 13.5px
}

.footer-news-letter-modal .footer-news-letter-content .newsletter-form .email.errorMsg {
    color: #f73131;
    position: absolute;
    bottom: -2em;
    font-size: .7em;
    padding: 0;
    margin: 0
}

.footer-news-letter-modal .footer-news-letter-content .alreadySubscribed,
.footer-news-letter-modal .footer-news-letter-content .successView {
    text-align: center;
    margin-top: 3em
}

.footer-news-letter-modal .footer-news-letter-content .alreadySubscribed h2,
.footer-news-letter-modal .footer-news-letter-content .successView h2 {
    font-size: 1em;
    font-size: 1.5em;
    line-height: 2em
}

.footer-news-letter-modal .footer-news-letter-content .alreadySubscribed a,
.footer-news-letter-modal .footer-news-letter-content .successView a {
    display: inline-block
}

body,
html {
    width: 100%;
    height: 100%
}

body {
    background-color: #2a2a2a;
    font-family: OpenSans, sans-serif;
    font-size: 16px;
    text-rendering: optimizeLegibility
}

.align-bottom {
    position: absolute;
    bottom: 1em;
    left: 0;
    right: 0;
    margin: 0 1em 0 0;
    color: #fff;
    text-align: right
}

@media only screen and (max-width:991px) {
    .align-bottom h3 {
        font-size: 1em
    }
}

@media only screen and (max-width:991px) {
    .align-bottom {
        margin: 0
    }
}

.col-centered {
    float: none;
    margin: 0 auto
}

.ellipsis {
    white-space: pre;
    -o-text-overflow: ellipsis;
    text-overflow: ellipsis;
    overflow: hidden
}

.embed-responsive {
    position: relative;
    display: block;
    height: 0;
    padding: 0;
    overflow: hidden
}

.embed-responsive-16by9 {
    padding-bottom: 56.25%
}

.embed-responsive .embed-responsive-item,
.embed-responsive embed,
.embed-responsive iframe,
.embed-responsive object,
.embed-responsive video {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0
}

@font-face {
    font-family: BurbankBigCondensed-Black;
    src: url(fonts/3145d45497404272c3d2ce2554b196b1.eot);
    src: url(fonts/3145d45497404272c3d2ce2554b196b1.eot#iefix) format("embedded-opentype"), url(fonts/c5d323c99493dd76432d4f531b8cc329.woff) format("woff"), url(fonts/43532e1ca66951cb8370066686a78c87.svg) format("svg");
    font-weight: 400;
    font-style: normal;
    font-stretch: normal
}

@font-face {
    font-family: BurbankSmall-Black;
    src: url(fonts/f0b9f8c8ddfc38012c5c12ab12390152.eot);
    src: url(fonts/f0b9f8c8ddfc38012c5c12ab12390152.eot#iefix) format("embedded-opentype"), url(fonts/77a30b9cce16b2ec2a0c0bb8c4fea1e3.woff) format("woff"), url(fonts/a4414286dbc65d33a294486c8641781c.svg) format("svg");
    font-weight: 400;
    font-style: normal;
    font-stretch: normal
}

@font-face {
    font-family: BurbankBigRegular-Black;
    src: url(fonts/76299fe73939fd5fd786c7ab6dee6552.eot);
    src: url(fonts/76299fe73939fd5fd786c7ab6dee6552.eot#iefix) format("embedded-opentype"), url(fonts/e868c17ab696cf4b6b618bcb2fdca65e.woff) format("woff"), url(fonts/1d6843c18d7f1185fb9cc25e98259cc2.woff2) format("woff2"), url(e2fc99375791425012682e598d964e75.html) format("svg");
    font-weight: 400;
    font-style: normal;
    font-stretch: normal
}

@font-face {
    font-family: OpenSans;
    font-weight: 200;
    font-style: normal;
    src: url(46a88522bae4b2d6d52a884d59d91e51.html);
    src: url(46a88522bae4b2d6d52a884d59d91e51d41d.html?#iefix) format("embedded-opentype"), url(74b082c44a961dd6d2b56adabdd1b67e.html) format("woff"), url(bf2d93f6fa0c1594c2d4a313040482af.html) format("truetype"), url(18634c71f9495a1017b3faf702b27102.html#open_sanslight) format("svg")
}

@font-face {
    font-family: OpenSans;
    font-weight: 300;
    font-style: normal;
    src: url(46a88522bae4b2d6d52a884d59d91e51.html);
    src: url(46a88522bae4b2d6d52a884d59d91e51d41d.html?#iefix) format("embedded-opentype"), url(74b082c44a961dd6d2b56adabdd1b67e.html) format("woff"), url(bf2d93f6fa0c1594c2d4a313040482af.html) format("truetype"), url(18634c71f9495a1017b3faf702b27102.html#open_sanslight) format("svg")
}

@font-face {
    font-family: OpenSans;
    font-weight: 400;
    font-style: normal;
    src: url(83efe33660ab6a7fe428c8078d47485f.html);
    src: url(83efe33660ab6a7fe428c8078d47485fd41d.html?#iefix) format("embedded-opentype"), url(55b8ce1f9a32bb0f83f14813eac0b7ca.html) format("woff"), url(c7571df954bd2b7ffcd78628a24ff2ed.html) format("truetype"), url(bdcfdd6f83b4fd26b9b75e61dd01c109.html#open_sansregular) format("svg")
}

@font-face {
    font-family: OpenSans;
    font-weight: 500;
    font-style: normal;
    src: url(3055c832e06d4423d110734ab7526880.html);
    src: url(3055c832e06d4423d110734ab7526880d41d.html?#iefix) format("embedded-opentype"), url(834e3616d9e57f3f027e96394f43efa0.html) format("woff"), url(a503b79af3e35504c7b322dbc84cac2d.html) format("truetype"), url(058450dd769bcdc85e082ef4edfe8b47.html#open_sanssemibold) format("svg")
}

@font-face {
    font-family: OpenSans;
    font-weight: 600;
    font-style: normal;
    src: url(80f498db52c0e2c87aac64f49ff59c12.html);
    src: url(80f498db52c0e2c87aac64f49ff59c12d41d.html?#iefix) format("embedded-opentype"), url(57988d1e313ced044867ac305c58ce7b.html) format("woff"), url(25b58a3f2e02b3ec021e9c765e38410e.html) format("truetype"), url(c3a6f74d1ca94f62915f637fbf1818f7.html#open_sansbold) format("svg")
}

@font-face {
    font-family: OpenSans;
    font-weight: 700;
    font-style: normal;
    src: url(80f498db52c0e2c87aac64f49ff59c12.html);
    src: url(80f498db52c0e2c87aac64f49ff59c12d41d.html?#iefix) format("embedded-opentype"), url(57988d1e313ced044867ac305c58ce7b.html) format("woff"), url(25b58a3f2e02b3ec021e9c765e38410e.html) format("truetype"), url(c3a6f74d1ca94f62915f637fbf1818f7.html#open_sansbold) format("svg")
}

@font-face {
    font-family: OpenSans;
    font-weight: 800;
    font-style: normal;
    src: url(80f498db52c0e2c87aac64f49ff59c12.html);
    src: url(80f498db52c0e2c87aac64f49ff59c12d41d.html?#iefix) format("embedded-opentype"), url(57988d1e313ced044867ac305c58ce7b.html) format("woff"), url(25b58a3f2e02b3ec021e9c765e38410e.html) format("truetype"), url(c3a6f74d1ca94f62915f637fbf1818f7.html#open_sansbold) format("svg")
}

@font-face {
    font-family: OpenSans;
    font-weight: 900;
    font-style: normal;
    src: url(dd36f76373a576b800f4824d1d4b433a.html);
    src: url(dd36f76373a576b800f4824d1d4b433ad41d.html?#iefix) format("embedded-opentype"), url(462b22cd3bf47ca775db7b6be40d5429.html) format("woff"), url(9d8ebd837eebcb510c28679a57edb348.html) format("truetype"), url(fedff12232aa98504ad1a4662fd1b2ab.html#open_sansExtraBold) format("svg")
}

@font-face {
    font-family: aERIN;
    font-weight: 300;
    font-style: normal;
    src: url(95f747f9aebd268d7e9a7a7223b81697.html);
    src: url(95f747f9aebd268d7e9a7a7223b81697d41d.html?#iefix) format("embedded-opentype"), url(9d568e6ac51b2dffaef6685711ef4161.html) format("woff"), url(19cb9b337d79332f1e5892944f1d55ab.html) format("truetype"), url(479ea0a40264cd0e196981d7210cfea7.html) format("svg")
}

@font-face {
    font-family: aERIN;
    font-weight: 500;
    font-style: normal;
    src: url(89a0a858c7305b64ba20da6a5bca078a.html);
    src: url(89a0a858c7305b64ba20da6a5bca078ad41d.html?#iefix) format("embedded-opentype"), url(6cb066317cf3249c961560c2cb358185.html) format("woff"), url(417c519cfcd23515482d06b378fa0778.html) format("truetype"), url(da4e45142e06057c29b98dc6f62777d0.html) format("svg")
}

@font-face {
    font-family: aERIN;
    font-weight: 700;
    font-style: normal;
    src: url(e6ad22c80c5a92517ed62196bbb6fac9.html);
    src: url(e6ad22c80c5a92517ed62196bbb6fac9d41d.html?#iefix) format("embedded-opentype"), url(95c1f272c70e240f1482e1bf08f8989d.html) format("woff"), url(a2807fd3832728b22f828c012bea2a4d.html) format("truetype"), url(fb1bcf98fc94d8d9c98e14932507f7d5.html) format("svg")
}

@font-face {
    font-family: NotoSansCJKkr;
    font-weight: 500;
    font-style: normal;
    src: url(19b7d8d4011e8f88930022704558246d.html) format("opentype")
}

@font-face {
    font-family: NotoSansCJKkr;
    font-weight: 700;
    font-style: normal;
    src: url(79d613fb8ec20fbb6bfcbf64e93cc9b2.html) format("opentype")
}

@font-face {
    font-family: Nis_Jyau_P;
    font-weight: 400;
    font-style: normal;
    src: url(35faa2627abd7020acc8a00e2b758e63.html) format("woff2"), url(f7b6ac379b4f220a39002fa138310da1.html) format("woff")
}

@font-face {
    font-family: NotoSansCJKjp;
    font-weight: 500;
    font-style: normal;
    src: url(7ed4b9a7daaf1d1c71903a92059434fb.html) format("opentype")
}

@font-face {
    font-family: NotoSansCJKjp;
    font-weight: 700;
    font-style: normal;
    src: url(1805644d0919a80051e76e1fc750a189.html) format("opentype")
}

@font-face {
    font-family: NotoNaskhArabic;
    font-weight: 500;
    font-style: normal;
    src: url(c9ea4fcb9b1761acdcc43e2078d51b19.html) format("truetype")
}

@font-face {
    font-family: NotoNaskhArabic;
    font-weight: 700;
    font-style: normal;
    src: url(563a631edc70eb9076230d629178092e.html) format("truetype")
}

@font-face {
    font-family: NotoNaskhArabicUI;
    font-weight: 500;
    font-style: normal;
    src: url(7aff0c64de97d36e04382b55e868e5f1.html) format("truetype")
}

@font-face {
    font-family: NotoNaskhArabicUI;
    font-weight: 700;
    font-style: normal;
    src: url(9429aacc871232c9154f22aba0dbbe85.html) format("truetype")
}

@font-face {
    font-family: icomoon;
    src: url(1a946db515e9d8863a32189412976fc4.html);
    src: url(1a946db515e9d8863a32189412976fc4.html#iefix) format("embedded-opentype"), url(5df4bc87a714ce6e477fb713dff7c663.html) format("truetype"), url(ed2b0320e7a7564ec0a350519bd6c888.html) format("woff"), url(b8e43667bb3a2075afd53a920399ac01.html#icomoon) format("svg");
    font-weight: 400;
    font-style: normal;
}

[class*=" icon-"],
[class^=icon-] {
    font-family: icomoon !important;
    font-style: normal;
    font-weight: 400;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    letter-spacing: 0;
    -webkit-font-feature-settings: "liga";
    -ms-font-feature-settings: "liga"1;
    font-feature-settings: "liga", normal, "dlig";
    -webkit-font-variant-ligatures: discretionary-ligatures;
    font-variant-ligatures: discretionary-ligatures;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale
}

.icon-ninja:before {
    content: "\E909"
}

.icon-outlander:before {
    content: "\E90A"
}

.icon-commando:before,
.icon-soldier:before {
    content: "\E902"
}

.icon-constructor:before {
    content: "\E903"
}

.icon-sfs-icon:before {
    content: "\E912"
}

.icon-packs:before {
    content: "\E917"
}

.icon-arrow {
    font-size: 1.2em
}

.icon-arrow:before {
    content: "\E911";
    font-size: .8em
}

.icon-arrow-right:before {
    content: "\E911"
}

.icon-arrow-left {
    -webkit-transform: rotate(-180deg);
    -ms-transform: rotate(-180deg);
    transform: rotate(-180deg);
    display: block
}

.icon-arrow-left:before {
    content: "\E911"
}

.icon-menu:before {
    content: "\E9BD"
}

.icon-magnifyGlass:before {
    content: "\E915"
}

.icon-clock:before {
    content: "\E90E"
}

.icon-x:before {
    content: "\E913"
}

.icon-play-triangle:before {
    content: "\EA1C"
}

.icon-badge:before {
    content: "\E900"
}

.icon-check:before {
    content: "\E901"
}

.icon-down-arrow:before {
    content: "\E905"
}

.icon-up-arrow {
    -webkit-transform: rotate(-180deg);
    -ms-transform: rotate(-180deg);
    transform: rotate(-180deg)
}

.icon-up-arrow:before {
    content: "\E905"
}

.icon-left-arrow:before {
    content: "\E906"
}

.icon-lock:before {
    content: "\E908"
}

.icon-reverse-left-arrow:before {
    content: "\E90B"
}

.icon-reverse-right-arrow:before {
    content: "\E90F"
}

.icon-right-arrow:before {
    content: "\E911"
}

.icon-toxic:before {
    content: "\E919"
}

.icon-close:before {
    content: "\E914"
}

.icon-play:before {
    content: "\E605"
}

.icon-refresh:before {
    content: "\E800"
}

.icon-grid:before {
    content: "\E90D"
}

.icon-link-external:before {
    content: "\E907"
}

.icon-warning:before {
    content: "\EA07"
}

.icon-notification:before {
    content: "\EA08"
}

.icon-plus:before {
    content: "\EA0A"
}

.icon-tv:before {
    content: "\E924"
}

.icon-location:before {
    content: "\E947"
}

.icon-full-arrow {
    font-size: 1.2em
}

.icon-full-arrow:before {
    content: "\E92C";
    font-size: .8em
}

.icon-facebook:before {
    content: "\EA90"
}

.icon-vk:before {
    content: "\EA98"
}

.icon-reddit:before {
    content: "\E916"
}

.icon-vk-noBox:before {
    content: "\E91A"
}

.icon-twitch:before {
    content: "\E904"
}

.icon-google-plus:before,
.icon-google:before {
    content: "\E910"
}

.icon-youtube:before {
    content: "\E90C"
}

.icon-facebook-circle:before {
    content: "\E918"
}

.icon-instagram:before {
    content: "\E91B"
}

.icon-twitter:before {
    content: "\E91C"
}

.icon-mixer:before {
    content: "\E922"
}

.icon-github:before {
    content: "\E929"
}

.icon-steam:before {
    content: "\EAAD"
}

.icon-ruble:before {
    content: "\20BD"
}

.icon-pc:before,
.icon-pcMac:before {
    content: "\E91D"
}

.icon-ps4:before,
.icon-psn:before {
    content: "\E91E"
}

.icon-xbl:before,
.icon-xbox:before {
    content: "\E91F"
}

.icon-pc_mobile:before {
    content: "\E920"
}

.icon-mobile:before {
    content: "\E921"
}

.icon-nintendo:before,
.icon-switch:before {
    content: "\E923"
}

.icon-iOS:before {
    content: "\E925"
}

.icon-android:before {
    content: "\E926"
}

.icon-mac-os:before {
    content: "\E927"
}

.icon-windows:before {
    content: "\E928"
}

.icon-exclamation-circle:before {
    content: "\E92A"
}

.icon-ticket:before {
    content: "\E92B"
}

@-webkit-keyframes jiggle {

    0%,
    14% {
        -webkit-transform: scale(1);
        transform: scale(1)
    }

    2% {
        -webkit-transform: scaleY(.9);
        transform: scaleY(.9)
    }

    8% {
        -webkit-transform: scale(.9, 1.1) translateY(-5px);
        transform: scale(.9, 1.1) translateY(-5px)
    }

    11% {
        -webkit-transform: scale(1) translateY(-3px);
        transform: scale(1) translateY(-3px)
    }
}

@keyframes jiggle {

    0%,
    14% {
        -webkit-transform: scale(1);
        transform: scale(1)
    }

    2% {
        -webkit-transform: scaleY(.9);
        transform: scaleY(.9)
    }

    8% {
        -webkit-transform: scale(.9, 1.1) translateY(-5px);
        transform: scale(.9, 1.1) translateY(-5px)
    }

    11% {
        -webkit-transform: scale(1) translateY(-3px);
        transform: scale(1) translateY(-3px)
    }
}

@-webkit-keyframes jelly {
    0% {
        -webkit-transform: matrix(1, 0, 0, 1, 0, 0);
        transform: matrix(1, 0, 0, 1, 0, 0)
    }

    50% {
        -webkit-transform: matrix3d(1.0593, 0, -.1, .00025, 0, .9603, .1, -.0001, .1, -.1, .9801, 0, 0, -3, 0, 1);
        transform: matrix3d(1.0593, 0, -.1, .00025, 0, .9603, .1, -.0001, .1, -.1, .9801, 0, 0, -3, 0, 1)
    }

    to {
        -webkit-transform: matrix(1, 0, 0, 1, 0, 0);
        transform: matrix(1, 0, 0, 1, 0, 0)
    }
}

@keyframes jelly {
    0% {
        -webkit-transform: matrix(1, 0, 0, 1, 0, 0);
        transform: matrix(1, 0, 0, 1, 0, 0)
    }

    50% {
        -webkit-transform: matrix3d(1.0593, 0, -.1, .00025, 0, .9603, .1, -.0001, .1, -.1, .9801, 0, 0, -3, 0, 1);
        transform: matrix3d(1.0593, 0, -.1, .00025, 0, .9603, .1, -.0001, .1, -.1, .9801, 0, 0, -3, 0, 1)
    }

    to {
        -webkit-transform: matrix(1, 0, 0, 1, 0, 0);
        transform: matrix(1, 0, 0, 1, 0, 0)
    }
}

@-webkit-keyframes bounce {
    0% {
        -webkit-transform: translateY(.1em);
        transform: translateY(.1em)
    }

    50% {
        -webkit-transform: translateY(.4em);
        transform: translateY(.4em)
    }

    to {
        -webkit-transform: translateY(.1em);
        transform: translateY(.1em)
    }
}

@keyframes bounce {
    0% {
        -webkit-transform: translateY(.1em);
        transform: translateY(.1em)
    }

    50% {
        -webkit-transform: translateY(.4em);
        transform: translateY(.4em)
    }

    to {
        -webkit-transform: translateY(.1em);
        transform: translateY(.1em)
    }
}

@-webkit-keyframes zoom {
    0% {
        opacity: 0;
        -webkit-transform: scale(.9) translateY(-50%);
        transform: scale(.9) translateY(-50%)
    }

    30% {
        opacity: 1;
        -webkit-transform: scale(.9) translateY(-50%);
        transform: scale(.9) translateY(-50%)
    }

    50% {
        -webkit-transform: scale(1.03) translateY(-50%);
        transform: scale(1.03) translateY(-50%)
    }

    to {
        -webkit-transform: scale(1) translateY(-50%);
        transform: scale(1) translateY(-50%)
    }
}

@keyframes zoom {
    0% {
        opacity: 0;
        -webkit-transform: scale(.9) translateY(-50%);
        transform: scale(.9) translateY(-50%)
    }

    30% {
        opacity: 1;
        -webkit-transform: scale(.9) translateY(-50%);
        transform: scale(.9) translateY(-50%)
    }

    50% {
        -webkit-transform: scale(1.03) translateY(-50%);
        transform: scale(1.03) translateY(-50%)
    }

    to {
        -webkit-transform: scale(1) translateY(-50%);
        transform: scale(1) translateY(-50%)
    }
}

@-webkit-keyframes float {
    0% {
        -webkit-transform: translate(0);
        transform: translate(0)
    }

    65% {
        -webkit-transform: translateY(2em);
        transform: translateY(2em)
    }

    to {
        -webkit-transform: translate(0);
        transform: translate(0)
    }
}

@keyframes float {
    0% {
        -webkit-transform: translate(0);
        transform: translate(0)
    }

    65% {
        -webkit-transform: translateY(2em);
        transform: translateY(2em)
    }

    to {
        -webkit-transform: translate(0);
        transform: translate(0)
    }
}

@-webkit-keyframes shadow-pulse {
    0% {
        -webkit-box-shadow: 0 0 0 0 rgba(0, 0, 0, .2);
        box-shadow: 0 0 0 0 rgba(0, 0, 0, .2)
    }

    to {
        -webkit-box-shadow: 0 0 0 35px transparent;
        box-shadow: 0 0 0 35px transparent
    }
}

@keyframes shadow-pulse {
    0% {
        -webkit-box-shadow: 0 0 0 0 rgba(0, 0, 0, .2);
        box-shadow: 0 0 0 0 rgba(0, 0, 0, .2)
    }

    to {
        -webkit-box-shadow: 0 0 0 35px transparent;
        box-shadow: 0 0 0 35px transparent
    }
}

@-webkit-keyframes text-focus-in {
    0% {
        -webkit-filter: blur(12px);
        filter: blur(12px);
        opacity: 0
    }

    to {
        -webkit-filter: blur(0);
        filter: blur(0);
        opacity: 1
    }
}

@keyframes text-focus-in {
    0% {
        -webkit-filter: blur(12px);
        filter: blur(12px);
        opacity: 0
    }

    to {
        -webkit-filter: blur(0);
        filter: blur(0);
        opacity: 1
    }
}

@-webkit-keyframes bounce-in-from-center {
    0% {
        -webkit-transform: scale(0);
        transform: scale(0);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in;
        opacity: 0
    }

    38% {
        -webkit-transform: scale(1);
        transform: scale(1);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out;
        opacity: 1
    }

    55% {
        -webkit-transform: scale(.7);
        transform: scale(.7);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in
    }

    72% {
        -webkit-transform: scale(1);
        transform: scale(1);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out
    }

    81% {
        -webkit-transform: scale(.84);
        transform: scale(.84);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in
    }

    89% {
        -webkit-transform: scale(1);
        transform: scale(1);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out
    }

    95% {
        -webkit-transform: scale(.95);
        transform: scale(.95);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in
    }

    to {
        -webkit-transform: scale(1);
        transform: scale(1);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out
    }
}

@keyframes bounce-in-from-center {
    0% {
        -webkit-transform: scale(0);
        transform: scale(0);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in;
        opacity: 0
    }

    38% {
        -webkit-transform: scale(1);
        transform: scale(1);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out;
        opacity: 1
    }

    55% {
        -webkit-transform: scale(.7);
        transform: scale(.7);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in
    }

    72% {
        -webkit-transform: scale(1);
        transform: scale(1);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out
    }

    81% {
        -webkit-transform: scale(.84);
        transform: scale(.84);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in
    }

    89% {
        -webkit-transform: scale(1);
        transform: scale(1);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out
    }

    95% {
        -webkit-transform: scale(.95);
        transform: scale(.95);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in
    }

    to {
        -webkit-transform: scale(1);
        transform: scale(1);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out
    }
}

@-webkit-keyframes bounce-in-from-top {
    0% {
        -webkit-transform: translateY(-500px);
        transform: translateY(-500px);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in;
        opacity: 0
    }

    38% {
        -webkit-transform: translateY(0);
        transform: translateY(0);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out;
        opacity: 1
    }

    55% {
        -webkit-transform: translateY(-65px);
        transform: translateY(-65px);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in
    }

    72% {
        -webkit-transform: translateY(0);
        transform: translateY(0);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out
    }

    81% {
        -webkit-transform: translateY(-28px);
        transform: translateY(-28px);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in
    }

    90% {
        -webkit-transform: translateY(0);
        transform: translateY(0);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out
    }

    95% {
        -webkit-transform: translateY(-8px);
        transform: translateY(-8px);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in
    }

    to {
        -webkit-transform: translateY(0);
        transform: translateY(0);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out
    }
}

@keyframes bounce-in-from-top {
    0% {
        -webkit-transform: translateY(-500px);
        transform: translateY(-500px);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in;
        opacity: 0
    }

    38% {
        -webkit-transform: translateY(0);
        transform: translateY(0);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out;
        opacity: 1
    }

    55% {
        -webkit-transform: translateY(-65px);
        transform: translateY(-65px);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in
    }

    72% {
        -webkit-transform: translateY(0);
        transform: translateY(0);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out
    }

    81% {
        -webkit-transform: translateY(-28px);
        transform: translateY(-28px);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in
    }

    90% {
        -webkit-transform: translateY(0);
        transform: translateY(0);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out
    }

    95% {
        -webkit-transform: translateY(-8px);
        transform: translateY(-8px);
        -webkit-animation-timing-function: ease-in;
        animation-timing-function: ease-in
    }

    to {
        -webkit-transform: translateY(0);
        transform: translateY(0);
        -webkit-animation-timing-function: ease-out;
        animation-timing-function: ease-out
    }
}

@-ms-viewport {
    width: auto !important
}

body * {
    text-rendering: optimizeLegibility;
    -webkit-font-feature-settings: "kern"1;
    font-feature-settings: "kern"1
}

body>#contentWrapper,
html,
html>body {
    background-color: #2a2a2a !important
}

body>#contentWrapper * :focus,
html * :focus,
html>body * :focus {
    outline: 0
}

body.ko * {
    word-break: keep-all
}

a:active,
a:focus,
a:hover {
    outline: 0;
    text-decoration: none
}

.fortnite-stream-overlay {
    height: 100%;
    width: 100%;
    overflow: hidden;
    position: fixed
}

.wrapper #egf {
    z-index: 0
}

#contentWrapper,
#contentWrapper>div {
    height: 100%
}

#contentWrapper .battle-pass-view {
    background-color: #fff;
    overflow: hidden
}

.wrapper {
    overflow: hidden
}

.wrapper .product-font {
    font-family: OpenSans, sans-serif
}

.wrapper .light-bg {
    background: top url(5b74e268c0f56be754b767d7e9b8cc26.html) no-repeat;
    background-size: 100%
}

.wrapper h1.site-block-page-title {
    margin-top: 0;
    padding: 2em 0;
    text-transform: uppercase;
    color: #fff;
    text-align: center
}

@media only screen and (max-width:767px) {
    .wrapper h1.site-block-page-title {
        padding: 1em 0;
        font-size: 2em
    }
}

.wrapper .site-block {
    padding: 2em;
    color: #1e1e1e;
    background-color: #f8f8f8;
    border: 1px solid #e8e8e8;
    max-width: 80%;
    margin: 1em auto;
    text-align: left;
}

@media only screen and (max-width:767px) {
    .wrapper .site-block {
        margin: .5em
    }
}

.wrapper .site-block .errorMessage {
    color: #bc0a0d
}

.wrapper .site-block .site-block-header {
    padding-bottom: 1em;
    border-bottom: 1px solid #e8e8e8;
    margin-bottom: 2em
}

.wrapper .site-block .site-block-header .site-block-title {
    margin-bottom: .5em;
    margin-top: .4em;
    font-size: 2em;
    font-weight: 400;
    text-transform: uppercase;
    text-align: center;
}

.wrapper .site-block .site-block-header .epic-logo-invert {
    background: url(c863eaaf5d8a7d8b1d95eaed3798941c.html) 50% no-repeat;
    background-size: contain;
    width: 2em;
    height: 2em
}

.wrapper .site-block .site-block-header .epic-logo {
    background: url(cb4399a7ee205610531057537937045e.html) 50% no-repeat;
    background-size: contain;
    width: 2em;
    height: 2em
}

.wrapper .site-block .site-block-footer h2 {
    font-size: 1em;
    font-weight: 200
}

.wrapper .btn-wide {
    width: 100%
}

.wrapper .dropDown-container {
    position: relative;
    text-align: center;
    cursor: pointer
}

.wrapper .dropDown-container .btn {
    position: relative;
    z-index: 1;
    margin-bottom: 0 !important
}

.wrapper .dropDown-container .btn i {
    display: inline-block;
    -webkit-transform: rotate(90deg);
    -ms-transform: rotate(90deg);
    transform: rotate(90deg);
    -webkit-transform-origin: center center;
    -ms-transform-origin: center center;
    transform-origin: center center;
    margin-left: .7em;
    font-size: .7em;
    -webkit-transition: -webkit-transform .3s ease-in-out;
    transition: -webkit-transform .3s ease-in-out;
    -o-transition: transform .3s ease-in-out;
    transition: transform .3s ease-in-out;
    transition: transform .3s ease-in-out, -webkit-transform .3s ease-in-out
}

.wrapper .dropDown-container .container-contents {
    position: absolute;
    z-index: 100;
    left: 0;
    right: 0;
    top: 0;
    width: inherit;
    margin: 0 auto;
    border: 1px solid #e8e8e8;
    background-color: #f8f8f8;
    opacity: 0;
    visibility: hidden;
    -webkit-transition: all .2s ease-in-out;
    -o-transition: all .2s ease-in-out;
    transition: all .2s ease-in-out
}

@media only screen and (max-width:767px) {
    .wrapper .dropDown-container .container-contents {
        width: 100%;
        max-width: 100%
    }
}

.wrapper .dropDown-container .container-contents a {
    font-family: OpenSans, sans-serif;
    font-size: .8em;
    font-weight: 700;
    color: #000;
    display: block;
    width: 100%;
    height: 100%;
    padding: .75em 0;
    -webkit-transition: color .3s ease-in-out;
    -o-transition: color .3s ease-in-out;
    transition: color .3s ease-in-out
}

.wrapper .dropDown-container .container-contents a span {
    white-space: normal
}

.wrapper .dropDown-container .container-contents a:hover {
    color: #000
}

.wrapper .dropDown-container.active .btn i {
    -webkit-transform: rotate(-90deg) !important;
    -ms-transform: rotate(-90deg) !important;
    transform: rotate(-90deg) !important
}

.wrapper .dropDown-container.active .container-contents {
    opacity: 1;
    visibility: visible;
    top: 100%
}

.wrapper .loading {
    position: relative;
    margin: 50px auto;
    text-align: center;
    min-height: 80px;
    background: url(ef532e79e05e2d24a0f6332068f3a61b.html) 50% no-repeat #fff;
    background-size: contain;
    background-color: transparent;
    height: 100%;
    width: 100%
}

.wrapper.msie .btn:after {
    -webkit-animation: none !important;
    animation: none !important
}

.launcherClient {
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none
}

.launcherClient ::-webkit-scrollbar {
    width: 8px;
    height: 18px
}

.launcherClient ::-webkit-scrollbar-track {
    background: #bbb;
    border-radius: 50px
}

.launcherClient ::-webkit-scrollbar-thumb {
    background: #999;
    border-radius: 50px
}

.launcherClient ::-webkit-scrollbar-thumb:horizontal:hover,
.launcherClient ::-webkit-scrollbar-thumb:vertical:hover {
    background: #666
}

.launcherClient ::-webkit-scrollbar-track:hover {
    background: #bbb
}

.launcherClient ::-webkit-scrollbar-button {
    width: 8px;
    height: 13px;
    display: block
}

.launcherClient ::-webkit-scrollbar-corner {
    background-color: #fff
}

.launcherClient .page-transition-appear,
.launcherClient .page-transition-appear.page-transition-appear-active,
.launcherClient .page-transition-enter,
.launcherClient .page-transition-enter.page-transition-enter-active {
    opacity: 1;
    -webkit-transform: none;
    -ms-transform: none;
    transform: none;
    -webkit-transition: none;
    -o-transition: none;
    transition: none
}

.launcherClient #contentWrapper {
    background: #fff;
    height: 100vh !important;
    padding: 0 5px 0 0;
    margin: 0 12px 0 0;
    overflow-y: auto !important;
    overflow-x: hidden !important;
    position: absolute;
    width: calc(100% - 12px);
    z-index: 1
}

.launcherClient #contentWrapper .epic-games-nav-spacer {
    height: 0
}

.launcherClient #contentWrapper #egh.fortnite nav {
    right: 24px
}

.launcherClient #contentWrapper .wrapper #footer {
    padding-bottom: 40px
}

.launcherClient #contentWrapper .wrapper #footer #footerSocial {
    display: none
}

.disable-hover .external-link,
.disable-hover .media,
.disable-hover a,
.disable-hover article,
.disable-hover img,
.disable-hover strong {
    pointer-events: none !important
}

.grab-hand,
.grab-hand a {
    cursor: -webkit-grabbing !important
}

.ReactModal__Overlay {
    background-color: rgba(0, 0, 0, .2) !important
}

.gradient {
    background: #2a2c31;
    background: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxIDEiIHByZXNlcnZlQXNwZWN0UmF0aW89Im5vbmUiPjxsaW5lYXJHcmFkaWVudCBpZD0iYSIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiIHgxPSIwJSIgeTE9IjAlIiB4Mj0iMCUiIHkyPSIxMDAlIj48c3RvcCBvZmZzZXQ9IjAlIiBzdG9wLWNvbG9yPSIjMmEyYzMxIi8+PHN0b3Agb2Zmc2V0PSIxMDAlIiBzdG9wLWNvbG9yPSIjMDgwNzA4Ii8+PC9saW5lYXJHcmFkaWVudD48cGF0aCBmaWxsPSJ1cmwoI2EpIiBkPSJNMCAwaDF2MUgweiIvPjwvc3ZnPg==);
    background: -webkit-gradient(linear, left top, left bottom, color-stop(0, #2a2c31), color-stop(100%, #080708));
    background: -webkit-linear-gradient(top, #2a2c31, #080708);
    background: -o-linear-gradient(top, #2a2c31 0, #080708 100%);
    background: -webkit-gradient(linear, left top, left bottom, from(#2a2c31), to(#080708));
    background: linear-gradient(180deg, #2a2c31 0, #080708);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#2a2c31", endColorstr="#080708", GradientType=0)
}

.wrapper,
.wrapper>div {
    position: relative
}

.wrapper h1,
.wrapper h2,
.wrapper h3,
.wrapper h4,
.wrapper h5,
.wrapper h6 {
    font-family: BurbankBigRegular-Black, sans-serif;
    text-transform: uppercase
}

.wrapper h1 {
    font-size: 2.75em;
    line-height: 85%
}

@media only screen and (max-width:1199px) {
    .wrapper h1 {
        font-size: 2em
    }
}

.wrapper h2 {
    font-size: 1.875em;
    line-height: 85%
}

@media only screen and (max-width:1199px) {
    .wrapper h2 {
        font-size: 1.25em
    }
}

.wrapper h3 {
    font-size: 1.375em
}

.wrapper h4 {
    font-size: 1.125em
}

.wrapper h5 {
    font-size: 1em
}

.wrapper h6 {
    font-size: .875em
}

.wrapper hr {
    border-top: 1px solid #b3b3b3
}

.wrapper .jumbotron {
    margin-bottom: 0;
    padding-left: 0;
    padding-right: 0;
    background-color: transparent
}

.wrapper .jumbotron h1 {
    font-size: 5em
}

@media only screen and (max-width:1199px) {
    .wrapper .jumbotron h1 {
        font-size: 3em
    }
}

.wrapper .jumbotron h2 {
    font-size: 4em
}

@media only screen and (max-width:1199px) {
    .wrapper .jumbotron h2 {
        font-size: 2.5em
    }
}

.wrapper .jumbotron h3 {
    font-size: 2.75em
}

@media only screen and (max-width:1199px) {
    .wrapper .jumbotron h3 {
        font-size: 2em
    }
}

.wrapper .jumbotron h4 {
    font-size: 1.75em
}

.wrapper .jumbotron h5 {
    font-size: 1.125em
}

@media only screen and (max-width:1199px) {
    .wrapper .jumbotron h5 {
        font-size: 1em
    }
}

.wrapper .jumbotron h6 {
    font-size: 1em
}

.wrapper a,
.wrapper ol,
.wrapper p,
.wrapper ul {
    font-family: OpenSans, sans-serif;
    font-weight: 400;
    font-size: .9em;
    line-height: 1.75
}

.wrapper a {
    color: #1db8f3;
    text-decoration: none;
    -webkit-transition: color .3s ease-in-out;
    -o-transition: color .3s ease-in-out;
    transition: color .3s ease-in-out
}

.wrapper a:hover {
    color: #0cadea
}

.wrapper .play-button {
    position: relative;
    width: 6.25em;
    height: 3.609em;
    background-color: transparent;
    margin: 0 auto 3em;
    border-left: .412em solid #fff;
    border-right: .412em solid #fff;
    cursor: pointer;
    -webkit-transition: border .3s ease-in-out;
    -o-transition: border .3s ease-in-out;
    transition: border .3s ease-in-out
}

.wrapper .play-button:hover {
    border-color: #ff0
}

.wrapper .play-button:hover i {
    color: #ff0
}

.wrapper .play-button:hover:after,
.wrapper .play-button:hover:before {
    border-color: #ff0
}

.wrapper .play-button.sm {
    display: inline-block;
    width: 1.875em;
    height: 1.083em;
    margin: .541em 0;
    border-left: .188em solid #fff;
    border-right: .188em solid #fff
}

@media only screen and (max-width:767px) {
    .wrapper .play-button.sm {
        width: 1.775em
    }
}

.wrapper .play-button.sm:hover i {
    color: #fff
}

.wrapper .play-button.sm:after,
.wrapper .play-button.sm:before {
    width: 1.326em;
    height: 1.326em;
    -webkit-transform: scaleY(.5774) rotate(-45deg);
    -ms-transform: scaleY(.5774) rotate(-45deg);
    transform: scaleY(.5774) rotate(-45deg);
    left: .087em
}

.wrapper .play-button.sm:before {
    top: -.663em;
    border-top: .265em solid #fff;
    border-right: .265em solid #fff
}

.wrapper .play-button.sm:after {
    bottom: -.663em;
    border-bottom: .265em solid #fff;
    border-left: .265em solid #fff
}

.wrapper .play-button.sm i {
    font-size: .9em;
    padding-top: .125em
}

@media only screen and (max-width:767px) {
    .wrapper .play-button.sm i {
        padding-top: .25em
    }
}

.wrapper .play-button.md {
    width: 80px;
    height: 46.19px
}

.wrapper .play-button.md:after,
.wrapper .play-button.md:before {
    width: 56.57px;
    height: 56.57px;
    left: 6.7px
}

.wrapper .play-button.md:before {
    top: -28.2843px
}

.wrapper .play-button.md:after {
    bottom: -28.2843px
}

.wrapper .play-button.md i {
    padding-top: .55em;
    padding-left: .1em
}

.wrapper .play-button:after,
.wrapper .play-button:before {
    content: "";
    position: absolute;
    z-index: 1;
    width: 4.419em;
    height: 4.419em;
    -webkit-transform: scaleY(.5774) rotate(-45deg);
    -ms-transform: scaleY(.5774) rotate(-45deg);
    transform: scaleY(.5774) rotate(-45deg);
    background-color: inherit;
    left: .603em;
    -webkit-transition: border .3s ease-in-out;
    -o-transition: border .3s ease-in-out;
    transition: border .3s ease-in-out
}

.wrapper .play-button:before {
    top: -2.225em;
    border-top: .442em solid #fff;
    border-right: .442em solid #fff
}

.wrapper .play-button:after {
    bottom: -2.225em;
    border-bottom: .442em solid #fff;
    border-left: .442em solid #fff
}

.wrapper .play-button i {
    font-size: 1.5em;
    display: block;
    padding-top: .75em;
    text-align: center;
    color: #fff;
    -webkit-transition: color .3s ease-in-out;
    -o-transition: color .3s ease-in-out;
    transition: color .3s ease-in-out
}

.wrapper .btn {
    position: relative;
    border: 0;
    border-radius: 0;
    line-height: 2;
    z-index: 1;
    font-family: BurbankBigRegular-Black, sans-serif;
    font-size: 1em;
    text-transform: uppercase;
    padding: .25em 1em;
    -webkit-transform: translateZ(0);
    transform: translateZ(0);
    letter-spacing: 0
}

.wrapper .btn.btn-xs {
    height: 3em;
    line-height: 2.25em;
    padding: .4em 1em
}

.wrapper .btn.btn-block {
    display: block
}

.wrapper .btn.btn-inline {
    display: inline-block
}

.wrapper .btn.btn-info {
    font-family: BurbankBigCondensed-Black, sans-serif;
    font-size: 1.25em;
    color: #000;
    background-color: #fff;
    border: none;
    text-decoration: none;
    -webkit-transition: background-color .3s ease;
    -o-transition: background-color .3s ease;
    transition: background-color .3s ease;
    -webkit-clip-path: polygon(0 0, 100% 10%, 98% 90%, 2% 100%);
    clip-path: polygon(0 0, 100% 10%, 98% 90%, 2% 100%);
    padding: .75em
}

.wrapper .btn.btn-border {
    background-image: url('data:image/svg+xml;charset=utf-8,<svg xmlns="http://www.w3.org/2000/svg" width="278" height="70"><path d="M.24 5.44l278-5-7 67-268 3zm270 2L6 9.44l4.58 52 255.7 2z" fill="%23fff"/></svg>');
    background-repeat: no-repeat;
    background-size: contain;
    background-color: transparent;
    background-position: 50%;
    font-size: 1.875em
}

.wrapper .btn.btn-border,
.wrapper .btn.btn-border span {
    color: #fff;
    -webkit-transition: all .3s ease-in-out;
    -o-transition: all .3s ease-in-out;
    transition: all .3s ease-in-out
}

.wrapper .btn.btn-border:hover {
    background-image: url('data:image/svg+xml;charset=utf-8,<svg xmlns="http://www.w3.org/2000/svg" width="278" height="70"><path d="M.24 5.44l278-5-7 67-268 3zm270 2L6 9.44l4.58 52 255.7 2z" fill="%23ff0"/></svg>')
}

.wrapper .btn.btn-border:hover span {
    color: #ff0
}

@media only screen and (max-width:767px) {
    .wrapper .btn.btn-border {
        padding: .25em 1em
    }
}

.wrapper .btn.btn-default {
    font-size: 1.5em;
    color: #fff;
    background-color: #2c82c5;
    border: none;
    padding: 0 1.5em;
    text-decoration: none;
    -webkit-transition: background-color .3s ease;
    -o-transition: background-color .3s ease;
    transition: background-color .3s ease
}

.wrapper .btn.btn-default:hover {
    background-color: #3be1ff;
    text-decoration: none
}

.wrapper .btn.btn-display {
    position: relative;
    font-size: 1.5em;
    padding: 0 1.5em;
    color: #000;
    margin-top: .5em;
    background: transparent
}

.wrapper .btn.btn-display span {
    position: relative;
    z-index: 1
}

.wrapper .btn.btn-display:after {
    content: "";
    display: block;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 2em;
    background-color: #ff0;
    -webkit-transition: background-color .3s ease-in-out;
    -o-transition: background-color .3s ease-in-out;
    transition: background-color .3s ease-in-out;
    -webkit-box-shadow: 0 4px 12px -4px rgba(0, 0, 0, .5);
    box-shadow: 0 4px 12px -4px rgba(0, 0, 0, .5);
    -webkit-animation: jelly 6s ease-in-out infinite;
    animation: jelly 6s ease-in-out infinite;
    -webkit-transform-origin: 50% 50% 20px;
    -ms-transform-origin: 50% 50% 20px;
    transform-origin: 50% 50% 20px
}

.wrapper .btn.btn-display:hover:after {
    background-color: #e6e600
}

.wrapper .btn.btn-display.no-animate:after {
    -webkit-animation: none;
    animation: none;
    -webkit-clip-path: polygon(0 4%, 100% 0, 100% 100%, 0 100%);
    clip-path: polygon(0 4%, 100% 0, 100% 100%, 0 100%)
}

.wrapper .btn.btn-primary {
    font-size: 2.5em;
    color: #000 !important;
    background-color: #ff0 !important;
    border: none;
    padding: 0 1.5em;
    text-decoration: none;
    -webkit-transition: background-color .3s ease;
    -o-transition: background-color .3s ease;
    transition: background-color .3s ease;
}

.wrapper .btn.btn-primary:hover {
    background-color: #dcdc00 !important;
}

.wrapper .btn.btn-hover-transform {
    -webkit-clip-path: polygon(2% 0, 98% 0, 98% 100%, 2% 100%);
    clip-path: polygon(2% 0, 98% 0, 98% 100%, 2% 100%)
}

.wrapper .btn.btn-hover-transform,
.wrapper .btn.btn-hover-transform>span {
    -webkit-transition: all .3s ease-in-out;
    -o-transition: all .3s ease-in-out;
    transition: all .3s ease-in-out
}

.wrapper .btn.btn-hover-transform>span {
    display: inline-block
}

.wrapper .btn.btn-hover-transform:hover {
    -webkit-clip-path: polygon(4% 0, 100% 0, 98% 100%, 2% 100%);
    clip-path: polygon(4% 0, 100% 0, 98% 100%, 2% 100%)
}

.wrapper .btn.btn-hover-transform:hover>span {
    -webkit-transform: translateX(2%);
    -ms-transform: translateX(2%);
    transform: translateX(2%)
}

.wrapper .btn.btn-fixed-width {
    min-width: 260px
}

.wrapper .btn.disabled {
    background-color: #ccc;
    color: grey;
    border-color: #ccc
}

.wrapper .btn.disabled:hover {
    color: grey !important
}

.wrapper .btn>span {
    pointer-events: none
}

.wrapper .btn-hex+.btn-hex {
    margin-top: 5px
}

.wrapper .fade-appear {
    opacity: .01
}

.wrapper .fade-appear.fade-appear-active {
    opacity: 1;
    -webkit-transition: opacity .3s ease-in-out;
    -o-transition: opacity .3s ease-in-out;
    transition: opacity .3s ease-in-out
}

.wrapper .transition-enter {
    opacity: .01
}

.wrapper .transition-enter.transition-enter-active {
    opacity: 1;
    -webkit-transition: opacity .3s ease-in;
    -o-transition: opacity .3s ease-in;
    transition: opacity .3s ease-in
}

.wrapper .transition-leave {
    opacity: 1
}

.wrapper .transition-leave.transition-leave-active {
    opacity: .01;
    -webkit-transition: opacity .15s ease-in;
    -o-transition: opacity .15s ease-in;
    transition: opacity .15s ease-in
}

.wrapper .no-padding {
    padding-left: 0 !important;
    padding-right: 0 !important
}

.wrapper .iosButton {
    width: 15em;
    height: 4em;
    background: url(data:image/svg+xml;base64,PHN2ZyBpZD0ibGl2ZXR5cGUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgdmlld0JveD0iMCAwIDE2OC42NyA1Ni4zOCI+PGRlZnM+PHN0eWxlPi5jbHMtMntmaWxsOiNmZmZ9PC9zdHlsZT48L2RlZnM+PHBhdGggZD0iTTE1Ni42Ni40OEgxMy4zMkwxMiAuNWExOCAxOCAwIDAwLTIuOC4yNSA5LjE3IDkuMTcgMCAwMC0yLjY4Ljg4IDkuMDcgOS4wNyAwIDAwLTIuMjggMS42NiA5LjE1IDkuMTUgMCAwMC0yLjU0IDUgMTcuOCAxNy44IDAgMDAtLjI1IDIuODJWNDYuM2ExNy44IDE3LjggMCAwMC4yNSAyLjgyIDkuMDcgOS4wNyAwIDAwLjg4IDIuNjhBOC44OSA4Ljg5IDAgMDA0LjI0IDU0YTkuMDcgOS4wNyAwIDAwMi4yOCAxLjcgOS41IDkuNSAwIDAwMi42OC44OSAxOS4zMiAxOS4zMiAwIDAwMi44My4yNWgxNDcuNDZhMTkuMDYgMTkuMDYgMCAwMDIuODItLjI1IDkuNjcgOS42NyAwIDAwMi42OS0uODkgOS4wNyA5LjA3IDAgMDAyLjI4LTEuNyA4Ljg5IDguODkgMCAwMDEuNjYtMi4yOCA5LjA3IDkuMDcgMCAwMC44OC0yLjY4IDIwLjUzIDIwLjUzIDAgMDAuMjYtMi44MlY0NSAxMy45MnYtMi44NGEyMC41MyAyMC41MyAwIDAwLS4yNi0yLjgyIDkuMTUgOS4xNSAwIDAwLTIuNTQtNUE5LjA3IDkuMDcgMCAwMDE2NSAxLjYzYTkuMzMgOS4zMyAwIDAwLTIuNjktLjg4IDE3LjggMTcuOCAwIDAwLTIuODItLjI1aC0xLjN6IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMS40MiAtLjQ4KSIgZmlsbD0iI2I3YjdiNyIvPjxwYXRoIGQ9Ik0xMy4zMyA1NS42MmgtMS4yOGExOCAxOCAwIDAxLTIuNjMtLjIzIDguNTggOC41OCAwIDAxLTIuMzQtLjc3IDggOCAwIDAxLTItMS40NCA3LjQ4IDcuNDggMCAwMS0xLjQzLTIgOCA4IDAgMDEtLjc3LTIuMzQgMTYuNjQgMTYuNjQgMCAwMS0uMjMtMi42NFYxMi4zOHYtMS4yNmExNi40NSAxNi40NSAwIDAxLjIzLTIuNjQgOC4xNCA4LjE0IDAgMDEuNzYtMi4zNCA3LjYzIDcuNjMgMCAwMTEuNDQtMiA3Ljc4IDcuNzggMCAwMTItMS40NUE4LjYxIDguNjEgMCAwMTkuNDEgMmExNy45MiAxNy45MiAwIDAxMi42NS0uMjNoMTQ3LjQxYTE3LjU1IDE3LjU1IDAgMDEyLjYyLjIzIDguNDkgOC40OSAwIDAxMi4zNi43NyA3LjgzIDcuODMgMCAwMTIgMS40MyA3LjkyIDcuOTIgMCAwMTEuNDQgMiA4LjA5IDguMDkgMCAwMS43NSAyLjMyIDE3LjU2IDE3LjU2IDAgMDEuMjUgMi42NlY0Ni4zYTE4LjM2IDE4LjM2IDAgMDEtLjI0IDIuNjIgOC41MiA4LjUyIDAgMDEtLjc2IDIuMzUgNy43NiA3Ljc2IDAgMDEtMS40NCAxLjk1IDcuNTEgNy41MSAwIDAxLTIgMS40NCA4LjEzIDguMTMgMCAwMS0yLjM1Ljc4IDE3Ljg5IDE3Ljg5IDAgMDEtMi42My4yM0gxMy4zM3oiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC0xLjQyIC0uNDgpIi8+PGcgaWQ9Il9Hcm91cF8iIGRhdGEtbmFtZT0iJmx0O0dyb3VwJmd0OyI+PGcgaWQ9Il9Hcm91cF8yIiBkYXRhLW5hbWU9IiZsdDtHcm91cCZndDsiPjxnIGlkPSJfR3JvdXBfMyIgZGF0YS1uYW1lPSImbHQ7R3JvdXAmZ3Q7Ij48cGF0aCBpZD0iX1BhdGhfIiBkYXRhLW5hbWU9IiZsdDtQYXRoJmd0OyIgY2xhc3M9ImNscy0yIiBkPSJNMzYuMzQgMjkuMDlhNyA3IDAgMDEzLjMyLTUuODUgNy4xMiA3LjEyIDAgMDAtNS42My0zYy0yLjM2LS4yNS00LjY2IDEuNDEtNS44NyAxLjQxcy0zLjA4LTEuMzktNS4wOC0xLjM1YTcuNSA3LjUgMCAwMC02LjMxIDMuODVjLTIuNzIgNC43Mi0uNjkgMTEuNjUgMS45MiAxNS40NyAxLjMxIDEuODcgMi44NCA0IDQuODMgMy44OHMyLjY5LTEuMjUgNS4wNS0xLjI1IDMgMS4yNSA1LjA2IDEuMiAzLjQyLTEuODcgNC42OC0zLjc2YTE1LjI2IDE1LjI2IDAgMDAyLjE0LTQuMzYgNi43NCA2Ljc0IDAgMDEtNC4xMS02LjI0eiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTEuNDIgLS40OCkiLz48cGF0aCBpZD0iX1BhdGhfMiIgZGF0YS1uYW1lPSImbHQ7UGF0aCZndDsiIGNsYXNzPSJjbHMtMiIgZD0iTTMyLjQ5IDE3LjY5YTYuODkgNi44OSAwIDAwMS41Ny00LjkyIDcgNyAwIDAwLTQuNTIgMi4zNCA2LjU0IDYuNTQgMCAwMC0xLjYyIDQuNzMgNS43OSA1Ljc5IDAgMDA0LjU3LTIuMTV6IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMS40MiAtLjQ4KSIvPjwvZz48L2c+PHBhdGggY2xhc3M9ImNscy0yIiBkPSJNNjEuMDUgMzguNzNoLTYuNjdsLTEuNiA0LjczSDUwTDU2LjI3IDI2aDIuOTRsNi4zMiAxNy41aC0yLjg4em0tNi0yLjE4aDUuMjlsLTIuNjEtNy42OGgtLjA3ek03OS4xNyAzNy4wOGMwIDQtMi4xMiA2LjUxLTUuMzIgNi41MWE0LjM0IDQuMzQgMCAwMS00LTIuMjNoLS4wNnY2LjMyaC0yLjY0di0xN2gyLjU0djIuMTJhNC41MSA0LjUxIDAgMDE0LjA2LTIuMjVjMy4yNS4wMiA1LjQyIDIuNTggNS40MiA2LjUzem0tMi42OSAwYzAtMi41OC0xLjMzLTQuMjgtMy4zNy00LjI4cy0zLjM1IDEuNzMtMy4zNSA0LjI4IDEuMzUgNC4yOSAzLjM1IDQuMjkgMy4zNy0xLjY4IDMuMzctNC4yOXpNOTMuMjIgMzcuMDhjMCA0LTIuMTIgNi41MS01LjMzIDYuNTFhNC4zMiA0LjMyIDAgMDEtNC0yLjIzaC0uMDZ2Ni4zMkg4MS4ydi0xN2gyLjUzdjIuMTJhNC41MyA0LjUzIDAgMDE0LjA3LTIuMjVjMy4yOC4wMiA1LjQyIDIuNTggNS40MiA2LjUzem0tMi42OSAwYzAtMi41OC0xLjM0LTQuMjgtMy4zOC00LjI4cy0zLjM0IDEuNzMtMy4zNCA0LjI4IDEuMzQgNC4yOSAzLjM0IDQuMjkgMy4zOC0xLjY4IDMuMzgtNC4yOXpNMTAyLjUgMzguNThjLjIgMS43NCAxLjg4IDIuODggNC4xOSAyLjg4czMuNzktMS4xNCAzLjc5LTIuN2MwLTEuMzYtMS0yLjE4LTMuMjItMi43M2wtMi4yNi0uNTVjLTMuMjItLjc4LTQuNzEtMi4yOC00LjcxLTQuNzIgMC0zIDIuNjMtNS4wOSA2LjM3LTUuMDlzNi4yNCAyLjA3IDYuMzIgNS4wOWgtMi42NGMtLjE2LTEuNzUtMS42MS0yLjgtMy43Mi0yLjhzLTMuNTUgMS4wNy0zLjU1IDIuNjJjMCAxLjI0LjkyIDIgMy4xOCAyLjUybDEuOTMuNDhjMy41OS44NCA1LjA4IDIuMjkgNS4wOCA0Ljg1IDAgMy4yNy0yLjYxIDUuMzItNi43NiA1LjMyLTMuODggMC02LjUtMi02LjY3LTUuMTd6TTExOC45IDI3LjY4djNoMi40M3YyLjA3aC0yLjQzdjdjMCAxLjA5LjQ5IDEuNiAxLjU2IDEuNi4yNiAwIC42OSAwIC44Ni0uMDZ2Mi4wNmE2Ljc5IDYuNzkgMCAwMS0xLjQ2LjEyYy0yLjU4IDAtMy41OS0xLTMuNTktMy40NHYtNy4yNmgtMS44NVYzMC43aDEuODV2LTN6TTEyMi43NCAzNy4wOGMwLTQgMi4zNi02LjU0IDYtNi41NHM2LjA1IDIuNTMgNi4wNSA2LjU0LTIuMzQgNi41NC02LjA1IDYuNTQtNi0yLjUxLTYtNi41NHptOS40MyAwYzAtMi43NS0xLjI2LTQuMzgtMy4zOC00LjM4cy0zLjM5IDEuNjQtMy4zOSA0LjM4IDEuMjcgNC4zOCAzLjM5IDQuMzggMy4zOC0xLjYxIDMuMzgtNC4zOHpNMTM3IDMwLjdoMi41djIuMTdoLjA2YTMgMyAwIDAxMy4wNy0yLjMgNC43MyA0LjczIDAgMDEuOS4wOXYyLjQ1YTMuOTIgMy45MiAwIDAwLTEuMTgtLjE1IDIuNjQgMi42NCAwIDAwLTIuNzMgMi45M3Y3LjU3SDEzN3pNMTU1LjYgMzkuNzFjLS4zNSAyLjMyLTIuNiAzLjkxLTUuNDkgMy45MS0zLjcxIDAtNi0yLjQ5LTYtNi40OHMyLjMyLTYuNiA1LjkxLTYuNiA1Ljc1IDIuNDMgNS43NSA2LjN2LjloLTl2LjE1YTMuMzIgMy4zMiAwIDAwMy40MyAzLjYyIDIuODggMi44OCAwIDAwMy0xLjh6bS04Ljg1LTMuODFoNi4zOGEzLjA2IDMuMDYgMCAwMC0zLjEzLTMuMjMgMy4yMiAzLjIyIDAgMDAtMy4yNSAzLjIzeiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTEuNDIgLS40OCkiLz48L2c+PGcgaWQ9Il9Hcm91cF80IiBkYXRhLW5hbWU9IiZsdDtHcm91cCZndDsiPjxwYXRoIGNsYXNzPSJjbHMtMiIgZD0iTTU0Ljc0IDEyLjc4YzIuNSAwIDQgMS41NCA0IDQuMThzLTEuNDUgNC4yMy00IDQuMjNoLTN2LTguNDF6TTUzIDIwaDEuNmMxLjc1IDAgMi43Ny0xLjA5IDIuNzctM3MtMS0zLTIuNzctM0g1M3pNNjAuMTcgMThjMC0yIDEuMTUtMy4zIDMtMy4zczMgMS4yNSAzIDMuMy0xLjE0IDMuMy0zIDMuMy0zLTEuMjMtMy0zLjN6bTQuNyAwYzAtMS4zOC0uNjItMi4xOC0xLjctMi4xOHMtMS43LjgtMS43IDIuMTguNjEgMi4xOCAxLjcgMi4xOCAxLjctLjc4IDEuNy0yLjE4ek03NC4xMiAyMS4xOWgtMS4zbC0xLjMxLTQuNjdoLS4xbC0xLjMxIDQuNjdoLTEuMjlsLTEuNzQtNi4zNGgxLjI3bDEuMTMgNC44NGguMWwxLjMtNC44NGgxLjJsMS4zMSA0Ljg0aC4xbDEuMTMtNC44NGgxLjI1ek03Ny4zMyAxNC44NWgxLjIxdjFoLjA5YTEuOTEgMS45MSAwIDAxMS45LTEuMTMgMi4wNiAyLjA2IDAgMDEyLjE5IDIuMzZ2NC4xMWgtMS4yNVYxNy40YzAtMS0uNDQtMS41My0xLjM3LTEuNTNhMS40NiAxLjQ2IDAgMDAtMS41MiAxLjYxdjMuNzFoLTEuMjV6TTg0LjcyIDEyLjM3SDg2djguODJoLTEuMjh6TTg3LjcxIDE4YzAtMiAxLjE1LTMuMyAzLTMuM3MzIDEuMjUgMyAzLjMtMS4xNCAzLjMtMyAzLjMtMy0xLjIzLTMtMy4zem00LjcgMGMwLTEuMzgtLjYyLTIuMTgtMS43LTIuMThTODkgMTYuNjQgODkgMThzLjYxIDIuMTggMS43IDIuMTggMS43MS0uNzggMS43MS0yLjE4ek05NSAxOS40YzAtMS4xNC44NS0xLjggMi4zNi0xLjlsMS43Mi0uMXYtLjU0YzAtLjY3LS40NS0xLTEuMy0xLS43IDAtMS4xOC4yNS0xLjMyLjdoLTEuMmMuMTMtMS4wOSAxLjE2LTEuNzkgMi42LTEuNzkgMS41OSAwIDIuNDkuOCAyLjQ5IDIuMTR2NC4zM2gtMS4yMXYtLjk0SDk5YTIuMTMgMi4xMyAwIDAxLTEuOTEgMUExLjkxIDEuOTEgMCAwMTk1IDE5LjR6bTQuMDgtLjU0di0uNTNsLTEuNTUuMDljLS44OC4wNi0xLjI3LjM2LTEuMjcuOTJzLjQ5LjkgMS4xNy45YTEuNSAxLjUgMCAwMDEuNjctMS4zOHpNMTAyIDE4YzAtMiAxLTMuMjggMi42NC0zLjI4YTIuMDggMi4wOCAwIDAxMS45NCAxLjExaC4xdi0zLjQ2aDEuMjV2OC44MmgtMS4ydi0xaC0uMWEyLjIxIDIuMjEgMCAwMS0yIDEuMTFDMTAzIDIxLjMgMTAyIDIwIDEwMiAxOHptMS4zIDBjMCAxLjM0LjYzIDIuMTUgMS42OSAyLjE1czEuNzEtLjgyIDEuNzEtMi4xNS0uNy0yLjEzLTEuNy0yLjEzLTEuNzEuODEtMS43MSAyLjEzek0xMTMuMSAxOGMwLTIgMS4xNC0zLjMgMy0zLjNzMyAxLjI1IDMgMy4zLTEuMTQgMy4zLTMgMy4zLTMtMS4yMy0zLTMuM3ptNC43IDBjMC0xLjM4LS42Mi0yLjE4LTEuNy0yLjE4cy0xLjcuOC0xLjcgMi4xOC42MSAyLjE4IDEuNyAyLjE4IDEuNy0uNzggMS43LTIuMTh6TTEyMC43NyAxNC44NUgxMjJ2MWguMWExLjkxIDEuOTEgMCAwMTEuOS0xLjEzIDIuMDYgMi4wNiAwIDAxMi4yIDIuMzZ2NC4xMWgtMS4yNVYxNy40YzAtMS0uNDUtMS41My0xLjM3LTEuNTNhMS40NiAxLjQ2IDAgMDAtMS41OCAxLjYxdjMuNzFoLTEuMjV6TTEzMy4yNCAxMy4yN3YxLjZoMS4zN3YxLjA2aC0xLjM3djMuMjZjMCAuNjcuMjcgMSAuODkgMWEzLjUzIDMuNTMgMCAwMC40OCAwdjFhMy41NSAzLjU1IDAgMDEtLjY4LjA3Yy0xLjM5IDAtMi0uNDktMi0xLjcydi0zLjYxaC0xdi0xLjA2aDF2LTEuNnpNMTM2LjMyIDEyLjM3aDEuMjR2My41aC4xYTIgMiAwIDAxMS45NC0xLjE0IDIuMDkgMi4wOSAwIDAxMi4xOCAyLjM3djQuMDloLTEuMjVWMTcuNGMwLTEtLjQ3LTEuNTItMS4zNi0xLjUyYTEuNDggMS40OCAwIDAwLTEuNTkgMS42MXYzLjdoLTEuMjZ6TTE0OS4wOSAxOS40OGEyLjU4IDIuNTggMCAwMS0yLjc1IDEuODRjLTEuODIgMC0yLjkzLTEuMjUtMi45My0zLjI4czEuMTMtMy4zMiAyLjkyLTMuMzIgMi44MyAxLjIxIDIuODMgMy4ydi40NGgtNC40OHYuMDdhMS42OCAxLjY4IDAgMDAxLjY5IDEuODIgMS41MyAxLjUzIDAgMDAxLjUxLS43N3ptLTQuNDEtMi4wNWgzLjIxYTEuNTMgMS41MyAwIDAwLTEuNTYtMS42NCAxLjYyIDEuNjIgMCAwMC0xLjY1IDEuNjR6IiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMS40MiAtLjQ4KSIvPjwvZz48L3N2Zz4=) no-repeat 50%;
    background-size: contain;
    margin: 0 auto
}

.page-transition-appear {
    opacity: .01
}

.page-transition-appear.page-transition-appear-active {
    opacity: 1;
    -webkit-transition: opacity .4s ease-out;
    -o-transition: opacity .4s ease-out;
    transition: opacity .4s ease-out
}

.page-transition-enter {
    overflow: hidden;
    opacity: .75;
    -webkit-transform: scale(1.025);
    -ms-transform: scale(1.025);
    transform: scale(1.025);
    -webkit-transform-origin: top center;
    -ms-transform-origin: top center;
    transform-origin: top center
}

.page-transition-enter.page-transition-enter-active {
    opacity: 1;
    -webkit-transform: scale(1);
    -ms-transform: scale(1);
    transform: scale(1);
    -webkit-transition: opacity .2s linear, -webkit-transform .4s ease;
    transition: opacity .2s linear, -webkit-transform .4s ease;
    -o-transition: transform .4s ease, opacity .2s linear;
    transition: transform .4s ease, opacity .2s linear;
    transition: transform .4s ease, opacity .2s linear, -webkit-transform .4s ease
}

#epicEuCookie.eu-cookie-msg {
    border: 1px solid #e8e8e8;
    background: #f8f8f8;
    color: #1e1e1e;
    bottom: 45px;
    right: 45px
}

#epicEuCookie.eu-cookie-msg a {
    color: #ff0
}

#epicEuCookie.eu-cookie-msg .eu-cookie-close {
    text-transform: uppercase;
    background-color: #ff0
}

#epicEuCookie.eu-cookie-msg .eu-cookie-close:hover {
    background-color: #e6e600
}

body.ar #epicEuCookie {
    direction: rtl;
    text-align: right
}

.ru .wrapper .blog-view-container .blog-view .grid-item .grid-content .title,
.ru .wrapper .btn,
.ru .wrapper .edition-section .edition-pack-wrapper .edition-pack .actual-price,
.ru .wrapper .edition-section .edition-pack-wrapper .edition-pack .content-wrapper .content,
.ru .wrapper .edition-section .edition-pack-wrapper .edition-pack .content-wrapper .content ul,
.ru .wrapper .edition-section .edition-pack-wrapper .edition-pack .old-price,
.ru .wrapper .edition-section .edition-pack-wrapper .edition-pack .pack-buy-button button,
.ru .wrapper .edition-section .edition-pack-wrapper .edition-pack .price,
.ru .wrapper .edition-section .edition-pack-wrapper .edition-pack .verb,
.ru .wrapper .edition-section .edition-pack-wrapper .edition-pack h3,
.ru .wrapper .help-center-wrapper .section-container .section-body,
.ru .wrapper .home-card .caption .home-battle-pass,
.ru .wrapper h1,
.ru .wrapper h2,
.ru .wrapper h3,
.ru .wrapper h4,
.ru .wrapper h5,
.ru .wrapper h6 {
    font-family: BurbankBigCondensed-Black, sans-serif
}

.ru #egh .siteNavKids li a,
.ru #egh .siteNav li a {
    max-height: unset
}

.ja .wrapper:not(.switch),
.ja .wrapper:not(.switch) a,
.ja .wrapper:not(.switch) ol,
.ja .wrapper:not(.switch) p,
.ja .wrapper:not(.switch) ul {
    font-family: NotoSansCJKjp, sans-serif
}

.ja .wrapper h1,
.ja .wrapper h2,
.ja .wrapper h3,
.ja .wrapper h4,
.ja .wrapper h5,
.ja .wrapper h6 {
    font-family: Nis_Jyau_P, sans-serif
}

.ja .wrapper h1 {
    font-size: 2.2em;
    line-height: 100%
}

@media only screen and (max-width:1199px) {
    .ja .wrapper h1 {
        font-size: 2em
    }
}

.ja .wrapper h2 {
    font-size: 2em;
    line-height: 100%
}

@media only screen and (max-width:1199px) {
    .ja .wrapper h2 {
        font-size: 1.5em
    }
}

.ja .wrapper h3 {
    font-size: 2.75em
}

@media only screen and (max-width:1199px) {
    .ja .wrapper h3 {
        font-size: 2em
    }
}

.ja .wrapper h4 {
    font-size: 1.75em
}

.ja .wrapper h5 {
    font-size: 1.125em
}

@media only screen and (max-width:1199px) {
    .ja .wrapper h5 {
        font-size: 1em
    }
}

.ja .wrapper h6 {
    font-size: 1em
}

.ja .wrapper .btn.btn-display,
.ja .wrapper .content-box .btn,
.ja .wrapper .detail-view .detail-pricing-title .discount,
.ja .wrapper .detail-view .detail-pricing-title .price,
.ja .wrapper .download-button.play-free,
.ja .wrapper .error-message .btn,
.ja .wrapper .pack-buy-button.can-buy .btn {
    font-family: Nis_Jyau_P, sans-serif
}

.ko #Stage {
    font-family: aERIN, sans-serif
}

.ko #Stage .FortsViewTitle .wrapper {
    font-family: aERIN, sans-serif !important
}

.ko #Stage .TitleLine2 {
    font-size: 104px !important;
    line-height: 1.4em !important
}

.ko .wrapper:not(.switch),
.ko .wrapper:not(.switch) .article-view,
.ko .wrapper:not(.switch) .battle-pass-jumbotron .jumbo-content p,
.ko .wrapper:not(.switch) .battle-pass-text .battle-pass-text-container .text-content p,
.ko .wrapper:not(.switch) .battle-pass-text .details-container .detail-items .content p,
.ko .wrapper:not(.switch) .blog-view-container .blog-view,
.ko .wrapper:not(.switch) .blog-view-container .blog-view .grid-item .grid-content .date,
.ko .wrapper:not(.switch) .detail-header-container .detail-header-pricing .detail-pricing-title h3,
.ko .wrapper:not(.switch) a,
.ko .wrapper:not(.switch) h5,
.ko .wrapper:not(.switch) h6,
.ko .wrapper:not(.switch) ol,
.ko .wrapper:not(.switch) p,
.ko .wrapper:not(.switch) ul {
    font-family: NotoSansCJKkr, sans-serif
}

.ko .wrapper:not(.switch) .blog-view-container .blog-view .grid-item .grid-content .title {
    font-family: aERIN, sans-serif
}

.ko .wrapper:not(.switch) .blog-container .blog-article .blog-content .blog-header-info .blog-header-author,
.ko .wrapper:not(.switch) .blog-container .blog-article .blog-content .blog-header-info .blog-header-date,
.ko .wrapper:not(.switch) .blog-container .blog-article .blog-content article strong,
.ko .wrapper:not(.switch) .blog-view-container .blog-view .top-featured-activity .feature-banner .feature-headline .feature-date p {
    font-family: NotoSansCJKkr, sans-serif
}

.ko .wrapper:not(.switch) .detail-view .stickyNav .pack-nav-container h5 {
    font-family: NotoSansCJKkr, sans-serif;
    white-space: nowrap
}

.ko .wrapper:not(.switch) .feature-video-container .feature-video-detail .feature-stream-title,
.ko .wrapper:not(.switch) .stream-card-container .stream-card-info a .video-title {
    font-weight: 700
}

.ko .wrapper .btn.btn-display,
.ko .wrapper .buyNow .fullPage-content p,
.ko .wrapper .detail-view .detail-pricing-title .discount,
.ko .wrapper .detail-view .detail-pricing-title .price,
.ko .wrapper .download-button.play-free,
.ko .wrapper .pack-buy-button.can-buy .btn,
.ko .wrapper h1,
.ko .wrapper h2,
.ko .wrapper h3,
.ko .wrapper h4 {
    font-family: aERIN, sans-serif
}

.ko .wrapper .egf .legal .links li a,
.ko .wrapper .egf .tags .tag-title {
    font-family: OpenSans, sans-serif
}

.ko .wrapper .battle-pass-text .heroImage .text h6 {
    font-family: BurbankBigCondensed-Black, sans-serif
}

.ko .wrapper .blog-view-container .blog-view .gridItem-large .grid-item .grid-content .title,
.ko .wrapper .blog-view-container .blog-view .gridItem-medium .grid-item .grid-content .title,
.ko .wrapper .blog-view-container .blog-view .headline-banner h2,
.ko .wrapper .blog-view-container .blog-view .headline h2,
.ko .wrapper .blog-view-container .blog-view .top-featured-activity .feature-banner .feature-headline h2,
.ko .wrapper .blog-wrapper .blog-view-container .headline-banner.headline-btn .btn-news,
.ko .wrapper .pack .pack-summary .price,
.ko .wrapper .ReactModalPortal .blog-view-container .headline-banner.headline-btn .btn-news {
    font-family: aERIN, sans-serif
}

.ko .wrapper .category-filter .head .filter-button {
    white-space: nowrap
}

.ko .wrapper .article-view .cmsContainer h1 {
    font-family: aERIN, sans-serif !important
}

.ko .wrapper .btn,
.ko .wrapper .btn-primary,
.ko .wrapper .guide-menu-wrap .menu-nav a,
.ko .wrapper .guide-menu-wrap .menu-nav button,
.ko .wrapper .guide-menu-wrap .menu>.title,
.ko .wrapper .guide-menu-wrap .sub-menu .title,
.ko .wrapper .guide-menu-wrap .sub-tab .title,
.ko .wrapper .play-guide-view .guide-info .guide-btn,
.ko .wrapper .play-guide-view.home .guide {
    font-family: aERIN, sans-serif
}

.blog-container .blog-article .blog-content .cms img {
    margin: 0
}

body.ar #nav #form.search .search-input {
    direction: rtl
}

body.ar #nav .kids a,
body.ar #nav .kids span,
body.ar #nav p {
    direction: rtl;
    font-size: 1em !important
}

body.ar #egf .copyright .copyright-paragraph,
body.ar #egf .footer-links-container .footer-cta-btn {
    direction: rtl
}

body.ar #egf .social li {
    margin: 0
}

body.ar .wrapper a,
body.ar .wrapper ol,
body.ar .wrapper p,
body.ar .wrapper span,
body.ar .wrapper ul {
    font-family: NotoNaskhArabicUI, NotoNaskhArabic, sans-serif
}

body.ar .wrapper h1,
body.ar .wrapper h2,
body.ar .wrapper h3,
body.ar .wrapper h4,
body.ar .wrapper h5,
body.ar .wrapper h6 {
    font-family: NotoNaskhArabicUI, NotoNaskhArabic, sans-serif;
    font-weight: 700
}

body.ar .wrapper h5 {
    font-size: 1em
}

body.ar .wrapper h6 {
    font-size: 1.125em
}

body.ar #Stage .ExploreView .Title,
body.ar #Stage .FortsViewTitle,
body.ar #Stage .TitleLine1,
body.ar .wrapper a,
body.ar .wrapper button,
body.ar .wrapper h1,
body.ar .wrapper h2,
body.ar .wrapper h3,
body.ar .wrapper h4,
body.ar .wrapper h5,
body.ar .wrapper h6,
body.ar .wrapper ol,
body.ar .wrapper p,
body.ar .wrapper span,
body.ar .wrapper ul {
    direction: rtl
}

.theEnd-active {
    background-color: #000
}

.theEnd-active .theEnd-all-chidren-override *,
.theEnd-active .theEnd-background-override {
    background: #000 !important
}

.theEnd-active .theEnd-all-children-background-color *,
.theEnd-active .theEnd-background-color {
    background-color: #000 !important
}

.theEnd-active .theEnd-text-color-white div,
.theEnd-active .theEnd-text-color-white h1 {
    color: #fff !important
}

.ar .wrapper h1,
.de .wrapper h1,
.es_ES .wrapper h1,
.es_MX .wrapper h1,
.it .wrapper h1,
.ja .wrapper h1,
.ko .wrapper h1,
.ru .wrapper h1,
.tr .wrapper h1 {
    line-height: 1
}

.slick-slider {
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    -webkit-touch-callout: none;
    -khtml-user-select: none;
    -ms-touch-action: pan-y;
    touch-action: pan-y;
    -webkit-tap-highlight-color: transparent
}

.slick-list,
.slick-slider {
    position: relative;
    display: block
}

.slick-list {
    overflow: hidden;
    margin: 0;
    padding: 0
}

.slick-list:focus {
    outline: none
}

.slick-list.dragging {
    cursor: pointer;
    cursor: hand
}

.slick-slider .slick-list,
.slick-slider .slick-track {
    -webkit-transform: translateZ(0);
    -ms-transform: translateZ(0);
    transform: translateZ(0)
}

.slick-track {
    position: relative;
    top: 0;
    left: 0;
    display: block;
    margin-left: auto;
    margin-right: auto
}

.slick-track:after,
.slick-track:before {
    display: table;
    content: ""
}

.slick-track:after {
    clear: both
}

.slick-loading .slick-track {
    visibility: hidden
}

.slick-slide {
    display: none;
    float: left;
    height: 100%;
    min-height: 1px
}

[dir=rtl] .slick-slide {
    float: right
}

.slick-slide img {
    display: block
}

.slick-slide.slick-loading img {
    display: none
}

.slick-slide.dragging img {
    pointer-events: none
}

.slick-initialized .slick-slide {
    display: block
}

.slick-loading .slick-slide {
    visibility: hidden
}

.slick-vertical .slick-slide {
    display: block;
    height: auto;
    border: 1px solid transparent
}

.slick-arrow.slick-hidden {
    display: none
}

#Stage,
#Stage * {
    position: absolute;
    user-select: none;
    -moz-user-select: none;
    -webkit-user-select: none;
    -o-user-select: none;
    -ms-user-select: none;
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
    -webkit-text-size-adjust: none;
    line-height: 1em
}

#Stage {
    font-family: BurbankBigCondensed-Black;
    color: #fff
}

#Stage .UIWarpPrompt .Background>.Background {
    background: url(data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAoHBwkHBgoJCAkLCwoMDxkQDw4ODx4WFxIZJCAmJSMgIyIoLTkwKCo2KyIjMkQyNjs9QEBAJjBGS0U+Sjk/QD3/2wBDAQsLCw8NDx0QEB09KSMpPT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT09PT3/wgARCAEAAQADAREAAhEBAxEB/8QAFwABAQEBAAAAAAAAAAAAAAAAAAEEBf/EABgBAQEBAQEAAAAAAAAAAAAAAAABAwUG/9oADAMBAAIQAxAAAADud/1IEAQCAIEQAgkgBECBEEAiINOmwgCAQBAJAEEkAIiAIgEERBDVptAEEACIVIAgkEBECBEEAiIIDTpsAQQBAiAEEkAIiAIggERAIJNOu5AIAgEgCCSAEQIEQCCIgEEg067AQBECAgEkACQQIggERAIJBDVrsIAiBAQCSAERAgQQCIgEEggNWu0AQCQBBIICIgQIIBEQCCQQJI1bbggRACCSABJAEQQAkggEggSQNW25AiAgEkAIiAIggERAIJBAkgDVtsEQAgkEBEQBEAgiIBBIIAkgQ167CAEEkAIgQIggEQJAJBAJICA1bbIAgkEBEQBEEAJIBBIICIgQA1a7AQSCAiIAiCAREAgkEASQIARNeu4gkgBECBEAgiIBBIIAkgQBIDXrvBJACIgCIIASQCCQQERAgBECNW26SAERAEQCCIgEEggEkBAEgEQ167CAiIAiCAREEAkEBEQIAkAiBNWu4EQIEQCCIggEggEkBACIEEgNWu4iIAiCAEkAgkEBJAIARAERANWu5IIEQQCIgEEggIiBACIEEgBI1bbBAiCAREAgkEBEQIARAiIAII1a7CBBAIiCASCASQEASAQSAEEDVrsIggEQJAJBAkgCAEQCQQCCBDXrtEEAiIBBIICIgQBIBAiAQQIDVrqIASQCCQQERAgCQCCQAkAQBNWu0AJIIBIICSAQBIBBIAQQIhSDTrsERBAJBAkECAJACSACCBEAENWuyIggEggCSBACIEEgBIAgQAQ1abRBAJBAkgCAEQIiACQBAgEANOmoEEggIiBAEgEEgBIAiAAQBNOmwgkEBEQIARAiIAIIAiAQABP/xAAUEAEAAAAAAAAAAAAAAAAAAACg/9oACAEBAAE/AAAf/8QAFBEBAAAAAAAAAAAAAAAAAAAAoP/aAAgBAgEBPwAAH//EABQRAQAAAAAAAAAAAAAAAAAAAKD/2gAIAQMBAT8AAB//2Q==)
}

#Stage b,
#Stage br,
#Stage span,
#Stage strong {
    position: relative
}

.fr #Stage .UIWarpPrompt .Text,
.ru #Stage .UIWarpPrompt .Text {
    white-space: nowrap;
    font-size: 40px !important
}

.bingResult {
    margin: 1em 0;
    padding: 2em;
    background-color: #fff
}

@media only screen and (max-width:767px) {
    .bingResult {
        padding: 1em
    }
}

.bingResult a {
    -webkit-transition: color .3s ease-in-out;
    -o-transition: color .3s ease-in-out;
    transition: color .3s ease-in-out;
    color: #1e1e1e
}

.bingResult a:hover {
    -webkit-text-decoration-line: none;
    text-decoration-line: none
}

.bingResult .resultTitle a {
    display: inline-block;
    font-size: 22px;
    font-weight: 600;
    line-height: 1.2;
    margin-bottom: .125em;
    padding-bottom: .25em;
    border-bottom: 2px solid transparent;
    -webkit-transition: border .3s ease-in-out;
    -o-transition: border .3s ease-in-out;
    transition: border .3s ease-in-out
}

@media only screen and (max-width:767px) {
    .bingResult .resultTitle a {
        font-size: 16px;
        text-decoration: underline;
        border-bottom: 0
    }
}

.bingResult .resultTitle a:hover {
    border-bottom: 2px solid grey
}

.bingResult .resultLink a {
    display: inline-block;
    margin: 5px 0 3px;
    font-size: 13px;
    word-break: break-all;
    font-weight: 600;
    line-height: 1.1
}

.bingResult .resultDescription {
    font-size: 14px;
    font-weight: 400;
    line-height: 1.4em;
    color: #1e1e1e
}

@media only screen and (max-width:767px) {
    .bingResult .resultDescription {
        font-size: 13px
    }
}

@-webkit-keyframes spin {
    0% {
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg)
    }

    to {
        -webkit-transform: rotate(1turn);
        transform: rotate(1turn)
    }
}

@keyframes spin {
    0% {
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg)
    }

    to {
        -webkit-transform: rotate(1turn);
        transform: rotate(1turn)
    }
}

.bingResults .bingLoader {
    margin: 80px auto;
    background-size: 5em;
    height: 5em;
    -webkit-animation: spin 1s linear infinite;
    animation: spin 1s linear infinite;
    border: 5px solid #f3f3f3;
    border-top-color: #555;
    border-radius: 50%;
    width: 50px;
    height: 50px
}

.bingResults .bingSearchBar {
    position: relative;
    height: 40px
}

.bingResults .bingSearchBar input {
    display: block;
    border: 1px solid #f8f8f8;
    padding: 0 0 0 1em;
    width: calc(100% - 108px);
    height: 100%;
    outline: none
}

@media only screen and (max-width:767px) {
    .bingResults .bingSearchBar input {
        width: calc(100% - 70px)
    }
}

.bingResults .bingSearchBar button {
    position: absolute;
    padding: 0;
    border: 0;
    height: 100%;
    width: 100px;
    right: 0;
    top: 0;
    font-size: .8em;
    font-weight: 500;
    text-transform: uppercase;
    text-align: center;
    -webkit-transition: background .2s ease-in-out;
    -o-transition: background .2s ease-in-out;
    transition: background .2s ease-in-out;
    outline: none
}

@media only screen and (max-width:767px) {
    .bingResults .bingSearchBar button {
        font-size: .6em;
        width: 60px
    }
}

.bingResults ul.search-filters {
    text-align: center;
    margin-top: 10px;
    padding: 0;
    list-style: none
}

.bingResults ul.search-filters li.search-filter-element {
    padding-left: 10px;
    display: inline-block
}

.bingResults ul.search-filters li.search-filter-element.active a {
    color: grey;
    pointer-events: none
}

.bingResults .pagination {
    width: 100%
}

.bingResults .pagination:after,
.bingResults .pagination:before {
    content: " ";
    display: table
}

.bingResults .pagination:after {
    clear: both
}

.bingResults .pagination button {
    border: 0;
    font-size: 3em;
    background: transparent;
    -webkit-transition: .2s ease-in-out;
    -o-transition: .2s ease-in-out;
    transition: .2s ease-in-out
}

.bingResults .pagination button:hover {
    -webkit-transform: scale(1.3);
    -ms-transform: scale(1.3);
    transform: scale(1.3)
}

.bingResults .nextResults {
    float: right
}

.bingResults .prevResults {
    float: left
}

.bingResults .noResults {
    margin: 1em 0
}

.ar .bingResults .bingSearchBar input {
    padding: 0 1em;
    float: left;
    width: calc(100% - 108px)
}

@media only screen and (max-width:767px) {
    .ar .bingResults .bingSearchBar input {
        width: calc(100% - 70px)
    }
}

.ar .nextResults span,
.ar .prevResults span {
    font-family: FontAwesome !important
}

body.ar .page-jumbotron .section-header-imagebg {
    -webkit-transform: scaleX(-1);
    -ms-transform: scaleX(-1);
    transform: scaleX(-1)
}

.page-jumbotron .section-header-imagebg {
    height: 260px;
    width: 100%;
    background-size: cover
}

@media only screen and (max-width:1199px) {
    .page-jumbotron .section-header-imagebg {
        height: 220px
    }
}

@media only screen and (max-width:991px) {
    .page-jumbotron .section-header-imagebg {
        height: 160px
    }
}

@media only screen and (max-width:767px) {
    .page-jumbotron .section-header-imagebg {
        height: 130px
    }
}

.page-jumbotron .name-container {
    position: relative;
    left: 0;
    color: #fff;
    max-width: 1200px
}

.page-jumbotron .name-container h1 {
    position: absolute;
    top: -175px;
    color: #fff
}

@media only screen and (max-width:1199px) {
    .page-jumbotron .name-container h1 {
        top: -155px
    }
}

@media only screen and (max-width:991px) {
    .page-jumbotron .name-container h1 {
        top: -120px
    }
}

@media only screen and (max-width:767px) {
    .page-jumbotron .name-container h1 {
        top: -100px
    }
}

.bing-branding {
    text-align: left
}

.bing-branding .logo-container .logo {
    position: relative;
    top: 4px;
    width: 50px;
    margin-right: .5em
}

.bing-branding .link,
.bing-branding .logo-container {
    display: inline-block
}

.bing-branding .link {
    font-size: .9em;
    margin: 1.1em auto;
    border-left: 1px solid #505050;
    padding-left: .5em
}

.bing-branding.dark .logo-container .logo {
    background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADIAAAAUCAYAAAG4zV4MAAAABGdBTUEAALGPC/xhBQAAA9JJREFUSA3Nl19ozlEYxzfbzGrNEC21LZJZSsmFP7GVluJipdRckLiSC2pI0i79TSxxIcm/doO4oOxSEcrk34U1mj9jRSTZlj/Z6/M973l+zn5+r/flVTz1fZ/n+T7Pec45v9/5nXPeglQq9aggkxB0ojjGCdDq7ZQIyXC8Mdy7OBf5hWapKfZYsArUuXIWNE1OUaaACvSAqZY8QisqArUssI2rgHMzsUYuh59pRuSkrXKYbBx6Y8jLHqUfAsPgkGxJIYKvJ/EMfRl8APvApWjyOG7srgU/8pFm+ejbgouJ9TLZEdl+LDtbXj5xN28rQIdjzI5rDUYcqgTsjMd/5Y/ohMQmFTOJN4TXszsK+rG1HppBKyhRLrrH65fSErhUcdp0TiX2BfPRzwLbTL2DKjBohDQv/Kv3P3it2TZiNzkfpxS8B5LVPikvRZ3zYCV4CGo0nba8KubSmE4kQ7nk/mlO/MUn1mEQM91QUqlvaO057oUmJieRvvEQuiEpLo6YOlng7REvPVObkA9n0uc7fI2eFyaZDT8R+6F85XqtRbMf3AHjPfcFewO4C6qjJcwyfAqhDXwSuIn9Aq5WjbwsRE8Hc4zwupy8LbJpswdoGZfCYaZeiY86kUOgiEAv5hT5MblO/AbxT6AmiL0PbO0YFerAc+n6NJDonRxw1o+f5dYYSu9E2+lWhcUH+k2Q1w5fDu6BGeABqHbJGKGctkb5aoqudzUwtvgeXqGjYzKfDqizDWwG/dYJdiTX8in+T9tGU0gbee0ulBgFdAIYRidNjvgckPHoSmqTjQu/92y5ucTrSdKnuALos13MgC8C3Tca8bWWtbQUK5f/tyRxInS2C+gycxIsAUW/2WE3n3wX6KRdC/gCZvkapehFQEesJqbJ7gVloA10gjNgpuKhwLWADnAFaFeoA0fAuPjXHi0tgiqYJL2Q28MOzIa3M2cQe8A3Vv7sIEfLTmKXOV1CJGuCnCp87eJut0DXA51jKy1HGv8ckPy0bUUT8Yma8XHwWdmBPA8Lmk3cJuLOtoDXUaP9V/eVpIlE+2vQpovcdvnoY+CqxUzDNQJJdeLSUiLBOtRBsA4kfrTwucoEErW8hFzFTiPl3wPzGVNtrPFa8+MT0RN7A1SkGyy1RLRuDjtAGWs/XtDSNNAn4BQlHoP74Cz+cdpUAtXV2a4cu4noSNUxHJc+iLciaXcEpeWp70OrQ/fjw/iqLfmoJ681nEluEZibzv2/fhmX7tl6UB0aWTGznSoDQq9f1+EBsBvenhjuvxXGppWzCejPgW5q/UDLrYFxarsv+A5s7u1WSq+jhwAAAABJRU5ErkJggg==);
    height: 20px
}

.bing-branding.dark .link {
    color: #fff;
    border-color: #fff
}

.bing-branding.light .logo-container .logo {
    background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADMAAAAWCAYAAAEax5Q5AAAABGdBTUEAALGPC/xhBQAABV1JREFUWAnNlw1oW1UUx5O0TdW0yhZbpytb03YTHTKk36vOMFydOBgIRSe6iSCI7hukjDkNOsWtCJ1DUQR1IBPshrhiwzq1iHb9jF+4lbGtHVKja9S6dV1J2yT+ztu7j+Tt9aW0Dnrh5rxzzzn/83HPu+/GUVpa+pNjiuFifTkKJ83yysrKJSKUcbf8oBTXaWMsFntEni1HhlotLy9fFg6HI9CdBQUFeU4gRhDOd7lcS3t6ejSfrCUEO6GsFK2trfVgWa54M1XBiXGtAhgeHi4EuScQCCTLG8UYrAc0kLKysqNmNCse0BC6hxzU4jYrBbs11+Tk5J9mBdD8sgbyc2aZ8FIhrRBut7ugo6Pjd1kk7hXxePwbp9P5QSKRuAxd2NvbuwGwYE5Oznot0VAo5BwfHx8Ug6TRgsEmDJ7VDQ5AHx4dHc3VjHRvo8oA5W95dgvPs7bdGGzGUwsRxRwVFRVLlbIdraurywC8U9MRLyovO6PZyjKnC0BBl5He4oyMjPPs0kmpHQHeB/1+OhgpjqhNALBXlKGAqWehyN7FSR49v0hf/w6q7bTuuBjZSuZx9B5l7W0w29i0DUYL60AndABLAsATGHtw+Hh1dfWNSUoReUZ2jjZaznymqKjoPVnDSatG8fgHhguEkUFp1nR3dx+7ys3+F/y9dFK9dP6O2cPZI0jZ3rreHZeyN3bxkLpfJgHdInpyNPF8u52NkhlO2JuUrlIKiiJv4w09Bd/AS7oWJ/L2XlRyO2ocOnTQarrjOF1Rz2btMxtJSfWWzUL3eY/H8/7IyMgS9G7Nz88/MTQ09AW2W7E9LbbofwLfy2OxkQmH81ciJOK9AkhpLgmfPFgTgD5094+NjbkB8cHfG4lEthDAGmz7RB/7KPyTPp/vAGubDCcilEghv8gzwlyhyYMo70SnBJCwab1B53/U6Q9Cm5qaYkLNb/9pwNMeimSQL8bmwbp2yrJekiwznEiJGJoM5an2JYqCOysry8v+JeOkPGP/EaWVbPIE09h4XesM5UibSQpiGobgz2hti9cvMzMzX+js7DyfxmZaYoD/IZs2lNex+TcZmbA4SWrHyGTttJDmoJLRxSQifTD1TWsOBm8OyWhks2CmvHy8afJfTfbj8G+y69p3mPYohj9LN2znNddufyb9GbGWyeBsP46cfDIPdnV1hWaCzGlaw2Gnfd/l+9Dc3HwJXDcJ7WSeA9P2+J+JT8tkqNY2XtYBbiKbCUDhxsnva+ZBKv85AV1RAjvKJdBNIvuwG+Ro0g5VbtI3g32RtXX4OoqPHTzvAqeNdr8MPcvcyNq87OxsX3t7u/xjcBDTLuSv8fgpMvnOyWvBUmIFxVtkmQyKCW5CNdyLj6BcyZThwmi1zKusfWVJ+GmCXDUwMOBF38+8Y2JiQrCCzGsGuPO8Xu/G1tZWda3eQ/D90Wi0HuWXJGHodmY2hZzQAV6nrR+TZIS3TEYE8o+Aqq4kmBdhpSLJ1zxRsR1U6mPVZqJIYOvBaCGoxbD/Whj/lZSIEv+NTY7O3AOVC7RKRFtGbnzTjdNMWbMjC3H4GTPR398fRXkPMzmRPnRXKf101O/33yBXHjDeYccPE8xv6Wys5Ly/jWDcT1yvKjmxlvD8oeKv2RmLv1xyqT4C2DYOg0FlOBWlvQbZlaeQF9ECRfw1u8LaKZKYr2x4X8ZEh6ldRHiXgqxZJfkyfiNix939Z4gLzAfZ5QCJXWAGmVuI71BhYWHYWVNTk0tf7mZxK8puMUQ4Bv8G97mGYDAo94o5MeQvOAW9oIKBr6IIclfdLUf8/348KkfXg1ZVVd1F8A8R/AKKLR0QYsc6lK//AAZ8fJjg6ytbAAAAAElFTkSuQmCC);
    height: 22px
}

.bing-branding.light .link {
    color: #505050
}

.epic-common-spinner-icon {
    background: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB2aWV3Qm94PSIwIDAgMTAwIDEwMCIgcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQiIGNsYXNzPSJsZHMtcmluZyIgc3R5bGU9ImJhY2tncm91bmQ6MCAwIj48Y2lyY2xlIGN4PSI1MCIgY3k9IjUwIiBmaWxsPSJub25lIiByPSIzMCIgc3Ryb2tlPSIjMGRiMmZiIiBzdHJva2Utd2lkdGg9IjciLz48Y2lyY2xlIGN4PSI1MCIgY3k9IjUwIiBmaWxsPSJub25lIiByPSIzMCIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjciIHN0cm9rZS1saW5lY2FwPSJzcXVhcmUiIHRyYW5zZm9ybT0icm90YXRlKDY3Ny42MDYgNTAgNTApIj48YW5pbWF0ZVRyYW5zZm9ybSBhdHRyaWJ1dGVOYW1lPSJ0cmFuc2Zvcm0iIHR5cGU9InJvdGF0ZSIgY2FsY01vZGU9ImxpbmVhciIgdmFsdWVzPSIwIDUwIDUwOzE4MCA1MCA1MDs3MjAgNTAgNTAiIGtleVRpbWVzPSIwOzAuNTsxIiBkdXI9IjEuN3MiIGJlZ2luPSIwcyIgcmVwZWF0Q291bnQ9ImluZGVmaW5pdGUiLz48YW5pbWF0ZSBhdHRyaWJ1dGVOYW1lPSJzdHJva2UtZGFzaGFycmF5IiBjYWxjTW9kZT0ibGluZWFyIiB2YWx1ZXM9IjE4Ljg0OTU1NTkyMTUzODc2IDE2OS42NDYwMDMyOTM4NDg4Mjs5NC4yNDc3Nzk2MDc2OTM4IDk0LjI0Nzc3OTYwNzY5Mzc3OzE4Ljg0OTU1NTkyMTUzODc2IDE2OS42NDYwMDMyOTM4NDg4MiIga2V5VGltZXM9IjA7MC41OzEiIGR1cj0iMS43IiBiZWdpbj0iMHMiIHJlcGVhdENvdW50PSJpbmRlZmluaXRlIi8+PC9jaXJjbGU+PC9zdmc+);
    background-size: contain;
    background-repeat: no-repeat;
    width: 20em;
    height: 20em;
    margin: 0 auto
}

@media only screen and (max-width: 767px) {
    .darkfireView .btn-hover-transform {
        transform: scale(1.4)
    }
}



@media only screen and (device-width: 768px), only screen and (device-width: 1024px) {
    .validateStage {
        width: 90%;
    }
}
/*# sourceMappingURL=thirdParty.fortnite-site.ce8535dff105c335abd7.css.map */
