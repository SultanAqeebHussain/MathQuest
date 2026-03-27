# 📚 Research and Theoretical Foundation

## My Research Process

As Team Leader, I conducted the following research areas:
1. Educational theories to inform adaptive difficulty design
2. UI and UX patterns for child-friendly applications
3. Ethics and data privacy for applications targeting minors
4. Flutter framework and library selection
5. Game mechanics for motivation and engagement

---

## Educational Theories Applied

### 1. Vygotsky — Zone of Proximal Development (1978)

**Theory:**
Learners perform best when challenged at a level slightly above 
their current ability, but still achievable with some support.

**How I Applied It:**
- Adaptive difficulty increases gradually based on performance
- System never jumps difficulty aggressively
- Hint prompts appear when user struggles repeatedly
- Each age band is carefully calibrated to match learning level

---

### 2. Bruner — Scaffolding Theory (1966)

**Theory:**
Learners need structured support early on. That support should 
systematically reduce as confidence and competence grow.

**How I Applied It:**
- Early levels include hints and guided answer steps
- Mid levels reduce hints to prompt-only
- Higher levels require fully independent problem solving
- XP system rewards independence over hint reliance

---

### 3. Piaget — Cognitive Development Stages (1952)

**Theory:**
Children progress through distinct cognitive stages. Content 
must match the cognitive readiness of the learner at each stage.

**How I Applied It:**
- 5 age bands mapped to Piaget's developmental stages
- Ages 3-5 (Pre-operational): Visual number recognition only
- Ages 5-7 (Early Concrete): Simple operations with visuals
- Ages 7-11 (Concrete Operational): Logical mathematical thinking
- Ages 11-15 (Formal Operational): Abstract algebra and geometry

---

## Game Mechanics Research

### Inspiration Sources
- Analysed Candy Crush — reward loops and level progression
- Analysed Subway Surfers — continuous motivation mechanics
- Researched Pinterest wireframes for child UI patterns
- Studied colour psychology for young user engagement

### Key Findings Applied

| Finding | Application in MathQuest |
|---|---|
| Reward loops increase retention | XP and badge reward system |
| Visual progress motivates continuation | Progress bar on every level |
| Bright colours attract young users | Warm colour palette in Figma |
| Simple navigation reduces frustration | Minimal text, icon-led UI |
| Levels create goal-oriented behaviour | Quest stage unlock system |

---

## Ethics Research

### GDPR (General Data Protection Regulation)
- Applies to all UK and EU users
- Personal data cannot be collected without explicit consent
- Children under 13 require verifiable parental consent
- Data must be stored securely and minimally

### COPPA (Children's Online Privacy Protection Act)
- US regulation restricting data collection from under-13s
- Relevant as app may be used internationally
- Prohibits behavioural advertising to children
- Requires clear privacy policy accessible to parents

### My Conclusions
MathQuest at prototype stage collects no personal data. 
All progress is stored locally via shared_preferences. 
Future deployment must implement parental consent flow 
before any account creation or data transmission.

---

## References

- Bruner, J. (1966). *Toward a Theory of Instruction*. Harvard University Press.
- Vygotsky, L. (1978). *Mind in Society: The Development of Higher Psychological Processes*. Harvard University Press.
- Piaget, J. (1952). *The Origins of Intelligence in Children*. International Universities Press.
