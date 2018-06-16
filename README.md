# InterPark Crawling Project

## Test Environment

- Language : Python3
- Tool : Anaconda, Jupyter Notebook
- OS : Window 10 64bit
- FrameWork : selenium
- Library : Beautifulsoup
- DataBase : MariaDB

## Installation

- Anaconda 에서 Selenium 설치
  ```
  pip install selenium
  ```
<br>

- Chrom driver를 다운받고 chromdriver.exe 을 작업 폴더 안에 넣어준다.
[Chrome Driver 다운 받기 ](https://sites.google.com/a/chromium.org/chromedriver/downloads)
<br>

- MariaDB 설치

- Jupyter notebook 에서 작업하게 되면, 다른 클래스 파일을 import 시킬 때 import 시킬 수 있는 module 이 필요하다.
  * installation

  ```
  pip install nbimporter
  ```

  * usage

  ```
  import nbimporter
  from DbMgr import DbHelper as Db
  ```

## 크롤링 확인 결과 및 DB 확인

![image](https://user-images.githubusercontent.com/33097467/41500092-c8b65c48-71c6-11e8-9b5c-cf96877f9fb7.png)

![image](https://user-images.githubusercontent.com/33097467/41500072-5e66df70-71c6-11e8-97e8-69ee3a713ab7.png)
