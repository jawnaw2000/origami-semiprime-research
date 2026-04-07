# origami-semiprime-research
# Origami Lattice Folding for Semiprime Factoring

## Overview

This project explores whether geometric transformations inspired by origami folding can improve the detection of factor-related structures in lattices used for semiprime factorization.

---

## Hypothesis

Can a sequence of geometric "fold" operations (reflections, projections, or structured basis transformations) applied to a lattice basis transform it in such a way that short vectors encoding factor information become easier to detect than with standard lattice reduction methods alone?

---

## Baseline

The baseline methods for comparison include:

* LLL (Lenstra–Lenstra–Lovász lattice reduction)
* Standard small-root or lattice-based factoring approaches

These methods operate purely algebraically without geometric folding transformations.

---

## Proposed Method

Introduce "fold operators" that:

* Reflect lattice vectors across chosen hyperplanes
* Compress or align vectors along meaningful axes
* Iteratively reshape the lattice before or during reduction

These folds are inspired by origami crease patterns and geometric symmetry.

---

## Success Criteria

The method will be considered successful if it demonstrates any of the following:

* Faster discovery of factor-related short vectors compared to baseline methods
* Higher probability of detecting useful candidate vectors
* Reduction in computational time for equivalent problem sizes
* Improved structure in the transformed lattice that correlates with factorization success

---

## Metrics

The following metrics will be measured:

1. Time to candidate discovery
2. Success rate (percentage of runs yielding useful vectors)
3. Quality of candidate vectors (distance from true factor relation)
4. False positive rate (irrelevant short vectors)
5. Stability across multiple semiprime sizes

---

## Initial Experimental Plan

* Generate lattices derived from semiprime structures
* Apply:

  * Baseline LLL reduction
  * Fold transformations + LLL
* Compare outputs across identical inputs
* Run multiple trials for statistical significance

---

## Long-Term Goal

To determine whether geometric lattice transformations provide a meaningful advantage in integer factorization, and if so, formalize the method into a publishable framework.

---
