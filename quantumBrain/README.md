# Quantum Brain

_The **Quantum Brain** is a next-generation photonic neuromorphic quantum computing system inspired by human brain function, specifically wavefront signal propagation observed in EEG data. Neuromorphic systems unify memory and computation, and this one is no different, however this one utilizes photonics using cutting-edge materials and logic architectures to emulate processing similar to that of the brain._

---

## Table of Contents

- [Terminology](#terminology)
- [Architecture](#architecture)
- [Quaternary Logic](#quaternary-logic)
- [Signal Propagation & Context Encoding](#signal-propagation--context-encoding)
- [Key Technologies & Their Biological Counterparts](#key-technologies--their-biological-counterparts)
- [References](#references)

---

## Terminology

If you are familiar with neuromorphic computing, skip this paragraph; otherwise, continue reading. Neuromorphic computing describes a kind of computational architecture based on or inspired by the brain. Many neuromorphic architectures use analog computing with memristors. Memristors are a basic circuit component that remembers the current that just passed through it and will have a variable resistance based on said current. It “remembers” the current, so it “remembers” what resistance value it will have, hence memristor. One aspect of neuromorphic computing that differentiates it from classical von Neumann computational architectures is that it does not operate on a clock. Another aspect of neuromorphic computing is that the computation and the memory are in the same location, which is the intention for this system as well. Components are only powered when they are being used, otherwise, they are off. All these factors lead neuromorphic computing to be incredibly energy efficient, and neuromorphic architectures are especially good when it comes to running neural networks and machine learning algorithms.

If you are familiar with photonic computing, skip this paragraph; otherwise, continue reading. Photonic computing uses light particles (photons) rather than electrons to perform operations and transfer information. Photonics is involved in fiber optic communications in data centers, telecommunications, the internet, and WiFi. Recently, Nvidia announced a photonic AI chip for data centers. Photonic computing is not new, neither photonic quantum computing, nor photonic neuromorphic computing are original, however their implementation here is what makes this architecture so promising.

---

## Architecture

A system of photonic qubits, each with **n** photonic memristors attached. Those memristors connect to other qubits, leading to step-based logic and interconnectedness, the same way that neurons have synapses connecting them to other neurons. The important part is that the signal from the memristors is analog and therefore noisy and unrefined, so it will need to be transformed into a digital signal to be refined by digital logic and then sent to the qubit. As such, the architecture will be photonic memristors  digital  qubit.

It is worth mentioning that the architecture being described would be best implemented in three dimensions rather than two.

Technologically, that is incredibly advanced and beyond out-of-reach at this time. So, instead, a two-dimensional format will be used, however, it will certainly be less optimized.

The implementation of this architecture in an incredibly dense three-dimensional format is not possible currently and may not even be possible in my lifetime. This architecture being described can be utilized with or without the qubits, and it could be designed with digital logic in mind. However, as will be stated below, the digital logic being used is unconventional. The quaternary form of logic may not be global across the entire quantum brain, however it is universal to all life (as we know it).

---

## Quaternary Logic

Computation occurs using quaternary logic, offering greater encoding efficiency compared to binary systems, and drawing inspiration from nature’s own encoding schemes (e.g. DNA’s ATCG and RNA’s AUCG). In this system, it would be 0,1,2,3. Quaternary-based logic is not a new concept, however, it is not utilized often. It is relatively simple to convert between binary and base 4; using two bits for one quaternary "quadit" (quadit being a classical bit that is not binary and is instead quaternary). However, that is for the sake of making this something safe, for the sake of national security, avoiding misuse, minimizing replicability, etc. Neither space taken up nor energy consumption would be minimized in the case of using two bits rather than one "quadit". Now, the process of making a "quadit" would be difficult, but possible. It would necessitate having 4 distinct voltage states, or 2 voltage states and 2 other states in the case of a CMOS architecture. For this photonic system, there are many options, whether wavelengths, polarization, phase shifts, or intensity.

Information would be encoded in quaternary storage and via a combination of transistors and memristors, as has been demonstrated in non-photonic neuromorphic computing, the memory and processing can exist in the same location.


Quaternary logic is used in the analog and digital processing layers for increased encoding efficiency. Photonic qubits currently operate using binary superposition states, though the architecture is extensible to higher-dimensional qudits (e.g. ququarts) in the future.

---

## Signal Propagation & Context Encoding

The photonic neuromorphic quantum computer uses algorithms based on human brain patterns. Using a combination of electroencephalograms (EEGs) to monitor real people doing calculations/tasks, and then making algorithms based on their brain wave patterns, one could use wavefront signal propagation to mimic brain wave patterns. Additionally, by investigating EEG neurodynamics, it becomes possible to emulate neuromorphic spatial-temporal information processing. I was unfamiliar with wavefront signal propagation until I read a blog from a company called Analog Physics, as such the blog has been cited at the bottom [1]. Conceptually, I think that designing an algorithm by copying a brain pattern will allow for algorithms that are more human in nature, and I hope that this will make the algorithms more powerful long-term.

Data encoding in the brain is based on patterns and synapse weightings, and every individual's pattern-based encoding of that information is not the same. Additionally, the brain has a mechanism through which synapses know the context of the task being performed and through said mechanism, signals are sent down various branches with the most intense signal being the one that is the most relevant. In order to emulate the synapses “knowing” what the context of a task is, this architecture will make use of what I would call, “filters,”  which use advanced materials, such as metamaterials, photonic waveguides, plasmonic structures, and polarizers (waveplates or otherwise). Using photonic memristors, a signal filtered from one activation point will have a color, or wavelength which can be filtered by each of the metamaterials that are inside of the waveguides, which would allow for the filtering of information by category, or type, then additional information could be filtered via combinations of polarizers where, for example, a horizontally polarized light beam is filtered out by the vertical polarizer and vice versa. 

Using a combination of photonic memristors, light polarization, metamaterials, polarizer filters, plasmonic structures, different colors of light, and possibly additional properties of light that can be filtered (i.e. phase), the synapses or photonic memristors have context-aware routing (CAR). With this context-aware routing, the artificial synapses of the quantum brain would be familiar with the kind of information they are receiving and whether it is relevant to them, a form of conditional signal flow, the same way that the (human) brain works. 

One aspect of the CAR is that it will be able to dynamically adjust its filters during operation. This is computationally powerful, as it allows for reconfigurable logic and memory wherein the same physical pathway can implement different logic operations at different times, and different filters can exist on either side of any given memristor. With this, adaptive routing is made possible, which is akin to synaptic plasticity in the brain. Additionally, contextual memory could be updated in real-time by reprogramming the filters. There are several technologies that allow for this dynamic adjustment, including tunable metasurfaces, electro-optic modulators, and thermally or optically switchable metamaterials.

Information would be encoded in a quaternary storage and, via a combination of transistors and memristors—as demonstrated in non-photonic neuromorphic computing—memory and processing can exist in the same location.

---

## Key Technologies & Their Biological Counterparts

-	_Synapses_ **Photonic Memristors**: Continuous analog input
-	_Dendrites_ **Context-aware routing(Filters) and Waveguides**: context encoding via (voltage or phase change) metamaterials, (electro-optic or 2D material) polarizers, (tunable metasurface or photonic crystal) waveplates, and (carrier injection or phase change coupling) plasmonic structures some or all of which are embedded into the waveguides
-	_Axon Hillock_ **Photonic Digital Logic Layer**: processes analog signal, decides if/what gate to trigger
-	_Axon_ **Photonic path/ (Qubits or Ququarts)**: Sends controlled signal(s) to (qubit or ququart) or the next unit
-	_Neuron Soma_ **Photonic (Qubits or Ququarts)**: stores and process the result of interpreted signals

---

## References

- [Neuromorphic Direct Drive Integration (QAI Deep Tech Blog)](https://qai.ai/deep-tech-blog/neuromorphic-direct-drive-integration-in-na-qai-qep-ndd-aom-semiotic-analysis-applications)

---

> *This project is experimental and highly interdisciplinary, combining quantum optics, photonics, neuromorphic computing, quantum computing, semiotics, and very advanced materials science.*
