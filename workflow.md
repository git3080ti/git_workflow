# Git3080ti's Workflow

## 도식화 - Repository  
![repository_structure](./image/repository_structure.png)  

## Repository 운영  
1. 저장소는 팀의 upstream repository, upstream을 fork한 팀원의 origin repository, 팀원의 local repository로 구성. 
2. 팀원은 local repository에서 개발을 해서 자신의 origin repository로 push를 한다. 
3. github에서 자신의 origin repository를 upstream으로 pull request를 보낸다. 
4. 코드리뷰를 거친 후 pr을 merge한다. 
5. 팀원은 개발 중 upstream을 수시로 pull한다. 
6. 같은 내용에 대해서 서로 다른 두개의 pr이 들어올 경우, 팀 회의를 통해 더 적합한 pr을 선택해서 merge한다. 
7. pr의 자동 merge가 불가능할 경우(conflict가 난 경우), 해당 pr을 보낸 팀원이 upstream을 pull 한 후, 자신의 origin 레포에 force push를 통해 pr을 수정한다. 