# My Precious Habits
습관 관리 모바일 어플리케이션

## 개요
- 3학년 2학기 모바일 프로그래밍 기말 프로젝트로 진행
- 개인(1인) 프로젝트
- 첫 네이티브(안드로이드) 어플리케이션 개발
- 자유 주제였는데, 사용자 습관 관리 어플리케이션을 개발하다보면 Database를 다루고 CRUD를 구현해볼 수 있을 것 같아서 진행하게 되었다.

## 이미지
|화면캡처|
|--|--|
|<img src="https://user-images.githubusercontent.com/61059893/159918358-40e24487-b2e7-4556-83ed-04ad46e26325.jpg" width="300" height="400"/>|<img src="https://user-images.githubusercontent.com/61059893/159918391-26a490f1-2dfc-4e38-bb5f-674dd0fed954.jpg" width="300" height="400"/>|



## 기술 스택
- Java
- AndroidStudio
- SQLite

## 기능 소개
1. 회원가입, 로그인, 정보 변경
2. 습관 생성(항목, 날짜, 내용) 및 관리
3. 습관 실행 횟수 누적
4. 레벨링 시스템 - 습관 실행 일정 횟수 도달 시 레벨업

## 배운 점
- SharedPreference 사용 : 키-값 쌍으로 간단한 값들을 저장 관리할 수 있음
- SQLite DB 구축 : 서버가 아닌 응용프로그램에 포함되는 형태인 SQLite를 사용하여 DB구축(습관 관리)
- ListView < RecyclerView : ListView에서는 ViewHolder패턴을 사용하지 않으면 자원이 낭비된다고 하여, RecyclerView 적용하여 리스트 구현

## 부족한 점
- 기능별로 클래스로 구분하지 못한 점
- 디자인
- 미완성 : 습관 마다 알림 시간을 맞추고 해당 시간에 알림창에 알림이 오도록 구현하고 싶었음 (AlarmManger)

