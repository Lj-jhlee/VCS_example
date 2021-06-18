# Version Control System Example Repository

## Issue

- 기능 개발, 버그 리포팅, 정보 공유 등
- 각 테마마다 템플릿을 만들어서 사용
- 이슈 등록 시
  - Assignees, Labels, Projects, Milestone, Linked pull requests 등 알맞게 연결
    - Assignees : 등록자 자신
    - Labels : 버전 or 테마에 맞는것으로 등록
    - Projects : Total Projects 와 이슈의 버전에 맞는 Projects에 등록
    - Milestone : 이슈의 버전에 맞는 Milestone 등록
    - Linked pull requests
      - 버그의 경우, 버그 해결 PR과 연결
      - 기능 개발의 경우 따로 등록 X

## Projects

- 전체 프로젝트 진행 사항을 한번에 볼 수 있는 Total Projects와 Major 버전 단위로 볼 수 있는 v1, v2 등의 Projects로 관리
- 이슈 등록 할 때, 해당 이슈에 맞는 버전과 Total Projects에 카드를 등록해서 관리
- Backlog, Todo, Done 으로 관리

## MileStone

- Minor 버전 단위로 관리 ( v1.1.0, v1.2.0 ... )
- 이슈 등록할 때 버전에 맞는 마일스톤 연결
- Minor 와 Patch 버전 관리용도

## Pull Requests

- Bug Fix 나 이슈 단위의 기능 개발 완료 시에 사용
- 이슈 단위 기능 개발 완료
  - 어떤 작업들을 했는지 check box로 나타냄
  - 마지막 줄에 어떤 이슈 단위와 연결되었는지 `resolved` 를 통해서 연결
  - 만약, 완전히 끝내지 못했다면, `issue`로 연결
- Bug Fix
  - 어떤 작업을 했는지 check box로 나타냄
  - 원인과 해결 방법을 간략히 작성
  - `resolved`를 통해서 Bug 이슈와 연결
