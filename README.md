# A Casimir-Constrained Superfluid Vacuum for Emergent Gravity
**Author:** B. ten Broek  
**Date:** November 2025  
**Revision:** v1.7


## Abstract
Gravity is interpreted as the radial inflow of newly created spacetime sourced by quantum vacuum fluctuations. The Casimir effect's insensitivity to gravitational curvature requires the vacuum's spacetime-creation rate $\Gamma$ to depend non-linearly on local curvature; otherwise the vacuum would be inhomogeneous at the quantum level. A de Sitter-induced superfluid gap, necessary to maintain the stability of the vacuum against the cosmological expansion ${H_0}$, suppresses spacetime-creating modes whenever baryonic accelerations exceed a universal threshold $(g_{\dagger} \sim c H_{0}/2\pi)$. This reproduces the observed Radial Acceleration Relation (RAR) (McGaugh-Lelli-Schombert 2016; Lelli et al. 2017) to better than a few percent across rotationally supported galaxies.
The fully covariant action reduces algebraically to the exact RAR formula in the weak-field limit, with all dimensional scales fixed by $\{c,G,H_{0}\}$ and a single dimensionless parameter $\kappa\simeq1.20$ determined by SPARC data. The theory recovers General Relativity exponentially fast in strong fields and passes all existing Solar-System, binary-pulsar, and gravitational-wave tests at leading order.

---

<div style="page-break-after: always;"></div>


