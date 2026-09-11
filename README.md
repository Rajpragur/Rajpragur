# raj

_math & computing @ IIT Patna '28_

[![website](https://img.shields.io/badge/website-0b0b0b?style=flat-square&logo=googlechrome&logoColor=white)](https://rajpragur.in) [![linkedin](https://img.shields.io/badge/linkedin-0b0b0b?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/rajpragur) [![raj@trelo.cc](https://img.shields.io/badge/raj%40trelo.cc-0b0b0b?style=flat-square&logo=gmail&logoColor=white)](mailto:raj@trelo.cc)

```python
class Raj:
    learning = ["low latency engineering", "inference / performance engineering"]
    curious  = "model architectures — why they are shaped the way they are"
    rule     = "measure the ceiling before optimising anything"
    daily_habit = "seeing the newest benchmaxxing model's performance, far too often"
```

I work in two places where latency *is* the product: trading systems and model inference.
They turn out to be the same discipline in different clothes. An order book and a decode loop
are both memory-bound problems pretending to be compute-bound ones, both punish a cache miss
more than a branch, and both are won by knowing what the hardware is actually doing.

```text
low latency                         inference
─────────────────────────────────────────────────────────────
lock-free ring buffers              GPU kernels, dispatch cost
cache lines, false sharing          memory bandwidth ceilings
memory ordering, atomics            quantisation, KV caches
p99 over averages                   TTFT over throughput
```

Separately I just like looking at architectures — MoE routing, attention variants, what got
dropped between one model generation and the next, and which choices were about quality versus
fitting the hardware. I check Artificial Analysis and benchmark leaderboards more often than is
strictly reasonable.

Also a devoted agent-harness user. Hermes runs my builds, benchmarks, job applications, and at
this point probably my dinner.

**now** · writing Metal and NEON kernels · lock-free C++20 · reading about quantisation

`C++` · `Python` · `Go` · `PyTorch` · `Docker` · `Git`
