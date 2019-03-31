# Huawei Reservation Script

Help pitiful Huawei freshman reserve their entry date.

## Getting Started

These instructions will tell you how to use thi script.

### Prerequisites

A serve or your personal computer, a cup of coffee will be better if you want.

### Installing

Run instruction below to download this code to your server.

```
git clone git@github.com:hyson666/Huawei-Reservation-Script.git
```


Next, you need to download chromedriver for running this script, using site below:

http://chromedriver.storage.googleapis.com/index.html

Please download according to your environment, and put it into the folder of this script.

chromedriver版本	支持的chrome版本
v2.46	v71-73
v2.43	v69-71
v2.42	v68-70
v2.41	v67-69
v2.40	v66-68
v2.39	v66-68
v2.38	v65-67
v2.37	v64-66
v2.36	v63-65
v2.35	v62-64
v2.34	v61-63
v2.33	v60-62
v2.32	v59-61
v2.31	v58-60
v2.30	v58-60


## Running the script

Use below instruction to run the script.

```
python script.py --id your_id --pwd your_password --mon month_to_reserve
```

## Authors

* **Hyson** - *HFUT Student*



## Analysis

argparse 是python自带的命令行参数解析包，可以用来方便地读取命令行参数。它的使用也比较简单。

Selenium-WebDriver 操作、模拟浏览器行为以及操作浏览器页面元素。


Selenium的好处，直接模拟浏览器行为，如click，避免了更为复杂的直接操作get/put等http信息。

### 启动Chrome

from selenium import webdriver
from selenium.webdriver.chrome.options import Options

实例化一个启动参数对象


chrome_options = Options()




添加启动参数
chrome_options.add_argument('--window-size=1366,768'

将参数对象传入Chrome，则启动了一个设置了窗口大小的Chrome
browser = webdriver.Chrome(chrome_options=chrome_options)


Selenium手册，https://www.jianshu.com/nb/25338984

* **Hyson** - *HFUT Student*

