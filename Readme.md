Layerd Architecture

api
|- view : presentation layer - endpoint 정의, request 받기
|- service : business layer - 로직 구현
|- model : persistence layer - 데이터베이스 접속
|- app.py : 앱을 실행해 모든 레이어의 변수들을 연결해주는 기능 

출처 : https://velog.io/@matisse/%EB%A0%88%EC%9D%B4%EC%96%B4%EB%93%9C-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98-%ED%8C%A8%ED%84%B4