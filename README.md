# 🧠 FractiData  
**Fractal Intelligence for Smarter AI Training Data**

FractiData is a modular AI agent that transforms raw or labeled datasets into enriched, fractal-structured data. It applies recursive feature engineering, entropy analysis, and curriculum-aware routing to improve data quality, insight, and model outcomes.

---

## 🚀 Features

- 📊 **Fractal Enrichment** – Adds entropy, self-similarity, and complexity metrics
- 🔁 **Recursive Feature Engineering** – Derives features at multiple resolutions
- 🧠 **Curriculum Routing** – Segments data by learning difficulty and relevance
- 🆔 **FractalID Indexing** – Multiscale metadata for smart filtering and analysis
- ⚡ **FastAPI + Docker Ready** – Deployable anywhere (Cloud, Local, Modal, etc.)

---

## 📂 Input & Output Formats

| Input | Output | Description |
|-------|--------|-------------|
| JSON, JSONL, COCO, Scale AI | JSONL, Parquet | Enriched with fractal stats, routing class, tags |

---

## 🔧 Quick Start

### 1. Clone & Run
```bash
git clone https://github.com/your-org/fractidata.git
cd fractidata
docker-compose up --build

2. Call the API

curl -X POST http://localhost:8000/enrich \
  -F 'file=@your_dataset.json'


⸻

🧬 Example (Python)

from fractidata.agent import FractiAgent

agent = FractiAgent()
enriched = agent.enrich("scale_labeled_data.json")
enriched.to_parquet("fractal_output.parquet")


⸻

💡 Use Cases
	•	Fine-tuning foundation models (e.g., LLMs, vision models)
	•	Data curriculum learning and routing optimization
	•	Entropy and complexity profiling for edge case discovery
	•	Scaling smart data ops beyond labeling

⸻

🛠️ Tech Stack
	•	Python 3.11, FastAPI
	•	Pandas, Polars, PyWavelets
	•	Docker, LangChain (optional agent mode)
	•	S3/GCS compatible

⸻

🌐 Deploy Anywhere
	•	Modal (serverless Python)
	•	Google Cloud Run / AWS Fargate
	•	Hugging Face Spaces
	•	Self-hosted (Docker Compose)

⸻

📜 License

MIT License © 2025 FractiAI

⸻

🤝 Contribute

Pull requests, issues, and feature ideas welcome!
Let’s build a smarter AI data ecosystem—fractal by design.
