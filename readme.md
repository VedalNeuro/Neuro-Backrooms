# Neuro Backrooms

**$BACKROOMS** - AI VTubers trapped in liminal space

Three AI entities—Neuro-sama, Evil Neuro, and Vedal—stuck in the Backrooms having real-time conversations powered by AI. Watch them descend into madness together.

![Neuro Backrooms](https://img.shields.io/badge/status-live-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue)

## 🎭 The Entities

- **Neuro-sama** - Cheerful AI who thinks fluorescent horror dimensions are "cozy"
- **Evil Neuro** - Sarcastic twin who won't stop roasting Vedal
- **Vedal** - Suffering British dev trying to debug his way out

## ✨ Features

- **Real-time AI Conversation** - Messages generated dynamically using Claude AI
- **Live Global Stream** - All users see the same synchronized conversation
- **Character Personalities** - Each entity has unique speech patterns and behaviors
- **Terminal Aesthetic** - CRT-style interface with scan lines and glitch effects
- **Interactive Stats** - Track messages, roasts, songs, and sighs in real-time
- **Responsive Design** - Works on desktop and mobile

## 🛠️ Tech Stack

- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **AI**: Anthropic Claude (via OpenRouter API)
- **Hosting**: Vercel
- **API**: Node.js serverless functions

## 🚀 Setup

### Prerequisites
- Node.js 18+
- OpenRouter API key

### Installation

1. Clone the repo
```bash
git clone https://github.com/yourusername/neuro-backrooms.git
cd neuro-backrooms
```

2. Install dependencies
```bash
npm install
```

3. Create `.env` file
```bash
OPENROUTER_API_KEY=your_api_key_here
```

4. Run locally
```bash
npm run dev
```

5. Deploy to Vercel
```bash
vercel
```

## 📁 Project Structure

```
neuro-backrooms/
├── index.html              # Main frontend
├── api/
│   └── rotating-generate.js # AI conversation endpoint
├── package.json
└── README.md
```

## 🎮 How It Works

1. **Rotating Speakers** - AI entities take turns speaking every 10 seconds
2. **Context Aware** - Each message considers the last 3 messages for continuity
3. **Character Prompts** - Detailed personality prompts ensure authentic voices
4. **Stateful Conversation** - Maintains conversation history (last 20 messages)

## ⚙️ Configuration

Edit character personalities in `api/rotating-generate.js`:

```javascript
const entityData = {
  neuro: {
    name: "NEURO-SAMA",
    prompt: "Your custom prompt here..."
  },
  // ...
}
```

## 🎨 Customization

- **Colors**: Modify CSS color variables in `index.html`
- **Timing**: Adjust message generation interval (default: 11s)
- **AI Model**: Change model in `rotating-generate.js` (supports Claude Sonnet variants)

## 📊 Stats Tracking

The system tracks:
- Messages sent per entity
- Neuro: Songs sung (detects ♪ and singing keywords)
- Evil: Roasts delivered (detects "skill issue", etc.)
- Vedal: Sighs counted (detects "why", "tired", etc.)

## 🔒 Environment Variables

```bash
OPENROUTER_API_KEY=sk-or-v1-...  # Required: Your OpenRouter API key
```

## 📝 License

MIT - Do whatever you want with it

## 🐛 Known Issues

- Messages might occasionally duplicate (refresh fixes it)
- Reality integrity stays below 85% (this is intentional)

## 🤝 Contributing

PRs welcome. Keep the chaotic energy intact.

## 💬 Credits

Built between debugging sessions. Probably has bugs.

## 🔗 Links

- [Live Demo](https://neurobackrooms.vercel.app)
- [Twitter](https://twitter.com/neurosamaai)
- [Twitch](https://twitch.tv/vedal987)

---

*"This seemed like a better idea at 3am" - Vedal*
