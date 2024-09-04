- /chil
- **Themes** Current Config
    - Lightblue
        - LightBlue theme @ethomasv - Github auto-update
            - ```css
 @import url('https://ethomasv.github.io/RemNoteTheme/LightBlueRemnote.css');
``` 
        - Light Theme by @eustachi - Modular (1.0)
            - 1 Body
                - ```css
body {	
    background-color: #F8F8F9;
    height: 100%;
    margin: 0;
    font-family: "Arial Unicode MS",-apple-system,BlinkMacSystemFont,segoe ui,Roboto,Helvetica,Arial,sans-serif,apple color emoji,segoe ui emoji,segoe ui symbol; 
    font-size: 15px;
    color: #535666;
    caret-color: #55CDC4;
}

#hierarchy-editor .rem-container--focused {
    background-color: rgba(170, 237, 255, 0.05);
    border-radius: 2px;
    margin-left: 3px;
    padding-left: 0px;
}
#hierarchy-editor .rem-container--spacious .rem-text {
    padding-bottom: 10px;
    padding-top: 7px;
    padding-left: 20px;
}
#ExamplesPageContainer #ExamplesPageContent, #export-container #export, #HelpPage #HelpPageContent, #sign-up-page-container #sign-up-page, #StatsPage #StatsPageContent, .centered-page, .document--narrow {
    background-color: #F8F8F9;
}

/* Update 23 March 2021*/
#hierarchy-editor .rem-container .rem-text {
    color: #535666;
	margin-left: 10px;
	margin-right: 0px;
    padding-left: 15 px;
}
.rem-bullet, .rem-bullet--in-list {
    width: 6px;
    height: 6px;
    background-color: rgba(211,212,216,0);
    border-color: rgba(211,212,216,.85);
}
.rem-bullet__container {
    top: 4px;
  
.rem-bullet__container-H1 {
    top: 1px;
}
.rem-bullet__container-H2 {
    top: 1px;
}
.rem-bullet__container-H3 {
    top: 1px;
}
.rem-header--1 {
	background-color: rgba(0,0,0,0);
	border-radius: 50px;
}
#document #actionRequiredDocumentTitle, #document .document-title {
    font-size: 26px;
    font-weight: 400;
    font-family: 'Arial Unicode MS';
}
#hierarchy-editor .is-toolbar-previous-focus-rem {
    box-shadow: 0 0 0px 0 rgba(85,205,196,0);
    border-radius: 2px;
    background-color: rgba(85,205,196,.13);
}
.flash {   
	background-color: rgba(85,205,196,.13)!important;
    box-shadow: 1px 2px 9px 5px rgba(0,0,0,0);
    margin-left: -20px;
    padding-left: 20px;
}
.pane {
    padding-left: 0px;
}
#DocumentTable .Cell {
    color: #535666;
}
#DocumentTable .ReactVirtualized__Table__headerRow {
    color: #535666;
}
.gutter {
    background-color: #F8F8F9;
}
.rem-calendar-icon--today {
    filter: contrast(10) brightness(3) hue-rotate(60deg);
}
.LinkNode {
    text-decoration: underline;
    color: rgb(79, 76, 210,0.9);
    font-weight: 300;
}
.rem-reference-link {
    color: #4674BD;
    font-weight: 300;
}
.rem-reference-link:hover {
    background-color: rgba(98, 160, 250,.2);
    font-weight: 320;
    border-radius: 30px;
	margin-left: -5px;
	padding-left: 6px;
	margin-right: -5px;
	padding-right: 5px;
}
.rem-reference--highlighted {
    border-color: rgba(0,0,0,0);
    box-shadow: 0 0 0px 0px rgba(0,0,0,0);
}
.rem-reference--focused {
    box-shadow: 0 0 0 0px rgba(0,0,0,0);
}
#hierarchy-editor .TreeNode--list--in-card-content {
    border-color: #fefefe;
    border-width: 3px;
    margin-left: 2px;
    margin-bottom: 6px;
}
.cloze {
    background-color: rgba(210,225,248,0);
    border-bottom: 3px solid rgb(79, 76, 210,0.4);
    padding-bottom: 0px;
    font-weight: 330;
    font-style: italic;
}
/*ScrollBar - Updated 29 April 2021*/
::-webkit-scrollbar {
  width: 13px;
}

::-webkit-scrollbar-track {
	background: rgba(89, 105, 113,0.2);
	border-radius: 20px;
}
::-webkit-scrollbar-thumb {
	background-color: rgb(116, 120, 120,0.3);
	border-radius: 20px;
	border: 0px solid rgba(89, 105, 113);
}
::-webkit-scrollbar-thumb:hover {
	background-color: rgb(116, 120, 120,0.6);
	border-radius: 20px;
	border: 0px solid rgba(89, 105, 113);
}
``` 
            - 2 Portals ^^(updated 1 Feb 2021)^^
                - ```css
#hierarchy-editor .TreeNode {
    border-color: rgba(209, 210, 210, 0.26);
    border-width: 0.8px;
    transition-timing-function: linear;
    position: relative;
    background-color: transparent;
    padding-left: 20px;
    padding-top: 0px;
    padding-bottom: 0px;
    margin-top: 0px;
    margin-bottom: 0px;
}
#hierarchy-editor .TreeNode--dark-indent-line {
    border-color: #bcbcbc!important;
    border-width: 1px;
    background-color: transparent;
}
.hierarchy-editor--ltr .TreeNode {
    margin-left: 2px;
    padding-left: 25px;
    border-left-style: solid;
}
#hierarchy-editor .portal-rem {
    border-style: none none;
    border-top-style: none;
    border-right-style: none;
    border-bottom-style: none;
    border-left-style: none;
    border-width: 0px;
    margin-top: 10px;
    margin-left: -7px;
    margin-right: -7px;
    padding-top: 0px;
    height: 100%;
}
#show-embedded-search-button {
	background-color: #F9F9F9;
    padding-left: 10px;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-right: 12px;
    margin-top: 10px;
    margin-bottom: 10px;
    border: 0px none rgb(0,0,0);
    border-bottom: 0px solid #000;
    border-radius: 7px;
    border-bottom-right-radius: 7px;
    border-bottom-left-radius: 7px;
    margin-right: 6px;
    margin-left: -6px;
    color: #82868B;
    font-weight: 350;
}
.embeddedSearch {
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
    border-bottom-right-radius: 5px;
    border-bottom-left-radius: 5px;
    border: 0px solid #d3d4d8;
    border-top-color: rgba(183,183,187,0);
    border-top-style: solid;
    border-top-width: 0px;
    border-right-color: rgba(183,183,187,0);
    border-right-style: solid;
    border-right-width: 0px;
    border-bottom-color: rgba(183,183,187,0);
    border-bottom-style: solid;
    border-bottom-width: 0px;
    border-left-color: rgba(183,183,187,0);
    border-left-style: solid;
    border-left-width: 0px;
    border-image-source: initial;
    border-image-slice: initial;
    border-image-width: initial;
    border-image-outset: initial;
    border-image-repeat: initial;
    text-decoration: none;
    text-decoration-line: none;
    text-decoration-thickness: initial;
    text-decoration-style: initial;
    text-decoration-color: initial;
    padding-top: 5px;
    padding-right: 5px;
    padding-bottom: 6px;
    padding-left: 10px;
    margin-bottom: 5px;
    margin-left: 10px;
    margin-right: 10px;
    margin-top: 0px;
    background-color: #FDFDFE;
}
#hierarchy-editor .portal-rem--embedded-search {
    border-color: none;
    background-color: #F0F0F2;
    margin-right: 6px;
    padding-top: 0px;
    margin-top: 14px;
    margin-left: -6px;
    padding-bottom: 14px;
    margin-bottom: 20px;
    border-bottom-right-radius: 7px;
    border-bottom-left-radius: 7px;
}
#hierarchy-editor .rem-container__top-level-spacer {
    margin-top: 10px;
    width: 100%;
    display: block;
}
#search-results__controls #search-results__control .search-results__control__keyboard-shortcut, .quote {
    margin-right: 0px;
    margin-left: 0px;
    background-color: rgba(98, 160, 250,.2);
    border-radius: 30px;
    padding: 1px;
    padding-left: 6px;
    padding-right: 6px;
}
i.icon.search:before {
    content: "\f002";
    zoom: 125%;
    padding-top: 6px;
    padding-left: 2px;
    color: rgba(183,183,187,0.5);
}
i.icon.refresh:before {
    content: "\f021";
    zoom: 120%;
    color: rgba(183,183,187,0.5);
    padding-right: 5px;
}
#embedded-search-refresh-button {
    float: right;
    padding-top: 6px;
    padding-right: 15px;
    padding-bottom: 10px;
    padding-left: 5px;
}
#no-search-results {
    color: rgba(183,183,187,0.7);
    text-align: center;
    margin-top: 20px;
    margin-bottom: 5px
}
#hierarchy-editor .portal-rem .portal-rem-top--embedded-search-top {
    border-color: rgb(0,0,0,0);
    text-align: right;
    border-top: solid rgb(0,0,0,0);
    border-width: 0px;
    position: relative;
    top: 0px;
    padding-top: 0px;
    margin-top: -25px;
}
#hierarchy-editor .search-portal-tree-node {
    border-bottom-width: 0px;
    border-top-width: 0px;
    border-left: 0px solid rgb(0,0,0,0);
    border-bottom-color: rgb(0,0,0,0);
    border-right: 0px solid rgb(0,0,0,0);
    border-top-color: rgb(0,0,0,0);
    margin-left: -6px;
    margin-right: 6px;
    padding-left: 15px;
    padding-right: 9px;
    padding-bottom: 12px;
    margin-bottom: 7px;
    margin-top: -30px;
    background-color: #F0F0F2;
    border-bottom-right-radius: 7px;
    border-bottom-left-radius: 7px;
}
.rem-indented-indicator {
    color: rgb(0,0,0,0);
    top: -1.8px;
    position: fixed;
}
#hierarchy-editor .isSearchResult {
    background-color: transparent;
    margin-top: 0px;
    margin-bottom: -0px;
    border: 0px solid rgb(0,0,0);
    border-radius: 0px;
    margin-right: 0px;
    margin-left: 0px;
    padding-left: 0px;
}
#hierarchy-editor .rem-container__top-level-spacer .rem-container__top-level-spacer__inner {
    border-color: rgb(0,0,0,0);
    border-top: solid rgb(0,0,0,0);
    border-width: 5px;
    bottom: 0px;
    position: relative;
}
#hierarchy-editor .portal-rem .portal-rem-top, #hierarchy-editor .portal-rem .portal-rem-top--embedded-search-top {
    border-color: rgb(0,0,0,0);
    text-align: right;
    border-top: solid rgb(0,0,0);
    border-width: 0px;
    position: relative;
    top: -4px;
    padding-top: 13px;
}
#hierarchy-editor .portal-tree-node {
    border-left: 0px solid rgba(183,183,187,0);
    border-bottom-color: rgba(183,183,187,0);
    border-right: 0px solid rgba(183,183,187,0);
    border-bottom: 8px solid #F0F0F2;
    border-top: 4px solid #F0F0F2);
    margin-left: -6px;
    margin-right: 6px;
    margin-top: -16px;
    margin-bottom: 10px;
    padding-left: 15px;
    padding-right: 9px;
    padding-top: 6px;
    padding-bottom: 0px;
    background-color: #F0F0F2;
    border-radius: 7px;
    border-bottom-right-radius: 7px;
    border-bottom-left-radius: 7px;
}
#hierarchy-editor .hierarchy-editor__after-portal .addItemAfterPortal {
    height: 25px;
    width: 100%;
    padding-left: 8px;
    margin-top: -8px;
    margin-bottom: -4px;
}
#hierarchy-editor .hierarchy-editor__after-portal {
    border-bottom-style: solid;
    border-width: 0px;
    border-top-width: 0px;
    border-right-width: 0px;
    border-bottom-width: 0px;
    border-left-width: 0px;
    padding-top: 0px;
    padding-bottom: 0px;
    margin-left: -6px;
    margin-right: 7px;
}
#hierarchy-editor .rem-container--not-included-in-document-scope {
    color: #535666;
    padding-left: 15px!important;
    padding-bottom: 2px;
    padding-top: 1px;
}
``` 
            - 3 Logo and Side, Bottom, Nav Bars ^^(updated 23 March 2021)^^
                - ```css
#document-sidebar_top #logo {     display: none; } 
body {     background-color: #F8F8F9;     height: 100%;     margin: 0;     font-family: fira code,-apple-system,BlinkMacSystemFont,segoe ui,Roboto,Helvetica,Arial,sans-serif,apple color emoji,segoe ui emoji,segoe ui symbol;      font-size: 15px;     color: #535666;     caret-color: #55CDC4; } #hierarchy-editor .rem-container--focused {     background-color: rgba(85,205,196,.07);     border-radius: 2px;     margin-left: -25px;     padding-left: 25px; } #hierarchy-editor .rem-container--spacious .rem-text {     padding-bottom: 5px;     padding-top: 5px;     padding-left: 20px; } #ExamplesPageContainer #ExamplesPageContent, #export-container #export, #HelpPage #HelpPageContent, #sign-up-page-container #sign-up-page, #StatsPage #StatsPageContent, .centered-page, .document--narrow {     background-color: #F8F8F9; }  /* Update 23 March 2021*/ #hierarchy-editor .rem-container .rem-text {     color: #535666; 	margin-left: 0px; 	margin-right: 0px;     padding-left: 14px; } .rem-bullet, .rem-bullet--in-list {     width: 6px;     height: 6px;     background-color: #747878;     border-color: rgba(211,212,216,.85); } .rem-bullet__container {     top: 4px; } .rem-bullet__container-H1 {     top: 8px; } .rem-bullet__container-H2 {     top: 7px; } .rem-bullet__container-H3 {     top: 4px; } .rem-header--1 { 	background-color: rgba(0,0,0,0); 	border-radius: 50px; } #document #actionRequiredDocumentTitle, #document .document-title {     font-size: 30px;     font-weight: bold; } #hierarchy-editor .is-toolbar-previous-focus-rem {     box-shadow: 0 0 0px 0 rgba(85,205,196,0);     border-radius: 2px;     background-color: rgba(85,205,196,.13); } .flash {    	background-color: rgba(85,205,196,.13)!important;     box-shadow: 1px 2px 9px 5px rgba(0,0,0,0);     margin-left: -20px;     padding-left: 20px; } .pane {     padding-left: 0px; } #DocumentTable .Cell {     color: #535666; } #DocumentTable .ReactVirtualized__Table__headerRow {     color: #535666; } .gutter {     background-color: #F8F8F9; } .rem-calendar-icon--today {     filter: contrast(10) brightness(3) hue-rotate(60deg); } .LinkNode {     text-decoration: underline;     color: rgb(79, 76, 210,0.9);     font-weight: 500; } .rem-reference-link {     color: #4674BD;     font-weight: 500; } .rem-reference-link:hover {     background-color: rgba(98, 160, 250,.2);     font-weight: 500;     border-radius: 30px; 	margin-left: -5px; 	padding-left: 6px; 	margin-right: -5px; 	padding-right: 5px; } .rem-reference--highlighted {     border-color: rgba(0,0,0,0);     box-shadow: 0 0 0px 0px rgba(0,0,0,0); } .rem-reference--focused {     box-shadow: 0 0 0 0px rgba(0,0,0,0); } #hierarchy-editor .TreeNode--list--in-card-content {     border-color: rgb(79, 76, 210,0.4);     border-width: 3px;     margin-left: 2px;     margin-bottom: 6px; } .cloze {     background-color: rgba(210,225,248,0);     border-bottom: 3px solid rgb(79, 76, 210,0.4);     padding-bottom: 0px;     font-weight: 600;     font-style: italic; } /*ScrollBar - Updated 29 April 2021*/::-webkit-scrollbar {   width: 13px; }  ::-webkit-scrollbar-track { 	background: rgba(89, 105, 113,0.2); 	border-radius: 20px; } ::-webkit-scrollbar-thumb { 	background-color: rgb(116, 120, 120,0.3); 	border-radius: 20px; 	border: 0px solid rgba(89, 105, 113); } ::-webkit-scrollbar-thumb:hover { 	background-color: rgb(116, 120, 120,0.6); 	border-radius: 20px; 	border: 0px solid rgba(89, 105, 113); }
``` 
                - 
            - 4 Highlight colours ^^(updated 23 March 2021)^^
                - ```css
/*The whole block has been updated - 23 March 2021*/ /*red*/ .highlight-color--red, .pdf-viewer__highlight-container--red .AreaHighlight, .pdf-viewer__highlight-container--red .Highlight__part {     background-color: rgba(243, 96, 106,.45);     border-radius: 35px;     margin-left: 0px;     margin-right: 0px;     padding-left: 6px;     padding-right: 6px; } /*orange*/ .highlight-color--orange, .pdf-viewer__highlight-container--orange .AreaHighlight, .pdf-viewer__highlight-container--orange .Highlight__part {     background-color: rgba(244, 167, 98,.45);     border-radius: 35px;     margin-left: 0px;     margin-right: 0px;     padding-left: 6px;     padding-right: 6px; } /*yellow*/ .highlight-color--yellow, .pdf-viewer__highlight-container--undefined .AreaHighlight, .pdf-viewer__highlight-container--undefined .Highlight__part, .pdf-viewer__highlight-container--yellow .AreaHighlight, .pdf-viewer__highlight-container--yellow .Highlight__part, .PdfHighlighter .textLayer::selection {     background-color: rgba(250, 233, 123,.45);     border-radius: 35px;     margin-left: 0px;     margin-right: 0px;     padding-left: 6px;     padding-right: 6px; } /*green*/ .highlight-color--green, .pdf-viewer__highlight-container--green .AreaHighlight, .pdf-viewer__highlight-container--green .Highlight__part {     background-color: rgba(112, 230, 109,.45);     border-radius: 35px;     margin-left: 0px;     margin-right: 0px;     padding-left: 6px;     padding-right: 6px; } /*blue*/ .highlight-color--blue, .pdf-viewer__highlight-container--blue .AreaHighlight, .pdf-viewer__highlight-container--blue .Highlight__part {     background-color: rgba(98, 160, 250,.45);     border-radius: 35px;     margin-left: 0px;     margin-right: 0px;     padding-left: 6px;     padding-right: 6px; } /*purple*/ .highlight-color--purple, .pdf-viewer__highlight-container--purple .AreaHighlight, .pdf-viewer__highlight-container--purple .Highlight__part {     background-color: rgba(162, 102, 232,.45);     border-radius: 35px;     margin-left: 0px;     margin-right: 0px;     padding-left: 6px;     padding-right: 6px; }
``` 
            - 5 Tags ^^(Updated 31 March 2021)^^
                - ```css
.hierarchy-editor__tag-bar .hierarchy-editor__tag-bar__power-up-tag { 	display: none; }
``` 
            - 6 Popups ^^(uploaded 31 Jan 2021)^^
            - 8 Code Block ^^(uploaded 31 Jan 2021)^^
                - ```css
#code-node {     font-family: Roboto; font-weight: 280;}
``` 
            - 7 Checkbox ^^(uploaded 31 Jan 2021)^^
                - ```css
.rem-checkbox {     margin-right: 10px;     margin-top: 3px; }
``` 
            - 9 Queue ^^(uploaded 31 Jan 2021)^^
                - ```css
.concept_rem_type, .question_rem_type {     font-weight: 700;     color: #535666; } .Queue .queue__title {     height: 35px;     border-radius: 10px 10px 0 0;     display: flex;     align-items: center;     background-color: #E8EEF8; } .Queue .queue__title .queue__sizeButton {     border: none;     outline: none;     background-color: #E8EEF8;     color: #232735;     border-radius: 10px;     display: flex; } .queue-container {     color: #535666; }
``` 
            - 10 Sticky menu ^^(uploaded 31 Jan 2021)^^
                - ```css
#hierarchy-editor #hierarchy-editor-list__sticky-top__container #hierarchy-editor-list__sticky-top .hierarchy-editor-list__sticky-top__rem-container .rem-text {     background-color: #F8F8F9;     border-style: none;     color: #535666  } #hierarchy-editor .rem-container--sticky-document-title .rem-text {     font-size: 18px;     color: #F8F8F9;     border-style: none; } #hierarchy-editor #hierarchy-editor-list__sticky-top__container #hierarchy-editor-list__sticky-top {     background-color: #F8F8F9;     color: #535666;     padding-left: 0px;     margin-left: -13px;  } .remInPortalBlue {     border-style: none; } .remInPortal {     border-style: none; } #hierarchy-editor .indented-hierarchy-editor-remPortal {     border-style: none; } #hierarchy-editor #hierarchy-editor-list__sticky-top__container #hierarchy-editor-list__sticky-top #hierarchy-editor-list__sticky-top__bottom {     border-bottom: 6px solid #c8c8c8;     border-radius: 10px; }
``` 
            - 11 Sharing document ^^(uploaded 31 Jan 2021)^^
                - ```css
.article-publish-confirmation {     color: #535666; } .ui.checkbox+label, .ui.checkbox label {     color: #535666; }  ArticleViewer #ArticleViewerTop {     color: #535666; }  #ExamplesPageContainer #ExamplesPageContent, #export-container #export, #HelpPage #HelpPageContent, #sign-up-page-container #sign-up-page, #StatsPage #StatsPageContent, .centered-page, .document--narrow {     background-color: #F8F8F9;     color: #535666; }
``` 
            - 12 Settings page ^^(uploaded 31 Jan 2021)^^
                - ```css
.settings-page .settings-page__sidebar {     min-width: 195px;     max-height: 100%;     display: flex;     flex-direction: column;     border-color: rgb(59, 70, 75,0.5);     border-right: solid rgb(59, 70, 75,0.5);     border-width: 1;     background-color: #3B464B; } .settings-page .settings-page__sidebar .settings-page__sidebar__link {     border-color: #3B464B;     color: rgb(248, 248, 249, .6);     font-size: 17px;     padding: 10px 10px 10px 20px;     border-bottom: solid rgb(59, 70, 75,0.5);     border-width: 0;     display: flex;     align-items: center; } .settings-page .settings-page__sidebar .settings-page__sidebar__title {     color: rgb(248, 248, 249, .6);     font-weight: 700;     font-size: 24px;     margin: 20px; } .settings-page label {     font-size: 14px!important;     color: #535666; } .settings-page .settings-page__content .settings-page__content-inner {     padding: 30px;     color: #535666; } .settings-page__option {     margin-top: 10px;     padding-bottom: 10px;     display: flex;     border-width: 1px; } .settings-page .settings-page__sub-header {     border-width: 1px;     color: #535666;     font-size: 18px;     margin: 40px 0 10px;     padding-bottom: 5px;     font-weight: 700; } .settings-page__option .settings-page__text .settings-page__text__subtext {     color: rgb(59, 70, 75,0.5);     margin-top: 5px; } .settings-page .settings-page__sidebar .settings-page__sidebar__link:hover {     background-color: rgb(73,83,88,0.4); } .settings-page .settings-page__sidebar .settings-page__sidebar__link--active {     font-weight: 700;     background-color: #495358;     border-left-style: solid;     border-left-width: 3px;     border-left-color: #41668C;     } .settings-page__option .settings-page__input .settings-page__input-box {     padding-right: 1rem;     padding-top: 5px;     padding-bottom: 5px;     padding-left: 5px;     border-style: none;     border-radius: 4px;     background-color: #E8F0FC; }
``` 
        - Lightblue 2.0
            - Whole code large block
                - ```css
:root {
    --main-background-c: #fff;     /* Main Window, Bottom Bar, Doc View, Sticky Top, Pages, Queue */
    --secondary-background-c: #fbfbfb;     /* Sidebar, Quotes, icons, Portals, Embedded Search, Settings Menu */
    --elevated-background-c: #fbfcfc;     /* Queue Cards, Popups */
    --hover-background-c: rgba(173, 216, 230, .5);     /* Hover */
    
    --border-c: #eee;

    --font-c: #222;
    --font-dark-c: #787878;
    --font-background-c: #aaa;

    --font-red-c: #f06f73;
    --blue-c: #add8e6;
    
    --main-font-spacing: 0.01em;
    --bold-font-spacing: 0.02em;
    --semiwide-font-spacing: 0.05em;
    --wide-font-spacing: 0.1em;

    --normal-font-weight: 200;
    --focus-font-weight: 300;
    --bold-font-weight: 380;
    }  

    div::-webkit-scrollbar {
        width: 6px !important;
        height: 2px !important;
    }
    div::-webkit-scrollbar-track {
        background-color: transperant !important;     
    }
    div::-webkit-scrollbar-thumb {
        background-color: rgba(200, 200, 200, .3) !important;
        border-radius: 10px!important;
    }
    div::-webkit-scrollbar-thumb:hover {
        box-shadow: 0px 0px 4px 1px rgba(200, 200, 200, .6) inset;  
    }
    
    .rem-bullet, .rem-bullet--in-list {  
        margin-bottom:0.35em;
    }

    .rem-bullet__container .rem-bullet--all-children-visible { 
        margin-bottom: 0.35em;
    }

    .rem-indented-indicator {
            color: #fafafa;
            font-size: 0.5em;
            opacity: 0.6;
    }

            
    .rem-reference.button.rem-reference-link.searchKeywordHighlight {
        padding: 0px 4px;
        border: none;
        border-radius: 4px;
        background-color: var(--hover-background-c);
    }    
        
    /* Custom colors for highlighting:  */

    .highlight-color--red {
        background-color: var(--highlight-red-c)!important;
        padding: 0px 5px;
    }

    .highlight-color--orange {
        background-color: var(--highlight-orange-c)!important;
        padding: 0px 5px;
    }

    .highlight-color--yellow {
        background-color: var(--highlight-yellow-c)!important;
        padding: 0px 5px;
    }

    .highlight-color--green {
        background-color: var(--highlight-green-c)!important;
        padding: 0px 5px;
    }

    .highlight-color--blue {
        background-color: var(--highlight-blue-c)!important;
        padding: 0px 5px;
    }

    .highlight-color--purple {
        background-color: var(--highlight-purple-c)!important;
        padding: 0px 5px;
    }

    .rem-text {
        padding-left: 25px!important;
    }
    
    /* Main */

    body {
        font-size: 14px;
        font-family: "Helvetica Neue";
        font-weight:200;
        letter-spacing: var(--main-font-spacing);
        color: var(--font-c);
        background: var(--main-background-c);
    }

    div {
        font-family:"Helvetica Neue";
        font-weight: 200;
        font-size: 1em;
        margin: 0px;
        padding: 0px;
    }

    :focus {
        outline: none;
    }

    h1 {
        font-size: 24px;
        font-weight: 400;
    }

    h2 {
        font-size: 21px;
        font-weight: 350;
    }

    h3 {
        font-size: 18px;
        font-weight: 330;
    }

    a {
        color: #555;
        text-shadow: none !important;
    }

    .bold {
        letter-spacing: var(--bold-font-spacing);
        color: var(--font-c);
        font-weight:300;
    }

    #code-node,
    #quote,
    .quote {
    	font-style: italic;
        background-color: #fafafa;
        border: none;
        color: var(--font-dark-c);
        padding: 1px;
        padding-left: 7px;
        padding-right: 7px;
    }

    #hierarchy-editor .rem-header--1 {
        font-size: 18px;
        font-weight: var(--focus-font-weight);
        background-color: transparent;
        letter-spacing: var(--bold-font-spacing);
    }
    
    /* Logo */

    #logo {
        opacity: 0.4;
        filter: grayscale(100%) brightness(105%);
    }

    #logo:hover {
        opacity: 0.55;
        filter: grayscale(100%) brightness(105%);
    }

    /* Icons */

    i.icon {
        color: rgba(25, 25, 25, 0.35)!important;
    }

    i.icon:hover {
        color: rgba(25, 25, 25, 0.5)!important;
    }

    i.icons .corner.icon {
        text-shadow: 
            -1px -1px 0 var(--secondary-background-c),
            1px -1px 0 var(--secondary-background-c),
            -1px 1px 0 var(--secondary-background-c),
            1px 1px 0 var(--secondary-background-c);
    }

    /* Left Sidebar */

    #homepage #content #document-sidebar,
    #main #content #document-sidebar {
        border-right: none;
        box-shadow: none;
        background-color: var(--secondary-background-c);
        color: var(--font-dark-c);
    }

    #homepage #content #document-sidebar .document-sidebar__linkQueue,
    #main #content #document-sidebar .document-sidebar__linkQueue {
        margin-top: 5px;
    }

    #homepage #content #document-sidebar #document-sidebar__link,
    #main #content #document-sidebar #document-sidebar__link {
        padding: 5px;
        font-weight: var(--focus-font-weight);
        letter-spacing: var(--semiwide-font-spacing);
        color: var(--font-dark-c);
    }

    #homepage #content #document-sidebar #document-sidebar__link:hover,
    #main #content #document-sidebar #document-sidebar__link:hover,
    #document-sidebar__hidden-link__container:hover {
        font-weight: var(--focus-font-weight);
        background: var(--hover-background-c);
    }

    #homepage #content #document-sidebar .document-sidebar__linkOpen,
    #main #content #document-sidebar .document-sidebar__linkOpen {
        font-weight: var(--normal-font-weight);
        background: var(--hover-background-c) !important;
        padding-left: 5px !important;
    }


    #homepage #content #document-sidebar #DocumentationList,
    #homepage #content #document-sidebar #documentList,
    #main #content #document-sidebar #DocumentationList,
    #main #content #document-sidebar #documentList {
        margin-top: 5px;
        letter-spacing: var(--bold-font-spacing);
        line-height: 1.2;
    }

    #homepage #content #document-sidebar #DocumentationList .documentListHeader:hover,
    #homepage #content #document-sidebar #DocumentationList .document-list-item:hover,
    #homepage #content #document-sidebar #documentList .documentListHeader:hover,
    #homepage #content #document-sidebar #documentList .document-list-item:hover,
    #main #content #document-sidebar #DocumentationList .documentListHeader:hover,
    #main #content #document-sidebar #DocumentationList .document-list-item:hover,
    #main #content #document-sidebar #documentList .documentListHeader:hover,
    #main #content #document-sidebar #documentList .document-list-item:hover {
        font-weight: var(--focus-font-weight);
        background: var(--hover-background-c);
    }

    #homepage #content #document-sidebar #DocumentationList .document-list-item--opened,
    #homepage #content #document-sidebar #documentList .document-list-item--opened,
    #main #content #document-sidebar #DocumentationList .document-list-item--opened,
    #main #content #document-sidebar #documentList .document-list-item--opened {
        font-weight: var(--normal-font-weight);
        background: var(--hover-background-c);
    }

    #homepage #content #document-sidebar #document-sidebar__bottom-menu,
    #main #content #document-sidebar #document-sidebar__bottom-menu {
        padding-top: 8px;
        font-size: 0.82em;
        font-weight: var(--normal-font-weight);
        border-top: 1px solid var(--border-c);
        box-shadow: none;
    }
        
    #homepage #content #document-sidebar #document-sidebar__bottom-menu #document-sidebar__bottom-menu--buttons, 
    #main #content #document-sidebar #document-sidebar__bottom-menu #document-sidebar__bottom-menu--buttons {
        white-space: normal;
    }

    #homepage #content #document-sidebar #document-sidebar__bottom-menu .document-sidebar__current-route,
    #main #content #document-sidebar #document-sidebar__bottom-menu .document-sidebar__current-route {
        border: 1px solid var(--hover-background-c) !important;
        background: var(--hover-background-c) !important;
        color: var(--font-dark-c) !important;
    }

    #DocumentationList #documentation-list__section__title {
        font-weight: 330;
        letter-spacing: var(--semiwide-font-spacing);
    }

    #DocumentationList #documentation-list__section {
        border-left: thin solid var(--border-c);
    }

    #DocumentationList {
        border-left: transparent;
    }

    #KeyboardShortcuts,
    #KeyboardShortcuts #KeyboardShortcutsTitle,
    #KeyboardShortcuts #KeyboardShortcutSectionHeader {
        background-color: var(--secondary-background-c)!important;
        color: var(--font-dark-c);
        border: none;
        line-height: 1.3;
        font-size: 12px;
    }

    #DocumentationList #documentation-list__section__large-title {
        font-weight: 320;
        background: var(--secondary-background-c)!important;
        padding-left: 5px !important;
        border: none;
    }

    #homepage #content #document-sidebar a,
    #main #content #document-sidebar a {
        color: var(--font-dark-c)!important;
    }

    #homepage #content #document-sidebar a:hover,
    #homepage #content #document-sidebar a:visited,
    #main #content #document-sidebar a:hover,
    #main #content #document-sidebar a:visited {
        color: var(--font-dark-c)!important;
    }

    #document-sidebar__hiden-link__container:hover {
        background-color: var(--hover-background-c);
    }

    #document-sidebar__hiden-link__container {
        background-color: var(--secondary-background-c);
    }

    /* Bottom Bar */

    .hierarchyEditorToolbarContainerOpened {
        background-color: var(--main-background-c);
        height: 37px;
    }

    #hierarchyEditorToolbarContainer #hierarchyEditorGlobalInsert .rich-text-editor {
        background-color: var(--secondary-background-c);
        border: 0px solid var(--border-c);
        border-radius: 7px;
        padding-left: 10px;
        width: 220px;
    }

    .hierarchyEditorToolbarContainerOpened #HierarchyEditorToolbar {
        border-top: 0px solid var(--border-c);
    }

    .hierarchyEditorToolbarContainerOpened #HierarchyEditorToolbar .HierarchyEditorToolbarItem {
        color: #888;
    }

    .hierarchyEditorToolbarContainerOpened #HierarchyEditorToolbar .ToolbarDuplicateKeyButton {
        color: var(--font-red-c);
        border-radius: 3px;
        border: 1px solid var(--font-red-c);
        padding: 2px 5px;
        font-size: 12px;
    }

    /* Documents List */
    
    .ReactVirtualized__Table__headerRow {   
        text-align: center;
        color: var(--font-background-c);
        font-weight: var(--normal-font-weight);
        letter-spacing: var(--wide-font-spacing);
        font-size: 13px;
        padding-bottom: 5px;
        margin-top: 25px;
    }
    
    .ReactVirtualized__Table__row[style*="background-color: rgba(1\, 1\, 1\, 0.1);"],   
    .ReactVirtualized__Table__row {
        color: var(--font-c)!important;
        background-color: transparent!important;
        border-top: 1px solid var(--border-c);
    }
    
    .ReactVirtualized__Grid__innerScrollContainer > * {
        margin-top: 0px;
    }
  
     #DocumentTable .DocumentLink:hover {
        background-color: transparent;
        color: var(--font-c)!important;
    }

    #DocumentTable .DocumentLink {
        color: var(--font-background-c)!important;
    }

    #DocumentTable a:hover,
    #DocumentTable .blackLinks a:hover {
        font-weight: var(--focus-font-weight);
        letter-spacing: -0.01em;
    }
    
    .ReactVirtualized__Table__rowColumn[style*="flex: 0 1 690px;"]:hover {
        background-color: #5da1b44d!important;
    }
    
    #DocumentTable .Cell {
        margin-left: auto;
        margin-right: auto;
    }
    
    /* Sticky Top */

    #hierarchy-editor-list__sticky-top__container {
        background-color: transparent;
    }

    #hierarchy-editor #hierarchy-editor-list__sticky-top__container #hierarchy-editor-list__sticky-top {
        background-color: var(--main-background-c);
        border-top: 1px solid var(--main-background-c);
    }

    #hierarchy-editor #hierarchy-editor-list__sticky-top__container #hierarchy-editor-list__sticky-top #hierarchy-editor-list__sticky-top__bottom {
        margin-left: 0px;
        border-width: thin;
        border-bottom-style: solid;
        border: 1px solid var(--main-background-c);
        background-image: linear-gradient(to bottom, #eee 0%, var(--main-background-c) 100%);
        padding: 2px;
    }

    #hierarchy-editor .rem-container--sticky-document-title {
        font-weight: var(--normal-font-weight);
        letter-spacing: var(--semiwide-font-spacing);
        color: var(--font-c);
        background-color: var(--main-background-c);
    }

    #hierarchy-editor #hierarchy-editor-list__sticky-top__container #hierarchy-editor-list__sticky-top .hierarchy-editor-list__sticky-top__rem-container {
        background-color: var(--main-background-c);
        border: none;
    }

    #hierarchy-editor-list__sticky-top__container .remInPortalBlue {
        background-color: var(--main-background-c);
    }

    #hierarchy-editor-list__sticky-top .indented-hierarchy-editor-remPortal {
        display:none;
    }

    /* Top */

    #document-parents .parent-link {
        color: var(--font-background-c);
        opacity: 0.0;
    }

    #document-parents i.icon {
        display: none;
    }

    #document-parents .join-arrow {
        font-size: 12px;
        color: #bbb;
        opacity: 0.65;
    }

    #ArticleViewer #ArticleContent #ArticleViewerTitle {
        letter-spacing: var(--semiwide-font-spacing);
        color: var(--font-c);
        padding-top: 5px;
    }

    .ArticleLink {
        border: none;
        color: var(--font-background-c);
        font-style: italic;
        margin-left: 10px;
        padding-top: 1.5em;
        font-size: 12px;
        letter-spacing: var(--bold-font-spacing);
    }

    .ArticleLink i.newspaper.icon {
        display: none;
    }

    #document-parents.documenParentsLinksDisabled {
        padding-bottom: 0.5em;
    }

    #ArticleViewer #ArticleContent #ArticleViewerSource {
        color: var(--font-background-c);
        font-size: 12px;
        letter-spacing: var(--bold-font-spacing);
    }

    #ArticleViewer #ArticleContent #ArticleViewerAuthor {
        font-style: italic;
        margin-left: 10px;
        padding-top: 4px;
        color: var(--font-background-c);
        font-size: 12px;
        letter-spacing: var(--bold-font-spacing);
        font-weight: var(--focus-font-weight);
    }

    #ArticleViewer #ArticleContent #ArticleViewerReadingTime {
        margin-left: 10px;
        padding-top: 4px;
        color: var(--font-background-c);
        font-size: 12px;
        letter-spacing: var(--bold-font-spacing);
    }


    #hierarchy-editor .rem-header--3 {
        font-size: 15px;
        font-weight: 300;
        font-family:"Helvetica Neue";
        letter-spacing: var(--semiwide-font-spacing);
    }

    #hierarchy-editor .rem-header--,
    #hierarchy-editor .rem-header--1,
    #hierarchy-editor .rem-header--2,
    #hierarchy-editor .rem-header--3 {
        color: var(--font-c);
    }

    #hierarchy-editor .rem-header--2 {
    	font-family:"Helvetica Neue";
        font-weight: 350;
        font-size: 17px;
        
    }

    #hierarchy-editor .TreeNode {
        border-color: var(--border-c);
    }

    #hierarchy-editor .indented-hierarchy-editor-rem {
        border-color: var(--border-c);
    }

    /* Document Window */

    #ExamplesPageContainer #ExamplesPageContent,
    #ExportContainer #Export,
    #HelpPage #HelpPageContent,
    #SettingsPage #SettingsPageContent,
    #StatsPage #StatsPageContent,
    .centered-page,
    .document--narrow {
        background-color: var(--main-background-c);
    }
    
     #multiple-windows .multiple-windows__document {
        border: none;
        margin-right: 3.5px;
    }
    
    /* Trail History */

    #thinking-trail-history:hover #thinking-trail-history__container {
        background-color: var(--main-background-c);
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.5) 0px 0px 24px;
        border-bottom-right-radius: 4px;
        border-top-right-radius: 4px;
        margin: 0px;
    }
    
    #thinking-trail-history {
        margin: 2px;
    }
    
    #thinking-trail-history .thinking-trail-history__document .thinking-trail-history__document-dot {
        background-color: var(--elevated-background-c);
        border: 1px solid var(--blue-c);
        border-radius: 5px;
        width: 5px;
        height: 5px;
        margin-left: -1px;
    }
        
    #thinking-trail-history .thinking-trail-history__document .thinking-trail-history__document-dot:hover,
    #thinking-trail-history .thinking-trail-history__document-dot--active {
        background-color: var(--blue-c)!important;
        border: 1px solid var(--blue-c)!important;
        border-radius: 5px!important;
        width: 7px!important;
        height: 7px!important;
        box-shadow: none!important;
        margin-left: -2px!important;
    }
       
    #thinking-trail-history .thinking-trail-history__document .thinking-trail-history__children-bar {
        color: var(--blue-c);
    }
    
    #thinking-trail-history #thinking-trail-history__container {
        padding-top: 25px;
    }
    
    #thinking-trail-history .thinking-trail-history__document-height-offset {
        padding-top: 0.9px;
    }
    
    #thinking-trail-history .thinking-trail-history__document .thinking-trail-history__document-height-offset {    
        background-color: var(--blue-c);
    }
        
    #thinking-trail-history .thinking-trail-history__document .thinking-trail-history__document-dot__preview {
        padding: 2px 7px 0px 5px;
    }    
    
    #thinking-trail-history__document-list .thinking-trail-history__document-dot__preview:hover {
        color: var(--main-background-c);         
    }
    
    #thinking-trail-history #thinking-trail-history__document-list .thinking-trail-history__document-dot__preview {
        padding: 1px 5px;
        color: var(--font-dark-c);
    }
    
    #thinking-trail-history #thinking-trail-history__document-list .thinking-trail-history__document-dot__preview:hover {
        background-color: var(--hover-background-c);
        color: var(--font-c);
    }
    
    #thinking-trail-history__container .grey.close.icon {
        color: var(--blue-c)!important;
    }

    /* Title */

    #document #DocumentTopRow {
        margin-top: 10px;
    }

    #document #actionRequiredDocumentTitle,
    #document .document-title {
        font-size: 20px;
        letter-spacing: var(--bold-font-spacing);
        color: var(--font-c);
    }

    .document-source {
        margin-left: 20px;
        margin-top: 5px;
    }

    #document #AddNewDocumentButtonSmall:hover {
        color: #999;
    }

    /* Bullets */

    .rem-bullet, .rem-bullet--in-list {
        width: 0.7em;
        height: 0.7em;
        border-radius: 100%;
        background-color: #ffffff;
        display: inline-block;
        border: 1px solid #fff; 
        opacity: 1;
        box-shadow: 0px 0px 0px 1px #fff;
    }

    .rem-bullet[style*="border-width: 0px;"] {
        border-width: 2px!important;
    }

    .rem-bullet__container .rem-bullet--all-children-visible {
        width: 0.5em;
        height: 0.5em;
        border-radius: 100%;
        background-color: #fff;
        display: inline-block;
        border: none; 
        box-shadow: none;
    }

    .rem-container--not-in-article .rem-bullet__container:hover .rem-bullet--all-children-visible,
    .rem-container--not-in-article .rem-bullet__container:hover .rem-bullet, .rem-container--not-in-article .rem-bullet__container:hover .rem-bullet--in-list {
        border: 0.4px solid #ddd;
    }
    
    /* Rems */

    #hierarchy-editor .rem-container--default .rem-bullet__container, #hierarchy-editor .rem-container--default .rem-hamburgerGeneric, #hierarchy-editor .rem-container--default .toggleCollapseButton {
        margin-top: 0.4em;
    }
        
    #hierarchy-editor .is-toolbar-previous-focus-rem {
        border: thin solid rgba(93, 161, 180, .4);
        box-shadow: none;
    }
   
    .selected-rem {
        background-color: rgba(93, 161, 180, .3);
        box-shadow: none;
    }

    #hierarchy-editor .rem-container--focused {
        background-color: transparent;
        box-shadow: none;
    }
        
    .work-in-progress-rem {       
        background-color: transparent;
        padding: 0px;
    }

    /* References */

    .rem.portal-rem--blue.portalRem {
        background-color: transparent!important;
        border: none!important;
        box-shadow: none!important;
    }

    #hierarchy-editor .portal-rem .portal-rem-top {
        border-top: 2px solid transparent;
        background-color:transparent;
    }

    #hierarchy-editor .portal-rem .portal-rem-top:hover {
        cursor: pointer;
    }

    #hierarchy-editor .portal-rem--selected, 
    #hierarchy-editor .portal-rem--selected .portal-rem-top {
        border-color: transparent!important;
        box-shadow: -0.5px 9px 0px 0.5px var(--secondary-background-c);
    }

    #show-embedded-search-button {
        padding: 4px;
        margin-right: 0;
        margin-top: 4px;
        margin-left: -6px;
        border: none;
        color: var(--font-background-c);
    }

    #show-embedded-search-button i.caret.down.icon {
        opacity: 0.5;
    }
        
    #hierarchy-editor .portal-rem {  
        border: none;
    }
        
    #hierarchy-editor .portal-rem--blue {  
        border-color: transparent;
    }  

    #hierarchy-editor .portal-rem-top--embedded-search-top {
        border-top-style: none !important;
    }

    i.refresh.icon {
        opacity: 0.5;
        margin-top: 0.2em;
    }

    i.refresh.icon:hover {
        opacity: 0.85;
    }

    .embeddedSearch {
        border-radius: 0.4em;
        border: 1px solid var(--border-c);
        text-decoration: none;
        padding: 5px 5px 5px 10px;
        color: var(--font-c);
        letter-spacing: var(--semiwide-font-spacing);
        background-color: var(--secondary-background-c);
        margin-left: 9px;
        margin-bottom: 8px;
    }

    .remInEmbeddedSearch {
        border-color: var(--secondary-background-c);
        background-color: var(--secondary-background-c);
    }

    #hierarchy-editor .search-portal-tree-node {
        border:none;
        border-radius: 0px;
        background-color: transparent;
        margin-left: 5px;
        margin-right: 25px;
    }

    #hierarchy-editor .rem-container__top-level-spacer .rem-container__top-level-spacer__inner {
        display: none;
    }

    #hierarchy-editor .rem-container__top-level-spacer {
        display: none;
    }

    #Hierarchy-editor .HierarchyEditorAfterPortal {
        border: 1px solid var(--border-c) !important;
        box-shadow: none;
        border-radius: 5px;
        background-color: var(--main-background-c);
    }

    #hierarchy-editor .portal-rem--embedded-search {
        background-color: transparent!important;
        border: none!important;
        box-shadow: none!important;
    }

    #hierarchy-editor .rem-container--not-included-in-document-scope, 
    #hierarchy-editor .notIncludedInDocumentScope .notIncludedAncestorClickable {
        text-decoration: none;
        color: #bbb;
    }

    #hierarchy-editor .rem-container--not-included-in-document-scope .join-arrow { 
        font-size: 17px;
        color: grey;
    }

    #hierarchy-editor .isSearchResult {
        background-color: var(--hover-background-c);
        padding: 5px 5px 5px 0px;
        border-radius: 5px;
        margin: 0px 7px 7px 0px; 
    }

    .isSearchResult .rem-bullet__container { 
        margin-left: 4px;
        padding-top: 0.35em;
    }
    
    .isSearchResult .rem-bullet__container i { 
        margin-left: 3px;
        padding-top: 0.6em;
    }

    .search-portal-tree-node  > .tree-node-container { 
        background-color: var(--secondary-background-c);
        border-top-color: var(--secondary-background-c);
        border-right-color: var(--secondary-background-c);
        border-bottom-color: var(--secondary-background-c);
        border-left: 1px solid transparent !important;
        box-shadow: 0px 0px 4px 0px rgba(0, 0, 0, .5);
        border-radius: 4px;
        padding: 5px;
        margin-bottom: 10px;
        margin-top: 5px;
    }

    .searchKeywordHighlight {
        background-color: transparent;
    }

    #hierarchy-editor .portal-tree-node {
        background-color: var(--secondary-background-c);
        letter-spacing: var(--semiwide-font-spacing);
        border-top-color: var(--secondary-background-c) !important;
        border-right-color: var(--secondary-background-c) !important;
        border-bottom-color: var(--secondary-background-c) !important;
        border-left: 1px solid transparent !important;
        box-shadow: 0px 0px 4px 0px rgba(0, 0, 0, .5);
        border-radius: 3px;
    }
 
    .import-all-contents-button__container {
        margin-top: 8px;
    }

    .ImportAllContentsButton {
        opacity: 0.5;
    }

    .ImportAllContentsButton:hover {
        color: grey;
        opacity: 0.8;
        font-weight: var(--focus-font-weight);
    }

    #hierarchy-editor .remChildren .ImportAllContentsButton {
        float: none;
        text-align: right;
    }

    /* List Item */

    #hierarchy-editor .TreeNodeListItems {
        border-left: solid;
        border-color: var(--border-c);
    }

    #hierarchy-editor .rem-container--importable .rem-bulletPlus {
        color: #aaa;
    }

    #hierarchy-editor .rem-container--importable .rem-bulletPlus:hover {
        color: var(--font-background-c);
        text-shadow: none;
    }

    #hierarchy-editor .hierarchy-editor__after-portal,
    #hierarchy-editor .indented-hierarchy-editor-rem--after-portal-embedded-search {
            border: none;
    }


    /* Tags */

    #hierarchy_editor__tag-bar #hierarchy-editor__tag-bar__tag,
    #hierarchy-editor__tag-bar__tag {
        border-radius: 4px;
        color: var(--font-background-c);
        padding: 1px 5px;
        letter-spacing: var(--bold-font-spacing);
        opacity: 1;
        margin-top: 5px;
        background-color: #f4f4f4;
    }

    #hierarchy-editor__tag-bar__tag .rem-indented-indicator {
        display: none;
    }

    #hierarchy_editor__tag-bar #hierarchy-editor__tag-bar__tag span.RichTextViewer {
        padding-left: 0px;
    }

    #hierarchy_editor__tag-bar #hierarchy-editor__tag-bar__tag #hierarchy-editor__tag-bar__tag__delete {
        padding: 7px;
        margin-left: -3px;
        color: var(--main-background-c);
        font-size: 12px;
        top: 0.8px;
    }

    #hierarchy_editor__tag-bar #hierarchy-editor__tag-bar__tag #hierarchy-editor__tag-bar__tag__delete:hover {
        color: var(--font-background-c);
    }

    .work-in-progress-tag {
        border-radius: 4px;
        color: var(--font-background-c);
        padding: 1px 5px;
        background-color: #f4f4f4;
    }
    
    /* Links */

    .rem-reference-link {
        color: var(--main-link-c);
    }

    .rem-reference-link:hover {
        background-color: transparent;
        border: none;
        font-weight: var(--focus-font-weight);
    }

    .rem-reference--focused {
        border: none;
        font-weight: var(--focus-font-weight);
        box-shadow: none!important;
    }

    .rem-reference--highlighted {
        border: none;
        box-shadow: none;
        font-weight: var(--focus-font-weight);
    }

    .rem-reference {
        border-radius: 5px;
        transition: none;
    }

    .rem-reference.rem-reference-link .file.text.small.icon {
        display: none;
    }

    #rem-reference__exclude-type-parent {
        padding-left: 4px;
        padding-right: 4px;
        padding-bottom: 2px;
        padding-top: 0px;
        margin-right: 3px;
        top: -2px;
        border-radius: 4px;
        color: var(--main-link-c);
        font-size: 11px;
        opacity: 1;
        border: 1px solid #eee;
        background-color: var(--main-background-c);
    }

    .rem-reference.rem-reference-link .gray {
        color: var(--font-dark-c);
    }

    .LinkNode {
        text-decoration: none;
        color: var(--main-link-c);
    }

    .link-node--focused {
        color: var(--main-link-c);
        font-weight: var(--focus-font-weight);
    }

    .workInProgressRem {
        padding: 0px;
        background-color: transparent;
    }
    .workInProgressRem > span::first-letter {
        visibility: hidden;
    }

    /* Flash Highlight */

    .flash {
        background-color: transparent !important;
        box-shadow:none;
        border: none;
    }

    /* Cloze */

    .cloze {
        background-color: #eee;
        padding: 0px 4px;
        text-decoration: none;
        border-radius: 4px;
        font-weight: var(--focus-font-weight);
    }

    /* Image Occlusion */

    .image-occlusion__toolbar > .button {
        font-size: 1em;
    }

    .image-occlusion__toolbar > .button > .icon {
        color: var(--hover-background-c)!important;
    }

    .image-occlusion .image-occlusion__toolbar .image-occlusion__toolbar__dropdown {
        border: thin solid var(--main-background-c);
        background-color: var(--main-background-c);
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.5) 0px 0px 24px;
        border-radius: 4px;
    }

    #clozeChangeDropdown #ClozeIdentifierInfo {
        color: var(--font-c);
    }

    #clozeChangeDropdown .ClozeIdentifierSelected {
        background-color: hsla(193, 37%, 54%, .3);
    }

    #clozeChangeDropdown #ClozeIdentifierOption {
        border: none;
    }

    #clozeChangeDropdown #ClozeIdentifierOption:hover {
        background-color: rgba(93, 161, 180, .7);
    }

    /* Queue Cards */

    .Queue {
        background-color: var(--elevated-background-c);
        border: thin solid var(--hover-background-c);
        border-radius: 4px;
        box-shadow: 0px 0px 3px 1px rgba(140, 167, 176, .25);
    }

    .Queue #queue__title {
        background-color: var(--elevated-background-c);
        box-shadow: 0px 1px 8px -2px #ccc;
        letter-spacing: var(--semiwide-font-spacing);
        color: var(--main-link-c);
        border-radius: 3px;
    }

    .Queue #QueueBadge,
    .Queue #queue__badge {
        color: var(--font-blue-c);
        padding: 2px 4px;
        border-radius: 4px;
        letter-spacing: var(--bold-font-spacing);
        background-color: var(--main-background-c);
        border: 1px solid rgba(173, 216, 230, 0.3);
        box-shadow: 0px 0px 4px 1px #eee;
        font-size: 12px;
    }

    .Queue #queue__title #QueueStreakIndicator {
        color: var(--font-blue-c);
        letter-spacing: var(--bold-font-spacing);
    }

    .Queue #queue__progress-bar[style*="background-color: darkgrey;"],
    .Queue #queue__progress-bar[style*="background-color: green;"] {
        background-color: var(--font-blue-c) !important;
    }

    .spacedRepetition .spaced-repetition__prompt .indented-rem .rem-bullet__document {
        background-color: var(--elevated-background-c);
        border-radius: 3px;
        display: inline-block;
        padding: 4px;
    }

    .spacedRepetition .spaced-repetition__prompt {
        font-size: 15px;
        line-height: 1.4;
    }

    .spacedRepetition .spaced-repetition__prompt .bold {
        font-weight: var(--normal-font-weight);
    }

    .spacedRepetition .spacedRepetitionAnswer {
        border-color: var(--font-blue-c);
    }

    .queue--desktop {
        box-shadow: 0px 0px 1px 10px white;
    }

    #ArticleQueue .QueueFocused {
        box-shadow: none;
    }

    .spacedRepetition .spaced-repetition__prompt .indented-rem .rem-bulletDocument {
        color: var(--font-blue-c);
        font-size: 13px;
        letter-spacing: var(--bold-font-spacing);
        margin-bottom: 5px;
        font-weight: var(--focus-font-weight);
        background-color: var(--elevated-background-c);
    }

    .spacedRepetition .fill-in-the-blank {
        color: var(--font-blue-c);
        border: none;
    }

    .spacedRepetition .spaced-repetition__bottom {
        background-color: var(--elevated-background-c);
        letter-spacing: var(--semiwide-font-spacing);
        color: var(--font-blue-c);
        font-weight: var(--focus-font-weight);
        font-size: 13px;
    }

    .spacedRepetition .spaced-repetition__reveal {
        background-color: var(--elevated-background-c);
    }

    .spacedRepetition .spaced-repetition__prompt .indented-rem .rem-bullet__document i.icon {
        display: none;
    }

    .spacedRepetition .fill-in-the-blank {
        color: var(--font-blue-c);
    }

    .queue__buttons {
        background-color: var(--elevated-background-c);
    }
    
    .spacedRepetition .queue__response-button--big > img {
        display: none;
    }
      
    .spacedRepetition .queue__response-button--big[data-tip*="(1/4)"]:after {
    content: "☹️";
    }
    .spacedRepetition .queue__response-button--big[data-tip*="(2/4)"]:after {
    content: "😐";
    }
    .spacedRepetition .queue__response-button--big[data-tip*="(3/4)"]:after {
    content: "🙂";
    }
    .spacedRepetition .queue__response-button--big[data-tip*="(4/4)"]:after {
    content: "😊";
    } 

    .spacedRepetition .queue__response-button--big i.icon {
        display: none;
    }

    #leech-card #leech-card__header i.frown.outline.icon:before {
        display: none;
    }

    #leech-card #leech-card__header i.frown.outline.icon:after {
        content: "☹️";
    }

    #leech-card #leech-card__header {
        margin: 20px;
        font-weight: var(--focus-font-weight);
    }

    #leech-card #leech-card__contents {
        border: 1px solid var(--elevated-background-c);
        border-radius: 3px;
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.5) 0px 0px 24px;
    }

    #leech-card #leech-card__fixes .LeechAction,
    #leech-card #leech-card__fixes ul li {
        text-decoration: none;
        color: var(--font-blue-c);
        font-weight: var(--normal-font-weight);
        letter-spacing: var(--bold-font-spacing);
    }

    #leech-card #leech-card__fixes .LeechAction:hover {
        text-decoration: none;
        color: var(--font-blue-c);
        font-weight: var(--focus-font-weight);
        letter-spacing: var(--bold-font-spacing);
    }

    #leech-card .leech-card__bottom {
        background-color: var(--elevated-background-c);
        letter-spacing: var(--semiwide-font-spacing);
        color: var(--font-blue-c);
        font-weight: var(--focus-font-weight);
        font-size: 13px;
    }

    .queue__response-button:hover {
        background-color: var(--elevated-background-c);
        color: var(--font-blue-c);
        font-weight: 700;
    }

    #milestone .daily-checkpoint {
        color: var(--font-blue-c) !important;
    }

    #milestone .badge {
        border: 1px solid var(--elevated-background-c);
        border-radius: 3px;
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.5) 0px 0px 24px;
    }

    .queue__response-button,
    .accuracy-item {
        background-color: var(--elevated-background-c);
        color: var(--font-blue-c);
        font-weight: var(--focus-font-weight);
        letter-spacing: var(--bold-font-spacing);
    }

    .queue__response-button:hover,
    .accuracy-item:hover {
        background-color: var(--elevated-background-c);
        color: var(--font-blue-c);
        font-weight: 700;
        letter-spacing: var(--bold-font-spacing);
    }

    #milestone h1 {
        color: var(--font-blue-c);
        font-weight: var(--bold-font-weight);
    }

    .Queue .queue__no-items .success {
        font-weight: var(--bold-font-weight);
        color: var(--font-blue-c);
        padding-bottom: 20px;
        font-size: 15px;
        letter-spacing: var(--semiwide-font-spacing);
    }

    #document-sidebar__link__queue-indicator {
        font-size: 12px;
    }

    .black-out--enable {
        background-color: var(--main-background-c);
    }

    .addListItemButton {
        border: none;
        border-radius: 3px;
        background-color: var(--hover-background-c);
        padding: 1px 7px;
        color: #888;
    }

    #QueueCollapsed {
        background-color: var(--hover-background-c);
        color: #ccc;
    }

    #QueueCollapsed #QueueCollapsedSmall {
        font-size: 13px;
    }

    #hierarchy-editor__embedded-queue-mode-toggle {
        color: #888!important;
        margin-bottom: 5px!important;
    }

    #hierarchy-editor__embedded-queue-mode-toggle:hover {
        color: var(--font-background-c)!important;
    }

    /* Latex */

    .katex {
        font-size: 18px!important;
        border-radius: 4px;
        padding: 0px 7px;   
    }

    .LatexNodeFocused {
        border: none;
        border-radius: 4px;
        color: var(--font-c);
        padding: 0px 2px;
        background-color: transparent!important;
    }

    .LatexNode {
        text-decoration: none;
    }

    .LatexNode .latex-node__latex {
        border: none;
        margin-top: 5px;
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.5) 0px 0px 12px;
        border-radius: 4px;
        padding: 2px 7px;
        background-color: var(--main-background-c)!important;
    }

    /* Popups */

    /* Preview */

    #document-hover-preview {
        background-color: var(--main-background-c);
        border: 1px solid var(--elevated-background-c);
        border-radius: 4px;
        padding: 10px 0 10px 20px;
        font-weight: var(--normal-font-weight);
        color: var(--font-dark-c);
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.5) 0px 0px 12px;
    }

    /* Search links */

    .search-results {
        color: var(--font-dark-c);
        font-weight: var(--normal-font-weight);
        max-width: 500px;
        background-color: var(--elevated-background-c);
        border: none; 
        padding: 5px;
    }
    
    .rich-text-editor__search-results .search-results {
        border-radius: 5px;
        box-shadow: 
            rgba(15, 15, 15, 0.2) 0px 0px 0px 1px,
            rgba(15, 15, 15, 0.4) 0px 0px 6px,
            rgba(15, 15, 15, 0.6) 0px 0px 24px;
        border: 1px solid var(--elevated-background-c); 
    }
    
    .rich-text-editor__search-results .search-results #search-results__result:first-child,
    .rich-text-editor__search-results .search-results #search-results__result:last-child {
        border-radius: 0px;
    }
    
    #search-results__result:hover{
        border-radius: 0px;
    }

    .selectedResult {
        font-weight: var(--focus-font-weight);
        background-color: var(--hover-background-c);
        letter-spacing: -0.004em;
        border-radius: 0px;
    }

    #search-results__list #SearchResultsResult div span#quote {
        visibility: hidden;
        display: none;
    }

    .search-results #search-results__list #search-results__result:not(:last-child) {
        border-bottom: 1px solid var(--border-c);
    }

    #search-results__controls {
        padding-left: 10px;
        padding-right: 10px;
        padding-top: 8px;
    }

    #search-results__controls #search-results__control {
        border-color: var(--border-c);
    }

    /* Menu */

    .react-contextmenu--visible {
        background-color: var(--main-background-c);
        border: 1px solid var(--elevated-background-c);
        border-radius: 3px;
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.5) 0px 0px 12px;
    }

    .react-contextmenu--visible .hierarchy-editor__rem-menu {
        color: var(--font-dark-c);
    }

    .react-contextmenu--visible .hierarchy-editor__rem-menu,
    .react-contextmenu--visible .MenuItem {
        padding: 5px;
        border: none;
    }

    .react-contextmenu--visible .hierarchy-editor__rem-menu:hover {
        background-color: var(--hover-background-c);
    }

    .react-contextmenu--visible #menu-divider {
        border: none;
    }

    .react-contextmenu-item.react-contextmenu-submenu {
        padding: 5px;
    }

    .react-contextmenu-item.react-contextmenu-submenu:hover {
        background-color: var(--hover-background-c);
    }

    .react-contextmenu--visible i.icon {
        opacity: 0.6;
    }

    .color-button {
        border: thin solid var(--border-c);
    }

    .color-button {
        border: thin solid var(--border-c);
    }

    /* Link Popup */

    .link-node__popup {
        text-decoration: none !important;
    }

    .link-node__popup .content {
        text-decoration: none !important;
    }

    .ui.popup {
        color: var(--font-c);
        background-color: var(--main-background-c);
        border: 1px solid var(--elevated-background-c);
        border-radius: 3px;
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.5) 0px 0px 12px;
    }

    .link-node__popup {
        box-shadow: none !important;
    }

    .link-node__popup a:-webkit-any-link {
        text-decoration: none !important;
    }

    /* Hidden Rems Popup */

    #hierarchy-editor .HierarchyEditorChildrenList .children-list-content {
        background-color: var(--main-background-c);
        border: 1px solid var(--elevated-background-c);
        border-radius: 3px;
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.5) 0px 0px 12px;
    }

    #hierarchy-editor .HierarchyEditorChildrenList .children-list-content .childrenListItem {
        padding: 7px;
        border-bottom: solid;
        border-width: 1px;
        border-color: var(--border-c);
        color: var(--font-dark-c);
    }

    #hierarchy-editor .HierarchyEditorChildrenList .children-list-content .childrenListItem:hover {
        background-color: var(--hover-background-c);
    }

    #hierarchy-editor .hierarchy-editor__children-list--focused {
        border-color: transparent;
        color: var(--font-dark-c)!important;
        font-weight: var(--normal-font-weight);
    }
    
    /* Selected text menu */

    .rich-text-editor__selected-text-menu {
        background-color: var(--main-background-c);
        border: 1px solid var(--elevated-background-c);
        border-radius: 3px;
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.5) 0px 0px 12px;
    }

    .rich-text-editor__selected-text-menu .rich-text-editor__selected-text-menu__divider {
        border: thin solid var(--border-c);
    }

    .rich-text-editor__selected-text-menu .rich-text-editor__selected-text-menu__search {
        padding-top: 7px;
        padding-bottom: 7px;
        border-top: thin solid var(--border-c);
        padding-left: 0px;
        padding-right: 0px;
    }

    .rich-text-editor__selected-text-menu .search-results {
        box-shadow: none;
        width: 308px;
    }

    .rich-text-editor__selected-text-menu .selected-text-menu__button:hover {
        background-color: var(--main-background-c);
    }

    /* Document Options Menu */

    .ui.dropdown .menu {
        background-color: var(--main-background-c);
        border: 1px solid var(--elevated-background-c);
        border-radius: 3px;
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.5) 0px 0px 12px;
    }

    .ui.dropdown .menu > .item {
        color: var(--font-c);
        background-color: var(--elevated-background-c);
        border: 1px solid var(--elevated-background-c);
    }

    .ui.dropdown .menu > .divider {
        border-top: thin solid var(--border-c);
    }

    .ui.dropdown .menu > .item:hover{
        background: var(--hover-background-c);
        color: var(--font-c);
    }

    .ui.header .sub.header {
        background-color: inherit;
        color: var(--font-c);
    }

    .ui.dropdown .menu .selected.item,
    .ui.dropdown.selected {
        background-color: var(--elevated-background-c);
        color: var(--font-c);
        border: 1px solid var(--elevated-background-c);
    }

    .ui.header {
        color: var(--font-c);
    }

    .ui.pointing.dropdown > .menu:after {
        background: var(--elevated-background-c);
    }

    /* "/" Menu */

    .search-results {
        color: var(--font-dark-c);
        min-width: 300px;
        background-color: var(--main-background-c);
        border: 1px solid var(--elevated-background-c);
        border-radius: 3px;
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.5) 0px 0px 12px;
        font-size: 15px;
        max-width: 600px;
    }

    .search-results #search-results__list #search-results__result:hover {
        background-color: var(--hover-background-c);
    }

    .search-results #search-results__list #SearchResultsResult {
        padding: 5px;
        border-bottom: 1px solid var(--border-c);
    }

    .keycode {
        font-size: 70%;
        transform: none;
    }

    .keycode #quote{
        font-size: 118%;
    }

    #search-results__controls {
        font-size: 11px;
        padding-bottom: 7px;
    }
    
    /* Date Picker */

    .react-datepicker__month, 
    .react-datepicker__header,
    .react-datepicker, 
    .react-datepicker-wrapper {
        background-color: var(--elevated-background-c);
    }

    .react-datepicker__header {
        border-bottom: none;
        opacity: 0.5;
    }
    
    .react-datepicker__day, 
    .react-datepicker__day-name, 
    .react-datepicker__time-name, 
    .react-datepicker-time__header, 
    .react-datepicker__current-month {
        color: var(--font-c)!important;
    }

    .react-datepicker__day--in-range, 
    .react-datepicker__day--in-selecting-range, 
    .react-datepicker__day--selected {        
        background-color: var(--main-link-c);
        opacity: 0.8;
        color: var(--main-background-c)!important;
    }

    .react-datepicker__month-container {
        width: 300px;
    }

    .react-datepicker__today-button {
        background: #e0e1e2 none;
        color: rgba(0, 0, 0, .6);
        border: none;
        border-radius: 3px;
    }

    .react-datepicker__today-button:hover {
        box-shadow: inset 0 0 0 1px transparent, inset 0 0 0 0 rgba(34, 36, 38, .15);
        background-color: #cacbcd;
        background-image: none;
        color: rgba(0, 0, 0, .8);
    }
        
    .react-datepicker__day:hover {
        background-color: var(--main-link-c);
        color: var(--main-background-c)!important;
        opacity: 0.85;
    }

    /* Ctrl+f Menu */

    #hierarchy-editor__ctrl-f {
        background-color: var(--main-background-c);
        border: 1px solid var(--elevated-background-c);
        border-radius: 3px;
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.4) 0px 0px 12px;
    }

    #hierarchy-editor__ctrl-f #hierarchy-editor__ctrl-f__suggestions {
        border-top: 1px solid var(--border-c);
    }

    /* Search */ 

    #SearchPopup .SearchPopupResults #search-results__no-results,
    #SearchPopup .SearchPopupResults #search-results__result, 
    #SearchPopup .SearchPopupResults #SearchResultsParentContext {
        border-left: none;
        border-right: none;
        border-bottom: none;
        border-top: thin solid var(--border-c);
    }
    
    #SearchPopup {
        color: var(--font-c);
    }
        
    #SearchPopup .search-results.search-popup__results {
        box-shadow: none;
    }
    
    #SearchPopup {
        width: 600px;
    }
        
    #hierarchy-editor-toolbar-container #hierarchy-editor__add-to-portal .search-results {
        border-radius: 4px;
    }
        
    /* "::" Bottom Menu */

    .hierarchy-editor-toolbar-container--opened {
        background-color: var(--main-background-c);
        border-top: 0px solid var(--elevated-background-c);
        border-bottom: 1px solid var(--main-background-c);
        padding: 3px;
    }
    
    #hierarchy-editor-toolbar-container #hierarchy-editor__add-to-portal .rich-text-editor {
        background-color: var(--elevated-background-c);
        border: 1px solid var(--border-c);
        border-radius: 5px;
    }
    
    .hierarchy-editor-toolbar-container--opened #hierarchy-editor-toolbar {
        border: none;
    }
    
    .hierarchy-editor-toolbar-container--opened #hierarchy-editor-toolbar .hierarchy-editor-toolbar-item {
        color: var(--font-background-c);
    }

    .red {
        color: var(--font-red-c);
    }

    .green.card-that-will-be-tested {
        color: var(--font-red-c);
    }

    /* Account Popup */

    #bordered-card,
    #Popup #PopupContent,
    .HierarchyEditorBodyview-as-cardTooltip {
        background-color: var(--main-background-c);
        border: 1px solid var(--elevated-background-c);
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.5) 0px 0px 12px;
    }

    #Popup #popup-close-button {
        background-color: var(--main-background-c);
        border: 1px solid var(--elevated-background-c);
        font-size: 14px;
        padding: 1px 0px 3px 5px;
    }
    
    /* Context Popup */

    .react-contexify {
        background-color: var(--main-background-c);
        border: 1px solid var(--elevated-background-c);
        border-radius: 3px;
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.5) 0px 0px 12px;
        color: var(--font-dark-c);
    }

    .react-contexify__item__content {
        display: block;
        color: var(--font-dark-c);
    }

    .react-contexify__item:not(.react-contexify__item--disabled):hover > .react-contexify__item__content {
        color: var(--font-dark-c);
        background-color: var(--hover-background-c);
        font-weight: var(--focus-font-weight);
    }

    /* Sorting Popup */

    .popup #ToolbarPopupHeader {
        font-weight: var(--focus-font-weight);
        padding-bottom: 10px;
        letter-spacing: var(--semiwide-font-spacing);
    }

    .sortSidebarOption {
        border-color: var(--border-c);
        color: var(--font-dark-c);
    }

    .sortSidebarOption:hover {
        background-color: var(--hover-background-c);
    }

    /* Filter popup */

    #HierarchyEditorCtrlF {
        background-color: var(--main-background-c);
        border: 1px solid var(--elevated-background-c);
        border-radius: 3px;
        box-shadow: 
            rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
            rgba(200, 200, 200, 0.2) 0px 0px 6px,
            rgba(200, 200, 200, 0.5) 0px 0px 12px;
        color: var(--font-dark-c);
    }

    #hierarchy_editor__tag-bar {
        margin-top: auto;
        margin-bottom: auto;
    }

    /* Buttons */

    #KnowledgeBaseButtons i.icon {
        color: var(--font-background-c) !important; 
    }

    .ui.button {
        background: var(--hover-background-c);
        color: rgba(0, 0, 0, .6);
    }

    .ui.button:hover {
        box-shadow: 0px 0px 3px 1px rgba(140, 167, 176, .25);
    }

    .ui.button:hover {
        background-color: var(--main-background-c);
        background-image: none;
        color: rgba(0, 0, 0, .8);
    }
    
    
    /* Note Popup */

    .__floater__container[style*="border-color: green;"] {
        border-color: black !important;
    }

    .__floater.__floater__open[style*="filter: drop-shadow(rgb(0\, 125\, 0) 0px 0px 5px);"] {
        filter: drop-shadow(black 0px 0px 5px) !important;
    }

    .__floater__container .green {
        color: var(--main-background-c);
    }

    /* Settings Menu */

    .ui.tabular.menu .active.item {
        background: var(--secondary-background-c);
        color: var(--font-c);
        border-color: var(--secondary-background-c);
    }

    .ui.tabular.menu .item {
        color: var(--font-c);
    }

    .ui.tabular.menu .item:hover {
        color: var(--font-dark-c);
    }

    .ui.segment {
        background: var(--secondary-background-c);
    }

    .ui.tabular.menu {
        border-bottom: 0px solid var(--secondary-background-c);
    }

    #SettingsPage #SettingsPageHeader {
        border-bottom: 1px solid var(--border-c);
    }

    /* About */

    #AboutSectionTitle {
        border: none;
        background-color: var(--main-background-c);
        color: var(--font-c);
    }

    #AboutPage a {
        color: var(--font-dark-c);
        text-decoration: none!important;
    }

    /* Checkbox */

    .ui.checkbox {
        margin-left: auto;
        margin-right: auto;
        display: block;
        width: 17px;
    }

    .ui.checkbox .box:before,
    .ui.checkbox label:before {
        background-color: var(--main-background-c);
        border: 1px solid var(--font-background-c);
        box-shadow: none;
    }

    ui.checkbox input:checked ~ .box:after,
    .ui.checkbox input:checked ~ label:after {
        font-size: 12px;
        padding: 1px 1px;
        background: var(--font-blue-c);
        border-radius: 3px;
        box-shadow: none;
    }

    .remCheckbox {
        opacity: 0.65;
    }

    #hierarchy-editor .remTodoFinished {
        text-decoration: none;
        color: var(--hover-background-c);
    }

    #homepage #content #document-sidebar #DocumentationList .document-list-item__container .documentListHeader .folder:hover,
    #homepage #content #document-sidebar #DocumentationList .document-list-item__container .document-list-item .folder:hover,
    #homepage #content #document-sidebar #documentList .document-list-item__container .documentListHeader .folder:hover,
    #homepage #content #document-sidebar #documentList .document-list-item__container .document-list-item .folder:hover,
    #main #content #document-sidebar #DocumentationList .document-list-item__container .documentListHeader .folder:hover,
    #main #content #document-sidebar #DocumentationList .document-list-item__container .document-list-item .folder:hover,
    #main #content #document-sidebar #documentList .document-list-item__container .documentListHeader .folder:hover,
    #main #content #document-sidebar #documentList .document-list-item__container .document-list-item .folder:hover {
        text-shadow: none !important;
    }

    #hierarchy_editor__tag-bar #hierarchy-editor__tag-bar__tag #hierarchy-editor__tag-bar__tag__delete:hover {
        text-shadow: none !important;
    }

    #hierarchy-editor .rem-container--importable .rem-bulletPlus:hover {
        text-shadow: none !important;
    }

    #hierarchy-editor .rem-container--importable .rem-bulletMinus:hover {
        text-shadow: none !important;
    }

    #hierarchy-editor .rem-container--focused .rem-bulletIcon,
    #hierarchy-editor .rem-container--focused .remListNumber {
        text-shadow: none !important;
    }

    #UpdateIndicator #UpdateIndicatorClose:hover {
        text-shadow: none !important;
    }

#ActionQueueDefaultDocumentContainer #ActionQueueDefaultDocument ul #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons li:hover,
#ActionQueueDefaultDocumentContainer #ActionQueueDefaultDocument ul #main #content #document-sidebar #document-sidebar__buttons-menu__buttons li:hover,
#ArticleViewer #ArticleViewerStartTakingNotes #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #ArticleViewerStartTakingNotesButton:hover,
#ArticleViewer #ArticleViewerStartTakingNotes #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #ArticleViewerStartTakingNotesButton:hover,
#connectionStatus #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #HidePrivateRemButton:hover,
#connectionStatus #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .signUpLink:hover,
#connectionStatus #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #HidePrivateRemButton:hover,
#connectionStatus #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .signUpLink:hover,
#document #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #AddNewDocumentButtonLarge:hover,
#document #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #AddNewDocumentButtonSmall:hover,
#document #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #AddNewDocumentButtonLarge:hover,
#document #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #AddNewDocumentButtonSmall:hover,
#document .documentMenu #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #selectFolder:hover,
#document .documentMenu #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .documentOptions:hover,
#document .documentMenu #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #selectFolder:hover,
#document .documentMenu #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .documentOptions:hover,
#document-hover-preview #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #RemReferencePreview:hover,
#document-hover-preview #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #RemReferencePreview:hover,
#document-parents #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .parent-link:hover,
#document-parents #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .parent-link:hover,
#DocumentTable #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .DocumentLink:hover,
#DocumentTable #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .DocumentLink:hover,
#GlobalNameHierarchyViewer #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons  #collapsedButton:hover,
#GlobalNameHierarchyViewer #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #collapsedButton:hover,
#hierarchy-editor#homepage #content  #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor__add-button:hover,
#HierarchyEditor #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor__embedded-queue-mode-toggle:hover,
#hierarchy-editor#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .rem-container--article-link:hover,
#hierarchy-editor#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .remListNumber:hover,
#hierarchy-editor#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .HierarchyEditorChildrenList:hover,
#hierarchy-editor#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor__add-button:hover,
#hierarchy-editor#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor__embedded-queue-mode-toggle:hover,
#hierarchy-editor#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .rem-container--article-link:hover,
#hierarchy-editor#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .remListNumber:hover,
#hierarchy-editor#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .HierarchyEditorChildrenList:hover,
#hierarchy-editor .remContainer #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .rem-hamburger:hover,
#HierarchyEditor .remContainer #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .toggleCollapseButton:hover,
#hierarchy-editor .remContainer #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .rem-hamburger:hover,
#hierarchy-editor .remContainer #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .toggleCollapseButton:hover,
#HierarchyEditor .remContainer .portal-remHamburger #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons span:hover,
#HierarchyEditor .remContainer .portal-remHamburger #main #content #document-sidebar #document-sidebar__buttons-menu__buttons span:hover,
#HierarchyEditor .remContainer .portal-remHamburgerEmbeddedSearch #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons span:hover,
#HierarchyEditor .remContainer .portal-remHamburgerEmbeddedSearch #main #content #document-sidebar #document-sidebar__buttons-menu__buttons span:hover,
#HierarchyEditor .remPotentialProperties #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .potentialProperty:hover,
#HierarchyEditor .remPotentialProperties #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .potentialProperty:hover,
#HierarchyEditor .notIncludedInDocumentScope #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .notIncludedAncestorClickable:hover,
#HierarchyEditor .notIncludedInDocumentScope #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .notIncludedAncestorClickable:hover,
#HierarchyEditorCtrlF #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .icon:hover,
#HierarchyEditorCtrlF #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .icon:hover,
#hierarchyEditorGlobalInsertContainer #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #HierarchyEditorGlobalInsertToggleVisibility:hover,
#hierarchyEditorGlobalInsertContainer #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #HierarchyEditorGlobalInsertToggleVisibility:hover,
#hierarchy_editor__tag-bar #hierarchy-editor__tag-bar__tag #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor__tag-bar__tag__delete:hover,
#hierarchy_editor__tag-bar #hierarchy-editor__tag-bar__tag #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor__tag-bar__tag__delete:hover,
#homepage #callToActionButtons #content #document-sidebar #document-sidebar__buttons-menu__buttons a:hover,
#homepage #callToActionButtons #main #content #document-sidebar #document-sidebar__buttons-menu__buttons a:hover,
#homepage #content #document-sidebar #DocumentationList #document-sidebar__buttons-menu__buttons .actionRequiredDocumentLink:hover,
#homepage #content #document-sidebar #DocumentationList #document-sidebar__buttons-menu__buttons .documentListHeader:hover,
#homepage #content #document-sidebar #DocumentationList #document-sidebar__buttons-menu__buttons .document-list-item:hover,
#homepage #content #document-sidebar #DocumentationList .document-list-item__container .documentListHeader #document-sidebar__buttons-menu__buttons .folder:hover,
#homepage #content #document-sidebar #DocumentationList .document-list-item__container .document-list-item #document-sidebar__buttons-menu__buttons .folder:hover,
#homepage #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .actionRequiredDocumentLink:hover,
#homepage #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .documentListHeader:hover,
#homepage #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .document-list-item:hover,
#homepage #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .folderFloatButton:hover,
#homepage #content #document-sidebar #documentList .document-list-item__container .documentListHeader #document-sidebar__buttons-menu__buttons .folder:hover,
#homepage #content #document-sidebar #documentList .document-list-item__container .document-list-item #document-sidebar__buttons-menu__buttons .folder:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #ActionQueueDefaultDocumentContainer #ActionQueueDefaultDocument ul li:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #ArticleDocumentButton:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #ArticleViewer #ArticleViewerStartTakingNotes #ArticleViewerStartTakingNotesButton:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #callToActionButtons a:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #connectionStatus #HidePrivateRemButton:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #connectionStatus .signUpLink:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #document #AddNewDocumentButtonLarge:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #document #AddNewDocumentButtonSmall:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #document .documentMenu #selectFolder:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #document .documentMenu .documentOptions:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .actionRequiredDocumentLink:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .documentListHeader:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .document-list-item:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .document-list-item__container .documentListHeader .folder:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .document-list-item__container .document-list-item .folder:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .folderFloatButton:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #document-hover-preview #RemReferencePreview:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .actionRequiredDocumentLink:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .documentListHeader:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .document-list-item:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .document-list-item__container .documentListHeader .folder:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .document-list-item__container .document-list-item .folder:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .folderFloatButton:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #document-parents .parent-link:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #document-sidebar__hiden-link__container:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #document-sidebar__link:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #document-sidebar__link--sign_up:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentTable .DocumentLink:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #EmbeddedSearchRefresh:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #GlobalNameHierarchyViewer #collapsedButton:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #hide-walkthrough-link-button:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor#hierarchy-editor__add-button:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #HierarchyEditor #hierarchy-editor__embedded-queue-mode-toggle:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor .rem-container--article-link:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor .remContainer .rem-hamburger:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #HierarchyEditor .remContainer .portal-remHamburgerEmbeddedSearch span:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #HierarchyEditor .remContainer .portal-remHamburger span:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #HierarchyEditor .remContainer .toggleCollapseButton:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor .remListNumber:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #HierarchyEditor .remPotentialProperties .potentialProperty:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor .HierarchyEditorChildrenList:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #HierarchyEditor .notIncludedInDocumentScope .notIncludedAncestorClickable:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #HierarchyEditorCtrlF .icon:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchyEditorGlobalInsertContainer #HierarchyEditorGlobalInsertToggleVisibility:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy_editor__tag-bar #hierarchy-editor__tag-bar__tag #hierarchy-editor__tag-bar__tag__delete:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #ImportEntireArticle:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #leech-card #leech-card__fixes .LeechAction:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #mobile-queue__shortcuts #mobile-queue__shortcuts__button:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #MobileSearchRemButton:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #multiple-windows .multiple-windows__document #multiple-windows__close-pane:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #OtherRemStack #OtherRemBlock #other-rem-block__title #close-other-rem-block-button:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #OtherRemStack #OtherRemBlock #other-rem-block__title #open-as-doc-button:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #OtherRemStack #other-rem-stack__close:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #PluginNode #PluginHamburgerMenu:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #Popup #popup-close-button:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #PrivateRemBlocker:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #rem-reference__exclude-type-parent:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #RemSelector #RemSelectorOption:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #RabbitQueueTopRightButton:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #SearchPopup #PinnedResults .PinnedResult:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #SearchPopup .SearchPopupResults #SearchResultsResult:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #show-embedded-search-button:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #thinking-trail-history .thinking-trail-history__document-dot:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #UpdateIndicator:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #zoomIntoRemBackDocument:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .queue__response-button:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .Queue #ActionQueueOfflineIndicator:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .Queue #ActionQueueOnlyActionRequiredSwitcher:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .Queue #queue__title #QueueBackButton:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .addListItemButton:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .AnnotationNode:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .thumbnail--big:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .thumbnail--big:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .blackOut:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .button:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .color-button-container:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .DocumentSidebarSmall #viewDocuments:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .rem-container--not-in-article .rem-bullet__container:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .rem-container--not-in-article .rem-bulletIcon:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .hierarchyEditorGlobalInsertContainerOpened #HierarchyEditorToolbar #NoFocusedRemToolbarNotice #NoFocusedRemToolbarNoticeClose:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .hierarchyEditorGlobalInsertContainerOpened #HierarchyEditorToolbar .ToolbarDuplicateKeyButton:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .hierarchyEditorGlobalInsertContainerOpened .HierarchyEditorToolbarButton:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .ImportAllContentsButton:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .LinkNode:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .popup #BulletFormatIcons .icon:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .popup .color-button:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .react-contextmenu--visible .hierarchy-editor__rem-menu:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .rich-text-editor__selected-text-menu .selected-text-menu__button:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .rich-text-editor__selected-text-menu .selected-text-menu__button--color-container:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .SearchResults #search-results__list #SearchResultsResult:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .sortSidebarOption:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .spacedRepetition .spaced-repetition__reveal:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .tumbnail--no-width:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .thumbnail--popup:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .tumbnail--small:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .tumbnail--with-width:hover,
#homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .whiteButton:hover,
#homepage #content .DocumentSidebarSmall #document-sidebar #document-sidebar__buttons-menu__buttons #viewDocuments:hover,
#homepage #main #content #document-sidebar #DocumentationList #document-sidebar__buttons-menu__buttons .actionRequiredDocumentLink:hover,
#homepage #main #content #document-sidebar #DocumentationList #document-sidebar__buttons-menu__buttons .documentListHeader:hover,
#homepage #main #content #document-sidebar #DocumentationList #document-sidebar__buttons-menu__buttons .document-list-item:hover,
#homepage #main #content #document-sidebar #DocumentationList #document-sidebar__buttons-menu__buttons .folderFloatButton:hover,
#homepage #main #content #document-sidebar #DocumentationList .document-list-item__container .documentListHeader #document-sidebar__buttons-menu__buttons .folder:hover,
#homepage #main #content #document-sidebar #DocumentationList .document-list-item__container .document-list-item #document-sidebar__buttons-menu__buttons .folder:hover,
#homepage #main #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .actionRequiredDocumentLink:hover,
#homepage #main #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .documentListHeader:hover,
#homepage #main #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .document-list-item:hover,
#homepage #main #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .folderFloatButton:hover,
#homepage #main #content #document-sidebar  #documentList .document-list-item__container .documentListHeader #document-sidebar__buttons-menu__buttons .folder:hover,
#homepage #main #content #document-sidebar #documentList .document-list-item__container .document-list-item #document-sidebar__buttons-menu__buttons .folder:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .actionRequiredDocumentLink:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .documentListHeader:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .document-list-item:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .document-list-item__container .documentListHeader .folder:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .document-list-item__container .document-list-item .folder:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .folderFloatButton:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .actionRequiredDocumentLink:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .documentListHeader:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .document-list-item:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .document-list-item__container .documentListHeader .folder:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .document-list-item__container .document-list-item .folder:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .folderFloatButton:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #document-sidebar__link:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #document-sidebar__link--sign_up:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #hide-walkthrough-link-button:hover,
#homepage #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .DocumentSidebarSmall #viewDocuments:hover,
#homepage #main #content .DocumentSidebarSmall #document-sidebar #document-sidebar__buttons-menu__buttons #viewDocuments:hover,
#leech-card #leech-card__fixes #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .LeechAction:hover,
#leech-card #leech-card__fixes #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .LeechAction:hover,
#main #content #document-sidebar #DocumentationList #document-sidebar__buttons-menu__buttons .actionRequiredDocumentLink:hover,
#main #content #document-sidebar #DocumentationList #document-sidebar__buttons-menu__buttons .documentListHeader:hover,
#main #content #document-sidebar #DocumentationList #document-sidebar__buttons-menu__buttons .document-list-item:hover,
#main #content #document-sidebar #DocumentationList #document-sidebar__buttons-menu__buttons .folderFloatButton:hover,
#main #content #document-sidebar #DocumentationList .document-list-item__container .documentListHeader #document-sidebar__buttons-menu__buttons .folder:hover,
#main #content #document-sidebar #DocumentationList .document-list-item__container .document-list-item #document-sidebar__buttons-menu__buttons .folder:hover,
#main #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .actionRequiredDocumentLink:hover,
#main #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .documentListHeader:hover,
#main #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .document-list-item:hover,
#main #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .folderFloatButton:hover,
#main #content #document-sidebar #documentList .document-list-item__container .documentListHeader #document-sidebar__buttons-menu__buttons .folder:hover,
#main #content #document-sidebar #documentList .document-list-item__container .document-list-item #document-sidebar__buttons-menu__buttons .folder:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #ActionQueueDefaultDocumentContainer #ActionQueueDefaultDocument ul li:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #ArticleDocumentButton:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #ArticleViewer #ArticleViewerStartTakingNotes #ArticleViewerStartTakingNotesButton:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #connectionStatus #HidePrivateRemButton:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #connectionStatus .signUpLink:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #document #AddNewDocumentButtonLarge:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #document #AddNewDocumentButtonSmall:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #document .documentMenu #selectFolder:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #document .documentMenu .documentOptions:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .actionRequiredDocumentLink:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .documentListHeader:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .document-list-item:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .document-list-item__container .documentListHeader .folder:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .document-list-item__container .document-list-item .folder:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .folderFloatButton:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #document-hover-preview #RemReferencePreview:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .actionRequiredDocumentLink:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .documentListHeader:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .document-list-item:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .document-list-item__container .documentListHeader .folder:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .document-list-item__container .document-list-item .folder:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .folderFloatButton:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #document-parents .parent-link:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #document-sidebar__hiden-link__container:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #document-sidebar__link:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #document-sidebar__link--sign_up:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentTable .DocumentLink:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #EmbeddedSearchRefresh:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #GlobalNameHierarchyViewer #collapsedButton:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #hide-walkthrough-link-button:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor#hierarchy-editor__add-button:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor#hierarchy-editor__embedded-queue-mode-toggle:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor .rem-container--article-link:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor .remContainer .rem-hamburger:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #HierarchyEditor .remContainer .portal-remHamburgerEmbeddedSearch span:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #HierarchyEditor .remContainer .portal-remHamburger span:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor .remContainer .toggleCollapseButton:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor .remListNumber:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #HierarchyEditor .remPotentialProperties .potentialProperty:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy-editor .HierarchyEditorChildrenList:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #HierarchyEditor .notIncludedInDocumentScope .notIncludedAncestorClickable:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #HierarchyEditorCtrlF .icon:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchyEditorGlobalInsertContainer #HierarchyEditorGlobalInsertToggleVisibility:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #hierarchy_editor__tag-bar #hierarchy-editor__tag-bar__tag #hierarchy-editor__tag-bar__tag__delete:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #homepage #callToActionButtons a:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #ImportEntireArticle:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #leech-card #leech-card__fixes .LeechAction:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #mobile-queue__shortcuts #mobile-queue__shortcuts__button:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #MobileSearchRemButton:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #multiple-windows .multiple-windows__document #multiple-windows__close-pane:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #OtherRemStack #OtherRemBlock #other-rem-block__title #close-other-rem-block-button:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #OtherRemStack #OtherRemBlock #other-rem-block__title #open-as-doc-button:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #OtherRemStack #other-rem-stack__close:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #PluginNode #PluginHamburgerMenu:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #Popup #popup-close-button:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #PrivateRemBlocker:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #rem-reference__exclude-type-parent:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #RemSelector #RemSelectorOption:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #RabbitQueueTopRightButton:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #SearchPopup #PinnedResults .PinnedResult:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #SearchPopup .SearchPopupResults #SearchResultsResult:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #show-embedded-search-button:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #thinking-trail-history .thinking-trail-history__document-dot:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #UpdateIndicator:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons #zoomIntoRemBackDocument:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .queue__response-button:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .Queue #ActionQueueOfflineIndicator:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .Queue #ActionQueueOnlyActionRequiredSwitcher:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .Queue #queue__title #QueueBackButton:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .addListItemButton:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .AnnotationNode:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .thumbnail--big:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .thumbnail--big:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .blackOut:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .button:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .color-button-container:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .DocumentSidebarSmall #viewDocuments:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .rem-container--not-in-article .rem-bullet__container:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .rem-container--not-in-article .rem-bulletIcon:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .hierarchyEditorGlobalInsertContainerOpened #HierarchyEditorToolbar #NoFocusedRemToolbarNotice #NoFocusedRemToolbarNoticeClose:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .hierarchyEditorGlobalInsertContainerOpened #HierarchyEditorToolbar .ToolbarDuplicateKeyButton:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .hierarchyEditorGlobalInsertContainerOpened .HierarchyEditorToolbarButton:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .ImportAllContentsButton:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .LinkNode:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .popup #BulletFormatIcons .icon:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .popup .color-button:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .react-contextmenu--visible .hierarchy-editor__rem-menu:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .rich-text-editor__selected-text-menu .selected-text-menu__button:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .rich-text-editor__selected-text-menu .selected-text-menu__button--color-container:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .SearchResults #search-results__list #SearchResultsResult:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .sortSidebarOption:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .spacedRepetition .spaced-repetition__reveal:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .tumbnail--no-width:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .thumbnail--popup:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .tumbnail--small:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .tumbnail--with-width:hover,
#main #content #document-sidebar #document-sidebar__buttons-menu__buttons .whiteButton:hover,
#main #content .DocumentSidebarSmall #document-sidebar #document-sidebar__buttons-menu__buttons #viewDocuments:hover,
#main #homepage #content #document-sidebar #DocumentationList #document-sidebar__buttons-menu__buttons .actionRequiredDocumentLink:hover,
#main #homepage #content #document-sidebar #DocumentationList #document-sidebar__buttons-menu__buttons .documentListHeader:hover,
#main #homepage #content #document-sidebar #DocumentationList #document-sidebar__buttons-menu__buttons .document-list-item:hover,
#main #homepage #content #document-sidebar #DocumentationList #document-sidebar__buttons-menu__buttons .folderFloatButton:hover,
#main #homepage #content #document-sidebar #DocumentationList .document-list-item__container .documentListHeader #document-sidebar__buttons-menu__buttons .folder:hover,
#main #homepage #content #document-sidebar #DocumentationList .document-list-item__container .document-list-item #document-sidebar__buttons-menu__buttons .folder:hover,
#main #homepage #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .actionRequiredDocumentLink:hover,
#main #homepage #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .documentListHeader:hover,
#main #homepage #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .document-list-item:hover,
#main #homepage #content #document-sidebar #documentList #document-sidebar__buttons-menu__buttons .folderFloatButton:hover,
#main #homepage #content #document-sidebar #documentList .document-list-item__container .documentListHeader #document-sidebar__buttons-menu__buttons .folder:hover,
#main #homepage #content #document-sidebar #documentList .document-list-item__container .document-list-item #document-sidebar__buttons-menu__buttons .folder:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .actionRequiredDocumentLink:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .documentListHeader:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .document-list-item:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .document-list-item__container .documentListHeader .folder:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .document-list-item__container .document-list-item .folder:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #DocumentationList .folderFloatButton:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .actionRequiredDocumentLink:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .documentListHeader:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .document-list-item:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .document-list-item__container .documentListHeader .folder:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .document-list-item__container .document-list-item .folder:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #documentList .folderFloatButton:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #document-sidebar__link:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #document-sidebar__link--sign_up:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #hide-walkthrough-link-button:hover,
#main #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .DocumentSidebarSmall #viewDocuments:hover,
#main #homepage #content .DocumentSidebarSmall #document-sidebar #document-sidebar__buttons-menu__buttons #viewDocuments:hover,
#mobile-queue__shortcuts #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #mobile-queue__shortcuts__button:hover,
#mobile-queue__shortcuts #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #mobile-queue__shortcuts__button:hover,
#multiple-windows .multiple-windows__document #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #multiple-windows__close-pane:hover,
#multiple-windows .multiple-windows__document #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #multiple-windows__close-pane:hover,
#OtherRemStack #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #other-rem-stack__close:hover,
#OtherRemStack #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #other-rem-stack__close:hover,
#OtherRemStack #OtherRemBlock #other-rem-block__title #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #close-other-rem-block-button:hover,
#OtherRemStack #OtherRemBlock #other-rem-block__title #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #open-as-doc-button:hover,
#OtherRemStack #OtherRemBlock #other-rem-block__title #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #close-other-rem-block-button:hover,
#OtherRemStack #OtherRemBlock #other-rem-block__title #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #open-as-doc-button:hover,
#PluginNode #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #PluginHamburgerMenu:hover,
#PluginNode #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #PluginHamburgerMenu:hover,
#Popup #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #popup-close-button:hover,
#Popup #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #popup-close-button:hover,
#RemSelector #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #RemSelectorOption:hover,
#RemSelector #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #RemSelectorOption:hover,
#SearchPopup #PinnedResults #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .PinnedResult:hover,
#SearchPopup #PinnedResults #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .PinnedResult:hover,
#SearchPopup .SearchPopupResults #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #SearchResultsResult:hover,
#SearchPopup .SearchPopupResults #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #SearchResultsResult:hover,
#thinking-trail-history #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .thinking-trail-history__document-dot:hover,
#thinking-trail-history #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .thinking-trail-history__document-dot:hover,
.Queue #queue__title #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #QueueBackButton:hover,
.Queue #queue__title #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #QueueBackButton:hover,
.Queue #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #ActionQueueOfflineIndicator:hover,
.Queue #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #ActionQueueOnlyActionRequiredSwitcher:hover,
.Queue #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #ActionQueueOfflineIndicator:hover,
.Queue #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #ActionQueueOnlyActionRequiredSwitcher:hover,
.rem-container--not-in-article #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .rem-bullet__container:hover,
.rem-container--not-in-article #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .rem-bulletIcon:hover,
.rem-container--not-in-article #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .rem-bullet__container:hover,
.rem-container--not-in-article #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .rem-bulletIcon:hover,
.hierarchyEditorGlobalInsertContainerOpened #HierarchyEditorToolbar #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .ToolbarDuplicateKeyButton:hover,
.hierarchyEditorGlobalInsertContainerOpened #HierarchyEditorToolbar #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .ToolbarDuplicateKeyButton:hover,
.hierarchyEditorGlobalInsertContainerOpened #HierarchyEditorToolbar #NoFocusedRemToolbarNotice #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #NoFocusedRemToolbarNoticeClose:hover,
.hierarchyEditorGlobalInsertContainerOpened #HierarchyEditorToolbar #NoFocusedRemToolbarNotice #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #NoFocusedRemToolbarNoticeClose:hover,
.hierarchyEditorGlobalInsertContainerOpened #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .HierarchyEditorToolbarButton:hover,
.hierarchyEditorGlobalInsertContainerOpened #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .HierarchyEditorToolbarButton:hover,
.popup #BulletFormatIcons #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .icon:hover,
.popup #BulletFormatIcons #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .icon:hover,
.popup #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .color-button:hover,
.popup #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .color-button:hover,
.react-contextmenu--visible #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .hierarchy-editor__rem-menu:hover,
.react-contextmenu--visible #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .hierarchy-editor__rem-menu:hover,
.rich-text-editor__selected-text-menu #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .selected-text-menu__button:hover,
.rich-text-editor__selected-text-menu #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .selected-text-menu__button--color-container:hover,
.rich-text-editor__selected-text-menu #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .selected-text-menu__button:hover,
.rich-text-editor__selected-text-menu #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .selected-text-menu__button--color-container:hover,
.SearchResults #search-results__list #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons #SearchResultsResult:hover,
.SearchResults #search-results__list #main #content #document-sidebar #document-sidebar__buttons-menu__buttons #SearchResultsResult:hover,
.spacedRepetition #homepage #content #document-sidebar #document-sidebar__buttons-menu__buttons .spaced-repetition__reveal:hover,
.spacedRepetition #main #content #document-sidebar #document-sidebar__buttons-menu__buttons .spaced-repetition__reveal:hover,
#GlobalNameHierarchyViewer #GlobalNameHierarchyViewerSelf:hover {
    color: var(--elevated-background-c);

}
``` 
            - `
    - tskn's Theme Template 2.0
        - Compiled? Code
        - tskn's Theme
            - Light, modern theme. Design by tskn, code by Eva Thomas. See the Homepage for proper attribution.
                - id: com.github.hannesfrank.remnote-library.tskn-theme
                - version: 1.1.0
                - [Homepage](https://github.com/ethomasv/RemNoteTheme)
                - [Report Problem or Suggest Improvement](https://github.com/ethomasv/RemNoteTheme/issues/new?title=RemNote%20Library%20Report%3A%20tskn%27s%20Theme%20v1.1.0&body=%0A%2A%2APlease%20check%20first%20if%20there%20is%20an%20update%20of%20this%20scroll%20available.%2A%2A%0A%0A---%0A%0A-%20%2A%2AId%3A%2A%2A%20com.github.hannesfrank.remnote-library.tskn-theme%0A-%20%2A%2AVersion%3A%2A%2A%201.1.0%0A-%20%2A%2AType%3A%2A%2A%20Problem/Suggestion%20%28choose%20one%29%0A%0A-%20%5B%20%5D%20Describe%20the%20problem%20you%20are%20having%20with%20the%20scroll%20or%20how%20it%20should%20be%20improved.%0A-%20%5B%20%5D%20_Add_%20a%20short%20description%20to%20the%20title%20%28don%27t%20replace%20it%20completely%21%29%20so%20people%20know%20what%20this%20is%20about.%0A-%20%5B%20%5D%20Make%20sure%20to%20include%20a%20screenshot%20or%20image%20to%20make%20your%20issue%20easy%20to%20understand.%0A%0A---%0A)
            - Theme
                - ```css
