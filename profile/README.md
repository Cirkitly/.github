# Cirkitly

> **AI-Accelerated Hardware Design Tools** — From spec to silicon in seconds.

Cirkitly is a modular open-source stack of intelligent agents and tools that reimagines the way digital hardware is designed. We use AI to radically simplify chip and accelerator development — from natural language specs to synthesizable RTL, optimized CUDA/HLS kernels, and layout-ready netlists.

Whether you're a student, FPGA developer, or silicon architect — **Cirkitly accelerates the hardware workflow** with clarity, automation, and AI augmentation.

---

## What Can Cirkitly Do?

| Tool          | Description                                                                |
|---------------|----------------------------------------------------------------------------|
| `spec2rtl`     | Convert structured specs → RTL + testbench + sim script                 |
| `rtl-copilot`  | Prompt-based Verilog generator & smart FSM editor                       |
| `picoplace`    | Lightweight placer-router with AI hints and SVG layout visualizer       |
| `cuda-genie`    | AI compiler that converts C/Python → optimized CUDA/HLS kernels         |
| `silicon-agent` | Integration orchestrator that runs spec → RTL → sim → layout → report   |

---

## Why Cirkitly?

Hardware development is traditionally:
- Slow
- Manual
- Fragmented
- Opaque

**Cirkitly fixes that** by introducing intelligent automation and an end-to-end AI-first stack, giving you:

✅ Rapid prototyping  
✅ Seamless integration  
✅ Natural language interfaces  
✅ Powerful abstractions

---

## Tech Stack

- **Languages**: Python, Verilog, CUDA, JavaScript  
- **Tooling**: Yosys, Verilator, Graphviz, LLVM, Magic VLSI  
- **AI Models**: GPT-4, custom prompt engineering, agent routing  
- **Frontend**: React (Monaco), Tailwind, FastAPI  
- **Simulation**: Verilator, GTKWave, cocotb (planned)

---

## Projects Inside

- [`spec2rtl`](https://github.com/Cirkitly/spec2rtl) – spec → RTL + TB  
- [`rtl-copilot`](https://github.com/Cirkitly/rtl-copilot) – LLM-powered Verilog authoring  
- [`picoplace`](https://github.com/Cirkitly/picoplace) – AI-assisted placement & routing  
- [`cuda-genie`](https://github.com/Cirkitly/cuda-genie) – CUDA/HLS kernel generation  
- [`silicon-agent`](https://github.com/Cirkitly/silicon-agent) – full flow orchestrator

> Each repo is modular, open, and can be used independently or as part of the full stack.

---

## Demo Projects

| Project         | Spec Type | Tools Used                          | Output                     |
|-----------------|-----------|-------------------------------------|----------------------------|
| UART Controller | YAML      | `spec2rtl`, `rtl-copilot`           | Verilog + Testbench + VCD |
| Pipelined ALU   | Prompt    | `rtl-copilot`, `picoplace`          | SVG layout + sim          |
| Matrix Mult     | Python    | `cuda-genie`, `silicon-agent`       | CUDA kernel + perf notes  |

Demos are coming soon to [Binary Mavericks YouTube](https://www.youtube.com/@BinaryMavericks)!

---

## How to Get Started

```bash
git clone https://github.com/Cirkitly/spec2rtl.git
cd spec2rtl
pip install -r requirements.txt
python cli.py --generate examples/uart.yaml
````

Or try the full stack orchestration via `silicon-agent` (coming soon).

---

## Contributing

We’re looking for contributors passionate about:

* EDA, FPGAs, or compilers
* LLMs and AI agents for engineering tools
* Hardware-software co-design

Open issues, suggest tools, or contribute to one of the core repos!

---

## Maintained by

* Utkarsh Maurya ([@binarymavericks](https://github.com/pro-utkarshM))
* The open-source hardware community 🚀

---

## License

MIT for core agents.
Some tools (e.g., yosys, verilator) follow their own licenses.

---

## Website

Coming soon: [https://cirkitly.dev](https://cirkitly.dev)

---
> *"Hardware should be as easy to write and debug as software — Cirkitly makes that real."*
