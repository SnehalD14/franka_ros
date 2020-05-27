# ROS integration for Franka Emika research robots

[![Build Status][travis-status]][travis]

See the [Franka Control Interface (FCI) documentation][fci-docs] for more information.

## License

All packages of `franka_ros` are licensed under the [Apache 2.0 license][apache-2.0].

[apache-2.0]: https://www.apache.org/licenses/LICENSE-2.0.html
[fci-docs]: https://frankaemika.github.io/docs
[travis-status]: https://travis-ci.org/frankaemika/franka_ros.svg?branch=kinetic-devel
[travis]: https://travis-ci.org/frankaemika/franka_ros

## Modifications

Changes were made to integrate Franka Emika with Gazebo and Moveit. Main changes made:

1. **Camera link** was added [panda xacro](franka_description/robots/panda_arm_hand.urdf.xacro)
2. **Friction Coefficient** for the fingers was added to [panda gazebo](franka_description/robots/panda.gazebo.xacro)