/*
@version        1.1.0
@description    RemNote Theme Designed by tskn > https://dribbble.com/shots/14178356-RemNote-Concept
@author         Code by Eva Thomas 
@homepageURL    https://githubf.com/ethomasv/RemNoteTheme
*/

/* === Changes from the original theme. === */

/* Code nodes should always be monospace. The theme otherwise sets the font of every div */
#code-node {
    font-family:Arial Unicode MS, Arial, sans-serif;
}

/* === Original theme below (see also factored out modules) === */
div {
    line-height: var(--spacing-line-height, 1.7em);
}

.tree-node-container {
    margin-top: var(--spacing-tree-node-container-margin-top, 0.5em);
}

/* Paragraph Bullet */
.rem-bullet__container .rem-bullet.rem-bullet--all-children-visible {
    margin-top: var(--spacing-bullet-paragraph-margin-top, 15px);
}

.rem-bullet__container .rem-bullet.rem-bullet--hidden-children {
    margin-top: var(--spacing-bullet-paragraph-margin-top, 15px);
}

/* Document Bullet */
.file.small.icon.rem-bullet__icon.rem-bullet--hidden-children,
.file.small.icon.rem-bullet__icon.rem-bullet--all-children-visible {
    margin-top: var(--spacing-bullet-document-margin-top, 1px);
}

