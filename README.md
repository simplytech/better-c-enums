# better-c-enums
Compile-time type checking of (wrapped) C enums to achieve (almost) feature-parity with C++ enums

C++ enums benefit from compile-time type checking but C enums do not. C enums are treated as integers and most of the time they are implicitly converted to integers. Some modern compilers might issue warnings if one enum type is used instead of another.

**Better C Enums** aims to wrap C enums to provide similar benefits to C++ enums.
