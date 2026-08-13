# Techno-economics of Ethane Cracker

A screening cost model for an ethane cracker. Single self-contained HTML file, no external dependencies.

**[robin-yk.github.io/Techno-economics](https://robin-yk.github.io/Techno-economics/)**

Degrees of freedom sit at the reactor and nowhere else. Coil outlet temperature, residence
time, steam dilution, capacity and heating efficiency are set; conversion follows from
first-order pyrolysis kinetics and selectivity falls as conversion climbs. The three
downstream columns hold fixed product specifications (99.9 mol% ethylene, 99.5% cold box
recovery) and re-solve, so reflux ratio is an output rather than an input.

| Tab | Contents |
|---|---|
| plant | Process flow diagram and cost breakdown |
| cost ladder | Accumulation from the stoichiometric floor to the final cost |
| carbon | Carbon intensity from the same inventory, by scope, with grid factor, tail gas fate and co-product handling |
| fired vs Joule | Both heating routes and the break-even power price |
| sensitivity | Tornado at ±10%, clamped to validated ranges |
| balances | Carbon, hydrogen, mass and energy residuals; fixed specifications |
| explained | Every figure on the page written out in plain English, with each term defined at first use |

Cost and carbon come from one inventory. Prices give the cost of ethylene; emission factors
give the carbon intensity. Two results that follow from the same mass and energy balance.

Screening estimate, AACE Class 5, ±40%. The output to read is the accumulation, not the
absolute figure. Known gaps are stated on the page: capital is correlation based, the
byproduct split is uncalibrated, and dilution steam carries no counterpart cost.

---

`ethane-cracker-tea-lab.html` was an attempt to reconstruct the TEA in Mittal, Kwak et al.,
*Chem. Eng. J.* 523 (2025) 168251. The published information is not sufficient to reproduce
it, so the work stopped and the file is not linked from the site. The audit is in
[`TEA_tool_selfcheck.md`](TEA_tool_selfcheck.md).
