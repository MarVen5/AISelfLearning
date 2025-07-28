# AISelfLearning

Here I will record what I did when I was self-studying AI.

这里我将记录我自学 AI 时的内容。

---

### Anaconda 安装

### Python 虚拟环境

1. 创建虚拟环境：（此目录下环境名为 ailearn）

```powershell
conda create -n 环境名 python=3.12
```

2. 查看已有虚拟环境：

```powershell
conda info --envs
```

3. 激活虚拟环境：

```powershell
conda activate 环境名
```

4. 退出虚拟环境：

```powershell
conda deactivate
```

### 安装第三方软件包

1. 在线安装：conda 会自动安装包所需的依赖，而 pip 不会；

```powershell
conda install 包名

pip install 包名
```

2. 离线安装：直接在 pypi 上下载编译好的 whl 文件；

```powershell
conda install whl文件

pip install whl文件
```

3. 批量安装：

```powershell
conda install --file requirements.txt

pip install -r requirements.txt
```

requirements.txt 示例：

```txt
pandas
numpy
matplotlib
```

### Jupyter Notebook

1. 安装：

```powershell
conda install jupyter

pip install iupyter
```

2. 启动：

```powershell
jupyter notebook

jupyter lab
```

### Pycharm 适用于大规模项目



