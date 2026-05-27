### Important Topics - Frequently Repeated topics for Interviews

#### Device & Logic Design
* **Second-Order Effects:** CLM, DIBL, and Velocity Saturation.
* **CMOS VTC:** Drawing and labeling all regions of the Inverter transfer curve.
* **MOSFET Sizing:** Why PMOS is wider than NMOS (Mobility ratio).
* **Pass Transistor Logic (PTL):** Implementation and its specific advantages/limitations.
* **Logic Realization:** Designing XOR using only NAND gates; designing gates using MUX.
* **Resistor Approximation:** When to treat a MOSFET as a resistor (Linear region).

#### Timing & Digital
* **Setup & Hold Time:** Calculating violations and fix techniques.
* **Metastability:** Cause, effect and synchronizer solutions.
* **Frequency Dividers:** Designing "Divide by N" circuits.
* **Latch vs. Flip-Flop:** Structural differences and "when to use which."
* **Clock Skew:** Its specific impact on maximum operating frequency (Fmax)
* **FIFO:** Basic operation and depth calculation.

#### Circuit Analysis (Intuitive)
* **RC/RL Transients:** Drawing Vout waveforms without Laplace transforms.
* <span style="color:red">**Two-Capacitor Circuits:** Charge sharing and behavior when shorted.</span>
* **HPF Negative Spikes:** Why they occur with square wave inputs.
* <span style="color:red">**Effective Time Constant:** Calculating τ for circuits with multiple R and C elements</span>

#### Verilog & CAM
* **Blocking vs. Non-blocking:** = vs <= (Combinational vs. Sequential logic rules).
* **Race Conditions:** How they occur in Verilog and how to prevent them.
* **Reg vs. Wire:** Synthesis differences and proper use cases.
* **Pipeline Hazards:** Identifying and resolving Data, Control, and Structural hazards.
* **Cache Performance:** Calculating Hit Ratio and average access time.

#### Analog & Filters
* **Barkhausen Criterion:** Conditions for stable oscillation.
* **Virtual Ground/Short:** Conditions where these assumptions are valid vs. invalid.
* **Feedback Identification:** Identifying positive vs. negative feedback loops.
* **Amplifier Impedances:** Calculating Rin and Rout for CS, CG, and CD stages.
