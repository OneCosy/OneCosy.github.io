---
layout: single
title:  "1.1 라이브러리 & 프레임워크"
categories: "DesignPattern" 
tags: [Libaray, Framework, CS]
toc: true
toc_sticky: true
toc_label: "목차"
author_profile: true
sidebar:
    nav: "docs"
search: true
---

# 라이브러리
<hr>

소프트웨어의 구성요소 중 한가지로, API를 바탕으로 대상 환경(플랫폼)에서 바로 실행될 수 있게 **<mark style='background-color: #E1EAF3'>모듈화</mark>**된 프로그램 모음을 의미한다. 

소프트웨어를 개발할 때 컴퓨터 프로그램이 사용하는 비휘발성 자원의 모임. 즉, **<mark style='background-color: #E1EAF3'>특정 기능을 모아둔 코드, 함수들의 집합</mark>**이며 코드 작성시 <u>활용 가능한 도구들</u>을 의미한다.

라이브러리는 혼자서 동작하는 완전한 프로그램이 아닌, <u>특정한 부분 기능만을 수행하도록 제작된 프로그램</u>이다. 이 자체로는 사용자가 직접 일반적인 조작으로 실행할 수 없으며, **<mark style='background-color: #E1EAF3'>해당 라이브러리의 기능을 직접 호출</mark>**하는 프로그램을 실행해야 한다.

* **<span style='color: #96BBF3'>표준 라이브러리</span>**<br>
특정 언어의 <u>개발 환경에 기본적으로 포함된 것들</u>은 대부분 표준 라이브러리라고 불린다. 기본적인 기능 수행과 더불어 <u>디버깅, 성능측정 등을 위한 별도의 API가 존재</u>한다.

* **<span style='color: #96BBF3'>런타임 라이브러리</span>**<br>
프로그램이 실제 환경에서 <u>실행되기 위해 필요한 모듈들이다.</u> 대부분 표준 라이브러리에서 <u>기능 수행에 필요한 것들만 제공</u>되거나, 스크립트의 실행기 등을 말한다.

<br>

**<span style='font-size:20px'>라이브러리 종류</span>**
* Python pip로 설치한 패키지/모듈 (tensorflow, pandas, beautifulsoup 등)
* C++의 표준 템플릿 라이브러리 (STL)
* Node.js에서 npm으로 설치한 모듈
* HTML의 클라이언트 사이드 조작을 단순화하는 JQuery
* 웹에서 사용자 인터페이스 개발에 사용되는 React.js
<br><br><br>

# 프레임워크
<hr>

원하는 목적을 달성하기 위해 복잡하게 얽혀있는 문제를 해결하기 위한 구조이며, 일정한 형태와 필요한 기능을 갖추고 있는 <u>골격, 뼈대</u>를 의미한다. 애플리케이션 개발 시 필수적인 코드, 알고리즘, DB 연동과 같은 기능들을 위해 어느 정도 뼈대를 제공하며 이러한 뼈대 위에서 사용자는 코드를 작성하여 애플리케이션을 개발한다. 

앱/서버 등의 <u>구동</u>, <u>메모리 관리</u>, <u>이벤트 루프 등</u>의 공통된 부분은 프레임워크가 관리하며, 사용자는 <u>프레임워크가 정해준 방식</u>대로 클래스, 메서드들을 구현한다.

<br>

**<span style='font-size:20px'>프레임워크 종류</span>**
* Java 서버 개발에 사용되는 <u>Spring</u>
* Python 서버 개발에 사용되는 <u>Django</u>, <u>Flask</u>
* 안드로이드 앱 개발에 사용되는 <u>Android</u>
* 아이폰 앱 개발에 사용되는 <u>Cocoa Touch</u>
* 웹 개발에 사용되는 <u>Angular</u>, <u>Vue.js</u> 등
* 자바 기반의 JSP를 위한 프레임워크 <u>Struts</u>
* 루비로 작성된 MVC 패턴을 이용하는 <u>Ruby on Rails</u>

<br>

# 라이브러리와 프레임워크 차이점
<hr>

사실 위의 설명들은 정확한 설명이 아닌, **<mark style='background-color: #E1EAF3'>대략적인 느낌</mark>**만 설명한 것이라고 보면 된다. 라이브러리와 프레임워크의 차이를 명확히 설명하는 것은 거의 **<span style='color: #F06666'>불가능</span>**에 가깝다. 

보통 프레임워크라고하면 여러 기능을 가진 **<mark style='background-color: #E1EAF3'>클래스와 라이브러리</mark>**가 특정 결과물을 구현하고자 **<mark style='background-color: #E1EAF3'>합쳐진 형태</mark>**라고 볼 수 있다. 따라서 대부분의 프레임워크들은 <u>다양한 기능들을 지원</u>하기 위해 많은 라이브러리들을 가지고 있다. 하지만 이 분류법도 예외가 있다.

메소드 및 클래스화, 즉 **<mark style='background-color: #E1EAF3'>모듈화</mark>**를 하는 이유 중 하나가 **<span style='color: #F06666'>재사용성</span>**인데, 프레임워크는 이 재사용성을 <u>큰 그룹 단위로 묶어주었다고</u> 보면 된다. 재사용 가능한 수많은 클래스들과 라이브러리들을 <u>융합</u>한 채로 처음부터 제공해주기 때문에, 여러 개의 표준을 만들지 않아도되서 개발자의 피곤함을 덜어준다.

예를 들어, <u>웹 프레임워크</u>는 '웹 서버'를 구현하기 위한 목적으로 만들어진 프레임워크이다. 웹 서버를 구현하기 위해선 페이지 구현, DB 관리, 유저 인증 등 많은 기능들이 들어있어야 할텐데, **<mark style='background-color: #E1EAF3'>각 기능을 보유한 라이브러리들을 한데 묶어 담은 것</mark>**이 프레임워크라고 보면 된다.

따라서 본인이 사용하는 프레임워크가 <u>자신에게 맞지 않을 때</u>는 라이브러리 단계로 들어가서 **<mark style='background-color: #E1EAF3'>자신에게 맞는 프레임워크로 변경</mark>**해서 사용할 수 있다.

현재는 만든 사람이 라이브러리라고 하면 라이브러리이고 프레임워크라고하면 프레임워크로 굳는 분위기이다. FE프레임워크로 자주 예시를 드는게 Vue와 React이고 이 둘은 일반적으로 우리가 이야기하는 프레임워크 정의에 완벽하게 부합하지만, **<mark style='background-color: #96BBF3'>Vue</mark>**는 <u>본인을 프레임워크라고 소개</u>하고 **<mark style='background-color: #96BBF3'>React</mark>**는 <u>본인을 라이브러리라고 소개한다.</u>

또한 **<mark style='background-color: #96BBF3'>유닛테스트</mark>**를 보통 우리는 프레임워크라고 부르는 경향이 있는데 언어마다 유닛테스트를 <u>어떤 관점</u>으로 보는지 또한 완전히 다르다.
<br><br><br>

> ※ 참고자료<br>
> 주홍철, 면접을 위한 CS 전공지식노트 (출판지: 길벗, 2022)<br>
> [https://namu.wiki/w/프레임워크](https://namu.wiki/w/프레임워크)