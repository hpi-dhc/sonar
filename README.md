# SONAR Code Submission

## Setup
Create a virtualenv with the required packages with the provided `environment.yml`

Run the following command in a terminal in this folder to create one.

```
conda env create --file=environment.yml
```

## Dataset

To run the code, please download the [SONAR_ML](https://zenodo.org/record/7693087) dataset. Once you have downloaded the dataset, please change the variable directory `dataset_root_dir` in the `src/utils/config.py` file to specify the path to the dataset on your local machine. This variable should point to the root directory where the dataset is located.

After setting the `dataset_root_dir variable, you can run the code using your preferred Python environment or IDE.

## Running the Code

Make sure that you have enough RAM available (in the best case more than 64GB). Then switch to the created environment (default name: `note-paper` -> `conda activate note-paper`) and run `python src/main.py` to start the script.

Afterwards, you should have a file `results.csv` in this folder with all model information and results.
