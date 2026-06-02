AI Convergence–Brokerage Network Analysis

This repository contains the code used to investigate how technological convergence and brokerage structures shape the emergence of high-quality innovation within the global artificial intelligence (AI) innovation ecosystem.

Using AI patents from G20 economies (2018–2024), the study integrates machine-learning-based patent quality identification with temporal IPC co-occurrence network analysis to examine the relationship between technological convergence, brokerage positions, and future high-quality innovation.

Study Overview

The analytical workflow consists of:

AI Patent Retrieval
AI-related patents identified using IPC classifications and keyword-based search strategies.
Coverage includes G20 economies from 2018–2024.
Patent Quality Identification
Random Forest classifier trained on 18,074 AI patents (2018–2020).
High-quality patents identified from the 2021–2024 patent population.
IPC Co-occurrence Network Construction
Nodes represent IPC technology domains.
Edges represent co-occurrence relationships within patent documents.
Convergence Analysis
Network density
Clustering coefficient
Community structure (modularity)
Brokerage Analysis
Betweenness centrality
Identification of brokerage technologies
Innovation Concentration Analysis
Distribution of high-quality patents across IPC domains
Brokerage threshold effects
Pareto/Lorenz concentration analysis
Validation and Robustness Testing
Temporal validation: Brokerage(t) → High-Quality Innovation(t+1)
Degree-preserving randomized network analysis
Z-score significance testing
Main Findings
AI innovation networks exhibit increasing technological convergence.
A small number of brokerage technologies act as structural bridges connecting diverse technological communities.
High-quality innovation is strongly concentrated within brokerage IPC domains.
Brokerage position predicts future high-quality patent production.
Empirical convergence and brokerage structures are significantly stronger than expected under randomized network organization.
