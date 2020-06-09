# Roadmap of TuringCell

## High Priority

* Translate [Paxos Made Easy](https://github.com/turingcell/paxos-made-easy) into English.

* Implement a standalone industrial Paxos library/service to provide a Paxos alternative to etcd and consul.

&emsp;&emsp;- Detailed Design Documents

&emsp;&emsp;- Multi-Master

&emsp;&emsp;- Weighted-Election

&emsp;&emsp;- Pipeline

&emsp;&emsp;- Full-Powered Membership Changement

&emsp;&emsp;- ...

* Implement turingcell-arm-emulator which supports various RTOS without MMU and Linux with MMU.

## Low Priority

* Implement turingcell-x86/mips/riscv-emulator which supports various RTOS without MMU and Linux with MMU.

* Add a golang-like scheduler to [libaco](https://github.com/hnes/libaco). And use libaco to improve the performance of the previous TuringCell implementation.
