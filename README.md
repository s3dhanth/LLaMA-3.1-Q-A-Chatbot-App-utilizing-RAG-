# Fine Tuning Pegasus for Text Summarization 

This repository contains a Gradio application for an enhanced Retrieval aungmented generation Q&A bot that leverages LLaMA 3.1 and Chromadb Admin with Docker Integration. The app allows users to interact with the Model and get responses based on their queries.

## DataSet

- SAMSum datase
t contains about 16k messenger-like conversations with summaries
- Data1: History of Tuscan-inspired sanctuary
- Data2: History of Giovanni
- Data3: Different Cuisine of Bella Vista

## Chromadb Vector Store
- Converted text into vectors using LLaMA 3.1 Embedding (5042 vectors)
  
![chromadb_embedding](https://github.com/user-attachments/assets/b2664fb0-790e-4a93-b0f8-c435d858d268)

- Integrated docker Container with port 8000:8000

![docker_container](https://github.com/user-attachments/assets/01651e44-a904-4acb-b3f0-2acdcb24e7c8)

## Installation

1. Clone the repository:

```sh
git clone https://github.com/your-username/rag_project.git
cd rag_project
Install the required dependencies:
sh
Copy code
pip install -r requirements.txt

# using Chromadb - Admin

git clone https://github.com/flanker/chromadb-admin.git
cd chromadb-admin
npm run dev

# To Integrate with Docker

cd Chroma
docker-compose up --build


Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
```
## Model DEMO (LLaMA 3.1)
- In the text box Enter our query and submit 
![model_output](https://github.com/user-attachments/assets/9a72b6dc-89ca-4caf-8dbd-283246b1f31f)

