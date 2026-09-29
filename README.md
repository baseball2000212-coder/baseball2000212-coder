### 안녕하세요 👋

옵션 리서치를 하고, 필요한 데이터는 직접 모으고, 전략을 백테스트하는 공간입니다.

* 🔭 지금은 **SPX 0DTE 옵션 전략**을 NH선물 REST API로 실매매에 옮기는 준비를 하고 있습니다
* 🎓 **고려대학교 경영학과** 20학번
* 📚 금융공학 학회 **UFEA 42기**
* 📖 세미나 교재: Neftci, *Principles of Financial Engineering* · Taleb, *Dynamic Hedging*
* 🌱 요즘 공부하는 것: **변동성과 감마 트레이딩**, 델타헤지 손익, 호가·체결 같은 시장 미시구조
* 💬 이런 얘기를 좋아합니다: **0DTE 옵션 · 풋콜 패리티 · 체결 가정 검증 · 옵션 데이터 수집 자동화**
* 📝 공부한 내용은 블로그 [Deep ITM](https://blogger71794.tistory.com)에, 시장 정리는 인스타그램 [@winwin_macro](https://www.instagram.com/winwin_macro)에 올립니다

### ✨ About Me

옵션과 변동성에 관심이 많은 **고려대학교 경영학과** 학생입니다.

처음에는 여러 조건을 조합해 수익이 나는 규칙을 찾는 데 집중했습니다. 그런데 체결을 1분 호가 중간값에서 **초 단위 매도호가**로 바꾸고, 실제 수수료와 시세 이용료를 넣고, 가장 크게 번 하루를 따로 떼어 보니 숫자가 크게 달라졌습니다. 그 뒤로는 **"이 결과가 어떤 가정에서 나왔나"**를 먼저 따지게 됐습니다.

필요한 데이터는 직접 모읍니다. 국내 파생·수급 데이터와 미국 옵션 체인을 매일 자동으로 쌓고, 그 데이터로 카드뉴스를 만들고 전략을 검증합니다.

리서치 질문·검증 설계·결과 해석은 직접 하고, 코드 구현은 AI 코딩 도구(Claude Code)와 함께 합니다.

#### 리서치 & 오픈소스 이야기

* **[spx0dte-research](https://github.com/baseball2000212-coder/spx0dte-research)** — S&P500 당일 만기 옵션 매수 전략을 1분·초 단위 호가로 395건 백테스트. 5·10초 체결 지연, 수수료, 시세 이용료까지 반영하고 큰 날 의존도·요일 효과를 따져 봤습니다. ([분석 보고서 PDF](https://github.com/baseball2000212-coder/spx0dte-research/blob/main/docs/SPX0DTE_naked_call_backtest.pdf))

* **[kis-data](https://github.com/baseball2000212-coder/kis-data)** — 한국투자증권 Open API로 K200 선물·옵션, 투자자 수급, 미국 지수·종목 데이터를 평일마다 자동 수집. GitHub Actions로 돌리고, 이 데이터로 매일 시장 카드뉴스를 발행합니다.

* **[us-option-chains](https://github.com/baseball2000212-coder/us-option-chains)** — SPY·TSLA·AAPL·NVDA·IBIT 전체 옵션 체인을 하루 10번 정시에 수집. 델타헤지 손익을 감마와 세타로 나눠 보려는 데이터입니다.
