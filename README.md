<p align="center">
  <strong>Seeing Is Not Scoring</strong><br>
  VLM-based Trait Assessment of Arabic Picture-Cued Writing
</p>

<p align="center">
  Khaoula Dahimi, Hadda Cherroun, Amel Belabbaci, Soumia Bougrine, and Abdelhamid Haouhat
</p>

<p align="center">
  Laboratoire d'Informatique et de Mathématiques (LIM)<br>
  Amar Telidji University, Laghouat, Algeria
</p>

<p align="center">
  <a href="#paper">Paper</a> |
  <a href="#overview">Overview</a> |
  <a href="#benchmark">Benchmark</a> |
  <a href="#evaluation">Evaluation</a> |
  <a href="#citation">Citation</a>
</p>


## 📄 Paper

**Title:** Seeing Is Not Scoring: VLM-based Trait Assessment of Arabic Picture-Cued Writing

**Conference:** 3rd International Conference on Artificial Intelligence and Its Practical Applications in the Age of Digital Transformation (I2COMSAPP 2026)

**Status:** Submitted

## 🌟 Overview

Automated assessment of Arabic writing remains challenging because writing quality involves multiple linguistic dimensions that cannot be captured by a single overall score. Vision-language models (VLMs) introduce new opportunities for evaluating picture-cued writing by jointly processing visual prompts and written responses.

This work investigates whether VLMs can reliably assess Arabic picture-cued writing across multiple writing traits. We introduce **TABSIR**, a synthetic benchmark designed to study trait-based assessment, model scoring behavior, and consistency across repeated evaluations.

The study examines the limitations of model-based assessment and explores whether models can distinguish between different dimensions of writing quality rather than relying on a single holistic judgment.

## 🎯 Key Features

- **Arabic picture-cued writing:** Focus on Arabic writing elicited by visual prompts.
- **Trait-based assessment:** Evaluation across five distinct writing dimensions.
- **Synthetic benchmark:** Structured samples designed to investigate automated scoring.
- **Human annotations:** Reference scores assigned using a predefined assessment rubric.
- **VLM evaluation:** Investigation of model-generated trait scores under different prompting configurations.


## 🏗️ Assessment Framework

The framework evaluates five writing traits:

1. **Comprehensiveness:** Coverage and development of ideas relevant to the picture.
2. **Vividness:** Descriptive detail and richness of expression.
3. **Mechanics:** Orthographic, grammatical, and punctuation correctness.
4. **Vocabulary Choice:** Appropriateness and effectiveness of word selection.
5. **Sentence Structure:** Syntactic organization and sentence formation.

Each trait is scored on a five-point scale:

| Score | Level |
|---:|---|
| 1 | Very Poor |
| 2 | Poor |
| 3 | Average |
| 4 | Good |
| 5 | Excellent |

## 📊 Benchmark: TABSIR

TABSIR is designed to support research on automated Arabic writing assessment using picture-cued writing tasks.

The benchmark construction process includes:

- Collecting image–text samples from relevant sources.
- Preparing Arabic writing samples for trait-based assessment.
- Filtering unsuitable samples.
- Applying a consistent assessment rubric.
- Collecting human annotations.
- Evaluating model-generated scores against reference annotations.

**Benchmark statistics:** To be completed with the final released dataset statistics.

## 🧪 Evaluation

The evaluation investigates the behavior of VLMs under different prompting configurations and examines their ability to reproduce trait-level human judgments.

The analysis focuses on:

- Agreement between model predictions and human reference scores.
- Performance across the five writing traits.
- Score distributions and potential scoring biases.
- Consistency across repeated model evaluations.
- Differences between linguistic and overall writing-quality judgments.

**Experimental results:** Evaluation tables and figures will be added when the results are finalized for public release.


## 💻 Code and Usage

Instructions for reproducing the experiments, configuring the models, and running the evaluation scripts will be provided with the public code release.

## 📚 Citation

If you use this work in your research, please cite the paper once its publication details are available.

```bibtex
@inproceedings{dahimi2026seeing,
  title     = {Seeing Is Not Scoring: VLM-based Trait Assessment of Arabic Picture-Cued Writing},
  author    = {Dahimi, Khaoula and Cherroun, Hadda
               and Belabbaci, Amel and Haouhat, Abdelhamid},
  year      = {2026},
  note      = {Submitted to I2COMSAPP 2026}
}
```

## 🙏 Acknowledgments

We acknowledge the researchers and communities whose publicly available resources support research on Arabic language technologies and multimodal evaluation.


