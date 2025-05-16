.i want to create a chatbot for medical store.assume that i am a begineer.i want to create it using next js and i want to use open router and in that i want to use qwen 3.0 model.


medical-chatbot/
├── public/
│   └── logo.png (optional)
├── pages/
│   ├── api/
│   │   └── chat.js        # Backend route to talk to OpenRouter (Qwen)
│   └── index.js           # Main Chatbot UI page
├── components/
│   └── ChatBox.js         # Chat UI component
├── utils/
│   └── openrouter.js      # Logic for making requests to OpenRouter
├── .env.local             # For API key (never upload to GitHub)
├── package.json
└── README.md
