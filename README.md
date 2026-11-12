<div align="center">

[![typing](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=2BFF7A&center=true&vCenter=true&width=700&height=48&lines=ikihsan%40kerala%3A%7E%24+whoami;building+payment+systems+in+Rust;shipping+apps+people+actually+use;learning+kernels+and+boot+internals;breaking+stuff+on+purpose+(legally))](https://ihsanik.tech)

<img src="https://img.shields.io/badge/Rust-0A0A0B?style=for-the-badge&logo=rust&logoColor=2BFF7A" />
<img src="https://img.shields.io/badge/Linux-0A0A0B?style=for-the-badge&logo=linux&logoColor=2BFF7A" />
<img src="https://img.shields.io/badge/Flutter-0A0A0B?style=for-the-badge&logo=flutter&logoColor=2BFF7A" />
<img src="https://img.shields.io/badge/kernel_dev-in_progress-0A0A0B?style=for-the-badge&labelColor=0A0A0B&color=4CE6E6" />

</div>

```console
ikihsan@kerala:~$ whoami
Ihsanul Hak IK  //  software engineer

ikihsan@kerala:~$ cat /etc/motd
rust + payments by day. kernels + boot + security by night.
i ship products end to end: backend, mobile, web, deploy.
```

## `$ top`

```text
 PID  PROCESS                                   STATE
 001  payments + reconciliation (rust)          running   @ Harwex Technology
 002  rust -> kernel / OS development           learning
 003  cybersecurity + ethical hacking           exploring
 004  agentos (voice-first OS on AOSP)          phase 0 / specs
```

## `$ ls ~/shipped`

Real products, real users. Some are private, so descriptions only.

| | product | what it does |
| --- | --- | --- |
| 🍽️ | [**Tabaq Al Hejazi**](https://tabaqalhejazi.com) &nbsp;+&nbsp; [**live menu**](https://menu.tabaqalhejazi.com) | Website for a seafood and mandi restaurant in Pulikkal: story-driven scroll layout, photo lightbox, optimized images, SEO/OG meta. The menu lives on its own subdomain with dishes and live pricing. |
| <img src="https://skillicons.dev/icons?i=flutter,firebase,supabase&theme=dark" height="28" /> | **Quality Dates** *(private)* | Distribution and billing app: inventory, purchase orders, orders, ledgers and reports. |
| <img src="https://skillicons.dev/icons?i=flutter,nestjs&theme=dark" height="28" /> | **Kooli Pani** *(app)* + [**website**](https://github.com/ikihsan/kooli-website) | Labour marketplace for India: daily-wage workers meet contractors. OTP-verified profiles, wages shown upfront, in-app chat, job tracking from assigned to completed, in English, Hindi and Malayalam. | 
| <img src="https://skillicons.dev/icons?i=nestjs,mysql,flutter,nginx,linux&theme=dark" height="28" /> | **Multi-tenant backend** *(private)* | NestJS / MySQL API behind a Flutter app and web admin, with inventory and usage-based BOQ workflows, on a Linux VPS with Nginx and TLS. |
| <img src="https://skillicons.dev/icons?i=rust,postgres&theme=dark" height="28" /> | **Payments platform** *(private, Harwex)* | Multi-currency fee transfers, a reconciliation engine, custom RBAC, and an append-only, SHA-256 hash-checked audit log in PostgreSQL. |
| 🧭 | [**TripInsta**](https://tripinsta.in) | Travel platform with a custom backend for publishing tour packages and handling enquiries. |

## `$ ls ~/lab`

Where the low-level and security curiosity lives.

| | project | what it is |
| --- | --- | --- |
| <img src="https://skillicons.dev/icons?i=bash,linux,fedora&theme=dark" height="28" /> | [**fedora-from-boot**](https://github.com/ikihsan/fedora-from-boot) | Hand-rolled initramfs: custom `/init` and `bin/`, packed as `initramfs.img.gz`. Poking at how Linux comes up before userspace exists. |
| <img src="https://skillicons.dev/icons?i=kotlin,androidstudio&theme=dark" height="28" /> | [**agentos**](https://github.com/ikihsan/agentos) | Voice-first, task-driven mobile OS on AOSP. Intent in, task runtime, UI only when needed. Phase 0: specs and ADRs. |
| <img src="https://skillicons.dev/icons?i=nextjs,ts&theme=dark" height="28" /> | [**SecureTerminal**](https://github.com/ikihsan/SecureTerminal-PrivateChatApp) | Terminal-style private chat: connection codes, bcrypt auth, attempt limits, IP bans, device fingerprinting, TTL media. [Live](https://chat.ikihsan.tech) |
| <img src="https://skillicons.dev/icons?i=py&theme=dark" height="28" /> | [**think-free**](https://github.com/ikihsan/think-free) | Autonomous research mission with an append-only session log. Every claim is labelled `observed`, `inferred`, `speculative`, and nothing is claimed as shipped. |
| <img src="https://skillicons.dev/icons?i=ts,py&theme=dark" height="28" /> | [**RacerTune**](https://github.com/ikihsan/RacerTune---Your-Track-Coach) + [**f1**](https://github.com/ikihsan/f1) | Voice-only AI race engineer for closed tracks. Physics-first, advisory only, fails silent. The spec lives in `f1`. |
| <img src="https://skillicons.dev/icons?i=py&theme=dark" height="28" /> | [**AI-Video-Generation-Pipeline**](https://github.com/ikihsan/AI-Video-Generation-Pipeline) | Script to shots to model routing (Mochi-1, CogVideoX, Hunyuan, LTX) to stitched long-form video. Resumable, YAML-driven. |
| <img src="https://skillicons.dev/icons?i=nextjs,nodejs,mongodb&theme=dark" height="28" /> | [**Mock_interview**](https://github.com/ikihsan/Mock_interview) | AI mock interviews: Gemini questions, speech-to-text answers, webcam emotion analysis, feedback dashboard. |

## `$ cat stack.txt`

<table>
  <tr>
    <td><b>systems</b></td>
    <td><img src="https://skillicons.dev/icons?i=rust,c,cpp,bash,neovim,git&theme=dark" /></td>
  </tr>
  <tr>
    <td><b>backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=nodejs,nestjs,express,graphql,prisma,redis&theme=dark" /></td>
  </tr>
  <tr>
    <td><b>data</b></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,sqlite,firebase,supabase&theme=dark" /></td>
  </tr>
  <tr>
    <td><b>mobile</b></td>
    <td><img src="https://skillicons.dev/icons?i=flutter,dart,kotlin&theme=dark" /></td>
  </tr>
  <tr>
    <td><b>web</b></td>
    <td><img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,tailwind,html,css&theme=dark" /></td>
  </tr>
  <tr>
    <td><b>infra</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,nginx,vercel,linux&theme=dark" /></td>
  </tr>
</table>

## `$ dmesg | grep career`

```text
[2026.06 - now ] harwex technology ....... rust payments, reconciliation, RBAC, audit framework
[2026.02-2026.05] g3 interactive .......... NestJS/MySQL multi-tenant backend, Linux VPS, Nginx, TLS
[2025.10-2026.02] spaceai ................. React/Next.js SaaS UI, AutoCAD revision diffing with Claude
[2025.05-2025.09] autobse ................. NestJS/GraphQL, PostgreSQL indexes, Redis Pub/Sub, JWT/OAuth2
[2021 - 2025   ] KMCT college of eng. ..... B.Tech, computer science
```

## `$ cat roadmap.md`

```text
[x] ship production backends
[x] ship Rust in a payments codebase
[x] build an append-only, hash-checked audit log
[ ] boot a toy Rust kernel
[ ] memory management, scheduling, drivers
[ ] security research, done responsibly
```

## `$ ping me`

<p>
  <a href="https://ihsanik.tech"><img src="https://img.shields.io/badge/ihsanik.tech-0A0A0B?style=for-the-badge&logo=gnometerminal&logoColor=2BFF7A" /></a>
  <a href="https://linkedin.com/in/ikihsan"><img src="https://skillicons.dev/icons?i=linkedin&theme=dark" height="40" /></a>
  <a href="mailto:ikihsaan@gmail.com"><img src="https://skillicons.dev/icons?i=gmail&theme=dark" height="40" /></a>
  <a href="https://github.com/ikihsan"><img src="https://skillicons.dev/icons?i=github&theme=dark" height="40" /></a>
</p>

```text
[SYSTEM] session active. kerala, india. no telemetry.
```
