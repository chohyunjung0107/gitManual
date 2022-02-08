# gitManual


## merge
```
git merge 
- HEAD가 master의 코드이고 ===== 밑에 코드가 내 코드 

```
## push하기 
```
**1) 저장 범위 **
-전체 저장
git add *

-파일 저장 
git add 파일명.tsx 

-수정 내용만 
git add -u

-stage 리셋 
git reset

**2)커밋하기** 
git commit -m '커밋 메세지'

**3)원격에 올리기** 
git push

** 4) 현재 브랜치의 헤더 커밋까지의 변경 사항을 origin이라는 이름을 갖는 원격 저장소의 마스터 브랜치에 전송
git push origin HEAD:master 

-origin: 원격 저장소 별칭(별도 설정이 없었다면 클론 명령으로 원격 저장소를 받아올 때 입력했던 주소이다.)
-HEAD:전송할 최종 커밋 
-master: 원격 저장소 브랜치의 이름 


```

## barnch 생성/삭제/현위치/브랜치이동
```
1. 브랜치 생성하기
(원결/로컬)git push origin 생성할명
(로컬)git branch 생성할명
- local의 branch를 retmoe branch와 연동하는 작업을 수행
git branch --set-upstream-to origin/생성한브랜치


2. 브랜치 삭제하기
(원격)
git push origin --delete 삭제할명 

(로컬)
git branch -d 삭제할명 

3. 브랜치 현위치 
git brnach 

4.브랜치 이동 
git switch 이동할브랜치명
```




