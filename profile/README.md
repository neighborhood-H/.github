[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=B82828&width=435&lines=who's+Next+Door)](https://git.io/typing-svg)

**who's NEXT-DOOR** — IoT / Network Vulnerability Research & Responsible Disclosure.

[![Team](https://img.shields.io/badge/team-NEXT--DOOR-blue)]()
[![License](https://img.shields.io/badge/license-MIT-lightgrey)]()
[![Public PoCs](https://img.shields.io/badge/public-1--day-green)]()

---

## Quick links
- **Private**: `0-DAY/` (internal vulnerability reports — access by request)
- **Public**: `1-DAY_Confirmation/` (research reports, PoC, emulation guides)
- `templates/` — 문서 템플릿(보고서·README)
- `tooling/` — 분석 스크립트, 자동화

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
5. `SECURITY.md` & `CONTRIBUTING.md`.

---

## Disclosure & Responsible Use
- 모든 PoC는 **격리 환경**(air-gapped / VM / container)에서만 실행해야 합니다.  
- 무단 테스트 금지. 내부 정책에 따라 공개/비공개 여부 결정.

---

## Inspiration & references
- Google Project Zero — public vulnerability writeups & tooling.  [oai_citation:3‡GitHub](https://github.com/googleprojectzero?utm_source=chatgpt.com)  
- ProjectDiscovery — 템플릿화된 대규모 커뮤니티 리포지토리(구성·기여 모델 참고).  [oai_citation:4‡GitHub](https://github.com/projectdiscovery/nuclei-templates?utm_source=chatgpt.com)  
- Trail of Bits — 연구 산출물·툴 문서화 사례(README·규칙집).  [oai_citation:5‡GitHub](https://github.com/trailofbits?utm_source=chatgpt.com)
                                                                                                            
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
