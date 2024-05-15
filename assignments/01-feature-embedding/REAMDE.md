# Assignment - 1: Data Embedding in Variational Quantum Circuits

## Objectives:
- Understand the concept and importance of data embedding in quantum circuits.
- Explore different methods of embedding classical data into quantum states.
- Implement a simple variational quantum circuit with data embedding using a quantum computing framework of your choice (Qiskit, Pennylane, or Cirq).

## Part 1: Background Reading

Students should start by reading the following topics:
- **Basic Principles of Quantum Computing** - Understand qubits, superposition, entanglement, and quantum gates.
- **Variational Quantum Circuits** - Focus on how these circuits are used as trainable models in quantum machine learning. Refer to the previous lecture.
- **Data Embedding Techniques** - Review different strategies for encoding classical data into quantum states, including basis, angle, and amplitude encoding.

## Part 2: Conceptual Questions

Answer the following questions to ensure understanding of the key concepts:
- Explain the significance of data embedding in the context of quantum machine learning.
- Describe the difference between different encoding methods. Provide examples of when each might be preferable.
- Discuss the potential challenges in embedding data into quantum circuits.

## Part 3: Practical Task

Implement a simple variational quantum circuit that uses basis, angle, and amplitude encoding to embed data for a binary classification task.

### Task Details:
- **Dataset**: Use any synthetic dataset with 2 features and a binary label. Generate this dataset using Python (e.g., using numpy or sklearn libraries).
- **Basis embedding Implementation**:
  - Use any quantum computing framework of your choice (Qiskit, Pennylane, Cirq, etc.).
  - Encode the data points into the quantum circuit using basis encoding.
  - Design a parameterized circuit that acts as the classifier.
  - Use a quantum measurement to interpret the output of the circuit.
  - Repeat for angular and amplitude encodings.
- **Training**:
  - Train the circuit parameters using a classical optimizer to minimize a loss function that reflects the classification accuracy.
- **Analysis**:
  - Evaluate the performance of your model on a separate validation set.
  - Provide insights into the training process, the impact of quantum circuit design choices on performance, and potential areas for improvement.
  - Compare the effectiveness of the given models.

## Part 4: Submission Guidelines

- Prepare the answers to the conceptual questions for the seminar on **14th of May**, 14:00.
- Provide well-commented code for the practical task in the form of a jupyter notebook.
- Commit to the repository.

## Part 5: Resources

- [Overview of embeddings](https://arxiv.org/abs/2311.10375)
- [Quantum Transfer Learning](https://arxiv.org/abs/1912.08278)
- [Very nice lecture on what to expect from QML](https://www.youtube.com/watch?v=VVY8xcps3N4&t=1925s&pp=ygUodmFyaWF0aW9uYWwgcXVhbnR1bSBjaXJjdWl0cyBtYXJpYSBzY2h1ZA%3D%3D)
