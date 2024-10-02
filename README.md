# PAWN-sensitivity-analysis
In this repository, the PAWN sensitivity indices are implemented for the Ishigami-Homma function, a benchmark model used as a numerical example (Pianosi, F., & Wagener, T. (2015)). The PAWN sensitivity indices are also applied to rank the most influential parameters in the abc model, a watershed water balance model with 3 parameters, as described in Vogel & Sankarasubramanian (2003).

PAWN sensitivity analysis is a density-based sensitivity index that measures the sensitivity to input xi by the distance between the unconditional CDF of y, which is obtained when all inputs vary simultaneously, and the conditional CDF of y, which is obtained when varying all inputs but xi (i.e., xi is fixed at a nominal value xi).

References:

- Pianosi, F., & Wagener, T. (2015). A simple and efficient method for global sensitivity analysis based on cumulative distribution functions. Environmental Modelling & Software, 67, 1-11. https://doi.org/10.1016/j.envsoft.2015.01.004

- Vogel, R. M., & Sankarasubramanian, A. (2003). Validation of a watershed model without calibration. Water Resour. Res., 39(1292). https://doi.org/10.1029/2002WR001940

