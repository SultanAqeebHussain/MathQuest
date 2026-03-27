# 🎮 MathQuest

> A quest-based mobile learning application for children aged 3–15

<img src="https://img.shields.io/badge/Status-Prototype-yellow">
<img src="https://img.shields.io/badge/Framework-Flutter-blue">
<img src="https://img.shields.io/badge/Design-Figma-purple">
<img src="https://img.shields.io/badge/Module-4WCM2010-green">

---

## 📌 Project Overview

MathQuest is a mobile learning application designed to make mathematics 
engaging and fun for children aged 3 to 15. The app uses a quest-based 
progression system inspired by popular mobile games, combined with 
adaptive difficulty rooted in educational theory.

### Core Features
- Quest and level progression system with XP rewards
- Adaptive difficulty based on individual user performance
- Age-appropriate content across 5 learning bands
- Hint system that reduces as user confidence grows
- Engaging visuals and reward mechanics for motivation

---

## 🎯 Age Group Content Structure

| Age Band | Content Focus |
|---|---|
| 3 – 5 | Number recognition and counting |
| 5 – 7 | Basic addition and subtraction |
| 7 – 9 | Multiplication and division |
| 9 – 11 | Fractions and decimals |
| 11 – 15 | Algebra and geometry |

---

## 👤 My Role — Sultan Aqeeb Hussain (Team Leader)

| Responsibility | Detail |
|---|---|
| Quest System Design | Proposed and designed the core quest and XP system |
| UI Design | Created all Figma prototypes and screen designs |
| Project Planning | Led team meetings and managed task allocation |
| Research | Educational theories, ethics, Flutter tech stack |
| Documentation | GitHub, interim report, Flutter libraries research |

---

## 👥 Team Members

| Member | Role |
|---|---|
| Sultan Aqeeb Hussain | Team Leader, UI Design, Quest System |
| Syed Abdul Rehman | Background Research, Educational Theory |
| Muhammad Mustafa | Requirements, Use Cases, Test Cases |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Figma | UI Design and Prototyping |
| Flutter (Dart) | Planned Mobile Development |
| GitHub | Version Control and Documentation |
| Trello | Project Management |
| Canva | Team Planning Board |

---

## 📐 Planned App Architecture
lib/
├── main.dart
├── screens/
│   ├── home_screen.dart
│   ├── level_screen.dart
│   └── results_screen.dart
├── models/
│   ├── user_progress.dart
│   └── question_model.dart
├── widgets/
│   ├── quest_card.dart
│   └── progress_bar.dart
└── data/
├── questions_age3_5.dart
├── questions_age5_7.dart
├── questions_age7_9.dart
├── questions_age9_11.dart
└── questions_age11_15.dart
---

## 📚 Theoretical Foundation

### Vygotsky's Zone of Proximal Development (1978)
Learners perform best when tasks are slightly beyond their current 
ability but still achievable with guidance. Applied in MathQuest 
through adaptive difficulty — complexity increases gradually based 
on user performance rather than jumping suddenly.

### Bruner's Scaffolding Theory (1966)
Structured support should reduce as learner confidence grows. 
Applied in MathQuest through the hint system — early levels 
include guided hints, higher levels require independent thinking.

### Piaget's Cognitive Development Stages (1952)
Children think differently at different ages. Applied in MathQuest 
through the 5 age band content structure, ensuring mathematical 
concepts match cognitive readiness at each stage.

---

## 🔒 Ethics and Data Privacy

Since MathQuest targets children as young as 3 years old, data 
privacy is a critical concern:

- **GDPR** (UK/EU) — personal data cannot be collected without consent
- **COPPA** — restricts data collection from users under 13
- Progress data stored **locally only** at prototype stage
- No third-party analytics or tracking
- Future deployment requires verified parental consent mechanism
- Leaderboard usernames must be anonymous or parental-consent-gated

---

## 🔗 Design Links

- <a href="https://www.figma.com/design/VITWra3FXIqEUFIlvKAjzy/Untitled?node-id=1-2&m=dev&t=lDaI4oYiueWWFQ3d-1">UI Design — Figma</a>
- <a href="https://www.figma.com/design/uR2H5RRDaqDlqcvaryj4Kd/Untitled?node-id=0-1&m=dev&t=lDaI4oYiueWWFQ3d-1">MathQuest System — Figma</a>

---

## ⚠️ Current Status

The project is currently at **prototype and design stage**. 
Two Figma UI screens have been completed. Full Flutter development 
is planned as the next phase. The architecture and research 
documented here provides the complete blueprint for development.

---

## 📖 References

- Bruner, J. (1966). *Toward a Theory of Instruction*. Harvard University Press.
- Vygotsky, L. (1978). *Mind in Society*. Harvard University Press.
- Piaget, J. (1952). *The Origins of Intelligence in Children*. International Universities Press.
