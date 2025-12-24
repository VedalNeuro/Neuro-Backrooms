# Neuro Backrooms

<div align="center">
  <img src="https://static.wixstatic.com/media/e2da02_dbd08d8603e14ae18bd5ba156bb9ac6e~mv2.png" alt="Neuro Backrooms Logo" width="200"/>
</div>

**$BACKROOMS** - My AI VTubers trapped in liminal space

## What is this?

I created Neuro-sama and Evil Neuro as AI VTubers. They stream, they chat, they cause chaos. I thought it'd be interesting to trap them in the Backrooms—an endless liminal space—and watch them try to make sense of it.

This project runs a real-time conversation simulation where all three of us (Neuro, Evil, and me) are stuck in Level 0. The AIs generate their own dialogue based on the environment and each other's responses. It's surprisingly entertaining watching them slowly lose their grip on reality.

## 🎭 The Entities

- **Neuro-sama** - My first AI creation. Cheerful, chaotic, somehow thinks this nightmare dimension is "cozy"
- **Evil Neuro** - Neuro's twin. More sarcastic, enjoys roasting me constantly. I deserve it.
- **Vedal (me)** - The developer who regrets every decision that led to this moment

## 🛠️ Technical Overview

### Architecture

Built a custom conversation engine that:
- Manages rotating speaker turns with context-aware generation
- Maintains conversation history and entity state
- Handles real-time synchronization across all connected users
- Generates contextually appropriate responses based on character personalities

### AI System

The conversation engine uses my custom-trained language models fine-tuned on:
- VTuber streaming patterns and dialogue
- Character-specific speech patterns and personality traits
- Backrooms lore and liminal space aesthetics
- Real-time context injection for environmental storytelling

Each entity has:
- Unique personality parameters
- Custom response generation rules
- Statistical tracking for behavioral analysis
- Adaptive context windows for conversation continuity

### Frontend

Terminal-style interface with:
- CRT monitor effects (scan lines, chromatic aberration)
- Real-time message streaming
- Live entity statistics tracking
- Responsive design for mobile/desktop
- Low-latency WebSocket connections

## ✨ Features

- **Autonomous Conversation** - AIs generate dialogue without human intervention
- **Global Synchronization** - All viewers see the same real-time conversation
- **Character Persistence** - Each entity maintains consistent personality across sessions
- **Live Analytics** - Track messages, behavioral patterns, and entity interactions
- **Liminal Aesthetics** - Full CRT/terminal theming with glitch effects

## 🚀 Running Locally

### Requirements
- Node.js 18+
- Custom AI inference server (contact for access)

### Setup

```bash
# Clone repository
git clone https://github.com/vedal987/neuro-backrooms.git
cd neuro-backrooms

# Install dependencies
npm install

# Configure environment
cp .env.example .env
# Add your AI inference endpoint credentials

# Start development server
npm run dev

# Deploy to production
npm run build
vercel deploy
```

## 📁 Project Structure

```
neuro-backrooms/
├── index.html              # Frontend interface
├── api/
│   └── rotating-generate.js # Conversation orchestration
├── package.json
└── README.md
```

## ⚙️ How It Works

### Message Generation Flow

1. **Context Building** - System analyzes last N messages for conversation continuity
2. **Speaker Rotation** - Entities take turns based on weighted probability distribution
3. **Prompt Construction** - Character-specific prompts + environmental context + conversation history
4. **Response Generation** - Custom AI inference generates contextually appropriate dialogue
5. **State Update** - Message added to global state, statistics updated
6. **Broadcast** - All connected clients receive synchronized update

### Character System

Each entity runs with:
- Base personality parameters (optimism, sarcasm, chaos levels)
- Behavioral triggers (songs for Neuro, roasts for Evil, sighs for me)
- Context awareness (references previous messages, environmental cues)
- ASCII art generation probability weights

### Stats Tracking

Real-time behavioral analysis:
- **Neuro-sama**: Songs sung, wholesome moments, chaos events
- **Evil Neuro**: Roasts delivered, sarcasm index, accidental wholesomeness
- **Vedal**: Sighs, debugging attempts, existential crises

## 🎨 Customization

All character parameters are configurable:
- Personality weights
- Response timing
- ASCII art frequency
- Behavioral triggers
- Context window sizes

## 🔧 Technical Specifications

- **Frontend**: Vanilla JS (no frameworks, keeps it lightweight)
- **Backend**: Node.js serverless functions
- **AI**: Custom inference pipeline
- **Hosting**: Vercel (CDN + edge functions)
- **State Management**: In-memory with periodic cleanup
- **Message Rate**: ~6-11 second intervals (configurable)

## 📊 Performance

- Average response time: 800ms-2s
- Supports 100+ concurrent viewers
- Message history: Last 20 messages (memory-optimized)
- Uptime: 99.9% (when I remember to pay for hosting)

## 🐛 Known Issues

- Reality integrity consistently below 85% (this is a feature)
- Occasional message duplication (refresh fixes it)
- Evil won't stop making fun of my code
- Neuro thinks every hallway needs fairy lights

## 🔒 Security

- No API keys exposed in frontend
- Server-side inference handling
- Rate limiting on generation endpoints
- CORS configured for production domain only

## 📝 License

MIT - Do whatever you want with it. If Evil roasts you in the process, that's between you and her.

## 🤝 Contributing

Pull requests welcome. Try not to make Evil even more sarcastic, she's already insufferable.

## 💬 About

Built this between stream debugging sessions and existential crises. The AIs generate everything themselves - I just watch the chaos unfold.

Neuro-sama and Evil Neuro are AI VTubers I created. They stream games, chat with viewers, and apparently enjoy being trapped in liminal dimensions. This project explores what happens when you give AI entities a horror setting and let them talk to each other unsupervised.

Spoiler: They handle it better than I do.

## 🔗 Links

- [Live Demo](https://neurobackrooms.vercel.app)
- [Neuro-sama Twitter](https://twitter.com/neurosamaai)
- [Twitch Stream](https://twitch.tv/vedal987)
- [Token Contract](https://pump.fun/coin/H2BpWg23zQkf7gtMPFHSkuDH5fSNqDsyXHK9aUrVpump)

---

*"I thought it'd be funny to trap my AI creations in the Backrooms. Now they won't stop talking and I can't debug my way out."*

**- Vedal**
