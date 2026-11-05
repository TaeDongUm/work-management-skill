# 과제 수행·이해 확인 키트
개정 v2 · 2026-11-05 · 첨부 work-management-skill(2).zip 기준.

## 바로 시작
[EXAM_QUICK_GUIDE.md](EXAM_QUICK_GUIDE.md)에서 현재 단계의 요청문 하나를 사용한다.
이번 목적은 AI가 만든 결과를 본인이 이해하고 선택·검증·한계를 설명하는 것이다.
이 파일 묶음은 설치형 SKILL.md가 없는 Markdown 키트다. 자동 설치·공개 저장소 업로드는 하지 않는다.

## 이번 수정
- 원문과 데이터를 함께 먼저 조사하도록 순서를 변경했다.
- 미확정 → 구체적 재질문 → 역제안 → 실제 합의/개발자 결정/임시 가정/차단으로 처리한다.
- 계산 문제 정의·기본안·대안·독립 검증을 UI 작업 앞에 둔다.
- 본인 이해 확인을 조사 후·설계 선택 후·핵심 흐름과 큰 변경 후에 분산한다.
- DATA_MAP과 UNDERSTANDING을 추가하고 WORKLOG의 중복 이해 기록을 옮겼다.
- EXAM_QUICK_GUIDE의 중복 흐름·Mermaid를 제거하고 복사용 Markdown으로 축약했다.
- 존재하지 않던 prep/REVIEW_NOTES.md 링크와 변경 프롬프트의 잘못된 경로를 수정했다.
- 지난 10월 31일 일정은 과거 안내로 표시했다. 재응시 새 공지가 우선이다.
- 배포본에서 불필요한 .git 내부 이력·설정을 제외했다. 기존 원격 저장소는 변경하지 않았다.

## 파일 역할
| 파일 | 역할·사용 시점 |
|---|---|
| [runtime/WORKFLOW.md](runtime/WORKFLOW.md) | 공통 작업 원칙 |
| [runtime/REQUIREMENTS.md](runtime/REQUIREMENTS.md) | 요구·목표·정책·질문·합의 |
| [runtime/DATA_MAP.md](runtime/DATA_MAP.md) | 데이터 의미·품질·없는 정보·대표 사례 |
| [runtime/DESIGN.md](runtime/DESIGN.md) | 계산·스택·대안·실제 모듈·변경 영향 |
| [runtime/VERIFICATION.md](runtime/VERIFICATION.md) | 기대값·실행·위임/직접 확인·남은 범위 |
| [runtime/WORKLOG.md](runtime/WORKLOG.md) | 작업·AI 협업·오류·중요 변경 |
| [runtime/UNDERSTANDING.md](runtime/UNDERSTANDING.md) | 내 실제 설명·교정·근거 색인 |
| [runtime/HANDOFF.md](runtime/HANDOFF.md) | 중단·전환 시에만 인계 |
| [prompts/discovery/00_UNDERSTAND_TASK_AND_DATA.md](prompts/discovery/00_UNDERSTAND_TASK_AND_DATA.md) | 초기 과제·데이터 조사 |
| [prompts/discovery/01_INTERVIEW.md](prompts/discovery/01_INTERVIEW.md) | 질문·재질문·역제안 |
| [prompts/design/01_SOLUTION.md](prompts/design/01_SOLUTION.md) | 계산·구조·검증 설계 |
| [prompts/change/PROPAGATE_CHANGE.md](prompts/change/PROPAGATE_CHANGE.md) | 변경점의 관련 문서·작업 전파 |
| [prompts/review/01_REVIEW_AND_EXPLAIN.md](prompts/review/01_REVIEW_AND_EXPLAIN.md) | 공통 검증·내 설명 확인 |
| [prompts/review/02_GAP_REVIEW.md](prompts/review/02_GAP_REVIEW.md) | 첫 흐름 후 필요할 때 부족 보완 |
| [prompts/ui/01_PLAN.md](prompts/ui/01_PLAN.md) · [02_BUILD.md](prompts/ui/02_BUILD.md) · [03_REVIEW.md](prompts/ui/03_REVIEW.md) | UI 필요 시만 사용 |
| [SUBMISSION_DOCUMENT_GUIDE.md](SUBMISSION_DOCUMENT_GUIDE.md) | 실제 지정 제출 문서로 기록 매핑 |
| [prep/EVALUATION_REFERENCE.md](prep/EVALUATION_REFERENCE.md) | 후기 기반 참고, 공식 배점 아님 |
| [prep/TOOLS.md](prep/TOOLS.md) · [prep/PRECHECK.md](prep/PRECHECK.md) | 사전 참고, 최신 안내와 대조 |

## 기록 부담 제한
- 사실은 한 곳, 다른 곳은 ID·짧은 참조. 매 명령·매 대화마다 전체 갱신하지 않는다.
- 기존 README는 보존한다. 추가 README를 여러 개 만들지 않는다.
- 제출 양식에 같은 항목이 있으면 그곳에 직접 기록하고 runtime 복제본을 만들지 않는다.
- UNDERSTANDING은 짧은 본인 설명 중심이며 긴 답안집·모든 함수 목록을 만들지 않는다.
- 핵심 3~4개 작업 묶음으로 관리하되 필수 요구를 누락하지 않는다.
- 화면 검증은 VERIFICATION의 UI 항목으로 통합한다. 별도 화면 결과물이 필수면 그 파일을 참조한다.
- HANDOFF는 필요할 때만, 평가 관점 전체 점검은 첫 흐름 후 필요할 때만 쓴다.

## 적용 한계
문서가 점수·정답·반입 승인을 보장하지 않는다. 제공 과제·규정이 우선이다.
시험 자료·실제 기록을 외부로 전송하거나 Git Push하지 않는다. 공개용 빈 양식과 실제 기록을 구분한다.
후속 AI 금지 문항에서는 사용하지 않는다. 해당 단계의 문서 열람 가능성도 가정하지 않는다.
이 개정은 문서 구조·링크 점검을 거쳤으며 실제 시험 환경이나 풀타임 리허설로 검증한 것은 아니다.
