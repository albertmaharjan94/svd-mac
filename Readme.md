Source : https://github.com/hazimhanif/svd_exp1

Dataset: https://osf.io/d45bw/

Picke Dump File : https://drive.google.com/drive/folders/1jQsoLC-09YY2sULZJaC0dLDDKDWT8iRi?usp=sharing

To resolve the issue of tensorflow error  "tuple has no attribute keys", the version of tensorflow has be downgraded to 2.1.0.
To complete the notebook the following dependencies has been used.

## Dependencies
- python 3.7
- pandas 1.3.3
- numpy 1.19.5
- h5py 2.10.0
- tensorflow 2.1.0

## If tensorflow is to be used in gpu: 
- cuda 10.1
- cudnn 10.0
- cudnn 10.1

Complication in gpu (from my execution) - using (gt-1070 laptop)
- GPU resource maxed out.
- Dst tensor is not initialized.

As a result, the svd was trained on a CPU environment. The CPU neural network training is time consuming, so the samples of both training and validation are sliced to 100000.
Total time of training: 3.5h

The testing is still done on full sample but can be changed.



