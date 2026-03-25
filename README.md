> ⚠️ This repo is a starting point, not a solution. 
> You will get stuck. That's the point. Google is your best friend.

# AI Chatbot UI

> A clean, fast chat interface connected to a real AI model with conversation memory.

## What You Will Learn
- How to integrate the OpenAI API into a React app
- How to manage conversation history and context
- How to build smooth chat UI interactions
- How to animate UI elements with Framer Motion

## Tech Stack
- React
- OpenAI API
- TailwindCSS
- Framer Motion
- Vercel (deployment)

## Getting Started

### Prerequisites
- Node.js 18+ installed
- An OpenAI API key — platform.openai.com

### Installation
```bash
git clone https://github.com/thanos.zip/ai-chatbot-ui
cd ai-chatbot-ui
npm install
cp .env.example .env
# Add your OpenAI API key to .env
npm run dev
```

## Project Structure
```
ai-chatbot-ui/
├── src/
│   ├── App.jsx                  # Main app component
│   ├── api/
│   │   └── openai.js           # OpenAI API calls here
│   ├── components/
│   │   ├── ChatWindow.jsx      # Message list display here
│   │   ├── Message.jsx         # Individual message bubble here
│   │   ├── InputBar.jsx        # Text input and send button here
│   │   └── TypingIndicator.jsx # Animated typing dots here
│   ├── hooks/
│   │   └── useChat.js          # Chat state and logic here
│   └── index.css
├── .env.example
├── package.json
└── README.md
```

## What To Build
- Input bar with send on enter and button click
- Display user and assistant messages in a clean chat layout
- Maintain full conversation history and send it with every API call
- Show a typing indicator while waiting for a response
- Auto scroll to the latest message
- Add a clear conversation button
- Animate messages appearing with Framer Motion
- Deploy on Vercel

## Stretch Goals
- Let users set a custom system prompt to change the bot's personality
- Add message timestamps
- Add code block formatting for technical responses

## Resources
- https://platform.openai.com/docs/api-reference/chat
- https://www.framer.com/motion/
- https://tailwindcss.com/docs

---
Built for [@thanos.zip](https://instagram.com/thanos.zip) followers.
