# 손 제스처 마법 프로토타입

> ### 목표
> 웹캠으로 손 모양을 인식하여 게임 입력으로 사용하는 프로토타입을 만든다.

| 필요한 내용   | 어떻게 했는가 |
|----------|---|
| 추론 엔진    | `com.unity.ai.inference` 2.6.1 설치 |
| 앵커 데이터 | `Assets/HandFightTest/data/` 배치 |
| 모델       | `Assets/HandFightTest/models/` 배치 |
| 파이프라인 코드 | 없음 |

---

## HandFightTest 란?

가위 바위 보 손 모양을 카메라에 유지하면 해당 속성의 마법이 시전된다.

시전된 마법으로 적을 공격한다.

---

## 파이프라인

---

## 선택 & 실패!

---

## 결과

---

## 실행 방법
1. Unity 6000.3.21f1 이상으로 프로젝트를 연다
   (`com.unity.ai.inference` manifest에 포함됨)

---

## 다음 목표

---

## 모델과 데이터

BlazeHand
- 이용 범위 - 손바닥 검출기 + 손 랜드마커 + 앵커 데이터
- 원저작자 - Google Research ([MediaPipe](https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker))
- ONNX 변환·배포 - Unity Technologies
- 출처 - [unity/inference-engine-blaze-hand](https://huggingface.co/unity/inference-engine-blaze-hand)
- 라이선스 - [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0)
- 수정 여부 - 수정하지 않음

---

읽어주셔서 감사합니다.