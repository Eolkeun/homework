# ✨ 카냐(CA NYA) ✨

사진

### ✏서비스 소개✏
좋은 카페를 찾고 싶고, 좋은 카페를 공유하고 싶으신가요?

카페에 대한 리뷰만을 확인하고 싶고, 상세한 평가가 궁금하신가요?

그렇다면, 카냐(CA NYA)에서 다녀온 카페 정보를 공유하고, 원하는 카페 리뷰를 검색해보아요!

마음에 드는 리뷰가 있다면 좋아요 기능을 통해 마이페이지에서 한눈에 확인해요.

카페리뷰 외에도 커뮤니티를 통해 카페를 좋아하는 유저간에 자유로운 소통을 할수있어요! 💛

### 웹사이트 [카냐 바로가기](https://ca-nya.com/)
### 팀 노션 [카냐 팀노션 바로가기](https://www.notion.so/99-4-dcbf8104c68b4d3a940968c05371e21a)

---

### 프로젝트 기간
기간 : 2022년 11월 03일 ~ 2022년 12월 16일

### 팀원 소개
|이름|github|position|
|------|---|---|
|박성민|https://github.com/Adam-SungMin-Park|팀장BE|
|서지영|https://github.com/jiyeong-seo|부팀장FE|
|임소희|https://github.com/Limsoheeee|BE|
|장지윤|https://github.com/Jaylin16|BE|
|김병기|https://github.com/Eolkeun|BE|
|김정윤||UX/UI|

---

### 서비스 아키텍쳐
사진

---

### API
사진

---

### 와이어 프레임
### [와이어 프레임 바로가기](링크)

---

### ERD
사진

---

### 기술 스택

### 툴

### 서버

---

### 주요기능

---

### 트러블 슈팅

 <details>
 <summary>데이터 새로고침 이슈</summary>
 <div markdown="1">       

 ```
 리렌더링 이슈 발생하여 수정 완료.
 특정 데이터 수정시 새고고침해야 수정 가능했으나 현재는 수정 완료.

 ```
 
 </div>
 </details>
 
 <details>
  <summary>채팅 (SockJS, Stomp)</summary>
 <div markdown="1">       

 ```
 백엔드에서 Stomp와 SockJS 둘 다 사용가능하도록 구현해둔 상황에서 프론트와 서버 통신하는 과정 중 localhost를 *로 푸는 대신 특정 포트를 지정해서 풀어줌으로써 수정 완료.

 ```
 
 </div>
 </details>
 
  <details>
  <summary>순환 참조 issue</summary>
 <div markdown="1">       

 ```
 로그인시 멤버와 엮여있는 코멘트 부분이 순환참조되어 따라왔었습니다.
 이를 memberDto에 담음으로써 순환참조를 끊어줘서 해결했습니다.

 ```
 
 </div>
 </details>
