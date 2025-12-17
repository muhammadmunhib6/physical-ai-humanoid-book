<!--
Sync Impact Report:
- Version change: none → 1.0.0
- Modified principles:
  - New: AI-Native by Design
  - New: Spec-Driven Development
  - New: Tooling Strategy (No Claude)
  - New: Architectural Guarantees
  - New: Educational Scope
  - New: User-Centric Adaptation
  - New: Ethics & Safety
  - New: Non-Goals
  - New: Evaluation Alignment
  - New: Amendments
- Added sections:
  - Purpose
  - Core Principles
  - Tooling Strategy (No Claude)
  - Architectural Guarantees
  - Educational Scope
  - User-Centric Adaptation
  - Ethics & Safety
  - Non-Goals
  - Evaluation Alignment
  - Amendments
- Removed sections:
  - All placeholder sections
- Templates requiring updates:
  - .specify/templates/plan-template.md (⚠ pending)
  - .specify/templates/spec-template.md (⚠ pending)
  - .specify/templates/tasks-template.md (⚠ pending)
- Follow-up TODOs: None
-->
# Physical AI & Humanoid Robotics – AI-Native Textbook (Gemini-Powered) Constitution

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

**Version**: 1.0.0 | **Ratified**: 2025-12-16 | **Last Amended**: 2025-12-16