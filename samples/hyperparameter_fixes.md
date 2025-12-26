Parameters :-

1. Epochs :
    The number of times AI goes through the training data.

    Recommended value : 2-3
    Problem : AI memorizes instead of learning (overfitting).
    Change : Fewer epochs reduce overfitting.

2. Learning rate :
    Controls how fast the AI model updates its knowledge.

    Recommended value : 1-5
    Problem : hallucinations, instruction drift.
    Change : Lower learning rate ensures more stable updates & reducing the risk of unsafe outputs.

3. Batch size :
    The number of data samples AI processes at once.

    Recommended value : 8–16
    Problem : Noise and unstable optimization.
    Change : Larger batch size stabilizes estimation, smoothing updates.

4. Gradient clipping :
    Process that helps maintain numerical stability by preventing the gradients from growing too large.

    Recommended value : 1.0
    Problem : Sudden behavioral regressions.
    Change : Prevents extremely large updates that can destabilize training.

5. Warmup steps :
    Use a very low learning rate for a set number of training steps

    Recommended value : 10%-15%
    Problem : Reducing instruction drift.
