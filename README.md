# Real-Time-RCP-qPCR-Pipeline
Auto-analysis for Real-Time RCP (qPCR) data

* [Dependencies](#Dependencies)
* [INPUT](#INPUT)
* [USAGE](#USAGE)
* [OUTPUT](#OUTPUT)
## 1. Dependencies
- python
  - collections
  - itertools
  - csv
  - pandas
  - numpy
  - sys
- R
  - ggplot2
  - gridExtra
  - ggthemes
  - ggsci
  - reshape2
  - dplyr
## 2. INPUT
## 3. USAGE
```
./qPCR.sh A B C D E
Argument:
- A: absolute path of Input data (e, /public/home/hope/qPCR)
- B: Input Data (e, raw_input_qPCR.csv)
- C: Width of output pdf file
- D: Height of output pdf file
- E: Whether plot a scientific journals figure using the ggsci packages (yes or no)
```
Running on the example data
```
./qPCR.sh /public/home/hope/qPCR raw_input_qPCR.csv 18 8 no
```

## 4. OUTPUT
