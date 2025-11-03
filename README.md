# newtonapple_README


<img width="563" height="289" alt="Image" src="https://github.com/user-attachments/assets/4887030f-3640-4759-8506-62bca92c232b" />

팀 뉴턴사과의 주제는 AI 방제였다. 
어떤 농작물을 방제할 것인지에 대해서는 팀장님이 사과농장 홈페이지를 개발해본 적이 있고 직접 답사도 다녀온 경험도 있기 때문에 목본식물인 사과를 선택하게 되었다. 

<img width="563" height="276" alt="Image" src="https://github.com/user-attachments/assets/dcb98fe8-4dd3-43b6-b80c-e49f22a18b99" />
필요성은 이와 같다. 
나날이 값이 올라가는 사과.. 저렴하게 먹으려면 어떻게 해야 할까?
그 전에 왜 값이 점점 오르는지에 대해서 조사해봤다. 
고령화, 기후변화 이 두가지가 가장 큰 이유로 추려졌다. 
즉, 우리는 농업 환경의 변화에 따른 기술적 필요성을 찾을 수 있다.

<img width="567" height="270" alt="Image" src="https://github.com/user-attachments/assets/28c0f304-7971-464c-a539-eba0435ace3f" />

뉴턴사과의 젯봇 모델은 기존의 로봇 청소기처럼 경로를 따라가고 스마트 팜의 요소가 더해졌다.

<img width="606" height="271" alt="Image" src="https://github.com/user-attachments/assets/601dab3a-4459-4d1b-b583-0f9142acbe2e" />

분석은 이와 같다. 단순 농사에서 끝나는 것이 아닌 정치, 경제, 사회, 기술 이 네가지 측면과 관련이 있다. 

<img width="537" height="269" alt="Image" src="https://github.com/user-attachments/assets/d9b9cc37-571f-4bb7-8935-2efbef13dd96" />

AI 웹 사이트로 그려본 예상 모델이다. 

<img width="538" height="269" alt="Image" src="https://github.com/user-attachments/assets/c37266f1-d3b7-4948-9b5a-4d3793312c0c" />

챌린지 포인트는 
회원가입을 하고 로그인을 하면 젯봇으로 방제한 기록과 또 욜로를 이용해 객체탐지를 해 사과를 구분할 수 있다. 그 외 등등의 병해충 정보 제공을 하고 커뮤니티를 할 수 있다.


<img width="559" height="294" alt="Image" src="https://github.com/user-attachments/assets/a3db32ff-e8e4-41d9-afb1-468e55ca47ae" />

서비스 흐름도이다. 

<img width="590" height="243" alt="Image" src="https://github.com/user-attachments/assets/89bea3ee-3c21-436c-9392-b0684b70c833" />

ER DIAGRAM 이다. 
웹사이트 테이블명세서를 기반으로 만들었다. 


<img width="568" height="281" alt="Image" src="https://github.com/user-attachments/assets/bd829084-c23a-4c29-bb82-9976321f6d8f" />
사용언어와 도구이다. 
젯봇, 파이썬, MySQL 
프론트 엔드는 HTML, CSS, JS
백엔드는 노드Js를 이용했다. 
그 외에 야붐로봇을 잠깐 사용했었다.

<img width="566" height="281" alt="Image" src="https://github.com/user-attachments/assets/46cb6f61-4f6e-4162-8dbe-310b1cb0a4fa" />

개발내용은 사과 객체를 탐지하면 앞으로 주행하고 사과가 보이지 않으면 정지한다. 
수동으로 사용자가 직접 전진과 정지를 할 수있고 
서버에 방제 기록이 기록된다. 


<img width="564" height="240" alt="Image" src="https://github.com/user-attachments/assets/da5a3b0f-9efc-461f-bb3a-eb0022088639" />

시스템 아키텍처이다. 

주요기능은 젯봇과 웹서버 두가지로 나눠정리했다.
먼저 젯봇이다. 

<img width="557" height="254" alt="Image" src="https://github.com/user-attachments/assets/e24ddfac-2237-47d9-a6b7-56f731b8b87e" />
크게 객체 탐지 서버, 동작서버, 방제 모듈을 활용했다. 


다음은 웹서버이다. 

<img width="564" height="278" alt="Image" src="https://github.com/user-attachments/assets/591f3200-bbb6-4b4b-8066-c5e1600e6638" />
회원가입/ 로그인, 메인 화면, 방제기록 등록, 게시판(댓글)으로 구성되어 있다. 

<img width="551" height="280" alt="Image" src="https://github.com/user-attachments/assets/fb4dbfa2-cf63-4a6a-bfab-2758be3f9e86" />

사과AI 방제 젯봇의 기대효과와 활용방안이다. 


<img width="512" height="493" alt="Image" src="https://github.com/user-attachments/assets/33f25425-d294-4230-aa0e-7776e95116a1" />


팀원 소개와 맡은 역할이다. 개발후기까지 적어보았다.
