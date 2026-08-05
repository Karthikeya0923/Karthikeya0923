# Hi, I'm Karthik 👋

Software Engineering student at the **University of Guelph**, looking for a
**Winter 2027 software engineering co-op**. I like building things that are ambitious
for their size — a full offline app, and the AI engine underneath it. Most of what I
know I learned by shipping these two end to end.

---

## 🚀 What I've built

### 🦕 [DinoSpace](https://github.com/Karthikeya0923/dinospace) · .NET MAUI · C#

[![Get it on Google Play](https://img.shields.io/badge/Google_Play-Download-414141?logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.dinospace.kids)

A polished, **fully offline** dinosaur-and-space encyclopedia for kids — 100 hand-written
entries, an AR **Scan Sky** mode that labels the real stars, planets and constellations you
point your phone at, dino battles, quizzes, and **Ask Nova**, an AI chat that runs entirely
on the device with no internet.

- An **instant answer engine** sits in front of the model: most questions are answered
  immediately from a vetted encyclopedia and a 156-topic knowledge base; only genuinely
  open-ended ones reach the LLM.
- Backed by an in-repo harness that runs **over a billion generated questions** through the
  exact production pipeline — each reply graded for being alive, on-topic and substantial —
  and passes with zero quality failures.
- Every screen is written in **C# rather than XAML page markup**, over one small reusable
  component kit, so the whole app can switch themes live.

### 🧠 [NovaSaur](https://github.com/Karthikeya0923/novasaur) · Android · Java/Kotlin ↔ C#

The **on-device AI inference engine** I built to power DinoSpace, running Google's Gemma
locally. Packaged as an Android library and bridged into .NET MAUI through a native binding.

- Streams answers token-by-token with a single-inference queue and automatic engine reload
  between questions, so the chat can never hang or leak state — all with **no network**.
- Ships a **3 GB model through Google Play** as four 1 GB asset packs to stay under Play's
  per-pack cap, with a resumable in-app download as the fallback.

---

## 🛠️ Tech

**Languages:** C# · Java · Kotlin · C · Python · JavaScript/TypeScript
**Building with:** .NET MAUI · XAML · Android · React Native · Expo · Git · Visual Studio · Android Studio

## 📫 Reach me

📧 <Karthikeya0923@gmail.com> · 💼 [linkedin.com/in/karthikeya0923](https://linkedin.com/in/karthikeya0923)
