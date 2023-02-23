## Git Command

- `git rebase [-i]`
- `git rebase [-i]`
  한 브랜치에서 다른 브랜치를 합치는 방법 중 하나이다
  다른 방법인 merge와 달리 깔끔하게 커밋 히스토리를 정리해준다

- `git rebase --abort`
  rebase 이전 상황으로 되돌아갑니다

- `git rebase --continue`
  rebase 상황에서 conflict를 해결한 후 --continue 명령어를 작성합니다

- `git reflog`
  로컬 저장소에서 HEAD의 업데이트 기록을 모두 출력합니다

- `git reset`
  현재 작업위치인 HEAD의 포인터를 특정 위치로 변경합니다
  reset을 통해 HEAD의 위치를 변경해주면 HEAD보다 뒤에 있는 커밋들은 연결이 사라지고, 히스토리에서 삭제된 것처럼 보이게 됩니다
