# Learning to Schedule

This project contains the code for implementing the preemptive-then-nonpreemtive empirical c\mu rule developed in the paper "Learning to Schedule".

## uniform service times.ipynb

This Python code implements the preemptive-then-nonpreemtive empirical c\mu rule for the setting where the service time of each job is deterministic and fixed at T. Figures 1 and 3 in the paper are drawn based on experiments run by this code. 

## heterogeneous service times.ipynb

This Python code implements the preemptive-then-nonpreemtive empirical c\mu rule for the setting where jobs have deterministic but heterogeneous service times. Figure 2 in the paper is drawn based on experiments run by this code. 

## Figure 1

Figure 1 in the paper has two plots: "uniform-regret.pdf" and "uniform-relative.pdf". "uniform-regret.pdf" plots and compares the regret values of three different versions of the empirical c\mu rul: the preemptive, nonpreemptive, and preemptive-then-nonpreemptive versions. "uniform-relative.pdf" plots the relative regret values, defined as the fraction of the regret and the minimum expected cumulative holding cost. 

## Figure 2

Figure 2 in the paper has two plots: "hetero-regret.pdf" and "hetero-relative.pdf". Figure 2 is similar to Figure 1 but plots data from experiments with jobs of heterogeneous service times. 

## Figure 3

Figure 3 in the paper has two plots: "uniform-T.pdf" and "uniform-N.pdf". "uniform-T.pdf" shows how the expected regret grows for the case of identical service times as the value of T increases. Similarly, "uniform-N.pdf" shows how the expected regret grows as a function of N.
