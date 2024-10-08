# 6 Weak interactions and invariance principles 

### Characteristics of weak interactions

In the previous sections we talked about interactions that are mediated by photons (QED) and gluons (QCD). In terms of relative strength we said that strong interactions are "stronger" than electromagnetic ones. In the same spirit we introduce weak interaction which, as the word says, have a weaker relative strength than the electromagnetic ones. Weak interactions are responsible for radioactive beta decays in nuclear physics, as well as many other phenomena in particle physics, which are the subject of this unit.

As previously mentioned, weak interactions are mediated by massive bosons, the $W^{ \pm}$and the $Z^{0}$ with a mass of approximately $80 \mathrm{GeV} / \mathrm{c}^{2}$ and $91 \mathrm{GeV} / \mathrm{c}^{2}$, respectively. All fermions in the standard model interact via the exchange of weak bosons, this includes the leptons (both charged and neutrinos) and the quarks. Therefore neutrinos can only interact via weak interactions, which makes very difficult to detect, as their interaction cross section is very small.

There are two types of weak interactions, based on the boson being exchanged

1) Charged-current interactions are mediated by the exchange of $W^{ \pm}$bosons with diagrams like the one in Fig 6.1(a) and (b). Interactions between different lepton family are forbidden, while interactions between different quark families are allowed. Hence the conservation of the 3 lepton numbers and one baryon number. Charged-current interactions are responsible for the nuclear $\beta$-decays, and the muon decay, see Fig 6.2 (right), and for neutrino interactions, see Fig 6.2 (left)
2) Neutral current interactions are mediated by the exchange of $Z^{0}$ bosons and interactions are with leptons or quarks of the same type (or flavour).

Fig 6.1 Weak interactions vertexes mediated by the W boson coupling leptons (left) and quarks (right)

