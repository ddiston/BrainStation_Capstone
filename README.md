# The AI Pianist

All code and data for this project can be found in the respective folders of this repository. 

### Full Project Directory:

The project directory requires 487MB on disk, and includes all data and code required to build out all datasets used in this project. Full build out of all datasets will require 13.8GB on disk. Please see the Jupyter notebook section below for details on building out project datasets. All data and notebooks have been arranged within the project directory to ensure local paths in code function correctly. Ensure that the desired notebook is placed in the working directory with the associated data directory for pathways to function.

<img src="Images/Figure%201%20_%20Sample%20Composition%20Plot.jpg" alt="sample" width="1000"/>

### Required Python Libraries/Packages:

##### Built-In Packages

    - os
    - random
    - shutil
    - itertools

##### Standard Libraries

    - numpy
    - pandas
    - matplotlib
    - sklearn
    - tensorflow

##### Non-Standard Libraries

    - mido (pip install mido)
    - pretty.midi (pip install pretty_midi)

This project includes 4 different model types. Each are listed below with their associated Jupyter notebooks. Note that dataset build out must be performed for the model before running any modeling code. Jupiter Notebooks have been numbered in the order they should be read/run:

##### Human vs. Computer Model:

    01-Computer_Pianist-Create_CSV.ipynb
    02-EDA_and_Visualization.ipynb
    03-Human_MIDI_Quantizer.ipynb
    04-Computer_MIDI_Quantizer.ipynb
    05-Velocity_Quantizer.ipynb
    06-Array_Converter.ipynb
    07-Test_Set_Split.ipynb
    08-Array_Sampler.ipynb
    09-RNN_Human_Detection.ipynb

##### Top 10 Composers Model:

    10-Composer_Model_Data_Preparation.ipynb
    11-RNN_Model_Composers.ipynb
    
<img src="Images/10%20Class%20Confusion%20Matrix.jpg" alt="results" width="600"/>

##### Century Classification Model:

    12-Composer_Year_Model_Data_Preparation.ipynb
    13-RNN_Model_Years.ipynb

##### Binary Composer Classification:

    14-Two_Comp_Data_Preparation.ipynb
    15-Debussy_Mozart_Model.ipynb
    16-Prokofiev_Rachmaninoff_Model.ipynb

### Directory Breakdown:

    2Comp -> Binary Composer Classification Data
    Composer_Year -> Century Classification Model
    Composers -> Top 10 Composers Model
    HumComp -> Human vs. Computer Model
    Models -> Saved Models and Weights
    Raw-Midi -> The raw .midi dataset I downloaded and labeled

### Additional Files:

    midi_files.csv -> The csv I created to Explore and Visualize the data
    The AI Pianist.pptx -> An updated Deck including final test set results

For Additional Info, please refer to the introductory markdown of each Jupyter Notebook, or the provided Project Report
