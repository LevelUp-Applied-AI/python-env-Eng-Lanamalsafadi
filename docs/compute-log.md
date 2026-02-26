## Compute Log — PR 4

==================================================
SYSTEM INFORMATION
==================================================
OS:         Windows 10
Version:    10.0.19045
Machine:    AMD64
Processor:  Intel64 Family 6 Model 142 Stepping 12, GenuineIntel
Python:     3.14.3 (tags/v3.14.3:323c59a, Feb  3 2026, 16:04:56) [MSC v.1944 64 bit (AMD64)]

Benchmark 1 — sum(range(5,000,000))
  Result:  12,499,997,500,000
  Time:    0.0730 seconds

Benchmark 2 — list comprehension (n=1,000,000)
  First 5: [0, 1, 4, 9, 16]
  Time:    0.0756 seconds

Benchmark 3 — string join (n=100,000)
  Length:  588,889 characters
  Time:    0.0136 seconds

==================================================
SUMMARY
==================================================
  sum benchmark:    0.0730s
  list benchmark:   0.0756s
  string benchmark: 0.0136s

## RAM

Total RAM: 16 GB