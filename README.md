## How to Run
### Training PARL
To train models with PARL loss run the notebook *train_parl.ipynb*.

Specify the required training parameters in the cell below *PARL Training Specification*.

Run the cell below *Train* to start training.


### Evaluation
To perform black box transfer attacks run the notebook *attacks.ipynb*.

Specify the dataset in the cell below *Load Clean Data*.

Run PGD (with restarts), MDI2-FGSM and SGM individually by running the respective cells and generate the adversarial samples.

Run the cell below *Perform All Attacks* to evaluate robustness.


### Additional Data and Pre-Trained Models
We are also sharing some pretrained ResNet20 models and the 1000 randomly sampled clean images (normalized) and their respective labels for both CIFAR-10 and CIFAR-100 dataset in *additional*. Nomenclature is similar to what is used in the notebooks.
