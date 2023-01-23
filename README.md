# Autoencoder-Neural-Network
In this question you will implement an autoencoder neural network with a single hidden layer for unsupervised feature extraction from natural images. The following cost function will be minimized:
<img width="843" alt="Screenshot" src="https://user-images.githubusercontent.com/59516214/214036961-0aac210d-829f-4dff-a279-6e877f90a068.png">

(1) The first term is the average squared-error between the desired response and the network output across training samples. Note that the desired output is the same as the input. The second term enforces Tykhonov regularization on the connection weights with parameter λ. The last term enforces that the hidden unit activations are sparse with parameter β for controlling the relative weighting of this term. The level of sparsity is tuned via ρ in the KL term (Kullback-Leibler divergence) between a Bernouilli variable with mean ρ and another
with mean ρˆb. ρˆb is the average activation of hidden unit b across training samples.

You can reach the data from the follwing Google Drive link:
https://drive.google.com/file/d/1B4rT-DcSVc-SJ6qcTt1UIHXgieEjuigv/view?usp=sharing
