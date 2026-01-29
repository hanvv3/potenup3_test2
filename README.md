# potenup3_test2
test repo

git config --global user.name "steadywing"
git config --global user.email "steadywing01@gmail.com"

git config user.name - 지금 user.name이 뭐니?
git config user.email - 지금 user.email이 뭐니?

git status : 현재 변경사항 조회
git add test.py : test.py 파일을 스테이징영역으로 보낼게
git status : 현재 변경사항 조회
git commit -m "첫번째 커밋이에요" : 내 활동 메시지 입력
git status
git push origin main : 원격저장소로 보내기

# 시나리오 1
## 원격저장소에서 최신 코드를 반영한다.
## 새로운 기능을 만들기 위해 2개의 파일을 만들어서 개발한다. 
1) new_feature.py 만들어서 print("개발1") 작성하기
2) new_feature_add.py 만들어서 print("개발1-1") 작성하기
## 새롭게 생성한 2개의 파일을 스테이징영역으로 보낸다.
## 2개의 파일이 담겨있는 스테이징 영역을 커밋한다.
    "커밋 메세지: 새로운 기능 생성"
## README.md에 설명을 추가한다.
## README.md를 add한다.
## 수정했다고 커밋한다.
## 원격 저장소로 푸시한다.