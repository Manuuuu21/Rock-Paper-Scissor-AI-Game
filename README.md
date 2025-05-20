# 🤖 Neural Network Rock Paper Scissors

A simple browser-based Rock Paper Scissors game powered by a neural network that learns to predict and counter your moves. This project is built entirely using **HTML**, **CSS**, and **JavaScript** — no external libraries required!

---

## 💡 How It Works

This project features a basic **feedforward neural network** implemented from scratch in JavaScript. It learns using a simple supervised learning approach to counter the player’s move:

- 🎮 **You are the player**: Choose Rock, Paper, or Scissors.
- 🧠 **The AI is trained** to counter your choice.
- 🤖 **Self-play mode**: The AI can play against itself and learn by experience!

---

## 🧠 Neural Network Details

**Architecture:**

- **Input Layer**: 3 nodes (Rock, Paper, Scissors)
- **Hidden Layer**: 3 × input nodes (max 20)
- **Output Layer**: 3 nodes (Rock, Paper, Scissors)

**Parameters:**

- **Learning Rate**: `0.1`
- **Activation Function**: `Sigmoid`
- **Training Mode**: Supervised with predefined rules or Self-play mode (AI vs AI)

---

## ✨ Features

- 🧠 **Custom Neural Network** built from scratch in JavaScript  
- 🎮 **Interactive UI** to play against the AI  
- 🔁 **AI vs AI Mode** to let the network train by playing against itself  
- 📈 **Real-time Stats & Output visualization** via `<canvas>`

---

Happy playing and experimenting with AI! 🎉
