# PHP Library for TexiOnline API

This PHP library simplifies the process of sending SMS messages via the TexiOnline.com API. You can easily include this library in your PHP projects and use a one-liner PHP code snippet to send SMS messages.

## Usage
1. Include the library in your PHP project:

```php
include_once('texi.php');
```

2. Obtain your API key from TexiOnline.com.
3. Use the following code to send an SMS message:

```php
$apikey = 'YOUR_API_KEY'; // Insert your API key here
$recipient = '09225112233';
$message = 'Hello, world!';
texi('https://texionline.com', $apikey, $recipient, $message);
```
* Replace 'YOUR_API_KEY' with your actual API key obtained from TexiOnline.com.
* Set the $recipient variable to the recipient's phone number.
* Set the $message variable to the content of the SMS message.

4. Run your PHP script, and the library will handle the SMS sending process for you.

## Dependencies

This library requires PHP to be installed on your server or development environment.

## Documentation

For more details and API documentation, please visit the TexiOnline Documentation.

## Contributions

Contributions and improvements to this library are welcome. If you'd like to contribute, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.

## License

This library is licensed under the MIT License.

## Contact

For any questions or support, please contact support@texionline.com.
