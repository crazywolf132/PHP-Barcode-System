# PHP-Barcode-System
Very basic Retailer barcode system in PHP


### VERY SIMPLE TO USE!
Simply include the `barcoder.php` file in your project...

Then reference to `generateBarcode()` function. 
eg. 

```PHP
$result = generateBarcode('9918274');
echo $result;
```

We need to `echo` the `$result` variableas `generateBarcode` will return us some HTML code...
