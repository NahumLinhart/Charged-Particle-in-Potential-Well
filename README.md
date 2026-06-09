# Charged Particle in a Potential Well Simulation


As a teaching assistant for AP Physics C: E&amp;M, I decided to make post AP physics worksheets on the Lagrangian formalism and a charged particle in a potential well due to a charged ring. GitHub's native PDF previewer sometimes distorts compiled LaTeX math fonts, so for the best viewing experience, I have hosted the worksheets and solutions externally: [View the worksheets and solutions here](https://drive.google.com/drive/folders/1Yj-az3sO3PaBEAiX5snnyF14qSkEwoeu?usp=sharing). The latter worksheet explores how the charged particle’s motion can be described by simple harmonic motion (SHO) when the displacement of the particle is small. Additionally, the worksheet explores the need for special relativity at high energies. 

The attached code is a simulation of the system explored in the second worksheet. The first block of code compares non-relatavistic motion to simple harmonic motion, the second block of code compares non-relativistic motion to relativistic motion, the third block of code displays only non-relativistic motion, and the last block of code displays only relativistic motion. Each block outputs animations of the particle's motion as a function of time, the particle's motion in cartesian coordinates, the potential energy as a function of the particle's position, and a phase diagram of the system. Additionally, the last block of code displays the ratio between the proper time of the moving particle and the coordinate time of the stationary observer as a function of coordinate time. Below is a clip of the output of block 4. Currently, the charged particle is set to be an electron. 


<img width="800" height="677" alt="relativistic_motion" src="https://github.com/user-attachments/assets/da9804e0-560e-428d-88a9-1084cb78641d" />


To run this notebook on your own machine, you will need Python installed along with Jupyter and a few scientific libraries.

1. Clone the repository:
   ```bash
   git clone https://github.com/NahumLinhart/Charged-Particle-in-Potential-Well.git
   cd Charged-Particle-in-Potential-Well
   ```

2. Install the required dependencies:
   This simulation relies on SciPy for numerical integration and Matplotlib for the animations.
   ```bash
   pip install numpy scipy matplotlib jupyter
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook
   ```

4. Open `electron_potential_well.ipynb` in your browser and click **Run All** to execute the simulation and generate the animations.


