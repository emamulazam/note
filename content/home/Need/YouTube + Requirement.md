# Machine Learning / AI Engineer Roadmap — Job-Ready

> **Goal:** Become employable as a Junior ML Engineer / AI Engineer, with enough software engineering, ML, deep learning, and deployment knowledge to build and explain real systems.
> 
> **Principle:** Do not optimize for completing courses. Optimize for **demonstrable skills, projects, GitHub evidence, and interview ability**.
> 
> **Target stack:** Python → NumPy/pandas → SQL → Classical ML → Deep Learning → NLP/LLMs → MLOps → Deployment → Projects → Job Applications

---

# 0. Overall Roadmap

```text
Python
  ↓
NumPy + pandas + Matplotlib
  ↓
Git + GitHub + Linux
  ↓
Math + Statistics
  ↓
Classical Machine Learning
  ↓
ML Projects
  ↓
Deep Learning
  ↓
PyTorch
  ↓
NLP + Transformers + LLMs
  ↓
APIs + Docker + Cloud
  ↓
MLOps
  ↓
Production-Level Projects
  ↓
Portfolio + Resume + Interview Preparation
  ↓
JOB APPLICATIONS
```

---

# Step 1 — Python for AI/ML

## Goal

Become comfortable enough with Python that you can read, modify, debug, and eventually write ML code without depending completely on an AI assistant.

## Learn

### Python fundamentals

- Variables
    
- Numbers
    
- Strings
    
- Boolean values
    
- Lists
    
- Tuples
    
- Sets
    
- Dictionaries
    
- `if / elif / else`
    
- `for`
    
- `while`
    
- Functions
    
- Scope
    
- Exceptions
    
- File handling
    
- Modules
    
- Packages
    
- Virtual environments
    

### Intermediate Python

- List/dictionary comprehensions
    
- `*args` / `**kwargs`
    
- Lambda functions
    
- Iterators
    
- Generators
    
- Decorators
    
- Classes
    
- OOP basics
    
- Dataclasses
    
- Type hints
    
- Context managers
    
- `pathlib`
    
- Logging
    
- Unit testing
    

## Practice

Build:

- Calculator
    
- CLI application
    
- File organizer
    
- CSV analyzer
    
- Web/API data collector
    
- Small automation tools
    

## AI-assisted learning rule

Use AI to:

- Explain code
    
- Debug code
    
- Generate exercises
    
- Review your code
    
- Explain errors
    

Do **not** let AI write every solution while you simply copy it.

## Exit requirement

You should be able to:

- Read a 200–300 line Python project
    
- Debug common errors
    
- Create a virtual environment
    
- Install dependencies
    
- Work with files and APIs
    
- Write functions/classes yourself
    
- Use Git with your projects
    

---

# Step 2 — Developer Foundations

ML engineers are software engineers who specialize in ML.

Do not skip this stage.

## Git + GitHub

Learn:

- `git init`
    
- `git clone`
    
- `git add`
    
- `git commit`
    
- `git push`
    
- `git pull`
    
- Branches
    
- Merge
    
- Rebase basics
    
- Pull requests
    
- `.gitignore`
    
- README files
    
- GitHub project structure
    

Every serious project from this point should be on GitHub.

## Linux

Learn:

- Filesystem
    
- Permissions
    
- Processes
    
- Environment variables
    
- Bash basics
    
- SSH
    
- Package management
    
- `grep`
    
- `find`
    
- `curl`
    
- `wget`
    
- `cat`
    
- `less`
    
- `chmod`
    
- `ps`
    
- `top`
    

## Development environment

Learn:

- VS Code
    
- Terminal
    
- `venv`
    
- `pip`
    
- `requirements.txt`
    
- Basic debugging
    
- Basic testing
    

## Exit requirement

You should be able to clone a GitHub project, create its environment, run it, modify it, test it, and push your changes.

---

# Step 3 — NumPy, pandas and Matplotlib

