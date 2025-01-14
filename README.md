# 💬 Chat with your PDF 

## 👷️ Architecture

Link: https://youtu.be/FuqdVNB_8c0

This tutorial goes over the architecture and concepts used for easily chatting with your PDF using LangChain, ChromaDB and OpenAI's API.

## 💻 Getting Started

### Prerequisites

You will need Python 3.x installed on your machine.

Note: For **Windows** users, you might need to delete the `Pipfile.lock` before proceeding with the installation.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/edrickdch/chat-pdf
```

2. Navigate to the project directory:

```bash
cd chat-pdf
```

3. Install the required dependencies:

```bash
pip install --upgrade -r requirements.txt
```

4. Create a .env file with your OpenAI API key (Replace with your key):

```bash
cat 'OPENAI_API_KEY="sk-XXXXXXXXXXXXXXXXXXXXXXXXXXXX"' >  .env
```

5. Run the ingestion:

```bash
python src/ingest.py
```

6. Run the conversation:

```bash
python src/single-pdf.py
```

## 🔗 Useful Links

- PDF: https://www.imf.org/en/Publications/WEO/Issues/2023/04/11/world-economic-outlook-april-2023 
- OpenAI: https://platform.openai.com/ 
- LangChain: https://python.langchain.com/en/latest/index.html  
- Chroma DB: https://docs.trychroma.com/ 

## 💌 Newsletter

👇 Subscribe to the newsletter if you're interested in building more AI applications 

https://practical-ai-builder.beehiiv.com/
