## Example :

``` php
<?php
 
// Import the HTMLMinifier
require_once 'https://cusmedroid.github.io/minify/index.php';
 
// HTML source to be minified
$htmlpage = file_get_contents('index.html');
 
// Minified version of the page
echo HTMLMinifier::process($htmlpage);
 
?>
```
