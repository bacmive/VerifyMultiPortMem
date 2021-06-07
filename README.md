### VerifyMultiPortMem
GSTE model checking on multiport memories using FORTE

#### Three kinds of multiport memories
- LVT
- XOR
- I-LVT

#### single port write and read verfication
sited in corresponding directories `lvt/, xor/, i-lvt/`

##### Files Descriptions
- *.blif: netlist model of memory in Berkeley Logic Interchange Format
- *.exlif: netlist model of memory in Extended Logic Interchange Format
- *.exe.gz: input model for FORTE system
- *mem.fl: verification FL scripts
- yosysBlif2Exlif.py: python script for translating blif format into exlif format
- gsteSymReduce.fl: trajectory evaluation theory definition

#### multiport write and read (synchronously) verification
sited in corresponding directories `m-lvt/, m-xor/, m-ilvt`

##### Files Descriptions
- *.blif: netlist model of memory in Berkeley Logic Interchange Format
- *.exlif: netlist model of memory in Extended Logic Interchange Format
- *.exe.gz: input model for FORTE system
- lvt.fl/xor.fl/ilvt.fl : verification FL scripts
- trajEval.fl: trajectory evaluation logic definition
- tools.fl: mathematical/bexpression-related tools
- yosysBlif2Exlif.py: python script for translating blif format into exlif format

