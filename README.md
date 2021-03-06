# GeST

GeST (Generating Stress-Tests) is a framework for automatic hardware stress-test generation.

A scientific paper about GeST is published in ISPASS 2019 https://ieeexplore.ieee.org/document/8695639 

Hadjilambrou, Z., Das, S., Whatmough, P.N., Bull, D. and Sazeides, Y., 2019, April. GeST: An Automatic Framework For Generating CPU Stress-Tests. In 2019 IEEE International Symposium on Performance Analysis of Systems and Software (ISPASS) (pp. 1-10). IEEE.



## Prerequisites

- On host machine

```bash
pip3 install paramiko
pip3 install visa
```

- On target machine
  - install likwid
  - sudo modprobe msr

## Usage
1. copy assembly_compilation_<arch> to compile dir(/tmp/GeST)
2. Run command
```bash
python3 ./src/__init.py <configure.xml>
```

Some configuraiton file example are placed in dir configurationFiles.

