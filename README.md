# Mathematical Foundations of Generative AI (IISc Bangalore)

[![NPTEL Course](https://img.shields.io/badge/NPTEL-106108004-blue.svg)](https://nptel.ac.in/courses/106108004)
[![Institute](https://img.shields.io/badge/Institute-IISc%20Bangalore-red.svg)](https://iisc.ac.in)
[![Python](https://img.shields.io/badge/Python-3.9%2B-green.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/Framework-PyTorch-orange.svg)](https://pytorch.org/)

This repository contains code implementations, Jupyter notebooks, tutorial walkthroughs, and assignments for the NPTEL course **[Mathematical Foundations of Generative AI](https://nptel.ac.in/courses/106108004)** offered by **IISc Bangalore**, taught by **Prof. Prathosh A. P**.

---

## 📌 Course Information

- **Course Title:** Mathematical Foundations of Generative AI
- **Course ID:** 106108004
- **Instructor:** [Prof. Prathosh A. P](https://eecs.iisc.ac.in/) (Department of Electrical Communication Engineering / AI, IISc Bangalore)
- **Offering Institute:** Indian Institute of Science (IISc), Bangalore
- **Platform:** NPTEL / SWAYAM
- **Primary Reference:** Foster, D. *Generative Deep Learning*, 2nd Edition, O'Reilly Media (2023), alongside seminal research papers.

---

## 🗺️ Syllabus & Progress Roadmap

| Week | Lecture Topics | Tutorial / Implementation Focus | Status |
| :---: | :--- | :--- | :---: |
| **01** | Introduction to Probabilistic Deep Generative Modelling | Python Basics, NumPy Foundations (`intro-numpy.ipynb`) | 🔄 In Progress |
| **02** | Generative Models: Problem Formulation | PyTorch Basics, CNNs, RNNs, Transfer Learning | ⏳ Upcoming |
| **03** | Probability Review & ML Foundations | Probability distributions, sampling, maximum likelihood | ⏳ Upcoming |
| **04** | Variational Divergence Minimization & $f$-Divergence | $f$-Divergence formulations and properties | ⏳ Upcoming |
| **05** | Generative Adversarial Networks (GANs) | Vanilla GAN, DCGAN, and Conditional GAN | ⏳ Upcoming |
| **06** | GANs, Inversion & Introduction to VAEs | Wasserstein GAN (WGAN), Latent Variable Models | ⏳ Upcoming |
| **07** | Variational Autoencoders (VAEs) | Standard VAE, $\beta$-VAE, Vector Quantized VAE (VQ-VAE) | ⏳ Upcoming |
| **08** | Diffusion Models: Foundations | WGAN (Gradient Clip & GP), VAE & $\beta$-VAE code | ⏳ Upcoming |
| **09** | Diffusion Models: Advanced Formulations | VQ-VAE Implementation & Diffusion pipeline overview | ⏳ Upcoming |
| **10** | Flow Matching Models | Flow Matching Parts 1 & 2, Diffusion Model implementation | ⏳ Upcoming |
| **11** | Flow Matching & Autoregressive Models | Flow Matching (contd.), Transformers & AR models | ⏳ Upcoming |
| **12** | RLHF & LLM Alignment | Reinforcement Learning for Alignment (PPO, DPO), Reward Modeling | ⏳ Upcoming |

---

## 📂 Repository Structure

```text
GenAI/
├── README.md
├── Week-01/
│   └── intro-numpy.ipynb
├── Week-02/
├── Week-03/
├── Week-04/
├── Week-05/
├── Week-06/
├── Week-07/
├── Week-08/
├── Week-09/
├── Week-10/
├── Week-11/
└── Week-12/
```

---

## 🛠️ Setup & Environment

To run the notebooks locally, set up a virtual environment and install the required dependencies:

```bash
# Clone the repository (if not already local)
git clone https://github.com/meshv-patel/GenAI.git
cd GenAI

# Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install numpy scipy matplotlib torch torchvision jupyter
```

---

## 🔗 Useful Links

- [NPTEL Course Portal (106108004)](https://nptel.ac.in/courses/106108004)
- [IISc Bangalore](https://iisc.ac.in/)
