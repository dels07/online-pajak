# Online Pajak

## How to install
<pre>
git clone
cd online-pajak
composer install
composer dump-autoload
</pre>

## Running test
<pre>
vendor/bin/phpunit
</pre>

## Structure
<pre>
src/
  Config.php
  TaxRelief.php (question 1)
  TaxScheme.php (question 2)
tests/
  TaxReliefTest.php (unit test for question 1)
  TaxSchemeTest.php (unit test for question 2)