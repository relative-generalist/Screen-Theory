# Screen Theory: Technical Session Summary
### March 2026 — P.A.I. Reilly and F. McCaul
### Working notes, not for circulation

---

## 1. Core Equation (unchanged)

$$\frac{dC}{d\tau} = \frac{2\pi Mc^2}{\hbar}$$

Mass $M$ generates irreversible classical information at the Compton rate per
unit proper time. This is the central quantitative claim. Everything below
is either a consequence or a motivated conjecture.

---

## 2. The α=2π Argument: Reordering (Pending Paper Rewrite)

**Current state in paper v0.9:** α fixed by matching to Schwarzschild, then
confirmed by Bekenstein. Logically: derive → match → confirm.

**Agreed reordering:** Fix α from Bekenstein first, then show this produces
the correct Schwarzschild metric. Logically: derive → fix → predict.

The Bekenstein bound in natural units ($\hbar = c = 1$):

$$S_\text{Bek} = 2\pi Mr$$

Information in transit from a mass $M$ to a sphere at radius $r$, with
generation rate $dC/d\tau = \alpha Mc^2/\hbar$:

$$\Delta C = \frac{\alpha Mc^2}{\hbar} \cdot \frac{r}{c} = \frac{\alpha Mcr}{\hbar} = \alpha Mr \quad \text{(natural units)}$$

Setting $\Delta C = S_\text{Bek}$ requires $\alpha = 2\pi$. This fixes the
free parameter from the Bekenstein bound alone, without reference to
Schwarzschild. The Schwarzschild metric is then a prediction, not a matching
condition.

**Revised derivation order:**
1. State H with free parameter $\alpha$
2. Apply Bekenstein bound at the Compton scale → $\alpha = 2\pi$
3. Derive $g_{rr}$ from area excess → exact Schwarzschild radial component
4. Schwarzschild matching is then confirmation, not definition

---

## 3. Derivation of g_rr (unchanged, reordered presentation)

Information in transit between mass $M$ and sphere at radius $r$:

$$\Delta C = \frac{2\pi Mcr}{\hbar}$$

Required holographic area (A3: each nat requires $4\ell_P^2$):

$$\Delta A = 4\ell_P^2 \cdot \Delta C = \frac{8\pi GMr}{c^2} = 2r_S r$$

where $r_S = 2GM/c^2$. Physical sphere area is $4\pi r^2$; unstretched area is
$4\pi r^2 - \Delta A$:

$$g_{rr} = \frac{4\pi r^2}{4\pi r^2 - 2r_S r \cdot (2\pi/2\pi)}
= \frac{1}{1 - r_S/r}$$

Exact Schwarzschild radial component. No field equations used.

**Fractional holographic saturation:**

$$\frac{S_\text{Bek}}{S_\text{max}} = \frac{2\pi Mr}{\pi r^2/G} = \frac{r_S}{r}$$

$$\frac{dr}{d\ell} = \sqrt{1 - \frac{r_S}{r}} = \sqrt{1 - \frac{S_\text{Bek}}{S_\text{max}}}$$

The ratio of coordinate to proper radial length is the square root of the
unsaturated holographic fraction. At $r = r_S$: saturation complete, $g_{rr}$
diverges. The horizon is the surface of complete holographic saturation.

**G reinterpreted:**

$$G = \frac{\ell_P^2 c^3}{\hbar}$$

$G$ is not a fundamental coupling constant but an exchange rate between
Planck area and quantum of action.

---

## 4. g_tt (Conjecture, Paper I)

For static spherically symmetric metric $ds^2 = -A(r)dt^2 + B(r)dr^2 + r^2 d\Omega^2$
with $B(r) = (1-r_S/r)^{-1}$ established, write:

$$A(r) = e^{2\Phi(r)}\left(1 - \frac{r_S}{r}\right), \quad \Phi(r) \to 0 \text{ as } r \to \infty$$

