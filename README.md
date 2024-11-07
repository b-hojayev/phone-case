# PandaCase

## Description

Live version: https://phone-case-lemon.vercel.app

## Description

Create custom high-quality phone cases in seconds

## Prerequisites

- Node.js (or any other relevant technology)
- npm (or yarn)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/b-hojayev/phone-case.git
   cd phone-case
   ```
2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a .env file in the root directory of the project.

## Configuration

Add the following environment variables to your .env file:

# host API Key

NEXT_PUBLIC_SERVER_URL="localhost or your host_url"

# Authentication API Key

KINDE_CLIENT_ID="get from kinde.com"
KINDE_CLIENT_SECRET="get from kinde.com"
KINDE_ISSUER_URL="get from kinde.com"
KINDE_SITE_URL="localhost or your host_url"
KINDE_POST_LOGOUT_REDIRECT_URL="localhost or your host_url"
KINDE_POST_LOGIN_REDIRECT_URL="http://your_localhost_or_host_url/auth-callback"

# Admin Email

ADMIN_EMAIL="your_admin_email"

# Payment API Key

STRIPE_SECRET_KEY="get from stripe.com"

# File Uploader API Key

UPLOADTHING_SECRET="get from uploadthing.com"
UPLOADTHING_APP_ID="get from uploadthing.com"

# Database URL

DATABASE_URL="databse url, get from neon.tech"

STRIPE_WEBHOOK_SECRET="get from stripe.com"

# Gmail API Key for Sending Messages

RESEND_API_KEY="get from resend.com"

# Usage

After configuring the .env file, you can run the project using:

```bash
   npm run dev
```

# Contributing

If you would like to contribute to this project, please open an issue or submit a pull request.

# Contact

For any questions or suggestions, please contact:
gmail: frontenddev673@gmail.com.
tg: https://t.me/frontend_dev64
github: https://github.com/b-hojayev
