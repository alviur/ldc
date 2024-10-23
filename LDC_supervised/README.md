# Exemplar-free Continual Representation Learning via Learnable Drift Compensation


## Implementation for Supervised Continual Learning

The code framework is taken from [PyCIL](https://github.com/G-U-N/PyCIL).

### Dependencies
1. [torch 1.81](https://github.com/pytorch/pytorch)
2. [torchvision 0.6.0](https://github.com/pytorch/vision)
3. [tqdm](https://github.com/tqdm/tqdm)
4. [numpy](https://github.com/numpy/numpy)
5. [scipy](https://github.com/scipy/scipy)

### Datasets

We performed experiments for `CIFAR100`, `ImageNet100,`, `TinyImageNet`. When training on `CIFAR100`, this framework will automatically download it.  When training on other datasets, you should specify the folder of your dataset in `utils/data.py`.

```python
    def download_data(self):
        train_dir = '[DATA-PATH]/train/'
        test_dir = '[DATA-PATH]/val/'
```
To download ImageNet-Subset dataset: [Link](https://www.kaggle.com/datasets/arjunashok33/imagenet-subset-for-inc-learn)

### Run experiments

The code for LDC can be found in [models/lwf.py](https://github.com/alviur/ldc/blob/main/LDC_supervised/models/lwf.py).

To use LDC, run

   ```
    python main.py --config=exps/lwf.json
   ```

The configs can be modified in [exps/lwf.json](https://github.com/alviur/ldc/blob/main/LDC_supervised/exps/lwf.json).

