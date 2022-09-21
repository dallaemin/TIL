# TIL

## 2022-09-21

### 리눅스 커맨드라인 기초

1. pwd
- print working directory

2. cd 
- change directory

3. ls
- list
    - ls 뒤에는 -a나 -l 옵션을 붙일 수 있음

4. git ignore
- 커밋에 포함하고 싶지 않은 파일들을 관리



### vim 사용법
> window에서 git bash를 설치할 때, default editor로 vim을 선택했기 때문에 git을 사용하려면 반드시 vim을 사용할 줄 알아야 함

#### 명령모드 vs. 입력모드

1. vim 에디터를 처음 킬때는 명령모드로 진입. 이때는 입력이 불가능함
2. 입력 하려면 입력 모드로 바꿔야함
  - 입력 모드로 바꾸려면 키보드에서 `i`키(insert)등을 누름
3. 입력이 다 끝나고 저장 등의 명령을 컴퓨터에게 내리려면 명령모드로 다시 돌아가야 함
  - 명령모드로 바꾸려면 키보드에서 `esc`키를 누름
  - 명령모드에서 `:w`를 입력하고 `enter`키를 누르면 저장만 됨(write)
  - `:wq`를 입력하면 저장하고 에디터에서 빠져나올 수 있음(write and quit)
  - `:q`를 입력하면 에디터에서 빠져나올 수 있음(quit)