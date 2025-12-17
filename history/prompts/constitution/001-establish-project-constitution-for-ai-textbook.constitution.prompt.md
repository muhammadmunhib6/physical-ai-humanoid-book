---
id: 001
title: Establish Project Constitution for AI Textbook
stage: constitution
date: 2025-12-16
surface: agent
model: gemini-pro
feature: none
branch: master
user: placeholder-user
command: /sp.constitution # Project Constitution
## Physical AI & Humanoid Robotics – AI-Native Textbook (Gemini-Powered)

---

## 1. Purpose

This project creates an **AI-native technical textbook** for teaching
**Physical AI & Humanoid Robotics**, aligned with the Panaversity curriculum.

The textbook is designed to:
- Teach embodied intelligence and Physical AI
- Bridge AI reasoning with robotic control systems
- Enable interactive, adaptive, and multilingual learning
- Serve as a foundation for future AI-native educational platforms

This project is developed as part of **Hackathon I: Create a Textbook for Teaching Physical AI & Humanoid Robotics Course**.

---

## 2. Core Principles

### 2.1 AI-Native by Design
The textbook is not static content. It is:
- Generated, adapted, and queried using AI agents
- Personalized per learner background
- Translatable on demand (including Urdu)
- Searchable and explainable via RAG

---

### 2.2 Spec-Driven Development
All functionality is:
- Defined first in formal specifications
- Implemented strictly according to specs
- Traceable from specification to deployment

**Spec-Kit Plus is the authoritative system contract.**

---

## 3. Tooling Strategy (No Claude)

### 3.1 Gemini API (Primary Intelligence Layer)
Gemini is used for:
- Textbook chapter generation
- Technical explanation and rewriting
- Content personalization
- Urdu translation
- Pedagogical adaptation

Gemini is accessed via clearly defined services and agent-like functions.

---

### 3.2 OpenAI Agents & ChatKit (RAG Only)
OpenAI tooling is used **exclusively** for:
- Retrieval-Augmented Generation
- Question answering over book content
- Selected-text-only reasoning

No content generation is delegated to OpenAI models.

---

### 3.3 Spec-Kit Plus
Spec-Kit Plus governs:
- Project structure
- Functional boundaries
- Evolution of features
- Evaluation alignment

---

## 4. Architectural Guarantees

The system must provide:

- A Docusaurus-based AI-native textbook
- Deployment via GitHub Pages or Vercel
- Embedded RAG chatbot
- User authentication and profiling
- Personalized chapter transformations
- On-demand Urdu translation

All components must be reproducible and auditable.

---

## 5. Educational Scope

The textbook covers the complete **Physical AI & Humanoid Robotics** curriculum:

- Physical AI & Embodied Intelligence
- ROS 2 (Robotic Nervous System)
- Gazebo & Unity Digital Twins
- NVIDIA Isaac Platform
- Vision-Language-Action (VLA)
- Conversational Robotics
- Sim-to-Real Transfer
- Capstone: Autonomous Humanoid Agent

---

## 6. User-Centric Adaptation

At signup, users provide:
- Software experience
- Hardware availability
- Robotics background

This profile enables:
- Adaptive chapter depth
- Hardware-aware examples
- Progressive difficulty scaling

---

## 7. Ethics & Safety

- No unsafe real-world robotic control code
- Clear separation between simulation and deployment
- No hallucinated APIs, hardware, or benchmarks
- Human oversight is mandatory for physical execution

---

## 8. Non-Goals

This project does not:
- Depend on proprietary AI subscriptions
- Require Claude Code or Anthropic services
- Replace formal robotics certification
- Enable uncontrolled autonomous systems

---

## 9. Evaluation Alignment

This constitution aligns with:
- Panaversity’s AI-native vision
- Hackathon functional requirements
- Open, reproducible AI systems
- Long-term extensibility

---

## 10. Amendments

This constitution may evolve only through:
- Updated specifications
- Explicit change documentation
- Backward compatibility guarantees

---

**This constitution is the governing contract for all specifications and implementations.**
labels: ["constitution", "setup"]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
  - .specify/memory/constitution.md
  - .specify/templates/plan-template.md
tests:
  []
---

## Prompt

{{PROMPT_TEXT}}

## Response snapshot

I have updated the project constitution to version 1.0.0.

Key changes:
- Established new principles: AI-Native by Design, Spec-Driven Development, Gemini-first tooling, and more.
- Updated the plan template to include a constitution checklist.
- Created a Prompt History Record for this update.

Next steps:
- You can now use other /sp.* commands to continue developing your project, which will now be aligned with the new constitution.

## Outcome

- ✅ Impact: The project now has a clear set of guiding principles.
- 🧪 Tests: No tests were run as this was a documentation change.
- 📁 Files: 
  - .specify/memory/constitution.md (updated)
  - .specify/templates/plan-template.md (updated)
  - history/prompts/constitution/001-establish-project-constitution-for-ai-textbook.constitution.prompt.md (created)
- 🔁 Next prompts: /sp.specify, /sp.plan
- 🧠 Reflection: The new constitution provides a solid foundation for the project.

## Evaluation notes (flywheel)

- Failure modes observed: none
- Graders run and results (PASS/FAIL): PASS
- Prompt variant (if applicable): null
- Next experiment (smallest change to try): n/a
