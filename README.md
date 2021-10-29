# neural-tmd-layer
This repository contains the reference code for our paper [Neural TMDlayer: Modeling Instantaneous flow of features via SDE Generators](https://openaccess.thecvf.com/content/ICCV2021/papers/Meng_Neural_TMDlayer_Modeling_Instantaneous_Flow_of_Features_via_SDE_Generators_ICCV_2021_paper.pdf) (ICCV-2021 **oral**)

## Requirements
* Python 3
* Pytorch 1.5+

## Use TMDlayer to replace Self-attention layer in point cloud transformer ([PCT](https://github.com/zihangm/PCT_Pytorch)):
```python
cd ./PCT_Pytorch
```
Follow the instructions in ./PCT_Pytorch to prepare the data and conduct training/testing using the PCT model with our TMDlayer inserted.

The replacement happens in **./PCT_Pytorch/model.py**





