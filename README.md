# Social Network Analysis - Assignments 📊🔍

This repository contains four assignments for the **CSL7390 - Social Network Analysis** course. The assignments involve **graph analysis, network modeling, information diffusion simulations, and community detection** using **Python, NetworkX, Pandas, and Matplotlib**.

## **Assignment 1: Network Metrics & Centrality Analysis**
**Objective:** Analyze an **undirected social network dataset** (3000-10,000 nodes) using fundamental **graph-theoretic properties**.

### **Tasks Performed**
✅ **Loaded and processed** a large **social network dataset** from [SNAP](https://snap.stanford.edu/data/index.html).  
✅ Computed **graph properties**:  
   - Node count, Edge count, Average Degree  
   - Degree Distribution  
   - Number of Triangles  
   - Network Diameter, Number of Components  
   - Largest Connected Component Size  
✅ Calculated **centrality measures**:  
   - **Degree Centrality, Betweenness, Eigenvector, Katz, PageRank**  
✅ Identified **k-cores** and **maximum & minimum cliques**.  
✅ **Visualized degree distributions** and **centrality histograms** using Matplotlib.

---

## **Assignment 2: Signed Networks, Random Graphs & Fuzzy Networks**
**Objective:** Work with **signed networks**, **random graph models**, and **fuzzy granular networks**.

### **Tasks Performed**
✅ Processed **signed network data** ([Wiki-RfA](https://snap.stanford.edu/data/wiki-RfA.html))  
✅ **Counted balanced & unbalanced cycles** in signed networks  
✅ Generated **Random Graphs** using:
   - **Fixed Nodes (N) and Edges (L)**
   - **Erdős-Rényi (N, p) Model**  
✅ Created **Scale-Free Graphs** (Barabási-Albert Model) and **plotted degree distributions** (log-log scale).  
✅ Converted **Random Graphs into Fuzzy Granular Networks** using **custom fuzzy membership function**.  

---

## **Assignment 3: Information Diffusion in Social Networks**
**Objective:** Simulate **information spread** using **Independent Cascade Model (ICM)** and **Linear Threshold Model (LTM)**.

### **Tasks Performed**
✅ **Generated a Barabási-Albert Graph (1000-10,000 nodes)**  
✅ Implemented **Monte Carlo simulations (10,000 iterations) for ICM & LTM diffusion**  
✅ **ICM Model**:  
   - Randomly activated **30 seed nodes**, simulated information spread  
   - Used **propagation probability between 0.05-0.15**  
✅ **LTM Model**:  
   - Activated **30 nodes**, used **random threshold (b, θ)** for diffusion  
✅ **Seed Selection Problem**:  
   - Used **Greedy Algorithm to find 20 most influential nodes**  
   - Compared information spread between **Greedy-selected nodes vs. Random nodes**  
✅ **Plotted influence spread over multiple runs**  

---

## **Assignment 4: Community Detection in Temporal Networks**
**Objective:** Apply **community detection algorithms** on **time-evolving networks**.

### **Tasks Performed**
✅ Used **a temporal dataset** where snapshots were taken at **one-month intervals**  
✅ Applied **four community detection algorithms**:
   - **Modularity-Based Community Detection**  
   - **Girvan-Newman Algorithm**  
   - **Label Propagation Algorithm**  
   - **Louvain Algorithm**  
✅ Evaluated **community structures** using **Normalized Mutual Information (NMI)**  
✅ **Visualized detected communities over time**  

---

## **How to Run the Assignments 🚀**
1. **Install dependencies**  
   ```bash
   pip install networkx numpy pandas matplotlib seaborn
