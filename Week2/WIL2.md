add: Working Directory에서 staging area로 옮기는 것. 다음 변경을 기록할 때까지 변경분을 모아두는 작업. staging area는 repository에 업로드 하기 전 임시 저장 정도.
commit: staging area에 저장되어 있는 변경 사항들을 로컬 저장소에 등록하는 것. 변경 사항을 확정하는 작업.
push: 지금까지의 버전을(commit된 파일들을) repository로 저장하는 것.

fetch: 변경 사항이 있는지 확인만 하는 것. 데이터를 실제로 가져오지는 않음.
pull: 변경된 데이터 정보를 확인할 뿐만 아니라 변경된 데이터를 실제로 로컬 git에 가져옴.

gitbash에서도 add commit 등 가능.

# WIL1
인터넷 주소를 입력했을 때 어떤 일이 일어나는가?

허니 콤보를 얻을 수 있는 교촌 치킨 신촌점 주소가 웹사이트의 주소임.

URL
리소스를 식별하는 통일된 방식
허니 콤보를 얻을 수 있는 위치를 얻어내기 위한 방식
유니폼 리소스 로케이션

URL = 교촌 치킨 신촌점

아이피는 언제든 사정에 의해 바뀔 수 있음.
사이트 이름이 도메인 주소다.

리소스의 정체는 html, css, js를 재료 삼아 브라우저가 렌더링을 해주는 것이다.

HTML: 자료(뼈대)
CSS: UI(살과 옷)
자바스크립트: 제어

# WIL2 
git을 사용하는 이유: 협업에 용이함.
변경 사항을 추적.
파일의 4가지 상태: 추적X, 변경X, 변경O, staged

working directory / staging area / local repository / git
                 add          commit              push

github = remote repository