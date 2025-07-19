# 🧬 Variant Analysis Pipeline

![Python](https://img.shields.io/badge/Built%20With-Python-blue?style=flat&logo=python)
![Project Status](https://img.shields.io/badge/Status-Demo%20Project-success?style=flat)

This repository presents a mock variant analysis pipeline simulating key steps of DNA sequencing data analysis using Python. It integrates four main components:

1. **Quality Control** – Simulated FastQC
2. **Alignment** – Simulated BWA output
3. **Variant Calling** – Mocked GATK variant calling
4. **Variant Annotation** – Mock VEP annotations

---

## 📌 Key Features

- ✅ **Single Python script** to simulate the full workflow
- 📁 **Pre-loaded input files** (sample FASTQ and reference genome)
- 🧪 **Simulated output files** mimicking real tools like FastQC, BWA, GATK, and VEP
- 🧰 **No external dependencies** (easy to run, no installations needed)
- 📦 **Clean project structure** ready for GitHub portfolio
- 👩‍💻 **Beginner-friendly** and useful for learning how pipelines work

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
