## Deep Learning Templates  

### Folder structure
```
  Deep Learning Templates/
  │
  ├── datasets/ - default directory for storing input data
  │   ├── train/
  │   ├── val/
  │   └── test/
  │
  ├── figs/ - created figures for publication
  │   ├── example1.jpg
  │   ├── example2.jpg
  │   └── example?.jpg
  │
  ├── src/ - all codes about data, model, loss, metric, etc.
  │   └── dataloader/ 
  |       ├── MyDataset.py
  |       └── dataload.py
  |
  │   └── losses/ 
  |       ├── common_loss.py
  |       └── custom_loss.py
  |
  │   └── metrics/ 
  |       ├── common_metric.py
  |       └── custom_metric.py
  |
  │   └── models/
  |       ├── base_models.py
  |       └── custom_model.py 
  |
  │   └── utils/ 
  |       ├── data_aug.py
  |       └── mk_plots.py
  |
  │   └── logs/ - default logdir for tensorboard and logging output
  |       ├── weights/
  |       └── training
  |
  ├── train.py - main script to start training
  |
  ├── test.py - evaluation of trained model
  |
  ├── config.json - holds configuration for training
  |
  ├── train_multi_model.py - main script to start training
  |
  |   ...
```

### Usage
```
python train.py -config config.json
```




### License
```
This project is licensed under the MIT License. See  LICENSE for more details
```


### Acknowledgements
This project is inspired by the project [Pytorch-Project-Template](https://github.com/victoresque/pytorch-template) by [victoresque](https://github.com/victoresque)