Contao TinyMCE skin
===================

The Contao skin is an exact copy of the default TinyMCE skin (lightgray). It
only adds content to the following two files:

 * `content.min.css`
 * `skin.min.css`


content.min.css
---------------

```css
body, th, td {
    /* Adjust to the back end theme */
    font-family:"Trebuchet MS",Verdana,sans-serif;
    font-size:12px;
    color:#444;
}
ul li {
    list-style:disc outside;
}
ol li {
    list-style:decimal outside;
}
```


skin.min.css
------------

```css
.mce-tinymce {
    border-radius:3px;
}
.mce-panel, .mce-btn {
    background-color:#f6f6f6;
}
.mce-floatpanel, .mce-foot {
    background-color:#fff;
}
.mce-path {
    padding:1px 8px;
}
.mce-path-item, .mce-path .mce-divider {
    font-size:12px;
}
.mce-grid-border a:hover, .mce-grid-border a.mce-active {
    border-color:#8ab858;
    background-color:#8ab858;
}
.mce-primary, .mce-menu-item:hover, .mce-menu-item:focus, .mce-menu-item-normal.mce-active, .mce-menu-item.mce-selected {
    background-color:#8ab858;
}
.mce-primary:hover, .mce-primary:focus {
    background-color:#90bc62;
}
.mce-container, .mce-container *, .mce-widget, .mce-widget *, .mce-reset, .mce-menubar .mce-menubtn button span, .mce-menu-item .mce-ico, .mce-menu-item .mce-text, .mce-path-item, .mce-menubtn button {
    color:#444;
}
.mce-menubar .mce-caret {
    border-top-color:#444;
}
.mce-tooltip, .mce-tooltip * {
    color:#fff;
}
```
