# Neuro Computation

This repository contains implementations of exercises from the **Neuro Computation** course.

Each exercise focuses on a different computational model or concept inspired by neural systems.

---

## Repository Structure

```
Neuro_Computation
│
├── Ex1
│   ├── Part A-B
│   │   ├── Adaline Algorithm.pdf
│   │   ├── AdalineAlgo.py
│   │   └── main.py
│   │
│   └── Part C-D
│       ├── Mlp Algorithm.pdf
│       ├── NN 2021 Spring Project 1.pdf
│       └── main.py
│
├── Ex2
│   ├── Part A
│   │   ├── Kohonen.py
│   │   ├── SOM Algorithm.pdf
│   │   └── main.py
│   │
│   └── Part B
│       ├── kohonen_part2.py
│       ├── SOM part 2 Algorithm.pdf
│       └── Project II 2021 Kohonen.pdf
│
├── LICENSE
└── README.md
```

---

## Exercises Overview

### Exercise 1 – Adaline and Backpropagation

This exercise investigates different neural learning algorithms for a 2-dimensional classification task.

The project compares the performance of:

- **Adaline (Adaptive Linear Neuron)** for linear classification
- **Multi-Layer Perceptron (MLP)** trained with backpropagation
- Using **MLP learned features with an Adaline output layer**

More information and analysis can be found in the following reports:

- 📄 [Adaline Algorithm Report](Ex1/Part%20A-B/Adaline%20Algorithm.pdf)
- 📄 [MLP Algorithm Report](Ex1/Part%20C-D/Mlp%20Algorithm.pdf)
- 📄 [Project Description](Ex1/NN%202021%20Spring%20Project%201.pdf)

---

### Exercise 2 – Kohonen Self-Organizing Maps

This exercise implements **Self-Organizing Maps (SOM)** for unsupervised learning and clustering.

The experiments explore:

- Training and visualization of SOM networks
- Mapping high-dimensional data onto a 2D grid
- Extended experiments analyzing SOM behavior

More information and analysis can be found in the reports:

- 📄 [SOM Algorithm Report](Ex2/Part%20A/SOM%20Algorithm.pdf)
- 📄 [SOM Part 2 Algorithm](Ex2/Part%20B/SOM%20part%202%20Algorithm.pdf)
- 📄 [Project II – Kohonen](Ex2/Project%20II%202021%20Kohonen.pdf)

---

## Installation

Clone the repository:

```bash
git clone https://github.com/MoriyaBitton/Neuro_Computation.git
cd Neuro_Computation
```

Install required dependencies:

```
pip install numpy matplotlib scikit-learn
```

---

## Run the Project

### Exercise 1

Run the Adaline experiments (Part A-B):

```
python Ex1/Part\ A-B/main.py
```

Run the MLP experiments (Part C-D):

```
python Ex1/Part\ C-D/main.py
```

### Exercise 2

Run the Self-Organizing Map implementation (Part A):

```
python Ex2/Part\ A/main.py
```

Run the extended SOM experiments (Part B):

```
python Ex2/Part\ B/kohonen_part2.py
```

---

###### Ariel University, Israel || Semester B, 2021
