forex-connect-py

FXCM's Forex Connect API wrapper enabling it as Python module

Develompent environment:

* Windows 7 64 bit,
* Visual Studio 2013,
* [PyCharm](https://www.jetbrains.com/pycharm/) for more advanced Python programming
* Python 2.7,
* [Python Tools for Visual Studio](http://pytools.codeplex.com/),
* [Boost 1.55](http://www.boost.org/),
* [Forex Connect API 1.3](http://www.dailyfx.com/forex_forum/forexconnect/392705-forexconnect-api-subscribe-updates-3.html#post1951709)

Python version 2.7 has been chosen as base platform to develop for. The reason is that this project is part of bigger machine learning solution using also another modules (like numpy, scipy, pandas, matplotlib etc.) that are not always available for Python 3.

Precompiled python module

Because it can be difficult to set up dev. environment correctly hence for the time being I've added precompiled Windows 64bit pyd in module subfolder (see /module/x64 subfolder). Place it under you local Python's DLL subfolder. You can use Python projects (i.e. fx.console and fx.market.watcher) as guidance how to use it.
