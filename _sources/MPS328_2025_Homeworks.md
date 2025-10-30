(Homework)=
# Homeworks and formative assessments
Roughly every two weeks, you will be given an exercise, which should be attempted by the following week. 
The purpose of the homeworks is to help your revision of the lecture material and to give you practice in problem solving.  
Two of the exercises are assessed homeworks, which must be handed in the following week.  These will be marked (the total homework mark counting 15% towards this module), and will be returned to you, with comments, before the next homework is set.  The other exercises are no less important to your understanding of the course, and should also be attempted seriously.  Solutions will be provided two weeks after each non-assessed exercise is set.


## Homework 1. Due on 21 October
This homework will assess Unit 1 and is made of two questions on relativistic kinematics. 

### Question 1. Two body decay (4 marks)
Consider the decay of a charged pion ($\pi^+$) into a muon ($\mu^+$) and a neutrino ($\nu_\mu$)

$$
\pi^+ \rightarrow \mu^+\  \nu_{\mu}
$$

Evaluate the energies of the muon and the neutrino in the pion rest frame.

\[Mass of the pion ($\pi^+$) is 139.6 MeV/c$^2$, mass of the muon ($\mu^+$) is 105.7 MeV/c$^2$, and the neutrino ($\nu_\mu$) is masseless \]
```{dropdown} Solutions and feedback
Solutions to be released on 4 November

```

### Question 2. Production of a a new particle (6 marks)
Electrons of energy 4.00 GeV are incident upon stationary target protons. A new particle $Q^0$ of unknown mass is produced as a result of the interaction

$$e^- + p \rightarrow e^- + p + Q^0$$

What is the maximum mass of $Q^0$ which can be produced?  Use any reasonable approximations, but justify your arguments. Make clear which statements you make are generally valid, and which are specific to the case of maximum $Q^0$ mass.

**Hint** Consider how the three particles will appear in the centre-of-mass frame in the special case of $Q^0$ being at its maximum mass. And remember that $E^2 – p^2$ (whether for an individual particle or a system of particles) is a Lorentz invariant, so it has the same value in all frames of reference. Use this to relate the initial state in the laboratory frame to the final state in the centre of mass frame.  

\[Mass of electron is 0.511 MeV/c$^2$;  that of proton is 938.3 MeV/c$^2$.\]

```{dropdown} Solutions and feedback
Solutions to be released on 4 November

```



## Homework 2. Due on 25 November
This homework assesses Units 2, 3 and 4.


### Question 1: $\rho$ meson decays in flight
The neutral rho meson often decays into two charged pions, $\rho^{0} \rightarrow \pi^{+} \pi^{-}$. In a monoenergetic beam of these mesons, some decays are observed where one pion is at rest. What is the energy of the particles in the beam?

[Mass of the $\rho^0$ is 775 MeV/c$^2$ and mass of the pions is 135 MeV/c$^2$.]

```{dropdown} Solution and feedback
Solutions to be released on 9 December
```

### Question 2: Allowed and forbidden decays
Which of the following reactions are allowed by lepton number conservation, and which are forbidden? Explain.
1.  $\tau^{+} \rightarrow \mu^{+} v_{\mu} \bar{v}_{\tau}$
2.  $\pi^{+} \rightarrow \mu^{+} \gamma$
3.  $\pi^{+} \rightarrow \mu^{+} v_{\mu}$
4.  $\pi^{0} \rightarrow e^{+} e^{-} \gamma$
5.  $\tau^{+} \rightarrow e^{+} \gamma$
6.  $\tau^{-} \rightarrow \pi^{-} v_{\tau}$

```{dropdown} Solution and feedback
Solutions to be released on 9 December
```

### Question 3: Photon-proton capture
A high energy photon can excite the quarks in a proton, producing a short-lived state which rapidly forms a nucleon and pion. Calculate the minimum photon energy required for the following reaction to occur when the target is a stationary proton

$$
\begin{equation*}
\gamma p \rightarrow n \pi^{+}
\end{equation*}
$$

Hint: consider the final state in the centre of mass frame.

```{dropdown} Solution and feedback
Solutions to be released on 9 December
```


### Question 4: Yukawa potential
In Exercise A, we saw that the Yukawa potential leads to an expression for the matrix element of

$$
\frac{4 \pi g^{2} \hbar^{2}}{q^{2}+m^{2} c^{2}}
$$

In the scattering of high energy neutrinos off electrons, it is observed that (after correcting for changing phase space or density-of-states effects) the differential cross-section falls by $10 \%$ as the momentum transfer $q$ increases from small values to $20 \mathrm{GeV} / c$. Use this information to estimate the mass of the exchanged boson.

```{dropdown} Solution and feedback
Solutions to be released on 9 December
```


