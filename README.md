This is the readme for the model associated with the paper:

N. Vladimirov, Y. Tu, R.D. Traub. Synaptic gating at axonal branches, and sharp-wave ripples with replay: a simulation study. *EJN*

This model was contributed by Dr. Nikita Vladimirov. These simulations require NEURON which is freely available from [http://www.neuron.yale.edu](http://www.neuron.yale.edu)

## Usage:

1) Run mknrndll module of NEURON in the folder you have unpacked. It will create dlls of mod files, necessary for NEURON execution.

2) Run one of the top-level NEURON files by clicking Init & Run after starting one of the below with a command like:

```
nrngui mosinit_1PC_1IN.hoc
```

Auto-launch from ModelDB runs the above if your browser is configured properly and you press the auto-launch button in the showmodel page. Some graphs that were created are shown below for the respective files:

- mosinit_1PC_1IN.hoc  
  ![screenshot 1PC 1IN](screenshot_1PC_1IN.png)

- mosinit_16PC_1IN.hoc  
  ![screenshot 16PC 1IN a](screenshot_16PC_1IN_a.png)  
  ![screenshot 16PC 1IN b](screenshot_16PC_1IN_b.png)

- mosinit_81PC_9INforward.hoc  
  ![screenshot 81PC 1IN forward a](screenshot_81PC_1INforward_a.png)  
  ![screenshot 81PC 1IN forward b](screenshot_81PC_1INforward_b.png)

- mosinit_81PC_9INforw_reverse.hoc  
  ![screenshot 81PC 9IN forward&backward a](screenshot_81PC_9INfor_bak_a.png)  
  ![screenshot 81PC 9IN forward&backward b](screenshot_81PC_9INfor_bak_a.png)

- mosinit_1PC_1IN_silent2firing.hoc  
  ![screenshot 1PC 1IN silent2firing](screenshot_1PC_1IN_silent2firing.png)

- mosinit_1PC_1IN_myelinatedAx.hoc  
  ![screenshot 1PC 1IN myelinatedAx](screenshot_1PC_1IN_myelinatedAx.png)

Have fun.  
Nikita Vladimirov <nikita.vladimirov@gmail.com>

---

2025-07-09: Converted README to Markdown.
