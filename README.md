### Hi there 👋


/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	padding-inline-start: 0;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-translucentGray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Tushar Shirsat</title><style>
	
</style></head><body><article id="10db03c3-f72e-4227-beab-fc6048e79346" class="page sans"><header><img class="page-cover-image" src="https://images.unsplash.com/photo-1498049860654-af1a5c566876?ixlib=rb-1.2.1&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb" style="object-position:center 50%"/><div class="page-header-icon page-header-icon-with-cover"><span class="icon">👨🏿‍💻</span></div><h1 class="page-title">Tushar Shirsat</h1></header><div class="page-body"><h1 id="bd28f2c6-a289-4b59-bb9b-b8cfa49ba7b0" class="">Data Analyst | Computer Engineer</h1><div id="ecd5ffbc-9d8f-4b1a-9f36-0dd6c002dbeb" class="column-list"><div id="c58b61f2-24cd-443b-a31c-cf10abf5357d" style="width:56.25%" class="column"><blockquote id="1a76e9da-e25c-4f31-9d53-43102a6230be" class=""><em>My goal is to help companies analyze trends to make better business decisions. Data passionate, continuous learning and curious soul.</em></blockquote><p id="21cf9171-7eac-43f6-8394-f5a8ade49725" class="">
</p><p id="3fff95c0-f9c8-4468-ab98-3f39aa08e95a" class="">
</p></div><div id="dae3ea8b-90bb-43e2-86cc-47924a1a70df" style="width:43.75%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="1ed220d9-4034-4562-be7b-77eba7baef34"><div style="font-size:1.5em"><span class="icon">💼</span></div><div style="width:100%"><a href="https://www.linkedin.com/in/tusharhshirsat/">My LinkedIn Profile </a></div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="911c73f8-7435-447a-b9a7-e0ccf24bf4c3"><div style="font-size:1.5em"><span class="icon">✉️</span></div><div style="width:100%">tusharshirsat72@gmail.com</div></figure></div></div><hr id="60f0a6fe-9134-4725-8d7e-fe85b937f30c"/><div id="6b5404a5-c7a6-41dc-86de-7ed58100c031" class="column-list"><div id="e3e17c44-de40-45ac-a50f-b3660476e90f" style="width:33.33333333333333%" class="column"><h2 id="6a400add-4fa8-4b79-933d-7833f78491cf" class="">Skills</h2><p id="6f79f2a0-b536-4e4a-80b5-9964284e8b14" class="">💡 Analytical skills</p><p id="21cf5f14-47ac-4440-a379-bc1ba769d9c3" class="">💡 Data visualization</p><p id="f42b2b2c-ae28-47f7-bb7d-4ea5320a8e86" class="">💡 Presentation skills</p><p id="c6dbc141-2e85-44c8-a1fa-228c4acb3b56" class="">💡 Problem-solving aptitude</p></div><div id="15d638da-462b-49bd-bae2-dc4c9837ea9b" style="width:37.5%" class="column"><h2 id="adf07c90-d9f0-4317-a572-ab66998dab50" class="">Technologies</h2><p id="556316e0-e0ef-4b33-9798-e8fde6a7741b" class="">⚙️ Python</p><p id="75edc87c-1d15-4fa3-b7cd-630335a71108" class="">⚙️ SQL</p><p id="7295a4b9-8f62-44f4-b2fa-6343b0084ff3" class="">⚙️ Advanced Excel</p><p id="7344a439-c611-4a2b-8456-b24ed38718b3" class="">⚙️ Tableau</p><p id="89844930-4439-4965-b3ef-c7169cf0cfae" class="">⚙️ Machine Learning</p><p id="9f8c214a-de9f-475a-937a-1b36894bf8a5" class="">⚙️ Data cleaning</p><p id="c279d57f-3f11-4e84-b913-d66a8fa4de73" class="">⚙️ Pandas, Numpy, Scikit-learn, Matplotlib.</p></div><div id="c3b7f50c-86c5-465b-9d8e-b80471569013" style="width:29.16666666666668%" class="column"><h2 id="f6c419bd-d527-4bc9-8ac7-c24740950b7d" class="">Languages</h2><ul id="dd06f541-e13c-4738-89c0-fa311b597d71" class="bulleted-list"><li style="list-style-type:disc">English</li></ul><ul id="23c42fca-03fe-4bf5-841b-944ab592ad14" class="bulleted-list"><li style="list-style-type:disc">Marathi</li></ul><ul id="f571ca66-fe2d-4ba1-a0f9-6500db4f83fa" class="bulleted-list"><li style="list-style-type:disc">Hindi</li></ul><p id="f3b2dd8f-4b52-46a5-b797-a3c4ab7d55ed" class="">
</p></div></div><hr id="1e8492c4-ff4a-4af3-a3ac-74eab4a976d2"/><h2 id="cc9add08-9b3f-4f9c-8e2a-b6bbae0acb7d" class=""><strong>Internships</strong></h2><h3 id="f3982773-2aa6-4731-8214-45137f71c2a1" class="">Machine Learning Internship</h3><p id="a2f5a3cb-ab4f-42ac-a94c-5d87652461c2" class="">Cognifront<mark class="highlight-gray"><em>, Nashik | Sep 2020 - Nov 2020</em></mark></p><p id="4a7bf4b7-5aa3-4acd-b8e4-9322d663fa39" class="">● Worked on python libraries( pandas, numpy, scikit-learn, matplotlib ) and Implemented various supervised machine learning algorithms. </p><p id="2e3770fd-8fdd-4254-bc46-1dddab7afc7c" class="">● Built machine learning data models to predict and analyze datasets.</p><p id="d82848d7-0462-4387-b534-29c7d858cbff" class="">
</p><h3 id="0f2f8d40-96bc-4a20-8670-2ffd5a71e683" class="">Data Analytics Internship</h3><p id="b7b8f64a-1fa1-4390-8de4-0ca466c6b08c" class="">Quantium<mark class="highlight-gray"><em> | Mar 2023 - Apr 2023</em></mark></p><p id="5fc7060c-ee89-4152-a9e6-dca4fce25f99" class="">● Performed data preparation and analysis on a large scale customer transaction dataset.
● Conducted statistical tests to evaluate the performance of trail strategies to get insights for customer preferences.
● Constructed reports and visualizations to drive strategic decisions.</p><p id="f0a37aa9-54e3-495b-8ead-1c32a188f484" class="">
</p><h2 id="e589554f-8f35-4148-bcce-24476e2fe59d" class=""><strong>Certifications</strong></h2><div id="4f4ab918-3af6-4336-ac91-96c14066b721" class="column-list"><div id="37fdb5db-54d9-4a6d-af59-c72da4277345" style="width:50%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="7d13afdf-51d5-46cf-8c3e-74abce50ad89"><div style="font-size:1.5em"><span class="icon">🎓</span></div><div style="width:100%"><a href="https://www.udemy.com/certificate/UC-aba5fc01-bd83-4ae7-aaec-70294e3d42b1/">MySQL for Data Analytics and Business Intelligence</a></div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="742a9dd9-d7e1-41bb-abfe-0f06e7c2c8a5"><div style="font-size:1.5em"><span class="icon">🎓</span></div><div style="width:100%">Google Data Analytics Certification (ongoing)</div></figure><p id="a5bfa060-bfe3-44e1-bfd8-c90e67563753" class="">
</p></div><div id="34a8f66e-65f8-48de-807a-08c741dcc48f" style="width:50%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="907e68ea-3dd5-4600-b1a1-66154c818129"><div style="font-size:1.5em"><span class="icon">🎓</span></div><div style="width:100%"><a href="https://www.hackerrank.com/certificates/99a04509c93d">HackerRank SQL Certificate</a></div></figure></div></div><h2 id="aaa57e4f-8452-4e61-815a-9e3cd77bf07a" class="">Education</h2><h3 id="830d55c1-1873-41a2-a326-2d91bb5c6f48" class="">Computer Engineering </h3><p id="822d4b16-4e46-4d3a-aa7d-e3e4df4b1752" class="">MVP’s KBT College of Engineering, Nashik | 2018 - 2022</p><p id="9cd6de07-76f0-4c69-8e66-458199764317" class="">CGPA - 9.2 / 10</p><p id="b75e33fc-4409-46a0-b9ea-6086a371af89" class="">
</p><hr id="952ffeaf-912d-4482-85e9-d268619bd559"/></div></article></body></html>
