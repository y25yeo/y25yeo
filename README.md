### 🙋 안녕하세요. 안드로이드 개발자 여창민입니다.

<p>
  <a href="https://yeo2507.notion.site/PROFILE-ae856bd1898544a1b6beede0a9d6cc6f" target="_blank"><img src="https://img.shields.io/badge/Notion-292929?style=flat-square&logo=Notion&logoColor=white"></a> &nbsp
  <a href="https://yeolife.tistory.com/" target="_blank"><img src="https://img.shields.io/badge/Tech Blog-F45D48?style=flat-square&logo=tistory&logoColor=white"></a>
</p>

### 🐾 History
+ 삼성 청년 SW 아카데미 11기 모바일 트랙 (2024.01 - 2024.12) </br>
  + 우수상 <a href="https://play.google.com/store/apps/details?id=com.ssafy.frogdetox&hl=ko">LLM을 활용한 투두리스트 & 도파민 디톡스 앱</a>
+ 음악유사성 판별데이터를 활용한 아이디어 해커톤 (2022.11.15 - 2022.12.04) </br>
  + 우수상 <a href="https://www.etnews.com/20221220000072">감성 분석을 통한 멜로디 추천 서비스</a>
+ 삼성SDS 하계 대학생 알고리즘 특강 (2022.07 - 2022.07) </br>
  + SW역량테스트 Pro등급 취득
+ 정보처리기사 취득 (2022.06.17) </br>
+ 케이쉴드 주니어 7기 취약점 진단 트랙 (2021.08 - 2021.11) </br>

#

### 📗 Team Projects

<details>
  <summary> 사내 협업 관리 플랫폼 with <b>삼성SDI</b> (2024.10.14 ~ 2024.11.19) </summary>

 #### 개요  
<b>슈퍼보드</b>는 언제 어디서든 활발한 협업을 위한 프로젝트 관리 플랫폼이다. 칸반 보드 기반으로 한눈에 작업을 파악할 수 있으며, 실시간 협업 및 오프라인 동기화 기능을 제공하여 원격 환경에서도 최고의 협업 환경을 제공한다.

 #### 담당 역할
+ 안드로이드 개발
+ 오프라인 환경에서도 안정적으로 데이터를 관리하기 위한 Room DB 설계 및 구현<br>
+ 동기화 시 객체의 변경된 컬럼 구분을 위한 비트마스킹 구현<br>
  + 저장공간 효율 28.1% 상승 
+ 복잡한 비트마스킹을 KSP과 Annotation를 활용하여 함수로 추상화 <br>
  + 업데이트 연산 메모리 효율 42.8% 향상, 시간 31.9% 단축 (<a href="https://yeolife.tistory.com/107">상세보기</a>)
+ WorkFlow 드래그 앤 드롭에서 발생하는 순서 충돌 방지 알고리즘 구현<br>
  + 분수 인덱싱 알고리즘(숫자 값 간격을 넓게 해서 타겟에 사잇값 할당)
</details>

<details>
  <summary> 어린이 자연생태 학습 플랫폼 (2024.08.26 ~ 2024.10.11) </summary>

 #### 개요  
<b>이게 모야</b>는 아이들이 증강현실로 자연을 학습하는 플랫폼이다. AR NPC와의 상호작용을 통해 미션을 수행하며, 탐험 중 생긴 궁금증은 AI 챗봇에게 물어볼 수 있어 호기심을 바로 해결할 수 있다. 미션 수행을 통해 동기부여를 제공하고, 자연과의 소중한 교감을 형성해 어린이의 건강한 성장을 도울 것이다.

 #### 담당 역할
+ 안드로이드 개발
+ 백엔드 API 통신
+ Fused Location Provide 활용
  + 목적지에 AR 배치를 위한 거리 연산
  + 거리에 따른 GPS 우선순위 조정으로 배터리 효율 향상
+ 증강현실 상호작용
  + HitTest를 활용한 AR 배치 안정성 확보
+ Overlay 형식의 음성 챗봇 TTS, STT
</details>

<details>
  <summary> 온라인 요가 티칭 플랫폼 (2024.07.05 ~ 2024.08.16) </summary>

 #### 개요  
<b>요가나비</b>는 요가의 느린 동작과 작은 활동 반경이라는 특성을 살려, 요가를 온라인으로 배우는 플랫폼이다. P2P 방식의 화상 강의를 통해 미디어 트랙을 서버를 거치지 않고 사용자 간에 직접 주고받아 프라이버시를 보장한다. 또한 사용자는 녹화된 강의를 보고 따라 하면서 AI로 자세의 정확도를 실시간으로 확인할 수 있으며, 온디바이스 AI라서 화면이 서버로 전송되지 않으므로 사용자에게 개인화된 서비스를 제공한다.

 #### 담당 역할
+ 안드로이드 개발
+ 백엔드 API 통신
+ 강의 목록을 Pagination하여 효율적인 데이터 호출
+ FCM을 활용한 화상강의 푸시알람
+ WebRTC를 이용한 P2P 화상강의 구현
+ Ktor 기반의 WebSocket 시그널링 서버 구축
</details>

<details>
  <summary> LLM을 활용한 투두 리스트 & 도파민 디톡스 앱 (2024.04.18 ~ 2024.06.30) </summary>

 #### 개요  
<b>청깨구리</b>는 도파민에 중독되어 밤낮이 종종 바뀌는 현대인을 위한 투두리스트이다. 생성형AI를 활용해 최근 작성한 투두리스트를 기반하여 할 일을 추천한다. 또한, 잠을 잘 시간에는 게이미피케이션 요소를 적용해 자연스럽게 앱 사용을 제한하여 도파민 디톡스를 유도한다.

 #### 담당 역할
+ 안드로이드 개발
+ Realtime Firebase를 활용한 투두 CRUD 구현
+ OpenAI API를 활용한 투두 추천 LLM 프롬프팅
+ Alarm Manager를 이용한 투두 알람 구현
+ 구글 플레이스토어 배포
</details>

#

<br>

[![Solved.ac 프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=yeo2507)](https://solved.ac/yeo2507)

<br>

<!--
<h3 align="center"> ⚡ Tech Stack </h3> <br>
<p align="center">
  <img src="https://img.shields.io/badge/android-34A853?style=for-the-badge&logo=android&logoColor=white">&nbsp
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">&nbsp 
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white">&nbsp <br><br>
  <img src="https://img.shields.io/badge/kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white">&nbsp
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white">&nbsp 
  <img src="https://img.shields.io/badge/Java-1A285F?style=for-the-badge&logo=coffeescript&logoColor=white"/>&nbsp
</p>
<br/>

# 
-->
