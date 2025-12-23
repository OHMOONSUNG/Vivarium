# Vivarium

> **An Open-Source Artificial Life IDE for Evolutionary Simulation**

Vivarium is a high-performance, modular development environment built with **Rust** and **Bevy**. It is designed to simulate complex biological systems and agent-based models on a hexagonal grid, providing a sandbox for structural ALife (Artificial Life) research.



## Vision
Vivarium aims to be more than just a simulation; it is an **Evolutionary IDE**. Our goal is to provide a platform where researchers and developers can define, branch, and evolve synthetic life forms through a deterministic tick-based system.

##  Key Features
* **Hexagonal Spatial Engine**: Optimized 2D/3D grid system for organic agent movement.
* **Dynamic Rule Engine**: Define agent behaviors (`var1`, `var2`, `var3`) and environmental rules in real-time.
* **Deterministic Tick System**: Full control over simulation time, allowing for perfect reproducibility and branching.
* **Open Ecosystem**: A collaborative platform where everyone can contribute rulesets and agents.

## Tech Stack
* **Language**: [Rust](https://www.rust-lang.org/)
* **Engine**: [Bevy Engine](https://bevyengine.org/)
* **Coordinate System**: [Hexx](https://github.com/ManevilleF/hexx)

##  Getting Started

### Prerequisites
Ensure you have the Rust toolchain installed:
```bash
curl --proto '=https' --tlsv1.2 -sSf [https://sh.rustup.rs](https://sh.rustup.rs) | sh
Installation
Clone the repository:

Bash

git clone [https://github.com/YOUR_USERNAME/vivarium.git](https://github.com/YOUR_USERNAME/vivarium.git)
Run the project:

Bash

cargo run --release
🤝 Contributing
Vivarium is an open-source project. We welcome all contributions! Please read our CONTRIBUTING.md (coming soon) and feel free to open a Pull Request. Since we prioritize structural integrity, all changes must pass through our Branch Rulesets and code review.

📜 License
This project is licensed under the MIT License (or Apache 2.0).
