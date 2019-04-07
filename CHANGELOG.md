Work in progress
- [Your entry here]
- Implement ECDSA signing and verifying
- Change input / output of digest and ec functions to Array of Uint8
- Add additional signatures for the digest and ec functions
- Add convenience functions to convert to and from hex strings / Array{Uint8}
- Add Julia pkg repo badge to README

v"0.0.1" (Initial release)
- OpenSSL bindings are available for
  - Digests: MD2, MD5, SHA, SHA1, SHA224, SHA256, SHA384, SHA512, DSS, DSS1, MDC2, RIPEMD160
  - Generating elliptic curve public keys
  - Random numbers
- Initial pure Julia implementations for
  - SHA256
  - RIPEMD160
  
