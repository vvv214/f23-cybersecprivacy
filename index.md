---
title: 
permalink: /
---


In a world driven by data science and transformed by machine learning, the questions of security and privacy take center stage. As algorithms become more sophisticated and interconnected, the balance between innovation and protection becomes a thrilling and complex challenge.

Welcome to our seminar course on Special Topics in Data Science, Cyber Security and Privacy – a journey into the future where machine learning meets its most fascinating counterpart: the art of keeping information safe and secure. This course will guide you through a maze of cutting-edge techniques, hidden layers of defense, and the ethical considerations that underpin our digital lives.

From the secret codes that shield our most sensitive data to the unseen algorithms that ensure individuals' privacy, this course offers an exploration that's both broad in scope and deep in its revelations. Whether it's designing robust machine learning models or unveiling the methods that protect the integrity of data, every lesson will unveil a new layer of intrigue.

Join us on this captivating intellectual expedition, and be part of the next generation of innovators, thinkers, and protectors of our digital world. Here, the known meets the unknown, the explicit meets the implicit, and every discovery is a step towards a safer and more transparent future.

Your path to the forefront of security and privacy starts now.

Prerequisites only include basic knowledge of coding (Python), algorithms, and probability.


- Instructor: [Tianhao Wang](https://tianhao.wang)
- Location: Rice 011 
- Time: TuTh 2pm - 3:15pm
- TA: [Mingtian Tan](wtd3gz@virginia.edu)
- Discussion: 
  - [Course Website](https://tianhao.wang/f23-cybersecprivacy/)
  - [Canvas](https://canvas.its.virginia.edu/courses/77158) 
- Office Hour
  - Mingtian: MW 2pm-3pm Room 542, [Zoom](), and by appointment
  - Tianhao: F 2pm-3pm Room 506, [Zoom](https://virginia.zoom.us/j/92226411033?pwd=SSthSnRKZzBIQzhMbGtsNmpHU0dIUT09&from=addon), and by appointment


## Grading (tentative, subject to change): 
- Four assignments (40%, 10% each). Theory (proofs) and practice (programming in python) will be covered in each assignment.
- Paper presentation (20%): Each student will present a paper for 35 minutes (30min presentation plus 5min Q&A). If the slides are public or there are videos available online, it is okay to reuse the slides, but make sure you make a high-quality presentation.
- [Project](project.md) (40%). Teams should utilize office hours to get feedbacks on the project. 

## Topics
1. privacy and security issues in machine learning
- preliminaries of machine learning, nlp, graph neural networks, GANs, self-supervise learning, and federated learning
- attacks and basic defenses to deep learning models, covering: membership inference attack, attribute inference attack, property inference attack, reconstruction attack, evasion attack, poison attack, backdoor attack
- machine unlearning

2. differential privacy (dp, the standard way for protecting privacy)
- earlier works of k-anonymity, l-diversity and t-closeness and their limitations
- basics of dp (definitions, compositions)
- primitives for satisfying dp
  - Laplace mechanism, Exponential mechanism, Report-noisy-max, SVT, Gaussian mechanism
- advanced composition, renyi dp
- applications: hierarchical method, marginals and generative models, graph, ml (dpsgd)
- other notions: local dp, shuffle dp
- relaxed definition of dp 
  - geo-indistinguishability, event-level, w-window, label dp
- interaction of dp with other domains, such as fairness, usability, explanabilities
- secure implementation of dp (and floating-point attacks to dp)

3. cryptography
- prelims of crypto: encryption, hash, message authentication, public-key encryption
- crypto-based techniques, including secure multi-party computation, homomorphic encryption (with federated learning), zero-knowledge proofs, encrypted databases, oblivious RAM, blockchain, 
- Tor
- secure hardware
- quantum computer 

4. student-led presentations

## Schedule (tentative, subject to change), we will meet in person

| Week |     Dates      |            Monday            |           Wednesday          |            Friday           |
| :--: | :------------: | :---------------------------:| :---------------------------:| :--------------------------:|
|  1   | Aug 21 - Aug 25|           No Class           |          Introduction        |     ML Preliminaries        |
|  2   | Aug 28 - Sep 1 |        GANs & Self-Supervised Learning |  Federated Learning  |  NLP & Graph Neural Networks |
|  3   | Sep 4 - Sep 8  |    Attacks & Basic Defenses   |  More Attacks & Defenses     |    Machine Unlearning       |
|  4   | Sep 11 - Sep 15|   Earlier Privacy Works      |  Basics of DP (Definitions)  |  DP Primitives (Laplace, etc.) |
|  5   | Sep 18 - Sep 22|  Advanced DP & Renyi DP      |  DP Applications             |    Local & Shuffle DP       |
|  6   | Sep 25 - Sep 29|      Relaxed DP Definitions  | DP Interaction with Other Domains |   Secure Implementation of DP |
|  7   | Oct 2 - Oct 6  |     Prelims of Crypto        |      Crypto-Based Techniques |           Tor                |
|  8   | Oct 9 - Oct 13 |   Secure Hardware            |  Quantum Computer            |        Blockchain           |
|  9   | Oct 16 - Oct 20|      Mid-Term Project Presentations        |      Mid-Term Project Presentations     |      Mid-Term Project Presentations     |
| 10   | Oct 23 - Oct 27| Student-led Paper Presentations | Student-led Paper Presentations | Student-led Paper Presentations |
| 11   | Oct 30 - Nov 3 | Student-led Paper Presentations | Student-led Paper Presentations |          No Class           |
| 12   | Nov 6 - Nov 10 | Student-led Paper Presentations | Student-led Paper Presentations | Student-led Paper Presentations |
| 13   | Nov 13 - Nov 17| Student-led Paper Presentations | Student-led Paper Presentations | Student-led Paper Presentations |
| 14   | Nov 20 - Nov 24|      Final Presentations           |           No Class           |           No Class          |
| 15   | Nov 27 - Dec 1 |      Final Presentations           |       Final Presentations          |       Final Presentations         |
| 16   | Dec 4  - Dec 8 |      Final Presentations           |           No Class           |           No Class          |
