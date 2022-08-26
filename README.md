# Get Bible<br>
### 개요<br>
nocr.net의 성경 페이지를 일괄적으로 txt파일로 다운로드 할 수 있는 프로그램이다.
Node.js와 puppeteer를 기반으로, 비동기를 통해 페이지 개수만큼 퍼펫티어 driver+page를 생성하여 동시 다운로드가 가능하게 했다.
(보통 19페이지까지 있으므로, 이 경우 19개 다운로드 동시진행)
<br>
<br>
### 사용언어<br>
Node.js 16.15.1<br>
Puppeteer 15.3.0<br>
<br>
### 사용법<br>
1. npm start로 실행한다.
![image](https://user-images.githubusercontent.com/52809844/186789248-82cd7f55-7ae4-4d35-9608-bf870041a492.png)

2. 원하는 성경을 선택한다.

3. 성경 다운로드를 개시한다. (저장 위치는 해당 프로젝트 내 '성경' 폴더이다.)
![image](https://user-images.githubusercontent.com/52809844/186789344-a16ac1cd-a258-41ae-977c-4ba8db482fd1.png)
![image](https://user-images.githubusercontent.com/52809844/186789419-f4d75729-8697-484a-acc3-7743ce886ed8.png)
