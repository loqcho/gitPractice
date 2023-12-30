# gitPractice

github guide의 명령어들을 순차적으로 실행해보며, 각 명령어가 어떤 일을 하고 있는지 알아보기.

# Commmand Line

```
echo # gitPractice >> README.md
git init 
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/loqcho/gitPractice.git
git push -u origin main
```

1. 새로운 텍스트 파일인 "README.md"를 생성하고 파일에 "# gitPractice"라는 내용 추가
2. 현재 디렉터리를 git 저장소로 초기화
3. "README.md" 파일을 stage에 add하기
4. Local Repository에 "first commit"이라는 메시지 commit하기
5. git 저장소의 브랜치 이름을 "main"으로 변경하기
6. 로컬과  원격 저장소 연결하기
7. 원격 저장소 메인에 작업한 파일 push하기
