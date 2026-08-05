# Hi, I'm Karthik 👋

Software Engineering student at the **University of Guelph**, currently looking for
a software engineering **co-op**. I like building things that are ambitious for
their size — a full offline app, the AI engine underneath it, and the math library
that powers its sky. Most of what I know I learned by shipping these three end to end.

---

## 🚀 What I've built

### 🦕 [DinoSpace](https://github.com/Karthikeya0923/dinospace) · .NET MAUI · C#
A polished, **fully offline** dinosaur-and-space encyclopedia for kids — 100 hand-written
entries, an AR **Scan Sky** mode that labels the real stars, planets and constellations
you point your phone at, dino battles, quizzes, and **Ask Nova**, an AI chat that runs
entirely on the device with no internet.
- An **instant answer engine** sits in front of the model: most questions are answered
  immediately from a vetted encyclopedia and a 156-topic knowledge base; only genuinely
  open-ended ones reach the LLM.
- Backed by an in-repo harness that runs **over a billion generated questions** through
  the exact production pipeline — each reply graded for being alive, on-topic and
  substantial — and passes with **zero quality failures**.
- Live astronomy: "where is Jupiter right now?" is computed from real orbital math.

### 🧠 [NovaSaur](https://github.com/Karthikeya0923/novasaur) · Android · Java/Kotlin ↔ C#
The **on-device AI inference engine** I built to power DinoSpace, running Google's Gemma
locally. Packaged as an Android library and bridged into .NET MAUI through a native binding.
- Streams answers token-by-token with a single-inference queue and automatic engine reload
  between questions, so the chat can never hang or leak state — all with **no network**.

### 🔭 [SkyScanner](https://github.com/Karthikeya0923/SkyScanner) · C#
The astronomy library behind DinoSpace's sky features: sun/moon/planet positions,
rise-and-set times, moon phases, and constellation placement — computed from first principles. Built with Claude using NASA's astronomy library.

---

## 🛠️ Tech
**Languages:** C# · C · Python · Java
**Building with:** .NET MAUI · XAML · Android · Git · Visual Studio

## 📫 Reach me
📧 Karthikeya0923@gmail.com · 💼 linkedin.com/in/karthikeya0923
