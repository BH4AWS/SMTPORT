# SMTPORT
the experimental results of SMTPORT

This work releases all experimental evaluation results of four algorithm variants in SMTPORT (A Parallel Framework of Combining Satisfiability Modulo Theory with 

Indicator-based Evolutionary Algorithm).

To further improve the optimization efficiency, we propose a parallel framework called SMTPORT for addressing the configuration optimization problems in software 

product lines (SPLs), which combines four corresponding SMTIBEA variants and performs these variants utilizing parallelization techniques within the limited time 

budget.We perform the above variants and present the original experimental results in five SPLs of the synthetic attribute values (Linux, eCos, FreeBSD, Fiasco and 

uClinux) and two feature models of real attribute values (Drupal and AmazonEC2The).

We mainly introduce one type of file and folder structure as follows:

1. the folder of SMTIBEAV1_result: the experimential results are generated from SMTIBEAv1 variant.
2. the folders of eCos,Fiasco,FreeBSD,Linux-2.6.28.6 and uClinux: the different experimental results for the special SPL
3. the file of 2.6.28.6-icse11.SMTibeaV1-150m.out.1: the first evaluation result of the linux SPL for SMTIBEAv1 variant, the terminal time is 15 minutes.
4. the folder of Merge_result: we merge the results from four SMTIBEA variants for different SPLs in terms of Pareto dominance.

Attention please: the 2.6.28.6-icse11 is the detail name of Linux SPL.
