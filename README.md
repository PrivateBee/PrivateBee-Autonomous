# Private Bee Autonomous

## Project Description 

GPS 4D is an innovative navigation system designed for **drones**, **air taxis**, and more generally for **next-generation aircraft** used in urban air mobility.

Unlike traditional navigation systems that rely on three-dimensional positioning (latitude, longitude, altitude), GPS 4D introduces a fourth essential dimension: **time**.

The objective of this project is to design a system capable of **planning**, **optimizing**, and **monitoring** aerial trajectories while simultaneously considering:

- **airspace geometry**,
- **regulatory constraints**,
- **real-time weather conditions**,
- **movements of other aircraft**,
- and **the urgency level of the mission**.

The system computes the **optimal trajectory** not only in **space** but also in **time**, in order to ensure **safer**, **faster**, and **more efficient** flights. It is also designed to dynamically adapt to **unexpected events** such as potential collisions, weather changes, restricted airspaces, or emergency situations.

---

## Repository Purpose

This repository serves as the central integration hub for the GPS 4D project, acting as a autonomous drone pilot, integrates all flight control logic and autonomous decision-making algorithms for the GPS 4D. Its goal is to provide a robust framework for high-level mission execution, allowing aircraft to navigate complex environments without human intervention while strictly adhering to 4D trajectory constraints.

Within the Private Bee ecosystem, this repository focuses on:

- Autonomous Pathfinding: Implementing real-time trajectory generation that accounts for the 4th dimension (Time) to ensure deconfliction and punctual arrivals.

- Sensor Fusion & Perception: Consolidating data from onboard sensors to maintain constant situational awareness and detect environmental changes.

- Behavioral Logic: Managing the transition between flight phases (take-off, cruising, landing, crash) and executing automated responses to mission updates or system alerts.

- Onboard Edge Computing: Hosting the core pilot software designed to run on embedded hardware, ensuring low-latency processing for critical flight maneuvers.

---

## Repository Structure <!-- Adapt the structure with your project's structure -->

```
privatebee-template/
├── .github/                        -> GitHub configuration files
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug-report.yml          -> Bug report issue template
│   │   ├── config.yml              -> Issue template configuration
│   │   └── new-feature.yml         -> Feature request issue template
│   └── PULL_REQUEST_TEMPLATE.md    -> Pull request template
├── .gitignore                      -> Git ignore rules
├── LICENSE.md                      -> Project license
└── README.md                       -> Project overview and documentation
```

---

## Getting Started

Before contributing, please go to the [Documentation Repository](https://github.com/PrivateBee/privatebee-docs), read the **README** file, and read subsequent files if necessary.

---

## Prerequisites

<!-- Complete this part with your project's prerequisites -->
<!-- Prerequisites are libraries, software, and tools that must be installed to work on this project -->

---

## Compilation / Build

<!-- Complete this part with instructions on how to compile/build your project -->

Example:
```bash
npm install
npm run build
```

---

## Installation

<!-- Complete this part with instructions on how to install your project -->

Example:
```bash
git clone https://github.com/PrivateBee/PrivateBee-Autonomous.git
cd your-repository
npm install
```

---

## Project Status / Progress <!-- Complete this part with your project's progress -->

| Task                                             |   Status   |
| ------------------------------------------------ | :--------: |
| Task 1                                           | [Completed] |
| Task 2                                           | [Completed] |
| Task 3                                           | [In Progress] |
| Task 4                                           | [In Progress] |
| Task 5                                           | [To Do] |
| Task 6                                           | [To Do] |

---

## License

This project is licensed under the terms described in the [LICENSE](./LICENSE.md) file.

---

## Support and Contact

If you have any questions or remarks about this repository, please **open an issue** in this repository or contact the **project maintainers via Discord**.

---