# QubitDuino
Spooky Manufacturing's single qubit quantum arduino shield

# What is the QubitDuino?
The QubitDuino is a single qubit optical quantum processor built on top of the arduino platform. With it you are able to perform quantum computations on a single qubit.

# Principles of Operation
 1. The qubit consists of a laser pulse containing millions of photons, the qubit can be placed into a 1 or a 0 bit state or into any quantum superposition in between.
 2. The QubitDuino is programmed using a modified version of OpenQASM.
 3. The QubitDuino connects via a serial connection to the arduino.
 4. Qubits are collapsed and measured after every logic gate, their state being copied to a new qubit for computational purposes.
 
# Where can I get one and how much do they cost?
We are still in the prototyping stage, however you can expect to spend less than $500 on the QubitDuino.

# Durability
The QubitDuino contains moving parts and while we do our best to design and manufacture them you should treat them like you would a hard disk drive, don't hit it with a hammer, don't toss it around, and don't stick it in the microwave.

# Gates
The QubitDuino has 6 gates:
 - Pauli-X Gate
 - Pauli-Y Gate
 - Pauli-Z Gate
 - Hadamard Gate
 - User defined X & Y Rotation Gates

*Note* The X & Y rotation gates are mathematically calculated and applied during the qubit generation process, the accuracy of the actual rotation applied has a mathematical limit of 1°, as with all applied physics there will be some degree of error, however we do not anticipate this to be an issue for most users or the degree of error to be larger than +-5%

