### Library to generate random strings using the PHP language.

#### Composer

```
$ composer require jfoza/php-random-string
```
#### Examples

```php
use JFoza\PhpRandomString\RandomStringHelper;

$basicString = RandomStringHelper::basicGenerate();
$alphaString = RandomStringHelper::alphaGenerate();
$alnumString = RandomStringHelper::alnumGenerate();
$strings = RandomStringHelper::stringsGenerate();
$numericString = RandomStringHelper::numericGenerate();
$noZeroString = RandomStringHelper::noZeroGenerate();
$md5String = RandomStringHelper::md5Generate();
$sha1String = RandomStringHelper::sha1Generate();

echo $numericString;
echo $alphaString;
echo $alnumString;
echo $strings;
echo $numericString;
echo $noZeroString;
echo $md5String;
echo $sha1String;

```

*Improvements and feedback are welcome ;)
