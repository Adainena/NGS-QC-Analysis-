# NGS Quality Control Analysis Tool

## Overview
This tool performs quality control analysis on Next Generation Sequencing (NGS) data, focusing on metrics relevant to clinical genomics applications. It processes FASTQ files to generate comprehensive QC reports with visualizations.

## Features
- FASTQ file quality assessment
- Per-base sequence quality analysis
- GC content distribution
- Read length distribution
- Quality score distribution
- Automated report generation
- ISO15189-compliant quality metrics

## Installation
```bash
# Clone the repository
git clone https://github.com/[your-username]/bioinformatics-portfolio.git
cd bioinformatics-portfolio/ngs-qc-analysis

# Install required packages
pip install -r requirements.txt
```

## Usage
```python
from src.qc_analyzer import FastqQualityAnalyzer

# Initialize analyzer with your FASTQ file
analyzer = FastqQualityAnalyzer("path_to_your_fastq_file.fastq")

# Run analysis
analyzer.analyze_file()

# Generate reports
analyzer.generate_reports("output_directory")
```

## Project Structure
- `src/`: Source code for the QC analysis tool
- `tests/`: Unit tests
- `docs/`: Documentation and user guides
- `requirements.txt`: Required Python packages

## Development Status
This project is currently under active development. Features and documentation will be updated regularly.
