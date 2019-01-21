# FTP Storage

Using Laravel's Filesystem Library, you may opt to use an external **FTP server** to serve as your application's default storage disk. This means that all upload, download, and stream requests are sent to and received from that server.

All you have to do is set the following [**environment variables**](../setup/environment-variables.md).

{% code-tabs %}
{% code-tabs-item title=".env" %}
```text
FILESYSTEM_DRIVER=ftp
FTP_HOST=ftp.yourserver.com
FTP_PORT=21
FTP_ROOT=path/to/folder
FTP_SSL=false
FTP_USERNAME=secret
FTP_PASSWORD=secret
```
{% endcode-tabs-item %}
{% endcode-tabs %}

