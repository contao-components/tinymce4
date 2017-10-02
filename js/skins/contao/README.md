Contao TinyMCE skin
===================

The Contao skin is an exact copy of the default TinyMCE skin (lightgray). It
only adds content to the following two files:

 * `content.min.css`
 * `skin.min.css`


content.min.css
---------------

```css
@font-face {
    font-family: "Lato Retina";
    src: local("Lato Light"), url(fonts/Lato-Light.woff2) format("woff2"), url(fonts/Lato-Light.woff) format("woff");
    font-weight: 400;
    font-style: normal;
    text-rendering: optimizeLegibility;
}

@font-face {
    font-family: "Lato Retina";
    src: local("Lato Light Italic"), url(fonts/Lato-LightItalic.woff2) format("woff2"), url(fonts/Lato-LightItalic.woff) format("woff");
    font-weight: 400;
    font-style: italic;
    text-rendering: optimizeLegibility;
}

@font-face {
    font-family: "Lato Retina";
    src: local("Lato Medium"), url(fonts/Lato-Medium.woff2) format("woff2"), url(fonts/Lato-Medium.woff) format("woff");
    font-weight: 700;
    font-style: normal;
    text-rendering: optimizeLegibility;
}

@font-face {
    font-family: "Lato Retina";
    src: local("Lato Medium Italic"), url(fonts/Lato-MediumItalic.woff2) format("woff2"), url(fonts/Lato-MediumItalic.woff) format("woff");
    font-weight: 700;
    font-style: italic;
    text-rendering: optimizeLegibility;
}

@font-face {
    font-family: "Lato";
    src: local("Lato Regular"), url(fonts/Lato-Regular.woff2) format("woff2"), url(fonts/Lato-Regular.woff) format("woff");
    font-weight: 400;
    font-style: normal;
    text-rendering: optimizeLegibility;
}

@font-face {
    font-family: "Lato";
    src: local("Lato Regular Italic"), url(fonts/Lato-Italic.woff2) format("woff2"), url(fonts/Lato-Italic.woff) format("woff");
    font-weight: 400;
    font-style: italic;
    text-rendering: optimizeLegibility;
}

@font-face {
    font-family: "Lato";
    src: local("Lato Semibold"), url(fonts/Lato-Semibold.woff2) format("woff2"), url(fonts/Lato-Semibold.woff) format("woff");
    font-weight: 700;
    font-style: normal;
    text-rendering: optimizeLegibility;
}

@font-face {
    font-family: "Lato";
    src: local("Lato Semibold Italic"), url(fonts/Lato-SemiboldItalic.woff2) format("woff2"), url(fonts/Lato-SemiboldItalic.woff) format("woff");
    font-weight: 700;
    font-style: italic;
    text-rendering: optimizeLegibility;
}

/* original content */

body, th, td {
    font: .875rem/1.2 Lato, Roboto, sans-serif;
    color: #222;
}

@media (-webkit-min-device-pixel-ratio: 2),(min-resolution: 192dpi) {
    body, th, td {
        font-family: "Lato Retina", Lato, Roboto, sans-serif;
        font-weight: 300;
    }
}
```


skin.min.css
------------

```css
/* original content */

.mce-tinymce {
    border-radius: 2px;
}

.mce-panel, .mce-btn {
    background-color: #f6f6f8;
}

.mce-floatpanel, .mce-foot {
    background-color: #fff;
}

.mce-path {
    padding: 2px 8px;
}

.mce-path-item, .mce-path .mce-divider {
    font-size: 12px;
}

.mce-grid-border a:hover, .mce-grid-border a.mce-active {
    border-color: #3997fe;
    background-color: #3997fe;
}

.mce-primary, .mce-menu-item:hover, .mce-menu-item:focus, .mce-menu-item-normal.mce-active, .mce-menu-item.mce-selected {
    background-color: #3997fe;
}

.mce-primary:hover, .mce-primary:focus {
    background-color: #208bfe;
}

.mce-primary span {
    color: #fff !important;
}

.mce-title, .mce-label, .mce-txt, .mce-text, .mce-path * {
    font: .875rem/1.2 Lato, Roboto, sans-serif;
}

@media (-webkit-min-device-pixel-ratio: 2),(min-resolution: 192dpi) {
    .mce-title, .mce-label, .mce-txt, .mce-text, .mce-path * {
        font-family: "Lato Retina", Lato, Roboto, sans-serif;
    }
}

.mce-window-head .mce-title {
    font-size: 17px;
    font-weight: 400;
}

.mce-container, .mce-container :not(.mce-menu-shortcut), .mce-widget, .mce-widget *, .mce-reset, .mce-menubar .mce-menubtn button span, .mce-menu-item .mce-ico, .mce-menu-item .mce-text, .mce-path-item, .mce-menubtn button {
    color: #222;
}

.mce-menubar .mce-caret {
    border-top-color: #222;
}

.mce-tooltip, .mce-tooltip * {
    color: #fff;
}
```
