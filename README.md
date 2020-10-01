# Contract Compilation Review
 Contract Compilation Review

Pointers:
- JSON_Unflattened and SOL Compilation are the same set of .sol files; One consolidated to be in standard_json format, the other compiled individual by calling solc.exe targetting Dexe.sol.
- Each directory contains the source files used for compilation, as well as their compilation output + metadata.
- The solc version used is 0.7.0, with a copy found under \solc folder (can be replaced with the executable downloaded off the solc repo :))

A diff between the Dexe.sol output:
![Diff](https://pictr.com/images/2020/10/01/7VRUCQ.png)
