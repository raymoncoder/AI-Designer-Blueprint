# 🧩 Part 2: Prompt Engineering vs. Context Engineering

In 2024, designers obsessed over "magic prompts." In May 2026, **Prompt Engineering is a legacy skill**. The focus has shifted to **Context Engineering**.

- **What is Context Engineering?** 
  It is the art of providing AI agents (like Gemini 3.5 or Antigravity) with structured, comprehensive information about your product so they can make autonomous, accurate decisions.
- **The Context Stack:**
  1. **Brand Identity:** JSON files containing tone of voice, hex codes, typography rules.
  2. **Design System:** Design tokens, component constraints, API hooks.
  3. **User Personas:** Deeply documented pain points, technical literacy, and goals.
  4. **Business Logic:** Edge cases, technical constraints, monetization strategy.

---

## 🛠️ Context Mapping Template

Before starting any design task, fill out this context map for your AI agent.

```markdown
### 🎯 Task Context
- **Primary Goal:** [e.g., Increase conversion on the checkout page]
- **Target Persona:** [e.g., High-income Gen Z, mobile-first]
- **Key Constraints:** [e.g., Must use existing Button components, 2-step max]

### 📜 Rules & Boundaries
- **Brand Tone:** [e.g., Professional yet witty, short sentences]
- **Accessibility:** [e.g., WCAG 3.0 Level AA, dark mode by default]
- **Technical:** [e.g., Next.js 16 components, Tailwind CSS v5]

### 🔗 Reference Assets
- **Design System URI:** [link/path to tokens.json]
- **Previous Research:** [link/path to synthesis_v2.md]
- **Success Metrics:** [e.g., < 3s time-to-completion]
```

**How to Apply It:**
Instead of saying: *"Design a modern login screen,"* you provide the Context Map and say: *"Execute the login flow per our design system, handling the edge cases outlined in auth-rules.md, and ensure the tone matches our enterprise B2B persona."*
