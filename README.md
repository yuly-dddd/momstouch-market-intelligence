# MOM'S TOUCH Market Intelligence

비공개 부서 공유용 시장·신제품 인텔리전스 대시보드입니다.

## 운영 범위
- 당사·경쟁사 신제품 검색 관심도
- 뉴스·YouTube 바이럴 신호
- 자사 VOC·허가된 리뷰의 제품별 긍정/부정 Aspect
- 출처·검색어·기간·수집시각 로그

## 자동 업데이트
GitHub Actions에서 매일 1회 `data.json`을 갱신하는 구조로 연결합니다.
API 키는 저장소의 Settings > Secrets and variables > Actions에 저장하며 코드에 직접 입력하지 않습니다.

## 현재 상태
현재 화면의 그래프·수치는 UI 검증용 예시값입니다. 네이버/뉴스/YouTube API 키와 자사 VOC 연결 후 실측값으로 교체합니다.
