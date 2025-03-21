# Stock AI Chat Application

A Next.js chat application with AI models integration through OpenRouter API. This application allows users to chat with various AI models and save their conversation history.

## Features

- Multi-model support via OpenRouter API
- User authentication with Supabase
- Chat history persistence
- Modern UI with Tailwind and Shadcn/UI
- Message actions (copy, like, dislike, voice, regenerate)

## Tech Stack

- Next.js 15
- React 19
- TypeScript
- Tailwind CSS
- Supabase for auth and database
- OpenRouter API integration

## Setup Instructions

Check the documentation in OAUTH-SETUP.md for setting up authentication providers.

```bash
# Install dependencies
npm install

# Run development server
npm run dev
```

## Environment Variables

Create a `.env.local` file with the following variables:

```
# Supabase
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key

# OpenRouter
OPENROUTER_API_KEY=your_openrouter_api_key
```