.file.small.icon.rem-bullet__icon.rem-bullet--hidden-children {
    margin-top: var(--spacing-bullet-document-margin-top, 3px);
}

/* Folder Bullet */
.folder.small.icon.rem-bullet__icon.rem-bullet--hidden-children,
.folder.small.icon.rem-bullet__icon.rem-bullet--all-children-visible {
    margin-top: var(--spacing-bullet-document-margin-top, 3px);
}

.folder.small.icon.rem-bullet__icon.rem-bullet--hidden-children {
    margin-top: var(--spacing-bullet-document-margin-top, 3px);
}

/* Concept Rem type Bullet */
.rem-container--concept-rem-type
    .rem-bullet__container
    .rem-bullet.rem-bullet--all-children-visible {
    margin-top: var(--spacing-bullet-conceptDescriptor-margin-top, 7px);
}

.rem-container--concept-rem-type
    .rem-bullet__container
    .rem-bullet.rem-bullet--hidden-children {
    margin-top: var(--spacing-bullet-conceptDescriptor-margin-top, 7px);
}

/* Descriptor Rem type Bullet */
.rem-container--descriptor-rem-type
    .rem-bullet__container
    .rem-bullet.rem-bullet--all-children-visible {
    margin-top: var(--spacing-bullet-conceptDescriptor-margin-top, 7px);
}

