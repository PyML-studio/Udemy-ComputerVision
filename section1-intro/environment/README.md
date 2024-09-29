

 * Create a conda environment

```
conda create -n py311 python=3.11
conda activate torch2.1
```

Find the proper installtion based on your OS (https://pytorch.org/get-started/locally/)

 * For MacOS:
```
conda install pytorch::pytorch torchvision torchaudio -c pytorch
```

* For Linux:
```
# with GPU
conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia
```

```
# or without GPU
conda install pytorch torchvision torchaudio cpuonly -c pytorch
```

 * For Windows:
```
# with GPU
conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia
```

```
# or without GPU
conda install pytorch torchvision torchaudio cpuonly -c pytorch
```

 * Install the rest of requirements

```
pip install -r requirements.txt 
```
