<h1 align="center">abbasghasemi/country</h1>

<p align="center">
    <strong>Enum countries list</strong>
</p>

## Example

```php
<?php
include 'vendor/autoload.php';

use AG\Country;

echo Country::IRAN->getName() . '<br>'; // Iran
echo Country::IRAN->value . '<br>'; // ir
echo Country::IRAN->getUtcOffsetInSeconds() . '<br>'; // 12600 (+03:30)
echo Country::IRAN->getTimezone() . '<br>'; // Asia/Tehran
echo Country::IRAN->getFlagUrl() . '<br>'; // https://flagcdn.com/ir.svg


```