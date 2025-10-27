# Synoptic  
*A project of the Open Pathology Foundation*  
**Advancing modular, AI-ready data structures for digital pathology and beyond**

---

### Overview  
**Synoptic** defines a modern, machine-readable data model for structured pathology reporting.  
It provides open, versioned schemas for encoding pathology “synoptic” data —  
the structured fields and logic that underpin tumor resections, biopsies, and diagnostic summaries.

The goal is to establish an interoperable foundation for:
- consistent, machine-verifiable data capture,  
- easy integration with laboratory systems and AI pipelines, and  
- vendor-neutral exchange of structured pathology data.

---

### Guiding Principles  
1. **Open by design** — transparent schemas, open-source tooling, public validation datasets.  
2. **Modular architecture** — each organ system (e.g., breast, colon, prostate) lives in its own versioned module.  
3. **Interoperable** — aligned with FHIR, JSON Schema, and other open standards.  
4. **Validated** — continuous integration verifies every schema and example through automated tests.  
5. **Clinically grounded** — built by and for pathologists, informaticians, and engineers.

---

### 📁 Repository Structure

```text
synoptic/
├── schemas/                 # JSON schemas for each organ
│   └── breast/
│       └── v0.1/
│           ├── synoptic.schema.json
│           └── examples/
│               └── case-0001.json
├── validators/              # schema validation tools
├── specs/                   # human-readable reference documents
└── .github/
    └── workflows/           # CI validation pipeline

---

### Relationship to Other Foundation Projects
- **[staging-api](https://github.com/OpenPathologyFoundation/staging-api)** (planned):  
  Independent API for AJCC/TNM staging logic.  
- **validation-suite** (planned):  
  Shared validation library for schema testing and CI/CD.  

---

### Contributing
We welcome contributions from the community.  
Please read the [CONTRIBUTING.md](CONTRIBUTING.md) and [GOVERNANCE.md](GOVERNANCE.md) before submitting pull requests.

All content is released under the [Apache 2.0 License](LICENSE).

---

### Contact  
Open Pathology Foundation  
📧 info@openpathology.tech  
🌐 https://openpathology.tech
