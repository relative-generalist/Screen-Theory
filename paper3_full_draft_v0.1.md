# The Universe as Accumulated Record: Information Generation, Cosmic Expansion, and the Arrow of Time

**Paul A. I. Reilly**

*Independent researcher, Pittsburgh, Pennsylvania*

*Preprint v0.1 — priority established. Submitted to GitHub 2026-03-09. Comments welcome.*

*This paper is the third in a series. Paper I: "Reflections on Two Moving Mirrors." Paper II: "On the Nature of Mass: Complexity Generation and Spacetime Curvature."*

---

## Abstract

*[To be written after all sections are finalised. Mission: show that
cosmic expansion is matter-driven area expansion, that information
supply matches geometric demand at the causal boundary if and only if
$w = 0$ and $\Omega = 1$ simultaneously, and that the vacuum energy
catastrophe dissolves as a category error once irreversibility is
properly accounted for.]*

---

## 1. Introduction: The Universe as Accumulated Record

*[To be written last. Key points: Papers I and II established the
local picture — mass generates irreversible information; geometry
accommodates it. This paper asks what that means at cosmic scales.
The universe is not a stage on which physics happens; it is a record
of what has happened. Every patch of space is built from R-process
data originating in its causal past, and constitutively entangled
with the rest of the universe through the complementary streams of
those R-processes (full development in the companion Wholographic
paper). We introduce the EdS universe as our spherical cow and state
clearly what it omits. Roadmap follows.]*

---



## The Information Generation Rate for Pressure-Supporting Matter


Paper~II derived the Einstein field equations for pressureless dust
by identifying the information generation rate $J$ with the
null-null contraction of the stress-energy tensor.
Before applying Screen Theory to cosmology, we must generalize this
identification to matter with nonzero pressure, since the radiation
era --- the focus of subsequent sections --- is pressure-dominated.
The generalization is immediate and requires no new assumptions.


### Derivation


Paper~II established two expressions for the null-null Ricci
contraction $R_{\mu\nu}k^\mu k^\nu$ evaluated on a null vector
$k^\mu$: one from the information side,

$$
  R_{\mu\nu}k^\mu k^\nu = 4G\,J,
  
$$

and one from the geometric side via the Einstein field equations,

$$
  R_{\mu\nu}k^\mu k^\nu = 8\pi G\,T_{\mu\nu}k^\mu k^\nu.
  
$$

Combining equations~\eqref{eq:info_side} and~\eqref{eq:geom_side}
gives immediately

$$
  J = \frac{2\pi}{\hbar}\,T_{\mu\nu}k^\mu k^\nu.
  
$$

For a perfect fluid with stress-energy tensor
$T_{\mu\nu} = (\rho + p)u_\mu u_\nu + p\,g_{\mu\nu}$,
the null-null contraction reduces to

$$
  T_{\mu\nu}k^\mu k^\nu
  = (\rho+p)(u_\mu k^\mu)^2 + p\,g_{\mu\nu}k^\mu k^\nu
  = (\rho+p)(u_\mu k^\mu)^2,
$$

since $k^\mu$ is null: $g_{\mu\nu}k^\mu k^\nu = 0$.
Choosing the affine normalization $u_\mu k^\mu = 1$,
which is a convenient parametrization with no physical content
(rescaling $k^\mu \to \lambda k^\mu$ rescales both sides of
equation~\eqref{eq:geom_side} by $\lambda^2$ and leaves the
physics unchanged), yields the central result of this section:

$$

$$J = \frac{2\pi(\rho + p)}{\hbar} \tag{1}$$

  
$$


\subsection{Physical interpretation: the timelike component
            of energy-momentum flow}


The formula~\eqref{eq:J_fluid} has a physical interpretation
that is not obvious from the algebra alone, and which bears
directly on the application to the radiation era.

The key distinction is between null and timelike energy-momentum
flow.
A single photon propagates on a null worldline.
The proper time elapsed between any two events on its path is zero:
$d\tau = 0$ everywhere.
The rate $dC/d\tau = 2\pi mc^2/\hbar$ is finite for massive
particles precisely because proper time accumulates along their
worldlines.
For a single photon there is no accumulated proper time in which
to generate irreversible information.
Individual photon propagation is a U-process; it contributes
$J = 0$.

The situation changes for a collection of non-collinear photons.
Two photons moving in opposite directions have a center of mass
that moves on a *timelike* worldline, even though each
photon individually moves on a null worldline.
Their combined invariant mass is nonzero:

$$
  M^2 c^4 = \left(\sum_i E_i\right)^2
            - \left|\sum_i \vec{p}_i\right|^2 c^2 > 0,
$$

and proper time accumulates along the center-of-mass worldline.
The composite system has a timelike degree of freedom that
individual photons lack.

For an isotropic photon gas --- which is precisely what thermal
radiation is --- momenta cancel statistically in every direction,
the center of mass is at rest in the fluid frame, and the
invariant mass is maximal for the given energy density.
The gas is as timelike as a massive particle.
It generates irreversible information at a rate proportional to
its invariant mass, which is why equation~\eqref{eq:J_fluid}
gives $J \neq 0$ for the radiation fluid.

The physical R-processes that cash out this information generation
are the thermalization scatterings --- Compton scattering off
electrons, photon-photon interactions --- that maintain the
correlations constituting the fluid's invariant mass.
Without these scatterings, photons would free-stream and their
momenta would no longer cancel isotropically; the collective
timelike character of the gas would dissolve.
The information generation rate of the radiation fluid is
sustained by the scatterings that keep it thermalized, not by
individual photon propagation.

This gives a precise physical reading of the enthalpy density
$(\rho + p)$.
It is exactly the measure of timelike energy-momentum flux
through null surfaces.
For a single photon moving in the null direction of $k^\mu$,
$T_{\mu\nu}k^\mu k^\nu = 0$ and $J = 0$: null propagation
contributes nothing.
For an isotropic radiation fluid, $T_{\mu\nu}k^\mu k^\nu
= \frac{4}{3}\rho$ and $J = \frac{8\pi\rho}{3\hbar}$:
the timelike collective motion contributes fully.
The formula is not selecting an arbitrary contraction of the
stress-energy tensor.
It is selecting precisely the timelike component of
energy-momentum flow, which is the component capable of
accumulating proper time and generating irreversible information.

