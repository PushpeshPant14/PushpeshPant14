<div align="center">

# Pushpesh Pant
### **AI & Software Engineer | Generative AI • RAG Systems • Full-Stack ML**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/pushpesh-pant14)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/PushpeshPant14)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=black)](https://leetcode.com/u/PushpeshPant19)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:pushpeshpant19@gmail.com)

<p align="center">
  <i>Designing and building scalable AI systems, low-latency LLM pipelines, and production-grade software applications.</i>
</p>

</div>

---

## 📌 Executive Summary

I am an **AI and Software Engineer** currently pursuing my **Master of Computer Applications (MCA)**. My work centers on the intersection of **applied Generative AI, high-throughput vector retrieval, and scalable backend engineering**. 

Rather than treating AI models as black boxes, I focus on building complete, deterministic, and optimized architectures—ranging from **dual-execution fallback pipelines** and **4-bit quantized edge inference** to **low-latency RAG systems**.

---

## 🎯 Core Technical Focus

* **Generative AI & RAG Architectures:** Designing end-to-end Retrieval-Augmented Generation workflows utilizing hybrid retrieval (dense + sparse), multi-turn conversation state, and page-level source attribution.
* **Inference Optimization & Deployment:** Implementing 4-bit NF4 quantization (`BitsAndBytes`), batch vectorization using NumPy matrix operations, and high-throughput LLM tool-calling (`Groq`, `Gemini API`).
* **Robust Backend & Schema Engineering:** Guaranteeing structured LLM outputs using strict Pydantic validation, deterministic regex fallback heuristics, and clean MVVM/repository architectural patterns.

---

## 🛠️ Technical Arsenal

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages** | Python, Java, SQL, C++ |
| **Generative AI & LLMs** | LangChain, Groq API, Google Gemini API, Hugging Face Transformers, Whisper ASR, Prompt Engineering |
| **Vector DBs & Embeddings** | ChromaDB, FAISS, Sentence-Transformers (`all-MiniLM-L6-v2`) |
| **Machine Learning & Data** | Scikit-Learn, TensorFlow, NumPy, Pandas, Matplotlib, Seaborn, Pydantic |
| **Frameworks & API** | Streamlit, Flask, Gradio, REST APIs |
| **Databases & Cloud** | MySQL, Firebase (Firestore, Auth), AWS Elastic Beanstalk, Docker, Git |

---

## 🚀 Featured Engineering Projects

### 1. [AI Resume Ranking & ATS Matching System](https://github.com/PushpeshPant14/resume-ranking)
> **High-throughput candidate evaluation engine featuring structured LLM extraction and vectorized semantic matching.**

* **Dual-Execution Pipeline:** Implemented a resilient parsing architecture combining Groq LLaMA-3.3 structured tool-calling with zero-API regex heuristics for guaranteed schema validation.
* **Vectorized Throughput (5x–10x Speedup):** Replaced sequential embedding calculations with batch vectorized embeddings (`all-MiniLM-L6-v2`) and NumPy dot-product matrix operations.
* **Precise Entity Matching:** Engineered a token-boundary regex matching engine with technical synonym matrix mapping (`ML` ↔ `Machine Learning`, `AWS` ↔ `Amazon Web Services`) to eliminate false substring positives.
* **Stack:** `Python`, `LangChain`, `ChromaDB`, `FAISS`, `Groq API`, `Pydantic`, `Streamlit`

---

### 2. [Multi-PDF Conversational RAG Assistant](https://github.com/PushpeshPant14)
> **Multi-turn document intelligence platform with source verification and dual-vector storage.**

* **Dual Vector Store Architecture:** Integrated FAISS for low-latency in-memory query retrieval alongside ChromaDB for persistent storage using 3072-dimensional Gemini embeddings.
* **Grounded Citations:** Implemented chunk-level metadata tracking with real-time typewriter token streaming and expandable citation cards (document name, page number, context slice).
* **Stack:** `Python`, `LangChain`, `ChromaDB`, `FAISS`, `Gemini API`, `Streamlit`

---

### 3. [MinuteAI — Automated Meeting Minutes System](https://github.com/PushpeshPant14)
> **Audio-to-intelligence pipeline for long-form meeting transcription and automated agenda extraction.**

* **Audio Processing & ASR:** Built an end-to-end transcription pipeline using `openai/whisper-medium.en` via Hugging Face.
* **Edge & GPU Optimization:** Deployed `meta-llama/Llama-3.2-3B-Instruct` with **4-bit NF4 quantization** via `BitsAndBytesConfig`, significantly reducing memory footprint for rapid inference on consumer GPUs.
* **Structured Output:** Engineered deterministic prompt workflows to extract structured discussion notes, decisions, and assignable action items.
* **Stack:** `Python`, `Transformers`, `Whisper`, `LLaMA-3.2`, `BitsAndBytes`, `PyTorch`

---

### 4. [CampusCare — Campus Incident Management](https://github.com/PushpeshPant14)
> **Production Android application for real-time issue reporting, image evidence verification, and resolution workflows.**

* **Clean Architecture:** Built using Android **MVVM + Repository pattern** with ViewBinding for separation of concerns and maintainability.
* **Real-time Synchronization:** Integrated Firebase Firestore for live status feeds and `FileProvider` for secure on-device camera evidence capture.
* **Stack:** `Java`, `Android SDK`, `Firebase (Auth, Firestore)`, `MVVM`

---

## 📈 GitHub Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=PushpeshPant14&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Pushpesh's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PushpeshPant14&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top Languages" width="48%" />
</div>

---

## 📬 Contact & Collaboration

I am always interested in discussing software engineering opportunities, Generative AI research, and high-impact technical collaborations.

* **Email:** [pushpeshpant19@gmail.com](mailto:pushpeshpant19@gmail.com)
* **LinkedIn:** [linkedin.com/in/pushpesh-pant](https://linkedin.com/in/pushpesh-pant14)
* **GitHub:** [github.com/PushpeshPant14](https://github.com/PushpeshPant14)
* **LeetCode:** [leetcode.com/u/PushpeshPant14](https://leetcode.com/u/PushpeshPant19)
