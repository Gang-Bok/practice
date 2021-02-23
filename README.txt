1. 로컬저장소 생성하기
git init

2. commit 만들기
ex) git add README.txt / git commit -m "설명"

2.1) commit log 확인
git log
2.2) 그곳으로 이동하기
git checkout 앞에7글자

3. commit 올리기

3.0) 새로운 repository 만들기
-> 깃허브에서 알아서 해

3.1) 로컬저장소에 원격저장소 주소 알려주기 
git remote add "원격저장소 주소" 

3.2) 올리기
git push origin master

4. 원격저장소 커밋을 로컬에 내려받기 (clone)
git clone 원격저장소 주소 .  -> 끝에 하나 띄어쓰기 후 . 넣어야해!

4.1) 원격저장소의 새로운 커밋을 로컬저장소에 갱신
git pull origin master 