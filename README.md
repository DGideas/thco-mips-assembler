# thco-mips-assembler
清华大学 THCO-MIPS指令集汇编器

# Usage

```bash
g++ msm.cpp -o msm --std=c++11
echo nop > 1.mips
./msm 1.mips out.bin
hexdump -C out.bin
```
