# Ml_Lab_3

# Implementation of the prune defence.

The Dataset can be found [here]https://drive.google.com/drive/folders/1O1h65Yv9h3xHEDF5sF35WFUmjX_fFm7c?usp=sharing

According to the instructions given in the lab description, we must save the models when the accuracy drop was at 2%, 4% and 10% respectively. The models can be found in the repository.

To evaluate the models, you have to first import the required packages present at the beginning of the notebook.Next, load the original badnet and the dataset. You can start running the code from the Evaluate the Combined Model section directly. The attack success rate when the accuracy drops at least 30%: 6.954187234779596

Looking at the graph, we can see that the prune defense is not too successful here. I believe the attack is prune aware attack that the pruned model is retrained with poisoned data. And the weight is changed again so that the model has the wrong predition.
