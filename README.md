## Assignment 2 

Assignment 1 결과물에서 remote 를 제거하고 시작한다.

```json
git remote rm origin
```

test 브랜치에서 third 부터 sixth 까지 커밋 히스토리를 interactive 모드로 접근해야 하므로 

```json
# 두 번째 커밋 해시까지
git rebase -i 1c106b52
```

![image](https://user-images.githubusercontent.com/68385605/136381518-9b66dbb8-e5d5-46cc-8f88-d00abe9a6992.png)

third 커밋에 합치기 위해 fourth, fifth, sixth 에 fixup 을 지정한다. 

![image](https://user-images.githubusercontent.com/68385605/136381664-d33893c8-7b1f-487c-8e8d-f0dc2b5ca025.png)

다음 내용을 저장한다. 

![image](https://user-images.githubusercontent.com/68385605/136382095-e98411a2-7316-454e-a69f-e38d894d71af.png)

Assignment 2 완료.
