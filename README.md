# kr-speedcam-public-data

전국 무인교통단속카메라 위치 데이터 (원본, 무가공).

- **출처:** 공공데이터포털 「전국무인교통단속카메라표준데이터」 — https://www.data.go.kr/data/15028200/standard.do
- **라이선스:** 공공누리 제1유형 (출처표시) — KOGL Type 1
- **수집일:** 2026-10-15 (데이터기준일자 최신값 2026-09-13), 43,764건, 23개 컬럼

## Files
| File | Encoding | Note |
|---|---|---|
| `전국무인교통단속카메라표준데이터.csv` | EUC-KR | 포털 CSV 다운로드 버튼과 동일한 방식으로 생성 (포털 `download/standard.json` → 포털 JS와 동일한 CSV 직렬화). 원본에 있던 U+FFFD 1자는 EUC-KR로 표현 불가하여 `?`로 대체됨 |
| `kr_speedcam_utf8.csv` | UTF-8 (no BOM) | 위 파일과 내용 동일, 인코딩만 UTF-8 |
| `columns.json` | UTF-8 | 포털 컬럼 정의 원본 응답 |

값은 수정·정제·필터링하지 않았습니다 (예: 단속구분 값에 `1`/`01`/`1+2`/`01+02` 등 기관별 표기가 혼재).

Stable URLs: GitHub release `data-20261015` assets.

This repository contains only public government data; it contains no third-party processed datasets.
