<table>
  <tr>
    <td valign="top">
      <h1>Gaoshan Zeng / 曾高山</h1>
      <p><strong>AI for Science (AI4S) | Scientific computing | Materials informatics | Open-source developer</strong></p>
      <p>I am an <strong>incoming graduate student (研0)</strong> at <strong>Peking University (PKU)</strong>, with a research focus on <strong>AI for Science (AI4S)</strong>.</p>
      <p><strong>Undergraduate background:</strong> Electronic Science &amp; Technology, <strong>SAU</strong>.</p>
      <p>My work connects <strong>AI4S, materials science, scientific simulation, and AI agents</strong>. I am especially interested in building systems that close the loop between <strong>domain knowledge, simulation, experiment, and autonomous discovery</strong>.</p>
      <p>
        <a href="mailto:zenggaoshan05@gmail.com"><img src="https://img.shields.io/badge/Email-zenggaoshan05%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
        <a href="https://github.com/zenggs05"><img src="https://img.shields.io/badge/GitHub-zenggs05-181717?style=flat&logo=github&logoColor=white" alt="GitHub" /></a>
        <img src="https://img.shields.io/badge/Focus-AI4S%20%7C%20Scientific%20Computing-2F80ED?style=flat" alt="Focus" />
      </p>
      <p><strong>Research interests:</strong> AI4S, AI Scientist agents, ML potentials, materials informatics, DFT/MD, high-entropy materials, microwave absorption, electrochemical sensing, and high-throughput screening.</p>
      <p><strong>Public writing:</strong> WeChat public account <strong>飞鸟想要飞</strong>, with 1M+ total views.</p>
    </td>
    <td width="250" align="center">
      <img src="./assets/profile.jpg" width="220" alt="Gaoshan Zeng cycling at Zongla Mountain" />
      <br />
      <sub>Solo, fully loaded ride from Chengdu to Lhasa; photo at Zongla Mountain, 4,150 m</sub>
    </td>
  </tr>
</table>

---

## Project Experience

### AI4S and Scientific Computing

**Million-scale high-fidelity electrolyte MLIP dataset and structure-property analysis**<br />
*Peking University Shenzhen Graduate School, visiting student / research assistant, 2026.04 - present*

- Proposed an adaptive, full-stack data-construction workflow for electrolyte MLIP datasets: generative-prior composition design, pulsed-dynamics sampling, and multi-fidelity quantum labeling.
- Combined classifier-guided diffusion with pulsed nanoreactor active learning under extreme temperature / volume perturbations to capture non-equilibrium transition states and high-uncertainty OOD configurations.
- Developed physics-guided reduction through adaptive fragmentation and ALMO-EDA analysis, then paired million-scale lower-cost force / geometry labels with sparse high-accuracy energy references to reduce computational cost by about 90%.

**DFR-related high-throughput screening research**  
*Department of Artificial Intelligence, Xiamen University, 2026.02*

- Worked on DFR-related research for accelerating high-throughput screening workflows.
- Focused on connecting AI models with candidate generation, simulation evaluation, and fast property filtering.
- Interested in turning high-throughput screening from a manual pipeline into a more automated and reproducible research loop.

**Electrodeposited Cu foils: microstructure and mechanical properties**  
*University of Science and Technology of China / Institute of Metal Research, Chinese Academy of Sciences*

- Worked around the system studied in *The effect of 2-mercaptobenzimidazole concentration on the microstructure and mechanical properties of electrodeposited Cu foils*.
- Studied how 2-mercaptobenzimidazole (MBI) affects electrodeposited Cu foils through grain refinement, surface morphology, crystallographic texture, nanotwinned grains, and thermal stability.
- Followed the electrochemical mechanism behind additive-assisted Cu electrodeposition, including MBI adsorption and complexation with cupric ions.

**Machine learning for high-entropy materials**  
*KAUST, visiting student / research assistant, 2025.09 - 2026.03*

- Built ML workflows for high-entropy alloys and oxides using ALIGNN, composition-based feature vectors, and JARVIS-DFT data.
- Focused on formation enthalpy, total energy, magnetic moments, and generalization under sparse high-fidelity data.
- Worked on accelerating candidate screening in large composition spaces.

**Electronic-structure atlas of MoS2 nanotubes with DeepH and first-principles workflows**  
*Westlake University, research assistant, 2025.07 - 2025.09*

- Integrated VASP, OpenMX, ABACUS, Quantum ESPRESSO, CHGNet, and DeepH into automated electronic-structure workflows.
- Studied chirality-dependent bandgaps, effective masses, and direct/indirect bandgap transitions.
- Compared DeepH predictions with DFT-level calculations to evaluate accuracy and computational efficiency.

**AI Scientist agents for materials discovery**  
*DeepModeling / AI4S exploration*

- Working on agentic workflows for literature understanding, hypothesis generation, simulation planning, and materials-design feedback loops.
- Interested in making scientific agents more reproducible, tool-aware, and grounded in physical constraints.

**LLM-guided reverse design of high-entropy microwave absorbers**  
*Manuscript in submission*

- Developing an autonomous LLM-agent-guided framework for multi-scale reverse design of high-entropy microwave absorption materials.
- Combining domain reasoning, conditional diffusion / reinforcement-learning style generation, ALIGNN-based stability evaluation, and CST-based electromagnetic simulation.
- Goal: accelerate the discovery of high-performance, ultra-broadband microwave absorbers with physics-aware constraints.

### Applied AI, Sensing, and Materials Projects

