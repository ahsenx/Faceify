Faceify!!!111
===========
PHP Class to convert a photo of a person into a unique style JPEG image.

Example!!!!
========
<?php
require_once 'Facify.php';
$image = 'sample.jpg';
$faceify = new Facify();
$faceify->setImage($image);

$faceify->draw();
