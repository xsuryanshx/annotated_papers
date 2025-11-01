# Contributing Guidelines

Thank you for your interest in contributing to this annotated papers repository!

## 📝 How to Add a Paper

### Step 1: Choose the Right Category

Select the most appropriate category for your paper:
- `machine_learning/` - Traditional ML algorithms, statistical learning
- `deep_learning/` - Neural networks, architectures, training techniques
- `natural_language_processing/` - Language models, NLP tasks
- `computer_vision/` - Image processing, object detection, vision models
- `reinforcement_learning/` - RL algorithms, policy optimization
- `misc/` - Papers that don't fit other categories

### Step 2: Create Paper Folder

Create a folder using this naming convention:
```
Author_Year_ShortTitle
```

**Examples**:
- `Vaswani_2017_Attention`
- `He_2016_ResNet`
- `Brown_2020_GPT3`

### Step 3: Use the Template

1. Copy `templates/PAPER_TEMPLATE.md` to your paper folder as `README.md`
2. Fill in all sections with your annotations
3. Be thorough but concise

### Step 4: Add Supporting Materials

Optionally add:
- `paper.pdf` - Original paper (check copyright)
- `notes.md` - Additional detailed notes
- `images/` - Figures, diagrams, your own visualizations
- `code/` - Implementation snippets or experiments

### Step 5: Update the Index

Add an entry to `PAPERS_INDEX.md` under the appropriate category:

```markdown
| [Paper Title](./papers/category/Author_Year_Title) | Author et al. | 2024 | ✅ | [arXiv](link) |
```

## ✅ Quality Guidelines

### Annotations Should Include

- **Clear summary** of the paper's main ideas
- **Key contributions** and innovations
- **Critical analysis** - strengths and limitations
- **Personal insights** - what you learned, how it connects to other work
- **Practical notes** - implementation details, reproducibility

### Writing Style

- Use clear, concise language
- Include code snippets or pseudocode where helpful
- Add visual diagrams to explain complex concepts
- Link to related papers and resources
- Use proper markdown formatting

### What to Avoid

- Copying large sections verbatim (summarize instead)
- Being too vague or superficial
- Ignoring limitations or critical analysis
- Forgetting to update PAPERS_INDEX.md

## 📂 File Structure Example

```
papers/deep_learning/Vaswani_2017_Attention/
├── README.md           # Main annotation (from template)
├── paper.pdf           # Original paper (optional)
├── notes.md            # Extended notes
└── images/
    ├── architecture.png
    └── attention_viz.png
```

## 🔍 Review Checklist

Before considering your annotation complete:

- [ ] All template sections are filled out
- [ ] Key contributions are clearly listed
- [ ] Personal insights and critical analysis included
- [ ] Related papers are linked
- [ ] PAPERS_INDEX.md is updated
- [ ] Proper formatting (headings, lists, code blocks)
- [ ] Tags are added for discoverability

## 🤝 Suggesting Papers

To suggest a paper for annotation:

1. Open an issue with title: "Paper Suggestion: [Paper Title]"
2. Include:
   - Paper link (arXiv, conference, journal)
   - Brief description of why it's interesting
   - Relevant category
   - Any connections to existing papers

## 📧 Questions?

Open an issue for any questions about contributing or the annotation process.

---

**Remember**: The goal is to create a valuable knowledge base that helps future you (and others) understand and remember important papers!
