# AugurCloud
AugurCloud (庆云): Heterogeneous AI compute orchestration platform for LLM distributed training &amp; inference.


# AugurCloud（庆云）

> **AugurCloud — Augur the fabric of cosmic compute.**
> 中文标语：**庆云垂象，预演星算**

## About
AugurCloud is a heterogeneous AI compute orchestration platform, built to unify GPU, XPU and diverse hardware resources for LLM training and inference workloads.

The word **Augur** comes from Latin. In ancient Rome, an augur observed clouds and celestial omens to read signs. This echoes the ancient Chinese myth of **Qingyun (庆云 / 诸天庆云)**, the primordial auspicious nebula condensed from cosmic vitality.

Compute nodes spread across the cluster like nebulae in the firmament. AugurCloud orchestrates tensor flows, data/tensor/pipeline parallelism and collective communication such as Ring-AllReduce across heterogeneous hardware.
Tensors and model weights circulate within this auspicious compute fabric.

> Note: AugurCloud is an independent open-source project, no affiliation with other projects named Augur.

### Sub Projects
- **AugurAvatar**: Digital human application powered by AugurCloud.
- **HeteroTrain-Tutorial**: Deep dive tutorials for distributed training stacks (PyTorch / DeepSpeed / Megatron-LM).

## Core Capabilities
- Heterogeneous compute resource abstraction: unify GPU / XPU hardware
- Scheduling for LLM training & inference workloads
- Topology-aware tensor orchestration and collective communication
- Elastic scaling of compute resources
- Distributed cluster observability for tensor flow

## Roadmap
- [ ] Core resource abstraction layer
- [ ] Topology-aware scheduler optimized for Ring-AllReduce
- [ ] Model weight partitioning & cross-hardware migration
- [ ] Tensor flow observability stack
- [ ] AugurAvatar demo integration

## License
AugurCloud is licensed under the Apache License 2.0.
See the [LICENSE](./LICENSE) file for full license text.

Copyright © [YEAR] [Your Name]
