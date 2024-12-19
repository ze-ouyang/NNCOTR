
(🚀This site is under construction 🚀)

**NNCOTR: Neural-Network-based reconstruction of the 3D structure of relativistic electron bunches by Coherent Optical Transition Radiation**

---
# Introduction
Transition Radiation (TR) is emitted when a charged particle crosses from one medium into another with different index of refractive. For electron bunches accelerated from Laser-Wakefield-Accelerator (LWFA), TR can be coherently emitted even down to optical range, i.e. Coherent Optical Transition Radiation (COTR). Different 3D structure of the electron bunch lead to different COTR patterns at different wavelengths, whose physical model is well understood. And we refer this as the forward process, from ![eq](https://latex.codecogs.com/svg.image?\rho(x_s,y_s,z_s)) to ![eq](https://latex.codecogs.com/svg.image?&space;S(x_d,y_d,\lambda)), where subscripts "![eq](https://latex.codecogs.com/svg.image?s)" stands for source, and "![eq](https://latex.codecogs.com/svg.image?d)" stands for detector recording COTR signal.

Therefore, COTR contains the 3D info of the electron bunches. However, reverse derivation of this 3D info from COTR is not as straightforward as the forward process. This is becuase the equations describing the forward process are analytically irreversible. The general way to solve such a problem is supposing the 3D structure of the electron bunch is a parameterized function, calculating resultant COTR, comparing with measured COTR guided by a objective function, and iterating the parameters of the electron bunch. While tradiational algorithms like genetic algorithm, and differential evolution have been used in such a reconstruction problem, neural network is emerging as an alternative way, which is the topic for this project.

In this project, we first develop high-performance numertical integration method for efficiently calculating the forward process and generating training data set for the neural network. Then we test its degree of fidelity in this inverse problem.

