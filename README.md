# 오늘 나는 몇 % 인간인가 🤔

> 매일 달라지는 15문항으로 오늘의 인간 지수를 측정해보세요.

<br>

[![바로 사용하기](https://img.shields.io/badge/🤔%20바로%20사용하기-몇%25%20인간인가-6c5ce7?style=for-the-badge)](https://kckworld.github.io/human-percentage)

<br>

---

## 🌈 어떻게 쓰나요?

```
1️⃣  오늘 해당되는 항목에 체크
        ↓
2️⃣  결과 보기 → 당신의 인간 지수 확인
        ↓
3️⃣  결과 이미지 저장 (인스타 스토리에 올려보세요)
```

---

## 📋 문항 구성

매일 날짜 기반으로 5개 카테고리에서 각 3개씩, 총 15개 항목이 랜덤 추출됩니다.  
**같은 날이면 누구나 같은 문항**이 나옵니다.

| 카테고리 | 예시 |
|--------|------|
| 😴 수면/게으름 | 알람을 3번 이상 껐다, 누운 채로 폰 1시간 이상 봤다 |
| 🍔 식습관 | 물을 500ml도 안 마셨다, 배달 음식을 시켰다 |
| 📱 디지털 중독 | 유튜브 쇼츠 30분 이상 봤다, 스크린 타임 5시간 초과 |
| 💪 건강/운동 | 햇빛 10분도 못 봤다, 하루종일 앉아있었다 |
| 👥 사회생활 | 연락 씹었다, 약속 취소했다 |

---

## 🐾 결과 캐릭터 (10단계)

| % 구간 | 캐릭터 |
|--------|--------|
| 0-9% | 🔌 충전 중인 스마트폰 |
| 10-19% | 🦥 나무늘보 |
| 20-29% | 🐼 야생 판다 |
| 30-39% | 🛋️ 소파와 합체된 존재 |
| 40-49% | 🐌 달팽이 |
| 50-59% | 🐧 펭귄 |
| 60-69% | 🐕 강아지 |
| 70-79% | 🌿 건강한 식물 |
| 80-89% | 🦁 사자 |
| 90-100% | 🧘 깨달은 인간 |

> 최다 체크 카테고리 + 요일 조합으로 멘트가 달라집니다.

---

## 💾 이미지 저장

- **아이폰 사파리**: 공유 시트를 통해 사진 앱에 직접 저장
- **안드로이드 / 기타**: PNG 파일 다운로드

---

<details>
<summary>🛠️ 기술 스택 / 로컬 실행</summary>

<br>

**기술 스택**

| 항목 | 내용 |
|------|------|
| 언어 | Vanilla HTML / CSS / JavaScript |
| 저장 | [html2canvas](https://html2canvas.hertzen.com/) CDN |
| 폰트 | Google Fonts (Black Han Sans, Gowun Dodum) |
| 배포 | GitHub Pages |

**로컬 실행**

서버 없이 파일 하나로 동작합니다.

```bash
git clone https://github.com/kckworld/human-percentage.git
cd human-percentage
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

**GitHub Pages 재배포**

```bash
git add .
git commit -m "update"
git push origin main
```

`main` 브랜치 루트에서 자동 배포됩니다. 배포까지 1-2분 소요.

</details>
