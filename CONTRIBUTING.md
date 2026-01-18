# Contributing to Behavioral Finance Lecture Framework

First off, thank you for considering contributing to this educational project! 🎓

This framework helps educators worldwide teach behavioral finance more effectively. Your contributions—whether big or small—make a real difference in how future professionals understand cognitive biases.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
  - [Reporting Issues](#reporting-issues)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Adding Content](#adding-content)
  - [Improving Visuals](#improving-visuals)
  - [Translations](#translations)
- [Development Guidelines](#development-guidelines)
- [Pull Request Process](#pull-request-process)
- [Recognition](#recognition)

---

## 📜 Code of Conduct

### Our Pledge

We are committed to providing a welcoming and inspiring environment for all contributors, regardless of:
- Experience level (from students to professors)
- Geographic location or cultural background
- Language proficiency
- Academic credentials

### Expected Behavior

- ✅ Use welcoming and inclusive language
- ✅ Respect differing viewpoints and experiences
- ✅ Accept constructive criticism gracefully
- ✅ Focus on what's best for the educational community
- ✅ Show empathy toward other contributors

### Unacceptable Behavior

- ❌ Harassment, trolling, or personal attacks
- ❌ Publishing others' private information
- ❌ Plagiarism or uncredited use of others' work
- ❌ Professional misconduct or unethical behavior

---

## 🤝 How Can I Contribute?

### 🐛 Reporting Issues

Found a problem? Help us improve!

**Before submitting:**
- Search existing issues to avoid duplicates
- Check if it's already been fixed in the latest version

**When submitting an issue:**
```markdown
**Type:** [Bug / Error / Typo / Outdated Info]

**Location:** [File name and section]

**Description:**
[Clear description of the problem]

**Expected vs Actual:**
- Expected: [What should happen]
- Actual: [What actually happens]

**Suggested Fix (optional):**
[Your proposed solution]

**Context:**
- I'm using this for: [Teaching / Self-study / Research]
- My audience: [Students / Professionals / Academics]
```

---

### 💡 Suggesting Enhancements

Have ideas to make this better?

**We're especially interested in:**
- New bias examples (particularly from non-Indian markets)
- Updated research citations (post-2024)
- Interactive teaching techniques
- Assessment tools and rubrics
- Industry-specific adaptations

**Enhancement Template:**
```markdown
**Enhancement Type:** [New Content / Improved Explanation / New Feature]

**Proposal:**
[Clear description of your idea]

**Rationale:**
[Why this would improve the framework]

**Target Audience:**
[Who would benefit most?]

**Implementation Effort:**
[Low / Medium / High - your estimate]

**Example (if applicable):**
[Show what it would look like]
```

---

### 📝 Adding Content

#### New Bias Examples

**We need more examples from:**
- Different countries (US, UK, EU, Asia-Pacific, LATAM, Africa)
- Different asset classes (real estate, commodities, crypto, bonds)
- Different time periods (historical bubbles, recent events)
- Different sectors (tech, pharma, banking, energy)

**Format for new examples:**
```markdown
### [Country/Market]: [Event Name] ([Year])

**Bias Demonstrated:** [Primary bias + secondary biases]

**Timeline:**
- [Date]: [What happened]
- [Date]: [What happened]
- [Date]: [Outcome]

**Data:**
- Metric 1: [Value]
- Metric 2: [Value]
- Impact: [Quantified loss/gain]

**Teaching Point:**
[What students should learn from this]

**Source:**
[Citation with link if available]
```

**Example:**
```markdown
### USA: GameStop Short Squeeze (2021)

**Bias Demonstrated:** Herd Behavior + Recency Bias + Overconfidence

**Timeline:**
- Jan 2021: Reddit r/WallStreetBets identifies high short interest
- Jan 27: Stock price $147 → $347 in one day
- Jan 28: Peak at $483
- Feb 2021: Crashes to $40-50 range

**Data:**
- Peak price: $483 (Jan 28)
- Starting price: ~$20 (Jan start)
- Return to: ~$40 within weeks
- Retail participation: Millions of new Robinhood accounts

**Teaching Point:**
Social media can create informational cascades at unprecedented speed.
Late entrants (buying above $300) lost 80-90% as herd reversed.

**Source:**
SEC (2021). Staff Report on Equity and Options Market Structure Conditions.
https://www.sec.gov/files/staff-report-equity-options-market-struction-conditions-early-2021.pdf
```

#### New Research Citations

**When adding academic papers:**
- Include full citation (APA format)
- Add 2-3 sentence summary of key findings
- Explain relevance to lecture framework
- Link to DOI or public access version if available

---

### 🎨 Improving Visuals

**We welcome:**
- Actual diagram files (PNG, SVG, PDF)
- PowerPoint/Google Slides templates
- Interactive web visualizations
- Infographics
- Animated GIFs or videos
- Mermaid diagram code

**Visual Contribution Checklist:**
- [ ] Matches the specification in VISUAL_DIAGRAMS_GUIDE.md
- [ ] Uses accessible color schemes (color-blind friendly)
- [ ] Includes source files (editable formats)
- [ ] High resolution (300 DPI minimum for print)
- [ ] Labeled clearly with figure numbers
- [ ] Includes attribution if using external data

**File Naming Convention:**
```
diagram_[number]_[name]_[format].[ext]

Examples:
diagram_01_prospect_theory_curve.png
diagram_03_bias_interaction_web.svg
diagram_05_three_levels_framework.pdf
```

---

### 🌍 Translations

**Help make this accessible globally!**

**Priority Languages:**
- Hindi (Indian context already available)
- Spanish (LATAM markets)
- Mandarin (Chinese markets)
- Portuguese (Brazil markets)
- Arabic (Middle East markets)
- French (African + European markets)

**Translation Guidelines:**
1. **Don't just translate—localize:**
   - Replace Indian examples with local equivalents
   - Use local currency
   - Reference local market indices
   - Cite local regulations

2. **Maintain academic rigor:**
   - Keep research citations intact
   - Don't simplify technical terms incorrectly
   - Preserve numerical accuracy

3. **File structure:**
   ```
   /translations/
     /es/  (Spanish)
       README_es.md
       QUICK_REFERENCE_es.md
       VISUAL_DIAGRAMS_GUIDE_es.md
     /zh/  (Mandarin)
       README_zh.md
       ...
   ```

4. **Translation completeness:**
   - Translate ALL markdown files
   - Update examples to local context
   - Add translator attribution
   - Note any cultural adaptations made

---

## 🛠️ Development Guidelines

### Content Standards

**Writing Style:**
- Clear, concise, accessible
- Academic without being pedantic
- Use active voice
- Define jargon on first use
- Include concrete examples

**Formatting:**
- Use markdown correctly (headers, lists, tables)
- Include emojis for visual navigation
- Break long sections with subheadings
- Use code blocks for scripts/quotes
- Add links to external resources

**Citations:**
- Always cite sources for data/claims
- Use APA format for academic papers
- Link to publicly accessible versions when possible
- Distinguish between primary research and commentary

### Technical Guidelines

**For Code Contributions:**
```python
# If contributing Python scripts for data analysis or visualization:
# - Use Python 3.8+
# - Include requirements.txt
# - Add docstrings
# - Follow PEP 8 style guide
# - Include example usage
```

**For Markdown:**
- Use consistent header levels
- Tables should be readable in plain text
- Test links before submitting
- Use relative links for internal references

---

## 🔄 Pull Request Process

### Before You Submit

1. **Search existing PRs** to avoid duplicates
2. **Test your changes** (if code/scripts)
3. **Proofread carefully** (typos matter in education!)
4. **Update documentation** if you've added features
5. **Add yourself to CONTRIBUTORS.md** (see Recognition section)

### PR Template

```markdown
## Description
[Clear description of what you're contributing]

## Type of Change
- [ ] Bug fix (typo, broken link, error correction)
- [ ] New content (example, case study, research citation)
- [ ] Enhancement (improved explanation, better formatting)
- [ ] Visual (diagram, chart, infographic)
- [ ] Translation (new language or localization)
- [ ] Documentation (README, guides, tutorials)

## Checklist
- [ ] I've tested my changes (if applicable)
- [ ] I've proofread for spelling/grammar
- [ ] I've added proper citations for new content
- [ ] I've followed the style guidelines
- [ ] I've added myself to CONTRIBUTORS.md

## Additional Context
[Any other information reviewers should know]

## Screenshots (if visual changes)
[Attach before/after images if relevant]
```

### Review Process

1. **Automated checks:** Basic markdown linting
2. **Maintainer review:** Content quality and fit
3. **Community feedback:** Others can comment
4. **Approval:** At least one maintainer approval needed
5. **Merge:** Maintainer merges your contribution

**Typical timeline:** 3-7 days for review

---

## 🏆 Recognition

### Contributors List

All contributors are acknowledged in **CONTRIBUTORS.md**:

```markdown
## Contributors

### Original Author
- **RK** - Initial framework development, Indian context adaptation

### Content Contributors
- **[Your Name]** - [Your contribution]
  - Added GameStop example (2024)
  - Improved anchoring bias explanation
  - GitHub: [@yourusername]

### Visual Contributors
- **[Your Name]** - [Your contribution]
  - Created Prospect Theory diagram
  - Designed slide templates

### Translation Contributors
- **[Your Name]** - [Language] translation
  - Spanish localization with LATAM examples
```

### How to Add Yourself

When submitting a PR, add yourself to CONTRIBUTORS.md:

```markdown
### Content Contributors
- **[Your Name]** - [Brief description of contribution]
  - [Specific addition 1]
  - [Specific addition 2]
  - Contact: [GitHub/LinkedIn/Email - optional]
  - Affiliation: [University/Company - optional]
```

### Special Recognition

**Significant contributions may be recognized via:**
- Co-authorship credit (for major additions/revisions)
- Featured in README.md acknowledgments
- Invited to collaborate on future versions
- Academic citation (for research-level contributions)

---

## 📊 What We're Looking For

### High Priority

- ✅ Examples from **non-Indian markets** (currently limited)
- ✅ **Recent events** (2023-2026) demonstrating biases
- ✅ **Visual diagrams** (specs provided, need actual files)
- ✅ **Assessment tools** (quizzes, rubrics, worksheets)
- ✅ **Video content** (recorded lectures, animations)

### Medium Priority

- ⚠️ Improved explanations of existing content
- ⚠️ Additional teaching techniques
- ⚠️ Industry-specific adaptations (fintech, banking, insurance)
- ⚠️ Student feedback integration

### Lower Priority (but still welcome!)

- 📋 Typo fixes
- 📋 Formatting improvements
- 📋 Broken link repairs

---

## ❓ Questions?

**Not sure if your contribution fits?** 
- Open an issue first with the `question` label
- Describe what you want to contribute
- Ask for feedback before investing time

**Need help getting started?**
- Check out GitHub's [guide to contributing](https://docs.github.com/en/get-started/quickstart/contributing-to-projects)
- Look at existing PRs for examples
- Reach out via issues with `help wanted` label

**Technical problems?**
- Include error messages
- Describe what you tried
- Share your environment (OS, browser, tools)

---

## 🌟 Why Contribute?

Your contributions help:
- **Educators** teach more effectively
- **Students** understand complex concepts better
- **Professionals** make better financial decisions
- **Researchers** build on this framework
- **Global community** access quality education

Even small contributions (fixing a typo, adding an example) make this resource better for thousands of learners worldwide.

---

<div align="center">

**Thank you for contributing to financial literacy education! 🎓**

*Every contribution, no matter how small, makes a difference.*

**Questions?** Open an issue with the `question` label  
**Ready to contribute?** Fork the repo and submit a PR!

</div>

---

**Last Updated:** January 2026  
**Maintained by:** RK and community contributors
