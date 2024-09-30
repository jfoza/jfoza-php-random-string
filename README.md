### Library to generate random strings using the PHP language.

#### Composer

add composer.json
```
"jfoza/php-random-string": "^1.0"
```
or execute
```
$ composer require jfoza/php-random-string
```
#### Examples

```php
use JFoza\PhpRandomString\RandomStringHelper;

$numericString = RandomStringHelper::numericGenerate();
$md5String = RandomStringHelper::md5Generate();

echo $numericString;
echo $md5String;

```

*Improvements and feedback are welcome ;)
