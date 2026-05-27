---
description: Python 环境配置 - 使用 E:\miniconda 中的 Python
alwaysApply: true
---

Python 环境配置

## 本地 Python 路径

- **Python 可执行文件**: `E:\miniconda\python.exe`
- **pip**: `E:\miniconda\Scripts\pip.exe`
- **conda**: `E:\miniconda\Scripts\conda.exe`

## 使用要求

1. **禁止自动搜索系统路径**：不要假设 `python` 命令会找到正确的 Python 环境，始终使用完整路径或确保 PATH 已正确配置
2. **安装包时使用完整路径**：例如 `E:\miniconda\Scripts\pip install xxx`
3. **创建/激活虚拟环境时指定路径**：例如 `E:\miniconda\Scripts\conda create -n myenv` 或 `E:\miniconda\Scripts\python -m venv venv`
4. **执行脚本时优先使用完整路径**：例如 `E:\miniconda\python.exe script.py`

## 常见场景

| 场景 | 正确做法 |
|------|----------|
| 运行 Python 脚本 | `E:\miniconda\python.exe your_script.py` |
| 安装依赖 | `E:\miniconda\Scripts\pip install package_name` |
| 创建虚拟环境 | `E:\miniconda\Scripts\python -m venv venv_name` |
| 检查 Python 版本 | `E:\miniconda\python.exe --version` |
| 激活 conda 环境 | `E:\miniconda\Scripts\activate.bat your_env` |

## 常用工具路径速查

| 工具 | 路径 |
|------|------|
| Python 主程序 | `E:\miniconda\python.exe` |
| pip 包管理器 | `E:\miniconda\Scripts\pip.exe` |
| conda 管理器 | `E:\miniconda\Scripts\conda.exe` |
| 环境激活脚本 | `E:\miniconda\Scripts\activate.bat` |

## 本地 Gradle仓库

- **gradle仓库**: `E:\.gradle`

  
