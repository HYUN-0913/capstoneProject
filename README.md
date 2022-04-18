
## 주제 : IOT 기반 옥외놀이터 모니터링 및 안전관리 시스템
  이화여자대학교 2020년 캡스톤디자인프로젝트로 진행한 프로젝트 입니다.

## 시연영상 (유투브 채널 주소)
https://www.youtube.com/watch?v=1UByyChkQVs

<h2>프로젝트 개요</h2>
 실내 놀이터는 이미 안전사고 관리 시스템이 잘 갖추어져 있는 반면 옥외놀이터는 안전관리 시스템이 잘 마련되어있지 않아 해마다 많은 사고가 일어납니다. 따라서 옥외놀이터를 선정하였으며 센서를 통해 놀이터의 상태를 모니터링하고 그 모니터링 결과를 이용하여 안전관리를 하는 통합 시스템을 개발하기로 하였습니다. 

<h2>프로젝트 목적</h2>
미끄럼틀을 거꾸로 오르는 등 사고를 일으키는 행동들이 유형화 되어있기 때문에 놀이기구 사용자들의 사용 패턴을 찾아 위험한 패턴이 감지되면 알람을 주는 것

<h2>프로젝트 폴더 설명</h2>
1학기 : 1학기 실험 내용 & 삽질<br>
IOT 기반 옥외놀이터 모니터링 및 안전관리 시스템 : 프로젝트 최종 결과물<br>
arduino : arduino 그네 코드, arduino 미끄럼틀 코드<br>
DB : 랜덤한 데이터 생성을 위한 코드<br>
IOTProcessing : Processing 서버 구축과 DB 접근 및 데이터 가공, 관리자 화면 및 웹페이지<br>
프로젝트 설명 : 중간발표자료, 최종발표자료, 최종보고서, 사업계획서, 최종포스터<br>

<h2>프로젝트 예상 구조도</h2>

<img width="560" alt="시스템구조도" src="https://user-images.githubusercontent.com/50941201/101448675-cd61fe00-396a-11eb-82ab-c2633d0dda5b.PNG">
각 놀이터에는 그네와 미끄럼틀에 esp8266 D1보드가 부착되어 있다. 그네는 IR트래킹 센서를 이용하였고 미끄럼틀은 조도 센서와 레이저 센서를 사용함. 수집한 정보는 공유기를 통해 관리자 화면으로 전달되고 데이터베이스에 저장된다. 

<h2>프로젝트 아키텍처</h2>

<img width="406" alt="미끄럼틀회로" src="https://user-images.githubusercontent.com/50941201/101448680-d05cee80-396a-11eb-8625-fa43f035a17a.PNG">
 미끄럼틀에 4개의 조도센서와 레이저센서, Esp8266 D1 R1보드 사용

<img width="450" alt="그네회로" src="https://user-images.githubusercontent.com/50941201/101448688-d2bf4880-396a-11eb-84a2-fb08a62a0ecf.PNG">
  그네에 IR트래킹센서, Esp8266 D1 R1보드 사용


## 구현 참고 자료
아두이노 :  https://wikidocs.net/book/2655, https://github.com/LennartHennigs/Button2.git 의 내용을 참고함<br>
 DB : https://wikidocs.net/book/1530 의 내용을 참고함<br>
 html : https://p5js.org/ko/ 의 내용을 참고함<br>

## 참여자
김소림 이효정 현재정
  
## 기술 블로그
* 김소림 https://blog.naver.com/ksr10217/222166393428 </p>
* 이효정 https://blog.naver.com/lhj97033/222146681749</p>
* 현재정 https://blog.naver.com/wowjd123589/222160705266</p>

## 수상실적
* 강서구청 - 강서구 스마트도시 아이디어 공모전 - 장려상
* 이화여자대학교 - SW창업경진대회 - 장려상
* 양천구청-양천구 스마트시티 아이디어 공모전 - 장려상
* 이화여자대학교 - 캡스톤디자인경진대회 - 장려상

##  License 표시
GNU(Gnu is Not Unix), General Public License(GPL)
