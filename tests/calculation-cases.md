# Calculation test cases

| Tool | Inputs | Expected result |
| --- | --- | --- |
| Surplus | 3,200,000 income; 2,750,000 costs | 450,000 |
| Surplus | 100 income; 150 costs | -50 |
| Goal | 12,000,000 target; 3,000,000 saved; 18 months | 500,000/month |
| Goal | Saved exceeds target | 0/month |
| Growth | 1,000 initial; 100 monthly; 0%; 1 year | 2,200 |
| Debt | 5,000,000; 24% nominal annual; 24 months | approximately 264,355/month |
| Debt | 1,200; 0%; 12 months | 100/month |

Run with `npm test`.
