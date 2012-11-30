rating
======

jquery rating simple &amp; easy

1. Include necessary JS and CSS files

        
            <script type="text/javascript" src="rating.js"></script>
            <link rel="stylesheet" type="text/css" href="rating.css" />
        
    

2. Create a text box element (the class "rating10" contain a num "10", this will display 10 starts)

        
            <input type="text" class="rating rating10" />
        
    

3. Fire plugin using jQuery selector

        
           $(function ()
            {
                $('.rating').rating();
            });
        
    

4. When form submit, You can access these values in the server-side script using the $_POST (PHP), Request.Form (Asp or Asp.net).

5. view the demo
http://www.chukeer.com/rating/example.html