<!--
  ┌──────────────────────────────────────────────────────────────────────┐
  │  supasuge / Evan Pardon — GitHub profile README                      │
  │  Theme: terminal + elementary cellular automaton (Rule 30)           │
  │  Regeneration: see ./scripts/ for the generators that produced the   │
  │    hex dump, GPG fingerprint, and Rule 30 art blocks below.          │
  │                                                                      │
  │  Easter egg for the CTF crowd — decode this on a fresh terminal:     │
  │    echo 'ZmxhZ3tydWxlXzMwX2lzX25vdF9hX1BSTkd9' | base64 -d           │
  └──────────────────────────────────────────────────────────────────────┘
-->

<h1 align="center">supasuge</h1>
<p align="center"><sub>Evan Pardon · cybersecurity × AI · cryptography · Software Engineer · CTF creator + puzzle enthusiast</sub></p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&pause=1200&color=84FA86&center=true&vCenter=true&width=640&lines=%24+whoami;offensive+security+%E2%80%A2+applied+cryptography+%E2%80%A2+agentic+automation;%E2%80%9CYou+can%27t+defend+what+you+don%27t+understand.%E2%80%9D" alt="typing tagline"/></a>
</p>

```text
·································█········································
·······························███······································
······························██  █·····································
·····························██ ████····································
····························██  █   █···································
···························██ ████ ███··································
··························██  █    █  █·································
·························██ ████  ██████································
························██  █   ███     █···············  rule 30 ·······
·······················██ ████ ██  █   ███······ a 1-D cellular automaton
······················██  █    █ ████ ██  █···· · deterministic, chaotic
·····················██ ████  ██ █    █ ████··· · once proposed as a PRNG
····················██  █   ███  ██  ██ █   █··· · a decent metaphor for
···················██ ████ ██  ███ ███  ██ ███······  this side of the web
```

<p align="center">
  <a href="https://github.com/supasuge"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-supasuge-0d1117?style=for-the-badge&logo=github&logoColor=84FA86&labelColor=0d1117"/></a>
  <a href="https://supasuge.com"><img alt="Blog" src="https://img.shields.io/badge/blog-supasuge.com-84FA86?style=for-the-badge&logo=hugo&logoColor=0d1117&labelColor=0d1117"/></a>
  <a href="https://linkedin.com/in/evan-pardon"><img alt="LinkedIn" src="https://img.shields.io/badge/in-evan--pardon-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117"/></a>
  <a href="https://tryhackme.com/p/supasuge"><img alt="TryHackMe" src="https://img.shields.io/badge/THM-supasuge-5232E7?style=for-the-badge&logo=tryhackme&logoColor=white&labelColor=0d1117"/></a>
  <a href="https://app.hackthebox.com/profile/1492227"><img alt="HTB" src="https://img.shields.io/badge/HTB-supasuge-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=0d1117&labelColor=0d1117"/></a>
  <a href="https://cryptohack.org/user/gxdqpardo/"><img alt="CryptoHack" src="https://img.shields.io/badge/CryptoHack-gxdqpardo-111827?style=for-the-badge&logo=protondrive&logoColor=white&labelColor=0d1117"/></a>
</p>

---

## `$ xxd identity.bin`

```text
00000000: 45 76 61 6e 20 50 61 72 64 6f 6e 00 00 00 00 00  |Evan Pardon.....|
00000010: 4f 61 6b 6c 61 6e 64 20 55 6e 69 76 65 72 73 69  |Oakland Universi|
00000020: 74 79 20 2d 20 42 2e 53 2e 20 41 49 00 00 00 00  |ty - B.S. AI....|
00000030: 43 79 62 65 72 73 65 63 75 72 69 74 79 20 2b 20  |Cybersecurity + |
00000040: 43 72 79 70 74 6f 67 72 61 70 68 79 00 00 00 00  |Cryptography....|
00000050: 73 75 70 61 73 75 67 65 2e 63 6f 6d 00 00 00 00  |supasuge.com....|
```

---

## `$ neofetch`

```text
           /\              evan@supasuge
          /  \             ─────────────────────────────────────
         / /\ \            os          : EndeavourOS x86_64
        / /  \ \           kernel      : Linux x.yzen
       / /    \ \          shell       : zsh  +  starship
      / /  /\  \ \         editor      : nvim (+ LazyVim)   /   vscode
     / /  /  \  \ \        wm          : Hyprland
    / /  /    \  \ \       langs       : Python · Rust · Go · C · Bash · SageMath
   / /__/______\__\ \      focus       : offensive-sec, cryptanalysis, agentic auto
  /__________________\     currently   : CTFd-ng · GPT-2-in-Rust · AutoRed · supasuge.com
                           ethos       : "can't defend what you don't understand"
                           uptime      : still learning
```

---

## `$ nmap -sV --top-ports 16 supasuge.local`

A scan of the things I keep listening on:

