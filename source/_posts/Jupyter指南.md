---
title: Jupyter指南
date: 2022-9-28 11:45:14
expires: 2023-08-31 23:59:59
categories:
    - "Python"
    - ”Jupyter“
tags: 
    - ”Jupyter“
    - "Python"
    - "机器学习"
    - "学习"
thumbnail: "/img/download.png"
sticky: 999
---

## Jupyter 安装



```bash

jupyter lab --allow-root --no-browser

# 先换源
pip config set global.index-url https://pypi.douban.com/simple/
# 一行命令搞定
pip install jupyterlab
```

## 生成配置文件并修改



```bas
# Input
jupyter lab --generate-config

# Output
Writing default config to: /root/.jupyter/jupyter_lab_config.py
```



## 代码格式化工具



```bash
# 安装格式化工具
# 安装插件
pip install jupyterlab_code_formatter 
pip install black isort
```

##  汉化与主题安装



```bash
pip install theme-darcula
pip install jupyterlab-theme-solarized-dark
pip install jupyterlab-language-pack-zh-CN
```

