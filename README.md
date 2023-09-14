# E0224-Computational_Complexity_Theory
E0224:Computational_Complexity_Theory is a course on the theoretical foundation of computer science and automation at IISc, Bengaluru.

🎯 Essential Highlights of techniques and tools:

$\textbf{Part-I}:$
> $\bullet$ Turing Machine and formal definition of algorithms
> $\bullet$ Uncomputability of 'Halting problem' via 'Diagonal Argument (Diagonalization)'

> $\bullet$ Universal Turing machine (UTM) and Church-Turing thesis

> UTM overhead of $\mathcal{O}(T\cdot log(T))$ [proof omitted]
> $\bullet \textbf{Possible violation of Strong Church-Turing Thesis due to Quantum Machine}[😃]$ 

$\textbf{Part-II}:$
> $\bullet$ Deterministic Turing Machine and complexity class $P$
> $\bullet$ Non-deterministic Turing Machine and complexity class $NP$

>⭐ $\bullet$ Cook-Levin Theorem and NP-Completeness of SAT (Boolean Satisfiability Problem)
 
> $\bullet$ Karp reduction and Zoo of NP-complete problem
>
> $\bullet$ Decision versus Search Problem: Complexity class co-NP
> $\bullet$ More harder Decision Problems: EXP and NEXP

$\textbf{Part-III}:$
> $\bullet$ Proofs techniques: Diagonalization and Oracle-Methods (Relativization)

>  Time Hierarchy Theorem: $f(n)log(f(n))=\mathbb{o}(g(n)) \implies DTIME(f(n))\not\subset DTIME(g(n))$

>  Prove for $P \subsetneq EXP\implies$ $\textbf{Chess and Go will never have a classical Polynomial-time algorithm(!)}$

> $\bullet$ Landner's Theorem and NP-Intermediate Problems: Prove for $SAT_H$ is NP-Intermediate

>⭐ $\bullet$ Curious case of $INTEGER\ FACTORING$ and Graph Isomorphism Problem

>⭐ $\bullet$ Oracle Machine and Proof by Relativization
> $\bullet$ Prove that the P versus NP debate can't be settled by oracle-based relativization

$\textbf{Part-IV}:$ 
> $\bullet$ Space bounded computation: PSPACE complexity problems
>
> SPACE Vs TIME bounded Computation: $DTIME(S(n))\subseteq SPACE(S(n)) \subseteq DTIME(2^{\mathcal{O}(S(n))})$

>⭐ P=PSPACE debate: Can time be reused during computation like space reuse/modification? [Within time travel restriction]

> Space Hierarchy Theorem: $f(n)=\mathcal{o}(g(n))\implies SPACE(f(n)) \subsetneq SPACE(g(n))$
>
$\bullet$ Savitch's Theorem: $NSPACE(S(n))\subseteq SPACE(S(n)^2) \implies$ Non-determinism doesn't add any more power to Turing machine in space-bounded computation

