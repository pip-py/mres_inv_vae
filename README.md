# Invariance in Variational Auto-Encoders: Evaluation of Latent Representation for Image Classification 2024-11

From paper:

### MNIST

<p align="center">
  <img src="https://github.com/user-attachments/assets/7bc356a4-e72b-4d76-b497-ef98d2552fcd" alt="MNIST Transforms"/>
</p>

### VAE model:

<p align="center">
  <img src="https://github.com/user-attachments/assets/af2c1898-bbbd-45ee-ad21-634a6296b102" alt="Model Architecture"/>
</p>


### Full Assignment Doc:

[**Link to PDF**](https://github.com/pip-py/mres_inv_vae/blob/main/Invariance%20in%20Variational%20Auto-Encoders%20JM%2020241105%20v10.pdf)


### Feedback from formative:
- Brief comments on formative – apologies for formatting/grammar. Generalised comments on canvas as well.
- Nice to see example transformations of the image, and a definition of a range of datasets (the task was underspecified in this regard).
- Figure labelling was mismatched - your text refers to Figure 1 as the architecture. VAE diagram looks good.
- Is the encoder just a linear transformation of the data? Or is it one hidden layer? Not quite clear.
- It would have been helpful to see what the loss function was for the VAE, and the classifier, - in particular what likelihood function you used? If it was just MSE - rather than a Gaussian negative log likelihood with a small variance, it might underfit the data.
- A confusion matrix for the best performing model would have been nice to see - which things get confused? It can also be helpful to do some qualitative evaluation of which datapoints were confidently classified incorrectly.

### My reflection:
Thoroughly enjoyed the project and identified plenty of gaps in my approach which I addressed throughout my discussion. I found the feedback very informative and will be particularly considering explicit in-depth definitions/figures of model architecture, explicit definition of loss function as well as including ablation/qualitative review of results also.
