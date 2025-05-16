medical-store-chatbot/
├── src/
│   ├── app/
│   │   ├── api/
│   │   │   └── chat/
│   │   │       └── route.ts      # API endpoint for OpenRouter (Qwen)
│   │   ├── page.tsx              # Main chatbot UI page
│   │   └── layout.tsx            # Already exists in your project
│   ├── components/
│   │   └── ChatBox.tsx           # Chat UI component
│   └── utils/
│       └── openrouter.ts         # Logic for OpenRouter API calls
├── public/
│   └── logo.png (optional)
├── .env.local                    # For API keys (in .gitignore)
├── package.json
└── README.md