---
uid: Microsoft.Quantum.Preparation.ApproximatelyPrepareArbitraryStateD
title: ApproximatelyPrepareArbitraryStateD operation
ms.date: 11/20/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Preparation
qsharp.name: ApproximatelyPrepareArbitraryStateD
qsharp.summary: >-
  Given a set of coefficients and a little-endian encoded quantum register,
  prepares an state on that register described by the given coefficients,
  up to a given approximation tolerance.
---

# ApproximatelyPrepareArbitraryStateD operation

Namespace: [Microsoft.Quantum.Preparation](xref:Microsoft.Quantum.Preparation)

Package: [Microsoft.Quantum.Standard](https://nuget.org/packages/Microsoft.Quantum.Standard)


Given a set of coefficients and a little-endian encoded quantum register,

```qsharp
operation ApproximatelyPrepareArbitraryStateD (tolerance : Double, coefficients : Double[], qubits : Microsoft.Quantum.Arithmetic.LittleEndian) : Unit is Adj + Ctl
```


## Description

This operation prepares an arbitrary quantum

## Input

### tolerance : [Double](xref:microsoft.quantum.lang-ref.double)

The approximation tolerance to be used when preparing the given state.


### coefficients : [Double](xref:microsoft.quantum.lang-ref.double)[]

Array of up to $2^n$ real coefficients. The $j$th coefficient


### qubits : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

Qubit register encoding number states in little-endian format. This is



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

Negative input coefficients $r_j < 0$ will be treated as though

## References

- Synthesis of Quantum Logic Circuits