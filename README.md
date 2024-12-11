# Insurance Documents QA RAG Chatbot  
Your Intelligent Chat Assistant for Insurance and General Queries  

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  
[![Python](https://img.shields.io/badge/python-3.8%2B-brightgreen.svg)](https://www.python.org/)  

---

## ✨ About the Project  
This chatbot leverages the advanced capabilities of LangGraph to deliver precise and context-aware responses. It dynamically retrieves data from insurance documents or conducts web searches based on user queries, enabling a seamless and intelligent interaction. LangGraph's graph-based orchestration and stateful design ensure optimal performance for multi-agent workflows.

---

## 🔍 Key Features  
- ✨ **Sophisticated Query Resolution**: Handles document-specific and general queries using intelligent orchestration.  
- ☆ **Efficient Data Retrieval**: Utilizes **LlamaIndex** for focused and accurate insurance data extraction.  
- ✪ **Agentic Generation**: Implements LangGraph's stateful framework to manage dynamic agent interactions.  
- ✨ **Scalable Embedding Storage**: Employs **ChromaDB** for efficient data storage and query operations.  
- 🔑 **Advanced Caching**: Integrates multi-layer caching at embedding and query levels for enhanced efficiency.  
- 🔄 **Dynamic Workflow Management**: LangGraph ensures flexible and optimized agent transitions.  
- 🕒 **Real-Time Adaptability**: Determines the most suitable workflow (document retrieval or web search) on-the-fly.

---

## 🛠️ Tech Stack  
- **Language**: Python  
- **Frameworks/Libraries**: LangGraph, LlamaIndex, ChromaDB 
- **APIs/Models**:  
  - OpenAI's Embedding Model for vector creation 
  - OpenAI for high-quality generative responses
  - LlamaIndex for document ingestion and querying
  - LangGraph for agent orchestration and state management

---

## 🧪 Example Use Cases   
- "What are the exclusions in my insurance policy?"  
- "How do I claim accidental insurance?"  
- "What is Drug Abuse related death?" (via web search)

---

## 📸 Sample Output  
### 1. Insurance Query Response  
![Insurance Query Response](Sample%20Code%20Output%20Screenshots/Sample%20Code%20Output%201.png)  
 
---
## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Docker (optional, for containerized deployment)

### Installation
1. Clone the repo:
git clone https://github.com/SandeepGitGuy/Insurance_Documents_QA_Chatbot_RAG_LlamaIndex_LangGraph.git

2. Navigate to the project directory:
cd Insurance_Documents_QA_Chatbot_RAG_LlamaIndex_LangGraph

3. Install the required dependencies:
pip install -r requirements.txt

- Please note: OpenAI API keys are required for the project to function.

4. Run the main file from Jupyter environment:
"Insurance_Docs_QA_Chatbot_RAG_Llamaindex_LangGraph.ipynb"

---

## 🚂 Challenges Faced and Fixes  
- **Agent Workflow Design**: Designed robust state graphs for agent interactions using LangGraph.  
- **Caching Optimization**: Enhanced efficiency by introducing caching layers for embeddings and responses.  
- **Workflow Customization**: Exploited LangGraph's graph-based orchestration for flexible agent transitions.  
- **Error Recovery**: Implemented memory-driven recovery mechanisms for enhanced reliability.  

---

## 🌐 Future Scope  
- Extend support for multi-language documents and diverse file formats.  
- Incorporate additional generative AI models.  
- Leverage LangGraph's advanced features for interactive and hierarchical agent workflows.

---

## 🔗 Documentation  
No documentation will be made available for this project since this project only uses technologies that already have their own documentation. Please refer to the following links for more information: 
- [LangGraph](https://langchain.com)  
- [LlamaIndex](https://llamaindex.ai/)  
- [ChromaDB](https://docs.trychroma.com/)   

---

## 🛡️ License  
Distributed under the MIT License. See `LICENSE` for more details.  

---

## 💬 Contact  
For questions, feedback, or collaboration opportunities:  
- **Email**: sandy974278@gmail.com  
- **GitHub**: [SandeepGitGuy](https://github.com/SandeepGitGuy)  
- **LinkedIn**: [Sandeep Gowda](https://www.linkedin.com/in/sandeepgowda24a319192)  

---