The Lorentzian trace $T = g^{\mu\nu}T_{\mu\nu} = -\rho + 3p$
encodes the same distinction from a different angle.
The metric signature $(-,+,+,+)$ means temporal and spatial
contributions enter $R$ with opposite signs; only their imbalance
generates scalar curvature and drives the accumulation of
Capital-T~Time.
For dust ($p=0$), the imbalance is maximal: pure temporal
accumulation, maximum $R$ per unit energy density.
For radiation ($p = \rho/3$), $T = 0$ and $R = 0$: the temporal
and spatial contributions cancel in the Ricci scalar, even though
$J \neq 0$.
Radiation generates irreversible information through its timelike
collective motion, but that information does not show up as
scalar curvature.


*[Table: see LaTeX source]*


The radiation row of Table~[ref:tab:cases] deserves particular
emphasis for what follows.
Radiation is informationally active --- $J \neq 0$, irreversible
outcomes are being generated, the holographic record is being
written --- but geometrically quiet in the scalar sense: $R = 0$.
The radiation era is therefore a regime in which the holographic
record is accumulating without the scalar curvature signal that
most directly tracks Capital-T~Time in the matter era.
This tension between high $J$ and vanishing $R$ is precisely
what makes the radiation era the frontier of the present
framework, and motivates the open questions of
Section~[ref:sec:open].



---



## 3. The Cosmological Origin of Space

### 3.1 Where does holographic capacity come from?

Paper I derived the Schwarzschild metric by assuming that the vacuum near
matter operates at holographic saturation (Assumption A2): newly generated
information requires a corresponding increase in the area of bounding
surfaces. The assumption was presented there as a local statement about the
vacuum near an isolated mass. In the cosmological setting, this assumption
demands a global account. Why does empty space have holographic capacity at
all? Where did the capacity come from?

The standard answer treats spacetime as a fixed background — ordained, not
earned. Space exists, and its holographic capacity is a property it has by
virtue of existing. This is geometrically consistent but ontologically
unsatisfying, and it offers no explanation of why the holographic capacity
of the observable universe is matched, to order unity, to the information
content of the matter within it. That match could be a coincidence. We
argue it is not.

The alternative, which we adopt here, is Machian: spacetime capacity is not
ordained but accumulated. The holographic area available at any location is
generated by the irreversible information production of all matter in that
location's causal past. Space is not the stage on which matter performs; it
is the accumulated record of matter's performance. This section makes that
claim quantitative.

### 3.2 The holographic Olbers integral

Consider our current location at cosmic time $t_0$. The causal past of this
event is the interior of the past light cone stretching back to the Big Bang.
Every mass element in this region has been generating irreversible
information at rate $J = 2\pi\rho c^2/\hbar$ per unit volume throughout its
history. The total area required to accommodate this information is:

$$A_{\rm required} = 4\ell_P^2 \int_{\rm past\ light\ cone} J\, d^4x$$

where $4\ell_P^2$ is the Bekenstein area per nat (Assumption A3 of Paper I)
and the integral runs over the four-volume of the past light cone. This is
the holographic analog of Olbers' integral for the total light received from
all sources in the observable universe — here we are integrating information
flux rather than electromagnetic flux.

For an Einstein-de Sitter universe — spatially flat, matter-dominated, the
idealization that captures the matter era cleanly — the Friedmann equation
gives $\rho(t) = 1/(6\pi G t^2)$, and the particle horizon sits at physical
radius $r_{\rm ph} = 3ct_0$ at the present epoch. Evaluating the integral
over the causal volume with the time-averaged density:

$$A_{\rm required} \sim 4\ell_P^2 \cdot \frac{2\pi\rho(t_0)c^2}{\hbar}
\cdot \frac{4\pi}{3}(3ct_0)^3 \cdot t_0$$

The factors of $G$ and $\hbar$ cancel identically — $\ell_P^2 = G\hbar/c^3$
absorbs the $\hbar$ in the denominator of $J$, and $G$ cancels against the
$G$ in $\rho = 1/(6\pi G t^2)$. What remains is pure geometry:

$$A_{\rm required} = 48\pi c^2 t_0^2 \tag{5}$$

The holographic area of the particle horizon is:

$$A_{\rm horizon} = 4\pi r_{\rm ph}^2 = 4\pi(3ct_0)^2 = 36\pi c^2 t_0^2$$

The ratio is:

$$\frac{A_{\rm required}}{A_{\rm horizon}} = \frac{48}{36} = \frac{4}{3} \tag{6}$$

Order unity, no free parameters, $G$ and $\hbar$ both absent from the
result. The matter in the observable universe has generated, over its causal
history, exactly the holographic area required to accommodate that
information — to within a geometric factor of order unity that will shift
when the proper past-light-cone integral is evaluated carefully, but will
remain of order unity by the same cancellation argument.

This is not a coincidence. It is the cosmological statement of holographic
saturation (Assumption A2): the vacuum operates at saturation because matter
has been filling it to saturation throughout the history of the universe. The
capacity is there because the matter put it there.

### 3.3 The Copernican character of the result

The integral was written for our location at $t_0$, but nothing in the
argument is specific to us. Every location in the universe is the unique
locus of convergence of its own complete causal history. Every observer
performs the same integral over their own past light cone and arrives at the
same order-unity ratio. No location is privileged; no location is
informationally starved.

This is the cosmological version of what-where symmetry: the holographic
capacity available at any point is generated by the matter visible from that
point, and the matter visible from that point is precisely the matter whose
information that point is equipped to receive. Content and capacity are
mutually constituted. The screen is jointly epic with respect to every
observer simultaneously.

### 3.4 Intellectual lineage

The structure of this argument is old. Leibniz argued that space is
relational — not a container in which matter sits, but a system of relations
among material things. Mach argued that inertia itself is generated by the
cosmic distribution of matter: a body's resistance to acceleration reflects
its gravitational relationship to everything else in the universe. Sciama
gave Mach's principle quantitative form, showing that the inertial frame is
determined by an integral over all matter in the observable universe weighted
by $1/r$ — structurally identical to a Newtonian gravitational potential
summed over all sources.

The holographic integral of Section 3.2 is the same animal. Instead of
summing the gravitational influence of distant matter to determine inertia,
we are summing the information generation of all past matter to determine
available holographic capacity. The Sciama integral and our integral are
structurally identical: both assert that local properties of spacetime
(inertia there, holographic capacity here) are generated by the integral
over all causally accessible matter.

The difference is that Screen Theory makes this precise in the language of
information geometry: the area of spacetime is the accumulated record of
irreversible outcomes. Spacetime is not ordained. It is earned, region by
region, from the irreversible decisions of matter.

### 3.5 Ontological summary

Space is the holographic record of settled questions. Its area at any
location is the area required to accommodate the irreversible information
generated by everything in that location's causal past. The vacuum's
holographic capacity is not a property of empty space; it is the legacy of
the matter that made the space what it is.

