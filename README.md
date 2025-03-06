# MedGraph Navigator: Patient Journey & Risk Analytics Platform

This repository contains the development notebooks for the MedGraph Navigator project, created for the [ArangoDB Hackathon: "Building the Next-Gen Agentic App with GraphRAG & NVIDIA cuGraph"](https://arangodbhackathon.devpost.com/).

## 🏆 Hackathon Submission

This project is our submission for the ArangoDB Hackathon on Devpost, where we've created an agentic application integrating GraphRAG and GPU-accelerated graph analytics with NVIDIA cuGraph.

**Hackathon Link:** [Building the Next-Gen Agentic App with GraphRAG & NVIDIA cuGraph](https://arangodbhackathon.devpost.com/)

## 📊 Project Overview

MedGraph Navigator is a comprehensive healthcare analytics platform that leverages graph databases, GPU-accelerated analytics, and AI reasoning to provide insights into patient journeys and health risks. The platform enables healthcare professionals to:

- Visualize complete patient medical journeys
- Identify high-risk patients through graph analytics
- Discover treatment patterns and correlations
- Query medical data using natural language
- Analyze complex medical relationships with graph algorithms

## 📓 Repository Contents

This repository contains the Jupyter notebooks used to develop and process data for the MedGraph Navigator application:

### 1. H_ArangoDB_Download_Extract_and_Merge_Data.ipynb

This notebook handles the data engineering pipeline for the Synthea healthcare dataset:
- Downloads the comprehensive SyntheticMass dataset (21.3GB)
- Extracts nested archives with progress tracking
- Merges CSV files by patient record types
- Processes and analyzes the dataset structure
- Creates visualizations of dataset characteristics
- Prepares data for graph ingestion

### 2. STEPS_MedGraph_Navigator_Patient_Journey_&_Risk_Analytics_Platform.ipynb

This notebook develops the core platform in step-by-step progression:
- **Step 0:** Package installation and environment setup
- **Step 1:** Dataset preparation and initial analysis
- **Step 2:** Converting and loading graph data into NetworkX with GPU acceleration
- **Step 3:** Persisting the graph in ArangoDB
- **Step 4:** Building the agentic application with LangChain & LangGraph
- Includes comprehensive data visualization and analytics

## 🚀 Full Application

The complete MedGraph Navigator application has been deployed and is available at:

**[https://medgraph-navigator.onrender.com/](https://medgraph-navigator.onrender.com/)**

The source code for the full application is available in a separate repository:

**[https://github.com/ajitonelsonn/medgraph-navigator](https://github.com/ajitonelsonn/medgraph-navigator)**

## 🛠️ Technologies Used

- **ArangoDB**: Graph database for storing and querying medical data
- **NetworkX**: Python library for graph data structures and algorithms
- **NVIDIA cuGraph**: GPU-accelerated graph analytics
- **LangChain & LangGraph**: Framework for creating reasoning chains and agentic workflows
- **Together AI**: AI model provider for LLM integration
- **Synthea**: Synthetic patient generator providing realistic medical data

## 📋 Prerequisites

To run these notebooks, you'll need:
- Python 3.8+
- NVIDIA GPU with CUDA support (for maximum performance)
- ArangoDB cloud instance or local installation
- API keys for Together AI or other LLM provider

## 🔗 Additional Resources

- [ArangoDB Documentation](https://www.arangodb.com/docs/)
- [NVIDIA cuGraph Documentation](https://docs.rapids.ai/api/cugraph/stable/)
- [LangChain Documentation](https://python.langchain.com/docs/get_started/introduction)
- [Synthea Project](https://synthea.mitre.org/)

## 📜 License

This project is licensed under the [MIT License](LICENSE).

## 👤 Author

- **Ajito Nelson**
  - GitHub: [ajitonelsonn](https://github.com/ajitonelsonn)
 
---

Made with ❤️ in **Timor-Leste** 🇹🇱
