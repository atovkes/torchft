# TorchFT Documentation and Presentation

This document provides an overview of TorchFT, covering key concepts and architectural details.

## Table of Contents

1.  [Parallelism Strategies](#parallelism-strategies)
2.  [Parameter, Data, and Gradient Sharding](#parameter-data-and-gradient-sharding)
3.  [Torch Computation Graph and Allreduce](#torch-computation-graph-and-allreduce)
4.  [TorchFX Framework Overview](#torchfx-framework-overview)
5.  [DiLoCo Algorithm Differences](#diloco-algorithm-differences)
6.  [Checkpointing and TCPStore](#checkpointing-and-tcpstore)
7.  [Quorum Flow Diagram](#quorum-flow-diagram)
8.  [DiLoCo Flow Diagram](#diloco-flow-diagram)

---

## 1. Parallelism Strategies

*   Pipeline parallelism, FSDP and Pipeline + FSDP

## 2. Parameter, Data, and Gradient Sharding

*   How we shard parameters, data and gradients during forward pass and backprop pass

## 3. Torch Computation Graph and Allreduce

*   How torch computation graph looks like and why we need make allreduce during backprop

## 4. TorchFX Framework Overview

*   High overview of torchfx framework

## 5. DiLoCo Algorithm Differences

*   Algo differences between classical Diloco and streaming Diloco

## 6. Checkpointing and TCPStore

*   About checkpoints to TCPStore, diloco 2 ways of storing checkpoints and Sasha also calculations

---

## 7. Quorum Flow Diagram

For a detailed understanding of the quorum mechanism, please refer to the diagram below:

[Quorum Flow Diagram](./quorum_flow_new.md)

<!-- Placeholder for Quorum Flow Diagram content if embedded directly -->

---

## 8. DiLoCo Flow Diagram

To visualize the DiLoCo algorithm flow, see the diagram linked here:

[DiLoCo Flow Diagram](./diloco_flow.md)

<!-- Placeholder for DiLoCo Flow Diagram content if embedded directly -->

---

## Additional Diagrams/Sections (Placeholders)

*   **[Diagram Title 1]**
    *   Link to Diagram 1: [Diagram1.md](./Diagram1.md)
    *   Brief description or placeholder text.

*   **[Diagram Title 2]**
    *   Link to Diagram 2: [Diagram2.md](./Diagram2.md)
    *   Brief description or placeholder text.

*   **[Section Title 1]**
    *   Content for Section 1.

*   **[Section Title 2]**
    *   Content for Section 2.
