# kinematic_pose_msgs

This package provides the Kinematic Pose message, for dynamic pose tracking.

- Depends on [geometry_msgs](https://github.com/ros2/common_interfaces/tree/rolling/geometry_msgs)

* [KinematicPose](msg/KinematicPose.msg): Expresses a moving pose with velocity (twist) and acceleration at that point in free space.

## Elements

1. pose (Pose): position (`geometry_msgs/Point`) and orientation (`geometry_msgs/Quaternion`);
2. pose_velocity (Twist): linear and angular (both `geometry_msgs/Vector3`);
3. pose_acceleration (Accel): linear and angular (both `geometry_msgs/Vector3`).
