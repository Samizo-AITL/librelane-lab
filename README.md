# librelane-lab

An open-source ASIC flow laboratory focused on learning and experimenting with
LibreLane, OpenROAD, Yosys, and modern open silicon workflows.

## Overview

This repository is intended as a practical laboratory for exploring the
open-source digital ASIC toolchain. The goal is to document experiments,
example designs, and reproducible workflows using industry-inspired EDA tools.

Topics include:

- LibreLane flow
- OpenROAD physical design
- Yosys synthesis
- RTL-to-GDSII automation
- ASIC implementation experiments
- Open PDK based workflows
- CI/CD for hardware projects

## Objectives

- Learn the complete RTL-to-GDSII flow.
- Build reproducible ASIC implementation pipelines.
- Experiment with timing, floorplanning, placement, routing, and signoff.
- Share educational examples and documentation.
- Create reusable templates for future open silicon projects.

## Planned Repository Structure

```
librelane-lab/
├── docs/              # Documentation
├── examples/          # Example RTL projects
├── scripts/           # Automation scripts
├── configs/           # LibreLane/OpenROAD configuration files
├── flows/             # Flow experiments
├── results/           # Generated outputs (optional)
└── README.md
```

## Toolchain

This project primarily targets the following open-source tools:

| Tool | Purpose |
|------|----------|
| LibreLane | End-to-end ASIC flow |
| OpenROAD | Physical design automation |
| Yosys | RTL synthesis |
| Magic | Layout visualization and verification |
| Netgen | LVS |
| OpenSTA | Static timing analysis |

## Requirements

Recommended environment:

- Linux (Ubuntu 22.04+)
- Docker
- Git
- Python 3.10+
- GNU Make

## Getting Started

Clone the repository:

```bash
git clone https://github.com/Samizo-AITL/librelane-lab.git
cd librelane-lab
```

Future setup instructions and example flows will be added as the project evolves.

## Roadmap

- [ ] Initial repository structure
- [ ] LibreLane setup guide
- [ ] Sample RTL project
- [ ] OpenROAD integration
- [ ] CI workflow
- [ ] Automated regression tests
- [ ] Example RTL-to-GDSII flow
- [ ] Documentation site

## Contributing

Contributions, suggestions, and issue reports are welcome.

Please open an issue or submit a pull request if you would like to improve the project.

## License

This project will be released under an open-source license.
A specific license file (`LICENSE`) will be added in a future update.

---

**librelane-lab** aims to serve as a hands-on environment for learning and experimenting with open-source ASIC design flows while promoting reproducibility and collaboration.
