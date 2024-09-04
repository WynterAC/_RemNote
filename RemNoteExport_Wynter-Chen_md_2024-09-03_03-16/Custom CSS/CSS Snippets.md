- > List of CSS Snippets Tags:
    - kanban
    - blockquote
    - blockquote-tree
    - divider
    - Kanban2
    - blockquote
    - blockquote-tree
    - tree
    - table
    - Table Columns
    - Columns
- RemNote Library 
    - ^^Columns (columns) ^^ 
        - Tags
            - columns
        - Demo
            - Column Layout   #columns
                - left
                    - your
                    - content
                - right
                    - like in notion
                - but more
        - Code 
            - ```css
.tree-node-container[data-rem-container-tags~="columns"] > .TreeNode {
    display: flex;
}

.tree-node-container[data-rem-container-tags~="columns"]
    > .TreeNode
    > .tree-node-container {
    /* equal width columns */
    flex: 1 1 0;
    /* more based on content */
    /* flex: 1 1 auto; */
}
```
- Remnote Library 2.0
    - Table
        - Table Demo  
            - 
        - Tags
            - Table Columns
            - Table 
        - Compare with main account.
        - code
            - ```css
.tree-node-container[data-rem-tags~=table] > .TreeNode {
  display: grid;
  /* auto jumps when toggling/writing rems */ 
  /* grid-template-columns: auto auto auto; */
  grid-auto-rows: 1fr;
}

.tree-node-container[data-rem-tags~=table] > .TreeNode > .tree-node-container {
  border: 1px solid black;
}

/* remove indentation marker */
.tree-node-container[data-rem-tags~=table] .TreeNode {
  border-left: unset !important;
}

.tree-node-container[data-rem-tags~=table] > .TreeNode > ._tree-node-container > .parent-node {
  border-bottom: 1px solid black;
  font-weight: bold;
  background-color: rgba(0,0,0,0.05);
}

#hierarchy-editor .tree-node-container[data-rem-tags~=table] > .TreeNode > .tree-node-container > .TreeNode {
  margin-left: 0;
  padding-left: 0;
}

.tree-node-container[data-rem-tags~=table] > .TreeNode:not(:hover) .rem-bullet__container {
  visibility: hidden;
}

.tree-node-container[data-rem-tags~=table] > .TreeNode > .tree-node-container > .parent-node {
  float: left;
  width: 100px;
}

.tree-node-container[data-rem-tags~=table] > .TreeNode > .tree-node-container > .TreeNode {
  display: flex;
  flex-direction: row;
}
.tree-node-container[data-rem-tags~=table] > .TreeNode > .tree-node-container > .TreeNode > .tree-node-container {
  flex: 1 1 0;
}
```
        -  #Table
    - ^^Rating, Reviews an/d scales^^ 
        - Combine with sliders
            - There are multiple options to lay out slider and value.
                - Rating
                    - Slider changes the rating tag
                    - <slider>
                - Multi value
                    - <slider|rating> shows multiple people
                        - Each child is a value for a person.
                        - H: 9
                        - L: 7
                - Real Multi user
                    - Have a token somewhere in the knowledge base, and sync now over own knowledge base.
                    - Use api keys
                - <slider|rating>
                    - value (data store), or even on same line, but this can be hidden
                    - show slider on hover, else rating
        - Tags
            - one
            - two
            - three
            - four
            - five
        - Demo
            - Meh.
            - Ok...
            - nice enough
            - pretty good
            - Awesome! #five
    - Rem Reference
        - ```css
 .rem-indented-indicator {
  display: none;
}
.gray {
  display: none;
}
.join-arrow {
  display: none;
}
``` 
    - Sticky
        - Tags
            - _sticky
        - ```css
[data-rem-container-tags~="sticky"] {
  position: sticky;
  top: 0;
  background: white;
  z-index: 10;
}
```
    - Divider (^^Divider^^)
        - Tags
            - divider
        - Demo
            - above
            - text makes not much sense here 😄 #divider
            - below
        - Code
            - ```css
[data-rem-tags~="divider"]:not(:focus-within) {
    color: transparent;
    position: relative;
}

[data-rem-tags~="divider"]:not(:focus-within)
    .rem-bullet__container {
    display: none;
}

[data-rem-tags~="divider"]:not(:focus-within)
    .hierarchy-editor__tag-bar {
    display: none;
}

[data-rem-tags~="divider"]:not(:focus-within):before {
    content: " ";
    display: block;
    position: absolute;
    width: 100%;
    top: 50%;
    border-bottom: var(--divider-style, 1px solid black);
}
```
        - divider Customization
            - ```css
:root {
    --divider-style: 1px solid black;
}
```
- Browneyedsoul GitLibrary
    -  __Browneyedsoul Code Import (ALL)__  
        - ```css
/*Tricks */
    @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Notion%20like%20Callout%20Rem.css");
  /* Modern Divider */
    @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Modern%20Divider.css"); 
  /* Active Recall */
    @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Active%20Recall.css");
   /* @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Active%20Recall2.css"); */
   /* @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Active%20Recall3.css"); */
  /* Rem Planner */
    @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Planner.css");
  /* Rem Tree */
    @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Rem%20Tree.css");
  /* Blockquote */
    @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Blockquote.css");
  /* Modern Table Row */
    @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Modern%20Table%20Row.css");
  /* Modern Table Column */
    @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Modern%20Table%20Column.css");
  /* Modern Kanban */
    @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Modern%20Kanban.css");
    @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Modern%20Kanban2.css");
  /* Strikethrough Workaround */
    @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Strikethrough.css");
``` 
    - Editor Mode 
        - Branch Emphasizing Editor /Mode(need to be polished)
            - ```css
  /* @import url("https―/browneyedsoul.github.io/RemNote-CSS-Library/"); *//
```
        - Notion like No Bullet Editor Mode 
            - ```css
 /* Notion like No Bullet Editor Mode */
  @import url("https―/browneyedsoul.github.io/RemNote-CSS-Library/Notion%20like%20No%20Bullet%20Editor%20Mode.css"); er.css");
```
        - Tables 
            - **Modern Table Column** 
                - ```css
/* Modern Table Column */
  @import url("https―/browneyedsoul.github.io/RemNote-CSS-Library/Modern%20Table%20Column.css");
```
            - **Modern Table Row** 
                - ```css
/* Modern Table Row */
  @import url("https―/browneyedsoul.github.io/RemNote-CSS-Library/Modern%20Table%20Row.css");
```
    - **Utilities  ** 
        - Strikethrough workaround
            - ```css
/* Strikethrough Workaround */
  @import url("https―/browneyedsoul.github.io/RemNote-CSS-Library/Strikethrough.css");
```
        - Modern Scrollable Codeblock
            - ```css
/* Modern Scrollable Codeblock */
  @import url("https―/browneyedsoul.github.io/RemNote-CSS-Library/Modern%20Scrollable%20Code%20Block.css");
```
        - Modern Table Column (^^Table^^)
            - Tag Name : `Table`
            - ```css
 @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Modern%20Table%20Column.css");
``` 
        - Notion like Callout Rem (^^callout^^)  
            - ```css
@import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Notion%20like%20Callout%20Rem.css");
``` 
        - Modern Kanban 2 (^^Kanban2^^)
            - ```css
@import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Modern%20Kanban2.css"); 
``` 
                -  #Tables  #Kanban2
                    - 1  
                        - -1
                        - 2
                        - 3
                        - 
                    - 2 
                        - 2.2
                        - 2.3
                        - 2.4
                    - 3
                        - 3.1 
                        - 3.2
        - RemTree (^^Tree^^, ^^Treec^^ ) 
            - Tag Name : `Tree` , `Treec`
            - ```css
 @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Rem%20Tree.css");
``` 
        - Active Recall  
            - ```css
/* Active Recall */
    @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Active%20Recall.css");
   /* @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Active%20Recall2.css"); */
   /* @import url("https://browneyedsoul.github.io/RemNote-CSS-Library/Active%20Recall3.css"); */
``` 
        - Backlink Declutter 
            - ```css
 [data-rem-container-tags~="remover"] .animate-zoom-into-bullet #show-embedded-search-button,
[data-rem-container-tags~="remover"] .animate-zoom-into-bullet #AutomaticSearchPortals,
[data-rem-container-tags~="remover"] .rem-container--embedded-search-stub {
  display: none !important;
}
``` 
- Hannes Frank CSS Snippet   l
    - Kanban Board (#kanban)
        - Code
            - ```css
.tree-node-container[data-rem-container-tags~=kanban] > .TreeNode {
  display: flex;
  /* auto jumps when toggling/writing rems */ 
  /* grid-template-columns: auto auto auto; */
  background-color: lightgrey;
  border-radius: 3px;
  padding-left: 0 !important;
}

.tree-node-container[data-rem-container-tags~=kanban] > .TreeNode > .tree-node-container {
  /* equal width columns */
  flex: 1 1 0;
  /* more based on content */
  /* flex: 1 1 auto; */
  background-color: rgb(160, 170, 256);
  margin: 6px;
  border-radius: 3px;
  position: relative;
  overflow: hidden;
}

.tree-node-container[data-rem-container-tags~=kanban] > .TreeNode > .tree-node-container:not(:first-child) {
  margin-left: 0;
}

/* bullet point only on hover */
.tree-node-container[data-rem-container-tags~=kanban] > .TreeNode .tree-node-container > div:first-child:not(:hover) .rem-bullet__container {
  visibility: hidden;
}

.tree-node-container[data-rem-container-tags~=kanban] > .TreeNode > .tree-node-container > div:first-child {
  background-color: rgba(0, 0, 0, 0.09);
  margin: 0;
  border-bottom: 1px solid grey;
}

.tree-node-container[data-rem-container-tags~=kanban] > .TreeNode > .tree-node-container > .TreeNode {
  margin: 0 !important;
  padding: 0 !important;
  border: unset !important;
}

/* Task cards */
.tree-node-container[data-rem-container-tags~=kanban] > .TreeNode > .tree-node-container > .TreeNode > .tree-node-container {
  background-color: white;
  margin: 5px;
  border-radius: 2px;
  box-shadow: 0 0 1px 0;
}

/* Drag & Drop bullets */
.tree-node-container[data-rem-container-tags~=kanban] > .TreeNode > .tree-node-container > .TreeNode > .tree-node-container > div:first-child .rem-bullet__container .rem-bullet {
  width: 100%;
  height: 100%;
  background-color: lightgrey;
  border-radius: 0;
  border: unset;
}

.tree-node-container[data-rem-container-tags~=kanban] > .TreeNode > .tree-node-container > .TreeNode > .tree-node-container > div:first-child .rem-bullet__container .rem-bullet:before {
  content: '';
}

.tree-node-container[data-rem-container-tags~=kanban] > .TreeNode > .tree-node-container > .TreeNode > .tree-node-container > div:first-child .rem-bullet__container {
  height: 100%;
  width: 20px;
  top: 0;
  left: 0;
  margin-top: 0 !important;
}

.tree-node-container[data-rem-container-tags~=kanban] > .TreeNode > .tree-node-container > .TreeNode > .tree-node-container > div:first-child .rem-text {
  padding-left: 25px;
  margin-left: 0;
}

.tree-node-container[data-rem-container-tags~=kanban] > .TreeNode > .tree-node-container:nth-child(1) {
  background-color: rgb(256, 200, 160);
}

.tree-node-container[data-rem-container-tags~=kanban] > .TreeNode > .tree-node-container:nth-child(2) {
  background-color: rgb(256, 256, 190);
}

.tree-node-container[data-rem-container-tags~=kanban] > .TreeNode > .tree-node-container:nth-child(3) {
  background-color: rgb(200, 256, 190);
}
```
        - Tags
            - ` kanban` 
        - Demo
            - My Kanban Board  #Tags #Kanban2
                - Todo
                    - Polish Kanban Board
                    - Write Essay
                - Doing
                    - Publish Kanban Board
                - Done
                    - Make Kanban Board
                - Archive
                    - Exercise
    - Column Layout (#columns)
        - Show children of a rem next to each other.
        - id: com.github.hannesfrank.remnote-library.column-layout
        - version: 0.1.0
        - [Homepage](https://github.com/hannesfrank/remnote-library/tree/master/public/scrolls/column-layout)
        - [Report Problem or Suggest Improvement](https://github.com/hannesfrank/remnote-library/issues/new?title=RemNote%20Library%20Report%3A%20Column%20Layout%20v0.1.0&body=%0A%2A%2APlease%20check%20first%20if%20there%20is%20an%20update%20of%20this%20scroll%20available.%2A%2A%0A%0A---%0A%0A-%20%2A%2AId%3A%2A%2A%20com.github.hannesfrank.remnote-library.column-layout%0A-%20%2A%2AVersion%3A%2A%2A%200.1.0%0A-%20%2A%2AType%3A%2A%2A%20Problem/Suggestion%20%28choose%20one%29%0A%0A-%20%5B%20%5D%20Describe%20the%20problem%20you%20are%20having%20with%20the%20scroll%20or%20how%20it%20should%20be%20improved.%0A-%20%5B%20%5D%20_Add_%20a%20short%20description%20to%20the%20title%20%28don%27t%20replace%20it%20completely%21%29%20so%20people%20know%20what%20this%20is%20about.%0A-%20%5B%20%5D%20Make%20sure%20to%20include%20a%20screenshot%20or%20image%20to%20make%20your%20issue%20easy%20to%20understand.%0A%0A---%0A)
        - Tags   #columns
            - columns
        - Demo
            - Column Layout #columns
                - left
                    - your 
                    - content
                - right
                    - like in notion
                - but more
        - Code
            - ```css

.tree-node-container[data-rem-container-tags~="columns"] > .TreeNode {
    display: flex;
}

.tree-node-container[data-rem-container-tags~="columns"]
    > .TreeNode
    > .tree-node-container {
    /* equal width columns */
    flex: 1 1 0;
    /* more based on content */
    /* flex: 1 1 auto; */
}
```
            - 
        - 
    - Block Quotes ((#^^Blockquote^^ or #^^Blockquote-tree^^)
        - Block-Quotes (#Blockquote or #Blockquote-tree)
            - Configurable quote highlight to distinguish your thoughts from someone else's. Comes in a single and a tree version.
                - id: com.github.hannesfrank.remnote-library.blockquote
                - version: 0.1.0
                - [Homepage](https://github.com/hannesfrank/remnote-library/tree/master/public/scrolls/blockquote)
                - [Report Problem or Suggest Improvement](https://github.com/hannesfrank/remnote-library/issues/new?title=RemNote%20Library%20Report%3A%20Blockquote%20v0.1.0&body=%0A%2A%2APlease%20check%20first%20if%20there%20is%20an%20update%20of%20this%20scroll%20available.%2A%2A%0A%0A---%0A%0A-%20%2A%2AId%3A%2A%2A%20com.github.hannesfrank.remnote-library.blockquote%0A-%20%2A%2AVersion%3A%2A%2A%200.1.0%0A-%20%2A%2AType%3A%2A%2A%20Problem/Suggestion%20%28choose%20one%29%0A%0A-%20%5B%20%5D%20Describe%20the%20problem%20you%20are%20having%20with%20the%20scroll%20or%20how%20it%20should%20be%20improved.%0A-%20%5B%20%5D%20_Add_%20a%20short%20description%20to%20the%20title%20%28don%27t%20replace%20it%20completely%21%29%20so%20people%20know%20what%20this%20is%20about.%0A-%20%5B%20%5D%20Make%20sure%20to%20include%20a%20screenshot%20or%20image%20to%20make%20your%20issue%20easy%20to%20understand.%0A%0A---%0A)
            - Tags
                - #Blockquote
                    - Block QUOTE EXAMPLE   ##Blockquote
                - #Blockquote-tree
                    - Block QIOTE tREE EXAMPLE  #blockquote-tree
                        - 
            - Demo
                - This is a blockquote. # blockquote
                    - Child Rem are not highlighted.
                - This is a tree blockquote. #blockquote-tree
                    - Child Rem are included.
            - Code
                - ```css
/* Style taken from Cato Minor: https://medium.com/better-programming/roamext-roam-extended-a-little-piece-of-code-with-mighty-power-a18184c0c5be */
[data-rem-container-tags~="blockquote"] > div:first-child .rem-text > div {
    background-color: var(--quote-background-color, rgb(244, 242, 242));
    border-left: var(--quote-border-width) solid
        var(--quote-border-color, rgb(255, 204, 111));
    padding: 6px 11px;
}

[data-rem-container-tags~="blockquotetree"] {
    background-color: var(--quote-background-color, rgb(244, 242, 242));
    border-left: var(--quote-border-width) solid
        var(--quote-border-color, rgb(255, 204, 111));
    margin-left: calc(-6px - var(--quote-border-width));
    padding: 3px 6px;
}

/* Reset background on selection. */
.selected-rem [data-rem-container-tags~="blockquotetree"],
.selected-rem
    [data-rem-container-tags~="blockquote"]
    > div:first-child
    .rem-text
    > div,
[data-rem-container-tags~="blockquotetree"].selected-rem,
[data-rem-container-tags~="blockquote"].selected-rem
    > div:first-child
    .rem-text
    > div {
    /* The default selection color is #cce2ff. I altered it slightly to have blockquotes still visible on selection. */
    background-color: #dce2ff;
}
```
            - Customization
                - ```css
:root {
    --quote-background-color: rgb(244, 242, 242);
    --quote-border-color: rgb(255, 204, 111);
    --quote-border-width: 5px;
}
```
    - Customized Card Icons and Types
        - Text Style #[[Text Style]] 
            - ```css
@import URL("https://hannesfrank.github.io/remnote-css-rem-types/text-style.css");
```
        - Practice Direction #[[Practice Direction]] 
            - ```css
@import URL("https://hannesfrank.github.io/remnote-css-rem-types/practice-direction.css");
```
        - Card Type #[[Card Type]] 
            - ```css
@import URL("https://hannesfrank.github.io/remnote-css-rem-types/card-type.css");
```
        - Rem Type #[[Rem Type]] 
            - ```css
@import URL("https://hannesfrank.github.io/remnote-css-rem-types/rem-type.css");
/* OR: @import URL("https://hannesfrank.github.io/remnote-css-rem-types/rem-type-simple.css"); */
```
- **/Customization** 
    - Customize Fonts
        - ```css

:root {
	/*
	--font-body: Helvetica Neue, Arial, sans-serif;
	--font-body: Arial Unicode MS, sans-serif;
	*/
}

```
    - Editor/UI Customization** ** 
        - UI Components
            -  _Side Bar_  
                - Sidebar Verticle line
                    - ```css
 #document-sidebar .accordion.ui.fluid {
		background:
			linear-gradient(#cacad9 0 0) 17px,
			linear-gradient(#cacad9 0 0) 43px,
			linear-gradient(#cacad9 0 0) 69px,
			linear-gradient(#cacad9 0 0) 95px,
			linear-gradient(#cacad9 0 0) 121px,
			linear-gradient(#cacad9 0 0) 147px,
			linear-gradient(#cacad9 0 0) 173px,
			linear-gradient(#cacad9 0 0) 199px,
			linear-gradient(#cacad9 0 0) 225px,
			linear-gradient(#cacad9 0 0) 251px,
			linear-gradient(#cacad9 0 0) 277px,
			linear-gradient(#cacad9 0 0) 303px,
			linear-gradient(#cacad9 0 0) 329px,
			linear-gradient(#cacad9 0 0) 355px,
			linear-gradient(#cacad9 0 0) 381px,
			linear-gradient(#cacad9 0 0) 407px;
		background-size: 1px 100%;
		background-repeat: no-repeat;
	}

	#document-sidebar .title.p-2 {
		background: white;
	}

	#document-sidebar .p-2:not(:hover) {
		background: white;
	}
``` 
                - Side Bar Font
                    - ```css
 #hierarchy-editor .rem-container--compact .EditorContainer {
margin-bottom: -4.5px;
margin-top: -4.5px;
}
``` 
                - Tighter Side BAR
                    - ```css
 /* tighter sidebar */
#document-sidebar div {
	padding-top: 1.1px; /* 0px for an even more severe effect */
	padding-bottom: 1.1px; /* 0px for an even more severe effect */
}
``` 
            -  _Scroll_  
                - Scroll Bar Color  
                    - ```css
 /*ScrollBar - Updated 29 April 2021*/
::-webkit-scrollbar {
  width: 7px;
}

::-webkit-scrollbar-track {
	background: rgba(89, 105, 113,0.22);
	border-radius: 20px;
}
::-webkit-scrollbar-thumb {
	background-color: rgb(116, 120, 120,0.3);
	border-radius: 20px;
	border: 0px solid rgba(89, 105, 113);
}
::-webkit-scrollbar-thumb:hover {
	background-color: rgb(116, 120, 120,0.5);
	border-radius: 20px;
	border: 0px solid rgba(89, 105, 113);
}
``` 
                    - Custom Scroll Bar
                        - ```css
div::-webkit-scrollbar {
    width: 5px !important;
    height: 2px !important;
}

div::-webkit-scrollbar-track {
    background-color: transparent !important;
}

div::-webkit-scrollbar-thumb {
    background-color: rgba(255, 255, 255, 0.4) !important;
    border-radius: 10px !important;
}

div::-webkit-scrollbar-thumb:hover {
    background-color: rgba(255, 255, 255, 0.4) !important;
}
``` 
            -  _Navigation_  
                - Scrollable Navigation Breadcrumb
                    - ```css
 /* add a scrollbar to show all breadcrumbs if needed */
.document-header-top-bar > div {
   overflow-x: auto;
}
``` 
                - Multi-line Nav Bar
                    - ```css
 /* Multi Line Breadcrumbs */
.document-header-top-bar {
	height: fit-content;
}
.document-header-top-bar > div > div {
	flex-wrap: wrap;
	overflow-wrap: normal;
}	
.document-header-top-bar .flex-nowrap {flex-wrap: wrap;}
.document-header-top-bar .flex {display: inline;}
``` 
        - **tsk's Special UI Code** 
            - Hide Alias if Empty
                - ```css
 /* Hide the aliases container if it is inside a child */
.tree-node--children [data-rem-container-tags~="aliases"] {
    display : none;
 }  

  /* Hide the aliases container if it is inside a reference context menu (the one you get when you hover over a rem reference) */
 .rn-popup__content [data-rem-container-tags~="aliases"] {
    display : none;
 }  
``` 
            - Hide Indented Rem Indicator |
                - ```css
.rem-indented-indicator {
    display: none;
}
```
            - Hide Cloze Menu Button while editing
                - ```css
i.icon.caret.square.down.icon:before {
    display: none;
}

i.icon.caret.square.down.icon:after {
    content: "+";
}
```
            - Show Reference Brackets [ ]
                - ```css
.rem-reference-link:before {
    content: "[";
}

.rem-reference-link:after {
    content: "]";
}
```
            - Spacing and Header Size, **Choose one:** 
                - Roomy Spacing and Large Headers
                    - ```css
:root {
    --spacing-line-height: 1.5em;
    --spacing-tree-node-container-margin-top: 0.5em;
    --spacing-bullet-paragraph-margin-top: 7px;
    --spacing-bullet-document-margin-top: 3px;
    --spacing-bullet-conceptDescriptor-margin-top: 7px;
    
    --header-1-margin-top: 20px;
    --header-2-margin-top: 11px;
    --header-3-margin-top: 6px;
    
    --header-1-font-size: 25px;
    --header-1-font-weight: 500;
    --header-2-font-size: 19px;
    --header-2-font-weight: 600;
    --header-3-font-size: 16px;
    --header-3-font-weight: 700;
}
```
                - Roomy Spacing and Small Headers
                    - ```css
:root {
    --spacing-line-height: 1.5em;
    --spacing-tree-node-container-margin-top: 0.5em;
    --spacing-bullet-paragraph-margin-top: 7px;
    --spacing-bullet-document-margin-top: 3px;
    --spacing-bullet-conceptDescriptor-margin-top: 7px;
    
    --header-1-margin-top: 11px;
    --header-2-margin-top: 8px;
    --header-3-margin-top: 6px;
    
    --header-1-font-size: 18px;
    --header-1-font-weight: 400;
    --header-2-font-size: 16px;
    --header-2-font-weight: 380;
    --header-3-font-size: 15px;
    --header-3-font-weight: 350;
}
``` 
                - Compact Spacing and Large Headers
                    - ```css
:root {
    --spacing-line-height: 1.3em;
    --spacing-tree-node-container-margin-top: 0em;
    --spacing-bullet-paragraph-margin-top: 4px;
    --spacing-bullet-document-margin-top: 3px;
    --spacing-bullet-conceptDescriptor-margin-top: 4px;
    
    --header-1-margin-top: 18px;
    --header-2-margin-top: 8px;
    --header-3-margin-top: 3px;
    
    --header-1-font-size: 25px;
    --header-1-font-weight: 500;
    --header-2-font-size: 19px;
    --header-2-font-weight: 600;
    --header-3-font-size: 16px;
    --header-3-font-weight: 700;
}
```
                - Compact Spacing and Small Headers
                    - ```css
:root {
    --spacing-line-height: 1.3em;
    --spacing-tree-node-container-margin-top: 0em;
    --spacing-bullet-paragraph-margin-top: 4px;
    --spacing-bullet-document-margin-top: 3px;
    --spacing-bullet-conceptDescriptor-margin-top: 4px;
    
    --header-1-margin-top: 8px;
    --header-2-margin-top: 5px;
    --header-3-margin-top: 3px;
    
    --header-1-font-size: 18px;
    --header-1-font-weight: 500;
    --header-2-font-size: 16px;
    --header-2-font-weight: 600;
    --header-3-font-size: 15px;
    --header-3-font-weight: 500;
}
```
        - Editor Styling 
            -  _Font Styling: _  
                - Font Family and Sizes     
                    - ```css
/* Editor Font */
.rem-text {
  font-family: "Helvetica Neue", -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica Neue, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji","Arial Unicode MS",  sans-serif;
}

/* Header Font */
.rem-header,
.rem-header--1,
.rem-header--2,
.rem-header--3 {
  font-family:"Helvetica Neue", -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica Neue, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji","Arial Unicode MS", sans-serif;
}
``` 
                    - ```css
/* Override font */

    div {
        font-family:"Helvetica Neue", sans-serif;
        font-weight: 250;
        font-size: 1em;
        margin: 0px;
        padding: 0px;
    }
    .rem-header--1{
    	font-family:"Helvetica Neue", sans-serif;
        font-size: 24px;
        font-weight: 400;
    }
    .rem-header--2{
        font-family:"Helvetica Neue", sans-serif;
        font-size: 20px;
        font-weight: 380;
    }
    .rem-header--3{
        font-family: "Helvetica Neue", sans-serif;
        font-size: 17px;
        font-weight: 350;
    } 
``` 
                - Italic  
                    - ```css
  /* set the text italic to be orange */
.italic {
	color:DarkOrange;
	
}
``` 
                - Bold Text weight  
                    - ```css
 /* set the text bold to be as bold as the default concept bold */
.bold {
	font-weight: 350; /* default is 700 */
	
}
``` 
                - Highlighters
                    - Light Blue Theme Highlighter 
                        - ```css
/* 2 --------------------------------------------------- */

/* Colors Customization Light Blue Theme */
:root {
	--quote-background-c: #eee; /* Color of Quotes */
    --main-link-c: #8ca7b0; /* Color of Referenced Rems */


	/* Highlighters */    
    --highlight-red-c: #ffadab80;
    --highlight-orange-c: #ffda9680;
    --highlight-yellow-c: #fcff8f80;
    --highlight-green-c: #b5e9a680;
    --highlight-blue-c: #b7dbff80;
    --highlight-purple-c: #e7b7ff80;
}

``` 
                    - Dark Theme ^^Highlighter ^^ 
                        - ```css
/* 1 --------------------------------------------------- */

/* Colors Customization Dark Mode Theme */
:root {
    --quote-background-c: #474c50; /* Color of Quotes */

    --main-link-c: #f4bf61; /* Color of Referenced Rems */


	/* Highlighters */
    --highlight-red-c: rgba(255, 115, 105, 0.5);
    --highlight-orange-c: rgba(255, 163, 68, 0.5);
    --highlight-yellow-c: rgba(255, 220, 73, 0.5);
    --highlight-green-c: rgba(77, 171, 110, 0.5);
    --highlight-blue-c: rgba(91, 174, 223, 0.5);
    --highlight-purple-c: rgba(194, 111, 177, 0.5);
	
}

```
                - Title font
                    - Title font  ```css
.document-title {
	font-family: "Helvetica Neue";
}
``` #Snippet
            -  _Component Styles_  
                - Smaller and more** **condensed font
                    - ```css
 /* Smaller and more condensed fontSmaller and more condensed font */
.rem-text {
	font-family:"Helvetica Neue","Arial Unicode MS",Roboto,Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol"
}
``` 
                - Smaller source and tags fields
                    - ```css
 #DropToOpenAsDocument > div > *:not(#DocumentTitle) {
  zoom: 90%;
}
``` 
                - Less Bold Document Title
                    - ```css
/* less bold bold text in document title */
.document-title .bold {
	font-weight: 350; /* default is 850 */
} 
``` 
                - Make Concepts Bold** ** 
                    - ```css
 /* set the concept bold */
.concept_rem_type{
	font-weight: 380; /* default is 600  */
}
``` 
                - Reducing whitespace around or between elements   
                    - Less whitespace in the left margin
                        - ```css
 /* less whitespace in the left margin */
.document--ltr {
	padding-left: 30px; /* 48px is the default, 0px will push the six dot menu halfway past the edge if the rem has an arrow, 32.5px will just reduce the margin */
}
.document-sidebar--collapsed--vertical {
	height: 5%; /* removes unused vertical sidebar hover area when used with windowed panes */
}
``` 
                    - less space between rem using the native setting's properties
                        - ```
/* less space between rem using the native setting's properties */
#hierarchy-editor .rem-container--compact .EditorContainer, #hierarchy-editor .rem-container--compact .rem-text {
    padding-bottom: 8px;
    padding-top: 8px;
}
``` 
                    - Leaner Bullet
                        - ```css
 /* leaner bullets */
#hierarchy-editor .rem-container--compact .EditorContainer {
	margin-bottom: -4.5px; /* -2.5px is the default, can go as low as -6.5px */
	margin-top: -4.5px; /* -2.5px is the default, can go as low as -6.5px */
}
``` 
                    - Line height in rem text
                        - ```
/* line height in rem text */
.rem-container {
	--line-height: 30px; /* 24px is the default */
}
``` 
                    - Space b/w Bullet and Text
                        - ```css
 /* less space between rem's bullet and text */
.hierarchy-editor--ltr .rem-text {
	padding-left: 25px; /* 24px is the default */
}
``` 
                    - Shorten space before rem reference portals
                        - ```css
 /* Shorten space before rem reference portals */
.rn-add-rem-button--bottom {
	height: 5rem; /* Default is 15rem*/
}
``` 
    - Misc.   
        - ```css

/* 4 --------------------------------------------------- */

/* Hide Indented Rems Indicator  " | " */
.rem-indented-indicator {
    display: none; 
}

/* 5 --------------------------------------------------- */
        
/* Show Cloze Menu Arrow only while editing  */
i.icon.caret.square.down.icon:before {
    display: none;
}

i.icon.caret.square.down.icon:after {
    content: '+';
}

/* 6 --------------------------------------------------- */
        
/* Hide Scrollers */
div::-webkit-scrollbar {
    width: 6px !important;
    height: 2px !important;
}
div::-webkit-scrollbar-track {
    background-color: transparent !important;     
}
div::-webkit-scrollbar-thumb {
    background-color: transparent!important;
    border-radius: 10px!important;
}
div::-webkit-scrollbar-thumb:hover {
    background-color: rgba(17, 17, 17, .35) !important;
    cursor: pointer !important;
}

/* 7 --------------------------------------------------- */

/* Thin Multi Rem Sidebar */
#hierarchy-editor .TreeNodeListItems {
    border-width: 1px!important;
}

/* 8 --------------------------------------------------- */
        

/* 9 --------------------------------------------------- */

/* Less Strong Bold Font: */
.bold {
    font-weight: 300;
}   

```
