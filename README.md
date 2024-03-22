# Dynamic Systems Analysis of Ellis and Maartens' Emergent Universe

## Prerequisites

To run this notebook, the user requires a Mathematica license and to have installed MaTeX (see https://github.com/szhorvat/MaTeX).

To avoid a Git large file error, a Git hook has been added which clears the output when the file is committed. To set the hooks directory to the .githooks folder, the following command needs to be run in your local directory where this repository has been pulled:

git config --local core.hooksPath .githooks/

## Analysis

In this notebook, a dynamical systems analysis of Ellis and Maartens' emergent universe scenario (https://arxiv.org/abs/gr-qc/0211082) is analysed. This scenario involves a scalar field with a plateau potential. In their paper, Ellis and Maartens' analyse this model with specific initial conditions such that the universe is past asymptotic to an initial Einstein state. The aim of this analysis is to consider all possible initial conditions to understand whether the generic past attractor is non-singular. Although we find other cases that can emerge from a non-singular de Sitter state, generally trajectories are past asymptotic to a singularity. 

This analysis in the notebook provides:

+ plots of the flat sub-manifold,
+ the sub-manifold where $\phi \rightarrow -\infty$,
+ the full phase space,
+ stability analysis of the fixed points in each case.
