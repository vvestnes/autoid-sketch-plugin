# autoid-sketch-plugin


This plugin will prepend an incremental ID on all your Pages and Artboards.

<img src="https://user-images.githubusercontent.com/256259/28485065-0aface62-6e77-11e7-9c87-557e3e9dd22e.jpg" />


Example: You sketch document contains 3 pages:

Landingpage
<ul>
   <li>My first Artboard!</li>
   <li>Another artboard</li>
   <li>Testing more artboards</li>
</ul>

Signup
<ul>
   <li>Mobile</li>
</ul>

Login
<ul>
   <li>Mobile design</li>
   <li>Tablet design</li>
   <li>Desktop (mockup)</li>
</ul>

Symbols



Running AutoID in this sketch document

will give the following result (Pages and Artboard names):

1 Landingpage
<ul>
   <li>1.1 My first Artboard!</li>
   <li>1.2 Another artboard</li>
   <li>1.3 Testing more artboards</li>
</ul>

2 Signup
<ul>
   <li>2.1 Mobile</li>
</ul>

3 Login
<ul>
   <li>3.1 Mobile design</li>
   <li>3.2 Tablet design</li>
   <li>3.3 Desktop (mockup)</li>
</ul>

Symbols


<hr/>


Version:

1.2 Applies ids X to all pages, and X.Y on all artboards. where X = incremental page number, and Y = incremental artboard number. 

1.1 Make AutoID only give id to pages which contains artboards (pages without artboards will be left unchanged)

1.0 First release

Enjoy! 
