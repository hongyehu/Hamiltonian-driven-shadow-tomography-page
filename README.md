## Quantum state tomography for general people
**Quantum state tomography** is an essential **quantum technology** underlying the characterization of quantum devices and the discrimination of quantum states. It aims to reconstruct the density matrix from repeated measurements of identically prepared copies of a quantum system. Okay, what does those words mean? 

<p align="center">
  <img src="img/fig_tomography.png" width="500">
</p>

The quantum system is like the black box in the cartoon. It can be some quantum device/computer that we build, or it could be some weird quantum mechanical systems that Nature prepares for us. We, human, are curious creatures, so we would like to know what is inside this quantum black box. Usually, we would like to do is to open the box and see what is going on. However, this method fails here. And interestingly, the reason why it fails is fundamentally related to how Nature stores quantum information. And you will see while classical bits do not have privacy, quantum bits, aka qubits, do have **privary**. 

If you want to look into their private life, they will not yield! The weirdness of quantum life comes from two points: 
 1. The qubits can live a superposition life (entanglement) 
 2. You cannot look at every aspect of their life (uncertainty principle)

### Superposition
<p align="center">
  <img src="img/cat_state.png" width="600">
</p>

You may already heard there is a famous cat in physics history, called Schodinger's cat. This cat risks its life to demonstrate the quantum superposition. As you can see 


While the complexity of exact tomography of the full density matrix scales exponentially with the system size due to the curse of dimensionality, approximate tomography with polynomial complexity has been developed with assumptions of the underlying quantum state, including _matrix product state tomography_, _reduced density matrix tomography_, and _machine learning tomography_ (If we want to learn more about ML-based tomography using information complete POVM measurements, I have created a [repo](https://github.com/hongyehu/Machine_Learning_Quantum_State_Tomography) using PyTorch).

## Classical shadow tomography of quantum states

<p align="center">
  <img src="img/fig_projection.png" width="250">
</p>

<p align="center">
  <img src="img/example.png" width="650">
</p>

## Hamiltonian-driven shadow tomography of quantum state

<p align="center">
  <img src="img/fig_protocol.png" width="300">
</p>

<p align="center">
  <img src="img/fig_variance.png" width="650">
</p>

<p align="center">
  <img src="img/chemical_clock.png" width="300">
</p>


### Quantum art for you

<p align="center">
  <img src="img/quantum_art.png" width="350">
</p>
