# Discord Clone with AI Chatbot

A modern Discord clone built with Next.js 13, featuring real-time messaging, video calls, and an integrated AI chatbot powered by Google's Gemini API.

## Features

- Real-time messaging using Socket.io
- Video and audio calls using LiveKit
- File uploads using UploadThing
- Authentication using Clerk
- AI Chatbot integration using Gemini API
- Modern UI with dark/light mode
- Responsive design

## Tech Stack

- Next.js 13
- TypeScript
- Tailwind CSS
- Prisma
- MySQL
- Socket.io
- LiveKit
- Clerk Authentication
- Gemini API

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up your environment variables:
   - Copy `.env.example` to `.env`
   - Fill in your API keys and credentials

4. Set up the database:
   ```bash
   npx prisma generate
   npx prisma db push
   ```

5. Run the development server:
   ```bash
   npm run dev
   ```

## Environment Variables

Create a `.env` file with the following variables:

```env
# Database
DATABASE_URL="your-database-url"

# Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your-clerk-publishable-key"
CLERK_SECRET_KEY="your-clerk-secret-key"

# File Uploads
UPLOADTHING_SECRET="your-uploadthing-secret"
UPLOADTHING_APP_ID="your-uploadthing-app-id"

# Video/Audio
LIVEKIT_API_KEY="your-livekit-api-key"
LIVEKIT_API_SECRET="your-livekit-api-secret"

# Site URL
NEXT_PUBLIC_SITE_URL="http://localhost:3000"

# AI Chatbot
GEMINI_API_KEY="your-gemini-api-key"
```

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License. 