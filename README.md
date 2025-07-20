# Persistent-Homology-Dimension_SER
applying PHD on speech emotion recognition tasks
##  About This Project

This project is part of my undergraduate thesis, in which I explored a topological approach to estimate the **intrinsic dimension** of neural networks using **persistent homology**.

The method is based on the findings of the following paper:  
👉 [Intrinsic Dimension,Persistent Homology and Generalization in Neural Networks
]([https://arxiv.org/abs/2111.13171])  
Using their approach, I applied the technique to a different task: **Speech Emotion Recognition (SER)**.

We observed that the estimated intrinsic dimension (referred to as **PHD**) correlates with the model's generalization performance. Specifically:

- When **PHD was higher**, the **generalization error increased**.
- When **PHD was minimized**, the **model's performance improved**.

This confirms the key insight of the original paper:  
> The intrinsic dimension of a neural network can be used as an indicator of how well the model generalizes.

In addition, the PHD score can be used as a **regularization metric** during training, helping guide hyperparameter tuning to reduce overfitting.

###  SER Experiment

I successfully applied the method on the SER task using the RAVDESSو,TESS,SAVEE datasets. The results confirmed that lowering the PHD also led to a lower generalization error, consistent with the original paper's conclusion.