This reframes the fine-tuning questions of standard cosmology. The flatness
problem asks why the universe has exactly the critical density. The
holographic Olbers integral suggests an answer: critical density is the
condition under which matter generates exactly the holographic capacity of
the horizon it inhabits — supply matches demand. We develop this in the
following section.


---



## 4. Information Balance and the Expansion Rate

Section 3 established that the holographic capacity of the observable
universe is generated, to order unity, by the matter within it. This
section asks the dynamical question: does the expansion rate of the
universe maintain that match over time? We define a balance ratio
comparing the rate at which matter generates information-area to the
rate at which the universe generates geometric area through expansion,
compute it for a general flat FLRW cosmology, and find that the
condition of persistent balance is satisfied if and only if two
apparently independent properties hold simultaneously: the equation of
state is that of pressureless matter ($w = 0$) and the universe is
spatially flat ($\Omega = 1$). In standard cosmology these appear as
separate coincidences requiring separate explanations. Here they are
two projections of a single information-geometric consistency
condition.

### 4.1 The balance ratio

Define the instantaneous balance ratio:

$$B(t) \equiv \frac{dA_{\rm info}/dt}{dA_{\rm geom}/dt}$$

where $dA_{\rm info}/dt$ is the rate at which matter generates
holographic area (information converted to area via the Bekenstein
factor $4\ell_P^2$ per nat), and $dA_{\rm geom}/dt$ is the rate at
which the physical area of a bounding sphere grows through Hubble
expansion.

For a sphere of physical radius $r$ in a flat FLRW cosmology with
equation of state $w$, the Friedmann equation gives
$H = 2/[3(1+w)t]$ and $\rho = 1/[6\pi G(1+w)^2 t^2]$.
The rate of information-area generation within the sphere is:

$$\frac{dA_{\rm info}}{dt}
= 4\ell_P^2 \cdot J \cdot \frac{4\pi r^3}{3}
= 4\frac{G\hbar}{c^3} \cdot \frac{2\pi(1+w)\rho c^2}{\hbar}
  \cdot \frac{4\pi r^3}{3}$$

The factor of $\hbar$ cancels immediately, and substituting $\rho$
causes $G$ to cancel as well:

$$\frac{dA_{\rm info}}{dt} = \frac{16\pi r^3}{9c(1+w)t^2}$$

The rate at which the sphere's boundary area grows through Hubble
expansion is:

$$\frac{dA_{\rm geom}}{dt}
= 8\pi r \cdot \dot{r} = 8\pi r \cdot Hr
= \frac{16\pi r^2}{3(1+w)t}$$

Both $G$ and $\hbar$ are absent from both rates. The balance ratio is:

$$B = \frac{dA_{\rm info}/dt}{dA_{\rm geom}/dt}
= \frac{16\pi r^3}{9c(1+w)t^2}
  \cdot \frac{3(1+w)t}{16\pi r^2}
= \frac{r}{3ct}$$

The factor $(1+w)$ cancels identically. The balance condition $B = 1$
requires:

$$r_{\rm balance} = 3ct \tag{2}$$

independent of the equation of state. The balance radius is the same
for dust, radiation, and any other perfect fluid. It depends only on
the age of the universe.

### 4.2 The particle horizon

The balance condition specifies a radius: $r_{\rm balance} = 3ct$. The
natural comparison radius is the particle horizon — the physical radius
of the observable universe, the furthest distance from which a signal
emitted at $t = 0$ could have reached us by time $t$. For a flat FLRW
cosmology with equation of state $w$ and scale factor
$a(t) \propto t^{2/[3(1+w)]}$:

$$r_{\rm ph}(t) = \frac{3(1+w)\,ct}{3(1+w) - 2}$$

For specific cases:

| $w$ | Matter type | $r_{\rm ph}$ |
|---|---|---|
| $0$ | Dust | $3ct$ |
| $1/3$ | Radiation | $2ct$ |
| $-1$ | Dark energy | $\infty$ (de Sitter) |

The balance radius $r_{\rm balance} = 3ct$ coincides with the particle
horizon if and only if $w = 0$. Dust is the unique equation of state
for which information supply matches geometric demand exactly at the
causal boundary. For radiation, the horizon sits inside the balance
radius; for dark energy, there is no particle horizon and the balance
condition is never satisfied.

### 4.3 The central result

Setting $B = 1$ at the particle horizon:

$$r_{\rm balance} = r_{\rm ph}
\iff 3ct = \frac{3(1+w)\,ct}{3(1+w)-2}
\iff 3(1+w) - 2 = 1+w
\iff w = 0$$

So $w = 0$ is necessary for horizon-scale balance. But it is not
sufficient if $\Omega \neq 1$. For a matter-dominated universe with
spatial curvature, the Friedmann equation becomes:

$$H^2 = \frac{8\pi G\rho}{3} - \frac{kc^2}{a^2}$$

The curvature term displaces $r_{\rm ph}$ away from $3ct$: positive
curvature ($k = +1$, $\Omega > 1$) shrinks the horizon; negative
curvature ($k = -1$, $\Omega < 1$) expands it. In either case $B \neq 1$
at the horizon, and the displacement grows over time as the curvature
term comes to dominate. Persistent balance — $B = 1$ at all times —
requires the curvature term to remain zero, which is $\Omega = 1$.

The central result of this paper is therefore:

> **The information-area balance condition $B = 1$ is satisfied at all
> times and at the particle horizon if and only if $w = 0$ and
> $\Omega = 1$ simultaneously.**

In standard cosmology, spatial flatness and matter domination appear as
independent conditions. Flatness is a fine-tuning of the initial
density to one part in $10^{60}$ at the Planck epoch. Matter domination
is a statement about the equation of state of the dominant component.
Neither explains the other. Here they are two aspects of a single
condition: the universe is the kind of universe in which information
supply matches geometric demand at the causal boundary throughout its
history.

### 4.4 The flatness conjecture

In standard cosmology, the flat universe ($\Omega = 1$) is an
*unstable* fixed point of the Friedmann equations. Small departures
from flatness grow as $|\Omega - 1| \propto t^{2/3}$ during matter
domination. The universe balanced on flatness is like a pencil balanced
on its point: mathematically possible, dynamically precarious. This is
the flatness problem. Inflation resolves it by diluting curvature, but
at the cost of introducing the inflationary mechanism.

