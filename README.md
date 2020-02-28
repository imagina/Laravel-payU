# Laravel-payU v0.1.0

A simple autoload for PayU SDK PHP in laravel.

### Installation

Add follow lines in the composer.json file

```
  "repositories": [
    ...
    {
      "type": "git",
      "url": "https://github.com/imagina/Laravel-payU.git"
    }
    ...
  ],
```

Install via composer

```ssh
 composer require imagina/laravel-payu
 ```
 
### Usage

```php
<?php
  
  namespace App\Http\Controllers;
  
  use App\Http\Controllers\Controller;
  use PayUReports;
  
  class myController extends Controller
  {
    public function ping () {
      PayUReports::doPing();
    }
  }

```
