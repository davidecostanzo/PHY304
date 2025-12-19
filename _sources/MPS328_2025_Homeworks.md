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

Write energy conservation

$$
m_{\pi}=E_{\mu}+p
$$

Use

$$
p=\sqrt{E_{\mu}^{2}-m_{\mu}^{2}}
$$

Gives:

$$
m_{\pi}=E_{\mu}+\sqrt{E_{\mu}^{2}-m_{\mu}^{2}}
$$

We can isolate the square root and have

$$
m_{\pi}-E_{\mu}=\sqrt{E_{\mu}^{2}-m_{\mu}^{2}}
$$

And square

$$
m_{\pi}^{2}+E_{\mu}^{2}-2 m_{\pi} E_{\mu}=E_{\mu}^{2}-m_{\mu}^{2}
$$

And eventually

$$
E_{\mu}=\frac{m_{\pi}^{2}+m_{\mu}^{2}}{2 m_{\pi}}=109.8 \mathrm{MeV}
$$

**Feedback:**

- Many of you solved the equations to calculate the momentum of the pion and then derived the energy from there. This is correct, and was awarded full marks. However since the momentum was not required, it is faster to solve for E directly
- If you do calculate the momentum $p$, then the easier way to get to the energy is to use the energy conservation equation written at the beginning. So

$$
E_{\mu}=m_{\pi}-p
$$

Of course you can also use the kinematic formula below, but it's just more difficult

$$
E_{\mu}=\sqrt{p^{2}+m_{\mu}^{2}}
$$

- A few people got confused with the square root. Remember that the fact that

$$
E^{2}=p^{2}+m^{2}
$$

- Does NOT mean that E=p+m (!!)
- As a consequence the kinetic energy of a particle with mass is NOT equal to $p$ (!!)
```

### Question 2. Production of a a new particle (6 marks)
Electrons of energy 4.00 GeV are incident upon stationary target protons. A new particle $Q^0$ of unknown mass is produced as a result of the interaction

$$e^- + p \rightarrow e^- + p + Q^0$$

What is the maximum mass of $Q^0$ which can be produced?  Use any reasonable approximations, but justify your arguments. Make clear which statements you make are generally valid, and which are specific to the case of maximum $Q^0$ mass.

**Hint** Consider how the three particles will appear in the centre-of-mass frame in the special case of $Q^0$ being at its maximum mass. And remember that $E^2 – p^2$ (whether for an individual particle or a system of particles) is a Lorentz invariant, so it has the same value in all frames of reference. Use this to relate the initial state in the laboratory frame to the final state in the centre of mass frame.  

\[Mass of electron is 0.511 MeV/c$^2$;  that of proton is 938.3 MeV/c$^2$.\]

````{dropdown} Solutions and feedback
**Solution: ** 

A drawing of the physics process in the lab and centre-of-mass frames is:

```{figure} HW1b_figure.png
:alt: Schematics of the $e^- + p \rightarrow e^- + p + Q^0$ process
:name: FigHW1b
:width: 600px
:align: center
Schematics of the $e^- + p \rightarrow e^- + p + Q^0$ process.
```

For the maximum $Q^{0}$ mass, we must have minimum kinetic energy consistent with the conservation of momentum.
In the centre-of-mass frame zero kinetic energy is possible, i.e. the three particles are all at rest in this frame. This means that the Lorentz invariant

$$
\left(\sum E\right)^{2}-\left(\sum p\right)^{2}=\left(m_{e}+m_{p}+m_{Q}\right)^{2}
$$

This is calculated in the rest frame, however being an invariant, it will have the same value in any other reference frame, including the Lab frame

NOTE: The fact that the invariant is equal to the sum of the three masses squared is true only because we assume that the three particles are at rest in the centre-of-mass frame (!!) This is not true in general, e.g. if the particles are moving

Evaluating the Lorentz invariant in the Lab frame before the collision and equating it to the same quantity calculated after the collision

$$
\begin{gathered}
\left(E_{e}+m_{p}\right)^{2}-p_{e}^{2}=\left(m_{e}+m_{p}+m_{Q}\right)^{2} \\
E_{e}^{2}-p_{e}^{2}+2 E_{e} m_{p}+m_{p}^{2}=\left(m_{e}+m_{p}+m_{Q}\right)^{2}
\end{gathered}
$$

And so

$$
m_{e}+m_{p}+m_{Q}=\sqrt{m_{p}^{2}+m_{e}^{2}+2 E_{e} m_{p}}
$$

Which gives $m_{Q}=1.958 \mathrm{GeV} / \mathrm{c}^{2}$
The mass of the electron could be neglected in the equation above as it is much smaller than all the other masses

**Feedback:**

- You did not need to expand the expression $\left(m_{p}+m_{e}+m_{Q}\right)^{2}$. It's perfectly OK to do it, but in the end you get a value for $m_{p}+m_{e}+m_{Q}$ to which you can subtract the known masses of the proton and the electron
- The mass of the electron can be neglected, as it is smaller than all the other quantities. It makes the algebra a bit simpler, but perhaps not that much simpler to have to explain that.
- Some of you confused the fact that the Lorentz invariant quantity is independent of the reference frame, and instead assumed that the total energy is invariant. The expression for the total energy $E^{*}=m_{q}+m_{e}+m_{Q}$ is only valid in the centre of mass frame. In the lab frame the energy will have a different value $E=E_{e}+m_{p}$
- It is NOT correct to assume that $E^{*}=E$, in fact they are different
- The quantity that is independent of the reference frame is $E^{2}-p^{2}$ and that is calculated in the centre of mass frame as $\left(m_{p}+m_{e}+m_{Q}\right)^{2}$.
- If you do that, you'd get that the maximum mass of the Q particle is 4 GeV . This means that all the energy of the electron goes to the mass of $Q$. However it is not possible to do that, as it would violate momentum conservation


````


## Homework 2. Due on 25 November
This homework assesses Units 2, 3 and 4.


### Question 1: $\rho$ meson decays in flight
The neutral rho meson often decays into two charged pions, $\rho^{0} \rightarrow \pi^{+} \pi^{-}$. In a monoenergetic beam of these mesons, some decays are observed where one pion is at rest. What is the energy of the particles in the beam?

[Mass of the $\rho^0$ is 775 MeV/c$^2$ and mass of the pions is 135.0  MeV/c$^2$ (Note the correct charged pion mass should be 139.6 MeV/c$^2$).]

```{dropdown} Solution and feedback

