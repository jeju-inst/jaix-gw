# jaix-gw — 그룹웨어 도우미 스킬 (자동 생성)

> **이 저장소는 자동 생성된다. 여기서 고치지 말 것.**
> 원본은 [`jeju-inst/ji-gw-ai`](https://github.com/jeju-inst/ji-gw-ai) 의 `share/` 이고,
> ji-gw-ai main 에 머지되면 `share-publish` 워크플로가 누수 검사를 통과한 경우에만 이곳으로 밀어 넣는다.
> 수정은 ji-gw-ai 에 PR 로 올린다. 이곳의 직접 커밋·PR 은 `guard` 검사가 거절하고 다음 동기화가 덮어쓴다.

제주연구원 연구원용 그룹웨어 도우미 `gw` 의 에이전트 스킬이다. 본인 계정으로 회의실 예약,
근태·출장·증명서 기안전 준비와 확인 코드 상신, 본인 결재함·결재 본문 읽기를 돕는다.

- 스킬: `skills/gw/SKILL.md`
- 런타임(`gw` 명령)은 이 저장소에 없다. **jaix-setup 이 원내 위치에서 설치**한다(사내 한정).
  스킬은 시작할 때 `gw version-check <최소 버전>` 으로 런타임 버전을 확인하고, 낮으면 jaix-setup 재실행을 안내한다.
- `share-build.json`: 이 커밋을 만든 원본 커밋(`source_sha`)·요구 런타임 버전(`runtime_version`)·내용 해시.
- 라이선스: **이 저장소의 스킬 문서만 MIT**(`LICENSE`). 런타임(`gw`)은 이 저장소에 없고 사내 배포다(재배포 불가).
- 버전 태그(vYYYY.MM.DD.N)는 `calver` 워크플로가 자동으로 단다. jaix-kit 잠금은 갱신 봇이 올린다.
