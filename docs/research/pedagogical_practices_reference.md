# Pedagogical Practices Reference for EdTech

A comprehensive mapping of learning science principles, pedagogical techniques, and best practices to EdTech content types, features, and delivery methods.

---

## Part 1 — Learning Science Foundations

### 1.1 Cognitive Load Theory (CLT)

Working memory is limited. Instruction must manage three types of load:

| Load Type | Definition | EdTech Implication |
|---|---|---|
| **Intrinsic** | Complexity inherent to the material | Break complex topics into chunks; sequence simple → complex |
| **Extraneous** | Load from poor design/distractions | Clean UI, no decorative fluff, no redundant narration+text |
| **Germane** | Load from building mental schemas | Use worked examples, analogies, concept maps |

**What our agent should detect:**
- Segments with too many new concepts at once (high intrinsic load)
- Redundant information (slides reading verbatim what's being spoken)
- Missing worked examples before independent practice
- Dense text walls without visual breaks

> **Seminal Reference:** 
> Sweller, J. (1988). Cognitive load during problem solving: Effects on learning. *Cognitive Science*, 12(2), 257-285. 
> 🔗 [https://doi.org/10.1207/s15516709cog1202_4](https://doi.org/10.1207/s15516709cog1202_4)

---

### 1.2 Retrieval Practice (Testing Effect)

Actively recalling information strengthens memory far more than re-reading.

| Technique | EdTech Implementation | What to Evaluate |
|---|---|---|
| Low-stakes quizzes | Embedded quiz after each video segment | Are recall checkpoints present? |
| Flashcard systems | Spaced repetition decks (Anki-style) | Is retrieval systematic or ad-hoc? |
| Free recall prompts | "Summarize what you learned" text boxes | Are students prompted to generate, not just consume? |
| Pre-tests | Quiz before the lesson to prime retrieval | Does the lesson activate prior knowledge first? |

> **Seminal Reference:** 
> Roediger, H. L., & Karpicke, J. D. (2006). Test-Enhanced Learning: Taking Memory Tests Improves Long-Term Retention. *Psychological Science*, 17(3), 249-255.
> 🔗 [https://doi.org/10.1111/j.1467-9280.2006.01693.x](https://doi.org/10.1111/j.1467-9280.2006.01693.x)

---

### 1.3 Spaced Repetition & Distributed Practice

Learning spread over time beats cramming. The spacing effect is one of the most robust findings in cognitive science.

| Principle | EdTech Implementation | What to Evaluate |
|---|---|---|
| Expanding intervals | Review at 1 day → 3 days → 7 days → 21 days | Does the course revisit key concepts? |
| Drip content release | Modules unlock over weeks, not all at once | Is pacing enforced or self-directed? |
| Spiral curriculum | Return to concepts at increasing depth | Are earlier topics referenced in later lessons? |

> **Seminal Reference:** 
> Cepeda, N. J., Pashler, H., Vul, E., Wixted, J. T., & Rohrer, D. (2006). Distributed practice in verbal recall tasks: A review and quantitative synthesis. *Psychological Bulletin*, 132(3), 354–380.
> 🔗 [https://doi.org/10.1037/0033-2909.132.3.354](https://doi.org/10.1037/0033-2909.132.3.354)

---

### 1.4 Interleaving

Mixing different problem types/topics within a session forces discrimination and deeper processing.

| Blocked Practice (Bad) | Interleaved Practice (Good) |
|---|---|
| 10 addition problems, then 10 subtraction | Mix of add/subtract/multiply in one set |
| Chapter 3 quiz covers only Chapter 3 | Cumulative quiz covers Chapters 1-3 |
| All similar examples grouped together | Varied examples requiring strategy selection |

**What our agent should detect:**
- Is practice purely blocked by topic?
- Are assessments cumulative or chapter-isolated?
- Does the lesson require students to choose which strategy to apply?

> **Seminal Reference:** 
> Rohrer, D., & Taylor, K. (2007). The shuffling of mathematics problems improves learning. *Instructional Science*, 35(6), 481-498.
> 🔗 [https://doi.org/10.1007/s11251-007-9015-8](https://doi.org/10.1007/s11251-007-9015-8)

---

### 1.5 Scaffolding & Zone of Proximal Development (Vygotsky)

Learners need temporary support to bridge the gap between what they can do alone and what they can achieve with help.

| Scaffolding Type | EdTech Implementation | Evaluation Criteria |
|---|---|---|
| **Procedural** | Step-by-step walkthroughs, checklists | Are complex tasks broken into guided steps? |
| **Conceptual** | Hints, concept maps, prerequisite reviews | Are prerequisites identified and addressed? |
| **Strategic** | Problem-solving frameworks, decision trees | Are students given tools for HOW to think? |
| **Metacognitive** | Self-assessment prompts, reflection journals | Are students asked to monitor their own learning? |
| **Fading** | Gradual removal of support | Do worked examples transition to independent practice? |

**Critical evaluation question:** Does the lesson assume prerequisite knowledge without teaching or reviewing it?

> **Seminal References:** 
> Vygotsky, L. S. (1978). *Mind in Society: The Development of Higher Psychological Processes*. Harvard University Press.
> 🔗 [https://www.jstor.org/stable/j.ctvjf9vz4](https://www.jstor.org/stable/j.ctvjf9vz4)
> Wood, D., Bruner, J. S., & Ross, G. (1976). The role of tutoring in problem solving. *Journal of Child Psychology and Psychiatry*, 17(2), 89-100.
> 🔗 [https://doi.org/10.1111/j.1469-7610.1976.tb00381.x](https://doi.org/10.1111/j.1469-7610.1976.tb00381.x)

---

### 1.6 Bloom's Taxonomy (Revised)

Hierarchy of cognitive complexity. Higher levels require deeper thinking.

| Level | Verbs | EdTech Content Example |
|---|---|---|
| **Remember** | List, define, recall | Flashcards, fill-in-the-blank |
| **Understand** | Explain, summarize, paraphrase | Video lecture, reading comprehension |
| **Apply** | Use, solve, demonstrate | Interactive simulation, coding exercise |
| **Analyze** | Compare, contrast, categorize | Case study analysis, data interpretation |
| **Evaluate** | Judge, critique, justify | Peer review, debate forum, essay |
| **Create** | Design, construct, produce | Project-based learning, portfolio |

**What our agent should detect:**
- Distribution across levels (too much "Remember", not enough "Apply+")
- Alignment between stated objectives and actual cognitive demand
- Whether assessments match the Bloom level of instruction

> **Seminal Reference:** 
> Anderson, L. W., & Krathwohl, D. R. (Eds.). (2001). *A taxonomy for learning, teaching, and assessing: A revision of Bloom's taxonomy of educational objectives*. Longman.
> 📖 ISBN-13: 978-0801319037 (Book format)

---

### 1.7 Mayer's Multimedia Learning Principles

12 evidence-based principles for designing multimedia content:

| Principle | Rule | Violation Example |
|---|---|---|
| **Coherence** | Remove extraneous material | Background music during explanation |
| **Signaling** | Highlight key information | No visual cues for important points |
| **Redundancy** | Don't duplicate narration as on-screen text | Instructor reads slides word-for-word |
| **Spatial Contiguity** | Place text near related graphics | Labels far from the diagram they describe |
| **Temporal Contiguity** | Present words and images simultaneously | Narration separated in time from animation |
| **Segmenting** | Break into learner-paced chunks | 60-min unbroken video lecture |
| **Pre-training** | Teach key terms before the main lesson | Jargon used without prior definition |
| **Modality** | Use narration (audio) with graphics, not text | Text-heavy slides with no audio explanation |
| **Multimedia** | Use words + pictures, not words alone | Text-only lesson with no visuals |
| **Personalization** | Use conversational tone, not formal | Stiff, academic language in beginner content |
| **Voice** | Use human voice, not machine | Robotic TTS for primary instruction |
| **Image** | Speaker's image doesn't always help | Talking-head video with no visual aids |

> **Seminal Reference:** 
> Mayer, R. E. (2001). *Multimedia Learning*. Cambridge University Press.
> 🔗 [https://doi.org/10.1017/CBO9781139164603](https://doi.org/10.1017/CBO9781139164603)

---

### 1.8 Formative vs. Summative Assessment

| Dimension | Formative | Summative |
|---|---|---|
| **Purpose** | Monitor learning, provide feedback | Evaluate mastery |
| **Timing** | During instruction | End of unit/course |
| **Stakes** | Low or no stakes | High stakes |
| **Frequency** | Continuous | Periodic |
| **Feedback** | Immediate, specific, actionable | Delayed, often just a score |
| **EdTech examples** | In-video quiz, poll, exit ticket | Final exam, capstone project |

**What our agent should detect:**
- Is formative assessment embedded throughout?
- Is feedback immediate or delayed?
- Are assessments diagnostic (revealing misconceptions) or just grading?

> **Seminal Reference:** 
> Black, P., & Wiliam, D. (1998). Assessment and classroom learning. *Assessment in Education: Principles, Policy & Practice*, 5(1), 7-74.
> 🔗 [https://doi.org/10.1080/0969595980050102](https://doi.org/10.1080/0969595980050102)

---

### 1.9 Metacognition & Self-Regulated Learning

Teaching students HOW to learn, not just WHAT to learn.

| Strategy | EdTech Implementation |
|---|---|
| Goal setting | Learning objectives displayed prominently |
| Self-monitoring | Progress bars, mastery dashboards |
| Self-assessment | "Rate your confidence" prompts |
| Reflection | Post-lesson reflection journals |
| Strategy selection | "Which approach would you use?" prompts |
| Planning | Study schedule generators, milestone tracking |

> **Seminal Reference:** 
> Flavell, J. H. (1979). Metacognition and cognitive monitoring: A new area of cognitive–developmental inquiry. *American Psychologist*, 34(10), 906–911.
> 🔗 [https://doi.org/10.1037/0003-066X.34.10.906](https://doi.org/10.1037/0003-066X.34.10.906)

---

### 1.10 Engagement & Motivation Frameworks

**Self-Determination Theory (Deci & Ryan):** Three innate needs:

| Need | EdTech Design |
|---|---|
| **Autonomy** | Choice in topics, pace, expression format |
| **Competence** | Clear progress indicators, achievable challenges |
| **Relatedness** | Discussion forums, peer collaboration, cohort identity |

**Flow Theory (Csikszentmihalyi):** Optimal engagement occurs when challenge matches skill level. Too easy → boredom. Too hard → anxiety.

> **Seminal References:** 
> Deci, E. L., & Ryan, R. M. (2000). The "What" and "Why" of Goal Pursuits: Human Needs and the Self-Determination of Behavior. *Psychological Inquiry*, 11(4), 227-268.
> 🔗 [https://doi.org/10.1207/S15327965PLI1104_01](https://doi.org/10.1207/S15327965PLI1104_01)
> Csikszentmihalyi, M. (1990). *Flow: The Psychology of Optimal Experience*. Harper & Row.
> 📖 ISBN-13: 978-0061339202 (Book format)

---

## Part 2 — EdTech Content Types & Pedagogical Alignment

### 2.1 Content Type → Pedagogy Mapping

| Content Type | Best For (Bloom Level) | Key Pedagogy Principles | Common Pitfalls |
|---|---|---|---|
| **Video Lecture** | Remember, Understand | Segmenting, Signaling, Modality, Personalization | Too long, no interaction points, redundant slides |
| **Interactive Video** | Understand, Apply | Retrieval practice, Active learning, Immediate feedback | Questions too simple, no consequence for wrong answers |
| **Reading Material** | Remember, Understand | Coherence, Pre-training, Signaling | Text walls, no visual breaks, assumed vocabulary |
| **Slide Deck / PPT** | Remember, Understand | Spatial contiguity, Coherence, Multimedia | Text-heavy slides, read-aloud redundancy |
| **Quiz / Assessment** | Remember → Evaluate | Retrieval practice, Interleaving, Formative feedback | Only testing recall, no diagnostic feedback |
| **Interactive Simulation** | Apply, Analyze | Experiential learning, Scaffolding, ZPD | No scaffolding, unclear objectives, no debrief |
| **Discussion Forum** | Analyze, Evaluate | Social constructivism, Peer learning, Metacognition | No moderation, vague prompts, no rubric |
| **Project / Portfolio** | Create, Evaluate | Authentic assessment, Self-regulation, UDL | No scaffolding, unclear criteria, no milestones |
| **Gamified Activity** | Apply, Analyze | Motivation, Flow, Mastery-based progression | Extrinsic rewards without learning, competition over collaboration |
| **Live Session / Webinar** | Understand, Apply | Active learning, Immediate feedback, Social presence | Passive lecture format, no breakout activities |
| **Podcast / Audio** | Remember, Understand | Modality, Personalization, Voice principle | No visual support, too long, monotone delivery |
| **Infographic** | Remember, Understand | Multimedia, Spatial contiguity, Coherence | Information overload, decorative over informative |
| **Lab / Hands-on** | Apply, Create | Experiential learning, Kolb cycle, Scaffolding | No connection to theory, missing debrief/reflection |
| **AI Tutor / Chatbot** | Understand, Apply | Adaptive learning, Scaffolding, Immediate feedback | Hallucination, no pedagogical grounding, over-reliance |
| **Flashcard / SRS** | Remember | Spaced repetition, Retrieval practice | Only rote memorization, no application context |

---

### 2.2 EdTech Features → Pedagogy Mapping

| EdTech Feature | Pedagogical Purpose | Learning Science Basis |
|---|---|---|
| **Progress bar** | Self-regulation, goal monitoring | Metacognition |
| **Adaptive difficulty** | Keep in ZPD, prevent boredom/frustration | Vygotsky, Flow theory |
| **Branching scenarios** | Decision-making, consequence exploration | Experiential learning, Bloom (Evaluate) |
| **Leaderboard** | Social motivation | Self-Determination (Relatedness), Gamification |
| **Badge/achievement** | Competence feedback | Self-Determination (Competence) |
| **Peer review** | Critical thinking, perspective-taking | Social constructivism, Bloom (Evaluate) |
| **Annotation tools** | Active reading, engagement | Active learning, Signaling |
| **Bookmarking** | Self-directed review | Self-regulated learning |
| **Transcript/captions** | Accessibility, dual coding | UDL, Multimedia principle |
| **Playback speed control** | Learner pacing | Segmenting, Autonomy |
| **In-video questions** | Retrieval during consumption | Testing effect, Active learning |
| **Discussion threading** | Collaborative knowledge building | Connectivism, Social constructivism |
| **Automated feedback** | Immediate, scalable response | Formative assessment |
| **Rubric display** | Transparent expectations | Metacognition, Self-regulation |
| **Study planner** | Distributed practice | Spaced repetition |
| **Dark/light mode** | Reduced visual fatigue | Cognitive load (extraneous) |
| **Offline access** | Anytime learning | Autonomy, Accessibility |

---

## Part 3 — Delivery Methods & Pedagogical Considerations

### 3.1 Delivery Mode Comparison

| Delivery Mode | Strengths | Weaknesses | Best Pedagogy Pairing |
|---|---|---|---|
| **Synchronous (Live)** | Social presence, immediate Q&A, accountability | Scheduling, time zone issues, passive risk | Active learning, Think-Pair-Share, polling |
| **Asynchronous (Self-paced)** | Flexibility, replayability, learner autonomy | Isolation, procrastination, no live feedback | Spaced repetition, SRS, discussion forums |
| **Hybrid/Blended** | Best of both; flexibility + community | Design complexity, coherence challenge | Flipped classroom, cohort-based learning |
| **Microlearning** | Low cognitive load, fits mobile, high completion | Fragmentation, shallow depth risk | Retrieval practice, spaced review, just-in-time |
| **Cohort-based** | Peer accountability, social learning, deadlines | Less flexibility, group dynamics | Collaborative projects, peer feedback, forums |
| **MOOC (Massive Open)** | Scale, access democratization | Low completion, minimal personalization | Gamification, adaptive paths, community TAs |

### 3.2 The Flipped Classroom Model

| Phase | Activity | Pedagogy |
|---|---|---|
| **Pre-class (async)** | Watch video, read material | Multimedia principles, Pre-training |
| **In-class (sync)** | Discussion, problem-solving, labs | Active learning, Scaffolding, ZPD |
| **Post-class (async)** | Reflection, spaced review, assessment | Retrieval practice, Metacognition |

---

## Part 4 — Assessment Design for EdTech

### 4.1 Assessment Type → Bloom Level Alignment

| Assessment Type | Bloom Level | Formative/Summative | Automation Potential |
|---|---|---|---|
| Multiple choice | Remember, Understand | Both | High |
| Fill-in-the-blank | Remember | Formative | High |
| Short answer | Understand, Apply | Both | Medium (AI grading) |
| Essay / Long response | Analyze, Evaluate, Create | Summative | Low (AI-assisted) |
| Coding exercise | Apply, Create | Both | High (auto-test) |
| Simulation performance | Apply, Analyze | Both | Medium |
| Peer review | Evaluate | Formative | Medium |
| Portfolio | Create, Evaluate | Summative | Low |
| Oral presentation | Apply, Evaluate | Summative | Low (AI-assisted) |
| Concept map | Understand, Analyze | Formative | Medium |
| Drag-and-drop ordering | Understand, Apply | Formative | High |
| Case study analysis | Analyze, Evaluate | Both | Low |

### 4.2 Feedback Quality Rubric

Effective feedback in EdTech must be:

| Quality | Definition | Bad Example | Good Example |
|---|---|---|---|
| **Timely** | Delivered immediately or near-immediately | Grade returned 2 weeks later | Instant quiz feedback |
| **Specific** | Points to exact issue | "Needs improvement" | "Your explanation of osmosis confuses it with diffusion" |
| **Actionable** | Tells what to do next | "Try harder" | "Review the worked example on p.12, then retry" |
| **Growth-oriented** | Focused on process, not person | "You're not good at this" | "Your strategy needs adjustment — try X" |
| **Calibrated** | Matches learner level | PhD-level feedback to a beginner | Adapted to current knowledge state |

---

## Part 5 — Frameworks for Technology Integration

### 5.1 SAMR Model

| Level | Description | Example |
|---|---|---|
| **Substitution** | Tech replaces tool, no functional change | PDF instead of printed handout |
| **Augmentation** | Tech replaces with functional improvement | Interactive PDF with hyperlinks |
| **Modification** | Tech allows significant task redesign | Collaborative document editing |
| **Redefinition** | Tech enables previously impossible tasks | Global peer review with students in another country |

> **Seminal Reference:** 
> Puentedura, R. R. (2006). *Transformation, Technology, and Education*. 
> 🔗 [http://hippasus.com/resources/tte/](http://hippasus.com/resources/tte/)

### 5.2 TPACK Framework

Effective EdTech lives at the intersection of:
- **Technological Knowledge** — What tools exist and how they work
- **Pedagogical Knowledge** — How to teach effectively
- **Content Knowledge** — Deep understanding of the subject matter

**Failure modes:**
- Tech without pedagogy = shiny tools, no learning
- Pedagogy without content = great teaching of nothing
- Content without pedagogy = expert who can't explain

> **Seminal Reference:** 
> Mishra, P., & Koehler, M. J. (2006). Technological Pedagogical Content Knowledge: A Framework for Teacher Knowledge. *Teachers College Record*, 108(6), 1017-1054.
> 🔗 [https://doi.org/10.1111/j.1467-9620.2006.00684.x](https://doi.org/10.1111/j.1467-9620.2006.00684.x)

### 5.3 Gagné's Nine Events of Instruction

| Event | Purpose | EdTech Implementation |
|---|---|---|
| 1. Gain attention | Focus learner | Hook video, surprising fact, problem statement |
| 2. Inform objectives | Set expectations | Learning outcomes displayed at start |
| 3. Stimulate recall | Activate prior knowledge | Pre-quiz, "What do you already know?" |
| 4. Present content | Deliver new material | Video, reading, interactive content |
| 5. Provide guidance | Support understanding | Worked examples, hints, scaffolding |
| 6. Elicit performance | Practice | Interactive exercise, quiz, simulation |
| 7. Provide feedback | Correct and reinforce | Immediate automated feedback |
| 8. Assess performance | Evaluate mastery | Graded assessment |
| 9. Enhance retention | Support transfer | Spaced review, real-world application |

> **Seminal Reference:** 
> Gagné, R. M. (1968). Learning hierarchies. *Educational Psychologist*, 6(1), 1-9.
> 🔗 [https://doi.org/10.1080/00461526809528918](https://doi.org/10.1080/00461526809528918)

---

## Part 6 — Accessibility & Inclusive Design (UDL)

### 6.1 Universal Design for Learning (UDL) — Three Principles

| Principle | Question | Implementation |
|---|---|---|
| **Multiple Means of Engagement** | WHY learn? | Choice, relevance, self-regulation support |
| **Multiple Means of Representation** | WHAT to learn? | Text + audio + video + visual; glossaries; alt-text |
| **Multiple Means of Action & Expression** | HOW to show learning? | Write, speak, draw, code, build, present |

> **Seminal Reference:** 
> Rose, D. H., & Meyer, A. (2002). *Teaching every student in the digital age: Universal design for learning*. Association for Supervision and Curriculum Development.
> 🔗 [https://udlguidelines.cast.org/](https://udlguidelines.cast.org/) (Official CAST Guidelines)

### 6.2 Accessibility Checklist for EdTech Content

| Element | Requirement |
|---|---|
| Video | Captions, transcript, audio description |
| Images | Alt text, not text-as-image |
| Documents | Heading structure, screen-reader compatible |
| Color | Not sole means of conveying info; sufficient contrast |
| Navigation | Keyboard navigable, skip links |
| Language | Clear, plain language; glossary for jargon |
| Timing | No time-limited interactions without override |
| Mobile | Responsive design, touch-friendly targets |

---

## Part 7 — What Our Agent Should Evaluate

This section maps every evaluation dimension in our system to the learning science that justifies it.

| Our Evaluation Dimension | Learning Science Basis | What to Look For |
|---|---|---|
| **Clarity** | CLT (extraneous load), Mayer (coherence) | Jargon without definition, dense passages, unclear structure |
| **Pacing** | CLT, Segmenting principle, Flow theory | Too many concepts per segment, no pauses, rushed transitions |
| **Engagement** | SDT, Active learning, Flow | All passive consumption, no interaction points, monotone delivery |
| **Scaffolding** | Vygotsky ZPD, Fading, Worked examples | Complex tasks without preparation, missing prerequisites |
| **Retrieval Practice** | Testing effect, Desirable difficulties | No recall prompts, no quizzes, no "summarize what you learned" |
| **Interleaving** | Discrimination learning | Purely blocked practice, no mixed problem sets |
| **Concept Reinforcement** | Spaced repetition, Distributed practice | Concepts mentioned once and never revisited |
| **Cognitive Load** | CLT all three types | Information overload, redundant channels, no chunking |
| **Misconception Handling** | Constructivism, Conceptual change theory | Common errors not addressed, no "what students often get wrong" |
| **Bloom Depth** | Bloom's taxonomy | All recall-level questions, no higher-order thinking demands |
| **Formative Assessment** | Formative assessment research | No checks for understanding during instruction |
| **Multimedia Design** | Mayer's 12 principles | Slides read aloud, decorative images, no signaling |
| **Accessibility** | UDL, WCAG | No captions, text-as-image, poor contrast, no alt text |
| **Motivation Design** | SDT, Gamification | No autonomy, no progress indicators, no relevance framing |
| **Social Learning** | Constructivism, Connectivism | No peer interaction opportunities, isolated learning path |
