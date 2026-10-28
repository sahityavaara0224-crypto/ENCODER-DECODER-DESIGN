# ENCODER-DECODER-DESIGN
# Encoder and Decoder Design Using Logisim Evolution

## Project Overview

This project demonstrates the design and simulation of a 4-to-2
binary encoder and a 2-to-4 binary decoder using Logisim Evolution.

The encoder converts one active input line into a two-bit binary code.
The decoder converts a two-bit binary input into one active output line.

## Objectives

- Understand encoder and decoder circuits.
- Implement Boolean expressions using logic gates.
- Design combinational circuits in Logisim Evolution.
- Verify circuit outputs using truth tables.

## Tools Used

- Logisim Evolution
- Git
- GitHub

## Circuits Implemented

### 4-to-2 Encoder

Inputs: D0, D1, D2, D3

Outputs: Y1, Y0

Boolean expressions:

Y1 = D2 OR D3

Y0 = D1 OR D3

Assumption: Exactly one input is HIGH at a time.

### 2-to-4 Decoder

Inputs: A1, A0

Outputs: D0, D1, D2, D3

Boolean expressions:

D0 = NOT A1 AND NOT A0

D1 = NOT A1 AND A0

D2 = A1 AND NOT A0

D3 = A1 AND A0

## Testing

Both circuits are tested with all valid input combinations.
Observed outputs are compared with the expected truth tables.

## Applications

- Digital communication systems
- Address decoding
- Data routing
- Control systems
- Digital electronics

sahitya

Sahitya

Third-Year B.Tech – Electronics and Communication Engineering
