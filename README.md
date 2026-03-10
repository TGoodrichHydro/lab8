# Multiplexers and Demultiplexers

In this lab you have learned about multiplexers and demultiplexers.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Names

Oleg Strekachev
Travis Goodrich

## Summary

We build an implementation of the Mux - Demux circuit passing 4 bit data chunks from 4 different recepients based on combination of pressed mux selector buttons, and then assigning output of the mux to 4 different recipients based on combination of pressed demux selector buttons.

## Lab Questions

### In plain English describe the function and use of a multiplexer.

Multiplexer allows to select 1 output out of multiple inputs based on the selector bits.

### In plain English describe the function and use of a demultiplexer.

Inverse of multiplexer - allows to assign input to one of multiple outputs based on the selector bits

### What other uses might these circuits have? (Think Shannon’s)

Computer Memory 

Multiplexers are utilized in computer memory to select specific memory locations and to reduce the number of physical copper connections needed between components.

Data conversion 

Mux circuits are used to convert multiple parallel data streams into a single serial data stream, reducing the number of communication lines required. Conversely, demultiplexers are used to convert serialized data back into parallel format.

Logic Function Generator 

A Mux can implement Boolean functions (like full adders or subtractors) in digital circuits by acting as a universal, programmable logic gate, enabling flexible design changes.

