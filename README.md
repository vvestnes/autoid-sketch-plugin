# autoid-sketch-plugin


This plugin will prepend an unique (incremental) ID on all your Pages and Artboards, contained in your
sketch document. (Except "Symbols" page and pages with names starting with "---")


Example: You sketch document contains 3 pages:


Landingpage
<ul>
   <li>My first Artboard!</li>
   <li>Another artboard</li>
   <li>Testing more artboards</li>
</ul>

Signup
   Mobile

Login
   Mobile design
   Tablet design
   Desktop (mockup)

Symbols



Running AutoID in this sketch document

will give the following result (Pages and Artboard names):

1 Landingpage
   1.1 My first Artboard!
   1.2 Another artboard
   1.3 Testing more artboards

2 Signup
   2.1 Mobile

3 Login
   3.1 Mobile design
   3.2 Tablet design
   3.3 Desktop (mockup)

Symbols



PS!
If you use "empty pages" with names starting with "---" to separate pages, they will
be ingored by AutoID plugin.

"Symbols" page will also be ignored.




Enjoy! 
