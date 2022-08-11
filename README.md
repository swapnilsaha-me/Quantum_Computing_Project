# Quantum_Computing_Project
This repository will contain the source code for our quantum computing project.


## Overview
We aim to detect eavesdropping in a quantum communication channel using
BB84 protocol [1] for secure message exchange. The basic idea is that the state
of a qubit changes its state with any measurement on it, and this change can be
detected. As an instance, say a message sender A wants to transmit a message
to receiver B using the quantum communication channel provided by C. Now, if
A sends a qubit to B, we want to make sure that C cannot intercept the state of
the qubit. We do this by making use of a fundamental property of qubits which
is- The state of a qubit changes, if someone measures that qubit. We detect this
change in states, and thus make the channel secure for message transmission.

<figure>
    <p align="center"><img alt="An example of eavesdropping" align="middle" width="350" src="http://gva.noekeon.org/QCandSKD/Figures/AliceBobEve.png"/></p>
    <figcaption><p align="center">Figure: An example</p></figcaption>
</figure>
