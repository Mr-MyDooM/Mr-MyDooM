<h1 align="center">🛠️ Not a Dev. Not an Engineer.</h1>
<p align="center">
  <i>Just a bored SRE who builds Linux desktop apps and writes Rust until it compiles.</i>
</p>

<p align="center">
  <img alt="Rust" src="https://img.shields.io/badge/Rustacean-%F0%9F%A6%80-orange?style=flat-square">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-first-black?style=flat-square&logo=linux">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-%E2%98%BD%EF%B8%8F-blue?style=flat-square&logo=kubernetes">
  <img alt="coffee" src="https://img.shields.io/badge/Coffee-overclocked-brown?style=flat-square">
</p>

---

## 🧑‍💻 Who I Am  

Just a **Site Reliability Engineer who got bored** and started building Linux desktop apps for fun.  
Now I'm deep into **Rust + QML**, drinking too much coffee, and dealing with **very questionable error handling**.

> 💡 _Engineer by heart. Degree? Yes — just not the kind that prepares you for lifetimes of `lifetimes` or why the **borrow checker** hates you._

---

I’ve scaled more pods than a Kubernetes dashboard in crisis, debugged production with only `journalctl` and sheer panic,  
and lived through enough `man` pages and Stack Overflow threads to earn a PhD in _"it worked on my machine."_  

💻 **Linux-first. Rust-second. Sanity… somewhere in swap.**  
🛠️ I make servers behave and desktops do new tricks.  
🧘 Calm during kernel panics — but panics on `unwrap(None)` during `cargo run`.  
🪟 If it breaks on Windows… yeah, probably not my fault.  
📦 _"It works on my Nix shell 🐚" is the new "it works on my machine."_

---

## 🔍 Philosophy  

- Code should fail loudly, log usefully, and compile eventually.  
- If it’s not observable, it doesn’t exist.  
- Everything should have a `--help` flag.  
- Never trust anything that works _only_ on staging.

---

## 🧘 SRE Brain, Rust Fingers  

<details>
<summary><strong>🛠️ Rust Habits</strong></summary>
<br>

🧵 Async where it matters. Blocking where it counts.  
🚨 Panics on `_unwrap(None)` during `cargo run`.  
🛠️ `cargo check`, `cargo clippy`, `cargo fix`... in that order.  
🎯 `cargo check` before `cargo pray`.  
📚 Reads `std::error::Error` like bedtime poetry.  
🧪 `Result<T, E>` believer. Retries with backoff.  
🔁 Never forgets to `impl Retryable` on life lessons.  
👣 Follows traces like a bloodhound through `tokio` tasks.  
🕵️‍♂️ Logs in JSON, thinks in traces.  
📉 Metrics before mutability.  
🔥 Tests in prod — but safely.

</details>

<details>
<summary><strong>☸️ Kubernetes / SRE Mindset</strong></summary>
<br>

🧘 Calm during kernel panics.  
💾 Hates state, trusts `etcd`.  
🔒 Ingress locked tighter than prod secrets.  
📦 Sidecars are friends. InitContainers are therapy.  
🔁 Can roll back a broken `CDR` in <30s.  
📊 Prometheus whisperer. Reads Grafana like tarot.  
🌐 DNS broken? Probably `CoreDNS` again.  
🛑 Won’t deploy if `livenessProbe` isn’t passing.  
📉 Knows when to `scale down`, when to `evict`.  
🐳 Doesn’t trust anything that runs outside the cluster.  
☸️ Speaks fluent `kubectl`, dreams in YAML.  
🔍 If it’s not in `otel`, did it even happen?

</details>

<details>
<summary><strong>🧯 Production Mindset</strong></summary>
<br>

👷 Builds infra like Rust: safe, concurrent, no undefined behavior.  
📦 Rolls out with canary, rolls back with `git revert`.  
🔍 RCA enthusiast — blameless, but thorough.  
⏱️ Latency budget is sacred.  
🔧 Owns the on-call pager and the panic trace.  
🙏 Prometheus, Alertmanager, and the occasional prayer.

</details>

---

## 🧰 Stack & Tools I Actually Use  

### 🧠 Languages & Markup  
`Rust` 🦀, `QML`, `TOML`, `YAML`, `HTML`, `JSON`

### 🛠️ Dev & Terminal Tools  
- `Neovim` + `LSP`, `tmux`, `cargo`, `ripgrep`, `lazygit`, `RustRover`  
- Shells: `fish` (with `omf`), also `bash` when necessary  
- Prompt: `starship`  
- CLI favorites: `fd`, `rg`, `bat`, `exa`, `zoxide`, `lsd`, `ranger`, `tldr`, `jq`

### ☸️ Kubernetes & Infra Stack  
- Clusters: `Kubernetes`, `Podman`, `Docker`, `systemd`, `Flatpak`, `D-Bus`  
- Tools: `k9s`, `kubectl`, `stern`, `Lens`, `Helm`, `minikube`, `kind`  
- Monitoring: `Prometheus`, `Alertmanager`, `Grafana`  
- Tracing: `OpenTelemetry`, `Jaeger`, `Tempo`, `bpftrace`, `strace`  
- Debugging: `journalctl`, `htop`, `ctop`, `ncdu`, `dig`, `ip`

### 📦 Infrastructure as Code (IaC)  
- `Terraform` — when I *have* to use the cloud  
- `Ansible` — config that survives longer than me  
- `Pulumi` — IaC with types? yes.  
- `Helm` — the only Helm chart I don’t hate is mine  
- `Nix` — declarative setups, reproducible everything  

### 🚀 CI/CD Stack  
- `GitHub Actions` — the reliable default  
- `Argo CD` — GitOps, minus the pain  
- `Flux`, `Drone`, `Earthly` — when YAML doesn’t suck

### 🛡️ DevSec / Security Tools  
- `Trivy` — scan first, deploy later  
- `Clippy` — petty, but right  
- `cargo-audit` — because supply chains are scary  
- `Dockle` — container linting because I forget flags  
- `gitleaks` — secrets belong in vaults, not Git  
- `pre-commit` — guards against 3 AM commits

### 🖼 GUI App Stack  
- `Qt` / `QML` — for Linux-native UI  
- `Tauri` — Rust meets web UI without Electron bloat  
- Desktop Envs: `KDE Plasma`, `Sway` (Wayland > X)

### 🗃️ Databases I Actually Trust  
- `PostgreSQL` — when structure matters  
- `Redis` — for fast, ephemeral chaos  
> _I don’t trust any DB that doesn’t survive a power cut or `SIGKILL`._

---

## 📌 Work in Progress  

➡️ **WhisperDesk** — WhatsApp-style encrypted messaging app (Rust + QML)  
➡️ Flatpak builds — because I use them  
➡️ Sysadmin CLI tools — built from rage and repetition  
➡️ Dotfiles & theming — terminal & KDE configs  
➡️ Contributing to openSUSE tooling — someday soon™

---

## 🧯 Bonus Facts  

- Yes, I’ve used `etcd` in prod.  
- No, I don’t enjoy YAML.  
- I have beef with `Cargo.lock`.  
- I believe `panic!()` should print a dad joke.  
- I’ll fix my README... eventually.

---

_This README is a living document — kinda like my dotfiles: never done, just slightly less broken each time._
