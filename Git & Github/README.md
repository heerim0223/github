# Git & Github
##  Git과 Github
+ ### [Git](https://git-scm.com/)
```
Git의 정의
로컬 파일의 변경사항을 기록하고 해당 파일에 대한 여러 사용자 간의 작업을 조율하기 위한 버전 관리 시스템(VCS: Version Control System)입니다.

Git의 특징:
1. 소프트웨어 개발에서 소스 코드를 효과적으로 관리할 수 있습니다.(유지보수)
2. 로컬 컴퓨터가 분산처리 서버가 되므로 중앙 서버가 할 일이 감소합니다.(빠른 처리속도)
3. 프로젝트 폴더 내에서 작업을 기록하고, 버전 관리를 통해 체계적인 개발이 가능하도록 합니다.(버전 관리)
4. 수천 개를 동시 다발적으로 Branch(가지치기)할 수 있습니다.(비선형적 개발)
```
+ ### [Github](https://github.com/)
```
Github의 정의
Git 저장소를 관리하는 클라우드 기반 웹 호스팅 서비스입니다.

Git의 특징
1. Github 클라우드에 Push(업로드)하여 서로 다른 위치에 있는 여러 사용자가 작업할 수 있습니다.(협업, 병렬 개발)
2. Github는 개발자들이 메인 코드 베이스에 병합되기 전에 코드 변경 사항을 검토하고 팀과 논의하여 잠재적인 버그를 방지할 수 있도록 합니다.(코드 리뷰)
3. Github는 크고 활발한 개발자 커뮤니티를 가지고 있어 다른 개발자들과 컨택하고, 자신의 작업을 공유하기 좋습니다.(커뮤니티)
```

## Git Install(2.42.0 기준)
[Git Install 방법](https://github.com/heerim0223/github/blob/main/Git%20%26%20Github/Git%20Install.md)

## 기본 용어
+ Repository(저장소): 저장소는 히스토리, 태그, 소스의 가지치기 혹은 Branch에 따라 버전을 저장합니다. 저장소를 통해 작업자가 변경한 모든 히스토리를 확인할 수 있습니다.
+ Working Tree: 저장소의 어느 한 시점에서 바라보는 작업자의 현재 시점.
+ Commit: 현재 변경된 작업 상태를 점검을 마치면 확정하고 저장소에 저장하는 작업.
+ Staging Area: 저장소를 커밋하기 전에 Commit을 준비하는 위치.
+ Branch(가지, 분기점): 작업을 할 때에 현재 상태를 복사하여 Branch에서 작업을 한 후에 완전하다 싶을 때 Merge하여 작업을 합니다.
+ Head: 현재 작업중인 Branch를 가리킵니다.
+ Merge(병합): 다른 Branch의 내용을 현재 Branch로 가져와 합치는 작업을 합니다.
+ Main(= 구 master): 이전에는 Master Branch로 Merge가 되었지만, Master라는 단어가 흑인을 비하하는 단어라고 해서 Main으로 통합되었습니다.

## 명령어
+ git --version: 설치되어 있는지 확인하고, 버전을 확인합니다.
+ git init: Git 저장소를 초기화합니다.
+ git help: Git의 명령어의 세부 옵션을 표시합니다.
+ git status: 저장소의 상태를 체크합니다.
+ git clone: 원격저장소의 저장소를 내 local에서 이용할 수 있게 그대로 복사해서 가져옵니다.
+ git add: 
+ git commit: 로컬 컴퓨터에서 작업할 때, 저장소의 변경된 내용을 로컬 저장소에 적용합니다.
+ git pull:
+ git log: Commit 내역을 확인할 수 있습니다.
+ git branch: 여러 협업자와 작업할 때 주로 사용하며, 새로운 Branch를 만들고 독립적인 공간을 만듭니다.
+ git checkout: 독립된 작업 공간인 Branch를 자유롭게 이동할 수 있습니다. 만약 Main(= 구 Master) Branch를 들여다 보고 싶을 때 git check out main을 사용할 수 있습니다.
+ git merge: Branch에서 작업을 끝내고, 모든 협업자가 볼 수 있는 Main(= 구 Master) Branch로 병합합니다.
+ config 설정:
```
git config --global (Github 가입 이름)
git config --global (Github 가입 이메일)
비밀번호 : (Github 가입 비밀번호)
```
+ remote 등록:
```
git remote add origin (Github 주소)
```
![image](https://github.com/heerim0223/Test/assets/74406700/7318c5b8-a93b-485a-afeb-559c04b39dff)

## Git Commit


## 참고 문헌
1. [Git](https://git-scm.com/)
2. [Github](https://github.com/)
3. [WikiPedia - Git](https://ko.wikipedia.org/wiki/%EA%B9%83_(%EC%86%8C%ED%94%84%ED%8A%B8%EC%9B%A8%EC%96%B4))
4. [WikiPedia - Github](https://ko.wikipedia.org/wiki/%EA%B9%83%ED%97%88%EB%B8%8C)
5. [[GitHub] 깃허브란? 깃허브의 장점과 단점](https://hoohaha.tistory.com/104)
6. [wlgns410.log - git](https://velog.io/@wlgns410/git)
7. [[GITHUB 입문] Git 설치하기(2.35.1 이상, 상세한 설치법)](https://taewow.tistory.com/13)
8. [Git | Git 초기 세팅 및 add, commit, push 해보기](https://velog.io/@suasue/Git-Git-%EC%B4%88%EA%B8%B0-%EC%84%B8%ED%8C%85-%EB%B0%8F-add-commit-push-%ED%95%B4%EB%B3%B4%EA%B8%B0)
9. [[Git] local 변경 사항 commit하기 : git commit, add, status, init](https://choiiis.github.io/git/how-to-commit-local-change/)

