> 이 저장소는 원본 배포본 https://kkankong32-alt.github.io/omniscient-body-view/ 을 그대로 복제해 Vercel로 배포한 사본입니다. 원작자 표기와 제3자 라이선스 표기는 아래 원문 그대로 둡니다.
> 바꾼 점: 반 공유 링크가 원본 주소 대신 지금 접속한 주소로 만들어지도록 함, `vercel.json`(캐시 설정) 추가.

# 전지적 몸속시점 — 배포본

초등 과학 5-1 「우리 몸의 구조와 기능」 3D 관찰 프로그램의 심사·검수용 웹 배포본입니다.
이 저장소에는 빌드된 실행 파일만 있습니다(소스 코드·기획 문서·참고 자료는 포함하지 않음).

- 실행: https://kkankong32-alt.github.io/omniscient-body-view/
- 로그인 없음 · 학생 이름·학번을 받지 않음 · 기록은 각 기기의 브라우저에만 저장
- 3D 인체 모형: BodyParts3D, © The Database Center for Life Science, CC BY 4.0
- 제3자 자료·라이선스: [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md), [ATTRIBUTION.md](./ATTRIBUTION.md)

## 2026-11-08 결선 부스 업데이트
- 간: BodyParts3D 4.0 PART-OF 간 전체 모형(FMA7197)을 원래 좌표 그대로 덧붙임(삼각형 수만 줄임).
- 폐 외곽: BodyParts3D의 갈비뼈·가로막·심장 위치와 기관지 모양을 바탕으로 계산한 학습용 추정 윤곽(변경·가공한 자료).
- 3D 자료를 첫 화면용(약 4.8MB) → 근육 → 온몸 혈관 순서로 나눠 받도록 다시 담음(위치 오차 0.013mm 이하, 삼각형 수 동일).
- 새 자료 목록은 `atlas/atlas-v2.json`. 옛 `atlas/atlas.json`·`body-0~14.bin.gz`·옛 스크립트는 캐시에 남은 옛 페이지가 깨지지 않도록 함께 둠.
