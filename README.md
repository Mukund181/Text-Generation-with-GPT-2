# Text-Generation-with-GPT-2
# 🧠 GPT-2 Text Generation with Fine-Tuning (Custom In-Memory Dataset)

This project demonstrates fine-tuning OpenAI's GPT-2 model on a custom dataset defined directly in Python code — without using external text files. After training, the model accepts a user prompt and generates text based on the learned context.

---

## 🚀 Features

- ✅ Fine-tune GPT-2 using HuggingFace Transformers
- ✅ No file I/O — dataset is written directly into the script
- ✅ Accepts prompt input after training
- ✅ Generates meaningful text responses
- ✅ Works on CPU or GPU


## 🔧 Installation

Install the required dependencies using pip:
pip install transformers torch

▶️ How to Run
python gpt2_finetune.py
You’ll be prompted to enter a text prompt once fine-tuning is complete.

🧠 Training Data
The dataset is a list of 10 AI-related sentences defined in-code:

custom_texts = [
    "Artificial intelligence is transforming the world in unprecedented ways.",
    "Natural language processing has made significant advances in recent years.",
    ...
]
You can easily modify or expand this list inside the script.

📝 Example
Input Prompt:

Enter your prompt for text generation: GPT-2 models can
Output:

GPT-2 models can generate human-like text and be fine-tuned to fit specific use cases. These models are revolutionizing how we approach language understanding and generation.

🛠️ Technologies Used
HuggingFace Transformers

PyTorch

Python 3.8+

👨‍💻 Author
Mukund Fegade
