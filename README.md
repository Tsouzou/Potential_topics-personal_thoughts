## A Fair Game and the Measurement Paradox: Martingales and Quantum Analogy

A **martingale** is a stochastic process whose expected future value, given all current information, equals its present value. In the fair coin-toss model where we assign $+1$ for heads and $-1$ for tails, let $S_t$ be the cumulative sum of these increments up to time $t$. Since each increment has zero mean and is independent of past outcomes, 

$$
E[S_t \mid \mathcal{F}_{t-1}] = S_{t-1},
$$

indicating no net drift in this “fair game.” Thus, $\{S_t\}$ is a classic martingale.

Conditioning on an event in classical probability can be loosely compared to **wavefunction collapse** in quantum mechanics. In both cases, we restrict ourselves to outcomes (or states) consistent with an observed result and renormalize probabilities (or amplitudes) accordingly. Yet while classical conditioning is viewed as merely updating our knowledge of a system presumed to have definite states, quantum measurement is often interpreted as causing a physical change in the wavefunction itself. Despite this conceptual difference, the shared mathematical structure—focusing on a subset of possibilities and recalculating likelihoods—remains strikingly similar.
