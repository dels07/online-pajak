# Online Pajak Coding Challenge
A program to calculate Simple Personal Income Tax in Indonesia based on taxpayer's annual income and tax reliefs.
## How to install
<pre>
git clone
cd online-pajak
composer install
composer dump-autoload
</pre>

## How to run (on terminal)
<pre>
cd online-pajak
php src/cli.php
</pre>

## Running test
<pre>
cd online-pajak
vendor/bin/phpunit
</pre>

## Structure
<pre>
src/
  cli.php (main program)
  Config.php (configuration)
  TaxRelief.php (question 1)
  TaxScheme.php (question 2)
tests/
  TaxReliefTest.php (unit test for question 1)
  TaxSchemeTest.php (unit test for question 2)
</pre>