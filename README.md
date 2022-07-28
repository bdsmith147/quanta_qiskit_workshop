# Instructions for Quanta Student Symposium Workshop

You are not expected to be an expert. The purpose is to provide an opportunity to play with quantum circuits.
These labs will be easier to those with more Python experience.

Disclaimer: The Quanta Symposium organizers didn't write these labs and exercises. You may notice several typos and inconsistencies.

Warnings:
* Some of the pre-written functions may be deprecated. In that case, you will have to find the correct functions to replace these with.
* If your lab page is inactive for too long, the kernel will die and you will have to refresh the page.
* If you refresh the page, all previously entered code will be lost.

Tips for when you get stuck:
* For testing out circuit configurations, try using the [drag-and drop Quirk simulator](https://algassert.com/quirk)
* Sometimes the "Scratchpad" sidebar is helpful for debugging code.
* Google is your friend. External resources such as StackExchange can be instructive.
* It may be helpful to review some of the Prerequisite and Other Relevant Material at the beginning of each lab.
* There are also links throughout the labs to relevant portions of the Qiskit textbook. 
* Sometimes it's helpful to draw out the quantum circuit, i.e. `qc.draw()`.
* A `QuantumCircuit` object can contain both quantum and classical channels. Calling `qc = QuantumCircuit(2, 1)` will create a circuit with 2 quantum channels and one classical channel.

* The Qiskit documentation pages on particular functions can be helpful.


[Here's a document](https://raw.githubusercontent.com/qiskit-community/qiskit-textbook/main/content/ch-states/supplements/single-gates-cheatsheet.pdf) listing many different single qubit quantum gates as they appear in Qiskit.
