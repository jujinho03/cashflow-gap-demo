# 출처와 고지

## 원본

이 폴더는 팀 통합 저장소의 데모 경로(`apps/demo/`)를 원천 커밋 `b2bbd0199767c890b98e4fc3af0b24ea39e6d819` 기준으로 분리한 스냅샷입니다. 그 데모는 원본 데모 커밋 `bd5a62518f07f4f738a1c1ec69d4c697d7345ccb`의 구조와 이력을 보존해 인수한 것입니다. 원저작자 기록과 전체 Git 이력은 원본 저장소에 그대로 남아 있습니다. 이 스냅샷에는 Git 이력을 옮기지 않았습니다.

분리하면서 바꾼 것:

- 루트 README를 이 폴더 기준의 설치·실행 안내로 새로 작성했습니다(원본 README는 원본 저장소 기준 경로와 링크를 사용).
- 디자인 참고 문서의 개인 PC 스크린샷 경로를 제거했습니다. 참고 디자인 명칭과 제3자 자산 고지는 보존했습니다.
- `frontend/src/components/cpa/Shell.tsx`의 모형 안내 문구 한 곳: 원본 저장소 문서로 가는 외부 링크를 README 참조 문구로 바꾸고, "루트 Python v4"를 "참가작 본문의 Python v4 참조 모형"으로 고쳤습니다. 계산·가정·기능은 바꾸지 않았습니다.

라이선스: 원본 데모에 별도 라이선스 파일이 없어 이 스냅샷에도 새 라이선스를 붙이지 않았습니다. 재사용 조건은 원저작자에게 확인해야 합니다.

## 제3자 자산

| 자산 | 사용 방식 | 라이선스 |
|---|---|---|
| Pretendard Variable | 실행 시 jsDelivr CDN에서 불러옴(파일 미포함) | SIL Open Font License 1.1 |
| Outfit | 실행 시 Google Fonts에서 불러옴(파일 미포함) | SIL Open Font License 1.1 |
| npm·Cargo 의존성 | `package-lock.json`, `Cargo.lock`에 고정. 설치 시 내려받음(파일 미포함) | 각 패키지의 라이선스 |

글꼴과 디자인 참고 출처는 `docs/DESIGN_REFERENCES.md`에 있습니다.

## 데이터

모든 고객·금액·일정은 합성 가정입니다. `ai/evaluations/cpa_experiment_runs.json`은 과거에 기록된 외부 AI 원출력이며, 이 데모가 이번 실행에서 AI를 다시 호출한 결과가 아닙니다. 원출력과 기록 내용은 분리하면서 수정하지 않았습니다.
