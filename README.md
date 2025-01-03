# Machine Learning for Quantum State Tomography 🧪🤖

## Overview  
This project explores the intersection of **machine learning** and **quantum information science** to enhance **Quantum State Tomography (QST)**. Using a **maximum likelihood estimation (MLE)** approach integrated with **graph neural networks (GNNs)**, the goal is to achieve more accurate and efficient quantum state reconstruction for multi-qubit systems.

---

## Features  
✨ **Maximum Likelihood Estimation**: Probabilistically reconstruct quantum states.  
✨ **Graph Neural Networks**: Model relational quantum data with cutting-edge GNN architectures.  
✨ **Single Jupyter Notebook**: Self-contained implementation for ease of understanding and experimentation.  
✨ **Improved Scalability**: Handle larger quantum systems with efficient computation.  

---

## Getting Started  

1. **Clone the Repository**  
   ```bash
   git clone git@github.com:javahedi/QuantumStateTomography-ML.git 
   cd QuantumStateTomography-ML
   ```

2. **Set Up the Environment**  
   - Create a virtual environment and install dependencies:  
     ```bash
     python -m venv venv
     source venv/bin/activate    # On Windows, use `venv\Scripts\activate`
     pip install -r requirements.txt
     ```

   - Alternatively, install Jupyter Notebook and other dependencies directly:  
     ```bash
     pip install jupyterlab numpy matplotlib scipy tensorflow torch
     ```

3. **Launch the Jupyter Notebook**  
   Start the notebook server:  
   ```bash
   jupyter lab
   ```
   Open `quantum_state_tomography.ipynb` and run the cells sequentially.

---

## Project Structure  
```plaintext
.
├── main_jaxFlax.ipynb       # Main project notebook (JAX and Flax implementation)
├── README.md                # Project documentation
├── requirements.txt         # Python dependencies
└── LICENSE                  # License for the project
```

---

## Results  
- **Accuracy**: Enhanced reconstruction of noisy multi-qubit quantum states.  
- **Efficiency**: Achieved faster computation compared to traditional methods.  
- **Scalability**: Successfully reconstructed quantum states for larger systems.  

Example output visualizations and results can be seen directly in the notebook.  

---

## Tools & Technologies  
- **Languages**: Python  
- **Libraries**: NumPy, TensorFlow, PyTorch, SciPy, Matplotlib  

---

## Future Work  
- Extend to hybrid quantum-classical algorithms.  
- Optimize the approach for larger, real-world quantum systems.  
- Validate the methodology on actual quantum hardware.  

---

## License  
This project is licensed under the [MIT License](LICENSE).

---

## Contact  
If you have any questions or suggestions, feel free to reach out:  
📧 Email: javahedi@gmail.com 
💼 GitHub: [javahedi](https://github.com/javahedi)

---


## Acknowledgments  
- This project incorporates the use of **Graph Attention Networks** as introduced in the paper:  
  *Veličković, P., et al. "Graph Attention Networks." arXiv:1710.10903 (2017).*
- Special thanks to my collaborator [Adrian Aasen](https://github.com/AdrianAasen) for their contributions to this project.



