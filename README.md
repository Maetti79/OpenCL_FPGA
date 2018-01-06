# OpenCL_FPGA

OpenCL_FPGA - Utilise an real Industrie FPGA with OpenCL for Mining<br>
<br>
Language C# VS 2017<br>
-OpenCL 1.2,2.0 Miner mainly for FPGA's (520S Stratix10/385A Arria10)<br>
-Multi Custom OpenCl Kernel's for different CryptoCurrencys<br>
-Statum Protokoll<br>
-Customer ATi GPU (Pitcairn,Tonga,Hawaii,Fiji,Vega) OpenCL > 1.2<br>
-Accelerator ATi GPU (Vega) OpenCL > 1.2<br>
-Customer nVidia GPU (GP104) OpenCL > 1.2 (No Cuda!)<br>
-Accelerator nVidia GPU (Tesla) OpenCL > 1.2 (No Cuda!)<br>
-Nallatech Accelerator FPGA PCIe Cards like 385A,395A,510T,520S,520N OpenCL > 1.2<br>
<br>
First Test Run's ETH... <br>
CPU  AMD FX 8350 16GB  ~    0.5 MH/s @211W 2800MHz - OpenCL 1.2<br>
GPU  ATi R9 290x 4GB   ~   28.7 MH/s @218W 1100MHz - OpenCL 1.2<br>
GPU  ATi R9 Fury 8GB   ~   31.9 MH/s @241W 1110MHz - OpenCL 1.2<br>
FPGA Nallatech 520S    ~ 421.41 MH/s @107W 1200MHz - OpenCL 1.2<br>
<br>
! UPDATE 06.01.2018 ! hardware and compatibility test's will be heavily continued tonight !<br>
! heavy development is going on here !<br>
<br>
! source code and more info to come soon !<br>
<br>
Don't ask for Verilog...it's not my road here!<br>
Stratix 10 OK<br>
Stratix 5 OK<br>
Arria 10 OK<br>
Intel® Xeon® Platinum 8180M Processor OK ;) .. testing now!<br>
<br>
Stratix 3 NOPE<br>
Cyclone NOPE<br>
xilinx NOPE<br>
<br>
The main problem is, you need fast access to > 4 GB of DDR3/4/5 and there are not hobby development boards out there.<br>
And you need an huge FPGA not a tiny Spartan<br>
<br>
best gerards <br>
