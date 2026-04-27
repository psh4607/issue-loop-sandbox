# issue-loop-sandbox

dev-agent `issue-loop-agent` 의 E2E 테스트 샌드박스.

이슈를 생성하면 `issue-loop-agent` 데몬이 2분 polling 으로 픽업하여
`triage → spec → plan → implement → verify` phase 를 자동 진행한다.
