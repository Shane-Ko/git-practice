# Git Practice
## Git을 사용하는 방법

## 기본 명령어

```
git init
```    
- 현재 폴더를 프로젝트로 만든다

```
git status
```
- 현재 git으로 관리되고 있는 프로젝트가 어떠한 상태 등 정보를 확인하는 명령어

```
git add
```

```
git commit
```

```
git log
```

## restore을 사용해서 수정
```
git restore <file>...
``` 
- 마지막 커밋된 상태로 돌리기

## add만 된 변경사항 으로 되돌려 보자

```
git restore --staged <file>
```
- 코드를 마지막 커밋으로 돌리는 것이 아닌, add된 것만 취소함

## commit 된 것 없애기
```
git reset <commit 번호(?)
```
- 코드가 사라지는 것은 아님. commit 자체를 없던 일로 만듬 (많이 안쓰는 것이 좋음)

