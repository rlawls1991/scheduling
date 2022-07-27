# HOW TO CONTRIBUTE
## Process
해당 Repository 에 contribute 하는 방법을 소개드립니다.

### Pull Request 를 통한 Contribute
#### 1. Fork this respository
이 repository 를 fork 해주세요!

#### 2. Clone forked repository
fork한 repository 를 local directory 에 clone 해주세요!

```bash
# in your workspace
$ git clone https://github.com/Codingvengers/scheduling.git
```

#### 3. Commit your
```bash
$ git add .
$ git commit -m "[your description]"
$ git push origin main
```

### 4. Register pull request for your commit
`Pull Request`를 등록해주세요.

### Optional. Resolve Conflict
Pull Request 를 등록했는데, conflict 가 있어서 auto merge 가 안된다고 하는 경우 해당 conflict 를 해결해주세요.

```bash
# in Interview_Question_for_Beginner
$ git remote add --track main upstream https://github.com/Codingvengers/scheduling.git
$ git fetch upstream
$ git rebase upstream/main
# (resolve conflict in your editor)
$ git add .
$ git rebase --continue
$ git push -f origin main
```
- 참고자료 : [많은 Git 커맨드 중 정말 필요한 것만 정리한 내용](https://github.com/JaeYeopHan/Minimal_Git_command)
