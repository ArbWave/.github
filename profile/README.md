<div align="center">

# ArbWave

**Open-source instrumentation · 开源仪器**

*Instruments you can open, read, modify and rebuild.*
*可以拆开、看懂、修改、重做的仪器。*

</div>

---

Most instruments are closed boxes. ArbWave publishes the schematics, the PCB
source, the FPGA and MCU firmware, the SCPI command set and the measured
results — so the design can be studied, not just used.

大多数仪器是黑盒。ArbWave 把原理图、PCB 源文件、FPGA 与 MCU 固件、SCPI
命令集和实测数据一起公开，让设计可以被看懂，而不只是被使用。

## Projects

| Project | Description | Status |
|---|---|---|
| **[ArbWave30](https://github.com/EERNINUO/ArbWave30)** | 30 MHz arbitrary waveform generator · FPGA + 150 MSPS DAC · SCPI over USB | MVP built and running · first release Dec 2026 |

## Naming

`ArbWave` is the family name. The number is the sine-wave bandwidth in MHz —
`ArbWave30` today; `45` and `60` are planned, as are other instrument types.

`ArbWave` 是系列名，数字代表正弦波带宽（MHz）。目前是 `ArbWave30`，
未来会有 `45` / `60`，以及其他类型的仪器。

## Links

- **Code & issues** — [EERNINUO/ArbWave30](https://github.com/EERNINUO/ArbWave30)
- **Documentation** — [docs/](https://github.com/EERNINUO/ArbWave30/tree/develop/docs)
- **Design decisions (ADR)** — [docs/adr/](https://github.com/EERNINUO/ArbWave30/tree/develop/docs/adr)
- **Build notes & measurements** — [docs/调试笔记/](https://github.com/EERNINUO/ArbWave30/tree/develop/docs/调试笔记)

## Status

This organization is new (November 2026) and is run by one person — expect
small, careful, slow releases. The flagship repository currently lives under
[@EERNINUO](https://github.com/EERNINUO) and will move here when there is a
reason to. Development resumes in late December 2026.

本组织成立于 2026 年 11 月，目前由一个人维护，所以更新慢但会尽量做扎实。
主仓库暂时仍在 [@EERNINUO](https://github.com/EERNINUO) 名下，等有需要时再迁移。
2026 年 12 月下旬恢复开发。

## Licenses

Firmware `GPL-3.0` · Hardware `CERN-OHL-S-2.0` · Documentation `CC-BY-SA-4.0`

---

**Found a problem or want to help?** Open an issue on the project above —
feedback from people who actually build things is what makes this better.
