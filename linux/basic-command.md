# 리눅스 기본 명령어

## 0. 리눅스 명렁어의 기본 형식
```
command [options] [arguments]
```
- 여기서 command 다음에 띄어쓰기 꼭 필요함
- command -> 실행할 명령어나 프로그램
- options -> 명령어의 옵션 / 주로 앞에 - 들어감
- arguments -> 명령어에 전달할 인자 / 활용할 때 써야 하는 데이터

# 1. 파일 및 디렉토리 관리

### ls (list)
- 디렉토리 내용 목록을 보여줌
- options
    - `-l`: 파일의 상세 정보 표시
    - `-a`: 숨김 파일 표시

- . 현재 폴더 의미함
- .. 상위 폴더 의미함


### cd (change directory)
- 현재 작업 디렉토리를 변경
- cd 다음에 내가 이동하고 싶은 경로 작성
- `cd {target-directory}`
    - target-directory는 자동완성 기능을 활용할 수 있음
    - TAB: 자동완성 기능


### pwd (print working directory)
- 현재 작업 중인 디렉토리의 전체 경로를 출력

### mkdir (make directory)
- 새로운 디렉토리를 생성
- `mkdir {directory-name}`

### touch
- 새로운 파일을 생성
- `touch {file-name}`

### rm (remove)
- 파일이나 폴더를 삭제
- 파일을 지울 수 있지만 폴더는 지울 수 없음
- rm은 하나만 지우는 게 기본 옵션임
- 폴더를 지우고 싶을 땐 옵션을 넣어줘야 함
- options
    - `-r`: 디렉토리와 그 내용을 재귀적으로 삭제(recursion의 약자)
    - `rm -r markup`

### cat (concatenate)
- 파일의 내용을 출력
- `cat README.md`
