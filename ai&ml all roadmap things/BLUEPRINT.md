# AI/ML Engineer Learning Blueprint — Beginner to Advanced

Oct 30, 2026 · @Sai Venkat Battula

## How to use this blueprint

This blueprint takes a complete beginner to an industry-ready AI/ML engineer in about **2,750 focused hours** for the full program, or about **2,170 hours** for the core (essential-only) path. At 4 hours a day alongside college, that is roughly 2.5 years for the full program. Section 11 has the plans for 2, 3, 4 and 6 hours a day.

It is built for someone starting from zero and studying alongside college. Every subject has three parts: what to learn (section 2), how long it takes (section 4) and where to learn it (section 5). They share the same numbering, so subject **S20** is Supervised Learning everywhere.

### The four levels

| Level | Meaning | Where it sits |
| --- | --- | --- |
| Foundational | Needed before anything else works | Phases 0–3: computing, Python, math, DSA, data, backend |
| Core | What every AI/ML engineer uses weekly | Phases 4–7: ML, deep learning, LLMs, production engineering |
| Advanced | What separates strong engineers from average ones | Phase 8: distributed training, GPUs, RL, research |
| Specialized | Pick one or two to go deep in, based on the jobs you want | Computer vision, NLP, agents, inference optimization, MLOps platforms |

### Priority markers

- **\[E\] Essential:** Required. Skipping it causes problems later.
- **\[R\] Recommended:** Most job descriptions expect it. Learn it to at least the Implement level.
- **\[O\] Optional:** Learn it when a project or job needs it. Being aware of it is enough until then.

### Proficiency levels (used in every time estimate)

| Level | You can… | Typical evidence |
| --- | --- | --- |
| L1 Understand | Explain the concept and its purpose in your own words | You can teach it to a friend, or answer the quiz in section 10 |
| L2 Implement | Build it while referring to docs and examples | A working notebook or repo that you wrote yourself |
| L3 Independent | Apply it to a new problem without a tutorial, debug it, and pick between alternatives | A project with a design you chose and failures you fixed |

Finishing the curriculum gets you to L2–L3 in core subjects. **Professional proficiency (reliable L3 under real constraints) comes from 1–2 years of real work.** That means internships, open-source contributions and production projects. Nothing in this plan replaces that, and section 12 tells you how to get it.

### Five rules for using this plan

1. **Follow the dependency map (section 3).** Don't skip ahead to LLMs before Python, math and classical ML are solid. Engineers who skip fundamentals get stuck at debugging.
2. **Spend about 30% of your time on theory and 70% on practice.** Every hour of video or reading should be followed by about two hours of writing code yourself.
3. **Pass each phase gate (section 10) before moving on.** If a gate fails, spend one consolidation week on the weak area.
4. **Put everything on GitHub from week 1.** Your repos become your portfolio and your proof of skill.
5. **Use college courses as credit.** If your degree already covers a subject (math, DSA, operating systems, networks, databases), take that subject's mastery check in section 10. If you pass, skip to its projects.

### Learning tools from day 1

Use an AI assistant (Claude, ChatGPT, Gemini) as a tutor, never as a ghostwriter. Ask it to explain errors, quiz you and review your code. **Do not paste solutions into exercises:** the struggle is the learning. A good rule is to try for 20 minutes before asking for a hint, and to ask for hints rather than answers.

## 1. Complete AI/ML engineering curriculum

The program has 10 phases, 55 subjects (S1–S55) and 2,755 hours in total. About 31% of the time is theory, 42% is hands-on practice and 27% is projects. Math (Phase 2) and DSA (S12) run as a **parallel track**: one hour a day alongside Phases 1–4, not as a block you must finish first.

| Phase | Name | Subjects | Full hours | Core hours | Goal | Exit gate (section 10) |
| --- | --- | --- | --- | --- | --- | --- |
| 0 | Computing foundations | S1–S4 | 82 | 82 | Use a computer like an engineer: shell, Git, editor | Ship a Git repo with a shell script, a README and 10+ meaningful commits |
| 1 | Programming & software engineering | S5–S8 | 265 | 265 | Write clean, tested, packaged Python | A CLI app with tests, type hints and a pip-installable package |
| 2 | Mathematics for AI (parallel) | S9–S11 | 215 | 215 | Read ML math and implement it in NumPy | Implement PCA and linear regression from scratch using only NumPy |
| 3 | DSA, data & systems | S12–S18 | 370 | 285 | Handle data and build services | 75 solved DSA problems, plus a FastAPI + PostgreSQL service with tests |
| 4 | Classical machine learning | S19–S25 | 285 | 270 | Train, evaluate and explain ML models | An end-to-end ML project that beats a baseline and has an honest evaluation |
| 5 | Deep learning | S26–S32 | 343 | 275 | Build and train neural networks in PyTorch | A GPT trained from scratch, plus a fine-tuned vision model |
| 6 | Generative AI & LLMs | S33–S39 | 285 | 255 | Build LLM apps that you can measure | A RAG system and an agent, both with an evaluation suite |
| 7 | Production AI engineering | S40–S49 | 460 | 365 | Deploy, scale, monitor and secure AI systems | A containerized model on Kubernetes or the cloud, with CI/CD and monitoring |
| 8 | Advanced & research | S50–S53 | 290 | 0 | Go deep: RL, GPUs, distributed training, papers | Reproduce one paper's key result and write it up |
| 9 | Capstone & job readiness | S54–S55 | 160 | 160 | Prove it with production-grade work | Two capstones, a portfolio and mock interviews |
|  | **Total** | **55** | **2,755** | **2,172** |  |  |

**Core path** = all \[E\] subjects (2,172 h). It makes you hireable for entry-level ML engineer and AI engineer roles. **Full path** = everything (2,755 h). It adds the advanced and research depth that senior, research-engineer and infrastructure roles expect.

### What each phase builds on

- **Phase 0 → 1:** You can't learn to program well if fighting the terminal and Git eats your time.
- **Phase 1 + 2 → 4:** ML is code (Python) applied to math (linear algebra, calculus, probability). Missing either makes ML feel like magic, and magic can't be debugged.
- **Phase 3 → 4–7:** Real ML work is about 60–80% data work. Every deployed model sits behind an API and a database.
- **Phase 4 → 5:** Deep learning reuses every classical idea: loss, gradient descent, overfitting, validation.
- **Phase 5 → 6:** LLMs are Transformers. Without S30, fine-tuning and RAG debugging are guesswork.
- **Phase 6 → 7:** A model that only runs in a notebook has no users. Phase 7 makes it a product.
- **Phase 7 → 8 → 9:** Advanced topics make sense once you have felt the production problems they solve: cost, latency and scale.

### Specializations (choose 1–2 after Phase 6)

