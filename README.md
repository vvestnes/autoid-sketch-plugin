# autoid-sketch-plugin


This plugin will rename all pages in your document with an incremental ID.

e.g your pages:

Landingpage
Signup
Login
Desktop


*** Then run AutoID plugin ***

Result:

1 Landingpage
2 Signup
3 Login
4 Desktop




If you use empty pages with names starting with "---", they will
be handled as separators and not included by the AutoID plugin.

"Symbols" page will NOT be given any ID.



All Artboards will also be renamed with a prepended UniqueID.
Each Artboard will get Page id + sequance number as id, for
example 1.1, 1.2, 1.3 etc...

If Landingpage has 3 Artboards, by example "Mobile", "Tablet", "Desktop",
Their new names will be 

1 Landingpage
   1.1 Mobile
   1.2 Tablet
   1.3 Desktop

2 Signup
   2.1 Mobile
   2.2 Tablet
   2.3 Desktop

etc...

Enjoy! 