Conservation of energy implies that the energy before the collision is equal to the energy after the collision:

$$
E_{\rho}=m_{\pi}+E_{\pi}
$$

Since one of the pions will be at rest, its total energy is equal to its mass
Momentum conservation implies that the momentum of the $\rho$ is transferred to the momentum of the pion in movement. We indicate this momentum with $p$.

Energy conservation is then written as

$$
E_{\rho}=m_{\pi}+\sqrt{p^{2}+m_{\pi}^{2}}
$$

We isolate the square root and square:

$$
\begin{gathered}
\left(E_{\rho}-m_{\pi}\right)^{2}=p^{2}+m_{\pi}^{2} \\
E_{\rho}^{2}-2 E_{\rho} m_{\pi}+m_{\pi}^{2}=p^{2}+m_{\pi}^{2}
\end{gathered}
$$

Remember that $E_{\rho}^{2}-p^{2}=m_{\rho}^{2}$

$$
E_{\rho}=\frac{m_{\rho}^{2}}{2 m_{\pi}}=2225 \mathrm{MeV}
$$

**Comments:**

- Most of you got to the correct result. Well done.
- Some of you took a longer route to calculate the momentum of the rho and then the energy from it. Other students calculated the energy of the moving pion and then that of the rho. This is correct and gets full marks. However it just takes a few extra steps. Practicing the faster method may save you some time in the exam.
- You should remember that for a particle of mass m:

$$
E^{2}=p^{2}+m^{2}
$$

We use this equation pretty much all the times there is a relativistic kinematic problem


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
(1), (3), (4) and (6) are allowed. Most of you did this correctly.

**Comments:**

