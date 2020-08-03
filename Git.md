# Git 사용법
> 해당 페이지는 주로 사용하는 명령어를 메모한 페이지로 자세한 내용은 공식 홈페이지 참고 
   

## Git Setting 
- Linux 환경에서 사용
  - /etc/gitconfig : 모든 사용자와 모든 저장소에 적용되는 파일
    - git config --system
  - ~/.gitconfig, ~/.config/git/config : 특정 사용자에게만 적용 되는 설정 
    - git config --global
  - .git/config : 특정 저장소에서만 적용   

   

## Git Command 
    git init    # git 초기화. 쉽게 말해 해당 공간을 git으로 관리하겠다라고 선언하는 작업. .git 폴더가 생성 된다.
    git clone   # 저장소를 복사

    git status  # 작업 공간의 상태를 확인

    git add     # 파일을 추가. 해당 명령어를 통해 git으로 추적하겠다의 의미. (staged)

    git commit  # 저장소에 변경사항을 기록함. (최종)