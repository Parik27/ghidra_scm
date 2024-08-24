# Ghidra SCM

![image](https://github.com/user-attachments/assets/72e94865-c562-4a71-97cb-1700c710fc26)

- Decompiles and Disassembles SCM files
- Recovers loops, conditions, whatnot.

## Limitations

- VCS only (for now)
- No analysers yet so you have to manually tell Ghidra to disassemble the main function and any mission
- Does not support string arguments properly (shows up only in disassembly, not in decompilation)
- Does not support call return arguments.
- Not renamed from YSC
- Opcode parameters in decompilation are all considered integers. You can set their type manually in the decompiler.

## Usage

- Paste data folder in a folder inside Ghidra/Processors
- Open main.scm as raw binary and select scm/ysc in the processor/language option.
