```text
C4RB0NX1(1)                    Builder's Manual                    C4RB0NX1(1)
```

## NAME

**c4rb0nx1** — Niranchan. DevOps engineer building guardrails, memory and
tooling for AI agents.

## SYNOPSIS

```sh
c4rb0nx1 [--devops] [--cloud-native] [--security] [--ai-agents] <problem>
```

## DESCRIPTION

Agents are getting shell access faster than they are getting seatbelts.
I build the seatbelts: sandboxes that keep installs off the host, memory that
survives a context reset, and read-only interfaces that let an agent look
before it touches anything.

Off the clock I run a two-site Proxmox homelab and write about what breaks at
**[carbonx1.in](https://carbonx1.in)**.

## COMMANDS

**[tuprwre](https://github.com/AmazingCarbon/tuprwre)** · Go<br>
Your agent's `apt install` never touches your host. Risky installs run in a
throwaway container and the binaries come back as shims. Ships with `tprsh`,
a policy-enforcing shell with a hash-chained audit log.

**[memlane](https://github.com/AmazingCarbon/memlane)** · MCP server<br>
Durable operational memory for AI agents. One call tells a fresh session
what it was doing, what's next, and what it must not do yet.
`brew install c4rb0nx1/tap/memlane`

**[mog](https://github.com/AmazingCarbon/mog)** · Swift, macOS<br>
Your Mac locks itself when someone else looks at it. Offline face
recognition, nothing uploaded.
`brew install c4rb0nx1/tap/mog`

## EXPERIMENTAL

**KlusterQL**<br>
SQL across Kubernetes fleets. Read-only first, with output compact enough
for an agent to parse.

**Orb**<br>
Floating voice overlay for macOS. On-device Whisper speech-to-text, routed
to agent backends.

## ENVIRONMENT

```text
cloud        AWS · Bottlerocket · EKS
orchestrate  Kubernetes · k3s · Proxmox LXC
build        Go · TypeScript · Swift · Nix
secure       sandboxing · least privilege · audit trails
```

## SEE ALSO

[carbonx1.in](https://carbonx1.in) (digital garden) ·
[LinkedIn](https://www.linkedin.com/in/niranchan-d-a900b2225/) ·
[X](https://twitter.com/c4rb0nX01)

## BUGS

Will tell you your agent needs a sandbox. Usually right.

```text
c4rb0nx1                        carbonx1.in                        C4RB0NX1(1)
```
