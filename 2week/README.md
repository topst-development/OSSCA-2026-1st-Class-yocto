2주차 숙제입니다. 질문은 관련 link(https://community.topst.ai/t/2026-1st-ossca-git-yocto-2/926) 또는 Discord에 남겨 주세요~

1. Github Collaborator 초대 수락하기

    협업자가 초대를 수락하는 방법  
  - github에 등록된 이메일 또는 GitHub 알림 확인
  - 초대 수락 버튼 클릭
  - 리포지토리 접근 가능해짐

2. Github ( topst-development/OSSCA-2026-1st-Class-yocto) clone 하기
(중요!! 1주차에 사용한 자신의 Fork된 내용을 받는 것 아님!!!)

3. 본인의 branch를 생성할 것  
    branch 이름 템플릿: feature/{한글이름}-dev

4. git에 2Week 디렉토리에 파일 추가하기
   - 모임참석 관련 파일 추가
     - 파일 이름 템플릿: yocto3주차off모임참석여부.md
     - 파일 내용에 꼭 들어가야 하는 text: git&yocto-3주차Off모임 =
     - text 다음에 들어갈 답변: {참석} 또는 {불가}
   - 그 다음 파일 추가
     - 파일 이름 템플릿: merge-{한글이름}-선택.md
     - 파일 내용에 꼭 들어가야 하는 text: merge-선택={merge} 또는 {rebase}
     - 본인 branch를 main에 merge 할 때, merge commit을 만들 것인지, rebase를 해서 올릴 것인지 내용도 추가

5. git의 main branch에 자신의 branch를 merge/rebase 하기

6. Github ( topst-development/OSSCA-2026-1st-Class-yocto) push 하기 (중요: PR이 아닙니다!!!)
- 만약 충돌이 난다면!
- 본인 파일에 충돌 내용 추가해서
- 충돌 해결한 후에 push 하기
