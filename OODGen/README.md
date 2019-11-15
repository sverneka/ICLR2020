Run experiemtns on image dataset

#############################

Each experiment mentioned in the paper has a separate Jupyter Notebook file

Step 1: Run the notebook up to training a VAE and  Creating jacobians.

Step 2: Run create_nullspaces.py to create nullspace. Note Offline nullspace computation takes up a large space (>50 GB). Hence one can do online nullspace creation while training the classifier. But training would take much longer in that case. One can resort to parallel computing if compute is available as everything can be parallelized.

Step 3: Run the classifier training part of the notebook to get final results.






.
