# Getting Started

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

## Configuration

Populate the **`.env`**  file at the root of the application folder with your server's configuration. Below is a snippet of the default configuration. The variables are explained in the succeeding sections.

```text
APP_NAME=CPDTrack
APP_ENV=production
APP_DEBUG=false
APP_URL=http://localhost
```

### Environment

| Variable | Default | Description |
| :--- | :--- | :--- |
| APP\_NAME | CPDTrack | Application name, contain inside quotation marks if exceeds two words |
| APP\_ENV | production | Environment setting |
| APP\_DEBUG | false | Enable debugging |
| APP\_URL | http://localhost | Base URL of your application |

{% hint style="warning" %}
For production, it is recommended that**`APP_ENV`** and **`APP_DEBUG`** be left as default as it may expose confidential information and compromise the application.
{% endhint %}

### Database

Consult with your database administrator for the following credentials.

| Variable | Default | Description |
| :--- | :--- | :--- |
| DB\_DATABASE | cpdtrack | Database name |
| DB\_USERNAME | root | Database username |
| DB\_PASSWORD |  | Database password |
| DB\_PORT | 3306 | Database server port |

{% hint style="warning" %}
The application's database structure is created with MySQL and therefore uses features that are native to MySQL and MariaDB alone.
{% endhint %}

### Mail Server

The application uses emails to send notifications and therefore required a working mail server.

| Variable | Default |
| :--- | :--- |
| MAIL\_DRIVER | smtp |
| MAIL\_HOST | smtp.mailtrap.io |
| MAIL\_PORT | 2525 |
| MAIL\_USERNAME |  |
| MAIL\_PASSWORD |  |
| MAIL\_ENCRYPTION | tls |

## Installation

## Upgrading



