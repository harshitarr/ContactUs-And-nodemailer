
# 📬 Contact Form with Email Functionality (Next.js + Nodemailer)

This is a **responsive contact form** built using **Next.js**, styled with **Tailwind CSS**, and integrated with **Nodemailer** to send form submissions directly to an admin email address.

## ✨ Features

- Beautiful UI with responsive design
- Real-time form validation
- Error handling
- Sends form data to admin via email
- Uses environment variables for secure credential handling

## 📸 Demo

![Demo Screenshot](./public/demo-screenshot.png) <!-- Replace with your screenshot path -->

## 🚀 Technologies Used

- Next.js (App Router)
- React
- Tailwind CSS
- Nodemailer
- Environment Variables (`.env.local`)

## 📁 Folder Structure

```bash
project-root/
├── app/
│ ├── components/
│ │ └── ContactUs.jsx
│ └── api/
│ └── sendMail/route.js
├── public/
│ └── assets/
│ └── contact-image3.svg
├── .env.local
└── README.md
```

 **Clone the repository**

```bash
git clone https://github.com/harshitarr/ContactUs-And-nodemailer.git
cd ContactUs-And-nodemailer
```

## Install dependencies
```bash
npm install
```

## Configure environment variables
- Create a .env.local file in the root and add:
```bash
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password
EMAIL_TO=receiver_email@gmail.com
```

## Run the development server
```bash
npm run dev
```

## 📧 Email Sending Logic
- Uses Nodemailer to send email via Gmail SMTP
- SMTP credentials are loaded from .env.local
- Sends form data (name, company, contact, etc.) in the email body

## 🛡️ Security Notes
- Never commit .env.local to GitHub.
- Use App Passwords for Gmail (2FA must be enabled).
- This project is for learning/demo purposes. In production, consider rate-limiting or CAPTCHA.


## 🤝 Contribution
- Feel free to fork this repository and contribute by submitting a pull request.

## Developed with 💙 by Harshita


