---
uid: Microsoft.Quantum.AmplitudeAmplification.StandardAmplitudeAmplification
title: StandardAmplitudeAmplification function
ms.date: 11/5/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.AmplitudeAmplification
qsharp.name: StandardAmplitudeAmplification
qsharp.summary: Standard Amplitude Amplification algorithm
---

# StandardAmplitudeAmplification function

Namespace: [Microsoft.Quantum.AmplitudeAmplification](xref:Microsoft.Quantum.AmplitudeAmplification)

Package: [](https://nuget.org/packages/)


Standard Amplitude Amplification algorithm

```qsharp
function StandardAmplitudeAmplification (nIterations : Int, stateOracle : Microsoft.Quantum.Oracles.StateOracle, idxFlagQubit : Int) : (Qubit[] => Unit is Adj + Ctl)
```


## Input

### nIterations : [Int](xref:microsoft.quantum.lang-ref.int)

Number of iterations $n$ of amplitude amplification


### stateOracle : [StateOracle](xref:Microsoft.Quantum.Oracles.StateOracle)

Unitary oracle $A$ that prepares start state


### idxFlagQubit : [Int](xref:microsoft.quantum.lang-ref.int)

Index to flag qubit



## Output : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[] => [Unit](xref:microsoft.quantum.lang-ref.unit) Adj + Ctl

An operation that implements the standard amplitude amplification quantum algorithm

## Remarks

This is the standard amplitude amplification algorithm obtained by a choice of reflection phases computed by `AmpAmpPhasesStandard`

## References

- [ *G. Brassard, P. Hoyer, M. Mosca, A. Tapp* ](https://arxiv.org/abs/quant-ph/0005055)