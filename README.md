# 🚀 Context-Aware NLP System for Geospatial Data Retrieval

## 🌟 Overview
This project aims to develop a context-aware NLP system for geospatial data retrieval, leveraging cutting-edge AI and NLP technologies combined with efficient backend and frontend solutions. The system will interpret complex geospatial queries, infer implicit spatial information, and retrieve relevant geospatial data accurately.

## 🛠️ Tech Stack

### 📡 Backend
- **FastAPI**: High-performance Python web framework
- **MongoDB**: Scalable NoSQL database
- **Langchain**: AI model integration and vector DB management
- **ChatOllama (phi3/llama3)**: Contextual response generation
- **Chroma**: Vector database for semantic search

### 💻 Frontend
- **React**: Dynamic UI development
- **Material-UI**: Polished component library

### 🧠 NLP and AI
- **HuggingFace Transformers**: Advanced NLP models

## 🛤️ Approach
1. **📝 Query Processing**: Incoming natural language queries are processed using HuggingFace Transformers.
2. **🔍 Context Inference**: ChatOllama analyzes the query to extract implicit geospatial information.
3. **📊 Data Embedding**: Relevant geospatial data is embedded using NLP models.
4. **🔎 Semantic Search**: Chroma performs semantic searches on the embedded data.
5. **⚙️ Result Generation**: The system compiles relevant geospatial data and generates a contextually accurate response.
6. **🖥️ Presentation**: Results are displayed through the React-based UI for interactive exploration.

## 🌟 USP of the Proposed Solution
- **🔗 Unique Integration**: Combines Langchain's AI capabilities with ChatOllama's contextual understanding for nuanced geospatial query interpretation.
- **🔍 Semantic Search**: Efficient and accurate semantic searches enabled by Chroma, outperforming traditional keyword-based systems.
- **🧠 Context Awareness**: Understands complex queries and infers implicit geospatial context, enabling more accurate data retrieval.

## 🚀 List of Features Offered by the Solution
- 📝 Natural language query processing for geospatial data
- 🔍 Context-aware inference of implicit geospatial information
- 🔎 Semantic search capabilities for geospatial datasets
- 🌍 Interactive visualization of retrieved geospatial data
- 💾 Scalable data storage and retrieval system
- ⏱️ Real-time query processing and response generation
- 👥 User-friendly interface for query input and result exploration
- 🌐 Integration with various geospatial data formats and sources
- 🎨 Customizable result presentation based on data types and user preferences

## 🏛️ Architecture Diagram
![Architecture Diagram](https://github.com/Aakashdeep-Srivastava/GeospatialLLM/blob/main/Frontend.png)

## 📚 Data Sources
1. **🌐 NASA Earth Data**: [earthdata.nasa.gov](https://earthdata.nasa.gov/)
2. **🗺️ USGS Earth Explorer**: [earthexplorer.usgs.gov](https://earthexplorer.usgs.gov/)
3. **🌍 OpenStreetMap Data Extracts**: [download.geofabrik.de](https://download.geofabrik.de/)
4. **🗺️ Natural Earth**: [naturalearthdata.com](https://www.naturalearthdata.com/)
5. **📊 EuroStat**: [ec.europa.eu/eurostat/web/gisco/geodata/reference-data](https://ec.europa.eu/eurostat/web/gisco/geodata/reference-data)

### 🌍 Geospatial-related Text Corpora
1. **🛰️ arXiv (Earth and Space Sciences category)**: [arxiv.org/list/earth/recent](https://arxiv.org/list/earth/recent)
2. **📚 CORE**: [core.ac.uk](https://core.ac.uk/)
3. **🚀 NASA Technical Reports Server**: [ntrs.nasa.gov](https://ntrs.nasa.gov/search.jsp)
4. **🌊 NOAA Central Library**: [library.noaa.gov](https://library.noaa.gov/)
5. **🔍 OpenAIRE**: [explore.openaire.eu](https://explore.openaire.eu/)

### 📰 For News Articles and Reports
1. **🔍 Google Dataset Search**: [datasetsearch.research.google.com](https://datasetsearch.research.google.com/)
2. **📊 Kaggle Datasets**: [kaggle.com/datasets](https://www.kaggle.com/datasets)

## 📄 Research Papers
1. A research paper on the underlying technology and methodology will be included once it is formally published.

## ⚙️ How to Run the Project
1. Clone the repository:
    ```bash
    git clone https://github.com/Aakashdeep-Srivastava/GeospatialLLM.git
    cd GeospatialLLM
    ```
2. Set up the backend:
    - Install the required dependencies:
      ```bash
      pip install -r requirements.txt
      ```
    - Run the FastAPI server:
      ```bash
      uvicorn app.main:app --reload
      ```
3. Set up the frontend:
    - Navigate to the frontend directory:
      ```bash
      cd frontend
      ```
    - Install npm dependencies:
      ```bash
      npm install
      ```
    - Start the React application:
      ```bash
      npm start
      ```
