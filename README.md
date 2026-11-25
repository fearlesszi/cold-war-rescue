# Cold War Rescue (冷战话术急救站 Agent Skill)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An actionable AI Agent Skill designed to break relationship standoffs and communication deadlocks after arguments or silent treatment. 

Unlike generic message lists, **Cold War Rescue** deconstructs both parties' underlying psychological needs, conflict nature, and standoff duration *before* generating 3 tailored, ready-to-send icebreaker messages.

---

## 📁 Repository Structure

```text
cold-war-rescue/
├── SKILL.md            # English Version (Standard Agent Skill format)
├── SKILL_ZH.md         # Chinese Version (中文版 Agent Skill)
├── README.md           # Project Documentation & Usage Guide
└── examples/
    └── sample-cases.md # Real-world diagnostic & message generation examples
```

---

## 💡 How It Works

```text
+-----------------------+     +-------------------------------+     +--------------------------------+
|  User Context Input   | --> | Psychological Deconstruction  | --> |  3-Tier Icebreaker Output      |
| (Duration, Trigger,   |     | - Partner vs User Need        |     | - Dignified (不卑不亢)        |
|  Partner Behavior)    |     | - Conflict Essence & Stage    |     | - Soft (柔软示弱)              |
+-----------------------+     +-------------------------------+     | - Casual (洒脱幽默)            |
                                                                    +--------------------------------+
```

---

## 🚀 Installation & Usage

### 1. In Claude / OpenAI / Custom Agent Frameworks
Copy the contents of `SKILL.md` (or `SKILL_ZH.md`) into your system prompt or custom Agent Skill library (e.g., OpenClaw, Dify, AnythingLLM, or Cursor/Claude agent setups).

### 2. Triggering the Skill
The agent automatically activates when detecting prompts like:
- *"We've been in a cold war for 3 days after arguing about plans, what should I text?"*
- *"冷战三天了怎么开口破冰？"*
- *"吵架之后对方已读不回，怎么给台阶下？"*

---

## 📖 Sample Output Preview

```markdown
🩹 Diagnosis
Partner State: Likely in defensive/self-protective mode; Core need may be "To feel prioritized in decision making".
User State: Core focus is actually "Feeling ignored when sharing opinions".
Conflict Essence: Feel Disagreement; Cold War (3 Days) is in the Emotional Phase.

💡 Icebreaker Strategy
Validate their emotional response first before re-explaining the decision rationale.

📱 Messages (Pick one to send)

[Dignified Version]
"I know we both got heated talking about weekend plans. I didn't mean to dismiss your point—let's take a beat and talk it through when you're ready."

[Soft Version]
"Hey, it felt terrible sleeping on this fight. I miss talking to you, and I'm really sorry for snapping earlier."

[Casual Version]
"Still mad at me? I saw that dessert spot you liked earlier and thought of you. truce?"

⚠️ Pitfalls to Avoid
- Avoid starting with "We need to talk seriously" right now.
- Do not bring up past disagreements from last month.
```

---

## 🛡️ Safety & Ethics

- **Zero Tolerance for Toxicity**: The skill refuses to generate manipulative, abusive, or passive-aggressive attack messages.
- **Relationship Safety**: If chronic silent treatment (>1 month), physical threats, or PUA/grooming is detected, the skill halts message generation and recommends seeking relationship counseling or professional support.

---

## 📜 License

Distributed under the [MIT License](LICENSE).
