<div align="center">

# Aashirvad Bajpai

### Systems Engineering • Columnar Data Systems • AI Infrastructure

</div>

---

## About Me

B.Tech Information Technology student at Manipal Institute of Technology (CGPA 8.04).

I work at the intersection of:

- Columnar data systems
- Memory layout correctness
- Backend abstraction
- GPU-accelerated AI pipelines
- High-performance scientific computing

I am an active contributor to **Scikit-HEP Awkward Array**, working on backend-agnostic buffer handling, Arrow interoperability, and GPU columnar compatibility.

I am currently exploring deeper C++ systems work through data layout design, buffer ownership models, and Arrow-native representations.

---

## Open Source Contributions

### Scikit-HEP Awkward Array (Active Contributor)

**Backend-Agnostic Byteorder & Buffer Handling**
- Refactored byteswap logic across NumPy, CuPy, and JAX backends
- Ensured safe dtype reinterpretation and schema-preserving round trips
- Strengthened buffer abstraction via the nplike layer

**GPU Backend Compatibility (cuDF ≥ 24.12)**
- Updated `ak.to_cudf` for new cuDF column factory APIs
- Migrated to stable column constructors
- Expanded GPU-gated CI regression tests

**Arrow-Backed String Kernels**
- Implemented `ak.str.uniques` and `ak.str.distinct_counts`
- Designed Arrow-compatible execution paths via `pyarrow.compute`
- Added isolated API documentation and correctness tests

**C++ Backend Investigation**
- Traced float64 precision loss in `ak.from_json`
- Identified parsing-level issue in awkward-cpp
- Proposed round-trip-safe parsing refinements

---

## GSoC 2026 Focus

### Apache Arrow Interface for PODIO

My interest lies in:

- Mapping structured event data into Arrow’s columnar format
- Preserving relation semantics (OneToMany, ObjectID)
- Designing Frame → Arrow Table → Frame round-trip guarantees
- Schema generation from runtime EDM metadata
- Zero-copy semantics and buffer ownership correctness

Key architectural interests:

- Reusing existing PODIO write buffers vs introducing Arrow-native buffer layers
- Arrow `StructArray` and `ListArray` representations for relation modeling
- Memory ownership guarantees across C++ backends
- Efficient Arrow `ArrayData` construction without semantic loss

This aligns strongly with my experience in buffer abstraction, schema integrity, and heterogeneous backend compatibility.

---

## Research

### Brain-to-Text Decoding (GPU Pipeline)

- Designed high-throughput preprocessing + inference on NVIDIA A100
- Reduced validation loss from 1.97 → 0.89 over 20 epochs
- Sustained 1.3 it/s under GPU-bound workloads
- Optimized device–host memory transfer paths
- Evaluated convergence across 505 batches per epoch

Focus areas:
- GPU memory efficiency
- Batching strategies
- Device-host synchronization minimization

---

### Knowledge Graph → Text Generation

Co-author, IEEE MoSICom 2025  
Extended manuscript under review at IEEE Open Journal of the Computer Society (OJCS)

- Ontology-driven triple-to-text generation
- LLaMA-based structured semantic decoding
- Schema-aware generation workflows

---

## Technical Areas

**Languages**
- Python
- C++
- C
- Java

**Data Systems**
- Apache Arrow (PyArrow)
- Awkward Array
- cuDF
- NumPy

**Systems Concepts**
- Columnar memory layout
- Buffer ownership models
- Zero-copy semantics
- Byteorder correctness
- Schema-preserving serialization
- GPU memory models

**AI / ML**
- PyTorch
- TensorFlow
- Scikit-learn

**Tools**
- Git
- Linux
- Jupyter
- VS Code
- LaTeX

---

## Current Direction

Building systems that:

- Guarantee memory safety and layout correctness
- Preserve semantics across heterogeneous backends
- Enable zero-copy data interoperability
- Support scalable scientific computing pipelines

Long-term interest: high-performance data infrastructure and systems-level AI tooling.

---

## Links

[GitHub](https://github.com/X0708a)  
[LinkedIn](https://linkedin.com/in/aashirvad-bajpai-534137286)  
[LeetCode](https://leetcode.com/u/X0208)
