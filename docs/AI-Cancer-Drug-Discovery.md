# 🚀 AI-Powered Cancer Drug Discovery  

## 🔬 Project Overview  
Cancer remains one of the deadliest diseases worldwide, with many treatments facing **toxicity issues, drug resistance, and high development costs**. Natural compounds from **plant-derived metabolites** have shown promising anti-cancer properties, but their computational validation remains a challenge.  

This project aims to develop an **AI-powered Nextflow pipeline** for discovering **plant-based anti-cancer drugs** by integrating **genomic analysis, molecular docking (AutoDock Vina), AI-driven compound ranking, and Power BI visualization**. The outcome will be an **open-source workflow** that can accelerate early-stage drug discovery and contribute to personalized medicine.

## 🎯 Objectives  
🔹 **Identify Cancer-Related Drug Targets** → Extract genomic data, analyze oncogenic pathways, and select viable drug targets.  
🔹 **Screen Plant-Based Metabolites from PubChem** → Retrieve bioactive compounds and assess their drug-likeness.  
🔹 **Perform Molecular Docking & MD Simulations** → Evaluate ligand-protein binding affinities using **AutoDock Vina**.  
🔹 **Train AI Models for Compound Ranking** → Implement QSAR-based **machine learning** models to predict the most promising drugs.  
🔹 **Develop an Interactive Power BI Dashboard** → Visualize docking results, AI rankings, and ADMET properties.  

## 🛠️ Methodology  
1️⃣ **Bioinformatics Analysis**:  
   - Extract cancer-related gene expression data from **GEO/TCGA**.  
   - Identify **differentially expressed genes (DEGs)** and map to **KEGG cancer pathways**.  

2️⃣ **Compound Screening**:  
   - Retrieve **plant-based metabolites from PubChem**.  
   - Perform **drug-likeness and ADMET analysis** using **SwissADME & RDKit**.  

3️⃣ **Molecular Docking & MD Simulations**:  
   - Prepare protein structures from **PDB or homology modeling (SwissModel, AlphaFold)**.  
   - Perform **AutoDock Vina docking simulations** to assess binding affinity.  
   - Conduct **molecular dynamics (MD) simulations** using **GROMACS** for stability assessment.  

4️⃣ **AI-Based Drug Ranking**:  
   - Train **QSAR models** using **Random Forest, XGBoost, and Deep Learning**.  
   - Rank compounds based on AI-driven **predictions of anti-cancer activity**.  

5️⃣ **Power BI Visualization**:  
   - Build **interactive charts, heatmaps, and docking visualizations**.  
   - Present **AI-driven compound rankings and ADMET insights**.  

## 🌟 Expected Outcome  
✔ **List of top-ranked plant-based compounds** with high anti-cancer potential.  
✔ **Validated molecular docking & MD results** for stable interactions.  
✔ **AI-powered ranking system** to identify promising drug candidates.  
✔ **Power BI dashboard for visualization & decision-making in drug discovery**.  
✔ **A fully automated Nextflow pipeline**, available as an **open-source workflow**.  

## 👨‍💻 Team Members & Contributions  
👨‍🔬 **Sahil Shelote** – *Bioinformatics Lead*  
- Handles **genomic data extraction, KEGG pathway mapping, and drug target identification**.  
- Works on **Nextflow implementation for genomic data processing**.  

🧪 **Kunal Pradhan** – *Cheminformatics & Molecular Docking Specialist*  
- Responsible for **PubChem compound screening, drug-likeness evaluation, and AutoDock molecular docking simulations**.  
- Performs **molecular dynamics simulations (MD) using GROMACS**.  

📊 **Sayali Shelote** – *AI & Visualization Expert*  
- Develops **QSAR-based AI models** to rank compounds based on docking results.  
- Builds **Power BI dashboard** for visualization of results and insights.  

## 🔗 GitHub Repository  
📌 **GitHub Link:** [HACKATHON_2025](https://github.com/mbxss25/HACKATHON_2025)  

## 📅 Hackathon Participation  
This project will be developed as part of the **nf-core Hackathon (March 24-26, 2025)**. We welcome contributions from the community and researchers in bioinformatics, cheminformatics, and AI-driven drug discovery.  

---

