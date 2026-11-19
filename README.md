# Object-Oriented Python Study Notebook

`OPS.ipynb` contains 49 code cells mixing written answers, string-wrapped code sketches, executable class definitions and a final empty cell. It covers initialization, inheritance, overriding, abstract classes, encapsulation, properties and small object-model exercises.

## Read and run

Open the notebook with Jupyter or a notebook-capable editor using Python 3. Executable snippets use built-in Python and the standard-library `abc` module. Many apparent code samples are actually string literals: running them displays notes rather than defining a class.

Class names such as `Person`, `Student`, `Car` and `BankAccount` are reused. Treat sections as separate examples, not a cohesive package or reusable financial application.

## Known limits

A fresh sequential review reaches `NameError` in cell 20 (one-based): `ChildClass` refers to an undefined `ParentClass`. Later examples must be read independently or run after deliberately addressing missing prerequisites. This README does not silently supply that parent class.

Notes and sketches are learning material, not a certified technical reference or security implementation. Python attribute conventions and name mangling should not be treated as secret storage or an authorization boundary. No full behavioral test suite or production-readiness claim is made.

This update adds documentation only. Original cells, saved outputs, exercises, names and history are preserved.
