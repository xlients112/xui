# 📦 xserve container manager

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/License-GNU_General_Public_License_v3.0-5A0E3B" alt="License" />
</p>

## 📄 Description

**xserve container manager** is a modern, lightweight, and high-performance container management tool built from the ground up to be **simple, clean, faster, and secure**. 

Engineered entirely in Rust, `xserve` provides bare-metal performance and strict memory safety, ensuring minimal overhead while managing your containerized workloads.

---

## ✨ Key Features

* **OCI Standard Compliant** – Full compatibility with Open Container Initiative (OCI) images and runtimes.
* **Built Entirely in Rust** – Harnesses the power of Rust for unmatched speed, zero-cost abstractions, and memory safety.
* **Resource Efficient** – Minimal CPU and memory footprint compared to traditional container daemons.
* **Security-First Architecture** – Designed with isolated execution environments and strict permission models.
* **Intuitive CLI** – Clean, human-readable commands that eliminate container management complexity.

---

## 🚀 Getting Started

### Prerequisites
* we supported linux only with Architecture:
* aarch64, x86_64
* this project is development mode (not-stable)

### Installation

You can install `xserve container manager` instantly using our automated setup script. Run the following command in your terminal:

```bash
curl
```

---

## 🛠️ Usage Quickstart

Here are a few basic commands to get you up and running:

### Verify Installation
```bash
xserve --version
```

### Pull an Image
```bash
xserve pull alpine:latest
```

### Run a Container
```bash
xserve run --name my-app -p 8080:80 alpine:latest
```

### List Running Containers
```bash
xserve ps
```

---

## ⚙️ Configuration

`xserve` works out of the box with zero configuration. However, you can easily customize its behavior by modifying the global configuration file:

```bash
nano ~/.config/xserve/config.toml
```

---

## 🤝 Contributing

Contributions are welcome! Whether it is reporting a bug, proposing new features, or submitting a pull request, your help makes `xserve` better.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.
