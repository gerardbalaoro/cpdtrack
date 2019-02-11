# Installation

## Command Line Installer

Once the environment configurations are set, fire up the command terminal at the root of the application folder and run the command.

```bash
php artisan app:install [options]
```

![](../.gitbook/assets/install.gif)

| Options | Description |
| :--- | :--- |


| `-d`, `--dummy` | Generate dummy data |
| :--- | :--- |


| `-c`, `--clean` | Generate dummy data _\(will destroy all exisiting data\)_ |
| :--- | :--- |


| `-r`, `--refresh` | Refresh migrations _\(will destroy all exisiting data\)_ |
| :--- | :--- |


<table>
  <thead>
    <tr>
      <th style="text-align:left"><code>-u</code>, <code>--username</code>
      </th>
      <th style="text-align:left">
        <p>Default Administrator Account Username.</p>
        <p><code>php artisan app:install --username=superadmin</code>
        </p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table><table>
  <thead>
    <tr>
      <th style="text-align:left"><code>-p</code>, <code>--password</code>
      </th>
      <th style="text-align:left">
        <p>Default Administrator Account Password.</p>
        <p><code>php artisan app:install --password=PASSW0RD!!</code>
        </p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>{% hint style="warning" %}
It is important to modify the default credentials created by the installation script.
{% endhint %}

## Upgrading

When upgrading to a later version, simply overwrite the application files and run the command below.

```bash
php artisan app:update
```

