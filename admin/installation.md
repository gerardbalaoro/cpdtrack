# Installation

## Interactive Installer

Once the environment configurations are set, fire up the command terminal at the root of the application folder and run the command below.php artisan setup install

```bash
php artisan setup install
```

This will run all the necessary scripts to setup the application. Upon completion, it will create an administrator account and provide a set of credentials.

{% hint style="warning" %}
It is important to modify the default credentials created by the installation script.
{% endhint %}

## Upgrading

When upgrading to a later version, simply overwrite the application files and run the command below.

```bash
php artisan setup update
```

