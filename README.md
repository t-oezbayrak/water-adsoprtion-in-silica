# <img width="640" height="480" alt="1" src="https://github.com/user-attachments/assets/27e2b5a4-97e0-485f-98bc-863a6eab5152" />
# Water Adsorption in Silica (LAMMPS / GCMC)

This project demonstrates a simple workflow to study water adsorption inside a silica structure using atomistic simulation.

## Workflow
1. Build and prepare an initial silica structure.
2. Introduce a crack/void region by deforming the simulation box.
3. Expand the box to create an accessible adsorption volume.
4. Use **GCMC** to insert water molecules into the crack and observe adsorption behavior.

Scripts included:
- `generate.lmp` – structure preparation
- `cracking.lmp` – crack/void creation by box manipulation
- `gcmc.lmp` – GCMC insertion of water into the crack
