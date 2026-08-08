# System Architecture — LingoTutor AI

## 🏗️ Technical Stack
- **Frontend Framework:** React 19 / HTML5 Single Page PWA Application
- **Styling & UI Components:** Modern Tailwind CSS / Mobile-First Component Library (Dark & Light Theme Support, Safe Area Insets)
- **Voice Stack:** ElevenLabs WebRTC / WebSocket Conversational AI Client & MediaRecorder Audio Synthesizer
- **AI Intelligence Stack:** Google Gemini 2.5 Flash REST API with JSON Schema Enforcement
- **State Management & Persistence:** Encrypted IndexedDB & LocalStorage Engine
- **Security:** Web Crypto API SHA-256 Passcode Gate & XOR Stream Cipher for API Key Storage

## 📱 Navigation Architecture
```
LingoTutor AI
├── Password Authentication Gate (SHA-256)
├── Navigation Bottom Bar
│   ├── 🏠 Home (Daily Plan, Continue Learning, Streak Tracker, Quick Tutor Call)
│   ├── 📚 Learn (CEFR Curriculum: Units, Lessons, Grammar Reference, Culture)
│   ├── 🎙️ Talk (ElevenLabs AI Voice Tutor, Roleplay Scenarios, Call Transcripts)
│   ├── 🔄 Review (SM-2 Spaced Repetition Vocabulary Bank, Phrasebook, Mistake Notebook)
│   └── 👤 Profile (Language Settings, CEFR Placement, Tutor Personality, Security)
```
