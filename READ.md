# npm 구동하는방법 
1.  nvm --version 하면 1.1.11 확인
1.  npm --version 하면 9.5.1 확인  

1.  npm init -y 하면 package.json화일생성됨  
1.  npm install parcel-bundler -D :
    (플래그는 개발용의존성패키지설치임)   
     나머지는 실제웹프라우져에서도 실행될수있다는 점이다. 
    node_modules 폴터 와 package-lock.json화일생성됨   
1.  npm install lodash 
1.   node_modules 폴터를 삭제후 다시, npm install하면  
      다시펙케지가 설치된다. 

1.  index.html과 main.js설치후 터미날차에서  
    parcel index.html실행한다.하니만 실행안되 
1.  "scripts": 이하 삭제함 
    "test": "echo \"Error: no test specified\" && exit 1"

1.  parcel index.html실행하면  

1.  parcel build index.html실행 전에 "scripts": {
    "dev": "parcel index.html",
    "build":"parcel build index.html"
  },삽입한다 
1.  devDependencies = 개발의존성 api , dependencies =  일반의존성 api  


1.  node --version 
1.  npm --version 
1.  용어설명 유의적버전 (semantic versioning , SemVer)
1.  ex) Major, Minor, Patch
    1.  e.g 12.14.1 
    1.  major버젼은 기존버젼과 호환안됨 
    1.  minor버젼은 기본버젼과 호환되나 새로운기능이 추가된버젼
    1.  기존버전과 호환되며 버그 및 오타등이 수정된 버전
1.  npm info lodash 
1.  npm install lodash@4.17.20 즉21에서 20으로 버전변경됨 
1.  npm update lodash 해서 20에서 21로변경함 
1.  npm run build 
1.  
1.  git init 하기전에 파일을 만든다. .gitignore
1.  git init , git status 추적되지않는 리스트를확인하고 
1.  git add . 변경사항이 추적되기시작해서 초록색으로 보인다. 
1.  git commit -m '프로젝트생성'
1.  버전이 잘만들어졌는지확인하기 위하여 git log하면 (head->master)를확인하고 

1.  git remote add origin https://github.com/kchair777/test.git 킷텁주소를 붙여넣는다. (origin별칭으로 remote의)

1.  git push origin master (master->master를 확인한다. )



