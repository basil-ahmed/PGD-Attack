# PGD-Attack

- Implemented in PyTorch
- Works by using gradient descent to iteratively perturb the input data in a way that maximizes the model's loss function, subject to a constraint that limits the size of the perturbations
- The attack computes the gradient of the loss function with respect to the input data, and then adds a scaled version of the gradient to the input while constraining the size of the perturbations to be no larger than a certain threshold.
- The constraint is typically imposed using a projection operator that maps the perturbed input back onto the set of allowable inputs, such as images that have pixel values in a specific range.

<img width="442" alt="image" src="https://user-images.githubusercontent.com/90772853/223029491-df1bdb3c-d8b1-45c0-b57f-17703636c2c5.png">

## My Output:

![PGD Implementation (2)](https://user-images.githubusercontent.com/90772853/223029533-eaa01511-f0ef-4658-93bc-f1cd2472d43f.png)

![PGD Implementation](https://user-images.githubusercontent.com/90772853/223029544-e6e3723b-34d5-4b60-ad96-8f595552cecc.png)

## Torchattacks implementation:

![PGD_TorchAttack](https://user-images.githubusercontent.com/90772853/223029591-e3286744-ce08-432c-a6a4-86da593a4e30.png)