Screen Theory suggests a different resolution. R-processes are
irreversible by definition — they are the source of the arrow of time.
The coupling between $J$ and the expansion rate through the balance
condition is therefore not time-reversal symmetric. This asymmetry may
convert the unstable fixed point into a stable attractor:

- $B < 1$ (information deficit): matter is generating more holographic
  area than the universe is expanding to accommodate. Expansion
  is insufficient; the universe is informationally overcrowded.
  The imbalance drives the expansion rate upward, pushing $B$ toward
  $1$.

- $B > 1$ (geometric surplus): the universe is expanding faster than
  matter can inscribe information on the growing boundary. Holographic
  capacity is being created faster than it can be filled. The imbalance
  damps the expansion rate, pushing $B$ back toward $1$.

In both cases the arrow of time — the irreversibility of R-processes —
means the restoring force acts forward, not backward. The fixed point
$B = 1$, $\Omega = 1$ behaves like a pendulum suspended from its pivot
rather than balanced on its point: perturbations produce restoring
forces rather than runaway departures.

We state this explicitly as a conjecture. The perturbation analysis
required to confirm that the coupling produces a stable attractor
rather than oscillatory or other behavior is a key open calculation,
flagged in Section 8. We do not claim to have solved the flatness
problem. We claim to have identified a plausible dynamical mechanism
with the right qualitative character — one that arises naturally from
the irreversibility at the heart of Screen Theory — and that the
mechanism warrants rigorous investigation.


---



## 5. The Arrow of Time: From Geometry to Logic

The arrow of time is usually treated as a puzzle about initial
conditions: the laws of physics are time-reversal symmetric, so why
does the universe have a preferred direction? The standard answer
appeals to the low entropy of the initial state — the Big Bang was
special, and entropy has been increasing ever since. This is
descriptively correct but explanatorily incomplete. It relocates the
puzzle to the initial conditions without dissolving it.

Screen Theory offers a different account. The arrow of time is not a
puzzle about entropy or initial conditions. It has two components: a
geometric arrow that is built into spacetime from the first moment and
requires nothing beyond the metric, and a logical arrow that emerges
when that geometric structure achieves global coherence. The
irreversibility of R-processes is not a consequence of the arrow of
time — it is, jointly with the geometric structure, what the arrow
of time *is*.

### 5.1 The geometric arrow

Consider any event $p$ in spacetime at cosmic time $t_2$, and any
earlier event $q$ along the same worldline at time $t_1 < t_2$. The
causal past of $p$ — the interior of its past light cone — strictly
contains the causal past of $q$. Every event that could have
influenced $q$ could also have influenced $p$, plus more. The causal
past grows strictly as one moves forward in time.

This containment relation is built directly into the metric. It
requires no matter, no thermodynamics, no R-processes. It is a
geometric fact about the causal structure of spacetime, present from
$t = 0$.

At $t = 0$ the causal past of any event is empty: zero prior
outcomes, zero contained information, zero settled questions. The
empty set $\{\}$ is the minimal element of the containment ordering.
Capital-T Time begins accumulating from $\{\}$ upward, adding
elements with each irreversible outcome. The direction of
accumulation — from smaller to larger causal pasts, from fewer to
more settled questions — is the geometric arrow.

This arrow does not need to be explained by appealing to special
initial conditions. It is not that the universe happened to start
with low entropy. It is that the universe started with an empty
causal past and has been filling it ever since. The emptiness of $t =
0$ is not a fine-tuned initial condition; it is a logical necessity.
You cannot have prior outcomes before there are any outcomes.

### 5.2 The logical arrow and global coherence

The geometric arrow exists locally at every spacetime event from the
beginning. But Capital-T Time — the linear, globally consistent
reading of accumulated history that underlies ordinary experience —
requires more than local containment. It requires that different
regions of the universe can agree on a consistent ordering of their
respective accumulations. This is a global coherence condition, and
it is not automatically satisfied.

In the chaotic pre-inflationary era, the universe is a tangle of
locally valid containment relations that cannot be consistently
globally ordered. Different patches have accumulated incompatible
local records. Logic loops are possible: patch A's settled questions
can be inconsistent with patch B's, with no meta-level arbiter to
resolve the conflict. The geometric arrow is present everywhere, but
the universe cannot yet read it consistently.

The chaos-to-inflation transition is not when the arrow of time
begins. It is when the arrow becomes *globally coherent*. Inflation
drives different patches into causal contact and forces their
accumulated records into a consistent mutual ordering. After the
transition, the universe can build information upward from $\{\}$ in
a well-founded way: each new settled question is added to a data set
that contains all prior settled questions, and every region agrees on
what has been settled.

This is the logical arrow: not just the geometric containment
relation, but the well-founded ordering of data sets by inclusion
depth that makes it possible to say, unambiguously, that event $A$
happened before event $B$.

### 5.3 The arrow as the arrow of containment

Each R-process adds a new settled question to the universe's
accumulated record. The new data set strictly contains the old one:
it has one more element. Reversal of this process would require
removing an already-contained element from a data set — it would
require un-settling a settled question. Once well-founded ordering
is established this is set-theoretically impossible, for the same
reason that you cannot remove an element from a set and leave the
set unchanged. The containment is irreversible not because of a
dynamical law but because of the logical structure of set membership.

**The arrow of time is the arrow of containment.**

This dissolves rather than solves the usual puzzle. The puzzle arises
because we treat time reversal as a symmetry of the laws and then ask
why it is broken in practice. Screen Theory says the premise is
wrong: the irreversible accumulation of settled questions is not a
broken symmetry of an underlying reversible dynamics. It is the
primary structure. Reversible unitary evolution (U-processes) takes
place within the accumulated record; R-processes extend it. There is
no deeper reversible substrate of which irreversibility is a
secondary feature.

The low-entropy initial condition of standard cosmology reappears
here, but reinterpreted. The universe at $t = 0$ had zero
entropy not because it was fine-tuned to a special low-entropy
state, but because it had settled zero questions. The empty set has
entropy zero by definition. The growth of entropy is the growth of
the settled record. There is nothing to explain about why it started
low: it could not have started otherwise.

### 5.4 The fruit fly footnote

The joke — *time flies like an arrow; fruit flies like a banana* —
is a perfect miniature of the arrow of time in action. The parser
commits irreversibly to the first syntactic reading, then cannot
un-read it when the second reading arrives. The disambiguation
resolves only forward: the surprise depends on having already
settled the first interpretation. Un-settling it, even briefly,
is what makes the joke work — and the fact that it takes cognitive
effort to do so is precisely the arrow of containment operating in
real time.


---



## 6. The Vacuum Energy Catastrophe

