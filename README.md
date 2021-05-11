# PRpractice

* pull request 연습용 레포

## Github 사용규칙 (필독!!)
---

File Name은 자유입니다! (단! 띄어쓰기, 특수문자, 한글 금지!!!) 예시) MobileNet_baseline
Commit message 역시나 자유입니다. 단, 실무에서 처럼 영어를 사용해보는게 좋을 듯 합니다. 예시) Add MobileNet_baseline
Issue를 쓸 때는 꼭 해당 게시글 링크를 함께 업로드해주세요.

## Git 사용법
---

- Fork해올 때 기본적으로 해줘야할 초기 세팅 절차
    - 자신의 git으로 fork해간다.
    - 폴더 하나 생성 후에, 해당 경로에서 터미널 열기를 한다.
    - git clone [https://github.com/SIAiffel/PRpractice](https://github.com/SIAiffel/PRpractice) # clone 하면 git init, git pull, git add remote 패쓰!
    - git remote -v # remote git 주소 확인
    - git remote add remote명 본인repo의 git주소 # fork해온 repo의 git주소에 대한 remote도 생성한다. remote명은 기본이 origin이므로 다른 걸로 아무거나 지어준다. (upstream 추천)
- Fork해온 repo에 pull request하는 법(= 새로운 파일 contribute하기)
    - **git pull origin master** # 항상 맨처음에 pull을 해줘서 최신 상태로 업데이트를 해줘야 충돌에러X
    - **git add 해당파일명** # 파일명(File Name) 규칙 확인
    - **git commit -m "자신만의 커밋 메세지"** # Commit message 규칙 확인
    - **git push 새로추가한remote명 브랜치명** # 본인 repo 기준으로한 브랜치명, remote명
    - 본인 Github에 fork해온 repo로 가서 상단의 초록색 compare&pull request 버튼 클릭
    - slack에 pull request 수행했음을 채널에 말해준다.
- 참고링크: [https://yorr.tistory.com/11](https://yorr.tistory.com/11)



