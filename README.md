# Samsung Electronics Equity Research

삼성전자의 반도체(DS), DX, SDC, Harman을 분리해 읽는 기업분석 포트폴리오입니다. 기준일은 2026-10-10이며, 단위는 KRW bn과 원/주입니다.

## 한 줄 결론

SOTP 기준 가치는 **361,786원**입니다. 메모리 2027E EBIT 25조원을 HBM·서버 DRAM·클라이언트/모바일 DRAM·NAND·기타로 나누고, 각 제품군에 9.0x·7.0x·4.5x·3.0x·2.5x를 적용했습니다. HBM에는 고객 인증, 공급 제약, 플랫폼 내 비중을 반영합니다. NAND와 기타 메모리에는 할인 폭을 크게 둡니다. 이 구분으로 메모리 유효 EV/EBIT은 6.2x가 됩니다.

DCF는 대규모 CAPEX와 운전자본을 확인하고, RIM은 메모리 초과 ROE의 하방을 보여줍니다. `Segment PER`는 HBM·서버 DRAM, 범용 메모리, DX·SDC·Harman, Foundry/S.LSI의 정상화 EPS에 개별 PER를 적용한 교차검증입니다.

## 기준 실적

- 2Q26: 매출 171.5조원, 영업이익 89.5조원, 순이익 71.6조원
- 2Q26 DS: 매출 127.5조원, 영업이익 89.2조원
- 3Q26 잠정치: 매출 195.0조원, 영업이익 107.4조원. 세부 사업부와 순이익은 2026-10-29 확정 공시 후 갱신합니다.

## 파일 안내

- `model/Samsung_Electronics_equity_research.xlsx`: 실제치, 메모리 프리미엄 빌드, 부문별 SOTP, DCF, RIM, Segment PER, 갱신 점검표
- `research/INVESTMENT_CASE.md`: 투자 논리와 업데이트 조건
- `research/PEER_SELECTION_SCORECARD.md`: peer 역할·포함 게이트·정규화 원칙
- `research/MEMORY_PREMIUM_FRAMEWORK.md`: 메모리 제품별 scenario multiple과 증거/반증 게이트
- `research/COMPANY_SPECIFIC_FRAMEWORK.md`: 사업부별 운영·valuation 드라이버
- `research/VALUATION_VINTAGE_POLICY.md`: 실적/주가/peer 추정 vintage와 갱신 순서
- `report/FINAL_REPORT.md`: GitHub에서 읽는 최종 보고서
- [`report/Samsung_Electronics_equity_research_report.pdf`](report/Samsung_Electronics_equity_research_report.pdf): 기존 제출용 PDF 보고서
- [`report/METHODOLOGY_APPENDIX.md`](report/METHODOLOGY_APPENDIX.md): peer 선정·vintage·세그먼트 프리미엄의 상세 보완
- `report/Samsung_Electronics_equity_research_report.docx`: PDF 원본 편집 파일
- `data/processed/2026-10-10_actuals_and_assumptions.csv`: 입력 데이터와 출처

## 세그먼트별 분석 기준

| 이익 풀 | 주 분석 기준 | valuation 역할 | peer 사용 한계 |
|---|---|---|---|
| HBM / Server DRAM | 세대별 인증, 수율, 고객 분산, ASP·믹스, CAPEX 후 현금전환 | 제품별 정상화 EV/EBIT 시나리오 | SK하이닉스·Micron은 operating anchor이며 이익률·믹스를 그대로 대입하지 않음 |
| Client/mobile DRAM / NAND | OEM 재고, 비트 공급, ASP·가동률, eSSD 믹스, 사이클 정상화 | 낮은 cycle-normalized EV/EBIT 범위 | HBM 성장 배수를 재사용하지 않음 |
| Foundry / S.LSI | 노드 수율·가동률·외부 고객 양산·손실·CAPEX 회수 | 적자 시 PER 대신 상태별 SOTP | TSMC는 공정·가동률 benchmark이며 배수 plug-in이 아님 |
| DX (MX / VD·DA) | 제품 믹스·sell-through·채널 재고·프로모션·정상 마진 | 정상화 EBIT/EPS | Apple·Xiaomi는 수요/가격 참고일 뿐 직접 peer 아님 |
| SDC | OLED 가동률·고객집중·IT/차량 OLED 수율과 투자수익 | 정상화 EBIT/ROIC | LG디스플레이는 업황 참고 |
| Harman | 수주잔고의 매출전환·차량당 콘텐츠·소프트웨어·운전자본 | 정상화 EBIT/현금전환 | 유사 segment 공시 전 수치 peer 미포함 |

구체적인 이익풀 분석은 [기업 고유 프레임워크](research/COMPANY_SPECIFIC_FRAMEWORK.md), [peer 포함 게이트](research/PEER_SELECTION_SCORECARD.md), [메모리 가정의 증거 기준](research/MEMORY_PREMIUM_FRAMEWORK.md), [valuation vintage 정책](research/VALUATION_VINTAGE_POLICY.md)를 따른다.

**해석 주의:** 9.0x/7.0x/4.5x/3.0x/2.5x는 현재 메모리 제품별 EV/EBIT 시나리오 입력이다. 공개된 제품별 시장 fair multiple이나 완전한 과거 주기 통계로 추정된 계수가 아니다. 6.23x 가중 배수는 이 입력의 수학적 결과이며, 실적전망에 이미 포함된 HBM 성장을 다시 프리미엄으로 더하지 않는다.

## 공식 출처

- [Samsung 2Q26 results](https://news.samsung.com/global/samsung-electronics-announces-second-quarter-2026-results)
- [Samsung 2Q26 earnings presentation](https://images.samsung.com/is/content/samsung/assets/global/ir/docs/2026_2Q_conference_eng.pdf)
- [Samsung 1Q26 earnings presentation](https://images.samsung.com/is/content/samsung/assets/global/ir/docs/2026_1Q_conference_eng.pdf)
- [Samsung 3Q26 preliminary release coverage](https://www.reuters.com/world/asia-pacific/samsung-q3-profit-jumps-783-ai-memory-boom-lifts-chip-earnings-2026-10-07/)

투자 권유가 아닙니다.
