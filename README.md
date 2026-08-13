# Techno-economics of Ethane Cracker

에탄 크래커 기술경제성 평가 도구. 자립형 단일 HTML, 외부 의존 없음.

**→ [robin-yk.github.io/Techno-economics](https://robin-yk.github.io/Techno-economics/)**

자유도는 반응기에만 있습니다. 코일 출구온도 · 체류시간 · 희석비 · 규모 · 가열 효율을
움직이면 후단이 순차적으로 다시 풀립니다. 후단 세 탑은 제품 규격(C₂H₄ 99.9 mol%,
콜드박스 회수율 99.5%)이 고정이라 **환류비는 입력이 아니라 결과로 나옵니다.**

| 탭 | 내용 |
|---|---|
| plant | 공정 흐름도 · 원가 표 |
| cost ladder | 화학량론 바닥에서 최종 원가까지의 누적 |
| CH vs JH | 연소 가열 vs 주울 가열 · 손익분기 전기 가격 |
| sensitivity | ±10% 토네이도 |
| balances | 탄소 · 수소 · 질량 · 에너지 수지 잔차, 고정 스펙 |

스크리닝 도구 · AACE Class 5 · ±40%. 절대값이 아니라 누적 구조를 보는 용도입니다.

---

`ethane-cracker-tea-lab.html`은 Mittal, Kwak et al., *Chem. Eng. J.* 523 (2025) 168251의
TEA를 재구성하려던 도구입니다. 논문이 공개한 정보만으로는 재현이 불가능하다는 결론이 나서
개발을 중단했고, 사이트에서 링크하지 않습니다. 감사 결과는
[`TEA_tool_selfcheck.md`](TEA_tool_selfcheck.md)에 남아 있습니다.