General asymptotic expansion: $\Phi(r) = \beta/r + \gamma/r^2 + \cdots$

**Conjecture (A4, minimality):** No source present for any nonzero coefficient,
therefore $\Phi(r) = 0$ identically, giving $g_{tt} = -(1 - r_S/r)$.

Status: conjecture in Paper I; derived as theorem in Paper II via Einstein equations.

---

## 5. Wholographic Principle and A2

**Wholographic bound** (correction to holographic): threads pass *through*
a surface, not merely into it. The bound $S_\text{max} = A/4\ell_P^2$ counts
threads crossing the surface in both directions.

**Thread picture derivation of A2:** Each thread has cross-sectional area
$\sim \ell_P^2$. Saturation near matter means threads are packed at one per
$4\ell_P^2$ (Bekenstein coefficient = packing geometry factor). A2 is then
not an assumption but a consequence of thread geometry near a mass source.

---

## 6. Dark Energy from Thread Tension

**Key result:**

$$\boxed{\lambda_\text{dark} = \sqrt{4\ell_P r_H}}$$

**Numerical check:**

$$\lambda_\text{dark} = \sqrt{4 \times 1.616\times10^{-35} \times 1.28\times10^{26}}
\approx 9.1 \times 10^{-5}\ \text{m} = 0.091\ \text{mm}$$

$$\rho_\Lambda = \frac{\hbar c}{\lambda_\text{dark}^4}
= \frac{3.16\times10^{-26}}{(9.1\times10^{-5})^4}
\approx 4.6 \times 10^{-10}\ \text{J/m}^3$$

Observed: $\rho_\Lambda^\text{obs} \approx 5.4 \times 10^{-10}$ J/m³.
Agreement within 15%, no free parameters.

**The $10^{122}$ resolution:**

$$\frac{\rho_\Lambda}{\rho_\text{Planck}} = \frac{\ell_P^4}{\lambda_\text{dark}^4}
= \frac{\ell_P^2}{16 r_H^2} \approx 9\times10^{-123}$$

The hierarchy is the square of the ratio of Planck length to Hubble horizon —
a geometric statement about thread configuration, not a fine-tuning.

**Stationary-phase argument (conjecture):**

Thread action with bulk propagation cost and endpoint localization cost:

$$S[\lambda] = \frac{\hbar r_H}{\lambda} + \frac{\hbar\lambda}{\ell_P}$$

Minimizing: $\lambda^2 = \ell_P r_H$, giving $\lambda_\text{dark} = \sqrt{\ell_P r_H}$
(factor of 4 from Bekenstein coefficient). Status: conjecture; action form motivated
but not derived from thread tension first principles.

**The $\pi/2$ conjecture:** $1.53 \approx \pi/2 = 1.571$ (2.5% off) suggests:

$$\lambda_\text{dark} = \sqrt{2\pi\ell_P r_H}$$

which would give exact resonance with the CMB throughout the radiation era,
connecting to the $2\pi$ in the Bekenstein bound. Status: conjecture.

---

## 7. Dark Energy as Function of Cosmic Time

Thread characteristic wavelength evolves as:

$$\lambda_\text{dark}(t) = \sqrt{4\ell_P c / H(t)}$$

Implied dark energy density:

$$\rho_\Lambda(t) = \frac{\hbar c}{\lambda_\text{dark}(t)^4}
= \frac{\hbar H(t)^2}{16\ell_P^2 c}$$

**$\rho_\Lambda \propto H^2$ tracks matter density during matter domination.**
The coincidence problem dissolves: dark energy has always been a fixed fraction
of total density, not a special feature of the present epoch.

**Equation of state:** During tracking epochs $w_\Lambda \approx w_\text{dominant}$
(not $-1$). Transition to $w = -1$ at de Sitter freezing when $H \to H_\infty$.

**Prediction:** $w \neq -1$ during matter domination, systematic deviation
detectable by DESI/Euclid.

---

