### VerifyMultiPortMem
GSTE model checking on multiport memories using FORTE

#### Three kinds of multiport memories
- LVT
- XOR
- I-LVT
verifications of them are sited in corresponding folders.

#### Files Descriptions
- *.blif: netlist model of memory in Berkeley Logic Interchange Format
- *.exlif: netlist model of memory in Extended Logic Interchange Format
- *.exe.gz: input model for FORTE system
- *mem.fl: verification FL script
- yosysBlif2Exlif.py: python script for translating blif format into exlif format
- gsteSymReduce.fl: trajectory evaluation theory definition

