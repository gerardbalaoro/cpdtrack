# reCAPTCHA

The application also supports **reCAPTCHA** verification on login and registration pages. To set it up, get your **SECRET KEY** and **SITE KEY** at the [reCAPTCHA Admin Console](https://www.google.com/recaptcha/admin). Next, simply append them at the `.env` file.

{% code-tabs %}
{% code-tabs-item title=".env" %}
```text
RECAPTCHA_SECRETKEY=secret
RECAPTCHA_SITEKEY=secret
```
{% endcode-tabs-item %}
{% endcode-tabs %}

In the [application settings](../../user-guide/administration/configuration.md), enable the reCAPTCH support then save.