## Exercise A. Fermions \& Bosons 
**(not assessed)**

### Question A1. Proton form factor
In the lectures, we showed that the form factor $F(q)$ is the 3-D Fourier transform of the normalised charge distribution $\rho(\boldsymbol{r})$

$$
F(q)=\int \rho(\boldsymbol{r}) e^{i \boldsymbol{q} \cdot \boldsymbol{r} / \hbar} d^{3} \boldsymbol{r}
$$
  
For a simplified model of a proton's charge distribution, $\rho(r)=C \frac{e^{-r / R}}{r}$
1. Find the constant of proportionality $C$ required to normalise $\rho$ correctly.
2.  Show that $F(q)=\frac{1}{1+\frac{q^{2} R^{2}}{\hbar^{2}}}$.
3.  Give an interpretation of the constant $R$
  
````{dropdown} Solution
**Part 1: normalisation**

The normalisation factor $C$ should be such that the integral over all space of the charge distribution should be equal to 1.

$$
\begin{aligned}
\int \rho(r) d^3 r &= 1 \\
\int C \frac{e^{-r / R}}{r} d^3 r &=1
\end{aligned}
$$

The integral should be done in spherical coordinates replacing 

$$
d^3 r = \sin \theta r^2\, d\theta\, d\phi\, dr 
$$

Since there is no dependency on the polar coordinates $\theta$ and $\phi$ the integral on the polar variables gives us a $4\pi$ factor hence

$$
\begin{aligned}
1 &= \int_0^\infty C \frac{e^{-r / R}}{r} 4\pi r^2 dr  \\
\frac{1}{4\pi C} &= \int_0^\infty r e^{-r / R} dr 
\end{aligned}
$$

Integrating by parts we have

$$
\begin{aligned}
\frac{1}{4\pi C} &= \left[-R e^{-r/R} r \right]_0^\infty -\int_0^\infty -R e^{-r/R} dr  \\
\frac{1}{4\pi C} &= 0 + \left[-R^2 e^{-r/R} \right]_0^\infty    \\
\frac{1}{4\pi C} &= R^2  \\
C &= \frac{1}{4\pi R^2}
\end{aligned}
$$

**Part 2: Form factor**
We repeat the integration similarly to what was done in Example 2.3. We integrated in polar coordinates in $\phi$, $\cos \theta$ and finally on $r$. The details are

$$
\begin{aligned}
F(q) &= \int_0^\infty \int_{-1}^{+1} \int_0^{2\pi} C \frac{e^{-r / R}}{r} e^{iqr \cos \theta / \hbar} r^2 dr\, d\cos \theta\, d\phi \\
&= 2 \pi C \int_0^\infty r e^{-r/R} \left[ \frac{\hbar}{iqr} e^{iqr \cos\theta / \hbar} \right]_{-1}^{+1} dr \\
&= \frac{2 \pi C \hbar}{iq} \int_0^\infty e^{-r/R} \left(e^{iqr/\hbar} -  e^{-iqr/\hbar} \right) dr \\
&= \frac{2 \pi C \hbar}{iq} \int_0^\infty e^{\left({-\frac{1}{R} +  \frac{iq}{\hbar}}\right)r} - e^{\left( {-\frac{1}{R} -  \frac{iq}{\hbar}}\right)r} dr \\
&= \frac{2 \pi C \hbar}{iq}  \left[ \frac{e^{\left(-\frac{1}{R} +  \frac{iq}{\hbar}\right)r}}{-\frac{1}{R} +  \frac{iq}{\hbar}} - \frac{e^{\left(-\frac{1}{R} -  \frac{iq}{\hbar} \right)r}}{-\frac{1}{R} -  \frac{iq}{\hbar}} \right]_0^\infty 
\end{aligned}
$$

The exponential terms $e^{-r/R}$ will give us 0 for $r\rightarrow \infty$ and $1$ for $r=0$, so we can simplify as

$$
\begin{aligned}
F(q) &= \frac{2 \pi C \hbar}{iq} \left( \frac{-1}{-\frac{1}{R} + \frac{iq}{\hbar} } - \frac{-1}{-\frac{1}{R} - \frac{iq}{\hbar} } \right) \\
&= \frac{2 \pi C \hbar}{iq} \left( \frac{1}{\frac{1}{R} - \frac{iq}{\hbar} } - \frac{1}{\frac{1}{R} + \frac{iq}{\hbar} } \right) \\
&= \frac{2 \pi C \hbar}{iq} \frac{\left(\frac{1}{R} + \frac{iq}{\hbar} \right) - \left(\frac{1}{R} - \frac{iq}{\hbar} \right) }{\frac{1}{R^2}+ \frac{q^2}{\hbar^2}} \\
&= \frac{2 \pi C \hbar}{iq} \frac{2 \frac{iq}{\hbar}}{ \frac{1}{R^2} +\frac{q^2}{\hbar^2}} \\
&= \frac{4 \pi C}{\frac{1}{R^2} +\frac{q^2}{\hbar^2}}
\end{aligned}
$$

