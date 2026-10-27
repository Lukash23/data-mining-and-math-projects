# Data Mining and Math Projects

Python notebooks from university coursework in data mining, discrete mathematics and calculus. They cover exploratory data analysis, probability and counting, number systems and Boolean logic, and numerical and symbolic calculus.

**Author:** Lukash Shrestha · [LinkedIn](https://www.linkedin.com/in/lukashshrestha-620bab267)

## Repository structure

| Folder | Focus | Notebooks |
|---|---|---|
| [`data-mining/`](data-mining) | Exploratory analysis of cryptocurrency price data | 1 |
| [`discrete-math/`](discrete-math) | Probability, counting, number bases, truth tables, proof | 5 |
| [`calculus/`](calculus) | Limits, derivatives, roots and integration | 4 |

## Tools used

Python · Jupyter · NumPy · pandas · Matplotlib · Seaborn · SciPy · SymPy

## Highlights

- **Crypto price and volatility analysis:** cleaned XRP/USD daily data with pandas, computed daily returns and annualized volatility, and visualized price and volatility over time.
- **Truth table generator:** a function that evaluates Boolean expressions (AND, OR, XOR, NOT) for 2 to 4 variables.
- **Two's complement arithmetic:** binary subtraction implemented from scratch and verified against Python's result.
- **Symbolic calculus with SymPy:** derivatives, tangent lines, extrema and inflection points, and a comparison of numerical and symbolic integration.

## Running the notebooks

1. Install Python 3 and the dependencies:
   ```bash
   pip install jupyter numpy pandas matplotlib seaborn scipy sympy
   ```
2. Clone this repository and start Jupyter:
   ```bash
   git clone https://github.com/Lukash23/data-mining-and-math-projects.git
   cd data-mining-and-math-projects
   jupyter notebook
   ```
3. Open any notebook and choose **Run → Run All Cells**.

The crypto notebook reads `XRP.csv`, which is included in the `data-mining/` folder (see [`data-mining/README.md`](data-mining/README.md)).

## Notes

These notebooks are course assignments and are kept close to their submitted form.
