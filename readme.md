#About Sublime Text 3

:mag: 主要的內容是介紹熱門、實用的Packages，與快捷鍵

|#|Catalog|
|---|---|
|1|[Installation](#installation)|
|2|[Basic Operation](#basic-operation)|
|3|[Recommended Packages](#recommended-packages)|
|4|[Hot Keys](#hot-keys)|

###Installation:
1. [Pakage control](https://packagecontrol.io/installation)
2. [Node](https://nodejs.org/en/) (with npm)

###Basic Operation:
1. Save:  `ctrl+ s`
2. Comment:  `ctrl+ /`
3. Undo: `ctrl+ z`
4. Redo: `ctrl+ shift+ z`

###Recommended Packages:
1. General use

  |Packages|Description / How to use|
  |---|---|
  |AdvanceNewFile|新增檔案，`ctrl+ alt+ n`|
  |Alignment|自動對齊，`ctrl+ alt+ a`|
  |All Autocomplete|Extends the default autocomplete to find matches in all open files. By default Sublime only considers words found in the current file.|
  |AutoFileName|自動路徑提示|
  |Bracket Highlighter|提示相對應的括弧|
  |ChineseLoremIpsum|自動產出中文(切換`ctlorem/cslorem`)，`clorem + alt + c`|
  |ConvertToUTF8|可顯示中文、韓文、日文；因為快捷鍵與ColorPicker衝突，所以要設定快捷鍵為`ctrl+ alt+ shift+ c`；另外，可將原本預設為簡體字改為繁體|
  |FileDiffs||
  |Git||
  |GitGutter|在 sublime 顯示 git diff|
  |HTML-CSS-JS-Pretiffy|存檔自動排版 html, css, js；要先確認安裝nodejs完畢後，進入此套件的`Set 'node' Path`將"`format_on_save": false,`改成`"format_on_save": true,`；之後確認"node_path"內的路徑是否正確|
  |Markdown Preview|預覽 Markdown，`alt + m`|
  |MarkdownEditing|Markdown syntax|
  |Material Theme||
  |PackageResourceViewer|view package resources|
  |SideBarEnhancements|提升邊攔作用|
  |SublimeCodeIntel|多語言提示 (smart autocomplete)|
  |SublimeLinter|偵錯 code|
  |SublimeLinter-contrib-eslint|偵錯 javascript, need to install `$ npm install -g eslint`|
  |SublimeLinter-csslint|偵錯 css, need to install `$ npm install -g csslint`|
  |Terminal|快捷鍵開啟Terminal，`ctrl + shift + t`|
  |TrailingSpacers|刪除多於空白|

2. For HTML

  |Packages|Description / How to use|
  |---|---|
  |Emmet|Snippets|
  |HTML5|HTML syntax|
3. For CSS

  |Packages|Description / How to use|
  |---|---|
  |Color Highlighter|在 sublime 顯示顏色|
  |ColorPicker|跳出面板選顏色，`ctrl+ shift+ c`|
  |CSS3|CSS3 syntax|
  |CSScomb|CSS coding style formatter|
  |Sass|Sass syntax|
  |SCSS|SCSS syntax|
3. For JavaScript

  |Packages|Description / How to use|
  |---|---|
  |Babel|ES6/7 to ES5|
  |Babel Snippets|Babel Snippets|
  |JavaScriptNext - ES6 Syntax|ES6 Syntax|
  |jQuery|jQuery Snippets|
  |JSX|React syntax|
  |Nodejs|node snippets and bindings|
  |Vue Syntax Hightlight|Vue syntax|
  |Pug|Pug syntax|

###Hot Keys:
1. Goto Anything (Navigation)

  |Description|hot key|
  |---|---|
  |Goto Anything|`Ctrl + P`|
  |Goto Symbol|`Ctrl + R`|
  |Goto Line|`Ctrl + G`|

2. Editing text

  |Description|hot key|
  |---|---|
  |Insert line before / after|`Ctrl + Shift + Return` / `Ctrl + Return`|
  |Copy line / Paste from history|`Ctrl + C` / `Ctrl + K, Ctrl + V`|
  |Delete to beginning / end|`Ctrl + Shift + Backspace` / `Ctrl + K`|
  |Delete / Cut a line|`Ctrl + Shift + K` / `Ctrl + X`|
  |Soft Undo / Redo|`Ctrl + U` / `Ctrl + Shift + U`|
  |Upper / lower case|`Ctrl + K, Ctrl + U` / `Ctrl + K, Ctrl + L`|
  |Joining Lines|`Ctrl + J`|
  |Bubble the line up / down|`Ctrl + Shift + up` / `Ctrl + Shift + down`|
  |Sort a line|`F9`|
  |Duplicating a line|`Ctrl + Shift + D`|
  |Indent - Unindent|`Ctrl + ]`, `Ctrl + [`|
  |Commenting a line / multiple lines|`Ctrl + /` / `Ctrl + Shift + /`|
  |Close HTML tag|`Alt + .`|
  |Wrap line at ruler|`Alt + Q`|
  |Transpose|`Ctrl + T`|
3. Selection

  |Description|hot key|
  |---|---|
  |Multiple selection|`Ctrl + clicks at multiple places`|
  |Column Selection|`Ctrl + Alt + (up|down)` or `Shift + right-click` / `Esc` for going back to single|
  |Split block of selection into multiple lines|`Ctrl + Shift + L`|
  |Select word with multiple occurrences|`Ctrl + D`, *Pro-tip*: select the initial word using the `Ctrl + D` shortcut. This switches the matching from fuzzy matching to word boundary matching|
  |Quick skip|`Ctrl + K`|
  |Selecting a line|`Ctrl + L`|
  |Expand selection to brackets|`Ctrl + Shift + M`|
  |Expand selection to indentation|`Ctrl + Shift + J`|
  |Expand selection to scope|`Ctrl + Shift + Space`
  |Select digit|`Shift + (up|down|left|right)`|
  |Select words|`Ctrl + Shift + left` / `Ctrl + Shift + right`|
4. Navigation

  |Description|hot key|
  |---|---|
  |Goto symbol in project|`Ctrl + Shift + R`|
  |Goto definition|`F12`|
  |Goto beginning / end of a line|`Home` / `End`|
  |Goto matching bracket|`Ctrl + M`|
  |Move back / forward in history|`Alt + -` / `Alt + Shift + -`|
  |Code fold / unfold|`Ctrl + Shift + [` / `Ctrl + Shift + ]`|
5. Find

  |Category|Description|hot key|
  |---|---|---|
  |**Find**|Find|`Ctrl + F`|
  ||Find next|`F3`|
  ||Find previous|`Shift + F3`|
  ||Find all|`Alt + Return` (while find window is open)|
  ||Use selection to find|`Ctrl + E`|
  |**Incremental find**|Incremental find|`Ctrl + I`|
  ||Incremental find previous|`Ctrl + Shift + I`|
  ||Find all with incremental find|`Alt + Return` (while the panel is open)|
  |**Replace**|Replace panel|`Ctrl + H`|
  ||Replace next|`Ctrl + Shift + H`|
  ||Replace all|`Ctrl + Alt + Return` (Only when replace panel is open)|
  ||Add selection to replace|`Ctrl + Shift + E`|
  |**Quick find**|Quick find|`Ctrl + F3`|
  ||Quick find previous|`Ctrl + Shift + F3`|
  ||Quick find all|`Alt + F3`|
  |**Find in project**|Find in project|`Ctrl + Shift + F`|

6. Others

  |Description|hot key|
  |---|---|
  |Opening User settings|`^ + ,`|
  |Python Console|`^ + Backticks` / `Ctrl + Backticks`|
  |Command Palette|`Ctrl + Shift + P`|
  