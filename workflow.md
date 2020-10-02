# Git3080ti's Workflow

### Issue

- 베타 버전(develop branch)에서 이슈가 보고되었을 경우, 해당하는 issue 번호를 붙여 **issue** 브랜치를 만듭니다. base branch 는 develop branch 입니다.
- 이 브랜치는 동시에 몇 가지 이슈를 해결하는지에 따라 여러 개 생성될 수 있습니다.
- 해당 이슈가 해결되면 develop 브랜치에 merge 합니다.
- develop 브랜치에 merge 된 issue 브랜치는 삭제합니다.

### Feature

- 새로운 기능을 추가하고 싶을 경우, 그 기능에 대한 **feature** 브랜치를 만듭니다. base branch 는 develop branch 입니다.
- 이 브랜치는 동시에 몇 가지 기능을 개발하는지에 따라 여러 개 생성될 수 있습니다.
- 해당 기능의 구현이 완료되면 develop 브랜치에 merge합니다.
- develop 브랜치에 merge 된 feature 브랜치는 삭제합니다.

