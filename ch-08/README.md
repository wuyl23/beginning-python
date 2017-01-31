# 第8章 异常


* `raise Exception` 引发异常
* `exceptions`: 内建异常模块
* `try`: 捕捉异常
* `except <ExceptionName>`: 引发异常执行
* `else`: 没有引发异常执行
* `finally` 是否有异常都会执行


* 如果捕捉到了异常，但是又想重新引发它，那么可以调用不带参数的 `raise`
* 如果需要用一个块捕捉多个类型异常，那么可以将他们作为`元组`列出
