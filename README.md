<h1 align="center">Hi, I'm Pranav 👋</h1>

<p align="center">
  <em>Software engineer working close to the OS, storage, and platform layers -<br/>
  Kubernetes internals, immutable Linux, and Go systems programming.</em>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/pranav-patil-4b70071b9/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://0xpranav.hashnode.dev">
    <img src="https://img.shields.io/badge/Blog-2962FF?style=for-the-badge&logo=hashnode&logoColor=white" alt="Blog"/>
  </a>
  <a href="https://github.com/pranav767">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

---

### 👨‍💻 About Me

- 🔧 I build **cloud-native infrastructure** and spend most of my time in **Kubernetes internals** and **immutable operating systems**.
- 🐧 Active contributor to **Talos Linux / Omni** ([siderolabs](https://github.com/siderolabs)) and **Incus / Incus OS** ([lxc](https://github.com/lxc)).
- 🧵 I like working at the boundary where the OS meets the cluster - volumes, networking, supply-chain security, and node lifecycle.
- ✍️ I write about what I learn at [0xpranav.hashnode.dev](https://0xpranav.hashnode.dev).

---

### 🛠️ Tech Stack & Tools

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  <img src="https://img.shields.io/badge/Talos_Linux-FF7300?style=for-the-badge&logo=linux&logoColor=white" alt="Talos Linux"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white" alt="WireGuard"/>
  <img src="https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=grpc&logoColor=white" alt="gRPC"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana"/>
</p>
<p>
  <img src="https://img.shields.io/badge/nftables-EE0000?style=for-the-badge&logo=linux&logoColor=white" alt="nftables"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
</p>

---

### 🌍 Open Source Impact

I contribute upstream to two production-grade infrastructure platforms, with work spanning
networking, storage, supply-chain hardening, and operator tooling.

#### 🧭 Leadership & Governance

- **Recurring contributor - Talos Linux & Omni (siderolabs):** Comfortable navigating the Talos
  codebase end-to-end, from kernel packaging to controller-level config documents.
- **Contributor - Incus / Incus OS (LXC):** Operator-facing tooling and multi-tenant storage
  isolation for the immutable Incus OS.
- I drive features through real design discussion with maintainers - including cases where the
  team ultimately shipped a different approach, and the value was in the exploration.

#### 📊 Technical Highlights

| Project | Contribution | Impact |
|---|---|---|
| [Talos #13374](https://github.com/siderolabs/talos/pull/13374) | Declarative **nftables NAT** config documents | Adds SNAT, DNAT & masquerading as first-class declarative config |
| [Talos #13082](https://github.com/siderolabs/talos/pull/13082) | **HTTP network probe** support | Removes false positives from TCP probes in proxy-gated environments |
| [Talos #12631](https://github.com/siderolabs/talos/pull/12631) | **tmpfs** support for STATE & EPHEMERAL volumes | Enables running Talos on devices with **no persistent storage** |
| [Talos #12585](https://github.com/siderolabs/talos/pull/12585) | **Opaque mount options** for volumes | Unblocks advanced FS options like `noatime` / secure mounts |
| [Talos #12085](https://github.com/siderolabs/talos/pull/12085) | Configurable **dashboard console** device | Dashboard access over serial console for headless servers |
| [Omni #2033](https://github.com/siderolabs/omni/pull/2033) | Image **digest pinning** for K8s components | Hardens the supply chain against compromised registries |
| [Omni #1976](https://github.com/siderolabs/omni/pull/1976) | `omnictl` **multi-directory** apply | `kubectl`-style ergonomics for multi-cluster config |
| [Incus #3162](https://github.com/lxc/incus/pull/3162) | **Per-project storage pool** restrictions | Proper multi-tenant storage isolation |
| [Incus OS #1135](https://github.com/lxc/incus-os/pull/1135) | API endpoint for **signed recovery scripts** | Run recovery without reboot or temporary mounts |

<details>
<summary><strong>More contributions</strong></summary>

**Talos Linux**
- [#12504](https://github.com/siderolabs/talos/pull/12504) - Kubespan as a multi-document config type (cleaner WireGuard mesh config)
- [#12751](https://github.com/siderolabs/talos/pull/12751) - Safer `talos upgrade` by removing the image parameter to avoid node-bricking
- [#1384](https://github.com/siderolabs/talos/pull/1384) - Built & packaged the `perf` binary for the Talos kernel
- [go-blockdevice #144](https://github.com/siderolabs/go-blockdevice/pull/144) - LUKS2 header validation (per Trail of Bits research)

**Omni**
- [#1986](https://github.com/siderolabs/omni/pull/1986) - Cluster-validity checks in `omnictl kubeconfig`
- [#2353](https://github.com/siderolabs/omni/pull/2353) - Fixed Docker Compose startup via required SQLite storage flag
- [#2062](https://github.com/siderolabs/omni/pull/2062) - Grafana dashboards for new Omni metrics
- Backend refactors: [#2060](https://github.com/siderolabs/omni/pull/2060) · [#2079](https://github.com/siderolabs/omni/pull/2079) · [#2083](https://github.com/siderolabs/omni/pull/2083) · [#2088](https://github.com/siderolabs/omni/pull/2088) · [#2091](https://github.com/siderolabs/omni/pull/2091)

**Incus OS**
- [#1037](https://github.com/lxc/incus-os/pull/1037) - Manual DNS cache flush via CLI
- [#1049](https://github.com/lxc/incus-os/pull/1049) - Human-readable `info` subcommands for system endpoints
- [#1140](https://github.com/lxc/incus-os/pull/1140) - Expose pending/prior OS version on the `/1.0` endpoint

</details>

#### 🧠 Engineering Philosophy in Public

- **Design in the open, before the diff.**: For infra-critical features (NAT, mount options, image
  pinning) I lead with the design discussion so maintainers can weigh trade-offs early.
- **Document the "why," not just the "what."**: Every non-trivial PR explains the operational
  scenario it unblocks, so reviewers and future readers understand intent easily.

---

### 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=pranav767&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</p>

---

### ✍️ Writing

I write about Kubernetes internals, immutable operating systems, and Go systems programming on my blog.

➡️ **[0xpranav.hashnode.dev](https://0xpranav.hashnode.dev)**

---

### 📫 Connect

- 💼 LinkedIn: [pranav-patil](https://www.linkedin.com/in/pranav-patil-4b70071b9/)
- 📝 Blog: [0xpranav.hashnode.dev](https://0xpranav.hashnode.dev)
- 🐙 GitHub: [@pranav767](https://github.com/pranav767)
- 💻 Twitter: [pranav767](https://x.com/pranavv767)
