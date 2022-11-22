# 2022년도 하계 계절제 현장실습
 <h2> 회사명 : <a href = "https://userinsight.co.kr/"> 유저인사이트 </a> </h2>

 * 수행 기간 : 2022.06.22 ~ 08.17 (8주)
 
 * 참여 프로젝트  
   * React Native 기반의 모바일 채팅 애플리케이션 "ITZY"
   * React 기반의 ITZY 관리자 웹 애플리케이션
   * Spring Boot + Spring Data JPA + QueryDSL + Thymeleaf 기반의 스마트팜 생육/생산 환경 조성 데이터 제공 웹 애플리케이션 <a href = "https://www.bizinfo.go.kr/web/lay1/bbs/S1T122C128/AS/74/view.do?pblancId=PBLN_000000000075234&cpage=26&rows=15&condition=&keyword=&hashCode=">(2022년 SW 융합 서비스 모델 개발 및 사업화 지원 사업)</a>
  * 버전 관리 도구 : <a href="https://yona.io/">Yona</a> 
  * 맡은 업무 : 애플리케이션 유지 보수 및 기능 개발
------------
각 주차 간의 해결 내용은 아래 표와 같습니다.

| 주차 | 수행 내용 | 사용 언어 |
|:-----:|:------------------|:-----------------------------:|
|1W| 환경 설정 및 프로젝트 분석 | React |
|2W| 관리자 페이지의 네이버 지도를 Google Map으로 변경 | React |
|3W| 환경 설정 및 프로젝트 분석 | React Native |
|  | 개인 채팅방 PUSH 알림 오류 수정 | Firebase Cloud Messaging |
|  | 공개 채팅방 PUSH 알림 구현 | Firebase Cloud Messaging |
|  | 친구 신청 수락 시 push 알림 클릭한 경우, 상대방 닉네임 데이터 미전달 결함 해결 | React Native + Firebase |
|  | Push 알림 클릭 시 채팅방 이동 후 다시 메인화면으로 이동되는 결함 해결 | React Native + Firebase |
|4W| ios 환경에서 app icon badge count 설정 | React Native + Firebase |
|  | 개인 채팅방 리스트에서 마지막 메시지 보낸(받은)시간이 표시되도록 수정 | React Native + Firebase |
|  | 공개 채팅방과 개인 채팅방에서 2명 이상의 사용자에게 push 알림이 전송되도록 수정 | React Native + Firebase |
|  | 초대된 채팅방에서 push 알림을 클릭하여 방에 접속할 경우 roomName이 갱신되도록 수정 | React Native + Firebase |
|5W| 환경 설정 및 프로젝트 분석 | Spring Boot |
|6W| RawData 엔티티 설계 및 연관관계 모델링 | Spring Boot + Spring Data JPA + QueryDSL + Thymeleaf |
|  | RawData 관리 페이지 글 추가, 글 수정 기능 구현 | Spring Boot + Spring Data JPA + QueryDSL + Thymeleaf |
|  | RawData 데이터 관리 페이지 페이징 처리 구현 | Spring Boot + Spring Data JPA + QueryDSL + Thymeleaf |
|  | QueryDSL을 활용하여 RawData 데이터를 chart로 시각화 | Spring Boot + Spring Data JPA + QueryDSL + Thymeleaf  |
|7~8W| RawData 데이터 관리 페이지의 검색 필터 구현하기 | Spring Boot + Spring Data JPA + QueryDSL + Thymeleaf |
|  | 생육환경(Environment) 페이지 추가/수정 기능 추가 | Spring Boot + Spring Data JPA + QueryDSL + Thymeleaf  |
|  | 동(Shelf)과 생육환경(Environment) 엔티티 간 1:n 관계 모델링 | Spring Boot + Spring Data JPA + QueryDSL + Thymeleaf |
|  | @Where을 활용하여 동(Shelf) 엔티티에서 start_date와 end_date가 유효한 생육환경(Environment)만 나타나도록 구현| Spring Boot + Spring Data JPA + QueryDSL + Thymeleaf |
|  | 동(Shelf) 페이지에서 생육 환경의 수동 데이터 입력을 위한 form 페이지 구현 | Thymeleaf |
|  | 입력된 수동 데이터 저장 기능 및 저장 후 동(Shelf) 페이지로 리다이렉션 구현 | Spring Boot + Spring Data JPA + QueryDSL + Thymeleaf |
