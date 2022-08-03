# Instructions for Quanta Student Symposium Workshop

You are not expected to be an expert. The purpose is to provide an opportunity to play with quantum circuits.
These labs will be easier to those with more Python experience.

:warning: Disclaimer: The Quanta Symposium organizers didn't write these labs and exercises. We are not responsible for the typos and inconsistencies you might notice.

:warning: Warnings:
* Some of the pre-written functions may be deprecated. In that case, you will have to find the correct functions to replace these with.
* If your lab page is inactive for too long, the kernel will die and you will have to refresh the page.
* If you refresh the page, all previously entered code will be lost.

:heavy_check_mark: Tips for when you get stuck:
* For testing out circuit configurations, try using the [drag-and drop Quirk simulator](https://algassert.com/quirk)
* Sometimes the "Scratchpad" sidebar is helpful for debugging code.
* Google is your friend. External resources such as StackExchange can be instructive.
* It may be helpful to review some of the Prerequisite and Other Relevant Material at the beginning of each lab.
* There are also links throughout the labs to relevant portions of the Qiskit textbook. 
* Sometimes it's helpful to draw out the quantum circuit, i.e. `qc.draw()`.
* A `QuantumCircuit` object can contain both quantum and classical channels. Calling `qc = QuantumCircuit(2, 1)` will create a circuit with 2 quantum channels and one classical channel.

* The Qiskit documentation pages on particular functions can be helpful.


[Here's a document](https://raw.githubusercontent.com/qiskit-community/qiskit-textbook/main/content/ch-states/supplements/single-gates-cheatsheet.pdf) listing many different single qubit quantum gates as they appear in Qiskit.

We recognize that we have participants with *widely* varying levels of experience and familiarity in quantum computing.
For that reason, this workshop is intended to be hands-on and practical.
Instruction will be very minimal; participants will be required to study and seek out answers with their assigned partner. I am willing to help as a resource, but my abilities will be limited with such a large group. I've provided tips and suggestions for when you get stuck. When 30 minutes remain, I will update the website with my pages of solutions that I compiled while working through these labs myself.

The purpose of these challenges is to provide a venue for us to learn and explore. Maybe we know about these concepts, and we know that there are companies and tools to use, but we might not have set aside time to really engage with them. We should acknowlege that we are all learning here. This should be a safe place to “Take chances, make mistakes, and get messy!” Raise your hand if you agree with this!

(* Take a picture of the group seated in the computer lab *)

There are lots of different platforms for designing quantum circuits. Qiskitis just one of them. The reason we have chosen to work with this ons is because of the availability and accessibliity of IBM's online interactive textbook. For individuals who are new to this, it gets them off the ground faster; for those with more experience, this provides them an easy opportunity to explore the functionality.

Preliminary instruction:
* State space of a qubit
* Setting up a quantum cicuit
  * The difference between classical and quantum channels
* Registering with IBM Quantum Experience

By the end of this session, participants will be able to:
* Identify the Qiskit Textbook as one resource for personal learning of quantum computing.
* Construct and execute a quantum circuit using Qiskit. 
* Recognize various single- and multi-qubit gates and predict their effects on a qubit's state.


<table>
<thead>
  <tr>
    <th>Raffle Level</th>
    <th>Lab Name</th>
    <th>Description</th>
    <th>Est. Completion Time</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Level 1</td>
    <td>Lab 2: Single Qubit Gates</td>
    <td>Explore the effects of gates on a qubit's state.</td>
    <td>20 min</td>
  </tr>
  <tr>
    <td>Level 2</td>
    <td>Lab 1: Quantum Circuits</td>
    <td>Contruct classical logic circuits using quantum gates. Test on a real quantum computer.</td>
    <td>30-40 min</td>
  </tr>
  <tr>
    <td>Level 3</td>
    <td>Lab 3: Quantum Measurements, OR <br> Lab 4: Bell Circuit & GHZ Circuit</td>
    <td>Compute expectation values in the computational basis. Calculate hydrogen hyperfine energy. Execute on a quantum computer.</td>
    <td>60-90 minutes</td>
  </tr>
</tbody>
</table>