And finally replacing the value obtained for $C$ in part 1 we get

$$
F(q) = \frac{1}{1+\frac{q^2R^2}{\hbar^2}}
$$

We should note that for $q=0$ we get $F(q)=1$ as expected. 

**Part 3: Interpretation**
If we plot the function for $r e^{-r/R}$ we can examine the functional dependence of $\rho(r)$.  The charge distribution will have a maximum at $r=R$ as in the figure below, and will extend to larger values of $R$. Hence $R$ would correspond to the radius where the nuclear density is at a maximum. 

We can exclude this distribution as, experimentally, we expect the cross section and $F(q^2)$ to have dips as a function of $q$ (see example 2.5), while for this particular charge distribution the form factor is a continuos function. 

```{figure} ExA3.png
:alt: charge distribution for exercise A1
:name: FigHWA3
:width: 600px
:align: center
$r e^{-r/R}$ distribution, plotted to study the behaviour of the function $\rho(r)$. The x-axis would represent the value of $r/R$, and we can see a maximum for $r=R$. 
```



````

### Question A2. Yukawa Potential

Earlier in the course, we used the Born approximation to show that in the case of scattering with a momentum transfer $q$ from a spherically symmetric potential $U(r)$, the matrix element is proportional to

$$
f(\boldsymbol{q})=\int U(\boldsymbol{r}) e^{i \boldsymbol{q} \cdot \boldsymbol{r} / \hbar} d \boldsymbol{r}
$$

For the case of the Yukawa potential,

$$
U(r)=\frac{g^{2}}{r} e^{-r / R}
$$

( with $R=\hbar / m c$, and $m$ the mass of the exchanged boson mediating the force) show that the matrix element evaluates to

$$
\frac{4 \pi g^{2} \hbar^{2}}{q^{2}+m^{2} c^{2}}
$$

When an electron scatters electromagnetically off a nucleus, the exchanged boson is the massless photon, and at low energies the nucleus can be considered to remain effectively at rest. Show that in case the scattering cross section yields to the Rutherford scattering formula with the usual angular dep$

$$
\frac{d \sigma}{d \Omega} \propto \frac{1}{\sin ^{4} \theta / 2}
$$

```{dropdown} Solution
**Part 1: Calculations** 

To calculate the integral

$$
f(q^2) = \int \frac{g^{2}}{r} e^{-r / R} e^{i \boldsymbol{q} \cdot \boldsymbol{r} / \hbar} d \boldsymbol{r}
$$

we reuse the derivation from {numref}`Sec:Coulomb` where we introduced a factor $\lambda$ and then set $\lambda=0$. The integral is the same provided we replace:

$$
\lambda = \frac{1}{R} \ \ \ \ g^2=\frac{zZe^2}{4\pi\epsilon_0}
$$

and we no longer assume that $\lambda=0$. If we take the result obtained before setting $\lambda=0$ the result of the integral becomes

$$
\begin{align}
f(q^2) &= \frac{2 \pi g^2 \hbar}{iq} \left[\frac{1}{\lambda - \frac{iq}{\hbar}} - \frac{1}{\lambda + \frac{iq}{\hbar}} \right ]
&= 4 \pi g^2 \hbar^2 \frac{1}{\lambda^2 \hbar^2 +q^2} 
\end{align}
$$

Using the definition of $\lambda$ and $R$ we get

$$
\lambda^2 \hbar^2 = \frac{\hbar^2}{R^2} = m^2 c^2
$$

Yielding the final result

$$
f(q^2) = \frac{4 \pi g^{2} \hbar^{2}}{q^{2}+m^{2} c^{2}}
$$

**Part 2: Coulomb approximations**

If the propagator is a photon the formula for $f(q^2)$ reduces to the formula we derived earlier and in particular since $m=0$ we have

$$
f(q^2) \propto \frac{1}{q^2}
$$

In {numref}`Sec:Rutherford` we evaluated $q=2p \sin \theta/2$ and the cross section is proportional to the square of $f(q^2)$, e.g.

$$
\frac{d\sigma}{d\Omega} \propto \frac{1}{q^4} \propto \frac{1}{\sin^4 \theta/2}
$$

so in the case of a scattering off a point-like nucleus which is mediated by a photon we recover the formula for the Rutherford scattering as expected. 
```




## Exercise B. Elastic and inelastic scattering 
**(not assessed)**

To be released on 17 November

## Exercise C. Mock paper with solutions 
**(not assessed)**

To be released on 8 December


