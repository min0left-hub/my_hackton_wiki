# my_hackton_wiki

AI와 과제를 진행할 때 참가자의 판단을 보존하고, 요구사항·결정·진행·검증을 파일로 이어가는 공개 준비 도구함입니다. 공식 시험 지침·정답·자동 기억 동기화 서비스가 아닙니다.

## 시작 순서
1. 실제 시험 규정과 과제 README를 참가자가 먼저 읽습니다.
2. Codex에게 이 저장소의 AGENTS.md와 START_PROMPT.md를 읽도록 요청합니다. 읽기 성공 여부만 알리고 참가자 해석을 기다리게 합니다.
3. 참가자가 자신의 이해를 설명합니다. 검토만 요청하면 검토만 합니다.
4. 참가자가 기획 정리를 승인하면 requirements-planning Skill로 필수·우선·미확인·성공 조건을 기록합니다.
5. 구현은 별도 명시적 승인 후 시작합니다. 승인된 범위 안의 통상적인 편집·테스트는 반복 확인 없이 진행합니다.
6. 기능별로 검증하고 wiki 문서를 갱신합니다. 모델별 역할은 정하지 않습니다.

## 구성
- [AGENTS.md](AGENTS.md): 공통 원칙과 승인 경계
- [START_PROMPT.md](START_PROMPT.md): 새 세션에서 읽을 시작 지침
- [.agents/skills/requirements-planning/SKILL.md](.agents/skills/requirements-planning/SKILL.md): 경량 기획·요구사항 정리
- [.agents/skills/verify-work/SKILL.md](.agents/skills/verify-work/SKILL.md): 실제 결과 검증
- [.agents/skills/fix-errors/SKILL.md](.agents/skills/fix-errors/SKILL.md): 실패 재현·원인 확인·최소 수정
- [wiki/INDEX.md](wiki/INDEX.md): 프로젝트 기억의 입구
- [templates](templates): 과제별 기록을 시작할 빈 양식
- [SOURCES.md](SOURCES.md): 참고 출처와 독립 작성 범위
- [VALIDATION.md](VALIDATION.md): 검사한 범위와 한계

## 기억과 공유
새 세션이 문서를 자동으로 전부 읽거나 다른 세션 대화를 자동 공유하는 것은 아닙니다. 프로젝트 안의 wiki/INDEX.md와 연결 문서를 읽도록 요청하세요. 실제 파일을 확인한 내용과 문서 주장도 대조합니다. 같은 파일을 여러 세션이 동시에 수정하지 않게 작업 범위를 지정합니다.

## 시험 중 사용
공개 저장소에는 범용 지침과 빈 양식만 유지합니다. 실제 과제 문제·개인 응시 링크·첨부자료·대화·코드·로그·완성된 위키는 시험 작업 공간에만 두고 이 저장소로 업로드하거나 Git Push하지 않습니다. 공개 자료의 허용 범위와 공개 유지 기간은 최신 운영 안내를 따르세요. 이 저장소를 읽었다고 Skill이 설치·인식됐다고 주장하지 않습니다. 지원되지 않으면 필요한 SKILL.md를 직접 읽혀 사용합니다. 실제 제출 문서와 파일명은 과제 안내가 우선입니다.
