# ROS integration for Franka Emika research robots

[![Build Status][travis-status]][travis]

See the [Franka Control Interface (FCI) documentation][fci-docs] for more information.

## License

All packages of `franka_ros` are licensed under the [Apache 2.0 license][apache-2.0].

[apache-2.0]: https://www.apache.org/licenses/LICENSE-2.0.html
[fci-docs]: https://frankaemika.github.io/docs
[travis-status]: https://travis-ci.org/frankaemika/franka_ros.svg?branch=kinetic-devel
[travis]: https://travis-ci.org/frankaemika/franka_ros

## Changes

Adapted to work with a simulated (https://github.com/kingjin94/enhanced_simulation) and real panda robot (https://github.com/kingjin94/real_robot_explorer)

This included:

 * Addition of a camera, bumper sensors and a probing tool to the robot model
 * Adapting the joint limits, safety controller gains