```text
Starting Nmap against host supasuge.local
───────────────────────────────────────────────────────────────────────────────
PORT       STATE  SERVICE          VERSION
22/tcp     open   ssh              OpenSSH 9.x (I teleport. No keys, no passwords. I'm just... there).
80/tcp     open   http             redirect → 443 
443/tcp    open   https            Caddy + Flask + HTMX  (TLS 1.3, HSTS) 
1337/tcp   open   ctf-build        manifest-driven challenges (crypto/web/pwn)
2718/tcp   open   gpt2-rust        burn framework · LoRA · Ollama self-improve
3141/tcp   open   auto-red         LangGraph multi-agent pentest orchestrator
4096/tcp   open   cryptanalysis    lattice attacks · padding oracles · side-channel
8080/tcp   open   fool             Rust CLI, 80+ magic-byte signatures
9001/tcp   open   blog-cms         SHA3-256 integrity · challenge-response auth
31337/tcp  open   homelab          AD + Linux, isolated VLANs
───────────────────────────────────────────────────────────────────────────────
Service detection performed against 1 host. 0 filtered, 0 closed.
```

- Just want to take some time out of my day to state that `nginx` compared to `Caddy` when used correctly is like watching the Mens Vs. Womens 100m dash finals in terms of being an all around **unit**. Solid reverse proxy, automated ACME TLS cert management... can't complain.
    - Truth be told I don't get the above analogy made either, and have not a singlular clue what was going through my head whilst mindlessly button mashing to some catchy tunes.

---

## `$ ps aux --sort=-start | grep ~evan/lab/`

```text
USER   PID    START  %FOCUS  PROJECT            NOTES
evan   1337   now    92%     CTFd-ng            Flask+HTMX CTF platform, YAML-based challenge deploys
evan   2718   now    78%     gpt2-rust          GPT-2 from scratch in Rust (Burn), pretrain → LoRA → self-improve
evan   3141   now    65%     AutoRed            policy-driven multi-agent offensive-sec orchestrator
evan   4096   now    55%     supasuge.com       hardened Flask blog, SSH auth, Caddy/nginx, SHA3 integrity
evan   8128   now    45%     fool               magic-byte spoofing / detection CLI (Rust)
evan   6174   bg     30%     ctf-challenges     COCONUT98, SchrodingerSeed, TROPIKOS, VoltLeak, PANCAKE PANIC
```

---

## `$ gpg --list-keys --fingerprint`

```text
/home/evan/.gnupg/pubring.kbx
────────────────────────────────────────

pub   rsa4096/C80848E2BE15B918 2024-01-01 [perpetual]
      Key fingerprint = 1F77 8C43 4F79 B1FC 5D60  E55E 0961 10AF DEC1 4497
uid           [ Certified AppSec Practitioner Certified ]

pub   rsa4096/894EFF9863015891 2023-01-01 [perpetual]
      Key fingerprint = 2502 B429 28F1 5A73 3CAE  CFF9 7D10 23E1 EFA8 65DA
uid           [ CompTIA Security+Certified ]

pub   rsa4096/911A01C7A8AF8303 2023-01-01 [perpetual]
      Key fingerprint = EFCE 0F2C 4A32 37ED B73D  30CD AB1F DD1E 30F4 0348
uid           [ CompTIA Network+ Certified ]
```

---

## `$ cat /etc/focus_areas`

| domain                   | what I actually do there                                                |
|:-------------------------|:------------------------------------------------------------------------|
| **security engineering** | hardening, secure-by-default infra, auth & session security, IAM        |
| **offensive security**   | understanding the attacker so the defender knows what's worth hardening |
| **detection / SOC**      | anomalies are invisible until you know what "normal" should look like   |
| **applied cryptography** | protocol analysis, side-channel & lattice attacks, SageMath tooling     |
| **automation**           | policy-driven, repeatable workflows; CI/CD-friendly security            |
| **sysadmin**             | AD & Linux enterprise ops — you can't harden what you can't operate     |

---

## `$ cat /etc/motd`

> *"Security is not a product, but a process."* — Bruce Schneier

```text
                                        █
                                       ███
                                      ██  █
                                     ▓▓ ▓▓▓▓
                                    ▓▓  ▓   ▓
                                   ▒▒ ▒▒▒▒ ▒▒▒
                                  ▒▒  ▒    ▒  ▒
                                 ░░ ░░░░  ░░░░░░
                                ░░  ░   ░░░     ░
                               ·· ···· ··  ·   ···
                              ··  ·    · ···· ··  ·

# logout
Connection to supasuge.local closed.
```

<p align="center">
  <a href="https://buymeacoffee.com/Coffee4supasuge">
    <img alt="bmc" src="https://img.shields.io/badge/%E2%98%95-coffee4supasuge-FFDD00?style=for-the-badge&labelColor=0d1117"/>
  </a>
</p>
