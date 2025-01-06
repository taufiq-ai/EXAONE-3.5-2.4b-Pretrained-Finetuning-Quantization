# EXAONE-3.5-2.4b-Pretrained-Finetuning-Quantization
EXAONE-3.5 comes in three variants: 2.4B, 7.8B, and 32B parameters. Below are benchmark comparison scores of the 2.4B & 7.8B variants against similar models.

![image](https://github.com/user-attachments/assets/639f66a4-2653-460a-aeda-b563cbc7507d)

## Hardware Requirements
Testing was conducted using the Kaggle Free Tier with the following specifications:
- GPU: Tesla P100 16GB
- RAM: 29GB
- Disk: 60GB

After a 2-hour session of inference testing, the resource consumption was notably efficient by the pre-trained version:
- GPU Memory: 6.3GB
- RAM Usage: ~2GB
- Disk Space: 11.1GB

## Code
Let's go through the Kaggle Notebook to explore the pretrained variant of EXAONE-3.5-2.4B-Instruct. The notebook is ready to run on the go - just do not forget to change the accelerator to GPU. It'll take approx. 3-4 minutes to setup the model and tokenizer. For detailed implementation guidelines, you can refer to the model's documentation here.

## I've explored the following use cases in this notebook:

- Named Entity Recognition (NER)
- Text Classification
- Python & HTML Code Generation
- Q&A
- Text Summarization
- Text Generation
