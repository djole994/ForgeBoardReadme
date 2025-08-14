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





<!-- MASTER TOGGLE -->
<details>
  <summary><b>📸 Screenshots</b> — klikni za prikaz</summary>

  <br/>

  <!-- NESTED: AUTH SCREENS -->
  <details>
    <summary><b>🔐 Auth screens</b> — Login / Register / Forgot / Reset</summary>

    <br/>

    <!-- LOGIN -->
    <table>
      <thead>
        <tr>
          <th align="center">Login — Desktop</th>
          <th align="center">Login — Mobile</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td align="center">
            <a href="media/screenshots/auth/login-desktop.png">
              <img src="media/screenshots/auth/login-desktop.png" width="520" alt="Login — Desktop">
            </a>
          </td>
          <td align="center">
            <a href="media/screenshots/auth/login-mobile.png">
              <img src="media/screenshots/auth/login-mobile.png" width="240" alt="Login — Mobile">
            </a>
          </td>
        </tr>
      </tbody>
    </table>

    <br/>

    <!-- REGISTER -->
    <table>
      <thead>
        <tr>
          <th align="center">Register — Desktop</th>
          <th align="center">Register — Mobile</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td align="center">
            <a href="media/screenshots/auth/register-desktop.png">
              <img src="media/screenshots/auth/register-desktop.png" width="520" alt="Register — Desktop">
            </a>
          </td>
          <td align="center">
            <a href="media/screenshots/auth/register-mobile.png">
              <img src="media/screenshots/auth/register-mobile.png" width="240" alt="Register — Mobile">
            </a>
          </td>
        </tr>
      </tbody>
    </table>

    <br/>

    <!-- FORGOT / RESET (oba desktop) -->
    <table>
      <thead>
        <tr>
          <th align="center">Forgot password — Desktop</th>
          <th align="center">Reset password — Desktop</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td align="center">
            <a href="media/screenshots/auth/forgot-desktop.png">
              <img src="media/screenshots/auth/forgot-desktop.png" width="480" alt="Forgot password — Desktop">
            </a>
          </td>
          <td align="center">
            <a href="media/screenshots/auth/reset-desktop.png">
              <img src="media/screenshots/auth/reset-desktop.png" width="480" alt="Reset password — Desktop">
            </a>
          </td>
        </tr>
      </tbody>
    </table>

    <br/>

    <!-- EMAIL TOKEN (puna širina) -->
    <p align="center">
      <a href="media/screenshots/auth/reset-email.png">
        <img src="media/screenshots/auth/reset-email.png" width="520" alt="Reset email (token)">
      </a>
      <br/>
      <sub><b>Reset email</b> — token preview</sub>
    </p>

  </details>
  <!-- /NESTED: AUTH SCREENS -->

</details>
<!-- /MASTER TOGGLE -->
