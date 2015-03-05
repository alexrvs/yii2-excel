Import Excel
============
Import Excel

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist alexandervas/yii2-excel "*"
```

or add

```
"alexandervas/yii2-excel": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?php

	$phpexcel = new PhpExcel();
	$phpexcel->load($filename);	
	
 ?>```