# QTAF 

[![Build Status](https://travis-ci.org/Tencent/QTAF.svg?branch=master)](https://travis-ci.org/Tencent/QTAF) 
[![PyPi version](https://img.shields.io/pypi/v/qtaf.svg)](https://pypi.python.org/pypi/qtaf/) 
[![GitHub tag](https://img.shields.io/github/tag/Tencent/QTAF.svg)](https://GitHub.com/Tencent/QTAF/tags/)
![](https://img.shields.io/badge/build-Test%20Fail-red.svg?logo=data:image/jpeg;base64,/9j/4AAQSkZJRgABAQEAYABgAAD/2wBDAAMCAgMCAgMDAwMEAwMEBQgFBQQEBQoHBwYIDAoMDAsKCwsNDhIQDQ4RDgsLEBYQERMUFRUVDA8XGBYUGBIUFRT/2wBDAQMEBAUEBQkFBQkUDQsNFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBT/wAARCAApACoDASIAAhEBAxEB/8QAGQAAAwEBAQAAAAAAAAAAAAAAAAcIBgUE/8QAMxAAAQIFAgQDBgYDAAAAAAAAAQIDAAQFBhESIQcTMWFRcYEIFBUYQbIWIzIzkaGiwdH/xAAXAQEBAQEAAAAAAAAAAAAAAAAGBwUI/8QAKxEAAQMCBAUDBQEAAAAAAAAAAQIDEQAEBQYhQTFRYXGBEhORIkJiobHw/9oADAMBAAIRAxEAPwC+I4dzXrRbPZSuqzzcspYyhrdTi/JI3x36R5uId4t2Pa8xUSkOTBIal2z0U4c4z2GCT2ESTVKrN1qfenZ59czNOq1LcWck/wDB2iZZizIMHIYZSFOkTrwA2nmTsPJpPlTKKseCrm4UUMpMacVHcCdABudeQqivmKtfnaORUtOf3OSjT9+f6ja2zetFvBlS6VPNzKkDK2t0uI80nfHfpEsp4bXcpIUm1q0QRkEU97f/ABjlSc5ULZq4eYW9T6hKuFJBBQttQOClQPqCD5GB7GccTt3Ab5qUH8Sk+CdD5p9dZAwm5aKcOeKXB+QWPIGo7j98KteCM1w8vFu+LXl6iEhuYBLUw2OiXBjOOxyCOxjSxYGH27lpL7RlKgCOxqB3Ns7Zvrt3xC0EgjqP98RSS9pp5xMpb7QzylLfUrw1AIA+5UI2TXLommlTTTj0sFAuNsuBtak/UBRSoA9yD5RUPGmznrttBRlEcyekV+8NIHVYwQpI7437lIES7KzT0hNNTDDimZhlYcQtOxSoHII9YhmcGHGcWLyx9Kwkg9gAR4jh1610nkK6afwRLDZ+pBUCN9SSD5B49OlMdyi2khVvywkKy3UKs1zuS/XWW0MJUohrUv3XqsDVuAAFJJO+2EuFhiVrE0wxIzdNSystrlZ54PPNrGygpQQgdQdtIx3jrL4o3gs5/FFXQcAflzjiNhsBsRHEq9YnbgqDk9UJhc3OOBKVvLxqXpSEgqP1OAMk7nqckwcvLi2eRDKYMj7UjSI2JMzry1jYUztLe5ZXLypEH7lHWZ3AERpz0nc07PZlecVKXA0c8pK2FJ8NRCwftTDtjA8FrOetK0EmbRy56eX7w6g9UDACUnvjfsVERvovmXrdy1wthp0QqJjlJJA+CK5bzVdM3uNXLzBlMxPOAAT5INELS+uBtKuuZcnZF34TPrJUsoRqacPiU5GD3B9DDLgjTvbG2xBr2bpAUn+djxHisfD8Su8Le9+zcKFdOBHIg6Edx8VOny21/nY+JU3lZ/Vqc1fxo/3DAsXgbSrUmW52ed+LT6CFIK0aWmz4hOTk9yfQQy4Iw7TLGFWboebblQ4eokx4On9pFfZyxrEGSw69CTofSAknuRr8EUQQQQroVX//2Q==)

[![QCI](http://127.0.0.1:8000/rest-api/pipeline/1/build/shield)]()


QTA is a cross-platform test automation tool for servers and native, hybrid and applications.

### Supported Platforms

* iOS (powered by [QT4i](https://github.com/tencent/QT4i) driver)
* Android (powered by [QT4A](https://github.com/tencent/QT4A) driver)
* Windows (powered by QT4C driver)
* Web (powered by QT4W driver)
* Server (powered by QT4S driver)

QTAF (QTA Framework) is a base framework for QTA, including,

* testbase
* tuia

### Testbase

Testbase is a test framework providing test execution, reporting and management, and is the common base for each platform-specific QTA driver.

For more inforamtion about quick startup, usage and API reference, please read [testbase's document](http://qta-testbase.readthedocs.io/zh/latest/).


### TUIA

TUIA (Tencent UI Automation) is a base framework for UI test automation, which is used by each platform-specific QTA driver for client.

For more inforamtion about quick startup, usage and API reference, please read [TUIA's document](http://qta-tuia.readthedocs.io/zh/latest/).


------------------------------

QTA是一个跨平台的测试自动化工具，适用于后台、原生或混合型客户端应用的测试。

### 平台支持

* iOS (由[QT4i](https://github.com/tencent/QT4i) driver提供)
* Android (由[QT4A](https://github.com/tencent/QT4A) driver提供)
* Windows (由QT4C driver提供)
* Web (由QT4W driver提供)
* Server (由QT4S driver提供)


QTAF (QTA Framework)是QTA的基础框架，包括以下模块：

* testbase
* tuia

### Testbase

Testbase是测试框架基础，提供包括测试执行、报告和用例管理等基础功能。Testbase会被各个平台的QTA Driver所使用。

快速入门、使用和接口文档请参考《[Testbase文档](http://qta-testbase.readthedocs.io/zh/latest/)》。


### TUIA

TUIA (Tencent UI Automation)是UI自动化基础库，为QTA各个平台下的客户端UI测试Driver所使用。

快速入门、使用和接口文档请参考《[TUIA文档](http://qta-tuia.readthedocs.io/zh/latest/index.html)》。

------------------------------

欢迎加入QQ群（432699528）交流使用和反馈

![image](https://github.com/Tencent/QTAF/blob/master/docs/misc/qq_group.png)
