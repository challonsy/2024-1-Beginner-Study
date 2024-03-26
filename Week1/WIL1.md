### Git이란?

버전 관리 및 협업을 위한 오픈소스 소프트웨어

누가, 언제, 어떻게, 무엇을 수정했는지 알 수 있게 해준다.



## Git 파일의 생명 주기

**git add**: 깃의 관리를 받을 수 있도록 스테이징 상태로 만든다.

처음 add를 하기 전에는 변경 사항이 생겨도 변동사항이 생겼는지 알 수 없는 Untracked 상태이고,

add를 하고나면 tracking 상태가 된다. tracking 상태를 3가지 상태로 더 자세히 나눌 수 있는데, modified, unmodified, staged 상태이다.

modified 상태에서 add를 하면 staged 상태가 되고, commit을 할 수 있게 된다.


## Git 명령어

git init: git 의 관리를 받는 폴더로 만들어준다 (.git 생성)

git status: 새로 수정된 파일이 있는지, untracked 파일이 있는지 등을 확인할 수 있음

git push origin [브랜치이름]: 원격 저장소의 브랜치로 푸쉬한다


https://github.com/challonsy/challonsy
