# Rector-Rules-for-Laravel
Rector Rules for Laravel (rector.php file)

- composer require rector/rector --dev
- composer require --dev driftingly/rector-laravel
- create `rector.php` file in project root

## How to run in a Laravel project (along with Laravel Pint code style fixer)

```composer run format```

It refers to `composer.json`:

    ```
     "scripts": {
        ...
        "format": [
                "vendor/bin/rector",
                "vendor/bin/pint"
        ],
        ...
    }
    ```

