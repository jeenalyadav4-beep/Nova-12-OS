# Nova 12 OS 🌌

Nova 12 OS is a fully independent, bare-metal x86-64 long-mode operating system built using pure Python file manipulation automation. Because it implements its own multi-module execution toolchain, it initializes directly on the CPU level, bypassing all standard Windows 10 or Windows 11 system controls.

## ⚙️ Core Architecture Features
- **64-Bit Multi-Stage Paging:** The builder directly configures x86 PAE (Physical Address Extension) page table blocks to shift processing registers out of legacy modes.
- **Embedded Font Typography:** Features a robust 8x8 font bitmap mapping grid for advanced visual console output layout rendering.
- **Low-Level Scancode Translators:** Integrates full hardware port scancode translator indexing maps to translate keyboard interrupts into terminal strings.

## 🛠️ Local Construction & Deployment
To safely build and run Nova 12 OS on your machine without third-party compiler downloads, follow these instructions:

1. Download or clone the **`generate_nova12.py`** script file from this repository.
2. Open your terminal or Command Prompt and run the master Python compiler:
   ```bash
   python generate_nova12.py
   ```
3. The engine will instantly assemble the raw byte registers, fill out the padding parameters, and output a deployment file named `nova12_ultimate.img`.
4. Open **AnyBurn**, select **Create Bootable Image File from Files / Folders**, target your workspace folder containing the image file, set the volume label to `NOVA12OS`, and compile your final `Nova12OS.iso` output tracking file.
5. Load the output `.iso` file into any system hypervisor or emulator (such as VirtualBox or QEMU) as a primary bootable optical disk drive to experience the independent, velvet-indigo text shell!


