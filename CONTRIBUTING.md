# Contributing to Awesome GenAI Papers

Thank you for your interest in contributing to this curated list of Generative AI research.

I welcome milestone papers and a small number of complementary learning resources. Paper contributions must follow the table format below; courses, tutorials, and lectures belong in the separate Learning Resources section.

## How to Add a Paper

### 1. The PR Workflow
1. **Fork the repository**.
2. **Create a new branch** (`git checkout -b add-paper-title`).
3. **Make your edits** to `README.md` following the exact template below.
4. **Submit a Pull Request** with a brief explanation of why this paper is a milestone or highly relevant.

### 2. The Exact Entry Format

Add your paper as a new row in the relevant category table in `README.md`. Copy and paste the following structure, replacing the bracketed text:

```markdown
| [YYYY] | [Paper Title](URL) | [1-2 sentence description.] <br><br> _"[Optional short quote or key takeaway]"_ |
```

**Example:**
```markdown
| 2026 | [EsoLang-Bench: Evaluating Genuine Reasoning...](https://arxiv.org/abs/2603.09678) | Large language models perform well on standard coding tests due to memorization... <br><br> _"By using direct interpreter feedback and iterative execution..."_ |
```

### 3. Category Rules

Place the paper under one of the six categories:
- **Reasoning, Intelligence & Robustness**: evaluations, model logic, failure modes, capabilities.
- **Prompt Engineering & Optimization**: frameworks, prompting techniques, optimization systems.
- **Alignment & Safety**: red-teaming, jailbreaks, trust, bias, emergent behaviors.
- **Agents & Tool Use**: multi-agent systems, tool-calling, autonomous execution.
- **Architectures & Base Models**: attention mechanisms, state-space models, pre-training.
- **Emerging Topics & Miscellaneous**: everything else that doesn't fit above (e.g. quantum AI, new modalities).

### 4. Quality Guidelines

- **High Quality**: Papers must be significant milestones or highly relevant to the GenAI ecosystem. Avoid highly niche or low-effort preprints.
- **Concise Descriptions**: Keep the description to 1-2 plain English sentences. Explain *what* it does and why it matters.
- **Provide Context**: Only if there is a genuinely impactful quote or takeaway, append it with `<br><br> _"Quote text"_`. If there is no standout insight, omit the quote entirely.
- **Working Links**: Ensure your link resolves correctly to the paper (e.g., arXiv, Nature, or the primary blog post).

## How to Suggest a Learning Resource

Use a pull request with a brief explanation of the resource's value and its overlap with existing entries.

- Preserve the order of the 14-step foundations path unless the change includes a pedagogical reason. Do not expand it to an author's entire catalog by default.
- For deep dives and practice, follow the existing `Resource | Starting point | Why choose it` table. Name prerequisites, a useful chapter or lecture, and the course edition when relevant.
- Prefer freely accessible original resources and official companion code. Link directly to the selected material rather than a generic channel or course marketplace.
- Explain what the resource adds. Avoid duplicate introductions, promotional lists, personal completion claims, and private course or application materials.
- Keep learning entries separate from the six paper categories. They are curated by learning order or purpose, not by publication year; paper formatting and category rules remain unchanged.
- Check links and descriptions, and keep descriptions concise and in English.

Thanks for contributing.
