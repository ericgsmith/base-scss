#Util

Collection of variables and any generic mixins or functions.

Using variables makes it much easier to ensure consistency throughout your 
stylesheets for values such as colors and numeric values.

When creating variables, consider the following rules

- the value is repeated at least twice;
- the value is likely to be updated at least once;
- all occurrences of the value are tied to the variable (i.e. not by coincidence).

Sass variables are `$hyphen-separated` NOT `$camelCase` or `$underscore_separated`.

Constants (not a real thing in Sass) can be represented as `$UPPERCASE_UNDERSCORE_SEPARATED`;

Sass variables should be documented using [SassDoc](http://sassdoc.com/).

###_breakpoints.scss

Contains your breakpoint definitions.

Breakpoints should not be named after devices but something more general.

###_colours.scss

Contains your colour values or maps.

###_fonts.scss

Contains your font related variables. 

This can include such items as:
- font sizing / line-height values or maps
- font weights
- font families

###_grid.scss

Contains any grid related variables. If using a system such as susy, place your
susy variables here.

###_spacings.scss

Contains any spacing related variables.

This can include such items as:
- default margin & padding
- high level layout separation margin
- horizontal or vertical spacing values

###_z-index.scss

Contains the z-index map and mixin.
