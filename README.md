# weighted_job_selection
Generalized weighted job selection problem for Algorithms and Data structures course

## Introduction

Given T programming tasks, each one with a starting date, an ending date, and a profit, and given P programmers, the generalized weighted job selection problem asks for the best subset of programming tasks such that:
- the sum of the profits of the programming tasks belonging to the subset is maximized,
- each programming task is done by a single programmer
- each programmer cannot work on more than one task at a time

Under the rules given above a programmer cannot interrupt a programming task to do another programming task; once she/he is commited to a programming task, she/he is busy until that task ends.

![Image](/screenshots/results.png)

## How to compile and run

```
make job_selection
./job_selection 98597 (no. of programs) (no. of programmers) (seed)
```

## Authors

- [José Trigo](https://github.com/zepedrotrigo)
- [Pedro Monteiro](https://github.com/pedromonteiro01)
- [André Gomes](https://github.com/andregomes04)
