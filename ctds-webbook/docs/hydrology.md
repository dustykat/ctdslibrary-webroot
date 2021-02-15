# Hydrology

This is currently a placeholder file, a suitable example problem would be to deconvolve a rainfall-runoff signal and parameterize a response kernel (unit hydrograph) , provided input precipitation and output runoff.

The example would contain links to a database with training events, then a few challenge events.

Entire problem can be done in JupyterLab/Python as per WCOE vision.

### Check Typeset

\begin{equation}
Q(t) = A \cdot \int_{0}^{t}{P(t-\tau)U(\tau)d \tau}
\end{equation}