
## Install

add `light/yii2-xmlparser` to composer.json

```sh
$ composer install
```

or

```sh
composer update
```

## Usage

```
# file app/config/main.php
<?php

return [
    'components' => [
    'request' => [
        'parsers' => [
	        	'text/xml' => 'light\XmlParser',
	            'application/xml' => 'light\XmlParser',
	        ],
        ],
    ],
];

```

## Test

TBD
