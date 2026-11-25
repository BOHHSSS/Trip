# Merry Fukuoka! 🎄

2026.12.18–12.21 후쿠오카 3박 4일 가족·커플 여행 일정 공유 웹사이트.

- GitHub: https://github.com/BOHHSSS/Trip
- 배포: https://bohhsss.github.io/Trip/fukuoka/
- 진입 파일: fukuoka/index.html (HTML/CSS/JS 단일 정적 파일)
- 인수인계 기준: 2026-11-25, index.html blob 405e8536f630e16f3eead848f8531f7996d5e8e3

## Codex에서 시작하기
BOHHSSS/Trip 저장소를 열고 fukuoka/AGENTS.md, README.md, DESIGN.md, TRIP_PLAN.md, TODO.md를 읽은 뒤 현재 index.html을 확인한다. 가장 최근 미완료 요청은 Day 헤더 배경 이미지 통합(TODO 첫 항목).
로컬에서는 저장소 루트에서 `python -m http.server 8000` 실행 후 http://localhost:8000/fukuoka/ 접속. 자동 배포 설정은 저장소에서 확인한다.

## 주요 기능
일정/맛집/준비 하단 내비, 가족·커플 전환, 날짜별 스크롤 스파이, 항공·숙소 접기, Google Maps 지도/검색, 투어 비교, 맛집 출처·카테고리·검색·평점·예약 필터, 체크리스트 저장.
현재 공유 제목 및 설명을 유지하며 별도 OG 이미지 지정은 원복한 상태.
현재 소스 기준 맛집 44개. 기존 추천 탭은 삭제되었으나 해당 식당은 전체 목록에 유지한다.
이 문서는 전체 채팅 원문이 아닌 현재 코드 및 대화 요구사항을 정리한 인수인계 기록이다.
