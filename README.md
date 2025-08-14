# ForgeBoard — Agile Board & Issue Tracker

> **Private repo:** this repository contains documentation, screenshots and demo materials only. The source code is not public yet.

## Current Status (Auth milestone)
- ✅ API endpoints: **/auth/register**, **/auth/login**, **/auth/forgot-password**, **/auth/reset-password**
- ✅ JWT issuance
- ✅ SMTP wired for password reset (email token, no password)
- ✅ React (.tsx) UI: Login / Register / Forgot / Reset
- ✅ Domain `Users` table mapped to Identity (1:1)
- 🧩 On sign-up: assign **Guest** role (no access until elevated)
- 🧩 Refresh tokens (hashed) + rotation & reuse detection





<h3>📸 Auth — Screens</h3>

<table>
  <thead>
    <tr>
      <th align="center">Desktop</th>
      <th align="center">Mobile</th>
    </tr>
  </thead>

  <tbody>
    <!-- LOGIN -->
    <tr>
      <td align="center">
        <a href="media/screenshots/auth/login-desktop.png">
          <img src="media/screenshots/auth/login-desktop.png" width="520" alt="Login — Desktop" />
        </a>
        <br/><sub><b>Login</b> — Desktop</sub>
      </td>
      <td align="center">
        <a href="media/screenshots/auth/login-mobile.png">
          <img src="media/screenshots/auth/login-mobile.png" width="240" alt="Login — Mobile" />
        </a>
        <br/><sub><b>Login</b> — Mobile</sub>
      </td>
    </tr>


    <tr>
      <td align="center">
        <a href="media/screenshots/auth/register-desktop.png">
          <img src="media/screenshots/auth/register-desktop.png" width="520" alt="Register — Desktop" />
        </a>
        <br/><sub><b>Register</b> — Desktop</sub>
      </td>
      <td align="center">
        <a href="media/screenshots/auth/register-mobile.png">
          <img src="media/screenshots/auth/register-mobile.png" width="240" alt="Register — Mobile" />
        </a>
        <br/><sub><b>Register</b> — Mobile</sub>
      </td>
    </tr>

    <!-- FORGOT / RESET (oba su desktop, rasporedjena lijevo/desno) -->
    <tr>
      <td align="center">
        <a href="media/screenshots/auth/forgot-desktop.png">
          <img src="media/screenshots/auth/forgot-desktop.png" width="520" alt="Forgot password — Desktop" />
        </a>
        <br/><sub><b>Forgot password</b> — Desktop</sub>
      </td>
      <td align="center">
        <a href="media/screenshots/auth/reset-desktop.png">
          <img src="media/screenshots/auth/reset-desktop.png" width="240" alt="Reset password — Desktop" />
        </a>
        <br/><sub><b>Reset password</b> — Desktop</sub>
      </td>
    </tr>

    <!-- EMAIL TOKEN (puna širina) -->
    <tr>
      <td align="center" colspan="2">
        <a href="media/screenshots/auth/reset-email.png">
          <img src="media/screenshots/auth/reset-email.png" width="520" alt="Reset email (token)" />
        </a>
        <br/><sub><b>Reset email</b> — token preview</sub>
      </td>
    </tr>
  </tbody>
</table>

