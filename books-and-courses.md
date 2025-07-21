---
layout: default
title: Books and courses
---

# Books and courses

{% capture UQIC %}

This is a course on the theory of quantum computing that I created while working for IBM. It consists of 16 lessons divided into four units, with each lesson including a video and a written component, and covers subject matter roughly corresponding to a one-semester university course at the advanced undergraduate or introductory graduate level.

### Written material

- Download all 16 lessons as a single file [[pdf]]({{ '/UQIC.pdf' | relative_url }})
- Find four courses named for the four units from [Quantum learning](https://quantum.cloud.ibm.com/learning/en) on the IBM Quantum Platform:
  - [Basics of quantum information](https://quantum.cloud.ibm.com/learning/en/courses/basics-of-quantum-information)
  - [Fundamentals of quantum algorithms](https://quantum.cloud.ibm.com/learning/en/courses/fundamentals-of-quantum-algorithms)
  - [General formulation of quantum information](https://quantum.cloud.ibm.com/learning/en/courses/general-formulation-of-quantum-information)
  - [Foundations of quantum error correction](https://quantum.cloud.ibm.com/learning/en/courses/foundations-of-quantum-error-correction)

### Videos

Videos are available on the [Qiskit](https://www.youtube.com/@qiskit) YouTube channel as a [playlist](https://www.youtube.com/playlist?list=PLOFEBzvs-VvqKKMXX4vbi4EB1uaErFMSO) or by lesson:

- Lesson 1: [Single Systems](https://youtu.be/3-c4xJa7Flk)
- Lesson 2: [Multiple Systems](https://youtu.be/DfZZS8Spe7U)
- Lesson 3: [Quantum Circuits](https://youtu.be/30U2DTfIrOU)
- Lesson 4: [Entanglement in Action](https://youtu.be/GSsElSQgMbU)
- Lesson 5: [Quantum Query Algorithms](https://youtu.be/2wticzHE1vs)
- Lesson 6: [Quantum Algorithmic Foundations](https://youtu.be/2wxxvwRGANQ)
- Lesson 7: [Phase Estimation and Factoring](https://youtu.be/4nT0BTUxhJY)
- Lesson 8: [Grover’s Algorithm](https://youtu.be/hnpjC8WQVrQ)
- Lesson 9: [Density Matrices](https://youtu.be/CeK9ry8G8HQ)
- Lesson 10: [Quantum Channels](https://youtu.be/cMl-xIDSmXI)
- Lesson 11: [General Measurements](https://youtu.be/Xi9YTYzQErY)
- Lesson 12: [Purifications and Fidelity](https://youtu.be/jemWEdnJTnI)
- Lesson 13: [Correcting Quantum Errors](https://youtu.be/OoQSdcKAIZc)
- Lesson 14: [The Stabilizer Formalism](https://youtu.be/3ib2JP_LeIU)
- Lesson 15: [Quantum Code Constructions](https://youtu.be/9TCIOm8gcVQ)
- Lesson 16: [Fault-Tolerant Quantum Computation](https://youtu.be/aeaqXh2XXMk)

{% endcapture %} 

{% include collapsible.html title="Understanding Quantum Information and Computation" content=UQIC %}

{% capture TQI %}

Published by [Cambridge University Press](https://www.cambridge.org/) in April 2018. This book is available for purchase through Cambridge University Press and other standard distribution channels. Please see the publisher's web page to order the book or to obtain further details on its publication. A manuscript of the book can be found below—it has been made available for personal use only and must not be sold or redistributed.

Errata [[pdf]]({{ '/TQI-errata.pdf' | relative_url }})

### Complete book

- Standard layout [[pdf]]({{ '/TQI.pdf' | relative_url }})
- Compact layout [[pdf]]({{ '/TQI.double.pdf' | relative_url }})

### Individual chapters (standard layout)

1. Mathematical preliminaries [[pdf]]({{ 'TQI.1.pdf' | relative_url }})
2. Basic notions of quantum information [[pdf]]({{ 'TQI.2.pdf' | relative_url }})
3. Similarity and distance among states and channels [[pdf]]({{ 'TQI.3.pdf' | relative_url }})
4. Unital channels and majorization [[pdf]]({{ 'TQI.4.pdf' | relative_url }})
5. Quantum entropy and source coding [[pdf]]({{ 'TQI.5.pdf' | relative_url }})
6. Bipartite entanglement [[pdf]]({{ 'TQI.6.pdf' | relative_url }})
7. Permutation invariance and unitarily invariant measures [[pdf]]({{ 'TQI.7.pdf' | relative_url }})
8. Quantum channel capacities [[pdf]]({{ 'TQI.8.pdf' | relative_url }})

### Individual chapters (compact layout)

1. Mathematical preliminaries [[pdf]]({{ 'TQI.double.1.pdf' | relative_url }})
2. Basic notions of quantum information [[pdf]]({{ 'TQI.double.2.pdf' | relative_url }})
3. Similarity and distance among states and channels [[pdf]]({{ 'TQI.double.3.pdf' | relative_url }})
4. Unital channels and majorization [[pdf]]({{ 'TQI.double.4.pdf' | relative_url }})
5. Quantum entropy and source coding [[pdf]]({{ 'TQI.double.5.pdf' | relative_url }})
6. Bipartite entanglement [[pdf]]({{ 'TQI.double.6.pdf' | relative_url }})
7. Permutation invariance and unitarily invariant measures [[pdf]]({{ 'TQI.double.7.pdf' | relative_url }})
8. Quantum channel capacities [[pdf]]({{ 'TQI.double.8.pdf' | relative_url }})

{% endcapture %} 

{% include collapsible.html title="The Theory of Quantum Information" content=TQI %}