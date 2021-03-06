# :deciduous_tree: 시나브로 :deciduous_tree:

## (Open Source Software Development - OurFirstApp) 
### 프론트엔드와 DB(SQLite)를 사용하여 사용자의 하루, 감상, 소망, 목표, 디데이를 설정/기록할 수 있도록 앱을 제작하였습니다 :-D 
### (감정 쓰레기통은 감정을 버리는 것이므로 따로 DB를 구축하지 않았습니다!)
###  Team name : growing 

<br>

**Team member :**

2019056462 LIM DANBI(임단비)

2019036380 LEE DAEUN(이다은)

2019089034 KIM HYUNJIN(김현진)

<br>


**Application description:**

저희는 현대인들이 바쁜 삶 속에서 자신을 좀 더 들여다보고, 여러 긍정적인 변화를 도모할 수 있도록 다양한 기능을 넣어 Application을 개발할 예정입니다. 

Application의 이름은“시나브로”로 정했으며, 이는 "시나브로"의 의미(모르는 사이에 조금씩)처럼 앱을 사용하면서 차곡차곡 긍정적인 변화를 만들어내기를 바라는 마음을 담았습니다. 

또한, “시나브로”가 순우리말인 만큼, Application의 전체 디자인을 되도록 순 우리말로 할 계획이며, 이를 통해 Application 사용자들은 더 많은 순 우리말을 접하고, 동시에 그 단어가 주는 따뜻함을 느낄 수 있게 될 것입니다.

추가 기능과 개발 상황들은 계속해서 README.md와 문서정리 등을 통해 업데이트하도록 하겠습니다.

<br>

- 2020.05.11. 개발 방향선정 회의 (어플리케이션 개발결정)

- 2020.05.13. 어플리케이션 기능 회의

- 2020.05.17. 어플리케이션 기능 회의2, 어플리케이션 표지 선정

- 2020.05.17. ~ 2020.05.24. fragment, data base 학습

- 2020.05.24. 시작화면 splash기능 추가, 어플리케이션 기능 구현방법 회의 및 각자 구현할 기능 분담

- 2020.05.24. ~ 2020.05.30. 맡은 기능 구현하기, data base 학습

- 2020.05.30. fragment 구현, 각자 앱 실행화면 구현, main activity에 띄울 날짜 함수 구현 

- 2020.05.31. ~ 2020.06.03. 각자 맡은 부분 수정, data base 학습

- 2020.06.03. D-day 기능 구현완료 (오픈소스 활용)

- 2020.06.03 감상책 기능 구현 ing, data base 학습

- 2020.06.23 감정쓰레기통 기능 구현완료

- 2020.06.21 ~ 2020.06.25. data base 구현

- 2020.06.24 감상책 기능 구현완료

- 2020.06.25 각 기능별 데이터베이스 구현완료 및 오류 수정


<br>
<br>

### <앱 시작화면(splash) - 3초간 유지 후 MainActivity로 이동>

<div>
<img src="https://user-images.githubusercontent.com/55095806/83333862-b1a3de00-a2dd-11ea-8442-791bb1be10f9.png" width="250">
<div>
  
<br>
<br>

### <앱 첫 화면>

<br>

**-1. 나만의 목표 설정 구현화면**

<br>

<img src="https://user-images.githubusercontent.com/55095806/85561166-50fe8b80-b666-11ea-928a-66f5a5b8fed5.png" width="250">
<img src="https://user-images.githubusercontent.com/55095806/85747802-909aa580-b742-11ea-9943-b4ed7bcb36b0.png" width="250">

<br>
<br>

**-2. 오늘의 날짜, 디데이기능 구현화면**

<br>

<div>

<img src="https://user-images.githubusercontent.com/55095806/83849568-935d3880-a74a-11ea-90df-b8e5ba9058c8.png" width="250">
<img src="https://user-images.githubusercontent.com/55095806/83849565-922c0b80-a74a-11ea-86cf-df42a785773e.png" width="250">
<img src="https://user-images.githubusercontent.com/55095806/83848933-90ae1380-a749-11ea-9a63-a47387becd33.png" width="250">

</div>

##### <D-day 기능 사용방법>

###### 첫 화면에서 Day(Text)를 클릭하면 날짜를 선택할 수 있는 창이 뜬다. 달력에서 내가 원하는 날짜를 설정하면 그에따른 D-Day를 알려준다.
###### * 다직해야  : '기껏해야' 라는 뜻의 순우리말 입니다. 
###### 사용의 목표까지 오랜 시간이 남지 않았음을 응원, 격려하는 마음으로 영어 표현인 'D-day' 대신 '다직해야' 라는 순우리말을 사용했습니다. 

<br>
<br>


### <세부 기능 - 한줄기록, 소망목록, 감정쓰레기통, 감상책>

<br>

**-1. 한줄기록 구현화면**

<br>


<div>
<img src="https://user-images.githubusercontent.com/55095806/85593061-aac07f00-b681-11ea-9504-95b9241e822a.png" width="250">
<img src="https://user-images.githubusercontent.com/55095806/85593260-d6dc0000-b681-11ea-9b1f-42b481dffbe6.png" width="250">
<img src="https://user-images.githubusercontent.com/55095806/85593075-adbb6f80-b681-11ea-8623-dc3f13b0343f.png" width="250">
</div>

<br>
<br>

**-2. 소망목록 구현화면**

<br>

<div>
<img src ="https://user-images.githubusercontent.com/55095806/85593615-291d2100-b682-11ea-89d7-742fe5d9e5ad.png" width = "250">
<img src ="https://user-images.githubusercontent.com/55095806/85593624-2a4e4e00-b682-11ea-915c-1cb65d92b77e.png" width = "250">
<img src ="https://user-images.githubusercontent.com/55095806/85593630-2b7f7b00-b682-11ea-9f1f-8c05b284ec13.png" width = "250">
</div>

<br>
<br>

**-3. 감정쓰레기통 구현화면**

<br>

<div>
<img src ="https://user-images.githubusercontent.com/55095806/85510726-bd5f9780-b632-11ea-8c7e-15234143290c.png" width = "250">
<img src ="https://user-images.githubusercontent.com/55095806/85510723-bc2e6a80-b632-11ea-8209-7c7355c5af5b.png" width = "250">
<img src ="https://user-images.githubusercontent.com/55095806/85510712-b89ae380-b632-11ea-845c-ab76ba23ed5e.png" width = "250">
</div>


<br>
<br>

**-4. 감상책 구현화면**

<br>

<div>

<img src ="https://user-images.githubusercontent.com/56716976/85556098-7dfc6f80-b661-11ea-9bd9-7611d4cec289.png" width = "250">
<img src ="https://user-images.githubusercontent.com/56716976/85556126-83f25080-b661-11ea-8652-c23d9b25ee60.png" width = "250">
<img src ="https://user-images.githubusercontent.com/56716976/85556144-88b70480-b661-11ea-9c7f-15e3519749f2.png" width = "250">
<img src ="https://user-images.githubusercontent.com/56716976/85556172-8fde1280-b661-11ea-978a-406e6a0a1965.png" width = "250">
<img src ="https://user-images.githubusercontent.com/56716976/85556204-97052080-b661-11ea-92a9-173a546357d6.png" width = "250">

</div>

<br>
<br>

**최종 보고서 파일에 세부적으로 다 작성하였으니, 최종 보고서 파일을 다운 받아 봐주시면 감사하겠습니다 :-D**

##### 최종 보고서는 '오픈소스 최종보고서.docx' 를 통해 확인하실 수 있습니다!

<br>

**- Hanyang University ERICA Computer Science -**
