## WaaS Express

## I. 안내
### I-1. 과제 하는 방법
* 신입생 여러분들을 위한 express 예제 page 입니다.
* 매일 하루 안에 수행할 수 있는 과제를 1개씩 내드릴 겁니다.
* 각자 과제를 수행하면 fork한 자신의 github repo의 readme에 다음과 같은 형식으로 작성하면 됩니다.

``` markdown
### 12월 23일
* todo list의 제목을 "HelloTODO"로 하기 위해서는 localhost:3000/todo________ 로 접근해야 함
```

* 하루 안에 해결할 수 있는 과제로 월~금 수행을 하고 나면 토요일까지 기한을 드리고 수합해 검사할 예정이고, 그 사이 기간에도 자유롭게 질문을 진행하시면 됩니다.
    * URL을 해당 주 금요일까지 @정연길 에게 제출해주시면 됩니다.

### I-2. 멘토 제도
* 12월 23일 ~ 27일 주가 지나고 남은 학생들에 대해서는 WaaS 팀 멤버들이 멘토로 붙어 별도로 웹개발 학습에 대한 조언을 드릴 예정입니다. 

### II. 과제

#### 12월 23일
1. 제공된 express 서버를 구동한다.
2. localhost:3000/todo에 접근해보고, 상단의 제목을 "HelloTODO"로 하기 위해서는 **어떤 URL로 접근해야 하는지 찾아 작성한다.**
    * Hint: get parameter
    * Hint2: req의 input 종류 - params, query, body, cookie
3. 2번을 수행해봤다면 EJS의 의미를 대략 이해할 수 있음. EJS는 HTML에 server의 parameter를 포함시켜 전송할 수 있도록 해주는 module이다.

#### 12월 24일
1. 제공된 express 서버를 구동한다.
2. localhost:3000/form에 **postman**을 이용해 접근해보고, 아래와 같이 결과를 얻으려면 설정해야 하는 **URL, query, body** 설정을 기록한다.
    * 예시
    ![12_24_ex](./docsimg/12_24_example.png)
    * **과제 문제**
        1. GET 요청, success가 3번 반복될 것
        2. POST 요청, success가 7번 반복될 것
        3. PUT 요청, success가 5번 반복될 것
        4. DELETE 요청, success가 1번 반복될 것
    * 기존에 올려줬던 PPT의 HTTP Method를 결부해 이해하면 좋을 것 같습니다.
    * Hint: Body 입력 시 "x-www-form-urlencoded"를 선택하세요!
3. readme.md에 작성되어 있는 형식을 참고헤 2의 4가지 결과의 screenshot을 같이 첨부한다.
