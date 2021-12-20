---
layout: page
title: "The Value of a Weapon in Valorant"
permalink: /
---
<html>
<head><meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>writeup</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>




<style type="text/css">
    pre { line-height: 125%; }
td.linenos pre { color: #000000; background-color: #f0f0f0; padding-left: 5px; padding-right: 5px; }
span.linenos { color: #000000; background-color: #f0f0f0; padding-left: 5px; padding-right: 5px; }
td.linenos pre.special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
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
}


/* <DEPRECATED> */ .p-TabBar[data-orientation='vertical'], /* </DEPRECATED> */
.lm-TabBar[data-orientation='vertical'] {
  flex-direction: column;
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


/* <DEPRECATED> */ .p-TabBar-tab.p-mod-hidden, /* </DEPRECATED> */
.lm-TabBar-tab.lm-mod-hidden {
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
.p-TabBar.p-mod-dragging .p-TabBar-tab.p-mod-dragging
/* </DEPRECATED> */
.lm-TabBar.lm-mod-dragging .lm-TabBar-tab.lm-mod-dragging {
  transition: none;
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
/*!

Copyright 2015-present Palantir Technologies, Inc. All rights reserved.
Licensed under the Apache License, Version 2.0.

*/
html{
  -webkit-box-sizing:border-box;
          box-sizing:border-box; }

*,
*::before,
*::after{
  -webkit-box-sizing:inherit;
          box-sizing:inherit; }

body{
  text-transform:none;
  line-height:1.28581;
  letter-spacing:0;
  font-size:14px;
  font-weight:400;
  color:#182026;
  font-family:-apple-system, "BlinkMacSystemFont", "Segoe UI", "Roboto", "Oxygen", "Ubuntu", "Cantarell", "Open Sans", "Helvetica Neue", "Icons16", sans-serif; }

p{
  margin-top:0;
  margin-bottom:10px; }

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
  line-height:40px;
  font-size:36px; }

h2.bp3-heading, .bp3-running-text h2{
  line-height:32px;
  font-size:28px; }

h3.bp3-heading, .bp3-running-text h3{
  line-height:25px;
  font-size:22px; }

h4.bp3-heading, .bp3-running-text h4{
  line-height:21px;
  font-size:18px; }

h5.bp3-heading, .bp3-running-text h5{
  line-height:19px;
  font-size:16px; }

h6.bp3-heading, .bp3-running-text h6{
  line-height:16px;
  font-size:14px; }
.bp3-ui-text{
  text-transform:none;
  line-height:1.28581;
  letter-spacing:0;
  font-size:14px;
  font-weight:400; }

.bp3-monospace-text{
  text-transform:none;
  font-family:monospace; }

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
  line-height:1.5;
  font-size:14px; }
  .bp3-running-text h1{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h1{
      color:#f5f8fa; }
  .bp3-running-text h2{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h2{
      color:#f5f8fa; }
  .bp3-running-text h3{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h3{
      color:#f5f8fa; }
  .bp3-running-text h4{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h4{
      color:#f5f8fa; }
  .bp3-running-text h5{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h5{
      color:#f5f8fa; }
  .bp3-running-text h6{
    color:#182026;
    font-weight:600;
    margin-top:40px;
    margin-bottom:20px; }
    .bp3-dark .bp3-running-text h6{
      color:#f5f8fa; }
  .bp3-running-text hr{
    margin:20px 0;
    border:none;
    border-bottom:1px solid rgba(16, 22, 26, 0.15); }
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
  text-decoration:none;
  color:#106ba3; }
  a:hover{
    cursor:pointer;
    text-decoration:underline;
    color:#106ba3; }
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
  text-transform:none;
  font-family:monospace;
  border-radius:3px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2);
  background:rgba(255, 255, 255, 0.7);
  padding:2px 5px;
  color:#5c7080;
  font-size:smaller; }
  .bp3-dark .bp3-running-text code, .bp3-running-text .bp3-dark code, .bp3-dark .bp3-code{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
    background:rgba(16, 22, 26, 0.3);
    color:#a7b6c2; }
  .bp3-running-text a > code, a > .bp3-code{
    color:#137cbd; }
    .bp3-dark .bp3-running-text a > code, .bp3-running-text .bp3-dark a > code, .bp3-dark a > .bp3-code{
      color:inherit; }

.bp3-running-text pre, .bp3-code-block{
  text-transform:none;
  font-family:monospace;
  display:block;
  margin:10px 0;
  border-radius:3px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.15);
  background:rgba(255, 255, 255, 0.7);
  padding:13px 15px 12px;
  line-height:1.4;
  color:#182026;
  font-size:13px;
  word-break:break-all;
  word-wrap:break-word; }
  .bp3-dark .bp3-running-text pre, .bp3-running-text .bp3-dark pre, .bp3-dark .bp3-code-block{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
    background:rgba(16, 22, 26, 0.3);
    color:#f5f8fa; }
  .bp3-running-text pre > code, .bp3-code-block > code{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:none;
    padding:0;
    color:inherit;
    font-size:inherit; }

.bp3-running-text kbd, .bp3-key{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  background:#ffffff;
  min-width:24px;
  height:24px;
  padding:3px 6px;
  vertical-align:middle;
  line-height:24px;
  color:#5c7080;
  font-family:inherit;
  font-size:12px; }
  .bp3-running-text kbd .bp3-icon, .bp3-key .bp3-icon, .bp3-running-text kbd .bp3-icon-standard, .bp3-key .bp3-icon-standard, .bp3-running-text kbd .bp3-icon-large, .bp3-key .bp3-icon-large{
    margin-right:5px; }
  .bp3-dark .bp3-running-text kbd, .bp3-running-text .bp3-dark kbd, .bp3-dark .bp3-key{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.4);
    background:#394b59;
    color:#a7b6c2; }
.bp3-running-text blockquote, .bp3-blockquote{
  margin:0 0 10px;
  border-left:solid 4px rgba(167, 182, 194, 0.5);
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
  margin:0;
  padding:0;
  list-style:none; }
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
    margin-top:0;
    margin-right:20px;
    font-size:40px; }

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
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-wrap:wrap;
      flex-wrap:wrap;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  margin:0;
  cursor:default;
  height:30px;
  padding:0;
  list-style:none; }
  .bp3-breadcrumbs > li{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center; }
    .bp3-breadcrumbs > li::after{
      display:block;
      margin:0 5px;
      background:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M10.71 7.29l-4-4a1.003 1.003 0 0 0-1.42 1.42L8.59 8 5.3 11.29c-.19.18-.3.43-.3.71a1.003 1.003 0 0 0 1.71.71l4-4c.18-.18.29-.43.29-.71 0-.28-.11-.53-.29-.71z' fill='%235C7080'/%3e%3c/svg%3e");
      width:16px;
      height:16px;
      content:""; }
    .bp3-breadcrumbs > li:last-of-type::after{
      display:none; }

.bp3-breadcrumb,
.bp3-breadcrumb-current,
.bp3-breadcrumbs-collapsed{
  display:-webkit-inline-box;
  display:-ms-inline-flexbox;
  display:inline-flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  font-size:16px; }

.bp3-breadcrumb,
.bp3-breadcrumbs-collapsed{
  color:#5c7080; }

.bp3-breadcrumb:hover{
  text-decoration:none; }

.bp3-breadcrumb.bp3-disabled{
  cursor:not-allowed;
  color:rgba(92, 112, 128, 0.6); }

.bp3-breadcrumb .bp3-icon{
  margin-right:5px; }

.bp3-breadcrumb-current{
  color:inherit;
  font-weight:600; }
  .bp3-breadcrumb-current .bp3-input{
    vertical-align:baseline;
    font-size:inherit;
    font-weight:inherit; }

.bp3-breadcrumbs-collapsed{
  margin-right:2px;
  border:none;
  border-radius:3px;
  background:#ced9e0;
  cursor:pointer;
  padding:1px 5px;
  vertical-align:text-bottom; }
  .bp3-breadcrumbs-collapsed::before{
    display:block;
    background:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cg fill='%235C7080'%3e%3ccircle cx='2' cy='8.03' r='2'/%3e%3ccircle cx='14' cy='8.03' r='2'/%3e%3ccircle cx='8' cy='8.03' r='2'/%3e%3c/g%3e%3c/svg%3e") center no-repeat;
    width:16px;
    height:16px;
    content:""; }
  .bp3-breadcrumbs-collapsed:hover{
    background:#bfccd6;
    text-decoration:none;
    color:#182026; }

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
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  border:none;
  border-radius:3px;
  cursor:pointer;
  padding:5px 10px;
  vertical-align:middle;
  text-align:left;
  font-size:14px;
  min-width:30px;
  min-height:30px; }
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
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    color:#182026; }
    .bp3-button:not([class*="bp3-intent-"]):hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
      background-clip:padding-box;
      background-color:#ebf1f5; }
    .bp3-button:not([class*="bp3-intent-"]):active, .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#d8e1e8;
      background-image:none; }
    .bp3-button:not([class*="bp3-intent-"]):disabled, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled{
      outline:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(206, 217, 224, 0.5);
      background-image:none;
      cursor:not-allowed;
      color:rgba(92, 112, 128, 0.6); }
      .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active, .bp3-button:not([class*="bp3-intent-"]):disabled.bp3-active:hover, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active, .bp3-button:not([class*="bp3-intent-"]).bp3-disabled.bp3-active:hover{
        background:rgba(206, 217, 224, 0.7); }
  .bp3-button.bp3-intent-primary{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
    .bp3-button.bp3-intent-primary:hover, .bp3-button.bp3-intent-primary:active, .bp3-button.bp3-intent-primary.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-primary:hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
      background-color:#106ba3; }
    .bp3-button.bp3-intent-primary:active, .bp3-button.bp3-intent-primary.bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#0e5a8a;
      background-image:none; }
    .bp3-button.bp3-intent-primary:disabled, .bp3-button.bp3-intent-primary.bp3-disabled{
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(19, 124, 189, 0.5);
      background-image:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-success{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#0f9960;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
    .bp3-button.bp3-intent-success:hover, .bp3-button.bp3-intent-success:active, .bp3-button.bp3-intent-success.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-success:hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
      background-color:#0d8050; }
    .bp3-button.bp3-intent-success:active, .bp3-button.bp3-intent-success.bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#0a6640;
      background-image:none; }
    .bp3-button.bp3-intent-success:disabled, .bp3-button.bp3-intent-success.bp3-disabled{
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(15, 153, 96, 0.5);
      background-image:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-warning{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#d9822b;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
    .bp3-button.bp3-intent-warning:hover, .bp3-button.bp3-intent-warning:active, .bp3-button.bp3-intent-warning.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-warning:hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
      background-color:#bf7326; }
    .bp3-button.bp3-intent-warning:active, .bp3-button.bp3-intent-warning.bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#a66321;
      background-image:none; }
    .bp3-button.bp3-intent-warning:disabled, .bp3-button.bp3-intent-warning.bp3-disabled{
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(217, 130, 43, 0.5);
      background-image:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button.bp3-intent-danger{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#db3737;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
    .bp3-button.bp3-intent-danger:hover, .bp3-button.bp3-intent-danger:active, .bp3-button.bp3-intent-danger.bp3-active{
      color:#ffffff; }
    .bp3-button.bp3-intent-danger:hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
      background-color:#c23030; }
    .bp3-button.bp3-intent-danger:active, .bp3-button.bp3-intent-danger.bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#a82a2a;
      background-image:none; }
    .bp3-button.bp3-intent-danger:disabled, .bp3-button.bp3-intent-danger.bp3-disabled{
      border-color:transparent;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(219, 55, 55, 0.5);
      background-image:none;
      color:rgba(255, 255, 255, 0.6); }
  .bp3-button[class*="bp3-intent-"] .bp3-button-spinner .bp3-spinner-head{
    stroke:#ffffff; }
  .bp3-button.bp3-large,
  .bp3-large .bp3-button{
    min-width:40px;
    min-height:40px;
    padding:5px 15px;
    font-size:16px; }
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
    min-width:24px;
    min-height:24px;
    padding:0 7px; }
  .bp3-button.bp3-loading{
    position:relative; }
    .bp3-button.bp3-loading[class*="bp3-icon-"]::before{
      visibility:hidden; }
    .bp3-button.bp3-loading .bp3-button-spinner{
      position:absolute;
      margin:0; }
    .bp3-button.bp3-loading > :not(.bp3-button-spinner){
      visibility:hidden; }
  .bp3-button[class*="bp3-icon-"]::before{
    line-height:1;
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-weight:400;
    font-style:normal;
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
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background-color:#394b59;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
    color:#f5f8fa; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):hover, .bp3-dark .bp3-button:not([class*="bp3-intent-"]):active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      color:#f5f8fa; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):hover{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      background-color:#30404d; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):active, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-active{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#202b33;
      background-image:none; }
    .bp3-dark .bp3-button:not([class*="bp3-intent-"]):disabled, .bp3-dark .bp3-button:not([class*="bp3-intent-"]).bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(57, 75, 89, 0.5);
      background-image:none;
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
      -webkit-box-shadow:none;
              box-shadow:none;
      background-image:none;
      color:rgba(255, 255, 255, 0.3); }
    .bp3-dark .bp3-button[class*="bp3-intent-"] .bp3-button-spinner .bp3-spinner-head{
      stroke:#8a9ba8; }
  .bp3-button:disabled::before,
  .bp3-button:disabled .bp3-icon, .bp3-button:disabled .bp3-icon-standard, .bp3-button:disabled .bp3-icon-large, .bp3-button.bp3-disabled::before,
  .bp3-button.bp3-disabled .bp3-icon, .bp3-button.bp3-disabled .bp3-icon-standard, .bp3-button.bp3-disabled .bp3-icon-large, .bp3-button[class*="bp3-intent-"]::before,
  .bp3-button[class*="bp3-intent-"] .bp3-icon, .bp3-button[class*="bp3-intent-"] .bp3-icon-standard, .bp3-button[class*="bp3-intent-"] .bp3-icon-large{
    color:inherit !important; }
  .bp3-button.bp3-minimal{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:none; }
    .bp3-button.bp3-minimal:hover{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(167, 182, 194, 0.3);
      text-decoration:none;
      color:#182026; }
    .bp3-button.bp3-minimal:active, .bp3-button.bp3-minimal.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(115, 134, 148, 0.3);
      color:#182026; }
    .bp3-button.bp3-minimal:disabled, .bp3-button.bp3-minimal:disabled:hover, .bp3-button.bp3-minimal.bp3-disabled, .bp3-button.bp3-minimal.bp3-disabled:hover{
      background:none;
      cursor:not-allowed;
      color:rgba(92, 112, 128, 0.6); }
      .bp3-button.bp3-minimal:disabled.bp3-active, .bp3-button.bp3-minimal:disabled:hover.bp3-active, .bp3-button.bp3-minimal.bp3-disabled.bp3-active, .bp3-button.bp3-minimal.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button.bp3-minimal{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
      color:inherit; }
      .bp3-dark .bp3-button.bp3-minimal:hover, .bp3-dark .bp3-button.bp3-minimal:active, .bp3-dark .bp3-button.bp3-minimal.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none; }
      .bp3-dark .bp3-button.bp3-minimal:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button.bp3-minimal:active, .bp3-dark .bp3-button.bp3-minimal.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button.bp3-minimal:disabled, .bp3-dark .bp3-button.bp3-minimal:disabled:hover, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled:hover{
        background:none;
        cursor:not-allowed;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-button.bp3-minimal:disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal:disabled:hover.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled.bp3-active, .bp3-dark .bp3-button.bp3-minimal.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button.bp3-minimal.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button.bp3-minimal.bp3-intent-primary:hover, .bp3-button.bp3-minimal.bp3-intent-primary:active, .bp3-button.bp3-minimal.bp3-intent-primary.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
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
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
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
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
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
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
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
    border-top-left-radius:0;
    border-bottom-left-radius:0; }
  .bp3-button-group:not(.bp3-minimal) > .bp3-popover-wrapper:not(:last-child) .bp3-button,
  .bp3-button-group:not(.bp3-minimal) > .bp3-button:not(:last-child){
    margin-right:-1px;
    border-top-right-radius:0;
    border-bottom-right-radius:0; }
  .bp3-button-group.bp3-minimal .bp3-button{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:none; }
    .bp3-button-group.bp3-minimal .bp3-button:hover{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(167, 182, 194, 0.3);
      text-decoration:none;
      color:#182026; }
    .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(115, 134, 148, 0.3);
      color:#182026; }
    .bp3-button-group.bp3-minimal .bp3-button:disabled, .bp3-button-group.bp3-minimal .bp3-button:disabled:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover{
      background:none;
      cursor:not-allowed;
      color:rgba(92, 112, 128, 0.6); }
      .bp3-button-group.bp3-minimal .bp3-button:disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button:disabled:hover.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled.bp3-active, .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover.bp3-active{
        background:rgba(115, 134, 148, 0.3); }
    .bp3-dark .bp3-button-group.bp3-minimal .bp3-button{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
      color:inherit; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:hover, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:hover{
        background:rgba(138, 155, 168, 0.15); }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-active{
        background:rgba(138, 155, 168, 0.3);
        color:#f5f8fa; }
      .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled:hover, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover{
        background:none;
        cursor:not-allowed;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button:disabled:hover.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled.bp3-active, .bp3-dark .bp3-button-group.bp3-minimal .bp3-button.bp3-disabled:hover.bp3-active{
          background:rgba(138, 155, 168, 0.3); }
    .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary{
      color:#106ba3; }
      .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:hover, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary:active, .bp3-button-group.bp3-minimal .bp3-button.bp3-intent-primary.bp3-active{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
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
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
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
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
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
        -webkit-box-shadow:none;
                box-shadow:none;
        background:none;
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
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column;
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch;
    vertical-align:top; }
    .bp3-button-group.bp3-vertical.bp3-fill{
      width:unset;
      height:100%; }
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
  line-height:1.5;
  font-size:14px;
  position:relative;
  border-radius:3px;
  background-color:rgba(138, 155, 168, 0.15);
  width:100%;
  padding:10px 12px 9px; }
  .bp3-callout[class*="bp3-icon-"]{
    padding-left:40px; }
    .bp3-callout[class*="bp3-icon-"]::before{
      line-height:1;
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-weight:400;
      font-style:normal;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased;
      position:absolute;
      top:10px;
      left:10px;
      color:#5c7080; }
  .bp3-callout.bp3-callout-icon{
    padding-left:40px; }
    .bp3-callout.bp3-callout-icon > .bp3-icon:first-child{
      position:absolute;
      top:10px;
      left:10px;
      color:#5c7080; }
  .bp3-callout .bp3-heading{
    margin-top:0;
    margin-bottom:5px;
    line-height:20px; }
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
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.15), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
  background-color:#ffffff;
  padding:20px;
  -webkit-transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-transform 200ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
  .bp3-card.bp3-dark,
  .bp3-dark .bp3-card{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), 0 0 0 rgba(16, 22, 26, 0), 0 0 0 rgba(16, 22, 26, 0);
    background-color:#30404d; }

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
  opacity:0.9;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
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
  margin:5px;
  border-right:1px solid rgba(16, 22, 26, 0.15);
  border-bottom:1px solid rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-divider{
    border-color:rgba(16, 22, 26, 0.4); }
.bp3-dialog-container{
  opacity:1;
  -webkit-transform:scale(1);
          transform:scale(1);
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  width:100%;
  min-height:100%;
  pointer-events:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-dialog-container.bp3-overlay-enter > .bp3-dialog, .bp3-dialog-container.bp3-overlay-appear > .bp3-dialog{
    opacity:0;
    -webkit-transform:scale(0.5);
            transform:scale(0.5); }
  .bp3-dialog-container.bp3-overlay-enter-active > .bp3-dialog, .bp3-dialog-container.bp3-overlay-appear-active > .bp3-dialog{
    opacity:1;
    -webkit-transform:scale(1);
            transform:scale(1);
    -webkit-transition-property:opacity, -webkit-transform;
    transition-property:opacity, -webkit-transform;
    transition-property:opacity, transform;
    transition-property:opacity, transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-dialog-container.bp3-overlay-exit > .bp3-dialog{
    opacity:1;
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-dialog-container.bp3-overlay-exit-active > .bp3-dialog{
    opacity:0;
    -webkit-transform:scale(0.5);
            transform:scale(0.5);
    -webkit-transition-property:opacity, -webkit-transform;
    transition-property:opacity, -webkit-transform;
    transition-property:opacity, transform;
    transition-property:opacity, transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }

.bp3-dialog{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:30px 0;
  border-radius:6px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  background:#ebf1f5;
  width:500px;
  padding-bottom:20px;
  pointer-events:all;
  -webkit-user-select:text;
     -moz-user-select:text;
      -ms-user-select:text;
          user-select:text; }
  .bp3-dialog:focus{
    outline:0; }
  .bp3-dialog.bp3-dark,
  .bp3-dark .bp3-dialog{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    background:#293742;
    color:#f5f8fa; }

.bp3-dialog-header{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  border-radius:6px 6px 0 0;
  -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
  background:#ffffff;
  min-height:40px;
  padding-right:5px;
  padding-left:20px; }
  .bp3-dialog-header .bp3-icon-large,
  .bp3-dialog-header .bp3-icon{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    margin-right:10px;
    color:#5c7080; }
  .bp3-dialog-header .bp3-heading{
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    margin:0;
    line-height:inherit; }
    .bp3-dialog-header .bp3-heading:last-child{
      margin-right:20px; }
  .bp3-dark .bp3-dialog-header{
    -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:0 1px 0 rgba(16, 22, 26, 0.4);
    background:#30404d; }
    .bp3-dark .bp3-dialog-header .bp3-icon-large,
    .bp3-dark .bp3-dialog-header .bp3-icon{
      color:#a7b6c2; }

.bp3-dialog-body{
  -webkit-box-flex:1;
      -ms-flex:1 1 auto;
          flex:1 1 auto;
  margin:20px;
  line-height:18px; }

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
.bp3-drawer{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin:0;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  background:#ffffff;
  padding:0; }
  .bp3-drawer:focus{
    outline:0; }
  .bp3-drawer.bp3-position-top{
    top:0;
    right:0;
    left:0;
    height:50%; }
    .bp3-drawer.bp3-position-top.bp3-overlay-enter, .bp3-drawer.bp3-position-top.bp3-overlay-appear{
      -webkit-transform:translateY(-100%);
              transform:translateY(-100%); }
    .bp3-drawer.bp3-position-top.bp3-overlay-enter-active, .bp3-drawer.bp3-position-top.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer.bp3-position-top.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer.bp3-position-top.bp3-overlay-exit-active{
      -webkit-transform:translateY(-100%);
              transform:translateY(-100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer.bp3-position-bottom{
    right:0;
    bottom:0;
    left:0;
    height:50%; }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-enter, .bp3-drawer.bp3-position-bottom.bp3-overlay-appear{
      -webkit-transform:translateY(100%);
              transform:translateY(100%); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-enter-active, .bp3-drawer.bp3-position-bottom.bp3-overlay-appear-active{
      -webkit-transform:translateY(0);
              transform:translateY(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer.bp3-position-bottom.bp3-overlay-exit-active{
      -webkit-transform:translateY(100%);
              transform:translateY(100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer.bp3-position-left{
    top:0;
    bottom:0;
    left:0;
    width:50%; }
    .bp3-drawer.bp3-position-left.bp3-overlay-enter, .bp3-drawer.bp3-position-left.bp3-overlay-appear{
      -webkit-transform:translateX(-100%);
              transform:translateX(-100%); }
    .bp3-drawer.bp3-position-left.bp3-overlay-enter-active, .bp3-drawer.bp3-position-left.bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer.bp3-position-left.bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer.bp3-position-left.bp3-overlay-exit-active{
      -webkit-transform:translateX(-100%);
              transform:translateX(-100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer.bp3-position-right{
    top:0;
    right:0;
    bottom:0;
    width:50%; }
    .bp3-drawer.bp3-position-right.bp3-overlay-enter, .bp3-drawer.bp3-position-right.bp3-overlay-appear{
      -webkit-transform:translateX(100%);
              transform:translateX(100%); }
    .bp3-drawer.bp3-position-right.bp3-overlay-enter-active, .bp3-drawer.bp3-position-right.bp3-overlay-appear-active{
      -webkit-transform:translateX(0);
              transform:translateX(0);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer.bp3-position-right.bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer.bp3-position-right.bp3-overlay-exit-active{
      -webkit-transform:translateX(100%);
              transform:translateX(100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
  .bp3-position-right):not(.bp3-vertical){
    top:0;
    right:0;
    bottom:0;
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
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-exit{
      -webkit-transform:translateX(0);
              transform:translateX(0); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right):not(.bp3-vertical).bp3-overlay-exit-active{
      -webkit-transform:translateX(100%);
              transform:translateX(100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
  .bp3-position-right).bp3-vertical{
    right:0;
    bottom:0;
    left:0;
    height:50%; }
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
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:200ms;
              transition-duration:200ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-exit{
      -webkit-transform:translateY(0);
              transform:translateY(0); }
    .bp3-drawer:not(.bp3-position-top):not(.bp3-position-bottom):not(.bp3-position-left):not(
    .bp3-position-right).bp3-vertical.bp3-overlay-exit-active{
      -webkit-transform:translateY(100%);
              transform:translateY(100%);
      -webkit-transition-property:-webkit-transform;
      transition-property:-webkit-transform;
      transition-property:transform;
      transition-property:transform, -webkit-transform;
      -webkit-transition-duration:100ms;
              transition-duration:100ms;
      -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
              transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
      -webkit-transition-delay:0;
              transition-delay:0; }
  .bp3-drawer.bp3-dark,
  .bp3-dark .bp3-drawer{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    background:#30404d;
    color:#f5f8fa; }

.bp3-drawer-header{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  position:relative;
  border-radius:0;
  -webkit-box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:0 1px 0 rgba(16, 22, 26, 0.15);
  min-height:40px;
  padding:5px;
  padding-left:20px; }
  .bp3-drawer-header .bp3-icon-large,
  .bp3-drawer-header .bp3-icon{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    margin-right:10px;
    color:#5c7080; }
  .bp3-drawer-header .bp3-heading{
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    margin:0;
    line-height:inherit; }
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
  overflow:auto;
  line-height:18px; }

.bp3-drawer-footer{
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  position:relative;
  -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
  padding:10px 20px; }
  .bp3-dark .bp3-drawer-footer{
    -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.4); }
.bp3-editable-text{
  display:inline-block;
  position:relative;
  cursor:text;
  max-width:100%;
  vertical-align:top;
  white-space:nowrap; }
  .bp3-editable-text::before{
    position:absolute;
    top:-3px;
    right:-3px;
    bottom:-3px;
    left:-3px;
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
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
    background-color:#ffffff; }
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
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    background-color:rgba(16, 22, 26, 0.3); }
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
  display:inherit;
  position:relative;
  min-width:inherit;
  max-width:inherit;
  vertical-align:top;
  text-transform:inherit;
  letter-spacing:inherit;
  color:inherit;
  font:inherit;
  resize:none; }

.bp3-editable-text-input{
  border:none;
  -webkit-box-shadow:none;
          box-shadow:none;
  background:none;
  width:100%;
  padding:0;
  white-space:pre-wrap; }
  .bp3-editable-text-input::-webkit-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-editable-text-input::-moz-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-editable-text-input:-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-editable-text-input::-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-editable-text-input::placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
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
    position:absolute;
    left:0;
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
    z-index:2;
    border-radius:inherit; }
    .bp3-control-group .bp3-input:focus{
      z-index:14;
      border-radius:3px; }
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
    z-index:4;
    border-radius:inherit; }
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
  .bp3-control-group .bp3-input-group > .bp3-input-action{
    z-index:16; }
  .bp3-control-group .bp3-select::after,
  .bp3-control-group .bp3-html-select::after,
  .bp3-control-group .bp3-select > .bp3-icon,
  .bp3-control-group .bp3-html-select > .bp3-icon{
    z-index:17; }
  .bp3-control-group:not(.bp3-vertical) > *{
    margin-right:-1px; }
  .bp3-dark .bp3-control-group:not(.bp3-vertical) > *{
    margin-right:0; }
  .bp3-dark .bp3-control-group:not(.bp3-vertical) > .bp3-button + .bp3-button{
    margin-left:1px; }
  .bp3-control-group .bp3-popover-wrapper,
  .bp3-control-group .bp3-popover-target{
    border-radius:inherit; }
  .bp3-control-group > :first-child{
    border-radius:3px 0 0 3px; }
  .bp3-control-group > :last-child{
    margin-right:0;
    border-radius:0 3px 3px 0; }
  .bp3-control-group > :only-child{
    margin-right:0;
    border-radius:3px; }
  .bp3-control-group .bp3-input-group .bp3-button{
    border-radius:3px; }
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
      margin-top:0;
      border-radius:3px 3px 0 0; }
    .bp3-control-group.bp3-vertical > :last-child{
      border-radius:0 0 3px 3px; }
.bp3-control{
  display:block;
  position:relative;
  margin-bottom:10px;
  cursor:pointer;
  text-transform:none; }
  .bp3-control input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
  .bp3-control:hover input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#106ba3; }
  .bp3-control input:not(:disabled):active:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background:#0e5a8a; }
  .bp3-control input:disabled:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(19, 124, 189, 0.5); }
  .bp3-dark .bp3-control input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control:hover input:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background-color:#106ba3; }
  .bp3-dark .bp3-control input:not(:disabled):active:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#0e5a8a; }
  .bp3-dark .bp3-control input:disabled:checked ~ .bp3-control-indicator{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(14, 90, 138, 0.5); }
  .bp3-control:not(.bp3-align-right){
    padding-left:26px; }
    .bp3-control:not(.bp3-align-right) .bp3-control-indicator{
      margin-left:-26px; }
  .bp3-control.bp3-align-right{
    padding-right:26px; }
    .bp3-control.bp3-align-right .bp3-control-indicator{
      margin-right:-26px; }
  .bp3-control.bp3-disabled{
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-control.bp3-inline{
    display:inline-block;
    margin-right:20px; }
  .bp3-control input{
    position:absolute;
    top:0;
    left:0;
    opacity:0;
    z-index:-1; }
  .bp3-control .bp3-control-indicator{
    display:inline-block;
    position:relative;
    margin-top:-3px;
    margin-right:10px;
    border:none;
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-clip:padding-box;
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    cursor:pointer;
    width:1em;
    height:1em;
    vertical-align:middle;
    font-size:16px;
    -webkit-user-select:none;
       -moz-user-select:none;
        -ms-user-select:none;
            user-select:none; }
    .bp3-control .bp3-control-indicator::before{
      display:block;
      width:1em;
      height:1em;
      content:""; }
  .bp3-control:hover .bp3-control-indicator{
    background-color:#ebf1f5; }
  .bp3-control input:not(:disabled):active ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background:#d8e1e8; }
  .bp3-control input:disabled ~ .bp3-control-indicator{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(206, 217, 224, 0.5);
    cursor:not-allowed; }
  .bp3-control input:focus ~ .bp3-control-indicator{
    outline:rgba(19, 124, 189, 0.6) auto 2px;
    outline-offset:2px;
    -moz-outline-radius:6px; }
  .bp3-control.bp3-align-right .bp3-control-indicator{
    float:right;
    margin-top:1px;
    margin-left:10px; }
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
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#137cbd;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.1)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0));
    color:#ffffff; }
  .bp3-control.bp3-checkbox:hover input:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 -1px 0 rgba(16, 22, 26, 0.2);
    background-color:#106ba3; }
  .bp3-control.bp3-checkbox input:not(:disabled):active:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background:#0e5a8a; }
  .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(19, 124, 189, 0.5); }
  .bp3-dark .bp3-control.bp3-checkbox input:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-dark .bp3-control.bp3-checkbox:hover input:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background-color:#106ba3; }
  .bp3-dark .bp3-control.bp3-checkbox input:not(:disabled):active:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#0e5a8a; }
  .bp3-dark .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(14, 90, 138, 0.5); }
  .bp3-control.bp3-checkbox .bp3-control-indicator{
    border-radius:3px; }
  .bp3-control.bp3-checkbox input:checked ~ .bp3-control-indicator::before{
    background-image:url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill-rule='evenodd' clip-rule='evenodd' d='M12 5c-.28 0-.53.11-.71.29L7 9.59l-2.29-2.3a1.003 1.003 0 0 0-1.42 1.42l3 3c.18.18.43.29.71.29s.53-.11.71-.29l5-5A1.003 1.003 0 0 0 12 5z' fill='white'/%3e%3c/svg%3e"); }
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
    width:auto;
    min-width:1.75em;
    -webkit-transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:background-color 100ms cubic-bezier(0.4, 1, 0.75, 0.9); }
    .bp3-control.bp3-switch .bp3-control-indicator::before{
      position:absolute;
      left:0;
      margin:2px;
      border-radius:50%;
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
      background:#ffffff;
      width:calc(1em - 4px);
      height:calc(1em - 4px);
      -webkit-transition:left 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
      transition:left 100ms cubic-bezier(0.4, 1, 0.75, 0.9); }
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
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background:#394b59; }
  .bp3-dark .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator::before{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.4); }
  .bp3-control.bp3-switch .bp3-switch-inner-text{
    text-align:center;
    font-size:0.7em; }
  .bp3-control.bp3-switch .bp3-control-indicator-child:first-child{
    visibility:hidden;
    margin-right:1.2em;
    margin-left:0.5em;
    line-height:0; }
  .bp3-control.bp3-switch .bp3-control-indicator-child:last-child{
    visibility:visible;
    margin-right:0.5em;
    margin-left:1.2em;
    line-height:1em; }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator .bp3-control-indicator-child:first-child{
    visibility:visible;
    line-height:1em; }
  .bp3-control.bp3-switch input:checked ~ .bp3-control-indicator .bp3-control-indicator-child:last-child{
    visibility:hidden;
    line-height:0; }
  .bp3-dark .bp3-control{
    color:#f5f8fa; }
    .bp3-dark .bp3-control.bp3-disabled{
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-control .bp3-control-indicator{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      background-color:#394b59;
      background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
      background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0)); }
    .bp3-dark .bp3-control:hover .bp3-control-indicator{
      background-color:#30404d; }
    .bp3-dark .bp3-control input:not(:disabled):active ~ .bp3-control-indicator{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background:#202b33; }
    .bp3-dark .bp3-control input:disabled ~ .bp3-control-indicator{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(57, 75, 89, 0.5);
      cursor:not-allowed; }
    .bp3-dark .bp3-control.bp3-checkbox input:disabled:checked ~ .bp3-control-indicator, .bp3-dark .bp3-control.bp3-checkbox input:disabled:indeterminate ~ .bp3-control-indicator{
      color:rgba(167, 182, 194, 0.6); }
.bp3-file-input{
  display:inline-block;
  position:relative;
  cursor:pointer;
  height:30px; }
  .bp3-file-input input{
    opacity:0;
    margin:0;
    min-width:200px; }
    .bp3-file-input input:disabled + .bp3-file-upload-input,
    .bp3-file-input input.bp3-disabled + .bp3-file-upload-input{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(206, 217, 224, 0.5);
      cursor:not-allowed;
      color:rgba(92, 112, 128, 0.6);
      resize:none; }
      .bp3-file-input input:disabled + .bp3-file-upload-input::after,
      .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after{
        outline:none;
        -webkit-box-shadow:none;
                box-shadow:none;
        background-color:rgba(206, 217, 224, 0.5);
        background-image:none;
        cursor:not-allowed;
        color:rgba(92, 112, 128, 0.6); }
        .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active, .bp3-file-input input:disabled + .bp3-file-upload-input::after.bp3-active:hover,
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active,
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after.bp3-active:hover{
          background:rgba(206, 217, 224, 0.7); }
      .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input, .bp3-dark
      .bp3-file-input input.bp3-disabled + .bp3-file-upload-input{
        -webkit-box-shadow:none;
                box-shadow:none;
        background:rgba(57, 75, 89, 0.5);
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-file-input input:disabled + .bp3-file-upload-input::after, .bp3-dark
        .bp3-file-input input.bp3-disabled + .bp3-file-upload-input::after{
          -webkit-box-shadow:none;
                  box-shadow:none;
          background-color:rgba(57, 75, 89, 0.5);
          background-image:none;
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
  outline:none;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
  background:#ffffff;
  height:30px;
  padding:0 10px;
  vertical-align:middle;
  line-height:30px;
  color:#182026;
  font-size:14px;
  font-weight:400;
  -webkit-transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  -webkit-appearance:none;
     -moz-appearance:none;
          appearance:none;
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  position:absolute;
  top:0;
  right:0;
  left:0;
  padding-right:80px;
  color:rgba(92, 112, 128, 0.6);
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-file-upload-input::-webkit-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-file-upload-input::-moz-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-file-upload-input:-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-file-upload-input::-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-file-upload-input::placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
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
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(206, 217, 224, 0.5);
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6);
    resize:none; }
  .bp3-file-upload-input::after{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-color:#f5f8fa;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
    color:#182026;
    min-width:24px;
    min-height:24px;
    overflow:hidden;
    text-overflow:ellipsis;
    white-space:nowrap;
    word-wrap:normal;
    position:absolute;
    top:0;
    right:0;
    margin:3px;
    border-radius:3px;
    width:70px;
    text-align:center;
    line-height:24px;
    content:"Browse"; }
    .bp3-file-upload-input::after:hover{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
      background-clip:padding-box;
      background-color:#ebf1f5; }
    .bp3-file-upload-input::after:active, .bp3-file-upload-input::after.bp3-active{
      -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#d8e1e8;
      background-image:none; }
    .bp3-file-upload-input::after:disabled, .bp3-file-upload-input::after.bp3-disabled{
      outline:none;
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(206, 217, 224, 0.5);
      background-image:none;
      cursor:not-allowed;
      color:rgba(92, 112, 128, 0.6); }
      .bp3-file-upload-input::after:disabled.bp3-active, .bp3-file-upload-input::after:disabled.bp3-active:hover, .bp3-file-upload-input::after.bp3-disabled.bp3-active, .bp3-file-upload-input::after.bp3-disabled.bp3-active:hover{
        background:rgba(206, 217, 224, 0.7); }
  .bp3-file-upload-input:hover::after{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-clip:padding-box;
    background-color:#ebf1f5; }
  .bp3-file-upload-input:active::after{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#d8e1e8;
    background-image:none; }
  .bp3-large .bp3-file-upload-input{
    height:40px;
    line-height:40px;
    font-size:16px;
    padding-right:95px; }
    .bp3-large .bp3-file-upload-input[type="search"], .bp3-large .bp3-file-upload-input.bp3-round{
      padding:0 15px; }
    .bp3-large .bp3-file-upload-input::after{
      min-width:30px;
      min-height:30px;
      margin:5px;
      width:85px;
      line-height:30px; }
  .bp3-dark .bp3-file-upload-input{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    background:rgba(16, 22, 26, 0.3);
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
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(57, 75, 89, 0.5);
      color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-file-upload-input::after{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      background-color:#394b59;
      background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
      background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
      color:#f5f8fa; }
      .bp3-dark .bp3-file-upload-input::after:hover, .bp3-dark .bp3-file-upload-input::after:active, .bp3-dark .bp3-file-upload-input::after.bp3-active{
        color:#f5f8fa; }
      .bp3-dark .bp3-file-upload-input::after:hover{
        -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
                box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
        background-color:#30404d; }
      .bp3-dark .bp3-file-upload-input::after:active, .bp3-dark .bp3-file-upload-input::after.bp3-active{
        -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
                box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
        background-color:#202b33;
        background-image:none; }
      .bp3-dark .bp3-file-upload-input::after:disabled, .bp3-dark .bp3-file-upload-input::after.bp3-disabled{
        -webkit-box-shadow:none;
                box-shadow:none;
        background-color:rgba(57, 75, 89, 0.5);
        background-image:none;
        color:rgba(167, 182, 194, 0.6); }
        .bp3-dark .bp3-file-upload-input::after:disabled.bp3-active, .bp3-dark .bp3-file-upload-input::after.bp3-disabled.bp3-active{
          background:rgba(57, 75, 89, 0.7); }
      .bp3-dark .bp3-file-upload-input::after .bp3-button-spinner .bp3-spinner-head{
        background:rgba(16, 22, 26, 0.5);
        stroke:#8a9ba8; }
    .bp3-dark .bp3-file-upload-input:hover::after{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      background-color:#30404d; }
    .bp3-dark .bp3-file-upload-input:active::after{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#202b33;
      background-image:none; }

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
    margin-top:5px;
    color:#5c7080;
    font-size:12px; }
  .bp3-form-group.bp3-intent-primary .bp3-form-helper-text{
    color:#106ba3; }
  .bp3-form-group.bp3-intent-success .bp3-form-helper-text{
    color:#0d8050; }
  .bp3-form-group.bp3-intent-warning .bp3-form-helper-text{
    color:#bf7326; }
  .bp3-form-group.bp3-intent-danger .bp3-form-helper-text{
    color:#c23030; }
  .bp3-form-group.bp3-inline{
    -webkit-box-orient:horizontal;
    -webkit-box-direction:normal;
        -ms-flex-direction:row;
            flex-direction:row;
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start; }
    .bp3-form-group.bp3-inline.bp3-large label.bp3-label{
      margin:0 10px 0 0;
      line-height:40px; }
    .bp3-form-group.bp3-inline label.bp3-label{
      margin:0 10px 0 0;
      line-height:30px; }
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
  .bp3-input-group > .bp3-button,
  .bp3-input-group > .bp3-icon{
    position:absolute;
    top:0; }
    .bp3-input-group .bp3-input-action:first-child,
    .bp3-input-group > .bp3-button:first-child,
    .bp3-input-group > .bp3-icon:first-child{
      left:0; }
    .bp3-input-group .bp3-input-action:last-child,
    .bp3-input-group > .bp3-button:last-child,
    .bp3-input-group > .bp3-icon:last-child{
      right:0; }
  .bp3-input-group .bp3-button{
    min-width:24px;
    min-height:24px;
    margin:3px;
    padding:0 7px; }
    .bp3-input-group .bp3-button:empty{
      padding:0; }
  .bp3-input-group > .bp3-icon{
    z-index:1;
    color:#5c7080; }
    .bp3-input-group > .bp3-icon:empty{
      line-height:1;
      font-family:"Icons16", sans-serif;
      font-size:16px;
      font-weight:400;
      font-style:normal;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased; }
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
    min-width:30px;
    min-height:30px;
    margin:5px; }
  .bp3-input-group.bp3-large > .bp3-icon,
  .bp3-input-group.bp3-large .bp3-input-action > .bp3-spinner{
    margin:12px; }
  .bp3-input-group.bp3-large .bp3-input{
    height:40px;
    line-height:40px;
    font-size:16px; }
    .bp3-input-group.bp3-large .bp3-input[type="search"], .bp3-input-group.bp3-large .bp3-input.bp3-round{
      padding:0 15px; }
    .bp3-input-group.bp3-large .bp3-input:not(:first-child){
      padding-left:40px; }
    .bp3-input-group.bp3-large .bp3-input:not(:last-child){
      padding-right:40px; }
  .bp3-input-group.bp3-small .bp3-button{
    min-width:20px;
    min-height:20px;
    margin:2px; }
  .bp3-input-group.bp3-small .bp3-tag{
    min-width:20px;
    min-height:20px;
    margin:2px; }
  .bp3-input-group.bp3-small > .bp3-icon,
  .bp3-input-group.bp3-small .bp3-input-action > .bp3-spinner{
    margin:4px; }
  .bp3-input-group.bp3-small .bp3-input{
    height:24px;
    padding-right:8px;
    padding-left:8px;
    line-height:24px;
    font-size:12px; }
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
  outline:none;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.15), inset 0 1px 1px rgba(16, 22, 26, 0.2);
  background:#ffffff;
  height:30px;
  padding:0 10px;
  vertical-align:middle;
  line-height:30px;
  color:#182026;
  font-size:14px;
  font-weight:400;
  -webkit-transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:-webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  transition:box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9), -webkit-box-shadow 100ms cubic-bezier(0.4, 1, 0.75, 0.9);
  -webkit-appearance:none;
     -moz-appearance:none;
          appearance:none; }
  .bp3-input::-webkit-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input::-moz-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input:-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input::-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input::placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
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
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(206, 217, 224, 0.5);
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6);
    resize:none; }
  .bp3-input.bp3-large{
    height:40px;
    line-height:40px;
    font-size:16px; }
    .bp3-input.bp3-large[type="search"], .bp3-input.bp3-large.bp3-round{
      padding:0 15px; }
  .bp3-input.bp3-small{
    height:24px;
    padding-right:8px;
    padding-left:8px;
    line-height:24px;
    font-size:12px; }
    .bp3-input.bp3-small[type="search"], .bp3-input.bp3-small.bp3-round{
      padding:0 12px; }
  .bp3-input.bp3-fill{
    -webkit-box-flex:1;
        -ms-flex:1 1 auto;
            flex:1 1 auto;
    width:100%; }
  .bp3-dark .bp3-input{
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    background:rgba(16, 22, 26, 0.3);
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
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(57, 75, 89, 0.5);
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
    -webkit-box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), 0 0 0 0 rgba(19, 124, 189, 0), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    background:rgba(16, 22, 26, 0.3);
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
      -webkit-box-shadow:none;
              box-shadow:none;
      background:rgba(57, 75, 89, 0.5);
      color:rgba(167, 182, 194, 0.6); }
label.bp3-label{
  display:block;
  margin-top:0;
  margin-bottom:15px; }
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
    width:100%;
    vertical-align:top;
    font-weight:400; }
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
  width:30px;
  min-height:0;
  padding:0; }
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
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  border:none;
  border-radius:3px;
  cursor:pointer;
  padding:5px 10px;
  vertical-align:middle;
  text-align:left;
  font-size:14px;
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
  background-color:#f5f8fa;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
  color:#182026;
  border-radius:3px;
  width:100%;
  height:30px;
  padding:0 25px 0 10px;
  -moz-appearance:none;
  -webkit-appearance:none; }
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
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-clip:padding-box;
    background-color:#ebf1f5; }
  .bp3-html-select select:active,
  .bp3-select select:active, .bp3-html-select select.bp3-active,
  .bp3-select select.bp3-active{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#d8e1e8;
    background-image:none; }
  .bp3-html-select select:disabled,
  .bp3-select select:disabled, .bp3-html-select select.bp3-disabled,
  .bp3-select select.bp3-disabled{
    outline:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    background-color:rgba(206, 217, 224, 0.5);
    background-image:none;
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
    .bp3-html-select select:disabled.bp3-active,
    .bp3-select select:disabled.bp3-active, .bp3-html-select select:disabled.bp3-active:hover,
    .bp3-select select:disabled.bp3-active:hover, .bp3-html-select select.bp3-disabled.bp3-active,
    .bp3-select select.bp3-disabled.bp3-active, .bp3-html-select select.bp3-disabled.bp3-active:hover,
    .bp3-select select.bp3-disabled.bp3-active:hover{
      background:rgba(206, 217, 224, 0.7); }

.bp3-html-select.bp3-minimal select,
.bp3-select.bp3-minimal select{
  -webkit-box-shadow:none;
          box-shadow:none;
  background:none; }
  .bp3-html-select.bp3-minimal select:hover,
  .bp3-select.bp3-minimal select:hover{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(167, 182, 194, 0.3);
    text-decoration:none;
    color:#182026; }
  .bp3-html-select.bp3-minimal select:active,
  .bp3-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal select.bp3-active,
  .bp3-select.bp3-minimal select.bp3-active{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:rgba(115, 134, 148, 0.3);
    color:#182026; }
  .bp3-html-select.bp3-minimal select:disabled,
  .bp3-select.bp3-minimal select:disabled, .bp3-html-select.bp3-minimal select:disabled:hover,
  .bp3-select.bp3-minimal select:disabled:hover, .bp3-html-select.bp3-minimal select.bp3-disabled,
  .bp3-select.bp3-minimal select.bp3-disabled, .bp3-html-select.bp3-minimal select.bp3-disabled:hover,
  .bp3-select.bp3-minimal select.bp3-disabled:hover{
    background:none;
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
    .bp3-html-select.bp3-minimal select:disabled.bp3-active,
    .bp3-select.bp3-minimal select:disabled.bp3-active, .bp3-html-select.bp3-minimal select:disabled:hover.bp3-active,
    .bp3-select.bp3-minimal select:disabled:hover.bp3-active, .bp3-html-select.bp3-minimal select.bp3-disabled.bp3-active,
    .bp3-select.bp3-minimal select.bp3-disabled.bp3-active, .bp3-html-select.bp3-minimal select.bp3-disabled:hover.bp3-active,
    .bp3-select.bp3-minimal select.bp3-disabled:hover.bp3-active{
      background:rgba(115, 134, 148, 0.3); }
  .bp3-dark .bp3-html-select.bp3-minimal select, .bp3-html-select.bp3-minimal .bp3-dark select,
  .bp3-dark .bp3-select.bp3-minimal select, .bp3-select.bp3-minimal .bp3-dark select{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:none;
    color:inherit; }
    .bp3-dark .bp3-html-select.bp3-minimal select:hover, .bp3-html-select.bp3-minimal .bp3-dark select:hover,
    .bp3-dark .bp3-select.bp3-minimal select:hover, .bp3-select.bp3-minimal .bp3-dark select:hover, .bp3-dark .bp3-html-select.bp3-minimal select:active, .bp3-html-select.bp3-minimal .bp3-dark select:active,
    .bp3-dark .bp3-select.bp3-minimal select:active, .bp3-select.bp3-minimal .bp3-dark select:active, .bp3-dark .bp3-html-select.bp3-minimal select.bp3-active, .bp3-html-select.bp3-minimal .bp3-dark select.bp3-active,
    .bp3-dark .bp3-select.bp3-minimal select.bp3-active, .bp3-select.bp3-minimal .bp3-dark select.bp3-active{
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none; }
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
      cursor:not-allowed;
      color:rgba(167, 182, 194, 0.6); }
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
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
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
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
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
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
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
      -webkit-box-shadow:none;
              box-shadow:none;
      background:none;
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
  height:40px;
  padding-right:35px;
  font-size:16px; }

.bp3-dark .bp3-html-select select, .bp3-dark .bp3-select select{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
  background-color:#394b59;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
  color:#f5f8fa; }
  .bp3-dark .bp3-html-select select:hover, .bp3-dark .bp3-select select:hover, .bp3-dark .bp3-html-select select:active, .bp3-dark .bp3-select select:active, .bp3-dark .bp3-html-select select.bp3-active, .bp3-dark .bp3-select select.bp3-active{
    color:#f5f8fa; }
  .bp3-dark .bp3-html-select select:hover, .bp3-dark .bp3-select select:hover{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background-color:#30404d; }
  .bp3-dark .bp3-html-select select:active, .bp3-dark .bp3-select select:active, .bp3-dark .bp3-html-select select.bp3-active, .bp3-dark .bp3-select select.bp3-active{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#202b33;
    background-image:none; }
  .bp3-dark .bp3-html-select select:disabled, .bp3-dark .bp3-select select:disabled, .bp3-dark .bp3-html-select select.bp3-disabled, .bp3-dark .bp3-select select.bp3-disabled{
    -webkit-box-shadow:none;
            box-shadow:none;
    background-color:rgba(57, 75, 89, 0.5);
    background-image:none;
    color:rgba(167, 182, 194, 0.6); }
    .bp3-dark .bp3-html-select select:disabled.bp3-active, .bp3-dark .bp3-select select:disabled.bp3-active, .bp3-dark .bp3-html-select select.bp3-disabled.bp3-active, .bp3-dark .bp3-select select.bp3-disabled.bp3-active{
      background:rgba(57, 75, 89, 0.7); }
  .bp3-dark .bp3-html-select select .bp3-button-spinner .bp3-spinner-head, .bp3-dark .bp3-select select .bp3-button-spinner .bp3-spinner-head{
    background:rgba(16, 22, 26, 0.5);
    stroke:#8a9ba8; }

.bp3-html-select select:disabled,
.bp3-select select:disabled{
  -webkit-box-shadow:none;
          box-shadow:none;
  background-color:rgba(206, 217, 224, 0.5);
  cursor:not-allowed;
  color:rgba(92, 112, 128, 0.6); }

.bp3-html-select .bp3-icon,
.bp3-select .bp3-icon, .bp3-select::after{
  position:absolute;
  top:7px;
  right:7px;
  color:#5c7080;
  pointer-events:none; }
  .bp3-html-select .bp3-disabled.bp3-icon,
  .bp3-select .bp3-disabled.bp3-icon, .bp3-disabled.bp3-select::after{
    color:rgba(92, 112, 128, 0.6); }
.bp3-html-select,
.bp3-select{
  display:inline-block;
  position:relative;
  vertical-align:middle;
  letter-spacing:normal; }
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
    top:12px;
    right:12px; }
  .bp3-html-select.bp3-fill,
  .bp3-html-select.bp3-fill select,
  .bp3-select.bp3-fill,
  .bp3-select.bp3-fill select{
    width:100%; }
  .bp3-dark .bp3-html-select option, .bp3-dark
  .bp3-select option{
    background-color:#30404d;
    color:#f5f8fa; }
  .bp3-dark .bp3-html-select::after, .bp3-dark
  .bp3-select::after{
    color:#a7b6c2; }

.bp3-select::after{
  line-height:1;
  font-family:"Icons16", sans-serif;
  font-size:16px;
  font-weight:400;
  font-style:normal;
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
    vertical-align:top;
    text-align:left; }
  .bp3-running-text table th, table.bp3-html-table th{
    color:#182026;
    font-weight:600; }
  
  .bp3-running-text table td,
  table.bp3-html-table td{
    color:#182026; }
  .bp3-running-text table tbody tr:first-child th, table.bp3-html-table tbody tr:first-child th,
  .bp3-running-text table tbody tr:first-child td,
  table.bp3-html-table tbody tr:first-child td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15); }
  .bp3-dark .bp3-running-text table th, .bp3-running-text .bp3-dark table th, .bp3-dark table.bp3-html-table th{
    color:#f5f8fa; }
  .bp3-dark .bp3-running-text table td, .bp3-running-text .bp3-dark table td, .bp3-dark table.bp3-html-table td{
    color:#f5f8fa; }
  .bp3-dark .bp3-running-text table tbody tr:first-child th, .bp3-running-text .bp3-dark table tbody tr:first-child th, .bp3-dark table.bp3-html-table tbody tr:first-child th,
  .bp3-dark .bp3-running-text table tbody tr:first-child td,
  .bp3-running-text .bp3-dark table tbody tr:first-child td,
  .bp3-dark table.bp3-html-table tbody tr:first-child td{
    -webkit-box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15);
            box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15); }

table.bp3-html-table.bp3-html-table-condensed th,
table.bp3-html-table.bp3-html-table-condensed td, table.bp3-html-table.bp3-small th,
table.bp3-html-table.bp3-small td{
  padding-top:6px;
  padding-bottom:6px; }

table.bp3-html-table.bp3-html-table-striped tbody tr:nth-child(odd) td{
  background:rgba(191, 204, 214, 0.15); }

table.bp3-html-table.bp3-html-table-bordered th:not(:first-child){
  -webkit-box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 1px 0 0 0 rgba(16, 22, 26, 0.15); }

table.bp3-html-table.bp3-html-table-bordered tbody tr td{
  -webkit-box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15);
          box-shadow:inset 0 1px 0 0 rgba(16, 22, 26, 0.15); }
  table.bp3-html-table.bp3-html-table-bordered tbody tr td:not(:first-child){
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

.bp3-dark table.bp3-html-table.bp3-html-table-striped tbody tr:nth-child(odd) td{
  background:rgba(92, 112, 128, 0.15); }

.bp3-dark table.bp3-html-table.bp3-html-table-bordered th:not(:first-child){
  -webkit-box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15);
          box-shadow:inset 1px 0 0 0 rgba(255, 255, 255, 0.15); }

.bp3-dark table.bp3-html-table.bp3-html-table-bordered tbody tr td{
  -webkit-box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15);
          box-shadow:inset 0 1px 0 0 rgba(255, 255, 255, 0.15); }
  .bp3-dark table.bp3-html-table.bp3-html-table-bordered tbody tr td:not(:first-child){
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
  top:40px;
  padding-bottom:0; }
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
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  -webkit-box-pack:justify;
      -ms-flex-pack:justify;
          justify-content:space-between;
  margin-right:0;
  margin-left:0; }
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
  line-height:1;
  font-family:"Icons16", sans-serif;
  font-size:16px;
  font-weight:400;
  font-style:normal;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  display:inline-block; }

span.bp3-icon-large{
  line-height:1;
  font-family:"Icons20", sans-serif;
  font-size:20px;
  font-weight:400;
  font-style:normal;
  -moz-osx-font-smoothing:grayscale;
  -webkit-font-smoothing:antialiased;
  display:inline-block; }

span.bp3-icon:empty{
  line-height:1;
  font-family:"Icons20";
  font-size:inherit;
  font-weight:400;
  font-style:normal; }
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
  margin:0;
  border-radius:3px;
  background:#ffffff;
  min-width:180px;
  padding:5px;
  list-style:none;
  text-align:left;
  color:#182026; }

.bp3-menu-divider{
  display:block;
  margin:5px;
  border-top:1px solid rgba(16, 22, 26, 0.15); }
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
  padding:5px 7px;
  text-decoration:none;
  line-height:20px;
  color:inherit;
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
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
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
    line-height:1;
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-weight:400;
    font-style:normal;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    margin-right:7px; }
  .bp3-menu-item::before,
  .bp3-menu-item > .bp3-icon{
    margin-top:2px;
    color:#5c7080; }
  .bp3-menu-item .bp3-menu-item-label{
    color:#5c7080; }
  .bp3-menu-item:hover, .bp3-submenu .bp3-popover-target.bp3-popover-open > .bp3-menu-item{
    color:inherit; }
  .bp3-menu-item.bp3-active, .bp3-menu-item:active{
    background-color:rgba(115, 134, 148, 0.3); }
  .bp3-menu-item.bp3-disabled{
    outline:none !important;
    background-color:inherit !important;
    cursor:not-allowed !important;
    color:rgba(92, 112, 128, 0.6) !important; }
    .bp3-menu-item.bp3-disabled::before,
    .bp3-menu-item.bp3-disabled > .bp3-icon,
    .bp3-menu-item.bp3-disabled .bp3-menu-item-label{
      color:rgba(92, 112, 128, 0.6) !important; }
  .bp3-large .bp3-menu-item{
    padding:9px 7px;
    line-height:22px;
    font-size:16px; }
    .bp3-large .bp3-menu-item .bp3-icon{
      margin-top:3px; }
    .bp3-large .bp3-menu-item::before{
      line-height:1;
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-weight:400;
      font-style:normal;
      -moz-osx-font-smoothing:grayscale;
      -webkit-font-smoothing:antialiased;
      margin-top:1px;
      margin-right:10px; }

button.bp3-menu-item{
  border:none;
  background:none;
  width:100%;
  text-align:left; }
.bp3-menu-header{
  display:block;
  margin:5px;
  border-top:1px solid rgba(16, 22, 26, 0.15);
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
    margin:0;
    padding:10px 7px 0 1px;
    line-height:17px; }
    .bp3-dark .bp3-menu-header > h6{
      color:#f5f8fa; }
  .bp3-menu-header:first-of-type > h6{
    padding-top:0; }
  .bp3-large .bp3-menu-header > h6{
    padding-top:15px;
    padding-bottom:5px;
    font-size:18px; }
  .bp3-large .bp3-menu-header:first-of-type > h6{
    padding-top:0; }

.bp3-dark .bp3-menu{
  background:#30404d;
  color:#f5f8fa; }

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
  position:relative;
  z-index:10;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 0 0 rgba(16, 22, 26, 0), 0 1px 1px rgba(16, 22, 26, 0.2);
  background-color:#ffffff;
  width:100%;
  height:50px;
  padding:0 15px; }
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
    position:fixed;
    top:0;
    right:0;
    left:0; }

.bp3-navbar-heading{
  margin-right:15px;
  font-size:16px; }

.bp3-navbar-group{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  height:50px; }
  .bp3-navbar-group.bp3-align-left{
    float:left; }
  .bp3-navbar-group.bp3-align-right{
    float:right; }

.bp3-navbar-divider{
  margin:0 10px;
  border-left:1px solid rgba(16, 22, 26, 0.15);
  height:20px; }
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
  -webkit-box-pack:center;
      -ms-flex-pack:center;
          justify-content:center;
  width:100%;
  height:100%;
  text-align:center; }
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
  position:static;
  top:0;
  right:0;
  bottom:0;
  left:0;
  z-index:20; }
  .bp3-overlay:not(.bp3-overlay-open){
    pointer-events:none; }
  .bp3-overlay.bp3-overlay-container{
    position:fixed;
    overflow:hidden; }
    .bp3-overlay.bp3-overlay-container.bp3-overlay-inline{
      position:absolute; }
  .bp3-overlay.bp3-overlay-scroll-container{
    position:fixed;
    overflow:auto; }
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
  position:fixed;
  top:0;
  right:0;
  bottom:0;
  left:0;
  opacity:1;
  z-index:20;
  background-color:rgba(16, 22, 26, 0.7);
  overflow:auto;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-overlay-backdrop.bp3-overlay-enter, .bp3-overlay-backdrop.bp3-overlay-appear{
    opacity:0; }
  .bp3-overlay-backdrop.bp3-overlay-enter-active, .bp3-overlay-backdrop.bp3-overlay-appear-active{
    opacity:1;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-overlay-backdrop.bp3-overlay-exit{
    opacity:1; }
  .bp3-overlay-backdrop.bp3-overlay-exit-active{
    opacity:0;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-overlay-backdrop:focus{
    outline:none; }
  .bp3-overlay-inline .bp3-overlay-backdrop{
    position:absolute; }
.bp3-panel-stack{
  position:relative;
  overflow:hidden; }

.bp3-panel-stack-header{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -ms-flex-negative:0;
      flex-shrink:0;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  z-index:1;
  -webkit-box-shadow:0 1px rgba(16, 22, 26, 0.15);
          box-shadow:0 1px rgba(16, 22, 26, 0.15);
  height:30px; }
  .bp3-dark .bp3-panel-stack-header{
    -webkit-box-shadow:0 1px rgba(255, 255, 255, 0.15);
            box-shadow:0 1px rgba(255, 255, 255, 0.15); }
  .bp3-panel-stack-header > span{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-flex:1;
        -ms-flex:1;
            flex:1;
    -webkit-box-align:stretch;
        -ms-flex-align:stretch;
            align-items:stretch; }
  .bp3-panel-stack-header .bp3-heading{
    margin:0 5px; }

.bp3-button.bp3-panel-stack-header-back{
  margin-left:5px;
  padding-left:0;
  white-space:nowrap; }
  .bp3-button.bp3-panel-stack-header-back .bp3-icon{
    margin:0 2px; }

.bp3-panel-stack-view{
  position:absolute;
  top:0;
  right:0;
  bottom:0;
  left:0;
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  margin-right:-1px;
  border-right:1px solid rgba(16, 22, 26, 0.15);
  background-color:#ffffff;
  overflow-y:auto; }
  .bp3-dark .bp3-panel-stack-view{
    background-color:#30404d; }

.bp3-panel-stack-push .bp3-panel-stack-enter, .bp3-panel-stack-push .bp3-panel-stack-appear{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0; }

.bp3-panel-stack-push .bp3-panel-stack-enter-active, .bp3-panel-stack-push .bp3-panel-stack-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease;
  -webkit-transition-delay:0;
          transition-delay:0; }

.bp3-panel-stack-push .bp3-panel-stack-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack-push .bp3-panel-stack-exit-active{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease;
  -webkit-transition-delay:0;
          transition-delay:0; }

.bp3-panel-stack-pop .bp3-panel-stack-enter, .bp3-panel-stack-pop .bp3-panel-stack-appear{
  -webkit-transform:translateX(-50%);
          transform:translateX(-50%);
  opacity:0; }

.bp3-panel-stack-pop .bp3-panel-stack-enter-active, .bp3-panel-stack-pop .bp3-panel-stack-appear-active{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease;
  -webkit-transition-delay:0;
          transition-delay:0; }

.bp3-panel-stack-pop .bp3-panel-stack-exit{
  -webkit-transform:translate(0%);
          transform:translate(0%);
  opacity:1; }

.bp3-panel-stack-pop .bp3-panel-stack-exit-active{
  -webkit-transform:translateX(100%);
          transform:translateX(100%);
  opacity:0;
  -webkit-transition-property:opacity, -webkit-transform;
  transition-property:opacity, -webkit-transform;
  transition-property:transform, opacity;
  transition-property:transform, opacity, -webkit-transform;
  -webkit-transition-duration:400ms;
          transition-duration:400ms;
  -webkit-transition-timing-function:ease;
          transition-timing-function:ease;
  -webkit-transition-delay:0;
          transition-delay:0; }
.bp3-popover{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  -webkit-transform:scale(1);
          transform:scale(1);
  display:inline-block;
  z-index:20;
  border-radius:3px; }
  .bp3-popover .bp3-popover-arrow{
    position:absolute;
    width:30px;
    height:30px; }
    .bp3-popover .bp3-popover-arrow::before{
      margin:5px;
      width:20px;
      height:20px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-popover{
    margin-top:-17px;
    margin-bottom:17px; }
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
    margin-right:17px;
    margin-left:-17px; }
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
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-popover-exit > .bp3-popover{
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-popover-exit-active > .bp3-popover{
    -webkit-transform:scale(0.3);
            transform:scale(0.3);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-popover .bp3-popover-content{
    position:relative;
    border-radius:3px; }
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
        -webkit-transition-property:-webkit-transform;
        transition-property:-webkit-transform;
        transition-property:transform;
        transition-property:transform, -webkit-transform;
        -webkit-transition-duration:100ms;
                transition-duration:100ms;
        -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
                transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
        -webkit-transition-delay:0;
                transition-delay:0; }
      .bp3-popover-exit > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1); }
      .bp3-popover-exit-active > .bp3-popover.bp3-minimal.bp3-popover{
        -webkit-transform:scale(1);
                transform:scale(1);
        -webkit-transition-property:-webkit-transform;
        transition-property:-webkit-transform;
        transition-property:transform;
        transition-property:transform, -webkit-transform;
        -webkit-transition-duration:100ms;
                transition-duration:100ms;
        -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
                transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
        -webkit-transition-delay:0;
                transition-delay:0; }
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
  display:block;
  position:absolute;
  -webkit-transform:rotate(45deg);
          transform:rotate(45deg);
  border-radius:2px;
  content:""; }

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
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-transition-container.bp3-popover-exit{
    opacity:1; }
  .bp3-transition-container.bp3-popover-exit-active{
    opacity:0;
    -webkit-transition-property:opacity;
    transition-property:opacity;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
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
  position:absolute;
  top:0;
  right:0;
  left:0; }
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
  display:block;
  position:relative;
  border-radius:40px;
  background:rgba(92, 112, 128, 0.2);
  width:100%;
  height:8px;
  overflow:hidden; }
  .bp3-progress-bar .bp3-progress-meter{
    position:absolute;
    border-radius:40px;
    background:linear-gradient(-45deg, rgba(255, 255, 255, 0.2) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.2) 50%, rgba(255, 255, 255, 0.2) 75%, transparent 75%);
    background-color:rgba(92, 112, 128, 0.8);
    background-size:30px 30px;
    width:100%;
    height:100%;
    -webkit-transition:width 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:width 200ms cubic-bezier(0.4, 1, 0.75, 0.9); }
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
    border-color:rgba(206, 217, 224, 0.2);
    background:rgba(206, 217, 224, 0.2); }
  to{
    border-color:rgba(92, 112, 128, 0.2);
    background:rgba(92, 112, 128, 0.2); } }
@keyframes skeleton-glow{
  from{
    border-color:rgba(206, 217, 224, 0.2);
    background:rgba(206, 217, 224, 0.2); }
  to{
    border-color:rgba(92, 112, 128, 0.2);
    background:rgba(92, 112, 128, 0.2); } }
.bp3-skeleton{
  border-color:rgba(206, 217, 224, 0.2) !important;
  border-radius:2px;
  -webkit-box-shadow:none !important;
          box-shadow:none !important;
  background:rgba(206, 217, 224, 0.2);
  background-clip:padding-box !important;
  cursor:default;
  color:transparent !important;
  -webkit-animation:1000ms linear infinite alternate skeleton-glow;
          animation:1000ms linear infinite alternate skeleton-glow;
  pointer-events:none;
  -webkit-user-select:none;
     -moz-user-select:none;
      -ms-user-select:none;
          user-select:none; }
  .bp3-skeleton::before, .bp3-skeleton::after,
  .bp3-skeleton *{
    visibility:hidden !important; }
.bp3-slider{
  width:100%;
  min-width:150px;
  height:40px;
  position:relative;
  outline:none;
  cursor:default;
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
    opacity:0.5;
    cursor:not-allowed; }
  .bp3-slider.bp3-slider-unlabeled{
    height:16px; }

.bp3-slider-track,
.bp3-slider-progress{
  top:5px;
  right:0;
  left:0;
  height:6px;
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
  -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
          box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
  background-color:#f5f8fa;
  background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.8)), to(rgba(255, 255, 255, 0)));
  background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0));
  color:#182026;
  position:absolute;
  top:0;
  left:0;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
  cursor:pointer;
  width:16px;
  height:16px; }
  .bp3-slider-handle:hover{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-clip:padding-box;
    background-color:#ebf1f5; }
  .bp3-slider-handle:active, .bp3-slider-handle.bp3-active{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#d8e1e8;
    background-image:none; }
  .bp3-slider-handle:disabled, .bp3-slider-handle.bp3-disabled{
    outline:none;
    -webkit-box-shadow:none;
            box-shadow:none;
    background-color:rgba(206, 217, 224, 0.5);
    background-image:none;
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
    .bp3-slider-handle:disabled.bp3-active, .bp3-slider-handle:disabled.bp3-active:hover, .bp3-slider-handle.bp3-disabled.bp3-active, .bp3-slider-handle.bp3-disabled.bp3-active:hover{
      background:rgba(206, 217, 224, 0.7); }
  .bp3-slider-handle:focus{
    z-index:1; }
  .bp3-slider-handle:hover{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 -1px 0 rgba(16, 22, 26, 0.1);
    background-clip:padding-box;
    background-color:#ebf1f5;
    z-index:2;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 1px 1px rgba(16, 22, 26, 0.2);
    cursor:-webkit-grab;
    cursor:grab; }
  .bp3-slider-handle.bp3-active{
    -webkit-box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
            box-shadow:inset 0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 2px rgba(16, 22, 26, 0.2);
    background-color:#d8e1e8;
    background-image:none;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 1px rgba(16, 22, 26, 0.1);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), inset 0 1px 1px rgba(16, 22, 26, 0.1);
    cursor:-webkit-grabbing;
    cursor:grabbing; }
  .bp3-disabled .bp3-slider-handle{
    -webkit-box-shadow:none;
            box-shadow:none;
    background:#bfccd6;
    pointer-events:none; }
  .bp3-dark .bp3-slider-handle{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
    background-color:#394b59;
    background-image:-webkit-gradient(linear, left top, left bottom, from(rgba(255, 255, 255, 0.05)), to(rgba(255, 255, 255, 0)));
    background-image:linear-gradient(to bottom, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0));
    color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle:hover, .bp3-dark .bp3-slider-handle:active, .bp3-dark .bp3-slider-handle.bp3-active{
      color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle:hover{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.4);
      background-color:#30404d; }
    .bp3-dark .bp3-slider-handle:active, .bp3-dark .bp3-slider-handle.bp3-active{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.6), inset 0 1px 2px rgba(16, 22, 26, 0.2);
      background-color:#202b33;
      background-image:none; }
    .bp3-dark .bp3-slider-handle:disabled, .bp3-dark .bp3-slider-handle.bp3-disabled{
      -webkit-box-shadow:none;
              box-shadow:none;
      background-color:rgba(57, 75, 89, 0.5);
      background-image:none;
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
    border-color:#5c7080;
    -webkit-box-shadow:none;
            box-shadow:none;
    background:#5c7080; }
  .bp3-slider-handle .bp3-slider-label{
    margin-left:8px;
    border-radius:3px;
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
    background:#394b59;
    color:#f5f8fa; }
    .bp3-dark .bp3-slider-handle .bp3-slider-label{
      -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
              box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
      background:#e1e8ed;
      color:#394b59; }
    .bp3-disabled .bp3-slider-handle .bp3-slider-label{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-slider-handle.bp3-start, .bp3-slider-handle.bp3-end{
    width:8px; }
  .bp3-slider-handle.bp3-start{
    border-top-right-radius:0;
    border-bottom-right-radius:0; }
  .bp3-slider-handle.bp3-end{
    margin-left:8px;
    border-top-left-radius:0;
    border-bottom-left-radius:0; }
    .bp3-slider-handle.bp3-end .bp3-slider-label{
      margin-left:0; }

.bp3-slider-label{
  -webkit-transform:translate(-50%, 20px);
          transform:translate(-50%, 20px);
  display:inline-block;
  position:absolute;
  padding:2px 5px;
  vertical-align:top;
  line-height:1;
  font-size:12px; }

.bp3-slider.bp3-vertical{
  width:40px;
  min-width:40px;
  height:150px; }
  .bp3-slider.bp3-vertical .bp3-slider-track,
  .bp3-slider.bp3-vertical .bp3-slider-progress{
    top:0;
    bottom:0;
    left:5px;
    width:6px;
    height:auto; }
  .bp3-slider.bp3-vertical .bp3-slider-progress{
    top:auto; }
  .bp3-slider.bp3-vertical .bp3-slider-label{
    -webkit-transform:translate(20px, 50%);
            transform:translate(20px, 50%); }
  .bp3-slider.bp3-vertical .bp3-slider-handle{
    top:auto; }
    .bp3-slider.bp3-vertical .bp3-slider-handle .bp3-slider-label{
      margin-top:-8px;
      margin-left:0; }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-end, .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start{
      margin-left:0;
      width:16px;
      height:8px; }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start{
      border-top-left-radius:0;
      border-bottom-right-radius:3px; }
      .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-start .bp3-slider-label{
        -webkit-transform:translate(20px);
                transform:translate(20px); }
    .bp3-slider.bp3-vertical .bp3-slider-handle.bp3-end{
      margin-bottom:8px;
      border-top-left-radius:3px;
      border-bottom-left-radius:0;
      border-bottom-right-radius:0; }

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
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
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
    -webkit-transform-origin:center;
            transform-origin:center;
    -webkit-transition:stroke-dashoffset 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    transition:stroke-dashoffset 200ms cubic-bezier(0.4, 1, 0.75, 0.9);
    stroke:rgba(92, 112, 128, 0.8);
    stroke-linecap:round; }
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
    -webkit-box-orient:vertical;
    -webkit-box-direction:normal;
        -ms-flex-direction:column;
            flex-direction:column;
    -webkit-box-align:start;
        -ms-flex-align:start;
            align-items:flex-start; }
    .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab{
      border-radius:3px;
      width:100%;
      padding:0 10px; }
      .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab[aria-selected="true"]{
        -webkit-box-shadow:none;
                box-shadow:none;
        background-color:rgba(19, 124, 189, 0.2); }
    .bp3-tabs.bp3-vertical > .bp3-tab-list .bp3-tab-indicator-wrapper .bp3-tab-indicator{
      top:0;
      right:0;
      bottom:0;
      left:0;
      border-radius:3px;
      background-color:rgba(19, 124, 189, 0.2);
      height:auto; }
  .bp3-tabs.bp3-vertical > .bp3-tab-panel{
    margin-top:0;
    padding-left:20px; }

.bp3-tab-list{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  -webkit-box-align:end;
      -ms-flex-align:end;
          align-items:flex-end;
  position:relative;
  margin:0;
  border:none;
  padding:0;
  list-style:none; }
  .bp3-tab-list > *:not(:last-child){
    margin-right:20px; }

.bp3-tab{
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
  word-wrap:normal;
  -webkit-box-flex:0;
      -ms-flex:0 0 auto;
          flex:0 0 auto;
  position:relative;
  cursor:pointer;
  max-width:100%;
  vertical-align:top;
  line-height:30px;
  color:#182026;
  font-size:14px; }
  .bp3-tab a{
    display:block;
    text-decoration:none;
    color:inherit; }
  .bp3-tab-indicator-wrapper ~ .bp3-tab{
    -webkit-box-shadow:none !important;
            box-shadow:none !important;
    background-color:transparent !important; }
  .bp3-tab[aria-disabled="true"]{
    cursor:not-allowed;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-tab[aria-selected="true"]{
    border-radius:0;
    -webkit-box-shadow:inset 0 -3px 0 #106ba3;
            box-shadow:inset 0 -3px 0 #106ba3; }
  .bp3-tab[aria-selected="true"], .bp3-tab:not([aria-disabled="true"]):hover{
    color:#106ba3; }
  .bp3-tab:focus{
    -moz-outline-radius:0; }
  .bp3-large > .bp3-tab{
    line-height:40px;
    font-size:16px; }

.bp3-tab-panel{
  margin-top:20px; }
  .bp3-tab-panel[aria-hidden="true"]{
    display:none; }

.bp3-tab-indicator-wrapper{
  position:absolute;
  top:0;
  left:0;
  -webkit-transform:translateX(0), translateY(0);
          transform:translateX(0), translateY(0);
  -webkit-transition:height, width, -webkit-transform;
  transition:height, width, -webkit-transform;
  transition:height, transform, width;
  transition:height, transform, width, -webkit-transform;
  -webkit-transition-duration:200ms;
          transition-duration:200ms;
  -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
          transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
  pointer-events:none; }
  .bp3-tab-indicator-wrapper .bp3-tab-indicator{
    position:absolute;
    right:0;
    bottom:0;
    left:0;
    background-color:#106ba3;
    height:3px; }
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
  position:relative;
  border:none;
  border-radius:3px;
  -webkit-box-shadow:none;
          box-shadow:none;
  background-color:#5c7080;
  min-width:20px;
  max-width:100%;
  min-height:20px;
  padding:2px 6px;
  line-height:16px;
  color:#f5f8fa;
  font-size:12px; }
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
    padding-right:8px;
    padding-left:8px; }
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
    min-width:30px;
    min-height:30px;
    padding:0 10px;
    line-height:20px;
    font-size:14px; }
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
      padding-right:12px;
      padding-left:12px; }
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
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  opacity:0.5;
  margin-top:-2px;
  margin-right:-6px !important;
  margin-bottom:-2px;
  border:none;
  background:none;
  cursor:pointer;
  padding:2px;
  padding-left:0;
  color:inherit; }
  .bp3-tag-remove:hover{
    opacity:0.8;
    background:none;
    text-decoration:none; }
  .bp3-tag-remove:active{
    opacity:1; }
  .bp3-tag-remove:empty::before{
    line-height:1;
    font-family:"Icons16", sans-serif;
    font-size:16px;
    font-weight:400;
    font-style:normal;
    -moz-osx-font-smoothing:grayscale;
    -webkit-font-smoothing:antialiased;
    content:""; }
  .bp3-large .bp3-tag-remove{
    margin-right:-10px !important;
    padding:5px;
    padding-left:0; }
    .bp3-large .bp3-tag-remove:empty::before{
      line-height:1;
      font-family:"Icons20", sans-serif;
      font-size:20px;
      font-weight:400;
      font-style:normal; }
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
  min-height:30px;
  padding-right:0;
  padding-left:5px;
  line-height:inherit; }
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
    margin-top:7px;
    margin-right:7px;
    margin-left:2px;
    color:#5c7080; }
  .bp3-tag-input .bp3-tag-input-values{
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-orient:horizontal;
    -webkit-box-direction:normal;
        -ms-flex-direction:row;
            flex-direction:row;
    -ms-flex-wrap:wrap;
        flex-wrap:wrap;
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center;
    -ms-flex-item-align:stretch;
        align-self:stretch;
    margin-top:5px;
    margin-right:7px;
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
    width:80px;
    line-height:20px; }
    .bp3-tag-input .bp3-input-ghost:disabled, .bp3-tag-input .bp3-input-ghost.bp3-disabled{
      cursor:not-allowed; }
  .bp3-tag-input .bp3-button,
  .bp3-tag-input .bp3-spinner{
    margin:3px;
    margin-left:0; }
  .bp3-tag-input .bp3-button{
    min-width:24px;
    min-height:24px;
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
      margin-top:10px;
      margin-left:5px; }
    .bp3-tag-input.bp3-large .bp3-input-ghost{
      line-height:30px; }
    .bp3-tag-input.bp3-large .bp3-button{
      min-width:30px;
      min-height:30px;
      padding:5px 10px;
      margin:5px;
      margin-left:0; }
    .bp3-tag-input.bp3-large .bp3-spinner{
      margin:8px;
      margin-left:0; }
  .bp3-tag-input.bp3-active{
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.2);
    background-color:#ffffff; }
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
    -webkit-box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px #137cbd, 0 0 0 1px #137cbd, 0 0 0 3px rgba(19, 124, 189, 0.3), inset 0 0 0 1px rgba(16, 22, 26, 0.3), inset 0 1px 1px rgba(16, 22, 26, 0.4);
    background-color:rgba(16, 22, 26, 0.3); }
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
  border:none;
  -webkit-box-shadow:none;
          box-shadow:none;
  background:none;
  padding:0; }
  .bp3-input-ghost::-webkit-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input-ghost::-moz-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input-ghost:-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input-ghost::-ms-input-placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input-ghost::placeholder{
    opacity:1;
    color:rgba(92, 112, 128, 0.6); }
  .bp3-input-ghost:focus{
    outline:none !important; }
.bp3-toast{
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:start;
      -ms-flex-align:start;
          align-items:flex-start;
  position:relative !important;
  margin:20px 0 0;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  background-color:#ffffff;
  min-width:300px;
  max-width:500px;
  pointer-events:all; }
  .bp3-toast.bp3-toast-enter, .bp3-toast.bp3-toast-appear{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px); }
  .bp3-toast.bp3-toast-enter-active, .bp3-toast.bp3-toast-appear-active{
    -webkit-transform:translateY(0);
            transform:translateY(0);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-toast.bp3-toast-enter ~ .bp3-toast, .bp3-toast.bp3-toast-appear ~ .bp3-toast{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px); }
  .bp3-toast.bp3-toast-enter-active ~ .bp3-toast, .bp3-toast.bp3-toast-appear-active ~ .bp3-toast{
    -webkit-transform:translateY(0);
            transform:translateY(0);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
            transition-timing-function:cubic-bezier(0.54, 1.12, 0.38, 1.11);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-toast.bp3-toast-exit{
    opacity:1;
    -webkit-filter:blur(0);
            filter:blur(0); }
  .bp3-toast.bp3-toast-exit-active{
    opacity:0;
    -webkit-filter:blur(10px);
            filter:blur(10px);
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:opacity, filter;
    transition-property:opacity, filter, -webkit-filter;
    -webkit-transition-duration:300ms;
            transition-duration:300ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-toast.bp3-toast-exit ~ .bp3-toast{
    -webkit-transform:translateY(0);
            transform:translateY(0); }
  .bp3-toast.bp3-toast-exit-active ~ .bp3-toast{
    -webkit-transform:translateY(-40px);
            transform:translateY(-40px);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:50ms;
            transition-delay:50ms; }
  .bp3-toast .bp3-button-group{
    -webkit-box-flex:0;
        -ms-flex:0 0 auto;
            flex:0 0 auto;
    padding:5px;
    padding-left:0; }
  .bp3-toast > .bp3-icon{
    margin:12px;
    margin-right:0;
    color:#5c7080; }
  .bp3-toast.bp3-dark,
  .bp3-dark .bp3-toast{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 2px 4px rgba(16, 22, 26, 0.4), 0 8px 24px rgba(16, 22, 26, 0.4);
    background-color:#394b59; }
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
  display:-webkit-box !important;
  display:-ms-flexbox !important;
  display:flex !important;
  -webkit-box-orient:vertical;
  -webkit-box-direction:normal;
      -ms-flex-direction:column;
          flex-direction:column;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  position:fixed;
  right:0;
  left:0;
  z-index:40;
  overflow:hidden;
  padding:0 20px 20px;
  pointer-events:none; }
  .bp3-toast-container.bp3-toast-container-top{
    top:0;
    bottom:auto; }
  .bp3-toast-container.bp3-toast-container-bottom{
    -webkit-box-orient:vertical;
    -webkit-box-direction:reverse;
        -ms-flex-direction:column-reverse;
            flex-direction:column-reverse;
    top:auto;
    bottom:0; }
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
.bp3-toast-container-bottom .bp3-toast.bp3-toast-leave-active ~ .bp3-toast{
  -webkit-transform:translateY(60px);
          transform:translateY(60px); }
.bp3-tooltip{
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 2px 4px rgba(16, 22, 26, 0.2), 0 8px 24px rgba(16, 22, 26, 0.2);
  -webkit-transform:scale(1);
          transform:scale(1); }
  .bp3-tooltip .bp3-popover-arrow{
    position:absolute;
    width:22px;
    height:22px; }
    .bp3-tooltip .bp3-popover-arrow::before{
      margin:4px;
      width:14px;
      height:14px; }
  .bp3-tether-element-attached-bottom.bp3-tether-target-attached-top > .bp3-tooltip{
    margin-top:-11px;
    margin-bottom:11px; }
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
    margin-right:11px;
    margin-left:-11px; }
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
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-popover-exit > .bp3-tooltip{
    -webkit-transform:scale(1);
            transform:scale(1); }
  .bp3-popover-exit-active > .bp3-tooltip{
    -webkit-transform:scale(0.8);
            transform:scale(0.8);
    -webkit-transition-property:-webkit-transform;
    transition-property:-webkit-transform;
    transition-property:transform;
    transition-property:transform, -webkit-transform;
    -webkit-transition-duration:100ms;
            transition-duration:100ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
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
  margin:0;
  padding-left:0;
  list-style:none; }

.bp3-tree-root{
  position:relative;
  background-color:transparent;
  cursor:default;
  padding-left:0; }

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
  display:-webkit-box;
  display:-ms-flexbox;
  display:flex;
  -webkit-box-align:center;
      -ms-flex-align:center;
          align-items:center;
  width:100%;
  height:30px;
  padding-right:5px; }
  .bp3-tree-node-content:hover{
    background-color:rgba(191, 204, 214, 0.4); }

.bp3-tree-node-caret,
.bp3-tree-node-caret-none{
  min-width:30px; }

.bp3-tree-node-caret{
  color:#5c7080;
  -webkit-transform:rotate(0deg);
          transform:rotate(0deg);
  cursor:pointer;
  padding:7px;
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
  position:relative;
  margin-right:7px; }

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
    display:-webkit-box;
    display:-ms-flexbox;
    display:flex;
    -webkit-box-align:center;
        -ms-flex-align:center;
            align-items:center; }

.bp3-tree-node.bp3-disabled .bp3-tree-node-content{
  background-color:inherit;
  cursor:not-allowed;
  color:rgba(92, 112, 128, 0.6); }

.bp3-tree-node.bp3-disabled .bp3-tree-node-caret,
.bp3-tree-node.bp3-disabled .bp3-tree-node-icon{
  cursor:not-allowed;
  color:rgba(92, 112, 128, 0.6); }

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
/*!

Copyright 2017-present Palantir Technologies, Inc. All rights reserved.
Licensed under the Apache License, Version 2.0.

*/
.bp3-omnibar{
  -webkit-filter:blur(0);
          filter:blur(0);
  opacity:1;
  top:20vh;
  left:calc(50% - 250px);
  z-index:21;
  border-radius:3px;
  -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
          box-shadow:0 0 0 1px rgba(16, 22, 26, 0.1), 0 4px 8px rgba(16, 22, 26, 0.2), 0 18px 46px 6px rgba(16, 22, 26, 0.2);
  background-color:#ffffff;
  width:500px; }
  .bp3-omnibar.bp3-overlay-enter, .bp3-omnibar.bp3-overlay-appear{
    -webkit-filter:blur(20px);
            filter:blur(20px);
    opacity:0.2; }
  .bp3-omnibar.bp3-overlay-enter-active, .bp3-omnibar.bp3-overlay-appear-active{
    -webkit-filter:blur(0);
            filter:blur(0);
    opacity:1;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:filter, opacity;
    transition-property:filter, opacity, -webkit-filter;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-omnibar.bp3-overlay-exit{
    -webkit-filter:blur(0);
            filter:blur(0);
    opacity:1; }
  .bp3-omnibar.bp3-overlay-exit-active{
    -webkit-filter:blur(20px);
            filter:blur(20px);
    opacity:0.2;
    -webkit-transition-property:opacity, -webkit-filter;
    transition-property:opacity, -webkit-filter;
    transition-property:filter, opacity;
    transition-property:filter, opacity, -webkit-filter;
    -webkit-transition-duration:200ms;
            transition-duration:200ms;
    -webkit-transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
            transition-timing-function:cubic-bezier(0.4, 1, 0.75, 0.9);
    -webkit-transition-delay:0;
            transition-delay:0; }
  .bp3-omnibar .bp3-input{
    border-radius:0;
    background-color:transparent; }
    .bp3-omnibar .bp3-input, .bp3-omnibar .bp3-input:focus{
      -webkit-box-shadow:none;
              box-shadow:none; }
  .bp3-omnibar .bp3-menu{
    border-radius:0;
    -webkit-box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
            box-shadow:inset 0 1px 0 rgba(16, 22, 26, 0.15);
    background-color:transparent;
    max-height:calc(60vh - 40px);
    overflow:auto; }
    .bp3-omnibar .bp3-menu:empty{
      display:none; }
  .bp3-dark .bp3-omnibar, .bp3-omnibar.bp3-dark{
    -webkit-box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
            box-shadow:0 0 0 1px rgba(16, 22, 26, 0.2), 0 4px 8px rgba(16, 22, 26, 0.4), 0 18px 46px 6px rgba(16, 22, 26, 0.4);
    background-color:#30404d; }

.bp3-omnibar-overlay .bp3-overlay-backdrop{
  background-color:rgba(16, 22, 26, 0.2); }

.bp3-select-popover .bp3-popover-content{
  padding:5px; }

.bp3-select-popover .bp3-input-group{
  margin-bottom:0; }

.bp3-select-popover .bp3-menu{
  max-width:400px;
  max-height:300px;
  overflow:auto;
  padding:0; }
  .bp3-select-popover .bp3-menu:not(:first-child){
    padding-top:5px; }

.bp3-multi-select{
  min-width:150px; }

.bp3-multi-select-popover .bp3-menu{
  max-width:400px;
  max-height:300px;
  overflow:auto; }

.bp3-select-popover .bp3-popover-content{
  padding:5px; }

.bp3-select-popover .bp3-input-group{
  margin-bottom:0; }

.bp3-select-popover .bp3-menu{
  max-width:400px;
  max-height:300px;
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
  --jp-icon-bug: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwIDhoLTIuODFjLS40NS0uNzgtMS4wNy0xLjQ1LTEuODItMS45NkwxNyA0LjQxIDE1LjU5IDNsLTIuMTcgMi4xN0MxMi45NiA1LjA2IDEyLjQ5IDUgMTIgNWMtLjQ5IDAtLjk2LjA2LTEuNDEuMTdMOC40MSAzIDcgNC40MWwxLjYyIDEuNjNDNy44OCA2LjU1IDcuMjYgNy4yMiA2LjgxIDhINHYyaDIuMDljLS4wNS4zMy0uMDkuNjYtLjA5IDF2MUg0djJoMnYxYzAgLjM0LjA0LjY3LjA5IDFINHYyaDIuODFjMS4wNCAxLjc5IDIuOTcgMyA1LjE5IDNzNC4xNS0xLjIxIDUuMTktM0gyMHYtMmgtMi4wOWMuMDUtLjMzLjA5LS42Ni4wOS0xdi0xaDJ2LTJoLTJ2LTFjMC0uMzQtLjA0LS42Ny0uMDktMUgyMFY4em0tNiA4aC00di0yaDR2MnptMC00aC00di0yaDR2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-build: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE0LjkgMTcuNDVDMTYuMjUgMTcuNDUgMTcuMzUgMTYuMzUgMTcuMzUgMTVDMTcuMzUgMTMuNjUgMTYuMjUgMTIuNTUgMTQuOSAxMi41NUMxMy41NCAxMi41NSAxMi40NSAxMy42NSAxMi40NSAxNUMxMi40NSAxNi4zNSAxMy41NCAxNy40NSAxNC45IDE3LjQ1Wk0yMC4xIDE1LjY4TDIxLjU4IDE2Ljg0QzIxLjcxIDE2Ljk1IDIxLjc1IDE3LjEzIDIxLjY2IDE3LjI5TDIwLjI2IDE5LjcxQzIwLjE3IDE5Ljg2IDIwIDE5LjkyIDE5LjgzIDE5Ljg2TDE4LjA5IDE5LjE2QzE3LjczIDE5LjQ0IDE3LjMzIDE5LjY3IDE2LjkxIDE5Ljg1TDE2LjY0IDIxLjdDMTYuNjIgMjEuODcgMTYuNDcgMjIgMTYuMyAyMkgxMy41QzEzLjMyIDIyIDEzLjE4IDIxLjg3IDEzLjE1IDIxLjdMMTIuODkgMTkuODVDMTIuNDYgMTkuNjcgMTIuMDcgMTkuNDQgMTEuNzEgMTkuMTZMOS45NjAwMiAxOS44NkM5LjgxMDAyIDE5LjkyIDkuNjIwMDIgMTkuODYgOS41NDAwMiAxOS43MUw4LjE0MDAyIDE3LjI5QzguMDUwMDIgMTcuMTMgOC4wOTAwMiAxNi45NSA4LjIyMDAyIDE2Ljg0TDkuNzAwMDIgMTUuNjhMOS42NTAwMSAxNUw5LjcwMDAyIDE0LjMxTDguMjIwMDIgMTMuMTZDOC4wOTAwMiAxMy4wNSA4LjA1MDAyIDEyLjg2IDguMTQwMDIgMTIuNzFMOS41NDAwMiAxMC4yOUM5LjYyMDAyIDEwLjEzIDkuODEwMDIgMTAuMDcgOS45NjAwMiAxMC4xM0wxMS43MSAxMC44NEMxMi4wNyAxMC41NiAxMi40NiAxMC4zMiAxMi44OSAxMC4xNUwxMy4xNSA4LjI4OTk4QzEzLjE4IDguMTI5OTggMTMuMzIgNy45OTk5OCAxMy41IDcuOTk5OThIMTYuM0MxNi40NyA3Ljk5OTk4IDE2LjYyIDguMTI5OTggMTYuNjQgOC4yODk5OEwxNi45MSAxMC4xNUMxNy4zMyAxMC4zMiAxNy43MyAxMC41NiAxOC4wOSAxMC44NEwxOS44MyAxMC4xM0MyMCAxMC4wNyAyMC4xNyAxMC4xMyAyMC4yNiAxMC4yOUwyMS42NiAxMi43MUMyMS43NSAxMi44NiAyMS43MSAxMy4wNSAyMS41OCAxMy4xNkwyMC4xIDE0LjMxTDIwLjE1IDE1TDIwLjEgMTUuNjhaIi8+CiAgICA8cGF0aCBkPSJNNy4zMjk2NiA3LjQ0NDU0QzguMDgzMSA3LjAwOTU0IDguMzM5MzIgNi4wNTMzMiA3LjkwNDMyIDUuMjk5ODhDNy40NjkzMiA0LjU0NjQzIDYuNTA4MSA0LjI4MTU2IDUuNzU0NjYgNC43MTY1NkM1LjM5MTc2IDQuOTI2MDggNS4xMjY5NSA1LjI3MTE4IDUuMDE4NDkgNS42NzU5NEM0LjkxMDA0IDYuMDgwNzEgNC45NjY4MiA2LjUxMTk4IDUuMTc2MzQgNi44NzQ4OEM1LjYxMTM0IDcuNjI4MzIgNi41NzYyMiA3Ljg3OTU0IDcuMzI5NjYgNy40NDQ1NFpNOS42NTcxOCA0Ljc5NTkzTDEwLjg2NzIgNC45NTE3OUMxMC45NjI4IDQuOTc3NDEgMTEuMDQwMiA1LjA3MTMzIDExLjAzODIgNS4xODc5M0wxMS4wMzg4IDYuOTg4OTNDMTEuMDQ1NSA3LjEwMDU0IDEwLjk2MTYgNy4xOTUxOCAxMC44NTUgNy4yMTA1NEw5LjY2MDAxIDcuMzgwODNMOS4yMzkxNSA4LjEzMTg4TDkuNjY5NjEgOS4yNTc0NUM5LjcwNzI5IDkuMzYyNzEgOS42NjkzNCA5LjQ3Njk5IDkuNTc0MDggOS41MzE5OUw4LjAxNTIzIDEwLjQzMkM3LjkxMTMxIDEwLjQ5MiA3Ljc5MzM3IDEwLjQ2NzcgNy43MjEwNSAxMC4zODI0TDYuOTg3NDggOS40MzE4OEw2LjEwOTMxIDkuNDMwODNMNS4zNDcwNCAxMC4zOTA1QzUuMjg5MDkgMTAuNDcwMiA1LjE3MzgzIDEwLjQ5MDUgNS4wNzE4NyAxMC40MzM5TDMuNTEyNDUgOS41MzI5M0MzLjQxMDQ5IDkuNDc2MzMgMy4zNzY0NyA5LjM1NzQxIDMuNDEwNzUgOS4yNTY3OUwzLjg2MzQ3IDguMTQwOTNMMy42MTc0OSA3Ljc3NDg4TDMuNDIzNDcgNy4zNzg4M0wyLjIzMDc1IDcuMjEyOTdDMi4xMjY0NyA3LjE5MjM1IDIuMDQwNDkgNy4xMDM0MiAyLjA0MjQ1IDYuOTg2ODJMMi4wNDE4NyA1LjE4NTgyQzIuMDQzODMgNS4wNjkyMiAyLjExOTA5IDQuOTc5NTggMi4yMTcwNCA0Ljk2OTIyTDMuNDIwNjUgNC43OTM5M0wzLjg2NzQ5IDQuMDI3ODhMMy40MTEwNSAyLjkxNzMxQzMuMzczMzcgMi44MTIwNCAzLjQxMTMxIDIuNjk3NzYgMy41MTUyMyAyLjYzNzc2TDUuMDc0MDggMS43Mzc3NkM1LjE2OTM0IDEuNjgyNzYgNS4yODcyOSAxLjcwNzA0IDUuMzU5NjEgMS43OTIzMUw2LjExOTE1IDIuNzI3ODhMNi45ODAwMSAyLjczODkzTDcuNzI0OTYgMS43ODkyMkM3Ljc5MTU2IDEuNzA0NTggNy45MTU0OCAxLjY3OTIyIDguMDA4NzkgMS43NDA4Mkw5LjU2ODIxIDIuNjQxODJDOS42NzAxNyAyLjY5ODQyIDkuNzEyODUgMi44MTIzNCA5LjY4NzIzIDIuOTA3OTdMOS4yMTcxOCA0LjAzMzgzTDkuNDYzMTYgNC4zOTk4OEw5LjY1NzE4IDQuNzk1OTNaIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iOS45LDEzLjYgMy42LDcuNCA0LjQsNi42IDkuOSwxMi4yIDE1LjQsNi43IDE2LjEsNy40ICIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNS45TDksOS43bDMuOC0zLjhsMS4yLDEuMmwtNC45LDVsLTQuOS01TDUuMiw1Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNy41TDksMTEuMmwzLjgtMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-left: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik0xMC44LDEyLjhMNy4xLDlsMy44LTMuOGwwLDcuNkgxMC44eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-right: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik03LjIsNS4yTDEwLjksOWwtMy44LDMuOFY1LjJINy4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-up-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iMTUuNCwxMy4zIDkuOSw3LjcgNC40LDEzLjIgMy42LDEyLjUgOS45LDYuMyAxNi4xLDEyLjYgIi8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-up: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik01LjIsMTAuNUw5LDYuOGwzLjgsMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-case-sensitive: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWFjY2VudDIiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTcuNiw4aDAuOWwzLjUsOGgtMS4xTDEwLDE0SDZsLTAuOSwySDRMNy42LDh6IE04LDkuMUw2LjQsMTNoMy4yTDgsOS4xeiIvPgogICAgPHBhdGggZD0iTTE2LjYsOS44Yy0wLjIsMC4xLTAuNCwwLjEtMC43LDAuMWMtMC4yLDAtMC40LTAuMS0wLjYtMC4yYy0wLjEtMC4xLTAuMi0wLjQtMC4yLTAuNyBjLTAuMywwLjMtMC42LDAuNS0wLjksMC43Yy0wLjMsMC4xLTAuNywwLjItMS4xLDAuMmMtMC4zLDAtMC41LDAtMC43LTAuMWMtMC4yLTAuMS0wLjQtMC4yLTAuNi0wLjNjLTAuMi0wLjEtMC4zLTAuMy0wLjQtMC41IGMtMC4xLTAuMi0wLjEtMC40LTAuMS0wLjdjMC0wLjMsMC4xLTAuNiwwLjItMC44YzAuMS0wLjIsMC4zLTAuNCwwLjQtMC41QzEyLDcsMTIuMiw2LjksMTIuNSw2LjhjMC4yLTAuMSwwLjUtMC4xLDAuNy0wLjIgYzAuMy0wLjEsMC41LTAuMSwwLjctMC4xYzAuMiwwLDAuNC0wLjEsMC42LTAuMWMwLjIsMCwwLjMtMC4xLDAuNC0wLjJjMC4xLTAuMSwwLjItMC4yLDAuMi0wLjRjMC0xLTEuMS0xLTEuMy0xIGMtMC40LDAtMS40LDAtMS40LDEuMmgtMC45YzAtMC40LDAuMS0wLjcsMC4yLTFjMC4xLTAuMiwwLjMtMC40LDAuNS0wLjZjMC4yLTAuMiwwLjUtMC4zLDAuOC0wLjNDMTMuMyw0LDEzLjYsNCwxMy45LDQgYzAuMywwLDAuNSwwLDAuOCwwLjFjMC4zLDAsMC41LDAuMSwwLjcsMC4yYzAuMiwwLjEsMC40LDAuMywwLjUsMC41QzE2LDUsMTYsNS4yLDE2LDUuNnYyLjljMCwwLjIsMCwwLjQsMCwwLjUgYzAsMC4xLDAuMSwwLjIsMC4zLDAuMmMwLjEsMCwwLjIsMCwwLjMsMFY5Ljh6IE0xNS4yLDYuOWMtMS4yLDAuNi0zLjEsMC4yLTMuMSwxLjRjMCwxLjQsMy4xLDEsMy4xLTAuNVY2Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkgMTYuMTdMNC44MyAxMmwtMS40MiAxLjQxTDkgMTkgMjEgN2wtMS40MS0xLjQxeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-circle-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDJDNi40NyAyIDIgNi40NyAyIDEyczQuNDcgMTAgMTAgMTAgMTAtNC40NyAxMC0xMFMxNy41MyAyIDEyIDJ6bTAgMThjLTQuNDEgMC04LTMuNTktOC04czMuNTktOCA4LTggOCAzLjU5IDggOC0zLjU5IDgtOCA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-circle: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iOSIgY3k9IjkiIHI9IjgiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-clear: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8bWFzayBpZD0iZG9udXRIb2xlIj4KICAgIDxyZWN0IHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgZmlsbD0id2hpdGUiIC8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI4IiBmaWxsPSJibGFjayIvPgogIDwvbWFzaz4KCiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxyZWN0IGhlaWdodD0iMTgiIHdpZHRoPSIyIiB4PSIxMSIgeT0iMyIgdHJhbnNmb3JtPSJyb3RhdGUoMzE1LCAxMiwgMTIpIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIxMCIgbWFzaz0idXJsKCNkb251dEhvbGUpIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-close: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1ub25lIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIGpwLWljb24zLWhvdmVyIiBmaWxsPSJub25lIj4KICAgIDxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjExIi8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIGpwLWljb24tYWNjZW50Mi1ob3ZlciIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMTkgNi40MUwxNy41OSA1IDEyIDEwLjU5IDYuNDEgNSA1IDYuNDEgMTAuNTkgMTIgNSAxNy41OSA2LjQxIDE5IDEyIDEzLjQxIDE3LjU5IDE5IDE5IDE3LjU5IDEzLjQxIDEyeiIvPgogIDwvZz4KCiAgPGcgY2xhc3M9ImpwLWljb24tbm9uZSBqcC1pY29uLWJ1c3kiIGZpbGw9Im5vbmUiPgogICAgPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-console: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwMCAyMDAiPgogIDxnIGNsYXNzPSJqcC1pY29uLWJyYW5kMSBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMjg4RDEiPgogICAgPHBhdGggZD0iTTIwIDE5LjhoMTYwdjE1OS45SDIweiIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNmZmYiPgogICAgPHBhdGggZD0iTTEwNSAxMjcuM2g0MHYxMi44aC00MHpNNTEuMSA3N0w3NCA5OS45bC0yMy4zIDIzLjMgMTAuNSAxMC41IDIzLjMtMjMuM0w5NSA5OS45IDg0LjUgODkuNCA2MS42IDY2LjV6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-copy: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTExLjksMUgzLjJDMi40LDEsMS43LDEuNywxLjcsMi41djEwLjJoMS41VjIuNWg4LjdWMXogTTE0LjEsMy45aC04Yy0wLjgsMC0xLjUsMC43LTEuNSwxLjV2MTAuMmMwLDAuOCwwLjcsMS41LDEuNSwxLjVoOCBjMC44LDAsMS41LTAuNywxLjUtMS41VjUuNEMxNS41LDQuNiwxNC45LDMuOSwxNC4xLDMuOXogTTE0LjEsMTUuNWgtOFY1LjRoOFYxNS41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
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
  --jp-icon-jupyter-favicon: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTUyIiBoZWlnaHQ9IjE2NSIgdmlld0JveD0iMCAwIDE1MiAxNjUiIHZlcnNpb249IjEuMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA3ODk0NywgMTEwLjU4MjkyNykiIGQ9Ik03NS45NDIyODQyLDI5LjU4MDQ1NjEgQzQzLjMwMjM5NDcsMjkuNTgwNDU2MSAxNC43OTY3ODMyLDE3LjY1MzQ2MzQgMCwwIEM1LjUxMDgzMjExLDE1Ljg0MDY4MjkgMTUuNzgxNTM4OSwyOS41NjY3NzMyIDI5LjM5MDQ5NDcsMzkuMjc4NDE3MSBDNDIuOTk5Nyw0OC45ODk4NTM3IDU5LjI3MzcsNTQuMjA2NzgwNSA3NS45NjA1Nzg5LDU0LjIwNjc4MDUgQzkyLjY0NzQ1NzksNTQuMjA2NzgwNSAxMDguOTIxNDU4LDQ4Ljk4OTg1MzcgMTIyLjUzMDY2MywzOS4yNzg0MTcxIEMxMzYuMTM5NDUzLDI5LjU2Njc3MzIgMTQ2LjQxMDI4NCwxNS44NDA2ODI5IDE1MS45MjExNTgsMCBDMTM3LjA4Nzg2OCwxNy42NTM0NjM0IDEwOC41ODI1ODksMjkuNTgwNDU2MSA3NS45NDIyODQyLDI5LjU4MDQ1NjEgTDc1Ljk0MjI4NDIsMjkuNTgwNDU2MSBaIiAvPgogICAgPHBhdGggdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMzczNjgsIDAuNzA0ODc4KSIgZD0iTTc1Ljk3ODQ1NzksMjQuNjI2NDA3MyBDMTA4LjYxODc2MywyNC42MjY0MDczIDEzNy4xMjQ0NTgsMzYuNTUzNDQxNSAxNTEuOTIxMTU4LDU0LjIwNjc4MDUgQzE0Ni40MTAyODQsMzguMzY2MjIyIDEzNi4xMzk0NTMsMjQuNjQwMTMxNyAxMjIuNTMwNjYzLDE0LjkyODQ4NzggQzEwOC45MjE0NTgsNS4yMTY4NDM5IDkyLjY0NzQ1NzksMCA3NS45NjA1Nzg5LDAgQzU5LjI3MzcsMCA0Mi45OTk3LDUuMjE2ODQzOSAyOS4zOTA0OTQ3LDE0LjkyODQ4NzggQzE1Ljc4MTUzODksMjQuNjQwMTMxNyA1LjUxMDgzMjExLDM4LjM2NjIyMiAwLDU0LjIwNjc4MDUgQzE0LjgzMzA4MTYsMzYuNTg5OTI5MyA0My4zMzg1Njg0LDI0LjYyNjQwNzMgNzUuOTc4NDU3OSwyNC42MjY0MDczIEw3NS45Nzg0NTc5LDI0LjYyNjQwNzMgWiIgLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-jupyter: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzkiIGhlaWdodD0iNTEiIHZpZXdCb3g9IjAgMCAzOSA1MSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMTYzOCAtMjI4MSkiPgogICAgPGcgY2xhc3M9ImpwLWljb24td2FybjAiIGZpbGw9IiNGMzc3MjYiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5Ljc0IDIzMTEuOTgpIiBkPSJNIDE4LjI2NDYgNy4xMzQxMUMgMTAuNDE0NSA3LjEzNDExIDMuNTU4NzIgNC4yNTc2IDAgMEMgMS4zMjUzOSAzLjgyMDQgMy43OTU1NiA3LjEzMDgxIDcuMDY4NiA5LjQ3MzAzQyAxMC4zNDE3IDExLjgxNTIgMTQuMjU1NyAxMy4wNzM0IDE4LjI2OSAxMy4wNzM0QyAyMi4yODIzIDEzLjA3MzQgMjYuMTk2MyAxMS44MTUyIDI5LjQ2OTQgOS40NzMwM0MgMzIuNzQyNCA3LjEzMDgxIDM1LjIxMjYgMy44MjA0IDM2LjUzOCAwQyAzMi45NzA1IDQuMjU3NiAyNi4xMTQ4IDcuMTM0MTEgMTguMjY0NiA3LjEzNDExWiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5LjczIDIyODUuNDgpIiBkPSJNIDE4LjI3MzMgNS45MzkzMUMgMjYuMTIzNSA1LjkzOTMxIDMyLjk3OTMgOC44MTU4MyAzNi41MzggMTMuMDczNEMgMzUuMjEyNiA5LjI1MzAzIDMyLjc0MjQgNS45NDI2MiAyOS40Njk0IDMuNjAwNEMgMjYuMTk2MyAxLjI1ODE4IDIyLjI4MjMgMCAxOC4yNjkgMEMgMTQuMjU1NyAwIDEwLjM0MTcgMS4yNTgxOCA3LjA2ODYgMy42MDA0QyAzLjc5NTU2IDUuOTQyNjIgMS4zMjUzOSA5LjI1MzAzIDAgMTMuMDczNEMgMy41Njc0NSA4LjgyNDYzIDEwLjQyMzIgNS45MzkzMSAxOC4yNzMzIDUuOTM5MzFaIi8+CiAgICA8L2c+CiAgICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjY5LjMgMjI4MS4zMSkiIGQ9Ik0gNS44OTM1MyAyLjg0NEMgNS45MTg4OSAzLjQzMTY1IDUuNzcwODUgNC4wMTM2NyA1LjQ2ODE1IDQuNTE2NDVDIDUuMTY1NDUgNS4wMTkyMiA0LjcyMTY4IDUuNDIwMTUgNC4xOTI5OSA1LjY2ODUxQyAzLjY2NDMgNS45MTY4OCAzLjA3NDQ0IDYuMDAxNTEgMi40OTgwNSA1LjkxMTcxQyAxLjkyMTY2IDUuODIxOSAxLjM4NDYzIDUuNTYxNyAwLjk1NDg5OCA1LjE2NDAxQyAwLjUyNTE3IDQuNzY2MzMgMC4yMjIwNTYgNC4yNDkwMyAwLjA4MzkwMzcgMy42Nzc1N0MgLTAuMDU0MjQ4MyAzLjEwNjExIC0wLjAyMTIzIDIuNTA2MTcgMC4xNzg3ODEgMS45NTM2NEMgMC4zNzg3OTMgMS40MDExIDAuNzM2ODA5IDAuOTIwODE3IDEuMjA3NTQgMC41NzM1MzhDIDEuNjc4MjYgMC4yMjYyNTkgMi4yNDA1NSAwLjAyNzU5MTkgMi44MjMyNiAwLjAwMjY3MjI5QyAzLjYwMzg5IC0wLjAzMDcxMTUgNC4zNjU3MyAwLjI0OTc4OSA0Ljk0MTQyIDAuNzgyNTUxQyA1LjUxNzExIDEuMzE1MzEgNS44NTk1NiAyLjA1Njc2IDUuODkzNTMgMi44NDRaIi8+CiAgICAgIDxwYXRoIHRyYW5zZm9ybT0idHJhbnNsYXRlKDE2MzkuOCAyMzIzLjgxKSIgZD0iTSA3LjQyNzg5IDMuNTgzMzhDIDcuNDYwMDggNC4zMjQzIDcuMjczNTUgNS4wNTgxOSA2Ljg5MTkzIDUuNjkyMTNDIDYuNTEwMzEgNi4zMjYwNyA1Ljk1MDc1IDYuODMxNTYgNS4yODQxMSA3LjE0NDZDIDQuNjE3NDcgNy40NTc2MyAzLjg3MzcxIDcuNTY0MTQgMy4xNDcwMiA3LjQ1MDYzQyAyLjQyMDMyIDcuMzM3MTIgMS43NDMzNiA3LjAwODcgMS4yMDE4NCA2LjUwNjk1QyAwLjY2MDMyOCA2LjAwNTIgMC4yNzg2MSA1LjM1MjY4IDAuMTA1MDE3IDQuNjMyMDJDIC0wLjA2ODU3NTcgMy45MTEzNSAtMC4wMjYyMzYxIDMuMTU0OTQgMC4yMjY2NzUgMi40NTg1NkMgMC40Nzk1ODcgMS43NjIxNyAwLjkzMTY5NyAxLjE1NzEzIDEuNTI1NzYgMC43MjAwMzNDIDIuMTE5ODMgMC4yODI5MzUgMi44MjkxNCAwLjAzMzQzOTUgMy41NjM4OSAwLjAwMzEzMzQ0QyA0LjU0NjY3IC0wLjAzNzQwMzMgNS41MDUyOSAwLjMxNjcwNiA2LjIyOTYxIDAuOTg3ODM1QyA2Ljk1MzkzIDEuNjU4OTYgNy4zODQ4NCAyLjU5MjM1IDcuNDI3ODkgMy41ODMzOEwgNy40Mjc4OSAzLjU4MzM4WiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM4LjM2IDIyODYuMDYpIiBkPSJNIDIuMjc0NzEgNC4zOTYyOUMgMS44NDM2MyA0LjQxNTA4IDEuNDE2NzEgNC4zMDQ0NSAxLjA0Nzk5IDQuMDc4NDNDIDAuNjc5MjY4IDMuODUyNCAwLjM4NTMyOCAzLjUyMTE0IDAuMjAzMzcxIDMuMTI2NTZDIDAuMDIxNDEzNiAyLjczMTk4IC0wLjA0MDM3OTggMi4yOTE4MyAwLjAyNTgxMTYgMS44NjE4MUMgMC4wOTIwMDMxIDEuNDMxOCAwLjI4MzIwNCAxLjAzMTI2IDAuNTc1MjEzIDAuNzEwODgzQyAwLjg2NzIyMiAwLjM5MDUxIDEuMjQ2OTEgMC4xNjQ3MDggMS42NjYyMiAwLjA2MjA1OTJDIDIuMDg1NTMgLTAuMDQwNTg5NyAyLjUyNTYxIC0wLjAxNTQ3MTQgMi45MzA3NiAwLjEzNDIzNUMgMy4zMzU5MSAwLjI4Mzk0MSAzLjY4NzkyIDAuNTUxNTA1IDMuOTQyMjIgMC45MDMwNkMgNC4xOTY1MiAxLjI1NDYyIDQuMzQxNjkgMS42NzQzNiA0LjM1OTM1IDIuMTA5MTZDIDQuMzgyOTkgMi42OTEwNyA0LjE3Njc4IDMuMjU4NjkgMy43ODU5NyAzLjY4NzQ2QyAzLjM5NTE2IDQuMTE2MjQgMi44NTE2NiA0LjM3MTE2IDIuMjc0NzEgNC4zOTYyOUwgMi4yNzQ3MSA0LjM5NjI5WiIvPgogICAgPC9nPgogIDwvZz4+Cjwvc3ZnPgo=);
  --jp-icon-jupyterlab-wordmark: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIHZpZXdCb3g9IjAgMCAxODYwLjggNDc1Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0RTRFNEUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDQ4MC4xMzY0MDEsIDY0LjI3MTQ5MykiPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMDAwMDAsIDU4Ljg3NTU2NikiPgogICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA4NzYwMywgMC4xNDAyOTQpIj4KICAgICAgICA8cGF0aCBkPSJNLTQyNi45LDE2OS44YzAsNDguNy0zLjcsNjQuNy0xMy42LDc2LjRjLTEwLjgsMTAtMjUsMTUuNS0zOS43LDE1LjVsMy43LDI5IGMyMi44LDAuMyw0NC44LTcuOSw2MS45LTIzLjFjMTcuOC0xOC41LDI0LTQ0LjEsMjQtODMuM1YwSC00Mjd2MTcwLjFMLTQyNi45LDE2OS44TC00MjYuOSwxNjkuOHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTU1LjA0NTI5NiwgNTYuODM3MTA0KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuNTYyNDUzLCAxLjc5OTg0MikiPgogICAgICAgIDxwYXRoIGQ9Ik0tMzEyLDE0OGMwLDIxLDAsMzkuNSwxLjcsNTUuNGgtMzEuOGwtMi4xLTMzLjNoLTAuOGMtNi43LDExLjYtMTYuNCwyMS4zLTI4LDI3LjkgYy0xMS42LDYuNi0yNC44LDEwLTM4LjIsOS44Yy0zMS40LDAtNjktMTcuNy02OS04OVYwaDM2LjR2MTEyLjdjMCwzOC43LDExLjYsNjQuNyw0NC42LDY0LjdjMTAuMy0wLjIsMjAuNC0zLjUsMjguOS05LjQgYzguNS01LjksMTUuMS0xNC4zLDE4LjktMjMuOWMyLjItNi4xLDMuMy0xMi41LDMuMy0xOC45VjAuMmgzNi40VjE0OEgtMzEyTC0zMTIsMTQ4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzOTAuMDEzMzIyLCA1My40Nzk2MzgpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS43MDY0NTgsIDAuMjMxNDI1KSI+CiAgICAgICAgPHBhdGggZD0iTS00NzguNiw3MS40YzAtMjYtMC44LTQ3LTEuNy02Ni43aDMyLjdsMS43LDM0LjhoMC44YzcuMS0xMi41LDE3LjUtMjIuOCwzMC4xLTI5LjcgYzEyLjUtNywyNi43LTEwLjMsNDEtOS44YzQ4LjMsMCw4NC43LDQxLjcsODQuNywxMDMuM2MwLDczLjEtNDMuNywxMDkuMi05MSwxMDkuMmMtMTIuMSwwLjUtMjQuMi0yLjItMzUtNy44IGMtMTAuOC01LjYtMTkuOS0xMy45LTI2LjYtMjQuMmgtMC44VjI5MWgtMzZ2LTIyMEwtNDc4LjYsNzEuNEwtNDc4LjYsNzEuNHogTS00NDIuNiwxMjUuNmMwLjEsNS4xLDAuNiwxMC4xLDEuNywxNS4xIGMzLDEyLjMsOS45LDIzLjMsMTkuOCwzMS4xYzkuOSw3LjgsMjIuMSwxMi4xLDM0LjcsMTIuMWMzOC41LDAsNjAuNy0zMS45LDYwLjctNzguNWMwLTQwLjctMjEuMS03NS42LTU5LjUtNzUuNiBjLTEyLjksMC40LTI1LjMsNS4xLTM1LjMsMTMuNGMtOS45LDguMy0xNi45LDE5LjctMTkuNiwzMi40Yy0xLjUsNC45LTIuMywxMC0yLjUsMTUuMVYxMjUuNkwtNDQyLjYsMTI1LjZMLTQ0Mi42LDEyNS42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg2MDYuNzQwNzI2LCA1Ni44MzcxMDQpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC43NTEyMjYsIDEuOTg5Mjk5KSI+CiAgICAgICAgPHBhdGggZD0iTS00NDAuOCwwbDQzLjcsMTIwLjFjNC41LDEzLjQsOS41LDI5LjQsMTIuOCw0MS43aDAuOGMzLjctMTIuMiw3LjktMjcuNywxMi44LTQyLjQgbDM5LjctMTE5LjJoMzguNUwtMzQ2LjksMTQ1Yy0yNiw2OS43LTQzLjcsMTA1LjQtNjguNiwxMjcuMmMtMTIuNSwxMS43LTI3LjksMjAtNDQuNiwyMy45bC05LjEtMzEuMSBjMTEuNy0zLjksMjIuNS0xMC4xLDMxLjgtMTguMWMxMy4yLTExLjEsMjMuNy0yNS4yLDMwLjYtNDEuMmMxLjUtMi44LDIuNS01LjcsMi45LTguOGMtMC4zLTMuMy0xLjItNi42LTIuNS05LjdMLTQ4MC4yLDAuMSBoMzkuN0wtNDQwLjgsMEwtNDQwLjgsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoODIyLjc0ODEwNCwgMC4wMDAwMDApIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS40NjQwNTAsIDAuMzc4OTE0KSI+CiAgICAgICAgPHBhdGggZD0iTS00MTMuNywwdjU4LjNoNTJ2MjguMmgtNTJWMTk2YzAsMjUsNywzOS41LDI3LjMsMzkuNWM3LjEsMC4xLDE0LjItMC43LDIxLjEtMi41IGwxLjcsMjcuN2MtMTAuMywzLjctMjEuMyw1LjQtMzIuMiw1Yy03LjMsMC40LTE0LjYtMC43LTIxLjMtMy40Yy02LjgtMi43LTEyLjktNi44LTE3LjktMTIuMWMtMTAuMy0xMC45LTE0LjEtMjktMTQuMS01Mi45IFY4Ni41aC0zMVY1OC4zaDMxVjkuNkwtNDEzLjcsMEwtNDEzLjcsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOTc0LjQzMzI4NiwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAuOTkwMDM0LCAwLjYxMDMzOSkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDQ1LjgsMTEzYzAuOCw1MCwzMi4yLDcwLjYsNjguNiw3MC42YzE5LDAuNiwzNy45LTMsNTUuMy0xMC41bDYuMiwyNi40IGMtMjAuOSw4LjktNDMuNSwxMy4xLTY2LjIsMTIuNmMtNjEuNSwwLTk4LjMtNDEuMi05OC4zLTEwMi41Qy00ODAuMiw0OC4yLTQ0NC43LDAtMzg2LjUsMGM2NS4yLDAsODIuNyw1OC4zLDgyLjcsOTUuNyBjLTAuMSw1LjgtMC41LDExLjUtMS4yLDE3LjJoLTE0MC42SC00NDUuOEwtNDQ1LjgsMTEzeiBNLTMzOS4yLDg2LjZjMC40LTIzLjUtOS41LTYwLjEtNTAuNC02MC4xIGMtMzYuOCwwLTUyLjgsMzQuNC01NS43LDYwLjFILTMzOS4yTC0zMzkuMiw4Ni42TC0zMzkuMiw4Ni42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMjAxLjk2MTA1OCwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuMTc5NjQwLCAwLjcwNTA2OCkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDc4LjYsNjhjMC0yMy45LTAuNC00NC41LTEuNy02My40aDMxLjhsMS4yLDM5LjloMS43YzkuMS0yNy4zLDMxLTQ0LjUsNTUuMy00NC41IGMzLjUtMC4xLDcsMC40LDEwLjMsMS4ydjM0LjhjLTQuMS0wLjktOC4yLTEuMy0xMi40LTEuMmMtMjUuNiwwLTQzLjcsMTkuNy00OC43LDQ3LjRjLTEsNS43LTEuNiwxMS41LTEuNywxNy4ydjEwOC4zaC0zNlY2OCBMLTQ3OC42LDY4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCBkPSJNMTM1Mi4zLDMyNi4yaDM3VjI4aC0zN1YzMjYuMnogTTE2MDQuOCwzMjYuMmMtMi41LTEzLjktMy40LTMxLjEtMy40LTQ4Ljd2LTc2IGMwLTQwLjctMTUuMS04My4xLTc3LjMtODMuMWMtMjUuNiwwLTUwLDcuMS02Ni44LDE4LjFsOC40LDI0LjRjMTQuMy05LjIsMzQtMTUuMSw1My0xNS4xYzQxLjYsMCw0Ni4yLDMwLjIsNDYuMiw0N3Y0LjIgYy03OC42LTAuNC0xMjIuMywyNi41LTEyMi4zLDc1LjZjMCwyOS40LDIxLDU4LjQsNjIuMiw1OC40YzI5LDAsNTAuOS0xNC4zLDYyLjItMzAuMmgxLjNsMi45LDI1LjZIMTYwNC44eiBNMTU2NS43LDI1Ny43IGMwLDMuOC0wLjgsOC0yLjEsMTEuOGMtNS45LDE3LjItMjIuNywzNC00OS4yLDM0Yy0xOC45LDAtMzQuOS0xMS4zLTM0LjktMzUuM2MwLTM5LjUsNDUuOC00Ni42LDg2LjItNDUuOFYyNTcuN3ogTTE2OTguNSwzMjYuMiBsMS43LTMzLjZoMS4zYzE1LjEsMjYuOSwzOC43LDM4LjIsNjguMSwzOC4yYzQ1LjQsMCw5MS4yLTM2LjEsOTEuMi0xMDguOGMwLjQtNjEuNy0zNS4zLTEwMy43LTg1LjctMTAzLjcgYy0zMi44LDAtNTYuMywxNC43LTY5LjMsMzcuNGgtMC44VjI4aC0zNi42djI0NS43YzAsMTguMS0wLjgsMzguNi0xLjcsNTIuNUgxNjk4LjV6IE0xNzA0LjgsMjA4LjJjMC01LjksMS4zLTEwLjksMi4xLTE1LjEgYzcuNi0yOC4xLDMxLjEtNDUuNCw1Ni4zLTQ1LjRjMzkuNSwwLDYwLjUsMzQuOSw2MC41LDc1LjZjMCw0Ni42LTIzLjEsNzguMS02MS44LDc4LjFjLTI2LjksMC00OC4zLTE3LjYtNTUuNS00My4zIGMtMC44LTQuMi0xLjctOC44LTEuNy0xMy40VjIwOC4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzYxNjE2MSIgZD0iTTE1IDlIOXY2aDZWOXptLTIgNGgtMnYtMmgydjJ6bTgtMlY5aC0yVjdjMC0xLjEtLjktMi0yLTJoLTJWM2gtMnYyaC0yVjNIOXYySDdjLTEuMSAwLTIgLjktMiAydjJIM3YyaDJ2MkgzdjJoMnYyYzAgMS4xLjkgMiAyIDJoMnYyaDJ2LTJoMnYyaDJ2LTJoMmMxLjEgMCAyLS45IDItMnYtMmgydi0yaC0ydi0yaDJ6bS00IDZIN1Y3aDEwdjEweiIvPgo8L3N2Zz4K);
  --jp-icon-keyboard: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMTdjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY3YzAtMS4xLS45LTItMi0yem0tOSAzaDJ2MmgtMlY4em0wIDNoMnYyaC0ydi0yek04IDhoMnYySDhWOHptMCAzaDJ2Mkg4di0yem0tMSAySDV2LTJoMnYyem0wLTNINVY4aDJ2MnptOSA3SDh2LTJoOHYyem0wLTRoLTJ2LTJoMnYyem0wLTNoLTJWOGgydjJ6bTMgM2gtMnYtMmgydjJ6bTAtM2gtMlY4aDJ2MnoiLz4KPC9zdmc+Cg==);
  --jp-icon-launcher: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkgMTlINVY1aDdWM0g1YTIgMiAwIDAwLTIgMnYxNGEyIDIgMCAwMDIgMmgxNGMxLjEgMCAyLS45IDItMnYtN2gtMnY3ek0xNCAzdjJoMy41OWwtOS44MyA5LjgzIDEuNDEgMS40MUwxOSA2LjQxVjEwaDJWM2gtN3oiLz4KPC9zdmc+Cg==);
  --jp-icon-line-form: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGZpbGw9IndoaXRlIiBkPSJNNS44OCA0LjEyTDEzLjc2IDEybC03Ljg4IDcuODhMOCAyMmwxMC0xMEw4IDJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-link: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMuOSAxMmMwLTEuNzEgMS4zOS0zLjEgMy4xLTMuMWg0VjdIN2MtMi43NiAwLTUgMi4yNC01IDVzMi4yNCA1IDUgNWg0di0xLjlIN2MtMS43MSAwLTMuMS0xLjM5LTMuMS0zLjF6TTggMTNoOHYtMkg4djJ6bTktNmgtNHYxLjloNGMxLjcxIDAgMy4xIDEuMzkgMy4xIDMuMXMtMS4zOSAzLjEtMy4xIDMuMWgtNFYxN2g0YzIuNzYgMCA1LTIuMjQgNS01cy0yLjI0LTUtNS01eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xOSA1djE0SDVWNWgxNG0xLjEtMkgzLjljLS41IDAtLjkuNC0uOS45djE2LjJjMCAuNC40LjkuOS45aDE2LjJjLjQgMCAuOS0uNS45LS45VjMuOWMwLS41LS41LS45LS45LS45ek0xMSA3aDZ2MmgtNlY3em0wIDRoNnYyaC02di0yem0wIDRoNnYyaC02ek03IDdoMnYySDd6bTAgNGgydjJIN3ptMCA0aDJ2Mkg3eiIvPgo8L3N2Zz4=);
  --jp-icon-listings-info: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pg0KPHN2ZyB2ZXJzaW9uPSIxLjEiIGlkPSJDYXBhXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSIwIDAgNTAuOTc4IDUwLjk3OCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgNTAuOTc4IDUwLjk3ODsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPGc+DQoJPGc+DQoJCTxnPg0KCQkJPHBhdGggc3R5bGU9ImZpbGw6IzAxMDAwMjsiIGQ9Ik00My41Miw3LjQ1OEMzOC43MTEsMi42NDgsMzIuMzA3LDAsMjUuNDg5LDBDMTguNjcsMCwxMi4yNjYsMi42NDgsNy40NTgsNy40NTgNCgkJCQljLTkuOTQzLDkuOTQxLTkuOTQzLDI2LjExOSwwLDM2LjA2MmM0LjgwOSw0LjgwOSwxMS4yMTIsNy40NTYsMTguMDMxLDcuNDU4YzAsMCwwLjAwMSwwLDAuMDAyLDANCgkJCQljNi44MTYsMCwxMy4yMjEtMi42NDgsMTguMDI5LTcuNDU4YzQuODA5LTQuODA5LDcuNDU3LTExLjIxMiw3LjQ1Ny0xOC4wM0M1MC45NzcsMTguNjcsNDguMzI4LDEyLjI2Niw0My41Miw3LjQ1OHoNCgkJCQkgTTQyLjEwNiw0Mi4xMDVjLTQuNDMyLDQuNDMxLTEwLjMzMiw2Ljg3Mi0xNi42MTUsNi44NzJoLTAuMDAyYy02LjI4NS0wLjAwMS0xMi4xODctMi40NDEtMTYuNjE3LTYuODcyDQoJCQkJYy05LjE2Mi05LjE2My05LjE2Mi0yNC4wNzEsMC0zMy4yMzNDMTMuMzAzLDQuNDQsMTkuMjA0LDIsMjUuNDg5LDJjNi4yODQsMCwxMi4xODYsMi40NCwxNi42MTcsNi44NzINCgkJCQljNC40MzEsNC40MzEsNi44NzEsMTAuMzMyLDYuODcxLDE2LjYxN0M0OC45NzcsMzEuNzcyLDQ2LjUzNiwzNy42NzUsNDIuMTA2LDQyLjEwNXoiLz4NCgkJPC9nPg0KCQk8Zz4NCgkJCTxwYXRoIHN0eWxlPSJmaWxsOiMwMTAwMDI7IiBkPSJNMjMuNTc4LDMyLjIxOGMtMC4wMjMtMS43MzQsMC4xNDMtMy4wNTksMC40OTYtMy45NzJjMC4zNTMtMC45MTMsMS4xMS0xLjk5NywyLjI3Mi0zLjI1Mw0KCQkJCWMwLjQ2OC0wLjUzNiwwLjkyMy0xLjA2MiwxLjM2Ny0xLjU3NWMwLjYyNi0wLjc1MywxLjEwNC0xLjQ3OCwxLjQzNi0yLjE3NWMwLjMzMS0wLjcwNywwLjQ5NS0xLjU0MSwwLjQ5NS0yLjUNCgkJCQljMC0xLjA5Ni0wLjI2LTIuMDg4LTAuNzc5LTIuOTc5Yy0wLjU2NS0wLjg3OS0xLjUwMS0xLjMzNi0yLjgwNi0xLjM2OWMtMS44MDIsMC4wNTctMi45ODUsMC42NjctMy41NSwxLjgzMg0KCQkJCWMtMC4zMDEsMC41MzUtMC41MDMsMS4xNDEtMC42MDcsMS44MTRjLTAuMTM5LDAuNzA3LTAuMjA3LDEuNDMyLTAuMjA3LDIuMTc0aC0yLjkzN2MtMC4wOTEtMi4yMDgsMC40MDctNC4xMTQsMS40OTMtNS43MTkNCgkJCQljMS4wNjItMS42NCwyLjg1NS0yLjQ4MSw1LjM3OC0yLjUyN2MyLjE2LDAuMDIzLDMuODc0LDAuNjA4LDUuMTQxLDEuNzU4YzEuMjc4LDEuMTYsMS45MjksMi43NjQsMS45NSw0LjgxMQ0KCQkJCWMwLDEuMTQyLTAuMTM3LDIuMTExLTAuNDEsMi45MTFjLTAuMzA5LDAuODQ1LTAuNzMxLDEuNTkzLTEuMjY4LDIuMjQzYy0wLjQ5MiwwLjY1LTEuMDY4LDEuMzE4LTEuNzMsMi4wMDINCgkJCQljLTAuNjUsMC42OTctMS4zMTMsMS40NzktMS45ODcsMi4zNDZjLTAuMjM5LDAuMzc3LTAuNDI5LDAuNzc3LTAuNTY1LDEuMTk5Yy0wLjE2LDAuOTU5LTAuMjE3LDEuOTUxLTAuMTcxLDIuOTc5DQoJCQkJQzI2LjU4OSwzMi4yMTgsMjMuNTc4LDMyLjIxOCwyMy41NzgsMzIuMjE4eiBNMjMuNTc4LDM4LjIydi0zLjQ4NGgzLjA3NnYzLjQ4NEgyMy41Nzh6Ii8+DQoJCTwvZz4NCgk8L2c+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8L3N2Zz4NCg==);
  --jp-icon-markdown: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjN0IxRkEyIiBkPSJNNSAxNC45aDEybC02LjEgNnptOS40LTYuOGMwLTEuMy0uMS0yLjktLjEtNC41LS40IDEuNC0uOSAyLjktMS4zIDQuM2wtMS4zIDQuM2gtMkw4LjUgNy45Yy0uNC0xLjMtLjctMi45LTEtNC4zLS4xIDEuNi0uMSAzLjItLjIgNC42TDcgMTIuNEg0LjhsLjctMTFoMy4zTDEwIDVjLjQgMS4yLjcgMi43IDEgMy45LjMtMS4yLjctMi42IDEtMy45bDEuMi0zLjdoMy4zbC42IDExaC0yLjRsLS4zLTQuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-new-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwIDZoLThsLTItMkg0Yy0xLjExIDAtMS45OS44OS0xLjk5IDJMMiAxOGMwIDEuMTEuODkgMiAyIDJoMTZjMS4xMSAwIDItLjg5IDItMlY4YzAtMS4xMS0uODktMi0yLTJ6bS0xIDhoLTN2M2gtMnYtM2gtM3YtMmgzVjloMnYzaDN2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-not-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI1IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMTkgMTcuMTg0NCAyLjk2OTY4IDE0LjMwMzIgMS44NjA5NCAxMS40NDA5WiIvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24yIiBzdHJva2U9IiMzMzMzMzMiIHN0cm9rZS13aWR0aD0iMiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOS4zMTU5MiA5LjMyMDMxKSIgZD0iTTcuMzY4NDIgMEwwIDcuMzY0NzkiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDkuMzE1OTIgMTYuNjgzNikgc2NhbGUoMSAtMSkiIGQ9Ik03LjM2ODQyIDBMMCA3LjM2NDc5Ii8+Cjwvc3ZnPgo=);
  --jp-icon-notebook: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNFRjZDMDAiPgogICAgPHBhdGggZD0iTTE4LjcgMy4zdjE1LjRIMy4zVjMuM2gxNS40bTEuNS0xLjVIMS44djE4LjNoMTguM2wuMS0xOC4zeiIvPgogICAgPHBhdGggZD0iTTE2LjUgMTYuNWwtNS40LTQuMy01LjYgNC4zdi0xMWgxMXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-palette: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE4IDEzVjIwSDRWNkg5LjAyQzkuMDcgNS4yOSA5LjI0IDQuNjIgOS41IDRINEMyLjkgNCAyIDQuOSAyIDZWMjBDMiAyMS4xIDIuOSAyMiA0IDIySDE4QzE5LjEgMjIgMjAgMjEuMSAyMCAyMFYxNUwxOCAxM1pNMTkuMyA4Ljg5QzE5Ljc0IDguMTkgMjAgNy4zOCAyMCA2LjVDMjAgNC4wMSAxNy45OSAyIDE1LjUgMkMxMy4wMSAyIDExIDQuMDEgMTEgNi41QzExIDguOTkgMTMuMDEgMTEgMTUuNDkgMTFDMTYuMzcgMTEgMTcuMTkgMTAuNzQgMTcuODggMTAuM0wyMSAxMy40MkwyMi40MiAxMkwxOS4zIDguODlaTTE1LjUgOUMxNC4xMiA5IDEzIDcuODggMTMgNi41QzEzIDUuMTIgMTQuMTIgNCAxNS41IDRDMTYuODggNCAxOCA1LjEyIDE4IDYuNUMxOCA3Ljg4IDE2Ljg4IDkgMTUuNSA5WiIvPgogICAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik00IDZIOS4wMTg5NEM5LjAwNjM5IDYuMTY1MDIgOSA2LjMzMTc2IDkgNi41QzkgOC44MTU3NyAxMC4yMTEgMTAuODQ4NyAxMi4wMzQzIDEySDlWMTRIMTZWMTIuOTgxMUMxNi41NzAzIDEyLjkzNzcgMTcuMTIgMTIuODIwNyAxNy42Mzk2IDEyLjYzOTZMMTggMTNWMjBINFY2Wk04IDhINlYxMEg4VjhaTTYgMTJIOFYxNEg2VjEyWk04IDE2SDZWMThIOFYxNlpNOSAxNkgxNlYxOEg5VjE2WiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-paste: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE5IDJoLTQuMThDMTQuNC44NCAxMy4zIDAgMTIgMGMtMS4zIDAtMi40Ljg0LTIuODIgMkg1Yy0xLjEgMC0yIC45LTIgMnYxNmMwIDEuMS45IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjRjMC0xLjEtLjktMi0yLTJ6bS03IDBjLjU1IDAgMSAuNDUgMSAxcy0uNDUgMS0xIDEtMS0uNDUtMS0xIC40NS0xIDEtMXptNyAxOEg1VjRoMnYzaDEwVjRoMnYxNnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-python: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMEQ0N0ExIj4KICAgIDxwYXRoIGQ9Ik0xMS4xIDYuOVY1LjhINi45YzAtLjUgMC0xLjMuMi0xLjYuNC0uNy44LTEuMSAxLjctMS40IDEuNy0uMyAyLjUtLjMgMy45LS4xIDEgLjEgMS45LjkgMS45IDEuOXY0LjJjMCAuNS0uOSAxLjYtMiAxLjZIOC44Yy0xLjUgMC0yLjQgMS40LTIuNCAyLjh2Mi4ySDQuN0MzLjUgMTUuMSAzIDE0IDMgMTMuMVY5Yy0uMS0xIC42LTIgMS44LTIgMS41LS4xIDYuMy0uMSA2LjMtLjF6Ii8+CiAgICA8cGF0aCBkPSJNMTAuOSAxNS4xdjEuMWg0LjJjMCAuNSAwIDEuMy0uMiAxLjYtLjQuNy0uOCAxLjEtMS43IDEuNC0xLjcuMy0yLjUuMy0zLjkuMS0xLS4xLTEuOS0uOS0xLjktMS45di00LjJjMC0uNS45LTEuNiAyLTEuNmgzLjhjMS41IDAgMi40LTEuNCAyLjQtMi44VjYuNmgxLjdDMTguNSA2LjkgMTkgOCAxOSA4LjlWMTNjMCAxLS43IDIuMS0xLjkgMi4xaC02LjJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-r-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjE5NkYzIiBkPSJNNC40IDIuNWMxLjItLjEgMi45LS4zIDQuOS0uMyAyLjUgMCA0LjEuNCA1LjIgMS4zIDEgLjcgMS41IDEuOSAxLjUgMy41IDAgMi0xLjQgMy41LTIuOSA0LjEgMS4yLjQgMS43IDEuNiAyLjIgMyAuNiAxLjkgMSAzLjkgMS4zIDQuNmgtMy44Yy0uMy0uNC0uOC0xLjctMS4yLTMuN3MtMS4yLTIuNi0yLjYtMi42aC0uOXY2LjRINC40VjIuNXptMy43IDYuOWgxLjRjMS45IDAgMi45LS45IDIuOS0yLjNzLTEtMi4zLTIuOC0yLjNjLS43IDAtMS4zIDAtMS42LjJ2NC41aC4xdi0uMXoiLz4KPC9zdmc+Cg==);
  --jp-icon-react: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMTUwIDE1MCA1NDEuOSAyOTUuMyI+CiAgPGcgY2xhc3M9ImpwLWljb24tYnJhbmQyIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxREFGQiI+CiAgICA8cGF0aCBkPSJNNjY2LjMgMjk2LjVjMC0zMi41LTQwLjctNjMuMy0xMDMuMS04Mi40IDE0LjQtNjMuNiA4LTExNC4yLTIwLjItMTMwLjQtNi41LTMuOC0xNC4xLTUuNi0yMi40LTUuNnYyMi4zYzQuNiAwIDguMy45IDExLjQgMi42IDEzLjYgNy44IDE5LjUgMzcuNSAxNC45IDc1LjctMS4xIDkuNC0yLjkgMTkuMy01LjEgMjkuNC0xOS42LTQuOC00MS04LjUtNjMuNS0xMC45LTEzLjUtMTguNS0yNy41LTM1LjMtNDEuNi01MCAzMi42LTMwLjMgNjMuMi00Ni45IDg0LTQ2LjlWNzhjLTI3LjUgMC02My41IDE5LjYtOTkuOSA1My42LTM2LjQtMzMuOC03Mi40LTUzLjItOTkuOS01My4ydjIyLjNjMjAuNyAwIDUxLjQgMTYuNSA4NCA0Ni42LTE0IDE0LjctMjggMzEuNC00MS4zIDQ5LjktMjIuNiAyLjQtNDQgNi4xLTYzLjYgMTEtMi4zLTEwLTQtMTkuNy01LjItMjktNC43LTM4LjIgMS4xLTY3LjkgMTQuNi03NS44IDMtMS44IDYuOS0yLjYgMTEuNS0yLjZWNzguNWMtOC40IDAtMTYgMS44LTIyLjYgNS42LTI4LjEgMTYuMi0zNC40IDY2LjctMTkuOSAxMzAuMS02Mi4yIDE5LjItMTAyLjcgNDkuOS0xMDIuNyA4Mi4zIDAgMzIuNSA0MC43IDYzLjMgMTAzLjEgODIuNC0xNC40IDYzLjYtOCAxMTQuMiAyMC4yIDEzMC40IDYuNSAzLjggMTQuMSA1LjYgMjIuNSA1LjYgMjcuNSAwIDYzLjUtMTkuNiA5OS45LTUzLjYgMzYuNCAzMy44IDcyLjQgNTMuMiA5OS45IDUzLjIgOC40IDAgMTYtMS44IDIyLjYtNS42IDI4LjEtMTYuMiAzNC40LTY2LjcgMTkuOS0xMzAuMSA2Mi0xOS4xIDEwMi41LTQ5LjkgMTAyLjUtODIuM3ptLTEzMC4yLTY2LjdjLTMuNyAxMi45LTguMyAyNi4yLTEzLjUgMzkuNS00LjEtOC04LjQtMTYtMTMuMS0yNC00LjYtOC05LjUtMTUuOC0xNC40LTIzLjQgMTQuMiAyLjEgMjcuOSA0LjcgNDEgNy45em0tNDUuOCAxMDYuNWMtNy44IDEzLjUtMTUuOCAyNi4zLTI0LjEgMzguMi0xNC45IDEuMy0zMCAyLTQ1LjIgMi0xNS4xIDAtMzAuMi0uNy00NS0xLjktOC4zLTExLjktMTYuNC0yNC42LTI0LjItMzgtNy42LTEzLjEtMTQuNS0yNi40LTIwLjgtMzkuOCA2LjItMTMuNCAxMy4yLTI2LjggMjAuNy0zOS45IDcuOC0xMy41IDE1LjgtMjYuMyAyNC4xLTM4LjIgMTQuOS0xLjMgMzAtMiA0NS4yLTIgMTUuMSAwIDMwLjIuNyA0NSAxLjkgOC4zIDExLjkgMTYuNCAyNC42IDI0LjIgMzggNy42IDEzLjEgMTQuNSAyNi40IDIwLjggMzkuOC02LjMgMTMuNC0xMy4yIDI2LjgtMjAuNyAzOS45em0zMi4zLTEzYzUuNCAxMy40IDEwIDI2LjggMTMuOCAzOS44LTEzLjEgMy4yLTI2LjkgNS45LTQxLjIgOCA0LjktNy43IDkuOC0xNS42IDE0LjQtMjMuNyA0LjYtOCA4LjktMTYuMSAxMy0yNC4xek00MjEuMiA0MzBjLTkuMy05LjYtMTguNi0yMC4zLTI3LjgtMzIgOSAuNCAxOC4yLjcgMjcuNS43IDkuNCAwIDE4LjctLjIgMjcuOC0uNy05IDExLjctMTguMyAyMi40LTI3LjUgMzJ6bS03NC40LTU4LjljLTE0LjItMi4xLTI3LjktNC43LTQxLTcuOSAzLjctMTIuOSA4LjMtMjYuMiAxMy41LTM5LjUgNC4xIDggOC40IDE2IDEzLjEgMjQgNC43IDggOS41IDE1LjggMTQuNCAyMy40ek00MjAuNyAxNjNjOS4zIDkuNiAxOC42IDIwLjMgMjcuOCAzMi05LS40LTE4LjItLjctMjcuNS0uNy05LjQgMC0xOC43LjItMjcuOC43IDktMTEuNyAxOC4zLTIyLjQgMjcuNS0zMnptLTc0IDU4LjljLTQuOSA3LjctOS44IDE1LjYtMTQuNCAyMy43LTQuNiA4LTguOSAxNi0xMyAyNC01LjQtMTMuNC0xMC0yNi44LTEzLjgtMzkuOCAxMy4xLTMuMSAyNi45LTUuOCA0MS4yLTcuOXptLTkwLjUgMTI1LjJjLTM1LjQtMTUuMS01OC4zLTM0LjktNTguMy01MC42IDAtMTUuNyAyMi45LTM1LjYgNTguMy01MC42IDguNi0zLjcgMTgtNyAyNy43LTEwLjEgNS43IDE5LjYgMTMuMiA0MCAyMi41IDYwLjktOS4yIDIwLjgtMTYuNiA0MS4xLTIyLjIgNjAuNi05LjktMy4xLTE5LjMtNi41LTI4LTEwLjJ6TTMxMCA0OTBjLTEzLjYtNy44LTE5LjUtMzcuNS0xNC45LTc1LjcgMS4xLTkuNCAyLjktMTkuMyA1LjEtMjkuNCAxOS42IDQuOCA0MSA4LjUgNjMuNSAxMC45IDEzLjUgMTguNSAyNy41IDM1LjMgNDEuNiA1MC0zMi42IDMwLjMtNjMuMiA0Ni45LTg0IDQ2LjktNC41LS4xLTguMy0xLTExLjMtMi43em0yMzcuMi03Ni4yYzQuNyAzOC4yLTEuMSA2Ny45LTE0LjYgNzUuOC0zIDEuOC02LjkgMi42LTExLjUgMi42LTIwLjcgMC01MS40LTE2LjUtODQtNDYuNiAxNC0xNC43IDI4LTMxLjQgNDEuMy00OS45IDIyLjYtMi40IDQ0LTYuMSA2My42LTExIDIuMyAxMC4xIDQuMSAxOS44IDUuMiAyOS4xem0zOC41LTY2LjdjLTguNiAzLjctMTggNy0yNy43IDEwLjEtNS43LTE5LjYtMTMuMi00MC0yMi41LTYwLjkgOS4yLTIwLjggMTYuNi00MS4xIDIyLjItNjAuNiA5LjkgMy4xIDE5LjMgNi41IDI4LjEgMTAuMiAzNS40IDE1LjEgNTguMyAzNC45IDU4LjMgNTAuNi0uMSAxNS43LTIzIDM1LjYtNTguNCA1MC42ek0zMjAuOCA3OC40eiIvPgogICAgPGNpcmNsZSBjeD0iNDIwLjkiIGN5PSIyOTYuNSIgcj0iNDUuNyIvPgogIDwvZz4KPC9zdmc+Cg==);
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
  --jp-icon-terminal: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0IiA+CiAgICA8cmVjdCBjbGFzcz0ianAtaWNvbjIganAtaWNvbi1zZWxlY3RhYmxlIiB3aWR0aD0iMjAiIGhlaWdodD0iMjAiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMikiIGZpbGw9IiMzMzMzMzMiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uLWFjY2VudDIganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGQ9Ik01LjA1NjY0IDguNzYxNzJDNS4wNTY2NCA4LjU5NzY2IDUuMDMxMjUgOC40NTMxMiA0Ljk4MDQ3IDguMzI4MTJDNC45MzM1OSA4LjE5OTIyIDQuODU1NDcgOC4wODIwMyA0Ljc0NjA5IDcuOTc2NTZDNC42NDA2MiA3Ljg3MTA5IDQuNSA3Ljc3NTM5IDQuMzI0MjIgNy42ODk0NUM0LjE1MjM0IDcuNTk5NjEgMy45NDMzNiA3LjUxMTcyIDMuNjk3MjcgNy40MjU3OEMzLjMwMjczIDcuMjg1MTYgMi45NDMzNiA3LjEzNjcyIDIuNjE5MTQgNi45ODA0N0MyLjI5NDkyIDYuODI0MjIgMi4wMTc1OCA2LjY0MjU4IDEuNzg3MTEgNi40MzU1NUMxLjU2MDU1IDYuMjI4NTIgMS4zODQ3NyA1Ljk4ODI4IDEuMjU5NzcgNS43MTQ4NEMxLjEzNDc3IDUuNDM3NSAxLjA3MjI3IDUuMTA5MzggMS4wNzIyNyA0LjczMDQ3QzEuMDcyMjcgNC4zOTg0NCAxLjEyODkxIDQuMDk1NyAxLjI0MjE5IDMuODIyMjdDMS4zNTU0NyAzLjU0NDkyIDEuNTE1NjIgMy4zMDQ2OSAxLjcyMjY2IDMuMTAxNTZDMS45Mjk2OSAyLjg5ODQ0IDIuMTc5NjkgMi43MzQzNyAyLjQ3MjY2IDIuNjA5MzhDMi43NjU2MiAyLjQ4NDM4IDMuMDkxOCAyLjQwNDMgMy40NTExNyAyLjM2OTE0VjEuMTA5MzhINC4zODg2N1YyLjM4MDg2QzQuNzQwMjMgMi40Mjc3MyA1LjA1NjY0IDIuNTIzNDQgNS4zMzc4OSAyLjY2Nzk3QzUuNjE5MTQgMi44MTI1IDUuODU3NDIgMy4wMDE5NSA2LjA1MjczIDMuMjM2MzNDNi4yNTE5NSAzLjQ2NjggNi40MDQzIDMuNzQwMjMgNi41MDk3NyA0LjA1NjY0QzYuNjE5MTQgNC4zNjkxNCA2LjY3MzgzIDQuNzIwNyA2LjY3MzgzIDUuMTExMzNINS4wNDQ5MkM1LjA0NDkyIDQuNjM4NjcgNC45Mzc1IDQuMjgxMjUgNC43MjI2NiA0LjAzOTA2QzQuNTA3ODEgMy43OTI5NyA0LjIxNjggMy42Njk5MiAzLjg0OTYxIDMuNjY5OTJDMy42NTAzOSAzLjY2OTkyIDMuNDc2NTYgMy42OTcyNyAzLjMyODEyIDMuNzUxOTVDMy4xODM1OSAzLjgwMjczIDMuMDY0NDUgMy44NzY5NSAyLjk3MDcgMy45NzQ2MUMyLjg3Njk1IDQuMDY4MzYgMi44MDY2NCA0LjE3OTY5IDIuNzU5NzcgNC4zMDg1OUMyLjcxNjggNC40Mzc1IDIuNjk1MzEgNC41NzgxMiAyLjY5NTMxIDQuNzMwNDdDMi42OTUzMSA0Ljg4MjgxIDIuNzE2OCA1LjAxOTUzIDIuNzU5NzcgNS4xNDA2MkMyLjgwNjY0IDUuMjU3ODEgMi44ODI4MSA1LjM2NzE5IDIuOTg4MjggNS40Njg3NUMzLjA5NzY2IDUuNTcwMzEgMy4yNDAyMyA1LjY2Nzk3IDMuNDE2MDIgNS43NjE3MkMzLjU5MTggNS44NTE1NiAzLjgxMDU1IDUuOTQzMzYgNC4wNzIyNyA2LjAzNzExQzQuNDY2OCA2LjE4NTU1IDQuODI0MjIgNi4zMzk4NCA1LjE0NDUzIDYuNUM1LjQ2NDg0IDYuNjU2MjUgNS43MzgyOCA2LjgzOTg0IDUuOTY0ODQgNy4wNTA3OEM2LjE5NTMxIDcuMjU3ODEgNi4zNzEwOSA3LjUgNi40OTIxOSA3Ljc3NzM0QzYuNjE3MTkgOC4wNTA3OCA2LjY3OTY5IDguMzc1IDYuNjc5NjkgOC43NUM2LjY3OTY5IDkuMDkzNzUgNi42MjMwNSA5LjQwNDMgNi41MDk3NyA5LjY4MTY0QzYuMzk2NDggOS45NTUwOCA2LjIzNDM4IDEwLjE5MTQgNi4wMjM0NCAxMC4zOTA2QzUuODEyNSAxMC41ODk4IDUuNTU4NTkgMTAuNzUgNS4yNjE3MiAxMC44NzExQzQuOTY0ODQgMTAuOTg4MyA0LjYzMjgxIDExLjA2NDUgNC4yNjU2MiAxMS4wOTk2VjEyLjI0OEgzLjMzMzk4VjExLjA5OTZDMy4wMDE5NSAxMS4wNjg0IDIuNjc5NjkgMTAuOTk2MSAyLjM2NzE5IDEwLjg4MjhDMi4wNTQ2OSAxMC43NjU2IDEuNzc3MzQgMTAuNTk3NyAxLjUzNTE2IDEwLjM3ODlDMS4yOTY4OCAxMC4xNjAyIDEuMTA1NDcgOS44ODQ3NyAwLjk2MDkzOCA5LjU1MjczQzAuODE2NDA2IDkuMjE2OCAwLjc0NDE0MSA4LjgxNDQ1IDAuNzQ0MTQxIDguMzQ1N0gyLjM3ODkxQzIuMzc4OTEgOC42MjY5NSAyLjQxOTkyIDguODYzMjggMi41MDE5NSA5LjA1NDY5QzIuNTgzOTggOS4yNDIxOSAyLjY4OTQ1IDkuMzkyNTggMi44MTgzNiA5LjUwNTg2QzIuOTUxMTcgOS42MTUyMyAzLjEwMTU2IDkuNjkzMzYgMy4yNjk1MyA5Ljc0MDIzQzMuNDM3NSA5Ljc4NzExIDMuNjA5MzggOS44MTA1NSAzLjc4NTE2IDkuODEwNTVDNC4yMDMxMiA5LjgxMDU1IDQuNTE5NTMgOS43MTI4OSA0LjczNDM4IDkuNTE3NThDNC45NDkyMiA5LjMyMjI3IDUuMDU2NjQgOS4wNzAzMSA1LjA1NjY0IDguNzYxNzJaTTEzLjQxOCAxMi4yNzE1SDguMDc0MjJWMTFIMTMuNDE4VjEyLjI3MTVaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzLjk1MjY0IDYpIiBmaWxsPSJ3aGl0ZSIvPgo8L3N2Zz4K);
  --jp-icon-text-editor: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTUgMTVIM3YyaDEydi0yem0wLThIM3YyaDEyVjd6TTMgMTNoMTh2LTJIM3Yyem0wIDhoMTh2LTJIM3Yyek0zIDN2MmgxOFYzSDN6Ii8+Cjwvc3ZnPgo=);
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
.jp-ConsoleIcon {
  background-image: var(--jp-icon-console);
}
.jp-CopyIcon {
  background-image: var(--jp-icon-copy);
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
.jp-PaletteIcon {
  background-image: var(--jp-icon-palette);
}
.jp-PasteIcon {
  background-image: var(--jp-icon-paste);
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
.jp-TerminalIcon {
  background-image: var(--jp-icon-terminal);
}
.jp-TextEditorIcon {
  background-image: var(--jp-icon-text-editor);
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

:root {
  --jp-icon-search-white: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjEsMTAuOWgtMC43bC0wLjItMC4yYzAuOC0wLjksMS4zLTIuMiwxLjMtMy41YzAtMy0yLjQtNS40LTUuNC01LjRTMS44LDQuMiwxLjgsNy4xczIuNCw1LjQsNS40LDUuNCBjMS4zLDAsMi41LTAuNSwzLjUtMS4zbDAuMiwwLjJ2MC43bDQuMSw0LjFsMS4yLTEuMkwxMi4xLDEwLjl6IE03LjEsMTAuOWMtMi4xLDAtMy43LTEuNy0zLjctMy43czEuNy0zLjcsMy43LTMuN3MzLjcsMS43LDMuNywzLjcgUzkuMiwxMC45LDcuMSwxMC45eiIvPgogIDwvZz4KPC9zdmc+Cg==);
}

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

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

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

.lm-CommandPalette-wrapper::after {
  content: ' ';
  color: white;
  background-color: var(--jp-brand-color1);
  position: absolute;
  top: 4px;
  right: 4px;
  height: 30px;
  width: 10px;
  padding: 0px 10px;
  background-image: var(--jp-icon-search-white);
  background-size: 20px;
  background-repeat: no-repeat;
  background-position: center;
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
  color: var(--jp-ui-font-color3);
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
  color: var(--jp-ui-font-color3);
}

.lm-CommandPalette-item.lm-mod-active {
  background: var(--jp-layout-color3);
}

.lm-CommandPalette-item.lm-mod-active:hover:not(.lm-mod-disabled) {
  background: var(--jp-layout-color4);
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
  color: var(--jp-ui-font-color3);
}

.lm-CommandPalette-item .lm-CommandPalette-itemIcon {
  margin: 0 4px 0 0;
  position: relative;
  width: 16px;
  top: 2px;
  flex: 0 0 auto;
}

.lm-CommandPalette-item.lm-mod-disabled .lm-CommandPalette-itemIcon {
  opacity: 0.4;
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

.jp-Dialog-header {
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

input.jp-mod-styled:focus {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
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

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

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

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

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
  /* 30px is the magic margin used to hide the element's real scrollbars */
  /* See overflow: hidden in .CodeMirror */
  margin-bottom: -30px; margin-right: -30px;
  padding-bottom: 30px;
  height: 100%;
  outline: none; /* Prevent dragging from highlighting the element */
  position: relative;
}
.CodeMirror-sizer {
  position: relative;
  border-right: 30px solid transparent;
}

/* The fake, visible scrollbars. Used to force redraw during scrolling
   before actual scrolling happens, thus preventing shaking and
   flickering artifacts. */
.CodeMirror-vscrollbar, .CodeMirror-hscrollbar, .CodeMirror-scrollbar-filler, .CodeMirror-gutter-filler {
  position: absolute;
  z-index: 6;
  display: none;
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
  margin-bottom: -30px;
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

/*
  Name:       material
  Author:     Mattia Astorino (http://github.com/equinusocio)
  Website:    https://material-theme.site/
*/

.cm-s-material.CodeMirror {
  background-color: #263238;
  color: #EEFFFF;
}

.cm-s-material .CodeMirror-gutters {
  background: #263238;
  color: #546E7A;
  border: none;
}

.cm-s-material .CodeMirror-guttermarker,
.cm-s-material .CodeMirror-guttermarker-subtle,
.cm-s-material .CodeMirror-linenumber {
  color: #546E7A;
}

.cm-s-material .CodeMirror-cursor {
  border-left: 1px solid #FFCC00;
}

.cm-s-material div.CodeMirror-selected {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material.CodeMirror-focused div.CodeMirror-selected {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material .CodeMirror-line::selection,
.cm-s-material .CodeMirror-line>span::selection,
.cm-s-material .CodeMirror-line>span>span::selection {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material .CodeMirror-line::-moz-selection,
.cm-s-material .CodeMirror-line>span::-moz-selection,
.cm-s-material .CodeMirror-line>span>span::-moz-selection {
  background: rgba(128, 203, 196, 0.2);
}

.cm-s-material .CodeMirror-activeline-background {
  background: rgba(0, 0, 0, 0.5);
}

.cm-s-material .cm-keyword {
  color: #C792EA;
}

.cm-s-material .cm-operator {
  color: #89DDFF;
}

.cm-s-material .cm-variable-2 {
  color: #EEFFFF;
}

.cm-s-material .cm-variable-3,
.cm-s-material .cm-type {
  color: #f07178;
}

.cm-s-material .cm-builtin {
  color: #FFCB6B;
}

.cm-s-material .cm-atom {
  color: #F78C6C;
}

.cm-s-material .cm-number {
  color: #FF5370;
}

.cm-s-material .cm-def {
  color: #82AAFF;
}

.cm-s-material .cm-string {
  color: #C3E88D;
}

.cm-s-material .cm-string-2 {
  color: #f07178;
}

.cm-s-material .cm-comment {
  color: #546E7A;
}

.cm-s-material .cm-variable {
  color: #f07178;
}

.cm-s-material .cm-tag {
  color: #FF5370;
}

.cm-s-material .cm-meta {
  color: #FFCB6B;
}

.cm-s-material .cm-attribute {
  color: #C792EA;
}

.cm-s-material .cm-property {
  color: #C792EA;
}

.cm-s-material .cm-qualifier {
  color: #DECB6B;
}

.cm-s-material .cm-variable-3,
.cm-s-material .cm-type {
  color: #DECB6B;
}


.cm-s-material .cm-error {
  color: rgba(255, 255, 255, 1.0);
  background-color: #FF5370;
}

.cm-s-material .CodeMirror-matchingbracket {
  text-decoration: underline;
  color: white !important;
}
/**
 * "
 *  Using Zenburn color palette from the Emacs Zenburn Theme
 *  https://github.com/bbatsov/zenburn-emacs/blob/master/zenburn-theme.el
 *
 *  Also using parts of https://github.com/xavi/coderay-lighttable-theme
 * "
 * From: https://github.com/wisenomad/zenburn-lighttable-theme/blob/master/zenburn.css
 */

.cm-s-zenburn .CodeMirror-gutters { background: #3f3f3f !important; }
.cm-s-zenburn .CodeMirror-foldgutter-open, .CodeMirror-foldgutter-folded { color: #999; }
.cm-s-zenburn .CodeMirror-cursor { border-left: 1px solid white; }
.cm-s-zenburn { background-color: #3f3f3f; color: #dcdccc; }
.cm-s-zenburn span.cm-builtin { color: #dcdccc; font-weight: bold; }
.cm-s-zenburn span.cm-comment { color: #7f9f7f; }
.cm-s-zenburn span.cm-keyword { color: #f0dfaf; font-weight: bold; }
.cm-s-zenburn span.cm-atom { color: #bfebbf; }
.cm-s-zenburn span.cm-def { color: #dcdccc; }
.cm-s-zenburn span.cm-variable { color: #dfaf8f; }
.cm-s-zenburn span.cm-variable-2 { color: #dcdccc; }
.cm-s-zenburn span.cm-string { color: #cc9393; }
.cm-s-zenburn span.cm-string-2 { color: #cc9393; }
.cm-s-zenburn span.cm-number { color: #dcdccc; }
.cm-s-zenburn span.cm-tag { color: #93e0e3; }
.cm-s-zenburn span.cm-property { color: #dfaf8f; }
.cm-s-zenburn span.cm-attribute { color: #dfaf8f; }
.cm-s-zenburn span.cm-qualifier { color: #7cb8bb; }
.cm-s-zenburn span.cm-meta { color: #f0dfaf; }
.cm-s-zenburn span.cm-header { color: #f0efd0; }
.cm-s-zenburn span.cm-operator { color: #f0efd0; }
.cm-s-zenburn span.CodeMirror-matchingbracket { box-sizing: border-box; background: transparent; border-bottom: 1px solid; }
.cm-s-zenburn span.CodeMirror-nonmatchingbracket { border-bottom: 1px solid; background: none; }
.cm-s-zenburn .CodeMirror-activeline { background: #000000; }
.cm-s-zenburn .CodeMirror-activeline-background { background: #000000; }
.cm-s-zenburn div.CodeMirror-selected { background: #545454; }
.cm-s-zenburn .CodeMirror-focused div.CodeMirror-selected { background: #4f4f4f; }

.cm-s-abcdef.CodeMirror { background: #0f0f0f; color: #defdef; }
.cm-s-abcdef div.CodeMirror-selected { background: #515151; }
.cm-s-abcdef .CodeMirror-line::selection, .cm-s-abcdef .CodeMirror-line > span::selection, .cm-s-abcdef .CodeMirror-line > span > span::selection { background: rgba(56, 56, 56, 0.99); }
.cm-s-abcdef .CodeMirror-line::-moz-selection, .cm-s-abcdef .CodeMirror-line > span::-moz-selection, .cm-s-abcdef .CodeMirror-line > span > span::-moz-selection { background: rgba(56, 56, 56, 0.99); }
.cm-s-abcdef .CodeMirror-gutters { background: #555; border-right: 2px solid #314151; }
.cm-s-abcdef .CodeMirror-guttermarker { color: #222; }
.cm-s-abcdef .CodeMirror-guttermarker-subtle { color: azure; }
.cm-s-abcdef .CodeMirror-linenumber { color: #FFFFFF; }
.cm-s-abcdef .CodeMirror-cursor { border-left: 1px solid #00FF00; }

.cm-s-abcdef span.cm-keyword { color: darkgoldenrod; font-weight: bold; }
.cm-s-abcdef span.cm-atom { color: #77F; }
.cm-s-abcdef span.cm-number { color: violet; }
.cm-s-abcdef span.cm-def { color: #fffabc; }
.cm-s-abcdef span.cm-variable { color: #abcdef; }
.cm-s-abcdef span.cm-variable-2 { color: #cacbcc; }
.cm-s-abcdef span.cm-variable-3, .cm-s-abcdef span.cm-type { color: #def; }
.cm-s-abcdef span.cm-property { color: #fedcba; }
.cm-s-abcdef span.cm-operator { color: #ff0; }
.cm-s-abcdef span.cm-comment { color: #7a7b7c; font-style: italic;}
.cm-s-abcdef span.cm-string { color: #2b4; }
.cm-s-abcdef span.cm-meta { color: #C9F; }
.cm-s-abcdef span.cm-qualifier { color: #FFF700; }
.cm-s-abcdef span.cm-builtin { color: #30aabc; }
.cm-s-abcdef span.cm-bracket { color: #8a8a8a; }
.cm-s-abcdef span.cm-tag { color: #FFDD44; }
.cm-s-abcdef span.cm-attribute { color: #DDFF00; }
.cm-s-abcdef span.cm-error { color: #FF0000; }
.cm-s-abcdef span.cm-header { color: aquamarine; font-weight: bold; }
.cm-s-abcdef span.cm-link { color: blueviolet; }

.cm-s-abcdef .CodeMirror-activeline-background { background: #314151; }

/*

    Name:       Base16 Default Light
    Author:     Chris Kempson (http://chriskempson.com)

    CodeMirror template by Jan T. Sott (https://github.com/idleberg/base16-codemirror)
    Original Base16 color scheme by Chris Kempson (https://github.com/chriskempson/base16)

*/

.cm-s-base16-light.CodeMirror { background: #f5f5f5; color: #202020; }
.cm-s-base16-light div.CodeMirror-selected { background: #e0e0e0; }
.cm-s-base16-light .CodeMirror-line::selection, .cm-s-base16-light .CodeMirror-line > span::selection, .cm-s-base16-light .CodeMirror-line > span > span::selection { background: #e0e0e0; }
.cm-s-base16-light .CodeMirror-line::-moz-selection, .cm-s-base16-light .CodeMirror-line > span::-moz-selection, .cm-s-base16-light .CodeMirror-line > span > span::-moz-selection { background: #e0e0e0; }
.cm-s-base16-light .CodeMirror-gutters { background: #f5f5f5; border-right: 0px; }
.cm-s-base16-light .CodeMirror-guttermarker { color: #ac4142; }
.cm-s-base16-light .CodeMirror-guttermarker-subtle { color: #b0b0b0; }
.cm-s-base16-light .CodeMirror-linenumber { color: #b0b0b0; }
.cm-s-base16-light .CodeMirror-cursor { border-left: 1px solid #505050; }

.cm-s-base16-light span.cm-comment { color: #8f5536; }
.cm-s-base16-light span.cm-atom { color: #aa759f; }
.cm-s-base16-light span.cm-number { color: #aa759f; }

.cm-s-base16-light span.cm-property, .cm-s-base16-light span.cm-attribute { color: #90a959; }
.cm-s-base16-light span.cm-keyword { color: #ac4142; }
.cm-s-base16-light span.cm-string { color: #f4bf75; }

.cm-s-base16-light span.cm-variable { color: #90a959; }
.cm-s-base16-light span.cm-variable-2 { color: #6a9fb5; }
.cm-s-base16-light span.cm-def { color: #d28445; }
.cm-s-base16-light span.cm-bracket { color: #202020; }
.cm-s-base16-light span.cm-tag { color: #ac4142; }
.cm-s-base16-light span.cm-link { color: #aa759f; }
.cm-s-base16-light span.cm-error { background: #ac4142; color: #505050; }

.cm-s-base16-light .CodeMirror-activeline-background { background: #DDDCDC; }
.cm-s-base16-light .CodeMirror-matchingbracket { color: #f5f5f5 !important; background-color: #6A9FB5 !important}

/*

    Name:       Base16 Default Dark
    Author:     Chris Kempson (http://chriskempson.com)

    CodeMirror template by Jan T. Sott (https://github.com/idleberg/base16-codemirror)
    Original Base16 color scheme by Chris Kempson (https://github.com/chriskempson/base16)

*/

.cm-s-base16-dark.CodeMirror { background: #151515; color: #e0e0e0; }
.cm-s-base16-dark div.CodeMirror-selected { background: #303030; }
.cm-s-base16-dark .CodeMirror-line::selection, .cm-s-base16-dark .CodeMirror-line > span::selection, .cm-s-base16-dark .CodeMirror-line > span > span::selection { background: rgba(48, 48, 48, .99); }
.cm-s-base16-dark .CodeMirror-line::-moz-selection, .cm-s-base16-dark .CodeMirror-line > span::-moz-selection, .cm-s-base16-dark .CodeMirror-line > span > span::-moz-selection { background: rgba(48, 48, 48, .99); }
.cm-s-base16-dark .CodeMirror-gutters { background: #151515; border-right: 0px; }
.cm-s-base16-dark .CodeMirror-guttermarker { color: #ac4142; }
.cm-s-base16-dark .CodeMirror-guttermarker-subtle { color: #505050; }
.cm-s-base16-dark .CodeMirror-linenumber { color: #505050; }
.cm-s-base16-dark .CodeMirror-cursor { border-left: 1px solid #b0b0b0; }

.cm-s-base16-dark span.cm-comment { color: #8f5536; }
.cm-s-base16-dark span.cm-atom { color: #aa759f; }
.cm-s-base16-dark span.cm-number { color: #aa759f; }

.cm-s-base16-dark span.cm-property, .cm-s-base16-dark span.cm-attribute { color: #90a959; }
.cm-s-base16-dark span.cm-keyword { color: #ac4142; }
.cm-s-base16-dark span.cm-string { color: #f4bf75; }

.cm-s-base16-dark span.cm-variable { color: #90a959; }
.cm-s-base16-dark span.cm-variable-2 { color: #6a9fb5; }
.cm-s-base16-dark span.cm-def { color: #d28445; }
.cm-s-base16-dark span.cm-bracket { color: #e0e0e0; }
.cm-s-base16-dark span.cm-tag { color: #ac4142; }
.cm-s-base16-dark span.cm-link { color: #aa759f; }
.cm-s-base16-dark span.cm-error { background: #ac4142; color: #b0b0b0; }

.cm-s-base16-dark .CodeMirror-activeline-background { background: #202020; }
.cm-s-base16-dark .CodeMirror-matchingbracket { text-decoration: underline; color: white !important; }

/*

    Name:       dracula
    Author:     Michael Kaminsky (http://github.com/mkaminsky11)

    Original dracula color scheme by Zeno Rocha (https://github.com/zenorocha/dracula-theme)

*/


.cm-s-dracula.CodeMirror, .cm-s-dracula .CodeMirror-gutters {
  background-color: #282a36 !important;
  color: #f8f8f2 !important;
  border: none;
}
.cm-s-dracula .CodeMirror-gutters { color: #282a36; }
.cm-s-dracula .CodeMirror-cursor { border-left: solid thin #f8f8f0; }
.cm-s-dracula .CodeMirror-linenumber { color: #6D8A88; }
.cm-s-dracula .CodeMirror-selected { background: rgba(255, 255, 255, 0.10); }
.cm-s-dracula .CodeMirror-line::selection, .cm-s-dracula .CodeMirror-line > span::selection, .cm-s-dracula .CodeMirror-line > span > span::selection { background: rgba(255, 255, 255, 0.10); }
.cm-s-dracula .CodeMirror-line::-moz-selection, .cm-s-dracula .CodeMirror-line > span::-moz-selection, .cm-s-dracula .CodeMirror-line > span > span::-moz-selection { background: rgba(255, 255, 255, 0.10); }
.cm-s-dracula span.cm-comment { color: #6272a4; }
.cm-s-dracula span.cm-string, .cm-s-dracula span.cm-string-2 { color: #f1fa8c; }
.cm-s-dracula span.cm-number { color: #bd93f9; }
.cm-s-dracula span.cm-variable { color: #50fa7b; }
.cm-s-dracula span.cm-variable-2 { color: white; }
.cm-s-dracula span.cm-def { color: #50fa7b; }
.cm-s-dracula span.cm-operator { color: #ff79c6; }
.cm-s-dracula span.cm-keyword { color: #ff79c6; }
.cm-s-dracula span.cm-atom { color: #bd93f9; }
.cm-s-dracula span.cm-meta { color: #f8f8f2; }
.cm-s-dracula span.cm-tag { color: #ff79c6; }
.cm-s-dracula span.cm-attribute { color: #50fa7b; }
.cm-s-dracula span.cm-qualifier { color: #50fa7b; }
.cm-s-dracula span.cm-property { color: #66d9ef; }
.cm-s-dracula span.cm-builtin { color: #50fa7b; }
.cm-s-dracula span.cm-variable-3, .cm-s-dracula span.cm-type { color: #ffb86c; }

.cm-s-dracula .CodeMirror-activeline-background { background: rgba(255,255,255,0.1); }
.cm-s-dracula .CodeMirror-matchingbracket { text-decoration: underline; color: white !important; }

/*

    Name:       Hopscotch
    Author:     Jan T. Sott

    CodeMirror template by Jan T. Sott (https://github.com/idleberg/base16-codemirror)
    Original Base16 color scheme by Chris Kempson (https://github.com/chriskempson/base16)

*/

.cm-s-hopscotch.CodeMirror {background: #322931; color: #d5d3d5;}
.cm-s-hopscotch div.CodeMirror-selected {background: #433b42 !important;}
.cm-s-hopscotch .CodeMirror-gutters {background: #322931; border-right: 0px;}
.cm-s-hopscotch .CodeMirror-linenumber {color: #797379;}
.cm-s-hopscotch .CodeMirror-cursor {border-left: 1px solid #989498 !important;}

.cm-s-hopscotch span.cm-comment {color: #b33508;}
.cm-s-hopscotch span.cm-atom {color: #c85e7c;}
.cm-s-hopscotch span.cm-number {color: #c85e7c;}

.cm-s-hopscotch span.cm-property, .cm-s-hopscotch span.cm-attribute {color: #8fc13e;}
.cm-s-hopscotch span.cm-keyword {color: #dd464c;}
.cm-s-hopscotch span.cm-string {color: #fdcc59;}

.cm-s-hopscotch span.cm-variable {color: #8fc13e;}
.cm-s-hopscotch span.cm-variable-2 {color: #1290bf;}
.cm-s-hopscotch span.cm-def {color: #fd8b19;}
.cm-s-hopscotch span.cm-error {background: #dd464c; color: #989498;}
.cm-s-hopscotch span.cm-bracket {color: #d5d3d5;}
.cm-s-hopscotch span.cm-tag {color: #dd464c;}
.cm-s-hopscotch span.cm-link {color: #c85e7c;}

.cm-s-hopscotch .CodeMirror-matchingbracket { text-decoration: underline; color: white !important;}
.cm-s-hopscotch .CodeMirror-activeline-background { background: #302020; }

/****************************************************************/
/*   Based on mbonaci's Brackets mbo theme                      */
/*   https://github.com/mbonaci/global/blob/master/Mbo.tmTheme  */
/*   Create your own: http://tmtheme-editor.herokuapp.com       */
/****************************************************************/

.cm-s-mbo.CodeMirror { background: #2c2c2c; color: #ffffec; }
.cm-s-mbo div.CodeMirror-selected { background: #716C62; }
.cm-s-mbo .CodeMirror-line::selection, .cm-s-mbo .CodeMirror-line > span::selection, .cm-s-mbo .CodeMirror-line > span > span::selection { background: rgba(113, 108, 98, .99); }
.cm-s-mbo .CodeMirror-line::-moz-selection, .cm-s-mbo .CodeMirror-line > span::-moz-selection, .cm-s-mbo .CodeMirror-line > span > span::-moz-selection { background: rgba(113, 108, 98, .99); }
.cm-s-mbo .CodeMirror-gutters { background: #4e4e4e; border-right: 0px; }
.cm-s-mbo .CodeMirror-guttermarker { color: white; }
.cm-s-mbo .CodeMirror-guttermarker-subtle { color: grey; }
.cm-s-mbo .CodeMirror-linenumber { color: #dadada; }
.cm-s-mbo .CodeMirror-cursor { border-left: 1px solid #ffffec; }

.cm-s-mbo span.cm-comment { color: #95958a; }
.cm-s-mbo span.cm-atom { color: #00a8c6; }
.cm-s-mbo span.cm-number { color: #00a8c6; }

.cm-s-mbo span.cm-property, .cm-s-mbo span.cm-attribute { color: #9ddfe9; }
.cm-s-mbo span.cm-keyword { color: #ffb928; }
.cm-s-mbo span.cm-string { color: #ffcf6c; }
.cm-s-mbo span.cm-string.cm-property { color: #ffffec; }

.cm-s-mbo span.cm-variable { color: #ffffec; }
.cm-s-mbo span.cm-variable-2 { color: #00a8c6; }
.cm-s-mbo span.cm-def { color: #ffffec; }
.cm-s-mbo span.cm-bracket { color: #fffffc; font-weight: bold; }
.cm-s-mbo span.cm-tag { color: #9ddfe9; }
.cm-s-mbo span.cm-link { color: #f54b07; }
.cm-s-mbo span.cm-error { border-bottom: #636363; color: #ffffec; }
.cm-s-mbo span.cm-qualifier { color: #ffffec; }

.cm-s-mbo .CodeMirror-activeline-background { background: #494b41; }
.cm-s-mbo .CodeMirror-matchingbracket { color: #ffb928 !important; }
.cm-s-mbo .CodeMirror-matchingtag { background: rgba(255, 255, 255, .37); }

/*
  MDN-LIKE Theme - Mozilla
  Ported to CodeMirror by Peter Kroon <plakroon@gmail.com>
  Report bugs/issues here: https://github.com/codemirror/CodeMirror/issues
  GitHub: @peterkroon

  The mdn-like theme is inspired on the displayed code examples at: https://developer.mozilla.org/en-US/docs/Web/CSS/animation

*/
.cm-s-mdn-like.CodeMirror { color: #999; background-color: #fff; }
.cm-s-mdn-like div.CodeMirror-selected { background: #cfc; }
.cm-s-mdn-like .CodeMirror-line::selection, .cm-s-mdn-like .CodeMirror-line > span::selection, .cm-s-mdn-like .CodeMirror-line > span > span::selection { background: #cfc; }
.cm-s-mdn-like .CodeMirror-line::-moz-selection, .cm-s-mdn-like .CodeMirror-line > span::-moz-selection, .cm-s-mdn-like .CodeMirror-line > span > span::-moz-selection { background: #cfc; }

.cm-s-mdn-like .CodeMirror-gutters { background: #f8f8f8; border-left: 6px solid rgba(0,83,159,0.65); color: #333; }
.cm-s-mdn-like .CodeMirror-linenumber { color: #aaa; padding-left: 8px; }
.cm-s-mdn-like .CodeMirror-cursor { border-left: 2px solid #222; }

.cm-s-mdn-like .cm-keyword { color: #6262FF; }
.cm-s-mdn-like .cm-atom { color: #F90; }
.cm-s-mdn-like .cm-number { color:  #ca7841; }
.cm-s-mdn-like .cm-def { color: #8DA6CE; }
.cm-s-mdn-like span.cm-variable-2, .cm-s-mdn-like span.cm-tag { color: #690; }
.cm-s-mdn-like span.cm-variable-3, .cm-s-mdn-like span.cm-def, .cm-s-mdn-like span.cm-type { color: #07a; }

.cm-s-mdn-like .cm-variable { color: #07a; }
.cm-s-mdn-like .cm-property { color: #905; }
.cm-s-mdn-like .cm-qualifier { color: #690; }

.cm-s-mdn-like .cm-operator { color: #cda869; }
.cm-s-mdn-like .cm-comment { color:#777; font-weight:normal; }
.cm-s-mdn-like .cm-string { color:#07a; font-style:italic; }
.cm-s-mdn-like .cm-string-2 { color:#bd6b18; } /*?*/
.cm-s-mdn-like .cm-meta { color: #000; } /*?*/
.cm-s-mdn-like .cm-builtin { color: #9B7536; } /*?*/
.cm-s-mdn-like .cm-tag { color: #997643; }
.cm-s-mdn-like .cm-attribute { color: #d6bb6d; } /*?*/
.cm-s-mdn-like .cm-header { color: #FF6400; }
.cm-s-mdn-like .cm-hr { color: #AEAEAE; }
.cm-s-mdn-like .cm-link { color:#ad9361; font-style:italic; text-decoration:none; }
.cm-s-mdn-like .cm-error { border-bottom: 1px solid red; }

div.cm-s-mdn-like .CodeMirror-activeline-background { background: #efefff; }
div.cm-s-mdn-like span.CodeMirror-matchingbracket { outline:1px solid grey; color: inherit; }

.cm-s-mdn-like.CodeMirror { background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFcAAAAyCAYAAAAp8UeFAAAHvklEQVR42s2b63bcNgyEQZCSHCdt2vd/0tWF7I+Q6XgMXiTtuvU5Pl57ZQKkKHzEAOtF5KeIJBGJ8uvL599FRFREZhFx8DeXv8trn68RuGaC8TRfo3SNp9dlDDHedyLyTUTeRWStXKPZrjtpZxaRw5hPqozRs1N8/enzIiQRWcCgy4MUA0f+XWliDhyL8Lfyvx7ei/Ae3iQFHyw7U/59pQVIMEEPEz0G7XiwdRjzSfC3UTtz9vchIntxvry5iMgfIhJoEflOz2CQr3F5h/HfeFe+GTdLaKcu9L8LTeQb/R/7GgbsfKedyNdoHsN31uRPWrfZ5wsj/NzzRQHuToIdU3ahwnsKPxXCjJITuOsi7XLc7SG/v5GdALs7wf8JjTFiB5+QvTEfRyGOfX3Lrx8wxyQi3sNq46O7QahQiCsRFgqddjBouVEHOKDgXAQHD9gJCr5sMKkEdjwsarG/ww3BMHBU7OBjXnzdyY7SfCxf5/z6ATccrwlKuwC/jhznnPF4CgVzhhVf4xp2EixcBActO75iZ8/fM9zAs2OMzKdslgXWJ9XG8PQoOAMA5fGcsvORgv0doBXyHrCwfLJAOwo71QLNkb8n2Pl6EWiR7OCibtkPaz4Kc/0NNAze2gju3zOwekALDaCFPI5vjPFmgGY5AZqyGEvH1x7QfIb8YtxMnA/b+QQ0aQDAwc6JMFg8CbQZ4qoYEEHbRwNojuK3EHwd7VALSgq+MNDKzfT58T8qdpADrgW0GmgcAS1lhzztJmkAzcPNOQbsWEALBDSlMKUG0Eq4CLAQWvEVQ9WU57gZJwZtgPO3r9oBTQ9WO8TjqXINx8R0EYpiZEUWOF3FxkbJkgU9B2f41YBrIj5ZfsQa0M5kTgiAAqM3ShXLgu8XMqcrQBvJ0CL5pnTsfMB13oB8athpAq2XOQmcGmoACCLydx7nToa23ATaSIY2ichfOdPTGxlasXMLaL0MLZAOwAKIM+y8CmicobGdCcbbK9DzN+yYGVoNNI5iUKTMyYOjPse4A8SM1MmcXgU0toOq1yO/v8FOxlASyc7TgeYaAMBJHcY1CcCwGI/TK4AmDbDyKYBBtFUkRwto8gygiQEaByFgJ00BH2M8JWwQS1nafDXQCidWyOI8AcjDCSjCLk8ngObuAm3JAHAdubAmOaK06V8MNEsKPJOhobSprwQa6gD7DclRQdqcwL4zxqgBrQcabUiBLclRDKAlWp+etPkBaNMA0AKlrHwTdEByZAA4GM+SNluSY6wAzcMNewxmgig5Ks0nkrSpBvSaQHMdKTBAnLojOdYyGpQ254602ZILPdTD1hdlggdIm74jbTp8vDwF5ZYUeLWGJpWsh6XNyXgcYwVoJQTEhhTYkxzZjiU5npU2TaB979TQehlaAVq4kaGpiPwwwLkYUuBbQwocyQTv1tA0+1UFWoJF3iv1oq+qoSk8EQdJmwHkziIF7oOZk14EGitibAdjLYYK78H5vZOhtWpoI0ATGHs0Q8OMb4Ey+2bU2UYztCtA0wFAs7TplGLRVQCcqaFdGSPCeTI1QNIC52iWNzof6Uib7xjEp07mNNoUYmVosVItHrHzRlLgBn9LFyRHaQCtVUMbtTNhoXWiTOO9k/V8BdAc1Oq0ArSQs6/5SU0hckNy9NnXqQY0PGYo5dWJ7nINaN6o958FWin27aBaWRka1r5myvLOAm0j30eBJqCxHLReVclxhxOEN2JfDWjxBtAC7MIH1fVaGdoOp4qJYDgKtKPSFNID2gSnGldrCqkFZ+5UeQXQBIRrSwocbdZYQT/2LwRahBPBXoHrB8nxaGROST62DKUbQOMMzZIC9abkuELfQzQALWTnDNAm8KHWFOJgJ5+SHIvTPcmx1xQyZRhNL5Qci689aXMEaN/uNIWkEwDAvFpOZmgsBaaGnbs1NPa1Jm32gBZAIh1pCtG7TSH4aE0y1uVY4uqoFPisGlpP2rSA5qTecWn5agK6BzSpgAyD+wFaqhnYoSZ1Vwr8CmlTQbrcO3ZaX0NAEyMbYaAlyquFoLKK3SPby9CeVUPThrSJmkCAE0CrKUQadi4DrdSlWhmah0YL9z9vClH59YGbHx1J8VZTyAjQepJjmXwAKTDQI3omc3p1U4gDUf6RfcdYfrUp5ClAi2J3Ba6UOXGo+K+bQrjjssitG2SJzshaLwMtXgRagUNpYYoVkMSBLM+9GGiJZMvduG6DRZ4qc04DMPtQQxOjEtACmhO7K1AbNbQDEggZyJwscFpAGwENhoBeUwh3bWolhe8BTYVKxQEWrSUn/uhcM5KhvUu/+eQu0Lzhi+VrK0PrZZNDQKs9cpYUuFYgMVpD4/NxenJTiMCNqdUEUf1qZWjppLT5qSkkUZbCwkbZMSuVnu80hfSkzRbQeqCZSAh6huR4VtoM2gHAlLf72smuWgE+VV7XpE25Ab2WFDgyhnSuKbs4GuGzCjR+tIoUuMFg3kgcWKLTwRqanJQ2W00hAsenfaApRC42hbCvK1SlE0HtE9BGgneJO+ELamitD1YjjOYnNYVcraGhtKkW0EqVVeDx733I2NH581k1NNxNLG0i0IJ8/NjVaOZ0tYZ2Vtr0Xv7tPV3hkWp9EFkgS/J0vosngTaSoaG06WHi+xObQkaAdlbanP8B2+2l0f90LmUAAAAASUVORK5CYII=); }

/*

    Name:       seti
    Author:     Michael Kaminsky (http://github.com/mkaminsky11)

    Original seti color scheme by Jesse Weed (https://github.com/jesseweed/seti-syntax)

*/


.cm-s-seti.CodeMirror {
  background-color: #151718 !important;
  color: #CFD2D1 !important;
  border: none;
}
.cm-s-seti .CodeMirror-gutters {
  color: #404b53;
  background-color: #0E1112;
  border: none;
}
.cm-s-seti .CodeMirror-cursor { border-left: solid thin #f8f8f0; }
.cm-s-seti .CodeMirror-linenumber { color: #6D8A88; }
.cm-s-seti.CodeMirror-focused div.CodeMirror-selected { background: rgba(255, 255, 255, 0.10); }
.cm-s-seti .CodeMirror-line::selection, .cm-s-seti .CodeMirror-line > span::selection, .cm-s-seti .CodeMirror-line > span > span::selection { background: rgba(255, 255, 255, 0.10); }
.cm-s-seti .CodeMirror-line::-moz-selection, .cm-s-seti .CodeMirror-line > span::-moz-selection, .cm-s-seti .CodeMirror-line > span > span::-moz-selection { background: rgba(255, 255, 255, 0.10); }
.cm-s-seti span.cm-comment { color: #41535b; }
.cm-s-seti span.cm-string, .cm-s-seti span.cm-string-2 { color: #55b5db; }
.cm-s-seti span.cm-number { color: #cd3f45; }
.cm-s-seti span.cm-variable { color: #55b5db; }
.cm-s-seti span.cm-variable-2 { color: #a074c4; }
.cm-s-seti span.cm-def { color: #55b5db; }
.cm-s-seti span.cm-keyword { color: #ff79c6; }
.cm-s-seti span.cm-operator { color: #9fca56; }
.cm-s-seti span.cm-keyword { color: #e6cd69; }
.cm-s-seti span.cm-atom { color: #cd3f45; }
.cm-s-seti span.cm-meta { color: #55b5db; }
.cm-s-seti span.cm-tag { color: #55b5db; }
.cm-s-seti span.cm-attribute { color: #9fca56; }
.cm-s-seti span.cm-qualifier { color: #9fca56; }
.cm-s-seti span.cm-property { color: #a074c4; }
.cm-s-seti span.cm-variable-3, .cm-s-seti span.cm-type { color: #9fca56; }
.cm-s-seti span.cm-builtin { color: #9fca56; }
.cm-s-seti .CodeMirror-activeline-background { background: #101213; }
.cm-s-seti .CodeMirror-matchingbracket { text-decoration: underline; color: white !important; }

/*
Solarized theme for code-mirror
http://ethanschoonover.com/solarized
*/

/*
Solarized color palette
http://ethanschoonover.com/solarized/img/solarized-palette.png
*/

.solarized.base03 { color: #002b36; }
.solarized.base02 { color: #073642; }
.solarized.base01 { color: #586e75; }
.solarized.base00 { color: #657b83; }
.solarized.base0 { color: #839496; }
.solarized.base1 { color: #93a1a1; }
.solarized.base2 { color: #eee8d5; }
.solarized.base3  { color: #fdf6e3; }
.solarized.solar-yellow  { color: #b58900; }
.solarized.solar-orange  { color: #cb4b16; }
.solarized.solar-red { color: #dc322f; }
.solarized.solar-magenta { color: #d33682; }
.solarized.solar-violet  { color: #6c71c4; }
.solarized.solar-blue { color: #268bd2; }
.solarized.solar-cyan { color: #2aa198; }
.solarized.solar-green { color: #859900; }

/* Color scheme for code-mirror */

.cm-s-solarized {
  line-height: 1.45em;
  color-profile: sRGB;
  rendering-intent: auto;
}
.cm-s-solarized.cm-s-dark {
  color: #839496;
  background-color: #002b36;
  text-shadow: #002b36 0 1px;
}
.cm-s-solarized.cm-s-light {
  background-color: #fdf6e3;
  color: #657b83;
  text-shadow: #eee8d5 0 1px;
}

.cm-s-solarized .CodeMirror-widget {
  text-shadow: none;
}

.cm-s-solarized .cm-header { color: #586e75; }
.cm-s-solarized .cm-quote { color: #93a1a1; }

.cm-s-solarized .cm-keyword { color: #cb4b16; }
.cm-s-solarized .cm-atom { color: #d33682; }
.cm-s-solarized .cm-number { color: #d33682; }
.cm-s-solarized .cm-def { color: #2aa198; }

.cm-s-solarized .cm-variable { color: #839496; }
.cm-s-solarized .cm-variable-2 { color: #b58900; }
.cm-s-solarized .cm-variable-3, .cm-s-solarized .cm-type { color: #6c71c4; }

.cm-s-solarized .cm-property { color: #2aa198; }
.cm-s-solarized .cm-operator { color: #6c71c4; }

.cm-s-solarized .cm-comment { color: #586e75; font-style:italic; }

.cm-s-solarized .cm-string { color: #859900; }
.cm-s-solarized .cm-string-2 { color: #b58900; }

.cm-s-solarized .cm-meta { color: #859900; }
.cm-s-solarized .cm-qualifier { color: #b58900; }
.cm-s-solarized .cm-builtin { color: #d33682; }
.cm-s-solarized .cm-bracket { color: #cb4b16; }
.cm-s-solarized .CodeMirror-matchingbracket { color: #859900; }
.cm-s-solarized .CodeMirror-nonmatchingbracket { color: #dc322f; }
.cm-s-solarized .cm-tag { color: #93a1a1; }
.cm-s-solarized .cm-attribute { color: #2aa198; }
.cm-s-solarized .cm-hr {
  color: transparent;
  border-top: 1px solid #586e75;
  display: block;
}
.cm-s-solarized .cm-link { color: #93a1a1; cursor: pointer; }
.cm-s-solarized .cm-special { color: #6c71c4; }
.cm-s-solarized .cm-em {
  color: #999;
  text-decoration: underline;
  text-decoration-style: dotted;
}
.cm-s-solarized .cm-error,
.cm-s-solarized .cm-invalidchar {
  color: #586e75;
  border-bottom: 1px dotted #dc322f;
}

.cm-s-solarized.cm-s-dark div.CodeMirror-selected { background: #073642; }
.cm-s-solarized.cm-s-dark.CodeMirror ::selection { background: rgba(7, 54, 66, 0.99); }
.cm-s-solarized.cm-s-dark .CodeMirror-line::-moz-selection, .cm-s-dark .CodeMirror-line > span::-moz-selection, .cm-s-dark .CodeMirror-line > span > span::-moz-selection { background: rgba(7, 54, 66, 0.99); }

.cm-s-solarized.cm-s-light div.CodeMirror-selected { background: #eee8d5; }
.cm-s-solarized.cm-s-light .CodeMirror-line::selection, .cm-s-light .CodeMirror-line > span::selection, .cm-s-light .CodeMirror-line > span > span::selection { background: #eee8d5; }
.cm-s-solarized.cm-s-light .CodeMirror-line::-moz-selection, .cm-s-ligh .CodeMirror-line > span::-moz-selection, .cm-s-ligh .CodeMirror-line > span > span::-moz-selection { background: #eee8d5; }

/* Editor styling */



/* Little shadow on the view-port of the buffer view */
.cm-s-solarized.CodeMirror {
  -moz-box-shadow: inset 7px 0 12px -6px #000;
  -webkit-box-shadow: inset 7px 0 12px -6px #000;
  box-shadow: inset 7px 0 12px -6px #000;
}

/* Remove gutter border */
.cm-s-solarized .CodeMirror-gutters {
  border-right: 0;
}

/* Gutter colors and line number styling based of color scheme (dark / light) */

/* Dark */
.cm-s-solarized.cm-s-dark .CodeMirror-gutters {
  background-color: #073642;
}

.cm-s-solarized.cm-s-dark .CodeMirror-linenumber {
  color: #586e75;
  text-shadow: #021014 0 -1px;
}

/* Light */
.cm-s-solarized.cm-s-light .CodeMirror-gutters {
  background-color: #eee8d5;
}

.cm-s-solarized.cm-s-light .CodeMirror-linenumber {
  color: #839496;
}

/* Common */
.cm-s-solarized .CodeMirror-linenumber {
  padding: 0 5px;
}
.cm-s-solarized .CodeMirror-guttermarker-subtle { color: #586e75; }
.cm-s-solarized.cm-s-dark .CodeMirror-guttermarker { color: #ddd; }
.cm-s-solarized.cm-s-light .CodeMirror-guttermarker { color: #cb4b16; }

.cm-s-solarized .CodeMirror-gutter .CodeMirror-gutter-text {
  color: #586e75;
}

/* Cursor */
.cm-s-solarized .CodeMirror-cursor { border-left: 1px solid #819090; }

/* Fat cursor */
.cm-s-solarized.cm-s-light.cm-fat-cursor .CodeMirror-cursor { background: #77ee77; }
.cm-s-solarized.cm-s-light .cm-animate-fat-cursor { background-color: #77ee77; }
.cm-s-solarized.cm-s-dark.cm-fat-cursor .CodeMirror-cursor { background: #586e75; }
.cm-s-solarized.cm-s-dark .cm-animate-fat-cursor { background-color: #586e75; }

/* Active line */
.cm-s-solarized.cm-s-dark .CodeMirror-activeline-background {
  background: rgba(255, 255, 255, 0.06);
}
.cm-s-solarized.cm-s-light .CodeMirror-activeline-background {
  background: rgba(0, 0, 0, 0.06);
}

.cm-s-the-matrix.CodeMirror { background: #000000; color: #00FF00; }
.cm-s-the-matrix div.CodeMirror-selected { background: #2D2D2D; }
.cm-s-the-matrix .CodeMirror-line::selection, .cm-s-the-matrix .CodeMirror-line > span::selection, .cm-s-the-matrix .CodeMirror-line > span > span::selection { background: rgba(45, 45, 45, 0.99); }
.cm-s-the-matrix .CodeMirror-line::-moz-selection, .cm-s-the-matrix .CodeMirror-line > span::-moz-selection, .cm-s-the-matrix .CodeMirror-line > span > span::-moz-selection { background: rgba(45, 45, 45, 0.99); }
.cm-s-the-matrix .CodeMirror-gutters { background: #060; border-right: 2px solid #00FF00; }
.cm-s-the-matrix .CodeMirror-guttermarker { color: #0f0; }
.cm-s-the-matrix .CodeMirror-guttermarker-subtle { color: white; }
.cm-s-the-matrix .CodeMirror-linenumber { color: #FFFFFF; }
.cm-s-the-matrix .CodeMirror-cursor { border-left: 1px solid #00FF00; }

.cm-s-the-matrix span.cm-keyword { color: #008803; font-weight: bold; }
.cm-s-the-matrix span.cm-atom { color: #3FF; }
.cm-s-the-matrix span.cm-number { color: #FFB94F; }
.cm-s-the-matrix span.cm-def { color: #99C; }
.cm-s-the-matrix span.cm-variable { color: #F6C; }
.cm-s-the-matrix span.cm-variable-2 { color: #C6F; }
.cm-s-the-matrix span.cm-variable-3, .cm-s-the-matrix span.cm-type { color: #96F; }
.cm-s-the-matrix span.cm-property { color: #62FFA0; }
.cm-s-the-matrix span.cm-operator { color: #999; }
.cm-s-the-matrix span.cm-comment { color: #CCCCCC; }
.cm-s-the-matrix span.cm-string { color: #39C; }
.cm-s-the-matrix span.cm-meta { color: #C9F; }
.cm-s-the-matrix span.cm-qualifier { color: #FFF700; }
.cm-s-the-matrix span.cm-builtin { color: #30a; }
.cm-s-the-matrix span.cm-bracket { color: #cc7; }
.cm-s-the-matrix span.cm-tag { color: #FFBD40; }
.cm-s-the-matrix span.cm-attribute { color: #FFF700; }
.cm-s-the-matrix span.cm-error { color: #FF0000; }

.cm-s-the-matrix .CodeMirror-activeline-background { background: #040; }

/*
Copyright (C) 2011 by MarkLogic Corporation
Author: Mike Brevoort <mike@brevoort.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
*/
.cm-s-xq-light span.cm-keyword { line-height: 1em; font-weight: bold; color: #5A5CAD; }
.cm-s-xq-light span.cm-atom { color: #6C8CD5; }
.cm-s-xq-light span.cm-number { color: #164; }
.cm-s-xq-light span.cm-def { text-decoration:underline; }
.cm-s-xq-light span.cm-variable { color: black; }
.cm-s-xq-light span.cm-variable-2 { color:black; }
.cm-s-xq-light span.cm-variable-3, .cm-s-xq-light span.cm-type { color: black; }
.cm-s-xq-light span.cm-property {}
.cm-s-xq-light span.cm-operator {}
.cm-s-xq-light span.cm-comment { color: #0080FF; font-style: italic; }
.cm-s-xq-light span.cm-string { color: red; }
.cm-s-xq-light span.cm-meta { color: yellow; }
.cm-s-xq-light span.cm-qualifier { color: grey; }
.cm-s-xq-light span.cm-builtin { color: #7EA656; }
.cm-s-xq-light span.cm-bracket { color: #cc7; }
.cm-s-xq-light span.cm-tag { color: #3F7F7F; }
.cm-s-xq-light span.cm-attribute { color: #7F007F; }
.cm-s-xq-light span.cm-error { color: #f00; }

.cm-s-xq-light .CodeMirror-activeline-background { background: #e8f2ff; }
.cm-s-xq-light .CodeMirror-matchingbracket { outline:1px solid grey;color:black !important;background:yellow; }

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

.jp-CodeMirrorEditor-static {
  margin: var(--jp-code-padding);
}

.jp-CodeMirrorEditor,
.jp-CodeMirrorEditor-static {
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

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| RenderedText
|----------------------------------------------------------------------------*/

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
  line-height: normal;
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
}
.jp-RenderedText pre .ansi-red-bg {
  background-color: #e75c58;
}
.jp-RenderedText pre .ansi-green-bg {
  background-color: #00a250;
}
.jp-RenderedText pre .ansi-yellow-bg {
  background-color: #ddb62b;
}
.jp-RenderedText pre .ansi-blue-bg {
  background-color: #208ffb;
}
.jp-RenderedText pre .ansi-magenta-bg {
  background-color: #d160c4;
}
.jp-RenderedText pre .ansi-cyan-bg {
  background-color: #60c6c8;
}
.jp-RenderedText pre .ansi-white-bg {
  background-color: #c5c1b4;
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
}
.jp-RenderedText pre .ansi-red-intense-bg {
  background-color: #b22b31;
}
.jp-RenderedText pre .ansi-green-intense-bg {
  background-color: #007427;
}
.jp-RenderedText pre .ansi-yellow-intense-bg {
  background-color: #b27d12;
}
.jp-RenderedText pre .ansi-blue-intense-bg {
  background-color: #0065ca;
}
.jp-RenderedText pre .ansi-magenta-intense-bg {
  background-color: #a03196;
}
.jp-RenderedText pre .ansi-cyan-intense-bg {
  background-color: #258f8f;
}
.jp-RenderedText pre .ansi-white-intense-bg {
  background-color: #a1a6b2;
}

.jp-RenderedText pre .ansi-default-inverse-fg {
  color: var(--jp-ui-inverse-font-color0);
}
.jp-RenderedText pre .ansi-default-inverse-bg {
  background-color: var(--jp-inverse-layout-color0);
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

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

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

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

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
  margin: 4px 12px;
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
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  justify-content: space-evenly;
}

.jp-FileBrowser-toolbar.jp-Toolbar .jp-Toolbar-item {
  flex: 1;
}

.jp-FileBrowser-toolbar.jp-Toolbar .jp-ToolbarButtonComponent {
  width: 100%;
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

.jp-DirListing-item.jp-mod-selected {
  color: white;
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
  color: limegreen;
  content: '\25CF';
  font-size: 8px;
  position: absolute;
  left: -8px;
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

.jp-FileDialog.jp-mod-conflict input {
  color: red;
}

.jp-FileDialog .jp-new-name-title {
  margin-top: 12px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

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

.jp-OutputArea-executeResult.jp-RenderedText {
  padding-top: var(--jp-code-padding);
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

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

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
}

.jp-InputArea-editor {
  flex: 1 1 auto;
}

.jp-InputArea-editor {
  /* This is the non-active, default styling */
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0px;
  background: var(--jp-cell-editor-background);
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

/* Text output with the Out[] prompt needs a top padding to match the
 * alignment of the Out[] prompt itself.
 */
.jp-OutputArea-executeResult .jp-RenderedText.jp-OutputArea-output {
  padding-top: var(--jp-code-padding);
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

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

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

.jp-Notebook .jp-Cell {
  overflow: visible;
}

.jp-Notebook .jp-Cell .jp-InputPrompt {
  cursor: move;
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
  display: flex;
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
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensurePackage() in @jupyterlab/buildutils */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

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

  --jp-brand-color0: var(--md-blue-700);
  --jp-brand-color1: var(--md-blue-500);
  --jp-brand-color2: var(--md-blue-300);
  --jp-brand-color3: var(--md-blue-100);
  --jp-brand-color4: var(--md-blue-50);

  --jp-accent-color0: var(--md-green-700);
  --jp-accent-color1: var(--md-green-500);
  --jp-accent-color2: var(--md-green-300);
  --jp-accent-color3: var(--md-green-100);

  /* State colors (warn, error, success, info) */

  --jp-warn-color0: var(--md-orange-700);
  --jp-warn-color1: var(--md-orange-500);
  --jp-warn-color2: var(--md-orange-300);
  --jp-warn-color3: var(--md-orange-100);

  --jp-error-color0: var(--md-red-700);
  --jp-error-color1: var(--md-red-500);
  --jp-error-color2: var(--md-red-300);
  --jp-error-color3: var(--md-red-100);

  --jp-success-color0: var(--md-green-700);
  --jp-success-color1: var(--md-green-500);
  --jp-success-color2: var(--md-green-300);
  --jp-success-color3: var(--md-green-100);

  --jp-info-color0: var(--md-cyan-700);
  --jp-info-color1: var(--md-cyan-500);
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
  --jp-cell-prompt-font-family: 'Source Code Pro', monospace;
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

  --jp-sidebar-min-width: 180px;

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

@media print {
  body {
    margin: 0;
  }
}
</style>



<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/latest.js?config=TeX-MML-AM_CHTML-full,Safe"> </script>
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
                },
                "HTML-CSS": {
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

<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><h1 align="center">The Value of a Weapon in Valorant</h1></p>
<h3 align="center">David Baek</h3>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h2 align="center">Introduction</h2>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><a href="https://playvalorant.com/en-us/">Valorant</a> is a 5v5 character-based tactical first-person shooter video game developed by Riot Games. The game was released in mid-2020, and has since become extremely popular, <a href="https://streamscharts.com/games/valorant">having an average of 100,000 concurrent viewers on Twitch.tv</a> and a <a href="https://valorantesports.com/">thriving esports community</a>. In Valorant, there are two teams of five players, who each have one life per round. One team is the "attacker," who is awarded a point if they either plant their bomb at a designated site and defend it until it explodes, or eliminate the opposing the team. The other team is the "defender," who is is awarded a point if they either eliminate the opposing team, or defuse the planted bomb before it explodes. The first team to 13 points, or leads by 2 points in overtime, wins the game; however, each team swaps sides (attackers become defenders and vice-versa) after 12 rounds, or each round in overtime. There are a total of <a href="https://playvalorant.com/en-us/maps/">7 maps</a> to play on, <a href="https://playvalorant.com/en-us/agents/">17 "agents"</a> with unique abilities and playstyles, and <a href="https://playvalorant.com/en-us/arsenal/">18 weapons</a> to use.</p>
<p>On July 8th, 2020 (one month after its release), Riot Games <a href="https://www.riotgames.com/en/DevRel/valorant-api-launch">announced</a> the launch of the Valorant API. This API allowed for players to view the <a href="https://developer.riotgames.com/apis#val-match-v1/GET_getMatch">precise results of specific games</a> they had previously played, along with a way to request recent games and information about API values; however, access to this API was, and still is, limited to those with approved products (more information can be found <a href="https://developer.riotgames.com/docs/portal#_getting-started">here</a>)*.</p>
<p>*Note: you must register for a "PRODUCTION API KEY" to get valorant access. This requires more steps than a "PERSONAL API KEY," which cannot gain access to Valorant's API</p>
<p>With access to Valorant's API, this tutorial explores some large-scale match data, and looks to provide an answer to a common question that beginner players have: "What weapon should I buy this round?" Valorant has an extremely laissez-faire approach to player assistance in-game, only telling a player what they can and cannot buy. This tutorial aims to use big data to create a model that can recommend a player a weapon, given their agent, map, money, and current round. Additionally, this tutorial will highlight the core aspects of the data science pipeline.</p>
<p>Overall, I hope that readers will be able to gain some insights into data science and Valorant from this tutorial, and have some fun at the same time.</p>

</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h4 align="center">Valorant's in-game shop interface</h4>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><img src="shop.png" width=711 height=400 align="center"/></p>

</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h2 align="center">Obtaining and Preparing the Data</h2>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[1]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Necessairy Imports for the entire project</span>
<span class="kn">import</span> <span class="nn">json</span>
<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sns</span>
<span class="kn">from</span> <span class="nn">sklearn.preprocessing</span> <span class="kn">import</span> <span class="n">LabelEncoder</span>
<span class="kn">from</span> <span class="nn">sklearn</span> <span class="kn">import</span> <span class="n">model_selection</span>
<span class="kn">from</span> <span class="nn">sklearn</span> <span class="kn">import</span> <span class="n">linear_model</span>
<span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="kn">import</span> <span class="n">accuracy_score</span>
<span class="kn">import</span> <span class="nn">statsmodels.api</span> <span class="k">as</span> <span class="nn">sm</span>
<span class="kn">import</span> <span class="nn">statsmodels.formula.api</span> <span class="k">as</span> <span class="nn">smf</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="n">pd</span><span class="o">.</span><span class="n">options</span><span class="o">.</span><span class="n">mode</span><span class="o">.</span><span class="n">chained_assignment</span> <span class="o">=</span> <span class="kc">None</span>
<span class="kn">import</span> <span class="nn">time</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Once an API key is acquired from Riot Games, again see <a href="https://developer.riotgames.com/docs/portal#_getting-started">here</a> for information on how to obtain one, data for matches must be acquired. The first step to acquiring data is to obtain the match id of recently completed games. It is impossible to find games otherwise, and obtaining recent games yields excellent results (I obtained over 1000 games from my first request).</p>
<p>The data from an API request can be managed manually; however, <a href="https://github.com/pseudonym117/Riot-Watcher">riotwatcher</a> manages the conversions from JSON, and makes the code much more readable compared to using HTTP requests.</p>
<p>Competitive queue was chosen, because that queue is where players are the most serious, and will thus yield the most quality results to build a model off of.</p>
<p>The specific API used in the following code can be found <a href="https://developer.riotgames.com/apis#val-match-v1/GET_getRecent">here</a>.</p>
<p>NOTE: the following code, and any code with an API request will not work unless you have a valid input key. I am not allowed to publicly show my API key, but the following code works with a key that has access to Valorant's API.</p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#If you do not have riotwatcher installed, run the below command</span>
<span class="c1">#!pip3 install riotwatcher</span>

<span class="c1">#Only after you install riotwatcher will the following work</span>
<span class="kn">from</span> <span class="nn">riotwatcher</span> <span class="kn">import</span> <span class="n">ValWatcher</span><span class="p">,</span> <span class="n">ApiError</span>

<span class="c1">#I cannot publicly show my API key, thus all requests will not work, unless the reader has their own key</span>
<span class="n">api_key</span> <span class="o">=</span> <span class="s1">&#39;insert key&#39;</span>
<span class="n">watcher</span> <span class="o">=</span> <span class="n">ValWatcher</span><span class="p">(</span><span class="n">api_key</span><span class="p">)</span>
<span class="n">my_region</span> <span class="o">=</span> <span class="s1">&#39;NA&#39;</span> <span class="c1">#Can change to other regions</span>

<span class="n">recent_match_ids_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">()</span>

<span class="c1">#Can change to whatever values, be mindful of API rates</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">6</span><span class="p">):</span>
    <span class="c1">#This returns a list of all recent match IDs for competitive that have ended in the past 10 minutes</span>
    <span class="n">recent_match_ids</span> <span class="o">=</span> <span class="n">watcher</span><span class="o">.</span><span class="n">match</span><span class="o">.</span><span class="n">recent_matches</span><span class="p">(</span><span class="n">my_region</span><span class="p">,</span><span class="s2">&quot;competitive&quot;</span><span class="p">)</span>
    <span class="n">recent_match_ids_df</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">recent_match_ids</span><span class="p">)</span>
    <span class="c1">#There is no point in repeating this loop instantly, removing the comment will wait till the API will send new games</span>
    <span class="c1">#sleep(600)</span>

<span class="c1">#Highly recommended to back-up this data to protect it against a kernel restart or failure.</span>
<span class="n">recent_match_ids_df</span><span class="o">.</span><span class="n">to_csv</span><span class="p">(</span><span class="s1">&#39;matches_date.csv&#39;</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>After obtaining match ids, we can use them to get specific map data, and explore its data. But first, here is a look at what match ids look like. The following table can be found <a href="https://dbaek25.github.io/320-final-tutorial/matchs_1218.csv">here (This is a download link)</a>.</p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[2]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#This is data that has already been collected, and will be the basis for the rest of this tutorial</span>
<span class="n">all_match_ids</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;matchs_1218.csv&#39;</span><span class="p">)</span>
<span class="n">all_match_ids</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="s1">&#39;Unnamed: 0&#39;</span><span class="p">,</span> <span class="n">axis</span> <span class="o">=</span> <span class="mi">1</span><span class="p">,</span> <span class="n">inplace</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>
<span class="n">all_match_ids</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[2]:</div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>0</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>d28031d6-dce8-4d50-aa6f-225420f1e96b</td>
    </tr>
    <tr>
      <th>1</th>
      <td>f03a68e5-f3a4-4472-a1c1-6d9406fb02de</td>
    </tr>
    <tr>
      <th>2</th>
      <td>53b9076e-a1f9-48d1-aeca-3be0e3a0e9fe</td>
    </tr>
    <tr>
      <th>3</th>
      <td>c5ddc8d7-94b7-4178-8a5f-711733d01abc</td>
    </tr>
    <tr>
      <th>4</th>
      <td>e03e42c4-a4d7-40ea-b7fe-1df681cbe2eb</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Code to obtain the data from the above dataframe, requires an authorized API key</span>
<span class="n">sample_match</span> <span class="o">=</span> <span class="n">watcher</span><span class="o">.</span><span class="n">match</span><span class="o">.</span><span class="n">by_id</span><span class="p">(</span><span class="n">my_region</span><span class="p">,</span><span class="n">all_match_ids</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">0</span><span class="p">)[</span><span class="s1">&#39;0&#39;</span><span class="p">])</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[3]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Sample data for a specific match from the API that has already been obtained, the total output is too long to show</span>
<span class="n">f</span> <span class="o">=</span> <span class="nb">open</span><span class="p">(</span><span class="s1">&#39;example_match.json&#39;</span><span class="p">)</span>
<span class="n">sample_match</span> <span class="o">=</span> <span class="n">json</span><span class="o">.</span><span class="n">load</span><span class="p">(</span><span class="n">f</span><span class="p">)</span>
<span class="n">f</span><span class="o">.</span><span class="n">close</span>
<span class="nb">print</span><span class="p">(</span><span class="n">sample_match</span><span class="o">.</span><span class="n">keys</span><span class="p">())</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>dict_keys([&#39;matchInfo&#39;, &#39;players&#39;, &#39;coaches&#39;, &#39;teams&#39;, &#39;roundResults&#39;])
</pre>
</div>
</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>To see the full output of that match, click <a href="https://dbaek25.github.io/320-final-tutorial/example_match.json">here</a> (It is not very readable). As you can see, most of the data is useless for trying to recommend a weapon. This means that the data must be modified before it can be used.</p>

</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h3 align="center">Creating dictionaries to decyper API output</h3>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>A major issue with the data for each match is that certain values are ids that make it difficult to easily understand what they represent. Here are two examples:</p>
<p>The map "Bind" is labeled as '/Game/Maps/Bonsai/Bonsai'</p>
<p>The character KAY/O is labeled as '601dbbe7-43ce-be57-2a40-4abd24953621'</p>
<p>Thus, three dictionaries were made to easily "translate" ids to their better known aliases.</p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#obtaining the file that contains all IDS and names for them, requires an authorized API key</span>
<span class="n">content</span> <span class="o">=</span> <span class="n">watcher</span><span class="o">.</span><span class="n">content</span><span class="o">.</span><span class="n">contents</span><span class="p">(</span><span class="n">my_region</span><span class="p">,</span><span class="s2">&quot;en-US&quot;</span><span class="p">)</span>

<span class="c1">#Creating a dictionary for character names</span>
<span class="n">char_ref</span> <span class="o">=</span> <span class="p">{}</span>
<span class="k">for</span> <span class="n">element</span> <span class="ow">in</span> <span class="n">content</span><span class="p">[</span><span class="s1">&#39;characters&#39;</span><span class="p">]:</span>
    <span class="n">char_ref</span><span class="p">[</span><span class="n">element</span><span class="p">[</span><span class="s1">&#39;id&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">lower</span><span class="p">()]</span> <span class="o">=</span> <span class="n">element</span><span class="p">[</span><span class="s1">&#39;name&#39;</span><span class="p">]</span>

<span class="c1">#Creating a dictionary for map names</span>
<span class="n">map_ref</span> <span class="o">=</span> <span class="p">{}</span>
<span class="k">for</span> <span class="n">element</span> <span class="ow">in</span> <span class="n">content</span><span class="p">[</span><span class="s2">&quot;maps&quot;</span><span class="p">][</span><span class="mi">1</span><span class="p">:]:</span>
    <span class="n">map_ref</span><span class="p">[</span><span class="n">element</span><span class="p">[</span><span class="s1">&#39;assetPath&#39;</span><span class="p">]]</span> <span class="o">=</span> <span class="n">element</span><span class="p">[</span><span class="s1">&#39;name&#39;</span><span class="p">]</span>

<span class="c1">#Creating a dictionary for weapon names</span>
<span class="n">weap_ref</span> <span class="o">=</span> <span class="p">{}</span>
<span class="k">for</span> <span class="n">element</span> <span class="ow">in</span> <span class="n">content</span><span class="p">[</span><span class="s2">&quot;equips&quot;</span><span class="p">]:</span>
    <span class="n">weap_ref</span><span class="p">[</span><span class="n">element</span><span class="p">[</span><span class="s1">&#39;id&#39;</span><span class="p">]]</span> <span class="o">=</span> <span class="n">element</span><span class="p">[</span><span class="s1">&#39;name&#39;</span><span class="p">]</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h3 align="center">Obtaining data for specific rounds</h3>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>With these dictionaries, we can now streamline the collection and modification of user data. Of all the data stored in each game and round, only the player's agent, map, weapon used, information on if they won the round, the amount of kills they had that round, the amount of money they had that round, their score for the round, the round number, and the match id were kept. Everything included could be used to create a model or modify it in the future to achieve better results, except for match_id, which was used simply as an identifier.</p>
<p>Now knowing what specific data we want, we can iterate through each game and round to harvest the exact data we need and create two more dictionaries to quickly check a player's team and agent, modify the data with our dictionaries to become readable, store it in a dataframe, and throw away the remaining data to save space. It should be noted that saving the dataframe during each iteration and sleeping to maintain API rates are extremly inefficient, but they were the safest method I could think of to keep the data flowing, and to protect against kernel failures (which happened in my testing notebook).</p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[&nbsp;]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Creating a dataframe with for desired values</span>
<span class="n">round_collector</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">[</span><span class="s1">&#39;agent&#39;</span><span class="p">,</span> <span class="s1">&#39;map&#39;</span><span class="p">,</span><span class="s1">&#39;weapon&#39;</span><span class="p">,</span><span class="s1">&#39;roundwon&#39;</span><span class="p">,</span><span class="s1">&#39;kills&#39;</span><span class="p">,</span><span class="s1">&#39;money&#39;</span><span class="p">,</span><span class="s1">&#39;score&#39;</span><span class="p">,</span><span class="s1">&#39;round_num&#39;</span><span class="p">,</span><span class="s1">&#39;match_id&#39;</span><span class="p">])</span>

<span class="c1">#loop to collect each match&#39;s data, requires an authorized API key</span>
<span class="k">for</span> <span class="n">counter</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">all_match_ids</span><span class="p">[</span><span class="s1">&#39;0&#39;</span><span class="p">])):</span>
    <span class="c1">#These counters are needed to ensure that API rates are being maintained</span>
    <span class="k">if</span><span class="p">(</span><span class="n">counter</span><span class="o">%</span><span class="k">100</span>==0 and counter!=0):
        <span class="n">time</span><span class="o">.</span><span class="n">sleep</span><span class="p">(</span><span class="mi">120</span><span class="p">)</span>
    <span class="k">elif</span><span class="p">(</span><span class="n">counter</span><span class="o">%</span><span class="k">20</span>==0 and counter!=0):
        <span class="n">time</span><span class="o">.</span><span class="n">sleep</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span> 
    <span class="n">curr_match</span> <span class="o">=</span> <span class="n">watcher</span><span class="o">.</span><span class="n">match</span><span class="o">.</span><span class="n">by_id</span><span class="p">(</span><span class="n">my_region</span><span class="p">,</span><span class="n">all_match_ids</span><span class="p">[</span><span class="s1">&#39;0&#39;</span><span class="p">][</span><span class="n">counter</span><span class="p">])</span>
    <span class="c1">#Creating two dictionaries for each player&#39;s team and character</span>
    <span class="n">player_team</span> <span class="o">=</span> <span class="p">{}</span>
    <span class="k">for</span> <span class="n">element</span> <span class="ow">in</span> <span class="n">curr_match</span><span class="p">[</span><span class="s1">&#39;players&#39;</span><span class="p">]:</span>
        <span class="n">player_team</span><span class="p">[</span><span class="n">element</span><span class="p">[</span><span class="s1">&#39;puuid&#39;</span><span class="p">]]</span> <span class="o">=</span> <span class="n">element</span><span class="p">[</span><span class="s1">&#39;teamId&#39;</span><span class="p">]</span>
    <span class="n">map_played</span> <span class="o">=</span> <span class="n">map_ref</span><span class="p">[</span><span class="n">curr_match</span><span class="p">[</span><span class="s1">&#39;matchInfo&#39;</span><span class="p">][</span><span class="s1">&#39;mapId&#39;</span><span class="p">]]</span>
    <span class="n">player_char</span> <span class="o">=</span> <span class="p">{}</span>
    <span class="k">for</span> <span class="n">element</span> <span class="ow">in</span> <span class="n">curr_match</span><span class="p">[</span><span class="s1">&#39;players&#39;</span><span class="p">]:</span>
        <span class="n">player_char</span><span class="p">[</span><span class="n">element</span><span class="p">[</span><span class="s1">&#39;puuid&#39;</span><span class="p">]]</span> <span class="o">=</span> <span class="n">char_ref</span><span class="p">[</span><span class="n">element</span><span class="p">[</span><span class="s1">&#39;characterId&#39;</span><span class="p">]]</span>
    <span class="n">match_id</span> <span class="o">=</span> <span class="n">curr_match</span><span class="p">[</span><span class="s1">&#39;matchInfo&#39;</span><span class="p">][</span><span class="s1">&#39;matchId&#39;</span><span class="p">]</span>
    <span class="c1">#loops through all the rounds in the game</span>
    <span class="k">for</span> <span class="n">curr_round</span> <span class="ow">in</span> <span class="n">curr_match</span><span class="p">[</span><span class="s1">&#39;roundResults&#39;</span><span class="p">]:</span>
        <span class="c1">#loops through every player in the round</span>
        <span class="k">for</span> <span class="n">player</span> <span class="ow">in</span> <span class="n">curr_round</span><span class="p">[</span><span class="s1">&#39;playerStats&#39;</span><span class="p">]:</span>
            <span class="c1">#Player is AFK they are not counted, and they do not have a weapon</span>
            <span class="k">if</span><span class="p">(</span><span class="n">player</span><span class="p">[</span><span class="s1">&#39;economy&#39;</span><span class="p">][</span><span class="s1">&#39;weapon&#39;</span><span class="p">]</span><span class="o">!=</span><span class="s1">&#39;&#39;</span><span class="p">):</span>
                <span class="c1">#obtaining necessairy data</span>
                <span class="n">did_win</span> <span class="o">=</span> <span class="n">player_team</span><span class="p">[</span><span class="n">player</span><span class="p">[</span><span class="s1">&#39;puuid&#39;</span><span class="p">]]</span> <span class="o">==</span> <span class="n">curr_round</span><span class="p">[</span><span class="s1">&#39;winningTeam&#39;</span><span class="p">]</span>
                <span class="n">curr_agent</span> <span class="o">=</span> <span class="n">player_char</span><span class="p">[</span><span class="n">player</span><span class="p">[</span><span class="s1">&#39;puuid&#39;</span><span class="p">]]</span>
                <span class="n">round_weapon</span> <span class="o">=</span> <span class="n">weap_ref</span><span class="p">[</span><span class="n">player</span><span class="p">[</span><span class="s1">&#39;economy&#39;</span><span class="p">][</span><span class="s1">&#39;weapon&#39;</span><span class="p">]]</span>
                <span class="n">round_kills</span> <span class="o">=</span> <span class="nb">len</span><span class="p">(</span><span class="n">player</span><span class="p">[</span><span class="s1">&#39;kills&#39;</span><span class="p">])</span>
                <span class="n">round_money</span> <span class="o">=</span> <span class="n">player</span><span class="p">[</span><span class="s1">&#39;economy&#39;</span><span class="p">][</span><span class="s1">&#39;remaining&#39;</span><span class="p">]</span><span class="o">+</span><span class="n">player</span><span class="p">[</span><span class="s1">&#39;economy&#39;</span><span class="p">][</span><span class="s1">&#39;spent&#39;</span><span class="p">]</span>
                <span class="n">round_score</span> <span class="o">=</span> <span class="n">player</span><span class="p">[</span><span class="s1">&#39;score&#39;</span><span class="p">]</span>
                <span class="n">round_num</span> <span class="o">=</span> <span class="n">curr_round</span><span class="p">[</span><span class="s1">&#39;roundNum&#39;</span><span class="p">]</span>
                <span class="n">round_collector</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="nb">len</span><span class="p">(</span><span class="n">results</span><span class="o">.</span><span class="n">index</span><span class="p">)]</span> <span class="o">=</span> <span class="p">[</span><span class="n">curr_agent</span><span class="p">,</span><span class="n">map_played</span><span class="p">,</span><span class="n">round_weapon</span><span class="p">,</span><span class="n">did_win</span><span class="p">,</span><span class="n">round_kills</span><span class="p">,</span><span class="n">round_money</span><span class="p">,</span><span class="n">round_score</span><span class="p">,</span><span class="n">round_num</span><span class="p">,</span><span class="n">match_id</span><span class="p">]</span>
    <span class="n">round_collector</span><span class="o">.</span><span class="n">to_csv</span><span class="p">(</span><span class="s1">&#39;round_collector.csv&#39;</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Once the loop finishes running, we have our data for each round! We can now do exploratory analysis and create a model from this data. The following table was premade for this notebook, but it was created using the exact code above. It can be found <a href="https://dbaek25.github.io/320-final-tutorial/round_data.csv">here (This is a download link)</a></p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[4]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#This is data that has already been collected, and will be the basis for the rest of this tutorial</span>
<span class="n">round_data</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;round_data.csv&#39;</span><span class="p">)</span>
<span class="n">round_data</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="s1">&#39;Unnamed: 0&#39;</span><span class="p">,</span> <span class="n">axis</span> <span class="o">=</span> <span class="mi">1</span><span class="p">,</span> <span class="n">inplace</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>
<span class="n">round_data</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[4]:</div>



<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>agent</th>
      <th>map</th>
      <th>weapon</th>
      <th>roundwon</th>
      <th>kills</th>
      <th>money</th>
      <th>score</th>
      <th>round_num</th>
      <th>match_id</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Killjoy</td>
      <td>Split</td>
      <td>Classic</td>
      <td>True</td>
      <td>1</td>
      <td>800</td>
      <td>374</td>
      <td>0</td>
      <td>d28031d6-dce8-4d50-aa6f-225420f1e96b</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Yoru</td>
      <td>Split</td>
      <td>Ghost</td>
      <td>False</td>
      <td>1</td>
      <td>800</td>
      <td>298</td>
      <td>0</td>
      <td>d28031d6-dce8-4d50-aa6f-225420f1e96b</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Raze</td>
      <td>Split</td>
      <td>Classic</td>
      <td>False</td>
      <td>1</td>
      <td>800</td>
      <td>178</td>
      <td>0</td>
      <td>d28031d6-dce8-4d50-aa6f-225420f1e96b</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Sage</td>
      <td>Split</td>
      <td>Ghost</td>
      <td>True</td>
      <td>2</td>
      <td>800</td>
      <td>318</td>
      <td>0</td>
      <td>d28031d6-dce8-4d50-aa6f-225420f1e96b</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Jett</td>
      <td>Split</td>
      <td>Classic</td>
      <td>True</td>
      <td>2</td>
      <td>800</td>
      <td>456</td>
      <td>0</td>
      <td>d28031d6-dce8-4d50-aa6f-225420f1e96b</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>188187</th>
      <td>Raze</td>
      <td>Ascent</td>
      <td>Vandal</td>
      <td>False</td>
      <td>0</td>
      <td>5800</td>
      <td>0</td>
      <td>23</td>
      <td>be8fb442-37c7-4a2d-b0e9-1ec83b949a68</td>
    </tr>
    <tr>
      <th>188188</th>
      <td>Sage</td>
      <td>Ascent</td>
      <td>Odin</td>
      <td>True</td>
      <td>1</td>
      <td>7250</td>
      <td>135</td>
      <td>23</td>
      <td>be8fb442-37c7-4a2d-b0e9-1ec83b949a68</td>
    </tr>
    <tr>
      <th>188189</th>
      <td>Killjoy</td>
      <td>Ascent</td>
      <td>Phantom</td>
      <td>False</td>
      <td>0</td>
      <td>900</td>
      <td>0</td>
      <td>23</td>
      <td>be8fb442-37c7-4a2d-b0e9-1ec83b949a68</td>
    </tr>
    <tr>
      <th>188190</th>
      <td>Sage</td>
      <td>Ascent</td>
      <td>Vandal</td>
      <td>False</td>
      <td>2</td>
      <td>5950</td>
      <td>579</td>
      <td>23</td>
      <td>be8fb442-37c7-4a2d-b0e9-1ec83b949a68</td>
    </tr>
    <tr>
      <th>188191</th>
      <td>Jett</td>
      <td>Ascent</td>
      <td>Phantom</td>
      <td>False</td>
      <td>1</td>
      <td>3900</td>
      <td>280</td>
      <td>23</td>
      <td>be8fb442-37c7-4a2d-b0e9-1ec83b949a68</td>
    </tr>
  </tbody>
</table>
<p>188192 rows × 9 columns</p>
</div>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h4 align="center">The Loading Screen for the Map Icebox</h4>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><img src="ValorantWallpaper_Icebox.jpg" width=711 height=400 align="center"/></p>

</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h2 align="center">Exploring the Data</h2>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>This section mainly provides visualizations of the data that we created in the previous section. Any modifications to the dataset are done locally to maintain the integrity of the dataset for the modeling portion of this tutorial.</p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[5]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#getting each weapon and putting it into a new dataframe</span>
<span class="n">weapons</span> <span class="o">=</span> <span class="n">round_data</span><span class="p">[</span><span class="s1">&#39;weapon&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">unique</span><span class="p">()</span>
<span class="n">weapon_table</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">weapons</span><span class="p">,</span> <span class="n">columns</span> <span class="o">=</span><span class="p">[</span><span class="s2">&quot;weapon&quot;</span><span class="p">])</span>

<span class="c1">#finding the number of times that each weapon was used in a round</span>
<span class="n">weapon_table</span><span class="p">[</span><span class="s1">&#39;occurances&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="mi">0</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">weapon_table</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="n">weapon_table</span><span class="o">.</span><span class="n">at</span><span class="p">[</span><span class="n">index</span><span class="p">,</span> <span class="s2">&quot;occurances&quot;</span><span class="p">]</span> <span class="o">=</span> <span class="p">(</span><span class="n">round_data</span><span class="o">.</span><span class="n">weapon</span><span class="o">.</span><span class="n">values</span> <span class="o">==</span> <span class="n">row</span><span class="p">[</span><span class="s2">&quot;weapon&quot;</span><span class="p">])</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span>
<span class="n">weapon_table</span> <span class="o">=</span> <span class="n">weapon_table</span><span class="o">.</span><span class="n">sort_values</span><span class="p">(</span><span class="n">by</span><span class="o">=</span><span class="s1">&#39;occurances&#39;</span><span class="p">,</span> <span class="n">ascending</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span>
<span class="n">weapon_table</span><span class="o">.</span><span class="n">reset_index</span><span class="p">(</span><span class="n">inplace</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span> <span class="n">drop</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>

<span class="c1">#plotting the results in a bar plot</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">weapon_table</span><span class="o">.</span><span class="n">plot</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">y</span> <span class="o">=</span> <span class="s2">&quot;occurances&quot;</span><span class="p">,</span> <span class="n">x</span> <span class="o">=</span> <span class="s2">&quot;weapon&quot;</span><span class="p">,</span> <span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">15</span><span class="p">,</span><span class="mi">7</span><span class="p">),</span> <span class="n">legend</span> <span class="o">=</span> <span class="kc">None</span><span class="p">,</span>
                           <span class="n">title</span> <span class="o">=</span> <span class="s2">&quot;The Number of Times Each Weapon was Used Acorss all Rounds Studied&quot;</span><span class="p">,</span>
                           <span class="n">xlabel</span> <span class="o">=</span> <span class="s2">&quot;Weapon&quot;</span><span class="p">,</span> <span class="n">ylabel</span> <span class="o">=</span> <span class="s2">&quot;Times Used&quot;</span><span class="p">)</span>

<span class="c1">#putting the raw value above each bar</span>
<span class="k">for</span> <span class="n">p</span> <span class="ow">in</span> <span class="n">ax</span><span class="o">.</span><span class="n">patches</span><span class="p">:</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">annotate</span><span class="p">(</span><span class="nb">str</span><span class="p">(</span><span class="n">p</span><span class="o">.</span><span class="n">get_height</span><span class="p">()),</span> <span class="p">(</span><span class="n">p</span><span class="o">.</span><span class="n">get_x</span><span class="p">()</span> <span class="o">*</span> <span class="mf">1.005</span><span class="p">,</span> <span class="n">p</span><span class="o">.</span><span class="n">get_height</span><span class="p">()</span> <span class="o">*</span> <span class="mf">1.01</span><span class="p">))</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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ux3IHqzlXGBBaD53KXBOAbvLHqUw/u8Ad58D3ElUI7KMqD/gR3ExPEf0XD8DrCWq5aq9w94L52Oi99Nn2U1Aw+u3Alju7vNC2VSifogPEL2W3xIGv9lZvEFB75OBRDVJS4CXgJvcfdJuHE8Vtie2c4gG3IifquM/RM3mFof1n5JToV5Dj/rVnkBUY7acqNb0V+CycJdywNXhuH4maub6f2Hbl4jeN2PD48wi6rOLu68E+hMlPKuInrfcz2e204iaQP8n1OL95O4/EfW/LE80WNFdRLWgbxElLY8BVcLzf1KIcRVRM9GTwuPnJd/jIeqX95lF84xOAK5w9/l57GNnz/0uc/eZRBcIrnX3yUTfdS8QfQfuT87+zxcB1xIdd3ui901hnU3UnPVnogGX/hO3bh+i77k1RP0i3yPvi1prwz4+s6gP5adE74Grw/p3iKbw+cnMsl+Pu4HNRJ+x0cRdRCnKe6YQ32GXEzWn/YmoVvOJAp8NEdkpy9nFQkREZM9mZucDF7r7YcmORUREpKSpBlFEREREREQAJYgiIiIiIiISqImpiIiIiIiIAKpBFBERERERkWCHiXvLurp163p6enqywxAREREREUmKL774YqW718tr3R6XIKanpzN16tRkhyEiIiIiIpIUZvZDfuvUxFREREREREQAJYgiIiIiIiISKEEUERERERERQAmiiIiIiIiIBEoQRUREREREBFCCKCIiIiIiIoESxEL65Zdf6NevH23atKFt27Z88sknXHvttbRp04ZOnTrRt29ffvnlFwC2bNnC4MGD6dixI23btmXEiBGx/Rx11FG0bt2ajIwMMjIyWL58OQB33XUX7dq1o1OnTvTq1Ysffsh35FkREREREZGEUIJYSFdccQV9+vTh66+/Zvr06bRt25bevXsza9YsZsyYQatWrWKJ4HPPPcemTZuYOXMmX3zxBf/6179YsGBBbF9PP/00mZmZZGZmUr9+fQC6dOnC1KlTmTFjBv369eO6665LxmGKiIiIiMgeTAliIaxZs4b333+foUOHAlCxYkVq1arFscceS1paGgA9evRg0aJFAJgZ69evJysri99++42KFStSs2bNAh+jZ8+eVK1adYd9iYiIiIiIlBQliIXw/fffU69ePS644AK6dOnChRdeyPr163Pc5/HHH+f4448HoF+/flSrVo2GDRvSrFkzrrnmGmrXrh277wUXXEBGRga33nor7r7D4z322GOxfYmIiIiIiJQUJYiFkJWVxbRp07jsssv48ssvqVatGiNHjoytHz58OGlpaQwaNAiAKVOmUL58eZYsWcL8+fO58847+f7774GoeenMmTP54IMP+OCDD3jqqadyPNZ///tfpk6dyrXXXltyBygiIiIiIoISxEJp0qQJTZo04aCDDgKiGsJp06YBMHr0aF599VWefvppzAyAZ555hj59+lChQgXq16/PoYceytSpUwFo3LgxADVq1ODss89mypQpscd5++23GT58OBMmTKBSpUoleYgiIiIiIiJKEAtjn332oWnTpsydOxeAyZMn065dOyZOnMjtt9/OhAkTYv0HAZo1a8Y777yDu7N+/Xo+/fRT2rRpQ1ZWFitXrgSikU5fffVVOnToAMCXX37JJZdcwoQJE2ID14iIiIiIiJQky6sPXFnWvXt3z67NK4rMzEwuvPBCNm/ezH777ccTTzzBAQccwKZNm6hTpw4QDS7z8MMPs27dOi644ALmzJmDu3PBBRdw7bXXsn79eo444gi2bNnC1q1bOeaYY7jrrrsoX748xxxzDDNnzqRhw4ZAlGROmDChWI9dRERERETEzL5w9+55rlOCKCIiIiIisucoKEFUE1MREREREREBIC3ZAZR26cNeS/hjLBh5YsIfQ0REREREZGdUgygiIiIiIiKAEkQREREREREJlCCKiIiIiIgIoARRREREREREAiWIIiIiIiIiAihBFBERERERkUAJooiIiIiIiABKEEVERERERCRQgigiIiIiIiKAEkQREREREREJlCCKiIiIiIgIoARRREREREREAiWIIiIiIiIiAiQ4QTSzWmb2vJl9bWZfmdnBZlbbzCaZ2bzwf++4+99gZt+a2VwzOy6uvJuZzQzr7jMzC+WVzOzZUP6ZmaUn8nhERERERETKskTXIN4LTHT3NkBn4CtgGDDZ3VsCk8MyZtYOGAC0B/oAD5pZ+bCfh4CLgZbhr08oHwqsdvcWwN3A7Qk+HhERERERkTIrYQmimdUEjgAeA3D3ze7+C3AqMDrcbTRwWrh9KjDW3Te5+3zgW+BAM2sI1HT3T9zdgf/k2iZ7X88DvbJrF0VERERERKRoElmDuB+wAnjCzL40s3+bWTWggbsvBQj/64f7NwYWxm2/KJQ1Drdzl+fYxt2zgF+BOrkDMbOLzWyqmU1dsWJFcR2fiIiIiIhImZLIBDEN6Ao85O5dgPWE5qT5yKvmzwsoL2ibnAXuj7h7d3fvXq9evYKjFhERERER2UMlMkFcBCxy98/C8vNECeOy0GyU8H953P2bxm3fBFgSypvkUZ5jGzNLA/YCfi72IxEREREREdkDJCxBdPefgIVm1joU9QLmABOAwaFsMDA+3J4ADAgjk+5LNBjNlNAMda2Z9Qj9C8/LtU32vvoB74R+iiIiIiIiIlJEaQne/++Bp82sIvA9cAFRUjrOzIYCPwL9Adx9tpmNI0ois4DfufvWsJ/LgCeBKsAb4Q+iAXCeMrNviWoOByT4eERERERERMqshCaI7p4JdM9jVa987j8cGJ5H+VSgQx7lGwkJpoiIiIiIiOyeRM+DKCIiIiIiIilCCaKIiIiIiIgAShBFREREREQkUIIoIiIiIiIigBJEERERERERCZQgioiIiIiICKAEUURERERERAIliCIiIiIiIgIoQRQREREREZFACaKIiIiIiIgAShBFREREREQkUIIoIiIiIiIigBJEERERERERCZQgioiIiIiICKAEUURERERERAIliCIiIiIiIgIoQRQREREREZFACaKIiIiIiIgAShBFREREREQkUIIoIiIiIiIigBJEERERERERCZQgioiIiIiICKAEUURERERERAIliCIiIiIiIgIoQRQREREREZFACaKIiIiIiIgAShBFREREREQkUIIoIiIiIiIigBJEERERERERCZQgioiIiIiICKAEUURERERERAIliCIiIiIiIgIoQRQREREREZFACaKIiIiIiIgAShBFREREREQkUIIoIiIiIiIigBJEERERERERCZQgioiIiIiICKAEUURERERERAIliCIiIiIiIgIoQRQREREREZFACaKIiIiIiIgAShBFREREREQkUIIoIiIiIiIigBJEERERERERCZQgioiIiIiICKAEUURERERERAIliCIiIiIiIgIkOEE0swVmNtPMMs1saiirbWaTzGxe+L933P1vMLNvzWyumR0XV94t7OdbM7vPzCyUVzKzZ0P5Z2aWnsjjERERERERKctKogaxp7tnuHv3sDwMmOzuLYHJYRkzawcMANoDfYAHzax82OYh4GKgZfjrE8qHAqvdvQVwN3B7CRyPiIiIiIhImZSMJqanAqPD7dHAaXHlY919k7vPB74FDjSzhkBNd//E3R34T65tsvf1PNAru3ZRREREREREiibRCaIDb5nZF2Z2cShr4O5LAcL/+qG8MbAwbttFoaxxuJ27PMc27p4F/ArUScBxiIiIiIiIlHlpCd7/oe6+xMzqA5PM7OsC7ptXzZ8XUF7QNjl3HCWnFwM0a9as4IhFRERERET2UAmtQXT3JeH/cuAl4EBgWWg2Svi/PNx9EdA0bvMmwJJQ3iSP8hzbmFkasBfwcx5xPOLu3d29e7169Yrn4ERERERERMqYhCWIZlbNzGpk3waOBWYBE4DB4W6DgfHh9gRgQBiZdF+iwWimhGaoa82sR+hfeF6ubbL31Q94J/RTFBERERERkSJKZBPTBsBLYcyYNOAZd59oZp8D48xsKPAj0B/A3Web2ThgDpAF/M7dt4Z9XQY8CVQB3gh/AI8BT5nZt0Q1hwMSeDwiIiIiIiJlWsISRHf/HuicR/kqoFc+2wwHhudRPhXokEf5RkKCKSIiIiIiIrsnGdNciIiIiIiISCmkBFFEREREREQAJYgiIiIiIiISKEEUERERERERQAmiiIiIiIiIBEoQRUREREREBFCCKCIiIiIiIoESRBEREREREQGUIIqIiIiIiEigBFFEREREREQAJYgiIiIiIiISKEEUERERERERQAmiiIiIiIiIBEoQRUREREREBFCCKCIiIiIiIoESRBEREREREQGUIIqIiIiIiEigBFFEREREREQAJYgiIiIiIiISKEEUERERERERQAmiiIiIiIiIBEoQRUREREREBFCCKCIiIiIiIoESRBEREREREQGUIIqIiIiIiEigBFFEREREREQAJYgiIiIiIiISKEEUERERERERQAmiiIiIiIiIBEoQRUREREREBFCCKCIiIiIiIoESRBEREREREQGUIIqIiIiIiEigBFFEREREREQAJYgiIiIiIiISKEEUERERERERQAmiiIiIiIiIBEoQRUREREREBFCCKCIiIiIiIoESRBEREREREQGUIIqIiIiIiEigBFFEREREREQAJYgiIiIiIiISKEEUERERERERQAmiiIiIiIiIBEoQRUREREREBFCCKCIiIiIiIoESRBEREREREQGUIIqIiIiIiEiQ8ATRzMqb2Zdm9mpYrm1mk8xsXvi/d9x9bzCzb81srpkdF1fezcxmhnX3mZmF8kpm9mwo/8zM0hN9PCIiIiIiImVVSdQgXgF8Fbc8DJjs7i2ByWEZM2sHDADaA32AB82sfNjmIeBioGX46xPKhwKr3b0FcDdwe2IPRUREREREpOxKaIJoZk2AE4F/xxWfCowOt0cDp8WVj3X3Te4+H/gWONDMGgI13f0Td3fgP7m2yd7X80Cv7NpFERERERERKZpE1yDeA1wHbIsra+DuSwHC//qhvDGwMO5+i0JZ43A7d3mObdw9C/gVqJM7CDO72MymmtnUFStW7OYhiYiIiIiIlE0JSxDN7CRgubt/UdhN8ijzAsoL2iZngfsj7t7d3bvXq1evkOGIiIiIiIjsWdISuO9DgVPM7ASgMlDTzP4LLDOzhu6+NDQfXR7uvwhoGrd9E2BJKG+SR3n8NovMLA3YC/g5UQckIiIiIiJSliWsBtHdb3D3Ju6eTjT4zDvufg4wARgc7jYYGB9uTwAGhJFJ9yUajGZKaIa61sx6hP6F5+XaJntf/cJj7FCDKCIiIiIiIjuXyBrE/IwExpnZUOBHoD+Au882s3HAHCAL+J27bw3bXAY8CVQB3gh/AI8BT5nZt0Q1hwNK6iBERERERETKmhJJEN39XeDdcHsV0Cuf+w0HhudRPhXokEf5RkKCKSIiIiIiIrunJOZBFBERERERkRSgBFFEREREREQAJYgiIiIiIiISKEEUERERERERQAmiiIiIiIiIBEoQRUREREREBFCCKCIiIiIiIoESRBEREREREQEgLb8VZrYW8PzWu3vNhEQkIiIiIiIiSZFvgujuNQDM7BbgJ+ApwIBBQI0SiU5ERERERERKTGGamB7n7g+6+1p3X+PuDwFnJDowERERERERKVmFSRC3mtkgMytvZuXMbBCwNdGBiYiIiIiISMkqTIJ4NnAmsCz89Q9lIiIiIiIiUobk2wcxm7svAE5NfCgiIiIiIiKSTDutQTSzVmY22cxmheVOZvaXxIcmIiIiIiIiJakwTUwfBW4AtgC4+wxgQCKDEhERERERkZJXmASxqrtPyVWWlYhgREREREREJHkKkyCuNLP9AQcws37A0oRGJSIiIiIiIiVup4PUAL8DHgHamNliYD5wTkKjEhERERERkRJXmFFMvweOMbNqQDl3X5v4sERERERERKSkFWYU0yvMrCawAbjbzKaZ2bGJD01ERERERERKUmH6IA5x9zXAsUB94AJgZEKjkoTYuHEjBx54IJ07d6Z9+/bcdNNNANx444106tSJjIwMjj32WJYsWQLA008/TUZGRuyvXLlyZGZmArB582YuvvhiWrVqRZs2bXjhhRcAuOuuu2jXrh2dOnWiV69e/PDDD0k5VhERERERKbrCJIgW/p8APOHu0+PKJIVUqlSJd955h+nTp5OZmcnEiRP59NNPufbaa5kxYwaZmZmcdNJJ3HLLLQAMGjSIzMxMMjMzeeqpp0hPTycjIwOA4cOHU79+fb755hvmzJnDkUceCUCXLl2YOnUqM2bMoF+/flx33XXJOlwRERERESmiwgxS84WZvQXsC9xgZjWAbYkNSxLBzKhevToAW7ZsYcuWLZgZNWvWjN1n/fr1mO2Y/48ZM4aBAwfGlh9//HG+/vprAMqVK0fdunUB6NmzZ+w+PXr04L///W9CjkVERERERIpfYWoQhwLDgAPcfQNQkaiZqaSgrVu3kpGRQf369enduzcHHXQQAH/+859p2rQpTz/9dKwGMd6zzz4bSxB/+eUXIGqa2rVrV/r378+yZct22Oaxxx7j+OOPT9zBiIiIiIhIsco3QTSzrmbWFcgIRfuaWVN3X+XuM0okOil25cuXJzMzk0WLFjFlyhRmzZoFRE1GFy5cyKBBg3jggQdybPPZZ59RtWpVOnToAEBWVhaLFi3i0EMPZdq0aRx88MFcc801Obb573//y9SpU7n22mtL5sBERERERGS3FVSDeGeuv7uAV83sKzPrXBLBSeLUqlWLo446iokTJ+YoP/vss2MDzmQbO3ZsjualderUoWrVqvTt2xeA/v37M23atNj6t99+m+HDhzNhwgQqVaqUwKMQEREREZHilG+C6O498/jrDJwL3F9yIUpxWbFiRax56G+//cbbb79NmzZtmDdvXuw+EyZMoE2bNrHlbdu28dxzzzFgwIBYmZlx8skn8+677wIwefJk2rVrB8CXX37JJZdcwoQJE6hfv37iD0pERERERIpNYQapycHdp5pZ9UQEI4m1dOlSBg8ezNatW9m2bRtnnnkmJ510EmeccQZz586lXLlyNG/enIcffji2zfvvv0+TJk3Yb7/9cuzr9ttv59xzz+WPf/wj9erV44knngDg2muvZd26dfTv3x+AZs2aMWHChJI7SBERERER2WXm7kXbwKwB8Lq7d0tMSInVvXt3nzp1aqHvnz7stQRGE1kw8sSEP4aIiIiIiAiAmX3h7t3zWpdvDaKZ3Q/kzh5rA4cAVxRfeFISEp3oKskVEREREUl9BTUxzV3N5sAq4Cp3X564kERERERERCQZ8k0Q3X10SQYiIiIiIiIiyVXQNBciIiIiIiKyB1GCKCIiIiIiIkARE0QzK2dmNRMVjIiIiIiIiCTPThNEM3vGzGqaWTVgDjDXzK5NfGgiIiIiIiJSkgpTg9jO3dcApwGvA82AcxMZlIiIiIiIiJS8wiSIFcysAlGCON7dt7Dj/IgiIiIiIiKS4gqTIP4LWABUA943s+bAmkQGJSIiIiIiIiUv33kQs7n7fcB9cUU/mFnPxIUkIiIiIiIiyVCYQWoamNljZvZGWG4HDE54ZCIiIiIiIlKiCtPE9EngTaBRWP4G+GOC4hEREREREZEkKUyCWNfdxwHbANw9C9ia0KhERERERESkxBUmQVxvZnUII5eaWQ/g14RGJSIiIiIiIiVup4PUAFcBE4D9zewjoB7QL6FRiYiIiIiISIkrzCim08zsSKA1YMDcMBeiiIiIiIiIlCE7TRDNrDxwApAe7n+smeHudyU4NhERERERESlBhWli+gqwEZhJGKhGREREREREyp7CJIhN3L1TUXdsZpWB94FK4XGed/ebzKw28CxRjeQC4Ex3Xx22uQEYSjRK6h/c/c1Q3o1ouo0qwOvAFe7uZlYJ+A/QDVgFnOXuC4oaq4iIiIiIiBRuFNM3zOzYXdj3JuBod+8MZAB9wgiow4DJ7t4SmByWMbN2wACgPdAHeDA0bwV4CLgYaBn++oTyocBqd28B3A3cvgtxioiIiIiICIVLED8FXjKz38xsjZmtNbM1O9vII+vCYoXw58CpwOhQPho4Ldw+FRjr7pvcfT7wLXCgmTUEarr7J+7uRDWG8dtk7+t5oJeZWSGOSURERERERHIpTIJ4J3AwUNXda7p7DXevWZidm1l5M8sElgOT3P0zoIG7LwUI/+uHuzcGFsZtviiUNQ63c5fn2Mbds4jmZ6yTRxwXm9lUM5u6YsWKwoQuIiIiIiKyxylMgjgPmBVq74rE3be6ewbQhKg2sEMBd8+r5s8LKC9om9xxPOLu3d29e7169XYStYiIiIiIyJ6pMIPULAXeNbM3iPoVAhRpmgt3/8XM3iXqO7jMzBq6+9LQfHR5uNsioGncZk2AJaG8SR7l8dssMrM0YC/g58LGJSIiIiIiItsVpgZxPtFgMhWBGnF/BTKzemZWK9yuAhwDfA1MAAaHuw0GxofbE4ABZlbJzPYlGoxmSmiGutbMeoT+hefl2iZ7X/2Ad3alplNEREREREQKUYPo7n/bxX03BEaHkUjLAePc/VUz+wQYZ2ZDgR+B/uFxZpvZOGAOkAX8zt23hn1dxvZpLt4IfwCPAU+Z2bdENYcDdjFWERERERGRPV6+CaKZPeDul5vZK+Tdr++Ugnbs7jOALnmUrwJ65bPNcGB4HuVTgR36L7r7RkKCKSIiIiIiIrunoBrE84DLgX+WUCwiIiIiIiKSRAUliN8BuPt7JRSLiIiIiIiIJFFBCWI9M7sqv5VFGcVURERERERESr+CEsTyQHXynmtQREREREREypiCEsSl7n5LiUUiIiIiIiIiSVXQPIiqORQREREREdmDFJQg5jkVhYiIiIiIiJRN+SaI7v5zSQYiIiIiIiIiyVVQDaKIiIiIiIjsQZQgioiIiIiICKAEUURERERERAIliCIiIiIiIgIoQRQREREREZFACaKIiIiIiIgAShBFREREREQkUIIoIiIiIiIigBJEERERERERCZQgioiIiIiICKAEUURERERERAIliJJSFi5cSM+ePWnbti3t27fn3nvvzbH+n//8J2bGypUrAVi1ahU9e/akevXqXH755Tnu26dPHzp37kz79u259NJL2bp1KwA//PADvXr1olOnThx11FEsWrSoZA5ORERERCTJlCBKSklLS+POO+/kq6++4tNPP2XUqFHMmTMHiJLHSZMm0axZs9j9K1euzK233so///nPHfY1btw4pk+fzqxZs1ixYgXPPfccANdccw3nnXceM2bM4K9//Ss33HBDyRyciIiIiEiSKUGUlNKwYUO6du0KQI0aNWjbti2LFy8G4Morr+SOO+7AzGL3r1atGocddhiVK1feYV81a9YEICsri82bN8e2mzNnDr169QKgZ8+ejB8/PqHHJCIiIiJSWihBlJS1YMECvvzySw466CAmTJhA48aN6dy5c5H2cdxxx1G/fn1q1KhBv379AOjcuTMvvPACAC+99BJr165l1apVxR6/iIiIiEhpowRRUtK6des444wzuOeee0hLS2P48OHccsstRd7Pm2++ydKlS9m0aRPvvPMOEPVjfO+99+jSpQvvvfcejRs3Ji0trbgPQURERESk1FGCKClny5YtnHHGGQwaNIjTTz+d7777jvnz59O5c2fS09NZtGgRXbt25aeffirU/ipXrswpp5wSa0raqFEjXnzxRb788kuGDx8OwF577ZWw4xERERERKS1ULSIpxd0ZOnQobdu25aqrrgKgY8eOLF++PHaf9PR0pk6dSt26dfPdz7p161i7di0NGzYkKyuL119/ncMPPxyAlStXUrt2bcqVK8eIESMYMmRIYg9KRERERKSUUIIoKeWjjz7iqaeeomPHjmRkZADw97//nRNOOCHfbdLT01mzZg2bN2/m5Zdf5q233qJOnTqccsopbNq0ia1bt3L00Udz6aWXAvDuu+9yww03YGYcccQRjBo1qiQOTUREREQk6ZQgSko57LDDcPcC77NgwYICl7N9/vnneZb369cvNmCNiIiIiMieRAmipIz0Ya8ldP8LRp6Y0P2LiIiIiJR2GqRGREREREREACWIIiIiIiIiEihBFBEREREREUAJooiIiIiIiARKEEVERERERARQgigiIiIiIiKBEkQREREREREBlCCKiIiIiIhIoARRREREREREACWIIiIiIiIiEihBFBEREREREUAJooiIiIiIiARKEEVERERERARQgigiIiIiIiKBEkQREREREREBlCCKiIiIiIhIoARRREREREREACWIIiIiIiIiEihBFBERERERESCBCaKZNTWz/5nZV2Y228yuCOW1zWySmc0L//eO2+YGM/vWzOaa2XFx5d3MbGZYd5+ZWSivZGbPhvLPzCw9UccjUpyGDBlC/fr16dChQ6xs+vTpHHzwwXTs2JGTTz6ZNWvWALBq1Sp69uxJ9erVufzyy3Ps59lnn6VTp060b9+e6667LlZ+5ZVXkpGRQUZGBq1ataJWrVolclwiIiIiktoSWYOYBVzt7m2BHsDvzKwdMAyY7O4tgclhmbBuANAe6AM8aGblw74eAi4GWoa/PqF8KLDa3VsAdwO3J/B4RIrN+eefz8SJE3OUXXjhhYwcOZKZM2fSt29f/vGPfwBQuXJlbr31Vv75z3/muP+qVau49tprmTx5MrNnz2bZsmVMnjwZgLvvvpvMzEwyMzP5/e9/z+mnn14yByYiIiIiKS1hCaK7L3X3aeH2WuAroDFwKjA63G00cFq4fSow1t03uft84FvgQDNrCNR090/c3YH/5Nome1/PA72yaxdFSrMjjjiC2rVr5yibO3cuRxxxBAC9e/fmhRdeAKBatWocdthhVK5cOcf9v//+e1q1akW9evUAOOaYY2LbxBszZgwDBw5MxGGIiIiISBlTIn0QQ9PPLsBnQAN3XwpREgnUD3drDCyM22xRKGscbucuz7GNu2cBvwJ18nj8i81sqplNXbFiRTEdlUjx6tChAxMmTADgueeeY+HChQXev0WLFnz99dcsWLCArKwsXn755R22+eGHH5g/fz5HH310wuIWERERkbIj4QmimVUHXgD+6O5rCrprHmVeQHlB2+QscH/E3bu7e/fs2haR0ubxxx9n1KhRdOvWjbVr11KxYsUC77/33nvz0EMPcdZZZ3H44YeTnp5OWlpajvuMHTuWfv36Ub58+Xz2IiIiIiKyXdrO77LrzKwCUXL4tLu/GIqXmVlDd18amo8uD+WLgKZxmzcBloTyJnmUx2+zyMzSgL2AnxNyMCIJ1qZNG9566y0AvvnmG1577bWdbnPyySdz8sknA/DII4/skAiOHTuWUaNGFX+wIiIiIlImJXIUUwMeA75y97viVk0ABofbg4HxceUDwsik+xINRjMlNENda2Y9wj7Py7VN9r76Ae+EfooiKWf58uhaybZt27jtttu49NJLC73N6tWrefDBB7nwwgtj6+bOncvq1as5+OCDExOwiIiIiJQ5iaxBPBQ4F5hpZpmh7E/ASGCcmQ0FfgT6A7j7bDMbB8whGgH1d+6+NWx3GfAkUAV4I/xBlIA+ZWbfEtUcDkjg8YgUm4EDB/Luu++ycuVKmjRpwt/+9jfWrVsXq+07/fTTueCCC2L3T09PZ82aNWzevJmXX36Zt956i3bt2nHFFVcwffp0AP7617/SqlWr2DZjxoxhwIABaNwmERERESks29Mq3Lp37+5Tp04t9P3Th+28md/uWjDyxIQ/RqKPQ8dQOGXl/SQiIiIiqcvMvnD37nmtK5FRTEVERERERKT0U4IoIiIiIiIigBJEERERERERCZQgioiIiIiICKAEUURERERERAIliCIiIiIiIgIoQRQREREREZFACaKIiIiIiIgAShBFREREREQkUIIoIiIiIiIigBJEERERERERCZQgioiIiIiICKAEUURERERERAIliCIiIiIiIgIoQRQREREREZFACaKIiIiIiIgAShBFREREREQkUIIoIiIiIiIigBJEERERERERCZQgioiIiIiICKAEUURERERERAIliCIiIiIiIgIoQRQREREREZFACaKIiIiIiIgAShBFREREREQkUIIoIiIiIiIigBJEERERERERCZQgioiIiIiICKAEUURERERERAIliCIiIiIiIgIoQRQREREREZFACaKIiIiIiIgAShBFREREREQkUIIoIiIiIiIigBJEERERERERCZQgioiIiIiICKAEUURERERERAIliCIiIiIiIgIoQRQREREREZFACaKI7JIhQ4ZQv359OnToECv7+eef6d27Ny1btqR3796sXr0agM2bN3PBBRfQsWNHOnfuzLvvvhvb5s9//jNNmzalevXqeT7O888/j5kxderUhB6PiIiIiChBFJFddP755zNx4sQcZSNHjqRXr17MmzePXr16MXLkSAAeffRRAGbOnMmkSZO4+uqr2bZtGwAnn3wyU6ZMyfMx1q5dy3333cdBBx2UwCMRERERkWxKEEVklxxxxBHUrl07R9n48eMZPHgwAIMHD+bll18GYM6cOfTq1QuA+vXrU6tWrViNYI8ePWjYsGGej3HjjTdy3XXXUbly5QQdhYiIiIjEU4IoIsVm2bJlsWSvYcOGLF++HIDOnTszfvx4srKymD9/Pl988QULFy4scF9ffvklCxcu5KSTTkp43CIiIiISSUt2ACJS9g0ZMoSvvvqK7t2707x5cw455BDS0vL/+tm2bRtXXnklTz75ZMkFKSIiIiJKEEWk+DRo0IClS5fSsGFDli5dSv369QFIS0vj7rvvjt3vkEMOoWXLlvnuZ+3atcyaNYujjjoKgJ9++olTTjmFCRMm0L1794Qeg4iIiMieTE1MRaTYnHLKKYwePRqA0aNHc+qppwKwYcMG1q9fD8CkSZNIS0ujXbt2+e5nr732YuXKlSxYsIAFCxbQo0cPJYciIiIiJUAJoojskoEDB3LwwQczd+5cmjRpwmOPPcawYcOYNGkSLVu2ZNKkSQwbNgyA5cuX07VrV9q2bcvtt9/OU089FdvPddddR5MmTdiwYQNNmjTh5ptvTtIRiYiIiIiamIpIkaQPey260fwcKg0+h8ah/NZ5cOs/PoUDroID4Dug6x2fbN+w710AfAsc+dAsYFZUXu5I0s45kmbhbk9uhJtzPWb8vIki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iRJEEZEyoFyFyjS9YkyOsvJVatJgwN/zvP9eh5zFXoeclXMfFSvT8Px7Y8v3jjyx+AMVERGRUk1NTEVEpNRIT0+nY8eOZGRk0L17dwBuvvlmGjduTEZGBhkZGbz++usArFq1ip49e1K9enUuv/zyHPvZvHkzF198Ma1ataJNmza88MILJX4sIiIiqUg1iCIiUqr873//o27dujnKrrzySq655pocZZUrV+bWW29l1qxZzJo1K8e64cOHU79+fb755hu2bdvGzz//nPC4RUREygIliCIikpKqVavGYYcdxrfffrvDuscff5yvv/4agHLlyu2QcIqIiEje1MRURERKDTPj2GOPpVu3bjzyyCOx8gceeIBOnToxZMgQVq9eXeA+fvnlFwBuvPFGunbtSv/+/Vm2bFkiwxYRESkzlCCKiEip8dFHHzFt2jTeeOMNRo0axfvvv89ll13Gd999R2ZmJg0bNuTqq68ucB9ZWVksWrSIQw89lGnTpnHwwQfv0DxVRERE8qYEUURESo1GjRoBUL9+ffr27cuUKVNo0KAB5cuXp1y5clx00UVMmTKlwH3UqVOHqlWr0rdvXwD69+/PtGnTEh67iIhIWaAEUURESoX169ezdu3a2O233nqLDh06sHTp0th9XnrpJTp06FDgfsyMk08+mXfffReAyZMn065du4TFLSIiUpZokBoREUma9GGvxW5v+eUnVrx4W7SwbRvV2h3Jpe9uZeU1g9i87HswI22v+tQ+7vLYdoseGoJv3oBvzeLh0WOpf9atVKzbjKy9j+PlwX9g26b1HN5xP5544olkHJ6IiEjKUYIoIiKlQoVa+9BoyAM7lNc9Kf8+h00uezzP8rS96rPPoNsBmDzyxOIJUEREZA+gJqYiIiIiIiICKEEUERERERGRQAmiiIhIMdm4cSMHHnggnTt3pn379tx0000A3HzzzTRu3JiMjAwyMjJ4/fXXY9uMGDGCFi1a0Lp1a958800ANmzYwIknnkibNm1o3749w4YNS8rxiIjInkd9EEVERIpJpUqVeOedd6hevTpbtmzhsMMO4/jjjwfgyiuv3GE+xjlz5jB27Fhmz57NkiVLOOaYY/jmm28AuOaaa+jZsyebN2+mV69evPHGG7F9iYiIJIpqEEVERIqJmVG9enUAtmzZwpYtWzCzfO8/fvx4BgwYQKVKldh3331p0aIFU6ZMoWrVqvTs2ROAihUr0rVrVxYtWlQixyAiIns2JYgiIiLFaOvWrWRkZFC/fn169+7NQQcdBMADDzxAp06dGDJkCKtXrwZg8eLFNG3aNLZtkyZNWLx4cY79/fLLL7zyyiv06tWr5A5CRET2WEoQRUREilH58uXJzMxk0aJFTJkyhVmzZnHZZZfx3XffkZmZScOGDbn66mjqDnffYfv4GsesrCwGDhzIH/7wB/bbb78SOwYREdlzKUEUERFJgFq1anHUUUcxceJEGjRoQPny5SlXrhwXXXQRU6ZMAaIaw4ULF8a2WbRoEY0aNYotX3zxxbRs2ZI//vGPJR2+iIjsoZQgioiIFJMVK1bwyy+/APDbb7/x9ttv06ZNG5YuXRq7z0svvUSHDh0AOOWUUxg7diybNm1i/vz5zJs3jwMPPBCAv/zlL/z666/cc889JX0YIiKyB9MopiIiIsVk6dKlDB48mK1bt7Jt2zbOPPNMTjrpJM4991wyMzMxM9LT0/nXv/4FQPv27TnzzDNp164daWlpjBo1ivLly7No0SKGDx9OmzZt6Nq1KwCXX345F154YTIPT0RE9gBKEEVERHZD+rDXchYcd1vs5uMb4PFhr0HjAdEfMAM4+N5pcRtkQP/72Apc9t42eC/aX/PrX+U34DdgwcgTE3gEOS1cuJDzzjuPn376iXLlynHxxRdzxRVX8Nxzz3HzzTfz1VdfMWXKFLp3755jux9//JF27dpx8803x6bzePbZZxk+fDhbt27lxBNP5I477iix4xARkV2jJqYiIiISk5aWxp133slXX33Fp59+yqhRo5gzZw4dOnTgxRdf5IgjjshzuyuvvDLHPI2rVq3i2muvZfLkycyePZtly5YxefLkkjoMFi5cSM+ePWnbti3t27fn3nvvBeDnn3+md+/etGzZkt69e8dGlF2wYAFVqlQhIyODjIwMLr300h32ecopp8SaB5eUIUOGUL9+/RyPO336dA4++GA6duzIySefzJo1awCYMmVKLP7OnTvz0ksvAbB27dpYeUZGBnXr1lW/VhHJlxJEERERiWnYsGGsWWuNGjVo27Ytixcvpm3btrRu3TrPbV5++WX2228/2rdvHyv7/vvvadWqFfXq1QPgmGOO4YUXXkj8AQT5JbojR46kV69ezJs3j169ejFy5MjYNvvvvz+ZmZlkZmby8MMP59jfiy++GJvjsiSdf/75TJw4MUfZhRdeyMiRI5k5cyZ9+/blH//4BwAdOnRg6tSpZGZmMnHiRC655BKysrKoUaNG7LgyMzNp3rw5p59+eokdQ15J7llnnRVLWNPT08nIyABg8+bNXHDBBXTs2JHOnTvz7rvvxrbp06cPnTt3pn379lx66aVs3bq1xI5BZE+iBFFERETytGDBAr788svYXI55Wb9+Pbfffjs33XRTjvIWLVrw9ddfs2DBArKysnj55ZdzjNiaaPkluuPHj2fw4MEADB48mJdffnmn+1q3bh133XUXf/nLXxIZcp6OOOIIateunaNs7ty5sZrc3r17xxLvqlWrkpYW9R7auHFjjilTss2bN4/ly5dz+OGHJzjy7fJKcp999tlYwnrGGWfEEtZHH30UgJkzZzJp0iSuvvpqtm3bBsC4ceOYPn06s2bNYsWKFTz33HMldgwiexIliCIiIrKDdevWccYZZ3DPPfdQs2bNfO930003ceWVV+5Qu7b33nvz0EMPcdZZZ3H44YeTnp4eS15KWnyiu2zZMho2bAhESeTy5ctj95s/fz5dunThyCOP5IMPPoiV33jjjVx99dVUrVq1xGPPS4cOHZgwYQIAzz33XI7E+7PPPqN9+/Z07NiRhx9+eIfnfMyYMZx11ll5Jo+JkleSm83dGTduHAMHDgRgzpw59OrVC4D69etTq1Ytpk6dChB7H2ZlZbF58+YSPQbIuyb05ptvpnHjxrHa0Ndffx2ASZMm0a1bNzp27Ei3bt145513YtuoJlRKOyWIIiIiksOWLVs444wzGDRo0E6bIn722Wdcd911pKenc8899/D3v/+dBx54AICTTz6Zzz77jE8++YTWrVvTsmXLkgg/h8Imug0bNuTHH3/kyy+/5K677uLss89mzZo1ZGZm8u2339K3b98SjLpgjz/+OKNGjaJbt26sXbuWihUrxtYddNBBzJ49m88//5wRI0awcePGHNuOHTs2loyVBh988AENGjSIvTc6d+7M+PHjycrKYv78+XzxxRc5EuDjjjuO+vXrU6NGDfr161eiseZVEwpR/9vs2tATTjgBgLp16/LKK68wc+ZMRo8ezbnnnhu7v2pCpbTTKKYiIiIS4+4MHTqUtm3bctVVV+30/vE1bTfffDPVq1fn8ssvB2D58uXUr1+f1atX8+CDDzJu3LiExZ2XvBLdBg0asHTpUho2bMjSpUupX78+AJUqVaJSpUoAdOvWjf33359vvvmGzz//nC+++IL09HSysrJYvnw5Rx11VI6+cSWtTZs2vPXWWwB88803vPbaazvcp23btlSrVo1Zs2bFRpydPn06WVlZdOvWrUTjLciYMWNyJKxDhgzhq6++onv37jRv3pxDDjkkRy3om2++ycaNGxk0aBDvvPMOvXv3LrFYjzjiCBYsWFCo+3bp0iV2u3379mzcuJFNmzZRqVKlpNeEiuyMahBFRESE9GGvkT7sNRqe+w+eeuopHnxmPBUb7EfFBvvRoP/N1D/9z6TVqMt7H37EQUf2psq+XWPbZP/d8/Y3DH/tq9jyvkf1p2LdZjRo2Zlhw4bRqlWrEjue/BLdU045hdGjRwMwevRoTj31VABWrFgRa+r3/fffM2/ePPbbbz8uu+wylixZwoIFC/jwww9p1apVUpNDINYsdtu2bdx2222xEVfnz59PVlYWAD/88ANz584lPT09tl3uZCzZsrKyePHFFznrrLNiZWlpadx9991kZmYyfvx4fvnllx1qnitXrswpp5zC+PHjSzrkPD3wwAN06tSJIUOGxEbFjffCCy/QpUuX2AUISG5N6L333kuHDh1o374999xzT451//znPzEzVq5cGSsbMWIELVq0oHXr1rz55pslGqskh2oQRUREJKZyk/Y0v/7VPNdVbXVIgdvWOmxQjuV6p1wXuz1gQOLncoyfk3Ljotkse/opKtRL58ExUX+9vY84j4qNurLy4ZHceMd9pNWsR91Tb2DcsNdYP/cjfv3gaShXDitXnr0OG0rXOz7Jsf93L21PSRs4cCDvvvsuK1eupEmTJvztb39j3bp1jBo1CoDTTz+dCy64AIAPP/yQkSNHUqFCBcqVK8eDDz5I3bp1Y/saN25crI9cafD222/Tpk0bmjRpEivbsGED7k61atWYNGkSaWlptGvXjnXr1rF27VoaNmxIVlYWr7/+eokOtJOfyy67jBtvvBEzi/VVffzxx2PrZ8+ezfXXXx+r8c2WrJrQWbNm8eijjzJlyhQqVqxInz59OPHEE2nZsiULFy5k0qRJNGvWLHb/OXPmMHbsWGbPns2SJUs45phj+OabbyhfvnyJxJufu+++m3//+9+YGR07duSJJ57gxhtv5JVXXqFixYrsv//+PPHE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
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Although this plot is extremely basic, it provides some interesting insights. First and foremost, it must be mentioned that the Vandal is by far the most popular weapon. The discrepancy between it and its counterpart, the Phantom, is astonishing, given that they cost the same in game (2900). The second thing that was immediately brought to my attention was the unpopularity of the Operator and Odin. These guns are much more situational, but each have their use. The <a href="https://valorant.fandom.com/wiki/Operator">Operator</a> has the ability to kill an enemy in one hit to the chest, making it an extremely deadly rifle, and the <a href="https://valorant.fandom.com/wiki/Odin">Odin</a> is the best weapon to suppress enemies and to hit an enemy through a wall (wallbang).</p>
<p>If you want to learn more about the debate between the vandal and the phantom, and why the vandal "is superior," <a href="https://dotesports.com/valorant/news/phantom-vs-vandal-whats-the-best-rifle-in-valorant">here is a further reading on the topic</a></p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[6]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Getting the number of games studied</span>
<span class="n">total_games</span> <span class="o">=</span> <span class="nb">len</span><span class="p">(</span><span class="n">round_data</span><span class="p">[</span><span class="s1">&#39;match_id&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">unique</span><span class="p">())</span>

<span class="c1">#Isolating each map that was played</span>
<span class="n">individual_maps</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">round_data</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">round_data</span><span class="p">[</span><span class="s1">&#39;round_num&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="mi">0</span><span class="p">][</span><span class="s1">&#39;map&#39;</span><span class="p">])</span>

<span class="c1">#creating a new dataframe to store each maps occurance</span>
<span class="n">map_count</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">index</span> <span class="o">=</span> <span class="n">round_data</span><span class="p">[</span><span class="s1">&#39;map&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">unique</span><span class="p">(),</span> <span class="n">columns</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;occurances&quot;</span><span class="p">,</span><span class="s1">&#39;occurances_per_game&#39;</span><span class="p">])</span>
<span class="n">map_count</span><span class="p">[</span><span class="s1">&#39;occurances&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="mi">0</span>
<span class="n">map_count</span><span class="p">[</span><span class="s1">&#39;occurances_per_game&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="mf">0.0</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">map_count</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="n">occurances</span> <span class="o">=</span> <span class="p">(</span><span class="n">individual_maps</span><span class="o">.</span><span class="n">map</span><span class="o">.</span><span class="n">values</span> <span class="o">==</span> <span class="n">index</span><span class="p">)</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span>
    <span class="n">map_count</span><span class="o">.</span><span class="n">at</span><span class="p">[</span><span class="n">index</span><span class="p">,</span> <span class="s2">&quot;occurances&quot;</span><span class="p">]</span> <span class="o">=</span> <span class="n">occurances</span>
    <span class="n">map_count</span><span class="o">.</span><span class="n">at</span><span class="p">[</span><span class="n">index</span><span class="p">,</span> <span class="s2">&quot;occurances_per_game&quot;</span><span class="p">]</span> <span class="o">=</span> <span class="n">occurances</span><span class="o">/</span><span class="n">total_games</span>

<span class="c1">#plotting the results in a pie chart</span>
<span class="n">map_count</span><span class="o">.</span><span class="n">plot</span><span class="o">.</span><span class="n">pie</span><span class="p">(</span><span class="n">y</span> <span class="o">=</span> <span class="s2">&quot;occurances_per_game&quot;</span><span class="p">,</span> <span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">12</span><span class="p">,</span><span class="mi">12</span><span class="p">),</span> <span class="n">autopct</span><span class="o">=</span><span class="k">lambda</span> <span class="n">p</span><span class="p">:</span> <span class="s1">&#39;</span><span class="si">{:.2f}</span><span class="s1">%&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">p</span><span class="p">),</span> <span class="n">legend</span> <span class="o">=</span> <span class="kc">None</span><span class="p">,</span>
                   <span class="n">title</span> <span class="o">=</span> <span class="s2">&quot;The Distribution of Maps Played Across all Games Studied&quot;</span><span class="p">,</span>
                   <span class="n">ylabel</span> <span class="o">=</span> <span class="s1">&#39;&#39;</span><span class="p">,</span> <span class="n">xlabel</span> <span class="o">=</span> <span class="s1">&#39;&#39;</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[6]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>&lt;AxesSubplot:title={&#39;center&#39;:&#39;The Distribution of Maps Played Across all Games Studied&#39;}&gt;</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>If each map in Valorant had an equal chance to be played, which I suspect it to be (as Riot has previously mentioned that <a href="https://twitter.com/PlayVALORANT/status/1270068071785324544?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1270068071785324544%7Ctwgr%5E%7Ctwcon%5Es1_&amp;ref_url=https%3A%2F%2Fus.millenium.gg%2Fnews%2F18675.html">"All maps should have an equal chance of being played"</a>), then each map should have around a 14% chance of being played. Obviously this is not the case, as Fracture and Breeze have below a 14% play rate, and with 930 games studied, this is highly unlikely to be random. In fact, there is a mechanic in Valorant where if a player does not pick a character, regardless of intent, the match is canceled. This likely means that Fracture and Breeze have higher dodge rates than the other maps, and is definitely an area of further study.</p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[7]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Isolating the agents picked per game</span>
<span class="n">individual_agents</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">round_data</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">round_data</span><span class="p">[</span><span class="s1">&#39;round_num&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="mi">0</span><span class="p">][</span><span class="s1">&#39;agent&#39;</span><span class="p">])</span>

<span class="c1">#Creating a new dataframe to store the number of times an agent was picked per game</span>
<span class="n">agent_count</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">index</span> <span class="o">=</span> <span class="n">round_data</span><span class="p">[</span><span class="s1">&#39;agent&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">unique</span><span class="p">(),</span> <span class="n">columns</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;occurances&quot;</span><span class="p">,</span><span class="s1">&#39;occurances_per_game&#39;</span><span class="p">])</span>
<span class="n">agent_count</span><span class="p">[</span><span class="s1">&#39;occurances&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="mi">0</span>
<span class="n">agent_count</span><span class="p">[</span><span class="s1">&#39;occurances_per_game&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="mf">0.0</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">agent_count</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="n">occurances</span> <span class="o">=</span> <span class="p">(</span><span class="n">individual_agents</span><span class="o">.</span><span class="n">agent</span><span class="o">.</span><span class="n">values</span> <span class="o">==</span> <span class="n">index</span><span class="p">)</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span>
    <span class="n">agent_count</span><span class="o">.</span><span class="n">at</span><span class="p">[</span><span class="n">index</span><span class="p">,</span> <span class="s2">&quot;occurances&quot;</span><span class="p">]</span> <span class="o">=</span> <span class="n">occurances</span>
    <span class="n">agent_count</span><span class="o">.</span><span class="n">at</span><span class="p">[</span><span class="n">index</span><span class="p">,</span> <span class="s2">&quot;occurances_per_game&quot;</span><span class="p">]</span> <span class="o">=</span> <span class="n">occurances</span><span class="o">/</span><span class="n">total_games</span>
<span class="n">agent_count</span><span class="o">.</span><span class="n">sort_values</span><span class="p">(</span><span class="n">by</span><span class="o">=</span><span class="s1">&#39;occurances&#39;</span><span class="p">,</span> <span class="n">ascending</span><span class="o">=</span><span class="kc">False</span><span class="p">,</span> <span class="n">inplace</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>

<span class="c1">#Creating a bar graph to display results</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">agent_count</span><span class="o">.</span><span class="n">plot</span><span class="o">.</span><span class="n">bar</span><span class="p">(</span><span class="n">y</span> <span class="o">=</span> <span class="s2">&quot;occurances_per_game&quot;</span><span class="p">,</span> <span class="n">figsize</span> <span class="o">=</span> <span class="p">(</span><span class="mi">15</span><span class="p">,</span><span class="mi">7</span><span class="p">),</span> <span class="n">legend</span> <span class="o">=</span> <span class="kc">None</span><span class="p">,</span>
                          <span class="n">title</span> <span class="o">=</span> <span class="s2">&quot;The Frequency an Agent was Picked per Game, Across all Games Studied&quot;</span><span class="p">,</span>
                          <span class="n">xlabel</span> <span class="o">=</span> <span class="s2">&quot;Agent&quot;</span><span class="p">,</span> <span class="n">ylabel</span> <span class="o">=</span> <span class="s2">&quot;Frequency&quot;</span><span class="p">)</span>
<span class="k">for</span> <span class="n">p</span> <span class="ow">in</span> <span class="n">ax</span><span class="o">.</span><span class="n">patches</span><span class="p">:</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">annotate</span><span class="p">(</span><span class="nb">str</span><span class="p">(</span><span class="nb">round</span><span class="p">(</span><span class="n">p</span><span class="o">.</span><span class="n">get_height</span><span class="p">(),</span><span class="mi">2</span><span class="p">)),</span> <span class="p">(</span><span class="n">p</span><span class="o">.</span><span class="n">get_x</span><span class="p">()</span> <span class="o">*</span> <span class="mf">1.005</span><span class="p">,</span> <span class="n">p</span><span class="o">.</span><span class="n">get_height</span><span class="p">()</span> <span class="o">*</span> <span class="mf">1.01</span><span class="p">))</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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fJHddtuNAw88cIXXSpKkVbMET5K0xubMmcPQoUPZbrvt6N+/PxMmTGDWrFndeu1WW23F6NGjAdhoo40YNmwYixYtqma4kiQ1LBM8SdIaW7RoEYMHD26bbm5u7jRJu+OOO9hll1049NBD+cMf/rDC8vnz53Pfffexxx57VDVeSZIalVU0JUlrLDNXmBcR7aZHjx7Nn//8ZwYMGMD111/PkUceyWOPPda2/J///CfHHHMMZ555JhtvvHHVY5YkqRFZgidJWmPNzc0sWLCgbXrhwoUMGjSo3Tobb7wxAwYMAGD8+PEsW7aMxYsXA7Bs2TKOOeYYjj/+eI4++ujeC1ySpAZjgidJWmNjx47lscceY968eSxdupSZM2dy+OGHt1vnqaeeaivpmzNnDq+++iqbb745mckJJ5zAsGHD+OxnP1uL8CVJahhW0ZQkrbGmpibOPfdcDj74YFpaWpg8eTLDhw9n+vTpAEydOpUrr7yS73//+zQ1NbHBBhswc+ZMIoLbbruNSy+9lLe97W2MGjUKgK997WuMHz++hnskSVJ9MsGTJK0V48ePXyEpmzp1atvzU045hVNOOWWF1+2zzz6dtuGTJEk9Z4InSVptQ067rurvMX/aYVV/D0mSGoVt8CRJqjB79mx23HFHhg4dyrRp07pc7+6776Zfv35ceeWVbfO+853vMHz4cEaMGMHEiRN55ZVXeiNkSZLamOBJklRqaWnh5JNP5oYbbmDu3LnMmDGDuXPndrreqaeeysEHH9w2b9GiRZx99tncc889PPTQQ7S0tDBz5szeDL+NSaokrbtM8CRJKs2ZM4ehQ4ey3Xbb0b9/fyZMmMCsWbNWWO+cc87hmGOOYeDAge3mL1++nJdffpnly5fz0ksvrTBURG9olCRVkrR6TPAkSSotWrSIwYMHt003NzezaNGiFda5+uqr23UgA7D11lvzuc99jm222YatttqKTTbZhIMOOqhX4q7UCEmqJGn1meBJklTqrDfPiGg3/elPf5qvf/3r9OvXr9385557jlmzZjFv3jyefPJJlixZwmWXXVbVeDvTCEmqJGn12YumJEml5uZmFixY0Da9cOHCFUqw7rnnHiZMmADA4sWLuf7662lqamLZsmVsu+22bLnllgAcffTR3H777XzgAx/ovR1g7SWpm266Ke9973u57LLLen0fJEmrzwRPkqTS2LFjeeyxx5g3bx5bb701M2fO5Iorrmi3zrx589qeT5o0iXe/+90ceeSR3HXXXdx555289NJLbLDBBtx0002MGTOmt3ehIZJUSdLqM8GTJKnU1NTEueeey8EHH0xLSwuTJ09m+PDhTJ8+HWCFKo2V9thjD4499lhGjx5NU1MTu+66KyeeeGJvhd6mEZJUSdLqM8GTJKnC+PHjGT9+fLt5XSV2F198cbvp008/ndNPP71aoXVLIySpkqTVZ4InSVqnDTntuqq/x/xph1X9PSrVe5IqSVp9JniSJDWAaieqvZ2kSpJWj8MkSJIkSVKDMMGTJEmSpAZhgidJkiRJDcIET5IkSZIahAmeJEmSJDUIEzxJkiRJahAmeJIkSZLUIEzwJEmSJKlBmOBJkiRJUoMwwZMkSZKkBmGCJ0mSJEkNwgRPkiRJkhqECZ4kSZIkNQgTPEmSJElqEFVN8CLikIh4NCIej4jTVrLe2IhoiYhjqxmPJEmSJDWyqiV4EdEP+C5wKLAzMDEidu5iva8DP69WLJIkSZK0LqhmCd7uwOOZ+URmLgVmAkd0st4ngKuAp6sYiyRJkiQ1vGomeFsDCyqmF5bz2kTE1sBRwPQqxiFJkiRJ64RqJnjRybzsMH0mcGpmtqx0QxEnRsQ9EXHPM888s7bikyRJkqSG0lTFbS8EBldMNwNPdlhnDDAzIgC2AMZHxPLMvKZypcw8DzgPYMyYMR2TREmSJEkS1U3w7ga2j4htgUXABOD9lStk5ratzyPiYuBnHZM7SZIkSVL3VC3By8zlEXEKRe+Y/YALM/MPETG1XG67O0mSJElai6pZgkdmXg9c32Fep4ldZk6qZiySJEmS1OiqOtC5JEmSJKn3mOBJkiRJUoMwwZMkSZKkBmGCJ0mSJEkNwgRPkiRJkhqECZ4kSZIkNQgTPEmS1CfNnj2bHXfckaFDhzJt2rQVls+aNYuRI0cyatQoxowZw2233QbAggUL2H///Rk2bBjDhw/nrLPO6u3QJalmqjoOniRJ0upoaWnh5JNP5sYbb6S5uZmxY8dy+OGHs/POO7etc8ABB3D44YcTETz44IMcd9xxPPLIIzQ1NfHtb3+b0aNH8+KLL7Lbbrtx4IEHtnutJDUqS/AkSVKfM2fOHIYOHcp2221H//79mTBhArNmzWq3zoABA4gIAJYsWdL2fKuttmL06NEAbLTRRgwbNoxFixb17g6UVrcUEmDy5MkMHDiQESNG9GbIkuqcCZ4kSepzFi1axODBg9umm5ubO03Srr76anbaaScOO+wwLrzwwhWWz58/n/vuu4899tijqvF2prUU8oYbbmDu3LnMmDGDuXPntlvngAMO4IEHHuD+++/nwgsvZMqUKW3LJk2axOzZs3s7bEl1zgRPkiT1OZm5wrzWErpKRx11FI888gjXXHMNX/rSl9ot++c//8kxxxzDmWeeycYbb1y1WLuyJqWQAOPGjWOzzTbr1Zgl1T8TPEmS1Oc0NzezYMGCtumFCxcyaNCgLtcfN24cf/rTn1i8eDEAy5Yt45hjjuH444/n6KOPrnq8nVlbpZCS1BMmeJIkqc8ZO3Ysjz32GPPmzWPp0qXMnDmTww8/vN06jz/+eFtJ37333svSpUvZfPPNyUxOOOEEhg0bxmc/+9lahA+snVJISeopEzxJktTnNDU1ce6553LwwQczbNgwjjvuOIYPH8706dOZPn06AFdddRUjRoxg1KhRnHzyyfzwhz8kIvjtb3/LpZdeyq9+9StGjRrFqFGjuP7663t9H9a0FLIvWVVnMZdffjkjR45k5MiR7L333jzwwANty8466yxGjBjB8OHDOfPMM3sxamnd5DAJkiSpTxo/fjzjx49vN2/q1Kltz0899VROPfXUFV63zz77dFp61tsqSyG33nprZs6cyRVXXNFunccff5y3vvWtRES7Usi+pDtDVmy77bbccsstvPGNb+SGG27gxBNP5K677uKhhx7iBz/4AXPmzKF///4ccsghHHbYYWy//fY13COpsZngSZKkPmHIaddVdfvzpx1W1e13VFkK2dLSwuTJk9tKIaFIVq+66iouueQS1l9/fTbYYIO2UkiAiRMncvPNN7N48WKam5s5/fTTOeGEE3p1H6B9ZzFAW2cxlQne3nvv3fZ8zz33ZOHChQA8/PDD7LnnnrzhDW8AYN999+Xqq6/mC1/4Qi/ugbRuMcGTJEmqktUthQSYMWNGVWPrrs46i7nrrru6XP+CCy7g0EMPBWDEiBH867/+K88++ywbbLAB119/PWPGjKl6zNK6zARPkiRpLal2KST0fklkdzuLAfj1r3/NBRdc0DZg+7Bhwzj11FM58MADGTBgALvssgtNTV5+StVkJyuSJEnqUnc7i3nwwQeZMmUKs2bN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
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>This plot shows some shocking results, and will be further elaborated on immediately following this. I am unsuprised that Jett and Reyna are the most played, and appear on average more than once a game. For those that do not know, those two characters are considered "duelists," and have abilities that enable the player to have the best chance to dominate the game and control their engagements and outcomes. I am surprised that Sage also has a high pick rate, as she is one of two agents with the ability to healers in the game, and has other abilities that incentivise a more supportive playstyle. Finally I did not expect the pick rate of the bottom three to be so low, but I understand why they are last. Those three agents have a more technical and complicated kit compared to the other agents, and their niche is not as valued on most maps.</p>
<p>One last thing I will mention is that the developers know about Yoru's underperformance, and have <a href="https://playvalorant.com/en-us/news/dev/state-of-the-agents-yoru/">recently announced changes</a> to the agent.</p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[8]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Isolating the number of times an agent was picked</span>
<span class="n">char_map</span> <span class="o">=</span> <span class="n">round_data</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">round_data</span><span class="p">[</span><span class="s1">&#39;round_num&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="mi">0</span><span class="p">]</span>
<span class="n">char_map</span><span class="o">.</span><span class="n">reset_index</span><span class="p">(</span><span class="n">inplace</span> <span class="o">=</span> <span class="kc">True</span><span class="p">,</span> <span class="n">drop</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>

<span class="c1">#spliting the isolated data based on map.</span>
<span class="n">char_maps</span> <span class="o">=</span> <span class="n">char_map</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="s1">&#39;map&#39;</span><span class="p">)</span>

<span class="c1">#Creating a pick rate per map for each character, and storing it in a new dataframe</span>
<span class="n">char_map_total</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">()</span>
<span class="k">for</span> <span class="n">maps</span><span class="p">,</span><span class="n">table</span> <span class="ow">in</span> <span class="n">char_maps</span><span class="p">:</span>
    <span class="n">agent_map</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">round_data</span><span class="p">[</span><span class="s1">&#39;agent&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">unique</span><span class="p">(),</span> <span class="n">columns</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;agent&#39;</span><span class="p">])</span>
    <span class="n">agent_map</span><span class="p">[</span><span class="s1">&#39;map&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">maps</span>
    <span class="n">agent_map</span><span class="p">[</span><span class="s1">&#39;pick_rate&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="mf">0.0</span>
    <span class="k">for</span> <span class="n">index</span><span class="p">,</span> <span class="n">row</span> <span class="ow">in</span> <span class="n">agent_map</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
        <span class="n">agent_map</span><span class="o">.</span><span class="n">at</span><span class="p">[</span><span class="n">index</span><span class="p">,</span> <span class="s1">&#39;pick_rate&#39;</span><span class="p">]</span><span class="o">=</span> <span class="p">(</span><span class="n">table</span><span class="o">.</span><span class="n">agent</span><span class="o">.</span><span class="n">values</span><span class="o">==</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;agent&#39;</span><span class="p">])</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span><span class="o">/</span><span class="nb">len</span><span class="p">(</span><span class="n">table</span><span class="p">[</span><span class="s1">&#39;match_id&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">unique</span><span class="p">())</span>                                
    <span class="n">char_map_total</span> <span class="o">=</span> <span class="n">char_map_total</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">agent_map</span><span class="p">)</span>

<span class="c1">#Creating a heatmap to display the results</span>
<span class="n">pivot</span> <span class="o">=</span> <span class="n">char_map_total</span><span class="o">.</span><span class="n">pivot</span><span class="p">(</span><span class="n">index</span><span class="o">=</span><span class="s1">&#39;agent&#39;</span><span class="p">,</span> <span class="n">columns</span><span class="o">=</span><span class="s1">&#39;map&#39;</span><span class="p">,</span> <span class="n">values</span><span class="o">=</span><span class="s1">&#39;pick_rate&#39;</span><span class="p">)</span>
<span class="n">f</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">12</span><span class="p">,</span><span class="mi">9</span><span class="p">))</span>
<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s1">&#39;Agent</span><span class="se">\&#39;</span><span class="s1">s Pickrate Heatmap&#39;</span><span class="p">)</span>
<span class="n">sns</span><span class="o">.</span><span class="n">heatmap</span><span class="p">(</span><span class="n">pivot</span><span class="p">,</span><span class="n">cmap</span> <span class="o">=</span> <span class="s2">&quot;Reds&quot;</span><span class="p">,</span> <span class="n">square</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span> <span class="n">linewidths</span><span class="o">=.</span><span class="mi">5</span><span class="p">,</span> <span class="n">ax</span><span class="o">=</span><span class="n">ax</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt">Out[8]:</div>




<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain">
<pre>&lt;AxesSubplot:title={&#39;center&#39;:&#34;Agent&#39;s Pickrate Heatmap&#34;}, xlabel=&#39;map&#39;, ylabel=&#39;agent&#39;&gt;</pre>
</div>

</div>

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>This <a href="https://seaborn.pydata.org/generated/seaborn.heatmap.html">heatmap</a> offers a more in depth view of each agent's pick rate. From it, we can discern the most "popular" maps for each agent. An example of this is viper, who on most maps has a modest pick rate, except for Breeze, where she is picked on average more than once per game. From a gameplay point of view, this can be justified due to Viper's ability to block vision every round in both a line and sphere being extremely useful in a map that has long and open areas. This same sense of using an agent's abilities to reason that map's pick rate is applicable to the rest of the cases, and truly highlights the niche that agents hold.</p>

</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h4 align="center">The Loading Screen for the Map Breeze</h4>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><img src="Breeze.png" width=711 height=400 align="center"/></p>

</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h2 align="center">Recommending a Weapon</h2>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>This section encompases the linear regression and machine learning portion of the tutorial. In this section, machine learning will be used to attempt to answer the aforementioned question: "What weapon should I buy this round?"</p>
<p>In order to create a model from our data, the categorical variables must be numerized. <a href="https://www.analyticsvidhya.com/blog/2015/11/easy-methods-deal-categorical-variables-predictive-modeling/">There are numerous ways to quantify categorical variables</a>, but for this data set, I chose <a href="https://www.educative.io/blog/one-hot-encoding">https://stats.oarc.ucla.edu/other/mult-pkg/faq/general/faqwhat-is-dummy-coding/</a>. This method is the least intensive given that I have many different types and levels of my categorical variables, and I readily found an applicable function to transform my data. Credit to <a href="https://stackoverflow.com/a/37293283">Wboy</a> for the dummyEncode function.</p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[9]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Auto encodes any dataframe column of type category,object, or boolean.</span>
<span class="k">def</span> <span class="nf">dummyEncode</span><span class="p">(</span><span class="n">df</span><span class="p">):</span>
    <span class="c1"># Filters through dataframe and recognizes categorical variables</span>
    <span class="n">columnsToEncode</span> <span class="o">=</span> <span class="nb">list</span><span class="p">(</span><span class="n">df</span><span class="o">.</span><span class="n">select_dtypes</span><span class="p">(</span><span class="n">include</span><span class="o">=</span><span class="p">[</span><span class="s1">&#39;category&#39;</span><span class="p">,</span><span class="s1">&#39;object&#39;</span><span class="p">,</span><span class="s1">&#39;boolean&#39;</span><span class="p">]))</span>
    <span class="n">le</span> <span class="o">=</span> <span class="n">LabelEncoder</span><span class="p">()</span>
    <span class="k">for</span> <span class="n">feature</span> <span class="ow">in</span> <span class="n">columnsToEncode</span><span class="p">:</span>
        <span class="k">try</span><span class="p">:</span>
            <span class="n">df</span><span class="p">[</span><span class="n">feature</span><span class="p">]</span> <span class="o">=</span> <span class="n">le</span><span class="o">.</span><span class="n">fit_transform</span><span class="p">(</span><span class="n">df</span><span class="p">[</span><span class="n">feature</span><span class="p">])</span>
        <span class="k">except</span><span class="p">:</span>
            <span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Error encoding &#39;</span><span class="o">+</span><span class="n">feature</span><span class="p">)</span>
    <span class="k">return</span> <span class="n">df</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[10]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Creating a copy of round_data for use in model creation</span>
<span class="n">round_train</span> <span class="o">=</span> <span class="n">dummyEncode</span><span class="p">(</span><span class="n">round_data</span><span class="o">.</span><span class="n">copy</span><span class="p">(</span><span class="n">deep</span> <span class="o">=</span> <span class="kc">True</span><span class="p">))</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[11]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Only keeping the rounds where the player one, to build a model that can predict a winning recommendation</span>
<span class="n">round_train</span> <span class="o">=</span> <span class="n">round_train</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">round_train</span><span class="p">[</span><span class="s1">&#39;roundwon&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="mi">1</span><span class="p">]</span>

<span class="c1">#removing the unnecesairy data that will not be used in making the model</span>
<span class="n">x</span> <span class="o">=</span> <span class="n">round_train</span><span class="o">.</span><span class="n">drop</span><span class="p">([</span><span class="s1">&#39;roundwon&#39;</span><span class="p">,</span><span class="s1">&#39;match_id&#39;</span><span class="p">,</span><span class="s1">&#39;kills&#39;</span><span class="p">,</span><span class="s1">&#39;score&#39;</span><span class="p">,</span><span class="s1">&#39;weapon&#39;</span><span class="p">],</span> <span class="n">axis</span> <span class="o">=</span> <span class="mi">1</span><span class="p">)</span>

<span class="c1">#partitioning the data into a training and test set</span>
<span class="n">y</span> <span class="o">=</span> <span class="n">round_train</span><span class="p">[</span><span class="s1">&#39;weapon&#39;</span><span class="p">]</span>
<span class="n">X_train</span><span class="p">,</span> <span class="n">X_test</span><span class="p">,</span> <span class="n">y_train</span><span class="p">,</span> <span class="n">y_test</span> <span class="o">=</span> <span class="n">model_selection</span><span class="o">.</span><span class="n">train_test_split</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">,</span> <span class="n">test_size</span><span class="o">=.</span><span class="mi">3</span><span class="p">)</span>
<span class="n">X_train</span><span class="p">[</span><span class="s1">&#39;weapon&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">y_train</span>
<span class="n">X_test</span><span class="p">[</span><span class="s1">&#39;weapon&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">y_test</span>

<span class="c1">#creating and hypothesis testing the model.</span>
<span class="n">linr</span> <span class="o">=</span> <span class="n">smf</span><span class="o">.</span><span class="n">ols</span><span class="p">(</span><span class="n">formula</span> <span class="o">=</span> <span class="s1">&#39;weapon ~ C(agent)+C(map)+money+round_num&#39;</span><span class="p">,</span> <span class="n">data</span><span class="o">=</span><span class="n">X_train</span><span class="p">)</span><span class="o">.</span><span class="n">fit</span><span class="p">()</span>
<span class="nb">print</span><span class="p">(</span><span class="n">linr</span><span class="o">.</span><span class="n">summary</span><span class="p">())</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>                            OLS Regression Results                            
==============================================================================
Dep. Variable:                 weapon   R-squared:                       0.210
Model:                            OLS   Adj. R-squared:                  0.210
Method:                 Least Squares   F-statistic:                     730.0
Date:                Mon, 20 Dec 2021   Prob (F-statistic):               0.00
Time:                        11:42:01   Log-Likelihood:            -1.8664e+05
No. Observations:               65996   AIC:                         3.733e+05
Df Residuals:                   65971   BIC:                         3.736e+05
Df Model:                          24                                         
Covariance Type:            nonrobust                                         
==================================================================================
                     coef    std err          t      P&gt;|t|      [0.025      0.975]
----------------------------------------------------------------------------------
Intercept          6.9241      0.109     63.325      0.000       6.710       7.138
C(agent)[T.1]     -0.0891      0.155     -0.576      0.565      -0.392       0.214
C(agent)[T.2]     -0.1099      0.131     -0.841      0.401      -0.366       0.146
C(agent)[T.3]     -1.3669      0.122    -11.241      0.000      -1.605      -1.129
C(agent)[T.4]     -0.4582      0.133     -3.458      0.001      -0.718      -0.198
C(agent)[T.5]     -0.2829      0.106     -2.658      0.008      -0.492      -0.074
C(agent)[T.6]     -0.0598      0.147     -0.406      0.685      -0.348       0.229
C(agent)[T.7]     -0.3255      0.116     -2.810      0.005      -0.553      -0.099
C(agent)[T.8]     -0.1128      0.119     -0.950      0.342      -0.345       0.120
C(agent)[T.9]     -0.1658      0.133     -1.248      0.212      -0.426       0.095
C(agent)[T.10]    -0.0535      0.113     -0.472      0.637      -0.276       0.169
C(agent)[T.11]     0.5274      0.105      5.012      0.000       0.321       0.734
C(agent)[T.12]    -0.0644      0.106     -0.609      0.542      -0.272       0.143
C(agent)[T.13]    -0.2014      0.121     -1.667      0.095      -0.438       0.035
C(agent)[T.14]    -0.2325      0.113     -2.051      0.040      -0.455      -0.010
C(agent)[T.15]    -0.2324      0.116     -2.003      0.045      -0.460      -0.005
C(agent)[T.16]    -0.3895      0.174     -2.233      0.026      -0.731      -0.048
C(map)[T.1]        0.2678      0.059      4.561      0.000       0.153       0.383
C(map)[T.2]        0.0284      0.061      0.465      0.642      -0.091       0.148
C(map)[T.3]        0.0838      0.065      1.290      0.197      -0.044       0.211
C(map)[T.4]        0.0345      0.058      0.597      0.551      -0.079       0.148
C(map)[T.5]        0.3099      0.058      5.308      0.000       0.195       0.424
C(map)[T.6]       -0.0493      0.058     -0.856      0.392      -0.162       0.064
money              0.0009   7.63e-06    122.136      0.000       0.001       0.001
round_num          0.0584      0.002     23.589      0.000       0.054       0.063
==============================================================================
Omnibus:                     4047.847   Durbin-Watson:                   1.987
Prob(Omnibus):                  0.000   Jarque-Bera (JB):             4783.348
Skew:                          -0.653   Prob(JB):                         0.00
Kurtosis:                       2.817   Cond. No.                     1.27e+05
==============================================================================

Notes:
[1] Standard Errors assume that the covariance matrix of the errors is correctly specified.
[2] The condition number is large, 1.27e+05. This might indicate that there are
strong multicollinearity or other numerical problems.
</pre>
</div>
</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>From this summary, we can understand the p-values of each coefficient. There are many significant (p&lt;.05) coefficients, especially money and round_num, but I am worried that the results for maps and agents may negatively impact this model. It is extremely likely that this model was unable to create an accurate model, given that it put such significance on certain operators and maps, relative to money and round_num.</p>
<p>To get a better understanding of the accuracy of this model, the following code creates a violin plot of the residuals</p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[12]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#beginning the check on the test set</span>
<span class="n">expected</span> <span class="o">=</span> <span class="n">linr</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">X_test</span><span class="p">)</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[13]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Creating a dataframe to hold the residuals</span>
<span class="n">residuals</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">()</span>
<span class="n">residuals</span><span class="p">[</span><span class="s1">&#39;expected&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">expected</span>
<span class="n">residuals</span><span class="p">[</span><span class="s1">&#39;actual&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">y_test</span>
<span class="n">residuals</span><span class="p">[</span><span class="s1">&#39;residuals&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="mf">0.0</span>
<span class="k">for</span> <span class="n">index</span><span class="p">,</span><span class="n">row</span> <span class="ow">in</span> <span class="n">residuals</span><span class="o">.</span><span class="n">iterrows</span><span class="p">():</span>
    <span class="n">residuals</span><span class="o">.</span><span class="n">at</span><span class="p">[</span><span class="n">index</span><span class="p">,</span><span class="s1">&#39;residuals&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">row</span><span class="p">[</span><span class="s1">&#39;actual&#39;</span><span class="p">]</span><span class="o">-</span><span class="n">row</span><span class="p">[</span><span class="s1">&#39;expected&#39;</span><span class="p">]</span>

<span class="c1">#plotting the residuals in a violin plot</span>
<span class="n">fig</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">15</span><span class="p">,</span> <span class="mi">7</span><span class="p">))</span>
<span class="n">ax</span><span class="o">.</span><span class="n">violinplot</span><span class="p">(</span><span class="n">residuals</span><span class="p">[</span><span class="s2">&quot;residuals&quot;</span><span class="p">],</span><span class="n">widths</span><span class="o">=</span><span class="mi">4</span><span class="p">,</span><span class="n">showmeans</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_xlabel</span><span class="p">(</span><span class="s2">&quot;&quot;</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_ylabel</span><span class="p">(</span><span class="s2">&quot;Residuals&quot;</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s2">&quot;Graph of the Residuals for the Actual Value of the Test set Minus the Model&#39;s Predictions for the Test Set&quot;</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_xticklabels</span><span class="p">([])</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>




<div class="jp-RenderedImage jp-OutputArea-output ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>

</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[14]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="n">residuals</span><span class="p">[</span><span class="s2">&quot;residuals&quot;</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">())</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>-0.001545438466541512
</pre>
</div>
</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>This violin plot shows disappointing results. Generally speaking, due to the categorical nature of weapon, most of the spread of the data is irrelevant, and the only thing that matters is how much data is close to 0. Being close to 0 means that the model almost picked the right weapon, whereas being at least 1 unit away means the model picked completely wrong. With that in mind, most of the data is at least 1 unit away from 0, meaning that our model's predictiveness is not good. This is likely due to the model having difficulties fitting a linear model among the multiple different variables.</p>
<p>The following example highlights one of the issues with the model</p>

</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs  ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[15]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#quick creation of a dictionary to understand the model&#39;s output</span>
<span class="n">dummy_to_weapon</span> <span class="o">=</span> <span class="nb">dict</span><span class="p">(</span><span class="nb">zip</span><span class="p">(</span><span class="n">round_train</span><span class="p">[</span><span class="s1">&#39;weapon&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">unique</span><span class="p">(),</span> <span class="n">round_data</span><span class="p">[</span><span class="s1">&#39;weapon&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">unique</span><span class="p">()))</span>
</pre></div>

     </div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell   ">
<div class="jp-Cell-inputWrapper">
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In&nbsp;[16]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
     <div class="CodeMirror cm-s-jupyter">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#generating a prediction that makes no sense in context of the game</span>
<span class="n">unexpected_result</span> <span class="o">=</span> <span class="n">x</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">unexpected_result</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;The Model predicted to pick: &quot;</span><span class="o">+</span><span class="n">dummy_to_weapon</span><span class="p">[</span><span class="nb">round</span><span class="p">(</span><span class="n">linr</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">unexpected_result</span><span class="p">)[</span><span class="mi">0</span><span class="p">])])</span>
</pre></div>

     </div>
</div>
</div>
</div>

<div class="jp-Cell-outputWrapper">


<div class="jp-OutputArea jp-Cell-outputArea">

<div class="jp-OutputArea-child">

    
    <div class="jp-OutputPrompt jp-OutputArea-prompt"></div>


<div class="jp-RenderedText jp-OutputArea-output" data-mime-type="text/plain">
<pre>   agent  map  money  round_num
0      7    6    800          0
The Model predicted to pick: Ares
</pre>
</div>
</div>

</div>

</div>

</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>This prediction is impossible, as the Ares costs 1550 credits. There is no way for a player to buy this weapon with only 800 credits. At the current time, I do not know of a way to force the model to consider the costs of a weapon when predicting, and is a point of future work.</p>

</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><img src="Valorant.png" width=711 height=400 align="center"/></p>

</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<h2 align="center">Conclusion</h2>
</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p>Although this tutorial produced a model that does not adequately recommend a weapon, it still fully represented the data science pipeline. You got to explore how data is collected, modified, explored, and used to create models to help determine action and policy. Additionally, you got to learn some cool facts about Valorant that are supported by data, which can hopefully be used to help you play different agents or use different weapons. Finally, there is still room to improve this model, and if I ever get it to actually work, this page will be updated.</p>
<p>Thanks for reading this tutorial!</p>

</div>
</div>
<div class="jp-Cell-inputWrapper"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput " data-mime-type="text/markdown">
<p><h2 align="center">Required Legal Statement</h2>
    "The Value of a Weapon in Valorant" isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games, and all associated properties are trademarks or registered trademarks of Riot Games, Inc.</p>

</div>
</div>
</body>







</html>