These are mandatory before serious ML.

## NumPy

Learn:

- Arrays
    
- Dimensions
    
- Shape
    
- Data types
    
- Indexing
    
- Slicing
    
- Broadcasting
    
- Vectorization
    
- Reshaping
    
- Aggregation
    
- Matrix multiplication
    
- Dot products
    
- Random numbers
    
- Basic linear algebra operations
    

### Practice

Implement:

- Vector operations
    
- Matrix multiplication
    
- Mean/variance
    
- Linear regression calculations
    
- Gradient descent
    

---

## pandas

Learn:

- Series
    
- DataFrame
    
- Reading CSV/Excel
    
- Selecting rows/columns
    
- Boolean filtering
    
- Sorting
    
- Missing values
    
- `groupby`
    
- Aggregation
    
- Merge
    
- Join
    
- Concatenation
    
- Pivot tables
    
- Datetime
    
- String operations
    
- Categorical data
    
- Duplicate handling
    

### Practice

Take messy datasets and perform:

```text
Load
 ↓
Inspect
 ↓
Clean
 ↓
Transform
 ↓
Analyze
 ↓
Visualize
```

---

## Matplotlib

Learn:

- Line plots
    
- Scatter plots
    
- Histograms
    
- Bar charts
    
- Box plots
    
- Subplots
    
- Labels
    
- Legends
    
- Figure sizing
    

Do not focus on artistic visualization. Focus on extracting information from data.

---

# Step 4 — SQL

SQL is important for ML jobs because real ML work involves databases.

## Learn

- `SELECT`
    
- `WHERE`
    
- `ORDER BY`
    
- `GROUP BY`
    
- `HAVING`
    
- `JOIN`
    
- Subqueries
    
- CTEs
    
- Window functions
    
- `CASE`
    
- Aggregations
    
- Dates
    
- NULL handling
    
- Index basics
    
- Primary/foreign keys
    

## Practice

Use:

- PostgreSQL
    
- SQLite
    

## Exit requirement

You should be able to take a database and answer analytical questions without using pandas for everything.

---

# Step 5 — Mathematics and Statistics

You do not need to become a mathematician.

You need enough mathematics to understand what your ML algorithms are doing.

## Linear Algebra

Learn:

- Scalars
    
- Vectors
    
- Matrices
    
- Tensors
    
- Vector addition
    
- Dot product
    
- Matrix multiplication
    
- Transpose
    
- Inverse
    
- Norms
    
- Linear transformations
    
- Eigenvalues/eigenvectors
    
- Basic dimensionality concepts
    

### Resource

3Blue1Brown — Linear Algebra

---

## Calculus

Learn:

- Functions
    
- Limits intuition
    
- Derivatives
    
- Partial derivatives
    
- Chain rule
    
- Gradients
    
- Integrals intuition
    
- Gradient descent
    

### Important

Understand:

```text
Function
   ↓
Derivative
   ↓
Gradient
   ↓
Direction of change
   ↓
Gradient Descent
```

---

## Probability

Learn:

- Probability
    
- Conditional probability
    
- Independence
    
- Bayes' theorem
    
- Random variables
    
- Expected value
    
- Variance
    
- Covariance
    
- Common distributions
    
- Maximum likelihood
    
- Probability density
    

---

## Statistics

Learn:

- Mean
    
- Median
    
- Variance
    
- Standard deviation
    
- Sampling
    
- Population vs sample
    
- Confidence intervals
    
- Hypothesis testing
    
- Correlation
    
- Regression
    
- Outliers
    
- Bias
    
- Variance
    

## Resources

- 3Blue1Brown
    
- StatQuest
    
- An Introduction to Statistical Learning
    

---

# Step 6 — Classical Machine Learning

## Goal

Be able to take raw data and independently build, evaluate, tune, and explain an ML model.

## Free resources

### Primary

Google Machine Learning Crash Course

