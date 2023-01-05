# Git-Flow 
원활한 개발을 위해 개발 단계별로 branch를 나누어 관리하는 방법론

# Git-Flow branch 
### 1. 주요 branch (필수)
- master : 최종 배포 브런치. 최초 개발이 완료되면 큼직한 업데이트가 있을 때 사용.
- develop : 주요 개발에 사용되는 브런치. 각자 작업한 기능을 합(Merge)하는 공간.   


### 2. 기능 branch (필요에 따라 생성하여 사용)
- feature : 기능 단위로 개발하는 브런치. 기능 개발이 완료되면 develop 브런치에 합침.   
  Ex) feature-login 브랜치 생성하여 개발 후 완료되면 develop에 합
- release : master 브런치로 보내기 전에 먼저 QA(품질검사)를 하기위한 공간.
- hotfix : master 브런치로 배포를 했는데 버그가 생겼을 떄 긴급 수정하는 공간.   
  develop 브런치를 거치지 않고 바로 master 브런치와 소통. 


# 참고자료

- "(알아두면 개발팀장가능) GitFlow vs Trunk-based 협업방식." 유튜브 비디오, 6:05. "코딩애플,"  2022. 7. 11. https://youtu.be/EV3FZ3cWBp8 
- "Git Flow 개념 이해하기." 앤조이[nJo2]. 2020년 3월 12일 작성, https://ux.stories.pe.kr/183 
