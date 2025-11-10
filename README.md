# mimic-mjx Supplementary Videos

This repository contains supplementary videos and data for the mimic-mjx project, demonstrating physics-based simulations and tracking across multiple organisms.

## Repository Structure

### `arms/`
Mouse arm reaching experiments including:
- Motion sequence analysis notebooks
- Reference videos (solid and transparent overlays)
- Full rollout videos with tracking data
- 47 individual trial videos of reaching behavior
- H5 data files containing rollout trajectories

### `fly/`
Fruit fly (Drosophila) simulation and tracking:
- STAC (Simulated Trajectory Analysis and Comparison) synchronization notebooks
- High-fidelity 3D fly mesh assets (`.obj` files for all body segments)
- MuJoCo XML models for physics simulation
- Tracking data from Anipose (H5 format)
- Synchronized videos comparing real tracking with MuJoCo simulation
- Example clips demonstrating tethered flight behavior

### `rodent/`
Rodent locomotion analysis:
- STAC analysis notebooks with real video comparison
- MuJoCo XML models (arena and rodent)
- Coltrane dataset rollout data (PKL format)
- Videos showing MuJoCo simulation synchronized with tracking

### `stick/`
Stick insect (Sungaya inexpectata) experiments:
- STAC analysis notebooks
- Real video data (centered tracking)
- MuJoCo XML models with arena setup
- Rollout videos and tracking data (H5 format)

### `worm/`
C. elegans worm behavior data (directory present for future additions)

## File Types

- **`.ipynb`**: Jupyter notebooks for analysis and visualization
- **`.h5`**: HDF5 files containing pose tracking and rollout data
- **`.xml`**: MuJoCo model definitions
- **`.mp4` / `.m4v`**: Rendered videos of simulations and tracking
- **`.obj`**: 3D mesh files for visual rendering
- **`.pkl`**: Pickle files with serialized trajectory data
- **`.yaml`**: Configuration files for STAC analysis

## Usage

These supplementary materials are intended to accompany the main mimic-mjx project. Each organism directory contains the necessary data and visualization notebooks to reproduce the results shown in the paper.

To explore the data:
1. Open the Jupyter notebooks (`.ipynb`) in each directory
2. Load the corresponding H5 or PKL data files
3. View the rendered videos to see simulation results

## Citation

If you use this data, please cite the associated mimic-mjx paper.

## License

See the main mimic-mjx repository for licensing information.
