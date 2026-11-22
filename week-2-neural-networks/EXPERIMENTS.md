# Week 2 experiment log

Run `Vimal_Week2_Neural_Networks.ipynb` from a clean runtime. Fill this file with actual values after execution; no placeholder results are supplied.

| Run | Model / setting | Dataset split | Metric | Value | Notes |
|---|---|---|---|---|---|
| NumPy XOR | 4 hidden neurons, lr=0.8 | 4 XOR rows | final MSE | _fill after run_ | |
| Tabular NN | 64/32 MLP, 80 epochs | fixed 80/20 split | MAE/RMSE/R² | _fill after run_ | |
| CNN | 3 conv layers | CIFAR-10 subset | accuracy | _fill after run_ | Record subset size and epochs |
| ResNet18 frozen | ImageNet weights, new head | same subset | accuracy | _fill after run_ | |
| ResNet18 fine-tuned | layer4 + head | same subset | accuracy | _fill after run_ | |
| Regularisation | dropout / weight decay / early stop / noise | fixed validation split | validation MSE | _fill after run_ | |

## Reproducibility

Seed: 42. Record Python, PyTorch, torchvision versions, Colab hardware/runtime, subset sizes, and any changes to epoch counts. Report the measured CPU/GPU timing rather than assuming GPU is faster.
