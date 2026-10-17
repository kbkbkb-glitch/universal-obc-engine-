# Open Boundary Computation (OBC) Engine

A scale-invariant dual-kernel tensor simulation engine modeling universal equilibrium and multi-domain dynamics across physics, cosmology, biology, and number theory.

## Core Architecture
- **Scale-Invariant Kernels:** Evaluates systems via opposing force pairs divided across scale $1/d$.
- **Cryptographic Auditability:** All state ledgers are locked via SHA-256 hashes to guarantee zero arithmetic drift across nodes.
- **Universal Master Equation:** $S(d, t+1) = S(d, t) + \sum ( \frac{A}{d} - \frac{B}{d} ) \cdot \Delta t$

## Included Domain Suites
- **Universal Baseline & Biology** (`universal_obc.py` / `universal_obc_data.json`)
- **Fundamental Physics & Quantum Mechanics** (`physics_cosmology_data.json`)
- **Cosmology & Thermodynamic Entropy** (`cosmology_entropy_data.json`)
- **Number Theory & Collatz Convergence** (`number_theory_data.json`)
- **Cross-Domain Universal Correlation Tensor** (`cross_domain_tensor_data.json`)

## License
This project is open-source under the [MIT License](LICENSE).
