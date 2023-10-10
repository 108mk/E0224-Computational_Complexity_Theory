# E0224-Computational_Complexity_Theory
E0224:Computational_Complexity_Theory is a course on the theoretical foundation of computer science and automation at IISc, Bengaluru.

🎯 Essential Highlights of techniques and tools:

$\textbf{Part-I: Turing Machine as a model of computation}$
> $\bullet$ Turing Machine and formal definition of algorithms
> $\bullet$ Uncomputability of 'Halting problem' via 'Diagonal Argument (Diagonalization)'

> $\bullet$ Universal Turing machine (UTM) and Church-Turing thesis

> UTM overhead of $\mathcal{O}(T\cdot log(T))$ [proof omitted]
> $\bullet \textbf{Possible violation of Strong Church-Turing Thesis due to Quantum Machine}[😃]$ 

$\textbf{Part-II: Deterministic and Non-deterministic Turing Machine}$
> $\bullet$ Deterministic Turing Machine and complexity class $P$
> $\bullet$ Non-deterministic Turing Machine and complexity class $NP$

>⭐ $\bullet$ Cook-Levin Theorem and NP-Completeness of SAT (Boolean Satisfiability Problem)
 
> $\bullet$ Karp reduction and Zoo of NP-complete problem
>
> $\bullet$ Decision versus Search Problem: Complexity class co-NP
> $\bullet$ More harder Decision Problems: EXP and NEXP

$\textbf{Part-III: Diagonalization and Oracle/Black-Box Model}$
> $\bullet$ Proofs techniques: Diagonalization and Oracle-Methods (Relativization)

>  Time Hierarchy Theorem: $f(n)log(f(n))=\mathbb{o}(g(n)) \implies DTIME(f(n))\not\subset DTIME(g(n))$

>  Prove for $P \subsetneq EXP\implies$ $\textbf{Chess and Go will never have a classical Polynomial-time algorithm(!)}$

> $\bullet$ Landner's Theorem and NP-Intermediate Problems: Prove for $SAT_H$ is NP-Intermediate

>⭐ $\bullet$ Curious case of $INTEGER\ FACTORING$ and Graph Isomorphism Problem

>⭐ $\bullet$ Oracle Machine and Proof by Relativization
> $\bullet$ Prove that the P versus NP debate can't be settled by oracle-based relativization

$\textbf{Part-IV: Space Bounded Computation}$ 
> $\bullet$ Space bounded computation: PSPACE complexity problems
>
> SPACE Vs TIME bounded Computation: $DTIME(S(n))\subseteq SPACE(S(n)) \subseteq DTIME(2^{\mathcal{O}(S(n))})$

>⭐ P=PSPACE debate: Can time be reused during computation like space reuse/modification? [Within time travel restriction]

> Space Hierarchy Theorem: $f(n)=\mathcal{o}(g(n))\implies SPACE(f(n)) \subsetneq SPACE(g(n))$

>⭐ Savitch's Theorem: $NSPACE(S(n))\subseteq SPACE(S(n)^2) \implies$ Non-determinism doesn't add any more power to Turing machine in space-bounded computation

> $\bullet$ Class L: Logarithmic space complexity; $UPATH \implies$ s-t connectivity in an undirected graph is in L.
>
> $\bullet$ Class NL: Non-deterministic Logarithmic space complexity; $PATH \implies$ s-t connectivity in a directed graph is in NL.

> ⭐ PSAPCE-completeness under Karp reduction: Quantified Boolean formula and hardness of TQBF decision problem.

> $\bullet$ NL-completeness under Log-space reduction: $PATH$ is NL-complete problem

$\textbf{Part-V: Polynomial Hierarchy}$ 
> $\bullet$ Polynomial Hierarchy(PH) and Alternating Turing Machine (ATM)
>
> Problem between NP and PSAPCE: Eq-DNF and Succinct Set-Cover

>⭐ Class $\Sigma_i$ and $\Pi_i$ as generalization of $NP$ and co-NP.

> Polynomial Hierarchy $(PH)$ $\in$ $PSPACE$

>⭐ $PH$ conjecture and hierarchy collapse theorem

> Complete problems in within any $PH$ level: $\Sigma_i$-SAT is a complete problem

> 💡 Oracle access to Language $L$ $\neq$ access to an efficient algorithm for $L$

$\textbf{Part-VI: Circuit Model of Computation}$ 
> $\bullet$ Boolean Circuit

> PARITY problem and its boolean circuit
> 
> Class $P/Poly=\bigcup_{c\geq 1} SIZE(n^c)$

> ⭐ Karp-Lipton Theorem

> Class NC $\equiv$ Efficient Parallel Computation
> 
> Class AC (Unbounded fan-in version of NC)
>
> Logarithmic blow up in size for AC to NC conversion: $AC^i\subseteq NC^{i+1}\subseteq AC^{i+1}$

🎯 P-complete problem under log space reduction
> P-complete problems:
>> Circuit Value Problem
>>
>> Linear Programming
>>
>> Context Free Grammer (CFG) membership
>> 
> Is $P=(uniform)NC?$

🎯 Switching Lemma and $PARITY \not\subset AC^0$
> Combinatorial Proof of Switching Lemma
