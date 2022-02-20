# Hello Composer
This is a Composer test package

## Requirements

- PHP version >= 5.6
- Composer

## Installation
Install the package using Composer.

```bash
composer require ingenius-hq/hello-composer
```

## Usage Example

```php
<?php

require_once __DIR__ . '/vendor/autoload.php';

// Include the class
use IngeniusHq\HelloComposer\Hello;

// Create an instance
$instance = new Hello();

echo $instance->say("Hello World");
```

## Credits

- [Omar Villafuerte](https://github.com/ovillafuerte94)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.