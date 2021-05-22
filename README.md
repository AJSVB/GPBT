# GPBT

- `FSN`: experiments environment and data processing
  - `FSN/final_notebook.ipynb` and `FSN/Boston_analytics.ipynb` for Boston
  - `FSN/MNIST.ipynb` and `FSN/MNIST_analytics.ipynb` for MNIST
  - `FSN/FMNIST.ipynb` and `FSN/FMNIST_analytics.ipynb` for FMNIST
  - `FSN/CIFARanalytics.ipynb`for data processing of CIFAR

  - Raw data from such experiments are in `FSN/data_brut` folder
  - Treated outputs are in `FSN/data_result` folder. 

- `TO_GPU` is the folder for CIFAR that was sent to a GPU
  - Run `TO_GPU/dependencies.sh` to run CIFAR-GPBT experiment.
  - There are files `TO_GPU/bohb1.py`, `TO_GPU/pbt.py` for other models as well. 
- `result_TO_GPU`: outputs of the GPU computations

