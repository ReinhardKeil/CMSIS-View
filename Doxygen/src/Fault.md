# Exception Fault Analysis {#fault}

## Overview {#about_fault}

The software components under **CMSIS-View:Fault** provide infrastructure and [API (function calls)](modules.html) to store, record, and analyze the Cortex-M Exception Fault information.
The Arm Cortex-M processors raise an exception fault on critical system failures such as illegal memory write or read, access to an disabled peripheral, execution of an invalid instruction, division by zero.
With the component **CMSIS-View:Fault:Storage** an exception fault can be saved for later analysis.  The component **CMSIS-View:Fault:Record** decodes an saved exception fault and records this information using the **Event Recorder**.

A typical execution flow is shown in the diagram below.

![Exception Fault Analysis](./images/ArmFault.png "Exception Fault Analysis")
