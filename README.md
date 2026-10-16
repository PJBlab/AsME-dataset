# AsME: Assamese Mathematical Entity dataset
The dataset was curated from standard secondary school mathematics textbooks (Class IX and X) prescribed by the Board of Secondary Education, Assam (SEBA). It aims to bridge the gap in NLP resources for mathematical content processing in low-resource Indo-Aryan languages (targeted for Assamese).

# Key Features
Domain-Specific: Focused entirely on mathematical discourse in Assamese.

Source-Grounded: Extracted from official SEBA pedagogy to ensure curriculum alignment.

Linguistic Nuance: Designed to handle Assamese-specific challenges like inflectional morphology and semantic ambiguity.

Benchmarked: Evaluated using MuRIL, BERT, and other transformer architectures.

# Dataset Schema

The dataset is provided in a standard 4-column format suitable for NER tasks:

1. **Sl.** for	'Serial Number'.
2. **Text** for 'The full sentence/context extracted from the textbook'.
3. **ME** for	'The specific Mathematical Entity identified within the text'.
4. **Label** for	'The category assigned to the entity'(see Taxonomy below).

# Entity Taxonomy (6 Labels)

We follow a strict protocol to balance linguistic specificity with domain coverage:

1. **CMT** (Common Math Terms): Conceptual terms (e.g., পূৰ্ণ-সংখ্যা, সংখ্যা-মালা).
2. **OS** (Operators & Symbols): Arithmetic operations and symbols (e.g., বিয়োগ, +, ₹).
3. **N** (Numeric Terms): Words or digits representing numbers (e.g., একৈশ, ৫).
4. **GS** (Geometry & Shapes): Terms for shapes and graphs (e.g., ত্ৰিভুজ, দণ্ডচিত্ৰ).
5. **FF** (Functions & Formulae): Complex identities and equations (e.g., $sin^2\theta + cos^2\theta = 1$).
6. **U** (Units): Standard measurements (e.g., গ্ৰাম, মিটাৰ).

## Cite as:

**P. J. Baruah, A. Paul and V. S. Snehal, "Named Entity Recognition for Mathematical Texts using Transformer-Based Encoders for Assamese with Corpus Creation," 2026 IEEE Guwahati Subsection Conference (GCON), Guwahati, India, 2026, pp. 1-6, doi: 10.1109/GCON69192.2026.11648964.**

