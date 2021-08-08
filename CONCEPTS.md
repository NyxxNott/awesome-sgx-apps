# Engineering Elements

## Enclave Engineering
- Enclave is a portion of memory
- Enclave code can be invoked by special instructions.
- Enclave can be built and loaded as a shared object on Linux OS
- Enclave file can be disassembled
- Enclave contents can be encrypted on the fly
- Enclave Image is statistically linked object under LinuxOS
- Enclave has an entry point to execution
- Every Enclave will have a heap size
- Every Enclave will have a few object files to be linked to the target enclave

## Enclave Execution
- Data stored in the enclave can be opened and decrypted within the SGX enclave on the Intel Xeon processor

## Enclave Engagements
- The OS communicate with the enclave through a kernel driver 
- The code is not allowed to make system calls inside the enclave
- The system calls has to be done by the applications connected to the enclave via kernel driver
- To execute the intel SGX commands and run in an enclave, code must be signed and verified with a developer key

## SGX Systemics 
- SGX allow user-level as well as operating system code to define private regions of memory, called enclaves,
- Contents of Enclave are protected and unable to be either read or saved by any process outside the enclave itself.

## SGX and Sidechannel Attacks
- Applications running inside of SGX must be written to be side channel resistant 
- SGX does not protect against side channel measurement or observation.
