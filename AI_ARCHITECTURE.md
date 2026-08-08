# AI Architecture & Orchestration — LingoTutor AI

## 🧠 Model Separation of Responsibilities

### 1. Google Gemini 2.5 Flash Engine
- **Curriculum Generation:** Structured JSON generation for CEFR A1-C2 courses.
- **Adaptive Placement Test:** Evaluates initial learner level based on diagnostic responses.
- **Post-Call Analysis:** Analyzes transcript after voice calls to extract vocabulary, highlight grammar mistakes, and generate actionable corrections.
- **Learner Memory Summaries:** Maintains a compact memory profile (struggling words, mastered concepts, favorite topics).

### 2. ElevenLabs Conversational AI Agents
- **Real-Time Voice Interaction:** Full duplex spoken voice conversation with low-latency WebSocket / WebRTC connection.
- **Customizable Voices:** Warm, encouraging natural voice models adapted to the selected language.
- **Dynamic Context Injection:** Passes learner metadata (Level, Current Lesson, Recent Mistakes) into the ElevenLabs session start payload.
