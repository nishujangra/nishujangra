# Nishant

**eBPF/Kernel Engineer · Systems & Infrastructure · Open Source**

I build things that live in the parts of the stack most engineers don't touch — kernel networking,
QUIC/HTTP3 edge proxies, eBPF-based packet filtering. When something is slow, broken, or under
attack, I want to understand exactly why and fix it at the right layer.

---

## Projects

| Project | Stack | Description |
|---|---|---|
| [Impulse](https://github.com/impulse-proxy/impulse) | Rust · HTTP/3 · QUIC | HTTP/3→HTTP/2 edge proxy · benchmarked across HTTP/1.1, HTTP/2, HTTP/3 (100% success; ~5K req/s at 100 clients on 4 vCPUs) · circuit breaker restores 5.6× throughput under backend failure · overload protection, distributed quota, observability bundle |
| [ElfOwl](https://github.com/cloudarmour-io/ElfOwl) | Go · eBPF · Linux | eBPF-based compliance and observability — network, file I/O, process, and capabilities |
| [vex](https://github.com/impulse-proxy/vex) | Rust · HTTP/3 | HTTP/3 load testing tool with latency aggregation |
| [BalancerX](https://github.com/nishujangra/balancerx) | Go · HTTP/TCP | Load balancer · round-robin/random · ~12K req/s across 3 backends |
| [debforge](https://github.com/nishujangra/debforge) | Bash · dpkg-deb | CLI tool to forge .deb packages from binaries |

---

## Stack

```
Core          Go · Rust · C (eBPF/XDP)
Networking    Linux · eBPF/XDP · iptables/nftables · WireGuard · dnsmasq · Shorewall
Backend       REST APIs · RBAC · OAuth 2.0 · JWT · ETL pipelines · goroutines
Databases     PostgreSQL · Redis · CouchDB · KeyDB
Infra         Docker · Hetzner · Nginx · Caddy · VirtualBox · Juju
Familiar      Python · C++ · TypeScript · Perl · Bash
```

---

## Writing

50+ articles on eBPF, Linux networking, Rust, and backend systems.

→ [nishujangra.dev/blogs](https://nishujangra.dev/blogs) · [Medium](https://medium.com/@nishujangra27)

---

## Connect

[Portfolio](https://nishujangra.dev) · [LinkedIn](https://linkedin.com/in/nishujangra27) · [GitHub](https://github.com/nishujangra) · [X](https://x.com/nishujangra27) · `ndjangra1027 [at] gmail.com`
