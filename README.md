# tests
Write valid input files for the NFA and DFA modules that you implemented.
Respect the folder structure provided in the templte. Write 3 DFA config files and 3 NFA confing files.

For every config file, write 5 tests that should be accepted and 5 tests that should be rejected. 
One test for NFA and one for DFA should be the following: 
A one config file for an automaton that accepts time  specifications. All  of  the  following examples should be accepted:
- 4 p m
- 7 : 3 8 p m
- 2 3 : 4 2
- 3 : 1 6 
- 3 : 1 6 a m


How your prgrams will be run:
dfa.py automaton.cfg w1 w2 w3 w4 w5 `(w1 w2 w3 w4 w5 are from string_{no_test})`
nfa.py automaton.cfg implementation_1 w1 w2 w3 w4 w5

Modify your current programs to output `accept(ed)` for accepted strings, `reject(ed)` for rejected strings, and `invalid` for invalid config files
