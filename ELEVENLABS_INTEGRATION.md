# ElevenLabs Integration Specifications — LingoTutor AI

## 🎙️ Real-Time Conversational AI Specs

### 1. Connection Lifecycle
- **Initialization:** Microphones permissions requested on mobile.
- **Session Start:** Sends dynamic prompt context including:
  - Learner Name & CEFR Level (e.g., "Spanish A1")
  - Target Language & Native Language
  - Correction Style Preference ("Immediate" vs "After Speaking")
  - Current Scenario ("Ordering in a Madrid Restaurant")
- **Live Stream:** Real-time audio input via `MediaRecorder` & WebRTC.
- **Visual Feedback:** Displays live call states (`Listening...`, `Thinking...`, `Speaking...`).
- **Post-Call Handoff:** On call disconnect, transcript text is routed directly to Gemini for automated analysis.
