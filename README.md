## 安装
RecBole可以在以下几种系统上运行:

* Linux
* Windows 10
* macOS X

RecBole需要在python 3.7或更高的环境下运行。

RecBole要求torch版本在1.7.0及以上，如果你想在GPU上运行RecBole，请确保你的CUDA版本或CUDAToolkit版本在9.2及以上。
这需要你的NVIDIA驱动版本为396.26或以上（在linux系统上）或者为397.44或以上（在Windows10系统上）。

python版本不要过高，python3.11以上可能报错，推荐python3.8

### 从Conda安装

```bash
conda install -c aibox recbole
```

### 从pip安装

```bash
pip install recbole
```

### 下载依赖
```
pip install -r requirements.txt
```
## 快速上手

```bash
python run_recbole_group.py
```

usage: run_recbole_group.py [-h] [--model_list MODEL_LIST] [--dataset DATASET] [--config_files CONFIG_FILES] [--valid_latex VALID_LATEX] [--test_latex TEST_LATEX]
                            [--nproc NPROC] [--ip IP] [--port PORT] [--world_size WORLD_SIZE] [--group_offset GROUP_OFFSET]