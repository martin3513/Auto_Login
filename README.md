# Auto_Login


로컬 저장소에서 Github로 push를 하는 상황에 다음과 같은 에러가 발생할 때가 있다.

우선 로컬의 현재 default 브랜치 명을 보면 master이고, 깃헙의 default 브랜치 명은 main으로 되어있다. 

이는 Git 2.28버젼 이후부터 default branch명을 master-> main으로 바꾸었기 때문에 별도의 세팅을 하지 않는다면

위와 같이 되어있을 가능성이 크다.

​

따라서, git bash(혹은 사용하는 CLI)의 default 브랜치 명을 main으로 바꿔주거나, 

깃헙 레포지토리를 생성할때 default 브랜치 명을 master로 바꿔주면 된다. 

물론 branch 명을 맞추기만 하고 push가 되지는 않았으나 이 작업도 필요함을 확인했기에 

우선적으로 branch명을 맞춰주자.

​

우선 git bash의 default 브랜치 명을 바꾸는 방법을 알아보자.

1) git config --global init.defaultBranch main  명령어를 입력

2) cat ~/.gitconfig 명령어로 바뀌어있는 것을 확인


