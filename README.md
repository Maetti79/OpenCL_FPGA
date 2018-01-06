# OpenCL_FPGA

OpenCL_FPGA - Utilise an real Industrie FPGA with OpenCL for Mining

Language C# VS 2017
-OpenCL 1.2,2.0 Miner mainly for FPGA's (520S Stratix10/385A Arria10)
-Multi Custom OpenCl Kernel's for different CryptoCurrencys
-Statum Protokoll
-Customer ATi GPU OpenCL
-Accelerator ATi GPU OpenC
-Customer nVidia OpenCL (No Cuda!)
-Accelerator nVidia GPU OpenC (No Cuda!)
-Nallatech Accelerator FPGA PCIe Cards like 385A,395A,510T,520S,520N

First Test Run ETH 
AMD FX 8350 16GB  ~    0.5 MH/s @211W 2800MHz - OpenCL 1.2
ATi R9 Fury 8GB   ~   31.9 MH/s @241W 1110MHz - OpenCL 1.2
Nallatech 520S    ~ 421.41 MH/s @107W 1200MHz - OpenCL 1.2

! hardware and compatibility test will be heavily continued !
! heavy development is going on here !

! source code and more info to come soon !

Don't ask for Verilog...it's not my road here!
Stratix 10 OK
Stratix 5 OK
Arria 10 OK
Intel® Xeon® Platinum 8180M Processor OK ;) .. testing now!

Stratix 3 NOPE
Cyclone NOPE
xilinx NOPE

The main problem is, you need fast access to > 4 GB of DDR3/4/5 and there are not hobby development boards out there.
And you need an huge FPGA not a tiny Spartan

best gerards 
