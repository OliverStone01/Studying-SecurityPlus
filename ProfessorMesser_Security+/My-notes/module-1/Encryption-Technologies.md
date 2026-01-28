#### 🎓 Professor Messer Study Notes

## Encryption Technologies - CompTIA Security+ SY0-701 - 1.4

[Link to video](https://youtu.be/u61J0xR_XPU?si=Qczt-ESGMiDMG5fM)

### Notes

A TPM (Trusted Platform Module) is a chip that resides on the computers motherboard. Here is where cryptography takes place on that device. If you need to randomly generate numbers or keys, this takes place on the TPM. 

The TPM has 2 types of memory. 

- Persistent memory, which means keys are burned into the memory and they are unable to be removed.
- Versatile memory, which is where we can store keys, hardware configuration information. This is where keys from BitLocker are stored.

The TPM is also password protected with no method to perform dictionary attacks.

For large data centers and servers, we use HSM (Hardware Security Module) instead. This provides redundancy and is able to store thousands of cryptographic keys.

We can attach high-end cryptographic hardware and cryptographic accelerators to the HMS to preform quicker and manage performance better.

To manage all our keys, we use a software called a `Key Management System`. Here we can create keys, associate keys with specific users, rotate keys, and log key use and important events.

To manage security on a device, we use a `Security enclave` which is a separate processor on your device. This device is does many tasks without the need of any other processor:
- Has it's own boot ROM
- Monitors the systems boot process
- True random number generator
- Real-time memory encryption
- Root cryptographic keys
- Performs AES encryption in hardware
- and much more.






