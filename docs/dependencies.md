# Dependencies 📦

DockNScore relies on the following Python libraries and external tools to function properly:

## Python Libraries

- **pandas**: A powerful data manipulation and analysis library. Pandas provides easy-to-use data structures and data analysis tools, making it an essential tool for working with molecular data. You can learn more about pandas on the [official pandas website](https://pandas.pydata.org/).

- **tqdm**: A library for adding progress bars to iterables. tqdm enhances the user experience by providing visual feedback on the progress of long-running tasks. To learn more about tqdm and its features, visit the [tqdm GitHub repository](https://github.com/tqdm/tqdm).

- **colorama**: Provides cross-platform support for colored terminal text output. Colorama allows DockNScore to produce visually appealing output in the terminal, improving readability and user experience. Explore more about colorama on the [official colorama website](https://pypi.org/project/colorama/).

- **rdkit**: A collection of cheminformatics and machine learning tools for handling molecular data. RDKit is widely used in the cheminformatics community for tasks such as molecular structure representation, substructure searching, and molecular property prediction. Dive deeper into RDKit by visiting the [RDKit GitHub repository](https://github.com/rdkit/rdkit).

  - **rdkit.Chem**: A submodule of RDKit providing additional chemistry-related functionality. rdkit.Chem extends the capabilities of RDKit with additional methods and classes specifically designed for chemical data processing and analysis. Learn more about rdkit.Chem in the [official RDKit documentation](https://www.rdkit.org/docs/).

- **glob**: A module for file path expansion using wildcard patterns. glob facilitates file manipulation and retrieval, allowing DockNScore to work with multiple files efficiently. You can find more information about glob in the [Python Standard Library documentation](https://docs.python.org/3/library/glob.html).

## External Tools

- **Open Babel**: A chemical toolbox designed to speak the many languages of chemical data. Open Babel is used in DockNScore for file format conversion and manipulation, enabling seamless integration with various molecular file formats. Explore the capabilities of Open Babel on the [official Open Babel website](https://open-babel.github.io/).

- **AutoDock Vina**: A molecular docking program for drug discovery. AutoDock Vina is utilized by DockNScore for conducting docking simulations, allowing users to predict the binding modes and affinities of small molecules with target proteins. Learn more about AutoDock Vina and its features on the [AutoDock Vina website](http://vina.scripps.edu/).

Ensure that all dependencies are properly installed before using DockNScore for your cheminformatics and molecular modeling tasks. For more in-depth information about each dependency, we encourage you to visit the respective websites provided above.
