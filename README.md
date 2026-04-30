# Navi — Indian Election Guide Agent 🇮🇳

Navi is a smart, dynamic conversational assistant designed to guide Indian voters through the entire electoral process. Built with a focus on accessibility, inclusivity, and real-world usability, Navi transforms complex civic information into an engaging, multilingual experience.

## 🚀 Key Features

- **Multilingual Support**: Supports 13 major Indian languages including Hindi, Kannada, Tamil, Telugu, Malayalam, Bengali, Gujarati, Marathi, Punjabi, Odia, Assamese, Urdu, and English.
- **Voice-First Interaction**: Integrated Speech-to-Text (STT) and Text-to-Speech (TTS) capabilities using the Web Speech API, localized for Indian accents.
- **Dynamic Intent Matching**: A custom keyword-matching engine (`QMAP`) that allows users to ask questions in their native script and receive instant, relevant guidance.
- **Cinematic UX**: A premium, dark-mode interface with saffron/gold accents, canvas particle effects, and tricolor celebrations.

## 🛠️ Google Services Integration

Navi meaningfully integrates 7+ Google Services to enhance the voter's journey:
1. **Google Search**: Contextual search integration for real-time BLO search and EPIC tracking.
2. **Google Maps**: Embedded interactive maps to help users find their nearest polling booth.
3. **Google Calendar**: One-click "Add to Calendar" functionality for election day reminders.
4. **YouTube**: Embedded official ECI voter awareness and EVM/VVPAT demonstration videos.
5. **Google Translate**: Dynamic translation bar for extended language support.
6. **Google Fonts**: Custom font stacks for native scripts (Devanagari, Tamil, Telugu, etc.) to ensure perfect typography.
7. **Google Play**: Direct integration for official ECI apps like "Voter Helpline" and "cVIGIL".

## 🧠 Approach & Logic

### Architecture
Navi uses a **Conversational State Machine** architecture. Each step in the voter's journey is a "node" in a JSON-based tree (`C` object). This allows for:
- **Complex Branching**: Logic flows change based on whether a user is a first-time voter, an NRI, or someone who has recently shifted residence.
- **Localization Mapping**: Every message and response choice is mapped to language keys, ensuring zero-latency language switching.

### Smart Intent Matching
Beyond button-clicking, Navi listens to user input. The `handleQuery` logic processes free-text input against a localized keyword map (`QMAP`), routing users to the correct part of the conversation even if they don't follow the linear path.

## ♿ Accessibility & Design
- **WCAG 2.1 Compliance**: Semantic HTML, high-contrast ratios, and full ARIA support.
- **Skip Navigation**: Keyboard users can skip directly to the chat interface.
- **Inclusive Design**: Support for "Reduced Motion" and "High Contrast" system preferences.

## 📝 Assumptions
- **Connectivity**: Requires an internet connection to fetch Google Fonts, YouTube embeds, and link to ECI web resources.
- **API Support**: Assumes a modern browser with `SpeechRecognition` support for voice input features.
- **Privacy**: No user data is collected or stored; the agent operates entirely client-side.

## 🏛️ Vertical
**Civic Technology / Election Assistance**

---
*Navi is a nonpartisan, educational tool. All data is sourced from official Election Commission of India (ECI) resources. Verify all information at voters.eci.gov.in.*
