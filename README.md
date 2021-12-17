# Ml_Lab_3
##Dataset
According to the instructions given in the lab description, we had to save the models when the accuracy drop was at 2%, 4% and 10% respectively. The models can be found in the repository.

To evaluate the models, you have to first import the necessary packages present at the beginning of the notebook. Call loadData, getAccuracyAndASR and the following code cells till you finish the model's initialisation. You can move to Evaluate the Model section directly and run the code from that point The attack success rate when the accuracy drops at least 30%: 6.954187234779596

Looking at the graph, we can see that the prune defense is not too successful here. I believe the attack is prune aware attack that the pruned model is retrained with poisoned data. And the weight is changed again so that the model has the wrong predition.
