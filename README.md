# Hi there, I'm Dheeraj Kumar Maradana 👋

[![IIT Bombay](https://img.shields.io/badge/IIT%20Bombay-B.Tech%20Computer%20Science%20%26%20Engineering-blue.svg)](https://www.cse.iitb.ac.in/)
[![Email](https://img.shields.io/badge/Email-dheerajkumarmaradana%40gmail.com-red.svg)](mailto:dheerajkumarmaradana@gmail.com)

Senior Undergraduate in **Computer Science and Engineering at the Indian Institute of Technology Bombay (IIT Bombay)**. My interests span **Computer Architecture**, **Deep Learning**, **Climate Science**, **GeoML**

---

## 🚀 Key Highlights & Achievements

* **Experience**: Former **Software Engineering Intern at Google** (Pre-Silicon DMA Simulation Acceleration & Driver Development for TPU On-Chip Networks).
* **Research**: Topic Modeling & NLP Pipeline Researcher with **Prof. Ramit Debnath, University of Cambridge** (Topic extraction over 1M+ multi-decade articles).


---

## 🛠️ Featured Projects & Research

### 🖥️ Systems, Compilers & Architecture

* [**C-Compiler-From-Scratch**](https://github.com/dheerajkumar2005/C-Compiler-From-Scratch)  
  * Multi-stage optimizing compiler (`sclp`) written in C++ translating high-level procedural C into optimized MIPS assembly.
  * Complete compilation pipeline: Flex lexer, Bison LALR(1) parser, AST construction, intermediate Three-Address Code (TAC), Register Transfer Language (RTL), and target MIPS generation validated on SPIM.
  * Control-flow graph (CFG) analysis, basic block partitioning, local/global common subexpression elimination, constant folding, and register allocation.
 
* [**Discrete-Event-Server-Simulator**](https://github.com/dheerajkumar2005/Discrete-Event-Server-Simulator)  
  *CS 681 (Performance Analysis of Systems and Networks), IIT Bombay | Guide: Prof. Varsha Apte*  
  * Discrete-event simulation of multi-threaded web servers and closed queueing networks in modern C++.
  * Priority-queue scheduler modeling finite worker thread pools, stochastic think/service distributions, request timeouts, and tandem networks with feedback.
  * Rigorously validated against Mean Value Analysis (MVA) analytical queueing theory formulations.

* [**plagiarism-checker**](https://github.com/dheerajkumar2005/plagiarism-checker)  
  *CS 293 (Data Structures and Algorithms), IIT Bombay | Guide: Prof. Ashutosh Gupta*  
  * Concurrent C++ code similarity engine detecting patchwork and structural code plagiarism.
  * Real-time streaming submission ingestion powered by a dual-thread producer-consumer pipeline with mutexes, reader-writer locks (`std::shared_mutex`), and condition variables.
  * Substring matching and pattern recognition leveraging Rabin-Karp **Rolling Hash algorithms** and tokenized AST abstractions.

* [**Link-State-Routing-Emulator**](https://github.com/dheerajkumar2005/Link-State-Routing-Emulator)  
  *CS 348 / CS 378 (Computer Networks), IIT Bombay | Guide: Prof. Bhaskaran Raman*  
  * Distributed virtual router emulation network communicating over raw POSIX TCP/UDP sockets.
  * Event-driven non-blocking I/O multiplexing via POSIX `select()` event loops.
  * Distributed Link State Advertisement (LSA) flooding and dynamic routing convergence via **Dijkstra's shortest path algorithm**.
 
* [**AES-Side-Channel-Key-Recovery**](https://github.com/dheerajkumar2005/AES-Side-Channel-Key-Recovery)  
  *CS 6102 (Implementation Security in Cryptography), IIT Bombay | Guide: Prof. Sayandeep Saha*  
  * Hardware-software $GF(2^4)$ finite-field multiplier in Verilog HDL and cycle-benchmarked C++ with AES key expansion (`expandSK`).
  * Correlation Power Analysis (CPA) and multivariate Gaussian template attack pipeline extracting 128-bit AES secret keys from power consumption traces.

* [**Hardware-Conscious-Performance-Engineering**](https://github.com/dheerajkumar2005/Hardware-Conscious-Performance-Engineering)  
  *CS 683 (Advanced Computer Architecture), IIT Bombay*  
  High-performance kernel engineering optimizing compute-bound algorithms:
  * **2D Convolution**: Loop interchange (unit-stride streaming), register unrolling, L1D cache tiling, and handwritten 256-bit **AVX2 SIMD intrinsics with FMA (`_mm256_fmadd_ps`)**.
  * **SGEMM in `llama.cpp`**: Custom cache-blocked, software-prefetched SGEMM matrix multiplication directly injected into the `llama.cpp` inference engine.
  * Hardware performance counter profiling via Linux `perf` (Instructions, IPC, L1-D MPKI).

* [**Database-Systems-Engineering-CS349**](https://github.com/dheerajkumar2005/Database-Systems-Engineering-CS349)  
  *CS 349 (Database and Information Systems), IIT Bombay*  
  * Production-grade database engineering spanning relational schema design, query optimization, and modern distributed data pipelines.
  * Query execution & profiling with `EXPLAIN ANALYZE`, indexing (B-Tree/Hash), trigger-based audit logging, and full-stack MVC applications (Node.js/EJS, React, React Native).
  * Distributed data pipelines with Apache Kafka message streaming, PySpark batch analytics, Docker orchestration, and semantic search via `pgvector` RAG embeddings.



---

### 🤖 Machine Learning, Computer Vision & Scientific Computing

* [**Poke-bot**](https://github.com/dheerajkumar2005/Poke-bot)  
  *Reinforcement Learning & Game AI*  
  * Transformer-based Reinforcement Learning agent trained for competitive Pokémon Showdown Gen 9 Random Battles.
  * Explores self-play policies, belief state modeling, and action space optimization under partial observability.

* [**SSD-Object-Detection-PyTorch**](https://github.com/dheerajkumar2005/SSD-Object-Detection-PyTorch)  
  *Deep Learning & Computer Vision | [Read Medium Article](https://medium.com/@dheerajkumarmaradana/ssd-single-shot-multibox-detector-d7d570bbbe6f)*  
  * Modular, clean PyTorch implementation of the **SSD300 (Single Shot MultiBox Detector)** from scratch on Pascal VOC 2007.
  * Features multi-scale feature pyramid heads, default box generation across 6 aspect ratios, 3:1 Hard Negative Mining, and Smooth L1 + Cross-Entropy MultiBox loss.

* [**Joint-Surrogate-Trees-Model-Differencing**](https://github.com/dheerajkumar2005/Joint-Surrogate-Trees-Model-Differencing)  
  *Artificial Intelligence & Machine Learning, IIT Bombay | Guide: Prof. Pushpak Bhattacharyya*  
  * Novel Explainable AI (XAI) framework for **Interpretable Model Differencing (IMD)**.
  * Trains a unified Joint Surrogate Tree (JST) simultaneously across the predictions of two black-box models to extract concise, human-readable propositional rules defining exact disagreement sub-spaces.

* [**Remote-Sensing-Deep-Learning**](https://github.com/dheerajkumar2005/Remote-Sensing-Deep-Learning)  
  *GNR 638 (Machine Learning for Remote Sensing), IIT Bombay*  
  * Deep representation probing and transferability analysis of vision backbones (ResNet-50) on Earth Observation imagery.
  * Layer-wise probing, few-shot adaptation regimes, fine-tuning dynamics, and out-of-distribution robustness assessments.



* [**Time-Series-Forecasting-and-Modeling**](https://github.com/dheerajkumar2005/Time-Series-Forecasting-and-Modeling)  
  *CS 215 (Data Analysis & Interpretation), IIT Bombay | Guide: Prof. Sunita Sarawagi*  
  * Non-stationary time series forecasting using Augmented Dickey-Fuller tests, ACF/PACF order selection, and ARIMA/SARIMA/ETS models.
  * Non-parametric anomaly and transaction fraud detection via Epanechnikov Kernel Density Estimation (KDE) and rolling window feature statistics.

* [**NYC-Taxi-Spatial-Temporal-Analysis**](https://github.com/dheerajkumar2005/NYC-Taxi-Spatial-Temporal-Analysis)  
  *CS 215 (Data Analysis & Interpretation), IIT Bombay | Guide: Prof. Sunita Sarawagi*  
  * Spatial-temporal exploratory data analysis, transit hub coordinate clustering, and trip duration regression over NYC Yellow Taxi trajectory records.

---

### 🔍 Information Retrieval & Search

* [**Sparse-Retrieval**](https://github.com/dheerajkumar2005/Sparse-Retrieval)  
  *CS 6101 (Indexing and Retrieving Text and Graphs), IIT Bombay*  
  * End-to-end information retrieval framework evaluating lexical and learned sparse models over the BEIR benchmark (SciFact, FEVER, HotpotQA, MSMARCO).
  * Implementations of Lucene/Pyserini inverted indexes, BM25 grid tuning, Rocchio & RM3 pseudo-relevance feedback, HyDE (LLM-generated queries), Doc2Query, and fine-tuned **SPLADE** neural representations.

---
### Others

* [**BB626-Biophysics-Simulations**](https://github.com/dheerajkumar2005/BB626-Biophysics-Simulations)  
  *BB 626 (Biophysics & Statistical Mechanics), IIT Bombay*  
  * Computational physics and statistical mechanics simulations using stochastic Monte Carlo and Langevin dynamics algorithms.
  * Metropolis-Hastings 1D & 2D Ising model simulating spontaneous magnetization, magnetic susceptibility, and second-order phase transitions.
  * Polymer chain scaling dynamics (Freely-Jointed & Freely-Rotating chains) and overdamped Brownian particle diffusion across harmonic and bistable potential landscapes.

---

## 💻 Technical Skills

| Domain | Technologies & Frameworks |
|---|---|
| **Languages** | C++, C, Python, JavaScript, Java, SystemVerilog, SQL, MIPS, Scheme, Bash |
| **Systems & Architecture** | POSIX Sockets, Pthreads, AVX2 SIMD, Cache Tiling, Linux `perf`, Docker, Make, Flex, Bison |
| **Databases & Distributed** | PostgreSQL, pgvector, Apache Kafka, Apache Spark (PySpark), Redis |
| **Machine Learning & Data** | PyTorch, Scikit-Learn, BERTopic, Transformers, Polars, cuML, NumPy, Pandas, SciPy |
| **Web & Frameworks** | Node.js, Express, React, React Native, EJS, HTML5/CSS3 |
| **Tools & Platforms** | Git, GitHub Actions, LaTeX, QEMU, UVM |

---

## 📬 Contact & Links

* **GitHub**: [@dheerajkumar2005](https://github.com/dheerajkumar2005)
* **Email**: [dheerajkumarmaradana@gmail.com](mailto:dheerajkumarmaradana@gmail.com) / [23b0920@iitb.ac.in](mailto:23b0920@iitb.ac.in)
* **Medium**: [@dheerajkumarmaradana](https://medium.com/@dheerajkumarmaradana)
