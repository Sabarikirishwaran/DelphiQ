# DelphiQ Phase 3 MITRE Submission 📘

Welcome to the **DelphiQ** repository. This package includes all final deliverables for our Phase 3 submission, fulfilling simulation, reproducibility, benchmarking, hardware implementation, and industrial relevance criteria.

---

## 🗂️ Repository Contents

All relevant files for this submission:

- **DelphiQ Mitre Maths formalism.pdf**  
  — Formal mathematical derivations underpinning our full algorithm pipeline. 
  *Maps to criteria:* Algorithm traceability, quantum advantage justification.

- **Phenanthrene Reactivity and Stability analysis.ipynb**  
  — Jupyter notebook with DFT-derived trends, HOMO–LUMO gaps, Fukui functions, charge distributions, and carbonyl-focused reactivity pathways.  
  *Maps to criteria:* Trends & chemical context, classical comparison, reaction energetics, analysis of stability and reactivity.

- **Phenanthrene plots static.ipynb**  
  — Extracts and exports static/high-resolution energy diagrams used in the interactive section of Phenanthrene Reactivity and Stability analysis.ipynb write-up.  
  *Maps to criteria:* Simulation results presentation, stability analysis visualisations.

- **QITE of Phenanthrene‑Quinone Fragment.ipynb**  
  — Fully annotated notebook implementing our QITE algorithm with Jordan–Wigner Hamiltonian encoding, active-space reduction, and cumulative energy output. Includes circuit block breakdown, qubit count, run parameters, convergence behavior, and correlation assessment.  
  *Maps to criteria:* Execution & results interpretation, reproducibility, environment configuration.

**LUCJ.ipynb**
— Demonstrates Local Unitary Cluster Jastrow (LUCJ) ansatz construction for the phenanthrene-quinone fragment. Details qubit encoding (Jordan–Wigner), spin-orbital layout, ancilla-mediated interactions, and hardware-aware topology mapping, as well as SQD execution. Includes circuit depth, gate composition, and SQD
*Maps to criteria:* Algorithm design, hardware-awareness, circuit construction, execution.

---

## 📌 Phase 3 Criteria Mapping

| Criterion                                      | Implementation / Files                                                                 |
|------------------------------------------------|-----------------------------------------------------------------------------------------|
| **1. Simulation Execution & Results**          | - *QITE…ipynb*: simulated QITE on the phenanthrene‑quinone fragment. <br> - *React/Stability…ipynb* + *plots static.ipynb*: computed HOMO–LUMO gaps, Fukui functions, reactivity trends, energy diagrams. |
| **2. Reproducibility & Traceability**         | All notebooks are annotated with: <br> – Quantum circuit diagrams, Hamiltonian encodings (JW mapping), <br> – QITE parameters (`dt`, `max_cycles`, convergence), <br> – Design rationales (error mitigation, active-space selection). |
| **3. Quantum Advantage & Benchmarking**       | - *Phenanthrene…ipynb*: includes classical DFT comparisons (HOMO–LUMO, Fukui). <br> *LUCJ.ipnb*: includes SQD execution and qubit encoding. <br> - *QITE…ipynb*: shows correlation energy improvements vs HF, discusses active-space relevance. |
| **4. Execution Environment & Challenges**     | • Qubits: shown via `2 × n_active_orbitals` <br> • Circuit depth & convergence: logged iteration behavior in QITE notebook <br> • Simulator used: Tangelo statevector backend <br> • Runtime stats and parameter settings embedded in notebook comments. |
| **5. Industrial Relevance & Future Directions** | Detailed discussion in *Phenanthrene Reactivity…ipynb* and *plots static.ipynb* and our Phase 3 Proposal and *Maths formalism.pdf*, linking carbonyl formation data to asphalt-aging mechanisms, binder design, and future modeling pathways. |

---

## 🚀 How to Navigate & Run the Notebooks

1. **Clone or download** this repository.
2. Launch your environment (e.g., JupyterLab, qBraid).
3. Run the following notebooks in order:

   a. `Phenanthrene Reactivity and Stability analysis.ipynb`  
   b. `Phenanthrene plots static.ipynb`  
   c. `QITE of Phenanthrene‑Quinone Fragment.ipynb`

4. Check printed outputs, convergence logs, and embedded markdown commentary.
5. Refer to our `DelphiQ Mitre Maths formalism.pdf` for detailed theoretical background.
6. Refer to our Phase 3 Proposal for overview of results and discussions.

---

## ⚠️ Code Availability & Licensing

All analysis and simulation code is property of **DelphiQ**. Please contact for attribution or queries:
[Jacinta May – LinkedIn](https://www.linkedin.com/in/jacinta-may-081041237xe/)


