
## Rust SGX - Intel SGX Differences
- Static data can be easily initialized in Rust, but there is no such mechanisms in SGX enclave.
- Unlike Rust thread, SGX thread does not have constructors nor destructors. 
- Rust mutex is different compared to SGX pthread mutex
