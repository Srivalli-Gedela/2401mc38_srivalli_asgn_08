# OS Assignment 8 — Virtual Memory and Address Translation

**Submission folder:** `2401mc38_srivalli_asgn_08`

## Contents

- `q1/` — Virtual-to-physical address translation (`va2pa`) implementation and test program.
- `q2/` — Physical memory statistics (`getmeminfo`) and memory test.
- `q3/` — Process page-table inspection (`vmprint`) and test program.
- `q4/` — Lazy allocation / demand paging implementation and test program.
- `screen shots/` — Output screenshots for questions 1–4 (`q1_ss.png` through `q4_ss.png`).
- `report.pdf` — Assignment report with implementation notes, issue-resolution notes, and test observations.

## Build and run

Run these commands from the xv6 source tree that contains the assignment's integrated changes. The question folders here contain the relevant files; they are not necessarily a complete standalone xv6 tree.

1. Build and launch xv6 using the course-provided Makefile/environment (commonly `make qemu-nox`).
2. From the xv6 shell, run the corresponding test:

   | Question | Test command |
   |---|---|
   | Q1 | `vatest` |
   | Q2 | `memtest` |
   | Q3 | `vmprinttest` |
   | Q4 | `lazytest` |

3. To exit QEMU, use `Ctrl+A`, then `X` (if supported by your terminal setup).

## Notes

- The source files and screenshots from the provided archive have been retained; screenshots are grouped under `screen shots/` for convenient submission.
- Check the course's required xv6 version and build instructions before running, since syscall and page-table interfaces can differ between xv6 variants.
