# Human Verification Testing Protocol

**A controlled route from an unresolved claim to a reviewable observation.**

*Public protocol summary*

## Purpose

Documentation, community reports, AI synthesis, and observed behavior do not always agree. This protocol describes how uncertain claims can be investigated through controlled observation while preserving inconsistent and negative results.

This page summarizes the protocol; the complete test template and project-specific decision rules remain private.

## Before Testing

Define the claim and the observable behavior that would support or challenge it. Identify the relevant conditions, including equipment state, environment, configuration, prerequisites, inputs, initialization, and known limitations.

Set the trial plan and review criteria before interpreting results. Record deviations when conditions change.

## Record and Review

| Step | Review focus |
| --- | --- |
| Establish conditions | Are prerequisites met, and is the starting state understood? |
| Observe the trial | What happened, under which conditions, and how was it recorded? |
| Check repeatability | Does the behavior recur under comparable conditions? |
| Preserve discrepancies | Which results differ from the expected behavior or other trials? |
| Review the evidence | What does the observation support, and what remains unresolved? |
| Revisit classification | Is a change to the [evidence status](./verification-framework.md) justified? |

## Outcome Categories

- **Repeatable success:** the expected behavior recurs under the defined conditions.
- **Repeatable variant:** a consistent behavior differs from the expectation.
- **Inconsistent result:** outcomes vary across comparable trials.
- **No observable response:** the expected behavior was not observed.
- **Repeatable rejection or unsupported result:** the system consistently rejects the tested input or indicates it is unsupported under the tested conditions.

No response alone does not establish that a capability is absent. Preconditions, input interpretation, system state, and observation limits may explain it. Repeated results support conclusions within the tested scope.

## Human Review

AI may organize trials, compare observations, and surface contradictions. A person validates conditions, interprets variation, and approves evidence-status changes.

**One observation should not be generalized beyond what it supports.**

## Public Scope

This guide demonstrates verification design. It does not publish test results, exact repetition thresholds, pass/fail criteria, project-specific procedures, private record schemas, or automation logic.

[Research Case Study](./README.md) · [Verification Framework](./verification-framework.md) · [Applied AI Systems](../../README.md)
