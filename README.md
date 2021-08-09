# Cyseg
## Usage
Get help : `python cyseg.py --help` <br>
Training example : `python cyseg.py train -d datasets/train/ -epochs 5 -classes 2 -weights 0 1 -save unet.pth` <br>
Inference example : `python cyseg.py segment -d datasets/valid/ -classes 2 -load unet.pth -thresh .5` <br>

## Setup
1. Create a Python virtual environment <br>
2. Run `sh setup.sh` inside the virtual environment <br>
