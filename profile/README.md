# AtomField Labs
**Autonomous computational pipelines and distributed infrastructure for high-throughput materials discovery**: [Website](https://tested-civil-ceo-millennium.trycloudflare.com)

    
AtomField develops high-performance simulation orchestrators and modular scientific drivers. Our platform bridges computational chemistry, machine learning force fields, and distributed workflow scheduling into an intuitive, graph-based canvas.

---
### Core Pillars

- **Graph-Based Pipeline Orchestrator**: HPC-inspired asynchronous task execution with topological dependency resolution, isolated POSIX
  workspaces, and zero-copy artifact symlinking.
- **Modular Simulation Drivers**: Extensible wrappers unifying machine-learned potentials (MLIPs), semi-empirical solvers (xTB), and atomistic toolkits (ASE, RDKit) with standardized data schemas.
- **Interactive Visual Canvas**: 2D DAG composition, parameter tuning, and real-time simulation telemetry powered by React Flow and modern web standards.
---

### Key Repositories
| Repository | Purpose |
| :--- | :--- |
| **`atomfield_web`** | Full-stack distributed DAG orchestration engine, control plane (FastAPI / Redis / ARQ), and visual editor. |
| **`afscripts`** | Core scientific drivers for geometry optimization, reactive MD, MLFF relaxation, and conformer sampling. |

---
### Technology Stack
`Python 3.11+` • `FastAPI` • `Redis / ARQ` • `PostgreSQL` • `React` • `TypeScript` • `React Flow` 
---
<sub>Proprietary and confidential to AtomField Labs.</sub>
