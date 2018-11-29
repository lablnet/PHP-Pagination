# PHP Pagination
Simple pagination library implements a paging interface on collections of things.

## Requirement

- PHP
- Composer

## install
run this command
``` composer require lablnet/pagination```

## usage

```php
<!-- Compiled and minified CSS -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">
<!-- Compiled and minified JavaScript -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>   
<?php 
use Lablnet\Pagination;
require '../vendor/autoload.php';
$pag1 = new Pagination(100,10,5,'/');
echo $pag1->pagination();
$pag2 = new Pagination(1000,10,25,'https://example.com/blogs/');
echo $pag2->pagination();
```    

