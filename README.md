# 环境配置

```
virtualenv --python=%appdata%\..\Local\Programs\Python\Python35\python.exe venv35tf115
cd venv35tf115
Scripts\activate
pip install tensorflow==1.5.0
```



# 原始 readme

## 中文语音识别

##### 1. 环境
- Python：3.5
- Tensorflow : 1.5.0

------

##### 2. 训练数据下载
- 清华大学中文语料库（thchs30）[下载地址](http://www.openslr.org/18/)

------

##### 3. 训练
- 配置conf目录下的conf.ini文件中的各项
- 在终端运行 ```python train.py``` 开始训练
- 在终端运行 ```python test.py``` 测试
- 也可以使用PyCharm打开

