# Career Guidance Chatbot with RAG and Cutting-Edge LLMs

This project presents a chatbot designed to offer personalized career advice and support to users navigating their professional paths. Leveraging advanced language models (LLMs) and the Retrieval-Augmented Generation (RAG) framework, the chatbot provides tailored responses and recommendations.

## Technologies Leveraged:

- **LLamaindex**: A robust indexing system tailored for large language models, enabling efficient retrieval of pertinent information.
- **Langchain**: A versatile library designed to manage and structure conversational data effectively.
- **RAG (Retrieval-Augmented Generation)**: A powerful framework that amalgamates retrievers and generative language models, enhancing performance in tasks like question answering and dialogue generation.
- **Hugging Face Transformers**: A renowned library offering pre-trained models catering to diverse Natural Language Processing (NLP) tasks.

## Project Architecture:

```
career-counselling-chatbot/
│
├── Research/
│   ├── scraper.ipynb
│   └── model.ipynb
│
├── config/
│   ├── config.yaml
│   └── param.yaml
│
├── src/
│   ├── careerbot/
│   │   ├── components/
│   │   │   ├── __init__.py
│   │   │   ├── llm.py
│   │   │   └── scraper.py
│   │   ├── config/
│   │   │   ├── __init__.py
│   │   │   └── configuration.py
│   │   ├── constants/
│   │   │   └── __init__.py
│   │   ├── entity/
│   │   │   └── __init__.py
│   │   ├── pipeline/
│   │   │   ├── __init__.py
│   │   │   └── chat.py
│   │   └── __init__.py
│   ├── logger/
│   │   └── __init__.py
│   └── utility.
│       ├── __init__.py
│       └── common.py
│
├── README.md
├── app.py
├── requirements.txt
├── setup.py
└── template.py
```

## Setup Instructions:

1. Set up the environment:

   ```
   conda create -n venv python=3.10
   conda activate venv
   ```

2. Clone the repository:

   ```
   cd careerbot
   ```

3. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

4. Launch the Flask application:

   ```
   python app.py
   ```

5. Access the chatbot via CLI.

## How to Use:

Once the application is up and running, users can engage with the chatbot through the command line interface. They can input queries or seek guidance related to career matters, receiving personalized responses and advice.

## Contributors:
-Group 15