# Installation Guide 🛠️

To get started with DockNScore, follow these steps to set up the pipeline and its dependencies.

## Prerequisites

Before installing DockNScore, ensure you have the following prerequisites:

- **Python 3.x**: If not already installed, you can download it from the [official Python website](https://www.python.org/downloads/).
- **Conda (Optional)**: If you prefer managing packages with Conda, you can install it by following the instructions on the [Conda documentation](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).

## Installation Steps

1. **Install Python Libraries**:

   - **Option 1: Install with Conda (Recommended)**:

     ```bash
     conda create -n docknscore_env python=3.x
     conda activate docknscore_env
     conda install pandas tqdm colorama rdkit
     ```

   - **Option 2: Install with pip**:
     ```bash
     pip install pandas tqdm colorama rdkit
     ```

   Installing with Conda is recommended as it provides better package management and avoids potential conflicts with other Python packages. Alternatively, you can install each library separately with pip.

   If you choose to install with pip, you can also install each library separately with the following commands:

   ```bash
   pip install pandas
   pip install tqdm
   pip install colorama
   pip install rdkit
   ```

2. **Install External Tools**:

   - **Open Babel**: Follow the installation instructions provided on the [Open Babel website](https://open-babel.github.io/getting.html).
   - **AutoDock Vina**: Refer to the [AutoDock Vina download page](https://vina.scripps.edu/download.html) for installation instructions.

3. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/DockNScore.git
   ```

Now you're all set to start using DockNScore for your cheminformatics and molecular modeling tasks!
