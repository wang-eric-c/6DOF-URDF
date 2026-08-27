# Validation Report: 6DOF_URDF

## Status: PASS (with warnings)

## Summary

| Metric | Value |
|--------|-------|
| Links | 6 |
| Joints | 5 |
| Assemblies | 10 |
| Root | `base_link` |
| Errors | 0 |
| Warnings | 4 |

## Warnings

- Joint 'Revolute_29' is internal to a rigid group (both endpoints → 6DOF_URDF/Elbow_Connector_Passive).  Dropped — rigid groups represent one rigid body, joints between members are ignored.  Move this joint to assemble between rigid groups instead.
- Joint 'Revolute_46' is internal to a rigid group (both endpoints → 6DOF_URDF/20mm).  Dropped — rigid groups represent one rigid body, joints between members are ignored.  Move this joint to assemble between rigid groups instead.
- Multi-parent link detected (child=Base Motor:1): keeping 'Revolute_5' as the URDF tree parent; routing ['Rigid_14'] to ``closing_joints`` (sidecar) — closed kinematic loop.  Tag the loop-closing joint(s) with prefix ``!closing_*`` in Fusion to make the choice explicit and avoid this warning.
- Root link renamed: 'Base_1' → 'base_link' (REP 120 convention). Consider renaming the component to 'base_link' in Fusion.

## Kinematic Tree

```
base_link [convex_hull]
  └─ Revolute_5 [revolute]
    Base_Motor [BAKE] [convex_hull]
      └─ Revolute_13 [revolute]
        UA_Motor [BAKE] [convex_hull]
          └─ Rigid_25 [fixed]
            Elbow_Connector_Passive [convex_hull]
              └─ Revolute_37 [revolute]
                Roll_Housing [BAKE] [convex_hull]
                  └─ Revolute_43 [revolute]
                    20mm [BAKE] [convex_hull]
```

## Collision Geometry

| Link | Source | Shape/File |
|------|--------|------------|
| `20mm` | convex hull STL | `meshes/6DOF_URDF/20mm_collision.stl` |
| `Base_Motor` | convex hull STL | `meshes/6DOF_URDF/Base_Motor_collision.stl` |
| `Elbow_Connector_Passive` | convex hull STL | `meshes/6DOF_URDF/Elbow_Connector_Passive_collision.stl` |
| `Roll_Housing` | convex hull STL | `meshes/6DOF_URDF/Roll_Housing_collision.stl` |
| `UA_Motor` | convex hull STL | `meshes/6DOF_URDF/UA_Motor_collision.stl` |
| `base_link` | convex hull STL | `meshes/6DOF_URDF/base_link_collision.stl` |

## Mesh Bake Offsets

Links where joint frame ≠ component origin. Visual/inertial/collision origins shifted.

| Link | Offset (mm) |
|------|-------------|
| `Base_Motor` | (0.0, 0.0, -0.6) |
| `UA_Motor` | (-77.1, -123.0, 60.4) |
| `Roll_Housing` | (41.2, -283.5, -47.5) |
| `20mm` | (-184.4, 172.6, -69.4) |