![](https://cdn.mathpix.com/cropped/2024_08_10_e145a9c7f4ab84bf3ab7g-02.jpg?height=347&width=555&top_left_y=266&top_left_x=451)

(a)

![](https://cdn.mathpix.com/cropped/2024_08_10_e145a9c7f4ab84bf3ab7g-02.jpg?height=275&width=564&top_left_y=311&top_left_x=1203)

(b)

Fig 6.2. (a) Neutrino-neutron interactions mediated by the charged current. (b) Muon decay. From Perkins fig 2.6.

### Comparing interaction types

Now that we introduced the three fundamental interactions in particle physics, we can compare them and review how we evaluate their Feynman diagrams to study physical processes. Figure 6.3 shows Feynman diagrams comparing simple $2 \rightarrow 2$ processes mediated by electromagnetism, strong and weak forces.

In Unit 2 we discussed the Fermi golden rule and we said that the rate of a process is proportional to the square of the matrix element. We defined the matrix element as the Fourier transform of the potential and described it using a Feynman diagram. The matrix element is proportional to

- The product of the "charges" at the vertexes. In the case of electromagnetism, that is the electric charge, or the constants $g_{s}, g_{w}$ in the case of the strong and weak interactions, respectively
- The distance $1 / \mathrm{r}$ in the case of massless boson mediating the force or $\frac{1}{r} e^{-r / R}$, where the range R is related to the mass of the mediator $R=\hbar / m c$ as shown in Exercise A .

We express the interaction rates in terms of proportionality to the factors above, so we have

- For the electromagnetic interaction, the potential is proportional to

$$
U \propto e^{2} / r
$$

therefore the matrix element is proportional to its Fourier transform, which we calculated as

$$
M_{f i} \propto e^{2} / q^{2}
$$

and the rate is proportional to

$$
W \propto \frac{e^{4}}{q^{4}} \propto \frac{\alpha_{e m}^{2}}{q^{4}}
$$

Which we showed leads to an expression for the Rutherford cross section and its dependency on $\sin ^{2} \theta / 2$.

- Likewise for the strong interaction at short distances (《1 fm ), we can evaluate a rate of interaction that depends on the strong constant $\alpha_{S}$

$$
W \propto \frac{g_{s}^{4}}{q^{4}} \propto \frac{\alpha_{s}^{2}}{q^{4}}
$$

- For weak interactions, the same argument still applies, except that when we calculate the Fourier transform of the potential expression, we need to use the formula for the Yukawa coupling and therefore

$$
W \propto \frac{g_{W}^{4}}{\left(q^{2}+M^{2} c^{2}\right)^{2}} \propto \frac{\alpha_{W}^{2}}{\left(q^{2}+M^{2} c^{2}\right)^{2}}
$$

For interactions where the momentum transfer (q) is smaller than the mass of the mediator, e.g. when the interaction is at a scale of a few GeV or smaller, we can neglect the value of $q$ at the denominator and the expression for the rate is given by

$$
W \propto \frac{\alpha_{W}^{2}}{M^{4}}
$$

![](https://cdn.mathpix.com/cropped/2024_08_10_e145a9c7f4ab84bf3ab7g-03.jpg?height=535&width=1580&top_left_y=858&top_left_x=244)

Fig 6.3 Three fundamental interaction compared, $e^{+} e^{-} \rightarrow \mu^{+} \mu^{-}$(left, electromagnetic interaction), $\bar{u} u \rightarrow \bar{d} d$ (middle, strong interaction) and $e \overline{v_{e}} \rightarrow \mu \overline{\nu_{\mu}}$ (left, weak interaction)

### Particle decays

The decay of particles is also described by Feynman diagrams in a way that is similar to the treatment we used to study the cross section of particle interaction. For particle decays we apply once again the Fermi golden rule and their rate of decay is proportional to the square of the matrix element. Therefore we expect larger rate of decays, when particle decay via the strong interaction, with lower rates for the electromagnetic interaction, and even lower when weak interactions mediate the decay.

In the case of weak decays, which are observed also in nuclear physics, the original Fermi theory of beta decay involved a point like "contact interaction" with a coupling constant

$$
G=1.166 \times 10^{-5} \mathrm{GeV}^{-2} \quad \text { (i.e. weak compared with } \frac{1}{137} \text { ). }
$$

This value of $G$ is compatible with all the observed decay rates for the muon decay and other nuclear decay processes, and is independent on the energy allowed in the decay.

The effective strength of the weak interaction at low energies thus depends both on the coupling of the W to fermions, $g$, and upon its mass. At low energies, the constant $G$ is proportional to

$$
\lim _{q^{2} \rightarrow 0} G \propto \frac{\alpha_{W}^{2}}{\left(q^{2}+m_{W}^{2}\right)^{2}}=\frac{\alpha_{W}^{2}}{m_{W}^{4}}
$$

so if $m_{w}$ is large, the weak coupling $g$ is not necessarily very small. In fact we will see that the weak and electromagnetic theories are "unified" as a single theory which goes under the name of electroweak theory, with the consequence that $g_{W} \approx e$. The so-called weakness of the weak interactions is due to the presence of the mass term in the propagator that causes the behaviour we observe at the GeV energy scale.

Example 6.1. The lifetime of the $\pi^{+}$(bound $u \bar{d}$ state) is $2.6 \times 10^{-8} \mathrm{~s}$, while the lifetime of the $\pi^{0}$ (bound $\bar{u} u$ state) is $8.4 \times 10^{-17}$ s. Sketch the Feynman diagrams for the decay of these two particles and show that the $\pi^{+}$decays via a weak interaction, while the $\pi^{0}$ decays via an electromagnetic interaction.

## Solution:

The Feynman diagrams for the two decays are sketched below

![](https://cdn.mathpix.com/cropped/2024_08_10_e145a9c7f4ab84bf3ab7g-04.jpg?height=389&width=1566&top_left_y=1005&top_left_x=242)

The $\pi^{+} \rightarrow \mu^{+} v_{\mu}$ decay is mediated by a weak interaction, while the $\pi^{0} \rightarrow \gamma \gamma$ is mediated by the electromagnetic interaction. As a consequence the lifetime of the charged pion will be proportional to $\alpha_{W}^{2}$, and the lifetime of the neutral pion is proportional to $\alpha_{e m}^{2}$. Therefore the lifetime of the charged pion is much longer than that of the neutral pion.

### Experimental results on weak interactions

The weak interaction responsible for beta decay involves a charged (or charge-changing) current, and the W must exist as $\mathrm{W}^{+}$and $\mathrm{W}^{-}$. This suggested there might also be a weak neutral current, propagated by a third boson, the $Z^{0}$. Evidence for this was first observed at CERN in 1973 in the form of neutrino interactions $v_{\mu} N \rightarrow v_{\mu} X$ (where $N$ is a nucleus and $X$ a hadronic system) and $v_{\mu} \mathrm{e} \rightarrow v_{\mu} \mathrm{e}$. However, this exposed a new theoretical problem. At sufficiently high energy, it should be possible to produce real $\mathrm{W}^{+} \mathrm{W}^{-}$pairs in $\mathrm{e}^{+} \mathrm{e}^{-}$annihilation through the $\mathrm{Z}^{0}$, and a calculation shows that at very high energies this cross section again becomes unphysically large. The diagram for this process would be cancelled by that corresponding to electromagnetic annihilation to $\mathrm{W}^{+} \mathrm{W}^{-}$through a photon, but this cancellation will only occur if the weak coupling constant $g$ is equal to the electromagnetic coupling, $\sqrt{ } \alpha$. (Note that at such very high energies, the mass of the $Z^{0}$ becomes insignificant.) Although this argument was originally a theoretical one, experimental evidence from $\mathrm{W}^{+} \mathrm{W}^{-}$ production at the large electron-positron collider, LEP, many years later confirmed this prediction, and such results will be presented in the lectures.

In the 1960's, Glashow, Salam and Weinberg proposed the unification of the electromagnetic and weak interactions as a single gauge theory with a common coupling constant. This implied that the mass of the W and Z must be about $90 \mathrm{GeV} / \mathrm{c}^{2}$. (At low energies, the W and Z cannot
be produced as real particles, and the electromagnetic and weak interactions appear as separate processes.) The first real weak bosons were produced at the CERN antiproton-proton collider, which effectively allowed antiquarks and quarks to interact. In 1982, processes such as

$$
d \bar{u} \rightarrow W \rightarrow e^{-} \overline{v_{e}}
$$

were observed in the UA1 and UA2 experiments, while the next year the rarer but cleaner signature

$$
q \bar{q} \rightarrow Z^{0} \rightarrow e^{+} e^{-}
$$

was observed.

In the late 1980s, a large $\mathrm{e}^{+} \mathrm{e}^{-}$collider, LEP, was built at CERN, allowing the "mass production" of $Z^{0}$ bosons. By colliding the particles with exactly the right energy to supply the $Z$ mass, a large resonance in the cross section occurs, and now several million $Z^{0}$ decays have been observed, shared between the 4 large experiments. Subsequently, the Large Hadron Collider, is now observing billion of events where $W$ and $Z$ bosons are produced, leading to the measurement of their masses with a precision of 12 MeV and 2 MeV respectively.

The $Z$ couples to all fermion-antifermion pairs, including neutral neutrinos. The decays to neutrinos are basically undetectable, as neutrinos leave no tracks and can pass through large amounts of material without interacting, but nonetheless they modify the properties of the $Z$. Results on neutrino production were some of the most important to emerge in the early days of LEP!

The $Z$ is a very short-lived particle, with a lifetime of only $2.6 \times 10^{-25} \mathrm{~s}$. The uncertainty principle implies a relationship between the uncertainty in energy (and hence mass) and that in time. Thus, in $\mathrm{e}^{+} \mathrm{e}^{-}$annihilation, the $\mathrm{Z}^{0}$ is seen with a width in mass of about 2.5 GeV (FWHM), as shown in fig. 6.4. Decays of the $Z$ into neutrinos have two effects. Each species of neutrino decreases the number of visible $Z$ decays by $13 \%$ and also shortens the lifetime, and hence increases the width by 0.176 GeV . Measurements by the ALEPH collaboration at LEP show that the data imply $N_{v}=2.994 \pm 0.012$ i.e. 3 ! There are therefore no new generations of lepton and neutrino (unless the mass of the new neutrino is greater than $45 \mathrm{GeV} / \mathrm{c}^{2}$ - very different from the three known species, which are almost massless).

![](https://cdn.mathpix.com/cropped/2024_08_10_e145a9c7f4ab84bf3ab7g-06.jpg?height=1257&width=1286&top_left_y=228&top_left_x=388)

Fig. 6.4 Cross sections for $e^{+} e^{-} \rightarrow$ hadrons as a function of centre-of-mass energy. The Standard Model predictions for $N_{v}=2,3$ and 4 are shown.

### Symmetries and invariance principles

One remarkable property of weak interaction is that they violate parity and charge conjugation, which are invariance principle that were considered central in physics until the 1950s. To understand the implications of this violation principle we need to first discuss symmetries and how they relate to physics.

Without invariance principles, there would be no laws of physics! We rely on the results of experiments remaining the same from day to day and place to place. An invariance principle reflects a basic symmetry, and is always intimately related to a conservation law (and to a quantity that cannot be determined absolutely). The proofs presented here rely on some key results from quantum mechanics.

Some classical invariance principles are related to the nature of space-time. We start by looking at continuous symmetries, such as invariance under space and time translation. These will be discussed also in your other quantum mechanics courses. We then move on to discuss invariance under discrete symmetries, which is at the core of particle physics.

## Hermitian operators

The first assumption we make is that operators corresponding to a physical observable in quantum mechanics are Hermitian, e.g. for any wave function we can write

$$
(\hat{A} \psi)^{*}=\psi^{*} \hat{A}
$$

Among physical observables, we should include the Hamiltonian $\widehat{H}$ of a system.

## Conserved quantities

Next we show the important result that operators which commute with the Hamiltonian (the operator for total energy) correspond to quantities which are conserved, that is they are "constants of the motion".

Consider an operator $\hat{A}$ that does not depend on time, e.g. $\frac{\partial \hat{A}}{\partial t}=0$, in this case the observed value of $\hat{A}$ for a wavefunction $\psi(x, t)$ is calculated as

$$
\langle a\rangle(t)=\int \psi^{*}(x, t) \hat{A} \psi(x, t) d^{3} \boldsymbol{x}
$$

And the derivative is

$$
\frac{d\langle a\rangle}{d t}=\int \frac{\partial \psi^{*}}{\partial t} \hat{A} \psi d^{3} \boldsymbol{x}+\int \psi^{*} \hat{A} \frac{\partial \psi}{\partial t} d^{3} \boldsymbol{x}
$$

We now use the time-dependent Schrödinger equation and substitute

$$
\begin{gathered}
\widehat{H} \psi=i \hbar \frac{\partial \psi}{\partial t} \\
\frac{d\langle a\rangle}{d t}=\int\left(\frac{i}{\hbar} \psi^{*} \widehat{H} \hat{A} \psi-\frac{i}{\hbar} \psi^{*} \hat{A} \widehat{H} \psi\right) d^{3} x=\frac{i}{\hbar} \int \psi^{*}[\widehat{H}, \hat{A}] \psi d^{3} \boldsymbol{x}
\end{gathered}
$$

Showing that if the commutator of the operator $\hat{A}$ with the Hamiltonian is zero, the observed quantities are invariant, which also means the eigenvalues of the operator are conserved quantities.

## Translation invariance

We now consider the translation operator $D$ that moves the coordinate $x$ by a quantity $\delta x$. For simplicity, we consider only one spatial coordinate.

$$
\widehat{D} \psi(x, t)=\psi(x+\delta x, t)
$$

The Hamiltonian of an isolated system of particles that are not subject to external forces has to be invariant under this operator $\widehat{D}$ as the physical laws should not depend on the where the observation is made. So we expect

$$
[\widehat{H}, \widehat{D}]=0
$$

We rewrite the wave function as a Taylor expansion after the translation:

$$
\begin{gathered}
\psi(x+\delta x, t)=\psi(x, t)+\delta x \frac{\partial \psi}{\partial x}(x, t)+\frac{(\delta x)^{2}}{2!} \frac{\partial^{2} \psi}{\partial x^{2}}(x, t)+\cdots \\
\psi(x+\delta x, t)=\left(1+\delta x \frac{\partial}{\partial x}+1+\frac{(\delta x)^{2}}{2!} \frac{\partial^{2}}{\partial x^{2}}+\cdots\right) \psi(x, t)=\exp \left(\delta x \frac{\partial}{\partial x}\right) \psi(x, t)
\end{gathered}
$$

Here we have used the notation where we indicate the exp of the partial derivative, which may look strange at first sight, but it is simply a shortcut for the Taylor expansion above. Using the Schrödinger equation and replacing in the formula

$$
\hat{P}_{x}=-i \hbar \frac{\partial}{\partial x}
$$

We get

$$
\widehat{D}=\exp \left(\frac{i}{\hbar} \widehat{P}_{x} \delta x\right)
$$

As an expression for the translation operator. If the system is to be invariant under translation, this will apply for any value of $\delta x$, and as a consequence we have

$$
\left[\widehat{P}_{x}, \widehat{H}\right]=0
$$

Which implies that the momentum is conserved as shown above.

Invariance of the Hamiltonian (the operator or expression for total energy) under a translation for an isolated, multiparticle system leads directly to the conservation of the total momentum of the system.

Example 6.2 Show that for a plane wave the momentum is conserved under the operator $\widehat{D}$

## Generators

In mathematical terms, we say that the translation operators $\widehat{D}$ form a group and the operator $\hat{P}_{x}$ is its generator. We will not discuss group theory here, but this result may be familiar to some of you.

Likewise it is easy to show that the time evolution operator

$$
\widehat{U} \psi(x, t)=\psi(x, t+\delta t)
$$

Can be expressed as

$$
\widehat{U}=\exp \left(-\frac{i}{\hbar} \widehat{H} \delta t\right)
$$

Which means that the Hamiltonian operator is the generator for the time evolution

Finally, the invariance of a system under rotation leads to the conservation of the angular momentum.

### Parity operator

The above continuous transformations led to additive conservation laws - the sum of all charges or momenta is conserved. There are also discrete or discontinuous transformations, which lead to multiplicative conservation laws. An important group of these are parity P, charge conjugation C and time reversal T .

The parity operator inverts spatial coordinates. It therefore transforms $\underline{x}$ into $-\underline{x}, \underline{p}$ into $-\underline{p}$ etc. In other words, polar vectors change sign; axial vectors, such as angular momentum $\underline{J}$, do not.

Now

$$
\begin{aligned}
& P \psi(\boldsymbol{x})=\psi(-\boldsymbol{x}) \\
& P^{2} \psi(\boldsymbol{x})=P \psi(-\boldsymbol{x})=\psi(\boldsymbol{x})
\end{aligned}
$$

The parity operator thus has eigenvalues of $\pm 1$.

If $\quad P \psi(\boldsymbol{x})=+\psi(\boldsymbol{x})$ the wavefunction has even parity, while if $\quad P \psi(\boldsymbol{x})=-\psi(\boldsymbol{x}) \quad$ it has odd parity.

(Note that wavefunctions do not have to be eigenfunctions of parity.)

The spherical harmonics $Y_{l}^{m}(\theta, \phi)$ (met in atomic physics and elsewhere) are examples of eigenfunctions of the parity operator. (If they are not familiar, look them up!) By considering a reflection in the origin, it should be clear that in spherical polar coordinates, the parity operator causes

$$
\begin{aligned}
& r \rightarrow r \text { (unchanged) } \\
& \theta \rightarrow \pi-\theta \\
& \phi \rightarrow \pi+\phi
\end{aligned}
$$

and by inspection of the form of the spherical harmonics it can be seen that $Y_{m}^{l}(\theta, \phi)$ changes sign if $/$ is odd and remains the same if it is even,

i.e.

$$
P Y_{m}^{l}(\theta, \phi)=(-1)^{l} Y_{m}^{l}(\theta, \phi)
$$

Since particles can be created in interactions, it is important to assign an "internal" parity to each particle, as we will see pions have parity -1 , while a fermion-antifermion pairs have opposite parity.

Electromagnetic and strong interactions conserve parity, and invariance with respect to $P$ leads to multiplicative conservation laws.

E.g. Consider $\quad a+b \rightarrow b+c$

The initial state wavefunction can be written as $\psi_{i}=\psi_{a} \psi_{b} \psi_{l}$, where $\psi_{a}$ and $\psi_{b}$ are "internal" wavefunctions for particles a and b , and $\psi_{l}$ is the wavefunction describing their relative motion which depends on the angular momentum I. The P operator affects each factor, so $P \psi_{i}=P \psi_{a} P \psi_{b} P \psi_{l}$

If the intrinsic parities of the particles are given by $P \psi_{a}=\pi_{a} \psi_{a}$, etc., where $\pi_{a}$ is just a number $\pm 1$, then

$$
P \psi_{i}=\pi_{a} \pi_{b}(-1)^{l} \psi_{i}
$$

i.e. the parity of a multiparticle system is given by the product of the intrinsic parities of the individual particles and the parity of the wavefunction describing their relative motion.

### Parity of the pions

As discussed earlier, particles have an intrinsic parity, which needs to be taken into account when evaluating the parity of a system. Parity of particles is determined experimentally by measuring the relative parity of a particle compared to the known parity of other particles. Since this is a relative measurement, we assume that the parity of protons and neutrons is +1 and derive the rest from experiment.

## Pion capture process

Here we show how we can determine the parity of the $\pi^{-}$to be -1 . We use the pion capture process

$$
\pi^{-} d \rightarrow n n
$$

Where a negative charged pion is captured by a deuteron. The $\pi^{-} d$ system form a "mesic atom", similar to a hydrogen atom, with the electron replaced by a pion. It is observed that the capture takes place in the atomic $s$-state with orbital angular momentum $L=0$. Hence the parity of the initial state is the product of the pion and deuteron parity

$$
P_{\pi} P_{d}(-1)^{0}
$$

Since the spin of the pion is zero and that of the deuteron is 1 , the initial state has total angular momentum $J=1$ due to the composition of angular momenta.

Final state wavefunction

In the final state we have two neutrons, which are identical fermions and as such their wavefunction needs to change sign if we exchange the two particles (recall the property of fermions vs bosons). The wave function can be written as the product of a space and spin parts

$$
\psi_{n n}=\psi(\boldsymbol{r})\left|S, S_{z}\right\rangle
$$

Where we indicate with $\psi(\boldsymbol{r})$ a function of the relative coordinate of the neutrons in the centre of mass system and the spin state is identified by the spin length and its zcomponent.

## Spin of the final state

The two neutrons have spin $1 / 2$, so they can combine into 4 different states, 3 states with total spin 1 and one state with spin 0 :

$$
\begin{gathered}
|1,1\rangle=|\uparrow \uparrow\rangle \\
|1,0\rangle=\frac{1}{\sqrt{2}}(|\uparrow \downarrow\rangle+|\downarrow \uparrow\rangle) \\
|1,-1\rangle=|\downarrow \downarrow\rangle \\
|0,0\rangle=\frac{1}{\sqrt{2}}(|\uparrow \downarrow\rangle-|\downarrow \uparrow\rangle)
\end{gathered}
$$

Where the notation on the right-hand side refers to the z-component of the spin of the neutrons. It can be noted that the three states with spin 1 are symmetric if we exchange the two neutrons, while the state with spin 0 is anti-symmetric for particle exchange.

In conclusion the exchange of the two particles will result in a change of sign in the wave function given by $(-1)^{S+1}$

## Orbital momentum of the final state

In the centre of mass frame the position of the two neutrons is $r$ and $-r$, respectively. The angular dependency of the wavefunctions is given by the spherical harmonics $Y_{m}^{l}(\theta, \phi)$ and swapping the two particles is equivalent to a reflection in the origin, and so the change in the wavefunction is given by $(-1)^{L}$ where $L$ is the orbital angular momentum of the final state. Therefore the exchange of the two neutrons will result in a change of sign of the wavefunction given by the product of the two $(-1)^{L+S+1}$. Since we expect the state to be anti-symmetric, we conclude that $L+S$ has to be even.

Angular momentum conservation in the reaction, implies that the total angular momentum $J=1$ is conserved. Using the rules for the addition of angular momenta, we can only have the following possible final states:

$$
\begin{aligned}
& L=0, S=1 \\
& L=1, S=0 \\
& L=1, S=1 \\
& L=2, S=1
\end{aligned}
$$

The only combination with $L+S$ even is when $L=1, S=1$. Which is the angular momentum of the final state.

Parity of the final state, conclusion

Now that we know the momentum of the final state, we can evaluate its parity as

$$
P_{n} P_{n}(-1)^{L}=-1
$$

(Note that the parity of the neutron is irrelevant here, since its square is always +1 ) Putting it all together we have

$$
P_{\pi} P_{d}=-1
$$

The deuteron is bound state of a proton and a neutron, which both have parity +1 in a state with orbital angular momentum 0 , so $P_{d}=+1$

In conclusion the parity of the pion is $P_{\pi}=-1$

(Note that this result is independent on the value we assigned to the parity of the proton and the neutron!)

### Parity of particle-antiparticle systems

An important experimental result, which we will not discuss here, is that the parity of a fermion and that of its corresponding antifermion is opposite. Differently a boson and its corresponding antiparticle have the same parity, for instance the $\pi^{-}$and $\pi^{+}$particles.

In the following we will use the notation $J^{P}$ to indicate the spin and parity of a particle or a system of particles. Where $J$ indicates the total angular momentum (e.g. the spin for a single particle) and $P$ the parity. So for the pion we write $J^{P}=0^{-}$, for the proton and neutron $J^{P}=\frac{1}{2}^{+}$

Example 6.3 The $\rho$ meson has spin 1 and decays into a pair of pions $\rho \rightarrow \pi^{+} \pi^{-}$. What is its parity?

## Solution:

The $\rho$ is a particle with spin one decaying into two particles with spin zero. We apply conservation of angular momentum. In the initial state the total angular momentum is 1 (due to the spin of the $\rho$ ). In the final state the pions have no spin, so to conserve angular momentum the orbital component of the angular momentum has to be one ( $L=1$ ). In conclusion the parity of the $\rho$ is

$$
P_{\rho}=P_{\pi}^{2}(-1)^{L}=-1
$$

(We shold note that the result is independent on the parity of the pion, since that quantity is squared.)

### Charge conjugation

Another discrete transformation is charge conjugation, $\hat{C}$, which changes a particle into its antiparticle. This reverses the charge, magnetic moment, baryon number and lepton number of the particle. Neutral states and neutral particles can be eigenstates of the $\hat{C}$ operator. For instance the photon is an eigenstate of $\hat{C}$ with value -1 :

$$
\hat{C}|\gamma\rangle=-1|\gamma\rangle
$$

Which can be derived from the Maxwell equations and the fact that electromagnetic fields are generated by moving charges that change sign under $\hat{C}$.

The charge conjugation is a multiplicative number, such as the parity, and it is easy to show that $\hat{C}^{2}=1$.

### Parity violation in weak interactions and neutrino helicity

One important result is that both C and P are conserved in electromagnetic and strong interactions. The same is not the case in weak interaction. This is experimentally observed in nuclear physics as decays between different parity states are observed.

This violation comes from a basic principle in particle physics, which is the fact that the projection of the spin of a neutrino in the direction of its motion is always negative. We call this quantity the helicity

$$
\frac{\boldsymbol{\sigma} \cdot \boldsymbol{p}}{p}
$$

which is illustrated in the diagrams of Fig 6.5 . We observe that neutrinos are always lefthanded ( $h=-1$ ) while antineutrinos are always right-handed ( $h=+1$ ).

![](https://cdn.mathpix.com/cropped/2024_08_10_e145a9c7f4ab84bf3ab7g-12.jpg?height=355&width=1186&top_left_y=930&top_left_x=412)

Fig 6.5. Possible spin configurations for the neutrino and antineutrinos

The parity operator will change the momentum of a neutrino, but not its spin (see Sec 8.2), so under parity operation the left-handed neutrino would turn into a right-handed neutrino. Right-handed neutrinos are not observed in Nature, which means that weak interactions cannot be invariant under parity.

On the other hand the C operator will change a neutrino into an antineutrino. The application of both the C and P operators to a neutrino state will result into a right-handed antineutrino. So the expectation is that weak interactions are invariant under the $C P$ operation combined.

(Note: small violation of the CP symmetry are observed, so this is not the end of the story. We stop here for now. But a violation of CP symmetry results in an asymmetry of matter vs antimatter which may explain why the Universe is predominantly made of matter!)

### Further reading

- Most of the material on weak interactions is taken from [Perkins] sec 2.8
- A more in-depth treatment of beta decay can be found in [Perkins] sections 7.2, 7.3, 7.4
- Some experimental results are also found in [Perkins] section 7.11 and 7.12
- Parity and charge conjugation are defined in [Martin] section 1.3.1
- The spin and helicity of neutrinos is discussed in [Martin] section 6.3
- The parity of the pion is discussed in [Martin] section

