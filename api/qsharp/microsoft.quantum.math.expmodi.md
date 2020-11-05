---
uid: Microsoft.Quantum.Math.ExpModI
title: ExpModI function
ms.date: 11/5/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Math
qsharp.name: ExpModI
qsharp.summary: >-
  Returns an integer raised to a given power, with respect to a given
  modulus.
---

# ExpModI function

Namespace: [Microsoft.Quantum.Math](xref:Microsoft.Quantum.Math)

Package: [](https://nuget.org/packages/)


Returns an integer raised to a given power, with respect to a given

```qsharp
function ExpModI (expBase : Int, power : Int, modulus : Int) : Int
```


## Description

Let us denote expBase by $x$, power by $p$ and modulus by $N$.

## Input

### expBase : [Int](xref:microsoft.quantum.lang-ref.int)




### power : [Int](xref:microsoft.quantum.lang-ref.int)




### modulus : [Int](xref:microsoft.quantum.lang-ref.int)





## Output : [Int](xref:microsoft.quantum.lang-ref.int)



## Remarks

Takes time proportional to the number of bits in `power`, not the `power` itself.