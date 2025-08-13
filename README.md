ForgeBoard – Auth Milestone (Status & Plan)
What’s implemented so far
✅ API (ASP.NET Core Web API): POST /auth/register, POST /auth/login, POST /auth/forgot-password, POST /auth/reset-password.

✅ JWT issuance for login/registration.

✅ SMTP wired for password reset (email is checked; if it exists, send reset token — not the password).

✅ Custom Users table (separate from Identity) – registration also creates a row here.

✅ Frontend (React, .tsx): UI for all auth flows (Login, Register, Forgot, Reset) — screenshots to be added.
