### Git이란?

버전 관리 및 협업을 위한 오픈소스 소프트웨어

누가, 언제, 어떻게, 무엇을 수정했는지 알 수 있게 해준다.




**git add**: 깃의 관리를 받을 수 있도록 스테이징 상태로 만든다.

처음 add를 하기 전에는 변경 사항이 생겨도 변동사항이 생겼는지 알 수 없는 Untracked 상태이고,

add를 하고나면 tracking 상태가 된다. tracking 상태를 3가지 상태로 더 자세히 나눌 수 있는데, modified, unmodified, staged 상태이다.

modified 상태에서 add를 하면 staged 상태가 되고, commit을 할 수 있게 된다.