| Track | Go deeper in | Typical roles |
| --- | --- | --- |
| LLM / AI application engineering | S34–S39, S44, S46 (LLMOps) | AI engineer, LLM engineer |
| ML platform / MLOps | S40–S47, S51 | MLOps engineer, ML platform engineer |
| Computer vision | S28, S32, S45 | CV engineer, perception engineer |
| NLP & language models | S30, S31, S33, S35 | NLP engineer, applied scientist |
| Inference & performance | S44, S45, S51 | ML systems / inference engineer |
| Research engineering | S50–S53 | Research engineer, AI scientist (usually needs a master's or PhD, or strong publications) |

## 2. Hierarchical topic and subtopic tree

Every subject below has the same layout: what it is, why it matters, prerequisites, then topics in learning order (each marked \[E\], \[R\] or \[O\], with subtopics), and finally how it is used in industry. Hours for each subject are in section 4, and links are in section 5.

### Phase 0 — Computing foundations (Foundational)

#### S1 Computing fundamentals \[E\]

**What:** How a computer actually runs your code: hardware, the operating system, memory and the way programs execute. **Why:** It explains things you will hit constantly in AI work: why a model runs "out of memory", why GPUs are fast, why a float isn't exact. **Prerequisites:** none.

1. &#91;E\] **Data representation:** binary, hexadecimal, bits and bytes; integers (two's complement); floating point (IEEE 754, float32/float16/bfloat16, precision loss); text encoding (ASCII, Unicode, UTF-8).
2. &#91;E\] **Hardware:** CPU (cores, clock, cache hierarchy L1/L2/L3), RAM vs disk vs SSD, latency numbers; what a GPU is and why it suits parallel math.
3. &#91;E\] **How programs run:** source code → compiler/interpreter → machine code; processes vs threads; stack vs heap memory; what Python's interpreter does.
4. &#91;R\] **Operating system concepts:** processes, scheduling, virtual memory, file systems, system calls, permissions. Studied in depth in S2 and section 7 (Docker internals).
5. &#91;O\] **Computer architecture deeper:** instruction pipelines, SIMD/vector instructions. These matter later for performance work (S51).

**In industry:** You choose float16 vs bfloat16 for training, estimate whether a 7B-parameter model fits in 16 GB of GPU memory (7B × 2 bytes = 14 GB for weights alone), and read profiler output that talks about cache misses.

#### S2 Linux and the shell \[E\]

**What:** The Linux operating system and its command-line shell (bash/zsh). **Why:** Nearly every server, cloud VM, Docker container and GPU cluster runs Linux. You will spend hours a week in a terminal. **Prerequisites:** S1 basics. On Windows, install WSL2 (Windows Subsystem for Linux).

1. &#91;E\] **Navigation and files:** pwd, ls, cd, mkdir, cp, mv, rm, find; absolute vs relative paths; the file system layout (/home, /etc, /var, /tmp, /usr).
2. &#91;E\] **Viewing and editing:** cat, less, head, tail -f, nano/vim basics; grep, wc, sort, uniq, cut; pipes (|) and redirection (>, >>, 2>&1).
3. &#91;E\] **Permissions and users:** chmod, chown, sudo, file permission bits, groups.
4. &#91;E\] **Processes:** ps, top/htop, kill, signals, background jobs (&, nohup), exit codes.
5. &#91;E\] **Packages and environment:** apt, environment variables, PATH, .bashrc, which.
6. &#91;E\] **Networking from the shell:** curl, wget, ssh, scp, ssh keys, ping, ports (ss/netstat).
7. &#91;E\] **Shell scripting:** variables, conditionals, loops, functions, arguments, set -euo pipefail, cron jobs.
8. &#91;R\] **Text processing:** sed, awk, jq (for JSON), xargs.
9. &#91;R\] **Remote and long-running work:** tmux/screen, rsync, disk usage (df, du), and nvidia-smi for GPU monitoring.
10. &#91;O\] **systemd services, logs (journalctl), cgroups and namespaces.** These are covered again in Docker internals (section 7).

**In industry:** You SSH into a GPU box, start training inside tmux, tail logs, watch nvidia-smi, and write a bash script to sync checkpoints to cloud storage.

#### S3 Git and GitHub \[E\]

**What:** Git is version control: it records every change to your code. GitHub hosts Git repos and adds collaboration features: pull requests, issues and Actions. **Why:** All professional code lives in Git, and your GitHub profile is your portfolio. **Prerequisites:** S2 basics.

1. &#91;E\] **Core model:** repository, working tree, staging area, commits, HEAD; init, add, commit, status, log, diff.
2. &#91;E\] **Branching:** branch, switch/checkout, merge, resolving merge conflicts.
3. &#91;E\] **Remotes:** clone, push, pull, fetch; origin and upstream; SSH auth to GitHub.
4. &#91;E\] **Collaboration:** forks, pull requests, code review, issues, writing good commit messages.
5. &#91;E\] **.gitignore**, and keeping secrets and large files out of Git.
6. &#91;R\] **History editing:** rebase, interactive rebase, cherry-pick, reset vs revert, stash, reflog (how to recover "lost" work).
7. &#91;R\] **Workflows:** trunk-based development vs GitFlow, tags and releases, semantic versioning.
8. &#91;R\] **Large files:** Git LFS, and why datasets and models need other tools (DVC, Hugging Face Hub; see S46).
9. &#91;O\] **Git internals:** objects (blob, tree, commit), and how a commit is a snapshot.

**In industry:** Every change goes through a pull request that CI tests (S42) and a teammate reviews. Model code, training configs and infrastructure all live in Git.

#### S4 Development environment \[E\]

**What:** The tools you write and run code with. **Why:** A good setup removes friction, and knowing how to make environments reproducible prevents "works on my machine" bugs. **Prerequisites:** S2.

1. &#91;E\] **VS Code:** extensions (Python, Jupyter, Pylance, Ruff), the debugger, integrated terminal, Remote-SSH and WSL.
2. &#91;E\] **Python environments:** what a virtual environment is, venv, pip, requirements.txt; **uv** (a fast modern installer and project manager); why you never install into the system Python.
3. &#91;E\] **Jupyter notebooks:** cells, kernels, magic commands; when to use notebooks (exploration) vs scripts (anything repeated).
4. &#91;E\] **Free GPU environments:** Google Colab and Kaggle Notebooks.
5. &#91;R\] **Conda/Mamba:** needed when you depend on non-Python libraries, such as CUDA toolkits.
6. &#91;R\] **Linters and formatters:** Ruff, Black, pre-commit hooks.
7. &#91;O\] **Dev containers:** a whole dev environment defined in Docker (see section 7).

**In industry:** Teams standardize on a pyproject.toml with a lock file, pre-commit hooks and a dev container, so a new hire runs one command and has the same setup as everyone else.

### Phase 1 — Programming and software engineering (Foundational)

#### S5 Python — beginner \[E\]

**What:** Core Python syntax and problem solving. **Why:** Python is the main language of AI/ML: PyTorch, Hugging Face, scikit-learn, LangChain and FastAPI are all Python. **Prerequisites:** S4.

1. &#91;E\] **Basics:** variables, types (int, float, str, bool, None), operators, input/output, f-strings, comments.
2. &#91;E\] **Control flow:** if/elif/else, for and while loops, break/continue, range, enumerate, zip.
3. &#91;E\] **Data structures:** lists, tuples, dictionaries, sets; indexing, slicing, mutability, copying (shallow vs deep).
4. &#91;E\] **Functions:** parameters, return values, default and keyword arguments, \*args/\*\*kwargs, scope (LEGB), docstrings.
5. &#91;E\] **Strings:** methods, formatting, splitting and joining, basic regular expressions.
6. &#91;E\] **Files:** reading and writing text, CSV and JSON; with-statements; paths using pathlib.
7. &#91;E\] **Errors:** reading tracebacks, try/except/finally, raising exceptions.
8. &#91;E\] **Modules:** import, the standard library (math, random, datetime, collections, itertools, os, sys), installing packages with pip/uv.
9. &#91;E\] **Comprehensions:** list, dict and set comprehensions; lambda, map, filter, sorted with key.

**In industry:** Data-loading scripts, config parsing and glue code. This is about 50% of daily ML engineering code.

#### S6 Python — intermediate and object-oriented programming \[E\]

**What:** Structuring larger programs with classes and modules. **Why:** PyTorch models are classes (nn.Module), and every framework expects you to read and extend class hierarchies. **Prerequisites:** S5.

1. &#91;E\] **Classes and objects:** **init**, attributes, methods, self, class vs instance attributes.
2. &#91;E\] **The four OOP pillars:** encapsulation, inheritance, polymorphism, abstraction; super(), method overriding, abstract base classes (abc).
3. &#91;E\] **Dunder (magic) methods:** **repr**, **str**, **len**, **getitem**, **iter**, **call**, **eq**, operator overloading. This is how torch tensors and Datasets work.
4. &#91;E\] **Composition vs inheritance:** when to use each.
5. &#91;E\] **dataclasses** and **type hints** (typing module, Optional, Union, list\[int\], generics basics); running mypy or pyright.
6. &#91;E\] **Iterators and generators:** the iterator protocol, yield, generator expressions, lazy evaluation for large datasets.
7. &#91;E\] **Project structure:** packages, **init**.py, relative imports, `if __name__ == "__main__"`, CLI arguments (argparse, Typer).
8. &#91;E\] **Logging:** the logging module, log levels; why print is not logging.
9. &#91;R\] **Functional tools:** functools (partial, lru\_cache, reduce), itertools recipes.

**In industry:** You subclass torch.utils.data.Dataset, write a config dataclass for experiments, and build a CLI that runs training.

#### S7 Python — advanced \[E\]

**What:** The features that production and framework code relies on. **Why:** Reading library source code, writing fast data pipelines and building async APIs (FastAPI, LLM calls) all need this. **Prerequisites:** S6.

1. &#91;E\] **Decorators:** functions as objects, closures, writing decorators with arguments, functools.wraps. Used for retries, timing and caching.
2. &#91;E\] **Context managers:** **enter**/**exit**, contextlib.contextmanager. Used for GPU memory scopes and file and DB sessions.
3. &#91;E\] **Concurrency:** the GIL; threading vs multiprocessing vs asyncio; concurrent.futures; when each helps (I/O-bound vs CPU-bound work).
4. &#91;E\] **asyncio:** async/await, event loop, gather, semaphores for rate limits. Needed for calling LLM APIs in parallel.
5. &#91;E\] **Packaging:** pyproject.toml, building wheels, versioning, publishing to (Test)PyPI, lock files.
6. &#91;E\] **Performance:** profiling (cProfile, line\_profiler, py-spy), memory profiling, vectorizing with NumPy instead of loops.
7. &#91;R\] **Advanced typing:** Protocol, TypedDict, Generics, Pydantic models for validation.
8. &#91;R\] **Python data model deeper:** descriptors, **slots**, metaclasses (read about them, rarely write them).
9. &#91;O\] **Extending Python:** Cython, Numba, Rust via PyO3; free-threaded Python 3.13+ (experimental).

**In industry:** An async FastAPI service that fans out 50 LLM calls with a semaphore. A retry decorator with exponential backoff. A multiprocessing data-preprocessing job.

#### S8 Software engineering principles and testing \[E\]

**What:** Writing code that other people (and future you) can understand, change and trust. **Why:** It is the gap between "knows ML libraries" and "is an engineer". ML code with no tests breaks silently. **Prerequisites:** S6, S3.

1. &#91;E\] **Clean code:** naming, small functions, single responsibility, DRY vs over-abstraction, comments that explain *why*.
2. &#91;E\] **SOLID principles,** and coupling vs cohesion.
3. &#91;E\] **Testing:** pytest, fixtures, parametrize, mocking, unit vs integration vs end-to-end tests, test coverage; testing ML code (shape tests, determinism, small-data overfit tests).
4. &#91;E\] **Debugging:** the VS Code debugger, pdb, rubber-duck debugging, bisecting.
5. &#91;E\] **Code review:** giving and receiving it; small pull requests.
6. &#91;R\] **Design patterns:** factory, strategy, observer, adapter, singleton (and why to avoid it), dependency injection.
7. &#91;R\] **Documentation:** READMEs, docstrings, architecture decision records (ADRs), MkDocs.
8. &#91;R\] **Error handling and configuration:** failing fast, config files (YAML, Hydra), the 12-factor app.
9. &#91;O\] **Formal methods:** UML diagrams, domain-driven design basics.

**In industry:** Every pull request needs tests to pass in CI. ML teams test data schemas, feature functions and model inference contracts.

### Phase 2 — Mathematics for AI/ML (Foundational, parallel track)

Study the math one hour a day, alongside Phases 1–4. Implement every concept in NumPy as soon as you meet it: a formula you have coded is a formula you understand. If high-school algebra is shaky, spend 15–20 extra hours on Khan Academy algebra and functions first.

#### S9 Linear algebra \[E\]

**What:** The math of vectors and matrices. **Why:** All data in ML is stored as vectors and matrices (tensors). A neural network layer is a matrix multiply, an embedding is a vector, and attention is matrix products. **Prerequisites:** high-school algebra.

1. &#91;E\] **Vectors:** geometric meaning, addition, scalar multiplication, dot product, norms (L1, L2), cosine similarity, projections. Cosine similarity is the core of vector search (S36).
2. &#91;E\] **Matrices:** as linear transformations; matrix–vector and matrix–matrix multiply; shapes and broadcasting; transpose; identity and inverse.
3. &#91;E\] **Systems of linear equations:** Gaussian elimination, rank, linear independence, span, basis, column space and null space.
4. &#91;E\] **Determinants:** as change in volume, and why a determinant of 0 means "not invertible".
5. &#91;E\] **Eigenvalues and eigenvectors:** meaning, computing them, diagonalization; the bridge to PCA.
6. &#91;E\] **Singular value decomposition (SVD):** the most useful decomposition in ML. Used in PCA, low-rank approximation and LoRA intuition (S35).
7. &#91;E\] **Orthogonality:** orthogonal and orthonormal matrices, Gram–Schmidt, QR (concept).
8. &#91;R\] **Positive definite matrices,** quadratic forms, covariance matrices.
9. &#91;R\] **Tensors:** higher-dimensional arrays, einsum notation, the tensor shapes used in deep learning (batch, sequence, heads, dimensions).
10. &#91;O\] **Numerical linear algebra:** conditioning, stability, why we never compute inverses explicitly.

**In industry:** Debugging shape errors, understanding why LoRA's low-rank matrices save memory, choosing cosine vs dot-product similarity, using PCA to compress embeddings.

#### S10 Calculus and optimization \[E\]

**What:** The math of change and of finding the minimum of a function. **Why:** Training = minimizing a loss with gradients. Backpropagation is the chain rule, applied automatically. **Prerequisites:** S9 (topics 1–2), functions and graphs.

1. &#91;E\] **Limits and derivatives:** intuition, rules (power, product, quotient), derivatives of exp, log and sigmoid.
2. &#91;E\] **The chain rule:** the single most important rule for deep learning.
3. &#91;E\] **Partial derivatives and gradients:** functions of many variables; the gradient as the direction of steepest ascent.
4. &#91;E\] **Vector and matrix calculus:** Jacobians, the gradient of a dot product and a matrix multiply, the Hessian (concept).
5. &#91;E\] **Computational graphs and automatic differentiation:** forward vs reverse mode. This is the bridge to S26 (micrograd).
6. &#91;E\] **Optimization:** gradient descent, learning rate, local vs global minima, saddle points, convex vs non-convex functions.
7. &#91;E\] **Gradient descent variants:** stochastic (SGD), mini-batch, momentum, RMSProp, Adam (the math is detailed in S26).
8. &#91;R\] **Integrals:** area under a curve; needed for continuous probability (expectations, densities) and AUC.
9. &#91;R\] **Taylor series:** local approximation; why second-order methods exist.
10. &#91;O\] **Constrained optimization:** Lagrange multipliers (used in the SVM derivation), KKT conditions.

**In industry:** Diagnosing exploding or vanishing gradients, picking learning-rate schedules, reading the loss curves in every training run.

#### S11 Probability and statistics \[E\]

**What:** The math of uncertainty, and of drawing conclusions from data. **Why:** ML models output probabilities. Loss functions come from likelihood, and model evaluation and A/B tests are statistics. LLM sampling is probability. **Prerequisites:** S10 topics 1–3 for continuous parts.

1. &#91;E\] **Descriptive statistics:** mean, median, mode, variance, standard deviation, percentiles, skew, outliers.
2. &#91;E\] **Probability basics:** sample spaces, events, rules of probability, conditional probability, independence.
3. &#91;E\] **Bayes' theorem:** priors, likelihoods, posteriors; the Naive Bayes classifier.
4. &#91;E\] **Random variables and distributions:** discrete (Bernoulli, binomial, categorical, Poisson) and continuous (uniform, normal/Gaussian, exponential); PMF, PDF, CDF.
5. &#91;E\] **Expectation, variance and covariance;** correlation vs causation; the multivariate Gaussian.
6. &#91;E\] **Law of large numbers and the central limit theorem.**
7. &#91;E\] **Estimation:** maximum likelihood estimation (MLE), MAP; why cross-entropy loss = negative log-likelihood.
8. &#91;E\] **Inferential statistics:** sampling, confidence intervals, hypothesis testing, p-values, t-tests, chi-square, multiple-comparisons problems.
9. &#91;E\] **Experiment design:** A/B testing, statistical power, sample size.
10. &#91;R\] **Information theory:** entropy, cross-entropy, KL divergence, perplexity (an LLM metric), mutual information.
11. &#91;R\] **Bootstrapping and resampling;** Bayesian inference basics.
12. &#91;O\] **Stochastic processes:** Markov chains (the basis for RL in S50 and diffusion models in S32), Monte Carlo methods.

**In industry:** Building confidence intervals on model accuracy, running an A/B test on a new recommender, choosing sampling temperature, judging whether a 1% eval improvement is real or noise.

### Phase 3 — DSA, data and systems (Foundational)

#### S12 Data structures and algorithms \[E\] (parallel track)

**What:** Standard ways to organize data and solve problems efficiently. **Why:** It is tested in almost every ML/AI engineering interview. It also teaches complexity thinking: why a vector index is faster than scanning a million embeddings, and why attention is O(n²). **Prerequisites:** S5–S6.

1. &#91;E\] **Complexity:** Big-O time and space, best/average/worst case, amortized analysis.
2. &#91;E\] **Arrays and strings:** two pointers, sliding window, prefix sums.
3. &#91;E\] **Hash maps and sets:** hashing, collisions; frequency counting.
4. &#91;E\] **Linked lists, stacks, queues, deques.**
5. &#91;E\] **Recursion and backtracking.**
6. &#91;E\] **Sorting and searching:** merge sort, quicksort, binary search (and binary search on the answer).
7. &#91;E\] **Trees:** binary trees, traversals, binary search trees, tries (used in tokenizers).
8. &#91;E\] **Heaps and priority queues:** top-k problems (used for top-k retrieval and beam search).
9. &#91;E\] **Graphs:** representations, BFS, DFS, topological sort (used in DAG pipelines and autograd), shortest paths (Dijkstra), union-find.
10. &#91;E\] **Dynamic programming:** memoization, tabulation, classic problems (knapsack, longest common subsequence, edit distance).
11. &#91;R\] **Greedy algorithms, intervals, bit manipulation.**
12. &#91;O\] **Advanced:** segment trees, approximate nearest neighbour structures (HNSW graphs, k-d trees). These link to S36.

**In industry:** Interviews; writing an efficient deduplication pass over 10M documents; understanding HNSW indexes; topological ordering of pipeline steps.

#### S13 Data analysis: NumPy, pandas, visualization, EDA \[E\]

**What:** Loading, cleaning, transforming, exploring and visualizing data in Python. **Why:** Most ML project time goes into understanding and preparing data. A bad dataset beats a good model every time. **Prerequisites:** S5–S6, S11 topic 1.

1. &#91;E\] **NumPy:** ndarrays, dtypes, indexing, slicing, boolean masks, broadcasting, vectorization, axis operations, random number generation, linear algebra routines.
2. &#91;E\] **pandas:** Series and DataFrame; reading CSV, Parquet, JSON and SQL; selection (loc/iloc); filtering; groupby/aggregate; merge/join; pivot and melt; apply vs vectorized ops; datetime handling; categorical data.
3. &#91;E\] **Data cleaning:** missing values, duplicates, type fixes, outliers, string cleanup, unit consistency.
4. &#91;E\] **Visualization:** Matplotlib (figure/axes model), Seaborn (statistical plots); histograms, box plots, scatter plots, heatmaps, pair plots; choosing the right chart.
5. &#91;E\] **Exploratory data analysis (EDA) workflow:** questions → summary stats → distributions → relationships → data-quality issues → write up the findings.
6. &#91;R\] **Interactive viz:** Plotly; dashboards with Streamlit or Gradio.
7. &#91;R\] **Scaling up:** Polars (fast DataFrames), DuckDB (SQL on files), chunked processing.
8. &#91;O\] **Spark (PySpark)** for data that doesn't fit on one machine.

**In industry:** Every project starts with EDA. Data analysts and ML engineers share notebooks of findings before anyone trains a model.

#### S14 SQL and relational databases \[E\]

**What:** Storing and querying structured data with SQL (PostgreSQL). **Why:** Company data lives in SQL databases and warehouses (Snowflake, BigQuery). Feature extraction and analytics are SQL. **Prerequisites:** S5.

1. &#91;E\] **Relational model:** tables, rows, columns, primary keys, foreign keys, data types.
2. &#91;E\] **Querying:** SELECT, WHERE, ORDER BY, LIMIT, DISTINCT, aggregate functions, GROUP BY, HAVING.
3. &#91;E\] **Joins:** inner, left, right, full, self-joins; the problem of duplicate rows from joins.
4. &#91;E\] **Subqueries and common table expressions (CTEs).**
5. &#91;E\] **Window functions:** ROW\_NUMBER, RANK, LAG/LEAD, running totals. Heavily used for time-series features.
6. &#91;E\] **Writing data:** INSERT, UPDATE, DELETE; transactions; ACID.
7. &#91;E\] **Schema design:** normalization (1NF–3NF), when to denormalize, star schema for analytics.
8. &#91;E\] **Indexes and performance:** B-tree indexes, EXPLAIN ANALYZE, query plans.
9. &#91;E\] **Using SQL from Python:** psycopg, SQLAlchemy, pandas.read\_sql.
10. &#91;R\] **Data warehouses:** columnar storage; BigQuery and Snowflake concepts.
11. &#91;R\] **pgvector:** vector search inside PostgreSQL (links to S36).

**In industry:** Pulling training data with SQL, building features with window functions, storing app data and conversation history for LLM apps.

#### S15 NoSQL databases \[R\]

**What:** Databases that don't use the relational table model: document, key-value, wide-column and graph stores. **Why:** Caching LLM responses (Redis), storing flexible documents (MongoDB) and session state are common in AI apps. **Prerequisites:** S14.

1. &#91;E\] **Why NoSQL:** the CAP theorem, schema flexibility, horizontal scaling, consistency trade-offs.
2. &#91;E\] **Document stores (MongoDB):** documents, collections, CRUD, queries, indexes, aggregation pipelines.
3. &#91;E\] **Key-value stores (Redis):** strings, hashes, lists, sets, TTLs (expiry); caching patterns (cache-aside); rate limiting; pub/sub; queues.
4. &#91;R\] **Choosing a database:** SQL vs document vs key-value vs vector vs graph.
5. &#91;O\] **Wide-column (Cassandra) and graph databases (Neo4j)**; GraphRAG links to S36.

**In industry:** A Redis cache in front of an LLM endpoint cuts cost; MongoDB stores chat sessions; Redis queues background jobs.

#### S16 Data engineering basics \[R\]

**What:** Building reliable pipelines that move and transform data. **Why:** Models depend on fresh, correct data. ML engineers build or maintain these pipelines constantly. **Prerequisites:** S13, S14.

1. &#91;E\] **ETL vs ELT,** batch vs streaming.
2. &#91;E\] **File formats:** CSV, JSON/JSONL, Parquet (columnar), Arrow; compression; partitioning.
3. &#91;E\] **Data quality:** schema validation (Pydantic, Pandera, Great Expectations), data contracts.
4. &#91;E\] **Storage:** data lakes (S3/GCS), warehouses, lakehouses (Delta Lake, Iceberg concepts).
5. &#91;R\] **Orchestration:** DAGs, scheduling and retries with Airflow, Prefect or Dagster.
6. &#91;R\] **Transformation in SQL:** dbt concepts.
7. &#91;R\] **Streaming:** Kafka concepts (topics, partitions, consumers) for real-time features.
8. &#91;O\] **Distributed processing:** Spark and Ray Data.
9. &#91;E\] **Data for LLMs:** web scraping ethics and robots.txt, document parsing (PDF, HTML), deduplication, PII removal.

**In industry:** A nightly Airflow DAG ingests data, validates it, writes Parquet files and triggers retraining. A document-ingestion pipeline feeds a RAG index.

#### S17 Computer networks \[R\]

**What:** How computers talk to each other. **Why:** APIs, model serving, distributed training and Kubernetes are all networking. You need it to debug timeouts, DNS errors and "connection refused". **Prerequisites:** S1, S2.

1. &#91;E\] **Models:** the OSI and TCP/IP layers, and what each layer does.
2. &#91;E\] **Addressing:** IP addresses (v4/v6), subnets and CIDR, ports, NAT, private vs public IPs.
3. &#91;E\] **Transport:** TCP vs UDP, the three-way handshake, connections and sockets.
4. &#91;E\] **DNS:** resolution, record types, caching.
5. &#91;E\] **HTTP/HTTPS:** methods, status codes, headers, cookies; HTTP/1.1 vs HTTP/2 vs HTTP/3; TLS certificates.
6. &#91;E\] **Load balancers, reverse proxies (Nginx), CDNs, firewalls.**
7. &#91;R\] **Real-time protocols:** WebSockets, Server-Sent Events (SSE, how LLM responses stream token by token), gRPC.
8. &#91;O\] **High-speed interconnects:** InfiniBand, RDMA, NVLink; why distributed training needs them (S51).

**In industry:** Debugging why a container can't reach a database, setting up HTTPS for an API, streaming LLM tokens to a browser over SSE.

#### S18 APIs and backend development \[E\]

**What:** Building web services that other programs call. **Why:** Every model in production is reached through an API. AI engineers build LLM backends daily. **Prerequisites:** S7, S14, S17 topics 1–5.

1. &#91;E\] **API design:** REST principles, resources, HTTP verbs, status codes, versioning, pagination, idempotency.
2. &#91;E\] **FastAPI:** routes, path/query/body parameters, Pydantic request and response models, automatic OpenAPI docs, dependency injection.
3. &#91;E\] **Async endpoints,** background tasks, streaming responses (SSE) for LLM output.
4. &#91;E\] **Databases in a backend:** SQLAlchemy ORM, migrations (Alembic), connection pooling.
5. &#91;E\] **Authentication and authorization:** API keys, OAuth2, JWT, password hashing; role-based access.
6. &#91;E\] **Testing APIs:** TestClient, httpx, integration tests with a test database.
7. &#91;E\] **Errors, validation and logging;** CORS; rate limiting.
8. &#91;R\] **Flask** (older but common), Django (awareness); gRPC for internal services.
9. &#91;R\] **Task queues:** Celery, RQ or Arq for long jobs (batch inference, document ingestion).
10. &#91;R\] **Simple frontends for demos:** Streamlit, Gradio; basic HTML/JS so you can build a chat UI.
11. &#91;O\] **GraphQL; WebSockets.**

**In industry:** A FastAPI service wraps a model or LLM pipeline, validates input with Pydantic, authenticates users, streams output and logs every request for monitoring (S47).

### Phase 4 — Classical machine learning (Core)

#### S19 ML foundations \[E\]

**What:** The ideas common to all machine learning. **Why:** Every later model, up to and including LLMs, reuses these ideas. **Prerequisites:** S9–S11 (at least topics 1–7 of each), S13.

1. &#91;E\] **What ML is:** learning from data vs hand-written rules; supervised vs unsupervised vs reinforcement learning; when *not* to use ML.
2. &#91;E\] **The ML workflow:** frame the problem → collect data → split → baseline → train → evaluate → iterate → deploy → monitor.
3. &#91;E\] **Train/validation/test splits;** data leakage; why the test set is touched once.
4. &#91;E\] **Loss functions and empirical risk minimization;** gradient descent from scratch in NumPy.
5. &#91;E\] **Generalization:** underfitting vs overfitting, the bias–variance trade-off, learning curves.
6. &#91;E\] **Regularization:** L1 (lasso), L2 (ridge), early stopping.
7. &#91;E\] **Baselines:** majority-class and simple heuristics. Always beat a baseline before you claim success.
8. &#91;R\] **Learning theory intuition:** no free lunch, the curse of dimensionality, inductive bias.

**In industry:** Framing a business request ("reduce churn") as an ML problem, with a metric, a baseline and a split strategy that matches how the model will be used.

#### S20 Supervised learning \[E\]

**What:** Learning to predict a label from input features. **Why:** Most deployed ML is supervised (fraud, pricing, ranking, classification), and gradient-boosted trees still win on tabular data. **Prerequisites:** S19.

1. &#91;E\] **Linear regression:** the normal equation, gradient descent, assumptions, interpreting coefficients, polynomial features.
2. &#91;E\] **Logistic regression:** the sigmoid, log-loss, decision boundary, softmax for multiclass.
3. &#91;E\] **k-nearest neighbours:** distance metrics, choosing k, scaling.
4. &#91;E\] **Naive Bayes:** for text classification.
5. &#91;E\] **Decision trees:** splitting criteria (Gini, entropy), depth, pruning, interpretability.
6. &#91;E\] **Ensembles:** bagging, random forests, boosting (AdaBoost idea), **gradient boosting (XGBoost, LightGBM, CatBoost)**.
7. &#91;E\] **Support vector machines:** margins, hinge loss, kernels (concept).
8. &#91;E\] **Imbalanced data:** class weights, resampling (SMOTE), threshold tuning.
9. &#91;R\] **Time-series forecasting:** lags, rolling features, time-based splits; ARIMA and Prophet awareness; gradient boosting for forecasting.
10. &#91;R\] **Ranking and recommendation basics:** learning to rank, collaborative filtering, matrix factorization.
11. &#91;O\] **Generalized linear models, Gaussian processes.**

**In industry:** XGBoost and LightGBM power credit scoring, fraud detection and demand forecasting. Logistic regression remains the fast, explainable baseline.

#### S21 Unsupervised learning \[E\]

**What:** Finding structure in data without labels. **Why:** Segmentation, anomaly detection, compression and visualizing embeddings. **Prerequisites:** S19, S9 topics 5–6.

1. &#91;E\] **Clustering:** k-means (and k-means++), choosing k (elbow, silhouette), hierarchical clustering, DBSCAN/HDBSCAN.
2. &#91;E\] **Gaussian mixture models** and the expectation–maximization (EM) algorithm.
3. &#91;E\] **Dimensionality reduction:** PCA (from SVD), explained variance; t-SNE and UMAP for visualization (and their pitfalls).
4. &#91;E\] **Anomaly detection:** Isolation Forest, one-class SVM, statistical methods.
5. &#91;R\] **Association rules:** Apriori (market basket analysis).
6. &#91;R\] **Topic modelling:** LDA, and BERTopic (embedding-based).

**In industry:** Customer segmentation, fraud and outlier detection, clustering support tickets, plotting embedding spaces with UMAP to debug a RAG system.

#### S22 Semi-supervised and self-supervised learning \[R\]

**What:** Learning from a few labels plus many unlabelled examples (semi-supervised), or creating labels from the data itself (self-supervised). **Why:** Labels are expensive. Self-supervision is how LLMs and modern vision models are pretrained. **Prerequisites:** S20, S21; S26 for the deep variants.

1. &#91;E\] **Problem setting:** labelled vs unlabelled data; the cluster and manifold assumptions.
2. &#91;E\] **Classical methods:** self-training and pseudo-labelling, label propagation (scikit-learn).
3. &#91;R\] **Consistency regularization:** MixMatch, FixMatch (after S28).
4. &#91;E\] **Self-supervised learning:** pretext tasks; contrastive learning (SimCLR, CLIP); masked modelling (BERT, MAE); next-token prediction (GPT).
5. &#91;R\] **Active learning and weak supervision:** choosing which examples to label; labelling functions (Snorkel idea); using LLMs as labellers.

**In industry:** Using an LLM to pseudo-label 100k support tickets, then training a small fast classifier on them. Active learning to cut labelling budgets.

#### S23 Feature engineering \[E\]

**What:** Turning raw data into inputs a model can learn from. **Why:** On tabular problems, good features beat model tuning. **Prerequisites:** S13, S20 topics 1–6.

1. &#91;E\] **Numeric features:** scaling (standard, min-max, robust), log transforms, binning.
2. &#91;E\] **Categorical features:** one-hot, ordinal and target encoding (and its leakage risk), hashing.
3. &#91;E\] **Missing data:** imputation strategies, missing-indicator features.
4. &#91;E\] **Datetime features:** cyclical encoding, lags, rolling windows, holidays.
5. &#91;E\] **Text features:** bag of words, TF-IDF, n-grams; embeddings (S33).
6. &#91;E\] **Feature selection:** correlation, mutual information, L1, permutation importance, recursive feature elimination.
7. &#91;E\] **scikit-learn Pipelines and ColumnTransformer:** these stop leakage and make features reproducible.
8. &#91;R\] **Feature interactions;** domain-driven features.
9. &#91;R\] **Feature stores:** offline/online consistency (Feast concept; see S46).

**In industry:** Fraud models use "transactions in the last 1 hour" features computed identically in training and serving. Mismatched features (training–serving skew) is a top cause of production bugs.

#### S24 Model evaluation and optimization \[E\]

**What:** Measuring model quality honestly, and improving it. **Why:** A wrong metric or a leaky split produces models that look great offline and fail in production. **Prerequisites:** S20, S11 topics 8–9.

1. &#91;E\] **Classification metrics:** confusion matrix, accuracy, precision, recall, F1, ROC-AUC, PR-AUC, log-loss; choosing a threshold from business costs.
2. &#91;E\] **Regression metrics:** MAE, MSE, RMSE, R², MAPE and its pitfalls.
3. &#91;E\] **Ranking metrics:** precision@k, recall@k, MRR, NDCG. These are reused for RAG retrieval in S36.
4. &#91;E\] **Cross-validation:** k-fold, stratified, group, time-series split.
5. &#91;E\] **Hyperparameter tuning:** grid search, random search, Bayesian optimization (Optuna).
6. &#91;E\] **Error analysis:** slice metrics by segment; inspect the worst errors.
7. &#91;E\] **Calibration:** reliability curves, Platt scaling, isotonic regression.
8. &#91;E\] **Interpretability:** feature importance, permutation importance, SHAP, partial dependence plots.
9. &#91;R\] **Statistical comparison of models:** confidence intervals, bootstrap, McNemar's test.
10. &#91;R\] **Fairness metrics** (links to S48).

**In industry:** A churn model is judged on recall at a fixed contact budget, sliced by region. SHAP explanations go to the risk team, and the threshold is set from the cost of a false positive.

#### S25 Classical ML capstone \[E\]

One end-to-end project of about 40 hours that combines S13–S24: a real dataset, EDA, features, three or more models, tuning, honest evaluation, SHAP, and a short write-up. It is described in section 8 as project P4.

### Phase 5 — Deep learning (Core)

#### S26 Neural network foundations \[E\]

**What:** How neural networks compute, learn and fail. **Why:** Every modern AI system (vision, speech, LLMs) is a neural network. Understanding backprop from scratch makes every later debug session faster. **Prerequisites:** S9, S10 (chain rule, gradients), S19.

1. &#91;E\] **The neuron and the perceptron;** multi-layer perceptrons (MLPs); the universal approximation idea.
2. &#91;E\] **Activation functions:** sigmoid, tanh, ReLU, Leaky ReLU, GELU, SiLU/Swish, softmax; why non-linearity matters.
3. &#91;E\] **Forward pass and loss functions:** MSE, cross-entropy, binary cross-entropy.
4. &#91;E\] **Backpropagation:** build an autograd engine from scratch (Karpathy's micrograd), computational graphs.
5. &#91;E\] **Optimizers:** SGD, momentum, Nesterov, RMSProp, Adam, AdamW; learning-rate schedules (warmup, cosine decay).
6. &#91;E\] **Initialization:** Xavier/Glorot, He/Kaiming; why bad initialization kills training.
7. &#91;E\] **Normalization:** batch norm, layer norm, RMSNorm.
8. &#91;E\] **Regularization:** dropout, weight decay, data augmentation, early stopping.
9. &#91;E\] **Training diagnostics:** loss curves, gradient norms, the overfit-one-batch test, vanishing/exploding gradients, residual connections.
10. &#91;R\] **Mixed precision** (fp16/bf16) and gradient clipping.

**In industry:** When a training run diverges, you check the learning rate, gradient norms, initialization and data bugs in that order. That sequence comes from this subject.

#### S27 PyTorch (+ TensorFlow/Keras awareness) \[E\]

**What:** The main deep-learning framework. **Why:** Most research and industry models (including most LLMs) are written in PyTorch. **Prerequisites:** S26 topics 1–5, S6.

1. &#91;E\] **Tensors:** creation, dtypes, devices (CPU/GPU/MPS), indexing, broadcasting, reshaping (view, reshape, permute), einsum.
2. &#91;E\] **Autograd:** requires\_grad, backward, torch.no\_grad, detaching.
3. &#91;E\] **nn.Module:** layers, parameters, building custom models; nn.Sequential.
4. &#91;E\] **Data:** Dataset, DataLoader, batching, shuffling, num\_workers, collate functions, transforms.
5. &#91;E\] **The training loop:** forward → loss → backward → optimizer step → zero\_grad; evaluation mode; model.train() vs model.eval().
6. &#91;E\] **Saving and loading:** state\_dict, checkpoints, resuming training, safetensors.
7. &#91;E\] **GPU usage:** .to(device), memory management, torch.cuda memory stats.
8. &#91;R\] **Higher-level libraries:** PyTorch Lightning, Hugging Face Accelerate.
9. &#91;R\] **Performance:** torch.compile, automatic mixed precision (torch.amp), the profiler.
10. &#91;R\] **TensorFlow/Keras:** enough to read and run TF code; Keras 3's multi-backend design.
11. &#91;O\] **JAX:** functional transforms (jit, grad, vmap); used at Google and DeepMind.

**In industry:** You write custom Datasets for company data, adapt Hugging Face model code, add mixed precision to cut training cost, and export models for serving (S44).

#### S28 CNNs and computer vision \[E\]

**What:** Neural networks for images and video, plus the wider field of computer vision. **Why:** Inspection, medical imaging, retail, autonomous systems and document AI (OCR) are all vision. **Prerequisites:** S27.

1. &#91;E\] **Image basics:** pixels, channels, colour spaces, image loading with OpenCV/PIL, resizing and normalization.
2. &#91;E\] **Convolutions:** kernels, stride, padding, receptive fields, pooling; why CNNs share weights.
3. &#91;E\] **Classic architectures:** LeNet, AlexNet, VGG, ResNet (residual connections), Inception; EfficientNet and MobileNet for efficiency.
4. &#91;E\] **Transfer learning and fine-tuning** with pretrained models (torchvision, timm).
5. &#91;E\] **Data augmentation:** flips, crops, colour jitter, mixup/cutmix; torchvision v2 transforms or Albumentations.
6. &#91;E\] **Object detection:** bounding boxes, IoU, anchor boxes, non-max suppression; two-stage (Faster R-CNN) vs one-stage (YOLO) detectors; mAP.
7. &#91;E\] **Segmentation:** semantic, instance and panoptic segmentation; U-Net, Mask R-CNN; Segment Anything (SAM).
8. &#91;R\] **Vision Transformers (ViT)** and CLIP (image–text embeddings); after S30.
9. &#91;R\] **OCR and document AI;** video basics (frames, tracking).
10. &#91;O\] **3D vision, pose estimation, depth estimation.**

**In industry:** Fine-tuning a YOLO model for defect detection on a factory line, then exporting it to ONNX and running it on an edge GPU.

#### S29 RNNs, LSTMs and GRUs \[R\]

**What:** Networks that process sequences step by step while keeping a memory. **Why:** They are the historical lead-in to Transformers and are still used in some time-series and on-device speech systems. Understanding their limits explains why attention won. **Prerequisites:** S27.

1. &#91;E\] **Sequence modelling:** variable-length input, teacher forcing, many-to-one vs many-to-many.
2. &#91;E\] **Vanilla RNNs:** hidden state, backpropagation through time, vanishing gradients.
3. &#91;E\] **LSTM:** input, forget and output gates; cell state.
4. &#91;E\] **GRU:** a simpler gated design; comparison with LSTM.
5. &#91;E\] **Encoder–decoder (seq2seq)** models, and Bahdanau attention as the bridge to S30.
6. &#91;R\] **Bidirectional and stacked RNNs;** 1D CNNs for sequences.
7. &#91;O\] **State-space models (Mamba)** as the modern recurrent revival (see S53).

**In industry:** Mostly legacy and niche now, used in some forecasting and streaming systems. The main value is understanding why Transformers replaced them.

#### S30 Attention mechanisms and Transformers \[E\]

**What:** The architecture behind all modern LLMs and most modern vision and audio models. **Why:** It is the single most important architecture to understand deeply. **Prerequisites:** S27, S9 (matrix products), S29 topic 5 helps.

1. &#91;E\] **Attention intuition:** queries, keys and values; soft lookup; scaled dot-product attention formula.
2. &#91;E\] **Self-attention and multi-head attention;** causal masking for decoders.
3. &#91;E\] **Positional information:** sinusoidal, learned, and rotary embeddings (RoPE).
4. &#91;E\] **The Transformer block:** attention + feed-forward MLP + residual connections + layer norm (pre-norm vs post-norm).
5. &#91;E\] **Three families:** encoder-only (BERT), decoder-only (GPT, Llama), encoder–decoder (T5).
6. &#91;E\] **Build a GPT from scratch:** character-level, then BPE tokens (Karpathy's "Let's build GPT", nanoGPT).
7. &#91;E\] **Complexity:** O(n²) attention cost, context length, the KV cache at inference.
8. &#91;R\] **Efficiency variants:** FlashAttention, grouped-query attention (GQA), multi-query attention, sliding-window attention, mixture of experts (MoE).
9. &#91;R\] **Vision Transformers and multimodal Transformers.**

**In industry:** Reading model cards ("GQA, RoPE, 128k context"), estimating KV-cache memory for serving, choosing between encoder models (for classification and embeddings) and decoder models (for generation).

#### S31 Natural language processing \[E\]

**What:** Making computers process and generate human language. **Why:** Search, chatbots, summarization, extraction and translation are core business uses of AI. **Prerequisites:** S20, S27; S30 for topics 5–8.

1. &#91;E\] **Text preprocessing:** normalization, tokenization (word, subword), stemming vs lemmatization, stop words, regex.
2. &#91;E\] **Classical representations:** bag of words, TF-IDF, n-gram language models.
3. &#91;E\] **Word embeddings:** word2vec, GloVe, FastText; analogies; their limits (one vector per word).
4. &#91;E\] **Classical tasks:** text classification, sentiment, named-entity recognition (NER), part-of-speech tagging; spaCy pipelines.
5. &#91;E\] **Transformer NLP with Hugging Face:** pipelines, AutoTokenizer, AutoModel, fine-tuning BERT for classification and NER with the Trainer API.
6. &#91;E\] **Sequence-to-sequence tasks:** summarization, translation, question answering (extractive vs generative).
7. &#91;E\] **Evaluation:** accuracy/F1 for classification, BLEU, ROUGE, BERTScore; their weaknesses.
8. &#91;R\] **Semantic search and sentence embeddings** (bridge to S33/S36).
9. &#91;R\] **Multilingual NLP** (Indian languages: IndicBERT and AI4Bharat models are worth exploring).
10. &#91;O\] **Speech:** ASR with Whisper; text-to-speech.

**In industry:** Classifying support tickets with a fine-tuned small encoder (cheaper and faster than an LLM), extracting entities from contracts, multilingual search.

#### S32 Generative models: autoencoders, VAEs, GANs, diffusion \[R\]

**What:** Models that generate new images, audio or other data. **Why:** Image generation (Stable Diffusion, Flux), synthetic data and multimodal AI products all use them. **Prerequisites:** S27, S28, S11 topics 4–7 and 10.

1. &#91;E\] **Autoencoders:** encoder, bottleneck, decoder; denoising autoencoders; anomaly detection use.
2. &#91;E\] **Variational autoencoders (VAEs):** latent variables, the reparameterization trick, the ELBO (KL + reconstruction).
3. &#91;E\] **GANs:** generator vs discriminator, the minimax game, mode collapse, DCGAN, StyleGAN (awareness).
4. &#91;E\] **Diffusion models:** the forward noising process, learning to denoise (DDPM), sampling steps, classifier-free guidance.
5. &#91;E\] **Latent diffusion and Stable Diffusion:** VAE + U-Net/DiT + text encoder; using Hugging Face diffusers.
6. &#91;R\] **Fine-tuning diffusion:** LoRA, DreamBooth, ControlNet.
7. &#91;O\] **Flow matching, video generation, audio generation.**

**In industry:** Product-image generation, synthetic training data, and image editing tools. Most teams fine-tune or serve existing models rather than training from scratch.

### Phase 6 — Generative AI and large language models (Core)

#### S33 LLM fundamentals, tokenization and embeddings \[E\]

**What:** How LLMs are built, trained, and turn text into numbers and back. **Why:** Without this, LLM behaviour (hallucination, cost, context limits, odd failures with numbers or rare languages) looks random. **Prerequisites:** S30, S31.

1. &#91;E\] **Tokenization:** characters vs words vs subwords; byte-pair encoding (BPE), WordPiece, SentencePiece/Unigram; vocabulary size; build a BPE tokenizer from scratch; tiktoken; why tokenization causes arithmetic and spelling quirks and higher cost for Telugu or Hindi text.
2. &#91;E\] **Embeddings:** token embeddings vs sentence embeddings; embedding models (sentence-transformers, API embedding models); similarity metrics; the MTEB leaderboard; dimensions vs cost.
3. &#91;E\] **Pretraining:** next-token prediction, data mixtures, compute; scaling laws (Kaplan, Chinchilla).
4. &#91;E\] **Post-training:** supervised fine-tuning (SFT) / instruction tuning; preference tuning with RLHF, DPO and related methods; reasoning training with reinforcement learning (o1/R1-style).
5. &#91;E\] **Inference and decoding:** logits, softmax, temperature, top-k, top-p, greedy vs sampling, beam search; stop sequences; the KV cache; context windows.
6. &#91;E\] **The model landscape:** closed APIs (OpenAI, Anthropic, Google) vs open-weight models (Llama, Qwen, Mistral, Gemma, DeepSeek); model cards; licences; how to pick a model for cost, latency and quality.
7. &#91;E\] **Limitations:** hallucination, knowledge cutoff, sycophancy, prompt sensitivity, lost-in-the-middle.
8. &#91;R\] **Multimodal LLMs:** vision-language models, audio models; how images become tokens.
9. &#91;R\] **Reasoning models:** test-time compute, thinking budgets; when they help and what they cost.

**In industry:** Estimating monthly cost from tokens per request, picking an embedding model for a Telugu + English search system, explaining to a manager why the model is "confidently wrong".

#### S34 Prompt engineering and LLM APIs \[E\]

**What:** Getting reliable behaviour from LLMs through instructions, examples and API features. **Why:** It is the cheapest, fastest way to improve an LLM product, and the base layer of RAG and agents. **Prerequisites:** S33, S18.

1. &#91;E\] **API basics:** messages (system/user/assistant), parameters, streaming, token counting, errors, retries with backoff, rate limits, cost tracking.
2. &#91;E\] **Prompt techniques:** clear instructions, role and context, few-shot examples, delimiters/XML tags, step-by-step reasoning (chain of thought), prompt chaining.
3. &#91;E\] **Structured output:** JSON mode, schemas, Pydantic validation, the Instructor library; handling failures to parse.
4. &#91;E\] **Tool use / function calling:** tool schemas, the call → execute → return loop.
5. &#91;E\] **Prompt management:** versioning prompts, templates, testing prompts against a dataset (links to S39).
6. &#91;E\] **Cost and latency:** prompt caching, batch APIs, choosing smaller models, response caching.
7. &#91;R\] **Running local models:** Ollama, llama.cpp; OpenAI-compatible APIs.
8. &#91;R\] **Prompt optimization frameworks:** DSPy (treat prompts as programs to optimize).
9. &#91;E\] **Safety basics:** prompt injection, jailbreaks, output filtering (deeper in S48).

**In industry:** Turning messy emails into validated JSON tickets; a classifier built from a prompt plus 10 examples, shipped in a day and then evaluated on 500 labelled cases.

#### S35 Fine-tuning and parameter-efficient fine-tuning \[E\]

**What:** Further training a pretrained model on your data. **Why:** It teaches a model a format, style, domain or task that prompting can't reach cheaply, and it lets a small model match a big one on a narrow task. **Prerequisites:** S27, S30, S33.

1. &#91;E\] **When to fine-tune vs prompt vs RAG:** knowledge → RAG; behaviour and format → fine-tuning; try prompting first.
2. &#91;E\] **Full fine-tuning:** the Hugging Face Trainer; memory needs (weights + gradients + optimizer states).
3. &#91;E\] **Datasets for fine-tuning:** instruction formats, chat templates, data quality over quantity, synthetic data generation, train/eval splits.
4. &#91;E\] **Parameter-efficient fine-tuning (PEFT):** LoRA (low-rank adapters, rank and alpha), QLoRA (4-bit base model + LoRA), adapters, prefix tuning; merging adapters.
5. &#91;E\] **Tooling:** Hugging Face PEFT, TRL (SFTTrainer, DPOTrainer), Unsloth, Axolotl/torchtune (awareness).
6. &#91;E\] **Preference tuning:** DPO and its variants; reward models and PPO (concept; links to S50); GRPO for reasoning (concept).
7. &#91;E\] **Evaluating a fine-tuned model:** held-out sets, LLM-as-judge, regression tests for general capability (catastrophic forgetting).
8. &#91;R\] **Embedding-model fine-tuning** for retrieval (sentence-transformers).
9. &#91;R\] **Distillation:** training a small model on a large model's outputs.
10. &#91;O\] **Continued pretraining** on domain text; model merging.

**In industry:** QLoRA-tuning an 8B open model on 5,000 company support transcripts so it matches the house tone at 1/20th of the API cost, then evaluating it against the API model.

#### S36 Retrieval-augmented generation (RAG) and vector databases \[E\]

**What:** Giving an LLM relevant documents at question time, so it answers from your data. **Why:** It is the most common enterprise LLM pattern: chat over docs, support bots, internal search. **Prerequisites:** S33, S34, S14; S24 topic 3 (ranking metrics).

1. &#91;E\] **The RAG pipeline:** ingest → parse → chunk → embed → index → retrieve → (rerank) → generate with citations.
2. &#91;E\] **Document parsing:** PDFs, HTML, tables, scanned docs (OCR); keeping metadata.
3. &#91;E\] **Chunking:** fixed-size, recursive, by structure (headings), semantic chunking; overlap; chunk-size trade-offs.
4. &#91;E\] **Vector search:** exact vs approximate nearest neighbour; index types (flat, IVF, HNSW, product quantization); recall vs latency.
5. &#91;E\] **Vector databases:** FAISS (a library), Chroma (local dev), Qdrant, Pinecone (managed), pgvector (inside Postgres), Weaviate/Milvus (awareness); metadata filtering; multi-tenancy.
6. &#91;E\] **Better retrieval:** hybrid search (BM25 + vectors), reciprocal rank fusion, rerankers (cross-encoders), query rewriting, HyDE, multi-query, contextual retrieval.
7. &#91;E\] **Generation:** prompt templates with context, citations, "I don't know" behaviour, handling long contexts and lost-in-the-middle.
8. &#91;E\] **RAG evaluation:** retrieval metrics (recall@k, MRR), generation metrics (faithfulness, answer relevance), Ragas, building a golden question set.
9. &#91;R\] **Advanced patterns:** agentic RAG, GraphRAG (knowledge graphs), multimodal RAG, parent-document retrieval, self-RAG/corrective RAG.
10. &#91;R\] **Operations:** incremental re-indexing, access control on documents, caching, cost.

**In industry:** An HR policy assistant over 3,000 PDFs with hybrid search and a reranker, answering with citations, evaluated weekly on 200 golden questions, with document-level permissions enforced at retrieval time.

#### S37 AI agents and agentic AI \[E\]

**What:** LLM systems that decide which actions to take (call tools, search, write code) in a loop until a goal is met. **Why:** Agents are the fastest-growing area of AI engineering: coding agents, research agents, customer-service automation. **Prerequisites:** S34 (tool use), S36, S7 (async), S18.

1. &#91;E\] **Workflows vs agents:** prompt chains, routing, parallelization, orchestrator–workers, evaluator–optimizer loops; start with the simplest pattern that works.
2. &#91;E\] **The agent loop:** reason → act → observe (ReAct); stopping conditions; max steps; error recovery.
3. &#91;E\] **Tools:** designing tool interfaces and descriptions, input validation, idempotent and safe tools, code execution sandboxes.
4. &#91;E\] **Memory and state:** short-term (conversation), long-term (vector or structured memory), context-window management and summarization.
5. &#91;E\] **Planning and reflection:** task decomposition, self-critique, retries.
6. &#91;E\] **Frameworks:** build one agent with no framework first; then **LangGraph** (stateful graphs, checkpoints, human-in-the-loop); awareness of the OpenAI Agents SDK, Claude Agent SDK, LlamaIndex, CrewAI, Pydantic AI.
7. &#91;E\] **Model Context Protocol (MCP):** a standard way to connect tools and data to any model; build an MCP server.
8. &#91;E\] **Human-in-the-loop and guardrails:** approval steps for risky actions, permissioning, audit logs.
9. &#91;E\] **Evaluating agents:** task success rate, trajectory review, cost and steps per task, benchmarks (SWE-bench and similar, awareness).
10. &#91;R\] **Computer-use and browser agents** (experimental, fast-moving).

**In industry:** A support agent that reads the ticket, looks up the order through an API tool, drafts a refund, and asks a human to approve anything above ₹5,000. Every step is traced in Langfuse or LangSmith.

#### S38 Multi-agent systems \[R\]

**What:** Several specialized agents that cooperate or check each other. **Why:** Useful for complex tasks such as research → write → review, but often over-used. Knowing when *not* to use multiple agents is the real skill. **Prerequisites:** S37.

1. &#91;E\] **Architectures:** supervisor/orchestrator, hierarchical, peer-to-peer, sequential pipeline, debate/critic.
2. &#91;E\] **Communication:** shared state vs message passing; handoffs; agent-to-agent (A2A) protocol (emerging).
3. &#91;E\] **Implementations:** LangGraph multi-agent, CrewAI, AutoGen/AG2 (awareness).
4. &#91;E\] **Failure modes:** loops, cost explosions, conflicting instructions, error propagation; observability for multi-agent traces.
5. &#91;R\] **When single agents win:** cost and latency comparisons; run single- vs multi-agent evals on the same tasks.
6. &#91;O\] **Agent simulations** (generative agents) and classical multi-agent RL concepts.

**In industry:** A research assistant with a planner, parallel search workers and a citation checker, where the parallelism cuts latency and the checker cuts hallucinated sources.

#### S39 LLM evaluation \[E\]

**What:** Measuring whether an LLM system is good, and whether a change made it better. **Why:** "It looked good on 5 examples" is the most common reason LLM products fail. Evals are the AI engineer's unit tests. **Prerequisites:** S24, S34.

1. &#91;E\] **Error analysis first:** read real outputs, categorize failures, then design metrics.
2. &#91;E\] **Eval datasets:** golden sets, synthetic test generation, adversarial cases, keeping eval data out of training data.
3. &#91;E\] **Metric types:** exact/rule-based checks, reference-based (ROUGE, embedding similarity), LLM-as-judge (rubrics, pairwise comparison, judge bias), human evaluation.
4. &#91;E\] **Tooling:** pytest-style eval suites; DeepEval, promptfoo, Ragas, Inspect (awareness); tracing tools (Langfuse, Phoenix, LangSmith).
5. &#91;E\] **Regression testing in CI:** block merges that drop eval scores (links to S42).
6. &#91;R\] **Public benchmarks:** MMLU, GSM8K, HumanEval, SWE-bench, the LMArena leaderboard; contamination; why benchmarks ≠ your use case.
7. &#91;R\] **Online evaluation:** user feedback, A/B tests, guardrail metrics.

**In industry:** Every prompt change runs against 300 test cases in CI. An LLM judge scores faithfulness, and the change only ships if scores hold and cost per request doesn't rise.

### Phase 7 — Production AI engineering (Core)

#### S40 Docker and containerization \[E\]

**What:** Packaging an application with everything it needs into a portable container. **Why:** It is how every model, API and pipeline is shipped and run in production. **Prerequisites:** S2, S18. The full curriculum (12 modules, about 80 hours) is in **section 7**. Start Docker basics early: you can use containers for databases from Phase 3 onward.

#### S41 Kubernetes and orchestration \[R\]

**What:** A system that runs and manages many containers across many machines. **Why:** Most companies serve models, run training jobs and host LLM inference on Kubernetes. It is essential for MLOps and platform roles, and recommended for AI engineers. **Prerequisites:** S40, S17.

1. &#91;E\] **Why orchestration:** scheduling, self-healing, scaling, desired-state reconciliation.
2. &#91;E\] **Architecture:** control plane (API server, etcd, scheduler, controller manager), worker nodes (kubelet, container runtime, kube-proxy).
3. &#91;E\] **Core objects:** Pods, ReplicaSets, Deployments, Services (ClusterIP, NodePort, LoadBalancer), Namespaces, labels and selectors.
4. &#91;E\] **Configuration:** ConfigMaps, Secrets, environment variables, resource requests and limits.
5. &#91;E\] **kubectl:** apply, get, describe, logs, exec, port-forward; debugging CrashLoopBackOff and ImagePullBackOff.
6. &#91;E\] **Storage:** Volumes, PersistentVolumes, PersistentVolumeClaims, StorageClasses (for model weights and checkpoints).
7. &#91;E\] **Networking:** Services, Ingress / Gateway API, DNS inside the cluster.
8. &#91;E\] **Health and scaling:** liveness, readiness and startup probes (important for slow-loading models); HorizontalPodAutoscaler.
9. &#91;E\] **Packaging:** Helm charts; Kustomize.
10. &#91;E\] **Jobs and CronJobs** for training and batch inference.
11. &#91;R\] **GPUs on Kubernetes:** the NVIDIA device plugin / GPU Operator, node selectors, taints and tolerations.
12. &#91;R\] **ML on Kubernetes:** KServe, Kubeflow (Pipelines, Training Operator), Ray on Kubernetes (KubeRay), KEDA for event-driven autoscaling.
13. &#91;R\] **GitOps:** Argo CD / Flux.
14. &#91;O\] **Operators and custom resources (CRDs); service mesh (Istio).**

**In industry:** A vLLM Deployment on GPU nodes, with a readiness probe that waits for the weights to load, autoscaling on queue depth, and Helm-managed releases through Argo CD.

#### S42 CI/CD \[E\]

**What:** Automatically testing, building and deploying code on every change (continuous integration / continuous delivery). **Why:** It catches bugs before users do and makes deploys boring. For ML, it also runs data checks and eval suites. **Prerequisites:** S3, S8, S40.

1. &#91;E\] **Concepts:** CI vs continuous delivery vs continuous deployment; pipelines, stages, artifacts.
2. &#91;E\] **GitHub Actions:** workflows, triggers, jobs, steps, runners, matrix builds, caching, secrets.
3. &#91;E\] **A Python CI pipeline:** lint (Ruff) → type-check → test (pytest) → coverage.
4. &#91;E\] **Container CI:** build → scan → push an image to a registry; tagging strategy.
5. &#91;E\] **Deployment strategies:** rolling, blue-green, canary, shadow deployments (important for models).
6. &#91;E\] **ML-specific CI:** data validation, model tests, eval-gated merges (S39), model registry promotion (S46).
7. &#91;R\] **Infrastructure as Code:** Terraform basics (links to S43).
8. &#91;O\] **Other CI systems:** GitLab CI, Jenkins (awareness).

**In industry:** A merge to main triggers tests, builds a Docker image, runs the eval suite, deploys a canary taking 5% of traffic, and rolls back automatically if error rates rise.

#### S43 Cloud computing: AWS, Azure, GCP \[E\]

**What:** Renting compute, storage and managed AI services. **Why:** Production AI runs in the cloud, and GPU access is usually cloud-based. **Learn one cloud deeply (AWS has the most jobs) and the other two at the concept level; the concepts transfer.** **Prerequisites:** S2, S17, S40.

1. &#91;E\] **Cloud basics:** regions and availability zones, the shared responsibility model, pricing models (on-demand, spot, reserved), free tiers, billing alerts (set these up on day 1).
2. &#91;E\] **Identity and access:** IAM users, roles, policies, least privilege, service accounts.
3. &#91;E\] **Compute:** VMs (EC2 / Azure VM / Compute Engine), GPU instance types, serverless functions (Lambda / Azure Functions / Cloud Run functions), container services (ECS, Cloud Run, Azure Container Apps).
4. &#91;E\] **Storage:** object storage (S3 / Blob / GCS), block storage, managed databases (RDS / Cloud SQL / Azure SQL).
5. &#91;E\] **Networking:** VPCs, subnets, security groups, load balancers.
6. &#91;E\] **Managed Kubernetes:** EKS / AKS / GKE.
7. &#91;E\] **Managed ML platforms:** SageMaker, Azure Machine Learning, Vertex AI (training jobs, endpoints, pipelines).
8. &#91;E\] **Managed LLM services:** Amazon Bedrock, Azure OpenAI / AI Foundry, Vertex AI Gemini; enterprise concerns (data residency, private networking).
9. &#91;E\] **Infrastructure as Code:** Terraform fundamentals (providers, resources, state, modules).
10. &#91;R\] **Cost management:** right-sizing GPUs, spot instances for training, autoscaling to zero, budgets.
11. &#91;R\] **GPU clouds:** Lambda, RunPod, Modal, Together and similar, for cheaper experiments.
12. &#91;O\] **Certifications:** AWS Certified AI Practitioner or Machine Learning Engineer – Associate, Azure AI Engineer Associate, Google Professional ML Engineer. Useful for resumes, but never a substitute for projects.

**In industry:** Terraform creates an S3 bucket, an ECR repo and an EKS cluster. Training runs on spot GPUs, and the model is served behind a load balancer with IAM-scoped access to Bedrock.

#### S44 Model serving and inference \[E\]

**What:** Running trained models so they answer real requests fast and cheaply. **Why:** Inference is where most of the cost and all of the user experience lives. **Prerequisites:** S18, S27, S40; S30 topic 7 (KV cache).

1. &#91;E\] **Serving patterns:** online (real-time) vs batch vs streaming; synchronous vs asynchronous; edge vs cloud.
2. &#91;E\] **Simple serving:** a model behind FastAPI; loading the model once at startup; input validation; health checks.
3. &#91;E\] **Performance metrics:** latency (p50/p95/p99), throughput, time to first token (TTFT), inter-token latency, tokens per second, cost per 1,000 requests.
4. &#91;E\] **Batching:** static vs dynamic batching; continuous batching for LLMs.
5. &#91;E\] **LLM inference servers:** vLLM (PagedAttention, OpenAI-compatible server), SGLang, Hugging Face TGI (awareness), Ollama and llama.cpp (local/CPU), NVIDIA NIM (awareness).
6. &#91;E\] **General inference servers:** NVIDIA Triton Inference Server, TorchServe (now in limited maintenance, awareness), BentoML, Ray Serve.
7. &#91;E\] **Model formats:** safetensors, ONNX, TorchScript/torch.export, GGUF (llama.cpp), TensorRT engines.
8. &#91;E\] **Scaling:** horizontal scaling, GPU memory planning (weights + KV cache), autoscaling, cold starts, request queues.
9. &#91;R\] **Advanced LLM serving:** prefix caching, speculative decoding, tensor parallelism across GPUs, LoRA adapter serving (multi-LoRA), routing between models.
10. &#91;R\] **API gateways for LLMs:** LiteLLM, model fallback, rate limits per user.

**In industry:** Moving from a naive Hugging Face generate() loop (2 requests/second) to vLLM with continuous batching (40+ requests/second on the same GPU), measured with a load test.

#### S45 Model optimization and quantization \[R\]

**What:** Making models smaller and faster with minimal quality loss. **Why:** It decides whether a model fits on your GPU (or phone) and what each request costs. **Prerequisites:** S27, S44; S1 topic 1 (floating point).

1. &#91;E\] **Numeric formats:** fp32, fp16, bf16, fp8, int8, int4; range vs precision.
2. &#91;E\] **Quantization basics:** scale and zero-point, per-tensor vs per-channel, post-training quantization (PTQ) vs quantization-aware training (QAT).
3. &#91;E\] **LLM quantization methods:** bitsandbytes (8-bit/4-bit NF4), GPTQ, AWQ, GGUF quantization levels (Q4\_K\_M and so on); measuring the quality drop.
4. &#91;E\] **Other techniques:** pruning (structured vs unstructured), knowledge distillation, low-rank factorization.
5. &#91;E\] **Compilers and runtimes:** torch.compile, ONNX Runtime, TensorRT / TensorRT-LLM, OpenVINO (Intel CPUs).
6. &#91;R\] **Attention and kernel optimizations:** FlashAttention, fused kernels, operator fusion.
7. &#91;R\] **Benchmarking methodology:** warmup, realistic inputs, quality evals alongside speed tests.
8. &#91;O\] **Edge deployment:** Core ML, TensorFlow Lite / LiteRT, ExecuTorch, MLC.

**In industry:** AWQ-quantizing a 70B model so it serves on 2 GPUs instead of 4, after confirming on the eval suite that quality drops by less than 1%.

#### S46 MLOps and LLMOps \[E\]

**What:** The practices and tools that make ML systems reproducible, automated and maintainable. **Why:** Most ML projects fail in the gap between notebook and production. MLOps is that bridge. **Prerequisites:** S40, S42, S24; S39 for LLMOps.

1. &#91;E\] **MLOps maturity levels:** manual → automated pipeline → CI/CD for ML (Google's level 0/1/2 framing).
2. &#91;E\] **Experiment tracking:** MLflow or Weights & Biases; logging parameters, metrics, artifacts; comparing runs.
3. &#91;E\] **Data and model versioning:** DVC, lakeFS (awareness), Hugging Face Hub; reproducible training (seeds, config snapshots, environment locks).
4. &#91;E\] **Model registry:** versions, stages (staging/production), lineage, model cards.
5. &#91;E\] **ML pipelines:** training pipelines as DAGs (Airflow, Prefect, Kubeflow Pipelines, ZenML, Metaflow, SageMaker Pipelines); scheduled vs triggered retraining.
6. &#91;E\] **Feature stores:** offline/online stores, point-in-time correctness (Feast).
7. &#91;E\] **Testing ML systems:** data tests, model tests, infrastructure tests (the "ML Test Score" idea).
8. &#91;E\] **LLMOps:** prompt versioning, eval pipelines, tracing (Langfuse, LangSmith, Phoenix), guardrails, cost tracking per feature, model and provider fallback.
9. &#91;R\] **Continuous training and model governance;** approval workflows.
10. &#91;O\] **Platform choice:** build vs buy (Databricks, SageMaker, Vertex AI).

**In industry:** A new data drop triggers a pipeline that validates data, retrains, logs to MLflow, compares against the production model, and registers a candidate for canary release only if it wins.

#### S47 Model monitoring and observability \[E\]

**What:** Knowing what your deployed AI system is doing, and noticing when it goes wrong. **Why:** Models degrade silently as the world changes. Infrastructure failures, cost spikes and LLM quality drops must be caught before users notice. **Prerequisites:** S44, S46.

1. &#91;E\] **The three pillars:** metrics, logs and traces; structured logging; correlation IDs.
2. &#91;E\] **Infrastructure monitoring:** Prometheus (metrics, PromQL), Grafana dashboards, GPU metrics (DCGM exporter), alerting.
3. &#91;E\] **Service-level objectives:** SLIs, SLOs, SLAs, error budgets; the golden signals (latency, traffic, errors, saturation).
4. &#91;E\] **Distributed tracing:** OpenTelemetry (SDKs, collector, spans); OpenTelemetry's GenAI conventions for LLM calls.
5. &#91;E\] **ML monitoring:** data drift, concept drift, prediction drift (PSI, KS test); delayed ground truth; Evidently.
6. &#91;E\] **LLM monitoring:** token usage and cost, latency per step, hallucination and guardrail flags, user feedback, trace review (Langfuse/Phoenix).
7. &#91;R\] **Incident response:** on-call basics, runbooks, postmortems.

**In industry:** A Grafana dashboard shows p95 latency, GPU utilization and cost per request. An Evidently job flags input drift weekly, and a Langfuse view samples 1% of conversations for human review.

#### S48 AI security and responsible AI \[E\]

**What:** Protecting AI systems from attack and misuse, and making sure they are fair, private and accountable. **Why:** LLM apps add new attack surfaces (prompt injection, data leakage), and laws such as the EU AI Act and India's DPDP Act create legal duties. **Prerequisites:** S34, S36, S37; S18 topic 5.

1. &#91;E\] **The LLM threat landscape:** the OWASP Top 10 for LLM applications: prompt injection (direct and indirect), sensitive information disclosure, insecure output handling, excessive agency, supply-chain risks, data and model poisoning.
2. &#91;E\] **Defences:** least-privilege tools, input/output filtering, separating instructions from data, human approval, sandboxing code execution, rate limits, red-teaming.
3. &#91;E\] **Classical security for ML apps:** secrets management, dependency scanning, container security (section 7), authentication, encryption, audit logging.
4. &#91;E\] **Privacy:** PII detection and redaction, data minimization, retention; differential privacy and federated learning (concept).
5. &#91;E\] **Fairness and bias:** sources of bias, fairness metrics (demographic parity, equalized odds), mitigation; Fairlearn.
6. &#91;E\] **Transparency:** model cards, datasheets for datasets, explainability (S24 topic 8).
7. &#91;E\] **Governance and regulation:** NIST AI Risk Management Framework, the EU AI Act risk tiers, India's Digital Personal Data Protection (DPDP) Act; internal AI policies.
8. &#91;R\] **Adversarial ML:** adversarial examples, model extraction, membership inference; MITRE ATLAS.
9. &#91;R\] **Guardrail tooling:** NeMo Guardrails, Llama Guard, Guardrails AI (awareness).
10. &#91;O\] **AI safety research:** alignment, interpretability (links to S53).

**In industry:** A RAG app that refuses to follow instructions hidden inside retrieved documents, redacts Aadhaar and phone numbers before logging, and enforces document permissions per user.

#### S49 System design for AI \[E\]

**What:** Designing complete systems (data, models, APIs, infrastructure) that meet requirements for scale, cost and reliability. **Why:** It is the senior-engineer skill, and it is tested in ML system design interviews. **Prerequisites:** S18, S40, S44, S46; S15, S17.

1. &#91;E\] **The design process:** clarify requirements (functional, non-functional), estimate scale (QPS, storage, tokens), sketch a high-level design, go deep on bottlenecks, discuss trade-offs.
2. &#91;E\] **Distributed-systems building blocks:** load balancers, caches, queues, replication, sharding, consistency, idempotency, rate limiting, back-pressure.
3. &#91;E\] **ML system design patterns:** offline training + online serving, feature pipelines, two-stage recommenders (retrieval + ranking), human-in-the-loop labelling, feedback loops.
4. &#91;E\] **LLM system design:** RAG at scale, agent platforms, model routing, caching layers, multi-tenant isolation, cost budgets, fallbacks.
5. &#91;E\] **Reliability:** redundancy, graceful degradation (fall back to a smaller model or a cached answer), timeouts, retries, circuit breakers.
6. &#91;E\] **Cost modelling:** GPU-hours, tokens, storage; build vs buy; API vs self-hosted break-even.
7. &#91;E\] **Writing it down:** design docs, architecture diagrams, ADRs.
8. &#91;R\] **Practice cases:** design a YouTube-style recommender, a fraud detection system, an enterprise RAG search, a coding assistant, a real-time translation service.

**In industry:** Before building, you write a two-page design doc estimating that 1M queries a month at 2k tokens each costs about X with an API vs Y self-hosted, and choose based on latency, privacy and team skill.

### Phase 8 — Advanced and research (Advanced / Specialized)

#### S50 Reinforcement learning \[R\]

**What:** Learning by trial and error from rewards, rather than from labelled examples. **Why:** It powers game AI, robotics and recommendation, and above all LLM post-training (RLHF, and RL for reasoning models). **Prerequisites:** S11 topic 12 (Markov chains), S26, S27. The fundamentals are \[R\]; deep RL research is \[O\].

1. &#91;E\] **The RL problem:** agent, environment, state, action, reward, episode; exploration vs exploitation; multi-armed bandits.
2. &#91;E\] **Markov decision processes:** returns, discounting, policies, value functions, Bellman equations.
3. &#91;E\] **Dynamic programming:** policy iteration, value iteration.
4. &#91;E\] **Model-free methods:** Monte Carlo, temporal-difference learning, SARSA, Q-learning.
5. &#91;E\] **Deep Q-networks (DQN):** experience replay, target networks.
6. &#91;E\] **Policy gradients:** REINFORCE, baselines, actor–critic, advantage estimation (GAE).
7. &#91;E\] **PPO** (proximal policy optimization): the workhorse algorithm, and the one used in classic RLHF.
8. &#91;E\] **RL for LLMs:** reward models, RLHF pipeline, DPO as RL-free preference optimization, GRPO and verifiable rewards for reasoning models.
9. &#91;R\] **Tools:** Gymnasium environments, Stable-Baselines3, CleanRL (single-file implementations), TRL for LLM RL.
10. &#91;O\] **Model-based RL, offline RL, multi-agent RL, imitation learning, robotics (sim-to-real).**

**In industry:** Bandits for recommendation and ad testing; RL fine-tuning of LLMs with verifiable rewards (unit tests for code, exact answers for math).

#### S51 Distributed training and GPU computing \[R\]

**What:** Using GPUs efficiently, and training across many GPUs and machines. **Why:** Large models don't fit on one GPU, and GPU time is the biggest cost in AI. It is essential for ML infrastructure and LLM training roles. **Prerequisites:** S27, S45 topic 1, S17 topic 8, S2.

1. &#91;E\] **GPU architecture:** streaming multiprocessors, CUDA cores vs Tensor Cores, memory hierarchy (HBM, shared memory, registers), memory bandwidth vs compute (the roofline model), arithmetic intensity.
2. &#91;E\] **The GPU memory budget for training:** weights + gradients + optimizer states + activations; activation checkpointing; gradient accumulation.
3. &#91;E\] **Mixed precision training:** autocast, loss scaling, bf16.
4. &#91;E\] **Profiling:** PyTorch profiler, nvidia-smi, Nsight Systems (awareness); finding data-loading bottlenecks.
5. &#91;E\] **Data parallelism:** PyTorch DDP; all-reduce; NCCL; torchrun.
6. &#91;E\] **Sharded data parallelism:** FSDP / FSDP2, DeepSpeed ZeRO stages 1–3.
7. &#91;R\] **Model parallelism:** tensor parallelism (Megatron-LM), pipeline parallelism, sequence/context parallelism, expert parallelism for MoE; 3D parallelism.
8. &#91;R\] **Frameworks:** Hugging Face Accelerate, DeepSpeed, Ray Train, torchtitan (awareness).
9. &#91;R\] **CUDA programming basics:** kernels, threads, blocks, grids, memory coalescing; writing simple kernels in Triton (the OpenAI language) or CUDA C++.
10. &#91;R\] **Cluster operations:** Slurm basics, multi-node setup, checkpointing and fault tolerance, Kubernetes training operators.
11. &#91;O\] **Other accelerators:** TPUs (JAX/XLA), AMD ROCm, AWS Trainium.

**In industry:** Fine-tuning a 70B model with FSDP across 8 GPUs, finding that data loading starves the GPUs, fixing it, and cutting the run cost by 30%.

#### S52 Research track \[R\]

**What:** Reading, reproducing and extending AI research. **Why:** The field moves monthly. Engineers who can read a paper and implement it are the ones who adopt new techniques first. **Prerequisites:** S26, S27, S30; math S9–S11 at L2. The full track is in **section 9**.

1. &#91;E\] Reading papers efficiently (the three-pass method).
2. &#91;E\] Understanding the math notation and turning equations into code.
3. &#91;E\] Interpreting experiments: baselines, ablations, error bars, benchmark contamination.
4. &#91;E\] Reproducing results, from a small scale to the paper's scale.
5. &#91;R\] Designing your own experiments; finding research gaps.
6. &#91;R\] Writing: technical blog posts, arXiv-style reports, workshop papers.

#### S53 Emerging AI (ongoing) \[O\]

**What:** Fast-moving areas to track for one or two hours a week, not to master upfront. Treat everything here as **experimental until it is in production at several companies.**

1. **Reasoning and test-time compute:** reasoning models, verifiers, search at inference time.
2. **Agents at scale:** long-horizon coding and computer-use agents, agent protocols (MCP, A2A), agent evaluation.
3. **Efficient architectures:** state-space models (Mamba), hybrid attention/SSM models, mixture of experts, long context.
4. **Multimodality:** any-to-any models, video generation, speech-native assistants.
5. **Small and on-device models:** distillation, edge inference.
6. **Interpretability and safety:** sparse autoencoders, circuit analysis, scalable oversight.
7. **AI for science and code:** protein models, math provers, automated research.

**How to keep up:** Follow the Hugging Face daily papers page, two or three newsletters or blogs (section 5), and reproduce one notable result per quarter.

#### Missing domains added to this curriculum

These were not in the original list but matter in industry. Each is covered inside the subject named.

| Domain | Where it is covered |
| --- | --- |
| Time-series forecasting | S20 topic 9 |
| Recommender systems and ranking | S20 topic 10, S49 |
| Speech and audio AI | S31 topic 10, S53 |
| Data labelling, active learning and weak supervision | S22 topic 5 |
| Experiment design and A/B testing | S11 topic 9 |
| Information theory | S11 topic 10 |
| Infrastructure as Code (Terraform) | S43 topic 9 |
| Privacy and AI regulation (DPDP Act, EU AI Act) | S48 |
| Technical writing and design documents | S8 topic 7, S49 topic 7 |
| Edge and on-device AI | S45 topic 8 |

### Phase 9 — Capstone and job readiness (Core)

#### S54 Production capstones \[E\]

Two production-grade projects of about 60 hours each, combining every phase. They are described in section 8 as P9 and P10. One must be an LLM system (RAG + agent) and one a classical or deep-learning model with a full MLOps pipeline.

#### S55 Interview and portfolio preparation \[E\]

1. &#91;E\] **Coding interviews:** 150+ DSA problems (the NeetCode 150 list), timed practice.
2. &#91;E\] **ML fundamentals interviews:** explain bias–variance, regularization, metrics, backprop, attention and transformers from memory.
3. &#91;E\] **ML/LLM system design interviews:** S49 practice cases, out loud, with diagrams.
4. &#91;E\] **Project deep-dives:** explain every design decision in your capstones, including what failed.
5. &#91;E\] **Portfolio:** pinned GitHub repos with READMEs, demo videos, a short technical blog, LinkedIn.
6. &#91;R\] **Behavioural interviews:** STAR stories (situation, task, action, result) from projects, internships and open source.

## 3. Prerequisite dependency map

The critical path runs **S1–S4 → S5–S7 → S9–S11 → S19–S24 → S26–S27 → S30 → S33–S37 → S40 → S44 → S46 → S54**. A delay on any of these delays everything after it, so protect those subjects first.

&#91;embedded content: prerequisite map · 55 subjects in 22 groups across 10 phases\]

Read the map top to bottom: each row needs the rows above it. Inside a row, subjects can be learned in either order unless an arrow joins them.

### Cross-phase prerequisites not drawn as arrows

| Subject | Also needs | Why |
| --- | --- | --- |
| S40 Docker | S2 Linux, S18 APIs | Containers are Linux processes, and most images you build wrap an API |
| S37 Agents | S7 asyncio, S18 APIs | Agents call many tools in parallel and are served as APIs |
| S36 RAG | S14 SQL, S24 ranking metrics | Metadata filters, pgvector and recall@k evaluation |
| S39 LLM evaluation | S11 statistics, S24 metrics | Telling a real improvement from noise |
| S41 Kubernetes | S17 networking | Services, DNS and ingress are networking |
| S44 Serving | S30 KV cache, S1 memory | GPU memory planning for LLMs |
| S49 System design | S15, S17, S44, S46 | It combines all of them |
| S50 RL | S11 Markov chains, S27 PyTorch | MDPs and policy networks |
| S51 Distributed training | S17 networking, S45 numeric formats | All-reduce over the network; mixed precision |
| S55 Interviews | S12 DSA | Coding rounds |

## 4. Learning-time estimates

The full program is **2,755 hours**: 868 theory, 1,162 practice and 725 project hours. The 4 h/day column assumes 6 study days a week (24 h/week) and counts only learning weeks. Section 11 adds consolidation and exam weeks.

The estimates assume a motivated beginner who codes along rather than just watching. Expect to take 1.3–1.5× as long for your first subject in each phase, and less once the habits stick. If a subject takes more than twice its estimate, that usually means a prerequisite is weak: go back to it.

| ID | Subject | Priority | Theory h | Practice h | Project h | Total h | Weeks at 4 h/day | Proficiency after |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **P0** | **Phase 0 — Computing foundations** |  | **29** | **44** | **9** | **82** | **3.4** |  |
| S1 | Computing fundamentals | E | 10 | 5 | 0 | 15 | 0.6 | L1 |
| S2 | Linux & the shell | E | 10 | 20 | 5 | 35 | 1.5 | L2 |
| S3 | Git & GitHub | E | 6 | 12 | 4 | 22 | 0.9 | L2 |
| S4 | Dev environment (VS Code, Jupyter, venv/uv) | E | 3 | 7 | 0 | 10 | 0.4 | L2 |
| **P1** | **Phase 1 — Programming & SE** |  | **80** | **130** | **55** | **265** | **11.0** |  |
| S5 | Python — beginner | E | 25 | 45 | 15 | 85 | 3.5 | L2 |
| S6 | Python — intermediate & OOP | E | 20 | 35 | 15 | 70 | 2.9 | L2 |
| S7 | Python — advanced | E | 20 | 30 | 15 | 65 | 2.7 | L2 |
| S8 | Software engineering principles & testing | E | 15 | 20 | 10 | 45 | 1.9 | L2 |
| **P2** | **Phase 2 — Math (parallel)** |  | **105** | **90** | **20** | **215** | **9.0** |  |
| S9 | Linear algebra | E | 35 | 30 | 5 | 70 | 2.9 | L2 |
| S10 | Calculus & optimization | E | 30 | 25 | 5 | 60 | 2.5 | L2 |
| S11 | Probability & statistics | E | 40 | 35 | 10 | 85 | 3.5 | L2 |
| **P3** | **Phase 3 — DSA, data & systems** |  | **110** | **193** | **67** | **370** | **15.4** |  |
| S12 | Data structures & algorithms | E | 35 | 75 | 0 | 110 | 4.6 | L2 |
| S13 | Data analysis (NumPy, pandas, visualization, EDA) | E | 15 | 35 | 20 | 70 | 2.9 | L3 |
| S14 | SQL & relational databases | E | 12 | 25 | 8 | 45 | 1.9 | L3 |
| S15 | NoSQL databases (MongoDB, Redis) | R | 6 | 10 | 4 | 20 | 0.8 | L2 |
| S16 | Data engineering basics | R | 12 | 15 | 13 | 40 | 1.7 | L2 |
| S17 | Computer networks | R | 15 | 8 | 2 | 25 | 1.0 | L1 |
| S18 | APIs & backend development (FastAPI) | E | 15 | 25 | 20 | 60 | 2.5 | L3 |
| **P4** | **Phase 4 — Classical ML** |  | **91** | **116** | **78** | **285** | **11.9** |  |
| S19 | ML foundations | E | 15 | 15 | 0 | 30 | 1.2 | L2 |
| S20 | Supervised learning | E | 35 | 40 | 15 | 90 | 3.8 | L3 |
| S21 | Unsupervised learning | E | 15 | 20 | 10 | 45 | 1.9 | L2 |
| S22 | Semi- & self-supervised learning | R | 6 | 6 | 3 | 15 | 0.6 | L1 |
| S23 | Feature engineering | E | 8 | 17 | 5 | 30 | 1.2 | L3 |
| S24 | Model evaluation & optimization | E | 12 | 18 | 5 | 35 | 1.5 | L3 |
| S25 | Classical ML capstone | E | 0 | 0 | 40 | 40 | 1.7 | L3 |
| **P5** | **Phase 5 — Deep learning** |  | **110** | **152** | **81** | **343** | **14.3** |  |
| S26 | Neural network foundations | E | 20 | 25 | 5 | 50 | 2.1 | L2 |
| S27 | PyTorch (+ TensorFlow/Keras awareness) | E | 10 | 30 | 10 | 50 | 2.1 | L3 |
| S28 | CNNs & computer vision | E | 20 | 25 | 20 | 65 | 2.7 | L2 |
| S29 | RNNs, LSTMs, GRUs | R | 10 | 12 | 6 | 28 | 1.2 | L2 |
| S30 | Attention & Transformers | E | 20 | 25 | 15 | 60 | 2.5 | L3 |
| S31 | Natural language processing | E | 15 | 20 | 15 | 50 | 2.1 | L2 |
| S32 | Generative models (VAE, GAN, diffusion) | R | 15 | 15 | 10 | 40 | 1.7 | L2 |
| **P6** | **Phase 6 — GenAI & LLMs** |  | **85** | **115** | **85** | **285** | **11.9** |  |
| S33 | LLM fundamentals, tokenization, embeddings | E | 20 | 15 | 5 | 40 | 1.7 | L2 |
| S34 | Prompt engineering & LLM APIs | E | 8 | 15 | 7 | 30 | 1.2 | L3 |
| S35 | Fine-tuning & PEFT | E | 15 | 20 | 15 | 50 | 2.1 | L2 |
| S36 | RAG & vector databases | E | 15 | 25 | 20 | 60 | 2.5 | L3 |
| S37 | AI agents & agentic AI | E | 15 | 20 | 20 | 55 | 2.3 | L3 |
| S38 | Multi-agent systems | R | 6 | 10 | 14 | 30 | 1.2 | L2 |
| S39 | LLM evaluation | E | 6 | 10 | 4 | 20 | 0.8 | L2 |
| **P7** | **Phase 7 — Production AI** |  | **143** | **202** | **115** | **460** | **19.2** |  |
| S40 | Docker & containerization (section 7) | E | 20 | 35 | 25 | 80 | 3.3 | L3 |
| S41 | Kubernetes & orchestration | R | 20 | 30 | 15 | 65 | 2.7 | L2 |
| S42 | CI/CD | E | 6 | 12 | 7 | 25 | 1.0 | L2 |
| S43 | Cloud computing (AWS, Azure, GCP) | E | 25 | 30 | 15 | 70 | 2.9 | L2 |
| S44 | Model serving & inference | E | 12 | 18 | 15 | 45 | 1.9 | L3 |
| S45 | Model optimization & quantization | R | 10 | 15 | 5 | 30 | 1.2 | L2 |
| S46 | MLOps & LLMOps | E | 15 | 25 | 20 | 60 | 2.5 | L2 |
| S47 | Monitoring & observability | E | 8 | 12 | 5 | 25 | 1.0 | L2 |
| S48 | AI security & responsible AI | E | 12 | 10 | 3 | 25 | 1.0 | L2 |
| S49 | System design for AI | E | 15 | 15 | 5 | 35 | 1.5 | L2 |
| **P8** | **Phase 8 — Advanced & research** |  | **100** | **95** | **95** | **290** | **12.1** |  |
| S50 | Reinforcement learning | R | 30 | 30 | 20 | 80 | 3.3 | L2 |
| S51 | Distributed training & GPU computing | R | 20 | 25 | 15 | 60 | 2.5 | L2 |
| S52 | Research track (section 9) | R | 30 | 30 | 60 | 120 | 5.0 | L2 |
| S53 | Emerging AI (ongoing) | O | 20 | 10 | 0 | 30 | 1.2 | L1 |
| **P9** | **Phase 9 — Capstone & jobs** |  | **15** | **25** | **120** | **160** | **6.7** |  |
| S54 | Production capstones | E | 0 | 0 | 120 | 120 | 5.0 | L3 |
| S55 | Interview & portfolio prep | E | 15 | 25 | 0 | 40 | 1.7 | L2 |
|  | **All subjects** |  | **868** | **1,162** | **725** | **2,755** | **115** |  |

### Understand vs implement vs independent

The three proficiency levels from the intro take very different amounts of time:

- **L1 Understand** needs roughly the theory hours alone. Example: S30 Transformers, 20 h, and you can explain attention.
- **L2 Implement** needs theory + practice. Example: S30, 45 h, and you have coded a GPT with the video beside you.
- **L3 Independent** needs the full total, *plus* reusing the skill in later projects. Example: S30 reaches true L3 only after P7 and P8 use Transformers in new ways. The "Proficiency after" column is the level the subject alone gets you to. Later projects raise it.

### Topic-level estimates

Inside a subject, split its total like this: each \[E\] topic gets an equal share, and each \[R\] topic gets half an \[E\] share. \[O\] topics are outside the estimate. For example, S5 Python beginner has 9 \[E\] topics and 85 h, so about 9.5 h per topic. Topics that are traps for beginners need about 1.5× a share: comprehensions and scope in S5, eigenvalues and SVD in S9, Bayes and MLE in S11, backprop in S26, attention shapes in S30, and Docker networking in section 7.

Some topics carry more weight than an equal split. These breakdowns are the ones to plan around:

| Subject | Topic | Hours |
| --- | --- | --- |
| S9 Linear algebra | Vectors & dot products | 8 |
| S9 | Matrices as transformations, multiplication, shapes | 12 |
| S9 | Systems, rank, basis, span | 10 |
| S9 | Determinants | 4 |
| S9 | Eigenvalues & eigenvectors | 12 |
| S9 | SVD | 10 |
| S9 | Orthogonality, QR | 6 |
| S9 | Positive definite, covariance, tensors & einsum \[R\] | 8 |
| S26 NN foundations | Perceptron → MLP, activations, losses | 10 |
| S26 | Backprop + micrograd from scratch | 14 |
| S26 | Optimizers & LR schedules | 8 |
| S26 | Initialization, normalization, regularization | 10 |
| S26 | Training diagnostics & mixed precision | 8 |
| S30 Transformers | Attention, multi-head, masking | 14 |
| S30 | Positional encodings, the full block, model families | 10 |
| S30 | Build GPT from scratch (nanoGPT) | 24 |
| S30 | KV cache, complexity, efficient variants \[R\] | 12 |
| S36 RAG | Pipeline, parsing, chunking | 12 |
| S36 | Vector search, indexes, vector databases | 14 |
| S36 | Hybrid search, reranking, query rewriting | 12 |
| S36 | Generation with citations | 6 |
| S36 | RAG evaluation | 10 |
| S36 | Advanced patterns & operations \[R\] | 6 |
| S37 Agents | Workflow patterns & the agent loop | 10 |
| S37 | Tool design, memory, planning | 12 |
| S37 | Agent from scratch, then LangGraph | 14 |
| S37 | MCP server | 6 |
| S37 | Guardrails, human-in-the-loop, agent evaluation | 13 |

### Overall duration by daily study time

These figures assume 6 study days a week, plus one consolidation week (revision, assessment, buffer for college exams) after every 5 learning weeks.

| Daily study | Hours per week | Core path (2,172 h) | Full program (2,755 h) |
| --- | --- | --- | --- |
| 2 h | 12 | 217 weeks ≈ 4.2 years | 276 weeks ≈ 5.3 years |
| 3 h | 18 | 145 weeks ≈ 2.8 years | 184 weeks ≈ 3.5 years |
| 4 h | 24 | 109 weeks ≈ 2.1 years | 138 weeks ≈ 2.7 years |
| 6 h | 36 | 72 weeks ≈ 1.4 years | 92 weeks ≈ 1.8 years |

If your degree covers math, DSA, operating systems, networks or databases, those hours (up to about 500) overlap with college work. Deduct them once you pass the mastery checks. At 2 h/day during a 4-year degree, the core path lines up with graduation, which is a realistic target.

## 5. Resource directory

Pick **one main resource per subject** (marked ★) and use the others to fill gaps. Collecting courses you never finish is the most common beginner trap. Everything is free unless it says *paid*. Levels: B = beginner, I = intermediate, A = advanced. YouTube links point to channels or playlists rather than single videos, because individual videos are often re-uploaded. Docker resources are in section 7, and research papers are in section 9.

### Phase 0 — Computing foundations

| Subject | Resource | Type | Level | What you'll learn and why it's recommended |
| --- | --- | --- | --- | --- |
| S1 | ★ [Harvard CS50x](https://cs50.harvard.edu/x/) | MOOC | B | The best free intro to computer science: memory, C, data structures, Python, SQL. Weeks 0–5 cover S1. |
| S1 | [Crash Course Computer Science](https://www.youtube.com/playlist?list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo) | YouTube | B | Short visual episodes on how CPUs, memory and operating systems work. |
| S1, S2 | ★ [The Missing Semester (MIT)](https://missing.csail.mit.edu/) | Lecture notes + videos | B | Shell, scripting, Vim, Git, debugging, profiling. Exactly the tools school never teaches. |
| S2 | [Linux Journey](https://linuxjourney.com/) | Interactive | B | Step-by-step Linux lessons, from the command line to processes and networking. |
| S2 | [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) | Game | B | Learn shell commands by solving 30+ levels of puzzles over SSH. |
| S2 | [The Linux Command Line (book)](https://linuxcommand.org/tlcl.php) | Book (free PDF) | B–I | The full reference for bash and shell scripting. |
| S2 | [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/) | Book (free) | I | Processes, memory and concurrency. Read it when S1 topic 4 or Docker internals needs depth. |
| S3 | ★ [Pro Git book](https://git-scm.com/book/en/v2) | Official docs | B–I | The official Git book. Chapters 1–3 are essential, and chapter 10 covers internals. |
| S3 | [Learn Git Branching](https://learngitbranching.js.org/) | Interactive | B–I | Visual puzzles for branching, rebasing and cherry-picking. |
| S3 | [GitHub Skills](https://skills.github.com/) | Interactive | B | Hands-on courses for pull requests, Actions and Pages, run inside GitHub. |
| S4 | [VS Code Python tutorial](https://code.visualstudio.com/docs/python/python-tutorial) | Official docs | B | Set up Python, debugging and environments in VS Code. |
| S4 | [uv documentation](https://docs.astral.sh/uv/) | Official docs | B | The modern fast Python package and project manager. |
| S4 | [Google Colab](https://colab.research.google.com/) / [Kaggle Notebooks](https://www.kaggle.com/code) | Platform | B | Free GPU notebooks for deep-learning practice. |

### Phase 1 — Programming and software engineering

| Subject | Resource | Type | Level | What you'll learn and why it's recommended |
| --- | --- | --- | --- | --- |
| S5 | ★ [Harvard CS50P](https://cs50.harvard.edu/python/) | MOOC | B | Python from zero with graded problem sets. Includes testing and OOP. |
| S5 | [Official Python tutorial](https://docs.python.org/3/tutorial/) | Official docs | B | The authoritative tour of the language. Use it as a reference alongside CS50P. |
| S5 | [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/) | Book (free online) | B | Practical scripts for files, web and spreadsheets. Great for motivation. |
| S5–S7 | [Corey Schafer (YouTube)](https://www.youtube.com/@coreyms) | YouTube | B–I | Clear deep-dives on OOP, decorators, generators and logging. |
| S5–S7 | [Real Python](https://realpython.com/) | Articles | B–A | Tutorials on almost every Python topic. Some content is *paid*. |
| S5, S12 | [Exercism Python track](https://exercism.org/tracks/python) | Interactive | B–I | 140+ exercises with free human mentoring. |
| S6–S7 | [Python Data Model reference](https://docs.python.org/3/reference/datamodel.html) | Official docs | I–A | The official explanation of dunder methods, descriptors and more. |
| S7 | *Fluent Python*, 2nd ed. (Luciano Ramalho, O'Reilly) | Book (*paid*) | A | The best book on idiomatic, advanced Python. Worth buying. |
| S7 | [asyncio documentation](https://docs.python.org/3/library/asyncio.html) | Official docs | I–A | Event loops, tasks and concurrency primitives. |
| S7 | [Python Packaging User Guide](https://packaging.python.org/) | Official docs | I | pyproject.toml, building and publishing packages. |
| S8 | [pytest documentation](https://docs.pytest.org/) | Official docs | B–I | Fixtures, parametrize, plugins. |
| S8 | [Refactoring.Guru: design patterns](https://refactoring.guru/design-patterns) | Articles | I | Illustrated explanations of every classic pattern. |
| S8 | [Google engineering practices](https://google.github.io/eng-practices/) | Guide | I | How Google does code review, from both the author's and reviewer's side. |
| S8 | [Software Engineering at Google (book)](https://abseil.io/resources/swe-book) | Book (free online) | I–A | Testing, code review, documentation and scale. |
| S8 | [The Twelve-Factor App](https://12factor.net/) | Guide | I | Principles for config, logs and deployable services. |

### Phase 2 — Mathematics

| Subject | Resource | Type | Level | What you'll learn and why it's recommended |
| --- | --- | --- | --- | --- |
| S9 | ★ [3Blue1Brown: Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | YouTube | B | Geometric intuition for vectors, matrices, determinants and eigenvectors. Watch it first. |
| S9 | ★ [MIT 18.06 Linear Algebra (Gilbert Strang)](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) | University course | B–I | The classic full course, with problem sets. Pair it with the 3B1B playlist. |
| S9–S11 | ★ [Mathematics for Machine Learning (book)](https://mml-book.github.io/) | Book (free PDF) | I | Linear algebra, calculus and probability, written specifically for ML. |
| S9–S11 | [Khan Academy Math](https://www.khanacademy.org/math) | Interactive | B | Fill gaps in algebra, precalculus, calculus and statistics. |
| S9–S11 | [Mathematics for ML & Data Science (DeepLearning.AI)](https://www.coursera.org/specializations/mathematics-for-machine-learning-and-data-science) | MOOC (free audit) | B | Beginner-friendly, Python-based math specialization. |
| S10 | ★ [3Blue1Brown: Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) | YouTube | B | Derivatives, the chain rule and integrals, visually. |
| S10 | [MIT 18.01 Single Variable Calculus](https://ocw.mit.edu/courses/18-01sc-single-variable-calculus-fall-2010/) | University course | B | Full calculus course with exercises. |
| S10 | [The Matrix Calculus You Need for Deep Learning](https://explained.ai/matrix-calculus/) | Article | I | Jacobians and gradients of vector functions, worked through for neural networks. |
| S11 | ★ [StatQuest with Josh Starmer](https://www.youtube.com/@statquest) | YouTube | B | Statistics and ML concepts explained simply: p-values, distributions, MLE. |
| S11 | [Harvard Stat 110: Probability](https://stat110.hsites.harvard.edu/) | University course | I | Joe Blitzstein's famous probability course: lecture videos, problems and a free textbook. |
| S11 | [Seeing Theory (Brown University)](https://seeing-theory.brown.edu/) | Interactive | B | Visual, interactive probability and statistics. |
| S11 | [An Introduction to Statistical Learning (ISLP)](https://www.statlearning.com/) | Book (free PDF) | I | Statistics bridged to ML, with Python labs. Also the main S20 book. |

### Phase 3 — DSA, data and systems

| Subject | Resource | Type | Level | What you'll learn and why it's recommended |
| --- | --- | --- | --- | --- |
| S12 | ★ [NeetCode roadmap](https://neetcode.io/roadmap) | Interactive + YouTube | B–I | The NeetCode 150 problems, grouped by pattern, each with a video solution. |
| S12 | [LeetCode](https://leetcode.com/) | Practice platform | B–A | Where you practise. Aim for 75 problems in Phase 3 and 150 by Phase 9. |
| S12 | [Abdul Bari (YouTube)](https://www.youtube.com/@abdul_bari) | YouTube | B–I | Clear algorithm lectures, popular with Indian students. |
| S12 | [MIT 6.006 Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/) | University course | I | Rigorous algorithms course with problem sets. |
| S12 | [VisuAlgo](https://visualgo.net/) | Interactive | B | Animated sorting, trees and graph algorithms. |
| S13 | ★ [Python for Data Analysis, 3rd ed.](https://wesmckinney.com/book/) | Book (free online) | B–I | Written by the creator of pandas. NumPy, pandas, cleaning and plotting. |
| S13 | [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) | Book (free online) | B–I | NumPy, pandas, Matplotlib and scikit-learn, with notebooks. |
| S13 | [Kaggle Learn](https://www.kaggle.com/learn) | Interactive | B | Short hands-on courses: pandas, data visualization, data cleaning, intro ML. |
| S13 | [NumPy](https://numpy.org/doc/stable/), [pandas](https://pandas.pydata.org/docs/), [Matplotlib](https://matplotlib.org/stable/), [Seaborn](https://seaborn.pydata.org/), [Polars](https://docs.pola.rs/) | Official docs | B–I | User guides and API references. Read each library's "getting started" guide. |
| S14 | ★ [SQLBolt](https://sqlbolt.com/) | Interactive | B | Learn SQL in the browser in a few evenings. |
| S14 | [PostgreSQL tutorial](https://www.postgresql.org/docs/current/tutorial.html) | Official docs | B–I | The official Postgres tutorial and reference. |
| S14 | [Use The Index, Luke](https://use-the-index-luke.com/) | Book (free online) | I | How indexes and query plans really work. |
| S14 | [CMU 15-445 Database Systems](https://15445.courses.cs.cmu.edu/) | University course | A | Database internals. \[O\] for depth. |
| S15 | [MongoDB University](https://learn.mongodb.com/) | MOOC | B | Official free MongoDB courses. |
| S15 | [Redis documentation](https://redis.io/docs/latest/) | Official docs | B–I | Data types, caching patterns, streams. |
| S16 | ★ [Data Engineering Zoomcamp (DataTalksClub)](https://github.com/DataTalksClub/data-engineering-zoomcamp) | MOOC + GitHub | B–I | Free course: Docker, Postgres, orchestration, warehouses, Spark, Kafka. |
| S16 | *Designing Data-Intensive Applications* (Martin Kleppmann, O'Reilly) | Book (*paid*) | I–A | The best book on data systems: storage, replication, streaming. Used again in S49. |
| S17 | [Computer Networking: A Top-Down Approach — author resources](https://gaia.cs.umass.edu/kurose_ross/index.php) | Lectures + labs | I | Kurose & Ross's free lecture videos and Wireshark labs. |
| S17 | [Cloudflare Learning Center](https://www.cloudflare.com/learning/) | Articles | B | Short, clear articles on DNS, TLS, CDNs and DDoS. |
| S17, S18 | [MDN: HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP) | Official docs | B–I | The reference for HTTP methods, headers and status codes. |
| S18 | ★ [FastAPI documentation and tutorial](https://fastapi.tiangolo.com/) | Official docs | B–I | One of the best framework tutorials anywhere. Covers Pydantic, dependencies and security. |
| S18 | [Pydantic](https://docs.pydantic.dev/) / [SQLAlchemy](https://docs.sqlalchemy.org/) | Official docs | I | Data validation, and the ORM for databases. |
| S18 | [OWASP API Security Top 10](https://owasp.org/API-Security/) | Guide | I | The most common API vulnerabilities and how to prevent them. |
| S18 | [Flask documentation](https://flask.palletsprojects.com/) | Official docs | B | For reading older codebases. |

### Phase 4 — Classical machine learning

| Subject | Resource | Type | Level | What you'll learn and why it's recommended |
| --- | --- | --- | --- | --- |
| S19–S21 | ★ [Machine Learning Specialization (Andrew Ng)](https://www.coursera.org/specializations/machine-learning-introduction) | MOOC (free audit) | B | The best-known beginner ML course: regression, classification, trees, clustering, recommenders. |
| S19–S24 | ★ [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html) | Official docs | B–I | Every classical algorithm with theory, examples and pitfalls. Excellent docs; read them like a book. |
| S19–S24 | [An Introduction to Statistical Learning (ISLP)](https://www.statlearning.com/) | Book (free PDF) | B–I | The standard intro textbook, with Python labs and free lecture videos. |
| S19–S24 | [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) | MOOC | B | Short, practical modules on core ML concepts, data and fairness. |
| S19–S24 | *Hands-On Machine Learning with Scikit-Learn and PyTorch* (Aurélien Géron, O'Reilly) + [notebooks](https://github.com/ageron/handson-ml3) | Book (*paid*) + GitHub | B–I | The most practical ML book. The notebooks are free; newer editions use PyTorch. |
| S19–S24 | [Stanford CS229 Machine Learning](https://cs229.stanford.edu/) | University course | I–A | Math-heavy theory: derivations of linear models, SVMs, EM, learning theory. |
| S20 | [XGBoost](https://xgboost.readthedocs.io/) / [LightGBM](https://lightgbm.readthedocs.io/) | Official docs | I | Parameters, tuning and the theory behind gradient boosting. |
| S20, S24 | [Kaggle competitions](https://www.kaggle.com/competitions) | Practice platform | B–A | Real datasets, plus public notebooks showing winning feature engineering. |
| S21 | [UMAP documentation](https://umap-learn.readthedocs.io/) | Official docs | I | How UMAP works and how to read embeddings plots without fooling yourself. |
| S22 | [scikit-learn: semi-supervised learning](https://scikit-learn.org/stable/modules/semi_supervised.html) | Official docs | I | Self-training and label propagation with examples. |
| S23 | [Feature Engineering and Selection (Kuhn & Johnson)](https://bookdown.org/max/FES/) | Book (free online) | I | A careful, practical treatment of encoding, interactions and selection. |
| S24 | [Optuna](https://optuna.org/) | Official docs | I | Bayesian hyperparameter optimization with pruning. |
| S24 | [Interpretable Machine Learning (Christoph Molnar)](https://christophm.github.io/interpretable-ml-book/) | Book (free online) | I | SHAP, LIME, partial dependence and permutation importance, with honest caveats. |
| S24 | [SHAP documentation](https://shap.readthedocs.io/) | Official docs | I | Explaining model predictions in practice. |
| S19–S24 | [Rules of Machine Learning (Google)](https://developers.google.com/machine-learning/guides/rules-of-ml) | Guide | I | 43 hard-won rules from production ML at Google. |

### Phase 5 — Deep learning

| Subject | Resource | Type | Level | What you'll learn and why it's recommended |
| --- | --- | --- | --- | --- |
| S26, S30, S33 | ★ [Neural Networks: Zero to Hero (Andrej Karpathy)](https://karpathy.ai/zero-to-hero.html) | YouTube course | B–I | Build micrograd, makemore and GPT from scratch, plus a tokenizer video. The single most valuable free DL resource. |
| S26 | [3Blue1Brown: Neural Networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) | YouTube | B | Visual intuition for neurons, gradient descent, backprop and transformers. |
| S26–S31 | ★ [Dive into Deep Learning (d2l.ai)](https://d2l.ai/) | Book (free online) | I | Interactive textbook with runnable PyTorch code for every chapter. |
| S26–S32 | [Understanding Deep Learning (Simon Prince)](https://udlbook.github.io/udlbook/) | Book (free PDF) | I–A | A modern, clearly illustrated textbook, including transformers and diffusion. |
| S26–S32 | [Deep Learning (Goodfellow, Bengio, Courville)](https://www.deeplearningbook.org/) | Book (free online) | A | The classic theoretical reference. |
| S26–S28 | [Practical Deep Learning for Coders (fast.ai)](https://course.fast.ai/) | MOOC | B–I | Top-down, build-first course. Great if you learn better by doing before theory. |
| S26–S31 | [Deep Learning Specialization (DeepLearning.AI)](https://www.coursera.org/specializations/deep-learning) | MOOC (free audit) | B–I | Andrew Ng's structured course: NNs, tuning, CNNs, sequence models. |
| S26–S30 | [MIT 6.S191 Introduction to Deep Learning](http://introtodeeplearning.com/) | University course | B–I | A fast-paced lecture series with labs, updated yearly. |
| S27 | ★ [PyTorch tutorials](https://pytorch.org/tutorials/) | Official docs | B–I | Start with "Learn the Basics". Includes DDP, profiling and torch.compile tutorials. |
| S27 | [TensorFlow tutorials](https://www.tensorflow.org/tutorials) / [Keras](https://keras.io/) | Official docs | B | Enough to read and run TF/Keras code. |
| S28 | ★ [Stanford CS231n: Deep Learning for Computer Vision](https://cs231n.stanford.edu/) | University course | I | The classic CNN course: lecture notes and assignments where you implement layers yourself. |
| S28 | [torchvision](https://pytorch.org/vision/stable/index.html) / [timm](https://huggingface.co/docs/timm/index) | Official docs | I | Pretrained vision models, transforms, detection and segmentation models. |
| S28 | [OpenCV documentation](https://docs.opencv.org/4.x/) | Official docs | B–I | Image processing basics and tutorials. |
| S28 | [Ultralytics YOLO docs](https://docs.ultralytics.com/) | Official docs | B–I | Train and deploy YOLO detectors quickly. Note: the AGPL licence matters for commercial use. |
| S28 | [Hugging Face Community Computer Vision Course](https://huggingface.co/learn) | MOOC | I | Modern vision, including ViTs, multimodal models and generative vision. |
| S29 | [Understanding LSTM Networks (Chris Olah)](https://colah.github.io/posts/2015-08-Understanding-LSTMs/) | Article | B–I | The famous visual explanation of LSTM gates. |
| S30 | ★ [The Illustrated Transformer (Jay Alammar)](https://jalammar.github.io/illustrated-transformer/) | Article | B–I | The clearest visual walkthrough of the Transformer. Read it before coding. |
| S30 | [The Annotated Transformer (Harvard NLP)](https://nlp.seas.harvard.edu/annotated-transformer/) | Article + code | I | The original paper, line by line, in PyTorch. |
| S30 | [nanoGPT (Karpathy)](https://github.com/karpathy/nanoGPT) | GitHub | I | A minimal GPT training codebase to read, run and modify. |
| S30, S33 | [Build a Large Language Model (From Scratch) — code](https://github.com/rasbt/LLMs-from-scratch) | GitHub + book (*paid*) | I | Sebastian Raschka's step-by-step LLM build: tokenizer, attention, pretraining, fine-tuning. |
| S31 | ★ [Stanford CS224n: NLP with Deep Learning](https://web.stanford.edu/class/cs224n/) | University course | I | Word vectors through transformers and LLMs; lecture videos are on YouTube. |
| S31 | [Speech and Language Processing (Jurafsky & Martin)](https://web.stanford.edu/~jurafsky/slp3/) | Book (free draft) | I | The standard NLP textbook, kept up to date with LLM chapters. |
| S31 | [spaCy usage docs](https://spacy.io/usage) | Official docs | B–I | Industrial NLP pipelines: tokenization, NER, rule-based matching. |
| S31, S33–S35 | ★ [Hugging Face LLM Course](https://huggingface.co/learn/llm-course/chapter1/1) | MOOC | B–I | Transformers, Datasets and Tokenizers libraries; fine-tuning; newer chapters on LLM training and reasoning. |
| S32 | [Hugging Face Diffusion Models Course](https://huggingface.co/learn) + [diffusers docs](https://huggingface.co/docs/diffusers/index) | MOOC + docs | I | Train and use diffusion models with the diffusers library. |
| S32 | [What are Diffusion Models? (Lilian Weng)](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/) | Article | A | The maths of DDPM and score-based models, clearly derived. |

### Phase 6 — Generative AI and LLMs

| Subject | Resource | Type | Level | What you'll learn and why it's recommended |
| --- | --- | --- | --- | --- |
| S33 | Karpathy's tokenizer and "Let's build GPT" lectures ([Zero to Hero](https://karpathy.ai/zero-to-hero.html)) + his talks on [his YouTube channel](https://www.youtube.com/@AndrejKarpathy) | YouTube | B–I | Build a BPE tokenizer, plus his general-audience explanations of how LLMs are trained and used. |
| S33 | [Sentence Transformers documentation](https://sbert.net/) | Official docs | I | Computing, comparing and fine-tuning text embeddings. |
| S33 | [MTEB leaderboard](https://huggingface.co/spaces/mteb/leaderboard) | Benchmark | I | Compare embedding models by task, language and size. |
| S33–S37 | [Lilian Weng's blog](https://lilianweng.github.io/) | Blog | I–A | Deep, well-referenced posts on prompting, agents, hallucination and RLHF. |
| S34 | ★ [Claude prompt engineering guide](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview) | Official docs | B–I | Clear, structured prompting techniques that transfer to any model. |
| S34 | [Anthropic courses (GitHub)](https://github.com/anthropics/courses) | Interactive notebooks | B–I | Free hands-on courses: API fundamentals, prompt engineering, tool use. |
| S34 | [OpenAI Cookbook](https://cookbook.openai.com/) | Examples | B–I | Practical recipes: structured output, function calling, embeddings, evals. |
| S34 | [Prompt Engineering Guide](https://www.promptingguide.ai/) | Guide | B–I | A catalogue of prompting techniques, with links to the papers behind them. |
| S34 | [DSPy](https://dspy.ai/) | Official docs | I–A | Programming (and automatically optimizing) LLM pipelines instead of hand-writing prompts. |
| S34, S44 | [Ollama](https://ollama.com/) | Tool | B | Run open models locally with one command. Ideal for free practice. |
| S35 | ★ [Hugging Face PEFT](https://huggingface.co/docs/peft/index) + [TRL](https://huggingface.co/docs/trl/index) | Official docs | I | LoRA/QLoRA, SFT and DPO trainers. These are the standard open-source fine-tuning stack. |
| S35 | [Unsloth documentation](https://docs.unsloth.ai/) | Official docs | I | Fast, memory-efficient fine-tuning with free Colab notebooks. |
| S35 | [Hugging Face smol course](https://huggingface.co/learn) | MOOC | I | A short, practical post-training course on small models. |
| S36 | ★ [DeepLearning.AI short courses](https://www.deeplearning.ai/short-courses/) | MOOC (free) | B–I | One-to-two-hour courses on RAG, vector databases, agents, evals and LangGraph, often taught by the tool's creators. |
| S36 | [Pinecone Learning Center](https://www.pinecone.io/learn/) | Articles | B–I | Excellent explanations of vector search, HNSW, product quantization and hybrid search. |
| S36 | [FAISS](https://faiss.ai/) / [Chroma](https://docs.trychroma.com/) / [Qdrant](https://qdrant.tech/documentation/) / [pgvector](https://github.com/pgvector/pgvector) | Official docs | I | Vector indexes and databases: start with Chroma, then Qdrant or pgvector. |
| S36 | [LlamaIndex documentation](https://docs.llamaindex.ai/) | Official docs | I | A data framework for RAG: loaders, indexes, query engines. |
| S36, S39 | [Ragas documentation](https://docs.ragas.io/) | Official docs | I | RAG evaluation metrics and synthetic test-set generation. |
| S36 | [Patterns for Building LLM-based Systems (Eugene Yan)](https://eugeneyan.com/writing/llm-patterns/) | Article | I | Evals, RAG, fine-tuning, caching and guardrails, all from a practitioner. |
| S37 | ★ [Building Effective Agents (Anthropic)](https://www.anthropic.com/engineering/building-effective-agents) | Article | I | The clearest guide to workflows vs agents, and when to use each pattern. |
| S37 | [Effective Context Engineering for AI Agents (Anthropic)](https://anthropic.com/engineering/effective-context-engineering-for-ai-agents) | Article | I | Managing what goes into an agent's context over long tasks. |
| S37, S38 | ★ [LangChain & LangGraph docs](https://docs.langchain.com/) + [LangChain Academy](https://academy.langchain.com/) | Official docs + MOOC | I | Stateful agent graphs, persistence, human-in-the-loop, multi-agent patterns. The academy's LangGraph intro course is free. |
| S37 | [Hugging Face Agents Course](https://huggingface.co/learn) | MOOC | B–I | Agent fundamentals with smolagents, LlamaIndex and LangGraph, with certification. |
| S37 | [Model Context Protocol](https://modelcontextprotocol.io/) + [Hugging Face MCP Course](https://huggingface.co/learn) | Spec + MOOC | I | Build and connect MCP servers and clients. |
| S37 | [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/) / [Claude Agent SDK](https://code.claude.com/docs/en/agent-sdk/overview) | Official docs | I | Two vendor agent frameworks. Learn one after building an agent without a framework. |
| S38 | [CrewAI](https://docs.crewai.com/) / [AutoGen](https://microsoft.github.io/autogen/) | Official docs | I | Multi-agent frameworks to compare against LangGraph. |
| S39 | [Your AI Product Needs Evals (Hamel Husain)](https://hamel.dev/blog/posts/evals/) | Article | I | The practical case for, and method of, building evals around error analysis. |
| S39 | [promptfoo](https://www.promptfoo.dev/docs/intro/) / [DeepEval](https://deepeval.com/docs/getting-started) | Official docs | I | Test-suite style LLM evaluation, including red-teaming. |
| S39 | [EleutherAI lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) | GitHub | A | The standard tool for running academic benchmarks on models. |

### Phase 7 — Production AI engineering

| Subject | Resource | Type | Level | What you'll learn and why it's recommended |
| --- | --- | --- | --- | --- |
| S40 | See section 7 |  |  | The full Docker curriculum has its own resources. |
| S41 | ★ [Kubernetes official tutorials](https://kubernetes.io/docs/tutorials/) + [concepts](https://kubernetes.io/docs/concepts/) | Official docs | B–I | Learn by deploying, scaling and updating apps on a local cluster. |
| S41 | [TechWorld with Nana (YouTube)](https://www.youtube.com/@TechWorldwithNana) | YouTube | B | Beginner-friendly full courses on Docker, Kubernetes, Helm and DevOps. |
| S41 | [kind](https://kind.sigs.k8s.io/) / [minikube](https://minikube.sigs.k8s.io/docs/) | Tools | B | Free local Kubernetes clusters for practice. |
| S41 | [Helm documentation](https://helm.sh/docs/) | Official docs | I | Packaging and templating Kubernetes apps. |
| S41 | [KServe](https://github.com/kserve/kserve) / [Kubeflow](https://www.kubeflow.org/docs/) | Official docs | A | Model serving and ML pipelines on Kubernetes. |
| S42 | ★ [GitHub Actions documentation](https://docs.github.com/en/actions) | Official docs | B–I | Workflows, secrets, caching, matrix builds and Docker publishing. |
| S43 | ★ [AWS Skill Builder](https://skillbuilder.aws/) + [AWS Free Tier](https://aws.amazon.com/free/) | MOOC + platform | B–I | Official free AWS training, then hands-on with free-tier limits. **Set a billing alarm first.** |
| S43 | [Microsoft Learn](https://learn.microsoft.com/en-us/training/) / [Google Cloud Skills Boost](https://www.cloudskillsboost.google/) | MOOC | B–I | Official free training paths for Azure and GCP. |
| S43 | [Amazon SageMaker](https://docs.aws.amazon.com/sagemaker/) / [Amazon Bedrock](https://docs.aws.amazon.com/bedrock/) / [Azure Machine Learning](https://learn.microsoft.com/en-us/azure/machine-learning/) / [Vertex AI](https://cloud.google.com/vertex-ai/docs) | Official docs | I | Managed ML training, endpoints, pipelines and LLM APIs. |
| S43 | [Terraform tutorials (HashiCorp)](https://developer.hashicorp.com/terraform/tutorials) | Official docs | B–I | Infrastructure as Code from first resource to modules. |
| S44 | ★ [vLLM documentation](https://docs.vllm.ai/) | Official docs | I | The most widely used open-source LLM serving engine. |
| S44 | [NVIDIA Triton Inference Server](https://github.com/triton-inference-server/server) | GitHub + docs | A | Multi-framework, multi-model GPU serving with dynamic batching. |
| S44 | [llama.cpp](https://github.com/ggml-org/llama.cpp) / [SGLang](https://github.com/sgl-project/sglang) | GitHub | I–A | CPU/edge inference with GGUF models; a fast alternative LLM serving engine. |
| S44 | [BentoML](https://docs.bentoml.com/) / [Ray Serve](https://docs.ray.io/en/latest/serve/index.html) | Official docs | I | Python-first model serving frameworks. |
| S45 | [Transformers quantization guide](https://huggingface.co/docs/transformers/main/en/quantization/overview) | Official docs | I | Compares bitsandbytes, GPTQ, AWQ and other methods, with usage examples. |
| S45 | [ONNX Runtime](https://onnxruntime.ai/docs/) / [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) | Official docs | A | Optimized runtimes for CPU and NVIDIA GPU inference. |
| S46 | ★ [Made With ML (Goku Mohandas)](https://madewithml.com/) | Course | I | Best free end-to-end MLOps course: design, data, training, testing, serving, CI/CD. |
| S46 | ★ [MLOps Zoomcamp (DataTalksClub)](https://github.com/DataTalksClub/mlops-zoomcamp) | MOOC + GitHub | I | Experiment tracking, orchestration, deployment and monitoring, with a final project. |
| S46 | [MLflow](https://mlflow.org/docs/latest/) / [Weights & Biases](https://docs.wandb.ai/) / [DVC](https://dvc.org/doc) | Official docs | I | Experiment tracking, model registry and data versioning. |
| S46 | [MLOps: continuous delivery and automation pipelines in ML (Google Cloud)](https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning) | Architecture guide | I | The MLOps level 0/1/2 maturity model. |
| S46, S49 | *Designing Machine Learning Systems* and *AI Engineering* (Chip Huyen, O'Reilly) | Books (*paid*) | I–A | The two best books on production ML and production LLM systems. Highly recommended. |
| S46, S49 | [Full Stack Deep Learning](https://fullstackdeeplearning.com/) | Course | I | Lectures on building and shipping ML products, including an LLM bootcamp. |
| S47 | [Prometheus](https://prometheus.io/docs/) / [Grafana](https://grafana.com/docs/) / [OpenTelemetry](https://opentelemetry.io/docs/) | Official docs | I | Metrics, dashboards and tracing. |
| S47 | [Google SRE books](https://sre.google/books/) | Books (free online) | I | SLOs, error budgets, monitoring and incident response, from the people who invented SRE. |
| S47 | [Evidently](https://docs.evidentlyai.com/) / [Langfuse](https://langfuse.com/docs) / [Arize Phoenix](https://github.com/Arize-ai/phoenix) | Official docs | I | Drift monitoring for ML; tracing and evaluation for LLM apps. |
| S48 | ★ [OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/) | Guide | I | The standard list of LLM app risks and mitigations. |
| S48 | [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) | Framework | I | How organizations govern AI risk. |
| S48 | [MITRE ATLAS](https://atlas.mitre.org/) | Knowledge base | A | Real-world adversarial tactics against AI systems. |
| S48 | [Fairlearn](https://fairlearn.org/) | Official docs | I | Fairness metrics and mitigation, with good conceptual guides. |
| S49 | ★ [System Design Primer](https://github.com/donnemartin/system-design-primer) | GitHub | I | Scalability fundamentals and practice problems. |
| S49 | *Machine Learning System Design Interview* (Ali Aminian & Alex Xu, ByteByteGo) | Book (*paid*) | I | Worked ML system design cases in interview format. |

### Phase 8 — Advanced and research

| Subject | Resource | Type | Level | What you'll learn and why it's recommended |
| --- | --- | --- | --- | --- |
| S50 | ★ [Reinforcement Learning: An Introduction (Sutton & Barto)](http://incompleteideas.net/book/the-book-2nd.html) | Book (free PDF) | I | The foundational RL textbook. |
| S50 | [David Silver's RL course (UCL/DeepMind)](https://www.davidsilver.uk/teaching/) | University course | I | Classic lectures matching Sutton & Barto. |
| S50 | [Hugging Face Deep RL Course](https://huggingface.co/learn/deep-rl-course/) | MOOC | B–I | Hands-on deep RL: Q-learning, DQN, policy gradients, PPO. |
| S50 | [OpenAI Spinning Up](https://spinningup.openai.com/) | Guide + code | I | A clear introduction to deep RL algorithms, with key papers. |
| S50 | [Gymnasium](https://gymnasium.farama.org/) / [Stable-Baselines3](https://stable-baselines3.readthedocs.io/) / [CleanRL](https://github.com/vwxyzjn/cleanrl) | Official docs + GitHub | I | Environments, reliable algorithm implementations, single-file reference code. |
| S51 | ★ [The Ultra-Scale Playbook (Hugging Face)](https://huggingface.co/spaces/nanotron/ultrascale-playbook) | Guide | A | Data, tensor, pipeline and context parallelism explained with experiments on up to thousands of GPUs. |
| S51 | [How to Scale Your Model (Google DeepMind)](https://jax-ml.github.io/scaling-book/) | Book (free online) | A | Roofline analysis and parallelism on TPUs and GPUs. |
| S51 | [Making Deep Learning Go Brrrr (Horace He)](https://horace.io/brrr_intro.html) | Article | I | Compute vs memory bandwidth vs overhead: the essential mental model for GPU performance. |
| S51 | [PyTorch DDP tutorial](https://pytorch.org/tutorials/intermediate/ddp_tutorial.html) / [DeepSpeed](https://www.deepspeed.ai/) / [Accelerate](https://huggingface.co/docs/accelerate/index) | Official docs | I–A | Practical multi-GPU training. |
| S51 | [GPU MODE lectures](https://github.com/gpu-mode/lectures) | YouTube + GitHub | A | Community lectures on CUDA, Triton and kernel optimization. |
| S51 | [CUDA C++ Programming Guide](https://docs.nvidia.com/cuda/cuda-c-programming-guide/) / [Triton language](https://triton-lang.org/) | Official docs | A | Writing GPU kernels. |
| S51 | *Programming Massively Parallel Processors* (Hwu, Kirk, El Hajj) | Book (*paid*) | A | The standard CUDA textbook. |
| S52 | See section 9 |  |  | Paper-reading method, reading list and tools. |

### Phase 9 and staying current

| Purpose | Resource | Type | What it gives you |
| --- | --- | --- | --- |
| S55 | [NeetCode 150](https://neetcode.io/practice) | Practice | The standard interview problem set. |
| S55 | [Hugging Face Spaces](https://huggingface.co/spaces) | Platform | Free hosting for Gradio and Streamlit demos for your portfolio. |
| News | [Hugging Face Daily Papers](https://huggingface.co/papers) | Paper feed | Community-voted new papers each day. |
| News | [The Batch (DeepLearning.AI)](https://www.deeplearning.ai/the-batch/) | Newsletter | A weekly, balanced summary of AI news. |
| News | [Simon Willison's blog](https://simonwillison.net/) | Blog | Hands-on, sceptical coverage of LLM tools and prompt-injection security. |
| News | [Chip Huyen's blog](https://huyenchip.com/blog/) | Blog | In-depth essays on AI engineering and production systems. |
| News | [Sebastian Raschka's Ahead of AI](https://magazine.sebastianraschka.com/) | Newsletter | Clear explanations of new LLM research and architectures. |
| Depth | [Yannic Kilcher](https://www.youtube.com/@YannicKilcher) / [Umar Jamil](https://www.youtube.com/@umarjamilai) (YouTube) | YouTube | Paper walkthroughs; from-scratch implementations of LLaMA, diffusion and more. |

## 6. Tools and experimentation directory

You need about **20 essential tools**. Learn them well, and read about the alternatives only when a job or project asks for them. **Bold** tools are essential; plain ones are alternatives. Each row gives one experiment that teaches the tool's core idea in under two hours.

### Programming and environment

| Tool | What it does / when to use it | Features to learn | Experiment to perform | Alternatives and differences |
| --- | --- | --- | --- | --- |
| **Python 3.12+** | The main AI language, used everywhere | Typing, venvs, the standard library | Write the same script in 3 Python versions with uv and note what breaks | None for AI. Learn some Bash; Rust or C++ only for performance work later |
| **VS Code** | Editor for scripts, notebooks and remote machines | Debugger, Remote-SSH/WSL, Jupyter, Git panel | Set a breakpoint inside a PyTorch training loop and inspect tensor shapes | PyCharm (heavier, strong refactoring); Cursor or other AI-first editors (VS Code-based) |
| **Jupyter** | Exploration, EDA, teaching | Kernels, magics (%timeit), widgets | Time a Python loop vs a NumPy version with %timeit | JupyterLab (full IDE), Marimo (reactive notebooks stored as .py files) |
| **uv** | Fast package and project manager | uv init, add, lock, run; Python version management | Recreate a project from its lock file on a second machine | pip + venv (built-in, slower), Poetry (similar but slower), Conda (needed for non-Python binaries) |
| **Git + GitHub** | Version control and collaboration | Branches, PRs, Actions, Issues | Make a merge conflict on purpose and resolve it | GitLab, Bitbucket (same Git underneath) |
| **Ruff** + pre-commit | Linting and formatting in one fast tool | Rule sets, auto-fix, pre-commit hooks | Add pre-commit to a repo and watch it block a bad commit | Black + Flake8 + isort (older, three separate tools) |
| **pytest** | Testing | Fixtures, parametrize, mocking | Write a test that catches a shape bug in a model's forward() | unittest (built-in, more verbose) |

### Data science and classical ML

| Tool | What it does / when to use it | Features to learn | Experiment to perform | Alternatives and differences |
| --- | --- | --- | --- | --- |
| **NumPy** | N-dimensional arrays; the base of all numeric Python | Broadcasting, vectorization, linalg | Implement linear regression with the normal equation, then with gradient descent | JAX (NumPy-like with autodiff and GPU support) |
| **pandas** | Tabular data wrangling | groupby, merge, pivot, time series | Clean a messy Kaggle dataset and document every fix | **Polars** (much faster, lazy queries; worth learning second), DuckDB (SQL on DataFrames and files) |
| **Matplotlib + Seaborn** | Static plots | Figure/axes API, statistical plots | Recreate one chart from a published paper | Plotly (interactive), Altair (declarative) |
| **scikit-learn** | Classical ML algorithms and pipelines | Pipeline, ColumnTransformer, CV, metrics | Show leakage: scale before vs after the split and compare test scores | statsmodels (statistical inference, p-values) |
| **XGBoost / LightGBM** | Gradient boosting for tabular data | Early stopping, categorical handling, feature importance | Beat a random forest on a tabular dataset and explain why with SHAP | CatBoost (best with many categorical features) |
| **Optuna** | Hyperparameter search | Samplers, pruning, dashboards | Tune LightGBM with 50 trials and plot parameter importance | Ray Tune (distributed), grid/random search |
| **Streamlit / Gradio** | Quick demo UIs | Layouts, state, file upload, chat components | Wrap a trained model in a web demo and host it on Hugging Face Spaces | Panel, simple HTML + FastAPI |

### Deep learning and LLM development

| Tool | What it does / when to use it | Features to learn | Experiment to perform | Alternatives and differences |
| --- | --- | --- | --- | --- |
| **PyTorch** | The main DL framework | Tensors, autograd, nn.Module, DataLoader, torch.compile, AMP | Train an MLP on MNIST, then switch to bf16 and compare speed and accuracy | TensorFlow/Keras (production at Google, mobile); JAX (research at Google/DeepMind, functional style) |
| **Hugging Face Transformers + Hub** | Pretrained models and a standard API | pipeline, AutoModel, AutoTokenizer, Trainer, generate() | Compare three sentiment models on the same 200 sentences | Model-specific repos; timm for vision |
| **HF Datasets, PEFT, TRL** | Data loading, LoRA, SFT/DPO training | map/filter, LoraConfig, SFTTrainer | QLoRA-tune a 1–3B model on a free Colab GPU | Unsloth (faster, less memory), Axolotl (config-driven), torchtune |
| **An LLM API** (OpenAI, Anthropic or Gemini) | Frontier models for apps | Messages, streaming, tools, structured output, caching | Build the same extractor on two providers and compare cost and accuracy | LiteLLM (one interface for 100+ providers) |
| **Ollama** | Run open models locally | pull, run, Modelfile, OpenAI-compatible API | Run a small Llama/Qwen model locally and point your app at it | llama.cpp (lower level, more control), LM Studio (GUI) |
| **Pydantic** | Data validation and structured LLM output | Models, validators, JSON schema | Force an LLM to return a valid invoice object and retry on failure | Instructor (Pydantic + retries for LLMs), marshmallow |
| **LangGraph** | Stateful agents and workflows | State, nodes, edges, checkpointers, interrupts | Add a human-approval step to a tool-calling agent | No framework (best for learning); LlamaIndex (RAG-first); CrewAI (role-based, simpler); vendor SDKs |
| LangChain | Integrations and simple chains | Chat models, tools, retrievers | Swap the LLM provider in a chain with one line | Direct SDK calls (fewer abstractions, easier to debug) |

### RAG and vector search

| Tool | What it does / when to use it | Features to learn | Experiment to perform | Alternatives and differences |
| --- | --- | --- | --- | --- |
| **sentence-transformers** | Embedding models | encode, similarity, fine-tuning | Plot recall@5 for three embedding models on your own questions | API embedding models (no GPU needed, cost per token) |
| **FAISS** | Vector-index library (in-process) | Flat, IVF, HNSW, PQ indexes | Measure the recall vs latency trade-off of HNSW vs a flat index on 1M vectors | hnswlib, Annoy, ScaNN |
| **Chroma** | Simple local vector database | Collections, metadata filters | Build a 100-document RAG prototype in an afternoon | LanceDB (embedded, columnar) |
| **Qdrant** or **pgvector** | Production vector search | Payload filters, hybrid search, HNSW tuning; SQL + vectors | Run hybrid (BM25 + dense) search and compare with dense only | Pinecone (fully managed), Weaviate, Milvus (large scale), Elasticsearch/OpenSearch (keyword-first) |
| Rerankers (cross-encoders) | Re-score the top candidates | Batch scoring, top-k cut-offs | Add a reranker and measure the change in MRR | Cohere Rerank and other APIs |
| **Ragas** / LLM judges | RAG evaluation | Faithfulness, context recall | Generate a test set from your docs and score two chunk sizes | DeepEval, TruLens, custom judges |

### Databases and backend

| Tool | What it does / when to use it | Features to learn | Experiment to perform | Alternatives and differences |
| --- | --- | --- | --- | --- |
| **PostgreSQL** | The default relational database | Indexes, EXPLAIN, JSONB, pgvector | Speed up a slow query 100× with an index and prove it with EXPLAIN ANALYZE | MySQL (similar), SQLite (file-based, great for prototypes) |
| **Redis** | Cache, queues, rate limiting | TTL, hashes, streams, pub/sub | Cache LLM responses by prompt hash and measure the saved cost | Memcached (cache only), Valkey (open-source Redis fork) |
| MongoDB | Document database | Collections, indexes, aggregation | Store chat sessions as documents and query them by user | Firestore, DynamoDB (managed key-value/document) |
| **FastAPI** | Python APIs | Pydantic models, dependencies, async, streaming | Stream LLM tokens to a browser over SSE | Flask (simpler, synchronous), Django (full framework), Litestar |

### Experiment tracking and MLOps

| Tool | What it does / when to use it | Features to learn | Experiment to perform | Alternatives and differences |
| --- | --- | --- | --- | --- |
| **MLflow** | Tracking, model registry, serving | Autologging, runs, registry, model signatures | Log 20 runs, compare them in the UI, register the best | **Weights & Biases** (hosted, nicer UI, free for personal use), Neptune, Comet |
| **DVC** | Data and model versioning with Git | dvc add, remotes, pipelines | Version a dataset, change it, and reproduce the old model exactly | lakeFS, Hugging Face Hub datasets, Git LFS |
| Prefect / **Airflow** | Pipeline orchestration | DAGs/flows, retries, schedules | Schedule a nightly retrain-and-evaluate flow | Dagster (asset-based), Kubeflow Pipelines (on Kubernetes), ZenML, Metaflow |
| **Langfuse** | LLM tracing, prompts, evals | Traces, sessions, scores, datasets | Trace a RAG app and find the slowest step | LangSmith (LangChain's hosted tool), Arize Phoenix (OpenTelemetry-native) |
| Evidently | Data and model drift monitoring | Reports, test suites | Simulate drift by shifting one feature and catch it | NannyML, WhyLabs |

### Containers, orchestration, cloud and serving

| Tool | What it does / when to use it | Features to learn | Experiment to perform | Alternatives and differences |
| --- | --- | --- | --- | --- |
| **Docker + Compose** | Package and run apps (section 7) | Dockerfile, layers, volumes, networks, Compose | Section 7 has 12 labs | Podman (daemonless, rootless, mostly CLI-compatible) |
| **Kubernetes** (kind/minikube locally) | Run containers at scale | Deployments, Services, probes, HPA, Helm | Deploy your model API with 3 replicas and kill a pod | Docker Swarm (simpler, rarely used), Nomad, managed PaaS (Cloud Run) |
| **GitHub Actions** | CI/CD | Workflows, matrices, caching, OIDC to the cloud | Block a merge when the eval score drops | GitLab CI, Jenkins, CircleCI |
| **AWS** (one cloud deeply) | Cloud infrastructure and managed AI | IAM, EC2, S3, ECR, EKS, SageMaker, Bedrock | Deploy a container to a managed service and tear it down with Terraform | Azure (strong in enterprises, Azure OpenAI), GCP (Vertex AI, TPUs, strong data tools) |
| **Terraform** | Infrastructure as Code | Providers, state, modules, plan/apply | Create and destroy an S3 bucket + IAM role from code | OpenTofu (open-source fork), Pulumi (IaC in Python), CloudFormation |
| **vLLM** | High-throughput LLM serving | OpenAI-compatible server, batching, quantized models, LoRA serving | Load-test vLLM vs a naive generate() loop on the same GPU | SGLang (very fast, structured generation), TGI, TensorRT-LLM (NVIDIA-optimized), Ollama/llama.cpp (local, CPU) |
| Triton Inference Server | Multi-framework GPU serving | Model repository, dynamic batching, ensembles | Serve an ONNX vision model with dynamic batching | TorchServe (limited maintenance), BentoML, Ray Serve, KServe |
| **Prometheus + Grafana** | Metrics and dashboards | Exporters, PromQL, alerts | Dashboard p95 latency and GPU utilization for your API | Datadog, New Relic (commercial, hosted) |
| **OpenTelemetry** | Vendor-neutral tracing and metrics | SDK instrumentation, collector, GenAI conventions | Trace one request across API → retriever → LLM | Vendor-specific agents |

### GPU compute (free and cheap options)

| Option | Best for | Limits and notes |
| --- | --- | --- |
| **Google Colab** (free tier) | Learning, small fine-tunes | Free GPUs with session limits; paid tiers add better GPUs |
| **Kaggle Notebooks** | Learning, competitions | Free weekly GPU quota; reliable for long-ish runs |
| Lightning AI Studios, Modal, RunPod, Lambda | Paid experiments when free tiers run out | Per-hour GPU rental; always stop instances when you finish |
| Your own GPU (if you have one) | Daily practice | 8–12 GB VRAM runs 7–8B models when quantized; install CUDA via the NVIDIA Container Toolkit (section 7) |

## 7. Docker — complete dedicated curriculum

Docker is 12 modules and **80 hours** (20 theory, 35 practice, 25 project). Do modules D1–D3 early, during Phase 3, so you can run PostgreSQL and Redis in containers. Do D4–D9 at the start of Phase 7, and D10–D12 alongside the AI subjects they serve. **Prerequisites for the whole track:** S2 Linux, S5–S6 Python, S17 networking topics 1–5.

### Module overview

| Module | Theory h | Practice h | Project h | Total h | When | Proficiency after |
| --- | --- | --- | --- | --- | --- | --- |
| D1 Containerization fundamentals | 2 | 1 | 0 | 3 | Phase 3 | L1 |
| D2 Architecture and internals | 2 | 2 | 0 | 4 | Phase 3 | L1 |
| D3 Images and the container lifecycle | 1 | 4 | 0 | 5 | Phase 3 | L2 |
| D4 Dockerfiles, image building, optimization, multi-stage builds | 3 | 5 | 1 | 9 | Phase 7 | L3 |
| D5 Storage and networking | 2 | 5 | 0 | 7 | Phase 7 | L2 |
| D6 Docker Compose, environment variables and secrets | 2 | 4 | 2 | 8 | Phase 7 | L3 |
| D7 Security and resource management | 2 | 3 | 0 | 5 | Phase 7 | L2 |
| D8 Registries, debugging and troubleshooting | 1 | 3 | 0 | 4 | Phase 7 | L2 |
| D9 Docker in CI/CD and the cloud | 1 | 2 | 3 | 6 | Phase 7 (with S42, S43) | L2 |
| D10 Docker for Python and ML development | 1 | 2 | 4 | 7 | Phase 7 (or earlier, with Phase 5) | L3 |
| D11 GPU workloads and LLM inference | 2 | 3 | 4 | 9 | Phase 7 (with S44) | L2 |
| D12 Production AI applications and Kubernetes integration | 1 | 1 | 11 | 13 | Phase 7 (with S41, S46) | L3 |
| **Total** | **20** | **35** | **25** | **80** |  |  |

### D1 Containerization fundamentals (3 h) \[E\]

**Prerequisites:** S1, S2 basics.

- &#91;E\] The problem: "works on my machine", dependency conflicts, environment drift.
- &#91;E\] **Virtual machines vs containers:** a VM virtualizes hardware and runs a full guest OS (heavy, strong isolation). A container shares the host kernel and isolates processes (light, starts in milliseconds, weaker isolation).
- &#91;E\] Images vs containers (a class vs an object); Docker's role vs the wider container ecosystem.
- &#91;E\] Installing Docker: Docker Desktop (Windows/macOS) or Docker Engine (Linux); Docker on WSL2.
- &#91;R\] Container history: chroot, LXC, Docker (2013), the Open Container Initiative (OCI).

**Lab:** Run `docker run hello-world`, then `docker run -it ubuntu bash`. Inside the container, run `ps aux` and `hostname` and compare the output with the host. **Exercise:** Write one paragraph on why a 7 GB PyTorch environment is easier to share as an image than as setup instructions.

### D2 Docker architecture and internals (4 h) \[E\]

**Prerequisites:** D1, S1 topic 4 (OS concepts).

- &#91;E\] **Client–server architecture:** the docker CLI → REST API → the Docker daemon (dockerd) → containerd → runc.
- &#91;E\] **Docker Engine components** and the OCI image and runtime specifications.
- &#91;E\] **Linux namespaces** (pid, net, mnt, uts, ipc, user): what isolation each provides.
- &#91;E\] **Control groups (cgroups v2):** limiting CPU, memory and I/O.
- &#91;E\] **Union filesystems (overlay2):** read-only image layers + a thin writable container layer; copy-on-write.
- &#91;R\] How Docker Desktop runs a Linux VM on macOS and Windows.
- &#91;O\] Build a mini container from scratch in Go or Python with namespaces (Liz Rice's demo).

**Lab:** Run a container, find its process on the host with `ps`, then inspect `/proc/<pid>/ns`. Run `docker info` and find the storage driver and cgroup version. **Exercise:** Explain why a container can't see host processes but the host can see container processes.

### D3 Images and the container lifecycle (5 h) \[E\]

**Prerequisites:** D1.

- &#91;E\] **Image commands:** pull, images, tag, rmi, history, inspect; tags vs digests (sha256); why `latest` is dangerous.
- &#91;E\] **Image layers:** how each Dockerfile instruction creates a layer; layer sharing between images.
- &#91;E\] **Container lifecycle:** created → running → paused → stopped → removed; run, start, stop, kill, restart, rm, `--rm`.
- &#91;E\] **Running options:** `-d`, `-it`, `--name`, `-p host:container`, `-e`, `-v`, `--restart` policies.
- &#91;E\] **Inspecting:** ps, logs (`-f`), exec, top, stats, inspect, diff.
- &#91;E\] **Docker Hub:** official images, verified publishers, reading an image's page (tags, sizes, architectures).
- &#91;R\] Cleanup: `docker system df`, `docker system prune`, dangling images.

**Labs:** (1) Run PostgreSQL and Redis from official images, connect from Python and write data. (2) Stop and remove the Postgres container and note that the data is gone. That sets up D5. (3) Compare the sizes of `python:3.12`, `python:3.12-slim` and `python:3.12-alpine`.

### D4 Dockerfiles, image building, optimization and multi-stage builds (9 h) \[E\]

**Prerequisites:** D3, S7 topic 5 (packaging).

- &#91;E\] **Instructions:** FROM, RUN, COPY vs ADD, WORKDIR, ENV vs ARG, EXPOSE, USER, LABEL, VOLUME, HEALTHCHECK, SHELL; **CMD vs ENTRYPOINT** (exec form vs shell form; signals and PID 1).
- &#91;E\] **.dockerignore:** keep .git, datasets, .env and venvs out of the build context.
- &#91;E\] **The build cache:** instruction order matters. Copy dependency files first, install, then copy code.
- &#91;E\] **BuildKit features:** `RUN --mount=type=cache` for pip/uv caches, `--mount=type=secret`, `docker buildx`.
- &#91;E\] **Base image choice:** full vs slim vs alpine (musl libc can break Python wheels) vs distroless; pinning versions and digests.
- &#91;E\] **Multi-stage builds:** build tools in one stage, a slim runtime in the final stage. Typical savings are 50–80% of image size.
- &#91;E\] **Linting and inspecting:** Hadolint for Dockerfile mistakes; dive to explore layers.
- &#91;R\] Multi-platform builds (amd64 + arm64) with buildx, for Apple Silicon and Graviton.
- &#91;R\] `docker init` to generate starter Dockerfiles.

**Labs:** (1) Containerize a FastAPI app naively, measure the image size and rebuild time after a one-line code change. (2) Reorder for caching, then convert it to multi-stage with uv and a non-root user. Measure again. (3) Run Hadolint and fix every warning.

A production-style Dockerfile for a Python API (multi-stage, cached dependency install, non-root user, health check):

```dockerfile
# syntax=docker/dockerfile:1
FROM python:3.12-slim AS builder
COPY --from=ghcr.io/astral-sh/uv:latest /uv /usr/local/bin/uv
WORKDIR /app
ENV UV_COMPILE_BYTECODE=1 UV_LINK_MODE=copy
COPY pyproject.toml uv.lock ./
RUN --mount=type=cache,target=/root/.cache/uv uv sync --frozen --no-install-project --no-dev
COPY . .
RUN --mount=type=cache,target=/root/.cache/uv uv sync --frozen --no-dev

FROM python:3.12-slim
RUN useradd --create-home appuser
WORKDIR /app
COPY --from=builder --chown=appuser:appuser /app /app
ENV PATH="/app/.venv/bin:$PATH"
USER appuser
EXPOSE 8000
HEALTHCHECK CMD python -c "import urllib.request; urllib.request.urlopen('http://localhost:8000/health')" || exit 1
CMD ["uvicorn", "app.main:app", "--host", "0.0.0.0", "--port", "8000"]
```

### D5 Storage and networking (7 h) \[E\]

**Prerequisites:** D3, S17 topics 1–5.

- &#91;E\] **Storage types:** named volumes (managed by Docker; for databases and model caches), bind mounts (host folders; for live code during development), tmpfs (in memory; for scratch data).
- &#91;E\] **Volume operations:** create, ls, inspect, rm; backing up and restoring a volume; read-only mounts (`:ro`) for model weights.
- &#91;E\] **Network drivers:** bridge (default), user-defined bridge (with built-in DNS by container name), host, none; overlay (multi-host, concept).
- &#91;E\] **Port publishing:** `-p 8000:8000` vs `127.0.0.1:8000:8000`; EXPOSE is documentation only.
- &#91;E\] **Container-to-container communication:** service names as hostnames; why `localhost` inside a container means the container itself.
- &#91;R\] Inspecting networks; debugging with a toolbox container (curl, dig, nc), for example nicolaka/netshoot.

**Labs:** (1) Re-run the D3 Postgres lab with a named volume, delete the container, and confirm the data survives. (2) Put an API and Postgres on a user-defined network and connect by name. (3) Break it on purpose by using `localhost` instead of the service name, read the error, and fix it.

### D6 Docker Compose, environment variables and secrets (8 h) \[E\]

**Prerequisites:** D4, D5.

- &#91;E\] **compose.yaml structure:** services, images vs build, ports, volumes, networks, environment, command.
- &#91;E\] **Lifecycle:** `docker compose up -d`, `down` (and `down -v`), `logs -f`, `exec`, `ps`, `build`.
- &#91;E\] **Start-up order:** `depends_on` with `condition: service_healthy` plus health checks. Order alone doesn't mean the dependency is ready.
- &#91;E\] **Environment variables:** `.env` files, `env_file`, variable substitution, per-environment override files (compose.override.yaml).
- &#91;E\] **Secrets:** never put API keys in images or Git. Use Compose secrets, BuildKit build secrets for private package installs, and cloud secret managers in production.
- &#91;E\] **Development workflow:** bind-mounted code with reload, `docker compose watch`, profiles for optional services.
- &#91;R\] Scaling a service (`--scale`), restart policies, resource limits in Compose.

**Mini-project (2 h):** A Compose stack of FastAPI + PostgreSQL + Redis + Adminer with health checks, a `.env.example` file and a one-command start-up. **Exercise:** Leak a fake API key into an image layer, find it with `docker history`, then fix the build so it never lands in a layer.

### D7 Security and resource management (5 h) \[E\]

**Prerequisites:** D4, D2.

- &#91;E\] **Least privilege:** run as non-root (USER), drop capabilities (`--cap-drop ALL`), `--read-only` root filesystem, `no-new-privileges`; never use `--privileged` or mount the Docker socket without understanding the risk.
- &#91;E\] **Supply chain:** trusted base images, pinned digests, image scanning (Trivy, Docker Scout), SBOMs, image signing (Cosign, concept).
- &#91;E\] **Resource limits:** `--memory`, `--cpus`, `--pids-limit`; what an OOM kill looks like (exit code 137); `docker stats`.
- &#91;R\] Rootless Docker; seccomp and AppArmor profiles; user namespaces.
- &#91;R\] **ML-specific risks:** pickled model files can execute code (prefer safetensors), and untrusted models or images from public hubs.

**Labs:** (1) Scan your D4 image with Trivy and fix the high-severity findings by changing the base image. (2) Give a container 256 MB of memory, load a large array in Python, and observe the OOM kill and exit code.

### D8 Registries, debugging and troubleshooting (4 h) \[E\]

**Prerequisites:** D3, D4.

- &#91;E\] **Registries:** Docker Hub (public and private repos, rate limits), GitHub Container Registry (GHCR), cloud registries (Amazon ECR, Azure ACR, Google Artifact Registry), self-hosted (Harbor, registry:2).
- &#91;E\] **Tagging strategy:** semantic version + Git SHA, immutable tags, pulling by digest in production.
- &#91;E\] **Debugging toolkit:** `docker logs`, `exec`, `inspect` (state, exit code, mounts, network), `events`, `docker run --entrypoint sh` to get into a crashing image.
- &#91;E\] **Common failures:** exit codes (0, 1, 126, 127, 137, 139), "port already allocated", permission denied on volumes (UID mismatch), "no space left on device", DNS failures, platform mismatch (arm64 vs amd64), build cache surprises.

**Lab:** Push your image to GHCR and Docker Hub, pull it on another machine (or Play with Docker) and run it. **Exercise:** A partner (or an AI assistant) breaks your Compose stack in five hidden ways, and you diagnose each one using only Docker commands.

### D9 Docker in CI/CD and the cloud (6 h) \[E\]

**Prerequisites:** D8, S42 topics 1–3.

- &#91;E\] **GitHub Actions:** the official Docker actions (login, setup-buildx, build-push), registry layer caching, tagging from Git metadata, scanning before pushing.
- &#91;E\] **Build once, promote everywhere:** the same image digest goes from dev to staging to production.
- &#91;E\] **Running containers in the cloud:** AWS ECS/Fargate and App Runner, Google Cloud Run, Azure Container Apps; pulling from private registries with IAM roles.
- &#91;R\] Multi-architecture images built in CI; OIDC authentication from GitHub to the cloud, with no long-lived keys.

**Mini-project (3 h):** On every push to main, CI tests, builds, scans and pushes the image. On a tag, it deploys to Cloud Run or ECS.

### D10 Docker for Python and ML development (7 h) \[E\]

**Prerequisites:** D6, S27.

- &#91;E\] **Reproducible ML environments:** pinning Python, CUDA and library versions in an image; lock files.
- &#91;E\] **Choosing ML base images:** `python:*-slim` for CPU inference; `pytorch/pytorch` or NVIDIA NGC images for GPU training; image size vs convenience.
- &#91;E\] **Jupyter in Docker,** with a bind-mounted notebooks folder.
- &#91;E\] **Dev containers** (devcontainer.json) in VS Code: the whole team gets the same environment.
- &#91;E\] **Databases for ML projects:** Postgres + pgvector, Redis, MinIO (S3-compatible storage) via Compose.
- &#91;R\] Keeping data and models out of images: mount them, or download them at start-up from object storage or the Hugging Face Hub, with a cache volume.

**Mini-project (4 h):** A dev container for your Phase 5 deep-learning repo, with Jupyter, a Postgres + pgvector service, and a Makefile with `make up`, `make train` and `make test`.

### D11 GPU workloads and LLM inference (9 h) \[R\]

**Prerequisites:** D10, S44 topics 1–5. You need an NVIDIA GPU machine; cloud GPUs are fine.

- &#91;E\] **NVIDIA Container Toolkit:** how containers reach the host GPU driver; `docker run --gpus all`; checking with `nvidia-smi` inside a container.
- &#91;E\] **CUDA image tags:** base vs runtime vs devel; matching the CUDA version in the image to the host driver.
- &#91;E\] **GPUs in Compose:** `deploy.resources.reservations.devices`.
- &#91;E\] **LLM serving containers:** Ollama (`ollama/ollama`), vLLM (`vllm/vllm-openai`), Hugging Face TGI, NVIDIA Triton and NIM images.
- &#91;E\] **Model weights:** mounting the Hugging Face cache as a volume, gated-model tokens as secrets, start-up time vs image size trade-offs; shared memory (`--ipc=host` or `--shm-size`) for PyTorch data loaders and vLLM.
- &#91;R\] Running several models on one GPU; GPU memory limits; MIG partitioning (awareness).

A Compose file serving an open LLM with vLLM on one GPU:

```yaml
services:
  vllm:
    image: vllm/vllm-openai:latest
    command: ["--model", "Qwen/Qwen2.5-1.5B-Instruct"]
    ports: ["8000:8000"]
    ipc: host
    volumes: ["hf-cache:/root/.cache/huggingface"]
    deploy:
      resources:
        reservations:
          devices:
            - driver: nvidia
              count: 1
              capabilities: [gpu]
volumes:
  hf-cache:
```

**Mini-project (4 h):** Serve the same model with Ollama and with vLLM in containers, load-test both with 1, 8 and 32 concurrent users, and write up throughput, time to first token and GPU memory use. Pin the image tag instead of `latest` in your final version.

### D12 Production AI applications and Kubernetes integration (13 h) \[E\]

**Prerequisites:** D6–D11; S41 for the Kubernetes part.

- &#91;E\] **Production container behaviour:** graceful shutdown (handling SIGTERM, finishing in-flight requests), health and readiness endpoints, structured JSON logs to stdout, configuration from the environment.
- &#91;E\] **A full RAG stack in Compose:** API, worker (document ingestion), vector DB, Postgres, Redis cache, LLM server or API gateway, Langfuse or Prometheus + Grafana for monitoring.
- &#91;E\] **From Compose to Kubernetes:** how Compose services map to Deployments + Services, volumes to PersistentVolumeClaims, `.env` files to ConfigMaps and Secrets; Kompose as a starting point (then clean up by hand); Helm charts.
- &#91;E\] **Containers in ML pipelines:** each pipeline step (ingest, train, evaluate, register) as its own image, run by Airflow, Kubeflow or Kubernetes Jobs.
- &#91;R\] Image size and start-up time for autoscaling; pre-pulling large images on GPU nodes.

**Capstone project (11 h): "Containerized RAG assistant."** A Compose stack of FastAPI + Qdrant + Postgres + Redis + Ollama (or an API LLM) + Langfuse, built by CI into versioned images and then deployed to a local kind cluster with Helm. **Deliverables:** a repo with Dockerfiles, compose.yaml, a Helm chart, a GitHub Actions workflow, an architecture diagram, and a README with a one-command local start-up and a load-test result.

### How Docker connects to the rest of the stack

| With | How they combine | Where you practise |
| --- | --- | --- |
| Python | Pinned interpreter + locked dependencies inside an image; uv or pip install with a cache mount | D4, D10 |
| PyTorch | CPU vs CUDA images; matching CUDA to the driver; shared memory for DataLoader workers; mounting datasets and checkpoints | D10, D11 |
| FastAPI | Uvicorn/Gunicorn in the container; health checks; non-root user; graceful shutdown | D4, D12 |
| Databases | Official Postgres/Redis/Mongo images with named volumes for development; managed cloud databases in production | D3, D5, D6 |
| RAG applications | Compose wires the API, ingestion worker, vector DB and cache; the same images go to Kubernetes | D6, D12 |
| LLMs | vLLM, Ollama, TGI or Triton containers; weights in volumes; GPU reservations | D11 |
| Production ML pipelines | One image per step, run by an orchestrator; images tagged by Git SHA for lineage in MLflow | D9, D12, S46 |
| Kubernetes | Images are the unit Kubernetes runs; probes, limits and config map directly from what you set in Docker | D12, S41 |

### Docker resources

| Resource | Type | Level | What you'll learn and why it's recommended |
| --- | --- | --- | --- |
| ★ [Docker: Get started](https://docs.docker.com/get-started/) | Official docs | B | The official hands-on introduction: images, containers, Compose, sharing. |
| ★ [TechWorld with Nana (YouTube)](https://www.youtube.com/@TechWorldwithNana) | YouTube | B | Her free 3-hour "Docker Tutorial for Beginners" full course and shorter Docker videos. |
| [Play with Docker](https://labs.play-with-docker.com/) | Interactive | B | A free browser-based Docker playground; no install needed. |
| [Dockerfile reference](https://docs.docker.com/reference/dockerfile/) | Official docs | B–I | Every instruction and its exact behaviour. |
| [Building best practices](https://docs.docker.com/build/building/best-practices/) / [Multi-stage builds](https://docs.docker.com/build/building/multi-stage/) | Official docs | I | Smaller, faster, safer images. |
| [Volumes](https://docs.docker.com/engine/storage/volumes/) / [Networking](https://docs.docker.com/engine/network/) | Official docs | B–I | Storage and network drivers in detail. |
| [Docker Compose docs](https://docs.docker.com/compose/) / [Compose secrets](https://docs.docker.com/compose/how-tos/use-secrets/) / [Build secrets](https://docs.docker.com/build/building/secrets/) | Official docs | I | Multi-container apps and handling secrets correctly. |
| [Docker security](https://docs.docker.com/engine/security/) / [Rootless mode](https://docs.docker.com/engine/security/rootless/) / [Resource constraints](https://docs.docker.com/engine/containers/resource_constraints/) | Official docs | I–A | Isolation, capabilities, limits and GPU flags. |
| [Docker GitHub Actions guide](https://docs.docker.com/build/ci/github-actions/) | Official docs | I | Build, cache, tag and push from CI. |
| [Compose GPU support](https://docs.docker.com/compose/how-tos/gpu-support/) / [NVIDIA Container Toolkit install guide](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html) | Official docs | I | GPUs inside containers. |
| [FastAPI in containers](https://fastapi.tiangolo.com/deployment/docker/) / [uv Docker guide](https://docs.astral.sh/uv/guides/integration/docker/) | Official docs | I | Framework-specific best practice for Python images. |
| [Dev Containers spec](https://containers.dev/) / [VS Code Dev Containers](https://code.visualstudio.com/docs/devcontainers/containers) | Official docs | I | Reproducible development environments. |
| [Docker on WSL2 (Microsoft)](https://learn.microsoft.com/en-us/windows/wsl/tutorials/wsl-containers) | Official docs | B | Setting up Docker on a Windows laptop. |
| [Linux namespaces](https://man7.org/linux/man-pages/man7/namespaces.7.html) / [cgroups](https://man7.org/linux/man-pages/man7/cgroups.7.html) man pages + [Containers from scratch (Liz Rice)](https://github.com/lizrice/containers-from-scratch) | Reference + code | A | The kernel features underneath Docker. |
| [Open Container Initiative](https://opencontainers.org/) | Spec | A | The image and runtime standards Docker follows. |
| [Hadolint](https://github.com/hadolint/hadolint) / [dive](https://github.com/wagoodman/dive) / [Trivy](https://github.com/aquasecurity/trivy) / [Docker Scout](https://docs.docker.com/scout/) | Tools | I | Linting, layer inspection, vulnerability scanning. |
| [Docker Hub](https://hub.docker.com/): [ollama/ollama](https://hub.docker.com/r/ollama/ollama), [vllm/vllm-openai](https://hub.docker.com/r/vllm/vllm-openai), [pytorch/pytorch](https://hub.docker.com/r/pytorch/pytorch); [NVIDIA NGC PyTorch](https://catalog.ngc.nvidia.com/orgs/nvidia/containers/pytorch) | Registries | I | The images you'll use for AI workloads. Read their tag lists and docs. |
| [GitHub Container Registry](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry) / [Amazon ECR](https://docs.aws.amazon.com/AmazonECR/latest/userguide/what-is-ecr.html) / [Harbor](https://goharbor.io/) | Official docs | I | Private registries. |
| [Distroless images](https://github.com/GoogleContainerTools/distroless) | GitHub | A | Minimal runtime images with no shell or package manager. |
| [Podman](https://podman.io/) | Official docs | I | A daemonless, rootless Docker alternative. Learn the differences after D7. |
| *Docker Deep Dive* (Nigel Poulton) | Book (*paid*) | B–I | A clear book covering the whole Docker stack, updated regularly. |
| [Data Engineering Zoomcamp, module 1](https://github.com/DataTalksClub/data-engineering-zoomcamp) | MOOC | B | Docker + Postgres + Compose in a data-pipeline context. |

## 8. Practical exercises and project roadmap

The project path has **10 portfolio projects (P1–P10)**, each reusing the previous ones. By P10, you have used every core subject at least twice. Small exercises and labs fill the practice hours in section 4; projects fill the project hours. Every project lives in its own public GitHub repo.

### Small exercises, labs and mini-projects by domain

| Domain | Small coding exercises | Concept experiments and labs | Mini-projects |
| --- | --- | --- | --- |
| Linux & Git (S2–S3) | 30 OverTheWire Bandit levels; 20 Learn Git Branching levels | Recover a deleted commit with reflog; write a cron job | A bash script that backs up a folder to a dated archive and logs the result |
| Python (S5–S7) | 60 Exercism/CS50P problems; implement map, filter and a decorator yourself | Time a loop vs a comprehension vs NumPy; threads vs processes vs asyncio on I/O vs CPU tasks | Typer CLI to-do app; async web-page downloader with a rate limit |
| Software engineering (S8) | Write tests for 5 of your earlier functions | Refactor a 200-line script into a package with tests | Publish a small utility package to TestPyPI |
| Math (S9–S11) | Implement dot product, matrix multiply, determinant and gradient descent in plain Python, then in NumPy | Visualize a 2×2 matrix transforming a grid; check the central limit theorem by simulation | PCA from scratch on images of faces or digits; an A/B test simulator with power analysis |
| DSA (S12) | 75 LeetCode problems by pattern (Phase 3), 150 by Phase 9 | Time the same search with a list vs a set vs a sorted list + binary search | A trie-based autocomplete; Dijkstra on a city-route graph |
| Data & SQL (S13–S16) | 50 SQLBolt/LeetCode SQL problems; 30 pandas exercises | Compare pandas vs Polars vs DuckDB speed on a 5 GB file | An ETL script: API → validate → Parquet → Postgres, scheduled with Prefect |
| Backend (S17–S18) | Build each HTTP verb endpoint; return proper status codes | Watch a TCP handshake in Wireshark; stream SSE to a browser | A URL shortener API with Redis caching and rate limiting |
| Classical ML (S19–S24) | Implement linear and logistic regression, k-NN and k-means from scratch | Show overfitting with polynomial degree; show leakage with target encoding | Spam classifier with TF-IDF + logistic regression and a threshold chosen from costs |
| Deep learning (S26–S32) | micrograd; an MLP in raw PyTorch; a conv layer by hand | Overfit one batch; compare optimizers; try no-init vs He-init | MNIST → CIFAR-10 CNN; a character-level RNN; a small VAE on MNIST |
| LLMs (S33–S39) | BPE tokenizer from scratch; cosine similarity search over 1,000 sentences | Temperature and top-p sweeps; chunk-size vs retrieval-recall experiment | Structured extraction app; a 50-question eval set for your own RAG app |
| Production (S40–S49) | 12 Docker labs (section 7); 10 kubectl debugging drills | Kill pods under load and watch recovery; drift simulation with Evidently | CI pipeline with eval gate; Grafana dashboard for an API |
| Advanced (S50–S53) | Q-learning on FrozenLake; DDP on 2 GPUs (or 2 CPU processes) | PPO on CartPole with Stable-Baselines3; profile a training step | Reproduce a figure from a paper (section 9) |

### The 10 portfolio projects

| # | Project | Phase | Time | Combines |
| --- | --- | --- | --- | --- |
| P1 | Personal finance CLI | 1 | 15 h | Python, OOP, testing, packaging, Git |
| P2 | Public-data analysis system | 3 | 20 h | P1 skills + pandas, SQL, EDA, visualization, Streamlit |
| P3 | Production-style REST API | 3 | 20 h | P1–P2 + FastAPI, Postgres, auth, Docker Compose basics |
| P4 | End-to-end predictive ML application | 4 | 40 h | P2 + P3 + classical ML, feature engineering, evaluation, SHAP |
| P5 | Computer vision classifier and detector | 5 | 20 h | P4 + PyTorch, CNNs, transfer learning, ONNX export |
| P6 | GPT from scratch + fine-tuned NLP classifier | 5 | 20 h | P5 + Transformers, tokenization, Hugging Face |
| P7 | RAG chatbot with an evaluation suite | 6 | 25 h | P3 + P6 + embeddings, vector DB, hybrid search, Ragas |
| P8 | Research agent and multi-agent system | 6 | 30 h | P7 + agents, LangGraph, MCP, guardrails, tracing |
| P9 | Capstone A: production LLM platform | 9 | 60 h | P7 + P8 + Docker, Kubernetes, CI/CD, cloud, LLMOps, security |
| P10 | Capstone B: end-to-end MLOps pipeline | 9 | 60 h | P4 + P5 + MLflow, DVC, orchestration, serving, monitoring |

### P1 — Personal finance CLI (15 h, Phase 1)

- **Problem:** Track income and expenses from the terminal, and report monthly spending by category.
- **Outcome:** A pip-installable CLI (`finance add`, `finance report --month 2027-03`) with 80%+ test coverage.
- **Technologies:** Python, Typer, dataclasses, SQLite or JSON storage, pytest, Ruff, uv.
- **Architecture:** CLI layer → service layer (business logic) → storage layer (a repository class you can swap from JSON to SQLite).
- **Features:** Add/edit/delete transactions, categories, monthly report, CSV import/export, input validation, logging.
- **Concepts:** OOP, separation of concerns, testing with fixtures, packaging, type hints.
- **GitHub deliverables:** README with a demo GIF, tests in CI (GitHub Actions), pyproject.toml, a CHANGELOG.

### P2 — Public-data analysis system (20 h, Phase 3)

- **Problem:** Answer five real questions from an open dataset, such as India's air-quality data (data.gov.in or Kaggle), IPL match data, or city rainfall records.
- **Outcome:** A reproducible pipeline and an interactive dashboard with findings a non-technical person can read.
- **Technologies:** pandas or Polars, PostgreSQL (in Docker), SQL window functions, Seaborn/Plotly, Streamlit.
- **Architecture:** Raw files → cleaning script → Postgres tables → SQL analysis views → Streamlit dashboard.
- **Features:** A data-quality report, 8+ charts, filters by region and time, a written insights page.
- **Concepts:** Data cleaning, EDA, SQL joins and windows, statistics (confidence intervals), visualization choices.
- **GitHub deliverables:** A notebook of EDA, a `src/` pipeline, SQL files, a dashboard link on Hugging Face Spaces or Streamlit Cloud, and a findings write-up.

### P3 — Production-style REST API (20 h, Phase 3)

- **Problem:** A backend for a study-notes app where users save, tag and search notes.
- **Outcome:** A documented, tested, containerized API that someone else can run with one command.
- **Technologies:** FastAPI, Pydantic, SQLAlchemy + Alembic, PostgreSQL, Redis, JWT auth, pytest, Docker Compose.
- **Architecture:** Client → FastAPI (routers, services, repositories) → Postgres; Redis for caching and rate limiting.
- **Features:** Sign-up/login, CRUD notes, tags, full-text search (Postgres), pagination, rate limiting, OpenAPI docs, health endpoint.
- **Concepts:** REST design, auth, database design and indexes, testing APIs, Docker basics (D1–D3).
- **GitHub deliverables:** compose.yaml, migration scripts, API tests in CI, an architecture diagram, Postman/HTTPie examples.

### P4 — End-to-end predictive ML application (40 h, Phase 4)

- **Problem:** Predict an outcome that matters to a business, such as loan default, customer churn or house prices (for example from a Kaggle dataset).
- **Outcome:** A model that beats a stated baseline, with an honest evaluation and an API that serves predictions with explanations.
- **Technologies:** scikit-learn Pipelines, LightGBM/XGBoost, Optuna, SHAP, MLflow (local), FastAPI (reuse P3's structure).
- **Architecture:** Data → feature pipeline → training script (tracked in MLflow) → saved pipeline → FastAPI `/predict` endpoint returning a prediction + top SHAP reasons.
- **Features:** EDA, 3+ model families compared with cross-validation, tuning, calibration, threshold chosen from a cost matrix, slice metrics by segment, a model card.
- **Concepts:** S19–S24 in full: leakage prevention, metrics, interpretability, fairness check.
- **GitHub deliverables:** Notebooks for EDA and error analysis, a `train.py` with a config file, MLflow screenshots, the API, a model card, a 2-page report.

### P5 — Computer vision classifier and detector (20 h, Phase 5)

- **Problem:** Identify plant diseases from leaf photos (the PlantVillage dataset), then detect and count objects in an image with a detector.
- **Outcome:** A fine-tuned model above 95% accuracy on held-out data, exported to ONNX, with a Gradio demo.
- **Technologies:** PyTorch, torchvision/timm, Albumentations, Weights & Biases, ONNX Runtime, Ultralytics YOLO, Gradio.
- **Architecture:** Dataset + augmentations → pretrained backbone + new head → training with mixed precision → evaluation (confusion matrix, Grad-CAM) → ONNX export → Gradio app.
- **Features:** Training from scratch vs transfer learning comparison, augmentation ablation, Grad-CAM visual explanations, latency benchmark (PyTorch vs ONNX).
- **Concepts:** CNNs, transfer learning, training diagnostics, model export, experiment tracking.
- **GitHub deliverables:** Training code, W&B report link, an ONNX model on the Hugging Face Hub, a live Gradio Space.

### P6 — GPT from scratch + fine-tuned NLP classifier (20 h, Phase 5)

- **Problem:** (a) Train a small GPT on a text corpus of your choice, for example Telugu or English stories. (b) Classify customer reviews or news headlines by fine-tuning a pretrained encoder.
- **Outcome:** A working GPT that generates text in the corpus style, and a classifier that beats a TF-IDF baseline.
- **Technologies:** PyTorch, your own BPE tokenizer (or SentencePiece), Hugging Face Transformers, Datasets, the Trainer API.
- **Architecture:** (a) Tokenizer → decoder-only Transformer → training loop → sampling with temperature/top-k. (b) Pretrained BERT-style encoder + classification head → fine-tuning → evaluation.
- **Features:** Loss curves, attention visualizations, sampling experiments; for the classifier, a comparison table: TF-IDF + logistic regression vs fine-tuned encoder vs zero-shot LLM.
- **Concepts:** Attention, tokenization, Transformers, transfer learning in NLP, evaluation.
- **GitHub deliverables:** Clean model code with tests on tensor shapes, sample outputs, the comparison table, a blog post explaining what you learned.

### P7 — RAG chatbot with an evaluation suite (25 h, Phase 6)

- **Problem:** Answer questions about a large set of documents, such as your university's regulations and syllabi, or public government scheme documents, with citations.
- **Outcome:** A chatbot that answers with sources, says "I don't know" when it should, and has measured retrieval and answer quality.
- **Technologies:** FastAPI (from P3), an embedding model, Qdrant or pgvector, BM25, a reranker, an LLM API or Ollama, Ragas, Langfuse, a simple chat UI.
- **Architecture:** Ingestion worker (parse → chunk → embed → index) → query API (rewrite → hybrid retrieve → rerank → generate with citations, streamed) → tracing and evaluation.
- **Features:** Hybrid search, reranking, citations with page numbers, streaming answers, a 100-question golden eval set, a dashboard comparing 3 chunking strategies.
- **Concepts:** S33, S34, S36 and S39; prompt injection checks from S48.
- **GitHub deliverables:** Ingestion and API code, the eval set and results table, a Docker Compose stack, a demo video, a write-up of what improved the scores most.

### P8 — Research agent and multi-agent system (30 h, Phase 6)

- **Problem:** Given a question, research it on the web and in your P7 knowledge base, then produce a cited report.
- **Outcome:** Two versions: a single agent, and a planner + parallel workers + reviewer system. Both are evaluated on the same 30 tasks.
- **Technologies:** An agent written from scratch first, then LangGraph; MCP (build one MCP server that exposes your P7 search); a web search API; Langfuse tracing.
- **Architecture:** LangGraph state graph: plan → parallel research workers (tools: web search, P7 retriever, Python sandbox) → synthesize → citation-check reviewer → human approval node → final report.
- **Features:** Checkpointing (resume after a crash), max-step and cost budgets, human-in-the-loop, citation verification, a comparison of single- vs multi-agent quality, cost and latency.
- **Concepts:** S37, S38 and S39; guardrails and excessive-agency risks from S48.
- **GitHub deliverables:** Both implementations, the MCP server, trace screenshots, an evaluation table, and a write-up of when multi-agent was and wasn't worth it.

### P9 — Capstone A: production LLM platform (60 h, Phase 9)

- **Problem:** Turn P7 + P8 into a multi-tenant "document assistant" service that an organization could actually run.
- **Outcome:** A deployed, monitored, secured system on Kubernetes or a managed cloud service, with CI/CD and a load-test report.
- **Technologies:** Docker, Helm, Kubernetes (kind locally, plus EKS/GKE/AKS or Cloud Run), GitHub Actions, Terraform, vLLM (or an LLM gateway such as LiteLLM over APIs), Redis, Postgres + vector DB, Langfuse, Prometheus + Grafana, OpenTelemetry.
- **Architecture:** Gateway (auth, rate limits per tenant) → API pods (autoscaled) → retriever + reranker → model router (small model first, large model fallback) → vLLM or API; ingestion workers on a queue; per-tenant document permissions; tracing and metrics across every hop.
- **Features:** Tenant isolation, document-level access control, semantic caching, model routing with cost tracking, prompt-injection defences, PII redaction in logs, eval-gated deployments, canary releases, SLO dashboard, runbook.
- **Concepts:** S40–S49 together, plus everything from P7–P8.
- **GitHub deliverables:** Monorepo with services, Helm chart, Terraform, CI/CD workflows, a design doc with cost estimates, a threat model, the load-test report, a 5-minute demo video.

### P10 — Capstone B: end-to-end MLOps pipeline (60 h, Phase 9)

- **Problem:** Keep a prediction model (P4's model, or a new problem such as demand forecasting for a store chain) accurate in production as data changes.
- **Outcome:** A pipeline that ingests new data, validates it, retrains, compares against production, deploys the winner safely and monitors drift. All automated.
- **Technologies:** DVC, Prefect or Airflow, MLflow (tracking + registry), Great Expectations or Pandera, Feast (optional), FastAPI or BentoML serving, Docker, Kubernetes, Evidently, Prometheus + Grafana, GitHub Actions.
- **Architecture:** Data source → ingestion + validation → feature pipeline → training job (container) → evaluation vs champion → registry promotion → canary deployment → monitoring (drift, latency, accuracy when labels arrive) → retraining trigger.
- **Features:** Reproducible runs (data version + code SHA + config), automated champion/challenger comparison, shadow or canary deployment, drift alerts, a rollback path, a model card that updates per release.
- **Concepts:** S16, S23–S24, S40–S47 together.
- **GitHub deliverables:** Pipeline code, DAG screenshots, MLflow registry, monitoring dashboards, an architecture diagram, and a postmortem of one failure you simulated (bad data, drift or a broken model) and how the system caught it.

### Optional specialization projects

- **Fine-tuning (S35, 15 h):** QLoRA-tune a small open model for one narrow task, such as converting English instructions into SQL for a known schema. Compare it with prompting a larger model on accuracy, latency and cost.
- **Inference optimization (S45, 15 h):** Quantize one model three ways (bitsandbytes, AWQ/GPTQ, GGUF) and chart quality vs speed vs memory.
- **RL (S50, 20 h):** Train PPO agents on Gymnasium tasks, then use TRL to apply DPO to a small LLM with a preference dataset.
- **Distributed training (S51, 15 h):** Convert your P6 GPT training to DDP and then FSDP; report scaling efficiency on 1, 2 and 4 GPUs.

## 9. Research paper reading and implementation roadmap

Read about **100 papers in five tiers**, each tier unlocked by a phase of the curriculum, and **reproduce three of them** (R1–R3 below). Start in Phase 4 with one paper every two weeks. From Phase 6, read one a week. The research track (S52) is 120 hours: 30 reading and method, 30 implementation practice, 60 for the three reproductions.

### How to read a paper

Use S. Keshav's three-pass method from [How to Read a Paper](http://ccr.sigcomm.org/online/files/p83-keshavA.pdf):

1. **Pass 1 (10 minutes):** title, abstract, introduction, section headings, figures, conclusion. Decide: what problem, what claim, is it worth more time?
2. **Pass 2 (1 hour):** read everything except proofs. Study every figure and table. Note terms and references you don't know.
3. **Pass 3 (3–5 hours, only for papers you'll implement):** re-derive the key equations, and imagine how you would have built it yourself. List every assumption.

Keep a reading log with one entry per paper: problem, key idea in 2 sentences, method, main result with numbers, limitations, and one question you still have.

**How deep to go:** Do pass 1 on every paper in the tiers below, pass 2 on about 30, and pass 3 only on the 8 starred (★) papers and the three you reproduce. Most tier 1–4 reading counts toward the theory hours of the subject it belongs to, so it is not all extra time.

### Understanding the mathematical formulations

- Rewrite each equation in words, then in NumPy/PyTorch with explicit tensor shapes written as comments (for example `# q: (batch, heads, seq, d_head)`).
- Build a notation table for each paper: every symbol, its meaning and its shape.
- Check the equation on a tiny example by hand: 2 tokens, dimension 3.
- If a step is unclear, find an earlier paper it cites, a blog explanation (Lilian Weng, Jay Alammar), or a reference implementation on GitHub.

### Interpreting experiments and evaluating claims

Ask these questions of every paper:

- **Baselines:** Are they strong and recent, and tuned as carefully as the new method?
- **Ablations:** Which parts of the method actually matter?
- **Variance:** Are there error bars, multiple seeds, or confidence intervals? Is the gain bigger than the run-to-run noise?
- **Fairness of comparison:** the same compute, data and tuning budget?
- **Contamination:** could the test data have leaked into training (a big issue for LLM benchmarks)?
- **Scope:** Does it hold beyond the datasets tested? What does the limitations section admit, and what does it leave out?

### Reproducing and implementing published work

1. Find the official code (linked from the paper, or from its [Hugging Face Papers](https://huggingface.co/papers) page) and run it first, as is.
2. Reimplement the core idea yourself at small scale: a small dataset, a small model, one GPU.
3. Match one key table or figure within a reasonable margin, and document every difference from the paper.
4. Run one ablation the paper didn't, or test it on a new dataset. **This is where research gaps appear.**
5. Write it up: a README report or a blog post with plots. This is excellent portfolio material.

### Finding research gaps and running your own experiments

- Read the "limitations" and "future work" sections, and the open issues on the official repo.
- Look for methods tested only in English (try Telugu or Hindi), only on large models (try small ones), or only on one domain.
- Design experiments like an engineer: one hypothesis, one variable changed, fixed seeds, 3+ runs, logged in W&B or MLflow, and a baseline run first.
- Tools for discovery: [Hugging Face Papers](https://huggingface.co/papers), [arXiv](https://arxiv.org/) (cs.LG, cs.CL, cs.CV listings), [Semantic Scholar](https://www.semanticscholar.org/), [Connected Papers](https://www.connectedpapers.com/), [alphaXiv](https://www.alphaxiv.org/) (discussion on arXiv papers).

### Tier 1 — Foundations of learning (read during Phase 4–5)

| Year | Paper | Why it matters |
| --- | --- | --- |
| 1986 | [Learning representations by back-propagating errors (Rumelhart, Hinton, Williams)](https://www.nature.com/articles/323533a0) | Backpropagation for neural networks |
| 1997 | [Long Short-Term Memory (Hochreiter & Schmidhuber)](https://www.bioinf.jku.at/publications/older/2604.pdf) | The gated memory cell behind LSTMs |
| 1998 | [Gradient-Based Learning Applied to Document Recognition (LeCun et al.)](https://ieeexplore.ieee.org/document/726791) | LeNet and the modern CNN |
| 2001 | [Random Forests (Breiman)](https://link.springer.com/article/10.1023/A:1010933404324) | Bagged decision trees with random features |
| 2014 | [Dropout (Srivastava et al.)](https://jmlr.org/papers/v15/srivastava14a.html) | The classic regularization method |
| 2014 | [Adam (Kingma & Ba)](https://arxiv.org/abs/1412.6980) | The default optimizer |
| 2015 | [Batch Normalization (Ioffe & Szegedy)](https://arxiv.org/abs/1502.03167) | Stable, faster deep-network training |
| 2015 | [Delving Deep into Rectifiers (He et al.)](https://arxiv.org/abs/1502.01852) | He/Kaiming initialization |
| 2016 | [XGBoost (Chen & Guestrin)](https://arxiv.org/abs/1603.02754) | Scalable gradient boosting |
| 2016 | [Layer Normalization (Ba, Kiros, Hinton)](https://arxiv.org/abs/1607.06450) | The normalization used in Transformers |

### Tier 2 — Vision and generative models (Phase 5)

| Year | Paper | Why it matters |
| --- | --- | --- |
| 2012 | [ImageNet Classification with Deep CNNs — AlexNet (Krizhevsky et al.)](https://papers.nips.cc/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html) | Started the deep-learning era |
| 2013 | [Auto-Encoding Variational Bayes (Kingma & Welling)](https://arxiv.org/abs/1312.6114) | VAEs |
| 2014 | [Generative Adversarial Networks (Goodfellow et al.)](https://arxiv.org/abs/1406.2661) | GANs |
| 2014 | [Very Deep Convolutional Networks — VGG (Simonyan & Zisserman)](https://arxiv.org/abs/1409.1556) | Depth with small filters |
| 2015 | [Deep Residual Learning — ResNet (He et al.)](https://arxiv.org/abs/1512.03385) | Residual connections; used in every modern architecture |
| 2015 | [U-Net (Ronneberger et al.)](https://arxiv.org/abs/1505.04597) | Segmentation; later the backbone of diffusion models |
| 2015 | [Faster R-CNN (Ren et al.)](https://arxiv.org/abs/1506.01497) / [YOLO (Redmon et al.)](https://arxiv.org/abs/1506.02640) | Two-stage vs one-stage object detection |
| 2015 | [Distilling the Knowledge in a Neural Network (Hinton et al.)](https://arxiv.org/abs/1503.02531) | Knowledge distillation |
| 2020 | [Denoising Diffusion Probabilistic Models (Ho et al.)](https://arxiv.org/abs/2006.11239) | Modern diffusion models |
| 2020 | [SimCLR (Chen et al.)](https://arxiv.org/abs/2002.05709) / [FixMatch (Sohn et al.)](https://arxiv.org/abs/2001.07685) | Contrastive self-supervision; semi-supervised learning |
| 2020 | [An Image is Worth 16x16 Words — ViT (Dosovitskiy et al.)](https://arxiv.org/abs/2010.11929) | Transformers for vision |
| 2021 | [CLIP (Radford et al.)](https://arxiv.org/abs/2103.00020) | Joint image–text embeddings |
| 2021 | [Latent Diffusion / Stable Diffusion (Rombach et al.)](https://arxiv.org/abs/2112.10752) | Diffusion in a compressed latent space |

### Tier 3 — Language models and Transformers (Phase 5–6)

| Year | Paper | Why it matters |
| --- | --- | --- |
| 2013 | [word2vec (Mikolov et al.)](https://arxiv.org/abs/1301.3781) + [follow-up](https://arxiv.org/abs/1310.4546) | Word embeddings |
| 2014 | [GloVe (Pennington et al.)](https://nlp.stanford.edu/pubs/glove.pdf) | Count-based embeddings |
| 2014 | [Sequence to Sequence Learning (Sutskever et al.)](https://arxiv.org/abs/1409.3215) / [GRU encoder–decoder (Cho et al.)](https://arxiv.org/abs/1406.1078) | Encoder–decoder models and the GRU |
| 2014 | [Neural Machine Translation by Jointly Learning to Align and Translate (Bahdanau et al.)](https://arxiv.org/abs/1409.0473) | The first attention mechanism |
| 2017 | ★ [Attention Is All You Need (Vaswani et al.)](https://arxiv.org/abs/1706.03762) | The Transformer. Read it three times. |
| 2017 | [Outrageously Large Neural Networks — MoE (Shazeer et al.)](https://arxiv.org/abs/1701.06538) | Sparse mixture of experts |
| 2018 | [BERT (Devlin et al.)](https://arxiv.org/abs/1810.04805) | Encoder pretraining with masked language modelling |
| 2019 | [GPT-2: Language Models are Unsupervised Multitask Learners (Radford et al.)](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) | Decoder-only scaling; zero-shot ability |
| 2019 | [T5 (Raffel et al.)](https://arxiv.org/abs/1910.10683) | Text-to-text framing; a systematic study of choices |
| 2019 | [Sentence-BERT (Reimers & Gurevych)](https://arxiv.org/abs/1908.10084) | Sentence embeddings for search |
| 2020 | [Scaling Laws for Neural Language Models (Kaplan et al.)](https://arxiv.org/abs/2001.08361) | How loss scales with compute, data and parameters |
| 2020 | [GPT-3: Language Models are Few-Shot Learners (Brown et al.)](https://arxiv.org/abs/2005.14165) | In-context learning |
| 2021 | [RoFormer — RoPE (Su et al.)](https://arxiv.org/abs/2104.09864) | Rotary positional embeddings |
| 2021 | [Switch Transformers (Fedus et al.)](https://arxiv.org/abs/2101.03961) | Scaling with simple MoE routing |
| 2022 | [Training Compute-Optimal LLMs — Chinchilla (Hoffmann et al.)](https://arxiv.org/abs/2203.15556) | Balance parameters and tokens |
| 2023 | [LLaMA (Touvron et al.)](https://arxiv.org/abs/2302.13971) / [Llama 2](https://arxiv.org/abs/2307.09288) / [The Llama 3 Herd of Models](https://arxiv.org/abs/2407.21783) | Open-weight model recipes in detail |
| 2023 | [Mamba (Gu & Dao)](https://arxiv.org/abs/2312.00752) | State-space models as an alternative to attention |
| 2024 | [Mixtral of Experts](https://arxiv.org/abs/2401.04088) / [DeepSeek-V3 Technical Report](https://arxiv.org/abs/2412.19437) | Production MoE models |

### Tier 4 — Alignment, prompting, RAG and agents (Phase 6)

| Year | Paper | Why it matters |
| --- | --- | --- |
| 2017 | [Deep RL from Human Preferences (Christiano et al.)](https://arxiv.org/abs/1706.03741) | The origin of RLHF |
| 2017 | [Proximal Policy Optimization (Schulman et al.)](https://arxiv.org/abs/1707.06347) | The RL algorithm used in classic RLHF |
| 2020 | [Dense Passage Retrieval (Karpukhin et al.)](https://arxiv.org/abs/2004.04906) / [ColBERT (Khattab & Zaharia)](https://arxiv.org/abs/2004.12832) | Neural retrieval |
| 2020 | ★ [Retrieval-Augmented Generation (Lewis et al.)](https://arxiv.org/abs/2005.11401) | The original RAG paper |
| 2021 | [LoRA (Hu et al.)](https://arxiv.org/abs/2106.09685) | Low-rank adapters for fine-tuning |
| 2022 | [Chain-of-Thought Prompting (Wei et al.)](https://arxiv.org/abs/2201.11903) / [Self-Consistency (Wang et al.)](https://arxiv.org/abs/2203.11171) | Reasoning through prompting |
| 2022 | ★ [InstructGPT: Training LMs to Follow Instructions with Human Feedback (Ouyang et al.)](https://arxiv.org/abs/2203.02155) | SFT + RLHF, the ChatGPT recipe |
| 2022 | [ReAct (Yao et al.)](https://arxiv.org/abs/2210.03629) | Reason + act: the basis of agent loops |
| 2022 | [Constitutional AI (Bai et al.)](https://arxiv.org/abs/2212.08073) | Training with AI feedback against written principles |
| 2022 | [HyDE: Precise Zero-Shot Dense Retrieval (Gao et al.)](https://arxiv.org/abs/2212.10496) | Query rewriting for retrieval |
| 2023 | [Toolformer (Schick et al.)](https://arxiv.org/abs/2302.04761) | Models learning to call tools |
| 2023 | [Reflexion (Shinn et al.)](https://arxiv.org/abs/2303.11366) / [Tree of Thoughts (Yao et al.)](https://arxiv.org/abs/2305.10601) | Self-reflection and search over reasoning steps |
| 2023 | [Generative Agents (Park et al.)](https://arxiv.org/abs/2304.03442) | Memory, reflection and planning in agent simulations |
| 2023 | ★ [Direct Preference Optimization (Rafailov et al.)](https://arxiv.org/abs/2305.18290) | Preference tuning without RL |
| 2023 | [QLoRA (Dettmers et al.)](https://arxiv.org/abs/2305.14314) | Fine-tuning 4-bit quantized models |
| 2023 | [Judging LLM-as-a-Judge (Zheng et al.)](https://arxiv.org/abs/2306.05685) | LLM judges, and their biases |
| 2023 | [Lost in the Middle (Liu et al.)](https://arxiv.org/abs/2307.03172) | How models use (and miss) long-context information |
| 2023 | [Self-RAG (Asai et al.)](https://arxiv.org/abs/2310.11511) / [RAG survey (Gao et al.)](https://arxiv.org/abs/2312.10997) | Adaptive retrieval; an overview of RAG techniques |
| 2023 | [SWE-bench (Jimenez et al.)](https://arxiv.org/abs/2310.06770) | Evaluating agents on real GitHub issues |
| 2024 | [DeepSeekMath — introduces GRPO (Shao et al.)](https://arxiv.org/abs/2402.03300) | RL for reasoning without a value network |
| 2024 | [Scaling LLM Test-Time Compute Optimally (Snell et al.)](https://arxiv.org/abs/2408.03314) | Trading inference compute for accuracy |
| 2025 | [DeepSeek-R1 (DeepSeek-AI)](https://arxiv.org/abs/2501.12948) | Reasoning learned through RL with verifiable rewards |

### Tier 5 — Systems, efficiency, evaluation and safety (Phase 7–8)

| Year | Paper | Why it matters |
| --- | --- | --- |
| 2015 | [Hidden Technical Debt in Machine Learning Systems (Sculley et al.)](https://papers.nips.cc/paper/2015/hash/86df7dcfd896fcaf2674f757a2463eba-Abstract.html) | Why ML systems are hard to maintain. Essential MLOps reading. |
| 2014 | [Explaining and Harnessing Adversarial Examples (Goodfellow et al.)](https://arxiv.org/abs/1412.6572) | Adversarial attacks on models |
| 2016 | [Concrete Problems in AI Safety (Amodei et al.)](https://arxiv.org/abs/1606.06565) | A practical safety research agenda |
| 2017 | [Mixed Precision Training (Micikevicius et al.)](https://arxiv.org/abs/1710.03740) | fp16 training with loss scaling |
| 2018 | [Model Cards for Model Reporting (Mitchell et al.)](https://arxiv.org/abs/1810.03993) / [Datasheets for Datasets (Gebru et al.)](https://arxiv.org/abs/1803.09010) | Documentation standards for responsible AI |
| 2018 | [GPipe (Huang et al.)](https://arxiv.org/abs/1811.06965) | Pipeline parallelism |
| 2019 | [Megatron-LM (Shoeybi et al.)](https://arxiv.org/abs/1909.08053) | Tensor parallelism |
| 2019 | [ZeRO (Rajbhandari et al.)](https://arxiv.org/abs/1910.02054) | Sharded optimizer states (DeepSpeed, FSDP) |
| 2020 | [MMLU (Hendrycks et al.)](https://arxiv.org/abs/2009.03300) / [HELM (Liang et al.)](https://arxiv.org/abs/2211.09110) | Benchmark design and holistic evaluation |
| 2022 | ★ [FlashAttention (Dao et al.)](https://arxiv.org/abs/2205.14135) / [FlashAttention-2](https://arxiv.org/abs/2307.08691) | IO-aware exact attention |
| 2022 | [LLM.int8() (Dettmers et al.)](https://arxiv.org/abs/2208.07339) / [GPTQ (Frantar et al.)](https://arxiv.org/abs/2210.17323) / [AWQ (Lin et al.)](https://arxiv.org/abs/2306.00978) | LLM quantization methods |
| 2022 | [Fast Inference via Speculative Decoding (Leviathan et al.)](https://arxiv.org/abs/2211.17192) | Faster generation with a draft model |
| 2023 | ★ [Efficient Memory Management for LLM Serving with PagedAttention — vLLM (Kwon et al.)](https://arxiv.org/abs/2309.06180) | Why vLLM is fast |
| 2023 | [Efficient Streaming LMs with Attention Sinks (Xiao et al.)](https://arxiv.org/abs/2309.17453) | Long-running generation |
| 2023 | [Indirect Prompt Injection (Greshake et al.)](https://arxiv.org/abs/2302.12173) / [Universal Adversarial Attacks on Aligned LMs (Zou et al.)](https://arxiv.org/abs/2307.15043) | The core LLM security threats |
| 2023 | [Towards Monosemanticity (Anthropic)](https://transformer-circuits.pub/2023/monosemantic-features/index.html) | Sparse autoencoders for interpretability |

### Reproduction milestones

| # | When | Paper to reproduce | Target | Time |
| --- | --- | --- | --- | --- |
| R1 | End of Phase 5 | Attention Is All You Need (decoder-only, small scale), via nanoGPT | Match nanoGPT's character-level Shakespeare loss; write up your attention-head visualizations | 15 h |
| R2 | End of Phase 6 | LoRA or DPO on a 1–3B open model | Reproduce the qualitative claim (LoRA ≈ full fine-tuning on a small task, or DPO improving preference win-rate) with your own evals | 20 h |
| R3 | Phase 8 | A recent paper in your specialization, for example a RAG retrieval method, a quantization method or a small-scale RL-for-reasoning result | Match one table or figure, plus one new ablation of your own; publish as a blog post or arXiv-style report | 25 h |

## 10. Mastery checklists and assessments

**Move to the next phase only when you pass its gate.** That means ticking every \[E\] item in its checklist, scoring 80% or more on its quiz, and finishing its milestone assessment without copying a tutorial. Retake failed gates after one consolidation week. Have an AI tutor or a study partner quiz you, and answer out loud or in writing, without notes.

### The seven-question test for any subject

Use these for every subject. Each matches one line of the mastery goal.

1. **Explain:** Can I explain it to a beginner in 2 minutes without notes?
2. **Internals:** Can I describe what happens inside (the algorithm, the data flow, the maths)?
3. **Implement:** Can I build it from a blank file, using only official docs?
4. **Debug:** When I break it on purpose, can I find the cause from the error alone?
5. **Compare:** Can I name 2 alternatives and when each one wins?
6. **Optimize:** Can I make it faster, smaller or cheaper, and measure the improvement?
7. **Apply:** Have I used it in a project with a problem nobody gave me the answer to?

Questions 1–2 = L1, 3–4 = L2, 5–7 = L3.

### Phase 0 gate — Computing foundations

- [ ] Explain how a float32 differs from a bfloat16, and how many bytes a 7B-parameter model needs in each.
- [ ] Navigate, search files (find, grep), chain commands with pipes, and write a bash script with arguments and error handling.
- [ ] Use Git branches, resolve a merge conflict, open a pull request, and recover a lost commit with reflog.
- [ ] Set up a project with uv, a virtual environment, VS Code debugging and pre-commit.

**Quiz sample:** What does `2>&1` do? What's the difference between `git reset` and `git revert`? Why shouldn't you install packages into the system Python? **Coding challenge:** a bash script that finds the 10 largest files under a folder and writes a report. **Milestone assessment:** your first public repo with a script, a README, a .gitignore and 10+ meaningful commits on 2+ branches.

### Phase 1 gate — Programming and software engineering

- [ ] Write classes with inheritance, dunder methods and dataclasses; explain composition vs inheritance.
- [ ] Use generators, decorators and context managers from scratch.
- [ ] Choose correctly between threading, multiprocessing and asyncio for a given task, and explain why.
- [ ] Write pytest tests with fixtures and mocks; get 80% coverage on a module.
- [ ] Package a project with pyproject.toml and install it in a fresh environment.

**Quiz sample:** What's the GIL, and when does it matter? What does `yield` do to a function? Why is a mutable default argument a bug? **Coding challenge:** implement a `@retry(times=3, backoff=2)` decorator and an LRU cache class, both with tests. **Milestone assessment:** P1 is complete, with CI passing.

### Phase 2 gate — Mathematics

- [ ] Multiply matrices by hand and explain what the result does geometrically.
- [ ] Compute eigenvalues for a 2×2 matrix; explain SVD and its link to PCA.
- [ ] Derive the gradient of the MSE loss for linear regression and of the cross-entropy loss with a softmax.
- [ ] Apply Bayes' theorem to a medical-test problem; explain MLE and why cross-entropy is a negative log-likelihood.
- [ ] Run a hypothesis test and explain correctly what the p-value means (and doesn't).

**Quiz sample:** Why does a zero determinant mean a matrix has no inverse? What does the chain rule have to do with backpropagation? What's the difference between variance and standard error? **Coding challenge:** implement PCA with only NumPy (via SVD) and check it against scikit-learn. **Milestone assessment:** a notebook implementing linear regression three ways (normal equation, gradient descent, scikit-learn), with matching results and your derivations written out.

### Phase 3 gate — DSA, data and systems

- [ ] Solve 75 LeetCode problems across all patterns; solve a new medium problem in 30 minutes.
- [ ] State the time and space complexity of your solutions.
- [ ] Clean and analyse a messy dataset with pandas, and explain each cleaning decision.
- [ ] Write SQL with joins, CTEs and window functions; use EXPLAIN to speed up a query.
- [ ] Build a FastAPI service with auth, a database, tests and a Compose file.
- [ ] Explain what happens, layer by layer, when your browser calls your API.

**Quiz sample:** When would you choose a heap over sorting? What's the difference between an inner and a left join? Why does `localhost` inside a container not reach your laptop? **Coding challenge:** a timed 2-hour task: build a paginated, authenticated endpoint over a provided dataset, with tests. **Milestone assessment:** P2 and P3 complete.

### Phase 4 gate — Classical machine learning

- [ ] Implement linear regression, logistic regression and k-means from scratch.
- [ ] Explain the bias–variance trade-off with learning curves from your own experiment.
- [ ] Detect and prevent data leakage; choose the right cross-validation strategy for time-series and grouped data.
- [ ] Choose a metric from business costs, and set a decision threshold from it.
- [ ] Explain why gradient boosting usually wins on tabular data, and tune it.
- [ ] Explain a model's predictions with SHAP, and say what SHAP can't tell you.

**Quiz sample:** Why is accuracy misleading on imbalanced data? What does regularization do to the coefficients? How do random forests reduce variance? **Coding challenge:** given a new tabular dataset and 3 hours, deliver a cross-validated model that beats a baseline, with an error analysis. **Milestone assessment:** P4 complete, with a 2-page report a non-ML manager can follow.

### Phase 5 gate — Deep learning

- [ ] Build micrograd from memory and explain backprop on a 3-node graph.
- [ ] Write a full PyTorch training loop (Dataset, DataLoader, model, optimizer, evaluation, checkpointing) without references.
- [ ] Diagnose a non-learning network: overfit one batch, check the learning rate, gradients and data.
- [ ] Fine-tune a pretrained CNN and a pretrained Transformer.
- [ ] Write scaled dot-product attention and a Transformer block from scratch with correct shapes.
- [ ] Explain the KV cache and why attention costs O(n²).

**Quiz sample:** Why do residual connections help deep networks train? What does layer norm normalize over? Why scale attention scores by √d? **Coding challenge:** implement multi-head causal self-attention in 45 minutes and pass a provided shape and masking test. **Milestone assessment:** P5, P6 and reproduction R1 complete.

### Phase 6 gate — Generative AI and LLMs

- [ ] Explain BPE tokenization, and estimate the token count and cost of a workload.
- [ ] Get validated structured output from an LLM, with retries.
- [ ] Decide between prompting, RAG and fine-tuning for a given problem, and justify the choice.
- [ ] Build a RAG pipeline with hybrid search and reranking, and measure retrieval recall@k.
- [ ] QLoRA fine-tune a small model and evaluate it against a baseline.
- [ ] Build an agent from scratch (no framework) with tools, a step limit and error handling, then rebuild it in LangGraph.
- [ ] Build an eval suite with an LLM judge, and check the judge's agreement with your own labels.

**Quiz sample:** What does temperature do mathematically? Why does chunk size matter? What is indirect prompt injection? When is a multi-agent system worse than a single agent? **Coding challenge:** in 4 hours, build a RAG app over a provided document set and report recall@5 and faithfulness on a provided question set. **Milestone assessment:** P7, P8 and reproduction R2 complete.

### Phase 7 gate — Production AI engineering

- [ ] Write a multi-stage Dockerfile for an ML API that is under 300 MB (CPU), non-root and scanned.
- [ ] Debug a broken Compose stack and a broken Kubernetes deployment from logs and events alone.
- [ ] Deploy a model API to Kubernetes with probes, resource limits, autoscaling and a Helm chart.
- [ ] Build a CI/CD pipeline that tests, builds, scans, runs evals and deploys.
- [ ] Deploy to one cloud with Terraform, with IAM least privilege and a budget alert.
- [ ] Serve an LLM with vLLM and measure throughput, TTFT and p95 latency under load.
- [ ] Set up metrics, tracing and drift monitoring, with one alert that fires correctly.
- [ ] Write a design doc for an AI system, with scale and cost estimates and a threat model.

**Quiz sample:** What's the difference between a readiness and a liveness probe? Why are pickled models a security risk? How would you roll back a bad model release? **Practical assignment:** a mock ML system design interview (45 minutes) on a section-2 S49 case, recorded and reviewed. **Milestone assessment:** the D12 Docker capstone deployed on kind, plus the D9 CI/CD pipeline.

### Phase 8 gate — Advanced and research

- [ ] Implement Q-learning and train PPO with a library; explain how RLHF uses PPO and how DPO avoids it.
- [ ] Estimate GPU memory for training a model of a given size, and fit it using mixed precision, checkpointing and FSDP.
- [ ] Read a new paper and present its claim, method, evidence and weaknesses in 10 minutes.
- [ ] Reproduce one result (R3) and publish the write-up.

**Milestone assessment:** R3 published, plus a 10-minute talk or video explaining it.

### Phase 9 gate — Industry readiness

P9 and P10 complete and deployed; 150 DSA problems; three mock interviews (coding, ML fundamentals, system design) passed; the final industry-readiness checklist in section 12 is all ticked.

### Assessment calendar

- **Weekly (30 min, Sunday):** a 10-question self-quiz on the week's topics, plus spaced-repetition review in Anki of past cards.
- **Every consolidation week (every 6th week):** a written test, a timed coding challenge, and a project review on the seven-question test above.
- **End of each phase:** the gate above, plus a public write-up (LinkedIn or blog) of what you built.

## 11. Month-wise and week-wise learning schedule

At **4 hours a day, the full program takes 137 weeks (about 32 months)**. At 2 h it takes 275 weeks, at 3 h 184 weeks, and at 6 h 92 weeks. Every plan uses 6 study days a week and **every 6th week is a consolidation week**: no new topics, only revision, the assessment, project polish, or a buffer for college exams. In Phases 1–3, one-third of daily time goes to the parallel math and DSA track.

### Phase timeline for each daily commitment (calendar weeks)

| Phase | 2 h/day | 3 h/day | 4 h/day | 6 h/day |
| --- | --- | --- | --- | --- |
| 0 Computing foundations | W1–8 | W1–5 | W1–4 | W1–3 |
| 1 Programming & SE | W8–47 | W5–32 | W4–23 | W3–15 |
| 2 Math (parallel) | W9–73 | W7–49 | W5–37 | W4–25 |
| 3 DSA, data & systems (DSA runs in parallel to the end) | W47–106 | W32–71 | W23–53 | W15–37 |
| 4 Classical ML | W87–122 | W58–81 | W43–61 | W28–41 |
| 5 Deep learning | W122–157 | W81–104 | W61–79 | W41–52 |
| 6 GenAI & LLMs | W157–184 | W104–123 | W79–92 | W52–62 |
| 7 Production AI | W185–231 | W123–154 | W93–116 | W62–77 |
| 8 Advanced & research | W231–260 | W154–173 | W116–130 | W77–87 |
| 9 Capstone & jobs | W260–275 | W173–184 | W130–137 | W87–92 |
| **Finish (full program)** | **\~5.3 years** | **\~3.5 years** | **\~2.6 years** | **\~1.8 years** |
| **Finish (core path only)** | **\~4.2 years** | **\~2.8 years** | **\~2.1 years** | **\~1.4 years** |

**Which plan to choose:** During semesters, 2–3 h/day is realistic alongside college. Use holidays for 6 h/day sprints. A mixed plan (3 h/day in term, 6 h/day for about 12 weeks of holidays a year) finishes the full program in about 3 years, or the core path in about 2.3 years. Choose the core path at 2 h/day: it finishes in about 4 years, around graduation.

### Daily study structure

| Daily time | Main track | Parallel track (Phases 1–3) | Revision | Example day |
| --- | --- | --- | --- | --- |
| 2 h | 75 min | 30 min | 15 min | 15 min Anki review → 30 min math video + exercises → 75 min Python practice |
| 3 h | 1 h 50 min | 55 min | 15 min | 15 min review → 55 min math/DSA → 50 min new topic → 60 min coding |
| 4 h | 2 h 25 min | 1 h 20 min | 15 min | 15 min review → 80 min math/DSA → 45 min new topic → 100 min coding/project |
| 6 h | 3 h 45 min | 2 h | 15 min | Morning: review + 2 h math/DSA; afternoon: 1 h new topic + 2 h 45 min project |

After Phase 3, the parallel track's time moves to the main track. Do the hardest thinking (math, new concepts) when your energy is highest, and coding when it's lower: code gives you feedback, which keeps you going.

### Theory-to-practice ratio

Across the program the split is **31% theory, 42% practice and 27% projects** (section 4). Day to day:

- **New topic days:** about 1 part theory to 2 parts practice: watch or read for 30–45 minutes, then code for 60–90 minutes.
- **Project weeks:** about 10% theory (looking things up), 90% building.
- **Never more than 45 minutes of video in a row** without writing code.

### Revision schedule

- **Daily (15 min):** Anki flashcards. Make 5–10 cards per study day: definitions, formulas, commands, "why" questions.
- **Weekly (Sunday, 1 h):** re-do one exercise from 2 weeks ago without looking at your solution; take the 10-question self-quiz; update your learning log.
- **Consolidation week (every 6th week):** a written test on the last 5 weeks, a timed coding challenge, fixing the weak spots, project polish, and one blog or LinkedIn post. During exams, this becomes 30 minutes of Anki a day.
- **Phase revision:** before each gate, re-read your notes for the whole phase and re-do its hardest lab.
- **Spaced re-use:** later projects deliberately reuse earlier skills (section 8), which is the most effective revision there is.

### Month-wise roadmap (4 h/day plan)

| Month | Main focus | Parallel track | Milestone / assessment |
| --- | --- | --- | --- |
| 1 | S1–S4 Linux, Git, setup; start S5 Python | — | Phase 0 gate (W4): first GitHub repo |
| 2 | S5 Python beginner | S9 Linear algebra | 30 CS50P/Exercism problems done |
| 3 | S5 → S6 OOP | S9 | Consolidation W12 |
| 4 | S6 → S7 Python advanced | S9 → S10 Calculus | Linear algebra mini-test |
| 5 | S7 → S8 Testing & SE | S10 | P1 started |
| 6 | S8 → S13 Data analysis | S10 → S11 Probability & stats | Phase 1 gate (W23): P1 done |
| 7 | S13; S14 SQL | S11 | P2 started |
| 8 | S14, S15 NoSQL, S16 Data engineering; Docker D1–D3 | S11 | P2 done |
| 9 | S16, S17 Networks, S18 APIs | S11 → S12 DSA | Phase 2 gate (W37) |
| 10 | S18; S19 ML foundations | S12 | P3 done (W43) |
| 11 | S19, S20 Supervised learning | S12 | Consolidation |
| 12 | S20, S21 Unsupervised | S12 | 50 DSA problems |
| 13 | S21–S23 Semi-supervised, feature engineering | S12 ends (W53) | Phase 3 gate (W53): 75 DSA problems + P2/P3 |
| 14 | S23, S24 Evaluation; start P4 | — | P4 started |
| 15 | S25 = P4; S26 NN foundations | — | Phase 4 gate (W61): P4 done |
| 16 | S27 PyTorch, S28 CNNs & CV | — | P5 started |
| 17 | S29 RNNs, S30 Transformers | — | P5 done; R1 started |
| 18 | S30, S31 NLP, S32 Generative models | — | P6 + R1 done |
| 19 | S32, S33 LLM fundamentals, S34 Prompting, S35 Fine-tuning | — | Phase 5 gate (W79) |
| 20 | S35, S36 RAG | — | R2 started; P7 started |
| 21 | S36, S37 Agents, S38 Multi-agent | — | P7 done; P8 started |
| 22 | S39 LLM evaluation; S40 Docker D4–D8 | — | Phase 6 gate (W92): P8 + R2 done |
| 23 | S40 Docker D9–D12, S41 Kubernetes | — | D12 Docker capstone |
| 24 | S41, S42 CI/CD, S43 Cloud | — | CI/CD pipeline live |
| 25 | S44 Serving, S45 Optimization | — | vLLM load-test report |
| 26 | S45, S46 MLOps, S47 Monitoring, S48 Security | — | Consolidation |
| 27 | S48, S49 System design; S50 RL | — | Phase 7 gate (W116) |
| 28 | S50, S51 Distributed training & GPUs | — | RL + DDP experiments |
| 29 | S51, S52 Research track | — | R3 started |
| 30 | S52, S53 Emerging AI | — | Phase 8 gate (W130): R3 published |
| 31 | S54 Capstones P9 + P10 | — | P9 deployed |
| 32 | S54, S55 Interviews & portfolio | — | Phase 9 gate (W137): job-ready |

### Week-wise roadmap (4 h/day plan)

Consolidation weeks (C) fall on W6, 12, 18, 24 … 132. Week ranges count calendar weeks, including the consolidation weeks inside them.

| Weeks | Main track | Parallel track | Project / assessment |
| --- | --- | --- | --- |
| W1 | S1 Computing fundamentals; start S2 | — | Install Linux/WSL2, VS Code |
| W1–3 | S2 Linux & shell; S3 Git (W3) | — | 30 Bandit levels; first repo |
| W4 | S4 Dev environment; start S5 | — | **Phase 0 gate** |
| W4–10 | S5 Python beginner | S9 starts W5 | C: W6 |
| W10–15 | S6 Python intermediate & OOP | S9 Linear algebra | C: W12 |
| W15–20 | S7 Python advanced | S9 ends W15 → S10 Calculus | C: W18; P1 started |
| W20–23 | S8 Software engineering & testing | S10 | **Phase 1 gate (W23)**: P1 done |
| W23–29 | S13 Data analysis | S10 ends W25 → S11 Probability & stats | C: W24; P2 started |
| W29–32 | S14 SQL; Docker D1–D3 | S11 | C: W30 |
| W32–34 | S15 NoSQL | S11 | P2 done |
| W34–37 | S16 Data engineering | S11 ends W37 | C: W36; **Phase 2 gate (W37)** |
| W37–39 | S17 Networks | S12 DSA starts |  |
| W39–43 | S18 APIs & backend | S12 | C: W42; P3 done (W43) |
| W43–45 | S19 ML foundations | S12 |  |
| W45–52 | S20 Supervised learning | S12 | C: W48 |
| W52–55 | S21 Unsupervised learning | S12 ends W53 | **Phase 3 gate (W53)**; C: W54 |
| W55–57 | S22 Semi/self-supervised; S23 Feature engineering | — |  |
| W57–59 | S24 Model evaluation & optimization | — |  |
| W59–61 | S25 = P4 classical ML capstone | — | C: W60; **Phase 4 gate (W61)** |
| W61–63 | S26 Neural network foundations (micrograd) | — |  |
| W63–66 | S27 PyTorch | — | C: W66 |
| W67–69 | S28 CNNs & computer vision | — | P5 |
| W69–70 | S29 RNNs, LSTMs, GRUs | — |  |
| W70–74 | S30 Attention & Transformers (build GPT) | — | C: W72; R1 |
| W74–76 | S31 NLP | — | P6 |
| W76–79 | S32 Generative models | — | C: W78; **Phase 5 gate (W79)** |
| W79–80 | S33 LLM fundamentals, tokenization, embeddings | — |  |
| W80–82 | S34 Prompt engineering & APIs | — |  |
| W82–85 | S35 Fine-tuning & PEFT | — | C: W84; R2 |
| W85–87 | S36 RAG & vector DBs | — | P7 |
| W87–89 | S37 AI agents | — | P8 |
| W89–92 | S38 Multi-agent; S39 LLM evaluation | — | C: W90; **Phase 6 gate (W92)** |
| W93–97 | S40 Docker D4–D12 (section 7) | — | C: W96; D12 capstone |
| W97–100 | S41 Kubernetes | — |  |
| W100–101 | S42 CI/CD | — |  |
| W101–104 | S43 Cloud computing | — | C: W102 |
| W105–106 | S44 Model serving & inference | — | vLLM load test |
| W106–109 | S45 Model optimization & quantization | — | C: W108 |
| W109–111 | S46 MLOps & LLMOps | — |  |
| W111–113 | S47 Monitoring; S48 Security & responsible AI | — |  |
| W113–116 | S49 System design for AI | — | C: W114; **Phase 7 gate (W116)** |
| W116–119 | S50 Reinforcement learning | — |  |
| W119–122 | S51 Distributed training & GPUs | — | C: W120 |
| W123–128 | S52 Research track | — | C: W126; R3 |
| W129–130 | S53 Emerging AI | — | **Phase 8 gate (W130)** |
| W130–136 | S54 Capstones P9 + P10 | — | C: W132 |
| W136–137 | S55 Interview & portfolio prep | — | **Phase 9 gate (W137)** |

**For other daily commitments,** keep the same order and gates and stretch the weeks by these factors: ×2.0 for 2 h/day, ×1.34 for 3 h/day, ×0.67 for 6 h/day (the phase table above has the exact weeks).

### Project milestones and assessment dates (4 h/day)

| Week | Milestone |
| --- | --- |
| W4 | Phase 0 gate; first public repo |
| W23 | P1; Phase 1 gate |
| W34 | P2 |
| W37 | Phase 2 gate (math) |
| W43 | P3 |
| W53 | Phase 3 gate (75 DSA problems) |
| W61 | P4; Phase 4 gate |
| W69 | P5 |
| W76 | P6; R1 |
| W79 | Phase 5 gate |
| W87 | P7 |
| W92 | P8; R2; Phase 6 gate |
| W97 | Docker D12 capstone |
| W116 | Phase 7 gate |
| W128 | R3 published |
| W130 | Phase 8 gate |
| W137 | P9 + P10; Phase 9 gate: industry-ready |

### Fitting it around college

- **Exam weeks:** shift a consolidation week onto them, and switch to 30 minutes of Anki a day. Never drop to zero, because the habit is the hardest thing to rebuild.
- **Semester breaks:** sprint at 6 h/day on project-heavy blocks (P4, P5, P7–P10 fit well).
- **Overlapping courses:** if your degree teaches math, DSA, OS, networks or databases this semester, use those hours for the matching subject and take its mastery check.
- **Internships (from about month 12):** apply after Phase 4 with P1–P4 in your portfolio. An internship's real-world experience is worth more than any single subject here, so pause the plan if you get one.
- **Falling behind is normal.** If you lose more than 2 weeks, don't compress: move every later date and protect the consolidation weeks.

## 12. Industry-level engineering skills and final readiness checklist

An AI/ML engineer is judged on **whether the system works for users reliably, at an acceptable cost**, not on how many models they can train. These 16 skills turn library knowledge into engineering. Each is already taught in a subject; the table shows where, and what "good" looks like.

| Skill | What "good" looks like in industry | Taught in |
| --- | --- | --- |
| Designing scalable AI architectures | You can draw the system, name the bottleneck, and explain how it behaves at 10× load | S49, P9 |
| Writing maintainable code | Small modules, typed interfaces, tests, no notebook-only logic in production | S6–S8 |
| API design | Clear resources, versioned, validated, documented, idempotent where it matters | S18 |
| Database design | Normalized where it should be, indexed for real queries, migrations under version control | S14–S15 |
| Distributed systems | You understand queues, caching, retries, consistency and partial failure | S16, S49 |
| Performance optimization | You profile before optimizing, and report before/after numbers | S7, S45, S51 |
| GPU utilization | You can estimate memory, keep GPUs busy, and choose batch size and precision | S44, S45, S51 |
| Cost optimization | You know the cost per request and per training run, and cut it with caching, routing, quantization and spot instances | S43, S44, S49 |
| Model evaluation | Offline metrics tied to business goals, sliced by segment, plus online checks after launch | S24, S39 |
| Security and privacy | Least privilege, secrets management, prompt-injection defences, PII handling | S48, D7 |
| Testing | Unit, integration, data and model tests, plus eval gates in CI | S8, S39, S42 |
| Logging and monitoring | Structured logs, metrics, traces, drift and quality monitoring, alerts tied to SLOs | S47 |
| Production deployment | Containerized, CI/CD, safe rollout (canary or shadow), quick rollback | S40–S42 |
| Reliability and scalability | Health checks, autoscaling, timeouts, fallbacks, graceful degradation | S41, S44, S49 |
| Technical documentation | READMEs, design docs, model cards, runbooks that others actually use | S8, S49 |
| System design and architectural decisions | You write down options, trade-offs and the decision (ADRs), and can defend them | S49 |

### Library user vs AI/ML engineer

Someone who only knows the libraries can train a model in a notebook. An engineer does the work around the model:

- **Frames the problem.** They choose a metric that matches what the business needs, and define what success means before training.
- **Builds for change.** Data pipelines, models and prompts are versioned, tested and reproducible, so next month's retrain is a button, not a week of archaeology.
- **Ships and operates.** The model sits behind a secure, monitored API with a rollback plan, and the engineer is the one who notices it degrading.
- **Makes trade-offs with numbers.** Accuracy vs latency vs cost vs privacy, measured, not guessed.
- **Communicates.** Design docs, honest evaluation reports and clear explanations to non-technical colleagues.

The projects in section 8 are designed to give you evidence of each of these: P4 shows framing and evaluation, P7–P8 show measured LLM systems, and P9–P10 show shipping and operating them.

### Final industry-readiness checklist

**Fundamentals**

- [ ] I can solve a new medium DSA problem in 30–40 minutes and explain its complexity (150+ problems solved).
- [ ] I can explain the maths behind linear regression, logistic regression, backprop, attention and softmax from memory.
- [ ] I write clean, typed, tested Python, and my repos pass CI.
- [ ] I'm comfortable in Linux, Git, SQL and the command line on a remote machine.

**Machine learning and deep learning**

- [ ] I have built a classical ML project end to end, with honest evaluation and explanations (P4).
- [ ] I can write a PyTorch training loop from scratch and debug a model that doesn't learn.
- [ ] I have fine-tuned a vision model and a language model, and built a GPT from scratch (P5, P6).

**LLMs and agents**

- [ ] I have shipped a RAG system with an eval suite, and I can show which change improved which metric (P7).
- [ ] I have built an agent with tools, memory, guardrails and human approval, and measured its success rate and cost (P8).
- [ ] I can decide between prompting, RAG and fine-tuning for a real problem, and justify the decision with numbers.

**Production**

- [ ] My projects run with one command (Docker Compose) and deploy through CI/CD.
- [ ] I have deployed to Kubernetes and to a cloud provider, with IaC, monitoring and alerts (P9, P10).
- [ ] I have served an LLM and load-tested it, and I know its throughput, latency and cost per 1,000 requests.
- [ ] I have threat-modelled an AI app against the OWASP LLM Top 10.

**Research and growth**

- [ ] I have reproduced at least one paper and written it up (R1–R3).
- [ ] I follow the field weekly and can explain one recent development and whether it is production-ready yet.

**Portfolio and job search**

- [ ] Six or more pinned GitHub repos with READMEs, diagrams, demos and results tables.
- [ ] Live demos (Hugging Face Spaces or similar) for at least three projects.
- [ ] Five or more technical blog posts or LinkedIn write-ups.
- [ ] A one-page resume that leads with projects and measured results.
- [ ] Three mock interviews done: coding, ML/LLM fundamentals, ML system design.
- [ ] At least one internship, open-source contribution (merged pull request) or real user of something I built.

**The last item matters most.** Real users, real teammates and real production bugs are what turn this curriculum into professional proficiency. Start applying for internships after Phase 4, contribute to an open-source AI library after Phase 6 (Hugging Face, LangChain and vLLM all label "good first issue"s), and treat every project as if someone will depend on it.
