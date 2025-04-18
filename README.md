# MindMateAI

MindMateAI is a mental health chatbot built with React and TypeScript. It provides a safe space for users to express their emotions, receive therapy-like interaction, and assess their mental health through tools like the DASS-21 screening.

## Features

- 💬 Chat Therapy with quick replies
- 👩🏻 Talk Therapy with voice interactions and a therapist avatar
- 🧠 DASS-21 Screening with scores and recommendations
- 📞 Call Therapist feature for severe cases
- 🔄 Redirect to therapy module for moderate cases
- ✨ Affirmations and grounding suggestions

## Project Setup

```bash
npm install
npm run dev
```

## Tech Stack

- React + TypeScript
- TailwindCSS
- React Router
- Web Speech API (SpeechRecognition & SpeechSynthesis)

## Folder Structure

```
/src
  /components
    ChatInterface.tsx
    TalkTherapy.tsx
    Dass21Screening.tsx
  /data
    therapy_dataset.json
  /store
    authStore.ts
    chatStore.ts
  /utils
    chatUtils.ts
    conversationUtils.ts
```

## License

This project is open-source and available under the MIT License.
