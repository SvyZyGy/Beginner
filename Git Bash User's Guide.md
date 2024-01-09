- 1) 사용자 등록  
git config --global user.name "[이름]" : name 등록  
git config --global user.email "[이메일주소]" : email 등록

- 2) Git 저장소 생성  
mkdir [폴더 이름] : 폴더 생성  
rmdir [폴더 이름] : 폴더 삭제  
cd [폴더 이름] : 폴더로 이동  
git init : main branch 생성 -> git bash 현재 폴더명에 branch 이름(main) 추가

- 3) stage에 올리기  
Git add -A  
: 현재 폴더의 파일들과 하위 폴더의 파일 모두를 저장할 대상으로 지정  
: 현재 디렉토리에 있는 파일을 index에 올림/스테이징 함/스테이지에 올림  
Git add [파일 이름] : 파일 하나하나를 지정

- 4) stage에 올라간 상태 확인  
git status : stage에 올라간 파일과 안 올라간 파일을 보여줌

- 5) commit 하기  
git commit -m "메세지" : 스테이지에 올라간 파일을 commit (stage에 파일이 올라가 있어야 함)  
git log : 현재 저장된 commit list를 보여줌

- 6) 로컬 저장소(git) -> 원격 저장소(git hub) push 하기  
git remote add origin [git 온라인 저장소 주소] : origin에 온라인(remote)저장소 주소를 등록(add)  
git push origin main : origin에 main branch를 업로드

- 7) 원격 저장소의 최신 file 현행화시키기  
git pull [git repository 이름] [branch 이름] : origin의 변경사항 현행화