Quantum field theory assigns a zero-point energy to every field mode.
Summing over all modes up to the Planck scale gives a vacuum energy
density of order $\rho_{\rm vac} \sim 10^{113}$ J/m$^3$. The observed
energy density of the universe is of order $10^{-9}$ J/m$^3$. The
discrepancy is $10^{122}$ — the most spectacular failure of a naive
estimate in the history of physics. Why does the vacuum energy not
curve spacetime catastrophically?

The standard responses are unsatisfying. Supersymmetry cancels
bosonic and fermionic contributions, but only perfectly in an exact
supersymmetry that is manifestly broken at low energies. Anthropic
arguments say the cosmological constant is small because we could not
exist otherwise, which is true but not explanatory. Fine-tuning
arguments simply accept that some mechanism cancels $10^{122}$ against
itself to a precision of one part in $10^{122}$, which is fine-tuning
of breathtaking audacity.

Screen Theory offers a structural answer that requires no cancellation
and no fine-tuning. It is a resolution by category, not by
arithmetic.

### 6.1 Virtual processes are U-processes

The zero-point energy of quantum field theory arises from virtual
processes — vacuum fluctuations, off-shell intermediate states,
closed loops with no external legs. These processes are by definition
reversible. A virtual photon created and reabsorbed leaves no
permanent record; the vacuum state before and after is identical. No
irreversible outcome is produced. No settled question is added to the
universe's accumulated record.

In Screen Theory the information generation rate is:

$$J = \frac{2\pi(\rho + p)}{\hbar}$$

where $J$ counts only irreversible R-process contributions. Virtual
processes are U-processes: reversible, unitary, leaving no record.
For any U-process, $J = 0$ by definition. Therefore virtual processes
do not contribute to the information-area coupling. They generate no
holographic area. They do not curve spacetime.

The vacuum is not gravitationally inert because its enormous energy
cancels against something else. It is gravitationally inert because
it is the wrong kind of energy. Virtual processes have energy in the
quantum mechanical sense — they contribute to the Hamiltonian — but
they have no irreversibility, and irreversibility is what couples to
geometry in Screen Theory.

### 6.2 A category error in the standard argument

The vacuum energy catastrophe arises from conflating two distinct
quantities: the total energy of the quantum vacuum, including all
virtual processes, and the irreversible information generation rate
that sources spacetime curvature. In standard GR, any energy-momentum
curves spacetime. In Screen Theory, only irreversible energy-momentum
curves spacetime. The standard QFT calculation correctly computes the
first quantity. The error is assuming it equals the second.

This is a category error, not a numerical accident. The naive vacuum
energy is large because there are many virtual modes. But virtual
modes do not write on the holographic boundary. They do not generate
area. They do not cause curvature. The $10^{122}$ discrepancy is not
a number that needs to be explained away — it is the ratio of the
total quantum vacuum activity to the irreversible fraction of it, and
there is no reason that ratio should be small or even finite in the
absence of a UV cutoff.

The correct statement is: virtual processes do not appear on the
right-hand side of the Screen Theory information-area relation
because they are not R-processes. They never belonged there. The
catastrophe dissolves once the correct source term is identified.

### 6.3 What this does and does not resolve

This argument resolves the vacuum *energy* catastrophe: why the
enormous zero-point energy density of quantum field theory does not
appear as spacetime curvature. The answer is that it cannot, because
it is the wrong kind of energy.

It does not resolve the cosmological *constant* problem, which is a
different question: what sets the observed nonzero value of $\Lambda$,
and why is it of order the present matter density rather than zero or
Planckian? These are distinct questions and we address only the first.
The cosmological constant is treated separately in Section 7.

The distinction matters because they are often conflated. The vacuum
energy catastrophe asks why $\rho_{\rm vac}^{\rm QFT}$ does not
appear as curvature. The cosmological constant problem asks why there
is a small residual curvature that looks like a constant energy
density. Screen Theory answers the first question cleanly. It has
a candidate answer for the second, developed in the following section,
but that answer is more speculative and is stated as such.


---



## 7. The Cosmological Constant

The cosmological constant $\Lambda$ is not determined by the present
framework. Paper II showed that $\Lambda$ enters the field equations
as a free parameter — a boundary condition on the information-area
relation, not a consequence of it. Setting $\Lambda = 0$ is a
separate assumption, and the observed nonzero value tells us
something real. This section offers a candidate interpretation and
sketches the qualitative picture it produces, while deferring a full
treatment to a companion paper.

### 7.1 A candidate interpretation

In Screen Theory, spacetime curvature is sourced by irreversible
information generation — R-processes that write permanently on the
holographic record. Classical matter generates R-processes at rate
$J = 2\pi(\rho+p)/\hbar$. But classical matter is not the only
source of irreversible outcomes. The quantum vacuum itself may
generate a slow, background rate of irreversible information
production — not the virtual U-processes of Section 6, which are
reversible and gravitationally inert, but a residual rate of genuine
state reductions that is independent of the presence of classical
matter.

On this interpretation, $\Lambda$ encodes the background R-process
rate of the vacuum — the irreducible minimum rate at which the
universe generates new settled questions even in the absence of
matter. It is small because genuine vacuum R-processes are rare
compared to matter-driven ones. It is nonzero because the vacuum is
not perfectly quiet: it is a quantum system, and quantum systems
generate irreversible outcomes.

This is a candidate interpretation, not a derivation. It does not
predict the value of $\Lambda$, and it should not be mistaken for a
solution to the cosmological constant problem. What it does is place
$\Lambda$ in the same conceptual category as $J$ — a rate of
irreversible information generation — rather than treating it as
geometrically sui generis.

### 7.2 Late-time acceleration as holographic surplus

As the universe expands and matter dilutes, the matter-driven
information generation rate $J \propto \rho$ falls as $a^{-3}$.
Eventually $\Lambda$ — constant by assumption — comes to dominate.
At this point the universe enters a second regime in which new
holographic area is being created by the accelerating expansion
faster than matter can inscribe information on it.

This is a second blank-tape era. The first was the inflationary
epoch, when the universe expanded so rapidly that the holographic
boundary was being created far faster than matter could populate it.
The current accelerating epoch has the same qualitative character:
surplus capacity, more screen than data, the boundary growing faster
than the record is being written.

In the balance ratio language of Section 4, $\Lambda$-dominated
expansion drives $B < 1$: the geometric area growth rate exceeds
the information generation rate. The universe is outrunning its
own record-keeping. If the attractor conjecture of Section 4.4
is correct, this represents a departure from the $B = 1$ fixed
point — one that grows rather than self-corrects because the
matter density is too dilute to provide the restoring force.

