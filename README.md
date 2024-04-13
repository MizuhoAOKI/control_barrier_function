[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Poetry](https://img.shields.io/endpoint?url=https://python-poetry.org/badge/v0.json)](https://python-poetry.org/)

# Control Barrier Function Example

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
    poetry run python scripts/cbf_vel_control.ipynb
    ```


## References

### Papers
1. Peter Wieland and Frank Allgöwer, "CONSTRUCTIVE SAFETY USING CONTROL BARRIER FUNCTIONS"
    - URL : https://www.sciencedirect.com/science/article/pii/S1474667016355690
1. Aaron D. Ames, et al. "Control Barrier Functions: Theory and Applications"
    - URL : http://ames.caltech.edu/ames2019control.pdf

### Articles
1. https://qiita.com/seria_hina/items/afd96b930ade860926bc
