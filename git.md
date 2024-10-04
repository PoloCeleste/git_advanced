- `staging area`란, 등록한 파일들의 변동사항만 기록한 txt파일을 `.git` 폴더 어딘가에 모아둔다.

```bash
# staging area에 등록해둔 변동사항을
# 하나의 버전으로 기록한다.
# 그 후, staging area는 비운다.
$ git commit -m "commit message"
```

- `commit` 즉 버전이란, 아까전 `staging area`에 등록해둔, 변동사항만을 모아서 하나의 상태로 저장한다.
- 그곳을 `repository`라고 부른다.

- git branch
- git branch -d {branch name}