.rem-container--descriptor-rem-type
    .rem-bullet__container
    .rem-bullet.rem-bullet--hidden-children {
    margin-top: var(--spacing-bullet-conceptDescriptor-margin-top, 7px);
}

/* Header */
.rem-bullet__container .rem-bullet.rem-header__bullet--1 {
    margin-top: var(--header-1-margin-top, 1px);
}

.rem-bullet__container .rem-bullet.rem-header__bullet--2 {
    margin-top: var(--header-2-margin-top, 8px);
}

.rem-bullet__container .rem-bullet.rem-header__bullet--3 {
    margin-top: var(--header-3-margin-top, 6px);
}

.rem-text.rem-header--1 {
    font-size: var(--header-1-font-size, 18px);
    font-weight: var(--header-1-font-weight, 400);
}

.rem-text.rem-header--2 {
    font-size: var(--header-2-font-size, 16px);
    font-weight: var(--header-2-font-weight, 380);
}

.rem-text.rem-header--3 {
    font-size: var(--header-3-font-size, 15px);
    font-weight: var(--header-3-font-weight, 350);
}

/* Documents List */
.ReactVirtualized__Table__headerRow {
    text-align: center;
    font-weight: 400;
    letter-spacing: 0.01em;
    font-size: 13px;
    padding-bottom: 5px;
    margin-top: 25px;
}

