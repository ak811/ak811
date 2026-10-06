Hi, I'm Ali Rahimian, and these are some highlights from my CV:

- Lead developer of [Fibottention](https://github.com/Charlotte-CharMLab/Fibottention), $O(N \log N)$ sparse attention for images, video, and robotics
- Co-author of [TruthLens](https://icml.cc/virtual/2025/51033) (ICML 2025), a training-free deepfake detection framework built on VLMs
- More than 8 years of experience (as ML researcher, software engineer, data engineer, and founder)
- Founded IRSoft; solo-built Android apps to 3.5M+ installs, 4.7★ from 120K+ reviews
- Lots of teaching and mentoring experience (as a teaching assistant, ESL instructor, and mentor)
- Former ML Engineer/Researcher at Charlotte Machine Learning Lab (under Dr. Christian Kümmerle)
- M.S. in Computer Science at UNC Charlotte (thesis on diverse multi-head sparse attention)
- B.S. in Computer Software Engineering at Yazd University (ranked 1st for three consecutive years)
- Multiple contest awards (ICPC Tehran Regional HM, 2nd JCAL, 3rd Sharif Fintech, 4th Obfuscated C)
- Open to ML Engineer, Software Engineer, and Data Scientist roles (US, on-site/hybrid/remote)

**Email:** [akhalegh@charlotte.edu](mailto:akhalegh@charlotte.edu) · **LinkedIn:** [alikrahimian](https://www.linkedin.com/in/alikrahimian) · **Scholar:** [Ali Rahimian](https://scholar.google.com/citations?user=MIelP8kAAAAJ&hl=en) · **YouTube:** [Ali Rahimian](https://www.youtube.com/watch?v=uyY6moVA-RA)

### Selected open source

- **[Fibottention](https://github.com/Charlotte-CharMLab/Fibottention)** – ViT sparse attention, $O(N^2) \to O(N \log N)$, for images, video, and robotics

- **[TruthLens](https://github.com/ak811/TruthLens)** – Training-free deepfake detection via VQA-style probing of vision-language models; ICML 2025

- **[Sparxiv](https://github.com/thejasprab/Sparxiv)** – Spark recommender over 3M+ arXiv papers: Parquet ETL, MLlib TF-IDF, CSR top-k search

- **[CTRL](https://github.com/ak811/CTRL)** – Cross-task RL with PPO transfer, Reptile meta-learning, and EWC continual learning

- **[Ase](https://github.com/ak811/Ase)** – Multilingual BM25 search engine in Java: SPIMI, positional phrase queries, Porter stemming

<details>
<summary><h4>More projects by topic</h4></summary>

### Deep Learning & ML Research

#### Efficient Transformers & Sparse Attention

- [Fibottention](https://github.com/Charlotte-CharMLab/Fibottention) – ViT sparse attention, $O(N^2) \to O(N \log N)$, for images, video, and robotics
- [two-percent-attention](https://github.com/ak811/two-percent-attention) – Sparse attention for ViTs at 2% of dense attention FLOPs, benchmarked across 10 mechanisms
- [transformer-encoder-from-scratch](https://github.com/ak811/transformer-encoder-from-scratch) – Transformer encoder in PyTorch, built up from scaled dot-product attention to a full stack

#### Model Compression

- [linear-quantization-from-scratch](https://github.com/ak811/linear-quantization-from-scratch) – Linear quantization in PyTorch from first principles, down to int8 multiply + int32 accumulate
- [vgg-magnitude-pruning](https://github.com/ak811/vgg-magnitude-pruning) – PyTorch implementation of Han et al. magnitude pruning on VGG

#### Vision-Language & Representation Learning

- [TruthLens](https://github.com/ak811/TruthLens) – Training-free deepfake detection via VQA-style probing of vision-language models; ICML 2025
- [oneshot-openclip-tta](https://github.com/ak811/oneshot-openclip-tta) – One-shot OpenCLIP classification with confidence-gated test-time prototype adaptation
- [moco-joint-ssl-training](https://github.com/ak811/moco-joint-ssl-training) – MoCo contrastive learning trained jointly with a supervised head from scratch
- [vit-imagenet21k-finetune](https://github.com/ak811/vit-imagenet21k-finetune) – ImageNet-21k ViT-B/16 fine-tuned for 16-class image classification: 96.75% test accuracy

#### Reinforcement Learning

- [CTRL](https://github.com/ak811/CTRL) – Cross-task RL with PPO transfer, Reptile meta-learning, and EWC continual learning
- [ppo-clip-lunarlander-v3](https://github.com/ak811/ppo-clip-lunarlander-v3) – From-scratch PPO-Clip on LunarLander-v3: categorical actor-critic, normalized GAE(λ), clip-ε decay
- [sb3-ppo-clip-carracing-v3](https://github.com/ak811/sb3-ppo-clip-carracing-v3) – SB3 PPO-Clip + GAE(λ) on CarRacing-v3 with CNN over 4 stacked 84×84 frames
- [dqn-replay-noise-ablation](https://github.com/ak811/dqn-replay-noise-ablation) – DQN ablation of prioritized vs uniform vs online replay, parameter noise vs ε-greedy
- [dqn-ddqn-pong-v5](https://github.com/ak811/dqn-ddqn-pong-v5) – DQN + Double DQN on ALE/Pong-v5 with replay, Huber loss, and difficulty 2–3 training
- [tabular-qlearning-frozenlake-v1](https://github.com/ak811/tabular-qlearning-frozenlake-v1) – Tabular Q-learning on FrozenLake-v1: Bellman TD updates with ε-greedy 1.0→0.01 decay

### ML Foundations & Classical AI

#### Classical ML from Scratch

- [logistic-regression-naive-bayes](https://github.com/ak811/logistic-regression-naive-bayes) – Multiclass logistic regression (GD/IRLS) and Gaussian/Bernoulli Naive Bayes from scratch
- [closed-form-ridge-regression](https://github.com/ak811/closed-form-ridge-regression) – Ridge vs. OLS via normal equations: log-spaced λ sweep with pairwise interaction features
- [nonlinear-decision-boundaries](https://github.com/ak811/nonlinear-decision-boundaries) – Nonlinear decision boundaries with a two-layer neural network

#### Optimization & Search

- [accelerated-gradient-methods](https://github.com/ak811/accelerated-gradient-methods) – Accelerated gradient methods: Momentum, Nesterov, and when theory misbehaves
- [gradient-descent-convergence](https://github.com/ak811/gradient-descent-convergence) – Gradient descent variants compared across quadratic, nonconvex, and least-squares tasks
- [cross-in-tray-optimization](https://github.com/ak811/cross-in-tray-optimization) – Genetic algorithm and simulated annealing for the Cross-in-Tray global optimization benchmark
- [pacman-search-agent](https://github.com/ak811/pacman-search-agent) – BFS/DFS/UCS/A* search agent with admissible Manhattan/Euclidean heuristics and a Pygame visualizer

#### Classical Computer Vision (OpenCV)

- [opencv-tracking-algorithms](https://github.com/ak811/opencv-tracking-algorithms) – Lucas-Kanade & Farneback optical flow, MeanShift/CAMShift, and OpenCV KCF/MIL trackers
- [watershed-image-segmentation](https://github.com/ak811/watershed-image-segmentation) – Segmentation with Watershed algorithm: median blur, contour detection, and custom seeds
- [hand-segmentation-convex-hull](https://github.com/ak811/hand-segmentation-convex-hull) – Hand segmentation & finger counting with Gaussian blur, contour detection, and convex hull
- [opencv-keypoint-detection](https://github.com/ak811/opencv-keypoint-detection) – Real-time Haar-cascade face/eye detection with median-adaptive Canny edge extraction

### Data Engineering & High-Performance Computing

#### Search & Recommendation

- [Sparxiv](https://github.com/thejasprab/Sparxiv) – Spark recommender over 3M+ arXiv papers: Parquet ETL, MLlib TF-IDF, CSR top-k search
- [Ase](https://github.com/ak811/Ase) – Multilingual BM25 search engine in Java: SPIMI, positional phrase queries, Porter stemming, Jaccard spell correction

#### Distributed & Streaming Data Processing

- [pyspark-ride-streaming](https://github.com/ak811/pyspark-ride-streaming) – PySpark Structured Streaming ride analytics: watermarked sliding windows, MLlib fare prediction
- [pyspark-listening-behavior-analytics](https://github.com/ak811/pyspark-listening-behavior-analytics) – PySpark user listening behavior analytics: deterministic row_number ranking, genre loyalty
- [hadoop-jaccard-similarity](https://github.com/ak811/hadoop-jaccard-similarity) – Hadoop MapReduce pairwise Jaccard similarity via inverted index, benchmarked on 1 vs 3 DataNodes

#### Cloud ETL & Analytics (AWS)

- [aws-event-driven-etl](https://github.com/ak811/aws-event-driven-etl) – Event-driven S3 → Lambda → Glue → Athena (Trino) ETL with a boto3/Flask dashboard on EC2
- [aws-ecommerce-analytics](https://github.com/ak811/aws-ecommerce-analytics) – AWS S3 → Glue crawler → Athena window-function analytics on ~129k Kaggle e-commerce sales

#### GPU & Parallel Computing

- [cuda-openmp-nbody](https://github.com/ak811/cuda-openmp-nbody) – $O(N^2)$ 2D N-body gravity in sequential C++, OpenMP, and CUDA, scaling to 100k bodies
- [cuda-h2d-d2h-bandwidth](https://github.com/ak811/cuda-h2d-d2h-bandwidth) – CUDA H2D/D2H bandwidth benchmark: pageable malloc vs. pinned cudaHostAlloc, 1 MB–1 GB sweep
- [openmp-three-pass-scan](https://github.com/ak811/openmp-three-pass-scan) – Three-pass block-decomposed exclusive scan in OpenMP; 12.6× speedup on 10⁹ elements, 64 threads
- [openmp-bottom-up-mergesort](https://github.com/ak811/openmp-bottom-up-mergesort) – OpenMP bottom-up merge sort with merge-path partitioning, scaled to 10⁹ elements

### Software Engineering

#### Cryptography & Blockchain

- [Rijn](https://github.com/ak811/Rijn) – FIPS-197 AES + SP 800-38D GCM from scratch in Java; streaming AES-256-GCM file CLI with PBKDF2/HKDF
- [bitcoin-merkle-engine](https://github.com/ak811/bitcoin-merkle-engine) – Parallel Bitcoin Merkle engine: SHA-256d trees, SPV proofs, PoW and SegWit commitment checks

#### Networking & Backend Systems

- [Aport](https://github.com/ak811/Aport) – Concurrent asyncio file transfer over TCP: resumable downloads, SHA-256 checks, atomic uploads
- [Punchcard](https://github.com/ak811/Punchcard) – Java/JDBC loyalty engine on SQLite with merge sort and $O(\log N)$ binary search scoring 5.7M transactions

#### Web, Mobile & Bots

- [EZpark](https://github.com/Park-EZ/ezpark) – Campus Parking Management System for UNC Charlotte: QR spot check-in, React.js, Fastify, MongoDB
- [Discore](https://github.com/ak811/Discore) – Large-scale Discord community bot with ~300 Python modules across 72 independently loadable extensions
- [Jaga](https://github.com/ak811/jaga) – A Java game development framework for Android: 10-pointer multi-touch, object pooling, Canvas HAL

</details>
