# Pattern distance
Results, datasets and parameters used in "A novel pattern-based edit distance for automatic log parsing"

# Installation steps
## Common depencies

* Debian, Ubuntu:
```shell
sudo apt update
sudo apt install git jupyter-notebook python3 python3-pip python3-setuptools
```

## LogMine

Install [LogMine](https://github.com/raynalm/logmine) (note this version is slighly adapted from the original one to be compliant with our notebook running the experiments).
```shell
mkdir ~/git
cd ~/git
git clone https://github.com/raynalm/logmine
cd logmine
sudo python3 setup.py install
```
Install its (optional) dependencies:
* via APT (Linux, Ubuntu)
```
sudo apt install python3-unittest2 
```
* via PIP (any operating system)
```
pip3 install unittest
```

## Drain

Install [Drain](https://github.com/IBM/Drain3.git):
```shell
mkdir ~/git
cd ~/git
git clone https://github.com/IBM/Drain3.git 
cd Drain3
sudo python3 setup.py install
```
Install its (optional) dependencies:
* via APT (Linux, Ubuntu)
```
sudo apt install python3-cachetools python3-jsonpickle python3-kafka python3-redis 
```
* via PIP (any operating system)
```
pip3 install -r requirements.txt 
```

