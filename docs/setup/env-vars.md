# Environment Variables

Laravel applications use `.env` file or an environment configuration to store and manage essential and usually unchanging settings such as database server credentials and mail provider. This elliminates the inconvenience of having to change the configuration file directly which may break future updates.

{% hint style="info" %}
**Read More:** [https://laravel.com/docs/5.4/configuration#environment-configuration](https://laravel.com/docs/5.4/configuration#environment-configuration)
{% endhint %}

Populate the `.env` file at the root of the application folder with your server's configuration. Below is a snippet of the default configuration. The variables are explained in the succeeding sections.

```text
APP_NAME=CPDTrack
APP_ENV=production
APP_DEBUG=false
APP_URL=http://localhost
```

## Application

| Variable | Default | Description |
| :--- | :--- | :--- |
| APP\_NAME | CPDTrack | Application name, contain inside quotation marks if exceeds two words |
| APP\_ENV | production | Environment setting |
| APP\_DEBUG | false | Enable debugging |
| APP\_URL | [http://localhost](http://localhost) | Base URL of your application |

{% hint style="warning" %}
For production, it is recommended that `APP_ENV` and `APP_DEBUG` be left as default as it may expose confidential information and compromise the application.
{% endhint %}

## Database

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

## Mail

The application uses emails to send notifications and therefore required a working mail server.

| Variable | Default |
| :--- | :--- |
| MAIL\_DRIVER | smtp |
| MAIL\_HOST | smtp.mailtrap.io |
| MAIL\_PORT | 2525 |
| MAIL\_USERNAME | _secret_ |
| MAIL\_PASSWORD | _secret_ |
| MAIL\_ENCRYPTION | tls |

