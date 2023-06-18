---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 21

title: Research
subtitle:

design:
  columns: '1'
---
Our research program will be led by Konstantina Trivisa (PI), Maria Cameron (Co-PI), Andrew Childs (Co-PI), Lawrence Washington (Co-PI), and Senior Personnel Howard Elman, Dionysios Margetis, Carl Miller, Ricardo Nochetto, Jonathan Rosenberg, Eitan Tadmor and Pratyush Tiwary. Gorjan Alagic, Thomas Haines, Alicia Koll´ar, and Deep Ray will serve as additional research mentors. Daniel Serrano (Co-PI) will develop and coordinate research training and educational activities. The mathematical expertise of the faculty covers a wide range of areas in Pure and Applied Mathematics: Algebra/Representation Theory, Nonlinear Analysis, PDEs, Scientific Computing and Stochastic Analysis, as well as Data Science and Machine Learning. Our faculty have common research interests and contributions within two or more of these areas, which play vital roles in QIS (Figure 2). Our RTG-MathQIS Program facilitates collaboration between faculty from the Departments of Mathematics, Chemistry, Computer Science, and Physics, as well as synergy with QuICS (Joint Center for Quantum Information and Computer Science), JQI (Joint Quantum Institute), IPST (Institute for Physical Science & Technology), and QTC (Quantum Technology Center). This well-established Quantum ecosystem offers excellent opportunities for research training, education and professional development of junior researchers in MathQIS.
The field of QIS includes the use of quantum mechanical systems to perform informationprocessing tasks, and the study of physical systems from an information-theoretic standpoint. Quantum technology is theoretically capable of performing certain tasks that are infeasible
using classical (non-quantum) technology. Recently, there has been a rapid acceleration of the field, including steady progress towards scalable quantum computers and large investments from the public and private sector. The RTG-MathQIS effort will focus on three interconnected research themes: Quantum Algorithms, Quantum Cryptography and Quantum Systems. These themes provide opportunities for mathematical innovation through research projects accessible even to existing non-quantum faculty and students.

Quantum Algorithms. The field of quantum algorithms
studies the possibility of solving computational problems dramatically
faster with computers that store and process information
quantum mechanically. Such exponential quantum
speedup relies often on the “structure” of a certain problem
arising from concepts such as algebra and graph theory. This
shows the essential connection between mathematics (e.g., algebraic
problems) and quantum information. In 2009, Harrow,
Hassidim, and Lloyd (HHL) developed a quantum algorithm
that produces a quantum state x solving Ax = b for known,
sparse linear system A and vector b in time κ2 log(N), where
κ is the condition number of A [14]. A similar process, performed
classically, requires time κN. Following HHL, Co-PI
Childs has developed advanced quantum linear system algorithms (QLSAs) that improve the
asymptotic dependence on κ and precision [14, 15] (see also Berry [16], Zhao et al. [17], Tang [18]).
Co-PIs Childs, Trivisa et al. [19] recently developed an efficient quantum algorithm for dissipative
nonlinear differential equations. The result employed the Carleman linearization method which maps
a system of nonlinear differential equations to an infinite-dimensional system of linear differential
equations, which are then discretized, truncated, and solved using QSLAs (see also [20]).
We aim to address central questions such as these in our project: (1) From a theoretical point
of view, can we offer exponential quantum speedups for more general differential equations? In
exploring this question, the group will investigate kinetic models arising in physics and biology where
the dimensionality of the problem exceeds the capacity of classical computers. The investigation
will include the study of particle systems describing self-organised dynamics (cf. Tadmor [21, 22,
23], Trivisa [24, 25, 26]). (2) Can we investigate end-to-end quantum applications for differential
equations and related real-world problems? In particular, how can we encode the equations and
understand what useful properties can be efficiently extracted from the output state? (3) Can one
construct Quantum Fourier Transforms (QFT) for compact Lie groups? The QFT is probably the
single most important ingredient responsible for dramatic quantum speedups (cf. Alagic [27]).

