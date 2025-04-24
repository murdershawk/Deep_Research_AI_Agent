# Deep_Research_AI_Agent
This repository hosts a dual-agent AI system for automated deep research, developed as a qualifying assignment for Kairon. The system leverages Tavily for web crawling, LangGraph for agent workflow management, and LangChain for data organization, demonstrating skills in data processing and automation applicable to bioinformatics, such as genomics and transcriptomics analysis.
Overview
The project features a modular, dual-agent architecture:

Research Agent: Queries the Tavily API to collect web data, with dynamic query optimization and error handling, resembling the retrieval of large-scale omics datasets.
Answer Drafter: Processes data using LangChain for retrieval and summarization, producing structured outputs akin to transcriptomics data pipelines.
Frameworks:
LangGraph: Orchestrates agent workflows via a state machine, enabling scalable data processing.
LangChain: Uses document loaders and embeddings for efficient data retrieval, adaptable to biological data.



Unique features include automated query reformulation and caching mechanisms, enhancing scalability for research applications.
Setup
To run the project:

Clone the repository:git clone https://github.com/your-username/Deep-Research-AI-Agent.git


Install dependencies:pip install -r requirements.txt


Open and run the notebook:
In Google Colab: Upload Deep_Research_AI_Agent.ipynb and execute all cells.
Locally: Use Jupyter Notebook or VS Code with the Jupyter extension.


Configure the Tavily API key:
Replace "your-api-key" in the notebook with a valid Tavily API key (obtain from Tavily).



Files

Deep_Research_AI_Agent.ipynb: Main Google Colab notebook with the dual-agent system.
requirements.txt: Python dependencies (e.g., langchain, langgraph, tavily-python).
README.md: Project documentation.

Notes

Developed in Google Colab, with requirements.txt ensuring compatibility in other environments.
The system’s data processing capabilities are relevant to bioinformatics tasks, such as analyzing genomic or transcriptomic data.
Refer to Deep_Research_AI_Agent_Explanation.pdf (submitted separately) for a detailed implementation overview.


License
MIT License.
