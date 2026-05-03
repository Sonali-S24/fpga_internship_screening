# FPGA_Internship_Screening
Verilog implementation and simulation of multiplexer designs using Yosys, Icarus Verilog, and GTKWave with waveform analysis.

## 📌 Overview
This repository contains the Verilog implementation and simulation of multiplexer (MUX) designs as part of FPGA RTL design and synthesis learning. The design is simulated using Icarus Verilog and visualized using GTKWave.

---

## 🎯 Objectives
- Design a multiplexer using Verilog HDL
- Simulate the design using Icarus Verilog
- Analyze waveforms using GTKWave
- Understand RTL design and logic synthesis using Yosys

---


## 🧠 Tools Used
- Icarus Verilog (iverilog)
- GTKWave
- Yosys

---

# 📦 MODULE 1: MULTIPLEXER (MUX)

## 📜 Verilog Files
- `good_mux.v` – RTL design of multiplexer
- `tb_good_mux.v` – Testbench for simulation

## 📊 Simulation Output

![MUX Waveform](lab2_good_mux.png)

## 🔧 Synthesis Output

![MUX Yosys](good_mux.yosys_show.png)

---

# 📦 MODULE 2: D FLIP-FLOPS

## 🔹 1. DFF with Asynchronous SET

### 📊 GTKWave Outputs
![Async Set Waveform](dff_async_set_gtkwave.png)

![Reset 0 to 1](dff_async_set_reset0to1_zoomed.png)

![Reset 1 to 0](dff_async_set_reset1to0_zoomed.png)

### 🔧 Yosys Output
![Async Set Synthesis](dff_async_set.yosys_show.png)

---

## 🔹 2. DFF with Asynchronous RESET

### 📊 GTKWave Outputs
![Async Reset Waveform](dff_asyncres_gtkwave_zoomed_in.png)

![Async Reset Zoom](dff_asyncres_gtkwave_reset_zoomed.png)

### 🔧 Yosys Output
![Async Reset Synthesis](dff_asyncres.yosys_show.png)

---

## 🔹 3. DFF with Synchronous RESET

### 📊 GTKWave Outputs
![Sync Reset Waveform](dff_syncres_gtkwave.png)

![Sync Reset Zoom](dff_syncres_zoomed.png)

### 🔧 Yosys Output
![Sync Reset Synthesis](dff_syncres.yosys_show.png)

---

## 4: MULTIPLIERS

## 📜 Verilog Files
- `mult_2.v` – 2-bit multiplier
- `mult_8.v` – 8-bit multiplier
- `mul2_net.v`, `mult8_net.v` – synthesized netlists

## 📊 Simulation Outputs

![2-bit Multiplier](mul2_show.png)

![8-bit Multiplier](mult_8_show.png)

## 🔧 Synthesis Outputs

![2-bit Yosys](mul2.yosys_show.png)

![8-bit Yosys](mult_8.yosys_show.png)

---

## 5: MULTIPLE MODULES (HIERARCHY vs FLAT)

## 📜 Verilog Files
- `multiple_modules_heir.v` – hierarchical design
- `multiple_modules_flat.v` – flattened design

## 📊 Outputs

![Hierarchical Output](multiple_modules_l3.png)

![Flat Output](multiple_modules_flat_l3.png)

## 🔧 Synthesis

![Hierarchical Yosys](multiple_modules.yosys_show.png)

![Flat Yosys](multiple_modules_flat.yosys_show.png)

---

## 6: SUB MODULE

## 📊 Outputs

![Submodule Output](sub_module_1_l3.png)

## 🔧 Synthesis

![Submodule Yosys](sub_module_1.yosys_show.png)

---


