# Hi, I'm Aashirvad Bajpai 

I’m a B.Tech student at **Manipal Institute of Technology** and an active open-source contributor to the **scikit-hep/awkward** project.

My work focuses on backend and systems-level problems in scientific computing, particularly around GPU support, array backends, and API correctness. I enjoy contributing to research-driven software that sits at the intersection of performance, data, and usability.

---

## Open Source Contributions

### Awkward Array (Scikit-HEP)

I am an active contributor to the Awkward Array ecosystem, with merged and ongoing work spanning backend internals, GPU compatibility, and documentation.

**Contribution highlights:**
- Improved `ak.to_cudf` compatibility across cuDF versions (≥ 24.12), adapting to column API changes
- Updated internal column construction logic for numerical, struct, and masked arrays
- Worked on buffer conversion paths (`to_buffers`) to avoid unsafe assumptions across non-NumPy backends
- Added and refined GPU-gated test coverage for cuDF-related code paths
- Clarified axis semantics and documented named-axis support in high-level APIs

My contributions include production code, tests, and user-facing documentation, driven by real issues encountered by downstream users.

I am currently collaborating with Awkward Array maintainers and participating in weekly mentor meetings.

---

## Technical Focus

- **Languages:** Python, C/C++
- **Scientific stack:** NumPy, Awkward Array, cuDF
- **GPU & systems:** GPU-accelerated pipelines, backend compatibility, array layouts
- **ML/DL (research use):** PyTorch, scikit-learn
- **Tools:** Git, Linux, VS Code, Jupyter, LaTeX

---

## Research & Projects

### Clinical Similarity Modeling (MIMIC-IV, PhysioNet)

Independent research project focused on learning patient representations from structured EHR data:
- Cohort similarity and retrieval
- Scalable pipelines for large clinical datasets
- Emphasis on reproducibility, ethical data usage, and evaluation

### Brain-to-Text Decoding (GPU Research Project)

Research-oriented project exploring neural decoding pipelines:
- Large-scale neural signal processing
- Training and inference on NVIDIA A100 GPUs
- Focus on preprocessing efficiency, model performance, and evaluation

### Other Work
- Panorama video generation using AI-based interpolation (research project, LaTeX documented)
- CNN-based handwritten digit recognition with GPU-enabled inference
- Transformer-based language modeling on Shakespearean text

---

## Publications

- **Knowledge Graph to Text Generation**  
  Co-author, *IEEE MoSICom 2025*  
  Ontology-driven triple-to-text generation using LLaMA-based language models  
  (Extended journal manuscript under review at IEEE OJCS)

---

## Goals

- Continue contributing to open-source scientific computing projects
- Pursue research at the intersection of systems, performance, and data-intensive workloads
- Prepare a **Google Summer of Code** proposal focused on extending and stabilizing GPU backend support in Awkward Array

---

## Contact

- **GitHub:** https://github.com/X0708a  
- **LinkedIn:** https://linkedin.com/in/aashirvad-bajpai-534137286  
- **Email:** aashirvadbajpai8@gmail.com
