---
title: "HELM-BERT: Peptide Language Model"
date: 2025-01-01
status: active
tags:
  - Deep Learning
  - NLP
  - Peptides
  - Drug Discovery
description: "Encoder-only transformer pretrained on HELM notation for topology-aware representations of chemically modified and macrocyclic peptides."
links:
  - label: Paper (arXiv)
    url: https://arxiv.org/abs/2512.23175
  - label: GitHub
    url: https://github.com/clinfo/HELM-BERT
  - label: HuggingFace
    url: https://huggingface.co/Flansma/helm-bert
featured: true
---

## Overview

HELM-BERT is an encoder-only transformer pretrained directly on HELM (Hierarchical Editing Language for Macromolecules) notation, which specifies monomer identity and explicit covalent connectivity. The resulting representations natively encode chemical modification and macrocyclic topology — a regime where atom-level (SMILES) and protein-sequence models both fall short.

## Key Features

- Pretrained on HELM notation, preserving macrocyclic topology in a linearly accessible form
- Supports non-canonical residues, chemical modifications, and explicit crosslinks
- Fine-tunable for downstream tasks (membrane permeability, peptide–protein interaction)

## Results

Top mean performance on cyclic peptide membrane permeability (random split R² = 0.668; retained under Murcko scaffold split), exceeding external pretrained SMILES-based encoders. Competitive on peptide–protein interaction prediction across Propedia and ChEMBL benchmarks.
