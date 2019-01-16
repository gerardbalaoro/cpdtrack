# User Management

## User Roles

The application uses [**Role-Based Access Control \(RBAC\)**](https://en.wikipedia.org/wiki/Role-based_access_control), a system of controlling which **users have access to resources based on the role of the user**. Access rights are grouped by role name, and access to resources is restricted to users who have been authorized to assume the associated role [_\(Webopedia\)_](https://www.webopedia.com/TERM/R/RBAC.html).

<table>
  <thead>
    <tr>
      <th style="text-align:left">Privileges</th>
      <th style="text-align:center">Member</th>
      <th style="text-align:center">Moderator</th>
      <th style="text-align:center">Administrator</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <ul>
          <li>Track CPD Credits</li>
          <li>Register Providers</li>
          <li>Create Programs</li>
          <li>Find Programs</li>
        </ul>
      </td>
      <td style="text-align:center">✔️</td>
      <td style="text-align:center">✔️</td>
      <td style="text-align:center">✔️</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <ul>
          <li>Accredit Programs</li>
          <li>Verify Providers and Users</li>
        </ul>
      </td>
      <td style="text-align:center">❌</td>
      <td style="text-align:center">✔️</td>
      <td style="text-align:center">✔️</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <ul>
          <li>Configure Application</li>
          <li>Create / Deactivate / Suspend User Accounts</li>
          <li>Reset User Passwords</li>
          <li>Suspend Providers</li>
        </ul>
      </td>
      <td style="text-align:center">❌</td>
      <td style="text-align:center">❌</td>
      <td style="text-align:center">✔️</td>
    </tr>
  </tbody>
</table>## Verification and Suspension



