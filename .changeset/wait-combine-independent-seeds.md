---
"llama-index-workflows": patch
---
Give each strategy in `wait_combine` its own jitter seed, so `wait_random(0, 1) + wait_random(0, 1)` sums two independent draws instead of doubling one.