.ReactVirtualized__Table__row[style*="background-color: rgba(1\, 1\, 1\, 0.1);"],
.ReactVirtualized__Table__row {
    color: var(--font-c) !important;
    background-color: transparent !important;
    border-top: 1px solid var(--border-c);
}

.ReactVirtualized__Grid__innerScrollContainer > * {
    margin-top: 0px;
    margin-left: 20px;
}

#DocumentTable .DocumentLink:hover {
    background-color: transparent;
    color: var(--font-c) !important;
}

#DocumentTable .DocumentLink {
    color: var(--font-background-c) !important;
}

#DocumentTable a:hover,
#DocumentTable .blackLinks a:hover {
    letter-spacing: -0.01em;
}

.ReactVirtualized__Table__rowColumn[style*="flex: 0 1 690px;"]:hover {
    background-color: #5da1b44d !important;
}

#DocumentTable .Cell {
    margin-left: auto;
    margin-right: auto;
}

/* Sidebar */
#document-sidebar__link__queue-indicator {
    background-color: var(--hover-blue-c);
    padding: 5px;
}

#homepage #content #document-sidebar,
#main #content #document-sidebar {
    background-color: var(--main-blue-c);
    color: white;
    border-right: 20px solid var(--main-blue-c);
    border-bottom: 2px solid var(--main-blue-c);
    padding: 10px 3px 10px 10px;
}

#document-sidebar #documentList #documentListScrollPortal .document-list-items {
    max-width: 240px;
}

#document-sidebar__link.document-sidebar__linkQueue {
    color: #fffc !important;
    font-weight: 400 !important;
    letter-spacing: 0.05em;
    font-size: 1.1em;
}

#document-sidebar__document-buttons__document-link-container,
#document-sidebar__document-buttons__document-link-container
    .document-sidebar__link__icon-container {
    color: white;
    font-weight: 400 !important;
    letter-spacing: 0.05em;
    font-size: 1.1em;
}

#document-sidebar__document-buttons
    #document-sidebar__document-buttons__document-link-container:hover {
    background-color: var(--hover-blue-c);
}

#homepage #content #document-sidebar a:hover,
#homepage #content #document-sidebar a:visited,
#main #content #document-sidebar a:hover,
#main #content #document-sidebar a:visited {
    color: white !important;
    opacity: 1;
}

#DocumentationList .document-list-item--opened,
#documentList .document-list-item--opened {
    background-color: var(--hover-blue-c) !important;
    font-weight: 400;
}

#DocumentationList .document-list-item,
#documentList .document-list-item {
    padding: 7px 0px;
}

.document-sidebar__linkOpen,
#document-sidebar__link:hover,
#DocumentationList .document-list-item:hover,
#documentList .document-list-item:hover {
    background-color: var(--hover-blue-c) !important;
}

#document-sidebar #logo {
    display: none;
}

#document-sidebar #document-sidebar__account-capsule {
    background-color: transparent;
    color: white;
}

#document-sidebar #document-sidebar__collapse-icon,
#document-sidebar .document-sidebar__document-buttons__button img,
#document-sidebar .document-sidebar__bottom-buttons__button img,
#document-sidebar
    .document-list-item__folder-icon.document-list-item__folder-icon--closed
    img,
#document-sidebar
    #DocumentationList
    .folder-float-buttons
    .folder-float-button
    img,
#document-sidebar
    #DocumentationList
    .document-list-item
    .document-list-item__folder-icon--opened
    img,
#document-sidebar
    #documentList
    .document-list-item
    .document-list-item__folder-icon--opened
    img {
    filter: grayscale(100%) invert(100%) contrast(300%);
    opacity: 1;
}

#document-sidebar
    #document-sidebar__link
    .document-sidebar__link__icon-container
    img,
#document-sidebar #documentList .folder-float-buttons .folder-float-button img {
    filter: invert(65%) brightness(200%);
}

#document-sidebar
    #document-sidebar__document-buttons__document-link-container
    i.file.icon,
#document-sidebar i.arrow.alternate.circle.up.icon,
.thinking-trail-history__document-dot__preview i.file.text.small.icon,
#document-sidebar i.caret.right.icon {
    color: white;
}

#document-sidebar #DocumentationList .documentListCheckbox,
#document-sidebar #documentList .documentListCheckbox {
    color: white;
}

#document-sidebar #DocumentationList .document-list-header,
#document-sidebar #documentList .document-list-header {
    color: white;
    text-transform: uppercase;
    font-weight: 400 !important;
}

#document-sidebar #DocumentationList .document-list-header b,
#document-sidebar #documentList .document-list-header b {
    font-weight: 400 !important;
    letter-spacing: 0.05em;
}

#document-sidebar #DocumentationList .document-list-header i.dropdown.icon,
#document-sidebar #documentList .document-list-header i.dropdown.icon,
.folderDocumentList i.dropdown.icon {
    color: white;
}

#document-sidebar #DocumentationList .folder-float-buttons,
#document-sidebar #documentList .folder-float-buttons {
    background-color: inherit;
    margin-top: 4px;
    margin-right: 5px;
}

#document-sidebar
    #DocumentationList
    .folder-float-buttons
    .folder-float-button
    i,
#document-sidebar #documentList .folder-float-buttons .folder-float-button i {
    color: white;
}

#document-sidebar i.icons .corner.icon {
    text-shadow: -1px -1px 0 var(--main-blue-c), 1px -1px 0 var(--main-blue-c),
        -1px 1px 0 var(--main-blue-c), 1px 1px 0 var(--main-blue-c);
}

#status-indicator__title,
#status-indicator,
#status-indicator__title i {
    color: white;
}

#document-sidebar--collapsed {
    background-color: var(--main-blue-c);
    z-index: 3;
    border: 1px solid var(--main-blue-c);
}

#document-sidebar--collapsed i.ellipsis.horizontal.large.icon {
    color: transparent;
}

#status-indicator__title,
#status-indicator,
#status-indicator__title i {
    background-color: transparent !important;
}

#document-sidebar.document-sidebar--floating {
    z-index: 5 !important;
}

#multiple-windows__document #multiple-windows__close-pane {
    opacity: 0.5;
    margin-top: -10px;
    margin-right: -2px;
}

#DocumentationList .documentListNoDocuments,
#documentList .documentListNoDocuments {
    color: white;
    opacity: 0.9;
}

/* Thinking trail */
#thinking-trail-history {
    margin-left: -20px;
    z-index: 4;
    background-color: var(--main-blue-c);
    width: 40px;
}

.small-window-page #thinking-trail-history {
    margin-left: 0px;
}

#thinking-trail-history__container {
    padding-bottom: 0px;
    padding-top: 25px !important;
    height: 100%;
    padding-left: 8.5px;
}

.multiple-windows--one-pane #thinking-trail-history {
    width: 20px;
}

.multiple-windows--two-panes #thinking-trail-history {
    width: 40px;
}

#thinking-trail-history
    #thinking-trail-history__document-list
    .thinking-trail-history__document-dot__preview:hover {
    background-color: var(--hover-blue-c);
    border: thin solid var(--soft-blue-c);
    border-radius: 4px;
    padding: 0px 6px !important;
}

#thinking-trail-history:hover #thinking-trail-history__container {
    background-color: var(--hover-blue-c);
    box-shadow: none;
    margin: 0px;
    border-right: 7px solid var(--hover-blue-c);
    height: 100vh;
    max-width: 500px;
}

#thinking-trail-history
    .thinking-trail-history__document
    .thinking-trail-history__document-dot {
    background-color: var(--soft-blue-c);
    border: 1px solid var(--soft-blue-c);
    border-radius: 5px;
    width: 5px;
    height: 5px;
    margin-left: -1px;
}

#thinking-trail-history
    .thinking-trail-history__document
    .thinking-trail-history__document-dot:hover,
#thinking-trail-history .thinking-trail-history__document-dot--active {
    background-color: white !important;
    border: 1px solid white !important;
    border-radius: 5px !important;
    width: 7px !important;
    height: 7px !important;
    box-shadow: none !important;
    margin-left: -2px !important;
}

#thinking-trail-history
    .thinking-trail-history__document
    .thinking-trail-history__children-bar {
    color: var(--soft-blue-c);
}

#thinking-trail-history .thinking-trail-history__document-height-offset {
    padding-top: 0.9px;
}

#thinking-trail-history
    .thinking-trail-history__document
    .thinking-trail-history__document-height-offset {
    background-color: var(--soft-blue-c);
}

#thinking-trail-history
    .thinking-trail-history__document
    .thinking-trail-history__document-dot__preview {
    padding: 2px 7px 0px 5px;
}

#thinking-trail-history__document-list
    .thinking-trail-history__document-dot__preview:hover {
    color: white;
    padding: 1px 7px !important;
}

#thinking-trail-history
    #thinking-trail-history__document-list
    .thinking-trail-history__document-dot__preview {
    padding: 1px 7px;
    color: white;
    overflow: hidden;
    max-width: 370px;
    font-size: 12px;
}

#thinking-trail-history
    #thinking-trail-history__document-list
    .thinking-trail-history__document-dot__preview:hover {
    color: white;
}

#thinking-trail-history__container .grey.close.icon {
    color: white !important;
    padding-left: 7px;
}

/* Document Top Bar */
.remHierarchyTop {
    width: 150vw !important;
    max-width: 150vw !important;
    min-width: 150vw !important;
    border-top: 1px solid var(--border-c);
    margin-left: -20vw;
    margin-top: 10px;
    height: 0px;
    visibility: visible !important;
    padding: 0px !important;
}

#homepage #content .DocumentationPageWrapper,
#homepage #content .page,
#main #content .DocumentationPageWrapper,
#main #content .page {
    padding: 0px;
}

.document-source--hide-on-unfocus {
    opacity: 1 !important;
    visibility: visible;
}

#document-parents {
    padding-bottom: 15px;
    padding-top: 10px;
}

.document-source {
    padding-left: 0;
    padding-right: 0;
    padding-top: 20px;
    padding-bottom: 7px;
    visibility: visible;
}

#document #actionRequiredDocumentTitle,
#document .document-title {
    font-size: 30px;
    font-weight: 500;
}

#document-parents .parent-link,
#document-parents .join-arrow {
    opacity: 0.4;
}

#DocumentTitle .rem-header--1,
#DocumentTitle .rem-header--2,
#DocumentTitle .rem-header--3 {
    background-color: transparent;
    font-size: 30px;
    font-weight: 600;
}

/* Headers */
.rem-text.rem-header--1,
.rem-text.rem-header--2,
.rem-text.rem-header--3 {
    border-radius: 7px;
    margin-left: -12px;
    padding-left: 29px !important;
}

.rem-text.rem-header--1,
.rem-text.rem-header--2,
.rem-text.rem-header--3 {
    background-color: rgb(244, 243, 239);
}

