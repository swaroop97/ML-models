# ML-models — data analysis & visualization template

This repository is a small **Python data science template**. It uses **pandas** for tabular data, **matplotlib** for a sample bar-chart visualization (`revenue_visual.py`), and **pytest** for unit tests (`test_calculations.py`). Dependencies are split between `requirements.txt` (runtime) and `dev-requirements.txt` (testing). Use it as a starting point for analysis scripts, charts, and simple automated checks.

## Running the Sample

- Open the template folder in VS Code
- Create a Python virtual environment using the **Python: Create Environment** command found in the Command Palette. Ensure you install dependencies found in the `requirements.txt` file
- Ensure your newly created environment is selected using the **Python: Select Interpreter** command found in the Command Palette
- Run `calculations.py` using the Play Button in the top right corner or by selecting **Python > Python File in Terminal** from the context menu or Command Palette
- Run `revenue_visual.py` using the Play Button in the top right corner or by selecting **Python > Python File in Terminal** from the context menu or Command Palette to generate the bar graph visual
- To test the Python code, install `dev-requirements.txt` into your virtual environment. 
- Navigate to the Test Panel to configure your Python test or by triggering the **Python: Configure Tests** command from the Command Palette
- Run tests in the Test Panel or by clicking the Play Button next to the individual tests in the `test_calculations.py` file

