# Kuka_Pybullet for Pick and Place

## Overview

This project provides a simulation environment for robotic manipulation, specifically focusing on pick-and-place tasks using a KUKA robotic arm. Built upon the PyBullet physics engine, it is designed to support research in robotic reinforcement learning, enabling users to integrate it into their RL algorithms for online data collection and performance evaluation.

## Features

*   Simulation of a KUKA IIWA arm with a gripper.
*   Pick and place task setup with objects and trays.
*   Integration with PyBullet for realistic physics simulation.
*   Suitable for reinforcement learning research and development.

## Prerequisites

*   **Python:** The original code was tested on Linux with Python 3.10.12.
*   **uv:** This project uses `uv` for environment and package management. If you don't have `uv` installed, please refer to the official `uv` installation guide.

## Setup and Installation

It is highly recommended to use a virtual environment to manage project dependencies. Follow these steps to set up the project using `uv`:

1.  **Clone the repository (if you haven't already):**
    ```bash
    git clone <repository-url>
    cd Kuka_Pybullet-for-pick-and-place
    ```
    *(Replace `<repository-url>` with the actual URL of the repository.)*

2.  **Create and activate a virtual environment using `uv`:**
    The following command creates a virtual environment in a `.venv` directory.
    ```bash
    uv venv
    ```
    Activate the environment:
    *   On macOS and Linux:
        ```bash
        source .venv/bin/activate
        ```
    *   On Windows (Command Prompt/PowerShell):
        ```bash
        .venv\Scripts\activate
        ```

3.  **Install dependencies using `uv sync`:**
    This command will install packages listed in `pyproject.toml`.
    ```bash
    uv sync
    ```

## Running the Simulation

Once the setup is complete and the virtual environment is activated, you can run the main simulation script:
```uv run python main.py```

![image] (https://github.com/cb614611757/Kuka_Pybullet-for-pick-and-place/blob/master/data/train_image/pick_and_place.png)
 
