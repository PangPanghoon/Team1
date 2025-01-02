<img width="1200" alt="img" src="https://github.com/user-attachments/assets/cab7e848-3026-4362-8e68-b70548024b12" />

# Git을 이용해 협업하기

## 팀원
- 김광훈
- 김준우
- 민기
- 이유빈
- 박유진
- 정준  

## 주요 기능 및 작업 내용
1. Repository 환경설정
    1. Github Repository 페이지 → Setting (우측 상단)
    2. Manage Access (or Collaborators)
    3. invite a collaborator 버튼 클릭
    4. 팀원의 Github 이메일 입력 → 초대
    5. 팀원 각자 수락 → Maintainer 권한 부여
    6. gitignore 파일 한 번 세팅해 보기
    7. README.md 파일 세팅해 보기
2. Branch Protection 설정으로 PR 강제하기 
    1.  dev 브랜치 생성하여 dev에 즉각 커밋이 불가능하도록 설정
    2. Setting → Branches → Add branch protection rule 클릭
    3. Branch name pattern = main
        1. 실제 브랜치 이름과 맞게 설정해야 함. main 혹은 master
    4. Rule 옵션
        1. Protect matching branches → 활성화
        2. Require pull request reviews before merging → 체크
        3. Require approvals → 전체 팀원 -1 명 이상 review 필요
        4. Include Administrators → 체크
        5. save
    5. PR
        1. 각자 작업 후 PR 요청
        2. PR 페이지 접근 → 코드 리뷰
        3. File changed 탭 확인 → Review changes 클릭

