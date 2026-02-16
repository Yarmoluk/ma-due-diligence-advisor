# Financial Due Diligence

## Understanding Financial Health and Performance

Financial due diligence represents the cornerstone of M&A investigation, providing the quantitative foundation for valuation, deal structuring, and risk assessment. This workstream validates reported financial performance, identifies quality of earnings issues, assesses working capital requirements, and evaluates the sustainability of historical results as a predictor of future performance.

### Quality of Earnings Analysis

Quality of earnings (QoE) analysis normalizes historical financial performance to reflect the sustainable earnings power of the business under new ownership. This process identifies and adjusts for non-recurring items, aggressive accounting policies, related party transactions, and other factors that distort reported results.

#### Objectives of QoE Analysis

The QoE process serves several critical functions:

- **Normalize Historical Performance**: Remove one-time items and anomalies to reveal sustainable earnings
- **Validate Management Representations**: Test the accuracy and completeness of financial information
- **Inform Valuation**: Provide normalized earnings as the foundation for valuation multiples
- **Identify Risk Factors**: Uncover accounting irregularities, revenue recognition issues, or expense timing manipulations
- **Support Purchase Price Adjustments**: Quantify adjustments to enterprise value based on findings

#### Common QoE Adjustments

**Non-Recurring Revenue Items**:
- One-time project revenues or consulting engagements
- Insurance proceeds or legal settlements
- Sale of assets or business units
- Government grants or subsidies
- Discontinued product lines

**Non-Recurring Expense Items**:
- Litigation settlements or legal fees for specific matters
- Restructuring and severance costs
- Impairment charges and write-downs
- Owner compensation above or below market rates
- Related party expenses at non-arm's length terms
- Transaction costs and professional fees

**Revenue Recognition Issues**:
- Premature revenue recognition (bill-and-hold arrangements, side letters, conditional sales)
- Channel stuffing or aggressive sales practices near period-end
- Gross vs. net revenue presentation
- Long-term contract revenue recognition methods

**Expense Timing and Classification**:
- Capitalization of expenses that should be expensed
- Deferred maintenance creating artificially low current expenses
- Accrual reversals or estimate changes
- Expense classification (operating vs. non-operating, COGS vs. SG&A)

!!! warning "Red Flags in QoE Analysis"
    Significant red flags include: frequent changes in accounting policies, large fourth-quarter adjustments, growing accounts receivable aging, declining gross margins despite revenue growth, related party transactions without clear business purpose, and material audit adjustments in recent periods.

#### Normalized EBITDA Calculation

Buyers typically focus on normalized EBITDA as the primary earnings metric for valuation purposes.

```
Reported Net Income
+ Interest Expense
+ Tax Expense
+ Depreciation & Amortization
= Reported EBITDA

+/- Quality of Earnings Adjustments
+/- Run-Rate Adjustments
= Normalized EBITDA (Adjusted EBITDA)
```

!!! example "QoE Adjustment Example"
    A target company reports $10M EBITDA. QoE analysis reveals: owner compensation is $800K but market rate for the role is $300K (+$500K adjustment), a $400K legal settlement is included in expenses (+$400K adjustment), and $200K in maintenance was deferred but will be required post-close (-$200K adjustment). Normalized EBITDA becomes $10.7M, directly impacting valuation.

### Working Capital Analysis

Working capital represents the operating liquidity required to run the business day-to-day. Understanding normalized working capital requirements is essential because purchase price typically includes an expected level of working capital at closing, with adjustments if actual working capital differs from the target amount.

#### Working Capital Components

**Current Assets**:
- Cash and cash equivalents (typically excluded from working capital definition)
- Accounts receivable
- Inventory (raw materials, work-in-process, finished goods)
- Prepaid expenses

**Current Liabilities**:
- Accounts payable
- Accrued expenses (wages, benefits, taxes, interest)
- Deferred revenue
- Current portion of long-term debt (typically excluded from working capital definition)

#### Normalized Working Capital Calculation

The normalized working capital target reflects the operating capital necessary to sustain normal business operations, typically calculated as the average of the trailing 12-month period, adjusted for seasonality, growth trends, and known anomalies.

**Step 1: Calculate Historical Working Capital**

For each month in the trailing 12-month period:
```
Working Capital = (A/R + Inventory + Prepaids) - (A/P + Accrued Expenses + Deferred Revenue)
```

**Step 2: Adjust for Anomalies**

Remove months with unusual activity (large one-time sales, inventory builds/liquidations, payment timing anomalies).

**Step 3: Consider Seasonality**

