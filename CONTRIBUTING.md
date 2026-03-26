# Contributing to Awesome GenAI Papers

Thank you for your interest in contributing to this curated list of Generative AI research.

I welcome additions that improve and grow the collection of milestone and highly-relevant papers. Because the list relies on a specific Markdown Table format to remain highly readable, please follow the strict formatting rules below when submitting a Pull Request.

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

Thanks for contributing.
