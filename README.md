# Missevan downloader

猫耳广播剧下载工具

有问题请邮件liuyiling.windy610@bytedance.com
github绑的邮箱很少看了

## 使用方法

`python downloader.py` 或者 `python3 downloader.py`后按提示操作. 使用哪种方法取决于你电脑里是否有多版本python。

支持广播剧列表(含有drama的地址.例: https://www.missevan.com/mdrama/drama/25276) 或单个音频(例: https://www.missevan.com/sound/player?id=2236921), 程序会自动识别

如果需要下载付费广播剧则需要输入cookie(开发者模式里自己找), 否则下载到付费剧的时候会报错, 我懒得把200检查加进去了.

## 运行环境

Python 3.7

仅使用re, os, requests三个库,全是默认自带的

部分人可能提示缺requests库，如果有提示 No module named 'requests'，请在命令行下pip install requests（mac下或电脑里有多环境，则执行pip3 install requests）
