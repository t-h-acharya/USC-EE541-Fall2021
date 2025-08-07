# USC-EE541-Fall2021

This repository contains my solutions to problem sets for EE541: A Computational Introduction to Deep Learning at the University of Southern California (USC) for the Fall 2021 semester. The course, taught by Prof. Brandon Franzke, covers topics such as linear regression, recurrent neural
networks, scikit‐learn, PyTorch, and more.

## Installation
To set up the project dependencies, ensure you have [Conda](https://docs.conda.io/en/latest/) installed. Then, follow these steps:
```bash
# Create a new conda environment
conda create --name ee541 python=3.8

# Activate the environment
conda activate ee541

# Install packages
conda install numpy scipy scikit-learn matplotlib tqdm opencv pandas
conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch
conda install tensorboard
conda install jupyter seaborn h5py

pip install pytorch_model_summary torchsummary flashtorch torchviz
```

## Repository Structure
The repository is organized by homework assignments or problem sets, with each folder containing the relevant code, data, and documentation.

## Usage
This repository is intended for personal reference and educational purposes. Please respect USC's academic integrity policies and do not copy solutions for submission.


To run the code:
1. Clone the repository: `git clone https://github.com/t-h-acharya/USC-EE541-Fall2021.git`
2. Navigate to the desired homework folder.
3. Activate the conda environment:
```bash
conda activate ee541
```
4. Run Jupyter Notebook:
```bash
jupyter notebook pset.ipynb
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Course instructor: Prof. Brandon Franzke

*Note*: This repository is a personal project and not officially affiliated with USC or the EE541 course.