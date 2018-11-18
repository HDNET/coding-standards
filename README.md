# coding-standards
HDNET Coding Standars für PHP

## Installation

Repository zu composer.json hinzufügen
```
"repositories": [
    { "type": "github", "url": "https://github.com/HDNET/coding-standards" }
]
```

```sh
  composer require --dev squizlabs/php_codesniffer ^3.0
  composer require --dev escapestudios/symfony2-coding-standard ^3.4
  composer require --dev hdnet/coding-standards 3.x-dev
```

Im Projekt:
pre-commit einrichten: http://pre-commit.com/#usage
```sh
  pre-commit install
```
### Team Black
Datei .phpcs.xml anlegen für neue Projekte
```xml
<?xml version="1.0" encoding="UTF-8" ?>
<ruleset name="Example">
  <config name="installed_paths" value="/app/vendor/escapestudios/symfony2-coding-standard/,/app/vendor/hdnet/coding-standards" />
  <rule ref="HDNETBlack"/>
</ruleset>
```
