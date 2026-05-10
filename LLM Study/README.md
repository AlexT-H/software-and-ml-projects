# LLM Study

## Overview

This project is a language-generation study that creates output text from a source text file using character-sequence modeling. The user can control parameters such as sequence length, output length, and randomization seed.

The project demonstrates text processing, simple language modeling, user-configurable generation, and analysis of how model behavior changes based on parameter selection.

---

## Project Goal

The goal was to explore how character-sequence length affects generated text quality.

At low sequence lengths, generated text becomes more random and less readable. At higher sequence lengths, output becomes more coherent but may begin to overfit and replicate the source text.

---

## Skills Demonstrated

- Python programming
- Text processing
- File I/O
- Character-sequence modeling
- Basic language generation
- Parameterized program design
- Experimental analysis

---

## Project Structure

```text
LLM Study/
├── examples/
├── aesop_3.txt
├── aesop_5.txt
├── aesop_7.txt
├── aesop_10.txt
├── main.py
├── processing.py
└── README.md
```

---

## How to Run

Run:

```bash
python main.py
```

The program prompts for:

1. `n` value, which controls character-sequence length
2. input text file
3. output file name
4. desired output character count
5. randomization seed

The generated output is saved to the project folder.

---

## Key Observations

- Very low `n` values tend to produce illegible output.
- Mid-range values begin forming recognizable words and phrases.
- Higher values produce more coherent output but may replicate source text too closely.
- The model demonstrates the tradeoff between randomness, coherence, and overfitting.

---

## Future Improvements

- Add token-based modeling rather than character-only modeling.
- Add grammar-aware post-processing.
- Add sentence-boundary handling.
- Add part-of-speech or phrase-level constraints.
- Add comparisons between generated outputs across parameter settings.

---

## Portfolio Relevance

This project demonstrates foundational AI/NLP experimentation and shows the ability to build configurable text-processing tools from scratch.