**Machine-learning-integrated electrochemical sensing for farmland heavy metals**<br />
*Provincial Undergraduate Innovation and Entrepreneurship Training Program, project lead, 2024.12 - 2025.09*

- Led the design of an electrochemical sensing and machine-learning integration platform for Pb<sup>2+</sup> and Cd<sup>2+</sup> detection.
- Built a PAC-SVR-LSTM pipeline with PCA and wavelet denoising for classification, concentration regression, and dynamic interference compensation.
- Achieved a 0.8 nM detection limit, 98.2% identification accuracy, and an R<sup>2</sup> above 0.995 for concentration quantification; the project resulted in two software copyrights.

**Composite nanofiber and machine-learning heavy-metal sensing platform**<br />
*National Undergraduate Innovation and Entrepreneurship Training Program, core member, 2024.06 - 2025.09*

- Prepared composite nanofiber electrodes through electrospinning and optimized electrode structure for heavy-metal ion capture.
- Built Python pipelines with Scikit-learn and TensorFlow to compare supervised-learning models for multi-component heavy-metal recognition.
- Helped develop a low-cost, non-destructive prototype for meat and soil testing using electrochemical measurements and data-driven analysis.

### Open-source Developer Tools

I also build small, focused tools for AI-native development workflows:

- [docs-drift-radar](https://github.com/zenggs05/docs-drift-radar): catch stale README snippets, CLI help, and OpenAPI docs in CI.
- [pr-evidence-pack](https://github.com/zenggs05/pr-evidence-pack): turn a PR diff into a reviewer-ready evidence pack.
- [browser-skill-forge](https://github.com/zenggs05/browser-skill-forge): record browser workflows and export Playwright / agent skills.
- [Crysio](https://github.com/zenggs05/Crysio): a local crystal-structure workbench for visualization, editing, and VASP relaxation-path comparison.
- [Auto_PaperFetcher](https://github.com/zenggs05/Auto_PaperFetcher): automate paper fetching and research-workflow collection.
- [vscode-remote-ssh-proxy-codex](https://github.com/zenggs05/vscode-remote-ssh-proxy-codex): improve remote SSH / proxy workflows for coding agents.

---

## Skills

**Programming and engineering**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Julia](https://img.shields.io/badge/Julia-9558B2?style=flat&logo=julia&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-e16737?style=flat)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**AI and data science**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

- Graph neural networks, ALIGNN, ML potentials, diffusion models, reinforcement learning, LSTM/SVR pipelines
- Computer vision for sensing and inspection: U-Net style models, MobileViT-style lightweight models
- Scientific data pipelines: feature engineering, active learning, uncertainty/OOD sampling, benchmark evaluation

**Scientific computing and simulation**

- First-principles and electronic structure: VASP, CP2K, Quantum ESPRESSO, Materials Studio, OpenMX, ABACUS, DeepH
- Molecular dynamics and chemistry simulation: GROMACS, Gaussian, LAMMPS
- Multiphysics and electromagnetic simulation: COMSOL, CST Studio Suite
- Data analysis and research tooling: Origin, SPSS, Python scientific stack, Linux HPC workflows
- Chemical experiments: materials synthesis, annealing, combustion, hydrothermal preparation, electrochemical sensing, electrode-material preparation

These simulation and experimental skills let me contribute to many published materials papers through DFT modeling, RCS / electromagnetic simulation, COMSOL analysis, Python data processing, and mechanism interpretation.

---

## Selected Publications

1. **G. Zeng**, H. Huang, et al. *Machine-Learning and Atomic-Scale Mechanistic Insights for Designing Gradient Porous MOF-Derived Carbon Electrodes*. **Inorganic Chemistry**, 2025.  
   First-author work combining ML, DFT/MD, and interpretable design rules for MOF-derived carbon electrodes.

2. N. Wang, X. Kou, **G. Zeng**, et al. *Geometry-defect-spin coupling in chiral high-entropy systems: Multiscale mechanisms of GHz electromagnetic dissipation*. **Science Advances**, 2025.  
   Multiscale study of chiral high-entropy systems for broadband electromagnetic dissipation.

---

## Honors

- Meritorious Winner, The Mathematical Contest in Modeling
- Third Prize, Asia and Pacific Mathematical Contest in Modeling
- Academic Excellence Scholarship, SAU
- 20+ awards across national, provincial, and university-level competitions

---

## What I Am Building Toward

I want to apply my experience across simulation, experiments, AI4S, and open-source development to more capable research and intelligent systems, especially **AutoResearch / AI for Science, embodied intelligence, and LLM development**.

- AutoResearch systems that can read papers, call scientific tools, run simulations, and report evidence.
- ML potential and materials-informatics workflows that scale from small datasets to real discovery loops.
- Embodied-intelligence systems that connect perception, planning, and action in real environments.
- LLM applications and agents that are reliable, tool-aware, and useful in complex technical workflows.
- Open-source developer tools that make research and engineering workflows easier to reproduce.

Outside research, I like long-distance cycling and endurance challenges. I once rode solo for 18 days from Chengdu to Lhasa, covering 2,300+ km across many high-altitude mountain passes. That experience shaped how I think about hard problems: break the route down, keep moving, and do not be afraid of difficult terrain.

At PKU, I aim to develop AI4S methods that connect scientific simulation with autonomous materials discovery.

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=zenggs05&show_icons=true&theme=minimal" alt="Gaoshan's GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=zenggs05&layout=compact&theme=minimal" alt="Top languages" />
</div>
