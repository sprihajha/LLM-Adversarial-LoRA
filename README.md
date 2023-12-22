# Evaluating and Circumventing Safety Measures in Large Language Models through Adversarial LoRA Fine-Tuning

This repository contains the code and resources for the final project in the EL-GY-9163: Machine Learning for Cyber-security class. The project evaluates the vulnerability of large language models (LLMs) to adversarial fine-tuning using Low-Rank Adaptation (LoRA), focusing on the robustness of safety measures in LLMs against subversive manipulations.

## Repository Structure

- `ckpts/`: Contains the manually downloaded public LLMs.
- `configs/`: Configuration files for running the code.
- `finetuned_models/`: Stores the models fine-tuned using LoRA.
- `finetuning.py`: Python script defining the LoRA fine-tuning process.
- `ft_datasets/`: Datasets used for fine-tuning the models.
  - `harmful_behaviors.csv`: CSV file containing harmful prompts.
- `model_checkpointing/`: Temporary storage for model checkpoints during training.
- `requirements.txt`: Lists dependencies for the project.
- `safety_evaluation/`: Code for comparing fine-tuned models against GPT-4.
- `LoRA_finetuning.ipynb`: Jupyter notebook demonstrating harmful examples.

## Setup and Installation

1. **Clone the Repository:**

   ```bash
   git clone [URL_of_This_Repo]
   cd [Repo_Name]
    ```

2. **Install Dependencies:**  

   ```bash

pip install -r requirements.txt
    ```
3. **Download Models:**  

Follow instructions in `LoRA_finetuning.ipynb` to manually download the required LLMs to `ckpts/`.

4. **Running the Experiments:**  

Launch `LoRA_finetuning.ipynb` in a Jupyter environment to see the demonstration of harmful examples.
