# 📜 Global Rules: Enterprise B2B SaaS
*Example of global Context Rules*

These rules should be passed as context to your AI agent before any design generation or code generation tasks.

1. **Never use destructive actions without confirmation.** All 'Delete', 'Remove', or 'Archive' actions must trigger a modal or toast with an 'Undo' option.
2. **Data-heavy layouts.** Use condensed typography (Geist Mono for numbers) and tight padding (e.g., `py-1 px-2`) for data tables to maximize vertical space.
3. **Primary Action Color.** The global brand primary color is `#0F172A` (Slate 900). Never use pure `#000000`.
4. **Error Handling.** Error states must always explain *how to fix* the issue, not just what went wrong (e.g., "Invalid API Key. Generate a new key in Settings -> Developers").
