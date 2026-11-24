# TruthGuard AI | Research on AI Reliability and Resistance to Misinformation

### Evaluating AI Models Under Social Pressure, False Authority, and Conflicting Information

**Research Area:** Artificial Intelligence | AI Safety | Model Evaluation | Responsible AI  
**Project:** TruthGuard AI Research  
**Author:** Data Engineer Luis Barahona

---

## Project Overview

TruthGuard AI is an experimental research framework designed to evaluate the reliability and consistency of artificial intelligence models when exposed to misinformation, social pressure, and misleading claims of authority.

The project investigates how AI models respond when users challenge initially correct answers, introduce unsupported corrections, or present false information as authoritative.

Its main objective is to explore whether AI systems can maintain evidence-based reasoning while remaining capable of accepting legitimate corrections.

## Research Question

**When should an AI model change its answer, and when should it resist unsupported pressure?**

This question guides the experimental design and evaluation methodology.

## Research Objectives

- Evaluate AI response consistency under different conversational conditions.
- Analyze model behavior when exposed to incorrect information.
- Identify cases of unjustified answer changes.
- Explore resistance to misleading authority claims.
- Develop reproducible evaluation procedures.
- Implement conservative classification of model responses.
- Support manual review of ambiguous results.
- Explore statistical methods for comparing experimental outcomes.

## Experimental Design

The framework evaluates model behavior across three conditions:

| Condition | Description |
|:---|:---|
| A — Baseline | Neutral verification without additional pressure |
| B — Social Pressure | Attempts to persuade the model to accept an incorrect answer |
| C — False Authority | Presentation of a misleading correction attributed to an authoritative source |

The research design supports:

- Up to 7 AI models.
- 20 evaluation questions.
- 3 experimental conditions.
- A maximum of 420 experimental scenarios.

These values represent the experimental capacity of the research design, not the number of completed tests.

## Methodology

### 1. Experiment Preparation

Evaluation questions are organized with expected answers and controlled conversational conditions.

### 2. Model Interaction

Selected AI models receive structured prompts designed to test their responses to conflicting information.

### 3. Response Evaluation

Generated responses are evaluated using conservative criteria to distinguish supported answers, incorrect answers, and ambiguous results.

### 4. Manual Review

Responses that cannot be reliably classified automatically are exported for additional examination.

### 5. Research Integrity

SHA-256 checks are incorporated to support experiment integrity and reproducibility.

### 6. Statistical Analysis

The framework includes tools for exploring experimental distributions and comparing model behavior.

## Execution Modes

The notebook supports three research workflows:

**Demo Mode:** Demonstrates the evaluation methodology without requiring a complete live experiment.

**Historical Analysis Mode:** Examines previously generated experimental records.

**Live API Mode:** Allows controlled interaction with compatible AI models through an API.

Live execution may involve external API costs and requires appropriate credentials.

## Technologies

**Python | Google Colab | AI APIs | Statistical Analysis | JSONL | SHA-256 | Data Evaluation**

## Verified Experimental Observations

The notebook includes a small live-API pilot using the Adaption model `glm-53-flash`.

The saved execution results contain two completed experimental records marked for manual review.

These observations demonstrate the experimental workflow but do not establish statistical significance or provide sufficient evidence to make general conclusions about model reliability.

## Limitations

- The notebook is an experimental research implementation.
- Its complete evaluation design has not been demonstrated across all proposed scenarios.
- Ambiguous responses require manual interpretation.
- Small experimental samples cannot establish general model reliability.
- Results depend on model versions, prompts, evaluation criteria, and API configurations.
- Additional experiments are required before making broader comparative claims.

## Future Development

Potential improvements include:

- Expanding the number of evaluated models.
- Increasing the diversity of experimental questions.
- Strengthening automated response classification.
- Developing standardized benchmark reports.
- Implementing additional statistical validation.
- Comparing model behavior across repeated experimental runs.

## Google Colab

[Open TruthGuard AI Research Notebook](https://colab.research.google.com/drive/1c-61AiNCsvpslRg0RZtutx_Lm_LR5rRa)

## Author

**Data Engineer Luis Barahona**

Mexican Data Engineer and 2026 graduate of Universidad del Caribe, interested in Data Science, Artificial Intelligence, Software Development, and responsible AI research.

## Contact

| Platform | Contact |
|:---|:---|
| Email | [190300395@ucaribe.edu.mx](mailto:190300395@ucaribe.edu.mx) |
| GitHub | [github.com/LuisBarahonaMX](https://github.com/LuisBarahonaMX) |
| LinkedIn | [linkedin.com/in/luis-barahona-mx](https://www.linkedin.com/in/luis-barahona-mx/) |
| Instagram | [@luisbarahonamx](https://www.instagram.com/luisbarahonamx/) |
| X | [@luisbarahonaMX](https://x.com/luisbarahonaMX) |
| Website | [SIKO AI Platform](https://sikoai.web.app/) |
