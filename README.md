# Categorical Imputation with Independent MLPs

**92.38% accuracy at 20% missing values** — outperforms conjunct MLP and mode baseline.

---

## Results
| Missing Rate | Independent MLPs | Conjunct MLP | Mode |
|--------------|-------------------|--------------|------|
| 5%           | **97.65%**        | 22.41%       | 25.0% |
| 10%          | **96.40%**        | 22.39%       | 25.0% |
| 20%          | **92.38%**        | 22.38%       | 24.9% |

---

## How to Run
```python
# 1. Train
intrain()

# 2. Test
test_and_compare()

# 3. Impute any file
query('input.csv', 'output.csv')
