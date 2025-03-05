# CUDA-Q Labs
References to lab exercies I've done after my club's webinar with NVIDIA representatives on quantum computing and CUDA-Q (March 4, 2025).

## Introduction to CUDA-Q
CUDA-Q is an open-source quantum development platform orchestrating the hardware and software needed to run useful, large-scale quantum computing applications. The platform’s hybrid programming model allows computation on GPU, CPU, and QPU resources in tandem from within a single quantum program. CUDA-Q is “qubit-agnostic”—seamlessly integrating with all QPUs and qubit modalities and offering GPU-accelerated simulations when adequate quantum hardware is not available.

## About the Resources
**What the Quick Start to Quantum Computing is:** 
These notebooks provide a quick and practical introduction to the basic quantum concepts sufficient to program and interpret variational algorithms. Additionally, through the interactive coding exercises, readers will learn the basics of the CUDA-Q platform.

**What the Quick Start to Quantum Computing is not:** 
These notebooks do not claim to provide an exhaustive introduction to quantum information science. We make several unspoken assumptions and simplifications to give the reader, who may be unfamiliar with quantum mechanics, a general sense of quantum computing so that they can begin to explore variational algorithms. Readers interested in a more thorough introduction to quantum information science are encouraged to read one of several texts on the subject for instance Introduction to Classical and Quantum Computing, Quantum Computer Science, or Introduction to Quantum Information Science, or watch online lectures such as this series.

**Pre-requisites:** 
Learners should have familiarity with Jupyter notebooks and programming in Python. Additionally, pre-requisite knowledge includes complex numbers, linear algebra, and statistics. In particular, we assume experience computing and understanding of arithmetic of complex numbers, probabilities, expectation values, vectors, dot products, and matrix multiplication. Knowledge of eigenvalues and eigenvectors will be helpful, but not necessarily a requirement.

### Learning Objectives:
- Employ multiple representations of quantum states and gates including bra-ket notation, matrix representation, and Bloch sphere visualization
- Recognize terminology including superposition, entanglement, interference, phase, quantum circuit, quantum kernel, measurement, Hamiltonian, expectation value, etc.
- Construct quantum kernels using CUDA-Q
- Execute quantum programs and hybrid quantum-classical programs using CUDA-Q and interpret the results
- Program variational quantum algorithms to explore the solution space of an optimization problem
- Discover opportunities for accelerating hybrid programs on a GPU

## Resources Provided During the Webinar
### GitHub Repository: 
https://github.com/NVIDIA/cuda-q-academic/tree/main/quick-start-to-quantum

### Reading Material, as Provided by the Speakers: 
- [What is a CUDA Kernel?](https://nvidia.github.io/cuda-quantum/latest/using/basics/kernel_intro.html)
- [Quantum Computing 101: Quantum Gates & Measurements](https://nvidia.github.io/cuda-quantum/latest/using/examples/quantum_operations.html)
- [Examples of CUDA-Q for Application Development in C++ and Python)](https://nvidia.github.io/cuda-quantum/latest/using/examples/examples.html)
- [Building CUDA-Q Programs](https://nvidia.github.io/cuda-quantum/latest/using/basics/build_kernel.html)
- [Running CUDA-Q Programs](https://nvidia.github.io/cuda-quantum/latest/using/basics/run_kernel.html)

- [Accelerating Google’s QPU Development with New Quantum Dynamics Capabilities](https://developer.nvidia.com/blog/accelerating-googles-qpu-development-with-new-quantum-dynamics-capabilities/)
- [Introducing NVIDIA CUDA-QX Libraries for Accelerated Quantum Supercomputing](https://developer.nvidia.com/blog/introducing-nvidia-cuda-qx-libraries-for-accelerated-quantum-supercomputing/)
- [NVIDIA CUDA-Q Runs Breakthrough Logical Qubit Application on Infleqtion QPU](https://developer.nvidia.com/blog/nvidia-cuda-q-runs-breakthrough-logical-qubit-application-on-infleqtion-qpu/)

## Speakers
Mark Wolf, Phd
</br>
Esperanza Cuenca-Gomez
