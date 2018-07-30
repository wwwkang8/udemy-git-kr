# udemy-git-kr
Git tutorial course
Update git command and practice

1) 마크다운 문법 : HTML 형식의 문서를 쉽게 작성하기 위한 문법이다
ex) #Text  --> "<h1>Text</h1>"

2) $git remote add [alias][url] : 로컬 리포지토리와 원격 리포지토리를 연결하는 명령어.
로컬 리포지토리에 원격 리포지토리의 url 정보를 등록하는 것이다.
alias는 원격 리포지토리의 별칭을 만들어 주는 것.

$git remote -v : 원격저장소의 정보를 보여준다.

3) $git fetch [alias][branch] : 원격 저장소에 있는 내용을 로컬로 받는 명령. BUT!! fetch를 써도
Working directory에는 변화가 없다.
ex) $git fetch origin

4)  $git pull [alias][branch] : 원격 저장소에 있는 내용을 로컬로 받고 자동으로 working directory에
반영이 된다. fetch도 로컬로 받지만 working directory에는 반영하지 않는다.

5) $git push [alias][branch] : 로컬 저장소의 내용을 원격저장소로 업로드


