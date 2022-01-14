# Symfony enum use case
Provide a use case for Symfony 6.0 PHP 8.1 enum

# Versions:
Symfony 6.0
PHP 8.1

# Install guide
1. git clone https://github.com/bastien70/symfony-enum-use-case.git
2. cd symfony-enum-use-case
3. composer install

# Use case description
We have a Product entity which contains a title and a status.

The status is an Enum of ProductState type.

The ProductState contains 3 cases:

```php
    case IN_STOCK = 'En stock';
    case OUT_OF_STOCK = 'Stock épuisé';
    case IN_RESTOCK = 'En réapprovisionnement';
```

Only the first two cases should be able to be chosen when creating or modifying a product
