## On your index
``` php
<?php include='main-minify.php';?>
<!DOCTYPE html>
<html>
  <head>
    <title>Demo for minifier</title>
  </head>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
<?php include='end-minify.php';?>
```

## Example :

``` php
<?php
 
// Import the HTMLMinifier
require_once 'minify/index.php';
 
// HTML source to be minified
$htmlpage = file_get_contents('index.html');
 
// Minified version of the page
echo HTMLMinifier::process($htmlpage);
 
?>
```
