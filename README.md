# test.kimdau
Code  와 github 와 연결하는법


먼저 터미널에 바로 bash 로 설정할수있겜 바꿀 예정  + 겸사 겸사 Emmet 한국어로


설정(crtl+,)
json.schemas 검색 ->편집

기본 터미널을 Git Bash로 설정
  "terminal.integrated.defaultProfile.windows": "Git Bash",

  // Emmet 한국어 설정
  "emmet.variables": {
    "lang": "ko",
  },
  추가 하면됨

  //////////////////////
  내 셋팅
  {
  "workbench.iconTheme": "material-icon-theme",
  "files.autoSave": "afterDelay",
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "liveServer.settings.donotShowInfoMsg": true,
  // 기본 터미널을 Git Bash로 설정
  "terminal.integrated.defaultProfile.windows": "Git Bash",

  // Emmet 한국어 설정
  "emmet.variables": {
    "lang": "ko",
  },
  "json.schemas": [
    

  
  ],
}


VS Code 사용자 이메일 등록
새 컴퓨터나 새로 설치한 Git에서 딱 한 번만 설정 해야함
git config --global user.email "a01088619487@naver.com"
git config --global user.name "a01088619487@naver.com"
git push --set-upstream origin master


Github 에 내 VScode 공유하는법 

Git Hub 홈->Repositories -> New ->Repository name:제목정하고 Create repository-> 주소[링크] 복사후 
Code 터미널에 들어와서
복사 붙여넣기[이때 홈페이지 새로고침해서 파일이 만들어졋는지 확인할것  그리고 공유 목적일때는  'index.html' 파일을 만들어야 공유가 가능함] 
->'git init'(처음 올릴때 꼭 필요함 - 현재 폴더를 Git 저장소로 만들기) ->' git add . '(파일전체를 담기)[공백 꼬옥중요] -> 'git commit -m "제목"'(메세지적고 저장하기) -> 'git push' (전송)
하면 내코드가 홈페이지에 들어간거 확인한다

index.html 파일이 없으면
깃허브에 프로젝트를 올렷는데 그안에 그 파일이 없다면 웹서버 입장에선 어떤파일을 보여줘야할지 모른다고함.
이로인하여 배포를 해도 화면이 안나오고 오류페이지가 뜨거나 웹사이트 화면 대신 폴더
파일 목록이 텍스트로 나타날수있음

그래서 저장용으로 올리는거면  index.html파일은 없어도 잘올라간다
하지만 나만의 웹사이트를 만들어서 공개및 배포를 하고싶다면 브라우저가 먼저 읽을수있게 첫페이지 파일 이릉ㅁ을 반드시 'index.html' 로 만들어야한다



GitHub를 내 코드로 다운로드 받는법

Git Hub 홈 -> Repositories -> 원하는 리포지토리에 들어간뒤 -> <>Code[초록색] ->
HTTPS탭 아래에 나오는 URL주소 를 복사 -> 터미널 열기[bash 확인]
->'git clone [복사한 주소 붙여넣기]'
하면 
내가 작성한 코드를 다운로드 받을수있다


인터넷깃허브 저장소와 연결(원격주소등록)
GitHub 웹에 로그인해서 업로드할 리포지토리-> <>Code 버튼을 누르고 HTTPS 주소를 복사->git remote add origin[복사한 주소 붙여넣기]



https://github.com/a01088619487-blip/test.kimdaun.git