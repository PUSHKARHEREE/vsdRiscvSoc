
# Task 1: Install & Sanity-Check the RISC-V Toolchain

## 1. Extract the Toolchain

```bash
 tar -xvzf ~/riscv_project/riscv-toolchain-rv32imac-x86_64-ubuntu.tar.gz -C ~/riscv_project
```
## 2. Add the Toolchain to PATH
   ```bash
   echo 'export PATH=$PATH:$HOME/Downloads/opt/riscv/bin' >> ~/.bashrc
   ```
   Then apply the change:
   ```bash
   source ~/.bashrc
   ```
## 3. Verify the Installation
   ```bash
   riscv32-unknown-elf-gcc --version
   riscv32-unknown-linux-gnu-gcc --version
```

## OUTPUT:

```bash
riscv32-unknown-elf-gcc (g04696df096) 14.2.0
Copyright (C) 2024 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

riscv32-unknown-linux-gnu-gcc (GCC) 14.2.0
Copyright (C) 2024 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
```
