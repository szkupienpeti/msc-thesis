# Step-by-Step Controllable Simulation of Component-Based Reactive Systems Based on Precise Formal Semantics

My MSc thesis in the field of Computer Science Engineering at Budapest University of Technology and Economics ([BME](https://www.bme.hu/?language=en) [VIK](https://vik.bme.hu/en/) [MIT](https://www.mit.bme.hu/eng/) [ftsrg](https://ftsrg.mit.bme.hu/en/)) under the supervision of [Vince Molnár, PhD](https://inf.mit.bme.hu/members/molnarv).

## Abstract
Safety-critical software systems are becoming more and more complex with the continuous spreading of software solutions in all areas of life. These systems must operate correctly under all circumstances, otherwise, their fault would cause catastrophic consequences. Therefore, for guaranteeing safety, new development principles have been introduced, such as model-based systems engineering (MBSE).

To apply MBSE, engineers need high-level modeling languages for describing the different aspects of systems. One of the crucial aspects is the dynamic behavior, for which the application of executable models is spreading. These models have their precise formal semantics defined by low-level mathematical concepts. The abstraction gap between the high-level models used by engineers, and their semantics defined on a low level, makes it harder to understand the precise semantics of a high-level model. A common example of this is the internal non-determinism inside high-level atomic steps, which may only occur in the hidden low-level. It is a general need for engineers to be able to simulate their models, in order to observe their behavior precisely. Internal non-determinism makes some parts of the executions uncontrollable and unobservable, causing imprecise simulation.

In this thesis, I present some modeling languages with different abstraction levels which are used to model component-based reactive systems. Based on their semantics, I analyze the possible non-deterministic decisions of their execution and propose my own algorithm to make internal non-determinism external. Building on this, I design a simulation framework, which enables the user to control the simulation step-by-step, by making every non-deterministic decision explicit. I also identify different use cases, for which different simulation control mechanisms are presented.

I implemented my theoretical results as parts of open-source tools – the Gamma Statechart Composition Framework, and the Theta Model Checking Framework – which I also briefly present. Finally, the use of my work is discussed through a case study.

---
Based on the [LaTeX thesis template](https://github.com/ftsrg/thesis-template-latex) of [ftsrg](https://github.com/ftsrg).
