## Accounting & Financial Calculation

이 섹터는 단순 회계 용어집이 아니라, LX인터내셔널 유지Trading 실무에서 사용하는 손익·현금흐름·경제성 산출 공식을 정리한 매뉴얼이다.

### 목차

**손익 계산**
1. [Revenue (매출액)](#revenue-매출액)
2. [Cost of Goods Sold (매출원가)](#cost-of-goods-sold-매출원가)
3. [Gross Profit (매출총이익)](#gross-profit-매출총이익)
4. [Gross Margin (매출총이익률)](#gross-margin-매출총이익률)
5. [Operating Expenses (영업비용)](#operating-expenses-영업비용)
6. [Operating Profit / EBIT (영업이익)](#operating-profit--ebit-영업이익)
7. [Operating Margin (영업이익률)](#operating-margin-영업이익률)
8. [EBITDA](#ebitda)
9. [EBITDA Margin](#ebitda-margin)
10. [Earnings Before Tax (EBT)](#earnings-before-tax-ebt)
11. [Net Income (당기순이익)](#net-income-당기순이익)
12. [Net Margin](#net-margin)

**Trading 경제성**
13. [Trading Margin](#trading-margin)
14. [Unit Margin](#unit-margin)
15. [Contribution Margin](#contribution-margin)
16. [Contribution Margin Ratio](#contribution-margin-ratio)
17. [Landed Cost](#landed-cost)
18. [Netback](#netback)
19. [Break-even Price](#break-even-price)
20. [Break-even Volume](#break-even-volume)

**현금흐름 / 투자**
21. [Operating Cash Flow (OCF)](#operating-cash-flow-ocf)
22. [Free Cash Flow (FCF)](#free-cash-flow-fcf)
23. [FCFF](#fcff)
24. [FCFE](#fcfe)
25. [CAPEX](#capex)
26. [Working Capital](#working-capital)
27. [Cash Conversion Cycle (CCC)](#cash-conversion-cycle-ccc)
28. [ROIC](#roic)

---

### Revenue (매출액)

**정의**
- 일정 기간 동안 상품 판매로 발생한 총 판매금액이다. Trading에서는 계약 단가와 인도 물량의 곱으로 산출되며, 인도조건(FOB/CIF 등)에 따라 인식 시점이 달라질 수 있다.

**산식**
- `Revenue = Selling Price × Volume`

**구성요소**
- Selling Price : 계약상 판매단가(USD/MT)
- Volume : 인도 물량(MT)

**Trading Example**
- 판매 : 5,000 MT × USD 1,150 = **USD 5,750,000**

---

### Cost of Goods Sold (매출원가)

**정의**
- 판매된 상품을 조달하는 데 직접 소요된 원가다. Trading에서는 매입원가에 Landed Cost(운임·보험·통관비 등)를 더해 산출하며, 매입 타이밍과 헤지 손익이 반영되기도 한다.

**산식**
- `COGS = Purchase Cost + Landed Cost`

**구성요소**
- Purchase Cost : 상품 매입가격(FOB 기준 등)
- Landed Cost : 목적지 도착까지 발생하는 운임·보험·통관·부대비용

**Trading Example**
- 매입 : 5,000 MT × USD 1,020 = USD 5,100,000
- Landed Cost : USD 150,000

→ COGS = **USD 5,250,000**

---

### Gross Profit (매출총이익)

**정의**

상품 판매를 통해 발생한 매출에서 상품 자체의 원가를 차감한 이익이다. Trading에서는 매입가격과 Landed Cost 관리가 Gross Profit의 핵심이다.

**산식**

`Gross Profit = Revenue - COGS`

**구성요소**

- Revenue : 총 판매금액
- COGS : 상품 매입원가 및 직접원가

**Trading Example**

- 판매 : 5,000 MT × USD 1,120 = USD 5,600,000
- COGS : USD 5,250,000

→ Gross Profit = **USD 350,000**

---

### Gross Margin (매출총이익률)

**정의**
- 매출액 대비 Gross Profit의 비율이다. Trading에서는 상품·항로별 마진율을 비교해 자본 배분 우선순위를 정하는 데 사용된다.

**산식**
- `Gross Margin = Gross Profit / Revenue × 100`

**구성요소**
- Gross Profit : 매출총이익
- Revenue : 매출액

**Trading Example**
- Gross Profit : USD 350,000
- Revenue : USD 5,600,000

→ Gross Margin = **6.25%**

---

### Operating Expenses (영업비용)

**정의**
- 매출원가 이외에 영업활동을 유지하기 위해 발생하는 비용이다. 인건비, 사무실 운영비, 마케팅비 등이 포함되며 Trading 실무에서는 데스크 운영비·시스템 이용료 등이 여기에 잡힌다.

**산식**
- `Operating Expenses = SG&A + Other Operating Costs`

**구성요소**
- SG&A : 판매비와 관리비
- Other Operating Costs : 기타 영업활동 관련 비용

**Trading Example**
- SG&A : USD 40,000
- Other Operating Costs : USD 10,000

→ Operating Expenses = **USD 50,000**

---

### Operating Profit / EBIT (영업이익)

**정의**
- Gross Profit에서 영업비용을 차감한, 이자와 세금 지급 전 영업활동만의 이익이다. 헤지손익이나 환차손익 등 영업외 항목을 제외해 순수 Trading 수익성을 보여준다.

**산식**
- `EBIT = Gross Profit - Operating Expenses`

**구성요소**
- Gross Profit : 매출총이익
- Operating Expenses : 영업비용

**Trading Example**
- Gross Profit : USD 350,000
- Operating Expenses : USD 50,000

→ EBIT = **USD 300,000**

---

### Operating Margin (영업이익률)

**정의**
- 매출액 대비 EBIT의 비율이다. 원자재 가격 변동성이 큰 Trading 특성상 Gross Margin보다 변동폭이 작게 관리되는지 확인하는 지표로 쓰인다.

**산식**
- `Operating Margin = EBIT / Revenue × 100`

**구성요소**
- EBIT : 영업이익
- Revenue : 매출액

**Trading Example**
- EBIT : USD 300,000
- Revenue : USD 5,600,000

→ Operating Margin = **5.36%**

---

### EBITDA

**정의**
- EBIT에 감가상각비와 무형자산상각비를 더한 값이다. 설비·탱크·물류 인프라에 대한 투자 부담을 제외한 현금창출력을 비교할 때 사용된다.

**산식**
- `EBITDA = EBIT + Depreciation + Amortization`

**구성요소**
- EBIT : 영업이익
- Depreciation : 유형자산 감가상각비
- Amortization : 무형자산 상각비

**Trading Example**
- EBIT : USD 300,000
- Depreciation : USD 15,000
- Amortization : USD 5,000

→ EBITDA = **USD 320,000**

---

### EBITDA Margin

**정의**
- 매출액 대비 EBITDA의 비율이다. 자산 규모나 감가상각 정책이 다른 사업부·법인 간 현금창출력을 비교할 때 활용된다.

**산식**
- `EBITDA Margin = EBITDA / Revenue × 100`

**구성요소**
- EBITDA : 상각전영업이익
- Revenue : 매출액

**Trading Example**
- EBITDA : USD 320,000
- Revenue : USD 5,600,000

→ EBITDA Margin = **5.71%**

---

### Earnings Before Tax (EBT)

**정의**
- EBIT에서 이자비용 등 영업외손익을 반영한, 법인세 차감 전 이익이다. Trading에서는 선물·옵션 헤지손익, 환차손익, 차입금 이자비용이 주요 영업외 항목이다.

**산식**
- `EBT = EBIT - Interest Expense + Non-operating Income - Non-operating Expense`

**구성요소**
- EBIT : 영업이익
- Interest Expense : 이자비용
- Non-operating Income/Expense : 헤지손익·환차손익 등 영업외손익

**Trading Example**
- EBIT : USD 300,000
- Interest Expense : USD 20,000
- Non-operating Income(환차익) : USD 10,000

→ EBT = **USD 290,000**

---

### Net Income (당기순이익)

**정의**
- EBT에서 법인세비용을 차감한 최종 순이익이다. 회사 전체 손익의 최종 결과이며 배당가능이익 산정의 기초가 된다.

**산식**
- `Net Income = EBT - Tax`

**구성요소**
- EBT : 법인세차감전순이익
- Tax : 법인세비용

**Trading Example**
- EBT : USD 290,000
- Tax(세율 25%) : USD 72,500

→ Net Income = **USD 217,500**

---

### Net Margin

**정의**
- 매출액 대비 Net Income의 비율이다. 세금·이자비용까지 모두 반영한 최종 수익성 지표로, 저마진 구조인 Trading 업의 특성상 통상 한 자릿수 초반에 형성된다.

**산식**
- `Net Margin = Net Income / Revenue × 100`

**구성요소**
- Net Income : 당기순이익
- Revenue : 매출액

**Trading Example**
- Net Income : USD 217,500
- Revenue : USD 5,600,000

→ Net Margin = **3.88%**

---

### Trading Margin

**정의**
- 매입가격과 판매가격의 차이를 물량으로 곱해 산출하는, Trading 계약 단위의 총마진이다. 개별 카고(Cargo) 단위의 손익 판단에 가장 먼저 확인하는 수치다.

**산식**
- `Trading Margin = (Selling Price - Buying Price) × Volume`

**구성요소**
- Selling Price : 판매단가
- Buying Price : 매입단가(Landed Cost 포함 여부는 별도 명시)
- Volume : 거래 물량

**Trading Example**
- Selling Price : USD 1,150/MT, Buying Price : USD 1,090/MT
- Volume : 5,000 MT

→ Trading Margin = (1,150 - 1,090) × 5,000 = **USD 300,000**

---

### Unit Margin

**정의**
- 1 MT당 마진으로, 계약 규모가 다른 여러 카고의 수익성을 동일선상에서 비교할 때 사용하는 표준화 지표다.

**산식**
- `Unit Margin = Trading Margin / Volume`

**구성요소**
- Trading Margin : 계약 총마진
- Volume : 거래 물량

**Trading Example**
- Trading Margin : USD 300,000
- Volume : 5,000 MT

→ Unit Margin = **USD 60/MT**

---

### Contribution Margin

**정의**
- 매출에서 변동비만을 차감한 이익으로, 고정비를 회수하고 남는 금액을 의미한다. 신규 카고 체결 여부를 판단할 때 고정비 배분 없이 "이 거래를 추가로 받을 가치가 있는가"를 보는 지표다.

**산식**
- `Contribution Margin = Revenue - Variable Cost`

**구성요소**
- Revenue : 매출액
- Variable Cost : 매입원가·운임 등 물량에 비례하는 변동비

**Trading Example**
- Revenue : USD 5,600,000
- Variable Cost(매입+운임) : USD 5,250,000

→ Contribution Margin = **USD 350,000**

---

### Contribution Margin Ratio

**정의**
- 매출액 대비 Contribution Margin의 비율이다. 이 비율이 높을수록 물량 증가가 고정비 회수에 기여하는 속도가 빠르다.

**산식**
- `Contribution Margin Ratio = Contribution Margin / Revenue × 100`

**구성요소**
- Contribution Margin : 공헌이익
- Revenue : 매출액

**Trading Example**
- Contribution Margin : USD 350,000
- Revenue : USD 5,600,000

→ Contribution Margin Ratio = **6.25%**

---

### Landed Cost

**정의**
- 상품이 최종 목적지(항구·탱크)에 도착하기까지 발생하는 모든 비용을 매입가격에 합산한 총원가다. 인도조건(FOB/CIF/Ex Tank)이 다른 오퍼를 동일 기준으로 비교할 때 반드시 환산해야 하는 개념이다.

**산식**
- `Landed Cost = FOB Price + Freight + Insurance + Import Duty + Other Charges`

**구성요소**
- FOB Price : 본선인도 기준 매입단가
- Freight : 해상운임
- Insurance : 해상보험료
- Import Duty : 수입관세
- Other Charges : 하역비·창고료 등 부대비용

**Trading Example**
- FOB Price : USD 1,020/MT × 5,000 MT = USD 5,100,000
- Freight : USD 100,000
- Insurance : USD 10,000
- Import Duty : USD 30,000
- Other Charges : USD 10,000

→ Landed Cost = **USD 5,250,000** (USD 1,050/MT)

---

### Netback

**정의**
- 최종 판매가격에서 운임·보험·관세 등 판매지까지의 비용을 역산해 공제한, 공급지 기준의 실질 실현가격이다. 여러 목적지로 판매 가능한 카고를 어디로 보낼지 결정할 때 목적지 간 비교 기준으로 쓰인다.

**산식**
- `Netback = Destination Selling Price - Freight - Insurance - Duty - Other Charges`

**구성요소**
- Destination Selling Price : 목적지 판매단가
- Freight/Insurance/Duty/Other Charges : 공급지에서 목적지까지 발생하는 비용

**Trading Example**
- 목적지 판매가 : USD 1,150/MT
- Freight+Insurance+기타 : USD 40/MT

→ Netback = 1,150 - 40 = **USD 1,110/MT** (공급지 기준 실현가치)

---

### Break-even Price

**정의**
- 해당 물량에서 손익이 0이 되는 판매단가다. 시장가격이 이 수준 이하로 하락하면 해당 카고는 손실 구간에 진입한다.

**산식**
- `Break-even Price = (Total Fixed Cost + Total Variable Cost) / Volume`

**구성요소**
- Total Fixed Cost : 해당 거래에 배분된 고정비
- Total Variable Cost : 매입원가 등 변동비 총액
- Volume : 거래 물량

**Trading Example**
- 배분 고정비 : USD 50,000
- 변동비 총액 : USD 5,100,000
- Volume : 5,000 MT

→ Break-even Price = (50,000 + 5,100,000) / 5,000 = **USD 1,030/MT**

---

### Break-even Volume

**정의**
- 주어진 판매단가에서 고정비를 회수하는 데 필요한 최소 판매물량이다. 계약 협상 시 "이 가격이면 최소 몇 MT는 팔아야 하는가"를 판단하는 기준이 된다.

**산식**
- `Break-even Volume = Total Fixed Cost / (Selling Price - Variable Cost per Unit)`

**구성요소**
- Total Fixed Cost : 고정비 총액
- Selling Price : 단위 판매단가
- Variable Cost per Unit : 단위당 변동비

**Trading Example**
- Total Fixed Cost : USD 50,000
- Selling Price : USD 1,120/MT, Variable Cost per Unit : USD 1,050/MT

→ Break-even Volume = 50,000 / (1,120 - 1,050) = **714 MT**

---

### Operating Cash Flow (OCF)

**정의**
- 영업활동을 통해 실제로 유입·유출된 현금이다. 순이익에 비현금성 비용을 더하고 운전자본 변동을 반영해 산출하며, 재고·매입채무 규모가 큰 Trading 업에서는 순이익과 괴리가 크게 발생할 수 있다.

**산식**
- `OCF = Net Income + Depreciation & Amortization - Change in Working Capital`

**구성요소**
- Net Income : 당기순이익
- Depreciation & Amortization : 감가상각비·무형자산상각비
- Change in Working Capital : 운전자본 증감(재고·매출채권·매입채무 변동)

**Trading Example**
- Net Income : USD 217,500
- D&A : USD 20,000
- Working Capital 증가(재고 확대) : USD 100,000

→ OCF = 217,500 + 20,000 - 100,000 = **USD 137,500**

---

### Free Cash Flow (FCF)

**정의**
- OCF에서 설비 등 자본적지출(CAPEX)을 차감한, 채권자와 주주 모두에게 배분 가능한 잉여현금이다. 배당·차입금 상환·재투자 여력을 판단하는 핵심 지표다.

**산식**
- `FCF = OCF - CAPEX`

**구성요소**
- OCF : 영업활동현금흐름
- CAPEX : 자본적지출

**Trading Example**
- OCF : USD 137,500
- CAPEX(탱크 개보수) : USD 30,000

→ FCF = **USD 107,500**

---

### FCFF

**정의**
- Free Cash Flow to Firm. 이자비용 지급 전, 채권자와 주주 모두에게 귀속되는 현금흐름이다. 기업가치(Enterprise Value) 평가 시 할인 대상 현금흐름으로 사용된다.

**산식**
- `FCFF = EBIT × (1 - Tax Rate) + D&A - CAPEX - Change in Working Capital`

**구성요소**
- EBIT : 영업이익
- Tax Rate : 법인세율
- D&A : 감가상각비·무형자산상각비
- CAPEX : 자본적지출
- Change in Working Capital : 운전자본 증감

**Trading Example**
- EBIT : USD 300,000, Tax Rate 25%
- D&A : USD 20,000, CAPEX : USD 30,000, Working Capital 증가 : USD 100,000

→ FCFF = 300,000×0.75 + 20,000 - 30,000 - 100,000 = 225,000 + 20,000 - 30,000 - 100,000 = **USD 115,000**

---

### FCFE

**정의**
- Free Cash Flow to Equity. FCFF에서 이자비용(세후)을 차감하고 순차입금 변동을 더한, 주주에게 귀속되는 현금흐름이다. 주식가치 평가나 배당 여력 판단에 사용된다.

**산식**
- `FCFE = FCFF - Interest Expense × (1 - Tax Rate) + Net Borrowing`

**구성요소**
- FCFF : 기업잉여현금흐름
- Interest Expense : 이자비용
- Net Borrowing : 순차입(신규 차입 - 상환)

**Trading Example**
- FCFF : USD 115,000
- Interest Expense : USD 20,000(세율 25% 적용 시 세후 15,000)
- Net Borrowing : USD 0

→ FCFE = 115,000 - 15,000 + 0 = **USD 100,000**

---

### CAPEX

**정의**
- 유형·무형자산 취득에 지출한 투자금액이다. Trading 업에서는 저장탱크·터미널·물류설비 등 장기 자산에 대한 지출이 주를 이루며, 손익계산서가 아닌 현금흐름표·재무상태표에 반영된다.

**산식**
- `CAPEX = Ending PP&E - Beginning PP&E + Depreciation`

**구성요소**
- Ending PP&E / Beginning PP&E : 기말·기초 유형자산 장부가액
- Depreciation : 해당 기간 감가상각비

**Trading Example**
- 기초 PP&E : USD 500,000, 기말 PP&E : USD 515,000
- Depreciation : USD 15,000

→ CAPEX = 515,000 - 500,000 + 15,000 = **USD 30,000**

---

### Working Capital

**정의**
- 유동자산에서 유동부채를 차감한 값으로, 단기 영업활동을 운영하는 데 필요한 자금이다. Trading 업은 재고와 매출채권 비중이 높아 물량·가격이 커질수록 운전자본 부담도 함께 커진다.

**산식**
- `Working Capital = Current Assets - Current Liabilities`

**구성요소**
- Current Assets : 재고자산·매출채권·현금성자산 등 유동자산
- Current Liabilities : 매입채무·단기차입금 등 유동부채

**Trading Example**
- Current Assets(재고 USD 800,000 + 매출채권 USD 400,000 + 현금 USD 100,000) : USD 1,300,000
- Current Liabilities(매입채무 USD 900,000) : USD 900,000

→ Working Capital = **USD 400,000**

---

### Cash Conversion Cycle (CCC)

**정의**
- 원재료·상품 매입에 현금을 투입한 시점부터 판매대금을 회수하기까지 걸리는 일수다. 재고 보유기간과 매출채권 회수기간의 합에서 매입채무 지급유예기간을 차감해 산출하며, 짧을수록 자금 회전이 빠르다.

**산식**
- `CCC = DIO + DSO - DPO`

**구성요소**
- DIO(Days Inventory Outstanding) : 재고자산 평균 보유일수
- DSO(Days Sales Outstanding) : 매출채권 평균 회수일수
- DPO(Days Payable Outstanding) : 매입채무 평균 지급유예일수

**Trading Example**
- DIO : 25일, DSO : 30일, DPO : 20일

→ CCC = 25 + 30 - 20 = **35일**

---

### ROIC

**정의**
- Return On Invested Capital. 영업활동에 투입된 자본(차입금+자본) 대비 세후 영업이익의 비율이다. Trading 사업이 자본비용 이상의 수익을 창출하는지 판단하는 핵심 투자수익성 지표다.

**산식**
- `ROIC = NOPAT / Invested Capital × 100`

**구성요소**
- NOPAT(Net Operating Profit After Tax) : 세후 영업이익 = EBIT × (1 - Tax Rate)
- Invested Capital : 순차입금 + 자기자본(또는 총자산 - 유동부채 중 무이자성 부채)

**Trading Example**
- EBIT : USD 300,000, Tax Rate 25% → NOPAT = USD 225,000
- Invested Capital : USD 2,500,000

→ ROIC = 225,000 / 2,500,000 × 100 = **9.0%**
