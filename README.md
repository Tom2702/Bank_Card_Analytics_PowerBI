
- Monthly card spend remained relatively stable, ranging from about **$184K in February** to **$208K in January**.
- Successful transaction volume ranged from around **4.2K to 4.7K transactions per month**, with October showing the highest transaction count.
- Average transaction value was **$43.52**, slightly down versus the previous month, while total spend and successful transactions showed small positive month-over-month movement.
- Active card rate was **13.9%**, indicating that a large share of issued cards still had no recent activity.
- The biggest failure reason was **Insufficient Balance**, with **534 failed transactions**, far higher than **Bad PIN** at **115** and **Technical Glitch** at **93**.

Business interpretation:

- The card business has stable transaction performance, but card activation remains a major growth opportunity.
- Insufficient balance is the main operational friction point and should be monitored as both a customer experience and risk signal.

### 2. Customer Value

The customer base includes **2,000 clients**, but only **301 active clients** are currently generating card activity.

Segment-level findings:

| Segment | Spend | Active Clients | Approx. Spend per Active Client |
|---|---:|---:|---:|
| Low Value | `$535K` | `147` | `$3.6K` |
| Mid Value | `$506K` | `78` | `$6.5K` |
| High Value | `$476K` | `29` | `$16.4K` |
| Upper Mid Value | `$456K` | `47` | `$9.7K` |

Key observations:

- **Inactive clients account for 1,697 clients**, or about **84.85%** of the total client base.
- Low Value clients generate the highest total spend because they have the largest active population.
- High Value clients have the strongest spend intensity, generating about **$16.4K per active client**, despite having only **29 active clients**.
- High DTI customers contributed about **$753K**, the largest spend among DTI groups.
- The dashboard indicates that age group, income group, DTI category, and client segment all influence total card spend.

Business interpretation:

- The bank should treat customer growth as two separate strategies: activate the large inactive base and retain high-value clients with stronger personalized offers.
- High DTI spend should be monitored carefully because it can represent both revenue opportunity and potential credit risk.

### 3. Card Performance

The dashboard shows **853 active cards**, an **active card rate of 13.9%**, and an average of **53 transactions per card**.

Card type performance:

| Card Type | Total Spend | Share of Spend | Active Cards | Avg Tx/Card |
|---|---:|---:|---:|---:|
| Debit | `$1.152M` | `58%` | `499` | `58` |
| Credit | `$761K` | `39%` | `284` | `48` |
| Debit Prepaid | `$59K` | `3%` | `70` | `37` |

Key observations:

- Debit cards dominate total spend, contributing about **58%** of total card spend.
- Credit cards still contribute a meaningful **39%** of total spend, but have fewer active cards than debit.
- Debit prepaid cards contribute only **3%** of spend and show the lowest average transactions per card.
- Dormant card opportunity is significant: **3,012 dormant debit cards**, **1,773 dormant credit cards**, and **508 dormant prepaid cards**.
- Total dormant cards across the three card types are approximately **5,293**, which is about **6.2 times** the number of active cards.
- Medium credit limit cards generated the highest spend at about **$848K** and the strongest active card rate at **15.4%**.

Business interpretation:

- Debit cards are the strongest current product, but dormant cards represent the largest immediate activation opportunity.
- Medium credit limit cards appear to balance spend potential and activity rate well, making them a useful benchmark for product targeting.

### 4. Merchant Spend

The Merchant Spend dashboard view shows approximately **$2.37M** in spend, **55K successful transactions**, an average transaction value of **$43.37**, and a **98.4% success rate**.

Top merchant categories by spend:

| Rank | Merchant Category | Spend |
|---:|---|---:|
| 1 | Money Transfer | `$201K` |
| 2 | Grocery Stores, Supermarkets | `$176K` |
| 3 | Wholesale Clubs | `$157K` |
| 4 | Drug Stores and Pharmacies | `$147K` |
| 5 | Service Stations | `$131K` |

Key observations:

