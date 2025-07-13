🧬 FractiData

FractiData is a modular, fractal-aware AI data agent that enriches and structures training data using recursive feature engineering and entropy-aware tagging. Built on LangChain, integrated with Pinecone vector storage, and deployable via Docker, FractiData exposes a clean API layer to support data-rich apps across the FractiEcosystem — including FractiVerse, FractiAgent, FractiScope, and more.

⸻

🌐 Overview

FractiData is designed to layer additional fractal structure and recursive intelligence into any data pipeline, particularly for ML/AI workloads. It improves data retrievability, feature salience, and intelligence routing by enriching data with:
	•	🌀 Fractal tags
	•	🔁 Recursive features
	•	📈 Entropy/complexity metrics
	•	🧬 Genetic data lineage chains

It acts as an AI agent API that receives raw or ScaleAI-enriched data and transforms it into a higher-order structured format for querying, training, and real-time interaction.

⸻

🛠️ Tech Stack

Component	Purpose
Python	Core agent and data processing
LangChain	Agent orchestration, tool routing
Pinecone	Vector database for semantic search
FastAPI	RESTful API layer
Docker	Containerized deployment
FAISS or Chroma	(Optional) Local fallback for vector DB


⸻

📦 Features
	•	🔍 Fractal Data Enrichment: Add meaningful fractal layers to training data
	•	🧠 Recursive Feature Engineering: Captures higher-order relationships in data
	•	🔗 Genetic Chain Tracing: Keeps metadata lineage for feature evolution
	•	📡 LangChain Agent: Modular tools with real-time extensibility
	•	🧰 API-First: Can be accessed from any frontend, app, or agent
	•	📊 Vector Search-Ready: Pushes enriched documents to Pinecone

⸻

📈 Data Processing Pipeline

Raw Training Data → [Scale AI] → [FractiData Agent] → Pinecone Vector DB
                                         |
                                         ↓
                           Fractal tags, entropy scores,
                           recursive features, vectors


⸻

📂 Folder Structure

fractidata/
├── fractidata/
│   ├── agent.py           # LangChain agent logic
│   ├── enrichment.py      # Fractal data augmentation
│   ├── vector_store.py    # Pinecone vector store integration
│   ├── api.py             # FastAPI interface
│   └── utils.py           # Utility functions
├── tests/
│   └── test_api.py
├── Dockerfile
├── docker-compose.yml
├── requirements.txt / pyproject.toml
└── README.md


⸻

🚀 Quick Start

1. Clone & Build

git clone https://github.com/your-org/fractidata.git
cd fractidata
docker build -t fractidata .

2. Run Locally

docker run -p 8000:8000 fractidata

3. Try the API

Visit http://localhost:8000/docs for FastAPI’s interactive documentation.

⸻

🧪 Example API Calls

Vectorize Example (POST /vectorize)

Input (JSON):

{
  "text": "The pedestrian walked across the intersection while the car waited.",
  "source": "scale_ai_annotated"
}

FractiData Output:

{
  "fractal_tags": ["spatial_relation", "cause-effect", "attention"],
  "recursive_features": {
    "subject_action_pairs": ["pedestrian-walked", "car-waited"],
    "time_order": ["before", "after"]
  },
  "entropy_score": 0.78,
  "vector_id": "doc_123456"
}


⸻

🧠 Why FractiData > Scale AI Alone?

Feature	Scale AI	FractiData
Basic annotation	✅	✅ (used as input)
Vectorization	❌	✅
Fractal semantic enrichment	❌	✅
Recursive feature chains	❌	✅
Intelligent query interface	❌	✅
Genetic metadata tracing	❌	✅


⸻

📤 Deployment Targets
	•	Docker: Fast local and cloud deployment
	•	GCP / AWS / Azure: Easily ported as container or API service
	•	Modal / Replicate / HuggingFace Spaces: For lightweight web-scale serving
	•	FractiAgent API Hub: Plug into ecosystem of intelligent agents

⸻

👨‍💻 Contributing

Pull requests and forks welcome. To add your own fractal tools or processing modules, see agent.py and submit a plugin spec.

⸻

🌀 License

MIT – Fractal data belongs to everyone.

⸻