/* Highlighters */
.highlight-color--orange {
    background-color: var(--highlight-orange-c, #ffc7c7) !important;
    padding: 0px 7px;
    border-radius: 4px;
}

.highlight-color--red {
    background-color: var(--highlight-red-c, #ffd599) !important;
    padding: 0px 7px;
    border-radius: 4px;
}

.highlight-color--blue {
    background-color: var(--highlight-blue-c, #fef49d) !important;
    padding: 0px 7px;
    border-radius: 4px;
}

.highlight-color--yellow {
    background-color: var(--highlight-yellow-c, #d7e985) !important;
    padding: 0px 7px;
    border-radius: 4px;
}

.highlight-color--green {
    background-color: var(--highlight-green-c, #e4b1eb) !important;
    padding: 0px 7px;
    border-radius: 4px;
}

.highlight-color--purple {
    background-color: var(--highlight-purple-c, #afd9fb) !important;
    padding: 0px 7px;
    border-radius: 4px;
}

/* Tags */
.hierarchy-editor__tag-bar__tag.button i.arrow.alternate.circle.up.icon {
    padding-left: 4px;
    color: #999;
}

.hierarchy-editor__tag-bar__tag.button {
    padding: 3px 7px 4px 7px;
    font-size: 11px;
    opacity: 1;
    color: #999;
}

.hierarchy-editor__tag-bar__tag.button > span:before {
    content: " ";
}

.hierarchy-editor__tag-bar__tag.button > span {
    color: #555;
}

.hierarchy-editor__tag-bar__tag {
    background-color: #f4f3ef80;
}

.work-in-progress-tag {
    border-radius: 4px;
    color: var(--font-background-c);
    padding: 1px 5px;
    background-color: #f4f4f4;
}

/* Main */
body {
    font-size: 13px;
    color: #222;
}

div {
    font-family: 'Arial Unicode MS',Arial,san-serif;
    font-size: 1em;
    margin: 0px;
    padding: 0px;
}

#code-node,
#quote,
.quote {
    background-color: var(--quote-background-c, #ecf3f6);
    border: none;
    border-radius: 3px;
    color: var(--font-c);
    padding-left: 7px;
    padding-right: 7px;
}

i.quote.right.icon {
    height: 16px;
    padding: 3px 7px;
}

:focus {
    outline: none;
}

.rem-text {
    padding-left: 20px !important;
}

#draggingIndicator,
#draggingIndicatorAddAsChild {
    height: 2px;
    border: 1px solid var(--soft-blue-c);
    background-color: var(--soft-blue-c);
    border-radius: 7px !important;
    top: -1px;
}

/* Bullets */
/* Main open and closed bullet for headers */
.rem-bullet__container
    .rem-bullet.rem-bullet--all-children-visible.rem-header__bullet--1 {
    border: 0.5px solid var(--bullet-main);
    background-color: transparent;
    height: 7px !important;
    width: 7px !important;
}

.rem-bullet__container
    .rem-bullet.rem-bullet--hidden-children.rem-header__bullet--1 {
    border: 1px solid var(--bullet-main) !important;
    background-color: var(--bullet-main);
    height: 7px !important;
    width: 7px !important;
}

.rem-bullet__container
    .rem-bullet.rem-bullet--all-children-visible.rem-header__bullet--2 {
    border: 2px solid var(--bullet-main);
    background-color: transparent;
    height: 7px !important;
    width: 7px !important;
}

.rem-bullet__container
    .rem-bullet.rem-bullet--hidden-children.rem-header__bullet--2 {
    border: 2px solid var(--bullet-main) !important;
    background-color: var(--bullet-main);
    height: 7px !important;
    width: 7px !important;
}

.rem-bullet__container
    .rem-bullet.rem-bullet--all-children-visible.rem-header__bullet--3 {
    border: 2px solid var(--bullet-main);
    background-color: transparent;
    height: 7px !important;
    width: 7px !important;
}

.rem-bullet__container
    .rem-bullet.rem-bullet--hidden-children.rem-header__bullet--3 {
    border: 2px solid var(--bullet-main) !important;
    background-color: var(--bullet-main);
    height: 7px !important;
    width: 7px !important;
}

/* Paragraph Bullet */
.rem-bullet__container .rem-bullet.rem-bullet--all-children-visible {
    border: 5px solid var(--bullet-main) !important;
    background-color: transparent;
    height: 7px !important;
    width: 7px !important;
}

.rem-bullet__container .rem-bullet.rem-bullet--hidden-children {
    border: 2px solid var(--bullet-main) !important;
    background-color: var(--bullet-main);
    height: 7px !important;
    width: 7px !important;
}

/* Document Bullet */
.file.small.icon.rem-bullet__icon.rem-bullet--hidden-children,
.file.small.icon.rem-bullet__icon.rem-bullet--all-children-visible {
    border: 2px solid var(--bullet-doc) !important;
    background-color: transparent;
    height: 7px !important;
    width: 7px !important;
    border-radius: 3px;
}

.file.small.icon.rem-bullet__icon.rem-bullet--hidden-children {
    border: 2px solid var(--bullet-doc) !important;
    background-color: var(--bullet-doc);
    height: 7px !important;
    width: 7px !important;
    border-radius: 3px;
}

.file.small.icon.rem-bullet__icon.rem-bullet--hidden-children::before,
.file.small.icon.rem-bullet__icon.rem-bullet--all-children-visible::before {
    display: none;
}

/* Folder Bullet */
.folder.small.icon.rem-bullet__icon.rem-bullet--hidden-children,
.folder.small.icon.rem-bullet__icon.rem-bullet--all-children-visible {
    border: 2px solid var(--bullet-folder) !important;
    background-color: transparent;
    height: 7px !important;
    width: 7px !important;
    border-radius: 3px;
}

.folder.small.icon.rem-bullet__icon.rem-bullet--hidden-children {
    border: 2px solid var(--bullet-folder) !important;
    background-color: var(--bullet-folder);
    height: 7px !important;
    width: 7px !important;
    border-radius: 3px;
}

.folder.small.icon.rem-bullet__icon.rem-bullet--hidden-children::before,
.folder.small.icon.rem-bullet__icon.rem-bullet--all-children-visible::before {
    display: none;
}

/* Concept Rem type Bullet */
.rem-container--concept-rem-type
    .rem-bullet__container
    .rem-bullet.rem-bullet--all-children-visible {
    border: 2px solid var(--bullet-concept) !important;
    background-color: transparent;
    height: 7px !important;
    width: 7px !important;
}

.rem-container--concept-rem-type
    .rem-bullet__container
    .rem-bullet.rem-bullet--hidden-children {
    border: 2px solid var(--bullet-concept) !important;
    background-color: var(--bullet-concept);
    height: 7px !important;
    width: 7px !important;
}

/* Descriptor Rem type Bullet */
.rem-container--descriptor-rem-type
    .rem-bullet__container
    .rem-bullet.rem-bullet--all-children-visible {
    border: 2px solid var(--bullet-descriptor) !important;
    background-color: transparent;
    height: 7px !important;
    width: 7px !important;
}

.rem-container--descriptor-rem-type
    .rem-bullet__container
    .rem-bullet.rem-bullet--hidden-children {
    border: 2px solid var(--bullet-descriptor) !important;
    background-color: var(--bullet-descriptor);
    height: 7px !important;
    width: 7px !important;
}

/* Bottom bar */
.multiple-windows--one-pane #hierarchy-editor-toolbar-container {
    width: 100vw !important;
    left: 12px;
    height: 40px;
    border-top: 1px solid var(--border-c);
}

.paddingPage
    .multiple-windows--one-pane
    .hierarchy-editor-toolbar-container--opened
    #hierarchy-editor-toolbar {
    max-width: 55vw !important;
    margin-left: auto;
    margin-right: auto;
    border: none;
    filter: grayscale(100%);
    opacity: 0.6;
}

.paddingPage
    .multiple-windows--one-pane
    #hierarchy-editor-toolbar-container
    #hierarchy-editor__add-to-portal
    #hierarchy-editor__add-to-portal__inner {
    bottom: 0px;
    right: 19vw;
    width: 250px;
}

.page--no-padding
    .multiple-windows--one-pane
    .hierarchy-editor-toolbar-container--opened
    #hierarchy-editor-toolbar {
    max-width: 40vw !important;
    margin-left: auto;
    margin-right: auto;
    border: none;
    filter: grayscale(100%);
    opacity: 0.6;
}

.page--no-padding
    .multiple-windows--one-pane
    #hierarchy-editor-toolbar-container
    #hierarchy-editor__add-to-portal
    #hierarchy-editor__add-to-portal__inner {
    bottom: 0px;
    right: 12vw;
    width: 250px;
}

.small-window-page
    .multiple-windows--one-pane
    .hierarchy-editor-toolbar-container--opened
    #hierarchy-editor-toolbar {
    margin-left: 5vw;
}

.small-window-page
    .multiple-windows--one-pane
    #hierarchy-editor-toolbar-container
    #hierarchy-editor__add-to-portal
    #hierarchy-editor__add-to-portal__inner {
    bottom: 0px;
    right: 1vw;
    width: 200px;
}

.multiple-windows--one-pane
    #hierarchy-editor-toolbar-container
    #hierarchy-editor__add-to-portal
    .rich-text-editor {
    border: none;
    background-color: var(--soft-background-c);
    font-size: 11px;
}

.multiple-windows--two-panes #hierarchy-editor-toolbar-container {
    height: 40px;
    border-top: 1px solid var(--border-c);
}

.paddingPage
    .multiple-windows--two-panes
    .hierarchy-editor-toolbar-container--opened
    #hierarchy-editor-toolbar {
    max-width: 45vw !important;
    margin-left: auto;
    margin-right: auto;
    border: none;
    filter: grayscale(100%);
    opacity: 0.6;
}

.paddingPage
    .multiple-windows--two-panes
    #hierarchy-editor-toolbar-container
    #hierarchy-editor__add-to-portal
    #hierarchy-editor__add-to-portal__inner {
    bottom: 0px;
    width: 250px;
}

.page--no-padding
    .multiple-windows--two-panes
    .hierarchy-editor-toolbar-container--opened
    #hierarchy-editor-toolbar {
    max-width: 40vw !important;
    margin-left: auto;
    margin-right: auto;
    border: none;
    filter: grayscale(100%);
    opacity: 0.6;
}

.page--no-padding
    .multiple-windows--two-panes
    #hierarchy-editor-toolbar-container
    #hierarchy-editor__add-to-portal
    #hierarchy-editor__add-to-portal__inner {
    bottom: 0px;
    width: 250px;
}

.multiple-windows--two-panes
    #hierarchy-editor-toolbar-container
    #hierarchy-editor__add-to-portal
    .rich-text-editor {
    border: none;
    background-color: var(--soft-background-c);
    font-size: 11px;
}

.search-results #search-results__list,
#hierarchy-editor-toolbar-container
    #hierarchy-editor__add-to-portal
    .search-results {
    z-index: 3;
    background-color: white;
    border: 1px solid var(--border-c) !important;
    border-radius: 5px;
    box-shadow: rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
        rgba(200, 200, 200, 0.2) 0px 0px 6px, rgba(200, 200, 200, 0.5) 0px 0px 12px !important;
}

#hierarchy-editor-toolbar-container
    #hierarchy-editor__add-to-portal
    #hierarchy-editor__add-to-portal__inner {
    /* Fix click issue on Add to Portel search box. Some other element above probably stole the click events. */
    z-index: 5;
}

/* Help Button */
#help-button,
#help-button:hover {
    bottom: 60px;
    background-color: var(--main-blue-c);
    color: white;
    opacity: 0.85;
}

/* Rem References Links */
.rem-reference-link {
    color: var(--reference-c, #b979cf);
    padding: 0px 2px;
    border: none !important;
}

.rem-reference-link:hover {
    background-color: transparent !important;
    border: none !important;
}

.rem-reference--highlighted {
    box-shadow: none;
}

.rem-indented-indicator {
    color: var(--reference-c, #b979cf);
    vertical-align: text-bottom;
}

/* 2 docs view */
#multiple-windows .multiple-windows__document {
    border-color: var(--border-c);
}

/* Portals */
.rem.portal-rem--blue.portalRem {
    background-color: transparent !important;
    border: none !important;
    box-shadow: none !important;
}

#hierarchy-editor .portal-rem .portal-rem-top {
    border-top: 2px solid transparent;
    background-color: transparent;
}

#hierarchy-editor .portal-rem .portal-rem-top:hover {
    cursor: pointer;
}

#hierarchy-editor .portal-rem--selected .portal-rem-top {
    border: 1px solid var(--soft-blue-c) !important;
    background-color: var(--soft-blue-c);
    height: 0px;
    border-radius: 10px;
    margin-right: 15px;
}

#hierarchy-editor .portal-rem--selected {
    border: none !important;
}

#show-embedded-search-button {
    padding: 4px;
    margin-right: 0;
    margin-top: 4px;
    margin-left: -6px;
    border: none;
}

.embeddedSearch i.search.icon {
    margin-top: -4px;
    margin-right: 10px;
}

#show-embedded-search-button i.caret.down.icon {
    opacity: 0.5;
}

#hierarchy-editor .portal-rem--blue {
    border-color: transparent;
}

#hierarchy-editor .portal-rem-top--embedded-search-top {
    border-top-style: none !important;
}

i.refresh.icon {
    opacity: 0.5;
    margin-top: -5px;
    padding-top: 0px !important;
}

#show-embedded-search-button
    #show-embedded-search-button__delete-button
    i.icon {
    color: #aaa;
}

i.refresh.icon:hover {
    opacity: 0.85;
}

#show-embedded-search-button {
    font-size: 12px;
    text-transform: uppercase;
    letter-spacing: 0.1em;
}

#show-embedded-search-button > b {
    display: none;
}

.embeddedSearch {
    border-radius: 0.4em;
    border: 1px solid var(--soft-background-c);
    background-color: var(--soft-background-c);
    text-decoration: none;
    padding: 5px 5px 5px 10px;
    margin-left: 11px;
    margin-bottom: 8px;
    margin-top: -10px;
}

#hierarchy-editor .portal-rem--embedded-search {
    background-color: transparent !important;
    border: none !important;
    box-shadow: none !important;
}

#hierarchy-editor .search-portal-tree-node {
    margin-left: 4px;
    background-color: transparent;
    margin-right: 25px;
    border: 1px solid var(--border-c) !important;
    box-shadow: none;
    border-radius: 12px;
}

#hierarchy-editor
    .rem-container__top-level-spacer
    .rem-container__top-level-spacer__inner {
    display: none;
}

#hierarchy-editor .rem-container__top-level-spacer {
    display: none;
}

#Hierarchy-editor .HierarchyEditorAfterPortal {
    border: 1px solid var(--border-c) !important;
    box-shadow: none;
    border-radius: 5px;
    background-color: white;
}

#hierarchy-editor .rem-container--not-included-in-document-scope,
#hierarchy-editor .notIncludedInDocumentScope .notIncludedAncestorClickable {
    text-decoration: none;
    color: #bbb;
}

#hierarchy-editor .rem-container--not-included-in-document-scope .join-arrow {
    font-size: 17px;
    color: grey;
}

#hierarchy-editor .isSearchResult {
    background-color: var(--soft-background-c);
    border: 1px solid var(--soft-background-c);
    padding: 5px 5px 5px 14px;
    border-radius: 5px;
    margin: 5px;
}

.isSearchResult .rem-bullet__container {
    margin-left: 10px;
    padding-top: 0.35em;
}

.isSearchResult .rem-bullet__container i {
    margin-left: 3px;
    padding-top: 0.6em;
}

.isSearchResult .rem-header--3,
.isSearchResult .rem-header--2,
.isSearchResult .rem-header--1 {
    background-color: transparent;
}

.search-portal-tree-node > .tree-node-container {
    margin-left: 10px;
}

.searchKeywordHighlight {
    background-color: transparent;
}

#hierarchy-editor .portal-tree-node {
    /* portal (not search) */
    background-color: transparent;
    border: 1px solid var(--border-c) !important;
    box-shadow: none;
    border-radius: 12px;
    padding-bottom: 10px;
    margin-left: 3px;
    padding-left: 20px !important;
    margin-right: 20px;
}

.import-all-contents-button__container {
    margin-top: 8px;
}

.ImportAllContentsButton {
    opacity: 0.5;
}

.ImportAllContentsButton:hover {
    color: grey;
    opacity: 0.8;
    font-weight: var(--focus-font-weight);
}

#hierarchy-editor .remChildren .ImportAllContentsButton {
    float: none;
    text-align: right;
}

#hierarchy-editor .hierarchy-editor__after-portal,
#hierarchy-editor .indented-hierarchy-editor-rem--after-portal-embedded-search {
    border: none;
}

/* Rems Blocks */
#hierarchy-editor .TreeNode {
    border-left: 1px solid var(--border-c);
}

#hierarchy-editor .TreeNodeListItems {
    border-left: 3px solid var(--border-c) !important;
}

#hierarchy-editor .rem-container--focused {
    background-color: transparent;
}

#hierarchy-editor .is-toolbar-previous-focus-rem {
    border: thin solid rgba(93, 161, 180, 0.4);
    box-shadow: none;
}

.selected-rem {
    background-color: rgba(93, 161, 180, 0.2);
    box-shadow: none;
}

/* Document Preview Popup */
#document-hover-preview {
    box-shadow: 0 0 0 1px rgba(15, 15, 15, 0.05), 0 3px 6px rgba(15, 15, 15, 0.1),
        0 9px 24px rgba(15, 15, 15, 0.2);
    border: none;
    border-radius: 3px;
    margin: 10px;
    padding: 15px 20px !important;
}

#document-hover-preview #document-hover-preview__popup {
    padding-left: 5px;
}

/* Selected text Popup menu */
.rich-text-editor__selected-text-menu {
    background-color: white;
    border: 1px solid var(--border-c);
    border-radius: 3px;
    box-shadow: rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
        rgba(200, 200, 200, 0.2) 0px 0px 6px, rgba(200, 200, 200, 0.5) 0px 0px 12px;
}

.rich-text-editor__selected-text-menu
    .rich-text-editor__selected-text-menu__divider {
    border: thin solid var(--border-c);
}

.rich-text-editor__selected-text-menu
    .rich-text-editor__selected-text-menu__search {
    padding-top: 7px;
    padding-bottom: 7px;
    border-top: thin solid var(--border-c);
    padding-left: 0px;
    padding-right: 0px;
}

.rich-text-editor__selected-text-menu .search-results {
    box-shadow: none;
    width: 400px;
    padding: 0px 7px;
}

.rich-text-editor__selected-text-menu .selected-text-menu__button:hover {
    background-color: white;
}

.rich-text-editor__selected-text-menu .selected-text-menu__button {
    opacity: 0.65;
}

.rich-text-editor__selected-text-menu .selected-text-menu__button--color {
    border: 1px solid var(--border-c);
}

/* Right Click popup */
.right-click-menu {
    background-color: white;
    color: black;
    border: 1px solid var(--border-c) !important;
    border-radius: 3px;
    box-shadow: rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
        rgba(200, 200, 200, 0.2) 0px 0px 6px, rgba(200, 200, 200, 0.5) 0px 0px 12px !important;
}

/* Bottom Bar Popups */
.ui.popup {
    background-color: white;
    border: 1px solid var(--border-c) !important;
    border-radius: 3px;
    box-shadow: rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
        rgba(200, 200, 200, 0.2) 0px 0px 6px, rgba(200, 200, 200, 0.5) 0px 0px 12px !important;
}

.hierarchy-editor-toolbar__menu
    .hierarchy-editor-toolbar__card-menu__view-as-card {
    border: none;
    box-shadow: none;
}

.hierarchy-editor-toolbar__menu .hierarchy-editor-toolbar__menu__item {
    border-bottom: none !important;
    border-top: thin solid var(--border-c) !important;
}

.hierarchy-editor-toolbar__menu
    .hierarchy-editor-toolbar__menu__item
    .hierarchy-editor-toolbar__menu__item__icon {
    opacity: 0.75;
    filter: grayscale(100%);
}

#BulletFormatIcons i {
    opacity: 0.75;
}

.hierarchy-editor-toolbar__menu
    .hierarchy-editor-toolbar__card-menu__view-as-card--on-right {
    background-color: white;
    border: 1px solid var(--border-c) !important;
    border-radius: 3px;
    box-shadow: rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
        rgba(200, 200, 200, 0.2) 0px 0px 6px, rgba(200, 200, 200, 0.5) 0px 0px 12px !important;
}

#QueueExample,
#view-as-card #view-as-card__cards #view-as-card__card .spacedRepetition {
    background-color: white;
    border: 1px solid var(--border-c) !important;
    border-radius: 10px;
    box-shadow: none !important;
}

.ui.popup .toolbar-button,
.ui.popup #BulletFormatIcons .icon {
    border: 1px soild var(--border-c) !important;
}

.popup .toolbar-button--selected {
    border: 1px solid var(--border-c) !important;
    box-shadow: rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
        rgba(200, 200, 200, 0.2) 0px 0px 6px, rgba(200, 200, 200, 0.5) 0px 0px 12px !important;
}

/* Ctrl + f popup */

#hierarchy-editor__ctrl-f {
    margin-top: 5px;
    border-radius: 5px;
    border: 1px solid var(--border-c) !important;
    box-shadow: rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
        rgba(200, 200, 200, 0.2) 0px 0px 6px, rgba(200, 200, 200, 0.5) 0px 0px 12px !important;
}

#hierarchy-editor #hierarchy-editor-list__sticky-top__container {
    z-index: 5;
}

/* Latex */
.katex {
    font-size: 18px !important;
    border-radius: 4px;
    padding: 0px 7px;
}

.LatexNodeFocused {
    border: 1px solid var(--border-c);
    border-radius: 4px;
    color: var(--font-c);
    padding: 0px 2px;
}

.LatexNode {
    text-decoration: none;
}

.LatexNode .latex-node__latex {
    border: none;
    margin-top: 5px;
    box-shadow: rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
        rgba(200, 200, 200, 0.2) 0px 0px 6px, rgba(200, 200, 200, 0.5) 0px 0px 12px;
    border-radius: 4px;
    padding: 2px 7px;
    background-color: white !important;
}

/* Link node */
.LinkNode {
    text-decoration: none;
    color: var(--reference-c, #b979cf);
}

.link-node--focused {
    color: var(--reference-c, #b979cf);
    font-weight: 500;
}

/* Work in progress Rem */
.workInProgressRem {
    padding: 0px;
    background-color: transparent;
}

.workInProgressRem > span::first-letter {
    visibility: hidden;
}

/* Flash Highlight */
.flash {
    background-color: transparent !important;
    box-shadow: none;
    border: none;
}

/* Cards */
/* Cloze */
.cloze {
    background-color: #eee;
    padding: 0px 4px;
    text-decoration: none;
    border-radius: 4px;
    font-weight: 500;
}

/* Image Occlusion */
.image-occlusion__toolbar > .button {
    font-size: 1em;
}

.image-occlusion__toolbar > .button > .icon {
    color: white !important;
}

.image-occlusion .image-occlusion__toolbar .image-occlusion__toolbar__dropdown {
    border: thin solid white;
    background-color: white;
    box-shadow: rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
        rgba(200, 200, 200, 0.2) 0px 0px 6px, rgba(200, 200, 200, 0.5) 0px 0px 24px;
    border-radius: 3px;
}

#clozeChangeDropdown #ClozeIdentifierInfo {
    color: var(--font-c);
}

#clozeChangeDropdown .ClozeIdentifierSelected {
    background-color: hsla(193, 37%, 54%, 0.3);
}

#clozeChangeDropdown #ClozeIdentifierOption {
    border: none;
}

#clozeChangeDropdown #ClozeIdentifierOption:hover {
    background-color: var(--hover-blue-c);
}

/* Queue Cards */
.Queue {
    background-color: white;
    border: thin solid var(--border-c);
    border-radius: 4px;
    box-shadow: 0px 0px 3px 1px rgba(140, 167, 176, 0.25);
}

.Queue #queue__title {
    background-color: var(--soft-blue-c);
    box-shadow: 0px 1px 8px -2px #ccc;
    color: var(--reference-c, #b979cf);
    border-radius: 3px;
}

.Queue #QueueBadge,
.Queue #queue__badge {
    color: white;
    margin-left: 5px;
    padding: 2px 7px;
    border-radius: 7px;
    background-color: var(--main-blue-c);
    border: 1px solid var(--main-blue-c);
    box-shadow: 0px 0px 4px 1px #eee;
    font-size: 12px;
}

.Queue #queue__title #QueueStreakIndicator {
    color: var(--main-blue-c);
    letter-spacing: 500;
}

.Queue #queue__progress-bar {
    background-color: var(--main-blue-c) !important;
}

.spacedRepetition
    .spaced-repetition__prompt
    .indented-rem
    .rem-bullet__document {
    border-radius: 3px;
    display: inline-block;
    padding: 4px;
}

.spacedRepetition .spaced-repetition__prompt {
    font-size: 15px;
    line-height: 1.4;
}

.spacedRepetition .spaced-repetition__prompt .bold {
    font-weight: 400;
}

.spacedRepetition .spacedRepetitionAnswer {
    border-color: var(--border-c);
}

.queue--desktop {
    box-shadow: 0px 0px 1px 10px white;
}

#ArticleQueue .QueueFocused {
    box-shadow: none;
}

.spacedRepetition .spaced-repetition__prompt .indented-rem .rem-bulletDocument {
    color: var(--hover-blue-c);
    font-size: 13px;
    margin-bottom: 5px;
    font-weight: 500;
    background-color: var(--soft-background-c);
}

.spacedRepetition .fill-in-the-blank {
    color: var(--soft-blue-c);
    border: none;
}

.spacedRepetition .spaced-repetition__bottom {
    background-color: var(--soft-background-c);
    font-weight: 500;
    font-size: 13px;
}

.spacedRepetition .spaced-repetition__reveal {
    background-color: var(--soft-background-c);
}

.spacedRepetition
    .spaced-repetition__prompt
    .indented-rem
    .rem-bullet__document
    i.icon {
    display: none;
}

.spacedRepetition .fill-in-the-blank {
    color: var(--main-blue-c);
}

.queue__buttons {
    background-color: var(--soft-background-c);
}

