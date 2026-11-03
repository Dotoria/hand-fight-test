# 개발 일지

### 5일 계획

| 일차 | 할 일                  | 상태 |
|---|----------------------|----|
| 1 | 패키지 세팅, MD 파일 작성     | 완료 |
| 2 | 웹캠 확인, 움직임 추출, 규칙 분류 |    |
| 3 | 안정화 상태 머신, 게임 연결     |    |
| 4 | 녹화 영상 테스트, 측정        |    |
| 5 | 수치 기반 튜닝, 마무리        |    |
| + | Android 빌드, 최적화      |    |

---

## 1일차 — 2026-11-03

### 한 일
- git 저장소 초기화, 공개 레포 생성 ([hand-fight-test](https://github.com/Dotoria/hand-fight-test))
- `com.unity.ai.inference` 2.6.1 설치
- HuggingFace에서 `BlazeHand 모델 2개` + `앵커 CSV` 다운 및 배치
- 폴더 구조 생성 (`models/`, `data/`)
- 공식 샘플 `Run a model`, `Convert textures to tensors` 임포트
- md 파일 작성

### 확인한 사실
- `com.unity.ai.inference` 2.6.1은 Unity 6000.0 이상에서 동작
- 웹캠(`WebCamTexture`)은 Unity 내장, 엔진은 숫자 → 숫자만

### 막힌 부분
- HuggingFace 구조 파악에 시간이 걸림. 모델 파일은 HF, 예제 코드는 GitHub으로 출처가 나뉘어 있었음
- HF 모델 카드의 "Source Code" 링크가 Hand가 아닌 Pose 샘플을 가리킴. 공식 문서도 틀려서 혼동됨
- 공식 샘플 `Convert textures to tensors`는 화면에 아무것도 안 그림. 2일차에 자세히 확인할 예정

### 앞으로 할 일
- 웹캠 확인
- 공식 샘플 확인 및 움직임 추출
- 규칙 분류 시도