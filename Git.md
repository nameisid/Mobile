# Git 

## git

[Step01] git 설치 [git Install Reference](https://git-scm.com)

[Step02] git 설정
```
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```
[Step03] github [github 회원가입](https://github.com)

## git 명령어
1. git 초기화 
    - git을 사용하겠습니다.
    ```
        git init
    ```
2. 관리하고 싶은 파일이 존재!!
    - 내가 그 파일을 추적(Tracking)하고 싶다!
    ```
        git add [filename]
    ```
3. git의 상태 확인
    ```
        git status
    ```
4. 변경사항 적용
    ```
    git commit -m "Message"
    ```
5. Message 확인
    ```
    git log
    ```