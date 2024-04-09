### Merge의 세가지 옵션

**Merge Commit**

다른 브랜치에서 커밋한 변경 내역이 그대로 유지된 채 합병

**Squash Merge**

다른 브랜치에서의 커밋 내역이 하나로 압축된다. 그래서 한번의 커밋으로 브랜치 합병까지 됨

**Rebase and Merge**

다른 브랜치에서 일어난 커밋의 base를 재설정함.

### 커밋 수정

**amend, reset, revert**

**--amend**

마지막 커밋을 수정할 때 사용. 완전히 새로운 커밋으로 바뀌기 때문에 커밋 아이디가 바뀐다.

git commit --amend -m "기존 커밋 메시지 수정할 내용": 커밋 메시지 수정과 함께 커밋 변경

git commit --amned --no-edit: 메시지 수정 없이 커밋 변경

**reset**

reset의 세가지 옵션:

1. soft: 로컬 리포에서 커밋만 취소-> staging area에 있음

2. mixed: 로컬 리포에서 커밋과 add 취소-> working directory 에 있기 때문에 add를 다시 해줘야함

3. hard: working directory에도 변경 사항이 남지 않고 아예 작업한 내용이 사라진다.

사용법: reset --option <돌아갈 commit id>

**revert**

reset은 되돌린 이후 그 전 히스토리를 삭제하지만 revert는 히스토리를 모두 가지고 있다.

되돌리기 위한 새로운 commit 생성
