# LearnProof

**Learn what you know. Prove what you learned.**

LearnProof is a course-first learning verification platform. It helps self-learners verify what they truly understand through concept checks, code reading, execution prediction, workflow reasoning, debugging, and scenario questions.

## MVP

- React + TypeScript + Vite
- Course dashboard based on the learner's AI Agent study plan
- Lesson overview and knowledge-point map
- Interactive chapter exam with multiple question formats
- Immediate explanations and code-focused questions
- Results, wrong-answer review, and knowledge mastery overview
- Local progress persistence with localStorage

## First course: AI Agent Development

The initial demo is grounded in the first four lessons from [ai-agent-learn](https://github.com/wan9h5/ai-agent-learn):

1. S1-01 — Model API and LangChain
2. S1-02 — Messages, Prompt, Token and Context
3. S1-03 — Streaming and Structured Output
4. S2-01 — System/User Message and Prompt Template

The first three lessons are marked as studied; the fourth is the current lesson. This is demo progress data and can be changed in the UI.

## Question formats

The demo includes 33 questions across concept understanding, code reading, execution reasoning, workflow reasoning, debugging, scenario decisions, and three code-snippet selection formats:

- **Select the correct snippet** — compare several implementations and choose the one that meets the requirement.
- **Complete code by selecting a snippet** — inspect an incomplete implementation and choose the missing method or expression.
- **Choose a complete implementation** — compare multi-line code blocks, including prompt templates and message history.

Code options are displayed as selectable code cards with lightweight Python syntax coloring. Answers include explanations and the related knowledge point.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Product principle

LearnProof is not an interview question bank. Questions are tied to lessons and knowledge points. The goal is to test understanding, code comprehension, execution reasoning, and transfer—not memorization.

## Roadmap

- [x] Course-first dashboard
- [x] Code reading and execution prediction
- [x] Workflow ordering
- [x] Debugging and scenario questions
- [x] Results and wrong-answer review
- [ ] Import external learning materials
- [ ] AI-assisted question generation
- [ ] Backend accounts and cross-device sync
- [ ] Spaced repetition scheduling