- Different leptons have different lepton numbers that are individually conserved. Hence ( $v$ ) is NOT allowed since the electron and tau lepton numbers are not conserved
- The question was not asking about baryon number conservation explicitly. However the baryon number of the pions is always zero.
- The question ends with the word "Explain". This means you need to explain why a reaction is allowed/forbidden. A short explanation is sufficient, mentioning lepton number conservation, and not just the equation.

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
This question is similar to the one you saw in your previous homework. The minimum energy corresponds to the configuration when the pion and the neutron are at rest in the centre of mass frame. Hence the Lorentz invariant quantity is:

$$
E^{2}-p^{2}=\left(m_{n}+m_{\pi}\right)^{2}
$$

This quantity will be conserved as both energy and momentum are conserved in the interaction. Moreover the quantity will be the same in all reference frames. We calculate the Lorentz invariant quantity in the lab frame before the collision

$$
\left(E_{\gamma}+m_{p}\right)^{2}-p_{\gamma}^{2}=\left(m_{n}+m_{\pi}\right)^{2}
$$

For a photon of zero mass we have $p_{\gamma}=E_{\gamma}$

$$
\begin{gathered}
2 m_{p} E_{\gamma}+m_{p}^{2}=\left(m_{n}+m_{\pi}\right)^{2} \\
E_{\gamma}=\frac{\left(m_{n}+m_{\pi}\right)^{2}-m_{p}^{2}}{2 m_{p}}=151.5 \mathrm{MeV}
\end{gathered}
$$

**Comments:**

- The pion mass was not given in the question. Some of you used the correct value for the charged pion mass (139.8 MeV/$c^2$) and some used the neutral pion mass (135.0 MeV/c$^2$) given in question 1. Both solutions were marked as correct. 
- A few of you got confused with the reference frames. It is important to realise that in the centre of mass frame the proton is NOT at rest, so its energy will NOT be equal to its rest mass.
- The fact that the quantity $E^{2}-p^{2}$ is Lorentz invariant is key to solve this exercise. It is important that you justify this assumption in your solution.


```


### Question 4: Yukawa potential
In Exercise A, we saw that the Yukawa potential leads to an expression for the matrix element of

$$
\frac{4 \pi g^{2} \hbar^{2}}{q^{2}+m^{2} c^{2}}
$$

In the scattering of high energy neutrinos off electrons, it is observed that (after correcting for changing phase space or density-of-states effects) the differential cross-section falls by $10 \%$ as the momentum transfer $q$ increases from small values to $20 \mathrm{GeV} / c$. Use this information to estimate the mass of the exchanged boson.

```{dropdown} Solution and feedback
The cross section is proportional to the square of the matrix element given in the question. So we can write

$$
\sigma(q) \propto\left(\frac{4 \pi g^{2} \hbar^{2}}{q^{2}+m^{2} c^{2}}\right)^{2}
$$

Small values of $q$ means $q \ll m c$, hence the mass can be neglected. This means that

$$
\begin{gather*}
\frac{\sigma(q=20 \mathrm{GeV} / \mathrm{c})}{\sigma(q=0 \mathrm{GeV} / \mathrm{c})}=0.9 \\
\frac{m^{4} c^{4}}{\left(q^{2}+m^{2} c^{2}\right)^{2}}=0.9  \tag{Eq.1}\\
\frac{m^{2} c^{4}}{q^{2} c^{2}+m^{2} c^{4}}=\sqrt{0.9}
\end{gather*}
$$

(Where we added an extra $\mathrm{c}^{2}$ at the numerator and denominator to make sure everything is in GeV . Alternatively we can take $\mathrm{c=1}$ )

$$
m c^{2}=20 \sqrt{\frac{\sqrt{0.9}}{1-\sqrt{0.9}}} \mathrm{GeV}=86 \mathrm{GeV}
$$

**Comments:**

- A few people squared the terms in Eq 1 and had to calculate the roots of a quadratic equation. This is correct, but it takes longer, as a square root makes this much faster to calculate

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




## Exercise B. Elastic and inelastic scattering (not assessed)

These exercises revisit the topic of scattering. In the first one you calculate the form factor for a proton described as a solid sphere with uniform charge. In the second one, you calculate the value of the two variables defined in the deep inelastic scattering in the laboratory frame

### Question B1. Proton form factor
Use the fact that the form factor, $F(q)$, is the Fourier transform of the normalised charge distribution $\rho(r)$, which in the spherically symmetric case gives

