# Divyansh Verma

Software Engineer focused on systems programming, distributed systems, and ML infrastructure.

[LinkedIn](https://www.linkedin.com/in/dv-verma/) · [GitHub](https://github.com/D-Vspec) · [LeetCode](https://leetcode.com/u/jam_lt/) · [Blog](https://dvblogs.com) · divi.verma1903@gmail.com

---

## Projects

### LLM Inference Engine — C++, GGUF
[Repository](https://github.com/D-Vspec/inferenceEngine) · [Blog Post](https://dvblogs.com/Tokenization)

A GGUF-based LLM runner built from scratch. Custom tensor operations with multi-threaded matrix multiplication, memory-mapped file loading via Linux syscalls, byte-level GGUF parsing with custom 16-bit float structs, and RAII-based memory management for long-running processes.

### Trustless RPC Proxy — Rust
[Repository](https://github.com/D-Vspec/etherium-proxy)

A multi-provider JSON-RPC proxy with M-of-N consensus for data integrity. Includes a verification engine that walks Merkle-Patricia Tries and validates RLP-encoded proofs at the byte level, cryptographic state-root validation for Ethereum calls, and a real-time observability suite.

### dvMeet — Next.js, Node.js, WebRTC, Socket.IO
[Repository](https://github.com/D-Vspec/dvMeet) · [Live Demo](https://dvmeet.vercel.app/)

A peer-to-peer video conferencing platform built on WebRTC for low-latency communication. Establishes direct P2P data channels using UDP hole punching, and handles complex NAT traversal via a self-deployed and configured STUN/TURN server (coturn).

### dvBoy — C, SDL2, Assembly
[Repository](https://github.com/D-Vspec/dvBoyC)

A Game Boy emulator with cycle-accurate CPU and MMU components. Handles memory-mapped I/O and hardware synchronization, renders 8-bit graphics via SDL2, and debugs system-level errors down to the register and instruction level.

---

## Publications

**Agentic Multi-Hop RAG Pipelines** (in progress) — [Benchmarking Repository](https://github.com)
Research paper on implementing multi-hop RAG pipelines with agent-based retrieval.

**Tokenization in LLMs** — [Blog](https://dvblogs.com/Tokenization)
Implementing tokenization algorithms for LLMs from scratch in C++.

---

VIT Class of 2027 · Vellore, India