For seasonal businesses, calculate normalized working capital using a full 12-month average or define different targets for peak and off-peak periods.

**Step 4: Adjust for Growth**

If the business is growing, historical average may understate post-close working capital needs. Pro forma the required working capital based on projected revenue levels.

#### Days Sales Outstanding (DSO) and Other Metrics

Key working capital efficiency metrics include:

**Days Sales Outstanding (DSO)**:
```
DSO = (Accounts Receivable / Revenue) × 365
```

**Days Inventory Outstanding (DIO)**:
```
DIO = (Inventory / Cost of Goods Sold) × 365
```

**Days Payable Outstanding (DPO)**:
```
DPO = (Accounts Payable / Cost of Goods Sold) × 365
```

**Cash Conversion Cycle**:
```
Cash Conversion Cycle = DSO + DIO - DPO
```

!!! tip "Working Capital Trends"
    Deteriorating working capital metrics often signal underlying business issues: rising DSO may indicate collection problems or customer credit quality issues, increasing DIO suggests inventory obsolescence or demand softening, and declining DPO may reflect supplier relationship strain.

### Debt and Debt-Like Items

The purchase agreement typically specifies that the buyer acquires the business on a "cash-free, debt-free" basis, meaning the seller retains all cash and pays off all debt at closing (or the purchase price is adjusted accordingly). Identifying all debt and debt-like items is critical to proper enterprise value calculation.

#### Debt Items

- Bank loans and credit facilities
- Bonds and notes payable
- Capital leases and financing obligations
- Seller notes and related party debt
- Accrued interest
- Unamortized debt issuance costs and premiums/discounts

#### Debt-Like Items

Certain balance sheet items represent claims on enterprise value even if not classified as debt:

- **Unfunded Pension Liabilities**: The present value of pension obligations exceeding pension assets
- **Operating Lease Obligations**: Under current accounting standards, operating leases create right-of-use assets and corresponding liabilities
- **Deferred Revenue**: For subscription businesses, deferred revenue represents customer prepayments that must be serviced post-close
- **Environmental Liabilities**: Cleanup obligations for known environmental contamination
- **Litigation Reserves**: Accrued amounts for ongoing legal matters
- **Restructuring Reserves**: Committed severance or facility closure costs
- **Earnout Obligations**: For prior acquisitions, remaining earnout liabilities

!!! info "Net Debt Calculation"
    Net Debt = Total Debt + Debt-Like Items - Cash and Cash Equivalents. This figure adjusts enterprise value to equity value: Equity Value = Enterprise Value - Net Debt.

### Financial Projections Review

Management projections form the basis for acquisition valuation, making their credibility assessment essential. Financial due diligence evaluates projection reasonableness, underlying assumptions, and historical accuracy of management forecasting.

#### Projection Assessment Framework

**Historical Accuracy Analysis**: Compare prior period projections to actual results. Consistent over-optimism raises concerns about current projections.

**Revenue Projection Assessment**:
- Customer and contract pipeline supporting growth assumptions
- Market growth rates and company market share trends
- Pricing assumptions vs. historical realization and competitive dynamics
- New product launches and their probability-weighted contribution
- Customer retention and churn assumptions

**Expense Projection Assessment**:
- Fixed vs. variable cost structure
- Historical relationships between revenue growth and expense growth
- Planned investments in headcount, facilities, or technology
- Inflation assumptions for wages and materials
- Margin trajectory and peer comparison

**Capital Expenditure Requirements**:
- Maintenance capex to sustain current operations
- Growth capex supporting expansion
- Historical capex as percentage of revenue
- Deferred capex that may require catch-up investment

**Sensitivity Analysis**:
- Downside scenarios testing projection sensitivity to key assumptions
- Break-even analysis and minimum performance thresholds
- Synergy dependency and standalone projections

!!! example "Projection Reality Check"
    Management projects 25% annual revenue growth while the historical three-year average is 12%. Investigation reveals: major customer recently reduced orders, two product development initiatives are delayed, and three sales executives departed. This gap between projection optimism and operational reality would prompt downward revision of growth assumptions for valuation purposes.

### Key Takeaways

Financial due diligence transforms reported historical results into reliable indicators of future performance. Quality of earnings analysis normalizes reported results, working capital analysis establishes closing balance sheet expectations, debt and debt-like item identification enables accurate enterprise value calculation, and projection assessment validates management's forecast credibility. These analyses directly inform valuation, deal structuring, and purchase agreement risk allocation, making financial due diligence the quantitative foundation supporting all M&A investment decisions.
