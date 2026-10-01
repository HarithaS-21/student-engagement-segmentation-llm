# student-engagement-segmentation-llm
"Student engagement segmentation using K-Means clustering and RAG-based LLM course guide."
# Student Engagement Segmentation & RAG LLM Course Guide

An end-to-end Machine Learning and Generative AI project that segments student learning behavior using unsupervised clustering algorithms and provides an interactive Retrieval-Augmented Generation (RAG) course assistant.

📌 Project Overview
This project consists of two core components:

Student Engagement Segmentation: Analyzes video interaction and quiz metrics (Watch Time, Completion Rate, Replays, Pauses, Quiz Scores) using K-Means Clustering and Principal Component Analysis (PCA) to categorize students into distinct engagement tiers (High, Medium, Low).

AI Course Assistant (RAG Pipeline): Builds a Retrieval-Augmented Generation pipeline using FAISS vector search, SentenceTransformers, and Hugging Face LLMs to answer student questions based on lecture notes.

🛠️ Tech Stack & Libraries
Language: Python

Data Processing & Analysis: pandas, numpy

Machine Learning & Clustering: scikit-learn (StandardScaler, KMeans, PCA, Silhouette Score)

Data Visualization: matplotlib, seaborn

Vector Search & Embeddings: faiss-cpu, sentence-transformers (all-MiniLM-L6-v2)

LLM Integration & Interface: Hugging Face Inference API, gradio

🔑 Key Features
Data Preprocessing & Scaling: Standardized feature distributions for reliable distance metrics in clustering.

Optimal Cluster Determination: Applied the Elbow Method to select K=3 as the optimal number of segments.

Dimensionality Reduction: Utilized 2D PCA projection to visualize multi-dimensional student clusters.

Semantic Vector Search: Chunked lecture transcripts and indexed text embeddings into a FAISS vector database for similarity search.

Interactive Chatbot Interface: Integrated a Gradio web app allowing users to query course material interactively.
