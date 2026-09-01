# Market selection

## Objective

Determine which prediction market category provides the strongest foundation for the project, considering data availability, trading relavance and feasability within the project's timeline.

---

## Candidate markets
| **Market** | Passed screening? |
|---|:---:|
| **Macro** | Y |
| **Weather** | Y |
| **Global shipping** | N |
| **Crypto** | Y |
| **Biotech contracts** | N |
| **Electricity pricing** | N |

See [Research log](research_log.md) for details.

| Market | Historical data | Granularity | Order book | Liquidity | Independent data | Sample size | Backtestability | Trading relevance | Differentiation |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Macro** |  |  |  |  |  |  |  |  |  |
| **Weather** |  |  |  |  |  |  |  |  |  |
| **Crypto** |  |  |  |  |  |  |  |  |  |

---

## Evaluation criteria

| Score | Meaning|
|---|---|
| **1** | Very poor |
| **2** | Weak |
| **3** | Adequate |
| **4** | Strong |
| **5** | Ideal |

* The following are general rules, scoring exceptions may apply. Refer to [Research Log](research_log.md) for details.

### Historical data
How much historical market data is publicly accessible?

| Score | Definition|
|---|---|
| **1** | Little/no data |
| **2** | Limited |
| **3** | Sufficient for basic analysis |
| **4** | Extensive |
| **5** | Extensive, high quality |

### Granularity
How frequently can market state be reconstructed?

| Score | definition|
|---|---|
| **1** | Resolution level/observation only |
| **2** | Daily |
| **3** | Hourly |
| **4** | Minute level |
| **5** | Tick |

### Order book
Can historical order book data be obtained?

| Score | definition|
|---|---|
| **1** | No data available |
| **2** | Very limited/short coverage of data |
| **3** | Reasonable data, with gaps/limited depth |
| **4** | Extensive data, good temporal resolution |
| **5** | High quality and comprehensive data, allows near faithful reconstruction of market state |

### Liquidity
Is sufficient liquidity available for realistic simulated execution?

| Score | definition|
|---|---|
| **1** | Negligible activity, wide spreads |
| **2** | Low, difficult executing positions regardless of size |
| **3** | Moderate, small positions are generally executeable |
| **4** | High, consistant volume and depth, relatively low spreads |
| **5** | Exceptional, substantial capacity for execution |

### Independant data
Can information unrelated to the market price be obtained to construct an independant probability estimate?

| Score | definition|
|---|---|
| **1** | No data available |
| **2** | Very limited or short coverage of data, insufficient |
| **3** | Reasonable data, with gaps or limited depth |
| **4** | Extensive data, good temporal resolution |
| **5** | High quality and comprehensive data |

### Sample size
How many relevant markets are obtainable?

| Score | definition|
|---|---|
| **1** | Very few relevant contracts |
| **2** | Some relevant contracts, Limited variety or inconsistant availability|
| **3** | Adequate number of contracts |
| **4** | Large and consistant group of contracts spread across time |
| **5** | Extensive, diverse and consistantly available group of highly relevant contracts|

### Backtestability
Can historical trades be simulated realistically, including execution, fees and liquidity?

| Score | definition|
|---|---|
| **1** | Not possible |
| **2** | Highly simplified system, major assumptions |
| **3** | Simplified system, assumptions for execution/liquidity |
| **4** | Realistic system, includes timestamps, executable prices, fees and useful liquidity information |
| **5** | A high fidelity system is feasible, includes order level execution, spreads, fees, slippage, liquidity constraints and unambiguous resolution rules |

### Trading relevance
How closely does the market resemble financial markets?

| Score | definition|
|---|---|
| **1** | Minimal relevance beyound prediction accuracy |
| **2** | Some similarity, certain dynamics are highly simplified |
| **3** | Supports genuine trading decisions and basic portfolio/risk management concepts |
| **4** | Closely reflects financial trading with dynamic pricing, liquidity constraints, execution trade-offs and risk management |
| **5** | Strongly resembles professional financial trading, produces methods/insights directly transferable to other markets |

### Differentiation
Does the market offer angle beyond a standard prediction/ML project?

| Score | definition|
|---|---|
| **1** | Conventional prediction task |
| **2** | Limited novelry beyond standard modelling|
| **3** | Combines probability estimation with market calibration/a basic trading strategy |
| **4** | Offers a distinctive research angle |
| **5** | Enables a clearly original and technically substantial study |

---

## Research conclusions

### Macro

### Weather

### Global shipping

### Crypto

### Biotech contracts

### Electricity pricing

---

# Final selection
