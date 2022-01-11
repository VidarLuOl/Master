# Aiming at heterogeneous parallel computing for bioinformatics: To overlap or not to overlap?

## Table of contents
* [Keywords](#Keywords)
* [Intoduction](#Introduction)
* [Goal](#Goal)
* [Learning outcome](#Learning-outcome)
* [Qualifications required](#Qualifications-required)

## Keywords
Heterogeneous computing, parallel programming, computational bioinformatics

The overall objective of this master project is to to investigate the necessity and potential performance benefits of overlapping communication with computation, in the context of modern parallel computing. A proper handling of this topic is essential for ensuring good performance of many applications in computational science, with computational bioinformatics being a prominent domain of applications.

## Introduction
The need for more computing power applies to all subjects of computational science. This is no exception in the case of computational bioinformatics, where typical applications that require supercomputing power include DNA sequence analytics and molecular dynamics simulations. Another timely example is the modeling of spread of virus. One way to answer the urgent need of supercomputing is to adopt heterogeneous computing platforms, that is, a system has at least two types of processor architectures. A typical configuration is a cluster of compute nodes where each node consists of a host CPU and one or several GPUs (graphics processing units). One of the research questions related to parallel programming of such heterogeneous systems is whether to overlap communication with computation for the purpose of "hiding" the communication overhead. In particular, the appropriateness of overlap in the era of heterogeneous computing requires new research. This is both due to the extra programming complexity that will be induced by implementing communication-computation overlap, and due to the impact of, for example, memory bandwidth contention thus incurred, which may lead to a slower computation speed as a whole.

## Goal
This master-degree project aims at a detailed and quantifiable understanding of the impact of overlapping communication with computation on heterogeneous parallel computers. The candidate will start with developing simple synthetic benchmark programs that implement various scenarios of communication-computation overlap, where it should be flexible to control the amounts (and designated segments) of node-to-node and CPU-to-GPU data communication, as well as CPU-GPU computation division. These benchmarks will be carefully experimented and time-measured for understanding the potential performance benefits (or disadvantages). An effort will be made to establish performance models related to communication-computation overlap or non-overlap. Another objective of this master-degree project is to summarise some programming guidelines in this regard. The scientific findings will then be tested in applications that fall in the domain of computational bioinformatics, to check the effectiveness of the resulting heterogeneous programming approach (with or without communication-computation overlap), as well as the applicability of the performance modeling methodology.

## Learning outcome
The candidate will learn about advanced parallel programming: applicable to both multicore CPUs and at least one specific GPU architecture. The candidate will also become an expert on performance profiling and modelling. The candidate will get the chances to be familiarised with real-world examples of computational bioinformatics. The candidate will also be exposed to cutting-edge hardware for parallel computing. All these skills and experiences are highly sought-after expertise of future workforce for scientific/technical computing.

## Qualifications required
The candidate is expected to be skilful in technical programming (experience with parallel programming is not required, but preferred). Very important: The candidate must be hard-working and eager to learn new skills and knowledge (such as about basic mathematical modeling and basic bioinformatics applications).