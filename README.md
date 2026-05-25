# GiFo-RFC-0117 (v. 1.2.1)

GAuth: Power Enforcement Point

New Request for Comments of Gimel Foundation (GiFo RFC) - Establishung GAuth`s Power Enforcement Point

Abstract of RFC: This specification defines the Policy Enforcement Point (PEP) interface for the Gimel
Authorization (GAuth) protocol. It determines the PEP interface with two layers:

• Normative Core - A protocol-level PEP Interface Contract defining the input
schema (enforcement request), output schema (enforcement decision), error
response schema, evaluation semantics (how each PoA field maps to an
enforcement check with defined order and precedence), interaction with RFC
0116 §10.2 validation modes, and an HTTP binding for remote PEP deployments.

• Non-Normative Guidance - Four deployment patterns for PEP integration
(Middleware/Interceptor, Sidecar/Proxy, SDK/Client Library, MCP Compliance
Proxy), with a trade-o\ matrix.

Together, these enable any party that receives PoA credentials — whether it issued them
(via an RFC 0116 Type A adapter), holds them for presentation to humans or cross-
platform delegation (via a Type B adapter — a future interoperability path for human-
facing PoA disclosure, and EUDI regulatory compliance), or simply accepts them as a
relying party — to enforce those credentials consistently and in an interoperable way,
based on a published specification rather than implementation-specific knowledge.

This RFC is a Gimel Foundation contribution paper intended for open-source publication
under Apache License 2.0. Proprietary platform extensions, i.e. so-called Exclusions (as
per Legal Terms of Gimel Foundation) like AI-based governance, DNA-based identity and
PQC associated, Web3 integration, are outside the scope of this specification and are
not covered by the Apache 2.0 license (see Section 2 of this Request of Comment).

You are more than welcome to contribute !

Legal Provisions for users of this page

Please see the Legal Provisions under https://gimelfoundation.com

In particular the following terms apply:

GiFo RFC 0080 Legal Provisions for the Gimel Foundation

GiFo RFC 0090 Legal Provisions Related to Gimel Foundation Documents

GiFo RCC 0100 Rights Contributors Provide to the Gimel Foundation
