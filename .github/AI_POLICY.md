# AI Policy

**AI assistance is welcomed and encouraged in Locvel projects.** We believe AI tools can accelerate development while maintaining quality when used responsibly.

## Our Philosophy

Locvel was built with AI assistance. We embrace AI as a productivity multiplier, not a replacement for human judgment. The key difference between good AI-assisted contributions and "bot spam" is **understanding and verification**.

## What's Required

When using AI assistance (GitHub Copilot, Claude, GPT-4, Cursor, etc.), you must:

1. **Understand every change** — Read and comprehend the code. Don't blindly copy-paste. You should be able to explain what each function does, why it's structured that way, and what edge cases it handles.

2. **Verify everything works** — Run the code locally. Execute tests. Check for bugs. Confirm it builds. AI can hallucinate dependencies, use deprecated APIs, or introduce subtle bugs. Catch them before submitting.

3. **Take ownership** — You are responsible for the contribution, not the AI. If it breaks something, you fix it. If maintainers ask questions, you answer them in your own words.

4. **Disclose AI use** — Mention in your PR description that AI helped. No need for a disclaimer novel — a simple "Implemented with AI assistance" is enough. This helps maintainers understand your workflow.

5. **Explain your changes** — Write clear commit messages and PR descriptions that show you understand the context. If you can't explain why you made a change, you shouldn't submit it.

## What's Not Allowed

- **Autonomous bot PRs** — Pull requests created entirely by agents without human review will be closed. If you didn't read the code, don't submit it.

- **AI-generated replies to maintainers** — When a maintainer asks a question, answer in your own words. Don't paste ChatGPT responses. We're collaborating with you, not your LLM.

- **Cargo-cult contributions** — Don't submit changes you don't understand just because AI suggested them. "The AI said to do it this way" is not a valid justification.

- **Hallucinated features** — Verify that dependencies, APIs, and syntax actually exist. AI sometimes invents plausible-sounding code that doesn't work.

## Examples of Good AI Use

✅ **"I used Copilot to scaffold the boilerplate, then refactored for our architecture and added tests."**

✅ **"Claude helped me debug the null pointer issue by suggesting I check the lifecycle state before accessing the view."**

✅ **"AI generated the initial regex pattern, but I tested it against our sample data and fixed edge cases it missed."**

✅ **"Used AI to understand the existing codebase architecture before implementing my feature to match the patterns."**

## Examples of Bad AI Use

❌ Pasting 500 lines of AI-generated code you haven't tested or read.

❌ Submitting a PR with "I asked ChatGPT to fix #123" and no understanding of what changed.

❌ Copying AI responses verbatim when maintainers ask you technical questions.

❌ Using AI to mass-generate issues or PRs across multiple repos.

## Why This Policy

We're building privacy-first software. That requires:
- **Security consciousness** — You need to spot when AI suggests insecure patterns
- **Architecture understanding** — You need to maintain consistency with our design principles
- **Ownership mentality** — You need to maintain what you build

AI is your copilot, not your autopilot. Use it to go faster, but keep your hands on the wheel.

## Questions?

If you're unsure whether your AI workflow is appropriate, ask in discussions or via email (hello.locvel@gmail.com). We're here to help you contribute effectively.
