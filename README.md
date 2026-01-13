<div align="center">

<!-- 🎨 메인 애니메이션 헤더 -->
<svg width="100%" height="220" viewBox="0 0 400 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#764ba2;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#f093fb;stop-opacity:1" />
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- 배경 -->
  <rect width="400" height="220" fill="url(#grad1)" opacity="0.08" rx="10"/>
  
  <!-- 움직이는 원들 -->
  <circle cx="60" cy="50" r="18" fill="#667eea" opacity="0.7" filter="url(#glow)">
    <animate attributeName="cy" values="50;110;50" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="r" values="18;25;18" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="200" cy="110" r="18" fill="#764ba2" opacity="0.7" filter="url(#glow)">
    <animate attributeName="cy" values="110;50;110" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="r" values="18;25;18" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="340" cy="50" r="18" fill="#f093fb" opacity="0.7" filter="url(#glow)">
    <animate attributeName="cy" values="50;110;50" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="r" values="18;25;18" dur="3s" repeatCount="indefinite"/>
  </circle>
  
  <!-- 중앙 회전 요소 -->
  <g>
    <circle cx="200" cy="110" r="38" fill="none" stroke="#764ba2" stroke-width="2.5" opacity="0.8">
      <animateTransform attributeName="transform" type="rotate" 
        values="0 200 110; 360 200 110" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="200" cy="110" r="55" fill="none" stroke="#667eea" stroke-width="1.5" opacity="0.4">
      <animateTransform attributeName="transform" type="rotate" 
        values="360 200 110; 0 200 110" dur="7s" repeatCount="indefinite"/>
    </circle>
  </g>
  
  <!-- 반짝이 효과 (별) -->
  <circle cx="120" cy="160" r="4" fill="#ffd700" filter="url(#glow)">
    <animate attributeName="opacity" values="0;1;0" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="280" cy="140" r="4" fill="#ffd700" filter="url(#glow)">
    <animate attributeName="opacity" values="0;1;0" dur="2s" begin="0.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="80" cy="180" r="4" fill="#ffd700" filter="url(#glow)">
    <animate attributeName="opacity" values="0;1;0" dur="1.8s" begin="1s" repeatCount="indefinite"/>
  </circle>
  <circle cx="320" cy="170" r="4" fill="#ffd700" filter="url(#glow)">
    <animate attributeName="opacity" values="0;1;0" dur="2.2s" begin="0.3s" repeatCount="indefinite"/>
  </circle>
  
  <!-- 텍스트 -->
  <text x="200" y="210" font-size="16" font-weight="bold" fill="#667eea" text-anchor="middle" opacity="0.9">
    ✨ 혁신적인 전자공학자 포트폴리오 ✨
  </text>
</svg>

# 👋 안녕하세요, 전자공학자입니다!

