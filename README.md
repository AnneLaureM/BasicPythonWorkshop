# BasicPythonWorkshop
This course provides a comprehensive guide to setting up Python virtual environments with Miniconda, working with data structures, manipulating Pandas DataFrames, applying algorithmic principles, utilizing regular expressions, and efficiently handling file operations.

# Advanced Python Workshop

## Overview
This Jupyter notebook covers essential and advanced Python concepts, focusing on:
- **Setting up Python virtual environments with Miniconda**
- **Understanding and using Python data structures**
- **Manipulating data with Pandas DataFrames**
- **Applying algorithmic principles**
- **Using regular expressions for pattern matching**
- **Reading and writing to files in Python**

This guide is structured for both beginners and advanced users who want to strengthen their Python programming skills with practical exercises.

## Prerequisites
To get started, ensure you have the following installed:
- **Miniconda** (or Anaconda) for virtual environment management
- **Python 3.x**
- **Jupyter Notebook** (installable via `conda` or `pip`)

## Installation and Setup
1. Install Miniconda:
   - [Download Miniconda](https://docs.conda.io/en/latest/miniconda.html)
   - Follow the installation instructions for your operating system.
   
2. Create a new Conda environment:
   ```bash
   conda create --name python_workshop python=3.9
   conda activate python_workshop
   ```

3. Install necessary Python libraries:
   ```bash
   conda install pandas numpy jupyterlab
   pip install regex
   ```

4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## License
This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.

### GNU GPL-3.0 License Citation:
```
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.
```

## Contribution
Contributions are welcome! If you'd like to improve this notebook:
- Fork the repository
- Create a new branch (`feature-branch`)
- Make your changes and commit (`git commit -m "Added new feature"`)
- Push the branch (`git push origin feature-branch`)
- Submit a pull request

## Author
Developed by AnneLaureM. If you have suggestions or feedback, feel free to reach out!