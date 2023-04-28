Stage 4.

Improper hyperparameters setting, like bad Delta_max which fails to limit the depth of recursive tree buiding process, will cause overflow, which renders the sampling point wandering in low probability region.

Thus it is necessary to decide the unknown relation between model parameters and algorithm hyperparameters.

MLP regression is promising for this task.

This is a training data producer, outputting Delta_max corresponding to different Hamiltonian model parameters randomly chosen.