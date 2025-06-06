# kinematic_pose_msgs

This package provides the Kinematic Pose message, for dynamic pose tracking.

* [KinematicPose](msg/KinematicPose.msg): Expresses a moving pose with velocity (twist) and acceleration at that point in free space.

## Elements

1. pose (Pose): position (`geometry_msgs/Point`) and orientation (`geometry_msgs/Quaternion`);
2. pose_twist (Twist): linear and angular velocities (both `geometry_msgs/Vector3`);
3. pose_accel (Accel): linear and angular accelerations (both `geometry_msgs/Vector3`).
