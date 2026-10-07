<div align="center">

# `TIRROU OUSSAMA`

### `SYSTEMS ARCHITECT` · `CO-FOUNDER & CTO`

**I build the systems underneath the software.**

<br>

[![AWFER](https://img.shields.io/badge/AWFER-MOBILITY_INFRASTRUCTURE-0066FF?style=for-the-badge)](https://awfer.net)
[![SYSTEMS](https://img.shields.io/badge/SYSTEMS-ARCHITECTURE-111827?style=for-the-badge)](#)
[![NETWORKING](https://img.shields.io/badge/NETWORKING-TCP%2FTLS-0066FF?style=for-the-badge)](#)
[![LINUX](https://img.shields.io/badge/LINUX-INFRASTRUCTURE-111827?style=for-the-badge\&logo=linux\&logoColor=white)](#)

<br>

`NETWORKING`　`SYSTEMS`　`INFRASTRUCTURE`　`MOBILE`　`DISTRIBUTED SYSTEMS`

</div>

---

<div align="center">

## `I DON'T JUST BUILD APPS.`

### `I BUILD THE SYSTEMS THEY RUN ON.`

</div>

<br>

<table>
<tr>

<td width="33%" align="center">

### `01`

**NETWORK**

TCP/IP
Raw sockets
TLS / mTLS
Connection lifecycle

</td>

<td width="33%" align="center">

### `02`

**SYSTEM**

Linux
systemd
Processes
Shared memory
Resource control

</td>

<td width="33%" align="center">

### `03`

**APPLICATION**

Android
Kivy
GPS
Real-time services
Trip state

</td>

</tr>
</table>

---

<div align="center">

# `AWFER`

### **Mobility infrastructure built from the network layer up.**

</div>

AWFER is the system I am building as **Co-Founder & CTO** — a mobility platform designed around real-time communication, driver availability, trip state and distributed services.

The goal is not simply to build another ride-hailing application.

**The goal is to build the infrastructure underneath mobility.**

<br>

<table>
<tr>

<td width="50%" valign="top">

### `BACKEND`

```text
CLIENT
  │
  ▼
TCP / TLS
  │
  ▼
CONNECTION
  │
  ▼
AUTHENTICATION
  │
  ▼
FINITE STATE MACHINE
  │
  ▼
SERVICE
  │
  ▼
SHARED MEMORY
  │
  ▼
SYSTEM
```

</td>

<td width="50%" valign="top">

### `MOBILE`

```text
ANDROID
   │
   ├── CUSTOMER
   │
   └── DRIVER
          │
          ▼
       GPS
          │
          ▼
   REAL-TIME STATE
          │
          ▼
      AWFER CORE
```

</td>

</tr>
</table>

---

<div align="center">

## `THE AWFER STACK`

[![Python](https://img.shields.io/badge/PYTHON-3.13-3776AB?style=for-the-badge\&logo=python\&logoColor=white)](#)
[![TCP](https://img.shields.io/badge/TCP-RAW_SOCKETS-0066FF?style=for-the-badge)](#)
[![TLS](https://img.shields.io/badge/TLS-mTLS-0066FF?style=for-the-badge)](#)
[![Linux](https://img.shields.io/badge/LINUX-SYSTEMS-111827?style=for-the-badge\&logo=linux\&logoColor=white)](#)
[![Android](https://img.shields.io/badge/ANDROID-MOBILE-3DDC84?style=for-the-badge\&logo=android\&logoColor=white)](#)
[![Kivy](https://img.shields.io/badge/KIVY-PYTHON_MOBILE-3776AB?style=for-the-badge)](#)
[![GCP](https://img.shields.io/badge/GCP-INFRASTRUCTURE-4285F4?style=for-the-badge\&logo=googlecloud\&logoColor=white)](#)

</div>

<br>

<table>
<tr>

<td width="25%" align="center">

### `TCP/IP`

Raw network communication

</td>

<td width="25%" align="center">

### `TLS`

Encrypted transport
& mutual authentication

</td>

<td width="25%" align="center">

### `FSM`

Explicit system state

</td>

<td width="25%" align="center">

### `IPC`

Shared-memory communication

</td>

</tr>

<tr>

<td width="25%" align="center">

### `LINUX`

Processes
systemd
resources

</td>

<td width="25%" align="center">

### `ANDROID`

Customer
Driver
background services

</td>

<td width="25%" align="center">

### `GPS`

Location
tracking
real-time state

</td>

<td width="25%" align="center">

### `GCP`

Cloud infrastructure
deployment
operations

</td>

</tr>
</table>

---

<div align="center">

# `HOW I THINK ABOUT SYSTEMS`

</div>

I prefer systems where **important behavior is explicit**.

Not hidden behind layers of abstraction.

Not dependent on frameworks doing things I cannot explain.

Not built around complexity for the sake of complexity.

```text
PROTOCOL
    ↓
CONNECTION
    ↓
STATE
    ↓
MEMORY
    ↓
PROCESS
    ↓
SERVICE
    ↓
APPLICATION
```

### `MY RULE`

> **Understand the machine before abstracting the machine.**

That means working close to the actual system:

`Sockets` · `Processes` · `Memory` · `TLS` · `State` · `Linux` · `Android`

---

<div align="center">

## `ENGINEERING PRINCIPLES`

</div>

<table>
<tr>

<td width="50%" valign="top">

### ⚙️ Explicit Systems

I like knowing exactly where state lives, how connections move and which process owns what.

### 🧠 Understand the Stack

Frameworks are tools — not substitutes for understanding the underlying system.

### ⚡ Real-Time First

Communication, state transitions and resource behavior matter more than decorative architecture diagrams.

</td>

<td width="50%" valign="top">

### 🔒 Security by Architecture

Authentication and encrypted communication belong inside the system design.

### 🧩 Small Services

Services should have clear responsibilities and predictable behavior.

### 🛠️ Build What You Need

When existing abstractions get in the way, I am comfortable going lower.

</td>

</tr>
</table>

---

<div align="center">

# `PROJECTS`

### Systems I am actively building.

</div>

<table>

<tr>

<td width="50%" valign="top">

## 🚘 `AWFER CUSTOMER`

Customer-side Android application for the AWFER mobility network.

**Core**

`Python` · `Kivy` · `Android` · `GPS`

**Focus**

Real-time location, trip lifecycle, networking and customer interaction.

</td>

<td width="50%" valign="top">

## 🚗 `AWFER DRIVER`

Driver-side Android application built around availability and real-time trip infrastructure.

**Core**

`Python` · `Kivy` · `Android` · `Services`

**Focus**

Driver availability, GPS, foreground/background services and trip state.

</td>

</tr>

<tr>

<td width="50%" valign="top">

## 🖥️ `AWFER SYSTEM`

The backend infrastructure powering the AWFER network.

**Core**

`Python 3.13` · `TCP/TLS` · `systemd` · `Shared Memory`

**Focus**

Networking, authentication, state machines, service orchestration and IPC.

</td>

<td width="50%" valign="top">

## 🔐 `INFRASTRUCTURE`

The systems surrounding the core platform.

**Core**

`Linux` · `TLS` · `SQLite` · `GCP`

**Focus**

Security, authentication, deployment, resource management and operations.

</td>

</tr>

</table>

---

<div align="center">

# `SYSTEMS OVER SYNTAX`

### I care about what the software **does**.

Not just what language it was written in.

<br>

```text
        ┌──────────────────────────┐
        │        APPLICATION       │
        └────────────┬─────────────┘
                     │
        ┌────────────▼─────────────┐
        │          STATE           │
        └────────────┬─────────────┘
                     │
        ┌────────────▼─────────────┐
        │         SERVICES         │
        └────────────┬─────────────┘
                     │
        ┌────────────▼─────────────┐
        │        PROCESSES         │
        └────────────┬─────────────┘
                     │
        ┌────────────▼─────────────┐
        │        NETWORK / IPC     │
        └────────────┬─────────────┘
                     │
        ┌────────────▼─────────────┐
        │           LINUX          │
        └──────────────────────────┘
```

</div>

---

<div align="center">

# `GITHUB`

<img src="https://streak-stats.demolab.com?user=TirrouOussama&theme=dark&hide_border=true&background=00000000&ring=0066FF&fire=00A8FF&currStreakLabel=FFFFFF" />

<br><br>

[![GitHub](https://img.shields.io/badge/GitHub-TirrouOussama-111827?style=for-the-badge\&logo=github)](https://github.com/TirrouOussama)
[![AWFER](https://img.shields.io/badge/AWFER-awfer.net-0066FF?style=for-the-badge)](https://awfer.net)

</div>

---

<div align="center">

## `CURRENTLY BUILDING`

<br>

`AWFER CORE`
`REAL-TIME MOBILITY INFRASTRUCTURE`
`ANDROID CLIENTS`
`NETWORK SERVICES`
`LINUX SYSTEMS`

<br>

### `FROM SOCKETS TO SYSTEMS.`

</div>

---

<div align="center">

# `LET'S BUILD SOMETHING THAT HAS TO WORK.`

<br>

**AWFER** · **SYSTEMS** · **NETWORKING** · **INFRASTRUCTURE** · **MOBILE**

<br>

[![Website](https://img.shields.io/badge/awfer.net-0066FF?style=for-the-badge\&logo=google-chrome\&logoColor=white)](https://awfer.net)
[![GitHub](https://img.shields.io/badge/GitHub-TirrouOussama-111827?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/TirrouOussama)

</div>
