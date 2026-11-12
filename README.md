<div align="center">

[![typing](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=2BFF7A&center=true&vCenter=true&width=700&height=48&lines=ikihsan%40kerala%3A%7E%24+whoami;building+payment+systems+in+Rust;learning+kernels+and+boot+internals;designing+things+that+fail+safe;breaking+stuff+on+purpose+(legally))](https://ihsanik.tech)

<img src="https://img.shields.io/badge/Rust-0A0A0B?style=for-the-badge&logo=rust&logoColor=2BFF7A" />
<img src="https://img.shields.io/badge/Linux-0A0A0B?style=for-the-badge&logo=linux&logoColor=2BFF7A" />

<img src="https://img.shields.io/badge/kernel_dev-in_progress-0A0A0B?style=for-the-badge&labelColor=0A0A0B&color=4CE6E6" />

</div>

```console
ikihsan@kerala:~$ whoami
Ihsanul Hak IK  //  software engineer

ikihsan@kerala:~$ cat /etc/motd
rust + payments by day. kernels + boot + security by night.

i like systems that are small, strict, and honest about what they know.
```

## `$ top`

```text
 PID  PROCESS                                   STATE
 001  payments + reconciliation (rust)          running   @ Harwex Technology
 002  rust -> kernel / OS development           learning
 003  cybersecurity + ethical hacking           exploring
 004  agentos (voice-first OS on AOSP)          phase 0 / specs
 005  think-free (autonomous research mission)  active
```

## `$ cat stack.txt`

<table>
  <tr>
    <td><b>systems</b></td>
    <td><img src="https://skillicons.dev/icons?i=rust,c,cpp,bash,kali,neovim,git&theme=dark" /></td>
  </tr>
  <tr>
    <td><b>backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=nodejs,nestjs,express,graphql,prisma,redis&theme=dark" /></td>
  </tr>
  <tr>
    <td><b>data</b></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,sqlite,firebase&theme=dark" /></td>
  </tr>
  <tr>
    <td><b>web + mobile</b></td>
    <td><img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,tailwind,flutter,dart,kotlin&theme=dark" /></td>
  </tr>
  <tr>
    <td><b>infra</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,nginx,vercel,linux&theme=dark" /></td>
  </tr>
  <tr>
    <td><b>other</b></td>
    <td><img src="https://skillicons.dev/icons?i=py,godot&theme=dark" />
  </tr>
</table>

## `$ ls ~/projects`

### `/sys` &nbsp;low level, boot, security

| | project | what it is |
| --- | --- | --- |
| <img src="https://skillicons.dev/icons?i=bash,linux,fedora&theme=dark" height="28" /> | [**fedora-from-boot**](https://github.com/ikihsan/fedora-from-boot) | Hand-rolled initramfs: custom `/init` and `bin/`, packed as `initramfs.img.gz`. Poking at how Linux comes up before userspace exists. |
| <img src="https://skillicons.dev/icons?i=kotlin,androidstudio&theme=dark" height="28" /> | [**agentos**](https://github.com/ikihsan/agentos) | Voice-first, task-driven mobile OS on AOSP. Intent in, task runtime, UI only when needed. Phase 0: specs and ADRs. |
| <img src="https://skillicons.dev/icons?i=nextjs,ts&theme=dark" height="28" /> | [**SecureTerminal**](https://github.com/ikihsan/SecureTerminal-PrivateChatApp) | Terminal-style private chat. Connection codes, bcrypt auth, attempt limits, IP bans, device fingerprinting, TTL media. [Live](https://chat.ikihsan.tech) |

### `/ai` &nbsp;agents, pipelines, coaching

| | project | what it is |
| --- | --- | --- |
| <img src="https://skillicons.dev/icons?i=py&theme=dark" height="28" /> | [**think-free**](https://github.com/ikihsan/think-free) | Autonomous research mission with an append-only session log. Every claim is labelled `observed`, `inferred`, `speculative`... and nothing is claimed as shipped. |
| <img src="https://skillicons.dev/icons?i=py&theme=dark" height="28" /> | [**AI-Video-Generation-Pipeline**](https://github.com/ikihsan/AI-Video-Generation-Pipeline) | Script to shots to model routing (Mochi-1, CogVideoX, Hunyuan, LTX) to stitched long-form video. YAML config, resumable. |
| <img src="https://skillicons.dev/icons?i=ts,py&theme=dark" height="28" /> | [**RacerTune**](https://github.com/ikihsan/RacerTune---Your-Track-Coach) + [**f1**](https://github.com/ikihsan/f1) | Voice-only AI race engineer for closed tracks. Physics-first, advisory only, fails silent. The spec lives in `f1`. |
| <img src="https://skillicons.dev/icons?i=nextjs,nodejs,mongodb&theme=dark" height="28" /> | [**Mock_interview**](https://github.com/ikihsan/Mock_interview) | AI mock interviews: Gemini-generated questions, speech-to-text answers, webcam emotion analysis, feedback dashboard. |
| <img src="https://skillicons.dev/icons?i=nextjs,flutter&theme=dark" height="28" /> | [**quranicai**](https://github.com/ikihsan/quranicai) | Islamic knowledge assistant, designed for web and Flutter clients. |

### `/web` &nbsp;products and client work

| | project | what it is |
| --- | --- | --- |
| <img src="https://skillicons.dev/icons?i=nestjs,graphql,prisma,postgres,nextjs&theme=dark" height="28" /> | [**forexai**](https://github.com/ikihsan/forexai) | Forex SaaS: NestJS + GraphQL + Prisma + PostgreSQL, Next.js 14 front end, Stripe subscriptions, live charts. |
| <img src="https://skillicons.dev/icons?i=nextjs,firebase,tailwind&theme=dark" height="28" /> | [**workspace (DocSpace)**](https://github.com/ikihsan/workspace) | Mobile-first personal document vault. Google sign-in, files stored on IPFS. |
| <img src="https://skillicons.dev/icons?i=react,express,mongodb&theme=dark" height="28" /> | [**Uservlog**](https://github.com/ikihsan/Uservlog) | Client blog platform with a separate admin panel, JWT auth, uploads, tags, search. |
| <img src="https://skillicons.dev/icons?i=nestjs,react&theme=dark" height="28" /> | [**primetrade**](https://github.com/ikihsan/primetrade) | Task manager with JWT + RBAC, built in 3 days for an internship assignment. |
| <img src="https://skillicons.dev/icons?i=ts,express,sqlite&theme=dark" height="28" /> | [**jobdocket**](https://github.com/ikihsan/jobdocket) | Jobs and time-tracking mini API with Zod validation. |
| <img src="https://skillicons.dev/icons?i=flutter,firebase&theme=dark" height="28" /> | **Qualitydates** *(private)* | Purchase orders, inventory, billing, ledgers, reports. |
| <img src="https://skillicons.dev/icons?i=nextjs&theme=dark" height="28" /> | [**TripInsta**](https://tripinsta.in) | Travel platform with a custom backend for tour packages and enquiries. |

### `/fun`

| | project | what it is |
| --- | --- | --- |
| <img src="https://skillicons.dev/icons?i=godot&theme=dark" height="28" /> | [**fake-friends**](https://github.com/ikihsan/fake-friends) | A game in Godot / GDScript. |

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
