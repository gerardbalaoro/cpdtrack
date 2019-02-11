# Setting Up

## Server Requirements

The application is built on **Laravel Framework** and follows its minimum system requirements. For a full list, read on the [documentation of Laravel 5.4](https://laravel.com/docs/5.4#server-requirements). Third-party modules that are used in the application also require additional software to be installed, although most of it is bundled with PHP.

| Software | Minimum Version |
| :---: | :---: |
| PHP | 5.6.4 |
| MySQL / MariaDB | 5.7 /  10.1.31 |
| BCMath Extension | _\*Installed and Activated_ |
| GD Extension | _\*Installed and Activated_ |
| GMP Extension | _\*Installed and Activated_ |

{% hint style="info" %}
Laravel requires [**Composer**](https://getcomposer.org/) to be installed. Follow its documentation for setting it up on your machine
{% endhint %}

## Updating Dependencies

Extract the contents of the application package \(.zip file\) at the root of your web server or at any directory you desire. Fire up the command terminal and navigate it to where you extracted the package.

The application uses Composer to manage its dependencies. Run the following command to download and update all the required packages.

```bash
composer update
```

