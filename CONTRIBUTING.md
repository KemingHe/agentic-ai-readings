# Contributing

> Updated on 2025-08-23 by @KemingHe

Quick start guide for contributors adding research papers and industry reports to the agentic AI collection.

## Adding Research Papers

**Step-by-step process:**

1. **Verify content quality**
   - [ ] Connects to agentic AI systems or career development  
   - [ ] Recent (2022+) or foundational paper
   - [ ] Peer-reviewed research, established companies, recognized experts  
   - [ ] Text-searchable PDF with clear abstract
   - [ ] Sourced from authoritative sites ([arXiv](https://arxiv.org/), [ACM Digital Library](https://dl.acm.org/), [Google Scholar](https://scholar.google.com/)) for full version lineage

2. **Name file**: `YYYY-MM-descriptive-title-by-author.pdf` (use **first** publishing date, not latest version)

   ```plaintext
   2017-06-attention-is-all-you-need-by-google.pdf  # Original publication date
   ```

3. **Choose directory**:
   - [**`industry-reports/`**](./industry-reports/): Market analysis, trends, workforce insights
   - [**`product-guides/`**](./product-guides/): Product documentation, certification programs  
   - [**`research-ml-llms/`**](./research-ml-llms/): ML/LLM foundations, optimization, best practices
   - [**`research-agentic-systems/`**](./research-agentic-systems/): Multi-agent systems, frameworks, coordination

4. **Generate audio**: Upload PDF → [NotebookLM](https://notebooklm.google.com) → Generate audio/video overview → Save as `.wav`/`.mp4`

5. **Submit PR**: Reference issue or explain added value

## Git Conventions

**Branch**: `<type>/<scope>/<assignee>` → `docs/add-paper-title/username`  
**Commit**: `<type>(<scope>): <description>` → `docs(ml-llms): add transformer paper by Google`

**Types**: `docs`, `fix`, `feat`, `refactor`, `chore`

> [!TIP]
> Use [commit message generation prompt](./prompts/prompt-commit-msg-gen.md) for structured commits.

## Issues & Pull Requests

**Report Issues**: 🔗 Broken links • 📁 Better categorization • 📄 Missing research

**PR Requirements**: ✅ Issue reference • ✅ Proper naming/placement • ✅ PDF+audio pair

**Templates**: [GitHub templates](./.github/) or [AI prompts](./prompts/) for structured content

---

> Contributing Guide Template v1.0.1 - KemingHe/common-devx
