[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=40&pause=1000&color=00B863&height=150&lines=who's+Next+Door%3F)](https://git.io/typing-svg)

**neighbohood-H** — Vulnerability Research & Responsible Disclosure.

[![Team](https://img.shields.io/badge/team-neighborhood--H-purple)]()
[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-blue.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Public PoCs](https://img.shields.io/badge/public-1--day-green)]()

---

## Quick links
- **Private**: `0-DAY/` (internal vulnerability reports — access by request)
- **Public**: `1-DAY_Confirmation/` (https://github.com/neighborhood-H/1-DAY_Confirmation)

---

## What we publish
- 기술 리포트 (root-cause analysis, diff screenshots)
- PoC (격리 환경에서 실행 가능한 샘플 — 반드시 README의 safe-mode 지침을 따를 것)
- 재현 환경(예: QEMU chroot 스크립트)과 체크리스트

---

## Repo standards
Each repository follows:
1. `README.md` — summary, affected product/version, CVE (if assigned), exposure level (public/private).
2. `reports/` — markdown reports with diff & evidence.
3. `poc/` — PoC scripts with `README_SAFE.md` explaining isolation steps.
4. `emulation/` — qemu/chroot instructions & exported images (or download links).

---

## Disclosure & Responsible Use
- 모든 PoC는 **격리 환경**(air-gapped / VM / container)에서만 실행해야 합니다.  
- 무단 테스트 금지. 내부 정책에 따라 공개/비공개 여부 결정.

---

## Inspiration & references
- Trail of Bits — 연구 산출물·툴 문서화 사례(README·규칙집).  [oai_citation:5‡GitHub](https://github.com/trailofbits?utm_source=chatgpt.com)
                                                                                                            
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
