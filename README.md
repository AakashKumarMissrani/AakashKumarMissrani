<div align="center">

<!-- Animated header -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=700&lines=sindhinltk+%F0%9F%87%B5%F0%9F%87%B0;Sindhi+NLP+Toolkit;%D8%B3%D9%86%DA%8C%DA%BE%D9%8A+%D9%B9%DA%AA%D9%86%D8%A7%D9%84%D8%A7%D8%AC%D9%8A;First+Open-Source+Sindhi+NLP" alt="Typing SVG" />

<br/>

<!-- Badges row 1 -->
[![PyPI](https://img.shields.io/pypi/v/sindhinltk?style=for-the-badge&logo=pypi&logoColor=white&color=0073b7&labelColor=0d1117)](https://pypi.org/project/sindhinltk/)
[![PyPI Downloads](https://img.shields.io/pypi/dm/sindhinltk?style=for-the-badge&logo=pypi&logoColor=white&color=00c853&labelColor=0d1117)](https://pypi.org/project/sindhinltk/)
[![Python](https://img.shields.io/pypi/pyversions/sindhinltk?style=for-the-badge&logo=python&logoColor=white&color=ffd43b&labelColor=0d1117)](https://pypi.org/project/sindhinltk/)
[![License](https://img.shields.io/badge/license-MIT-red?style=for-the-badge&logo=opensourceinitiative&logoColor=white&labelColor=0d1117)](LICENSE)

<!-- Badges row 2 -->
[![GitHub Stars](https://img.shields.io/github/stars/AakashKumarMissrani/SindhiNLTK?style=for-the-badge&logo=github&logoColor=white&color=f9c513&labelColor=0d1117)](https://github.com/AakashKumarMissrani/SindhiNLTK/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/AakashKumarMissrani/SindhiNLTK?style=for-the-badge&logo=github&logoColor=white&color=9b59b6&labelColor=0d1117)](https://github.com/AakashKumarMissrani/SindhiNLTK/forks)
[![Issues](https://img.shields.io/github/issues/AakashKumarMissrani/SindhiNLTK?style=for-the-badge&logo=github&logoColor=white&color=e74c3c&labelColor=0d1117)](https://github.com/AakashKumarMissrani/SindhiNLTK/issues)
[![HuggingFace](https://img.shields.io/badge/🤗%20HuggingFace-aakashMeghwar01-ff6b35?style=for-the-badge&labelColor=0d1117)](https://huggingface.co/aakashMeghwar01)

<br/>

```
 ░██████╗██╗███╗░░██╗██████╗░██╗░░██╗██╗
 ██╔════╝██║████╗░██║██╔══██╗██║░░██║██║
 ╚█████╗░██║██╔██╗██║██║░░██║███████║██║
 ░╚═══██╗██║██║╚████║██║░░██║██╔══██║██║
 ██████╔╝██║██║░╚███║██████╔╝██║░░██║██║
 ╚═════╝░╚═╝╚═╝░░╚══╝╚═════╝░╚═╝░░╚═╝╚═╝
        ███╗░░██╗██╗░░░░░████████╗██╗░░██╗
        ████╗░██║██║░░░░░╚══██╔══╝██║░██╔╝
        ██╔██╗██║██║░░░░░░░░██║░░░█████═╝░
        ██║╚████║██║░░░░░░░░██║░░░██╔═██╗░
        ██║░╚███║███████╗░░░██║░░░██║░╚██╗
        ╚═╝░░╚══╝╚══════╝░░░╚═╝░░░╚═╝░░╚═╝
```

**The first open-source Python NLP library for the Sindhi language — built by a computational linguist, for the world.**

[📦 PyPI](https://pypi.org/project/sindhinltk/) · [🤗 HuggingFace](https://huggingface.co/aakashMeghwar01) · [📊 Dataset](https://huggingface.co/datasets/aakashMeghwar01/sindhi-corpus-505m) · [🐛 Issues](https://github.com/AakashKumarMissrani/SindhiNLTK/issues)

</div>

---

## 👤 Author

<div align="center">

**Aakash Meghwar** — Computational Linguist · NLP Engineer · Low-Resource Language Advocate

[![GitHub](https://img.shields.io/badge/GitHub-AakashKumarMissrani-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AakashKumarMissrani)
[![HuggingFace](https://img.shields.io/badge/🤗-aakashMeghwar01-ff6b35?style=for-the-badge)](https://huggingface.co/aakashMeghwar01)

*Building NLP infrastructure for the 80 million Sindhi speakers who deserve better tools.*

</div>

---
---

## ⚡ Why sindhinltk?

Sindhi is spoken by **~80 million people** yet has virtually zero open-source NLP tooling. This library changes that.

| | sindhinltk | General NLP libs |
|---|---|---|
| Sindhi Arabic script | ✅ Native | ❌ Broken / mangled |
| Zero dependencies | ✅ Pure Python | ❌ Heavy installs |
| Morpheme-aware stemmer | ✅ Sindhi suffix rules | ❌ Not available |
| Sindhi stopwords | ✅ 143 words, 10 categories | ❌ Not available |
| Sentiment in Sindhi | ✅ Labels in سنڌي | ❌ Not available |
| Diacritic handling | ✅ Full harakat support | ❌ Not available |

---

## 🚀 Install

```bash
pip install sindhinltk
```

No dependencies. No model downloads. It just works.

---
---

## 📦 Module Reference

| Module | Class | Key Methods |
|--------|-------|-------------|
| `tokenizer` | `SindhiTokenizer` | `tokenize(text)` · `sent_tokenize(text)` |
| `normalizer` | `SindhiNormalizer` | `normalize(text, remove_diacritics=False)` |
| `stemmer` | `SindhiStemmer` | `stem(word)` · `stem_tokens(tokens)` |
| `stopwords` | `SindhiStopwords` | `remove_stopwords(tokens)` · `is_stopword(word)` · `get_stopwords(category)` · `get_categories()` |
| `sentiment` | `SindhiSentiment` | `analyze(text)` · `score(text)` · `analyze_detail(text)` |
| `datasets` | `SindhiDatasets` | `load(name)` · `list()` · `load_stopwords()` · `load_sentiment_lexicon()` |

---

## 🗂️ Bundled Data Assets

```python
from sindhinltk.datasets import SindhiDatasets
ds = SindhiDatasets()

ds.list()
# → ['stopwords', 'sentiment_lexicon']

sw  = ds.load_stopwords()          # dict: {category → [words]}
lex = ds.load_sentiment_lexicon()  # dict: {positive, negative, intensifiers, negators}
```

---

## 🏗️ Corpus & Models

| Resource | Description | Link |
|----------|-------------|------|
| **Sindhi Corpus 505M** | 742K docs · ~505M tokens · 11 sources | [🤗 Dataset](https://huggingface.co/datasets/aakashMeghwar01/sindhi-corpus-505m) |
| **SindhiLM Tokenizer v1** | BPE · merged into Qwen2.5 · 7,978 Sindhi tokens | [🤗 Model](https://huggingface.co/aakashMeghwar01/SindhiLM-Tokenizer-v1) |
| **SindhiLM Tokenizer v2** | Morpheme-aware BPE · 4,571 cleaner tokens | 🔜 Coming Soon |

---

## 🧠 Linguistic Notes

- **Script**: Sindhi uses the **Naskh Arabic script** with unique letters: `ڄ ڃ ٻ ڦ ڳ ڱ ڻ ڏ ڊ ٺ ٽ ڇ ڦ`
- **Morphology**: Agglutinative verb system — a single verb root can generate 40+ surface forms via suffixation
- **Diacritics**: Harakat marks (zabar, zer, pesh) are common in formal/religious text — the normalizer handles all of them
- **RTL**: Full right-to-left support throughout the library

---

## 📈 Changelog

| Version | Changes |
|---------|---------|
| `1.3.1` | Fix stemmer MIN_STEM, MIT license, full README |
| `1.3.0` | Real stemmer, stopwords, sentiment, datasets module |
| `1.2.3` | SindhiNLTK package restructure |
| `1.1.0` | Expanded stopwords (168 words), datasets module |

---

## 🤝 Contributing

PRs welcome — especially for:
- Expanding the sentiment lexicon
- Adding more morphological rules to the stemmer
- Named entity recognition (NER) for Sindhi
- POS tagger

```bash
git clone https://github.com/AakashKumarMissrani/SindhiNLTK.git
cd SindhiNLTK
pip install -e .
python -m pytest
```

## 📄 License

MIT © Aakash Meghwar

---

<div align="center">

**If this helped your research or project, consider giving it a ⭐**

Made with ❤️ for the Sindhi language

</div>