![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)
![Last Update](https://img.shields.io/badge/Last%20Update-Jan%202026-blue?style=flat-square)
![Version](https://img.shields.io/badge/Version-3.0-brightgreen?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Embedded%20Systems-ff69b4?style=flat-square)

**혁신적인 전자 제품을 만드는 열정적인 4학년입니다** 🚀

</div>

---

<!-- 🎨 구분선 애니메이션 1 -->
<div align="center">
<svg width="100%" height="60" viewBox="0 0 400 60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:0" />
      <stop offset="50%" style="stop-color:#764ba2;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#667eea;stop-opacity:0" />
    </linearGradient>
  </defs>
  <line x1="0" y1="20" x2="400" y2="20" stroke="url(#lineGrad)" stroke-width="2" opacity="0.6">
    <animate attributeName="stroke-width" values="2;4;2" dur="2s" repeatCount="indefinite"/>
  </line>
  <circle cx="200" cy="20" r="8" fill="none" stroke="#764ba2" stroke-width="1.5" opacity="0.7">
    <animate attributeName="r" values="8;12;8" dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>
</div>

## 🎯 프로필

<table align="center">
<tr>
<td width="50%"><b>🏫 학교</b><br>전자공학부 4학년</td>
<td width="50%"><b>🎓 전공</b><br>전자공학</td>
</tr>
<tr>
<td><b>🌍 관심분야</b><br>마이크로컨트롤러, FPGA, IoT</td>
<td><b>💡 목표</b><br>혁신적인 제품 개발</td>
</tr>
</table>

---

<!-- 🎨 구분선 애니메이션 2 -->
<div align="center">
<svg width="100%" height="60" viewBox="0 0 400 60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="lineGrad2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#f093fb;stop-opacity:0" />
      <stop offset="50%" style="stop-color:#667eea;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#f093fb;stop-opacity:0" />
    </linearGradient>
  </defs>
  <line x1="0" y1="20" x2="400" y2="20" stroke="url(#lineGrad2)" stroke-width="2" opacity="0.6">
    <animate attributeName="stroke-width" values="2;4;2" dur="2.5s" repeatCount="indefinite"/>
  </line>
  <circle cx="200" cy="20" r="8" fill="none" stroke="#667eea" stroke-width="1.5" opacity="0.7">
    <animate attributeName="r" values="8;12;8" dur="2.5s" repeatCount="indefinite"/>
  </circle>
</svg>
</div>

## 🛠️ 기술 스택

<div align="center">

### 💻 프로그래밍 언어
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)

<br/>

### 🔌 하드웨어 & 개발도구
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-4B8BBE?style=for-the-badge&logo=v&logoColor=white)
![FPGA](https://img.shields.io/badge/FPGA-FF6B6B?style=for-the-badge)
![PCB Design](https://img.shields.io/badge/PCB%20Design-0071B5?style=for-the-badge&logo=autodesk&logoColor=white)

<br/>

### 🌐 주요 기술 & 개념
![Embedded Systems](https://img.shields.io/badge/Embedded%20Systems-FF6B6B?style=for-the-badge)
![IoT](https://img.shields.io/badge/IoT-00BFFF?style=for-the-badge)
![Microcontroller](https://img.shields.io/badge/Microcontroller-4A90E2?style=for-the-badge)
![Circuit Design](https://img.shields.io/badge/Circuit%20Design-FFB6C1?style=for-the-badge)

</div>

---

<!-- 🎨 구분선 애니메이션 3 -->
<div align="center">
<svg width="100%" height="60" viewBox="0 0 400 60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="lineGrad3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#764ba2;stop-opacity:0" />
      <stop offset="50%" style="stop-color:#f093fb;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#764ba2;stop-opacity:0" />
    </linearGradient>
  </defs>
  <line x1="0" y1="20" x2="400" y2="20" stroke="url(#lineGrad3)" stroke-width="2" opacity="0.6">
    <animate attributeName="stroke-width" values="2;4;2" dur="2.2s" repeatCount="indefinite"/>
  </line>
  <circle cx="200" cy="20" r="8" fill="none" stroke="#f093fb" stroke-width="1.5" opacity="0.7">
    <animate attributeName="r" values="8;12;8" dur="2.2s" repeatCount="indefinite"/>
  </circle>
</svg>
</div>

## 📊 기술 숙련도

<div align="center">

| 기술 | 숙련도 | 경험 | 진행도 |
|:---:|:----:|:---:|:------:|
| **C/C++** | ⭐⭐⭐⭐⭐ | 2년 | ![](https://progress-bar.dev/100/?color=667eea&title=Expert) |
| **Arduino** | ⭐⭐⭐⭐⭐ | 3년 | ![](https://progress-bar.dev/100/?color=764ba2&title=Expert) |
| **FPGA/Verilog** | ⭐⭐⭐⭐ | 1년 | ![](https://progress-bar.dev/85/?color=f093fb&title=Advanced) |
| **PCB Design** | ⭐⭐⭐⭐ | 1.5년 | ![](https://progress-bar.dev/80/?color=667eea&title=Advanced) |
| **Python** | ⭐⭐⭐⭐⭐ | 2년 | ![](https://progress-bar.dev/95/?color=764ba2&title=Expert) |
| **IoT Systems** | ⭐⭐⭐⭐ | 1.5년 | ![](https://progress-bar.dev/85/?color=f093fb&title=Advanced) |

</div>

---

<!-- 🎨 구분선 애니메이션 4 -->
<div align="center">
<svg width="100%" height="60" viewBox="0 0 400 60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="lineGrad4" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#f093fb;stop-opacity:0" />
      <stop offset="50%" style="stop-color:#667eea;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#f093fb;stop-opacity:0" />
    </linearGradient>
  </defs>
  <line x1="0" y1="20" x2="400" y2="20" stroke="url(#lineGrad4)" stroke-width="2" opacity="0.6">
    <animate attributeName="stroke-width" values="2;4;2" dur="2s" repeatCount="indefinite"/>
  </line>
  <circle cx="200" cy="20" r="8" fill="none" stroke="#667eea" stroke-width="1.5" opacity="0.7">
    <animate attributeName="r" values="8;12;8" dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>
</div>

## 🎓 핵심 역량

<div align="center">

| 🔧 **기술 역량** | 💼 **소프트 스킬** |
|---|---|
| ✅ 마이크로컨트롤러 프로그래밍 | ✅ 문제 해결 능력 |
| ✅ FPGA 설계 및 구현 | ✅ 팀 협업 경험 |
| ✅ 회로 설계 및 PCB 레이아웃 | ✅ 프로젝트 관리 |
| ✅ IoT 시스템 개발 | ✅ 빠른 학습 능력 |
| ✅ 임베디드 시스템 개발 | ✅ 창의적 사고 |
| ✅ 펌웨어 최적화 | ✅ 커뮤니케이션 스킬 |

</div>

---

## 🎨 주요 프로젝트

### 📌 프로젝트 1️⃣ - 스마트 홈 IoT 시스템
<div align="center">

> 🏠 Arduino 기반 센서 네트워크를 활용한 IoT 홈 오토메이션

**핵심 기술:**
- 마이크로컨트롤러 프로그래밍 (ATmega328P)
- 무선 통신 (Wi-Fi, BLE)
- 센서 인터페이싱 (온습도, 조도, 모션)
- 클라우드 연동

**성과:** ✨ 에너지 절감 40% 달성

</div>

---

### 📌 프로젝트 2️⃣ - FPGA 기반 신호처리 시스템
<div align="center">

> ⚡ Verilog를 이용한 실시간 신호처리 회로 설계

**핵심 기술:**
- FPGA 보드 (Xilinx Basys 3)
- Verilog HDL 설계
- 고속 데이터 처리
- 신호 필터링 및 변환

**성과:** 🎯 처리 속도 10배 향상

</div>

---

### 📌 프로젝트 3️⃣ - PCB 설계 및 제작
<div align="center">

> 🔧 커스텀 센서 보드 완전 설계부터 제작까지

**핵심 기술:**
- Altium Designer를 이용한 회로도 설계
- PCB 레이아웃 최적화
- 부품 배치 및 신호 무결성
- 프로토타입 제작 및 테스트

**성과:** 📦 5개 보드 성공적으로 제작

</div>

---

<!-- 🎨 구분선 애니메이션 5 -->
<div align="center">
<svg width="100%" height="60" viewBox="0 0 400 60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="lineGrad5" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#764ba2;stop-opacity:0" />
      <stop offset="50%" style="stop-color:#f093fb;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#764ba2;stop-opacity:0" />
    </linearGradient>
  </defs>
  <line x1="0" y1="20" x2="400" y2="20" stroke="url(#lineGrad5)" stroke-width="2" opacity="0.6">
    <animate attributeName="stroke-width" values="2;4;2" dur="2.5s" repeatCount="indefinite"/>
  </line>
  <circle cx="200" cy="20" r="8" fill="none" stroke="#764ba2" stroke-width="1.5" opacity="0.7">
    <animate attributeName="r" values="8;12;8" dur="2.5s" repeatCount="indefinite"/>
  </circle>
</svg>
</div>

## 📚 학습 경로

<div align="center">

```
┌──────────────────────────────────────────────────────┐
│  전자공학 기초                                        │
│  ├─ 회로이론 & 신호처리 ⭐⭐⭐⭐⭐                   │
│  ├─ 디지털 로직 ⭐⭐⭐⭐⭐                         │
│  └─ 마이크로프로세서 ⭐⭐⭐⭐⭐                     │
│                                                      │
│  임베디드 시스템 심화                                 │
│  ├─ 마이크로컨트롤러 프로그래밍 ⭐⭐⭐⭐⭐         │
│  ├─ RTOS & 펌웨어 개발 ⭐⭐⭐⭐                   │
│  └─ IoT 통신 프로토콜 ⭐⭐⭐⭐⭐                   │
│                                                      │
│  FPGA & HDL 설계                                    │
│  ├─ Verilog HDL ⭐⭐⭐⭐                         │
│  ├─ 디지털 회로 설계 ⭐⭐⭐⭐                      │
│  └─ FPGA 최적화 ⭐⭐⭐⭐                          │
│                                                      │
│  PCB & 회로설계                                     │
│  ├─ 회로도 설계 ⭐⭐⭐⭐⭐                        │
│  ├─ PCB 레이아웃 ⭐⭐⭐⭐                         │
│  └─ 신호무결성 ⭐⭐⭐                            │
└──────────────────────────────────────────────────────┘
```

</div>

---

<!-- 🎨 구분선 애니메이션 6 -->
<div align="center">
<svg width="100%" height="60" viewBox="0 0 400 60" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="lineGrad6" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:0" />
      <stop offset="50%" style="stop-color:#764ba2;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#667eea;stop-opacity:0" />
    </linearGradient>
  </defs>
  <line x1="0" y1="20" x2="400" y2="20" stroke="url(#lineGrad6)" stroke-width="2" opacity="0.6">
    <animate attributeName="stroke-width" values="2;4;2" dur="2.2s" repeatCount="indefinite"/>
  </line>
  <circle cx="200" cy="20" r="8" fill="none" stroke="#f093fb" stroke-width="1.5" opacity="0.7">
    <animate attributeName="r" values="8;12;8" dur="2.2s" repeatCount="indefinite"/>
  </circle>
</svg>
</div>

## 🚀 빠른 시작

### 📌 이 프로젝트 확인

README.md 파일을 GitHub에서 보시면 :
- 📊 동적 SVG 애니메이션 확인 가능
- 🎨 기술 숙련도 시각화
- 📈 프로젝트 성과 확인

### 🌐 GitHub에서 보기

이 README는 마크다운 형식의 포트폴리오입니다.
GitHub에서 전체 내용을 한눈에 확인할 수 있습니다!

---

## ⚙️ README 커스터마이징 가이드

<details>
<summary><b>1️⃣ 개인정보 업데이트</b></summary>

다음 부분을 찾아 수정하세요:

- 이메일: `your@email.com`
- GitHub: `[GitHub Profile](#)`
- LinkedIn: `[LinkedIn](#)`

본인의 실제 정보로 변경하세요.

</details>

<details>
<summary><b>2️⃣ 기술 스택 수정</b></summary>

기술 스택 섹션에서 다음을 수정하세요:

- 프로그래밍 언어 추가/제거
- 하드웨어 & 개발도구 업데이트
- 주요 기술 & 개념 수정

</details>

<details>
<summary><b>3️⃣ 프로젝트 정보 업데이트</b></summary>

프로젝트 섹션에서 다음을 수정하세요:

- 프로젝트 제목 변경
- 핵심 기술 업데이트
- 성과 수치 수정

</details>

---

## 📁 파일 구조

```
📦 lee6147/
├─ 📄 README.md          # 마크다운 포트폴리오 (현재 파일) ⭐
├─ 📂 projects/          # (향후 추가)
│  ├─ iot-system.md
│  ├─ fpga-design.md
│  └─ pcb-board.md
└─ 📂 assets/            # (향후 추가)
   ├─ images/
   └─ certificates/
```

---

---

<!-- 🎨 구분선 애니메이션 최종 -->
<div align="center">
<svg width="100%" height="80" viewBox="0 0 400 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="finalGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#764ba2;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#f093fb;stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect x="50" y="20" width="300" height="40" fill="none" stroke="url(#finalGrad)" stroke-width="2" rx="10" opacity="0.8">
    <animate attributeName="stroke-width" values="2;3;2" dur="1.5s" repeatCount="indefinite"/>
  </rect>
  <text x="200" y="47" font-size="14" font-weight="bold" fill="url(#finalGrad)" text-anchor="middle">
    🌟 함께 성장하는 엔지니어입니다 🌟
  </text>
</svg>
</div>

## 🔗 연결

<div align="center">

| 📧 **이메일** | 💼 **GitHub** | 🔗 **LinkedIn** |
|---|---|---|
| [your@email.com](mailto:your@email.com) | [@username](https://github.com) | [@profile](https://linkedin.com) |

<br>

**마지막 업데이트:** January 13, 2026 ✨

</div>

---

## 📝 라이선스

<div align="center">

![License](https://img.shields.io/badge/License-Personal%20Portfolio-blueviolet?style=flat-square)

이 프로젝트는 개인 포트폴리오 프로젝트입니다.
<div align="center">

```
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃                                           ┃
┃  ✅ 2026.01.12: 시각 효과 추가             ┃
┃     • 진행도 바 시각화                   ┃
┃     • 프로젝트 박스 디자인               ┃
┃     • 배치 별 구분 개선                  ┃
┃                                           ┃
┃  ✅ 2026.01.12: README.md 완전 개선       ┃
┃     • 마크다운 형식 오류 해결            ┃
┃     • 기술 숙련도 테이블 추가            ┃
┃                                           ┃
┃  ✅ 2026.01.12: intro.html 완성           ┃
┃     • 애니메이션 효과 적용              ┃
┃     • Glassmorphism 디자인                ┃
┃                                           ┃
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
```

</div>
---

## 🎯 최근 업데이트

- ✅ **2026.01.12**: README.md 마크다운 형식 완전 수정 및 개선
- ✅ **2026.01.12**: intro.html 애니메이션 효과 추가
- ✅ **2026.01.12**: 기술 숙련도 테이블 추가

---

<div align="center">

### ✨ 함께 멋진 기술을 만들어가요! ✨

**마지막 수정**: 2026년 1월 12일 ⏰

**👇 intro.html을 열어서 멋진 포트폴리오를 확인해보세요! 👇**

</div>
