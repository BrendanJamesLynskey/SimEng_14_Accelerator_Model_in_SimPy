# Simulation Engineering Toolkit 14 — An Accelerator Model in SimPy, End to End

A real graph from torch.export or ONNX run through an event-driven model of a tiled accelerator: off-chip memory, interconnect, DMA engines, an on-chip buffer with back-pressure, a compute array and a vector unit. Lowering to tiles, a cycle-approximate timing model, the roofline, Little's law and stall attribution, a timeline and hot-spot report, a cycle-stepped twin, how gem5 and SST are structured, a bit-identical C++ fast path with pybind11, ONNX Runtime execution providers, and an FHE-style NTT workload.

Topics: SimPy, Back-pressure, Stall attribution, Cycle-based twin, gem5 and SST, pybind11, Execution providers, NTT.

**Live site:** https://brendanjameslynskey.github.io/SimEng_14_Accelerator_Model_in_SimPy/

Part of the [Simulation Engineering Toolkit series](https://github.com/BrendanJamesLynskey/SimEng_Hub_Toolkit). Companion code: [Torch_Sim_Frontend](https://github.com/BrendanJamesLynskey/Torch_Sim_Frontend). Interview questions: [Interview_Simulation](https://github.com/BrendanJamesLynskey/Interview_Simulation), [Interview_AI_Accelerator_Architecture](https://github.com/BrendanJamesLynskey/Interview_AI_Accelerator_Architecture), [Interview_CPP](https://github.com/BrendanJamesLynskey/Interview_CPP). Every concept used here is explained, with links, in the [series glossary](https://brendanjameslynskey.github.io/SimEng_Hub_Toolkit/#glossary).

Slides and text: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
