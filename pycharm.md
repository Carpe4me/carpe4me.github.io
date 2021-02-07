# 파이참을 이용해서 코딩하기

## 파이썬 코드 실행 방법

### 코드 전체 실행

- Run 메뉴 이용 : 전체 실행
- Alt + Shift + e : 선택된 영역만 실행

### 변수값 쉽게 확인하기 (Show Variables)

- 'Python Colsole' 창의 'Show Variables' 아이콘 이용

### 파이참에서 if 문 쉽게 입력하기 (Postfix Completion)

- '포스트 픽스 postfix' : .if 입력

  - ``` python
    a= =2.if
    if a= = 2:
    ```

  - white, return, print 문 사용 가능

  - Editor - General - Postfix Completion

  - ![image-20210205221418505](D:\gitHub\carpe4me.github.io\screenshot\Postfix Completion)

### 주석으로 'TODO' 관리하기

- File - Settings - Editor - TODO

### 'PEP8' 코딩 스타일 적용 - black 패키지

- pip install black
- File - Settings - Tools - External Tools : + black 추가
  - ![image-20210205225605480](D:\gitHub\carpe4me.github.io\screenshot\pycharm\ExternalTools-Black)

### 파이썬 패키지 관리

- Settings - 'Project:<프로젝트명>'  - 'Project Interpreter'
  - ![image-20210205230320044](D:\gitHub\carpe4me.github.io\screenshot\pycharm\Project Interpreter)



## 코드 탐색 효율적으로 하기

- 최근 파일 찾기 : Ctrl + E
- 다른 파일/도구창 이동 : Ctrl + Tab
- 다른 프로그램에서 파일 열기 : Alt + F1
- 탐색 바로 이동 : Alt + Home
- 함수 단위로 이동 : Alt + 상하 화살표
- 함수 제일 상단과 하단으로 이동 : Ctrl + { or }
- 특정 라인으로 이동 : Ctrl + G
- 클래스, 함수, 변수 찾고 이동하기 : View - Tool Windows
- 전에 커서가 있었던 위치 찾기 : Naviage - Forward
  - Ctrl + Alt + { Left, Right }
- 전역 찾기 : Search Everywhere, 'shift' 키를 2번 누르기
- Quick Documentation : Ctrl + Shift + I
- 앞/뒷 문자 선택(단어 단위) : Shift + Ctrl + {좌, 우 화살표}
- 확장하면서 선택하기: Ctrl + W, 반대 : Shift + Ctrl + W
- 코드 위/아래로 이동 : Shift + Alt + {위, 아래 화살표}
- import 문 정리 : Ctrl + Alt + O
- 자동 들여쓰기 : Ctrl + Alt + I
- 파일, 변수명 바꾸기 (Refactor) :  **Shift + F6**
- 튜토리얼 쉽게 보기 : Python External Documentation - **Shift + F1**
  - File - Settings - Tools - 'Python External Documentation'
    - pandas : https://pandas.pydata.org/pandas-docs/stable/generated/{element.qname}.html
    - seaborn : https://seaborn.pydata.org/generated/{module.name}.{element.name}.html#{module.name}.{element.name}
    - matplotlib : http://matplotlib.org/api/{module.basename}_api.html#{element.qname}
- 에러 메세지 구글 검색하기 :
  - ![image-20210205235836518](D:\gitHub\carpe4me.github.io\screenshot\pycharm\google)
  - 에러 메세지 발생 -> Ctrl + C   -> 구글 Search
- 코드 탬플릿
  - File - Settings - Editor - Code Style - File and Code Templates
- 라이브 템플릿
  - File - Settings - Editor - Color scheme - Live Templates

## 파이참 플러그인

- Material Theme UI
- CSV Plugin
- Nyan Progress Bar
- Grep Console 
  - Console 에 키워드 등록 : 색깔 구분, 정규식 이용
- String Manipulation
  - 문자 편집에 유용한 플러그인
  - 대소문자 바꾸기, 정렬하기, 필터, 중복된 행 삭제 등
- Rainbow Brackers
  - 괄호 구분

