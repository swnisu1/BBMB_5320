# BBMB 5320 – Enzyme kinetics widgets

## When Michaelis–Menten breaks (`when-michaelis-menten-breaks/`)

Interactive simulation showing why the Michaelis–Menten equation fails when
[E]<sub>total</sub> is not ≪ [S] + K<sub>m</sub>: substrate bound as ES is no
longer negligible, so [S]<sub>free</sub> ≠ [S]<sub>total</sub>. This is common
with low-K<sub>m</sub>, low-activity enzymes, where it is tempting to add more
enzyme to shorten the time course.

Simulated initial-rate data (exact steady-state rate for total substrate, with
adjustable noise) are fit with both the MM equation and the quadratic (Morrison)
equation. Students can adjust true K<sub>m</sub>, [E]<sub>total</sub>,
k<sub>cat</sub>, the [S] range, number of points and noise, and see:

- the error in fitted K<sub>m</sub> for both models, as a ratio (fitted/true)
  or % difference, against [E]<sub>total</sub>/K<sub>m</sub>
- the rate data with both fits, optionally replotted against true [S]<sub>free</sub>
- the fraction of substrate that is free across the [S] range
- the progress curve, compared with a "safe" enzyme concentration

Open `when-michaelis-menten-breaks/index.html` in any browser (no install or internet needed), or enable
GitHub Pages for the repository.

With GitHub Pages enabled (Settings → Pages → deploy from `main`, root), the
widget is at <https://swnisu1.github.io/BBMB_5320/when-michaelis-menten-breaks/>
and the repository root shows a list of widgets.
