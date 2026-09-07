# 감자·하람 동화도서관 📚

뱃속에서 자라는 우리 아들 하람이의 이야기들.

## 사이트 주소
`https://[계정명].github.io/gamja-haram`

---

## 📁 폴더 구조
```
gamja-haram/
├── index.html          ← 메인 도서관 페이지
├── stories/            ← 동화 HTML 파일들
│   ├── gamja_gratitude_dr_kim.html
│   ├── gamja_morning_routine.html
│   └── ... (동화 파일들)
└── README.md
```

---

## ✨ 새 동화 추가하는 법

1. 새 동화 HTML 파일을 `stories/` 폴더에 업로드
2. `index.html` 파일을 열어서 `STORIES` 배열에 항목 하나 추가:

```javascript
{
  num:"15",                                    // 번호
  file:"stories/새파일이름.html",              // 파일 경로
  title:"새 동화 제목",                        // 제목
  date:"날짜",                                 // 날짜
  pages:6,                                     // 페이지 수
  tags:["일상"],                               // 태그: 감사/태동/여행/음악/일상/성장
  desc:"짧은 설명 한두 줄.",                    // 설명
  color:"#0c1830",                             // 썸네일 배경색 (어두운색 or 밝은색)
  emoji:"🌿"                                   // 썸네일 이모지
},
```

3. 저장하고 GitHub에 push → 자동 반영!

---

## 🏷️ 태그 종류
- `감사` — 감사 이야기
- `태동` — 태동·성장 관찰
- `여행` — 여행 기록
- `음악` — 음악·공연
- `일상` — 일상 일기
- `성장` — 하람이 성장 기록

---

made with 💙 for 하람 · 2026
