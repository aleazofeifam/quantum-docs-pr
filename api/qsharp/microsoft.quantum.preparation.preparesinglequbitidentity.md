---
uid: Microsoft.Quantum.Preparation.PrepareSingleQubitIdentity
title: PrepareSingleQubitIdentity operation
ms.date: 11/5/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Preparation
qsharp.name: PrepareSingleQubitIdentity
qsharp.summary: >-
  Prepares a qubit in the maximally mixed state.

  It prepares the given qubit in the $\boldone / 2$ state by applying the depolarizing channel
  $$
  \begin{align}
  \Omega(\rho) \mathrel{:=} \frac{1}{4} \sum_{\mu \in \{0, 1, 2, 3\}} \sigma\_{\mu} \rho \sigma\_{\mu}^{\dagger},
  \end{align}
  $$
  where $\sigma\_i$ is the $i$th Pauli operator, and where
  $\rho$ is a density operator representing a mixed state.
---

# PrepareSingleQubitIdentity operation

Namespace: [Microsoft.Quantum.Preparation](xref:Microsoft.Quantum.Preparation)

Package: [](https://nuget.org/packages/)


Prepares a qubit in the maximally mixed state.

```qsharp
operation PrepareSingleQubitIdentity (qubit : Qubit) : Unit
```


## Input

### qubit : [Qubit](xref:microsoft.quantum.lang-ref.qubit)

A qubit whose state is to be depolarized in the manner



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

The mixed state $\boldone / 2$ describing the result of