- The top three merchant categories generated about **$534K**, representing roughly **22.5%** of the selected Merchant Spend view.
- Everyday categories such as grocery, pharmacy, service stations, utilities, and restaurants appear frequently in the top spend categories.
- Some categories have much higher average transaction values, such as **Cruise Lines at $1,188**, **Bolt/Nut/Screw/Rivet Manufacturing at $1,034**, and **Tools/Parts/Supplies Manufacturing at $918**.
- Debit and credit cards both contribute strongly across merchant categories, while prepaid debit contributes much less.

Business interpretation:

- Everyday merchant categories should be prioritized for loyalty offers and partnership campaigns because they drive recurring spend.
- High-ticket merchant categories should be reviewed separately because they may create large spend impact with lower transaction frequency.

### 5. Credit Risk

The Credit Risk page identifies **70 high-risk clients**, a **23.3% high-risk client rate**, an average credit score of **718**, and a DTI ratio of **1.27**.

Risk distribution findings:

| Dimension | Key Finding |
|---|---|
| Credit Score Group | The Good score group has the largest client count with **156 clients** |
| High-Risk Count by Income | Low Income has the highest high-risk client count with **21 clients** |
| High-Risk Rate by Income | High Income shows a high-risk rate of about **25%** |
| Debt Burden by Income | High Income has the highest total debt at about **$985M** |
| DTI by Income | Lower-Mid Income has the highest DTI ratio at about **1.36** |
| Debt Exposure by Credit Score | Good score clients carry the largest debt exposure at about **$1.338B** |
| Poor Credit Score Group | Smallest group, but highest high-risk rate at about **60%** |

Key observations:

- Risk is not limited to customers with low credit scores. The Good credit score group has the largest debt exposure by volume.
- The Poor credit score group has only a small number of clients, but its high-risk rate is the highest.
- Low Income customers have the highest count of high-risk clients, while Lower-Mid Income customers show the highest DTI pressure.
- Insufficient Balance transactions reached **534**, making it an important behavioral warning signal.

Business interpretation:

- Credit risk monitoring should combine credit score, DTI ratio, income group, and debt exposure instead of relying on credit score alone.
- The bank should separately monitor high-volume debt groups and high-risk-rate groups because they represent different types of risk.

## Business Recommendations

- **Activate dormant cards**: Prioritize debit and credit card activation campaigns because dormant cards are more than six times larger than active cards.
- **Reduce insufficient balance failures**: Use balance alerts, transaction reminders, or pre-transaction notifications to reduce the largest failure category.
- **Protect high-value customers**: High Value clients generate the strongest spend per active client, so retention offers should focus on this group.
- **Grow everyday merchant partnerships**: Grocery, pharmacy, utilities, restaurants, and service stations are strong candidates for rewards or cashback campaigns.
- **Monitor DTI-heavy customers**: High DTI customers generate meaningful spend, but should be tracked carefully for credit risk.
- **Improve risk segmentation**: Combine credit score, income group, debt exposure, and DTI ratio to identify risk more accurately.

## Tools & Technologies

- **Power BI Desktop**: Dashboard development and data visualization
- **Power Query**: Data cleaning, transformation, and shaping
- **DAX**: KPI measures, calculated logic, and analytical metrics
- **Data Modeling**: Star schema, relationships, and date dimension
- **Design Thinking**: User-centered dashboard planning and validation
- **PowerPoint**: Project presentation and storytelling

## Project Files

| File | Description |
|---|---|
| `Bank Card Project.pbix` | Main Power BI dashboard file |
| `Design Thinking Bank Project - Design Thinking Ver 4.csv` | Design Thinking documentation and project planning file |
| `Design_Thinking_Bank_Project_Presentation.pptx` | Project presentation deck |
| `README.md` | GitHub project documentation |

## Future Improvements

- Publish the report to Power BI Service for scheduled refresh and stakeholder sharing
- Add drill-through pages for client, card, and merchant-level investigation
- Add predictive scoring for high-risk client detection
- Add customer lifetime value analysis
- Add row-level security for different stakeholder groups
- Convert business recommendations into a formal action plan with owners and timelines