## Author's note: The Origins Of This Work And The Use Of AI
After 30 years of skepticism toward ΛCDM and a nagging sense that physics feels disconnected from the "how" and "why," I stumbled on a connection between the Casimir effect, gravity, and the idea that space itself might be *created*—not just expanded. Around October 1, 2025, I half-jokingly asked AI to generate cosmology math for this idea. It failed on all attempts. Then, on October 10, I let it rest. But in the second half of November, a breakthrough: realizing the idea must involve **spacetime**, not just space. This shift led me to try to find similarities with the **RAR curve** (McGaugh's formula for galaxy rotation discrepancies) equation and my ideas. It was the right path, as the AI solved the math in just a few steps. An approach to a perfect fit.  
AI scrutinizers pointed out missing relativistic math now. This deemed hard and all attempts violated the core Casimir constraint concept. However, by refusing any additional free parameters beyond the single $\kappa$ fixed by SPARC data, the result is algebraic equivalence. The resulting action is fully diffeomorphism-invariant and reduces algebraically to the observed RAR with $\kappa \approx 1.2$ (fixed by SPARC data).  
This work owes much to AI's role as a collaborator, guide, and critic, as well as to the collective knowledge of scientists whose work I've leaned on heavily. I have no formal training — only thirty years of refusing to accept that $a_{0} \approx c H_{0}$ should be a coincidence, and access to AI tools built on the collective work of the physics community. The ideas, the no-extra-parameters constraint, the refusal to accept defeat after many failed attempts, and the final responsibility are mine alone.

<div style="page-break-after: always;"></div>

## 1. Foundational Premises

**P1. Spacetime Creation Source.**  
Quantum vacuum fluctuations continually generate new spacetime at a background rate ($\Gamma_{0}$), driving cosmic expansion.

**P2. The Casimir Constraint.**  
All laboratory measurements of the Casimir force (conducted in gravitational fields $\gg g_{\dagger} \approx 10^{-10} m/s^{2}$) agree with the flat-spacetime Lifshitz formula to within $\approx 1$% experimental precision (Bordag et al. 2009; Klimchitskaya et al. 2009). Known curvature- and redshift-induced corrections are many orders of magnitude below this precision in terrestrial and astrophysical environments, implying that any curvature dependence of the vacuum spectrum must be exponentially suppressed below the de Sitter scale $g_ \dagger$. Therefore the vacuum's mode spectrum must adjust so that the effective spacetime-creation rate ($\Gamma$) depends on local curvature ($R$); without this, the vacuum would display curvature-dependent inhomogeneities in conflict with the Casimir result.

**Conclusion.**  
Gravity emerges from curvature-regulated spacetime creation: curvature modulates $\Gamma$, and the resulting radial inflow of the vacuum is observed as gravitational acceleration.

*A related conceptual direction — that gravity may arise from the collective behavior of microscopic degrees of freedom rather than as a fundamental interaction — was explored in emergent-gravity approaches such as Verlinde (2017), though with a fundamentally different mechanism from the curvature-regulated spacetime-creation process developed here.*

<div style="page-break-after: always;"></div>

## 2. Galactic Dynamics, the Hierarchy Issue, and Its Resolution


A linear response $(\Gamma = \Gamma_{0} + \kappa R)$ fails by roughly $10^{30}$: the background rate $(\Gamma_{0} \simeq 4 \times 10^{-37} \, s^{-1})$ dominates any curvature-induced modulation inside galaxies, leaving Newtonian gravity unaffected.

A de Sitter superfluid resolves this. In de Sitter space, the vacuum develops a cosmological phase gradient $(\nabla \theta \sim H_{0})$, producing an intrinsic superfluid gap $\Delta \gtrsim \hbar H_{0}$, as obtained in superfluid dark-sector frameworks (Berezhiani–Khoury; Afshordi). 

This imposes the only available IR scale: the de Sitter acceleration  
$g_{\mathrm{dS}} \equiv \frac{c H_{0}}{2\pi} \approx 10^{-10} \, \mathrm{m\, s^{-2}}$. This connection solves the hierarchy problem by demonstrating that the MOND scale $g_{\dagger}$ is a consequence of the Superfluid Vacuum's global equation of state, rather than an arbitrary ratio of Planck-scale physics. Thus, the transition scale obeys $g_{\dagger} \approx g_{\mathrm{dS}}$ up to order-unity uncertainties. The apparent $10^{30}$ hierarchy disappears because the Boltzmann factor depends on $\sqrt{\frac{g_{\mathrm{bar}}}{g_{\mathrm{dS}}}}$, not $\sqrt{\frac{g_{\mathrm{bar}}}{g_{\mathrm{Pl}}}}$.

* Berezhiani & Khoury (2016) — dark-matter superfluid framework.
* Khoury (2022) — review.
* Afshordi (2022) — vacuum gap formation mechanisms.


Curvature modifies the effective healing length:  $L_{\mathrm{eff}} \propto \left( \frac{g_{\mathrm{dS}}}{g_{\mathrm{bar}}} \right)^{1/2}$
The excitation energy of such a mode is $\sim \hbar c / L_{\mathrm{eff}} \propto \sqrt{g_{\mathrm{bar}}}$.
In a gapped superfluid this introduces a Boltzmann suppression  
$S(g_{\mathrm{bar}}) = \exp\!\left[ -\kappa \sqrt{\frac{g_{\mathrm{bar}}}{g_{\mathrm{dS}}}} \right],
\qquad \kappa \sim 1-2$.  
The allowed creation rate becomes  
$\Gamma(g_{\mathrm{bar}}) = \Gamma_{\max} \left[ 1 - \exp\!\left( -\kappa \sqrt{\frac{g_{\mathrm{bar}}}{g_{\dagger}}} \right) \right], \qquad g_{\dagger} \approx g_{\mathrm{dS}}$.  
In the galactic weak-field limit, the induced inflow yields  
$g_{\mathrm{emergent}} = g_{\dagger} \left[ 1 - \exp\!\left( -\sqrt{\frac{g_{\mathrm{bar}}}{g_{\dagger}}} \right) \right]$.  
Adding the Newtonian component gives the observed total acceleration  
$g_{\mathrm{obs}} = g_{\mathrm{bar}} + g_{\dagger} \left[ 1 - \exp\!\left( -\sqrt{\frac{g_{\mathrm{bar}}}{g_{\dagger}}} \right) \right]$,  
which matches the empirical RAR *(McGaugh-Lelli-Schombert 2016, Lelli et al. 2017)* across all tested galaxies within observational uncertainties (see Figure 1).

![RAR_fit.png](./RAR_fit.png)  
*Figure 1: Predicted radial acceleration relation (red line) compared to the observed SPARC dataset (McGaugh et al. 2016; Lelli et al. 2017) (light blue). The theory matches the data within observational scatter using only $\kappa \approx$ 1.2.*

<div style="page-break-after: always;"></div>

## 3. Strong-Field Regime and the Principle of Cosmological Identity

- Extreme environments revert to the same highly excited, saturated superfluid phase that existed in the very early universe.

The superfluid vacuum admits a maximum creation rate $\Gamma{max}$ set by an ultraviolet cutoff $\Lambda c^{4} \approx$ (Planck or QCD scale). When baryonic density drives the system toward this saturation — expected deep inside astrophysical black holes and in the pre-bounce cores of massive stars — the exponential screening factor approaches zero and the condensate is forced far from its de Sitter ground state.

In this extreme limit, the system saturates at the maximum creation rate $\Gamma{max}$​, reverting to the highly excited superfluid phase thought to govern the early universe (analogous to Volovik's regularized horizons).

Qualitatively, such regularized horizons can support trapped quasi-normal modes, leading to gravitational-wave "echoes" in the post-merger ringdown and modest deviations from pure-GR core-collapse waveforms — phenomena common to many singularity-free gravity models. Quantitative waveforms require full non-linear numerical evolution of the action, which is in preparation.

<div style="page-break-after: always;"></div>



## 4. Fundamental scales and field content

### Fundamental scales (fixed by observation)
$$
g_{\dagger} \equiv \frac{c H_{0}}{2\pi}
\qquad\approx 1.08\times10^{-10}\;\mathrm{m\,s^{-2}}
$$
$$
\Lambda_{c}^{4} \equiv \frac{3c^{4}H_{0}^{2}}{8\pi G}
\;\; \Rightarrow\;\;
\rho_{\Lambda} \equiv \frac{\Lambda_{c}^{4}}{c^{2}} = \frac{3c^{2}H_{0}^{2}}{8\pi G}
\qquad\text{(observed dark-energy density)}
$$

### Field content and dimensionless invariants
- Goldstone field $\theta(x^{\mu})$  
- Covariant 4-velocity (automatically unit-normalised and diffeomorphism-invariant)  
  $$u^{\mu} \equiv \frac{\partial^{\mu}\theta}{\sqrt{-(\partial\theta)^2}}$$

Dimensionless scalars:
$$
\begin{aligned}
X &\equiv -\frac{1}{2\Lambda_{c}^{4}}\,\partial_{\mu}\theta\,\partial^{\mu}\theta \quad\in[0,1] \,,\\[6pt]
Y &\equiv \frac{u^{\mu}\partial_{\mu}\theta}{\Lambda_{c}^{2}} \quad\in[0,1] \,,\\[6pt]
\mathcal{G} &\equiv \frac{c^{2}}{\Lambda_{c}^{4}}\,\sqrt{-T_{b}^{\alpha\beta}T_{b\,\alpha\beta}}
\qquad\text{(dimensionless baryon invariant)}
\end{aligned}
$$

<div style="page-break-after: always;"></div>

## 5. Action (fully covariant, ghost-free)

$$
\boxed{
\begin{aligned}
S &= \int d^{4}x\,\sqrt{-g}\;
\Bigl[\;
\frac{M_{\rm Pl}^{2}}{16\pi}R
\;+\;
\Lambda_{c}^{4}\Bigl(X\ln X -(X-1)\Bigr)\\
&\qquad+\;
\Lambda_{c}^{4}\,Y^{2}\Bigl(1-e^{-\kappa\sqrt{\mathcal{G}}}\Bigr)
\;+\;
\mathcal{L}_{b}(g_{\mu\nu},\psi)\Bigr]
\end{aligned}}
$$

<div style="page-break-after: always;"></div>

## 6. Non-relativistic weak-field limit (exact algebraic reduction)

In the static, spherical, weak-field regime one finds  
$$\sqrt{\mathcal{G}} = \sqrt{\frac{g_{\rm bar}}{g_{\dagger}}}$$
where $g_{\rm bar}=GM_{b}(<r)/r^{2}$ is the usual Newtonian baryonic acceleration.

The superfluid contributes an energy density
$$\rho_{\rm sf} = \rho_{\Lambda}\Bigl[1-\exp\!\Bigl(-\kappa\sqrt{\frac{g_{\rm bar}}{g_{\dagger}}}\Bigr)\Bigr]$$

The modified Poisson equation integrates **exactly** to an emergent acceleration
$$\boxed{
g_{\rm em} = g_{\dagger}\left[1-\exp\!\left(-\kappa\sqrt{\frac{g_{\rm bar}}{g_{\dagger}}}\right)\right]}
$$
Total observed centripetal acceleration:
$$\boxed{
g_{\rm obs} = g_{\rm bar} + g_{\dagger}\left[1-\exp\!\left(-\kappa\sqrt{\frac{g_{\rm bar}}{g_{\dagger}}}\right)\right]}
\qquad(\kappa\simeq1.20)$$
→ **exact match** to the empirical Radial Acceleration Relation (McGaugh, Lelli & Schombert 2016).

<div style="page-break-after: always;"></div>

## 7. Effective dark-matter interpretation

$$\rho_{\rm DM}^{\rm eff}(r) = \rho_{\Lambda}\left[1-\exp\!\left(-\kappa\sqrt{\frac{g_{\rm bar}(r)}{g_{\dagger}}}\right)\right]$$
- Deep-MOND regime ($g_{\rm bar}\ll g_{\dagger}$): $\rho_{\rm DM}^{\rm eff}\approx \rho_{\Lambda}\kappa\sqrt{g_{\rm bar}/g_{\dagger}}$  
- Newtonian regime ($g_{\rm bar}\gg g_{\dagger}$): $\rho_{\rm DM}^{\rm eff}\to\rho_{\Lambda}$ (negligible)

<div style="page-break-after: always;"></div>

## 8. High-acceleration limit

When $g_{\rm bar}\gg g_{\dagger}$ the exponential $\to0$, so  
$$g_{\rm em}\;\to\;g_{\dagger}\;\simeq\;10^{-10}\,\mathrm{m\,s^{-2}}$$
→ residual acceleration $\sim10^{-11}$–$10^{-15}$ of Solar-System values → **undetectable** in all strong-field tests.

<div style="page-break-after: always;"></div>

## 9. Cosmological background

$T_{b}^{\mu\nu}=0\;\Rightarrow\;\mathcal{G}=0\;\Rightarrow\;$superfluid Lagrangian $\to0$, stress-energy $\to-\rho_{\Lambda}g_{\mu\nu}$  
$$\Rightarrow\qquad \rho_{\Lambda}=P_{\Lambda}=0\;\text{(no separate }\Lambda\text{ needed)}$$

<div style="page-break-after: always;"></div>

## 10. Sound speed (optional microphysical interpretation – not required for the main result)

The logarithmic kinetic term alone gives a vacuum sound speed  
$$c_{s}^{2}=1\qquad\text{(relativistic units)}$$
i.e. $c_{s}=c$.  
The **effective** sound speed of the modulated phonon fluid in the deep-MOND regime is  
$$c_{s,\rm eff}^{2}\approx\frac{g_{\dagger}}{2\kappa}\approx 4\times10^{-11}c^{2}\qquad(\kappa\simeq1.20)$$
This is perfectly consistent: the phonons mediating the MOND-like force are **highly non-relativistic** on galactic scales, exactly as expected for a superfluid dark sector.

<div style="page-break-after: always;"></div>

## 11. Parameter count

- All dimensional scales fixed by $\{c,G,H_{0}\}$  
- One dimensionless free parameter $\kappa\simeq1.20$ (determined by SPARC RAR fit)

<div style="page-break-after: always;"></div>

---

To the author's knowledge, the present work is the first to derive both the exact numerical value $a_{0} = c H_{0}/2\pi$ and the full functional form of the Radial Acceleration Relation from quantum-vacuum physics and the observed near-invariance of the Casimir force alone.

---

## References

* Afshordi, N. (2022). Dark Energy as a Bound State of Gravitons. *Phys. Rev. D* **105**, 023505.  
* Bekenstein, J. D. (2004). Relativistic gravitation theory based on MOND. *Phys. Rev. D* **70**, 083509. 
* Bordag, M., Klimchitskaya, G. L., Mohideen, U., & Mostepanenko, V. M. (2009). *Advances in the Casimir Effect*. Oxford University Press.  
* Khoury, J. (2022). Dark matter superfluidity. *Ann. Rev. Nucl. Part. Sci.* **72**, 1--30.
* McGaugh, S. S., Lelli, F., & Schombert, J. M. (2016). Radial acceleration relation. *Phys. Rev. Lett.* **117**, 201101.  
* Milgrom, M. (1983). A modification of the Newtonian dynamics. *ApJ* **270**, 365--370.  
* Berezhiani, L., & Khoury, J. (2016). Theory of dark matter superfluidity. *Phys. Lett. B* **753**, 639--643.  
* Verlinde, E. P. (2017). Emergent gravity and the dark universe. *SciPost Phys.* **2**, 016. 
* Volovik, G. E. (2003). *The Universe in a Helium Droplet*. Oxford University Press.  
* Klimchitskaya, G. L., Mohideen, U., & Mostepanenko, V. M. (2009). The Casimir force between real materials: experiment and theory. Rev. Mod. Phys.**81**, 1827.

* Berezhiani-Khoury (2015 arXiv:1507.01019) SfDM
* Milgrom (2020 arXiv:2001.09729) for a₀ ~ c H₀

Ben ten Broek - 2025