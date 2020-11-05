---
uid: Microsoft.Quantum.Characterization.EstimateFrequencyA
title: EstimateFrequencyA operation
ms.date: 11/5/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Characterization
qsharp.name: EstimateFrequencyA
qsharp.summary: >-
  Given a preparation that is adjointable and measurement, estimates the frequency
  with which that measurement succeeds (returns `Zero`) by
  performing a given number of trials.
---

# EstimateFrequencyA operation

Namespace: [Microsoft.Quantum.Characterization](xref:Microsoft.Quantum.Characterization)

Package: [](https://nuget.org/packages/)


Given a preparation that is adjointable and measurement, estimates the frequency

```qsharp
operation EstimateFrequencyA (preparation : (Qubit[] => Unit is Adj), measurement : (Qubit[] => Result), nQubits : Int, nMeasurements : Int) : Double
```


## Input

### preparation : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[] => [Unit](xref:microsoft.quantum.lang-ref.unit) Adj

An adjointable operation $P$ that prepares a given state $\rho$ on


### measurement : [Qubit](xref:microsoft.quantum.lang-ref.qubit)[] => __invalid<Result>__ 

An operation $M$ representing the measurement of interest.


### nQubits : [Int](xref:microsoft.quantum.lang-ref.int)

The number of qubits on which the preparation and measurement


### nMeasurements : [Int](xref:microsoft.quantum.lang-ref.int)

The number of times that the measurement should be performed



## Output : [Double](xref:microsoft.quantum.lang-ref.double)

An estimate $\hat{p}$ of the frequency with which

## Remarks

For adjointable operations, certain assumptions can be made such like