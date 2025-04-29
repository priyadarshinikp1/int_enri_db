# Multiomic Integration App

## Overview
The **Multiomic Integration App** is a Streamlit-based tool designed to help integrate genomic, transcriptomic, and proteomic data in a user-friendly way. The app combines data from various biological databases to build a network that connects **genes**, **proteins**, **metabolites**, **enzymes**, **transcription factors (TFs)**, **pathways**, and **diseases**. This can be useful for researchers interested in understanding complex biological interactions and how different molecular layers (genes, proteins, etc.) come together.

### Databases Used
We’ve integrated data from several well-known biological databases:
1. **KEGG** (Kyoto Encyclopedia of Genes and Genomes)
2. **Reactome**
3. **HMDB** (Human Metabolome Database)
4. **Kinase**
5. **JNS** (Transcription Factor Database)
6. **DISGENET** (Disease Gene Association Database)
7. **(Additional database 1)** (e.g., STRING or BioGRID)
8. **(Additional database 2)** (e.g., Ensembl or UniProt)

These databases allow the app to create a network of interactions between genes, proteins, metabolites, enzymes, transcription factors, pathways, and diseases.

### Features
- **Integration of Omic Data**: The app combines genomic, transcriptomic, and proteomic data to create a unified analysis.
- **Network Construction**: Using data from the selected databases, the app builds a network that shows the relationships between genes, proteins, metabolites, and more.
- **Association Table**: A final table is generated that summarizes all the key associations and interactions identified during the integration process.

### How It Works
1. **Input Data**: You can upload genomic, transcriptomic, and proteomic datasets in various formats (like CSV or TSV).
2. **Choose Databases**: The app will pull relevant information from the chosen databases (e.g., KEGG, Reactome, etc.).
3. **Run Integration**: The app processes the data and integrates it into a network.
4. **View Results**: Once integration is complete, you can visualize the network and explore the results.
5. **Download the Table**: A final table of associations is generated and can be downloaded for further analysis.

### Example Output
The app generates a table that looks something like this:

| Gene | Protein | Metabolite | Enzyme | Transcription Factor (TF) | Pathway | Disease |
|------|---------|------------|--------|---------------------------|---------|---------|
| GeneA | ProteinX | Metabolite1 | Enzyme1 | TF1 | Pathway1 | Disease1 |
| GeneB | ProteinY | Metabolite2 | Enzyme2 | TF2 | Pathway2 | Disease2 |

