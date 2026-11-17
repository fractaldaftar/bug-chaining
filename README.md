# Bug Chaining — Low → Critical Playbook

> Single-bug reports get triaged. Chained reports get paid. $10K+ reports are almost always chains.

## What it is

A standalone bug-chaining skill: the complete chaining mindset for turning low/medium findings into Critical impact — by connecting finding A to finding B so an attacker walks away with real harm (account takeover, stolen money, PII exfiltration, RCE) that neither bug achieves alone.

**The only question that matters:** "Can I connect finding A to finding B so that an attacker walks away with real harm that they couldn't achieve with either bug alone?" If you can't answer YES with a working PoC, keep escalating or move on.

## What's inside

- **The 10-question chain filter** — run for every candidate finding before spending more than 30 minutes on it. 3+ YES means ready to report; 1–2 means keep escalating; 0 means kill it and move on.
- **15 proven chain patterns (A–O)** with payout data — e.g. recon → source disclosure → bug-class flood ($5K–$50K).
- **Escalation ladders per vuln class** and a conditional-chain table (when a standalone bug needs a gadget).
- **Impact-writing rules, CVSS chain multipliers, and the 30-minute chain-or-move decision clock.**

## Use it when

- You have a low/medium finding and want to know how to chain it to Critical.
- You are strategizing what to hunt for maximum payout.

## Scope & Authorization

Authorized testing only — bug bounty programs (in-scope targets only), pentest engagements, or CTFs. Never test a target you do not own or have explicit written authorization for. Follow the program's rules, report through official channels, and never exfiltrate, destroy, or manipulate other users' data.

## License

MIT — see [LICENSE](LICENSE).
