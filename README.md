The notebook models the height of the Greenland Ice Sheet (h) over time.
The ice sheet evolves according to a differential equation that balances precipitation input (P) (ice accumulation), runoff/melt (depends on temperature T(t)), dynamic thinning/flow factor (F·h).

The simulation scenarios are for multiple initial heights and different climate forcing.
The outputs are the time series of the ice sheet height, equilibria and their stability, what year the tipping point is reached, and the sea level rise as a result of melting.

This is a nonlinear dynamical system with bifurcations.

As warming increases, the high equilibrium shrinks and disappears.

Beyond this critical threshold, the ice sheet cannot recover and so it inevitably collapses.
This represents a climate tipping point.
The differential equation is numerically solved (ODE integration with solve_ivp), allowing exploration of long-term nonlinear behavior.

The simulation shows:
Path dependence (different starting heights lead to different fates), disappearance of equilibria as climate warms → hysteresis (no way back), quantification of timescales (how many centuries to collapse).