.spacedRepetition .queue__response-button--big[data-tip*="(1/4)"] > img {
    display: none;
}
.spacedRepetition .queue__response-button--big[data-tip*="(2/4)"] > img {
    display: none;
}
.spacedRepetition .queue__response-button--big[data-tip*="(3/4)"] > img {
    display: none;
}
.spacedRepetition .queue__response-button--big[data-tip*="(4/4)"] > img {
    display: none;
}
.spacedRepetition .queue__response-button--big[data-tip*="(1/4)"]:before {
    content: "☹️";
}
.spacedRepetition .queue__response-button--big[data-tip*="(2/4)"]:before {
    content: "😕";
}
.spacedRepetition .queue__response-button--big[data-tip*="(3/4)"]:before {
    content: "🙂";
}
.spacedRepetition .queue__response-button--big[data-tip*="(4/4)"]:before {
    content: "😊";
}

#leech-card #leech-card__header i.frown.outline.icon:before {
    display: none;
}

#leech-card #leech-card__header i.frown.outline.icon:before {
    content: "☹️";
}

#leech-card #leech-card__header {
    margin: 20px;
    font-weight: 500;
}

#leech-card #leech-card__contents {
    border: 1px solid var(--soft-background-c);
    border-radius: 3px;
    box-shadow: rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
        rgba(200, 200, 200, 0.2) 0px 0px 6px, rgba(200, 200, 200, 0.5) 0px 0px 24px;
}

#leech-card #leech-card__fixes .LeechAction,
#leech-card #leech-card__fixes ul li {
    text-decoration: none;
    color: var(--hover-blue-c);
    font-weight: 400;
}

#leech-card #leech-card__fixes .LeechAction:hover {
    text-decoration: none;
    color: var(--hover-blue-c);
    font-weight: 500;
}

#leech-card .leech-card__bottom {
    background-color: var(--soft-background-c);
    color: var(--hover-blue-c);
    font-weight: 500;
    font-size: 13px;
}

.queue__response-button:hover {
    font-weight: 700;
    border-radius: 0px;
}

#milestone .daily-checkpoint {
    color: var(--hover-blue-c) !important;
}

#milestone .badge {
    border: 1px solid var(--soft-background-c);
    border-radius: 3px;
    box-shadow: rgba(200, 200, 200, 0.1) 0px 0px 0px 1px,
        rgba(200, 200, 200, 0.2) 0px 0px 6px, rgba(200, 200, 200, 0.5) 0px 0px 24px;
}

.queue__response-button,
.accuracy-item {
    background-color: var(--soft-background-c);
    color: var(--font-c);
    font-weight: 500;
}

.queue__response-button:hover .queue__response-button__next-time {
    color: white;
}

.queue__response-button:hover,
.accuracy-item:hover {
    background-color: var(--hover-blue-c);
    font-weight: 700;
    opacity: 0.65;
}

#milestone h1 {
    color: var(--hover-blue-c);
    font-weight: 600;
}

.Queue .queue__no-items .success {
    font-weight: 600;
    color: var(--hover-blue-c);
    padding-bottom: 20px;
    font-size: 15px;
}

#document-sidebar__link__queue-indicator {
    font-size: 12px;
}

#document-sidebar__link__queue-indicator i.star.icon:after {
    padding-right: 2px;
}

#document-sidebar__link__queue-indicator i.star.icon {
    color: white;
    padding-left: 7px;
    padding-right: 2px;
}

.queue__streak-indicator i.fire.icon {
    color: white;
}

.QueueDesktop .queue__title .queue__streak-indicator i.fire.icon {
    color: var(--main-blue-c) !important;
}

.queue__streak-indicator {
    align-items: baseline !important;
}

.black-out--enable {
    background-color: white;
}

.addListItemButton {
    border: none;
    border-radius: 3px;
    background-color: var(--soft-background-c);
    padding: 1px 7px;
    color: #888;
}

#QueueCollapsed {
    background-color: var(--soft-background-c);
    color: #aaa;
}

#QueueCollapsed #QueueCollapsedSmall {
    font-size: 13px;
}

#hierarchy-editor__embedded-queue-mode-toggle {
    color: #888 !important;
    margin-bottom: 5px !important;
}

#hierarchy-editor__embedded-queue-mode-toggle:hover {
    color: var(--font-background-c) !important;
}

/* Buttons */
.ui.button {
    background: var(--main-blue-c);
    color: white;
}

.ui.button:hover {
    background: var(--hover-blue-c);
    color: white;
}

.ui.button i.add.icon {
    color: white;
}
/* } */
``` 
        - tskn's Font Customization 
            - code
                - ```css
:root {
    --main-blue-c: #65b6fb;
    --hover-blue-c: #4baae5;
    --soft-blue-c: #96c9f8;
    
    --font-c: 6f8091;
    --font-background-c: lightgray;
    
    --border-c:#f5f6f8;
    
    --soft-background-c:#f5f6f8;
    
    --bullet-main: #e2e2e2;
    --bullet-doc: #82c6f6;
    --bullet-folder: #528cc2;
    --bullet-concept: #adcb2a;
    --bullet-descriptor: #f9c866;
    
    --focus-font-weight: 350;
``` 
            - Highlighter
                - ```css
 /* Highlight Colors */
    --highlight-red-c: #ffc7c7;
    --highlight-orange-c: #ffd599;
    --highlight-yellow-c: #fef49d;
    --highlight-green-c: #d7e985;
    --highlight-purple-c: #e4b1eb;
    --highlight-blue-c: #afd9fb;
```
            - Links
                - ```css
  /* Linked Rems Color */
    --reference-c: #b979cf;
    /* Quote Background Color */
    --quote-background-c: #ecf3f6;
```
            - Headings
                - ```css
   /* Header size */  
    /* --header-1-font-size: 22px;
    --header-1-font-weight: 400;
    --header-2-font-size: 18px;
    --header-2-font-weight: 380;
    --header-3-font-size: 15px;
    --header-3-font-weight: 350;
    
    --header-1-margin-top: 10px;
    --header-2-margin-top: 8px;
    --header-3-margin-top: 5px; */
    
    /* === Font === */
    /* --font-body: "Helvetica Neue", Arial, sans-serif; */

}

``` 
            - sidebar
                - ```css
/* Sidebar Font */
#homepage #content #document-sidebar,
#main #content #document-sidebar {
  font-family :  Arial Unicode MS;
}
```
    - Lighter
        - ```css
/*font configuration*/

body {
  font-family: "Helvetica Neue","Arial Unicode MS", -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica Neue, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji",
    "Arial Unicode MS", "Microsoft YaHei Light", sans-serif;
}

/*Portals and search configuration*/
#hierarchy-editor .portal-rem--blue,
#hierarchy-editor .portal-rem--embedded-search {
  background-color: #ebf1f5;
}

#hierarchy-editor .portal-rem {
  border-color: #ebf1f5;
  color: #222;
}

#hierarchy-editor .hierarchy-editor__after_portal--blue,
#hierarchy-editor .indented-hierarchy-editor-rem--after-portal-embedded-search {
  border-color: #ebf1f5;
}

#hierarchy-editor .portal-rem .portal-rem-top,
#hierarchy-editor .portal-rem .portal-rem-top--embedded-search-top {
  border-color: #ebf1f5;
}

#no-search-results {
  color: #222;
}

#show-embedded-search-button,
#hierarchy-editor .search-portal-tree-node {
  border-color: #ebf1f5;
  background-color: #ebf1f5;
}

/*Sidebar config*/
div#logo {
  display: none;
}
#DocumentationList .document-list-item--opened,
#documentList .document-list-item--opened {
  border-left-color: #e9e9ed;
  color: #37352f;
}

div#document-sidebar__collapse-icon__container {
  display: flex;
  align-items: center;
  justify-content: center;
}

#document-sidebar__account-capsule__text {
  height: 25px !important;
  width: 25px !important;
}

span.document-sidebar__account-capsule__name {
  display: none;
}

div#document-sidebar__account-capsule:hover {
  background-color: #f7f6f3;
}

#homepage #content #document-sidebar,
#main #content #document-sidebar {
  background-color: #fff;
  border-color: #eee;
}

#document-sidebar {
  border: solid 2px #efefef;
}

.document-list-item {
  color: #aaa9a5;
}
#document-sidebar__link {
  border-radius: 2px;
}

#document-sidebar__link,
#document-sidebar__document-buttons__document-link-container,
.document-list-header {
  text-transform: uppercase;
}

/*Text configuration*/

/*Document*/
.concept_rem_type {
  color: #aac53c;
  font-weight: 400;
}
.descriptor_rem_type {
  color: #ee7945;
  font-weight: 380;
}

#hierarchy-editor .TreeNode--list--in-card-content {
  border-color: #738694;
  border-width: 1.5px;
}

.document-title {
  font-weight: 400;
}
.rem-text {
  color: #202b33;
}

.rem-bullet {
  background-color: 
}

.rem-header--1,
.rem-header--2,
.rem-header--3 {
  font-weight: 350;
  background-color: #fff;
}

.rem-reference-link {
  color: #48aff0;
}

.rem-indented-indicator {
  display: none;
}

#hierarchy-editor .TreeNode {
  border-color: #ffffff;
}

/*scrollbar config*/

/* width */
::-webkit-scrollbar {
  width: 8px;
}

/* Track */
::-webkit-scrollbar-track {
  background: #fff;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: #ddd;
  border-radius: 6px;
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #ccc;
}

``` 
    - Clean 
        - ```css
 /* Title */
#document .document-title {
    text-align: left;
    font-family: "Arial Unicode MS";
    font-size: 40px; 
}


/* Header */
.rem-header--1 {
    padding: 1px 20px;
    line-height: 1.5em;
    border-radius: 20px 20px 20px 0px;
    text-align: left;
}

/* Sidebar */

#main #content #document-sidebar {
    background-color: #fff;
    background-image: radial-gradient(#DDD, #FFF), radial-gradient(#DDD, #FFF);
    background-size: 2px 100%;
    background-position: 0 0, 100% 0;
    background-repeat:	no-repeat;
}

/* Body */
body {
    font-family: "Arial Unicode MS";
}

/* Highlighting */

/*green*/
.highlight-color--green, ::selection {
    padding: 1px 20px;
    line-height: 1.5em;
    border-radius: 20px 20px 20px 0px;
    background-color: #80cbc4
}
/*red*/
.highlight-color--red, ::selection {
    padding: 1px 20px;
    line-height: 1.5em;
    border-radius: 20px 20px 20px 0px;
    background-color: #ff867f
}
/*blue*/
.highlight-color--blue, ::selection {
    padding: 1px 20px;
    line-height: 1.5em;
    border-radius: 20px 20px 20px 0px;
    background-color: #90caf9
}
/*yellow*/
.highlight-color--yellow, ::selection {
    padding: 1px 20px;
    line-height: 1.5em;
    border-radius: 20px 20px 20px 0px;
}
/*purple*/
.highlight-color--purple, ::selection {
    padding: 1px 20px;
    line-height: 1.5em;
    border-radius: 20px 20px 20px 0px;
    }
/*orange*/
.highlight-color--orange, ::selection {
    padding: 1px 20px;
    line-height: 1.5em;
    border-radius: 20px 20px 20px 0px;
} 
 

/* Rem-indented */

.rem-indented-indicator {
    display: none;
}

 /*
 .rem-indented-indicator::before{
  content: '';
  color: #000;
  margin: 0px 0px -10px 0px;
  vertical-align: 'bottom';
  font-size: 8px;
  }
 */
  
/* Portals */
#hierarchy-editor .portal-tree-node {
    border-color: #000;
    border-width: 2px;
    border-top-width: 2px;
    margin: 5px;
    padding: 10px;
    border-radius: 16px;
    border-top-width: 2px;
    border-top-style: solid;
    border-top-color: rgb(0, 0, 0);
    border-bottom-width: 2px;
    border-bottom-style: solid;
    border-bottom-color: rgb(0, 0, 0);
    border-color: white;
    box-shadow: inset -2px 2px 8px 2px rgba(0, 0, 0, 0.08), inset 0px -6px 15px -2px rgba(0, 0, 0, 0.1);
}
#hierarchy-editor .portal-rem .portal-rem-top, #hierarchy-editor .portal-rem--blue {
	height: 0;
	border-color: white;
}
.hierarchy-editor__after-portal {
    display: none;
}
.portal-rem-hamburger {
	padding-left: 10px;
	padding-top: 10px;
} 
 
``` 
    - White Minimalist
        - Body
            - ```css
body {
    background-color: #F8F8F9;
    height: 100%;
    margin: 0.5;
    font-family: Arial Unicode MS, sans-serif;
    font-weight: 300; 
    font-size: 15px;
    color: #535666;
    caret-color: #F7FEFF;
}
#hierarchy-editor .rem-container--focused {
    background-color: #FBFDFF;
    border-radius: 2px;
    margin-left: -25px;
    padding-left: 25px;
}
#hierarchy-editor .rem-container--spacious .rem-text {
    padding-bottom: 5px;
    padding-top: 5px;
    padding-left: 20px;
}
#ExamplesPageContainer #ExamplesPageContent, #export-container #export, #HelpPage #HelpPageContent, #sign-up-page-container #sign-up-page, #StatsPage #StatsPageContent, .centered-page, .document--narrow {
    background-color: rgba(252, 252, 251, 0.85);
}

/* Update 23 March 2021*/
#hierarchy-editor .rem-container .rem-text {
    color: rgba(84, 87, 99, 1);
	margin-left: 0px;
	margin-right: 0px;
    padding-left: 14px;
}
.rem-bullet, .rem-bullet--in-list {
    width: 1px;
    height: 1px;
    background-color: rgba(248, 248, 248, 1);
    border-color: rgba(211, 212, 216, 0.55);
}
.rem-bullet__container {
    top: 4px;
}
.rem-bullet__container-H1 {
    top: 8px;
}
.rem-bullet__container-H2 {
    top: 7px;
}
.rem-bullet__container-H3 {
    top: 4px;
}
.rem-header--1 {
	background-color: rgba(0,0,0,0);
	border-radius: 50px;
	font-weight: 400;
}
#document #actionRequiredDocumentTitle, #document .document-title {
    font-size: 24px;
    font-weight: 420;
}
#hierarchy-editor .is-toolbar-previous-focus-rem {
    box-shadow: 0 0 0px 0 rgba(85,205,196,0);
    border-radius: 2px;
    background-color: rgba(85,205,196,.13);
}
.flash {   
	background-color:rgba(0, 141, 184, 0.06)!important;
    box-shadow: 1px 2px 9px 5px rgba(0,0,0,0);
    margin-left: -20px;
    padding-left: 20px;
}
.pane {
    padding-left: 0px;
}
#DocumentTable .Cell {
    color: #535666;
}
#DocumentTable .ReactVirtualized__Table__headerRow {
    color: #535666;
}
.gutter {
    background-color: rgba(247, 247, 247, 0.85);
}
.rem-calendar-icon--today {
    filter: contrast(10) brightness(3) hue-rotate(60deg);
}
.LinkNode {
    text-decoration: underline;
    color: rgb(79, 76, 210,0.9);
    font-weight: 200;
}
.rem-reference-link {
    color: #029eff;
    font-weight: 200;
}
.rem-reference-link:hover {
    background-color: rgba(98, 160, 250,.2);
    font-weight: 250;
    border-radius: 30px;
	margin-left: -5px;
	padding-left: 6px;
	margin-right: -5px;
	padding-right: 5px;
}
.rem-reference--highlighted {
    border-color: rgba(0,0,0,0);
    box-shadow: 0 0 0px 0px rgba(0,0,0,0);
}
.rem-reference--focused {
    box-shadow: 0 0 0 0px rgba(0,0,0,0);
}
#hierarchy-editor .TreeNode--list--in-card-content {
    border-color: rgb(79, 76, 210,0.4);
    border-width: 1px;
    margin-left: 2px;
    margin-bottom: 6px;
}
.cloze {
    background-color: rgba(210,225,248,0);
    border-bottom: 3px solid rgb(79, 76, 210,0.4);
    padding-bottom: 0px;
    font-weight: 380;
    font-style: italic;
}
/*ScrollBar - Updated 29 April 2021*/
::-webkit-scrollbar {
  width: 8px;
}

::-webkit-scrollbar-track {
	background: rgba(89, 105, 113,0.2);
	border-radius: 20px;
}
::-webkit-scrollbar-thumb {
	background-color: rgb(116, 120, 120,0.3);
	border-radius: 20px;
	border: 0px solid rgba(89, 105, 113);
}
::-webkit-scrollbar-thumb:hover {
	background-color: rgb(116, 120, 120,0.6);
	border-radius: 20px;
	border: 0px solid rgba(89, 105, 113);
}
``` 
                - font-size: 15px;
                - height: 100%;
                - caret-color: #55CDC4;
                - color: #535666;
                - margin: 0;
                - background-color: #F8F8F9;
                - font-family: fira code,-apple-system,BlinkMacSystemFont,segoe ui,Roboto,Helvetica,Arial,sans-serif,apple color emoji,segoe ui emoji,segoe ui symbol;
        - Portal
            - ```css
#hierarchy-editor .TreeNode {
    border-color: #e5e5e5;
    border-width: 1.1px;
    transition-timing-function: linear;
    position: relative;
    background-color: transparent;
    padding-left: 45px;
    padding-top: 0.3px;
    padding-bottom: 0.7px;
    margin-top: 2px;
    margin-bottom: 1px;
}
#hierarchy-editor .TreeNode--dark-indent-line {
    border-color: #efefef!important;
    border-width: 1px;
    background-color: transparent;
}
.hierarchy-editor--ltr .TreeNode {
    margin-left: 2.5px;
    padding-left: 20px;
    border-left-style: dashed;
}
#hierarchy-editor .portal-rem {
    border-style: none none;
    border-top-style: none;
    border-right-style: none;
    border-bottom-style: none;
    border-left-style: none;
    border-width: 0px;
    margin-top: 10px;
    margin-left: -7px;
    margin-right: -7px;
    padding-top: 0px;
    height: 100%;
}
#show-embedded-search-button {
	background-color: #F0F0F2;
    padding-left: 10px;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-right: 12px;
    margin-top: 10px;
    margin-bottom: 10px;
    border: 0px none rgb(0,0,0);
    border-bottom: 0px solid #000;
    border-radius: 7px;
    border-bottom-right-radius: 7px;
    border-bottom-left-radius: 7px;
    margin-right: 6px;
    margin-left: -6px;
    color: #82868B;
    font-weight: 280;
}
.embeddedSearch {
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
    border-bottom-right-radius: 5px;
    border-bottom-left-radius: 5px;
    border: 0px solid #d3d4d8;
    border-top-color: rgba(183,183,187,0);
    border-top-style: solid;
    border-top-width: 0px;
    border-right-color: rgba(183,183,187,0);
    border-right-style: solid;
    border-right-width: 0px;
    border-bottom-color: rgba(183,183,187,0);
    border-bottom-style: solid;
    border-bottom-width: 0px;
    border-left-color: rgba(183,183,187,0);
    border-left-style: solid;
    border-left-width: 0px;
    border-image-source: initial;
    border-image-slice: initial;
    border-image-width: initial;
    border-image-outset: initial;
    border-image-repeat: initial;
    text-decoration: none;
    text-decoration-line: none;
    text-decoration-thickness: initial;
    text-decoration-style: initial;
    text-decoration-color: initial;
    padding-top: 5px;
    padding-right: 5px;
    padding-bottom: 6px;
    padding-left: 10px;
    margin-bottom: 5px;
    margin-left: 10px;
    margin-right: 10px;
    margin-top: 0px;
    background-color: #FDFDFE;
}
#hierarchy-editor .portal-rem--embedded-search {
    border-color: none;
    background-color: #F0F0F2;
    margin-right: 6px;
    padding-top: 0px;
    margin-top: 14px;
    margin-left: -6px;
    padding-bottom: 14px;
    margin-bottom: 20px;
    border-bottom-right-radius: 7px;
    border-bottom-left-radius: 7px;
}
#hierarchy-editor .rem-container__top-level-spacer {
    margin-top: 10px;
    width: 100%;
    display: block;
}
#search-results__controls #search-results__control .search-results__control__keyboard-shortcut, .quote {
    margin-right: 0px;
    margin-left: 0px;
    background-color: rgba(98, 160, 250,.2);
    border-radius: 30px;
    padding: 1px;
    padding-left: 6px;
    padding-right: 6px;
}
i.icon.search:before {
    content: "\f002";
    zoom: 125%;
    padding-top: 6px;
    padding-left: 2px;
    color: rgba(183,183,187,0.5);
}
i.icon.refresh:before {
    content: "\f021";
    zoom: 120%;
    color: rgba(183,183,187,0.5);
    padding-right: 5px;
}
#embedded-search-refresh-button {
    float: right;
    padding-top: 6px;
    padding-right: 15px;
    padding-bottom: 10px;
    padding-left: 5px;
}
#no-search-results {
    color: rgba(183,183,187,0.7);
    text-align: center;
    margin-top: 20px;
    margin-bottom: 5px
}
#hierarchy-editor .portal-rem .portal-rem-top--embedded-search-top {
    border-color: rgb(0,0,0,0);
    text-align: right;
    border-top: solid rgb(0,0,0,0);
    border-width: 0px;
    position: relative;
    top: 0px;
    padding-top: 0px;
    margin-top: -25px;
}
#hierarchy-editor .search-portal-tree-node {
    border-bottom-width: 0px;
    border-top-width: 0px;
    border-left: 0px solid rgb(0,0,0,0);
    border-bottom-color: rgb(0,0,0,0);
    border-right: 0px solid rgb(0,0,0,0);
    border-top-color: rgb(0,0,0,0);
    margin-left: -6px;
    margin-right: 6px;
    padding-left: 15px;
    padding-right: 9px;
    padding-bottom: 12px;
    margin-bottom: 7px;
    margin-top: -30px;
    background-color: #F0F0F2;
    border-bottom-right-radius: 7px;
    border-bottom-left-radius: 7px;
}
.rem-indented-indicator {
    color: rgb(0,0,0,0);
    top: -1.8px;
    position: fixed;
}
#hierarchy-editor .isSearchResult {
    background-color: transparent;
    margin-top: 0px;
    margin-bottom: -0px;
    border: 0px solid rgb(0,0,0);
    border-radius: 0px;
    margin-right: 0px;
    margin-left: 0px;
    padding-left: 0px;
}
#hierarchy-editor .rem-container__top-level-spacer .rem-container__top-level-spacer__inner {
    border-color: rgb(0,0,0,0);
    border-top: solid rgb(0,0,0,0);
    border-width: 5px;
    bottom: 0px;
    position: relative;
}
#hierarchy-editor .portal-rem .portal-rem-top, #hierarchy-editor .portal-rem .portal-rem-top--embedded-search-top {
    border-color: rgb(0,0,0,0);
    text-align: right;
    border-top: solid rgb(0,0,0);
    border-width: 0px;
    position: relative;
    top: -4px;
    padding-top: 13px;
}
#hierarchy-editor .portal-tree-node {
    border-left: 0px solid rgba(183,183,187,0);
    border-bottom-color: rgba(183,183,187,0);
    border-right: 0px solid rgba(183,183,187,0);
    border-bottom: 8px solid #F0F0F2;
    border-top: 4px solid #F0F0F2);
    margin-left: -6px;
    margin-right: 6px;
    margin-top: -16px;
    margin-bottom: 10px;
    padding-left: 15px;
    padding-right: 9px;
    padding-top: 6px;
    padding-bottom: 0px;
    background-color: #F0F0F2;
    border-radius: 7px;
    border-bottom-right-radius: 7px;
    border-bottom-left-radius: 7px;
}
#hierarchy-editor .hierarchy-editor__after-portal .addItemAfterPortal {
    height: 25px;
    width: 100%;
    padding-left: 8px;
    margin-top: -8px;
    margin-bottom: -4px;
}
#hierarchy-editor .hierarchy-editor__after-portal {
    border-bottom-style: solid;
    border-width: 0px;
    border-top-width: 0px;
    border-right-width: 0px;
    border-bottom-width: 0px;
    border-left-width: 0px;
    padding-top: 0px;
    padding-bottom: 0px;
    margin-left: -6px;
    margin-right: 7px;
}
#hierarchy-editor .rem-container--not-included-in-document-scope {
    color: #535666;
    padding-left: 15px!important;
    padding-bottom: 2px;
    padding-top: 1px;
}
```
        - Logo and Side, Bottom, Nav Bars
            - ```css
