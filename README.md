# qamp_22_db_eval
Some recent simulations related to QEC, for QAMP application

File description: 
- `3qubit_code_qamp.ipynb`: Program to simulate pseudo-threshold of 3-qubit repetition code under i.i.d. bit flip noise on data qubits and using a naive lookup-table syndrome decoder.
- `five_qubit_code_error_analysis_full_code_capacity_qamp.ipynb`: Program to perform error analysis of [5,1,3] code. This program will calculate the theoretically expected asymptotic scaling of logical error rate with physical error rate, by computing which error patterns along with the naive correction leads to a non-trivial operation on the codespace, i.e. a logical error.
