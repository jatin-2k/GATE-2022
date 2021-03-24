
<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Syllabus</title><style>
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
	text-indent: -1.7em;
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
	height: 30vh;
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

.sans { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, YuMincho, "Yu Mincho", "Hiragino Mincho ProN", "Hiragino Mincho Pro", "Songti TC", "Songti SC", "SimSun", "Nanum Myeongjo", NanumMyeongjo, Batang, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC', 'Noto Sans CJK KR'; }

.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC', 'Noto Sans Mono CJK KR'; }

.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, YuMincho, "Yu Mincho", "Hiragino Mincho ProN", "Hiragino Mincho Pro", "Songti TC", "Songti SC", "SimSun", "Nanum Myeongjo", NanumMyeongjo, Batang, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC', 'Noto Sans CJK KR'; }

.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC', 'Noto Sans Mono CJK KR'; }

.highlight-default {
}
.highlight-gray {
	color: rgb(155,154,151);
}
.highlight-brown {
	color: rgb(100,71,58);
}
.highlight-orange {
	color: rgb(217,115,13);
}
.highlight-yellow {
	color: rgb(223,171,1);
}
.highlight-teal {
	color: rgb(15,123,108);
}
.highlight-blue {
	color: rgb(11,110,153);
}
.highlight-purple {
	color: rgb(105,64,165);
}
.highlight-pink {
	color: rgb(173,26,114);
}
.highlight-red {
	color: rgb(224,62,62);
}
.highlight-gray_background {
	background: rgb(235,236,237);
}
.highlight-brown_background {
	background: rgb(233,229,227);
}
.highlight-orange_background {
	background: rgb(250,235,221);
}
.highlight-yellow_background {
	background: rgb(251,243,219);
}
.highlight-teal_background {
	background: rgb(221,237,234);
}
.highlight-blue_background {
	background: rgb(221,235,241);
}
.highlight-purple_background {
	background: rgb(234,228,242);
}
.highlight-pink_background {
	background: rgb(244,223,235);
}
.highlight-red_background {
	background: rgb(251,228,228);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(55, 53, 47, 0.6);
	fill: rgba(55, 53, 47, 0.6);
}
.block-color-brown {
	color: rgb(100,71,58);
	fill: rgb(100,71,58);
}
.block-color-orange {
	color: rgb(217,115,13);
	fill: rgb(217,115,13);
}
.block-color-yellow {
	color: rgb(223,171,1);
	fill: rgb(223,171,1);
}
.block-color-teal {
	color: rgb(15,123,108);
	fill: rgb(15,123,108);
}
.block-color-blue {
	color: rgb(11,110,153);
	fill: rgb(11,110,153);
}
.block-color-purple {
	color: rgb(105,64,165);
	fill: rgb(105,64,165);
}
.block-color-pink {
	color: rgb(173,26,114);
	fill: rgb(173,26,114);
}
.block-color-red {
	color: rgb(224,62,62);
	fill: rgb(224,62,62);
}
.block-color-gray_background {
	background: rgb(235,236,237);
}
.block-color-brown_background {
	background: rgb(233,229,227);
}
.block-color-orange_background {
	background: rgb(250,235,221);
}
.block-color-yellow_background {
	background: rgb(251,243,219);
}
.block-color-teal_background {
	background: rgb(221,237,234);
}
.block-color-blue_background {
	background: rgb(221,235,241);
}
.block-color-purple_background {
	background: rgb(234,228,242);
}
.block-color-pink_background {
	background: rgb(244,223,235);
}
.block-color-red_background {
	background: rgb(251,228,228);
}
.select-value-color-default { background-color: rgba(206,205,202,0.5); }
.select-value-color-gray { background-color: rgba(155,154,151, 0.4); }
.select-value-color-brown { background-color: rgba(140,46,0,0.2); }
.select-value-color-orange { background-color: rgba(245,93,0,0.2); }
.select-value-color-yellow { background-color: rgba(233,168,0,0.2); }
.select-value-color-green { background-color: rgba(0,135,107,0.2); }
.select-value-color-blue { background-color: rgba(0,120,223,0.2); }
.select-value-color-purple { background-color: rgba(103,36,222,0.2); }
.select-value-color-pink { background-color: rgba(221,0,129,0.2); }
.select-value-color-red { background-color: rgba(255,0,26,0.2); }

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
	
</style></head><body><article id="af980752-42b5-4be5-b7aa-511e066e9dac" class="page sans"><header><h1 class="page-title"><strong>Syllabus</strong></h1></header><div class="page-body"><ul id="fa9d05d7-7f1d-458f-82b9-c3616c0a6813" class="toggle"><li><details open=""><summary>Section 1: General Aptitude (GA)</summary></details></li></ul><ul id="dc57227b-7a2e-41f6-937a-835e8896d1fc" class="toggle"><li><details open=""><summary>Section 2: Mathematics</summary><ul id="97e0050d-6c4d-4dfe-8c6b-86799ef2fa7b" class="toggle"><li><details open=""><summary>Discrete Mathematics</summary><p id="e030c207-188b-49da-86c5-4be166f1fa7f" class="">Propositional Logic and First order logic:<div class="indented"><p id="41f90d3b-c313-4dbf-9bba-5ba0322351ce" class="">Sets</p><p id="502659a6-d677-41e2-ac86-42d28cf51f83" class="">Relations</p><p id="15f6506e-6caf-4e8d-83b7-480dacc4c7b1" class="">Functions</p><p id="376606f0-f388-433c-88dc-49ca4f95dc81" class="">Partial orders</p><p id="587eb3b7-dc5f-472c-a292-56c94ef3423e" class="">Lattices</p><p id="690c4a54-fcb2-42d6-a8b3-f37ebd84cad7" class="">Monoids</p><p id="f5d548e2-74ba-4e1f-a8f1-99ec1bd45e9b" class="">Groups</p></div></p><p id="4db2b086-8a15-4079-a10a-e70ba4ac4273" class="">Graphs:<div class="indented"><p id="0c6580b5-1f79-40a7-83e0-42ac80588172" class="">connectivity</p><p id="6f8598ec-96c0-41fd-932f-0cef7c90c70c" class="">matching</p><p id="0551ce33-97e1-43df-a606-b46026c36983" class="">colouring</p></div></p><p id="c037aa41-bab4-4911-b2e7-ebd424e4ff21" class="">Combinatorics:<div class="indented"><p id="cb9c94c0-9927-4db6-ad2e-c7824fc676ed" class="">counting</p><p id="b9ac6127-d4dd-4add-a023-d6e899308a37" class="">recurrence relations</p><p id="85f5fb97-e421-4c16-8b29-415e4e4d2086" class="">generating functions</p></div></p></details></li></ul><ul id="f895d9d9-4d42-422f-8bcb-ab1c4d5c64cb" class="toggle"><li><details open=""><summary>Linear Algebra</summary><p id="f0b5ad55-90a1-4790-a189-ec5f08d07df9" class="">Matrices</p><p id="a9f1169c-5e9b-47db-9826-3e1b73593f15" class="">determinants</p><p id="b941d7ea-3525-48cd-b328-fc7af48b386b" class="">system of linear equations</p><p id="646f9851-cde7-466a-a0a6-af20071835e3" class="">eigenvalues</p><p id="a2882638-7254-4cc6-b82e-6e7507e7b692" class="">eigenvectors</p><p id="8afcae5c-2b8b-4216-9fe4-c6013335e5d3" class="">LU decomposition</p></details></li></ul><ul id="8d24908d-77c5-494c-b5ce-fc4333cd5d88" class="toggle"><li><details open=""><summary>Calculus</summary><p id="0a57d3fa-2694-42be-be54-598c6942fe9d" class="">Limits</p><p id="02e83265-ef40-4c5c-a151-ed6e0c13aae7" class="">continuity and differentiability</p><p id="3fbac77d-9bf8-4201-9a70-7b4321a5beb5" class="">maxima and minima</p><p id="9126bf9f-bc1b-4127-90e9-aca814d9578a" class="">mean value theorem</p><p id="165eaa5d-bb0a-4fad-9e9e-49dd2e69cffb" class="">integration</p></details></li></ul><ul id="f3fcde76-b543-486d-a583-00503538ec62" class="toggle"><li><details open=""><summary>Probability and Statistics</summary><p id="5786b6a7-e656-4682-bb0e-57264fe1816b" class="">Random variables</p><p id="9d2376a5-4568-4b2f-b8a5-3b9f937ac1e5" class="">Mean</p><p id="5f237ca2-cbd9-4a92-bac3-f487a990d27a" class="">Median</p><p id="f8831a2f-a081-4f1a-8a48-068bf55b340b" class="">Mode</p><p id="3948b2fa-2eef-48a6-9cca-8fe906751b5c" class="">Standard Deviation</p><p id="c11ed738-8001-43f5-be0b-d5b017fe671e" class="">Conditional Probability</p><p id="b700880a-b871-451f-a215-0f5dbf8a5240" class="">Bayes Theorem</p><p id="5485febc-597a-49c5-b624-5a1357b2875c" class="">Distributions:<div class="indented"><p id="5bc71956-d7d1-4b14-879d-ed4abf0a88e6" class="">uniform</p><p id="9124e2a9-fa4a-40ba-894f-83c1fb3c4dea" class="">normal</p><p id="3e5d6421-f7be-4b01-a48a-989c57c66e10" class="">exponential</p><p id="29584e8a-b1f3-4a85-a96c-bf284d7810a5" class="">poisson</p><p id="5b67fafd-380a-4f10-82e3-0ba56141b00d" class="">binomial</p></div></p></details></li></ul></details></li></ul><ul id="9acf5670-1a05-4b7c-b27c-62c35aeac55e" class="toggle"><li><details open=""><summary>Section 3: Algorithms</summary><p id="e5d72d2f-f162-41e6-99d4-eff95015810c" class="">Searching</p><p id="01ee31b3-97c6-48f8-b76a-288090dd03ab" class="">Sorting</p><p id="3990f082-dfaa-4101-8911-1af39620365f" class="">hashing</p><p id="cb8b2742-1062-4ef8-ba31-deb4b42115d2" class="">Asymptotic time and space complexities</p><p id="50af7f11-14e7-42fc-b5a0-33279985858d" class="">Algorithm design techniques:<div class="indented"><p id="306a2b17-f1a4-4651-af32-571356769ef8" class="">greedy</p><p id="540c8622-5ca7-4045-82ac-1042082050d9" class="">dynamic programming</p><p id="fe3debe9-c694-45bf-bb16-16507d793df5" class="">divide and conquer</p></div></p><p id="64669305-16b1-4254-bd91-8e86d96eacd1" class="">Graph traversals</p><p id="9c26d583-8cd7-429d-9e8d-e21775c9199b" class="">minimum spanning trees</p><p id="ef90a42b-78f8-4ee7-a20c-70d2cb0fb91c" class="">shortest paths</p></details></li></ul><ul id="19593bfc-817a-4ac7-ab82-064065b81902" class="toggle"><li><details open=""><summary>Section 4: Programming and Data Structures</summary><p id="8780f0e8-10c2-449c-909d-3626252e573a" class="">programming in c</p><p id="992ef424-47e7-49ea-8726-aaff9f4edd47" class="">recursion</p><p id="d9013b14-f9dd-4492-b5af-9c971cb137a0" class="">arrays</p><p id="4a479573-18b7-4919-9122-d2bd8993de1f" class="">stacks</p><p id="0c2cbd77-abc7-4e82-ab0e-3e2ac4a271d8" class="">queues</p><p id="078e1e00-a777-4e58-b208-3f452ba01603" class="">linked lists</p><p id="4f4bcbbe-c3f8-43fa-aa2c-499d942c2ef8" class="">trees</p><p id="e2a56a2d-31bc-430d-b482-7167ee697bd0" class="">binary search tree</p><p id="ec243f6c-cc7e-47d9-8fd0-9fd5337050c1" class="">binary heaps</p><p id="18e56477-ed71-45ba-877d-550a4473badf" class="">graphs</p></details></li></ul><ul id="617a4cf2-705c-42e4-8021-f0e4a7e955ac" class="toggle"><li><details open=""><summary>Section 5: Operating Systems</summary><p id="a41c9dc4-144c-42f4-90df-a25142f9052d" class="">System calls</p><p id="03d502a2-26a4-462a-bf2a-2dc4e25ae9bf" class="">processes</p><p id="260aabf8-d260-49ce-a8d5-fb8279e79d24" class="">threads</p><p id="e4427a83-60a7-4750-88f7-48a6bdf23a5f" class="">inter-process communication</p><p id="3a32f670-a2ed-46b4-880e-1fe64ea77d7f" class="">concurrency and synchronization</p><p id="3ab14110-3606-41d9-a145-d1217e2ad1f6" class="">deadlock</p><p id="c3bba76d-53ce-4c24-9c32-a4bf6fb21b46" class="">cpu and io scheduling</p><p id="e942a171-57c0-4c35-8d23-9fa3aa1530bd" class="">memory management</p><p id="24aa7130-6a95-4ea7-8c57-0942ddbe13bb" class="">virtual memory</p><p id="7d1c1504-e6ec-41e4-bccc-dd84ec2fb54a" class="">file systems</p></details></li></ul><ul id="0f74ac8d-48d9-41b9-b1c3-9735602bd52c" class="toggle"><li><details open=""><summary>Section 6: Databases</summary><p id="9909557f-d083-490c-85f9-33502b157c6e" class="">ER model</p><p id="bd31ae40-6bae-4b8b-9ede-c6135dd1b77e" class="">Relational Model<div class="indented"><p id="bfe62d9c-aec2-44c5-a1b5-9d93381f3e86" class="">Relational Algebra</p><p id="e9cd9e6b-f20d-4d24-b223-99d8b8d76eb7" class="">tuple calculus</p><p id="bda29ea9-707c-49c7-b8f9-cfc1b3b0bdf1" class="">sql</p></div></p><p id="37291af0-12dd-43b8-9faf-c3679c2af5cd" class="">integrity constraints</p><p id="4b832961-5132-4d18-94db-a2f815bef40d" class="">normal forms</p><p id="4e620f89-3ee0-46f3-850e-11d257306ced" class="">file organization</p><p id="2deeafa1-d0b6-49bb-981f-af9c138e0170" class="">indexing (B and B+ trees)</p><p id="f57e911c-98a3-4cd5-a698-2dfd18aea6dc" class="">transactions and concurrency control</p></details></li></ul><ul id="550a0891-c59b-437e-9583-cd872796d7f9" class="toggle"><li><details open=""><summary>Section 7: Computer Networks</summary><p id="e40c344a-5737-490b-a4ef-9b6abc037882" class="">Concept of layering:<div class="indented"><p id="c98a34d2-0282-4d81-9bf4-26b1656a81e6" class="">OSI</p><p id="41af4b17-2083-4ff4-b66b-98d98cd7cc9f" class="">TCP/IP</p></div></p><p id="c62864ab-8ce5-4066-aad6-2388c492a6e7" class="">Basics of packets</p><p id="90f0d8d0-ed7b-4446-a8f1-8baa9cda5a5e" class="">circuit and virtual circuit switching</p><p id="6c4cdbbd-2493-4bd0-aa65-c8c9c9d61e13" class="">Data link layer:<div class="indented"><p id="d568d202-28ff-4465-a816-4f543f9b2325" class="">framing</p><p id="ae406e9d-ba71-49fd-8a96-f6752fc55383" class="">error detection</p><p id="2c225583-a57c-4b9a-87e3-7503c0f2934d" class="">medium access control</p><p id="0347f142-140d-466f-a38c-7787aaaa1f73" class="">ethernet bridging</p></div></p><p id="e4104c8b-3892-4cb4-bedc-4b6e5ec1915a" class="">Routing protocols:<div class="indented"><p id="999ce6c9-3b59-4449-9d0f-ba6fda20b182" class="">shortest path</p><p id="ff0d155f-bae4-43a3-a23d-2585192d4313" class="">flooding</p><p id="4e95c5da-6cdd-4c0c-960f-a3ee81ad4798" class="">distance vector and link state routing</p></div></p><p id="eeb52c25-0bcb-45bd-ba13-e9271823a58f" class="">Fragmentation and IP addressing</p><p id="bab7ff95-aee3-4dcd-9a97-0fe86400130d" class="">IPv4</p><p id="1b65e02d-8e4d-44ca-bca6-b8a2ada3e1f7" class="">CIDR notation</p><p id="53644e99-88a0-4479-b61e-c63e793dfb4c" class="">Basics of IP support protocols:<div class="indented"><p id="3ce9c39a-ec03-4b75-a7b0-8e239339b443" class="">ARP</p><p id="54720eab-0660-44e5-a6e5-2b9e1ae75f46" class="">DHCP</p><p id="18483fd3-ea1f-422a-898a-c5d984c3047b" class="">ICMP</p><p id="af0fa0a4-8fe7-4fc7-b3a0-1a222edd0d1f" class="">network address translation (NAT)</p></div></p><p id="87ea2d58-4cb1-4157-ad41-0d70f487c845" class="">Transport Layer:<div class="indented"><p id="ca5b88a3-519c-4d73-90b0-e135844f7854" class="">flow control</p><p id="cc97c1a9-2038-4ec0-996e-4304466fd6ea" class="">congestion control</p><p id="fb6c57a2-560a-4f4b-a2ef-21e90a952fe2" class="">UDP</p><p id="fa16a61b-d620-49ab-9cbd-a598fe913c15" class="">TCP</p><p id="5c0db751-8a2c-4ee8-91b7-fc7400c0fc70" class="">sockets</p></div></p><p id="6284a8de-fe4c-4c88-8f4d-592981af3f78" class="">Application layer protocol:<div class="indented"><p id="bb00a136-eae4-4690-bd04-96093138aff7" class="">DNS</p><p id="b7be2f99-d487-48b3-b4f7-d426e384a27a" class="">SMTP</p><p id="6bcb2923-7e74-47ea-b090-a731b54e8445" class="">HTTP</p><p id="1a03158a-513c-4873-94b2-f300068195e8" class="">FTP</p><p id="cd3e82c6-641a-42e0-9105-18746628ce88" class="">Email</p></div></p></details></li></ul><ul id="1143dde4-256b-458f-8d8b-2d44bd109dbb" class="toggle"><li><details open=""><summary>Section 8: Computer Organization and Architecture</summary><p id="908ddf9b-aa7b-4881-ac88-c2fa9bec36c7" class="">Machine instructions and addressing modes</p><p id="7ac3a666-9f0d-4134-b872-67f4bcb95fb4" class="">ALU</p><p id="856543c6-ad4a-47a3-8110-a9a033101a46" class="">data-path and control unit</p><p id="70c18e14-b0ca-4534-aef8-f6fd42d2372e" class="">Instruction pipeline, pipeline hazards</p><p id="3463213a-d75e-42ac-8296-ce7ffd0009f3" class="">Memory hierarchy:<div class="indented"><p id="e1c2f8ef-1521-460a-872c-5463222a7e71" class="">cache</p><p id="b4ead5c2-aa5d-453f-8a4d-42823700011f" class="">main memory</p><p id="6abc683d-6ba8-47f6-b3eb-e6246e74f8aa" class="">secondary storage</p></div></p><p id="a1b84bba-f7bd-41a9-9ced-477479dd2f8c" class="">I/O interface (interrupt and DMA mode)</p></details></li></ul><ul id="12c0f78b-4a5b-48b9-8e32-d92d9a42ff6f" class="toggle"><li><details open=""><summary>Section 9: Theory of Computation</summary><p id="cca0dedc-0a34-4b7a-95f5-7c8abb498143" class="">Regular expressions and finite automata</p><p id="b81624b9-6800-4205-a1a5-d1a29dcd2827" class="">Context free grammars </p><p id="93f15102-6b43-495f-97a3-dda09e7aa00d" class="">push-down automata</p><p id="a272ce3d-f1f5-4cbb-9b48-9398230ed6e3" class="">Regular and Context free languages</p><p id="9eed64f1-2d20-4de1-b300-4c97532dcb97" class="">pumping lemma</p><p id="6fb0062b-ed16-4452-b455-6698f1218301" class="">Turing machine and undecidability</p></details></li></ul><ul id="575f5753-6719-4ad6-a6a1-a9c687af7485" class="toggle"><li><details open=""><summary>Section 10: Compiler Design</summary><p id="e8ff2488-63cb-4a42-8875-f7e679dc44f5" class="">Lexical analysis</p><p id="c708e65e-a557-43da-bbe4-07cb5e41fc94" class="">parsing</p><p id="79c19eef-0cf1-4cff-9e94-c57c0bbcaf07" class="">syntax-directed translation</p><p id="5af6ff77-bc60-4c21-8ce9-aa39920eb0e7" class="">Runtime Environments</p><p id="88f5c41a-a275-40ae-9cec-604ab2687a15" class="">Intermediate code generation</p><p id="00c92e2c-952f-48a5-8462-29294c821c1f" class="">Local optimisation</p><p id="387de095-e363-4255-9aad-ec77dea041ca" class="">data flow analyses:<div class="indented"><p id="2c62d416-f83f-4954-90fb-94de2c70f43e" class="">constant propogation</p><p id="9098b796-13fc-4bc5-b0c2-8b55d47102a2" class="">liveness analysis</p><p id="63e69f01-15ac-472b-aafe-15926bf65e8b" class="">common subexpression elemination</p></div></p></details></li></ul><ul id="387cbd49-2307-42fb-8592-6d0c0a6df431" class="toggle"><li><details open=""><summary>Section 11: Digital Logic</summary><p id="32c7aab3-bbcd-4ea4-869d-b853a0ca86af" class="">Boolean algebra</p><p id="8c3e60da-1598-4651-936d-514986c91102" class="">Combinational and Sequential circuits</p><p id="2dd24e80-b957-4a97-b97a-fe0649600aa9" class="">minimization</p><p id="bff3909c-104a-4f1a-980b-66a09083af26" class="">number representations and computer arithmetic (fixed and floating point)</p></details></li></ul></div></article></body></html>