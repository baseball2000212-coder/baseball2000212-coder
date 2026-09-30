### 안녕하세요, 이승윤입니다

- 고려대학교 경영학과 20학번
- 금융공학 학회 U.FE.A 42기
- 세미나 교재: Neftci, *Principles of Financial Engineering* / Taleb, *Dynamic Hedging*
- 요즘 공부하는 것: 변동성, 감마 트레이딩, 델타헤지 손익
- 지금은 SPX 0DTE 옵션 전략을 NH선물 REST API로 실매매해 보려고 준비 중입니다
- 블로그 [Deep ITM](https://blogger71794.tistory.com), 인스타그램 [@winwin_macro](https://www.instagram.com/winwin_macro)

### About Me

파생상품과 트레이딩에 관심이 많습니다.

처음에는 조건을 이것저것 조합해서 수익이 나는 규칙을 찾는 데 집중했습니다. 그런데 체결 가격을 1분 호가 중간값에서 초 단위 매도호가로 바꾸고, 실제 수수료와 시세 이용료를 넣고, 제일 크게 번 하루를 따로 떼어 보니 결과가 꽤 달라졌습니다. 그 뒤로는 백테스트 결과를 보면 어떤 가정으로 계산했는지부터 확인합니다.

데이터는 직접 모읍니다. 국내 파생·수급 데이터와 미국 옵션 체인을 매일 자동으로 받아서, 카드뉴스도 만들고 전략 검증에도 씁니다.

리서치 질문, 검증 설계, 결과 해석은 제가 했고 코드는 AI 코딩 도구(Claude Code)로 같이 짰습니다.

### 프로젝트

**[spx0dte-research](https://github.com/baseball2000212-coder/spx0dte-research)**
S&P500 당일 만기 옵션 매수 전략 백테스트. 1분·초 단위 호가로 395건을 계산했고, 5초·10초 체결 지연과 수수료, 시세 이용료를 반영했습니다. [분석 보고서(PDF)](https://github.com/baseball2000212-coder/spx0dte-research/blob/main/docs/SPX0DTE_naked_call_backtest.pdf)

**[kis-data](https://github.com/baseball2000212-coder/kis-data)**
한국투자증권 Open API로 K200 선물·옵션, 투자자 수급, 미국 지수·종목 데이터를 평일마다 자동 수집합니다. 이 데이터로 매일 시장 카드뉴스를 올립니다.

**[us-option-chains](https://github.com/baseball2000212-coder/us-option-chains)**
SPY, TSLA, AAPL, NVDA, IBIT 옵션 체인 전체를 하루 10번 수집합니다. 델타헤지 손익 분석용 데이터입니다.
