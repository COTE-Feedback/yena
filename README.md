### 1. 레퍼지토리 생성

public, add README, Add .gitignore python 체크


### 2. 클론, 브랜치 생성 후 업로드

    git clone [깃허브 주소]
    cd [클론한 폴더명]
    git checkout -b week1
    git branch --set-upstream-to origin/main
    git add .
    git commit -m "커밋 메세지"
    git push origin week1

### 3. 리뷰 요청

Pull requests > 리뷰 원하는 브랜치의 Compare & pull request > Reviewrs 모두 선택


### 4. 리뷰 받은 후 main 브랜치에 합치기

    git checkout main
    git merge week1
    git push
