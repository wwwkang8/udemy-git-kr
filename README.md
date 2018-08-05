# udemy-git-kr
Git tutorial course
Update git command and practice

0) $ git merge
-Merge는 항상 잘 될까요?
 1. 잘 되는 경우 : 중복되는 위치를 변경하지 않은 경우
 2. 안되는 경우 : 같은 파일의 같은 부분의 내용이 변경되는 경우. --> 두 개의 소스를 병합할 수가 없다. 개발자가 
 직접 어느 부분을 남길지 결정해야한다.
 
 충돌이 발생하면?
 충돌이 발생한 경우 자동으로 병합할 수 없다는 메시지가 출력된다.
 
 충돌 발생시
 - <<<<<<Head :  현재 브랜치에 포함된 내용
 - >>>>>[브랜치명] : 다른 브랜치에 포함된 내용
 
 0) $git diff

1) 마크다운 문법 : HTML 형식의 문서를 쉽게 작성하기 위한 문법이다

2) $git remote add [alias][url] : 로컬 리포지토리와 원격 리포지토리를 연결하는 명령어.
로컬 리포지토리에 원격 리포지토리의 url 정보를 등록하는 것이다.
alias는 원격 리포지토리의 별칭을 만들어 주는 것.

$git remote -v : 원격저장소의 정보를 보여준다.

3) $git fetch [alias][branch] : 원격 저장소에 있는 내용을 로컬로 받는 명령. BUT!! fetch를 써도
Working directory에는 변화가 없다.
ex) $git fetch origin

4)  $git pull [alias][branch] : 원격 저장소에 있는 내용을 로컬로 받고 자동으로 working directory에
반영이 된다. fetch도 로컬로 받지만 working directory에는 반영하지 않는다.

5) $git push [alias][branch] : 로컬 저장소의 내용을 원격저장소로 업로드하는 것을 PUSH라고 한다.
ex) $ git push -u origin master : origin이라는 별칭을 가진 원격저장소에 master 브랜치에 푸쉬를 한다.

6) $git clone [url] : 공개된 원격 저장소를 다운로드 하는 명령. 권한이 없어도 다른 소스 저장소를 다운로드
하여 내 로컬에 저장할 수 있다.

7) pull Request : 오픈 소스에서 기능 개선 또는 버그가 있는 경우 직접 수정하고 원작자에게 반영 요청을 하는 기능.

* 내가 사용하는 오픈 소스에 버그가 있는 경우
* 신규 기능을 추가하고 싶은 경우
  
  - Pull Request의 단계
   1. Fork : 원작자의 저장소를 복제
   2. Clone : 원격저장소를 로컬 저장소로 다운로드
   3. Branch : Master 브랜치에서 Develop 또는 다른 작업을 할 브랜치를 생성
   4. Checkout : 작업할 브랜치로 변경
   5. Source Change : 수정이 필요한 부분의 소스를 변경
   6. Commit : 변경한 소스를 로컬 저장소에 저장
   7. Push : 로컬 저장소의 작업 브랜치를 원격 저장소로 업로드
   8. Pull Request : 변경사항을 원작자에게 원본 소스에 반영 요청 송신




