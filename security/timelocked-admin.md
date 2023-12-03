---
description: >-
  This section discusses the timelock administrative contract overseeing the
  protocol
---

# Timelocked Admin

In an effort to fortify our community's security measures, a timelock mechanism has been implemented across all administrative functions, including proxy contracts. This safeguard is governed by a multi-signature contract.

For reference, the contract addresses are as follows:

* Timelock Contract: [0x1a85d24a7C3f9995b7D91209c928980c03001D51](https://basescan.org/address/0x1a85d24a7c3f9995b7d91209c928980c03001d51#code)
* Safe Contract (Multisig): [0x3f927868aAdb217ed137e87c44c83e4A3EB7f70B](https://app.safe.global/home?safe=base:0x3f927868aAdb217ed137e87c44c83e4A3EB7f70B)

All admin functionalities to the protocol are protected within these two contracts.

The timelocked multi-sig admin serves as a crucial protective layer for the protocol, especially as we work towards transitioning to decentralized governance. Proposing a transaction requires consensus from at least two out of three authorized parties. The execution of the proposed transaction is contingent upon a designated 24-hour waiting period, which may be extended if deemed necessary.