## 8. CMB Comparison and the Epoch Calculation

CMB peak (Wien's law): $\lambda_\text{CMB} = b/T = 2.898\times10^{-3}/2.725
\approx 1.06$ mm.

Ratio today: $\lambda_\text{CMB}/\lambda_\text{dark} \approx 12$.

**Scaling laws:**
- Radiation domination: $H \propto a^{-2}$, $r_H \propto a^2$,
  $\lambda_\text{dark} \propto a$ — same as CMB.
- Matter domination: $H \propto a^{-3/2}$, $r_H \propto a^{3/2}$,
  $\lambda_\text{dark} \propto a^{3/4}$ — slower than CMB.

**Frozen ratio during entire radiation era:**

$$R_\text{radiation} = 11.7 \times a_\text{eq}^{1/4}
= 11.7 \times (2.94\times10^{-4})^{1/4} \approx 1.53$$

The entire factor of 12 visible today accumulated during matter domination.
Throughout the radiation era — Big Bang through recombination — the two
scales agreed to within a factor of 1.53.

Factor of $(1 + z_\text{recomb})^{1/4} \approx 1100^{1/4} \approx 5.75$
accounts for most of the post-recombination divergence.

**Physical interpretation:** $\lambda_\text{dark}$ and $\lambda_\text{CMB}$
were in resonance throughout the epoch when photons and matter were in thermal
equilibrium. They parted ways at decoupling. The universe became transparent
at exactly the moment the harp's characteristic frequency and the thermal
photon frequency diverged.

---

## 9. Thread Geometry and Spacetime Points

**V/U thread geometry:**

```
H1                    H2
 |                     |
 P                     Q
  \                   /
   \                 /
    \_____________/
           U
      (spacelike segment ~ℓ_P)
```

Both arms run to the horizon. The spacelike segment at U is the R-event.
Shape determined globally by path integral subject to horizon boundary
conditions at P and Q. Irreversibility is topological: cannot remove the
bend without pulling both endpoints from the horizon simultaneously.

**Twistor correspondence:**

One twistor (one point in CP³) = one null geodesic in spacetime.

Two twistors = one line in CP³ = one spacetime point.

Therefore: **two crossing threads define exactly one spacetime point.**
Three twistors define a plane (CP²) in twistor space = three pairwise
null-separated events (a triangle, not a point).

Spacetime points are composite objects defined by thread crossings.
Low thread density → poorly defined points. Near mass → high thread
density → well-defined local geometry. Mass creates well-defined points
by maintaining high crossing density at the Compton rate.

---

## 10. Complex Reilly Information and Thread Area

$$\Delta K = -\log\psi = \log(1/|\psi|) - iS/\hbar$$

Real part: classical improbability (what Born rule reads off).
Imaginary part: full phase history, total accumulated action along thread.

**Thread area = K:** Thread cross-sectional area (in units of $\ell_P^2$)
equals the Reilly information of the event that generated the thread.

**Complexity as action:** The path integral $\int e^{iS/\hbar}\mathcal{D}\text{path}$
is $\int e^{i\text{Im}(\Delta K)}\mathcal{D}\text{path}$. Stationary phase
$\delta K = 0$ selects the classical path. Minimizing complexity =
minimizing action = the classical path.

**Thread area conservation at the Apex:**

A split thread on two arms of a beam splitter carries area $-\log|ψ|²$ on
one arm and $-\log|1-|ψ|²|$ on the other. At the Apex, one arm receives
all the area. The Born rule $P \sim |ψ|²$ is thread area conservation at
the R-event. Open problem 6 is looking closeable.

**ℏ as threshold, not minimum:** Sub-threshold crossings ($< \hbar$ information
transfer) accumulate continuously as virtual crossings constituting fields.
Classical fields are high-density sub-threshold crossing distributions.
An R-event is a crossing that exceeds the threshold — a cut in the film.
Decoherence is sub-threshold accumulation until threshold is crossed.

---

## 11. The Propagator and Junction Reconciliation

At each vertex, incoming momentum $p_\text{in}$ and outgoing $p_\text{out}$
differ by $q^\mu = p_\text{in}^\mu - p_\text{out}^\mu$. The virtual thread
carries this discrepancy to the other junction and deposits it exactly.
Momentum conservation is the checksum on the message, not the message itself.

Feynman propagator:

$$D(q) = \frac{1}{q^2 - m^2 + i\varepsilon}$$

Thread interpretation:
- Large when $q^2 \approx m^2$ (nearly on-shell, resonance, efficient carrier)
- Small when $q^2 \gg m^2$ (far off-shell, reluctant carrier)
- Pole at $q^2 = m^2$: crossing threshold, virtual becomes real, R-event fires

The $i\varepsilon$ prescription encodes the finite width of the R-event
threshold — not a mathematical trick but the temporal extent of the crossing.

Full phase: $S = p \cdot x$ = (words per page) × (number of pages) =
total information content of thread biography. $\hbar$ = threshold below
which a page does not register as a new classical entry in the record.

---

## 12. Color Force: Twist, Writhe, and Confinement

**Color charge = over-twist.** A quark is an over-twisted thread. The
over-twist is the structural feature that makes baryon formation topologically
possible.

**Confinement from endpoint constraint:** A colored thread has no valid
horizon endpoint — the horizon is color-neutral. Therefore:
- Meson: quark-antiquark, color-anticolor pair, thread with two endpoints
- Baryon: three quarks (R+G+B), color-neutral triple crossing, valid endpoint
- Gluon: color-anticolor, closed loop, no net color endpoint required

Confinement is topological, not dynamical.

**Flux tube string tension:** Linear confinement potential $V(r) \sim \sigma r$
where $\sigma \approx 1$ GeV/fm is the color thread tension. String breaking
at threshold $\sim 2m_q$: snap-back energy = new quark-antiquark pair rest mass.

**Snarling = pair production:** Twist-to-writhe conversion when tension
released. In topology: twist + writhe = linking number (conserved).
Releasing tension converts stored twist to writhe — virtual pairs popping up
as snarls along the flux tube length.

**Asymptotic freedom = thread alignment under tension:**

Taut thread → internal degrees of freedom aligned → low internal entropy →
low confirmation threshold → strong coupling.

Slack thread → internal degrees of freedom disordered → high internal entropy →
high confirmation threshold → weak coupling.

The beta function of QCD is a statistical mechanics calculation about
internal thread entropy as a function of tension, not merely a loop integral.

**QCD string tension vs. Planck tension:**

$\sigma \approx 1.6\times10^5$ N; $T_\text{Planck} = \hbar c/\ell_P^2 \approx 10^{44}$ N.

$$\sigma/T_\text{Planck} \approx 10^{-39}$$

Flux tube cross-sectional area $\sim 1$ fm² contains $\sim (10^{-15}/10^{-35})^2 = 10^{40}$
Planck areas. Ratio off by one order of magnitude — likely closed by factor
of 3 (number of color threads) or 9 (= 3²). Needs working out.

---

## 13. The Pringle/Theorema Egregium Argument

**Unitary evolution assumes a fixed metric.** The Schrödinger inner product
$\langle\psi|\phi\rangle$ is preserved under U-processes. That inner product
presupposes a fixed measure, fixed volume element, fixed metric.

**$R_{\mu\nu}$ requires a dynamic metric.** The Ricci tensor is the geometric
record of area growth events. You cannot simultaneously demand unitarity
(fixed metric) and Ricci curvature (dynamic metric).

**Gauss's Theorema Egregium:** A surface of nonzero Gaussian curvature has
no isometric embedding in flat space. Trying to reconcile curved-spacetime QFT
with a flat Hilbert space inner product is literally trying to flatten a
non-flattenable surface. Possible locally (normal coordinates) but not globally.
The UV divergences of perturbative quantum gravity are the infinities generated
by the attempt to flatten the Pringle.

**Implication:** The measurement problem is not a measurement problem. It is
a geometry problem. Demanding R-events be reducible to U-processes
(the Everettian programme) is demanding that curvature be reducible to flatness.
The wall quantum gravity has been beating its head against is this one.

---

## 14. Ricci vs. Weyl: Screen and Picture

$$\text{Riem}_{\mu\rho\nu\sigma} = \text{Ricci component} + C_{\mu\rho\nu\sigma}$$

**Ricci tensor $R_{\mu\nu}$:** Depends on thread density and fatness.
Describes the geometry of the screen — its curvature, its capacity, how much
information it can hold per unit area. Set to zero in vacuum; responds to
local matter via Einstein equations.

**Weyl tensor $C_{\mu\rho\nu\sigma}$:** Depends on thread content and
crossing topology — the specific information threaded through the geometry.
Describes the picture on the screen. Nonzero in vacuum (gravitational waves,
tidal forces, long-range Coulomb structure of gravity). Propagates according
to:

$$\nabla^\sigma C_{\mu\rho\nu\sigma} = J_{\mu\rho\nu}$$

where $J_{\mu\rho\nu}$ is sourced by Ricci gradients. The picture moves
across the fabric driven by the edges of the weave pattern.

**Conformal invariance of Weyl:** Under $g_{\mu\nu} \to \Omega^2 g_{\mu\nu}$,
$C_{\mu\rho\nu\sigma}$ is unchanged. In thread terms: scaling thread
cross-sectional area by $\Omega^2$ while keeping crossing topology fixed
is a conformal transformation. The picture survives; only the fabric size changes.

**Two-tier conservation structure:**
- Bianchi identity: conserves total thread count (amount of fabric)
- Weyl propagation equation: governs how the picture moves (specific content)

---

## 15. Born Rule from Thread Area (Open Problem 6)

Split thread on beam splitter arm carries area:

$$A_\text{arm} = -\log|\psi_\text{arm}|^2 = K_\text{arm}$$

At the Apex R-event, one arm receives all the thread area. The probability
of that arm being selected is $|\psi|^2$ — the arm with lower $K$ (higher
$|\psi|^2$, lower improbability) is selected with higher probability.

Born rule $P \sim |\psi|^2$ is thread area conservation at the Apex.
The less improbable thread carries more area and is selected more often.
This closes open problem 6 if the area conservation law can be derived
from the thread action. Status: candidate derivation.

---

## 16. Summary of Open Problems from This Session

| # | Problem | Status |
|---|---------|--------|
| — | Reorder α=2π argument in Paper I | Action item |
| — | Rewrite abstract, intro, conclusion of Paper I | Action item |
| 1 | Full Einstein equations from thread continuity | Long-term |
| 4 | Weyl propagation as no-torn-seams | Partially developed |
| 5 | Fubini-Study metric for Wholographic Principle | Flagged |
| 6 | Born rule from thread area conservation | Candidate derivation above |
| — | Derive stationary-phase action $S[\lambda]$ properly | Medium-term |
| — | Confirm/derive $\lambda_\text{dark} = \sqrt{2\pi\ell_P r_H}$ | Medium-term |
| — | $w \neq -1$ prediction vs. DESI/Euclid | Check against data |
| — | SU(3) from three-strand plying geometry | Long-term |
| — | Weinberg angle as plying angle | Long-term |
| — | QCD string tension from thread tension × Planck areas | Medium-term |
| — | Bilson-Thompson correspondence | Flagged for follow-up |
| — | Twistor correspondence for non-null threads | Consult Sparling |

---

*Technical session summary, March 2026.*
*Equations marked (conjecture) need derivation before publication.*
*Equations without that marking are either derived in existing papers*
*or follow directly from the core hypothesis by the chain H→A1→A2→A3→A4.*
