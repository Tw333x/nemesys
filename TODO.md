Verilog
-------

- [x] predicates
- [x] comparisons
- [x] conditional branches
- [x] "small immediate" encodings
- [x] halting
- [x] comparisons w/ immediates
- [ ] reversible immediates: can't currently rA >= #imm, as #imm is always 'B'
- [ ] add/sub with carry
- [ ] mov immediate hi/lo 16-bits
- [x] branch when predicate false
- [x] link register
- [x] call/return instructions
- [ ] memory instructions
- [ ] select instructions
- [ ] remove hard-coded numbers; be as generic as possible

Misc
----

- [x] put testbenches into own directory

Software
--------

- [ ] simple LLVM TableGen description files
- [ ] assembly parser/printer
- [ ] object emitter
- [ ] simulator
