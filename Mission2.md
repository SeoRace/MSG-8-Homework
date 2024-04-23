# MSG-8-Homework

**기본용어**
- 작업 디렉토리: 코딩하는 공간
- 스테이징 영역: 임시 저장 공간
- 로컬 저장소: 실제 저장 공간
- 원격 저장소: 내가 저장한 변경내역을 다른 사람과 공유할 수 있는 원격 공간


## Git 명령어
변경사항 확인
 Git 명령어
1) 변경사항 확인

`git status`
2) 변경사항 스테이지에 올리기

`git add (파일명)`
`git add .					//변경된 모든 파일 add`		
3) 커밋(commit)하기

`git commit -m "add README"`
4) 커밋 로그 확인하기

`git log		`	
5) 수정내용 확인하기

`git diff	`						
6) 방금 커밋한 메세지 수정하기

`git commit --amend`

7) 푸쉬(push) 하기

`git push -u origin main`