# DnD Campaign Generator
Ethan Chappel (mxk273), Nathan Mauch (nja859), Franscisco Perales (ffn480)

## Setup
### Data
The dataset we used can be downloaded from here:
[https://utsacloud-my.sharepoint.com/:u:/g/personal/mxk273_utsa_edu/EeWZCPr3mA5DgUyAB0-DmGkBJuQRU6CawHUrNqM3Q0krKA?e=q9j9Tf](https://utsacloud-my.sharepoint.com/:u:/g/personal/mxk273_utsa_edu/EeWZCPr3mA5DgUyAB0-DmGkBJuQRU6CawHUrNqM3Q0krKA?e=q9j9Tf)

Copy the `./data` folder to the root of the project directory.

### Install Dependencies
```
python3 -m pip install numpy==1.19.5 tensorflow==2.5.0rc3 notebook
```

## Code
The code is organized in a Jupyter notebook, which runs down the steps of generating a model with brief comments. The program concatenates a dataset from multiple text files into one string and gives it to a GRU model to train on. The model generates a string of 5,000 characters by default. Running it requires Jupyter Notebook.

```
jupyter notebook dnd-campaign-generator.ipynb
```
