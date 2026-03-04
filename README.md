# 🚗 Self-Driving Car using First-Principles Machine Learning

A simple **self-driving car simulation** built completely from scratch — without using any external machine learning libraries.  
This project demonstrates how a car can learn to navigate through traffic (obstacles) using a **basic Genetic Algorithm**, implemented purely from first principles.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [How It Works](#-how-it-works)
- [Installation](#-installation)
- [What Can It Be Used For](#-what-can-it-be-used-for)
- [Project Structure](#-project-structure)
- [Contribution](#-contribution)
- [Acknowledgement](#-acknowledgement)
- [License](#-license)
- [Author](#-author)

---

## 📖 Overview

This project is a **first-principles machine learning implementation** where:

- A car attempts to drive forward.
- Multiple obstacles (traffic) appear in its path.
- The car learns to avoid obstacles over generations.
- Learning is achieved using a **Genetic Algorithm (GA)**.
- No external ML frameworks or libraries are used.

The goal is to demonstrate:

- Evolution-based learning
- Neural network basics (if implemented)
- Selection, mutation, and crossover
- Fitness-based improvement across generations

This project focuses on understanding **how ML works internally**, rather than relying on high-level libraries.

---

## ⚙️ How It Works

### 1️⃣ Initialization

- A population of cars is created.
- Each car has its own “brain” (a simple neural model or decision parameters).
- Parameters are randomly initialized.

### 2️⃣ Simulation

- All cars attempt to drive forward.
- Sensors (or distance calculations) detect obstacles.
- Based on inputs, cars decide:
  - Move forward
  - Turn left/right
  - Accelerate/brake (if implemented)

### 3️⃣ Fitness Calculation

Each car is evaluated based on:

- Distance traveled
- Time survived
- Obstacles avoided

Higher survival = higher fitness.

### 4️⃣ Selection

- The best-performing cars are selected.
- Weak performers are removed.

### 5️⃣ Crossover

- Selected parents combine parameters.
- Offspring inherit mixed traits.

### 6️⃣ Mutation

- Small random changes are introduced.
- Encourages exploration and prevents stagnation.

### 7️⃣ Repeat

- New generation starts.
- Over multiple generations, driving improves.

---

## 🛠 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/driving-car-without-driver.git
cd driving-car-without-driver
```

### Run the Project

```bash
open index.html
```

No external libraries are required.

---

## 🎯 What Can It Be Used For

This project can be used for:

- Learning Genetic Algorithms from scratch
- Understanding evolutionary computation
- Teaching first-principles machine learning
- Academic mini-projects
- Demonstrating AI concepts without frameworks
- Interview discussions on ML fundamentals
- Classroom demonstrations

---

## 📂 Project Structure

```
├── main.(js/py)
├── car.(js/py)
├── genetic_algorithm.(js/py)
├── environment.(js/py)
├── utils.(js/py)
└── README.md
```

---

## 🤝 Contribution

Contributions are welcome!

To contribute:

1. Fork the repository
2. Create a new branch

   ```bash
   git checkout -b feature-name
   ```

3. Commit your changes

   ```bash
   git commit -m "Added new feature"
   ```

4. Push to your branch

   ```bash
   git push origin feature-name
   ```

5. Open a Pull Request

---

## 🙏 Acknowledgement

A special thanks to **Radu Mariescu-Istodor** for the inspiration and project idea. His tutorials and teachings laid the foundation for this project and helped guide its development.

---

## 📜 License

This project is licensed under a **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License**. You may use the code for **personal projects** or **non-commercial purposes**. For any commercial use, including reselling or distributing the code, please contact the author for permission.

---

## 👤 Author

- GitHub: [@Anonav0](https://github.com/Anonav0)
- LinkedIn:[Swarnavo Khanra](https://linkedin.in/swarnavo-khanra)

Feel free to reach out with any questions or feedback!
