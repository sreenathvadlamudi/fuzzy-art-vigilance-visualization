Fuzzy ART Vigilance Visualization

This project provides a modular and interactive implementation of the **Fuzzy ART (Adaptive Resonance Theory)** neural network model, focusing on how the **vigilance parameter (ρ)** influences learning and category formation.

It includes:
- Realistic match and choice functions from ART theory
- Interactive 2D clustering visualizations with Plotly
- Visualization of clustering behavior at various vigilance levels
- Scalable architecture for future extensions (real datasets, web dashboards, etc.)

---
About Fuzzy ART

**Fuzzy ART** is a type of neural network that balances stability and plasticity by learning in real-time with a vigilance threshold. The vigilance parameter (ρ) controls the model’s sensitivity:

- **Low ρ (e.g., 0.2):** Generalization; fewer, broader clusters  
- **High ρ (e.g., 0.95):** Specialization; more precise and numerous clusters

This simulation visually demonstrates these dynamics using synthetic 2D data.

---

Demo Output

The code generates **4 interactive scatter plots** (via Plotly) showing the cluster assignments formed by the Fuzzy ART model at:

- `ρ = 0.2`
- `ρ = 0.5`
- `ρ = 0.75`
- `ρ = 0.95`

Each point is assigned to a category based on vigilance and weight vector adaptation.

---
Getting Started

Prerequisites

```bash
pip install numpy scikit-learn plotly
