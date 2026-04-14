# Yuva Cyber Cafe Contact Form

A simple contact form website that sends messages to your email.

## Setup EmailJS

1. Go to [EmailJS](https://www.emailjs.com/) and sign up for a free account.
2. Create a new email service (e.g., connect your Gmail account).
3. Create a new email template. In the template, use `{{message}}` for the message content, and set the recipient to `yuvacybercafer73@gmail.com`.
4. Note down your:
   - Public Key
   - Service ID
   - Template ID

5. Edit `index.html` and replace:
   - `YOUR_PUBLIC_KEY` with your Public Key
   - `YOUR_SERVICE_ID` with your Service ID
   - `YOUR_TEMPLATE_ID` with your Template ID

## Hosting

To host this live at yuvacybercafe.com:

1. Upload the `index.html` file to a static hosting service like:
   - Netlify (free): Drag and drop the file to netlify.com
   - Vercel (free): Use their CLI or web interface
   - GitHub Pages (free): Create a repo and enable Pages

2. Point your domain yuvacybercafe.com to the hosting provider's DNS settings.

## Local Testing

Open `index.html` in your browser to test the form. Note that EmailJS works from local files, but for production, host it.

## Security Note

EmailJS is client-side, so the email credentials are exposed in the browser. For a production site, consider using a backend service for better security.