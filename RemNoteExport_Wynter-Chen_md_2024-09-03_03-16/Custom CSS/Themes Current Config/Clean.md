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
