# VoiceBot - AI Voice Assistant

A modern Next.js web application with voice recognition and AI-powered responses using Google's Gemini AI.

## Features

- 🎤 **Voice Recognition**: Uses Web Speech API for real-time speech-to-text conversion
- 🤖 **AI Responses**: Powered by Google Gemini AI for intelligent conversations
- 🌙 **Dark Theme**: Professional black theme with blue accents
- 💬 **Chat Interface**: Real-time conversation display with timestamps
- 📱 **Responsive Design**: Works on desktop and mobile devices

## Setup Instructions

### 1. Install Dependencies

```bash
npm install
```

### 2. Configure Gemini API

1. Get your Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Copy `.env.local` and add your API key:

```env
GEMINI_API_KEY=your_actual_api_key_here
```

### 3. Run the Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

1. Click the microphone button to start listening
2. Speak your question or message
3. The app will convert your speech to text in real-time
4. AI will process your message and respond
5. View the conversation history in the chat interface

## Browser Support

- ✅ Chrome (Recommended)
- ✅ Edge
- ✅ Safari (macOS/iOS)
- ❌ Firefox (Limited Web Speech API support)

## Tech Stack

- **Framework**: Next.js 15 with App Router
- **Styling**: TailwindCSS
- **AI**: Google Gemini Pro
- **Speech**: Web Speech API
- **Language**: TypeScript

## File Structure

```
src/
├── app/
│   ├── api/gemini/       # Gemini AI API route
│   ├── globals.css       # Global styles
│   └── page.tsx          # Main page
├── components/
│   ├── VoiceBotCard.tsx  # Main chat interface
│   └── MicrophoneButton.tsx # Voice input button
└── types/
    └── speech.d.ts       # Web Speech API types
```
