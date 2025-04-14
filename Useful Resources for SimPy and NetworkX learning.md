# Some Useful Resources for self-learning SimPy and NetworkX Python Libraries.

This document outlines useful resources for learning two important Python libraries.
---

## 1. SimPy learning resources

You have two popular options for managing your project's dependencies:

- **Conda:** Ideal if you have multiple dependencies including C libraries (e.g., geopandas, PyPSA). It uses YAML files.
- **pip and virtualenv/venv:** Great for pure Python projects and when you want lightweight environments using a `requirements.txt` file.

---

## 2. NetworkX learning resources

### 2.1. Using Conda

1. **Create an Environment YAML File:**  
   Prepare a file (e.g., `environment_project1.yaml`) that lists all the required dependencies for a specific research project. For example, for the "Urban Road Network Resilience Analysis" project:
   
   ```yaml
   name: urban_road_analysis
   channels:
     - conda-forge
     - defaults
   dependencies:
     - python=3.9
     - pandas
     - numpy
     - networkx
     - geopandas
     - matplotlib
