# joongbuGitStudy
git 수업입니다.

git remote 저장소 생성 및 clone
git clone 저장소 url

git 로컬 저장소와 리모트 저장소의 차이
    origin/main => 저장소 이름/가지
    origin/HEAD => 리모트 저장소에 등록된 최신 이력
    HEAD -> main => 로컬 저장소의 최신 이력

리모트 저장소에 로컬 저장소의 이력을 올리는 행위
git push origin main (가지 단위로 (history 전체)이력을 올린다.)

(HEAD -> main, origin/main, origin/HEAD)
로컬 저장소와 리모크 저장소의 이력차이가 없음(최신이력)

git push 리모트저장소 가지
    해당 리모트 저장소 생성자와 로컬저장송 작업자가 동일해야  push할 수 있다.(브라우저 로그인 인증)
    해당 리모트 저장소의 팀원으로 등록되면 push할 수 있다.