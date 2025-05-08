# 🧠 AI Mental Fitness Coach – Multi-Agent System

An empathetic, mood-aware mental fitness assistant powered by **Litellm Agents**.  
This project guides users through a personalized 3-step mental wellness routine using conversational AI and modular agent tools.

---

## 🚀 What It Does

1. **🧍 Mood Tracker Agent**  
   - Starts with: *“Hi! How are you feeling today? I’m here to support you with care.”*  
   - Summarizes your mood in 1–2 words with an emoji (e.g., `happy 😊`, `tired 😴`, `uncertain 🤔`).

2. **💪 Motivation Agent**  
   - Delivers a **3-word motivational phrase** (like “Rest. Rise. Refocus.”)  
   - Follows up with a <20-word message based on your mood — sharp, original, and empowering.

3. **📅 Focus Planner Agent**  
   - Creates a **gentle day plan** (Morning, Afternoon, Evening) with activities tailored to your emotional state.  
   - Balances work, rest, and reflection.

4. **🧩 Orchestrator Agent**  
   - Connects all the tools smoothly.  
   - Handles errors gracefully and keeps the tone supportive, warm, and non-judgmental.  
   - Rejects unrelated queries kindly and explains its purpose.

---

## 💡 Tech Stack

- **Litellm Agent SDK** – Agent creation and tool integration  
- **Tools API** – Agents used as callable tools with `as_tool()`  
- **Async Runner Loop** – Interactive experience in CLI  
- **Context Passing** – Mood is tracked and passed across steps  
- **Emotion-Aware Logic** – Adapts tone, activities, and language to user feelings

---