[https://developers.google.com/machine-learning/crash-course](https://developers.google.com/machine-learning/crash-course)

### Concept explanations

StatQuest

[https://www.youtube.com/@statquest](https://www.youtube.com/@statquest)

### Implementation

scikit-learn documentation

[https://scikit-learn.org/stable/user_guide.html](https://scikit-learn.org/stable/user_guide.html)

### Deeper understanding

An Introduction to Statistical Learning

[https://www.statlearning.com/](https://www.statlearning.com/)

---

## Learn in this order

### Regression

- Linear Regression
    
- Multiple Linear Regression
    
- Polynomial Regression
    

### Classification

- Logistic Regression
    
- k-Nearest Neighbors
    
- Naive Bayes
    

### Tree-based models

- Decision Trees
    
- Random Forest
    
- Gradient Boosting
    
- XGBoost
    

### Other important algorithms

- SVM
    
- k-Means
    
- PCA
    

---

# Step 7 — ML Fundamentals

Do not just learn algorithms.

Learn the complete ML process.

## Data splitting

Understand:

- Training set
    
- Validation set
    
- Test set
    
- Cross-validation
    
- Data leakage
    

## Overfitting

Understand:

- Underfitting
    
- Overfitting
    
- Bias
    
- Variance
    
- Regularization
    

## Feature engineering

Learn:

- Scaling
    
- Normalization
    
- Encoding categorical variables
    
- Missing-value handling
    
- Feature selection
    
- Feature transformation
    
- Feature creation
    

## Evaluation

### Regression

- MAE
    
- MSE
    
- RMSE
    
- R²
    
- MAPE
    

### Classification

- Accuracy
    
- Precision
    
- Recall
    
- F1
    
- Confusion matrix
    
- ROC-AUC
    
- PR-AUC
    
- Log loss
    

Understand **when each metric should be used**.

---

# Step 8 — ML Pipelines

This is where you start thinking like an ML engineer.

Learn:

```text
Raw Data
   ↓
Data Validation
   ↓
Train/Test Split
   ↓
Preprocessing
   ↓
Feature Engineering
   ↓
Model
   ↓
Validation
   ↓
Hyperparameter Tuning
   ↓
Final Evaluation
   ↓
Save Model
   ↓
Deploy
```

Learn scikit-learn:

- `Pipeline`
    
- `ColumnTransformer`
    
- `StandardScaler`
    
- `OneHotEncoder`
    
- `SimpleImputer`
    
- `GridSearchCV`
    
- `RandomizedSearchCV`
    
- Cross-validation
    

---

# Step 9 — Classical ML Projects

Do not move forward until you have completed several projects.

## Project 1 — Regression

Example:

**House Price Prediction**

Requirements:

- Data cleaning
    
- EDA
    
- Feature engineering
    
- Multiple models
    
- Cross-validation
    
- Hyperparameter tuning
    
- Evaluation
    
- Error analysis
    
- README
    

---

## Project 2 — Classification

Example:

**Customer Churn Prediction**

Requirements:

- Missing-value handling
    
- Categorical features
    
- Feature engineering
    
- Logistic Regression
    
- Random Forest
    
- XGBoost
    
- Precision/Recall/F1
    
- Confusion matrix
    
- Model comparison
    

---

## Project 3 — End-to-End ML

Build:

```text
Dataset
 ↓
Training pipeline
 ↓
Saved model
 ↓
FastAPI API
 ↓
Docker
 ↓
Cloud deployment
```

This project is more valuable for your portfolio than ten notebook-only projects.

---

# Step 10 — Deep Learning

## Framework

Learn **PyTorch**.

Do not try to learn TensorFlow and PyTorch simultaneously.

## Learn

- Tensors
    
- Autograd
    
- Datasets
    
- DataLoaders
    
- Training loops
    
- Validation loops
    
- Optimizers
    
- Loss functions
    
- Backpropagation
    
- Learning rate
    
- Batch size
    
- Epochs
    
- Dropout
    
- Batch normalization
    
- Weight initialization
    
- Checkpointing
    

---

# Step 11 — Neural Networks

Understand:

- Perceptron
    
- MLP
    
- Activation functions
    
- ReLU
    
- Sigmoid
    
- Softmax
    
- Forward propagation
    
- Backpropagation
    
- Gradient descent
    

Implement a neural network:

1. With NumPy
    
2. With PyTorch
    

---

# Step 12 — Computer Vision

Learn:

- CNN
    
- Convolution
    
- Padding
    
- Stride
    
- Pooling
    
- Image augmentation
    
- Transfer learning
    

Build:

### Project

**Image Classification System**

Requirements:

- Dataset preparation
    
- CNN
    
- Transfer learning
    
- Training/validation curves
    
- Evaluation
    
- Error analysis
    
- API
    
- Docker
    

---

# Step 13 — NLP

Learn:

- Text preprocessing
    
- Tokenization
    
- Vocabulary
    
- Embeddings
    
- Word embeddings
    
- Sequence models
    
- RNN
    
- LSTM
    
- Attention
    

Then move quickly toward Transformers.

---

# Step 14 — Transformers and LLMs

## Learn

- Attention
    
- Self-attention
    
- Query
    
- Key
    
- Value
    
- Positional encoding
    
- Encoder
    
- Decoder
    
- Transformer architecture
    
- Tokenization
    
- Embeddings
    
- Context window
    
- Pretraining
    
- Fine-tuning
    
- Instruction tuning
    
- Inference
    

## Resources

### Stanford CS25

Study the freely available lectures.

### Andrej Karpathy

Study:

- Neural networks from scratch
    
- GPT from scratch
    
- nanoGPT
    

Do not just watch.

Implement.

---

# Step 15 — LLM Engineering

For current AI engineering jobs, learn how to build applications around existing foundation models.

## Learn

- Open-source LLMs
    
- Hugging Face
    
- Transformers
    
- Tokenizers
    
- Embeddings
    
- Vector databases
    
- Semantic search
    
- RAG
    
- Prompt engineering
    
- Structured output
    
- Tool calling
    
- Function calling
    
- Evaluation
    
- Guardrails
    
- Context management
    

## Build

### Project — RAG System

Example:

**Japanese Learning Assistant**

```text
Documents
   ↓
Chunking
   ↓
Embeddings
   ↓
Vector Database
   ↓
Retriever
   ↓
LLM
   ↓
Answer
```

Include:

- Evaluation dataset
    
- Retrieval evaluation
    
- Answer evaluation
    
- API
    
- UI
    
- Docker
    

---

# Step 16 — Recommender Systems

Learn after classical ML fundamentals.

## Learn

- Collaborative filtering
    
- Content-based filtering
    
- User-item matrices
    
- Similarity
    
- Matrix factorization
    
- Embeddings
    
- Ranking
    
- Recommendation metrics
    

Build:

**Movie Recommendation System**

Then improve it with:

- Content features
    
- Collaborative filtering
    
- Hybrid recommendation
    

---

# Step 17 — Software Engineering for ML

This separates a notebook user from an ML engineer.

Learn:

- Clean code
    
- Project structure
    
- Type hints
    
- Unit tests
    
- Integration tests
    
- Logging
    
- Configuration
    
- Environment variables
    
- Error handling
    
- Documentation
    
- Code review
    
- API design
    

Learn:

- FastAPI
    
- Pydantic
    
- pytest
    

---

# Step 18 — APIs

Learn FastAPI.

Build:

```text
POST /predict
GET /health
GET /model-info
```

Understand:

- HTTP
    
- REST
    
- JSON
    
- Request/response
    
- Status codes
    
- Validation
    
- Authentication basics
    

---

# Step 19 — Docker

Learn:

- Images
    
- Containers
    
- Dockerfile
    
- Docker Compose
    
- Volumes
    
- Networks
    
- Environment variables
    
- Docker Hub
    

Containerize:

1. ML API
    
2. Deep learning API
    
3. RAG application
    

---

# Step 20 — Cloud

Choose **one** cloud first.

Recommended:

- AWS
    

Learn enough to deploy real applications.

## Learn

- EC2
    
- S3
    
- IAM
    
- Basic networking
    
- Docker deployment
    
- Cloud logging
    
- Environment configuration
    

Do not attempt to learn every AWS service.

---

# Step 21 — MLOps

Learn the basic production lifecycle:

```text
Data
 ↓
Training
 ↓
Experiment Tracking
 ↓
Model Registry
 ↓
Deployment
 ↓
Monitoring
 ↓
Retraining
```

## Learn

- MLflow
    
- Experiment tracking
    
- Model versioning
    
- Data versioning
    
- Model versioning
    
- CI/CD basics
    
- Monitoring
    
- Model drift
    
- Data drift
    

Optional later:

- Kubernetes
    
- Airflow
    
- Kubeflow
    

Do not prioritize Kubernetes before you can deploy a simple ML service.

---

# Step 22 — DSA for Interviews

You do not need competitive-programming-level DSA.

Learn:

## Data structures

- Arrays
    
- Strings
    
- Hash tables
    
- Stack
    
- Queue
    
- Linked list
    
- Trees
    
- Binary search trees
    
- Heap
    
- Graph basics
    

## Algorithms

- Sorting
    
- Binary search
    
- Two pointers
    
- Sliding window
    
- Recursion
    
- BFS
    
- DFS
    
- Dynamic programming basics
    

## Target

Solve approximately:

```text
100–150 well-selected problems
```

Focus on understanding patterns rather than memorizing solutions.

---

# Step 23 — System Design for ML

Learn basic ML system design.

Understand:

- Batch vs real-time inference
    
- Training pipeline
    
- Feature store concept
    
- Model serving
    
- Caching
    
- Queues
    
- Databases
    
- Vector databases
    
- Monitoring
    
- Scaling
    
- Latency
    
- Throughput
    
- Cost
    
- Reliability
    

Practice designing:

- Recommendation system
    
- Fraud detection system
    
- Image classification API
    
- RAG system
    
- LLM chatbot
    

---

# Step 24 — Portfolio

You do **not** need 30 projects.

Build **4–6 strong projects**.

## Project 1 — Classical ML

End-to-end tabular ML system.

## Project 2 — Deep Learning

Computer vision or NLP system.

## Project 3 — LLM/RAG

Production-style RAG application.

## Project 4 — ML API

Deploy a trained model using:

```text
PyTorch/scikit-learn
+
FastAPI
+
Docker
+
Cloud
```

## Project 5 — Recommender System

Build and evaluate a recommendation engine.

## Project 6 — Advanced project

Choose something aligned with jobs you want.

---

# Step 25 — Every Portfolio Project Must Have

```text
README.md
Architecture diagram
Problem definition
Dataset description
Data preprocessing
EDA
Model choice
Training procedure
Evaluation
Experiments
Error analysis
Results
How to run
API documentation
Docker instructions
Limitations
Future improvements
```

Your GitHub should demonstrate **engineering ability**, not just Jupyter notebooks.

---

# Step 26 — Kaggle

Use Kaggle to develop practical ML ability.

Start with:

- Titanic
    
- House Prices
    
- Beginner tabular competitions
    

Then move to:

- Classification
    
- Regression
    
- NLP
    
- Computer vision
    

For each competition:

```text
Baseline
 ↓
EDA
 ↓
Feature engineering
 ↓
Model
 ↓
Validation
 ↓
Experiment
 ↓
Improvement
 ↓
Final analysis
```

Do not blindly copy public notebooks.

---

# Step 27 — Research / Paper Reading

After you have solid fundamentals, start reading papers.

Start with accessible papers related to:

- CNNs
    
- ResNet
    
- Attention
    
- Transformers
    
- BERT
    
- GPT
    
- RAG
    
- LoRA
    
- Retrieval systems
    

For every paper:

```text
Problem
 ↓
Previous limitation
 ↓
Proposed method
 ↓
Architecture
 ↓
Training
 ↓
Results
 ↓
Implementation
```

Implement selected papers rather than trying to implement everything.

---

# Step 28 — Job Preparation

Start preparing for jobs **before** finishing the entire roadmap.

Do not wait until:

> "I have learned everything."

You never will.

## Resume

Create a one-page technical resume.

Prioritize:

- Projects
    
- Technical skills
    
- Results
    
- GitHub
    
- Deployment experience
    
- Relevant education
    
- Certifications only when useful
    

Avoid listing 50 technologies you barely know.

---

# Step 29 — Interview Preparation

Prepare four categories.

## Python

- Data structures
    
- Functions
    
- OOP
    
- Debugging
    
- Algorithms
    
- File handling
    
- APIs
    

## ML

Be able to explain:

- Linear regression
    
- Logistic regression
    
- Decision trees
    
- Random forest
    
- Gradient boosting
    
- Overfitting
    
- Regularization
    
- Cross-validation
    
- Data leakage
    
- Precision/Recall
    
- ROC-AUC
    
- Feature engineering
    

## Deep Learning

Explain:

- Neural networks
    
- Backpropagation
    
- Optimizers
    
- CNN
    
- Transformers
    
- Attention
    
- Embeddings
    
- Fine-tuning
    

## ML System Design

Explain:

- How to deploy a model
    
- How to monitor it
    
- How to handle millions of predictions
    
- How to update models
    
- How to build a RAG system
    
- How to reduce inference cost
    

---

# Step 30 — When to Start Applying

Do **not** wait for the end of the roadmap.

Start applying when you have:

```text
✓ Strong Python
✓ NumPy/pandas
✓ SQL
✓ Classical ML
✓ scikit-learn
✓ 2 strong ML projects
✓ Git/GitHub
✓ Basic FastAPI
✓ Basic Docker
✓ Basic DSA
```

At this point, target:

- ML Intern
    
- AI Intern
    
- Junior ML Engineer
    
- Junior AI Engineer
    
- Data/ML Engineer Intern
    
- Python Developer with ML responsibilities
    
- AI Application Engineer
    

Then continue learning while applying.

---

# Step 31 — Job-Ready Minimum Standard

Before calling yourself **job-ready**, you should be able to do this without blindly following a tutorial:

```text
Raw dataset
     ↓
EDA
     ↓
Data cleaning
     ↓
Feature engineering
     ↓
Train/validation/test split
     ↓
Baseline
     ↓
Multiple ML models
     ↓
Cross-validation
     ↓
Hyperparameter tuning
     ↓
Evaluation
     ↓
Error analysis
     ↓
Save model
     ↓
FastAPI
     ↓
Docker
     ↓
Deploy
     ↓
Monitor
```

You should also be able to explain **why** you made each decision.

---

# Step 32 — AI-Assisted Learning Rules

AI is a tool, not your replacement.

## Use AI for

- Explanations
    
- Debugging
    
- Code review
    
- Generating exercises
    
- Documentation
    
- Brainstorming
    
- Test generation
    
- Refactoring suggestions
    
- Understanding unfamiliar code
    

## Do not use AI to

- Complete every assignment
    
- Generate projects you don't understand
    
- Write your entire portfolio
    
- Solve every coding problem immediately
    
- Replace mathematical understanding
    
- Replace debugging practice
    

## The rule

```text
Try yourself
    ↓
Get stuck
    ↓
Investigate
    ↓
Ask AI for a hint
    ↓
Try again
    ↓
Ask for explanation
    ↓
Implement yourself
```

---

# Step 33 — Weekly Study System

Use a 6-day cycle.

## Day 1–4

Learn new material.

```text
Theory
+
Code
+
Exercises
```

## Day 5

Build something without following a tutorial.

## Day 6

Review:

- What did I learn?
    
- Can I explain it?
    
- Can I implement it?
    
- What mistakes did I make?
    
- What should I revisit?
    

## Day 7

Rest or light review.

---

# Step 34 — Learning Ratio

As you progress, reduce passive learning.

### Beginning

```text
40% learning
60% coding
```

### Classical ML

```text
30% theory
70% implementation
```

### Deep Learning

```text
30% theory
70% implementation
```

### Job preparation

```text
20% learning
80% projects / coding / interviews
```

---

# Step 35 — Resource Strategy

Do not collect courses endlessly.

For each major subject choose:

```text
1 Primary Resource
1 Supplementary Resource
1 Documentation Source
1 Project
```

Example:

### Classical ML

```text
Primary:
Google ML Crash Course

Supplement:
StatQuest

Documentation:
scikit-learn

Project:
End-to-end classification system
```

### Deep Learning

```text
Primary:
PyTorch tutorials

Supplement:
Andrej Karpathy

Documentation:
PyTorch docs

Project:
Image/NLP classifier
```

### Transformers

```text
Primary:
Hugging Face course

Supplement:
Stanford CS25 / Karpathy

Documentation:
Hugging Face docs

Project:
RAG / LLM application
```

---

# Step 36 — Final Skill Stack

By the time you apply seriously for ML/AI engineering positions, aim for:

```text
Programming
├── Python
├── SQL
├── Bash
└── Git

Data
├── NumPy
├── pandas
└── Matplotlib

Math
├── Linear Algebra
├── Calculus
├── Probability
└── Statistics

Classical ML
├── scikit-learn
├── Regression
├── Classification
├── Trees
├── Boosting
├── Clustering
├── Feature Engineering
└── Model Evaluation

Deep Learning
├── PyTorch
├── Neural Networks
├── CNN
└── Transformers

AI/LLM
├── Hugging Face
├── Embeddings
├── Vector Databases
├── RAG
├── Fine-tuning
└── LLM Evaluation

Engineering
├── FastAPI
├── Docker
├── Testing
├── Logging
└── REST APIs

MLOps
├── MLflow
├── CI/CD
├── Model Versioning
├── Monitoring
└── Cloud

Interview
├── DSA
├── ML Theory
├── Python
└── ML System Design
```

---

# Final Roadmap

```text
PHASE 1
Python
Git
Linux
                    ↓
PHASE 2
NumPy
pandas
Matplotlib
SQL
                    ↓
PHASE 3
Math
Probability
Statistics
                    ↓
PHASE 4
Classical ML
scikit-learn
Evaluation
Pipelines
                    ↓
PHASE 5
2–3 Serious ML Projects
Kaggle
                    ↓
PHASE 6
PyTorch
Deep Learning
                    ↓
PHASE 7
Computer Vision / NLP
                    ↓
PHASE 8
Transformers
LLMs
RAG
Hugging Face
                    ↓
PHASE 9
FastAPI
Docker
Cloud
MLOps
                    ↓
PHASE 10
4–6 Portfolio Projects
                    ↓
PHASE 11
DSA
ML Interviews
System Design
                    ↓
PHASE 12
JOB APPLICATIONS
                    ↓
PHASE 13
Continue learning while working
```

# The Actual Objective

The objective is **not**:

> Finish every resource.

The objective is:

> **Become capable of taking an ML/AI problem, writing the code, training the model, evaluating it, deploying it, explaining your decisions, and maintaining the system.**

If a course slows that objective down, replace the course.

If a topic does not contribute to that objective yet, postpone it.

If you cannot build something without a tutorial, you have not mastered the topic yet.

**Build → Measure → Explain → Deploy → Repeat.**