# 쿠팡 리뷰 운영 30초 간편 견적 랜딩

네이버·카카오·메타 광고 및 자체 유입용. **구글 광고 최종 URL로는 사용 금지** (리뷰 서비스는 구글 정책상 광고 불가).

- `index.html` — 견적 계산기(수량별 운영용역비 990~1,500원 + 배송비 2,000원/건) + Google Forms 접수
- `privacy.html` — 개인정보처리방침 (보관 1년)

## 접수 확인
Google Forms "쿠팡 간편 견적 접수" (kangjiho0722@gmail.com 소유)
https://docs.google.com/forms/d/1zA0OJX-SzO_pQBc2B9euNoxUrrExE1K8IEMXZklIfeo/edit#responses
- 시트 연결 / 이메일 알림은 응답 탭에서 설정
- `index.html`의 `FORM_FIELDS`는 폼 질문 entry ID — 질문 삭제·재생성 금지

## 단가 수정
`index.html` `unitPrice()` 함수와 01 비용 안내 섹션 표를 함께 수정.

## 프리필
`?qty=500&url=https://www.coupang.com/...` 로 수량/URL 미리 채움. `utm_*`, `n_*`, gclid, fbclid 보존.

## 배포
GitHub Pages (kangjiho0722-ai/coupang-quote). 단일 HTML이라 cafe24(babocompany.com)에 그대로 업로드해도 동작.
