# 실습과제 #1 : 영화 보드 완성판
- 이름 / 학번 : 장성민 / 2351044
- 사이트 주소 : [https://faraaaway.github.io/web-hw1/](https://faraaaway.github.io/web-hw1/)
- 사용한 API 1 : TMDB (포스터, 영화 정보)
- 사용한 API 2 : KOBIS 일별 박스오피스 (기준일 2026-10-20)
## 구현 항목 체크
- 1. CSS 변수 [✓]
- 2. 섹션 2개 [✓]
- 3. 카드 10장의 포스터 [✓]
- 4. 박스오피스 배지 [✓]
- 5. 6주차 효과 유지 [✓]
- 6. 보드 격자 [✓]
- 7. 헤더 [✓]
- 8. 히어로 [✓]
- 9. 상세 페이지 [✓]
- 10. 캡처 3장 [✓]
- 11. 푸터(두 쪽 모두) [✓]
- 12. 검증과 README [✓]
- 보너스 1. 로딩 스켈레톤 상태 UI (loading.png)
- 보너스 2. 다크 모드 또는 라이트 모드 (theme.png)
- 보너스 3. 반응형 이미지 (detail.html)
## 어려웠던 점 3가지와 해결
- root안에 변수에 오타가 있어 제대로 적용이 안됨. 오타 수정
- Step 2의 change new/up/down 내용일 이해를 못했었음. 이해 될 때까지 읽음
- 보너스 미션인 로딩 스켈레톤 상태 UI를 구현할 때 카드 애니메이션이 작동이 안됐었음. 원인은 .board안 .skeleton 때문으로 .card의 선택자를 nth-child에서 nth-type-of로 수정해 해결
## 참고한 자료 (교재 절, MDN 페이지 제목, 검색어)
- 웹개발기초_실급과제1_안내.pdf
- HTML <dl> 태그의 올바른 이해와 <dt>, <dd> (https://codingeverybody.kr/html-dl-%ED%83%9C%EA%B7%B8/)
- [CSS]css 가상 선택자 정리 및 비교 (nth-child, nth-of-type) (https://lalacode.tistory.com/6)
- HTML IMG의 srcset과 sizes 속성 ()https://www.heropy.dev/p/5Gl8hX)

