Paper: Hustiu I., Hustiu S., Toader A-A., Kloetzer M., Mahulea C., A Time Petri Net Framework for Heterogeneous Robots and MITL Specifications, submited to IFAC World Congress 2026.

This paper presents a Time Petri Net (TPN) framework that enables heterogeneous mobile robots to satisfy a global Metric Interval Temporal Logic (MITL) mission. Robot motion is modeled through quotient TPN abstractions, while the MITL formula is translated into a TPN. Synchronization transitions couple both models, triggering mission progression only when collaborative actions occur, ensuring correctness-by-construction. Unlike optimization-based approaches, the execution sequence is computed as a reachability path in the composed TPN using the ROMEO tool. A case study with three robots illustrates how the framework enforces temporal and spatial constraints and confirms feasibility through reachability analysis.

The ROMEO tool used for modeling and simulation is from [1]. 

[1] Lime, Didier, et al. "Romeo: A parametric model-checker for Petri nets with stopwatches." International Conference on Tools and Algorithms for the Construction and Analysis of Systems. Berlin, Heidelberg: Springer Berlin Heidelberg, 2009.
