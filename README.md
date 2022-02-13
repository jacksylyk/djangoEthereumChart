# djangoEthereumChart

Installation

Install **selenium**, **BeautidulSoup 4**, using these following:
```
pip install -U selenium
```
```
pip install bs4
```
Usage
**Login etherscan.io**

```
from bs4 import BeautifulSoup
from selenium import webdriver

url = 'https://etherscan.io/accounts'
driver = webdriver.Firefox()
driver.get(url)
```
