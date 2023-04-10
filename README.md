# BSc_thesis: Efficiently representing radio astronomy data into qubits

Is Quantum Computing viable for radio astronomy?

## Research questions
- Considering that naive representation of radio astronomy data is wasteful in qubits, what is a more efficient  way to represent such data in a quantum computer?
- How to efficiently turn radio telscope's visibility data into astronomical images?

## Learning materials

### Books and tutorials

- [QisKit textbook](https://qiskit.org/textbook/preface.html)
- [PennyLane demos](https://pennylane.ai/qml/demos_getting-started.html)
- [Loading Classical Data into a Quantum Computer](https://arxiv.org/abs/1803.01958)
- [Data re-uploading for a universal quantum classifier](https://arxiv.org/abs/1907.02085)
- [Data re-uploading tutorial](https://github.com/NLESC-quantum/quantum_comp/tree/main/pulsar_search/ml/reupload)
- [QFT tutorial - Qiskit](https://qiskit.org/textbook/ch-algorithms/quantum-fourier-transform.html#3.-Example-1:-1-qubit-QFT-)
- [MeasurementSet description for LOFAR](file:///C:/Users/roman/OneDrive/Bureau/UM/BSc/TH/Visibitlity_data_format/LOFAR.pdf)
- [SDP to CSP Mid Interface Control Document](file:///C:/Users/roman/OneDrive/Bureau/UM/BSc/TH/Visibitlity_data_format/SKA.pdf)

### Publications
- Commodity compute and data-transport system design in modern large-scale distributed radio telescopes. [Chris Broekema's PhD thesis](https://www.astron.nl/~broekema/Thesis/PhD-Thesis.pdf)
- Efficiently representing radio astronomy data in qbit. [Roman Ilic's BSc thesis](https://fr.overleaf.com/project/63f27501db619ad658e44c56)

### Tools
- [QisKit](https://qiskit.org/)
- [Pennylane](https://pennylane.ai/)

### Tips
In order to use bra-ket notation in Jupyter notebooks, include the snippet below in a markdown cell:

```markdown
$$
\renewcommand{\braket}[2]{\left\langle{#1}\middle|{#2}\right\rangle}
\renewcommand{\ket}[1]{\left|{#1}\right\rangle}
\renewcommand{\bra}[1]{\left\langle{#1}\right|}
$$
```

it will render to whitespace, but it will allow to use the latex commands `\bra{q}`, `\ket{q}` and `\braket{q, p}`.