/*Added 23 March 2021*/
#homepage #content .document-sidebar--pinned, #main #content .document-sidebar--pinned {
    height: 100.1%;
}

#homepage #content .document-sidebar--floating, #main #content .document-sidebar--floating {
    border-top-left-radius: 0px;
    border-top-right-radius: 6px;
    border-bottom-left-radius: 0px;
    border-bottom-right-radius: 6px;
    z-index: 7!important;
    background-color: rgba(117,166,239,0.12);
}
#homepage #content #document-sidebar, #main #content #document-sidebar {
    background-color: #3B464B;
	color: rgb(248, 248, 249, .6);
}
#DocumentationList .documentListNoDocuments, #documentList .documentListNoDocuments {
    color: rgb(248, 248, 249, .25);
}
/*logo*/
#document-sidebar_top #logo img {
	filter: contrast(1) brightness(1.2) grayscale(0);
	opacity: .5;
	height: 25px;
} 
#document-sidebar_top #logo img:hover {
	filter: contrast(1) brightness(1.2) grayscale(0);
	opacity: .8;
} 
#document-sidebar_top #logo {
    margin-top: 15px;
}
#document-sidebar__account-capsule:hover {
	background-color: rgb(66, 76, 80);
}
#document-sidebar_top__user-and-collapse {
	margin-top: 10px;
}
#document-sidebar__collapse-icon__container {
	filter: contrast(0.2) hue-rotate(300deg) brightness(1);
}
.acc-capsule__menu__trial-info:hover {
    background-color: #455055;
}
.acc-capsule__menu__trial-info img {
    filter: contrast(0.2) hue-rotate(300deg) brightness(1);
}
#acc-capsule__menu {
	background-color: #424C50;
	border: 0px solid rgb(0,0,0,0);
	color: rgb(248, 248, 249, .6);
}
.acc-capsule__menu__account .acc-capsule__menu__name {
	color: rgb(62, 114, 173);
}
.acc-capsule__menu__account .acc-capsule__menu__email {
	color: rgb(62, 114, 173);
}
.acc-capsule__menu__account {
	border-bottom: 0px
}
.acc-capsule__menu__element--hoverable:hover {
	border-bottom: 0px
}
.acc-capsule__menu__element--hoverable:hover {
	background-color: #455055;
}
.switch-knowledgebase .switch-knowledgebase__knowledgebase, .switch-knowledgebase .switch-knowledgebase__knowledgebase .switch-knowledgebase__knowledgebase__button {
	background-color: transparent;
	color: rgb(62, 114, 173);
}
.switch-knowledgebase {
	border-color: rgb(248, 248, 249, .3);
}
#document-sidebar__document-buttons .document-sidebar__document-buttons__button-container {
	filter: contrast(0.2) hue-rotate(300deg) brightness(1); 
}
#document-sidebar__document-buttons .document-sidebar__document-buttons__button {
    display: flex;
    opacity: 1;
}
.flashcards-icon {
	filter: contrast(0.2) hue-rotate(300deg) brightness(1); 
}
#document-sidebar__link__queue-indicator {
	background-color: rgba(90, 98, 101,.7);
	border-radius: 10;
}
#document-sidebar__link__queue-indicator .icon {
	color: rgba(73, 134, 205,1);

}
#document-sidebar__document-buttons .document-sidebar__document-buttons__button:hover {
	filter: contrast(0.2) hue-rotate(300deg) brightness(2.5);
}
#document-sidebar__link:hover {
	background-color: #404B50;
	color: rgb(248, 248, 249, .6);
}

/*Added 23 March 2021*/
#document-sidebar__link:hover:not(.document-sidebar__linkOpen) {
    background-color: rgb(73 83 88 / 100%);
    border-radius: 10px;
    margin: 5px;
    padding: 8px 5px 8px 10px;
}
/*Added 23 March 2021*/
#document-sidebar__document-buttons:hover:not(.document-sidebar__linkOpen) {
    background-color: rgb(73 83 88 / 100%);
    border-radius: 10px;
    margin: 5px;
}

#document-sidebar__link {
	color: rgb(248, 248, 249, .6);
}
#homepage #content #document-sidebar a:hover, #homepage #content #document-sidebar a:visited, #main #content #document-sidebar a:hover, #main #content #document-sidebar a:visited {
    color: rgb(248, 248, 249, .6)!important;
}
#homepage #content #document-sidebar a, #main #content #document-sidebar a {
	color: rgb(248, 248, 249, .6)!important;
}
#document-sidebar__document-buttons:hover {
	background-color: #404B50;
}
.document-sidebar__linkOpen {
	background-color: #495358!important;
}
#DocumentationList .folder-float-buttons, #documentList .folder-float-buttons {
	background-color: #404B50;
}

i.icons .corner.icon {
	text-shadow: -1px -1px 0 #989E9E, 1px -1px 0 #989E9E, -1px 1px 0 #989E9E, 1px 1px 0 #989E9E;
	color: #747878;
}

#DocumentationList .document-list-item .document-list-item__folder-icon-container, #documentList .document-list-item .document-list-item__folder-icon-container {
	filter: contrast(0.2) hue-rotate(300deg) brightness(1);
}

.hierarchy-editor-toolbar-container--opened #hierarchy-editor-toolbar {
    border-color: rgba(0,0,0,0);
    border-top: solid rgba(0,0,0,0);
    border-width: thin;
    white-space: nowrap;
    display: flex;
    align-items: center;
    height: 100%;
    padding-left: 15px;
    padding-right: 15px;
    background-color: #F8F8F9;
}
.document-sidebar--collapsed--horizontal {
    border-color: rgba(0,0,0,0);
    border-bottom: solid rgba(0,0,0,0);
    border-width: thin;
    width: 100%;
    height: 40px;
    flex-shrink: 0;
}
#DocumentationList .document-list-item--opened, #documentList .document-list-item--opened {
    font-weight: 370!important;
    background-color: #495358;
    border-width: 3px;
    border-left-color: #41668C;
    font-size: 13.5px!important;
    color: rgb(248, 248, 249, .9);
    font-style: bold;
}
/*Hover*/
#DocumentationList .document-list-item:hover, #documentList .document-list-item:hover {
    background-color: rgb(73,83,88,0.4);
    font-size: 14px;
    color: rgb(248, 248, 249, .7);
}
#DocumentationList .document-list-item, #documentList .document-list-item {
    font-weight: 390;
    border-width: 3px;
    font-size: 14px;
    margin-top: 0px;
    margin-bottom: 0px;
    padding-top: 5px;
    padding-bottom: 5px;
}

#hierarchy-editor .rem {
	color: #535666;
}
#document .document-title {
    color: #535666;
}
#document-parents .parent-link {
    color: #535666;
}
#document-sidebar__hidden-link__container {
    padding-top: 5px;
    padding-left: 5px;
    padding-right: 0px;
}
i.icon {
	opacity: 1;
	color: rgb(116, 120, 120);
}
#document-sidebar__bottom-buttons {
	filter: contrast(0.2) hue-rotate(300deg) brightness(1);
}
#document-sidebar__bottom-buttons .document-sidebar__bottom-buttons__button:hover {
	filter: contrast(0.2) hue-rotate(300deg) brightness(3);
}

#document-hover-preview {
    background-color: #F8F8F9;
    border: thing solid #c8c8c8;
    border-radius: 6px;
    color: #535666;
    padding-top: 17px;
    padding-bottom: 0px;
    margin-left: 10px;
    padding-left: 15px;
    padding-right:9px;
}
.right-click-menu {
	background-color: #424C50;
	border-radius: 3px;
}

/*Added 23 March 2021*/
.document-link__right-click-menu {
	background-color: #424C50;
	border-radius: 3px;
	color: rgb(248, 248, 249, .6);
}

/*Updated 23 March 2021*/
.document-sidebar-item__right-click-menu .item:hover {
	background-color: rgb(94, 110, 118, 0.2);
	border-radius: 3px;	
}

/*Tutorial menu*/
#DocumentationList #documentation-list__section__large-title {
	background-color: #3B464B;
}
#DocumentationList #documentation-list__section {
	border-color: rgb(248, 248, 249, .3);
}
.navigation-bar  {
    background-color: #F8F8F9;
}

/*Added 23 March 2021*/
#documentList .document-list-item__plus-icon {
	filter: brightness(1.5) grayscale(1);
}
/*Added 23 March 2021*/
#UpdateIndicator {
    border: 0px;
    font-size: 13px;
    color: rgb(73, 134, 205, .7);
    font-weight: 300;
}
```
        - Highlighter colors
            - ```css
/*The whole block has been updated - 23 March 2021*/
/*red*/
.highlight-color--red, .pdf-viewer__highlight-container--red .AreaHighlight, .pdf-viewer__highlight-container--red .Highlight__part {
    background-color: rgba(243, 96, 106,.45);
    border-radius: 35px;
    margin-left: 0px;
    margin-right: 0px;
    padding-left: 6px;
    padding-right: 6px;
}
/*orange*/
.highlight-color--orange, .pdf-viewer__highlight-container--orange .AreaHighlight, .pdf-viewer__highlight-container--orange .Highlight__part {
    background-color: rgba(255, 209, 128,.65);
    border-radius: 35px;
    margin-left: 0px;
    margin-right: 0px;
    padding-left: 6px;
    padding-right: 6px;
}
/*yellow*/
.highlight-color--yellow, .pdf-viewer__highlight-container--undefined .AreaHighlight, .pdf-viewer__highlight-container--undefined .Highlight__part, .pdf-viewer__highlight-container--yellow .AreaHighlight, .pdf-viewer__highlight-container--yellow .Highlight__part, .PdfHighlighter .textLayer ::selection {
    background-color: rgba(255, 255, 141,.80);
    border-radius: 35px;
    margin-left: 0px;
    margin-right: 0px;
    padding-left: 6px;
    padding-right: 6px;
}
/*green*/
.highlight-color--green, .pdf-viewer__highlight-container--green .AreaHighlight, .pdf-viewer__highlight-container--green .Highlight__part {
    background-color: rgba(206, 255, 157,.75);
    border-radius: 35px;
    margin-left: 0px;
    margin-right: 0px;
    padding-left: 6px;
    padding-right: 6px;
}
/*blue*/
.highlight-color--blue, .pdf-viewer__highlight-container--blue .AreaHighlight, .pdf-viewer__highlight-container--blue .Highlight__part {
    background-color: rgba(201, 246, 255,.75);
    border-radius: 35px;
    margin-left: 0px;
    margin-right: 0px;
    padding-left: 6px;
    padding-right: 6px;
}
/*purple*/
.highlight-color--purple, .pdf-viewer__highlight-container--purple .AreaHighlight, .pdf-viewer__highlight-container--purple .Highlight__part {
    background-color: rgba(202, 195, 255,.75);
    border-radius: 35px;
    margin-left: 0px;
    margin-right: 0px;
    padding-left: 6px;
    padding-right: 6px;
}
```
        - Tags
            - 5 Tags
                - ```css
/*Upda	ted 31 March 2021
- background-color has been deactivated, this allows the tag to pick the color of the highlight rem.
- border-radius has been increased to 15px
*/
.hierarchy-editor__tag-bar__tag {
    border-radius: 15px;
    padding-top: 0px;
    padding-bottom: 0px;
    padding-left: 10px;
    padding-right: 5px;
    color: #535666;
    font-size: 13px;
	/*background-color: rgb(0,0,0,0);*/
	white-space: pre;
    font-weight: 300;
    margin-top: 0px;
    margin-bottom: 0px;
}
.hierarchy-editor__tag-bar {
	top: 1px;
	bottom: 0px;
}
/*Added 31 March 2021*/
.hierarchy-editor__tag-bar__tag__delete:hover {
	color: black;
	background-color: rgba(0,0,0,0);
}
```
        - Popups
            - 6 Popups
            - ```css
.concept_rem_type, .question_rem_type {
    font-weight: 380;
    color: #535666;
}
.Queue .queue__title {
    height: 35px;
    border-radius: 10px 10px 0 0;
    display: flex;
    align-items: center;
    background-color: #E8EEF8;
}
.Queue .queue__title .queue__sizeButton {
    border: none;
    outline: none;
    background-color: #E8EEF8;
    color: #232735;
    border-radius: 10px;
    display: flex;
}
.queue-container {
    color: #535666;
}
```
        - Checkbox
            - ```css
.rem-checkbox {
    margin-right: 10px;
    margin-top: 3px;
}
```
        - Code Block
            - ```css
#code-node {
    font-family: Arial Unicode MS;
}
```
        - Que
            - ```css
.concept_rem_type, .question_rem_type {
    font-weight: 700;
    color: #535666;
}
.Queue .queue__title {
    height: 35px;
    border-radius: 10px 10px 0 0;
    display: flex;
    align-items: center;
    background-color: #E8EEF8;
}
.Queue .queue__title .queue__sizeButton {
    border: none;
    outline: none;
    background-color: #E8EEF8;
    color: #232735;
    border-radius: 10px;
    display: flex;
}
.queue-container {
    color: #535666;
}
```
        - Sticky Menu
            - 10 Sticky Menu
            - ```css
#hierarchy-editor #hierarchy-editor-list__sticky-top__container #hierarchy-editor-list__sticky-top .hierarchy-editor-list__sticky-top__rem-container .rem-text {
    background-color: #F8F8F9;
    border-style: none;
    color: #535666

}
#hierarchy-editor .rem-container--sticky-document-title .rem-text {
    font-size: 20px;
    color: #F8F8F9;
    border-style: none;
}
#hierarchy-editor #hierarchy-editor-list__sticky-top__container #hierarchy-editor-list__sticky-top {
    background-color: #F8F8F9;
    color: #535666;
    padding-left: 0px;
    margin-left: -13px;

}
.remInPortalBlue {
    border-style: none;
}
.remInPortal {
    border-style: none;
}
#hierarchy-editor .indented-hierarchy-editor-remPortal {
    border-style: none;
}
#hierarchy-editor #hierarchy-editor-list__sticky-top__container #hierarchy-editor-list__sticky-top #hierarchy-editor-list__sticky-top__bottom {
    border-bottom: 6px solid #c8c8c8;
    border-radius: 10px;
}
```
        - Sharing Document
            - 11 Sharing Documents
            - ```css
.article-publish-confirmation {
    color: #535666;
}
.ui.checkbox+label, .ui.checkbox label {
    color: #535666;
}

ArticleViewer #ArticleViewerTop {
    color: #535666;
}

#ExamplesPageContainer #ExamplesPageContent, #export-container #export, #HelpPage #HelpPageContent, #sign-up-page-container #sign-up-page, #StatsPage #StatsPageContent, .centered-page, .document--narrow {
    background-color: #F8F8F9;
    color: #535666;
}
```
        - Settings Page
            - ```css
.settings-page .settings-page__sidebar {
    min-width: 195px;
    max-height: 100%;
    display: flex;
    flex-direction: column;
    border-color: rgb(59, 70, 75,0.5);
    border-right: solid rgb(59, 70, 75,0.5);
    border-width: 1;
    background-color: #3B464B;
}
.settings-page .settings-page__sidebar .settings-page__sidebar__link {
    border-color: #3B464B;
    color: rgb(248, 248, 249, .6);
    font-size: 17px;
    padding: 10px 10px 10px 20px;
    border-bottom: solid rgb(59, 70, 75,0.5);
    border-width: 0;
    display: flex;
    align-items: center;
}
.settings-page .settings-page__sidebar .settings-page__sidebar__title {
    color: rgb(248, 248, 249, .6);
    font-weight: 700;
    font-size: 24px;
    margin: 20px;
}
.settings-page label {
    font-size: 14px!important;
    color: #535666;
}
.settings-page .settings-page__content .settings-page__content-inner {
    padding: 30px;
    color: #535666;
}
.settings-page__option {
    margin-top: 10px;
    padding-bottom: 10px;
    display: flex;
    border-width: 1px;
}
.settings-page .settings-page__sub-header {
    border-width: 1px;
    color: #535666;
    font-size: 18px;
    margin: 40px 0 10px;
    padding-bottom: 5px;
    font-weight: 700;
}
.settings-page__option .settings-page__text .settings-page__text__subtext {
    color: rgb(59, 70, 75,0.5);
    margin-top: 5px;
}
.settings-page .settings-page__sidebar .settings-page__sidebar__link:hover {
    background-color: rgb(73,83,88,0.4);
}
.settings-page .settings-page__sidebar .settings-page__sidebar__link--active {
    font-weight: 700;
    background-color: #495358;
    border-left-style: solid;
    border-left-width: 3px;
    border-left-color: #41668C;
    }
.settings-page__option .settings-page__input .settings-page__input-box {
    padding-right: 1rem;
    padding-top: 5px;
    padding-bottom: 5px;
    padding-left: 5px;
    border-style: none;
    border-radius: 4px;
    background-color: #E8F0FC;
}
```
        - Power-ups tag off
            - ```css
.hierarchy-editor__tag-bar .hierarchy-editor__tag-bar__power-up-tag {
	display: none;
}	
```
        - Highlighted focused rem
            - ```css
body {
    caret-color: black;
}

#hierarchy-editor .rem-container--focused {
    background: linear-gradient(
    				90deg,
    				rgba(0,0,0,0) 0%,
    				rgba(0,0,0,0) 3%,
    				rgba(85,205,196,.2) 3%,
    				rgba(85,205,196,.1) 100%);
    border-radius: 0px;
    margin-left: -25px;
    padding-left: 25px;
    padding-top: 0px;
}

#hierarchy-editor .TreeNode .rem-container:hover {
    background: linear-gradient(
    				90deg,
    				rgba(85,159,242,0.3) 0%,
    				rgba(85,159,242,0.3) .5%,
    				rgba(0,0,0,0) .5%,
    				rgba(0,0,0,0) 100%);
    border-radius: 0px;
    margin-left: -25px;
    padding-left: 25px;

}
#hierarchy-editor .TreeNode .rem-container--focused {
    background: linear-gradient(
    				90deg,
    				rgba(85,159,242,0.8) 0%,
    				rgba(85,159,242,0.8) 0.5%,
    				rgba(85,159,242,0) 0.5%,
    				rgba(85,159,242,0) 3%,
    				rgba(85,205,196,.15) 3%,
    				rgba(85,205,196,.075) 100%);
    border-radius: 0px;
    margin-left: -25px;
    padding-left: 25px;
}
#hierarchy-editor .TreeNode .rem-container--focused:hover   {
    background: linear-gradient(
    				90deg,
    				rgba(85,159,242,0.8) 0%,
    				rgba(85,159,242,0.8) .5%,
    				rgba(85,159,242,0) .5%,
    				rgba(85,159,242,0) 3%,
    				rgba(85,205,196,.15) 3%,
    				rgba(85,205,196,.075) 100%);
    border-radius: 0px;
    margin-left: -25px;
    padding-left: 25px;

}
#hierarchy-editor .rem-container--focused .rem-text {
    color: black;
}

#hierarchy-editor .rem-container--focused .concept_rem_type {
    color: black;
}
#hierarchy-editor .rem-container--focused .question_rem_type {
    color: black;
}
#hierarchy-editor .rem-container--focused .hierarchy-editor__tag-bar__tag {
    color: black;
}
#hierarchy-editor .rem-container--focused .rem-bullet, .rem-bullet--in-list {
    background-color: black;
}
#hierarchy-editor .rem-container--focused .rem-hamburger {
	filter: brightness(0);
}
#hierarchy-editor .rem-container--focused .toggleCollapseButton {
	filter: brightness(0);
}
#hierarchy-editor .TreeNode:hover {
    border-color: rgba(85,159,242,.3);
}
#hierarchy-editor .TreeNode:focus-within {
    border-color: rgba(85,159,242,0.8);
}
#hierarchy-editor .rem-container--focused .rem-reference-link {
    color: #284DA9;
    font-weight: 500;
}
#hierarchy-editor .rem-container--focused .LinkNode {
    text-decoration: underline;
    color: rgb(42, 39, 178,1);
    font-weight: 500;
}
#hierarchy-editor .rem-container--focused .rem-bullet__icon {
	color: black;
}
#hierarchy-editor .rem-container--focused .rem-calendar-icon--today {
	color: rgb(61, 58, 200);
	filter: brightness(120) ;
}
#hierarchy-editor .rem-container--focused i.icon.calendar.alternate.outline::before {
	filter: brightness(0.01);
}

/*red*/
#hierarchy-editor .rem-container--focused .highlight-color--red, .pdf-viewer__highlight-container--red .AreaHighlight, .pdf-viewer__highlight-container--red .Highlight__part {
    background-color: rgba(243, 96, 106,.6);
}
/*orange*/
#hierarchy-editor .rem-container--focused .highlight-color--orange, .pdf-viewer__highlight-container--orange .AreaHighlight, .pdf-viewer__highlight-container--orange .Highlight__part {
    background-color: rgba(244, 167, 98,.6);
}
/*yellow*/
#hierarchy-editor .rem-container--focused .highlight-color--yellow, .pdf-viewer__highlight-container--undefined .AreaHighlight, .pdf-viewer__highlight-container--undefined .Highlight__part, .pdf-viewer__highlight-container--yellow .AreaHighlight, .pdf-viewer__highlight-container--yellow .Highlight__part, .PdfHighlighter .textLayer ::selection {
    background-color: rgba(250, 233, 123,.7);
}
/*green*/
#hierarchy-editor .rem-container--focused .highlight-color--green, .pdf-viewer__highlight-container--green .AreaHighlight, .pdf-viewer__highlight-container--green .Highlight__part {
    background-color: rgba(112, 230, 109,.6);
}
/*blue*/
#hierarchy-editor .rem-container--focused .highlight-color--blue, .pdf-viewer__highlight-container--blue .AreaHighlight, .pdf-viewer__highlight-container--blue .Highlight__part {
    background-color: rgba(98, 160, 250,.6);
}
/*purple*/
#hierarchy-editor .rem-container--focused .highlight-color--purple, .pdf-viewer__highlight-container--purple .AreaHighlight, .pdf-viewer__highlight-container--purple .Highlight__part {
    background-color: rgba(162, 102, 232,.6);
}

#hierarchy-editor .rem-container--focused .quote {
    margin-right: 0px;
    margin-left: 0px;
    background-color: rgba(98, 160, 250,.35);
    border-radius: 30px;
    padding: 1px;
    padding-left: 6px;
    padding-right: 6px;
}

#hierarchy-editor .tree-node-container[data-rem-container-tags~="columns"] > .TreeNode > .tree-node-container .rem-container:hover  {
    background: linear-gradient(
    				90deg,
    				rgba(0,0,0,0) 0%,
    				rgba(0,0,0,0) 9%,
    				rgba(85,205,196,.1) 9%,
    				rgba(85,205,196,.05) 100%);
}
#hierarchy-editor .tree-node-container[data-rem-container-tags~="columns"] > .TreeNode > .tree-node-container .rem-container--focused  {
    background: linear-gradient(
    				90deg,
    				rgba(0,0,0,0) 0%,
    				rgba(0,0,0,0) 8.5%,
    				rgba(85,205,196,.2) 9%,
    				rgba(85,205,196,.1) 100%);
}
#hierarchy-editor .tree-node-container[data-rem-container-tags~="columns"] > .TreeNode > .tree-node-container .rem-container--focused:hover  {
    background: linear-gradient(
    				90deg,
    				rgba(0,0,0,0) 0%,
    				rgba(0,0,0,0) 8.5%,
    				rgba(85,205,196,.2) 9%,
    				rgba(85,205,196,.1) 100%);
}
```
        - Optional - To hide the RemNote logo from the side bar ^^(uploaded 1 Feb 2021)^^ 
            - ```css
#document-sidebar_top #logo {
    display: none;
}
```
        - 
- **CSS Snippets ** 
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
