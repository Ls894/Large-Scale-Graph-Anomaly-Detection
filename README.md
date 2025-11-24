# Overview

This project applies graph-based anomaly detection techniques to a large-scale Facebook social network (4,039 nodes and 88,234 edges).
By combining five structural features—degree centrality, clustering coefficient, PageRank, betweenness centrality, and local heterogeneity—this work identifies nodes that behave abnormally within the network structure.

# Dataset

Facebook Social Network (SNAP)
4,039 nodes
88,234 edges
Density: 0.0108
Diameter: 8

# Environment Setup

We recommend running this project in a Python 3.10+ virtual environment.

# Steps:

# 1. Create virtual environment
python3 -m venv .venv

# 2. Activate it
source .venv/bin/activate        # macOS/Linux
.\.venv\Scripts\Activate.ps1     # Windows PowerShell

# 3. Install required packages
pip install -r requirements.txt

# 4. Run the project
python src/main.py
