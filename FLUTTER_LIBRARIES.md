# 📦 Flutter Libraries — Research and Selection

## Why Flutter?

Flutter was selected as the planned development framework for 
MathQuest after careful research and comparison with alternatives.

| Reason | Detail |
|---|---|
| Cross-platform | Single codebase runs on both iOS and Android |
| Performance | Fast Skia rendering engine suitable for animated UI |
| UI Flexibility | Highly customisable widgets ideal for child-friendly design |
| Open Source | Free to use with large active community |
| Dart Language | Simple syntax easy to learn for rapid development |
| Hot Reload | Speeds up development and testing significantly |
| Widget Library | Rich built-in components reduce development time |

### Alternatives Considered

| Framework | Reason Rejected |
|---|---|
| React Native | Less consistent UI across platforms |
| Xamarin | Smaller community, slower development |
| Android Native | iOS support would require separate codebase |
| Unity | Designed for games, overkill for learning app |

---

## ✅ Libraries Selected

| Library | Version | Purpose | Justification |
|---|---|---|---|
| `flutter/material.dart` | Built-in | Core UI components | Reliable, well documented, no extra dependency |
| `provider` | ^6.0.0 | State management for XP and progress | Lightweight, beginner friendly, widely used |
| `shared_preferences` | ^2.2.0 | Local storage for level data | Simple key-value storage, no server required |
| `flutter_animate` | ^4.0.0 | Animations for quest transitions | Easy API, visually engaging for children |
| `audioplayers` | ^5.0.0 | Sound effects for correct/incorrect answers | Enhances engagement especially for younger users |
| `google_fonts` | ^6.0.0 | Child-friendly typography | Wide selection, free, easy to implement |

---

## ❌ Libraries Researched but Rejected

| Library | Purpose | Reason Rejected |
|---|---|---|
| `firebase_auth` | User authentication | Raises GDPR concerns for child users under 13 |
| `cloud_firestore` | Cloud database for leaderboard | Requires backend setup, deferred to next phase |
| `hive` | Lightweight local database | More complex than shared_preferences for current needs |
| `flame` | Full game engine | Too heavy and complex for prototype scope |
| `flutter_bloc` | Advanced state management | More complex than provider, unnecessary at this stage |
| `sqflite` | Local SQL database | Unnecessary complexity for MVP prototype |
| `firebase_analytics` | User behaviour tracking | Prohibited for under-13 users without parental consent |

---

## 🔒 Ethics Note on Library Selection

Several powerful libraries were deliberately rejected due to 
data privacy concerns. Since MathQuest targets children as young 
as 3 years old, any library that collects, transmits, or stores 
personal data externally was excluded at this stage. This decision 
directly reflects GDPR and COPPA compliance requirements researched 
during the project.
