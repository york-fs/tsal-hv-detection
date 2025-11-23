# TSAL HV Detection Board

![Revision](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fyork-fs.github.io%2Ftsal-hv-detection%2Finfo.json&query=%24.revision&label=Revision)
![Pad Count](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fyork-fs.github.io%2Ftsal-hv-detection%2Finfo.json&query=%24.pad_count&label=Pad%20Count)
![Via Count](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fyork-fs.github.io%2Ftsal-hv-detection%2Finfo.json&query=%24.via_count&label=Via%20Count)
![ERC Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fyork-fs.github.io%2Ftsal-hv-detection%2Ferc.json)
![DRC Status](https://img.shields.io/endpoint?url=https%3A%2F%2Fyork-fs.github.io%2Ftsal-hv-detection%2Fdrc.json)

Detects if >60 V is present between TS+ and TS- and outputs a 5 V signal (inverted logic for SCS rule compliance).

## Cloning

A recursive clone must be used to download the `kicad-library` repository:

    git clone --recursive https://github.com/york-fs/tsal-hv-detection.git

<img width="1920" height="1080" alt="TSAL_HV" src="https://github.com/user-attachments/assets/f0437d08-d7fa-4fc5-82d6-030e6278b5c3" />


