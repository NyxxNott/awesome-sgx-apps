# awesome-sgx-solutions
Awesome Artefacts on SGX Systems and Services

## Technology Architecture
- TEE has to be considered as a co-processor
- TEE executes programs whose hash, or fingerprint, corresponds to the original code

## Security Architecture
-  The manufacturer of the processor guarantees that nobody has access to the internal keys of the TEE  
-  The manufacturer of the processor guarantees that nobody has access to read its memory.

## Business Architecture
- Manufacturer can authenticate each TEE and provide remote attestation to a user.
- This is to confirm that the untampered program is actually running on a genuine TEE.
- Even if the machine is physically located in an off-site data center.

## Functional Architecture
- TEEs allow us to execute any state update without sharing data with the blockchain validators

## Relevant Usecases 
- 
