
## About
This package contains ruleset for PHP Code sniffer which used by Internal IT in Dotykacka. 


| Supported version |  Ruleset filename  |
|-------------------|--------------------|
| PHP 7.4+          | ruleset.xml        |
| PHP 7.3           | ruleset.73.xml     |

## Usage

Replace <src> with your source code destination
 
```shell script
php vendor/bin/phpcs app --standard=vendor/dotykacka/code-style/ruleset.xml <src>
```

For code sniffer autofixation run 
```shell script
php vendor/bin/phpcbf app --standard=vendor/dotykacka/code-style/ruleset.xml <src>
```
(replace phpcs with phpcbf)

## Advanced usage

* For better usage insert commands in `composer scripts` section in your project composer.json. 
* Add `--cache <path>/<to>/<cache>/<file>` to improve code sniffer speed

