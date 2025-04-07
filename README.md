# 🧠 Policy Gradient (REINFORCE) with PyTorch

This project implements the **Policy Gradient (REINFORCE)** algorithm using PyTorch on:
- 🏗️ **CartPole-v1**
- 🚁 **Pixelcopter-v0** (from `gymnasium[box2d]`)

![Pixelcopter](https://github.com/YashrajKupekar17/Policy-Gradient-Pytorch_Implementation-Pixelcopter/blob/main/assets/replay-gif.gif)

---

## 🚀 Highlights

- REINFORCE with softmax policy
- Trains directly from rewards
- Works on both classic control and pixel-based environments
- Visualizations included

---

## 📁 Files

```
Policy_Gradient.ipynb   # Implementation and training
assets                 # GIFs and result plots
```

---

## 🛠️ Setup

```bash
git clone https://github.com/YashrajKupekar17/Policy-Gradient-Pytorch_Implementation-Pixelcopter
cd Policy-Gradient-RL
pip install torch gymnasium[box2d] matplotlib numpy
```

Launch the notebook:
```bash
jupyter notebook Policy_Gradient.ipynb
```

---

## ✅ Results

- **CartPole-v1**: Achieves consistent balancing with high reward
- **Pixelcopter-v0**: Learns to navigate through the terrain


