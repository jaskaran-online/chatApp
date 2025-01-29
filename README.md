# Modern Chat Application

A real-time chat application built with HTML, Tailwind CSS, and JavaScript. This application allows users to register, login, and engage in one-on-one conversations with other users.

## Features

- User Authentication (Register/Login)
- User Role Management
- Real-time Chat
- Image Attachments (up to 5 images)
- Message History
- Responsive Design
- User Status
- User List

## Tech Stack

- HTML5
- Tailwind CSS
- JavaScript (Vanilla)
- REST API Integration

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   pnpm install
   ```
3. Build Tailwind CSS:
   ```bash
   pnpm run dev
   ```

## Project Structure

```
chatApp/
├── src/              # Source files
│   ├── register.html # Registration page
│   ├── index.html    # Login page
│   ├── dashboard.html# User list/dashboard
│   ├── chat.html     # Chat interface
│   └── input.css     # Tailwind input file
├── dist/             # Compiled CSS
├── package.json      # Project dependencies
└── tailwind.config.js# Tailwind configuration
```

## API Integration

The application integrates with the following API endpoints:

- User Registration
- User Login
- User List
- Chat Creation
- Message Sending/Receiving

## Deployment

This project is ready to be deployed on Vercel. Follow these steps:

1. Push the code to a GitHub repository
2. Connect your Vercel account to GitHub
3. Import the repository in Vercel
4. Deploy!

## Development

To start development:

1. Run Tailwind build process:
   ```bash
   pnpm run dev
   ```
2. Use a local server to serve the files:
   ```bash
   npx serve src
   ```

## License

MIT License
