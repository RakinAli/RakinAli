## Rakin Ali

Building [Vetnio](https://vetnio.com) — AI clinical documentation for veterinarians. Stockholm.

I work end to end — product, backend, infrastructure and the model layer. Day to day that means
TypeScript and Python, AWS, Stripe, database schema design, and LLM systems in production.

Before Vetnio: MSc in Machine Learning at KTH. My thesis trained **sparse autoencoders** on
GPT-2 MLP activations to pull dense representations apart into sparse, interpretable features —
sweeping latent width from 512 to 4096 against the L1 penalty, then reading out top-activating
tokens per latent to see what each one had actually learned.

---

### What I spend time on

**LLM systems in production.** Structured generation, speech-to-text, and the harnesses that
keep model output trustworthy enough to put in front of professionals.

**Speech.** Speaker diarization, ASR, speech and speaker recognition — the thread most of the
public work below runs along.

**Interpretability.** Sparse autoencoders and feature decomposition. The research question I
keep coming back to.

---

### Stack

- **Daily** — TypeScript · Python · React · Node · PostgreSQL · AWS
- **Modelling** — PyTorch · NumPy · Hugging Face · Weights & Biases
- **Also fluent in** — Java · C++ · SQL · Docker · GitHub Actions

---

### Public repositories

Day-to-day work at Vetnio is private. What's public is the machine learning and speech work
from KTH — written from scratch, not wired together from libraries.

| Repo | What it is |
|---|---|
| [Deep-Learning](https://github.com/RakinAli/Deep-Learning) | Neural networks from scratch in NumPy. One-layer → k-layer with batch normalization, a char-level RNN trained with AdaGrad, and a VGG/ResNet CIFAR-10 project past 90%. Gradients hand-derived, no autograd. |
| [Diarization---Project](https://github.com/RakinAli/Diarization---Project) | Speaker diarization on VoxData. Benchmarked state-of-the-art embedding models against each other, then built a custom diarization model and compared clustering strategies. |
| [Speaker-and-Speech](https://github.com/RakinAli/Speaker-and-Speech) | DT2119 Speech and Speaker Recognition. MFCC feature extraction, HMM alignment and concatenation, and phoneme recognition. |
| [NLP-Course](https://github.com/RakinAli/NLP-Course) | Language engineering, implemented rather than imported: CKY parsing, transition-based dependency parsing, n-gram language models, NER, random indexing, word2vec/GloVe, char-level LMs and neural machine translation. |
| [Computer-Vision-course](https://github.com/RakinAli/Computer-Vision-course) | Image analysis and computer vision. Fourier analysis and Gaussian filtering, edge detection, and segmentation via k-means, mean-shift and graph cuts. |
| [Text-summarizer](https://github.com/RakinAli/Text-summarizer) | Abstractive summarization on the wikiHow corpus — T5 fine-tuning, evaluation and an interactive demo. |
| [AI-course](https://github.com/RakinAli/AI-course) | Classical AI: search and heuristics, logic-based knowledge representation, HMMs and Bayesian inference, planning and decision theory. |
| [TSP-Problem](https://github.com/RakinAli/TSP-Problem) | Traveling salesman heuristics in C++ under a hard runtime budget on Kattis — greedy construction plus 2-opt local search. |

---

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/rakin-ali/) · [rakin@vetnio.com](mailto:rakin@vetnio.com)