$$
F(q)=\int \frac{4 \pi \hbar r}{q} \rho(r) \sin \frac{q r}{\hbar} d r
$$

to find an expression for $F(q)$ for a simple model of the proton considered as a uniform spherical charge distribution of radius $R$.

Show that the requirement that the wavelength associated with $q$ be much greater than the proton size is equivalent to the condition

$$
\frac{q R}{\hbar} \ll 1
$$

(Ignore factors like $2 \pi$.) Using your calculated expression for $F(q)$, demonstrate that in this limit the form factor reduces to 1.
Explain why is this condition satisfied by any form factor.

```{dropdown}  Solution
In this exercise we describe the scattering of an electron off a solid sphere target (the proton). In the form factor formula, we use  $q$ as the magnitude of the momentum transferred in the collision $q=\left|\boldsymbol{p}-\boldsymbol{p}^{\prime}\right|$. We also assume that the charge distribution $\rho(r)$ is normalised to 1. 

We define the radius of the proton as $R$ and we solve the problem in four parts:

**Part 1: Evaluate the form factor**

We can write an expression for $\rho(r)$ as:

$$
\begin{array}{ll}
\rho(r)=\frac{3}{4 \pi R^{3}} & \text { for } r<R \\
\rho(r)=0 & \text { for } r \geq R
\end{array}
$$

We use the formula for the form factor for a charge distribution with spherical symmetry.

$$
F(q)=\int \frac{4 \pi \hbar r}{q} \rho(r) \sin \frac{q r}{\hbar} d r=\frac{3}{4 \pi R^{3}} \int_{0}^{R} \frac{4 \pi \hbar r}{q} \sin \frac{q r}{\hbar} d r
$$

And, as seen in the lectures, we define a new variable $z=\frac{q r}{\hbar}$. Which implies

$$
r=\frac{z \hbar}{q} \quad d r=\frac{\hbar}{q}
$$

Changing variables gives

$$
F(q)=\frac{3}{4 \pi R^{3}} \int_{0}^{\frac{q R}{\hbar}} \frac{4 \pi \hbar}{q} \frac{z \hbar}{q} \sin z \frac{\hbar}{q} d z=3\left(\frac{\hbar}{q R}\right)^{3} \int_{0}^{\frac{q R}{\hbar}} z \sin z d z
$$

for simplicity we define $b=\frac{q R}{\hbar}$ and get the integral in a nice form

$$
F(q)=3 b^{-3} \int_{0}^{b} z \sin z d z
$$

The integral can be solved by parts to obtain

$$
F(q(b))=3 b^{-3}(\sin b-b \cos b)
$$

Note, that this result can be found on the textbook by Martin.

**Part 2: proton radius much smaller than the wavelength**
The wavelength associated with the momentum transfer $q$ is given by the De Broglie expression

$$
\lambda=\frac{h}{q}
$$

The fact that the proton is much smaller than the wavelength associated with the electron is expressed by

$$
R \ll \lambda=\frac{h}{q}
$$

which means that

$$
\frac{R q}{h} \ll 1 \quad \text { or similarly } \quad b=\frac{R q}{\hbar} \ll 1
$$

**Part 3: Limit of $F(q)$ for $b \ll 1$ **

We need to calculate

$$
\lim _{b \rightarrow 0} F(q)=\lim _{b \rightarrow 0} 3 \frac{\sin b-b \cos b}{b^{3}}=1
$$

and use the de l'Hopital rule (three times) to show that this limit is equal to 1. (Or alternatively a Taylor expansion up to the power of $b^{3}$.

**Part 4: Form factor in the limit $R \ll \lambda$ **

There is a physics explanation of the reason why the form factor is 1 when the size of the charge distribution is smaller than the wavelength. In the lectures we saw that the cross section of an elastic scattering process is written as

$$
\left.\frac{d \sigma}{d \Omega}=|F(q)|^{2} \frac{d \sigma}{d \Omega}\right)_{\text {point-like }}
$$

in other words the form factor modifies the cross section expected for a point like object to account for an extended charge distribution. If the wavelength of the particle used to probe the distribution is much bigger than the charge distribution itself, the charge distribution is observed as a point-like distribution. Hence the form factor has to be 1 in this limit.




```


