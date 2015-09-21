Faceify!@!!
===========
PHP Class to convert a photo of a person into a unique style JPEG image.

Example@!11
========
<?php
require_once 'Facify.php';
$image = 'sample.jpg';
$faceify = new Facify();
$faceify->setImage($image);

$faceify->draw();;
