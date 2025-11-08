# Model Training and Testing

## Loss functions and multiple objective optimization
Carefully describe your use of loss functions for training.

Here are some sample questions for a single loss function:
- What does minimizing the loss function accomplish?
- What are typical values of the loss function?
- What are great values for the loss function?

When combining multiple loss function, consider:
- What does each loss function accomplish and how?
- How did you decide to combine the different loss functions in terms of multi-objective optimization?

## Model generalization considerations
Consider the following questions:
- Did your training set loss get reduced significantly?
- How does the training loss compare against the validation loss?
- How do you think your model will generalize on new tests?
- Did you perform any out-of-distribution testing?  

## Documenting model optimization
Consider the following questions:
- Which optimization algorithms did you consider?
- Which learning rate scheduler did you use? (see below).
- What is the underlying hardware and what are the training times for your models? Does it take minutes or hours to train? Document the size of the training set and the number of parameters for your model.
- How fast does your model perform during inference? (give milliseconds, required FLOPs per frame, etc).

## Required table of models' performance versus datasets
Provide a table that contains:
- Each row represents a different model.
- Columns are grouped in terms of the testing datasets.
- Within each dataset group, provide different performance metrics.
- Explain performance in terms of multi-objective optimization.

## Required dataset examples
Provide comparative examples:
- First column should be the ground truth.
- Each column should contain results from a different model.
- Add discussion for the performance.

## [Main optimization link in PyTorch](https://docs.pytorch.org/docs/stable/optim.html)
* [PyTorch optimization methods](https://docs.pytorch.org/docs/stable/optim.html#algorithms).
* [PyTorch vision models training parameters](https://github.com/pytorch/vision/tree/main/references/classification)

## [Pytorch: Adjusting the learning rate](https://docs.pytorch.org/docs/stable/optim.html#how-to-adjust-learning-rate)
* [A (Very Short) Visual Introduction to Learning Rate Schedulers (With Code)](https://medium.com/@theom/a-very-short-visual-introduction-to-learning-rate-schedulers-with-code-189eddffdb00)
* [Step learning rate scheduler](https://docs.pytorch.org/docs/stable/generated/torch.optim.lr_scheduler.StepLR.html)
* [Reduce the learning rate when we reach a plateau](https://docs.pytorch.org/docs/stable/generated/torch.optim.lr_scheduler.ReduceLROnPlateau.html) 

## Model Evaluation Notes
For evaluating your models, consider
   [Model Evaluation, Model Selection, and Algorithm Selection in Machine Learning by Sebastian Raschka.](https://arxiv.org/abs/1811.12808).
