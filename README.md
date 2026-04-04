# LLM Evaluation & Complexity Analysis Notebooks

This repository contains a collection of Jupyter notebooks used for evaluating and analyzing Large Language Models (LLMs) as part of a thesis project. The notebooks cover various aspects of model evaluation, complexity analysis, and conversational AI testing.

## Repository Structure

### Model Complexity Analysis

- **`gemma3_4b_q4_0_complexity.ipynb`** - Complexity analysis for the Gemma 3 4B quantized model
- **`Llama3_2_Q4_0_Complexity.ipynb`** - Complexity analysis for Llama 3.2 4-bit quantized model
- **`phi35_38b_q4_0_complexity.ipynb`** - Complexity analysis for Phi-3.5 38B quantized model
- **`qwen3_4b_q4_0_complexity.ipynb`** - Complexity analysis for Qwen3 4B quantized model

### Conversational AI Testing

- **`Unsloth Llama3.2_(1B_and_3B)-Conversational.ipynb`** - Conversational inference tests using Unsloth-optimized Llama 3.2 models (1B and 3B variants)
- **`Unsloth Phi_3.5_Mini-Conversational.ipynb`** - Conversational inference tests using Unsloth-optimized Phi 3.5 Mini model

### Evaluation Metrics

- **`BertScore Automated Evaluation.ipynb`** - Automated evaluation using BERTScore metric for assessing text generation quality

### Data Processing

- **`Dataset Conversion.ipynb`** - Scripts and utilities for converting datasets into formats suitable for model training/evaluation

### OpenRouter Automation

- **`OpenRouter Automate Script - Culture`** - Automated evaluation script for cultural domain tasks using OpenRouter API
- **`OpenRouter Automate Script - Government_`** - Automated evaluation script for government/policy domain tasks
- **`OpenRouter Automate Script - History`** - Automated evaluation script for historical domain tasks

## Setup

These notebooks are designed to run in Google Colab or local Jupyter environments. Dependencies are typically managed within each notebook.

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/REPO_NAME.git
cd REPO_NAME

# Install Jupyter if not available
pip install jupyterlab

# Launch Jupyter
jupyter lab
```

## Notes

- Some notebooks may require API keys (e.g., OpenRouter, Hugging Face) - these should be set as environment variables or in the notebook's configuration cells
- Quantized models are used to reduce computational requirements while maintaining performance
- Unsloth is used for optimized inference on smaller models

## License

This project is licensed under the Apache License 2.0. This license is chosen to be compatible with Unsloth's Apache 2.0 license, which is used by the Unsloth library referenced in several notebooks.

See the [LICENSE](LICENSE) file for the full license text.

## Contact

For questions about this thesis work, please contact the repository owner.
