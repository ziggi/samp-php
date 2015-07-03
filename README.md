# samp-php
PHP utilties for SA-MP 0.3.7

# Usage
```php
<?php
include "SampQueryAPI.php"; 
 
$query = new SampQueryAPI('127.0.0.1', '7777');
 
if ($query->isOnline()) {
  $aInformation = $query->getInfo();
  $aServerRules = $query->getRules();
  
  print_r($aInformation);
  print_r($aServerRules);
}
```
Full example script: https://gist.github.com/ziggi/d3a8f93783b7deea2895