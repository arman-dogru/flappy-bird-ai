# 🐦 Flappy Bird AI

Flappy Bird AI is an implementation of the **NeuroEvolution of Augmenting Topologies (NEAT)** algorithm to train an AI that learns to play the classic Flappy Bird game. The model evolves multiple agents over generations to improve their performance and survival time.

## 🚀 Features

- 🎮 **Automated Gameplay** – The AI learns how to play Flappy Bird autonomously.
- 🧠 **Evolutionary Learning** – Uses the NEAT algorithm to evolve multiple agents.
- 📊 **Real-time Visualization** – See the AI's decision-making in action.
- 🔄 **Multi-Agent Training** – Simultaneously trains multiple instances for faster learning.

## 🛠 Installation

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/arman-dogru/flappy-bird-ai.git
cd flappy-bird-ai
```

### **2️⃣ Install Dependencies**
Ensure you have Python 3 installed, then install the required packages:
```sh
pip install pygame neat-python
```

Alternatively, you can install dependencies using the provided `.whl` files.

### **3️⃣ Run the AI**
```sh
python flappybird_AI.py
```

## 📌 How It Works

1. **Game Environment**: The AI interacts with the Flappy Bird environment built using `pygame`.
2. **NEAT Algorithm**:
   - Each agent is represented as a neural network.
   - The algorithm selects the best-performing agents and evolves them.
   - Over time, the AI improves and survives longer.
3. **Fitness Function**: The AI is rewarded based on survival time and successful pipe navigation.

## 📷 Screenshots

| Training Progress | AI in Action |
|------------------|-------------|
| ![Training](imgs/training.png) | ![AI Playing](imgs/playing.png) |

## 📚 Dependencies

- Python 3.x
- `pygame`
- `neat-python`
- Other dependencies included in the repository (`.whl` files)

## 🏗 Future Improvements

- Implement deep reinforcement learning (e.g., DQN)
- Enhance the visualization of agent performance
- Optimize training speed

## 🤝 Contributing

Contributions are welcome! If you want to improve the AI or add features, feel free to fork the repository and create a pull request.

## 📜 License

This project is open-source and available under the **MIT License**.

---

### 🎯 **Star the Repository if You Like It! ⭐**
