# Engineering Elements

## Enclave Engineering
- An Enclave code can be invoked by special instructions.
- An Enclave can be built and loaded as a shared object on Linux OS
- An Enclave file can be disassembled

## Enclave Execution
- Data stored in the enclave can be opened and decrypted within the SGX enclave on the Intel Xeon processor

## Enclave Engagements
- The OS communicate with the enclave through a kernel driver 
- The code is not allowed to make system calls inside the enclave
- The system calls has to be done by the applications connected to the enclave via kernel driver
- To execute the intel SGX commands and run in an enclave, code must be signed and verified with a developer key

## 
