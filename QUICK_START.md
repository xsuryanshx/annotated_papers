# Quick Start Guide

Get started with annotating papers in 5 minutes!

## 🚀 Adding Your First Paper

### 1. Pick a Category

Choose from:
- `papers/machine_learning/`
- `papers/deep_learning/`
- `papers/natural_language_processing/`
- `papers/computer_vision/`
- `papers/reinforcement_learning/`
- `papers/misc/`

### 2. Create a Folder

Name format: `Author_Year_ShortTitle`

```bash
cd papers/deep_learning/
mkdir Vaswani_2017_Attention
cd Vaswani_2017_Attention
```

### 3. Copy the Template

```bash
cp ../../../templates/PAPER_TEMPLATE.md README.md
```

### 4. Fill It Out

Edit `README.md` with:
- Paper metadata (title, authors, year, link)
- Summary of the paper
- Key contributions
- Your personal insights and notes
- Related papers

### 5. Update the Index

Add a line to `PAPERS_INDEX.md` under the appropriate category:

```markdown
| [Attention Is All You Need](./papers/deep_learning/Vaswani_2017_Attention) | Vaswani et al. | 2017 | ✅ | [arXiv](https://arxiv.org/abs/1706.03762) |
```

### 6. Commit

```bash
git add .
git commit -m "Add Vaswani 2017 - Attention Is All You Need"
git push
```

## 📚 Example Paper

Check out the example at `papers/deep_learning/Example_2024_PaperAnnotation/` to see a complete annotation.

## 💡 Tips

- **Be consistent** - Use the template for every paper
- **Add personal insights** - Don't just summarize, analyze!
- **Link related papers** - Build connections
- **Update regularly** - Add papers as you read them
- **Use tags** - Makes searching easier later

## 📖 More Information

- [README.md](README.md) - Full repository documentation
- [CONTRIBUTING.md](CONTRIBUTING.md) - Detailed guidelines
- [templates/PAPER_TEMPLATE.md](templates/PAPER_TEMPLATE.md) - The template

---

**Ready to start?** Pick a paper and begin annotating! 🎉
