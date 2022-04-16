
5.1

Identifying the lowest and the highest learning rate for the cyclic learning rate policy.

5.2

Training a Conv-Net model and observing the training/validation accuracy and loss vs epochs.

5.3

Experimenting and checking if the increasing batch size has the same effect as decreasing learning rate for a fixed batch size. I have experimented starting with batch size of 32 incrementing till batch size 16384. I have plot the training loss vs batch size and infered that using cyclic learning rate policy is better than increasing batch size. (code run on NYU HPC)
