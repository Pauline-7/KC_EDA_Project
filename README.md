# ds-eda-project-pauline

This project is about the analysis of housing data in kings county in Seattle area. 
The task was to fetch, clean and analyse data for an independently chosen client. 
This project deals with the client Zachary Brooks, he sells and invests in historical houses, in best neighborhoods, with high profits. He requested suggestions for the best timing within a year to sell properties and he wonders about the benefit of renovating houses before selling them. 

## 1. Assignment details
- assignment.md
- column_names.md
- workflow.md
- requirements.txt

## 2. Data
- df_eda.csv (initial data)
- historical_houses_in_good_neighborhoods (cleaned up data)
- csv_map.html (html file of map)

## 3. Data preparation
- EDA_fetch_data.ipynb (data fetching)
- EDA_hypotheses_and_clean_up.ipynb (pre-analysis & data cleaning)

## 4. Final results
- EDA_project_results.ipynb (most relevant outcomes of analysis)
- EDA_presentation.pdf (presentation slides)

## Requirements

- pyenv
- python==3.11.3

## Setup

* setting the python version locally to 3.11.3
* creating a virtual environment using the `venv` module
* activating your newly created environment 
* upgrading `pip` (This step is not absolutely necessary, but will save you trouble when installing some packages.)
* installing the required packages via `pip`

## Set up your Environment
This repo contains a requirements.txt file with a list of all the packages and dependencies you will need.

Before you can start with plotly in Jupyter Lab you have to install node.js (if you haven't done it before).
- Check **Node version**  by run the following commands:
    ```sh
    node -v
    ```
    If you haven't installed it yet, begin at `step_1`. Otherwise, proceed to `step_2`.


### **`macOS`** type the following commands : 


- `Step_1:` Update Homebrew and install Node by following commands:
    ```sh
    brew update
    brew install node
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :


- `Step_1:` Update Chocolatey and install Node by following commands:
    ```sh
    choco upgrade chocolatey
    choco install nodejs
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
  
    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
 

 **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:

   ```Bash
   python.exe -m pip install --upgrade pip
   ```

