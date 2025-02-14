# AI Debate System

## 📌 Project Description
The **AI Debate System** is a Python-based project that uses **LangChain** to simulate a structured debate between two AI models. One AI argues **for** a given topic, another argues **against**, and a third AI acts as a **judge** to determine the winner. 

### 🔥 Features:
- **Multi-LLM Debate**: Two AI models engage in a logical debate.
- **Automated Judging**: A third AI evaluates and declares the winner.
- **Custom Topics**: Users can define their own debate topics.

## 🛠 Installation

### 📦 Setup with Conda
To install the required dependencies, use the provided `environment.yml` file:

```sh
conda env create -f environment.yml
conda activate ai-debate
```

### 📥 Downloading the Model
This project requires the **Meta-Llama-3.1-8B-Instruct-GGUF** model from Hugging Face. Download it from [Link](https://huggingface.co/bartowski/Meta-Llama-3.1-8B-Instruct-GGUF/resolve/main/Meta-Llama-3.1-8B-Instruct.Q4_K_M.gguf)

Ensure that the downloaded model is placed in the root of this project.

## 🚀 Usage
Run the Jupyter Notebook to start a debate on a chosen topic:

```sh
jupyter notebook ai_debate.ipynb
```

Modify the `topic` variable in `ai_debate.ipynb` to debate a different subject.

## 🔧 Dependencies
- Python 3.x
- LangChain
- OpenAI API
- Conda (for environment management)
- Jupyter Notebook
- Hugging Face Model (`Meta-Llama-3.1-8B-Instruct-GGUF`)

## 📜 License
MIT License

## 📞 Contact
For any issues or feature requests, feel free to reach out or create a pull request!

