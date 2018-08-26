# Fonts
## Adding fonts to WP
### Using **CSS3 @font-face**
1. Find the font (freefonts) and download 
2. If necessary generate web fonts (woff) from downloaded ttf file using online facility like **FontSquirrel**
3. Upload woff and ttf files to **/fonts** folder of selected theme
4. Add @font-face css to relevant stylesheet, eg.
```
@font-face {
    font-family: 'action_isregular';
    src: url('https://www.koek-e-loer.co.za/wp-content/themes/windcake/fonts/actionis-webfont.woff2') format('woff2'),
         url('https://www.koek-e-loer.co.za/wp-content/themes/windcake/fonts/actionis.ttf') format('woff2'),
         url('https://www.koek-e-loer.co.za/wp-content/themes/windcake/fonts/actionis-webfont.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}

```
5. Add to font-family where required, eg.
```
h1,h2,h3,h4,h5,h6{
	font-family: 'action_isregular', 'Sevillana', cursive;
	color:#00ada7;
}
```