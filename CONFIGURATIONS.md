
# Hardware Configurations
- The CPU and the motherboard BIOS must support SGX.
- SGX is turned off by default and must be enabled via MSR.IA32_Feature_Control.SGX_Enable. 
- Only the BIOS can make changes to the IA32_Feature_Control.
