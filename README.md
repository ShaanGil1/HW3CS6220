# HW3 CS6220
# Installation
- Install conda from: https://www.anaconda.com/ <br>
- Extract all files into a folder <br>
- In the root of the folder run the following line using conda command line<br>
```
conda env create -f environment.yml
```
```
conda activate HW3
```
- Run the Colab_filtering.ipynb <br>
- Run all cells and the models should run <br>
- Note that all data cleaning is done on the original dataset which is not in these files and need to be downloaded <br>
- All results will be pasted into a .csv file after model completion
# Computer Specs
- CPU: AMD Ryzen 5800X 8-Core (only used CPU)
- 32 GB DDR4 RAM
# Files
- model.ipynb : File that does everything, cleans data, runs models and pastes results into .csv file.
- rmse_test.csv : Test set used for calculating RSME
- top_test.csv : Test set used for Top 1, Top 5 and Top 10 metrics
- results.csv : Prints out of all metrics after all models have been run
- environment.yml : env file that has all the used packages/versions

