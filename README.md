# 🧬 Variant Analysis Pipeline (Python – Mock Project)

This repository presents a mock variant analysis pipeline simulating key steps of DNA sequencing data analysis using Python. It integrates four main components:

1. **Quality Control** – Simulated FastQC
2. **Alignment** – Simulated BWA output
3. **Variant Calling** – Mocked GATK variant calling
4. **Variant Annotation** – Fake VEP annotations

> This project is meant for showcasing bioinformatics skills and pipeline logic. It uses simulated inputs and outputs.

---

## 📌 Key Features

- Python-based execution (single script)
- No real bioinformatics tools required
- Preloaded sample FASTQ and reference files
- Mock output files generated automatically

---

## ▶️ How to Run

```bash
git clone https://github.com/yourusername/variant-analysis-pipeline.git
cd variant-analysis-pipeline
pip install -r requirements.txt
python variant_pipeline.py
```

---

## 📁 Output Files

All results are saved in the `output/` folder:

- `fastqc_report.html`: Simulated QC report
- `aligned.bam`: Fake alignment output
- `variants.vcf`: Simulated variant calls
- `annotated.txt`: Fake annotated variant list

---

## 📂 Project Structure

```
variant-analysis-pipeline/
├── data/               # Input files
├── output/             # Results from each step
├── variant_pipeline.py # Main script
└── README.md
```

---

## 💡 Disclaimer

This is a mock implementation designed for portfolio/demo purposes. Tools like FastQC, BWA, GATK, and VEP are referenced but not actually used.

---

## 👩‍💻 Author

Dhanyashri A/P Guruparan  
Bioinformatics & Data Science Portfolio  
