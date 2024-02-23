layout: page
title: "PAGE-TITLE"
permalink: /URL-PATH

<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Reciept Reader</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>




<style type="text/css">
    pre { line-height: 125%; }
td.linenos .normal { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
span.linenos { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
td.linenos .special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
span.linenos.special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
.highlight .hll { background-color: var(--jp-cell-editor-active-background) }
.highlight { background: var(--jp-cell-editor-background); color: var(--jp-mirror-editor-variable-color) }
.highlight .c { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment */
.highlight .err { color: var(--jp-mirror-editor-error-color) } /* Error */
.highlight .k { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword */
.highlight .o { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator */
.highlight .p { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation */
.highlight .ch { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Multiline */
.highlight .cp { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Preproc */
.highlight .cpf { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Single */
.highlight .cs { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Special */
.highlight .kc { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Pseudo */
.highlight .kr { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Type */
.highlight .m { color: var(--jp-mirror-editor-number-color) } /* Literal.Number */
.highlight .s { color: var(--jp-mirror-editor-string-color) } /* Literal.String */
.highlight .ow { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator.Word */
.highlight .w { color: var(--jp-mirror-editor-variable-color) } /* Text.Whitespace */
.highlight .mb { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Bin */
.highlight .mf { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Float */
.highlight .mh { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Hex */
.highlight .mi { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer */
.highlight .mo { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Oct */
.highlight .sa { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Affix */
.highlight .sb { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Backtick */
.highlight .sc { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Char */
.highlight .dl { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Delimiter */
.highlight .sd { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Doc */
.highlight .s2 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Double */
.highlight .se { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Escape */
.highlight .sh { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Heredoc */
.highlight .si { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Interpol */
.highlight .sx { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Other */
.highlight .sr { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Regex */
.highlight .s1 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Single */
.highlight .ss { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Symbol */
.highlight .il { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer.Long */
  </style>



<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
 * Mozilla scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */
[data-jp-theme-scrollbars='true'] {
  scrollbar-color: rgb(var(--jp-scrollbar-thumb-color))
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar. These selectors
 * will match lower in the tree, and so will override the above */
[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
}

/* tiny scrollbar */

.jp-scrollbar-tiny {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
  scrollbar-width: thin;
}

/*
 * Webkit scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar,
[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-corner {
  background: var(--jp-scrollbar-background-color);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-thumb {
  background: rgb(var(--jp-scrollbar-thumb-color));
  border: var(--jp-scrollbar-thumb-margin) solid transparent;
  background-clip: content-box;
  border-radius: var(--jp-scrollbar-thumb-radius);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-track:horizontal {
  border-left: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
  border-right: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
}

[data-jp-theme-scrollbars='true'] ::-webkit-scrollbar-track:vertical {
  border-top: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
  border-bottom: var(--jp-scrollbar-endpad) solid
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar */

[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar::-webkit-scrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar::-webkit-scrollbar,
[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-corner,
[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-corner {
  background-color: transparent;
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-thumb,
[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-thumb {
  background: rgba(var(--jp-scrollbar-thumb-color), 0.5);
  border: var(--jp-scrollbar-thumb-margin) solid transparent;
  background-clip: content-box;
  border-radius: var(--jp-scrollbar-thumb-radius);
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-hscrollbar::-webkit-scrollbar-track:horizontal {
  border-left: var(--jp-scrollbar-endpad) solid transparent;
  border-right: var(--jp-scrollbar-endpad) solid transparent;
}

[data-jp-theme-scrollbars='true']
  .CodeMirror-vscrollbar::-webkit-scrollbar-track:vertical {
  border-top: var(--jp-scrollbar-endpad) solid transparent;
  border-bottom: var(--jp-scrollbar-endpad) solid transparent;
}

/* tiny scrollbar */

.jp-scrollbar-tiny::-webkit-scrollbar,
.jp-scrollbar-tiny::-webkit-scrollbar-corner {
  background-color: transparent;
  height: 4px;
  width: 4px;
}

.jp-scrollbar-tiny::-webkit-scrollbar-thumb {
  background: rgba(var(--jp-scrollbar-thumb-color), 0.5);
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:horizontal {
  border-left: 0px solid transparent;
  border-right: 0px solid transparent;
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:vertical {
  border-top: 0px solid transparent;
  border-bottom: 0px solid transparent;
}

/*
 * Phosphor
 */

.lm-ScrollBar[data-orientation='horizontal'] {
  min-height: 16px;
  max-height: 16px;
  min-width: 45px;
  border-top: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] {
  min-width: 16px;
  max-width: 16px;
  min-height: 45px;
  border-left: 1px solid #a0a0a0;
}

.lm-ScrollBar-button {
  background-color: #f0f0f0;
  background-position: center center;
  min-height: 15px;
  max-height: 15px;
  min-width: 15px;
  max-width: 15px;
}

.lm-ScrollBar-button:hover {
  background-color: #dadada;
}

.lm-ScrollBar-button.lm-mod-active {
  background-color: #cdcdcd;
}

.lm-ScrollBar-track {
  background: #f0f0f0;
}

.lm-ScrollBar-thumb {
  background: #cdcdcd;
}

.lm-ScrollBar-thumb:hover {
  background: #bababa;
}

.lm-ScrollBar-thumb.lm-mod-active {
  background: #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal'] .lm-ScrollBar-thumb {
  height: 100%;
  min-width: 15px;
  border-left: 1px solid #a0a0a0;
  border-right: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] .lm-ScrollBar-thumb {
  width: 100%;
  min-height: 15px;
  border-top: 1px solid #a0a0a0;
  border-bottom: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-left);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-right);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-up);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-down);
  background-size: 17px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-Widget, /* </DEPRECATED> */
.lm-Widget {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  cursor: default;
}


/* <DEPRECATED> */ .p-Widget.p-mod-hidden, /* </DEPRECATED> */
.lm-Widget.lm-mod-hidden {
  display: none !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-CommandPalette, /* </DEPRECATED> */
.lm-CommandPalette {
  display: flex;
  flex-direction: column;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-CommandPalette-search, /* </DEPRECATED> */
.lm-CommandPalette-search {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-content, /* </DEPRECATED> */
.lm-CommandPalette-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  min-height: 0;
  overflow: auto;
  list-style-type: none;
}


/* <DEPRECATED> */ .p-CommandPalette-header, /* </DEPRECATED> */
.lm-CommandPalette-header {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}


/* <DEPRECATED> */ .p-CommandPalette-item, /* </DEPRECATED> */
.lm-CommandPalette-item {
  display: flex;
  flex-direction: row;
}


/* <DEPRECATED> */ .p-CommandPalette-itemIcon, /* </DEPRECATED> */
.lm-CommandPalette-itemIcon {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-itemContent, /* </DEPRECATED> */
.lm-CommandPalette-itemContent {
  flex: 1 1 auto;
  overflow: hidden;
}


/* <DEPRECATED> */ .p-CommandPalette-itemShortcut, /* </DEPRECATED> */
.lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-CommandPalette-itemLabel, /* </DEPRECATED> */
.lm-CommandPalette-itemLabel {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.lm-close-icon {
	border:1px solid transparent;
  background-color: transparent;
  position: absolute;
	z-index:1;
	right:3%;
	top: 0;
	bottom: 0;
	margin: auto;
	padding: 7px 0;
	display: none;
	vertical-align: middle;
  outline: 0;
  cursor: pointer;
}
.lm-close-icon:after {
	content: "X";
	display: block;
	width: 15px;
	height: 15px;
	text-align: center;
	color:#000;
	font-weight: normal;
	font-size: 12px;
	cursor: pointer;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-DockPanel, /* </DEPRECATED> */
.lm-DockPanel {
  z-index: 0;
}


/* <DEPRECATED> */ .p-DockPanel-widget, /* </DEPRECATED> */
.lm-DockPanel-widget {
  z-index: 0;
}


/* <DEPRECATED> */ .p-DockPanel-tabBar, /* </DEPRECATED> */
.lm-DockPanel-tabBar {
  z-index: 1;
}


/* <DEPRECATED> */ .p-DockPanel-handle, /* </DEPRECATED> */
.lm-DockPanel-handle {
  z-index: 2;
}


/* <DEPRECATED> */ .p-DockPanel-handle.p-mod-hidden, /* </DEPRECATED> */
.lm-DockPanel-handle.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-DockPanel-handle:after, /* </DEPRECATED> */
.lm-DockPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='horizontal'],
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='horizontal'] {
  cursor: ew-resize;
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='vertical'],
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='vertical'] {
  cursor: ns-resize;
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='horizontal']:after,
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='horizontal']:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}


/* <DEPRECATED> */
.p-DockPanel-handle[data-orientation='vertical']:after,
/* </DEPRECATED> */
.lm-DockPanel-handle[data-orientation='vertical']:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}


/* <DEPRECATED> */ .p-DockPanel-overlay, /* </DEPRECATED> */
.lm-DockPanel-overlay {
  z-index: 3;
  box-sizing: border-box;
  pointer-events: none;
}


/* <DEPRECATED> */ .p-DockPanel-overlay.p-mod-hidden, /* </DEPRECATED> */
.lm-DockPanel-overlay.lm-mod-hidden {
  display: none !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-Menu, /* </DEPRECATED> */
.lm-Menu {
  z-index: 10000;
  position: absolute;
  white-space: nowrap;
  overflow-x: hidden;
  overflow-y: auto;
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-Menu-content, /* </DEPRECATED> */
.lm-Menu-content {
  margin: 0;
  padding: 0;
  display: table;
  list-style-type: none;
}


/* <DEPRECATED> */ .p-Menu-item, /* </DEPRECATED> */
.lm-Menu-item {
  display: table-row;
}


/* <DEPRECATED> */
.p-Menu-item.p-mod-hidden,
.p-Menu-item.p-mod-collapsed,
/* </DEPRECATED> */
.lm-Menu-item.lm-mod-hidden,
.lm-Menu-item.lm-mod-collapsed {
  display: none !important;
}


/* <DEPRECATED> */
.p-Menu-itemIcon,
.p-Menu-itemSubmenuIcon,
/* </DEPRECATED> */
.lm-Menu-itemIcon,
.lm-Menu-itemSubmenuIcon {
  display: table-cell;
  text-align: center;
}


/* <DEPRECATED> */ .p-Menu-itemLabel, /* </DEPRECATED> */
.lm-Menu-itemLabel {
  display: table-cell;
  text-align: left;
}


/* <DEPRECATED> */ .p-Menu-itemShortcut, /* </DEPRECATED> */
.lm-Menu-itemShortcut {
  display: table-cell;
  text-align: right;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-MenuBar, /* </DEPRECATED> */
.lm-MenuBar {
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-MenuBar-content, /* </DEPRECATED> */
.lm-MenuBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: row;
  list-style-type: none;
}


/* <DEPRECATED> */ .p--MenuBar-item, /* </DEPRECATED> */
.lm-MenuBar-item {
  box-sizing: border-box;
}


/* <DEPRECATED> */
.p-MenuBar-itemIcon,
.p-MenuBar-itemLabel,
/* </DEPRECATED> */
.lm-MenuBar-itemIcon,
.lm-MenuBar-itemLabel {
  display: inline-block;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-ScrollBar, /* </DEPRECATED> */
.lm-ScrollBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */
.p-ScrollBar[data-orientation='horizontal'],
/* </DEPRECATED> */
.lm-ScrollBar[data-orientation='horizontal'] {
  flex-direction: row;
}


/* <DEPRECATED> */
.p-ScrollBar[data-orientation='vertical'],
/* </DEPRECATED> */
.lm-ScrollBar[data-orientation='vertical'] {
  flex-direction: column;
}


/* <DEPRECATED> */ .p-ScrollBar-button, /* </DEPRECATED> */
.lm-ScrollBar-button {
  box-sizing: border-box;
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-ScrollBar-track, /* </DEPRECATED> */
.lm-ScrollBar-track {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  flex: 1 1 auto;
}


/* <DEPRECATED> */ .p-ScrollBar-thumb, /* </DEPRECATED> */
.lm-ScrollBar-thumb {
  box-sizing: border-box;
  position: absolute;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-SplitPanel-child, /* </DEPRECATED> */
.lm-SplitPanel-child {
  z-index: 0;
}


/* <DEPRECATED> */ .p-SplitPanel-handle, /* </DEPRECATED> */
.lm-SplitPanel-handle {
  z-index: 1;
}


/* <DEPRECATED> */ .p-SplitPanel-handle.p-mod-hidden, /* </DEPRECATED> */
.lm-SplitPanel-handle.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-SplitPanel-handle:after, /* </DEPRECATED> */
.lm-SplitPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='horizontal'] > .p-SplitPanel-handle,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle {
  cursor: ew-resize;
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='vertical'] > .p-SplitPanel-handle,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle {
  cursor: ns-resize;
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='horizontal'] > .p-SplitPanel-handle:after,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}


/* <DEPRECATED> */
.p-SplitPanel[data-orientation='vertical'] > .p-SplitPanel-handle:after,
/* </DEPRECATED> */
.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-TabBar, /* </DEPRECATED> */
.lm-TabBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}


/* <DEPRECATED> */ .p-TabBar[data-orientation='horizontal'], /* </DEPRECATED> */
.lm-TabBar[data-orientation='horizontal'] {
  flex-direction: row;
  align-items: flex-end;
}


/* <DEPRECATED> */ .p-TabBar[data-orientation='vertical'], /* </DEPRECATED> */
.lm-TabBar[data-orientation='vertical'] {
  flex-direction: column;
  align-items: flex-end;
}


/* <DEPRECATED> */ .p-TabBar-content, /* </DEPRECATED> */
.lm-TabBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex: 1 1 auto;
  list-style-type: none;
}


/* <DEPRECATED> */
.p-TabBar[data-orientation='horizontal'] > .p-TabBar-content,
/* </DEPRECATED> */
.lm-TabBar[data-orientation='horizontal'] > .lm-TabBar-content {
  flex-direction: row;
}


/* <DEPRECATED> */
.p-TabBar[data-orientation='vertical'] > .p-TabBar-content,
/* </DEPRECATED> */
.lm-TabBar[data-orientation='vertical'] > .lm-TabBar-content {
  flex-direction: column;
}


/* <DEPRECATED> */ .p-TabBar-tab, /* </DEPRECATED> */
.lm-TabBar-tab {
  display: flex;
  flex-direction: row;
  box-sizing: border-box;
  overflow: hidden;
}


/* <DEPRECATED> */
.p-TabBar-tabIcon,
.p-TabBar-tabCloseIcon,
/* </DEPRECATED> */
.lm-TabBar-tabIcon,
.lm-TabBar-tabCloseIcon {
  flex: 0 0 auto;
}


/* <DEPRECATED> */ .p-TabBar-tabLabel, /* </DEPRECATED> */
.lm-TabBar-tabLabel {
  flex: 1 1 auto;
  overflow: hidden;
  white-space: nowrap;
}


.lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing : border-box;
}


/* <DEPRECATED> */ .p-TabBar-tab.p-mod-hidden, /* </DEPRECATED> */
.lm-TabBar-tab.lm-mod-hidden {
  display: none !important;
}


.lm-TabBar-addButton.lm-mod-hidden {
  display: none !important;
}


/* <DEPRECATED> */ .p-TabBar.p-mod-dragging .p-TabBar-tab, /* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging .lm-TabBar-tab {
  position: relative;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging[data-orientation='horizontal'] .p-TabBar-tab,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging[data-orientation='horizontal'] .lm-TabBar-tab {
  left: 0;
  transition: left 150ms ease;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging[data-orientation='vertical'] .p-TabBar-tab,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging[data-orientation='vertical'] .lm-TabBar-tab {
  top: 0;
  transition: top 150ms ease;
}


/* <DEPRECATED> */
.p-TabBar.p-mod-dragging .p-TabBar-tab.p-mod-dragging,
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging .lm-TabBar-tab.lm-mod-dragging {
  transition: none;
}

.lm-TabBar-tabLabel .lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing : border-box;
  background: inherit;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ .p-TabPanel-tabBar, /* </DEPRECATED> */
.lm-TabPanel-tabBar {
  z-index: 1;
}


/* <DEPRECATED> */ .p-TabPanel-stackedPanel, /* </DEPRECATED> */
.lm-TabPanel-stackedPanel {
  z-index: 0;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

@charset "UTF-8";
html{
  -webkit-box-sizing:border-box;
          box-sizing:border-box; }

*,
*::before,
*::after{
  -webkit-box-sizing:inherit;
          box-sizing:inherit; }

body{
  font-size:14px;
  font-weight:400;
  letter-spacing:0;
  line-height:1.28581;
  text-transform:none;
  color:#182026;
  font-family:-apple-system, "BlinkMacSystemFont", "Segoe UI", "Roboto", "Oxygen", "Ubuntu", "Cantarell", "Open Sans", "Helvetica Neue", "Icons16", sans-serif; }

p{
  margin-bottom:10px;
  margin-top:0; }

small{
  font-size:12px; }

strong{
  font-weight:600; }

::-moz-selection{
  background:rgba(125, 188, 255, 0.6); }

::selection{
  background:rgba(125, 188, 255, 0.6); }
.bp3-heading{
  color:#182026;
  font-weight:600;
  margin:0 0 10px;
  padding:0; }
  .bp3-dark .bp3-heading{
    color:#f5f8fa; }

h1.bp3-heading, .bp3-running-text h1{
  font-size:36px;
  line-height:40px; }

h2.bp3-heading, .bp3-running-text h2{
  font-size:28px;
  line-height:32px; }

h3.bp3-heading, .bp3-running-text h3{
  font-size:22px;
  line-height:25px; }

h4.bp3-heading, .bp3-running-text h4{
  font-size:18px;
  line-height:21px; }

h5.bp3-heading, .bp3-running-text h5{
  font-size:16px;
  line-height:19px; }

h6.bp3-heading, .bp3-running-text h6{
  font-size:14px;
  line-height:16px; }
.bp3-ui-text{
  font-size:14px;
  font-weight:400;
  letter-spacing:0;
  line-height:1.28581;
  text-transform:none; }

.bp3-monospace-text{
  font-family:monospace;
  text-transform:none; }

.bp3-text-muted{
  color:#5c7080; }
  .bp3-dark .bp3-text-muted{
    color:#a7b6c2; }

.bp3-text-disabled{
  color:rgba(92, 112, 128, 0.6); }
  .bp3-dark .bp3-text-disabled{
    color:rgba(167, 182, 194, 0.6); }

.bp3-text-overflow-ellipsis{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal; }
.bp3-running-text{
  font-size:14px;
  line-height:1.5; }
  .bp3-running-text h1{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h1{
      color:#f5f8fa; }
  .bp3-running-text h2{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h2{
      color:#f5f8fa; }
  .bp3-running-text h3{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h3{
      color:#f5f8fa; }
  .bp3-running-text h4{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h4{
      color:#f5f8fa; }
  .bp3-running-text h5{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h5{
      color:#f5f8fa; }
  .bp3-running-text h6{
    color:#182026;
    font-weight:600;
    margin-bottom:20px;
    margin-top:40px; }
    .bp3-dark .bp3-running-text h6{
      color:#f5f8fa; }
  .bp3-running-text hr{
    border:none;
    border-bottom:1px solid rgba(16, 22, 26, 0.15);
    margin:20px 0; }
    .bp3-dark .bp3-running-text hr{
      border-color:rgba(255, 255, 255, 0.15); }
  .bp3-running-text p{
    margin:0 0 10px;
    padding:0; }

.bp3-text-large{
  font-size:16px; }

.bp3-text-small{
  font-size:12px; }
a{
  color:#106ba3;
  text-decoration:none; }
  a:hover{
    color:#106ba3;
    cursor:pointer;
    text-decoration:underline; }
  a .bp3-icon, a .bp3-icon-standard, a .bp3-icon-large{
    color:inherit; }
  a code,
  .bp3-dark a code{
    color:inherit; }
  .bp3-dark a,
  .bp3-dark a:hover{
    color:#48aff0; }
    .bp3-dark a .bp3-icon, .bp3-dark a .bp3-icon-standard, .bp3-dark a .bp3-icon-large,
    .bp3-dark a:hover .bp3-icon,
    .bp3-dark a:hover .bp3-icon-standard,
    .bp3-dark a:hover .bp3-icon-large{
      color:inherit; }
.bp3-running-text code, .bp3-code{
  font-family:monospace;
  text-transform:none;
  background:rgba(255, 255, 255, 0.7);
  border-radius:3px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2);
  color:#5c7080;
  font-size:smaller;
  padding:2px 5px; }
  .bp3-dark .bp3-running-text code, .bp3-running-text .bp3-dark code, .bp3-dark .bp3-code{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#a7b6c2; }
  .bp3-running-text a > code, a > .bp3-code{
    color:#137cbd; }
    .bp3-dark .bp3-running-text a > code, .bp3-running-text .bp3-dark a > code, .bp3-dark a > .bp3-code{
      color:inherit; }

.bp3-running-text pre, .bp3-code-block{
  font-family:monospace;
  text-transform:none;
  background:rgba(255, 255, 255, 0.7);
  border-radius:3px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
  color:#182026;
  display:block;
  font-size:13px;
  line-height:1.4;
  margin:10px 0;
  padding:13px 15px 12px;
  word-break:break-all;
  word-wrap:break-word; }
  .bp3-dark .bp3-running-text pre, .bp3-running-text .bp3-dark pre, .bp3-dark .bp3-code-block{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
  .bp3-running-text pre > code, .bp3-code-block > code{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:inherit;
    font-size:inherit;
    padding:0; }

.bp3-running-text kbd, .bp3-key{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  color:#5c7080;
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  font-family:inherit;
  font-size:12px;
  height:24px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  line-height:24px;
  min-width:24px;
  padding:3px 6px;
  vertical-align:middle; }
  .bp3-running-text kbd .bp3-icon, .bp3-key .bp3-icon, .bp3-running-text kbd .bp3-icon-standard, .bp3-key .bp3-icon-standard, .bp3-running-text kbd .bp3-icon-large, .bp3-key .bp3-icon-large{
    margin-right:5px; }
  .bp3-dark .bp3-running-text kbd, .bp3-running-text .bp3-dark kbd, .bp3-dark .bp3-key{
    background:#394b59;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#a7b6c2; }
.bp3-running-text blockquote, .bp3-blockquote{
  border-left:solid 4px rgba(167, 182, 194, 0.5);
  margin:0 0 10px;
  padding:0 20px; }
  .bp3-dark .bp3-running-text blockquote, .bp3-running-text .bp3-dark blockquote, .bp3-dark .bp3-blockquote{
    border-color:rgba(115, 134, 148, 0.5); }
.bp3-running-text ul,
.bp3-running-text ol, .bp3-list{
  margin:10px 0;
  padding-left:30px; }
  .bp3-running-text ul li:not(:last-child), .bp3-running-text ol li:not(:last-child), .bp3-list li:not(:last-child){
    margin-bottom:5px; }
  .bp3-running-text ul ol, .bp3-running-text ol ol, .bp3-list ol,
  .bp3-running-text ul ul,
  .bp3-running-text ol ul,
  .bp3-list ul{
    margin-top:5px; }

.bp3-list-unstyled{
  list-style:none;
  margin:0;
  padding:0; }
  .bp3-list-unstyled li{
    padding:0; }
.bp3-rtl{
  text-align:right; }

.bp3-dark{
  color:#f5f8fa; }

:focus{
  outline:rgba(19, 124, 189, 0.6) auto 2px;
  outline-offset:2px;
  -moz-outline-radius:6px; }

.bp3-focus-disabled :focus{
  outline:none !important; }
  .bp3-focus-disabled :focus ~ .bp3-control-indicator{
    outline:none !important; }

.bp3-alert{
  max-width:400px;
  padding:20px; }

.bp3-alert-body{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }
  .bp3-alert-body .bp3-icon{
    font-size:40px;
    margin-right:20px;
    margin-top:0; }

.bp3-alert-contents{
  word-break:break-word; }

.bp3-alert-footer{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:reverse;
      -ms-flex-direction:row-reverse;
          flex-direction:row-reverse;
  margin-top:10px; }
  .bp3-alert-footer .bp3-button{
    margin-left:10px; }
.bp3-breadcrumbs{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  cursor:default;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-wrap:wrap;
      flex-wrap:wrap;
  height:30px;
  list-style:none;
  margin:0;
  padding:0; }
  .bp3-breadcrumbs > li{
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex; }
    .bp3-breadcrumbs > li::after{
      background:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M10.71 7.29l-4-4a1.003 1.003 0 00-1.42 1.42L8.59 8 5.3 11.29c-.19.18-.3.43-.3.71a1.003 1.003 0 001.71.71l4-4c.18-.18.29-.43.29-.71 0-.28-.11-.53-.29-.71z' fill='%235C7080'/%3e%3c/svg%3e");
      content:"";
      display:block;
      height:16px;
      margin:0 5px;
      width:16px; }
    .bp3-breadcrumbs > li:last-of-type::after{
      display:none; }

.bp3-breadcrumb,
.bp3-breadcrumb-current,
.bp3-breadcrumbs-collapsed{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  font-size:16px; }

.bp3-breadcrumb,
.bp3-breadcrumbs-collapsed{
  color:#5c7080; }

.bp3-breadcrumb:hover{
  text-decoration:none; }

.bp3-breadcrumb.bp3-disabled{
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-breadcrumb .bp3-icon{
  margin-right:5px; }

.bp3-breadcrumb-current{
  color:inherit;
  font-weight:600; }
  .bp3-breadcrumb-current .bp3-input{
    font-size:inherit;
    font-weight:inherit;
    vertical-align:baseline; }

.bp3-breadcrumbs-collapsed{
  background:#ced9e0;
  border:none;
  border-radius:3px;
  cursor:pointer;
  margin-right:2px;
  padding:1px 5px;
  vertical-align:text-bottom; }
  .bp3-breadcrumbs-collapsed::before{
    background:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cg fill='%235C7080'%3e%3ccircle cx='2' cy='8.03' r='2'/%3e%3ccircle cx='14' cy='8.03' r='2'/%3e%3ccircle cx='8' cy='8.03' r='2'/%3e%3c/g%3e%3c/svg%3e") center no-repeat;
    content:"";
    display:block;
    height:16px;
    width:16px; }
  .bp3-breadcrumbs-collapsed:hover{
    background:#bfccd6;
    color:#182026;
    text-decoration:none; }

.bp3-dark .bp3-breadcrumb,
.bp3-dark .bp3-breadcrumbs-collapsed{
  color:#a7b6c2; }

.bp3-dark .bp3-breadcrumbs > li::after{
  color:#a7b6c2; }

.bp3-dark .bp3-breadcrumb.bp3-disabled{
  color:rgba(167, 182, 194, 0.6); }

.bp3-dark .bp3-breadcrumb-current{
  color:#f5f8fa; }

.bp3-dark .bp3-breadcrumbs-collapsed{
  background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-breadcrumbs-collapsed:hover{
    background:rgba(16, 22, 26, 0.6);
    color:#f5f8fa; }
.bp3-button{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  border:none;
  border-radius:3px;
  cursor:pointer;
  font-size:14px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  padding:5px 10px;
  text-align:left;
  vertical-align:middle;
  min-height:30px;
  min-width:30px; }
  .bp3-button > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-button > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-button::before,
  .bp3-button > *{
    margin-right:7px; }
  .bp3-button:empty::before,
  .bp3-button > :last-child{
    margin-right:0; }
  .bp3-button:empty{
    padding:0 !important; }
  .bp3-button:disabled, .bp3-button.bp3-disabled{
    cursor:not-allowed; }
  .bp3-button.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-button.bp3-align-right,
  .bp3-align-right .bp3-button{
    text-align:right; }
  .bp3-button.bp3-align-left,
  .bp3-align-left .bp3-button{
    text-align:left; }
  .bp3-button:not([class*="bp3-intent-"]){
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    color:#182026; }
    .bp3-button:not([class*="bp3-intent-"]):hover{
      background-clip:padding-box;
      background-color:#ebf1f5;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
    .bp3-button:not([class*="bp3-intent-"]):active, .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      background-color:#d8e1e8;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button:not([class*="bp3-intent-"]):disabled, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled{
      background-color:rgba(206, 217, 224, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed;
      outline:none; }
      .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active, .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active:hover, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active:hover{
        background:rgba(206, 217, 224, 0.7); }
  .bp3-button.bp3-intent-primary{
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-primary:hover, .bp3-button.bp3-intent-primary:active, .bp3-button.bp3-intent-primary.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-primary:hover{
      background-color:#106ba3;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-primary:active, .bp3-button.bp3-intent-primary.bp3-active{
      background-color:#0e5a8a;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-primary:disabled, .bp3-button.bp3-intent-primary.bp3-disabled{
      background-color:rgba(19, 124, 189, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-success{
    background-color:#0f9960;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-success:hover, .bp3-button.bp3-intent-success:active, .bp3-button.bp3-intent-success.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-success:hover{
      background-color:#0d8050;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-success:active, .bp3-button.bp3-intent-success.bp3-active{
      background-color:#0a6640;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-success:disabled, .bp3-button.bp3-intent-success.bp3-disabled{
      background-color:rgba(15, 153, 96, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-warning{
    background-color:#d9822b;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-warning:hover, .bp3-button.bp3-intent-warning:active, .bp3-button.bp3-intent-warning.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-warning:hover{
      background-color:#bf7326;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-warning:active, .bp3-button.bp3-intent-warning.bp3-active{
      background-color:#a66321;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-warning:disabled, .bp3-button.bp3-intent-warning.bp3-disabled{
      background-color:rgba(217, 130, 43, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-danger{
    background-color:#db3737;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
    .bp3-button.bp3-intent-danger:hover, .bp3-button.bp3-intent-danger:active, .bp3-button.bp3-intent-danger.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-danger:hover{
      background-color:#c23030;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-danger:active, .bp3-button.bp3-intent-danger.bp3-active{
      background-color:#a82a2a;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-button.bp3-intent-danger:disabled, .bp3-button.bp3-intent-danger.bp3-disabled{
      background-color:rgba(219, 55, 55, 0.5);
      background-image:none;
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button[class*="bp3-intent-"] .bp3-button-spinner .bp3-spinner-head{
    stroke:#ffffff; }
  .bp3-button.bp3-large,
  .bp3-large .bp3-button{
    min-height:40px;
    min-width:40px;
    font-size:16px;
    padding:5px 15px; }
    .bp3-button.bp3-large::before,
    .bp3-button.bp3-large > *,
    .bp3-large .bp3-button::before,
    .bp3-large .bp3-button > *{
      margin-right:10px; }
    .bp3-button.bp3-large:empty::before,
    .bp3-button.bp3-large > :last-child,
    .bp3-large .bp3-button:empty::before,
    .bp3-large .bp3-button > :last-child{
      margin-right:0; }
  .bp3-button.bp3-small,
  .bp3-small .bp3-button{
    min-height:24px;
    min-width:24px;
    padding:0 7px; }
  .bp3-button.bp3-loading{
    position:relative; }
    .bp3-button.bp3-loading[class*="bp3-icon-"]::before{
      visibility:hidden; }
    .bp3-button.bp3-loading .bp3-button-spinner{
      margin:0;
      position:absolute; }
    .bp3-button.bp3-loading > :not(.bp3-button-spinner){
      visibility:hidden; }
  .bp3-button[class*="bp3-icon-"]::before{
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-style:normal;
    font-weight:400;
    line-height:1;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    color:#5c7080; }
  .bp3-button .bp3-icon, .bp3-button .bp3-icon-standard, .bp3-button .bp3-icon-large{
    color:#5c7080; }
    .bp3-button .bp3-icon.bp3-align-right, .bp3-button .bp3-icon-standard.bp3-align-right, .bp3-button .bp3-icon-large.bp3-align-right{
      margin-left:7px; }
  .bp3-button .bp3-icon:first-child:last-child,
  .bp3-button .bp3-spinner + .bp3-icon:last-child{
    margin:0 -7px; }
  .bp3-dark .bp3-button:not([class*="bp3-intent-"]){
    background-color:#394b59;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):hover, .bp3-dark .bp3-button:not([class*="bp3-intent-"]):active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      color:#f5f8fa; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):hover{
      background-color:#30404d;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      background-color:#202b33;
      background-image:none;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):disabled, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-disabled{
      background-color:rgba(57, 75, 89, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
      .bp3-dark .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active{
        background:rgba(57, 75, 89, 0.7); }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-button-spinner .bp3-spinner-head{
      background:rgba(16, 22, 26, 0.5);
      stroke:#8a9ba8; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"])[class*="bp3-icon-"]::before{
      color:#a7b6c2; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon, .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon-standard, .bp3-dark .bp3-button:not([class*="bp3-intent-"]) .bp3-icon-large{
      color:#a7b6c2; }
  .bp3-dark .bp3-button[class*="bp3-intent-"]{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:hover{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:active, .bp3-dark .bp3-button[class*="bp3-intent-"].bp3-active{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-button[class*="bp3-intent-"]:disabled, .bp3-dark .bp3-button[class*="bp3-intent-"].bp3-disabled{
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(255, 255, 255, 0.3); }
    .bp3-dark .bp3-button[class*="bp3-intent-"] .bp3-button-spinner .bp3-spinner-head{
      stroke:#8a9ba8; }
  .bp3-button:disabled::before,
  .bp3-button:disabled .bp3-icon, .bp3-button:disabled .bp3-icon-standard, .bp3-button:disabled .bp3-icon-large, .bp3-button.bp3-disabled::before,
  .bp3-button.bp3-disabled .bp3-icon, .bp3-button.bp3-disabled .bp3-icon-standard, .bp3-button.bp3-disabled .bp3-icon-large, .bp3-button[class*="bp3-intent-"]::before,
  .bp3-button[class*="bp3-intent-"] .bp3-icon, .bp3-button[class*="bp3-intent-"] .bp3-icon-standard, .bp3-button[class*="bp3-intent-"] .bp3-icon-large{
    color:inherit !important; }
  .bp3-button.bp3-minimal{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none; }
    .bp3-button.bp3-minimal:hover{
      background:rgba(167, 182, 194, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026;
      text-decoration:none; }
    .bp3-button.bp3-minimal:active, .bp3-button.bp3-minimal.bp3-active{
      background:rgba(115, 134, 148, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026; }
    .bp3-button.bp3-minimal:disabled, .bp3-button.bp3-minimal:disabled:hover, .bp3-button.bp3-minimal.bp3-disabled, .bp3-button.bp3-minimal.bp3-disabled:hover{
      background:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed; }
      .bp3-button.bp3-minimal:disabled.bp3-active, .bp3-button.bp3-minimal:disabled:hover.bp3-active, .bp3-button.bp3-minimal.bp3-disabled.bp3-active, .bp3-button.bp3-minimal.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button.bp3-minimal{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:inherit; }
      .bp3-dark .bp3-button.bp3-minimal:hover, .bp3-dark .bp3-button.bp3-minimal:active, .bp3-dark .bp3-button.bp3-minimal.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none; }
      .bp3-dark .bp3-button.bp3-minimal:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button.bp3-minimal:active, .bp3-dark .bp3-button.bp3-minimal.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button.bp3-minimal:disabled, .bp3-dark .bp3-button.bp3-minimal:disabled:hover, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled:hover{
        background:none;
        color:rgba(167, 182, 194, 0.6);
        cursor:not-allowed; }
        .bp3-dark .bp3-button.bp3-minimal:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal:disabled:hover.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:hover, .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:disabled, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-primary:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-success{
      color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:hover, .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button.bp3-minimal.bp3-intent-success:disabled, .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-success:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:hover, .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button.bp3-minimal.bp3-intent-warning:disabled, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-warning:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-danger{
      color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:hover, .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button.bp3-minimal.bp3-intent-danger:disabled, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button.bp3-minimal.bp3-intent-danger:disabled.bp3-active, .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button.bp3-minimal.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }
  .bp3-button.bp3-outlined{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    border:1px solid rgba(24, 32, 38, 0.2);
    -webkit-box-sizing:border-box;
            box-sizing:border-box; }
    .bp3-button.bp3-outlined:hover{
      background:rgba(167, 182, 194, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026;
      text-decoration:none; }
    .bp3-button.bp3-outlined:active, .bp3-button.bp3-outlined.bp3-active{
      background:rgba(115, 134, 148, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026; }
    .bp3-button.bp3-outlined:disabled, .bp3-button.bp3-outlined:disabled:hover, .bp3-button.bp3-outlined.bp3-disabled, .bp3-button.bp3-outlined.bp3-disabled:hover{
      background:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed; }
      .bp3-button.bp3-outlined:disabled.bp3-active, .bp3-button.bp3-outlined:disabled:hover.bp3-active, .bp3-button.bp3-outlined.bp3-disabled.bp3-active, .bp3-button.bp3-outlined.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button.bp3-outlined{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:inherit; }
      .bp3-dark .bp3-button.bp3-outlined:hover, .bp3-dark .bp3-button.bp3-outlined:active, .bp3-dark .bp3-button.bp3-outlined.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none; }
      .bp3-dark .bp3-button.bp3-outlined:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button.bp3-outlined:active, .bp3-dark .bp3-button.bp3-outlined.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button.bp3-outlined:disabled, .bp3-dark .bp3-button.bp3-outlined:disabled:hover, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled:hover{
        background:none;
        color:rgba(167, 182, 194, 0.6);
        cursor:not-allowed; }
        .bp3-dark .bp3-button.bp3-outlined:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined:disabled:hover.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:hover, .bp3-button.bp3-outlined.bp3-intent-primary:active, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:active, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-primary:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-success{
      color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:hover, .bp3-button.bp3-outlined.bp3-intent-success:active, .bp3-button.bp3-outlined.bp3-intent-success.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:active, .bp3-button.bp3-outlined.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-success:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:hover, .bp3-button.bp3-outlined.bp3-intent-warning:active, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:active, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-warning:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button.bp3-outlined.bp3-intent-danger{
      color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:hover, .bp3-button.bp3-outlined.bp3-intent-danger:active, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:active, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button.bp3-outlined.bp3-intent-danger:disabled.bp3-active, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button.bp3-outlined.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }
    .bp3-button.bp3-outlined:disabled, .bp3-button.bp3-outlined.bp3-disabled, .bp3-button.bp3-outlined:disabled:hover, .bp3-button.bp3-outlined.bp3-disabled:hover{
      border-color:rgba(92, 112, 128, 0.1); }
    .bp3-dark .bp3-button.bp3-outlined{
      border-color:rgba(255, 255, 255, 0.4); }
      .bp3-dark .bp3-button.bp3-outlined:disabled, .bp3-dark .bp3-button.bp3-outlined:disabled:hover, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-disabled:hover{
        border-color:rgba(255, 255, 255, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-primary{
      border-color:rgba(16, 107, 163, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
        border-color:rgba(16, 107, 163, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary{
        border-color:rgba(72, 175, 240, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-primary.bp3-disabled{
          border-color:rgba(72, 175, 240, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-success{
      border-color:rgba(13, 128, 80, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
        border-color:rgba(13, 128, 80, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success{
        border-color:rgba(61, 204, 145, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-success.bp3-disabled{
          border-color:rgba(61, 204, 145, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-warning{
      border-color:rgba(191, 115, 38, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
        border-color:rgba(191, 115, 38, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning{
        border-color:rgba(255, 179, 102, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-warning.bp3-disabled{
          border-color:rgba(255, 179, 102, 0.2); }
    .bp3-button.bp3-outlined.bp3-intent-danger{
      border-color:rgba(194, 48, 48, 0.6); }
      .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
        border-color:rgba(194, 48, 48, 0.2); }
      .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger{
        border-color:rgba(255, 115, 115, 0.6); }
        .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger:disabled, .bp3-dark .bp3-button.bp3-outlined.bp3-intent-danger.bp3-disabled{
          border-color:rgba(255, 115, 115, 0.2); }

a.bp3-button{
  text-align:center;
  text-decoration:none;
  -webkit-transition:none;
  transition:none; }
  a.bp3-button, a.bp3-button:hover, a.bp3-button:active{
    color:#182026; }
  a.bp3-button.bp3-disabled{
    color:rgba(92, 112, 128, 0.6); }

.bp3-button-text{
  -webkit-box-flex:0;
      -ms-flex:0 1 auto;
          flex:0 1 auto; }

.bp3-button.bp3-align-left .bp3-button-text, .bp3-button.bp3-align-right .bp3-button-text,
.bp3-button-group.bp3-align-left .bp3-button-text,
.bp3-button-group.bp3-align-right .bp3-button-text{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto; }
.bp3-button-group{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex; }
  .bp3-button-group .bp3-button{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    position:relative;
    z-index:4; }
    .bp3-button-group .bp3-button:focus{
      z-index:5; }
    .bp3-button-group .bp3-button:hover{
      z-index:6; }
    .bp3-button-group .bp3-button:active, .bp3-button-group .bp3-button.bp3-active{
      z-index:7; }
    .bp3-button-group .bp3-button:disabled, .bp3-button-group .bp3-button.bp3-disabled{
      z-index:3; }
    .bp3-button-group .bp3-button[class*="bp3-intent-"]{
      z-index:9; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:focus{
        z-index:10; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:hover{
        z-index:11; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:active, .bp3-button-group .bp3-button[class*="bp3-intent-"].bp3-active{
        z-index:12; }
      .bp3-button-group .bp3-button[class*="bp3-intent-"]:disabled, .bp3-button-group .bp3-button[class*="bp3-intent-"].bp3-disabled{
        z-index:8; }
  .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:first-child) .bp3-button,
  .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:first-child){
    border-bottom-left-radius:0;
    border-top-left-radius:0; }
  .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:last-child){
    border-bottom-right-radius:0;
    border-top-right-radius:0;
    margin-right:-1px; }
  .bp3-button-group.bp3-minimal .bp3-button{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none; }
    .bp3-button-group.bp3-minimal .bp3-button:hover{
      background:rgba(167, 182, 194, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026;
      text-decoration:none; }
    .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
      background:rgba(115, 134, 148, 0.3);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#182026; }
    .bp3-button-group.bp3-minimal .bp3-button:disabled, .bp3-button-group.bp3-minimal .bp3-button:disabled:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover{
      background:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed; }
      .bp3-button-group.bp3-minimal .bp3-button:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button:disabled:hover.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button-group.bp3-minimal .bp3-button{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:inherit; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:hover, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled:hover, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover{
        background:none;
        color:rgba(167, 182, 194, 0.6);
        cursor:not-allowed; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled:hover.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.15);
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(16, 107, 163, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
        stroke:#106ba3; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary{
        color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover{
          background:rgba(19, 124, 189, 0.2);
          color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
          background:rgba(19, 124, 189, 0.3);
          color:#48aff0; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled{
          background:none;
          color:rgba(72, 175, 240, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-disabled.bp3-active{
            background:rgba(19, 124, 189, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success{
      color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.15);
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#0d8050; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(13, 128, 80, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
        stroke:#0d8050; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success{
        color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:hover{
          background:rgba(15, 153, 96, 0.2);
          color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-active{
          background:rgba(15, 153, 96, 0.3);
          color:#3dcc91; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled{
          background:none;
          color:rgba(61, 204, 145, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-success.bp3-disabled.bp3-active{
            background:rgba(15, 153, 96, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning{
      color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.15);
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#bf7326; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(191, 115, 38, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
        stroke:#bf7326; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning{
        color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:hover{
          background:rgba(217, 130, 43, 0.2);
          color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-active{
          background:rgba(217, 130, 43, 0.3);
          color:#ffb366; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled{
          background:none;
          color:rgba(255, 179, 102, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-warning.bp3-disabled.bp3-active{
            background:rgba(217, 130, 43, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger{
      color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
        background:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.15);
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#c23030; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(194, 48, 48, 0.5); }
        .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
        stroke:#c23030; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger{
        color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:hover{
          background:rgba(219, 55, 55, 0.2);
          color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-active{
          background:rgba(219, 55, 55, 0.3);
          color:#ff7373; }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled{
          background:none;
          color:rgba(255, 115, 115, 0.5); }
          .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-danger.bp3-disabled.bp3-active{
            background:rgba(219, 55, 55, 0.3); }
  .bp3-button-group .bp3-popover-wrapper,
  .bp3-button-group .bp3-popover-target{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-button-group.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-button-group .bp3-button.bp3-fill,
  .bp3-button-group.bp3-fill .bp3-button:not(.bp3-fixed){
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-button-group.bp3-vertical{
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch;
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column;
    vertical-align:top; }
    .bp3-button-group.bp3-vertical.bp3-fill{
      height:100%;
      width:unset; }
    .bp3-button-group.bp3-vertical .bp3-button{
      margin-right:0 !important;
      width:100%; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:first-child .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:first-child{
      border-radius:3px 3px 0 0; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:last-child .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:last-child{
      border-radius:0 0 3px 3px; }
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
    .bp3-button-group.bp3-vertical:not(.bp3-minimal) > .bp3-button:not(:last-child){
      margin-bottom:-1px; }
  .bp3-button-group.bp3-align-left .bp3-button{
    text-align:left; }
  .bp3-dark .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-dark .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:last-child){
    margin-right:1px; }
  .bp3-dark .bp3-button-group.bp3-vertical > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-dark .bp3-button-group.bp3-vertical > .bp3-button:not(:last-child){
    margin-bottom:1px; }
.bp3-callout{
  font-size:14px;
  line-height:1.5;
  background-color:rgba(138, 155, 168, 0.15);
  border-radius:3px;
  padding:10px 12px 9px;
  position:relative;
  width:100%; }
  .bp3-callout[class*="bp3-icon-"]{
    padding-left:40px; }
    .bp3-callout[class*="bp3-icon-"]::before{
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-style:normal;
      font-weight:400;
      line-height:1;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased;
      color:#5c7080;
      left:10px;
      position:absolute;
      top:10px; }
  .bp3-callout.bp3-callout-icon{
    padding-left:40px; }
    .bp3-callout.bp3-callout-icon > .bp3-icon:first-child{
      color:#5c7080;
      left:10px;
      position:absolute;
      top:10px; }
  .bp3-callout .bp3-heading{
    line-height:20px;
    margin-bottom:5px;
    margin-top:0; }
    .bp3-callout .bp3-heading:last-child{
      margin-bottom:0; }
  .bp3-dark .bp3-callout{
    background-color:rgba(138, 155, 168, 0.2); }
    .bp3-dark .bp3-callout[class*="bp3-icon-"]::before{
      color:#a7b6c2; }
  .bp3-callout.bp3-intent-primary{
    background-color:rgba(19, 124, 189, 0.15); }
    .bp3-callout.bp3-intent-primary[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-primary > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-primary .bp3-heading{
      color:#106ba3; }
    .bp3-dark .bp3-callout.bp3-intent-primary{
      background-color:rgba(19, 124, 189, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-primary[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-primary > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-primary .bp3-heading{
        color:#48aff0; }
  .bp3-callout.bp3-intent-success{
    background-color:rgba(15, 153, 96, 0.15); }
    .bp3-callout.bp3-intent-success[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-success > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-success .bp3-heading{
      color:#0d8050; }
    .bp3-dark .bp3-callout.bp3-intent-success{
      background-color:rgba(15, 153, 96, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-success[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-success > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-success .bp3-heading{
        color:#3dcc91; }
  .bp3-callout.bp3-intent-warning{
    background-color:rgba(217, 130, 43, 0.15); }
    .bp3-callout.bp3-intent-warning[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-warning > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-warning .bp3-heading{
      color:#bf7326; }
    .bp3-dark .bp3-callout.bp3-intent-warning{
      background-color:rgba(217, 130, 43, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-warning[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-warning > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-warning .bp3-heading{
        color:#ffb366; }
  .bp3-callout.bp3-intent-danger{
    background-color:rgba(219, 55, 55, 0.15); }
    .bp3-callout.bp3-intent-danger[class*="bp3-icon-"]::before,
    .bp3-callout.bp3-intent-danger > .bp3-icon:first-child,
    .bp3-callout.bp3-intent-danger .bp3-heading{
      color:#c23030; }
    .bp3-dark .bp3-callout.bp3-intent-danger{
      background-color:rgba(219, 55, 55, 0.25); }
      .bp3-dark .bp3-callout.bp3-intent-danger[class*="bp3-icon-"]::before,
      .bp3-dark .bp3-callout.bp3-intent-danger > .bp3-icon:first-child,
      .bp3-dark .bp3-callout.bp3-intent-danger .bp3-heading{
        color:#ff7373; }
  .bp3-running-text .bp3-callout{
    margin:20px 0; }
.bp3-card{
  background-color:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
  padding:20px;
  -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-card.bp3-dark,
  .bp3-dark .bp3-card{
    background-color:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }

.bp3-elevation-0{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }
  .bp3-elevation-0.bp3-dark,
  .bp3-dark .bp3-elevation-0{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0); }

.bp3-elevation-1{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-1.bp3-dark,
  .bp3-dark .bp3-elevation-1{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-elevation-2{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 1px 1px rgba(16, 22, 26, 0.2), 0 2px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 1px 1px rgba(16, 22, 26, 0.2), 0 2px 6px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-2.bp3-dark,
  .bp3-dark .bp3-elevation-2{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.4), 0 2px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.4), 0 2px 6px rgba(16, 22, 26, 0.4); }

.bp3-elevation-3{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-3.bp3-dark,
  .bp3-dark .bp3-elevation-3{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }

.bp3-elevation-4{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2); }
  .bp3-elevation-4.bp3-dark,
  .bp3-dark .bp3-elevation-4{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4); }

.bp3-card.bp3-interactive:hover{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  cursor:pointer; }
  .bp3-card.bp3-interactive:hover.bp3-dark,
  .bp3-dark .bp3-card.bp3-interactive:hover{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }

.bp3-card.bp3-interactive:active{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  opacity:0.9;
  -webkit-transition-duration:0;
          transition-duration:0; }
  .bp3-card.bp3-interactive:active.bp3-dark,
  .bp3-dark .bp3-card.bp3-interactive:active{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-collapse{
  height:0;
  overflow-y:hidden;
  -webkit-transition:height 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:height 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-collapse .bp3-collapse-body{
    -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-collapse .bp3-collapse-body[aria-hidden="true"]{
      display:none; }

.bp3-context-menu .bp3-popover-target{
  display:block; }

.bp3-context-menu-popover-target{
  position:fixed; }

.bp3-divider{
  border-bottom:1px solid rgba(16, 22, 26, 0.15);
  border-right:1px solid rgba(16, 22, 26, 0.15);
  margin:5px; }
  .bp3-dark .bp3-divider{
    border-color:rgba(16, 22, 26, 0.4); }
.bp3-dialog-container{
  opacity:1;
  -webkit-transform:scale(1);
          transform:scale(1);
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  min-height:100%;
  pointer-events:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none;
  width:100%; }
  .bp3-dialog-container.bp3-overlay-enter > .bp3-dialog, .bp3-dialog-container.bp3-overlay-appear > .bp3-dialog{
    opacity:0;
    -webkit-transform:scale(0.5);
            transform:scale(0.5); }
  .bp3-dialog-container.bp3-overlay-enter-active > .bp3-dialog, .bp3-dialog-container.bp3-overlay-appear-active > .bp3-dialog{
    opacity:1;
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:opacity, -webkit-transform;
    transition-property:opacity, -webkit-transform;
    transition-property:opacity, transform;
    transition-property:opacity, transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-dialog-container.bp3-overlay-exit > .bp3-dialog{
    opacity:1;
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-dialog-container.bp3-overlay-exit-active > .bp3-dialog{
    opacity:0;
    -webkit-transform:scale(0.5);
            transform:scale(0.5);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:opacity, -webkit-transform;
    transition-property:opacity, -webkit-transform;
    transition-property:opacity, transform;
    transition-property:opacity, transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }

.bp3-dialog{
  background:#ebf1f5;
  border-radius:6px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:30px 0;
  padding-bottom:20px;
  pointer-events:all;
  -webkit-user-select:text;
     -moz-user-select:text;
      -ms-user-select:text;
          user-select:text;
  width:500px; }
  .bp3-dialog:focus{
    outline:0; }
  .bp3-dialog.bp3-dark,
  .bp3-dark .bp3-dialog{
    background:#293742;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }

.bp3-dialog-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background:#ffffff;
  border-radius:6px 6px 0 0;
  -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  min-height:40px;
  padding-left:20px;
  padding-right:5px;
  z-index:30; }
  .bp3-dialog-header .bp3-icon-large,
  .bp3-dialog-header .bp3-icon{
    color:#5c7080;
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    margin-right:10px; }
  .bp3-dialog-header .bp3-heading{
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    line-height:inherit;
    margin:0; }
    .bp3-dialog-header .bp3-heading:last-child{
      margin-right:20px; }
  .bp3-dark .bp3-dialog-header{
    background:#30404d;
    -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:0 1px 0 rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-dialog-header .bp3-icon-large,
    .bp3-dark .bp3-dialog-header .bp3-icon{
      color:#a7b6c2; }

.bp3-dialog-body{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  line-height:18px;
  margin:20px; }

.bp3-dialog-footer{
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  margin:0 20px; }

.bp3-dialog-footer-actions{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:end;
      -ms-flex-pack:end;
          justify-content:flex-end; }
  .bp3-dialog-footer-actions .bp3-button{
    margin-left:10px; }
.bp3-multistep-dialog-panels{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }

.bp3-multistep-dialog-left-panel{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:1;
      -ms-flex:1;
          flex:1;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column; }
  .bp3-dark .bp3-multistep-dialog-left-panel{
    background:#202b33; }

.bp3-multistep-dialog-right-panel{
  background-color:#f5f8fa;
  border-left:1px solid rgba(16, 22, 26, 0.15);
  border-radius:0 0 6px 0;
  -webkit-box-flex:3;
      -ms-flex:3;
          flex:3;
  min-width:0; }
  .bp3-dark .bp3-multistep-dialog-right-panel{
    background-color:#293742;
    border-left:1px solid rgba(16, 22, 26, 0.4); }

.bp3-multistep-dialog-footer{
  background-color:#ffffff;
  border-radius:0 0 6px 0;
  border-top:1px solid rgba(16, 22, 26, 0.15);
  padding:10px; }
  .bp3-dark .bp3-multistep-dialog-footer{
    background:#30404d;
    border-top:1px solid rgba(16, 22, 26, 0.4); }

.bp3-dialog-step-container{
  background-color:#f5f8fa;
  border-bottom:1px solid rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-dialog-step-container{
    background:#293742;
    border-bottom:1px solid rgba(16, 22, 26, 0.4); }
  .bp3-dialog-step-container.bp3-dialog-step-viewed{
    background-color:#ffffff; }
    .bp3-dark .bp3-dialog-step-container.bp3-dialog-step-viewed{
      background:#30404d; }

.bp3-dialog-step{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background-color:#f5f8fa;
  border-radius:6px;
  cursor:not-allowed;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  margin:4px;
  padding:6px 14px; }
  .bp3-dark .bp3-dialog-step{
    background:#293742; }
  .bp3-dialog-step-viewed .bp3-dialog-step{
    background-color:#ffffff;
    cursor:pointer; }
    .bp3-dark .bp3-dialog-step-viewed .bp3-dialog-step{
      background:#30404d; }
  .bp3-dialog-step:hover{
    background-color:#f5f8fa; }
    .bp3-dark .bp3-dialog-step:hover{
      background:#293742; }

.bp3-dialog-step-icon{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background-color:rgba(92, 112, 128, 0.6);
  border-radius:50%;
  color:#ffffff;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  height:25px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  width:25px; }
  .bp3-dark .bp3-dialog-step-icon{
    background-color:rgba(167, 182, 194, 0.6); }
  .bp3-active.bp3-dialog-step-viewed .bp3-dialog-step-icon{
    background-color:#2b95d6; }
  .bp3-dialog-step-viewed .bp3-dialog-step-icon{
    background-color:#8a9ba8; }

.bp3-dialog-step-title{
  color:rgba(92, 112, 128, 0.6);
  -webkit-box-flex:1;
      -ms-flex:1;
          flex:1;
  padding-left:10px; }
  .bp3-dark .bp3-dialog-step-title{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-active.bp3-dialog-step-viewed .bp3-dialog-step-title{
    color:#2b95d6; }
  .bp3-dialog-step-viewed:not(.bp3-active) .bp3-dialog-step-title{
    color:#182026; }
    .bp3-dark .bp3-dialog-step-viewed:not(.bp3-active) .bp3-dialog-step-title{
      color:#f5f8fa; }
.bp3-drawer{
  background:#ffffff;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:0;
  padding:0; }
  .bp3-drawer:focus{
    outline:0; }
  .bp3-drawer.bp3-position-top{
    height:50%;
    left:0;
    right:0;
    top:0; }
    .bp3-drawer.bp3-position-top.bp3-overlay-enter, .bp3-drawer.bp3-position-top.bp3-overlay-appear{
      -webkit-transform:translateY(-100%);
              transform:translateY(-100%); }
    .bp3-drawer.bp3-position-top.bp3-overlay-enter-active, .bp3-drawer.bp3-position-top.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-top.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer.bp3-position-top.bp3-overlay-exit-active{
      -webkit-transform:translateY(-100%);
              transform:translateY(-100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-position-bottom{
    bottom:0;
    height:50%;
    left:0;
    right:0; }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-enter, .bp3-drawer.bp3-position-bottom.bp3-overlay-appear{
      -webkit-transform:translateY(100%);
              transform:translateY(100%); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-enter-active, .bp3-drawer.bp3-position-bottom.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-exit-active{
      -webkit-transform:translateY(100%);
              transform:translateY(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-position-left{
    bottom:0;
    left:0;
    top:0;
    width:50%; }
    .bp3-drawer.bp3-position-left.bp3-overlay-enter, .bp3-drawer.bp3-position-left.bp3-overlay-appear{
      -webkit-transform:translateX(-100%);
              transform:translateX(-100%); }
    .bp3-drawer.bp3-position-left.bp3-overlay-enter-active, .bp3-drawer.bp3-position-left.bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-left.bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer.bp3-position-left.bp3-overlay-exit-active{
      -webkit-transform:translateX(-100%);
              transform:translateX(-100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-position-right{
    bottom:0;
    right:0;
    top:0;
    width:50%; }
    .bp3-drawer.bp3-position-right.bp3-overlay-enter, .bp3-drawer.bp3-position-right.bp3-overlay-appear{
      -webkit-transform:translateX(100%);
              transform:translateX(100%); }
    .bp3-drawer.bp3-position-right.bp3-overlay-enter-active, .bp3-drawer.bp3-position-right.bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer.bp3-position-right.bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer.bp3-position-right.bp3-overlay-exit-active{
      -webkit-transform:translateX(100%);
              transform:translateX(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
  .bp3-position-right):not(.bp3-vertical){
    bottom:0;
    right:0;
    top:0;
    width:50%; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-enter, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-appear{
      -webkit-transform:translateX(100%);
              transform:translateX(100%); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-enter-active, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-exit-active{
      -webkit-transform:translateX(100%);
              transform:translateX(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
  .bp3-position-right).bp3-vertical{
    bottom:0;
    height:50%;
    left:0;
    right:0; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-enter, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-appear{
      -webkit-transform:translateY(100%);
              transform:translateY(100%); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-enter-active, .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-exit-active{
      -webkit-transform:translateY(100%);
              transform:translateY(100%);
      -webkit-transition-delay:0;
              transition-delay:0;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-drawer.bp3-dark,
  .bp3-dark .bp3-drawer{
    background:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }

.bp3-drawer-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  border-radius:0;
  -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  min-height:40px;
  padding:5px;
  padding-left:20px;
  position:relative; }
  .bp3-drawer-header .bp3-icon-large,
  .bp3-drawer-header .bp3-icon{
    color:#5c7080;
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    margin-right:10px; }
  .bp3-drawer-header .bp3-heading{
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    line-height:inherit;
    margin:0; }
    .bp3-drawer-header .bp3-heading:last-child{
      margin-right:20px; }
  .bp3-dark .bp3-drawer-header{
    -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:0 1px 0 rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-drawer-header .bp3-icon-large,
    .bp3-dark .bp3-drawer-header .bp3-icon{
      color:#a7b6c2; }

.bp3-drawer-body{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  line-height:18px;
  overflow:auto; }

.bp3-drawer-footer{
  -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  padding:10px 20px;
  position:relative; }
  .bp3-dark .bp3-drawer-footer{
    -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.4); }
.bp3-editable-text{
  cursor:text;
  display:inline-block;
  max-width:100%;
  position:relative;
  vertical-align:top;
  white-space:nowrap; }
  .bp3-editable-text::before{
    bottom:-3px;
    left:-3px;
    position:absolute;
    right:-3px;
    top:-3px;
    border-radius:3px;
    content:"";
    -webkit-transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-editable-text:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-editable-text.bp3-editable-text-editing::before{
    background-color:#ffffff;
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-disabled::before{
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-editable-text.bp3-intent-primary .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-primary .bp3-editable-text-content{
    color:#137cbd; }
  .bp3-editable-text.bp3-intent-primary:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(19, 124, 189, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(19, 124, 189, 0.4); }
  .bp3-editable-text.bp3-intent-primary.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-success .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-success .bp3-editable-text-content{
    color:#0f9960; }
  .bp3-editable-text.bp3-intent-success:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px rgba(15, 153, 96, 0.4);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px rgba(15, 153, 96, 0.4); }
  .bp3-editable-text.bp3-intent-success.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-warning .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-warning .bp3-editable-text-content{
    color:#d9822b; }
  .bp3-editable-text.bp3-intent-warning:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px rgba(217, 130, 43, 0.4);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px rgba(217, 130, 43, 0.4); }
  .bp3-editable-text.bp3-intent-warning.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-editable-text.bp3-intent-danger .bp3-editable-text-input,
  .bp3-editable-text.bp3-intent-danger .bp3-editable-text-content{
    color:#db3737; }
  .bp3-editable-text.bp3-intent-danger:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px rgba(219, 55, 55, 0.4);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px rgba(219, 55, 55, 0.4); }
  .bp3-editable-text.bp3-intent-danger.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-editable-text:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(255, 255, 255, 0.15); }
  .bp3-dark .bp3-editable-text.bp3-editable-text-editing::before{
    background-color:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-disabled::before{
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-dark .bp3-editable-text.bp3-intent-primary .bp3-editable-text-content{
    color:#48aff0; }
  .bp3-dark .bp3-editable-text.bp3-intent-primary:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(72, 175, 240, 0), 0 0 0 0 rgba(72, 175, 240, 0), inset 0 0 0 1px rgba(72, 175, 240, 0.4);
            box-shadow:0 0 0 0 rgba(72, 175, 240, 0), 0 0 0 0 rgba(72, 175, 240, 0), inset 0 0 0 1px rgba(72, 175, 240, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-primary.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #48aff0, 0 0 0 3px rgba(72, 175, 240, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #48aff0, 0 0 0 3px rgba(72, 175, 240, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-success .bp3-editable-text-content{
    color:#3dcc91; }
  .bp3-dark .bp3-editable-text.bp3-intent-success:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(61, 204, 145, 0), 0 0 0 0 rgba(61, 204, 145, 0), inset 0 0 0 1px rgba(61, 204, 145, 0.4);
            box-shadow:0 0 0 0 rgba(61, 204, 145, 0), 0 0 0 0 rgba(61, 204, 145, 0), inset 0 0 0 1px rgba(61, 204, 145, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-success.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #3dcc91, 0 0 0 3px rgba(61, 204, 145, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #3dcc91, 0 0 0 3px rgba(61, 204, 145, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-warning .bp3-editable-text-content{
    color:#ffb366; }
  .bp3-dark .bp3-editable-text.bp3-intent-warning:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(255, 179, 102, 0), 0 0 0 0 rgba(255, 179, 102, 0), inset 0 0 0 1px rgba(255, 179, 102, 0.4);
            box-shadow:0 0 0 0 rgba(255, 179, 102, 0), 0 0 0 0 rgba(255, 179, 102, 0), inset 0 0 0 1px rgba(255, 179, 102, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-warning.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #ffb366, 0 0 0 3px rgba(255, 179, 102, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #ffb366, 0 0 0 3px rgba(255, 179, 102, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-danger .bp3-editable-text-content{
    color:#ff7373; }
  .bp3-dark .bp3-editable-text.bp3-intent-danger:hover::before{
    -webkit-box-shadow:0 0 0 0 rgba(255, 115, 115, 0), 0 0 0 0 rgba(255, 115, 115, 0), inset 0 0 0 1px rgba(255, 115, 115, 0.4);
            box-shadow:0 0 0 0 rgba(255, 115, 115, 0), 0 0 0 0 rgba(255, 115, 115, 0), inset 0 0 0 1px rgba(255, 115, 115, 0.4); }
  .bp3-dark .bp3-editable-text.bp3-intent-danger.bp3-editable-text-editing::before{
    -webkit-box-shadow:0 0 0 1px #ff7373, 0 0 0 3px rgba(255, 115, 115, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #ff7373, 0 0 0 3px rgba(255, 115, 115, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-editable-text-input,
.bp3-editable-text-content{
  color:inherit;
  display:inherit;
  font:inherit;
  letter-spacing:inherit;
  max-width:inherit;
  min-width:inherit;
  position:relative;
  resize:none;
  text-transform:inherit;
  vertical-align:top; }

.bp3-editable-text-input{
  background:none;
  border:none;
  -webkit-box-shadow:none;
          box-shadow:none;
  padding:0;
  white-space:pre-wrap;
  width:100%; }
  .bp3-editable-text-input::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-editable-text-input:focus{
    outline:none; }
  .bp3-editable-text-input::-ms-clear{
    display:none; }

.bp3-editable-text-content{
  overflow:hidden;
  padding-right:2px;
  text-overflow:ellipsis;
  white-space:pre; }
  .bp3-editable-text-editing > .bp3-editable-text-content{
    left:0;
    position:absolute;
    visibility:hidden; }
  .bp3-editable-text-placeholder > .bp3-editable-text-content{
    color:rgba(92, 112, 128, 0.6); }
    .bp3-dark .bp3-editable-text-placeholder > .bp3-editable-text-content{
      color:rgba(167, 182, 194, 0.6); }

.bp3-editable-text.bp3-multiline{
  display:block; }
  .bp3-editable-text.bp3-multiline .bp3-editable-text-content{
    overflow:auto;
    white-space:pre-wrap;
    word-wrap:break-word; }
.bp3-divider{
  border-bottom:1px solid rgba(16, 22, 26, 0.15);
  border-right:1px solid rgba(16, 22, 26, 0.15);
  margin:5px; }
  .bp3-dark .bp3-divider{
    border-color:rgba(16, 22, 26, 0.4); }
.bp3-control-group{
  -webkit-transform:translateZ(0);
          transform:translateZ(0);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:stretch;
      -ms-flex-align:stretch;
          align-items:stretch; }
  .bp3-control-group > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-control-group > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-control-group .bp3-button,
  .bp3-control-group .bp3-html-select,
  .bp3-control-group .bp3-input,
  .bp3-control-group .bp3-select{
    position:relative; }
  .bp3-control-group .bp3-input{
    border-radius:inherit;
    z-index:2; }
    .bp3-control-group .bp3-input:focus{
      border-radius:3px;
      z-index:14; }
    .bp3-control-group .bp3-input[class*="bp3-intent"]{
      z-index:13; }
      .bp3-control-group .bp3-input[class*="bp3-intent"]:focus{
        z-index:15; }
    .bp3-control-group .bp3-input[readonly], .bp3-control-group .bp3-input:disabled, .bp3-control-group .bp3-input.bp3-disabled{
      z-index:1; }
  .bp3-control-group .bp3-input-group[class*="bp3-intent"] .bp3-input{
    z-index:13; }
    .bp3-control-group .bp3-input-group[class*="bp3-intent"] .bp3-input:focus{
      z-index:15; }
  .bp3-control-group .bp3-button,
  .bp3-control-group .bp3-html-select select,
  .bp3-control-group .bp3-select select{
    -webkit-transform:translateZ(0);
            transform:translateZ(0);
    border-radius:inherit;
    z-index:4; }
    .bp3-control-group .bp3-button:focus,
    .bp3-control-group .bp3-html-select select:focus,
    .bp3-control-group .bp3-select select:focus{
      z-index:5; }
    .bp3-control-group .bp3-button:hover,
    .bp3-control-group .bp3-html-select select:hover,
    .bp3-control-group .bp3-select select:hover{
      z-index:6; }
    .bp3-control-group .bp3-button:active,
    .bp3-control-group .bp3-html-select select:active,
    .bp3-control-group .bp3-select select:active{
      z-index:7; }
    .bp3-control-group .bp3-button[readonly], .bp3-control-group .bp3-button:disabled, .bp3-control-group .bp3-button.bp3-disabled,
    .bp3-control-group .bp3-html-select select[readonly],
    .bp3-control-group .bp3-html-select select:disabled,
    .bp3-control-group .bp3-html-select select.bp3-disabled,
    .bp3-control-group .bp3-select select[readonly],
    .bp3-control-group .bp3-select select:disabled,
    .bp3-control-group .bp3-select select.bp3-disabled{
      z-index:3; }
    .bp3-control-group .bp3-button[class*="bp3-intent"],
    .bp3-control-group .bp3-html-select select[class*="bp3-intent"],
    .bp3-control-group .bp3-select select[class*="bp3-intent"]{
      z-index:9; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:focus,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:focus,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:focus{
        z-index:10; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:hover,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:hover,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:hover{
        z-index:11; }
      .bp3-control-group .bp3-button[class*="bp3-intent"]:active,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:active,
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:active{
        z-index:12; }
      .bp3-control-group .bp3-button[class*="bp3-intent"][readonly], .bp3-control-group .bp3-button[class*="bp3-intent"]:disabled, .bp3-control-group .bp3-button[class*="bp3-intent"].bp3-disabled,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"][readonly],
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"]:disabled,
      .bp3-control-group .bp3-html-select select[class*="bp3-intent"].bp3-disabled,
      .bp3-control-group .bp3-select select[class*="bp3-intent"][readonly],
      .bp3-control-group .bp3-select select[class*="bp3-intent"]:disabled,
      .bp3-control-group .bp3-select select[class*="bp3-intent"].bp3-disabled{
        z-index:8; }
  .bp3-control-group .bp3-input-group > .bp3-icon,
  .bp3-control-group .bp3-input-group > .bp3-button,
  .bp3-control-group .bp3-input-group > .bp3-input-left-container,
  .bp3-control-group .bp3-input-group > .bp3-input-action{
    z-index:16; }
  .bp3-control-group .bp3-select::after,
  .bp3-control-group .bp3-html-select::after,
  .bp3-control-group .bp3-select > .bp3-icon,
  .bp3-control-group .bp3-html-select > .bp3-icon{
    z-index:17; }
  .bp3-control-group .bp3-select:focus-within{
    z-index:5; }
  .bp3-control-group:not(.bp3-vertical) > *:not(.bp3-divider){
    margin-right:-1px; }
  .bp3-control-group:not(.bp3-vertical) > .bp3-divider:not(:first-child){
    margin-left:6px; }
  .bp3-dark .bp3-control-group:not(.bp3-vertical) > *:not(.bp3-divider){
    margin-right:0; }
  .bp3-dark .bp3-control-group:not(.bp3-vertical) > .bp3-button + .bp3-button{
    margin-left:1px; }
  .bp3-control-group .bp3-popover-wrapper,
  .bp3-control-group .bp3-popover-target{
    border-radius:inherit; }
  .bp3-control-group > :first-child{
    border-radius:3px 0 0 3px; }
  .bp3-control-group > :last-child{
    border-radius:0 3px 3px 0;
    margin-right:0; }
  .bp3-control-group > :only-child{
    border-radius:3px;
    margin-right:0; }
  .bp3-control-group .bp3-input-group .bp3-button{
    border-radius:3px; }
  .bp3-control-group .bp3-numeric-input:not(:first-child) .bp3-input-group{
    border-bottom-left-radius:0;
    border-top-left-radius:0; }
  .bp3-control-group.bp3-fill{
    width:100%; }
  .bp3-control-group > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-control-group.bp3-fill > *:not(.bp3-fixed){
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto; }
  .bp3-control-group.bp3-vertical{
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column; }
    .bp3-control-group.bp3-vertical > *{
      margin-top:-1px; }
    .bp3-control-group.bp3-vertical > :first-child{
      border-radius:3px 3px 0 0;
      margin-top:0; }
    .bp3-control-group.bp3-vertical > :last-child{
      border-radius:0 0 3px 3px; }
.bp3-control{
  cursor:pointer;
  display:block;
  margin-bottom:10px;
  position:relative;
  text-transform:none; }
  .bp3-control input:checked ~ .bp3-control-indicator{
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
  .bp3-control:hover input:checked ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
  .bp3-control input:not(:disabled):active:checked ~ .bp3-control-indicator{
    background:#0e5a8a;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-control input:disabled:checked ~ .bp3-control-indicator{
    background:rgba(19, 124, 189, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-dark .bp3-control input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control:hover input:checked ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control input:not(:disabled):active:checked ~ .bp3-control-indicator{
    background-color:#0e5a8a;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-control input:disabled:checked ~ .bp3-control-indicator{
    background:rgba(14, 90, 138, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-control:not(.bp3-align-right){
    padding-left:26px; }
    .bp3-control:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-26px; }
  .bp3-control.bp3-align-right{
    padding-right:26px; }
    .bp3-control.bp3-align-right .bp3-control-indicator{
      margin-right:-26px; }
  .bp3-control.bp3-disabled{
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
  .bp3-control.bp3-inline{
    display:inline-block;
    margin-right:20px; }
  .bp3-control input{
    left:0;
    opacity:0;
    position:absolute;
    top:0;
    z-index:-1; }
  .bp3-control .bp3-control-indicator{
    background-clip:padding-box;
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    border:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    cursor:pointer;
    display:inline-block;
    font-size:16px;
    height:1em;
    margin-right:10px;
    margin-top:-3px;
    position:relative;
    -webkit-user-select:none;
       -moz-user-select:none;
        -ms-user-select:none;
            user-select:none;
    vertical-align:middle;
    width:1em; }
    .bp3-control .bp3-control-indicator::before{
      content:"";
      display:block;
      height:1em;
      width:1em; }
  .bp3-control:hover .bp3-control-indicator{
    background-color:#ebf1f5; }
  .bp3-control input:not(:disabled):active ~ .bp3-control-indicator{
    background:#d8e1e8;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-control input:disabled ~ .bp3-control-indicator{
    background:rgba(206, 217, 224, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none;
    cursor:not-allowed; }
  .bp3-control input:focus ~ .bp3-control-indicator{
    outline:rgba(19, 124, 189, 0.6) auto 2px;
    outline-offset:2px;
    -moz-outline-radius:6px; }
  .bp3-control.bp3-align-right .bp3-control-indicator{
    float:right;
    margin-left:10px;
    margin-top:1px; }
  .bp3-control.bp3-large{
    font-size:16px; }
    .bp3-control.bp3-large:not(.bp3-align-right){
      padding-left:30px; }
      .bp3-control.bp3-large:not(.bp3-align-right) .bp3-control-indicator{
        margin-left:-30px; }
    .bp3-control.bp3-large.bp3-align-right{
      padding-right:30px; }
      .bp3-control.bp3-large.bp3-align-right .bp3-control-indicator{
        margin-right:-30px; }
    .bp3-control.bp3-large .bp3-control-indicator{
      font-size:20px; }
    .bp3-control.bp3-large.bp3-align-right .bp3-control-indicator{
      margin-top:0; }
  .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator{
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    color:#ffffff; }
  .bp3-control.bp3-checkbox:hover input:indeterminate ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2); }
  .bp3-control.bp3-checkbox input:not(:disabled):active:indeterminate ~ .bp3-control-indicator{
    background:#0e5a8a;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
    background:rgba(19, 124, 189, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-dark .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-checkbox:hover input:indeterminate ~ .bp3-control-indicator{
    background-color:#106ba3;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-checkbox input:not(:disabled):active:indeterminate ~ .bp3-control-indicator{
    background-color:#0e5a8a;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
    background:rgba(14, 90, 138, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-control.bp3-checkbox .bp3-control-indicator{
    border-radius:3px; }
  .bp3-control.bp3-checkbox input:checked ~ .bp3-control-indicator::before{
    background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M12 5c-.28 0-.53.11-.71.29L7 9.59l-2.29-2.3a1.003 1.003 0 00-1.42 1.42l3 3c.18.18.43.29.71.29s.53-.11.71-.29l5-5A1.003 1.003 0 0012 5z' fill='white'/%3e%3c/svg%3e"); }
  .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator::before{
    background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M11 7H5c-.55 0-1 .45-1 1s.45 1 1 1h6c.55 0 1-.45 1-1s-.45-1-1-1z' fill='white'/%3e%3c/svg%3e"); }
  .bp3-control.bp3-radio .bp3-control-indicator{
    border-radius:50%; }
  .bp3-control.bp3-radio input:checked ~ .bp3-control-indicator::before{
    background-image:radial-gradient(#ffffff, #ffffff 28%, transparent 32%); }
  .bp3-control.bp3-radio input:checked:disabled ~ .bp3-control-indicator::before{
    opacity:0.5; }
  .bp3-control.bp3-radio input:focus ~ .bp3-control-indicator{
    -moz-outline-radius:16px; }
  .bp3-control.bp3-switch input ~ .bp3-control-indicator{
    background:rgba(167, 182, 194, 0.5); }
  .bp3-control.bp3-switch:hover input ~ .bp3-control-indicator{
    background:rgba(115, 134, 148, 0.5); }
  .bp3-control.bp3-switch input:not(:disabled):active ~ .bp3-control-indicator{
    background:rgba(92, 112, 128, 0.5); }
  .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator{
    background:rgba(206, 217, 224, 0.5); }
    .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator::before{
      background:rgba(255, 255, 255, 0.8); }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator{
    background:#137cbd; }
  .bp3-control.bp3-switch:hover input:checked ~ .bp3-control-indicator{
    background:#106ba3; }
  .bp3-control.bp3-switch input:checked:not(:disabled):active ~ .bp3-control-indicator{
    background:#0e5a8a; }
  .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator{
    background:rgba(19, 124, 189, 0.5); }
    .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator::before{
      background:rgba(255, 255, 255, 0.8); }
  .bp3-control.bp3-switch:not(.bp3-align-right){
    padding-left:38px; }
    .bp3-control.bp3-switch:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-38px; }
  .bp3-control.bp3-switch.bp3-align-right{
    padding-right:38px; }
    .bp3-control.bp3-switch.bp3-align-right .bp3-control-indicator{
      margin-right:-38px; }
  .bp3-control.bp3-switch .bp3-control-indicator{
    border:none;
    border-radius:1.75em;
    -webkit-box-shadow:none !important;
            box-shadow:none !important;
    min-width:1.75em;
    -webkit-transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    width:auto; }
    .bp3-control.bp3-switch .bp3-control-indicator::before{
      background:#ffffff;
      border-radius:50%;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
      height:calc(1em - 4px);
      left:0;
      margin:2px;
      position:absolute;
      -webkit-transition:left 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
      transition:left 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
      width:calc(1em - 4px); }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator::before{
    left:calc(100% - 1em); }
  .bp3-control.bp3-switch.bp3-large:not(.bp3-align-right){
    padding-left:45px; }
    .bp3-control.bp3-switch.bp3-large:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-45px; }
  .bp3-control.bp3-switch.bp3-large.bp3-align-right{
    padding-right:45px; }
    .bp3-control.bp3-switch.bp3-large.bp3-align-right .bp3-control-indicator{
      margin-right:-45px; }
  .bp3-dark .bp3-control.bp3-switch input ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.5); }
  .bp3-dark .bp3-control.bp3-switch:hover input ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.7); }
  .bp3-dark .bp3-control.bp3-switch input:not(:disabled):active ~ .bp3-control-indicator{
    background:rgba(16, 22, 26, 0.9); }
  .bp3-dark .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator{
    background:rgba(57, 75, 89, 0.5); }
    .bp3-dark .bp3-control.bp3-switch input:disabled ~ .bp3-control-indicator::before{
      background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator{
    background:#137cbd; }
  .bp3-dark .bp3-control.bp3-switch:hover input:checked ~ .bp3-control-indicator{
    background:#106ba3; }
  .bp3-dark .bp3-control.bp3-switch input:checked:not(:disabled):active ~ .bp3-control-indicator{
    background:#0e5a8a; }
  .bp3-dark .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator{
    background:rgba(14, 90, 138, 0.5); }
    .bp3-dark .bp3-control.bp3-switch input:checked:disabled ~ .bp3-control-indicator::before{
      background:rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch .bp3-control-indicator::before{
    background:#394b59;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator::before{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-control.bp3-switch .bp3-switch-inner-text{
    font-size:0.7em;
    text-align:center; }
  .bp3-control.bp3-switch .bp3-control-indicator-child:first-child{
    line-height:0;
    margin-left:0.5em;
    margin-right:1.2em;
    visibility:hidden; }
  .bp3-control.bp3-switch .bp3-control-indicator-child:last-child{
    line-height:1em;
    margin-left:1.2em;
    margin-right:0.5em;
    visibility:visible; }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator .bp3-control-indicator-child:first-child{
    line-height:1em;
    visibility:visible; }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator .bp3-control-indicator-child:last-child{
    line-height:0;
    visibility:hidden; }
  .bp3-dark .bp3-control{
    color:#f5f8fa; }
    .bp3-dark .bp3-control.bp3-disabled{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-control .bp3-control-indicator{
      background-color:#394b59;
      background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
      background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-control:hover .bp3-control-indicator{
      background-color:#30404d; }
    .bp3-dark .bp3-control input:not(:disabled):active ~ .bp3-control-indicator{
      background:#202b33;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-control input:disabled ~ .bp3-control-indicator{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      cursor:not-allowed; }
    .bp3-dark .bp3-control.bp3-checkbox input:disabled:checked ~ .bp3-control-indicator, .bp3-dark .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
      color:rgba(167, 182, 194, 0.6); }
.bp3-file-input{
  cursor:pointer;
  display:inline-block;
  height:30px;
  position:relative; }
  .bp3-file-input input{
    margin:0;
    min-width:200px;
    opacity:0; }
    .bp3-file-input input:disabled + .bp3-file-upload-input,
    .bp3-file-input input.bp3-disabled + .bp3-file-upload-input{
      background:rgba(206, 217, 224, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed;
      resize:none; }
      .bp3-file-input input:disabled + .bp3-file-upload-input::after,
      .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after{
        background-color:rgba(206, 217, 224, 0.5);
        background-image:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:rgba(92, 112, 128, 0.6);
        cursor:not-allowed;
        outline:none; }
        .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active, .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active:hover,
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active,
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active:hover{
          background:rgba(206, 217, 224, 0.7); }
      .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input, .bp3-dark
      .bp3-file-input input.bp3-disabled + .bp3-file-upload-input{
        background:rgba(57, 75, 89, 0.5);
        -webkit-box-shadow:none;
                box-shadow:none;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input::after, .bp3-dark
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after{
          background-color:rgba(57, 75, 89, 0.5);
          background-image:none;
          -webkit-box-shadow:none;
                  box-shadow:none;
          color:rgba(167, 182, 194, 0.6); }
          .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active, .bp3-dark
          .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active{
            background:rgba(57, 75, 89, 0.7); }
  .bp3-file-input.bp3-file-input-has-selection .bp3-file-upload-input{
    color:#182026; }
  .bp3-dark .bp3-file-input.bp3-file-input-has-selection .bp3-file-upload-input{
    color:#f5f8fa; }
  .bp3-file-input.bp3-fill{
    width:100%; }
  .bp3-file-input.bp3-large,
  .bp3-large .bp3-file-input{
    height:40px; }
  .bp3-file-input .bp3-file-upload-input-custom-text::after{
    content:attr(bp3-button-text); }

.bp3-file-upload-input{
  -webkit-appearance:none;
     -moz-appearance:none;
          appearance:none;
  background:#ffffff;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
  color:#182026;
  font-size:14px;
  font-weight:400;
  height:30px;
  line-height:30px;
  outline:none;
  padding:0 10px;
  -webkit-transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  vertical-align:middle;
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  color:rgba(92, 112, 128, 0.6);
  left:0;
  padding-right:80px;
  position:absolute;
  right:0;
  top:0;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-file-upload-input::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-file-upload-input:focus, .bp3-file-upload-input.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-file-upload-input[type="search"], .bp3-file-upload-input.bp3-round{
    border-radius:30px;
    -webkit-box-sizing:border-box;
            box-sizing:border-box;
    padding-left:10px; }
  .bp3-file-upload-input[readonly]{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-file-upload-input:disabled, .bp3-file-upload-input.bp3-disabled{
    background:rgba(206, 217, 224, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    resize:none; }
  .bp3-file-upload-input::after{
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    color:#182026;
    min-height:24px;
    min-width:24px;
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    border-radius:3px;
    content:"Browse";
    line-height:24px;
    margin:3px;
    position:absolute;
    right:0;
    text-align:center;
    top:0;
    width:70px; }
    .bp3-file-upload-input::after:hover{
      background-clip:padding-box;
      background-color:#ebf1f5;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
    .bp3-file-upload-input::after:active, .bp3-file-upload-input::after.bp3-active{
      background-color:#d8e1e8;
      background-image:none;
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-file-upload-input::after:disabled, .bp3-file-upload-input::after.bp3-disabled{
      background-color:rgba(206, 217, 224, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(92, 112, 128, 0.6);
      cursor:not-allowed;
      outline:none; }
      .bp3-file-upload-input::after:disabled.bp3-active, .bp3-file-upload-input::after:disabled.bp3-active:hover, .bp3-file-upload-input::after.bp3-disabled.bp3-active, .bp3-file-upload-input::after.bp3-disabled.bp3-active:hover{
        background:rgba(206, 217, 224, 0.7); }
  .bp3-file-upload-input:hover::after{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
  .bp3-file-upload-input:active::after{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-large .bp3-file-upload-input{
    font-size:16px;
    height:40px;
    line-height:40px;
    padding-right:95px; }
    .bp3-large .bp3-file-upload-input[type="search"], .bp3-large .bp3-file-upload-input.bp3-round{
      padding:0 15px; }
    .bp3-large .bp3-file-upload-input::after{
      min-height:30px;
      min-width:30px;
      line-height:30px;
      margin:5px;
      width:85px; }
  .bp3-dark .bp3-file-upload-input{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa;
    color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input:disabled, .bp3-dark .bp3-file-upload-input.bp3-disabled{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::after{
      background-color:#394b59;
      background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
      background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      color:#f5f8fa; }
      .bp3-dark .bp3-file-upload-input::after:hover, .bp3-dark .bp3-file-upload-input::after:active, .bp3-dark .bp3-file-upload-input::after.bp3-active{
        color:#f5f8fa; }
      .bp3-dark .bp3-file-upload-input::after:hover{
        background-color:#30404d;
        -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-file-upload-input::after:active, .bp3-dark .bp3-file-upload-input::after.bp3-active{
        background-color:#202b33;
        background-image:none;
        -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
                box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
      .bp3-dark .bp3-file-upload-input::after:disabled, .bp3-dark .bp3-file-upload-input::after.bp3-disabled{
        background-color:rgba(57, 75, 89, 0.5);
        background-image:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-file-upload-input::after:disabled.bp3-active, .bp3-dark .bp3-file-upload-input::after.bp3-disabled.bp3-active{
          background:rgba(57, 75, 89, 0.7); }
      .bp3-dark .bp3-file-upload-input::after .bp3-button-spinner .bp3-spinner-head{
        background:rgba(16, 22, 26, 0.5);
        stroke:#8a9ba8; }
    .bp3-dark .bp3-file-upload-input:hover::after{
      background-color:#30404d;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-file-upload-input:active::after{
      background-color:#202b33;
      background-image:none;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
.bp3-file-upload-input::after{
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
.bp3-form-group{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:0 0 15px; }
  .bp3-form-group label.bp3-label{
    margin-bottom:5px; }
  .bp3-form-group .bp3-control{
    margin-top:7px; }
  .bp3-form-group .bp3-form-helper-text{
    color:#5c7080;
    font-size:12px;
    margin-top:5px; }
  .bp3-form-group.bp3-intent-primary .bp3-form-helper-text{
    color:#106ba3; }
  .bp3-form-group.bp3-intent-success .bp3-form-helper-text{
    color:#0d8050; }
  .bp3-form-group.bp3-intent-warning .bp3-form-helper-text{
    color:#bf7326; }
  .bp3-form-group.bp3-intent-danger .bp3-form-helper-text{
    color:#c23030; }
  .bp3-form-group.bp3-inline{
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start;
    -webkit-box-orient:horizontal;
    -webkit-box-direction:normal;
        -ms-flex-direction:row;
            flex-direction:row; }
    .bp3-form-group.bp3-inline.bp3-large label.bp3-label{
      line-height:40px;
      margin:0 10px 0 0; }
    .bp3-form-group.bp3-inline label.bp3-label{
      line-height:30px;
      margin:0 10px 0 0; }
  .bp3-form-group.bp3-disabled .bp3-label,
  .bp3-form-group.bp3-disabled .bp3-text-muted,
  .bp3-form-group.bp3-disabled .bp3-form-helper-text{
    color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-dark .bp3-form-group.bp3-intent-primary .bp3-form-helper-text{
    color:#48aff0; }
  .bp3-dark .bp3-form-group.bp3-intent-success .bp3-form-helper-text{
    color:#3dcc91; }
  .bp3-dark .bp3-form-group.bp3-intent-warning .bp3-form-helper-text{
    color:#ffb366; }
  .bp3-dark .bp3-form-group.bp3-intent-danger .bp3-form-helper-text{
    color:#ff7373; }
  .bp3-dark .bp3-form-group .bp3-form-helper-text{
    color:#a7b6c2; }
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-label,
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-text-muted,
  .bp3-dark .bp3-form-group.bp3-disabled .bp3-form-helper-text{
    color:rgba(167, 182, 194, 0.6) !important; }
.bp3-input-group{
  display:block;
  position:relative; }
  .bp3-input-group .bp3-input{
    position:relative;
    width:100%; }
    .bp3-input-group .bp3-input:not(:first-child){
      padding-left:30px; }
    .bp3-input-group .bp3-input:not(:last-child){
      padding-right:30px; }
  .bp3-input-group .bp3-input-action,
  .bp3-input-group > .bp3-input-left-container,
  .bp3-input-group > .bp3-button,
  .bp3-input-group > .bp3-icon{
    position:absolute;
    top:0; }
    .bp3-input-group .bp3-input-action:first-child,
    .bp3-input-group > .bp3-input-left-container:first-child,
    .bp3-input-group > .bp3-button:first-child,
    .bp3-input-group > .bp3-icon:first-child{
      left:0; }
    .bp3-input-group .bp3-input-action:last-child,
    .bp3-input-group > .bp3-input-left-container:last-child,
    .bp3-input-group > .bp3-button:last-child,
    .bp3-input-group > .bp3-icon:last-child{
      right:0; }
  .bp3-input-group .bp3-button{
    min-height:24px;
    min-width:24px;
    margin:3px;
    padding:0 7px; }
    .bp3-input-group .bp3-button:empty{
      padding:0; }
  .bp3-input-group > .bp3-input-left-container,
  .bp3-input-group > .bp3-icon{
    z-index:1; }
  .bp3-input-group > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group > .bp3-icon{
    color:#5c7080; }
    .bp3-input-group > .bp3-input-left-container > .bp3-icon:empty,
    .bp3-input-group > .bp3-icon:empty{
      font-family:"Icons16", sans-serif;
      font-size:16px;
      font-style:normal;
      font-weight:400;
      line-height:1;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased; }
  .bp3-input-group > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group > .bp3-icon,
  .bp3-input-group .bp3-input-action > .bp3-spinner{
    margin:7px; }
  .bp3-input-group .bp3-tag{
    margin:5px; }
  .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus),
  .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus){
    color:#5c7080; }
    .bp3-dark .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus), .bp3-dark
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus){
      color:#a7b6c2; }
    .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-standard, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-large,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-standard,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:not(:hover):not(:focus) .bp3-icon-large{
      color:#5c7080; }
  .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled,
  .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled{
    color:rgba(92, 112, 128, 0.6) !important; }
    .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon-standard, .bp3-input-group .bp3-input:not(:focus) + .bp3-button.bp3-minimal:disabled .bp3-icon-large,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon-standard,
    .bp3-input-group .bp3-input:not(:focus) + .bp3-input-action .bp3-button.bp3-minimal:disabled .bp3-icon-large{
      color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-input-group.bp3-disabled{
    cursor:not-allowed; }
    .bp3-input-group.bp3-disabled .bp3-icon{
      color:rgba(92, 112, 128, 0.6); }
  .bp3-input-group.bp3-large .bp3-button{
    min-height:30px;
    min-width:30px;
    margin:5px; }
  .bp3-input-group.bp3-large > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group.bp3-large > .bp3-icon,
  .bp3-input-group.bp3-large .bp3-input-action > .bp3-spinner{
    margin:12px; }
  .bp3-input-group.bp3-large .bp3-input{
    font-size:16px;
    height:40px;
    line-height:40px; }
    .bp3-input-group.bp3-large .bp3-input[type="search"], .bp3-input-group.bp3-large .bp3-input.bp3-round{
      padding:0 15px; }
    .bp3-input-group.bp3-large .bp3-input:not(:first-child){
      padding-left:40px; }
    .bp3-input-group.bp3-large .bp3-input:not(:last-child){
      padding-right:40px; }
  .bp3-input-group.bp3-small .bp3-button{
    min-height:20px;
    min-width:20px;
    margin:2px; }
  .bp3-input-group.bp3-small .bp3-tag{
    min-height:20px;
    min-width:20px;
    margin:2px; }
  .bp3-input-group.bp3-small > .bp3-input-left-container > .bp3-icon,
  .bp3-input-group.bp3-small > .bp3-icon,
  .bp3-input-group.bp3-small .bp3-input-action > .bp3-spinner{
    margin:4px; }
  .bp3-input-group.bp3-small .bp3-input{
    font-size:12px;
    height:24px;
    line-height:24px;
    padding-left:8px;
    padding-right:8px; }
    .bp3-input-group.bp3-small .bp3-input[type="search"], .bp3-input-group.bp3-small .bp3-input.bp3-round{
      padding:0 12px; }
    .bp3-input-group.bp3-small .bp3-input:not(:first-child){
      padding-left:24px; }
    .bp3-input-group.bp3-small .bp3-input:not(:last-child){
      padding-right:24px; }
  .bp3-input-group.bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    width:100%; }
  .bp3-input-group.bp3-round .bp3-button,
  .bp3-input-group.bp3-round .bp3-input,
  .bp3-input-group.bp3-round .bp3-tag{
    border-radius:30px; }
  .bp3-dark .bp3-input-group .bp3-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-input-group.bp3-disabled .bp3-icon{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-input-group.bp3-intent-primary .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-primary .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-primary .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #137cbd;
              box-shadow:inset 0 0 0 1px #137cbd; }
    .bp3-input-group.bp3-intent-primary .bp3-input:disabled, .bp3-input-group.bp3-intent-primary .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-primary > .bp3-icon{
    color:#106ba3; }
    .bp3-dark .bp3-input-group.bp3-intent-primary > .bp3-icon{
      color:#48aff0; }
  .bp3-input-group.bp3-intent-success .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-success .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-success .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #0f9960;
              box-shadow:inset 0 0 0 1px #0f9960; }
    .bp3-input-group.bp3-intent-success .bp3-input:disabled, .bp3-input-group.bp3-intent-success .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-success > .bp3-icon{
    color:#0d8050; }
    .bp3-dark .bp3-input-group.bp3-intent-success > .bp3-icon{
      color:#3dcc91; }
  .bp3-input-group.bp3-intent-warning .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-warning .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-warning .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #d9822b;
              box-shadow:inset 0 0 0 1px #d9822b; }
    .bp3-input-group.bp3-intent-warning .bp3-input:disabled, .bp3-input-group.bp3-intent-warning .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-warning > .bp3-icon{
    color:#bf7326; }
    .bp3-dark .bp3-input-group.bp3-intent-warning > .bp3-icon{
      color:#ffb366; }
  .bp3-input-group.bp3-intent-danger .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-danger .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input-group.bp3-intent-danger .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #db3737;
              box-shadow:inset 0 0 0 1px #db3737; }
    .bp3-input-group.bp3-intent-danger .bp3-input:disabled, .bp3-input-group.bp3-intent-danger .bp3-input.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-input-group.bp3-intent-danger > .bp3-icon{
    color:#c23030; }
    .bp3-dark .bp3-input-group.bp3-intent-danger > .bp3-icon{
      color:#ff7373; }
.bp3-input{
  -webkit-appearance:none;
     -moz-appearance:none;
          appearance:none;
  background:#ffffff;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
  color:#182026;
  font-size:14px;
  font-weight:400;
  height:30px;
  line-height:30px;
  outline:none;
  padding:0 10px;
  -webkit-transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  vertical-align:middle; }
  .bp3-input::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input:focus, .bp3-input.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-input[type="search"], .bp3-input.bp3-round{
    border-radius:30px;
    -webkit-box-sizing:border-box;
            box-sizing:border-box;
    padding-left:10px; }
  .bp3-input[readonly]{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15); }
  .bp3-input:disabled, .bp3-input.bp3-disabled{
    background:rgba(206, 217, 224, 0.5);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    resize:none; }
  .bp3-input.bp3-large{
    font-size:16px;
    height:40px;
    line-height:40px; }
    .bp3-input.bp3-large[type="search"], .bp3-input.bp3-large.bp3-round{
      padding:0 15px; }
  .bp3-input.bp3-small{
    font-size:12px;
    height:24px;
    line-height:24px;
    padding-left:8px;
    padding-right:8px; }
    .bp3-input.bp3-small[type="search"], .bp3-input.bp3-small.bp3-round{
      padding:0 12px; }
  .bp3-input.bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    width:100%; }
  .bp3-dark .bp3-input{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark .bp3-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-input:disabled, .bp3-dark .bp3-input.bp3-disabled{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
  .bp3-input.bp3-intent-primary{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-primary:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-primary[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #137cbd;
              box-shadow:inset 0 0 0 1px #137cbd; }
    .bp3-input.bp3-intent-primary:disabled, .bp3-input.bp3-intent-primary.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px #137cbd, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-primary:focus{
        -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-primary[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #137cbd;
                box-shadow:inset 0 0 0 1px #137cbd; }
      .bp3-dark .bp3-input.bp3-intent-primary:disabled, .bp3-dark .bp3-input.bp3-intent-primary.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-success{
    -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-success:focus{
      -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-success[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #0f9960;
              box-shadow:inset 0 0 0 1px #0f9960; }
    .bp3-input.bp3-intent-success:disabled, .bp3-input.bp3-intent-success.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-success{
      -webkit-box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), 0 0 0 0 rgba(15, 153, 96, 0), inset 0 0 0 1px #0f9960, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-success:focus{
        -webkit-box-shadow:0 0 0 1px #0f9960, 0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #0f9960, 0 0 0 1px #0f9960, 0 0 0 3px rgba(15, 153, 96, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-success[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #0f9960;
                box-shadow:inset 0 0 0 1px #0f9960; }
      .bp3-dark .bp3-input.bp3-intent-success:disabled, .bp3-dark .bp3-input.bp3-intent-success.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-warning{
    -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-warning:focus{
      -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-warning[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #d9822b;
              box-shadow:inset 0 0 0 1px #d9822b; }
    .bp3-input.bp3-intent-warning:disabled, .bp3-input.bp3-intent-warning.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), 0 0 0 0 rgba(217, 130, 43, 0), inset 0 0 0 1px #d9822b, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-warning:focus{
        -webkit-box-shadow:0 0 0 1px #d9822b, 0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #d9822b, 0 0 0 1px #d9822b, 0 0 0 3px rgba(217, 130, 43, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-warning[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #d9822b;
                box-shadow:inset 0 0 0 1px #d9822b; }
      .bp3-dark .bp3-input.bp3-intent-warning:disabled, .bp3-dark .bp3-input.bp3-intent-warning.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input.bp3-intent-danger{
    -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-danger:focus{
      -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-input.bp3-intent-danger[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px #db3737;
              box-shadow:inset 0 0 0 1px #db3737; }
    .bp3-input.bp3-intent-danger:disabled, .bp3-input.bp3-intent-danger.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-input.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), 0 0 0 0 rgba(219, 55, 55, 0), inset 0 0 0 1px #db3737, inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-danger:focus{
        -webkit-box-shadow:0 0 0 1px #db3737, 0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px #db3737, 0 0 0 1px #db3737, 0 0 0 3px rgba(219, 55, 55, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
      .bp3-dark .bp3-input.bp3-intent-danger[readonly]{
        -webkit-box-shadow:inset 0 0 0 1px #db3737;
                box-shadow:inset 0 0 0 1px #db3737; }
      .bp3-dark .bp3-input.bp3-intent-danger:disabled, .bp3-dark .bp3-input.bp3-intent-danger.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none; }
  .bp3-input::-ms-clear{
    display:none; }
textarea.bp3-input{
  max-width:100%;
  padding:10px; }
  textarea.bp3-input, textarea.bp3-input.bp3-large, textarea.bp3-input.bp3-small{
    height:auto;
    line-height:inherit; }
  textarea.bp3-input.bp3-small{
    padding:8px; }
  .bp3-dark textarea.bp3-input{
    background:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark textarea.bp3-input::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input::placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark textarea.bp3-input:focus{
      -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark textarea.bp3-input[readonly]{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark textarea.bp3-input:disabled, .bp3-dark textarea.bp3-input.bp3-disabled{
      background:rgba(57, 75, 89, 0.5);
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
label.bp3-label{
  display:block;
  margin-bottom:15px;
  margin-top:0; }
  label.bp3-label .bp3-html-select,
  label.bp3-label .bp3-input,
  label.bp3-label .bp3-select,
  label.bp3-label .bp3-slider,
  label.bp3-label .bp3-popover-wrapper{
    display:block;
    margin-top:5px;
    text-transform:none; }
  label.bp3-label .bp3-button-group{
    margin-top:5px; }
  label.bp3-label .bp3-select select,
  label.bp3-label .bp3-html-select select{
    font-weight:400;
    vertical-align:top;
    width:100%; }
  label.bp3-label.bp3-disabled,
  label.bp3-label.bp3-disabled .bp3-text-muted{
    color:rgba(92, 112, 128, 0.6); }
  label.bp3-label.bp3-inline{
    line-height:30px; }
    label.bp3-label.bp3-inline .bp3-html-select,
    label.bp3-label.bp3-inline .bp3-input,
    label.bp3-label.bp3-inline .bp3-input-group,
    label.bp3-label.bp3-inline .bp3-select,
    label.bp3-label.bp3-inline .bp3-popover-wrapper{
      display:inline-block;
      margin:0 0 0 5px;
      vertical-align:top; }
    label.bp3-label.bp3-inline .bp3-button-group{
      margin:0 0 0 5px; }
    label.bp3-label.bp3-inline .bp3-input-group .bp3-input{
      margin-left:0; }
    label.bp3-label.bp3-inline.bp3-large{
      line-height:40px; }
  label.bp3-label:not(.bp3-inline) .bp3-popover-target{
    display:block; }
  .bp3-dark label.bp3-label{
    color:#f5f8fa; }
    .bp3-dark label.bp3-label.bp3-disabled,
    .bp3-dark label.bp3-label.bp3-disabled .bp3-text-muted{
      color:rgba(167, 182, 194, 0.6); }
.bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button{
  -webkit-box-flex:1;
      -ms-flex:1 1 14px;
          flex:1 1 14px;
  min-height:0;
  padding:0;
  width:30px; }
  .bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button:first-child{
    border-radius:0 3px 0 0; }
  .bp3-numeric-input .bp3-button-group.bp3-vertical > .bp3-button:last-child{
    border-radius:0 0 3px 0; }

.bp3-numeric-input .bp3-button-group.bp3-vertical:first-child > .bp3-button:first-child{
  border-radius:3px 0 0 0; }

.bp3-numeric-input .bp3-button-group.bp3-vertical:first-child > .bp3-button:last-child{
  border-radius:0 0 0 3px; }

.bp3-numeric-input.bp3-large .bp3-button-group.bp3-vertical > .bp3-button{
  width:40px; }

form{
  display:block; }
.bp3-html-select select,
.bp3-select select{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  border:none;
  border-radius:3px;
  cursor:pointer;
  font-size:14px;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  padding:5px 10px;
  text-align:left;
  vertical-align:middle;
  background-color:#f5f8fa;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
  color:#182026;
  -moz-appearance:none;
  -webkit-appearance:none;
  border-radius:3px;
  height:30px;
  padding:0 25px 0 10px;
  width:100%; }
  .bp3-html-select select > *, .bp3-select select > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-html-select select > .bp3-fill, .bp3-select select > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-html-select select::before,
  .bp3-select select::before, .bp3-html-select select > *, .bp3-select select > *{
    margin-right:7px; }
  .bp3-html-select select:empty::before,
  .bp3-select select:empty::before,
  .bp3-html-select select > :last-child,
  .bp3-select select > :last-child{
    margin-right:0; }
  .bp3-html-select select:hover,
  .bp3-select select:hover{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
  .bp3-html-select select:active,
  .bp3-select select:active, .bp3-html-select select.bp3-active,
  .bp3-select select.bp3-active{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-html-select select:disabled,
  .bp3-select select:disabled, .bp3-html-select select.bp3-disabled,
  .bp3-select select.bp3-disabled{
    background-color:rgba(206, 217, 224, 0.5);
    background-image:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    outline:none; }
    .bp3-html-select select:disabled.bp3-active,
    .bp3-select select:disabled.bp3-active, .bp3-html-select select:disabled.bp3-active:hover,
    .bp3-select select:disabled.bp3-active:hover, .bp3-html-select select.bp3-disabled.bp3-active,
    .bp3-select select.bp3-disabled.bp3-active, .bp3-html-select select.bp3-disabled.bp3-active:hover,
    .bp3-select select.bp3-disabled.bp3-active:hover{
      background:rgba(206, 217, 224, 0.7); }

.bp3-html-select.bp3-minimal select,
.bp3-select.bp3-minimal select{
  background:none;
  -webkit-box-shadow:none;
          box-shadow:none; }
  .bp3-html-select.bp3-minimal select:hover,
  .bp3-select.bp3-minimal select:hover{
    background:rgba(167, 182, 194, 0.3);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:#182026;
    text-decoration:none; }
  .bp3-html-select.bp3-minimal select:active,
  .bp3-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal select.bp3-active,
  .bp3-select.bp3-minimal select.bp3-active{
    background:rgba(115, 134, 148, 0.3);
    -webkit-box-shadow:none;
            box-shadow:none;
    color:#182026; }
  .bp3-html-select.bp3-minimal select:disabled,
  .bp3-select.bp3-minimal select:disabled, .bp3-html-select.bp3-minimal select:disabled:hover,
  .bp3-select.bp3-minimal select:disabled:hover, .bp3-html-select.bp3-minimal select.bp3-disabled,
  .bp3-select.bp3-minimal select.bp3-disabled, .bp3-html-select.bp3-minimal select.bp3-disabled:hover,
  .bp3-select.bp3-minimal select.bp3-disabled:hover{
    background:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
    .bp3-html-select.bp3-minimal select:disabled.bp3-active,
    .bp3-select.bp3-minimal select:disabled.bp3-active, .bp3-html-select.bp3-minimal select:disabled:hover.bp3-active,
    .bp3-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-html-select.bp3-minimal select.bp3-disabled.bp3-active,
    .bp3-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-disabled:hover.bp3-active,
    .bp3-select.bp3-minimal select.bp3-disabled:hover.bp3-active{
      background:rgba(115, 134, 148, 0.3); }
  .bp3-dark .bp3-html-select.bp3-minimal select, .bp3-html-select.bp3-minimal .bp3-dark select,
  .bp3-dark .bp3-select.bp3-minimal select, .bp3-select.bp3-minimal .bp3-dark select{
    background:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:inherit; }
    .bp3-dark .bp3-html-select.bp3-minimal select:hover, .bp3-html-select.bp3-minimal .bp3-dark select:hover,
    .bp3-dark .bp3-select.bp3-minimal select:hover, .bp3-select.bp3-minimal .bp3-dark select:hover, .bp3-dark .bp3-html-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal .bp3-dark select:active,
    .bp3-dark .bp3-select.bp3-minimal select:active, .bp3-select.bp3-minimal .bp3-dark select:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-active,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none; }
    .bp3-dark .bp3-html-select.bp3-minimal select:hover, .bp3-html-select.bp3-minimal .bp3-dark select:hover,
    .bp3-dark .bp3-select.bp3-minimal select:hover, .bp3-select.bp3-minimal .bp3-dark select:hover{
      background:rgba(138, 155, 168, 0.15); }
    .bp3-dark .bp3-html-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal .bp3-dark select:active,
    .bp3-dark .bp3-select.bp3-minimal select:active, .bp3-select.bp3-minimal .bp3-dark select:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-active,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-active{
      background:rgba(138, 155, 168, 0.3);
      color:#f5f8fa; }
    .bp3-dark .bp3-html-select.bp3-minimal select:disabled, .bp3-html-select.bp3-minimal .bp3-dark select:disabled,
    .bp3-dark .bp3-select.bp3-minimal select:disabled, .bp3-select.bp3-minimal .bp3-dark select:disabled, .bp3-dark .bp3-html-select.bp3-minimal select:disabled:hover, .bp3-html-select.bp3-minimal .bp3-dark select:disabled:hover,
    .bp3-dark .bp3-select.bp3-minimal select:disabled:hover, .bp3-select.bp3-minimal .bp3-dark select:disabled:hover, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled:hover,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled:hover{
      background:none;
      color:rgba(167, 182, 194, 0.6);
      cursor:not-allowed; }
      .bp3-dark .bp3-html-select.bp3-minimal select:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select:disabled.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select:disabled:hover.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-select.bp3-minimal .bp3-dark select:disabled:hover.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-disabled:hover.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-disabled:hover.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-disabled:hover.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-disabled:hover.bp3-active{
        background:rgba(138, 155, 168, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-primary,
  .bp3-select.bp3-minimal select.bp3-intent-primary{
    color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover,
    .bp3-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-html-select.bp3-minimal select.bp3-intent-primary:active,
    .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover,
    .bp3-select.bp3-minimal select.bp3-intent-primary:hover{
      background:rgba(19, 124, 189, 0.15);
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:active,
    .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active{
      background:rgba(19, 124, 189, 0.3);
      color:#106ba3; }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled{
      background:none;
      color:rgba(16, 107, 163, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active{
        background:rgba(19, 124, 189, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-primary .bp3-button-spinner .bp3-spinner-head{
      stroke:#106ba3; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary{
      color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:hover{
        background:rgba(19, 124, 189, 0.2);
        color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-active{
        background:rgba(19, 124, 189, 0.3);
        color:#48aff0; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled{
        background:none;
        color:rgba(72, 175, 240, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-primary.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-primary.bp3-disabled.bp3-active{
          background:rgba(19, 124, 189, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-success,
  .bp3-select.bp3-minimal select.bp3-intent-success{
    color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:hover,
    .bp3-select.bp3-minimal select.bp3-intent-success:hover, .bp3-html-select.bp3-minimal select.bp3-intent-success:active,
    .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:hover,
    .bp3-select.bp3-minimal select.bp3-intent-success:hover{
      background:rgba(15, 153, 96, 0.15);
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:active,
    .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active{
      background:rgba(15, 153, 96, 0.3);
      color:#0d8050; }
    .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled{
      background:none;
      color:rgba(13, 128, 80, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active{
        background:rgba(15, 153, 96, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-success .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-success .bp3-button-spinner .bp3-spinner-head{
      stroke:#0d8050; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success{
      color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:hover{
        background:rgba(15, 153, 96, 0.2);
        color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-active{
        background:rgba(15, 153, 96, 0.3);
        color:#3dcc91; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled{
        background:none;
        color:rgba(61, 204, 145, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-success.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-success.bp3-disabled.bp3-active{
          background:rgba(15, 153, 96, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-warning,
  .bp3-select.bp3-minimal select.bp3-intent-warning{
    color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover,
    .bp3-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-html-select.bp3-minimal select.bp3-intent-warning:active,
    .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover,
    .bp3-select.bp3-minimal select.bp3-intent-warning:hover{
      background:rgba(217, 130, 43, 0.15);
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:active,
    .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active{
      background:rgba(217, 130, 43, 0.3);
      color:#bf7326; }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled{
      background:none;
      color:rgba(191, 115, 38, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active{
        background:rgba(217, 130, 43, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-warning .bp3-button-spinner .bp3-spinner-head{
      stroke:#bf7326; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning{
      color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:hover{
        background:rgba(217, 130, 43, 0.2);
        color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-active{
        background:rgba(217, 130, 43, 0.3);
        color:#ffb366; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled{
        background:none;
        color:rgba(255, 179, 102, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-warning.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-warning.bp3-disabled.bp3-active{
          background:rgba(217, 130, 43, 0.3); }
  .bp3-html-select.bp3-minimal select.bp3-intent-danger,
  .bp3-select.bp3-minimal select.bp3-intent-danger{
    color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover,
    .bp3-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-html-select.bp3-minimal select.bp3-intent-danger:active,
    .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active{
      background:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover,
    .bp3-select.bp3-minimal select.bp3-intent-danger:hover{
      background:rgba(219, 55, 55, 0.15);
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:active,
    .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active{
      background:rgba(219, 55, 55, 0.3);
      color:#c23030; }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled,
    .bp3-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled,
    .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled{
      background:none;
      color:rgba(194, 48, 48, 0.5); }
      .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active,
      .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active{
        background:rgba(219, 55, 55, 0.3); }
    .bp3-html-select.bp3-minimal select.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head, .bp3-select.bp3-minimal select.bp3-intent-danger .bp3-button-spinner .bp3-spinner-head{
      stroke:#c23030; }
    .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger{
      color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:hover,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:hover, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:hover{
        background:rgba(219, 55, 55, 0.2);
        color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-active,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-active{
        background:rgba(219, 55, 55, 0.3);
        color:#ff7373; }
      .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled,
      .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled{
        background:none;
        color:rgba(255, 115, 115, 0.5); }
        .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger:disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger:disabled.bp3-active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled.bp3-active,
        .bp3-dark .bp3-select.bp3-minimal select.bp3-intent-danger.bp3-disabled.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-intent-danger.bp3-disabled.bp3-active{
          background:rgba(219, 55, 55, 0.3); }

.bp3-html-select.bp3-large select,
.bp3-select.bp3-large select{
  font-size:16px;
  height:40px;
  padding-right:35px; }

.bp3-dark .bp3-html-select select, .bp3-dark .bp3-select select{
  background-color:#394b59;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
  color:#f5f8fa; }
  .bp3-dark .bp3-html-select select:hover, .bp3-dark .bp3-select select:hover, .bp3-dark .bp3-html-select select:active, .bp3-dark .bp3-select select:active, .bp3-dark .bp3-html-select select.bp3-active, .bp3-dark .bp3-select select.bp3-active{
    color:#f5f8fa; }
  .bp3-dark .bp3-html-select select:hover, .bp3-dark .bp3-select select:hover{
    background-color:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-html-select select:active, .bp3-dark .bp3-select select:active, .bp3-dark .bp3-html-select select.bp3-active, .bp3-dark .bp3-select select.bp3-active{
    background-color:#202b33;
    background-image:none;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-html-select select:disabled, .bp3-dark .bp3-select select:disabled, .bp3-dark .bp3-html-select select.bp3-disabled, .bp3-dark .bp3-select select.bp3-disabled{
    background-color:rgba(57, 75, 89, 0.5);
    background-image:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-html-select select:disabled.bp3-active, .bp3-dark .bp3-select select:disabled.bp3-active, .bp3-dark .bp3-html-select select.bp3-disabled.bp3-active, .bp3-dark .bp3-select select.bp3-disabled.bp3-active{
      background:rgba(57, 75, 89, 0.7); }
  .bp3-dark .bp3-html-select select .bp3-button-spinner .bp3-spinner-head, .bp3-dark .bp3-select select .bp3-button-spinner .bp3-spinner-head{
    background:rgba(16, 22, 26, 0.5);
    stroke:#8a9ba8; }

.bp3-html-select select:disabled,
.bp3-select select:disabled{
  background-color:rgba(206, 217, 224, 0.5);
  -webkit-box-shadow:none;
          box-shadow:none;
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-html-select .bp3-icon,
.bp3-select .bp3-icon, .bp3-select::after{
  color:#5c7080;
  pointer-events:none;
  position:absolute;
  right:7px;
  top:7px; }
  .bp3-html-select .bp3-disabled.bp3-icon,
  .bp3-select .bp3-disabled.bp3-icon, .bp3-disabled.bp3-select::after{
    color:rgba(92, 112, 128, 0.6); }
.bp3-html-select,
.bp3-select{
  display:inline-block;
  letter-spacing:normal;
  position:relative;
  vertical-align:middle; }
  .bp3-html-select select::-ms-expand,
  .bp3-select select::-ms-expand{
    display:none; }
  .bp3-html-select .bp3-icon,
  .bp3-select .bp3-icon{
    color:#5c7080; }
    .bp3-html-select .bp3-icon:hover,
    .bp3-select .bp3-icon:hover{
      color:#182026; }
    .bp3-dark .bp3-html-select .bp3-icon, .bp3-dark
    .bp3-select .bp3-icon{
      color:#a7b6c2; }
      .bp3-dark .bp3-html-select .bp3-icon:hover, .bp3-dark
      .bp3-select .bp3-icon:hover{
        color:#f5f8fa; }
  .bp3-html-select.bp3-large::after,
  .bp3-html-select.bp3-large .bp3-icon,
  .bp3-select.bp3-large::after,
  .bp3-select.bp3-large .bp3-icon{
    right:12px;
    top:12px; }
  .bp3-html-select.bp3-fill,
  .bp3-html-select.bp3-fill select,
  .bp3-select.bp3-fill,
  .bp3-select.bp3-fill select{
    width:100%; }
  .bp3-dark .bp3-html-select option, .bp3-dark
  .bp3-select option{
    background-color:#30404d;
    color:#f5f8fa; }
  .bp3-dark .bp3-html-select option:disabled, .bp3-dark
  .bp3-select option:disabled{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-html-select::after, .bp3-dark
  .bp3-select::after{
    color:#a7b6c2; }

.bp3-select::after{
  font-family:"Icons16", sans-serif;
  font-size:16px;
  font-style:normal;
  font-weight:400;
  line-height:1;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  content:""; }
.bp3-running-text table, table.bp3-html-table{
  border-spacing:0;
  font-size:14px; }
  .bp3-running-text table th, table.bp3-html-table th,
  .bp3-running-text table td,
  table.bp3-html-table td{
    padding:11px;
    text-align:left;
    vertical-align:top; }
  .bp3-running-text table th, table.bp3-html-table th{
    color:#182026;
    font-weight:600; }
  
  .bp3-running-text table td,
  table.bp3-html-table td{
    color:#182026; }
  .bp3-running-text table tbody tr:first-child th, table.bp3-html-table tbody tr:first-child th,
  .bp3-running-text table tbody tr:first-child td,
  table.bp3-html-table tbody tr:first-child td,
  .bp3-running-text table tfoot tr:first-child th,
  table.bp3-html-table tfoot tr:first-child th,
  .bp3-running-text table tfoot tr:first-child td,
  table.bp3-html-table tfoot tr:first-child td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-running-text table th, .bp3-running-text .bp3-dark table th, .bp3-dark table.bp3-html-table th{
    color:#f5f8fa; }
  .bp3-dark .bp3-running-text table td, .bp3-running-text .bp3-dark table td, .bp3-dark table.bp3-html-table td{
    color:#f5f8fa; }
  .bp3-dark .bp3-running-text table tbody tr:first-child th, .bp3-running-text .bp3-dark table tbody tr:first-child th, .bp3-dark table.bp3-html-table tbody tr:first-child th,
  .bp3-dark .bp3-running-text table tbody tr:first-child td,
  .bp3-running-text .bp3-dark table tbody tr:first-child td,
  .bp3-dark table.bp3-html-table tbody tr:first-child td,
  .bp3-dark .bp3-running-text table tfoot tr:first-child th,
  .bp3-running-text .bp3-dark table tfoot tr:first-child th,
  .bp3-dark table.bp3-html-table tfoot tr:first-child th,
  .bp3-dark .bp3-running-text table tfoot tr:first-child td,
  .bp3-running-text .bp3-dark table tfoot tr:first-child td,
  .bp3-dark table.bp3-html-table tfoot tr:first-child td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15); }

table.bp3-html-table.bp3-html-table-condensed th,
table.bp3-html-table.bp3-html-table-condensed td, table.bp3-html-table.bp3-small th,
table.bp3-html-table.bp3-small td{
  padding-bottom:6px;
  padding-top:6px; }

table.bp3-html-table.bp3-html-table-striped tbody tr:nth-child(odd) td{
  background:rgba(191, 204, 214, 0.15); }

table.bp3-html-table.bp3-html-table-bordered th:not(:first-child){
  -webkit-box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-html-table-bordered tbody tr td,
table.bp3-html-table.bp3-html-table-bordered tfoot tr td{
  -webkit-box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15); }
  table.bp3-html-table.bp3-html-table-bordered tbody tr td:not(:first-child),
  table.bp3-html-table.bp3-html-table-bordered tfoot tr td:not(:first-child){
    -webkit-box-shadow:inset 1px 1px 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 1px 1px 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td{
  -webkit-box-shadow:none;
          box-shadow:none; }
  table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td:not(:first-child){
    -webkit-box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-interactive tbody tr:hover td{
  background-color:rgba(191, 204, 214, 0.3);
  cursor:pointer; }

table.bp3-html-table.bp3-interactive tbody tr:active td{
  background-color:rgba(191, 204, 214, 0.4); }

.bp3-dark table.bp3-html-table{ }
  .bp3-dark table.bp3-html-table.bp3-html-table-striped tbody tr:nth-child(odd) td{
    background:rgba(92, 112, 128, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered th:not(:first-child){
    -webkit-box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered tbody tr td,
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered tfoot tr td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15); }
    .bp3-dark table.bp3-html-table.bp3-html-table-bordered tbody tr td:not(:first-child),
    .bp3-dark table.bp3-html-table.bp3-html-table-bordered tfoot tr td:not(:first-child){
      -webkit-box-shadow:inset 1px 1px 0 0 rgba(255, 255, 255, 0.15);
              box-shadow:inset 1px 1px 0 0 rgba(255, 255, 255, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td{
    -webkit-box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15); }
    .bp3-dark table.bp3-html-table.bp3-html-table-bordered.bp3-html-table-striped tbody tr:not(:first-child) td:first-child{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-dark table.bp3-html-table.bp3-interactive tbody tr:hover td{
    background-color:rgba(92, 112, 128, 0.3);
    cursor:pointer; }
  .bp3-dark table.bp3-html-table.bp3-interactive tbody tr:active td{
    background-color:rgba(92, 112, 128, 0.4); }

.bp3-key-combo{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center; }
  .bp3-key-combo > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-key-combo > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-key-combo::before,
  .bp3-key-combo > *{
    margin-right:5px; }
  .bp3-key-combo:empty::before,
  .bp3-key-combo > :last-child{
    margin-right:0; }

.bp3-hotkey-dialog{
  padding-bottom:0;
  top:40px; }
  .bp3-hotkey-dialog .bp3-dialog-body{
    margin:0;
    padding:0; }
  .bp3-hotkey-dialog .bp3-hotkey-label{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1; }

.bp3-hotkey-column{
  margin:auto;
  max-height:80vh;
  overflow-y:auto;
  padding:30px; }
  .bp3-hotkey-column .bp3-heading{
    margin-bottom:20px; }
    .bp3-hotkey-column .bp3-heading:not(:first-child){
      margin-top:40px; }

.bp3-hotkey{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:justify;
      -ms-flex-pack:justify;
          justify-content:space-between;
  margin-left:0;
  margin-right:0; }
  .bp3-hotkey:not(:last-child){
    margin-bottom:10px; }
.bp3-icon{
  display:inline-block;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  vertical-align:text-bottom; }
  .bp3-icon:not(:empty)::before{
    content:"" !important;
    content:unset !important; }
  .bp3-icon > svg{
    display:block; }
    .bp3-icon > svg:not([fill]){
      fill:currentColor; }

.bp3-icon.bp3-intent-primary, .bp3-icon-standard.bp3-intent-primary, .bp3-icon-large.bp3-intent-primary{
  color:#106ba3; }
  .bp3-dark .bp3-icon.bp3-intent-primary, .bp3-dark .bp3-icon-standard.bp3-intent-primary, .bp3-dark .bp3-icon-large.bp3-intent-primary{
    color:#48aff0; }

.bp3-icon.bp3-intent-success, .bp3-icon-standard.bp3-intent-success, .bp3-icon-large.bp3-intent-success{
  color:#0d8050; }
  .bp3-dark .bp3-icon.bp3-intent-success, .bp3-dark .bp3-icon-standard.bp3-intent-success, .bp3-dark .bp3-icon-large.bp3-intent-success{
    color:#3dcc91; }

.bp3-icon.bp3-intent-warning, .bp3-icon-standard.bp3-intent-warning, .bp3-icon-large.bp3-intent-warning{
  color:#bf7326; }
  .bp3-dark .bp3-icon.bp3-intent-warning, .bp3-dark .bp3-icon-standard.bp3-intent-warning, .bp3-dark .bp3-icon-large.bp3-intent-warning{
    color:#ffb366; }

.bp3-icon.bp3-intent-danger, .bp3-icon-standard.bp3-intent-danger, .bp3-icon-large.bp3-intent-danger{
  color:#c23030; }
  .bp3-dark .bp3-icon.bp3-intent-danger, .bp3-dark .bp3-icon-standard.bp3-intent-danger, .bp3-dark .bp3-icon-large.bp3-intent-danger{
    color:#ff7373; }

span.bp3-icon-standard{
  font-family:"Icons16", sans-serif;
  font-size:16px;
  font-style:normal;
  font-weight:400;
  line-height:1;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  display:inline-block; }

span.bp3-icon-large{
  font-family:"Icons20", sans-serif;
  font-size:20px;
  font-style:normal;
  font-weight:400;
  line-height:1;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  display:inline-block; }

span.bp3-icon:empty{
  font-family:"Icons20";
  font-size:inherit;
  font-style:normal;
  font-weight:400;
  line-height:1; }
  span.bp3-icon:empty::before{
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased; }

.bp3-icon-add::before{
  content:""; }

.bp3-icon-add-column-left::before{
  content:""; }

.bp3-icon-add-column-right::before{
  content:""; }

.bp3-icon-add-row-bottom::before{
  content:""; }

.bp3-icon-add-row-top::before{
  content:""; }

.bp3-icon-add-to-artifact::before{
  content:""; }

.bp3-icon-add-to-folder::before{
  content:""; }

.bp3-icon-airplane::before{
  content:""; }

.bp3-icon-align-center::before{
  content:""; }

.bp3-icon-align-justify::before{
  content:""; }

.bp3-icon-align-left::before{
  content:""; }

.bp3-icon-align-right::before{
  content:""; }

.bp3-icon-alignment-bottom::before{
  content:""; }

.bp3-icon-alignment-horizontal-center::before{
  content:""; }

.bp3-icon-alignment-left::before{
  content:""; }

.bp3-icon-alignment-right::before{
  content:""; }

.bp3-icon-alignment-top::before{
  content:""; }

.bp3-icon-alignment-vertical-center::before{
  content:""; }

.bp3-icon-annotation::before{
  content:""; }

.bp3-icon-application::before{
  content:""; }

.bp3-icon-applications::before{
  content:""; }

.bp3-icon-archive::before{
  content:""; }

.bp3-icon-arrow-bottom-left::before{
  content:"↙"; }

.bp3-icon-arrow-bottom-right::before{
  content:"↘"; }

.bp3-icon-arrow-down::before{
  content:"↓"; }

.bp3-icon-arrow-left::before{
  content:"←"; }

.bp3-icon-arrow-right::before{
  content:"→"; }

.bp3-icon-arrow-top-left::before{
  content:"↖"; }

.bp3-icon-arrow-top-right::before{
  content:"↗"; }

.bp3-icon-arrow-up::before{
  content:"↑"; }

.bp3-icon-arrows-horizontal::before{
  content:"↔"; }

.bp3-icon-arrows-vertical::before{
  content:"↕"; }

.bp3-icon-asterisk::before{
  content:"*"; }

.bp3-icon-automatic-updates::before{
  content:""; }

.bp3-icon-badge::before{
  content:""; }

.bp3-icon-ban-circle::before{
  content:""; }

.bp3-icon-bank-account::before{
  content:""; }

.bp3-icon-barcode::before{
  content:""; }

.bp3-icon-blank::before{
  content:""; }

.bp3-icon-blocked-person::before{
  content:""; }

.bp3-icon-bold::before{
  content:""; }

.bp3-icon-book::before{
  content:""; }

.bp3-icon-bookmark::before{
  content:""; }

.bp3-icon-box::before{
  content:""; }

.bp3-icon-briefcase::before{
  content:""; }

.bp3-icon-bring-data::before{
  content:""; }

.bp3-icon-build::before{
  content:""; }

.bp3-icon-calculator::before{
  content:""; }

.bp3-icon-calendar::before{
  content:""; }

.bp3-icon-camera::before{
  content:""; }

.bp3-icon-caret-down::before{
  content:"⌄"; }

.bp3-icon-caret-left::before{
  content:"〈"; }

.bp3-icon-caret-right::before{
  content:"〉"; }

.bp3-icon-caret-up::before{
  content:"⌃"; }

.bp3-icon-cell-tower::before{
  content:""; }

.bp3-icon-changes::before{
  content:""; }

.bp3-icon-chart::before{
  content:""; }

.bp3-icon-chat::before{
  content:""; }

.bp3-icon-chevron-backward::before{
  content:""; }

.bp3-icon-chevron-down::before{
  content:""; }

.bp3-icon-chevron-forward::before{
  content:""; }

.bp3-icon-chevron-left::before{
  content:""; }

.bp3-icon-chevron-right::before{
  content:""; }

.bp3-icon-chevron-up::before{
  content:""; }

.bp3-icon-circle::before{
  content:""; }

.bp3-icon-circle-arrow-down::before{
  content:""; }

.bp3-icon-circle-arrow-left::before{
  content:""; }

.bp3-icon-circle-arrow-right::before{
  content:""; }

.bp3-icon-circle-arrow-up::before{
  content:""; }

.bp3-icon-citation::before{
  content:""; }

.bp3-icon-clean::before{
  content:""; }

.bp3-icon-clipboard::before{
  content:""; }

.bp3-icon-cloud::before{
  content:"☁"; }

.bp3-icon-cloud-download::before{
  content:""; }

.bp3-icon-cloud-upload::before{
  content:""; }

.bp3-icon-code::before{
  content:""; }

.bp3-icon-code-block::before{
  content:""; }

.bp3-icon-cog::before{
  content:""; }

.bp3-icon-collapse-all::before{
  content:""; }

.bp3-icon-column-layout::before{
  content:""; }

.bp3-icon-comment::before{
  content:""; }

.bp3-icon-comparison::before{
  content:""; }

.bp3-icon-compass::before{
  content:""; }

.bp3-icon-compressed::before{
  content:""; }

.bp3-icon-confirm::before{
  content:""; }

.bp3-icon-console::before{
  content:""; }

.bp3-icon-contrast::before{
  content:""; }

.bp3-icon-control::before{
  content:""; }

.bp3-icon-credit-card::before{
  content:""; }

.bp3-icon-cross::before{
  content:"✗"; }

.bp3-icon-crown::before{
  content:""; }

.bp3-icon-cube::before{
  content:""; }

.bp3-icon-cube-add::before{
  content:""; }

.bp3-icon-cube-remove::before{
  content:""; }

.bp3-icon-curved-range-chart::before{
  content:""; }

.bp3-icon-cut::before{
  content:""; }

.bp3-icon-dashboard::before{
  content:""; }

.bp3-icon-data-lineage::before{
  content:""; }

.bp3-icon-database::before{
  content:""; }

.bp3-icon-delete::before{
  content:""; }

.bp3-icon-delta::before{
  content:"Δ"; }

.bp3-icon-derive-column::before{
  content:""; }

.bp3-icon-desktop::before{
  content:""; }

.bp3-icon-diagnosis::before{
  content:""; }

.bp3-icon-diagram-tree::before{
  content:""; }

.bp3-icon-direction-left::before{
  content:""; }

.bp3-icon-direction-right::before{
  content:""; }

.bp3-icon-disable::before{
  content:""; }

.bp3-icon-document::before{
  content:""; }

.bp3-icon-document-open::before{
  content:""; }

.bp3-icon-document-share::before{
  content:""; }

.bp3-icon-dollar::before{
  content:"$"; }

.bp3-icon-dot::before{
  content:"•"; }

.bp3-icon-double-caret-horizontal::before{
  content:""; }

.bp3-icon-double-caret-vertical::before{
  content:""; }

.bp3-icon-double-chevron-down::before{
  content:""; }

.bp3-icon-double-chevron-left::before{
  content:""; }

.bp3-icon-double-chevron-right::before{
  content:""; }

.bp3-icon-double-chevron-up::before{
  content:""; }

.bp3-icon-doughnut-chart::before{
  content:""; }

.bp3-icon-download::before{
  content:""; }

.bp3-icon-drag-handle-horizontal::before{
  content:""; }

.bp3-icon-drag-handle-vertical::before{
  content:""; }

.bp3-icon-draw::before{
  content:""; }

.bp3-icon-drive-time::before{
  content:""; }

.bp3-icon-duplicate::before{
  content:""; }

.bp3-icon-edit::before{
  content:"✎"; }

.bp3-icon-eject::before{
  content:"⏏"; }

.bp3-icon-endorsed::before{
  content:""; }

.bp3-icon-envelope::before{
  content:"✉"; }

.bp3-icon-equals::before{
  content:""; }

.bp3-icon-eraser::before{
  content:""; }

.bp3-icon-error::before{
  content:""; }

.bp3-icon-euro::before{
  content:"€"; }

.bp3-icon-exchange::before{
  content:""; }

.bp3-icon-exclude-row::before{
  content:""; }

.bp3-icon-expand-all::before{
  content:""; }

.bp3-icon-export::before{
  content:""; }

.bp3-icon-eye-off::before{
  content:""; }

.bp3-icon-eye-on::before{
  content:""; }

.bp3-icon-eye-open::before{
  content:""; }

.bp3-icon-fast-backward::before{
  content:""; }

.bp3-icon-fast-forward::before{
  content:""; }

.bp3-icon-feed::before{
  content:""; }

.bp3-icon-feed-subscribed::before{
  content:""; }

.bp3-icon-film::before{
  content:""; }

.bp3-icon-filter::before{
  content:""; }

.bp3-icon-filter-keep::before{
  content:""; }

.bp3-icon-filter-list::before{
  content:""; }

.bp3-icon-filter-open::before{
  content:""; }

.bp3-icon-filter-remove::before{
  content:""; }

.bp3-icon-flag::before{
  content:"⚑"; }

.bp3-icon-flame::before{
  content:""; }

.bp3-icon-flash::before{
  content:""; }

.bp3-icon-floppy-disk::before{
  content:""; }

.bp3-icon-flow-branch::before{
  content:""; }

.bp3-icon-flow-end::before{
  content:""; }

.bp3-icon-flow-linear::before{
  content:""; }

.bp3-icon-flow-review::before{
  content:""; }

.bp3-icon-flow-review-branch::before{
  content:""; }

.bp3-icon-flows::before{
  content:""; }

.bp3-icon-folder-close::before{
  content:""; }

.bp3-icon-folder-new::before{
  content:""; }

.bp3-icon-folder-open::before{
  content:""; }

.bp3-icon-folder-shared::before{
  content:""; }

.bp3-icon-folder-shared-open::before{
  content:""; }

.bp3-icon-follower::before{
  content:""; }

.bp3-icon-following::before{
  content:""; }

.bp3-icon-font::before{
  content:""; }

.bp3-icon-fork::before{
  content:""; }

.bp3-icon-form::before{
  content:""; }

.bp3-icon-full-circle::before{
  content:""; }

.bp3-icon-full-stacked-chart::before{
  content:""; }

.bp3-icon-fullscreen::before{
  content:""; }

.bp3-icon-function::before{
  content:""; }

.bp3-icon-gantt-chart::before{
  content:""; }

.bp3-icon-geolocation::before{
  content:""; }

.bp3-icon-geosearch::before{
  content:""; }

.bp3-icon-git-branch::before{
  content:""; }

.bp3-icon-git-commit::before{
  content:""; }

.bp3-icon-git-merge::before{
  content:""; }

.bp3-icon-git-new-branch::before{
  content:""; }

.bp3-icon-git-pull::before{
  content:""; }

.bp3-icon-git-push::before{
  content:""; }

.bp3-icon-git-repo::before{
  content:""; }

.bp3-icon-glass::before{
  content:""; }

.bp3-icon-globe::before{
  content:""; }

.bp3-icon-globe-network::before{
  content:""; }

.bp3-icon-graph::before{
  content:""; }

.bp3-icon-graph-remove::before{
  content:""; }

.bp3-icon-greater-than::before{
  content:""; }

.bp3-icon-greater-than-or-equal-to::before{
  content:""; }

.bp3-icon-grid::before{
  content:""; }

.bp3-icon-grid-view::before{
  content:""; }

.bp3-icon-group-objects::before{
  content:""; }

.bp3-icon-grouped-bar-chart::before{
  content:""; }

.bp3-icon-hand::before{
  content:""; }

.bp3-icon-hand-down::before{
  content:""; }

.bp3-icon-hand-left::before{
  content:""; }

.bp3-icon-hand-right::before{
  content:""; }

.bp3-icon-hand-up::before{
  content:""; }

.bp3-icon-header::before{
  content:""; }

.bp3-icon-header-one::before{
  content:""; }

.bp3-icon-header-two::before{
  content:""; }

.bp3-icon-headset::before{
  content:""; }

.bp3-icon-heart::before{
  content:"♥"; }

.bp3-icon-heart-broken::before{
  content:""; }

.bp3-icon-heat-grid::before{
  content:""; }

.bp3-icon-heatmap::before{
  content:""; }

.bp3-icon-help::before{
  content:"?"; }

.bp3-icon-helper-management::before{
  content:""; }

.bp3-icon-highlight::before{
  content:""; }

.bp3-icon-history::before{
  content:""; }

.bp3-icon-home::before{
  content:"⌂"; }

.bp3-icon-horizontal-bar-chart::before{
  content:""; }

.bp3-icon-horizontal-bar-chart-asc::before{
  content:""; }

.bp3-icon-horizontal-bar-chart-desc::before{
  content:""; }

.bp3-icon-horizontal-distribution::before{
  content:""; }

.bp3-icon-id-number::before{
  content:""; }

.bp3-icon-image-rotate-left::before{
  content:""; }

.bp3-icon-image-rotate-right::before{
  content:""; }

.bp3-icon-import::before{
  content:""; }

.bp3-icon-inbox::before{
  content:""; }

.bp3-icon-inbox-filtered::before{
  content:""; }

.bp3-icon-inbox-geo::before{
  content:""; }

.bp3-icon-inbox-search::before{
  content:""; }

.bp3-icon-inbox-update::before{
  content:""; }

.bp3-icon-info-sign::before{
  content:"ℹ"; }

.bp3-icon-inheritance::before{
  content:""; }

.bp3-icon-inner-join::before{
  content:""; }

.bp3-icon-insert::before{
  content:""; }

.bp3-icon-intersection::before{
  content:""; }

.bp3-icon-ip-address::before{
  content:""; }

.bp3-icon-issue::before{
  content:""; }

.bp3-icon-issue-closed::before{
  content:""; }

.bp3-icon-issue-new::before{
  content:""; }

.bp3-icon-italic::before{
  content:""; }

.bp3-icon-join-table::before{
  content:""; }

.bp3-icon-key::before{
  content:""; }

.bp3-icon-key-backspace::before{
  content:""; }

.bp3-icon-key-command::before{
  content:""; }

.bp3-icon-key-control::before{
  content:""; }

.bp3-icon-key-delete::before{
  content:""; }

.bp3-icon-key-enter::before{
  content:""; }

.bp3-icon-key-escape::before{
  content:""; }

.bp3-icon-key-option::before{
  content:""; }

.bp3-icon-key-shift::before{
  content:""; }

.bp3-icon-key-tab::before{
  content:""; }

.bp3-icon-known-vehicle::before{
  content:""; }

.bp3-icon-lab-test::before{
  content:""; }

.bp3-icon-label::before{
  content:""; }

.bp3-icon-layer::before{
  content:""; }

.bp3-icon-layers::before{
  content:""; }

.bp3-icon-layout::before{
  content:""; }

.bp3-icon-layout-auto::before{
  content:""; }

.bp3-icon-layout-balloon::before{
  content:""; }

.bp3-icon-layout-circle::before{
  content:""; }

.bp3-icon-layout-grid::before{
  content:""; }

.bp3-icon-layout-group-by::before{
  content:""; }

.bp3-icon-layout-hierarchy::before{
  content:""; }

.bp3-icon-layout-linear::before{
  content:""; }

.bp3-icon-layout-skew-grid::before{
  content:""; }

.bp3-icon-layout-sorted-clusters::before{
  content:""; }

.bp3-icon-learning::before{
  content:""; }

.bp3-icon-left-join::before{
  content:""; }

.bp3-icon-less-than::before{
  content:""; }

.bp3-icon-less-than-or-equal-to::before{
  content:""; }

.bp3-icon-lifesaver::before{
  content:""; }

.bp3-icon-lightbulb::before{
  content:""; }

.bp3-icon-link::before{
  content:""; }

.bp3-icon-list::before{
  content:"☰"; }

.bp3-icon-list-columns::before{
  content:""; }

.bp3-icon-list-detail-view::before{
  content:""; }

.bp3-icon-locate::before{
  content:""; }

.bp3-icon-lock::before{
  content:""; }

.bp3-icon-log-in::before{
  content:""; }

.bp3-icon-log-out::before{
  content:""; }

.bp3-icon-manual::before{
  content:""; }

.bp3-icon-manually-entered-data::before{
  content:""; }

.bp3-icon-map::before{
  content:""; }

.bp3-icon-map-create::before{
  content:""; }

.bp3-icon-map-marker::before{
  content:""; }

.bp3-icon-maximize::before{
  content:""; }

.bp3-icon-media::before{
  content:""; }

.bp3-icon-menu::before{
  content:""; }

.bp3-icon-menu-closed::before{
  content:""; }

.bp3-icon-menu-open::before{
  content:""; }

.bp3-icon-merge-columns::before{
  content:""; }

.bp3-icon-merge-links::before{
  content:""; }

.bp3-icon-minimize::before{
  content:""; }

.bp3-icon-minus::before{
  content:"−"; }

.bp3-icon-mobile-phone::before{
  content:""; }

.bp3-icon-mobile-video::before{
  content:""; }

.bp3-icon-moon::before{
  content:""; }

.bp3-icon-more::before{
  content:""; }

.bp3-icon-mountain::before{
  content:""; }

.bp3-icon-move::before{
  content:""; }

.bp3-icon-mugshot::before{
  content:""; }

.bp3-icon-multi-select::before{
  content:""; }

.bp3-icon-music::before{
  content:""; }

.bp3-icon-new-drawing::before{
  content:""; }

.bp3-icon-new-grid-item::before{
  content:""; }

.bp3-icon-new-layer::before{
  content:""; }

.bp3-icon-new-layers::before{
  content:""; }

.bp3-icon-new-link::before{
  content:""; }

.bp3-icon-new-object::before{
  content:""; }

.bp3-icon-new-person::before{
  content:""; }

.bp3-icon-new-prescription::before{
  content:""; }

.bp3-icon-new-text-box::before{
  content:""; }

.bp3-icon-ninja::before{
  content:""; }

.bp3-icon-not-equal-to::before{
  content:""; }

.bp3-icon-notifications::before{
  content:""; }

.bp3-icon-notifications-updated::before{
  content:""; }

.bp3-icon-numbered-list::before{
  content:""; }

.bp3-icon-numerical::before{
  content:""; }

.bp3-icon-office::before{
  content:""; }

.bp3-icon-offline::before{
  content:""; }

.bp3-icon-oil-field::before{
  content:""; }

.bp3-icon-one-column::before{
  content:""; }

.bp3-icon-outdated::before{
  content:""; }

.bp3-icon-page-layout::before{
  content:""; }

.bp3-icon-panel-stats::before{
  content:""; }

.bp3-icon-panel-table::before{
  content:""; }

.bp3-icon-paperclip::before{
  content:""; }

.bp3-icon-paragraph::before{
  content:""; }

.bp3-icon-path::before{
  content:""; }

.bp3-icon-path-search::before{
  content:""; }

.bp3-icon-pause::before{
  content:""; }

.bp3-icon-people::before{
  content:""; }

.bp3-icon-percentage::before{
  content:""; }

.bp3-icon-person::before{
  content:""; }

.bp3-icon-phone::before{
  content:"☎"; }

.bp3-icon-pie-chart::before{
  content:""; }

.bp3-icon-pin::before{
  content:""; }

.bp3-icon-pivot::before{
  content:""; }

.bp3-icon-pivot-table::before{
  content:""; }

.bp3-icon-play::before{
  content:""; }

.bp3-icon-plus::before{
  content:"+"; }

.bp3-icon-polygon-filter::before{
  content:""; }

.bp3-icon-power::before{
  content:""; }

.bp3-icon-predictive-analysis::before{
  content:""; }

.bp3-icon-prescription::before{
  content:""; }

.bp3-icon-presentation::before{
  content:""; }

.bp3-icon-print::before{
  content:"⎙"; }

.bp3-icon-projects::before{
  content:""; }

.bp3-icon-properties::before{
  content:""; }

.bp3-icon-property::before{
  content:""; }

.bp3-icon-publish-function::before{
  content:""; }

.bp3-icon-pulse::before{
  content:""; }

.bp3-icon-random::before{
  content:""; }

.bp3-icon-record::before{
  content:""; }

.bp3-icon-redo::before{
  content:""; }

.bp3-icon-refresh::before{
  content:""; }

.bp3-icon-regression-chart::before{
  content:""; }

.bp3-icon-remove::before{
  content:""; }

.bp3-icon-remove-column::before{
  content:""; }

.bp3-icon-remove-column-left::before{
  content:""; }

.bp3-icon-remove-column-right::before{
  content:""; }

.bp3-icon-remove-row-bottom::before{
  content:""; }

.bp3-icon-remove-row-top::before{
  content:""; }

.bp3-icon-repeat::before{
  content:""; }

.bp3-icon-reset::before{
  content:""; }

.bp3-icon-resolve::before{
  content:""; }

.bp3-icon-rig::before{
  content:""; }

.bp3-icon-right-join::before{
  content:""; }

.bp3-icon-ring::before{
  content:""; }

.bp3-icon-rotate-document::before{
  content:""; }

.bp3-icon-rotate-page::before{
  content:""; }

.bp3-icon-satellite::before{
  content:""; }

.bp3-icon-saved::before{
  content:""; }

.bp3-icon-scatter-plot::before{
  content:""; }

.bp3-icon-search::before{
  content:""; }

.bp3-icon-search-around::before{
  content:""; }

.bp3-icon-search-template::before{
  content:""; }

.bp3-icon-search-text::before{
  content:""; }

.bp3-icon-segmented-control::before{
  content:""; }

.bp3-icon-select::before{
  content:""; }

.bp3-icon-selection::before{
  content:"⦿"; }

.bp3-icon-send-to::before{
  content:""; }

.bp3-icon-send-to-graph::before{
  content:""; }

.bp3-icon-send-to-map::before{
  content:""; }

.bp3-icon-series-add::before{
  content:""; }

.bp3-icon-series-configuration::before{
  content:""; }

.bp3-icon-series-derived::before{
  content:""; }

.bp3-icon-series-filtered::before{
  content:""; }

.bp3-icon-series-search::before{
  content:""; }

.bp3-icon-settings::before{
  content:""; }

.bp3-icon-share::before{
  content:""; }

.bp3-icon-shield::before{
  content:""; }

.bp3-icon-shop::before{
  content:""; }

.bp3-icon-shopping-cart::before{
  content:""; }

.bp3-icon-signal-search::before{
  content:""; }

.bp3-icon-sim-card::before{
  content:""; }

.bp3-icon-slash::before{
  content:""; }

.bp3-icon-small-cross::before{
  content:""; }

.bp3-icon-small-minus::before{
  content:""; }

.bp3-icon-small-plus::before{
  content:""; }

.bp3-icon-small-tick::before{
  content:""; }

.bp3-icon-snowflake::before{
  content:""; }

.bp3-icon-social-media::before{
  content:""; }

.bp3-icon-sort::before{
  content:""; }

.bp3-icon-sort-alphabetical::before{
  content:""; }

.bp3-icon-sort-alphabetical-desc::before{
  content:""; }

.bp3-icon-sort-asc::before{
  content:""; }

.bp3-icon-sort-desc::before{
  content:""; }

.bp3-icon-sort-numerical::before{
  content:""; }

.bp3-icon-sort-numerical-desc::before{
  content:""; }

.bp3-icon-split-columns::before{
  content:""; }

.bp3-icon-square::before{
  content:""; }

.bp3-icon-stacked-chart::before{
  content:""; }

.bp3-icon-star::before{
  content:"★"; }

.bp3-icon-star-empty::before{
  content:"☆"; }

.bp3-icon-step-backward::before{
  content:""; }

.bp3-icon-step-chart::before{
  content:""; }

.bp3-icon-step-forward::before{
  content:""; }

.bp3-icon-stop::before{
  content:""; }

.bp3-icon-stopwatch::before{
  content:""; }

.bp3-icon-strikethrough::before{
  content:""; }

.bp3-icon-style::before{
  content:""; }

.bp3-icon-swap-horizontal::before{
  content:""; }

.bp3-icon-swap-vertical::before{
  content:""; }

.bp3-icon-symbol-circle::before{
  content:""; }

.bp3-icon-symbol-cross::before{
  content:""; }

.bp3-icon-symbol-diamond::before{
  content:""; }

.bp3-icon-symbol-square::before{
  content:""; }

.bp3-icon-symbol-triangle-down::before{
  content:""; }

.bp3-icon-symbol-triangle-up::before{
  content:""; }

.bp3-icon-tag::before{
  content:""; }

.bp3-icon-take-action::before{
  content:""; }

.bp3-icon-taxi::before{
  content:""; }

.bp3-icon-text-highlight::before{
  content:""; }

.bp3-icon-th::before{
  content:""; }

.bp3-icon-th-derived::before{
  content:""; }

.bp3-icon-th-disconnect::before{
  content:""; }

.bp3-icon-th-filtered::before{
  content:""; }

.bp3-icon-th-list::before{
  content:""; }

.bp3-icon-thumbs-down::before{
  content:""; }

.bp3-icon-thumbs-up::before{
  content:""; }

.bp3-icon-tick::before{
  content:"✓"; }

.bp3-icon-tick-circle::before{
  content:""; }

.bp3-icon-time::before{
  content:"⏲"; }

.bp3-icon-timeline-area-chart::before{
  content:""; }

.bp3-icon-timeline-bar-chart::before{
  content:""; }

.bp3-icon-timeline-events::before{
  content:""; }

.bp3-icon-timeline-line-chart::before{
  content:""; }

.bp3-icon-tint::before{
  content:""; }

.bp3-icon-torch::before{
  content:""; }

.bp3-icon-tractor::before{
  content:""; }

.bp3-icon-train::before{
  content:""; }

.bp3-icon-translate::before{
  content:""; }

.bp3-icon-trash::before{
  content:""; }

.bp3-icon-tree::before{
  content:""; }

.bp3-icon-trending-down::before{
  content:""; }

.bp3-icon-trending-up::before{
  content:""; }

.bp3-icon-truck::before{
  content:""; }

.bp3-icon-two-columns::before{
  content:""; }

.bp3-icon-unarchive::before{
  content:""; }

.bp3-icon-underline::before{
  content:"⎁"; }

.bp3-icon-undo::before{
  content:"⎌"; }

.bp3-icon-ungroup-objects::before{
  content:""; }

.bp3-icon-unknown-vehicle::before{
  content:""; }

.bp3-icon-unlock::before{
  content:""; }

.bp3-icon-unpin::before{
  content:""; }

.bp3-icon-unresolve::before{
  content:""; }

.bp3-icon-updated::before{
  content:""; }

.bp3-icon-upload::before{
  content:""; }

.bp3-icon-user::before{
  content:""; }

.bp3-icon-variable::before{
  content:""; }

.bp3-icon-vertical-bar-chart-asc::before{
  content:""; }

.bp3-icon-vertical-bar-chart-desc::before{
  content:""; }

.bp3-icon-vertical-distribution::before{
  content:""; }

.bp3-icon-video::before{
  content:""; }

.bp3-icon-volume-down::before{
  content:""; }

.bp3-icon-volume-off::before{
  content:""; }

.bp3-icon-volume-up::before{
  content:""; }

.bp3-icon-walk::before{
  content:""; }

.bp3-icon-warning-sign::before{
  content:""; }

.bp3-icon-waterfall-chart::before{
  content:""; }

.bp3-icon-widget::before{
  content:""; }

.bp3-icon-widget-button::before{
  content:""; }

.bp3-icon-widget-footer::before{
  content:""; }

.bp3-icon-widget-header::before{
  content:""; }

.bp3-icon-wrench::before{
  content:""; }

.bp3-icon-zoom-in::before{
  content:""; }

.bp3-icon-zoom-out::before{
  content:""; }

.bp3-icon-zoom-to-fit::before{
  content:""; }
.bp3-submenu > .bp3-popover-wrapper{
  display:block; }

.bp3-submenu .bp3-popover-target{
  display:block; }
  .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{ }

.bp3-submenu.bp3-popover{
  -webkit-box-shadow:none;
          box-shadow:none;
  padding:0 5px; }
  .bp3-submenu.bp3-popover > .bp3-popover-content{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-submenu.bp3-popover, .bp3-submenu.bp3-popover.bp3-dark{
    -webkit-box-shadow:none;
            box-shadow:none; }
    .bp3-dark .bp3-submenu.bp3-popover > .bp3-popover-content, .bp3-submenu.bp3-popover.bp3-dark > .bp3-popover-content{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
.bp3-menu{
  background:#ffffff;
  border-radius:3px;
  color:#182026;
  list-style:none;
  margin:0;
  min-width:180px;
  padding:5px;
  text-align:left; }

.bp3-menu-divider{
  border-top:1px solid rgba(16, 22, 26, 0.15);
  display:block;
  margin:5px; }
  .bp3-dark .bp3-menu-divider{
    border-top-color:rgba(255, 255, 255, 0.15); }

.bp3-menu-item{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  border-radius:2px;
  color:inherit;
  line-height:20px;
  padding:5px 7px;
  text-decoration:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-menu-item > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-menu-item > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-menu-item::before,
  .bp3-menu-item > *{
    margin-right:7px; }
  .bp3-menu-item:empty::before,
  .bp3-menu-item > :last-child{
    margin-right:0; }
  .bp3-menu-item > .bp3-fill{
    word-break:break-word; }
  .bp3-menu-item:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
    background-color:rgba(167, 182, 194, 0.3);
    cursor:pointer;
    text-decoration:none; }
  .bp3-menu-item.bp3-disabled{
    background-color:inherit;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
  .bp3-dark .bp3-menu-item{
    color:inherit; }
    .bp3-dark .bp3-menu-item:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
      background-color:rgba(138, 155, 168, 0.15);
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-disabled{
      background-color:inherit;
      color:rgba(167, 182, 194, 0.6); }
  .bp3-menu-item.bp3-intent-primary{
    color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-primary::before, .bp3-menu-item.bp3-intent-primary::after,
    .bp3-menu-item.bp3-intent-primary .bp3-menu-item-label{
      color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-menu-item.bp3-intent-primary.bp3-active{
      background-color:#137cbd; }
    .bp3-menu-item.bp3-intent-primary:active{
      background-color:#106ba3; }
    .bp3-menu-item.bp3-intent-primary:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-menu-item.bp3-intent-primary:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-menu-item.bp3-intent-primary:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-primary:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-primary:active, .bp3-menu-item.bp3-intent-primary:active::before, .bp3-menu-item.bp3-intent-primary:active::after,
    .bp3-menu-item.bp3-intent-primary:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-primary.bp3-active, .bp3-menu-item.bp3-intent-primary.bp3-active::before, .bp3-menu-item.bp3-intent-primary.bp3-active::after,
    .bp3-menu-item.bp3-intent-primary.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-success{
    color:#0d8050; }
    .bp3-menu-item.bp3-intent-success .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-success::before, .bp3-menu-item.bp3-intent-success::after,
    .bp3-menu-item.bp3-intent-success .bp3-menu-item-label{
      color:#0d8050; }
    .bp3-menu-item.bp3-intent-success:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-menu-item.bp3-intent-success.bp3-active{
      background-color:#0f9960; }
    .bp3-menu-item.bp3-intent-success:active{
      background-color:#0d8050; }
    .bp3-menu-item.bp3-intent-success:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-menu-item.bp3-intent-success:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-menu-item.bp3-intent-success:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-success:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-success:active, .bp3-menu-item.bp3-intent-success:active::before, .bp3-menu-item.bp3-intent-success:active::after,
    .bp3-menu-item.bp3-intent-success:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-success.bp3-active, .bp3-menu-item.bp3-intent-success.bp3-active::before, .bp3-menu-item.bp3-intent-success.bp3-active::after,
    .bp3-menu-item.bp3-intent-success.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-warning{
    color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-warning::before, .bp3-menu-item.bp3-intent-warning::after,
    .bp3-menu-item.bp3-intent-warning .bp3-menu-item-label{
      color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-menu-item.bp3-intent-warning.bp3-active{
      background-color:#d9822b; }
    .bp3-menu-item.bp3-intent-warning:active{
      background-color:#bf7326; }
    .bp3-menu-item.bp3-intent-warning:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-menu-item.bp3-intent-warning:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-menu-item.bp3-intent-warning:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-warning:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-warning:active, .bp3-menu-item.bp3-intent-warning:active::before, .bp3-menu-item.bp3-intent-warning:active::after,
    .bp3-menu-item.bp3-intent-warning:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-warning.bp3-active, .bp3-menu-item.bp3-intent-warning.bp3-active::before, .bp3-menu-item.bp3-intent-warning.bp3-active::after,
    .bp3-menu-item.bp3-intent-warning.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item.bp3-intent-danger{
    color:#c23030; }
    .bp3-menu-item.bp3-intent-danger .bp3-icon{
      color:inherit; }
    .bp3-menu-item.bp3-intent-danger::before, .bp3-menu-item.bp3-intent-danger::after,
    .bp3-menu-item.bp3-intent-danger .bp3-menu-item-label{
      color:#c23030; }
    .bp3-menu-item.bp3-intent-danger:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-menu-item.bp3-intent-danger.bp3-active{
      background-color:#db3737; }
    .bp3-menu-item.bp3-intent-danger:active{
      background-color:#c23030; }
    .bp3-menu-item.bp3-intent-danger:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-menu-item.bp3-intent-danger:hover::before, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-menu-item.bp3-intent-danger:hover::after, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after,
    .bp3-menu-item.bp3-intent-danger:hover .bp3-menu-item-label,
    .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label, .bp3-menu-item.bp3-intent-danger:active, .bp3-menu-item.bp3-intent-danger:active::before, .bp3-menu-item.bp3-intent-danger:active::after,
    .bp3-menu-item.bp3-intent-danger:active .bp3-menu-item-label, .bp3-menu-item.bp3-intent-danger.bp3-active, .bp3-menu-item.bp3-intent-danger.bp3-active::before, .bp3-menu-item.bp3-intent-danger.bp3-active::after,
    .bp3-menu-item.bp3-intent-danger.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-menu-item::before{
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-style:normal;
    font-weight:400;
    line-height:1;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    margin-right:7px; }
  .bp3-menu-item::before,
  .bp3-menu-item > .bp3-icon{
    color:#5c7080;
    margin-top:2px; }
  .bp3-menu-item .bp3-menu-item-label{
    color:#5c7080; }
  .bp3-menu-item:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
    color:inherit; }
  .bp3-menu-item.bp3-active, .bp3-menu-item:active{
    background-color:rgba(115, 134, 148, 0.3); }
  .bp3-menu-item.bp3-disabled{
    background-color:inherit !important;
    color:rgba(92, 112, 128, 0.6) !important;
    cursor:not-allowed !important;
    outline:none !important; }
    .bp3-menu-item.bp3-disabled::before,
    .bp3-menu-item.bp3-disabled > .bp3-icon,
    .bp3-menu-item.bp3-disabled .bp3-menu-item-label{
      color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-large .bp3-menu-item{
    font-size:16px;
    line-height:22px;
    padding:9px 7px; }
    .bp3-large .bp3-menu-item .bp3-icon{
      margin-top:3px; }
    .bp3-large .bp3-menu-item::before{
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-style:normal;
      font-weight:400;
      line-height:1;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased;
      margin-right:10px;
      margin-top:1px; }

button.bp3-menu-item{
  background:none;
  border:none;
  text-align:left;
  width:100%; }
.bp3-menu-header{
  border-top:1px solid rgba(16, 22, 26, 0.15);
  display:block;
  margin:5px;
  cursor:default;
  padding-left:2px; }
  .bp3-dark .bp3-menu-header{
    border-top-color:rgba(255, 255, 255, 0.15); }
  .bp3-menu-header:first-of-type{
    border-top:none; }
  .bp3-menu-header > h6{
    color:#182026;
    font-weight:600;
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    line-height:17px;
    margin:0;
    padding:10px 7px 0 1px; }
    .bp3-dark .bp3-menu-header > h6{
      color:#f5f8fa; }
  .bp3-menu-header:first-of-type > h6{
    padding-top:0; }
  .bp3-large .bp3-menu-header > h6{
    font-size:18px;
    padding-bottom:5px;
    padding-top:15px; }
  .bp3-large .bp3-menu-header:first-of-type > h6{
    padding-top:0; }

.bp3-dark .bp3-menu{
  background:#30404d;
  color:#f5f8fa; }

.bp3-dark .bp3-menu-item{ }
  .bp3-dark .bp3-menu-item.bp3-intent-primary{
    color:#48aff0; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary::before, .bp3-dark .bp3-menu-item.bp3-intent-primary::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary .bp3-menu-item-label{
      color:#48aff0; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active{
      background-color:#137cbd; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary:active{
      background-color:#106ba3; }
    .bp3-dark .bp3-menu-item.bp3-intent-primary:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-primary:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-primary:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-primary.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-primary:active, .bp3-dark .bp3-menu-item.bp3-intent-primary:active::before, .bp3-dark .bp3-menu-item.bp3-intent-primary:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-primary.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item.bp3-intent-success{
    color:#3dcc91; }
    .bp3-dark .bp3-menu-item.bp3-intent-success .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-success::before, .bp3-dark .bp3-menu-item.bp3-intent-success::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success .bp3-menu-item-label{
      color:#3dcc91; }
    .bp3-dark .bp3-menu-item.bp3-intent-success:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active{
      background-color:#0f9960; }
    .bp3-dark .bp3-menu-item.bp3-intent-success:active{
      background-color:#0d8050; }
    .bp3-dark .bp3-menu-item.bp3-intent-success:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-success:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-success:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-success.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-success:active, .bp3-dark .bp3-menu-item.bp3-intent-success:active::before, .bp3-dark .bp3-menu-item.bp3-intent-success:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-success.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item.bp3-intent-warning{
    color:#ffb366; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning::before, .bp3-dark .bp3-menu-item.bp3-intent-warning::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning .bp3-menu-item-label{
      color:#ffb366; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active{
      background-color:#d9822b; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning:active{
      background-color:#bf7326; }
    .bp3-dark .bp3-menu-item.bp3-intent-warning:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-warning:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-warning:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-warning.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-warning:active, .bp3-dark .bp3-menu-item.bp3-intent-warning:active::before, .bp3-dark .bp3-menu-item.bp3-intent-warning:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-warning.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item.bp3-intent-danger{
    color:#ff7373; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger .bp3-icon{
      color:inherit; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger::before, .bp3-dark .bp3-menu-item.bp3-intent-danger::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger .bp3-menu-item-label{
      color:#ff7373; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active{
      background-color:#db3737; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger:active{
      background-color:#c23030; }
    .bp3-dark .bp3-menu-item.bp3-intent-danger:hover, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item, .bp3-dark .bp3-menu-item.bp3-intent-danger:hover::before, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::before, .bp3-dark .bp3-menu-item.bp3-intent-danger:hover::after, .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after, .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger:hover .bp3-menu-item-label,
    .bp3-dark .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label,
    .bp3-submenu .bp3-dark .bp3-popover-target.bp3-popover-open > .bp3-intent-danger.bp3-menu-item .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-danger:active, .bp3-dark .bp3-menu-item.bp3-intent-danger:active::before, .bp3-dark .bp3-menu-item.bp3-intent-danger:active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger:active .bp3-menu-item-label, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active::before, .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active::after,
    .bp3-dark .bp3-menu-item.bp3-intent-danger.bp3-active .bp3-menu-item-label{
      color:#ffffff; }
  .bp3-dark .bp3-menu-item::before,
  .bp3-dark .bp3-menu-item > .bp3-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-menu-item .bp3-menu-item-label{
    color:#a7b6c2; }
  .bp3-dark .bp3-menu-item.bp3-active, .bp3-dark .bp3-menu-item:active{
    background-color:rgba(138, 155, 168, 0.3); }
  .bp3-dark .bp3-menu-item.bp3-disabled{
    color:rgba(167, 182, 194, 0.6) !important; }
    .bp3-dark .bp3-menu-item.bp3-disabled::before,
    .bp3-dark .bp3-menu-item.bp3-disabled > .bp3-icon,
    .bp3-dark .bp3-menu-item.bp3-disabled .bp3-menu-item-label{
      color:rgba(167, 182, 194, 0.6) !important; }

.bp3-dark .bp3-menu-divider,
.bp3-dark .bp3-menu-header{
  border-color:rgba(255, 255, 255, 0.15); }

.bp3-dark .bp3-menu-header > h6{
  color:#f5f8fa; }

.bp3-label .bp3-menu{
  margin-top:5px; }
.bp3-navbar{
  background-color:#ffffff;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  height:50px;
  padding:0 15px;
  position:relative;
  width:100%;
  z-index:10; }
  .bp3-navbar.bp3-dark,
  .bp3-dark .bp3-navbar{
    background-color:#394b59; }
  .bp3-navbar.bp3-dark{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-navbar{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4); }
  .bp3-navbar.bp3-fixed-top{
    left:0;
    position:fixed;
    right:0;
    top:0; }

.bp3-navbar-heading{
  font-size:16px;
  margin-right:15px; }

.bp3-navbar-group{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  height:50px; }
  .bp3-navbar-group.bp3-align-left{
    float:left; }
  .bp3-navbar-group.bp3-align-right{
    float:right; }

.bp3-navbar-divider{
  border-left:1px solid rgba(16, 22, 26, 0.15);
  height:20px;
  margin:0 10px; }
  .bp3-dark .bp3-navbar-divider{
    border-left-color:rgba(255, 255, 255, 0.15); }
.bp3-non-ideal-state{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  height:100%;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  text-align:center;
  width:100%; }
  .bp3-non-ideal-state > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-non-ideal-state > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-non-ideal-state::before,
  .bp3-non-ideal-state > *{
    margin-bottom:20px; }
  .bp3-non-ideal-state:empty::before,
  .bp3-non-ideal-state > :last-child{
    margin-bottom:0; }
  .bp3-non-ideal-state > *{
    max-width:400px; }

.bp3-non-ideal-state-visual{
  color:rgba(92, 112, 128, 0.6);
  font-size:60px; }
  .bp3-dark .bp3-non-ideal-state-visual{
    color:rgba(167, 182, 194, 0.6); }

.bp3-overflow-list{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-wrap:nowrap;
      flex-wrap:nowrap;
  min-width:0; }

.bp3-overflow-list-spacer{
  -ms-flex-negative:1;
      flex-shrink:1;
  width:1px; }

body.bp3-overlay-open{
  overflow:hidden; }

.bp3-overlay{
  bottom:0;
  left:0;
  position:static;
  right:0;
  top:0;
  z-index:20; }
  .bp3-overlay:not(.bp3-overlay-open){
    pointer-events:none; }
  .bp3-overlay.bp3-overlay-container{
    overflow:hidden;
    position:fixed; }
    .bp3-overlay.bp3-overlay-container.bp3-overlay-inline{
      position:absolute; }
  .bp3-overlay.bp3-overlay-scroll-container{
    overflow:auto;
    position:fixed; }
    .bp3-overlay.bp3-overlay-scroll-container.bp3-overlay-inline{
      position:absolute; }
  .bp3-overlay.bp3-overlay-inline{
    display:inline;
    overflow:visible; }

.bp3-overlay-content{
  position:fixed;
  z-index:20; }
  .bp3-overlay-inline .bp3-overlay-content,
  .bp3-overlay-scroll-container .bp3-overlay-content{
    position:absolute; }

.bp3-overlay-backdrop{
  bottom:0;
  left:0;
  position:fixed;
  right:0;
  top:0;
  opacity:1;
  background-color:rgba(16, 22, 26, 0.7);
  overflow:auto;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none;
  z-index:20; }
  .bp3-overlay-backdrop.bp3-overlay-enter, .bp3-overlay-backdrop.bp3-overlay-appear{
    opacity:0; }
  .bp3-overlay-backdrop.bp3-overlay-enter-active, .bp3-overlay-backdrop.bp3-overlay-appear-active{
    opacity:1;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-overlay-backdrop.bp3-overlay-exit{
    opacity:1; }
  .bp3-overlay-backdrop.bp3-overlay-exit-active{
    opacity:0;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-overlay-backdrop:focus{
    outline:none; }
  .bp3-overlay-inline .bp3-overlay-backdrop{
    position:absolute; }
.bp3-panel-stack{
  overflow:hidden;
  position:relative; }

.bp3-panel-stack-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-shadow:0 1px rgba(16, 22, 26, 0.15);
          box-shadow:0 1px rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-negative:0;
      flex-shrink:0;
  height:30px;
  z-index:1; }
  .bp3-dark .bp3-panel-stack-header{
    -webkit-box-shadow:0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 1px rgba(255, 255, 255, 0.15); }
  .bp3-panel-stack-header > span{
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1;
            flex:1; }
  .bp3-panel-stack-header .bp3-heading{
    margin:0 5px; }

.bp3-button.bp3-panel-stack-header-back{
  margin-left:5px;
  padding-left:0;
  white-space:nowrap; }
  .bp3-button.bp3-panel-stack-header-back .bp3-icon{
    margin:0 2px; }

.bp3-panel-stack-view{
  bottom:0;
  left:0;
  position:absolute;
  right:0;
  top:0;
  background-color:#ffffff;
  border-right:1px solid rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin-right:-1px;
  overflow-y:auto;
  z-index:1; }
  .bp3-dark .bp3-panel-stack-view{
    background-color:#30404d; }
  .bp3-panel-stack-view:nth-last-child(n + 4){
    display:none; }

.bp3-panel-stack-push .bp3-panel-stack-enter, .bp3-panel-stack-push .bp3-panel-stack-appear{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0; }

.bp3-panel-stack-push .bp3-panel-stack-enter-active, .bp3-panel-stack-push .bp3-panel-stack-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack-push .bp3-panel-stack-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack-push .bp3-panel-stack-exit-active{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack-pop .bp3-panel-stack-enter, .bp3-panel-stack-pop .bp3-panel-stack-appear{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0; }

.bp3-panel-stack-pop .bp3-panel-stack-enter-active, .bp3-panel-stack-pop .bp3-panel-stack-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack-pop .bp3-panel-stack-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack-pop .bp3-panel-stack-exit-active{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }
.bp3-panel-stack2{
  overflow:hidden;
  position:relative; }

.bp3-panel-stack2-header{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-shadow:0 1px rgba(16, 22, 26, 0.15);
          box-shadow:0 1px rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-negative:0;
      flex-shrink:0;
  height:30px;
  z-index:1; }
  .bp3-dark .bp3-panel-stack2-header{
    -webkit-box-shadow:0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 1px rgba(255, 255, 255, 0.15); }
  .bp3-panel-stack2-header > span{
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1;
            flex:1; }
  .bp3-panel-stack2-header .bp3-heading{
    margin:0 5px; }

.bp3-button.bp3-panel-stack2-header-back{
  margin-left:5px;
  padding-left:0;
  white-space:nowrap; }
  .bp3-button.bp3-panel-stack2-header-back .bp3-icon{
    margin:0 2px; }

.bp3-panel-stack2-view{
  bottom:0;
  left:0;
  position:absolute;
  right:0;
  top:0;
  background-color:#ffffff;
  border-right:1px solid rgba(16, 22, 26, 0.15);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin-right:-1px;
  overflow-y:auto;
  z-index:1; }
  .bp3-dark .bp3-panel-stack2-view{
    background-color:#30404d; }
  .bp3-panel-stack2-view:nth-last-child(n + 4){
    display:none; }

.bp3-panel-stack2-push .bp3-panel-stack2-enter, .bp3-panel-stack2-push .bp3-panel-stack2-appear{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0; }

.bp3-panel-stack2-push .bp3-panel-stack2-enter-active, .bp3-panel-stack2-push .bp3-panel-stack2-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack2-push .bp3-panel-stack2-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack2-push .bp3-panel-stack2-exit-active{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack2-pop .bp3-panel-stack2-enter, .bp3-panel-stack2-pop .bp3-panel-stack2-appear{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0; }

.bp3-panel-stack2-pop .bp3-panel-stack2-enter-active, .bp3-panel-stack2-pop .bp3-panel-stack2-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }

.bp3-panel-stack2-pop .bp3-panel-stack2-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack2-pop .bp3-panel-stack2-exit-active{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0;
  -webkit-transition-delay:0;
          transition-delay:0;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease; }
.bp3-popover{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  -webkit-transform:scale(1);
          transform:scale(1);
  border-radius:3px;
  display:inline-block;
  z-index:20; }
  .bp3-popover .bp3-popover-arrow{
    height:30px;
    position:absolute;
    width:30px; }
    .bp3-popover .bp3-popover-arrow::before{
      height:20px;
      margin:5px;
      width:20px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover{
    margin-bottom:17px;
    margin-top:-17px; }
    .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow{
      bottom:-11px; }
      .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(-90deg);
                transform:rotate(-90deg); }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover{
    margin-left:17px; }
    .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow{
      left:-11px; }
      .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(0);
                transform:rotate(0); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover{
    margin-top:17px; }
    .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow{
      top:-11px; }
      .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(90deg);
                transform:rotate(90deg); }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover{
    margin-left:-17px;
    margin-right:17px; }
    .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow{
      right:-11px; }
      .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow svg{
        -webkit-transform:rotate(180deg);
                transform:rotate(180deg); }
  .bp3-tether-element-attached-middle > .bp3-popover > .bp3-popover-arrow{
    top:50%;
    -webkit-transform:translateY(-50%);
            transform:translateY(-50%); }
  .bp3-tether-element-attached-center > .bp3-popover > .bp3-popover-arrow{
    right:50%;
    -webkit-transform:translateX(50%);
            transform:translateX(50%); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-top > .bp3-popover > .bp3-popover-arrow{
    top:-0.3934px; }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-right > .bp3-popover > .bp3-popover-arrow{
    right:-0.3934px; }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-left > .bp3-popover > .bp3-popover-arrow{
    left:-0.3934px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-bottom > .bp3-popover > .bp3-popover-arrow{
    bottom:-0.3934px; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:top left;
            transform-origin:top left; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:top center;
            transform-origin:top center; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:top right;
            transform-origin:top right; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:center left;
            transform-origin:center left; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:center center;
            transform-origin:center center; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:center right;
            transform-origin:center right; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-left > .bp3-popover{
    -webkit-transform-origin:bottom left;
            transform-origin:bottom left; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-center > .bp3-popover{
    -webkit-transform-origin:bottom center;
            transform-origin:bottom center; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-right > .bp3-popover{
    -webkit-transform-origin:bottom right;
            transform-origin:bottom right; }
  .bp3-popover .bp3-popover-content{
    background:#ffffff;
    color:inherit; }
  .bp3-popover .bp3-popover-arrow::before{
    -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2);
            box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2); }
  .bp3-popover .bp3-popover-arrow-border{
    fill:#10161a;
    fill-opacity:0.1; }
  .bp3-popover .bp3-popover-arrow-fill{
    fill:#ffffff; }
  .bp3-popover-enter > .bp3-popover, .bp3-popover-appear > .bp3-popover{
    -webkit-transform:scale(0.3);
            transform:scale(0.3); }
  .bp3-popover-enter-active > .bp3-popover, .bp3-popover-appear-active > .bp3-popover{
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-popover-exit > .bp3-popover{
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-popover-exit-active > .bp3-popover{
    -webkit-transform:scale(0.3);
            transform:scale(0.3);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-popover .bp3-popover-content{
    border-radius:3px;
    position:relative; }
  .bp3-popover.bp3-popover-content-sizing .bp3-popover-content{
    max-width:350px;
    padding:20px; }
  .bp3-popover-target + .bp3-overlay .bp3-popover.bp3-popover-content-sizing{
    width:350px; }
  .bp3-popover.bp3-minimal{
    margin:0 !important; }
    .bp3-popover.bp3-minimal .bp3-popover-arrow{
      display:none; }
    .bp3-popover.bp3-minimal.bp3-popover{
      -webkit-transform:scale(1);
              transform:scale(1); }
      .bp3-popover-enter > .bp3-popover.bp3-minimal.bp3-popover, .bp3-popover-appear > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1); }
      .bp3-popover-enter-active > .bp3-popover.bp3-minimal.bp3-popover, .bp3-popover-appear-active > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1);
        -webkit-transition-delay:0;
                transition-delay:0;
        -webkit-transition-duration:100ms;
                transition-duration:100ms;
        -webkit-transition-property:-webkit-transform;
        transition-property:-webkit-transform;
        transition-property:transform;
        transition-property:transform, -webkit-transform;
        -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
                transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
      .bp3-popover-exit > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1); }
      .bp3-popover-exit-active > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1);
        -webkit-transition-delay:0;
                transition-delay:0;
        -webkit-transition-duration:100ms;
                transition-duration:100ms;
        -webkit-transition-property:-webkit-transform;
        transition-property:-webkit-transform;
        transition-property:transform;
        transition-property:transform, -webkit-transform;
        -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
                transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-popover.bp3-dark,
  .bp3-dark .bp3-popover{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-popover.bp3-dark .bp3-popover-content,
    .bp3-dark .bp3-popover .bp3-popover-content{
      background:#30404d;
      color:inherit; }
    .bp3-popover.bp3-dark .bp3-popover-arrow::before,
    .bp3-dark .bp3-popover .bp3-popover-arrow::before{
      -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4);
              box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4); }
    .bp3-popover.bp3-dark .bp3-popover-arrow-border,
    .bp3-dark .bp3-popover .bp3-popover-arrow-border{
      fill:#10161a;
      fill-opacity:0.2; }
    .bp3-popover.bp3-dark .bp3-popover-arrow-fill,
    .bp3-dark .bp3-popover .bp3-popover-arrow-fill{
      fill:#30404d; }

.bp3-popover-arrow::before{
  border-radius:2px;
  content:"";
  display:block;
  position:absolute;
  -webkit-transform:rotate(45deg);
          transform:rotate(45deg); }

.bp3-tether-pinned .bp3-popover-arrow{
  display:none; }

.bp3-popover-backdrop{
  background:rgba(255, 255, 255, 0); }

.bp3-transition-container{
  opacity:1;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  z-index:20; }
  .bp3-transition-container.bp3-popover-enter, .bp3-transition-container.bp3-popover-appear{
    opacity:0; }
  .bp3-transition-container.bp3-popover-enter-active, .bp3-transition-container.bp3-popover-appear-active{
    opacity:1;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-transition-container.bp3-popover-exit{
    opacity:1; }
  .bp3-transition-container.bp3-popover-exit-active{
    opacity:0;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-transition-container:focus{
    outline:none; }
  .bp3-transition-container.bp3-popover-leave .bp3-popover-content{
    pointer-events:none; }
  .bp3-transition-container[data-x-out-of-boundaries]{
    display:none; }

span.bp3-popover-target{
  display:inline-block; }

.bp3-popover-wrapper.bp3-fill{
  width:100%; }

.bp3-portal{
  left:0;
  position:absolute;
  right:0;
  top:0; }
@-webkit-keyframes linear-progress-bar-stripes{
  from{
    background-position:0 0; }
  to{
    background-position:30px 0; } }
@keyframes linear-progress-bar-stripes{
  from{
    background-position:0 0; }
  to{
    background-position:30px 0; } }

.bp3-progress-bar{
  background:rgba(92, 112, 128, 0.2);
  border-radius:40px;
  display:block;
  height:8px;
  overflow:hidden;
  position:relative;
  width:100%; }
  .bp3-progress-bar .bp3-progress-meter{
    background:linear-gradient(-45deg, rgba(255, 255, 255, 0.2) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.2) 50%, rgba(255, 255, 255, 0.2) 75%, transparent 75%);
    background-color:rgba(92, 112, 128, 0.8);
    background-size:30px 30px;
    border-radius:40px;
    height:100%;
    position:absolute;
    -webkit-transition:width 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:width 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    width:100%; }
  .bp3-progress-bar:not(.bp3-no-animation):not(.bp3-no-stripes) .bp3-progress-meter{
    animation:linear-progress-bar-stripes 300ms linear infinite reverse; }
  .bp3-progress-bar.bp3-no-stripes .bp3-progress-meter{
    background-image:none; }

.bp3-dark .bp3-progress-bar{
  background:rgba(16, 22, 26, 0.5); }
  .bp3-dark .bp3-progress-bar .bp3-progress-meter{
    background-color:#8a9ba8; }

.bp3-progress-bar.bp3-intent-primary .bp3-progress-meter{
  background-color:#137cbd; }

.bp3-progress-bar.bp3-intent-success .bp3-progress-meter{
  background-color:#0f9960; }

.bp3-progress-bar.bp3-intent-warning .bp3-progress-meter{
  background-color:#d9822b; }

.bp3-progress-bar.bp3-intent-danger .bp3-progress-meter{
  background-color:#db3737; }
@-webkit-keyframes skeleton-glow{
  from{
    background:rgba(206, 217, 224, 0.2);
    border-color:rgba(206, 217, 224, 0.2); }
  to{
    background:rgba(92, 112, 128, 0.2);
    border-color:rgba(92, 112, 128, 0.2); } }
@keyframes skeleton-glow{
  from{
    background:rgba(206, 217, 224, 0.2);
    border-color:rgba(206, 217, 224, 0.2); }
  to{
    background:rgba(92, 112, 128, 0.2);
    border-color:rgba(92, 112, 128, 0.2); } }
.bp3-skeleton{
  -webkit-animation:1000ms linear infinite alternate skeleton-glow;
          animation:1000ms linear infinite alternate skeleton-glow;
  background:rgba(206, 217, 224, 0.2);
  background-clip:padding-box !important;
  border-color:rgba(206, 217, 224, 0.2) !important;
  border-radius:2px;
  -webkit-box-shadow:none !important;
          box-shadow:none !important;
  color:transparent !important;
  cursor:default;
  pointer-events:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-skeleton::before, .bp3-skeleton::after,
  .bp3-skeleton *{
    visibility:hidden !important; }
.bp3-slider{
  height:40px;
  min-width:150px;
  width:100%;
  cursor:default;
  outline:none;
  position:relative;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-slider:hover{
    cursor:pointer; }
  .bp3-slider:active{
    cursor:-webkit-grabbing;
    cursor:grabbing; }
  .bp3-slider.bp3-disabled{
    cursor:not-allowed;
    opacity:0.5; }
  .bp3-slider.bp3-slider-unlabeled{
    height:16px; }

.bp3-slider-track,
.bp3-slider-progress{
  height:6px;
  left:0;
  right:0;
  top:5px;
  position:absolute; }

.bp3-slider-track{
  border-radius:3px;
  overflow:hidden; }

.bp3-slider-progress{
  background:rgba(92, 112, 128, 0.2); }
  .bp3-dark .bp3-slider-progress{
    background:rgba(16, 22, 26, 0.5); }
  .bp3-slider-progress.bp3-intent-primary{
    background-color:#137cbd; }
  .bp3-slider-progress.bp3-intent-success{
    background-color:#0f9960; }
  .bp3-slider-progress.bp3-intent-warning{
    background-color:#d9822b; }
  .bp3-slider-progress.bp3-intent-danger{
    background-color:#db3737; }

.bp3-slider-handle{
  background-color:#f5f8fa;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
  color:#182026;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
  cursor:pointer;
  height:16px;
  left:0;
  position:absolute;
  top:0;
  width:16px; }
  .bp3-slider-handle:hover{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1); }
  .bp3-slider-handle:active, .bp3-slider-handle.bp3-active{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
  .bp3-slider-handle:disabled, .bp3-slider-handle.bp3-disabled{
    background-color:rgba(206, 217, 224, 0.5);
    background-image:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed;
    outline:none; }
    .bp3-slider-handle:disabled.bp3-active, .bp3-slider-handle:disabled.bp3-active:hover, .bp3-slider-handle.bp3-disabled.bp3-active, .bp3-slider-handle.bp3-disabled.bp3-active:hover{
      background:rgba(206, 217, 224, 0.7); }
  .bp3-slider-handle:focus{
    z-index:1; }
  .bp3-slider-handle:hover{
    background-clip:padding-box;
    background-color:#ebf1f5;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
    cursor:-webkit-grab;
    cursor:grab;
    z-index:2; }
  .bp3-slider-handle.bp3-active{
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 1px rgba(16, 22, 26, 0.1);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 1px rgba(16, 22, 26, 0.1);
    cursor:-webkit-grabbing;
    cursor:grabbing; }
  .bp3-disabled .bp3-slider-handle{
    background:#bfccd6;
    -webkit-box-shadow:none;
            box-shadow:none;
    pointer-events:none; }
  .bp3-dark .bp3-slider-handle{
    background-color:#394b59;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle:hover, .bp3-dark .bp3-slider-handle:active, .bp3-dark .bp3-slider-handle.bp3-active{
      color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle:hover{
      background-color:#30404d;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-slider-handle:active, .bp3-dark .bp3-slider-handle.bp3-active{
      background-color:#202b33;
      background-image:none;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2); }
    .bp3-dark .bp3-slider-handle:disabled, .bp3-dark .bp3-slider-handle.bp3-disabled{
      background-color:rgba(57, 75, 89, 0.5);
      background-image:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      color:rgba(167, 182, 194, 0.6); }
      .bp3-dark .bp3-slider-handle:disabled.bp3-active, .bp3-dark .bp3-slider-handle.bp3-disabled.bp3-active{
        background:rgba(57, 75, 89, 0.7); }
    .bp3-dark .bp3-slider-handle .bp3-button-spinner .bp3-spinner-head{
      background:rgba(16, 22, 26, 0.5);
      stroke:#8a9ba8; }
    .bp3-dark .bp3-slider-handle, .bp3-dark .bp3-slider-handle:hover{
      background-color:#394b59; }
    .bp3-dark .bp3-slider-handle.bp3-active{
      background-color:#293742; }
  .bp3-dark .bp3-disabled .bp3-slider-handle{
    background:#5c7080;
    border-color:#5c7080;
    -webkit-box-shadow:none;
            box-shadow:none; }
  .bp3-slider-handle .bp3-slider-label{
    background:#394b59;
    border-radius:3px;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
    color:#f5f8fa;
    margin-left:8px; }
    .bp3-dark .bp3-slider-handle .bp3-slider-label{
      background:#e1e8ed;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
      color:#394b59; }
    .bp3-disabled .bp3-slider-handle .bp3-slider-label{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-slider-handle.bp3-start, .bp3-slider-handle.bp3-end{
    width:8px; }
  .bp3-slider-handle.bp3-start{
    border-bottom-right-radius:0;
    border-top-right-radius:0; }
  .bp3-slider-handle.bp3-end{
    border-bottom-left-radius:0;
    border-top-left-radius:0;
    margin-left:8px; }
    .bp3-slider-handle.bp3-end .bp3-slider-label{
      margin-left:0; }

.bp3-slider-label{
  -webkit-transform:translate(-50%, 20px);
          transform:translate(-50%, 20px);
  display:inline-block;
  font-size:12px;
  line-height:1;
  padding:2px 5px;
  position:absolute;
  vertical-align:top; }

.bp3-slider.bp3-vertical{
  height:150px;
  min-width:40px;
  width:40px; }
  .bp3-slider.bp3-vertical .bp3-slider-track,
  .bp3-slider.bp3-vertical .bp3-slider-progress{
    bottom:0;
    height:auto;
    left:5px;
    top:0;
    width:6px; }
  .bp3-slider.bp3-vertical .bp3-slider-progress{
    top:auto; }
  .bp3-slider.bp3-vertical .bp3-slider-label{
    -webkit-transform:translate(20px, 50%);
            transform:translate(20px, 50%); }
  .bp3-slider.bp3-vertical .bp3-slider-handle{
    top:auto; }
    .bp3-slider.bp3-vertical .bp3-slider-handle .bp3-slider-label{
      margin-left:0;
      margin-top:-8px; }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-end, .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start{
      height:8px;
      margin-left:0;
      width:16px; }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start{
      border-bottom-right-radius:3px;
      border-top-left-radius:0; }
      .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start .bp3-slider-label{
        -webkit-transform:translate(20px);
                transform:translate(20px); }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-end{
      border-bottom-left-radius:0;
      border-bottom-right-radius:0;
      border-top-left-radius:3px;
      margin-bottom:8px; }

@-webkit-keyframes pt-spinner-animation{
  from{
    -webkit-transform:rotate(0deg);
            transform:rotate(0deg); }
  to{
    -webkit-transform:rotate(360deg);
            transform:rotate(360deg); } }

@keyframes pt-spinner-animation{
  from{
    -webkit-transform:rotate(0deg);
            transform:rotate(0deg); }
  to{
    -webkit-transform:rotate(360deg);
            transform:rotate(360deg); } }

.bp3-spinner{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  overflow:visible;
  vertical-align:middle; }
  .bp3-spinner svg{
    display:block; }
  .bp3-spinner path{
    fill-opacity:0; }
  .bp3-spinner .bp3-spinner-head{
    stroke:rgba(92, 112, 128, 0.8);
    stroke-linecap:round;
    -webkit-transform-origin:center;
            transform-origin:center;
    -webkit-transition:stroke-dashoffset 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:stroke-dashoffset 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-spinner .bp3-spinner-track{
    stroke:rgba(92, 112, 128, 0.2); }

.bp3-spinner-animation{
  -webkit-animation:pt-spinner-animation 500ms linear infinite;
          animation:pt-spinner-animation 500ms linear infinite; }
  .bp3-no-spin > .bp3-spinner-animation{
    -webkit-animation:none;
            animation:none; }

.bp3-dark .bp3-spinner .bp3-spinner-head{
  stroke:#8a9ba8; }

.bp3-dark .bp3-spinner .bp3-spinner-track{
  stroke:rgba(16, 22, 26, 0.5); }

.bp3-spinner.bp3-intent-primary .bp3-spinner-head{
  stroke:#137cbd; }

.bp3-spinner.bp3-intent-success .bp3-spinner-head{
  stroke:#0f9960; }

.bp3-spinner.bp3-intent-warning .bp3-spinner-head{
  stroke:#d9822b; }

.bp3-spinner.bp3-intent-danger .bp3-spinner-head{
  stroke:#db3737; }
.bp3-tabs.bp3-vertical{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex; }
  .bp3-tabs.bp3-vertical > .bp3-tab-list{
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start;
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column; }
    .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab{
      border-radius:3px;
      padding:0 10px;
      width:100%; }
      .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab[aria-selected="true"]{
        background-color:rgba(19, 124, 189, 0.2);
        -webkit-box-shadow:none;
                box-shadow:none; }
    .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab-indicator-wrapper .bp3-tab-indicator{
      background-color:rgba(19, 124, 189, 0.2);
      border-radius:3px;
      bottom:0;
      height:auto;
      left:0;
      right:0;
      top:0; }
  .bp3-tabs.bp3-vertical > .bp3-tab-panel{
    margin-top:0;
    padding-left:20px; }

.bp3-tab-list{
  -webkit-box-align:end;
      -ms-flex-align:end;
          align-items:flex-end;
  border:none;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  list-style:none;
  margin:0;
  padding:0;
  position:relative; }
  .bp3-tab-list > *:not(:last-child){
    margin-right:20px; }

.bp3-tab{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  color:#182026;
  cursor:pointer;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  font-size:14px;
  line-height:30px;
  max-width:100%;
  position:relative;
  vertical-align:top; }
  .bp3-tab a{
    color:inherit;
    display:block;
    text-decoration:none; }
  .bp3-tab-indicator-wrapper ~ .bp3-tab{
    background-color:transparent !important;
    -webkit-box-shadow:none !important;
            box-shadow:none !important; }
  .bp3-tab[aria-disabled="true"]{
    color:rgba(92, 112, 128, 0.6);
    cursor:not-allowed; }
  .bp3-tab[aria-selected="true"]{
    border-radius:0;
    -webkit-box-shadow:inset 0 -3px 0 #106ba3;
            box-shadow:inset 0 -3px 0 #106ba3; }
  .bp3-tab[aria-selected="true"], .bp3-tab:not([aria-disabled="true"]):hover{
    color:#106ba3; }
  .bp3-tab:focus{
    -moz-outline-radius:0; }
  .bp3-large > .bp3-tab{
    font-size:16px;
    line-height:40px; }

.bp3-tab-panel{
  margin-top:20px; }
  .bp3-tab-panel[aria-hidden="true"]{
    display:none; }

.bp3-tab-indicator-wrapper{
  left:0;
  pointer-events:none;
  position:absolute;
  top:0;
  -webkit-transform:translateX(0), translateY(0);
          transform:translateX(0), translateY(0);
  -webkit-transition:height, width, -webkit-transform;
  transition:height, width, -webkit-transform;
  transition:height, transform, width;
  transition:height, transform, width, -webkit-transform;
  -webkit-transition-duration:200ms;
          transition-duration:200ms;
  -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
          transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-tab-indicator-wrapper .bp3-tab-indicator{
    background-color:#106ba3;
    bottom:0;
    height:3px;
    left:0;
    position:absolute;
    right:0; }
  .bp3-tab-indicator-wrapper.bp3-no-animation{
    -webkit-transition:none;
    transition:none; }

.bp3-dark .bp3-tab{
  color:#f5f8fa; }
  .bp3-dark .bp3-tab[aria-disabled="true"]{
    color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-tab[aria-selected="true"]{
    -webkit-box-shadow:inset 0 -3px 0 #48aff0;
            box-shadow:inset 0 -3px 0 #48aff0; }
  .bp3-dark .bp3-tab[aria-selected="true"], .bp3-dark .bp3-tab:not([aria-disabled="true"]):hover{
    color:#48aff0; }

.bp3-dark .bp3-tab-indicator{
  background-color:#48aff0; }

.bp3-flex-expander{
  -webkit-box-flex:1;
      -ms-flex:1 1;
          flex:1 1; }
.bp3-tag{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  background-color:#5c7080;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:none;
          box-shadow:none;
  color:#f5f8fa;
  font-size:12px;
  line-height:16px;
  max-width:100%;
  min-height:20px;
  min-width:20px;
  padding:2px 6px;
  position:relative; }
  .bp3-tag.bp3-interactive{
    cursor:pointer; }
    .bp3-tag.bp3-interactive:hover{
      background-color:rgba(92, 112, 128, 0.85); }
    .bp3-tag.bp3-interactive.bp3-active, .bp3-tag.bp3-interactive:active{
      background-color:rgba(92, 112, 128, 0.7); }
  .bp3-tag > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-tag > .bp3-fill{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-tag::before,
  .bp3-tag > *{
    margin-right:4px; }
  .bp3-tag:empty::before,
  .bp3-tag > :last-child{
    margin-right:0; }
  .bp3-tag:focus{
    outline:rgba(19, 124, 189, 0.6) auto 2px;
    outline-offset:0;
    -moz-outline-radius:6px; }
  .bp3-tag.bp3-round{
    border-radius:30px;
    padding-left:8px;
    padding-right:8px; }
  .bp3-dark .bp3-tag{
    background-color:#bfccd6;
    color:#182026; }
    .bp3-dark .bp3-tag.bp3-interactive{
      cursor:pointer; }
      .bp3-dark .bp3-tag.bp3-interactive:hover{
        background-color:rgba(191, 204, 214, 0.85); }
      .bp3-dark .bp3-tag.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-interactive:active{
        background-color:rgba(191, 204, 214, 0.7); }
    .bp3-dark .bp3-tag > .bp3-icon, .bp3-dark .bp3-tag .bp3-icon-standard, .bp3-dark .bp3-tag .bp3-icon-large{
      fill:currentColor; }
  .bp3-tag > .bp3-icon, .bp3-tag .bp3-icon-standard, .bp3-tag .bp3-icon-large{
    fill:#ffffff; }
  .bp3-tag.bp3-large,
  .bp3-large .bp3-tag{
    font-size:14px;
    line-height:20px;
    min-height:30px;
    min-width:30px;
    padding:5px 10px; }
    .bp3-tag.bp3-large::before,
    .bp3-tag.bp3-large > *,
    .bp3-large .bp3-tag::before,
    .bp3-large .bp3-tag > *{
      margin-right:7px; }
    .bp3-tag.bp3-large:empty::before,
    .bp3-tag.bp3-large > :last-child,
    .bp3-large .bp3-tag:empty::before,
    .bp3-large .bp3-tag > :last-child{
      margin-right:0; }
    .bp3-tag.bp3-large.bp3-round,
    .bp3-large .bp3-tag.bp3-round{
      padding-left:12px;
      padding-right:12px; }
  .bp3-tag.bp3-intent-primary{
    background:#137cbd;
    color:#ffffff; }
    .bp3-tag.bp3-intent-primary.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-primary.bp3-interactive:hover{
        background-color:rgba(19, 124, 189, 0.85); }
      .bp3-tag.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-primary.bp3-interactive:active{
        background-color:rgba(19, 124, 189, 0.7); }
  .bp3-tag.bp3-intent-success{
    background:#0f9960;
    color:#ffffff; }
    .bp3-tag.bp3-intent-success.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-success.bp3-interactive:hover{
        background-color:rgba(15, 153, 96, 0.85); }
      .bp3-tag.bp3-intent-success.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-success.bp3-interactive:active{
        background-color:rgba(15, 153, 96, 0.7); }
  .bp3-tag.bp3-intent-warning{
    background:#d9822b;
    color:#ffffff; }
    .bp3-tag.bp3-intent-warning.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-warning.bp3-interactive:hover{
        background-color:rgba(217, 130, 43, 0.85); }
      .bp3-tag.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-warning.bp3-interactive:active{
        background-color:rgba(217, 130, 43, 0.7); }
  .bp3-tag.bp3-intent-danger{
    background:#db3737;
    color:#ffffff; }
    .bp3-tag.bp3-intent-danger.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-intent-danger.bp3-interactive:hover{
        background-color:rgba(219, 55, 55, 0.85); }
      .bp3-tag.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-tag.bp3-intent-danger.bp3-interactive:active{
        background-color:rgba(219, 55, 55, 0.7); }
  .bp3-tag.bp3-fill{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    width:100%; }
  .bp3-tag.bp3-minimal > .bp3-icon, .bp3-tag.bp3-minimal .bp3-icon-standard, .bp3-tag.bp3-minimal .bp3-icon-large{
    fill:#5c7080; }
  .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]){
    background-color:rgba(138, 155, 168, 0.2);
    color:#182026; }
    .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:hover{
        background-color:rgba(92, 112, 128, 0.3); }
      .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive.bp3-active, .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:active{
        background-color:rgba(92, 112, 128, 0.4); }
    .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]){
      color:#f5f8fa; }
      .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:hover{
          background-color:rgba(191, 204, 214, 0.3); }
        .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]).bp3-interactive:active{
          background-color:rgba(191, 204, 214, 0.4); }
      .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) > .bp3-icon, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) .bp3-icon-standard, .bp3-dark .bp3-tag.bp3-minimal:not([class*="bp3-intent-"]) .bp3-icon-large{
        fill:#a7b6c2; }
  .bp3-tag.bp3-minimal.bp3-intent-primary{
    background-color:rgba(19, 124, 189, 0.15);
    color:#106ba3; }
    .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:hover{
        background-color:rgba(19, 124, 189, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:active{
        background-color:rgba(19, 124, 189, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-primary > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-primary .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-primary .bp3-icon-large{
      fill:#137cbd; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary{
      background-color:rgba(19, 124, 189, 0.25);
      color:#48aff0; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:hover{
          background-color:rgba(19, 124, 189, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-primary.bp3-interactive:active{
          background-color:rgba(19, 124, 189, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-success{
    background-color:rgba(15, 153, 96, 0.15);
    color:#0d8050; }
    .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:hover{
        background-color:rgba(15, 153, 96, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:active{
        background-color:rgba(15, 153, 96, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-success > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-success .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-success .bp3-icon-large{
      fill:#0f9960; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success{
      background-color:rgba(15, 153, 96, 0.25);
      color:#3dcc91; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:hover{
          background-color:rgba(15, 153, 96, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-success.bp3-interactive:active{
          background-color:rgba(15, 153, 96, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-warning{
    background-color:rgba(217, 130, 43, 0.15);
    color:#bf7326; }
    .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:hover{
        background-color:rgba(217, 130, 43, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:active{
        background-color:rgba(217, 130, 43, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-warning > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-warning .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-warning .bp3-icon-large{
      fill:#d9822b; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning{
      background-color:rgba(217, 130, 43, 0.25);
      color:#ffb366; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:hover{
          background-color:rgba(217, 130, 43, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-warning.bp3-interactive:active{
          background-color:rgba(217, 130, 43, 0.45); }
  .bp3-tag.bp3-minimal.bp3-intent-danger{
    background-color:rgba(219, 55, 55, 0.15);
    color:#c23030; }
    .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive{
      cursor:pointer; }
      .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:hover{
        background-color:rgba(219, 55, 55, 0.25); }
      .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:active{
        background-color:rgba(219, 55, 55, 0.35); }
    .bp3-tag.bp3-minimal.bp3-intent-danger > .bp3-icon, .bp3-tag.bp3-minimal.bp3-intent-danger .bp3-icon-standard, .bp3-tag.bp3-minimal.bp3-intent-danger .bp3-icon-large{
      fill:#db3737; }
    .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger{
      background-color:rgba(219, 55, 55, 0.25);
      color:#ff7373; }
      .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive{
        cursor:pointer; }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:hover{
          background-color:rgba(219, 55, 55, 0.35); }
        .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive.bp3-active, .bp3-dark .bp3-tag.bp3-minimal.bp3-intent-danger.bp3-interactive:active{
          background-color:rgba(219, 55, 55, 0.45); }

.bp3-tag-remove{
  background:none;
  border:none;
  color:inherit;
  cursor:pointer;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  margin-bottom:-2px;
  margin-right:-6px !important;
  margin-top:-2px;
  opacity:0.5;
  padding:2px;
  padding-left:0; }
  .bp3-tag-remove:hover{
    background:none;
    opacity:0.8;
    text-decoration:none; }
  .bp3-tag-remove:active{
    opacity:1; }
  .bp3-tag-remove:empty::before{
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-style:normal;
    font-weight:400;
    line-height:1;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    content:""; }
  .bp3-large .bp3-tag-remove{
    margin-right:-10px !important;
    padding:0 5px 0 0; }
    .bp3-large .bp3-tag-remove:empty::before{
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-style:normal;
      font-weight:400;
      line-height:1; }
.bp3-tag-input{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:horizontal;
  -webkit-box-direction:normal;
      -ms-flex-direction:row;
          flex-direction:row;
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  cursor:text;
  height:auto;
  line-height:inherit;
  min-height:30px;
  padding-left:5px;
  padding-right:0; }
  .bp3-tag-input > *{
    -webkit-box-flex:0;
        -ms-flex-positive:0;
            flex-grow:0;
    -ms-flex-negative:0;
        flex-shrink:0; }
  .bp3-tag-input > .bp3-tag-input-values{
    -webkit-box-flex:1;
        -ms-flex-positive:1;
            flex-grow:1;
    -ms-flex-negative:1;
        flex-shrink:1; }
  .bp3-tag-input .bp3-tag-input-icon{
    color:#5c7080;
    margin-left:2px;
    margin-right:7px;
    margin-top:7px; }
  .bp3-tag-input .bp3-tag-input-values{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-orient:horizontal;
    -webkit-box-direction:normal;
        -ms-flex-direction:row;
            flex-direction:row;
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center;
    -ms-flex-item-align:stretch;
        align-self:stretch;
    -ms-flex-wrap:wrap;
        flex-wrap:wrap;
    margin-right:7px;
    margin-top:5px;
    min-width:0; }
    .bp3-tag-input .bp3-tag-input-values > *{
      -webkit-box-flex:0;
          -ms-flex-positive:0;
              flex-grow:0;
      -ms-flex-negative:0;
          flex-shrink:0; }
    .bp3-tag-input .bp3-tag-input-values > .bp3-fill{
      -webkit-box-flex:1;
          -ms-flex-positive:1;
              flex-grow:1;
      -ms-flex-negative:1;
          flex-shrink:1; }
    .bp3-tag-input .bp3-tag-input-values::before,
    .bp3-tag-input .bp3-tag-input-values > *{
      margin-right:5px; }
    .bp3-tag-input .bp3-tag-input-values:empty::before,
    .bp3-tag-input .bp3-tag-input-values > :last-child{
      margin-right:0; }
    .bp3-tag-input .bp3-tag-input-values:first-child .bp3-input-ghost:first-child{
      padding-left:5px; }
    .bp3-tag-input .bp3-tag-input-values > *{
      margin-bottom:5px; }
  .bp3-tag-input .bp3-tag{
    overflow-wrap:break-word; }
    .bp3-tag-input .bp3-tag.bp3-active{
      outline:rgba(19, 124, 189, 0.6) auto 2px;
      outline-offset:0;
      -moz-outline-radius:6px; }
  .bp3-tag-input .bp3-input-ghost{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    line-height:20px;
    width:80px; }
    .bp3-tag-input .bp3-input-ghost:disabled, .bp3-tag-input .bp3-input-ghost.bp3-disabled{
      cursor:not-allowed; }
  .bp3-tag-input .bp3-button,
  .bp3-tag-input .bp3-spinner{
    margin:3px;
    margin-left:0; }
  .bp3-tag-input .bp3-button{
    min-height:24px;
    min-width:24px;
    padding:0 7px; }
  .bp3-tag-input.bp3-large{
    height:auto;
    min-height:40px; }
    .bp3-tag-input.bp3-large::before,
    .bp3-tag-input.bp3-large > *{
      margin-right:10px; }
    .bp3-tag-input.bp3-large:empty::before,
    .bp3-tag-input.bp3-large > :last-child{
      margin-right:0; }
    .bp3-tag-input.bp3-large .bp3-tag-input-icon{
      margin-left:5px;
      margin-top:10px; }
    .bp3-tag-input.bp3-large .bp3-input-ghost{
      line-height:30px; }
    .bp3-tag-input.bp3-large .bp3-button{
      min-height:30px;
      min-width:30px;
      padding:5px 10px;
      margin:5px;
      margin-left:0; }
    .bp3-tag-input.bp3-large .bp3-spinner{
      margin:8px;
      margin-left:0; }
  .bp3-tag-input.bp3-active{
    background-color:#ffffff;
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-success{
      -webkit-box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
    .bp3-tag-input.bp3-active.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2); }
  .bp3-dark .bp3-tag-input .bp3-tag-input-icon, .bp3-tag-input.bp3-dark .bp3-tag-input-icon{
    color:#a7b6c2; }
  .bp3-dark .bp3-tag-input .bp3-input-ghost, .bp3-tag-input.bp3-dark .bp3-input-ghost{
    color:#f5f8fa; }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-webkit-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-webkit-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-moz-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-moz-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost:-ms-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost:-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::-ms-input-placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::-ms-input-placeholder{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-tag-input .bp3-input-ghost::placeholder, .bp3-tag-input.bp3-dark .bp3-input-ghost::placeholder{
      color:rgba(167, 182, 194, 0.6); }
  .bp3-dark .bp3-tag-input.bp3-active, .bp3-tag-input.bp3-dark.bp3-active{
    background-color:rgba(16, 22, 26, 0.3);
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-primary, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-primary{
      -webkit-box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #106ba3, 0 0 0 3px rgba(16, 107, 163, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-success, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-success{
      -webkit-box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #0d8050, 0 0 0 3px rgba(13, 128, 80, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-warning, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-warning{
      -webkit-box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #bf7326, 0 0 0 3px rgba(191, 115, 38, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }
    .bp3-dark .bp3-tag-input.bp3-active.bp3-intent-danger, .bp3-tag-input.bp3-dark.bp3-active.bp3-intent-danger{
      -webkit-box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px #c23030, 0 0 0 3px rgba(194, 48, 48, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4); }

.bp3-input-ghost{
  background:none;
  border:none;
  -webkit-box-shadow:none;
          box-shadow:none;
  padding:0; }
  .bp3-input-ghost::-webkit-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost::-moz-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost:-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost::-ms-input-placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost::placeholder{
    color:rgba(92, 112, 128, 0.6);
    opacity:1; }
  .bp3-input-ghost:focus{
    outline:none !important; }
.bp3-toast{
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  background-color:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  margin:20px 0 0;
  max-width:500px;
  min-width:300px;
  pointer-events:all;
  position:relative !important; }
  .bp3-toast.bp3-toast-enter, .bp3-toast.bp3-toast-appear{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px); }
  .bp3-toast.bp3-toast-enter-active, .bp3-toast.bp3-toast-appear-active{
    -webkit-transform:translateY(0);
            transform:translateY(0);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-toast.bp3-toast-enter ~ .bp3-toast, .bp3-toast.bp3-toast-appear ~ .bp3-toast{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px); }
  .bp3-toast.bp3-toast-enter-active ~ .bp3-toast, .bp3-toast.bp3-toast-appear-active ~ .bp3-toast{
    -webkit-transform:translateY(0);
            transform:translateY(0);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11); }
  .bp3-toast.bp3-toast-exit{
    opacity:1;
    -webkit-filter:blur(0);
            filter:blur(0); }
  .bp3-toast.bp3-toast-exit-active{
    opacity:0;
    -webkit-filter:blur(10px);
            filter:blur(10px);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:opacity, filter;
    transition-property:opacity, filter, -webkit-filter;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-toast.bp3-toast-exit ~ .bp3-toast{
    -webkit-transform:translateY(0);
            transform:translateY(0); }
  .bp3-toast.bp3-toast-exit-active ~ .bp3-toast{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px);
    -webkit-transition-delay:50ms;
            transition-delay:50ms;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-toast .bp3-button-group{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    padding:5px;
    padding-left:0; }
  .bp3-toast > .bp3-icon{
    color:#5c7080;
    margin:12px;
    margin-right:0; }
  .bp3-toast.bp3-dark,
  .bp3-dark .bp3-toast{
    background-color:#394b59;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-toast.bp3-dark > .bp3-icon,
    .bp3-dark .bp3-toast > .bp3-icon{
      color:#a7b6c2; }
  .bp3-toast[class*="bp3-intent-"] a{
    color:rgba(255, 255, 255, 0.7); }
    .bp3-toast[class*="bp3-intent-"] a:hover{
      color:#ffffff; }
  .bp3-toast[class*="bp3-intent-"] > .bp3-icon{
    color:#ffffff; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button, .bp3-toast[class*="bp3-intent-"] .bp3-button::before,
  .bp3-toast[class*="bp3-intent-"] .bp3-button .bp3-icon, .bp3-toast[class*="bp3-intent-"] .bp3-button:active{
    color:rgba(255, 255, 255, 0.7) !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:focus{
    outline-color:rgba(255, 255, 255, 0.5); }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:hover{
    background-color:rgba(255, 255, 255, 0.15) !important;
    color:#ffffff !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button:active{
    background-color:rgba(255, 255, 255, 0.3) !important;
    color:#ffffff !important; }
  .bp3-toast[class*="bp3-intent-"] .bp3-button::after{
    background:rgba(255, 255, 255, 0.3) !important; }
  .bp3-toast.bp3-intent-primary{
    background-color:#137cbd;
    color:#ffffff; }
  .bp3-toast.bp3-intent-success{
    background-color:#0f9960;
    color:#ffffff; }
  .bp3-toast.bp3-intent-warning{
    background-color:#d9822b;
    color:#ffffff; }
  .bp3-toast.bp3-intent-danger{
    background-color:#db3737;
    color:#ffffff; }

.bp3-toast-message{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  padding:11px;
  word-break:break-word; }

.bp3-toast-container{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box !important;
  display:-ms-flexbox !important;
  display:flex !important;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  left:0;
  overflow:hidden;
  padding:0 20px 20px;
  pointer-events:none;
  right:0;
  z-index:40; }
  .bp3-toast-container.bp3-toast-container-in-portal{
    position:fixed; }
  .bp3-toast-container.bp3-toast-container-inline{
    position:absolute; }
  .bp3-toast-container.bp3-toast-container-top{
    top:0; }
  .bp3-toast-container.bp3-toast-container-bottom{
    bottom:0;
    -webkit-box-orient:vertical;
    -webkit-box-direction:reverse;
        -ms-flex-direction:column-reverse;
            flex-direction:column-reverse;
    top:auto; }
  .bp3-toast-container.bp3-toast-container-left{
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start; }
  .bp3-toast-container.bp3-toast-container-right{
    -webkit-box-align:end;
        -ms-flex-align:end;
            align-items:flex-end; }

.bp3-toast-container-bottom .bp3-toast.bp3-toast-enter:not(.bp3-toast-enter-active),
.bp3-toast-container-bottom .bp3-toast.bp3-toast-enter:not(.bp3-toast-enter-active) ~ .bp3-toast, .bp3-toast-container-bottom .bp3-toast.bp3-toast-appear:not(.bp3-toast-appear-active),
.bp3-toast-container-bottom .bp3-toast.bp3-toast-appear:not(.bp3-toast-appear-active) ~ .bp3-toast,
.bp3-toast-container-bottom .bp3-toast.bp3-toast-exit-active ~ .bp3-toast,
.bp3-toast-container-bottom .bp3-toast.bp3-toast-leave-active ~ .bp3-toast{
  -webkit-transform:translateY(60px);
          transform:translateY(60px); }
.bp3-tooltip{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  -webkit-transform:scale(1);
          transform:scale(1); }
  .bp3-tooltip .bp3-popover-arrow{
    height:22px;
    position:absolute;
    width:22px; }
    .bp3-tooltip .bp3-popover-arrow::before{
      height:14px;
      margin:4px;
      width:14px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip{
    margin-bottom:11px;
    margin-top:-11px; }
    .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow{
      bottom:-8px; }
      .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(-90deg);
                transform:rotate(-90deg); }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip{
    margin-left:11px; }
    .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow{
      left:-8px; }
      .bp3-tether-element-attached-left.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(0);
                transform:rotate(0); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip{
    margin-top:11px; }
    .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow{
      top:-8px; }
      .bp3-tether-element-attached-top.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(90deg);
                transform:rotate(90deg); }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip{
    margin-left:-11px;
    margin-right:11px; }
    .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow{
      right:-8px; }
      .bp3-tether-element-attached-right.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow svg{
        -webkit-transform:rotate(180deg);
                transform:rotate(180deg); }
  .bp3-tether-element-attached-middle > .bp3-tooltip > .bp3-popover-arrow{
    top:50%;
    -webkit-transform:translateY(-50%);
            transform:translateY(-50%); }
  .bp3-tether-element-attached-center > .bp3-tooltip > .bp3-popover-arrow{
    right:50%;
    -webkit-transform:translateX(50%);
            transform:translateX(50%); }
  .bp3-tether-element-attached-top.bp3-tether-target-attached-top > .bp3-tooltip > .bp3-popover-arrow{
    top:-0.22183px; }
  .bp3-tether-element-attached-right.bp3-tether-target-attached-right > .bp3-tooltip > .bp3-popover-arrow{
    right:-0.22183px; }
  .bp3-tether-element-attached-left.bp3-tether-target-attached-left > .bp3-tooltip > .bp3-popover-arrow{
    left:-0.22183px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-bottom > .bp3-tooltip > .bp3-popover-arrow{
    bottom:-0.22183px; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:top left;
            transform-origin:top left; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:top center;
            transform-origin:top center; }
  .bp3-tether-element-attached-top.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:top right;
            transform-origin:top right; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:center left;
            transform-origin:center left; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:center center;
            transform-origin:center center; }
  .bp3-tether-element-attached-middle.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:center right;
            transform-origin:center right; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-left > .bp3-tooltip{
    -webkit-transform-origin:bottom left;
            transform-origin:bottom left; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-center > .bp3-tooltip{
    -webkit-transform-origin:bottom center;
            transform-origin:bottom center; }
  .bp3-tether-element-attached-bottom.bp3-tether-element-attached-right > .bp3-tooltip{
    -webkit-transform-origin:bottom right;
            transform-origin:bottom right; }
  .bp3-tooltip .bp3-popover-content{
    background:#394b59;
    color:#f5f8fa; }
  .bp3-tooltip .bp3-popover-arrow::before{
    -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2);
            box-shadow:1px 1px 6px rgba(16, 22, 26, 0.2); }
  .bp3-tooltip .bp3-popover-arrow-border{
    fill:#10161a;
    fill-opacity:0.1; }
  .bp3-tooltip .bp3-popover-arrow-fill{
    fill:#394b59; }
  .bp3-popover-enter > .bp3-tooltip, .bp3-popover-appear > .bp3-tooltip{
    -webkit-transform:scale(0.8);
            transform:scale(0.8); }
  .bp3-popover-enter-active > .bp3-tooltip, .bp3-popover-appear-active > .bp3-tooltip{
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-popover-exit > .bp3-tooltip{
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-popover-exit-active > .bp3-tooltip{
    -webkit-transform:scale(0.8);
            transform:scale(0.8);
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-tooltip .bp3-popover-content{
    padding:10px 12px; }
  .bp3-tooltip.bp3-dark,
  .bp3-dark .bp3-tooltip{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4); }
    .bp3-tooltip.bp3-dark .bp3-popover-content,
    .bp3-dark .bp3-tooltip .bp3-popover-content{
      background:#e1e8ed;
      color:#394b59; }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow::before,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow::before{
      -webkit-box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4);
              box-shadow:1px 1px 6px rgba(16, 22, 26, 0.4); }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow-border,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow-border{
      fill:#10161a;
      fill-opacity:0.2; }
    .bp3-tooltip.bp3-dark .bp3-popover-arrow-fill,
    .bp3-dark .bp3-tooltip .bp3-popover-arrow-fill{
      fill:#e1e8ed; }
  .bp3-tooltip.bp3-intent-primary .bp3-popover-content{
    background:#137cbd;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-primary .bp3-popover-arrow-fill{
    fill:#137cbd; }
  .bp3-tooltip.bp3-intent-success .bp3-popover-content{
    background:#0f9960;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-success .bp3-popover-arrow-fill{
    fill:#0f9960; }
  .bp3-tooltip.bp3-intent-warning .bp3-popover-content{
    background:#d9822b;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-warning .bp3-popover-arrow-fill{
    fill:#d9822b; }
  .bp3-tooltip.bp3-intent-danger .bp3-popover-content{
    background:#db3737;
    color:#ffffff; }
  .bp3-tooltip.bp3-intent-danger .bp3-popover-arrow-fill{
    fill:#db3737; }

.bp3-tooltip-indicator{
  border-bottom:dotted 1px;
  cursor:help; }
.bp3-tree .bp3-icon, .bp3-tree .bp3-icon-standard, .bp3-tree .bp3-icon-large{
  color:#5c7080; }
  .bp3-tree .bp3-icon.bp3-intent-primary, .bp3-tree .bp3-icon-standard.bp3-intent-primary, .bp3-tree .bp3-icon-large.bp3-intent-primary{
    color:#137cbd; }
  .bp3-tree .bp3-icon.bp3-intent-success, .bp3-tree .bp3-icon-standard.bp3-intent-success, .bp3-tree .bp3-icon-large.bp3-intent-success{
    color:#0f9960; }
  .bp3-tree .bp3-icon.bp3-intent-warning, .bp3-tree .bp3-icon-standard.bp3-intent-warning, .bp3-tree .bp3-icon-large.bp3-intent-warning{
    color:#d9822b; }
  .bp3-tree .bp3-icon.bp3-intent-danger, .bp3-tree .bp3-icon-standard.bp3-intent-danger, .bp3-tree .bp3-icon-large.bp3-intent-danger{
    color:#db3737; }

.bp3-tree-node-list{
  list-style:none;
  margin:0;
  padding-left:0; }

.bp3-tree-root{
  background-color:transparent;
  cursor:default;
  padding-left:0;
  position:relative; }

.bp3-tree-node-content-0{
  padding-left:0px; }

.bp3-tree-node-content-1{
  padding-left:23px; }

.bp3-tree-node-content-2{
  padding-left:46px; }

.bp3-tree-node-content-3{
  padding-left:69px; }

.bp3-tree-node-content-4{
  padding-left:92px; }

.bp3-tree-node-content-5{
  padding-left:115px; }

.bp3-tree-node-content-6{
  padding-left:138px; }

.bp3-tree-node-content-7{
  padding-left:161px; }

.bp3-tree-node-content-8{
  padding-left:184px; }

.bp3-tree-node-content-9{
  padding-left:207px; }

.bp3-tree-node-content-10{
  padding-left:230px; }

.bp3-tree-node-content-11{
  padding-left:253px; }

.bp3-tree-node-content-12{
  padding-left:276px; }

.bp3-tree-node-content-13{
  padding-left:299px; }

.bp3-tree-node-content-14{
  padding-left:322px; }

.bp3-tree-node-content-15{
  padding-left:345px; }

.bp3-tree-node-content-16{
  padding-left:368px; }

.bp3-tree-node-content-17{
  padding-left:391px; }

.bp3-tree-node-content-18{
  padding-left:414px; }

.bp3-tree-node-content-19{
  padding-left:437px; }

.bp3-tree-node-content-20{
  padding-left:460px; }

.bp3-tree-node-content{
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  height:30px;
  padding-right:5px;
  width:100%; }
  .bp3-tree-node-content:hover{
    background-color:rgba(191, 204, 214, 0.4); }

.bp3-tree-node-caret,
.bp3-tree-node-caret-none{
  min-width:30px; }

.bp3-tree-node-caret{
  color:#5c7080;
  cursor:pointer;
  padding:7px;
  -webkit-transform:rotate(0deg);
          transform:rotate(0deg);
  -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-tree-node-caret:hover{
    color:#182026; }
  .bp3-dark .bp3-tree-node-caret{
    color:#a7b6c2; }
    .bp3-dark .bp3-tree-node-caret:hover{
      color:#f5f8fa; }
  .bp3-tree-node-caret.bp3-tree-node-caret-open{
    -webkit-transform:rotate(90deg);
            transform:rotate(90deg); }
  .bp3-tree-node-caret.bp3-icon-standard::before{
    content:""; }

.bp3-tree-node-icon{
  margin-right:7px;
  position:relative; }

.bp3-tree-node-label{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  position:relative;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-tree-node-label span{
    display:inline; }

.bp3-tree-node-secondary-label{
  padding:0 5px;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-tree-node-secondary-label .bp3-popover-wrapper,
  .bp3-tree-node-secondary-label .bp3-popover-target{
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center;
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex; }

.bp3-tree-node.bp3-disabled .bp3-tree-node-content{
  background-color:inherit;
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-tree-node.bp3-disabled .bp3-tree-node-caret,
.bp3-tree-node.bp3-disabled .bp3-tree-node-icon{
  color:rgba(92, 112, 128, 0.6);
  cursor:not-allowed; }

.bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content{
  background-color:#137cbd; }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content,
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon, .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon-standard, .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-icon-large{
    color:#ffffff; }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-tree-node-caret::before{
    color:rgba(255, 255, 255, 0.7); }
  .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content .bp3-tree-node-caret:hover::before{
    color:#ffffff; }

.bp3-dark .bp3-tree-node-content:hover{
  background-color:rgba(92, 112, 128, 0.3); }

.bp3-dark .bp3-tree .bp3-icon, .bp3-dark .bp3-tree .bp3-icon-standard, .bp3-dark .bp3-tree .bp3-icon-large{
  color:#a7b6c2; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-primary, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-primary, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-primary{
    color:#137cbd; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-success, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-success, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-success{
    color:#0f9960; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-warning, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-warning, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-warning{
    color:#d9822b; }
  .bp3-dark .bp3-tree .bp3-icon.bp3-intent-danger, .bp3-dark .bp3-tree .bp3-icon-standard.bp3-intent-danger, .bp3-dark .bp3-tree .bp3-icon-large.bp3-intent-danger{
    color:#db3737; }

.bp3-dark .bp3-tree-node.bp3-tree-node-selected > .bp3-tree-node-content{
  background-color:#137cbd; }
.bp3-omnibar{
  -webkit-filter:blur(0);
          filter:blur(0);
  opacity:1;
  background-color:#ffffff;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  left:calc(50% - 250px);
  top:20vh;
  width:500px;
  z-index:21; }
  .bp3-omnibar.bp3-overlay-enter, .bp3-omnibar.bp3-overlay-appear{
    -webkit-filter:blur(20px);
            filter:blur(20px);
    opacity:0.2; }
  .bp3-omnibar.bp3-overlay-enter-active, .bp3-omnibar.bp3-overlay-appear-active{
    -webkit-filter:blur(0);
            filter:blur(0);
    opacity:1;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:filter, opacity;
    transition-property:filter, opacity, -webkit-filter;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-omnibar.bp3-overlay-exit{
    -webkit-filter:blur(0);
            filter:blur(0);
    opacity:1; }
  .bp3-omnibar.bp3-overlay-exit-active{
    -webkit-filter:blur(20px);
            filter:blur(20px);
    opacity:0.2;
    -webkit-transition-delay:0;
            transition-delay:0;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:filter, opacity;
    transition-property:filter, opacity, -webkit-filter;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-omnibar .bp3-input{
    background-color:transparent;
    border-radius:0; }
    .bp3-omnibar .bp3-input, .bp3-omnibar .bp3-input:focus{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-omnibar .bp3-menu{
    background-color:transparent;
    border-radius:0;
    -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
    max-height:calc(60vh - 40px);
    overflow:auto; }
    .bp3-omnibar .bp3-menu:empty{
      display:none; }
  .bp3-dark .bp3-omnibar, .bp3-omnibar.bp3-dark{
    background-color:#30404d;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4); }

.bp3-omnibar-overlay .bp3-overlay-backdrop{
  background-color:rgba(16, 22, 26, 0.2); }

.bp3-select-popover .bp3-popover-content{
  padding:5px; }

.bp3-select-popover .bp3-input-group{
  margin-bottom:0; }

.bp3-select-popover .bp3-menu{
  max-height:300px;
  max-width:400px;
  overflow:auto;
  padding:0; }
  .bp3-select-popover .bp3-menu:not(:first-child){
    padding-top:5px; }

.bp3-multi-select{
  min-width:150px; }

.bp3-multi-select-popover .bp3-menu{
  max-height:300px;
  max-width:400px;
  overflow:auto; }

.bp3-select-popover .bp3-popover-content{
  padding:5px; }

.bp3-select-popover .bp3-input-group{
  margin-bottom:0; }

.bp3-select-popover .bp3-menu{
  max-height:300px;
  max-width:400px;
  overflow:auto;
  padding:0; }
  .bp3-select-popover .bp3-menu:not(:first-child){
    padding-top:5px; }
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensureUiComponents() in @jupyterlab/buildutils */

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

/* Icons urls */

:root {
  --jp-icon-add: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDEzaC02djZoLTJ2LTZINXYtMmg2VjVoMnY2aDZ2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bug: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0yMCA4aC0yLjgxYy0uNDUtLjc4LTEuMDctMS40NS0xLjgyLTEuOTZMMTcgNC40MSAxNS41OSAzbC0yLjE3IDIuMTdDMTIuOTYgNS4wNiAxMi40OSA1IDEyIDVjLS40OSAwLS45Ni4wNi0xLjQxLjE3TDguNDEgMyA3IDQuNDFsMS42MiAxLjYzQzcuODggNi41NSA3LjI2IDcuMjIgNi44MSA4SDR2MmgyLjA5Yy0uMDUuMzMtLjA5LjY2LS4wOSAxdjFINHYyaDJ2MWMwIC4zNC4wNC42Ny4wOSAxSDR2MmgyLjgxYzEuMDQgMS43OSAyLjk3IDMgNS4xOSAzczQuMTUtMS4yMSA1LjE5LTNIMjB2LTJoLTIuMDljLjA1LS4zMy4wOS0uNjYuMDktMXYtMWgydi0yaC0ydi0xYzAtLjM0LS4wNC0uNjctLjA5LTFIMjBWOHptLTYgOGgtNHYtMmg0djJ6bTAtNGgtNHYtMmg0djJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-build: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE0LjkgMTcuNDVDMTYuMjUgMTcuNDUgMTcuMzUgMTYuMzUgMTcuMzUgMTVDMTcuMzUgMTMuNjUgMTYuMjUgMTIuNTUgMTQuOSAxMi41NUMxMy41NCAxMi41NSAxMi40NSAxMy42NSAxMi40NSAxNUMxMi40NSAxNi4zNSAxMy41NCAxNy40NSAxNC45IDE3LjQ1Wk0yMC4xIDE1LjY4TDIxLjU4IDE2Ljg0QzIxLjcxIDE2Ljk1IDIxLjc1IDE3LjEzIDIxLjY2IDE3LjI5TDIwLjI2IDE5LjcxQzIwLjE3IDE5Ljg2IDIwIDE5LjkyIDE5LjgzIDE5Ljg2TDE4LjA5IDE5LjE2QzE3LjczIDE5LjQ0IDE3LjMzIDE5LjY3IDE2LjkxIDE5Ljg1TDE2LjY0IDIxLjdDMTYuNjIgMjEuODcgMTYuNDcgMjIgMTYuMyAyMkgxMy41QzEzLjMyIDIyIDEzLjE4IDIxLjg3IDEzLjE1IDIxLjdMMTIuODkgMTkuODVDMTIuNDYgMTkuNjcgMTIuMDcgMTkuNDQgMTEuNzEgMTkuMTZMOS45NjAwMiAxOS44NkM5LjgxMDAyIDE5LjkyIDkuNjIwMDIgMTkuODYgOS41NDAwMiAxOS43MUw4LjE0MDAyIDE3LjI5QzguMDUwMDIgMTcuMTMgOC4wOTAwMiAxNi45NSA4LjIyMDAyIDE2Ljg0TDkuNzAwMDIgMTUuNjhMOS42NTAwMSAxNUw5LjcwMDAyIDE0LjMxTDguMjIwMDIgMTMuMTZDOC4wOTAwMiAxMy4wNSA4LjA1MDAyIDEyLjg2IDguMTQwMDIgMTIuNzFMOS41NDAwMiAxMC4yOUM5LjYyMDAyIDEwLjEzIDkuODEwMDIgMTAuMDcgOS45NjAwMiAxMC4xM0wxMS43MSAxMC44NEMxMi4wNyAxMC41NiAxMi40NiAxMC4zMiAxMi44OSAxMC4xNUwxMy4xNSA4LjI4OTk4QzEzLjE4IDguMTI5OTggMTMuMzIgNy45OTk5OCAxMy41IDcuOTk5OThIMTYuM0MxNi40NyA3Ljk5OTk4IDE2LjYyIDguMTI5OTggMTYuNjQgOC4yODk5OEwxNi45MSAxMC4xNUMxNy4zMyAxMC4zMiAxNy43MyAxMC41NiAxOC4wOSAxMC44NEwxOS44MyAxMC4xM0MyMCAxMC4wNyAyMC4xNyAxMC4xMyAyMC4yNiAxMC4yOUwyMS42NiAxMi43MUMyMS43NSAxMi44NiAyMS43MSAxMy4wNSAyMS41OCAxMy4xNkwyMC4xIDE0LjMxTDIwLjE1IDE1TDIwLjEgMTUuNjhaIi8+CiAgICA8cGF0aCBkPSJNNy4zMjk2NiA3LjQ0NDU0QzguMDgzMSA3LjAwOTU0IDguMzM5MzIgNi4wNTMzMiA3LjkwNDMyIDUuMjk5ODhDNy40NjkzMiA0LjU0NjQzIDYuNTA4MSA0LjI4MTU2IDUuNzU0NjYgNC43MTY1NkM1LjM5MTc2IDQuOTI2MDggNS4xMjY5NSA1LjI3MTE4IDUuMDE4NDkgNS42NzU5NEM0LjkxMDA0IDYuMDgwNzEgNC45NjY4MiA2LjUxMTk4IDUuMTc2MzQgNi44NzQ4OEM1LjYxMTM0IDcuNjI4MzIgNi41NzYyMiA3Ljg3OTU0IDcuMzI5NjYgNy40NDQ1NFpNOS42NTcxOCA0Ljc5NTkzTDEwLjg2NzIgNC45NTE3OUMxMC45NjI4IDQuOTc3NDEgMTEuMDQwMiA1LjA3MTMzIDExLjAzODIgNS4xODc5M0wxMS4wMzg4IDYuOTg4OTNDMTEuMDQ1NSA3LjEwMDU0IDEwLjk2MTYgNy4xOTUxOCAxMC44NTUgNy4yMTA1NEw5LjY2MDAxIDcuMzgwODNMOS4yMzkxNSA4LjEzMTg4TDkuNjY5NjEgOS4yNTc0NUM5LjcwNzI5IDkuMzYyNzEgOS42NjkzNCA5LjQ3Njk5IDkuNTc0MDggOS41MzE5OUw4LjAxNTIzIDEwLjQzMkM3LjkxMTMxIDEwLjQ5MiA3Ljc5MzM3IDEwLjQ2NzcgNy43MjEwNSAxMC4zODI0TDYuOTg3NDggOS40MzE4OEw2LjEwOTMxIDkuNDMwODNMNS4zNDcwNCAxMC4zOTA1QzUuMjg5MDkgMTAuNDcwMiA1LjE3MzgzIDEwLjQ5MDUgNS4wNzE4NyAxMC40MzM5TDMuNTEyNDUgOS41MzI5M0MzLjQxMDQ5IDkuNDc2MzMgMy4zNzY0NyA5LjM1NzQxIDMuNDEwNzUgOS4yNTY3OUwzLjg2MzQ3IDguMTQwOTNMMy42MTc0OSA3Ljc3NDg4TDMuNDIzNDcgNy4zNzg4M0wyLjIzMDc1IDcuMjEyOTdDMi4xMjY0NyA3LjE5MjM1IDIuMDQwNDkgNy4xMDM0MiAyLjA0MjQ1IDYuOTg2ODJMMi4wNDE4NyA1LjE4NTgyQzIuMDQzODMgNS4wNjkyMiAyLjExOTA5IDQuOTc5NTggMi4yMTcwNCA0Ljk2OTIyTDMuNDIwNjUgNC43OTM5M0wzLjg2NzQ5IDQuMDI3ODhMMy40MTEwNSAyLjkxNzMxQzMuMzczMzcgMi44MTIwNCAzLjQxMTMxIDIuNjk3NzYgMy41MTUyMyAyLjYzNzc2TDUuMDc0MDggMS43Mzc3NkM1LjE2OTM0IDEuNjgyNzYgNS4yODcyOSAxLjcwNzA0IDUuMzU5NjEgMS43OTIzMUw2LjExOTE1IDIuNzI3ODhMNi45ODAwMSAyLjczODkzTDcuNzI0OTYgMS43ODkyMkM3Ljc5MTU2IDEuNzA0NTggNy45MTU0OCAxLjY3OTIyIDguMDA4NzkgMS43NDA4Mkw5LjU2ODIxIDIuNjQxODJDOS42NzAxNyAyLjY5ODQyIDkuNzEyODUgMi44MTIzNCA5LjY4NzIzIDIuOTA3OTdMOS4yMTcxOCA0LjAzMzgzTDkuNDYzMTYgNC4zOTk4OEw5LjY1NzE4IDQuNzk1OTNaIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iOS45LDEzLjYgMy42LDcuNCA0LjQsNi42IDkuOSwxMi4yIDE1LjQsNi43IDE2LjEsNy40ICIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNS45TDksOS43bDMuOC0zLjhsMS4yLDEuMmwtNC45LDVsLTQuOS01TDUuMiw1Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNy41TDksMTEuMmwzLjgtMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-left: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik0xMC44LDEyLjhMNy4xLDlsMy44LTMuOGwwLDcuNkgxMC44eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-right: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik03LjIsNS4yTDEwLjksOWwtMy44LDMuOFY1LjJINy4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-up-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iMTUuNCwxMy4zIDkuOSw3LjcgNC40LDEzLjIgMy42LDEyLjUgOS45LDYuMyAxNi4xLDEyLjYgIi8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-up: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik01LjIsMTAuNUw5LDYuOGwzLjgsMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-case-sensitive: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWFjY2VudDIiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTcuNiw4aDAuOWwzLjUsOGgtMS4xTDEwLDE0SDZsLTAuOSwySDRMNy42LDh6IE04LDkuMUw2LjQsMTNoMy4yTDgsOS4xeiIvPgogICAgPHBhdGggZD0iTTE2LjYsOS44Yy0wLjIsMC4xLTAuNCwwLjEtMC43LDAuMWMtMC4yLDAtMC40LTAuMS0wLjYtMC4yYy0wLjEtMC4xLTAuMi0wLjQtMC4yLTAuNyBjLTAuMywwLjMtMC42LDAuNS0wLjksMC43Yy0wLjMsMC4xLTAuNywwLjItMS4xLDAuMmMtMC4zLDAtMC41LDAtMC43LTAuMWMtMC4yLTAuMS0wLjQtMC4yLTAuNi0wLjNjLTAuMi0wLjEtMC4zLTAuMy0wLjQtMC41IGMtMC4xLTAuMi0wLjEtMC40LTAuMS0wLjdjMC0wLjMsMC4xLTAuNiwwLjItMC44YzAuMS0wLjIsMC4zLTAuNCwwLjQtMC41QzEyLDcsMTIuMiw2LjksMTIuNSw2LjhjMC4yLTAuMSwwLjUtMC4xLDAuNy0wLjIgYzAuMy0wLjEsMC41LTAuMSwwLjctMC4xYzAuMiwwLDAuNC0wLjEsMC42LTAuMWMwLjIsMCwwLjMtMC4xLDAuNC0wLjJjMC4xLTAuMSwwLjItMC4yLDAuMi0wLjRjMC0xLTEuMS0xLTEuMy0xIGMtMC40LDAtMS40LDAtMS40LDEuMmgtMC45YzAtMC40LDAuMS0wLjcsMC4yLTFjMC4xLTAuMiwwLjMtMC40LDAuNS0wLjZjMC4yLTAuMiwwLjUtMC4zLDAuOC0wLjNDMTMuMyw0LDEzLjYsNCwxMy45LDQgYzAuMywwLDAuNSwwLDAuOCwwLjFjMC4zLDAsMC41LDAuMSwwLjcsMC4yYzAuMiwwLjEsMC40LDAuMywwLjUsMC41QzE2LDUsMTYsNS4yLDE2LDUuNnYyLjljMCwwLjIsMCwwLjQsMCwwLjUgYzAsMC4xLDAuMSwwLjIsMC4zLDAuMmMwLjEsMCwwLjIsMCwwLjMsMFY5Ljh6IE0xNS4yLDYuOWMtMS4yLDAuNi0zLjEsMC4yLTMuMSwxLjRjMCwxLjQsMy4xLDEsMy4xLTAuNVY2Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik05IDE2LjE3TDQuODMgMTJsLTEuNDIgMS40MUw5IDE5IDIxIDdsLTEuNDEtMS40MXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-circle-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDJDNi40NyAyIDIgNi40NyAyIDEyczQuNDcgMTAgMTAgMTAgMTAtNC40NyAxMC0xMFMxNy41MyAyIDEyIDJ6bTAgMThjLTQuNDEgMC04LTMuNTktOC04czMuNTktOCA4LTggOCAzLjU5IDggOC0zLjU5IDgtOCA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-circle: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iOSIgY3k9IjkiIHI9IjgiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-clear: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8bWFzayBpZD0iZG9udXRIb2xlIj4KICAgIDxyZWN0IHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgZmlsbD0id2hpdGUiIC8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI4IiBmaWxsPSJibGFjayIvPgogIDwvbWFzaz4KCiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxyZWN0IGhlaWdodD0iMTgiIHdpZHRoPSIyIiB4PSIxMSIgeT0iMyIgdHJhbnNmb3JtPSJyb3RhdGUoMzE1LCAxMiwgMTIpIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIxMCIgbWFzaz0idXJsKCNkb251dEhvbGUpIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-close: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1ub25lIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIGpwLWljb24zLWhvdmVyIiBmaWxsPSJub25lIj4KICAgIDxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjExIi8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIGpwLWljb24tYWNjZW50Mi1ob3ZlciIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMTkgNi40MUwxNy41OSA1IDEyIDEwLjU5IDYuNDEgNSA1IDYuNDEgMTAuNTkgMTIgNSAxNy41OSA2LjQxIDE5IDEyIDEzLjQxIDE3LjU5IDE5IDE5IDE3LjU5IDEzLjQxIDEyeiIvPgogIDwvZz4KCiAgPGcgY2xhc3M9ImpwLWljb24tbm9uZSBqcC1pY29uLWJ1c3kiIGZpbGw9Im5vbmUiPgogICAgPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-code: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTExLjQgMTguNkw2LjggMTRMMTEuNCA5LjRMMTAgOEw0IDE0TDEwIDIwTDExLjQgMTguNlpNMTYuNiAxOC42TDIxLjIgMTRMMTYuNiA5LjRMMTggOEwyNCAxNEwxOCAyMEwxNi42IDE4LjZWMTguNloiLz4KCTwvZz4KPC9zdmc+Cg==);
  --jp-icon-console: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwMCAyMDAiPgogIDxnIGNsYXNzPSJqcC1pY29uLWJyYW5kMSBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMjg4RDEiPgogICAgPHBhdGggZD0iTTIwIDE5LjhoMTYwdjE1OS45SDIweiIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNmZmYiPgogICAgPHBhdGggZD0iTTEwNSAxMjcuM2g0MHYxMi44aC00MHpNNTEuMSA3N0w3NCA5OS45bC0yMy4zIDIzLjMgMTAuNSAxMC41IDIzLjMtMjMuM0w5NSA5OS45IDg0LjUgODkuNCA2MS42IDY2LjV6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-copy: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTExLjksMUgzLjJDMi40LDEsMS43LDEuNywxLjcsMi41djEwLjJoMS41VjIuNWg4LjdWMXogTTE0LjEsMy45aC04Yy0wLjgsMC0xLjUsMC43LTEuNSwxLjV2MTAuMmMwLDAuOCwwLjcsMS41LDEuNSwxLjVoOCBjMC44LDAsMS41LTAuNywxLjUtMS41VjUuNEMxNS41LDQuNiwxNC45LDMuOSwxNC4xLDMuOXogTTE0LjEsMTUuNWgtOFY1LjRoOFYxNS41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-copyright: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDI0IDI0IiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCI+CiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0xMS44OCw5LjE0YzEuMjgsMC4wNiwxLjYxLDEuMTUsMS42MywxLjY2aDEuNzljLTAuMDgtMS45OC0xLjQ5LTMuMTktMy40NS0zLjE5QzkuNjQsNy42MSw4LDksOCwxMi4xNCBjMCwxLjk0LDAuOTMsNC4yNCwzLjg0LDQuMjRjMi4yMiwwLDMuNDEtMS42NSwzLjQ0LTIuOTVoLTEuNzljLTAuMDMsMC41OS0wLjQ1LDEuMzgtMS42MywxLjQ0QzEwLjU1LDE0LjgzLDEwLDEzLjgxLDEwLDEyLjE0IEMxMCw5LjI1LDExLjI4LDkuMTYsMTEuODgsOS4xNHogTTEyLDJDNi40OCwyLDIsNi40OCwyLDEyczQuNDgsMTAsMTAsMTBzMTAtNC40OCwxMC0xMFMxNy41MiwyLDEyLDJ6IE0xMiwyMGMtNC40MSwwLTgtMy41OS04LTggczMuNTktOCw4LThzOCwzLjU5LDgsOFMxNi40MSwyMCwxMiwyMHoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-cut: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkuNjQgNy42NGMuMjMtLjUuMzYtMS4wNS4zNi0xLjY0IDAtMi4yMS0xLjc5LTQtNC00UzIgMy43OSAyIDZzMS43OSA0IDQgNGMuNTkgMCAxLjE0LS4xMyAxLjY0LS4zNkwxMCAxMmwtMi4zNiAyLjM2QzcuMTQgMTQuMTMgNi41OSAxNCA2IDE0Yy0yLjIxIDAtNCAxLjc5LTQgNHMxLjc5IDQgNCA0IDQtMS43OSA0LTRjMC0uNTktLjEzLTEuMTQtLjM2LTEuNjRMMTIgMTRsNyA3aDN2LTFMOS42NCA3LjY0ek02IDhjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTAgMTJjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTYtNy41Yy0uMjggMC0uNS0uMjItLjUtLjVzLjIyLS41LjUtLjUuNS4yMi41LjUtLjIyLjUtLjUuNXpNMTkgM2wtNiA2IDIgMiA3LTdWM3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-download: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDloLTRWM0g5djZINWw3IDcgNy03ek01IDE4djJoMTR2LTJINXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-edit: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMgMTcuMjVWMjFoMy43NUwxNy44MSA5Ljk0bC0zLjc1LTMuNzVMMyAxNy4yNXpNMjAuNzEgNy4wNGMuMzktLjM5LjM5LTEuMDIgMC0xLjQxbC0yLjM0LTIuMzRjLS4zOS0uMzktMS4wMi0uMzktMS40MSAwbC0xLjgzIDEuODMgMy43NSAzLjc1IDEuODMtMS44M3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-ellipses: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iNSIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxOSIgY3k9IjEyIiByPSIyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-extension: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwLjUgMTFIMTlWN2MwLTEuMS0uOS0yLTItMmgtNFYzLjVDMTMgMi4xMiAxMS44OCAxIDEwLjUgMVM4IDIuMTIgOCAzLjVWNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAydjMuOEgzLjVjMS40OSAwIDIuNyAxLjIxIDIuNyAyLjdzLTEuMjEgMi43LTIuNyAyLjdIMlYyMGMwIDEuMS45IDIgMiAyaDMuOHYtMS41YzAtMS40OSAxLjIxLTIuNyAyLjctMi43IDEuNDkgMCAyLjcgMS4yMSAyLjcgMi43VjIySDE3YzEuMSAwIDItLjkgMi0ydi00aDEuNWMxLjM4IDAgMi41LTEuMTIgMi41LTIuNVMyMS44OCAxMSAyMC41IDExeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-fast-forward: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTQgMThsOC41LTZMNCA2djEyem05LTEydjEybDguNS02TDEzIDZ6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-file-upload: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkgMTZoNnYtNmg0bC03LTctNyA3aDR6bS00IDJoMTR2Mkg1eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-file: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuMyA4LjJsLTUuNS01LjVjLS4zLS4zLS43LS41LTEuMi0uNUgzLjljLS44LjEtMS42LjktMS42IDEuOHYxNC4xYzAgLjkuNyAxLjYgMS42IDEuNmgxNC4yYy45IDAgMS42LS43IDEuNi0xLjZWOS40Yy4xLS41LS4xLS45LS40LTEuMnptLTUuOC0zLjNsMy40IDMuNmgtMy40VjQuOXptMy45IDEyLjdINC43Yy0uMSAwLS4yIDAtLjItLjJWNC43YzAtLjIuMS0uMy4yLS4zaDcuMnY0LjRzMCAuOC4zIDEuMWMuMy4zIDEuMS4zIDEuMS4zaDQuM3Y3LjJzLS4xLjItLjIuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-filter-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEwIDE4aDR2LTJoLTR2MnpNMyA2djJoMThWNkgzem0zIDdoMTJ2LTJINnYyeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY4YzAtMS4xLS45LTItMi0yaC04bC0yLTJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-html5: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMDAiIGQ9Ik0xMDguNCAwaDIzdjIyLjhoMjEuMlYwaDIzdjY5aC0yM1Y0NmgtMjF2MjNoLTIzLjJNMjA2IDIzaC0yMC4zVjBoNjMuN3YyM0gyMjl2NDZoLTIzbTUzLjUtNjloMjQuMWwxNC44IDI0LjNMMzEzLjIgMGgyNC4xdjY5aC0yM1YzNC44bC0xNi4xIDI0LjgtMTYuMS0yNC44VjY5aC0yMi42bTg5LjItNjloMjN2NDYuMmgzMi42VjY5aC01NS42Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2U0NGQyNiIgZD0iTTEwNy42IDQ3MWwtMzMtMzcwLjRoMzYyLjhsLTMzIDM3MC4yTDI1NS43IDUxMiIvPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNmMTY1MjkiIGQ9Ik0yNTYgNDgwLjVWMTMxaDE0OC4zTDM3NiA0NDciLz4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNlYmViZWIiIGQ9Ik0xNDIgMTc2LjNoMTE0djQ1LjRoLTY0LjJsNC4yIDQ2LjVoNjB2NDUuM0gxNTQuNG0yIDIyLjhIMjAybDMuMiAzNi4zIDUwLjggMTMuNnY0Ny40bC05My4yLTI2Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIiBkPSJNMzY5LjYgMTc2LjNIMjU1Ljh2NDUuNGgxMDkuNm0tNC4xIDQ2LjVIMjU1Ljh2NDUuNGg1NmwtNS4zIDU5LTUwLjcgMTMuNnY0Ny4ybDkzLTI1LjgiLz4KPC9zdmc+Cg==);
  --jp-icon-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1icmFuZDQganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNGRkYiIGQ9Ik0yLjIgMi4yaDE3LjV2MTcuNUgyLjJ6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzNGNTFCNSIgZD0iTTIuMiAyLjJ2MTcuNWgxNy41bC4xLTE3LjVIMi4yem0xMi4xIDIuMmMxLjIgMCAyLjIgMSAyLjIgMi4ycy0xIDIuMi0yLjIgMi4yLTIuMi0xLTIuMi0yLjIgMS0yLjIgMi4yLTIuMnpNNC40IDE3LjZsMy4zLTguOCAzLjMgNi42IDIuMi0zLjIgNC40IDUuNEg0LjR6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-inspector: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY2YzAtMS4xLS45LTItMi0yem0tNSAxNEg0di00aDExdjR6bTAtNUg0VjloMTF2NHptNSA1aC00VjloNHY5eiIvPgo8L3N2Zz4K);
  --jp-icon-json: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMSBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNGOUE4MjUiPgogICAgPHBhdGggZD0iTTIwLjIgMTEuOGMtMS42IDAtMS43LjUtMS43IDEgMCAuNC4xLjkuMSAxLjMuMS41LjEuOS4xIDEuMyAwIDEuNy0xLjQgMi4zLTMuNSAyLjNoLS45di0xLjloLjVjMS4xIDAgMS40IDAgMS40LS44IDAtLjMgMC0uNi0uMS0xIDAtLjQtLjEtLjgtLjEtMS4yIDAtMS4zIDAtMS44IDEuMy0yLTEuMy0uMi0xLjMtLjctMS4zLTIgMC0uNC4xLS44LjEtMS4yLjEtLjQuMS0uNy4xLTEgMC0uOC0uNC0uNy0xLjQtLjhoLS41VjQuMWguOWMyLjIgMCAzLjUuNyAzLjUgMi4zIDAgLjQtLjEuOS0uMSAxLjMtLjEuNS0uMS45LS4xIDEuMyAwIC41LjIgMSAxLjcgMXYxLjh6TTEuOCAxMC4xYzEuNiAwIDEuNy0uNSAxLjctMSAwLS40LS4xLS45LS4xLTEuMy0uMS0uNS0uMS0uOS0uMS0xLjMgMC0xLjYgMS40LTIuMyAzLjUtMi4zaC45djEuOWgtLjVjLTEgMC0xLjQgMC0xLjQuOCAwIC4zIDAgLjYuMSAxIDAgLjIuMS42LjEgMSAwIDEuMyAwIDEuOC0xLjMgMkM2IDExLjIgNiAxMS43IDYgMTNjMCAuNC0uMS44LS4xIDEuMi0uMS4zLS4xLjctLjEgMSAwIC44LjMuOCAxLjQuOGguNXYxLjloLS45Yy0yLjEgMC0zLjUtLjYtMy41LTIuMyAwLS40LjEtLjkuMS0xLjMuMS0uNS4xLS45LjEtMS4zIDAtLjUtLjItMS0xLjctMXYtMS45eiIvPgogICAgPGNpcmNsZSBjeD0iMTEiIGN5PSIxMy44IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY3g9IjExIiBjeT0iOC4yIiByPSIyLjEiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-julia: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDMyNSAzMDAiPgogIDxnIGNsYXNzPSJqcC1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjY2IzYzMzIj4KICAgIDxwYXRoIGQ9Ik0gMTUwLjg5ODQzOCAyMjUgQyAxNTAuODk4NDM4IDI2Ni40MjE4NzUgMTE3LjMyMDMxMiAzMDAgNzUuODk4NDM4IDMwMCBDIDM0LjQ3NjU2MiAzMDAgMC44OTg0MzggMjY2LjQyMTg3NSAwLjg5ODQzOCAyMjUgQyAwLjg5ODQzOCAxODMuNTc4MTI1IDM0LjQ3NjU2MiAxNTAgNzUuODk4NDM4IDE1MCBDIDExNy4zMjAzMTIgMTUwIDE1MC44OTg0MzggMTgzLjU3ODEyNSAxNTAuODk4NDM4IDIyNSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzM4OTgyNiI+CiAgICA8cGF0aCBkPSJNIDIzNy41IDc1IEMgMjM3LjUgMTE2LjQyMTg3NSAyMDMuOTIxODc1IDE1MCAxNjIuNSAxNTAgQyAxMjEuMDc4MTI1IDE1MCA4Ny41IDExNi40MjE4NzUgODcuNSA3NSBDIDg3LjUgMzMuNTc4MTI1IDEyMS4wNzgxMjUgMCAxNjIuNSAwIEMgMjAzLjkyMTg3NSAwIDIzNy41IDMzLjU3ODEyNSAyMzcuNSA3NSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzk1NThiMiI+CiAgICA8cGF0aCBkPSJNIDMyNC4xMDE1NjIgMjI1IEMgMzI0LjEwMTU2MiAyNjYuNDIxODc1IDI5MC41MjM0MzggMzAwIDI0OS4xMDE1NjIgMzAwIEMgMjA3LjY3OTY4OCAzMDAgMTc0LjEwMTU2MiAyNjYuNDIxODc1IDE3NC4xMDE1NjIgMjI1IEMgMTc0LjEwMTU2MiAxODMuNTc4MTI1IDIwNy42Nzk2ODggMTUwIDI0OS4xMDE1NjIgMTUwIEMgMjkwLjUyMzQzOCAxNTAgMzI0LjEwMTU2MiAxODMuNTc4MTI1IDMyNC4xMDE1NjIgMjI1Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-jupyter-favicon: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTUyIiBoZWlnaHQ9IjE2NSIgdmlld0JveD0iMCAwIDE1MiAxNjUiIHZlcnNpb249IjEuMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA3ODk0NywgMTEwLjU4MjkyNykiIGQ9Ik03NS45NDIyODQyLDI5LjU4MDQ1NjEgQzQzLjMwMjM5NDcsMjkuNTgwNDU2MSAxNC43OTY3ODMyLDE3LjY1MzQ2MzQgMCwwIEM1LjUxMDgzMjExLDE1Ljg0MDY4MjkgMTUuNzgxNTM4OSwyOS41NjY3NzMyIDI5LjM5MDQ5NDcsMzkuMjc4NDE3MSBDNDIuOTk5Nyw0OC45ODk4NTM3IDU5LjI3MzcsNTQuMjA2NzgwNSA3NS45NjA1Nzg5LDU0LjIwNjc4MDUgQzkyLjY0NzQ1NzksNTQuMjA2NzgwNSAxMDguOTIxNDU4LDQ4Ljk4OTg1MzcgMTIyLjUzMDY2MywzOS4yNzg0MTcxIEMxMzYuMTM5NDUzLDI5LjU2Njc3MzIgMTQ2LjQxMDI4NCwxNS44NDA2ODI5IDE1MS45MjExNTgsMCBDMTM3LjA4Nzg2OCwxNy42NTM0NjM0IDEwOC41ODI1ODksMjkuNTgwNDU2MSA3NS45NDIyODQyLDI5LjU4MDQ1NjEgTDc1Ljk0MjI4NDIsMjkuNTgwNDU2MSBaIiAvPgogICAgPHBhdGggdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMzczNjgsIDAuNzA0ODc4KSIgZD0iTTc1Ljk3ODQ1NzksMjQuNjI2NDA3MyBDMTA4LjYxODc2MywyNC42MjY0MDczIDEzNy4xMjQ0NTgsMzYuNTUzNDQxNSAxNTEuOTIxMTU4LDU0LjIwNjc4MDUgQzE0Ni40MTAyODQsMzguMzY2MjIyIDEzNi4xMzk0NTMsMjQuNjQwMTMxNyAxMjIuNTMwNjYzLDE0LjkyODQ4NzggQzEwOC45MjE0NTgsNS4yMTY4NDM5IDkyLjY0NzQ1NzksMCA3NS45NjA1Nzg5LDAgQzU5LjI3MzcsMCA0Mi45OTk3LDUuMjE2ODQzOSAyOS4zOTA0OTQ3LDE0LjkyODQ4NzggQzE1Ljc4MTUzODksMjQuNjQwMTMxNyA1LjUxMDgzMjExLDM4LjM2NjIyMiAwLDU0LjIwNjc4MDUgQzE0LjgzMzA4MTYsMzYuNTg5OTI5MyA0My4zMzg1Njg0LDI0LjYyNjQwNzMgNzUuOTc4NDU3OSwyNC42MjY0MDczIEw3NS45Nzg0NTc5LDI0LjYyNjQwNzMgWiIgLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-jupyter: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzkiIGhlaWdodD0iNTEiIHZpZXdCb3g9IjAgMCAzOSA1MSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMTYzOCAtMjI4MSkiPgogICAgPGcgY2xhc3M9ImpwLWljb24td2FybjAiIGZpbGw9IiNGMzc3MjYiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5Ljc0IDIzMTEuOTgpIiBkPSJNIDE4LjI2NDYgNy4xMzQxMUMgMTAuNDE0NSA3LjEzNDExIDMuNTU4NzIgNC4yNTc2IDAgMEMgMS4zMjUzOSAzLjgyMDQgMy43OTU1NiA3LjEzMDgxIDcuMDY4NiA5LjQ3MzAzQyAxMC4zNDE3IDExLjgxNTIgMTQuMjU1NyAxMy4wNzM0IDE4LjI2OSAxMy4wNzM0QyAyMi4yODIzIDEzLjA3MzQgMjYuMTk2MyAxMS44MTUyIDI5LjQ2OTQgOS40NzMwM0MgMzIuNzQyNCA3LjEzMDgxIDM1LjIxMjYgMy44MjA0IDM2LjUzOCAwQyAzMi45NzA1IDQuMjU3NiAyNi4xMTQ4IDcuMTM0MTEgMTguMjY0NiA3LjEzNDExWiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5LjczIDIyODUuNDgpIiBkPSJNIDE4LjI3MzMgNS45MzkzMUMgMjYuMTIzNSA1LjkzOTMxIDMyLjk3OTMgOC44MTU4MyAzNi41MzggMTMuMDczNEMgMzUuMjEyNiA5LjI1MzAzIDMyLjc0MjQgNS45NDI2MiAyOS40Njk0IDMuNjAwNEMgMjYuMTk2MyAxLjI1ODE4IDIyLjI4MjMgMCAxOC4yNjkgMEMgMTQuMjU1NyAwIDEwLjM0MTcgMS4yNTgxOCA3LjA2ODYgMy42MDA0QyAzLjc5NTU2IDUuOTQyNjIgMS4zMjUzOSA5LjI1MzAzIDAgMTMuMDczNEMgMy41Njc0NSA4LjgyNDYzIDEwLjQyMzIgNS45MzkzMSAxOC4yNzMzIDUuOTM5MzFaIi8+CiAgICA8L2c+CiAgICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjY5LjMgMjI4MS4zMSkiIGQ9Ik0gNS44OTM1MyAyLjg0NEMgNS45MTg4OSAzLjQzMTY1IDUuNzcwODUgNC4wMTM2NyA1LjQ2ODE1IDQuNTE2NDVDIDUuMTY1NDUgNS4wMTkyMiA0LjcyMTY4IDUuNDIwMTUgNC4xOTI5OSA1LjY2ODUxQyAzLjY2NDMgNS45MTY4OCAzLjA3NDQ0IDYuMDAxNTEgMi40OTgwNSA1LjkxMTcxQyAxLjkyMTY2IDUuODIxOSAxLjM4NDYzIDUuNTYxNyAwLjk1NDg5OCA1LjE2NDAxQyAwLjUyNTE3IDQuNzY2MzMgMC4yMjIwNTYgNC4yNDkwMyAwLjA4MzkwMzcgMy42Nzc1N0MgLTAuMDU0MjQ4MyAzLjEwNjExIC0wLjAyMTIzIDIuNTA2MTcgMC4xNzg3ODEgMS45NTM2NEMgMC4zNzg3OTMgMS40MDExIDAuNzM2ODA5IDAuOTIwODE3IDEuMjA3NTQgMC41NzM1MzhDIDEuNjc4MjYgMC4yMjYyNTkgMi4yNDA1NSAwLjAyNzU5MTkgMi44MjMyNiAwLjAwMjY3MjI5QyAzLjYwMzg5IC0wLjAzMDcxMTUgNC4zNjU3MyAwLjI0OTc4OSA0Ljk0MTQyIDAuNzgyNTUxQyA1LjUxNzExIDEuMzE1MzEgNS44NTk1NiAyLjA1Njc2IDUuODkzNTMgMi44NDRaIi8+CiAgICAgIDxwYXRoIHRyYW5zZm9ybT0idHJhbnNsYXRlKDE2MzkuOCAyMzIzLjgxKSIgZD0iTSA3LjQyNzg5IDMuNTgzMzhDIDcuNDYwMDggNC4zMjQzIDcuMjczNTUgNS4wNTgxOSA2Ljg5MTkzIDUuNjkyMTNDIDYuNTEwMzEgNi4zMjYwNyA1Ljk1MDc1IDYuODMxNTYgNS4yODQxMSA3LjE0NDZDIDQuNjE3NDcgNy40NTc2MyAzLjg3MzcxIDcuNTY0MTQgMy4xNDcwMiA3LjQ1MDYzQyAyLjQyMDMyIDcuMzM3MTIgMS43NDMzNiA3LjAwODcgMS4yMDE4NCA2LjUwNjk1QyAwLjY2MDMyOCA2LjAwNTIgMC4yNzg2MSA1LjM1MjY4IDAuMTA1MDE3IDQuNjMyMDJDIC0wLjA2ODU3NTcgMy45MTEzNSAtMC4wMjYyMzYxIDMuMTU0OTQgMC4yMjY2NzUgMi40NTg1NkMgMC40Nzk1ODcgMS43NjIxNyAwLjkzMTY5NyAxLjE1NzEzIDEuNTI1NzYgMC43MjAwMzNDIDIuMTE5ODMgMC4yODI5MzUgMi44MjkxNCAwLjAzMzQzOTUgMy41NjM4OSAwLjAwMzEzMzQ0QyA0LjU0NjY3IC0wLjAzNzQwMzMgNS41MDUyOSAwLjMxNjcwNiA2LjIyOTYxIDAuOTg3ODM1QyA2Ljk1MzkzIDEuNjU4OTYgNy4zODQ4NCAyLjU5MjM1IDcuNDI3ODkgMy41ODMzOEwgNy40Mjc4OSAzLjU4MzM4WiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM4LjM2IDIyODYuMDYpIiBkPSJNIDIuMjc0NzEgNC4zOTYyOUMgMS44NDM2MyA0LjQxNTA4IDEuNDE2NzEgNC4zMDQ0NSAxLjA0Nzk5IDQuMDc4NDNDIDAuNjc5MjY4IDMuODUyNCAwLjM4NTMyOCAzLjUyMTE0IDAuMjAzMzcxIDMuMTI2NTZDIDAuMDIxNDEzNiAyLjczMTk4IC0wLjA0MDM3OTggMi4yOTE4MyAwLjAyNTgxMTYgMS44NjE4MUMgMC4wOTIwMDMxIDEuNDMxOCAwLjI4MzIwNCAxLjAzMTI2IDAuNTc1MjEzIDAuNzEwODgzQyAwLjg2NzIyMiAwLjM5MDUxIDEuMjQ2OTEgMC4xNjQ3MDggMS42NjYyMiAwLjA2MjA1OTJDIDIuMDg1NTMgLTAuMDQwNTg5NyAyLjUyNTYxIC0wLjAxNTQ3MTQgMi45MzA3NiAwLjEzNDIzNUMgMy4zMzU5MSAwLjI4Mzk0MSAzLjY4NzkyIDAuNTUxNTA1IDMuOTQyMjIgMC45MDMwNkMgNC4xOTY1MiAxLjI1NDYyIDQuMzQxNjkgMS42NzQzNiA0LjM1OTM1IDIuMTA5MTZDIDQuMzgyOTkgMi42OTEwNyA0LjE3Njc4IDMuMjU4NjkgMy43ODU5NyAzLjY4NzQ2QyAzLjM5NTE2IDQuMTE2MjQgMi44NTE2NiA0LjM3MTE2IDIuMjc0NzEgNC4zOTYyOUwgMi4yNzQ3MSA0LjM5NjI5WiIvPgogICAgPC9nPgogIDwvZz4+Cjwvc3ZnPgo=);
  --jp-icon-jupyterlab-wordmark: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIHZpZXdCb3g9IjAgMCAxODYwLjggNDc1Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0RTRFNEUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDQ4MC4xMzY0MDEsIDY0LjI3MTQ5MykiPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMDAwMDAsIDU4Ljg3NTU2NikiPgogICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA4NzYwMywgMC4xNDAyOTQpIj4KICAgICAgICA8cGF0aCBkPSJNLTQyNi45LDE2OS44YzAsNDguNy0zLjcsNjQuNy0xMy42LDc2LjRjLTEwLjgsMTAtMjUsMTUuNS0zOS43LDE1LjVsMy43LDI5IGMyMi44LDAuMyw0NC44LTcuOSw2MS45LTIzLjFjMTcuOC0xOC41LDI0LTQ0LjEsMjQtODMuM1YwSC00Mjd2MTcwLjFMLTQyNi45LDE2OS44TC00MjYuOSwxNjkuOHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTU1LjA0NTI5NiwgNTYuODM3MTA0KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuNTYyNDUzLCAxLjc5OTg0MikiPgogICAgICAgIDxwYXRoIGQ9Ik0tMzEyLDE0OGMwLDIxLDAsMzkuNSwxLjcsNTUuNGgtMzEuOGwtMi4xLTMzLjNoLTAuOGMtNi43LDExLjYtMTYuNCwyMS4zLTI4LDI3LjkgYy0xMS42LDYuNi0yNC44LDEwLTM4LjIsOS44Yy0zMS40LDAtNjktMTcuNy02OS04OVYwaDM2LjR2MTEyLjdjMCwzOC43LDExLjYsNjQuNyw0NC42LDY0LjdjMTAuMy0wLjIsMjAuNC0zLjUsMjguOS05LjQgYzguNS01LjksMTUuMS0xNC4zLDE4LjktMjMuOWMyLjItNi4xLDMuMy0xMi41LDMuMy0xOC45VjAuMmgzNi40VjE0OEgtMzEyTC0zMTIsMTQ4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzOTAuMDEzMzIyLCA1My40Nzk2MzgpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS43MDY0NTgsIDAuMjMxNDI1KSI+CiAgICAgICAgPHBhdGggZD0iTS00NzguNiw3MS40YzAtMjYtMC44LTQ3LTEuNy02Ni43aDMyLjdsMS43LDM0LjhoMC44YzcuMS0xMi41LDE3LjUtMjIuOCwzMC4xLTI5LjcgYzEyLjUtNywyNi43LTEwLjMsNDEtOS44YzQ4LjMsMCw4NC43LDQxLjcsODQuNywxMDMuM2MwLDczLjEtNDMuNywxMDkuMi05MSwxMDkuMmMtMTIuMSwwLjUtMjQuMi0yLjItMzUtNy44IGMtMTAuOC01LjYtMTkuOS0xMy45LTI2LjYtMjQuMmgtMC44VjI5MWgtMzZ2LTIyMEwtNDc4LjYsNzEuNEwtNDc4LjYsNzEuNHogTS00NDIuNiwxMjUuNmMwLjEsNS4xLDAuNiwxMC4xLDEuNywxNS4xIGMzLDEyLjMsOS45LDIzLjMsMTkuOCwzMS4xYzkuOSw3LjgsMjIuMSwxMi4xLDM0LjcsMTIuMWMzOC41LDAsNjAuNy0zMS45LDYwLjctNzguNWMwLTQwLjctMjEuMS03NS42LTU5LjUtNzUuNiBjLTEyLjksMC40LTI1LjMsNS4xLTM1LjMsMTMuNGMtOS45LDguMy0xNi45LDE5LjctMTkuNiwzMi40Yy0xLjUsNC45LTIuMywxMC0yLjUsMTUuMVYxMjUuNkwtNDQyLjYsMTI1LjZMLTQ0Mi42LDEyNS42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg2MDYuNzQwNzI2LCA1Ni44MzcxMDQpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC43NTEyMjYsIDEuOTg5Mjk5KSI+CiAgICAgICAgPHBhdGggZD0iTS00NDAuOCwwbDQzLjcsMTIwLjFjNC41LDEzLjQsOS41LDI5LjQsMTIuOCw0MS43aDAuOGMzLjctMTIuMiw3LjktMjcuNywxMi44LTQyLjQgbDM5LjctMTE5LjJoMzguNUwtMzQ2LjksMTQ1Yy0yNiw2OS43LTQzLjcsMTA1LjQtNjguNiwxMjcuMmMtMTIuNSwxMS43LTI3LjksMjAtNDQuNiwyMy45bC05LjEtMzEuMSBjMTEuNy0zLjksMjIuNS0xMC4xLDMxLjgtMTguMWMxMy4yLTExLjEsMjMuNy0yNS4yLDMwLjYtNDEuMmMxLjUtMi44LDIuNS01LjcsMi45LTguOGMtMC4zLTMuMy0xLjItNi42LTIuNS05LjdMLTQ4MC4yLDAuMSBoMzkuN0wtNDQwLjgsMEwtNDQwLjgsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoODIyLjc0ODEwNCwgMC4wMDAwMDApIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS40NjQwNTAsIDAuMzc4OTE0KSI+CiAgICAgICAgPHBhdGggZD0iTS00MTMuNywwdjU4LjNoNTJ2MjguMmgtNTJWMTk2YzAsMjUsNywzOS41LDI3LjMsMzkuNWM3LjEsMC4xLDE0LjItMC43LDIxLjEtMi41IGwxLjcsMjcuN2MtMTAuMywzLjctMjEuMyw1LjQtMzIuMiw1Yy03LjMsMC40LTE0LjYtMC43LTIxLjMtMy40Yy02LjgtMi43LTEyLjktNi44LTE3LjktMTIuMWMtMTAuMy0xMC45LTE0LjEtMjktMTQuMS01Mi45IFY4Ni41aC0zMVY1OC4zaDMxVjkuNkwtNDEzLjcsMEwtNDEzLjcsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOTc0LjQzMzI4NiwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAuOTkwMDM0LCAwLjYxMDMzOSkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDQ1LjgsMTEzYzAuOCw1MCwzMi4yLDcwLjYsNjguNiw3MC42YzE5LDAuNiwzNy45LTMsNTUuMy0xMC41bDYuMiwyNi40IGMtMjAuOSw4LjktNDMuNSwxMy4xLTY2LjIsMTIuNmMtNjEuNSwwLTk4LjMtNDEuMi05OC4zLTEwMi41Qy00ODAuMiw0OC4yLTQ0NC43LDAtMzg2LjUsMGM2NS4yLDAsODIuNyw1OC4zLDgyLjcsOTUuNyBjLTAuMSw1LjgtMC41LDExLjUtMS4yLDE3LjJoLTE0MC42SC00NDUuOEwtNDQ1LjgsMTEzeiBNLTMzOS4yLDg2LjZjMC40LTIzLjUtOS41LTYwLjEtNTAuNC02MC4xIGMtMzYuOCwwLTUyLjgsMzQuNC01NS43LDYwLjFILTMzOS4yTC0zMzkuMiw4Ni42TC0zMzkuMiw4Ni42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMjAxLjk2MTA1OCwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuMTc5NjQwLCAwLjcwNTA2OCkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDc4LjYsNjhjMC0yMy45LTAuNC00NC41LTEuNy02My40aDMxLjhsMS4yLDM5LjloMS43YzkuMS0yNy4zLDMxLTQ0LjUsNTUuMy00NC41IGMzLjUtMC4xLDcsMC40LDEwLjMsMS4ydjM0LjhjLTQuMS0wLjktOC4yLTEuMy0xMi40LTEuMmMtMjUuNiwwLTQzLjcsMTkuNy00OC43LDQ3LjRjLTEsNS43LTEuNiwxMS41LTEuNywxNy4ydjEwOC4zaC0zNlY2OCBMLTQ3OC42LDY4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCBkPSJNMTM1Mi4zLDMyNi4yaDM3VjI4aC0zN1YzMjYuMnogTTE2MDQuOCwzMjYuMmMtMi41LTEzLjktMy40LTMxLjEtMy40LTQ4Ljd2LTc2IGMwLTQwLjctMTUuMS04My4xLTc3LjMtODMuMWMtMjUuNiwwLTUwLDcuMS02Ni44LDE4LjFsOC40LDI0LjRjMTQuMy05LjIsMzQtMTUuMSw1My0xNS4xYzQxLjYsMCw0Ni4yLDMwLjIsNDYuMiw0N3Y0LjIgYy03OC42LTAuNC0xMjIuMywyNi41LTEyMi4zLDc1LjZjMCwyOS40LDIxLDU4LjQsNjIuMiw1OC40YzI5LDAsNTAuOS0xNC4zLDYyLjItMzAuMmgxLjNsMi45LDI1LjZIMTYwNC44eiBNMTU2NS43LDI1Ny43IGMwLDMuOC0wLjgsOC0yLjEsMTEuOGMtNS45LDE3LjItMjIuNywzNC00OS4yLDM0Yy0xOC45LDAtMzQuOS0xMS4zLTM0LjktMzUuM2MwLTM5LjUsNDUuOC00Ni42LDg2LjItNDUuOFYyNTcuN3ogTTE2OTguNSwzMjYuMiBsMS43LTMzLjZoMS4zYzE1LjEsMjYuOSwzOC43LDM4LjIsNjguMSwzOC4yYzQ1LjQsMCw5MS4yLTM2LjEsOTEuMi0xMDguOGMwLjQtNjEuNy0zNS4zLTEwMy43LTg1LjctMTAzLjcgYy0zMi44LDAtNTYuMywxNC43LTY5LjMsMzcuNGgtMC44VjI4aC0zNi42djI0NS43YzAsMTguMS0wLjgsMzguNi0xLjcsNTIuNUgxNjk4LjV6IE0xNzA0LjgsMjA4LjJjMC01LjksMS4zLTEwLjksMi4xLTE1LjEgYzcuNi0yOC4xLDMxLjEtNDUuNCw1Ni4zLTQ1LjRjMzkuNSwwLDYwLjUsMzQuOSw2MC41LDc1LjZjMCw0Ni42LTIzLjEsNzguMS02MS44LDc4LjFjLTI2LjksMC00OC4zLTE3LjYtNTUuNS00My4zIGMtMC44LTQuMi0xLjctOC44LTEuNy0xMy40VjIwOC4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzYxNjE2MSIgZD0iTTE1IDlIOXY2aDZWOXptLTIgNGgtMnYtMmgydjJ6bTgtMlY5aC0yVjdjMC0xLjEtLjktMi0yLTJoLTJWM2gtMnYyaC0yVjNIOXYySDdjLTEuMSAwLTIgLjktMiAydjJIM3YyaDJ2MkgzdjJoMnYyYzAgMS4xLjkgMiAyIDJoMnYyaDJ2LTJoMnYyaDJ2LTJoMmMxLjEgMCAyLS45IDItMnYtMmgydi0yaC0ydi0yaDJ6bS00IDZIN1Y3aDEwdjEweiIvPgo8L3N2Zz4K);
  --jp-icon-keyboard: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMTdjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY3YzAtMS4xLS45LTItMi0yem0tOSAzaDJ2MmgtMlY4em0wIDNoMnYyaC0ydi0yek04IDhoMnYySDhWOHptMCAzaDJ2Mkg4di0yem0tMSAySDV2LTJoMnYyem0wLTNINVY4aDJ2MnptOSA3SDh2LTJoOHYyem0wLTRoLTJ2LTJoMnYyem0wLTNoLTJWOGgydjJ6bTMgM2gtMnYtMmgydjJ6bTAtM2gtMlY4aDJ2MnoiLz4KPC9zdmc+Cg==);
  --jp-icon-launcher: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkgMTlINVY1aDdWM0g1YTIgMiAwIDAwLTIgMnYxNGEyIDIgMCAwMDIgMmgxNGMxLjEgMCAyLS45IDItMnYtN2gtMnY3ek0xNCAzdjJoMy41OWwtOS44MyA5LjgzIDEuNDEgMS40MUwxOSA2LjQxVjEwaDJWM2gtN3oiLz4KPC9zdmc+Cg==);
  --jp-icon-line-form: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGZpbGw9IndoaXRlIiBkPSJNNS44OCA0LjEyTDEzLjc2IDEybC03Ljg4IDcuODhMOCAyMmwxMC0xMEw4IDJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-link: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMuOSAxMmMwLTEuNzEgMS4zOS0zLjEgMy4xLTMuMWg0VjdIN2MtMi43NiAwLTUgMi4yNC01IDVzMi4yNCA1IDUgNWg0di0xLjlIN2MtMS43MSAwLTMuMS0xLjM5LTMuMS0zLjF6TTggMTNoOHYtMkg4djJ6bTktNmgtNHYxLjloNGMxLjcxIDAgMy4xIDEuMzkgMy4xIDMuMXMtMS4zOSAzLjEtMy4xIDMuMWgtNFYxN2g0YzIuNzYgMCA1LTIuMjQgNS01cy0yLjI0LTUtNS01eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xOSA1djE0SDVWNWgxNG0xLjEtMkgzLjljLS41IDAtLjkuNC0uOS45djE2LjJjMCAuNC40LjkuOS45aDE2LjJjLjQgMCAuOS0uNS45LS45VjMuOWMwLS41LS41LS45LS45LS45ek0xMSA3aDZ2MmgtNlY3em0wIDRoNnYyaC02di0yem0wIDRoNnYyaC02ek03IDdoMnYySDd6bTAgNGgydjJIN3ptMCA0aDJ2Mkg3eiIvPgo8L3N2Zz4=);
  --jp-icon-listings-info: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA1MC45NzggNTAuOTc4IiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA1MC45NzggNTAuOTc4OyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+Cgk8Zz4KCQk8cGF0aCBzdHlsZT0iZmlsbDojMDEwMDAyOyIgZD0iTTQzLjUyLDcuNDU4QzM4LjcxMSwyLjY0OCwzMi4zMDcsMCwyNS40ODksMEMxOC42NywwLDEyLjI2NiwyLjY0OCw3LjQ1OCw3LjQ1OAoJCQljLTkuOTQzLDkuOTQxLTkuOTQzLDI2LjExOSwwLDM2LjA2MmM0LjgwOSw0LjgwOSwxMS4yMTIsNy40NTYsMTguMDMxLDcuNDU4YzAsMCwwLjAwMSwwLDAuMDAyLDAKCQkJYzYuODE2LDAsMTMuMjIxLTIuNjQ4LDE4LjAyOS03LjQ1OGM0LjgwOS00LjgwOSw3LjQ1Ny0xMS4yMTIsNy40NTctMTguMDNDNTAuOTc3LDE4LjY3LDQ4LjMyOCwxMi4yNjYsNDMuNTIsNy40NTh6CgkJCSBNNDIuMTA2LDQyLjEwNWMtNC40MzIsNC40MzEtMTAuMzMyLDYuODcyLTE2LjYxNSw2Ljg3MmgtMC4wMDJjLTYuMjg1LTAuMDAxLTEyLjE4Ny0yLjQ0MS0xNi42MTctNi44NzIKCQkJYy05LjE2Mi05LjE2My05LjE2Mi0yNC4wNzEsMC0zMy4yMzNDMTMuMzAzLDQuNDQsMTkuMjA0LDIsMjUuNDg5LDJjNi4yODQsMCwxMi4xODYsMi40NCwxNi42MTcsNi44NzIKCQkJYzQuNDMxLDQuNDMxLDYuODcxLDEwLjMzMiw2Ljg3MSwxNi42MTdDNDguOTc3LDMxLjc3Miw0Ni41MzYsMzcuNjc1LDQyLjEwNiw0Mi4xMDV6Ii8+CgkJPHBhdGggc3R5bGU9ImZpbGw6IzAxMDAwMjsiIGQ9Ik0yMy41NzgsMzIuMjE4Yy0wLjAyMy0xLjczNCwwLjE0My0zLjA1OSwwLjQ5Ni0zLjk3MmMwLjM1My0wLjkxMywxLjExLTEuOTk3LDIuMjcyLTMuMjUzCgkJCWMwLjQ2OC0wLjUzNiwwLjkyMy0xLjA2MiwxLjM2Ny0xLjU3NWMwLjYyNi0wLjc1MywxLjEwNC0xLjQ3OCwxLjQzNi0yLjE3NWMwLjMzMS0wLjcwNywwLjQ5NS0xLjU0MSwwLjQ5NS0yLjUKCQkJYzAtMS4wOTYtMC4yNi0yLjA4OC0wLjc3OS0yLjk3OWMtMC41NjUtMC44NzktMS41MDEtMS4zMzYtMi44MDYtMS4zNjljLTEuODAyLDAuMDU3LTIuOTg1LDAuNjY3LTMuNTUsMS44MzIKCQkJYy0wLjMwMSwwLjUzNS0wLjUwMywxLjE0MS0wLjYwNywxLjgxNGMtMC4xMzksMC43MDctMC4yMDcsMS40MzItMC4yMDcsMi4xNzRoLTIuOTM3Yy0wLjA5MS0yLjIwOCwwLjQwNy00LjExNCwxLjQ5My01LjcxOQoJCQljMS4wNjItMS42NCwyLjg1NS0yLjQ4MSw1LjM3OC0yLjUyN2MyLjE2LDAuMDIzLDMuODc0LDAuNjA4LDUuMTQxLDEuNzU4YzEuMjc4LDEuMTYsMS45MjksMi43NjQsMS45NSw0LjgxMQoJCQljMCwxLjE0Mi0wLjEzNywyLjExMS0wLjQxLDIuOTExYy0wLjMwOSwwLjg0NS0wLjczMSwxLjU5My0xLjI2OCwyLjI0M2MtMC40OTIsMC42NS0xLjA2OCwxLjMxOC0xLjczLDIuMDAyCgkJCWMtMC42NSwwLjY5Ny0xLjMxMywxLjQ3OS0xLjk4NywyLjM0NmMtMC4yMzksMC4zNzctMC40MjksMC43NzctMC41NjUsMS4xOTljLTAuMTYsMC45NTktMC4yMTcsMS45NTEtMC4xNzEsMi45NzkKCQkJQzI2LjU4OSwzMi4yMTgsMjMuNTc4LDMyLjIxOCwyMy41NzgsMzIuMjE4eiBNMjMuNTc4LDM4LjIydi0zLjQ4NGgzLjA3NnYzLjQ4NEgyMy41Nzh6Ii8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-markdown: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjN0IxRkEyIiBkPSJNNSAxNC45aDEybC02LjEgNnptOS40LTYuOGMwLTEuMy0uMS0yLjktLjEtNC41LS40IDEuNC0uOSAyLjktMS4zIDQuM2wtMS4zIDQuM2gtMkw4LjUgNy45Yy0uNC0xLjMtLjctMi45LTEtNC4zLS4xIDEuNi0uMSAzLjItLjIgNC42TDcgMTIuNEg0LjhsLjctMTFoMy4zTDEwIDVjLjQgMS4yLjcgMi43IDEgMy45LjMtMS4yLjctMi42IDEtMy45bDEuMi0zLjdoMy4zbC42IDExaC0yLjRsLS4zLTQuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-new-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwIDZoLThsLTItMkg0Yy0xLjExIDAtMS45OS44OS0xLjk5IDJMMiAxOGMwIDEuMTEuODkgMiAyIDJoMTZjMS4xMSAwIDItLjg5IDItMlY4YzAtMS4xMS0uODktMi0yLTJ6bS0xIDhoLTN2M2gtMnYtM2gtM3YtMmgzVjloMnYzaDN2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-not-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI1IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMTkgMTcuMTg0NCAyLjk2OTY4IDE0LjMwMzIgMS44NjA5NCAxMS40NDA5WiIvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24yIiBzdHJva2U9IiMzMzMzMzMiIHN0cm9rZS13aWR0aD0iMiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOS4zMTU5MiA5LjMyMDMxKSIgZD0iTTcuMzY4NDIgMEwwIDcuMzY0NzkiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDkuMzE1OTIgMTYuNjgzNikgc2NhbGUoMSAtMSkiIGQ9Ik03LjM2ODQyIDBMMCA3LjM2NDc5Ii8+Cjwvc3ZnPgo=);
  --jp-icon-notebook: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNFRjZDMDAiPgogICAgPHBhdGggZD0iTTE4LjcgMy4zdjE1LjRIMy4zVjMuM2gxNS40bTEuNS0xLjVIMS44djE4LjNoMTguM2wuMS0xOC4zeiIvPgogICAgPHBhdGggZD0iTTE2LjUgMTYuNWwtNS40LTQuMy01LjYgNC4zdi0xMWgxMXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-numbering: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTQgMTlINlYxOS41SDVWMjAuNUg2VjIxSDRWMjJIN1YxOEg0VjE5Wk01IDEwSDZWNkg0VjdINVYxMFpNNCAxM0g1LjhMNCAxNS4xVjE2SDdWMTVINS4yTDcgMTIuOVYxMkg0VjEzWk05IDdWOUgyM1Y3SDlaTTkgMjFIMjNWMTlIOVYyMVpNOSAxNUgyM1YxM0g5VjE1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-offline-bolt: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDIuMDJjLTUuNTEgMC05Ljk4IDQuNDctOS45OCA5Ljk4czQuNDcgOS45OCA5Ljk4IDkuOTggOS45OC00LjQ3IDkuOTgtOS45OFMxNy41MSAyLjAyIDEyIDIuMDJ6TTExLjQ4IDIwdi02LjI2SDhMMTMgNHY2LjI2aDMuMzVMMTEuNDggMjB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-palette: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE4IDEzVjIwSDRWNkg5LjAyQzkuMDcgNS4yOSA5LjI0IDQuNjIgOS41IDRINEMyLjkgNCAyIDQuOSAyIDZWMjBDMiAyMS4xIDIuOSAyMiA0IDIySDE4QzE5LjEgMjIgMjAgMjEuMSAyMCAyMFYxNUwxOCAxM1pNMTkuMyA4Ljg5QzE5Ljc0IDguMTkgMjAgNy4zOCAyMCA2LjVDMjAgNC4wMSAxNy45OSAyIDE1LjUgMkMxMy4wMSAyIDExIDQuMDEgMTEgNi41QzExIDguOTkgMTMuMDEgMTEgMTUuNDkgMTFDMTYuMzcgMTEgMTcuMTkgMTAuNzQgMTcuODggMTAuM0wyMSAxMy40MkwyMi40MiAxMkwxOS4zIDguODlaTTE1LjUgOUMxNC4xMiA5IDEzIDcuODggMTMgNi41QzEzIDUuMTIgMTQuMTIgNCAxNS41IDRDMTYuODggNCAxOCA1LjEyIDE4IDYuNUMxOCA3Ljg4IDE2Ljg4IDkgMTUuNSA5WiIvPgogICAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik00IDZIOS4wMTg5NEM5LjAwNjM5IDYuMTY1MDIgOSA2LjMzMTc2IDkgNi41QzkgOC44MTU3NyAxMC4yMTEgMTAuODQ4NyAxMi4wMzQzIDEySDlWMTRIMTZWMTIuOTgxMUMxNi41NzAzIDEyLjkzNzcgMTcuMTIgMTIuODIwNyAxNy42Mzk2IDEyLjYzOTZMMTggMTNWMjBINFY2Wk04IDhINlYxMEg4VjhaTTYgMTJIOFYxNEg2VjEyWk04IDE2SDZWMThIOFYxNlpNOSAxNkgxNlYxOEg5VjE2WiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-paste: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE5IDJoLTQuMThDMTQuNC44NCAxMy4zIDAgMTIgMGMtMS4zIDAtMi40Ljg0LTIuODIgMkg1Yy0xLjEgMC0yIC45LTIgMnYxNmMwIDEuMS45IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjRjMC0xLjEtLjktMi0yLTJ6bS03IDBjLjU1IDAgMSAuNDUgMSAxcy0uNDUgMS0xIDEtMS0uNDUtMS0xIC40NS0xIDEtMXptNyAxOEg1VjRoMnYzaDEwVjRoMnYxNnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-pdf: url(data:image/svg+xml;base64,PHN2ZwogICB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyMiAyMiIgd2lkdGg9IjE2Ij4KICAgIDxwYXRoIHRyYW5zZm9ybT0icm90YXRlKDQ1KSIgY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI0ZGMkEyQSIKICAgICAgIGQ9Im0gMjIuMzQ0MzY5LC0zLjAxNjM2NDIgaCA1LjYzODYwNCB2IDEuNTc5MjQzMyBoIC0zLjU0OTIyNyB2IDEuNTA4NjkyOTkgaCAzLjMzNzU3NiBWIDEuNjUwODE1NCBoIC0zLjMzNzU3NiB2IDMuNDM1MjYxMyBoIC0yLjA4OTM3NyB6IG0gLTcuMTM2NDQ0LDEuNTc5MjQzMyB2IDQuOTQzOTU0MyBoIDAuNzQ4OTIgcSAxLjI4MDc2MSwwIDEuOTUzNzAzLC0wLjYzNDk1MzUgMC42NzgzNjksLTAuNjM0OTUzNSAwLjY3ODM2OSwtMS44NDUxNjQxIDAsLTEuMjA0NzgzNTUgLTAuNjcyOTQyLC0xLjgzNDMxMDExIC0wLjY3Mjk0MiwtMC42Mjk1MjY1OSAtMS45NTkxMywtMC42Mjk1MjY1OSB6IG0gLTIuMDg5Mzc3LC0xLjU3OTI0MzMgaCAyLjIwMzM0MyBxIDEuODQ1MTY0LDAgMi43NDYwMzksMC4yNjU5MjA3IDAuOTA2MzAxLDAuMjYwNDkzNyAxLjU1MjEwOCwwLjg5MDAyMDMgMC41Njk4MywwLjU0ODEyMjMgMC44NDY2MDUsMS4yNjQ0ODAwNiAwLjI3Njc3NCwwLjcxNjM1NzgxIDAuMjc2Nzc0LDEuNjIyNjU4OTQgMCwwLjkxNzE1NTEgLTAuMjc2Nzc0LDEuNjM4OTM5OSAtMC4yNzY3NzUsMC43MTYzNTc4IC0wLjg0NjYwNSwxLjI2NDQ4IC0wLjY1MTIzNCwwLjYyOTUyNjYgLTEuNTYyOTYyLDAuODk1NDQ3MyAtMC45MTE3MjgsMC4yNjA0OTM3IC0yLjczNTE4NSwwLjI2MDQ5MzcgaCAtMi4yMDMzNDMgeiBtIC04LjE0NTg1NjUsMCBoIDMuNDY3ODIzIHEgMS41NDY2ODE2LDAgMi4zNzE1Nzg1LDAuNjg5MjIzIDAuODMwMzI0LDAuNjgzNzk2MSAwLjgzMDMyNCwxLjk1MzcwMzE0IDAsMS4yNzUzMzM5NyAtMC44MzAzMjQsMS45NjQ1NTcwNiBRIDkuOTg3MTk2MSwyLjI3NDkxNSA4LjQ0MDUxNDUsMi4yNzQ5MTUgSCA3LjA2MjA2ODQgViA1LjA4NjA3NjcgSCA0Ljk3MjY5MTUgWiBtIDIuMDg5Mzc2OSwxLjUxNDExOTkgdiAyLjI2MzAzOTQzIGggMS4xNTU5NDEgcSAwLjYwNzgxODgsMCAwLjkzODg2MjksLTAuMjkzMDU1NDcgMC4zMzEwNDQxLC0wLjI5ODQ4MjQxIDAuMzMxMDQ0MSwtMC44NDExNzc3MiAwLC0wLjU0MjY5NTMxIC0wLjMzMTA0NDEsLTAuODM1NzUwNzQgLTAuMzMxMDQ0MSwtMC4yOTMwNTU1IC0wLjkzODg2MjksLTAuMjkzMDU1NSB6IgovPgo8L3N2Zz4K);
  --jp-icon-python: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMEQ0N0ExIj4KICAgIDxwYXRoIGQ9Ik0xMS4xIDYuOVY1LjhINi45YzAtLjUgMC0xLjMuMi0xLjYuNC0uNy44LTEuMSAxLjctMS40IDEuNy0uMyAyLjUtLjMgMy45LS4xIDEgLjEgMS45LjkgMS45IDEuOXY0LjJjMCAuNS0uOSAxLjYtMiAxLjZIOC44Yy0xLjUgMC0yLjQgMS40LTIuNCAyLjh2Mi4ySDQuN0MzLjUgMTUuMSAzIDE0IDMgMTMuMVY5Yy0uMS0xIC42LTIgMS44LTIgMS41LS4xIDYuMy0uMSA2LjMtLjF6Ii8+CiAgICA8cGF0aCBkPSJNMTAuOSAxNS4xdjEuMWg0LjJjMCAuNSAwIDEuMy0uMiAxLjYtLjQuNy0uOCAxLjEtMS43IDEuNC0xLjcuMy0yLjUuMy0zLjkuMS0xLS4xLTEuOS0uOS0xLjktMS45di00LjJjMC0uNS45LTEuNiAyLTEuNmgzLjhjMS41IDAgMi40LTEuNCAyLjQtMi44VjYuNmgxLjdDMTguNSA2LjkgMTkgOCAxOSA4LjlWMTNjMCAxLS43IDIuMS0xLjkgMi4xaC02LjJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-r-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjE5NkYzIiBkPSJNNC40IDIuNWMxLjItLjEgMi45LS4zIDQuOS0uMyAyLjUgMCA0LjEuNCA1LjIgMS4zIDEgLjcgMS41IDEuOSAxLjUgMy41IDAgMi0xLjQgMy41LTIuOSA0LjEgMS4yLjQgMS43IDEuNiAyLjIgMyAuNiAxLjkgMSAzLjkgMS4zIDQuNmgtMy44Yy0uMy0uNC0uOC0xLjctMS4yLTMuN3MtMS4yLTIuNi0yLjYtMi42aC0uOXY2LjRINC40VjIuNXptMy43IDYuOWgxLjRjMS45IDAgMi45LS45IDIuOS0yLjNzLTEtMi4zLTIuOC0yLjNjLS43IDAtMS4zIDAtMS42LjJ2NC41aC4xdi0uMXoiLz4KPC9zdmc+Cg==);
  --jp-icon-react: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMTUwIDE1MCA1NDEuOSAyOTUuMyI+CiAgPGcgY2xhc3M9ImpwLWljb24tYnJhbmQyIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxREFGQiI+CiAgICA8cGF0aCBkPSJNNjY2LjMgMjk2LjVjMC0zMi41LTQwLjctNjMuMy0xMDMuMS04Mi40IDE0LjQtNjMuNiA4LTExNC4yLTIwLjItMTMwLjQtNi41LTMuOC0xNC4xLTUuNi0yMi40LTUuNnYyMi4zYzQuNiAwIDguMy45IDExLjQgMi42IDEzLjYgNy44IDE5LjUgMzcuNSAxNC45IDc1LjctMS4xIDkuNC0yLjkgMTkuMy01LjEgMjkuNC0xOS42LTQuOC00MS04LjUtNjMuNS0xMC45LTEzLjUtMTguNS0yNy41LTM1LjMtNDEuNi01MCAzMi42LTMwLjMgNjMuMi00Ni45IDg0LTQ2LjlWNzhjLTI3LjUgMC02My41IDE5LjYtOTkuOSA1My42LTM2LjQtMzMuOC03Mi40LTUzLjItOTkuOS01My4ydjIyLjNjMjAuNyAwIDUxLjQgMTYuNSA4NCA0Ni42LTE0IDE0LjctMjggMzEuNC00MS4zIDQ5LjktMjIuNiAyLjQtNDQgNi4xLTYzLjYgMTEtMi4zLTEwLTQtMTkuNy01LjItMjktNC43LTM4LjIgMS4xLTY3LjkgMTQuNi03NS44IDMtMS44IDYuOS0yLjYgMTEuNS0yLjZWNzguNWMtOC40IDAtMTYgMS44LTIyLjYgNS42LTI4LjEgMTYuMi0zNC40IDY2LjctMTkuOSAxMzAuMS02Mi4yIDE5LjItMTAyLjcgNDkuOS0xMDIuNyA4Mi4zIDAgMzIuNSA0MC43IDYzLjMgMTAzLjEgODIuNC0xNC40IDYzLjYtOCAxMTQuMiAyMC4yIDEzMC40IDYuNSAzLjggMTQuMSA1LjYgMjIuNSA1LjYgMjcuNSAwIDYzLjUtMTkuNiA5OS45LTUzLjYgMzYuNCAzMy44IDcyLjQgNTMuMiA5OS45IDUzLjIgOC40IDAgMTYtMS44IDIyLjYtNS42IDI4LjEtMTYuMiAzNC40LTY2LjcgMTkuOS0xMzAuMSA2Mi0xOS4xIDEwMi41LTQ5LjkgMTAyLjUtODIuM3ptLTEzMC4yLTY2LjdjLTMuNyAxMi45LTguMyAyNi4yLTEzLjUgMzkuNS00LjEtOC04LjQtMTYtMTMuMS0yNC00LjYtOC05LjUtMTUuOC0xNC40LTIzLjQgMTQuMiAyLjEgMjcuOSA0LjcgNDEgNy45em0tNDUuOCAxMDYuNWMtNy44IDEzLjUtMTUuOCAyNi4zLTI0LjEgMzguMi0xNC45IDEuMy0zMCAyLTQ1LjIgMi0xNS4xIDAtMzAuMi0uNy00NS0xLjktOC4zLTExLjktMTYuNC0yNC42LTI0LjItMzgtNy42LTEzLjEtMTQuNS0yNi40LTIwLjgtMzkuOCA2LjItMTMuNCAxMy4yLTI2LjggMjAuNy0zOS45IDcuOC0xMy41IDE1LjgtMjYuMyAyNC4xLTM4LjIgMTQuOS0xLjMgMzAtMiA0NS4yLTIgMTUuMSAwIDMwLjIuNyA0NSAxLjkgOC4zIDExLjkgMTYuNCAyNC42IDI0LjIgMzggNy42IDEzLjEgMTQuNSAyNi40IDIwLjggMzkuOC02LjMgMTMuNC0xMy4yIDI2LjgtMjAuNyAzOS45em0zMi4zLTEzYzUuNCAxMy40IDEwIDI2LjggMTMuOCAzOS44LTEzLjEgMy4yLTI2LjkgNS45LTQxLjIgOCA0LjktNy43IDkuOC0xNS42IDE0LjQtMjMuNyA0LjYtOCA4LjktMTYuMSAxMy0yNC4xek00MjEuMiA0MzBjLTkuMy05LjYtMTguNi0yMC4zLTI3LjgtMzIgOSAuNCAxOC4yLjcgMjcuNS43IDkuNCAwIDE4LjctLjIgMjcuOC0uNy05IDExLjctMTguMyAyMi40LTI3LjUgMzJ6bS03NC40LTU4LjljLTE0LjItMi4xLTI3LjktNC43LTQxLTcuOSAzLjctMTIuOSA4LjMtMjYuMiAxMy41LTM5LjUgNC4xIDggOC40IDE2IDEzLjEgMjQgNC43IDggOS41IDE1LjggMTQuNCAyMy40ek00MjAuNyAxNjNjOS4zIDkuNiAxOC42IDIwLjMgMjcuOCAzMi05LS40LTE4LjItLjctMjcuNS0uNy05LjQgMC0xOC43LjItMjcuOC43IDktMTEuNyAxOC4zLTIyLjQgMjcuNS0zMnptLTc0IDU4LjljLTQuOSA3LjctOS44IDE1LjYtMTQuNCAyMy43LTQuNiA4LTguOSAxNi0xMyAyNC01LjQtMTMuNC0xMC0yNi44LTEzLjgtMzkuOCAxMy4xLTMuMSAyNi45LTUuOCA0MS4yLTcuOXptLTkwLjUgMTI1LjJjLTM1LjQtMTUuMS01OC4zLTM0LjktNTguMy01MC42IDAtMTUuNyAyMi45LTM1LjYgNTguMy01MC42IDguNi0zLjcgMTgtNyAyNy43LTEwLjEgNS43IDE5LjYgMTMuMiA0MCAyMi41IDYwLjktOS4yIDIwLjgtMTYuNiA0MS4xLTIyLjIgNjAuNi05LjktMy4xLTE5LjMtNi41LTI4LTEwLjJ6TTMxMCA0OTBjLTEzLjYtNy44LTE5LjUtMzcuNS0xNC45LTc1LjcgMS4xLTkuNCAyLjktMTkuMyA1LjEtMjkuNCAxOS42IDQuOCA0MSA4LjUgNjMuNSAxMC45IDEzLjUgMTguNSAyNy41IDM1LjMgNDEuNiA1MC0zMi42IDMwLjMtNjMuMiA0Ni45LTg0IDQ2LjktNC41LS4xLTguMy0xLTExLjMtMi43em0yMzcuMi03Ni4yYzQuNyAzOC4yLTEuMSA2Ny45LTE0LjYgNzUuOC0zIDEuOC02LjkgMi42LTExLjUgMi42LTIwLjcgMC01MS40LTE2LjUtODQtNDYuNiAxNC0xNC43IDI4LTMxLjQgNDEuMy00OS45IDIyLjYtMi40IDQ0LTYuMSA2My42LTExIDIuMyAxMC4xIDQuMSAxOS44IDUuMiAyOS4xem0zOC41LTY2LjdjLTguNiAzLjctMTggNy0yNy43IDEwLjEtNS43LTE5LjYtMTMuMi00MC0yMi41LTYwLjkgOS4yLTIwLjggMTYuNi00MS4xIDIyLjItNjAuNiA5LjkgMy4xIDE5LjMgNi41IDI4LjEgMTAuMiAzNS40IDE1LjEgNTguMyAzNC45IDU4LjMgNTAuNi0uMSAxNS43LTIzIDM1LjYtNTguNCA1MC42ek0zMjAuOCA3OC40eiIvPgogICAgPGNpcmNsZSBjeD0iNDIwLjkiIGN5PSIyOTYuNSIgcj0iNDUuNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-redo: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTE4LjQgMTAuNkMxNi41NSA4Ljk5IDE0LjE1IDggMTEuNSA4Yy00LjY1IDAtOC41OCAzLjAzLTkuOTYgNy4yMkwzLjkgMTZjMS4wNS0zLjE5IDQuMDUtNS41IDcuNi01LjUgMS45NSAwIDMuNzMuNzIgNS4xMiAxLjg4TDEzIDE2aDlWN2wtMy42IDMuNnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-refresh: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTkgMTMuNWMtMi40OSAwLTQuNS0yLjAxLTQuNS00LjVTNi41MSA0LjUgOSA0LjVjMS4yNCAwIDIuMzYuNTIgMy4xNyAxLjMzTDEwIDhoNVYzbC0xLjc2IDEuNzZDMTIuMTUgMy42OCAxMC42NiAzIDkgMyA1LjY5IDMgMy4wMSA1LjY5IDMuMDEgOVM1LjY5IDE1IDkgMTVjMi45NyAwIDUuNDMtMi4xNiA1LjktNWgtMS41MmMtLjQ2IDItMi4yNCAzLjUtNC4zOCAzLjV6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-regex: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiBmaWxsPSIjRkZGIj4KICAgIDxjaXJjbGUgY2xhc3M9InN0MiIgY3g9IjUuNSIgY3k9IjE0LjUiIHI9IjEuNSIvPgogICAgPHJlY3QgeD0iMTIiIHk9IjQiIGNsYXNzPSJzdDIiIHdpZHRoPSIxIiBoZWlnaHQ9IjgiLz4KICAgIDxyZWN0IHg9IjguNSIgeT0iNy41IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjg2NiAtMC41IDAuNSAwLjg2NiAtMi4zMjU1IDcuMzIxOSkiIGNsYXNzPSJzdDIiIHdpZHRoPSI4IiBoZWlnaHQ9IjEiLz4KICAgIDxyZWN0IHg9IjEyIiB5PSI0IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjUgLTAuODY2IDAuODY2IDAuNSAtMC42Nzc5IDE0LjgyNTIpIiBjbGFzcz0ic3QyIiB3aWR0aD0iMSIgaGVpZ2h0PSI4Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-run: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTggNXYxNGwxMS03eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-running: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMjU2IDhDMTE5IDggOCAxMTkgOCAyNTZzMTExIDI0OCAyNDggMjQ4IDI0OC0xMTEgMjQ4LTI0OFMzOTMgOCAyNTYgOHptOTYgMzI4YzAgOC44LTcuMiAxNi0xNiAxNkgxNzZjLTguOCAwLTE2LTcuMi0xNi0xNlYxNzZjMC04LjggNy4yLTE2IDE2LTE2aDE2MGM4LjggMCAxNiA3LjIgMTYgMTZ2MTYweiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-save: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE3IDNINWMtMS4xMSAwLTIgLjktMiAydjE0YzAgMS4xLjg5IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjdsLTQtNHptLTUgMTZjLTEuNjYgMC0zLTEuMzQtMy0zczEuMzQtMyAzLTMgMyAxLjM0IDMgMy0xLjM0IDMtMyAzem0zLTEwSDVWNWgxMHY0eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-search: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjEsMTAuOWgtMC43bC0wLjItMC4yYzAuOC0wLjksMS4zLTIuMiwxLjMtMy41YzAtMy0yLjQtNS40LTUuNC01LjRTMS44LDQuMiwxLjgsNy4xczIuNCw1LjQsNS40LDUuNCBjMS4zLDAsMi41LTAuNSwzLjUtMS4zbDAuMiwwLjJ2MC43bDQuMSw0LjFsMS4yLTEuMkwxMi4xLDEwLjl6IE03LjEsMTAuOWMtMi4xLDAtMy43LTEuNy0zLjctMy43czEuNy0zLjcsMy43LTMuN3MzLjcsMS43LDMuNywzLjcgUzkuMiwxMC45LDcuMSwxMC45eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-settings: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuNDMgMTIuOThjLjA0LS4zMi4wNy0uNjQuMDctLjk4cy0uMDMtLjY2LS4wNy0uOThsMi4xMS0xLjY1Yy4xOS0uMTUuMjQtLjQyLjEyLS42NGwtMi0zLjQ2Yy0uMTItLjIyLS4zOS0uMy0uNjEtLjIybC0yLjQ5IDFjLS41Mi0uNC0xLjA4LS43My0xLjY5LS45OGwtLjM4LTIuNjVBLjQ4OC40ODggMCAwMDE0IDJoLTRjLS4yNSAwLS40Ni4xOC0uNDkuNDJsLS4zOCAyLjY1Yy0uNjEuMjUtMS4xNy41OS0xLjY5Ljk4bC0yLjQ5LTFjLS4yMy0uMDktLjQ5IDAtLjYxLjIybC0yIDMuNDZjLS4xMy4yMi0uMDcuNDkuMTIuNjRsMi4xMSAxLjY1Yy0uMDQuMzItLjA3LjY1LS4wNy45OHMuMDMuNjYuMDcuOThsLTIuMTEgMS42NWMtLjE5LjE1LS4yNC40Mi0uMTIuNjRsMiAzLjQ2Yy4xMi4yMi4zOS4zLjYxLjIybDIuNDktMWMuNTIuNCAxLjA4LjczIDEuNjkuOThsLjM4IDIuNjVjLjAzLjI0LjI0LjQyLjQ5LjQyaDRjLjI1IDAgLjQ2LS4xOC40OS0uNDJsLjM4LTIuNjVjLjYxLS4yNSAxLjE3LS41OSAxLjY5LS45OGwyLjQ5IDFjLjIzLjA5LjQ5IDAgLjYxLS4yMmwyLTMuNDZjLjEyLS4yMi4wNy0uNDktLjEyLS42NGwtMi4xMS0xLjY1ek0xMiAxNS41Yy0xLjkzIDAtMy41LTEuNTctMy41LTMuNXMxLjU3LTMuNSAzLjUtMy41IDMuNSAxLjU3IDMuNSAzLjUtMS41NyAzLjUtMy41IDMuNXoiLz4KPC9zdmc+Cg==);
  --jp-icon-spreadsheet: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNENBRjUwIiBkPSJNMi4yIDIuMnYxNy42aDE3LjZWMi4ySDIuMnptMTUuNCA3LjdoLTUuNVY0LjRoNS41djUuNXpNOS45IDQuNHY1LjVINC40VjQuNGg1LjV6bS01LjUgNy43aDUuNXY1LjVINC40di01LjV6bTcuNyA1LjV2LTUuNWg1LjV2NS41aC01LjV6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-stop: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik02IDZoMTJ2MTJINnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tab: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIxIDNIM2MtMS4xIDAtMiAuOS0yIDJ2MTRjMCAxLjEuOSAyIDIgMmgxOGMxLjEgMCAyLS45IDItMlY1YzAtMS4xLS45LTItMi0yem0wIDE2SDNWNWgxMHY0aDh2MTB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-table-rows: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMSw4SDNWNGgxOFY4eiBNMjEsMTBIM3Y0aDE4VjEweiBNMjEsMTZIM3Y0aDE4VjE2eiIvPgogICAgPC9nPgo8L3N2Zz4=);
  --jp-icon-tag: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjgiIGhlaWdodD0iMjgiIHZpZXdCb3g9IjAgMCA0MyAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTI4LjgzMzIgMTIuMzM0TDMyLjk5OTggMTYuNTAwN0wzNy4xNjY1IDEyLjMzNEgyOC44MzMyWiIvPgoJCTxwYXRoIGQ9Ik0xNi4yMDk1IDIxLjYxMDRDMTUuNjg3MyAyMi4xMjk5IDE0Ljg0NDMgMjIuMTI5OSAxNC4zMjQ4IDIxLjYxMDRMNi45ODI5IDE0LjcyNDVDNi41NzI0IDE0LjMzOTQgNi4wODMxMyAxMy42MDk4IDYuMDQ3ODYgMTMuMDQ4MkM1Ljk1MzQ3IDExLjUyODggNi4wMjAwMiA4LjYxOTQ0IDYuMDY2MjEgNy4wNzY5NUM2LjA4MjgxIDYuNTE0NzcgNi41NTU0OCA2LjA0MzQ3IDcuMTE4MDQgNi4wMzA1NUM5LjA4ODYzIDUuOTg0NzMgMTMuMjYzOCA1LjkzNTc5IDEzLjY1MTggNi4zMjQyNUwyMS43MzY5IDEzLjYzOUMyMi4yNTYgMTQuMTU4NSAyMS43ODUxIDE1LjQ3MjQgMjEuMjYyIDE1Ljk5NDZMMTYuMjA5NSAyMS42MTA0Wk05Ljc3NTg1IDguMjY1QzkuMzM1NTEgNy44MjU2NiA4LjYyMzUxIDcuODI1NjYgOC4xODI4IDguMjY1QzcuNzQzNDYgOC43MDU3MSA3Ljc0MzQ2IDkuNDE3MzMgOC4xODI4IDkuODU2NjdDOC42MjM4MiAxMC4yOTY0IDkuMzM1ODIgMTAuMjk2NCA5Ljc3NTg1IDkuODU2NjdDMTAuMjE1NiA5LjQxNzMzIDEwLjIxNTYgOC43MDUzMyA5Ljc3NTg1IDguMjY1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-terminal: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0IiA+CiAgICA8cmVjdCBjbGFzcz0ianAtaWNvbjIganAtaWNvbi1zZWxlY3RhYmxlIiB3aWR0aD0iMjAiIGhlaWdodD0iMjAiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMikiIGZpbGw9IiMzMzMzMzMiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uLWFjY2VudDIganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGQ9Ik01LjA1NjY0IDguNzYxNzJDNS4wNTY2NCA4LjU5NzY2IDUuMDMxMjUgOC40NTMxMiA0Ljk4MDQ3IDguMzI4MTJDNC45MzM1OSA4LjE5OTIyIDQuODU1NDcgOC4wODIwMyA0Ljc0NjA5IDcuOTc2NTZDNC42NDA2MiA3Ljg3MTA5IDQuNSA3Ljc3NTM5IDQuMzI0MjIgNy42ODk0NUM0LjE1MjM0IDcuNTk5NjEgMy45NDMzNiA3LjUxMTcyIDMuNjk3MjcgNy40MjU3OEMzLjMwMjczIDcuMjg1MTYgMi45NDMzNiA3LjEzNjcyIDIuNjE5MTQgNi45ODA0N0MyLjI5NDkyIDYuODI0MjIgMi4wMTc1OCA2LjY0MjU4IDEuNzg3MTEgNi40MzU1NUMxLjU2MDU1IDYuMjI4NTIgMS4zODQ3NyA1Ljk4ODI4IDEuMjU5NzcgNS43MTQ4NEMxLjEzNDc3IDUuNDM3NSAxLjA3MjI3IDUuMTA5MzggMS4wNzIyNyA0LjczMDQ3QzEuMDcyMjcgNC4zOTg0NCAxLjEyODkxIDQuMDk1NyAxLjI0MjE5IDMuODIyMjdDMS4zNTU0NyAzLjU0NDkyIDEuNTE1NjIgMy4zMDQ2OSAxLjcyMjY2IDMuMTAxNTZDMS45Mjk2OSAyLjg5ODQ0IDIuMTc5NjkgMi43MzQzNyAyLjQ3MjY2IDIuNjA5MzhDMi43NjU2MiAyLjQ4NDM4IDMuMDkxOCAyLjQwNDMgMy40NTExNyAyLjM2OTE0VjEuMTA5MzhINC4zODg2N1YyLjM4MDg2QzQuNzQwMjMgMi40Mjc3MyA1LjA1NjY0IDIuNTIzNDQgNS4zMzc4OSAyLjY2Nzk3QzUuNjE5MTQgMi44MTI1IDUuODU3NDIgMy4wMDE5NSA2LjA1MjczIDMuMjM2MzNDNi4yNTE5NSAzLjQ2NjggNi40MDQzIDMuNzQwMjMgNi41MDk3NyA0LjA1NjY0QzYuNjE5MTQgNC4zNjkxNCA2LjY3MzgzIDQuNzIwNyA2LjY3MzgzIDUuMTExMzNINS4wNDQ5MkM1LjA0NDkyIDQuNjM4NjcgNC45Mzc1IDQuMjgxMjUgNC43MjI2NiA0LjAzOTA2QzQuNTA3ODEgMy43OTI5NyA0LjIxNjggMy42Njk5MiAzLjg0OTYxIDMuNjY5OTJDMy42NTAzOSAzLjY2OTkyIDMuNDc2NTYgMy42OTcyNyAzLjMyODEyIDMuNzUxOTVDMy4xODM1OSAzLjgwMjczIDMuMDY0NDUgMy44NzY5NSAyLjk3MDcgMy45NzQ2MUMyLjg3Njk1IDQuMDY4MzYgMi44MDY2NCA0LjE3OTY5IDIuNzU5NzcgNC4zMDg1OUMyLjcxNjggNC40Mzc1IDIuNjk1MzEgNC41NzgxMiAyLjY5NTMxIDQuNzMwNDdDMi42OTUzMSA0Ljg4MjgxIDIuNzE2OCA1LjAxOTUzIDIuNzU5NzcgNS4xNDA2MkMyLjgwNjY0IDUuMjU3ODEgMi44ODI4MSA1LjM2NzE5IDIuOTg4MjggNS40Njg3NUMzLjA5NzY2IDUuNTcwMzEgMy4yNDAyMyA1LjY2Nzk3IDMuNDE2MDIgNS43NjE3MkMzLjU5MTggNS44NTE1NiAzLjgxMDU1IDUuOTQzMzYgNC4wNzIyNyA2LjAzNzExQzQuNDY2OCA2LjE4NTU1IDQuODI0MjIgNi4zMzk4NCA1LjE0NDUzIDYuNUM1LjQ2NDg0IDYuNjU2MjUgNS43MzgyOCA2LjgzOTg0IDUuOTY0ODQgNy4wNTA3OEM2LjE5NTMxIDcuMjU3ODEgNi4zNzEwOSA3LjUgNi40OTIxOSA3Ljc3NzM0QzYuNjE3MTkgOC4wNTA3OCA2LjY3OTY5IDguMzc1IDYuNjc5NjkgOC43NUM2LjY3OTY5IDkuMDkzNzUgNi42MjMwNSA5LjQwNDMgNi41MDk3NyA5LjY4MTY0QzYuMzk2NDggOS45NTUwOCA2LjIzNDM4IDEwLjE5MTQgNi4wMjM0NCAxMC4zOTA2QzUuODEyNSAxMC41ODk4IDUuNTU4NTkgMTAuNzUgNS4yNjE3MiAxMC44NzExQzQuOTY0ODQgMTAuOTg4MyA0LjYzMjgxIDExLjA2NDUgNC4yNjU2MiAxMS4wOTk2VjEyLjI0OEgzLjMzMzk4VjExLjA5OTZDMy4wMDE5NSAxMS4wNjg0IDIuNjc5NjkgMTAuOTk2MSAyLjM2NzE5IDEwLjg4MjhDMi4wNTQ2OSAxMC43NjU2IDEuNzc3MzQgMTAuNTk3NyAxLjUzNTE2IDEwLjM3ODlDMS4yOTY4OCAxMC4xNjAyIDEuMTA1NDcgOS44ODQ3NyAwLjk2MDkzOCA5LjU1MjczQzAuODE2NDA2IDkuMjE2OCAwLjc0NDE0MSA4LjgxNDQ1IDAuNzQ0MTQxIDguMzQ1N0gyLjM3ODkxQzIuMzc4OTEgOC42MjY5NSAyLjQxOTkyIDguODYzMjggMi41MDE5NSA5LjA1NDY5QzIuNTgzOTggOS4yNDIxOSAyLjY4OTQ1IDkuMzkyNTggMi44MTgzNiA5LjUwNTg2QzIuOTUxMTcgOS42MTUyMyAzLjEwMTU2IDkuNjkzMzYgMy4yNjk1MyA5Ljc0MDIzQzMuNDM3NSA5Ljc4NzExIDMuNjA5MzggOS44MTA1NSAzLjc4NTE2IDkuODEwNTVDNC4yMDMxMiA5LjgxMDU1IDQuNTE5NTMgOS43MTI4OSA0LjczNDM4IDkuNTE3NThDNC45NDkyMiA5LjMyMjI3IDUuMDU2NjQgOS4wNzAzMSA1LjA1NjY0IDguNzYxNzJaTTEzLjQxOCAxMi4yNzE1SDguMDc0MjJWMTFIMTMuNDE4VjEyLjI3MTVaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzLjk1MjY0IDYpIiBmaWxsPSJ3aGl0ZSIvPgo8L3N2Zz4K);
  --jp-icon-text-editor: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTUgMTVIM3YyaDEydi0yem0wLThIM3YyaDEyVjd6TTMgMTNoMTh2LTJIM3Yyem0wIDhoMTh2LTJIM3Yyek0zIDN2MmgxOFYzSDN6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-toc: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik03LDVIMjFWN0g3VjVNNywxM1YxMUgyMVYxM0g3TTQsNC41QTEuNSwxLjUgMCAwLDEgNS41LDZBMS41LDEuNSAwIDAsMSA0LDcuNUExLjUsMS41IDAgMCwxIDIuNSw2QTEuNSwxLjUgMCAwLDEgNCw0LjVNNCwxMC41QTEuNSwxLjUgMCAwLDEgNS41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMy41QTEuNSwxLjUgMCAwLDEgMi41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMC41TTcsMTlWMTdIMjFWMTlIN000LDE2LjVBMS41LDEuNSAwIDAsMSA1LjUsMThBMS41LDEuNSAwIDAsMSA0LDE5LjVBMS41LDEuNSAwIDAsMSAyLjUsMThBMS41LDEuNSAwIDAsMSA0LDE2LjVaIiAvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tree-view: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMiAxMVYzaC03djNIOVYzSDJ2OGg3VjhoMnYxMGg0djNoN3YtOGgtN3YzaC0yVjhoMnYzeiIvPgogICAgPC9nPgo8L3N2Zz4=);
  --jp-icon-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMiAxNy4xODQ0IDIuOTY5NjggMTQuMzAzMiAxLjg2MDk0IDExLjQ0MDlaIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiMzMzMzMzMiIHN0cm9rZT0iIzMzMzMzMyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOCA5Ljg2NzE5KSIgZD0iTTIuODYwMTUgNC44NjUzNUwwLjcyNjU0OSAyLjk5OTU5TDAgMy42MzA0NUwyLjg2MDE1IDYuMTMxNTdMOCAwLjYzMDg3Mkw3LjI3ODU3IDBMMi44NjAxNSA0Ljg2NTM1WiIvPgo8L3N2Zz4K);
  --jp-icon-undo: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjUgOGMtMi42NSAwLTUuMDUuOTktNi45IDIuNkwyIDd2OWg5bC0zLjYyLTMuNjJjMS4zOS0xLjE2IDMuMTYtMS44OCA1LjEyLTEuODggMy41NCAwIDYuNTUgMi4zMSA3LjYgNS41bDIuMzctLjc4QzIxLjA4IDExLjAzIDE3LjE1IDggMTIuNSA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-vega: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbjEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjEyMTIxIj4KICAgIDxwYXRoIGQ9Ik0xMC42IDUuNGwyLjItMy4ySDIuMnY3LjNsNC02LjZ6Ii8+CiAgICA8cGF0aCBkPSJNMTUuOCAyLjJsLTQuNCA2LjZMNyA2LjNsLTQuOCA4djUuNWgxNy42VjIuMmgtNHptLTcgMTUuNEg1LjV2LTQuNGgzLjN2NC40em00LjQgMEg5LjhWOS44aDMuNHY3Ljh6bTQuNCAwaC0zLjRWNi41aDMuNHYxMS4xeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-yaml: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1jb250cmFzdDIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjRDgxQjYwIj4KICAgIDxwYXRoIGQ9Ik03LjIgMTguNnYtNS40TDMgNS42aDMuM2wxLjQgMy4xYy4zLjkuNiAxLjYgMSAyLjUuMy0uOC42LTEuNiAxLTIuNWwxLjQtMy4xaDMuNGwtNC40IDcuNnY1LjVsLTIuOS0uMXoiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxNi41IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxMSIgcj0iMi4xIi8+CiAgPC9nPgo8L3N2Zz4K);
}

/* Icon CSS class declarations */

.jp-AddIcon {
  background-image: var(--jp-icon-add);
}
.jp-BugIcon {
  background-image: var(--jp-icon-bug);
}
.jp-BuildIcon {
  background-image: var(--jp-icon-build);
}
.jp-CaretDownEmptyIcon {
  background-image: var(--jp-icon-caret-down-empty);
}
.jp-CaretDownEmptyThinIcon {
  background-image: var(--jp-icon-caret-down-empty-thin);
}
.jp-CaretDownIcon {
  background-image: var(--jp-icon-caret-down);
}
.jp-CaretLeftIcon {
  background-image: var(--jp-icon-caret-left);
}
.jp-CaretRightIcon {
  background-image: var(--jp-icon-caret-right);
}
.jp-CaretUpEmptyThinIcon {
  background-image: var(--jp-icon-caret-up-empty-thin);
}
.jp-CaretUpIcon {
  background-image: var(--jp-icon-caret-up);
}
.jp-CaseSensitiveIcon {
  background-image: var(--jp-icon-case-sensitive);
}
.jp-CheckIcon {
  background-image: var(--jp-icon-check);
}
.jp-CircleEmptyIcon {
  background-image: var(--jp-icon-circle-empty);
}
.jp-CircleIcon {
  background-image: var(--jp-icon-circle);
}
.jp-ClearIcon {
  background-image: var(--jp-icon-clear);
}
.jp-CloseIcon {
  background-image: var(--jp-icon-close);
}
.jp-CodeIcon {
  background-image: var(--jp-icon-code);
}
.jp-ConsoleIcon {
  background-image: var(--jp-icon-console);
}
.jp-CopyIcon {
  background-image: var(--jp-icon-copy);
}
.jp-CopyrightIcon {
  background-image: var(--jp-icon-copyright);
}
.jp-CutIcon {
  background-image: var(--jp-icon-cut);
}
.jp-DownloadIcon {
  background-image: var(--jp-icon-download);
}
.jp-EditIcon {
  background-image: var(--jp-icon-edit);
}
.jp-EllipsesIcon {
  background-image: var(--jp-icon-ellipses);
}
.jp-ExtensionIcon {
  background-image: var(--jp-icon-extension);
}
.jp-FastForwardIcon {
  background-image: var(--jp-icon-fast-forward);
}
.jp-FileIcon {
  background-image: var(--jp-icon-file);
}
.jp-FileUploadIcon {
  background-image: var(--jp-icon-file-upload);
}
.jp-FilterListIcon {
  background-image: var(--jp-icon-filter-list);
}
.jp-FolderIcon {
  background-image: var(--jp-icon-folder);
}
.jp-Html5Icon {
  background-image: var(--jp-icon-html5);
}
.jp-ImageIcon {
  background-image: var(--jp-icon-image);
}
.jp-InspectorIcon {
  background-image: var(--jp-icon-inspector);
}
.jp-JsonIcon {
  background-image: var(--jp-icon-json);
}
.jp-JuliaIcon {
  background-image: var(--jp-icon-julia);
}
.jp-JupyterFaviconIcon {
  background-image: var(--jp-icon-jupyter-favicon);
}
.jp-JupyterIcon {
  background-image: var(--jp-icon-jupyter);
}
.jp-JupyterlabWordmarkIcon {
  background-image: var(--jp-icon-jupyterlab-wordmark);
}
.jp-KernelIcon {
  background-image: var(--jp-icon-kernel);
}
.jp-KeyboardIcon {
  background-image: var(--jp-icon-keyboard);
}
.jp-LauncherIcon {
  background-image: var(--jp-icon-launcher);
}
.jp-LineFormIcon {
  background-image: var(--jp-icon-line-form);
}
.jp-LinkIcon {
  background-image: var(--jp-icon-link);
}
.jp-ListIcon {
  background-image: var(--jp-icon-list);
}
.jp-ListingsInfoIcon {
  background-image: var(--jp-icon-listings-info);
}
.jp-MarkdownIcon {
  background-image: var(--jp-icon-markdown);
}
.jp-NewFolderIcon {
  background-image: var(--jp-icon-new-folder);
}
.jp-NotTrustedIcon {
  background-image: var(--jp-icon-not-trusted);
}
.jp-NotebookIcon {
  background-image: var(--jp-icon-notebook);
}
.jp-NumberingIcon {
  background-image: var(--jp-icon-numbering);
}
.jp-OfflineBoltIcon {
  background-image: var(--jp-icon-offline-bolt);
}
.jp-PaletteIcon {
  background-image: var(--jp-icon-palette);
}
.jp-PasteIcon {
  background-image: var(--jp-icon-paste);
}
.jp-PdfIcon {
  background-image: var(--jp-icon-pdf);
}
.jp-PythonIcon {
  background-image: var(--jp-icon-python);
}
.jp-RKernelIcon {
  background-image: var(--jp-icon-r-kernel);
}
.jp-ReactIcon {
  background-image: var(--jp-icon-react);
}
.jp-RedoIcon {
  background-image: var(--jp-icon-redo);
}
.jp-RefreshIcon {
  background-image: var(--jp-icon-refresh);
}
.jp-RegexIcon {
  background-image: var(--jp-icon-regex);
}
.jp-RunIcon {
  background-image: var(--jp-icon-run);
}
.jp-RunningIcon {
  background-image: var(--jp-icon-running);
}
.jp-SaveIcon {
  background-image: var(--jp-icon-save);
}
.jp-SearchIcon {
  background-image: var(--jp-icon-search);
}
.jp-SettingsIcon {
  background-image: var(--jp-icon-settings);
}
.jp-SpreadsheetIcon {
  background-image: var(--jp-icon-spreadsheet);
}
.jp-StopIcon {
  background-image: var(--jp-icon-stop);
}
.jp-TabIcon {
  background-image: var(--jp-icon-tab);
}
.jp-TableRowsIcon {
  background-image: var(--jp-icon-table-rows);
}
.jp-TagIcon {
  background-image: var(--jp-icon-tag);
}
.jp-TerminalIcon {
  background-image: var(--jp-icon-terminal);
}
.jp-TextEditorIcon {
  background-image: var(--jp-icon-text-editor);
}
.jp-TocIcon {
  background-image: var(--jp-icon-toc);
}
.jp-TreeViewIcon {
  background-image: var(--jp-icon-tree-view);
}
.jp-TrustedIcon {
  background-image: var(--jp-icon-trusted);
}
.jp-UndoIcon {
  background-image: var(--jp-icon-undo);
}
.jp-VegaIcon {
  background-image: var(--jp-icon-vega);
}
.jp-YamlIcon {
  background-image: var(--jp-icon-yaml);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

.jp-Icon,
.jp-MaterialIcon {
  background-position: center;
  background-repeat: no-repeat;
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-cover {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/**
 * (DEPRECATED) Support for specific CSS icon sizes
 */

.jp-Icon-16 {
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-18 {
  background-size: 18px;
  min-width: 18px;
  min-height: 18px;
}

.jp-Icon-20 {
  background-size: 20px;
  min-width: 20px;
  min-height: 20px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for icons as inline SVG HTMLElements
 */

/* recolor the primary elements of an icon */
.jp-icon0[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon1[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon2[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon3[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}
/* recolor the accent elements of an icon */
.jp-icon-accent0[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-accent1[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-accent2[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-accent3[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-accent4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-accent0[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-accent1[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-accent2[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-accent3[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-accent4[stroke] {
  stroke: var(--jp-layout-color4);
}
/* set the color of an icon to transparent */
.jp-icon-none[fill] {
  fill: none;
}

.jp-icon-none[stroke] {
  stroke: none;
}
/* brand icon colors. Same for light and dark */
.jp-icon-brand0[fill] {
  fill: var(--jp-brand-color0);
}
.jp-icon-brand1[fill] {
  fill: var(--jp-brand-color1);
}
.jp-icon-brand2[fill] {
  fill: var(--jp-brand-color2);
}
.jp-icon-brand3[fill] {
  fill: var(--jp-brand-color3);
}
.jp-icon-brand4[fill] {
  fill: var(--jp-brand-color4);
}

.jp-icon-brand0[stroke] {
  stroke: var(--jp-brand-color0);
}
.jp-icon-brand1[stroke] {
  stroke: var(--jp-brand-color1);
}
.jp-icon-brand2[stroke] {
  stroke: var(--jp-brand-color2);
}
.jp-icon-brand3[stroke] {
  stroke: var(--jp-brand-color3);
}
.jp-icon-brand4[stroke] {
  stroke: var(--jp-brand-color4);
}
/* warn icon colors. Same for light and dark */
.jp-icon-warn0[fill] {
  fill: var(--jp-warn-color0);
}
.jp-icon-warn1[fill] {
  fill: var(--jp-warn-color1);
}
.jp-icon-warn2[fill] {
  fill: var(--jp-warn-color2);
}
.jp-icon-warn3[fill] {
  fill: var(--jp-warn-color3);
}

.jp-icon-warn0[stroke] {
  stroke: var(--jp-warn-color0);
}
.jp-icon-warn1[stroke] {
  stroke: var(--jp-warn-color1);
}
.jp-icon-warn2[stroke] {
  stroke: var(--jp-warn-color2);
}
.jp-icon-warn3[stroke] {
  stroke: var(--jp-warn-color3);
}
/* icon colors that contrast well with each other and most backgrounds */
.jp-icon-contrast0[fill] {
  fill: var(--jp-icon-contrast-color0);
}
.jp-icon-contrast1[fill] {
  fill: var(--jp-icon-contrast-color1);
}
.jp-icon-contrast2[fill] {
  fill: var(--jp-icon-contrast-color2);
}
.jp-icon-contrast3[fill] {
  fill: var(--jp-icon-contrast-color3);
}

.jp-icon-contrast0[stroke] {
  stroke: var(--jp-icon-contrast-color0);
}
.jp-icon-contrast1[stroke] {
  stroke: var(--jp-icon-contrast-color1);
}
.jp-icon-contrast2[stroke] {
  stroke: var(--jp-icon-contrast-color2);
}
.jp-icon-contrast3[stroke] {
  stroke: var(--jp-icon-contrast-color3);
}

/* CSS for icons in selected items in the settings editor */
#setting-editor .jp-PluginList .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}
#setting-editor
  .jp-PluginList
  .jp-mod-selected
  .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* CSS for icons in selected filebrowser listing items */
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* CSS for icons in selected tabs in the sidebar tab manager */
#tab-manager .lm-TabBar-tab.jp-mod-active .jp-icon-selectable[fill] {
  fill: #fff;
}

#tab-manager .lm-TabBar-tab.jp-mod-active .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}
#tab-manager
  .lm-TabBar-tab.jp-mod-active
  .jp-icon-hover
  :hover
  .jp-icon-selectable[fill] {
  fill: var(--jp-brand-color1);
}

#tab-manager
  .lm-TabBar-tab.jp-mod-active
  .jp-icon-hover
  :hover
  .jp-icon-selectable-inverse[fill] {
  fill: #fff;
}

/**
 * TODO: come up with non css-hack solution for showing the busy icon on top
 *  of the close icon
 * CSS for complex behavior of close icon of tabs in the sidebar tab manager
 */
#tab-manager
  .lm-TabBar-tab.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}
#tab-manager
  .lm-TabBar-tab.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

#tab-manager
  .lm-TabBar-tab.jp-mod-dirty.jp-mod-active
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: #fff;
}

/**
* TODO: come up with non css-hack solution for showing the busy icon on top
*  of the close icon
* CSS for complex behavior of close icon of tabs in the main area tabbar
*/
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

/* CSS for icons in status bar */
#jp-main-statusbar .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

#jp-main-statusbar .jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}
/* special handling for splash icon CSS. While the theme CSS reloads during
   splash, the splash icon can loose theming. To prevent that, we set a
   default for its color variable */
:root {
  --jp-warn-color0: var(--md-orange-700);
}

/* not sure what to do with this one, used in filebrowser listing */
.jp-DragIcon {
  margin-right: 4px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for alt colors for icons as inline SVG HTMLElements
 */

/* alt recolor the primary elements of an icon */
.jp-icon-alt .jp-icon0[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-alt .jp-icon1[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-alt .jp-icon2[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-alt .jp-icon3[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-alt .jp-icon4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-alt .jp-icon0[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-alt .jp-icon1[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-alt .jp-icon2[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-alt .jp-icon3[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-alt .jp-icon4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* alt recolor the accent elements of an icon */
.jp-icon-alt .jp-icon-accent0[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-alt .jp-icon-accent1[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-alt .jp-icon-accent2[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-alt .jp-icon-accent3[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-alt .jp-icon-accent4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-alt .jp-icon-accent0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-alt .jp-icon-accent1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-alt .jp-icon-accent2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-alt .jp-icon-accent3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-alt .jp-icon-accent4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-icon-hoverShow:not(:hover) svg {
  display: none !important;
}

/**
 * Support for hover colors for icons as inline SVG HTMLElements
 */

/**
 * regular colors
 */

/* recolor the primary elements of an icon */
.jp-icon-hover :hover .jp-icon0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-hover :hover .jp-icon1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-hover :hover .jp-icon2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-hover :hover .jp-icon3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-hover :hover .jp-icon4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-hover :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-hover :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-hover :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-hover :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-hover :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-hover :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-hover :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-hover :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-hover :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-hover :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-hover :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-hover :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-hover :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-hover :hover .jp-icon-none-hover[fill] {
  fill: none;
}

.jp-icon-hover :hover .jp-icon-none-hover[stroke] {
  stroke: none;
}

/**
 * inverse colors
 */

/* inverse recolor the primary elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[fill] {
  fill: var(--jp-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[fill] {
  fill: var(--jp-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[fill] {
  fill: var(--jp-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[fill] {
  fill: var(--jp-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* inverse recolor the accent elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-switch {
  display: flex;
  align-items: center;
  padding-left: 4px;
  padding-right: 4px;
  font-size: var(--jp-ui-font-size1);
  background-color: transparent;
  color: var(--jp-ui-font-color1);
  border: none;
  height: 20px;
}

.jp-switch:hover {
  background-color: var(--jp-layout-color2);
}

.jp-switch-label {
  margin-right: 5px;
}

.jp-switch-track {
  cursor: pointer;
  background-color: var(--jp-border-color1);
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 34px;
  height: 16px;
  width: 35px;
  position: relative;
}

.jp-switch-track::before {
  content: '';
  position: absolute;
  height: 10px;
  width: 10px;
  margin: 3px;
  left: 0px;
  background-color: var(--jp-ui-inverse-font-color1);
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 50%;
}

.jp-switch[aria-checked='true'] .jp-switch-track {
  background-color: var(--jp-warn-color0);
}

.jp-switch[aria-checked='true'] .jp-switch-track::before {
  /* track width (35) - margins (3 + 3) - thumb width (10) */
  left: 19px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* Sibling imports */

/* Override Blueprint's _reset.scss styles */
html {
  box-sizing: unset;
}

*,
*::before,
*::after {
  box-sizing: unset;
}

body {
  color: unset;
  font-family: var(--jp-ui-font-family);
}

p {
  margin-top: unset;
  margin-bottom: unset;
}

small {
  font-size: unset;
}

strong {
  font-weight: unset;
}

/* Override Blueprint's _typography.scss styles */
a {
  text-decoration: unset;
  color: unset;
}
a:hover {
  text-decoration: unset;
  color: unset;
}

/* Override Blueprint's _accessibility.scss styles */
:focus {
  outline: unset;
  outline-offset: unset;
  -moz-outline-radius: unset;
}

/* Styles for ui-components */
.jp-Button {
  border-radius: var(--jp-border-radius);
  padding: 0px 12px;
  font-size: var(--jp-ui-font-size1);
}

/* Use our own theme for hover styles */
button.jp-Button.bp3-button.bp3-minimal:hover {
  background-color: var(--jp-layout-color2);
}
.jp-Button.minimal {
  color: unset !important;
}

.jp-Button.jp-ToolbarButtonComponent {
  text-transform: none;
}

.jp-InputGroup input {
  box-sizing: border-box;
  border-radius: 0;
  background-color: transparent;
  color: var(--jp-ui-font-color0);
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.jp-InputGroup input:focus {
  box-shadow: inset 0 0 0 var(--jp-border-width)
      var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-InputGroup input::placeholder,
input::placeholder {
  color: var(--jp-ui-font-color3);
}

.jp-BPIcon {
  display: inline-block;
  vertical-align: middle;
  margin: auto;
}

/* Stop blueprint futzing with our icon fills */
.bp3-icon.jp-BPIcon > svg:not([fill]) {
  fill: var(--jp-inverse-layout-color3);
}

.jp-InputGroupAction {
  padding: 6px;
}

.jp-HTMLSelect.jp-DefaultStyle select {
  background-color: initial;
  border: none;
  border-radius: 0;
  box-shadow: none;
  color: var(--jp-ui-font-color0);
  display: block;
  font-size: var(--jp-ui-font-size1);
  height: 24px;
  line-height: 14px;
  padding: 0 25px 0 10px;
  text-align: left;
  -moz-appearance: none;
  -webkit-appearance: none;
}

/* Use our own theme for hover and option styles */
.jp-HTMLSelect.jp-DefaultStyle select:hover,
.jp-HTMLSelect.jp-DefaultStyle select > option {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color0);
}
select {
  box-sizing: border-box;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapse {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-top: 1px solid var(--jp-border-color2);
  border-bottom: 1px solid var(--jp-border-color2);
}

.jp-Collapse-header {
  padding: 1px 12px;
  color: var(--jp-ui-font-color1);
  background-color: var(--jp-layout-color1);
  font-size: var(--jp-ui-font-size2);
}

.jp-Collapse-header:hover {
  background-color: var(--jp-layout-color2);
}

.jp-Collapse-contents {
  padding: 0px 12px 0px 12px;
  background-color: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-commandpalette-search-height: 28px;
}

/*-----------------------------------------------------------------------------
| Overall styles
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  padding-bottom: 0px;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Modal variant
|----------------------------------------------------------------------------*/

.jp-ModalCommandPalette {
  position: absolute;
  z-index: 10000;
  top: 38px;
  left: 30%;
  margin: 0;
  padding: 4px;
  width: 40%;
  box-shadow: var(--jp-elevation-z4);
  border-radius: 4px;
  background: var(--jp-layout-color0);
}

.jp-ModalCommandPalette .lm-CommandPalette {
  max-height: 40vh;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-close-icon::after {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-header {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-item {
  margin-left: 4px;
  margin-right: 4px;
}

.jp-ModalCommandPalette
  .lm-CommandPalette
  .lm-CommandPalette-item.lm-mod-disabled {
  display: none;
}

/*-----------------------------------------------------------------------------
| Search
|----------------------------------------------------------------------------*/

.lm-CommandPalette-search {
  padding: 4px;
  background-color: var(--jp-layout-color1);
  z-index: 2;
}

.lm-CommandPalette-wrapper {
  overflow: overlay;
  padding: 0px 9px;
  background-color: var(--jp-input-active-background);
  height: 30px;
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.lm-CommandPalette.lm-mod-focused .lm-CommandPalette-wrapper {
  box-shadow: inset 0 0 0 1px var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-SearchIconGroup {
  color: white;
  background-color: var(--jp-brand-color1);
  position: absolute;
  top: 4px;
  right: 4px;
  padding: 5px 5px 1px 5px;
}

.jp-SearchIconGroup svg {
  height: 20px;
  width: 20px;
}

.jp-SearchIconGroup .jp-icon3[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-input {
  background: transparent;
  width: calc(100% - 18px);
  float: left;
  border: none;
  outline: none;
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  line-height: var(--jp-private-commandpalette-search-height);
}

.lm-CommandPalette-input::-webkit-input-placeholder,
.lm-CommandPalette-input::-moz-placeholder,
.lm-CommandPalette-input:-ms-input-placeholder {
  color: var(--jp-ui-font-color2);
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Results
|----------------------------------------------------------------------------*/

.lm-CommandPalette-header:first-child {
  margin-top: 0px;
}

.lm-CommandPalette-header {
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin-top: 8px;
  padding: 8px 0 8px 12px;
  text-transform: uppercase;
}

.lm-CommandPalette-header.lm-mod-active {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-header > mark {
  background-color: transparent;
  font-weight: bold;
  color: var(--jp-ui-font-color1);
}

.lm-CommandPalette-item {
  padding: 4px 12px 4px 4px;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  font-weight: 400;
  display: flex;
}

.lm-CommandPalette-item.lm-mod-disabled {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item.lm-mod-active {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item.lm-mod-active .lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-inverse-font-color0);
}

.lm-CommandPalette-item.lm-mod-active .jp-icon-selectable[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-item.lm-mod-active .lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-inverse-font-color0);
}

.lm-CommandPalette-item.lm-mod-active:hover:not(.lm-mod-disabled) {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item:hover:not(.lm-mod-active):not(.lm-mod-disabled) {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-itemContent {
  overflow: hidden;
}

.lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.lm-CommandPalette-item.lm-mod-disabled mark {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item .lm-CommandPalette-itemIcon {
  margin: 0 4px 0 0;
  position: relative;
  width: 16px;
  top: 2px;
  flex: 0 0 auto;
}

.lm-CommandPalette-item.lm-mod-disabled .lm-CommandPalette-itemIcon {
  opacity: 0.6;
}

.lm-CommandPalette-item .lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemCaption {
  display: none;
}

.lm-CommandPalette-content {
  background-color: var(--jp-layout-color1);
}

.lm-CommandPalette-content:empty:after {
  content: 'No results';
  margin: auto;
  margin-top: 20px;
  width: 100px;
  display: block;
  font-size: var(--jp-ui-font-size2);
  font-family: var(--jp-ui-font-family);
  font-weight: lighter;
}

.lm-CommandPalette-emptyMessage {
  text-align: center;
  margin-top: 24px;
  line-height: 1.32;
  padding: 0px 8px;
  color: var(--jp-content-font-color3);
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Dialog {
  position: absolute;
  z-index: 10000;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  top: 0px;
  left: 0px;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-dialog-background);
}

.jp-Dialog-content {
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
  background: var(--jp-layout-color1);
  padding: 24px;
  padding-bottom: 12px;
  min-width: 300px;
  min-height: 150px;
  max-width: 1000px;
  max-height: 500px;
  box-sizing: border-box;
  box-shadow: var(--jp-elevation-z20);
  word-wrap: break-word;
  border-radius: var(--jp-border-radius);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color1);
  resize: both;
}

.jp-Dialog-button {
  overflow: visible;
}

button.jp-Dialog-button:focus {
  outline: 1px solid var(--jp-brand-color1);
  outline-offset: 4px;
  -moz-outline-radius: 0px;
}

button.jp-Dialog-button:focus::-moz-focus-inner {
  border: 0;
}

button.jp-Dialog-close-button {
  padding: 0;
  height: 100%;
  min-width: unset;
  min-height: unset;
}

.jp-Dialog-header {
  display: flex;
  justify-content: space-between;
  flex: 0 0 auto;
  padding-bottom: 12px;
  font-size: var(--jp-ui-font-size3);
  font-weight: 400;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-body {
  display: flex;
  flex-direction: column;
  flex: 1 1 auto;
  font-size: var(--jp-ui-font-size1);
  background: var(--jp-layout-color1);
  overflow: auto;
}

.jp-Dialog-footer {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  flex: 0 0 auto;
  margin-left: -12px;
  margin-right: -12px;
  padding: 12px;
}

.jp-Dialog-title {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.jp-Dialog-body > .jp-select-wrapper {
  width: 100%;
}

.jp-Dialog-body > button {
  padding: 0px 16px;
}

.jp-Dialog-body > label {
  line-height: 1.4;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-button.jp-mod-styled:not(:last-child) {
  margin-right: 12px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-HoverBox {
  position: fixed;
}

.jp-HoverBox.jp-mod-outofview {
  display: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-IFrame {
  width: 100%;
  height: 100%;
}

.jp-IFrame > iframe {
  border: none;
}

/*
When drag events occur, `p-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-IFrame {
  position: relative;
}

body.lm-mod-override-cursor .jp-IFrame:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

.jp-Input-Boolean-Dialog {
  flex-direction: row-reverse;
  align-items: end;
  width: 100%;
}

.jp-Input-Boolean-Dialog > label {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MainAreaWidget > :focus {
  outline: none;
}

/**
 * google-material-color v1.2.6
 * https://github.com/danlevan/google-material-color
 */
:root {
  --md-red-50: #ffebee;
  --md-red-100: #ffcdd2;
  --md-red-200: #ef9a9a;
  --md-red-300: #e57373;
  --md-red-400: #ef5350;
  --md-red-500: #f44336;
  --md-red-600: #e53935;
  --md-red-700: #d32f2f;
  --md-red-800: #c62828;
  --md-red-900: #b71c1c;
  --md-red-A100: #ff8a80;
  --md-red-A200: #ff5252;
  --md-red-A400: #ff1744;
  --md-red-A700: #d50000;

  --md-pink-50: #fce4ec;
  --md-pink-100: #f8bbd0;
  --md-pink-200: #f48fb1;
  --md-pink-300: #f06292;
  --md-pink-400: #ec407a;
  --md-pink-500: #e91e63;
  --md-pink-600: #d81b60;
  --md-pink-700: #c2185b;
  --md-pink-800: #ad1457;
  --md-pink-900: #880e4f;
  --md-pink-A100: #ff80ab;
  --md-pink-A200: #ff4081;
  --md-pink-A400: #f50057;
  --md-pink-A700: #c51162;

  --md-purple-50: #f3e5f5;
  --md-purple-100: #e1bee7;
  --md-purple-200: #ce93d8;
  --md-purple-300: #ba68c8;
  --md-purple-400: #ab47bc;
  --md-purple-500: #9c27b0;
  --md-purple-600: #8e24aa;
  --md-purple-700: #7b1fa2;
  --md-purple-800: #6a1b9a;
  --md-purple-900: #4a148c;
  --md-purple-A100: #ea80fc;
  --md-purple-A200: #e040fb;
  --md-purple-A400: #d500f9;
  --md-purple-A700: #aa00ff;

  --md-deep-purple-50: #ede7f6;
  --md-deep-purple-100: #d1c4e9;
  --md-deep-purple-200: #b39ddb;
  --md-deep-purple-300: #9575cd;
  --md-deep-purple-400: #7e57c2;
  --md-deep-purple-500: #673ab7;
  --md-deep-purple-600: #5e35b1;
  --md-deep-purple-700: #512da8;
  --md-deep-purple-800: #4527a0;
  --md-deep-purple-900: #311b92;
  --md-deep-purple-A100: #b388ff;
  --md-deep-purple-A200: #7c4dff;
  --md-deep-purple-A400: #651fff;
  --md-deep-purple-A700: #6200ea;

  --md-indigo-50: #e8eaf6;
  --md-indigo-100: #c5cae9;
  --md-indigo-200: #9fa8da;
  --md-indigo-300: #7986cb;
  --md-indigo-400: #5c6bc0;
  --md-indigo-500: #3f51b5;
  --md-indigo-600: #3949ab;
  --md-indigo-700: #303f9f;
  --md-indigo-800: #283593;
  --md-indigo-900: #1a237e;
  --md-indigo-A100: #8c9eff;
  --md-indigo-A200: #536dfe;
  --md-indigo-A400: #3d5afe;
  --md-indigo-A700: #304ffe;

  --md-blue-50: #e3f2fd;
  --md-blue-100: #bbdefb;
  --md-blue-200: #90caf9;
  --md-blue-300: #64b5f6;
  --md-blue-400: #42a5f5;
  --md-blue-500: #2196f3;
  --md-blue-600: #1e88e5;
  --md-blue-700: #1976d2;
  --md-blue-800: #1565c0;
  --md-blue-900: #0d47a1;
  --md-blue-A100: #82b1ff;
  --md-blue-A200: #448aff;
  --md-blue-A400: #2979ff;
  --md-blue-A700: #2962ff;

  --md-light-blue-50: #e1f5fe;
  --md-light-blue-100: #b3e5fc;
  --md-light-blue-200: #81d4fa;
  --md-light-blue-300: #4fc3f7;
  --md-light-blue-400: #29b6f6;
  --md-light-blue-500: #03a9f4;
  --md-light-blue-600: #039be5;
  --md-light-blue-700: #0288d1;
  --md-light-blue-800: #0277bd;
  --md-light-blue-900: #01579b;
  --md-light-blue-A100: #80d8ff;
  --md-light-blue-A200: #40c4ff;
  --md-light-blue-A400: #00b0ff;
  --md-light-blue-A700: #0091ea;

  --md-cyan-50: #e0f7fa;
  --md-cyan-100: #b2ebf2;
  --md-cyan-200: #80deea;
  --md-cyan-300: #4dd0e1;
  --md-cyan-400: #26c6da;
  --md-cyan-500: #00bcd4;
  --md-cyan-600: #00acc1;
  --md-cyan-700: #0097a7;
  --md-cyan-800: #00838f;
  --md-cyan-900: #006064;
  --md-cyan-A100: #84ffff;
  --md-cyan-A200: #18ffff;
  --md-cyan-A400: #00e5ff;
  --md-cyan-A700: #00b8d4;

  --md-teal-50: #e0f2f1;
  --md-teal-100: #b2dfdb;
  --md-teal-200: #80cbc4;
  --md-teal-300: #4db6ac;
  --md-teal-400: #26a69a;
  --md-teal-500: #009688;
  --md-teal-600: #00897b;
  --md-teal-700: #00796b;
  --md-teal-800: #00695c;
  --md-teal-900: #004d40;
  --md-teal-A100: #a7ffeb;
  --md-teal-A200: #64ffda;
  --md-teal-A400: #1de9b6;
  --md-teal-A700: #00bfa5;

  --md-green-50: #e8f5e9;
  --md-green-100: #c8e6c9;
  --md-green-200: #a5d6a7;
  --md-green-300: #81c784;
  --md-green-400: #66bb6a;
  --md-green-500: #4caf50;
  --md-green-600: #43a047;
  --md-green-700: #388e3c;
  --md-green-800: #2e7d32;
  --md-green-900: #1b5e20;
  --md-green-A100: #b9f6ca;
  --md-green-A200: #69f0ae;
  --md-green-A400: #00e676;
  --md-green-A700: #00c853;

  --md-light-green-50: #f1f8e9;
  --md-light-green-100: #dcedc8;
  --md-light-green-200: #c5e1a5;
  --md-light-green-300: #aed581;
  --md-light-green-400: #9ccc65;
  --md-light-green-500: #8bc34a;
  --md-light-green-600: #7cb342;
  --md-light-green-700: #689f38;
  --md-light-green-800: #558b2f;
  --md-light-green-900: #33691e;
  --md-light-green-A100: #ccff90;
  --md-light-green-A200: #b2ff59;
  --md-light-green-A400: #76ff03;
  --md-light-green-A700: #64dd17;

  --md-lime-50: #f9fbe7;
  --md-lime-100: #f0f4c3;
  --md-lime-200: #e6ee9c;
  --md-lime-300: #dce775;
  --md-lime-400: #d4e157;
  --md-lime-500: #cddc39;
  --md-lime-600: #c0ca33;
  --md-lime-700: #afb42b;
  --md-lime-800: #9e9d24;
  --md-lime-900: #827717;
  --md-lime-A100: #f4ff81;
  --md-lime-A200: #eeff41;
  --md-lime-A400: #c6ff00;
  --md-lime-A700: #aeea00;

  --md-yellow-50: #fffde7;
  --md-yellow-100: #fff9c4;
  --md-yellow-200: #fff59d;
  --md-yellow-300: #fff176;
  --md-yellow-400: #ffee58;
  --md-yellow-500: #ffeb3b;
  --md-yellow-600: #fdd835;
  --md-yellow-700: #fbc02d;
  --md-yellow-800: #f9a825;
  --md-yellow-900: #f57f17;
  --md-yellow-A100: #ffff8d;
  --md-yellow-A200: #ffff00;
  --md-yellow-A400: #ffea00;
  --md-yellow-A700: #ffd600;

  --md-amber-50: #fff8e1;
  --md-amber-100: #ffecb3;
  --md-amber-200: #ffe082;
  --md-amber-300: #ffd54f;
  --md-amber-400: #ffca28;
  --md-amber-500: #ffc107;
  --md-amber-600: #ffb300;
  --md-amber-700: #ffa000;
  --md-amber-800: #ff8f00;
  --md-amber-900: #ff6f00;
  --md-amber-A100: #ffe57f;
  --md-amber-A200: #ffd740;
  --md-amber-A400: #ffc400;
  --md-amber-A700: #ffab00;

  --md-orange-50: #fff3e0;
  --md-orange-100: #ffe0b2;
  --md-orange-200: #ffcc80;
  --md-orange-300: #ffb74d;
  --md-orange-400: #ffa726;
  --md-orange-500: #ff9800;
  --md-orange-600: #fb8c00;
  --md-orange-700: #f57c00;
  --md-orange-800: #ef6c00;
  --md-orange-900: #e65100;
  --md-orange-A100: #ffd180;
  --md-orange-A200: #ffab40;
  --md-orange-A400: #ff9100;
  --md-orange-A700: #ff6d00;

  --md-deep-orange-50: #fbe9e7;
  --md-deep-orange-100: #ffccbc;
  --md-deep-orange-200: #ffab91;
  --md-deep-orange-300: #ff8a65;
  --md-deep-orange-400: #ff7043;
  --md-deep-orange-500: #ff5722;
  --md-deep-orange-600: #f4511e;
  --md-deep-orange-700: #e64a19;
  --md-deep-orange-800: #d84315;
  --md-deep-orange-900: #bf360c;
  --md-deep-orange-A100: #ff9e80;
  --md-deep-orange-A200: #ff6e40;
  --md-deep-orange-A400: #ff3d00;
  --md-deep-orange-A700: #dd2c00;

  --md-brown-50: #efebe9;
  --md-brown-100: #d7ccc8;
  --md-brown-200: #bcaaa4;
  --md-brown-300: #a1887f;
  --md-brown-400: #8d6e63;
  --md-brown-500: #795548;
  --md-brown-600: #6d4c41;
  --md-brown-700: #5d4037;
  --md-brown-800: #4e342e;
  --md-brown-900: #3e2723;

  --md-grey-50: #fafafa;
  --md-grey-100: #f5f5f5;
  --md-grey-200: #eeeeee;
  --md-grey-300: #e0e0e0;
  --md-grey-400: #bdbdbd;
  --md-grey-500: #9e9e9e;
  --md-grey-600: #757575;
  --md-grey-700: #616161;
  --md-grey-800: #424242;
  --md-grey-900: #212121;

  --md-blue-grey-50: #eceff1;
  --md-blue-grey-100: #cfd8dc;
  --md-blue-grey-200: #b0bec5;
  --md-blue-grey-300: #90a4ae;
  --md-blue-grey-400: #78909c;
  --md-blue-grey-500: #607d8b;
  --md-blue-grey-600: #546e7a;
  --md-blue-grey-700: #455a64;
  --md-blue-grey-800: #37474f;
  --md-blue-grey-900: #263238;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Spinner {
  position: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 10;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-layout-color0);
  outline: none;
}

.jp-SpinnerContent {
  font-size: 10px;
  margin: 50px auto;
  text-indent: -9999em;
  width: 3em;
  height: 3em;
  border-radius: 50%;
  background: var(--jp-brand-color3);
  background: linear-gradient(
    to right,
    #f37626 10%,
    rgba(255, 255, 255, 0) 42%
  );
  position: relative;
  animation: load3 1s infinite linear, fadeIn 1s;
}

.jp-SpinnerContent:before {
  width: 50%;
  height: 50%;
  background: #f37626;
  border-radius: 100% 0 0 0;
  position: absolute;
  top: 0;
  left: 0;
  content: '';
}

.jp-SpinnerContent:after {
  background: var(--jp-layout-color0);
  width: 75%;
  height: 75%;
  border-radius: 50%;
  content: '';
  margin: auto;
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

@keyframes load3 {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

button.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: none;
  box-sizing: border-box;
  text-align: center;
  line-height: 32px;
  height: 32px;
  padding: 0px 12px;
  letter-spacing: 0.8px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input.jp-mod-styled {
  background: var(--jp-input-background);
  height: 28px;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color1);
  padding-left: 7px;
  padding-right: 7px;
  font-size: var(--jp-ui-font-size2);
  color: var(--jp-ui-font-color0);
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input[type='checkbox'].jp-mod-styled {
  appearance: checkbox;
  -webkit-appearance: checkbox;
  -moz-appearance: checkbox;
  height: auto;
}

input.jp-mod-styled:focus {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-FileDialog-Checkbox {
  margin-top: 35px;
  display: flex;
  flex-direction: row;
  align-items: end;
  width: 100%;
}

.jp-FileDialog-Checkbox > label {
  flex: 1 1 auto;
}

.jp-select-wrapper {
  display: flex;
  position: relative;
  flex-direction: column;
  padding: 1px;
  background-color: var(--jp-layout-color1);
  height: 28px;
  box-sizing: border-box;
  margin-bottom: 12px;
}

.jp-select-wrapper.jp-mod-focused select.jp-mod-styled {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-input-active-background);
}

select.jp-mod-styled:hover {
  background-color: var(--jp-layout-color1);
  cursor: pointer;
  color: var(--jp-ui-font-color0);
  background-color: var(--jp-input-hover-background);
  box-shadow: inset 0 0px 1px rgba(0, 0, 0, 0.5);
}

select.jp-mod-styled {
  flex: 1 1 auto;
  height: 32px;
  width: 100%;
  font-size: var(--jp-ui-font-size2);
  background: var(--jp-input-background);
  color: var(--jp-ui-font-color0);
  padding: 0 25px 0 8px;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toolbar-height: calc(
    28px + var(--jp-border-width)
  ); /* leave 28px for content */
}

.jp-Toolbar {
  color: var(--jp-ui-font-color1);
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: 2px;
  z-index: 1;
  overflow-x: auto;
}

/* Toolbar items */

.jp-Toolbar > .jp-Toolbar-item.jp-Toolbar-spacer {
  flex-grow: 1;
  flex-shrink: 1;
}

.jp-Toolbar-item.jp-Toolbar-kernelStatus {
  display: inline-block;
  width: 32px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: 16px;
}

.jp-Toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  display: flex;
  padding-left: 1px;
  padding-right: 1px;
  font-size: var(--jp-ui-font-size1);
  line-height: var(--jp-private-toolbar-height);
  height: 100%;
}

/* Toolbar buttons */

/* This is the div we use to wrap the react component into a Widget */
div.jp-ToolbarButton {
  color: transparent;
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0px;
  margin: 0px;
}

button.jp-ToolbarButtonComponent {
  background: var(--jp-layout-color1);
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0px 6px;
  margin: 0px;
  height: 24px;
  border-radius: var(--jp-border-radius);
  display: flex;
  align-items: center;
  text-align: center;
  font-size: 14px;
  min-width: unset;
  min-height: unset;
}

button.jp-ToolbarButtonComponent:disabled {
  opacity: 0.4;
}

button.jp-ToolbarButtonComponent span {
  padding: 0px;
  flex: 0 0 auto;
}

button.jp-ToolbarButtonComponent .jp-ToolbarButtonComponent-label {
  font-size: var(--jp-ui-font-size1);
  line-height: 100%;
  padding-left: 2px;
  color: var(--jp-ui-font-color1);
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar.jp-Toolbar-micro {
  padding: 0;
  min-height: 0;
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar {
  border: none;
  box-shadow: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/


/* <DEPRECATED> */ body.p-mod-override-cursor *, /* </DEPRECATED> */
body.lm-mod-override-cursor * {
  cursor: inherit !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-JSONEditor {
  display: flex;
  flex-direction: column;
  width: 100%;
}

.jp-JSONEditor-host {
  flex: 1 1 auto;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0px;
  background: var(--jp-layout-color0);
  min-height: 50px;
  padding: 1px;
}

.jp-JSONEditor.jp-mod-error .jp-JSONEditor-host {
  border-color: red;
  outline-color: red;
}

.jp-JSONEditor-header {
  display: flex;
  flex: 1 0 auto;
  padding: 0 0 0 12px;
}

.jp-JSONEditor-header label {
  flex: 0 0 auto;
}

.jp-JSONEditor-commitButton {
  height: 16px;
  width: 16px;
  background-size: 18px;
  background-repeat: no-repeat;
  background-position: center;
}

.jp-JSONEditor-host.jp-mod-focused {
  background-color: var(--jp-input-active-background);
  border: 1px solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

.jp-Editor.jp-mod-dropTarget {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

/* BASICS */

.CodeMirror {
  /* Set height, width, borders, and global font properties here */
  font-family: monospace;
  height: 300px;
  color: black;
  direction: ltr;
}

/* PADDING */

.CodeMirror-lines {
  padding: 4px 0; /* Vertical padding around content */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  padding: 0 4px; /* Horizontal padding of content */
}

.CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  background-color: white; /* The little square between H and V scrollbars */
}

/* GUTTER */

.CodeMirror-gutters {
  border-right: 1px solid #ddd;
  background-color: #f7f7f7;
  white-space: nowrap;
}
.CodeMirror-linenumbers {}
.CodeMirror-linenumber {
  padding: 0 3px 0 5px;
  min-width: 20px;
  text-align: right;
  color: #999;
  white-space: nowrap;
}

.CodeMirror-guttermarker { color: black; }
.CodeMirror-guttermarker-subtle { color: #999; }

/* CURSOR */

.CodeMirror-cursor {
  border-left: 1px solid black;
  border-right: none;
  width: 0;
}
/* Shown when moving in bi-directional text */
.CodeMirror div.CodeMirror-secondarycursor {
  border-left: 1px solid silver;
}
.cm-fat-cursor .CodeMirror-cursor {
  width: auto;
  border: 0 !important;
  background: #7e7;
}
.cm-fat-cursor div.CodeMirror-cursors {
  z-index: 1;
}
.cm-fat-cursor-mark {
  background-color: rgba(20, 255, 20, 0.5);
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
}
.cm-animate-fat-cursor {
  width: auto;
  border: 0;
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
  background-color: #7e7;
}
@-moz-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@-webkit-keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}
@keyframes blink {
  0% {}
  50% { background-color: transparent; }
  100% {}
}

/* Can style cursor different in overwrite (non-insert) mode */
.CodeMirror-overwrite .CodeMirror-cursor {}

.cm-tab { display: inline-block; text-decoration: inherit; }

.CodeMirror-rulers {
  position: absolute;
  left: 0; right: 0; top: -50px; bottom: 0;
  overflow: hidden;
}
.CodeMirror-ruler {
  border-left: 1px solid #ccc;
  top: 0; bottom: 0;
  position: absolute;
}

/* DEFAULT THEME */

.cm-s-default .cm-header {color: blue;}
.cm-s-default .cm-quote {color: #090;}
.cm-negative {color: #d44;}
.cm-positive {color: #292;}
.cm-header, .cm-strong {font-weight: bold;}
.cm-em {font-style: italic;}
.cm-link {text-decoration: underline;}
.cm-strikethrough {text-decoration: line-through;}

.cm-s-default .cm-keyword {color: #708;}
.cm-s-default .cm-atom {color: #219;}
.cm-s-default .cm-number {color: #164;}
.cm-s-default .cm-def {color: #00f;}
.cm-s-default .cm-variable,
.cm-s-default .cm-punctuation,
.cm-s-default .cm-property,
.cm-s-default .cm-operator {}
.cm-s-default .cm-variable-2 {color: #05a;}
.cm-s-default .cm-variable-3, .cm-s-default .cm-type {color: #085;}
.cm-s-default .cm-comment {color: #a50;}
.cm-s-default .cm-string {color: #a11;}
.cm-s-default .cm-string-2 {color: #f50;}
.cm-s-default .cm-meta {color: #555;}
.cm-s-default .cm-qualifier {color: #555;}
.cm-s-default .cm-builtin {color: #30a;}
.cm-s-default .cm-bracket {color: #997;}
.cm-s-default .cm-tag {color: #170;}
.cm-s-default .cm-attribute {color: #00c;}
.cm-s-default .cm-hr {color: #999;}
.cm-s-default .cm-link {color: #00c;}

.cm-s-default .cm-error {color: #f00;}
.cm-invalidchar {color: #f00;}

.CodeMirror-composing { border-bottom: 2px solid; }

/* Default styles for common addons */

div.CodeMirror span.CodeMirror-matchingbracket {color: #0b0;}
div.CodeMirror span.CodeMirror-nonmatchingbracket {color: #a22;}
.CodeMirror-matchingtag { background: rgba(255, 150, 0, .3); }
.CodeMirror-activeline-background {background: #e8f2ff;}

/* STOP */

/* The rest of this file contains styles related to the mechanics of
   the editor. You probably shouldn't touch them. */

.CodeMirror {
  position: relative;
  overflow: hidden;
  background: white;
}

.CodeMirror-scroll {
  overflow: scroll !important; /* Things will break if this is overridden */
  /* 50px is the magic margin used to hide the element's real scrollbars */
  /* See overflow: hidden in .CodeMirror */
  margin-bottom: -50px; margin-right: -50px;
  padding-bottom: 50px;
  height: 100%;
  outline: none; /* Prevent dragging from highlighting the element */
  position: relative;
}
.CodeMirror-sizer {
  position: relative;
  border-right: 50px solid transparent;
}

/* The fake, visible scrollbars. Used to force redraw during scrolling
   before actual scrolling happens, thus preventing shaking and
   flickering artifacts. */
.CodeMirror-vscrollbar, .CodeMirror-hscrollbar, .CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  position: absolute;
  z-index: 6;
  display: none;
  outline: none;
}
.CodeMirror-vscrollbar {
  right: 0; top: 0;
  overflow-x: hidden;
  overflow-y: scroll;
}
.CodeMirror-hscrollbar {
  bottom: 0; left: 0;
  overflow-y: hidden;
  overflow-x: scroll;
}
.CodeMirror-scrollbar-filler {
  right: 0; bottom: 0;
}
.CodeMirror-gutter-filler {
  left: 0; bottom: 0;
}

.CodeMirror-gutters {
  position: absolute; left: 0; top: 0;
  min-height: 100%;
  z-index: 3;
}
.CodeMirror-gutter {
  white-space: normal;
  height: 100%;
  display: inline-block;
  vertical-align: top;
  margin-bottom: -50px;
}
.CodeMirror-gutter-wrapper {
  position: absolute;
  z-index: 4;
  background: none !important;
  border: none !important;
}
.CodeMirror-gutter-background {
  position: absolute;
  top: 0; bottom: 0;
  z-index: 4;
}
.CodeMirror-gutter-elt {
  position: absolute;
  cursor: default;
  z-index: 4;
}
.CodeMirror-gutter-wrapper ::selection { background-color: transparent }
.CodeMirror-gutter-wrapper ::-moz-selection { background-color: transparent }

.CodeMirror-lines {
  cursor: text;
  min-height: 1px; /* prevents collapsing before first draw */
}
.CodeMirror pre.CodeMirror-line,
.CodeMirror pre.CodeMirror-line-like {
  /* Reset some styles that the rest of the page might have set */
  -moz-border-radius: 0; -webkit-border-radius: 0; border-radius: 0;
  border-width: 0;
  background: transparent;
  font-family: inherit;
  font-size: inherit;
  margin: 0;
  white-space: pre;
  word-wrap: normal;
  line-height: inherit;
  color: inherit;
  z-index: 2;
  position: relative;
  overflow: visible;
  -webkit-tap-highlight-color: transparent;
  -webkit-font-variant-ligatures: contextual;
  font-variant-ligatures: contextual;
}
.CodeMirror-wrap pre.CodeMirror-line,
.CodeMirror-wrap pre.CodeMirror-line-like {
  word-wrap: break-word;
  white-space: pre-wrap;
  word-break: normal;
}

.CodeMirror-linebackground {
  position: absolute;
  left: 0; right: 0; top: 0; bottom: 0;
  z-index: 0;
}

.CodeMirror-linewidget {
  position: relative;
  z-index: 2;
  padding: 0.1px; /* Force widget margins to stay inside of the container */
}

.CodeMirror-widget {}

.CodeMirror-rtl pre { direction: rtl; }

.CodeMirror-code {
  outline: none;
}

/* Force content-box sizing for the elements where we expect it */
.CodeMirror-scroll,
.CodeMirror-sizer,
.CodeMirror-gutter,
.CodeMirror-gutters,
.CodeMirror-linenumber {
  -moz-box-sizing: content-box;
  box-sizing: content-box;
}

.CodeMirror-measure {
  position: absolute;
  width: 100%;
  height: 0;
  overflow: hidden;
  visibility: hidden;
}

.CodeMirror-cursor {
  position: absolute;
  pointer-events: none;
}
.CodeMirror-measure pre { position: static; }

div.CodeMirror-cursors {
  visibility: hidden;
  position: relative;
  z-index: 3;
}
div.CodeMirror-dragcursors {
  visibility: visible;
}

.CodeMirror-focused div.CodeMirror-cursors {
  visibility: visible;
}

.CodeMirror-selected { background: #d9d9d9; }
.CodeMirror-focused .CodeMirror-selected { background: #d7d4f0; }
.CodeMirror-crosshair { cursor: crosshair; }
.CodeMirror-line::selection, .CodeMirror-line > span::selection, .CodeMirror-line > span > span::selection { background: #d7d4f0; }
.CodeMirror-line::-moz-selection, .CodeMirror-line > span::-moz-selection, .CodeMirror-line > span > span::-moz-selection { background: #d7d4f0; }

.cm-searching {
  background-color: #ffa;
  background-color: rgba(255, 255, 0, .4);
}

/* Used to force a border model for a node */
.cm-force-border { padding-right: .1px; }

@media print {
  /* Hide the cursor when printing */
  .CodeMirror div.CodeMirror-cursors {
    visibility: hidden;
  }
}

/* See issue #2901 */
.cm-tab-wrap-hack:after { content: ''; }

/* Help users use markselection to safely style text background */
span.CodeMirror-selectedtext { background: none; }

.CodeMirror-dialog {
  position: absolute;
  left: 0; right: 0;
  background: inherit;
  z-index: 15;
  padding: .1em .8em;
  overflow: hidden;
  color: inherit;
}

.CodeMirror-dialog-top {
  border-bottom: 1px solid #eee;
  top: 0;
}

.CodeMirror-dialog-bottom {
  border-top: 1px solid #eee;
  bottom: 0;
}

.CodeMirror-dialog input {
  border: none;
  outline: none;
  background: transparent;
  width: 20em;
  color: inherit;
  font-family: monospace;
}

.CodeMirror-dialog button {
  font-size: 70%;
}

.CodeMirror-foldmarker {
  color: blue;
  text-shadow: #b9f 1px 1px 2px, #b9f -1px -1px 2px, #b9f 1px -1px 2px, #b9f -1px 1px 2px;
  font-family: arial;
  line-height: .3;
  cursor: pointer;
}
.CodeMirror-foldgutter {
  width: .7em;
}
.CodeMirror-foldgutter-open,
.CodeMirror-foldgutter-folded {
  cursor: pointer;
}
.CodeMirror-foldgutter-open:after {
  content: "\25BE";
}
.CodeMirror-foldgutter-folded:after {
  content: "\25B8";
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.CodeMirror {
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  border: 0;
  border-radius: 0;
  height: auto;
  /* Changed to auto to autogrow */
}

.CodeMirror pre {
  padding: 0 var(--jp-code-padding);
}

.jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-dialog {
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

/* This causes https://github.com/jupyter/jupyterlab/issues/522 */
/* May not cause it not because we changed it! */
.CodeMirror-lines {
  padding: var(--jp-code-padding) 0;
}

.CodeMirror-linenumber {
  padding: 0 8px;
}

.jp-CodeMirrorEditor {
  cursor: text;
}

.jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
  border-left: var(--jp-code-cursor-width0) solid var(--jp-editor-cursor-color);
}

/* When zoomed out 67% and 33% on a screen of 1440 width x 900 height */
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
    border-left: var(--jp-code-cursor-width1) solid
      var(--jp-editor-cursor-color);
  }
}

/* When zoomed out less than 33% */
@media screen and (min-width: 4320px) {
  .jp-CodeMirrorEditor[data-type='inline'] .CodeMirror-cursor {
    border-left: var(--jp-code-cursor-width2) solid
      var(--jp-editor-cursor-color);
  }
}

.CodeMirror.jp-mod-readOnly .CodeMirror-cursor {
  display: none;
}

.CodeMirror-gutters {
  border-right: 1px solid var(--jp-border-color2);
  background-color: var(--jp-layout-color0);
}

.jp-CollaboratorCursor {
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-top: none;
  border-bottom: 3px solid;
  background-clip: content-box;
  margin-left: -5px;
  margin-right: -5px;
}

.CodeMirror-selectedtext.cm-searching {
  background-color: var(--jp-search-selected-match-background-color) !important;
  color: var(--jp-search-selected-match-color) !important;
}

.cm-searching {
  background-color: var(
    --jp-search-unselected-match-background-color
  ) !important;
  color: var(--jp-search-unselected-match-color) !important;
}

.CodeMirror-focused .CodeMirror-selected {
  background-color: var(--jp-editor-selected-focused-background);
}

.CodeMirror-selected {
  background-color: var(--jp-editor-selected-background);
}

.jp-CollaboratorCursor-hover {
  position: absolute;
  z-index: 1;
  transform: translateX(-50%);
  color: white;
  border-radius: 3px;
  padding-left: 4px;
  padding-right: 4px;
  padding-top: 1px;
  padding-bottom: 1px;
  text-align: center;
  font-size: var(--jp-ui-font-size1);
  white-space: nowrap;
}

.jp-CodeMirror-ruler {
  border-left: 1px dashed var(--jp-border-color2);
}

/**
 * Here is our jupyter theme for CodeMirror syntax highlighting
 * This is used in our marked.js syntax highlighting and CodeMirror itself
 * The string "jupyter" is set in ../codemirror/widget.DEFAULT_CODEMIRROR_THEME
 * This came from the classic notebook, which came form highlight.js/GitHub
 */

/**
 * CodeMirror themes are handling the background/color in this way. This works
 * fine for CodeMirror editors outside the notebook, but the notebook styles
 * these things differently.
 */
.CodeMirror.cm-s-jupyter {
  background: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

/* In the notebook, we want this styling to be handled by its container */
.jp-CodeConsole .CodeMirror.cm-s-jupyter,
.jp-Notebook .CodeMirror.cm-s-jupyter {
  background: transparent;
}

.cm-s-jupyter .CodeMirror-cursor {
  border-left: var(--jp-code-cursor-width0) solid var(--jp-editor-cursor-color);
}
.cm-s-jupyter span.cm-keyword {
  color: var(--jp-mirror-editor-keyword-color);
  font-weight: bold;
}
.cm-s-jupyter span.cm-atom {
  color: var(--jp-mirror-editor-atom-color);
}
.cm-s-jupyter span.cm-number {
  color: var(--jp-mirror-editor-number-color);
}
.cm-s-jupyter span.cm-def {
  color: var(--jp-mirror-editor-def-color);
}
.cm-s-jupyter span.cm-variable {
  color: var(--jp-mirror-editor-variable-color);
}
.cm-s-jupyter span.cm-variable-2 {
  color: var(--jp-mirror-editor-variable-2-color);
}
.cm-s-jupyter span.cm-variable-3 {
  color: var(--jp-mirror-editor-variable-3-color);
}
.cm-s-jupyter span.cm-punctuation {
  color: var(--jp-mirror-editor-punctuation-color);
}
.cm-s-jupyter span.cm-property {
  color: var(--jp-mirror-editor-property-color);
}
.cm-s-jupyter span.cm-operator {
  color: var(--jp-mirror-editor-operator-color);
  font-weight: bold;
}
.cm-s-jupyter span.cm-comment {
  color: var(--jp-mirror-editor-comment-color);
  font-style: italic;
}
.cm-s-jupyter span.cm-string {
  color: var(--jp-mirror-editor-string-color);
}
.cm-s-jupyter span.cm-string-2 {
  color: var(--jp-mirror-editor-string-2-color);
}
.cm-s-jupyter span.cm-meta {
  color: var(--jp-mirror-editor-meta-color);
}
.cm-s-jupyter span.cm-qualifier {
  color: var(--jp-mirror-editor-qualifier-color);
}
.cm-s-jupyter span.cm-builtin {
  color: var(--jp-mirror-editor-builtin-color);
}
.cm-s-jupyter span.cm-bracket {
  color: var(--jp-mirror-editor-bracket-color);
}
.cm-s-jupyter span.cm-tag {
  color: var(--jp-mirror-editor-tag-color);
}
.cm-s-jupyter span.cm-attribute {
  color: var(--jp-mirror-editor-attribute-color);
}
.cm-s-jupyter span.cm-header {
  color: var(--jp-mirror-editor-header-color);
}
.cm-s-jupyter span.cm-quote {
  color: var(--jp-mirror-editor-quote-color);
}
.cm-s-jupyter span.cm-link {
  color: var(--jp-mirror-editor-link-color);
}
.cm-s-jupyter span.cm-error {
  color: var(--jp-mirror-editor-error-color);
}
.cm-s-jupyter span.cm-hr {
  color: #999;
}

.cm-s-jupyter span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}

.cm-s-jupyter .CodeMirror-activeline-background,
.cm-s-jupyter .CodeMirror-gutter {
  background-color: var(--jp-layout-color2);
}

/* Styles for shared cursors (remote cursor locations and selected ranges) */
.jp-CodeMirrorEditor .remote-caret {
  position: relative;
  border-left: 2px solid black;
  margin-left: -1px;
  margin-right: -1px;
  box-sizing: border-box;
}

.jp-CodeMirrorEditor .remote-caret > div {
  white-space: nowrap;
  position: absolute;
  top: -1.15em;
  padding-bottom: 0.05em;
  left: -2px;
  font-size: 0.95em;
  background-color: rgb(250, 129, 0);
  font-family: var(--jp-ui-font-family);
  font-weight: bold;
  line-height: normal;
  user-select: none;
  color: white;
  padding-left: 2px;
  padding-right: 2px;
  z-index: 3;
  transition: opacity 0.3s ease-in-out;
}

.jp-CodeMirrorEditor .remote-caret.hide-name > div {
  transition-delay: 0.7s;
  opacity: 0;
}

.jp-CodeMirrorEditor .remote-caret:hover > div {
  opacity: 1;
  transition-delay: 0s;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| RenderedText
|----------------------------------------------------------------------------*/

:root {
  /* This is the padding value to fill the gaps between lines containing spans with background color. */
  --jp-private-code-span-padding: calc(
    (var(--jp-code-line-height) - 1) * var(--jp-code-font-size) / 2
  );
}

.jp-RenderedText {
  text-align: left;
  padding-left: var(--jp-code-padding);
  line-height: var(--jp-code-line-height);
  font-family: var(--jp-code-font-family);
}

.jp-RenderedText pre,
.jp-RenderedJavaScript pre,
.jp-RenderedHTMLCommon pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
  border: none;
  margin: 0px;
  padding: 0px;
}

.jp-RenderedText pre a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}
.jp-RenderedText pre a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}
.jp-RenderedText pre a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* console foregrounds and backgrounds */
.jp-RenderedText pre .ansi-black-fg {
  color: #3e424d;
}
.jp-RenderedText pre .ansi-red-fg {
  color: #e75c58;
}
.jp-RenderedText pre .ansi-green-fg {
  color: #00a250;
}
.jp-RenderedText pre .ansi-yellow-fg {
  color: #ddb62b;
}
.jp-RenderedText pre .ansi-blue-fg {
  color: #208ffb;
}
.jp-RenderedText pre .ansi-magenta-fg {
  color: #d160c4;
}
.jp-RenderedText pre .ansi-cyan-fg {
  color: #60c6c8;
}
.jp-RenderedText pre .ansi-white-fg {
  color: #c5c1b4;
}

.jp-RenderedText pre .ansi-black-bg {
  background-color: #3e424d;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-red-bg {
  background-color: #e75c58;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-green-bg {
  background-color: #00a250;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-yellow-bg {
  background-color: #ddb62b;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-blue-bg {
  background-color: #208ffb;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-magenta-bg {
  background-color: #d160c4;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-cyan-bg {
  background-color: #60c6c8;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-white-bg {
  background-color: #c5c1b4;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-black-intense-fg {
  color: #282c36;
}
.jp-RenderedText pre .ansi-red-intense-fg {
  color: #b22b31;
}
.jp-RenderedText pre .ansi-green-intense-fg {
  color: #007427;
}
.jp-RenderedText pre .ansi-yellow-intense-fg {
  color: #b27d12;
}
.jp-RenderedText pre .ansi-blue-intense-fg {
  color: #0065ca;
}
.jp-RenderedText pre .ansi-magenta-intense-fg {
  color: #a03196;
}
.jp-RenderedText pre .ansi-cyan-intense-fg {
  color: #258f8f;
}
.jp-RenderedText pre .ansi-white-intense-fg {
  color: #a1a6b2;
}

.jp-RenderedText pre .ansi-black-intense-bg {
  background-color: #282c36;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-red-intense-bg {
  background-color: #b22b31;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-green-intense-bg {
  background-color: #007427;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-yellow-intense-bg {
  background-color: #b27d12;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-blue-intense-bg {
  background-color: #0065ca;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-magenta-intense-bg {
  background-color: #a03196;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-cyan-intense-bg {
  background-color: #258f8f;
  padding: var(--jp-private-code-span-padding) 0;
}
.jp-RenderedText pre .ansi-white-intense-bg {
  background-color: #a1a6b2;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-default-inverse-fg {
  color: var(--jp-ui-inverse-font-color0);
}
.jp-RenderedText pre .ansi-default-inverse-bg {
  background-color: var(--jp-inverse-layout-color0);
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-bold {
  font-weight: bold;
}
.jp-RenderedText pre .ansi-underline {
  text-decoration: underline;
}

.jp-RenderedText[data-mime-type='application/vnd.jupyter.stderr'] {
  background: var(--jp-rendermime-error-background);
  padding-top: var(--jp-code-padding);
}

/*-----------------------------------------------------------------------------
| RenderedLatex
|----------------------------------------------------------------------------*/

.jp-RenderedLatex {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
}

/* Left-justify outputs.*/
.jp-OutputArea-output.jp-RenderedLatex {
  padding: var(--jp-code-padding);
  text-align: left;
}

/*-----------------------------------------------------------------------------
| RenderedHTML
|----------------------------------------------------------------------------*/

.jp-RenderedHTMLCommon {
  color: var(--jp-content-font-color1);
  font-family: var(--jp-content-font-family);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
  /* Give a bit more R padding on Markdown text to keep line lengths reasonable */
  padding-right: 20px;
}

.jp-RenderedHTMLCommon em {
  font-style: italic;
}

.jp-RenderedHTMLCommon strong {
  font-weight: bold;
}

.jp-RenderedHTMLCommon u {
  text-decoration: underline;
}

.jp-RenderedHTMLCommon a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* Headings */

.jp-RenderedHTMLCommon h1,
.jp-RenderedHTMLCommon h2,
.jp-RenderedHTMLCommon h3,
.jp-RenderedHTMLCommon h4,
.jp-RenderedHTMLCommon h5,
.jp-RenderedHTMLCommon h6 {
  line-height: var(--jp-content-heading-line-height);
  font-weight: var(--jp-content-heading-font-weight);
  font-style: normal;
  margin: var(--jp-content-heading-margin-top) 0
    var(--jp-content-heading-margin-bottom) 0;
}

.jp-RenderedHTMLCommon h1:first-child,
.jp-RenderedHTMLCommon h2:first-child,
.jp-RenderedHTMLCommon h3:first-child,
.jp-RenderedHTMLCommon h4:first-child,
.jp-RenderedHTMLCommon h5:first-child,
.jp-RenderedHTMLCommon h6:first-child {
  margin-top: calc(0.5 * var(--jp-content-heading-margin-top));
}

.jp-RenderedHTMLCommon h1:last-child,
.jp-RenderedHTMLCommon h2:last-child,
.jp-RenderedHTMLCommon h3:last-child,
.jp-RenderedHTMLCommon h4:last-child,
.jp-RenderedHTMLCommon h5:last-child,
.jp-RenderedHTMLCommon h6:last-child {
  margin-bottom: calc(0.5 * var(--jp-content-heading-margin-bottom));
}

.jp-RenderedHTMLCommon h1 {
  font-size: var(--jp-content-font-size5);
}

.jp-RenderedHTMLCommon h2 {
  font-size: var(--jp-content-font-size4);
}

.jp-RenderedHTMLCommon h3 {
  font-size: var(--jp-content-font-size3);
}

.jp-RenderedHTMLCommon h4 {
  font-size: var(--jp-content-font-size2);
}

.jp-RenderedHTMLCommon h5 {
  font-size: var(--jp-content-font-size1);
}

.jp-RenderedHTMLCommon h6 {
  font-size: var(--jp-content-font-size0);
}

/* Lists */

.jp-RenderedHTMLCommon ul:not(.list-inline),
.jp-RenderedHTMLCommon ol:not(.list-inline) {
  padding-left: 2em;
}

.jp-RenderedHTMLCommon ul {
  list-style: disc;
}

.jp-RenderedHTMLCommon ul ul {
  list-style: square;
}

.jp-RenderedHTMLCommon ul ul ul {
  list-style: circle;
}

.jp-RenderedHTMLCommon ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol ol {
  list-style: upper-alpha;
}

.jp-RenderedHTMLCommon ol ol ol {
  list-style: lower-alpha;
}

.jp-RenderedHTMLCommon ol ol ol ol {
  list-style: lower-roman;
}

.jp-RenderedHTMLCommon ol ol ol ol ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol,
.jp-RenderedHTMLCommon ul {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon ul ul,
.jp-RenderedHTMLCommon ul ol,
.jp-RenderedHTMLCommon ol ul,
.jp-RenderedHTMLCommon ol ol {
  margin-bottom: 0em;
}

.jp-RenderedHTMLCommon hr {
  color: var(--jp-border-color2);
  background-color: var(--jp-border-color1);
  margin-top: 1em;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon > pre {
  margin: 1.5em 2em;
}

.jp-RenderedHTMLCommon pre,
.jp-RenderedHTMLCommon code {
  border: 0;
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  line-height: var(--jp-code-line-height);
  padding: 0;
  white-space: pre-wrap;
}

.jp-RenderedHTMLCommon :not(pre) > code {
  background-color: var(--jp-layout-color2);
  padding: 1px 5px;
}

/* Tables */

.jp-RenderedHTMLCommon table {
  border-collapse: collapse;
  border-spacing: 0;
  border: none;
  color: var(--jp-ui-font-color1);
  font-size: 12px;
  table-layout: fixed;
  margin-left: auto;
  margin-right: auto;
}

.jp-RenderedHTMLCommon thead {
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  vertical-align: bottom;
}

.jp-RenderedHTMLCommon td,
.jp-RenderedHTMLCommon th,
.jp-RenderedHTMLCommon tr {
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}

.jp-RenderedMarkdown.jp-RenderedHTMLCommon td,
.jp-RenderedMarkdown.jp-RenderedHTMLCommon th {
  max-width: none;
}

:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon td,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon th,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon tr {
  text-align: right;
}

.jp-RenderedHTMLCommon th {
  font-weight: bold;
}

.jp-RenderedHTMLCommon tbody tr:nth-child(odd) {
  background: var(--jp-layout-color0);
}

.jp-RenderedHTMLCommon tbody tr:nth-child(even) {
  background: var(--jp-rendermime-table-row-background);
}

.jp-RenderedHTMLCommon tbody tr:hover {
  background: var(--jp-rendermime-table-row-hover-background);
}

.jp-RenderedHTMLCommon table {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon p {
  text-align: left;
  margin: 0px;
}

.jp-RenderedHTMLCommon p {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon img {
  -moz-force-broken-image-icon: 1;
}

/* Restrict to direct children as other images could be nested in other content. */
.jp-RenderedHTMLCommon > img {
  display: block;
  margin-left: 0;
  margin-right: 0;
  margin-bottom: 1em;
}

/* Change color behind transparent images if they need it... */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-light-background {
  background-color: var(--jp-inverse-layout-color1);
}
[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-dark-background {
  background-color: var(--jp-inverse-layout-color1);
}
/* ...or leave it untouched if they don't */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-dark-background {
}
[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-light-background {
}

.jp-RenderedHTMLCommon img,
.jp-RenderedImage img,
.jp-RenderedHTMLCommon svg,
.jp-RenderedSVG svg {
  max-width: 100%;
  height: auto;
}

.jp-RenderedHTMLCommon img.jp-mod-unconfined,
.jp-RenderedImage img.jp-mod-unconfined,
.jp-RenderedHTMLCommon svg.jp-mod-unconfined,
.jp-RenderedSVG svg.jp-mod-unconfined {
  max-width: none;
}

.jp-RenderedHTMLCommon .alert {
  padding: var(--jp-notebook-padding);
  border: var(--jp-border-width) solid transparent;
  border-radius: var(--jp-border-radius);
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon .alert-info {
  color: var(--jp-info-color0);
  background-color: var(--jp-info-color3);
  border-color: var(--jp-info-color2);
}
.jp-RenderedHTMLCommon .alert-info hr {
  border-color: var(--jp-info-color3);
}
.jp-RenderedHTMLCommon .alert-info > p:last-child,
.jp-RenderedHTMLCommon .alert-info > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-warning {
  color: var(--jp-warn-color0);
  background-color: var(--jp-warn-color3);
  border-color: var(--jp-warn-color2);
}
.jp-RenderedHTMLCommon .alert-warning hr {
  border-color: var(--jp-warn-color3);
}
.jp-RenderedHTMLCommon .alert-warning > p:last-child,
.jp-RenderedHTMLCommon .alert-warning > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-success {
  color: var(--jp-success-color0);
  background-color: var(--jp-success-color3);
  border-color: var(--jp-success-color2);
}
.jp-RenderedHTMLCommon .alert-success hr {
  border-color: var(--jp-success-color3);
}
.jp-RenderedHTMLCommon .alert-success > p:last-child,
.jp-RenderedHTMLCommon .alert-success > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-danger {
  color: var(--jp-error-color0);
  background-color: var(--jp-error-color3);
  border-color: var(--jp-error-color2);
}
.jp-RenderedHTMLCommon .alert-danger hr {
  border-color: var(--jp-error-color3);
}
.jp-RenderedHTMLCommon .alert-danger > p:last-child,
.jp-RenderedHTMLCommon .alert-danger > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon blockquote {
  margin: 1em 2em;
  padding: 0 1em;
  border-left: 5px solid var(--jp-border-color2);
}

a.jp-InternalAnchorLink {
  visibility: hidden;
  margin-left: 8px;
  color: var(--md-blue-800);
}

h1:hover .jp-InternalAnchorLink,
h2:hover .jp-InternalAnchorLink,
h3:hover .jp-InternalAnchorLink,
h4:hover .jp-InternalAnchorLink,
h5:hover .jp-InternalAnchorLink,
h6:hover .jp-InternalAnchorLink {
  visibility: visible;
}

.jp-RenderedHTMLCommon kbd {
  background-color: var(--jp-rendermime-table-row-background);
  border: 1px solid var(--jp-border-color0);
  border-bottom-color: var(--jp-border-color2);
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
  display: inline-block;
  font-size: 0.8em;
  line-height: 1em;
  padding: 0.2em 0.5em;
}

/* Most direct children of .jp-RenderedHTMLCommon have a margin-bottom of 1.0.
 * At the bottom of cells this is a bit too much as there is also spacing
 * between cells. Going all the way to 0 gets too tight between markdown and
 * code cells.
 */
.jp-RenderedHTMLCommon > *:last-child {
  margin-bottom: 0.5em;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MimeDocument {
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-filebrowser-button-height: 28px;
  --jp-private-filebrowser-button-width: 48px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FileBrowser {
  display: flex;
  flex-direction: column;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  border-bottom: none;
  height: auto;
  margin: var(--jp-toolbar-header-margin);
  box-shadow: none;
}

.jp-BreadCrumbs {
  flex: 0 0 auto;
  margin: 8px 12px 8px 12px;
}

.jp-BreadCrumbs-item {
  margin: 0px 2px;
  padding: 0px 2px;
  border-radius: var(--jp-border-radius);
  cursor: pointer;
}

.jp-BreadCrumbs-item:hover {
  background-color: var(--jp-layout-color2);
}

.jp-BreadCrumbs-item:first-child {
  margin-left: 0px;
}

.jp-BreadCrumbs-item.jp-mod-dropTarget {
  background-color: var(--jp-brand-color2);
  opacity: 0.7;
}

/*-----------------------------------------------------------------------------
| Buttons
|----------------------------------------------------------------------------*/

.jp-FileBrowser-toolbar.jp-Toolbar {
  padding: 0px;
  margin: 8px 12px 0px 12px;
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  justify-content: flex-start;
}

.jp-FileBrowser-toolbar.jp-Toolbar .jp-Toolbar-item {
  flex: 0 0 auto;
  padding-left: 0px;
  padding-right: 2px;
}

.jp-FileBrowser-toolbar.jp-Toolbar .jp-ToolbarButtonComponent {
  width: 40px;
}

.jp-FileBrowser-toolbar.jp-Toolbar
  .jp-Toolbar-item:first-child
  .jp-ToolbarButtonComponent {
  width: 72px;
  background: var(--jp-brand-color1);
}

.jp-FileBrowser-toolbar.jp-Toolbar
  .jp-Toolbar-item:first-child
  .jp-ToolbarButtonComponent:focus-visible {
  background-color: var(--jp-brand-color0);
}

.jp-FileBrowser-toolbar.jp-Toolbar
  .jp-Toolbar-item:first-child
  .jp-ToolbarButtonComponent
  .jp-icon3 {
  fill: white;
}

/*-----------------------------------------------------------------------------
| Other styles
|----------------------------------------------------------------------------*/

.jp-FileDialog.jp-mod-conflict input {
  color: var(--jp-error-color1);
}

.jp-FileDialog .jp-new-name-title {
  margin-top: 12px;
}

.jp-LastModified-hidden {
  display: none;
}

.jp-FileBrowser-filterBox {
  padding: 0px;
  flex: 0 0 auto;
  margin: 8px 12px 0px 12px;
}

/*-----------------------------------------------------------------------------
| DirListing
|----------------------------------------------------------------------------*/

.jp-DirListing {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
  outline: 0;
}

.jp-DirListing:focus-visible {
  border: 1px solid var(--jp-brand-color1);
}

.jp-DirListing-header {
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  overflow: hidden;
  border-top: var(--jp-border-width) solid var(--jp-border-color2);
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
}

.jp-DirListing-headerItem {
  padding: 4px 12px 2px 12px;
  font-weight: 500;
}

.jp-DirListing-headerItem:hover {
  background: var(--jp-layout-color2);
}

.jp-DirListing-headerItem.jp-id-name {
  flex: 1 0 84px;
}

.jp-DirListing-headerItem.jp-id-modified {
  flex: 0 0 112px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-id-narrow {
  display: none;
  flex: 0 0 5px;
  padding: 4px 4px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
  color: var(--jp-border-color2);
}

.jp-DirListing-narrow .jp-id-narrow {
  display: block;
}

.jp-DirListing-narrow .jp-id-modified,
.jp-DirListing-narrow .jp-DirListing-itemModified {
  display: none;
}

.jp-DirListing-headerItem.jp-mod-selected {
  font-weight: 600;
}

/* increase specificity to override bundled default */
.jp-DirListing-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

.jp-DirListing-content mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.jp-DirListing-content .jp-DirListing-item.jp-mod-selected mark {
  color: var(--jp-ui-inverse-font-color0);
}

/* Style the directory listing content when a user drops a file to upload */
.jp-DirListing.jp-mod-native-drop .jp-DirListing-content {
  outline: 5px dashed rgba(128, 128, 128, 0.5);
  outline-offset: -10px;
  cursor: copy;
}

.jp-DirListing-item {
  display: flex;
  flex-direction: row;
  padding: 4px 12px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-DirListing-item[data-is-dot] {
  opacity: 75%;
}

.jp-DirListing-item.jp-mod-selected {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.jp-DirListing-item.jp-mod-dropTarget {
  background: var(--jp-brand-color3);
}

.jp-DirListing-item:hover:not(.jp-mod-selected) {
  background: var(--jp-layout-color2);
}

.jp-DirListing-itemIcon {
  flex: 0 0 20px;
  margin-right: 4px;
}

.jp-DirListing-itemText {
  flex: 1 0 64px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  user-select: none;
}

.jp-DirListing-itemModified {
  flex: 0 0 125px;
  text-align: right;
}

.jp-DirListing-editor {
  flex: 1 0 64px;
  outline: none;
  border: none;
}

.jp-DirListing-item.jp-mod-running .jp-DirListing-itemIcon:before {
  color: var(--jp-success-color1);
  content: '\25CF';
  font-size: 8px;
  position: absolute;
  left: -8px;
}

.jp-DirListing-item.jp-mod-running.jp-mod-selected
  .jp-DirListing-itemIcon:before {
  color: var(--jp-ui-inverse-font-color1);
}

.jp-DirListing-item.lm-mod-drag-image,
.jp-DirListing-item.jp-mod-selected.lm-mod-drag-image {
  font-size: var(--jp-ui-font-size1);
  padding-left: 4px;
  margin-left: 4px;
  width: 160px;
  background-color: var(--jp-ui-inverse-font-color2);
  box-shadow: var(--jp-elevation-z2);
  border-radius: 0px;
  color: var(--jp-ui-font-color1);
  transform: translateX(-40%) translateY(-58%);
}

.jp-DirListing-deadSpace {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

.jp-Document {
  min-width: 120px;
  min-height: 120px;
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
}

/*-----------------------------------------------------------------------------
| Main OutputArea
| OutputArea has a list of Outputs
|----------------------------------------------------------------------------*/

.jp-OutputArea {
  overflow-y: auto;
}

.jp-OutputArea-child {
  display: flex;
  flex-direction: row;
}

body[data-format='mobile'] .jp-OutputArea-child {
  flex-direction: column;
}

.jp-OutputPrompt {
  flex: 0 0 var(--jp-cell-prompt-width);
  color: var(--jp-cell-outprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);
  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

body[data-format='mobile'] .jp-OutputPrompt {
  flex: 0 0 auto;
  text-align: left;
}

.jp-OutputArea-output {
  height: auto;
  overflow: auto;
  user-select: text;
  -moz-user-select: text;
  -webkit-user-select: text;
  -ms-user-select: text;
}

.jp-OutputArea-child .jp-OutputArea-output {
  flex-grow: 1;
  flex-shrink: 1;
}

body[data-format='mobile'] .jp-OutputArea-child .jp-OutputArea-output {
  margin-left: var(--jp-notebook-padding);
}

/**
 * Isolated output.
 */
.jp-OutputArea-output.jp-mod-isolated {
  width: 100%;
  display: block;
}

/*
When drag events occur, `p-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated {
  position: relative;
}

body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/* pre */

.jp-OutputArea-output pre {
  border: none;
  margin: 0px;
  padding: 0px;
  overflow-x: auto;
  overflow-y: auto;
  word-break: break-all;
  word-wrap: break-word;
  white-space: pre-wrap;
}

/* tables */

.jp-OutputArea-output.jp-RenderedHTMLCommon table {
  margin-left: 0;
  margin-right: 0;
}

/* description lists */

.jp-OutputArea-output dl,
.jp-OutputArea-output dt,
.jp-OutputArea-output dd {
  display: block;
}

.jp-OutputArea-output dl {
  width: 100%;
  overflow: hidden;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dt {
  font-weight: bold;
  float: left;
  width: 20%;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dd {
  float: left;
  width: 80%;
  padding: 0;
  margin: 0;
}

/* Hide the gutter in case of
 *  - nested output areas (e.g. in the case of output widgets)
 *  - mirrored output areas
 */
.jp-OutputArea .jp-OutputArea .jp-OutputArea-prompt {
  display: none;
}

/*-----------------------------------------------------------------------------
| executeResult is added to any Output-result for the display of the object
| returned by a cell
|----------------------------------------------------------------------------*/

.jp-OutputArea-output.jp-OutputArea-executeResult {
  margin-left: 0px;
  flex: 1 1 auto;
}

/* Text output with the Out[] prompt needs a top padding to match the
 * alignment of the Out[] prompt itself.
 */
.jp-OutputArea-executeResult .jp-RenderedText.jp-OutputArea-output {
  padding-top: var(--jp-code-padding);
  border-top: var(--jp-border-width) solid transparent;
}

/*-----------------------------------------------------------------------------
| The Stdin output
|----------------------------------------------------------------------------*/

.jp-OutputArea-stdin {
  line-height: var(--jp-code-line-height);
  padding-top: var(--jp-code-padding);
  display: flex;
}

.jp-Stdin-prompt {
  color: var(--jp-content-font-color0);
  padding-right: var(--jp-code-padding);
  vertical-align: baseline;
  flex: 0 0 auto;
}

.jp-Stdin-input {
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  color: inherit;
  background-color: inherit;
  width: 42%;
  min-width: 200px;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
  flex: 0 0 70%;
}

.jp-Stdin-input:focus {
  box-shadow: none;
}

/*-----------------------------------------------------------------------------
| Output Area View
|----------------------------------------------------------------------------*/

.jp-LinkedOutputView .jp-OutputArea {
  height: 100%;
  display: block;
}

.jp-LinkedOutputView .jp-OutputArea-output:only-child {
  height: 100%;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapser {
  flex: 0 0 var(--jp-cell-collapser-width);
  padding: 0px;
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
  border-radius: var(--jp-border-radius);
  opacity: 1;
}

.jp-Collapser-child {
  display: block;
  width: 100%;
  box-sizing: border-box;
  /* height: 100% doesn't work because the height of its parent is computed from content */
  position: absolute;
  top: 0px;
  bottom: 0px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Header/Footer
|----------------------------------------------------------------------------*/

/* Hidden by zero height by default */
.jp-CellHeader,
.jp-CellFooter {
  height: 0px;
  width: 100%;
  padding: 0px;
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Input
|----------------------------------------------------------------------------*/

/* All input areas */
.jp-InputArea {
  display: flex;
  flex-direction: row;
  overflow: hidden;
}

body[data-format='mobile'] .jp-InputArea {
  flex-direction: column;
}

.jp-InputArea-editor {
  flex: 1 1 auto;
  overflow: hidden;
}

.jp-InputArea-editor {
  /* This is the non-active, default styling */
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0px;
  background: var(--jp-cell-editor-background);
}

body[data-format='mobile'] .jp-InputArea-editor {
  margin-left: var(--jp-notebook-padding);
}

.jp-InputPrompt {
  flex: 0 0 var(--jp-cell-prompt-width);
  color: var(--jp-cell-inprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  opacity: var(--jp-cell-prompt-opacity);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);
  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

body[data-format='mobile'] .jp-InputPrompt {
  flex: 0 0 auto;
  text-align: left;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Placeholder {
  display: flex;
  flex-direction: row;
  flex: 1 1 auto;
}

.jp-Placeholder-prompt {
  box-sizing: border-box;
}

.jp-Placeholder-content {
  flex: 1 1 auto;
  border: none;
  background: transparent;
  height: 20px;
  box-sizing: border-box;
}

.jp-Placeholder-content .jp-MoreHorizIcon {
  width: 32px;
  height: 16px;
  border: 1px solid transparent;
  border-radius: var(--jp-border-radius);
}

.jp-Placeholder-content .jp-MoreHorizIcon:hover {
  border: 1px solid var(--jp-border-color1);
  box-shadow: 0px 0px 2px 0px rgba(0, 0, 0, 0.25);
  background-color: var(--jp-layout-color0);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-cell-scrolling-output-offset: 5px;
}

/*-----------------------------------------------------------------------------
| Cell
|----------------------------------------------------------------------------*/

.jp-Cell {
  padding: var(--jp-cell-padding);
  margin: 0px;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Common input/output
|----------------------------------------------------------------------------*/

.jp-Cell-inputWrapper,
.jp-Cell-outputWrapper {
  display: flex;
  flex-direction: row;
  padding: 0px;
  margin: 0px;
  /* Added to reveal the box-shadow on the input and output collapsers. */
  overflow: visible;
}

/* Only input/output areas inside cells */
.jp-Cell-inputArea,
.jp-Cell-outputArea {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Collapser
|----------------------------------------------------------------------------*/

/* Make the output collapser disappear when there is not output, but do so
 * in a manner that leaves it in the layout and preserves its width.
 */
.jp-Cell.jp-mod-noOutputs .jp-Cell-outputCollapser {
  border: none !important;
  background: transparent !important;
}

.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputCollapser {
  min-height: var(--jp-cell-collapser-min-height);
}

/*-----------------------------------------------------------------------------
| Output
|----------------------------------------------------------------------------*/

/* Put a space between input and output when there IS output */
.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputWrapper {
  margin-top: 5px;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea {
  overflow-y: auto;
  max-height: 200px;
  box-shadow: inset 0 0 6px 2px rgba(0, 0, 0, 0.3);
  margin-left: var(--jp-private-cell-scrolling-output-offset);
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-prompt {
  flex: 0 0
    calc(
      var(--jp-cell-prompt-width) -
        var(--jp-private-cell-scrolling-output-offset)
    );
}

/*-----------------------------------------------------------------------------
| CodeCell
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| MarkdownCell
|----------------------------------------------------------------------------*/

.jp-MarkdownOutput {
  flex: 1 1 auto;
  margin-top: 0;
  margin-bottom: 0;
  padding-left: var(--jp-code-padding);
}

.jp-MarkdownOutput.jp-RenderedHTMLCommon {
  overflow: auto;
}

.jp-showHiddenCellsButton {
  margin-left: calc(var(--jp-cell-prompt-width) + 2 * var(--jp-code-padding));
  margin-top: var(--jp-code-padding);
  border: 1px solid var(--jp-border-color2);
  background-color: var(--jp-border-color3) !important;
  color: var(--jp-content-font-color0) !important;
}

.jp-showHiddenCellsButton:hover {
  background-color: var(--jp-border-color2) !important;
}

.jp-collapseHeadingButton {
  display: none;
}

.jp-MarkdownCell:hover .jp-collapseHeadingButton {
  display: flex;
  min-height: var(--jp-cell-collapser-min-height);
  position: absolute;
  right: 0;
  top: 0;
  bottom: 0;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-NotebookPanel-toolbar {
  padding: 2px;
}

.jp-Toolbar-item.jp-Notebook-toolbarCellType .jp-select-wrapper.jp-mod-focused {
  border: none;
  box-shadow: none;
}

.jp-Notebook-toolbarCellTypeDropdown select {
  height: 24px;
  font-size: var(--jp-ui-font-size1);
  line-height: 14px;
  border-radius: 0;
  display: block;
}

.jp-Notebook-toolbarCellTypeDropdown span {
  top: 5px !important;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-notebook-dragImage-width: 304px;
  --jp-private-notebook-dragImage-height: 36px;
  --jp-private-notebook-selected-color: var(--md-blue-400);
  --jp-private-notebook-active-color: var(--md-green-400);
}

/*-----------------------------------------------------------------------------
| Imports
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Notebook
|----------------------------------------------------------------------------*/

.jp-NotebookPanel {
  display: block;
  height: 100%;
}

.jp-NotebookPanel.jp-Document {
  min-width: 240px;
  min-height: 120px;
}

.jp-Notebook {
  padding: var(--jp-notebook-padding);
  outline: none;
  overflow: auto;
  background: var(--jp-layout-color0);
}

.jp-Notebook.jp-mod-scrollPastEnd::after {
  display: block;
  content: '';
  min-height: var(--jp-notebook-scroll-padding);
}

.jp-MainAreaWidget-ContainStrict .jp-Notebook * {
  contain: strict;
}

.jp-Notebook-render * {
  contain: none !important;
}

.jp-Notebook .jp-Cell {
  overflow: visible;
}

.jp-Notebook .jp-Cell .jp-InputPrompt {
  cursor: move;
  float: left;
}

/*-----------------------------------------------------------------------------
| Notebook state related styling
|
| The notebook and cells each have states, here are the possibilities:
|
| - Notebook
|   - Command
|   - Edit
| - Cell
|   - None
|   - Active (only one can be active)
|   - Selected (the cells actions are applied to)
|   - Multiselected (when multiple selected, the cursor)
|   - No outputs
|----------------------------------------------------------------------------*/

/* Command or edit modes */

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-InputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-OutputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

/* cell is active */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser {
  background: var(--jp-brand-color1);
}

/* cell is dirty */
.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt {
  color: var(--jp-warn-color1);
}
.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt:before {
  color: var(--jp-warn-color1);
  content: '•';
}

.jp-Notebook .jp-Cell.jp-mod-active.jp-mod-dirty .jp-Collapser {
  background: var(--jp-warn-color1);
}

/* collapser is hovered */
.jp-Notebook .jp-Cell .jp-Collapser:hover {
  box-shadow: var(--jp-elevation-z2);
  background: var(--jp-brand-color1);
  opacity: var(--jp-cell-collapser-not-active-hover-opacity);
}

/* cell is active and collapser is hovered */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser:hover {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/* Command mode */

.jp-Notebook.jp-mod-commandMode .jp-Cell.jp-mod-selected {
  background: var(--jp-notebook-multiselected-color);
}

.jp-Notebook.jp-mod-commandMode
  .jp-Cell.jp-mod-active.jp-mod-selected:not(.jp-mod-multiSelected) {
  background: transparent;
}

/* Edit mode */

.jp-Notebook.jp-mod-editMode .jp-Cell.jp-mod-active .jp-InputArea-editor {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-cell-editor-active-background);
}

/*-----------------------------------------------------------------------------
| Notebook drag and drop
|----------------------------------------------------------------------------*/

.jp-Notebook-cell.jp-mod-dropSource {
  opacity: 0.5;
}

.jp-Notebook-cell.jp-mod-dropTarget,
.jp-Notebook.jp-mod-commandMode
  .jp-Notebook-cell.jp-mod-active.jp-mod-selected.jp-mod-dropTarget {
  border-top-color: var(--jp-private-notebook-selected-color);
  border-top-style: solid;
  border-top-width: 2px;
}

.jp-dragImage {
  display: block;
  flex-direction: row;
  width: var(--jp-private-notebook-dragImage-width);
  height: var(--jp-private-notebook-dragImage-height);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
  overflow: visible;
}

.jp-dragImage-singlePrompt {
  box-shadow: 2px 2px 4px 0px rgba(0, 0, 0, 0.12);
}

.jp-dragImage .jp-dragImage-content {
  flex: 1 1 auto;
  z-index: 2;
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  line-height: var(--jp-code-line-height);
  padding: var(--jp-code-padding);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background-color);
  color: var(--jp-content-font-color3);
  text-align: left;
  margin: 4px 4px 4px 0px;
}

.jp-dragImage .jp-dragImage-prompt {
  flex: 0 0 auto;
  min-width: 36px;
  color: var(--jp-cell-inprompt-font-color);
  padding: var(--jp-code-padding);
  padding-left: 12px;
  font-family: var(--jp-cell-prompt-font-family);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: 1.9;
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
}

.jp-dragImage-multipleBack {
  z-index: -1;
  position: absolute;
  height: 32px;
  width: 300px;
  top: 8px;
  left: 8px;
  background: var(--jp-layout-color2);
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  box-shadow: 2px 2px 4px 0px rgba(0, 0, 0, 0.12);
}

/*-----------------------------------------------------------------------------
| Cell toolbar
|----------------------------------------------------------------------------*/

.jp-NotebookTools {
  display: block;
  min-width: var(--jp-sidebar-min-width);
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  /* This is needed so that all font sizing of children done in ems is
    * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  overflow: auto;
}

.jp-NotebookTools-tool {
  padding: 0px 12px 0 12px;
}

.jp-ActiveCellTool {
  padding: 12px;
  background-color: var(--jp-layout-color1);
  border-top: none !important;
}

.jp-ActiveCellTool .jp-InputArea-prompt {
  flex: 0 0 auto;
  padding-left: 0px;
}

.jp-ActiveCellTool .jp-InputArea-editor {
  flex: 1 1 auto;
  background: var(--jp-cell-editor-background);
  border-color: var(--jp-cell-editor-border-color);
}

.jp-ActiveCellTool .jp-InputArea-editor .CodeMirror {
  background: transparent;
}

.jp-MetadataEditorTool {
  flex-direction: column;
  padding: 12px 0px 12px 0px;
}

.jp-RankedPanel > :not(:first-child) {
  margin-top: 12px;
}

.jp-KeySelector select.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: var(--jp-border-width) solid var(--jp-border-color1);
}

.jp-KeySelector label,
.jp-MetadataEditorTool label {
  line-height: 1.4;
}

.jp-NotebookTools .jp-select-wrapper {
  margin-top: 4px;
  margin-bottom: 0px;
}

.jp-NotebookTools .jp-Collapse {
  margin-top: 16px;
}

/*-----------------------------------------------------------------------------
| Presentation Mode (.jp-mod-presentationMode)
|----------------------------------------------------------------------------*/

.jp-mod-presentationMode .jp-Notebook {
  --jp-content-font-size1: var(--jp-content-presentation-font-size1);
  --jp-code-font-size: var(--jp-code-presentation-font-size);
}

.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-InputPrompt,
.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-OutputPrompt {
  flex: 0 0 110px;
}

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Cell-Placeholder {
  padding-left: 55px;
}

.jp-Cell-Placeholder-wrapper {
  background: #fff;
  border: 1px solid;
  border-color: #e5e6e9 #dfe0e4 #d0d1d5;
  border-radius: 4px;
  -webkit-border-radius: 4px;
  margin: 10px 15px;
}

.jp-Cell-Placeholder-wrapper-inner {
  padding: 15px;
  position: relative;
}

.jp-Cell-Placeholder-wrapper-body {
  background-repeat: repeat;
  background-size: 50% auto;
}

.jp-Cell-Placeholder-wrapper-body div {
  background: #f6f7f8;
  background-image: -webkit-linear-gradient(
    left,
    #f6f7f8 0%,
    #edeef1 20%,
    #f6f7f8 40%,
    #f6f7f8 100%
  );
  background-repeat: no-repeat;
  background-size: 800px 104px;
  height: 104px;
  position: relative;
}

.jp-Cell-Placeholder-wrapper-body div {
  position: absolute;
  right: 15px;
  left: 15px;
  top: 15px;
}

div.jp-Cell-Placeholder-h1 {
  top: 20px;
  height: 20px;
  left: 15px;
  width: 150px;
}

div.jp-Cell-Placeholder-h2 {
  left: 15px;
  top: 50px;
  height: 10px;
  width: 100px;
}

div.jp-Cell-Placeholder-content-1,
div.jp-Cell-Placeholder-content-2,
div.jp-Cell-Placeholder-content-3 {
  left: 15px;
  right: 15px;
  height: 10px;
}

div.jp-Cell-Placeholder-content-1 {
  top: 100px;
}

div.jp-Cell-Placeholder-content-2 {
  top: 120px;
}

div.jp-Cell-Placeholder-content-3 {
  top: 140px;
}

</style>

    <style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
The following CSS variables define the main, public API for styling JupyterLab.
These variables should be used by all plugins wherever possible. In other
words, plugins should not define custom colors, sizes, etc unless absolutely
necessary. This enables users to change the visual theme of JupyterLab
by changing these variables.

Many variables appear in an ordered sequence (0,1,2,3). These sequences
are designed to work well together, so for example, `--jp-border-color1` should
be used with `--jp-layout-color1`. The numbers have the following meanings:

* 0: super-primary, reserved for special emphasis
* 1: primary, most important under normal situations
* 2: secondary, next most important under normal situations
* 3: tertiary, next most important under normal situations

Throughout JupyterLab, we are mostly following principles from Google's
Material Design when selecting colors. We are not, however, following
all of MD as it is not optimized for dense, information rich UIs.
*/

:root {
  /* Elevation
   *
   * We style box-shadows using Material Design's idea of elevation. These particular numbers are taken from here:
   *
   * https://github.com/material-components/material-components-web
   * https://material-components-web.appspot.com/elevation.html
   */

  --jp-shadow-base-lightness: 0;
  --jp-shadow-umbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.2
  );
  --jp-shadow-penumbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.14
  );
  --jp-shadow-ambient-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.12
  );
  --jp-elevation-z0: none;
  --jp-elevation-z1: 0px 2px 1px -1px var(--jp-shadow-umbra-color),
    0px 1px 1px 0px var(--jp-shadow-penumbra-color),
    0px 1px 3px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z2: 0px 3px 1px -2px var(--jp-shadow-umbra-color),
    0px 2px 2px 0px var(--jp-shadow-penumbra-color),
    0px 1px 5px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z4: 0px 2px 4px -1px var(--jp-shadow-umbra-color),
    0px 4px 5px 0px var(--jp-shadow-penumbra-color),
    0px 1px 10px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z6: 0px 3px 5px -1px var(--jp-shadow-umbra-color),
    0px 6px 10px 0px var(--jp-shadow-penumbra-color),
    0px 1px 18px 0px var(--jp-shadow-ambient-color);
  --jp-elevation-z8: 0px 5px 5px -3px var(--jp-shadow-umbra-color),
    0px 8px 10px 1px var(--jp-shadow-penumbra-color),
    0px 3px 14px 2px var(--jp-shadow-ambient-color);
  --jp-elevation-z12: 0px 7px 8px -4px var(--jp-shadow-umbra-color),
    0px 12px 17px 2px var(--jp-shadow-penumbra-color),
    0px 5px 22px 4px var(--jp-shadow-ambient-color);
  --jp-elevation-z16: 0px 8px 10px -5px var(--jp-shadow-umbra-color),
    0px 16px 24px 2px var(--jp-shadow-penumbra-color),
    0px 6px 30px 5px var(--jp-shadow-ambient-color);
  --jp-elevation-z20: 0px 10px 13px -6px var(--jp-shadow-umbra-color),
    0px 20px 31px 3px var(--jp-shadow-penumbra-color),
    0px 8px 38px 7px var(--jp-shadow-ambient-color);
  --jp-elevation-z24: 0px 11px 15px -7px var(--jp-shadow-umbra-color),
    0px 24px 38px 3px var(--jp-shadow-penumbra-color),
    0px 9px 46px 8px var(--jp-shadow-ambient-color);

  /* Borders
   *
   * The following variables, specify the visual styling of borders in JupyterLab.
   */

  --jp-border-width: 1px;
  --jp-border-color0: var(--md-grey-400);
  --jp-border-color1: var(--md-grey-400);
  --jp-border-color2: var(--md-grey-300);
  --jp-border-color3: var(--md-grey-200);
  --jp-border-radius: 2px;

  /* UI Fonts
   *
   * The UI font CSS variables are used for the typography all of the JupyterLab
   * user interface elements that are not directly user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-ui-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-ui-font-scale-factor: 1.2;
  --jp-ui-font-size0: 0.83333em;
  --jp-ui-font-size1: 13px; /* Base font size */
  --jp-ui-font-size2: 1.2em;
  --jp-ui-font-size3: 1.44em;

  --jp-ui-font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica,
    Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';

  /*
   * Use these font colors against the corresponding main layout colors.
   * In a light theme, these go from dark to light.
   */

  /* Defaults use Material Design specification */
  --jp-ui-font-color0: rgba(0, 0, 0, 1);
  --jp-ui-font-color1: rgba(0, 0, 0, 0.87);
  --jp-ui-font-color2: rgba(0, 0, 0, 0.54);
  --jp-ui-font-color3: rgba(0, 0, 0, 0.38);

  /*
   * Use these against the brand/accent/warn/error colors.
   * These will typically go from light to darker, in both a dark and light theme.
   */

  --jp-ui-inverse-font-color0: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color1: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color2: rgba(255, 255, 255, 0.7);
  --jp-ui-inverse-font-color3: rgba(255, 255, 255, 0.5);

  /* Content Fonts
   *
   * Content font variables are used for typography of user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-content-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-content-line-height: 1.6;
  --jp-content-font-scale-factor: 1.2;
  --jp-content-font-size0: 0.83333em;
  --jp-content-font-size1: 14px; /* Base font size */
  --jp-content-font-size2: 1.2em;
  --jp-content-font-size3: 1.44em;
  --jp-content-font-size4: 1.728em;
  --jp-content-font-size5: 2.0736em;

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-content-presentation-font-size1: 17px;

  --jp-content-heading-line-height: 1;
  --jp-content-heading-margin-top: 1.2em;
  --jp-content-heading-margin-bottom: 0.8em;
  --jp-content-heading-font-weight: 500;

  /* Defaults use Material Design specification */
  --jp-content-font-color0: rgba(0, 0, 0, 1);
  --jp-content-font-color1: rgba(0, 0, 0, 0.87);
  --jp-content-font-color2: rgba(0, 0, 0, 0.54);
  --jp-content-font-color3: rgba(0, 0, 0, 0.38);

  --jp-content-link-color: var(--md-blue-700);

  --jp-content-font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji',
    'Segoe UI Symbol';

  /*
   * Code Fonts
   *
   * Code font variables are used for typography of code and other monospaces content.
   */

  --jp-code-font-size: 13px;
  --jp-code-line-height: 1.3077; /* 17px for 13px base */
  --jp-code-padding: 5px; /* 5px for 13px base, codemirror highlighting needs integer px value */
  --jp-code-font-family-default: Menlo, Consolas, 'DejaVu Sans Mono', monospace;
  --jp-code-font-family: var(--jp-code-font-family-default);

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-code-presentation-font-size: 16px;

  /* may need to tweak cursor width if you change font size */
  --jp-code-cursor-width0: 1.4px;
  --jp-code-cursor-width1: 2px;
  --jp-code-cursor-width2: 4px;

  /* Layout
   *
   * The following are the main layout colors use in JupyterLab. In a light
   * theme these would go from light to dark.
   */

  --jp-layout-color0: white;
  --jp-layout-color1: white;
  --jp-layout-color2: var(--md-grey-200);
  --jp-layout-color3: var(--md-grey-400);
  --jp-layout-color4: var(--md-grey-600);

  /* Inverse Layout
   *
   * The following are the inverse layout colors use in JupyterLab. In a light
   * theme these would go from dark to light.
   */

  --jp-inverse-layout-color0: #111111;
  --jp-inverse-layout-color1: var(--md-grey-900);
  --jp-inverse-layout-color2: var(--md-grey-800);
  --jp-inverse-layout-color3: var(--md-grey-700);
  --jp-inverse-layout-color4: var(--md-grey-600);

  /* Brand/accent */

  --jp-brand-color0: var(--md-blue-900);
  --jp-brand-color1: var(--md-blue-700);
  --jp-brand-color2: var(--md-blue-300);
  --jp-brand-color3: var(--md-blue-100);
  --jp-brand-color4: var(--md-blue-50);

  --jp-accent-color0: var(--md-green-900);
  --jp-accent-color1: var(--md-green-700);
  --jp-accent-color2: var(--md-green-300);
  --jp-accent-color3: var(--md-green-100);

  /* State colors (warn, error, success, info) */

  --jp-warn-color0: var(--md-orange-900);
  --jp-warn-color1: var(--md-orange-700);
  --jp-warn-color2: var(--md-orange-300);
  --jp-warn-color3: var(--md-orange-100);

  --jp-error-color0: var(--md-red-900);
  --jp-error-color1: var(--md-red-700);
  --jp-error-color2: var(--md-red-300);
  --jp-error-color3: var(--md-red-100);

  --jp-success-color0: var(--md-green-900);
  --jp-success-color1: var(--md-green-700);
  --jp-success-color2: var(--md-green-300);
  --jp-success-color3: var(--md-green-100);

  --jp-info-color0: var(--md-cyan-900);
  --jp-info-color1: var(--md-cyan-700);
  --jp-info-color2: var(--md-cyan-300);
  --jp-info-color3: var(--md-cyan-100);

  /* Cell specific styles */

  --jp-cell-padding: 5px;

  --jp-cell-collapser-width: 8px;
  --jp-cell-collapser-min-height: 20px;
  --jp-cell-collapser-not-active-hover-opacity: 0.6;

  --jp-cell-editor-background: var(--md-grey-100);
  --jp-cell-editor-border-color: var(--md-grey-300);
  --jp-cell-editor-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-cell-editor-active-background: var(--jp-layout-color0);
  --jp-cell-editor-active-border-color: var(--jp-brand-color1);

  --jp-cell-prompt-width: 64px;
  --jp-cell-prompt-font-family: var(--jp-code-font-family-default);
  --jp-cell-prompt-letter-spacing: 0px;
  --jp-cell-prompt-opacity: 1;
  --jp-cell-prompt-not-active-opacity: 0.5;
  --jp-cell-prompt-not-active-font-color: var(--md-grey-700);
  /* A custom blend of MD grey and blue 600
   * See https://meyerweb.com/eric/tools/color-blend/#546E7A:1E88E5:5:hex */
  --jp-cell-inprompt-font-color: #307fc1;
  /* A custom blend of MD grey and orange 600
   * https://meyerweb.com/eric/tools/color-blend/#546E7A:F4511E:5:hex */
  --jp-cell-outprompt-font-color: #bf5b3d;

  /* Notebook specific styles */

  --jp-notebook-padding: 10px;
  --jp-notebook-select-background: var(--jp-layout-color1);
  --jp-notebook-multiselected-color: var(--md-blue-50);

  /* The scroll padding is calculated to fill enough space at the bottom of the
  notebook to show one single-line cell (with appropriate padding) at the top
  when the notebook is scrolled all the way to the bottom. We also subtract one
  pixel so that no scrollbar appears if we have just one single-line cell in the
  notebook. This padding is to enable a 'scroll past end' feature in a notebook.
  */
  --jp-notebook-scroll-padding: calc(
    100% - var(--jp-code-font-size) * var(--jp-code-line-height) -
      var(--jp-code-padding) - var(--jp-cell-padding) - 1px
  );

  /* Rendermime styles */

  --jp-rendermime-error-background: #fdd;
  --jp-rendermime-table-row-background: var(--md-grey-100);
  --jp-rendermime-table-row-hover-background: var(--md-light-blue-50);

  /* Dialog specific styles */

  --jp-dialog-background: rgba(0, 0, 0, 0.25);

  /* Console specific styles */

  --jp-console-padding: 10px;

  /* Toolbar specific styles */

  --jp-toolbar-border-color: var(--jp-border-color1);
  --jp-toolbar-micro-height: 8px;
  --jp-toolbar-background: var(--jp-layout-color1);
  --jp-toolbar-box-shadow: 0px 0px 2px 0px rgba(0, 0, 0, 0.24);
  --jp-toolbar-header-margin: 4px 4px 0px 4px;
  --jp-toolbar-active-background: var(--md-grey-300);

  /* Statusbar specific styles */

  --jp-statusbar-height: 24px;

  /* Input field styles */

  --jp-input-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-input-active-background: var(--jp-layout-color1);
  --jp-input-hover-background: var(--jp-layout-color1);
  --jp-input-background: var(--md-grey-100);
  --jp-input-border-color: var(--jp-border-color1);
  --jp-input-active-border-color: var(--jp-brand-color1);
  --jp-input-active-box-shadow-color: rgba(19, 124, 189, 0.3);

  /* General editor styles */

  --jp-editor-selected-background: #d9d9d9;
  --jp-editor-selected-focused-background: #d7d4f0;
  --jp-editor-cursor-color: var(--jp-ui-font-color0);

  /* Code mirror specific styles */

  --jp-mirror-editor-keyword-color: #008000;
  --jp-mirror-editor-atom-color: #88f;
  --jp-mirror-editor-number-color: #080;
  --jp-mirror-editor-def-color: #00f;
  --jp-mirror-editor-variable-color: var(--md-grey-900);
  --jp-mirror-editor-variable-2-color: #05a;
  --jp-mirror-editor-variable-3-color: #085;
  --jp-mirror-editor-punctuation-color: #05a;
  --jp-mirror-editor-property-color: #05a;
  --jp-mirror-editor-operator-color: #aa22ff;
  --jp-mirror-editor-comment-color: #408080;
  --jp-mirror-editor-string-color: #ba2121;
  --jp-mirror-editor-string-2-color: #708;
  --jp-mirror-editor-meta-color: #aa22ff;
  --jp-mirror-editor-qualifier-color: #555;
  --jp-mirror-editor-builtin-color: #008000;
  --jp-mirror-editor-bracket-color: #997;
  --jp-mirror-editor-tag-color: #170;
  --jp-mirror-editor-attribute-color: #00c;
  --jp-mirror-editor-header-color: blue;
  --jp-mirror-editor-quote-color: #090;
  --jp-mirror-editor-link-color: #00c;
  --jp-mirror-editor-error-color: #f00;
  --jp-mirror-editor-hr-color: #999;

  /* Vega extension styles */

  --jp-vega-background: white;

  /* Sidebar-related styles */

  --jp-sidebar-min-width: 250px;

  /* Search-related styles */

  --jp-search-toggle-off-opacity: 0.5;
  --jp-search-toggle-hover-opacity: 0.8;
  --jp-search-toggle-on-opacity: 1;
  --jp-search-selected-match-background-color: rgb(245, 200, 0);
  --jp-search-selected-match-color: black;
  --jp-search-unselected-match-background-color: var(
    --jp-inverse-layout-color0
  );
  --jp-search-unselected-match-color: var(--jp-ui-inverse-font-color0);

  /* Icon colors that work well with light or dark backgrounds */
  --jp-icon-contrast-color0: var(--md-purple-600);
  --jp-icon-contrast-color1: var(--md-green-600);
  --jp-icon-contrast-color2: var(--md-pink-600);
  --jp-icon-contrast-color3: var(--md-blue-600);
}
</style>

<style type="text/css">
/* Force rendering true colors when outputing to pdf */
* {
  -webkit-print-color-adjust: exact;
}

/* Misc */
a.anchor-link {
  display: none;
}

.highlight  {
  margin: 0.4em;
}

/* Input area styling */
.jp-InputArea {
  overflow: hidden;
}

.jp-InputArea-editor {
  overflow: hidden;
}

.CodeMirror pre {
  margin: 0;
  padding: 0;
}

/* Using table instead of flexbox so that we can use break-inside property */
/* CSS rules under this comment should not be required anymore after we move to the JupyterLab 4.0 CSS */


.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-prompt {
  min-width: calc(
    var(--jp-cell-prompt-width) - var(--jp-private-cell-scrolling-output-offset)
  );
}

.jp-OutputArea-child {
  display: table;
  width: 100%;
}

.jp-OutputPrompt {
  display: table-cell;
  vertical-align: top;
  min-width: var(--jp-cell-prompt-width);
}

body[data-format='mobile'] .jp-OutputPrompt {
  display: table-row;
}

.jp-OutputArea-output {
  display: table-cell;
  width: 100%;
}

body[data-format='mobile'] .jp-OutputArea-child .jp-OutputArea-output {
  display: table-row;
}

.jp-OutputArea-output.jp-OutputArea-executeResult {
  width: 100%;
}

/* Hiding the collapser by default */
.jp-Collapser {
  display: none;
}

@media print {
  .jp-Cell-inputWrapper,
  .jp-Cell-outputWrapper {
    display: block;
  }

  .jp-OutputArea-child {
    break-inside: avoid-page;
  }
}
</style>

<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/latest.js?config=TeX-AMS_CHTML-full,Safe"> </script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    init_mathjax = function() {
        if (window.MathJax) {
        // MathJax loaded
            MathJax.Hub.Config({
                TeX: {
                    equationNumbers: {
                    autoNumber: "AMS",
                    useLabelIds: true
                    }
                },
                tex2jax: {
                    inlineMath: [ ['$','$'], ["\\(","\\)"] ],
                    displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
                    processEscapes: true,
                    processEnvironments: true
                },
                displayAlign: 'center',
                CommonHTML: {
                    linebreaks: {
                    automatic: true
                    }
                }
            });

            MathJax.Hub.Queue(["Typeset", MathJax.Hub]);
        }
    }
    init_mathjax();
    </script>
    <!-- End of mathjax configuration --></head>
<body class="jp-Notebook" data-jp-theme-light="true" data-jp-theme-name="JupyterLab Light">

<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p style="text-align: center; font-size: 40px;">Reciept Reading OCR</p>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Introduction</strong>:
    In this mini project I developed a script for preprocessing a reciept then running it through an Optical Character Recognition model to scan the reciept into text. With this text, I used regex to wrangle the data into a breakdown of items and their costs. The inspiration for this project was splitting a costco reciept with my roommates so the examples will follow a costco reciept through the pipeline and final output</p>

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Imports</strong>: I import cv2 and PIL for image processing, and pytesseract for OCR</p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">cv2</span>
<span class="kn">from</span> <span class="nn">PIL</span> <span class="kn">import</span> <span class="n">Image</span>
<span class="kn">import</span> <span class="nn">pytesseract</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">math</span>
<span class="kn">import</span> <span class="nn">re</span>

<span class="kn">from</span> <span class="nn">skimage.filters</span> <span class="kn">import</span> <span class="n">threshold_local</span>

<span class="n">pytesseract</span><span class="o">.</span><span class="n">pytesseract</span><span class="o">.</span><span class="n">tesseract_cmd</span> <span class="o">=</span> <span class="sa">r</span><span class="s1">'C:\Program Files\Tesseract-OCR\tesseract.exe'</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Basic Functions</strong> here I wrote a few basic functions to be called later. Kernel_getter will be used for retrieving the morphological kernel, opener is used to preform the opening operation on the image, which will break narrow isthmuses between characters, allowing for better reading, plot rgb will help use visualize our processed image)</p>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">kernel_getter</span><span class="p">(</span><span class="n">I_shape</span><span class="p">):</span>
    <span class="k">return</span> <span class="p">((</span><span class="nb">max</span><span class="p">(</span><span class="n">I_shape</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span><span class="o">//</span><span class="mi">20</span><span class="p">,</span> <span class="mi">1</span><span class="p">)</span> <span class="o">*</span> <span class="mi">4</span><span class="p">)</span> <span class="o">+</span> <span class="mi">1</span><span class="p">,</span> <span class="p">(</span><span class="nb">max</span><span class="p">(</span><span class="n">I_shape</span><span class="p">[</span><span class="mi">1</span><span class="p">]</span><span class="o">//</span><span class="mi">20</span><span class="p">,</span> <span class="mi">1</span><span class="p">)</span> <span class="o">*</span> <span class="mi">4</span><span class="p">)</span> <span class="o">+</span> <span class="mi">1</span><span class="p">)</span>


<span class="k">def</span> <span class="nf">opener</span><span class="p">(</span><span class="n">I</span><span class="p">):</span>
    <span class="n">dimensions</span> <span class="o">=</span> <span class="n">kernel_getter</span><span class="p">(</span><span class="n">I</span><span class="o">.</span><span class="n">shape</span><span class="p">)</span>
    <span class="n">elm</span> <span class="o">=</span> <span class="n">cv2</span><span class="o">.</span><span class="n">getStructuringElement</span><span class="p">(</span><span class="n">cv2</span><span class="o">.</span><span class="n">MORPH_RECT</span><span class="p">,</span> <span class="p">(</span><span class="n">dimensions</span><span class="p">[</span><span class="mi">0</span><span class="p">],</span><span class="n">dimensions</span><span class="p">[</span><span class="mi">1</span><span class="p">]))</span>
    <span class="n">out</span> <span class="o">=</span> <span class="n">cv2</span><span class="o">.</span><span class="n">morphologyEx</span><span class="p">(</span><span class="n">I</span><span class="p">,</span> <span class="n">cv2</span><span class="o">.</span><span class="n">MORPH_OPEN</span><span class="p">,</span> <span class="n">elm</span><span class="p">)</span>
    <span class="k">return</span> <span class="n">out</span>

<span class="k">def</span> <span class="nf">plot_rgb</span><span class="p">(</span><span class="n">image</span><span class="p">):</span>
    <span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">16</span><span class="p">,</span><span class="mi">10</span><span class="p">))</span>
    <span class="k">return</span> <span class="n">plt</span><span class="o">.</span><span class="n">imshow</span><span class="p">(</span><span class="n">cv2</span><span class="o">.</span><span class="n">cvtColor</span><span class="p">(</span><span class="n">image</span><span class="p">,</span> <span class="n">cv2</span><span class="o">.</span><span class="n">COLOR_BGR2RGB</span><span class="p">))</span>
    
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
<li><p><strong>Image Loading and Preprocessing:</strong></p>
<ul>
<li>Loads an image using OpenCV (<code>cv2</code>) and converts it to grayscale.</li>
<li>Adds a border to the image to avoid loss of information during later processing.</li>
</ul>
</li>
</ol>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">I</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">asarray</span><span class="p">(</span><span class="n">Image</span><span class="o">.</span><span class="n">open</span><span class="p">(</span><span class="s2">"tn1200w_15680401584732.jpeg"</span><span class="p">))</span>
<span class="n">I</span> <span class="o">=</span> <span class="n">cv2</span><span class="o">.</span><span class="n">cvtColor</span><span class="p">(</span><span class="n">I</span><span class="p">,</span> <span class="n">cv2</span><span class="o">.</span><span class="n">COLOR_BGR2GRAY</span><span class="p">)</span>
<span class="n">top</span><span class="p">,</span> <span class="n">bottom</span><span class="p">,</span> <span class="n">left</span><span class="p">,</span> <span class="n">right</span> <span class="o">=</span> <span class="mi">20</span><span class="p">,</span> <span class="mi">20</span><span class="p">,</span> <span class="mi">20</span><span class="p">,</span> <span class="mi">20</span>
<span class="n">border_color</span> <span class="o">=</span> <span class="p">[</span><span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">]</span> 
<span class="n">I</span> <span class="o">=</span> <span class="n">cv2</span><span class="o">.</span><span class="n">copyMakeBorder</span><span class="p">(</span><span class="n">I</span><span class="p">,</span> <span class="n">top</span><span class="p">,</span> <span class="n">bottom</span><span class="p">,</span> <span class="n">left</span><span class="p">,</span> <span class="n">right</span><span class="p">,</span> <span class="n">cv2</span><span class="o">.</span><span class="n">BORDER_CONSTANT</span><span class="p">,</span> <span class="n">value</span><span class="o">=</span><span class="n">border_color</span><span class="p">)</span>
<span class="n">plot_rgb</span><span class="p">(</span><span class="n">I</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[&nbsp;]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>&lt;matplotlib.image.AxesImage at 0x20da44322f0&gt;</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
class="
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
<li><p><strong>Image Filtering and Thresholding:</strong></p>
<ul>
<li>Generates a kernel and performs image filtering (details not provided in the snippet).</li>
<li>Thresholds the image using Otsu's method to segment it into foreground and background.</li>
<li>Applies Gaussian blur to reduce noise in the image.</li>
</ul>
</li>
</ol>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">ker</span> <span class="o">=</span> <span class="n">kernel_getter</span><span class="p">(</span><span class="n">I</span><span class="o">.</span><span class="n">shape</span><span class="p">)</span>
<span class="n">blur</span> <span class="o">=</span> <span class="n">cv2</span><span class="o">.</span><span class="n">GaussianBlur</span><span class="p">(</span><span class="n">I</span><span class="p">,</span> <span class="n">ker</span><span class="p">,</span> <span class="mi">0</span><span class="p">)</span>
<span class="n">th</span><span class="p">,</span> <span class="n">bined</span> <span class="o">=</span> <span class="n">cv2</span><span class="o">.</span><span class="n">threshold</span><span class="p">(</span><span class="n">blur</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">255</span><span class="p">,</span> <span class="n">cv2</span><span class="o">.</span><span class="n">THRESH_OTSU</span><span class="p">)</span>
<span class="n">opened</span> <span class="o">=</span> <span class="n">opener</span><span class="p">(</span><span class="n">bined</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
<li><p><strong>Edge Detection and Contour Finding:</strong></p>
<ul>
<li>Performs Canny edge detection to identify edges in the thresholded image.</li>
<li>Finds contours using the <code>cv2.findContours</code> function.</li>
</ul>
</li>
</ol>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">edged</span> <span class="o">=</span> <span class="n">cv2</span><span class="o">.</span><span class="n">Canny</span><span class="p">(</span><span class="n">opened</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mf">.5</span><span class="p">,</span> <span class="n">apertureSize</span><span class="o">=</span><span class="mi">3</span><span class="p">)</span>
<span class="n">contours</span><span class="p">,</span> <span class="n">hierarchy</span> <span class="o">=</span> <span class="n">cv2</span><span class="o">.</span><span class="n">findContours</span><span class="p">(</span><span class="n">edged</span><span class="p">,</span> <span class="n">cv2</span><span class="o">.</span><span class="n">RETR_EXTERNAL</span><span class="p">,</span> <span class="n">cv2</span><span class="o">.</span><span class="n">RETR_LIST</span><span class="p">)</span>
<span class="n">plot_rgb</span><span class="p">(</span><span class="n">edged</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[&nbsp;]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>&lt;matplotlib.image.AxesImage at 0x20d9fcd2410&gt;</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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WXHfffflPQOAbkgkQgc1aNCgePfdd71gBYBciETooCZMmBAPPPBA3jMA6KZEInRAPXr0iOrq6igWi3lPAaCbEonQAfXr1y9qampi+fLleU8BoJsSiQAAJEQidEAXXXRR3HLLLXnPAKAbE4nQAQ0cODDeeuutvGcA0I2JRAAAEiIRAICESAQAICESoYMZMGBAvPPOO5FlWd5TAOjGRCJ0MJ/61Kfi6aefjubm5rynANCNiUQAABIiEQCAhEgEACAhEgEASIhE6EAqKirisMMOi2eeeSbvKQB0cyIROpCysrKoq6uLVatW5T0FgG5OJEIHUldXF6tXr857BgCIROhILrroorj99tvzngEAIhEAgJRIBAAgIRIBAEiIRAAAEiIRAICESAQAICESoYPYb7/9oqGhIRoaGvKeAgAiETqKPn36RGNjYzQ1NeU9BQBEIgAAKZEIAEBCJAIAkBCJAAAkRCJ0EIVCIbIsy3sGAESESIQO49xzz4177rkn7xkAEBEiETqMPn36xPr16/OeAQARIRIBAPgAIhEAgIRIBAAgIRIBAEiIRAAAEiIRAICESIQO4IwzzogHH3ww7xkAUCISoQPo379/vPvuu3nPAIASkQgAQEIkAgCQEIkAACREIgAACZEIAEBCJAIAkBCJAAAkRCJ0AIVCIbIsy3sGAJSIRMhZv379Yo899oglS5bkPQUASkQi5Ky8vDwqKiqiqakp7ykAUCISAQBIiEQAABIiEQCAhEgEACAhEgEASIhEAAASIhEAgIRIhJxVVFTEli1b8p4BAK2IRMjZZZddFj/4wQ/yngEArYhEyFmvXr1i48aNec8AgFZEIgAACZEIAEBCJAIAkBCJAAAkRCIAAAmRCABAQiQCAJAQiQAAJEQiAAAJkQgAQEIkAgCQaPNInD59ehx11FHRp0+fGDRoUJx22mnx5z//udWZLMti6tSpUV9fHz179owTTjghnn/++VZnGhsb45JLLokBAwZE7969Y9y4cbFy5cq2ngsAwAdo80icM2dOXHzxxfH000/H7Nmzo7m5OcaMGRPvvfde6cx1110XN954Y9x6662xYMGCqKuri5NPPjnWr19fOjNlypR46KGHYubMmTF37tzYsGFDjB07NrZu3drWkyE3hx9+eCxZsiSampryngIArWXtbM2aNVlEZHPmzMmyLMtaWlqyurq6bMaMGaUzmzdvzmpqarLbb789y7IsW7t2bVZZWZnNnDmzdOb111/PysrKskcffXSb/n+LxWIWES5Xh74+97nPZaeffnruO1yurnwNGTIkmzZtWu47XK6OdhWLxY9sqXb/mcRisRgREbW1tRERsWzZsli9enWMGTOmdKa6ujqOP/74mDdvXkRELFy4MLZs2dLqTH19fQwfPrx05v0aGxtj3bp1rS4AAHZMu0ZilmVx6aWXxujRo2P48OEREbF69eqIiBg8eHCrs4MHDy7dt3r16qiqqop+/fp96Jn3mz59etTU1JSuvfbaq62/HACAbqNdI3HSpEnxxz/+MX72s58l9xUKhVZ/zrIsue39PurM1VdfHcVisXStWLFix4cDAHRz7RaJl1xySTz88MPxxBNPxJ577lm6va6uLiIieUZwzZo1pWcX6+rqoqmpKRoaGj70zPtVV1dH3759W10AAOyYNo/ELMti0qRJMWvWrPj1r38dQ4cObXX/0KFDo66uLmbPnl26rampKebMmROjRo2KiIiRI0dGZWVlqzOrVq2KJUuWlM4AANB+Ktr6E1588cXxwAMPxL/8y79Enz59Ss8Y1tTURM+ePaNQKMSUKVNi2rRpMWzYsBg2bFhMmzYtevXqFePHjy+dnThxYlx22WXRv3//qK2tjcsvvzxGjBgRJ510UltPhtzU1tbGqlWr8p4BAKnteTubbREf8jLrn/zkJ6UzLS0t2TXXXJPV1dVl1dXV2XHHHZctXry41efZtGlTNmnSpKy2tjbr2bNnNnbs2Gz58uXbvMNb4Lg6+lVRUZHdcccdue9wubr65S1wXK4Pvj7uLXDa/JnEf+/Ej1YoFGLq1KkxderUDz3To0ePuOWWW+KWW25pw3UAAGwLv7sZAICESAQAICESAQBIiEQAABIiEQCAhEiEnJx33nlx77335j0DAD6QSISc7L333n7HOAAdlkgEACAhEgEASIhEAAASIhEAgIRIBAAgIRIBAEiIRAAAEiIRclBbWxuNjY2xfv36vKcAwAcSiZCDwYMHR2NjYxSLxbynAMAHEokAACREIgAACZEIAEBCJAIAkBCJAAAkRCIAAAmRCABAQiRCDs4444x44IEH8p4B3cI//MM/xN133533DOh0RCLkYI899oiVK1fmPQO6hb333juWL1+e9wzodEQiAAAJkQgAQEIkAgCQEIkAACREIgBd1ogRI2Lp0qWxdevWvKdApyMSAeiy9t9//3jllVeipaUl7ynQ6YhEAAASIhEAgIRIBAAgIRJhFxs1alTMmzcv7xkA8JFEIuxiBx98cPzpT3/KewYAfCSRCECX1bNnz9i0aVPeM6BTEokAdElVVVUxevTo+NWvfpX3FOiURCIAAAmRCLtYeXm53/4Au0B1dXU0NTXlPQM6LZEIu1BNTU0MGzYsFi5cmPcU6PKuuOKKuOGGG/KeAZ2WSIRdqFAoRFlZmWcSYReorq6OxsbGvGdApyUSAQBIiEQAABIiEQCAhEgEACAhEmEXuuCCC+KOO+7IewYAfCyRCLvQnnvuGStXrsx7BgB8LJEIAEBCJAIAkBCJAHQ5AwcOjA0bNsTGjRvzngKdlkgEoMvZY489olgsxoYNG/KeAp2WSAQAICESYRcZNGhQvPPOO9Hc3Jz3FAD4WCIRdpHhw4fHSy+9FI2NjXlPAYCPJRIBAEiIRAAAEiIRgC6nsrIytmzZkvcM6NREIgBdzte+9rW4++67854BnZpIBKDLqa6ujqamprxnQKcmEgEASIhEAAASIhF2gUKhEMcee2w89dRTeU8BgG0iEmEXKBQKsc8++8Srr76a9xQA2CYiEQCAhEgEoEspFArR0tKS9wzo9EQiAF3K1772tbjvvvvyngGdnkgEoEvp3bt3vPfee3nPgE5PJMIucNRRR8UzzzyT9wwA2GYiEXaBz372szF79uy8ZwDANhOJAAAkRCIAAAmRCECXUVNTEwMHDoyXX3457ynQ6YlEALqMqqqq6NmzZ6xbty7vKdDpiUQAABIiEQCAhEiEdrbbbrtFlmWxYcOGvKcAwDYTidDOBg8eHFmWxVtvvZX3FADYZiIRAICESAQAICESAQBIiEQAABIiEYAuY+DAgV4kBm1EJALQZUyaNCluvvnmvGdAlyASAQBIiEQAABIiEQCAhEgEACAhEqGdnXjiiTF79uy8ZwDAdhGJ0M6OOuqomD9/ft4zAGC7iEQAuoTq6upobGyMLMvyngJdgkgEoEv4zGc+E0899VQ0NTXlPQW6BJEIQJdQKBSipaUl7xnQZYhEAAASIhEAgIRIBKDTKy8vj2OPPTbmzp2b9xToMkQiAJ1eoVCIgQMHxpo1a/KeAl2GSAQAICESoR1VVlbGli1b8p4BANtNJEI7Ov3002PWrFne3BeATkckQjuqqKiI5ubmvGcAwHYTiQAAJEQiAAAJkQhAp/flL385Zs2alfcM6FJEIgCd3iGHHBLPP/983jOgSxGJAAAkRCIAAAmRCO2kvLw8dt9993j77bfzngIA200kQjvp2bNnDBs2LJYsWZL3FADYbiIRAICESAQAICESAQBIiEQAABLtHonTp0+PQqEQU6ZMKd2WZVlMnTo16uvro2fPnnHCCSckb4La2NgYl1xySQwYMCB69+4d48aNi5UrV7b3XAAAop0jccGCBXHnnXfGJz/5yVa3X3fddXHjjTfGrbfeGgsWLIi6uro4+eSTY/369aUzU6ZMiYceeihmzpwZc+fOjQ0bNsTYsWNj69at7TkZAIBox0jcsGFDTJgwIe66667o169f6fYsy+Kmm26K7373u/HFL34xhg8fHv/0T/8UGzdujAceeCAiIorFYtx9991xww03xEknnRSHH3543H///bF48eJ4/PHH22syAAD/od0i8eKLL45TTjklTjrppFa3L1u2LFavXh1jxowp3VZdXR3HH398zJs3LyIiFi5cGFu2bGl1pr6+PoYPH146836NjY2xbt26VhcAADumoj0+6cyZM+PZZ5+NBQsWJPetXr06IiIGDx7c6vbBgwfHa6+9VjpTVVXV6hnIv57568e/3/Tp0+O///f/3hbzAQC6vTZ/JnHFihUxefLkuP/++6NHjx4feq5QKLT6c5ZlyW3v91Fnrr766igWi6VrxYoV2z8e2tDEiRPjxz/+cd4zoMvbd99947333ou33nor7ynQpbR5JC5cuDDWrFkTI0eOjIqKiqioqIg5c+bEzTffHBUVFaVnEN//jOCaNWtK99XV1UVTU1M0NDR86Jn3q66ujr59+7a6IE/77rtv6dlxoP307t07mpubo6mpKe8p0KW0eSSeeOKJsXjx4li0aFHpOvLII2PChAmxaNGi2G+//aKuri5mz55d+pimpqaYM2dOjBo1KiIiRo4cGZWVla3OrFq1KpYsWVI6AwBA+2nzn0ns06dPDB8+vNVtvXv3jv79+5dunzJlSkybNi2GDRsWw4YNi2nTpkWvXr1i/PjxERFRU1MTEydOjMsuuyz69+8ftbW1cfnll8eIESOSF8IAAND22uWFKx/nO9/5TmzatCkuuuiiaGhoiGOOOSYee+yx6NOnT+nMD3/4w6ioqIivfOUrsWnTpjjxxBPj3nvvjfLy8jwmAwB0K7skEp988slWfy4UCjF16tSYOnXqh35Mjx494pZbbolbbrmlfccBAJDwu5sBAEiIRAAAEiIRgE7t1FNPjZ///Od5z4AuRyQC0Kntv//+8dJLL+U9A7ockQgAQEIkQjsoFAqRZVlkWZb3FADYISIR2sHRRx8dL7zwQqxfvz7vKQCwQ0QitIPKyspobm72TCIAnZZIBKDTOuyww2LRokV5z4AuSSQC0GkdffTRsWDBgrxnQJckEgEASIhEAAASIhGATqmsrCyqqqpi8+bNeU+BLkkkAtAp1dTUxNChQ+O5557Lewp0SSIRAICESAQAICESAQBIiERoB1/4whfikUceyXsGAOwwkQjtYODAgfHWW2/lPQMAdphIBAAgIRIB6JR69+4d7733Xt4zoMsSiQB0Spdffnn84Ac/yHsGdFkiEYBOqby8PJqbm/OeAV2WSAQAICESAQBIiEQAABIiEQCAhEiENrbHHnvEG2+8kfcMANgpIhHa2Nlnnx0//elP854BXdpBBx0Uf/nLX6KpqSnvKdBliUQAOp36+vp48803vQUOtCORCABAQiQCAJAQiQAAJEQiAJ1OVVVVbNmyJe8Z0KWJRAA6lbKysjj11FPj5z//ed5ToEsTiQB0OhUVFV7ZDO1MJEIbKxQKeU8AgJ0mEqEN1dfXR3V1dbzyyit5T4Eua//994+//OUvec+ALk8kQhuqqKiIQqHg22DQjsaPHx8PPvhg3jOgyxOJAAAkRCIAAAmRCABAQiQC0Gn07t07WlpaYuPGjXlPgS5PJALQadTX10dzc3OsWbMm7ynQ5YlEAAASIhGATmPIkCHxxhtv5D0DugWRCECncfbZZ8c//dM/5T0DugWRCG3okEMOiSVLluQ9AwB2mkiENnTaaafFrFmz8p4BADtNJAIAkBCJAAAkRCIAnUJlZWVs2bIl7xnQbYhEADqFL3/5y/F//+//jSzL8p4C3YJIBKBTqKysjObm5rxnQLchEgEASIhEAAASIhEAgIRIBAAgIRIB6PB69eoVBx54YDz77LN5T4FuQyQC0OGVl5dHr169YsOGDXlPgW5DJAIAkBCJAAAkRCIAAAmRCABAQiQCAJAQiQAAJEQiAAAJkQgAQEIkAgCQEIkAdHjV1dXR2NiY9wzoVkQiAB3eFVdcEddff33eM6BbEYkAdHjV1dWxefPmvGdAtyISAQBIiEQAABIiEQCAhEgEACAhEgEASIhEAAASIhEAgIRIBKBDq6ysjObm5siyLO8p0K2IRAA6tGOOOSaWLl0aGzZsyHsKdCsiEYAOraysLFpaWvKeAd2OSAQAICESAQBIiEQAABIiEQCAhEgEACAhEgEASIhEAAASIhEAgIRIBAAgIRIBAEiIRAAAEiIRAICESAQAICESAQBIiEQAABIiEQCAhEgEACAhEgHo0Gpra+Pdd9/NewZ0OyIRgA6rUCjEKaecEg8//HDeU6DbEYkAACREIgAACZEIAEBCJAIAkBCJAAAkRCIAAAmRCABAQiQCAJAQiQAAJEQiAAAJkQgAQEIkAgCQEIkAACTaJRJff/31OOuss6J///7Rq1evOOyww2LhwoWl+7Msi6lTp0Z9fX307NkzTjjhhHj++edbfY7Gxsa45JJLYsCAAdG7d+8YN25crFy5sj3mAgDwPm0eiQ0NDfGpT30qKisr49/+7d9i6dKlccMNN8Tuu+9eOnPdddfFjTfeGLfeemssWLAg6urq4uSTT47169eXzkyZMiUeeuihmDlzZsydOzc2bNgQY8eOja1bt7b1ZAAA3i9rY1deeWU2evToD72/paUlq6ury2bMmFG6bfPmzVlNTU12++23Z1mWZWvXrs0qKyuzmTNnls68/vrrWVlZWfboo49+4OfdvHlzViwWS9eKFSuyiHC5dul1xx13ZOXl5bnvcLm6ylUoFLK77ror9x0uV1e8isXiRzZdmz+T+PDDD8eRRx4ZX/7yl2PQoEFx+OGHx1133VW6f9myZbF69eoYM2ZM6bbq6uo4/vjjY968eRERsXDhwtiyZUurM/X19TF8+PDSmfebPn161NTUlK699tqrrb80AIBuo80j8ZVXXonbbrsthg0bFv/v//2/uPDCC+Nb3/pW/O///b8jImL16tURETF48OBWHzd48ODSfatXr46qqqro16/fh555v6uvvjqKxWLpWrFiRVt/aQAA3UZFW3/ClpaWOPLII2PatGkREXH44YfH888/H7fddlucc845pXOFQqHVx2VZltz2fh91prq6Oqqrq3dyPQAAEe3wTOKQIUPi4IMPbnXbQQcdFMuXL4+IiLq6uoiI5BnBNWvWlJ5drKuri6ampmhoaPjQMwAAtJ82j8RPfepT8ec//7nVbS+++GLss88+ERExdOjQqKuri9mzZ5fub2pqijlz5sSoUaMiImLkyJFRWVnZ6syqVatiyZIlpTMAALSjbX/d8raZP39+VlFRkV177bXZSy+9lP30pz/NevXqld1///2lMzNmzMhqamqyWbNmZYsXL87OPPPMbMiQIdm6detKZy688MJszz33zB5//PHs2WefzT7zmc9khx56aNbc3LxNO4rFYu6vGnJ1v8urm12utr28utnlar/r417d3OaRmGVZ9sgjj2TDhw/PqqurswMPPDC78847W93f0tKSXXPNNVldXV1WXV2dHXfccdnixYtbndm0aVM2adKkrLa2NuvZs2c2duzYbPny5du8QSS68rhEosvVtpdIdLna7/q4SCxkWZZFF7Ru3bqoqanJewbdzB133BEXXXSRN32HNlIoFOLOO++M888/P+8p0OUUi8Xo27fvh97vdzcDAJAQiQAAJEQiAAAJkQgAQEIkAgCQEIkAACREIgAACZEIAEBCJAIAkBCJAAAkRCIAAAmRCABAQiQCAJAQiQAAJEQiAAAJkQgAQEIkAgCQEIkAACREIgAACZEIAEBCJAIAkBCJAAAkRCIAAAmRCABAQiQCAJAQiQAAJEQiAAAJkQgAQEIkAgCQEIkAACREIgAACZEIAEBCJAIAkBCJAAAkRCIAAAmRCABAQiQCAJAQiQAAJEQiAAAJkQgAQEIkAgCQEIkAACREIgAACZEIAEBCJAIAkBCJAAAkRCIAAAmRCABAQiQCAJAQiQAAJEQiAAAJkQgAQEIkAgCQEIkAACREIgAACZEIAEBCJAIAkBCJ0Ia2bNkSlZWVec8AgJ0mEqEN3XzzzfHtb3877xkAsNNEIrShzZs3R48ePfKeAQA7TSQCAJAQiQAAJEQiAAAJkQgAQEIkAgCQEInQhtauXRvNzc0xYMCAvKcAwE4RidCG1q1bF1u2bIna2tq8pwDAThGJAAAkRCIAAAmRCABAQiQCAJAQidDGXnzxxfjEJz6R9wwA2CkiEdrYrFmz4u///u/zngEAO0UkAgCQEIkAdFhf//rX45577sl7BnRLIhGADmvgwIHx9ttv5z0DuiWRCABAQiQCAJAQiQAAJEQiAAAJkQgAQEIkQjt4+eWXY9iwYXnPAIAdJhKhHTz11FPx6U9/Ou8ZALDDRCIAAAmRCABAQiQCAJAQiQAAJEQiAAAJkQgAQEIkAgCQEIkAACREIgAdUt++faO8vDwaGhryngLdkkgEoEPq169flJeXx9tvv533FOiWRCIAAAmRCABAQiQCAJAQiQAAJEQitINBgwbFm2++mfcMANhhIhHawec///n413/917xnAMAOE4kAACREIgAACZEIAEBCJALQIQ0dOjReeeWVvGdAtyUSAeiQxo8fH/fff3/eM6DbEokAACREIgAACZEIAEBCJAIAkBCJ0MZ69+4dGzduzHsGAOwUkQht7KKLLorbb7897xkAsFNEIrSx8vLy2Lp1a94zAGCniEQAABIiEQCARJtHYnNzc3zve9+LoUOHRs+ePWO//faL73//+9HS0lI6k2VZTJ06Nerr66Nnz55xwgknxPPPP9/q8zQ2NsYll1wSAwYMiN69e8e4ceNi5cqVbT0XgA7o+OOPj9/+9ret/tsB7FptHon/83/+z7j99tvj1ltvjT/96U9x3XXXxfXXXx+33HJL6cx1110XN954Y9x6662xYMGCqKuri5NPPjnWr19fOjNlypR46KGHYubMmTF37tzYsGFDjB071s96AXQDQ4YMiVWrVuU9A7q3rI2dcsop2Xnnndfqti9+8YvZWWedlWVZlrW0tGR1dXXZjBkzSvdv3rw5q6mpyW6//fYsy7Js7dq1WWVlZTZz5szSmddffz0rKyvLHn300Q/8/928eXNWLBZL14oVK7KIcLl26VVdXZ1997vfzfbaa6/ct7hcnfk644wzspNOOin3HS5XV76KxeJHNl2bP5M4evTo+NWvfhUvvvhiREQ899xzMXfu3PjCF74QERHLli2L1atXx5gxY0ofU11dHccff3zMmzcvIiIWLlwYW7ZsaXWmvr4+hg8fXjrzftOnT4+amprStddee7X1lwYfa/DgwVFVVRUrVqzIewoA7JSKtv6EV155ZRSLxTjwwANLbwVy7bXXxplnnhkREatXr46If/+P6X82ePDgeO2110pnqqqqol+/fsmZv378+1199dVx6aWXlv68bt06oQgAsIPaPBIffPDBuP/+++OBBx6IQw45JBYtWhRTpkyJ+vr6OPfcc0vnCoVCq4/Lsiy57f0+6kx1dXVUV1fv/BcAAEDbR+IVV1wRV111VZxxxhkRETFixIh47bXXYvr06XHuuedGXV1dRPz7s4VDhgwpfdyaNWtKzy7W1dVFU1NTNDQ0tHo2cc2aNTFq1Ki2ngxAB/NxTxoA7a/NfyZx48aNUVbW+tOWl5eX3sZg6NChUVdXF7Nnzy7d39TUFHPmzCkF4MiRI6OysrLVmVWrVsWSJUtEIkAX16NHjxg5cmTMnTs37ynQrbX5M4mnnnpqXHvttbH33nvHIYccEn/4wx/ixhtvjPPOOy8i/v1vh1OmTIlp06bFsGHDYtiwYTFt2rTo1atXjB8/PiIiampqYuLEiXHZZZdF//79o7a2Ni6//PIYMWJEnHTSSW09GYAOpFAoRI8ePWLz5s15T4Furc0j8ZZbbol//Md/jIsuuijWrFkT9fX1ccEFF8R/+2//rXTmO9/5TmzatCkuuuiiaGhoiGOOOSYee+yx6NOnT+nMD3/4w6ioqIivfOUrsWnTpjjxxBPj3nvvjfLy8raeDADA+xSyLMvyHtEe1q1bFzU1NXnPoJvZe++9Y+LEiXHNNdfkPQU6rZ49e8b1118fkyZNynsKdGnFYjH69u37off73c0AACREIrSh/fffP1566aW8ZwDAThOJ0Ia++tWvxs9+9rO8ZwDAThOJAHQoxx57bDz99NN5z4BuTyRCG9l9991j7dq10UVfCwa7zCmnnBL/+q//mvcM6PZEIrSRMWPGxK9+9avSG8cDQGcmEgEASIhEAAASIhEAgIRIBAAgIRIB6DDKysq8+As6CJEIQIdx+OGHx7Jly2Lt2rV5T4FuTyQC0GFUVFTE1q1bvd8odAAiEQCAhEgEACAhEgHoMKqqqqKpqSnvGUCIRAA6kPHjx8d9992X9wwgRCIAHUhlZWU0NzfnPQMIkQgAwAcQidAGysrKora2Nt5+++28pwBAmxCJ0AaqqqpixIgR8eyzz+Y9BQDahEgEoEM4/PDDY9GiRXnPAP6DSASgQzjxxBPjiSeeyHsG8B9EIgAACZEIAEBCJAIAkBCJAAAkRCIAAAmRCEDuampqolevXvHGG2/kPQX4DyIRgNz17t07qquro6GhIe8pwH8QiQAAJEQiAAAJkQgAQEIkQhvo0aNHbN68Oe8Z0GlVV1dHY2Nj3jOA/0QkQhu44oor4gc/+EHeM6DT+va3vx033HBD3jOA/0QkQhuorq6OpqamvGdAp1VVVeWZROhgRCIAAAmRCABAQiTCTvqbv/mbePPNN2P9+vV5TwGANiMSYSfV1tbGhg0b/EwiAF2KSAQAICESYSeVl5dHS0tL3jOg0xoxYkQsXbrUv0fQwYhE2Enjx4+P++67L+8Z0Gntv//+8Ze//EUkQgcjEmEn9erVKzZu3Jj3DABoUyIRAICESISdcM4558T999+f9wwAaHMiEXbCgAED4u233857BgC0OZEIAEBCJAIAkBCJAOSqUCjkPQH4ACIRgNxUVVXFqFGj4sknn8x7CvA+IhGA3BQKhejVq1e89957eU8B3kckAgCQEIkAACREIgAACZEIAEBCJAIAkBCJAAAkRCIAAAmRCABAQiQCAJAQiQDk5swzz4wHH3ww7xnABxCJAOTmoIMOij/96U95zwA+gEgEACAhEgEASIhEAAASIhEAgIRIBAAgIRIBAEiIRAAAEiIRAICESAQAICESAQBIiEQAABIiEQCAhEgEACAhEgEASIhEAAASIhEAgIRIBAAgIRIBAEiIRAByccABB8SaNWvi3XffzXsK8AFEIgC56NWrVzQ1NUVzc3PeU4APIBIBAEiIRAAAEiIRAICESAQAICESAQBIiEQAABIiEQCAhEgEACAhEgEASIhEAAASIhEAgIRIBAAgIRIBAEiIRAAAEiIRAICESAQAICESAQBIiEQAABIiEQCAhEgEACAhEgEASIhEAAASIhEAgIRIBAAgIRIByMW4cePi5z//ed4zgA8hEgHIxV577RUrVqzIewbwIUQiAAAJkQgAQEIkAgCQEIkAACS2OxJ/85vfxKmnnhr19fVRKBSSV6ZlWRZTp06N+vr66NmzZ5xwwgnx/PPPtzrT2NgYl1xySQwYMCB69+4d48aNi5UrV7Y609DQEGeffXbU1NRETU1NnH322bF27drt/gIBANh+2x2J7733Xhx66KFx6623fuD91113Xdx4441x6623xoIFC6Kuri5OPvnkWL9+fenMlClT4qGHHoqZM2fG3LlzY8OGDTF27NjYunVr6cz48eNj0aJF8eijj8ajjz4aixYtirPPPnsHvkQAALZbthMiInvooYdKf25pacnq6uqyGTNmlG7bvHlzVlNTk91+++1ZlmXZ2rVrs8rKymzmzJmlM6+//npWVlaWPfroo1mWZdnSpUuziMiefvrp0pnf/e53WURkL7zwwjZtKxaLWUS4XO16XXrppdnw4cNz3+Fydcbrxz/+ce4bXK7ufBWLxY9sqTb9mcRly5bF6tWrY8yYMaXbqqur4/jjj4958+ZFRMTChQtjy5Ytrc7U19fH8OHDS2d+97vfRU1NTRxzzDGlM3/7t38bNTU1pTPv19jYGOvWrWt1AQCwY9o0ElevXh0REYMHD251++DBg0v3rV69OqqqqqJfv34feWbQoEHJ5x80aFDpzPtNnz699POLNTU1sddee+301wMA0F21y6ubC4VCqz9nWZbc9n7vP/NB5z/q81x99dVRLBZLl3fxBwDYcW0aiXV1dRERybN9a9asKT27WFdXF01NTdHQ0PCRZ958883k87/11lvJs5R/VV1dHX379m11AQCwY9o0EocOHRp1dXUxe/bs0m1NTU0xZ86cGDVqVEREjBw5MiorK1udWbVqVSxZsqR05thjj41isRjz588vnfn9738fxWKxdAYAgPZTsb0fsGHDhnj55ZdLf162bFksWrQoamtrY++9944pU6bEtGnTYtiwYTFs2LCYNm1a9OrVK8aPHx8RETU1NTFx4sS47LLLon///lFbWxuXX355jBgxIk466aSIiDjooIPic5/7XJx//vlxxx13RETEN77xjRg7dmwccMABbfF1AwDwUbbp/WT+kyeeeOIDX0Z97rnnZln272+Dc80112R1dXVZdXV1dtxxx2WLFy9u9Tk2bdqUTZo0Kautrc169uyZjR07Nlu+fHmrM++88042YcKErE+fPlmfPn2yCRMmZA0NDdu801vguHbF5S1wXK4dv7wFjsuV7/Vxb4FTyLIsiy5o3bp1UVNTk/cMurhLL700HnvssViyZEneU6DT+fGPfxxf//rX854B3VaxWPzI13D43c0AACREIgAACZEIAEBCJAIAkBCJAAAkRCIAAAmRCMAu96UvfSkeeuihvGcAH0EkArDL1dfXxxtvvJH3DOAjiEQAABIiEQCAhEgEACAhEgEASIhEAAASIhEAgIRIBAAgIRIBAEiIRAAAEiIRAICESAQAICESAQBIiEQAABIiEQCAhEgEACAhEgEASIhEAAASIhEAgIRIBAAgIRIBAEiIRAAAEiIRAICESAQAICESAQBIiEQAABIiEQCAhEgEACAhEgHYpXbbbbfYfffdY+XKlXlPAT6CSARgl+rZs2fstttu8dZbb+U9BfgIIhEAgIRIBAAgIRIBAEiIRAAAEiIRAICESAQAICESAQBIiEQAABIiEQCAhEgE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"
class="
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
<li><p><strong>Identifying the Receipt Area:</strong></p>
<ul>
<li>Sorts contours based on their arc length and selects the contour with the largest arc length, assuming it represents the receipt.</li>
</ul>
</li>
</ol>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">to_sort</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">zeros</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">contours</span><span class="p">))</span>
<span class="k">for</span> <span class="n">i</span><span class="p">,</span> <span class="n">contour</span> <span class="ow">in</span> <span class="nb">enumerate</span><span class="p">(</span><span class="n">contours</span><span class="p">):</span>
    <span class="n">to_sort</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="o">=</span> <span class="n">cv2</span><span class="o">.</span><span class="n">arcLength</span><span class="p">(</span><span class="n">contour</span><span class="p">,</span> <span class="kc">False</span><span class="p">)</span>
<span class="n">biggest</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">argsort</span><span class="p">(</span><span class="n">to_sort</span><span class="p">)[</span><span class="o">-</span><span class="mi">1</span><span class="p">]</span>
<span class="n">receipt</span> <span class="o">=</span> <span class="n">contours</span><span class="p">[</span><span class="n">biggest</span><span class="p">]</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
<li><p><strong>Perspective Transformation:</strong></p>
<ul>
<li>Approximates the contour of the receipt to a rectangle and transforms it into a quadrilateral with known dimensions.</li>
<li>Applies perspective transformation to warp the receipt area into a rectangular shape, facilitating OCR.</li>
</ul>
</li>
</ol>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">epsilon</span> <span class="o">=</span> <span class="mf">0.1</span> <span class="o">*</span> <span class="n">cv2</span><span class="o">.</span><span class="n">arcLength</span><span class="p">(</span><span class="n">receipt</span><span class="p">,</span> <span class="kc">True</span><span class="p">)</span>
<span class="n">approx</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">array</span><span class="p">(</span><span class="n">cv2</span><span class="o">.</span><span class="n">approxPolyDP</span><span class="p">(</span><span class="n">receipt</span><span class="p">,</span> <span class="n">epsilon</span><span class="p">,</span> <span class="kc">True</span><span class="p">))</span>

<span class="c1"># Get the minimum bounding rectangle</span>
<span class="n">rect</span> <span class="o">=</span> <span class="n">cv2</span><span class="o">.</span><span class="n">minAreaRect</span><span class="p">(</span><span class="n">receipt</span><span class="p">)</span>

<span class="c1"># Convert the rectangle to box points</span>
<span class="n">approx</span> <span class="o">=</span> <span class="n">cv2</span><span class="o">.</span><span class="n">boxPoints</span><span class="p">(</span><span class="n">rect</span><span class="p">)</span>


<span class="n">height</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">linalg</span><span class="o">.</span><span class="n">norm</span><span class="p">(</span><span class="n">approx</span><span class="p">[</span><span class="mi">0</span><span class="p">]</span> <span class="o">-</span> <span class="n">approx</span><span class="p">[</span><span class="mi">1</span><span class="p">])</span>
<span class="n">width</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">linalg</span><span class="o">.</span><span class="n">norm</span><span class="p">(</span><span class="n">approx</span><span class="p">[</span><span class="mi">1</span><span class="p">]</span> <span class="o">-</span> <span class="n">approx</span><span class="p">[</span><span class="mi">2</span><span class="p">])</span>


<span class="n">dst_points</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">array</span><span class="p">([[</span><span class="mi">0</span><span class="p">,</span> <span class="n">height</span><span class="p">],</span> <span class="p">[</span><span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">],</span> <span class="p">[</span><span class="n">width</span><span class="p">,</span> <span class="mi">0</span><span class="p">],</span> <span class="p">[</span><span class="n">width</span><span class="p">,</span> <span class="n">height</span><span class="p">]],</span> <span class="n">dtype</span><span class="o">=</span><span class="n">np</span><span class="o">.</span><span class="n">float32</span><span class="p">)</span>

<span class="c1"># Compute perspective transformation matrix</span>
<span class="n">M</span> <span class="o">=</span> <span class="n">cv2</span><span class="o">.</span><span class="n">getPerspectiveTransform</span><span class="p">(</span><span class="n">approx</span><span class="o">.</span><span class="n">astype</span><span class="p">(</span><span class="n">np</span><span class="o">.</span><span class="n">float32</span><span class="p">),</span> <span class="n">dst_points</span><span class="p">)</span>

<span class="c1"># Warp the image</span>
<span class="n">warped_image</span> <span class="o">=</span> <span class="n">cv2</span><span class="o">.</span><span class="n">warpPerspective</span><span class="p">(</span><span class="n">I</span><span class="p">,</span> <span class="n">M</span><span class="p">,</span> <span class="p">(</span><span class="nb">int</span><span class="p">(</span><span class="n">width</span><span class="p">),</span> <span class="nb">int</span><span class="p">(</span><span class="n">height</span><span class="p">)))</span>

<span class="c1"># Display the warped image</span>
<span class="n">plot_rgb</span><span class="p">(</span><span class="n">warped_image</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[&nbsp;]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>&lt;matplotlib.image.AxesImage at 0x20dc62eb5e0&gt;</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAASoAAAMyCAYAAADaIIzwAAAAOXRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjcuMCwgaHR0cHM6Ly9tYXRwbG90bGliLm9yZy88F64QAAAACXBIWXMAAA9hAAAPYQGoP6dpAAEAAElEQVR4nOz9V4xkWXYeCn/hvXcZEeltmczyVd1d3dV+elxzOEOQHIEgKYiSQIIUAWKoBxF8EQWChPQg6EUSIF2BEkYYDskRqZnW2B7fprrLZ1Wl9zYiIyLDe/s/5F2rd5w6JyKyeng1f7EWUKiMY/bZZ5+9v738UrVarRae0lN6Sk/p55jU/7c78JSe0lN6St3oKVA9paf0lH7u6SlQPaWn9JR+7ukpUD2lp/SUfu7pKVA9paf0lH7u6SlQPaWn9JR+7ukpUD2lp/SUfu7pKVA9paf0lH7u6SlQPaWn9JR+7ukpUD2lp/SUfu7p5xqo/tN/+k8YGRmB0WjExYsX8c477/zf7tJTekpP6f8C/dwC1V/91V/hD/7gD/DHf/zHuHv3Lq5du4ZPf/rT2N7e/r/dtaf0lJ7S/8ek+nkNSn7mmWdw4cIF/Of//J/52MmTJ/H5z38ef/7nf971/mazif39fdhsNqhUqr/Prj6lp/SUHpNarRZyuRxCoRDUamW+Sfv/YZ96pmq1itu3b+Nf/at/1Xb8jTfewPvvvy97T6VSQaVS4d97e3s4derU32s/n9JTeko/G9rZ2UF/f7/i+Z9LoEokEmg0GggEAm3HA4EAotGo7D1//ud/jj/5kz+RPafX62EymWAwGKDT6VCv11GtVuH3+2EymZBIJDAwMACXywWj0YhGo4FoNIparYZz584hmUwin8/DbrfD5/PhmWeewdDQEPR6PXQ6HfR6PVQqFVQqFYhBpd/0d6vVgkqlglqtluXwpMeUuECxfaVrxWtarRZarRYymQw2Nzf5X61WQywWQ7FYhEajQbPZ5PEJBoMYGRnB1NQUPB4PLBYLNBoNarUarFYrWq0WNBoNgCPOld5N7Id0HOgc9Ue8R3pvp/ejdqkN8bxarW47Lh0DpfHrNN7SbyhSs9l8ZNyl/erUl16o07U0bsSJSN9R7L94XO5d6LzcOCi9g0qlwvXr1/HVr34VNpsNQ0NDWF5eRrlcBgCcPn0aer0eKysr2NzcxKlTpzA6Oor33nsPOp0OExMTcLlc+NM//VPYbLaO4/BzCVREcgtQaUL90R/9Eb70pS/x72w2i4GBAUxPT6O/vx/j4+MYHh7GxsYGUqkU6vU6wuEw9Ho95ufn0Wq1UKlUkEql4HQ6cfnyZajVang8HvT39yOTyaBYLKKvrw/Dw8MYHh7mPnXqv7hAaVJ1YnE7vXu3Z9B19I+es7Ozg5/85Cd45513kM/nUa1WodPpeGHT/blcDo1GA/v7+7h79y7C4TB8Ph/8fj9PMgItapuASgpW4qKRgrN0MVNbIihI313umBwYiuMk/Vs6hr1sGErHpO+oBKByixw4GrdeNhul3+J9UqCS6/vH0fBIwV383lqtFqlUClqtFmazGZVKBTqdDoFAAE6nE36/H7VaDdVqFRaLBXq9HiMjIwCATCYDi8XS1rYS/VwCldfrhUajeYR7isVij3BZRAaDAQaD4ZHjMzMzKJfLyOVyMJlMSKVSSCaTcLvdMBgMKJfLUKlU8Hq98Hq9aDabWFtbw8LCAgwGA0KhEACg0WhAr9fDarXCaDQCeHSyAfK7lbgAj6Mvky5EpckmtzhbrRaq1Sq2trbwve99D7Ozs8hmswAAnU4HjUYDlUqFRqOBRqPBE77VavH5ZDKJZDKJlZUVzM3NYXBwEK+88gouX77M3ES3HZh+i8Ap3tMLaFMb0oUtHutlbMR75UgJKJXuU3pP6Xm5fvf63p36IcdBSUncQJS4KLFfnUg8r1ar0Ww2YTKZMDQ0xIAzMjKCQqGAubk55PP5ts1frVZDo9FAq9UimUyiXq+jXq/39M4/l1Y/vV6Pixcv4u233247/vbbb+Pq1avHauvBgwcwm80YHh6GTqdDX18fyuUytra2UK/XoVarkUwmUSqVGLRoJ/B4PKhUKnzcZDIhmUyiWq0CQNvCUwIhUSx5HJCSttWpjVarxRxOo9HA7Ows/ut//a+4fv06crkcc3PU70ajAeAjrog4Ja1Wy3/ThIzH47h79y6+/e1vI51OK4pOvXAtSuJXt4Uk/afEqYnj0Ov4PS5I9cKpdOKGlEg6p3oRj5W41uOKm3JtSI/TRlWv15HNZrG7u4tGo4FYLIZIJIJQKIShoSEW6VZWVrC9vQ2VSoVsNotMJoNAIAC9Xt9TX34uOSoA+NKXvoTf+I3fwKVLl/Dcc8/hv/yX/4Lt7W38zu/8zrHaMZvNWFxcRC6XQ6vVwt7eHkKhEIxGI7RaLSqVCrxeL2KxGGKxGN/n9/uh0+lQLpcRjUZZdxMMBqHX6zvunHIsv3QiSRd2LyDWCQSkE3N7extvvfUW9vb20Gw22zgommiNRgM6na5tYWs0mrbzUpLbAeVELrmFTRyoEqA/zoIW71WpVLyAuulbOolz3bjE44hlnfrc6ZySnqnTsW5Ar9SGEiB12xRpsyiXy8yZazQa6HQ6NJtNJBIJOBwOGAwGDA0NwWq1olwuIxAIwGAwIJFIyEpBcvRzC1Rf/OIXcXh4iH/zb/4NIpEIpqen8a1vfQtDQ0PHasfr9UKv1yMUCiEcDiMajWJjYwPZbBYulwvFYhGVSgWTk5MIhUKwWCyIx+O4desWKpUK+vv7USqVkEwmYbVa4Xa7H9E7iSQuGrndsNOueBySgpR4vF6vY2trCwcHB1CpVNDpdLyIRbASF7aoiKa/SSTUarXMvTgcDp6IUrGilwUrp8/qhSOVe09xQXcTjbuNczcuT0nckirU5Uiub3JApKTPkmtPqf8/C+rE6Uq/B0kr1WoVrVYL/f39SKVSWFlZQSqVQjAYRCaTgV6vR61WA3A01wqFAlqtFrTa3iDo5xaoAOB3f/d38bu/+7sfq439/X2Ew2EYDAYUCgUYjUbYbDZejGazGRqNBru7u9jc3ITD4cD4+DjOnz+PYrEIlUoFv9+PaDSKZDIJs9mMYrEI4FE9CZFU3BMXoRzn0StY9cJZqFQqZDIZ3L9/H7VaDTqdru25tAvSswk4LBYLW/QajQbK5TIqlQpzVVqtFiqVCuFwGCaTCc1mE81mU1GkFduXHlciUW/T68KTgpX4bLGdjyP6iM+Qa08qnj4Odeqf3DvKcV0iaD4Ohy69T4lDo+NqtRq1Wg3RaBSHh4fwer1IJpPY2tpCIBDA4OAggsEg8vk8Hjx4gGw2i+HhYZTLZSQSCZw7dw4ul6trP4Gfc6D6WdDExARyuRwODw8RCoWQy+VgNpvh8/lgMBja0L5cLqNer0Oj0SCXy8FisaCvr4/N+H6/nzkKoH1BKIl3StzX4y6cXibgwcEB1tfXUalUHgFLkWUnkfCZZ57BCy+8gJGREZ5EOzs7WFhYwPr6OvL5PFqtFvR6Pfx+PzQaDer1Ootz5KpAfZRbuOLklnJjdI0IfEoLT47rkI5rL5yWkhgtxxl2EvuU3lPufrEvtFlIny9ttxf9knidElh2Uhs8DrhSezQXisUifz+j0QiTyYRSqQQAsFgsGBoaQrlcRqvVgt1ux9TUFBKJBPL5fE/Pe+KBamlpCT6fD1arFVqtFjqdDktLS6hUKnjttddQrVaxs7ODkydP4sKFCzAajdje3sbW1hYPLCn8SM8jNeuLC66bXE/USUcitknHetlx6Z5arcbcoGiZFEU7jUYDjUaD06dP41d+5VcQDAbZnyoYDOL06dN44YUXsLS0hHfeeQf379+H2WxGX19fW1uFQoFF43K5DI1GA71eD6PRCJfLBZPJBK1WC61Wy3qvTuPUy6IUr+1VPDqu6CXXLznOWXqvHCfXqxrgOCQ3N5Q2RfEdPu5zxftJLdDX1weHwwGj0QiLxQKTyYStrS1sbW0hFAohFouhXq+jVqvx/IvH4wxovdATD1TVahVmsxlWqxWNRgMOhwMDAwPI5/Oo1+uwWq3w+/3I5/O4e/cu6vU6dDodzpw5A6PRiHq9DofDgVqthnQ6DZfLxQplEQgedxJ8HL1KN5KKUiSukXjncrnw0ksvcfhCrVZrAz2Xy4Vnn30W/f39zDUFAgEUi0Wk02msrq5ibm4OsViMgYqcRnU6Hfx+P1wuF86ePYuJiQlYrdae3k1OdOtGUu6qk+5I5D7EY52eJx6Xull00uF0es9ev6+0nU56NOl79MqVPQ7R/E+lUohEIrDZbNDpdFhbW0M4HMbMzAyCwSCazSZu3bqFra0tDA8Pw2g0olqtYmho6P//lek/Kzpz5gzK5TL29/fh8XiQTqeh0WgQDoeh0+lQKBRgNptZ5CAxMBaLwWAwwO12I5PJQKPRYGhoCMFgEEaj8ZHJLif2KZH0PjnqtHtTG3J/0zsQgKrVatTr9bYFTG0ZjUb4fD6oVCp21Wg0Gm1uCQAQDAbxxS9+EdFoFJVKBe+//z6uX7+OVCrFgE/+MaVSCY1GA/V6HRsbG1CpVPjwww/R39+PF198EZcvX+bJqbTQRTGV+ix1apTTs9GxTp7anb6PksjYTZzqtkn9rDiYbufluMZeuPheni8ncgNHukvioOl/p9OJTCaDZDIJvV6PbDYLr9cLh8PBhpnh4WFEo9GejBHAPwCgWl9fx/j4OMLhMCwWC1wuF4t2Fy9eRKvVQjqdxvT0NDweD5rNJrsq0KQnbqNSqbQ5OooLiCaz+Ps4okSn63udqEQulwsWi4UdPMU+ixbAfD6PWCyG8fHxNoCiCU59bDabCAQC0Ol0eP/99/G9730P8XicxTzitkTdl8FgYCtPPp/H/Pw8tre3sbGxgQsXLmBmZkYW2OUWF3GD0uukY0DXiDow4iLlxkrub7lvogRYx+WWugGZEqDKcWZKomY3TvRnAVw0V4AjdxXS5ep0Ot784vE40uk0SqUS+yImk0lYLBYEAgHs7u7CaDTC4/H09MwnHqhI2Vev11GpVFAsFhEKhdBoNGAwGNBqteBwOLC2tobr16+zX9Xo6CjMZjOq1SovxFQqhYGBgTaRSk4/Jf4vt/DkuCXp30o7eC/6Da/Xi8nJSdy8eRONRoMV3iKn1Gq1UC6X8c477+DcuXMwm81tC1rKMbZaLayuruLtt99GMplknRNdQxyZ+BytVtsGgOVyGW+//Tbef/99/Nqv/Rqee+45mM1m1lvR//TNiKTOmwS49C50L31vpfvkvpnS+x6Hut2jxHmJHGEnDq8b6Ikg/vfB3Um5d3HsiIteWFhAuVxGMBjE4uIi3G43Tp48yZxUMplkgxbwkb43nU731IcnHqiGhoZQqVRwcHCAwcFBJBIJAOBFlcvlUCwW4fF4mKOKx+O4efMmfD4f3njjDSSTSdRqNUxOTsLtdrPVjxYKme6JpCKJEkknqpKIIUdKOykAmEwmnDhxAvfu3ePz5DtFz6IFPTc3h7feeguf/OQn4XA4HgFDAoJCoYAPPvgAmUyG7yewIqdRmnzEWdHf0njAVCqFr3zlKygUCnj99ddZoarValGv17mvuVwO1WoVh4eHSKfTKBaLrJwPh8Ow2WywWq0MhNIxV1q0vWwU4v2iKNkLmInfVHRAlbYl97+S/qsXsV+Oy5Qelzv2OPpVukej0cBmsyEcDqOvrw9OpxNjY2OIRCK4c+cOyuUyK9hPnz4Nh8MBk8mE/v5+7O/vs6tPN3rigerWrVs4d+4cQqEQdDodPB4PFhcXkUql4PP5oNVqkclk0N/fD4fDAZVKxQuAYgE9Hg9yuRyy2SwvQhILlXZnOZJOElHP0sskkQNDpevOnz+P9957DxsbG233UL8JqOr1On7wgx9ga2sLv/zLv4y+vr62oONW6yhmcH5+HgsLC49wMCqVipXw1WoVBoMBJpOJOShRdKb31Gq1SKfT+PrXv45arYZPfepTzFkVCgVsbW1hZWUFt2/f5nixYrGIer0Og8EAq9UKq9UKh8OBYDCIM2fOYHR0FFarFZVKBaVSCWq1mrkuKacnipNS7lgk6YYj/i2Oj3SzkYKTnN5L+mw6L1pFRb2bHDfdTUEu5ezF95IjpTklvpv4Ls1msy30LJVKweFwQK1Ww263Q6fTwe12w2g0IpVKYWNjAw6HA16vF9vb29BqtRgYGOj4DkRPPFAFg0FUq1XkcjkUCgUUCgUMDw9jdHSUlc6BQAA7Ozu4f/8+KpUKfD4fJicnodPpUK1WWddSq9VgMBjYm1ZuwhIp7W5SkoqMx51Ecour0WggGAzilVdeQTweRz6fl812QOJZrVbD7Ows0uk0xsfHEQwGOUtCsVjEwcEBtre3USgU2vx/RAW8SqXCwMAAzp49i/7+fuh0Oqyvr+PmzZscG9hqtVixr9FokM/n8b3vfQ/9/f24fPkyDg4O8IMf/AD37t3DwcEBisViG7ioVCpW1sfjcbRaLdy7dw8ffPABJicn8dprryGZTOL+/fsAAIfDAbfbDbPZzKZwSuVjs9k4ppHChqTfVDrOos5S7huL4ypyVHLfVWyDrhdF6U7zQaozk97XSdcl/VvuHbpxnCJwms1m6HQ67O3twWQywel0Ynt7G0ajEYFAAGazGQ6HA5lMhq8BwM7Fh4eHj/RVjp54oCKuqdVqwWAwoF6vIx6Po9FowG63I5/Po1gsYnh4GOfPn4dKpcLi4iI+/PBD2O12fOITn0AymYRKpUIoFILL5Wpz+xc5LKniVSQlhazcNSJ1Ay+l65rNJl544QUcHBzgxz/+MbPYpLOivpLoqlarEY1GcXBwwIBM3JS4+5OFr16vt3mnT0xM4Atf+ALOnDkDvV4PtVqNZ599FuFwGN/4xjfaMmGIHGkmk8GPf/xj+Hw+3Lx5Ez/84Q8ZWElRT+Ar3qvRaFj/FYvFkE6ncXBwwJkyKP5MdJcgy1S9Xsfg4CBMJhPsdjs8Hg+0Wi1zg5SbjMZY+kxyZKR0OTQHSCUgWlal30UOJGhMxc1EdH6V49qkc6QblyXXh17ERjkS76/X6zCZTJicnORgfoPBgMPDQ9y/fx8HBweYnJxELpfDxMQEDAYD1Go1fD4fb0a90BMPVEtLS7h8+TLnnhocHEQul0M+n+cgShpwmuA2m42TfuXzefh8PvYdEk39cjtrJ2BRok5iXK/6A7kd0mg04hd+4RdQrVbx3nvvoVQqMWhLrZeimEQLhbzPLRYL5xQSQYP6pNPp8NJLL+Hs2bNt0fBGoxEvvvgiisUivva1r7WJgqLovL+/jwcPHuDmzZvsNCouPHIUpVQ+rVarrS2dTodwOMyZMEjPpdVq2zhi8oImJW4+n4dKdeSmQeFGg4OD+NVf/VW4XC4G6ng8jkgkglqthlqthkgkgmw2i2q1CrvdDrvdDpPJhGAwCI/Hg2AwyPo7cYwJPKvVKhKJBJLJJIu7JpOJxVkxq4A4FjQeShwdkTh2nTjxTvO0EycnPqNUKrF4nk6n4XQ6eY0MDQ3B5/MxR7W6uop6vQ6/3494PI5yuYzBwUHFPoj0xAPV2NgYotEoTCYTWq0WdnZ2OPmdyWRizioajSKfzyOVSvFkoywJFEApsv1ijJt0MsjteN0mldyxThNN6Xpxt2s0GnA6nfj85z+PZrOJ27dvI5vNtu3cophDljYyDtAimZmZQTqdxvLycpt+jRaiwWCAy+WCXq9/xPPcbDbj0qVL+OlPf4qtra02yyJ5wieTSbzzzjvMdYlB0QSaXq8Xn/70pxEOhzl2bGlpCdlsFqFQCF/4whewvr6OWCz2iBsJvReBF3GE9JxSqcQ6NpvNhr6+PmSzWaytrWF9fR1LS0vY2dlBoVB4JH8XcUIajQZmsxkzMzP4zd/8TR5Dan9jYwN37txBIpHgTS+bzaLZbKJarbZZSgcGBjA2NoaTJ09icnKS85+J4y4333rhpno518uco2sIqBcXF9FsNmG325HJZFCv1+F0Onl+EBDTvKL0Lzs7Ox2fQ/TEA1WpVILD4WBZWavVYnl5GbVaDRcuXEAikUA8HsfU1BT6+vrQaDR4grpcLtZxAYDNZmPWVcoVEEl3neNYUrqRVM+gdF48R2D1y7/8yxgYGMCPf/xjnhwEUsR5kHhM76FSHXmnX7lyBWtra1hcXGxLAyM+k8BcKtrU63V2BCRgFBXyBBAHBwdt3Bop+6nNer3Okfo2mw0nT57E3Nwc7t69i5GREYyMjGBtbQ0mkwnVarXN1UH8LtR3Uaykd9HpdPD5fEilUnj33XcxOzvLXA8RicnUBnAE+BS5UK/X+V1LpRJWV1fxwQcfYG1tDdFotK1fBMJ0jNJkLy8vY2lpCR988AGef/55nDt3DqOjo9xfaZzgceaN3Dnp+EjPdaJGo4FarYb+/n6YTCYEAgG4XC4kk0msrq4COFK/5HI5+P1+fmeLxdKW260bPfFAtbu7i3A4jGAwCIPBgGAwiGKxiEKhAOAIfJLJJIrFInZ2dpDP55kLIGuVz+dDNpvF4eFhW5hJpwnTTcaX/pbqC6QWHulxpfsA8OQnjlCtVsPlcuETn/gERkZG8Pbbb+P+/fsoFAqsrxKV1uLCDAaDOHXqFAwGA77//e+jWq0yN0FAR/5YQ0NDGB4ebgPMSqWC+fl5RCIR5j5E/Yj0uVIukoAmm83iq1/9Km7cuIHBwUE4HA5MTU3hxIkTsNlsMJvNuHbtGk6cOIF4PI65uTnMzc21+WjR81QqFeciE5XdOp0O+/v7+NrXvoaHDx8yJyZVoFOfRKAjkZo4he3tbXzzm9/EysoKDg8P0Wq1OOaRxELipER9lqhYj8fjeOutt3Dr1i38+q//Oqanpx+ZB70AlpzC/LjqCSlRfyuVCjKZDMd70vul02kWhV0uF2KxGGZnZ5FKpRAOh3F4eIhEIoHx8fGenvfEA9Xk5CTi8TjW1tYwNDSEvb09OBwONp8WCgVYLBZUq1Xk83mUy2UUCgUu5mCz2ZDNZmE0Gtt8dog6iW4fh5vqNpGUAEulOkrz8sEHH8DtdmNgYIAXsk6nw/j4ONxuN06dOoX79+9jZ2cHyWSSuQpa0CQmhcNhWK1WDA4OYmBgAGtra6xUFhW+Kysr+Nu//Vt87nOfQyAQQKvVQj6fx8bGBn7yk5+gUCgwNwIcWVDpmXa7HWfPnsXDhw8Ri8Ue8Yki0Sqfz+Phw4dYW1vj4h/PP/88XnzxRc7FTRPf7/djbm6OwUYcH1LCX7hwAcARCNZqNRwcHGB1dRWVSoU5HCLy8SKRUfTwJ+DRarUIBALY2NjA//k//wc3btzgvtP7ikYXUYRUq9VsoBC5zmbzqOzb/v4+pqene4586EZS9YJ0Lonj1YnL8ng8GBwcxPvvv498Po9QKMSB6oFAABaLBTqdDk6nk/Ooa7Va2O12DA4OPnX4JEqn05wQj3Iuzc/Po1Ao4PLly6hWq8hmszh79iysVivq9TpisRgSiQTK5TL0ej1PRGLZRetLL1Y5UQQ8Lngp6cGk58W/K5UK3nvvPRwcHCAYDMLr9WJ4eBhjY2O8y73yyiu4dOkSEokENjY2sLi4iPn5eaTTaQYUq9WKgYEB6PV6eDwePPPMM9jd3UWlUmEOgRZWvV7HvXv3cHh4iIGBATQaDaRSKezt7XEojzgOtBjr9Tq8Xi8+97nPYWZmBt/61rcYiKhtenfREFCpVLC+vo54PI5oNIrf+I3f4O+nVquxu7vL4Cgq/wkggsEgfv3Xfx0ejwf1eh3RaBT/8T/+R+zv78tyXwRwBoMB09PTCIVCsFqtiEQiWFhYwOHhIWfn+O53v4v5+Xl2hKV5Q+9cqVQ4jtRoNKJSqXCqaOAjq6HIbZIbhcgBdrLaSeeO0jXSOaR0Xq4NEvkLhQIGBwehVqsxMDAAjUbD8+rg4ACf+tSnEIvF4PV6GZyNRiMymQxLNt3oiQcqKgdlMpnYYXB4eBiNRoMTwNlsNuzv7yMejyOZTGJgYAADAwM88UlHkkql2gCHdjz6fRxS0mvROaXJ1ek5tCiMRiP8fj+SyST29/exvr6O2dlZOBwOhEIhTE9PY3JyEj6fDwMDAxgeHsa1a9dweHiIvb09pFIpHB4ewul04sSJE8xdvfjii4hEIvjpT3+KarXappAmfdTm5iaDPIEKAQ4tNOAjRbrdbse1a9dQrVbh8Xjwz//5P8eNGzcwOzuLvb29NkMGkQg8pVIJ77//Pq5cuYILFy5ArVYjl8vh3r17bQtaBNZWq4WZmRkEAgHWfaVSKaRSKVSrVXZhoOeS1bC/vx+f/vSn8eyzz7KVtFqtYmVlBTdv3sTKygqWl5dx//595o5ITBR1mYFAAM888wxOnjwJo9GIQqGAd955B7du3Wp7N+o/AaBIcsG83URCOS5KnM/iMWl8pPR6ela5XEY+n0cmk2FDjclkQiwWg8fjwfj4OBdNmZ+fx9bWFjuFZjIZDqnpRk88UFFVjL29PdhsNuzs7LR5ZSeTSXZk1Ol0sFgsSKfT2Nvbw9TUFE6dOsWZP4eGhtrEEqJeQaqX63qxtkhJqvfRaDQ4efIkJydbXV3F4eEhMpkMotEoVlZW4PF4EAgEcOLECUxMTCAUCiEUCiEQCLATqNQiSBbEdDrNOhxRGU0kclzkKkCAJfoYGQwGXLhwAVNTU/jOd76Dvb09fOELX8BnP/tZvPrqq4hEInjw4AHW19exsLCAWq3GYie9Z6t1FFQ+Pz+PS5cuodFo4MGDB9jb2+MajSJg0DiNjo62LbZ33nkHmUwGwJFYSlwl3T80NIRf+7VfawumbrVaMJlMOH/+PKampvC3f/u3eOedd1AsFvk5orin1WoxNTWFz372s5icnGQrmEqlwuDgIGq1GgOs2FdRtyce73V+yOlElQK1xWPi8+TaUKlUbCXd399HqVRigCbraDweh9PpRLPZhNvths1m44o1fX192Nvbk30PKT3xQLWwsIDBwUGYzWZotVpYrVY8ePCALRWUkmRwcJBTFKdSKWxtbbE8bbPZMDExAZ/P1+Zr1Muk6Ha827W96CGInQaOQCudTuOb3/wm60zC4TDGx8eRyWSQyWQ4di4ej2N+fh5utxuhUAjDw8MYGBjgsaCwFgKsRqMBv9+P3/qt38Jf/dVf4b333gMATo0jcpli1gIaL1FJbzab8cwzz+DFF1/EzZs38dOf/hS1Wg1f/vKXceLECQwPD+P06dN48803sbm5iVQqhc3NzTalMwEQOfKSPorEU6VvNDw8jHA4zNxyMpnE4uJiGxdD99LCI8U9vR8tXhp7siqTf57YFs0xr9eLN998E2fPnuV26LsFg0E888wzmJ+fZ0uYqMsS54IcFy/leLrNpeMae+TaaLVavPm5XC4EAgEEg0GYTCYYjUZsbW1hf38fbrebgZr88Ww2GyKRSM/lsp54oDIajRgcHITH40GpVMLQ0BDrocj3xWq1wmQy8SBWq1U4nU7Y7XZoNBrODkpe2jRRRWUykRybfBzqpk+QI9HKRvcRt0gOkF6vF/39/VyMNZlMIpFIcEqbZDKJubk5qNVqVkqPjIywNz65LTQaDXi9XvyTf/JP0N/fjzt37rCoSFwY9YF2VXofMt17PB68+uqruHTpEtbX1/GDH/yAvbP39vYQjUbZe5kSFUaj0TbltSjWGQwG+P1+tFotZLNZLC4utnnUi5whWQfJOqdSqVAsFhlopSIm6ahEx0vxHelYo9HgCt9S3ST1wWazIRQKtYEdiZdSJ1rx+4tlzT6OgUYqCovPk54Xf0v/FomsfJSbrFQqwWq1YmdnB16vF1euXMHQ0BDy+TxmZ2exuroKrVaLsbExZDIZeL3envr+xAMVFSNotVocsErJvcSFRSEUarUaOzs7KJfLvLNRLh2Hw8HihvhB5WLDiKRss9Ju1U0x2kv7pAfS6XT49Kc/jYODA6ytrbEpOB6Pw2AwwOv1wm63o7+/n3PKp1IppNNppFIpLC8vY25ujssc9fX1IRwOY3R0FG63mz2xP/e5z3F2iffee4/LkpXLZfbiJncGMlOfOHEC58+fRzAYxObmJn784x8jnU4zENJGUKvVsLu7i52dHd4UqDAq+RvRgh8eHsbU1BQAYG9vD/v7+21cF1noyJP85MmT0Ol0DAAUhE7hHCLo09zY2dnB+vo6Jicn2wwp9XodmUwGW1tb2NzcbBP5xLkhumCIi57OU91Eim+kuaFksOlmyOlE3fRYcroupWttNhsGBga4+rjNZoNGo+E5UiwWEYvF2MfKarUiGAxyNAFlM+lGTzxQFYtF6HQ62O12WCwWxGIxFAoFnuxqtRoHBwdsIaKF5ff7WVnrcDiwv7/PDn60C4pWrF5JnASdAOy4bLrof7O3t4cPPviAleEk3kQiEWQyGSQSCUSjUezv78NqtcLr9SIYDHICvVgsht3dXcTjcayurmJpaQkmkwkejwd2ux19fX0YGBjA+Pg4AoEA/H4/3nzzTbz44ottQJXL5VCr1TixmtfrhcFgaONOKCyGOBEKa1KpVKyTku7qougVDAbxxhtvsFJ2Y2OD3Quk9zSbTbhcLthstjYwosVGAbJi5R0CltXVVXz5y1/GG2+8gYmJCajVas4c++DBAxSLRQ6RIeukKLapVCocHBzg1q1buHbtGgfllkolJBIJvPfee3j48GEbwNJ9Uo5ZjgtS4up7mY/ic+TmXyfKZrPY3t7m8B+Px8MWze3tbSwvL2N0dBR+v5+55mKxCLfbjVKp9NThk4gUpWNjYxgZGcHs7CxCoRD6+vpYkarT6ZBIJFjPQfFKVL8OOPL1oUBVcacjkjp/Kiko5f4+rmJejm0Xdz7SL62srGBpaYmtfePj4xz7RnqqdDqNw8NDLC0tATjyi/H5fBgcHER/fz/resiqk0gksLi4COAo75XX60U4HObSSH6/H06nk3WClLeKSCyAOjU1Bb/fjw8//BD379/H5uYmCoUCA42oOJcGglutVoyNjeGll17CmTNnuKDlysoKT37Sr9HiJ+U9pfOhBa3T6fD8889jY2ODLbuiiE8i7NraGv7iL/4CZrOZwZXyc7388ssYHx9HIpFgY4IYAA4AuVwO3/jGN7C5uYmRkREYDAasr68zF1gqlWTFRqvVys671LdOzsbS40pinnTedJuz9JtAmPpHonk6nYbFYsHg4CB2dnbgdDpx5coVhMNhqFQq3L59G0tLS5iYmEAwGEQqlWIRvBs98UBFplGbzQan0wmXy8Xl3EOhEOsyzp49C6fTiVKphK2tLczOzmJqagqnT59GNpuFwWCAxWKR1UlJqRtbLqcL6KTA7ETE3YkTbnJyEv/sn/0zbG1t4c6dO1haWsLCwgKbjvv6+jAyMsJOlMlkErFYjJP0U+FSi8UCr9fLwE7m+MPDQ+zv7+Pw8BCrq6tYXV1lpz6fzwez2Qyv1wu/34+hoSHOOGG1Wh+JW+vr68OnP/1pnD9/Huvr60gkEjg4OMDKygrr10ik1ev1cDgcmJiYwODgIFsrKV3P+vo6NjY22jzcATCX5vF4MD09zTnvaZzVajVOnjyJM2fO4Kc//WmbbxjQng2B3DJEw4DT6cTExASGh4dx+/ZtrK2t8fUi2BKHfvPmTbbuSbMHkNhHlj6VSoW+vj709/e3+ZSJfaLvfpx5I84zqXgnJ/op3WO323H69GkW8Uj0s9lsnNIllUrxhqbRaDg3XDgcRi6X66mfTzxQ7ezs4Pz58+wt7fV6WVel0+mg1WpRKBQQi8V4R/d4PLh8+TKXoPb5fKzjESvQdKJOICTloB6X7ab75XZQn8+HQCDATp0kwm1sbGBvbw+RSARGoxFmsxkej4d3vXw+j0KhwMn5d3Z2EIlEoNfrYbFYYLfbYbVaceLECS7qSpbEfD6PnZ0dlEol1Go19hYPBALY2tqC0WjExMQEPvWpT8Hr9SISiaBcLnMytVAoxB7cxWIRh4eHqFQqMJvNnFrFbrdz/nZRvKtWq0ilUpzpgXSM5K9F3z4QCDzi+d1qHdWae/PNN1GtVnHz5k2OfSTlPbk3EIiRjqter8PlcqG/vx/BYBDXrl1DJBJBLpd7ZEMSXSSIeyKgFC16Yr+mp6fx6U9/Gv39/cylEXDLzRUlzkh6rdgvpWs6EYFoLpfD0tISjEYjZ/D0eDzw+/3Y29vD7OwsXC4XFx41m81sGS2VSvxdu9ETD1ThcJiV42NjY0gkErDb7fD5fADAJZ4KhQKy2ewj+g2dTodkMgmNRsPKdCI5cOm0w8lNIukE7cSNdZpEUvATY/j6+voQDAZx8eJFJBIJLrKwu7uLaDTKcXhms5lzCgWDQfaYTqVSyOVyrN8itwCTyQS/3w+bzYbx8XEGBcr6WCqVYDKZOLFavV5HIpHA1atXodPp8M1vfhPLy8sIBoN47bXXMD09jf39fezu7sLpdMLtdqO/v79N7BE9tMXFZjAYcPXqVZw6dQrZbBaZTAbFYhH5fJ7T+kxOTsJisbR9XxEkwuEwfvVXfxVerxcffPABIpHII64fxGmJSnFR0f/cc8+hXC7jhz/8ISKRCCvjpfNAyhGR5Y+4L7vdjnPnzuGNN97A0NCQbH/FudYrZ9RJl9WrQUf6HNoYDg4OmDs9ODiATqfD5cuX4XQ6YbPZsLm5idu3b0Ov12NiYoKjIHqhJx6ocrkc50MnN4OHDx+iUChgbGwMGo0GyWQS09PTHN1N4kyj0UB/fz9UKhUH+UodPpXEwE67mtx1cmx8LyTeIzp+St0EWq2jQqoDAwMYGhrClStXkM/nkc1mEYlEEIlEsLe3h8PDQ3ZTsFqtcDqdXFpMp9OxbotSM6+srDBoENBRaIjFYuEYL8o1Rfmk5ufncfPmTSSTSWxvb7OY+Pbbb+Odd95hUa+vr4/zM01PT+OZZ57hmoKUGYIi9smZkNLbiuMoZhYVx0ccM1LO/8qv/ArOnDmDDz/8EPPz8yiXy8hms5zi2GAwQKX6KKRnZGQEFouFK7J86lOfwvj4OD744APcvn0bqVSKleyk8xQV9QA4G0N/fz9GR0dx4cIFnDp1ChaLhfsncmC9cPRSy6N4Tjp35M4rXSPOf7fbjbNnz2J7e5vLYxmNRrjdbqjVanaBIQPEiRMnOGZ2YGDgqehHdHh4iNHRUXi9Xuh0OlYs12o1uN1utkKsr69jbm4OKpWKlYB6vR7FYhFer5eraMiFLnQjJTlf7u9u90qBTg6YREuQOFlFDoDi9zweD4aGhtglIJfLYX9/Hzs7O1heXsbBwQE2Nzeh0+m48vHg4CBcLhcqlQqi0SgSiQQvZLImqlRHnudGoxHXrl2D0+lENBpFvV7H3t4e3nvvPRSLRV68+Xwem5ubmJubQ6lUgl6vR7lcRiaTweLiIoeQPPfcc9jf38df/uVfIp1Oo6+vD2+++SZOnTqFra0tLC0tIZ/Ps07KZDKxw2u9Xue+2Ww26PX6trEidxWdTofTp09jaGgI0WiUk+Ulk0kAQCgUQqvVYu6bAr9JNNNoNJiYmMDAwACef/55PHjwAKlUCrVajVNDUz08us9sNmNycpItZEajkTlH0SggR3IcuMiZk7iqNBcf5zi1nUqlcOfOHZjNZi4oSh7oZF0mqaRYLKLRaCCdTqO/v5/LtfVCTzxQTUxMYH9/H5FIBGfPnsXe3h47cpI7AjmtEfudz+exuLjI5v3Dw0MYjUZ4vV6+TqoMB5T1A3SdnL+V3O6lREo7nciVSa9V6o+0r8QpkDh35swZvPTSS4jFYtjZ2cHm5iYikQgHm6rVR6mCrVYrPB4PRkdHGexIB1gsFvkfAE5d8q1vfQuHh4fMXalUKuzt7eH73/8+IpEItFoti59LS0solUpoNpvY3d3F3NwclpaWsLu7y75aCwsLWFxcxOrqKh+ndyLd1D/+x/8YTqcTX/7yl1Gr1TA+Po4zZ87g3LlzUKvVKJVKuH37NsfViSlZSIFPfmEEZmKiQQID4l5VqqOYy9HRUYyNjfGxYrHI1XUIyInTo0K4rVaLw5PoHH3L4+qZjrMJ9kri3CHDSTwex/b2NorFIs6cOYNCoYBqtYrJyUkEg0HY7XZsbW3hwYMHUKlUmJqa4iDvXuiJB6qDgwOMjIywIvXg4ADr6+soFArw+/2wWCwol8u4dOkSl24nPQllfqQFRQtObsJ00kV12glF6gZ0dI/SNVLg6XSfVIlPOy+FjABHk3BkZATDw8N45plnUCgU2CpHwc6RSAQ7Ozucm5xcI0gvodFo4PV62dJmMBiwu7vLFYFo8W5sbLB4qdPp8PLLL0Or1TKXq1KpsLy8jP/n//l/2jzFS6USrl+/zn5NarWaN6JMJoNWq4X9/X389V//NUKhEBYWFtBqtXheEKdSKBTwrW99C+l0mhcQPXdychK/+Iu/iOXlZSwsLHAgM1mTr127hmAwiGg0yiEwJKKdP38ebrcb1WqVi4dQmpOpqSnONrqzs8MgSOBF36+vr68txbN0TkjnkxTAlMQ38e/jAp54zuVyoVwuw2q1wuVywe12cwJDMsgQRzs6OspViqg8XS/0xANVsVhkxzLaxWh3NJvNvEAfPHjARR8GBwcxNTWFVusoZ7bJZEK5XEYqlQLQ2aIn0nF1Vp0Un3LtyClNe5mAImen1IaoFwE+csx0u904ceIEj002m8Xe3h52d3exv7+PVCqFTCaDnZ0dZLNZtFotDqcgUYbiJz/xiU/gpz/9KZf0KpfL0Gq1uHLlCq5evYq//du/bdOvkehEC5n6m8lk2BT+iU98Ai+++CIymQz+1//6X1heXoZGo8Hu7i52d3dZV9VoNNhy2Godhd7k83nk83m2OrZaLdRqNdhsNnz1q1/F3NwcnwfAMaLnz59HqVTCD37wA7z//vvs+Elc1muvvYZ0Oo2vfe1rXD3n6tWrGB4ehtFoRD6fx9e+9jXmVGnMtVot+vv78Zu/+ZsIBAKKc0OqTFeaJ51Iaa5I25BuboVCAfPz85zSW6/Xc2YJsXQZtZ9IJJDP56HT6VAqlXBwcNC1b8A/AKAaHh5m/cnQ0BAODg7a0u0C4CBJm80Gleoo8f/169dhsVjw6quv4tatWzCbzZiYmGjb2XrllJQAR44T66U9ufNSDkmpPSkYEZHJXrrDiYtA1HsRp+nz+eD1ejEzM4NarcbJ/rPZLA4ODrist9frRTqdRiaTQa1Ww/T0NM6fP4979+6xNa3VaiEUCuGTn/wkDAYDK+pJ8er3+7G+vo5kMsl9Jz0T5X4aHx/H0NAQGo0GFhYWOLaMfMDIP4l86oii0Si7NKhUKm5XrVZjf38fGxsb7ARMYq9Wq8Wzzz6LgYEBPHjwANevX0cul2PjApUhu3btGqLRKLtbqNVq+P1+Ns4cHBxgd3cXmUymTQUBHKkuCISlXLz0O0m/8XFEwOOKgXQ9JT08ODjA4uJiWxXtZDKJ0dFRBAIB+Hw+RKNR7O7u8hgbjca2b9CJnnigWl9fx+nTpznRmdfrxd27d5HP5xEOhzm/s9/v52IPpJcol8sAjpxGq9Uq60qA7o6e3bgtur6XXazT88RrlZSq0v5Jz0m5p04ignheyo3p9XqYTCa2+ABHXAelTblw4QL7R7lcLvh8Ppw4cQLAEVek0+nw2c9+FoODg1hbW+OqMRqNBs888wzeeOMN/O///b/x9a9/nY/b7XYuTlqr1XD79m20WkdVlulvUnKLYU9ms5k56nq9zskUgY+CqVutFvx+P1wuF3Nm9E4UNH3ixAnEYjF85zvfQSqVYqU/AfrW1hb7sdF80ul0nE4HANcqFEtvqVRHhROuXr0Ku90ua0ARx15uzsh9w050nPlGvxuNBouzBEjhcBjAUeRCJBLB4uIiBgcHOb50ZGSELX+kT+xGTzxQaTQaxONxVpCWy2XMzMxAo9FwmaRqtYrV1VVO0tbf34/BwUEYDAaUSiUYDAb2FRHjzIDOAZ6dqBsoyLUpcjPS67vptpSsRt1AqVP/5bg4AgQR0ElU6+vrA3CUI6zVOsqz9JnPfAavvPIKcrkcKpUKwuEwFwh9+eWXEYvFUK1WMTw8DJ1Oh76+Ptb5eL1enD59mounqlQqfPDBB3j//fdZp0hOrVSEgN43kUjgL//yLxEKheB2u7mKCvmIEdD29/djamoKsViMOUYCt/39fbz//vswmUzsja7X62EwGJDJZNjzPxqNIpvNsthJXBmpHZLJJFsQ6TuR4yuF+4jfXZw73dQE3eal0nklnZX4HBKRKWyJxPNcLge73c7v6/F4WFpJJpM4ODhAf38//H4/tra2OvaP6IkHqtHRUfb7OXHiBJaXl3mS6PV6VKtVlMtl5qiazaMc1T/84Q8RCATw+uuvcxknl8v1SG4gOerEtXRjwTtRt/vl+qGkg5JO4sdh/8XniO1I/6YFKRIdozQ7pIMh3Q45XxIokEPl6dOnYbVaOQvG+Pg4JiYmsLi4yLX6stksCoUCDAYDnE4nZmZmOGUwKdyz2Szu3r2Lhw8fwufzcdI8cZyIIyKXgv7+fmSzWaRSKe7//fv32QjRarW4vDkBi1qt5lQ65PhZLpdx69YtFItFuFwurK+vo1QqsTOrWn1UNquvrw9Wq7VNJO+Ve3rcbylHUjAUf9vtdjzzzDPY39/H3NwcZ7ugQr/j4+NwOBycrYQs6GazGSaTCf39/T314YkHqoWFBczMzHBqCa/Xi9nZWWSzWeaaKpUKrFYrm4dJpNDr9ahUKvB6vayQV9ITiAu/GxgdB2w63Xcc4Ovlmb2AlRwnSf0gXVMnEZMWsRi3JrYjx6mR/qnZPKrv5/V6+VqdTodnnnkGZ86cYXGtXC5zilyNRgO/38/FESjImkQWisXb399HsVhkyxu5WtTrdQ5cTyaTzJWRioB+UyVmmk/kWFoul/Hee+8hnU6z3qter+PGjRu4c+cOhoeHkcvl+H2oACsFxEt1maK+kH7L6R2PM8d63aTkAKtYLGJra4v1kG63G8FgEEajEVqtFpFIBNevX+dUQZQKnKzD5JvWjZ54oCI2nLIONhoNnD59mj2vaYfd3NxEMplEuVzGyMgIJicnWWdlsVh44h6X8/hZ7GxK+ohuwCXloHoVD7rpJ+T0Xt1EYfEaMd+SVATu1I4ciBGnIQY7k5jRan2Ua93lcmFqaqot9EYMY6lUKqjX6ygUChwiQ3ovleqj5HoUVpTNZlnnRKA1OjoKj8eDTCaDhw8fciiR6GAr5S7tdjuAIydSei6JxR6PB2az+ZHvIQ1CF8dHbg7IgZdUL9krSa+v1+vY3d1lMZsKV/h8PhQKBVitVkxPT8Pj8UCj0WB5eRmbm5sIhUKYmZnB5uZmT8994oFqcHCQnQ9ptyPAKZVKPEH7+/sxOTmJWq2GZDKJDz/8EE6nE5cvX+YSTj6fr60KDaCsqxHPSUnpeDe2XdQzScFL/J+uldt1xefI7dbSiS0HQkp97kUBKz5Xbjyk14vHxZQpcotObjzE/FDS8CexLRLLKG2u+E+ayZXuEyswAx9luwSACxcu8HWUO570TgSCwBG3WC6X2xw8SfSjMCRRlFT6dkqA3onrPq6YKB1bleoo3c4zzzyDRCKBtbU17O/vcwQIZfAkHztyDqVSZ5SYsRd64oFqe3sbJ06c4HQjLpcLDx48YDd+s9mMWq3WFo1P9fxocrrdbqTTaa6aK7eoOk2IXhSTna4rFAqIRqNotVqcJVHMlSVOOGmoRDfdmChKKIkTxxVlO/2WA5pufVP6LW2T/qdxofEQU7KInJS0/yTS0ViIWRbE8aExJlFOKqKpVEdWRaV3V/ot9k98jvhdj0OdgOxxSdpOuVxmJ1er1YqzZ8+yCKjRaLC1tYWVlRXOWUaJFKvVKnQ63dPEeUQUSEu+HblcDqOjo9BqtZwnHQD7sVCg6/DwMBwOB1qtI8dGo9HIfi/Ao9xHN0Ag6sSaS6+j/7e3t/Hee+9hcnKSnSgpuZ0c2ClxU9361ku/lO45jk5E7JOUExTbklpYxX5RG1KwFtsVU6aI58UMGErvSM+RVq8R7xH7Lj0mFU2lJCd2SduQi9OUGyfp/Z3A8eOS+M6kzy2XyxxcTMkVT548iY2NDej1eszMzGBgYAAq1VGh2vn5eZhMJgwMDLChqhs98UBFyfGKxSLX78tms7wDkOUvFApxLu2trS3cu3cPHo8Hzz//PAqFAvR6PVelIZKywuIx8RopyR2TE0kAcFoRp9OJa9euQaVSYXt7mxOvjYyMtLUhTiJpW9Lnin2WTnI58Uja115BqttiEZ8hFbuk/VVqS27sxBg5sY1eSEl8Uhofpba7iVedRGcp4B1nM+iFHodblZ4zGAw4d+4chwjt7u5yuBTlErNYLKhUKnA4HHA4HGy51Wg0GB0d7amvTzxQ7e7u4tKlSxgdHYXL5UI2m8XDhw+RzWZhMpmg1+s54p0sPE6nE+fPn+fdwu/3c3I9OXCSo144EukCVbqmUqmweV6tVmN4eBgqlaqtrh5ZxqS7vPRvpRS2cjs2HZf7rSQSKi1o6Tt12v07gaO0HaU25EjaZwJ0OfCRW8TS63oBDiU1Qaf36AZ+cveK/ex0rVQS6NY3KUn7UygUMDc3xyLdmTNnuIIT5Rej7BeUfod0xZVK5WmlZCKXy8UBxidOnEClUuHik2SatlqtSCQSnIqDTOBUlYaCW0knQdRtUvRCnfRU1MdiscgiC022/v5+Vszu7+9z4QUqiCCXiI8qnJADpvg8UdQQ+9YtF3wnsFI6Ln3HTmCl1M5xRJpOi11O9Oz0TCXw/Ljilhw3LPZP7l2UAF3u3m4b6+P2mwwI6XSaqzXt7Ozg3LlziEajbbnxNRoN1tfXuYai2+1+WoWGyGg0ctlstfqo3DeVCu/r6+NBpnp3wJHX8vLyMpxOJ65evcomZkrqL9X/PI6eptfrW60WPB4PVldXkU6nOX8R1U9rtVq4efMmZmZmOGtAs9lEoVBgMz095+HDh9jd3cVnPvOZtnL10p2206SWOycdDyWOTbqIlLgBJS7sOBzMcUhJ5JYe6wYMcsd66bcS+HUD0U5crfRe6TEpgCk9Sw6gxWsMBgNOnz6NfD6PjY0NLsmmUqk4brFWq3FgOqWxtlgs8Hg8UKvV+O53v9txfIB/AEC1ubmJ5557DgMDA+zLQjmbybGTgpYPDw+RzWbh9Xpx7tw51l95PB5OxStSJz3NcTkqOTGQxJLJyUkUi0Xcvn0bHo8HOp0OBwcHOH36NFwuF5fSpv5Uq1X86Ec/wpUrV9jzl0zGP/rRjxjk5NLaSnMq9QoaUsBWEuM66UGkf3dahHLXKImU0t+dRHel+0RO57icRy/XK82fXlQMvT5X+n26AW43EVetVqNYLGJ2dhbFYhEWiwVTU1OwWCxwOBwwGAxIJpMcnkYVy2u1GmKxGKxW6yNrSomeeKAaGBjAysoKstkspqenEYvF4Ha72QGtXC7DbrejUChwGEOhUEAul0NfXx8sFgt7zzqdzjaO43F0FnKkNKFI/6TX63HlyhUOQYjH45yxlECFLJakc9vd3cWpU6e4HRJdrVbrI/2kKjvkECvG6ilxW70sJPG95JTBSu3IgYJ4byc9m1zbxz3f6VwnjrITKYG7EvUqjso9p5c+Kb1jJ65aCeAqlQqSySRv5iqVChcvXuSMEVTT0Ww2c5BysVhEIBB4WtKdqFwuw+v1wuFwMJpTJDul4E0mk5iYmEBfXx9sNhuWl5extraGZDLJ7Goul+MUL8dl7ek66b3icSUSc3sbjUaEw2H09fWh1Wqxy8Xly5exubnJSstkMtlW5YSeUygU+LcIRFtbW0gmk7hy5QoH8NbrdWbdO72LHGATiZNeelxJ3JBmTxWfKSdmd+PAOpGSjkmpfek9nY6JfRavOQ4H9HFI7t1EEOu2ufby/q3WUQ3JK1eusK/f7OwshwSFw2EutWY2m6HX6+FyuVCr1bCysoJarfY01o+IcqZTXN/w8DDHeVHMGLGi29vbaDab8Hg8OHPmDIdLmEwmLt0tikVE3XQJUtHmcSeHWB9OVJhPTU0hGAyiVCohm81Cr9djbGwMJpMJKpWKc5JT2W2pk10wGMTs7Cy8Xi9OnTqFaDSK9fV1TExMwOfzcfgQ5WHqBag7LUy5AprS3VwKTErmeSXdSbc+9Eq9AKLc91fiOJU41E7P/rh9F3934+ykm5v0faS/NRoNDAYDB5KXy2U8ePAA+XweQ0NDKBQKHCNJ39zhcMBms3Feql7oiQeq4eFhrK2toVQqYXR0FDs7O1x+2mQyoVAowGKxcA4ileqotl0ikYDD4cCJEycwPz/PBTZVqo9KbouDLA1x6JWUFoKc/ktM0i9a6FQqFSeCo9Lmp06dYu91Eg0LhQJMJhP29vbgdDpZ6el2uzE5OYnV1VU4HA6uGDMxMYFms4mVlRUcHBzA6XRCr9fDbDbD5/PBbrej1WpxqW6x31LOTfpuSmBE10gXshLn1k0MlQMyJd2M3JhLnyf3W4k7VGqD/pYDbLn3EL3rpXOsF5BR6utxSOnd6Pu3Wi3Oq0VJCskFwWazcXGQYrHI6ZSocGwv9MQDFcnCHo8HDocDRqMR8/PzyGazXC4rnU5jamoKbrebCxDs7e2x97rT6WTXBQBtNd0AeYtWt12pk85DiUSveLEd8R9dY7FYAHy0GPr6+vDKK6+w3wpxWsCRiXlmZgbb29v4yle+gnA4jGvXrqGvrw+1Wg337t1j0VClUnGBzjfffBN2ux1ra2sAjhIMUj9pcnbShdC11WqVS7lTmSyKBBDHjcZdDgCUdF3dgOpnxXFRv0RveinwiQUgxJxXUqCTAnWvOciURNlOujqRlMC2EzfZbDYRjUY5W0KlUoHL5YLD4UCj0UC5XMb6+joH+1ssFhgMBpw6dQqBQOBpCA1RJpOBy+WCRqNBpVKBxWLBxMQEV+glz++trS3Mz88zhzE+Ps6JwEj0o/LvckBB1EmZKbdo5cRCOdFC+iy5SSq3W4qLllw1xF2MFoLFYsG1a9cQDocxNDQEv9/fdp7Sj7RaRylNKpUKyuUyjEYjbty4gb29PbzyyiswmUxIp9MwGAyYnp6G1Wpt66c0Lq7RaGBjYwMPHjxAKBTiYrC1Wg1nz57lAhDUF1F3JrZF5ykIWWl8pGMtpxOT45BEoBE5QpGTFP9Jv5HSvJDrB/0T9YOdAOrjkBTUlURVpec2m03Mzc0hl8txEY/BwUH4/X6u7kMcPdU3pKIPtVrtkfmhRE88UA0ODiIWizELStk+KQ0t5Sei4gU0qJFIBD6fD1euXOHabhaL5ZHKrp0mTTdRQ7xOjqUX71cCPqXnSnd6Wthy7dAC9/v9CAQCvAApPe758+dx//59TuURDAZZSUrs/eTkJC5cuACtVotMJoPd3V0OoVDa+el4JBLB4eEhXn/9dZhMJuRyOdy/fx+bm5sctqRSqbi+ntvtZrGT+knnZ2dnEQgEOA5SBESRgxGrLXcaR3EMxXvluB258aXzZPggsBPj+MR7CPikwdBSTktuDiiJe72QEkhJnyO+K5Wco4KzlGgwl8shHA7D5/NhfX0dwWAQJ06cQCgUQiqVwjvvvINoNMrHeqEnHqgikQiGh4e5tpjJZOIdYGhoCGazGalUCleuXOHo7p2dHayvr/Pgu91udhhVYq9FUuKcetkJlVhvuV2NrpNLVid9rig+ZTIZWCwWjsmiBU/naRHTIjp16hQGBga4UAP9T8/V6XTw+XwwmUxotVocQiE3RlJOiEBEo9GwuKjT6fDss88yuJC4FIvFsLS0hMuXL/NzacFQOMb169dx6tQpBINBFq/EFMNEcjpFOVGN6vfV63V8+OGHGBkZgdlsxubmJmZmZh4R8akuZDQahcfj4erb29vbnFtcpVKxC8zp06d5DsZiMZRKJQBHZdLtdjtGRkb4nm7z57ggJreBKP2W+47AEbAODg5yBs93330XjUYDZrOZN7X+/n7mpBwOB06ePMlc+9O6fv8vkZWOwmFcLhfOnj2LUqnEGT2bzSbW19cxPz8P4KhM9dTUFC8QcvwUTf6d5HgpJyRl+3vhwqTXKYlz0mOdJptGo+EUvOPj4xgbG0OhUMDm5iYnOyPPd6k4RKlvVCoV+77QuL788sssQtNxuf5KdTAAuAgspfAlkYdETABtOp3r169jcnKSLbbUTqlUwu7uLlcZ8nq9mJiYgNVqRTqdxvb2NmZmZljvlU6nEY/HMTExoTiGYl7ztbU1vP322zwvbt26hd/6rd/C2NgYv3symUQ8HkcsFsPt27dx9uxZfOITn2BFM4ms9Xqd9X5DQ0MwmUz4/ve/z6XCdDod4vE4vvvd7+Izn/kMRkZGmItT+rbiMSXO6rgio5wKQvRvo7mwvr6ObDYLv9+Pvr4+DA8Pw+VywWg0cuHRtbU1hEIhThJQr9eRTqd5Q+tGTzxQ+f1+VoRfunQJe3t7vFsC4Enk9Xrh9/uh1Wqxu7uLd955B3a7HZ/5zGfw8OFDFh1J9FNKuSvVUcgdk6NOk1COLZcjJY6KiMpEud1uDp+p1+vs8Lm8vIwLFy5wEQaqsycGbhP3RZyOWq3G0NCQImiKYou0P8S1hcNhrK6u4sGDB7Db7ahWq5ifn8fg4CAuXbrEoikFXlMCOpHDJYuk3W7HzMwMpqamYDAYoNVqkc/n8YMf/ABOpxN9fX3QaDRYW1vDhx9+yDnJlDYa0nnZ7XYev1wux2oCire8ceMG510KBAJQqY6sx63Wkb/b+Pg4OxPfuXMHDocDzz33HAMubajVahWNRgPZbBa7u7soFAptrii9kBKASedip+uVSA4EHQ4Hx6QeHh4imUzyZkFr69q1a/D7/ahUKrh9+zbW19cRDoe5Yk03euKBihLnEco7HA7cvXsX6XQag4ODcLvdODw85MR6JEYYjUaOU/J4PIjH47KTRU7EkypC5agXZa7YjrjQ5XRaSkAm6kBIEe10OpmTtNlsnEt8b2+PPYnz+Tzu37/P5Y1UqqOqxKVSCXa7va2MubS/cmMi9kcsfNBoNHDixAkuT0a19agSEIlsmUyGxfGdnR2EQiHY7fY23RMFyKpUKi6K0Gg04PP5MDk5yTu/yWTCxsYGOyaKY0l9FUXDcrmMw8NDrkJDAG0ymTi6oVAosMhLxW4LhQIbHKj9paUlzM3NcVkwArtXXnkFyWSS9VyRSIQjCaTj+nE5Iyl10k11u4+KpOr1ek6fVC6X4fP54Ha7uSJNsVhENBrlQh4OhwOBQOCRCtBK9MQDFS0wSjHcbDZx6tQpqFQqBqNisYjV1VVkMhmukDE+Pg6dTscuCRaLpU15KqYHkXsmkZxCViTp5JMT4aSLiNoSr5XjWKREC5rEWeKOWq0WfvjDH8Lv92N4eBixWAwrKyvY399nl43Dw0Osr6+j2Wzi5MmTqFar2N/fh81mg91uh8/ne8TcLhV75cTSZvOocjIVDaX+kdIaAJdQHx8fR19fH98n6oVIYT0zM8MVemkRWCwWzMzMIJVKwWKxcDVfq9XK3JnSuFG/qbBHqVRiP6BEIgGv1wuTyYSXXnqJry+Xy7hx4wbr3MQxSSaTMBqNj3BSZIHOZrPY2NhAo9HAr/zKrzC3KuVMxTGUzqFuQKO02Sop7OXuo/MU6bG/v88VhWg+mEwmFItFHBwcYGtrC3a7nVO91Ot17O3tsUtLN3rigWpgYICtUHa7Hbu7u22KZNqR+/v72a9qa2sLH374ISwWC958800kEglO/NWrfkmOvZZOql4V7NJ7pKQ0QemZUt8eqWLZaDTC7XZzodC5uTm4XC5MTExAp9OhUChgfX2dRSebzYaNjQ1otVoUCgUsLCzgypUrLDICYNM0gQwptEXPdlGpTn2krJHiuxOgut3utgo0Un2hWq3Gq6++2pYnXQTjfD7PpbesViueffZZNgDI6dXomEajwfj4OF5//XUMDAxwltjJyUn2yhZTWatUKpw7d451esBH9Q6DwSBnihUBslqtcrn30dFRPPfcczCZTG3Xid+5V1CSm0dK80f67uI56VjT3NJoNMwlabVaJJNJ7O/vAwD6+vpQr9fR19eHq1evwmazwWg0YmFhAZubm+wu0ws98UB1cHCAiYkJTExMoL+/H3t7e7h37x6q1SqCwSAMBgMikQi7JzQaDYTDYXi9Xpa7PR4PEokEyuVym6jRSZktd076t0hKegUpSX1regVOaYI4+pv0LS+99BJu3ryJeDwOk8mEeDyOTCbDY7S/vw+n0wngI0sP7Ypiimaxb/l8HrlcDoODg6y/GBoaglar5XEUQYd0MfV6Hc1mkzcTkROUgrZ0cyCFtRgj2Ww2MTw8zPoQ8Xmi/kduIROIGgwGXL58mcdRBHupOK7VanHx4kUedzGiYHJykvspvovVamU9ltiu1OdNjrtW+uZK1GnOSPWL4nG5ua1Wq2GxWNhFYWdnB8VikQs5UOmvra0tNBoNjI6OQqfTsY8dOSZ3oyceqLLZLLa3t+F0OtlJ8ezZs9BqtazcLJfL2N7e5mq3VI2X9A/Emoue0uLkE0luwosTTG63UqJOu6ac+Ndtx6Tzdrudd7JMJoN0Oo1AIMBZTq9cuYJisYgbN26weV6lUiGVSiEej2NqagoejweHh4d4//33cebMGXg8nkfelaoT08Im5TJxCNQf0aKl1Wo57zZxuKL+i/RsSoAl1euJ30oMKpfeI/4v3i8aXUROT+RWSRUgnhNFPtFnS9TpSecC3SO3yfUCQMcV+cR7um2w0nboumazic3NTezu7sLpdMLr9aK/v5993Wq1Gvb29rC/vw+V6siZmnRZyWSyjQvvRE88UI2NjSGdTiOTycDn8yGXyyEej6NWq7G1h1z6KZZvY2ODLTOf+cxnsLW1hXq9zuhPk7yTJeY4op14j0hKgCbVFXTi5sSdnn6Lk4Pq0K2srECr1bJBwWq1YnBwkPV44+PjOHXqFNbX15FKpTgL6qlTp3B4eMhFXMV4PRL3yA+p0WigVCphc3OT8xeNjo5ysVCyrtVqNezv7zM3R+JiuVzmZ4ugIRWjRBCgd89kMpynWwQpkWORcnjiOKvVRxWPU6kUtFotxzpSBliTydRmCRS5bpGzI18qMVtrL9z3cYCkV5JTFXQCOzkOS6fTwePxwGKxQK1W4/DwkLkn2uwdDgcuXrzILi6Li4tYXV2FSqWCy+Xqqa9PPFClUilMTExgdHQUfX19iMVimJ2dRSaT4TLumUyG45QoncrZs2e5xDvtAsRZyJGSovM41OtuRv8rgZScrkXKwRBRWXQKLCWdjUqlYvN+q3WkBE4kEhxKlEqlYLPZcP78edy7dw/pdJrDIcQ+ZbNZ3L9/HyaTCQCYs6nValhfX2cOijaCarUKrVaLw8NDrK6uotVqYWBgAH6/H7VaDdVqlb23i8UiSqUSDAYDLBZLG+dCoplKdeRcubu7i8HBQdjt9jZOSdSX0fhJLbHEMSWTSWSzWZjNZqytreHcuXNotVqIRqOw2+3sZU1tSvN6tVotThhH9QOPM0fkgELKDYrP73Z/ryQnZovvaDAYYDKZ4Ha7odPpUCwWodfr4ff7+VsfHBxgc3OTRb+ZmRmYzeanflREzWaTJ3y5XEY2m2XHP7VajXK5zAm+8vk8++KQX06zeVRiS6VS8T1KHA39JjqO/kBpN5Nrg66V+nJ1Y+0pZq/RaDCn1Gq1+L1E3Q6ANs4rl8thZ2cHjUaDQyFWV1dhtVrZa1867q1WC2tra1w3cWRkBDs7O4hEIjCbzSwC6PV65HI57pNGo0F/fz+mpqaQTCaxsbHBhSvJraRer2N5eZlDmwwGAwKBAFZXVxnQ/H4/hoaGsLW1hdnZWVSrVZw5cwbVahXRaBSNRoNdVg4PD1EqlXiXpwVEgNdqHcVK1ut1BAIBzvtNQE7cNY2v2WxmB2FSMtdqNezu7mJ8fLxjSJP0W3c6323+iNRtI+3lfim33modlXPb3t6Gw+GAz+dDKBTiLJ9qtRrRaBSRSIRdW2iMtre3n1ahIaKdmNKT5PN5LiRKaU5yuRxGRkbg9XqhVqvZS93j8WBgYIDDGkiHAMiLZVIxS4mUJoxcjqZObUj/0XGlNnK5HNbX17lU2NjYWFsVYaA99YgY3EtcV71e5wVLdRGtViuXKxc5PQqjGBwcxOrqKlcFHhgYQCgUYitgMBiEy+Xi/o2MjLCbiJjHiCxs9F61Wg3Dw8OwWq2ciicej+PChQuIx+OIRCIYGRmBx+OByWSCy+VCs9nE7u4uj/fKygpGRkZw//59juZPJBK4fPlyG3dFILS2toZ4PI5UKsVtiJkQ8vk84vE4pqensb29DZXqyD0mn8/DYrFge3ubveGlQc6dNhzpt+11rimRnI7sOCTGKppMJoyMjMBgMCCdTmNpaQn1eh1er5erRI+PjyMQCMBut2N7exu3b99mY00v9MQD1fr6Os6dO4ehoSF4PB4Eg0HcuXMH+XwegUAATqezzXEROOIkfD4fgCM/kVAoxErcbvS4H56oF3CSe6bS7iuKhLlcjmupbW5u8kKu1+ttIEm5uURXAhKJqU1y9BM5A7EPrdaRAeLatWswGo0IBALw+/3I5/OYm5tDLBbD4eEhAoEAEokECoUCO2iKuj9ywCXn20ql0vZuVquVxVXKA3///n32ndPpdPB6vbzpkKf6+fPnARyVe6pWq7Db7Th79iwKhQIePHgg+z30ej1OnjyJ/v5+/OhHP+LCtCLQm81mxONxFItFJBIJhMNhJJNJnDp1Cg6Hg7+BElD0ykHJ/e50jxzH1cv9UpL2udVqwe12s+Xv4OAAxWKR9Xiiw+ra2hrcbjcMBgNmZmagVh+lA+qFnnigcjqdqNfrKBQKbBY/e/Ys5z2qVqtQq9XY29vDgwcPuDqGy+WCwWBg+ZoqvHTipMTjx9U/iG2JJAdOUi5KfK4SR9Vqtbg0mKiby+fzbcHJdP3q6iqGh4dhs9naytgD7dk2SeyRPot+U5qWoaEhqNVqOBwOFuNIAV8oFNi66HK5eOxbrRYnXAPAqUKIOxE3F+KQL1y4ALVajUQigfX1dV4kovWxVCpxrcRyucwir1QBL7qiqNVqVoQDH5Vzp7lFPk8WiwUWiwV3796FxWKB1+vlzLFUzYh0Z+I8URLDOm0+nUhJjfA44KTUDv2fyWQwOzvLCSkHBwc57bDBYEAqlcLGxgb7I1Kiymw2+9Q9gYiKju7t7cHhcCCRSPBEpQqu+XweY2NjGB0dhV6vx9bWFj744AN4vV784i/+IhYXF5HNZjnWTG5BSulxJpjSJJLTDUgXFV0n7ZvUD4cWHqWsWVtbw8TEBNRqNSvEjUYjKpXKIyKhtC+U2VPkxuQyetLiJO6LFjl5+zscDrhcLgZEyo9F4t74+DhUKhX8fj8uXLjAIjj5ZKlUKnaknJ+fR61WQ6vV4mIcxHkRl2iz2XD//n3OjqHX61nZT5yZyGXSO5fLZWQyGWQyGYTDYd7oCoUCW5BVKhXGxsYwOzuLkydPQq1Ww2w24969ezAajUgmk7LgLv4tNw/kvv/jkPQZUs5Obn6LzxXPEwdstVoxPDwMi8XCust4PA673Y6+vj6USiUMDAzg9OnT8Hg8HBi/t7f3VPQj2tjYwMWLFzE5OQmfz4dwOMyiH8nXpCwn87HT6eQo9mw2y/oUaeS4SHJKdblJKFI3BTqdFwGR/slxXvRcab9ID0UuGfSuADhrgUajYVFQpfooRKjZbCKTycBsNnNIERkZKAxHBKlOnCVdS75plNOd3kfU2VAcIHFV9Xoder2eQy5UqiOfHGqXajSeOHGCFdcU1tNsNjEzM8PWzqmpKS7qqtVqYTQaYbPZGCApl5XolAoAJ0+eZB0duRioVCrOwwUccXYOhwOXL1/m95uammKRdWRk5JFkcZ2AR+57Pi6nLjdHxA1PvFYEMOlmJ21Dp9Oxa4ter0e9Xofb7UYwGOQqTtVqFffu3YPNZmMVzNDQEAwGA773ve917f8TD1ROpxPZbBb7+/vMPV26dIkXYblchl6vZx8ZjUYDi8XCdQDr9Tri8Tjcbnebcllpwkjld6Vr5Ba0+Fvu/27ck3QyEuAQR0NFLJxOJ+LxOC8YAgZSlrdaLXbFaDabiEQicDqdCIVCiMfjzImSF3s4HGalKT2PDBVi/wBgZ2eHUxeHw2GcOHECAFgEF0FPykUQyXGYxGVRrBm1QefF1Mzk2yNuPqL4S24p0n4QyNPY0jUEcjTerVaLr1WpjqzFBGR0rfiNHmcTUxoX6d9KYygluetoPKRzU7y22Wwim81ibm4Oy8vLcLvd7D9lNBphMpngcDiwu7uLTCbDnLpKpeq5nDvwDwCoXC4X6vU6SqUSnE4nVldXsbW1hUKhwD4e9XodY2NjmJ6ehkajQTQaxfLyMkwmEz75yU9yonppug2pSV5OFBP/J+q0I8oB4ePqKeg6WmyBQAC3bt1CsVgEcGTJK5fL2N/fh8lkQj6fZ8saPZ9CUiil897eHgKBADY2NmC325FOp7Gzs4PR0VGOEaQgY9JP0QKm5HdjY2Ow2WxYW1tDPp+HzWZj/yIybqhUKqyvr2NwcLCtmk4nLpUAgDgh4oqo4CyJu6RvogyVotc4cRC0iVH8Iyns8/k8VCoVbDYb1Go18vk8qwUogJssgsSpqVSqNrcQSvgnipb0zaXfTglc5MCjkwOydAOVnuskdiqRSqViYwVlHykUClhbW8PBwQGsViuGhoZwcHCAYDCIS5cuweFwoFQqYWVlBVtbW0+V6UR7e3t49tlnMTAwAKPRiIGBASwvL3N+I51Oh1QqhVQqhUKhwMdJ4Z7NZjmhnBJIyU0acUIoLS4l8VB6rBdQUmqLjjcaDXg8Hjz//PPIZDLQ6/Vwu92oVCrY3NxEqVRCuVxmvRMA5qr8fj/W1taws7PDbgnpdJq5INoIDAYDBgcHUS6X23ZOAGzNo+Bisv6YTCY0Gg2kUinodDoGtN3dXSwtLUGr1WJ0dLRtYVNuLOm70jHSnajVasTjcfajs9lsmJqaQrPZxL1799BsNnH+/Hm2TImpXWKxGOLxOO/8J0+eRKVSwcbGBkqlEoaHh+H1erGwsMBARyqC7e1tfq+xsTEUi0VsbGwAAKeckQu/kqNOYPWzJDnxT/xf+rdIpIfzeDywWq1spaWiKlT0dmdnB1tbW3A4HJz22mw249atW13798QDlcfjwdLSElqtFlwuFzY2Nlg+Jp0U6aKoQKfZbOZgZJvNhnQ63VYlWRRRlLgqom7iYafrpNSJw5JeJ0404i7IOZJEG5VKhVAoxFwncVSZTAbRaBR+vx92u50To62srODkyZMwmUzweDycT0gsNxYKhdqCh6XvSha2ZrMJu93eFmIj1nkjxXUikWAFLOV7isVisFgsnI1UfA49i/Ry8XgcHo8HoVAIOzs7HE5ls9lQq9UwPz+PM2fOMEjSeKVSKZhMJgwNDWF+fh6Hh4fI5XIIBoPQ6XRYWVmBy+XC6OgoHA4HIpEIYrEYtFotvF4vRkdHsbKywnPn/PnzaLVaWFpaQjabPZZnuhyAdJo7vXBivbQlbrhKXD1x23fu3MHy8jKneBkfH2cjSTqdRiQSQTweBwBWE1DQei/0xAOVSqXi8Aqr1YpyuYzbt29z/mb6EFNTUwiFQuzvQU5rw8PDvMuSHkMkJd2S0t9yk0NKSrqLThOnW3tSBbXYDsXoUSyc2+3Giy++yBwKeYqrVEfWNZXqyIlxbW2N4+7oH3Fhch78BEqiUp0AgpLQAUcTeXBwkNOpGI1GbG9vsy4qEolw4rxu4hIVH3C5XG35kcbHx9FqtbC4uIharcYir0ql4j7GYjGOXyOrpcfjgV6vx/b2Nv/O5/M4ODjg8KCDgwM0m01sbGywEUelUuHg4IDdIaifvYCV9J2k6oVOc0ruXC8cmpwKQmyLOFyNRgOTyQS/3w+fz4dWq8We6GazGTMzM4hEIhw2Q/G0m5ubWF9f79oPoiceqA4ODnDx4kUEg0E4HA5MTk6i2WyiUCjwrkYTLRaLseL1ypUrbKYnzkqprlwnndTH0S/1eq1cn6TnRE9iUUkq6n4IKMjfidpqNptwuVyw2WycjP/cuXNIpVIcAiNNECdHrdZR4rnl5WV4vV7EYjGcPn2a48NIF0WgQO0ajUY4HA6sr69jd3cX6+vr8Hg8HALVarUeKRJAIiKJZeSwS4BBdQQLhQKmpqb4Hlp8g4ODbG3MZrPstU6caalU4pqQ8/Pz0Gg0mJychF6v59TNlC1CrVZzObaRkREGWGkkQrdv36tiXNqGqBDv9ozjkDj3PR4Ph8NotVqUy2UuiktjlkgkuOiFyWTC+fPnYTAYsLS01PVZTzxQeb1e7OzssEdyJBJhix4A9hTO5XLIZDJotY78aEqlEoLBIEwmE/b391n8EcUDEZiUOBy5HVO6Symx29K2jkvSXVvOx0lut6T7RF8flUrF7gg0rmQJpWdI3RPEcaJkdpOTk1hbW8P29jZngSyVSkgkEmg2m1zIgCY3Fajs6+uD0WiERqPhTAutVgtbW1sol8uYmZmRHYN6vc5+VQcHB1CpjhThg4ODqFar2NzcbBtvegfKHrG5uQm73Y5AIICtrS3s7u62pammTJ6Tk5Mwm83QarUIhUKcv8vtdmNpaQkrKyuYnp5mzlS6qfWqNJc736sOU/qNle7vBGrSNoiLXlxcxN7eHnNXY2NjMJvNXO5sf38fh4eHzD1rtVrkcjkcHBx07TvwDwCotFotl293uVzY3NzEgwcPkM1mOU2HWq1mZzSVSoVIJIKVlRUYDAYMDw+35QdvNptsalZSQH4cYBH/lpvQStRJMS9O0k59lN4v+o1RZkzxOhoHEZTk2hT7FggE0NfXx8puMmOTRzlxQjqdjj2cgaMN5eHDh/D5fOygSSljKNxJCvBk1Zufn0c8Hkc+n8fExAT7+NRqNWQymTbOhsaKLFPZbBanTp2Cz+dDs9nE/fv3odfrceLECVQqFV58GxsbLI7Oz8+jVCrhzJkzcDqduHXrFg4PD3FwcIB6vc6hPL1+W+lYiqqBTtyS3HGlOdUNMKXnqB0q/jE8PIwTJ06g2Tyq2DM7OwutVotTp04hk8mwgSoYDMJsNmN1dRUrKys9GxWeeKCikkihUIhTT9TrddjtdtbN5PN57O7uYmVlBcARGzs9Pc3OoIFAAC6XS1ZHpMT5iJOpmygoHu/Epf19ktKiUalUSCaTODg4YH1RvV5HIpHgFB/SPE9KFlE6J1rXSJwm/YZ4j9frZdHN7XZzhev+/n5YLBY0m02EQiHWI8rR2NgYdDodqtUqxsbGOBUJgWQoFGqLvSOiuTI6Ospe8n6/H1euXIFarea588Ybb7D1k5xiyWvd7XZDpVLh0qVLXFRCDJ+RjpEc9aJ/kmvjOBxaLyBF14lASdeTISSXy8HhcMBut2N4eBiBQAA+nw+pVAqZTAYPHjzgArFGoxEnT56EXq/HjRs3Oj4X+AcAVF6vF/Pz80in0wiFQtja2kIwGOR8zmRGLxQKbbtroVCA3+9HOBzG4eEhhoeH20zigDxI9apTkpKSAv3vi+REPTmgpbptOp2O379cLmNubg4WiwWHh4dwOp14/vnnEYlEkM1mOaUuAE5SSAVBRTFUqqcRny/G2NF1AwMDDG4kUp48ebIt46eUTCYTxsbG2r6PuOlIiwtQ+zqdri0igQpPkO6OXCQIjOiYWq1m5TmNo8/nYyAWuVTxPbuJW52AqJNYKNeW9LwSNy6nhpD2l66JRqNIp9MwGAxwOBwwGo1sOSWXBXICpgiHra0tpNNp2b5L6YkHqkqlgmAwCLfbjb6+PqyurrLTo8Ph4GRtJ0+e5JzYa2trbJGYnJxErVZrq9wiR3JK9cehXnUOcs85ruipJAaI70hZOakqDwDOiGqxWPDuu++iXC4DOEr7/PDhQ06Odnh4iIWFBfazIh+mRqOB2dlZNmFL3yGXyyGdTrNimgLLRYACwLGXSjo44COdE/lw0bvKxUDSoiTHXrKQEhckPotKyculaaHFLOrmpAUnxGdLv5sUHLp9Q/EeJUDrJO7JkdLzpWFOrdaRfxolpyRH3lu3bqFUKrW9/6lTpzjXVyKR4Mo1vdATD1SZTAanT5/muC8SAQuFAqcFicfj2NrawsbGBlqtFsf6UZWVUCjEO6J0cT+OnkH6t9LOdpx2u10vnfy9cG+kp9JqtRwSAoB9hd577z0cHBzgC1/4ArRaLU6ePIm9vT2+nxLeBQIB3L17F+FwGGazmYFgfn4eV69ebQMaymOfSCSQz+extraG1157DTs7O/zsvr4+DAwMcCaEw8NDBINBWc6KqrtQZgaqu7e/vw+DwcBcE/n69PX1wel0Ym9vD7FYDM1mE7VaDWfPnmVxkxafCJpKagFR1CUxV0l10G2zk4rGnb65ku6ql82tE0hK+0+WVcqQQGLd1NQUjEYjQqEQl6qbm5tDKpXC8PAwnE4nB5vfuXNH8XlETzxQ+Xw+PHz4EPF4HOPj49jb2+NqtrVaDfl8HmazGblcDslkksWdYrEIr9cLq9WKzc1NXLx48ZE8QqIuRk4fJaXj6CZ6ISXWXkmU65WkQCyNuyMlal9fH9bW1pBKpdjVgzISUGGHsbExOJ1ODtEhL/Dx8XGuBkQpXWjhU+6qWCyGUqnE4DY8PMxclkqlQjqdxsLCAmKxGF555RXZtLabm5tsWdra2sLFixeRSCQQiUQ47TGFVrVaLTx48ABnz57l8mj5fB7r6+uYmppqc5+QE1ulY6QEKNL/O4l1vXy3TmKj3LWPu/kpbaRGo5GND9vb2wiFQuyXRpklKBEipZKm9EmJRKKnPjzxQFWpVGA2mznDZyaTwdLSEkfXA0e7wuXLl+H3+9FoNHDv3j1sbGygUChgZmaGK/CSGCBOUhGglNhq6U7ZTTcg/VukxxErlXbXXkij0aBarSKdTnN9vlKphGbzqJArcFSNemBggEsjyQE4TVziKgwGA/umiRxVs9lkHUYsFuNsn4eHhyiXy7DZbOyYe/PmTWg0mrYCAaLOrdU6ikYIh8NQqVS4ffs24vE4CoUCTp8+jcPDQ2xvbyObzUKj0WB6ehpzc3NIp9MYHR1FKpXCwsIChoaGYLPZ2gwG3UTmxyEpcH2cOSDOx4/z/aVtSt+dIhK8Xi/6+vrg9XoRiUQwOzuLVCqFcDiM/v5+ZDIZLhBisVhQKBQQjUZZbdCNnnigymazOHv2LE+2mZkZGAwGlEoldkarVqsolUpYXV3lPFUvvPACp1YdHh5uU5rK7SzdlJtSEOpVzPs4op+cqNBLe2LfiHOKRCLw+XzQarUoFotYXFyEw+Fo0zOILgwk8sTjcajVag5PovY7hdk0m00Ui0WUy2V2D/H5fDAYDKjX6+w4SR7qmUwGyWQSGo0G6+vryOfzcDqdGBkZQSAQ4PzcpBBXqVTsmpLP55HP5zlFicPhYMVvpVJBKpViTq3V+igVTSeOqdO36cY9/SyBT0lU7EWf2uk4ibLS/haLReRyOXZXCIfD7GJitVoRiURw7949tgb29/djYGAADx8+7PouTzxQBYNBLvHkdrsRiUQwNTUFrVbLtcXIc7hYLLLpuVwuc1KvbDbbUQHabSfsZQIfV9nZqQ0piQpfOZI7TotSq9ViYmICuVyOwcfhcHCBB7fbjeHhYc6WSemKSR+4vLyMvb095qBoou/u7rZV9ZGmSaFc7FarlX1wjEYjarUabt26BZPJhOnpadZnkaWOCmGSn1K1WsXu7i42NjYwMDDAuzmJ+JQdgfpCWRUqlQoCgQBefvllzM/PI5VKwe/3PxIaJI6flFvu9r2O8y16OdbL83q5T+RK5Z4rghSF0GQyGezv77Mo7fP52I/NbDa3ZTc1m81oNBpc2agXeuKBqlKpwO12w+FwIBgMIhKJ4ObNm6jX67DZbCwanjx5Eh6PB81mE/v7+9jd3UU6nYbf72ePYyJabL06q3UiqT5ISt127V5ETPG64+o/CADEAqNarRbDw8MYHBxsE4f1ej37LTWbTQwMDKDVarGXP4EY1VYMh8NtWVOljpcAWNRcXV3l4hsq1ZF3eV9fH8rlMgfCispxamtlZQVLS0s4ffo0+vv7udDC/v4+kskklxXf3t6GwWBgV5StrS22VlFiODkRX6oY76SrehwOqRMHJkdyINpNd6p0vxJ3J4rWtBnY7XZMTEzA5/MhnU5jeXkZ+/v7sNvtGB8fRy6XQ19fH8bHx+FyuVCr1XB4ePjUPYGoUChwYGir1UJ/fz8vGK1Wi1KphEKhwAndiJM6c+YMDAYDqtUqnE4n3wM8Cipy3JXStdJz4v/Sv5UsMr2y7QSo4gLqZGHspU0RVMSdlc6LWQgI0ETgAI7SIF+4cIFDYqSB0uQ8SbsycXLLy8sMGuQyQGIFuY6IHE+tVsPy8jKi0Si8Xi+LkpSexWw2s2MvKebJ0LK3t4fd3V323xIV9XIbghSMerXQdeN0lDibXu6XO9atPemcE7+xuHnQJk1gXiwWEY1GuaBGMBiEx+PhFElUkXtxcRF2ux2Dg4Nwu924ePFiWzENJXrigcrr9WJ5eZnzXCcSCQ42peBScvzM5XJoNBo4ODjA/v4+xsbGuEpKt6RtdEy62xxXxyTXphIpgY3czi7+LTpbis/oRV+hJObSb9HHRgyEFp9NmSxEa6J0IRgMBubitFotTp8+jWq1yo6WpJwnEVOn07XpTwjErly5gkwmA6PRyBbDgYEBOJ1O6HQ6LhJx7tw55p7UajUGBwcRDAYZcEUfqE6LuBMQHFc/2Mt1j3O90nm5Pko5Kenmp1areQwpsJ/cQBqNBofPkBuDyWSC3W6HTqdDNBrF/v5+174D/wCA6uDggM3jNpsNCwsLbIr2eDzsE0POaBqNBolEApubm1xinNIVd5oQ0p31ZwFS0raPQ0riB00uOefIXiZ9J9GG2iD9lrRNupbASqVq9y2ia8S2ReCjuD9p1gHidqViGHAUWxgIBLhf1Ba5UxAR5yZydeQ2ITcG3cZI7EOv9/Qi5hFQiO/7OCKl3DOkG1a3+UBz/PDwEEajEZOTkxgZGUGxWMSDBw+wuLgIk8mEyclJFItFDA0NcREIytGfz+d76ucTD1QUU0SpWigdKuVQJ/QnKxDtqpSYnia1KPrJ0XEmJV3TjZM5LilxeXLiXi86sW7cnByJGRfE54ggTh7i0oUg1z850UrkmpT61E2U6gRASrq+XhdwN3GvE3UbE+BRoFa6v5tYSdcozQMl1YPUG584JlKMm0wmhEIheL1e+Hw+GI1GFItFpNNpvPvuuzCbzRgbG4PD4cCVK1cwPz/fdVyeeKAKBoPsZkBlu81mM2w2G0qlErOipPfQ6/Vt+dFJFBAzBRB1m4DddEziuV536eOQkgL0cUgJBKR/Sxez3KJRWgRKz5Xe00sf5Uj6HcRjcqEw0rZ7/Qa9imJ0bafNQRSppc/oJsb12helNjttpuL39Xq9MBqNiMfj2NjYgF6vh8/ng06nY46JkiZS3Uyj0YhIJMJVq7vREw9UKtWRcyHpJCg/utFohMFgQC6X44yOYgZKSt5fKBR40Km9XkBFeo2Us6FjSvfLLYxOHESnduSu7ZXrk1InkFFqU/oucroraX+lwCYeOw6oywEpiZTSd5IbT7lv1ou41U2M6/VbSudSL/ovpc2w0/PFtjv1VRQ9ab1kMhkukDI8PIx6vY779+/jwYMHnKGCMl1cunSJfRJzuRznG+tGTzxQbW9vI5PJcAzX4uIie8tS2ah4PI7NzU0AR2yr2+3mXYJq4RHL242UJoic+NVrO49DclxPLxNeqa3HFVOVJr+0XaXfSsDV6+KTgooSgPQCAEptyD1HvK4bKHQCLaU5pNSeHLA9jhTQ6bjInYtBx9lsFtvb2+zPdu7cOTidTpjNZtTrdeRyOdy+fRvNZhOTk5PQarWYmZnB7du3O/YJ+AcAVA6HA7FYDDqdDmNjYxxnFI/HWZEbCoUwNDQEk8kEnU6H/f19fPjhhwiHw3jhhRfaar7JcQFA+26ttKh71UspAQMd70U/0Y26cQVygCGd8McBOyX9TidRq1u/fpbUCwcrd1xJ9JX+luqLjjt2vVzfC3grcarH+Z7iO6lUKk4tTBELOp0OgUCAPf9brSMHXpJejEYjVKqjPGdiEHsneuKBqtVq4YUXXoDf70cwGEQoFMLc3Byy2SwX4HS5XJienuaSWJVKBSqVikNDqHhlp4ksB1jHAQ4RhH5WjqTddnSlBScCbq/cQ7e+SJ8hfVY30BQXx3F1bUp6oMfR5Uj70e1a6fXSZ8u1J8dFyvXhuKQ0fzttnp24N+DIV21/f5/Lyp06dQq1Wg3b29tYWFgAcLS+1Go1/H4/zp8/z+FK+Xy+5yKkTzxQFQoFpFIptuip1WpcunSJLUeHh4fIZDK4fv06c1jhcBjDw8OwWq2cn1tpgkmpkw5HOlF/FoAk93yl3504IrlJ2+0djwPCcnRcEViJO+mFlMSrXriQbiAq5aY7gZDcMx4HeLr1sRvX2gv32Ek8JRcXMbNpvV5HuVyGRqNhZ12z2QyHw4FGo4FyuYzl5WWUSiVMTExAo9FgZmbmqcMnALjdbqyvryObzcJgMCCVSrGivFKpoFwuQ6vVcllyAEilUvjwww9x4sQJPPfccxwSIi5ecbHKcSNSUtIVdNvlej0n97zHJTlQ7kXH1KkvvYpVvbT1s75HTv/STcyVA3kxo4Z4TSfdlRx3+LMS34/b3nGIFOqUm8zpdCKbzWJlZQXlchlerxcWi4XXg9FoRKFQQK1WY3+1Wq3GVaW70RMPVNFoFFNTUwiHw/B4PFhbW8N7772Her0Oh8OBarUKn8+HsbExdu6k9KlUWNNgMDxSmbcbCy8nCookPdbLjq80oY8rism19TjUC3fZK/UKeB+n393628u1SpuSFHy6ibty1OsGIQeiHxeMjsshE0fVarWQTqeRz+fhcDgwMjICANjf38e9e/eQz+cRCoVgtVo5M6zZbIbL5cLu7i62t7d7euYTD1SUoZHKtdtsNjzzzDPMlqZSKaTTady/f5/9p/r6+tDX18dJ/YlE9h541MdFyvYrTaJeJrfc352omx6mE0fzswCtbn3r9ZwSMDwOV/S4/etFHFR6dq/cUaeNqNO379a3TsDWTYSV65+SekAupCyXy2F7exv1eh0ajQYnTpzgmowUV7uzs4NYLIZLly6xt3ov9MQDVTgcZgtff38/crkc56PK5XIolUqwWCzo7++H1WpFo9HA/v4+ZmdnMTY2htOnT0Ov1yum95DmJhKBTC5vjxx3pSQWKp2XHpcq8EXqJLbJ9ec4Ysdxru/Uvpw4rXRe7vfHeXYv5zpRJyA9Tr+V3kU6d7q10wmkO3GUcuMuVW2I7VIYlFar5XQ82WwWsVgMuVwOTqcTer2eEx5aLBbk83lOsmez2ZDP5xGNRmX7KqUnHqjy+TxmZmYQCARgNptRLBbx8OFDFAoFmEwmtFpHWSApR06tVoPRaMTg4CBsNhsAcBoToP0jEydVLpeRzWZhNBrbSkdJOTDgeKKAEkknjxJYyYFRJ32J0gSWPrNTv3tVUh8XEKV/dwKp4+ptjmscEO9XGp9uYHocsU7sZy+iXi9td+qj3PyRnhOliL29Pezt7SEUCmFkZISL9t66dQvpdBq1Wg1Op5MLzFKtzXK5zLnwu9ETD1SlUgkLCwvY3d2F1+tFLpfDhQsXOHFeNptFNpvF4uIi8vk8TCYTBgcH4fF4uKCBUmFNlUqFUqmE69evY2VlBSqVCufPn8fMzAwODw9hMBhgsVg4CJNIOtGU2GvxfDe9RzfqVUGsBGpy/ZGOh7TdjwNkx6XHHRs5sa1bPz4uFykHar2Cy8d5Zi/39LIB0HqgxIo+nw+BQAD1eh3b29ttOd6oyjQALqCxuLiIV155hWtm9kJPPFD5fD5kMhkAR5H0hUIB2WyWMzpSVkrK+V2pVBCNRrGysoJLly7h+eef52KVch9Ro9HA4/EgFAqhWq3i9u3b8Pl8XJHZbrfj/PnzmJ6eZsdR4KPFLi0N3wnExGPSJHPdduJOpKSfEEkUY0Wg6iSmSs+J6UHkntfrouwVjHoRg+Tu6eV4Jy6sF6A/bn/l+tDLd5O7Tum50g1I6T4x+0Wz2eR6BMlkkoukUJrvjY0NOBwOuFwuHB4eol6vt5V039jY6Ng3oiceqPb393HhwgX09fXBarUiGo1ytLbdbueqyeFwGC6XC9VqFUajEZVKhauOiFkogfaJqNfrcfbsWS6ttba2BqPRiJdffhnVahXNZhMej+eRggetVgs7OztcUogKoXbygqc+aDQa1Ov1R/RmvQBWN5Gh04KSm8jiJO9Ej8MFPs79SjoV6TWd7u/0TOn7dxKHuwGPeH0vIp3cM3rpe6+icK9j3Gq1OP98s9lEJBLB5uYmO05rNBocHBxga2uLnUH1ej27AYXDYXi9Xs6/3ws98UBFdfvK5TIcDgesVitefvllzi6ZTqeRyWSwuLiIQqGAVqvFJeApcRuRkr5ErVajWCzi1q1b2Nvb4x3DYrHA5XJhdHT0kWorarUac3NzyOfz+OIXv8hlrV944QU2/UpzRtEza7XaI1YXom4iYielqdI90mt7fYZUGSsnHorH5dqh871yD71yJEoLs5vOrhc6ro7scXRjvV53nA2i26Yj991araMAfsrkaTabYTAYoNfr2V8xkUjAYrFw6mpaL1QEohd64oEqEAjg4OAAkUgEMzMzyGazrHeqVCps9QuHw1Cr1ajX60gmk1hcXMTVq1c5fEZaHgv46EMlEgn8+Mc/xubmJl588UXY7Xa0Wi3k83n09fXxtXQ96atqtRru3r2L06dP45133sHFixcBfCTakae86AVMIT6Li4s4c+YMc1VKoomUlEDiuFyRKH6KfyvpvqRj2ElE7PX5cu+gdEzuWb2AnxyHdtzF36lNuf5242o7jVcvG0Av9yqRdFwpKJmcpUulEq8j2qwPDw+50pNKpeLirZSRpBd64oEqFothenoafr8fFosF0WgUi4uLPIjlchk+nw/BYBBms5nLZQUCgbYYPzk9ikqlQjQaxd/8zd9Ao9Hgl37plzA2NsbXl8tlFhvFTJXARwtdr9fjL//yL1GpVKDVarG7u4vd3V3O4hAMBpHP5zn9rl6vR71ex8rKCiYnJ9n7V+wTtS8uLDmvaeqnHAhL9VBSgCHOULp4pWlqRc5PbEM6nt30Od04N/EaOSB8XO5IbE/an164ok4i1cfl2LqBYC/A002UlSMaT/onhs+USiUYDAaYzWYcHh4im83CYrFAq9WiXC6jXC5jb28PwWAQer0ea2trPb3zEw9UVFuuVCrBarXCZDLhlVde4bCYTCaDw8ND3L17l0v6nDx5EsFgkFMTUxI9OcdOqqTr8XiwtbUFm80Gv9/P19GuISqjaQFrtVq8+uqryGQyDFTXr18HAFitVty4cQMvv/wy7t69i1gsBqPRiPHxcUxMTCAajeLOnTsIBoMIBAJc1Zc86Q0GAwC0cXDShUW/q9UqNjY2YDabuVhnq9XC/v4+i6/0DpQBlUiacI7+iaKu+Gyp6CjH6XTSjfUqAtI5JfFYpE6iqNK1H1fP1WnzO05bH4c6cWtKYy73/rRZ7u7uYn9/H7VaDfV6HW63GwMDA5xdIZ1OY3NzE3t7e2g0GrBarahUKj319YkHKr/fj0QigVQqhcnJSVSrVWQyGbRaR6knisUibDYbBgYGYDAYuNbY1tYWXn/9dVitVlSr1UecPulDDg0N4Xd+53dweHiIw8NDLC0twWazQafTwWQycXUUqbhIk2BsbAz9/f344IMP0Gg0cHh4yOCYz+eRTqfZ6lgqlbC4uAij0Qi1Wo1sNotoNAqbzYZTp07h/v37XABhZmYGJpMJ2WwWNpsNdrudo9ilXFQ6ncb3v/99DAwMwO/3Q6PRYHV1FW+//TaeffZZXLlyBa1WC8vLy1hbW8PVq1fh8XhQLBYRiUTQbDbZT02lUrXFc4n/pCQFLSIpcEgXkFw70gUk5Rh7oV4AqJe+iNd3ulacC93EuV761YmO86xuJB1jqkdAm2+9XuditMlkEoeHhwgEAlxYo7+/n6tBPQWq/5eKxSIuXrzIQcc3btzA/fv3WexqNBowm82cAZSS+vv9fmZpKXuCVIHdah1Z/U6cOMFcBJluAeDUqVMwmUyPFNek/0lMorLp1N7g4CAsFguGhobg9XoRj8cxMjICjUaDQqGASqWCyclJvPzyy4jFYrhx4wY2NzdxcHCAyclJbG1tYWFhARqNBrOzs/zuL7zwAkZHR7nv9L/L5cLY2Bj3yWAwoK+vj62VtOByuRyWlpYwMzMDl8uF2dlZ3L59m72TP/3pT8NoNGJ+fp4rFatUKg6dsFqt6Ovra/Mpo02AxlVaIYf0HVIupFKp8ObRarW4qpDJZGoTr8VnKZHIORyHY+tVVKJrqb3jiHxKolk3cO/UTi9gKwU16WYg3pdKpbCxsQGn0wmXy4WhoSE0Gg0sLS1hZWWFvw/VJzAajeymYDKZehqHJx6o6vU6tra2EI/H4XK5YLFY8Prrr3MCvVQqhVwuh+vXr6NUKgE44nJ8Ph/nUqcFLH4gaT06Eg1FrmtwcPARDoqISjJR4DMlE6MMDzqdjjkn4s6AI2VlrVZjMVWn0zH3lUqlEIlEUKvV4Pf7kcvl8Nprr+HSpUtco07sL4EnZWSkasitVosLttJC12g0mJycxObmJr9TIpGAx+PB1atX8b3vfQ9ra2sIh8O4efMmRkdHMTIygkajgdu3b+Pu3bvQarX41Kc+hdHRUTSbTczNzWFtbQ0vv/wyPB4P8vk85ufn0Wg0cPHiReh0OmSzWdy4cQN+vx9nzpxBvV7Hzs4O5ufncebMGQSDQcRiMSwvL6NarWJ6eho+nw83b95EuVzGSy+9xHpCIrlvclw9Vic9Uafj3c6JfemFA6K+iPcocX5SsOqlD3J9lj7D4XCgr68PpVIJiUQCkUiEi/devXoVLpeLdVQHBweYn5+HVqvFc889x2uuGz3xQGWz2ZBOp1kHlEqlEI1G0Wg0UK/XUa1W4ff7cfr0abZQUH2y4eFhWdFFWruOAErOZYAmhJSb0mg0OHXqFFSqI7+o06dPo9VqIRQKYXNzk5P3GY1G+Hw+hMNh1Ot19jvZ2NjAnTt3UK1WUalUYDQa4fV6cfbsWWg0GuZ47HY7TCYTxsbGuK9ShatoUSSOplarodVqtdWzU6vV7NZBjq7Uh2KxyF7IZ86c4bxEe3t72NjYwPPPP49IJIIHDx6gr68Pi4uL+P73v49SqcQT9s6dO/j2t7+NsbExnDt3Dvl8Hj/84Q/x7rvv4vXXX8f09DQikQjeeust7O/vY2RkBBaLBR9++CF0Oh3Onz8Pt9uNer2O3d1dlEqlNmAGenOF6ES9LHCl648Lhp3aVNKp9dIPud9K90rHRW7DpX+0uZpMJlSrVVSrVczPz6NSqSAQCMBkMiGfzyMcDsPpdMJms/U8Hk88UJXLZTz77LNwOp1QqVR48OAB1tfXodFooNPpGBCooKVWq2U9DaV3UfrorVYLq6uryGQysFgs8Hq9cLvdXA9OTmEsgpVer2dgoI/mdDoxMDDQZj2z2WzMcVH+aavVinK5jGq1isnJSVitViQSCV60Fy9e5Mo60r6Lk01aKFTkukgcFQGYHE1rtRoikQg8Hg+0Wi0ymQyDrs1mQ7FYhEql4pjK06dPw+Fw4L333sPs7Cx++tOfYnJyEoeHh2g0Grh37x5u376NoaEhtFpHFtPvfve7SCQSmJqagkp1FFP2zW9+ExaLBaFQCPV6Hevr64hGo3j11VfhcDhgNBqh1Wpx7tw53Lt3rw2k6P2l30P6XYmUdEydxCY5Oo44KX4jcZ51Eu0e57jIhYnHxP526qe46cXjcaysrMDtdrPKYmxsDDs7O4hGoygWi6hWqzCZTDCbzXC73dBoNDCZTHA4HB3HguiJByq1Wo35+XnodDp2SnvuuecAgH2myuUy7t27x1VdR0dH20poiSED4sdsNBrY2tpCJpOB3W7H9vY2xsbGMDk5KcsqS0UOKVsvpxsAwIU3AXAFD7/fz2BCOhkKESqXy3C73TCZTKwPkBoCiGgRU1yilNsSdWutVosrFRPX9eyzz+LkyZN46623kE6nAYAri4i6I9ppydIajUYZyHZ2drC1tYVCoQCDwYBYLIZ4PI79/X0WcSnqPhqNIhwOI5fLYWdnB61WC7FYDKurq5ibm8O5c+cwNTXF+sZOopn4LUS9VifOR0kcUqLj6LEe995OHJD0GjlgPg6XJ262ADjAeGRkBIVCAYlEAtVqFbu7u/D7/ZiamuK42WazicPDQzx48IC91akWYDd64oEKOFKoU+npSCSCbDbL58rlMlsiQqEQkskk1tbWYLFYcPnyZZ7wonuCVEY/e/YsJicnUalU2ixM4vVK1E1UkIIWhS7QYhLDe5xOJ0ept1otWK3WNtFHujOL7Y6OjjJ3Sf0eHR3l0uvA0aQkBShd99577yGXyyESieDEiRMAwKFDGo0GFosFiUQC8Xgcu7u7aDabuHLlCk6fPo1YLIbvfOc7cDgcuHjxIoLBILa2tpDL5eBwOPDJT34S5XIZ7733HjweDyYnJ2E0GlEqlfCjH/0IPp8PsVgMFy9exPPPP4933nkHm5ubzIGJgNmN5HRBchvJ44huj0viJvG49yspy+XATTpflTgr6XGdTgebzdYmAbRaLRQKBSSTSaysrCAQCMBms3EcYF9fH8xmc9fCvkRPPFC1Wi1cvnwZDocDJpMJ6+vrWFhYwP7+Psf59ff3Y2BggH09Dg4O2GlN1EHJcUbpdBrNZhN+vx8mk6nNf+m4E11ughD3UqlU2oqhitdK9U3irke118QJL9cn4r7oepVKhdHRUahUKr7faDTiwoULMBgM0Gq1ePHFF/Huu+9ifX2dy3WTXstoNDIXZLfb8fWvfx3lchkXL15kVwmKsaRcYKOjo3A4HNDr9fB4PHA6ndBqtTg4OGAHWKfTiWq1iocPH6K/vx+pVIpF1EKhwCIyJUyUjqd0vKXn5EQhuXu7fcNO1KvoKAcQnXRNSqKq9Fql6zrdIzd3aX6l02nMz8+ztbivr4+t1ffu3UMymWRRT6/XIxAIsOpFGqamRE88UAUCAVQqFcRiMWi1Wuh0OkxOTrKPksfjgV6vR7lc5gyFsVgMdrsdV65cYcUxhbMAH0WPA0cOnwcHB0ilUhgeHuZ7pBOdSLo4lMBLZK83Nzdx7949XL16FYFAANVqlZPke71ehMNhLqtNQdXUZ6n4I8el0TvRtaJOSgrUwWAQwBFn5/f78eabb7a5MLRaLYyNjaFWq6FWq8FiseDVV1/FvXv34Ha7cf78eRanKd+2mL/LbDa3hR0BR+KuzWZDvV5nzjAcDnNKntnZWbYqjo+Ps6g5MDDQNp5yf0vHvNP3kvt+Yj+VSA4ExfGSfpNOf4u/xUKg1L7S9xUBR+5/pfeQUwVI38ftdmN0dBSFQgH5fB7JZBL7+/tcvMFkMnGqo3Q6jY2NDWxvb+PkyZO8sXejJx6o9Hp9m1KcMhDSIi6VSgxCpASnog/kHiAV+8R8PAaDAS+99BLn4yFuR/pBlSYzTT6pNU60DqpUKuzv76NarUKr1WJhYQG3b9+G3+/HBx98gFdffRUTExO4d+8eDg8P8dprr3F9wrt370KtVuPEiRMYGRnhSiBarRYTExMwGAzIZDJsEKC0saSPIgU5iZxSXRf5mInA7HA4+J0ajQYGBgYQCASgUqnarIhmsxmvvvpqW/qb/v7+Ns9+ADh9+jQXuVSpVNDr9Xj22WdhsVgwPj7O4AmAOTnSRypVZVYiuYXbiROTOy8lJX0R3SunIpDOAxGA6H4CeJqf9I2kfezEhclRL+8jtm0wGOByudBqtVAsFjmFS6PRQC6XQ6VSgcPhgN/vRywWAwD09fVxzYJe6IkHqsPDQ+j1es5oQOlbgsEgqtUqYrEY7t69C+AI1AqFAsLhMHuq00SiiUAfUeSocrkcxxKKuiC53a3TpKXf4kRpNpsYGBhAKBRi58fBwUH09/fD5XLh29/+NiKRCMbHx5FOp7G+vo5r166h1WphZWUFTqcTGo0G3/rWt/CFL3wB29vb2NjYQLFYRKVSwcjICL73ve+h2WyiUCjg2WefxfT0NDY2NjA/P4+ZmRkMDQ219VMEbin3KNWh0XFpyTHi3CjLKv0Ww3/oWaQTo3sbjQaXYGq12nVx1A7pJOl7dOMcpNSL7lB6Tkn/p9Q+cea1Wg0ajYbnWL1e5+uIoxfbpwgGClXRarVwu92oVqvI5/NQqVSw2+1cl7IXUupvpw2WxrtYLOL27duoVqvo7++H3W7HK6+8go2NDdy7dw97e3vo6+vjrAkDAwNwu93w+XzI5/M99e+JBypyDgyFQggGgxxK4/V6USqVYLfbkcvlkEgkWMlO4SnijkUfRgQstVqN/v5+rKysYGFhAQ6HA1euXIHf72/b3XpRqktJvFbqmU1FJw4PD5FIJNDX1wedToepqSlUq1XmXC5cuACLxYJKpYL19XVEIhEsLCzg1Vdf5cml1WoRiUTwmc98BktLS7h//z5sNhs++OADlMtlfP/738cXvvAFuN3utl0eANbX17G9vQ273Y7x8XHo9Xr2DgfAxTKAjxamdOITZyu3wOUUySL3Jt0A6J/oUiJyv9LxFdumby0CrZIiW9pXKUfZ6XqpyBWPxzE3N4epqSmEQiGsrq7i/v370Ov1yGQymJycxPnz5zkUCzgyVqyvr6NSqSAej+Pg4ABXr17F8vIyc7kWiwXXrl3r6PmtpGzvJgJKr9PpdHC5XKjVagyWxWIR+XweQ0NDmJiYgNPphNFoRLFYRDqdxurqKifU64WeeKCi4GKz2QybzYZEIoFbt25BpfrITygcDuPs2bOw2WyIxWLY3t5GMpkE8KjvE/CREtFgMODll1/m1Cu1Wg1ms/kRFp3a6URSMVGc0KL4QmLY9vY2fvzjH6NarXKJIgDsl9JsNmGz2ZDJZPDuu++yMp5Y8Gq1inv37nG6mw8//BC5XA5DQ0PY2tqC0+nEtWvX8O1vf5uznYpB2dlsFu+++y60Wi22trawubmJiYkJFAoFnD9/HsVikZMI2mw29Pf3Y21tjfVTHo8HbrcbsVgMer0eTqezbayy2Sy2trZQLBah0Wg4DrFcLiMajcLlcrEzbzwe58onbrcbh4eHnHHC4XAgEAggk8lwXiS3241isYi9vT1WuIfDYWg0GqytraHVOvJrO3HiBFs9u3HCvZJU7ItEIrhx4wbcbjdCoRBqtRpCoRCcTie+9a1vsTuKCLRUdoqC2HO5HLf7+uuvo1Qq4f333+cURgSiUsCUgmYnrqrTtXa7HRMTE8hkMmxcophZq9XKTsoejwflcplzUVksljbXm070My/V++d//ue4fPkyZxH4/Oc/j6WlpbZrWq0W/vW//tcIhUIwmUx4+eWXMTc313ZNpVLB7//+73Mhw8997nPY3d09dn9qtRouXLiAq1evYmhoiNNLaDSaNqUz7U71eh0jIyO4fPnyI6Xc5RTQFJDp9XrR19cHk8nEu7L4cTvtuOK4SLkFEvcIpJrNJtbX1/HWW2/BbDbjC1/4AsfUkZc6tbWxscFi3ec+9zm4XC626pFuIJFIQKPRwG63syc36XjIKke+TKKeh0To119/HZ///OcRDAZRLBZRLBbRarVQKpWwt7eHzc1N7OzsYHl5Gbdv32ZO7ic/+QlKpRKWl5exubnJfRYrWN+5c4ezpv7kJz9BLBbDO++8g2984xt46623EI1G0Ww2sbu7y+XO6P6HDx/i+vXrSCQSqNfryGaz+PDDD7G+vo5Go4G9vT3EYjF4PB6Ew2EYDAY8fPgQKpUKoVAIBwcHiMfjbd9F6XvJzQ2RxE1LvE6j0WB8fBxTU1PMBY6Pj+PkyZO4d+8edDodnnvuOc71JG5aNpsN1WoV8XgcZ86cgdfrRSaT4cDxRCLBsadiOp7jAqy4OSm9G+VHW19fR71eh9FoxMWLF3HlyhX+jg8fPsTW1ha2trag0WgwOjqKgYEBNpx0o585R/WTn/wEv/d7v4fLly+jXq/jj//4j/HGG29gfn6eF/6/+3f/Dv/+3/97/Pf//t8xOTmJP/3TP8UnPvEJzjwAAH/wB3+At956C1/96lfh8Xjwh3/4h3jzzTdx+/btngJNier1Om7cuMHZPQ0GA65cucJpUGOxGLLZLJaWllAul6FWqzE2NsYsqei5DSj728jpQI7LVUnbF8UlynxQrVZx9+5drK2tIRAIsHXF6XRy5s9ms4lUKoXvfve7yOVy+NznPgez2Qy1Wo1yucw6KuBIjBgaGsJrr72GQCCA3d1d1pHI6WVEPQkFI9tsNly5cgXz8/NYXV3F/v4+MpkM75wLCwvQ6XQYGxvD0NAQ7t69iwcPHmBmZoatgyLHSgvS7Xbj0qVLODg4wK1bt3D//n1EIhG8/vrrmJ2dxcrKCq5du4aRkRG0Wi2uI0f+cPl8nq2wZrMZW1tbnBZneXkZTqeTfa5KpRKKxSLMZjOGh4c5kFvkpjspqJVIznonHtfpdMxVtFot9hOj3P6ZTIbnoqjL02g0iEajqFQqGB0d5ZTY2WyWQbhXA0I3/ZRUkU9jolKpeFO2Wq0AwCWwms0mNjY24PV6WW9lNpuRy+Wwu7uLGzduwGAwtFlmO9HPHKi+853vtP3+i7/4C/j9fty+fRsvvvgiWq0W/sN/+A/44z/+Y/zSL/0SAOB//I//gUAggK985Sv47d/+bWQyGfy3//bf8OUvfxmvv/46AOB//s//iYGBAXz/+9/HJz/5yUeeW6lU2lJGkL6JlLjkw7Gzs8OhFUQjIyN49tlnYbVacXBwwJ7SxHUogQ0lATMYDPwhDAaD7IeXAzixTemOJy5ak8mE8+fPw2g0Qq/X49q1axgcHOQ0NaVSCU6nE16vFzqdDlqtFnq9HuPj44hGo5idncX+/j7OnTuHiYkJ3LhxA1qtFufPn4dWq8Xq6iru3LmDaDTK4tPm5iY2Nzexv7+P4eHhNl0TcXkAeNcm3d329jYHE1M16rt372JychInTpxglt/j8eD+/fssGkrBvdlsYnNzE1arlYsCVKtVjicMh8PMARKg6HQ6HkutVsthUSLgE+dSLpexsLCAYrEIt9uN06dPY3h4GLOzs0gmkxgcHMTU1NQj4VBK301JWS8FN+n3Ja970V/OZDLhl3/5l/GTn/wEt2/fRn9/P1vULBYLjz9V9aa5TfGRe3t7bNw5Tj+l6odO14tZLlQqFfr6+lCpVLC3t8fAns1modVqkUwm22JnbTYbrFYrXC4XA1w3+nvXUVEFGLfbDeAomDYajeKNN97ga8jE//777+O3f/u3cfv2bdRqtbZrQqEQpqen8f7778sC1Z//+Z/jT/7kT2T7cOnSJXg8HhYNxHxJxEWRF61KpcLIyAj8fj8PorijEKlUKhwcHODdd9+F1+uFSnXkA3ThwgV4PJ42x0tR0SsXHCvlouiYqBMjTrPVasHv93MIjSguUqAnxdu9/PLLbUp9AicqURQKhQCAQx/MZjNOnToFh8OB1dVV/M3f/A3cbjeGh4cfMQi0Wi3kcjkUCgUWRyuVCqanp/Hqq69iZWUFs7Oz0Gg0GB4eRrlcxv7+PiYmJqDVanHp0iUsLCwgmUzitddek10cZNEaHByEz+fD3NwcZmdnUa1Wsb+/j8HBQQBo+6Zi/8iwQFZbkVNUq9Xwer0YHh6G1WqF2WzGxYsXcfLkSWxubuLdd9+F3W7H5OTkI5kzRFJSC0hJOn9EUBA3RDJ6kC8aqSeWl5cxOzuL119/HQ6Hg4OAxYD4ubk53Lx5E8ViEZ/97Gd505QaEpT6JD1HfVICK+AjK+/q6ipSqRScTifMZjOXcb9z5w5WVlZgMBjgdDo5gN7v90OtVrfpJjvR3ytQtVotfOlLX8ILL7yA6elpAODKqNJ6XoFAAFtbW3yNXq9/xCIQCAQUK6v+0R/9Eb70pS/x72w2i4GBAej1ety8eRMWi4VN9ZcvX0aj0UCpVEImk0G5XMb8/DzK5TLMZjO8Xi+z4zQJ5Cw99XodHo8HL7zwAu/eYniJ3Hj0MmZS7kKqxBedT6UTR+pbQ46gYoS7NKH+5cuX+R4yh3/xi19EPB6HxWKBz+drA9hWq8UBwN/73veYYw2FQswxUX4vo9GIZ599FoVCAe+88w6cTidXrVapVPjrv/5r9qOSgvTIyAieeeYZ5pjW19fx3HPP4cqVK7h58yYKhUIbEIljTJlIxbjEbDaLarXKjqOUygY4ElkePHgAt9vNnLHoyCql4+h65Kxl4jHSwzabTZjNZhwcHCCTyUCj0eC5555jr27y1Kd5ICYrpI3qk5/8JG+y5L4grSkp1wclKUBOAS/VoWo0GgSDQeakDw4O4Pf7cffuXeh0Oly7do11noVCAZFIBLdu3UKxWMSzzz7b0xj+vQLVv/gX/wL379/Hu++++8g5OT3PcXclkaT+N0T1ep0rYhiNRqysrOD+/fusRG80GhgfH2cDQCaTwcLCAg4ODhgQRMCQyucbGxswGAwIBAKYmJjghaFk2j6uMpPuEScIKdWlC5sClMWEcqIrhWh6F++j9xFDbsjrm55F99F7U16vWCyGarWKUCiERqOBZDLJuhZSUjudTvT19aFeryMejzOYnTx5EidOnODUxtIFQA634vvbbDa4XC6EQiFEIhHulyiikehHVYVqtRoePHiARCKBnZ0dNuKsra3h3Xff5fTTtVoNN27cYMug3++XFckf9xvK/VapVDh9+jRX6g6FQvjUpz7FflV0vL+/H8FgsG1ekeWTvsvg4CCDNnFpUn2udOMjktNHiiRyqtJNpdlswufzcZEHk8nEOdJsNhsqlQoKhQL6+/vRaDRQLBY5RK1XffPfG1D9/u//Pr7xjW/gpz/9Kfr7+/k4afmj0WibR3EsFmMuq6+vD9VqFalUqo2risViuHr16rH6oVKpMD09DbvdzvqUg4MDtkxRCopIJILd3V3+4OPj422TQEqktKZsAIVCAV6vF1ar9ZFMn4Cy7003Eq8R/xb9g1QqFTKZDD788EOEw2HMzMxw7T/yEfN6vXA6nWi1jjIaUDVb6qNo1RMVpmIWUqnRwOVyMetO1/p8PrRaLXg8Hly5coU5G4PBgE984hNoNpuYmJjghP+/9Eu/xPUVCQRVKhWCwSBPeBrnmZkZHr/+/n4Ov/F4PCzmEPc4OTnJwKzRaNDf3w+n08kLZGZmBv39/cw52Ww2DA4O4plnnmHQJmubko5S/N2rcl0cQxpj0aVErVazyoE2Ghpf8RsQWFCWWvpmUlcKOWDtpm+T/pbOQfH5KtVRYPze3h4WFhY4dQuN8dzcHBYXF1kPp1IdOYiOj4/D6XT+30vz0mq18Pu///v4u7/7O/z4xz9u8/EBjhTXfX19ePvtt3H+/HkAR5ann/zkJ/i3//bfAgBnd3z77bfxq7/6qwCASCSChw8f4t/9u393rP5Uq1W8//77sNvtPKFnZmZY2UfhI+vr621WH8p2KX038cNT8ruXX34ZrVarLT96J2dFOZ1Xp/GULhTphCLRq1gsIpVKcWrjhYUFXL9+HdFoFP/oH/0jOJ1OpNNprKysYGNjA2+++Sb0ej0WFxeRTqcxOTnJXIRKpeLkebSrS7lKAgXgI4dKem/i7Gicms0mpxwWxWPSk4mpaFqtFnOpBJQUF0jPtdvtsNvtAMB5jmg8ms0m++iQs2woFGrbJOga8ZsSIBN4i4tRqueRbjjHBSyxH2KcpfS70/90DbVPrijEvZI/HKkGGo0G64Xl9H9K/RHfSY7EDVe0iFMYjU6nYyNPq9WCz+eDXq+HXq9nX7V8Po9sNou1tTVMTk72NFY/c6D6vd/7PXzlK1/B17/+ddhsNtYpUfYClUqFP/iDP8Cf/dmfYWJiAhMTE/izP/szmM1m/Nqv/Rpf+0//6T/FH/7hH7Jj4L/8l/8SMzMzbAXslYhrIOvf0tISrl+/DqPRyArYgYEBXL58mXMhbW1tsS5AJCloVCoVjmWid5NyUZ3ASEk0lNMdiMflxBASV4hDiEQi+P73v4/p6WmUy2UAR1Wj/+7v/g71eh2Hh4d44403sL6+zpalb3zjG/iFX/gFeL1e7O7uYn5+Hi6XC88//3zbglWpVFwTkbhOqn5DDpQEPGKspHThibo0UR8kitzAR9yrFBTklNx0n6g8F4Ot6ft0Es3F/nZbvHJcR6dvLc6HRqOBzc1NJBIJaLVaDA8Pw+l0cobZ8fFxttyJ3/v/x957BEeWZefBX3rvkJlAwntvC4Xy3nRNu+me6Z4hgxyGyAhFaCHtteZOSy0YCgWDC0qKUFBUiOrpmZ421d3V5Q2AQsF7n3AJZCK9d/8CPKdvvsoEavjzD/0qzolAAMh8+fK9d+8995jvfCeVSuH58+eIx+MMs+nt7cXm5iYSiQTm5+dhMBjwx3/8x5yEeZNrPO5axe+n18VYaU1NDQwGA2MRk8kkVlZWIJPJ4HQ62WKm5g9UwvV/rLnDf/7P/xkAcP369YLX//Zv/xZ/8Rd/AQD49//+3yMej+Pf/tt/C7/fj3PnzuHu3bsFD/U//sf/CKVSiT/6oz9CPB7HrVu38F/+y3/5vTBUwBGE4MyZMygrK2OGBMr00U5PrbMSiQRkMhna2trQ2Nj4WsyLJitZEhqNBh6PB1988QW0Wi2am5tx+vTp1ywv+myxc0nlTZSbuHhICLRqNpu52Jq64uzs7GBvb4+7gly8eBGvXr1itoiuri4MDg7C7/djaWkJ09PTmJ6eRjqdRktLCy9wcQLv7OxgZ2cH/f39mJqaYsW+tbUFm80GrVbLcand3V1GidfW1sJoNCIUCiGfz3MBs6gIyWqiejZCrqvVaiSTScRiMa7vIyuYPk8K1GKxQCY7IuYzGAzMjU+F136/n2ElHo8HSqUSVqu1ZNym2Bj+U4XOQ9xnFosFbrcbu7u7uH79qGHH8+fPUVFRAaPRWGDR0diura1hcHAQDocD33//PTKZDFM6U+2n2POxmEItNj+LuX+l5jGNk0wmg9frxcLCApRKJVwuF0wmE7q7u7G2toaRkRFEIhHmfPN6vWhoaEBLS8v/WdfvJJHJZPjLv/xL/OVf/mXJY7RaLf7qr/4Kf/VXf/X/+nqePHnCE7SsrAydnZ08qSnDMjo6yi5HfX19UTyUuJMDQH19PX7xi19wLEitVjPDAVkS/9TJXWpCSUXqjul0OmQyGdTU1ODnP/85Dg4OsLe3h0wmwy23x8fH2f2j7JFWq0VjYyOSySRmZmZ4spErIbI5yOVyRCIRLC4uYn9/H7FYDDdv3sTU1BR0Oh1qamqQyWS4wWsgEMDCwgIuX77MfRCnpqYQiUTQ09ODM2fOcHEycLQACN6g1+u5PrO6uhozMzNYW1tDc3Mzurq6sLm5ib6+PrY8fD4fvv76a1y/fh3xeBwjIyMYGBjAwsICDAYD0uk0ampq2Pr4+OOPsbq6ytguka3gn1OKna+srAxXr16FSqXCs2fPsLm5yXCM2dnZ1yxHOg+59rOzs9Bqtdjd3eUg9tzcHJRKJccpS4nUovx9XFY6np6TUqlksHE+f0QjTTAEs9nMHY4cDgdMJhPPi7W1tddCQ6Xkra/1ozQtEXRtbm5ySQ8FlltaWjh47vF4sLGxwTVLpdwtCiK6XK6CHU8M/paa7CcpHvotNbWLfU6cYKRQKM09ODiIRCLBxa2VlZVobW3Fzs4O7t27h6qqKq6Lo2yMSqVCbW0t3G43pqenYbFYcPHiRTgcjoLrSafTmJiYgMvlwi9/+UuUl5ezwk6lUuyyKxQKroPs7e1FNBrF3Nwczp8/j3w+jx9++IHLKcS4zMHBAYLBIM6dO8cB45cvX0Imk+HixYt4/vw5W7cUh6Js19zcHA4ODpjulvBlly9fxvT0NLa2tuD3+zE3N4fGxkak02lOgJwUfJaOSTE36U0XPW1oq6urWFxcRFtbGzQaDYcSRAodOm8ul4PRaMS1a9ewv7+PYDDI8y2bzSIQCKCxsbGgiLzYHCt2vaVcvmLPga6LFFRZWRl6e3sRDAYRiUS4JpMoibVaLYORZbKj5E8oFCqJ8XrtWb3RUf8XSyaTQX9/P8xmM4LBIFO7UFaMWmZR4DiXy6GmpgYtLS0lSxCkg0yLRHQLTxp08b3jFgdNKtFyEoU+S9Qn5MaKwU76rFKphMlkgtVqhdPphNVqhcFgwPLyMpfP9Pb24sMPP0Q+n8d3333HzRnEyUw/1BRVrEVbW1tDPB5HQ0MDo/1lMhnHzgAw35fRaGRLSNwUgKMi4enpady7dw/nzp1DXV0dMpkMKisr0dTUxB15RZeUpL6+HoFAgON2KpUKBoOBy308Hg+DOYn1ghDfx1lTxSyQYq5Ssc+IYyiO7+rqKh49eoSmpiYMDQ0xZkzMOFK8TcSG9fT0IB6Pc3mY2WzmY6WMCcW+V/r372tRiZ+hfpMLCwtIpVLsptfU1ODw8JBZPolOem9vD1VVVYyvehN56xWV3+/Hd999B6fTyZmJwcFBDuiFw2EGqREjQjKZRCQSKeAyksadKFYAgHcK4EfApXTXKia/zw5W7H9ptqq7u7uAQz2fP8pE9vX1cRceijfZbDZoNBp0dHTgm2++wRdffAGTycTAPZnsqIEEYV7E6yXFfOHCBfh8PoyOjjJI9urVqzh9+jRyuRwDOel6yNqkzsxqtZpjVVI3p66uDj/72c+wurqKZ8+eYX9/H9FoFE+ePMHy8jI8Hg/a29sLsFYktbW1uHPnDneWpnERSQ21Wi16enqwuLiI8fFx1NTUsGKnayhmRUvH7riMn/i6ONb0N8U3NRoNWlpaeKOk4yjJkM/nsb6+juXlZe6otL+/j/HxcczNzWFoaAgOh4PrJsWEhXgtUkX7Ju5tMeUr3UTFKg86NpVKMfKf2DIcDge7fzKZDGtra39o7kBit9thMBhQUVHB9V3k01MKvb29HV1dXVxXtrKyUuBzSxUKWTCvXr3C/v4+k9S3tbUVYMZISu1iJwUz6fViCop+i3+bzebXMmHE5EkTl44bGBiAVqtFTU0Nrl+/Dq/Xi7q6Om4OQbEHqZISr6GiogKdnZ24e/cuJiYmkE6nEY/HOdtGmT8CkZISqKysxLVr15BIJPDDDz8UxFLo2fp8Psjlcpw7d45jiRqNBqdPn0ZNTQ1GRkbYdSd8Dn0WOLKqQqEQZmdnkclk4Pf7OXZCCZSysjJ0dHRgamqqoGaxlMsvHbPjpJibROch5UMUNQ6HAxMTE6isrMTAwAA3SxCtqmg0iv39fb62YDCIZDKJq1evoquri58BsbbS5lXMCi91H6XmY6mQA90XMSacOnWKrzMSiSCVSmFychJVVVXMk06drIlZo9h6KSZvvaKKRqOw2+1QKBRQq9VwuVzcnTidTiOZTGJ3dxcejwdqtRp6vR6VlZWM+SimpMgUDwaDTBOSTqe5XEWcIMUyJ0DpCVBs5xN/i69LFVWxALwUxEkTmBQSAO5qLGUJaGtre60+jnZ9UvwUOI9Go5DL5ZiZmcHu7i4MBgP6+/vR0tLClDqkTIh1Qa/Xc5YS+JGLPpfLcfF4R0cHF0ur1WpUVVWhpaWFeeoPDg4wPT3NmCGR2pbuxWQyYXx8HEqlkhvOJhIJqNVqdHR0YGhoiGEsxWoxpc+92HiUOrZUjDOfz6Ourg7/+l//a8hkMp57crmcOyARzksul6O7uxutra2MF2toaEBtbS23dKPjamtrC+AYb2LZi/NDeu9SS1d6f/TdsVgM6+vrXLWg0+ngcrkQDAYxOTmJ7e1tmEwmtLW1IRwOw+l04saNG7BYLPjtb3974vW99YoqHo/j5cuXqK2tZcuHEM7UBp1I1RKJBC9McutEhSKaumQdVFRUMGhNWtYiVVLFrKaTdjY6XvoZ8VykNPP5I1pecrlEd1RcgFLaGunflHYm5ULviUwEFRUV/B29vb0cQxkcHORNgCy88vJy5gCzWCzo6+vjjjd9fX0MNaDvkcvlaGxsRDgcRjweh8vlQmNjIyKRCCwWC5/TbDYjEAggEonwvZaXl6OpqYnR5j09PaipqeGmqA0NDaiqqmKoAtXHibG9k6RUfEr6dzHXXVQIOp0OLS0t/L4YzKeWUzTPqACZhMINUmUo5bsXN5jj7kV6nScdU+y+iCddo9Ew4NPhcKC+vh5KpRJOp5OrN8xmM3Z2dpiL7CR56xWVxWKBy+ViTumFhQUMDw9zLIfIy6gNFOGP0ul0SfOX3AS/34/Hjx9je3sbtbW17GIdZ0mRnGRaFzteukBoIns8Hjx58oSbjZ46dYoZMu12OyorK1FbWwuZTMbIda1WW9BwVMxakgISF4FSqSxQVKJ1RXV5+XyelZv4Wb1ez1gnai9PCp+UCn0/PY+ysjJcvnyZzyGlFxbT2lILoqKigi0NqiUcGhoqUAQikJIwV+KzPW4MpL+lcpybKL1X6XH0XMSSE/E505wV3VPRIiXFROeSKsdS91TqesXrpu8Q75OablCWORKJ4ODgAIlEAolEAtPT0zCZTOjs7IRCoeBuNH6/HysrK3/I+pEQW4Ber0cikWA0Ne066XQaiUQCbrcbMtkRVQtp/lLuGi0MtVrNFLki9xFQOEmkIk6eYq6l+H3Sv8Xj6YeC4uXl5RgeHsbk5CR33ikrK+PY0cTEBHZ3d2E0GhGPx3Hz5k1YrVbs7e1hc3MTTqcTDQ0NTMNMOBixCFq8RzHYS7EhKYJcnIhiVk36nKQLn54zudmidUDZL2ngWbR4KftKCpa+XyzSlloc0vuTjpl0fKSvl7JOxHsS3W8CGRMLRFlZGd9vIBCAzWZ77XvpWkOhEJMcUl3k4uIi0+4AwKVLl6BWq1/LqErHoJSiKhWnE8cTACemiDqaCAJo/iwvLzPguKWlBYlEAgqFgpM8L1++fO25SeWtV1REL0LteQwGA7MKJpNJdvl8Ph/Xefn9/qJobFHo9ZaWFqYsoYErNimkr5NIldlxO3QxkclkcDgccDqdTFMTCoUQj8e5ns1kMkGn08Hn8+HcuXNwOp34zW9+g52dHbjdboyMjMDlcqG8vByBQAC//e1vOd5WW1uLd955h9km6Ho3NzextbXFBGgNDQ3wer3cNklc/NRCiaxY2iDI6iFFJColOlaMW0ldGFr4ovIRlZL4P1Domh8eHnK9HCmJZDLJoM833emLyXEWtRjXCYVCePLkCZLJJILBIAYHB9HZ2ckcTh9++CHT4ohKNZlM4u7duwCOSqeGh4fxzjvvQKvVwmq1YmxsDMFgkJlspddRbAOU/i29ZhLpeei6FAoFUyZRjaVMdhTnlMmOMr7EpCGXH7FCJJNJuN3uN3qmb72iUqvVXMCaz+exsLDAC4cWQnd3N2f9qNav2ODQb1o00WgU9+7d4y7LnZ2dsNvtkMl+zD6JcpxpfZxpfpLkcjmEw2FMTk5ibm4OZ86cwe7uLnZ2dvDy5Uvs7e3h5z//OdPAUgfoRCKBkZERNDQ04MqVK2xd6XQ6fPrpp9je3sZXX32F69evv1a3FwgE8PLlS7S3t+P+/fv4oz/6I4yMjODy5cuw2+18/wcHBxgZGUEymcS1a9dQVlaGly9fwu12Q6lU4ty5c8zeWV9fj+XlZW4kKj4DlUoFr9eLubk5DkTX1NTA5/PxZK+uroZMJsPMzAwrr6GhIS7TEMfx4cOHkMlkTE+dTqextLTEJH4nSamN6zirSrSoSFHp9Xr09/djdnYWi4uLzCpKgGPaGMSayHQ6jc3NTQwNDaGyshIrKytQqVRc1/n48WO0tbUVdI2WupfFLKpSIrXixeNpI9Hr9RgYGODCeJ/Ph0Qigc3NTeRyOQwMDHCPTQIhLy0twePxnPisgX8BiopYLW02G5vFZIYSYjqZTGJ5eRlarRbA0YSnYHEpN0CtVuPOnTsIBALI5/Nc4CyN9QCv70jHuRZSkU4imnjiuakAORaL4dq1a+ju7ua6MavVis8++wx7e3sYGBjA7OwsVlZWMDExgfr6euzt7UGpVOL+/ftob2+HwWDA/v4+FhYWEI/HC9w38XloNBqYTCY0NzdjY2ODO5AQDEEuP+Jnv3fvHgAgEAjgs88+w+XLlzE1NYXz589jbW0Njx494oajyWQSz549w4ULFwosWlL833zzDYCjmNLnn3+Od955B8vLy7BarUgkElhYWMDg4CCmp6f5ex48eID333+fXSCy2iKRCC5dusSZs62tLbZCS7lEpRZ2KYtDKtL4TnV1NSorKyGTybC4uMjv19XVcQ2kaC0CP7KelpWV4cWLF8wBRXWy1DKrp6enwAoTlaR0Dh4Xwyp1T2J8LJfLcWwqGo1y5o+sqNXVVYyPj3Npl06nQygU4kqJpaWlkt9N8tYrqng8zq6fTCaDxWLB+fPnIZMdYVN8Ph+CwSD29vZgt9s59iHGX6RCg19fX89upFiZL+6axVy7N9mxpd8n7srSnXliYgKjo6O4cuUKLBYLkskk1tfX0dDQAIfDwdm3wcFBNDc349WrV1hdXUU+f0Rr3Nvbyzvxhx9+iP7+fmxsbGB2dpatTvG6ZbKjOsnFxUV4PB54vV5cuHCB3UW6xlQqhXA4zJTSX375JeOG2tra0Nrait3dXSwtLcHtdmNpaQm1tbVoamoqQLuTu5NMJnH9+nXU1tZiamoKsVgMMpkMAwMDiMfj+Prrr5kCprGxETqdDsvLy6/FvfL5PHe3CYfDqKqqYldFuoBL/f0mQXe6fnEcxfGUyY5KkYizaWBgoKAEixI6UjcykUggnU6jvr4eer0ei4uLCIVCMJvN2N3dRX19PbtYpWAF/xQpdt80N7LZLPb39+Hz+eB0OpktpampCYlEgl1tjUYDi8XCHP9/6JT8j2I0GqHT6eBwOBAOh7mamx6wyWRCb28venp6YLFYsLW1xW2nRY4kUWjSiBNJnBTFFFOxySsufCmKWDrBRMUnvZampiZcuHABmUwGo6Oj6OnpQTgcxjfffIOysjJsbm7ixo0b2NjYwPT0NMbHxzEwMIDy8nKoVCrU1NRAq9ViY2MDMpkM77zzDtPXEKMEcDQpSYEAQE9PDxobG/Htt9+yCU8WACkqv9+PV69eQavVMvMBbQZarRZNTU2Yn5/HDz/8gMbGRrz//vvQ6XQFsSZSlhqNhrmNBgcHsbKygkAgwFYFNUAVucTFxp30vEgpxWIxhEIhxmDRd0nxZCctbGlM67jj6T2FQoFEIoFnz55haWkJ586dQ09PD1t+4vwAjjZcao1O6PO+vj7YbDZ4PB4kk0l2twlUWUyklpX0e4rFAIudQ3yfXLqWlhY0NDQgFothZ2cHLpcLfr8foVAIp06dgl6v5z6Jfr8fExMTf4hRkahUKnR1dcFqtXJXDFpsqVQKudwRQ2c4HIbNZkMikeB27se5Y6IbICoaMY4jSikXiv4HCgGPUsUmpoel56IJks1medeqrq7mCdzW1oampiZsbm4iHA7jypUrGBgYYDfi3r17TGqXSqUwMjKC2dlZBAIB3Lp1q4AQkH7H43EYjUZ0dHRwfZ94T2QRUAUAMammUilOu1MhNHDkbmezWezu7nL7b/HZiMDTfD7PfEZUtkHPQ3z25NaL5yE3ndD5tbW1UCgUWF5eZktGVGbSwmCpdUPXc5xINyaaI+vr63jw4AEaGxthMBgQCARQUVEBmUzGFQH0fbOzs5ibm8O7774LjUYDlUqFiYkJ5lUj108s/JXCSY4T6XwrpqRKxW0pbib9DvIwqCQtkUhwGQ01J21ubn6t72cxeesV1cHBATY3N1FVVQWlUgmbzYbu7m4A4MBfKBSC3+/nmFUmk2FrqtgkpDR3PB4vaExAAyPiXMTdmUQ64KLSke7Mxc4hhQrk83meoETgBwCtra38+VzuiBe8q6uLvzebzeKjjz5CIBBAKpXiFttbW1twuVx45513CtghxPjY4eEhJicncXh4CL/fj+rqamxubuL58+doaGhgxHlDQwMuX77MfFmkFBobG7mNklqtxo0bN5BOp/HkyRPY7XY0NjYW3B8xA2xubiKfz3Orra2tLayurnIvPCIF3NjYKIh9SAPT1GaK+NoVCgU2Nzdx9+5d2Gw22Gw2bgyaz/8IJ6BnVyx2+PvGeWQyGZeWLCwsoKqqCk6nEzqdjuma6ZptNhtqa2u5vdidO3eYOntgYIApoLu7u18rnSlmRUnn4Zveh1RobKif3/b2NqxWK1paWqDT6RjuMjw8zEXkhK6nMX4TeesVFTU60Ov1CAaDWFtbQyAQYOoQpVKJrq4utLW1wWQyYXt7G7lcjndwoDh2JpvNYmZmpoD4rb6+HltbW1wATX3owuEwZ9pokaTT6YJ2RnRO0dWRZmeA0iBBqVspKjmiQQFQYM0AYGiD+H1nzpwpiNFJzwkA/f39bPkYjUY4nU4YDAb4fD7mqKqqqkJDQwPXnlHwOJFI4MGDBwCAgYEB5PN5jmdQrKOhoaFgZ6cWTNTJxmKxoLOzkzvxarVa7j+YTCYxOjrKXVwowwscKSy1Wo22traCdu0ulwu3bt3i5yPSrBy3eIuNQynrSxoiaGxsxK9+9Ss+jhSMXq9HT09PAci2sbER9fX1bLVUV1fzJiKGJwj/J25wpWJmJNJi7OOQ7NJ7JNdPrVZzEiCdTsPr9cLn8wE4apnX398PvV6PsrIyZLNZ6HQ6LrR+E3nrFZXZbEZnZyfMZjMODw9hMBjg9XqhUqk4kEfMl2TuV1dXM1VGsZ2QFEkgEMD9+/eh0Whw+fJlyGQybG1tcT+7qqoqJrgn5WC1WtHQ0IDZ2VlUVFQgEolAp9PB6XRibW0N1dXVCIfDTHJHTS98Ph8XqsbjcZSXlzPFCikVEeskvV66F3IDpPGJYoFjMYguxtpkMhmj3cXjTp8+/ZpLJLZrOn36NHQ6Herr65FMJtkCpNIls9mMmzdvFjAAkKhUKrz//vs4d+4c0uk0LBYLLBYLysvLubUUcajX1dVxqy5yW8WdW6fToaOjg0kAafPo6el5LSEijTsWs4ylMRupq0jHkiVO/8tkMlaW4rySyX7EkQE/9s6TotqlzR6klrqIv5IqL9HCErsTvYkbK36XGEqhxhmJRALZbLYATxUOh3F4eIhgMIjKykr4fD7o9Xq0trZiamrq2O8E/gUoqmAwiIcPHzJ5Wnl5OWN0CO8RDocRDAa5Ueab0KNSJoP41Xt6ehAIBLC/v89p45/85CfIZrPw+/3MG3Tjxg1kMhns7+9jZmYGcrmc+wIuLS1hdHQUNpuNCeOmpqYwNzeHbDbLls6zZ89QW1sLj8fDsaZYLIbKykqEQiE4HA52S7VaLbOOkosI/AiTICtOdLFEZSbusFLLSlx04kIUF7aYvSO3lJDLZO0RipmOEV0ecbGR8qcFncvluH6TRCaTsRVdzEoQ40RSt1u0dkopKKmVRCKNW0n/lslkrLTpuoBCJSR+j/i+eP1iHEhqaYv3RucRUfp0z1SeQ+ENsVyHrk0abyqmwGgcKLvr8/mwtrYGm82G5uZmxi9S0mB/fx8OhwMWiwWxWIy7AL2JvPWKiophCWvz8uVLBINBBp5RkXJXVxccDgdWV1e5GUKxCQkcTRCtVouysjK0tbVBoVDA5XLBbDbzTp/P57lUJxaLIRAIQCY7yhRGo1Hs7e1hZmYGWq0W7e3t3E5+ZmYGlZWV6OnpQS6Xw9raGpe3dHR0AADjUqg0yOv14unTp1zjdvnyZbjdbvj9flZe3d3d2Nzc5DKNRCKByspKBAIB5jLKZrPY3t7G48ePYbVaYbVauYpfumDz+Tw3chAzVdKUuKjEABQohmKdbUq5sbRYqcOK1K2RWi7iQhO/X1Q4ooUpKmixVo7uSfxOunYRBCsqIlGkSRCxhRcpBdESlt4XKRSSRCLB1hYdl0wmOdRAvylDS92LDw8PIZf/yPNfVVWFzc1N2O127hpTU1ODpaUlxjoVm/viGqDfRExI7n8+n8f+/j52dnYQjUaxurqK+vp6bltHTBi7u7uYmZkp+R2ivPWKymq1oq2tjVtFqdVqeDweZDIZxONxxv7EYjEkEgkolUrY7XYO+AGvZ91oJ7HZbPjpT3/6Gujz3Xff5fbwer0eNpsNN2/e5Op/s9kMm82G/v5+RKNR1NXVwWazoaKighumkkKhzxPnO6Who9EoIpEIwuEw9vb2MDk5iWw2i97eXuYFGhkZgV6vx6lTp7iifWJigulurFYrRkZGUF1dzRaZUqlEJBJBf38/njx5gvLycnR3d3Oci9wl4KjP4vb2Nlt6+Xwee3t7SCQSaG5uLrBoSMQFCOA1V/U4SyWbzXLBKylSqUtK3XNUKhXUajXOnj3L7p+oWEhRkCWxu7uLhYUF3Llzhy0MUkbiNcpkR6wbo6OjXEsXDoe5/Ip6KO7t7bFlHgqFUFFRUZCyp9ie2+1mDndixjw4OIDL5WJ6YkJ5O51Oxlutra1xAmV3dxcXLlzA8PAwqqurcXh4yAXZIyMjaG5uxtzcHNra2lBVVcX0z263m7s6vXjxAhsbG9jb2+Pem+IYSNeB+NyJDppej0QiiEQi3C4tGo1ymzaz2Yzu7m5sb29zpv1N5K1XVNvb21hZWeH21+Xl5VxqEYlE4PV6cXBwgNXVVXR2dnJ8SFyQxQKkVDJAQflUKgWVSoVz585xE9JQKATgqB6wrKwMgUAAwI/V/42NjVxYGo/HYbfbceHCBczOzvL5mpqacO3aNS4LyeVyaGpqwuDgINfWUdeVUCgEo9EIpVKJZDKJ/f195PN51NTUIBKJYGlpCY8fP4ZKpcKnn37KO9+LFy+gUqnwZ3/2ZzAajewS0CTa29tjOg69Xo+Ojg5Eo1HMzs5icnIS5eXlqKur48YQh4eHqKys5NQ5JS2IOVR0K0UXq5j7KFo4S0tLePjwITKZDFpbW3Hz5k1+niQHBwd4+fIlLl26hK+++go1NTWM7SGWT61Wi1gsxtAIg8GAeDzO5Hqbm5uorq6GWq2G1+vl67fZbEin05ifn8eDBw+4O7bb7cbW1hYqKyvh8Xhw8+ZNbG1tYWpqCnq9nokbZ2dnsbm5id3dXXR1dcFkMmF0dBQbGxvY2trC7du3IZfL2aJNJBJMif3111/DarXCZrNBLj9il/3++++h0WjQ3t7OcJDPPvsMsVgMP/3pTwEcbSbDw8NIJpNoaGjg7OgXX3wBo9HIDVfn5+fx8OFDLoMhb0AUaQyLNmxiys1ms5ienoZKpUJFRQVDQ8xmM/b29hAIBLhRh0aj4fKlZ8+enbiO33pFRcFmmUyGUCiEpaUlxGIxBiCq1Wq0traipaUFVVVVWFtbQzgcfi1tKt25KXskk8k4oJjP/8iyqdFoOANDrdEp2AuAUchkFSgUClz/x5o6p9PJ13z27FkYDAZmaACAa9euQafTYWFhgWMEly5dgk6nQyAQ4LjNqVOn4PV6YbVame6FgvCUiYvH49jZ2YHZbGalks/nsbi4iImJCZw6dYpZMh0OB16+fMnW3d7eHpLJJA4ODlBdXY2VlRU8ffqUIQgNDQ0MriUrS61WY2ZmhjOjbW1tXIdJolAouB1XJpNBWVkZmpqasL29DYvFguvXr/PzFi1dufyIdE6v1/M9A0cNPebm5qDX66FWq9HS0oKJiQnmHBNjJcPDw5ifn8cnn3yCw8NDPH36FBaLBcFgEH19fbDb7VhbW0M2m8XOzg4zVL569Qrj4+PMDkAVEQqFAjdv3oTf70cgEMCDBw8gk8nQ0tKCcDiMQCCAJ0+ewGKxYGhoCFqtFh6PB2NjY6itrWW+tN3dXSwuLuLMmTNcUbGxsYFsNovKykoEg0H4/X643W4oFArm6aIwg1jvSN2StFotY7IMBgPHConA7zjogLh5q9Vq2Gw2rqslFzCdTjNEgRp97O7uAjjiDTvpOwrW8Rsd9X+xOJ1ONDU1weFwwO12I5fLYX9/vyBTQc0LCOfhcrk4NVwMmV4qaEoDR26DyLxIyk10OaTv0XlEsCkFv0mh0TXLZDKu52pubkZjYyNUKhV2d3chk8lgt9tRX1+PeDyOg4MDpFIphEIh/PSnP8Xa2hrUajX3srt69So8Hg9MJhPS6TTa2tpw69YtDvqHw2EMDQ2hsbGRkw+NjY3o6OiAw+FAX18fc7PTRGxpacHe3h729/dx9uxZrK2tMS0ttcuimi9S0KIbQR1nlEolJiYmoFKp2FprbW1FV1fXa/Ew8VlOT09jZ2cHqVSKSzry+Tz3npuamuIWXDabDeFwGBMTE9jZ2cE777yD8vJyPHz4EKFQCM3NzfB6vdjd3UVTUxPOnj2LfP7HgudAIIDDw0NuaiHS0hASX61WQ6fTFWxMFHYgVL1Op+PMmcVigdFohNVqBQDO+BI6X6/Xo7a2Ful0mhHfRqMR3d3dDMaluNGVK1fg9/t5LhkMBrz33nvweDzIZrPM1HrlyhV+jea5dI6Lv6XJFkKo0/XY7XZYrVZW0uFwmOc8xalOyjKSvPWKiiZYRUUFgCPa3d7eXgBHgM/9/X3s7u4iEolgaGgIBwcHaG5uBlA83fymGR8iFKNYDCk9qeksWgXi+9IYgDTDI+5EZDWSm5fPH5XV0OeJnvb27dtsQVKdXH9/P1tDwFGWlNwig8GAVCrFsbBEIvFa3R/FZkj5igspkUjAbrejoaEBSqUS4XAYsVgMnZ2d8Hq9HJMTM48KhQKxWAzRaBSXL19GRUUFPv/8c2SzWVRUVKChoQHNzc286KSBb6qBu3nzJsee1tbWsL29jYqKCnbliJZmZ2eHd/1gMMisn8BR2Qq1TzOZTKivr4darS5AfwNga4junxTK1atXEYlEePw1Gg23uaL7bWxsxNmzZ7G9vc3zrKurC7du3cL6+joymQwrc+pgncvlYDabcefOHY6RZTIZVFRUoK+vD7FYjGOKHR0dqKmpgdfrhV6vZyiN0+nk+5XL5dx0IRqNcgZWfK6iSF8rFqMi1laaC9Txic4dj8cRDof5+Zwkb72iUiqViEaj/AB9Ph9SqRTkcjmbv7W1tTCbzaiqqkIgEEAsFnsNhVzMeio2iGKGio4TU96i4qLzAz9aA2K8RjxfMXiA9H1plopeJ+uRFjfFTfL5PFpbW6FQKFh5z8/PY25ujru+3L59G/v7+3j8+DF2d3cZ5Q8clbVQgSxZiCKFM2U7SUGJPFQipED6PMXMHlkb5CYTzzo9V9HipTGlv9VqNaLRKPx+P3p7ezkwnc/nmT55a2sLk5OTcDgcaGpqQjwex1dffYVPPvkECoWCLXJq4AqAM7fJZBL5/BHd7pUrV2A0GnF4eAilUon6+nqmqKY+fQMDA7BarUilUsjnj9hQz58/D4vFwuOgVCpx9uxZxpuRO0UbWnV1NTcSIWVJ9Y2EAxPLuNrb2zkpQ3NLr9fzddNrBBeh8EQxS0caoyIREyNlZWWIRqOYnp6G3++HUqnkbt1NTU0wmUxQqVSIRqPY3NzE6urqa+crJm+9oqqsrMSZM2eg1+uxvb2NxcVFjk1RcJq0PS0yaucjWkRSJSJW29NCI5OeFpFoFYluiqi0ipnWJHQcne+4riLid4kupfieSD0jukyiAj1z5gxaW1s53mM2m5knKpc74hVqaGjg8hhSfnSesrIyxONxpNNpWK1WeL1epqChOAbVeHk8ngIrTdzFifLFbDbj4OCAY2ciIFN6f9QAdXV1Fb/+9a+RSCTQ2dnJ2U6v18vQgvn5ec6cVlVVweFwYGBgAI2NjXj27Bncbjeqq6uxtraGmZkZqNVqRvCbTCaOTeXzebhcLlaslC0mC14sA3I4HGx10UZFRINkgZA1LpPJuDhbtLpJwYvPXcxqAuB5K+K1pPOEjpda9eI8KjbHir0m1kNWVVUhGo1CpVJxWIXis1qtlq0vrVYLu92OeDz+Ruj0t15RbWxscOpXqVQyEI0yOl6vFx6Ph1toEU3qSYWcgUAAHo8HdXV12NvbQ0VFBfv7FRUVCAaDvHMR8jkWi/HkE60HaeFrsWJSWmClLLliyo7+lt6HqCyl7xHgUpzE5eXlzBlFCxI4WozU4Ye+p7+/H/F4HAqFAnV1dfjwww8ZqUwsBUSRbLVaObUvKnudToehoSHs7e0BAHp7e7lWU1S2otBz6erqgt1u5043LpcLtbW18Hq9/D4Vn5N7RNmnZDIJq9UKl8vFbovdbucMLLW4N5vNOHfuHMeY6JmKlqFoMYvjJbrxxdz8YlazaKGLnyuWhRN/xHkhXoM003qcZyB9Tfp/Pp9HKpWC2+1GXV0dtra2EIvFUFZWxuNgtVqxsbGBxcVFqFQq9Pf3Qy4/ou7p7OzEo0ePXvt+qbz1ikqr1TI26uDgAHNzc+zDp1Ip2Gw25hs3mUzcL63UYiBJpVIYHh7G+Pg49Ho9s1o+ffqUKX3PnDkDmUyGiYkJVFVV4fDwEN3d3chms9jc3ERFRQV2d3fR0dGBQCDASs7j8aCmpgZ+vx+ZTIYBe9XV1QiFQrxTEaqbwH3FJhdNRjFGJiow8Z7ERSVaOSIQUupyiUqWXBDa7YlChs4tPkOyMKhTrrigFIqjTsBdXV0Fbh2V7EgXoWglOJ3OAtLDbDYLk8nERdKkQMhqFq1WiisS/kcmkzFEQzxOJpNxxleqCIopUvF/8ZlL445ShXXcZik+F/H+RStdPKd0nOlzxax0qUKU/i29NzFuRw1GCPPmcrlgs9lQVVUFufyoCQhteqFQCJubm0XPK5W3XlHV1taioqKCzeNUKsWDTIBPokYFfqQuliKbpQogEAhgZ2cHm5ubaG9vx6lTp5BOp7GysoIXL16gqqqKd47l5WU8f/4ctbW1aGtrQzabxdTUFJ48eQKHw4Guri6oVCp88803zJ1VVVWFSCSC4eFhzv7U1NTA4/Hg4OAATqeTdyRKP1NsymazIRaLcTt16W4tjbWJkzUWi0Eul7PCoQVDcT06lrBWdB4RTEnfIXV1iz1PcSFJY3GktERLUhrbE88p/i1aoOJrUgCqmG2Vnkf8X1QIpUCsojsltY6KXad4XcUsYjHWJF6D+HzFc5CiBVAQspA+M6nV9f9WqAM5NfOlHgSBQABarZa7OrW1tbF7TIwLhDU8Sd56RbWwsIDZ2VmmfK2rq+N4QCgUQigUwu7uLtxuN9rb2xGPx7lWrJh1QpOG4hRms5l3bELjarVaLoolDqZAIACr1cpZHGp6KpfLEQ6Hsb+/j5WVFfh8PsbKhEIhzM/PI5FI4Pz58wiFQtjf38fXX38NnU6H6/+Y1t/d3cWTJ09gMBjQ2NgIvV6PiYkJlJeXI5VKcY3jwcEBqqqq4Pf7GVNE9XLU5ODJkyeYn5+HxWLhVPze3h7H9pqbm1FVVcVIeKPRyMh/8TnR4iPqFZVK9VpZhri4pbE+el9cqKLSLeXSAD+2M5OW5BQ7nha/aC1K3SKpUhAXvFheIx4nTaCQdSdeSy6XYwuONgK5XM7Pi/jCKEGgUCgQj8eh1+u52wsBLo1GYwFLB81jQn9TCZdWq8Xh4SEj5ansS2rNFbP6ignd99raGtPuBINBbjRBsVyPx4Nnz54hl8uhp6cHdrsdwWAQbW1tePr06bHfAfwLUFSUPlcoFNjb2+M0vFar5aAf4aycTidCoRCi0SiA12M8NJGBH7nYnU5nAUvhqVOn4HK5mAspnz/KrA0MDHDFODXCJL4oi8WCaDSKpqYm1NbWwmazwWw2Q6fToaamBrFYjKldybdPJpMIh8OsvJ4/f87A0GQyia2tLTx79gw2mw03btyAUqnE5OQkVldXGYqhUCiwuLiIhoYGeDwetLS0QKPRoKqqCq2trRgZGUFNTQ2eP38OlUoFhUKB7777Du+++y5mZma47ZbP58N7771X8NzlcjkODw9x//59BAIBGI1GXLlyhTOGomUiLgpp/IwsPrIUSMlSXz5pID6dTmN8fBxbW1tobW1Fd3f3a4kMsqwpoSJ+BykNuh7q7BOLxZhBlBZ8JBKBwWBgrBQpZovFAo/HA6vVinQ6jVAoBJfLhe3tbVRVVcHn80Emk8FqtWJ5eRktLS1YX18vAKgSKHVoaAhut5vPsby8jHPnzmFhYYGtk729PVy+fBnj4+OorKyE3+9HPn/Em/7s2TO0tLRgcXERHR0dqK6uxqNHj9DW1ob5+XlcvXqV+xpKNxGpkj9ujVGdIUFLNBoNzGYzlEol6urqEI/HOZvrdDqZ2YLqak+St15RNTU1oa6ujmMpZNFQ5s/hcKCuro4R5SaTCUajscCEB153DVwuF5Oekc9tNptRWVkJlUrFaPRcLodLly5x6lqv18PhcODatWuw2+3MXa7RaHDjxg0ujM5mj5o63rhxAxqNBjs7OxwbuXnzJqLRKHQ6HdcOVldXI5FIMOI8Go1ifX0dBwcHXOqzurqKhYUFuFwuBmlOTExgeHgYdrudm3VGIhGGEZDVcP36dRiNRvz6179GPp+H1WpFZ2cntzwSlQ4phtXVVezu7mJoaAjT09MM+JRuAKIVIr5Of5Mlm81m8ejRI7S0tKC/v5+vkSyaXO6INXN4eBjl5eX44osv4HK5OOBP30uAUIfDwUq/ubkZP/zwA86dO4f19XWYTCY4HA48fvwYZ8+exeLiIvr6+hAKhTA5OYmOjg7Mz8/j5s2bmJ+fh8fjYWzSnTt3sLS0hFAohHw+j4qKCrhcLoyMjECn02FnZwfXrl2DzWbDgwcPsLq6Co/Hg5/97GdIpVJ48OABRkdHkUqlMDQ0BI1Gg9/+9rcwmUxcUhMKhfDDDz/AZrNxd+rDw0N899130Ol0uHHjBoCjErKnT59yIiEWi3F4oqysDGfOnCmqjKTz/jjLimAQarUavb29SKVSCAaD2NraQnt7Ow4PD+Hz+TAwMMBoeJlMhu3tbezs7LzROn7rFZVcLkckEuGFRCniQCAAs9mM8vJy5HJHXTSo6lxsZS4NOJOIu7NYjwYcDS7hlABwyrq6uppdLTpHd3c3Z5JIMZrNZqhUKs4aUlmNWq1GZ2cnK4j9/X1WaD//+c+xsbEBAFxHdf36dc5I2u12Rj8TKjqZTCIQCGBvbw8ymYxLaNLpNBYWFrC+vo7Lly+zG0uIY61Wi1AohFevXiEajRaUBokuWSqVQldXFy5cuICmpiZEo1Fm3qTauY6ODm5IAAC7u7vQ6/Vwu90IBoOQyY5I7VpaWjA+Po7x8XH4/X7ORIrulEwmw8rKCjo7O3Hu3Dn8t//237C3tweHw1FAsSKTyeD1evH48WPI5XKcPn0aSqUSPp8P//2//3ckEgn8yZ/8CfL5PKanp7G9vY1sNov+/n6oVCqMjo5ieHiYQbXpdBr37t3jbsGUrHny5Ankcjk++OADphL67rvvoNVqcfr0aQQCAfh8PkxPT6OqqgrpdJrDAAQ8DoVCODg44ALwyspKju1QHIhAnhTA1ul0iMfjnNkki4+C3JT4AFDAe1UsFnuSkEtLriX19yNsHW0Ee3t7mJ2dZarv8vJyuN3uApjFcfLWKyoqRyB/n4RcKAJ3EpiPXAIxQ1YqcCt1S0SLQEzjA8WDmqI7Ip6bsk40iHR99JusDKfTCYVCgaGhIcjlR+3RQ6EQVCoV+vr6UFNTw4yl1Fzz/fffx4MHD7gBQlNTE/r6+rC/v89W5cDAAAYGBvDXf/3X3OSBjk8mkxxsHxgYYNBeNpstmPS0gCn+4XQ64XQ68eWXXzKv1PPnz6FQKDA/Pw+73Q6j0YiZmRlUVVXh8ePH3Pr922+/ZUs1mUwW1AZK41yxWIzZWuvq6nhsgB+hFclkkhWESqVCa2sr8ylNTk7CZDIxC0IsFsPm5ibq6uqY9z2Xy8Hj8aCzs5N52VUqFUKhEI8zxZLoPdo8qqqqmPaZ5iYxZBKivaqqCtXV1dySjBgH6ByE9j579izjksj1pBZu5Fo5nU60t7djbW2NKxiamppw+/Ztxsa9qYtXTKiOMxAIwGAwcO9Ih8OB9vZ2jlXF43EMDw8XtCQrKyuD0Wh8o+956xUVgQUJv0S+s16v5x1+c3MTJpMJra2t8Pl8BeURUmUltaToN71HfxdLUxfL7Eg/TzEXKWWwuOBEBSeSnimVSjgcDo6LyeVytLa2spX4/vvvw2q1ch1YOp3G5cuX4XA4sLi4yCR/qVSKEdb5fJ53dJPJxAwQyWQS1dXVsNvt2Nra4gUpxpio5iybzbKCSyQSGBgYQHNzMzY3N5m2mJ5zNBrlOA+14HK73Ugmk+ju7kZHRwfOnDlTQEUiBoBjsRiCwSCTuUmbZRCUw2w248yZM/D5fDAYDFCr1TCZTFzvZrPZoFQq0dDQgP7+foRCIajVasTjcXR2dmJoaIgTEGq1GleuXGF6abJYb968yRmvXC4Hp9OJwcFBTE5OsoLr6elBa2srFhYWuFLiypUrqKiowMbGBltBt2/fhtPpxPb2NoAj67ytrY0D5jKZDJ2dncxaQPPl1KlTqKys5IakBoMBV69ehdPpRGNjY4GiKGZNneQC0ng3NTVBq9WisrISLpcLyWSSaW2IM621tZXbvANHHaL+gEz/RxkbG+Ndk4LYDQ0NyOWOugt7PB54PB5mFADARcrA66A6UiQrKyv8OnGGk0UhVWr0t1SKvSbFOonHSNP/xYKfUneU0taZTIYtSxFnRIHUgYEBpFIpDkYvLS3BZrMxXcvf//3fMytBMpmE1+vF3bt32QIVRQzETkxMMOMANYENBoMMcdBoNFw4TZnOsrIypoURi3fJIiKrppjFazQaMTExgVwuh1AoxHgpeiZUk1ZdXc0KiCzg06dPM20LFc2eP38edXV12NnZgUKhgMlk4vjS3t4e1Go1mpqauKCYuKaoXCadTiOdTsNgMODs2bMwGo08/4jTXaPRoKysjK1Wuv/y8nLIZDK0t7fzmBMLQmtrKysjm83GyoLCDjT2jY2NyOfznPUGwEre4XDwc/yniDgHaROihE8ul+NQAlldkUgEyWSSgbhUKfAm8tYrqpqaGq7TojbkhKWiCUQ0FFarFT6fr6AZgjRVTYHM58+fo6qqChqNBtFolE3yYgqmVHr8uNcAsFVgNBpZCYrKCihk1KTziIyRomtErxVDvisUCuh0Oty5c4czMVRC88tf/hJbW1tIJBKor6+HVqvFhQsXuEVWZ2cnc8wDP6b9u7q6sLy8jO+//x4KhQKVlZUwm8149OgR14Jdu3YNBoMBX3zxBScN6urqChgtKEFAqW6fz4eGhobXlDUADA0N4Xe/+x0eP36Mnp4eboBA10WWbnt7OysDUuYdHR1QKpVoampiK9VqtUImkzF9NT1ThUKBmpoaKBQKbnFFgXNyy8nKJWueYDEiQyfdm1j7KGKgiln0pTBQUktd+lqx44ttdsWkVPiDYpGbm5u8FlZWVjjwb7PZuKD78ePHzFar1+uRSqU4C3ySvPWKqrGxkQs5AWBlZYVrjWi3pkwExYBEpUDuFS1slUrFCOze3l7Y7faCtDoJDbq01kp8v9hrovu4u7uL77//HhcvXkRraytksiM2gO3tbXR2dhZ0UaF6RcIqSUGCootJLh3VgonuEcVE6F6y2WwBtxMdd/36df6fLCopy0N9fT1+9atfIRwOc7ykqqoKe3t7DAWor69HY2MjVldXkUqlcPr0ae5cTOc9e/Ysj8vVq1cLSpxEFxg4qu38xS9+gUQiwRxIxLwqLnJyU8VMIJ2Xno3o3gOFaHBpbKcUxEIUcR4Vs4DfVAmRSFHr0nMWs+xLSSlFVOp9OoaUbUVFBeRyOStjwnx5vV4ex+bmZtTU1MBms8FisSASicDv9x97XSRvvaJaWlrC2toaHA4H5HI5+vr6oNVqkcvlmHFwdXUVKpUKHR0drwWFRRSyWHC8tbWF+/fvw+l0oquri+vDgNcxKKWsK1GkuyFlxVQqFeLxOL/v9Xq5953ZbEYymYTH48H6+jrS6TR6enoYLkHZF6pzJFChuKvTYpJyfYuxMqBQCYklO2IsTlyg9AxsNhvKysr4f5PJxO4YXYvFYsHAwEDB4hZBlDU1NezKVldXFzwvKRAzn88z+JTcDlEBSBdzsXEQ8Vv0HdKiXeB1RSE9jxjfKRbjlJ5HGm4QlSpl6+hz1HuSniPBNCi7KVL/SM/9zyV0LpVKxcywVquVs45erxfJZBKZTAYej4ctR7qXeDzORAAnyVuvqGiBZbNZJpynyUs4nLq6OjgcDqYLlpaGiJNdJjuq7LfZbFwfKLpTxeQk1086QWlnt1gsqKmpKQjuNzQ0oLGxkf9fX1/H06dP0dLSgsbGRphMJiQSCayurmJ4eBgKhQIff/wxdnd3MTk5iXw+j/r6egwMDMDj8cDr9UKn08FsNqOurg4ymYwBe9JuveIiJ/dYvDbgdd4t8bmILio9f3KxRGtSqvBISdFr9B3FcFeicpD+L1qVYla22CIWFVmx85/kwp8Ue5F+F0ksFsPGxgYSiQTMZjMT8ZFQ1nJ6ehqBQIAtwfb2doyNjXFpk9Vq5WREse+RykmKrJiFJSrBtbU1fr5zc3PI5/Ooq6tjxWW32zE6Oor19XVuYRcOhwsqGo6Tt15RtbW1ob6+HgrFUTfalZUV7kJDPEd6vZ45osXGk0Bhto0knU7D5XLh9OnTHLgsZUH9PiLd/aRuCAkB5vL5PLa2tnBwcIDe3l7o9Xpu9f306dOC+kZq6tDU1IR79+4hnz/K5hGyemxsDDdv3oRarcb333+Pzs5ODA4OFgVfer1eTE1NcVatpaUFFRUV2Nra4rgf4dNEgF8+f5TVMxgMyGQy3D1FpG6hgDfhbwh9nUqlEI1G2YIjjBmRxuXzeZSVlRUE9unaqbqflHQwGEQ4HGa6GuCos08mk0FHRwfW19eRTCYZXEnypuN6UlxIPJ/Ukh4ZGcHa2hrq6urw/fff4/3330dXV1eBgg4GgxgbG2OM27179yCTyeB2u/Hxxx8jFArh+++/x8DAQEHR+EmKqpSVKb1eqXVIMAsaT8o853I57oIj8r6VlZVxPSrx1p8kb72iWl1dxfb2NlO79Pb2sllMrdynp6exsbHBOwBVxhcLNpLS2Nvbw+joKLdBJ8tHKtLznDRhxOPpt0iLDIBNfpq8ADAzM4PJyUmcP38eW1tbODw8RG9vL1PLOp1OjIyMQKVSwW63Q6vVIh6Po6urixkbYrEYx6Koqac0hkLo783NTS7vWFtbQ3l5OXw+HzcI0Gg0WF1dZQuQMj9TU1O8m05PT2NwcJCzUHT+WCyGV69e4fDwkHFR+fwR+NJkMiEcDqOtrQ06nQ4ejwc6nQ67u7s4ffo0WlpaCp5fNBrF2NgYu8bt7e3Q6XTcjZlkYWEBExMT+NnPfoZvv/0WTqcTLS0tJy5e6bj9PlJsYyLqZ+ooTNak1GIPBAKIx+OMAqeaUa/Xy0SFonUqfs9J1yO9r2LxK+lrBATW6XRoa2tDOp3G1tYWQyf29/e5xRzFhSkz+yby1iuqWCzGdCniYJPrIZfLuSkidZ8pFnMRd1ar1YqWlpaCTjPl5eUlUbaldjTpa+K1URpedIkAFLBkAkeA1suXL2NgYADPnz+H2+1GW1sbMpkMfD4ftra2sLOzg1AoxE0X0uk0rl+/DoVCgSdPnkCv12NlZYUJBqn8R7xGMWMGgDm4r1y5gmw2C4vFgp6eHqyvr+PUqVMoKyvD6Ogot30nJb+6ugqZTIbFxUXU1dXBbrcXuIpyuRw7OztYWVnBtWvXsL29jZGREdTX18PhcODWrVt4/vw5wx2I95zogqXJg8PDQywvL+ODDz5g9k5aSOJzz+Vy2N7exl//9V8jk8mgsrKyaAxKalFI45L0dynrutRGRbEom82GkZERPHnyBH6/HzabrcDFpYRPbW0t5ufnGfVNHWZWVlawvb2NQCBQMIbFpJg7J3XzSx0rilKpxPr6Oje9XV9fRzQahcPhYNoXk8mEFy9eYGtrC2q1mluwvamV+tYrqrKyMt6xl5aWsL29jUwmw001iSWgoqKiAKwnijQoabFYuIU7LUApW6dUSg26GPcRhY4pKyvj9DZZOIRiJouBiOlMJhNCoRBaW1vR1NSEtbU1Lr9ZWlrCp59+CpvNhl//+teIRCK4efMm3G43FyqT8iMrTowT0TXJ5XI0Nzdje3sb9+7dQ1NTE4aGhgosP8qoihlBOu/Ozg7W19fR3d2N8+fPFyQuSIiVoampCXq9HtPT00gmk9ywkgC6uVyOrSq3282IdVFR5fN5JkgUY2BEWEgxTIVCgatXr+Lw8JDR4lIoSKlxPMltKubiFYulyWQyrK+v4/Tp0zh37hz+/u//Hnt7ewx1oPiTXq/HRx99hEwmgxcvXmBtbQ12ux0/+clPkMlk8OWXXzJ0hMZQ/A6pSK+t2HvSGJ8oFE/N539sTEJrKJlMIpfLwW63MyeV1WplZo8/ZP3+UahCXi6XM9sjxW4IYDg3N4e9vT3U19dzxbc40UURMzU0eLSoS5nYb7IzSXdgyqxRJpJeMxgM6OzshMFgYCzPgwcP8N133yEajaKjo4N5s6kzicFgQDKZRDAYhMvlYiVdUVEBg8EAj8eDsrKyAi5ykTxOXIhyuZwbC7jdbnz//fcIh8P49NNPuW2YSJNDOCFyt2OxGHZ3d3H+/HlOZUsD7oQ9oudMzzoWi+F//s//iYqKCty5cwfDw8M8VvPz88zjJS6uTCaDSCSC8fFxqNVqhEIhZLNZXlCkUJPJJNrb29HZ2YnJyUlsb2+XdIWKjeXv6/aVmgPk6lZUVBT01ltZWUE8Hudu2fF4HOvr65iZmcHly5e56PzVq1eYmJjAhx9+yPO8lCJ9U0V73DlI6VMW2mg04vTp04jFYjg4OGBE//r6OvPGE/sqlSS9ibz1imp3dxcrKyuorKyETqdj35jKGog7ivrBSctnpG6fXC5nxK2YwaLdVxp8LRVkL2V5iVkz2plEl0upVHJXmVwuh/b2du50nEgkmLA/nz+i2K2trYVer0d9fT2++uorjI2NMbne+vo6ZmdnsbKywqhpuj9xFxYnai6X435yzc3N8Pl8jNKnjBQpJcJC0XMgWtq6ujqMjY1hcHCQY2Ii4RvxqJMVkcsd8dpfvXoVPp8Pc3NzsFgs/KyolIesM+roQmDfjo4OfPzxx4jFYvjss8+QTqeRSCTg9XoL2jYR6JUwXtJ6TZoT4hi+SRC6lBRzG10uF8bGxrinIaHHJyYmsLe3h6amJqhUKiwtLWFlZQX9/f3MJLu3twelUok//dM/5USAFMH/phvlcZYjzVOSdDrNBdZarRbBYJC7NbtcLq5FdLvdGB0dhUKh4Dn8B5qXf5TW1lYYjUbodDpMTU0xARwBIy0WC86dO4eKioqivfykCiWXy8HtdmNycpLPa7PZmPdIlDcNXorfIa0bFF0vUhT0HrkvFouFSyvE81qtVgwODkKtVuPatWvo6enhbsrl5eXMYnDnzh3OjAJHJRkEJi12jcFgEI8ePUJPTw9bYz6fDzMzM1hfX8f09DT6+vqQTCY5g0aFt2azGe+++y6++uor3Lt3D5988klB0JcW08zMDLuYxLWu0+lw6dIljI+Pc6xtfHwcVqsVBwcHUCqVSKfTmJiYQCqVQmVlJRQKBScP0uk0qqqquOh4eHiYFRqxSwDgzBU9y1KbijQY/k8R8Ry5XA63bt3C9vY25HI5lzABwM2bN9kSlMvl6O7uLrCss9ksZ2k1Gg1jyGjsSsXNisWiisWpjrtHuVzODX2JmYSaZpSXl8NgMKC5ubkAD0iZwD/gqP5RaKeXy+WoqamBy+VCKpWCUqlkQOT8/DxCoRCsViscDkdB3ESKTJbLjxg14/E481ypVKrXsD10vDTA+iYxAlJWYoGudPKIbosoYvA/n/+xNCOfP+Iopzq/fD7PsSyKJ9BioVIS6bWShUHlJBRvIBBmNBpFQ0MDDg4OkEgkUFlZiZWVFbjdblgsFrS0tLB7fefOHTx//hyBQICtKrr22tpa1NXVYXp6mttH+Xw+mM1mGAwGfPzxx9BqtTh79ix2dnagVqtx8eJFbhw7MDDA56uqqoLFYoFCoeB6O61Wy22kyKKqra1lFHtbW1sBkJTOJR2rN5FS7mGx81AVALng4viStQv8GAIQx1kulzPaXpwTpebcmwaxi7mLUs8gl8sx5Y5Go+FAeSgUwvr6OpxOJxeL9/T0cJPSbDbLRdYniSz/z+Fc//9QQqEQLBYLc5lT/RjFoFKpFGKxGNLpNILBIGpqalBXV4eysjJ89NFHrHzI7RItmO+//x4AcOHChQJFJSXWLxa3epN4FblNo6OjWF1dxQcffMDIX2qj3tjYWIAapwwKuTHi94pIa1Ghii6meD10P/QZqbkvTS7QfRKVDp2bXGT6IXeKkhZE/icG8ek7EokEdwQyGAyvpeop7iVaDXRt0gSA9FlLXXa6t2KBY+k4/j7yJkquVNxIvBc6h9QFF++l2LmKvV5sXp5kMUrfF+e3XC7H2toa/tN/+k/Y3t5GXV0d8vkjfBvVN/b09CAej2N2dha7u7uIxWKwWq0MsP72228RDAYLeM2k8tZbVHV1ddDr9dDpdFhcXMT09DRkMhk3grRarejq6kJVVRXjPEghiSIu8GQyiaWlJcTjcVRUVPAuIa3/AkrvSKUmgXiM0Whkq48+MzY2Bp/PB5fLBZPJhFQqhfX1daytrcFsNmNwcBAajQaZTAbBYJDbPAEoaGwhnezib2lZDSksWiiiGyFV5mIJDFFAiy6r+Dyp0p7+F61JAuSSUIZORLcTjkxUPOI90d+lSmCkVhP9TUqx1DiWWrgnifRzxdwuwpvl83nO7kqVVDabhcfjQTAYRCKRgM1mQ0VFBZaWlhAMBqFWq1FZWYna2tqSSlZqnUvvUXqseP1ShU6bdTgcZvI/CgmUl5ezG1tVVQWv1wsAnPARQxbHyVuvqEwmEyOWW1tbUVVVhVwux5XemUwG6+vrAI7YAqg90nFumkKhQFdXFxc7FzOHj5u4J71HgeeampqC2jatVovOzk68evWKJ/XLly8xNTWF+vp6bj2VTCaxuLiIJ0+eoKOjA2fPnsXk5CQ2NjZgMBjQ39+PiooKbG9v86JwuVxwOp3cxJM62FAWjso46DXxOsUdVqRjISUmBnTFmkKpkqLzkGIR3wfAm4doVdB1EaxEtILoOWezWfh8Po4pHh4esgKn7yOUvl6vRyQSgVwu5/KoYiKe/5/ilBRb/LlcDisrK1hYWODYzTvvvMNlJmJlwN27d1FZWYlsNouXL1+ip6cHs7Oz6O3thdfrxcTEBP70T/+UN6mTNsZir72pRSiTHTVLraurg8FgYHrvUCiEjY0NOBwO6HQ6bG9vo62tjcGhuVwOPp/vjZ7XW6+o5ubmoFKpmMCLkLEy2VFGLRaL4fDwEPF4vKBhAFB856TslMViYQZKMU4gjUUVc/2KmeIkIjiSrBLRGhA53TOZDBYWFmAwGDAwMMBB57GxMe4MTOyLL1++RFtbG6LRKO7evcs84GVlZdjf38fCwgLeffdduN1uTExM4MqVKwz8lFohu7u7WFtbYzxae3s7kskkDg4OOHNG7JhUEJ3P55FMJhGJRGAymZBMJpFKpWA2m1/rLZfJZLilvEqlQmVlJXZ2dpiCR6PRoLm5GcFgEHt7e2wpnj59mhUsXXMikcDY2BhevnyJhoYGnD17FktLSzCbzejv72cL6smTJzCbzRgaGsLXX3+N5uZmzqa9ictWTI6zrot9Pp1O49WrV1Aqlejt7cXXX3+NnZ0dLuqmeyJE+sDAALLZLHZ3dxmd3tLSAqvV+hqP/XHyT70/klwuh2AwyF2YUqkUIpEIZLIfabVps5ubm+O1VlNTwxbWSfLWKyqn0wmdTge9Xo+1tTUcHBwglztqPU6UsI2Njez6iUFLUaTuzsuXL3kXbmhoQF1dHYB/Wp2fNE4kxsTE8ol8Pl9g2WSzWQSDQYRCIXzzzTcoLy9HV1cXxsbGkMvlOOhN1fexWAwOhwMHBwfw+/3QaDS4cOEC9vf38eLFC7Y0A4EAL37RaiAlOjs7i2g0itraWqysrDC18Pz8PLa3t3Hu3DkoFApMT0/j/PnzbBEEAgEsLy+jr68P8/Pz8Pl8uHr1KisX+h63243nz5/DZDJhf38fXV1d8Pv9kMmO2BgeP37Mlfl1dXUwmUxYW1vjdlFismFpaQnz8/M4d+4c3G43Hj9+DIPBwHxXdI+Hh4cYHR3F3t4eJiYmmMP9pEUsVQRSV+64z0s3KIKiEHo7m80yX5Z4HpVKhWg0itHRUWQyGXi9XvT19WFubg6ff/45c6mLLmOx6y52P7+v5PN5jmkSJ1UwGMTq6iqqqqrQ09PDrJ51dXU4ODhAMBjkDK1YcH2cvPWKym63M2MicKS4UqkUA86o1IQsFSmnUjEFcvHiRa4pA8BmrBicJTnO5C4lYrmMeE4xBkQWldPpxMWLF2GxWPD48WPY7XY0NTVhc3MTy8vLsNlsaGpqglqtxszMDGKxGFpbW1FeXo65uTm8ePEC8XicC4wrKyuZDVK0CkV3i4qDu7q60NDQgHz+iBOdavxOnTqFcDjM1f3AkWuWyWTgdruhVqsxPz+Ps2fPMvhUzFR5PB5YLBZcvXqVMUVy+RERX3NzM/NZaTQaNDQ0QKVSoaysjLOjdM2E0yH4iEqlwvT0NMfNxIVMcZb5+XkmvyMFL82sSudGMTnOaiYR42vi8TRXo9EowuEwKioqCrisysrKcPv2bUSjUbYo6+rqUFtby01rDw8Pi8YhpUpLGqeSXvubzFvCxzU1NcFsNnOvwFwuh4WFBQBHMcetrS3U1tait7cXRqOREyVvIm+9olpcXIRSqeTgc2NjI/dno754fr8f6XS6YDcmkQ4a1VpJcUvSILP4Gel5SolUKVIHWpEXScoLRQuyoqKCoRXXr19HNBrFs2fPuF7QYDDgo48+wv7+PrfHunjxIvx+PzY3N5neRrRGyAUVn4lCoUBdXR2eP3+Or7/+GgMDAwXWB2XqADBSnd7LZrOYmJjA+vo6bty4wbzu5OLSfafTadjtdo4vUgnM48ePMTo6Cq/XizNnznB3ocnJSSwvL+POnTtsKdG1x+NxTE5OIpPJIJFIMN2yVEGoVCq89957bHmL1qt0jEopnpNcvZPcSIqlXbp0CZ2dndjZ2WFLkjjWiUCwu7sbgUAAGxsbaG5uRllZGWQyGYLBIDY2NphNQ2pVHWdlnSTSc4hJjP39fb6HfP4IbEzxT4L7ECuG3+9nsDJx8J8kb72iqq6uhk6ng1qthtvtxtTUFNfF5XJHbaq6urpQWVnJJSfSwQQK8UliQBko5CsqFp86SUpNero24oUCjizE5uZmKBQKblQxMjKCvb09BINBZn9QqVQoLy9nCAA1bXA4HAWgwUAggN3dXRgMBs6sUdMCUcTMGVH8Li4u4ptvvsG1a9eYiiSZTPJzIEiC+JwikQgSiQTkcjkrMSk7gBThT/daXl6O4eFhdHZ2oqurCw8fPmSranR0lBUQ0Y1QsL+vrw+XL1/GwsICFhcXGXlPx9N3VlVVoa6uDpubmzzOxRZyMUuT7ln6+zgXS7opkqVHvR6JIiWXy+Grr76C1+vFv/k3/wa53FFfwpmZGeRyObzzzjtQqVT49ttvsby8jJ6eHty+ffu12F+pkrDj3NfjhD5HgE8q8/H5fNjZ2YFer0d1dTX0ej00Gg3a2towNjaGtbU1Ln4Ph8Nv9F1vvaIidCwNhEajQTKZRFlZGe+wW1tbUKlUbEJLJxDw4yQjS0y0AkwmU0EvQOlkKDaZi71fLFYlWggy2RGSnpSKTCbD7du3EQgEuDCZOMLz+SN+JspkulwufPbZZ5y6lslkePnyJS9c4jYSM3DFUPH5/FFdXXl5OS5duoRAIID9/X10d3ezcqJjE4lEQbJBJpOhra0NFosFd+/eRXNzc1H2hEQigWQyiXw+z12rATD04tWrV0in0/D5fIhGo8jljqhhCB/33XffobGxEX19fQCOmhhUVlYiFAphd3cXqVQKc3NzXGdWV1fHilIspib3upScZJWISRCS46wqCivMzc1hY2MDFy9eZGvV5XLBarVyMkej0aC9vR3Nzc2wWq3I5/Po6+tDX18fHA4HJzCkVtBJ11HqHkutCTqP2WyGw+GAyWSC1WqFXq9HOp2G1+vF1tYWrFYr/H4/LBYLzp8/z9UUIovFcfLWK6qRkREuiTAYDGhtbeUSg2AwCL/fz9w+tGiKmfc0UPF4HI8ePYLBYOD0dX19PcMeRHP4OFcQONk1EK04msginksmkzEXudgxmJRFTU0N8vkjWMNPf/pThEIhRCIROBwOmM1mrpNrbW1FTU0NgCN3zel0shVH56O/gaPuu48ePUJjYyP29vbQ2NiI5eVljI+PY2FhAQsLC9w1eGpqCnq9nkkKnU4n3n33Xfzd3/0dvvvuO/zpn/7pa/dsMplw7949qNVq5odfXV2FVqvF5cuXMTs7i3A4DLlcjgcPHjC9i1qtRi53xHFEmJ7a2loeB7vdzgDgw8NDtrrkcjkvnkwmg6GhIV5oxRIr4ngVE6lFLW409ByloQL6u6urq6DFGc2Jc+fO8fnlcjna2tpeU4QVFRUAfgwRSK/hOMup2L1Ir1t6b/RePB5nMkpS9i6Xi0tmKOsHHLnYiUQC8XgcSqXyDyU0JA6HA3q9HmazGTs7O5xWJ4vKaDSiv7+fMVFEqVIMtS1aFf39/QwapQUiKimplNq9igXbZbKjzh4UN6L0tBSNTBYMocBFJUUThP7W6/Xcdw04msxDQ0Ov1TbK5XIMDg5yp2dyn8iCBIAzZ86grKyM43XNzc3w+/1Qq9Vob29nloa2tjYu/DUYDKiurmYL4OOPP8by8jJSqVQBYDSfz6O3t5eJ33p6etDR0YGysjJ2IT755BOYTCZ89NFHCIfD0Gq16OnpgclkglKpxLvvvsvuLYEec7kcbDYbd5URgakAGIMmk8kKWkuVct/EMRAVgFQ5ScdWfE/8rDg/qDCaxkmcU/QZMQRRTKTK8jgXVPzMcfNUfF9UkgShIc8kFAphf38fMtlRCZPdbucN0O12Y25ujuOXf2D4/EchcjZ6MIeHh4zloULVvb09NkNLKRoRYR0KhRAMBpmNgRQCUBisLDVRSYq5iPQ7Eongiy++QHV1Nd555x3IZDIcHh5iZmYG6XQaFy5cgE6nQyKRYCWl1+sLymSkpS5AYdU7TTKxXIbMeFogIpaLXnM4HLDb7QWWFnUBJpHL5bh9+3bBd8tkMs6oVVVVoaKigusMCSgqkx1VDdBn6bsJswYcxR1pnKS96XK5H7mRpBncYlaNqHDENmPHjVOpmNRxUuw6Ss0TcplLNWigxADFA6l2zuv1Mn7JYrHAbrcXtdxKyXHxK+kzETdNpVKJ+vp6hv44HI4CmiCPx8P1i+Xl5dxazul0IhKJnPjsgH8Biurly5f8UGw2G+rr63kBEkhtZ2engEq4mIKhwZbLjyiMnzx5wh1o6+vrC1zG4xRUqR2YhN4zGAyw2+1Ip9PI548yJjMzM/B6vfB4PACAc+fO4fnz58wn3tzcjIaGBm6gScwBJpOJgZKE1xGBpaLCImUsup3S14tdu9g1hkT8nz4j1vVJawqpJIY+J7X0pNchLcou5t7QOSkbRZAD6iYskx1xfov4NCpal3bmKSXFxvm4WBRdVz5/hBlLp9NobGwEALjdbmxsbCCdTqOsrOy1ZIpMJkMoFMLjx48LnmVDQwNevXoFu93O9L/vvvsu9Hr9a9/9+0gx5SV9LRKJwOPxcKma1WpleheCkpjNZng8HvYQRMLCN5G3XlER22Q6ncby8jJnGerq6rC3twe73Y729nbY7XYYjUYudBUzJuJiicfjcLlcOH/+PNejibinYoyVQPEBLhUvoAXV1NQEv9+PfD7P5Qjnz5/H6dOn8c0336CiogLT09O4c+cO9vb2cP/+ffzyl79k+tfR0VFotVr09vZiY2MDuVwOXq8XnZ2dOH36NGQyGYMDCQ/l9/uZWpjKL+iaSLERayO1ZVKr1cw+Kbos9Dmp6yK6L/RcxdfEDrvEbpBMJvl1ahhBXZez2SwXLrvdbl40FRUV8Pv92N/fh16vh9Fo5JKksbExHB4eMoPEy5cv0dHRgbq6Ojx9+hRNTU38TKRyXHyq2NgWE4VCAb/fj3v37iGXy6GmpgbZbBYPHz7kwPS9e/dgNBoZs0cbpd/vRzgcxo0bN5BKpfD06VOO0V2+fBkHBwd4+PAhj4locZaab6Wu/zhXUHTXI5EItra2AByx0sZiMUQiESgUCjQ3NyMSiSAcDmNqaootr46OjgIlfJy89Yqqra2NO6KsrKxwhkilUnG8IpVKcUv3Uma/aC1lMhluASS6fKVoV6RyksUlTg6aCKlUClqtFna7HTqdjqlLCEhHtWuEAI5Gowz4rKur49d+97vfwev1Ip1O4+DgAPfv30cgEMCf/MmfYG9vD4uLi9DpdIjFYrh06RJqamoKFHUsFsPIyEiB6d/c3IxoNIqmpibIZEd0ukqlEru7u+xeU73X7u4u3yeBU6XFzDMzM5xZDYfDaG9v59gidae5cOEC9vb2OEGgVqtx9uxZLtMYHByE1WrF/Pw8TCYT+vr6uB6QLE2v18uNXScnJ+HxePCzn/0MoVCIqXylY1ZMToo/FpsLmUyGeeZXVlZ4nMmNJ6tX7KBM5yBlHo/HmQrI6XQyieH+/v5r+KTjFGup+5TG0cTNlt7LZrPQ6XRwuVzY2NhAJBJhELVSqeR+BOFwGE6nE93d3ZidnYXP54NMJuPY4Eny1iuqjY0NuN1urvOjUhe5XI5AIACPx4PFxUWUl5dzbEOqLIDCYHooFML9+/f5M42NjQXdhcUdVzrwQPH6P/F/MRZBbhEARk9TPIrcrSdPniCTyWBgYIALbUkhtLe3s/nv9Xo58Oz1evHgwQMEAgG+383NTSQSCVy/fh13797F3NwcczzRdVJtWXd3N7RaLe/cxCSh0WiwsLDAnV4GBwexs7ODp0+foq6uDpFIBN3d3VAqlbwIRZcym81iY2MDFRUVqK+vx6NHj7C4uIhgMIhr167BZDLhN7/5DZaWlpBIJHD+/Hn4fD6Mjo4yVmdpaQn19fVc+0gxHIr5yOVy2O12WK1W2Gw2XtTLy8tYXV2FXC5/ra36SRaUdDxPCliTW0sbjkwmg1arhdVqxfj4OHfkpuSO+B2E5n/48CEikQhCoRCuXr2KcDiMiYkJbG1tcasxcX5J8X4nzT/xPenn6IesatoQvV4vTCYTDg8PUVZWBofDgXQ6jVAoVBDjpMakomt6nLz1iioSifBOFY/HsbOzAwAwm83wer3QaDSor6/n+i+gMFMiui20A9y6dYvpckV+cKCw4eZJ5v9x7iBdsxjoDQaDPBHC4TD29vagUqnwy1/+Equrq9jf30csFoNer8fOzg6XD8lkR8jmnZ0dlJeXo7y8HCMjIwgEAujt7YXb7WYw6MLCAsbHx5FIJJiiQ7wvciNsNhs3bSV3TyTby+WOaFyam5thNpsZv6TX61FTU1NA6CfGnehZ6vV6ztIRKps68FC6myxIir8BP8bKCEdE7obH40F7e3uBGyVeq91uR2VlJSYnJwswcaUK1ElEF7fUmEqF3qdnS/GxaDQKn8+Hs2fPwm634969e/B6vUwsSJxjdrsdH374IcLhMMbGxpBKpeByudDY2Ih4PI6vv/4a6+vrBcq2VFJBOh9L/S/+TXNAVKBKpRJmsxmRSIRjoel0GrFYDCaTCeXl5Ty+fr+/YDN4E3nrFdWZM2eYYXBpaQlbW1vI5Y4IvYCjGBaVIGi1Wub4JhEHmZDW1GdOGmCWKjYSaZxGKsXcS+DHTGM+/yOo9N69eygvL+fGqTKZDC6XCxaLBQ8fPuTgezKZRHV1NWckide6tbUVSqUSGo0GkUgEL1++RDAYZAYEuVzOSk+n0xVkBelafD4fnj9/DqvVimAwyLsmuXDE57Wzs4MnT55w3RkATE5OQqVSwWw2c489MQWfy+UQDocxMjKC1dVVBAIBtLW1YWVlBb/+9a8RDAa5/yKdl56XRqNBPB5nAj8ar9OnT7MFKLrotAHk80dYs8HBQfz2t7+F1+vF0NAQj40USyVVYuLYHSdS65oUr7i5JZNJlJeXo6KigmtIc7kco9VbW1sBHDUt2dvbw8bGBk6dOgWLxYKdnR2MjY1hZmYGH330Ec/xUlJsQ5XOU3FOl3IFtVotN4klAjxKUBweHkIuP2qsQgXLVDxut9tLwiuk8tYrKmpbTo03qUsJ+f+hUAijo6NcsyYuShIxy0T/H7eDSt8rFgMQrbRSgcuamhpGaGu1Wly8eBEPHz6Ez+fDmTNn4HA48PLlS3z++efsQoiFtOTqiKLVarmspKGhAVtbW3j8+DHMZjOWlpbQ29uLgYEB3L17FxsbG8zAQNeXzx/VIJK1RsrQ4/GwoqH6wnw+j8XFRWxvb+PTTz9FLBaDRqNhV5IyfNIAPAEGRdLD2dlZtLa24v79+xgYGIDT6eTsJzWAUKlU7FLQ7k0ZJ+LaAo46uBC9z+HhIYCjioPKykr09PTgm2++YWxcMTkuxljsOPFYqcul1WpZgWq1WrhcLoyMjPB9E5D41atXSKVSDAadnZ3F+Pg4ent7cenSJchkMszNzeHw8BC//OUvcerUqYJ5JZ1vb2LtH+f2iZZmMpnkQmjyTLq6uhCPx3FwcIDd3V0G2u7s7KC2thYajaYkU0kxeesV1crKClKpFJeS0OJVqVSMOdHr9ZDL5QXtxYvBDY7LjryJnORGSIVaY9PEqKmpwSeffMJt0xUKBX7xi19gcXERmUwGDQ0NXHJjNpsLWB2kHVU0Gg3vcktLSwyADYfDUKlU0Ov1r8ER6H6p7RHRt+zt7TEeJp/PczFqZWUlhoaG8L/+1/+CTqdDJpNBfX09UziLz0R85lR029zcDADY39+HWq3G4OAgfD4f5ufnYbFYmOnA5/MVxHo0Gk1BX7nnz58jHo9Dp9OhoaEBiUQCu7u7yGazWFtbQ0NDA5qamrh5BOHspBbycUFz0eqQPjPxPfE+c7kcKisrOcAPAO+//z7zwFMX7nw+j/fee483S5lMhq6uLrS3t8Nms/G9Xr16lbN/Ik21lH1D+rvU/BTnv3g/IqaQPhMMBtlKJK4xavZgsVgKWCiWl5cRiURgs9nYQjxJ3npF1d3dDZvNhkQiwY0G8vk8qqurme6lsbERLpeLi5eLiRgEFeVNd9diUmriS2lexPMTyJSup6Kighs20HEymYwD1gC4HKOtrY2Bd3R+pVKJ8vJyaDQaNDY24ssvv8Q//MM/IJPJ4NatW69ZhKTk6dzkXnk8HoyOjkKtVsPv96OhoQFKpRLV1dXo7OzE7OwsqqqqGJksk8lQVlbGSHma+LTACGNFz0mtVkOr1eLChQu4d+8eDAYDOjo6sLm5CZvNht7eXlaiZ86cYfqQW7du8TjT8xO79mg0Guh0Om76oNPp8POf/7xk1+tiY0cLudjmJkqxOBEV59L7RqORWSXE0ILFYmF3lmhVpOVepFxF5UIU2fSdYmJEvC6xokHcmKX3IQ3My2RHgM/m5uaC5rAejweHh4ewWq1oa2uDyWSCRqNBV1cXHj9+jEAgwFQvbyJvvaJKJBKcCq2rq0NDQwOAo1boh4eH2N/fx8TEBHQ6HTMnSP1yqbKQ7pDie8dZWMXcPPH8ovWUSqV4sUjjZCIMgtwbsX5MJpNxZkjMzlBLLPEcBoMBp0+fZpZQijeZTCZUV1cXxHPkcjkMBgO6u7s5lieXH/FenzlzBoeHh1AqlTh16hSam5txcHAAtVqNS5cuYXZ2Fna7HQ6HA7u7u3xOap1O1y2Xy9Hf38+KJJfLwWq14uLFi+wSfvjhhzAajbhz5w7Ho0iIhoYWcXV1NWPjqGgZAPMl0feKYF8KzBfbmEqNa6nXpC6UWHpSquxKBL+Kn6HzSUGxYiUCvUbXLpY+0b2SsiNyRNogirm6peKt9OzIiqqoqMDh4SF3uaY2cpQlJv50v9+P2tpatLa2FmSUT5K3XlEtLS0xBqmhoYFBneFwGMlkkt1B4nEWM3jFFJJUpEHGkyyrYvEq8Twy2VGpzKtXrzieZDab0d3dzVS+Wq22gO+7mIsmll6IIs3YUKCeFgMhpGniSsn7VCoVurq6CnZWuVyOK1euAEDBxHM6naxozpw5wxaWqDiKgRHpGuj6lEoldzcBUMADLi58ev4ifQzdSz5/lEUVXSJxUZfaaERXrtimVczVk8ICis0hMYZGGTBSImJpjPQ+qaRIjMVR6IIyo+T+iaVdYsF6IpFAKBTi2kipC1hK6B7EDC1w5F5PT08jEAiwxU5tv6hgmSwq2hyJ/YL6J54kb72iam1thc1mw8HBAVZXV5nY32azcSfa06dPw2azFfj2UpGaxcUUktRNEj9X6pzSYyio6nA4kEqlMDk5yQt1bm4Os7OzUKlU+MUvfgG9Xg+Px4PNzU2Ul5ejpqaGlUs4HGbSvUwmw3gXMWYhTjayumjyi4tanJhSemQA3BGZFhRNerFfICH2paBacdcXlQe9Lj538dykbGlHp6CuaG2Qi0yvU+WAyEMvjUGJLpc4rm/iygE/xm9KiahQCZyqVqvR2dkJ4CimOjs7i3w+j7a2NnR3d792vaFQCI8ePUIsFmNLub6+Hk+fPkUwGEQymURfXx+GhoZYSQPgLOOLFy8wPDyM/v5+nD9/HgaDoWAeSN1a8bd0vgJHm1NVVRXC4TA2NzfhcDiws7PDwfWmpibGrDU2NuLJkydYWlritfcm8tYrKtLiGo2GUci0ixLg8+nTp2yu0iIBfpxUpcz/44Kn9PnjjqNjxB9y2wYGBhCJRLC9vY3y8nJ4PB7MzMxgYGAAw8PDGBsbQ3d3N+7fv49EIoHh4WF8+OGHKCsrw8jICJaXl9He3s4u0+LiIkKhENra2lhJB4NBVtakKGihi9AI8T2xJlDaa0/q2tK5RBGPFd0Y0aWg7xLPT+DHVCrFFC6Hh4cMZ6ioqIDb7eaNSC4/Yl7Y2trC7Ows5HI5mpqa0NfXx3GxYuMpxoWkG1MxZSUGqsXf0rkgnoOeo8fjwf3791FXV4euri4kk0nMz89zPO3Zs2dwuVyoqqoqmEO7u7twu904c+YMotEolpaWGE1//vx5LC4uYmJigiEZ4lycnp7G6OgoampqMDMzw2U30nER52OxDRgo3MDq6uoQi8UQj8e5YQfNIwJV19fXw+fzwWq14tSpU7Db7cf28hPlrVdUIyMjHIwlYCdZCtQhBfgRvSz691IppniOU0LiZ0hOciVFWVtbg1KpRFdXF7a3t9kFVCqVmJ+fZ6Xx4Ycf4uuvv8bS0hLKy8vhdrvR1NSE6elpblT67Nkz+Hw+LCws4Oc//zkymQy+++477O/v49KlSxgcHEQikcDc3FxBQFe8bplMhkgkgqWlJZ6kjY2NsNlsSCaT2NraQllZGaxWKxdPU4EvuYEWi4ULVPP5PHMo0bPKZrNYWFiA3+9HPB6HSqVCdXU1QqEQ+vv7EQwGMTY2xsh2l8vFbvve3h5qamrQ3NzMsTO73Y5UKoWDgwN0d3czPU2ppEgxkcYtxdfEY6R/S1+j/+n7Vi2TTQABAABJREFUq6urMTg4iGAwCJnsqOXUxYsXYbPZEIlE2DoS3Xiydm02G9rb23F4eIidnR2mu2loaEA0GsXOzg4XYoubwNbWFpqamnD79m08evSIKYQBlLSqpM9H+l4oFGJrzmazMVi3srIS8Xgcu7u73LGIsq9Ug/um8tYrKuqCsr29jc3NTczPz0OtVjPnT3V1NXp6epg5Eyid4SMptsMUM5GlfxezuorFOsgt2N3dRXV1Nex2O2e3NBoNnE4nNjY2uJjYZrOhs7MTGxsbiMfjqKmpwbVr15BOp5nB0+Vy4d1338Wvf/1r7hun0+nQ39+Ply9foqqqCjqdDmNjY3A6nWhsbOSehVLX7/nz56isrITf74fP58P58+fx8uVLDA8PQ61W4/3334dOp8P6+jrGxsbQ2dkJtVqNjY0N1NfXo7OzE9vb24jH4ygvLy94jtFoFFNTU2hubobNZsP6+jr29vaYnyqVSjGVsdPp5FbsZH1RXznKTMrlcu5/53Q6+Z6OG0upSyy+LpMVVvxLQwFvqsAolma1WhGLxSCTHcEqamtrkUqlsLa2hkAg8Fqwmdzog4MDPH36FHt7ewgEAuju7sb4+Dg+//xzLC8vc0GyOO+oVjIajWJlZYWrNkTLVirHzWf6HHWZ8fl82NzchNFoRDgc5qSJ3W5nAKhMJsPS0hL29vYY5vIm8tYrKlpoOp0ONTU1cLlcUKlU3BYqGo1icXERVquVd3eKUxSbwG/6naX+Lha0FV0O+j+fz3PhKsUZaIcNhUKIRqNIp9MwGo1sMdICMplMUKvVcLlcjHHq6OhARUUFamtrsb+/j0Qigfb2drS3t8PtdmNnZwdDQ0Po6elBMBh87dpIKLjf1NQEr9eLQCCA9fV1bG1t4Sc/+QkmJibw8OFD/Nmf/RmuX78Or9eLU6dOob6+HisrK8y1RDTQYokOAG6Amsvl0NTUhPr6eszPz2NlZQVLS0tYW1tDKBSCwWDA1NQUotEoA0/D4TBGR0exv7+P2tpapkghxSONRx3nrhdbtPR5abD8JJG6UuJ1SF3GVCqFxcVFjI6Oor29nfm2xO+rrq7GwMAAwuEwW57Nzc3Q6XRcTC3G8sSfbDaL9fV16PV6bGxswOVyFXx/qXgcidS1pz6Op06dgkajwdTUFFQqFcckySggN7C2thbRaJQBn39w/f5RqG6NGoba7XamJaFdjOrGxBqv46SYkhFfly6GYruqeA6pgqIfsXbO4XDg+fPnGB8fh9frhdFohMFgwObmJnp7e7G3t8efC4VCSKfT3EiB7pUyLvF4HLncUWMLstAooG02m5l1sZRV6ff78ejRI4TDYQ6ikhuoVqvx8uVLvh+DwcBA2mg0irGxMUSjUczOzqKysvK1hWE0GlFfX4/JyUmsrq6itbUVmUwGoVAIa2tr2Nra4i41NpsNNTU1XOqj1WpRVVWF+vp6plqmgDtZLUBh27FS4yodW/H/Yq6d9DwnbXJkpZLlRxvT5OQkHj16xIFuAt4mEgkAR6UzRqMRFy5cQCAQwN7eHoxGI8rLy1FVVYWtrS2MjIygra3tNWuM0PuXLl3CxYsX8ezZM+zv70Mul/McKbZBS5+VOGb0bEdGRuD1euF0OqFWq1FeXg6n08mNaQlYu7+/z+EMup83kbdeUel0OhgMBsRiMUxPTzPuRqVSIRwOc6dfEY8jxpGOm4zS/4sFk0WzmgLQdN5i7h+JUqlEa2srTCYT41Ta2towMTEBvV6PK1euQKvVYm5uDr/73e8Qi8Vw6tQpZLNZzM7OYnl5Gbu7uygvL+euIPX19fB6vTAYDEgmkwiHw0ilUmzZEFsDTVq6JlFhER9UTU0NNjY2cHh4iEAggOnpaeRyOUaoi/dNMATgxywfNW0QS2ho4V66dAl9fX149eoVnj9/js7OTrS2tuLWrVtYWlrC2NgYgKOOPMQLTyl9h8OBlpaWguym9B6OiyWeFIc6SUlJ3ysVk6RziZnOcDiMBw8eIJFIwOFwwOfzMcf43bt3odPpcPv2bWQyGWxtbWFychKBQADvvPMO849NTk7CZDLh4sWLBa4fjQO1YCN3LRqNvmbpF1NWxa5fTKp4PB6EQiHmD9NoNPD7/bzpid7K1tYWUxV3d3cf+z0kb72iOnXqFGpqauD3+7GwsMDBQ+qebLVaUVtby0hoseK8lIjvFXPtREuKgJti/EmMB0iVongcEbfRTnjlyhX09/dDLpfDbDZDqVTivffew8zMDJqamtDe3o58Po/t7W08fvwYZWVl6O3txe7uLr788kumYe7v78fS0hJGR0cZ59LT08PKRFSw0ngNBcd7e3vR2NiI+/fvI5c7IkG7cuUKu2d0H2QJAEcg2/b2dvT29jLXvPjcACAcDmN4eBgtLS2orKzE7u4uZDIZ44KIrJB6BFK8ymazIZfLYXR0lLsEt7a2oqqqip+/+Gzpe8WxErOdpcb7TTauUvNDHG/6TrPZzJ1YZLIjtH4mk8Ha2hpnyGjzIMWTSqWwubmJXC6Hn/zkJ2hsbOQuRKdOnUJrays3qqBrIYgK9fvLZDJobm7m+lZxToqbbam/xXvRarU4f/48tra2MDMzw8wiq6urUKvVqK6u5oYhbW1t3NwBQAE543Hy1iuqg4MDpnOprKzkzrpyuZytAbfbDZfL9doOJIp0cEoF0+n1VCqFmZkZLC8vo66uDoODg1AqlfB6vfD5fJwVAX4sqiUXoFhMg4KoRPlB39nY2IjGxkZGGwPAzZs3cXBwwK2LjEYjrl+/jq2tLZw6dQqNjY0wGo347LPP8OLFC7S1tTFCXHRFpEoqlztq6Lm3t8ctq0wmE0wmEyPCiZCPngVR+uZyR330CMSqVquLWrByuZwDxHq9Hm1tbaiuruaFWlVVBaVSCZ1Ox4R5cvlRgfmVK1cQDoeZZkSv1yOfz6O2tpZBrXQf0oymiOwW5Tirt9hrxeaCOJ7i+/l8HjU1NaisrIRCoYDRaMRPf/pTnn9knchkMrz//vt8fpVKhcHBQX5eZImeOnWK8XLUNEMMK5BlTtdCMAhSYmJcS/wtgnLF+6D7y+Vy2N/fL2hBbzabMTAwgEwmA7/fj5GRETidTu741NXVBbVa/Qc+KpLDw0MecL/fX8CNnclkYLVaUVlZybEUmlSlsiBSKTaAVOxKQfrh4WHodDpUVlbi2bNniEQiSCaT+OCDD1BWVobR0VGsrKygoqKCC0v39/dxeHgIu93OCzUajbJ1ITb2zOcLOcdJeYgKbmhoCKdPny7IhP3FX/wFwuEwLBYL3zvVPIqTkEQmO6pFo8CpWq1GXV0dF3jn80dwg97eXsjlcuh0OnR3dzNpXU9PD8MDqN0TjQcpRqPRiE8//RTJZJKtKIrVUVKkqakJuVyuIBCcz+cZ5SxuJtQBx2g0FixE8Rjxp5TLX8pdfNOYZjElRYqcLMR8Ps+lQzQ/gR8VCf1N7ezFKgO5XM5jKAXlisfQXCFAr2hxSRWq9PqLKelcLsd8/ul0mudFNBrl8aUNkLKzXq+XE0IiO8dx8tYrKmprFY/Hsby8zNgeKjkgfxr4sR018LrldFxAXATK0f+bm5uorq7GhQsXYDKZuGI8Go3ixo0bePbsGV6+fInm5mZsbGygqakJY2NjqKioQGVlJR49esSZvU8++QTxeByjo6Nsed26dYvTwKlUignyKF5DMQkxdU/ZQ4qLGAyGgppA4konPJkYW6N7tVgsuHnzJt+niEkDjtw7QlnL5XK0t7fzc2lqauLnJhZSk9Bz1Ol0bBXReaQJB1JcYpccel9clKL7I46fOGalsrx0raVeL/a3dK7Q+1LrmO5XtFbIYhXHi+5NLFCnxARxw1PD0a2tLbjdblRWVqKqqqpo/V4ul+Pi4d7eXo7xibFCqUKSrgk6Dz03jUaDM2fOwO12Y3V1FbFYDHa7HQsLCwiHw6irq0NnZycMBgMqKyvhdruxtbWFeDz+hwakJCMjI2xilpWV4fTp07wb7e/vM5WrGOwVJ61UWRULjkoBeRSbqq+vh0ajQUVFBTweD+LxOOrr61FTU4Oenh68fPkSW1tbsNlsOHPmDHK5o1bdoVAIarUad+7cwZdffomxsTG0trbCbDajvr4eDx48wJMnT3Dz5k387//9v+H3+/Hv/t2/g1KpxPLyMgMyKyoqMDg4iNXVVbZGjEYj7HY7x3by+aOyFmrKSi6kdEcWlYWo/Oj+6d6pTEcmkzGJn5TWl/6mz6ZSKbYSZDIZwuEw3G43jEYjampqIJfLsbKygpWVFTQ1NbE1try8jGg0iv7+/tespGLBcboP8T0ab/F1UYrNA6l18abxKVGkygs4sv6/++47znIqlUr84he/YHwffS6VSuGHH35g2uSPPvoIBoMBn3/+OVPsfPDBBwzaFa242dlZfP3115DJZFhcXOTjirEnFHsO4nOkjSqbzaKqqgpqtZo7iRMrBFnai4uLnKnW6XTo7e2FWq3mDe4keesVldi9JJlMcnA2n88jHo/DZDIxFkmEA7zJTkpSLEhLDSTI7KZzE90x4UuI0ZGI8D0eD2KxGFpaWuB0Opn8v66uDjU1NVCpVFhbW+NmFP39/RzQlslkePbsGZeLfPvttygrK4Pf7+cuNpubm/jVr36FiYkJnjiVlZVoaWnB1NQUkskkZDIZysvL0dHR8doCFi2Wvb09+P1+aDQauN1udgOo8/Lq6ip2dnY4jhaNRjEzM4ODgwP09fVx5vDZs2fw+/24desWd4RZWVmB3+/Hz372M1itVjx9+hRqtRqff/45/uRP/gQ1NTUYHx9HOBzmxg3FFIaoCOjaM5kMxymlLm6xzUhcwMcpn2LzQ7rApecRn2c8HueuLQT/IIoake55bW0Na2truHjxIiYnJ/Hq1St21z/99FP88MMPmJ6eZgtWLC6fnp5GT08P+vv78cUXX2Bzc5OPO+m+pC4ybUCUrTw8PITZbOZET3V1NXK5HHw+H6PTyeLP548617xJMTTwL0BRnTlzhvmoFhYW4PF42GpIp9OwWq3Q6/UFILXj3ABRpEpNjAkRIV1zczNWVlb4+w4ODpBOp+HxeDjoSan1aDTK3WMpoE0+P1krMzMzWFhYQE9PD8dlqJMHYaMODg5gNpthNBqRyWRw5swZyGQyPHr0iMkCfT4f+vr6ODZ3eHiI0dFRnDp1CqFQCF9//TVcLhdsNttr9yuTyRCLxfD48WOYTCYmcAsGg7h79y7DD549e4ZUKoWxsTH8+Z//OTY2NjA/P49sNovf/e53+OlPf4oXL14wQeDDhw+RTCaxubmJ27dv44cffsDY2BisVis0Gg0+/PBD/PrXv8bU1BRqa2vR39+P6elp5lEvtrmIikihUCAUCnE8h8ZOan1JraXfNz51XJxLem5SUoScv379OndpuX37NrMRiHNyZ2cHFRUV6OrqQj6fx9zcHCKRCNrb21FXV4fGxkb4fD5sbGxgbm6O2UN6e3tZSdMcE1tqiTCRN7lXsS60vLwcqVQKXq8XyWQSSqWSW5VZLBZUVlbCbDYzc+r09DQODw+Zi+skeTMe0P+LZWtri1O9VVVVGBoawrlz5zAwMICWlhakUinMz8+z1fUmuyaJdHek3wqFAj09PZidncU333yD3d1dNDc3w+l0YnV1lX+qqqq4TMTv98PtdnNPvr29Peac1mg0SCQSmJ2dxaNHj1BTU4P+/n5eVBqNhieTWq3G/v4+vv32W8TjcQbgxeNxbG1t4fLlyygrK0M4HOasZCwW47hWY2Mjent7WclJ43Eky8vL2N/fR3t7O+rr67mlent7O/r7+zExMYHa2lr88pe/hE6nw+TkJGZmZtDT04P333+f+yymUimcPn0a58+fRz6fx+rqKlwuFxoaGjAwMAC5XI5IJILKykoYjUY0NTXxAhM5xKTWSrExpK7SlIiQKinpmBb7OS54XkwRkTIq9n2iYsznfyQH3NjYYIVKG5Y0S0kULeQuU6yIspeUVKmrq0NLSws/t3g8jsnJSTx9+hRra2uvxWWlP+Kzkd4Xva5SqdDZ2Yn+/n7U1dXBbDbz2Oh0OqZV2t/fL7iujo4O5oc7Sd56i4qwHCaTCRaLhVuwkytoNpv5dXIfpAHkkyaoKJR1aWpqwtDQENxuN+90qVQKCwsLePbsGUwmE5qampBOpzE6Oorf/OY3SCaT+MlPfgKfz4cXL17A6XRia2sLzc3NmJubw8OHD9HW1oZr167BYDAgn88XxHay2SwODw9x9epVWK1WfPXVVwiFQlyoTFzWVNSazWaxsrKCxcVF3L59G9FoFF9//TWy2Sy3kJJW1MtkMnbh2tvbucN0OBzG4uIiOjo6uN9hXV0dysvLUV9fj1gshlwuh+rqajgcDlRUVPBOT2hraiVPkANx4ZHrTEpXJvuRlrdYsJf+Fy2WeDzOXORSOcllK3VssY1Keqz4vtT6FmN/dO83btxAOp3GxMQEenp6uBWbmCQ4ODhAJpNhC12hUGB3dxfRaBR7e3vM3FpRUcHfFQgEeA60tbVBo9FwNQYp099nntN9RSIR3L9/n3mnHA4H5HI5GhoaUFlZiXA4zBRLBKWh2OObGgVvvaKiDh3hcBhLS0vw+/2cTclms2hvb0dlZeVrjRCKTc5iwWD6WzrIMpkMly5dKqAqIfclGAxCp9Mx/ujDDz9kC8vlcsHhcGB+fh737t1DU1MTmpub8fnnn2N9fR3V1dVYW1tDU1MTt2qnBUC7Y3l5OVPDUulIIpGA1Wplut2PP/4YTqcTkUgEX331FUwmE95//30cHh5iZmamgNuJ7pkW1eLiIuLxODo7O5lzKhKJIJvNFgRwM5lMQflOOp1GKpXiNmDUGSeVSnFCQ6VSYWtri3dgeqabm5sIBoPY3d3l7juZTIbBheIY0d903dlsFn6/v6CXYCmUunScpfNBqqSKyXHuIvBjPIyeJ/0fDofh9XpRVVWF7u5uPHv2DPn8EeHfxsYGd3ouKyvDs2fP8Pz5cywsLLDr/eDBA3z99dfwer2cmaX7p+8mrny73c5F2qXmcCkXttgmTsXiZABks1nEYjFsbW0xSJhibbSpER3xm8hbr6iohk+hUKC9vZ13jlQqhUgkwgBG6vZRDAxI8qaTVMxoST9PAWxRAVBbcdppibfb5/OxJXju3DnYbDbIZDLs7OzAZDJBr9dzt2SyMPR6PZ4+fYr9/X2mSclmsxyLUCgU3F67vLycWx3J5Uf8TZFIBIFAgIP9pGTo2sLhMObn59HY2Mi92uj81AWH7nV3dxdOpxNerxf19fXY2NjA2toad6ZuamrCzMwMpqam2NppamrCV199hUePHsHr9aK9vR1arRZffvklvvrqKwQCAdy5c4c3Fqm1R0qCni8pRMJT0fXRPUnHs5iS+ucS6QIXsUsy2REh3rfffguXy4XNzU3Oxvr9fnz22WcYHBxk0HJDQwOGh4dRWVmJ/v5+6HQ6eDwe7OzsoL+/n+l9xN6QKpUK/f39cDqdkMlkaG9vL0hCiK7eSdaVeKzFYsHFixe5hnN1dZWfu9frRXl5OVpbW9He3o7q6mq+/83NzaLWbTF56xXV8+fP2Xohn5kWFLkYBLoD8HubwMcJxSdEEXEzIlJa/L5cLge9Xs/uHQB0dHSgtbW14HiZTMZxLrISb9y4genpaYTDYXR1daG2thYA+FxKpRLJZBKPHz/G8vIyTCYT0uk0MpkM5ufnMTs7C7/fj9OnT3M2lL4rm83C7XYjmUyio6ODA6NyuZyhCOSeNTc34+nTp5w0IJfzxYsXzOLQ2dmJvb093L17l7nQa2trsbu7i9XVVdTX16Ojo4Pr/7a2tnDmzBmmJSYWh+N4tylAbDabuUyqWMyFfpdSUtIEy3Gu4nEiPYdoAVqtVnR3dyMej6O7uxstLS3QaDQwmUz46KOPGCxrsVjw0Ucfca0qcaxdu3aNrVKK45EQALe5uZk3H9poRDdUvE7p9R33zPb29iCTyWC1WtHY2MigY6qznZ+fx+7uLq5cuYKFhQUYjUYMDAxAJpPhwYMHJz63t15R9fX1oby8nOMqPp+PJ6tCoUBbWxsqKioKENDAm088kmKTuNguXcq9lE6IYrEPMYZGr9N103sOhwNXr14toB8GgIaGBlYmDocDly5dwubmJqODzWYzlpeXIZPJcPHiRTQ1NTFgULRO9Ho9N4EQrU+Hw4FTp06xK9HX1wcACAQC6OzsREVFBc6dO8fWW0dHBwwGA9555x1Gutvtdsjlcly9ehVnzpyBSqXiHffChQvM8knP02w2v4YVkmauyO2geJYY6yk2VqIUe+2kTB+NsTTuU+xz5L6SaDQanD17tsA1JJrntra2gnlhNpthMpkKQKPSygrxfun7KeQhXmex+Sq9L+lcFZVbOp3GyMgIAPD4UqCfGqxSVpaKr3d2djhc8CYiy/9/Zef+H5ZQKASLxYI///M/59RpMBjk5pgETJPJZKipqcG5c+fQ19cHq9XK1snvu0sWUzbixBEnsPgZ8X9yS+k9GnRRWUgRxGKpAokUqS1OVPpb+jopMoJD0PfTsRSUFhHppRDjYkmPWEcnxuzEBSN9fsUWkHgt0u8Uv5uuPZVKcUtx8Z5KWVTFpNgCPUmk80BqsYgxI+owTTFGqesp7SAjtXREd1cc11wux4qCXhNjYlR3WcyKLGVFSZ8BKUifz4e/+Zu/AQC43W4sLy+jvr6eG+RqtVo0Njaira0NjY2NcLvdGBsbw9LSEoxGI3frPo6b6q23qMbGxmAwGGCxWOB0OjmuQzstTRR6HfjRZStGlVpskksXi/QYMVYlXXz0eVpghDvyer1MSjY4OAir1YqdnR0kk0nU1NQwkhwAA0qLXRNdszihxe8XlZGUZYCOkyoQEX0ufU9UaGJ6nY6R1k9KlY3UgpO6zjLZUQEuKVV6vlLlTwqf0uNiLEZ8PuJYHaeEjnMLix1b7Nx0nXQeqUIX3TVp+EGs08tkMoz4BsBsCAcHB4hGo8zLRXNbfDaEYfJ6vTh79ix3KxarEKTPm66nWOxWqVQikUggkUjAaDTCYrGgqqoKVquV2TuIk8rv98NsNjMw9NKlS1CpVMxfdpy89Yqqra0NFosF8Xgcq6urPMDEWNDR0QGn08kDQRNSGjs6znw/aRIfFwMR/ycTubGxkTFXz58/Z5qaZ8+ewev1oq+vD9evX0cgEMCjR4+QTqdx48YNzuJtb29z5xq6ZqprlFo80olItXNSV0a8fmljVHJhKAZGC09ai0fNSkmJiH0LaWFStX0qlUIul0NVVRVCoRDHFyk7mE6nkUgkOOZmt9sRCoWQSCS4mDmbzcJqtRZwbolZrmLjKXV/jotLnSTFnqFUaayurqKsrIwbbszOzvIm1dXVxWwZ1EEnlzuqIx0ZGeFA+7lz53B4eIjp6WlYLBbs7+/jxo0b6Ozs5HGl8Xj16hWGh4e5395PfvIThpOI13ucJUnH0rhSWAU4Sl6Re57NZjmznUwmEY/HGeQcCoXg8Xj+UOtHUl5ejrKyMragiB+JupmQ20QuEbkltCClmbtiZn2xnUg8RjyOXpcuAJnsR1xQZWUlcrmj7iqdnZ0oKyvDkydP4HK50NraiocPH3KtYCAQQDKZxFdffYVf/OIXmJ+fx6tXr5BIJHDt2jX09/djY2ODkwrvvvsuNBoNIpEId7Wtra2FTHaUpdnf30dVVdVrViAttI2NDaZx0el06OjoQD6fx9raGvb39zE4OAiFQoHR0VH4/X7GSNXV1SEUCqGzsxOpVApTU1Po7e19DcdDi1Cr1WJ/f58bmzY1NaGlpQVra2s4PDxEKBRCPp+H3W6Hx+NBb28vXrx4wbgyvV6P1tZWjI+PY29vDzabDQ6Hg7soF1t4x204pWJZpdxIcU6IlqEYS1taWsJvfvMb3L59G3a7HV6vF7Ozs6ioqMDm5iYikQjeeecdnhe0wUxMTAAAent78ezZMywtLTFv+qlTp/DDDz9wWEO0ciORCKampjA4OIiamhp88803ODg44MoAaR3km8xv+qmpqUEikUAkEmHkfC6Xw9TUFHP2U1ccg8HA9EpvqvzfekX1/PlzmEwm2Gw2mM1mxhJRuUoul2NzmdwUabBVNOWPs6ykUiw4Wcz/FycUve/3+zExMYHLly/DbDbD6/Xi0qVLsFgsmJycxPb2Nvb29vCTn/wEFosFf/VXf4XNzU2Mj49jaGgIgUAA33//PWpra/H06VNotVqsrq7iu+++w/Xr1/Ho0SNeDB9//DFaWlowPz+Pb7/9Fv/qX/0r5hWSTtjFxUUsLCygtrYWMzMzcDqdcLvdGB0d5bZIP/vZz2AymTA+Pg4AOHv2LHw+H5aWltDV1cUTmHi+xUWysrICk8mEq1evYn19Hfl8Hvv7+ygvL2c6mUgkglQqhVu3bsFsNjM2KxaL4fLly9DpdAgGg6irq4PdbscPP/wAtVqNpqYmtkpEl1Q6ZqWsi+PGWPq+GEej3+LzVCgUqK6uhtVq5dd0Oh2uX78Op9OJ4eFhrK6ucsmL6C4mk0mUlZXBYrFwtpo23r29Pezu7hZQ9dB1UnxWp9NxTJM2aamlXOyZiCI+I6VSiYGBAWg0Guzs7GB6epoZRMU6VjpHdXU1otEow202Nzdf+06pvPWKimIqfr8fKysryGQyzAseDofhcrlgtVpfyz6Iu+BxvrsoxXajYjGhYp+Rfm5/fx9WqxX19fWcOSFohV6v5/iL1WqFWq1GbW0tgsEglEolGhsbkclkMDExgbW1NUQiEdy6dQsdHR343e9+h6qqKqyvr+ODDz7A+Pg4Xrx4gaamJra0qGhUeo1y+VGXF5vNxsXSgUAAk5OT6O/vh81mw9/93d9hd3cXvb29jJoeGBjA6uoq0uk04vE4gzTF+JNoMayuruLg4ADt7e1Qq9UYHx/H9vY2amtrEYlEmF1gZ2cHMtmP/FzAEa9SKpWCw+GAVquFxWLh1uE1NTW8KEvt5NKs7HFxq2LjX0y5S8cZOFJUNpuNM50AYLPZYLVa4fF4MDc3B6fT+VrsMZfLMSDY5/Ph5cuXOH/+PJqamuB2u+HxeDA7O4va2tqCxAU931AohJcvX8JoNGJrawt9fX0F1y1lWzjuXul5RSIRPH78mAkNyf0zm80coyJrkSiXqCnHm2b93npFdfr0aVRVVSGVSmFjYwO7u7s8wVtbW9Hf34+ysjI+vtTELGUJiX9LF7d0RyO/vth5xXNTUJ3AqrQwvV4vrFYrQqEQx3IoTkMcRbQrEjc29VozmUxQqVQoLy+H1+uFy+XizsrfffcdU9AQ8FQU6XXNzc3B5/PB6/UiHA4zsNRoNHLDBmIpoJR5KpWC2+3G/fv3EQ6HEQgECp4RxbJ6e3txeHiIu3fvorKyEkNDQ9yYM51OY35+Hg0NDYjFYnjy5AkqKytRX1/PlCIPHjxAPp/HxYsX4XK5CrooF7unNxlzqTVU6jx0bKkxFf8XA+iia7e0tIRnz57BZrPh7NmzHMcTs6Tnzp1DS0sLvF4vxsfHuR9gMpmE2+3G9vY2M5rSd9E9WK1WXLp0CVarlal+6D2p6yeN0xXzAui5EPlfLBZDMBhkHCB1HrLb7WhtbYXdbofP50MwGOQKhzeRt15RUf2YQqGA3W5HLnfEQyX+H4lEEIvFimaRjsuCSCekmNURg/HiJJA2HRBjCCRi4JnAny6XC48ePUJtbS10Oh2cTifS6TTW19e5N5zBYIDf72dWU0qDx2IxZDIZrpgXaWrVajUMBgOjy4/rxEP3QxQ0+/v78Pv9iEQiHFfa3NzExYsXeXcmFyufP8L+UO2ZWJ8o7uA2mw0ffvghDg8P8c0332B4eBgajQYdHR0YGBhgziybzYbBwUGmJqbALZUg1dTUvDZWxSypYjHHUvJPDaaXciXp3mnOHBwc4KuvvmIXkNg+g8Egx31sNhsrl/X1dVYA+fxRQfezZ88YKCsVmUwGm80Gp9PJNXkii4RUMR3n7onHGI1GdHV18fybmZnhOU+ZR1LGBBdxOp08L91u94nP8q1XVETfSz58OBzm9HY0GkUymSzA2RwnJ7ltomKSBqJFN1IavxAVI71P/c8oE3j58mXcu3cPy8vLGBoaQkNDA3p7e/G73/0ORqMRfX196OjowNTUFH744QeYTCamMZ6ensbs7Cy3z9JoNJifn8fBwQHcbjcrFbJqpIFf+pusJGKhODw8RDqdRnV1NYaGhhjlTvcjghnT6TTKy8vR1dXFVp34rOi+x8fHkUql0NzczBk7sg7tdjvKy8uxvb3NiwA4WvCUJczlcsy0QNYrxSSliur3cetKBZSLWRuljpPGv8gSIWVO5ID19fUYHR1FQ0MDenp6sLe3h2+//Ra3bt2CzWbD9vY2vv/+ewDABx98gPr6erjdbkxPT8PlcuHatWuMYhfnldFoRE9PD5dwDQ4OMimfCAkp9WyKKfl8/qiBx9OnT6HX62E2m7lUiZqAxONx+Hw+7nBNxI3U6OHhw4cnPv+3XlGp1WqYzWYkEgnEYjHodDrYbDb4/X54PB6YTCaueZNaOsUUk9QkFk1gqYJKp9McYygGVhQnkSi5XA5Op5PphTOZDGpra/HJJ58gnU5zOQjhYHK5Iw5yk8mEK1eu4OnTp8hkMpzdaW5uxt27d2EwGHDp0iXum/eb3/wGMtlRyyKdTseLWVRU4j0RSHZlZYVdPrPZzPAAepYUByJ3EzjCaNECUSgUsFgsr5W+UDzx5cuXWF1dRSKRQHd3N5LJJLRaLXK5o76EFGMcGRnBysoK9Ho9dximzjQmkwlDQ0MoLy8vAJRKx7CYZSy9puPkJCtLGh4Qf+dyOdTU1HBQuaGhAZ9++im7TTabjWNrn3zyCR9XUVGBd999FwaDAWVlZcjnjwrR79y5wzWg0s2QLHOxptTlcr1maZZSyMWeBYUycrkcs2PQvAeOvJlgMMhMHBUVFbBYLJDJZIhEIpidnUU4HD72+ZG89Yrq2bNncLlcyGQy0Ov1qKiogMvlQjAYhNvtxuLiIvR6PU6dOsWfOS4OJUqxwc3njzBaGxsbmJmZgV6vx/nz57nmyePxQK1Wo7Kykj8nKixx16UFT64rDTLhk3Q6Hc6ePVug9FpaWlBbW4t0Os3lDNeuXeOauNraWmi1Wrz33nsYHh6G3W5Hb28vlzxQQ0+p0DVVV1cjm81yh5ja2lp4vV4GzJ46dYpBhJ2dnVx4W1dXh7KyMg4inz59mt1M8fn19/ejvr6e+bHIqiKro7OzE83NzYzNAX7En506dYopoGUyGXehaWxsRCqVOtZakCqr4xaseHwpK6PU94jHKJVKdHd3871VVVUVKFYKFej1er4XKiOi+CL96HQ6HjfRtRfvWcTIiZusmO0rleErJqTgDAYDent7UVtbC7/fj/n5eabT9ng88Pv9aG5uZk42hUKB+vp6Tv68ibz1JTQUTCe/nmIjlEnTarVoaGjA1atX0dDQUNDCieQ4n51+i5Nzb2+PqXPdbjeam5tx+fJlzMzMYH5+HqlUChcvXkRHRwe8Xi/jYs6fPw+j0YhYLAav1wutVssDS92NiS5GXExiVkec5LTDiZzl4j3Q4qWMmVwu58C4tJWVuDOL56KJLpbIUDxCWiJTTCGLypqsLRJRiRcruaHYVD5/lHqfnp5GdXU1ysvL+TjRKpT+vImUCoZL58BJUmyTEy0ZukaalzRupHDE+6DNkLq+0LMnAkSLxfKad0DPI5fLYXt7G9lsFtXV1QXQB/GZlVLmUgWuUCjw8uVL/If/8B+4g1E4HObzx+NxxGIxpFIpbG1toaOjA01NTVhYWIBWq0U6ncZ//a//9Q8lNOSvezwezMzMwOv1IpfLMYJ5YGCA6V7F2jSSUm5BsZgDHUM9zi5fvgyPx4OnT59yY86+vj721y0WC1Pp0uS5cuUKXr16hfHxccjlcty+fRt1dXWMncrn8zh16hSampoYYkHUMcBRTC4Wi0Gj0cBgMBRMeuliI7dMFAJDSktXSGhRiHE1sRMyoZXpe0XgKOF26DPixBcXltgSij4rIt/pcyIXF3U0IcZPcZzeVJm8iZxkMZV6r9TrojV8cHCA+fl57mJNTV5FCzuXyyGVSuHhw4fw+Xzo6elBb28vgsEgvvzyS3g8Hly9epU9BKl1vrGxgS+++ALRaBRXrlzB+fPnARQWKJ9kcUpd51wuB7fbDb/fj8rKSiSTSSgUCmZUTSQSBS2/UqkUDg8PC9zCk+StV1QbGxuIRqNIpVKoqKhAdXU1BwC9Xi+2t7dhNpvR3d197AAVcwel79H/lIGijKPFYkEwGOROseR2bmxsIBAI4MaNG/B6vXj06BGqqqqwurqKixcvYnd3F8PDwwxJqKysxObmJh48eACXy4WVlRV8/fXXePfdd9Hf3w+/34/nz5/j4OAAcrkcZ86cgV6vx/T0NMeIqqurYbFYuP22THbUnZf6HpKiJuqYYguLlMT29ja0Wi22tra4RbtarUZfXx9isRimp6eh0WgwMDAAnU6Hra0tTExMwGq14vz581AqlZifn8fExATq6uq47+Ds7CwWFxdRV1eHM2fOIJ1OY3h4GGtra+ju7sbQ0BDS6TQWFxeRy+XQ1dXFAF6isyll7RaTUtaSKMUsq38uBUhKYm5uDm63Gw6HA48ePYJGo0FTU1NBl2SFQoHJyUlMTk6itrYW3377LaqqqjAyMoJUKoX+/n48fvwYtbW1HPKgcfT7/bh79y46Ojqg0+nw/PlztLa2cusycUOR3rd47+LflF3u7OxkS3Z+fh6Hh4dobm7G7u4uNjY2UF9fjzNnzqC6uhoajQaNjY0YHh4u6KR9nLz1impychIul6uAj4rS5jSJqYVPsYJZ+i3ufOJ74rFi/IjaFpG7QuR9xItN7hu18VIqlTCbzQiFQtDpdOjs7ER1dTU+++wzKBQKnD9/HjqdDg6HA/fv30cmk0F1dTUMBgNn1/b39/Hq1SvcvHkTCwsLePDgAT766CM4nU4Eg0F8++23qKioQHd3N6ampmA0GqHX63Hu3DlkMhmMjY1BpVLh4OAAV69eRU9PT0HDVlEODw/x4MEDnD59mhu7UpOBhoYGvHjxApubm/D5fEin0zh16hSePHmCVCqFly9fcmD30aNHUKlU+Pzzz1FeXg6DwYAXL15Ao9Hgd7/7Hbc4HxkZgdVqxT/8wz8wu+nDhw+h1+vR09MDr9fLwXppkuI4y+dN5aSY1XFSKlAt/k8xqrq6OszMzMBut6O9vZ0VCG0giUQCL1++xOXLl9Hf34+//uu/xsLCAhYWFvDee++hubkZk5OTODg4gEajQTKZRCqVglqtRiwW4wSFXC7Hq1evEIvF+FqkLBbFnoEoIqKdsn0ajQb19fXcMIXmqFwux9TUFDY3N5mgsbW1FTKZDCsrKyc+w7deUXV1dcHhcCAYDGJpaYmDtKlUCplMBs3NzRyolO7CpRQXUBx3QkFvs9mM7e1tBAIBeDwe3u23t7eRSCQQCAQQi8U4JkTxIIoNUVEtBUiVSiVMJhN2d3cxOjrKvO9Go5FxRDLZEUaGmjhkMhlmjHA6nfB4PFhYWMC5c+c4+P3OO+8gn8/D6XTi/v37MJlMOH/+PB4+fMgNKkUQIN1rLpfD6OgokskkGhoa0Nrayh12Ojs7IZPJsLGxgV/+8pdYXFzEyMgIjEYjQqEQfvWrX+HevXsYGRnh3nV//Md/jM8++wyjo6Oc4v7000/xt3/7t5ibm0M0GkVrayuuXbuGv/mbv8HU1BSuX7+O/v5+uN1upNNp+Hw+dHZ2vpbtko5Vqf/FzxRTKMWOLRV4lmZLi4k4xyiYTc1onzx5wuwD4v0QJEOn06GxsRFarRYul4shHFarldP/mUwG4+PjWF1dhdFoRENDAywWC3w+H7766isAR/gscfOl7kzFrlM61ykGqVQqEY1GMTU1BYVCAZfLBYXiqD29mKEWKx6okDwYDP6hKJmks7MTFosFXq8XALgxQDQaRTQaZbJ/yryU2oXFwCe9Lw0yU6yGutT+j//xP6DVajlTdffuXYyOjjKw0ul0ck87n8/HvQB3d3eRzWa5XESpVGJnZwdPnjxBIpHAxYsXmQUgn89zMJyYIbxeL5aXl3Hu3DluCkl1eW1tbfB4PBgbG2MWgg8++ADxeByBQAChUAjxeJxr8MRnQVbKzs4OJicn8d5773Hr+O3tbUSjUfz0pz9FMBhEWVkZo9Snp6cRiURQU1PDLJbUE7Curg4GgwGtra1YWFhAJBJBZ2cntFot2tra4PP5OF5TVlbGGUEA3H4pFosVdJd5E+vnuGNEK0f8LX622P9SJVbq/NI5RpaJQqGA0+nExYsXMTo6iuXlZQwODr6m/IiJgDjos9ks/x2LxRCJRCCXy3Hu3DmcPn0awFHiYXNzE/8Pe/8ZG2manQfDVxUrF4uVWAxFFnNOTTbZOU9Pd8/0hE2zu7Or9UqyYQmWIViwDBuG/8iAIMEyHGD5h2XZ1gpraFfa8e7k7emZ7ukcSTabZDPnWKxi5VxFVn0/iHPmrocP2b3+Xn9+v5ZugCBZ4Xnu5w7nPuE61zEYDGhra4NWq+XDkq4v3QNif+X2hfh3aWkpa1QbGxvY3NxEYWEhAoEAhoeHYTAYUFNTw4SMWq0WbrebE9yf1156QfXFF1/AbrczV05ZWRkAcFWSaDQKv9+/5+ITnbxSDUvqMKaFaTAY8PWvf525sMhhf+rUKa5Td+TIEVRWVsJms+EnP/kJ9Ho9mpqaUFdXhxs3bjD7QHFxMXw+Hz799FMUFBTg8uXLLAjpNCIH9sbGBpqamvDOO+/g1q1bzF+VyWTgdrtx5MgRmEwmNDQ04Dvf+Q6qqqpw8+ZNDA4OoqmpCffu3cOjR48wMDCAixcv5m168fQfHh6G0+nMK9e+sLCA+vp6mM1muN1udpzTeJBDlUxhjUbDxR/IgU5AXEqepWhiJpPhggFEIkjRMcpPpIOC5ko6l3LBgb005+e1F/FPPU8Qymlk8XgcGo0GFy5cwObmJkKhEJRKJQtrWrsajQajo6OcinLw4EGGw1AklPyOlN1AGpDL5UJXVxfUajWmpqZ47dA47CeU5fx9uVyOU7MocZx8YlSTkoTY9vY21tbWoNfr2fR3uVxYWVl57pi/9IKKGBOoLh6Fz4mfqKmpKS8tQbTTxcUkt2mpiYh0eq+0tBSXLl0C8FW069ixY6irq0Mut0MHrFarceHCBTx69AhFRUXo6uqCyWTCwYMHcfv2bdjtdpw/fx5+v58LKiwsLDAAlE5XEiCEtk+n07Db7QgGg5xyQiXDyNSrqqqCXq/ngEJTUxOqqqoQCoWwtLS0iy+dfjY2NrCwsMAsBfS8W1tbjJ9SKr+qouzxeFi4LC8vIxgMYm1tjU/fhYUFfo1wVbOzs2hubsb6+jonFC8uLqK2thZer5fNCwqKBAIBAF9FBqntFwjZ63/pe89zxIvXlwoeUdve67ridyYnJ+HxeNhMpmDMyMgIBgYG8O6776K8vBwdHR24desWpqam0NzcjLq6OiSTSTx69AjpdJqBrnQPEYdHyecKhQLV1dWM4N/LjyY+x15mbjKZxPj4OMbGxlBRUQGlUgm73Q61Ws2FcEOhEObm5piamvBhe0WXpe2lF1R9fX1cKh3YMY+omAFpVRqNZlf4XlxA0okTmUBFbUpcGFKHLn22vLycr0Nm4htvvAGF4quQ/ZkzZ9DT04Pt7W2YzWZEo1G8++67rEWQMCLgKJk8VJnk/fff59qCYhCANMDBwUHEYjH09fUhHA5DrVaz2TA6OoqSkhLU1tbm0YBQSszY2BjMZjOqq6v5uWgjkAnqdDqxvb2Njz76CCqVCo2NjUwL8/HHHwPYKWNmNBoxPDyMn/zkJwiHw3j77behUCjwwQcf4KOPPkImk0FTUxMsFguuX7/Opc6ampqgUHzF30Wlz6kc/Yu0vfxIe835fvACce5F4S5+j8ae3hMPRjL7CgsLMTw8DJ1Oh8OHD6OjowNK5Q6/vNPp5OT5gwcPsh/K6XTCYDCgq6sLTqcTCoWCgbXk+6JxcjqdKC0tZezVoUOHGCQqFcp7CV2pICMnPxVL0Wq1CAaDWF9f5wNqdHQUALhMF2WBzMzMvJA2BfwtEFR37tzhFJmSkhLWaIhlkGqp7ddoIXo8Hi69pFar2T8j1bpEzQzYnS4jYo5EB6YIbrRYLHzfoqIiHD58mPtCi0OhUODQoUN8ncrKSrz77rvw+XwoKChAZWUlY6WomAKwQycyODgIt9sNYEdo+Hw+9Pf3I5PJ4MiRI0x8JkbRyC9CpqzY5+LiYs6gLywsxKVLlzAwMAC73c7C5ty5c5iZmUFZWRlrdJcuXcLMzAza2tpQVVUFlUqFEydOYG1tDZ2dnVywlOaLnMJEdxKPxzlnMxwOs3kk9m2vOaW52c8vKf6Wy4fb60ATv0sJ3/RZmjuxWEcul0NDQwOnIIn8aGVlZQwhoEOhpqZmF40xPTv1h3ymdAiKVZcVip1qy+LnxQijqEWLe0BsIu7Q5XKhqqoKhYWFmJub4yR/cpybzWbW0lOpFCwWCyoqKqBSqV4oKfmlR6YfO3YMxcXF2N7e5lw2ivptb2+jrKwMXV1duHjxYl76gghULCgo4Jpr4XAYCsVX1VhI85AufFFoiYtReiLt5xMQT31x0Yins5xvQW4z0eITHe9EOEdZ+oFAgCsWy4Fes9ksEokEtFrtLrBoMpnMu75C8VWFFREKQknLpAUSJTShsMmMFYU5+Vfk/CPpdBr9/f2Muzp16hRzv+9n8olzJZ0vcV7EZ5ebZ1GjEsec5ohMb/pf/C7BZESBJWpZIrsCwV7k5pqa1J8qCkW5MZGODX2fQLnSsRbvSf9vb2/jww8/xH/5L/8FarUa1dXVPO92u51dEIlEAgsLC/D7/Xj99dexubmJTCYDtVqNP/uzP/s7ZHpvby8cDgfcbjcmJyc5v4hMwNLSUphMprywrHRR04LR6/Xo6elBSUkJUqlU3maVMwmkk73f5L/oNaSnPJDvA5FqQdINR3lzlD9GTalUsukgCjZRAwTASdCiVpfL5biiidhfEjKiJkHJxWI6jKgZkLlC16bvU+ED6fMTTIMgH/X19Xlc8dL0HXEzyzWpyUObXkzXEd8Tn1GcAxJMooASv0evkQtC9I3uVVRErPxDP8RYSqY5jRnVrJSOo3i47aU5iWMk9nWvtUjBjXQ6zTxjNDYEjSHznIqSxONxjI2NIRwOy86DtL30gmpiYgKbm5tQKpVsbqjVaiSTSXi9XsTjcfh8PgB7p1vQpMbjcSb6EoXb805uaXvRz++lBQBf5bnRaU0aCm12qeAVFygJCWllFlHtF/sp9kMUMKKWIRUCIgODuEmkmoUoFKXPKC54qRAUNQun0wm9Xo/R0VGk02lmiLBYLFCr1XkbljQ4AkJSBZVkMplHFQPsCEGdTsfFNCmKRY3GQOyr+Pxy5pLYSMOk+SETnoS1FGVPc7eyssI0z7W1tXC5XHj8+DELC0q9otqL4rjJrXGx33tpXNLDS/xsOBxGSUkJXC4XTCYTFhYWMD8/j62tLbS1tWFiYgIqlQq9vb1wuVxwuVwwGo3w+/1/x55Azev1Ymtri5HntNBooer1egZQSk8ManRa+Xw+XLt2DVarFW1tbejo6NilNchtOGovamU/T9iRKZRIJPDs2TOsrq7ilVdeQS6Xw+TkJD9Xa2srl1IicB1FGykHi8y4XC7H6QziaSzVIKggJuVL6nQ6JBIJFmCFhYV8yosndywWY7NZr9fDbDYzkZ9I3haJRPgwIV9bMpnk/LFcbofShE5lwoL19vbC7XZjenoa6+vrKC8vZ5ppq9UKACyQYrEYgsEggxApmZeStEWtTq1WQ6vVory8HLW1taiurobL5crTRvcy+6Qbfy+zn8w8v9+PsbExmEwm+Hw+1NTUoLW1Nc8xHovF8Nlnn6G4uBhGoxGffPIJvvnNb8Ln8+HgwYOYnZ3FwMAATp8+vUs7lK5Fqea419qTmqzis1D5LoVih7rF4XCgtLQUwFdlvFpaWpDNZuH3+zE+Po4TJ04gnU4zdGdqamrf9Q78LRBUHR0dsFqt8Pv9TH1KaFqlUon29vZdJ5fcpOVyO2H9rq4uduYCu4tnim2/hbJX2+/zoqodiURw584d3Lp1ix3QMzMzGB4eRnNzM4NDe3p6MDo6iuXlZeZo0ul0ePDgAXw+H2pra3Ho0CFOiI3H4ygsLMSRI0dYuJPAiUajmJ6exoEDB+DxeDA+Po7m5maMjo5yYKKsrAyXLl1is5hO4aWlJc5Li0QiOHv2LPx+P7RaLbq6uqBQ7JAbEn97SUkJvvzyS1RWVmJtbQ3pdBpFRUW88JPJJPr7+xGJRNDY2Ii2tjb84Ac/wIMHDzAzM4OZmRmMjIwwHU4ul0MsFuO/CatFgntzcxONjY3Y2NhANBpFc3NzHs6OntdsNqOzsxOnT59mn6YogETNYy9hJZ1vgsy43W4MDg7ihz/8IRYWFjA4OIiOjo48wVlQUIBgMIiTJ08CAG7dugWr1YoLFy4gFAphcHAQ7e3tLJyfd1ju5YbYb12K6xDYcSesr69jYWGBc1q1Wi2b+S6XC8FgEB6PhzFvudyOU51yRJ/XXnpBRYNZWFiIpqYmNokSiQQ2NzcRi8W4bJacs1FUdYnHnEjp5XwJ1ESTh66z1+fEe+0lJMW+ZLM7RSSHh4dx+vRpzM/P51GC1NXVYWlpCX6/HzMzM5iensbhw4c5l25wcBAejwc1NTXM10WaZ3l5OW7dugWbzYaurq48/1QqlcLw8DBqamrw5MkTDkq43W6cPXsWADA6Oop4PA6z2cxjUFBQAKPRiIKCApw6dQpXrlzBwsICstlsnjAEwBn1s7OzyGazaGhowOzsLAcuALAGlkwmMTU1hdOnT3N4nNhDV1dXMTU1haGhIfT29nLaT2NjI7Ok+nw+qFQqNDU14Re/+AUOHDiAJ0+eQKfT4R/+w3+IXC6Xx1tGY3rz5k34fD5897vfZeI6qYm1n9Na+j+BJIuLixGLxTA2Noa1tTVOlBeFCeWG3rx5E7FYjJPfi4qKcPXqVaysrOCdd95hCIIUJiNdc3u1vQ5e6XdJ2NDYFxcXw+PxYH5+nnFb9+/fx9raGoNNqcBDNpvF4uLic/sC/C0QVE+ePIFWq4XNZoPNZmMyOYVCwRVAaJGLTeon0Wg0CAaD+PnPf47y8nI4HA60trbCYrHkfZ6+Q79fVKPaz28g9TEA4JzBhYUFLC8vw+12w2KxYHV1FZ9//jnm5+fxta99DdPT0/B6veyXMZvNWF5eRk1NDfr6+jA7O4uFhQX09fUx7GJiYgKJRCLPn0UObY/HgwcPHsDv9+Py5ct8miaTSTQ2NnLIWXwmhWInPB6JRLC+vs40NMR9RXgtlUqFRCKBu3fvIpVK4d1334XD4WAKabG4aC6XY7OO6jZms1mOWpKZFggE8PbbbzPIt6OjAzqdDr/xG7+Bzc1NvPfeewxUvX//PgNKi4qKoNVqUVxcjIaGBhw+fBiTk5O4desWJicnMTo6CrvdjjfeeIOxSFJfjzTvUDrHoqObNNZUKsU1Eg8dOpTnwM9ms4xY7+npQSaTwfDwMJLJJKxWK44cOQKfz4cHDx6goaGB4Qdy60guKCP3v/Q16TOk02kAO76ympoaOBwOLoArMr2WlpbC4XCwiVhUVISysjIolUpMT0/vuqe0/Wq5A/8b7Y//+I+hUCjwe7/3e/xaLpfDH/zBH7AT9OzZs1xplVoqlcLv/u7vsi3+9ttvvzA4TGytra3o6OiA2WzG3NwchoaGMDExgQcPHuDJkycIBoN5eW3SRhNTWFiIt99+G5cuXUJDQwOjaveK7IjfpWfezzm+nyNT+rmCggL09fXhN37jN9Dc3MzJzFNTU2hvb8eJEydgMBgQiUTYxJ2cnMTf/M3fYGZmBtvb2wy8I39CUVERVCoVZmdnkUgkYLVadyXEZrM7hTE++OADuFwu2Gw22O12NDQ04Nq1a7hy5Qp8Pt8u3xaZLtlsFlNTU1hcXGRWBdG/R9GjwcFB9guRX2ZgYAA3b97E6Ogoh7+p2jJdRxxrOoB8Ph/ef/99XLt2jSNPudwOL5OY/9nZ2QmLxYLe3l7YbLY8AjvS/Lq6uvD222+joaEBCoUCT58+5cx/0dSjgIYY/aPnE2EDUi1+ZWUFhw8fxte//nUcOHAAPp+PBRWlSyUSCRQWFqK7uxtHjx7lwqXr6+uor6/Ha6+9xrmAYikq0Qz93zHz9lqr5F9bXFzEtWvXWNgTX38qlUJDQwOam5tZI/d6vYhGo4hEIqwdP6/9H9WoHj9+jP/6X/8rurq68l7/kz/5E/z7f//v8aMf/QhNTU34wz/8Q1y4cAGTk5N8Cvze7/0ePvroI/z0pz+F3W7H7//+7+PNN9/EwMDAviaXtNlsNk6hITwPUa14vV5eBFKcE/2IJ54IqJNGQQB5YSSNcMk1cbPKvSe9FrAD2qTqvwsLC6iqqkJ/fz/n4PX19TEl7ZkzZ9Da2oqPPvoICwsLnJBNNfCMRiOSySSGh4fx7NkzHDhwAFVVVQC+imwRaJHKqs/NzeHEiRPQarV466234Pf7ce/ePfziF7/Ar/3arzFgVcwzKy8vZ15v4qsvLi4GANZ4tFotWltbsbq6itnZWbS0tMBisaCjowONjY15QQ8AXJRDTvMknNzRo0eRy+WwurqKTCaDYDCIx48fc305hWKHueDYsWPw+/28xkQ6X7p+dXU1zp49C4/HwzUN6+vrGZ6x18El7ZuI0wPAgo1YPUjYAjupNaurqzhy5AhrqyMjI5wrGQ6Hce/ePdTW1sLtduddf69+SNem3Pt7fU/8vlhlhgI0qVQK0WiUaYnC4TAmJiagUCi4kg4A+Hy+F6J4Af4PalTRaBS/9mu/hj//8z/njgE7D/cf/+N/xL/6V/8K3/zmN9HR0YG//Mu/RDwex1/91V8B2PFT/Pf//t/x7/7dv8Orr76Knp4e/M//+T8xMjKCL7744lfqx/3793Hz5k1MTU1Bo9HwBq+vr0dLSwuKior4tNrPLqfNShVPpDzT9P3n+aT2ai/6eTrBxA1BdCBlZWW4d+8erl+/jmAwyL60mZkZeL1eKBQK5kUfGhpiXJnFYsGTJ09w69YtVFZWoqWlZVcZJYVihya3qqoK7777LtbW1jA4OAiv14upqSnY7XY2VYjdgPpIviy6DkE7qFgEFSVNp9MoLCzEK6+8gt7eXly7dg2rq6soKChg7a2oqIj9XqTxkeYgnQ9ylrtcLlRXV7OWWFNTg7fffhsXL15EaWkpCgoKoNfrUVJSgsLCQqbIFQ8u2vxqtRqNjY1obGxEOp3GzMwMs8aKP6LWJEdAKNVsiEd8c3MTV69eRTAYRF1dHZt7BKEpLy/HiRMnuEzZsWPH0NTUBKfTiZWVFWQyGZw+fZoPfPHAFdeanL9M7vX91qpCoeA6AMXFxTh79iyOHDmC6upqps8mLTmZTKKyshJdXV0oKSlBeXk5GhsbUVdX9yLL/v+cRvWP//E/xhtvvIFXX30Vf/iHf8ivz8/Pw+124+LFi/yaVqvFmTNncO/ePfz2b/82BgYGkMlk8j7jdDrR0dGBe/fucbKv2FKpVF6RSQKSEQYmk8lgfHwcarUaNpsNCwsLSKVScDgcOHToEH9PLvonnpCUJkKv74c4/1WE1X7quCgsgPxilBaLhdHYVP49nU5zsqrJZMLo6CgGBweZbM9isWB6ehpffPEFGhsbUVJSgk8++YQ3hBg5og0H7CxMMo+IaZII7MbHxznRlHxIJFBofgKBAG7evAm/34/m5mZ4PB48evSITbDGxkZotVpOu/nkk0+wvLzMqT/iBiGqYjmzXRQCRIdDQlqhUHCibC6X40ovhEMjP52cyUO/jUYj6urq8PjxY4RCIYRCITahxeCDuPn38lOJEbTm5mausEO1HBWKnTSpbDbLBHS9vb3o6enh1BmlUokLFy5wgjr5zKSYOLmD9UXWn/Q70muR+T09PQ2r1crMCARdoLLu8XgcDx48gNPpZFZW0tyf1/6PCKqf/vSnGBwcxOPHj3e9R/llNLHUSktLOQLgdrtZ+5F+hr4vbX/8x3+Mf/2v//Wu1zs6OlBcXIxgMIi5uTnkcjsIcxpwi8XCDnE5NZkmxe12Y2pqiheCxWJBVVUVJ1iSD+Z/J7oiCiJCKYvJwKIZIDVLKVpEJ3lfX1/eid7S0oLa2to8dH1BQQF+8zd/E5FIhNlNT506hZaWFk4sJdNHFNYmkwkHDhyAXq/HsWPHUF5ejuLiYpw/fx6JRII1HzEVgp7J6XTi3LlzUKvVaGtrQ0VFBXNPUYSqsLCQx9RkMuGNN97gHEYyJemaZIYRml4UEDROdrsdvb29HFk8duwYI9wVih1A5eHDhzmQUlBQgJKSEhw7dgyFhYV8HTntw+FwwGg08gEpzovoJBcFvVwT1wjlzNE9SYsnXJvYSKCSli8KW9Hk3mvNSe/9q2j04uez2SyKiopQUFCAtbU1RKNRFBcXczoUVU7y+XyIRqNQqVTMax8KhbC6uvpC9/1/XFAtLy/jn/yTf4KrV6/yaSbX5E6W5w3Wfp/5l//yX+Kf/tN/yv+Hw2HO2KfS6Ha7HWazmf/2er1IpVLsq9pr4hQKBcLhMHw+H5qbm5FOp9nHI3diSbUr6Wkq1bzoPcp5o5OSFr3o1KZriyklIqZLFHq0WIk+RTSJjEZj3masr69HXV1dnvYkrSij1+v5pFQoFGhqasozPcnMkfr3gK98hdQPEppE2QLkm3DZbJYPKum803MQXkcaXaNr6XQ6PrEVih32ABo7GmOiy6EfvV4Pp9OZdx+53+Qr0ul0eQef9NnlNKn9HNR0HVGLlzqvaY7EnEjp56T3e94BupdABnbT1IgtEolgZmYGJpMJ9fX1MBqNCIfDmJqaQiAQgMvlAgDMzs6ipqYGhw4dgsPhQGFhISKRCFP0PK/9Py6oBgYG4PF4mFkQ2BnQW7du4T//5/+MyclJADtak0h54vF4WMsietVAIJCnVXk8Hhw/flz2vrRopY1YDDOZDFcK1uv18Hg8SCQSXCRTznwQ/yY/Vk1NTR5rwvN8Ur+K+Uco7NnZWRYEJCR8Ph8SiQTKysqYOpkEFW1W+qzoHxHzyOhZxAUoZ7bKLWpRAO0VRBA1G+n4iNcTtQ4gPwlWvOdempJoAsvhl/badHRfsb+iABD/lwoQ8YcCC6lUClarlQUwjTtpE3uBgeVMMLq/yFEvPiddi4IOxHVOGnIikeBxNBgMe7J1ivfdr0mFpth36diQVr61tYVkMgmz2QyXy8WafkFBAVpbWwHsBNg0Gg0OHz4Mn8+HioqK5/YF+D8gqM6fP4+RkZG8137zN38TLS0t+Bf/4l+grq4OZWVl+Pzzz7mkTzqdxs2bN/Fv/s2/AbCTSKxWq/H555/jO9/5DgBgfX0do6Oj+JM/+ZNfqT8HDhxAcXEx/H4/pqen4fP5UFxcjKWlJSSTSTQ3N7N6Kp1YcQNkMhmm1K2qqkJHRwdKSkpYkxA/v9/f4v9ymlUikcDt27ehUChQV1cHjUaDlZUVLsleWlqKY8eOcZEEpVKJo0ePQqPRIJFIYHZ2FtFoFPX19bBarYzqJg524jQic0WtVucltuZyuTxKX+qbVCCIz0IChbQU+o5045MQFRc7vUcLmkxUErDkdKf3RVOKBAaAPJgCPZdUS5GyH0i1PmpyOXxiDuD29jZCoRDS6TTDZ+haJKikkem9hKkouD0eD+fFGY1GtLW15Y0nCan79+9zcIjoce7duweFYodIsba2Fj09PbsOKEBeO5IKHvHzcpaGmByt1WpRWlrK2QA6nQ4NDQ1QqVQclCgsLITVakUwGGRTmfr6f61clslkQkdHR95rRqMRdrudX/+93/s9/NEf/RFHT/7oj/4IBoMB3//+9wEAZrMZ/+Af/AP8/u//Pux2O2w2G/7ZP/tn6OzsxKuvvvor9ScSifBCoyrAlI/m8XgAgJ3wcqq6aGp1dXWhq6uLfQLSJM1fRXsSry3+T6WkJicnkcvt1KsbHh6G2WxGV1cXbt68ibm5OdTW1nJCNTlbx8bGOAw8NTWFc+fOYWBggOv+kTN5fHwc6+vrfPIePnwYwWAQS0tLSKfTqKioQHt7e95mo7Qdv9+PmpoahEIhuN1ulJaWYmVlBaFQCADgcrm4Fp04HpSHl8vtpE5QdJE2KYW3x8fHMTc3B41GA6PRyClAm5ubnJZTV1eHYDCISCTCAqS9vR1TU1MMQDQYDGhpacHCwgIOHDiAbDaLyclJNDc3swNebu5ISIpNNMPob4/Hw5E6sYDrXq4A8bfc3+l0mskBOzs78eGHHzKXvDiW6+vruHLlCi5fvoxwOIwPP/wQly5dgtvtxqVLl7C8vIwnT57gwIEDu4SlVPjsZ9rJaZL0HdFEj0ajmJqawvb2NkdWAWBubg4ejwcnT55EZWUlRkdHkcvl0N7eDofDAbPZDKvVirm5uV33lmv/V5Dp//yf/3MkEgn8zu/8DgKBAI4cOYKrV6/mIWn/w3/4D1CpVPjOd76DRCKB8+fP40c/+tGvhKECgKmpKRiNRo7+6fV6ZDIZJngTizvINRJySqUSJSUl7JcRVeIX8QE8T4iJQotC5LR5qUx5VVUVSkpKGKTa3t6O/v5+Pp1mZ2fR2NiI2tpavPfee4xwLiwsZNpZhUKBlZUVHDhwAGazGVeuXMHo6CgWFhZgtVphNpvx2WefoaioCPX19XnPGIlE8OTJExQVFXFprGw2i4cPH6KmpoZR1aJDnZ7b6/ViZWUFlZWVGBkZwerqKurr6/P4q1QqFdxuNyYmJnDo0CHcvXsXJSUlWFpags1mg8vlglKphNFoxNDQEDo7O5HL5fDpp58yor6rqwsajQY3b96Ew+HIE9SEeQLy6aP3miPpPAM7wiiVSnF5LqLeFTXFvbRy6WvivZVKJQNtib2TMGPiNSmiF4lEEI1GObuCTD6NRsPFHcTnkJricn9L160UD0ZjJuK8MpkMMpkMampqYDAYYDabmW1VpVIxU4ndbodKpUI4HMby8jJ6enqYofRF2v9PBNWNGzfy/lcoFPiDP/gD/MEf/MGe39HpdPjTP/1T/Omf/un/V/dub2/ngpuzs7PweDyorKzEs2fP2ESiU4JOdiC//Diwk7Ly7NkzFiLFxcWc5yW38Og5n9ekAk48uTQaDQMAKbpIv0U/D22e7e1tVFVVMSo4mUyyJuH1epHJZHDmzBl2dra2trKQTiaTnLgsag8kpGmMZmZmoNFoEAqFcPr0aWSzWbjdbpw5cwZVVVXY3Nxk57L4bC6Xi7MDotEoTpw4sQvaoVKpuEAARfNoI1itVrhcLhZs4XCYBSIlK6fTaabmJaaMxsZG/PKXv4TD4UBdXR0XGZCa3WKEU24+xPmKx+NYWVmByWTicmXiXO7lF5L6d8TXiYp4bGyME3vF0ux0XTLTBwcHEY1G0dPTA5vNhnA4jA8++ABLS0vsGxK/u18WhfQ5X+Rv2i86nQ4ulwuLi4tYXV2FwWBAVVUVCgoK2HVBB20gEMDa2hrXgaSfF2kvfa4fhW0NBgPKy8sZ2FdVVcUl0qnMFCCf+6RQKDjETyZHIBBAe3s7ayn7OS73Elhygk30B9HmjcfjWF9fZwLAxsbGPH9LQUEBkwFSUyp36IzPnDkDg8EAnU6HK1euIBqN4tChQxgaGsLt27cxMTHBsIR4PI6ZmRkkEglZtsWCggIsLi5iZWUFP/jBD1BZWYloNIqSkhJ89tln6OjoQE9PD5Ojiehoi8UCjUaD9957DxsbGygvL2eHL2kPtImWlpZw7do1zM/PI51OIxQK4fbt21heXobT6URvby8ikQg+/fRTGI1G1srv3LmDu3fvIhQKsT/ObrczxXJ3d3fe+AD5Zo9UIMn5krLZr8qXHz9+nKEt4vf2E1h7rYNoNAq3282m0kcffYRIJMJFGkiQkjD4zne+g4WFBUxPT8PhcOAb3/gGkskkotEodDpdHiCZ7rGX0JGLHIo+SblUHDrExMij3W5nrc7tdjM7R01NDZaWljAxMYHq6mo0NTWhuLiYk8pfpL30gurhw4cwGo2w2WysVms0GtTU1OzSiKSnkLhwzWYz85OTykvajJypJ7YXjbzQ/QkbQ5gtl8uFO3fuMHFfZWUlgHwSOypQMT4+Dq1WC4/Hw4DPiooKFBQUMDK7r68PfX19GB8fZ2Edi8Xw9a9/HSaTCT/+8Y8RiURgt9vzzCNKao7H45yqYTQa8YMf/ACzs7O4e/cupqen8cMf/pChKaLpqNfr8frrr+Nv/uZvcO/ePZSXl+fRDxPkoqOjA5cuXUIikWBMXU1NDdra2mAwGLgcVGtrK65evYre3l5UVlaiuLgY1dXV+MUvfoFvf/vbKC4uRi6XQ3NzM+x2O2tTYvBD6q8RX6d+i+ZfJpPB2NgYUwRJyROf548Sr0lzB4CLdVDOodVqZROLHM4WiwWZTAbl5eUoLS1FMpnE9PQ0c6hTwIVS1kjwS7XCvf7fzy8lvQ5dOxaLYWVlhfnPSkpK+OAhemoqSU9gY+ISs1qt/3cBn/9vag0NDTCbzchkMpyfVVtbi5GREcRiMVRXVzNnOLB7wYkLSuqroAkgzUd6ionXkVusezW73Y7a2lr+zOHDh7G2tobx8XF0dnaywMnlvopuabVaHD58GB999BEXALXb7fjss8/Q2NgIp9OJaDSKgoICxONxbG5u4t69e6ivr0dJSQnS6TRHB4nwjBapeHrW1dWhsrISjx49QltbG0pKShCJRNDW1gaTyYRf/OIXzKsuts3NTWxvb6OlpQVnzpzBxMQEg1qlh4XJZEJ5eTlaW1s5QlRdXY2amho2vbRaLZqbmxEOh7l+ocFgQH19PfNlpVIp1qYpJ1AORAvkC31RQyYhRXNLxV1LSkqYDYC+J/VVPa+Ja40SywcGBqDVajmvMplM4rPPPoNOp8OlS5dgMBiwsbGBK1euYH19HTabDYlEAk+ePMHDhw9RWlqKtrY2fibR1JPTsMS/5QSY+L546NDfRqMRNTU1XMUbACorK6FSqVBXVweDwcClv5RKJVZWVuB2u3Ho0CFotdq/q5RMjbQKqlSyvb3NFB4+n48TYaULlJr4v4gOF9NnAPmKJ+ICERf+Xo3edzgcXJAC2DlJv/vd7zKpHQkPYp8Adk761tZWhMNhRKNRdHR0wOFwoKGhAcvLy9jY2EBhYSFKSkowMTGBwcFBlJWVcVHSiooKXL9+HcXFxTCbzXm5YiLy3maz4eTJk0gmk7h9+zaOHTuGa9euoaWlBVtbWyygxPFQKpWYn5/Ho0ePcPDgQSwvL8PhcOyKplHggBKD19bWUFdXh/X1dTx79gzBYBAKxU5iKwno9vZ2jI6Ocl1AnU6Ho0ePMmcU+byoP5TWIQpi6aaVbkgRljA9PY1gMIjDhw9zGg7BJuQc6lJflLTRvU0mE06ePInx8XEkk0mcOHECZWVlnJtICfWVlZU4e/YsFhYW4HQ60dfXx8GUnp4etLa2cj1Ase9yflQ5UOl+/is59whFZ7e2thCNRqHRaHhfxeNxrpgdDAYxMjICpVLJKUw+n++FKF6AvwWC6t69exyNKCoqgs1mY7W9rKwMuVyOy7yLi0kUMgqFgik3qH6dXq+HVquVnUg5P4V0Q+zXpP3IZndoRvR6fR4/lFqt5g1PwuTYsWPM7ZTL5XDkyBEmwKM0FUIR63Q61jTeeOMNLC8vI5vNcvUQ6UZ2OBxobm6GRqPBqVOnMDExAYvFgsbGRq7q29fXxw5vuicJVYfDgeXlZRgMBvT29jKlsSgIiRp5ZmYGLpcLHR0dXA2ZqIepH1qtFkajESdPnuRS8VqtFtXV1Vz2XqHYAc5KcVXSOaYmmkvivFEofnR0lCOiYlVgcgO8qJkvPQyz2SwaGxtRXV0NhULB5bKAnTp+dGBQrh/526ji9NGjRwEgT7OX80ftZQI+T0jJfQfYOSDn5uaYOtnlcjGvO0UmjUYjjEYjR80p/cjhcECpVGJgYGDX+EjbSy+oKHE1nU4zQ2N9fT0mJiYQjUa5gCf5SMTNSQswm81ifHwca2trvOCbm5vZCS234KntN8niYhI3j9Q3sNd35ZpY2IH6T0h62oREE0vXpYTX9vb2vGuJpzGdhKRpFRUVoa+vDyqVCmfOnMkrGCFizOj6ZWVlePPNN/l10TQUC2V2d3ejq6uLNyYlkYvPL7IRKBQK9PT05EVuFQoFWltbWQOurKzM64v0GvSs4o84BzR2c3NzWFpaQm9vL8rLy/ME016a1F7rYa/5JF+jaBKL6VIUsaToNL1Onxed23Laolw/5PqzV7+lTafTwWazMc0zVQWiZOlkMolcLofCwkImnyTN61eBGr30gqqnpwdmsxkbGxuYm5tjXqp0Og2fz4fKykqmDiFTTjx16XcqlUJzczPa29s5VUFcTDSR4jWAr7Qj6etyUSU5B6y48KWmp2iW0XWl1WekC4w2E11D3FxiMGEvASt+l5DkYo4f8FV5MVHLyGazu7ikpBuVBBY9gwjDkPsO9YveFyN5dB/R9yR+T/qcJLik+Cq6RzweZ/rltrY2GI3GXS4BaZM7hOTGUzo/JGhIG6XgilQbFAWvKKCka016z72Ek5wwku4HaZ+JPCAQCHAfkskkEolEHkzFZDLxGBO+ai8NVK699IJqamoKJpMJSuUO8Z3RaIROp0NXVxfsdjs7LoG9aTGy2SwTrMXjcUZ5iwtFFADU5E5ZOfVarkkFA/WDTqmxsTF4vV7OuK+rq0M4HOYS7SaTCRaLBdlslnmBaHPlcjl2ZFOjxS1qJXL9Efsr9X+IG10sqinyy8sdBKKQkmox9BptWhKQ4jWoz2KaDV1bFOTitaXzLTcX4ufm5uawuLiI5uZmdurLrRW5JrcustksQqEQFAoFM0NQtWe1Ws0UO6KgomclTFwqlYJWq4XD4cDi4iK8Xi/jl8RK2+Lz7SeY5ASruIbFgAHNhVqtZggJFcogF8Xa2hoXGi0sLORooE6nY0tnfX19z3ET20svqAKBAEeJSLhQ1ZFkMskcP0A+glcqXAhjtLKyAqfTiePHj+exD4jajbTtdVJJ/97ru9INHAwGMTExgbq6OsRiMabZXVpa4nywdDqNixcvIpFIYGhoCMFgEEeOHEF7ezvcbjcePnyIXC6Hw4cPw+l0IpVKYX19HR6Ph8P8BB2QCimFYsd56/F44HQ6mTe9sLAQdrsdsVgMfr8fwI4AtNvtyGQyDGqk56HKNVSSqqioCMlkEn6/H9nsTt4gOc5FbYvC2xS2z+V2cFrEC6VQKLCxsQGz2Qy/34/19XWYTCY4HA5YLBbMz88jFoshk8nA4XDAZrNhcnIS0WgUwWAQzc3NaGxsBLAjpMLhMGOxOjo6mB+LxkIUWnKN1oc4fm63G++//z5qamrw2muvIR6P4969e1hbW4PRaITL5UJ3dzebfaStzMzM4OHDh4zwJ8qd27dvo6GhAQsLC1hcXMTrr7+ep+XKaddypqe45qRaFB1ANK90ANFaoKIaZrMZKpUKwWAQBQUFCAQCCIfD8Pv9mJ2dRSgUYn65F2X4fOkFVW9vLwwGA9bW1jhiY7VasbKygpWVFfT19e1CSEtV+Wx2h3OnpaUFzc3NTCFCTaray6n6e31GbHILR2pSip8l7nYCoKbTabz55pvI5XbSStbX17G0tMTkcHfu3IHFYsHTp085d+/u3bt48803MTs7i6dPn6K0tJRBhvTscn2Nx+MYGhpiEOjdu3ehVqvx9ttvIx6P44svvoDT6UQoFEJZWRkzaRJJYTabxbNnz/DZZ5/B5XIhFovh7bffxsbGBiYnJ2Gz2bC5uYmDBw+iu7s7TytKJpO4c+cOBw1mZmZw9OhRrK2t4ZVXXoFKpcLQ0BCampqQTqdx+/Zt6PV6nD9/HsFgEJ999hmXw5qcnER9fT0GBwdx/PjxPM2MzOupqSlMTU2hpqYGtbW1HIGT+5HO417/FxUVwWKxIB6Ps+BPJBI4cuQI0uk0rl27hoqKCg6WkOlXUlKCV155BRsbGwgEAmhra8PW1hZWV1dRV1eHeDzOUAA5DV5scia1uD7ltGqpZqpSqWC321FZWclFRgKBAOfoGo1Gpivu7OxEIBDAxMQEstkdGp//V6XQ/N9s5MzTarWoq6vjzHSKXtGJBeQLFHGSyO4OBAI8OXJCaK+21/vS7+51LenrhCL/5S9/yWkpPT098Pv9GBkZQWFhIWsH4XAYR48ehUqlwnvvvYepqSlsbm7iwoULSKfTuHLlCmZmZnDnzh1UVVWht7cXZrN5l/9N2s9cLsec18+ePcPx48exuLiITz/9FJ2dnaiqqsJbb72FiYkJPHz4kKN5AHi89Xo9TCYTTp8+jWvXrmFtbY2LFBw6dAizs7O7ompktgYCAZw/fx4Wi4WBo36/nwukhsNhjqQRbU5HRweGh4eRTqcZx7O6uso4LAIgihpTIBDA3bt3mYWWQLDPO2j28gkBO+Yb5QkGAgFkszvVcy5evIhcLoeZmRk2r8S1SZ/TarVcAIMSzTUaDcxmM+x2+54cT6JPTUpHI02oJiFN808anRh1pnHIZDLY2tqC2WxGYWEhm3mLi4uIxWJ47bXX4HA4cOvWLaRSKVgsFlRWVvI8vkh76QXV4OAg1Go1LBYLbDYbTCYTh8HLy8vZkS51zIpNqVTCYDBgbGwMi4uLzDhAqSzUfpWTdT/f1F4+DWBHaFosFrz22mucwLu5uYmKigrodDq43W6MjY1hZmaG+ayMRiNUKhVHz9RqNYqLi9kkDgaDmJ+fh06nw+DgIBeI2C+4QH8TNo3gHh9++CEymQxmZ2cxMTGB1dVV1lKkAo+SkB88eID5+Xl0dXUhmUzCYrEgFotxmbNIJAKv18umBqGyP/74Y5w9exb19fVIJBJsStIGJxZMAJzWYzKZkEwm8emnn6KtrQ3V1dUwGAwYHx/HjRs3kM1m8frrr8PpdGJ7exuPHz/GxsYGjh8/jvr6+l00NnvNp1xaivieSBYoCrCnT59ifHwcR48e5RxGMo91Oh0CgQASiQTOnTsHrVaLp0+fMmKf/EVk/tLalRNQckJK9LOSsNre3mb+eGmeIP0dCATg9/tRUlKCjo4OFBYWYnNzE2NjY+xkV6vVMBqNqK+vh8PhgMFggFarRWNjI65fvy67F8T20guq9vZ2aDQabGxsMIfPwYMH8ezZM6ytraGzszPPlpcTFBqNBmfOnMGxY8eQzWYZJCrnQKdrUBPfF53EL6KJ0Xek/VIqlSgtLYXBYMDi4iJcLhecTidaWloQi8Vw7949BINBmM1mDAwMIBKJcIXdqqoqeL1erhZCtfJKS0vR0dHBdCOEvBbR9sFgEJlMhuuxETJ/dXUVv/zlLznFZ3t7G8lkEu+//z4ikQjeffddLi4hPhM9B1Vq9ng8SCaTUKvVWFtbw+eff45jx46hvr4eKysrrFFUVFTgm9/8Jp49e4YnT55gZWUFFy5cgNfrxaeffopcbqdwKIXISaMGdooj/NZv/RampqYwODiI0dFRvP3223jnnXcQi8Vw9epVxONx5HI7eXX9/f0oKSnB0aNHmfNK3NhyB5uc01q6yWmMSKOncR8bG8Px48eZRDKRSODzzz9HRUUFjh49ymZ1aWkpNjc389wR8Xicq/WIvqT9fsQmBYBKk7el65XWY0VFBRYXFxEKhfDw4UOYzWYYDAYUFxez28Hr9cLpdCIcDmNgYADZbBZHjhz5O42KWnFxMVO7kL+FqIh9Pt8uOg1g92mpUOxQaBCz5l4TRt99kSiQNMIoqtKidifn09re3saTJ0/w7NkzpNNpvPLKK9BqtVhaWsLMzAympqZw6NAh1NfX486dO7hx4wasViuUSiXq6+tx/fp1PH78mDUtAhe2t7cjnU7jyZMneSp+LpdjTuyhoSF897vfRTgcRiwWY/Pq1KlTWFlZYfOrr68Pra2t+LM/+zMm8CNHPznKqVRXVVUVGhoaEIvFOD+svb0dT58+RTQahcPh4CRpyiHz+/04fPgwQqEQ/vRP/xShUAh+vx9ra2vI5XIc6c3ldthZya+0ubmJQCCA3t5e6HQ63Lt3j4t4EttrYWEhF0Ld3NzEt771LWYkSKVSjBWjuZIyL0jXgvSH5l+pVLKgCgQCePbsGQwGA0KhEAcA1Go1Dh48yJWny8rKcPnyZT5ALBYL1Go1Tp06xfzqzxNSJGD30/zFHxH+IRVeVCOyqqoKs7OzWF9fRzAYRFFREVfHpowKqkZTVFQEvV4Pg8GwZw0EaXvpBdXnn38OlUoFk8nEiasajYZ/m0wmLmYg50iUhmJJdRYhDdLImJyGRteT2v5yIXLxfXLqimR9KpWKKYntdjs7qt1uN/x+P44ePYqOjg5oNBqcO3cOV69eZVoWh8OBV199FT//+c9RUVGB06dPo7i4GJFIBB9//DFUKhXzyou8Q7lcDmazGYuLi/jggw+QTCa5KnJpaSkDZ6emppDL7SQgV1dXo62tDWNjY+yUpvGrqqrCxsYGpqen8Rd/8RdYX1/H+fPnEQgE8ODBAyQSCSwsLDCLKtEtK5VK1j4ImU/jQD5IhWKHiI7M9aWlJa54EolEcOXKFVRVVcHn8zFCf3x8HDU1NThx4gRsNhvGx8cxPDyMxsZGTj4moUdzL4c5kwukiD8i1qm+vp6vYbFY8L3vfQ9arZZxRmRmEhyCrk8OdrEfFGRQKpWs7UvNur1yEaUHrRQ0Kt6D1rD4bBsbGxgYGIDJZEJfXx/Ky8sRCAQwOzuL1dVVWK1WFBUVIRwOQ6vV4sSJEzCbzbBYLFCpVPjkk0+eu49fekFFXM1+vx+Li4tYW1vDsWPHMDMzA5/Ph97eXk6OpEVOjf7OZDLo7+9HKpXKq0Aj5sNREwULwSEUCkUeolj0X9D3xVOWgJRAPmBRXCCUaiFugoMHD6Krq4tNnu3tbTQ3N8Nms0GlUnEyc3d3N0pLS/mEVqvV+M53voNoNAqFQpHnyxPv4XQ68e1vfxubm5tQKpVMfROLxZDL5WAwGNDX1weDwcDC/NKlS2x6FhcXc0TKYDCgtbWVGQEOHTrE2fcjIyNYWFhATU0NnE7nLmFutVrx5ptvsv+rpqYGNTU1uHz5MofQc7kdyMLS0hLTMgM7uZ+vv/46lxRzuVzQarWoqanhQg3JZBL3799HIpFAX18fbDYb338/7nhxzYhzK/c3pQLRvCqVO8SM4lqh74gHVyQSwfT0NFMOWSwWHDx4EGNjYxgdHYXJZMK5c+e41JbURyXti+gsl/ZRziqQw6VRIrtCsYMzjMVizNlGNEs+nw9FRUWIRCK4f/8+kskkDhw4gEQisesecu2lF1RVVVVwOByMLyFTr6ioCGtra1z8QUxcBfJR2ltbW5iZmWEbOxAIwGQy5SUI0wTGYjGMjo5iaWkJDQ0NXH9tcXERCwsLsNlsaGtr4yjV5uYmzGYzCxNyXkqTe0mzEaNwcuq5mGcHfOUHEgGdBQUFTBVDjZgvRUEqjgVtoLq6OtTU1PC1c7mdslSk9dTW1uZpGjabDTabjbUoEqB03fLy8jx0e3NzM5qamvj7JAikJnpZWRmnsVCmQHNzc973gB0fJWlEovCmZyJtWayQMzExgYmJCbS3t6OtrW1XwITuIZrFUu1K7IPUZyXODwklmluPx4OnT5+ioaGBK+SQKVdQUACPx4O1tTW4XC5MTEwwPuzp06doaWmB2+3G3bt38cYbb/ChQMJQ9I+K/RD7J2dVUBOfSVx/xcXFqK2txdLSEoaHhzE2NsZVh8Q+kElNawcAU0c/r730gurmzZscBq+oqGC+7NraWuZyl6YeSJ2+9H5bWxvXXRPfp99bW1uYmJiA2+2G1WrFjRs3oNPpmDo3m82iv78farUaZWVlePToEVZXV5FKpfDWW2+hoqICU1NTePr0KYqLi3Hy5EmOjHk8HqjVajQ0NHBB1XQ6nUdZnEwmedMoFF+BI6lvtFnFBUsLRvqscg5hep++T45l+r7U7KV7UP/oddGRS+8DYK1WLI4g+nLkwKei0CZhSt+Tcp+TQCP/jrTcFAAGd6rVavT19TFCXC6FRTTf98IkSc16MXorfhYAVldXce/ePYaYkMknatpNTU1wuVx48OABUqkULl26hHQ6DbPZjOPHj2NpaQl3797lKjVEo2IwGPLSfsQ+SoWXuB7k1oL4mkKxk6y9tLQEYEdjLS0txdbWFtxuNxYWFtDa2oqGhgau2E2as9VqxfLyMl6kvfSCiiI1fr8fqVQKRqMRra2tmJmZgdvtxsGDB/MEjtQ3RafRysoKPvroI5SVlaG1tZVD/+J30uk0I9f7+voQi8UwPz+PbHaH/eDcuXO4ffs2hoaGUFVVBb/fjxMnTuDJkycYGBhAIpHA06dPYbFYMDY2BrVajfr6evT390OpVGJxcRFzc3N47bXXMDs7i/7+fpw9exZ1dXVYWVnBwMAAUqkUh6i7urowPz+PcDiMdDrNJbQJmKdSqdDU1AS73Y50Oo3l5WX4/X5UV1fnFYiV+jAUCgXW1tYQiUTQ0NDAEADa0BsbGxgZGUE2m4VOp+Py59PT0+xXOXz4MGw2G+bm5hCJRFBXV8f1AanCi9VqZQYEqrRMJqSomZGJQ9oR8JWmIhLliUJaOt/0XJOTk5ienkZXVxcaGhryhKA4FiQ0RS1Xek1RAFDfRAElmmTr6+v48MMPodVqYbVasb6+zuNHnxUFdiQSYX+ZTqdj6hS73Q6TycRI99XVVZhMJhw6dIg55uWE1F4mqpyQEoUYzUMqlYLJZILZbOa1I0Y2yUpQq9WYnZ3FzMwMGhoadl17r/bSC6qamhpYLBasr69jZWWFoQXxeBwbGxt8glOTntDkpLTb7aipqYFer+cFJ0Z+aPLIF0TmldfrRTqdhsvlgsFgQGVlJSKRCCKRCJxOJ2pqarC9vY2RkREsLS3BaDTi1VdfhdPpxMjICNrb23H8+HEUFRVhbGwMIyMjSCaTTEhGNMoU5o/FYrhz5w78fj+WlpYwNzeHpqYmrK2t4e7du6z1FRYWYm5uDjMzM7h8+TImJycxNzeH0tJSuFyuXf4p0fcTi8Xw+PFj6HQ6NhnFNj4+jng8jvb2djx8+BB+v583NQnekZERlJeX48aNG0yf8s477yAajeLGjRvweDw4cOAAzpw5g2QyicHBQSwsLMDlcuHYsWN5lWRoPkTfkbjBpJgmQD7/LhAIYHBwECqVCt3d3bvKxUs1brHJrRupn0nsh+jgFtHwwA4kgQgD6RCg7yiVO6yvb775JgM/e3t7GdicTqe5tt6FCxcYT0YOdhoP6ThJrYQXESD0Wb1ej4qKCvh8PgwPD2NiYoKrzLhcLlgsFiQSCdjtds5kWFtbg8ViYT6157WXXlBRiXAqJU2mUXl5eR4RHTXR+Uhta2uLSeYcDgef1FIhRQsllUoxmn1ra4uhEVtbW3laGgES9Xo910CjLPPi4mKummM2mxEMBvMKJzidzrzKxlqtFlVVVVhcXITNZkNnZyfi8ThSqRScTifMZjMePXoEu92OS5cuoaioCCMjI3j48CFGR0fx4MEDHDt2DG1tbbygRP+XaN4+efIEXq8XFy9eZIocUVuJRqOIRCIwGAyw2WxcSstkMsHlcmFpaQnBYBAejwculwttbW349NNPMTIygrW1NSgUCvT29qK/vx8VFRWYm5vD8vIyzp49y/MpZ4pIm5w/Sao10/vZbBazs7N52pS0MK2cgHrePQH55G1pP1wuF37zN38T29vbuHv3LqfYAEAsFoNSqYTJZILP50MwGER9fT16e3vxySefQKvVwu12Y21tDVNTU1AoFFx5RxSOokCXanfScdxLUO31fjKZBPAVrVI2m8Xm5iZXLHe5XFhdXcXQ0BBMJhOqqqpQWlqKcDj83DEF/hYIqmvXrgHY4TwnzmYSCPX19cyhDshjoEgora+vY2Jigs1HkYmAmkqlglarxcLCAhwOB1ZXV+FwOJDJZLC0tISmpiZsbGxAqdyp3kGJ0WSW6nQ6jrylUinmZQ+FQnjw4AGWlpaYWVL0DwFfUSPPzMzAYDCgpqYGGxsbiMVi+Pzzz7m+IZVy9/v9WFhYYJR3IBDA/Pw8VldX0djYiIMHD+b5kWhcvF4vxsfH0dbWhsrKyl0bQancYXMYHR3Fe++9h/X1dXR2dqK6uhpPnz7F5uYmJiYmmBCvtrYW1dXVcLlcWF9fh9/vx6lTp1BTU4OZmRksLi7i6dOn0Ol08Pv9UKvVeTTNewkPURjQ5hQ5s0StR6lUIhAIYGBgAGq1GgcOHOBcTukci+tCru2nqYj+PDnEOCW5E/OBWq1mEGphYSHOnz8Pn8+HTz75BJ2dnVwRqKqqCoWFhfj5z3+OWCyG8+fP52kqUiCnKLDknud5Qkq8rlqtxtbWFqampmC1WtHQ0MBWwsrKCrsd6DA2m81oaGhAUVERHA4HC7jntZdeUFVXV0OlUiEQCGBmZgYmkwldXV2YmJhgPirgK9Vd3Jy00I1GI8xmM0ZGRjA6OgqLxYLTp0/n+XGAnYhbc3Mzrly5wqpte3s7AoEAPv74Y9aw+vr6UFhYiPfffx/Xr19ntdjhcODBgwdYX1/noguhUAijo6NYXFxk9gOVSsWpK8BXfoJsdofShUzUiooKfPe730U0GsWDBw/g8/kYuHn16lXY7XacOHECk5OTaG1txbFjxzA/P4/JyUl0dnYyXYcYoSHfWWdn5y7nNo1fd3c32traEIvF8OMf/5hLeDc3N2N9fR1zc3N50ToyTQjpbrfbOQBClLYFBQUYHh7G5uYmfuM3fgNOp3NfBy8gz64qJ0C2t7cxNTXFnPSNjY2MWQOwy2TbSwORIr3FaJtUMInMFKIZCIALJORyOcYAmkwmqFQqVFVVobm5GcvLyygqKkJvby+cTicuXbqEwcFBmM1mJhKUe2a5MZCO317PKh1jeo+Kj2azOxV6vF4vjEYjDAYDM7GST9TlcmF+fh4LCwuoqKhAdXU1XqS99IKKNtzCwgKWl5cZEWs2m+Hz+dg5KdUexE1otVrx9ttv5/lqRBI4Ud2vrq7G+fPnsbm5ierqapSUlMBut+OVV17hDPyqqiqo1Wq0tbUxY0FbWxuKiorw9OlT/PjHP4bNZsORI0ewvr6OmzdvoqGhgX1rhN9SKpV55ddJexCJ56xWK5uAjY2NCAQC+Oijjxh4R/gitVoNl8uFTCbDPEnips9ms/B4PJiZmcHx48fzisVK/Rrb29vw+XwYGRlBOp1GZ2dnXolvo9GIuro6BgTW1NRgfn4eDQ0NXNzTZrPB5/OhubkZZrMZb731Fux2O/7H//gfiEQiuxz84txJN5Ko5UiFAh0Gjx49glK5Q/NLSbVSWl/x+3IanQhvoc+JSdX0uhSISXNFgo1SYihH7uzZs4yGLygowMWLF1moE6ymvr4elZWVfD9pMjM1OR+e2PYaV/H74rNms1muEhQMBjkXkUq3Z7M77LHl5eXI5XKchG2z2fJYOp7XXnpBdfXqVQakkdDIZrOora3lbHOpuSd1igJgQJsYYZJOIL3X1NTEUUFakIcOHUJPT0/eAj927BhaW1tRUFDAKN3Lly9jenqaTVO32w2Xy4V4PI5Hjx6hqakJBw8eZDOTomK0AEUhGo/Hcf/+fSwuLqK4uBhHjhzB9PQ0xsfH4XQ6cefOHdTV1UGn02F2dhZXrlxBKpVCWVlZXqCAnm11dZXTXWiRSscN2AHXfvzxxwiFQrh06RKampqwurqKGzduwOv1oq2tDb29vVAoFPjoo48QCASwubmJr33ta+xMpwVfU1OD27dvIxAIcKFUkcVUzmEtjrEovETMkhgsePr0KWZnZ1FTU8PJ2MBuk0lszzM96T0p3a5cCgt9ljBuarU6z4lOxUfoGUhAiesul8sxwJieUzoe4jhJn0Pa9vqMVLtMJBKIRqMYGhrijAmK5pHPbHNzk+c7EAjA5XLhwIEDsNvtDKN4XnvpBRUR4yWTSSwtLSEajaK6uhqjo6OIRqNobW3NKytOv8UFDcjTzUo3svQ9cTOLoXRaQBqNZhf3k81mw+HDhxnZXl1djR/+8Id5uCCVSgWVSoWenh4UFhayz4FMMqoJp1Kp4HQ6UV5ejurqas7t+53f+R2+BiHtyS8CgAGi5HPK5XaoVXp6epDJZPKKTAD5ZrJSqYTD4cC3vvUtaLVavq7ZbEZjYyN6e3vR2NgInU6H7u5urKyswOPx4MyZM6ioqMCZM2fwF3/xF7h58yZOnjwJl8uF2tpajjKWlpbmVbChMabxE8eetA56jZ6F8FoEC3jw4AEAoLu7m4MDorYjPp907mmMRA1cvJ/YHwB54FC5e8hpg6KfTQrLkK49OdNWTuMU/5cLAEjXsXg9UfhRfiGZ6YlEAuvr6wxFqK2tBQBEo1Gk02k4HA6sr69jZGQEpaWlf8dHRe3o0aPQarWYm5vDwsIC4vE4DAYD4vE4fD4fn3ripqTJoxOOfEuUf0Wai9wkymlZ9Lf4W/q3mI6hUHxF6K9QKFhrkoI1qcCmeC+Xy8X/k88MAKflmEwmtLS07BK8lHcmPYVJCFKf6PnFZ5P7TTXvSHhYLBYcO3YsTzPQ6XT4xje+wYudUPS/9Vu/hXQ6zWj9r3/961yTUKvVcpkqUaOT23Qi/TGZTul0Ok/r6O/vx+rqKlPbkCCRwzvReMhp4NL/RY1JnFfpZ6WmFACuryhnYtJ8xONxpvhVqVQMeclmd0geKYGeviuFcMitSTnTVtpEYUc/arWa3QpUAEOr1aK0tJQtBQoWWa1W5HI7qUBUautF2ksvqAgdrtPpUFFRwVnonZ2d8Hq9/L/0dBIXvNvtxq1bt9jhW1RUhPPnz8NkMr2wjS13stHfwO48rL0WqLj5pCaK2GfpRhEFjhyeB/iqGgz1R0R5i+Mjt+lEjULUNsT+0zXFfpLwo/uT9kXOdiKZE2mfxevRawqFIo+ZgYSRwWAAAN4YFP0Edgp2jI6OIpPJQKfTMWOB6H8Tm9zBI2f6iT5P+ozUJyVeU2x+vx+Dg4Oor69HbW1t3v2y2SxH/SKRCFQqFVpaWlBZWYnHjx8jl9uhdy4pKeHIn7jOpGagdB2Izyg1m6XCjH5vbW1hY2MDMzMziMVizNlOVMTPnj1DNpvFmTNnYDabMTY2BgCora1FfX39rsyAvdpLL6jIoUeLntC9brcbuVyON4DU7KMFT3gonU6H48eP8zWBfB+G3Cm018J8nna116lLQoa0I/qb/BqEVCYtcXt7G+l0mtHLJCgSiQRyuVweQ+TW1hbTrNjt9jxBR8hiou+gKCpl+pNmqtfrYbfb8/osbm6ps1n8LY6NqM2K4yFif8QKOHRCj46OMu+Rw+HgiryJRAIPHz5EcXExHj9+DIfDgUQiAa/Xi5WVFSYSfPr0KbxeL86fP7+rYo60r9L+SoW43DPKrQf6rlKpRDAYxOeff46BgQG89dZbLKjEyOHq6ioSiQQuXLgAn8+HsbExTgR+9dVX4fF4MDw8zKSIcoejXJPOk3QO5dZ2NrvDzUbrLJvdyd2kJHCC9GxubjLwlBK8CRJCwZzntZdeUB04cABmsxmrq6uYm5tDKpVCSUkJV79IJpN8OouLSHS4kmAijh2KtEhNAGpyCxLYjYreS8XeT/gBQCgUwsDAAILBIPR6PY4ePYqCggKMjo4iGAxCqVQyi8Hg4CBTbRw/fhwbGxt4/PgxYrEY0uk0Ll++jNLSUiwtLWFqagpqtRqHDh3KS9IFdhbvw4cP0draCrVajQcPHqCtrQ0bGxtYW1uDRqPB5uYmLl++jIaGhrxoWSqVwtTUFCoqKmCz2eDxeGA0GhGPx5ngrqioCFarFclkkkGtwE6u2urqKheHKCkpYdNPNCMXFxdRVFQEjUaD5eVlbG9vY3Nzk1kcgsEgM7qeO3cOU1NTePDgAWKxGLq7u/H2229jYWEBk5OTrMVJo2WipkEHhSicxGgerSGppi5q0KJ/KxgM4sqVK/B6vYxDEgWEKOTNZjMcDgcAcPpKJpNhgUHQFVGLkoNY7Lf+9jpEpZ9XqVQwGAyoqqrC5uYmVlZWMDc3x5Aei8UCh8OBwsJCxONxuFwuLvKgUqnQ2dm56/5y7aUXVOl0GtFoFDqdDtXV1axFNDU1MUnbXicjADYpJicnuWpJd3d3nhNcTihRk/NnyGlU4vv7/b+9vY3V1VVEIhFUVFRgaGgIAOBwOHiR9/f3s5/I6/WiqqoKT548gdVqxcLCAgoKCvD666/jZz/7GYaHh1FeXo7R0VG0tbWhtrY2jxVCvH8oFMLCwgKCwSBsNhucTieGhoZQW1uLlpYWjIyM8CaRaqj37t1DY2Mjurq68MUXX6CzsxNqtRrXr19HJBLB8ePH0dDQgGfPnuHo0aOMyo7H4/j8889ZKBUWFuLNN99kYQWAQ+EE8Whra8P09DST6QWDQda+yA2QTqcZNKtUKrG2tobFxUXWuIGvKF3EuZI6zcX1IgdF2O/QEteC1+vF2NgYqqurkcvlGKxL0WZaozqdDsvLy3jvvfe4PFprayuWlpZw7do1eDyevDkgoSquJan2Ll2H+2leciYhcaUROwLlm/p8Puau397eRmNjIzweD2OqqGr5i7SXXlCNjIygoKCAkbBUkolwPVK/idjERdjZ2ckgRzFRlD4HPD/FYj8n5Ys2lUrFSG6DwcBc4Z2dnejq6gKw4+eIRqNYXFxEVVUVDhw4wHmBJpMJAwMDDDp0uVwYHByE3+9npyyxaYpFLLLZLPx+P4aGhtDe3o4LFy5wfcOFhQXU1dXh5MmTu8aOFnIgEMCNGzewtLSEoaEhNDY2Mi3J2toas3VubGzkwQg0Gg20Wi26urpQWFiIX/7yl/B4PMwnnsvtlDIj35NSqURxcTFmZ2extLSE27dvIxaLsaa5tbWFeDyOyclJJBIJ5hm/evUqgsEg3n33Xej1+l3JxtJ5FLUr0QclPv+LrAt6z2AwoKGhAel0GgsLCygvL89jpaXP1dbW4vvf/z5isRgGBwcRi8XQ2NiIpqYmhEIh3LlzhzVJ+j6wm0eK7r2fkNrrPfH1RCKBmZkZrK2twe/3o7i4GAcPHmSq5IWFBSwtLaGwsJB9f1SOrbi4mH2Iz2svvaBqamqCWq2Gz+fDwsICotEoGhoaMD4+jnQ6jSNHjuQ5fqXqOvlF9Ho9Kisr83wX0oUopz2Jf/8qQkp66omvUS7V/Pw8FhcX0dTUxJEV8tPU1dVxkrNSucP6SGau0+mEWq1GOBxmbYNMpocPH+LUqVNoa2vb5QzP5XbAkWIhyb6+PgwMDOCzzz5DdXU1+vr6GOMjOtCNRiPXI9TpdAxmLCwshMFggF6vRyAQYFoSUYMhQrvS0lKYzWaeF3o/Fotx8c1sdod9QalUoqGhgdNOqJyXVqtFOBzG2toaj0t7eztsNhsePnwIp9O5q9r0Xv5CaQBBOn9y/iqxic9RXFyMd955B5lMBjdv3gSw42rY3t6G2+2GWq3mHMzS0lKsr68jEAigoqKCzdTp6WkmhhR9r9JnkJqjv8papDEX94vdbmefIrFwkLvEarUyI0QoFILNZoPX62Wmj56enhfqw0svqNra2qDRaJg9gXh5SkpKEAqFmM9J6l8QTw+VSoWRkREEAgHYbDbY7XZ0dnYyKlxse53AoobxPB+UeC3pZ0hDGR8fx8TEBDo7O9Ha2opoNIqHDx/C7Xbj+PHjcDqdmJ+fx9LSEkpLS5nsb21tDd3d3Thw4ACAnYINWq0WfX19aGxsxLVr11j7AMBqfS63Q5D31ltvYXJyEo8ePcLx48dhtVrx1ltvYWlpCVevXoXRaMSxY8fy+ry9vQ2z2Yyuri7kcrk8DqJcLscBAFE4iUBJEnhkWlFBUsJJKZVKeDweLC8vQ6vVYmRkBHa7HYWFhQyTyOVy7O8i00qpVHIO2qFDhzA9PY2xsTGUlZXlaTJS4STd6NJoGj2D3LqQc7Dncrm8oAhp/cCO6fvZZ5/BYDDgG9/4Bra2tvDFF19wUOCtt96CQqHA7du3MTo6iq6uLvT09OzicZdbk+LfotCU+6zcOqc+k5mu1+uxurqKxcVFrK6uMkSBYCFkHhNg9UVJ84C/BYLqs88+43wpqpSbzWZRXV2NTCbDdrKcg5F+19fX86mVy+V20X88T1Mik0Tu9eeZB+JmoZ+ZmRncvn0b9fX1qKmpQUFBAe7cuYNbt27h7NmzHMmrrq7G9evXEQwGmXtqY2MDn3/+OZaWluD1etHe3s7pLsR6QNQtIpyBAKVdXV2sfZSWlmJ+fh6FhYVwuVwoLCzMA4KKp3k2u1MEwmq1MjWxCHykA4F8STQn4oYjPBvxp9N3i4uL0dDQgBs3bkCj0cDhcOQRItLmz2QyjJYmKpTDhw/D4XDAbDbj6NGj8Hg8rDGKvssXMevFtbCXP4ia1KQT10JVVRVH0XQ6Hbq6urhoA80rUQRZLBZsbW2hubkZtbW1TC0t9mMvbU5unVGTc21IP09m99OnT7G9vVPCXa1WM5CTymh5vV4UFhait7cX8/PzWFlZQW1tLaqqqmA2m/cdV2ovvaCiRU9mjsPhQH19PcbHx/OAnsBuE44WT2FhIZf4Fq/7ohgQuVP5Rb4rt4iz2SwX6lSpVEgkEkyXSzQgY2Nj6OzsxIEDB5DNZhGLxVBfX8/Jq8+ePUMut1Npub6+nssdkS+orq5u1+LU6/VcDYUKfgI71C1Pnz7F5OQk0uk0ysvLZXFaBQUF7G+i8SUiwJWVFSwuLkKtViMYDGJ8fJxZLUgLfPToESe6Go1GRt6T//HVV1/FxsYGkskknE4n9Ho9h/eLiopw8eJFDhL8+Mc/hkqlgsViwcWLF1kj6Ozs5CozcvOwnym/16aWamXS1+WuV11dnUedQ+SOJPBbW1vz/H+53E7JKoVCkReNJHiNnH9qv2eQa9I1TD+pVIoPD6PRyNkD1dXVSKfTvE7VajUSiQSMRiNsNhsSiQSmpqZ2UWLv1V56QXX8+HEYDAbmTM9ms4zaDYVCrL4+DzsiFRpiVEV8X9r28l9JG11XCmKUam4KhQLd3d1c0Vev18NoNKKhoQFnzpxhHxoBKY8ePYpMJsOv2+12nDp1CsBXDlaXy4Wqqir21Ym+F3Gh19XV8TP09PRAqVSirq4Ora2t7LgtKyvL00RyuZ2iD11dXQw7aGhogMViQSQSAbAj7BYXF9Ha2orKykosLi5iZWUFJSUlaGpqQl1dHdRqNUpKSlBdXc0aA8FEyDylxFcyE4mqJZfLsW9rc3OTkd+NjY1cjYjmn3w7e6XGiGtE+rfcOpCaeHJzLo616C8Vx1GcF3FNkbYrwh1I8wIgmxMoJ6ykQkj6OemzUF8LCgpQX1/PtQe8Xi+GhoYwNjbG1Z6qq6uh1+tZUDmdTrjdbszPz7Mv63ntpRdUz54949SLmpoaGI1GbG9vo6WlBYlEIg/xLF1UNCGBQIBLEel0Oq7yKudkFf8XfV4k2MSFTwtNvKeUkE9qMiqVO4wIVCJL7ANFq8QFTAJL5GISK9xIT3ZxM4j9FIW5CIYtKChg0B59RzQZSWh2dHTwtSmth05eSqdRqVT43ve+l7dx1Wo13nzzTX5W8UARN6a4ybPZLHO0S3niCRmt0+nQ0tKSR6NMZqY47tKxEDepdIz2MqfkNr20yWUXiL+lfjECMNNry8vLCAaDzCZbUlIiK2T3WrNSM1T8LY6F9FkjkUge+R0dEJTF4Xa7WUs9ceIEYrEYnjx5Ao1Gg8rKSthstn3HhdpLL6hWV1eRze5UGSFgnMlkgtvtzmMe2MsXkcvlMDQ0xKjsbDYLu92OAwcO5J1W4m9qYmSE3pdDZ1OTWyhyGhWAPJ4ouiaBG8VFTU5MMa0kkUiwZkn9I7yZUqlkeII4JhS9k4bh5bQ+cYHLaZyiGaPT6Xal6NBz0T1J4xHHjj5Dgnd1dRVra2sAwOXt1Wo1zGYzC2afz4e1tTVkMhmmXCbqXuoTpe+I6UpyTVwz0vnZS8sW51WaT0ivEe++0WhkUKd0Pp88eQKPx4NsNgur1YqSkhLcuXMHpaWliMfjWFlZweuvvw6DwbCrwIXYpMJP2uQEnTh/5KOieo2xWAyFhYWor69HY2MjcrkcJicn2SdIB5zJZEJxcTGamppgtVrx13/913v2kdpLL6gIob22tobV1VVEo1G0t7djbW2NqUykCGSxKRQKhMNhlJWV4dChQ/yaSNUrNqkaLU1elgpDURvY71QTr0+4JIVCwblp6XSaC5DabDaUl5cjGAziyZMn2NzcxJEjR1BSUoLx8XHMzMzA4/GgvLwcFy9eRCqVwuTkJFZWVlBaWoq+vr48bU2hUDDYs6WlhRlLnU4nEokE53hReSRRs6INSeT+1H+NRsPPKzrRxTEUU35isRhisRhKS0vZhKTPE60MleWamppCXV0dEokETp06hXA4zNxYHo+HS5KFw2F4vV4sLi5Cp9PB5/Oho6ODn1/OxKPnkm5w6bxJ14Jo5knXCLAjFBKJBO7du4fbt2/j9OnTXIVIHI/FxUU8fPgQR44cQTabxdOnT7noxcmTJ7G6uoqBgQFm1ZQzOcXX9ssxlWqw0udTKBTQaDSora1FNptlACoV/iBmj9raWuj1eqavqaqqwtraGj788MO/c6ZTo7LSVqsVBoOB89bq6uoAfFUHD5DHi+RyO2FtSjuxWq3o7OyUdbhKFyUBDOn95zXpIhavTf0hQODw8DAUCgXnfUWjUUxMTGBrawtra2v49re/jaWlJfh8PqTTaXzyySe4cOECbt68id7eXtTU1ODq1atoamrC2NgYkskk+vr6UFJSwsJTuokGBwdRXFyM4eFheDweHD9+HI8ePWJNMxQK4Y033sgzBQsKChAOh/HgwQP09vZCo9FgaGiI02+I47uxsRGVlZXw+XwcyVQodqiP+/v7UVJSgpmZGRw4cIChFSQsiAH0zJkz0Ol0mJqaQjweh9frZYDn2NgYm0uEy6L8v8LCQhw9ehSPHz/G1NQU2tvbdwnDF5k7ubl83vt0j2QyiVu3bmF8fBx6vZ59N6KpmclkmGaHqlsTRMPn8+Hzzz9nQUzfEX+kh+R+/jPpZ/Z6XpVKxXtMr9dDpVJhY2MDXq+XGWXpsxqNBhaLBbFYDEajEfX19SgqKkJ/f/9zx/elF1RffPEFm2sUQk+lUlCr1bBYLHyyA/KnIuWYEdEepV+IGCqpJiT+LfqG9sLWvEijxUT+ts7OTpSVleGLL77A+Pg4GhoacPz4cTgcDvzsZz/jMPChQ4dgs9nws5/9DIlEAkqlEnfv3kVhYSHKy8uhUCgwMjKCuro6+P3+POoNqRbh8/lw48YN+P1+XLhwgbWQzs5OVFVVYWZmJk+TonGIx+O4evUqAoEA7HY7bty4wXl/lE5x8OBBBAIBPH78GGVlZRyho0rMDQ0NrFVJx47wUAUFBSgsLERPTw8mJiYwMDCAx48fAwDcbjei0ShSqRQqKirQ19fH6SbJZBLRaJRz5Ui7k5qbdF+pdiGniew3x6JgIFOdcjArKyvZlA0Gg3kah0KhgMViQTgcxk9/+lPu8/HjxxlEGwwGuXL189aTXB/l1rG00TrM5XYCUkNDQ9BoNLwvysrKUFdXB71ej+XlZQwPD3NBCq1WC6/Xi+LiYjidTvYRP6+99IKqqakJWq0WwWAQs7OzsFgsOH78OJaXlxGLxfLyoOQWJC3UlpYWruBLbT+fjag6S31V4mfF79B9xSbn8KQKuqFQiCvP1tTUQKVScT24goICmEwmWK1WjrQQJ5DFYkEoFMLm5iZisRhTHA8PD+Px48f49re/zcyn1LLZLNxuN2ZnZ/H9738f9fX1SCQSsFgs+PLLL3H8+HE0NjbmlbmnBU1Rx/v370On07FmU1ZWhvr6eubcnpmZYfwQPS8hsouKivJodUQtgcZYNFPIZ7KxsYGtrS34/X52+hYXF8Nut8PtdiOTyWBiYgKzs7PMQCClIBbnSjov+5mCctqL+D9FFQmlT9Ezt9vNmQQi7TQduD/84Q+RSCRYGBMAmSr7UNbAfn40uSa+Jz18yboQTUZCpRMHGq1Hj8eDRCLBfa+oqEBlZSVTKpWXl8Pv9+PWrVv7+gHF9tILKorsBAIBbGxscJi+uLgYFoslryIJNXEiCYfU39+PRCKBoqIiLmUlplqITZxkcYLlnK37mQfSJi6kzc1N3L17F6lUik2lcDjMpZZqamrg8/lYS0gmkwiHwzCZTDh//jwA4OOPP0YgEEBdXR3OnTuHRCKBq1evIhaL5UVjcrmdMmAmkwmpVAqrq6vY2tqCyWTC66+/zgJuenoaly9f5jw8UTDX19czXCAUCvHi12q1eXQtGo0mLwVHfG6lUrmr4jL9TqVSnBA7NzeHeDyO0tJSnD17FrFYDMPDw2yKELSDqEfopCeIBMEeaI6ob3J4OznzSm497OXTImHsdDrxrW99C+l0Go8fP4bP54PZbGa+J0p9Il9gLpdjn6LZbMbm5iYePnyI9fV1fO1rX+M0K6m1INeka1X6HbnDmH7sdjtqa2vZPeD1erG8vIzFxUWmdSksLOQxJQrtwsJCXgcv0l56QXX16lVkszsUvwRPIDyHw+HIC09Lf+dyO9nqPT09WF1dhd/vx8bGBjKZDAwGw666b/Q9+u5eAgnIDzu/iLotamjr6+u4ffs2AODSpUuorKxEIBDA7du3kUwmcebMGRQVFXHyLWlgGo0GPp8PHo+HGS8Vih0e6+XlZXZsi30U+9fc3IyTJ0/i0aNHGB4eRltbGxKJBI4dO8Yo+EAgALPZnFdlJZfLwWQy4dy5cwB2yAzFIgTkyyLmArVanQdHoKRjn8+XlxVAmgyxXF69ehVWqxVutxvt7e1QKBSMYqd+EB4rEAggHo+juLgYer0eHR0dcLvdWFlZYeZUml8SunuZcXKMCtK5f56pRX1Vq9Ww2WyIx+PQaDRIpVIYHh5GLBbDa6+9Bq1Wi0ePHuH+/fvQ6/X4+te/joKCAoyPj/NnpGytomCRviY3z2IjISXVtEhwK5VKPHv2jNkoYrEYV8vRaDTM+plIJKDVauFyuTA+Pg6dToeGhgb2eT6vvfSCigbW4/EgFAqhuLgYBw4cYD6qvcK3ogOwvb0dLS0t/B6BRPc7Qfe6prhYxBNaajKK3xEXfiqVQn9/PwYHB3HmzBlezLdv38bt27fx+uuv8/crKytx+/ZtVFRUcFGG+fl5fPzxx1zKqLm5GQsLC3jw4AHXXZNGYsjXplKpcODAAUQiEQwPD8NkMuH+/ftcVy6ZTOb5d0RNaXt7m/0RZOqQ05fGQORWojFKJpOYmZlhgXrq1CkWYNQ3g8GACxcu4MmTJ0gmk+jp6UFFRQXXRcxkMkwWmM1m8eTJE+RyOa7zGI1G4XQ60dLSgpmZGbS0tORpeuL95Da0nG9T7v+91oL0h3izCAPW19eH7e1tFtJlZWW4dOkSnE4na1c9PT3o7e3lepPELLFff8U+Sj8jald7uSxyuRwXnqDDxmg0ori4mLFcPp8PT58+5dxKYMf0VqvVrIW9SHvpBRVFFkKhEOccGQwGpFKpPBSvnGZEjT4nPTXlbP/naUTiCSw1YcTk1r2EVUFBAcrLy9Hc3IxwOIzHjx+jvr4eyWQSmUwGT58+RTAYxJEjR3DgwAH2gRBDwDe/+U0Eg0FoNBoUFhZCq9Xi+9//PjuRyfQSfTDb29soLS1Fb28vTCYTLly4gIWFBS446fV64fV6UVFRwZn04kbUarUoKiriaKLBYEA2m8XAwACePHnCwYpcLofFxUV8+umnsFgssNlsMJvNqKqqYh4wl8vF1xb9SLR5RXPHbrdDq9VyiXmTyYSjR4/ixIkTKCgoQGVlJdLpNGsBR48eZee+OB9S02c/zVfa9vqs1BUg/m+z2ThyqlQqUVZWlifwibNKXFsUeSX/pHjtvQ5EaaBgvwNW/Az1ldK2urq6mEonEAjA7XZjYWGBq3wXFRXBbrejuLgYsVgMtbW1CIVCmJmZgd/vf6FxfOkFlcPh4MrGer0eNpuNeagMBgMXFRDNA2mTU9+l7z/vNVFIiQtEnHQRNS5nHpCg6u7uRktLC79O1XJPnz7NETC9Xg+tVstMBuS0NBgMeRxAFK6nk5G0HFHTzGaz0Gq1nE9GxIO0qahsPYWoxf5ms1k4HA4cOXKEcVSHDx+G1WqFXq/HxYsXAeykrpjNZnz7298GAOZJNxgMcDqd0Gq1eYcFCSkpzkecL4rQzs/PA9gpO9XT04OWlha+ltFohNVqZX712traXQh1OTNOeqBIzaj9fFbiISA3xyIYVJo3SeaWqOHRbzktX/TjUYBhbm4OpaWlsNvtec8i50eT9l8qYBUKBftAxRJumUwGyWQSiUSCAbu5XA4WiwULCwsIh8PQ6XSora3F4uLirjGStpdeUCUSCa62G4/HYTabGVpAIe291N8XdfTJaWN7TbqoRUnNOlFgSq8vCjTCrogpKgqFgnFiImKetAPpZiNMlog4ly7YFxkXMoNJCEmjnHTCl5SU8DUrKytZSFB+Hn2ekr/F9BhxDMXnIoZO+i1qD/R/IpHA7OwsgB0K37q6OlmArVQ40HVIAMvNrdz4SF9/kTUlFW5Uzos+K9cvUUBTvcNwOIytrS2uMk2aIM1LJpPBjRs3cPfuXZSUlODNN99kR/hejnc5a0Ncj9vb21hYWMDq6ioUCgVz7vf19cFqtWJzcxOTk5NYXl6G3W5niuuysjIum3bjxo1dYyJtL72gMhgMMJlMHDoVCx1Q6sReTe6UfFGVX+rXkDapGbnX98S8NcJ8icJN1MLIH0Onq1yUSlzoIq9TPB5n4UEmmhyFrbjwxbLncuMjbixR0Iqfp2cQT2op42oul+N5S6VSTMBGPO3Z7E4VZ5pPjUbDyctLS0ucRlVXV8dmpzR3kJrohJYz+aR9l87581wA9Dm6t8j3lc1mMTc3h1AohKampjyoB80FRQW9Xi8UCgWsViu6urowMDAAj8fD93/ttde40AY909TUFKanp/HWW29hbm4OQ0NDqKyszCtwul+fxXkEdrTa7e1tOJ1OBjdHo1EoFDvFagmI63A4YDAYUFpaygwm4XAYd+7cQTQa3fOeYnvpBdXc3BwAMJaH2CAprCtnOlCTCgW598XfYpOeuvQ56YaWalHigslmd1gb5+fn2Rl99OhReL1eeDweJtYn/iiFYod2g+AFSqUSfr8fiUQCxcXFAMAIe/I7dXR04MGDB/B6vdjc3ERdXR3DF8Qx8Hq9mJubw+HDh+HxeLCysoK2tjYsLy8jHA5Dq9WirKyMWSlpkyUSCdZcpWMn4p80Gg2Xk9/e3kYkEmH8lNfrxYMHD1BZWYnW1lY8evQIJ06cQFFREQYHB5HJZPDs2TNUVlayM9lsNmNqagpXrlyBz+eDyWRCaWkpPvroIyiVO8nldXV1sNlsGBwc5Co+hw4dQklJSZ5/Sjqv0rERN7HcepAzrdLpNB49egS/349XX30Ver0e8/PzuH79OjKZDBYXF3Hx4kVmaCXBubGxgf7+fmYFuX79OtRqNWZmZvDKK6/AZDLhgw8+QDgczoOYKBQ7WQy1tbXo7e2FzWbDo0ePOLVJuqbl+ixqzLQvtFotKisreT6j0Sg8Hg9WV1cxOzsLnU4Hm80GrVbLyHo6cMRE9+e1vxWCKpfbCY83NDSgsLAQ6XSaOdRFzIx0oe0npPb6vLTt5YSV+w6ZP+JpG41GYbfbYTKZcP36dZjNZszPz3NpqgcPHiASiaCrqwuzs7MYHR1FUVERTp06BY1Ggzt37sDj8aCiogJHjx7F5OQk6uvrUVJSAqvVyjzor7zyCrRaLZ4+fYqTJ0/mlRQnjNbc3BwaGhrwxRdfwGg0oq2tDel0Grdu3WLiuUgkggcPHuCdd97B1tYWrl+/jrNnz3LInzZcOp3G8PAw1tfXEQ6HuUz9l19+iZKSErjdbjgcDhw6dAgPHz5EJpPBlStXWMOkfhGyXKFQoKenh9kYkskkHj16hGAwyBGmXC6HpaUlnDx5Epubm7hx4wZOnDiBoaEhrtocDAbxjW98A3q9HkC+Vig3/8/TsOXMJppfj8cDr9eLbHan7NTTp0/R2dmJiooK/OIXv8Dq6iozTdB36RAgv51Go0EikWBgbSQSYYEg7YNSqcTS0hKuX7+OtbU1BINB1tblnOpS01PcD+Kh6/F4MDQ0BL1eD7/fD7VajcrKShgMBgbdejweVFZWorGxEWNjY/B4PKirq0N3dzcmJib2HUPgb4Ggopw+QqZvbm7ixIkTGB0dRUlJCYB8cwuQFyhyr0tNwv0EFjXRSS2nbYl+BSpdpVAoEIlE4HA4EAwGEYlEUFVVhYMHDyISicDv96O/vx9PnjzBoUOHUFtbC61Wi8nJScTjcRw8eBA3b95EaWkpALCvwGQyIZlMIhAIYGVlBel0mjnDRf+QQrET7l5dXcWVK1eQyWRw6tQpGAwGtLe3Y2ZmBuXl5Rzef/DgAcrLy5ke+dixY7t8bysrK3jy5An6+vrgdrsxNDTEzJCXLl3C6Ogo+vv78ejRIxgMBpw7dw5Xr16F1+vlqjOij21rawuDg4MIh8Ncnokiu2LQpLCwEC0tLUilUtjY2IBCoUBJSQkOHz6MtrY2/PKXv0Q8HmdBJTf30tf3E2bSz1LT6XTo7OxEf38/MpkMO6RdLhfKy8vhcDgYpU/rAgBzqX388cdQKpWYnp5GW1sbLBYLHj58iGg0iuXlZcankQZEdD9UTbmyspKhIHJrmH6L8yY9mKlvFIwxGAyIRqPsULfb7TCbzXxvu92OTCaDoqIiJBIJrK6ucqDjee2lF1REdD89PY2FhQUetMLCQqYY2cvBSU1uAqV/yy3kF3Wkio0EJqVxUJb/o0ePEA6H0d7eju3tbQwMDMDtdmNsbAytra2cOkOpL5lMBjMzM3A6nWhra8Pq6ip8Ph/i8Tg+/vhjBhe++eabMJvNGB4eRjQaRU1NDfdL6mCenJzE/Pw8fvu3fztPQ9JoNBzxAXac1h9++CGAnWielHqG0P4OhwOtra1obW1FMpnEkydPsLa2hv7+fkxNTcFut3Ppp4mJCXi9XjgcDmxtbeHRo0fwer1IJBKwWq1cwIMEDM1tOp1mH1g6ncbS0hLee+89ZkelAhPUV0LPyx1E+wkrufekcytdLwQDocIIdCCQP5L6TnOwvb0Nq9WKb33rW4hGoxgfH8fy8jKsViu6u7sRjUa5ohD5H4F8SpzKykqcPHmS6x6Kgor6tZd2JbU0FIqdCHB1dTWjzAnkSTUSiRra6XQyHbTD4YBOp8Pi4iI2NjZ2jadce+kF1ZUrVwDsnEQVFRUs9evq6lBVVQVgbw1or8W310Tu5aN43vWk1xGvt7q6inv37mF7extnzpxhrp/29nau5kECLZVK4eHDh/D7/Th06BCSySRrEqWlpQiHw+ju7obFYoHT6cS1a9cwPz8Pi8WCS5cuYWVlBYODg4w5Ev00W1tbcDqdHN5ubm5m81DUAlOpFBoaGqDRaNi5CuQTw5GwIrI8lUoFvV6PUCgEj8eDzz77DLlcDr/xG7+B/v5+NlHIBxcMBtHf349kMolQKIQLFy6gsLAQhw4dQkdHB3K5HILBILLZnQrZRUVFLIyICmZ8fByvvPIKbDYbCzEKVmxtbbG2sJd2LTe30s/s5XSna4opQQUFBUgmk1hcXGQNmlKR5ufnuX6fVqvl4NDU1BRcLhecTicfTFNTUzh8+HAeJTRpnUT6CICr71CqjVyfpWtafBZxXIj2h8Cz2WwWZrMZBoMB8Xgcfr8fMzMzsNvtOHv2LFZWVjAyMoLy8nL09PRwVHa/9tILKsJzxONxbG1tsV+KohLPi85Qk3Ouyp1Ev4rPQu4kFgVWMpnEl19+iampKbz22mucn0Z+GrfbDbvdjoqKCqTTaXR2dqK7uxs3btyAx+OBQrHD/Njc3AyPxwOlUslmAlVoSafTDN8gZLp0DAhb1d3djcrKSty5cwdjY2Po7u7m/pAmkMvt4JfeeOMNJBIJ3Lx5My9gQBHJbDaLVCqFXC4Hn88Hr9cLpVKJ48ePo6SkBJ988gkCgQA0Gg26u7vR19eHZDIJv9+P8vJybG5uorm5GU+fPkV1dTXW19d3+cC2trY4/YXwXSUlJUwHE4vFGP0ej8cZGS9n6oh+nr3mVW59SMdyr+AKpZTcv38f8/PzsNvtcDqd2N7exuzsLNbW1hhKMDAwgHv37qG0tBTnzp2DyWTC+Pg41tfXcfDgQXR3dzNchH5UKhWzFVDUu7m5OQ+eI4WoSNeq2ER4TSqVwsrKClQqFfx+P/R6PcrLy1FeXo5kMom1tTU20wFwYON5xH5ie+kF1cmTJ6HX67G0tIT5+XmusrK1tcUlifZT2aULS/xbupDFhSc2qQ9Meh054UYburKyEtFoFGtra4hGo2hpacHW1hbu3bsHhUKBc+fOob6+Hqurq7h9+zZCoRDW1tbgdDpRUVGBW7dusYbR2dmJoaEhpFIpVFVVYX19HU1NTZiamsIvfvELWK1WNDY2wmAw8KIiPq2CggKYzWb09PQgl8thfn4eVVVVmJ+fx+joKHNjA+DirlIGAhpP2tDT09N4/PgxJ4uTn6O5uZlzK+12O2tBLpcLFosF1dXVnCfW0NCAmpoalJWV5QFZfT4f09pkMhk4nU7U1tZienoaer0evb29uHPnDtbW1rC5uYk7d+6wdiEHA9lPeEnncT+NWnRQ0/PS+HZ3dzOqv7OzE0ajEblcDocOHWJmWnqvvr4eJpOJMYH19fWora1lDVoqOInp1Wq15h0a4mEpapH7WRli02g0qKioQGtrK6f4RCIRjI+PY2xsjHMXa2pqOCJMtOBLS0uYmpqSvY+0KXL7eX7//7iFw2GYzWZ885vfhEaj4STPwsJC2Gw2xGIxnDhxAocOHZJFH0v9EiIeiJqYD0WLQs6Uk353ryGX+jAAsKOYfsivQfX4KDM9EolgYWGBfTrV1dWwWq14+PAh5ubmUF1dzdCGwcFBDisfPHgwj1pEPOloHLa3txGPx5FOp2GxWJDJZOD3+1FYWIilpSXMzc1BpVKhsbGRsU2dnZ1czbe9vR0Oh4PHivp769YtRCIRlJSUcM0/ACgrK0MikWDTlXi4qYCERqPZxQgqanTZbBZffvkl3n//fRQVFeHNN99EV1cXtFototEoioqKoFQqGeKxuLiISCTCEIv6+vo8Zk0SQvsdKrQexP/l1pL4na2tLYTDYe4Paa9y9xDNOPGZxTUmCkGxwpI0CVmq9RFqXXp9uQwKsdFzPXr0CO+99x6Kiorg9/sRDAYZt0jztbW1BaPRiKNHj8Lv92NkZISvMTAwgFAoxBTYcu2l16gmJiYQi8VgMBjgcrm4bE8ymdzlIJRzmBJ9iEKh4Iq+cg54ERwoPZnECZeCQJ/nAyDgpljLLpfbyW0TW1FRETo6OtgJT/c+evQoDhw4wGk1RAFDGgz5isQ6eHJ9pFA4AUUpgtja2orm5ua8Z6TCEyaTCceOHcvDUNF4mEwmXL58GalUih374phRf6kfIgBTuoHEfqtUKsTjcczMzGBrawvFxcVobm5mfBUl8QJAeXk5tre3GWNG18vlcoxIJ0FNm1lOWIkCgja+3HqSAnlp3sT7SpHn0vVEcyt+R7yeeKiKByg1aZ9o/KT9Fa2DvSwA6lcymcS9e/fQ0dGBubk56HQ6Js9TKpXsO4vFYsxOCoC14oGBATyvvfSCiria/H4/VlZWmHd7aWmJixkAu+1z+r25uYkvv/yS86Ta2tpw7NgxVrnFicvlcohGowgGgygrK8s7lcX2PD8WNVqYbreb4QnSii/0OaqSQ+kkdKJShJMQ7AqFgrUU8fviZqCMdr1ez/XzyHQQn2cv342YliPSrIjPRac+MXmKm12lUrFpLh4MUoFAf4sblqiYZ2dnOYggl7BLAQKpIBIFn1QoiYJIzumcy+WYPocEq5zJKL2eVJOWWy9SYSe9llx/5ZqcNi+OJ42DOJ/iHEu1RGAnL7OqqoqLNlCi99raGleirqmpgUKhYJZVKks/Ojq6b3+pvfSCqry8nIsj2mw25pEqLy/Pq4Ai1XCoUcn3AwcOwOfzYXBwEFVVVTzw0lMrFArh2bNnXECTmpx5KLd4peamx+PBtWvXGLT5ta99jdNAxHy0e/fuYWJigtk8z5w5wxtGLH1OG1vcdNnsDs2wTqeDyWTC8vIy4vE4ent7+ftkltAz7KURSk9r6bOKJokYPhe/R1S8MzMzOH36dN6BIBUOojalUOwkyN67dw8+nw9arTaPm0n8vqiZiBoJOdfdbjcaGhqgUOxQBFksFni9Xr4OpWaRtplMJpFMJmEwGLhsVSaTYUG8tLTEJcypgtGLCBZxfUjHV7pufpW2lxlHf4sarJyWRZ8jzbm3txe5XI7pqVdWVrC2tsZarNVq5ewDrVYLq9WKRCKRB0zdr730gur27ducflJXV8cVWwoLC2G32/eF8dMCpuqvLpcLbrebSxpRKNZqtaKiogKhUAhzc3MYHBxEUVERDh48iGw2i83NTa4mW1JSwn4m0elJUTDSekhAhkIhFBYW4uzZs3mYE3GxkkAyGo3o6OjAzZs3uQpyIBDA+Pg4F1agJtb0Uyh2OLtzuRzjcYggUNTQqJ9UwBP4arGKJgSQr2GJh4GU9YDeE5OMFQoFHjx4wFoQPStFKKk/lBIVj8fZSbyxsYGHDx9CoVBwtWS6j9QPQ5uExo/6Ho/Hce/ePTidTvT392N6ehq9vb24evUqysrK2LFfUVGBpaUlnDlzBsvLy3j27BmKi4tx7949mEwm6PV6NDU1wWAw4IsvvkB7ezsmJycRjUZx5syZXVqm+FvOvBT7KBVWcpqZuFaedzjK/b3Xa1KBlclkMDw8DJvNBp/Ph0gkAo1Gg9bWVmSzWXi9XkxPTyObzTKGanR0FGazGV1dXZicnNx1T2l76QUV1WmLRqOYnZ2F3+9n7EZPTw+A3U5x2iDZ7E7uUiQS4dOQNk4mk8H09DS8Xi/C4TC+//3vc4pCMplEJBJBJBLBysoKV41dWlrC4cOHcfLkybx7Uf/u378Pv9+PVCqF4uJiXLx4EZubm3C73TAajTh06FDe6Sb6FojCpqurC8+ePWPYQDwex9zcHEMJSMiQ34hSLzY3NzE9PY2ysjJsbW1hYGAAuVyOsVc1NTW7xiiRSDDEgyhepKYeQQUUiq/YNslJDnxlXpKZR/mJExMT+OY3v4mVlRUEAgG0t7fj8ePHUCgUMBqNCIVCOHjwIK5fvw69Xo9Tp04hl8vhzp078Pv9KCoqQjqdxuzsLKxWK7NKhkIhlJaWoqKiAkNDQxxGB8DASzJ/l5aWcOPGDVy6dAl6vR5OpxNvv/02crkco7wnJyfR1taG0dFRho10dXXh1Vdf5XlaXl5GZWUlLly4wAykqVQqr0AIsDvaLBVCcsKJ2vO0s70E0H6CSa4P9DftD9FUJNgDBa3Ky8thsViwubmJ2dlZBAIB/k5ZWRlHhl+kvfSC6sKFC8yHvbCwAI1GA5PJxJVcpZWJRUFFvgsilCMzKR6PY319HW63G9vb29jY2OBqLEeOHEFBQQFOnToFpXKHpjUWi+HMmTNIJpNYWlpirm7RtxEKhbC6uooLFy4gmUzi448/ZjjB8vIyBgcHcerUqTzSfuCrBbS1tYW7d+9ibW0N4+Pj6OvrY0dnIBDgsPCdO3cwPDwMvV4Pq9WKc+fOwWAwYGBgAD6fD8vLyygoKIDT6URdXR0mJia4OgoJNRqnhYUF3LlzB6lUiulnL168mOfrUavVcLvd6O/vx6lTp+DxeLC2tsYYqLNnz3IC6xtvvMEoebPZjOrqarjdbnz66aeYnJyEx+PBq6++irKyMvz1X/81Hjx4gIKCAnznO99BQUEBlpeXuSKKRqNBZ2cnbt++zVHJEydOwOfz4cMPP0RdXR2mpqbw1ltv5WltNKaLi4v40Y9+hI6ODj7YCFir0+n4p7S0FFeuXEEwGMTbb7/NaPmtrS3uR0FBAUM+ysvLWXuVNjlflSgc9kqQfp52JN5LjOrtJfye1zfaH9RHyvsknx/RXS8sLMBgMDABYklJCWMBXS4XfD4fpqen9968QnvpBdXTp08ZL1VSUsJc4kQclk6n88qzk3ZA+W4EnEulUohGowgEAvB4PBgbG0Nvby8UCgXTGpMZRD/AjrmSSCQwPDyMZDKJgwcP7kpNIQFgMBiYprW4uBgFBQVoaWmB3W7H0aNH82hV6F7iYuzp6UFtbS1WV1fh9XoZjUzOdGCnBHdZWRkOHz6MQCAAn88Hl8uFV155BXNzc2htbcX09DTq6urQ3t4OlUqFu3fv5qV5iL6tUCiEUCjEuKBUKgW9Xp8n5EtLS7G5uYmf/exnUCqV6Orqgs1mw+bmJv7qr/4KAHDkyBGo1Wouv9Tb2wutVova2lo0Njbis88+w+HDh+FyuWAwGFBWVoabN2/i0qVLKCkpwfb2Np48ecKEbCaTCWfPnsXNmzdx/fp1/L2/9/dQXl4Ou93OrAqnT5+Gy+XaJQBIwIfDYTQ1NTH7w8rKCj799FPY7XZ0dXWhqqoKBw4cwI9+9CPU19ejsrISXq8X9+/fZy3q5MmT7LAnX6HU1JQKC+khJGd6Sdt+kT4557ycoJITbNIAxl4maDweRyKRyPNjUgAqmUzy+mtpaYHL5cLY2Bj8fj9DLJ7XXnpBtbm5yWWSiNRLr9fD4/EA+AqnJCVHo59AIIDV1VU8ePAAoVAIJpMJarUaXq8XbrcbTqcTNpuNNTDyNVHtQIpstbW1IZvNspkB5E8+lXTyeDwwGAys7RkMBhQVFbFaLfoapGH6srIy9PX1wev1MpULobKBryI6PT09DCkgjdLpdGJ5eZk/T1ExEtqkIdC9tre3UVtbi3fffZdpkCn5V2qe6nQ69Pb24i//8i9RXV2N1tZW2O129Pb24s/+7M9QW1uL1tZWFBQU4N69e1AqlczCSWajyWTiMSdzorOzE2tra0zl09/fz4KcqFqoluDa2hrT3pJg3dzcRCQSYbofcXxJgxwaGkJ9fT0DG48cOYLCwkKOvlZXV6O5uRkNDQ0M0KytrcXZs2dhNBo5ZYvmO5VK5flEpRv+eUJKbHICR/q++Huv1+W0KVEgSe8hDaBks1ksLS0xN/3m5ibMZjNaW1thNpuxurqK5eVlRCIRNvHVajUnYL+IVvXSC6r29nao1WqsrKxgZWUFANDR0cFRGp1OJ+uIJOHhcDhw7tw5KJVKVFZWoqKiAiUlJdBoNJifn8f8/DyMRiNHNIqKilBWVsY19Nrb2/Ho0SM8efIEOp0ORqORy57Tvcghr1Qq8cUXX7CGReychF/aCzi6vb0Nj8eDcDjMZHFtbW2shgcCAc5ql4aYKZiQy+WYBZUEEwknq9XKUAtxcer1embrpPdEvxlBDYLBICYmJlBVVYVkMomxsTEoFArMzc3B5XIhkUjg6dOnaGhowJMnT9Da2sp5bktLS9jY2MCbb76J2dlZPHv2DGVlZSguLmaWhdnZWRQWFsJkMiEajSIWi6GsrAw+nw+VlZW4fPkyZmdnMTExwQSB3/ve97i8PXHLiyY1sVQ+ffoUX375Jdra2qBU7rAvWCyWPAiCqLFqtVrYbDZUVlZyVHl7exuhUAhLS0uYnp5mNwKwd7ROTrvZr4lmovS1vUxEuf9Fd4QUXyXXF/LXORyOvAOaqHUIU0WUPDabDYlEAi6XC6lUCsvLyy/0fC+9oNra2mJQYV1dHed4kbkgJQ6jRhPkcDhQXFycN1lKpRJHjx7F0aNH2bQjDBM5vUkodHV1oa2tDcDeizKb3Snn9c477zC1B1VyVqvVnEVP1xAFFf3U1NRgbm4OMzMzqKioYEEVCAQYW0SaAKWIiKajWq2GRqNBKBSC3W5nLBUVVSAti3LoAOTBC/YyZQh9XV5ejldffRWrq6sIBALwer3QaDT43ve+x6R9xFnU3d3NQtpoNOLcuXOora1FT08Pa27t7e0cRc3lvqLv/elPf4qioiI0NDSgpaUF7e3tKCws5OhfJpPB4cOHYTKZ0NrayiYtjSewA0lpbm6G0+lEWVkZHjx4gHA4jGg0is8//5wLu/b19bHgIg1UoVDgyZMnSKVSMBgMKCkpYUT84OAgTCYTDh48yCwN0nUh5yOSi+BJP7dXlI/+lxNKojCUalBywk3ufgrFDlSjtbUVfr8fkUgEBoMBbrcbIyMjUCgUfIgQ9xutl0gkglAohBdpL30KzZEjR+D3+6HT6VBdXQ2bzcY+lNdffx1NTU15Zd3lTo69FoT4mtTnJNa1o8+Iwm4/oQXsXmxSn4N0IYoOTvHziUQCsViMCyXEYrG8Yg7UXwC8yIxGIwtHMQWDzGRK3N3PDyJqVbSJaaGKEVTKDyNgKQD2GZIvTBw7cVxIMCiVOwVIr169iitXrqC8vBw//OEP4XQ68/pO47LXHNIziYEAhULBmQnhcDgP91NaWgqNRgOv1wuVSoXi4mKGqFAxCioekU6nOSpKCdJ7rTPpenue0KF+0+vkGxQFkuiMp7UiFl2QwkXIvJfeRzq/CoUCfr8f/+k//Scua+bz+fh9wpVtbW2xJnXhwgXcvn0bbrcbBoMBg4ODf5dCQ2V6vF4v5ufnEQwG0d3dzZEwUuHlCPzF/8UmJ9REQKVUVaaFJOKJpHa+eG2pdiI1rcQm9WlIG1WdofdpMUgxRUqlkv0upM5LN69C8RVmi+hJxOeX06ikmyeXy3GuHl2LtDv6HPnGxDETf1MfxchpJpPB6uoqzzmxQIgbWfTrSVHo0r6LRTGIrI6Eu7RRSgjlsx04cICfiTBfoiAR7yc9yADkmePS74iaMEXZaMzC4TBT/Docjl1ZF/S5+fl5TE9Po729HZWVlbtAwHuZeWIT+0VpS5FIBFarlXMzKXIcjUbh9/sxPT3NFEItLS2oq6tDLpfD4ODgvvcC/hYIqubmZmg0GmxsbGBjY4OrtJjNZllno/Q1OTWb3pebVHFRiBrFXlqU9PpyPqS9NAo5H4RU0NHr9D/5jcRFSVVsqImbRPqM4ianU5vMXroWCRq6l5yJKAowOUEumuT0edLoCAlO5h5hmlZWVrhPpEVSn+kwEjUssaajOD7i3NDmlvMPikJVejCJ5ij9SE0u8dnE5yZhQ8nh4vWVSiVWVlbw6NEjKJVKqNVqHD58GDMzMxgaGoJWq0U4HMZrr72G1tbWvLWczWa5bmI8HsfExAS+8Y1vwOl05gkqad+k60i63ijTAwD/TYdSPB4HsEPtQpFecc2kUqlde0KuvfSCigj0iVrCbDYjHo/DaDRyCgSwG1citv00KqmQEZucOi0nHEWNif4WhZ2oSdBiXltbg1KpRHV1NfugKA2GytVns1nmDCeYAl2L4BfU93Q6zY5Q0TShyKHb7UY4HEZDQwMHJoxGI0MIiBzNarXiwYMHLGTOnj3LJhjwlbbg9XoRjUbR3NyMWCyG2dlZ1NXVYXFxEYuLizAajWhsbITRaEQwGERVVRVCoRAGBgbQ2NjIxHmkxZSUlGBpaQkqlQqBQABjY2Ow2+2sGYnaBZl1dIhIE33Fw0KcQzkck1TLFeeSBCJdU+oLo/7QvcgHFg6HoVAo8Oqrr6KysjKvYnMul8Onn34Kg8GAtrY2XLt2DQAwPz+PpqYmdHd34/PPP8fq6ipaW1vz1lMul8PNmzdhtVrxjW98Ax988AGePn2Kqqoqjq6K/dvrMJYeahSdjUQieRAaEfZDGQVKpZLT2MR7Pq+99ILKbDYjk8kgHo8zm2VDQwM2NjZY2gN7R0jE31ItQ/pbFETSv+VOJ3pPvL74ebFv9BmFYgcy8dFHH6GyspIX2f379+Hz+aBQKOD1enH+/HkoFAo8e/aMQaLnz5+HwWDA/fv3EYlE4HQ6ceLECayvr2NkZATRaBSZTAbnz59nbilqm5ub+Oijj/CDH/wA9+7dg9/vR21tLYqKitDc3IxUKsXjGwwG8frrr2N4eBjvv/8+fv3Xf53zE4Gdzbm+vo7V1VW0tLQgk8kwU+lHH32EpqYmzM/PY3h4GGfOnGEmy62tLUxPTzPN7htvvIGNjQ3cvXuX+15aWorLly+jsrIyT5MVx14amBDNQPot9WWJ5ud+B5rU7BWzHEhoShsBip8+fYrJyUm8+eab+PTTT9Hf34+Kioq8NUD9OnLkCJqamvJyCKuqqmCz2WAymfKAzKQR0t8tLS2wWCzMm06+PiD/UJU+u/RZxTHzeDyYm5uDyWRiEsbq6mqmrF5bW+OIK/n8jEbj35V0p9bW1gatVou1tTVMT09DodiJQkgrEktPQrFJhZWcGSj+Fj8r97rcd6mJp5/cogEAi8WSV9qcuKAo5+yDDz5AJBKB1+tFc3MzysvLcfv2bQwNDcFoNGJzcxMtLS24ceMGs1oCwOHDh3Hz5k1MT09z2XAaD8rP+slPfoL19XVUVVVhe3ubsWLZbJZr75lMJjQ3N8PhcOAv/uIvdmmMxOTg8/l4kwQCAYRCIZjNZrzzzjsIhUL48z//c4ZXUGoGIeP9fj+2t7fR2tqK2tpa/Nt/+28B7EA5aLPKHRr7jb30wNnvtJceXNJrSude1IjFuRavlc1m2UQiH5s496IGeOvWLayurmJ0dJRxabdu3cKzZ8/w8OFDnDp1Kg90S/fd2trCtWvXMDU1xZTScnUU5Z5FbKJvkUC9sViM5yaVSmFhYQEej4f5qNRqNSoqKrC4uAiv18u/X6S99IJqaWmJAZ9lZWXQ6/Wc5W40GvMI2ET/i5xG9au0/SZZrokCir4v9RvQe0ajEXV1dYyIV6lU6OzsxMTEBD744ANUVVWhr68PP//5z7l0UXFxMZRKJTo7O9HV1QW73c4JvVtbW2hsbER1dTXKy8vZLBTNFqKyJWZPOZQ8CS6qoUhYGuCrQqmiX2hkZAQ/+clPkE6nEQwGkcvluI6dyWRi/xZBNqgftbW18Hg8+NnPfoaqqiqUlZVxOlM8HsfVq1fx2muvMWeX1LyXG3u5A0O6eaVYK1G7ktNCRPNPTMnay0dVW1uLTz75BD/60Y+wsbGB2traXdpdNpvFmTNnMDg4iJWVFXi9XrS3t+P06dNYXl7msadcT/GAoPmprKxkbnmaFxprUfCK4yYdG7FR7h75KS0WC3w+H6eWUaDGYDAwbpE0LZ1Oh5mZmT33BbWXXlBFIhHMz88jm82iurqagZiRSIRPBHEy93Ioyk2g+Bk5826v9ryJ3+s9qSlJ2gU9h1KpRCAQgMVi4SIAX375JWZnZzE2NobTp0+z74qSkNvb2+F2u3Ht2jWMj4/j6dOn+OY3v5nnt6F7Hzp0iKM4c3Nzu3wnBPtQq9VsUoiJt+ImzeV2Sru3tLRgc3OTNxltHFrEVPJKLIJgsVjwta99DT6fD48ePcJ/+2//DaFQCCqVChcvXkRDQwPMZvMuU10cT6nGK3WIS5voTJd+T6pxy31OzAKQm09C0VutVhw9ehTz8/NYX19HJpPhzAL6HB02xK5qNptRUVGBsrIyjI2NMQBTvAfdX6PRoLGxEZ2dnUgmk3wPqQDdby1K90EqlcLs7CyGhoY40ZiQ/DabDalUigvY5nI5lJSUIJVKYX19fRcB5F7tpRdUuVwOLpeLa9eZTCY0NTXB7Xbv2viAvCYkPUHptb1OZ+n3paftXp/Z6zr0nuhcFyNRwI5K39bWht/93d/FT3/6U0xNTeHy5cuYn5/nun8UkZubm8Mvf/lLlJeX4+DBg9je3sb4+DhXVSZENd2fNpjBYMChQ4fw7NkzrKyscJWZTCbDJISk/SQSCSb8F6OQ9Ht7e5vBncFgEDMzM8zhlEwmkU6n8/wZtNEAYGFhAUqlEk1NTejt7cUXX3yBXC6H4uJiOJ1OFBcXy8IO9jpMxPGlJoIfxXmQmv9yGpb0WcVnFoWbdM0Rl31vby+sVitGRkaQzWbh9/sxOzvLPp9EIoHl5WW8//770Ov1aG5uRiQS4TqIDQ0NaG5uZp8Ute3tbZSUlMBgMHDZKq1WyxFJueyH/YSXeEATSyvdhw4btVrN8A6aXxprtVrNqWzPay+9oOru7oZSqUQ8Hsfy8jI0Gg2rn6I2BciDPcUmqv9yqr74OfG6tOj3wlnRZ6Tfl7sPXYNC39nsDhXNnTt30NPTw0UdKLxfXV2Nzc1NRqWPjY3hl7/8Jerq6vDaa68xDc6RI0fwxRdfcKEEUbjQ/UizofJWCoUCAwMDiMVimJ+fh8PhwMbGBubn5/Hzn/8ca2trjCAnU5L6r1Tm0yurVCoYjUYsLi7i/fffz/N5ud1uLlxBqU937tzB/fv3EYvF4Pf7oVAouOpNYWEhSkpKcPLkSY500hw9z18oflaKZ5PzM0lfkx5m4jyLAFVxXmlNaLVarKys4M6dO/B6vTAajVCpVNjY2MD169dx5swZFBcXY21tDR999BGKiopw6dIlTvqORCLo7u7GwYMHYbVad62jgoIC9PT0cMSzvLwcZWVlu9Yl9V1O6Ip/05goFApUV1ezmUuJ6pubm3yolJSUMBcV0UxXV1cz9u157aUXVPPz83knMoXNCQQpbWJkB9hb05H7X6qNiTa/1FQTPyc9Xel/6YYgYadUKhnRncvtYJc8Hg9+/OMfc/JySUkJZmZm8PjxY6yvr+Pw4cNwOp344IMPsLS0hJaWFszNzXHU8N69e3C73Th9+nTeIhf7RMnXZrMZjY2NXHE5m90ppUUc2UVFRdBoNNBqtXA6nXyiiiSFzc3NcLlcAHZSVs6cOQOHwwGLxYLFxUVks1kcOXIEDocDmUyGi4uePn0aLS0tsFqtiMVi8Hg8mJ6eRjKZxMmTJ9HZ2ck5ZjTXFELfzzyXmvdyZIBym/VFmngwSTU1cX4bGxuxvr6O5eVlFBcX4+DBg9BoNCgpKcHbb7/NidZOpxN//+//fahUKs6qsNvtuHTpEoB88K0UKEtzIWpOctrmfn4qqVWhVO5wiI2NjUGv1zPUxWAwwOFwIB6PIxQKYX19Hel0Gj09PbDZbOjv789LJdqvvfSCinLUUqkUIpEIp2qI4XJxIoG9F6E4MVKNR7qI5RajnNNVej85U0Xuvbq6OlbrdTodvv71r8Pj8SCdTsNoNKK0tBQ+n4+pSOrq6qBWq5le1+/3cya7Xq+H2WxGZ2cnCxu6F522FRUVeSXh7XY7gB2WAunGJ8c9AHYki2ZrLpeDzWZjgUiUwblcjisnk0NfoVDgwoULLJCJwYFy94aHh9ks7ezsRGdnJ99H9DdKw+tycyvOk/j84tzT89DnxPek19nrPmTCSn1barUaZ86cYYc4+feIKZQagUHF7yoUX2UNiNqgVEAqFDs4vGAwCLPZvAsUKzVxxTHZq21vbyMWi2F5eZkFDxE5Njc3w2AwYGlpCSMjIwwJMhqNsFgsfyeoqFHJHuLLiUajCIfDKCws5AmUEwqAvHNURFfLNdE8lDYRyS1nItA96TU5E4IWudFoBPDViVlUVISioiJ+JqquQkm7wM6mO3nyJJP6kZ8AAPMyyfVFodhBH1NajbhRafMCX+GTRM1JTAcRNyiNLfkyRDCk6I+SpoGIUbDt7W2sr68jGo2itrYWpaWlu/ov9zxycyZnuot9FedUzjSX047ps9Sk8ym9Jz0bacXi/Ervl81mEYvFoNVqGScXiUSwsbEBnU6XN+9iHxKJBG7cuIHh4WHU1tbi9ddf5wT95wlcuXVBc1NcXIympiaYTCYEg0HEYjGmWCKAbUlJCVwuF4qLi7G9vQ2n0/l3PipqMzMzCAaDUCgUqKyshEqlQigUQkVFBdvqe2k6YpMuUmrixKZSKWxsbKCgoAClpaUcJg4GgwB28E8i1W0sFoPRaGShQykFGo2GE2KJ4YH8O6LjkzaQ2C/pJpBubmKclJqY4qKT0xhE53QoFMLW1hbsdjv7PkThHQgEsLi4iLq6OpjNZvh8PvT39zMSmUopPXnyBD6fDwBQV1eH1tZWrK6uYnx8HEVFRWhpaYHJZGJ6lnQ6jeLiYjbvtra2EAgEoNPpUFFRAYvFwv2W+oykG32/OZbzXVGjOaDxoA1OYywXHZTeVzpPNLdE7xMOh7G1tcUah1SoKZVKjI6O4vr16ygpKcFbb70Fg8GA/v5+3Lt3DwaDAV//+tdRUVGR537Y3t7GyMgIRkZG0N7ejmfPnuHJkyd4/fXXd1kU0gPzeVaG0WhEcXExioqKoNfrEQqFEIlEAOwUgyUfJOHhysrKEAgEGKz6vPbSCypi8SRSr3g8zmh1uZNvv4kRF5e4AchRPDY2hsePH2N7extHjhxBd3c3FhYW8MUXX2BzcxPHjh3DmTNnEA6HcfPmTaysrMDlcuG1116DSqXC/fv38eTJE5SVleH8+fPQ6XS4f/8+R89aWlrQ3d2NeDzOvEy1tbXY3t7GwsICA1pra2tRX1+P7e1tLC0tQalUoqqqCplMhv0EpCWR43xxcRGbm5soLy9HU1PTnn6cTCaDR48eIR6P46233toVkCB/18DAAH79138dZrMZy8vLmJqaQktLC2+U48ePY2BgAN3d3fB4PLh69SoUCgU+//xzWCwWjI+P8+c+++wzpmQZHBxknvNoNAqPxwO73Y62tjYG8ooIeLHvosCl+ZRCJuhZpOkydA36LZdOI2rocr5NqdZFvjNRm3z48CEGBwexvb2NqqoqfO1rX2OWA3qmUCiEwcFBOJ1OuN1uPHr0CF1dXcyMOjMzgwcPHuBrX/saC0D6/vz8PI4cOYKzZ8+ioKAAgUBgV7+lmph0L0gFOlUNun37NpMQAju4xfb2digUCqyurmJubg6rq6soKChAa2srwuFwXnXr/dpLL6icTieqqqqYgC0UCqGhoWEXZ7ncKUJ/i02cJNEfQPzPra2tSCQSGBkZgdPpxMzMDMrLy9He3o7h4WHU1dVxpQ6i/Z2dnUVRURHm5ubQ2NiIpaUlDA0Nobq6GnNzc2hvb4fH48G9e/dQVVUFv9+Pmzdv4tSpU2hoaIDf78e1a9dYgxseHsb3v/99bG9v4xe/+AUqKirgdDqRSqXw5MkTeL1exONxeDweXL58mUvGJ5NJDA0NobKykvMgpYLZ7/djdHSUqYOlG1CtVqO5uRnz8/MMoaioqMDrr78OvV6PoaEhlJaWYnt7G3a7Ha+88grW1tbwN3/zNygqKmIclMfjwf/6X/8LwWAQRqMRr7zyCgvaZDLJY76+vs4EfqR9ZDKZXRS3Ut+LFL4g/Vtu4+4HBhZNWzkzUBxLEdUtRj2TySQjzS0WC7744gv4/X7OlaRrhcNhuN1u/KN/9I8wOTmJe/fucST76NGjsFgsGBwcRCKRwNjYGLs9jh49ikQiAZ/Ph8nJSbjd7jy8Fd1DLhoutweke4Uiy8RZRtQuVLzWbrczvi8SiaCwsJBpwp/XXnpBJWJ8KisrmWuJeLBFM0dckHJalXQh02u0gdPpNNrb25HJZLC4uIjZ2Vl4PB4cO3YM5eXlzPAYCARQVVWFEydOQKlUsnak0+lw+vRpjI6OYnp6GocOHcJ3vvMdFBUVwev14oMPPkA6nUZVVRVrUtlslvnc33jjDVgsFvz0pz9FNBqF0+mE0+nkSjE6nQ4nTpyATqfD6uoqrl27BqvViuHhYRw6dAgWiwW3b9/m5xKd0WQ6LCwsIJlMslNedMACOz6pmpqaPLJBp9MJo9GIn/zkJ/D5fPjGN74Bv9+PxcVFDA0NYXNzE8FgEDabDbW1tVAoFGwSGAwGeDwejI6OQqFQIBgM8vwsLCwgHA7DarXCZDIhmUxyPp04t1LhstcGlL4uZzJKNSUxq0HO1yldR3LaHvVVr9fj7bffZlDu3bt3mYecvkP+O3rm2tpa3L59G4lEAjU1NSgqKoLFYkFRURFSqRSnsBCBXzqdxtTUFIN+y8v/P+y9d5Bc2XUf/Oucc/fkHDARgxnkDCzSYrHgBpLaJbkULZlSSVZZtiSHKtn/yP6DLqnKtlyyS2VJtESRXIoiucsNwALYXcQFsMhpcs6x03TO/f0xPndvX7zXM6D11fcZ4qmamu5+791347nnnHvO75QXteFJaRaiGqrT6eByudDd3Q2Xy4VgMMhCosbGxjA7OwuDwYDS0lKUlJTAbrcjm82itrYWgUDgqfKl6LlnVKOjo1hZWWELyGKxFBh6RfGWFp8Y0CruIuKOk0qlYLFYYLVaEY/HYbFYkE6nodVq4Xa7YTAY4HK5WK48yqTs8XhYBmeXy8UymwwMDABY26Uo4DcajbJU7MQIFIq12EWNRoMrV66gvLwcKpUKbrebxdwNDQ2xBWy1WqFUKjE3N4fa2lo0NDTgs88+w6VLl+DxeFg+OmJAudwXmYuj0SiuX7+Ojo4OOByOAjwkIuo70ZiuVqvZQhkfH8fmzZsZYwwGgwgGg8z5cHx8HD/96U9RUlKCxsZGuN1uFki9uLgIlUqFTCaDpaUllradovF5xE6eREbFH4rIHX7QOIsbl5Rax7dZfCfdw5/E8QyeQlgAMHwoQhUlqRUAg7ihTDjkAc5DR1NWcEoMevz4cRaPmc1mYTAY8PLLL2PTpk24evXqU3ZanpFKSY9iu+l/MBjEyMgI5ufnmXRI2Yy0Wi28Xi+mp6cRDodRV1eHPXv2YGhoqAAYoBg994yqurqanS7MzMwgGAxiz549T0XQiyoB76UrReIOms/nWUxhOp1msBaxWIwNeiQSgV6vZ9cUCgVL4kDOjXyAL5X18OFDXL9+Hc3NzTCbzU/59mSzWSQSCfj9fszPz0Or1TKHTD6jDjltLi8vs/RUOp2ORbUvLy+zwFI+BpIWIhm/f/VXf5WdFgKFHtcUykMhNNSfZrMZ3/jGN2AwGHDnzh0cPnwY3/72t5FKpXDx4kU8ePAAADA7O4u3334bNpsNX/7yl1FSUoJf//VfRzKZxPXr1+H3+1m85sTEBPL5NRhm/pCB6ixKT6KLBDEsKalHStqSkpjEOSQlifPXSQom5086NCFmQQbvixcvYseOHXA4HGwsaAxzuRwWFxeZU6VGo4HJZMLQ0BALNq6trS1wqKW6EbyRwWBgJ4O8+4goIfJ9SSS1UcfjcZYqjE75SktLUV5ejtbWVszOzmJgYIDBdmu1WnaItBF67hmV2Wxmx+q8Hw75VxFtRGrir4lkNBrh8/kwOjqKcDiMaDQKj8eDBw8eYHJyEjU1NVheXsbWrVuxuLiI4eFhVFVVMWgMrVaLyclJJJNJTE1NMZG/t7cXV69eRVdXF3bv3s0YRCqVYk6riUQCOp0Ob775JpRKJX74wx+yDMv5fJ7ZbmiyU0qpsrIydiL6a7/2awgEArh+/XrBkThN4Egkgtu3b2PXrl3Mh0pk5vxuzDPG0dFRljWmoqICY2NjLK5vYmICvb292Lp1K4LBIL773e9Co9Hg1VdfZclJtVot5ubmMDw8jC1btsBisWBubg6xWAx2ux21tbWMGUuNFW9jEyUr0c5E9ZdiSPzvxWyXUvOKrwcxKz6chJhWf38/zpw5g7a2NpabkTYr8qeiEKFr165heXkZpaWlaGtrw+joKH7+858XqNAUbEzv37VrF/NzI7wqXgKV25zlDOs07k6nk+GHUbaZSCSC/v5+RKNRAGv+fm1tbQyyuaysDF6vV/J9Ij33jOrx48fwer3MqdButyMSiRT4BQHS9gp+txGv0X8S2ysrK1FdXY13330Xer0emzdvRl1dHerq6vDjH/+Y6efd3d3I5XL48MMPmR5/6tQpqFQq3Lx5E2fOnMHU1BS6urowOjqKn/zkJ2hpaUFjYyNTL1QqFRKJRMHionx6ZKykemezWWZopROgaDQKp9MJlUqFWCyGRCKB+fl5LC8vw2QyFXhyEw0ODiKZTGLHjh2sv3jJi3eXyOVyDMyfYGTee+89PH78GLOzs2hubkY6ncaVK1fQ29uLzZs34+TJk1heXmZqy7vvvovq6mocPnwYDx8+xN27d1FRUYETJ05ApVJhZGQEwWAQzc3NKCkpkQyqlVK9+GtyNimRIfGMSY5ZFVORRLWRXCtyuRzDpler1fD7/Th79iwWFhZQWVmJO3fuYOfOndDr9ejv72dJWY1GI44fP46rV6/CbDZj586dsNlsOHbsGDOQ85sJtVWlUjGcMYVCwZKi8mr6RohfM9QGrVYLm80Gi8UCs9mMWCzG1hkxLXJgTafTzKC+0eQOzz2jstlszC1hfn6epSgnewh/cifupPx/UaznJzWF5hw9epQBtjU1NUGpVOLAgQPsyLazs5PFW5FD3Pbt25m96tChQxgZGUF9fT22bNnCkgTMzc3h7NmzaG1txcGDBwGgQNWhdE1vv/02s3UQkgHVl0c6UKlUsFqtzCjrdrtx4cIFuN1uHDx4sED8B9Ymu8PhwKuvvsrwwan9cr5ou3btYlC6jY2N+PrXv45EIoGenh5UV1fDZDKhtbWVwctYrVaYTCb8y3/5L5nqReoBMaOamho4HA6Ew2FMTU0xgyyFExHJbT5SxnCp+/i2Sz0vMkCRSUkZ06nf6TrNG1L7aRPZunUrOjo6YLfbYbPZWLDvsWPHmLc6j8NFDCefz7PNkJ/LUuE0Uu2Qaq94TeqQgerv9/tx584dJvGTE2hNTQ0aGxuxtLSEgYEBzM/PswD6WCy2YWP6c5+F5s0332SLfWFhAXq9HidPnkRXVxdaW1sBfGHnkdPDRdsGb9Oie+lZmoAkbfCJDMRdmOwUJL2Qwycd5xJOE92nUKzF22k0Gob/TjAZhA5Bqanq6uqgUCgwNDSElZUVdHZ2wmg0MmNrLpdDWVkZtFotQytQKpUwmUySEoBUW6UmMIACnG8pXyHeQ52XWOke/pifN3gTzc3N4e2338bS0hK+9rWvYefOnRsKgeLrKP4mqv7iIhZVOnGO8M9I2anE58QQFx4ymYe64d9Dz/HSPq/Skxonmiz4uvPMS4RGFtXhYn2Zy+WYNJVOp/HTn/4UZ8+eZep6NBqFWq1GTU0Ni/+LRCKIxWIs7yHFNd66deuXWWiy2SyCwSBUKhWqq6uZ12wxbCCpAePvE1UEfmLyELBkGBfv4yUQnvnxSQDIIEl+LryRn8JjiBnSKR8F8JInOwDmLcwnHyUbBQ+aJmZB5usnuiDwn3kXBt4/iGfcfP35ic8/K8XA6FRRZHakMrvdbgbVW4xECUJK4uGZgihRFlu860kictIab68SPdrJdiUyEP59/CEA9TdJNwCYkV5sTz6/dmgyPDyM+vp6VFZWPpWBSaqdYpuI+dF7Kisr0dzczJBVyRk3m81ifn4ei4uLcLvdBQl/7Xb7L5M7EM3OzrI8Y7W1tUxnTiQSBYMoJfEQydkipCQsqaNufiHz94rPSxFfJ/F5+o0P6SC/FvrudDoLJAJxwfLMiH8nHxIiJXGI9eKlDdGoLSV5FFOx+RMoHnGC6ri4uIhEIoH29vaCFF98X/N9L1d/cfFL1Z8fK3E8+bKkfpdzV6B5QpsRLyXx/SPOD4Xii8DjQCDAUFE9Hg9UKhXu37+PlZUVKJVKlnyVyqQ+XV1dxccff4yBgQGUlZWxbDViG8SNSaqtfHvJyZmyQBPMEKV21+v1WFhYwNjYGGw2GzuJHxwcxEbouWdUNTU1qKurw+LiIlZWVhAOh7F37152fC9OCp7EHYkncRHS/fx/cVDFCSnFoETxXnwH/5kPj+ATnvK+TDyTkrLB8Yw1lUoVpM7ig40JfYJ8ciwWCzMKU4JXCopeXV3F0tISDAYDS2+fSCRgs9mQzWaxsrICj8fD7Bl8PwSDQczOziKfz7P4vVQqxVJ/l5WVYWpqisWSzczMoLS0FFartcCtgCSMhYUFBAIBGAwGZo9TKBTwer0M6zsWi7FTWvJ4pww2IjMVx3m9TUZqPvDjl0gkEIvFGDQ2ZRjiw5tEmpiYwM9//nM4HA5EIhFm73v48CF6enqwsrKChw8fsuS69D46PQwGg/jWt76FJ0+e4O7du8wEwrdPqs5ya4TuJVx0cnehwxSz2YyOjg4GyEgHWWazmaE3rEfPPaNyOp3I57/IL0bHtSQi8/r7eoOz3oSke+R2HVGs5t/HT16e0aTTaSwuLsLr9aKsrAwejweBQAALCwtwuVxoaGhAPB7HxMQEwuEwbDYbOwVbWlpiTpCUECKZTDIxnKQRYE1K6e/vR1tbGwtx4W0YQ0ND+OCDD6BQrPniHD16FJs3b8bIyAg+/fRTmM1mnDx5EkajEefOncP09DQymQx2794Nl8uFxcVFHDlyBNFoFLdu3WIgcHxfrKys4P3338fMzAzy+Txqamrw+uuvY2xsDOfPn0cul8P27dsxOzvL7HmffvopSkpKcPr0aSadUF8HAgF89NFH0Gq1zOb32muvIRAI4O///u8BAF/72tcAAH19fTh+/DjL6LN//354PB5Z6bjYGIpSiZREks/n2SlfIBCA0+nEa6+9hkQigXfffRdtbW0oKyuTTLG1uroKl8uFr33ta5ifn2cnyOXl5Th48CD6+/tx69atAlMDSVTJZBJNTU1obGxEJBJBb2/vU/OZv78Y8e212Wzo7OyE2WxmyVDD4TCSySQeP34Mv98Pj8fDAs3z+TysViva2tqYD10xeu4Z1aNHj+D1eqFUKllev2g0itXVVcakaDBpskkxJnGXEdVE/nheavISieK9WD7PpDKZDK5du4YHDx6gtLSUeaDfunULMzMzUKvVOH36NKLRKK5evYqqqiqMjIzAZDIx94Z0Os3iDU+fPo2+vj5cu3YNr776Kux2OxSKtVAUYhD8yRFJalqtlh07v/jii5iZmcHNmzeh0+lw7tw5GAwGBINBnDlzBt3d3VhdXcXXv/51LC8v4+bNm+jq6kIkEmHtDIVCTJojqQ1YW4DBYBC/8Ru/AaVSiZs3b2JmZgbnz59HTU0N8vm1nHbhcBgmkwkvvvgiUqkUrl27xrDa+X6PRqPIZDJ4+eWXYTAY0N/fj4WFBXzwwQdoaGhAMpnEz3/+c+zbt4/5kwHYcGYUKQYkfpb6TnNlaWkJRqMRx44dw5UrVzA8PIyOjg6Ul5ezww26n5d8lUolvF4vFhcXMTExgWQyCbPZjCdPnuDs2bMYGRlhPmz8XKNN+v79+0gmkwxOWkpdFuvNS49SzDeRSGB1dRXxeJxlCyJhwGg0Mh/BXC4HnU6Hbdu2IZlMsgiM9ei5Z1R6vZ5lxZicnITNZkN3dzeTqkjVIeYgJWpvlDZqixFJ6r5sNovHjx9jdHQU+/fvR3t7O4xGI548ecLy5t27dw+3bt1CZWUlWltbceTIEUxMTLDf6uvrsbS0BL/fj6amJhgMBlRXV8NutzPj+dLSEj744AMkk0mUlZWxd4txfgRHU1ZWhtLSUkxNTTEY2TfeeAN+vx8ffvghIpEIHA4HampqYLFYcP/+fRaPqFAoGJSJlH0vn19zTnU6ndDpdDh+/DgWFxehVCpx9OhR5HI59Pb2wuv1slg4sTx+ESmVa8iTfX192Lt3Lw4cOIDh4WGo1Wq89NJLCAaD+OEPf4hwOFzADKSyH8tJF7wEJ46pqL6L1NjYiNraWtjtdjgcDnby1dnZicHBwYLMzny5lZWVyOVyOH/+PKanp6HT6dDV1YVYLMZSU1HEA78Z03+LxYKGhgZotVqMjIwUnNLK2d+k5iyp18Ca2WBwcJCtp0wmA4PBAKPRiOrqamg0GszPz2N+fp75TvHhbOvRc8+otmzZAq1Wi6GhIRaHZDQa2ekEv2vxgwoUPwHhF5eUyM/vPuIz/D3ic7wReWhoCEtLSyzspaKiAuFwGGVlZdi0aRNSqRQ+//xzWK1WjIyMwOFwYHBwEIFAgEHUDgwMwGKxYPPmzdBqtXA4HDCbzQw6ZHh4GLOzs9ixYwdGR0cxMTHBfMD4+vMxZ7QYKERodnaWRcxTX+bzeRaTB6DgJIsSNogLg/fBUSgUrJ6EHJHL5Vj2ILKPBQIBFhBOhlzq07KyMqYK+Xw+dHR0QKVSwev14urVqywtPDHmVCqFVCrFPKmlTjvF7yLDJRLDnETpW6VSsQzW/f39uH37NoMSpsB58USQ3lVWVoZ/82/+DbLZLH7605/C5/PBbrfjpZdewsrKCnp7e1FTU1Ngl6RnKQtNZ2cn7HZ7QRYaUWISma3UXKa6kUsMMXwC9dNoNKw/nU5nQVsSiQRT/9ej555RDQwMMBWgpKQEJpMJoVAI8Xi8IGsGzySKndZITVxxQkoNcLGdVU7EJpiMGzduIB6P4/Dhw8zrmwzalNp7ZWUFT548waNHjxiMTSQSwdLSEnbs2MGMqiT+8/GFZrMZQ0NDmJiYgNPpZDss3w6e6VAQrFqtxsrKCm7cuIF8Ps/CIQjviqSdXC7HPOnVajULn+H7h1d56b/P52MqBDntRiIRtsgJx+t//s//iUgkUmCYpTr39PSgs7MTQ0ND+PTTT7Fjxw5ks1mEQiEkk0nEYjE23uSmwbtXUFmihFlMUpaTQvgxJqNyX18f3nvvPfT09KCnpwf5/Bo0M8VvEmQ2wUxXVVWxuXH//n2Mj4/j2LFjyOfzGBgYwN27d2E2m7Fv374Ch2b6s9vtBXDAzc3NTzEiOVWQbx//jEqlYqd7ZFMLBoNMxV9YWMDU1BRcLhccDgfbJI1GI4O3Xo+ee0YVj8eZUZlUED6LLvC0dCTFWKSYkRStN8hyZfMnJ/zE+sY3voGOjg5cuXIFi4uL0Ov1LBPt4OAgTCYTamtr8dZbb7Gkj4QuSpKZ2+1mjIFOmuidhDOey+XwV3/1V2htbS0wStN95NaxurrK4JzT6TTq6urw9a9/HbFYDD/84Q+Ry62B8C0uLmJ5eZmhPIbDYYRCIayurrJUWFL9OTc3x9SRixcvoqurC5WVlTh9+jTm5+dx9+5dJt35/X7mx0MSG6+Kzc3N4caNG9i7dy870QuHw2htbcWv/MqvIJ1O43/8j//BjvtnZ2cRiUQKgql5Ek9jicS2yBmixQU+PDyMn/3sZ6iqqsLBgwcLIGqANYav0+mQz68B6s3Pz7OA8AsXLqCvrw8HDx7E9u3bkcutBSqXlpZi+/btjAHwKmwut5YTkOrocrmwZ8+eAmlZVKGlNAOpeZvP5zExMYFQKASTyYRkMol0Og2Hw4HKykq2kS0uLiKdTqO5uRkVFRV49OjRU/0kRc89o/J4PHA6nZidnYXf70c0GsWWLVuYfxFP4oQTRfZiqiDvwiDF8KSkMLF8fqKn02msrq5ibm4OLpeLedp7PB588MEH+PDDDzE5OYmXXnqJnd7cvn0budxa9hZSPch+Q7YEWmy8FEmqiNlsZplb+N1VoVg7QZuensZPf/pT5PN5FidG4Ts6nY4dNyuVSvzVX/0VotEo2tvb4Xa74fP58IMf/AAKhYLFAdI7qK4ulws1NTX4m7/5G+Rya5ltSktLUVFRAaVSiUgkglwuB7fbjWQyiffffx8qlQoNDQ0sUQRfZ71ez0D5CA/JZrMxrCuFQsFw5SmNWCqVgs1mYzY8qbkh9bvUBiQ1X3hGsLCwgKWlJaTTafyv//W/sGXLFhw4cIBB/fDlNTQ0MH8pjUaDvXv3Yu/evXC5XEwCPXToEHPCFOcUkdguKRcRfv5KBWjLqe2JRAKhUAiRSASpVApWqxVGoxEOhwMOhwNzc3OYmppi0MRmsxlOpxMboeeeUbndbmaHIBd9UkOAp8MTxN/Eyc+TuNuIgydOavGdItHEUCqVsNls2LVrFx4+fIjZ2VmYTCaWPmpmZgZzc3Po7u5GfX09Q2ysrq7GgQMH2CQnDC7Rv6ihoaEglRQxq9bWVoY7TkQHDAaDAUeOHGFMra2tjWFskXfxzp07UVJSgpMnT2JxcRFGoxFbt26F2WzGr//6rzMAQzrBJBWTTv8MBgP+yT/5J1hdXWWSYD6fZ/ntCARux44d2LRpE0sb73a7mTTCj4fH48Ebb7yBaDTKjPSkepI/2MmTJ+FyuVBdXc0kTVpgUmNXbFz58eWv8XOJt9F0dHTgn/2zf8ZUTmKQxIhImlIoFGhvby+Yby6Xi0leZC8ku6TIFImR0WcpEwXfb/Qb70TMt0tKSzAYDGhqakJZWRk0Gg1CoRASiQTC4TAGBgawvLzM0mdRzCawhr+1EXruY/2OHDmC6elpqNVqNDc3w2g0wmaz4YUXXsCWLVsAfLEY6U+OkUh5nUuR1EBKGVqlPJJpR6TJlUwm2XXKTpJIJFhqeooljMfjMBgMBZJKPr+GgSVCoCSTSajV6qcy9tJpF+/oSIyE91Sncmih8Cem2WwWgUAA8XicGe7JS5k/fRJPWEWGL/ZTLpfDD3/4Qzx69Ai/+Zu/iebmZvZucZHRf14ikUtoIW5G/PvlxrbYPBDLonfwsXu8asj3CR/rKDIHKW95Gh+eEfJ+V3w/8mEyosTEl8v3JZ8hSEol5Glubg7f/e534fP52GFAKBRiAsLY2Biza+ZyOZSWlqK+vh69vb347LPPfhnrp1AoWCaUwcFB2Gw2HDp0iGE1AV/Ez4nPFZuUUsfSokTF/y6qlfyz/C7L25IUCsVTabFyuRzbdYlIBRMnEgVF8zskGXH5yUiTWErd4UNYxJMhqnM+ny/A/CK8JGonH+IjSqvUTqqbXJ9T7JjNZmMTWk4lEd9TbOMQ1c+N2B7FsZeSqMR6SamGPHgj9YFYB97PT6ocMoxrtVqsrq7C7/cjm83CYrGwLMiiqiY1Z/l5IyV1SY0d1SObzSIWi7FTY8LuNxqNDP6ovr4eCwsLGB4exsLCAoMjkor6kKLnnlF1dHRArVZjenoa09PTMBgMMJlMTKwGvmBU/ORSKpUIBAKIRCLQ6XQFdhi6LrcQgKc91IuROJFEFwm6xksg/Pv5UyqeIfEJDnhmyJdJ5fB+NPw9ZM/J5/NsR+R3WKlcfxQ6Qe8Xsa1IchN3b54Rklc+jU8oFEIoFILdbmdjQOXy6BSUXUipVD6lDkqp71KSnNzmIyXxUd/yz/Bjz5fBSy/83KH+48eRwOdsNlvBxqJQKBCLxXD58mUEAgFoNBrmR3f9+nUEg0Ho9XrEYjGcOHGCqVY0xnJ+S2KdScLjGbmUHZbaYLFYWDiSyWRiSRtIwiam6nK5YLVa4fF4WEqwjdBzz6gWFhbg9XqRSCRYJ0Wj0QLjMv/HL5zHjx9jYGCAwcHSKQnhSxVjQHLqI5FU2M7q6io0Gg1sNhuAtQVNR/ROpxMGgwHJZBLBYJDFUFF8HYUrEFoopUGPxWIMfJ9gh30+HxwOB8OLIlhbpXINQ6i0tJTVjxZ7IBBALBZDZWUlIpEIFhYWUFJSgqWlJRYI63K50NrayqQ4Wpxerxc+n48B5g0PD7O4r02bNiGZTOLRo0ewWq1YWlrCzp07mWe60+nE4uIiDAYDYrEYstksxsfHodFo0NrailwuhwcPHqCkpAQzMzMsr6LL5cKuXbug0+meYlJS0o3IaKQ+8/fzzJm/j9RjKamQ3iunbtH3+fl5XLp0CQ6HA7t372YSKj2TzWbh8/nQ2dmJmpoadmq3srKC/fv3o7y8HOfPn0cwGERNTU2BiUHcFPl20Xjx/0XpT+wDKsdisaCurg4ajYYl2ohGo2zejIyMIJdbgxYi+59Wq/2lMZ2I4uII6ZLsOLxILSXKZzIZpFIpbNq0CV1dXWxwTCbTU5OciGc6fFlyOzJ9VirX4HqvXr2KtrY27N+/n4XFPHz4ELlcDhUVFThy5AgmJycxMDAAk8mEbDaLgwcPwmq14vz58xgbG0NNTQ1efPFF+Hw+XLx4EcAa+mdXVxd27dqF3t5eXL9+HSdPnkR7ezumpqbw0UcfMUA6rVaLr371q+wUjfopFouht7cXDocDDx48wPT0NLq7u/H555+z2MKhoSE4HA5mzCcJLBAIYHBwEHV1dUgkEujv72cBtc3NzchkMhgfH4fH48Fnn30GhWLN2fPChQs4cOAALl26BJPJhGg0ing8juXlZeRyObS0tCCTyWBsbAxerxcDAwPYvXs3tFotRkdHsbq6itLSUkmpSU5lXI/4cnj7mFie3DvEa3zgt1KpRDAYxLlz52A2m1lmIHqWJCJyHwmHwwgEAlCr1XC5XAUqYiaTKQhbkqqP+FlkmsWIv05hMeFwGPfv32drhMqqrKxES0sLJicnGWaa1WpFZWUlpqamNtTvzz2jqqysRHl5OWZnZ7G0tIRIJIJt27Yx2w8v+Uh551LGFz4ujd+ZilExdYOXyPL5PPM9CQQCDL5XqVTilVdegdVqxZkzZxh4v9PpxI4dO/D+++/j8ePHsNvtWF1dxbFjx3Dnzh08fvyYnbp89atfxY0bN9Db24uenh44HA5oNBoW0hKPx1FaWorXXnsNPp8Pn3zyCfPl4qWNXC6HSCSCkZER3LlzBydOnGCexsePH4fFYsHExASzlcXjcSQSCWb8pyPrVCrF3k1t5BdxMBjE+fPnYTabGXxtKpViiAoE7MeHzfD1bWhoYDYRCn7lxwwohOeVomK2Kn4Mac7QdykbjpRaKTVvaMOcmprC9PQ0fud3fgcOh4OptOJzmUwGP/3pT1FaWsriGc1mMz7++GOWI7K6upq9k9Rtvo18OzbSD1LfqRydTgeTycQcqenAxul0Qq/Xs5O+iYkJTE1NsTllMBiK9jPRc8+ojEYjU6lKSkoYbKvoHyJOOACIRqN4/PgxfD4fSkpK0NLSArvdXnAKJqXiiYtgI7u12+1GQ0MDO6EzmUw4cOAAdDodCzUgD2By7Mzn87DZbFhZWUFjYyN6enoQCoWwsrKC2tpa9Pb2YmxsDIlEgmFtU9Axv7BCoRB8Ph+TWKgN/H+tVovp6WmMj49j69at6O7uxtLSErxeLy5duoT9+/ejvr6eeb5T8gyKOZuYmMDAwACy2SxWV1dRVVXFmA0B+NEROyXHIPuFTqdjgIe8HxjPqCit2N///d/jxRdfZGqIlDRFn6XsSHILdz3Gxd8nNd5Sm5UolajVaiSTSXi9Xnz88cdQKNbcErq7u1kfAV/kTqyvr8e2bdtw/fp1zM3NsRPuXC6H2dlZFsMo5gWUU22l7HFiXeWkRKVSifr6enR2dsLpdCIUCiEWi7FEt/39/UilUrDb7ejo6GCCAmG7r0fPPaMaHh7G5OQklEolGhoaYLVanzqWBwp3GJKeSF3MZrPMY5kmuBRjo+88SV0XpTZieuRPQ9fp9OThw4cYHR3F0aNHkUqlGCJEIBDA8ePH4fV6GXqi0+lk2YVXV1fx+eefIxwO49ChQ9Dr9QDAXBAUijV/nJmZGfzgBz9ALBZjUo5oWFUqlZifn4dCoUBjYyPUajVKSkqwa9cuPHjwALOzs9i+fTt2797NmI/RaGS56ILBIO7evYtUKoXl5WW0t7cX9A0lOSgtLUV7ezuSySSzfWk0GoY3ZTAYGHwy9Vkmk0FZWRneeustXLp0CT/+8Y+xZcsWvPLKK5LMh1f7pUiUJsX5wTM5cTzFcqSeEUl83mw2o6ysjKFPkM8aMRqdTod9+/axnH5NTU148uQJS081MjKCZDLJ1EHRBiYyIbn6ybVHat0AYIidoVCowNal1WphtVoZ9A/l2dy6dStTT9ej555RkSF5ZWUFY2NjcLvd2LlzJ9P3pSYPTeJ8Po+9e/di27ZtBfC8fFQ6T+JuJLU7ie/hr1NiSfotlUrh4cOHuHLlCkuKcPPmTWzbtg2tra04d+4cZmZmEIlE2K5JPlajo6NobGzEV77yFdy5c4elWOfj9PL5tYQAv/mbv4lwOIwHDx7g0aNHBSownYbm83kmtdy6dQubNm2CUqnEkSNHsG3bNty8eRMffPABOjs7C0DsdDodS831yiuvAADefvttph7SpkGwJiqVCocOHYJarcZ3v/vdgjbV1tYypk6qDHlE6/V6uFwu/Oqv/ioePnyI8+fP49SpUwWqk9y4SDEeqd/lxq2YFMYbwcWxl5PwmpubcejQIaysrOBnP/sZ4vE41Go1pqamYLVa4XK58OTJE0SjUWzdupV5t4fDYYyNjeHKlSvMLkRlS81V3qbF10Gqf+i/lASWz+dZgpPFxUVks1m28TidTpYIt7q6GlNTUxgfH0cymYRGo3nKsVaOnntG1dnZCQAF/hvUOTxGt0iUksrv9yMQCEChULDdXO7UppiUJhJ/jWdU9O5YLIYbN27g+vXr2LNnD/bu3QuVSoVwOIydO3eivb0d/f39Bfnxuru7MTExwexdVVVVKC8vR0VFBQOj02q1LJqd3l9VVYVwOIyLFy/C4/EUHBgAYIyhqqoK27dvx7vvvovHjx+jrq4OMzMz6OzsxM6dO/HgwYMCiZNfBAaDAW63m0lYSqWSxQ2Gw2EWE0jvJUfWfD7PGFVpaSnC4TBLerGyssJU19nZWXz++ec4cOAArFYri9rn3VDE/7zNig+Gpmty48cvZClpRFzsYmSAHOXza6iYPp8Pd+/eZcf6+fzaqe758+fR1NSEY8eOscOGoaEhJBIJdHR0IJ1OY2pqCtXV1di+fTtsNltR21gxkwXfJvGzHFHqeEKEjcfjyGQy8Hq98Pv9LH1WTU0NC0z+pR/V/6be3l4sLS0xb1ibzYZYLMYSW8qJ7RSL9OjRI8zMzECpVLKkkLyNCvhCXSSS2qHFyctPYP79BKESDofx6aefMsnv/v372LRpEzOYTk9Po7+/H6dOnUJ9fT1+/OMfs1Og119/HaOjo7h8+TJyuRzGx8cZogK9h2we2WwWd+7cwcOHD7G6uopXX321IMEE72dlMpnQ2dmJQCCATz/9FF/+8pdx5swZPH78mO2oUoudnP9IYrLb7Qxi+Hvf+x7bMHh3CwAspZler0c0GkVlZSV8Ph/zLfrZz37GTrwcDgeuXLmCkZERaDQauFyup/DI5eyGPMPixweQT8jJkxTzEcvgHYqlmAf1N+GIDQwMQK1WY8eOHWxj3bdvHzvAaG1txW//9m8XjI1Go8GJEydYkhB+0+DnoJSkKMWI+I1GSu2j72QH0+v1qKioYE7JsVgMwWCQfZ6YmIDdbmd1VSgUv5SoiNRqNUKhEHK5tfx3PFa6VAgL/9wLL7yA7du3I59fcyQ0mUwFujf/jJwKKd4jvo+fIPX19XA6nWyg9+/fz/yjqL4nT57ErVu3EI/HsWvXLrS1tcFoNOLo0aNYWFjACy+8gIqKCjidTnaKWFNTg927dzMHyZ6eHnYokMlkEIvFUFpaipMnT6K+vh5Aocc6sJYfcfPmzVCr1Thw4ADsdjucTieOHj2KpaUlAMDWrVufwqLP59fwk1544QUWX7dv3z6UlJTgK1/5ClZXV6FSqZhbg91uZ+89duwYDAYD6urqWGZdyrRbW1vLJEOLxQKXywW73c4kM5fLxRYBLSYpcDhixnIbCj+Wop1HTh0UGReveokMQ7zX7Xbj5ZdfZuYFgp0BvtAOaINxOBxP1YF82HgpTooJ8e8u9rscQ6PPfHB7Pp/H7OwsvF4vMzGQjYqw871eL/OpIsiXjdBzz6isViu2bduGiYkJLC0tIZlMsiNukVHwg06BwVartSDMQySR+cjRRuwYZPdRKNb8iI4dO8YmOKknLpcLVVVVTzG7/fv3s5MjMkC/+OKLBQuL3tPZ2cl2WY1Gw9Azxfgyfkcl8D0yYO/YsQNqtZohNZDBnVeh6D+hKtDu39jYCABoaWl5ijkQemUikWCfKSLAZrOhuroa+XweBoOBqXjUltLSUuasKheyIyXJihsWjX+xcZVS8eXGfCPSDH+aScHWdI3cL8Q4SwK84yU3UU2jMqVME2LdebvVRkjsA71eX2Bj1ev17MTW7XZDp9MxdFmySfKhYMXouWdULpcL8Xgcbrebhc9IhajwJCVl8ZObF6lFZkdUbHfm7+XLo5g4usZPPH5Xph1WatcktEr6ja8ff0xNxAfA8unZ+cBkIt4wzbdRZHDiYpRiDMX6hHbiVCrFoENMJlOBzw3fNt5VgS+fZ7hS7ih89miqo9xcKBaHKNV2kSmJTFIkKpskWXEMxfApXkIkqYb8l+iEmpBs+XES1TlRsiu24UqpifwY6vV6NDU1we12Q6vVIplMIhqNMj+4wcFBWCwWlJeXw2KxwO12s1Cb9ei5Z1T9/f0YHx9nfh68gXG93VK00/ALXEzaKMWkNkLixOHVE35xi+WTvYcmKX3nd0TeHiWGe/CLj37jd2dx8fOLjI/Q55knzyR5SZBXh/j6AoX5FKlspVKJeDwOpVLJ0nQZDAa2W1P5ZIsBUJBVSLSR8cZyUW2TC4ORkoDFoGG+HCkGJWWYl2KEfL2VyjUYX6/Xi3x+DaOLpFFeSqU8euFwmPXpli1bMDIygrm5OeZwefLkSZbElh9Tqgtff56R8e1fz7zBb7SJRAIrKyswGo0Ih8OIx+PM3SKTyWBhYQFzc3NQKpVoaWnZUAJZ4B8Bo6Jja5/Ph4mJCcTjcUnRGyjETY9EIhgdHWUY3blcDg0NDaipqWH3yh35Sk1yqd9pcpB4Pz8/z45z8/m1066FhQWo1WpUVFQwZ8jFxUXk83nmwErxVPl8ngGVRaNRRCIRph5QFplAIMCOjh0OB5RKJXsWWAsR4sV3ahNBApOjXjweh06nQzQaRTQaRTqdhtVqfSrIVKFY836fn59nRler1cr8amhBVVVVQa/XY2pqCsFgkPlM0elrSUkJ9Ho98vm1cJ6ZmRmmEuVyOTQ3N2N5eRnLy8tIp9Msldjw8DAWFxdht9tRUVGBiooKjI2NsQOS6upqbNq06SlJTJQKeabHM29xQReTtsR7pKTqaDSKa9euMd8/h8OBU6dOsZNY+vP5fHj06BHa29sxPT2NoaEh2Gw2TExMYOfOndDr9bh06RL8fj/LZSjnoAwUStmiFiBXf5EUirUMQ5RAI5vNMlil0tJS7N+/H5OTkwwJlMZpI/TcM6rNmzejubkZo6OjWF5eZgZ1cdcURfdYLIbHjx/D4XAw6GIyYtKuz5M4gGLZUgNMdchkMnj06BGuXbuGEydOoKurC8lkErdv38bFixehUChw4sQJ9PT04MaNG5iammIpznfu3ImHDx8y9chms6GrqwsTExOYmJhAPp/H4uIiWltbUVFRgXv37kGtViMcDqOpqQkulwuXLl2CzWaDxWJBV1cXuru7C07MFAoFZmZmMDo6ikOHDmFychJPnjzB1q1b8fnnnyMWizHY2ddff51lF6H2TU9P40c/+hE8Hg+sVitaW1uhUChw4cIFlnSTMNCnpqYwMTGB8fFxJBIJ7Nu3D/F4HC6XixmKvV4vbt68iYaGBma8n52dxUcffcQ8+B8/fox4PI5r166hrq4OKpUKH3/8Mcsj19bWhmQyiUuXLsHpdLIFI9qNxN/4sZbbkOTmgFgGP99ImlxaWsKtW7fw8ssvAwDOnDmD/fv3FxwMKBQKlJSUsGQQt2/fZgigDx48YLY7AAXhRXx2HX7+iQy3WIhRMSalUqng8XhQVVXFEpES1r7f72eOntXV1SzQfnFxUbI8kZ57RvXkyRPMzc0hm82ivLy8wFtXnGz8TkJZX7dt28aMuqI9RspeITeppSY27XJarZYtRLIjkQR44sQJ5HI59PX1oby8nIXW6PV6fPLJJ8yRc9euXSx7jEajgd1uR3d3N3w+Hz744AOYTCZ4vV64XC7s378f09PTePLkCZRKJaqqqnDs2DGWoUdqdyWP8rm5OVy8eBHt7e3I5dawxr/0pS8hk8lgaGioQAWjNqvVatTU1OD06dMwGAzQ6XQsF92uXbtgMBjw4YcfIh6P4+DBg9iyZQveeecd5PNrqZ2y2exTUfZGoxEHDx5kKu/09DRMJhNeeukl6PV6TE5OMszxw4cPQ6PRoKKiArFYDAqFgiU/mJiYYG0WmYccSW1C/JivZ1KQuodsTVarleUgVCrXcMZ4jH96TqvVory8HBcuXMD4+DiDfFapVDh37hzUajXGxsawZ88e9g7xpHq9OoruGuI8Ftug0+lQUlLCEBIoIQdJzaOjowDWMtaQK8tGjekb87Z6Rpqbm8M3v/lNdkTc3d2Ne/fusev5fB5/9Ed/hIqKChgMBhw+fBh9fX0FZSSTSfzu7/4u3G43TCYTXnnlFczOzj5zXUhkDgaDWFpaYsfXcp3N/x4KhfDkyRM8efIECwsLT0ldogFWbheSKp9/t0KxFmFeUVHBJBmfz4dsNov29nZ0dnYy/6q9e/eira0Ner0eCoWCOT9+9NFHePvtt3Hp0iX4fD6YzWaYTCYG39vR0YF8Ps9UNmIW6XQaMzMzePLkCfr7++H3+1mdeGQJrVaLubk5fPrpp7BYLNixYwcUCgVL2lBXV4fjx48zCBxxUY6MjODMmTM4e/Ysbt26xdRAg8HAsgORZLW6uorZ2Vn09PQgkUiwGEferhQMBjE+Po7FxUWW7YSM4xSRT1AyADA/Pw+lUgmn04loNIp33nkHc3NzqK+vZ/hWvHQh2uzWG1856UNUI4sRbX6UgYbS1lNMJFDIbLRaLXp6erBnzx5cuXIFqVQKr7/+Og4ePIjm5ma2CdJY8uptsTpKtVOUBKXqrlAosLy8jMHBQfT392NwcBCTk5MIBAJMzYtGo+jt7cXNmzcxPDzMILHXo39wRhUIBLBv3z5oNBp89NFH6O/vx3/+z/+5wHbxJ3/yJ/gv/+W/4L//9/+OO3fuoKysDMePH2dMBAB+7/d+D++++y7+7u/+Dp999hkikQhOnz79FBLneqTRaNDW1oaKigrE43EGzSu1e4q/xeNxDA8P49GjRyx3HYACBiUyLyJ+sEXmxNs4aOLwTIHuI+mDUpKTGL+ysoKLFy9iZWUFlZWVsFqtqKmpQXNzM4aGhnD//n0oFApEIhEMDg6iqakJJSUlcDqdGBkZwQ9/+EO8//77WF1dhVqtht/vx+DgIAuDoRRXvAE9m81idHQU9+/fR1dXF8xmM0pLS1FVVYWPP/4Y7733HsbGxp7qh3w+z/LXkVH34sWLDE2B+oH3FXv48CHKyspQVlbGVAMKJgfWDPfLy8u4cuUKbt++zbJGk0/YnTt38POf/xxLS0sMB314eBjnzp2D3W7Hr/7qr0Kv1+PHP/4xfvrTnyIcDj+lEvFqET+mUp/FsS32m5RUzX8m9IyvfOUr+NrXvsY2TOCLUCKFYg09Ym5uDhUVFXjxxRdhNBoRiUTgdrthNBoxPj6OmpoaBlBHc4zXAqTmrtzGXYz4fiK3CcpGzkuJPT092L59O0NSoIOQjdA/uOr3x3/8x6iursZf//Vfs9/q6urY53w+jz/90z/Fv//3/x5f/vKXAQDf+973UFpairfffhu/9Vu/hdXVVXz3u9/F97//fRw7dgwA8IMf/ADV1dX45JNPmG6+ETKZTPD7/TAajTCZTMyADHxxRM2Ls/yu7XA4cOLECaYuEkAZLwaLtqpiOrzcdaoDJUmgBUtG81QqBb/fD7VajaWlJZw9exaBQAAvvvgiNm3ahJqaGpjNZuj1enYkTHa2eDyOtrY2KJVKbNmyBXa7HfF4HFeuXEE6nUZPTw+6urpQXV2NyclJvPPOOwVpmngi94mRkRFs3rwZNpsNb775Jubn53H9+nW88847qK+vZ/YUYnaVlZX4rd/6LXg8HoRCIUxNTbFsvuT3FYvFoFQqWX7C1157DQ6Hg8GG8MkggDXHyG984xvMj4oOCRwOB770pS/hu9/9LmP8NpsNe/fuxfDwMFKpFMxmM958801MTU3hL//yL7Fv374CiW09tU/OYC4nLctJI6KURGXE43H09/dDpVIxiYjSh2WzWZw8eRKRSATf//73mQoOrKleAwMDuHr1KpRKJV566SVYLJaCekh5m/PtFuu7UUmQ1kJ5eTkaGxths9lYuFM2m0U0GsXc3BxDaS0vL4fNZtuwe8I/uET1/vvvY/v27fiVX/kVlJSUoKenB3/5l3/Jrk9MTGBxcREnTpxgv+l0Ohw6dAg3btwAANy7dw/pdLrgnoqKCnR2drJ7RKKobf4PWINq6e/vx+zsLLRaLfOj4geMiJeS6AQjEAggGAwyVFDxHnquGIn6vSi50bExD6nr8XiQSqXQ29uLgYEBKBQKZsuZnp7GCy+8gMbGRmQyGdy9excrKytMoiCi42KSNjQaDaqrq5HJZBAMBtHS0sJissgbnoyiQOEOrFAoUF9fj6997Wu4ffs2ent7EQqF0NfXh+rqahw6dIgdNvBtUygUWFxcxM2bNxGJRBCPx9nJazwex+rqKkMYzefzOHfuHKxWKyoqKrC6uopoNMrADsUxokWQTCYZ8un8/Dw7OaSdfXBwEKOjoyx33zvvvIOxsTGWAl1KjefHTorBSDEl/tp6ZgDxeWI2VVVVOHLkCAYGBvDgwQPs3LkTHo+H2fpoE3M4HNi7dy9LyPr666/D4/Ewtfy1114rwKMqprpJaQYbVVepTJonZFbQarXslJY2+Vwuh7m5OczMzGB4eBgjIyMMVmg9+geXqMbHx/Hnf/7n+IM/+AP8u3/373D79m38i3/xL6DT6fCtb32LifJihtTS0lJmW1hcXGTpx8V75E4J/tN/+k/4D//hPzz1Ox2bz8/PY3BwEKFQiO3CUkHJtLj0ej00Gg0uXboEo9EInU6HXbt2Ma9q8X4qR0rUFycBfz+v7un1enas63K5sGXLFrz77rtQqVR45ZVXoNfrMTQ0BAB4+PAhBgYGsG/fPiwtLeHRo0coKSnB8PAwTp48+ZTTIwD4/X5cuHABg4ODaGhowMGDBzEwMIAPPvgA+/btY0yNbwOVQzDHO3bsQCgUwuXLl2EymfD+++9jYGAA+Xye2YSk1J9r165henqaSUVkaD179ixUKhXKy8uhUCjQ19eHcDiMv/iLv2BY983NzQW+YCTZ/vznP4fb7UY0GsX27dthMpnw7rvvIpfLQa/Xo7KyEm63G1euXAEAFmOoVCrxgx/8gEkAdrv9Kf8vUZoQD19E6UOOeEO0OB7i93x+LQSGkorS3KUwkwMHDrB+BoCDBw+yjYVsfrW1taipqSl4p6jySW2w/Jzk/6TaV+z3cDiMR48eMUgkpVIJu92OaDTKTlcpGD0SibCQrfXoH5xR5XI5bN++Hd/5zncAAD09Pejr68Of//mf41vf+lZBo3gSRWcpKnbPH/7hH+IP/uAP2PdQKITq6mqGKz0wMICVlRWW2IEvT2ryuN1uvPXWW0gkEshkMuz4nerOO9+JEpI4+aTawf+ey63By+7bt4+dcuXzeRw4cAAtLS3I5XKoqqqCSqViWYkJi8hqtbI8ekqlEjt37kRtbS1DKTh48CAMBgNbBLW1tWhvb0dtbS3MZjPa29sRDAYRCASg0+lw4MCBAnsYSXlutxs9PT1Qq9U4evQoBgcH4fF4cPLkSfh8Pmi1WmzduvUpGNpsNouysjL8xm/8BrNLUdLP06dPM6bidrtht9vxzW9+k/Xx5OQkJicnWQp7Wow2mw2vvPIKlEolO1SwWCz4jTZdCJoAAQAASURBVN/4jQLoGMrSSxhbarUadrsdVVVVBYkqRC98ceMRf+dpI8Z1KdOCHJHHuYhOStIKbxgXvdiBQkQQkblKtUmqrr8oKRQKOJ1OmM1mhEIh5sNIiBw2mw0ulwtLS0uYnJxkWsBG6B+cUZWXl6O9vb3gt7a2NvzsZz8DAJSVlQFYk5rKy8vZPcvLy0zKKisrQyqVQiAQKJCqlpeXsXfvXsn3ksgp0vj4OB4/foxcLofq6mqGBS4n9RDxMWqAtP4uOgjyJLfj8Nf4srLZLDM2ExPU6XSor69nqiEAdHV1FZRDoRJ0fE/1JDSDjo4O9rvFYsGuXbsK7HBGoxHHjx+X9Cvjy3I6ncyOo9PpGOrkzp07C2wtvB2EZ1jNzc3sM0ldW7duLejvfD6P1tZW1if0LqvVysoj9ZJSQfHhJORIyqurNput4DsAppbQc3SQISURi/NDavHzfSU1T9ZTt/jfeKO0mN1avE+MYhDjQsnfr5jax5e53j3ivXz/0H8ynNOhFQFPLi8vIxQKsXstFgtCoRCzy65H/+CMat++fUw9IRoeHkZtbS0AoL6+HmVlZfj444/R09MDYM1H58qVK/jjP/5jAMC2bdug0Wjw8ccf44033gCwlk2mt7cXf/Inf/JM9SGxmdII8TnmiIrtMKLExO9o69mopCa0+Fn8jfR9+s5LNnz95J4XGQxfTz7ERWQkoj1KTp0lRsRLk/wCEftIlBzlGLpoI1KpVIhGo1Aqlcypk0+xxW8S/KGI6H0tVRe+vfwmQPcUCyORIykm9aykUKy5mywtLRWoTuR3xM8PcmGhQwTysl9eXsb4+Dhrx5YtW1jKLCm7LE9SGosckxW1CLpXo9EU2IJTqRST/EkFDAaDzO1CPIySo39wRvX7v//72Lt3L77zne/gjTfewO3bt/EXf/EX+Iu/+AvWmN/7vd/Dd77zHTQ3N6O5uRnf+c53YDQa8Y1vfAPA2inNt7/9bfyrf/Wv4HK54HQ68a//9b/G5s2b2SngRimXy6GtrQ2jo6Pwer2S4SE8UcdTPBWB2ZEzJB/nRuXw3/lyiKTsG/x/0RVAZEQ88xAXKr8wefVInEByOyYxAKm6i4uPl2B4Fw9RUuLrzTNdqTaJ9eTbwzMRGhNS1Yjp0hE3H+fIMyw6wVQoFAxkkJf8xIBqse5SG42U5FVMLZRSIaXaDgBLS0ssVVY4HMbCwgJef/11ZhulZ4LBIN577z1YLBY4nU4MDw9j8+bNWFxchM1mQ21tLe7fv4/R0VGGtiFKfVK03rwu9gy9gxhQNptlIWgajQZOp5NlJaJoBt4lqRj9gzOqHTt24N1338Uf/uEf4j/+x/+I+vp6/Omf/ineeustds+//bf/FvF4HL/zO7+DQCCAXbt24cKFC+woFQD+63/9r1Cr1XjjjTcQj8dx9OhR/M3f/M1Ti2o9UijWTu/UajVDu6TFVsy1YHh4GDdu3GB58ux2O9ra2ph6ut5Ow09EKXVATuyXUz2IyEFzeHgYDocDDQ0NePz4MaLRKFN/mpqaMDMzw+xOBoMBDQ0NLDFEKBRCZWUljEYjYrEY5ufnWXiF0+lksWF8vejEJhKJQKn8Iv/f4uIilpaWWLyeQrHmv1VdXY1EIoHZ2VkYDAaMjY0xxuJwONDY2MiM4vQO8g0aGBhAJpPB8vIyotEoHj58yHzYLBYLGhoa2D20CPbs2YNsNosHDx4gk8lgx44dyOfzuHfvHnbt2gW9Xo+bN2+is7MTFRUVBZuE1JgUY+5SVGxBS10Tx5kYrNvtxt69e6HVavHJJ5/AZDLBbDY/xWBIvSO/JPJbikQiaGlpQW1tLQYHBwtsQLx0KdZFZMi8VFms/eI8IbWapGACc5yenoZKpcKjR4+YrbCmpoblsFyP/l8JoTl9+jROnz4te12hUOCP/uiP8Ed/9Eey9+j1evzZn/0Z/uzP/uz/qC7pdBqTk5NIJBKor6+HwWCQ9CURJyXB2FKIh0KhKEibLj4jMiUiqd1LSgUkKjYpstksnjx5glu3bsFoNKKkpATRaBTDw8Ooqalh8BrpdBp37tyBRqNhhmNCDb169Srm5ubw5ptvQqPR4P79+7hx4wbKysoQCARQWlqKL3/5ywVIBQAwNTWFc+fOwWazwe/3w2Aw4NChQ7h69Spz8rPb7aivr4fX60VFRQUikQhu3boFp9OJBw8eoKOjA4lEAvfu3YPNZkN5eXmBZLOysoL33nsPTqcTKpUK9+7dY+NAyVLv3buHVCqFhYUF7Ny5E2q1mnnZf/DBB/D7/VAoFFhYWMDWrVuZv5jb7cbnn3+OmpoaVFRUFMDbyI2nOCZSqqAcg9qIqij1m8lkQl1dHc6dO8f8yUpKSp6aR2q1GvF4HFevXkVNTQ3GxsbQ0dEBnU6Hy5cvY2RkBH19fQU2XTkJT4p4KV1qjor1ISZoMpnYPKRcf9FolPnCkZMvSbu0Aa1Hz32sH0kAwWAQvb29LNW4aGAV1bF8Ps/A5y0WC3NMlFMVeRJtYHK0EfWBXzzz8/O4cuUKmpqacPjwYdhsNsaE6VSFgMlIwmlpaWFZXJTKtUw8CwsLjFn7/X50dnbi1KlTePjwIe7cucPsYfxiDgaDyOfzeOmll6DT6TA6OoqVlRUoFAp89atfxdLSEs6fPw+73c58exQKBaLRKKxWK6qrq3HixAmEQiG89957LPU63+ZEIgGdTocvfelL0Gg0MBgM+Oijj2C329HV1QUAGB0dZW4U1DaS9gKBAL7yla9Ar9fj3XffZRmyP/30UxaiQ30qZRsRpQNRNRfHSFTR5cZQjoqNd3l5OUpKSvDkyRNs2bKFIb9SvW02G1588UU8fvwYi4uLWFxcxK5du9Dd3Y3h4WEolUo230UJqZitim+HnJooZZ5QKBQsqcPo6CjzoCfP9LKyMtjtdmzfvh0TExOYm5tDMBh8yk1Jjp57RuXxeBg6pN/vh9lsLlA5iGgAaRDJ2TISicBut6OzsxMNDQ1P7TD8YEoNnpyKR5/F+6V2aqpbMBiE1+tFTU0NhoeH4XK5oFCsoQlcuHABer0eJpMJL7zwAkKhEK5du4be3l4AwMmTJ9Ha2oqysjJ2OkoG2/HxcYyPj2Nubo6loeKN26Syzc7O4saNGzh69Ch6enrw6NEj6PV6WK3WAlsQEZ1cKRRr6AYPHz6Ez+dDMBhkLgG8XYsYPElJtbW10Ov1WFpawrVr15jNw2azYWxsDGfOnIHBYEBjYyNLvEE464SQYbfbmbMoj121nhFXbozpO90jhqQUs/+IZUsxRhrrbdu2wW634+2330YwGITb7WZ2OXpna2srNm3ahImJCQZKV1FRAYfDwQzq5CwqZZ8qJlnJzUWx3kT8STW5AKVSqQKDeTweZ2aUbDYLk8kEq9VatK+InntGRfYXAp83Go0FMUZSOyL9ud1uVFZWMkjVYvp6sckqxayKlSHWh8rMZDKIRqMYHx9niSZfeukl9PT0sMQPH330ERYXF9Hc3Ayz2Yzy8nJcuXIFo6OjaG5uLmAOKpUKmzZtwpMnT/CjH/0Ifr+fJQ/gF2E2m0VdXR2OHTuGu3fv4smTJwxtgRgR2Q5J8uQZvkKhwNTUFN5//334/X4cPXpU0k2ETon4kBClUslsV319fTh58iQqKipw//59ZpwlCXJiYgI/+tGPoFar4fV6GVDiqVOnkMlkcOXKlYIEF1L9LkpMcvdKSRxyC1uOeYnjrVCsxXFev34dO3fuRDKZZH2RzWbx+eefw+/3Myz5YDCImZkZfPLJJ6ivr0dDQwNWVlbw+PFj3Lt3Dx0dHWhtbX0KiliqznKaxUbmO/9fo9Ggvr6epX4jvDIKpxkZGUEoFILL5WLB6Buh555R5fN5Fn1Oi0j0vgaePgVUKNZCRo4ePfqUUVHOxlSMOa1H/CSi56XKaGpqwuuvv45EIoEPPvgASqUShw8fht1uRyaTYZDLFBhO3t28OkbhNPn8Wgr03/qt30I6ncaHH36IYDAI4IvkDlQHnU6HPXv2oKWlBZ999hkuXLiAffv2MRWZys3lcgWp2knS2rx5Mw4ePIi/+Zu/QWNjI/R6fUFCV159oPL8fj9yuRzcbjdee+01LCwswOl0QqvVwmg0Yt++fWy3DgQCDPpFr9fj/fffRyqVQiaTYb5on376KRSKLyB/RUZUzL4ozo1i4y4u7mLSCf+MQrEWJhUKhfDxxx8jGo2is7MTHo8HKpUKkUgEfr8fqVQKRqMRk5OTuHnzJurr63HgwAFYLBaMjY1hYWEB7e3t2Lt3L7OrSo2pWHf++0aYudQ6yOfzLFs3gR5SeFYmk4HNZsPCwgKCwSASiQTzU1yPnntG1dTUhEAggMnJSSSTyQJjHiBtICXXhMXFRUxNTUGpXEuxTkZeIikRfj2Sk66knuXtCXw9adCVyrXceL29vdi/fz9zorPb7fjss89YxhbKXMsHP/MB1jabDSMjI5iZmcHu3bufCi9SqVSYnZ3FysoKtm/fjkOHDmF8fBy5XA4LCwvwer1YWFhgzNDv9zPs7lQqhXx+DQmiqakJTU1N6O/vR2dnZ4FqSRLeysoKJiYmYDAYcPbsWUQiETidTpSVlWHHjh149OgR3G43YrEYC7Uilwyn04nW1lbYbDZ89tlnjFnSAqWMLrz6VEz6XU9VEtWpjYx/MZtoPr/mlPvVr36V5cSz2WzMh2r//v3IZDIMmLCrqwsdHR0FcZA1NTUMuI6XbHm1kld7i0lOUvY4uXbyZWezWayuriKdTrPQK9pA29vbYTabMTIygtnZ2f/vPNP//0bT09OYnp5GMBgsAIWjQeSJt8sYjUb4/X5cvXoVAFBbW4udO3cWJOcUbVNyAynaruR2ZrpO16hOwJq9x+VyIRgM4p133kEul0M6nYbNZsO1a9cwPj4Og8EAn8+H7u5u3L59G4ODgygpKcHIyAjLPgx84QQLrPntXLhwAZOTk2hpaWFZZcT6xGIxfPDBBxgeHmbwMMQE//Zv/5bBBXs8HiwtLeHv//7vsbKywqQ6eueuXbtw7do1Zq+g/iCja01NDWtfaWkpQ4lMJpPYsWMHfD4f0uk0M7SbTCZ2TF9RUQFgTXKorq6Gx+PBpk2bWBtaW1sLwqfEfpcbO7mxlCJRMhYZ00aeJ3x4nkHmcjmW3IIvgxyY6R7ybxPnnFg/qXqt1yaxXJ74Mh0OB5OWI5EI8vk1JA+SkJeWlmC321m6rP7+ftl3szrkn1VH+b+EQqEQbDYbfv/3fx8XL15EOp1GXV0damtr8fWvf50hBfCTgffcTqfTDFWA4t0o5kzKtiJlU6LvPJEEwd9LZdB18V5+V5yZmWFOdHTEv7KyAp/PxyS/2tpaeL1eTE9PM2NmW1sbzGYz4vE4JicnmR8TISBYLBY0NTU9lSWZVKVkMokHDx4gGo1CoVCgqakJjY2NGBkZYRmoOzo6YDabmf9OKpVCZWUlzGYz/H4/Q0qdnZ1FZWUls3HxfUWeyyqVCgaDAd/73veg1Wrxa7/2azAYDAgEArBYLIjFYkylUCjWElmmUilmRI9GoywtE6VH4w3+oqQkpwLx2FTiNanx5cew2Bzgx7+YNMMzUNGzn+otFVVQbHMUDxLoN6myi9Vf/C2fz2N5eRk/+tGPsLi4yOJWCQWjubkZqVQKDx48gNlsZk7UhI1WzLD+3EtUFMC7srKCgYGBghgqkfgBUavVDK2SH3gx1AOQnpAiwxLvpc/0XcqlQdzFVCoVampqGA41Ta6KigqGPkDvdrlcT8Eu53JrOfIoa3I+n4fNZiuAqxWlqXw+z07TyCeHN0jTyRPZAAEwNFGeeB+0urq6Ag9yvk8tFgssFgvDqDKbzUgmk0xFIGxzghABvpCOyTBLqqZCoShQi+gz73YhR8Wkjo1IXVJETIU87EVpnOpEx/w05iQFitJMJpNBPB5nzN5kMkGr1SISiSAQCMButxcEN1PdpdojaglybZGTa/i6LS0tYWBggG0UAJgN1eVyoby8nDkK/zIB6f8ms9mMzZs3Q6fTwefzQaPRMLFU1N3FHQX4QlrimZt4Ly8N8U6EVC5RsUHmSWoh8GXxfk5kc+ExpMRUV7Qw6TsxFGJe/C5MC4kkCVECpPfSwucnNr2XZz4KhaKgv+m9VC+xD8hDntpkMpmwurrKbB3iePGBuXxYEV8uzwjEsJliKo/URiPWt1gZ4oJfXFzEwsIC4vE4amtrUVVVBZ/Ph/v37yOZTGLnzp2w2Wy4f/8+BgcHWaTB3r174Xa7C+ZCPB7H5cuXMTk5CQAIh8M4ePAgOjs7ceXKFQwPD6O8vBynTp0qgLER20ckFdMq1Q6pTZn/jdR8Ul/Jdw0Ag54uKysrGCvCUi9Gzz2jmpubY2mZPB4Pi7qXEo3Xsy3w3+k3KSYjNchSzEeUmIqJ1Px3sTxeNRHFf74OvNgvZXPg2yply6Dn6RpBpYjvExeAKDWJCTZ5hiP6JZlMJqRSKXaSSL8TI+VJZFBS1+SYSjGGI0obxVQ5KVIoFFhdXcWNGzcYxn1/fz9eeeUV9PX1ob+/n4H8bd++HXfv3kVrayusVivu37+P+fl5eDyegs0VWDuJ3bdvH8LhMM6ePctAIgOBAPbu3YuHDx/i3r17OHLkSEH9pMZejkRpj28TXxaNp0ajQWlpKZLJJFwuF0sgS0gJ8Xgc4+PjUKvVDGro1q1bResA/CNgVDabjQU/Us68YgMkNRF5kpqsxSQiqQVP/9fb0YsR1SGTyWBubg7Ly8tQKpWorKyE0+nE6uoq7HY7CwJVKL6Iu1Iq1/LFVVRUwOfzMQynVCoFi8UCl8sFr9eLcDgMvV6P8vJyhMNhBoesVCphNBpRXl6OXC6H5eVlWCwWOBwO+Hw+5iYB4ClpjH4T7XTiaRSpbQSdTNljpBaNODbPco1nMnKbCf+d/y91Te7d+fzaiRydQtPBxMDAAF544QVotVqcPXsWpaWl0Ov12LJlC8xmM0ZHRwukEiJyxaCIgNLSUrS1teH69euoqqrCrl27EAqFMDc3J1tnqTbJ3Sv2k5xqnM+vuSdMT09jdXWVqfBks6QTTJ/Ph+np6Q3P/+eeUQFryKDhcBijo6NsZ5Kijeyo/L3FdiO5XVgsa70dTayfWO7s7CzOnTvHdP2bN2+iu7sbc3NzOHz4MFwuFwsEXVxcxMjICMxmM5RKJV577TXMzMzgs88+QyAQQFlZGbZt24bS0lJcvnyZuTUcPnwYRqMRly9fZllttm7diuPHj2NoaAiffvopKioqcPLkSczOzsLv97NdnEjK9sW3S27BkNc7HSCI9xTrp2Lqy0YXiNS9cmMmJVlR2xwOB7Zt24ZcLsckfFJzy8vLYTAYmIpG+Qb1ej1z1BXfSww7GAwiGAzCZrOxrELk1OzxeDA/P//UHBTVPLHvxHbz/9fbDPR6PcOSi0ajLHDcarWyzayzsxMTExMYHR1lkOHr0f8r6bL+/0QWiwUmkwklJSUoLS2F0+lkKoyo8onqHxE/UOtJXHIkZ3eSKktcuHJqnEKxdkoGAC+++CLeeOMNbN26FRqNhjm5KhQKJBIJNoGbm5vx8ssvsySku3fvxmuvvcby7m3btg3Dw8PI5XJ4+eWXUV1djYcPH6K0tBRf+tKXUFVVhePHj+PEiROYmZnBp59+irKyMni9Xpw/fx5+vx+BQAAAnlLv5PpXqk/oHrJLUbBxsWfk+vxZmBJfPznTgJQ6LtUmXlokmpycxLlz5xiSByGxkpTo8Xhw4sQJOBwOZLNZ5psGPJ0wVK1Wo6OjA7/2a78GhUKBBw8esOP/XC6HUCjEjPLr9T1fX9EEIPYn36fiPWq1GmazGSUlJSgvL0d5eTkcDgezEQcCAYaPX1FRgZaWlg2NzXPPqJaXlzE6Ogq/3w+Hw8HCLqREV56kBne9nRR4euD4dzyL9LRRUqvVCIVCuHPnDqLRKHbu3MkWANkOiDFrNBrMzMygr6+PSUtqtRomk4mdchIiY0NDAzo6OtgJHsEFE/4RpYcvLS3F17/+dRw/fhzBYJAtDL5f5IK0eZsX30f0OxmTtVotFhcXmbF+IwBwGyG5RSiWJaUCFStPbD9tijMzM7h06RIqKipw+vRplJSUsOQWwWAQCwsLMJlMaG1txaFDh1j2ajq9pdM0cqO5evUqxsfH4fF44Ha7kcvlUFtbi8ePH+PRo0fo7e1l+OnA04dAcoycl8DEsRHbL64Pmk8Oh4OZF2pqamA0Gpn/WyqVgtfrLcgqtB4996pfPr92vL68vIxMJoPKysqCBbRRCanYjknXix15F1MVpQZ/I8/mcjlUVlYyw+n3v/997Nixg+GE027OT1Cv14t0Oo2VlRWWVgsA87cSFy9NLHImTKfTBR7uiUQC09PT8Hq9LDaNt0Hxn4sZu/mFQcwol8sxx8Dl5WWk02nmN1WsD59FgqL/xWyO/P3F1J9i45tMJvHee+9hdXUVp0+fZjn4SkpKcPbsWdjtdpjNZlRWVmJ0dBS3b9/G8PAw9u7di8rKSiiVSgwODuLSpUv45//8n8PtdmN2dhbnz59nqaneeOMN1NXVob+/n2Xz2bZtm6ytTWwXXZOTFott7HQ9l1vLnj02NgadTgeHw8FsnJQey2g0IpFIsCD4jdBzz6jcbjfy+bVTpXA4XLAzrKdz84MmpbvTd6my1itzI3YSOZsHXw+1Wo2uri50dnZidHQU58+fx86dO9nxPoWY0LPbtm3D9u3b8eGHH2JhYYH9TmE1AFgsIK+G0UkdeYorFGvuBRMTE/j444+ZUx95zFMdxfgyOYYv9ieRVqtFdXU17t+/j3A4zIz0tDEU20DkVEWxH8Xn5MZB6vtGbF/UV9FoFGq1Gnfu3IHVasXRo0dx6tQpnDlzBrlcDqdPn2YqeS6Xw6lTp9Dd3c3cSShGkhxYX3/9dfT09LANpaqqioFNkvc3zX+pusr1A30X4W3EjVlUFel3s9nMkudSVAGB6ZHKl0wmWYKHlZWVp/pMpOeeUfl8PpbDze12M/RK/thcajeRkmrE71JMC8BTC6iYKiROlI0wL77shYUF3Lp1C/v27YPb7WbH9hTAqtVq4fV6YbFYWHp0k8kEjUZTEPdIqiKw5u+yuLiIaDSK+fl51kfkSa7RaNgpYWdnJ7785S9jfHwcH330EQCwfHu8S8J6G4L4mWeQlZWVuHnzJhYXF1kCjGKqtJSEIG4mcmMnNRZy9S4mQYvl6/V6vPXWW8ybnjDCdDod3nrrLajVaubq0d7ejvb2dmaiIJW3srIS5eXlbH7pdLqCZBjUTlK7iKTmuNx8Fu8pJj2J7SXVz+FwoLS0FGazGSqViuWaDIVCSCQSbG46nU6UlpY+lWNBip57RmW326FQKFg4DAVrStk6RIZSbPdfz6ZRzE4lTnDxRGwjqgvtcEajkYUtAGAuCvfv38ePfvQjOJ1OeL1edHd3Y2BgAIuLi5iZmUEwGMShQ4eYSsf7GdXV1TE1ZWVlBdu2bSuAb+HjJF0uF2w2G0t3pdfrMTk5iR/84AdIJpOw2+04ceLEUxl7+TYUk3Ly+Tyqq6sZWkB7ezsUii9y2RXrq2IqHD8eZBOTGwOxfsWka6k60H18QlD+/RTDR995XH6xT6ievPMvH9ZFz/CY8lIMdT1GTfWWCq2Rm/sEyZPJZBCJRACAoa+SI3I+v+Yo7Pf7WRjURui5Z1ShUAgGgwGZTAZjY2MsbZM4CTbKHMSdXEoiktqJ5Zgf78Et9S6pZ/l3ut1ufPnLX2aJVY1GI0pLS/HNb36Tnf6o1WqWHGB1dRVarRY2mw0NDQ3I5dbSgh07doy5OHR2diKXy8Hr9aKtrQ1btmxh7dq9ezecTifS6TQLnSEY4j179sBut7MEDEqlEhaL5SlY4/X6Wtz97XY7XC4X5ufnkUwmWT03wqSkxkVKGhNVmvXKFcsWrxVTCaXmgljPVCoFv9+PbDYLt9vN1HKecrkc/H4/5ufn0dLSwlSrbDaLhYUFDAwMoKenh6nLcu2Qoo2uCbE8ClFbXl5GOBxmIT40LwEwH7yRkRH4fL4Nlf/cM6qKigqWTSaRSDAweT7eSo6krq0nCm90h6U//lSOnllPRRInellZGSorKxnTUCqVKCkpQVlZWcEu29nZydK7A4Uxcp2dnQC+CHPYvXs3C73hDfKdnZ0ssr+hoYFJplqtFp2dnchms6isrGS7J69OihKUVN9KbR5GoxF1dXUYGRlhJ40k2ckxeKl+FFUgsV+l+lhKgpCS/Day8Iu9lyfClX/w4AHKyspw+PDhguS39D8cDuOnP/0pQqEQKioqYDQakcvlMDMzgzNnzmB6ehq1tbVMXRZJbNtGGZNUn1MbM5kM7HY7SkpKmIAQiUQKzAVmsxkul4uhf5CttBg99+4JPp8PU1NTCIfDcLlcDNKVFpiodolHuET8BJFabFK/Se2Y9Flup5e6nycpAydv3BZz3/FMhrd3AF9A8vJMRewXHtyOVzekspsQDjr/DJ9vT1ykckxL7BNKUpFMJrG0tMRSXkmpkVJ9zJe7kfcXK+MXWdjPcn82m8XAwACuXbuGmpoaHDhwgPn+iUzWbDazVPZU15WVFXzyySdYXl6GwWAoGoBdrC0bbafUNQI2dDqdqK+vR11dHVt3NEdWVlaQy+V+iZnOk8FgYMGg27ZtY4uON6bLSU90bT2VT+458Xfxeamy+d/pOSlGp1arMTMzgzt37jBoFLPZjL1798JqtWJkZATJZBJtbW1QKpUYHx9HVVUVjEYjZmdnoVarmbuGuOilpBLqKx52hr7zdZRrp9w1OWZAkqZCsWbf0el0mJycZKqonPS5EYn0WVUbubKkGMgvWl4+n0cikcD9+/dRXl7OwBClsNMUirXDjbq6OvT29rLNob+/H5OTk+jp6cHExAQCgUDB5svPZ7EtUu171jYAa9joExMTWF5eZkgftKEmk0lks1mEQiFMTU39MgsNEYHbU7ooXt2SOn2TU+GKLSbx92IMSqps8ZqcNCX1rFarhcViwdDQEHQ6HSorK5HJZHDz5k1cvXoV2WwW09PT2LNnD+7fv49gMIjNmzfjzp07qKurQ0VFxVOLXk6i5A2r1Ic8hheP0CAuDCnGIsfQpfrD4XCgpKQE8/PziEQiBTkg5ahYP/LvX++auKjl1EK5za7YdZ7oejgcRiwWw0cffQSLxYJdu3ahpKSkYIOgcsnwTpIrnRROTExgenoaJSUl2L59O4uxk2qH+H5xgxSZ8Xrzkw6wKKUX+U45nU7Y7XY4nU5s3rwZSqWSoT+sR889o5qfn8fk5CTi8ThKS0ths9mKLhpAmknJqWhyJKeS8NfkpDSexB2QV/1yuTU88QMHDiAQCMBms+HQoUOYnp7GrVu3sHnzZlgsFty9excNDQ1wuVzo7e1FKpXC8vIydu7c+RSSgdx7ATA1kXZIsc+KTXC59q0nFdHGotfr0djYiOvXr8Pn8xWcIv6iJLXZSEmFYr2KScZS9xVjhlLt12g0cLlcsNvtGBwchNFoxPHjxyXfo9FoChJsdHZ2MoTNc+fOoa6ujiGpys13qTby0qxc26WI3F9KSkpgNpsZPlYul0Mmk2H+XYS429zcjLGxsaJlAv8IGBUlrqRccGL4DLC+D5MU45KTBqRUOvE3Ps5Q6h1Sv4mMgP/PY0cpFGvOmw6HA3v37oXNZsPKygqy2Sw6OjrQ39+Pmzdvorm5GaWlpQU2K56KqbS8Uyc5hvLXxT+5fhbHQVTNxHrU19fj1q1bmJ+fR11d3YZ2+Y2Mqaj+i9KU1AKXYkpyDG89SZX+059Wq8WOHTvQ1dUFjUaDeDzOfOOWlpZYEDOwNvaUVIM8+e12O9LpNB48eACr1cpO4taTYOXWQbH6S81ho9EIrVbLbFVarRbxeByhUIihYCQSCZYrciP03BvTg8EgNBoNwuEwhoaGGMwJ8PSCkPoTF5zIYOQGl7cL0DOiLYdoPWlNrI9INEn5uvr9fpYFeWVlBfl8nkmUq6urLGu0nI9NsYUv1xdS98iRFCOTe54+ezweNDY2Ynx8HPF4/Beqt6jG8P+LqfNSY86Pi9x3/v967QTAwAgfPXqEBw8eYGxsjM2d+fl5/PVf/zWmpqbY/cQQgEIHVLVajdLSUhiNRnZN6pRUqm/WG185ojloMBgQj8cxPz+P/v5+9PX1YWJiAul0msWVulwuhiSxEXruGZXT6YTH40F9fT3Ky8thMpkkkROALxa8FIYSIK/OiUyo2OBKMamNnMrw9ZGaWBRgTBMyFAqxSeLz+aBQKBAIBBAIBKDRaDA9PV3AiPmJLMdApCRJ3g9sPYlIjlHItVe8R6/XY9u2bVheXobP52P9LjdechKOyHREpig1vnJMSO66FEmVIW5oarUa3d3d8Pv9ePToEXMdyefzcLlc2LlzJ5xOJyuHIKIpKJlIqVRi586dqK6uLlDt+U1NjsGKfVaM5MYwn8+zgGq9Xs+SUEQiESSTSRiNRng8HpaQYz167lU/n8+HiYkJxONxNDQ0wGw2y05E4NncBdZbWMUWjlQ5G32HHPGMqqqqCm+++SY0Gg3+7u/+Dul0Gr29vbDZbNiyZQsePHiAlZWVovhc4vupb/j68nDC6+GQUxlS34v1Ac/YqqqqUF1djfHxcdTU1BSorutJcSJYn9w4822UihqQU/PWG28pdZH/Tm3ZuXMn83mjxLkKhQJOpxMvvvgik7roNLCjo6MgvRm9izJp0zjRM8AXfm18W9abn+sRPU8Zk4C1yJDy8nKGUUUe64lEAqlUit23Hj33jMrhcMBgMMDv9yMajT6VgJEncVeRG0Apm4VIUoug2EQQmYBcveQWBcG4AF+EVVD6eqPRiGQyifHxcezatQt1dXUYHx/H6OgoO02SIjmpSqpuUn0n1zfFqJgKTNmAuru7ce3aNezatUvS672YqiXVl8VCqfjf5SQ3KeIZCT+24kbIh3PxjJ6YE4V80bOEHkGSGMVsiuaMfL4Q8lk8NJHKevR/QnzfZrNZrKysIJPJYHV1FRqNBgaDAel0mhn/M5kMFhYWEA6HN1T+c8+o1Go1SkpKWJLMZDLJrsntqHKBylK03s7KTwp+0vCe2qKTKe+tzu/iVBavghG1tbUxNEy3242dO3cydbCjowNOpxN6vR7Nzc0wGo144YUXYDQaJZnJekyRv4/qxi/iZ2FOz6JukNRBmXiGhobQ1dXF+oxQBkSGtJ5kQ79JLXb+Hikbjngd+MLjn+pE94l48LzTKj+mPJNTKtdSlRFmPDlMEhFAos1mQygUYjF0JpMJlZWV8Hq9GB4eZs6WmUwGJpMJXV1dBR7rv8iGItaZSK/Xw2w2MzjraDQKnU4Hg8GAhoYGGAwGlJeXo6GhYUOJHYB/BIwqFArB6/VCp9MxzHQ+ALeYhEDE74YbXQA02cQTPjGYVso1QGrwpVQknqFROEs+vxYb19HRwfCjtmzZAgCoqqpi5fAps0R1bqNUjCmJqpWUVMr3o1Sb5chgMKCzsxP9/f1obGxkrgrFGKsozfDjwm8k1J8i46Xf6T7qfzlGy9eFEFZpDhLzIVSP8vJyuFwuDAwMIBAIoL29HWVlZchms8hms7h37x7u37/PMg+nUimGEZbL5XDgwAEcPXoU169fx7Vr11jSh/LycgwPD+NnP/sZaz/FdhLirZQ0vd4GJbZTVB/VajWcTiey2SxMJhNLXJHP5xEIBFh8Xzab/aXqR2QwGBi4vNPpZKcg/AQUGYnIBIikJiW/uOioWFTj+IVIk5t8kqQYEL1f3IF5kZ73naF3iyqBVOaQYkxBTgUtpr5KSRj8fSKTkmJExRiy+C7qk5aWFvT392N6ehqbN28uYP5SC43alEgkmFRNEf2U5YaHp6HvKpWK9WUmk0E6nUYqlWLJCjKZDDKZDMNAp9/z+Ty7l6SeAwcOYMeOHUilUtDr9ZiYmMCdO3fwla98BWazGdevX8fAwAA0Gg0CgQCePHmCWCyG0dFRTE1NQa1WF8TMkRq8detWBkaXTqfR1dWFTZs2sTmUyWQY0wPWtAxSF+WkR74f19s8pDZspVIJnU7HEo2aTCZEo1HW9xqNBslkcsOS3HPPqOLxODQaDaampqBSqZBIJJ5aGKRSSC0ucRDXk6JEkDhRzaN3SYXwSLk08PUk4tWcYDCI1dVVBnan1WpRUlKCWCxWkFFZqVRieXm5oB1ut5vlXovH4yyBJyFO8GqLFEkxWZG5F7NViXYb+hyJRBjoGl8+338WiwVbtmzB6uoqW7S8yiSnkj98+BDnz59ngerkiCjWh98UaFOh+/P5PMOOklLr6Xd6BljzLVpcXMRnn32GgYEB7N+/HzU1Nbh48SI+//xzltiBGFwsFsPc3BxSqVRBUC8dmKjVarS0tOCVV17B/Pw8EokEFIo1zKr9+/djcXGRJd+lPuP7gY/HJJICIizGwMT1wJdHKJ9ms5nZpDQaDcOCp3FaWlqSnV88PfeMqry8nO12UlAZUqrARlUQqXKAL9QyPuCXv6ZWq5FMJpkaSEgOtGj4xJ5inBevMiqVShbrNzs7C6PRiPr6euzYsQM3b97ExMQEFIo1ILatW7fixo0bmJ6eRiKRgMfjwUsvvYTS0lJcuXIFQ0NDOHbsGBoaGnD9+nVs2rQJjY2NG1Kn1vtd7Bupa/zOvp67Bj3T1taGSCTyFO66nASnVK6lel9eXmaqE20QYpAzvUdkvFSmVNwjXeMN1zSW8Xgc165dY+gVmzdvhtVqZb5E0WiUzc9UKoX29naGmNDf34/z588X1Fmj0aCmpgZ2ux3Ly8vQaDSoq6tDLBZjKe8Jc93j8bDUVMS04vG4pHmDp41IO+IzSqUSWq0WLpcLy8vL0Ov1BRl3yM5mNBrhcrnYKeB69NwzqrGxMYyNjSGRSKCjo6PAgMwzJlE62MhRu0j0bCaTYWmpzGYzRkZG0NLSgmAwiGg0itraWgwNDbEwg4GBATQ0NGB1dRV+vx8dHR0YGBiA0WhESUkJRkdH0dLSArvd/pQ6uWnTJthsNnzwwQfo7OzErl27MDg4iLm5ORw5cgSJRAKff/45mpubcfjwYdy4cQNerxfHjx+H3W7Hxx9/jL6+Pmi1Wnz44Yc4duwYfD4fYrHYhpi1nP1Jrm/4z8SUxDbJneSJDEir1RZgLRWTfPl6ib5ffIIBOalClBKlmBv9JxWLz16tUCgQi8Wg0+nQ09ODxsZGDA4OIh6PQ6/XM5NBOp1mCTr7+vrQ0NCA1tZWhnDKt2FsbAwPHjxAPr8GLqjVajE9PY33338fOp0OW7ZsgdFoRCQSYcyVGKWc2rVRVYxvLxFtuoReWlJSApvNBo1Gw9S+aDSKaDQKt9uNeDzOPOzXo+eeUbndbpblg8RdKTTHjQ6Q3I4t7vY+nw8PHjxgWV3a2tqQTqdx48YN9PX1IRKJ4MiRI1AoFBgeHsbo6CgikQhqamqgVCqRSqVw7949GAwGKBQKBlLHSx20qD0eD8xmM2w2G2PE5eXl2Lx5MxKJBEZGRqBQKFBWVobS0lIolUpUVFQwqOEDBw6gtbUVH374IcbHxyWP4aXUPKl71lOPRZJ6l5TURd95KUasR7Ex5BmKaCgX7TRE/CkgSb1iu3h1U65+pPqr1Wps2bIFx44dw+TkJC5fvox4PA6LxQKVSsWQBgYHBzE1NcWgUFpaWphkR/Mpk8lgeHgYY2Nj0Gg0+OY3v4lkMomJiQlMTExAq9XCZDJh06ZNLH0ZmSXIKM/3jdj3Yr/KjamUFEaHBYFAgDl3Us5Bkq6USiXC4fCGPdOfe0ZFE4Gww8mwKe7igLR0IKejF1N5wuEwFhYW8PDhQ2QyGdTW1rJsxgRob7PZ0NTUhHA4zOCBlUols2XMzs4ymBaXy4XFxUVmaxLrzBvwpWwo9BlYW3y0KKgM8sWhaHfepiYnccr1zUZILEP06ZF6r9RYSY2HHMPiJQq5+8R5Ib6H1HieEZE6A3wRpkIbIi1IGrOmpiacPHkSq6uruHDhAjv94pmGTqdDZ2cnWlpacOXKFWZHBNaiLF577TWsrq7i7/7u75jNKpfLIRqNFtSfpBdilOQ4SqqpFNPl213M/CGnMtJnai/F9uXzeYagQGitWq0WTU1NiMViGB4elnwPT889o1KpVEin09Dr9cyXSFwItMAB+d2FXwxS3/n/NFlpApMPCWWEoRMRq9XKQnpoAdG9POhZeXk5A08TY/p4ZqPVatnCIIZEfUDGZjqJorqHw2FcuHABCoUCq6uraG9vZwZhvo+KTVo5RlFMshL7T3xGqgy5Oki9R06tEReo6GLALzS5tor38zZEHvImnU4zpqBWq9HZ2Ynq6mrEYjEcOHAAXq8Xn332GTttBNaYYSwWw+bNm1FVVQWdTodQKMTcG8hc4Ha7mZ1Tq9WyU+3W1lbGPN1uN3Q6HXbs2AG1Wg2j0QiTyQSVSoWmpiZJ1wRxgxKZEv0X5zw/V9RqNSwWC+x2OwwGA4xGI0s6ms1mMTc3B4fDgWQyuSG4HuAfAaOiE5RsNguHwyGLt81/J7WKt2VILRIpsTeXy0Gn08Fms2Hz5s0wmUyIRCKwWq2Ym5tDSUkJ9u3bh7GxMTZxXC4XOjo6sLi4yGAy1Go1du/eDbvdjrGxsQLkTqobr8LScbNC8UVqplwux3xuqH38MTX51Bw7doylcad7xT9ekpBjBMX6Z737+X6Wkmb4e6TUPvE9Uu/mDy3oM78R0T0ig6b7eebPS6a0MdBGQUTSOzlAUhLOiooKVFZWYmlpidXNZDIxA7vNZkMsFoPD4WDlv/766wz+xePx4Hd/93eZBK5UKtkpbWtrKytTo9FArVbjN3/zN6FQrHm184xaahzFeSV3H9+3UhKWXq+H1WqFwWCAy+WCxWJhYTSrq6sF/lUboeeeUVFoSSAQwMLCQgGWkkjihCfbg5TNRMpWw4u+lZWV6OrqgtVqxfT0NLRaLWpqauB2u1FbW4v29nZYrVZoNBrs3LkTtbW1CIfDCIVCDH+cdqOmpqanvMhFSSOTyTCpSa/XY2xsjOXbW1lZYcD/VAapflRXt9sNh8PBApcHBweZK0dFRQXKy8slmZSc9CT2TTE7FX+/yDjkyuP/r6eC8td1Oh2z8xBzIWZAR/kknZKqpFarCxiSQqFgjIfQC0hiIYlYo9FAp9NBp9MBWGMaJpMJBoOBSfUWiwX19fXsnfX19di+fTt7F809m83GcOiJ0VitVgAoGMdcLsewp/j+5KF4xL4W+53vL7FPxfknd59Cseb+EAqFsLS0hOnpaVaHbDbLMkQHAoFfuicQORwOxONxhMNhNuHkYtuKMS8p6YkmiDgxdDodC+1QKpUsxRMxC6VSWYCn1N7ejnw+X5Cpo6qqipVXV1fH/LH4OhFptVpUVVUx7OzGxkbs3r0bQ0NDLFyG8hk6HA52ZE7uDHTyUlZWxgzyU1NTCAQC0Ol00Gq1KCsrW7evpaSdZ6GN2kWkdnhRRRcXFEmDzc3N+O3f/m1m9+FNAbzUyktIPDPTaDRPqd9ExMj4+vLzRKwrMR3+Ht6FRqp8ktpp3hHD5YPDpfqO9y8rZueT+q2Y+i3Ofb7dJL1TNmS9Xg+LxYKKigoWzgUAIyMjsnUneu4Z1dTUFMbGxpBOpxniIJHcjixldyEqpm4Q8VKY6HwotRh5CYKXWvjneOAz8XmtVov9+/dDr9cz1fP48eM4dOgQm/y087a1tbH6mUwm7N27l3nrb968Gfl8nnlW02Lg06g/izon1WfFpB+pzWCj71rPhgaAhXS0tLQU+KpJ+akRc+NdDOi/eGrIH3BIoS3Qc3KOsHKMRJyPPMMV7WK8RC8+z8eMiu8X6Rfpc/HdCsUa0kNJSQl8Ph9CoRAUCgVLfBsMBjE7O7vhdO7APwJGVVFRgaWlJXi93gL7wrOqInIDK9oz+D+5gRbj/6SkAyLeriL3DC+t8ZloSFLiFwt5NlNZOp2uIFyIVAVRauClOVE1k1IJpUhk2mI/8uUV28mlmKY4DlJ9RIyCpFPRmZbayDMU/gSUX/DiePPf+VNAXuKQcjCl7zxjFJ/jie8bUYKUUs3EAHeaS+IcFP/LjRPf93LzVqVSMQwqQvkkr35yUYjH48wJdCP03DMqiqtKJBLMLwUoLhnxk4e+S0k8csxOnExi+UR0Tcp4yZdDMWkiRI3U+2kR8tlz+V2bT8bAMwO+LL7tUo6vUl7cYhlS14upEPx1qTrJvUeO5MoniUhc6NQuPhZTjIUrNmfkpBiekfAMj2eS/OmsONfEeoqbCt0ntoXHm+I3Ol4y5JmElPYgXhN/Ezctsc8jkQhzTyBGRaFRlHRFCqlVip57RqVQrB2X2u125odEBnW6TrTerk2/F9vxxeeKSWHiZBbj/oDCiH6p90jVnRaBVNyb1C4oVwd6vxSz4he0+LucnUauH/i6bEQlkSKR6UrdzzNfucUn5QzMl19M+hXHlM8/yL8fQIFUI6px5FJDWOhkJ4tGoww/XafTwWKxIBqNsozKOp0OHo8H4XAYS0tLSCQS0Ol0qKmpQTqdxsDAAHPVqa2tRXl5edH+kuoHvs1yY0q/x+NxdjJKcyudTmNiYgJGoxFms5nFn65Hzz2jSqVS8Hq9UCqVzCsbKJwo4s5EJIrm/O9EcieDgLRBVTzi55mS1GQRF70Y9CxOIH4xiioJ32a+jvzEk5IMxHbzR/V8O8Qypeomx8hFSWKjxPet2B45psy3S0pC5aUNKQRTPqCXDO6RSIS5iFBCBZ/Ph3Q6zVxjTCYTlpaWWEC02+2G0+nE1NQUQqEQkskkysvLUV1djcnJSSwvLyOXy8Hj8aChoQErKyuYmZlBPr+G3tnc3Izl5WUMDQ1BoVCgtLSUhVlRHYlZGgwGVFdXs43bYrE8JQ0VY8Lr9T9/v0KxZj5wOp0AwGxTsVgMqVQKPp+P+TX+MoSGI4VCwXC2eaYjDg4NHL+Yed8kcSGTdCalkvG7K1DoCCguWKldnFcDxJAM+syjC0jt3KINhn4T2yolNYlSFRHfVlHa45kb/x6x7XLSG8+MgS/UF2IWfN/k81+EpvCqFDlPkuE8m82ybCdkL8nlclheXkYikYBWq0V5eTmy2SwmJiYQiUSgUCjQ2NgIo9GIoaEhdmLc0NAAu92OR48eIZPJMJcTp9OJ8fFxBINBqNVqNDc3w+FwYG5uDl6vl50amkwmVj9yAlWpVCx4OJ/PMx+6srIyOBwO5nKgVqtRUVEBt9sNlUoFnU7HEpDW19ezMSTfKgpo5vu9qqqqQG0vpkL/IpsFfaZ3hMNhpFIpZkwnHz2DwYBkMolEIgGv17uhdzz3jMpms8HhcMDn8z2FZEAkSku8oZV2SRLHeSmFfEPEqHYALBA0n8+zSUVxTrQ4yU8nEokwMd9oNMJgMCAcDrNTEUoySmERtONbLBZks1msrq6y38hJkOBPstksjEYjLBYL/H4/kskkcrkcczQlVEiFQsEmeCqVgt/vRzqdhsFggNvtZpOKDPIejwcajQaLi4usjoT3RUiq+fwaiJ/ZbMbs7CxWV1ehUCgYjvbS0hKWl5ehVCphNptRV1cHv9+PlZUV9u7GxkZ4vV7Mzs4ydMqWlhZks1lMTU0x+119fT2i0Sh6e3uRz+dhtVqxefNmKBQKzM3NIZ1Ow+l0FsDjEHyKxWKBwWBgcC9kCCaGQW21Wq3QarXo6OgoiDDgj9rJkKxSqdDd3V1gwCcGyEuBSuVa5AHNK2Ji5CfFb1J6vZ5JIKIkyp9Oypkh+PKKMSmp8vn1wX8WTzlpY6KTYlJVA4EAEokErFYrnE4nKisrmVR47969onUB/hEwquXlZYTDYVgsFoauyHe+lMhLgbyhUAh6vR7l5eXweDyYn5+H1+tFMpmEyWRCY2Mj4vE4njx5gnA4DLvdjra2NhiNRgwODjIIkurqalRWVmJ2dhbz8/PI5/MwGAxoa2tjQajkodvU1ISKigrMzc1hfn4eyWQSJSUl6OjoYM5zSqUSJpMJDQ0NDAudDg10Oh0UCgX6+/sRDAahVCrR3NwMvV7PpEoAKC0thdVqhd/vx/DwMDKZDDweD0wmE8LhMGZmZpBIJGCz2VjmW/Lwt1gssNlssFqtbCKazWaUlpaya5lMBolEAnq9HkqlEgsLCwWSIgC20Hn/IYPBAIvFwhg5MWRazNTGXC7HVBmFYs0Bk+LI+LIVijWYGwAFnuRdXV0F0lkul2Op4mkBEhMR1US73Q6gcNFS0hBeuuQZEi9J8lI0r/YTw+HvFeeolKoqzmep63w54tzfiH1KSlWXIuoDQg5Jp9Ow2WzMxqZWq+H3+7G0tASbzbbhUz9Ffj3W+n8phUIh2Gw2fOMb38Dk5CQikQheeOEFnDp1quDYXs6+srq6img0ypgCIRTG43EoFGtOnUajsWBXoeQDSqWSRYuTyqHT6QrEft7LmVQVejcFCfOuBqK6w09qPtBaSh2kP5LaiEQYEqoTqRZ6vZ6Ff/BxhOSXJYZj8A6JvHqRzWbh8/mwsrKCRCLBJFaxvryNg1db+d+lVEZ6Hig8kaTyRXskv9jEMCmRUVGZonpMZfMMia8jT1J2Pr6uIvF1ERncerYkqeUsxfD472J5ogQl9r/U+0QGeevWLXz/+99HLpdjYUGhUAipVAoLCwuoqKjAnj17cPXqVZw5cwarq6tMipSi516iojAG8qUSbVBE4iBSxlm6BgAWi+WpIEqeYZBaAYDt/PxkoO9AIVa6aNOhsqg80c4jTjzeiVVqt+RtP1IneISuQAiMZPjlGZLUBJfrP3GXVKlUDDdqbm6u4BnR7keqpTg+Uu4ZvA1NavFIqTi8XU50lOQlH14yEiUaukYbE1+fYtIJ/y5+8fN1FvtSqjy+DsWYl9j2YgyuGEkxOKm28aRSqVh6rGQyifn5eSb1kymDIJI3Qs89oyLVg3dPAAp3aXFxS4ne4u7DLzAiud+kPvPvkSKp61L3Su1oUsQ7jErtjGQjouQXYj+JdXsWIibodDqxurrKbGpULynJgX8PL1EChQcCJH3xdRIXv7ho+X4VDxukypFrM3m3r9cnxe4RmYDUBvAsSs96ZdHv4me5+he7JnUv/TeZTCgtLUUqlYJOp0MikUAoFEIul2PmAcLLOnfu3LplP/eMKhgMIhwOQ6VSwW63PxVLxRO/EMQJIqWn8zsb/ztPUjumeL+UlECf5RiWlMoBFJ4uytVLZMJmsxm1tbWw2Wxs4cvVWWyb3EQW200qo8ViYadA4mLhmYco+YljIvaTXP+up9qI9ZW6T0qV41EoijF1vh70WWq8N8oMiklFxfpBjjYyxs9KCoWC5fAj6dxqtcJutyObzSIUCmFmZgYul4vZTNej555RWa1WKJVKLC4uYnV1lf1eTFwm722yb4gMQ4pp0fPib/z7xPdIvXsj5YtliqqK3D1StgoyGDscDlnJpBitt9BEhkSeyaKdSc5xdCMLUaSNLFa5ektJczyRnY9SkcViMdjtdkmV+hetm1jHjf4uzp1iz8ptgsWe2Yj0SKRSqdjJL510k2SVy+WQSCSgVCpZ8ov16NmBwf8vI5IYNBoN65RitgQ5KUEqqFRqUfMqVrGdk3++2G+iQVxK/VQoFEVtWLwhmZeYADCVTO49G/kT21isT6WekWIOcirQsyxeUerky+LL5P+k3s1/Hx0dxZMnT5DPr7mV3L59G7FYTFZiouf5jUTOiC7SszCGYm2T64v1zArFNt71mKVWq0U6ncbi4iIikQgWFhYwMjLCHFbJDFPMgM7Tcy9RqVQqJoKS/UVuByHJhP7TzkmOaqlUitkl6OSKX3yEZU2GX0L0TCQSDFSfMNBjsRg7HSSUT4KOJaZIqYb8fj8MBgOi0ShcLhfUajWWl5ehUqkQj8cZkiL5XikUCqZmxeNxeL1e5rPl8XiQyWQwPz/PgPfJsLzRo+JnIZG5kKe2eA8gfaokRVLSjiiBSjG6YgtPrr5A4aloIBBAOBxmksLS0hJSqZTk83L/1yOxDVLSuLhhPUu5G5G4pJ7dKHOlk77q6mqW+oxSumez2QK4I94xtRg994wqFArB5/NBqVQyHxu5Tifbw/j4ONxuN1wuFwPcU6vVCIVC6O7uRjabxZ07d+DxeDA3N4fu7m64XC4MDw+zUAq73Y729nZ4vV7cv38fVVVVmJmZwcGDB6HT6XDp0iVUVlZicnISO3bsQEVFBXp7exl2eSgUwokTJ+Dz+XDu3Dm0t7djZGQEL7/8MoxGI65fv46KigqMjY1h8+bN6OjoQF9fH8LhMNLpNLRaLQ4dOoTJyUk8ePAAzc3NmJ2dxcmTJxEKhXD58mVs2bIFiUQCO3fuZDn9/k9ITs0kIi9lcdeXOr7/RaQIek6UFOTUbCkpY7330tj4fD4EAgGGAsA/L0rGUmXyaloxda2YNFiMxP6Xs++t975iKjL/G+/moVCs2agIJ12n0zEXn2QyiXA4jJWVFSSTScRisaLtIHruGRV15tLSEkvICcgfsQPAwsICy4s2MDCA1dVVuN1u3L9/H7W1tcwDev/+/RgfH4fJZIJWq8WtW7fQ0NCAeDyOiYkJVFZWore3F8FgEM3NzRgZGUF9fT2USiUmJibQ1taGVCqFJ0+eQKFYS47Z3d0Ns9mMu3fvoq2tDWNjY1Ao1uK47t27hwcPHsBsNmNhYQHt7e0wGAy4c+cO1Go1Hj9+jJ07d0KhUOD69euorKzEw4cPYbVaUV5ejrt37+Lhw4cslKisrAwLCwssfdFG6Fl3b6JcLodwOMzyuD3Lzr3eAvtFbCgbZVKi9KJSqfDw4UMsLCwwh14+9k9OzZWS/uS+b+Q+/j3rtbNYvxRjkvw9xfpGqq4k7YdCIZaNmofH1mq1SCaTBYktitFzz6icTidDpyQIFFLJeKJOV6lU2LRpE+7cuQOVSoXZ2Vm0tbWhvLwcjx49wuXLl5FOp1FWVoba2lp4vV7cunULU1NTSKVSaGlpQS6Xw7vvvouPP/4YPp8P+/btY9HqV65cgUKxFkpRX1+PRCKBCxcuYGZmBlqtFi0tLdDr9Xj8+DHee+895PN57N+/HxUVFejp6cGlS5eQy62lUKquroZarcZ7772HDz/8EFarFXV1ddDr9Xj48CHef/99qNVqvPbaa6isrERDQwM+++wz5HI5vPDCCygpKYFWq5X0ZdkoQ5Iiqc0gn1/LRMLjt8s5Qq5HIkNY716pz8UkhWJtUalUKCkpwe7du+Hz+TA6Orqu/UeKGcjZ4TbKZEVJTCxvPSP5RmyLYjvk7pXqV5KiiEkRUkIut4bTX1FRAavV+ktjOtHs7CyWlpaYbgx8MYi84ZuniooK2O123L59GyaTCTU1NXC5XNi8eTPu3r2L2dlZdHV1wWg0YsuWLQCAa9euobW1FSUlJaioqEBDQwNu374NnU6H+vp66PV69PT0YGVlBUtLS2hra4NKpUJ9fT00Gg0GBwfR0dEBu93OwnPGx8ehUChQX18PtVrNcvv5fD60trbCaDSirKwMTqcTMzMzqKqqgt1uh16vR01NDebm5mCxWFBaWsoy6VL695qaGqjVapSXl284E4hIcoZncRHQguIxkURECnEcRGOwSKJKI45lMYmNv1+qTVJ1p2c1Gg1KS0vR3d2NPXv2sNhKOUYh/km1QWzPekT3iNhq4vVnYf4bfedG71Or1TCZTHA4HAz7v7KyEh6PB3q9Hn6/n8WOboSee0ZlNBqZ0ycB7a9nWKVwFvKmpcSQZDAn0VWhULAj2Gw2y7LPJpNJZmsiXKF8Po9QKMQ+k25OBnC1Wo2lpSWk02mk02msrKzAaDQWOMpNT0+zwFwaZMq+7HA4sLy8zKLSx8bGYLFYEAwGWT7D2dlZFv82NTXFUhfNz88/c7+utyOLDIpPIy4ymfV+498h9wzRRiUJsQwpu5KUcZ/aw38v9rxYP/E58TeR6a7H5NZjcFJt+UUYWDHGz7+H/y0cDhcw05KSEhYPGo/HkUqlNmwbfe5VP+oQn8+HcDgM4IuOFD2c6W9lZQX9/f0sm8uWLVvgdDoxNDSEyspKpFIpDA4OsnTriUQCbW1tGB8fZ+mAZmdnsWPHDszPz2NychJarRZDQ0NobGxENpvF4OAg6urqMDAwAIPBgAMHDmBycpJl5RgfH8fu3buxuLiIJ0+ewG634+HDh8wxs7+/H83Nzejv74dKpcILL7yAe/fuYWxsjCUSPX36NB4/foyhoSGYTCaMj49jz549CIfD6O3tRV1dHe7cuQOtVsskw/WkjI2Q1CKKxWLsVHOjZa6nlvG/b/ReUeUjZsqXIWXzos92ux0OhwNqtZqB0vGhUXIq5UbasB6tx/DkPherjxw9q51QfKdOp0M8Hsfi4iI0Gg2MRiPbaCmsLZ/P/zJdFlFzczPzijabzU9hRImTkpiI2+3GqVOncOnSJfT29qKyshKBQAAnTpzA/Pw8RkZGUF5ejt7eXrS1taG1tRUXLlzA4OAgQ2vYt28fPv/8cwwMDDBj8vHjx5FIJHDp0iUMDAxgdHQUXV1daGtrw8rKCgYHB1ks1L59+zAyMoK7d+/C4/EgGo3ixRdfhMFgwOTkJEZHRzE7O4uWlhb09PRgeXkZw8PD0Gg0KC8vx5YtW5BOpzE6OsoQCXp6ehAKhfDxxx9jYmKCnWgSGuSz7LjFFg7fx/F4HMvLywyWVipmT5Ra5DzrpaQs0U+M7itmAN6ouiS2p7y8HC6XCyqVCkajEfv27WNoDiJjE5mhWG+5PtyIgVyqzlLB2mK7i30vVrbcfXKkVqtRWVkJv9+PSCQCs9kMACyo32azFYS0rUfPPaMaGhqC1+uFQqEoyHnGMyy+01OpFNLpNNra2lBTU4PGxkbMzMwgGAwy25PVasXMzAxWVlZgMpnQ2dmJiooK1NfXIxQKQalUoq2tDR6PB21tbRgaGoJKpUJzczMqKioQj8fR0NAAlUqFyspKNDY2wmazobOzk0HFdnd3w+l0YtOmTewEsru7G1VVVQCAHTt2wGq1QqfToaGhAWazGd3d3QV+K0ajER0dHQzixmq1wuFwwGg0Yvfu3fB4PCzmyuv1oqysrADVgUhqUfOSiAjQx6sqsVgMi4uLCAQC7Bq/qPmUUTzxi06hUDwFUCg3fsWo2H3rqWr0O5kQyO+M/OqkmJQUU5Sy6Um9Z726iyqsXFlS94nXi9mJxA2gGPFtpTRZhK2VTqcLbKSBQABzc3MsPdx69NwzKh5tkPd3kdql8/k1Y2lXVxdMJhNyuRw6OztRU1PDUqyr1Wq43W4cP36cMSmCnj148GAB6qRKpUJtbS1KSkqYqEsJK48cOQKtVsuCNlOpFLq6up6ql8ViwZ49e9iCoAW6bdu2p1ADamtrAaAAzJ9QIGhCKhRroQwdHR0AgJKSEuTzeUxPT0OlUjFpQU5FkmJgFPfGQ9uQnY4A0yj0hGc+Usil2WyWtZWPBqC05URS9eAX7EbjFfm28SqgFGOQkjqKSR5Sz4hUjIlJ1VN8r9Q1ufKLvVvq92ISmFTdxDZrNBrmGE1QRCaTCYlEgtlof2mj+t/kdDqZvwZlwlCr1U9hlxMplUq43W4mJZCISgyI7iH8dX5iEz4VLbJcLgeNRlOQqZYfRKoLDSafHJXu5yGJaXHzGEt83XlYGHqGj6vjP9M78vk886ifmJjA6uoqKisroVarodFoJOFEqG/oWTLqkx2QZ5Ti8TMPDEfwMnxd+D4l6S6XyzFGJ4VfJUcbkQLEcnhGyo+XVHlSc+hZpTyxLlLfi0lnUhuuHFOVqtezMMqN1p02HIPBgFgshlgsBovFgsXFRQSDQWazUiqVv8xCQ0Te0CqVCgaDgU16fkEQ8UyH37VEuwotMPqdV314dSidThcwGrF8up8nuk5e8vQbMTI6OeOlHlJXKTxHqVQilUqxdpI0R7DFZCOg51dWVqBQKOByuRhuFzGY8vJyhsQYCAQQCoVYOnMK7yE3ipKSEsTjcUxOTrLTUKvVisbGRnaqaTAYWNgEoZsmk0k0NjbC6XQim81iZmYGyWQSTU1NbJyGhoYwOzuL+vp6BvsrBoyLkpDI9PlxFukXtcWIc0fu+Y0w1o0wE6l6ixKWFFMTrxWTwDZS1/XaoVAoWPIKOniwWq2IRqNMq1AqlSxj9Xr03DMqwikH1jCXeMmk2CRPpVKIx+MMfSGRSDB3BWANytdkMmFmZoaJtR6Ph4Ht8SiWROvp+iSJabVaLC4u4t69e2hpaUF9fT3y+TwWFxeZw+iRI0fgcrmwurqKy5cvY3FxEVu3bkVPTw8ymQyuXr2KR48eob29HUePHoVWq8WTJ09w9epV6HQ6nDp1CpWVlZiamsI777yDRCKB06dPM8jjM2fOYGlpCT09PXj55ZeRSqXws5/9DLOzs6isrMTp06dhNptx9uxZPHr0CEajEV/5ylcQiUTw/vvvw2AwMEzyb33rW4hGo3jnnXfwwgsvYMeOHcyT/qOPPkIqlUJnZydeeeUVhEIhfPDBB+xETaVSYX5+HufPn0c8Hsfg4CCcTifcbnfBghL7Vk492ogqSPdulJ7l3o28/1kYhZxEJGfaKPY+Oelsvffy9/HvInccilktKytjCS7C4TDm5+dZWNt69NwzKrKd+Hw+lnBByjZCUhBJIxcuXMD9+/fx0ksvoaurC8FgEBcuXMDk5CSsViuOHDmC6upqfO9732NSmsPhwLe//W24XC5JFUJq8fBE0tDs7Cw++OADjIyM4MmTJ/jyl7+MmpoafPzxx5idnWXR+qdPn8bt27fR29sLm82GTz/9FHV1dfB6veyk8O7du6iqqkJlZSWuXr0Ks9kMr9eLmzdv4vjx47hx4wYztl+5cgWVlZW4efMmgsEg6uvrcefOHbS2tmJlZQXj4+Po7OzEo0eP8OTJE7hcLjx58gQ7duzA0NAQbty4gZaWFrS1tWHTpk24fPkygsEgcrkcO5KmsJNkMom7d++ioaEB5eXluHbtGnp6elBZWYmKigp4vV4mUd6+fRsWiwWvvvoqzpw5g4cPH+LQoUNMpRYZlpQKJNXXNC7/p/SsEshG1K1ntS3JSXPr2aHWo2JSolx5vNoeDoehVCoZaiv5DJK5YaOB8M+9w2d5eTncbjfKy8sLcMeBpzs3n1/z9zl//jwuX76MTCaDM2fOYHBwEA6HA0ePHoXNZsP27dvR1tbGEhx86Utfwre//W3k83nMzMww+9TExERBEC7/Lno/z9Dy+bWI/Bs3biAQCOCVV16BxWLBrVu30Nvbi/n5eZw+fRrHjh3D+Pg4RkdH8fjxY3R2duL06dPQaDTo7e3FvXv3UFpaildffRXV1dV48OABnjx5AgB4+eWXceDAAczOzmJwcBBzc3M4cOAAXnrpJaTTaQwNDWF0dBSdnZ146aWXUFpair6+PgwODqK5uRmHDx9Ge3s7RkdHMTQ0hPLycuzevRvt7e1sh9y/fz+mpqaYL5nH40FNTQ1aWlqYSunz+ZBMJtHd3Y2enh7Y7XYEAgEYDAa0tLQwgMNcbi21VX19Perq6tDY2IhgMPhU+jK5TYBnYFK0nhQmXltvs5EjKTsYj76x3jMbqd9GfhPrIGXqkHq/lLQl9T66RhmRACAQCDANZXR0FJOTk8jn80wr2Qg994zK6/UiFAoxwzAZxaXSCikUCgSDQfT19eFLX/oSfvd3fxelpaWYmpqCUqlEZWUlSkpKUFZWVoCn43A4UF9fj/LycubJ7vV6cebMGUxNTQF4eqClVEIyQgaDQezcuRMHDx7Enj17GJyIy+VCbW0t2traoNVqGbbPpk2bUFFRgZqaGuav1NHRAZfLhaamJmZLqq6uhsPhQE1NDTQaDQu2pjAct9uNaDQKm82G6upqWK1WVFVVIRqNIplMoqKiAkajEVVVVez42ePxQKfToaKigoHi6fV6zM7OMgmWdlfy0yJGrtPpYLPZYDQaUVpaypgYGfDpPqPRCJvNxtJX0YYjZRuUCosSF+JGbUVSYyXeI7eA+bqIz4kS4EbqtF49eVpP4lnvmpQaXexZKRuZUqlkITQejwcqlQpms5lhn8Xj8WeKinjuVT8+bIM/9hYzqPCDY7VaUVlZCavVirKyMrZgaFHQ6RpvlCfbEn3XarVoa2tj2WI3omrQPdlsFtPT07hy5QomJiaQTCZZmipK5GA0GlkIAuFZ6XQ6pNNpqNVqFuJjNpsZ/g8xEoVCwU4+yUhPz1OoEO32+Xye5TbkF2cul0MymWThSfzENhgM2LdvHzKZDB4+fIgtW7agoqKCYXIR44rFYsyGGIvFnnK34J0BSYoiGBuqA09yEpUUs5BSy8VxWI94hvMs9p9idZUjqfeI6q7UtWdV/URm/qzSI7WX5kcwGGSHPCqVim3mkUgE0Wh0w3393DMqOmEg0ZOIBkD05iVUwr/927+F2WyG3+/H9u3bWefTs3Q/6d7ECOm6zWbDvn37GMMQn+OJXzi5XA7pdBpLS0ssOWhJSQkymQxLN0Tpv8nIT2m8/H4/S+lN6cSXlpYQi8VgMBjg8/mQSqWwvLyMeDwOlUqFYDCI1dVVpNNp+P1+OJ1OJBIJLC0tobKyEisrK7Barcjn81hYWEA8Hsfs7CyTdGZmZrC6uorFxUWk02kkk0ksLS2ho6MDKpUK7733HoPyoJNQkqYI+0ulUiEUCjH3DlEdoaDtlpYWjI2NMabH+1nxDEGUBtazA0lJ1kTrncBthOGsZ9vZKIOSUxN/EWZCZcvVrZi0JieditIV5fUjKZ3CaHK5HPR6PQug3wg994zKYrHA6/Wy4GSp0w2eCeVyORgMBlRXV8PtduPhw4fI5/NsYfCiO0kHpIpkMhmW18/n8+Hhw4fo6OhAeXn5U/WS2mWpHjqdDvv27UN3dzeGhoYwNDQEs9mM4eFhTE9PIxgMIpVKobS0FCMjIxgaGmKZjFtbWwEAY2NjDJivrKwMNTU1uHjxIu7du4epqSmYTCbU1dVhcHAQ9+7dY5Aczc3NWFlZQV9fH8MQ2r59OwKBAG7dusWkvJ6eHpSWlqK/vx+ffvopFhYWUFZWBp/Ph9u3b6OzsxPLy8usj8RsM5RQ4saNG4xZVVZWFtgPSfJqa2vDhx9+iJ/85CfIZDI4ePBggUQs+obx/6VoI2qNnN2mWJlyUpkUE92I5CLFPKTKeRbmVYwxiRIa794hVe9i9j1KkVZfX4+5uTkoFGvOnplMhpkEeA1hPXruGdX8/DxisRiDlwAKs4aIEyybzaK0tBTHjh1jdhOCE15ZWWGSSzgcRiwWg9/vx9TUFBYWFjA1NYXNmzcDWHOLGBkZQUVFBWNUUpNZVKfI+93hcKCkpIQNcmtrK4aGhvCTn/wEALBt2za0tbXB5/Phs88+Q19fH0pLS7Fp0yY4HA48fvwY3//+9+FyuVhQdV9fHz755BPo9Xq88MILqK+vx7Zt23D58mUkEgkcOHAAlZWV6OnpwXvvvYebN2+is7MTTU1NiEajmJ6eRl9fH9xuN7q6umC1WtHd3Y179+7B5XJhx44dMBgM0Ov1ePDgARQKBXbv3s1cCVwuFzupU6vV2L59O1ZXV5FMJhlkSi6Xg91ux6ZNm5iE2tLSglQqhfn5eVRVVaG2tlaSyUt9lutrKRIZQDFGtRFD90YlOzmSekZUj/n7iqmiUsyGfi8mJUoZ3UUmJcfEVldX4ff7maSczWZRV1eHWCzGNJeZmZkN9cVzz6j0ej1Td6QcPfmOp8lGdpxUKsVCZ6ampnD58mXMzc0hHo+z3WB5eRkXL16ETqdjsXwA4HA48OKLL8LtdktOLpF4VbK+vh5utxuZTAZOpxOtra1wuVw4fvw47t+/z4JhjUYjtm/fzhw6m5ubYbFYoNPp8Oqrr8Lv96O8vBxVVVVQKBQ4duwYA+ZraGiAWq3Gtm3b4PF4AIBhVLW0tOCtt95CMpmE0+mETqeDVqvFqVOnEIlEYDQa2YnO0aNHsXv3boY/pFAo8Prrr7M4L+qnfD6PxsZGJinlcjmUlpbiK1/5CrLZLDv9yeVyLC6RpCadToctW7agu7u7QILlJTUpvzjq12J9LydhyOFViffy7+PnFj+XpJ6VU+mKMQ5RE5Arkz6L805OXZNqv9R7ipUhpaWQaYJso3RYQpoN2XU3Qs99Svc333yT4Tm99dZbLAiSn+zAF1JWNBrFwsICamtroVKpWN4xk8mE5eVl1vFlZWVQq9Xw+/0A1jqfFiVNNoKp5UlkiiLl82u+JmSYpxAVGnjeY52vt2hY5n+Xm0R8GI5Umfyio7rTf/5wge9HkfHTQiVJkd4p1olsfby0y1+nLEJ8mJFop5JbsMVUPfGaGOwsJX3QmFCIFPUhJeig5AYAsLq6ilQqBavVCpPJ9BQTFeu4UUYltqGYSignzRWzUfHvk5OgRClNrN+dO3fw3/7bf2PY6Y2NjRgYGEAymYRGo4FWq0VzczN++MMf/jKlOwG22Ww2hvDJ7zbiYqQOpclHp35KpRIWi4UtElowZWVlbJIChcfP9NxGTqd4IoA/qSBeqj+VQR7wItFC4k/v+InF2+T4PpCyJ/GxfXw9+Hbwkg0xVL58CjsSJdpiGWnE+4ihUvnJZJJlCeJBEQH5hKU8o85kMlhZWYHFYoFarcbIyAhisRhWV1eh0+mwfft2eL1e9Pf3I5lMoq2tjS223t5eJJNJWCwWnDx5EkajESMjIwwV9siRI5iZmcG1a9cQi8Wg1+vxxhtvsI1SjnE8K4nB13JS17O8S071o2tSqqb4rEKhgN1ux+bNmzE+Ps5wqCwWC9vsPR4PSkpKNtTO555RBQIBFndGbgVEvHhOKa6kOl9KTCc1kogWL78Q+TAaud1N3NH5+6heCsUXKc3FhRyLxQri/kgSoyDeZDIJg8GATCaDaDTKEEotFgtTt6TaK9rtqK38Z37Ri3GJPIOj67zkAaydsI6NjSEcDqO7u5vZpHhmSN/5oHAag8ePH8NgMCCVSjG1kMZCagHxizmXy2FkZAQ/+9nPcOTIEWzatAlDQ0NIJpOYnZ1FPB5HWVkZrl27xpjs2bNncerUKVy9ehW1tbUoKyvD5cuX0dnZCY1GgzNnzsDj8aCjowMGgwGff/45amtrsW3bNrzzzjvo6+tjPkX/UCRKgVLjR/fx13+R90iRuKnx90ejUQSDQWi1WqjVaoTDYbhcLmZOeRYo4ueeUVmt1gI1BXg6mSgtAupoQlvgdwFeveDVF1HszufXTv+Wl5eRz+eh1+uZMRl42uFPJPp9bGwMS0tL2LFjB1vgExMTePDgAex2O/bt24dAIICzZ88CAMP9OXz4MC5duoTx8XFWlxdeeAGRSAS9vb3Ml2nv3r3YunVrQV1EpspLWVR3vt945imlzlCZUpTNZtHb24tPPvkEoVAICwsLOHr0KAP449VTcQHk82swMjMzM0gkEgDA4HSy2Syi0SjUajUz4vJEZfb19eHDDz/EwsICUqkUnE4nTp06BbVajU8++QQ+nw86nQ6zs7M4cuQIPB4P3n//fXi9XiiVSnR3d6OkpATLy8sIBAKYmJiAXq/H4cOHmZ1SpVKhqakJVVVVePPNN5FOp586yFmP1pO+pdRd/vtGn5diZFJSmrjJ0njImTEIPYHCZvjx3Ijtlui5Z1Q2m41BENOOTcQzF5JK/H4/zpw5g9nZWeTzawk7v/rVr8Lj8TzVsTTZeAwqAIhEIvj000+h1+vR3NwMt9stucvxdeDLnJ2dxbvvvgu1Wo3Ozk7YbDYEg0GcO3eOZZ4l0LyZmRl0dnYyr99cLofZ2Vk0NTVBr9fj0qVLmJ2dRTQahclkwubNm6FWq1FRUVFQJ57pStk8qG7PYtIU1WqeQqEQPv30UzgcDmzatAkPHjxAU1MT7HY7S8ZhsViwadMmLC0tYW5ujtk2KPZwZGQEfr8fmUwGNpsNL774IhQKBT755BO43W7s27evAEoGWGNUi4uLuHDhAtxuNywWCxs/k8kEv9+Pubk5dHV1sdyOt27dgtFohEajgcfjQTqdxu3bt+F0OjE/Pw+Hw4FAIIBoNIpbt27BZrOhq6urIJkIQQfxfUKMX1St+P7bSB9LfV9vI5S7T0oSlWKq60nhSuVaAl273c7CpcrKyrCysoLZ2VkYjUa43W5UV1ev20bgHwGjmp+fx9LSEmpra5mfE/C0yEqdPDMzg7m5ORw/fhxarRafffYZFhYW4HA4GEoCAJZ5mNRKEudzuRzGxsYYqkIsFkNdXR1DVQCkTxr5axaLBXV1dVhcXASwZjS+c+cOEokE/uk//ae4c+cO7t69i/b2dtjtdrbAyQv94MGDcLlcuHjxIjtdI9x2heKLjM9A4aHCeotkIzYPUcWVWxAUnHr48GHmf7WysoJbt24hGAzCaDQiGAziyJEjGBgYwPz8PEpKSjA/P4/V1VX09PTAZrMhkUjAbDZj06ZNzCBPhmsaD1HVikQi8Hq97Jg8n89j69atsNvtGB0dhU6nQ2trK9v9tVot9Ho9VlZWkM/n0dHRgfHxcczNzTEoaAoPymQyuHXrFgCw005SNaUM/8/C+Nd7Rhy/jUptfNnFypVjqFJEWGtmsxk2m41FHphMJhiNRuTzeQQCgV+6JxARJC9hKgHyxnRSi/R6Perq6uDxeOB0OmE0GjEwMMCwzzUaDfbs2QOlUonLly/D6/VCrVZj69atqK6uxueff87cIXK5HBYWFgrwn/j3ilJNPp+Hw+FAa2srotEoU1W8Xi9qa2tRXV2NaDSKixcvIpFIYHl5GR999BEUCgWsViteffVVdHR04MqVK7h37x42bdqETZs2YW5uDn19fQiFQggGg5ifn8epU6cKPIPlJusvYpRdz86Xz6+B6t2/fx9WqxU+nw+VlZWIRCJobm5GV1cXzp07h5WVFaTTaVRUVGDv3r2MkanVauj1elZ//mT00KFDUCgUDGGSlwzJ/WH37t2IRCIsLx8x63Q6DZfLBYfDweLQjhw5goqKCnzwwQeIxWI4evQoDhw4gLGxMbz77rsM+nnnzp1oaWnBlStXWDageDwOjUbDIgRqamokTzY30ofFpKViG0uxcoqV+awStFgGRUak02kYjUZkMhlYLBY0NjYiHo+z6IuN0HPPqFKpFAs7yWQyDFlTPMkCwFAJQ6EQ/uqv/gq7du1iIvy1a9cQj8dRVVWFvr4+5s8zNTWF7u5ujI2NYXJyEl1dXdizZw+CwSDy+Ty6u7tRU1NTID0VswEQ8SoBJU0tLS2FWq2GwWCAyWSC2WxGc3MzmpqaoFAo8Pnnn7OQm8rKSlRXV2NqagojIyMsVVF7ezsePXqEsbExpFKppxb6s5KcZEjXik102lUp9IYk1nv37rETuK6uLiwsLKCvr48ZX3ft2oWlpSUsLS1hcXERarUajx49Qm1tLfR6Pfr7+2EymdDc3CypupKPm1KpxLlz55hqRlIPMS2SNiORCFKpFLP5JZNJLC8v48GDB3C5XKivr8fS0hJ8Ph+CwSDi8TiLUPj8888BAP39/aiqqkJ1dbWs+iU1N8T607VnYSBin4u2Rrn7xPfzv0tdo9/oHpLayeZL2ZFpbRA80kbouWdUHo8HyWQSLperYCeTEmdzuRzq6urwta99DXfv3sW1a9cwPDyMAwcOMAwoHhecTrp4uOFwOMxOjbLZLLMpGY1G9r71iMqmwSSkgsXFRWSzWYZDXlZWhqqqKpSXlyMajWJ0dJTVqbm5GV//+tfxk5/8BF6vl3mNezwe+Hw+5vEuqggbWQByKmsxo7qUWmmxWHD8+HGUlpbi7NmzzAGwtbUVtbW1MBqNaGhowPj4OLZu3Yr29nbodDr8P+y9Z2xcWXYn/qucWcUqhmIx5yRKFKmc1VKru6fDTHvs9gTA9toLGPCXNdbehA1YA2sbux+8xn8D7AUWcByniZ271Wq1ciuTFEkx55wr56r/B/rcvnV536tSzywWq+kDEFV89d5N797fPefcE6qqqqDVauHz+RCPx+FyudDd3Q2z2YxUKoUnT57AYrGgsbFxT8YbIjKStVgszBBR5GxtNhucTic+/fRT5kNZVlaGoaEh3Lx5Ew6HA2fPnkVlZSVKSkrw+PFjLCwsIJFI4MiRI7Barfjwww/x2WefsdNA0U4r3zwQfVGVlOdKz8tI5Oxlz/Gcr5LeSjZ3+Hlht9tRXl4Ov9+PQCDAROGVlRWYzWYWpePOnTt5+/LcA9Xs7CxCoVDO8TaQu3uRHoNAoaqqCq2trVhcXMQ777zDAIKM+7q7u3H06FFEIhEsLS3h7t272NrawsGDBxEMBjExMYHt7W1otVqsr69jZ2dnD1DyJJsw/GTRaHZtUqampjA9PY3h4WFYrVYEAgEsLS3BYrEgFoshHo9ja2sLH3zwATo7O9nCjcfjePjwIQwGAw4ePIilpSXGvYiLphDAot9EG55894tKbaPRyERzylRC9ksUbjgWi8FgMKCxsRE9PT05BqqUkYdC1ZC4d+rUqT1Za8SxprGtrq5mesZMJsPyJqbTaVitVrz66qssBZnX60VtbS1cLhecTie8Xi87WTx16hQ7wDCZTCz332/8xm9Ap9OxjDWiuoFXQ4gbgPgp48rF+SPjzmTX1N5VIe+eylUT/bXaL9LUETdqt9tRUlICYFc0XF5eVm0P0XMPVDRZE4lEztGokthFituzZ88C+CI6gl6vR11dHZqbm7G1tQWDwYDa2lq89dZbSKfTuHfvHoLBICoqKnD27Fk2+Y8cOYK6ujpF/0LxxfPKVz7pQ1tbG4aGhvD9738fsVgML730EoxGI/r6+pguhax7x8bGMDAwwOyp6urqsL29jXv37mFsbAzRaJSlkieSTX7Z+PCkBPzi/7LJbbfb0dnZyfK91dbWIpPJwOFwwG63swWs1+tRU1OD4uLinI1Fq9Vi3759aGhoYGIwEWXj4e/liTcGbWpqYvfpdDr4fD6Ul5cz8HC73Th69CgDSLI6pxDVxMFaLBY0NDSwBUr9tlqte2zgSPTiAUs21mpil9L74v9/Fr2VrF4ZsBWix+TfE/na0iGWwWBg8cwoBn8h9NwDVUlJCQuJwk8W8SXTxNTr9Xj8+DHu3LmDbDbLQuMuLi5icHAQExMTbLA9Hg88Hg9T0M7NzSEWizGvcb1ej6qqKhYHS4lFFhd0JpNBSUkJOjo6GFDW1NTgtddew9TUFNxuNw4cOIBMJoMXX3wRoVAIRqMRRUVFaG1tRVVVFebm5thCq6urQyAQYCYJOp0OpaWlbIcvVIxQU+IqiQl8//h+OhwO9Pb2skVNgEGpycigVq/X4+jRo+wd8eXQzkx94BXqMrFJ9g7EZ/lkHMAXHgi80Sq/KHmXHiqXuHdqC32SHRGQ61IkZgfi+yiOcyHvRDb+hXC9fFl8e9QASxQT+d8ozhkdKuh0Ovj9fiwtLeV4QBRCzz1Q0SQzGo17Ui3Jdvrm5mZ861vfYidu5eXlLJwxJU/k9ST0bH19PaxWK1N6X7hwAQAYd6BGspdeUVGBsrIyBnJ6vR5tbW1oa2vLmTgHDx5k/aT+lZWVobS0NMfIrqioCB0dHTkL7Vkmv5puRG3npoUqXidPALpG91ksFsaB8H0S6xBBSFxY1FYqRzTw5f+n5wgcyYyFOHEqh8S3ZDKJZDKJaDQKi8UCk8mEnZ0d2Gw2Fhee3iUlpAXAQuksLCywA5L29nZm2vCsVCjX+6z6LKXyRKBXmhPUd71ej4aGBqRSKaysrMBkMsFqtTJTBZfL9VVyB6KtrS3EYjEWiVKG/vzLpCgINLlohy0tLUVpaWmO7x6/w3u9Xvh8PnaNj+xZiBc7T7RweZGBxFbeyZcHSh6AaLeOx+M5NkQyvQjfHhmp6SD476IrBF82uQKR+QfvL0ngwE96fnxItCKOhACEv1dpHPj7RkZGYLVaUVNTg3g8jnv37iGT2Q1SSEan/f392NraQjqdRlFREXp7e3Hjxg12eGG1WvH6668jHA4zi/rS0lKWZKOrq4tl9qFAgsPDwyxs9YEDB5BOp/Hxxx+joqICm5ubWFtbw8WLF3Pcu9Q2CiVS4s6V9Ff5iFdDqG1Sas9nMhkW5NHhcLC5QHrBeDz+VShiIo1Gg2g0io2NjRzlqhJrTaw78MXiEHdu2ulF7oO/ly+P5y74ukRxVNYWItLXEGCRI64S+PL30/NifbzoU8iOKmsjP87i//RHGXzoiN/tduPChQs5Pooyzkd8V3w7+X7zfeM3Dxqr8fFxloLrjTfegNVqxe3bt1FbW4tIJIKbN2/i9ddfx927d1FfX490Oo1r167B5XJhdnYWjY2NKC4uxo0bNzA8PIyJiQkkk0kcOHAAt27dQn9/PzMqrqqqQjQaZcakPT09OH78OIBd/czMzAwqKiqYGD84OIiTJ0/C4XBIx1PtXai9AxlgKb0rpWtKdRayeWWzWeZfSq5D2eyu7ZzdbmecJ2VMzkfPPVDV1NQgm82ytOYy4ncPYv3J2Zf38xN1JETJZBJGozEnEgA9TyInr59QcuSkskX2OpPJ4OHDh6irq4PX68XKygqePn2KU6dOsVA0VquVWfzyoKqmdOXb8Swke0ZpB6Yww0NDQyyo4J07d9DQ0ICWlhY2gUmfQWXwnCAf9VOj0TALe4qhThNf1Dvp9XosLy/j8uXL8Pl8MBgMuHLlCnp7e1FSUoJXX30VBoMBf/mXf4nt7W1YrVa89NJLMJvN8Pv9CAaDyGZ3LdEbGhqwvLzMfNfOnz+P9vZ2RKNR+P1+aLVaTE1NobGxEVNTU7Db7YhGo8yqPZPZDb/LJ+NsbGzExMREjnipJkbL3qF4n5Iu6cvQs9RD1/nndDodrFYrE5MdDgcsFgump6fZWstnz0X03APV7OwsNjY20NjYCCD3FIgGi1ecbmxs4PLlyxgaGoLNZsOlS5eYMhdAzv38C+G5KY1Gg0ePHsFms6G3tzdHPKGXw4te4u7Ht4t+GxgYQFFREaqrq7G1tYWJiQkcP34c6XSacQJdXV1IpVLMsJUWPHGBdJKo0Why0szzVKgOSu0esT+pVAolJSU4f/48HA4HdnZ22NH04uIiUqkULBYL2tvb4ff7MTIywoIWHjx4kPn6kUlFe3s7qqqqkEql8ODBA/h8PnR2du7Z0bVaLfx+PwwGAy5evAiDwYAf/ehHTJRbXl5mHLdGo0EsFsPIyAhTAGezuxEAbt26hbGxMSwuLrJAghRWhmK/19TUYGhoCIuLi9jc3ERdXR2i0SiuXLmCgYEBuN1uvPrqqzntIyCnDUWNq5WJcmrvQdRNqXFChZJYhqizEttgMBhQV1eHra0t5g5GOshQKMSy1BRCzz1QETDQwgX2ijz8bnbv3j2MjIzg5MmTmJ+fx/Xr19HU1MSUfiJXxU8MmnSRSASzs7MsRx2FtYhEIkwnQwaEdCJC7gW8pTiVS+Lo6uoqotEoZmdnGUeRTqexuLiIyspKNuEpdxpFVNi/fz/W1tYwODjI0nl1d3fnOIQWqr94lsnOc4SZTIalfieguHLlCra3t2EymbCyssLCDc/Pz6O6uhqrq6uorq7G7du3sbm5ifr6ekxMTGB9fR1vvvkm40zIkFBsHz92k5OTMBqNTBHu9/vx3nvvAQCLWBqPx3H16lXmcuX1emE2mzE7O4sHDx6gubkZtbW1mJ+fZ+YupFtqaGhAf38/7t69C41GA5/Ph7W1NVRXV2Pfvn0sRDPNE9pEjEbjnlPDn2bM1d6DErCI94rPid/V2iWqULa3txGNRpmOOJPJoKqqioWgpsCU+ei5B6pkMsmSFCgFaSOxQ6vdDcZGadD9fj+ePHmCbDaLx48fM+M0o9GIY8eOYX19Hbdv32bZfy9cuACv14uPPvoIg4ODMBgMsNlsOHLkCB48eICRkREWI+r48eNwOBy4desWs0Jvbm7GCy+8wNJb8cpip9OJsbExdHV1YW5uDjU1NTAajfD7/YwjAIC1tTW899570Gp3cw6mUik0NDQgnU4zmxbyZi8vLy84FCygvpur/UZK1atXr2J7exvV1dVwuVwsnnZxcTETq3i9BTlZ08FCZWVlTnwxjUaDzs5OFiFB1AeSsnxnZwfDw8Msl2EymURZWRnOnj0Lt9sNs9mM7e1tuFwunD59GhUVFQzU3G432tvb8eTJE5hMJrhcLuYpQBwq+Qd6PB4MDQ2hvb0dLpcLWq0W1dXVOHbsWI5OM5lMIhaLsaxC1G5xIxXHV41k3I74u1LZSiRyZfnaIqszHA6zvJoajYYd8BBnFQ6HC2rLcw9UFAecJhgf5UBUJKdSKWSzu75gtNDPnj2L+fl5XL58GV6vFyaTCePj43A4HBgbG8P6+jra2toQiUSQTqdZPPKpqSk4nU7U1tayDLGNjY1oaWlBOByGw+HA/fv34Xa7cfbsWUxNTWF4eJiltuInlE6nQ2trK27fvo2JiQlEIhFUV1ez/H10ogLsWnKHQiFUVFSwuEgGgwEbGxtM5IrH4+wIHSjcCLAQEVB2SJFKpVjyh08++QR1dXXM/mxzcxOxWAw1NTVoaGiAx+NBMpnE5uYmFhYWmMJ9bW0NN27cgEajwdGjR1kOwuHhYRQVFeVET+D7lM3uur28/vrrLPN1NrsbJ6y8vBxFRUWMy6MQ0xRDfmNjAxqNBuXl5TCbzfjoo4+wuLiIdDqNW7duQafTYXx8HFVVVTCZTKirq8Pg4CCqq6tZ9Ibp6Wl8/vnn0Gq1KC0tZd4M165dg9/vh06nY+3+MvpCItkhxJcR9/LNAZ5EMVNsu8FgYKJdKBQCsBsfbnp6mpl2iIcISvTcA9XU1FSOZSzwxUmczMaH/oit12g0CIVC8Hq9eO2112AymfDuu+8yfcnOzg6ePn0Ks9nMQuPu27cPExMTqKioQHt7O3NzOXjwYI6I1t/fj/LycmaVTcHu+PbQZ2VlJbRaLYuNxGe24RXJBAgzMzN4+vQp1tfXGbgWFRWhqakJQ0NDrA7xhJI+Rf1ZPpLtprxez2QyoaGhAV1dXZienkZzczOLLeX1elmMrVAohM7OTthsNmYaYDKZcOzYMZw4cYJZr1OyAIpj39zcvCegIdXtcDhQUlLCjHFtNtue0yaDwQCr1Zpj2KnX6+FwOGAwGNDU1ITR0VGEQiF0dHTg6tWruHLlCiwWC3MKb2pqynFCr6iowPLyMkZHR5HNZlFbW8tS25vNZthsNjQ1NeXoafKdzsnoWcDoWYGLV5Pwz4vzRjwEAnbH3uPxoLy8HBsbG8zw2mq1stPArziqfyTyYifHU2DvMSoRiWDkmxUOh7G0tIRgMAiz2QyLxQKDwcCyspw+fRrFxcUIh8MYGRnB48eP2c7Ol8lHNiRwJO4tm82yUxFqG6/sp0lQXFwMn8+HGzdu4OLFiywQPiVW5Y0MS0tLUV9fD7/fjytXriAUCiGZTKKkpITZ+VBdIkiJpHY9nwjA60XotK6npwfT09Pw+/2w2+3o7+9nMaAaGxsxNzeH/v5+GAwGxONxNDY2IhwOo6ioiHG6pPMyGo04cuQIe1+y09LS0lK0tLQwQO/o6IDNZkNFRQUsFgvjrB0OB44cOZLjimOz2dDd3c3i7b/wwgvQaDQM8MlMhdJ8ud1uvPjiiywz8L59+9Da2pqTLorsiMgYlw89VOiYyriXZ+XGnkV8k53MKYmWYtkrKytYXV2FwWBg0XbJJSqRSGB1dbWg9j73QEUncnwYWEC+c9Hvg4ODKCkpweTkJDY2NtDU1ISVlRU8fvwYwG6YYJfLhfn5eZhMJng8HqytrbFyiBuj3UKn0yEajeLGjRsoKirCxsYGs9e5d+8eC1lCp0myEyByzJ2YmEBTUxOb4Kurq1heXkZRURHi8TgCgQBu377NDBeNRiOqqqqQzWaZH2MikUBra6viBMy3aGTPyMqgsaioqMCpU6eYA/Lrr7+O4uJiVFVVYXl5GVqtloliR44cQXNzMxNrPR4PC+VCClq+XR6Ph4GUeDJLrkjEsWi1WuaqQ++FiBKy8u3WarXsWiaTYQcq2ewXETt5IhDjvQnocITXN/JuNTR2Yny0fONbKBWqnFfTPfLtp3tl1+k7745EelqDwcAiKGxvbzPdXKH03AOV0+lEMpnMmTAyokFraGjA06dP8dd//dcwmUx46aWX4PV6MTg4iBs3bjARoby8HGNjY0yMMpvNaGtrg8lkQiaTQWVlJVO4ulwu7N+/H6urqywiJSXSfPjwIeLxOBMTrVbrHitvand9fT2+/vWvM9ECAMv3V1xczELlvvbaa0gmk9Dr9czfsKWlBfv37wewuyicTmdOCnq+HiXFrBpwyRYT/dlsNuawq9PpWPsdDkdOFhLiHMkBmRZ2XV2dYhv4gxBaIHyiCZEjUNLliO46BHyiIztv3sJ7B/AeC2RBT5w077zMEw+sMps32ULO9y6+jI5LjTuTcXCFbGB0f1lZGYqKithJr8fjwdbWFgKBAOx2Owt/lI+e+7x+R48eRTabxfnz53Hu3LmcCSE7eqUjU41GA6vVCrvdDqPRiK2tLXa0bzQaUVxczKyPDQYDS8AJgJ02ZbNZZm9DOwid/vAhP/Kx9fzv/ILg7xMdcul+/jeZaES/04Lm9QtUhrjb03O8PkesQyxDyQqf7hOv814E1DbiinkxT6/X55yoEeDwYaOVSLboqS6ZkzD/m6gL498dH2mBwE90fRLftWwMZPZ2akCl9Jv4Xvh7ZEbMoq5JTW8m3ktlkkrjs88+Y+YlBFSJRIIFQYxGoxgeHv4qrx+BRiwWy9nVxEVApNfrWUojfvKUlZXtWWx2uz3Hsppne+nYn3Z4mYGlOOGVUnaJgMaTuFB4bozK50FGZN+pXF5cErkOfjLy91NfeZCi/ykeFG+/RkDD2w6R2QidygJfxDT3er2wWCxYW1tDMBhk4OPz+aDX67G0tIR4PM44RLvdjqdPn7I2NzY2MhFbRiKo8xuA6JokisRKYhA/t3gOTeTyxPEVE8DyYq5YJ/+s0nyQkdhuWTsKASXZ/7I5ms1msbW1hbm5ORY2OpvNwufzobi4GLFYjOlL89FzD1SNjY1YXl5mCk6ZM67IsfA7Hi93i7I4P8FkugUxB5646HnXHAIpCnRHOhniyKg8UvgXEkuKyiZLYDKq1Ol0LB7V8vIyO4ZvbW3NEQeHhoZQVFSE+vp6pqOjyKIUUfPu3buYmZlh+es0Gg3GxsbQ19cHg8GAl156CS6XC9PT08zf72tf+xqam5uxs7OD999/HxaLBd/4xjeg1+uxubmJf/iHf8Di4iIaGhrw1ltv4datW8wy32q14sKFC4jH43jw4AGcTieWlpZgNBrR0dGBwcFBFpFA5HpE4rkwfpHmAwX+/Ysgzo+/+L+4qdD7CYVCcDqdOe1Ra3s+ETzfM+I8FNss45IKBUDxuslkQiKRYJJHJpNh3gI03wuh5x6oFhcXWcgW2WQTd0QyCKRdn2yw6Hde7OF3XhKDlMKS8Nc0ml0/tNnZWTx+/JhxH11dXTCbzfjkk09gNBqRSCTQ1dWFnp4exGIx3LhxA0ajkZ12iRwBtY9fRNSuDz/8EOPj4ywl1GuvvQabzYYPP/wQWq0W29vbOHnyJAtP09fXhx/+8Ic4ffo0SktLceXKFaa0v3PnDqxWKxwOBz744ANYLBYMDw/D7XbD5XLh008/hcFgwMrKCsrLy3H48GFcv34d8XicRQ+ora1lyRVKS0vZZtDX14ft7W0cPnwYd+/exdDQEGKxGPbv388MJ0tKSjA3N4fDhw+juLgY77zzDtxuN0KhEHw+H06dOsXi39PY8OPPj49MHygTY/l5o0QiSIjvRvxO829sbAxmsxkdHR3sBFNNuf5lSFaO+L9szuYjEYTpO4FtdXU1WlpasLy8DL/fD6vVyk77KK17IfTcAxXJyqS0U+M+UqkU882itNPd3d148803mZmDqKugMnhdDa9g5V8+L1Ilk0mk02ns7OxgYGAABw4cgNFoRCQSwdDQEA4dOgQAePfdd1l22adPnzLg7OzsZMZygUAAZrOZvXS+HRrNrg/bxMQETpw4gYaGBnz00UdYWFiA0+lEVVUVTp8+jUePHmF4eBg9PT2YnJzERx99hGAwCI1Gw8Ir9/b2oqurCxMTE1hcXMT6+jrKy8vx1ltv4Xvf+x4ePnwIn8+HWCyGb37zmxgYGMDAwABzkfmlX/olAMBf/dVfMY7pxIkTmJ2dZeYjT58+RWdnJy5duoT19XXMzMwgGo1ic3MT9+7dQzqdRm9vL2pqahCLxfDJJ5/A7/fj0qVLzAF5cnISmUwGZ86cwYkTJ3K4Wp5LlnFQItcsctvi5ia7lycZ98Vvdnq9HhUVFbh58yaLFy8aIysBYKEkE0/F9snaLatLCfRl0kY2m2W5A6xWK9vI6aQ2EokgkUgU1IfnHqiSySSCwSDC4fAe50/ZSzty5AhKS0tx48YNXLhwAQ0NDWyCkq0TGYImk0mkUik2ic1mM/PbSyaTyGR285gRgBB40GdDQwMLunb+/HnU1dVhdnYW5eXlOHfuHDQaDf7sz/4M6+vrGBwcxNTUFMve29TUhN7eXqawrKqqQnd3t3QhEmfo8XhQVlbGYlh3d3ez3Gtutxt6vR4TExO4fPkyqqqqmN2L2WxGUVERhoeHsbW1Ba1WC7fbjcnJSXR3d8PtdjMRm/zbSktL0dDQgNHRUWxsbMDhcDA7KNJPALsJHkRfPUrsUF1djc3NTSYSWiwWbGxsIBaL4a233kI2m8XOzg4CgQD8fj/MZjNaW1tx8OBB9PX1YXJyEkePHmVxsPJxEOLv/GEBf7/SIpYteLXoAPSOfD4fOjo6MDw8jJKSEsZhFkIyri0fuPDflcRTHiCVylUifhwjkQjm5+eZqAfs+laazWbEYrGvfP2IGhsbWRIBngsiEnesqqoqaDQaDA4Oora2FuXl5RgeHmYW7olEAtXV1Th58iTu3buHwcFBpNNpOJ1OlixzcnKS2U61t7fj3LlzObom8eWTMSm1xW63Mxscyojc1NSEubk5BINBVFdXM8v0bDbLRCqexBC62WwWn376KR4+fIiRkRH09vayEDYDAwO4fv06yxm4s7MDi8XCTj9bWlqQze76bVGePcpX53K5mKvE2toakskksxy3WCxMhLZarcw5mwLJiY7XJBITR0FcLCXTaG5uxsDAAPr7+5FMJuF0OvHqq6/i448/xtOnT/H666+jp6eHRdp88uSJoi4GAIsyAeSeVJFbC40fRVKgOcRvdoXoskSgE3/TaDRoa2tDOp3G3NwcXC4XMxpW06/RZz6uiL+Pn/P5SCb+ykRIpbJo8zaZTOwwxGQyIRAIMNOdQjmqwoLB/D9M09PTLCsvf/IiG2z6oxAjtBOPj4/j0aNH7ISKXCkoI6/BYMDTp0/x6NEjTE9PIx6Po6urCxUVFRgbG2OuA1SPeKrGn4yRvooWsU6ng8lkgs/nQ0lJCYqKilgWFI1m93Tx7NmzTL8hKmGJq7tw4QLq6+sZiAC7yvmxsTFcvnwZTqcT586dQ11dHfbt25djSLmzs4NYLIbz58/jjTfegM/nQyAQYOBFudqoTjLo297eRiqVgtFoRDAYZJxtIBBgi4s/pKB3s7y8jGAwiJWVFXai5/F4WCwnjUaDzc1NbG9vo6KiAl1dXchms5ifn8f09DQz8KVFEA6H8eDBAxZNkvr09ttvo6+vj52uRaNRfPrppyz6J72P+/fv4/Lly4hGo9I2qymd+XklEg8cRqMRnZ2dKC8vZ/Gp1OoRy3gWPVa++a90z7PWo9XuhvKurq5mWXlI3I1Go0gkEl/pqIgInMRjd57EnSab3c0ewgNId3c3i2nk9/sBAENDQxgeHmYcBsVT7+3txbFjxzA6Oopr164xjkbc/QgU+TYQUPH6ptXVVeZqkk6nEQgE0NbWhv379yOdTmNjYwMAmK8a6czI1EGv1+PgwYPo7u5GX18fBgcH4fF4MDs7i08++YTF3fL5fEin06irq0Mmk8Hf//3fs6zBlBCCog1oNLuZZMbHx+Hz+TA7O4vKykpYrVY8evQIExMTmJiYYAk6h4aG8OTJE2aiQIEMeVHVaDTC5/NheHgYwO5ByLFjx3Dv3j34/X6cOHGCRddcWlrCjRs30NzczDhYv9+Pjz/+GMPDw1hdXWV2OTs7O7h58yaOHTuGyspKJrbPzs7C6XSy8U+lUlhaWsLOzg56enpgNpvZeK+urrIwyqI5hhop6bR4oOZt68iRnN69jGPLpxSXzW+1Z5QOfpT0ufkOFMQyaV0UFRXlSAyZTIapAPLRcw9UFouF6aeUlJ50jYwJSbHLT8by8nLGjdhsNoyPj2NjYwOXLl2C1WrFjRs3mLhGp02JRILtIqKCVGTXCVBJzKB02GQkR87NiUSCRfqk6Jk3b97E/v37WbZfqoc36PT7/ZiYmMD169dRXl6OhoYG3Lt3DwsLCzh48CB2dnYwPz+P8vJyJg5R5EybzQadTodbt27BZrNhdXUVhw8fRlVVFd5++20WFK2jowMWiwWjo6P45JNPoNXuplevra1FY2Mjbt++DQA4cuQIPB4P4whtNhszCzl48CAWFhbw5MkT1NTUYN++fdDr9bh+/TquXLmCbDaLAwcOoKamBmtra1hYWIDNZkNnZyeLxR0MBlFZWYm2tjYYjUa4XC6cPHkyx6K/uLgYv/iLv4iioiIGFA6HAy+//DI0Gg3bpAwGA8vhSJE6lZKa0pzhv8s4FfG7aO+mpLTn56tYvhqIqIl5SiBFJDsBVeMgxd8TiQSmpqZyQrtQ1NN4PK7YLpGee6AqKyvDzs4OMzZTIl5U4qN18hEx+R0uHo+zYHcOhwM2m40p2UVAJGU7sfI02WdnZ/Hw4UPMzc3h3r17OH78OPx+P2ZnZ/H+++9jbW0NRqMRJSUlzBcuk8mwiAMajQZmsxmNjY3MFUUEReIUHj9+jIcPH8LlcuGFF15gMZdMJhOmp6extraGjo4OeDweBlTFxcWw2+0oLi7GiRMn2GnoyZMn0draCp1Oh9OnT2NpaQkNDQ0swsOFCxcwPz8Pp9OJ5uZmmEwmnDt3DrW1tTAajaivrwewC86U8JPqLC8vx5tvvolQKITi4mI4nU4cOnQI9fX1rF8ulws2mw0lJSXMn5EWwSuvvMLGm9f5nTp1ir1fYDemGPnx8f6DxNHwAECxpkRgkZGogFb6XUm3xdchC1sje0ZWvjivn4VkwKcETrLr/BwkfWE4HEY4HIbJZGIx1PhAAfnouQeqiYmJHHsa2dEvP3lEg0+yKidfQbq3uLgYVquVcQ7JZBIdHR0AwEDRYrGgpKQkJ8mCRvNFJND19XVsbm6itLQU0WiUpSdvampiANHc3AyPxwOj0YgzZ84gm80yuy5SxJ86dSoneBxPBIrd3d0sSQGl8Dp+/DjLqExhR6jtGo0Ghw4dYiDd3d3NnKFNJhNzG+KP/2nM6uvrUVdXl2MT5HK50NPTs2chib59Gs1uLkI+oqpOp2MgzWfmETML8UQiNI0TEf+eeTFODUB4S3G1UzyxLp7UdD48SBHxm2Ihiu8vQ7J6f5q6ZNKKw+HAvn37WGYeEvFJVZJvPImee1+/Q4cOQavV4hvf+AZL2gnszQBDn1qtFjs7O9jY2GCLbXl5GU6nk6XAIova9fV1BINB5m9WUlKCZDLJcr3F43GEw2F2ygV8MTFpAfOOq6TwJ+U7H76EX0i0YMVIAkSiDoQ4DJmClu7nicaFBwV+jESRQ7S+5wGf5zCoDUCue49YN++aw4MNf5JJz/EhdXh3JlEXKBO5+LrE5KL8iSlvgMmXIzMi5sdffB/idX5OyN6HEojJlmwh+jI1UqtLbLPsnSnR5OQk/r//7/9jRtcAWDQLv9+PcDiM+/fvf+XrxzsIy/QERPxkdjqdTMlK8YN4sKBJXV5eDq/XyxYHX1YmsxsviRcHqW6+LGLveZGCssmIi4BfYPxuRMBA3/nJRW4LSv0Vr8naCCDHDokAhO4hNwi6RnZk5NdHIKXVahGJRNjJ3fb2ds67oazWGxsbTKSjqKoimPBAnM1mc7IO82Mmc+rlx4L3LKB76Dr/u0wEKmSPfxbdjkiyDeL/FD0rv1Jo37VaLZsf9D0QCLDIHrzZjho990Dl9XqRSqUYWivJ9aKNFS+i8buIbNLQ4hTtZXhjULouq4svU+T4xEUm7vwyAAqHw9BoNDkgsb29zbg10v3IODKRawC+MGOgpJpFRUXo6enB7Owsnjx5wkD51KlTcLlcGBkZQX9/P4qLi/HSSy+xybizs4PLly9j3759KC0txdtvv82SLYRCIXzjG9/A0tISHj16BI1m1yKebKNE/0vxHYhcWL7FLdPlyMZUHItCQEPcEMUyeMW5jJORAaOaSClyjoWQbLMW26/Wn0KIxLyysjIsLCzkpHanWG28z6oaPfdAtbq6yvKpEQio6RoosScA5hzM79IAchYEiQZ8WioS4Uh8I+tbj8eTw/HwoCXbbXlxDdiN4Z1MJlFRUcFMHvgJTWLru+++yzLVHDlyBAcPHsSf/umfsvsqKyvxjW98g8UtpzrFxUH6uaWlJbz99ttwOBwwmUwYHR2F2WzGzZs3kUwm4fV6MTQ0xGyBPv74Y5hMJjx9+hRVVVU4ePAgNjY28JOf/AQPHjxAaWkpKioq0NzcDKfTiYmJCdy4cQOJRAJPnjxBd3c3Wlpa8Omnn2J+fj7H4l4kcbGL4ig/pkqLXgQ+XoRV2xBkzyr9rtRuJVISt5XEykIARLYpKfVLrDPfPbL2Z7NZdtiTyWSwurrKOOVsNsuMPguh597gM5vNIhQK5dgy0XV+gAlQPv30UxZn6vbt25ibm5NOfCqDxB0CKF6fQWLd6OgoRkZGcia/bPcEwJ7jAZLEpqdPn+Lx48fIZDIsbIzIAdlsNhw4cADZbBb79u3DoUOHYLPZkM1msX//fpw8eRIzMzMYHx8HsMv1zc3NIRKJ5Jgz8OJdJBKBwWDAG2+8gW984xsoLS2F3+9HJBLBpUuX8N3vfhe9vb2IRCJ4/PgxLBYLvv71r6O9vR39/f1YW1vDhx9+iMXFReZz6XA4cOLECezbtw/JZBK1tbVMx+fxeFBdXQ2fz7dHxya+N37cRPFY9pv4f6F/svpkJIp6MiDgNyYRFGXgyM+VUCiUY80tApnS/FaqSySRe1S6T3a/rI5IJILJyUksLCwgm82yYHlerxeVlZUoKSlRLJun556jKi4uZs61sl2Q/06KPa/Xi6KiIly9ehVf//rXc9xQADAAEk+O+N2BrItNJhM2NzeRTqfh9/uRzWaZcj0YDCKTybAUQm63mx3jkiEcWaPPzMxgcnISkUiEhSPmuTH6bjKZ0NnZidu3b6OpqQkVFRWIRqNwuVxob29Hc3MzpqamWCC/7e1t/OhHP8L58+fR1dW1BxRIx5dIJBAKhRCLxZgOKp1OY35+HhaLBevr63A6nVhfX0dNTQ3zmn/8+DGGhobw9OlTtLW1seiOZAQ4Pz+PhYUFnDhxAk6nk2V7efLkCSYnJ5mTbqE6FCURXYnDkemelK7lW9gy7kpp3gHImS+yjVBWTigUgt/vZ6YgsnaotbdQEjk4Gcet1F6+X2SXSCmz9Ho9E/dSqZRirDCRnnugAsCO4/kJI4IUvyDv3r0Lo9GIUCgEo9GI1dVVzM3NMQUxJRxYWVnB1tYWwuEwGhoasG/fPkxPT2NkZIQt5p6eHgSDQabjyWaz6OjoQG9vL27evImJiQm2aF966SUMDw9jcnKSxVzv6OjAuXPn8OjRIzx9+pRFgvD5fLDZbHt2/Gw2y04SCUyo3cT1kWhLHGFpaSkriyYZPxnJiZmy76yursJoNKKiogK3bt3CnTt34Pf7cfz4cWSzWWYhT36AFI/o6dOnCIVCCAaDOHr0KMrLy7G4uMgStVqtVpw4cQKjo6PQaDQMTAsRkXgSx0NN3yOWz/8vE33UdEZqoqmsDHpGrX/8vKXNbHNzk7lwyUhWp+weWdtFcBTvVwIrfmOj37PZLMvSs7Ozw9YKJe5IJBIFmyc890AVCATYwuSV2DSQ/KkPhXaZnZ2FVrubXTkcDuO9997D9vY2zGYzlpeX0dPTA6vVitu3b7Mg/0tLSzCbzbh16xYLn7KxsQG/349UKoWysjL09PRgdXUVQ0ND6OjoQFVVFba3t7GxsYHp6WkWPsXj8eDo0aMYHx/HwsICAOCFF15AIBBg7i5qsdVFhTLpmmgi0UkksJtn7eWXX2annFQG8IWC2ufz4Y033mBZmimSweuvv46NjQ2EQiF89NFHbHFQDjc6km5ubmamHbdu3WL59LLZXReikpIStpkcOHAAbW1tmJubYzZwSmK3kjjH38P3Q4kTyKenyXe/KH4rLXbx+Xzio/iZze4GUnS73cydRxwbJQBS6yP9nw/gZW1XAm56njZNi8WCoqIihMNh5t0Ri8X+74V5SaVS+I//8T/ir//6r7GysoKKigr82q/9Gv7dv/t3Oadfv/d7v4f/9b/+F7a3t3H06FH8j//xP9DZ2cnKicfj+N3f/V38zd/8DaLRKC5cuID/+T//J6qqqp6pPeLpmsjC0jXiQKqqqph+iAaSArKVl5cz2w+NRoOamhp87Wtfg81mw/b2Noulfu7cOfh8PnaysbCwAJ/Ph6NHj2J1dRVra2tYWVnB3bt3MTU1xQxGKWBfT08PWltbkcnsJugkcZGcoIn7kekPeBGQwIkmOHE3/ATf2tpCf38/9u/fz0wtiEjfRvn3tre3MTY2xhyjS0pKGGCnUinm1jI7O4vJyUlMTU2xbDOU3GFhYQFut5sZ4dL404YRjUYxPT3NEnySC42a0lW2wMTFVejOTffLyhbrEO9R45SUACQfieKURqNhwRPzgW+hnJrs3nztk4EXXy7//MzMDFZWVliEVgDMHS0ej+PJkyeqdQH/B4DqP//n/4w/+ZM/wZ//+Z+js7MTDx48wD/5J/8ETqcT/+yf/TMAwH/5L/8Ff/RHf4Q/+7M/Q0tLC/7Tf/pPePHFFzE6OsqCwf32b/823nnnHfzt3/4tPB4Pfud3fgevvfYaHj58uOcUTo0qKytZJEESdYhEFp9Ch5w7dw5arRZXrlxhOqTBwUFMT0/DaDSiubkZS0tLqKmpQUVFBbTa3USLy8vLzC0FQE7eOLIFop1wdXUVgUAAr732GsxmM65cucJENJLhE4kEEokE25X4ly/6YPELdGdnB9FolEV7SCQSLJV7NBrF6uoqS5cVjUbR39+PyspKVFRUSMU/ykh8//59rK+v48yZM6iqqsLIyAhu3ryJ8fFx9PT0YP/+/VhYWMDQ0BB+8IMfAAC+9rWvMat+INdxmsKskAN2NpvF1NQUrly5Ap1Oh5dffhkNDQ1SjqgQTocn3uzjy5JMV8NvdmpcRj4uS+l+GQejdqJJ9zyLjupZuT4ZIMu412x21zyBTsUpFdzm5iaLH0YbVj76mQPVnTt38PWvfx2vvvoqAKCurg5/8zd/gwcPHgDY7eQf//Ef49/+23+LX/iFXwAA/Pmf/znKy8vxve99D7/5m78Jv9+P//2//zf+8i//EhcvXgSwGxWyuroan3zyCV566aWC27O5uQmv18ucg0WWlt8ByO7JZrMhHo8zjkqn0+HYsWOoqalBNBpFXV0dlpaWcuI9azS7YUIoeBwpqvkIDMAXrh2kZIxGo4ybM5lMOWYOooOxVqvF5uYmc3YWJ282m8XS0hI++ugjTExMYHt7G1rtbmr65eVlXL16lWXLqaysBLBrMnHixAnGTcmcUGOxGObm5pBKpXDy5EkcPHiQxRhKp9N48cUX0d3dDYvFgrq6OrzwwgtYWlqC1+tlWYRpjNvb23NiTjU0NKCsrIz1u7KyEufPn4fH42FJHHgwoLHmP0VSWqgiWKjpm2QkckiF6rr4OmSW3Up9EOuU/ca3Q3xvanoxEWDVODPZb/lESaqHIkIsLy9jZ2cHiUQCqVSKSSr/1ww+T506hT/5kz/B2NgYWlpa0N/fj5s3b+KP//iPAezGh1pZWcGlS5fYMyaTCWfPnsXt27fxm7/5m3j48CGSyWTOPT6fD/v27cPt27elQBWPx3O8sQOBAACwgQHkg8nrcejFkv0TiUsajQZDQ0NYWFhAKpWC3W5nGZOBL6zf9Xo9IpEIfvCDH8DpdCIWi7EkCDabjemHbDYbSktLWXxx8iYvLi6G2WyGw+GARrPr80ZOvRrNrg8dhXThJxhvAGqxWNDc3IySkhI4HA74fD6YTCZcvHiRZXguLS1lvnM2mw2HDh1iFuyifgrYNXk4ffo00uk0ioqKWDC8AwcOoKuri5lTAGDx3FOpFLvOiy28QzL58JFDNfXZ7XbvSZdVyCJUAxL+uow7exYRShRvZCKUTL+kVmY+kgEr3xfeLEbsfz5dmMx6X0ay60oiOW8o7fV64fP5sLOzg83NzRz3qkLpZw5U/+pf/Sv4/X60tbUxg8jf//3fx7e//W0AYCFBysvLc54rLy9nqXNWVlaYvke8h54X6Q//8A/xe7/3e3uuk2lBPnldo9n1kifj0FQqBZ/Px9JPj46Owmg0wu12M7cOo9GY419G8cNDoRBbuGVlZYhGo0yvVFpaivPnz8PpdKK6upqFLNZoNCxZKrHDPp8PpaWlLP5Ta2vrnpTxQK6uzel04vjx4wwICICOHTu2Z4JQvcT1kUghhh2hcoloctJzpDTlRSNRh8LXy3MVvPEtv9NTG/g2ywCLnuPbJQMsjSbXQ0D2/vlnxPEVgUf0DsgnlsrEM9k9IilxZvSd5jcAFqRQBClZ+5XqVeKU1MRS8Rpvj8eLeryoz7tYFUI/c6D6u7/7O/zVX/0Vvve976GzsxN9fX347d/+bfh8Pvzqr/7qno4RFbLLqN3zb/7Nv8E//+f/nP0fCARQXV2NmpoaFoWTJ7EcrfaLdN8UR/zMmTNM9KBkC7SAKPAbEWXHrampYeXThOGjHZD/WjabZVmVKTInuaLQIuCTawJf+NIR8ROCD62h0XwRxpf3wxNBSja+/C4tghcvhtKY8eMp06vIxBOawKLTMT9u4jsSHZz5MvOJXXz5hcwzpTYofRefEe9RAli1utVspPjr/KaysbEBm83GTlSV2qr0Wz4OTKk94njxY01zmtxmSMKh+/6vnfr9i3/xL/Cv//W/xre+9S0AQFdXF2ZnZ/GHf/iH+NVf/VV4vV4AYCeCRGtra4zL8nq9LJQtz1Wtra3hxIkT0npNJpNU3p2bm0NjY2POQgbkE4239iYS847RQlOKaiAuZtmOJu7y9Cxdo8kninW84aNYLu++wz/H18O3T0n84ReJeE2cyLLdVgQpvhyekxIXsaxPYh18n9SARyYm0XeZDk6pbvF3WbtlnzyJ7VACDREECwFfEcz0ej3Gx8fR1tbGHNtlfVD6X63fhZJYJ6kXbDYbEokEC+9CVChH9TN3oYlEIntOJfgY4PX19fB6vbh8+TL7PZFI4Nq1awyEent7YTAYcu5ZXl7G4OCgIlApEb/gZRM937MiySa5kmghLlC+bt47n8qUiRPi4tJqtUz0k3n882Iuz7GIHBSVxQMX3wd+YSrtukpihAwI1U7bxMXM913k8giQRQASx0vJTUU2Dvw9ojkL/27zcZBKICX7TW3s+LrV7uHnVCaTgcfjgd1ux+TkZI4xpVim7J3mWw/8exVJ6V3QvRMTExgYGGD6KafTibKyMpSWlrJT/nz0M+eoXn/9dfz+7/8+ampq0NnZicePH+OP/uiP8Ou//usAdjv827/92/iDP/gDNDc3o7m5GX/wB38Aq9WK73znOwAAp9OJ3/iN38Dv/M7vwOPxwO1243d/93fR1dXFTgELJZPJlCNCZbPZHBFKXKg8Ke12sgkq8+4Xj2r5nZJ+4+MdiVEaZDt1Npvd45AsEg9c4n1q3IsSKXGhSveKE/9Zd2Uivn2yBaBWh9rCE8dWJJ675etWK1vcnMQ2iQDOA0ahG4EMCMV+1NXV4eHDhxgdHUV7e/ueQxL+OZEKeU/5xkFWFsVIt1gsTP9KqpJCGAbg/wBQ/bf/9t/w7//9v8dv/dZvYW1tDT6fD7/5m7+J//Af/gO751/+y3+JaDSK3/qt32IGnx9//HEOuv7X//pfodfr8dZbbzGDzz/7sz97JhsqYFffRHGx8ynVgb0yu2yRyzgm/n5xQYkThS9LBib872rt5RfQswAP34dn/f2nmeD5+iKCKN8ONa5FJpaKHJ1YpsxVSKlutbHNN+5KmwT/SfUoiaX5iN+AjUYjWltb8fjxY+YhIZtLMpDPx/XJOCdZ/+g7bb4ejwculwupVIolRgmFQgVLNgCe/wif+/fvx4kTJ3DhwoWcUyQljkoGVOL1fN8L4XSofP6TSHZ0K/s/3z1qbVArV01My/e8yFGIooqS6PAsICtrkwj4IlDxxM8Bpb7yz/Lcsvgb/7/I/Ray+ShxXbLfldpI74wXW9fX1zE+Po7a2loGVjxHJ7ZLBs6y38W6Ze3kgTebzWJgYAC3bt3C4uIitra2EAwG2b2RSARTU1NfRfjkFdPixJQBlDjZ6Rp/P09KL11pkvJ1KJWlJN6IC0GkQtqmVF+hzyktQtmzaqCXT3x6VpJxl7J6lIBExpEV0maxbKCw7MhKG5zsvauNB3EuYrllZWUIBAKYnJxEcXExHA5HDoCIdmpinUpzkK833/uits3NzaGvr4/Z1TkcDpaYNB6PY2pqSrF/RM89UNXV1bEMIoC6fC4DCvotH8mcQwtdcDy4KU0aGQelBlpiuXxZ9JtMPPpZkhqYFcL9FQpcIkiJz8vqktlcFcK9iByikplHIUCnxKkUKv6J80YElpqaGmi1WubMTkSHLmp2ZV+GZECn0WhYwlGfz4eqqiqEQiEsLi6yFFqF0HMPVNvb28hms3uMJIH8u4aM8nFLMiqE+xDvLaQepTb/tOCTDwD59uW7VxxjcTLnq1tpEaldF8FKCcRkOiEZF61UB7+ByN6NeE0t5pTSZyEk49ZpzldXV2NzcxPhcBgOh4OdiIrmOnxZ+URcpbr5a/y4UEaldDqNWCzGQk9vbW3tMf9Rouc+wie5tpAYIhoYKnErPIn3yO4XryktFv5/flIqhTIRy3xWTq/QPokkTlhZ3wsZBwIEvj7xT+l5NY5I1h8iWaA9JVGTFi71WW1MZO+QnlO7Rwn0ZH/PSjKAJINKjWbXNtBms+Hp06c57ldKri9KY17IxiW7ptHsppY7cOAAnE4nFhcXMTMzAwDsgKsQeu6BigCKvtMuIipIlSaMbCKoLfJ8olshi0CsV2xvvgmuNvGVuLRCxJ583FA+sOe/yzaKfPeo1VvIhqN0P/2JgKr0jIyURD0RpPK9ky8DWOKGQgBAdTscDlitVty8eXNP1nBZnYVsXkok9ler3Y3j/+DBA2xubjJfV5fLhYqKioLDNj33QFVTU8NC/z6ryAaoL05xgsueFQ0PxXJEsOTLlT2nxs0oAe1PI5qq1cffR5QvyJ3sHfCTWwSPfLHuxfr5/qgBIH9djZuld6hWH39NaSPhfy/E+PVZiR9X3i2LymttbYXFYsHjx4/ZPbJNmOcu1URisU7+Go0b7wqWTqdx6NAhvPTSS7h06RI0mt1oIxRyOx8990C1tbXFjCplk0S2eNQmdr7f1O5VIrWgcGq7Pf+ptiPmAzfxHv5TSfcighPdJwILjTnv38f7KPJ9l4mIhY6TSErvVWybEqcjG7NCAF2JS1eyas9XnhrRfXwd9F3cILVaLQ4fPoytrS0sLS3l2COK70GpDYVsVPxz1AaTyYSioiIEg0EEAgFoNLsK9rW1NayurubtJ/BzoEwnHRWR6PMmkhoXk+9+pVhD4sSVAZgS18FPRqqDl+tFvYrS4hTvzWazLDZWMpmEwWCQ+i/KdlACHL5NwK7OYWZmhkV8APZGWOV3edpp+br4+mWnUiIo5+uz2G5xbPP1k/5X4vyU5oT4zvmyldrzrKQ015S4IpfLhYMHD6K/vx8OhwMul0tx4yqEZMAlGzuTyYSuri4sLi5ibm4OoVCIxV/7KrnDPxKxnrTAxckhm7hK/4svUXQK5Xc1McIA/z/9TuXpdDpEIhGYzWYWb5zut9lsiEQiSKVS7OVTfkB6yTzIyWxq6B6+H9vb27h9+zYymQwikQhcLhdOnz7NUmvxz4gAw6fxEgHr1q1bOHToEAulzN/DW4Pz3JNYF/VfBuxiXwq9LgMdWdn8GPHjqARM4gahBj6FiOD88yLgiUAp6zfNQVm/stndnI5zc3NYXFxkBpZKm4Ks/HwkA+loNIqBgQEWL12j0cBsNsPj8SAajWJiYiJvuc89UNXW1sJut7NMxiJIiBMylUohHo/DarVCo9nNaRcIBBjIWSwWuFwuzM7OsgSKBoMBjY2NWFtbw/LyMgv/W1VVhZaWFiwvL6O/vx/RaBTV1dXo7e3Fo0ePUFlZierqamxvb+POnTtoaWnBZ599lsP1XLhwAY8fP0ZfXx+02t0wxb/wC7+Ajo6OPWKLzDZIXPAazW4G6GAwiLt376K1tRUmkwm3b9+G2+1msaxEEOHrIBsc8teicQPAgqPt7Owgm82iqKgImUyGpSwDdoP7mUwmbG9vIxKJIB6Pw2QyoaysDMFgECsrK4jH4zAajairq2NxtkWOS0ayNhPJNh0RaNRERll5Mk5MVofSpqHULrFNz0J8vVQX75x/4MABjIyMYGNjA6WlpVKAFOvNd00m/tFaI86ZnJL1ej0L/VKoecJzD1Rra2tscfIDKIpZtNhu3bqF/v5+nD59Gvv378fDhw9x5coVZjDndrvxwgsv4O///u8ZcEQiEZw7dw6hUAh3796Fx+NBMpnEgwcP8NZbb+GTTz5BOByGzWbDkydPYDAYMDg4yOxcwuEwy7iyubmJI0eOwGKxsF0nm82ioqICFy9exKeffopr166hoaGBOZyKxPdLFscJ2I1Y4Xa78eKLL8Jut2NnZ4eFHC4rK4Ner0cgEEAwGIRWu5sSPhAIIBKJoLKyEg0NDRgaGmIhinU6HXp6epBMJvH5559jYmIC6XQavb29qK6uxpUrV7C9vY1QKITq6mqcPn0a165dYynEbDYbXnvtNTx69Ajj4+Ow2+1YXV3FkSNHcP78+T2RQvlPse8yjlIcFyKaE3yEC7FsNaAR2/JlRbl8IiTfN5H7VHqe7w+/OTscDlRXV+Pp06csBVc2m93jR1sId6W2GfAcOFmjh0IhhEIhljKrUGX6cw9UAJiOimeLZQv3wYMHuHr1KrLZLH74wx8ilUohHA6jrKwM586dQyQSwdWrV7G+vg69Xo+LFy+irq4OH374IVNQnj59GmfOnMHCwgJ++MMfYn5+HsFgEK+++iq8Xi/+7u/+DsvLy4jFYlhaWgIALC4uIplMIhaLwev14tSpUznyu81mg8/nQ3NzM6LRKG7fvs1Sz4v6qmg0mjPBzWbzHj+4bHY3kQXVTWCbSCRw5coVnDt3DrW1tVhcXMT4+Dj0ej2ePHmC4uJiZDIZzMzMIJVK4bPPPkN5eTlKSkoQCoWwubkJg8EAp9OJyspKTExM4MmTJ6ioqIDRaEQ6nUYgEMCjR49QUlLCfNFcLheLHT8zMwOTyYTa2lqmbJUpe2ULmH+/4m4vcjeFiJOFgo4SKH5ZUgJa/nfZ90LaSPeXlZVhZWUFY2NjOHLkCBPRxfETy5CNm0zNQOK9VquFxWJBZ2cnSkpKsL6+jtXVVYTDYTYnCqHnHqh4UU/koPh7QqEQ7t+/j+7ubuzfvx8ff/wxRkZGYDab4fP50Nrais3NTZhMJgYSLpcLRUVFDAgpO3IsFkMwGGRhYV0uF8tlV1FRAbvdjtLSUkxPT2NtbQ19fX2oqqqCwWBgNid6vR5er5cFGiTbGLJDAeT56gYHBzE6OsrCvl68eBHl5eVS0SYQCODmzZvQaHYNA71eL2ZnZ1nseUocShzdhQsXmMiWyezmanvhhRfg9XpZwP4nT56gvb0dvb29sNvtGBwcxMTEBIaHhxkYA2Cx4aenp6HR7J4CtbS0QKfTYW1tDaFQCDqdDjU1NTlH7Wo6JUD98EMNjAoBFl6Mkok7aqKSKD6K87EQnZlaXwoBWr4Oimg7NTWFra0tlJWV5Yj8aqKe0riIdfOHS1NTU1heXmbhhymKLgCMjo5Ky+XpuQeqmpqaPWGIgdyJpdVqkUgkYDQa0d3djYaGBkxNTWF1dRXJZBKTk5NIpVLY2NhgWWn8fj8uX74Mg8GAubk5lrPv448/xt27dxGJRNDQ0MBeCj8B+JRbs7Oz2N7eRk9PD2KxGDY2NtDX18dyoJWXl7NTOY3mi/hVtHj5A4JsNovS0lIGYFarNSd0DnElBKwlJSU4c+YMXC4X08mJXCYlafB6vaipqWGgNTIyAoPBAIvFAoPBwMIek/U/7aTArvhtMpnw2muvYXt7Gzdu3EBxcTEuXLjAUnh9/vnnmJ+fh06nQ1tbG5qbm5HJZFBTU8M2GyWScchqxI8XLVoZsKg9L84h2f9qXJFYRz7dm1gmcSyyemXly4DNZrOhoqICo6OjMJlMsNvtUjMFNV2cGnfKi37RaJTlO6DU7nwmpXz03AMVKXGVXiR/KheJRPD+++/DYDBgaWkJjY2NyGQyiMViCIVCcDqdOHjwIIqKimCxWFBWVgaPx4P29nY0Njbi8uXLqKysZE6Yx44dYy+DwIXYXeIUPv30UxgMBtTU1ODp06doamrCK6+8wuK88zuTRqNhadpl4hCwC8zkjAp8MZH4WFy0QG02G2pqatgxdTAYZIBcVlaGqakpltJItjBisRi2trZgNBrh9/tZHdQ2AiwSSUnHBeyGIVlfX2cnTxQrXqvVYmZmBlqtFsFgEHq9Hh6Ph/WFf3dK18R3rPSbmvJYVgb9TuIKz1kVIqbxIKMEcs+id3oWLpDuF0+jKevPyMgIent7pT6A+UBb7V3QYZPP50MqlWJhXiiL9lc6qn8kfiBkegQaUJp8lP2GRDeNRoPe3l68+OKLbBeg0BmHDx9mcd/T6TTMZjMOHz4Mj8eDn/zkJ0ilUkxUJMUhAZ7T6URxcTFGRkZw6tQplgCCRDseHCKRCEwmE3Z2dvD06VMmFgHyXZ03m6B+8QuKjy7KP6vVamE2m/HJJ5+gr68P4+PjaGpqgslk2gN8FosF0WgU3//+92GxWBCLxXD48GF2okfKWYvFAq/Xi7t37+Kjjz5iz5rNZqyurmJ4eBh6vR5OpxNNTU1wu9149OgRNjY2YDKZWAYemSU1339RV6KkdH5WUuKelOqXPVsoAMrKUhMpRU7zWfrJ31tfX4/BwUFsbW3B4/HkhIHh2yGLECLTBfIGvnQ9lUqxE2CaG5QGrhB67oGKEj7wL1UcnEwmwwbyxRdfRGVlJa5cuYJQKASNZtfmgw9CT4NPIg8AltEYAMtjNjIygv3792NxcRHvvfceioqKMDExgfb2duh0OjQ3N2N0dBQtLS0wm81MmfzOO+8gk8nAbrejtbUVS0tLWF9fx+joKILBIM6ePcvAQOyPuMvzOzjwxQQ1m80oKyvLSZBqtVpx5swZpNNpJJNJdHV1wefzobKyMsdmC9hVxr744otMgW61WtHU1ITNzU12ilReXo7Dhw+z1O+ki9Lr9SgrK0NDQwNTotMGUVNTw8Q+nU4Hp9O5Z5GI/c7HeRRC4r0iYIjiTr6ylNpWSJvUuDTxOg8KsnvztZnXD1LadT58MQ8+hRDPLVK7yAp9cnKSSRUWi4X5/BVCzz1QVVRU7NkdiMTdgDgKirFO9j3A3vjnZrM5h6tJp9NM9rZarWhsbMT4+DiKiorQ2dmJiYkJBAIBtLe3M12P1+tFV1cXqqurkclkUFxcDI/Hwzgmu90Ok8mE9vZ2VFZWwmq1orS0FG1tbTntF3c+mRhBJzB0j9frRVFREcxmM7tfp9OhoaEBVVVVOQkSZOOn1+tx4MCBHPekbDbL8v8R0JIBKW8ASgBqNpvhdrv3JKRwu90574gHXZ6zKoQDoffLj5f4m5KOhQebfPom8Vn+f6W2KbVTBCK+nWqgLBNlZQAsI7vdDrPZjK2tLZSWluaADR9kT6nNSv0nlQfZwgWDQSYOFmpDBfwcANXm5mYOoPBH9bxOxWKxoKGhARaLBZlMBj6fjy00i8XCEjBks1m43W709vay+D7Z7K4/07Fjx2C1WqHT6bBv3z5UVlaioqICL7/8MhMlKWuyRqNBRUUFXn31VcYCd3Z2orW1ldkMEUiUlpYyQzna3eg0TrR8B3KBl0gENQq0z99H9lDEZdFvpLDnj6/pGf40TlxIYvgUvj0EOBSShIjnEGiBkMGgLF6+bAEpcc5KXJYIEDJgUQMCtcVaCJDKSAaMfFkih8xzz+J1Gcmeq6iowPj4OEwmE5xOJwMpmdGwrByldmazu4c8nZ2d2NjYwM7ODvx+PxMJC6HnHqiSyWTOBBflavrzeDzo7e1lINLU1MQWiThpHA4HHA7HHkv3srIytrCtVitsNhvjjKhcvm6dTsdO4Ggh0gkhz8Xwf8S98SdVIscB5LrqFMJhUZt43zseNKg8PmuOOC6i+xD1gy+Xby//Lnjif+OVu3xUSp5ErovvkxIpcRoykOH7JgMdpUgESuKfGslAgP9NDWz535XEQbFcfn7Qpri8vAy73a4YtTafmCmKf5lMBslkEkajkW3uANiaKISee6ASdUv0KQ42xXLmFybPfcmOgmlCkJUtXefZdXGX418+nerRziITbURuhTgqAppYLMbML+j5QCCAVCrFzBMobfzm5iYD02AwyIw5s9ks7HY7mpqapIudgH57ext9fX1obW1FVVUV0uk04vE4Pv/8c2Szu+4+lKqbnqP+yHZmajPPrYpjKJKSaCdbROJ3GQgocUTPygHlu5cHX36M+U/+ez7wE8vl/+c/lcaD/59vW3FxMWKxGAKBADsNVgNPpXEgonUUiUQwODjI3NNMJhMz3SmEnnugEnVU/MsRFZH8IuKTpvLH7fF4nCkbE4kEG2ij0YhQKMREx2QyiXA4DKvVimQyyQzqVldXYbPZsLm5iUAgAGA3E4fX60VtbS0AuZghTpBMJoOdnR3cvXsX5eXlqK6uRnFxMR4/foxHjx4hFAqhtLQUX//612Gz2XDr1i08evQIv/Zrv8ZMD9577z24XC5mWFlXV5eTsJSf9KFQCFevXsXDhw/hdrtRXV2NVCqFBw8e4IMPPkBbWxsbI55E1yWeRHFCtsjziVb8piD7XW2hKtUhAxK155VIqc/id1m/lUBKqQ0y7jYfZ6VUX0lJCXOE54FEaSyUwJPuIS6cDJpjsRhzqylUSf/cA9XOzo7iZCFRgp8Ak5OTiEQi6OjogNlsxv379+F2u1FTU4O1tTWMjY3hwIEDGBwcRF9fHzKZDNrb23H8+HG8++67OHLkCJqbmzE5OckszmdnZ/HWW29Bp9Ph6tWr6OjowOjoKB48eIBgMAifz4ejR4+itra2oCgPwK4F+scff4zV1VU4nU7U1dXh2LFjuHnzJnw+H2pqanDjxg00NTVh//79GBsbw/r6OuLxOLLZLOLxOIqLi/HKK68wuzACGbKAp/EJBAK4fv06+vr6mPV9KpXC/fv38dlnnwH4ImEAn1SSFz1Fkk36QjgIGYncj9qCFrkI/ru4OfDi1LO0R61epbYrAbVYhlqUA1nZvA5RBBClzZBs/ci4me4ttP8ykdXhcKCpqQlOpxN+v59x/WqGvDw990BFCyif/iKTyWB0dBRvv/02AoEAXnjhBZw8eRK3b9+Gw+HAL/7iL+LRo0cYGxuD3W7HrVu3UF5eDgC4desWnE4n1tfXWXnxeByhUAjRaBSjo6MYHx9Ha2srgsEgzGYzXnzxRXg8Hjx+/Bjf/e53UVxczHbA+fl5GAwGVFRUSCeGTqfD5OQkNJpdpTgp7q1WK44fP46mpiZYrVYsLS0hHo/DZrPh/PnzLJ8aTbpoNIqFhQXodDpmuEqTkQfx/v5+PHjwAE1NTVhZWUEmk8Hq6iquX78Ot9uNhoYGJJNJxmHKuEA1rkhNXHqW//nrvPiUT8wjkundxPtkwMLr02TtU1vgzwJ++QA4H2cmAyjZu8pms8z+j9zF+IMUtbrF8QTAQC+VSsFoNMJms+Wc/hZCzz1QkU2PbEB4sWFmZgZvv/02rFYrnE4n7ty5w+LlLC0t4cGDB3j48CHsdjvW19dhtVrx8ssvw2g04q/+6q+ws7PDRMJs9gtzBRIB7927h4qKCjah3W43PB4PnE4n7HY7My7NZDK4evUqvF4vi2IgLupUKsXYZzKJaGxshNPpRElJCXQ6HcbHx7G+vo6mpiZkMhnmJsMrN9fW1vDgwQNoNBrE43E4HA7U1tbmnJppNBqsrq4iEomwEC59fX3o7OxEOBxGKBRiwDo/P4/W1lYAyBGdZaTERcnuK2QBitxPoSTbwPJdU+vHl+W48tUvq4vvw8+C+LHWaHbtqyKRCDtxFtvB1y+CnrhZALsO8Nvb23A4HCzMC5kt5KPnHqj4wROPrQk0tFotA5pXXnkFLpcL3//+97GxsYFMJoNwOIxPP/0UkUgERUVFSCQSKC4uZu4fdrudKZFJsU0GkmRISpEIRDacjEZJXwbs6tXcbrei82s2m4XP58Pw8DCCwSBu376NWCyGl156CTabDfPz88wKvLKyMifYP8WTcjqdOHr0KA4ePIhUKoV3332XBf4XOYvy8nI0NDTk7JBFRUXo7e3NydHGR2rgDx/4T6JCRD/+d1FUE38T3yv9n0+XIqsrn3mDWrlKYlW+OsU6xLJk15XqFokHDf5e/h3zIjp9kt8mOS0rbTyycRLHKpVKweFwIBQKIR6PIxKJsLhohdBzD1SxWEyRXeVZ2UwmA6vVikQigY2NDWSzu6FQyDk4EAjA4/HAYrEweyN6juyeRP0SheNtaWlBIpHA/fv3WWQCAiE6vifS6/U4deoUmyQysUWn0+Hw4cMwGo24du0abDYbVlZWEI1Gsb29jXfeeQfhcBgvv/wy6urqcpSq9On1elFcXIzKykqEw2Hm3kChiROJBLMJO3z4MLq6uhCJRPCTn/wEra2taGlpQUNDA7RaLR48eIClpSV4vd494pZsgcmOvZVIacGriTFqIlIhVKh4JWuTuEiVnuVJdp9a/wolJaAFkDP3aS2InBGwG+QwGAwy9xpZO5RUKUQGgwFGoxE+nw82mw1bW1vY2dnJOSHOR889UInH3uJvxMnE43HMzMxgdXUV2eyusrmqqgomkwmdnZ3weDzY2dnB+Pg4ADCHW9HVgICH/kj/4/V68eMf/zgH5ETZXqvVIh6Po7+/Hx6Ph4lRQO4kS6fTWFhYYDohsqD3+/24desWtre3cfHiRTQ3N7PnCITo/4WFBUxOTuLw4cOIRqMIh8Osrnv37mF4eBivvvoqqqqqYDabmRuR1WqFxWJh1vsAcoLaiWBRqJ4q33UZFyNbzD8LkBK5ASXRk1/ooo4qH3cnq1OtPqVy+WtimWL9onis1CbeiDib3TVwDgaDOTkyxbaI70Pk4Ch6AoUIIpUFbeb56LkHKj6dO080kDTJ0uk03G43Dh48CIPBgIGBAfZcSUkJ2tvbMTQ0xESjQCDAHI2JI0mlUkgmk9BoNAgEAowrMZlMaGlpQW1tLSYnJ1md/ASnlxuPxzE8PIza2lq0trZKd690Oo2JiQncunULoVAIVqsVR44cQTgcxvDwMLLZLIaGhrC0tIRDhw6hurqa6bNIzNTpdBgcHMTMzAwbBwqMFwqFsLa2xhy6edeX4uJiZrlOE9HpdKKqqkoaLkWkQjgjtfv564UsVhkHkA8IZKILH1uJyhZFZLq/EKW8WCe/mfBgJbsmK1OJe1J6HzKuV7yH34itVisikUhO2CBxoyUS7eWIo3I4HFhYWGD60mQy+ZVlOhFFvCTiXwZNvlQqhVQqhaqqKpw5cwaJRALLy8vQaDQ5iRzpk0IKv/POO4jH4/D7/ejq6sLMzAzee+89PHjwALOzs2hoaGC+Tg6Hg7kQ8IakxJ1QXSaTCUeOHGEnI7IIiEajEUePHoXH48Hg4CDq6+uxf/9+xONxtLe3s6B5wBe7os1mw759+1BUVIRsNovGxkZcunSJWQwXFxejpKQE2WwWR44cQVtbGyoqKnKUoWazmYVJ5vU4dXV1qK2tZQpXEYh5EvUt/DWeRJFXiZvi7xV1VaKNHG/nxbeP7qfx5m2/eGt7us4br/Knynx7xT7wIj6VQ++WB6JEIsF0nXxdYvgVWX0yEoFU9il7hufyiItaWFhAQ0NDzikg/w74tokcFak8rFZrji6XbAnz0XMPVGIoE5F4kY1siUis0+v1bDcAwMKRtLW1YXNzE+vr67DZbDh+/Dg7BZuenkYikUBlZSW6u7tZIHsA6OzsZCd+6XQaVVVVcLvdOaKTwWBAV1cXazu1EchdgG63G4cOHUJbWxusVis7YXzzzTfZROGD9tlsNhw5coT112az4dixY9KdlVIpyfQYFC2Un+SidXEh+hT+8ICf2Go6IB7gxbr450UnWtqMaC6QjRgRPUsccSKRYP/TgcnOzg47lHC5XHA6ney5ra0tWK1W2O32HE6GB6Dl5WVkMhnm8E2eAalUCiUlJSxixODgINbW1tDa2sriocnGJh9Y8/eJvyt9F5/jTRJMJhOqqqrQ19fHpA4lsOLbRWYuZrOZBVlcWlrC4uIi0uk0C66Yj557oBIta0XdAg10fX09E18MBgMOHz4Ms9mMjo4OFritqqqKcR6vvPIKizdlNpthMBhw5swZnD59mpVJweBowhYVFaGnp4f97/F4mLhF7aF2yk5oeH0b/ZF1Ly1CWiz8xOazxogAQYcBPAvOi3aiWCDTb/CTXLTm58PI8ONN0UCB3QMPmrQkUlM5FosFDocDm5ubiMfjSCaTsNlsOdlTxIUXCAQwOzuL5uZmtnOvra1hYGAADocDhw8f3hP1lTiXO3fuYHZ2FhqNBuFwGJ2dnXA6nRgcHGRH6i0tLQz019fX8aMf/Qj79u3D6dOnc/pJXNjKygp++MMforKykrke3b9/H4uLi9BoNLh+/Tq++93vQq/X4/79+4hEIhgZGcG3v/3tnDDS/FwQQepZROd8Yrko9vIbWDqdxsrKCqqrq6UAygMr8MWGlEgksL6+jlAohEgkwsL98C5uavTcAxUZUvIvUvbyfD4f+67ValFbW5vjUEu+cxaLBRqNZk/yRt5AUtTV8Kw7cU+iGED3isAg+v7xi5PKFgGFdyDmxR2+HGojJXkQxS+Kl07x2ek5Ijp8SCQSrD319fXs/q2tLUxOTuLQoUM5yTVorOg7WbiHQiGcP38eDx8+xNTUFFKpFPx+PxobG3Hs2DH86Ec/YuNhNBrxrW99Cy6XK6dPOp0O4XAY165dw9OnT1FTUwOTyYRYLIbbt29jdXUV8Xgc6XQaZ86cyRk3EsWWlpbg8Xjgcrlw/fp1zM7Oorq6GlqtFmfPnoXRaGSxvtfX13H58mWMjo6ykMl8P6ls8rmMRqM5hylHjhxBSUkJ/uEf/gGTk5MAgNLSUhw9ehQ/+MEP8PjxY5b+XEmPpCYt5CMl3Z1MzKZrPT09WFtby5lDInjSJ7/ZUvij5eVlhMNh5uv3lWX6PxIfaUDpxfCLW7yHdn4SoXhdhahDIrGCP2Ej40oCBBIngdzdhjg5Siek1+uZH14ymcTW1hYTE4hLiUQimJ+fR11dHcxmM1KpFAYGBhAMBhGLxeB2u9Hd3c3aJnJACwsLuHXrFo4fP87MGLLZLEZHR3H79m0Yjcac5BC8knR1dRXvv/8+81vc2NjAL//yL6O3txdra2v44IMPMDc3h46ODiY+8eOi0eyGJ3706BGuXLnCYsOXlpaiqKgIJpMJP/7xj5FIJDAzM4N0Oo033ngDOp0Of/M3f4PV1VUGVDzQmEwm2Gw2ZDK7IaQdDgfm5+exvLyMl156CaFQCPfu3cOBAweYvo4Wml6vx5kzZ2A0GjEwMIBsNovm5mak02lsbW1hYWEBBoOBcRMfffQRkskkWltbmeO3KJ4SJ93d3Z1zYnzy5EkWk8nj8bDwvDU1NaiqqsK+ffuwuLjI5l8+XZQ4r5VEb5ET4zl0tfLoz2KxMF9AMSKIEvHzrqKiAsvLy4hGo4hEIix+WT567oEKUD9p4Qc6nU4ztpR3Lg6FQshmd11OSMFMYksikcDExAQaGxuh1Wrx8OFDBINB7N+/H+Xl5ejv72c57rRaLfbt24fOzk6m79BoNLh58yZKS0vh9Xpx+fJlrKyswGQy4cUXX0RzczMGBgZw+/ZthMNhnDx5EidOnEA0GsXHH3+MiYkJ/Mqv/ArMZjNmZmZw5coVeDweJBIJXL9+HcXFxSxkjTgWAwMD+Pzzz9Hc3Iy6ujpoNBo8ffoUH374IdxuN44dO8bAIJ1OY2dnByaTiVkWHzx4EM3Nzbh9+zZ2dnag1+uxs7ODq1evYnp6mnGiRNRnAvj+/n7cvHmThcPRaDQsE83s7CyMRiPa2tpYJmev18sWC52u8mFpCGzIlzIej0Or1WJzcxN2u51xzQ8ePEAoFGIAys+T2tpazM7O4v79+wCAtrY2TExMYGNjA48fPwYAPHnyBEePHsXi4iIqKyuRzWaxvLzMyhQ5YI1GwwIU8iGvs9ksxsfHsbGxgYqKChZyGthNnLu8vIxUKsWO8EUxS42UAEQEPLGt4rN0jZcStFot5ubm4PV6WYROJbAijp8YAbK129ragt/vL6gvwM8BUKnpUvjfMpkM7t69i4cPH8LpdOLVV1+Fw+HA9773PczOzrLQv6+99hr2798PYPflPH36FDdv3kR1dTUGBgbw2WefQavVYmJiAr/8y7/MUlmTqQHFACcubnx8HHfu3MHFixdx8+ZNBINB9Pb2or+/H59//jlMJhMuX76M5uZm6PV63L59GzU1NUwhTz5UWq0W6+vrsNvtePXVV6HT6fAXf/EXiEQie0RLYHeydXV14cmTJ+y3nZ0dXLlyBRUVFXjttddyOKFMJoPLly+joaEBhw8fRmlpKUpKSnDv3j3cuXMH+/fvR0NDA65cuYLFxUUcPHgQY2NjzNWHd3AFgOXlZdy5cwdlZWWoqKjA7OwsEokEbDYb4vE4njx5grKyMjQ2NmJiYgJTU1P4yU9+Ar1en2PNzO/2BFxkhkEnTQBYiF3iuhKJRE4ZRBRLrLq6GiMjI3j69Cm8Xi+OHTuGAwcOIJlM4tNPP0UwGITVasXMzAwzTwkEAnA4HHvGm961aHQ7NzeHzz//HGVlZWhvb2cJX+ke2ihl4pXYbp6UuK98XJmo/1RSk1itVpY74MCBA2xcxXUmqkGCwSCWlpYQCoVYujRZMEQZPfdARbHIZfoDXk9Ek4aci+/fv4/W1lasr6/j/Pnz8Pl8uHHjBkuIqdPpEAqF8PDhQ5YM4tGjRzhy5Aiqq6vx4x//GKOjo0x8OHToEDKZDNNvZLO7bgV9fX3s1Mfr9cJoNDJDU1ooGo0Gx48fh9FoxOjoKJaWllBTU4PTp0+z0yTR0j0Wi+WItFQnUTabRVVVFcrLy9kEpUwxRUVFGBoaQnFxMWpraxl3SWYUvML0yZMnCAaDbGedn59n8Yyi0SimpqZQXl6eczrEK9QpyWg4HMbi4iJcLhdisRhWVlbQ3d0Nh8OBuro6dHd3IxAIsGw3ov0NLW5aGLzJB59glU50iSMTFyOdqH7jG9/ABx98gKdPn6KtrQ0nTpxAaWkpotEoioqKUFxcjG9+85tIJBJ49OgR/H4/i2fG28VRHfwhhlarxfLyMu7duweLxYKjR4+iuLgYNpsN09PT6O3txebmJmKxmKI7D/U5n2KcJ/5e2bNKwMQ/S58+nw/BYBBra2vw+Xx71CuiLpVO1SnuGiX3+Moy/R8plUrt2YVEmTybzaKvrw92ux3f/OY30dfXhydPnqCoqAglJSU4ePAgbDYbBgcHc54bHh7G+vo63njjDRbnvLu7G8XFxfD5fNjc3EQikcCdO3cwNjaGVCqFzs5OnD9/HhaLBbOzs5iZmcHZs2fhcrmYA/X29jYmJydhMpmYfVdJSQlLikD6rkwmA5vNxo7bHQ4HVldX8Rd/8ReIx+MIBAKqgcko3hAfwC+dTrNcg+FwGBcvXsSxY8dgMBhw7ty5nFMavV6P06dPIxaL4fHjx6iurobX60U2m8XW1hZLeMFPYK12N/+f3W5Hb28vIpEIFhcXmdKZJrzRaERpaSmz7H/ttdeQTCbx6NEj7OzssDDK9P54QCZ9H4mZFosFGxsbWFtbywFdahfPSUxMTECv16OhoQH19fXo7+/HwsICtre3cfjwYdb3TGY3XLXBYEAwGMTIyAgsFkvOgqXvpOMkLimdTmNoaAgTExM4efIk2yQaGxvx6NEjfPDBB4jFYqiurs5JbiHqvkQRLp+uqFBSK4fqtdvtqKqqwuTkJJxOJzsRpA2MP9ihdx4Oh9m4x2IxRCKRryzTiURlNxFNJnJBCQQCLMddZWUlxsbGkMnsRsX88MMPodVqMTQ0hBMnTgDYNVQbGhpCbW0t6urqMDc3B5vNxvzjSElIyl2fz4f19XUMDw8z7ujRo0ewWq1MrCM92PXr17G5uYlLly5hcXGR6cjoxIvfqWnyZ7NZ1NXV4cyZM4jH41hZWWEcnciSi6cx9HwikYDdbsfp06dRX1+PDz74ANvb29Bodu2QgsEgLBYLc8LOZDJobW1FUVERfvSjHyEUCuGll15CKpXCysoKrl27hrq6uhxDUGpHUVERzp49C41Gg4cPHzJRj+4jsw56hzqdDtPT0yxFfHl5+R4zC7qfB4tsNsvi33/2jyno3W43q4vup3pnZmYwPT2N1tZWzMzMwOl0wmQyYWBgAEtLSzCbzSxAIo2lyWTKMRIl4rkro9HI9E/ZbJZF1ejr68Pw8DDj2rq6unD//n1UVFQwfZ04h0XOmCc13ZS4BpQoH/dGZbndbkxPT2NiYoId2vDjyZuoFBUVoaioCG63G0tLS2yz+SrC5z8S7dIyLor39DebzfB4PDnGaRUVFWhsbMT09DS0Wi1TtGs0u2Fh/H4/XnzxRdhsNqTTaWYOQAvbaDTi2LFjcDqdqKysxNDQEG7evIlMZjee0/T0NI4fP47i4mIAu4r5u3fvMi6rubkZy8vLjDMj4KSjcGo7fbfZbDh9+jSi0Sg+/PBDlsBBxpaLk4n+N5lMqKioQFlZGVwuF2PVI5EIrly5gpqaGly6dAkzMzNM1A2Hw4hGozCZTCgqKmKildFoZMBKxIOLXq+HVquFzWbLCXNDnB0t0HA4jKtXr2JkZARerxcXLlxgSmsZl6HX61FcXMz65HQ6WVDBYDCI48ePw2q17tH7aLVa9Pb2IhqNYnNzE6WlpTh8+DC8Xi/zrzQajWhqamKcYyaTYSeWStxOJpNBSUkJjh49ykCtt7cXpaWlbINyuVwwGo04e/Ys2traYDKZmKcAX6YaSCldy0eFKujFe/V6PZqbm3H37l34fL4948CrHpLJJDY3N+H3+7G9vc3WmczzQkbPPVCJWU54ol2YTASCwSDS6TQCgQBisRiKiorwyiuvIJPJYGJiAh9++CEcDgcikQj6+/tRUlKC+vp6pvcIBAIIhUIs23B1dTXsdjtTPtLCTCaTGBwchNVqRUNDA9Ol9Pf3Y3p6GidPnkRLSwu0Wi1LnzUyMoJsdtdZ2uv1AthdWCaTKYcr2tzcxIMHDzA4OIienh5UVlYC2KszoAlNCSVIXAoGg/jggw/g8/kwOjqK7u5uZLO7/lqVlZXMg95gMDDRNZlMwu12o7a2NkfvV1RUxERFXryidlCbHQ4HysvLGVdiNBrR2NjIFNN6vR5utxtHjx5Fe3s7ysrK9ohsPFFGIOJ6stnddF10aiiezPHjU15ejldeeYX9Thzy/v370dHRwerjo2c4HA60tbXt4Q74OnQ6Haqrq1m7y8rKUFpauqcNRqMRlZWVDHDpPfMbK5H4XdyICyE1HRdfpihm0uZGDvf9/f144YUXcrhT/rO4uBh2u50dAFEYo0JP/p57oCIRRaZMB77grIxGI6amptDS0oLR0VGYTCZm4Lm4uIi+vj44HA5UV1djenoay8vLuHjxIsvWUVFRAYfDgZs3b7JTroqKCty6dQvJZBIdHR2YmJhAKpXC6uoqRkZGcOjQIZSXlzNwfPLkCRKJBBMvUqkUamtrUVtbi7fffptZzFNsdYPBgNLSUsaNRCIRPHjwAE+fPkVvby/Onz/PjOpkTrUajQbl5eWw2+3IZDIoLS3F8ePHMTg4iPX1dbS0tODgwYPQaDQwmUw4c+YME0W8Xi9ee+01Fuq5rq4uJ2aR0+nEqVOnmK0Sz/3wCvlsdjdNU3FxMQM18ikkNw2z2YwTJ07kcIH0DsU+UbmUG5B3TaJ8dfz9fDm0YRAXLo4V6fKAXBcgfmxFA1sRoOl+kVPiFzh/Ekb94U8N+X7LOEoRJJQATIkjUwNA8TmtVouOjg4Wv41Ect7GkD88obmaSCQQjUYRjUb3tEFGzz1Q0SCpsbdmsxmtra1477338M477yAYDDKL4Pfeew/9/f0wm824cOECHA4Hbty4gfLycjQ2NgIAi7zQ09ODTz75BNlsFidPnkR1dTVWV1dx69YtbG5uQq/Xo7u7m2UV7ujoYBPQbDbj2LFjbIeJRqMsvfuZM2fgcDhgNpvR3d3NuDKn04nu7m5meGc2m3Hw4EF0dHTA6/Uy2x3RUp6+GwwG9PT0MBacRFXemtxkMjGRlhTYpHegMDL8+NInH0pZ3J35hUTtI4t2Wpi8PodfyDwpcUX0na+br1/JmZa4N574FF2yED4EbiLHwSdm5dsqLl4CbVmfRJDjNxzxGVE3pgZePKjKwF4k8RoPZtns7iHI/v37MTc3h7KyMml0V7LI9/l8yGazLB5VoZbpmuyXEWr/H6BAIACn04n//t//O6qqqvZMUn4CZbNZhEIh3Lp1i/mInTx5EqlUCtevX0cikcCxY8eYDD4xMYGioiJUVVWxhQbsTsL19XXodDoUFxfDYrEgFotha2uL+bIVFxdDr9cjmUzmLEZ+B6Kg97w/Gr9gRNFNaaLzJAMLUc8lcgBUHu3kfDl8O9Q2AZloBkA6QcUFJ74nsT+yekTuRGyfyN0oASFtIHy5/PP8KZwoIoltlr03pef4jYX3lhA5Kr799JvMA4MHpXwnh2okAqj4LhKJBB4/fozKykpmrkB6xlQqhZ/85Cfo6+uD0+lkMd/ICfzhw4fw+/17DHB5eu45KrKjEkUfIhp0m82Gc+fOIRaLwWKxMG7k0qVLTDQkm5zW1tY99km0w/I+g8TGE2fBT2ISyXiRg4jfNWmSi/oJIj5xhWwS8WWKO61MNBDHRhQD1J6RiZaFLgQZiSKOrA7ZNREExT7zz4nzQiZeyj5F8UpsB/1G75E+SQ/HXxOBlC+bP5zhyxU3qmw2yxTZYsJdGXcp1pWPZBwZ/5vFYkFLSwuWlpZQXFzMYqGTeQKd8JEetLS0lGVEKoQKs7b6f5jo5clYXH6yALvg4XQ6GSgBX0TyJDZVif0GcpWeNIF4H0ElboGekf3xbRf7IFvIaqTGlSjVoQZ+ssUqu4d+l40Bv3gKFQOoDBpnEYhE2y0RNEVOSOl3HsRkY8frqIiUAJzK43VO9Ml/57k7nhsS+86DIBEfwZXGWhQhxfbJQFzpT9YGvh0kRfBGyLy4HIlEkE6nYbPZmL7vq5jp/0j86YyMq+Injigq8NwOXRNN/mUvXlwksvvoNyWwKYRjkT2vxnnk445kgCPu8LL7+D4r6X/EazIOUVyEYv/UOD/6nV/4vKhE38U5IIrN4nE51U9GttQ/cigmf0Ke6yYjYzpJBb44fSbjT41Gw1x8iPOmSA/882RISSfS2WyWHeCEw2E2N61WK8xmM0scCoBFKAiFQjk+hkajEfF4nLleiYk58nHa/JiLY1VRUYGpqSn4/X4Wwkir1cJqtcLlcsHj8cBoNDKTm0I57uceqPhIBSI3wn/mW3xq8j9/f74FJi5e2U7Flydrj9jOQlh4pWeV7hXvkblyKPVRJq7xAMYDCN0nliXrO2/5rNPpmI6D+kZifjgcZjoSo9HI4lyFQiEYjUZmgBgOh7G5ucn6VllZyXzYotEoi8xaV1eHpaUlrK+vw2AwwGKxoLa2FoFAAFNTUwB2bYpaW1uh1+sxPj7OzFt8Ph+sVisGBgYQCARgtVpRX18Pr9eL6elplguSbPbW1tYwOTnJnJH379+PbDbL2pTNZtHQ0IDi4mLMzc2xGORVVVWoqanB6OgolpeXYTabUVVVhdraWqysrGBjYwOpVAoulwsNDQ2YnZ1lVvhOpxNdXV057l3ippNvftB7sdlscLlcWF9fh8PhyNGzBgIB6HQ6bGxsMEnnq8B5/0jiYuCvidf538RFrBQplAcmtXr4+pTqEW1Q8vVLxsrzv8naIwIjXw4vovGW1uQcS6d/JpMJWq0W0WiUicMUcSIajTJHaToNBYCNjQ22g1qtVhQXFzMLZbK4r6mpQSqVwvT0NMLhMDQaDWpqalBeXo6hoSFmCuFyudDW1oZYLMZCwBiNRlRXVwMAHj58iFgshng8jvr6euzbtw8LCwtYWVmB3W6H1+uFzWZDKpXC5uYmC93sdrtZ7PtYLMYWGelgyLGZAiI6nU5UV1ezfun1ephMJmamQSYuZrMZbW1tSCaTDOiMRiMqKiqY+QaBRGlpKTvFNRgMsFqt0Gg0aG9vzzG1MJlMaG5uZpwetauzs5NFyyCdkM/ng9vtZv2ksaaAkEoB7PKJ9Py84qPRer1elsiBbMX4KLnhcHhP/PV89NwDFcV6EsU6GclAS0mHIePQeNsavjzxD/iCwxPFRFG5ypfDB9kjgODdFDKZDNMDZLNZljWGWH8CGqfTyU4oSQQgX8PFxUWsrq4imUzCbrejubmZRZwkUaOtrQ2lpaXo6+vD3NwcUqkUqqurcezYMSwtLWFmZgbxeBxGoxE9PT0wGAyYmppi/pBerxdFRUXY2tpiyUudTmfO2JEoQqK20+mEwWCATqdjYWGsVis7qKCMJmRrRuNFC76xsRF1dXVMRKPF7nQ6mR6S3suBAwf2iIQlJSXweDw5cdO1Wi0zcuX1ZjU1NXvmkNvt3iOiFxUV7YnHJFrz0/PEefDz0WKxMAt7mjeU3YXuJbMSitpBdVNkWn6Oy/RRSpsh9YMnAiwSWRcXF5kLEomqpaWlcDqdzNePj2KhRs89UNHLUhK3+Pv4ScADCfCFjoEcgGkXzWazLJAdDwh6vR52ux3hcBiBQIDpHbxeL0wmExYWFpjNlMfjQUVFBVZWVrC2tga73Q6Xy4Xi4mIkk0mMjIxgc3OTsfM+nw/z8/OYm5tjzshtbW3IZDJ49OgRtre3AQDNzc1obW3FxMQEpqenodHsWj4fOXIEGo0G09PTOSePLpeLZdYhUQvY3a0dDgcDCIfDAZPJhMbGRhYJlRZDZWUlc67W6XQsNPKBAweYCE0Zcbq6utDR0ZGz8LPZbE4YHXqmoaGBvSciMlLl3x8AOByOPRsLLRY+uQPwxU7PbwBiPUTiCaySnlBc3Pl0ezISjVrFTZTeDf87nyeP30z54Huy+gvJK8A/wz8rU11ks1kWx39mZgYtLS2wWq1wu91wuVwoKyuD1WrFzs4Otra2FOvl6bkHKt5RVUn0y2azLFlDPB6HxWJBdXU1kskknjx5whSmFRUVaG5uxszMDCYnJ9mu3NraCqPRiLt372JrawvJZBItLS3o7e3F+vo6pqammChAoUBWV1cRCAQYN1RWVoZwOIxgMAi9Xs8iD2g0GgYQlHKIfNlIoUvtoKBxBJQ2mw0mkwnt7e1oampiY0CxtXp7e5mIAOyy5U1NTcx9h5/IBB408QHkJHqg+0nU4RdQJpNhIowYepk+6V4+IQLv90fvUgQH2SKWkSjeivfLflMrM199X+Z+EUj4hS8DQlHxLXL4Mu6e9wig+cWbZIhW82LbxWtKelmdToeysjL09/ejqqoKer0esVgMq6ur8Pv9zG/2q5Tu/0j8ka1MQajVaplby/z8PNM9eL1eaLVa2O12lj2DTltItjeZTDniw/Hjx2EwGJiIotVqUV9fz1xeiCPTaDTo6enZc7ze0tLCko5Se3U6HZqbm9nzJF663W4UFxfnGHwSxwbkTjoSdcTdVnTM5Sc3DxD8IhbHkK7z9lzUH9GQlEBLfJZ/F3zfZb9Re2Sf9KzawhK/q12TkRLQqd0ra1e+ckWQkm2uoihJc4HnxnhOkd84RCNR/p0RiTpTkQOUcVr8d8r3uLi4yHINULw30u8tLy/nHUfg5wCoZDuOOCnoxIbnOkjkOHjwIOM4aOF6PB6UlJTkLECNRsMiB1AdPHfA20SRslo0GhW5BXFC0rP8ZCJ9lDjh+H6KYAQgB5D4+2U7JT/xZQaK4qdsMj8LEIjlP0t5SiAlcmD8/TLRTdYusU2FiktEMhWEjINReg/8M+K8AZATvUN8Rvwu27RlXKUMpGTzVIlDpRRblCwknU6jqKiIxUyPRCKKY8jTc2/wKTtilU1gg8HAlLE8l5PJZFiaJqJMJpMThoRnd+l/PnccL0bxRoL0P7VHnID0yf8p9Ul0cxFFA9niFMsVRTFxJ+fvEcsSx1bpf/463zaRE+DLFcdELEOpDiIlr4RC+pevLzLQlr0zsc1K7ec5WX4zoSS5BEay9vDx6MXfeUAU9VWyuSFeV+KelMaF+qXX69HY2IhwOMyy8XR1dcHpdGJlZQWbm5t7npXRc89RydJhy8AAyAUA/mVqNJo9SljZy+aBSfSi5+sWOSW+DNkOSiQuZP4Z8Xm+TLEONdFJaWzEZ8Xr4v1qXIzYBxnJ7lfipvJxUeJ9sjaJ4y4ru1CuUI3EPszOziIWi7ETTFJFLC4uoqysjPmLjoyMsM3IYrGgo6NjT7t4cS4YDMLv96OsrIwd9sRiMRbhgE6JZfNRxlWpbRbiM/waSafTcDqdsFqtiEaj2NjYwNzcHDY3N5mNWyH0cwFUfFps2QInEgebZ7Nli0T8Xohlr9LCF8uUAQYPjrwilBfJ8i04nmUHcsURGZdFJDN4lZHYHlLsKz2nBKpKIoj4DE9K4y4bZ9lv+fqWr2w17lG8P5PZzYp848YNlp35/Pnz2L9/P/r7+/Hpp5/i1VdfxYEDB+D3+/H222/D7XbDarXC4/GwFGl86jYCsmg0is8++wxjY2P49re/DZ/Px2K7379/H9/85jdZnDJZ+2WuQWqgLr5D/nfarGtra3MySe/s7MDj8exJBKtEzz1QiYpFcVHyJJvQPMDxO5fSc7w/F9WjRPmATLxXnEiyZ2Tcjdp3Ebx5HzE1zkwGqJlMBsvLyygvL4fRaMTW1haCwSA7TBBDn/Dl8sApWrHzej+1BULXnkWc459/FjAT55N4P/+cjHtLp9NYXFyEx+PB/v37cevWLTx69Aj79+9nmXa2t7eRze4ehrjdbpw9exY+n4+521BZPAcTj8dx//593L9/H4lEAuFwGPF4HCMjI7h79y5WVlYQCARQVVWVM74yP0vRlkwNlGUbKz+PiouL4XA4EIvFmNNyJBLJUamo0XOvo+JFP36w1Sa0OOnz7ZTiglESa/jr+RYPDxpi+4i7WV9fx8LCAgKBwB6lrPgn1g/sOmxPT08zmzAepPi+iGWJfSAxNxaL4f3338fa2hr0ej3m5uZw9+5dVj6lMefrUVPOZ7NfZJOhfhcK7rJ3rMQRiuOm9Jt4ndovc7YWnxfbrdfr0dvbiwsXLqC1tRX79u1jvoM9PT1oaWnJ0TWFQiE8fvwYd+/exePHjxEKhQB8oZvMZDJIpVIYGhrC7du3UVlZCafTyZJnfPbZZzAajSgpKWGGu8TxiA7Mav0ohGsk4nVpZrMZ5eXlKCoqQmtrK7q7u1FWVvZVcgeeePFNXBT5xC/xBclYfyWxSFYX/xxdVwJDpbam02ncunULn3/+OctSc+nSJZb6StY+/lSQPiORCD755BO8/vrr8Pl8OeKrRqNhRqoEYrwNlIxrAHZTvfv9fmg0Gvj9fpa2i7LbuFwuVkcoFGK7qk6nQ0lJCUuVRanXq6qqWOhhpXcm/iYbO5EKEfPUnhE3ECWAU/uNDGM3NzeZXR6Bh8PhQDweZ+Ou0WiwsLDA9ExarRanTp3KsYECgFAohGAwiLKyMqRSKYyPjzMTgZqaGhiNRoyNjaGlpQUOhyPHAVo2t2XjJ15XkwLoU6PZtd/b3t7G8PAwFhYWoNVqvwIqIhpEijBI19TED/G6rEwljojXFcjqEAFNjWOTtUmr1WJ6ehpXr15FQ0MDampqcOvWLQwPD6O0tDTnRJLcMch3jU8fFY1GmaPt6OgoO5HZ2NjAzs4O42a8Xi9CoRDm5uaYC0xTUxPKy8tZ+3idVCaTwdzcHJqamjA/P88MPYPBINbX1xmrH41G8f7772NxcRHArsvMm2++iWQyic8++wyRSISJjW+++SaLn67ErYrjJYJyoe9P9nu+9yOqB5QAjR8vYJfb9/v9uHXrFhYWFnDq1CmWjt5qtbKxohjwFRUVqKqqwqeffoqVlRUW2pdAKpPJsDj1ExMT8Pv9LAW90+nE/Pw8y36zsbHBfO1EgFfaUPNtpjzHLb4HjWbX84Fi9O/s7MBgMLB8kPnouQcqYs1l6K8knon38aQ08fN958tW22ULKSMWi8HtduPixYuoqKiAzWaD3W7HwsICHj9+zLLCtLS0oKurC9euXcPc3Bx0Oh3Ky8tx8eJFbGxs4Pr161hfX8ft27dhMpng8/nw3nvvIRgMMu7q3LlzmJqawsLCAoqKirC+vo6VlRW8/vrrexI32O12lJWVYXFxEfPz89jc3MSJEyfYfQaDAfF4HBqNBoFAALOzsygrK4PX68XOzg6LNU8TPpFI5IQDEcVYcVxEXVa+MZeRbH6Iz+bTS+WrhxZuPB7HwMAAhoeH0dnZic7OTsZt6vV6BAIB9r29vR02m40ZI1Ni2kxmNzGJ0Whkm8g//af/FH6/H5999hmKi4vR2NgIs9mMWCyGgYEBZLO7WW9Erljsv9r45AN6vq8kmup0Oubv5/F4sL29zdy98tFzD1Q0aGr2VOK1QnbsnxUp7VLidV7pSTK/xWKBTqfDoUOHkEgk8Pbbb2NiYgItLS2IRCIYGBiAwWDA4OAg6urqUFpaypxAKyoqsH//fmxvb7PsLrOzs0ilUvja177G9BsmkwmPHz/GgQMHcOTIEXz++eeYnp5mTsfUBwKKpqYmXLt2Df39/QDAMqqYTCbY7XYWeYCy8szOzmJzcxM6nY6B4NLSEktBRsDF2wfReOQDjHzvil+chSxAGfH1KLWJJ15Bvby8jNu3b8Nms6G9vZ2NJ41XNBpFOp1GNBrFjRs34PP5sH//fsYhJ5NJRCIR3Lp1C1VVVejs7GT+oNXV1SwnpNPpzHF+HhwcZIlYxYMipXETx6cQLpVXJVA4GYvFgpKSEmi1WiwsLLAwN/nouQcqIpmTJ/3PfwLqXBcvUqiRKKI8C/jJ6uDFGF4vxsdZTyQS6O3txdmzZzE9PY3r168zJevs7Cw2NjZQXFyMeDwOt9uNxsZGDA4OoqamBsXFxRgbG4PL5UJTUxPTHQSDQRYD3u12o7y8HNPT03v6QG2prq6GVqtl5fIOyqRwz2azKCkpwfnz5zE5OYlMJoOnT59idHQUiUQCdXV1OHfuHJ48eYLh4eG8QKKm5+N/50VU2fjme0eFchv8M3RdVvbm5iYWFxdZ9iK3243Tp0/D7XbnpD83Go1IJpP46KOPMDMzg83NTZYLEgDGxsYQiUSYbRWJ+DabDcFgkHEzmUyGidDi6WqhHKcSGCsBGOkntdrdIIKRSAQzMzNMdP3KPEGBRCX2s5BodlDILpTvHrFN9MmDEj+BKPYT74Kzvr7OdHAOh4NFMkilUigvL8eRI0ewsLCAZDKJyclJTE5O5vgE8m3g7bP4lOyxWIyBHi0gUQek0eyGM6moqMDDhw9RW1vLuATSOVGkynA4jHA4jJaWFgDA/Pw8qzsQCGBlZQV+v58pe/nxURrjfO+lELFcRkqLWE1/k4/jyGazKC0tRU9PD0vRRfrEbDaLyspKNuYGgwGnTp1iiUHKyspQUVHB/EpPnjzJFPF8+VVVVSyLEIF0WVkZyyWp1Bc1EnV/vA5KVia/Zii/pcvlwuTkJPOlLYSee6DiXVV4PUY+Utu5CwE5kStS4pAKBTOxHaSczmQyuHHjBkpKSpBKpeD3+xEIBLC5uYlkMolUKoWKigrs27cPOzs7ePfdd1k0CI1mN78apYzX6XRYXV3F3bt3YbfbsbKygqqqKiQSCdy/fx/hcBjj4+OqdlwUTWJ6ehr19fUsOeri4iKWlpYQjUZx8OBBZLNZ3LhxA36/nyl1KQP0+Pg4rl+/zkLYmEwmKeA8y+LKRzIVgRr4iJuH+Kx4n4y7rqysxC/90i8xDhkAc70qLi5GT08PK9/r9cLr9e5J8kDxs0TgoPdeVlaWU3dRUREOHToEk8mU4z0hc1CW9VUcA5nkIOtzNptl+SP1ej18Ph+2trYQCAT2jJmMnnugEjmofJNbfOFEImurpFuSlSW7J58uQPYM7YpWqxUbGxv4yU9+gqKiIqytreFrX/sazGYz7t27h+XlZRbNMhwO491332UBBLVaLTvupwiQkUgEGo2GWQp/+OGHLEBdbW0tmpqacP/+fQwMDAAADh48yML+ikBMsaMOHTqEkpIS9pvb7cbJkydZMD+z2YxXXnmFhfug+Fa0y5IeS6vVMnGF6pIZ1MrGUikGk4yUFqf4Kd4r47DV3qX4HH88z8eFImt+MpLlo1Pw/1M9vNsWbTrEZdM4EBjy+R550Yxvt9JczjfuMnGagNNkMrFgf/X19chms9jY2FAco5zxyhay3fw/SJTX73vf+15OOBPZxBInGX+vbKdV4raUuDW1xZFvIYivR6fTIZlM4s6dOxgeHobdbkd9fT0OHz6MlZUV3LlzBxaLBVqtFtXV1aipqcHjx48Ri8Wg1+vh8XjQ1tbGTBQmJiZQWlrK7G7W1tbYKRLdn0wmWRhgjWY3PhaF7ZDpLDQaDaLRKDNNII5WzOzDLx5+sfB2abw+TlaP0kYg+y7bgJTGXklMVOOm1ermyxKf5w9KaB6RbRkPPuQgT/ZHIljxfcxkMix3JH8PpXyjwwl6h7K5qzTPxU/ZNZm5xtbWFv70T/8Udrsdy8vLzN7u9u3bX+X1A+QZYXkqVORSI1GMI8pXrigSqrWHPxA4efIkDh8+zLgOnU6HyspKvP766znGe7wOg3+eJmxLSwvbfQEw3RXPKRmNRpSVlbF28KePsv4AyAEpAhulsCKinkumR1TjbsXyRIdypWfU9E6yPtHvSsAlE+MLmVc8WBCg824tVOfc3Bzu378Pu92OkydPspDSorFmMpnEwMAA5ubm0N7ejtbWVuh0OoyOjjLDT8pyzW+UYl+U1BdqLmTimPC/GwwG2Gw2eDwepqsUszop0c8FUBHCFyqKqU0upcVRyL2F/Kb2DO2wBDR8QH7+hIgmPvCFewsfOkQM+UGf/KSV+YDRBBSvid9lk11tnESSievi8/x1tQ2o0Hr4MkWScVl8GWpgmq//hfQhm80iEAgwuzfy33vllVdYtFYirVaLqakp3LhxA4lEAmNjY/jOd74Du92Ozz77DOFwGH19fXjttddyEkaoqSJEdYgaIPPfxblF5iaU948PWZOPfm6AqpDr+TgrceF9GbARf1fTmSlxWjxYAV/EwRKt7+nEiL7zdYTDYZjNZhb2OB6Ps0QQ4XAYyWSS5WJbXV1lri7pdBp2u50pvtUOJwoFJnFnl5UhGyeqWwQSPraVaCck1iuWqXSPkniotoBl/aD28XOoEC5ufn4eCwsLePnllxEOh3H79m10dXWhubmZbVJUztDQEKxWK15//XVcvnwZjx49gsfjQSwWw4ULF/Do0SPcvn0b1dXVzBKer4vnGmUbOd8fnpuTjTPNPWA3Pj21w+VysXwChdBzD1Qyd5ZCWXI1UhL16Ld8gJevbKXrBA7kkJxMJuHz+VhKqcrKSpSUlCAQCGBoaAhHjx5FIpHAvXv3EAwGcerUKVgsFly7dg0NDQ1ob2/H+vo6Hjx4gI6ODly+fJm5uthsNrz++uu4evUqtra2WEjm1tZWeL1eRT8tmd5K7BMPuEpgJHJWSu9NfI73RlDSSSmJgmpchdI1UTwS26S0yNXGiL9Hq9UiFovB6XSioaEBBoMBjx8/xtbWVg5IEgdM/p8tLS3w+/3o7++HwWBASUkJWlpaYDKZ8MknnyAUCsFqte7RkamRGuDTdxGAefHOZDIx2y5KOlEIPfdARQMmmxz5ruXTOahxQz9tm9V+W1tbw9/+7d9idXUVJpMJLpcLL730Eh49esQSRezs7GBoaAhNTU24e/cuPv30UwC7Cs0LFy5gdHQUCwsLqKioQDQaxfLyMmw2G3Z2dnD27FnY7XbcvHkTa2triMfjOHbsGNra2pgilxI45OsHz82JO6+ayCVek3E0SnXyXFS+hSUDLRE8lbgjGfckumspgWQhojD9ThwTxZ+iOP3kC0hKcQIrSpmu1WrhcrmYF4DVamWnvna7nWVqzscVy8ZLxj3KRF8ak2w2y1KcaTS7DvGrq6tfOSUTKelTgPxil9LEFRcZff6sODVZm/g2zM/PY3t7G7/wC78Ap9OJTz75BAsLC4hEIkwnlUqlkMlk0NfXh76+Ply6dAl6vR6fffYZM8ScmJjA4OAgS1YRCoVQXV2NQ4cOQaPRoLS0FFqtFk+fPoXRaGSZbniraCXRSO2UtBC9jficOLbis7LfleqX1SfbgNTENyUxRwn4xOeV6pT1jRzJt7e3madALBZjBrmieGswGLCyssIMRqPRKABgZWUFkUiE6Yso8zLfnnzSgNK4yMRh+p83g9Dr9YhEIixvI7UtHz33QAUoKwTVSAkolBZAIS9Y9oxam8VnaDKm02mWusvlcrGEjiMjI8y9ZWpqikWOLC0txfHjx6HRaDA7O8t2Ur1ejydPnqCtrY3VRT53V65cQSQSQW9vL6LRKG7duoX+/n643W587WtfY+BW6LjJ+qfEJaktdBlY5dsgaLE863iL1/Pdr8R9K3Fg+crmOVLioCYnJ1FdXY1AIMAW++bmJpaXl1lG5KKiIty/fx8TExNYXV1FIpGAx+PB48ePMTk5ieLiYgZYMolDTWcm64M4P/nrvPmJTqeDy+WC2WxmBp9f5fUTKB/Q5JvoSjuoWH6+stTaplY/tYH0L+SQDAA+nw+bm5vIZDJ48OABxsbGEAqFUFxcDK1Wi7W1NfzDP/wDstksszY3m83o7u7G/Pw8njx5wiJGArsGgZRyfXNzE1qtFj6fD/X19cxYU6kf4pip9Un2HP+/bOLL7lEqV+m6TMxUu79QKlQXpfQbvV8ZJ1laWor6+npcvXoVtbW1LHyLRrOrCvjxj3+Ms2fP4syZM2hqasKdO3fw/e9/H0ajEQ0NDWhqasLIyAjef/99lJSUsIzV5CKlJq7KxkmMwaYGytQHskoPh8NYW1vD6urqVzoqnkhRKLOvUaJnBRuZbqtQvUq+HZa/j1+gZAhIqbH1ej0OHz6M9vZ2jI+PY25ujoUB2dragl6vZ8HYDAYD6uvrodHsGtzV1dWxDDwejwcXLlxgcalMJhMOHjyIgwcP7smqWwhHo0YykJKBkJK4LY6bDPRFkUytfv7+L9MX2TsXuXm1Nor9oXKMRiNOnDiB9fV1RKNRdHZ2oqSkBJlMhoX5IXcll8uF8+fP46OPPoLBYEB7ezuKiopw/PhxbGxsIBwOo6enBzab7UtJBUokuhLxnCz1iTI92e12+P3+HBMbNfq5ACoaJJnrhXgP/aa0M/CkNDH5TzU9hxrJyiYxgJSoFCN7cHAQmUwGRqMRTU1NaG9vRywWw9zcHLLZLBoaGvCLv/iLSKfT+MEPfsDsVxwOB7q7uzEwMIB4PM4CuQWDQSwvL2N5eRklJSXIZrMIBoNYWVlBOp2GyWRi19VAQ62/MtGIH2eZUSFfD3+vKL6IY6YGGGptlLWZBxOl8mRcFS1avqxC6ya9Y1VVFb7zne+wE1lys6moqMC3vvUt2O12Vk93dzfL9u12u6HValFTU4Nf/uVfRjKZRHFxcU57RROFfIDFvw9xvfBjwxt1kq6NVA9FRUWIxWJ5+w/8nACVGEaXXoKS64ASKSkcZaCnBIgiqU1YJWCkKJ8PHjxALBbDgwcP0Nvby/pDET5TqRQ77XE4HEgmk8z1BdjVUVVXV6OlpQUrKyswm81YXFzE9773PWxubiIQCMBkMiGVSuHq1au4d+8eNBoN2tracOnSpT27oRpI5QNtccIXururcaP5ONp8Ineh5anNBbFPX4b4Oed0OnPCD9O4lZWV7eFe6NCDF7vKy8tzTDfyccQyMVz8jS9HtG0TuSu73Q673Y7i4mLU19djbW2toDF47oFKhvg/LburBEyFyPrPWp8IrhqNBj6fD8lkEn//93/PdBU1NTVYXFyEwWBghp82mw1Wq5XZqxAXVVRUhEQiAZvNBqPRiAMHDsBms6G5uZkZdxYXF8NkMqGmpoYFaCPxorKyUjGWkTgGIiehNqZq4K6kA+Gv8f/z713kcGVlFaLbUmuPeL8MvJT0Oc9arggudKom4/IKbZtaH5XuETlh8ZqsTVqtlvmUrq6ufnXqR8S/VFFEEBdHvt083zU1sfKn4Rb47xqNBtXV1fjud7+LYDAIYDdaZ0lJCWPzAaCqqopZllOwOtJzUPRICkfb0tLC4mq/8sorLPOLRrOrB6urq2P+hLwzseirJeufuLDyiV35xjgflya7V8nXUyZyyhazjNQAU4nzEOvKV67s/fPlKc03MUikjAppU755KtsIlJ6n9vPRM0jdUAj9XAAVP2CiAyd/H1EhIEX3qynolSaaWt357ifxrrm5mWUnyWZ3dVctLS3suaKiIsYB8cHnyKzAZrOxMg0GA4xGI7LZLGw2W07f0uk0LBYLAyVeXObZepFETpYfHxloqe3ySotBxnUocQ1qm4TM36zQd6K2kJU2Gr4dPKjkq0upLCWSvQP+uqyNMolDrS4ZaMoAkueoyK3L5XJ9FYqYSCb6FfKilRZLIWAksrxqVIjeQkm0Eb3rxfaJoTz4T3pOFBtEXQMpbPn8iLLYRUqiCo1HvnFQWrCFAgHdqwRIIlet9Nyzkqwe2T1fhmPh73sWUgIatY2zkHYotUsGUqK0Qvfr9XqWKaeysjInEKAaPfdABchZZCXkJ8rHnsteBP+77Dpfd76JorajK+1YIuDw4ViUJi+vgBcPHHgOheekZCy90hiJfVZa1M+yaYhlFno/395CAEaNCuG6+Tp5gOfboBZR9FkAKt98+bJlydYM336R6B41vSTFN1tdXUU4HC6oTT8XQAUoL3IlwFACAnH3EEm2i4i/KU0acTEr7fziBFTiFPig/lSe2PdsNpvjK8bXQQDGnzLx0RnU2s4TiabPAkaFiB9KHIJaO2SfapzYz4KU2iKOmRpnqlaGeO+XaVshgM/PPdm9Sps/3wcS/ej0udCU7j8XQKU0QXlSWxhKi0h8yWIZaju2EsDkWyQiWPFliddF3YsYX0qtXfQ8f9xcSNuUSG3BKY2zGv00oprs2pflOgoZF/EZ2Wbz05Da82qbntKzsvche39qm4usjRqNhmUjikQiOclT89HPBVDxJHIshU40NUBR273/T+/O1C4x4ibPfouTMt/CKAREn0X0U+JSvqzop7S41PqVr5353peafudZdE2yTS4f95ePW1X6XY0DykfPMm/V1hDVz3uH2Gw2JBIJmEwmhEKhgur4uQAqceGpcTfAXsVrIYtOJLE8WX38vc/Sl0LpZw2SYjuUJqiSaKrUHjUQe5bF9tOC1bM8I7bzWdpTaDvF5Bn57v8/IbZS3YWInnQv3yZxHdFvFKDR7/cX1IbCzbL/HyVxoj/Lzi7bRfmXJltEP63OQEZqE6VQ1lkUN2QTTLyeb5fOx2XQ87wSWek+te/5+lMoie1V+5+/JvsD9p52/ayIX9jP2k+aE/nmhVLZ+YC30E2a/y5yfWazGQ6HA16vF7W1tXnLA35OOCqeRA4p38LkSYkzkHFcahPsy+glxMUhW1Rq/8vamq8+sZ2y3V1JTKTfstms9LSQL09NlMonYqq1XySRo1ba7ZXE62dpB1+HGqDLrosboWxuycaFT6MlcrVKG61sHShJAuLvsntknLZG84UpDZnDbG1twWAwfCX6EfE7Rz72lb9PtlCBZzuW5usQ75WxyIU8L6tTCaTUuJdC6pCR0oRWA9+ftUiSDzxlpCSS8L/LwEpJtOE5RTXxV+lavvcncqTi/Xw/RN8/ce7K5r9SW2TX8s1NcWxFkKQ2kijrdDphtVqRTqe/AiolEl9Avt1BpEIXhli+0kvky5XtkuLuyN8vA1Exomm+Uz5ZuYX0VcaNqNWjxjWpUaHvIF95SqJePrBVKlepLrUIHfn6wF9XAgBZm8Usx2qgRG2k60oRHZQAOl9fxH7xa4D/PRQK5Q1myNNzD1TPwuqK94vXnmVh5GuTGiDIfsvHHdGElU0U/l5Z+BQZ4KmBj9pOrQSssv9/1qQ26ZUAVcY5i2MpijOyucDfVyipgSN/D/9d5KYAMEdf/t3y4MXb0sk8AArdDAoRBelZEQTJVzSdTrPsRwC+MvgUSWm3USKlna4QsBLdVGRtEX9TAimRhRfLUPpf6Z5CdjA1J14R9EWxRKm9Yh+fZUErga/avWJ7lMZOadyVylcS82TjpVR+vvaKZdI1nhOiCBkGg4EZ5RJgkYdBOp1GLBZjIYv5jYUU7rwLFf9/IVyh2H8RoPi+8QBJTskUzaMQeu5P/URS4p4KXdR0XeQqxDoKlfF5kp3WqIFTISTbgfMRPyb5+qfGXSiJIEqLWqn9P01fCilfDSxk71v2nBoQ5QMpvg6aA0r9TqfTmJ6exuXLl3H37l0kk8mc54l7ymazWFhYwJUrVzA7O7unjCdPnuCzzz5DKBSSgiI/Dmr9ks0R2cZCQKrX62Gz2eByuVictELo54ajUtvNxQWkJvYUUg5vAa62+/PPAIV58atxXGrsPN83pf7xLjdiubRTitdEcZPnWvMt0J+VKK1GMpAR685HsndeyJgr1SPjOvNxy/R+BgYGcPv2bRbON5VKsXj3Ioc0NDSEmzdvwu12o76+nr2vgYEBXL58Gel0Gl1dXSgqKlLNgyiSGigp9ZUv32w2w2azsaS2hdDPDVAR8S9DnGRKXJUIUkrsPz3POwI/C0jxdfEvVrRDkrHmNBnEvpJuANjdSWli8GXwp1e824wYGVW2U4r1ideVFl0h135WpMQZK9VZCNf2swDVfKDAt5uSzl6/fh12ux0vvfQSSktLYTAY2HujT7q/q6sLY2NjSCQSrJzp6Wlcv34dgUAARqNxT24/2eahtDnnm9tK64vyEvr9/pykImr03AMVP/mUBk72ItTEk3wLVwQXXocg20GB3YlCqdQBsASRGxsbLEGDyWRCeXk5otEoAoEA7HY7DAYDlpaWUFNTkxPwDtgFpqGhIUxMTCAejyMej8Nms+HcuXNwu9057eRBjr7zsa4LBV6R41Bb9IWAWD5SKl/GPcr0KEptEcuiz2fR3Si1lf/Og4HIrYpzcGlpCdvb22hpaYHZbEYymWQZgfhMxwRYFRUVaGxsZIETE4kE7t+/j2AwiJ6eHkxNTcHv97OYZWJbCwVRNTWAKErS2BsMBoTD4RwQVaPnHqiIZAtIdLqV3Z9MJpkjpfg7X1Y0GsXU1BTKy8tRUlLCnh0ZGcHS0hJ8Ph/a29tZOeLLHR8fx+XLlxGLxWCz2XDmzBmk02l88sknSKVSSKfT8Hg8uHjxIu7evYvHjx9j3759KC8vx8TEBN58800WI5smg0ajYSE1xsbGUFZWBp/PlxOpk28HD0Y8Z/esoW6VwEMmjvK//TRcihKXLNYl25z4/8Xr+dopA+9CwFMm/tF3NdE8GAzi4cOHGBsbQ2lpKV5++WWWaEPcdCiZAp2sZTIZhEIhbG9vY3p6Gtvb2xgYGEB7eztMJhMDOv6AhOe6ZaAvGyN+nPhPvu9OpxMej+ervH4yEsGB/xMnTTqdRl9fH+7evYuamhqcO3cuR5YnymaziMfjuHHjBh4+fMgmDgCMjo7ivffeQyqVQlFREVwuF6qqqva0y+/348aNG/D7/WhsbMTU1BTu3buHyspK6PV6HD9+HHa7ncn2m5ub8Pv9mJ+fx9zcHAs7zPeT+tHZ2YmqqirE43EcPHgQR48eRTqdxvLyMuPWLBYLKioqEAgEEAqF0NTUhEAggLm5OdTU1LDwxrKkAAD2gB4/jmq6C7X/ZVSISKYEGmI9P0vR8llF3S9DlOLMbrejtbUVRqMRT548wczMDEpLS3Pqoc2QEjpQ7j6z2Yx9+/bBaDQiHA4jFotJ8/OprQtZv2X9k601agdxVJFIpGBfv58LoBJZdv6PJ/5lP378GB999BFisRgWFxeh0WjwwgsvMEAQFyplZCEOLBKJoL+/H+Xl5Th8+DCuXbuGkZERlJeXMxsSIoPBgP3796OsrAyVlZW4du0apqam2EQiPYRGs5vfrbu7G0ajEYFAANFoFF1dXTCZTDlKfJpYRqORJSulCRyPx9HX14eBgQE2cU6cOIFMJoNHjx7hwoULmJ+fx9jYGL75zW+y1EoyZbr4ydctI5kI+dOIe/meVapLSYwtRASk+2TB4fKJuErlKwEB306TyQSPx4MXX3wRdrsdOzs72NnZAQCkUimEQiHY7XbGHRHnnEgkGJfU29uL/fv3w+/343vf+x6amppgs9mYHZZS+3lui2+v0hoS3w09S/PTZDLBarUW/O5/LoCKKJ9Oin5PJBIYHh5GWVkZXnjhBQwNDWFmZgZ+vz8n3RSJRSaTCQcOHMD8/DyAXW5sa2sL29vbOH78OFpbWzExMYHNzU0kk8kcoKKdrru7GxqNBuFwGPPz80gmk4jFYpiYmIDf74dGsxvL57XXXsOhQ4dQWVmJH/7wh6ivr2eJREWrdL6/fBA8UmbabDbE43Fsbm5ibm4Op0+fxvDwMN59911ks1kcO3YMXq83h4PKp6PJB1Kycf9Zk4yLEoFJqZ1KHJfSAlbjJvJxV0qLnRe3eaKs1yMjIyguLkY8Hmfx8NfX1/F3f/d3OHv2LHp6enI4JdIDaTQaWCwWZsdktVphtVqRzeYahSoRAZbYZhkjwD8j29D0ej1CoVDBoYh/7uyoeBIHlU7IUqkUNBoNOjs70djYyFhteoZnlem7Xq+HwWDIOWWzWCwoKyuD0WiE2+3OSRzKE+3O0WgU165dw9DQEMrLy1FaWoq6ujqcPXsWx44dQyaTwdbWFnQ6Hebn5xEKhbBv3z6mUBX1AXx7yYYFAILBIIaGhrCxscH0X7FYjOnRNjc3AQBtbW0s6YOS7oTvg2x8ZfflK6tQ4ssS+yy7VyZuKv2J9yi1WXZdTUclls3fz3Mroj1VNrubDMFkMuHKlSt4//33sbOzA6/Xy0CJNkd6XqfTMb86HiiorrKyMnYAw3NU4jjIwDXf+5aBFT8GBoMBHo8HPp9vTzkyeu45KnFg1cQ+onQ6jUAggLt372J+fh5ra2vIZrNs0YpiDnE7wK4YR/XQRKNkoARiIhus1e5mPP70009x584ddHV14fTp00ilUqioqEBtbS1isRgmJyeRze4q7oeGhtjkXFhYYLovEUCpPtJXaLVa+P1+rK2t4dixY6ipqcEnn3wCg8GAWCyG1dVVBpqrq6uoqqqCTqdjIq3SGMs4UzHBq9JO+yxJYAslNXBRIxnIPIu+LV99Mq6O51Z5kOHv0Wq1KC0txXe+8x3GYWs0GrS0tAAAysrK8Ou//utwuVysPel0Gm1tbXA6nQByT3Z1Oh3Onz/Psg7RfCTgIhLFfbGvSpyx+JsMtJPJJAKBgOp4ET33QEUkDqhMDAG+sA6PxWLw+/0wGAyIRqNMz8NPKL5MEq2IiLVdX1+Hy+XC/Pw8HA4HOwre2dmBRqNBcXExUqkUHjx4gNu3b6O1tRWXLl1CcXExxsfHsbq6ioqKCkQiEcRiMWg0GoyOjmJ+fh7pdBoffvghKisr8Su/8ivMJkXcoWmn5F0sSDw1m82IxWIwGAyYmprC8PAwDh8+jI2NDdy4cQMNDQ1wuVzSUC1Keik1TupZdEQ/jVj4LCClNCeU2vhl2ydrk2xeyu4j0G9sbGQbEG1+6XQaJpOJqQD4flgsFmnMJ41Gg9LS0pw8jUp9E7+L80tGagBG9Vmt1q/y+vEk6ldEot9IYUhKyJdeegkHDx7E3Nwcbty4sYebEneeeDwOk8mEbDbLMhLfuXMHS0tLmJqawptvvgm9Xo/19XV8//vfR2lpKV5//XVEIhE8fPgQwK7yu6+vD263G9FoFJcvX8bY2BiSySRmZmZw4MABPHr0CPX19dBqtXjw4AECgcAeJTrPRVH7aFLYbDbU19djYWEBy8vL0Gg0KCkpQSKRwP79+3Hp0iVsbGzg/v37DODUFqzMPkzGPRUKHEq6n2eln6YMJT0RT88CqqKORlYGbZJiAlFxftK9vKmLWCb/DG9jReXT4QoPkErAk08CEa/nAylgd87Q5lsI/VwAFSAHK3EgacGRiFRaWgqn0wm73c7SSalxEXSEDOzqp7q7u/HOO+9gfX0ddXV1aGhogEajYTohUWeQTCYxPj6O2dlZ7Nu3D/v27UNtbS1SqRTMZjN6enrQ2NiITCaDyspK5qdVV1cHs9mcI+7w7L/BYMCZM2fg8XiQzWZRVFSEl19+GZFIhI2Jw+GA0WhEc3Mz7HY7bDYbysrKYLVa9yhQZWMocgT53oPa7/lIBENRHyd7N2K71erkyy1E3BOvq+lxlHQ7onglBprj30Emk0E0GkUqlYLD4WAJPWXlxWIxJJNJ2Gw2BloEXMFgkJm88PNGpiaRjUkhXCffJhGAHQ4HE0vz0XMPVDwQAMqGgfx1nU6H8vJyFBUVAQCsVisaGxthsVikx7jEivf29sLtdjPdVEdHB2w2G5LJJKqqqmC325HJZOB2u/HWW2+xTMZFRUX49re/DZ1OB71ez16ozWbDL/3SL7E6tFotzGYzent7YTAYkEql0NDQAKPRuMc7ntpEz1VXV+dMFrfbDbfbvWe35kUBmsAiu1/IAs63YHkSxz/fu1QqVxTdZP8rccRq7VcjcR6IfcpXlhInpCR+plIpTE9P49GjR4jFYnjllVdQXl4OYK8+aXNzk0kCL7/8cs6B0MzMDG7cuIHe3l50d3crjofYTrFtYv/EMmRio/g+CqHnHqhkg6I0IYhrMhgMeOGFF+ByuZhF+JkzZ9jOJS5qYPcldHR0MGVkJpOByWRiyk6R7abTGirL6XTueWmZTIYdH1O7xcBslMlYFK944BLFC1HBLf5OAEeApTb5qF2y67L3oFaO7BnZ/YWAiJJYJhO7ZL/nA818bVVbuEr35rum0WgwOzuLTz/9FH6/H62trczGTnzP2WwWy8vLePz4MUpKShhXnslksLi4iGvXrmFwcJAvVHuFAACKXklEQVQdlqgFWJSBFD+3RNBSek4sw2g0fpUpmSifwo8fYP5esi6nGNRkRMc/x79cvV7PdixRXyQCGn3Kdn4evOhZagP/PB8bO5vNIplMIpVKsTaEw2HGgfFliRNG1i5eV0ft4sGLv19pQfJ9Ejkg2W4qe142wflyCiWlRf/TlCH2X+leEfjEDVONeD2UTqdDPB7H3bt3EQ6H8cYbb6C+vh5ms5mVI25iTU1NOHz4MCYmJtgGtbq6isuXL2NzcxNOp1MKFDLQofbK3oPae1QaL97FqxB67oGKJojsT8Zl8YuUj5IoKiTpGbovmUzmAJfJZGJmCclkEiaTCRqNBtFoFHq9PmeCAV+ACO9Yura2huXlZYRCIXbi19XVBY/Hg7m5OUxNTaG1tRVerxdLS0tYWlrCgQMHYDKZ8ODBA5SUlKCjo4P1UXT/4cdBibsQ2XX+N55kHJOauCMDTKWdWVa+Esf0rKT07LNwbEq/KwGy2rMit89vjsFgEIuLi3A4HNBqtdja2oLH42GbkyjqWiwWtLS0YGZmhgESHex0dnYyMxw6CebbV+i75H9T27xkm5TVaoXNZlMdR6LnHqjECZ2PpSel9vT0NPx+PxKJBLLZLEpLS9HQ0ICFhQWMj48jGo2ioaEB9fX1ePjwISYnJ5kvU3l5OS5cuIBsNotbt25ha2sLJ0+eRGVlJXOrIcU63xY+pEoqlcLMzAzu3LmDlZUVmM1mVFZWoqmpCZOTk/jBD36A+fl5dHR04KWXXoLf78f9+/dRW1uLoqIijI6OMkNQ6jv/SUT6NBnnWYhIpzTWz3K/uEsrcRziu3zW+pTaoFaWbLGJYKL0nFqflLgSOnGW6QI1ml31xOTkJDY2NmAymfDCCy+gp6dnDxfHg5XI1cViMYyNjbE2Tk1NoaWlJWejVeNClfoifs/HOabTaUQiEelvIj33QMVTvgVH4t/m5iZu377NrL+tViuOHTuGVCqFjz76CPF4HJlMBmNjY/jGN77BTvoWFhZY9IRkMonPPvsM9+/fRyaTQTqdxvnz57G6uspCw/IcDu2e/MljR0cHHA4HPvroI1RXV+PkyZPQarX46KOPkMlkcO7cOUxMTOD69evMV29gYAB2ux0AUF1dLV0Y4oSTffJ/MtcK2VgWMkllu7X4O89V5ntfsvplAKK068vaKJYh1iNy4Urinyjm5+uDOO5kl0fzku5ta2tDdXU1hoeH0dfXh66urhxDY75PZrMZ6XSajWlVVRWOHDkCYHe+8iY1AKTzUsbpyrgn/pqayoWesVgsX8WjIuLdAgpdJC6XCxcvXsTIyAjGxsZw8eJF1NbW4v79+zAajXjjjTcQj8dx+fJlRKNRHDlyBGVlZfjwww9x4cIFNDU1YWJiAv39/ejq6oLT6cSjR4/w5MkT5iBKxC9K8eWSgt3lcsHr9aKyshILCwuIxWK4cOECenp6cPXqVYyMjMDlcqG9vR0PHz6EwWBAW1sbi3oAKO/whViF59sZn4XURApR1JQp/WWLvhDg4H+XXVejfL+LdSqJy7JnlOYlz1HxKgmtVouTJ0+io6MDBoMBDx8+ZFzxysoKtFotfD4f4+71ej2SyeT/396bBreZZefBDwBiBwgCBPed4i6u2qWWuqVep6d7umd6JpOMnZTLcRI7Kdtx2a5UbP+wXZWy/TlVTlITO05sx5OKE3fKM909PdP7pta+UaQkSiIlivu+g8ROEO/3Az63Dy7vC0DtsaeH4qliEXhx37vf555z7jnnCtArLS3F1772NWiahjNnzmB4eBi1tbVpei497loFVpm4XlV7udqEXM5yoR0PVPIulYmoky0WC8rKyrCwsAC73Q6/3y+UmSUlJaiqqkI8HkdRUZEIBetwOESkA4qeUFxcjKeeegoOhwMbGxsIBoNCb0Xl8UUmXx5Jz0kc5ZM1FAphfn5ePKMTxnPnziEcDqOmpgY2m034LdJ7n1c8y7WvVSKN3jNZrMqFA6Hf9eqZaeHIOh96JnMNqrrL6VXtyAaEKs5MBis9rlTTUi5cm5ub6O3tRSwWw/j4uBATAeAHP/gBDAYD/sW/+Bdig+YcFeXpcDhgNptRUlKC0dFR4SKVaRNQ9W2mdsqcFrWB/1E0iFxoxwOVapHInSfvFNwhlLzT6TsdB1N6+XcOBvF4HIODgzAaU2Fki4qKEIvFlJwNr6P8nUwe6ARwfX0d7733Hj788EPE43EBpOFwWOyk5EMlg7QKCDPt+pQm150z23POLanK5iJItvplKlMl8qrSqEAklzGR66aaZ/L3TL9x0hsri8WCqqoq3Lx5E5OTk8KTgIfwiUajaaeFFGuMhwqisouKiuD3+9Os11WcoFy/TKJ5Nu6buEP6fdc84W8pk5JY77lsHkC2SgCEcSUpvuXJxKNnTk1NYXV1FUajEcFgEKWlpWlH/hwYATWnQLoKeZJRdM+JiQmsra0hFovh6tWr8Pv9sNvt6O/vx969e+HxeJRAo0cc2OTjbtXClhdrJmCQ25irGCaDg4rkNsrAyJ+rOLlsolqm/nsYEFctZHnR67UlLy8PL7zwArq6usTmVVxcLOb4yy+/LECK2mQ0GvH888+L6K/AZyYv1dXV4oIIPQU+J5oTqvboPeP9KvexxWLZ1VFxkjmmbDsZfeYst8FgQDweRywWQ15enogFRL50BGYEZMlkElVVVTh58iSMRiNOnz4tHJIJzOTFL4sBRLFYLK3upEivrq5Gb28vPvroI8zNzWFqagpf/vKXYbVa8dd//dcYHx9Hd3d3mrM0bxsvU7Xj6+lP+Hv0WbXQVQs2m2iUaUfWA0deBzlfGVxVoo2cbyZuSFV3OZicXl659oeqDfTZ6/WmgQ5vY2lpqciT65rKyspEes4NGQwGFBYWbjPw1WtrrqeC2Thc/rcbM/1vSQYpFak4I/6+pqXspaLRKCYmJvDgwQPMz89jcnISR44cgdFoRDQaRSQSEfnFYjHk5+ejs7MTiUQCV65cAQBEIhHcvHkTi4uLMBhSx8dHjx4VgMcXIYl7ZOVOnJXRaBTuOEZjKrpoMBgUCnWDwYDq6mphWiG3T15QFFCPSE+hquo3+i8vTP6c9yUPZ8zBWn5PpUvidcrGxchALNdHtVlRu3lIHtmZV55PMpfBy9TbCGUAlO3bVO3h5ciKdp4Hd5vieXLTF3lT4iClsrVTEe9Hea7IYy4TiX50x18utOOBipOK/VRxMVwkowHPy8tDaWkprl69iv/3//4fotEoCgsLRQRMIKUPsNvtadbs9Nlms8Hn82F1dRWzs7MIBAJwOBwoKioS9VOJgHl5eaitrRW7otPpxJEjR4QBaWFhIQ4ePIjq6mrk5+eLMp9++ml4PB7dRcS/8/9yXeR0qu+5Lky9d+m/bPlPY0VhaWRAVI0lsP1eRVkvQqKPLOpQObTwuM6G8uS6HH7Zp4oTy2XBqkivH2UHZbncRCKBaDQKl8sl+oduNkomU7cS2+32tI2I8uOqjEx1UgGoilQbgswM0IaeCz00UJ05cwb/8T/+R/T29mJ2dhavv/46vvrVr6YV/ru/+7v4H//jf2B1dRWHDx/GH//xH2Pv3r0iTSwWw6//+q/jr//6rxGJRPDUU0/hT/7kT9IuPlhdXcUv//Iv48033wQAvPTSS/j2t7+NgoKCh63ytkXEWWM9llfTUqFaGhoahOUvhXhdXl6GzWZDU1OTcFwuKCjAU089BbvdDgBobm5GQ0ODyPexxx6D1+tFY2OjsFQ3m83iiFa1eIEUUD3++ONiUbhcLhw7dkyc1FAkUKPRCL/fLxYa9aXMrqtAWu4n1YQikusqi6Sy2Cjny/OjxS5zXnpcWDL52WUF5Je5tbWFUCgk8icDR95WOvVaWVnB2toa8vLyYLVaRb8tLCxgY2MDBoMBjY2NCIfDWFtbQ0VFRZqrx+DgIJaXl4UP5t69e+FyuURZKi6Qk9wfqt/4dz0xWeYsjUYj1tbWcOHCBdjtdpw6dQomkwmjo6O4ePEigsEgYrEY6uvr8eSTT8Ltdm8bU15vVT1kDkze7PQ2e55GHmez2SzWTzZ6aKAKhULo6urCz/7sz+LrX//6tt//8A//EH/0R3+E73znO2hqasJ/+A//Ac888wyGhobE9c2/8iu/gh/84Ad49dVXUVhYiF/7tV/Diy++iN7eXqFs/qmf+ilMTU3h3XffBQD8q3/1r/DP/tk/ww9+8IOHrbIgOXSGTPKiraqqQnV1tZjsFosFBw8e3PYuhdtwOp1iQXm93jQn5KqqKgAp2yi+m9PuzoFTJgJKeo/ERMqb8uDt1NO7cCCSRYNM3Be1hQwLObdB3/nJEnFABkPqZHR9fR2bm5sCpH0+HxYXF4WvVzQaFWFzJyYmhNhqNBpRX1+PhYUFAcrz8/OYmZlBY2MjRkdHce/ePcFJHjlyBMXFxdvAamlpCR9++CE2NjaE2Exj2dvbi0QigUAggNXVVbjdboyOjqKoqEgc72uahrt372J0dBRlZWWYm5vD6uoqTp06JcZHJpWopRoj1e96gC/nS8+WlpbQ19eH0tJSPPnkkzAYDBgcHEQwGMThw4exsLCAmzdvoq2tDV6vN2185DJV46+qW66kErOp7n9vp37PP/88nn/+ed0K/ef//J/xW7/1W3jllVcAAP/rf/0vlJSU4P/+3/+Ln//5n0cgEMBf/MVf4H//7/+Np59+GgDwV3/1V6iqqsKHH36I5557Dnfv3sW7776LS5cu4fDhwwCAP/uzP8PRo0cxNDSE5ubmbWXTBZtEPMSpzEnQMxVLzSeIXown+h1IFw/l/FWOvCQK0kTh73PxhIOJPGm5CMNtsuLxuAAUu90Oi8WCjY0NxONxobS02Wwwm83ipJDsZyimFe8bKnd+fh6Dg4OIx+PCjef27dsYGRmBpmmIRqOw2+04efKk4Hg517qxsYFPPvkEU1NT0DQN9fX1OHz4MK5du4Y7d+4gEonA5/Ohp6cHJpMJly9fFiBB14ydPXsWFRUVePrpp3H9+nVMTEwgkUjgzp07IoTOpUuXUFpaKhzKCfhNJhOWl5cRCoXw+OOPw+v14vLly1hYWMDCwgLy8vLw7LPP4tatW7hx4wZaWlqwtraWximYzWa43W5xl97Nmzdx7949HD16VIA3L1PmMvgmIM+jTJwIf6bihg2GlM6ytrZWBHlMJpOw2Wyw2WwoKSnBoUOHsL6+jtnZWeEzyjmzbOJepud6XKMKnOQ2U0z3XOhHqqMaHR3F3Nwcnn32WfHMarXiiSeewIULF/DzP//z6O3txebmZlqa8vJytLe348KFC3juuedw8eJFeDweAVIAcOTIEXg8HhGuV6bf//3fx+/+7u9ue65a8ESyiCErd+VJxIGHOBjiaMieioMONyvgikoONCSnb25uCrGRLnCgEMherxfhcBiTk5Ow2WxYXV1FTU0NXC4XpqenEQgEYLPZMDAwIK7YqqurQ0tLC86dO4fJyUlhv7Vnzx6Ulpbi+vXrghOLRCI4deoUenp60sDQaDRidXUVb7/9NpaXl+FwOHD37l1sbm5ieHgYs7Oz2LNnj4hmSkfNsmjtcDjQ0NCA+fl5+P1+dHZ2wu/349SpUygvL8eVK1fw1FNPobq6Gn19fSgvL8fTTz8tONR4PI5IJIKrV6/C7Xajv78fVqtVBH7bv3+/MGKkiS9ze7QpeDweVFRU4MSJE4jH4yLUc2VlJeLxOCYnJ7eJszRuBP4+nw91dXV48OBBWjhg6rtkMonx8XEEAgFoWiqyhcPhEGFZsimsVRwWPZfnJ803ito6MzOTBpRTU1MYHR1FMBgUXC2NLdflyWXLwKoS3fUoE0jxsUkmkz8eX7+5uTkAEIG8iEpKSjA+Pi7SWCyWtCNWSkPvz83Nobi4eFv+xcXFIo1Mv/Ebv4Ff/dVfFd/X19eFrxsfYCLiaqLRKOLxOLa2thCLxWC32+Hz+bC+vo65uTlsbm6iuLgYfr8f4+PjGBsbEy4JLpcL3d3dsNvtuHv3Lubn59HR0QGfzyeclFtaWtJOYnj59Oz+/fuYnJzEsWPHYLfbce3aNdhsNiwvL6OpqQmFhYXY2NgQHMPdu3fx1FNPoa6uDmfPnhW6laGhIezZsweRSAS3bt1CcXGxiC7a1NSEra0tFBQUiEsijh8/DqvVik8++QQLCwtpi4D6anFxUYg4FRUVeOeddzA4OAhN09Da2pqmP+NKaD5JbTYbWltbMTY2Bo/Hg+rqapjNZtjtdpSWlsLpdMLv94uY8sS90IEB18OcO3cO6+vr8Pv9yMvLw9LSEm7evInOzs60vuZ/RqNRANs777yDQ4cOiUim3JaHyiOdFOdwNU0TtksGg0F4IBBnzCkej+PWrVu4ffu2SFNeXi7aTX0s65oygRcnGaTofafTKfR3AFBRUYGLFy/i9ddfRyQSSRO15TIzcU+qTV5Oo9cOTnI/mUwm4Zeajf5eTv1ylXUzpVGlz5SP1WpVGo/JNkQ8j5WVFZw9e1Y4ZzqdTnR2dmLPnj1CVCFQfeKJJzAzM4Nbt25heXkZBQUFaGlpEUrWjz76COFwGMvLyzhx4gSmpqbSAu3J+iduPbyxsYHr16+jsLAQnZ2diEQiQpSjkMXkepNMJrG2toabN28iFAphZGQEtbW1cLlcKCwsxLFjx7C6uoorV64IwCgrK0NjY6Pg+kZHR2GxWFBTUwOLxZImrqlYeafTierqahQWFqKsrAyLi4vicgHSO1H4Zv4+Bwrgsxt8uZjNw9uQyDI7O4tz586JQ4GKigrYbDZUVlYiEAgII8eKigqhm1lcXER5eTmam5uFHpDak0gkUF5ejqeeegp9fX04e/Ys5ubm0g47ODdM48PnosFgSDP85aYL9MfDVUciEUQiEfE8FArpcklyn/EyVek5yPFNmPz66LempiZ84xvfQDQaxfLyMt5//33RBj2AUpWfLa3ed15n1e+ybjUT/UiBigzO5ubm0ozMSBFKaeLxOFZXV9O4qoWFBRw7dkykmZ+f35b/4uLiNm4tV+KcFf3l5+dj3759sNvtGB4exqFDh1BbW4vR0VEsLy/j6aefhsPhwJkzZ7CysoLjx4+jrq4Ob7/9tnAMnZubw5kzZ+Dz+dDV1YWBgQFcuXIFRmMqlC+3+JU5Oq6/CAaDuHv3Lvbs2SNuPQZSp34kXvKA/ENDQ5ibm0MkEhG2VMlkEiMjI5iZmRFB8xOJBDY2NjA6OgqDwYDy8nJYLBasra3hxo0b2NzcxPj4eFqoEC46UGhk7pJBdO3aNUxNTcFkMuHAgQPo6OgQE48vYhkE5HEg3SIdEgSDQczPzyMvLw9FRUViYe7bt0/o0fr7+1FWVoaqqirB6X788cdIJBI4cuSIyJv6y2azoaurCw0NDZiYmMD169cRj8cF+FPaeDwOi8WCeDwuyqU2kaiUTCZFGgJZOuigGPXV1dXiHZvNBo/HI8aIg6FK7JPnrEx6h0FmsznNds5sNqO9vR3hcBgXLlyA0+ncpkNUSRu8HtnqowKhTKIfT8f9FLPRjxSo6urqUFpaig8++AA9PT0AUmzwp59+iv/v//v/AEDE+/7ggw/wzW9+EwAwOzuLgYEB/OEf/iEA4OjRowgEArhy5YoISXH58mUEAgEBZrmSXodrWuqG4vr6ekSjUaytraGhoQH5+fkYHh5GTU0N9u7dC03TMDAwgHg8DpPJBJvNBovFAovFgry8PEQiEVitVpw6dQqVlZWIRqMIh8PiRmV+msaBQNYFWK1WrK6uYmJiIm3HJM6AFoPJZILdbkc8HsfKygpKSkoEiCwvL+PSpUsIhUJwuVyIRqOIxWI4e/asOAp+6aWXYDCkTsE+/fRTRCIRFBYWora2VrdutDA4Z2QymeBwOFBaWgqbzYaCgoI0f0fe1yr3DPlkkkKNbG1twe/34ytf+YoQA4lrKywsRHNzMyYmJhCLxUTf19fXo7i4GGNjY9jY2BDcHpVjNBqxvr6OwcFBdHV1oa2tDdPT00Kft7i4iK2tLaytrSEcDgvAIRGf9FB0cLC5uSk2A3mBUpt6enrQ0dEh+gvAttNB1YKWRa1sYhfvS7r6jPp8a2tLrKPr16+ju7sblZWV27jZbMSBTN5sc9FbZeK0/t6uywoGgxgeHhbfR0dHxfVO1dXV+JVf+RX83u/9HhobG9HY2Ijf+73fg8PhwE/91E8BSB3P/9zP/Rx+7dd+DYWFhfD5fPj1X/91dHR0iFPA1tZWfOlLX8K//Jf/Ev/9v/93ACnzhBdffFGpSM9Geiw0LYxkMimiDFCnUmhhCu9LJzv0DulC+HXZ6+vroixaKJxzovf5fyAFRsXFxTCbzbhy5Qq8Xq9QCnP3DNIv2O127N+/X9gP0aWhZrMZjz32GCKRCHp7e8U1Wi0tLWhubobNZkNhYSEWFhbg8/lw6NAhnDt3DjU1NaipqUkDGqovHfsTOBEHYrVa0dLSglOnTgGAUBLLfc4nI78pmgCE8qRyiatyOp2ij7kpBNUjmUxiZmYG09PT6OjoQDKZFK5GvL+pLZFIBB999BEWFhZQWlqKubk51NTUwOFw4L333oPVasX4+Dg8Hg8KCwuxsrKCCxcuCDu35uZmzM/PY2xsDO+++y5GR0fh9/vF7S7caJI+65ktEOlxRnIfyu/I9lr8oMZutwuQikajePfddzEyMoKWlhYRyYNzU7mSzHWpOC1ZaqDfMhGNdzZ6aKC6du2amJwAhAL7Z37mZ/Cd73wH/+7f/TtEIhH8m3/zb4TB5/vvvy9sqADgP/2n/4S8vDx885vfFAaf3/nOd9LQ9f/8n/+DX/7lXxangy+99BL+63/9rw9b3W0TV0UcnOTdTdNSp3K0iGgn4kfSS0tLeOutt4T+iIxEuU8fL4eInxA6nU50dHTgrbfewsrKCg4cOICtra0015p4PC6+79u3D2azGX19fZibm4PJZILVakV7ezsAYGRkBEBqt21vb0dLS4soN5lMIj8/H/v378f8/DwWFxfFQQKVxfttdXVVhJQZHx8XjqwAhB8k3aQsH3nTbyMjIyKs8t27d9Ha2ioAkC9yk8mE+fl5vPXWWyIPqjuNAekibTYblpaW8Nprr8HtdiMcDqOqqkosZC7aeL1etLW1YXJyEoFAAB6PB83NzfB6vZiensbCwgJcLhdOnTqFgoICeL1eIdaS0j8/Px/V1dUiBPCJEyeEnZVqocqbkkrM4QCgN0e52kLOm+ZPXl4e3G634ESNRiPsdjsOHz6Mzs5OVFRUpJ2I8hNuuexs9eF1ehiS+4Pb5WWjhwaqkydPZkRJg8GA3/md38Hv/M7v6Kax2Wz49re/jW9/+9u6aXw+H/7qr/7qYauXE8lglEgkBCjwkxyaWHKwu83NTeF8TLoJUkzfvXtX6CLIDov+uAsG8NmAEcjs3bsXfX19uHv3rhAraRGTYp04HLvdLq5hJxaexJSpqSksLCyItgQCAczMzIiFTpyNxWJBT08PXnvtNUxMTKC5uTltwRkMqaB9DocDb7/9NlwuF8bGxvDyyy/j3r17Arj5xOf9REAUDodx8eJFrK+vIxQK4datW2hsbBSAT9ykpqW8AYqLi7G6uiraaLFY0NraCr/fD01L3Ut45MgRVFRU4OTJk5ienhaiNgWB45woiZZf+tKXxEGF3W6HzWaD1WrFl7/8ZQE2BNY/93M/l6afstlsqK2tRXt7u1Bc052H3I8u10VO/zmYyr9TPpn0RPQ76cYoRj6lo5DXsgsRdwVSqUdyIT5PHkaE5P+zcZ1Ej5SvHyfeWVwMIZuoQCCARCKBeDyOYDCYduJDimrKg4wAKbgegcz6+jrW19cRi8WwtbUlrNWB7acrBkMqoFlPTw/u3Lkjdpq+vj5sbW3hzp07QhwlR04CULfbjcnJSSwuLuL111/H6uoqiouLRaTHjz/+WIBWTU0NGhoaxEFGZWUlmpqalHGyNC114vfCCy/gxo0b0DQNTz31lLgWTHW0TCDB/5NbB+n5SDwxGFKXUL7wwguw2WzY3NxEdXU1/tE/+kdpVu4UyBCAEMVJ+U+mI0R6JhLcCJLSEBCRgp4rluVLOUmE5VwntZF0WHxO8DHm9nMPA0jyfM1EtEmovAvkcvgzWc+k0jvxtCpAylXc4/lxETkX2vFApWJR5YHjO4umpQwUR0dHceHCBczNzWFpaQkFBQVpOw9dn0UKXTkwWTQaxZkzZ4TNkdPpxFe/+lWhdCYi7s3pdCIej6OhoQFNTU3weDxoaWlBX1+fCGF8+PBh+P1+NDQ0wGBI2fJ4vV64XC5YrVb09PTAbrejuroara2tKCkpwRNPPCEOAaxWK+x2O5xOJyorK2E2m5GXl4cnnngizb5HnsxNTU3ihmYgtcBbW1tFem7Yyt+lv7y8PFRWVm5bALRBcH85TdPSRBTKjya0rAfj3JwsgtHYUp25mYh8EiuLbDJXRuXxOtBiy3Zyxd/j/STPQTqh5On4AQZvF73HPxOnRH3AY67Te5yTUtUxWxty4Z7kMeDE+zLXEz/gEQAq1U4ms7qapoljW1Kc3r9/Hzdv3oTZbMazzz4rwg9rmoaGhgahPC4oKMDevXvFpNmzZw+MRqMIW0xckM1mE+IJ1YkmZEdHhxg4l8uFl19+WcRL7+rqEid+LpcLJpMJhYWFYsK1traKdjU0NKTp0TRNE9bmMpFjqqZpIl/qC5WNE4EFVxzzvpUXH+9rle8hiYXyGHEwkXUoqh1f5lDlsujdh+VY5AWpAjSZY6PvnKsLBoNi/OkZ5cMBk7h4u90Oh8MBIMU9zs/PCxs/mk+8TfSZLNCpHkVFRWhra0MsFsO9e/ewsbGBuro64Witsu3LRHqgo3qe6T2Z4/x701H9pBFfcPSd/wdSZhU1NTVp4PPCCy9gc3MTNptNHARomgafz4cnn3xSHKfTsT7lScBBp1PcUljWFRCRvRVNssLCQiFqkLKaG8bxe9woHSlUed6yKCCbG3BuhAMU1ZuXQXWXOQiD4TNbK6JMooJqMfM6yKIKBzDVZ9XYymVxsJQ5JbktevWmusplEslhUqLRKEZHRzEwMICCggIxx+QDG6LZ2VlcvnwZe/fuRWdnJ5LJJIaGhnD69GlEo1GYTCY8/fTTwuyH13Vraws3btzA4OAgPB4PVldXkUwm4fP5EIlE8MMf/hBbW1soKyvD1772NWGbxknVXtVGoUqb6V09EKN3dnVUf0t6uwZfWH6/f1vHkqjHd3ZasORqQeDAWXu+0GTPcD7QfODlyAU8zpFq16JdlRT5HDxk8KE0smgQi8UQj8eFYt3j8aRdjkonmG63G+vr61hZWRERTSsrK6FpGgYHB7G+vg6z2YyKigqxEOX2yv3IAYc/o7ScO5F/Vymf5TQy6S0wPhbyZ07y3NArh4tww8PDeO+997CysgK73Y6JiQk8//zzaYbQfANYWVnByMgIvF4vurq6EIvF8ODBA3G91ZkzZ3DhwgU0NjYiPz9/mwjodDpx9OhRNDc343vf+x6mp6cRDAZx/fp1VFdXo6urC2+++SbOnTuHV155ZVufZ2qTqg9z4cT0+ksl3WSjHQ9UgPp4F0hXnsqTlXM4fOfV4864zoMvRj39hkxUF+LA5J2X7+bhcFhc5EBREskeaXx8HE6nE2VlZYjFYhgdHUV5eTm8Xi/m5+extLSEoqIi9Pb2YnJyEolEAqWlpTh8+DDu37+P/Px89PT0YG1tDefPn8eePXvQ29uLxcVFYY392GOPwWAw4NNPP0V+fj62trYwMDCAl19+GWVlZcrdVyW6qcaIf5f7R/WOzBXJv2fKO5MOJdszvd9JQb+8vAyj0Yji4mJUVFSgvb1dHD7I881oNKKxsVE4fJNIdPDgQTgcDvj9fuzfvx/vvvtuWrQMIvIM2NzcxL179zA2NobOzk44HA4sLCxg37592Lt3L27evInh4WERDlsPdPTGIVfAz8R9yXntclR/S9lAisQZ4mC4vxSJNORWAaQMXmmgnU4nNjc3sbi4KPRIpJvy+XyIRqOYmZkRdjmhUAizs7OoqKiA1WrFxMQEAoEADIZU7CCKw+5yufDYY4+huro6zbjPYDBgbm4O77zzjjA3sFgsOHnyJNra2nD16lV88sknKCwsxLPPPgu73Y6rV6/i8ccfh9/vx8LCAvr7+3Hq1CnY7XZxfReBy/DwMDY3N1FXV4dkMon5+XmYzWYsLS3h1KlTKCoqwuXLl7G6uipCvjz33HMisgEZblK/y+PAx0OVhp7piXIy1yTraVR5yfOAP1fVQ16kMrehV3cV1xsKhWC1WhEOh+FyuVBQUKC8qEPTNKFiIA43Ly8PZWVl4iT5wYMHwrRCBn1NSx1ALCws4NKlS4jFYmhoaBAnl+Q21dLSgunp6bT2yxysXv9RerkvVJysnuSg2jB+LC40X1TSm8zRaBQ3b97E0tISNC1lw9PW1oaZmRk4HA40NTUhEAjg5s2bqKmpwdjYGG7cuAGDIXWsTorqy5cvY21tDVtbW3C73Th58iScTidOnz6Ny5cvo6GhASdOnBC3J584cQKNjY2YmZnBwsICurq64HK5MDExgby8PNTU1KRdxU2kaRomJyexsrKCxx9/HPn5+bhw4QImJiYAAOfPn4fb7UYgEMDp06dx8OBBhMNhBINBACnnZwocd+TIEQSDQQQCAXR1dQmL87GxMdy/fz8t8oTVakV1dTW8Xi9OnDiBWCwm/ATNZjMKCwvTAgdmo1x1HdlAjS9UPr7ZdnEVGGWqo17+egBmMKSCLlIEjNXVVYTDYbzyyisoLS1N01nyP4p9z7n2RCKBS5cuobe3FwcOHIDb7da9rCM/Px/d3d2YmZnBe++9J8rSNE24PGXiWvWe55ru8+Sxa57wt5RJmbexsYGZmRkMDAxA01LhgpPJJG7duoVkMomSkhKhFAUg5P09e/aIwHEnTpzAqVOn8Mknn8Bms+GZZ56B3W7HJ598gvPnz6OyslKEhiHL6P7+flRUVAgjzrq6OpSXl4srtU6dOiX0S7I8n0ymwhG3traKG0m2trZw/vx52O12fOtb38Lk5CQ++OADbGxsIJlMCmPO0dFREf6YwpQQEFEkhEQigf7+fmEuQYr1RCKBW7duYX5+HhUVFSgoKEBvby9ef/117N27V1jj56K7oLbkkjabeJKrrkV+N1fdiIpjUJUj6wnLysrwjW98A2+99RYikYiISlpcXJyWlvIiv0ZyhqZyiUs+cuQInnzyyW0Lm9oSDodhNptx6tQpeL1e/M//+T+FXvHBgwdobW3FysrKthuNMrVJ1Rfyd5k71Os/vf7e1VExUumLDIbUEe7TTz8tdqjjx48Ln7Hx8XEMDw+joqJCgIbT6cSxY8dQVVWFwsJCxGIxFBUVIT8/H06nUzjpBgIBPHjwAJ2dnXj++efR19eH/v5+BINBbG5uigCD3Cuf6kfKbxKj5ElgNpuxuLiIs2fPoqurK+2KpNLSUhQUFCAWiwnRtLCwELOzs1hYWMDs7Cz2798Pm80m8qOyTSYT8vLy0NTUhOXlZQwMDAjXIU1Lue/cuXMH9+/fR1tbG55++mkYjUZMTU3h/PnzGBwcxJe+9CWUlJRk5Tj4GPAxygQIqsUgA5Sch+pdWdTIhSPLhQvhbTCZTJiZmcHo6Kg4iSXdo6rdpHuka9iAlOjX19eHjz/+GLW1tXj88ceFW5amaZiZmcHi4iIaGxvhdrsxMjKClZUVHDt2DIWFhXA4HDCZTKitrUV/fz+am5sxODgoDkJ4u1QgpcfBqvpK1T/ZFOa5bipEOx6o9DqUfiM3DZPJBLPZLHRQsVgMt2/fFhwLkIpfde7cORw4cACVlZVpp28AhE1IIpGA2WxGTU0NfD4fvF6vEK0oEmVfX58wPSCwiMfjaQHZVDqampoa9PT0YHBwEDdv3kRjYyO6u7uxubmJiYkJ/PCHP8TKygqWl5dht9tRV1eH06dPY2BgAIlEQrhUaJomdG3AZyeNJPr29fXB6XQKnZ3P58Mrr7yCd955B+FwWFiHHzhwACMjI3jttdewsrKC0tJSpVFmJt2TnFZ+j/+uAjxZTNMT9TO9y/tYTqP6XUV0uJFMpiJXXrt2DaFQCNFoFMXFxSgrK0tz/OansAZDysyD5pTRaMTg4CDGx8dhMBjw3e9+F16vF08++SQ8Hg9u3bqFCxcu4Gd/9mfhdrsRj8fx4Ycf4u7du+K0tri4GIWFhbh9+7bwpf3qV7+67SRcBcx6QKLi8FWMwI+adjxQZdJLUEfLp2x5eXmoqqrC4uIi7t+/j1gsJsIl9/f3Y3R0FN3d3ejo6EB5ebkQobhBZzQaxdmzZzE4OCiM9sxmM1wuF9rb29Hb2wuj0Sgstql8bgSpUjQWFBTgxIkTaG9vx4MHD4TIF4vFRIgZOnmi4HjxeBy9vb0oLi4WHBidEtIpktGYupvQ6XQKNx5qE4EsKYiNRiNu3LiBeDyOo0ePittvqN60EHPRK31ePQlfHDKoZRI1ZC5VBj95gT6svosU01VVVXj55ZcxMDAAAGhvbxeXTtB7fHw1TUNJSUna4U5jY6PYvCwWS5pNXnV1NUKhkHDpaWtrE4cjkUgEdXV1KCwshNlsxte+9jWMjo6iqqoKe/bsycrNyEAv9yt/V7bw//uiHQ9UQGY9FQARm5wAZ3NzEx0dHZibm8OVK1dgNptF9MgDBw6I4HjhcBhf//rXBTdktVoFax4KheB0OmG32+F2u0WAO7PZjO7ubhEep6amBgaDQUwwCjtDdZO5k+XlZczOzqK9vR0VFRUYGhqCwZByrN6/fz++/OUvY2VlBRMTE9C0lB+i3+/H0NCQCPMRi8WwsrKC+fl5GAwpq2YS2YzGVLx1uuHFYDAgEAjg3XffxebmJm7fvo3u7m4EAgFcvnwZw8PDwheSrN1VE11WHKtENT4mqjxUfmwqXZX8m5yPSgTMRJl0ObwcfjuQxWLBnj170u5jJOJeANzwtb6+HrW1tWID7ezsRFdXl9jAKD15JDQ1NYn6OJ1OnDhxQrSPODuDwYCenh50d3frtoOPBwd/VVo9QMpFB6XaAPTMdWTa8UCVqWMNhpS/XCKRECBjNBoRj8dRXFyMoqIiXLp0CYWFhYjH45iamkJ1dbWIRR4Oh8Xk4cadNLG+9KUvoaWlBTdv3sTrr78uBsXpdGLfvn24c+cOgM+C42maJnwIucMm/UZhVj766CNMTk7CaDRiYmIC1dXV0LTUqSXt1HQJJbkELS0tiQsMVlZW8Pbbb2NsbAx5eXk4f/48nnnmGRQUFMBms8FkMqGrq0uYLvT09IiT0IaGBtTV1aGqqkp47G9tbaGkpEQoirPpcTI9y8bBqLglWazkIKgCJJ6ec36kX+LjqFdfbvVPgKDyKyR3GF53Ht6EAwN5M9BYc0NdFRDzKAhULm+fDEBUXi6gIvd1JhE402+Z1t+ujoqRaifgegF+uQOdkhmNqcsAysrKUFJSgq2tLdy7dw8XL17EwYMHkZeXh5GRETQ3NwuxCIDgjOgKKr4LFhQUiDAtQOqC0vr6ehHPiFh6Hq5Wtm8xmUwoKiqC1+sVzs4NDQ1obW0VvwGpnb2trQ0OhwOapqGpqUnEVAc+A8ra2lrY7XahfCWwAlJ+g+Xl5fD5fHj55ZcFmNLiMJvNeO6559IWpRzNNNNC559VXJVKtOPvqgBIVZ4cuUAWPSneO+WpcpORIzLweOlym/hFFypuj4MLn4ccrGQumt6jeqlOg7kqQxa7+e+cMvn6Pexm83noYXRZOx6oAH1xYnZ2Fh9++KGIkZ5MJoUFMbmS7N27F1NTU8Kl5v3334fdbhcRLmnilJeXw+/3i91y7969yM/PFwacnZ2dKCoqEqGDLRaLMMokTu5LX/oSCgsL03Zq+Ti6oqICX//618XioUst/H6/iIBgt9tx4sQJYS5A3A4tCIrvRET9QYpwchimSxLo6FwGDipPPmrPdQLSCSeNEQdnvvDk/GRAUumY+DNev83NTaEv5BdSyGBG+j7ilKmfA4GACEPNo3jS+6FQSHClKsAhootYiYtLJBIIhUJIJBLC+JO4e3JWpvFQ5cnBUAZ/fqrMSQZ/WScl9+nDkh7X9XnyMmg/Knj8gtH6+jo8Hg/++q//WugH5MmyuLiIoaEhBINB2Gw2lJeXo7y8HEtLSygtLYXL5RIXKJSVlWFjY0Mc/dPtLTSxNzY20kIWU8RLKpP73HH5XN6hZdFFZtnlRcVBDUjnCnha2mllS3cimYuhZzwtz5vKonT0jMCVyuSkWggEitSvwGfW/0BKf+hyueB0OrGwsIBgMAiDIRXQj65Uk4EJAMLhMIaGhoRDMPVVb28vhoeH0drair179woOlwPW1tYWPv30U9y5c0dEwqisrERbWxuuXbsm6ub1eoXVv6Zp4rS0s7MTtbW1aX3Nxbfp6Wn09/ejq6sLTU1NSCaTGBwcxO3btxEOh+FwOHDqb+887O/vF6GSn332WXR2dqYdgGQT4zKJevJYZBLh+HcZuGSgo2cyUPO5TRQOh/HMM88gEAhkvN79keCo9Fj0srKytCNj+o30O+SBTguSPssOwwDSYmcT+ABIY9VVzsO8TrKuRSb5d14eBwqeJ6XlC5HXS9bj0ASjoHz8UlHOAQWDQczNzYmTQ7PZjKqqKjgcDmxtbWF1dRWTk5Oor68XSnaZCNTGx8dx6dIlHDhwAPn5+fjggw8QCoUApKzpu7u7UVhYiNOnTwNIBQz0er146aWX0k7SeLsGBgbwwQcf4OjRo2hoaICmaZiYmMDFixdhtVpx48YNEbqZAz6Q8liYm5tDYWEhmpqa0Nvbi7GxMZSXlyMQCKC7u1vcLEMnvUtLS/j444+Fb2VNTY3oT97nkUgE/f396O3tRXV1NQwGA0KhEK5evQqj0YiGhgZcv34d58+fx6lTp9DX1wev1wuDwYDTp0+jrq5OiPR63KseSKk2Cnl+5coN58JlqdLoccPZ6JEAKmD74NDpGukM6BkfLL4wKQ8ezZHnyzkNzsFQnhyMyAhQpT/jXA03EKQ8aUHxyyboggmK6gBAhAbhSlt+71w8Hsfo6CgcDgcqKioAQIQN7uvrw71799DU1ITDhw9vE6fIev/SpUvIy8sToZxffvlltLS0IBgM4r333sP4+Di+9a1v6e6UeXl5WFxcxDvvvIPR0VE0NDSgqKgIFRUVcDqdWFlZwdWrV7G1tYXZ2Vk4nU4888wzCAaD+Pjjj7G8vIyioqJtHJXBYIDf74fH4xEXidL9i/n5+XjmmWdw7949DA0Nobm5WYSVpjGxWq3o7OyEx+OBpmniynkyoqyrqxOhUsxmM5aXl/HRRx+JG4ToJhjO2dJ8sNlsOHLkCCYnJ0V8M4vFgs7OThQXFwv7vMuXL2NkZARjY2P4p//0n8LpdOI73/kO7ty5g0OHDm2LMCHPx1xELdVzGawyiX56oqfqdzkdXze50I4HKpV+QzXAMlfFJz4NFolodMkC3fTB7VzookniykgHEQwGMTs7KwAymUyioqICm5ub4kYUj8eDRCKB4eFhEQWho6MDTqcTk5OTuHr1KoLBIAoKCnD8+HHMz8/j/fffh9FoxLFjx9DZ2SkcqsmyXb5wQdNSt9lcu3YNH330EQ4ePCiCqW1sbODChQvo7+9HcXExSkpK0rgxCvOSTCYRCoVQWlqKjo4O3LhxA8PDwzAYUjfxnDlzBrdu3VJ6xvP+X1lZwTvvvIPp6WlYLBZsbm7C5XLh2LFjsFgsuHTpEtxuN5qbm3Hr1i0UFRWhqqpK2A/J3CTnlmtra1FVVSXEJOpnugswEokIGzlyIeIGmO3t7VhaWsJ3v/tdrKys4IknnkBBQQHm5ubw9ttvw+FwwGKx4ODBgxgfH8fQ0BCOHz8urvKS5xD1odFohN/vF54NBkPKho7MEDQt5dpFDu5Wq1V4PxQVFWF1dVWMiWp+ZyOViK+XR64Al0kMzMTxPYzW6ZEBKhmUACAQCMBoNIpYTLOzswiFQqioqIDP5xOcx8jICEZGRoR7jdFoxOHDhxEKhdDf34+enh7U19cjGAzi3LlzCIfDeP755+FwOJBIJMT1VRcvXhRA4fF48PWvfx0TExNYXl5GVVUVpqenYbVaEQwGcenSJTQ0NGDv3r0IBALY2trC2NgYFhYWcOLECTidTmxsbGB6ehpOp1OAGV37/thjjwkFOPDZYuEB8UwmkwA2TUvFl+rt7cXBgwexf/9+FBQUiEm9srKCu3fvoqOjA263Gy0tLWhpaUEgEMDk5CSqqqrg8/lw+fJl9Pb2oqWlBUtLS9s4HSICy9HRURw9ehQTExNpomg4HMb9+/fh8/nEIcXIyIi4BmxpaUnkJYfe0TRNbB78huLNzU14vV4YjUZhyMpdlbhoDkBcjJFMJrG+vi5OR/Pz8+HxeHD37l0AEBvM0tKS8Kfr7u4WJ6iciIMiDpcMaWlc7ty5g8uXL6OtrQ35+flwOBxpByZkEpNtketxS7LYpbc5y6TSP8lipUoyyCWfXGjHAxUNBJ/MxOFcu3ZN3O22vr6O8+fPY3V1Fa+88gqi0ai4FmljYwNnzpwRYTaqq6tx8OBB3L17V1xVNTQ0JC4tCAQCWFtbw3vvvYfh4WEYjUasrq6mXfFdX1+PgoIC9PX1wWaz4erVq7hw4QKamppw7NgxVFdXo6WlRbjKPPHEE2hoaMDMzAzu3r2Luro6ERaGFtj9+/dx8eJF1NXV4fDhwyIAHp8QZFpw8OBBTE1NAYAA5IGBAdjtdnGayU8dl5eXcebMGdTU1CA/Px/l5eXY2NjAG2+8gVAoJGInXb9+HV6vF7W1tVhYWMDCwoKIxCCL1TMzM0gmk9jY2EAgEMDY2Bi6urpgt9sxPz+Pubk5fPnLX4bNZkNDQwNu3ryJTz/9VBxeEHGreCI68KALSWkhcV+6aDQqODLOmRFY+f1+/JN/8k/w4Ycf4pNPPkFzczO++tWvory8HC6XC2azGdPT09i7dy8aGxsBQIyxbKZBfclNEqheBJaTk5N47733UFxcjKefflpEXqAYVTzcEOUtt5uXmQ1w9N7N9Lvqea7Kevr+MJwU0SMBVER8ByHRy+Vy4dNPP0V5eTnq6uoApCYq6VhOnDiB8vJyMcGsVqu4kmh4eFi4ObzzzjtoaWlBXV2dsMeixUZGkTRhHQ4H2traMDU1hYGBAWxubiISiSAWiwng83q9KC4uxvvvv4/BwUHs3btXOJTOz88jGAwiFoshmUwKsLLb7cjPz4fX6912bE7+g7QTkk8h74+1tTUsLS3hjTfegM1mQ09Pjwh963a70d3dnaYYNxqNwh9wfHxcGJQuLy9jZWUF6+vruH//Ptrb28VRPBejCwoK4HQ6MTc3h+XlZbhcLqEXDIVCIpooAOzZswc//dM/DbvdjtHRUbz77rtpJ3bA9ptnCAQACJMCAsdQKJR2kSzXJZFy3Ol0ikst/vRP/1TYXBGHk5+fj/HxcTQ2NqKpqQlGoxGvvvoqrFaruOWH6iFvlEBKj0gANjY2hvfeew8WiwUvvvgiioqKEI/HEYlEMDExAbPZjLGxsW0W5rwM1bNcdFWq93MR+1SAKKtM5LSfR+wDHgGgkgeLntntdjQ2NuLWrVv46KOPcPToUSFmxWIxzM7OYnV1Vfi20aRyuVxoampCf38/VlZWUFtbK5SeNptNiEb5+fk4efIkuru7hfJ5aGgIwGcx2t944w0sLy8LEDGbzWhvbxeOwJqWOqmKRqOYn59HY2OjEB35/0gkggcPHqC9vR3PPfecsNXix+NAul8WcVGk66EyXS4XKioqsLKygvPnz6OlpQUOhwPFxcU4deoUrFarAAabzYYXX3wR169fR39/P9rb2/Hiiy8CAFZXV/HRRx+hra1tG0gRcJ48eRInTpyA1WrFn//5n+PAgQMiuBw5TBPgWiwW1NbWIhgMYmBgABaLRZz48UXAzTAIEKm8uro6XLlyBVevXsXw8DCqqqrSNhEuDlOAwCeffFLcs7iysoIzZ86gs7MTdXV1GBsbE31LNlk+n08AIIGufHBCCnvaOEwmE06fPo2xsTE88cQTSCQSmJycRFFREerr6/Huu++isbERsVhsm/1bNh1VJu5KTievkVzSqkS8TDqsz0u5Ozz9BBPXU9FkJiPG6elprK+vY2FhIe3W27179wo7l2g0KiIvtre3w+PxoL+/X1wESjqkSCQCAGKhLS0t4cGDB/B6vTh8+LCw3t63bx8ikQjGxsbSuJOnnnoK3d3dePvttzEzMyN0F7Tg+CUK/DaSZDKJixcv4oc//CEuXbqE8fFxABAihZ5bCxkdUj6bm5s4cuQIXnnlFTz99NOIxWJCJ7e0tITz589jfX0dADA5OYm5uTn4/X5xU04kEkFnZ6dw2HY4HOKiCn5YQZ+dTqewRSOdUiKRSBsjAp5oNIre3l78zd/8DSYnJ3Hy5ElhHyfv3tyEhPrBZDIJ0Hz77bcxNzeH7u7ubVeKa1rqVNbn82F0dBR/8zd/g76+PnR0dKCoqAgejwdnz57Fd7/7Xdy/fx9lZWVCCU8ARG5QfM7J6geqO9WVNqqBgQG89tpr+PTTTxEKhfDYY48hEongypUraGpqErZjfF5TvWXi/Z0pHU8r/6lIFpeziZN69DAHATueo5KJJgwAEUaYdBcGgwGTk5MwGAzweDxwuVwi1rjBkIrqefjwYdy6dQvT09PCO91sNgsQslqtGB8fx/3794VyvrCwUNwMvGfPHtTV1eHtt99GKBQSA33kyBE89thjePvtt3Ht2jXU19cLpa/RaERJSQnW19fT7LL45Q7BYBD37t2D0+mE3+/H8vKyiKUOpB8Dy+4dRqNR3P5MHMXq6qooy2QyYWJiApcuXUJjYyM8Hg8GBgYwOTmJQ4cOYWlpCX6/Hz6fTwAN+U9yYJJFbwIkLopyDiU/P1+8GwgE0NfXh3A4jBdffFGckqlcduidqqoqYYxJ/ptf/vKXMT09jZKSEnG1GQcRqk9XVxeKiorEJRjl5eUixPPs7KxQ2FdUVKSZm+zdu1f0AXeV4VxfIpHAgQMH0sxhnnnmGaytrQFIiYakSG9pacHP/dzPIZFIwO/3i1hiP2ow0BPJ9MqSuSo9fRk9U3G+D0OPBFBxhSbnYAAIHQ8t0sXFRYyOjkLTUiYGjY2N4oSpra0NQCrSJ4lW0WgUPp9PGJDG43Gsra0J/0ES0SKRiBDtpqencf/+fQCpSdne3o7jx4/j9OnT6O3thcGQMgIMBAIiLIfX68WVK1fEMTrXd9DkcLlcOHHiBHw+H65evYqDBw8Kg0TZEJTEHD5BHQ4Hrly5IgL7ud1uIRL6/X4cOHBA3DdYVFQkXI/a29tx7Ngx4flPCuvu7m7Y7fZtJ41yKF6z2YzHHnsszdK8rKwMFotFmH3k5+fjueeeg8ViEVyaSjfCre9ramq26Ubq6+tRV1cnDhX4XKD+BFIcD403P1TweDziijQyiCWOKBKJiDZQ/Tg3z/8XFRWl6dQqKytRXV2d1i/0G0Vg4CYJegCUi5jFQUVP3yUDUbbP8rNcwPRhFOs7HqjkjqPOoevaS0tLxc41NzcnwvHabDYcOnQIFosFt27dQkFBAQ4ePIj+/n7Mzs4KcWRkZESEgOnq6sKdO3fg8Xhw+PBhnD17FqurqygrK8Pa2hpqampQX1+PDz/8UIhQLpcLhw8fFkfWbW1tCIfD4nSvq6sLXV1dWFtbw+DgIAAo9U9VVVU4cuQIXC4X3n//fWxsbGD//v26CyaZTKK4uFgofekmE7KHogB9brcbyWQSVVVVqKysFEDQ0dGBtrY2wUkZDAYRpsZsNqOyshKvvPIKgNRJGMVKokXGF53RmLqFhXNYdCEG1d1isaC8vDxtLCkP7hDN7zbk8cEIlPl73MYMwDYxkDhP6ms6tODcYDgcFu2gueXxeERUDrKto37hoqD8WZ6zRLLejY9jLvOfp+UglIveKhMgfp73H5aTItrxQCWLODT51tfXMTk5iZqaGjz++OOoqKjAxYsXEYvFUF1dje7ubtTX1+Pjjz/G5OSkOH4fGBhIE72GhoZQVVWFL33pS4hEIrhx44Y4gXvhhRcQjUaFXsPr9WJ8fByjo6Ni4pJeJhwOo7GxEbW1tZifn8fa2hqGhoZQWFiI/Px8ES2B7GpmZ2eFgyyQ8jujQwASMW02WxowyQvj4MGDYkFpmoaOjg60traKPpJPDvlnp9MpXDtisZhwXqZ3yFjRYDAIx2syKeCxkrilPXc7opAnKl0IcULkzEvvyAuQAx8951w1/U7W68Q9ErAREfhxoOP6Q+ovh8OBvLw8hMNhYXVOv0ejUUQiEXEYwc0UuE5I5pZ4Gk6qtLnQwyq2M+m+MqXXEyU/Tx2ARwioaLBpB93Y2BAnVUeOHMG9e/dw+/ZtYQ1eUFCAM2fOiIsf8vLycOXKFayurgqXi7y8PMTjcUxOTqKiogJTU1PipGpqakrcGLK0tCSOrCORCNrb26FpKcO//Px8Ea2BYheReGM2m1FQUACTyYRjx46hu7sbQIpToKiaJ0+eFJEOyMKadmAKGcP7gU8kil9F/WI2m7f59vEFxHUu/CpuOvEi1xHqHw5CXq8XVqsV6+vrcLvdAtCsVquwPeL6NyqfAwh9Jwdmg8EguCBN08QhBtVP5kRIzCcTAwBpPo0mk0noBOlElcrg7kvUX6QjpAsZiIOz2WxiHEhsdzgcCAaD4qCjurpaRLeQTwY5fV5A0hPrsqVX1UMWseU0uZT1sIAn044HKlWnJ5OpCIwej0fYPCWTSfT09AiXBbPZjObmZjQ3N8NkMgmH5Obm5jQfQQq/YbVahbhEimDOOXCbHdrVOQchK7g52ywrwnmbCgsLlXoBeSdWHZPLYoBKDOGfqS18oVPbqP6kuCZdFJ0ams1mcXU9LXKz2YxIJIJIJCIAhjg5zsXQO/xggPRG3PqeTmYJKHkwQ4pmQae9BGwUroU2MDoh5FE46YYe+s7TEhdJ+RHAkc6TyOVyiT5bW1sTwEjcbDaXGOoHPRB5WJFQJhmkMuWjxy3xuaPKh55xH8hdoGLEJwJ1UlFREb785S8D+Kwz6bSGLwiZPecKaMqb/8/Pz98mbvJdUTXIlD8/IVKZFHCOg9LwCSqLOZz4yRuvu7yj0++8HF4+gebW1pY4gdI0TYhM3B+QOFF6DiANnGlBU3hkMmDlkU35zcDU9zwsDveX4+Agm3EQSPG+IFCi56RTIvDlHBsBBfcJpDJ4fYgbo98IVAlo/X4/KioqEI1GRXt5//L5SJ+5Xk2P5I1HHudMuiaeXpVO3kBVnFc2vZfq94cB1R0PVLJeRrUw5QXLOQQ5LxVXQp9lroT/pvpMxDkHfmQti63yZ9KTcB81zkVwHY88qfgCUR2n8zbLzwCIqKS0eCl/fpLGozVQ3gRickBAElUpb3nXlTkZ6hs+llwk5GIjBwAukvG2cBGZgIwrzilfMkUBPotWQXOFXFzofj7i2KhviNvSNC3NdINODeU5xwGKzzn5GR9X3gaej968y4WyAVImcMrGoeUKVjseqID03YazzzSgKg5Kfp8T33GJOOckD6IsjpGild88E41Ghe8Z3WiraZrwEfT5fOKoXxYJNU3DyMiIuJB0fX1duN1Q7CJZV6VqryqsDXEyfIJSmygOFQejQCAgRBzeV6Q/4/oeEhO5LRPVhy9yWvjEzXAApPrRGFAd6RmVSWIoBwrSY/HQPbxtlCfpyLi+Sw5HnJeXB7vdjng8Lrg8AnPi3mTjTq6X5DcC8bbIczCXha0nkqkAJVewktPq5SenlTcFTrscFSN5B5AXHk1ibjwZjUbT3DhInCMnYDrJI10Hz1OPC6Pni4uL6OvrQ11dnbCRGh4eFvGV3G43nnrqKdTX1+PBgwd46623sLm5iX379uH48eMCBKj+RmMqPMsHH3yAPXv24Nlnn0U4HEZvby8aGhrEdUqUlnNIMqemEleofxKJBObm5lBcXCx0QBRylxalpqWuFSeulCu6ucU5gY7FYhGW3BS7ngN+MpkUfUygQtwP59xoMdB4yRwRrwcBAOdcyY2I3jWbzUKspfZFIhERe4vPG+LY4vG40H3Sbw6HI02cp74OhULCrIGXTXqwTGIYH/uHWeiq9/+upJImVOX8XesLPAJAJRPfhdfW1jAwMIDl5WUUFxejubkZ8/PzuHTpkrjVuLi4GE888QSKi4tx7do1jI+Pw2hMubtQ8DSZS+HlcAqHwzh9+jSuX7+O/Px8NDc3IxAI4P333xeGk4ODgzh37hzcbjc++eQTbG1tobS0FP39/aitrUVDQ4NYLMTFGI1GLC8vIxgMYv/+/aIetIDINsxsNsNut2NzcxNra2vCNMFgSOns1tbWMDExgUAggGg0itbWVtTW1iIvLw9jY2P4/ve/j29961uwWq3CYZZEGDp2J45vY2MDwWBQmGBQnUgBTmOwtbWFtbU1EelB1pEB6Qa7pIQmACKFNIEB5+Y4IBNXJAMrP5mkcrkoHIvFhI0bJ84hEZByLoIAi9tgEVmtVmxubgrwNZvNIq4Zb28mPVMuXEqu4lkulAs3lkt5D1su0Y4HKhWaGwwGLC4u4tVXX8X8/Dx8Ph8GBwexvr6OWCyG6elp7N+/X4S0nZiYgN/vx9zcHGZmZgR3RYtlayt1gw25rMg6MV6Pqqoq3L17Vxxla5qGPXv24Omnn0ZNTQ0qKytx9epVcQX7N7/5Tfj9fvzFX/wFJiYmhGuNvKjJIv7u3buora0VnMeZM2cwOjqKWCwGl8uFJ598EiMjI/j4449FHCWfz4cXXnhB3NPndruxurqKhYUFlJSUwOFwIBKJpIk/ZGlP3BAtfrfbDZfLJcQ6Ll6SfshiscBmswGAqJfdbhd2XwQg/CIDzpHQ8T+JdVys51yYSswl7k7mvGQuhrg7EtWBz05nqRwCXa5jovc4kHFgpDZy0wner9RWSqNSRTzsfM/0/PNwOXqAlE0U/LuInjseqID0TqJdfG5uDqurq/jpn/5plJSU4M0338Tc3BxcLhcaGhrw3HPPIR6PY35+HolEAtevX8fg4KCwMv7www/x8ssvo6ioCPPz8/jwww/x+OOPo7q6Om1RUPlAis3v6urCmTNnxOS12Ww4fvy4OOJeWVlBNBoVup7q6mpYrVaUl5cLp2eV/iIvLw8ejwc3b95MC0lss9kECIyMjODWrVsIBoMwGlMxsoqKirC8vIzp6WlMT0+jsrISjY2N6O/vRyAQQDweh81mQ1VVFb75zW+ioKBA6HWIS3C73QIcSGze2NhI4wxIJ7S5uYmNjQ1xSmc2m8VtL2T8yi3veQQC4thCoVDarTiUhnM43E2HgIPENA4I3AyBAx43caDxI8CiZ2SoS/MK+OxEkfRrXEdF7kCkhyQwl/WdsiilEquIeBp5TuitBVVeevnwZ38XkZHnQXNCD7xUtOOBincKfTaZTAiFQigoKEBZWRncbjeKi4uxsLAgFt/q6qqIqrBnzx7BNVCefr9fRIlcX1/H7OzsNitpeSD4yRfXCZFh5vXr13H69Gl0dXXBaDSitLRUcC0OhyPNdIG3b2trCy6XC21tbeIWZyBl1Do+Po7p6WkAEBbkBoMBnZ2dmJ+fF7qwcDiMWCyGyclJLCwsIBQKiThSwGcGlQRcmpYKmRuNRuFyuQSnYLPZhP6K68Q2Nzdhs9lEW+mmGQqjIx/7E2BRn/P475z4vXzUx8TtcvGSG6Ry8wcCEnqX2zbRu1QPKstgMKSBDh9PagtF3ODlxWIx0U+UPi8vLy2sD9ejZeOCsnFDeiCgOlihcrMpyR+GVOD3sABF9MgAFQesRCIhdA/0nXbczc1NjI2NYXV1FRsbG9jc3ER5eTmKioowNTWF6elp2O12HDlyBHa7HZqmwefz4fnnn0dpaWlGBSItdm6kSNzDzZs38cMf/hAlJSU4deoU7t27JyY8cR0kUskKeopUQFE3r1+/juLiYoyPj2NiYgKtra0oLCzEtWvXRHvtdruoh8lkEidVXq9XhFVuamoSepZbt27h+vXr+NrXviZ87kgxvrq6mtbfZIlNXA0ZWXLLdQJAt9stYn3Jynw+oemQg5+acYChNATmFGeK+pgvRAIkEuEJhGgsCCRp4+E6QQ5O/ASZyqbTPNJR0cEB5RcOh4U+j3OExAXTySSRbMZB8ygXQJGV3ap8eFoV56QSIbMpzeX3somEudCOByogvdP4pKYTMT4B4/E4zGYzysrKsGfPHlRVVaGurg4XL17EyMiIEFNu376Nffv2CRcYn8+3jWWX68BPpqg8CtJ27tw5VFZWCnFyYmICi4uLIi733NycsJKn/Ii7IlHTarWip6dHxLkiq3DiMmKxmIi5DaRuQ/Z4PCIKaX5+PgKBAO7cuYNoNIqysjKxiEpKStDZ2SlOQPlikXU8q6ur4tQL+Mzam2yQOAdFhqL0jNrHj/9JjCK9EBl20nfZ7orGWHbe5mIiPSOw5jZMZHnPxUf+eXNzE9FoVHBV/JSU2stNK8iynTYHzvGR2QY3NqV68LHlQCJvVESZAIZ+l3W1HGhVnBuXDGTxTX7O+5rPDVX9VN8z0SMBVHyAuOUx2QBtbm6K2FAA0NramhbNMhaLYWpqSuzogUAAwWBQsPzDw8O4fPkyTp06hYaGhjRxghMBFS1WgyGl1D937hyCwSDKyspw5swZFBcXo6amBkVFRfjggw+QSCSwZ88eNDc3i/YQ0a7udDphsVhQVlaGnp4eoQgvLi7G6OgojEYjHA4HqqqqYDCkohPQlfTxeBxlZWUCIOl0kDgqTdNQW1uL2traNJ0OtYn+08QkmyWv1ytMP7gJARd9+LvcdIA+E5gRkNHpJSnzw+GwcIEh8Zy733BxlfIjAJCt5YnbpP8EJlwUs1gsiMfjgtPl4ZApvI2maWnuPFarFaFQSIRXBiDuLQyFQkgmk3A6nQKsqE9krkTWWeW60GWAkz+r/utxWPRdBWCqMnOtWzba8UCl6kyajNPT07hy5QpisRju3buHrq4uRKNREaGAREO73Y5jx44hEAhgfn4eZWVlOH78uDDApFhU5ISsN8C0MIuLi0X4FAAoKSmB0+kUiubKykr4/X48+eSTuHPnDiwWC7q7u+H1erftUBQ++OTJkygtLYXFYsG+ffsQjUbh9XpRUVGRdkJFdabFTLHRaQG1tLRssybnRrG8TXqfDYaU3dHMzIyInMDtzGRbKW5wKbuucDs3OmGzWq1C7CYRjyIX0AInYCYw4uYHVCb9pzEEPrv8guumCDzIrow4cXJG5qd24XBY2JcRV2symeB0OoXzNY0D9VU4HEYoFEoT81TAJM9pPd0VpVFZp38ekMs05vL3TOKmXP7D6Kp2PFBxokmcl5eHmpoa3Lt3T9xqUl1djfb2dgwPD4vwJZztzs/PF2FYioqK4HQ6RYdTMDZ+Q4jMYgOpgXI4HDh27Ji4SqmwsBBf+cpXxAQmfY7RaERVVRXKy8vFM86B0G4PpBxeXS6XKMPj8YirrijIHN+pSSQiwKAFDnwWo0nmlHhb+K4sK0y5iEUXVhgMBnGzMOmuCGSAz0RD8pGjRU8LnsCVbLK4kp70QASo1EfxeFxc/85dZDhAGgwpY0+KXsHFSxJJqb+4u5AMXmReQfZq8tgTl8nFWjL3oL4hcVBWaOfKreiBD3/GgUuP9IBDBVZ6YCT/58DE36N5kgsZtIcRFH+CaH19HR6PB6+++qrQlfAJtLW1hWAwKCY5RTvY2NgQl0sC6W4ZXFSQxRd+hK4aHHlH4wsSwLaFxN/j5ggyR8U5H/pdtoTm9eR1UZHsb6Y3KfUWC/+d6sc3CLfbLW4cpnHgJgUEWvF4HPF4PC2CJqUhLoaL0QDS9F28vjydSnTlCnAOghx0ZZsu+p3KdjqdcDgcCIVCaU7JVBeug+LmEgCEQSnnXPm7NK/09FR6eie9MVPpr1SkmsdEfL5mmwPyd74GQqEQvvGNbyAQCOjeqA08YhwVH1ij0SjC6vJIARRVUiWn80nE9Sq5sLTyJJHfkxWkMkfDFcDyZJXbJ4MS/ed6JLlcqpPMIdHnTG3idVGloTwTiQTW1taEfmlzczPNKJQbTgIQZgxUT65spjzJ5ILbVRkMBqytrSEajcLv96dtDJQvX1B0Ckw2UdzCXl7UcqSEubk5LCwsoLOzUwQGlPtF9ccDBfL6ZBOtVEagqg2RP5ft7uRyVM9Uc1OVf6Y85Hmo4qxypUcKqIiog2TuREb8TACS6bNeeZnSqLgY+Zlq4ciTiIOQahckzkIFPhzEePl895R/yzRZZS6SFM7z8/Pwer1KcZbXVW4P5yqojP7+fiwvL2Pfvn0oLS2FwWDAwsIC3nzzTeTn5+MrX/lKmu5KNiAl7ob3j+qkivc9/TeZUhfPXr58GXV1ddt0iLz/uHhN7eGnnHJfc+NV/g7vH/m5PJ6873hb9PJUPcvESWcSN+X5pVfHXOmRuC6Lk7wQVRNQBRr8u94gyKQCMj3uRK98PQBTTVpZHJHLpYVKYkwsFkuLrslFLN5XqgkukzyBeZm8nhMTE/je976HhYUFATwcQDhgyQDF89e0z0Symzdv4vTp0wiHw9jY2MB7770n3I14PCryTwwEAggEAtjY2BAuL0RLS0tCSU6cD5AyD6GoF7xupBfjOi0+PnqbotxPMijp/akWfKa08qYk/3HdHv/LllaPe85WzufhpoBHkKPKxNWofpcXnWpw5HT8N9XupQc4cp48D85Rqbggfpw/PT2NyclJof8ht5Z4PI7CwkLs27cPZrMZZ8+eFcp9lWjJOTDKm9dD3rFJZOLRKWSACQQCmJmZEeYglJbEL1mRL/cLL99oNGL//v0Ih8O4cuUK+vr6EIvFcP/+fTzxxBNobW0V9ZydncW1a9eEWYHdbkc0GoXb7caBAwfg9XoxPT2N1157Dc899xyamppE366srOD73/8+nn/++bQbaDiHx00LVKIWbwPn0rkuTG8O8P7LlK/qvWyAoPqdA0qmtHobpgpA+Tufh6Pa8UClWtzy79nezfS7Hlus+pyJ5c5GqsGmSc51Z4lEQlypbjAYcO/ePQQCARw6dAjFxcUoKioSRoaDg4Nptw1TOTKQEsdA/8lGiMwEiFtZWVmB1WrF2tqa8BMEgPLycpSUlAh3EfqjW3xu3rwJt9uNffv2wePxKPtW1V/E8Rw8eBAAcOXKFQSDQRw+fBj79+8XkR22trbwzjvvIBQK4cUXXxThmycnJ/Hmm2/CbDbj1KlTiMfjmJubE36KQAp06CIQujmI6rK1tSWu9OJiYzZOm4+/nuilByAqzlKeI3rzUI9Um48ex8TLVv2m974s2mZSHahoxwMVJ3kCfR5057shf5Ypreq5ql58cPX8vVRp+UQzGAxobW0Vxpxzc3NIJBI4evSoABVavMQtXLt2DXl5eSJ+eXl5OSorK2Gz2ZCXl4fFxUX09vamhc4NhULwer3o7u4WV8D/4Ac/gMlkgsPhgM1mg9VqFXckvvzyy4IbAYB79+7hxo0buHPnjrjqi6z7VX3F+4G3PZlMwuVy4eDBg5iYmMDW1hb27dsHp9MpdEPBYFDckdjQ0CBO/wgwV1ZWRJ4Uc4rroajNZNBJ9TAYDKioqMD+/fvh8XiUDs56cyZXLkNvQcv9QM9kIJBJj1PKJpLlyqlxcTiTFJAJkFX0SABVLuyvzD2pdhT5Nw4meu/K+WQaPCA30JMHWtaJGAyGtF1edZ8ccUVkbEhH9FtbW/j444/R0NCAU6dOwWBI2ZAVFRVhenpalD0/P4/BwUHk5eWJi1dnZmbw2GOP4cSJEyJW1O3bt/H9738fs7OzqKmpAZCycerr60M0GkV+fj66urqEIlwer2x9CyAtYia/GAL4bIc3m82YnZ3FyMgIPB4PNE3D+Pg44vG48GckO62xsTHU1tbCbDaL+xWJg5VNRbhhMBkSq+rL/QLltmXitFXPsnFhD8Otyxy0XppMz1Qcmd5mzD9nWmMy7XigkieBHjjoiRZ6+entEnKZ2QY5l7pn+sxZaq48pXS0EPl73K/O5/PhscceE0amGxsbuHfvHhYXF8Wku3nzJs6fPy/S0zX25H5DHJrRaER+fr5wPdI0DQUFBcIUgUfn3LdvH4xGI+7fv4+PPvoIk5OT6OrqQnFxsXLT4H2u6mfaxbnuiOpvs9mwd+9e9PX14fvf/764Lj0YDKKiogKtra3i4oUjR47gzp07eOONN8QdfU6nE/X19WkRLKjs9fV1PHjwAPX19Wl2QHqcMG9HNk5LlVZFKu4+G4ekokxpM81jmcMl4uYgqs31YeiRAKpcdpqHAZRME0v1PNsOo/eOXpnAdtsbeWemCcPDtJCym+dP3AC9T1wFAcvq6iquXLkCg8GAJ598UnBPFy9exPz8fBqrzyMa8Pjm3KAzmUwFziNn77a2NgwODuLOnTtYXV0VkVNV/ZBNX9jW1iZifHGyWCw4fvw4Ojo6EAwGhdinaSkrfnJ9slqtOH78OLq7u0VfaFrKjzIcDou+4n81NTUoLCyEz+cT9ZB1SapxzsS9yFy3ikPT0+HpgbkK8FQcnup7NpDSe5dzvHpgu8tR/S3pDSz9lm3CAGqzAaJcQIuXpdIt8HdzYb9VkxBIBy++s8lxneh3AhLZmp44M4pUUF1djaGhIZw7dw4ejwfJZBILCwvw+XzCaNZoNKKwsFAosDXts2BxjY2NwpWHTh2LiopgsVhQXFwMn8+HxsZGxONxuN3ujH2hWnAGQ8rqvb29XXwG0vV8FosFRUVF8Pv92/LhJ28mkwkFBQWiTTRmPBghf99ut4tLS7mxqh7AZuOg5DHX00XJ4y9zN5nmGU+bjQPLhatX1YUfKsiuO7zcXNx6gEcAqIB0PcHDsJzZ9AV6O41qoWWakHrclup5Ng6O/9/a2oLT6RRtByDMB0wmEyorK+H1ercF8uvq6oLNZhPRAU6ePCmAhE65yMmZLhUtKSnBSy+9JHwYiShWF9kj0Qkg+c/R4i4tLVX2R6Y+lK37eWA9vjGoxHSVcSeVpxKnM/k/8rSZxkfPvo2Pdy7zMxOXycFBBQh6Kgs9YJPLywRWvJxMmzG3rt8FKkbZBj8bN6OaVKr3eRoVt8YXz+epox4npbc4jEYjenp60gLV0eRwOBx44oknROx2mjDEmfBFRdFD+W4p14lMFSgvAgHuF0l//CJQEsH0xBmZE9Xrd7l/ZdFYHg85b3ks9ECFvucKKvw9vXmRy7ty/TJJCbwcWQzV60OensqQ02daBzwfbl8mv/MwHCWnHQ9UepM5E3cip+WUCRxUACKLKPK7mSZuNrGA79KqnS4vLw+VlZVp7eXvkM2SrADlYo4qwJ1sZS078sqTXd7VVaBLv8vvU/7ctYTeU+mCKD/uKsTrIJM8PvxPfj8TJ5PL4uPt5lyFCjDlRS7no0org4EKHFQAIudhMHx2r6LKD1GVr2r+qTYY/iyXNUi044FKtfPpAYXcaTLg8DSqPPTYajkvVR4yqSaCHpem976Kg+D5qEKSqLg21Q4ttyNbm7ItInmxqoBA5tZkrkdedDwf1YYh1x1ItyrPdRHx9HJ/8nwMBsO26A38HQ4KKm6JiKeTgVvlYSCfBMtzlDhf/h65U8njoNI3ZQJwFSDpzeVMtOOBSuUOIE8GvQksp1f9xsvJtMvmwjbLz1T1Vg2yinNTTQL+XLWYM5WpKkeuv6pMypOPA19M/H0VSNJJIQ+NQjo2XqdMOhm5vdk2CD0uWNXnKtAmIoAIhUIYGRnB7OysiF3Gbb14X1NbeX48gJ88ttxlSdM+C4OjN6dU/6m/+HO+GWTigPTWQqYNS68OmWjHAxWgjuWst6iykTyB6WheDyhUnAM9lx1GeYA2GUDlcvnElesuLy7V5FCBE4k7fOFn6h8VBymnl5/xOFRczOLvUNuWlpYwMDCARCIBh8OB5eVlAEBTUxNaWlq2xQBTgQn/LwMkT8c5Cl4nDhzyuKqMOPl7m5ubmJmZQW9vLyYmJuB0OjEyMoLy8nLs27cPFRUVaW3g5XPOhSv1ZX867rYjt2trawsPHjyA2WxGTU2NkpNUcZOZzAl42fyzvEGo5qs8HrR2cqEdD1QyOKm4Ej2OQG8XVrGxvDy93YI4C56GJhm/8EEP8OT3+H85vdweGTB5+my6Iz3uQpVGlT89k5Ws8ljQeyaTCRMTE3jjjTdgsVhw+PBheDwe5Ofno6+vD++++y5cLhdqa2tFn1K/Uohhbo3P603xq2w2m7hTz+FwpN3erGkaAoGAiB5qNKaieGYSGeV+MJlMGB4exhtvvIGCggI8++yzKCsrw8zMDM6cOYPXXnsNX//611FZWSnC3wSDwbS+djgcaRfVcp9LmjdkRkJXmPExiMViWFlZETZesl6MjIGj0agw3DUYDOIkV69t2Z7rcV7y81y5KeARACpguxIQ2M6l6IGLnjgo56mXTs6DFiw/mte07bf38rjmBoMhDcji8bgI0kaB/jjpKZlVu24mFlzebWURQMWdyhyCDEqZ+ofnvbCwgI2NDbzwwgvo7u4WXJbH48HS0pLwC9za2sLKygpGR0fhdDrF5a0OhwN79uwRrjn9/f1YXFzE/Pw8NE2D3+/H1tYW1tfX0dTUhAMHDsBsNmNoaAi3b9/G2tqasETf2NiA3+/H4cOHUVZWlrMIubq6isXFRRw5cgQVFRUwmUyorq5GQ0MDzp8/Ly6UXVtbw5UrVzA1NYWioiLYbDZEIhEYjUY0NTVhz549Anhu3ryJ5eXlNEd0i8WCtrY2FBUVifmlaRoePHiACxcuoKOjAzU1NWnvxONxXL58WRgAh0IhMa9KS0uxb98+FBQU6Lr+ZGp3LiBF466SbFT0SAEVkFkPJS8k+ZkeO6wSXVTpVY7GW1tbuH//PiYmJkQIEgKrwsJC1NXViSiVNGnGx8fx6aefiqvYya9P1TY5RIseJ0l1IeITlCZ4PB5Pc4Xhfm5Ei4uLWF1dFVdEWSwW+Hw++P3+tPAvcv/Ln5PJVMz0/Pz8NPGmsrIS1dXVIrb74OAgLl26hKKiIhQXF4uwvjdu3MDIyAhefPFF+Hw+3LhxA/fv30dHRwcmJycxNzeHffv2YXBwELFYDJ2dnUgkEvj444+xvr6OU6dOoaKiAvF4HO+88w7OnDkDn8+H4uLitIsq9ICfNheDIRXBgq4Qi0ajmJqaQjgcFtzR7du38dFHH+HAgQPYv38/LBYLAoEALl68iI8++giFhYXwer3Cop8uAUkmk5iZmcH4+DhmZ2fx0ksvpcWkLy8vh81mw8LCgtBl0TzZ3NxEf38/NC3lME79PD4+jnfffReBQAAvvvhimueCPE6qdmcCNdX83AWqvyVZNAIyy+d6Ha0HaiqQ4mn4+7KRocFgQDQaxeXLlzE7O4sDBw7A7XbDaDRifn4ely9fxuTkJJ599tm08Cder1fsfvICp/Lj8bi4fp7Kzs/PT3MvicViWFxcFLtpNBpFIpFAUVERysrKhNixtraG/v5+LCwsCEPQeDyOmpoatLa2CvGhr68Pd+7cEeVomoaZmRk4nU5x3X2mWE28P7mfGDdN4G45BoMB09PTCIfD6OnpQXV1teA65+fnMTQ0JMwqrFYrqqqq8PTTT+ODDz5AMBjEoUOHMD8/n3bNVTAYRDAYxM2bN3H37l0kEglEIhHs27cPjY2NaSDF54W8qZGrEBnWNjc3C9Hy/v37+OSTT0Rdi4uLUV5ejpWVFTx48EBc/rC0tIT19XVEIhEUFhZidHQU7733HhKJBMrKyqBpmvCjnJubSxN/DYbUxRX5+fmIRCJprlO87i6XC2VlZWKD3LNnD3w+nwggSEa0uWwwqrGU14meVJONdjxQUcdwhSiRSufDf+N50DPVUa+eSCVzV3I9aBGGw2GUlJTg+PHjQj+wtLSE2dlZBAKBbcfwdIcfLQiet9FoxOLiIq5du4bl5WVhmR6JROByudDe3i6iGEQiEYyPjwsOCAAmJycBAPv378eBAwcQjUbx/e9/H6Ojo9i3bx/q6+uFCw2/DGFlZQVXr16FzWZDdXW1EMMmJiawsLCQFiKF95E8Hvw7HZHzW3Pm5uZw//59NDU1CZ/AWCyWdgNMPB5HLBYTXB3lQ6eGxD1QmJdwOCwWudVqhdlsRkdHB6qqqkT/krsQvzWZLzqVgSiQsmUrLy9HbW1tmm3ShQsXRLyumpoavPzyy5iYmBA3MFutVjidTqytrQnVwO3btzEyMoKvfOUr2L9/PzQtdeXb+Pi40L3JhyDJZCpwIt3QTPUj9yiKokHz32w2w2azCYDX48Ll8cumOpCf60knerTjgUqmXDtGFouoczkwEKlATQVesk6HK0nD4TDu3LkDh8MBgyF1qeni4iI6OzuFJTflK183RQAKpLz5P/30UwwNDaGzsxM1NTWIxWLo7+/H/fv3YTabUVFRIXZ7ozF1cScAwVUtLy8LPQWQcoOhYHx0/RVdxur1elFSUiI4uEQigfHxcQGk5HxcX1+fJvqpxGze13QF+vDwsLizj3Q58Xgce/bsAZAyWrVYLLh69SrW19cRi8WwtLSEiYkJNDU1oaCgQIigdAPy0aNHhbLa6XSKu/dMJhMOHDiAa9euob+/H0NDQ2JBl5aW4ujRo9siURCpnMStViv8fr8AJxo7Us7TDTs0fmazGaWlpTCZTOI2G9p8AKCxsRGTk5MYGhoS47C0tASTySSueKMNKxQK4fTp0xgeHobRaMTly5fR09ODsrIyUUefz4dwOCw2Tdp08vPzEQwGt9nMyfNW1Q+qjVvWUfJn2ThsokcCqFSnNSrZWO5MlW5JtsrmpAeCfICB9NMXCmG7vr6Oe/fuweVyQdNSF4ueOnUKe/fuFWIU55ooLAvPkyzIl5aWkEgksLGxgfHxcXEtWFtbmwhDHI1GcfHiRQwMDKC1tRUVFRUAUu4y169fF3V0OBzYv38/ysrKhH9fJBLB9evXcenSJdjtdsHZWCwWwVH5/X6xMPm9eTLbr9pZDQYDqqqq0NXVheXlZfT19cHlciEcDsPr9aKnpwclJSUAgPb2dvh8PszPzwvxxu/3o7KyEnV1deKi0q6uLiSTSXEHIi3O/fv3i2u5CKgaGhrEDczUD+R4zMdaTxlM7SktLcXzzz+PsrKyNKDy+/342te+huLiYgFi4XAYg4ODGBsbg8lkQjAYxNbWFk6cOCEcuhsaGlBYWIhAICBOAEtKStDZ2Smco2ku5OXlCSU6XVLrdrvF7xaLBQcOHEgzE6E27d+/H83NzbDb7UpJQ08dIq8FmdtSAd6ujoqRLCfn2jlEsm1IpjKypeNpCPjMZjOqqqrw7LPPpi0I2r3lyURXm9Nv8v12JpMJVqsVRUVF4tRra2sLXq8XPp9PiAPT09NiB3U4HNjY2EAwGBR1NBgM2NjYwLVr17CxsSHiLVH89aqqKtTU1IjICY899hhGR0cxPDyMyclJwaXU1NSgsrJSqfBX9ZXBYIDf78epU6fE6RfdsygfxVutVtTX1wv9F494QGQ0GoV+SbaLqqqqStuQLBaLAFniAGW7Nrmuqg2LwK26unrbfLPZbKiqqgKQ4mJNJpO4xYbGisIc5+fnpx2WFBQUiJNePp9lQKGoFzSPSMTj7aioqNimOzIajSgrKxNzLtPGrAfSqv6RNyngs8tuc6FHAqiI9CZaLu/oyeb0XY9LozJU4iIBFYEVt+fh5dJCSSaTiEQiuHv3LmZnZ+FyuXDjxg0RRoXyqaysRDQaxeLiIoLBoDipKyoqgsfjgd1uh81mw/79+zE8PCzihAOpRXTo0CFUVlaKW4r37t2LhYUFcYplNpvR1NQEv9+PoqIiJJNJuN1u9PT0oKmpSSxSYu0pOoOss+P9z8GFRFt+dbvcZwQ6HHxkgOIcKOll6Dm9yxcof4f0W9xkRDVvVG2hz1x04iBNY059Q3o4n8+37XSWgwX3haR6ZfKIIDGTbtWR5zDnyFXzXC43E2Wa+wS+/PvDMgs7Hqg+T6cAuR3DZlIk8vR6Ig8tIlqQqrxkvUAwGEQ0GkVdXZ0wD+AneQ6HA4899pgIy0ILNC8vTxhNklK5ra0NDQ0Nafou4s5IVMvLy0N1dbXgWGihkHjBdXY8SgNvo6wDyQZUcr9x40b+PtmWAenmFFzPRd+5GEffOSjwRWswGAS48gWmGmeZQ+N1JpKtzgGkgSSfT7yt8kGC3ryjZ9Qfct+o5hUnGcBkUY33m4r0+obnLY/zw0o3Ox6oiPQ4nlzFNHkREXFOIVfiE9pms+HgwYPiQk7Kny88bkTp9Xpx4MABoWtSXa7pcDiEywTfhUkE4NwF/aeFwO2i+LvEHdEC5Mf0KhDhi4mLrfIilndrDiScZLsu+bRTBgxuP8bz5RSPx4V9k9lsFrG0VlZWRPxzp9OZFmLYYEiZazidzjRQpv9Un3A4jOXlZRgMBhQVFcFsNmNtbS3thJGe8zHnfWU0GhGJRNLuJqR6R6NRwfHS+3RvIdlS0UbCgU4mmXvjYy+PVaY1pDf/5c2DjwNXV2SjRwKosnE/8m+8M1UnH7J/VabBU7HcVAYZTXK/NXnQ+aQlJSgdYcvtUnEVql1bBhFVv8iuPpqmpenKuEjC31HVY3NzMy1MscFgELY9TqczbQy4jVkymRTGmXSSVVpaiubm5m0gLI8l8BmYUv153cLhMK5du4bV1VUAqUsuDh48iFAohIsXL8LhcAAAmpubceDAAaEnunfvHq5cuYLnn39e6LI4kBuNRgSDQXzyySeIRCKwWq0oKSnB3r17ce3aNXGRxsbGBsrLy3Hs2LFtfobUzwsLCzh37hx6enrEKefq6irOnj2LYDAIm82G7u5uoWcje7yWlha0tbUp55Oqn/TAigO+LBrK60M1p+SyOEDx9uZCjwRQAWrHZPoOqG07eFp5MdAgkqjEJyyVx69a4u/K+ZHuhw+6XB96h8ri7je8ffSO6jRHtTvS73T6aDB8FimT95m84FUAx9PRop2ZmcHS0hJaWlpEO4PBIC5evIhYLIaOjg5x4kh5cN3I2toalpeXMT8/j5qaGthstm3gzye73CfEncmAQpbhhw4dgqZpeOutt8S1WQ0NDcKlhv62trYwMjKCM2fOCDMIWYShvpmYmMDGxgZOnToFALh48SL8fj9isRiam5tRXV2N5eVl9Pf3IxqNCrCOxWKCSwNSpibz8/PiPsFkMom7d+/CYDDg8ccfx8TEBPr6+lBYWIiZmRmsra2hpaUF09PTaQcpfG7JpCdKZvqvIhUXLRP1/a7op6BcRDsi1S6jAi0ZOOi/fFMu1xHoAaJcPxVHRBONgJF+JyU5AGFzY7VaEQqFEAwGkUgk4HQ6xfVQ/BSL3pmensb8/DxWV1dhNBqFFTWvNwGfrFiWuT2jMeUgS3ZLy8vLeOutt0TcdOIcrl27hnA4jMLCQgwMDMDj8YhY7FwUMJlM6OjoQHl5Ofr7+3HkyBG43W6h6AYgfCRpgdM17clkEh6PBw6HQ4zVvXv3UF5eDp/PB5fLhSNHjsDhcODSpUvY3NwU9xNSiGU+BvPz8zhz5gwaGxuxtLSkFFcp7ebmJurq6lBaWoqtrS34fD4BQg6HQzgJu1wuYaQaDAZx+/ZttLS0iLjx1dXVwqyC5lNzczNsNhvsdjtcLheWl5exvr6O+/fvo66uDu3t7VhfX8fQ0BCKioq2eULI80wmvY1HL70MODJ3Rf85Jy7/lgvteKAC1GKNKo2KS5A5L56WgxYBCGdrVfnIHEkm1lrmFAKBACYmJlBTU4N4PI7+/n6sra0BSC3Y5uZmVFZW4tKlS+LWFIfDgZ6eHni93rT2G40pj/1AIID19XWMjIygubk5zXBQTq/iODlIhcNhAZakI2lsbBScitFoxPLyMpaWlnD48GG4XC588MEHWFpaSjN9IG6M3iFraeofcnEhq/2SkhLU1tYiGo3i5s2bon6lpaXo7u6Gy+VCKBTCwMAADIaUCxKdSo6Pj6O3txednZ0oKyvD3Nyc8AskE4yDBw9icHAQXq8XXV1dOHfunHAolrlV4uCo3zQtdchAG8rCwgK8Xi/m5uawtLQkrMnX19cxNjaG6upqsbHQSfDm5qboC+onTdMQjUYRi8XSgNlgMKCsrAx3794V9mF6XIseWKg2UJkygZGcP6VXcaC50o4HqkydIYuBKmABPoscQIZ5ZrNZcCdra2vCCNLr9aadtmQbFHkCEdfD/fOAFGexsrKCjz/+GMFgUFzDXlBQgPLycgDA1atXkZeXh7GxMUSjURw6dAgWiwV9fX1YXV2F1+vdJh46HA7s3bsXJSUliEaj6Onpgc/nE/f1JRIJYfhYUFCAZDKJxcVFbG1tiaP7qqoqAXpXrlxBYWGhuA3G7XYLAKH2LC8vw+12w+/3C5Ahn0XVZsCVurSAAoEA+vr6UFtbi+7ubqyvryMUCmFpaQkbGxs4fvw4zGYz7ty5g7W1NbjdbuEWU1xcLMpIJpMIBoPilmi6Sstms6GrqwuapuHevXuYnZ1FNBpFMBhEb2+v8MerqKjYFl6Fc5h8McfjccTjcVy9ehVTU1NYX19HRUWFuNHZ5XLh8OHDQu/F5wuFYOFgQN4GBkPKtopOXDVNg9vtFlwwn1cqe8BMm2k2Lko1h2XxT+amZLDaVab/LcniG3+uAgqZeJpoNIqxsTFUVFTA7XYjEAhgZGREuJi4XK60m1BkUYbrb3gdZN0UnThRTKVQKIQLFy5geXlZ7Jr5+fniWqepqSk4nU4UFxfjwYMHqKqqQmVlpchDPmJXnaCR35umaVhZWUFfXx82NjYQjUbh8XjQ1dWFUCiE8+fPQ9NSOrLi4mLY7Xb4/X5hhMo5H74wuOLbbreL00ra8TlAq8aI50dcw8mTJ+H1egV3s7q6ij179qC+vh6JRAKjo6PCx9BisaClpWXbxlRTU4PHH38cAwMDGB4eRmNjI2prawWwLy4uIh6Po66uThxk0EZF/SXrLzUtFfeKyqFr4i0WC1pbW9HR0SHAiQ4ZHA4HbDZb2gEA14Py/tjc3MS1a9cwNTWF559/Hi6XS4jc1F+kFqDv2UCKP+N/KiDic1VlwyZzUny+q9ZiLrTjgQrYfvTLn+ciK5M4Qn5wZOQYiUQQDofhdrsRiUTEdVIk9tDiI/bcaDQKFxna/U0mk3BvyMvLQywWw/Xr1+HxeITHfW9vLwKBAA4fPiy85PmEnp2dRV1dncgjFAphZWUFwWAQs7OzIjQJP6kE0k9suKFpKBTC6OgoWltbUVdXh+XlZWxubiIQCMDj8Yjj8ry8PKyurqKkpES4ZHDdjsxRytwR6fVoIfJxkXdtOb+CggI4HA4kk0nB1cjH+/LOvbi4KMwQiCu02Wxoa2tDLBbD+vq6cBuhulFbm5ub0dTUJACZfPLkcoDPwJ82CMrPYrGgsLAQJSUl0DRNOEwT8I+Pj6O4uFhwr1znx/vhzp07GBoawsmTJ1FeXi4U+3Nzc6iurkYgEMDq6qqYi3xjkvtZ9Uzv0EWmbByRPP4y+Onlq6JHAqhyUSLy3+WdQV5oRLTI4vE45ufnce3aNeTl5cFms6G+vh4ulwt9fX2YmJiA2WxGWVkZOjs7RdgUi8UiAKKjowM+nw/RaBQrKysi3Mvq6iqmpqZQVVUFg8EgnIMpqNni4qII/mY0GuF2uzE1NYWzZ88iGo1idXV1mwU2FwvkttICq6iowL59+4QrjtGYiuhQWloqFm80Gk1bnBSpQRYdaLEkkynL+VAoJGJvLS8vo6KiYtskVu3msiW1rC+TOVZO0WgUFy5cQHl5OQ4cOCCclwsKCmAymYRz79LSEqamptDR0QFNS5kx+Hy+tMCF/AowWVwCUm49KysrmJmZgc1mw+TkpAh+R+l4oESDIeXkfefOHeTl5aXdjcjNOgBgamoKFy5cwP79+1FZWYlwOIy8vDxUVFTg3r17qK6uxuzsrNg8yI5KtXGo5r7e7yoRTkWqDUZPUnkYruqRACoiVefr/Qak7+S0y/BFwDmERCIBq9WK/Px8LCws4MGDB3C73Zibm8PBgweFqGM2mzE9PQ2bzYaOjg6srq7i9u3biEQiQj9y7NgxEe6FFsfExAQSiQQWFhZERAIS0xwOB/Lz88X1WDabTXB8V69eFe2T2yCLZLzdVqs1jVOhXV+2leKnbwMDA3C5XGhsbBRp5fDKLpcLAAR4r62tCRMBFTjxenIOhsCPX+nE3XV4PgRwVVVV8Pl84v3p6Wn09/cLw89nn30WyWQSw8PDuHfvHra2thAKhdDR0ZHWDofDIUCAl0Hk8/lQWFiIvr4+oTeqra3FyMiIOGjgAA+kAKm+vj7Nj0/TNCFq0rgEAgGEQiHMzs5ifX0dFosF7e3tqKysTItX9cwzz2wz2pT7JZvuVMWVZnpf5iz5+PH3H4ZxIHpkgEqvQzJ1FN8t+WKOx+MYGRkRCmWTySROmEjPEAgExIIOBAIwmUxwu91Cqbq0tIQbN25gfX1dcEJAasLS8TTF8z5w4IAQyYaGhlBRUbEtTDHpMqxWK8rKymA0GjEwMIBkMinC9nJDVSDdaE/TPjNfoF2YJhfflTUtdY25xWJBMBgUgBWPx7G4uCjsnAAIPQ63M8vPz0dFRQVu3LghFjCFBaY6yaKC2WwWtyuTqFdXV5dmKGk0phyjObhXV1fD5/Nha2sLVqsV7e3t4h2Hw4H6+noxvl1dXaisrEQikcDBgwfFxuF2u1FSUiJEsby8PNTV1QldnGpRU8QJitnldrvh9XpRU1MjgIubDWhaykOBghASJZNJ+P1+IY5qWspk4YknnhBioclkEj6iPT09mJubg9vtFocGmcQ2WfUhG2/yz3QSyzdvlU6K583HRlUP6odc6JEDKr3O1XtGz6nzSUk7MjKCiooKoV8hsKAJRADh8XgwMTEh4hppmiassj0eD/x+P0pLS+F2u5FMpkJ3DA8PixM9u90uAt2tra1hdnY2TQ/EbbeIU0gkEhgaGkJ/fz9aW1tRWFi4rf18wpH4ymMtyTot0tdYrVbU1dUBgBBRSaTr7OwUgEsL0eFwpF3hnpeXlwYQra2t23Zm+XDB4XAI0dZgSB0keDwe8Z3+060uBCpVVVVpYi8Xo4xGI/x+vwA3zsHU19dv4xz4QqPQ0HriqtFohNPpFPlQnQoLC9PmmR4HydvvdDqFlTwAOJ1OHDp0KG1saAzJSZzXRyUi83mtVwcZrGRuKZOeSeaysomLudAjA1REsrinYmVVVrw04ebm5rC4uAgACAaD4hYRfjJD+fr9frhcLlgsFiQSCREuxWKxoKGhAW1tbdjc3BQnRGT+MDo6KhYmnQBy7ofEHaoXF0MSiQQuXLiAkZERtLS0oKurS5weck6J8gJSJ2IEJpqWOt6ur68XvoHUZ5WVlcK2J5FIYM+ePWnGpGRyQKdPBoMBLpdLuLxQ/9rtdnECJxskyuIG/ee3yhCXJo8p50ZkUYUvVs4tctCQiXOC3I5M5jxozOXTXCpLVmbzPDgRl8w5X15P+o1Cw5D4KwOJLJJSWTIHJeudMnE3cj/pcWCZSKXnyhW8djxQ6SnzchH55N3HZDIhHA4jFoth37596O3thdvtTtMzEFdE+qPBwUGx4MkNJBaLYWpqCgsLCyJaJe3sNpsN+/btEyeLQLoRaXFxcRrw5OfnCyNNArWysjI0NzcL8AE+E+/4YiOuiU7QqN0Ut4rfpMxFKw5MpJ+jOsrH4KqontQWqods9CoDAD0jjpW/z0leMKpxlDkhOY2sg5TbwBe9PF9kEOCiNOWtEvtoLPi7HLRlUJNds2SbLSqDt5WDBK+H3H+ZJA++2cj9SmkflmvKtA457XigAvQnrCqdLH/z32w2G5qbmxGNRtHa2or19XXs3btXBN+ngfd4PMI9grgkk8kk9CBut1sEgrPZbCI0MH0vLS1NG0Ca2C6XCy0tLbDb7WkxjLi+imJFyRyHbITI/5MSn5fHSZ6g9EyPO5UBnvetTKp+Vuk85LqoQEoPuFTf5XL4+zKHJ4tZvF3yM14GgTAHN95vXAzl+anAUzbWld+R08v50++cA9PbEOQ+U4FXJm5Ir19V5eZKjwRQqRYDf67H/ssyvMlkQltbm9A3HT16VPhxkdiTTCZRUlIi3iEAo9OoZDIVZ7ygoACapqXphfQWMhc/uCU06Ya4roYvBj6hVKCimqB6IKHXh9l+k79n2gx4e7OVL7+TywJQiV+8TBVnJIO2DEaZ2popvdz3udRZJr33OCiqxDoV8HMOTS5br/65ck96aXeBilG2RaNayHrpuK8VABQVFUHTNMEN0Tv0nb9LYCNPIrk8GRwpPVcK891VFrn02p9p0vFy9EBH9Z/3XbZJy+tOoCtzBXpgk42byRWg9EQgvfGXuQm9DU2PVBwsp0z1VrWV111lLsPflcdGnk96ddIj1VzRG3cVEKra8jD0SACVSnHJfyfSGwAV287f5WlVilOeVuUHlik/Xr6qnnrAIZev12ZV/jyditPLtMBy4ThkPZYMOLwMLq7oiaSqvPTakqnfVaQHZJnSys/kNqm+ZwMPPRFKrw9knVe2ehPJCvKHrau8yfK8cnXjUdGOBypg+5E8UbYJKn/O1qmZuBW9XS0TydyYSmzIxs3Iu5g8yTJNZD0g4iRzi3LdVW3VW3RyOdzcQ+ZMsnEGqvblykFkAhtVmkzcBU+TacPM9C4Hab7hqfpElZfevMw2rz8P50P56c2FXDhgFe14oOKL5WF2Fr28VOlyAQp5osnvPwxo6nFysviXbYLmWp78WW/hE7jw7zyN7MqRaXFz8UyPS8rEiVEdVYpwVT5yW3MBOtVzzoWqypNtxOTy9NqoSqdqE59nKrEx29jLbkr8v1wv/luunGSum75MOx6oOOlNnkydlssurBJvVJyL/HumxcPT6YlgD1vXh+Xo9N7XA075N75ByOYRcl1lFx4yoFUtTHmH5nWT85PLkzcOvXZ+HnFJ7g9ZR5VtI1FxQpm4o2yckyyGPQzJ40F5fl7i9VFJBtloxwOVvMhVbKn8PNNnOW9OKs5Nb2fRmzgqENDbhTLVTbXYsol4euKhKp1M2XZYnk61Y/P39MQGIn7cnql9mTYDvXnA66Na5Kr3VAtOHrNMY5cJcFV1zDZ3ctnYVGOtshHLRtnGQK+ODwugjwRQZVJeZ9oZ5UHLthAyDRL/jbu7cAdVvffkya43OeT68MnH88r0vkwPw+KrfpfrpQfcss5FVQ7npvTKz1YX/ky1MLMBRa4cuYrDAtIPWzIBqWqjzAT+PE+Zc8uVg+dt0au/qjzVBs3bSyT398NweTseqIDtna/qMNVk1ePC5HSq57KNjipvg+GzI3KVh7s8+LmKdqo287wzgS8nGaxV72eqlx43SOYJeqJNpt/451x2/kzAyjmPXDjcXL7rlZ9pM5Dz4lbl9DxXjlWeL6pNStWPudSPl6vaNHLhBvXqmo0eCaAi4oPCJwX/XY/0Frc8ofTeoe9yetXE09uhs4GWahfOpR6q/PXqIafVA3W5r2WltspCmv8mt1G1eFVtytQ/cnpV+1VjIgOFDG6ZOApVubytmeqZScTNxvHo1V9O9zDcTSYgypReBmC9DS8TPVJApRoUzsmo0mVbzDw9/643CKodXY/TUXFDnK3X4xRV72ers177MnFTKrZfNRHlCUvhSfglo5nEG9WiVKV/GE5Pbq/epsHbxA8E5PZz8xH+TqbyVWXIXJDcPlXd9PLTa1cmYMuUl6rcXLkmPQ45F4AEHgGgymUi6p3GqFhvVToVoOktYD3OQ5WPpn0WoC6XSaFqV6bFIgN2LotAbpOKy5M5E+Az3QznmvSckfXq+zDPeRszpclWJt8ECJBU76rKUM2rTNy4PO9Uc+hhwOrvSnoAp2p3rpvEw6Yh2vFARaQSG/gOxvUmRHqLlACEnvE85Pf57zy9qgy98jJNlGykV54MspnYcVW95EWTbTLLR/V6ICX3lZ4ZQS6LiJ7rLaJM4KfarPQ4ZT1uMxPJ3MTDLPRcgFc11+m7qo8epv5yX8icv6oeqvrvclRZSLULyAOZTRSQSV5gcjpeVq7HwPJOSkHyuMiklz4T6e3IeguR550NOPUAh/64yKdy18g2iVVlyX3L388VePXaRp9lsU+uk2rxq4hzlKq+yrZ4M+WbDVwoHU8vA/HfhXKp+8NsspweGaCSuZ1siJ8LUKl2wVycg1X1kNPIiyaZ/Cz+uMz5qfKSy1ZxlA8zMeU68fJU4CIDP8VQ4k7UqvrSc+42I9cjU1tVaXNtH6+vDH6ZFrIsDqrmAefE9cZPVWe9dLmKe9k4Tr18ss0vPc4sl3x4+lzHaMcDFS1yQK0D4v/lz3qDpQKxXHZu+TkXn3ieubh9yPllSyfXOdcJ8jBikwxSvCxqi8w5ZOJWs3Gmsmio1w+ZxEIVqcQ9Pa5LxanwdudCcr3lQHuq/Pi8yQQq2bheeb7nsomppAf6LI+1Ks9Mc0iPHgmg4gBAnaQ6PVOR3Nl8x1R1uCxG6Q2KPAF5etlfi8BW3q1l04pcWP9s7VW1X/Wf8skFTKluKn2THuCpFiiVw/tHjzPTW0gqeph+01v4MtDkyvll2hhVG9rDkmpeqDafzyP25Tqn5M0p1wsdOO14oOLEBz6bWQJ/9jAsrd7Ey5Y+E5CpFiulkXd3PS5DFsVUeajyzNY+1e6aSXzRE3VVpIqLnqm8bBxTNm6Z/6bXdlX7VWkyzRm5LXpgn23xy2On+qzHCare4flmolxATeau9MrLlR5JoOKL+fNwF6rPubDM/PdcRTpeRiYuQU884d9Vv8ucgKpdn3c3l+soT9pMIoEcZUBvQ9H77WE5BA7ymfpU5g7kcvUo09yRIxao+uNh+18FTA8rgsn9qwLqbO/L5X3e+fTIAJVexzysXK43kbK9L5MMHqr8eNpM31UhiHPJMxfQ4P8zcUoqkheaHmeYiatV7cp6wJepzbmOVaZ+IVCR883EPelxShyc5JtqchGjVPOH10fv90zfVf31eTYoFRBxkU9v3DLRjgcqeaLpcR255qWaBLkC1OdhqWXgUe1IKj9BvfwzsfrZFl2upCpD7xnvU7lv9RaRXp0y7daZ+j7T4jUY1OFZ5PqpSK/dvK70jN/4o8fxqkA+V+7o81AmMVBPosglz88DfjsWqKjjwuFw2g6mYuVz6WQVGyuXpfqeTTzINMH44tXLmxS3/E47VbmZOJnPA6D0vkokzcS9ZgIYel8OPawncsnjp1e+akORx11vQyPbNV4vuSw9TpHeyaVf9DYRVXtV7cv1oELOXy+9am6ozDAylSPXlb7zuobD4dzqqv0oIfgLRFNTU6iqqvpxV2OXdmmXcqDJyUlUVlbq/r5jgSqZTGJoaAhtbW2YnJxMuz3mUaL19XVUVVXt9sEj3gfAF7MfNE3DxsYGysvLM5ot7FjRz2g0oqKiAgCQn5//hRmYHxft9sFuHxB90frB4/FkTfPwlle7tEu7tEv/wLQLVLu0S7v0hacdDVRWqxW//du/DavV+uOuyo+Ndvtgtw+IfpL7Yccq03dpl3Zp59CO5qh2aZd2aWfQLlDt0i7t0heedoFql3Zpl77wtAtUu7RLu/SFp12g2qVd2qUvPO1YoPqTP/kT1NXVwWazYf/+/Th79uyPu0o/Mjpz5gy+8pWvoLy8HAaDAW+88Uba75qm4Xd+53dQXl4Ou92OkydP4vbt22lpYrEYfumXfgl+vx9OpxMvvfQSpqam/gFb8Xej3//938fBgwfhdrtRXFyMr371qxgaGkpLs9P74b/9t/+Gzs5OYWl+9OhRvPPOO+L3HdV+bQfSq6++qpnNZu3P/uzPtDt37mj/9t/+W83pdGrj4+M/7qr9SOjtt9/Wfuu3fkv73ve+pwHQXn/99bTf/+AP/kBzu93a9773Pe3WrVvaP/7H/1grKyvT1tfXRZpf+IVf0CoqKrQPPvhAu379unbq1Cmtq6tLSyQS/8Ct+Xz03HPPaX/5l3+pDQwMaP39/doLL7ygVVdXa8FgUKTZ6f3w5ptvam+99ZY2NDSkDQ0Nab/5m7+pmc1mbWBgQNO0ndX+HQlUhw4d0n7hF34h7VlLS4v27//9v/8x1ejvj2SgSiaTWmlpqfYHf/AH4lk0GtU8Ho/2p3/6p5qmadra2ppmNpu1V199VaSZnp7WjEaj9u677/6D1f1HSQsLCxoA7dNPP9U07dHtB6/Xq/35n//5jmv/jhP94vE4ent78eyzz6Y9f/bZZ3HhwoUfU63+4Wh0dBRzc3Np7bdarXjiiSdE+3t7e7G5uZmWpry8HO3t7T+xfRQIBAAAPp8PwKPXD1tbW3j11VcRCoVw9OjRHdf+HQdUS0tL2NraQklJSdrzkpISzM3N/Zhq9Q9H1MZM7Z+bm4PFYoHX69VN85NEmqbhV3/1V3H8+HG0t7cDeHT64datW3C5XLBarfiFX/gFvP7662hra9tx7d+xYV5U0Qs/TwjUn1T6PO3/Se2jX/zFX8TNmzdx7ty5bb/t9H5obm5Gf38/1tbW8L3vfQ8/8zM/g08//VT8vlPav+M4Kr/fD5PJtG1HWFhY2La77EQqLS0FgIztLy0tRTwex+rqqm6anxT6pV/6Jbz55pv45JNP0iJEPir9YLFY0NDQgAMHDuD3f//30dXVhf/yX/7Ljmv/jgMqi8WC/fv344MPPkh7/sEHH+DYsWM/plr9w1FdXR1KS0vT2h+Px/Hpp5+K9u/fvx9mszktzezsLAYGBn5i+kjTNPziL/4iXnvtNXz88ceoq6tL+/1R6QeZNE1DLBbbee3/cWnx/z6JzBP+4i/+Qrtz5472K7/yK5rT6dTGxsZ+3FX7kdDGxobW19en9fX1aQC0P/qjP9L6+vqE+cUf/MEfaB6PR3vttde0W7duad/61reUx9KVlZXahx9+qF2/fl178sknv5DH0nr0r//1v9Y8Ho92+vRpbXZ2VvyFw2GRZqf3w2/8xm9oZ86c0UZHR7WbN29qv/mbv6kZjUbt/fff1zRtZ7V/RwKVpmnaH//xH2s1NTWaxWLR9u3bJ46tdwJ98sknGoBtfz/zMz+jaVrqaP63f/u3tdLSUs1qtWqPP/64duvWrbQ8IpGI9ou/+Iuaz+fT7Ha79uKLL2oTExM/htZ8PlK1H4D2l3/5lyLNTu+Hf/7P/7mY40VFRdpTTz0lQErTdlb7d+NR7dIu7dIXnnacjmqXdmmXdh7tAtUu7dIufeFpF6h2aZd26QtPu0C1S7u0S1942gWqXdqlXfrC0y5Q7dIu7dIXnnaBapd2aZe+8LQLVLu0S7v0haddoNqlXdqlLzztAtUu7dIufeFpF6h2aZd26QtP/z/nE939cvaB8QAAAABJRU5ErkJggg=="
class="
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
<li><p><strong>OCR Text Extraction:</strong></p>
<ul>
<li>Configures Tesseract OCR with custom parameters to improve accuracy.</li>
<li>Extracts text from the warped receipt image using <code>pytesseract.image_to_string</code>.</li>
<li>Uses presets to not penalize non-words/non-sentences as the receipt is not plain english</li>
</ul>
</li>
</ol>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">custom_config</span> <span class="o">=</span> <span class="sa">r</span><span class="s1">'--oem 3 --psm 6 -c load_system_dawg=0 load_freq_dawg=0'</span>
<span class="n">extracted_text</span> <span class="o">=</span> <span class="n">pytesseract</span><span class="o">.</span><span class="n">image_to_string</span><span class="p">(</span><span class="n">warped_image</span><span class="p">,</span> <span class="n">config</span><span class="o">=</span><span class="n">custom_config</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><strong>Receipt Splitting</strong></p>

</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<ol>
<li><p><strong>Extracted Text Assignment:</strong></p>
<ul>
<li>Assigns the extracted text to the variable <code>text</code>.</li>
</ul>
</li>
<li><p><strong>Groceries Extraction:</strong></p>
<ul>
<li>Uses a regular expression to find patterns matching grocery items in the text.</li>
</ul>
</li>
<li><p><strong>Prices Extraction:</strong></p>
<ul>
<li>Uses a regular expression to find patterns matching prices in the text.</li>
</ul>
</li>
<li><p><strong>Price Formatting:</strong></p>
<ul>
<li>Formats the prices by replacing spaces with dots if present.</li>
</ul>
</li>
<li><p><strong>Dues Calculation:</strong></p>
<ul>
<li>Initializes a dictionary to keep track of dues for each individual.</li>
<li>Iterates through each grocery item and asks for input about who bought the item.</li>
<li>Calculates and updates the dues for each person based on the price of the item and the number of people who bought it.</li>
</ul>
</li>
</ol>

</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">text</span> <span class="o">=</span> <span class="n">extracted_text</span>
<span class="n">groceries</span> <span class="o">=</span> <span class="n">re</span><span class="o">.</span><span class="n">findall</span><span class="p">(</span><span class="sa">r</span><span class="s1">' (.+)\d{1,2}\.\d{1,3}[^-\d]'</span><span class="p">,</span><span class="n">text</span><span class="p">)</span>
<span class="n">prices</span> <span class="o">=</span> <span class="n">re</span><span class="o">.</span><span class="n">findall</span><span class="p">(</span><span class="sa">r</span><span class="s1">'[^D](\d{1,3}[\. ]+\d</span><span class="si">{2}</span><span class="s1">)'</span><span class="p">,</span><span class="n">text</span><span class="p">)</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">prices</span><span class="p">)):</span>
    <span class="k">if</span> <span class="s2">" "</span> <span class="ow">in</span> <span class="n">prices</span><span class="p">[</span><span class="n">i</span><span class="p">]:</span>
        <span class="n">prices</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="o">=</span> <span class="n">prices</span><span class="p">[</span><span class="n">i</span><span class="p">]</span><span class="o">.</span><span class="n">replace</span><span class="p">(</span><span class="s2">" "</span><span class="p">,</span><span class="s1">'.'</span><span class="p">)</span>

<span class="n">dues</span> <span class="o">=</span> <span class="p">{</span><span class="s1">'a'</span><span class="p">:</span><span class="mi">0</span><span class="p">,</span><span class="s1">'c'</span><span class="p">:</span><span class="mi">0</span><span class="p">,</span><span class="s1">'l'</span><span class="p">:</span><span class="mi">0</span><span class="p">,</span><span class="s1">'r'</span><span class="p">:</span><span class="mi">0</span><span class="p">,</span><span class="s1">'v'</span><span class="p">:</span><span class="mi">0</span><span class="p">}</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">groceries</span><span class="p">)):</span>
    <span class="n">add_to</span> <span class="o">=</span> <span class="nb">input</span><span class="p">(</span><span class="s2">"initial(s) who bought "</span><span class="o">+</span><span class="n">groceries</span><span class="p">[</span><span class="n">i</span><span class="p">])</span>
    <span class="n">price</span> <span class="o">=</span> <span class="nb">float</span><span class="p">(</span><span class="n">prices</span><span class="p">[</span><span class="n">i</span><span class="p">])</span>
    <span class="k">for</span> <span class="n">initial</span> <span class="ow">in</span> <span class="n">add_to</span><span class="p">:</span>
        <span class="n">dues</span><span class="p">[</span><span class="n">initial</span><span class="p">]</span><span class="o">+=</span> <span class="n">price</span> <span class="o">/</span> <span class="nb">len</span><span class="p">(</span><span class="n">add_to</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">groceries</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>[&#34;_&#39;212080 CHKN PATTIES 1&#34;, &#39;E 19904 KETA SALMON 2&#39;, &#39;e 269 BLACK COD FL 2&#39;, &#39;169891 SILK ORG.ALM &#39;, &#39;_ _}184891 SILK ORG.ALM &#39;, &#39;PURE PROTEIN 1&#39;, &#39;BATH SHEET 1&#39;, &#39;BATH SHEET 1&#39;, &#39;KS BLKFT &#39;, &#39;1010598 KS 3 BERRY &#39;, &#39;99006 JARLBG-SWISS/ 1&#39;, &#39;22086 KS MILD CHI &#39;, &#39;22086 KS MILD CHDR &#39;, &#39;296058 KIM CRAWFBRD 1&#39;, &#39;DAQU CAB SAU = 2&#39;, &#39;1280819 KS HUMPUS &#39;, &#39;E 1025795 KS 5DZ EGGS &#39;, &#39;65519 SOUR CREAM &#39;, &#39;20&#39;, &#39;$21&#39;, &#39;Costco Visa 21&#39;, &#39;10.25% Tax &#39;, &#39;TAX &#39;, &#39;SAVINGS $ 1&#39;]
</pre>
</div>
</div>

</div>

</div>

</div>
</body>







</html>