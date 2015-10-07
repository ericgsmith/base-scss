#Base

Base rules as defined by [SMACCS](https://smacss.com/book/type-base). Contains only
base HTML styles with no classes.

You will probably want some kind of reset here. Options include 
[normalize.css](https://necolas.github.io/normalize.css/) or a traditional 
[reset](https://github.com/richclark/HTML5resetCSS).

##_00_base.scss

Import file. Contains ONLY imports to the other base files.

##_global.scss

Contains any universal selectors (e.g. *).

##_document.scss

Contains document level element styles (e.g html, body).

##_forms.scss

Contains form element styles (e.g. input, textarea).

##_lists.scss

Contains list element styles (e.g. ul, li, dd).

##_media.scss

Contains media element styles (e.g. img, video, audio).

##_tables.sccs

Contains table element styles (e.g. table, tr, td).

##_typography.scss

Contains typographic element styles (e.g. h1, p, strong, em).