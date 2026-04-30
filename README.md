---
title: Election Guide
emoji: 🗳️
colorFrom: yellow
colorTo: green
sdk: static
pinned: false
---

<p align="center">
  <img src="https://img.shields.io/badge/🗳️_Navi-Indian_Election_Guide-ff9933?style=for-the-badge&labelColor=050810&color=ff9933" alt="Navi">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Languages-13_Indian_📜-138808?style=flat-square&labelColor=050810" alt="13 Languages">
  <img src="https://img.shields.io/badge/Voice-Enabled_🎤-5b8def?style=flat-square&labelColor=050810" alt="Voice Enabled">
  <img src="https://img.shields.io/badge/Google_Services-7_Integrated-d4a84b?style=flat-square&labelColor=050810" alt="Google Services">
  <img src="https://img.shields.io/badge/Accessibility-WCAG_2.1_AA-e8e8e8?style=flat-square&labelColor=050810" alt="Accessibility">
  <img src="https://img.shields.io/badge/Size-<100KB-ff9933?style=flat-square&labelColor=050810" alt="Size">
</p>

<br>

<p align="center">
  <i>"In a democracy, the power belongs to the people — but only if the people know how to use it."</i>
</p>

<p align="center">
  <strong>Navi</strong> is a conversational election agent that speaks your language — literally.<br>
  It walks 97 crore+ Indian voters through the entire election process,<br>
  from Voter ID registration to casting their vote on the EVM.<br>
  In <strong>13 Indian languages</strong>. With <strong>voice</strong>. With <strong>Google</strong>. For <strong>India</strong>.
</p>

<br>

---

## 🇮🇳 What Is Navi?

Navi isn't a website. It isn't a form. It isn't a PDF nobody reads.

**Navi is an agent.** It talks to you. It listens to you. It guides you — step by step, in your language, at your pace — through the most important process in the world's largest democracy.

Think of it as that knowledgeable friend who:
- Knows every ECI form by heart
- Speaks 13 Indian languages fluently
- Never gets tired of your questions
- Remembers where you are in the journey
- Celebrates when you're ready to vote 🎉

<br>

---

## ✨ What Makes It Special

<table>
<tr>
<td width="50%">

### 🗣️ 13 Indian Languages
Not just translated — **natively rendered** in proper scripts:

English · हिन्दी · ಕನ್ನಡ · தமிழ் · తెలుగు · മലയാളം · বাংলা · ગુજરાતી · मराठी · ਪੰਜਾਬੀ · ଓଡ଼ିଆ · অসমীয়া · اردو

Each with proper Google Noto Sans fonts, native voice mapping, and fully localized conversation trees.

</td>
<td width="50%">

### 🎤 Voice System
**Speak to Navi. Navi speaks back.**

- 🎙️ **Voice Input** — Ask questions by speaking in your language (Web Speech API)
- 🔊 **Voice Output** — Navi reads responses aloud (Speech Synthesis)
- 🌊 **Visual Feedback** — Animated wave while recording
- 🔇 **Toggle** — Voice on/off with one tap

</td>
</tr>
<tr>
<td width="50%">

### 🧠 Smart Conversation Engine
Not a chatbot with canned replies. A **branching decision tree** with 31 nodes:

- 5 personalized starting paths based on voter profile
- Context-aware responses that adapt to your journey
- **Tiered Query Resolution**: Local Keywords → Google Gemini AI → Static Fallback
- Progress tracking that persists through the conversation

</td>
<td width="50%">

### 🎨 Living, Breathing Interface
An agent should feel **alive**, not like a form:

- Animated orbital agent with breathing glow
- Typing indicator when "thinking"
- Character-by-character text reveal when "speaking"
- Saffron particle field background
- Smooth transitions between every state
- Indian tricolor confetti on completion 🎊

</td>
</tr>
</table>

<br>

---

## 🔗 Google Services — 7 Deep Integrations

Not token links. Every Google service is woven naturally into the conversation flow:

| Service | How It's Used |
|---------|--------------|
| 🔍 **Google Search** | 10+ contextual deep links for eligibility, electoral roll, candidate research |
| 📍 **Google Maps** | Embedded map + polling booth search for Election Day preparation |
| 📅 **Google Calendar** | One-click event creation for Election Day reminders |
| 📱 **Google Play Store** | App download links for Voter Helpline App and cVIGIL App |
| 📺 **YouTube** | Embedded ECI awareness videos and EVM/VVPAT demos |
| 🌐 **Google Gemini AI** | Advanced conversational engine for free-text election queries |
| 🔤 **Google Fonts** | Noto Sans family for 10+ native Indian scripts |

<br>

---

## 🧪 Testing
Navi includes a built-in automated test suite (`tests.html`) with **95+ validation cases**:

| Suite | Focus Area | Status |
|-------|------------|--------|
| 🌐 Languages | 13 Indian languages & native scripts | ✅ |
| 🌳 Conversation | 31-node branching integrity | ✅ |
| 🔍 Query Engine | Multilingual keyword matching | ✅ |
| 🔗 Google Services | Search, Maps, Calendar, Play, YouTube, Translate, Fonts, Gemini | ✅ |
| 🛡️ Security | XSS prevention, CSP, sanitization | ✅ |
| ♿ Accessibility | WCAG 2.1 AA, keyboard nav, ARIA, high contrast | ✅ |
| 🎤 Voice System | STT/TTS initialization & state | ✅ |
| 🧠 Gemini AI | 3-tier fallback & AI resolution | ✅ |
| ⚡ Performance | DOM batching & animation optimization | ✅ |

### Browser Compatibility

| Browser | Core | Voice Input | Voice Output |
|---------|------|-------------|-------------|
| Chrome 90+ | ✅ | ✅ | ✅ |
| Edge 90+ | ✅ | ✅ | ✅ |
| Firefox 90+ | ✅ | ⚠️ Limited | ✅ |
| Safari 15+ | ✅ | ⚠️ Limited | ✅ |
| Mobile Chrome | ✅ | ✅ | ✅ |
| Mobile Safari | ✅ | ⚠️ Limited | ✅ |

<br>

---

## 📁 Project Structure

```
navi-election-guide/
│
├── index.html              ← Complete application v3.0 (~125KB)
├── tests.html              ← Automated 95-test suite
└── README.md               ← Documentation
```

**Zero dependencies. Zero build steps. Zero servers.**

<br>

---

## 🏆 Competition Compliance

| Requirement | Implementation |
|------------|---------------|
| Smart, dynamic assistant | 31-node branching logic with Gemini AI integration |
| Logical decision making | Context-aware journey mapping & state persistence |
| Google Services | 7 services deeply integrated (Gemini, Search, Maps, Calendar, Play, YouTube, Fonts) |
| Practical usability | Real-world election data & ECI process alignment |
| Clean code | 15 labeled sections with JSDoc, strict mode, & architectural optimizations |
| Security | Full CSP, input sanitization, zero PII collection |
| Efficiency | Single-file architecture, DocumentFragment batching, will-change optimization |
| Testing | 95+ automated tests via `tests.html` |
| Accessibility | WCAG 2.1 AA, high-contrast support, screen reader optimized |
| Repository < 10MB | ~125KB total |
| Public repository | ✅ |

<br>

---

<p align="center">
  <strong>🗳️ Your vote is your voice. Use it wisely.</strong><br><br>
  <img src="https://img.shields.io/badge/Jai_Hind-🇮🇳-ff9933?style=for-the-badge&labelColor=138808&color=FFFFFF" alt="Jai Hind">
</p>
