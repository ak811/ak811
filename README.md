Hi. My name is Ali Rahimian, and these are some highlights from my CV:

- Honorable Mention – 17th ACM ICPC Asia Tehran Regional Contest (Nov 2019)
- 2nd Place – JCAL Programming Contest (May 2018)
- 3rd Place – Sharif ICT Fintech Hackathon (Aug 2019)
- 4th Place – Sharif Obfuscated C Code Contest (Dec 2019)
- 10th Place – JavaCup Programming Contest (Oct 2019)

Selected Repositories

- [Fibottention](https://github.com/Charlotte-CharMLab/Fibottention) – Wythoff/Fibonacci sparse attention cutting ViT self-attention from $O(N^2)$ to $O(N \log N)$
- [TruthLens](https://github.com/ak811/truthlens) – Training-free deepfake detection via VQA-style probing of vision-language models; ICML 2025
- [Sparxiv](https://github.com/thejasprab/Sparxiv) – Spark recommender over 3M+ arXiv papers: Parquet ETL, MLlib TF-IDF, CSR top-k search
- [CTRL](https://github.com/ak811/ctrl) – Cross-task RL with PPO transfer, Reptile meta-learning, and EWC continual learning

Machine Learning and Efficient Transformer Models

- [two-percent-attention](https://github.com/ak811/two-percent-attention) – Sparse attention for ViTs at 2% of dense attention FLOPs, benchmarked across 10 mechanisms
- [vgg-magnitude-pruning](https://github.com/ak811/vgg-magnitude-pruning) – PyTorch implementation of Han et al. magnitude pruning on VGG
- [linear-quantization-from-scratch](https://github.com/ak811/linear-quantization-from-scratch) – Linear quantization in PyTorch from first principles, down to int8 multiply + int32 accumulate
- [transformer-encoder-from-scratch](https://github.com/ak811/transformer-encoder-from-scratch) – Transformer encoder in PyTorch, built up from scaled dot-product attention to a full stack
- [accelerated-gradient-methods](https://github.com/ak811/accelerated-gradient-methods) – Accelerated gradient methods: Momentum, Nesterov, and when theory misbehaves
- [gradient-descent-convergence](https://github.com/ak811/gradient-descent-convergence) – Gradient descent variants compared across quadratic, nonconvex, and least-squares tasks
- [closed-form-ridge-regression](https://github.com/ak811/closed-form-ridge-regression) – Ridge vs. OLS via normal equations: log-spaced λ sweep with pairwise interaction features
- [logistic-regression-naive-bayes](https://github.com/ak811/logistic-regression-naive-bayes) – Multiclass logistic regression (GD/IRLS) and Gaussian/Bernoulli Naive Bayes from scratch
- [nonlinear-decision-boundaries](https://github.com/ak811/nonlinear-decision-boundaries) – Nonlinear decision boundaries with a two-layer neural network
- [cross-in-tray-optimization](https://github.com/ak811/cross-in-tray-optimization) – Genetic algorithm and simulated annealing for the Cross-in-Tray global optimization benchmark

Computer Vision & Deep Learning

- [moco-joint-ssl-training](https://github.com/ak811/moco-joint-ssl-training) – MoCo contrastive learning trained jointly with a supervised head from scratch
- [oneshot-openclip-tta](https://github.com/ak811/oneshot-openclip-tta) – One-shot OpenCLIP classification with confidence-gated test-time prototype adaptation
- [vit-imagenet21k-finetune](https://github.com/ak811/vit-imagenet21k-finetune) – ImageNet-21k ViT-B/16 fine-tuned for 16-class image classification: 96.75% test accuracy
- [watershed-image-segmentation](https://github.com/ak811/watershed-image-segmentation) – Segmentation with Watershed algorithm: median blur, contour detection, and custom seeds
- [hand-segmentation-convex-hull](https://github.com/ak811/hand-segmentation-convex-hull) – Hand segmentation & finger counting with Gaussian blur, contour detection, and convex hull
- [opencv-tracking-algorithms](https://github.com/ak811/opencv-tracking-algorithms) – Lucas-Kanade & Farneback optical flow, MeanShift/CAMShift, and OpenCV KCF/MIL trackers
- [opencv-keypoint-detection](https://github.com/ak811/realtime-facial-keypoint-detection) – Real-time Haar-cascade face/eye detection with median-adaptive Canny edge extraction

Deep Reinforcement Learning & Game Theory

- [sb3-ppo-clip-carracing-v3](https://github.com/ak811/sb3-ppo-clip-carracing-v3) – SB3 PPO-Clip + GAE(λ) on CarRacing-v3 with CNN over 4 stacked 84x84 frames
- [dqn-ddqn-pong-v5](https://github.com/ak811/dqn-ddqn-pong-v5) – DQN + Double DQN on ALE/Pong-v5 with replay, Huber loss, and difficulty 2–3 training
- [tabular-qlearning-frozenlake-v1](https://github.com/ak811/tabular-qlearning-frozenlake-v1) – Tabular Q-learning on FrozenLake-v1: Bellman TD updates with ε-greedy 1.0→0.01 decay
- [ppo-clip-lunarlander-v3](https://github.com/ak811/ppo-clip-lunarlander-v3) – From-scratch PPO-Clip on LunarLander-v3: categorical actor-critic, normalized GAE(λ), clip-ε decay
- [dqn-replay-noise-ablation](https://github.com/ak811/dqn-replay-noise-ablation) – DQN ablation of prioritized vs uniform vs online replay, parameter noise vs ε-greedy
- [pacman-search-agent](https://github.com/ak811/pacman-search-agent) – BFS/DFS/UCS/A* search agent with admissible Manhattan/Euclidean heuristics and a Pygame visualizer

Distributed & Cloud Computing

- [aws-event-driven-etl](https://github.com/ak811/aws-event-driven-etl) – Event-driven S3 → Lambda → Glue → Athena (Trino) ETL with a boto3/Flask dashboard on EC2
- [aws-ecommerce-analytics](https://github.com/ak811/aws-ecommerce-analytics) – AWS S3 → Glue crawler → Athena window-function analytics on ~129k Kaggle e-commerce sales
- [pyspark-ride-streaming](https://github.com/ak811/pyspark-ride-streaming) – PySpark Structured Streaming ride analytics: watermarked sliding windows, MLlib fare prediction
- [pyspark-listening-behavior-analytics](https://github.com/ak811/pyspark-listening-behavior-analytics) – PySpark user listening behavior analytics: row_number ranking, genre loyalty, night-owl detection
- [hadoop-jaccard-similarity](https://github.com/ak811/hadoop-jaccard-similarity) – Three-stage Hadoop MapReduce pairwise Jaccard similarity via inverted index, benchmarked on 1 vs 3 DataNodes

Parallel Computing

- [cuda-openmp-nbody](https://github.com/ak811/cuda-openmp-nbody) – O(N²) 2D N-body gravity in sequential C++, OpenMP, and CUDA, scaling to 100k bodies
- [cuda-h2d-d2h-bandwidth](https://github.com/ak811/cuda-h2d-d2h-bandwidth) – CUDA H2D/D2H bandwidth benchmark: pageable malloc vs. pinned cudaHostAlloc, 1 MB–1 GB sweep
- [openmp-bottom-up-mergesort](https://github.com/ak811/openmp-bottom-up-mergesort) – OpenMP bottom-up merge sort with merge-path partitioning, scaled to 10⁹ elements on 64 threads
- [openmp-three-pass-scan](https://github.com/ak811/openmp-three-pass-scan) – Three-pass block-decomposed exclusive scan in OpenMP; 12.6× speedup on 10⁹ elements, 64 threads
- [bitcoin-merkle-engine](https://github.com/ak811/bitcoin-merkle-engine) – Parallel Bitcoin Merkle engine: SHA-256d trees, SPV proofs, PoW and SegWit commitment checks

Algorithms & Competitive Programming

- [competitive-programming](https://github.com/ak811/competitive-programming) – ACM-ICPC problems & algorithm design
- Profiles
  - Codeforces: [https://codeforces.com/profile/Ali811](https://codeforces.com/profile/Ali811)
  - Timus Online Judge: [https://acm.timus.ru/author.aspx?id=238630](https://acm.timus.ru/author.aspx?id=238630)

Software Development

- [Jaga](https://github.com/ak811/jaga) – A Java game development framework for Android
- [EZpark](https://github.com/Park-EZ/ezpark) – Campus parking spot availability app
- [java-jdbc-loyalty-engine](https://github.com/ak811/java-jdbc-loyalty-engine) – Java/JDBC loyalty engine on SQLite with merge sort and $O(logN)$ binary search scoring 5.7M transactions
- [tcp-socket-messenger](https://github.com/ak811/tcp-socket-messenger) – TCP-based messenger
- [aes-encryption](https://github.com/ak811/aes-encryption) – AES encryption/decryption
- [tfidf-ngram-search-engine](https://github.com/ak811/tfidf-ngram-search-engine) – Local search engine with TF-IDF and n-grams
- [infinity-bot](https://github.com/ak811/infinity-bot) – Large-scale Discord community bot with ~300 Python modules across 72 independently loadable extensions
