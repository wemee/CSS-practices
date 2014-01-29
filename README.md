CSS-practices
=============

CSS+HTML5

## float_cleaner
#### Usage
    <!-- link to float_cleaner.css in your header -->
    <link rel="stylesheet" type="text/css" href="float_cleaner.css">
    
    <!-- warp you float elements in a class named "cleaner" -->
    <div class="cleaner">
	    ...
    </div>

### Example
    <!DOCTYPE html>
    <html>
    <header>
	    <link rel="stylesheet" type="text/css" href="float_cleaner.css">
    </header>
    <body>
    
    <div class="cleaner">
	    <div class="floater">
		    Float Left|
	    </div>
	    <div class="floater">
		    Float Right
	    </div>
    </div>
    
    <div>
	    None-Float
    </div>
    </body>
    </html>