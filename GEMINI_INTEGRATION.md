# Google Gemini Integration Specifications — LingoTutor AI

## 🤖 Gemini API Endpoints & Workflows

### 1. Model Selection
- Primary Engine: `models/gemini-2.5-flash`
- Fallback Engine: `models/gemini-2.0-flash` / `models/gemini-flash-latest`

### 2. Post-Call Analysis JSON Schema
```json
{
  "summary": "Learner practiced ordering food in a restaurant in Spanish.",
  "strengths": ["Great vocabulary use for food items", "Good polite phrasing"],
  "corrections": [
    {
      "said": "Yo quiero una agua",
      "corrected": "Yo quiero un agua / Quisiera un agua",
      "explanation": "Gender agreement with 'agua' requires masculine article 'un'."
    }
  ],
  "extractedVocabulary": [
    {"word": "Quisiera", "translation": "I would like", "partOfSpeech": "verb"}
  ]
}
```
