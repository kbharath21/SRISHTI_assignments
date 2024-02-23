# SRISHTI24

## Llama 2 Fine-Tuning Guide

This guide outlines the steps to fine-tune the Llama 2 model for your specific task.

1. **Install Required Packages:** Ensure all necessary packages are installed.

2. **Import Libraries:** Import required libraries into your Python environment.

3. **Reformat Instruction Dataset:** Adhere to the specified prompt template.

   - **System Prompt:** Optional guide for the model.
   - **User Prompt:** Required instruction.
   - **Model Answer:** Desired response.

   - Original Dataset: [OpenAssistant Guanaco](https://huggingface.co/datasets/timdettmers/openassistant-guanaco)
   - Reformat Dataset: [Guanaco-Llama2-1k](https://huggingface.co/datasets/mlabonne/guanaco-llama2-1k)

4. **Fine-tune Llama 2:**
   
   - **Load Dataset:** Preprocessed or reformatted dataset.
   - **Configure Bitsandbytes:** For 4-bit quantization.
   - **Load Model:** In 4-bit precision on GPU.
   - **Load QLoRA Configurations:** For fine-tuning.
   - **Start Training:** Pass configurations to the SFTTrainer.

5. **Text Generation Pipeline:** Use pipeline to generate responses from the fine-tuned Llama 2 model.

**Repository Link:** [SRISHTI24 - Large-Language-Models](https://github.com/Manoj010104/SRISHTI24/tree/main/Large-Language-Models)

