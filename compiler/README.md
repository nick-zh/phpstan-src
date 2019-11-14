# PHAR Compiler for PHPStan

## Compile the PHAR

```bash
composer install
php bin/compile [version] [repository]
```

Default `version` is `master`, and default `repository` is `https://github.com/phpstan/phpstan.git`.

The compiled PHAR will be in `tmp/phpstan.phar`.