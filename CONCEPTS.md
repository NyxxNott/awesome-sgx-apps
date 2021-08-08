# Engineering Elements

## Enclave Engineering
- An Enclave is a portion of memory
- An Enclave code can be invoked by special instructions.
- An Enclave can be built and loaded as a shared object on Linux OS
- An Enclave file can be disassembled
- An Enclave contents can be encrypted on the fly

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
