# CatchUp 온보딩 Cold-start UX 실험

조직 협업툴이 연동되기 전 "빈 깡통" 상태에서, **사용자가 가치를 경험하기 전에 설정 부담을 먼저 지는 문제**를 어떻게 풀 것인가에 대한 5개 설계 가설 목업입니다.

## 바로 보기

`index.html`을 브라우저로 열면 5개 실험을 탭으로 전환하며 한 화면에서 볼 수 있습니다.

### GitHub Pages로 공유하기
1. 이 폴더를 repo에 push
2. **Settings → Pages → Source: main 브랜치 / root** 선택
3. 발급된 주소 `https://<계정>.github.io/<repo>/` 로 팀원과 공유

## 실험 목록

| # | 주제 | 가설 | 파일 |
|---|---|---|---|
| 1 | 가치 미리보기 (Value-first) | 연동 전 샘플 답변·출처를 미리 보여주면 설정 동기가 유지된다 | `experiment-1-value-preview.html` |
| 2 | 점진형 온보딩 (Progressive) | 1개만 먼저 연동시켜 작은 성공을 주면 완주율이 오른다 | `experiment-2-progressive.html` |
| 3 | 80% 매핑 대시보드 | 매핑 조건을 어드민이 팀원을 독려하는 진척 대시보드로 풀면 빨라진다 | `experiment-3-mapping-dashboard.html` |
| 4 | 빈 상태 가이드 (Empty state) | 빈 홈을 '다음 할 일'로 재정의하면 이탈이 준다 | `experiment-4-empty-state.html` |
| 5 | 모달 vs 인라인 (A/B) | 온보딩 제시 방식(모달/인라인)에 따라 완주율·이탈이 다르다 | `experiment-5-ab-comparison.html` |

## 제약 조건 (공통 전제)
- 최소 1개 커넥터 연동 필수
- 루트어드민 본인 계정을 각 협업툴에 매핑
- 사내 사용자 80% 이상 매핑 시 임베딩(정확한 답변) 활성화

## 참고
각 실험은 독립 실행형 인터랙티브 목업입니다. 카드/버튼을 클릭해 loading·empty·error·success 상태 전환을 직접 확인할 수 있습니다. 파일 용량이 큰 편(각 ~22MB)이라 첫 로드에 약간 시간이 걸릴 수 있습니다.
