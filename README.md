# daily-basic-function
日常基础工具封装，日志，安全文件目录等


## install
```bash
pip install git+https://github.com/jackLi-2024/daily-basic-function.git
```

## 输出执行时间

```python
from daily_basic_function import logger_execute_time

@logger_execute_time(doc="xxx")
def test():
    pass
```

## 文件安全目录

```python
from daily_basic_function import safe_dir
def test():
    with safe_dir() as _dir:
        pass
```

## generate_sorted_uuid
```python
from daily_basic_function import generate_sorted_uuid
```

## pretty_print_dict
```python
from daily_basic_function import pretty_print_dict
```
