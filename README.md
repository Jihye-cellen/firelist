## 배경

Firebase의 실시간 데이터베이스, 인증 기능 등을 직접 경험하고 활용하여 서버 없이 개발할 수 있는 백엔드 개발에 대한 이해도를 높이고 싶었습니다.

## 프로젝트 요약 설명

Kakao API를 복습하고 Firebase의 기능 이해도를 높이기 위해 장바구니, 즐겨찾기, 게시판, 채팅 기능을 제작했습니다.
![033](https://github.com/user-attachments/assets/a0fb4ce6-f9e7-45d4-b3c2-a5b81d0156c8)
![034](https://github.com/user-attachments/assets/2ec7cf35-5524-46b2-844e-485d700e3dff)
![035](https://github.com/user-attachments/assets/5f1700f9-d060-4e03-ad0a-b8bc97a071a8)
![036](https://github.com/user-attachments/assets/68cb2075-2ec0-4815-8d97-70e4769947d9)
![037](https://github.com/user-attachments/assets/bae020e6-c1ea-4855-ac85-1d788a6ec17e)
![038](https://github.com/user-attachments/assets/18a24cc2-dba4-4e53-873d-1abd8d5a7dcc)



### 목표

Firebase의 기능 살피고, 어떻게 접근하는 지 알기

React/Kakao에 대한 이해도 높이기

### 주요 제공 서비스

- 도서검색, 지역검색
- 즐겨찾기, 장바구니
- 게시판
- 공용채팅

## 기술스택

**Frontend:** React,  Javascript, CSS

**Backend:** Firebase

**Database:** Firebase

**API:** KakaoAPI

**Tool:** Visual Studio Code

## 역할 및 기능

- 로그인/회원가입
- 마이페이지 사진 업로드
- 도서검색(KakaoAPI 책 검색 API이용)
- 지역검색(KakaoAPI 지도 API이용)
- 게시판(댓글포함)
- 즐겨찾기/장바구니 기능
- 공용채팅

## 어려웠던 점/해결방안

| 어려웠던 점  | 해결방안 |
| --- | --- |
| 사진 업로드 시, Realtime Database에서 Storage로 변경 | Realtime Database를 계속해서 사용하다보니, 사진도 같이 저장하게 되었다가 이미지 크기 및 비용문제로 인해 Storage로 변경 |
| Realtime Database 채팅 ID별 위치 선정(CSS) | 카카오톡 CSS를 토대로 배경 및 레이아웃을 구성했는데, 이 레이아웃이 채팅을 입력하는 자와 다른 사용자가 보낸 채팅을 구분해야 하는 작업을 어렵게 생각함. 삼항연산자를 이용해서 인증한 이메일을 비교하여 CSS의 클래스를 이용해 위치를 다르게 구분. |

## 회고

- 파이어베이스와 React에 대한 이해도가 높아지면서 다양한 기능을 활용하여 개발 효율성을 높일 수 있었습니다.
- 파이어베이스와 React를 깊이 있게 학습하면서 개발의 재미를 더욱 느끼게 되었고, 다양한 기능을 조합하여 창의적인 프로젝트를 구현할 수 있다는 자신감이 생겼습니다.