### 7.3 The Gödelian endgame

As matter continues to dilute and $J \to 0$, Capital-T Time
decelerates. The rate at which new settled questions are added to
the universe's accumulated record slows. The remaining open
questions are increasingly the irreducible ones — the Gödelian
conundrums that have no valid antithesis, the questions the universe
cannot settle by any finite sequence of R-processes.

The universe does not end. It falls quiet. The holographic boundary
continues to grow with the accelerating expansion, but the record
being inscribed on it grows ever sparser. What remains are the
irreducible open questions — the logical bedrock whose irreducibility
is precisely what made the universe interesting in the first place.

This is the Screen Theory eschatology: not heat death, not a Big
Rip, not a Big Crunch, but a gradual quieting in which the easy
questions are settled and only the hard ones remain. Whether the
Gödelian conundrums are ever settled, and what it would mean for
them to be, is a question the present framework cannot answer.

### 7.4 Scope

The treatment in this section is qualitative throughout. $\Lambda$
is not computed; the transition redshift to $\Lambda$-domination is
not derived; the Gödelian endgame is a picture, not a calculation.
A companion paper will develop the $\Lambda$ interpretation
quantitatively and connect it to the observed value of the
cosmological constant — or explain honestly why the connection
cannot yet be made.


---



## 8. Open Questions: The Radiation Era and Assumption A2

*This section is shorter by design. We have solid results for the
matter era; we have open questions for the radiation era. We state
both clearly.*

### 8.1 The radiation era balance ratio

In the matter era, the balance ratio $B = r/3ct$ equals unity at the
particle horizon $r_{\rm ph} = 3ct$. The framework is internally
consistent: information supply matches geometric demand precisely at
the causal boundary.

In the radiation era the picture is different. For $w = 1/3$, the
particle horizon is $r_{\rm ph} = 2ct$, while the balance radius
remains $r_{\rm balance} = 3ct$ — independent of equation of state,
as Section 4 showed. The balance ratio at the horizon is therefore:

$$B\big|_{w=1/3} = \frac{r_{\rm ph}}{3ct} = \frac{2ct}{3ct} = \frac{2}{3} \tag{3}$$

Geometric area growth exceeds information-driven area generation.
The expanding boundary has surplus holographic capacity — more screen
than data. The universe in the radiation era is writing on a boundary
that is growing faster than the record can fill it.

This is not a contradiction. It is a frontier. The matter era result
$B = 1$ was derived under the assumption that Assumption A2 holds
exactly: that the vacuum operates at holographic saturation and every
new nat of information requires new area. In the radiation era, with
surplus capacity available, this assumption may not hold exactly.
New information can be absorbed into pre-existing blank area rather
than requiring new area to be generated. The framework is pointing
at its own boundary condition.

### 8.2 The fill factor

To parametrize the departure from exact saturation, define the fill
factor $f(t) \in [0,1]$, where $f = 1$ means Assumption A2 holds
exactly and $f < 1$ means surplus holographic capacity is available.
The effective coupling between information generation and geometry
becomes:

$$G_{\mu\nu} + \Lambda g_{\mu\nu} = 8\pi f(t)\, G\, T_{\mu\nu} \tag{4}$$

This is a Brans-Dicke structure with $\phi = f(t)$: an
effective gravitational coupling that varies with cosmic epoch.
Papers I and II are recovered exactly in the limit $f \to 1$,
which the matter era achieves. The radiation era corresponds to
$f < 1$, with the departure from unity measuring the holographic
surplus.

We do not derive $f(t)$ in this paper. Deriving it would require a
detailed model of how information fills available holographic
capacity in the early universe — a calculation that depends on the
R-process rate during the radiation era, the geometry of the
causal horizon at each epoch, and the dynamics of the
matter-radiation transition. This is the key open calculation of
the Screen Theory cosmological program.

### 8.3 Observational constraints and points of contact

Although $f(t)$ is not derived here, it is observationally
constrained. Big Bang nucleosynthesis (BBN) is sensitive to the
expansion rate during the first few minutes, which depends on the
effective gravitational coupling. Alvey et al. (2020) find, from
combined BBN and CMB constraints, that $G_{\rm eff}/G \gtrsim 0.94$
at $2\sigma$ at the BBN epoch. In Screen Theory language: $f(t_{\rm
BBN}) \gtrsim 0.94$.

The direction of variation is independently motivated. Fits of
Brans-Dicke cosmology with a cosmological constant (BD-$\Lambda$CDM)
to $H_0$ tension and $\sigma_8$ data favor a slightly smaller
effective $G$ in the past, converging to the standard value today
(Solà Peracaula et al. 2019, 2020). The Screen Theory fill factor
$f(t)$ increasing from $f < 1$ in the radiation era to $f = 1$ in
the matter era is consistent with the direction this data favors.

The lithium problem — the persistent discrepancy between the
primordial $^7$Li abundance predicted by standard BBN and the
observed abundance in metal-poor stars — may be a point of contact.
$f < 1$ at BBN reduces the effective gravitational coupling and
therefore the expansion rate, which reduces helium-4 production
slightly and $^7$Li production in the correct direction to reduce
the discrepancy. We do not claim to resolve the lithium problem.
We note that the Screen Theory framework produces a natural
candidate mechanism, and that the direction of the effect is right.

### 8.4 Open questions

The following questions are stated explicitly as open, as
invitations to the community as much as reminders to ourselves:

1. **What is $f(t)$?** Can the fill factor be derived from
   first principles — from the R-process rate, the holographic
   capacity of the causal horizon, and the dynamics of the
   radiation era — without being inserted by hand?

2. **Is $f$ spatially uniform?** In high-density regions,
   matter-driven R-processes may saturate the local holographic
   capacity even in the radiation era, giving $f \to 1$ locally.
   The fill factor may be an inhomogeneous field rather than a
   universal function of cosmic time.

3. **Does the transition $f \to 1$ drive matter-radiation
   equality, or follow from it?** The causal direction matters:
   if increasing $f$ is what causes the expansion rate to slow
   and matter to come to dominate, the matter era is the
   attractor that Screen Theory predicts. If $f \to 1$ is merely
   a consequence of matter domination established by other means,
   the story is less clean.

4. **What is the relationship between Screen Theory and
   Linde's chaotic inflation?** The two frameworks are
   qualitatively compatible — both involve a pre-inflationary
   chaotic era transitioning to a globally coherent ordered
   phase — but the precise connection, and whether they make
   contradictory predictions in any regime, has not been worked
   out.

