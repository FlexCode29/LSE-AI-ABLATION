Sample of the work done at LSE.AI (lseai.org). This is an example of some preliminary exploratory experiments on in-context-learning for linear regression.
We found a preliminary circuit on this toy example, and as a result we have since scaled the rigor of our data generation, and the precision of our model to proceed with our research on this line.

These notebooks check a circuit found by ACDC on GPT-2 for in context linear regression, and find that ablating the rest of the model with activations from a random similar prompt mantains mse at 8.1 (3.2 base)
For reference, an arbitrary reference circuit is considere. Ablating the rest of the model (including the original circuit) increases mse to 15570.3.

These notebooks do not contain the model and data we are currently using, as we employ a gaussian sampler to generate multi-dimensional points, and a custom GPT-2 to perform the regression.
