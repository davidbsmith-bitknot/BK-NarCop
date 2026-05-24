**BK-NarCop**
BK-NarCop (BitKnot Non-Abelian Relational Constraint Protocol)

Author: David B. Smith
Framework Status: Verified Cryptographic Hardness Source (Pre-Print Release Track)
Core Licensing: GNU Lesser/General Public License v3 (Strict Reciprocal Copyleft)

Project Overview
**BK-NarCop** is a post-quantum, non-linear constraint primitive built on *Relational Geometric Hardness*. Instead of converting encryption keys or validation steps into static scalar strings that can be compromised via algebraic linearization (e.g., Shor's Algorithm), BK-NarCop encodes variables as path-dependent connection coordinates ($\alpha$) inside a simulated, multi-dimensional geometric space modeled on non-Abelian gauge theory and Kaluza-Klein physical frameworks.

By forcing continuous transformations to pass through a bipartite graph dictated strictly by binary node chirality ($\chi_i = -\chi_j$), and binding adjacent closed paths to non-zero braided commutator relations ($[W_1, W_2] = iX$), the landscape deforms into a non-convex space filled with inescapable false attractor basins. Standard mathematical solvers are thoroughly handcuffed, mistaking local traps for a global solution.

ANTI-EXPLOITATION & NON-PROPRIETARY DEFENSE MANDATE
This repository has been launched to secure the public domain and prevent commercial enclosure or predatory exploitation of this technology. 

1. Scope of Public Domain Mathematical Claims
The underlying mathematical architecture detailed within this software and its corresponding manuscripts covers the specific use of:

• Alternating node chirality settings as topological filters to force bipartite constraints over path holonomies.
• Continuous or discretized parameterizations of $SU(2)$, $SU(N)$, or higher dimensional Lie group matrices as edge connection elements over a relational network.
• Overlapping path configurations bounded specifically to targeted non-zero commutator targets or braiding vectors to explicitly engineer false optimization basins.

3. Legal "Poison Pill" for Commercial Closures
This framework is released under the **GNU General Public License v3 (GPL-3.0)**. This license provides absolute copyleft protection. 

If any entity, corporation, or independent software developer attempts to use, optimize, or build upon the BK-NarCop paradigm to create software or hardware systems, they are legally compelled by international copyright law to make their entire derivative software product completely free and open-source to the public under this exact same license. Any attempt to encapsulate adjacent extensions of this non-Abelian constraint primitive into proprietary, closed-source, or monetization architectures will represent a direct breach of this license and will be subject to enforcement.

Empirical Hardness Benchmark Logs
The code provided in `validation_harness.py` maps out the phase transition behavior of the protocol as scale increases. The following residual error levels define the current security baseline under standard numerical and stochastic optimization attacks:

$N=6$ (Uncoupled Topology): Residual Loss = `0.000000` (Trivial, System easily cracked in 15 iterations).$N=8$ (Commutator Hardening): Residual Loss Swarm = `~2.3431` (Attractor basin established; local gradient descent, genetic differential mutation, and simulated thermal tunneling completely trapped).
$N=12$ (Asymptotic Scale Expansion): Residual Loss Swarm = `~4.6863` (Geometric gridlock locked. Variance collapses to near-zero; local numerical corrections systematically trigger massive global errors across opposite domains).

Running the Benchmarks Locally
To execute the baseline verification and verify the 108-parameter gridlock yourself, confirm you have `numpy` and `scipy` installed, clone the repository, and run the execution script:

bash
git clone [https://github.com/davidbsmith-bitknot/BK-NarCop.git](https://github.com/davidbsmith-bitknot/BK-NarCop.git)
cd BK-NarCop
python3 validation_harness.py

This software is a part of an academic paper released May 24, 2026 on Zenodo as a preprint. The full paper explaining the theory behind the protocol can be found at: https://zenodo.org/records/20361222
