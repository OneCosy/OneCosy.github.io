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
<hr/>

공통으로 사용될 수 있는 특정한 기능들을 **<mark style='background-color: #E1EAF3'>모듈화</mark>**한 것을 의미한다.

소프트웨어를 개발할 때 컴퓨터 프로그램이 사용하는 비휘발성 자원의 모임. 즉, **<mark style='background-color: #E1EAF3'>특정 기능을 모아둔 코드, 함수들의 집합</mark>**이며 코드 작성시 <u>활용 가능한 도구들</u>을 의미한다.

**라이브러리 종류**
* Python pip로 설치한 패키지/모듈 (tensorflow, pandas, beautifulsoup 등)
* C++의 표준 템플릿 라이브러리 (STL)
* Node.js에서 npm으로 설치한 모듈
* HTML의 클라이언트 사이드 조작을 단순화하는 JQuery
* 웹에서 사용자 인터페이스 개발에 사용되는 React.js

여기서 **<mark style='background-color: #E1EAF3'>React</mark>**는 프레임워크인 줄 알았지만 리엑트 홈페이지에도 프레임워크가 아닌 <u>라이브러리</u>로 분류된다고 나와있다.

**<mark style='background-color: #E1EAF3'>Express.js</mark>**는 홈페이지에 <u>Web Framework</u>라고 나와있다.
<br/><br/><br/>

# 프레임워크
<hr/>

원하는 기능 구현에 집중하여 개발할 수 있도록 일정한 형태와 필요한 기능을 갖추고 있는 <u>골격, 뼈대</u>를 의미한다. 애플리케이션 개발 시 필수적인 코드, 알고리즘, DB 연동과 같은 기능들을 위해 어느 정도 뼈대를 제공하며 이러한 뼈대 위에서 사용자는 코드를 작성하여 애플리케이션을 개발한다. 

앱/서버 등의 구동, 메모리 관리, 이벤트 루프 등의 공통된 부분은 프레임워크가 관리하며, 사용자는 프레임워크가 정해준 방식대로 클래스, 메서드들을 구현한다.

**프레임워크 종류**
* Java 서버 개발에 사용되는 <u>Spring</u>
* Python 서버 개발에 사용되는 <u>Django</u>, <u>Flask</u>
* 안드로이드 앱 개발에 사용되는 <u>Android</u>
* 아이폰 앱 개발에 사용되는 <u>Cocoa Touch</u>
* 웹 개발에 사용되는 <u>Angular</u>, <u>Vue.js</u> 등
* 자바 기반의 JSP를 위한 프레임워크 <u>Struts</u>
* 루비로 작성된 MVC 패턴을 이용하는 <u>Ruby on Rails</u>

<br/>

> ※ 참고자료<br/>
> 주홍철, 면접을 위한 CS 전공지식노트 (출판지: 길벗, 2022)