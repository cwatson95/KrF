# Creating a public Repository for Kinetic Excimer Laser Gas Simulations
- Original file was based on Weng Chow 1978
- Adjusted to include LoKI-MC to take cross-sectional data to calculate
EEDF tables
- Currently do not have EEDF tables for molecules such as KrF, ArF
- Simulation must make do without these kinetic reactions

- Project solely pumps in a guassian wave with energy to excite 200+ 
reaction rates to calculate stochiometric densities of species

## Must include:
- CO2 absorption from Inverse Bremmstrahlung
- 5-10 main governing Reaction Rates (Rxn)
- Must include EM wave propagation
- Must extend 0D to a 1D Particle-in-cell (PIC) model
- Possibly add 3D Radiation module

### Specifications:
1. Microwave frequency range: 10-100GHz, reasonable intensity (Possible to get kW, MW microwave power, then focus down to about diffraction limit).
2. Plasma density: 10^12--- 10^15 per cm^3, electron at 2-3 eV, ions at room temperature.
3. Neutral atoms at room temperature, 3*10^19 per cm^3 (~1 atm pressure).
4. For Particle-in-Cell simulation, we can keep the volume small first, e.g., a 100 micrometer cube.


