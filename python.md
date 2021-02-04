[Using % and .format() for great good!](https://pyformat.info/)  

## Python Unit test ##
[Workshop: Unit Testing in Python](https://www.slideshare.net/DavidTan26/workshop-unit-testing-in-python)  
[Testing in Python: doctest and unittest](https://www.slideshare.net/fadirra/testing-in-python-doctest-and-unittest)  
[Pragmatic Introduction to Python Unit Testing (PyDays 2018)](https://www.slideshare.net/pkofler/pragmatic-introduction-to-python-unit-testing-pydays-2018)  
[Visual testing with PyCharm and pytest PyCon 2018](https://www.slideshare.net/testandcode/visual-testing-with-pycharm-and-pytest) *PyCharm pytest illustration Project*  
SlideShare.net [Mocking in Python-pytest](https://www.slideshare.net/excellaco/mocking-in-python-44973320)  

## Resource ##
[Python 资源大全中文版](https://jobbole.github.io/awesome-python-cn/)  

## blog ##  
*GIL* [Concurrent Programming in Python is not what you think it is](https://melvinkoh.me/concurrent-programming-in-python-is-not-what-you-think-it-is-cjn39wijd009e25s19bb6pb17?ref=hackernoon.com)  

## Book ##

*DOUG HELLMANN* [THE PYTHON 3 STANDARD LIBRARY BY EXAMPLE](https://doughellmann.com/blog/the-python-3-standard-library-by-example/)  

## package & distribute ##  
[python Binaries and Dependencies](https://python-packaging-tutorial.readthedocs.io/en/latest/binaries_dependencies.html)  
[How pip install Works](https://pydist.com/blog/pip-install)  
[What Are Python Wheels and Why Should You Care?](https://realpython.com/python-wheels/)  

## python moudle ##  
[What’s __init__ for me](https://towardsdatascience.com/whats-init-for-me-d70a312da583)  

## Python Java bridges  
[A brief overview of Python-Java bridges in 2020](https://talvi.net/a-brief-overview-of-python-java-bridges-in-2020.html)  

## JPype Known limitations
[JPype Known limitations](https://jpype.readthedocs.io/en/latest/userguide.html#jpype-known-limitations)
1. Restarting the JVM  
1. Running multiple JVM  

## debug with GDB  
[centos 7.x 版本下用gdb 调试 python3.6.3 解释器](https://www.jianshu.com/p/1794c0fd94b6)  
[Debugging of CPython processes with gdb](https://www.podoliaka.org/2016/04/10/debugging-cpython-gdb/)  
[Easier Python Debugging](https://fedoraproject.org/wiki/Features/EasierPythonDebugging)  
[使用 gdb 调试运行中的 Python 进程](https://mozillazg.com/2017/07/debug-running-python-process-with-gdb.html)  

## debug with PDB  
[Python PDB doc](https://docs.python.org/3.7/library/pdb.html)  

    # setting pdb on
    %pdb on
    
    # enable step trace
    from IPython.core.debugger import set_trace
    set_trace()
    
    # insert a breakpoint
    breakpoint /usr/local/python3.7/lib/python3.7/site-packages/xxx/zzz.py:150
