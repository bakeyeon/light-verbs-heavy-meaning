# Light Verbs, Heavy Meaning?
Exploring Informativity, Frequency and Morpho-Syntactic Interface of Simplex Verbs and 'root+hata' Light Verb Constructions in Korean  

This research was developed for the MA module "Linguistic Typology and Fieldwork" (Seminar: Linearisierung / Linearization, SS26). 
The paper examines Polinsky and Magyar's (2020) informativity account on head-final lexicons by probing the computational geometry and corpus distribution of Korean predicate pairs. I appreciate your understanding regarding its preliminary nature and welcome any inquiries or academic discussions related to this work.  

- Author: Kai H. Park (Ms)
- Evaluator: Dr. Andreas Blümel at Georg-August-Universität Göttingen. 

## Abstract
Polinsky and Magyar (2020) propose that head-final languages favor low-informativity simplex verbs and expand their verbal lexicon through light verb constructions (LVCs). This study tests whether Korean simplex verbs are systematically more polysemous, less contextually stable (lower self-similarity), and more frequent than their counterpart root+hata light verb constructions across concept-controlled minimal pairs.  

Using empirical measures—lexicographic sense counts from two official dictionaries (STDICT, Urimalsaem), contextual embedding self-similarity across three architectures (KLUE-BERT, KcBERT, Vertex AI dense embeddings) and two registers (dictionary examples vs. NSMC), and corpus frequency across spoken (KoFREN) and informal written (NSMC) data—the hypothesis is evaluated alongside a syntactic baseline analyzing hata as a semantically transparent $v$ head selecting a root phrase ($\sqrt{ }\text{P}$).  

Across 38 testable conditions, the predicted asymmetry holds in 58% of comparisons, being driven entirely by specific items (sing, cook) while failing or reversing in others (vomit, think, warm). The findings argue against a deterministic informativity constraint in Korean word-formation, demonstrating that the semantic breadth of root+hata predicates is largely inherited from the communicative versatility of their immobilized roots rather than structural head-finality alone.

## Limitations
- Sample Size and Generalizability: The study relies on five hand-selected minimal pairs from the Korean Swadesh list, which precludes broad statistical inferencing and limits generalizability across the entire Korean verbal lexicon.
- Orthogonal Axes of Semantic Breadth: Operationalizing polysemy as raw dictionary sense counts overlooks the distinction between technical domain specialization (e.g., kwupta) and conceptual hypernymy (e.g., yolihata), revealing that sense counts and taxonomic generality do not measure an identical construct.
- Register and Data Asymmetries: Certain items (e.g., keywuta) exhibited extreme lexical sparsity in colloquial web corpora (NSMC, $n=1$), preventing full cross-register representation. Furthermore, Vertex AI dense embeddings were evaluated exclusively on dictionary definitions due to token/resource constraints.
- Multilingual Embedding Anisotropy: Baseline self-similarity scores from Vertex AI's multilingual dense representations were uniformly elevated due to representation anisotropy (narrow cone effect), meaning absolute cosine distances cannot be compared directly against monolingual BERT architectures.
- Automated Morphological Parsing: Corpus frequency counts rely on automated tokenization (Bareun, Mecab-ko) without exhaustive manual verification of spoken transcript boundaries.
