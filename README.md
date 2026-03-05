# Phytop Analysis Guide

A comprehensive guide for interpreting incomplete lineage sorting (ILS) and hybridization signals in phylogenomic data using Phytop.

## Overview

This repository contains documentation and resources for analyzing gene tree discordance patterns using Phytop, a tool that distinguishes between incomplete lineage sorting and hybridization/introgression in phylogenomic datasets.

## Documentation

📖 **[Complete Analysis Guide](https://github.com/svenbuerki/Gene_conflict_Phytop.git)**

Our comprehensive guide covers:

- **Introduction to gene tree discordance** - Understanding the biological processes behind conflicting phylogenetic signals
- **ASTRAL integration** - How Phytop leverages quartet support statistics from ASTRAL-III output
- **Statistical framework** - The χ² test methodology for distinguishing ILS from hybridization
- **Results interpretation** - Step-by-step guidance for analyzing Phytop output
- **Case study** - Real-world example using Balanops dataset with 47 nodes
- **Best practices** - Workflow integration and validation approaches

## Quick Start

1. Run your phylogenomic analysis with ASTRAL-III
2. Use the ASTRAL output tree as input for Phytop
3. Interpret results using our statistical guidelines
4. Follow up significant nodes with additional validation methods

## Key Features of This Guide

- ✅ **Practical examples** with real data
- ✅ **Statistical interpretation** guidelines
- ✅ **Manuscript language** suggestions
- ✅ **Validation workflows** for significant results
- ✅ **Complete bibliography** in BibTeX format

## Example Results

Our Balanops case study demonstrates:
- Analysis of 47 phylogenetic nodes
- Detection of 3 significant hybridization events (6.4%)
- Predominantly tree-like evolutionary history
- Mixed ILS/hybridization signals in specific lineages

## Related Tools

- **[Phytop](https://github.com/zhangrengang/phytop)** - The main software tool
- **[ASTRAL](https://github.com/smirarab/ASTRAL)** - Species tree inference
- **[PhyloNet](https://bioinfocs.rice.edu/phylonet)** - Network-based validation
- **[Dsuite](https://github.com/millanek/Dsuite)** - D-statistics for validation

## Citation

If you use this guide in your research, please cite:

```bibtex
@misc{phytop_guide2024,
  title={Phytop Analysis Guide: Interpreting Incomplete Lineage Sorting and Hybridization in Phylogenomic Data},
  author={[Your Name]},
  year={2024},
  url={https://github.com/yourusername/repository-name},
  note={GitHub repository}
}