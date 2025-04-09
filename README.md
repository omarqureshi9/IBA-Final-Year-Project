# Federated Learning with Differential Privacy

This repository contains a project of Federated Learning (FL) combined with Differential Privacy (DP). The project demonstrates how multiple clients can collaboratively train a machine learning model without sharing raw data, while preserving privacy through DP techniques.

## 🧠 Key Features

- Simulated Federated Learning environment using multiple clients
- Implementation of Differential Privacy using `Opacus`
- Model aggregation on the server side
- Evaluation of model performance under privacy constraints

## 📁 File Structure

- `Federated learning (DP).ipynb`: Main notebook demonstrating FL with DP
- `README.md`: Project documentation

## ⚙️ Requirements

Ensure the following packages are installed:

```bash
pip install torch torchvision opacus numpy matplotlib
```

## 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/omarqureshi9/IBA-Final-Year-Project.git
cd IBA-Final-Year-Project-dp
```

2. Open the notebook:

```bash
jupyter notebook "Federated learning (DP).ipynb"
```

3. Run all cells to simulate a federated training process with differential privacy.

## 📊 Model Overview

- **Model Type**: Feed Forward Network
- **Dataset**: MNIST
- **Privacy Mechanism**: Differential Privacy via `Opacus`
- **Federated Rounds**: 3
- **Client Count**: 3

## 🔐 Privacy Focus

This project leverages [Opacus](https://opacus.ai/) to add differentially private noise during model training. It ensures:
- Bounded influence of individual training examples
- Improved generalization under strict privacy budgets (ε, δ)

## 📝 Notes

- Ensure your machine has enough memory and compute if you're scaling client count.
- This is a simulation—no real communication between machines is performed.

## 📌 To-Do / Enhancements

- [ ] Extend to real-world distributed environments (e.g., using Flower or PySyft)
- [ ] Add visualization for privacy budget (epsilon) over time
- [ ] Integrate TensorBoard for monitoring training

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss.

## 📄 License

This project is licensed under the MIT License.

---

### 📬 Contact

For queries or collaboration: [your-email@example.com]
