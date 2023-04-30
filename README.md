# few-shot-image-classification

## Download Data

```commandline
wget -O master.zip https://github.com/alexeygrigorev/clothing-dataset-small/archive/master.zip && \
unzip master.zip && \
rm master.zip && \
mv clothing-dataset-small-master data
```

## Install requirements

```
conda create --name FewShot python=3.8
```

### Torch

#### GPU
```
conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia
```

#### CPU
```
conda install pytorch torchvision torchaudio cpuonly -c pytorch
```

### Requirements

```commandline
pip install -r requirements.txt
```