# Drug Modality Distribution Analysis from OTP Data

Analysing patterns in the distribution of drug modalities based on the subcellular location of drug targets, utilising datasets provided by Open Targets.


## Description

This project aims to analyse the correlation between drug modalities and the subcellular locations of their targets using datasets from the Open Targets Platform. The datasets utilised include:

* Drug target data
* Drug specific data
* Drug mechanisms of action (MoA) data

These datasets are available at: [Open Targets Platform Downloads](https://platform.opentargets.org/downloads)

The goal is to investigate and identify significant distribution patterns of drug modalities based on the subcellular location of their targets.


## Getting Started

### Dependencies

Minimum requirements: 
* Python 3.7 or later
* Libraries listed in `requirements.txt`
* Operating System: Any (Windows, macOS, Linux)


### Installing

To get started, download the repository files. If you're unfamiliar with this process, you can find detailed instructions [here](https://docs.github.com/en/repositories/working-with-files/using-files/downloading-source-code-archives).

Before running the notebooks, ensure you have the necessary libraries installed in a virtual environment:

1. Open the repository folder in your preferred code editor (I recommend VSCode).

2. Create a virtual environment by executing the following commands in your terminal and activate it:

    ```bash
    python -m venv venv
    .\venv\Scripts\activate
    ```

3. Install the required libraries listed in `requirements.txt` using pip:

    ```bash
    pip install -r requirements.txt
    ```

4. Install the `ipykernel` package to ensure proper execution of Jupyter Notebooks:

    ```bash
    pip install ipykernel
    ```

These steps will set up your environment with the required dependencies for executing the notebooks seamlessly.


### Executing program

The project utilises Jupyter Notebooks for its intuitive and cohesive structure, enhancing usability. Each notebook includes comments within code blocks for easier understanding.

Below is the prescribed sequence for executing the notebooks:

    1_Dataset_Inspection.ipynb

    2_Preprocessing.ipynb

    3_EDA.ipynb

    4_Visualise_Analysis_Results.ipynb


This structured layout encompasses inspection, data preprocessing, exploratory data analysis (EDA), and visualisation, providing a comprehensive approach to the project's objectives.

**_Run each of the .ipynb files from within the python interpreter._**

Descriptions of data, along with information on inputs and outputs, are included within markdown sections in the notebooks.


### Additional Information

Any intermediary and supplementary data files, steps, or visualisations, are saved within the /data folder of the repository. This folder structure helps maintain organisation and accessibility throughout the project workflow.


## Help

Message me regarding issues or for general queries!


## Authors

[Henry Shelton](https://github.com/Henry-Shelton)


## Version History

* 0.1 (06/04/2024)
    * Initial Release


## License

This project is licensed under the MIT License - see the LICENSE.md file for details


## Acknowledgments

* [Open Targets Platform](https://platform.opentargets.org)
* EMBL-EBI