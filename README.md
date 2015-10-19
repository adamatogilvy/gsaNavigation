# gsaNavigation
The main navigation for GSA web services

1. Include a link to the gsaNavigation.css file in the <head> of the page. This file compiles all the styles from other sass files. 
2. Include the following scripts just before the closing </body> tag (jquery 1.11 or greater is a dependency and will also need to be included if not already):
		<script src="js/handlebars-v4.0.2.js" type="text/javascript"></script>
        <script src="js/navigation-json.js" type="text/javascript"></script>
		<script src="js/jquery.smartmenus.min.js" type="text/javascript" ></script>
		<script src="js/jquery.smartmenus.bootstrap.min.js" type="text/javascript" ></script>
		<script src="js/navigation.js" type="text/javascript" type="text/javascript" ></script>
3. Add the entire header.html code OUTSIDE of any wrapper containers. Usually works best just after the opening <body> tag.
		
