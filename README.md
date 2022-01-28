# QuTech QEC Challenge @ MIT iQuHACK 2022


<p align="middle">
  <a href="https://www.quantum-inspire.com/" target="_blank"><img src="https://user-images.githubusercontent.com/10100490/151484481-7cedb7da-603e-43cc-890c-979fb66aeb60.png" width="25%" style="padding-right: 15%"/></a>
  <a href="https://iquhack.mit.edu/" target="_blank"><img src="https://user-images.githubusercontent.com/10100490/151484702-4fc8ca20-59fe-4244-9d3c-210118d5d69a.svg" width="10%" style="padding-left: 15%"/> </a>
</p>



## Description 

In this challenge, participants will be tasked with using the available noisy intermediate-scale quantum  (NISQ)  hardware  to  implement  a  program  that  makes  use  of  quantum  error detection/correction (QED/QEC) techniques. The team at QuTech proposes a particular topic around a fundamental building block of quantum error correction, Quantum Parity Measurements  (QPM).  Nevertheless,  any  project  that  makes  use  of  QED/QEC  will  be admissible, and scoring will be adapted on a case-by-case basis to assess all projects fairly.


## Background 

Besides  quantum  communication,  which  participants  will  be  able  to  explore  in  the  QuTech Quantum  Encryption  challenge,  another  outstanding  goal  of  QuTech  is  the  development of  fault-tolerant  quantum  computing.  In  honoring  this  tradition,  we  present a challenge  around  the implementation of QPMs, projective measurements used to stabilize quantum information, allowing the detection and, potentially, correction of quantum errors. These form the basis of quantum error correction, and their implementation is, therefore, fundamental to move us from the NISQ era into fully fault-tolerant quantum computing.

## Goal

The proposed goal of this challenge is the implementation of high-fidelity QPMs. It will be the 
responsibility of participants to define a set of relevant metrics, either from existing literature or  of  their  own  making,  to  assess  the  performance  of  their  implementations.  Furthermore, participants will be challenged to iteratively improve on their original implementation of QPMs through  error  mitigation  strategies,  in  such  a  way  as  to  develop  an  understanding  of  the fundamental error channels inherent to NISQ hardware.

## Scoring and Submission

**Rubric:** https://docs.google.com/document/u/1/d/e/2PACX-1vR5PVoInN_Fi42lIOchhblgGBPblgNyouj1XHukonZ4sdqY-p5ulS9TxdzvddEcDNFc5k_6teFyKzXv/pub

**Submission:** Please visit https://iquhack.mit.edu/ for details on how to submit your project.


## Quantum Parity Measurements

In  an  actively  corrected  quantum  memory,  quantum  information  is  distributed  among  many elementary degrees of freedom. QPMs are a procedure used to actively gather information  about  which  (or  whether)  errors  took  place,  particularly  in  stabilizer  codes,  by  measuring  subsets of qubits in Pauli matrix bases. An ideal QPM provides a discretization of the set of  errors that occurred in the qubits over which quantum information was distributed. 

Participants are encouraged to read parts of reference [1] for a theoretical framework of the 
concepts. Furthermore, curious participants can read about the experimental implementation 
of various QPMs in the context of recent experiments on quantum error correction codes, the 
Bacon-Shor code [2], the color code [3], the repetition code [4] and the surface code [5]. 
 
## Benchmarking and performance metrics

Participants should choose and/or create different metrics to assess the performance of the implemented  circuits  and  determine  the  effectiveness  of  any  methods  employed  to  further improve the performance of their circuits. In particular, participants could consider metrics on the  fidelity  of  the  parity  assessment,  the  average  assignment  probability  being  a  trivial example, or more involved metrics on, for example, the back-action of the parity measurement. 

## Error mitigation and NISQ hardware

Participants  are  encouraged  to  augment  their  projects  through  the  exploration  of  error mitigation  strategies,  to  determine  whether  they  can  be  employed  to  further  improve  the implemented  circuits.  Examples  of  these  could  range  from  dynamical  decoupling  to  more involved approaches, such as randomized compiling. Furthermore, participants are encouraged to draw information from these experiments to study the effects of specific error channels inherent to the NISQ hardware platforms used in the event, whether through direct measurement or matching with simulation results. 



## References

1. Terhal, B. M. (2015). Quantum error correction for Quantum Memories. Reviews of Modern Physics, 87(2), 307–346. https://doi.org/10.1103/revmodphys.87.307 

2. Egan, L., Debroy, D. M., Noel, C., Risinger, A., Zhu, D., Biswas, D., Newman, M., Li, M., Brown,  K.  R.,  Cetina,  M.,  &  Monroe,  C.  (2021).  Fault-tolerant  control  of  an  error-corrected qubit. Nature, 598(7880), 281–286. https://doi.org/10.1038/s41586-021-03928-y 

3. Chen, Z., Satzinger, K. J., Atalaya, J., Korotkov, A. N., Dunsworth, A., Sank, D., Quintana, C.,  McEwen,  M.,  Barends,  R.,  Klimov,  P.  V.,  Hong,  S.,  Jones,  C.,  Petukhov,  A.,  Kafri,  D., Demura, S., Burkett, B., Gidney, C., Fowler, A. G., Paler, A., ... Kelly, J. (2021). Exponential suppression  of  bit  or  phase  errors  with  cyclic  error  correction. Nature, 595(7867),  383–387. https://doi.org/10.1038/s41586-021-03588-y 

4. Ryan-Anderson, C., Bohnet, J. G., Lee, K., Gresh, D., Hankin, A., Gaebler, J. P., Francois, D., Chernoguzov, A., Lucchetti, D., Brown, N. C., Gatterman, T. M., Halit, S. K., Gilmore, K., Gerber, J. A., Neyenhuis, B., Hayes, D., & Stutz, R. P. (2021). Realization of real-time fault-tolerant quantum error correction. Physical Review X, 11(4). https://doi.org/10.1103/physrevx.11.041058 

5.  Marques,  J.  F.,  Varbanov,  B.  M.,  Moreira,  M.  S.,  Ali,  H.,  Muthusubramanian,  N., Zachariadis, C., Battistel, F., Beekman, M., Haider, N., Vlothuizen, W., Bruno, A., Terhal, B. M., & DiCarlo, L. (2021). Logical-qubit operations in an error-detecting surface code. Nature Physics, 18(1), 80–86. https://doi.org/10.1038/s41567-021-01423-9 