5. **Does the perturbation analysis of the $B = 1$ fixed point
   confirm a stable attractor?** The qualitative argument of
   Section 4.4 suggests that irreversibility converts the
   standard unstable flatness fixed point into a stable one.
   Confirming this requires a perturbation analysis of the
   coupled information-geometry system that has not yet been
   done.

The radiation era is where Screen Theory's cosmological program
meets its own frontier. The matter era results are clean and
derive from well-established foundations. The radiation era opens
onto harder questions — questions that, if they can be answered,
will determine whether the framework is a complete cosmological
theory or a powerful partial one.


---



## 9. Discussion

### 9.1 The cosmological story in five chapters

The framework developed in this paper tells a coherent story about
the universe from first moment to final quiet. It is worth stating
that story plainly, without equations, before summarizing the
technical results.

**Chapter 1 — The empty set.**
At $t = 0$ the causal past of every event is empty. Zero prior
outcomes, zero settled questions, zero holographic area earned.
The geometric arrow of containment is present — larger causal pasts
strictly containing smaller ones — but unreadable globally, because
different patches cannot yet agree on a consistent ordering of their
local records. Logic loops tangle the pre-inflationary era. The
universe exists, in some sense, but has not yet begun to know itself.

**Chapter 2 — The blank tape.**
The transition to global coherence — assuming, with Linde, that
chaotic inflation provides the mechanism — aligns the local arrows
into a single readable direction. Capital-T Time begins. But
inflation drives exponential expansion, creating holographic capacity
far faster than matter can inscribe it. The boundary is vast and
nearly empty. The universe has a tape but has barely begun to write
on it.

**Chapter 3 — The radiation era.**
The inflationary expansion slows. The universe is filled with an
enormous density of matter and antimatter — roughly a billion times
more of each than the surviving matter we see today. Every proton,
antiproton, electron, and positron is generating irreversible
information at its Compton rate, $dC/d\tau = 2\pi mc^2/\hbar$.
This is the dominant source of $J$ in the radiation era: not
annihilation, but continuous existence. Each particle completes
roughly 7,000 Compton cycles before annihilating, writing on the
holographic record at every step. Annihilation is the final
R-process of a particle that has already spent 7,000 Compton
periods as an author. The library is not being filled by authors
handing in final manuscripts — it is being filled by authors
scribbling continuously at the Compton rate, with the library
struggling to create shelf space fast enough.

The boundary is still growing faster than the inscription can fill
it: $B = 2/3 < 1$ at the radiation-era horizon. The universe is
informationally explosive but not yet in balance. Out of the
annihilation, the baryon asymmetry crystallizes: the Gödelian
conundrums, the questions with no valid antithesis, the
$\sim 1$ in $10^{10}$ surplus of matter that cannot be settled
by annihilation because it has no complement to annihilate with.

Publication begins well before recombination, through channels that
do not require electromagnetic transparency. Gravitational waves
decouple at the Planck epoch and free-stream from the earliest
moments of Capital-T Time; a primordial gravitational wave background,
if detected, would be a direct reading of the universe's first
published record. Neutrinos decouple at $T \sim 2$-$3$ MeV, roughly
one second after the Big Bang, publishing the state of the universe
at nucleosynthesis to any detector coupled to the neutrino field.
The universe is not waiting for recombination to begin publishing.
It is publishing continuously through every channel whose mean free
path has grown to horizon scale.

**Chapter 4 — The big reveal.**
Matter-radiation equality. The expansion rate slows enough that
information generation catches up to geometric growth. The balance
ratio $B$ approaches unity. Recombination follows: the universe
becomes transparent to photons, and the cosmic microwave background
— the holographic record of the radiation era inscribed on the last
scattering surface — is published electromagnetically for the first
time. This is not the universe's first publication; it is its most
accessible one, the layer of the record readable by matter coupled
to the photon field.

Every new Planck area on the growing boundary earns its inscription.
Capital-T Time accumulates in earnest. The arrow of containment
becomes the organizing principle of structure: matter falls into the
skeleton that the informational domain structure of the inflationary
era laid down, and the cosmic web — voids, filaments, walls, cluster
seeds — appears not as random residue but as the logical architecture
of the universe's question space made visible.

The nested decoupling surfaces — gravitational wave horizon, neutrino
last-scattering surface, photon last-scattering surface — are nested
screens, each publishing a different layer of the accumulated record
to a different class of receiver. The wholographic principle applies
to each channel separately and to all jointly. The universe is a
library with multiple reading rooms, each opened at a different epoch,
each containing a different stratum of the record.

**Chapter 5 — The long quiet.**
Dark energy comes to dominate. Matter dilutes; $J \to 0$; the
information generation rate of classical matter fades. New
holographic surplus appears — a second blank tape era, but this
time without the furious inscription of the radiation era to
follow. The hard questions remain: the Gödelian conundrums,
processing at the centers of large structures, irreducible by
definition. The universe does not end. It runs out of easy
questions, and falls quiet around the hard ones.

---

### 9.2 Summary of solid results

The following results are derived in this paper and rest on
established foundations:

**$J = 2\pi(\rho+p)/\hbar$** (Section 2). The information
generation rate for a perfect fluid follows in three lines from
the null-null contraction results of Paper II. The enthalpy
density $(\rho + p)$ selects precisely the timelike component of
energy-momentum flow: the component that accumulates proper time,
generates irreversible outcomes, and couples to geometry. Single
photons contribute nothing; an isotropic photon gas contributes
its full collective invariant mass.

**$r_{\rm balance} = 3ct$ independent of $w$** (Section 4.1).
The balance radius at which information supply equals geometric
demand is $3ct$ for any equation of state. The factors $(1+w)$,
$G$, and $\hbar$ all cancel in the balance condition. The result
is pure geometry.

**$B = 1 \Leftrightarrow w = 0$ and $\Omega = 1$** (Section 4.3).
Persistent balance at the particle horizon requires matter
domination and spatial flatness simultaneously. In standard
cosmology these appear as independent coincidences. Here they
are two projections of a single information-geometric consistency
condition.

**Vacuum energy catastrophe resolved structurally** (Section 6).
Virtual processes are U-processes: reversible, leaving no record,
contributing $J = 0$. The $10^{122}$ discrepancy between the
naive QFT vacuum energy and the observed curvature is not a
number requiring cancellation. It is a category error: the
standard argument counts the wrong kind of energy.

**Cosmological origin of space** (Section 3). The Olbers
holographic integral gives $A_{\rm required}/A_{\rm horizon}
= 4/3$ for an Einstein-de Sitter universe, with $G$ and $\hbar$
both absent from the result. The holographic capacity of the
observable universe is generated, to order unity, by the matter
within it — with no free parameters.

