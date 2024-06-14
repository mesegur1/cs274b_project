# CS274B Project 
Project Repo for CS274B

Experiments are contained in the following files:
1. `hmm_experiments.ipynb`: Contains Hidden Markov Model Feature Extraction Classifer
2. `dkf_experiments.ipynb`: Contains Deep Kalman Filter Feature Extraction Classifier

## Instructions for running
1. Download and extract `all_accelerometer_data_pids_13.csv` from dataset (`https://archive.ics.uci.edu/dataset/515/bar+crawl+detecting+heavy+drinking`)
2. Place `all_accelerometer_data_pids_13.csv` in folder `data/`
3. Execute `python data_combined_reader.py` to create PKL files with windowed data
4. Run code in Jupyter Notebooks.
