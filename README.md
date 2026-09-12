# Hi, I'm Kethan 👋

**AI/ML engineer building end-to-end autonomous driving systems** from VLM-based navigation to LLM fine-tuning. OpenCV open source contributor. Top 11% on Kaggle.

I like problems where models meet the real world: a wrong token is a metric, a wrong trajectory is a braking event.

---

## 🚗 Autonomous driving - TiHAN, IIT Hyderabad

Research Intern, May–Aug 2026. Code is proprietary, so here's what I actually worked on:

- **RL post-training for TiTAN**, an end-to-end VLM navigation stack (Qwen3-based) that matched SOTA trajectory accuracy in real time stabilized early training collapse and shaped rewards around steady progress and correct steering
- **Map-free RL reward signal** built from real-time safety checks (TTC, occupancy, drivable area, vehicle dynamics), replacing HD-map-dependent PDM scoring so rewards could be evaluated on unmapped Indian road data
- **Sub-1ms safety layer** scoring every planned trajectory against those same checks, triggering AEB or a replan once risk crosses threshold. Thresholds derived from physics to give clean actionable STOP/PROCEED signals
- **Monocular TTC on a live vehicle** - Time-to-Collision estimated from bounding-box growth across frames, fed per-frame from a YOLO11n detector into a fail-safe
- **Benchmarking** on H200 and A100 clusters against Delhi and Waymo driving datasets
- **Self-hosted HMI dashboard** for the vehicle OSRM routing on real roads, destination search, split-screen ride view, live telemetry (speed, distance remaining, ETA), packaged as a Docker repo with India OSM → routing-graph scripts

---

## 🛠️ Open source

- **[OpenCV](https://github.com/opencv/opencv)** - `cv::aruco::Board` setters ([PR #28600](https://github.com/opencv/opencv/pull/28600), under review); CV_16F HDF5 support in opencv_contrib 
- **[vLLM](https://github.com/vllm-project/vllm)** - InternVL2 multimodal support under transformers v5: HF converter fixes, native v5 loading, test un-skips *(in progress)*

---

## 🏆 Competitions & applied research - [Kaggle](https://www.kaggle.com/kethansaikoneru)

**CAFA 6 - Protein Function Prediction**
Deep-learning pipeline predicting hierarchical Gene Ontology labels from protein sequences. Custom hierarchical loss function, submission score **0.396**.

**AI Mathematical Olympiad - Progress Prize 3**
Served GPT-OSS-120B via vLLM on a Kaggle H100; tuned sampling and majority-vote selection to a best score of **40**. Fine-tuned the base model with Unsloth QLoRA on NuminaMath-CoT for stronger chain-of-thought reasoning.

**Road Accident Severity Prediction**
Tuned XGBoost on real-world accident data - **top 11%**, driven by feature engineering and cross-validation.

---

## 📦 Projects

**Lung Cancer Diagnosis**: PyTorch, AlexNet, Medical Imaging
AlexNet classifier on a 500K+ datapoint imaging dataset 89.65% accuracy (P 0.92 / R 0.85 / F1 0.80) with image-reconstruction preprocessing.

**Resume Builder**: FastAPI, React, Vite
Full-stack resume generator with JWT auth, customizable PDF generation, and real-time preview.

---

## ⚙️ Stack


- **Languages**: Python, C++, Java, SQL, JavaScript
- **ML/AI**: PyTorch, Hugging Face, Transformers, vLLM, Unsloth QLoRA, TensorFlow/Keras, XGBoost, scikit-learn
- **DL & NLP**: CNNs, Transformers, LLM fine-tuning, RAG, BM25, multilingual embeddings
- **Web & Backend**: React, Node, Express, FastAPI, Vite, Supabase
- **Tools**: Git · Docker, CMake, Linux, Jupyter

---

## 📫 Reach me

[Portfolio](https://kethansai.vercel.app) · [LinkedIn](https://www.linkedin.com/in/kethan-sai-koneru-64b722236/) · [Kaggle](https://www.kaggle.com/kethansaikoneru) · kethan1701@gmail.com

*B.Tech IT, VNR VJIET · Hyderabad, India*
