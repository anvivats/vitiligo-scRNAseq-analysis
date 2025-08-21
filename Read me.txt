# 🧬 Cellular and Cytokine Landscape of Vitiligo Lesions

This repository contains a single-cell RNA sequencing (scRNA-seq) analysis of lesional and non-lesional skin from vitiligo patients using dataset [GSE203262](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE203262). The project explores cellular composition, immune activation, cytokine expression, and intercellular communication in vitiligo skin.

---

## 📖 Abstract

Vitiligo is an autoimmune skin disorder characterized by melanocyte loss. To dissect its cellular and cytokine landscape, we analyzed single-cell RNA-seq data (GSE203262) from matched lesional and non-lesional skin. Among 1,497 high-quality cells, eight distinct clusters were identified, with lesional skin dominated by stress keratinocytes (~85%) expressing CXCL10, S100A9, and CRIP1. Lesional samples showed increased CXCR3 ligands (CXCL9–11), interferon-stimulated genes (ISG15), and MHC-I molecules, with depleted melanocyte markers. CD8⁺ T cells were reduced, possibly due to exhaustion or timing. Network analysis revealed disrupted immune signaling centered on keratinocyte stress and monocyte pathways. These findings highlight epithelial–immune crosstalk and CXCR3 signaling as key features of vitiligo pathogenesis.

---

## 📁 Project Contents

- `vitiligo_analysis.ipynb` – Jupyter Notebook with full pipeline   
- `requirements.txt` – Python packages needed  
- `README.md` – Project overview and usage instructions

---

## 🔬 Main Findings

- Lesional skin is dominated by **stress keratinocytes** (~85%) expressing KRT6A, CXCL10, and S100A9  
- **CXCR3 chemokines (CXCL9–11)** are elevated in lesional skin  
- **Melanocytes are depleted**, consistent with depigmentation  
- **CD8⁺ T cells are reduced** in lesional skin, despite chemokine signaling  
- **Network analysis** shows loss of coordinated immune–epithelial interactions  
- **Trajectory analysis** suggests keratinocytes transition from basal to stress phenotype

---

## ⚠ Limitations

- Small sample size (~1,500 cells from GSE203262)  
- Some genes (especially metabolic) were filtered out or undetected  
- Cell-cell communication modeling was simplified  
- No protein-level validation (e.g., IHC, flow cytometry)

---

## 🧪 Tools Used

- Python, Scanpy, Seaborn, Matplotlib, NetworkX, Scikit-learn, Pandas

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/vitiligo-scRNAseq.git
cd vitiligo-scRNAseq
