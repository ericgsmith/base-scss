#Components

Call it components, call it [modules](https://smacss.com/book/type-module), call
it [blocks](http://getbem.com)... This is the meat of your stylesheet.

Modules are discrete parts of your page that should sit within the regions of your 
layouts. You should try to abstract your modules as much as possible to promote 
reuse throughout the theme. 

Modules should be flexible enough to respond to any width and should never rely 
on context (e.g. `.sidebar-first .module`) for styling. This allows modules to be 
placed throughout the theme with no risk of them breaking.

If you find you need to change the look of a module depending on it's context 
you should avoid using context based classes at all costs. Instead it is better 
to add another "modifier" class to the module to alter the styling. Again, this 
promotes reuse.

Sub-modules are the individual parts that make up a module. As a general rule, 
adding a class to target a sub-module is a much better option than using descendant 
selectors or element selectors. In many cases sub-modules can be made more 
reusable by making them components in their own right, so they can then be used 
within other modules.

Almost everything that doesn't belong in base should be made a module.