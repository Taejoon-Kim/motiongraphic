# SDV Architecture — 30s Motion Graphic

테슬라(Model 3) 구조를 기준으로 SDV(Software Defined Vehicle)의 계층 구조를 설명하는 30초 16:9 모션 그래픽입니다.

## 재생

- **웹에서 보기**: https://taejoon-kim.github.io/motiongraphic/
- **HTML**: `sdv.html`을 브라우저로 열면 바로 반복 재생됩니다. 외부 의존성이 없는 단일 파일입니다.
  - `Space` 또는 화면 클릭: 재생/일시정지
  - `←` / `→`: 3초 뒤로/앞으로 이동
  - `F`: 전체화면
  - 하단 바를 클릭하거나 드래그해서 원하는 시점으로 이동
- **영상**: `SDV_architecture_30s.mp4` (1920×1080, 30fps, H.264)

## 구성

| 시간 | 장면 |
|---|---|
| 0–3s | 인트로: SOFTWARE / DEFINED / VEHICLE 키네틱 타이포 |
| 3–7s | 차량 탑뷰 라인 드로잉 |
| 7–25s | 6개 계층 순차 등장: 하드웨어·센서 → 존 E/E → 중앙 컴퓨팅 → OS·미들웨어 → 애플리케이션 → 클라우드·OTA |
| 25–30s | 아웃트로: 계층 스택 + "CODE IS THE NEW HORSEPOWER" |

차량 일러스트는 Canvas로 직접 그린 벡터이며, 외부 이미지를 쓰지 않았습니다.
