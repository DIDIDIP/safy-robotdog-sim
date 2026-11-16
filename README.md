# SAFY 스마트 안전교육 로봇독 시뮬레이터

Hiwonder MechDog 기반 "Factory Quest" 프로젝트의 웹 3D 시뮬레이션 예시입니다.
로봇독이 공장 3개 구역(보호구 점검 · 품질 검사 · 비상 정지)을 돌며 안전교육 퀴즈를 내고,
틀린 구역은 기억해 두었다가 재교육합니다.

- 실행: `index.html`을 웹 서버로 열기 (GitHub Pages로 배포됨)
- 조작: 교육 시작 → 숫자키 1~3으로 답 선택, 장애물 놓기 / 시점 / 속도 / 화질 버튼
- 기술: Three.js r160, GTAO · Bloom · Bokeh DOF 후처리, HDR 환경 조명

## 에셋 출처
`assets/` 의 텍스처와 HDRI는 [Poly Haven](https://polyhaven.com) 의 CC0 에셋입니다.
(concrete_floor_worn_001, corrugated_iron_02, blue_metal_plate, metal_plate, concrete_wall_008, empty_warehouse_01)
