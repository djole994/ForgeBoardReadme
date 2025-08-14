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





## 📸 Screenshots (Auth)

> Demo podaci, klikni na sliku za full-size.

**Login**
[<img src="media/screenshots/auth/login-desktop.png" width="520" alt="Login — Desktop" />](media/screenshots/auth/login-desktop.png)
[<img src="media/screenshots/auth/login-mobile.png"  width="220" alt="Login — Mobile"  />](media/screenshots/auth/login-mobile.png)

**Register**
[<img src="media/screenshots/auth/register-desktop.png" width="520" alt="Register — Desktop" />](media/screenshots/auth/register-desktop.png)
[<img src="media/screenshots/auth/register-mobile.png"  width="220" alt="Register — Mobile"  />](media/screenshots/auth/register-mobile.png)

**Forgot / Reset**
[<img src="media/screenshots/auth/forgot-desktop.png" width="520" alt="Forgot password — Desktop" />](media/screenshots/auth/forgot-desktop.png)
[<img src="media/screenshots/auth/reset-desktop.png"  width="520" alt="Reset password — Desktop"  />](media/screenshots/auth/reset-desktop.png)

**Reset email (token)**
[<img src="media/screenshots/auth/reset-email.png" width="520" alt="Reset email with token" />](media/screenshots/auth/reset-email.png)
