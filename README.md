# coursegraph-js

https://github.com/RakeshC7/HTML5-Boilerplate 로부터 기본 틀을 가져왔습니다.
처음에 빈 디렉토리로 시작하면 디렉토리 구조 잡거나 하는 것부터가 한세월 걸릴 거 같아 최소한의 HTML/CSS/JS 파일이 포함된 내용은 사실상 거의 없는 가장 간단한 걸로 나름 찾아서 가져온겁니다.

## GitHub와 VSCode 연동하여 coursegraph-js 실행하는 방법
VSCode를 설치합니다.

VSCode를 실행하여 F1키를 누릅니다.

git clone을 입력합니다.

Git: Clone 메뉴를 선택합니다.(만약, git clone 입력해도 No matching commands 글자가 뜨면 깃허브를 설치한 후 다시 두번째 순서부터 진행합니다)

GitHub의 repository 주소를 복사하여 붙여넣기(입력)합니다.

파일 창이 뜨면 clone 시킬 폴더(위치 설정)를 선택합니다.

Would you like to open the cloned repository 문구가 뜨면 open을 클릭합니다.

파이썬이 설치되어 있다면 터미널을 열어서 아래의 파이썬에서 웹서버를 띄우는 방법을 참고하고, 
Live server를 이용하려 한다면 아래의 Live server 사용법을 참고합니다. 


## Live Server 사용법

![방법1](https://github.com/SiRyung/forgitimage/blob/main/coursegraph_js/1.PNG)<br><br>
vscode 좌측 확장에서 Live Server를 검색합니다.

---
![방법2](https://github.com/SiRyung/forgitimage/blob/main/coursegraph_js/2.PNG)<br><br>
사진과 같이 Live Server과 표시되면 설치버튼을 눌러줍니다.

---
![방법3](https://github.com/SiRyung/forgitimage/blob/main/coursegraph_js/3.PNG)<br><br>
생략해도 됩니다. (오류 발생시 방법 권장)
Live Server 관리 버튼을 눌러줍니다.

---
![방법4](https://github.com/SiRyung/forgitimage/blob/main/coursegraph_js/4.PNG)<br><br>
하단으로 스크롤 하여 Live Server > Settings: Use Local IP에 해당하는 부분인
Use local IP as host를 활성화 시켜줍니다.

---
![방법6](https://github.com/oss2024hnu/coursegraph-js/assets/162093749/1e7ed3ba-593b-48a9-8a5f-c00ef964902b)<br><br> 
그림과 같이 우측 하단에 Go Live를 눌러서 실행 하면 라이브 서버를 활성화시킬 수 있습니다.

---
![방법7]!(https://github.com/ohnakyu/coursegraph-js/assets/162093749/b2d2a74f-8b91-479a-935b-e959daad3b2e)<br><br>
그림과 같이 vs code의 우측 하단에 Port:5500을 클릭하면 라이브 서버를 종료시킬 수 있습니다.


# 파이썬에서 웹서버를 띄우는 방법
https://docs.python.org/3/library/http.server.html 를 참고하여 만들었습니다.

## 기본 명령어
http.server(Python 내장 라이브러리 사용)
아래 CLI 커맨드 한 줄이면 현재 디렉터리의 파일을 서빙하는 HTTP 웹 서버를 띄울 수 있습니다.
```
python -m http.server
```
이후 이후 웹 브라우저에서 http://localhost:8000 주소로 접속하면 파일 목록이 보이거나 혹은 HTML 파일을 볼 수 있습니다.

## 추가 옵션
```
python -m http.server 3000 --bind 127.0.0.1
```
위 코드를 예를 들어 포트를 3000으로 바꿀수 있으며 바인딩 주소 또한 바꿀수 있습니다.

현재 디렉토리가 아닌 다른 디렉토리를 루트로 하고싶다면 `--directory`를 사용하여 바꿀수있습니다.
