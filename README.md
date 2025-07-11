# 🤖 Enhanced AI Tutor System using LLaMA-3 and LangGraph

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Made with LangGraph](https://img.shields.io/badge/Built%20with-LangGraph-purple)](https://python.langgraph.dev/)
[![Model: Meta LLaMA 3.2](https://img.shields.io/badge/Model-Meta%20LLaMA%203.2%203B-blue)](https://huggingface.co/meta-llama/Llama-3.2-3B-Instruct)

An **adaptive, feedback-based AI tutor system** built using:

- 🧠 Meta's [LLaMA-3.2-3B-Instruct](https://huggingface.co/meta-llama/Llama-3.2-3B-Instruct)
- 🔄 [LangGraph](https://github.com/langchain-ai/langgraph) for multi-agent workflow
- ⚡ Hugging Face Transformers (4-bit quantization for efficiency)
- ✅ PyTorch, BitsandBytes, Accelerate for seamless GPU usage

---

## 🎓 What It Does

This notebook walks you through a **complete interactive tutor session** that:

1. 📚 Asks a question from a topic you choose
2. 📝 Evaluates your answer and gives structured feedback
3. 🧪 Generates a new practice question
4. 📈 Tracks your progress and adapts difficulty

It's like having your own AI teacher, personalized to your learning!

---

## 🚀 Quickstart

### 🔧 Requirements

Install required packages first:

```bash
pip install langgraph transformers accelerate bitsandbytes --quiet
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118 --quiet
pip install huggingface_hub --quiet
```
---

### 🔑 Login to Hugging Face

```python
from huggingface_hub import notebook_login
notebook_login()
```

### 🏃‍♂️ Run the Notebook

1. Launch the `.ipynb` in a Google Colab GPU runtime
2. Follow the prompts
3. Learn, improve, repeat 🔁

---

## 📁 Project Structure

```
├── EnhancedTutorSystem.ipynb   
├── README.md                   
├── requirements.txt            
```

---

## 🧠 Model Info

This project uses (but does not rehost) Meta's official instruction-tuned model:

[![Model: Meta LLaMA 3.2](https://img.shields.io/badge/Model-Meta%20LLaMA%203.2%203B-blue)](https://huggingface.co/meta-llama/Llama-3.2-3B-Instruct)

The model is loaded via transformers using 4-bit quantization (BitsAndBytes)

**Note:** You must agree to Meta's license to access the model.

---

## 🎯 Features

- ✍️ Adaptive questions across difficulty levels
- 📊 Real-time performance tracking
- 🤓 Intelligent feedback on every answer
- 💡 LangGraph-powered multi-agent workflow
- 🧵 Fully reproducible session history

---

## 🔜 Coming Soon

- 🌐 A Hugging Face Space with a user-friendly UI
- 📝 Student progress export to PDF
- 🎯 Topic-based quiz sessions
- 🧪 Integration with LangChain for evaluation metrics

---

## 📄 License

This project is released under the MIT License.

---

## 🙌 Acknowledgments

- 🧠 Meta AI for LLaMA-3
- 🔄 LangGraph by LangChain
- 🤗 Hugging Face for open infrastructure

---

## 📬 Contact / Feedback

[![GitHub](https://img.shields.io/badge/GitHub-Mrigank005-181717?logo=github)](https://github.com/Mrigank005)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mrigank005-0077B5?logo=linkedin)](https://www.linkedin.com/in/mrigank005)

Feel free to raise issues or suggestions on GitHub  
Or connect via Hugging Face community tab!

**Happy learning!** 💡

---