Quantum Cryptography. Cryptography is the study of interactive information processing in
scenarios where not all participants are trusted. Of all the fields of theoretical computer science,
it is one of the most impacted by the development of quantum technology. On one hand, if Shor’s
algorithm were ever implemented on a large-scale quantum computer, it would destroy the security
of most commonly used public-key encryption algorithms. This has motivated, in the last several
years, a new stage of development in cryptography: “post-quantum cryptography.” On the other
hand, quantum information science itself offers an alternative approach to cryptosystem design.
“Quantum cryptography” exploits the unique properties of quantum devices to secure information.
Because of its technical depth and relative maturity as a field, quantum cryptography benefits
greatly from interactions with mathematics research. Examples from the work of Senior Personnel
Miller illustrate this. In 2014, Miller (a mathematician) and his co-author Yaoyun Shi (a computer
scientist) gave the first proof of robust device-independent quantum random number generation [28].
Their proof, which resolved an open question that had first appeared in 2007, made crucial use of a
known mathematical result on the uniform concavity of the Schatten matrix norm. More recently,
in 2019, Miller resolved the question of the efficiency of quantum weak coin-flipping [29], a problem
on which there had been no progress for the previous twelve years. To solve the problem, Miller
used techniques from complex analysis that he learned from a pure mathematician (Alexandre
Eremenko). Both of these cases underscore the benefit of interdisciplinary work between math and
quantum cryptography, and the potential benefit of a more systematized effort.
In the present day, the original scenario of concern in quantum cryptography — interaction
between two parties, in a minimal physical model — is well understood at a theoretical level. A
natural next direction for the field is to improve cryptographic results in multi-party settings (e.g.,
voting, secret sharing, etc.) to see if they can reach the same level of security as in the two-party
setting. But perhaps an even more interesting direction (from the mathematical perspective) is:
what new cryptographic capabilities can we achieve if additional assumptions are introduced?
Position-based cryptography [30] is based on the additional physical assumption that communication
between distant parties cannot travel faster than the speed of light. This subfield of quantum
cryptography has been under development for several years, but basic problems remain open. This
project will aim to tackle central questions such as: (1) Is it possible to verify the location of an
untrusted party in space? (See [31] for relevant research). (2) How could the basic construction
of trapdoor claw-free functions in [32, 33] be reconfigured to achieve more powerful results? This
question is part of a rich subfield originated by Mahadev et al. on quantum cryptography in a
classical communication model with post-quantum cryptographic assumptions [32, 33].

Quantum Systems. The study of quantum phenomena has acquired significant momentum
in recent years. Two particular areas of quantum research bearing exciting projects for graduate
students and postdocs are rare events in quantum chemical systems and quantum oscillators.
Rare events in quantum systems are of a principally different nature than in classical ones. They
happen not due to a streak of random forcing driving the system out of a metastable state but
due to the wave nature of quantum particles enabling the quantum tunneling [34, 35, 36, 37]. The
development of a mathematical framework for the description of rare events in quantum chemical
systems, relies on a quantum counterpart of Transition Path Theory (TPT), as well as numerical
methods for sampling and quantification. Questions such as the concept of a quantum analog of
the committor function, the key function of the TPT, will be addressed. Applications to real-life
molecular systems will be investigated (cf. Cameron and Tiwary (2022), unpublished).
The interest in quantum oscillators is promoted by envisioning the development of quantum
technologies. While the dynamics of the linear quantum oscillator are well-understood [38], the
dynamics of nonlinear quantum oscillators are the subject of active research [39, 40, 41, 42, 43, 44,
45, 46]. Phenomena such as synchronization, oscillation collapse, and critical response to external
forcing have been studied. Single quantum van der Pol and Rayleigh oscillators served as the
prototypical models. The study of quantum oscillator arrays will the subject of our research.
Some fundamental questions that our team is poised to address are: (1) What are the quantum
analogs of a bistable oscillator and oscillator arrays? (2) What are the transition mechanisms
between the attractors? (3) How can they be found numerically? These questions are motivated
by recent successes in the study of circular arrays of classical nonlinear oscillators with external
periodic forcing and small white noise [47].
The team will also investigate many-body theories (including Fock-space techniques) as well as
quantum Boson dynamics of atomic gases beyond mean field approaches (cf. Margetis [48]); the
electronic transport in novel 2D materials and topological insulators as well as models of quantum
fluids (cf. Jayanti and Trivisa [49, 50, 51]). Recently, strong connections have been found between
the physics/engineering of devices and mathematical topics such as non-Euclidean geometry and
spectral graphs (cf. Koll´ar and Sarnak [52]). This project will explore such connections.