LEARN GIT
==============



Read the Docs https://readthedocs.org

.rst (reStructureText) https://en.wikipedia.org/wiki/ReStructuredText

.rst Specification: https://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html

learngit ReadTheDocs: https://readthedocs.org/projects/learngit/




---------------------------------------------------------------



HI
==============

hello




---------------------------------------------------------------



GIT
==============

[[GIT]]


* 원격저장소에 파일을 올리는 과정

[ 내 작업 트리 (폴더) ]
--(add)--> [ 인덱스(스테이지) ]
--(commit)--> [ 로컬저장소(repository) ]
--(push)--> [ 원격저장소 ]



* 원격저장소의 최신데이터를 가져와 업데이트하는 과정

[ 원격저장소 ] --(pull)--> [ 로컬저장소 ]



* 원격저장소의 모든 파일을 복제해 가져오는 과정

[ 원격 저장소] --(clone)--> [ 로컬저장소 ]



* 브랜치
: 독립적인 여러 작업을 별개로 진행할 때, 브랜치를 나누어 따로 작업한 후 병합한다.
브랜치는 다른 브랜치의 영향을 받지 않으므로, 여러 작업을 동시에 수행하기 쉽다.
저장소를 초기화하면 기본적으로 master 브랜치가 생성된다.



------------------------------------------------------------



*기본 명령어 정리

git config --global user.name "~~~"
:이름 설정

git config --global user.email "~~~"
:깃허브 메일주소



git init
:초기화

git add .
:현재폴더의 모든 파일을 staging (현재 작업트리의 파일을 인덱스(스테이지)로 이동)

git commit -m "설명"
:인덱스(스테이지)에 새로 추가된 파일들을, 내 로컬 저장소(repository)로 이동)

git remote add origin https://github.com/계정/원격저장소이름.git
:원격저장소와 연결

git push origin master
:원격저장소의 master 브랜치로 자료 갱신



git clone https://github.com/계정/원격저장소이름.git
:원격저장소의 파일들을 내 로컬저장소에 복제

git pull https://github.com/계정/원격저장소이름.git
:원격저장소의 파일들 중 갱신된 파일을 내 로컬저장소로 업데이트



git branch "브랜치이름"
:새로운 브랜치 생성

git checkout "브랜치이름"
:브랜치 전환

(git checkout -b "브랜치이름")
:생성, 전환 한번에

git merge "브랜치이름"
:현재 브랜치에 다른 브랜치를 병합함

git branch -d "브랜치이름"
:브랜치 삭제


^_^)b




-------------------------------------------------------------------


BYE
==============

bye bye
