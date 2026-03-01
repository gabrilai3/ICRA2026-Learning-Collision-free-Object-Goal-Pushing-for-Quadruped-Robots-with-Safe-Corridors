# Learning Collision-free Object Goal Pushing for Quadruped Robots with Safe Corridors

> **🚧 Code Release Coming Soon — Estimated September 2026 🚧**

Official implementation of the ICRA 2026 paper:
**"Learning Collision-free Object Goal Pushing for Quadruped Robots with Safe Corridors"**

---

## Overview

This repository contains the code for learning collision-free object-goal pushing behaviors for quadruped robots using safe corridor constraints. Our approach enables a legged robot to push objects to target goal positions while safely navigating around obstacles by constructing safe corridors in the environment.

## Key Features

- **Safe Corridor Construction**: Automatically generates collision-free corridors to guide the pushing trajectory.
- **Reinforcement Learning**: Trains a pushing policy that respects safe corridor constraints.
- **Quadruped Robot Support**: Designed and tested for quadruped robotic platforms.
- **Collision-free Navigation**: Ensures the robot and object remain within safe regions throughout the task.

## Citation

If you find this work useful, please consider citing our paper:

```bibtex
@inproceedings{icra2026pushing,
  title     = {Learning Collision-free Object Goal Pushing for Quadruped Robots with Safe Corridors},
  booktitle = {2026 IEEE International Conference on Robotics and Automation (ICRA)},
  year      = {2026}
}
```

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file included in this repository.
