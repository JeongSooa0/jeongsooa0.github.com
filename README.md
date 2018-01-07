
<h1>01/07</h1>
오른쪽 하단 git branch master -> git develop


1. 깃 설치 후  
git 설치: https://git-scm.com/
설치 확인 cmd  (터미널):  git --version

2. git 에서 new repository 후
 cmd  (터미널): 
     git clone https://github.com/JeongSooa0/study-fd3-react-project

3. 파일생성 (오른쪽 마우스 -> git -> add 후 커밋)
   index.html
   .gitignore  .idea : 버전관리 할 대상이 아니다
   README.md

4. cmd 터미널 에서
    git config --global user.name sooa  
    git config --global user.email jsa85love@hanmail.net
    git config user.name 으로 확인

5. 아무파일에서 오른쪽마우스 git 레파짓토리 - pull  : 업데이트



https://github.com/wow9144/study-fd3-git



jsa85love.github.com 레파짓토리 생성 후 아래 주소에서 확인가능
http://jsa85love.github.io/




패키지.json 설치   :  npm init -y 
제스트 설치 :       npm install --save-dev jest 

npm test : "jest" 셋팅



master branch
check in
gitlab
pull
travice  가입해야함

Travis CI 배포 자동화 툴
https://travis-ci.org/
git - > setting -> Integrations & services   add service  travice ci

build history

travice.yaml 파일 생성
	language : node_js
	node_js : "8"

  - > push

jenkins 
