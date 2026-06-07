# 원예장비 제조업체 총괄생산계획 대시보드

강의록의 총괄생산계획 예제를 바탕으로 만든 React + Vite + TypeScript 웹앱입니다.
월별 수요와 파라미터를 변경하면 선형계획 기반 최적화 모델로 새로운 총괄생산계획을 계산하고, KPI·표·차트·계획 검토 요약을 갱신합니다.

## 실행 방법

```bash
npm install
npm run dev
```

브라우저에서 터미널에 표시되는 로컬 주소로 접속합니다.

## 배포 방법, Vercel

Vercel에서 프로젝트를 연결한 뒤 기본 설정으로 배포하면 됩니다.

- Framework Preset: Vite
- Install Command: 비워두거나 `npm install`
- Build Command: `npm run build`
- Output Directory: `dist`

## 포함 기능

- 월별 수요 및 생산 파라미터 입력
- 선형계획 기반 총비용 최소화 계산
- KPI 카드
- 월별 생산계획 표
- 수요/생산량, 재고/부족재고, 인력, 비용 차트
- 계획 검토 요약
- 최적화 모델 설명
- 제약조건 확인표
- 시나리오 저장 및 비교
