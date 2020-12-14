The files in this directory have 4 columns each, namely:
temperature/K pressure/bar deltaMu1/meV deltaMu2/meV

deltaMu1 and deltaMu2 are NQE corrections relative to ice II, computed using two different integration schemes.

deltaMu1 corresponds to a fit of the integrand in the thermodynamic integration a given temperature and pressure to b*x+c*x*x+d*x**3 integrated numerically from 0 to 1.

deltaMu2 corresponds to the same quantity, but integrated using Simpson's rule.
