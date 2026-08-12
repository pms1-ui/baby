# 👶 빤짝이네 육아정보 책장

실제 경험 기반의 임신·출산·육아 정보를 모바일에서 보기 좋게 정리한 웹 프로젝트입니다.

## 프로젝트 소개

- 출산/육아 과정에서 직접 겪으며 알게 된 현실적인 팁들을 모아둔 사이트
- 모바일 퍼스트 반응형 디자인
- Seed Design(당근 디자인 시스템) 토큰 기반 UI
- 게이트 페이지(대문)에서 원하는 콘텐츠를 선택해 상세 페이지로 이동

## 구조

```
baby/
├── index.html                      # 게이트 페이지 (대문)
├── style.css                       # 공통 스타일 (Seed Design 토큰 기반)
├── README.md
├── ref/                            # 콘텐츠 원본 텍스트 (8개)
│   ├── 1.txt                       # 임신·출산·육아 지원금 총정리
│   ├── 2.txt                       # 출산 후 남편이 해야 할 일
│   ├── 3.txt                       # 어린이집 입소대기 가이드
│   ├── 4.txt                       # 제왕절개 산모 꿀아이템
│   ├── 5.txt                       # 임산부 119 안심콜
│   ├── 6.txt                       # 신생아 육아 총정리
│   ├── 7.txt                       # 신생아 외출 가이드
│   └── 8.txt                       # 아동수당 계좌 세팅
└── pages/                          # 콘텐츠 상세 페이지
    ├── daycare-tips.html           # 출생아기 어린이집 중간입소 꿀팁
    ├── support-money.html          # 2026 임신·출산·육아 지원금 총정리
    ├── husband-checklist.html      # 출산 후 남편이 해야 할 일 총정리
    ├── daycare-guide.html          # 어린이집 입소대기 완벽 가이드
    ├── csection-items.html         # 제왕절개 산모 병원·조리원 꿀아이템
    ├── 119-safety.html             # 임산부 119 안심콜 서비스
    ├── newborn-care.html           # 신생아 육아 총정리
    ├── newborn-outing.html         # 신생아 외출 가이드
    └── child-account.html          # 아동수당 계좌 세팅 실전 노트
```

## 콘텐츠 목록 (9개)

| # | 제목 | 파일 |
|---|------|------|
| 1 | 출생아기 어린이집 중간입소 꿀팁 | pages/daycare-tips.html |
| 2 | 2026 임신·출산·육아 지원금 총정리 | pages/support-money.html |
| 3 | 출산 후 남편이 해야 할 일 총정리 | pages/husband-checklist.html |
| 4 | 어린이집 입소대기 완벽 가이드 | pages/daycare-guide.html |
| 5 | 제왕절개 산모 병원·조리원 꿀아이템 | pages/csection-items.html |
| 6 | 임산부 119 안심콜 서비스 | pages/119-safety.html |
| 7 | 신생아 육아 총정리 | pages/newborn-care.html |
| 8 | 신생아 외출 가이드 | pages/newborn-outing.html |
| 9 | 아동수당 계좌 세팅 실전 노트 | pages/child-account.html |

## 기술 스택

- HTML5 / CSS3 / Vanilla JavaScript
- 모바일 퍼스트 반응형 디자인
- Seed Design 토큰 기반 CSS 변수 시스템 (당근 디자인 시스템 참조)
- Pretendard Variable 웹폰트
- 외부 프레임워크 없이 순수 구현

## 디자인 시스템

[Seed Design](https://github.com/daangn/seed-design) 토큰을 참조하여 구현:
- 브랜드 컬러: `#FF6F0F` (당근 오렌지)
- 배경 계층: basement(`#F7F8FA`) → surface(`#FFFFFF`)
- 상태 색상: danger / info / success / warning
- 폰트: Pretendard Variable
- 라운딩: 8px / 12px / 16px 단계

## 작업 규칙

- Git 원격 저장소: https://github.com/pms1-ui/baby.git
- 배포 주소: https://baby-ms.netlify.app/
- 작업 완료 시 자동 커밋 & 푸시 (묻지 않고 바로)
- 브랜치: main
- 콘텐츠 추가 시: ref/ 에 원본 텍스트 추가 → pages/ 에 HTML 페이지 생성 → index.html 에 버튼 추가
- 공구/광고 관련 내용은 절대 포함하지 않음
- 정보전달과 무관한 불필요한 내용 제외

## 사용 방법

`index.html`을 브라우저에서 열거나 GitHub Pages로 배포하여 사용할 수 있습니다.
