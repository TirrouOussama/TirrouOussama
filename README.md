<div align="center">

# `TIRROU OUSSAMA`

### `SYSTEMS ARCHITECT` · `SOFTWARE ENGINEER`

**Designing systems from the protocol layer to the application layer.**

<br>

[![SYSTEMS](https://img.shields.io/badge/SYSTEMS-ARCHITECTURE-0066FF?style=for-the-badge)](#)
[![NETWORKING](https://img.shields.io/badge/NETWORKING-TCP%2FIP-0066FF?style=for-the-badge)](#)
[![LINUX](https://img.shields.io/badge/LINUX-SYSTEMS-111827?style=for-the-badge\&logo=linux\&logoColor=white)](#)
[![PYTHON](https://img.shields.io/badge/PYTHON-3.13-3776AB?style=for-the-badge\&logo=python\&logoColor=white)](#)

<br>

`SYSTEMS`　·　`NETWORKING`　·　`LINUX`　·　`SECURITY`　·　`MOBILE`　·　`INFRASTRUCTURE`

</div>

---

<div align="center">

# `I BUILD SYSTEMS.`

### Not just applications.

</div>

<br>

I am interested in the layers most software eventually depends on:

```text
APPLICATION
     ↓
STATE
     ↓
SERVICES
     ↓
PROCESSES
     ↓
MEMORY
     ↓
IPC
     ↓
NETWORK
     ↓
OPERATING SYSTEM
```

I like understanding what happens between those layers — how data moves, how state changes, how processes communicate, how resources are managed, and how the system behaves when things go wrong.

---

<div align="center">

## `THE WAY I BUILD`

</div>

<table>
<tr>

<td width="33%" align="center">

### `01`

## `UNDERSTAND`

Understand the layer before abstracting it.

</td>

<td width="33%" align="center">

### `02`

## `DESIGN`

Make state, ownership and communication explicit.

</td>

<td width="33%" align="center">

### `03`

## `BUILD`

Turn the model into software that actually runs.

</td>

</tr>
</table>

<br>

<div align="center">

```text
LESS MAGIC
MORE UNDERSTANDING

LESS NOISE
MORE CONTROL

LESS ABSTRACTION
MORE INTENT
```

</div>

---

<div align="center">

# `TECHNICAL TERRITORY`

</div>

<table>
<tr>

<td width="50%" valign="top">

## 🌐 `NETWORKING`

[![TCP/IP](https://img.shields.io/badge/TCP%2FIP-0066FF?style=flat-square)](#)
[![TLS](https://img.shields.io/badge/TLS-0066FF?style=flat-square)](#)
[![mTLS](https://img.shields.io/badge/mTLS-0066FF?style=flat-square)](#)
[![Sockets](https://img.shields.io/badge/RAW_SOCKETS-0066FF?style=flat-square)](#)

Connection-oriented systems, transport security, socket communication, connection lifecycle and protocol-level behavior.

</td>

<td width="50%" valign="top">

## 🖥️ `SYSTEMS`

[![Linux](https://img.shields.io/badge/LINUX-111827?style=flat-square\&logo=linux\&logoColor=white)](#)
[![systemd](https://img.shields.io/badge/SYSTEMD-111827?style=flat-square)](#)
[![IPC](https://img.shields.io/badge/IPC-111827?style=flat-square)](#)
[![FSM](https://img.shields.io/badge/FSM-111827?style=flat-square)](#)

Processes, service architecture, resource management, state machines, IPC and system-level behavior.

</td>

</tr>

<tr>

<td width="50%" valign="top">

## 🔐 `SECURITY`

Authentication, encrypted communication, credentials, trust boundaries, service isolation and security-conscious system design.

</td>

<td width="50%" valign="top">

## 📱 `APPLICATIONS`

Python applications, Android systems, mobile services, GPS-driven applications and real-time client behavior.

</td>

</tr>

</table>

---

<div align="center">

# `MY MENTAL MODEL`

</div>

When I look at a system, I tend to break it down into a few fundamental questions:

<table>
<tr>

<td align="center" width="20%">

### `STATE`

**What does it know?**

</td>

<td align="center" width="20%">

### `MEMORY`

**Where does it live?**

</td>

<td align="center" width="20%">

### `PROCESS`

**Who owns it?**

</td>

<td align="center" width="20%">

### `NETWORK`

**How does it move?**

</td>

<td align="center" width="20%">

### `FAILURE`

**What happens when it breaks?**

</td>

</tr>
</table>

<br>

```text
              ┌───────────────┐
              │     STATE     │
              └───────┬───────┘
                      │
              ┌───────▼───────┐
              │    PROCESS    │
              └───────┬───────┘
                      │
         ┌────────────┴────────────┐
         │                         │
   ┌─────▼─────┐             ┌─────▼─────┐
   │   MEMORY  │             │   NETWORK │
   └─────┬─────┘             └─────┬─────┘
         │                         │
         └────────────┬────────────┘
                      │
               ┌──────▼──────┐
               │ APPLICATION │
               └─────────────┘
```

---

<div align="center">

# `ENGINEERING PHILOSOPHY`

</div>

<table>
<tr>

<td width="50%" valign="top">

### `EXPLICIT > IMPLICIT`

If something is important, I want to be able to see it.

State.
Ownership.
Communication.
Failure paths.

</td>

<td width="50%" valign="top">

### `UNDERSTANDING > CONVENIENCE`

High-level tools are useful.

But knowing what happens underneath them is more useful.

</td>

</tr>

<tr>

<td width="50%" valign="top">

### `SIMPLE > ARTIFICIALLY COMPLEX`

A system does not become better because it contains more layers.

Complexity should solve a problem.

</td>

<td width="50%" valign="top">

### `CONTROL > MAGIC`

I prefer predictable systems whose behavior can be traced from input to output.

</td>

</tr>

</table>

---

<div align="center">

# `WHAT I LIKE BUILDING`

<br>

`NETWORK SERVICES`

`STATE MACHINES`

`LINUX SERVICES`

`REAL-TIME SYSTEMS`

`SECURE COMMUNICATION`

`DISTRIBUTED COMPONENTS`

`MOBILE SYSTEMS`

`INFRASTRUCTURE`

`DEVELOPER TOOLING`

</div>

---

<div align="center">

# `PROJECTS`

### Things I build are experiments in systems engineering.

</div>

<table>

<tr>

<td width="50%" valign="top">

### 🖥️ `SYSTEMS`

Low-level services, networking, process architecture, IPC and Linux infrastructure.

`Python` · `Linux` · `TCP/TLS` · `systemd`

</td>

<td width="50%" valign="top">

### 📱 `MOBILE`

Android applications and services designed around real-time system behavior.

`Python` · `Kivy` · `Android` · `GPS`

</td>

</tr>

<tr>

<td width="50%" valign="top">

### 🔐 `SECURITY`

Authentication systems, encrypted communication and security-oriented infrastructure.

`TLS` · `mTLS` · `Authentication` · `Linux`

</td>

<td width="50%" valign="top">

### ☁️ `INFRASTRUCTURE`

Systems that have to survive outside the development environment.

`GCP` · `Linux` · `Deployment` · `Operations`

</td>

</tr>

</table>

---

<div align="center">

# `CURRENT FOCUS`

```text
SYSTEM ARCHITECTURE
        │
        ├── NETWORKING
        ├── PROCESS DESIGN
        ├── IPC
        ├── SECURITY
        ├── REAL-TIME SYSTEMS
        └── INFRASTRUCTURE
```

<br>

**Going deeper into the systems underneath modern software.**

</div>

---

<div align="center">

# `GITHUB`

<img src="https://streak-stats.demolab.com?user=TirrouOussama&theme=dark&hide_border=true&background=00000000&ring=0066FF&fire=00A8FF&currStreakLabel=FFFFFF" />

<br><br>

[![GitHub](https://img.shields.io/badge/GitHub-TirrouOussama-111827?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/TirrouOussama)

</div>

---

<div align="center">

# `BUILD THE SYSTEM.`

### Understand the protocol.

### Understand the state.

### Understand the machine.

<br>

`SYSTEMS` · `NETWORKING` · `SECURITY` · `LINUX` · `INFRASTRUCTURE`

</div>
