# Hi there, I'm Dheeraj Kumar Maradana 👋

[![IIT Bombay](https://img.shields.io/badge/IIT%20Bombay-B.Tech%20Computer%20Science%20%26%20Engineering-blue.svg)](https://www.cse.iitb.ac.in/)
[![Email](https://img.shields.io/badge/Email-dheerajkumarmaradana%40gmail.com-red.svg)](mailto:dheerajkumarmaradana@gmail.com)

Senior Undergraduate in **Computer Science and Engineering at the Indian Institute of Technology Bombay (IIT Bombay)**. My interests span **Computer Architecture**, **Deep Learning**, **Climate Science**, **GeoML**

---

## 🚀 Key Highlights & Achievements

* **Experience**: Incoming / Former **Software Engineering Intern at Google** (Pre-Silicon DMA Simulation Acceleration & Driver Development for TPU On-Chip Networks).
* **Research**: Topic Modeling & NLP Pipeline Researcher with **Prof. Ramit Debnath, University of Cambridge** (Topic extraction over 1M+ multi-decade articles).


---

## 🛠️ Featured Projects & Research

### 🖥️ Systems, Networking & Hardware Architecture

* [**Hardware-Conscious-Performance-Engineering**](https://github.com/dheerajkumar2005/Hardware-Conscious-Performance-Engineering)  
  *CS 683 (Advanced Computer Architecture), IIT Bombay*  
  High-performance kernel engineering optimizing compute-bound algorithms:
  * **2D Convolution**: Loop interchange (unit-stride streaming), register unrolling, L1D cache tiling, and handwritten 256-bit **AVX2 SIMD intrinsics with FMA (`_mm256_fmadd_ps`)**.
  * **SGEMM in `llama.cpp`**: Custom cache-blocked, software-prefetched SGEMM matrix multiplication directly injected into the `llama.cpp` inference engine.
  * Hardware performance counter profiling via Linux `perf` (Instructions, IPC, L1-D MPKI).

* [**Multi-Threaded-Plagiarism-Detector**](https://github.com/dheerajkumar2005/Multi-Threaded-Plagiarism-Detector)  
  *CS 293 (Data Structures and Algorithms), IIT Bombay | Guide: Prof. Ashutosh Gupta*  
  * Concurrent C++ code similarity engine detecting patchwork and structural code plagiarism.
  * Real-time streaming submission ingestion powered by a dual-thread producer-consumer pipeline with mutexes, reader-writer locks (`std::shared_mutex`), and condition variables.
  * Substring matching and pattern recognition leveraging Rabin-Karp **Rolling Hash algorithms** and tokenized AST abstractions.

* [**Link-State-Routing-Emulator**](https://github.com/dheerajkumar2005/Link-State-Routing-Emulator)  
  *CS 348 / CS 378 (Computer Networks), IIT Bombay | Guide: Prof. Bhaskaran Raman*  
  * Distributed virtual router emulation network communicating over raw POSIX TCP/UDP sockets.
  * Event-driven non-blocking I/O multiplexing via POSIX `select()` event loops.
  * Distributed Link State Advertisement (LSA) flooding and dynamic routing convergence via **Dijkstra's shortest path algorithm**.

---

### 🤖 Machine Learning, Computer Vision & Explainable AI

* [**SSD-Object-Detection-PyTorch**](https://github.com/dheerajkumar2005/SSD-Object-Detection-PyTorch)  
  *Deep Learning & Computer Vision | [Read Medium Article](https://medium.com/@dheerajkumarmaradana/ssd-single-shot-multibox-detector-d7d570bbbe6f)*  
  * Modular, clean PyTorch implementation of the **SSD300 (Single Shot MultiBox Detector)** from scratch on Pascal VOC 2007.
  * Features multi-scale feature pyramid heads, default box generation across 6 aspect ratios, 3:1 Hard Negative Mining, and Smooth L1 + Cross-Entropy MultiBox loss.

* [**Joint-Surrogate-Trees-Model-Differencing**](https://github.com/dheerajkumar2005/Joint-Surrogate-Trees-Model-Differencing)  
  *Artificial Intelligence & Machine Learning, IIT Bombay | Guide: Prof. Pushpak Bhattacharyya*  
  * Novel Explainable AI (XAI) framework for **Interpretable Model Differencing (IMD)**.
  * Trains a unified Joint Surrogate Tree (JST) simultaneously across the predictions of two black-box models to extract concise, human-readable propositional rules defining exact disagreement sub-spaces.

* [**Guided-BERTopic-Topic-Modeling**](https://github.com/dheerajkumar2005/Guided-BERTopic-Topic-Modeling)  
  *Research with University of Cambridge | Guide: Prof. Ramit Debnath*  
  * Scalable, GPU-accelerated NLP topic modeling pipeline over **1,000,000+ newspaper articles** spanning five decades (1961–2010).
  * Combines Guided BERTopic with RAPIDS `cuML` (GPU-accelerated UMAP & HDBSCAN) and interactive force-directed graph networks (PyVis & NetworkX).

* [**Remote-Sensing-Deep-Learning-GNR638**](https://github.com/dheerajkumar2005/Remote-Sensing-Deep-Learning-GNR638)  
  *GNR 638 (Machine Learning for Remote Sensing), IIT Bombay*  
  * Deep representation probing and transferability analysis of vision backbones (ResNet-50) on Earth Observation imagery.
  * Layer-wise probing, few-shot adaptation regimes, fine-tuning dynamics, and out-of-distribution robustness assessments.

* [**Time-Series-Forecasting-and-Modeling**](https://github.com/dheerajkumar2005/Time-Series-Forecasting-and-Modeling)  
  *CS 215 (Data Analysis & Interpretation), IIT Bombay | Guide: Prof. Sunita Sarawagi*  
  * Non-stationary time series forecasting using Augmented Dickey-Fuller tests, ACF/PACF order selection, and ARIMA/SARIMA/ETS models.
  * Non-parametric anomaly and transaction fraud detection via Epanechnikov Kernel Density Estimation (KDE) and rolling window feature statistics.

---

### 🔍 Information Retrieval & Search

* [**Sparse-Retrieval-Search-Engine**](https://github.com/dheerajkumar2005/Sparse-Retrieval-Search-Engine)  
  *CS 6101 (Indexing and Retrieving Text and Graphs), IIT Bombay*  
  * End-to-end information retrieval framework evaluating lexical and learned sparse models over the BEIR benchmark (SciFact, FEVER, HotpotQA, MSMARCO).
  * Implementations of Lucene/Pyserini inverted indexes, BM25 grid tuning, Rocchio & RM3 pseudo-relevance feedback, HyDE (LLM-generated queries), Doc2Query, and fine-tuned **SPLADE** neural representations.

---

## 💻 Technical Skills

| Domain | Technologies & Frameworks |
|---|---|
| **Languages** | C++, C, Python, Java, SystemVerilog, SQL, MIPS, Scheme, Bash |
| **Systems & Architecture** | POSIX Sockets, Pthreads, AVX2 SIMD, Cache Tiling, Linux `perf`, Docker, Make |
| **Machine Learning & Data** | PyTorch, Scikit-Learn, BERTopic, Transformers, Polars, cuML, Statsmodels, NumPy, Pandas |
| **Tools & Platforms** | Git, GitHub Actions, LaTeX, QEMU, UVM |

---

## 📬 Contact & Links

* **GitHub**: [@dheerajkumar2005](https://github.com/dheerajkumar2005)
* **Email**: [dheerajkumarmaradana@gmail.com](mailto:dheerajkumarmaradana@gmail.com) / [23b0920@iitb.ac.in](mailto:23b0920@iitb.ac.in)
* **Medium**: [@dheerajkumarmaradana](https://medium.com/@dheerajkumarmaradana)