### Question B2. Deep inelastic scattering variables
We defined the deep inelastic scattering as the process

$$
e+p \rightarrow e+X \text { (hadrons) }
$$

And defined the variables as:

- $E_{i}, \boldsymbol{p}_{\boldsymbol{i}}$ as the energy and momentum of the incoming electron
- $E_{f}, \boldsymbol{p}_{f}$ as the energy and momentum of the outgoing electron
- $M$ as the mass of the proton
- $W$ as the invariant mass of the hadron system, and $E_{W}, \boldsymbol{p}_{W}$ the total energy and momentum of the system
- $Q^{2}=-\left[\left(E_{i}-E_{f}\right)^{2}-\left(\boldsymbol{p}_{\boldsymbol{i}}-\boldsymbol{p}_{f}\right)^{2}\right]$
- The variable $\nu$ defined as $2 M \nu=W^{2}+Q^{2}-M^{2}$

Show that in the laboratory frame, where the proton is at rest, the two variables can be written

- $Q^{2}=2 E_{i} E_{f}(1-\cos \theta)$
- $\nu=E_{i}-E_{f}$

Show that in case of an elastic scattering the ratio x is equal to 1, where

$$
x=\frac{Q^{2}}{2 M v}
$$

[Note the mass of the electron should be neglected]

```{dropdown}  Solution
(Note: solutions amended on 19 Dec 2026)

The question asks to neglect the mass of the electron, which means that

$$
E_i=p_i \quad \text { and } \quad E_f=p_f
$$

(using, as usual $\mathrm{c=1}$ )

**Part 1: Calculate $Q^{2}$ in the lab frame**

Using this approximation we can write

$$
Q^{2}=-\left[E_i^2+E_f^2-2 E_i E_f-E_i^2-E_f^2+2 E_i E_f \cos \theta\right]=2 E_i E_f(1-\cos \theta)
$$

where we used the fact that $\left|\boldsymbol{p_i}-\boldsymbol{p_f}\right|^{2}=p_i^{2}+p_f^{2}-2 \boldsymbol{p_i} \cdot \boldsymbol{p_f}=E_i^{2}+E_f^{2}-2 E_i E_f \cos \theta$, with $\theta$ being the angle between the incoming and outgoing momenta.

**Part 2: Calculate $\nu$ in the lab frame**

We start by writing the equations for conservation of energy and momentum

$$
\begin{aligned}
& E_i+M=E_f+E_{W} \\
& \boldsymbol{p_i}=\boldsymbol{p_f}+\boldsymbol{p}_{\boldsymbol{W}}
\end{aligned}
$$

Rearranging

$$
\begin{aligned}
E_i-E_f&=E_{W}-M \\
\boldsymbol{p_i}-\boldsymbol{p_f}&=\boldsymbol{p}_{\boldsymbol{W}}
\end{aligned}
$$

Squaring the two and subtracting (as we usually do)

$$
\left(E_i-E_f\right)^{2}-\left(p_i-p_f \right)^{2}=E_{W}^{2}-p_{W}^{2}+M^{2}-2 E_{W} M
$$

The right-hand side of the equation can be recognised as $-Q^{2}$, while $E_{W}^{2}-p_{W}^{2}=W^{2}$, e.g. the invariant mass of the hadronic system. Hence

$$
-Q^{2}=W^{2}+M^{2}-2 E_{W} M
$$

From the energy conservation

$$
E_{W}=E_i-E_f+M
$$

which gives

$$
2 M\left(E_i-E_f \right)=W^{2}+Q^{2}-M^{2}
$$

Implying that

$$
\nu=E-E
$$

**Part 3: Elastic scattering limit**

If the scattering is elastic, then $\nu$ and $Q^{2}$ are no longer independent. In particular the hadronic component of the final state is the proton alone, which means that the invariant mass of the final system, which we indicate with $W$, is the mass of the proton. Or $W=M$. This means that for elastic scattering

$$
2 M v=Q^{2}
$$

leading to the ratio $x=1$




```



## Exercise C. Mock paper with solutions 
**(not assessed)**

Mock exam paper and solutions are available on Blackboard under "Mock Exam"

