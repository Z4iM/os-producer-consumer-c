# OS Producer/Consumer — Course Project

This repository holds two C implementations of the producer/consumer assignment described in the course report:

1. `prodcons_naive` — a naïve, file-based implementation (no semaphores).  
2. `prodcons_sem` — a synchronized implementation that uses POSIX semaphores.

Both are implemented in C using POSIX threads and tested on **Ubuntu**.

---

## TL;DR
- Language: **C (POSIX)**  
- Build: `make`  
- Execs: `prodcons_naive` and `prodcons_sem`  
- Test: `bash tests/run_test.sh`

---

## How to build
```bash
# from repository root
make
