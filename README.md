# php-library

This is a simple PHP library for TexiOnline. We can include it to any PHP project and use the one-liner PHP code provided below to send SMS.

## Usage

```php
<?php
include_once('texi.php');

$apikey = ''; // Insert your API key here
$recipient = '09225112233';
$message = 'Hello, world!';
texi('http://texionline.com', $apikey, $recipient, $message);

?>
```