**Arrow of containment** (Section 5). The geometric arrow
is present from $t = 0$ as a strict containment relation on
causal pasts. It requires no matter, no thermodynamics, no
R-processes. Capital-T Time begins when this arrow becomes
globally coherent. The low-entropy initial condition is not
fine-tuning; it is the logical necessity that you cannot have
prior outcomes before there are any.

### 9.3 Future directions

The following calculations and extensions are the natural next
steps:

**The pendulum calculation.** Section 4.4 conjectured that
irreversibility converts the flatness fixed point from an
unstable equilibrium into a stable attractor. Confirming this
requires a perturbation analysis of the coupled
information-geometry system. This is the most important open
calculation in the cosmological program.

**Derivation of $f(t)$.** The fill factor parametrizing
holographic saturation in the radiation era (Section 8.2) is
constrained observationally but not derived theoretically.
Deriving it from R-process rates and causal horizon geometry
would complete the radiation era picture and potentially connect
to the lithium problem and $H_0$ tension.

**General Friedmann equations from information-geometric
principles.** The present paper derives results for
Einstein-de Sitter and flat FLRW. The full Friedmann equations,
including curvature and $\Lambda$, should follow from the
same framework applied without the simplifying assumptions.

**The Wholographic Principle paper.** The baseline
entanglement of any patch of space with the rest of the universe
— a consequence of the R-process structure developed here —
provides a derivation of the Ryu-Takayanagi relation, the
Van Raamsdonk picture, and ER = EPR from first principles.
This is the subject of a companion paper in preparation.

**Paper IV: horizons, black holes, and the Page curve.**
The event horizon as the surface where publication rate equals
question-arrival rate; Bekenstein-Hawking entropy as queued
questions; Hawking radiation as thermalized slow publication;
the Page curve as the information accounting of a black hole
completing its queue. The framework for this treatment is in
place; the paper is in preparation.


---

## Acknowledgments

*Thanks to Finula McCaul for pressure-testing whether the formal
structures still feel like reality when the notation is stripped away;
to Bob Carlitz for review and criticism; to George Sparling for
conversations on twistor geometry and paradigmatic domains.*

---



## References

**Reilly Papers (this series)**

Reilly, P.A.I. (2026a). "Reflections on Two Moving Mirrors."
*[Paper I — in preparation]*

Reilly, P.A.I. (2026b). "On the Nature of Mass: Complexity Generation
and Spacetime Curvature." *[Paper II — in preparation]*

---

**Holographic principle and black hole thermodynamics**

Bekenstein, J.D. (1973). Black holes and entropy.
*Physical Review D* **7**(8): 2333–2346.

Bekenstein, J.D. (1981). Universal upper bound on the
entropy-to-energy ratio for bounded systems.
*Physical Review D* **23**(2): 287–298.

't Hooft, G. (1993). Dimensional reduction in quantum gravity.
*arXiv:gr-qc/9310026.*

Susskind, L. (1995). The world as a hologram.
*Journal of Mathematical Physics* **36**(11): 6377–6396.

Hawking, S.W. (1975). Particle creation by black holes.
*Communications in Mathematical Physics* **43**(3): 199–220.

---

**Entanglement and geometry**

Srednicki, M. (1993). Entropy and area.
*Physical Review Letters* **71**(5): 666–669.

Ryu, S. and Takayanagi, T. (2006). Holographic derivation of
entanglement entropy from AdS/CFT.
*Physical Review Letters* **96**(18): 181602.

Van Raamsdonk, M. (2010). Building up spacetime with quantum
entanglement. *General Relativity and Gravitation* **42**(10):
2323–2329.

Maldacena, J. and Susskind, L. (2013). Cool horizons for entangled
black holes. *Fortschritte der Physik* **61**(9): 781–811.
[ER = EPR]

---

**Thermodynamics of spacetime**

Jacobson, T. (1995). Thermodynamics of spacetime: the Einstein
equation of state. *Physical Review Letters* **75**(7): 1260–1263.

---

**Quantum measurement and irreversibility**

Penrose, R. (1994). *Shadows of the Mind.* Oxford University Press.

Shannon, C.E. (1948). A mathematical theory of communication.
*Bell System Technical Journal* **27**(3): 379–423.

Kolmogorov, A.N. (1965). Three approaches to the quantitative
definition of information. *Problems of Information Transmission*
**1**(1): 1–7.

Wheeler, J.A. (1990). Information, physics, quantum: The search
for links. In Zurek, W.H. (ed.), *Complexity, Entropy, and the
Physics of Information.* Addison-Wesley.

---

**General relativity**

Wald, R.M. (1984). *General Relativity.* University of Chicago Press.

Lovelock, D. (1971). The Einstein tensor and its generalizations.
*Journal of Mathematical Physics* **12**(3): 498–501.

---

**Machian and relational gravity**

Mach, E. (1883). *The Science of Mechanics.* Open Court, 1960
translation.

Sciama, D.W. (1953). On the origin of inertia.
*Monthly Notices of the Royal Astronomical Society* **113**: 34–42.

Leibniz, G.W. (1715–1716). Correspondence with Clarke.
In Alexander, H.G. (ed.), *The Leibniz-Clarke Correspondence.*
Manchester University Press, 1956.

---

**Inflation**

Linde, A.D. (1983). Chaotic inflation.
*Physics Letters B* **129**(3–4): 177–181.

Linde, A.D. (1986). Eternally existing self-reproducing chaotic
inflationary universe. *Physics Letters B* **175**(4): 395–400.

---

**Observational cosmology**

Alvey, J., Sabti, N., Escudero, M., and Fairbairn, M. (2020).
Improved BBN constraints on the variation of the gravitational
constant. *European Physical Journal C* **80**: 148.

Solà Peracaula, J., Gómez-Valent, A., de Cruz Pérez, J., and
Moreno-Pulido, C. (2019). Brans-Dicke gravity with a cosmological
constant smoothes out ΛCDM tensions. *Astrophysical Journal Letters*
**886**: L6.

Solà Peracaula, J., Gómez-Valent, A., de Cruz Pérez, J., and
Moreno-Pulido, C. (2020). Brans-Dicke cosmology with a Λ term: a
possible solution to ΛCDM tensions. *Classical and Quantum Gravity*
**37**: 245003.

---

**Peirce**

Peirce, C.S. (1902). The phaeneron. In *Collected Papers of Charles
Sanders Peirce*, Vol. 1. Harvard University Press, 1931.

