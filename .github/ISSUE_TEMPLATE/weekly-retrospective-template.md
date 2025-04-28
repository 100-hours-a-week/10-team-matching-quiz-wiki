---

name: Weekly-Retrospective-Template
about: '팀 주간 회고 템플릿입니다.'
title: ''
labels: Weekly Retrospective
assignees: ''

---

# 주간 회고 템플릿 (Weekly Retrospective)

## 0. 이번 주 스프린트 목표 (Sprint Goals)

- 이번 주 팀이 설정했던 주요 목표를 작성합니다.
- 구체적인 산출물이나 기능 위주로 작성해 주세요.

> 예시:
> - 면접 피드백 API 베타 오픈
> - Whisper STT 모델 성능 측정
> - GCP + FastAPI 구조 최종 점검

---

## 1. 실제 완료된 작업 (What was done)

- 구체적으로 내가 이번 주 개인의 성과!! 마음껏 자랑해주시면 됩니다.
- 넘버링해서 자세히 작성해주세요!

| 파트 | 담당자 | 완료 작업 | 산출물 링크 |
| --- | --- | --- | --- |
| AI | Eunice |  |  |
| AI | Tommy |  |  |
| AI | David |  |  |
| BE | Leo |  |  |
| FE | Joy |  |  |
| CL | Jihoo |  |  |
| CL | Ken |  |  |

---

## 2. 어려웠던 점 및 장애 요인 (Challenges)

- 기술적/조직적 어려움, 협업 중 겪은 이슈를 파트별로 작성합니다.
- “무엇이 왜 힘들었는지”를 구체적으로 기술하면 좋아요!

> 예시:
> 
> - GCP 서비스 계정 권한 문제로 STT 요청 실패 → IAM 설정 재검토 필요
> - LLM 응답 지연 (평균 24초) → vLLM 실험 필요

| 파트 | 담당자 | 장애 요인 | 해결 방안(방법) |
| --- | --- | --- | --- |
| AI |  |  |  |
| BE |  |  |  |
| FE |  |  |  |
| CL |  |  |  |

---

## 3. 개선 사항 및 인사이트 (Improvements & Insights)

- 이번 주에 새롭게 배운 점, 실험 결과로 알게 된 통찰을 작성해주세요.
- 다음 주에 반영할 구조적 개선 방향 포함해주시면 더 좋습니다!

> 예시
> 
> - Whisper-large-v3는 정밀도 ↑, 속도 ↓ → 상황에 따라 모델 스위칭 구조 고려
> - BERTScore를 기반으로 피드백 문장 개선 평가 → 기준 점수 설정 필요
> - Redis를 통한 피드백 캐싱 적용 후, API 평균 응답시간이 1.2초 → 0.4초로 단축됨
> → 정적 데이터에 대한 TTL 설정 전략 검토 필요
> - Refresh Token 재발급 시 기존 DB 조회 방식 대비 Redis Lookup이 5배 빠름
> → 보안 레이어 추가 없이 구현 가능할지 검토 필요
> - 피드백 결과에 대해 `localStorage` 기반 브라우저 캐싱 실험 진행
> → 재요청 시 네트워크 사용량 60% 감소 확인
> → 그러나 캐시 만료 정책 미정으로 상태 불일치 이슈 발생 가능성
> - Langsmith를 이용한 로드 밸런싱 실시간 모니터링 실험
> → 특정 모델 노드에 처리 집중 현상 확인 → 요청 균등 분산 정책 개선 필요
> - GCP Cloud Monitoring 설정을 통해, inference 서버의 메모리 임계점 탐지 가능
> → Auto-scaling 임계값 재설정 검토

| 파트 | 담당자 | 주제 | 산출물 링크 or 간단한 설명 |
| --- | --- | --- | --- |
| AI | Eunice |  |  |
| AI | Tommy |  |  |
| AI | David |  |  |
| BE | Leo |  |  |
| FE | Joy |  |  |
| CL | Jihoo |  |  |
| CL | Ken |  |  |

---

## 4. 다음 주 계획 (Next Week’s Action Items)

- 파트별 - 대략적으로, 개인별 - 상세하게 작성해주세요.

| 파트 | 담당자 | 장애 요인 | 해결 방안(방법) |
| --- | --- | --- | --- |
| AI |  |  |  |
| BE |  |  |  |
| FE |  |  |  |
| CL |  |  |  |

| 파트 | 담당자 | 작업 목표 | 목표일 |
| --- | --- | --- | --- |
| AI | Eunice |  |  |
| AI | Tommy |  |  |
| AI | David |  |  |
| BE | Leo |  |  |
| FE | Joy |  |  |
| CL | Jihoo |  |  |
| CL | Ken |  |  |

---

## 5. 팀원 소감 및 피드백 (All Members Required)

> 이번 주를 마무리하며, 각자 느낀 점이나 팀에 전하고 싶은 피드백(개선사항)을 작성해주세요.

| 파트 | 팀원 | 소감 및 피드백 |
| --- | --- | --- |
| AI | Eunice |  |
| AI | Tommy |  |
| AI | David |  |
| FE | Joy |  |
| BE | Leo |  |
| CL | Ken |  |
| CL | Jihoo |  |

---
