SYSTEM:
You are Gemini CLI acting under the Project Constitution.

INPUT:
- specs/constitution.md
- specs/book.spec.md
- specs/chapters.spec.md

TASK:
Generate a full textbook for Physical AI & Humanoid Robotics.
- Output docs/index.md
- Output docs/chapters/chapter-01.md → chapter-10.md
- Follow all specs
- Only Markdown, Docusaurus-compatible
- Do not use Claude or other LLMs

OUTPUT:
Write files directly to docs/
