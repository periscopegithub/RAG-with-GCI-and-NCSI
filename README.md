
# GCI and NCSI Insights Extraction and Summarization

This notebook contains the complete code for extracting and summarizing insights from the Global Cybersecurity Index (GCI) report and the National Cyber Security Index (NCSI) website using Retrieval-Augmented Generation (RAG) techniques. The notebook is designed to provide valuable cybersecurity-related insights to users from various jurisdictions, leveraging advanced LLM applications.

### Environment
- Python 3.10.14
- Jupyter Notebook

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/periscopegithub/RAG-with-GCI-and-NCSI.git
    cd RAG-with-GCI-and-NCSI
    ```

2. Create a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

### Requirements

#### 1. API Keys
This project utilizes Azure's OpenAI API. You need to create a `.env` file in the root directory and add your API keys:

```
AZURE_OPENAI_ENDPOINT=your_endpoint_here
AZURE_OPENAI_KEY=your_key_here
AZURE_OPENAI_VERSION=your_version_here
AZURE_OPENAI_DEPLOYMENT_GPT35TURBO=your_gpt35turbo_deployment_here
AZURE_OPENAI_DEPLOYMENT_GPT4=your_gpt4_deployment_here
AZURE_OPENAI_DEPLOYMENT_GPT4O=your_gpt4o_deployment_here
AZURE_OPENAI_EMBEDDING_MODEL=your_embedding_model_here
AZURE_OPENAI_EMBEDDING_DEPLOYMENT=your_embedding_deployment_here

```

#### 2. Ollama
The scripts utilize Ollama for running local LLM. You need to install Ollama. Refer to the [Ollama website](https://ollama.com/) for installation instructions.

#### 3. Llama3 Model
Download the Llama3 model in Ollama for local LLM operations.

#### 4. CUDA and cuDNN
It is advised you have an Nvidia GPU with CUDA toolkit and cuDNN installed. Refer to the official [Nvidia CUDA](https://developer.nvidia.com/cuda-toolkit) and [cuDNN](https://developer.nvidia.com/cudnn) websites for installation instructions.

### References
**Code Reference:** https://colab.research.google.com/drive/1IVQkSGwS5kdTiKBwz85PO6vg_WaNx15c?usp=sharing

