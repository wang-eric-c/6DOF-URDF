# 6DOF-URDF

Hi everyone! This is version 1 of the URDF for my robotic arm, I'm currently moving it to SIM so there isn't going to be much support and I'm currently designing the gripper. But if you want to test it out here are some instructions:

<img width="932" height="864" alt="image" src="https://github.com/user-attachments/assets/c2904d03-a27e-45c5-851e-33d63dabbfcf" />

Chain: `base_link` → `Shoulder` → `UA` → `Elbow` → `Roll` → `Yaw` → `Gripper`

## ROS 2

The ROS 2 package is `6DOF_URDF_description/`. Everything you need is in there —
copy that folder into your workspace and build it:

```bash
cp -r 6DOF_URDF_description ~/ros2_ws/src/
cd ~/ros2_ws
colcon build --packages-select 6DOF_URDF_description
source install/setup.bash
ros2 launch 6DOF_URDF_description display.launch.py
```

That opens RViz with a slider per joint.

## Browser viewer

<https://viewer.robotsfan.com/> renders the arm with draggable joints, no ROS
needed. It reads from local disk, so clone or download the repo first:

```bash
git clone https://github.com/wang-eric-c/6DOF-URDF.git
```

Then open the viewer, pick **URDF** (not XACRO), and drag the whole
`6DOF_URDF_description` folder onto the page. Drop the folder, not just the
`.urdf` file — the meshes are referenced by relative path and won't load
otherwise.
