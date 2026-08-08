# Database Schema & State Model — LingoTutor AI

## 🗄️ LocalStorage & IndexedDB Data Structures

```json
{
  "userProfile": {
    "name": "Alex",
    "nativeLanguage": "English",
    "targetLanguage": "Spanish",
    "cefrLevel": "A1",
    "learningGoal": "Conversation",
    "tutorPersonality": "Friendly Coach",
    "correctionStyle": "After speaking",
    "immersionLevel": "Balanced",
    "streakDays": 5,
    "xp": 450,
    "minutesStudied": 120
  },
  "vocabularyBank": [
    {
      "id": "vocab_1",
      "word": "Hola",
      "translation": "Hello",
      "masteryScore": 4,
      "nextReview": "2026-08-10T12:00:00Z"
    }
  ],
  "conversationHistory": [
    {
      "id": "call_101",
      "timestamp": "2026-08-08T15:30:00Z",
      "duration": 180,
      "scenario": "Restaurant Ordering",
      "transcript": "...",
      "analysis": {}
    }
  ]
}
```
