![open-memory-interface-omi-wht](pictures/open-memory-interface-omi-wht.png)



## **OMI Overview **

**OMI**, stands for Open Memory Interface

Starting with Power10 processor, the host memory is now connected to the processor through a new OMI serial interface. This Open Memory Interface (based on OpenCAPI3.1 protocol) opens a new era in memory attachment since it allows to connect new types of memories to replace conventional DDR host memory.

Thanks to the serial connection, much more memory interfaces are connected to the processor chip. This means Power10 chip has 1 Terabyte/s bandwidth on memory side and the same on external hardware supporting up to 2 Petabytes of addressable memories!

Thanks to the very low latency, this OMI near-memory connection brings plenty of new memory disaggregation possibilities. "Memory inception" for example, allows a process to borrow host memory from another server. "Pool of memories" can now be built to optimize the sharing of the most expensive resource of our servers.

Using this CAPI/OpenCAPI technology associated with FPGAs has not only solved unbelievable bottlenecks, but has drastically decreased the power consumption of previous solutions.

 All the code and related materials are contributed to different Github repositories: 

- <https://github.com/OpenCAPI/omi_asic_device_reference_design>.
- <https://github.com/OpenCAPI/omi_host_fire>.
- <https://github.com/OpenCAPI/omi_device_ice>.


