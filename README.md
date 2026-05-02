# Formal Statistical Tests for Homoscedasticity

**Author:** Youssef Aittizi  
**Affiliation:** Department of Mathematics, Zhejiang University of Science & Technology  
**Date:** May 2026

## Overview

This repository contains a production-grade Jupyter notebook demonstrating 
the detection of heteroscedasticity via four key formal tests:

- Breusch–Pagan / Koenker (BP/K) test
- White's general test (1980)
- Goldfeld–Quandt test (1965)
- Park test (1966) — historical reference

**Dataset:** Current Population Survey (CPS) `wage1` (Wooldridge, 2015; n=526)

**Model:** Mincer log-wage equation with graphical diagnostics (residual plots, 
scale-location), formal tests, and HC3-robust standard error corrections.

## References

- Breusch, T.S. & Pagan, A.R. (1979). *Econometrica*, 47(5), 1287–1294.
- Koenker, R. (1981). *Journal of Econometrics*, 17(1), 107–112.
- White, H. (1980). *Econometrica*, 48(4), 817–838.
- Goldfeld, S.M. & Quandt, R.E. (1965). *JASA*, 60(310), 539–547.
- Park, R.E. (1966). *Econometrica*, 34(4), 888.
- Wooldridge, J.M. (2015). *Introductory Econometrics* (6th ed.). Cengage.

