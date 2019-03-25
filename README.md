# GAT-Stroke

Graph attention network for stroke classification.

### Requirements

all Linux distributions no earlier than Ubuntu 16.04

Python 3.5 or later

PyTorch 1.0

### Installing

pip install -r requirements.txt

### Data

Download data.tar.gz and edge.tar.gz from

https://drive.google.com/drive/folders/1-0tRJGNZGBWgmMJ6NIzUN8QY115MBLWO?usp=sharing

and put the data in the same directory of the code.

### Usage

tar -zxvf data.tar.gz

tar -zxvf edge.tar.gz

python train.py

You can use the following command to display the training option:

python train.py --help
