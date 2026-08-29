<div align="center">

[简体中文](README.md) · [English](README.en.md) · [日本語](README.ja.md) · [**한국어**](README.ko.md) · [Español](README.es.md)

# 🎨 만능 커버 Skill (Cover Studio)

### 올인원 멀티 플랫폼 썸네일 & 커버 워크플로우 · 9대 최고 오픈소스 커버 엔진 통합

크리에이터, 1인 개발자, 테크 블로거를 위한 오픈소스 AI Skill. 초기 설정에서 **명확히 구분된 플랫폼 규격 목록을 직접 체크**하고, 글 입력 시 **메인 헤드라인·서브 카피·태그 요소의 텍스트 계층을 먼저 확인**. 정렬된 문구를 바탕으로 **서로 다른 3가지 스타일 이미지를 즉시 생성·제시**합니다. 브랜드 시스템(Brand System) 고정은 물론, **Codex 환경 직접 생성**과 **Nano Banana (Google Flow 무료 플랫폼) 프롬프트 출력**의 듀얼 패스를 지원합니다.

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827?style=flat-square)
![9대 오픈소스 엔진](https://img.shields.io/badge/통합%20엔진-9대%20오픈소스%20Skill-0066ff?style=flat-square)
![개별 규격 선택](https://img.shields.io/badge/자율%20선택-3%3A4%20%7C%202.35%3A1%20%7C%2016%3A9%20%7C%205%3A2-f59e0b?style=flat-square)
![무료 생성 지원](https://img.shields.io/badge/생성%20방식-Codex%20직출%20%7C%20Nano%20Banana%20무료-8b5cf6?style=flat-square)
![MIT License](https://img.shields.io/badge/License-MIT-16a34a?style=flat-square)

<br/>

활용 분야: **샤오홍슈(小红书) 세로형 카드, 위챗 공식 계정 헤더, X/트위터 아티클 커버, 유튜브/치지직 썸네일, GitHub Social Preview**.

</div>

---

## 💡 왜 「만능 커버 Skill」을 만들었을까요?

콘텐츠 크리에이터, 1인 개발자, 테크 블로거라면 누구나 겪어본 **커버 이미지 제작의 고통**:

1. **🤯 도구 선택 피로감과 결정 장애**: GitHub에 수많은 개별 커버 스킬(사이버 긱, 샤오홍슈형, 위챗형, 빅테크 스타일 등)이 있지만, 매번 글을 쓸 때마다 어떤 도구를 골라야 할지 고민하고 테스트하는 데 많은 시간이 소요됩니다.
2. **📐 멀티 플랫폼 배포 시 '화면비 지옥'**: 샤오홍슈(3:4), 위챗(2.35:1), X/트위터(16:9 / 5:2), 유튜브(16:9) 등에 원소스를 멀티 유즈할 때, 단순 크롭(자르기)은 텍스트가 잘리거나 구도가 망가집니다.
3. **✍️ 텍스트 깨짐 및 정보 계층 부재**: AI 이미지 생성 시 문구가 뭉개지거나, 메인 헤드라인의 시각적 후킹이 부족한 문제.
4. **🎨 브랜드 일관성 부재**: 매번 제각각인 스타일로 인해 독자가 나의 고유한 브랜드를 인식하기 어렵습니다.

### 🎯 우리의 해법: 바퀴를 재발명하지 않고, 최고의 총괄 지휘자를 만들다!
> **10개의 개별 도구를 번거롭게 오갈 필요 없이, 콘텐츠·화면비·브랜드를 관통하는 하나의 통합 워크플로우를 제공합니다.**

- **9대 최고 오픈소스 엔진 통합**: 콘텐츠에 가장 적합한 3가지 서로 다른 스타일을 즉시 동시 생성.
- **텍스트 계층 선행 정렬**: 메인 헤드라인 + 서브 카피 + 태그 문구를 먼저 완벽히 맞춘 후 생성.
- **자율 선택 멀티 규격 일괄 납품**: 마음에 드는 스타일 선택 시 체크된 모든 플랫폼 규격에 맞춰 구도를 자동 재배치하여 일괄 출력.
- **원클릭 브랜드 VI 고정**: 나만의 시각적 아이덴티티를 표준화하여 지속적인 브랜드 인지도 확보.

---

## ✨ 핵심 기능

- ⚙️ **명확한 플랫폼 규격 조합 설정**: 상시 일괄 출력할 개별 플랫폼 비율(샤오홍슈 `3:4`, 위챗 `2.35:1`, X 포스트 `16:9`, X 아티클 `5:2`, 영상 `16:9`, GitHub `2:1`, `1:1` 정사각 등)을 사용자가 직접 체크하여 저장.
- ✍️ **텍스트 계층 선행 확인**: 메인 대형 텍스트, 서브 카피, 캡슐 태그 문구를 이미지 생성 전에 미리 완벽하게 정렬.
- 🖼️ **3가지 스타일 즉시 생성**: 정렬된 텍스트를 바탕으로 3가지 서로 다른 고품질 완성작/프롬프트를 즉시 제시.
- 🏷️ **원클릭 브랜드 시스템(Brand System) 고정**: 마음에 드는 스타일을 브랜드 표준으로 저장.
- 📐 **화면비에 맞춘 지능형 재배치**: 선택된 비율에 맞게 구도와 여백을 자동 재구성.
- 🚀 **Codex 직접 생성 ＋ Google Flow (Nano Banana) 무료 생성 듀얼 패스**.
- 🔄 **9대 오픈소스 커버 엔진 통합 라우팅**.

---

## 🛠️ 표준 워크플로우 전체 흐름

```mermaid
flowchart TD
    classDef default fill:#ffffff,stroke:#e2e8f0,stroke-width:1.5px,color:#1e293b,rx:8px,ry:8px;
    classDef startNode fill:#0f172a,stroke:#0f172a,stroke-width:2px,color:#ffffff,font-weight:bold,rx:20px,ry:20px;
    classDef stepNode fill:#ffffff,stroke:#cbd5e1,stroke-width:1.5px,color:#0f172a,rx:8px,ry:8px;
    classDef highlightNode fill:#eff6ff,stroke:#2563eb,stroke-width:2px,color:#1e40af,font-weight:bold,rx:8px,ry:8px;

    A0(["🚀 만능 커버 Skill 실행"]):::startNode
    --> A1["<b>0. 초기 환경 설정 (최초 1회)</b> ： 출력 모드 선택 (통합 브랜드 멀티 규격 / 단일 규격 커스텀)"]:::stepNode
    --> A2["<b>1. 텍스트 계층 선행 확인</b> ： 📌 메인 헤드라인 (≤8단어) ＋ 📝 서브 카피 ＋ 🏷️ 캡슐 태그"]:::highlightNode
    --> A3["<b>2. 3가지 스타일 즉시 생성</b> ： 【사이버 긱】·【볼드 헤드라인】·【심층 저널】3가지 결과물 즉시 제시"]:::stepNode
    --> A4["<b>3. 선택 ➔ 자율 규격 일괄 납품</b> ： Codex 직접 렌더링 또는 Google Flow (Nano Banana) 무료 생성"]:::stepNode
```

---

## 📚 4대 카테고리 · 9대 오픈소스 엔진 요약

```mermaid
flowchart LR
    classDef rootBox fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#ffffff,font-weight:bold,rx:8px,ry:8px;
    classDef cat1 fill:#eff6ff,stroke:#2563eb,stroke-width:2px,color:#1e3a8a,font-weight:bold,rx:6px,ry:6px;
    classDef cat2 fill:#fff1f2,stroke:#e11d48,stroke-width:2px,color:#881337,font-weight:bold,rx:6px,ry:6px;
    classDef cat3 fill:#ecfdf5,stroke:#059669,stroke-width:2px,color:#064e3b,font-weight:bold,rx:6px,ry:6px;
    classDef cat4 fill:#faf5ff,stroke:#9333ea,stroke-width:2px,color:#581c87,font-weight:bold,rx:6px,ry:6px;
    classDef leaf fill:#ffffff,stroke:#cbd5e1,stroke-width:1px,color:#334155,rx:4px,ry:4px;

    CS["🎨 Cover Studio<br/>만능 커버 스튜디오"]:::rootBox

    CS --> S1["🌐 크로스 플랫폼 전능 흐름"]:::cat1
    S1 --> E1["punk-cover<br/><i>사이버 긱 · 멀티 적응</i>"]:::leaf
    S1 --> E2["huashu-skills<br/><i>기업 발표회 · AI+HTML</i>"]:::leaf
    S1 --> E3["rn-cover-skill<br/><i>5:2 에디토리얼 · 엄격한 지식</i>"]:::leaf

    CS --> S2["📕 샤오홍슈 3:4 세로형 버즈 흐름"]:::cat2
    S2 --> E4["atutun-xhs-cover<br/><i>인물 등장 · 형광 볼드 · Emoji</i>"]:::leaf
    S2 --> E5["gbro-cover-design<br/><i>플랫 단색 · UI 카드 · 10종</i>"]:::leaf
    S2 --> E6["ponyo-cover-anchor-system<br/><i>감정 훅 · 찢은 종이 콜라주</i>"]:::leaf

    CS --> S3["🟢 위챗 2.35:1 전용 흐름"]:::cat3
    S3 --> E7["knowledge-media-cover<br/><i>아이보리 종이 · 1:1 안전</i>"]:::leaf
    S3 --> E8["wechatcover<br/><i>아트 디렉팅 · 폰트 정렬</i>"]:::leaf

    CS --> S4["🎬 영상/실습 도구 흐름"]:::cat4
    S4 --> E9["oil-cover<br/><i>애플 미니멀 · Mac 창 · 캡처</i>"]:::leaf
```

| 카테고리 | 엔진명 | GitHub 링크 | 주요 비주얼 특징 | 추천 사용처 |
|:---|:---|:---|:---|:---|
| **🌐 크로스 플랫폼** | `punk-cover` | [adrianpunk/Punk-Skill](https://github.com/adrianpunk/Punk-Skill) | 사이버 긱 / 모던 테크풍 | 3:4, 2.35:1, 16:9, 5:2 자동 적응 |
| **🌐 크로스 플랫폼** | `huashu-skills` | [alchaincyf/huashu-skills](https://github.com/alchaincyf/huashu-skills) | 기업 발표회 / 산업 디자인 | AI 생성 ＋ HTML 벡터 렌더링 |
| **🌐 크로스 플랫폼** | `rn-cover-skill` | [Pluviobyte/rnskill](https://github.com/Pluviobyte/rnskill) | 5:2 에디토리얼 인포그래픽 | 전문 기술 분석, 리서치 보고서 |
| **📕 세로형 3:4** | `atutun-xhs-cover` | [panggungunvibe/atutun-xhs-cover](https://github.com/panggungunvibe/atutun-xhs-cover) | 인물 등장 / 형광 볼드 텍스트 / 이모지 | 1인 브랜딩, 노하우 팁 공유 |
| **📕 세로형 3:4** | `gbro-cover-design` | [pyang5166/gbro-cover-design](https://github.com/pyang5166/gbro-cover-design) | 깔끔한 플랫 / UI 카드 구도 | 툴 리뷰, 소프트웨어 튜토리얼 |
| **📕 세로형 3:4** | `ponyo-cover-anchor-system` | [ponyodong2026/ponyo-cover-anchor-system](https://github.com/ponyodong2026/ponyo-cover-anchor-system) | 감정적 훅 / 찢어진 종이 콜라주 | 스토리텔링, 고클릭률 훅 |
| **🟢 가로형 2.35:1** | `knowledge-media-cover` | [aa1143/knowledge-media-cover](https://github.com/aa1143/knowledge-media-cover) | 아이보리 종이 질감 / 추상 메타포 | 심층 아티클 (1:1 크롭 완벽 대응) |
| **🟢 가로형 2.35:1** | `wechatcover` | [naplesblue/wechatcover](https://github.com/naplesblue/wechatcover) | 아트 디렉팅급 폰트 레이아웃 | 기업 뉴스레터, 브랜드 정체성 확립 |
| **🎬 영상 실습** | `oil-cover` | [oil-oil/oil-cover](https://github.com/oil-oil/oil-cover) | 애플 감성 미니멀 / Mac 창 캡처 | 코딩 녹화, AI 도구 튜토리얼 영상 |

---

## 📦 설치 및 실행

```bash
git clone https://github.com/kaomei/cover-studio.git
cd cover-studio

# Codex CLI
cp -R skills/cover-studio "${CODEX_HOME:-$HOME/.codex}/skills/cover-studio"

# Antigravity / Gemini CLI
cp -R skills/cover-studio ~/.gemini/config/skills/cover_studio
```

---

## ⚠️ 면책 조항

1. **오픈소스 통합 안내**: 본 프로젝트는 커버 디자인 라우팅 스킬이며, 통합된 9개 스킬의 모든 권리는 원저작자에게 있습니다.
2. **비공식 프로젝트**: 언급된 플랫폼 및 Google과 공식적인 상업적 제휴 관계가 없습니다.
3. **사용 범위**: 개인 학습, 연구 및 합법적인 콘텐츠 제작에 활용하시기 바랍니다.

---

## 🤝 기여 안내

새로운 오픈소스 커버 엔진 추천 및 프롬프트 레시피 PR을 환영합니다!

이 프로젝트가 마음에 드셨다면, **Star ⭐️를 눌러 kaomei(烤妹儿)를 응원해주세요!**

## 📄 라이선스

[MIT License](LICENSE) © 2026 [kaomei](https://github.com/kaomei)
