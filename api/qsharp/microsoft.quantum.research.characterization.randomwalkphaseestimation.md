---
uid: Microsoft.Quantum.Research.Characterization.RandomWalkPhaseEstimation
title: RandomWalkPhaseEstimation operation
ms.date: 11/5/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Research.Characterization
qsharp.name: RandomWalkPhaseEstimation
qsharp.summary: >-
  Performs iterative phase estimation using a random walk to approximate
  Bayesian inference on the classical measurement results from a given
  oracle and eigenstate.
---

# RandomWalkPhaseEstimation operation

Namespace: [Microsoft.Quantum.Research.Characterization](xref:Microsoft.Quantum.Research.Characterization)

Package: [](https://nuget.org/packages/)


Performs iterative phase estimation using a random walk to approximate

```qsharp
operation RandomWalkPhaseEstimation (initialMean : Double, initialStdDev : Double, nMeasurements : Int, maxMeasurements : Int, unwind : Int, oracle : Microsoft.Quantum.Oracles.ContinuousOracle, targetState : Qubit[]) : Double
```


## Input

### initialMean : [Double](xref:microsoft.quantum.lang-ref.double)

Mean of the initial normal prior distribution over $\phi$.


### initialStdDev : [Double](xref:microsoft.quantum.lang-ref.double)

Standard deviation of the initial normal prior distribution over $\phi$.


### nMeasurements : [Int](xref:microsoft.quantum.lang-ref.int)

Number of measurements to be accepted into the final posterior estimate.


### maxMeasurements : [Int](xref:microsoft.quantum.lang-ref.int)

Total number of measurements than can be taken before the operation is considered to have failed.


### unwind : [Int](xref:microsoft.quantum.lang-ref.int)

Number of results to forget when consistency checks fail.


### oracle : [ContinuousOracle](xref:Microsoft.Quantum.Oracles.ContinuousOracle)

An operation representing a unitary $U$ such that $U(t)\ket{\phi} = e^{i t \phi}\ket{\phi}$


### targetState : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[]

A register that $U$ acts on.



## Output : [Double](xref:microsoft.quantum.lang-ref.double)

The final estimate $\hat{\phi} \mathrel{:=} \expect[\phi]$ , where

## Remarks

### Iterative Phase Estimation and Eigenstates

## References

- Ferrie *et al.* 2011 [doi:10/tfx](https://doi.org/10.1007/s11128-012-0407-6),