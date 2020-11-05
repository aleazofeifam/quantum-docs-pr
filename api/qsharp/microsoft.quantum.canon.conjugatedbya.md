---
uid: Microsoft.Quantum.Canon.ConjugatedByA
title: ConjugatedByA function
ms.date: 11/5/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: ConjugatedByA
qsharp.summary: >-
  Given outer and inner operations, returns a new operation that
  conjugates the inner operation by the outer operation.
---

# ConjugatedByA function

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [](https://nuget.org/packages/)


Given outer and inner operations, returns a new operation that

```qsharp
function ConjugatedByA<'T> (outerOperation : ('T => Unit is Adj), innerOperation : ('T => Unit is Adj)) : ('T => Unit is Adj)
```


## Input

### outerOperation : 'T => [Unit](xref:microsoft.quantum.lang-ref.unit) Adj

The operation $U$ that should be used to conjugate $V$. Note that the


### innerOperation : 'T => [Unit](xref:microsoft.quantum.lang-ref.unit) Adj

The operation $V$ being conjugated.



## Output : 'T => [Unit](xref:microsoft.quantum.lang-ref.unit) Adj

A new operation whose action is represented by the unitary

## Type Parameters

### 'T

The type of the target on which each of the inner and outer operations

## Remarks

The outer operation is always assumed to be adjointable, but does not

## See Also

- [Microsoft.Quantum.Canon.ConjugatedByA](xref:Microsoft.Quantum.Canon.ConjugatedByA)
- [Microsoft.Quantum.Canon.ConjugatedByC](xref:Microsoft.Quantum.Canon.ConjugatedByC)
- [Microsoft.Quantum.Canon.ConjugatedByCA](xref:Microsoft.Quantum.Canon.ConjugatedByCA)
- [Microsoft.Quantum.Canon.ApplyWith](xref:Microsoft.Quantum.Canon.ApplyWith)