[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Poetry](https://img.shields.io/endpoint?url=https://python-poetry.org/badge/v0.json)](https://python-poetry.org/)

# Control Barrier Function Example

<!-- https://github.com/MizuhoAOKI/control_barrier_function/assets/63337525/e6407a02-2b1f-4b04-bbc4-0cb408916f30 -->
https://github.com/MizuhoAOKI/control_barrier_function/assets/63337525/36dc97ea-8573-433f-976e-a3bcc91b7118

The algorithm was successfully implemented in a real car. 

(Once the obstacle is removed, the vehicle automatically restarts moving forward.)

https://github.com/MizuhoAOKI/control_barrier_function/assets/63337525/d735f495-5054-4ff7-9b38-d011a2ca2579

## Dependency

- [python](https://www.python.org/)
  - version 3.10 or higher is recommended.

- [poetry](https://python-poetry.org/)
  - seting up python environment easily and safely.
  - only `numpy`, `matplotlib`, `notebook` are needed to run all scripts in this repository.

- [ffmpeg](https://ffmpeg.org/)
  - mp4 movie writer
  - <details>
    <summary>installation details</summary>

    - For Ubuntu Users
        - `sudo apt-get update`
        - `sudo apt-get -y install ffmpeg`
    - For Windows Users
        - Install [scoop](https://scoop.sh/)
        - `scoop install ffmpeg`
    - For macOS Users
        - Install [homebrew](https://brew.sh/)
        - `brew install ffmpeg`
    - Check the official website if necessary
        - https://ffmpeg.org/

    </details>

## Setup
```sh
git clone https://github.com/MizuhoAOKI/control_barrier_function.git
cd control_barrier_function
poetry install
```

## Usage

### Collision-Avoidance Velocity Control
- Run simulation
    ```sh
    cd control_barrier_function
    poetry run jupyter notebook notebooks/cbf_vel_control.ipynb
    ```

## References

### Papers
1. Peter Wieland and Frank Allgöwer, "CONSTRUCTIVE SAFETY USING CONTROL BARRIER FUNCTIONS"
    - URL : https://www.sciencedirect.com/science/article/pii/S1474667016355690
1. Aaron D. Ames, et al. "Control Barrier Functions: Theory and Applications"
    - URL : http://ames.caltech.edu/ames2019control.pdf

### Articles
1. https://qiita.com/seria_hina/items/afd96b930ade860926bc
