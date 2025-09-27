# 快速开始

环境要求:  
1. Python ≥ 3.10  
2. Redis ≥ 6.0  

步骤:  

1. 获取项目源码并进入项目目录  

```bash
git clone https://github.com/MeoProject/lx-music-api-server
cd lx-music-api-server
```

2. 安装项目依赖

```bash
pip install poetry
poetry install --no-root
```

3. 启动项目以生成配置文件

```bash
poetry run py app.py
```

4. 配置项目