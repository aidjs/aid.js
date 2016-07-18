# Aid Js
Aid Js is a javascript framework/library which aids/helps developers make incredible javascript single/multi page applications with high performance. Aid JS apps also ensures code maintainability as well as reusability.

#### Why Aid js? 

	- Easy to learn as this is none other than javascript but just using it in an described way
	- Follows more or less the same MVC flow of server side language like PHP,.net, JAVA.
	- Automatic routing without any extra routing codes which makes development faster 
	- Provides easy templating features and gives high performance in generating templates 
	- Uses the objected oriented programming concept in the best way one can do in javascript
	- Classes, Mixins and Modules enhances code reusabiliy as well as maintainability
	- No dependencies, its core javascript and so works without/with any js libraries


## Framework/Library ?
Well, you can use aid as a framework also you can use it as a library. But using it as a framework will get you more feature than as a library
#### Framework
When aid is used as a framework it will act obviously as a MVC framework with the same MVC flow of server side language like PHP,.net, JAVA.
Aid has controllers(C) and views(V) explicitly and model(M) implicitly as models are always an ajax call to a server side language 
##### Main Concepts of Aid - framework

	- Routing
	- Controllers
	- Templating/Views
	- Collections
	- Classes
	- Mixins
	- Inheritance
	- Modules


#### Library
Aid can be used as a library mainly if one needs just a javascript templating engine
An example of using aid as library
```html		
	<!-- The div where view is to be placed -->
	<div id="view"></div>
	<!-- Including aid js file -->
	<script type="text/javascript" src="aid.js">
	<script type="text/javascript">
	   // creating the aid library
	   var app = $_.library();
	   // Calling templating function
	   // Params : Template url,Data object,callback function
	   app.makeTemplate( 'templates/home', {
	       title            : 'Aid JS',
	       highlights 	: ['MVC','Templating','oops Concept'], 
	       built_on  	: 'js', 
	       console_msg      : 'Templating concept understood!',
	       one 		: 1,
	       two 		: 2
	   }, function(html) {
	       document.getElementById('view').innerHTML = html;
	   });
	</script>
```
