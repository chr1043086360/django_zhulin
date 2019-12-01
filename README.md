# 毕业设计Django后台项目
- 实验室内部项目
- 请先配置.env环境：https://github.com/chr1043086360/python-dotenv
- 在python3.5之后的版本可以通过内置的命令创建虚拟环境
```bash
python -m venv .venv
```
```bash
source .venv/bin/activate
```
- 通过which查看python是否是虚拟环境的python

```bash
which django-admin
```
- 后面可以加上./避免太多层嵌套
```bash
django-admin startproject project ./
```
- 导入导出需求包
```bash
pip freeze > requirements.txt
```
```bash
pip install -r requirements.txt
```


