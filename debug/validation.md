# Validation Report: 6DOF_URDF

## Status: PASS (with warnings)

## Summary

| Metric | Value |
|--------|-------|
| Links | 7 |
| Joints | 6 |
| Assemblies | 10 |
| Root | `base_link` |
| Errors | 0 |
| Warnings | 4 |

## Warnings

- Multi-parent link detected (child=!frame_elbow:1): keeping 'Revolute_29' as the URDF tree parent; routing ['Rigid_55'] to ``closing_joints`` (sidecar) — closed kinematic loop.  Tag the loop-closing joint(s) with prefix ``!closing_*`` in Fusion to make the choice explicit and avoid this warning.
- Multi-parent link detected (child=!frame_roll:1): keeping 'Revolute_37' as the URDF tree parent; routing ['Rigid_56'] to ``closing_joints`` (sidecar) — closed kinematic loop.  Tag the loop-closing joint(s) with prefix ``!closing_*`` in Fusion to make the choice explicit and avoid this warning.
- Multi-parent link detected (child=!frame_yaw:1): keeping 'Revolute_43' as the URDF tree parent; routing ['Rigid_57'] to ``closing_joints`` (sidecar) — closed kinematic loop.  Tag the loop-closing joint(s) with prefix ``!closing_*`` in Fusion to make the choice explicit and avoid this warning.
- Root link renamed: 'Base' → 'base_link' (REP 120 convention). Consider renaming the component to 'base_link' in Fusion.

## Kinematic Tree

```
base_link [convex_hull]
  └─ Revolute_5 [revolute]
    Shoulder [BAKE] [convex_hull]
      └─ Revolute_13 [revolute]
        UA [BAKE] [convex_hull]
          └─ Revolute_29 [revolute]
            Elbow [BAKE] [convex_hull]
              └─ Revolute_37 [revolute]
                Roll [BAKE] [convex_hull]
                  └─ Revolute_43 [revolute]
                    Yaw [BAKE] [convex_hull]
                      └─ Revolute_46 [continuous]
                        Gripper [BAKE] [convex_hull]
```

## Collision Geometry

| Link | Source | Shape/File |
|------|--------|------------|
| `Elbow` | convex hull STL | `meshes/6DOF_URDF/Elbow_collision.stl` |
| `Gripper` | convex hull STL | `meshes/6DOF_URDF/Gripper_collision.stl` |
| `Roll` | convex hull STL | `meshes/6DOF_URDF/Roll_collision.stl` |
| `Shoulder` | convex hull STL | `meshes/6DOF_URDF/Shoulder_collision.stl` |
| `UA` | convex hull STL | `meshes/6DOF_URDF/UA_collision.stl` |
| `Yaw` | convex hull STL | `meshes/6DOF_URDF/Yaw_collision.stl` |
| `base_link` | convex hull STL | `meshes/6DOF_URDF/base_link_collision.stl` |

## Mesh Bake Offsets

Links where joint frame ≠ component origin. Visual/inertial/collision origins shifted.

| Link | Offset (mm) |
|------|-------------|
| `UA` | (0.0, 0.0, 0.0) |
| `Elbow` | (0.0, 0.0, 0.0) |
| `Roll` | (0.0, 0.0, 0.0) |
| `Yaw` | (0.0, 0.0, 0.0) |
| `Gripper` | (0.0, 0.0, 0.0) |
| `Shoulder` | (0.0, 0.0, 0.0) |
