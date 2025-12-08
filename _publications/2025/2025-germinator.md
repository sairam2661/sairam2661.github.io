---
title: "Bootstrapping Fuzzers for Compilers of Low-Resource Language Dialects Using Language Models"
date: 2025-08-02 00:01:00 +0800
selected: false
pub: "arXiv Preprint"
pub_date: "2025"
abstract: >-
  Modern extensible compiler frameworks-such as MLIR-enable rapid creation of domain-specific language dialects. This flexibility, however, makes correctness harder to ensure as the same extensibility that accelerates development also complicates maintaining the testing infrastructure. We present a dialect-agnostic and dialect-effective grammar-based and coverage-guided fuzzing approach for extensible compilers that combines two key insights: (i) the grammars of dialects can often be extracted automatically from the dialect specification; and (ii) these grammars can be used with pre-trained large language models to automatically generate representative and diverse seed inputs without requiring manual input or training data. We built this approach into Germinator, which when evaluated on six MLIR projects spanning 91 dialects, improved line coverage by 10-120% over grammar-based baselines and discovered 88 previously unknown bugs (40 confirmed).
cover: assets/images/covers/germinator-cover.png
authors:
  - Sairam Vaidya
  - Marcel Böhme
  - Loris D'Antoni
links:
  Paper: https://arxiv.org/abs/XXXX.XXXXX
---
