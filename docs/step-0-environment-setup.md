
# Step 0 — Environment Setup

## 1. Development Environment

The development environment was successfully prepared with the following tools:

| Component | Installed Version |
|---|---|
| Operating System | Ubuntu 26.04.1 LTS |
| ROS 2 Distribution | Lyrical |
| Gazebo Sim | 10.5.0 |
| Git | 2.53.0 |

## 2. ROS 2 Communication Test

The ROS 2 communication test was successfully completed using the `demo_nodes_cpp` package.

Two terminals were opened:

- **Talker:** `ros2 run demo_nodes_cpp talker`
- **Listener:** `ros2 run demo_nodes_cpp listener`

The talker successfully published messages, and the listener received them.

**Evidence:** `screenshots/step-0/ros2-communication.png`

## 3. Gazebo Simulation Test

Gazebo Sim was successfully launched using:

```bash
gz sim
```

The simulator opened correctly and displayed its default world.

**Evidence:** `screenshots/step-0/gazebo-launch.png`

## 4. Environment Information

The installed software versions were checked and recorded.

**Evidence:** `screenshots/step-0/environment-versions.png`

## 5. Step 0 Status

- [x] Ubuntu environment available
- [x] ROS 2 installed and accessible
- [x] Gazebo Sim installed and accessible
- [x] ROS 2 talker and listener communication verified
- [x] Gazebo Sim successfully launched
- [x] Evidence collected

**Status: COMPLETED**
