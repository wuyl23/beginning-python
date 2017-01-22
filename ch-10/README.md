# 第10章 充电时刻

**在哪里寻找模块**

* sys.path: 解释器在该列表中查找模块
* PYTHONPATH: 环境变量
* 路径配置文件: `.pth`

	import sys
	sys.path.append()
	sys.path.expanduser()
	
	
**模块测试**

	if __name__ == '__main__': 
	
### 包

* 为了组织好模块，你可以将他们分组为包(package), 
* 包就是模块所在的目录: `__init__.py` 文件

### 探究模块

* dir / `__all__` : 查看模块包含的内容
* `__all__`: 定义模块的公有接口(public interface),从模块导入所有名字代表什么含义
* help / `__doc__`:
* `__file__`: 源代码


### 标准库

* sys
* os
* fileinput
* sets
* time
* random
* re