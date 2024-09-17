
# QuantaScript Examples

## 1. Hello Quantum World
```quantaScript
// © Reece Dixon, 2024 - QuantaScript Language
qubit q1 = |0⟩;
q1.apply(H);
result = measure(q1);
print("Measured state: ", result);
```

This simple example demonstrates a qubit in superposition, measured to collapse to either 0 or 1.

© 2024 Reece Dixon. All rights reserved.
