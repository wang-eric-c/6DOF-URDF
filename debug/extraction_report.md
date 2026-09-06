# Extraction Report: 6DOF URDF

**Exported:** 2026-09-06T12:14:45.352276
**Exporter:** v3.1.0

## Summary

| Metric | Value |
|--------|-------|
| Occurrences | 98 |
| Subassemblies | 15 |
| Leaf components | 83 |
| Joints (total) | 51 |
| As-built joints | 0 |
| Regular joints | 51 |
| Max nesting depth | 1 |

## Assembly Hierarchy

```
[6DOF_URDF]  (design root)
  ├── Base_Connector_Shaft_V2  (315.9g)
  ├── Base_Motor  (498.9g)
  ├── Bearing_Housing_Shoulder_V2  (39.3g)
  ├── Elbow_Belt_Sensorless  (138.4g)
  ├── Elbow_Cap  (1.0g)
  ├── Elbow_Connector_Passive  (11.0g)
  ├── Elbow_Motor  (390.2g)
  ├── Gripper_Shaft  (11.2g)
  ├── Lower_Bottom_Base_Bearing_Ring  (62.2g)
  ├── Lower_Upper_Base_Bearing_Ring  (98.9g)
  ├── Motor_Connector_Shoulder  (28.4g)
  ├── Motor_Housing_Roll  (120.9g)
  ├── Motor_Housing_Yaw  (45.4g)
  ├── Passive_Cap  (7.4g)
  ├── Roll_Motor  (390.2g)
  ├── Shoulder_Bearing_2_Lower  (62.2g)
  ├── Shoulder_Bearing_2_Lower  (62.2g)
  ├── Shoulder_Bearing_2_Lower  (62.2g)
  ├── Shoulder_Bearing_2_Upper  (98.9g)
  ├── Shoulder_Bearing_2_Upper  (98.9g)
  ├── Shoulder_Bearing_2_Upper  (98.9g)
  ├── Shoulder_Cap  (4.9g)
  ├── Shoulder_Motor  (498.9g)
  ├── UA_Motor  (390.2g)
  ├── Upper_arm  (290.9g)
  ├── Yaw_Motor  (139.8g)
  ├── base_link  (274.7g)
  ├── elbow  (0.0g)
  ├── gripper  (0.0g)
  ├── roll  (0.0g)
  ├── shoulder  (0.0g)
  ├── ua  (0.0g)
  ├── yaw  (0.0g)
  [Belt_Shaft]  (depth=0, children=1)
    ├── Component64  (14.8g, Active_Cap_Roll)
  [EG17_G10]  (depth=0, children=13)
    ├── 10circlip_1  (0.2g, Steel)
    ├── 6801_1  (4.6g, Steel)
    ├── EG17_shaft  (157.2g, Steel)
    ├── M3hexagon_socket_head_cap_screw_1  (0.2g, Steel)
    ├── M3hexagon_socket_head_cap_screw_1  (0.2g, Steel)
    ├── M3hexagon_socket_head_cap_screw_1  (0.2g, Steel)
    ├── M3hexagon_socket_head_cap_screw_1  (0.2g, Steel)
    ├── M3hexagon_socket_head_cap_screw_1  (0.2g, Steel)
    ├── M3hexagon_socket_head_cap_screw_1  (0.2g, Steel)
    ├── M3hexagon_socket_head_cap_screw_1  (0.2g, Steel)
    ├── M3hexagon_socket_head_cap_screw_1  (0.2g, Steel)
    ├── input_shaft_1  (5.8g, Steel)
    ├── nema17input_flange_1  (126.7g, Steel)
  [EG17_G50]  (depth=0, children=13)
    ├── 10circlip  (0.2g, Steel)
    ├── 6801  (5.0g, Steel)
    ├── EG17_shaft_2  (239.6g, Steel)
    ├── M3hexagon_socket_head_cap_screw  (0.2g, Steel)
    ├── M3hexagon_socket_head_cap_screw  (0.2g, Steel)
    ├── M3hexagon_socket_head_cap_screw  (0.2g, Steel)
    ├── M3hexagon_socket_head_cap_screw  (0.2g, Steel)
    ├── M3hexagon_socket_head_cap_screw  (0.2g, Steel)
    ├── M3hexagon_socket_head_cap_screw  (0.2g, Steel)
    ├── M3hexagon_socket_head_cap_screw  (0.2g, Steel)
    ├── M3hexagon_socket_head_cap_screw  (0.2g, Steel)
    ├── input_shaft  (6.3g, Steel)
    ├── nema17input_flange  (138.0g, Steel)
  [GT2_400mm_Motor_Connector]  (depth=0, children=1)
    ├── Component54  (12.9g, PETG_10_Grid_UA_Gear)
  [GT2_Elbow_Connector]  (depth=0, children=1)
    ├── Component52  (25.9g, PETG_25_Gryoid_ECA)
  [Roll_Bearing_2]  (depth=0, children=2)
    ├── HR32906J_Inner_ring  (45.1g, Bearing_Steel)
    ├── HR32906J_Inner_ring  (45.1g, Bearing_Steel)
    ├── HR32906J_Inner_ring  (45.1g, Bearing_Steel)
    ├── HR32906J_Inner_ring  (45.1g, Bearing_Steel)
    ├── HR32906J_Inner_ring  (45.1g, Bearing_Steel)
    ├── HR32906J_Inner_ring  (45.1g, Bearing_Steel)
    ├── HR32906J_Inner_ring  (45.1g, Bearing_Steel)
    ├── HR32906J_Outer_ring  (29.4g, Bearing_Steel)
    ├── HR32906J_Outer_ring  (29.4g, Bearing_Steel)
    ├── HR32906J_Outer_ring  (29.4g, Bearing_Steel)
    ├── HR32906J_Outer_ring  (29.4g, Bearing_Steel)
    ├── HR32906J_Outer_ring  (29.4g, Bearing_Steel)
    ├── HR32906J_Outer_ring  (29.4g, Bearing_Steel)
    ├── HR32906J_Outer_ring  (29.4g, Bearing_Steel)
  [Shaft_Connector]  (depth=0, children=1)
    ├── Component58  (28.9g, PET_Plastic)
  [UA_Shaft_COupler]  (depth=0, children=3)
    ├── 92605A009  (0.0g, )
    ├── 92605A009  (0.0g, )
    ├── Connector  (27.7g, Steel)
  [UA_Shaft_Coupler]  (depth=0, children=3)
    ├── 92605A009_1  (0.0g, )
    ├── 92605A009_1  (0.0g, )
    ├── Connector_1  (27.7g, Steel)
```

## Occurrences

### Depth 0

#### 🔧 COMPONENT: `elbow`

| Property | Value |
|----------|-------|
| Full path | `!frame_elbow:1` |
| Component name | !frame_elbow |
| Depth | 0 |
| Path segments | elbow |
| **Transforms** | |
| Global position (m) | (0.122551, -0.102543, 0.215314) |
| Global position (mm) | (122.55, -102.54, 215.31) |
| Local transform (m) | (0.122551, -0.102543, 0.215314) |
| Assembly context depth | 0 |
| transform2 (m) | (0.122551, -0.102543, 0.215314) |
| **Physical** | |
| Mass | 0.000000 kg (0.000 g) |
| Volume | 0.000000e+00 m³ |
| Density | 0.0 kg/m³ |
| Surface area | 0.000000e+00 m² |
| Body count | 0 |
| CoM (component-local, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, mm) | (0.00, 0.00, 0.00) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Bounding box (m) | 0.0000 × 0.0000 × 0.0000 |
| Bounding box (mm) | 0.00 × 0.00 × 0.00 |
| **Material & Appearance** | |
| Material |  |
| Appearance |  |

#### 🔧 COMPONENT: `gripper`

| Property | Value |
|----------|-------|
| Full path | `!frame_gripper:1` |
| Component name | !frame_gripper |
| Depth | 0 |
| Path segments | gripper |
| **Transforms** | |
| Global position (m) | (-0.124345, -0.049506, 0.270208) |
| Global position (mm) | (-124.35, -49.51, 270.21) |
| Local transform (m) | (-0.124345, -0.049506, 0.270208) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.124345, -0.049506, 0.270208) |
| **Physical** | |
| Mass | 0.000000 kg (0.000 g) |
| Volume | 0.000000e+00 m³ |
| Density | 0.0 kg/m³ |
| Surface area | 0.000000e+00 m² |
| Body count | 0 |
| CoM (component-local, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, mm) | (0.00, 0.00, 0.00) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Bounding box (m) | 0.0000 × 0.0000 × 0.0000 |
| Bounding box (mm) | 0.00 × 0.00 × 0.00 |
| **Material & Appearance** | |
| Material |  |
| Appearance |  |

#### 🔧 COMPONENT: `roll`

| Property | Value |
|----------|-------|
| Full path | `!frame_roll:1` |
| Component name | !frame_roll |
| Depth | 0 |
| Path segments | roll |
| **Transforms** | |
| Global position (m) | (0.100980, -0.032643, 0.298969) |
| Global position (mm) | (100.98, -32.64, 298.97) |
| Local transform (m) | (0.100980, -0.032643, 0.298969) |
| Assembly context depth | 0 |
| transform2 (m) | (0.100980, -0.032643, 0.298969) |
| **Physical** | |
| Mass | 0.000000 kg (0.000 g) |
| Volume | 0.000000e+00 m³ |
| Density | 0.0 kg/m³ |
| Surface area | 0.000000e+00 m² |
| Body count | 0 |
| CoM (component-local, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, mm) | (0.00, 0.00, 0.00) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Bounding box (m) | 0.0000 × 0.0000 × 0.0000 |
| Bounding box (mm) | 0.00 × 0.00 × 0.00 |
| **Material & Appearance** | |
| Material |  |
| Appearance |  |

#### 🔧 COMPONENT: `shoulder`

| Property | Value |
|----------|-------|
| Full path | `!frame_shoulder:1` |
| Component name | !frame_shoulder |
| Depth | 0 |
| Path segments | shoulder |
| **Transforms** | |
| Global position (m) | (0.000000, 0.000000, -0.051500) |
| Global position (mm) | (0.00, 0.00, -51.50) |
| Local transform (m) | (0.000000, 0.000000, -0.051500) |
| Assembly context depth | 0 |
| transform2 (m) | (0.000000, 0.000000, -0.051500) |
| **Physical** | |
| Mass | 0.000000 kg (0.000 g) |
| Volume | 0.000000e+00 m³ |
| Density | 0.0 kg/m³ |
| Surface area | 0.000000e+00 m² |
| Body count | 0 |
| CoM (component-local, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, mm) | (0.00, 0.00, 0.00) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Bounding box (m) | 0.0000 × 0.0000 × 0.0000 |
| Bounding box (mm) | 0.00 × 0.00 × 0.00 |
| **Material & Appearance** | |
| Material |  |
| Appearance |  |

#### 🔧 COMPONENT: `ua`

| Property | Value |
|----------|-------|
| Full path | `!frame_ua:1` |
| Component name | !frame_ua |
| Depth | 0 |
| Path segments | ua |
| **Transforms** | |
| Global position (m) | (-0.007100, -0.149900, 0.060400) |
| Global position (mm) | (-7.10, -149.90, 60.40) |
| Local transform (m) | (-0.007100, -0.149900, 0.060400) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.007100, -0.149900, 0.060400) |
| **Physical** | |
| Mass | 0.000000 kg (0.000 g) |
| Volume | 0.000000e+00 m³ |
| Density | 0.0 kg/m³ |
| Surface area | 0.000000e+00 m² |
| Body count | 0 |
| CoM (component-local, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, mm) | (0.00, 0.00, 0.00) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Bounding box (m) | 0.0000 × 0.0000 × 0.0000 |
| Bounding box (mm) | 0.00 × 0.00 × 0.00 |
| **Material & Appearance** | |
| Material |  |
| Appearance |  |

#### 🔧 COMPONENT: `yaw`

| Property | Value |
|----------|-------|
| Full path | `!frame_yaw:1` |
| Component name | !frame_yaw |
| Depth | 0 |
| Path segments | yaw |
| **Transforms** | |
| Global position (m) | (-0.065503, -0.097698, 0.226876) |
| Global position (mm) | (-65.50, -97.70, 226.88) |
| Local transform (m) | (-0.065503, -0.097698, 0.226876) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.065503, -0.097698, 0.226876) |
| **Physical** | |
| Mass | 0.000000 kg (0.000 g) |
| Volume | 0.000000e+00 m³ |
| Density | 0.0 kg/m³ |
| Surface area | 0.000000e+00 m² |
| Body count | 0 |
| CoM (component-local, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, mm) | (0.00, 0.00, 0.00) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Bounding box (m) | 0.0000 × 0.0000 × 0.0000 |
| Bounding box (mm) | 0.00 × 0.00 × 0.00 |
| **Material & Appearance** | |
| Material |  |
| Appearance |  |

#### 🔧 COMPONENT: `Base_Motor`

| Property | Value |
|----------|-------|
| Full path | `Base Motor:1` |
| Component name | Base Motor |
| Depth | 0 |
| Path segments | Base_Motor |
| **Transforms** | |
| Global position (m) | (0.058777, -0.112580, 0.067400) |
| Global position (mm) | (58.78, -112.58, 67.40) |
| Local transform (m) | (0.058777, -0.112580, 0.067400) |
| Assembly context depth | 0 |
| transform2 (m) | (0.058777, -0.112580, 0.067400) |
| **Physical** | |
| Mass | 0.498902 kg (498.902 g) |
| Volume | 1.030788e-04 m³ |
| Density | 4840.0 kg/m³ |
| Surface area | 1.430189e-02 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.000000, -0.000017, 0.030332) |
| CoM (global, m) | (0.058777, -0.112596, 0.097732) |
| CoM (global, mm) | (58.78, -112.60, 97.73) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 6.837719e-04, 6.834972e-04, 1.375650e-04 |
| Ixy, Ixz, Iyz | 2.867839e-10, 1.023765e-10, 5.859788e-08 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 2.247628e-04, 2.244883e-04, 1.375649e-04 |
| Ixy, Ixz, Iyz | 2.867961e-10, 8.000350e-11, -1.915324e-07 |
| Bounding box (m) | 0.0423 × 0.0603 × 0.0840 |
| Bounding box (mm) | 42.32 × 60.31 × 84.00 |
| **Material & Appearance** | |
| Material | Base_Motor |
| Appearance | Opaque_255_255_255 |
| Color (RGB 0-1) | (1.000, 1.000, 1.000) |
| Color (RGB 0-255) | (255, 255, 255) |

#### 🔧 COMPONENT: `Bearing_Housing_Shoulder_V2`

| Property | Value |
|----------|-------|
| Full path | `Bearing Housing Shoulder V2:1` |
| Component name | Bearing Housing Shoulder V2 |
| Depth | 0 |
| Path segments | Bearing_Housing_Shoulder_V2 |
| **Transforms** | |
| Global position (m) | (-0.009385, -0.123499, 0.060400) |
| Global position (mm) | (-9.39, -123.50, 60.40) |
| Local transform (m) | (-0.009385, -0.123499, 0.060400) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.009385, -0.123499, 0.060400) |
| **Physical** | |
| Mass | 0.039267 kg (39.267 g) |
| Volume | 7.465244e-05 m³ |
| Density | 526.0 kg/m³ |
| Surface area | 2.424542e-02 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.000000, -0.007887, 0.000064) |
| CoM (global, m) | (-0.009385, -0.131386, 0.060464) |
| CoM (global, mm) | (-9.39, -131.39, 60.46) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 2.687388e-05, 2.698548e-05, 4.476358e-05 |
| Ixy, Ixz, Iyz | 5.979928e-21, 4.133326e-16, 7.643905e-08 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 2.443108e-05, 2.698532e-05, 4.232093e-05 |
| Ixy, Ixz, Iyz | -2.328525e-16, 4.152143e-16, 5.670045e-08 |
| Bounding box (m) | 0.0700 × 0.0700 × 0.0430 |
| Bounding box (mm) | 70.00 × 70.00 × 43.00 |
| **Material & Appearance** | |
| Material | PETG_20_CH_BSH |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 📦 SUBASSEMBLY: `Belt_Shaft`

| Property | Value |
|----------|-------|
| Full path | `Belt Shaft:1` |
| Component name | Belt Shaft |
| Depth | 0 |
| Path segments | Belt_Shaft |
| Child occurrences | 1 |
| **Transforms** | |
| Global position (m) | (-0.073037, 0.009960, 0.222777) |
| Global position (mm) | (-73.04, 9.96, 222.78) |
| Local transform (m) | (-0.073037, 0.009960, 0.222777) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.073037, 0.009960, 0.222777) |

#### 📦 SUBASSEMBLY: `EG17_G10`

| Property | Value |
|----------|-------|
| Full path | `EG17-G10:1` |
| Component name | EG17-G10 |
| Depth | 0 |
| Path segments | EG17_G10 |
| Child occurrences | 13 |
| **Transforms** | |
| Global position (m) | (0.052248, -0.024063, 0.139266) |
| Global position (mm) | (52.25, -24.06, 139.27) |
| Local transform (m) | (0.052248, -0.024063, 0.139266) |
| Assembly context depth | 0 |
| transform2 (m) | (0.052248, -0.024063, 0.139266) |

#### 📦 SUBASSEMBLY: `EG17_G50`

| Property | Value |
|----------|-------|
| Full path | `EG17-G50:1` |
| Component name | EG17-G50 |
| Depth | 0 |
| Path segments | EG17_G50 |
| Child occurrences | 13 |
| **Transforms** | |
| Global position (m) | (-0.029898, 0.089275, 0.063047) |
| Global position (mm) | (-29.90, 89.28, 63.05) |
| Local transform (m) | (-0.029898, 0.089275, 0.063047) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.029898, 0.089275, 0.063047) |

#### 🔧 COMPONENT: `Elbow_Belt_Sensorless`

| Property | Value |
|----------|-------|
| Full path | `Elbow Belt Sensorless:1` |
| Component name | Elbow Belt Sensorless |
| Depth | 0 |
| Path segments | Elbow_Belt_Sensorless |
| **Transforms** | |
| Global position (m) | (0.074382, -0.034945, 0.287390) |
| Global position (mm) | (74.38, -34.95, 287.39) |
| Local transform (m) | (0.074382, -0.034945, 0.287390) |
| Assembly context depth | 0 |
| transform2 (m) | (0.074382, -0.034945, 0.287390) |
| **Physical** | |
| Mass | 0.138434 kg (138.434 g) |
| Volume | 2.911336e-04 m³ |
| Density | 475.5 kg/m³ |
| Surface area | 6.961989e-02 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.000000, -0.042111, -0.002854) |
| CoM (global, m) | (0.074382, -0.077056, 0.284535) |
| CoM (global, mm) | (74.38, -77.06, 284.54) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 5.281802e-04, 1.299795e-04, 5.580865e-04 |
| Ixy, Ixz, Iyz | 1.437080e-16, 2.290333e-16, -2.345481e-05 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 2.815608e-04, 1.288516e-04, 3.125951e-04 |
| Ixy, Ixz, Iyz | 2.544949e-15, 3.917973e-16, -6.814597e-06 |
| Bounding box (m) | 0.0670 × 0.1464 × 0.0700 |
| Bounding box (mm) | 67.00 × 146.40 × 70.00 |
| **Material & Appearance** | |
| Material | PETG_25_Gyroid_EH |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 🔧 COMPONENT: `Elbow_Cap`

| Property | Value |
|----------|-------|
| Full path | `Elbow Cap:1` |
| Component name | Elbow Cap |
| Depth | 0 |
| Path segments | Elbow_Cap |
| **Transforms** | |
| Global position (m) | (0.100980, -0.032643, 0.298969) |
| Global position (mm) | (100.98, -32.64, 298.97) |
| Local transform (m) | (0.100980, -0.032643, 0.298969) |
| Assembly context depth | 0 |
| transform2 (m) | (0.100980, -0.032643, 0.298969) |
| **Physical** | |
| Mass | 0.000970 kg (0.970 g) |
| Volume | 3.661817e-06 m³ |
| Density | 264.8 kg/m³ |
| Surface area | 2.438492e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.000000, 0.000000, 0.002000) |
| CoM (global, m) | (0.100980, -0.032643, 0.300969) |
| CoM (global, mm) | (100.98, -32.64, 300.97) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 8.066178e-08, 8.066180e-08, 1.509807e-07 |
| Ixy, Ixz, Iyz | 4.703793e-23, -3.706683e-18, -1.763922e-23 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 7.678318e-08, 7.678320e-08, 1.509807e-07 |
| Ixy, Ixz, Iyz | 4.703793e-23, -9.407586e-24, -1.763922e-23 |
| Bounding box (m) | 0.0350 × 0.0350 × 0.0040 |
| Bounding box (mm) | 35.00 × 35.00 × 4.00 |
| **Material & Appearance** | |
| Material | PETG_15_Gyroid |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 🔧 COMPONENT: `Elbow_Connector_Passive`

| Property | Value |
|----------|-------|
| Full path | `Elbow Connector Passive:1` |
| Component name | Elbow Connector Passive |
| Depth | 0 |
| Path segments | Elbow_Connector_Passive |
| **Transforms** | |
| Global position (m) | (0.111341, 0.026973, 0.215314) |
| Global position (mm) | (111.34, 26.97, 215.31) |
| Local transform (m) | (0.111341, 0.026973, 0.215314) |
| Assembly context depth | 0 |
| transform2 (m) | (0.111341, 0.026973, 0.215314) |
| **Physical** | |
| Mass | 0.010964 kg (10.964 g) |
| Volume | 2.076444e-05 m³ |
| Density | 528.0 kg/m³ |
| Surface area | 5.153886e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.000000, 0.000000, 0.009262) |
| CoM (global, m) | (0.111341, 0.026973, 0.224577) |
| CoM (global, mm) | (111.34, 26.97, 224.58) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 2.372988e-06, 2.372988e-06, 1.275592e-06 |
| Ixy, Ixz, Iyz | -3.751666e-22, -1.645391e-16, 7.503331e-22 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.432402e-06, 1.432403e-06, 1.275592e-06 |
| Ixy, Ixz, Iyz | -3.751666e-22, 9.285045e-18, 1.097826e-21 |
| Bounding box (m) | 0.0350 × 0.0350 × 0.0300 |
| Bounding box (mm) | 35.00 × 35.00 × 30.00 |
| **Material & Appearance** | |
| Material | PETG_30_Gyroid_ECP |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 🔧 COMPONENT: `Elbow_Motor`

| Property | Value |
|----------|-------|
| Full path | `Elbow Motor:1` |
| Component name | Elbow Motor |
| Depth | 0 |
| Path segments | Elbow_Motor |
| **Transforms** | |
| Global position (m) | (0.093689, -0.033274, 0.199984) |
| Global position (mm) | (93.69, -33.27, 199.98) |
| Local transform (m) | (0.093689, -0.033274, 0.199984) |
| Assembly context depth | 0 |
| transform2 (m) | (0.093689, -0.033274, 0.199984) |
| **Physical** | |
| Mass | 0.390226 kg (390.226 g) |
| Volume | 8.285048e-05 m³ |
| Density | 4710.0 kg/m³ |
| Surface area | 1.249357e-02 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.000000, -0.000022, 0.023653) |
| CoM (global, m) | (0.093689, -0.033296, 0.223636) |
| CoM (global, mm) | (93.69, -33.30, 223.64) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 3.513838e-04, 3.510934e-04, 1.078761e-04 |
| Ixy, Ixz, Iyz | -3.483183e-10, -1.478300e-10, 3.618025e-07 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.330715e-04, 1.327813e-04, 1.078759e-04 |
| Ixy, Ixz, Iyz | -3.484175e-10, -4.343794e-11, 1.542227e-07 |
| Bounding box (m) | 0.0423 × 0.0603 × 0.0720 |
| Bounding box (mm) | 42.32 × 60.31 × 72.00 |
| **Material & Appearance** | |
| Material | Iron_Wrought |
| Appearance | Opaque_255_255_255 |
| Color (RGB 0-1) | (1.000, 1.000, 1.000) |
| Color (RGB 0-255) | (255, 255, 255) |

#### 📦 SUBASSEMBLY: `GT2_400mm_Motor_Connector`

| Property | Value |
|----------|-------|
| Full path | `GT2 400mm Motor Connector:1` |
| Component name | GT2 400mm Motor Connector |
| Depth | 0 |
| Path segments | GT2_400mm_Motor_Connector |
| Child occurrences | 1 |
| **Transforms** | |
| Global position (m) | (0.257304, -0.117941, 0.100536) |
| Global position (mm) | (257.30, -117.94, 100.54) |
| Local transform (m) | (0.257304, -0.117941, 0.100536) |
| Assembly context depth | 0 |
| transform2 (m) | (0.257304, -0.117941, 0.100536) |

#### 📦 SUBASSEMBLY: `GT2_Elbow_Connector`

| Property | Value |
|----------|-------|
| Full path | `GT2 Elbow Connector:1` |
| Component name | GT2 Elbow Connector |
| Depth | 0 |
| Path segments | GT2_Elbow_Connector |
| Child occurrences | 1 |
| **Transforms** | |
| Global position (m) | (0.136592, -0.123750, 0.112897) |
| Global position (mm) | (136.59, -123.75, 112.90) |
| Local transform (m) | (0.136592, -0.123750, 0.112897) |
| Assembly context depth | 0 |
| transform2 (m) | (0.136592, -0.123750, 0.112897) |

#### 🔧 COMPONENT: `Gripper_Shaft`

| Property | Value |
|----------|-------|
| Full path | `Gripper Shaft:1` |
| Component name | Gripper Shaft |
| Depth | 0 |
| Path segments | Gripper_Shaft |
| **Transforms** | |
| Global position (m) | (-0.098040, -0.048485, 0.248691) |
| Global position (mm) | (-98.04, -48.48, 248.69) |
| Local transform (m) | (-0.098040, -0.048485, 0.248691) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.098040, -0.048485, 0.248691) |
| **Physical** | |
| Mass | 0.011203 kg (11.203 g) |
| Volume | 3.019696e-05 m³ |
| Density | 371.0 kg/m³ |
| Surface area | 7.619092e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.000000, -0.000000, 0.019308) |
| CoM (global, m) | (-0.098040, -0.048485, 0.267999) |
| CoM (global, mm) | (-98.04, -48.48, 268.00) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 6.111915e-06, 6.111915e-06, 1.864791e-06 |
| Ixy, Ixz, Iyz | 0.000000e+00, -8.391962e-17, -1.054445e-21 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.935595e-06, 1.935595e-06, 1.864791e-06 |
| Ixy, Ixz, Iyz | -3.855144e-32, 7.424594e-17, -2.072386e-21 |
| Bounding box (m) | 0.0400 × 0.0400 × 0.0340 |
| Bounding box (mm) | 40.00 × 40.00 × 34.00 |
| **Material & Appearance** | |
| Material | Yaw_Shaft |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 🔧 COMPONENT: `Lower_Bottom_Base_Bearing_Ring`

| Property | Value |
|----------|-------|
| Full path | `Lower Bottom Base Bearing Ring:1` |
| Component name | Lower Bottom Base Bearing Ring |
| Depth | 0 |
| Path segments | Lower_Bottom_Base_Bearing_Ring |
| **Transforms** | |
| Global position (m) | (-0.027200, -0.056181, 0.070740) |
| Global position (mm) | (-27.20, -56.18, 70.74) |
| Local transform (m) | (-0.027200, -0.056181, 0.070740) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.027200, -0.056181, 0.070740) |
| **Physical** | |
| Mass | 0.062154 kg (62.154 g) |
| Volume | 6.939147e-06 m³ |
| Density | 8957.0 kg/m³ |
| Surface area | 5.531252e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.112039, 0.056181, 0.027200) |
| CoM (global, m) | (0.084840, 0.000000, 0.097939) |
| CoM (global, mm) | (84.84, 0.00, 97.94) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 2.958846e-04, 8.537613e-04, 1.003952e-03 |
| Ixy, Ixz, Iyz | -3.912234e-04, -1.894095e-04, -9.497671e-05 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 5.372853e-05, 2.757216e-05, 2.757216e-05 |
| Ixy, Ixz, Iyz | 2.710505e-19, 1.355253e-19, 4.065758e-20 |
| Bounding box (m) | 0.0120 × 0.0620 × 0.0620 |
| Bounding box (mm) | 12.00 × 62.00 × 62.00 |
| **Material & Appearance** | |
| Material | NSK_32908 |
| Appearance | Opaque_128_128_128 |
| Color (RGB 0-1) | (0.502, 0.502, 0.502) |
| Color (RGB 0-255) | (128, 128, 128) |

#### 🔧 COMPONENT: `Lower_Upper_Base_Bearing_Ring`

| Property | Value |
|----------|-------|
| Full path | `Lower Upper Base Bearing Ring:1` |
| Component name | Lower Upper Base Bearing Ring |
| Depth | 0 |
| Path segments | Lower_Upper_Base_Bearing_Ring |
| **Transforms** | |
| Global position (m) | (-0.027200, -0.056181, 0.070740) |
| Global position (mm) | (-27.20, -56.18, 70.74) |
| Local transform (m) | (-0.027200, -0.056181, 0.070740) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.027200, -0.056181, 0.070740) |
| **Physical** | |
| Mass | 0.098851 kg (98.851 g) |
| Volume | 1.103621e-05 m³ |
| Density | 8957.0 kg/m³ |
| Surface area | 9.107294e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.114770, 0.056181, 0.027200) |
| CoM (global, m) | (0.087571, 0.000000, 0.097939) |
| CoM (global, mm) | (87.57, 0.00, 97.94) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 4.387634e-04, 1.403665e-03, 1.642534e-03 |
| Ixy, Ixz, Iyz | -6.373786e-04, -3.085847e-04, -1.510536e-04 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 5.363167e-05, 2.844369e-05, 2.844458e-05 |
| Ixy, Ixz, Iyz | 1.758402e-14, 8.666841e-15, 4.191742e-15 |
| Bounding box (m) | 0.0150 × 0.0577 × 0.0577 |
| Bounding box (mm) | 15.00 × 57.70 × 57.70 |
| **Material & Appearance** | |
| Material | NSK_32908 |
| Appearance | Opaque_128_128_128 |
| Color (RGB 0-1) | (0.502, 0.502, 0.502) |
| Color (RGB 0-255) | (128, 128, 128) |

#### 🔧 COMPONENT: `Motor_Connector_Shoulder`

| Property | Value |
|----------|-------|
| Full path | `Motor Connector Shoulder:1` |
| Component name | Motor Connector Shoulder |
| Depth | 0 |
| Path segments | Motor_Connector_Shoulder |
| **Transforms** | |
| Global position (m) | (-0.022708, 0.030426, 0.060400) |
| Global position (mm) | (-22.71, 30.43, 60.40) |
| Local transform (m) | (-0.022708, 0.030426, 0.060400) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.022708, 0.030426, 0.060400) |
| **Physical** | |
| Mass | 0.028380 kg (28.380 g) |
| Volume | 5.076876e-05 m³ |
| Density | 559.0 kg/m³ |
| Surface area | 1.469832e-02 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.000450, -0.013858, 0.012556) |
| CoM (global, m) | (-0.023159, 0.016568, 0.072956) |
| CoM (global, mm) | (-23.16, 16.57, 72.96) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 2.500451e-05, 1.765981e-05, 2.520169e-05 |
| Ixy, Ixz, Iyz | -3.579297e-07, 5.282634e-07, 8.370271e-06 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.508019e-05, 1.318010e-05, 1.974555e-05 |
| Ixy, Ixz, Iyz | -1.807766e-07, 3.677612e-07, 3.432183e-06 |
| Bounding box (m) | 0.0700 × 0.0700 × 0.0457 |
| Bounding box (mm) | 70.00 × 70.00 × 45.73 |
| **Material & Appearance** | |
| Material | PETG_30_Gyroid_SMH |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 🔧 COMPONENT: `Motor_Housing_Roll`

| Property | Value |
|----------|-------|
| Full path | `Motor Housing Roll:1` |
| Component name | Motor Housing Roll |
| Depth | 0 |
| Path segments | Motor_Housing_Roll |
| **Transforms** | |
| Global position (m) | (0.041569, -0.037785, 0.273105) |
| Global position (mm) | (41.57, -37.79, 273.11) |
| Local transform (m) | (0.041569, -0.037785, 0.273105) |
| Assembly context depth | 0 |
| transform2 (m) | (0.041569, -0.037785, 0.273105) |
| **Physical** | |
| Mass | 0.120881 kg (120.881 g) |
| Volume | 2.066342e-04 m³ |
| Density | 585.0 kg/m³ |
| Surface area | 6.656408e-02 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.002097, -0.000552, 0.076431) |
| CoM (global, m) | (0.043666, -0.038337, 0.349536) |
| CoM (global, mm) | (43.67, -38.34, 349.54) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.022640e-03, 1.131636e-03, 1.730749e-04 |
| Ixy, Ixz, Iyz | -8.678370e-07, -8.364543e-06, 2.202971e-06 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 3.164606e-04, 4.249617e-04, 1.725064e-04 |
| Ixy, Ixz, Iyz | -1.007838e-06, 1.101137e-05, -2.899283e-06 |
| Bounding box (m) | 0.0910 × 0.0500 × 0.1640 |
| Bounding box (mm) | 91.00 × 50.00 × 164.00 |
| **Material & Appearance** | |
| Material | PETG_30_Gyroid_RH |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 🔧 COMPONENT: `Motor_Housing_Yaw`

| Property | Value |
|----------|-------|
| Full path | `Motor Housing Yaw:1` |
| Component name | Motor Housing Yaw |
| Depth | 0 |
| Path segments | Motor_Housing_Yaw |
| **Transforms** | |
| Global position (m) | (-0.097266, -0.048455, 0.248058) |
| Global position (mm) | (-97.27, -48.45, 248.06) |
| Local transform (m) | (-0.097266, -0.048455, 0.248058) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.097266, -0.048455, 0.248058) |
| **Physical** | |
| Mass | 0.045446 kg (45.446 g) |
| Volume | 7.862570e-05 m³ |
| Density | 578.0 kg/m³ |
| Surface area | 3.238378e-02 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.001550, -0.000000, -0.020661) |
| CoM (global, m) | (-0.098816, -0.048455, 0.227398) |
| CoM (global, mm) | (-98.82, -48.45, 227.40) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 5.439205e-05, 5.339116e-05, 3.126589e-05 |
| Ixy, Ixz, Iyz | -2.234174e-19, -2.571197e-06, -2.168463e-19 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 3.499295e-05, 3.388287e-05, 3.115670e-05 |
| Ixy, Ixz, Iyz | -2.193431e-19, -1.115781e-06, -1.625409e-19 |
| Bounding box (m) | 0.0550 × 0.0550 × 0.0765 |
| Bounding box (mm) | 55.00 × 55.00 × 76.50 |
| **Material & Appearance** | |
| Material | Yaw_Housing |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 🔧 COMPONENT: `Passive_Cap`

| Property | Value |
|----------|-------|
| Full path | `Passive Cap:1` |
| Component name | Passive Cap |
| Depth | 0 |
| Path segments | Passive_Cap |
| **Transforms** | |
| Global position (m) | (-0.067108, -0.074771, 0.226003) |
| Global position (mm) | (-67.11, -74.77, 226.00) |
| Local transform (m) | (-0.067108, -0.074771, 0.226003) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.067108, -0.074771, 0.226003) |
| **Physical** | |
| Mass | 0.007373 kg (7.373 g) |
| Volume | 1.582267e-05 m³ |
| Density | 466.0 kg/m³ |
| Surface area | 4.741087e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.000000, 0.000000, 0.012447) |
| CoM (global, m) | (-0.067108, -0.074771, 0.238450) |
| CoM (global, mm) | (-67.11, -74.77, 238.45) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.906025e-06, 1.906025e-06, 8.856442e-07 |
| Ixy, Ixz, Iyz | 3.311129e-22, 1.241597e-16, 0.000000e+00 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 7.637444e-07, 7.637445e-07, 8.856442e-07 |
| Ixy, Ixz, Iyz | 3.311129e-22, -1.142880e-17, 2.060628e-22 |
| Bounding box (m) | 0.0350 × 0.0350 × 0.0230 |
| Bounding box (mm) | 35.00 × 35.00 × 23.00 |
| **Material & Appearance** | |
| Material | PC_Roll_Housing |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 📦 SUBASSEMBLY: `Roll_Bearing_2`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:1` |
| Component name | Roll Bearing 2 |
| Depth | 0 |
| Path segments | Roll_Bearing_2 |
| Child occurrences | 2 |
| **Transforms** | |
| Global position (m) | (-0.048702, -0.143824, 0.168578) |
| Global position (mm) | (-48.70, -143.82, 168.58) |
| Local transform (m) | (-0.048702, -0.143824, 0.168578) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.048702, -0.143824, 0.168578) |

#### 📦 SUBASSEMBLY: `Roll_Bearing_2`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:2` |
| Component name | Roll Bearing 2 |
| Depth | 0 |
| Path segments | Roll_Bearing_2 |
| Child occurrences | 2 |
| **Transforms** | |
| Global position (m) | (-0.089943, 0.036878, 0.206694) |
| Global position (mm) | (-89.94, 36.88, 206.69) |
| Local transform (m) | (-0.089943, 0.036878, 0.206694) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.089943, 0.036878, 0.206694) |

#### 📦 SUBASSEMBLY: `Roll_Bearing_2`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:3` |
| Component name | Roll Bearing 2 |
| Depth | 0 |
| Path segments | Roll_Bearing_2 |
| Child occurrences | 2 |
| **Transforms** | |
| Global position (m) | (0.099032, -0.166007, 0.165928) |
| Global position (mm) | (99.03, -166.01, 165.93) |
| Local transform (m) | (0.099032, -0.166007, 0.165928) |
| Assembly context depth | 0 |
| transform2 (m) | (0.099032, -0.166007, 0.165928) |

#### 📦 SUBASSEMBLY: `Roll_Bearing_2`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:4` |
| Component name | Roll Bearing 2 |
| Depth | 0 |
| Path segments | Roll_Bearing_2 |
| Child occurrences | 2 |
| **Transforms** | |
| Global position (m) | (0.280742, -0.098574, 0.298136) |
| Global position (mm) | (280.74, -98.57, 298.14) |
| Local transform (m) | (0.280742, -0.098574, 0.298136) |
| Assembly context depth | 0 |
| transform2 (m) | (0.280742, -0.098574, 0.298136) |

#### 📦 SUBASSEMBLY: `Roll_Bearing_2`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:5` |
| Component name | Roll Bearing 2 |
| Depth | 0 |
| Path segments | Roll_Bearing_2 |
| Child occurrences | 2 |
| **Transforms** | |
| Global position (m) | (-0.179504, -0.250298, 0.243397) |
| Global position (mm) | (-179.50, -250.30, 243.40) |
| Local transform (m) | (-0.179504, -0.250298, 0.243397) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.179504, -0.250298, 0.243397) |

#### 📦 SUBASSEMBLY: `Roll_Bearing_2`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:6` |
| Component name | Roll Bearing 2 |
| Depth | 0 |
| Path segments | Roll_Bearing_2 |
| Child occurrences | 2 |
| **Transforms** | |
| Global position (m) | (-0.201719, -0.307444, 0.209205) |
| Global position (mm) | (-201.72, -307.44, 209.20) |
| Local transform (m) | (-0.201719, -0.307444, 0.209205) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.201719, -0.307444, 0.209205) |

#### 📦 SUBASSEMBLY: `Roll_Bearing_2`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:7` |
| Component name | Roll Bearing 2 |
| Depth | 0 |
| Path segments | Roll_Bearing_2 |
| Child occurrences | 2 |
| **Transforms** | |
| Global position (m) | (0.066042, -0.164696, 0.317817) |
| Global position (mm) | (66.04, -164.70, 317.82) |
| Local transform (m) | (0.066042, -0.164696, 0.317817) |
| Assembly context depth | 0 |
| transform2 (m) | (0.066042, -0.164696, 0.317817) |

#### 🔧 COMPONENT: `Roll_Motor`

| Property | Value |
|----------|-------|
| Full path | `Roll Motor:1` |
| Component name | Roll Motor |
| Depth | 0 |
| Path segments | Roll_Motor |
| **Transforms** | |
| Global position (m) | (0.008721, -0.002018, 0.258513) |
| Global position (mm) | (8.72, -2.02, 258.51) |
| Local transform (m) | (0.008721, -0.002018, 0.258513) |
| Assembly context depth | 0 |
| transform2 (m) | (0.008721, -0.002018, 0.258513) |
| **Physical** | |
| Mass | 0.390226 kg (390.226 g) |
| Volume | 8.285048e-05 m³ |
| Density | 4710.0 kg/m³ |
| Surface area | 1.249357e-02 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.000000, -0.000022, 0.023653) |
| CoM (global, m) | (0.008721, -0.002040, 0.282166) |
| CoM (global, mm) | (8.72, -2.04, 282.17) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 3.513838e-04, 3.510934e-04, 1.078761e-04 |
| Ixy, Ixz, Iyz | -3.483183e-10, -1.478300e-10, 3.618025e-07 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.330715e-04, 1.327813e-04, 1.078759e-04 |
| Ixy, Ixz, Iyz | -3.484175e-10, -4.343794e-11, 1.542227e-07 |
| Bounding box (m) | 0.0423 × 0.0603 × 0.0720 |
| Bounding box (mm) | 42.32 × 60.31 × 72.00 |
| **Material & Appearance** | |
| Material | Iron_Wrought |
| Appearance | Opaque_255_255_255 |
| Color (RGB 0-1) | (1.000, 1.000, 1.000) |
| Color (RGB 0-255) | (255, 255, 255) |

#### 📦 SUBASSEMBLY: `Shaft_Connector`

| Property | Value |
|----------|-------|
| Full path | `Shaft Connector:1` |
| Component name | Shaft Connector |
| Depth | 0 |
| Path segments | Shaft_Connector |
| Child occurrences | 1 |
| **Transforms** | |
| Global position (m) | (0.162400, -0.198097, 0.089529) |
| Global position (mm) | (162.40, -198.10, 89.53) |
| Local transform (m) | (0.162400, -0.198097, 0.089529) |
| Assembly context depth | 0 |
| transform2 (m) | (0.162400, -0.198097, 0.089529) |

#### 🔧 COMPONENT: `Shoulder_Bearing_2_Lower`

| Property | Value |
|----------|-------|
| Full path | `Shoulder Bearing 2 Lower:1` |
| Component name | Shoulder Bearing 2 Lower |
| Depth | 0 |
| Path segments | Shoulder_Bearing_2_Lower |
| **Transforms** | |
| Global position (m) | (0.000000, 0.000000, 0.000000) |
| Global position (mm) | (0.00, 0.00, 0.00) |
| Local transform (m) | (0.000000, 0.000000, 0.000000) |
| Assembly context depth | 0 |
| transform2 (m) | (0.000000, 0.000000, 0.000000) |
| **Physical** | |
| Mass | 0.062154 kg (62.154 g) |
| Volume | 6.939147e-06 m³ |
| Density | 8957.0 kg/m³ |
| Surface area | 5.531252e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.009700, -0.000000, -0.000000) |
| CoM (global, m) | (-0.009700, -0.000000, -0.000000) |
| CoM (global, mm) | (-9.70, -0.00, -0.00) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 5.372853e-05, 3.342072e-05, 3.342072e-05 |
| Ixy, Ixz, Iyz | -7.955414e-20, -6.841656e-20, -3.054879e-19 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 5.372853e-05, 2.757216e-05, 2.757216e-05 |
| Ixy, Ixz, Iyz | -2.399114e-20, -1.902723e-20, -3.054879e-19 |
| Bounding box (m) | 0.0120 × 0.0620 × 0.0620 |
| Bounding box (mm) | 12.00 × 62.00 × 62.00 |
| **Material & Appearance** | |
| Material | NSK_32908 |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `Shoulder_Bearing_2_Lower`

| Property | Value |
|----------|-------|
| Full path | `Shoulder Bearing 2 Lower:2` |
| Component name | Shoulder Bearing 2 Lower |
| Depth | 0 |
| Path segments | Shoulder_Bearing_2_Lower |
| **Transforms** | |
| Global position (m) | (-0.011239, -0.102079, 0.060400) |
| Global position (mm) | (-11.24, -102.08, 60.40) |
| Local transform (m) | (-0.011239, -0.102079, 0.060400) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.011239, -0.102079, 0.060400) |
| **Physical** | |
| Mass | 0.062154 kg (62.154 g) |
| Volume | 6.939147e-06 m³ |
| Density | 8957.0 kg/m³ |
| Surface area | 5.531252e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.009700, -0.000000, -0.000000) |
| CoM (global, m) | (-0.020940, -0.102079, 0.060400) |
| CoM (global, mm) | (-20.94, -102.08, 60.40) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 5.372853e-05, 3.342072e-05, 3.342072e-05 |
| Ixy, Ixz, Iyz | -7.955414e-20, -6.841656e-20, -3.054879e-19 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 5.372853e-05, 2.757216e-05, 2.757216e-05 |
| Ixy, Ixz, Iyz | -2.399114e-20, -1.902723e-20, -3.054879e-19 |
| Bounding box (m) | 0.0120 × 0.0620 × 0.0620 |
| Bounding box (mm) | 12.00 × 62.00 × 62.00 |
| **Material & Appearance** | |
| Material | NSK_32908 |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `Shoulder_Bearing_2_Lower`

| Property | Value |
|----------|-------|
| Full path | `Shoulder Bearing 2 Lower:3` |
| Component name | Shoulder Bearing 2 Lower |
| Depth | 0 |
| Path segments | Shoulder_Bearing_2_Lower |
| **Transforms** | |
| Global position (m) | (-0.007531, -0.144918, 0.060400) |
| Global position (mm) | (-7.53, -144.92, 60.40) |
| Local transform (m) | (-0.007531, -0.144918, 0.060400) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.007531, -0.144918, 0.060400) |
| **Physical** | |
| Mass | 0.062154 kg (62.154 g) |
| Volume | 6.939147e-06 m³ |
| Density | 8957.0 kg/m³ |
| Surface area | 5.531252e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.009700, -0.000000, -0.000000) |
| CoM (global, m) | (-0.017232, -0.144918, 0.060400) |
| CoM (global, mm) | (-17.23, -144.92, 60.40) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 5.372853e-05, 3.342072e-05, 3.342072e-05 |
| Ixy, Ixz, Iyz | -7.955414e-20, -6.841656e-20, -3.054879e-19 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 5.372853e-05, 2.757216e-05, 2.757216e-05 |
| Ixy, Ixz, Iyz | -2.399114e-20, -1.902723e-20, -3.054879e-19 |
| Bounding box (m) | 0.0120 × 0.0620 × 0.0620 |
| Bounding box (mm) | 12.00 × 62.00 × 62.00 |
| **Material & Appearance** | |
| Material | NSK_32908 |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `Shoulder_Bearing_2_Upper`

| Property | Value |
|----------|-------|
| Full path | `Shoulder Bearing 2 Upper:1` |
| Component name | Shoulder Bearing 2 Upper |
| Depth | 0 |
| Path segments | Shoulder_Bearing_2_Upper |
| **Transforms** | |
| Global position (m) | (0.000000, 0.000000, -0.000600) |
| Global position (mm) | (0.00, 0.00, -0.60) |
| Local transform (m) | (0.000000, 0.000000, -0.000600) |
| Assembly context depth | 0 |
| transform2 (m) | (0.000000, 0.000000, -0.000600) |
| **Physical** | |
| Mass | 0.098851 kg (98.851 g) |
| Volume | 1.103621e-05 m³ |
| Density | 8957.0 kg/m³ |
| Surface area | 9.107294e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.006970, 0.000000, 0.000000) |
| CoM (global, m) | (-0.006970, 0.000000, -0.000600) |
| CoM (global, mm) | (-6.97, 0.00, -0.60) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 5.363167e-05, 3.324533e-05, 3.324622e-05 |
| Ixy, Ixz, Iyz | -1.035031e-16, 1.035540e-16, 3.818599e-20 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 5.363167e-05, 2.844369e-05, 2.844458e-05 |
| Ixy, Ixz, Iyz | -1.035186e-16, 1.035518e-16, 3.818599e-20 |
| Bounding box (m) | 0.0150 × 0.0577 × 0.0577 |
| Bounding box (mm) | 15.00 × 57.70 × 57.70 |
| **Material & Appearance** | |
| Material | NSK_32908 |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `Shoulder_Bearing_2_Upper`

| Property | Value |
|----------|-------|
| Full path | `Shoulder Bearing 2 Upper:2` |
| Component name | Shoulder Bearing 2 Upper |
| Depth | 0 |
| Path segments | Shoulder_Bearing_2_Upper |
| **Transforms** | |
| Global position (m) | (-0.011239, -0.102079, 0.060400) |
| Global position (mm) | (-11.24, -102.08, 60.40) |
| Local transform (m) | (-0.011239, -0.102079, 0.060400) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.011239, -0.102079, 0.060400) |
| **Physical** | |
| Mass | 0.098851 kg (98.851 g) |
| Volume | 1.103621e-05 m³ |
| Density | 8957.0 kg/m³ |
| Surface area | 9.107294e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.006970, 0.000000, 0.000000) |
| CoM (global, m) | (-0.018209, -0.102079, 0.060400) |
| CoM (global, mm) | (-18.21, -102.08, 60.40) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 5.363167e-05, 3.324533e-05, 3.324622e-05 |
| Ixy, Ixz, Iyz | -1.035031e-16, 1.035540e-16, 3.818599e-20 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 5.363167e-05, 2.844369e-05, 2.844458e-05 |
| Ixy, Ixz, Iyz | -1.035186e-16, 1.035518e-16, 3.818599e-20 |
| Bounding box (m) | 0.0150 × 0.0577 × 0.0577 |
| Bounding box (mm) | 15.00 × 57.70 × 57.70 |
| **Material & Appearance** | |
| Material | NSK_32908 |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `Shoulder_Bearing_2_Upper`

| Property | Value |
|----------|-------|
| Full path | `Shoulder Bearing 2 Upper:3` |
| Component name | Shoulder Bearing 2 Upper |
| Depth | 0 |
| Path segments | Shoulder_Bearing_2_Upper |
| **Transforms** | |
| Global position (m) | (-0.007531, -0.144918, 0.060400) |
| Global position (mm) | (-7.53, -144.92, 60.40) |
| Local transform (m) | (-0.007531, -0.144918, 0.060400) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.007531, -0.144918, 0.060400) |
| **Physical** | |
| Mass | 0.098851 kg (98.851 g) |
| Volume | 1.103621e-05 m³ |
| Density | 8957.0 kg/m³ |
| Surface area | 9.107294e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.006970, 0.000000, 0.000000) |
| CoM (global, m) | (-0.014501, -0.144918, 0.060400) |
| CoM (global, mm) | (-14.50, -144.92, 60.40) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 5.363167e-05, 3.324533e-05, 3.324622e-05 |
| Ixy, Ixz, Iyz | -1.035031e-16, 1.035540e-16, 3.818599e-20 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 5.363167e-05, 2.844369e-05, 2.844458e-05 |
| Ixy, Ixz, Iyz | -1.035186e-16, 1.035518e-16, 3.818599e-20 |
| Bounding box (m) | 0.0150 × 0.0577 × 0.0577 |
| Bounding box (mm) | 15.00 × 57.70 × 57.70 |
| **Material & Appearance** | |
| Material | NSK_32908 |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `Shoulder_Cap`

| Property | Value |
|----------|-------|
| Full path | `Shoulder Cap:2` |
| Component name | Shoulder Cap |
| Depth | 0 |
| Path segments | Shoulder_Cap |
| **Transforms** | |
| Global position (m) | (-0.007531, -0.144918, 0.060400) |
| Global position (mm) | (-7.53, -144.92, 60.40) |
| Local transform (m) | (-0.007531, -0.144918, 0.060400) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.007531, -0.144918, 0.060400) |
| **Physical** | |
| Mass | 0.004930 kg (4.930 g) |
| Volume | 6.004853e-06 m³ |
| Density | 821.0 kg/m³ |
| Surface area | 3.596300e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.000000, -0.000000, 0.002282) |
| CoM (global, m) | (-0.007531, -0.144918, 0.062682) |
| CoM (global, mm) | (-7.53, -144.92, 62.68) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 5.490462e-07, 5.490463e-07, 1.026583e-06 |
| Ixy, Ixz, Iyz | -2.916778e-22, -1.821681e-17, 0.000000e+00 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 5.233730e-07, 5.233731e-07, 1.026583e-06 |
| Ixy, Ixz, Iyz | -2.916778e-22, -1.588432e-18, -3.328058e-23 |
| Bounding box (m) | 0.0450 × 0.0450 × 0.0050 |
| Bounding box (mm) | 45.00 × 45.00 × 5.00 |
| **Material & Appearance** | |
| Material | PETG_30_Gyroid |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 🔧 COMPONENT: `Shoulder_Motor`

| Property | Value |
|----------|-------|
| Full path | `Shoulder Motor:1` |
| Component name | Shoulder Motor |
| Depth | 0 |
| Path segments | Shoulder_Motor |
| **Transforms** | |
| Global position (m) | (-0.034307, 0.164425, 0.060400) |
| Global position (mm) | (-34.31, 164.42, 60.40) |
| Local transform (m) | (-0.034307, 0.164425, 0.060400) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.034307, 0.164425, 0.060400) |
| **Physical** | |
| Mass | 0.498902 kg (498.902 g) |
| Volume | 1.030788e-04 m³ |
| Density | 4840.0 kg/m³ |
| Surface area | 1.430189e-02 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.000000, -0.000017, 0.030332) |
| CoM (global, m) | (-0.034307, 0.164408, 0.090732) |
| CoM (global, mm) | (-34.31, 164.41, 90.73) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 6.837719e-04, 6.834972e-04, 1.375650e-04 |
| Ixy, Ixz, Iyz | 2.867839e-10, 1.023765e-10, 5.859788e-08 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 2.247628e-04, 2.244883e-04, 1.375649e-04 |
| Ixy, Ixz, Iyz | 2.867961e-10, 8.000350e-11, -1.915324e-07 |
| Bounding box (m) | 0.0423 × 0.0603 × 0.0840 |
| Bounding box (mm) | 42.32 × 60.31 × 84.00 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Opaque_255_255_255 |
| Color (RGB 0-1) | (1.000, 1.000, 1.000) |
| Color (RGB 0-255) | (255, 255, 255) |

#### 🔧 COMPONENT: `UA_Motor`

| Property | Value |
|----------|-------|
| Full path | `UA Motor:1` |
| Component name | UA Motor |
| Depth | 0 |
| Path segments | UA_Motor |
| **Transforms** | |
| Global position (m) | (0.051780, -0.019838, 0.135897) |
| Global position (mm) | (51.78, -19.84, 135.90) |
| Local transform (m) | (0.051780, -0.019838, 0.135897) |
| Assembly context depth | 0 |
| transform2 (m) | (0.051780, -0.019838, 0.135897) |
| **Physical** | |
| Mass | 0.390226 kg (390.226 g) |
| Volume | 8.285048e-05 m³ |
| Density | 4710.0 kg/m³ |
| Surface area | 1.249357e-02 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.000000, -0.000022, 0.023653) |
| CoM (global, m) | (0.051780, -0.019860, 0.159549) |
| CoM (global, mm) | (51.78, -19.86, 159.55) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 3.513838e-04, 3.510934e-04, 1.078761e-04 |
| Ixy, Ixz, Iyz | -3.483183e-10, -1.478300e-10, 3.618025e-07 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.330715e-04, 1.327813e-04, 1.078759e-04 |
| Ixy, Ixz, Iyz | -3.484175e-10, -4.343794e-11, 1.542227e-07 |
| Bounding box (m) | 0.0423 × 0.0603 × 0.0720 |
| Bounding box (mm) | 42.32 × 60.31 × 72.00 |
| **Material & Appearance** | |
| Material | UA_Motor |
| Appearance | Opaque_255_255_255 |
| Color (RGB 0-1) | (1.000, 1.000, 1.000) |
| Color (RGB 0-255) | (255, 255, 255) |

#### 📦 SUBASSEMBLY: `UA_Shaft_COupler`

| Property | Value |
|----------|-------|
| Full path | `UA Shaft COupler:1` |
| Component name | UA Shaft COupler |
| Depth | 0 |
| Path segments | UA_Shaft_COupler |
| Child occurrences | 3 |
| **Transforms** | |
| Global position (m) | (0.088024, -0.221124, -0.012713) |
| Global position (mm) | (88.02, -221.12, -12.71) |
| Local transform (m) | (0.088024, -0.221124, -0.012713) |
| Assembly context depth | 0 |
| transform2 (m) | (0.088024, -0.221124, -0.012713) |

#### 📦 SUBASSEMBLY: `UA_Shaft_Coupler`

| Property | Value |
|----------|-------|
| Full path | `UA Shaft Coupler:1` |
| Component name | UA Shaft Coupler |
| Depth | 0 |
| Path segments | UA_Shaft_Coupler |
| Child occurrences | 3 |
| **Transforms** | |
| Global position (m) | (0.176478, -0.169058, 0.066145) |
| Global position (mm) | (176.48, -169.06, 66.14) |
| Local transform (m) | (0.176478, -0.169058, 0.066145) |
| Assembly context depth | 0 |
| transform2 (m) | (0.176478, -0.169058, 0.066145) |

#### 🔧 COMPONENT: `Upper_arm`

| Property | Value |
|----------|-------|
| Full path | `Upper arm:1` |
| Component name | Upper arm |
| Depth | 0 |
| Path segments | Upper_arm |
| **Transforms** | |
| Global position (m) | (-0.019690, -0.004444, 0.060400) |
| Global position (mm) | (-19.69, -4.44, 60.40) |
| Local transform (m) | (-0.019690, -0.004444, 0.060400) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.019690, -0.004444, 0.060400) |
| **Physical** | |
| Mass | 0.290872 kg (290.872 g) |
| Volume | 5.997351e-04 m³ |
| Density | 485.0 kg/m³ |
| Surface area | 1.147166e-01 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001691, 0.059769, 0.047443) |
| CoM (global, m) | (-0.017999, 0.055325, 0.107843) |
| CoM (global, mm) | (-18.00, 55.33, 107.84) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 3.859039e-03, 1.386153e-03, 2.632012e-03 |
| Ixy, Ixz, Iyz | -5.623487e-05, -1.964548e-05, -7.131326e-04 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 2.165246e-03, 7.306094e-04, 1.592100e-03 |
| Ixy, Ixz, Iyz | -2.683789e-05, 3.689287e-06, 1.116693e-04 |
| Bounding box (m) | 0.0600 × 0.2618 × 0.1610 |
| Bounding box (mm) | 60.00 × 261.82 × 161.00 |
| **Material & Appearance** | |
| Material | PETG_30_Gryoid_UA |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 🔧 COMPONENT: `Yaw_Motor`

| Property | Value |
|----------|-------|
| Full path | `Yaw Motor:1` |
| Component name | Yaw Motor |
| Depth | 0 |
| Path segments | Yaw_Motor |
| **Transforms** | |
| Global position (m) | (-0.064771, -0.047193, 0.221479) |
| Global position (mm) | (-64.77, -47.19, 221.48) |
| Local transform (m) | (-0.064771, -0.047193, 0.221479) |
| Assembly context depth | 0 |
| transform2 (m) | (-0.064771, -0.047193, 0.221479) |
| **Physical** | |
| Mass | 0.139847 kg (139.847 g) |
| Volume | 3.513747e-05 m³ |
| Density | 3980.0 kg/m³ |
| Surface area | 7.882676e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.000000, -0.000047, 0.010540) |
| CoM (global, m) | (-0.064771, -0.047240, 0.232019) |
| CoM (global, mm) | (-64.77, -47.24, 232.02) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 4.024218e-05, 4.001974e-05, 3.845672e-05 |
| Ixy, Ixz, Iyz | 2.044361e-10, 5.334451e-12, 2.877624e-08 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 2.470563e-05, 2.448351e-05, 3.845641e-05 |
| Ixy, Ixz, Iyz | 2.044979e-10, -8.436603e-12, -4.095276e-08 |
| Bounding box (m) | 0.0423 × 0.0603 × 0.0400 |
| Bounding box (mm) | 42.32 × 60.31 × 40.00 |
| **Material & Appearance** | |
| Material | Yaw_Motor |
| Appearance | Opaque_255_255_255 |
| Color (RGB 0-1) | (1.000, 1.000, 1.000) |
| Color (RGB 0-255) | (255, 255, 255) |

#### 🔧 COMPONENT: `base_link`

| Property | Value |
|----------|-------|
| Full path | `base_link:1` |
| Component name | base_link |
| Depth | 0 |
| Path segments | base_link |
| **Transforms** | |
| Global position (m) | (0.000000, 0.000000, 0.000000) |
| Global position (mm) | (0.00, 0.00, 0.00) |
| Local transform (m) | (0.000000, 0.000000, 0.000000) |
| Assembly context depth | 0 |
| transform2 (m) | (0.000000, 0.000000, 0.000000) |
| **Physical** | |
| Mass | 0.274677 kg (274.677 g) |
| Volume | 1.037299e-03 m³ |
| Density | 264.8 kg/m³ |
| Surface area | 1.084489e-01 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.000000, 0.000000, -0.039151) |
| CoM (global, m) | (0.000000, 0.000000, -0.039151) |
| CoM (global, mm) | (0.00, 0.00, -39.15) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.046247e-03, 1.046247e-03, 1.017214e-03 |
| Ixy, Ixz, Iyz | -1.156004e-18, 4.846066e-15, 4.142348e-18 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 6.252186e-04, 6.252186e-04, 1.017214e-03 |
| Ixy, Ixz, Iyz | -1.156004e-18, -1.371567e-15, 3.953769e-18 |
| Bounding box (m) | 0.1750 × 0.1750 × 0.0710 |
| Bounding box (mm) | 175.00 × 175.00 × 71.00 |
| **Material & Appearance** | |
| Material | PETG_15_Gyroid |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

### Depth 1

#### 🔧 COMPONENT: `Base_Connector_Shaft_V2`

| Property | Value |
|----------|-------|
| Full path | `Base Connector + Shaft V2:1` |
| Component name | Base Connector + Shaft V2 |
| Depth | 1 |
| Path segments | Base_Connector → Shaft_V2 |
| Parent path | `Base Connector ` |
| **Transforms** | |
| Global position (m) | (0.074721, 0.006468, 0.025400) |
| Global position (mm) | (74.72, 6.47, 25.40) |
| Local transform (m) | (0.074721, 0.006468, 0.025400) |
| Assembly context depth | 0 |
| transform2 (m) | (0.074721, 0.006468, 0.025400) |
| **Physical** | |
| Mass | 0.315930 kg (315.930 g) |
| Volume | 7.820055e-04 m³ |
| Density | 404.0 kg/m³ |
| Surface area | 1.173904e-01 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.076504, 0.036952, -0.014900) |
| CoM (global, m) | (0.151224, 0.043419, 0.010500) |
| CoM (global, mm) | (151.22, 43.42, 10.50) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.777431e-03, 2.584179e-03, 4.104951e-03 |
| Ixy, Ixz, Iyz | -9.328358e-04, 3.553725e-04, 1.434327e-04 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.275902e-03, 6.649494e-04, 1.824480e-03 |
| Ixy, Ixz, Iyz | -3.971328e-05, -4.768174e-06, -3.051794e-05 |
| Bounding box (m) | 0.1600 × 0.2300 × 0.0769 |
| Bounding box (mm) | 160.00 × 230.00 × 76.90 |
| **Material & Appearance** | |
| Material | PETG_25_Gyroid |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 🔧 COMPONENT: `Component64`

| Property | Value |
|----------|-------|
| Full path | `Belt Shaft:1+Component64:1` |
| Component name | Component64 |
| Depth | 1 |
| Path segments | Belt_Shaft → Component64 |
| Parent path | `Belt Shaft:1` |
| **Transforms** | |
| Global position (m) | (-0.073037, 0.009960, 0.222777) |
| Global position (mm) | (-73.04, 9.96, 222.78) |
| Local transform (m) | (0.000000, 0.000000, 0.000000) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.073037, 0.009960, 0.222777) |
| **Physical** | |
| Mass | 0.014791 kg (14.791 g) |
| Volume | 3.447743e-05 m³ |
| Density | 429.0 kg/m³ |
| Surface area | 9.330631e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.000000, 0.000000, 0.010675) |
| CoM (global, m) | (-0.073037, 0.009960, 0.233452) |
| CoM (global, mm) | (-73.04, 9.96, 233.45) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 4.468267e-06, 4.468267e-06, 3.638875e-06 |
| Ixy, Ixz, Iyz | 1.707008e-20, -5.401826e-17, 1.219291e-21 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 2.782782e-06, 2.782782e-06, 3.638875e-06 |
| Ixy, Ixz, Iyz | 1.707008e-20, 3.950873e-17, 9.028827e-21 |
| Bounding box (m) | 0.0524 × 0.0524 × 0.0300 |
| Bounding box (mm) | 52.42 × 52.42 × 30.00 |
| **Material & Appearance** | |
| Material | Active_Cap_Roll |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 🔧 COMPONENT: `6801_1`

| Property | Value |
|----------|-------|
| Full path | `EG17-G10:1+6801 (1):1` |
| Component name | 6801 (1) |
| Depth | 1 |
| Path segments | EG17_G10 → 6801_1 |
| Parent path | `EG17-G10:1` |
| **Transforms** | |
| Global position (m) | (0.053893, -0.044247, 0.135897) |
| Global position (mm) | (53.89, -44.25, 135.90) |
| Local transform (m) | (-0.002088, 0.002647, 0.020250) |
| Assembly context depth | 1 |
| transform2 (m) | (0.053893, -0.044247, 0.135897) |
| **Physical** | |
| Mass | 0.004629 kg (4.629 g) |
| Volume | 1.122774e-06 m³ |
| Density | 4123.0 kg/m³ |
| Surface area | 1.026358e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.000000, -0.000000, 0.002500) |
| CoM (global, m) | (0.053893, -0.044247, 0.138397) |
| CoM (global, mm) | (53.89, -44.25, 138.40) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 2.075264e-07, 2.075264e-07, 3.392209e-07 |
| Ixy, Ixz, Iyz | 6.408429e-22, -5.605545e-19, 7.314032e-18 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.785940e-07, 1.785940e-07, 3.392209e-07 |
| Ixy, Ixz, Iyz | 6.408429e-22, -5.604858e-19, 2.288725e-23 |
| Bounding box (m) | 0.0210 × 0.0210 × 0.0050 |
| Bounding box (mm) | 21.00 × 21.00 × 5.00 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `EG17_shaft`

| Property | Value |
|----------|-------|
| Full path | `EG17-G10:1+EG17 shaft:1` |
| Component name | EG17 shaft |
| Depth | 1 |
| Path segments | EG17_G10 → EG17_shaft |
| Parent path | `EG17-G10:1` |
| **Transforms** | |
| Global position (m) | (0.055703, -0.065168, 0.135897) |
| Global position (mm) | (55.70, -65.17, 135.90) |
| Local transform (m) | (-0.002088, 0.002647, 0.041250) |
| Assembly context depth | 1 |
| transform2 (m) | (0.055703, -0.065168, 0.135897) |
| **Physical** | |
| Mass | 0.157168 kg (157.168 g) |
| Volume | 3.811971e-05 m³ |
| Density | 4123.0 kg/m³ |
| Surface area | 7.835194e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.000000, -0.000005, -0.002897) |
| CoM (global, m) | (0.055703, -0.065174, 0.133000) |
| CoM (global, mm) | (55.70, -65.17, 133.00) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 2.969085e-05, 2.969336e-05, 3.309726e-05 |
| Ixy, Ixz, Iyz | 1.621511e-15, -1.729833e-15, 1.939865e-08 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 2.837178e-05, 2.837429e-05, 3.309726e-05 |
| Ixy, Ixz, Iyz | 1.622548e-15, -1.182256e-15, 2.189636e-08 |
| Bounding box (m) | 0.0420 × 0.0420 × 0.0485 |
| Bounding box (mm) | 42.00 × 42.00 × 48.50 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Silver_Polished |
| Color (RGB 0-1) | (0.984, 0.980, 0.961) |
| Color (RGB 0-255) | (251, 250, 245) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw_1`

| Property | Value |
|----------|-------|
| Full path | `EG17-G10:1+M3hexagon socket head cap screw (1):1` |
| Component name | M3hexagon socket head cap screw (1) |
| Depth | 1 |
| Path segments | EG17_G10 → M3hexagon_socket_head_cap_screw_1 |
| Parent path | `EG17-G10:1` |
| **Transforms** | |
| Global position (m) | (0.040314, -0.072523, 0.127585) |
| Global position (mm) | (40.31, -72.52, 127.59) |
| Local transform (m) | (0.004801, 0.019277, 0.047250) |
| Assembly context depth | 1 |
| transform2 (m) | (0.040314, -0.072523, 0.127585) |
| **Physical** | |
| Mass | 0.000191 kg (0.191 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4123.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (0.041699, -0.072522, 0.127584) |
| CoM (global, mm) | (41.70, -72.52, 127.58) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485983e-10, 9.436327e-10, 9.436874e-10 |
| Ixy, Ixz, Iyz | -2.328417e-13, 1.910243e-13, -1.881040e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485981e-10, 5.768244e-10, 5.768791e-10 |
| Ixy, Ixz, Iyz | -1.781302e-14, 1.461388e-14, -1.882074e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw_1`

| Property | Value |
|----------|-------|
| Full path | `EG17-G10:1+M3hexagon socket head cap screw (1):2` |
| Component name | M3hexagon socket head cap screw (1) |
| Depth | 1 |
| Path segments | EG17_G10 → M3hexagon_socket_head_cap_screw_1 |
| Parent path | `EG17-G10:1` |
| **Transforms** | |
| Global position (m) | (0.064501, -0.070429, 0.119930) |
| Global position (mm) | (64.50, -70.43, 119.93) |
| Local transform (m) | (-0.018717, 0.009535, 0.047250) |
| Assembly context depth | 1 |
| transform2 (m) | (0.064501, -0.070429, 0.119930) |
| **Physical** | |
| Mass | 0.000191 kg (0.191 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4123.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (0.065887, -0.070428, 0.119930) |
| CoM (global, mm) | (65.89, -70.43, 119.93) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485983e-10, 9.436327e-10, 9.436874e-10 |
| Ixy, Ixz, Iyz | -2.328417e-13, 1.910243e-13, -1.881040e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485981e-10, 5.768244e-10, 5.768791e-10 |
| Ixy, Ixz, Iyz | -1.781302e-14, 1.461388e-14, -1.882074e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw_1`

| Property | Value |
|----------|-------|
| Full path | `EG17-G10:1+M3hexagon socket head cap screw (1):3` |
| Component name | M3hexagon socket head cap screw (1) |
| Depth | 1 |
| Path segments | EG17_G10 → M3hexagon_socket_head_cap_screw_1 |
| Parent path | `EG17-G10:1` |
| **Transforms** | |
| Global position (m) | (0.072128, -0.069769, 0.144208) |
| Global position (mm) | (72.13, -69.77, 144.21) |
| Local transform (m) | (-0.008976, -0.013983, 0.047250) |
| Assembly context depth | 1 |
| transform2 (m) | (0.072128, -0.069769, 0.144208) |
| **Physical** | |
| Mass | 0.000191 kg (0.191 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4123.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (0.073513, -0.069768, 0.144207) |
| CoM (global, mm) | (73.51, -69.77, 144.21) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485983e-10, 9.436327e-10, 9.436874e-10 |
| Ixy, Ixz, Iyz | -2.328417e-13, 1.910243e-13, -1.881040e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485981e-10, 5.768244e-10, 5.768791e-10 |
| Ixy, Ixz, Iyz | -1.781302e-14, 1.461388e-14, -1.882074e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw_1`

| Property | Value |
|----------|-------|
| Full path | `EG17-G10:1+M3hexagon socket head cap screw (1):4` |
| Component name | M3hexagon socket head cap screw (1) |
| Depth | 1 |
| Path segments | EG17_G10 → M3hexagon_socket_head_cap_screw_1 |
| Parent path | `EG17-G10:1` |
| **Transforms** | |
| Global position (m) | (0.047940, -0.071863, 0.151863) |
| Global position (mm) | (47.94, -71.86, 151.86) |
| Local transform (m) | (0.014542, -0.004242, 0.047250) |
| Assembly context depth | 1 |
| transform2 (m) | (0.047940, -0.071863, 0.151863) |
| **Physical** | |
| Mass | 0.000191 kg (0.191 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4123.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (0.049326, -0.071862, 0.151862) |
| CoM (global, mm) | (49.33, -71.86, 151.86) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485983e-10, 9.436327e-10, 9.436874e-10 |
| Ixy, Ixz, Iyz | -2.328417e-13, 1.910243e-13, -1.881040e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485981e-10, 5.768244e-10, 5.768791e-10 |
| Ixy, Ixz, Iyz | -1.781302e-14, 1.461388e-14, -1.882074e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw_1`

| Property | Value |
|----------|-------|
| Full path | `EG17-G10:1+M3hexagon socket head cap screw (1):5` |
| Component name | M3hexagon socket head cap screw (1) |
| Depth | 1 |
| Path segments | EG17_G10 → M3hexagon_socket_head_cap_screw_1 |
| Parent path | `EG17-G10:1` |
| **Transforms** | |
| Global position (m) | (0.068075, -0.022944, 0.144208) |
| Global position (mm) | (68.07, -22.94, 144.21) |
| Local transform (m) | (-0.008976, -0.013983, 0.000250) |
| Assembly context depth | 1 |
| transform2 (m) | (0.068075, -0.022944, 0.144208) |
| **Physical** | |
| Mass | 0.000191 kg (0.191 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4123.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (0.069460, -0.022943, 0.144207) |
| CoM (global, mm) | (69.46, -22.94, 144.21) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485983e-10, 9.436327e-10, 9.436874e-10 |
| Ixy, Ixz, Iyz | -2.328417e-13, 1.910243e-13, -1.881040e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485981e-10, 5.768244e-10, 5.768791e-10 |
| Ixy, Ixz, Iyz | -1.781302e-14, 1.461388e-14, -1.882074e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw_1`

| Property | Value |
|----------|-------|
| Full path | `EG17-G10:1+M3hexagon socket head cap screw (1):6` |
| Component name | M3hexagon socket head cap screw (1) |
| Depth | 1 |
| Path segments | EG17_G10 → M3hexagon_socket_head_cap_screw_1 |
| Parent path | `EG17-G10:1` |
| **Transforms** | |
| Global position (m) | (0.060448, -0.023604, 0.119930) |
| Global position (mm) | (60.45, -23.60, 119.93) |
| Local transform (m) | (-0.018717, 0.009535, 0.000250) |
| Assembly context depth | 1 |
| transform2 (m) | (0.060448, -0.023604, 0.119930) |
| **Physical** | |
| Mass | 0.000191 kg (0.191 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4123.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (0.061834, -0.023604, 0.119930) |
| CoM (global, mm) | (61.83, -23.60, 119.93) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485983e-10, 9.436327e-10, 9.436874e-10 |
| Ixy, Ixz, Iyz | -2.328417e-13, 1.910243e-13, -1.881040e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485981e-10, 5.768244e-10, 5.768791e-10 |
| Ixy, Ixz, Iyz | -1.781302e-14, 1.461388e-14, -1.882074e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw_1`

| Property | Value |
|----------|-------|
| Full path | `EG17-G10:1+M3hexagon socket head cap screw (1):7` |
| Component name | M3hexagon socket head cap screw (1) |
| Depth | 1 |
| Path segments | EG17_G10 → M3hexagon_socket_head_cap_screw_1 |
| Parent path | `EG17-G10:1` |
| **Transforms** | |
| Global position (m) | (0.036261, -0.025698, 0.127585) |
| Global position (mm) | (36.26, -25.70, 127.59) |
| Local transform (m) | (0.004801, 0.019277, 0.000250) |
| Assembly context depth | 1 |
| transform2 (m) | (0.036261, -0.025698, 0.127585) |
| **Physical** | |
| Mass | 0.000191 kg (0.191 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4123.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (0.037646, -0.025697, 0.127584) |
| CoM (global, mm) | (37.65, -25.70, 127.58) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485983e-10, 9.436327e-10, 9.436874e-10 |
| Ixy, Ixz, Iyz | -2.328417e-13, 1.910243e-13, -1.881040e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485981e-10, 5.768244e-10, 5.768791e-10 |
| Ixy, Ixz, Iyz | -1.781302e-14, 1.461388e-14, -1.882074e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw_1`

| Property | Value |
|----------|-------|
| Full path | `EG17-G10:1+M3hexagon socket head cap screw (1):8` |
| Component name | M3hexagon socket head cap screw (1) |
| Depth | 1 |
| Path segments | EG17_G10 → M3hexagon_socket_head_cap_screw_1 |
| Parent path | `EG17-G10:1` |
| **Transforms** | |
| Global position (m) | (0.043887, -0.025038, 0.151863) |
| Global position (mm) | (43.89, -25.04, 151.86) |
| Local transform (m) | (0.014542, -0.004242, 0.000250) |
| Assembly context depth | 1 |
| transform2 (m) | (0.043887, -0.025038, 0.151863) |
| **Physical** | |
| Mass | 0.000191 kg (0.191 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4123.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (0.045273, -0.025037, 0.151862) |
| CoM (global, mm) | (45.27, -25.04, 151.86) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485983e-10, 9.436327e-10, 9.436874e-10 |
| Ixy, Ixz, Iyz | -2.328417e-13, 1.910243e-13, -1.881040e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 8.485981e-10, 5.768244e-10, 5.768791e-10 |
| Ixy, Ixz, Iyz | -1.781302e-14, 1.461388e-14, -1.882074e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `input_shaft_1`

| Property | Value |
|----------|-------|
| Full path | `EG17-G10:1+input shaft (1):1` |
| Component name | input shaft (1) |
| Depth | 1 |
| Path segments | EG17_G10 → input_shaft_1 |
| Parent path | `EG17-G10:1` |
| **Transforms** | |
| Global position (m) | (0.054410, -0.050224, 0.135897) |
| Global position (mm) | (54.41, -50.22, 135.90) |
| Local transform (m) | (-0.002088, 0.002647, 0.026250) |
| Assembly context depth | 1 |
| transform2 (m) | (0.054410, -0.050224, 0.135897) |
| **Physical** | |
| Mass | 0.005764 kg (5.764 g) |
| Volume | 1.397989e-06 m³ |
| Density | 4123.0 kg/m³ |
| Surface area | 1.379087e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.006437, 0.000000, -0.000000) |
| CoM (global, m) | (0.060847, -0.050224, 0.135897) |
| CoM (global, mm) | (60.85, -50.22, 135.90) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.491071e-07, 3.903589e-07, 3.986656e-07 |
| Ixy, Ixz, Iyz | -3.535164e-19, 5.581971e-18, -5.969044e-09 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.491071e-07, 1.515334e-07, 1.598401e-07 |
| Ixy, Ixz, Iyz | 3.128624e-19, -6.979164e-18, -5.969044e-09 |
| Bounding box (m) | 0.0125 × 0.0160 × 0.0160 |
| Bounding box (mm) | 12.50 × 16.00 × 15.95 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `nema17input_flange_1`

| Property | Value |
|----------|-------|
| Full path | `EG17-G10:1+nema17input flange (1):1` |
| Component name | nema17input flange (1) |
| Depth | 1 |
| Path segments | EG17_G10 → nema17input_flange_1 |
| Parent path | `EG17-G10:1` |
| **Transforms** | |
| Global position (m) | (0.053504, -0.039763, 0.135897) |
| Global position (mm) | (53.50, -39.76, 135.90) |
| Local transform (m) | (-0.002088, 0.002647, 0.015750) |
| Assembly context depth | 1 |
| transform2 (m) | (0.053504, -0.039763, 0.135897) |
| **Physical** | |
| Mass | 0.126704 kg (126.704 g) |
| Volume | 3.073092e-05 m³ |
| Density | 4123.0 kg/m³ |
| Surface area | 1.149512e-02 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.000000, 0.000000, -0.006001) |
| CoM (global, m) | (0.053504, -0.039763, 0.129895) |
| CoM (global, mm) | (53.50, -39.76, 129.90) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 3.312754e-05, 3.258812e-05, 3.789330e-05 |
| Ixy, Ixz, Iyz | 1.696087e-07, -1.948682e-10, 1.948686e-10 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 2.856433e-05, 2.802491e-05, 3.789330e-05 |
| Ixy, Ixz, Iyz | 1.696087e-07, 3.273582e-11, -3.273615e-11 |
| Bounding box (m) | 0.0420 × 0.0420 × 0.0305 |
| Bounding box (mm) | 42.00 × 42.00 × 30.50 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `10circlip_1`

| Property | Value |
|----------|-------|
| Full path | `EG17-G10:1+¦µ10circlip (1):1` |
| Component name | ¦µ10circlip (1) |
| Depth | 1 |
| Path segments | EG17_G10 → 10circlip_1 |
| Parent path | `EG17-G10:1` |
| **Transforms** | |
| Global position (m) | (0.056669, -0.076327, 0.135897) |
| Global position (mm) | (56.67, -76.33, 135.90) |
| Local transform (m) | (-0.002088, 0.002647, 0.052450) |
| Assembly context depth | 1 |
| transform2 (m) | (0.056669, -0.076327, 0.135897) |
| **Physical** | |
| Mass | 0.000179 kg (0.179 g) |
| Volume | 4.340030e-08 m³ |
| Density | 4123.0 kg/m³ |
| Surface area | 1.718047e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.000000, -0.000500, 0.001176) |
| CoM (global, m) | (0.056669, -0.076827, 0.137073) |
| CoM (global, mm) | (56.67, -76.83, 137.07) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 4.040028e-09, 6.165970e-09, 2.245234e-09 |
| Ixy, Ixz, Iyz | -5.364199e-25, -5.721812e-24, 1.052108e-10 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 3.747851e-09, 5.918527e-09, 2.200499e-09 |
| Ixy, Ixz, Iyz | -4.648972e-25, -5.890024e-24, -2.067952e-25 |
| Bounding box (m) | 0.0115 × 0.0010 × 0.0144 |
| Bounding box (mm) | 11.51 × 1.00 × 14.44 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `6801`

| Property | Value |
|----------|-------|
| Full path | `EG17-G50:1+6801:1` |
| Component name | 6801 |
| Depth | 1 |
| Path segments | EG17_G50 → 6801 |
| Parent path | `EG17-G50:1` |
| **Transforms** | |
| Global position (m) | (-0.027020, 0.080240, 0.060400) |
| Global position (mm) | (-27.02, 80.24, 60.40) |
| Local transform (m) | (-0.002088, 0.002647, 0.009250) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.027020, 0.080240, 0.060400) |
| **Physical** | |
| Mass | 0.005041 kg (5.041 g) |
| Volume | 1.122774e-06 m³ |
| Density | 4490.0 kg/m³ |
| Surface area | 1.026358e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.000000, -0.000000, 0.002500) |
| CoM (global, m) | (-0.027020, 0.080240, 0.062900) |
| CoM (global, mm) | (-27.02, 80.24, 62.90) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 2.259990e-07, 2.259990e-07, 3.694159e-07 |
| Ixy, Ixz, Iyz | 6.978862e-22, -6.104510e-19, 7.965075e-18 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.944911e-07, 1.944911e-07, 3.694159e-07 |
| Ixy, Ixz, Iyz | 6.978862e-22, -6.103762e-19, 2.492451e-23 |
| Bounding box (m) | 0.0210 × 0.0210 × 0.0050 |
| Bounding box (mm) | 21.00 × 21.00 × 5.00 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `EG17_shaft_2`

| Property | Value |
|----------|-------|
| Full path | `EG17-G50:1+EG17 shaft-2:1` |
| Component name | EG17 shaft-2 |
| Depth | 1 |
| Path segments | EG17_G50 → EG17_shaft_2 |
| Parent path | `EG17-G50:1` |
| **Transforms** | |
| Global position (m) | (-0.024261, 0.048359, 0.060400) |
| Global position (mm) | (-24.26, 48.36, 60.40) |
| Local transform (m) | (-0.002088, 0.002647, 0.041250) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.024261, 0.048359, 0.060400) |
| **Physical** | |
| Mass | 0.239584 kg (239.584 g) |
| Volume | 5.335957e-05 m³ |
| Density | 4490.0 kg/m³ |
| Surface area | 9.286610e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.000000, -0.000004, -0.008495) |
| CoM (global, m) | (-0.024261, 0.048355, 0.051905) |
| CoM (global, mm) | (-24.26, 48.35, 51.91) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 7.519585e-05, 7.519859e-05, 5.113149e-05 |
| Ixy, Ixz, Iyz | 1.765845e-15, 2.465976e-19, 2.112537e-08 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 5.790806e-05, 5.791080e-05, 5.113149e-05 |
| Ixy, Ixz, Iyz | 1.765831e-15, -3.034548e-17, 2.910096e-08 |
| Bounding box (m) | 0.0420 × 0.0420 × 0.0595 |
| Bounding box (mm) | 42.00 × 42.00 × 59.50 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Silver_Polished |
| Color (RGB 0-1) | (0.984, 0.980, 0.961) |
| Color (RGB 0-255) | (251, 250, 245) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw`

| Property | Value |
|----------|-------|
| Full path | `EG17-G50:1+M3hexagon socket head cap screw:1` |
| Component name | M3hexagon socket head cap screw |
| Depth | 1 |
| Path segments | EG17_G50 → M3hexagon_socket_head_cap_screw |
| Parent path | `EG17-G50:1` |
| **Transforms** | |
| Global position (m) | (-0.030606, 0.041787, 0.043770) |
| Global position (mm) | (-30.61, 41.79, 43.77) |
| Local transform (m) | (0.004801, 0.019277, 0.047250) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.030606, 0.041787, 0.043770) |
| **Physical** | |
| Mass | 0.000208 kg (0.208 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4490.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (-0.029221, 0.041788, 0.043770) |
| CoM (global, mm) | (-29.22, 41.79, 43.77) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241345e-10, 1.027628e-09, 1.027688e-09 |
| Ixy, Ixz, Iyz | -2.535676e-13, 2.080279e-13, -2.048476e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241342e-10, 6.281692e-10, 6.282287e-10 |
| Ixy, Ixz, Iyz | -1.939861e-14, 1.591470e-14, -2.049603e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw`

| Property | Value |
|----------|-------|
| Full path | `EG17-G50:1+M3hexagon socket head cap screw:2` |
| Component name | M3hexagon socket head cap screw |
| Depth | 1 |
| Path segments | EG17_G50 → M3hexagon_socket_head_cap_screw |
| Parent path | `EG17-G50:1` |
| **Transforms** | |
| Global position (m) | (-0.007175, 0.043815, 0.053512) |
| Global position (mm) | (-7.18, 43.82, 53.51) |
| Local transform (m) | (-0.018717, 0.009535, 0.047250) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.007175, 0.043815, 0.053512) |
| **Physical** | |
| Mass | 0.000208 kg (0.208 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4490.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (-0.005790, 0.043816, 0.053511) |
| CoM (global, mm) | (-5.79, 43.82, 53.51) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241345e-10, 1.027628e-09, 1.027688e-09 |
| Ixy, Ixz, Iyz | -2.535676e-13, 2.080279e-13, -2.048476e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241342e-10, 6.281692e-10, 6.282287e-10 |
| Ixy, Ixz, Iyz | -1.939861e-14, 1.591470e-14, -2.049603e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw`

| Property | Value |
|----------|-------|
| Full path | `EG17-G50:1+M3hexagon socket head cap screw:3` |
| Component name | M3hexagon socket head cap screw |
| Depth | 1 |
| Path segments | EG17_G50 → M3hexagon_socket_head_cap_screw |
| Parent path | `EG17-G50:1` |
| **Transforms** | |
| Global position (m) | (-0.016881, 0.042975, 0.077030) |
| Global position (mm) | (-16.88, 42.98, 77.03) |
| Local transform (m) | (-0.008976, -0.013983, 0.047250) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.016881, 0.042975, 0.077030) |
| **Physical** | |
| Mass | 0.000208 kg (0.208 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4490.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (-0.015495, 0.042976, 0.077029) |
| CoM (global, mm) | (-15.50, 42.98, 77.03) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241345e-10, 1.027628e-09, 1.027688e-09 |
| Ixy, Ixz, Iyz | -2.535676e-13, 2.080279e-13, -2.048476e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241342e-10, 6.281692e-10, 6.282287e-10 |
| Ixy, Ixz, Iyz | -1.939861e-14, 1.591470e-14, -2.049603e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw`

| Property | Value |
|----------|-------|
| Full path | `EG17-G50:1+M3hexagon socket head cap screw:4` |
| Component name | M3hexagon socket head cap screw |
| Depth | 1 |
| Path segments | EG17_G50 → M3hexagon_socket_head_cap_screw |
| Parent path | `EG17-G50:1` |
| **Transforms** | |
| Global position (m) | (-0.040311, 0.040947, 0.067288) |
| Global position (mm) | (-40.31, 40.95, 67.29) |
| Local transform (m) | (0.014542, -0.004242, 0.047250) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.040311, 0.040947, 0.067288) |
| **Physical** | |
| Mass | 0.000208 kg (0.208 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4490.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (-0.038926, 0.040948, 0.067288) |
| CoM (global, mm) | (-38.93, 40.95, 67.29) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241345e-10, 1.027628e-09, 1.027688e-09 |
| Ixy, Ixz, Iyz | -2.535676e-13, 2.080279e-13, -2.048476e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241342e-10, 6.281692e-10, 6.282287e-10 |
| Ixy, Ixz, Iyz | -1.939861e-14, 1.591470e-14, -2.049603e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw`

| Property | Value |
|----------|-------|
| Full path | `EG17-G50:1+M3hexagon socket head cap screw:5` |
| Component name | M3hexagon socket head cap screw |
| Depth | 1 |
| Path segments | EG17_G50 → M3hexagon_socket_head_cap_screw |
| Parent path | `EG17-G50:1` |
| **Transforms** | |
| Global position (m) | (-0.021882, 0.100759, 0.077030) |
| Global position (mm) | (-21.88, 100.76, 77.03) |
| Local transform (m) | (-0.008976, -0.013983, -0.010750) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.021882, 0.100759, 0.077030) |
| **Physical** | |
| Mass | 0.000208 kg (0.208 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4490.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (-0.020497, 0.100760, 0.077029) |
| CoM (global, mm) | (-20.50, 100.76, 77.03) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241345e-10, 1.027628e-09, 1.027688e-09 |
| Ixy, Ixz, Iyz | -2.535676e-13, 2.080279e-13, -2.048476e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241342e-10, 6.281692e-10, 6.282287e-10 |
| Ixy, Ixz, Iyz | -1.939861e-14, 1.591470e-14, -2.049603e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw`

| Property | Value |
|----------|-------|
| Full path | `EG17-G50:1+M3hexagon socket head cap screw:6` |
| Component name | M3hexagon socket head cap screw |
| Depth | 1 |
| Path segments | EG17_G50 → M3hexagon_socket_head_cap_screw |
| Parent path | `EG17-G50:1` |
| **Transforms** | |
| Global position (m) | (-0.012177, 0.101599, 0.053512) |
| Global position (mm) | (-12.18, 101.60, 53.51) |
| Local transform (m) | (-0.018717, 0.009535, -0.010750) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.012177, 0.101599, 0.053512) |
| **Physical** | |
| Mass | 0.000208 kg (0.208 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4490.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (-0.010792, 0.101600, 0.053511) |
| CoM (global, mm) | (-10.79, 101.60, 53.51) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241345e-10, 1.027628e-09, 1.027688e-09 |
| Ixy, Ixz, Iyz | -2.535676e-13, 2.080279e-13, -2.048476e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241342e-10, 6.281692e-10, 6.282287e-10 |
| Ixy, Ixz, Iyz | -1.939861e-14, 1.591470e-14, -2.049603e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw`

| Property | Value |
|----------|-------|
| Full path | `EG17-G50:1+M3hexagon socket head cap screw:7` |
| Component name | M3hexagon socket head cap screw |
| Depth | 1 |
| Path segments | EG17_G50 → M3hexagon_socket_head_cap_screw |
| Parent path | `EG17-G50:1` |
| **Transforms** | |
| Global position (m) | (-0.035607, 0.099571, 0.043770) |
| Global position (mm) | (-35.61, 99.57, 43.77) |
| Local transform (m) | (0.004801, 0.019277, -0.010750) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.035607, 0.099571, 0.043770) |
| **Physical** | |
| Mass | 0.000208 kg (0.208 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4490.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (-0.034222, 0.099572, 0.043770) |
| CoM (global, mm) | (-34.22, 99.57, 43.77) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241345e-10, 1.027628e-09, 1.027688e-09 |
| Ixy, Ixz, Iyz | -2.535676e-13, 2.080279e-13, -2.048476e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241342e-10, 6.281692e-10, 6.282287e-10 |
| Ixy, Ixz, Iyz | -1.939861e-14, 1.591470e-14, -2.049603e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `M3hexagon_socket_head_cap_screw`

| Property | Value |
|----------|-------|
| Full path | `EG17-G50:1+M3hexagon socket head cap screw:8` |
| Component name | M3hexagon socket head cap screw |
| Depth | 1 |
| Path segments | EG17_G50 → M3hexagon_socket_head_cap_screw |
| Parent path | `EG17-G50:1` |
| **Transforms** | |
| Global position (m) | (-0.045313, 0.098731, 0.067288) |
| Global position (mm) | (-45.31, 98.73, 67.29) |
| Local transform (m) | (0.014542, -0.004242, -0.010750) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.045313, 0.098731, 0.067288) |
| **Physical** | |
| Mass | 0.000208 kg (0.208 g) |
| Volume | 4.636304e-08 m³ |
| Density | 4490.0 kg/m³ |
| Surface area | 1.178730e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.001385, 0.000001, -0.000001) |
| CoM (global, m) | (-0.043927, 0.098732, 0.067288) |
| CoM (global, mm) | (-43.93, 98.73, 67.29) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241345e-10, 1.027628e-09, 1.027688e-09 |
| Ixy, Ixz, Iyz | -2.535676e-13, 2.080279e-13, -2.048476e-13 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 9.241342e-10, 6.281692e-10, 6.282287e-10 |
| Ixy, Ixz, Iyz | -1.939861e-14, 1.591470e-14, -2.049603e-13 |
| Bounding box (m) | 0.0030 × 0.0053 × 0.0053 |
| Bounding box (mm) | 3.00 × 5.30 × 5.30 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `input_shaft`

| Property | Value |
|----------|-------|
| Full path | `EG17-G50:1+input shaft:1` |
| Component name | input shaft |
| Depth | 1 |
| Path segments | EG17_G50 → input_shaft |
| Parent path | `EG17-G50:1` |
| **Transforms** | |
| Global position (m) | (-0.026503, 0.074262, 0.060400) |
| Global position (mm) | (-26.50, 74.26, 60.40) |
| Local transform (m) | (-0.002088, 0.002647, 0.015250) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.026503, 0.074262, 0.060400) |
| **Physical** | |
| Mass | 0.006277 kg (6.277 g) |
| Volume | 1.397989e-06 m³ |
| Density | 4490.0 kg/m³ |
| Surface area | 1.379087e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.006437, 0.000000, -0.000000) |
| CoM (global, m) | (-0.020066, 0.074262, 0.060400) |
| CoM (global, mm) | (-20.07, 74.26, 60.40) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.623796e-07, 4.251059e-07, 4.341520e-07 |
| Ixy, Ixz, Iyz | -3.849839e-19, 6.078838e-18, -6.500366e-09 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.623796e-07, 1.650219e-07, 1.740679e-07 |
| Ixy, Ixz, Iyz | 3.407112e-19, -7.600400e-18, -6.500366e-09 |
| Bounding box (m) | 0.0125 × 0.0160 × 0.0160 |
| Bounding box (mm) | 12.50 × 16.00 × 15.95 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `nema17input_flange`

| Property | Value |
|----------|-------|
| Full path | `EG17-G50:1+nema17input flange:1` |
| Component name | nema17input flange |
| Depth | 1 |
| Path segments | EG17_G50 → nema17input_flange |
| Parent path | `EG17-G50:1` |
| **Transforms** | |
| Global position (m) | (-0.027408, 0.084723, 0.060400) |
| Global position (mm) | (-27.41, 84.72, 60.40) |
| Local transform (m) | (-0.002088, 0.002647, 0.004750) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.027408, 0.084723, 0.060400) |
| **Physical** | |
| Mass | 0.137982 kg (137.982 g) |
| Volume | 3.073092e-05 m³ |
| Density | 4490.0 kg/m³ |
| Surface area | 1.149512e-02 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.000000, 0.000000, -0.006001) |
| CoM (global, m) | (-0.027408, 0.084723, 0.054399) |
| CoM (global, mm) | (-27.41, 84.72, 54.40) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 3.607631e-05, 3.548888e-05, 4.126629e-05 |
| Ixy, Ixz, Iyz | 1.847060e-07, -2.122140e-10, 2.122144e-10 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 3.110692e-05, 3.051949e-05, 4.126629e-05 |
| Ixy, Ixz, Iyz | 1.847060e-07, 3.564972e-11, -3.565009e-11 |
| Bounding box (m) | 0.0420 × 0.0420 × 0.0305 |
| Bounding box (mm) | 42.00 × 42.00 × 30.50 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `10circlip`

| Property | Value |
|----------|-------|
| Full path | `EG17-G50:1+¦µ10circlip:1` |
| Component name | ¦µ10circlip |
| Depth | 1 |
| Path segments | EG17_G50 → 10circlip |
| Parent path | `EG17-G50:1` |
| **Transforms** | |
| Global position (m) | (-0.023295, 0.037201, 0.060400) |
| Global position (mm) | (-23.29, 37.20, 60.40) |
| Local transform (m) | (-0.002088, 0.002647, 0.052450) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.023295, 0.037201, 0.060400) |
| **Physical** | |
| Mass | 0.000195 kg (0.195 g) |
| Volume | 4.340030e-08 m³ |
| Density | 4490.0 kg/m³ |
| Surface area | 1.718047e-04 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.000000, -0.000500, 0.001176) |
| CoM (global, m) | (-0.023295, 0.036701, 0.061576) |
| CoM (global, mm) | (-23.29, 36.70, 61.58) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 4.399643e-09, 6.714820e-09, 2.445089e-09 |
| Ixy, Ixz, Iyz | -5.841681e-25, -6.231127e-24, 1.145759e-10 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 4.081458e-09, 6.445352e-09, 2.396372e-09 |
| Ixy, Ixz, Iyz | -5.062790e-25, -6.414312e-24, -2.584939e-25 |
| Bounding box (m) | 0.0115 × 0.0010 × 0.0144 |
| Bounding box (mm) | 11.51 × 1.00 × 14.44 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `Component54`

| Property | Value |
|----------|-------|
| Full path | `GT2 400mm Motor Connector:1+Component54:1` |
| Component name | Component54 |
| Depth | 1 |
| Path segments | GT2_400mm_Motor_Connector → Component54 |
| Parent path | `GT2 400mm Motor Connector:1` |
| **Transforms** | |
| Global position (m) | (0.059153, -0.105019, 0.135897) |
| Global position (mm) | (59.15, -105.02, 135.90) |
| Local transform (m) | (0.196298, -0.029961, 0.035361) |
| Assembly context depth | 1 |
| transform2 (m) | (0.059153, -0.105019, 0.135897) |
| **Physical** | |
| Mass | 0.012921 kg (12.921 g) |
| Volume | 2.949899e-05 m³ |
| Density | 438.0 kg/m³ |
| Surface area | 1.028764e-02 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.000000, 0.000000, 0.004983) |
| CoM (global, m) | (0.059153, -0.105019, 0.140879) |
| CoM (global, mm) | (59.15, -105.02, 140.88) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 3.799688e-06, 3.799688e-06, 6.735600e-06 |
| Ixy, Ixz, Iyz | 6.722303e-20, -1.876643e-19, -1.120384e-20 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 3.478883e-06, 3.478883e-06, 6.735600e-06 |
| Ixy, Ixz, Iyz | 6.722303e-20, -6.360354e-20, -4.070345e-21 |
| Bounding box (m) | 0.0652 × 0.0652 × 0.0100 |
| Bounding box (mm) | 65.15 × 65.15 × 10.00 |
| **Material & Appearance** | |
| Material | PETG_10_Grid_UA_Gear |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 🔧 COMPONENT: `Component52`

| Property | Value |
|----------|-------|
| Full path | `GT2 Elbow Connector:1+Component52:1` |
| Component name | Component52 |
| Depth | 1 |
| Path segments | GT2_Elbow_Connector → Component52 |
| Parent path | `GT2 Elbow Connector:1` |
| **Transforms** | |
| Global position (m) | (0.122551, -0.102543, 0.215314) |
| Global position (mm) | (122.55, -102.54, 215.31) |
| Local transform (m) | (0.012160, -0.022339, 0.102417) |
| Assembly context depth | 1 |
| transform2 (m) | (0.122551, -0.102543, 0.215314) |
| **Physical** | |
| Mass | 0.025855 kg (25.855 g) |
| Volume | 5.298209e-05 m³ |
| Density | 488.0 kg/m³ |
| Surface area | 1.306760e-02 m² |
| Body count | 1 |
| CoM (component-local, m) | (0.000000, 0.000000, 0.011793) |
| CoM (global, m) | (0.122551, -0.102543, 0.227107) |
| CoM (global, mm) | (122.55, -102.54, 227.11) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.098370e-05, 1.098370e-05, 9.494729e-06 |
| Ixy, Ixz, Iyz | 8.876668e-20, -6.588984e-17, 4.438334e-20 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 7.388056e-06, 7.388056e-06, 9.494729e-06 |
| Ixy, Ixz, Iyz | 8.876668e-20, 5.274864e-17, 7.382461e-20 |
| Bounding box (m) | 0.0652 × 0.0652 × 0.0380 |
| Bounding box (mm) | 65.15 × 65.15 × 38.00 |
| **Material & Appearance** | |
| Material | PETG_25_Gryoid_ECA |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 🔧 COMPONENT: `HR32906J_Inner_ring`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:1+HR32906J Inner ring:1` |
| Component name | HR32906J Inner ring |
| Depth | 1 |
| Path segments | Roll_Bearing_2 → HR32906J_Inner_ring |
| Parent path | `Roll Bearing 2:1` |
| **Transforms** | |
| Global position (m) | (0.121430, -0.089591, 0.215314) |
| Global position (mm) | (121.43, -89.59, 215.31) |
| Local transform (m) | (-0.174175, -0.039359, 0.046736) |
| Assembly context depth | 1 |
| transform2 (m) | (0.121430, -0.089591, 0.215314) |
| **Physical** | |
| Mass | 0.045132 kg (45.132 g) |
| Volume | 5.229677e-06 m³ |
| Density | 8630.0 kg/m³ |
| Surface area | 5.054410e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.005434, 0.000000, 0.000000) |
| CoM (global, m) | (0.115996, -0.089591, 0.215314) |
| CoM (global, mm) | (116.00, -89.59, 215.31) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.370829e-05, 8.686935e-06, 8.686846e-06 |
| Ixy, Ixz, Iyz | 2.158523e-11, 4.236266e-11, -6.216943e-11 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.370829e-05, 7.354228e-06, 7.354139e-06 |
| Ixy, Ixz, Iyz | 6.009455e-12, 1.179416e-11, -6.216907e-11 |
| Bounding box (m) | 0.0120 × 0.0432 × 0.0432 |
| Bounding box (mm) | 12.00 × 43.20 × 43.20 |
| **Material & Appearance** | |
| Material | Bearing_Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `HR32906J_Outer_ring`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:1+HR32906J Outer ring:1` |
| Component name | HR32906J Outer ring |
| Depth | 1 |
| Path segments | Roll_Bearing_2 → HR32906J_Outer_ring |
| Parent path | `Roll Bearing 2:1` |
| **Transforms** | |
| Global position (m) | (0.121430, -0.089591, 0.215314) |
| Global position (mm) | (121.43, -89.59, 215.31) |
| Local transform (m) | (-0.174175, -0.039359, 0.046736) |
| Assembly context depth | 1 |
| transform2 (m) | (0.121430, -0.089591, 0.215314) |
| **Physical** | |
| Mass | 0.029417 kg (29.417 g) |
| Volume | 3.408716e-06 m³ |
| Density | 8630.0 kg/m³ |
| Surface area | 3.246179e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.007994, 0.000000, 0.000000) |
| CoM (global, m) | (0.113436, -0.089591, 0.215314) |
| CoM (global, mm) | (113.44, -89.59, 215.31) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.440246e-05, 9.271567e-06, 9.271567e-06 |
| Ixy, Ixz, Iyz | 8.048229e-21, 1.532996e-21, 3.065992e-21 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.440246e-05, 7.391575e-06, 7.391575e-06 |
| Ixy, Ixz, Iyz | 4.371687e-21, 3.074819e-22, 3.065992e-21 |
| Bounding box (m) | 0.0090 × 0.0470 × 0.0470 |
| Bounding box (mm) | 9.00 × 47.00 × 47.00 |
| **Material & Appearance** | |
| Material | Bearing_Steel |
| Appearance | Silver_Polished |
| Color (RGB 0-1) | (0.984, 0.980, 0.961) |
| Color (RGB 0-255) | (251, 250, 245) |

#### 🔧 COMPONENT: `HR32906J_Inner_ring`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:2+HR32906J Inner ring:1` |
| Component name | HR32906J Inner ring |
| Depth | 1 |
| Path segments | Roll_Bearing_2 → HR32906J_Inner_ring |
| Parent path | `Roll Bearing 2:2` |
| **Transforms** | |
| Global position (m) | (0.111341, 0.026973, 0.215314) |
| Global position (mm) | (111.34, 26.97, 215.31) |
| Local transform (m) | (-0.199680, 0.027226, 0.008620) |
| Assembly context depth | 1 |
| transform2 (m) | (0.111341, 0.026973, 0.215314) |
| **Physical** | |
| Mass | 0.045132 kg (45.132 g) |
| Volume | 5.229677e-06 m³ |
| Density | 8630.0 kg/m³ |
| Surface area | 5.054410e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.005434, 0.000000, 0.000000) |
| CoM (global, m) | (0.105907, 0.026973, 0.215314) |
| CoM (global, mm) | (105.91, 26.97, 215.31) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.370829e-05, 8.686935e-06, 8.686846e-06 |
| Ixy, Ixz, Iyz | 2.158523e-11, 4.236266e-11, -6.216943e-11 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.370829e-05, 7.354228e-06, 7.354139e-06 |
| Ixy, Ixz, Iyz | 6.009455e-12, 1.179416e-11, -6.216907e-11 |
| Bounding box (m) | 0.0120 × 0.0432 × 0.0432 |
| Bounding box (mm) | 12.00 × 43.20 × 43.20 |
| **Material & Appearance** | |
| Material | Bearing_Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `HR32906J_Outer_ring`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:2+HR32906J Outer ring:1` |
| Component name | HR32906J Outer ring |
| Depth | 1 |
| Path segments | Roll_Bearing_2 → HR32906J_Outer_ring |
| Parent path | `Roll Bearing 2:2` |
| **Transforms** | |
| Global position (m) | (0.111341, 0.026973, 0.215314) |
| Global position (mm) | (111.34, 26.97, 215.31) |
| Local transform (m) | (-0.199680, 0.027226, 0.008620) |
| Assembly context depth | 1 |
| transform2 (m) | (0.111341, 0.026973, 0.215314) |
| **Physical** | |
| Mass | 0.029417 kg (29.417 g) |
| Volume | 3.408716e-06 m³ |
| Density | 8630.0 kg/m³ |
| Surface area | 3.246179e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.007994, 0.000000, 0.000000) |
| CoM (global, m) | (0.103346, 0.026973, 0.215314) |
| CoM (global, mm) | (103.35, 26.97, 215.31) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.440246e-05, 9.271567e-06, 9.271567e-06 |
| Ixy, Ixz, Iyz | 8.048229e-21, 1.532996e-21, 3.065992e-21 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.440246e-05, 7.391575e-06, 7.391575e-06 |
| Ixy, Ixz, Iyz | 4.371687e-21, 3.074819e-22, 3.065992e-21 |
| Bounding box (m) | 0.0090 × 0.0470 × 0.0470 |
| Bounding box (mm) | 9.00 × 47.00 × 47.00 |
| **Material & Appearance** | |
| Material | Bearing_Steel |
| Appearance | Silver_Polished |
| Color (RGB 0-1) | (0.984, 0.980, 0.961) |
| Color (RGB 0-255) | (251, 250, 245) |

#### 🔧 COMPONENT: `HR32906J_Inner_ring`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:3+HR32906J Inner ring:1` |
| Component name | HR32906J Inner ring |
| Depth | 1 |
| Path segments | Roll_Bearing_2 → HR32906J_Inner_ring |
| Parent path | `Roll Bearing 2:3` |
| **Transforms** | |
| Global position (m) | (0.051623, -0.036915, 0.277482) |
| Global position (mm) | (51.62, -36.91, 277.48) |
| Local transform (m) | (0.019321, -0.132700, 0.115647) |
| Assembly context depth | 1 |
| transform2 (m) | (0.051623, -0.036915, 0.277482) |
| **Physical** | |
| Mass | 0.045132 kg (45.132 g) |
| Volume | 5.229677e-06 m³ |
| Density | 8630.0 kg/m³ |
| Surface area | 5.054410e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.005434, 0.000000, 0.000000) |
| CoM (global, m) | (0.046189, -0.036915, 0.277482) |
| CoM (global, mm) | (46.19, -36.91, 277.48) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.370829e-05, 8.686935e-06, 8.686846e-06 |
| Ixy, Ixz, Iyz | 2.158523e-11, 4.236266e-11, -6.216943e-11 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.370829e-05, 7.354228e-06, 7.354139e-06 |
| Ixy, Ixz, Iyz | 6.009455e-12, 1.179416e-11, -6.216907e-11 |
| Bounding box (m) | 0.0120 × 0.0432 × 0.0432 |
| Bounding box (mm) | 12.00 × 43.20 × 43.20 |
| **Material & Appearance** | |
| Material | Bearing_Steel |
| Appearance | Silver_Polished |
| Color (RGB 0-1) | (0.984, 0.980, 0.961) |
| Color (RGB 0-255) | (251, 250, 245) |

#### 🔧 COMPONENT: `HR32906J_Outer_ring`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:3+HR32906J Outer ring:1` |
| Component name | HR32906J Outer ring |
| Depth | 1 |
| Path segments | Roll_Bearing_2 → HR32906J_Outer_ring |
| Parent path | `Roll Bearing 2:3` |
| **Transforms** | |
| Global position (m) | (0.051623, -0.036915, 0.277482) |
| Global position (mm) | (51.62, -36.91, 277.48) |
| Local transform (m) | (0.019321, -0.132700, 0.115647) |
| Assembly context depth | 1 |
| transform2 (m) | (0.051623, -0.036915, 0.277482) |
| **Physical** | |
| Mass | 0.029417 kg (29.417 g) |
| Volume | 3.408716e-06 m³ |
| Density | 8630.0 kg/m³ |
| Surface area | 3.246179e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.007994, 0.000000, 0.000000) |
| CoM (global, m) | (0.043629, -0.036915, 0.277482) |
| CoM (global, mm) | (43.63, -36.91, 277.48) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.440246e-05, 9.271567e-06, 9.271567e-06 |
| Ixy, Ixz, Iyz | 8.048229e-21, 1.532996e-21, 3.065992e-21 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.440246e-05, 7.391575e-06, 7.391575e-06 |
| Ixy, Ixz, Iyz | 4.371687e-21, 3.074819e-22, 3.065992e-21 |
| Bounding box (m) | 0.0090 × 0.0470 × 0.0470 |
| Bounding box (mm) | 9.00 × 47.00 × 47.00 |
| **Material & Appearance** | |
| Material | Bearing_Steel |
| Appearance | Silver_Polished |
| Color (RGB 0-1) | (0.984, 0.980, 0.961) |
| Color (RGB 0-255) | (251, 250, 245) |

#### 🔧 COMPONENT: `HR32906J_Inner_ring`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:4+HR32906J Inner ring:1` |
| Component name | HR32906J Inner ring |
| Depth | 1 |
| Path segments | Roll_Bearing_2 → HR32906J_Inner_ring |
| Parent path | `Roll Bearing 2:4` |
| **Transforms** | |
| Global position (m) | (0.097141, -0.032975, 0.297298) |
| Global position (mm) | (97.14, -32.98, 297.30) |
| Local transform (m) | (0.175460, -0.081187, 0.025209) |
| Assembly context depth | 1 |
| transform2 (m) | (0.097141, -0.032975, 0.297298) |
| **Physical** | |
| Mass | 0.045132 kg (45.132 g) |
| Volume | 5.229677e-06 m³ |
| Density | 8630.0 kg/m³ |
| Surface area | 5.054410e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.005434, 0.000000, 0.000000) |
| CoM (global, m) | (0.091707, -0.032975, 0.297298) |
| CoM (global, mm) | (91.71, -32.98, 297.30) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.370829e-05, 8.686935e-06, 8.686846e-06 |
| Ixy, Ixz, Iyz | 2.158523e-11, 4.236266e-11, -6.216943e-11 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.370829e-05, 7.354228e-06, 7.354139e-06 |
| Ixy, Ixz, Iyz | 6.009455e-12, 1.179416e-11, -6.216907e-11 |
| Bounding box (m) | 0.0120 × 0.0432 × 0.0432 |
| Bounding box (mm) | 12.00 × 43.20 × 43.20 |
| **Material & Appearance** | |
| Material | Bearing_Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `HR32906J_Outer_ring`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:4+HR32906J Outer ring:1` |
| Component name | HR32906J Outer ring |
| Depth | 1 |
| Path segments | Roll_Bearing_2 → HR32906J_Outer_ring |
| Parent path | `Roll Bearing 2:4` |
| **Transforms** | |
| Global position (m) | (0.097141, -0.032975, 0.297298) |
| Global position (mm) | (97.14, -32.98, 297.30) |
| Local transform (m) | (0.175460, -0.081187, 0.025209) |
| Assembly context depth | 1 |
| transform2 (m) | (0.097141, -0.032975, 0.297298) |
| **Physical** | |
| Mass | 0.029417 kg (29.417 g) |
| Volume | 3.408716e-06 m³ |
| Density | 8630.0 kg/m³ |
| Surface area | 3.246179e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.007994, 0.000000, 0.000000) |
| CoM (global, m) | (0.089147, -0.032975, 0.297298) |
| CoM (global, mm) | (89.15, -32.98, 297.30) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.440246e-05, 9.271567e-06, 9.271567e-06 |
| Ixy, Ixz, Iyz | 8.048229e-21, 1.532996e-21, 3.065992e-21 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.440246e-05, 7.391575e-06, 7.391575e-06 |
| Ixy, Ixz, Iyz | 4.371687e-21, 3.074819e-22, 3.065992e-21 |
| Bounding box (m) | 0.0090 × 0.0470 × 0.0470 |
| Bounding box (mm) | 9.00 × 47.00 × 47.00 |
| **Material & Appearance** | |
| Material | Bearing_Steel |
| Appearance | Silver_Polished |
| Color (RGB 0-1) | (0.984, 0.980, 0.961) |
| Color (RGB 0-255) | (251, 250, 245) |

#### 🔧 COMPONENT: `HR32906J_Inner_ring`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:5+HR32906J Inner ring:1` |
| Component name | HR32906J Inner ring |
| Depth | 1 |
| Path segments | Roll_Bearing_2 → HR32906J_Inner_ring |
| Parent path | `Roll Bearing 2:5` |
| **Transforms** | |
| Global position (m) | (-0.065852, -0.092714, 0.226686) |
| Global position (mm) | (-65.85, -92.71, 226.69) |
| Local transform (m) | (-0.090522, 0.149792, 0.086004) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.065852, -0.092714, 0.226686) |
| **Physical** | |
| Mass | 0.045132 kg (45.132 g) |
| Volume | 5.229677e-06 m³ |
| Density | 8630.0 kg/m³ |
| Surface area | 5.054410e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.005434, 0.000000, 0.000000) |
| CoM (global, m) | (-0.071286, -0.092714, 0.226687) |
| CoM (global, mm) | (-71.29, -92.71, 226.69) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.370829e-05, 8.686935e-06, 8.686846e-06 |
| Ixy, Ixz, Iyz | 2.158523e-11, 4.236266e-11, -6.216943e-11 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.370829e-05, 7.354228e-06, 7.354139e-06 |
| Ixy, Ixz, Iyz | 6.009455e-12, 1.179416e-11, -6.216907e-11 |
| Bounding box (m) | 0.0120 × 0.0432 × 0.0432 |
| Bounding box (mm) | 12.00 × 43.20 × 43.20 |
| **Material & Appearance** | |
| Material | Bearing_Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `HR32906J_Outer_ring`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:5+HR32906J Outer ring:1` |
| Component name | HR32906J Outer ring |
| Depth | 1 |
| Path segments | Roll_Bearing_2 → HR32906J_Outer_ring |
| Parent path | `Roll Bearing 2:5` |
| **Transforms** | |
| Global position (m) | (-0.065852, -0.092714, 0.226686) |
| Global position (mm) | (-65.85, -92.71, 226.69) |
| Local transform (m) | (-0.090522, 0.149792, 0.086004) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.065852, -0.092714, 0.226686) |
| **Physical** | |
| Mass | 0.029417 kg (29.417 g) |
| Volume | 3.408716e-06 m³ |
| Density | 8630.0 kg/m³ |
| Surface area | 3.246179e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.007994, 0.000000, 0.000000) |
| CoM (global, m) | (-0.073846, -0.092714, 0.226686) |
| CoM (global, mm) | (-73.85, -92.71, 226.69) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.440246e-05, 9.271567e-06, 9.271567e-06 |
| Ixy, Ixz, Iyz | 8.048229e-21, 1.532996e-21, 3.065992e-21 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.440246e-05, 7.391575e-06, 7.391575e-06 |
| Ixy, Ixz, Iyz | 4.371687e-21, 3.074819e-22, 3.065992e-21 |
| Bounding box (m) | 0.0090 × 0.0470 × 0.0470 |
| Bounding box (mm) | 9.00 × 47.00 × 47.00 |
| **Material & Appearance** | |
| Material | Bearing_Steel |
| Appearance | Silver_Polished |
| Color (RGB 0-1) | (0.984, 0.980, 0.961) |
| Color (RGB 0-255) | (251, 250, 245) |

#### 🔧 COMPONENT: `HR32906J_Inner_ring`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:6+HR32906J Inner ring:1` |
| Component name | HR32906J Inner ring |
| Depth | 1 |
| Path segments | Roll_Bearing_2 → HR32906J_Inner_ring |
| Parent path | `Roll Bearing 2:6` |
| **Transforms** | |
| Global position (m) | (-0.072200, -0.002002, 0.223232) |
| Global position (mm) | (-72.20, -2.00, 223.23) |
| Local transform (m) | (-0.133560, 0.294910, 0.073869) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.072200, -0.002002, 0.223232) |
| **Physical** | |
| Mass | 0.045132 kg (45.132 g) |
| Volume | 5.229677e-06 m³ |
| Density | 8630.0 kg/m³ |
| Surface area | 5.054410e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.005434, 0.000000, 0.000000) |
| CoM (global, m) | (-0.077634, -0.002002, 0.223232) |
| CoM (global, mm) | (-77.63, -2.00, 223.23) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.370829e-05, 8.686935e-06, 8.686846e-06 |
| Ixy, Ixz, Iyz | 2.158523e-11, 4.236266e-11, -6.216943e-11 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.370829e-05, 7.354228e-06, 7.354139e-06 |
| Ixy, Ixz, Iyz | 6.009455e-12, 1.179416e-11, -6.216907e-11 |
| Bounding box (m) | 0.0120 × 0.0432 × 0.0432 |
| Bounding box (mm) | 12.00 × 43.20 × 43.20 |
| **Material & Appearance** | |
| Material | Bearing_Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `HR32906J_Outer_ring`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:6+HR32906J Outer ring:1` |
| Component name | HR32906J Outer ring |
| Depth | 1 |
| Path segments | Roll_Bearing_2 → HR32906J_Outer_ring |
| Parent path | `Roll Bearing 2:6` |
| **Transforms** | |
| Global position (m) | (-0.072200, -0.002002, 0.223232) |
| Global position (mm) | (-72.20, -2.00, 223.23) |
| Local transform (m) | (-0.133560, 0.294910, 0.073869) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.072200, -0.002002, 0.223232) |
| **Physical** | |
| Mass | 0.029417 kg (29.417 g) |
| Volume | 3.408716e-06 m³ |
| Density | 8630.0 kg/m³ |
| Surface area | 3.246179e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.007994, 0.000000, 0.000000) |
| CoM (global, m) | (-0.080194, -0.002002, 0.223232) |
| CoM (global, mm) | (-80.19, -2.00, 223.23) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.440246e-05, 9.271567e-06, 9.271567e-06 |
| Ixy, Ixz, Iyz | 8.048229e-21, 1.532996e-21, 3.065992e-21 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.440246e-05, 7.391575e-06, 7.391575e-06 |
| Ixy, Ixz, Iyz | 4.371687e-21, 3.074819e-22, 3.065992e-21 |
| Bounding box (m) | 0.0090 × 0.0470 × 0.0470 |
| Bounding box (mm) | 9.00 × 47.00 × 47.00 |
| **Material & Appearance** | |
| Material | Bearing_Steel |
| Appearance | Silver_Polished |
| Color (RGB 0-1) | (0.984, 0.980, 0.961) |
| Color (RGB 0-255) | (251, 250, 245) |

#### 🔧 COMPONENT: `HR32906J_Inner_ring`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:7+HR32906J Inner ring:1` |
| Component name | HR32906J Inner ring |
| Depth | 1 |
| Path segments | Roll_Bearing_2 → HR32906J_Inner_ring |
| Parent path | `Roll Bearing 2:7` |
| **Transforms** | |
| Global position (m) | (-0.112740, -0.049055, 0.260715) |
| Global position (mm) | (-112.74, -49.06, 260.72) |
| Local transform (m) | (-0.019669, 0.129914, 0.177007) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.112740, -0.049055, 0.260715) |
| **Physical** | |
| Mass | 0.045132 kg (45.132 g) |
| Volume | 5.229677e-06 m³ |
| Density | 8630.0 kg/m³ |
| Surface area | 5.054410e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.005434, 0.000000, 0.000000) |
| CoM (global, m) | (-0.118174, -0.049055, 0.260715) |
| CoM (global, mm) | (-118.17, -49.06, 260.72) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.370829e-05, 8.686935e-06, 8.686846e-06 |
| Ixy, Ixz, Iyz | 2.158523e-11, 4.236266e-11, -6.216943e-11 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.370829e-05, 7.354228e-06, 7.354139e-06 |
| Ixy, Ixz, Iyz | 6.009455e-12, 1.179416e-11, -6.216907e-11 |
| Bounding box (m) | 0.0120 × 0.0432 × 0.0432 |
| Bounding box (mm) | 12.00 × 43.20 × 43.20 |
| **Material & Appearance** | |
| Material | Bearing_Steel |
| Appearance | Steel_Satin |
| Color (RGB 0-1) | (0.627, 0.627, 0.627) |
| Color (RGB 0-255) | (160, 160, 160) |

#### 🔧 COMPONENT: `HR32906J_Outer_ring`

| Property | Value |
|----------|-------|
| Full path | `Roll Bearing 2:7+HR32906J Outer ring:1` |
| Component name | HR32906J Outer ring |
| Depth | 1 |
| Path segments | Roll_Bearing_2 → HR32906J_Outer_ring |
| Parent path | `Roll Bearing 2:7` |
| **Transforms** | |
| Global position (m) | (-0.112740, -0.049055, 0.260715) |
| Global position (mm) | (-112.74, -49.06, 260.72) |
| Local transform (m) | (-0.019669, 0.129914, 0.177007) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.112740, -0.049055, 0.260715) |
| **Physical** | |
| Mass | 0.029417 kg (29.417 g) |
| Volume | 3.408716e-06 m³ |
| Density | 8630.0 kg/m³ |
| Surface area | 3.246179e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.007994, 0.000000, 0.000000) |
| CoM (global, m) | (-0.120734, -0.049055, 0.260715) |
| CoM (global, mm) | (-120.73, -49.06, 260.72) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.440246e-05, 9.271567e-06, 9.271567e-06 |
| Ixy, Ixz, Iyz | 8.048229e-21, 1.532996e-21, 3.065992e-21 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.440246e-05, 7.391575e-06, 7.391575e-06 |
| Ixy, Ixz, Iyz | 4.371687e-21, 3.074819e-22, 3.065992e-21 |
| Bounding box (m) | 0.0090 × 0.0470 × 0.0470 |
| Bounding box (mm) | 9.00 × 47.00 × 47.00 |
| **Material & Appearance** | |
| Material | Bearing_Steel |
| Appearance | Silver_Polished |
| Color (RGB 0-1) | (0.984, 0.980, 0.961) |
| Color (RGB 0-255) | (251, 250, 245) |

#### 🔧 COMPONENT: `Component58`

| Property | Value |
|----------|-------|
| Full path | `Shaft Connector:1+Component58:1` |
| Component name | Component58 |
| Depth | 1 |
| Path segments | Shaft_Connector → Component58 |
| Parent path | `Shaft Connector:1` |
| **Transforms** | |
| Global position (m) | (0.051623, -0.036915, 0.277482) |
| Global position (mm) | (51.62, -36.91, 277.48) |
| Local transform (m) | (0.067809, -0.170134, 0.200085) |
| Assembly context depth | 1 |
| transform2 (m) | (0.051623, -0.036915, 0.277482) |
| **Physical** | |
| Mass | 0.028892 kg (28.892 g) |
| Volume | 5.610175e-05 m³ |
| Density | 515.0 kg/m³ |
| Surface area | 1.223441e-02 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.000000, -0.000000, -0.013672) |
| CoM (global, m) | (0.051623, -0.036915, 0.263810) |
| CoM (global, mm) | (51.62, -36.91, 263.81) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 1.830279e-05, 1.830279e-05, 5.505948e-06 |
| Ixy, Ixz, Iyz | 8.782308e-21, -1.318535e-15, -5.269385e-20 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.290215e-05, 1.290215e-05, 5.505948e-06 |
| Ixy, Ixz, Iyz | 8.782308e-21, -2.897136e-16, -4.669028e-20 |
| Bounding box (m) | 0.0524 × 0.0524 × 0.0610 |
| Bounding box (mm) | 52.42 × 52.42 × 61.00 |
| **Material & Appearance** | |
| Material | PET_Plastic |
| Appearance | Plastic_Matte_Black |
| Color (RGB 0-1) | (0.098, 0.098, 0.098) |
| Color (RGB 0-255) | (25, 25, 25) |

#### 🔧 COMPONENT: `92605A009`

| Property | Value |
|----------|-------|
| Full path | `UA Shaft COupler:1+92605A009:1` |
| Component name | 92605A009 |
| Depth | 1 |
| Path segments | UA_Shaft_COupler → 92605A009 |
| Parent path | `UA Shaft COupler:1` |
| **Transforms** | |
| Global position (m) | (0.088714, -0.229094, -0.006704) |
| Global position (mm) | (88.71, -229.09, -6.70) |
| Local transform (m) | (0.000000, 0.008000, 0.006009) |
| Assembly context depth | 1 |
| transform2 (m) | (0.088714, -0.229094, -0.006704) |
| **Physical** | |
| Mass | 0.000000 kg (0.000 g) |
| Volume | 0.000000e+00 m³ |
| Density | 0.0 kg/m³ |
| Surface area | 0.000000e+00 m² |
| Body count | 0 |
| CoM (component-local, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, mm) | (0.00, 0.00, 0.00) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Bounding box (m) | 0.0000 × 0.0000 × 0.0000 |
| Bounding box (mm) | 0.00 × 0.00 × 0.00 |
| **Material & Appearance** | |
| Material |  |
| Appearance |  |

#### 🔧 COMPONENT: `92605A009`

| Property | Value |
|----------|-------|
| Full path | `UA Shaft COupler:1+92605A009:2` |
| Component name | 92605A009 |
| Depth | 1 |
| Path segments | UA_Shaft_COupler → 92605A009 |
| Parent path | `UA Shaft COupler:1` |
| **Transforms** | |
| Global position (m) | (0.082728, -0.229612, -0.012713) |
| Global position (mm) | (82.73, -229.61, -12.71) |
| Local transform (m) | (0.006009, 0.008000, -0.000000) |
| Assembly context depth | 1 |
| transform2 (m) | (0.082728, -0.229612, -0.012713) |
| **Physical** | |
| Mass | 0.000000 kg (0.000 g) |
| Volume | 0.000000e+00 m³ |
| Density | 0.0 kg/m³ |
| Surface area | 0.000000e+00 m² |
| Body count | 0 |
| CoM (component-local, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, mm) | (0.00, 0.00, 0.00) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Bounding box (m) | 0.0000 × 0.0000 × 0.0000 |
| Bounding box (mm) | 0.00 × 0.00 × 0.00 |
| **Material & Appearance** | |
| Material |  |
| Appearance |  |

#### 🔧 COMPONENT: `Connector`

| Property | Value |
|----------|-------|
| Full path | `UA Shaft COupler:1+Connector:1` |
| Component name | Connector |
| Depth | 1 |
| Path segments | UA_Shaft_COupler → Connector |
| Parent path | `UA Shaft COupler:1` |
| **Transforms** | |
| Global position (m) | (-0.021415, 0.015482, 0.060400) |
| Global position (mm) | (-21.41, 15.48, 60.40) |
| Local transform (m) | (0.088628, -0.245162, 0.073113) |
| Assembly context depth | 1 |
| transform2 (m) | (-0.021415, 0.015482, 0.060400) |
| **Physical** | |
| Mass | 0.027734 kg (27.734 g) |
| Volume | 3.533029e-06 m³ |
| Density | 7850.0 kg/m³ |
| Surface area | 2.700970e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.000062, 0.004096, -0.000062) |
| CoM (global, m) | (-0.021477, 0.019578, 0.060338) |
| CoM (global, mm) | (-21.48, 19.58, 60.34) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 2.196173e-06, 2.689968e-06, 2.196171e-06 |
| Ixy, Ixz, Iyz | 1.383799e-08, 5.508889e-13, 1.383902e-08 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.730749e-06, 2.689752e-06, 1.730747e-06 |
| Ixy, Ixz, Iyz | 6.753123e-09, 1.084347e-10, 6.753485e-09 |
| Bounding box (m) | 0.0320 × 0.0130 × 0.0320 |
| Bounding box (mm) | 32.00 × 13.00 × 32.00 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Silver_Polished |
| Color (RGB 0-1) | (0.984, 0.980, 0.961) |
| Color (RGB 0-255) | (251, 250, 245) |

#### 🔧 COMPONENT: `92605A009_1`

| Property | Value |
|----------|-------|
| Full path | `UA Shaft Coupler:1+92605A009 (1):1` |
| Component name | 92605A009 (1) |
| Depth | 1 |
| Path segments | UA_Shaft_Coupler → 92605A009_1 |
| Parent path | `UA Shaft Coupler:1` |
| **Transforms** | |
| Global position (m) | (0.177168, -0.177029, 0.072153) |
| Global position (mm) | (177.17, -177.03, 72.15) |
| Local transform (m) | (-0.000000, 0.008000, 0.006009) |
| Assembly context depth | 1 |
| transform2 (m) | (0.177168, -0.177029, 0.072153) |
| **Physical** | |
| Mass | 0.000000 kg (0.000 g) |
| Volume | 0.000000e+00 m³ |
| Density | 0.0 kg/m³ |
| Surface area | 0.000000e+00 m² |
| Body count | 0 |
| CoM (component-local, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, mm) | (0.00, 0.00, 0.00) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Bounding box (m) | 0.0000 × 0.0000 × 0.0000 |
| Bounding box (mm) | 0.00 × 0.00 × 0.00 |
| **Material & Appearance** | |
| Material |  |
| Appearance |  |

#### 🔧 COMPONENT: `92605A009_1`

| Property | Value |
|----------|-------|
| Full path | `UA Shaft Coupler:1+92605A009 (1):2` |
| Component name | 92605A009 (1) |
| Depth | 1 |
| Path segments | UA_Shaft_Coupler → 92605A009_1 |
| Parent path | `UA Shaft Coupler:1` |
| **Transforms** | |
| Global position (m) | (0.171182, -0.177547, 0.066145) |
| Global position (mm) | (171.18, -177.55, 66.14) |
| Local transform (m) | (0.006009, 0.008000, 0.000000) |
| Assembly context depth | 1 |
| transform2 (m) | (0.171182, -0.177547, 0.066145) |
| **Physical** | |
| Mass | 0.000000 kg (0.000 g) |
| Volume | 0.000000e+00 m³ |
| Density | 0.0 kg/m³ |
| Surface area | 0.000000e+00 m² |
| Body count | 0 |
| CoM (component-local, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, m) | (0.000000, 0.000000, 0.000000) |
| CoM (global, mm) | (0.00, 0.00, 0.00) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Ixy, Ixz, Iyz | 0.000000e+00, 0.000000e+00, 0.000000e+00 |
| Bounding box (m) | 0.0000 × 0.0000 × 0.0000 |
| Bounding box (mm) | 0.00 × 0.00 × 0.00 |
| **Material & Appearance** | |
| Material |  |
| Appearance |  |

#### 🔧 COMPONENT: `Connector_1`

| Property | Value |
|----------|-------|
| Full path | `UA Shaft Coupler:1+Connector (1):1` |
| Component name | Connector (1) |
| Depth | 1 |
| Path segments | UA_Shaft_Coupler → Connector_1 |
| Parent path | `UA Shaft Coupler:1` |
| **Transforms** | |
| Global position (m) | (0.058290, -0.095057, 0.135897) |
| Global position (mm) | (58.29, -95.06, 135.90) |
| Local transform (m) | (0.111366, -0.083918, 0.069752) |
| Assembly context depth | 1 |
| transform2 (m) | (0.058290, -0.095057, 0.135897) |
| **Physical** | |
| Mass | 0.027734 kg (27.734 g) |
| Volume | 3.533029e-06 m³ |
| Density | 7850.0 kg/m³ |
| Surface area | 2.700970e-03 m² |
| Body count | 1 |
| CoM (component-local, m) | (-0.000062, 0.004096, -0.000062) |
| CoM (global, m) | (0.058228, -0.090961, 0.135834) |
| CoM (global, mm) | (58.23, -90.96, 135.83) |
| **Inertia at origin (kg·m²)** | |
| Ixx, Iyy, Izz | 2.196173e-06, 2.689968e-06, 2.196171e-06 |
| Ixy, Ixz, Iyz | 1.383799e-08, 5.508889e-13, 1.383902e-08 |
| **Inertia at CoM (kg·m²)** | |
| Ixx, Iyy, Izz | 1.730749e-06, 2.689752e-06, 1.730747e-06 |
| Ixy, Ixz, Iyz | 6.753123e-09, 1.084347e-10, 6.753485e-09 |
| Bounding box (m) | 0.0320 × 0.0130 × 0.0320 |
| Bounding box (mm) | 32.00 × 13.00 × 32.00 |
| **Material & Appearance** | |
| Material | Steel |
| Appearance | Silver_Polished |
| Color (RGB 0-1) | (0.984, 0.980, 0.961) |
| Color (RGB 0-255) | (251, 250, 245) |

## Joints

#### 🔧 Joint: `Revolute_13` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | revolute (enum=1) |
| Axis | (0.0862, -0.9963, -0.0000) |
| **Connections** | |
| Parent (occ2) | `Shoulder_Bearing_2_Upper` |
| Parent path | `Shoulder Bearing 2 Upper:3` |
| Child (occ1) | `Upper_arm` |
| Child path | `Upper arm:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-0.7531, -14.4918, 6.0400) |
| geometryOrOriginTwo | (-0.7531, -14.4918, 6.0400) |
| occ1.transform | (-1.9690, -0.4444, 6.0400) ctx_depth=0 |
| occ1.global (assembled) | (-1.9690, -0.4444, 6.0400) |
| occ2.transform | (-0.7531, -14.4918, 6.0400) ctx_depth=0 |
| occ2.global (assembled) | (-0.7531, -14.4918, 6.0400) |
| **Picked origin (m)** | (-0.007531, -0.144918, 0.060400) via `geometryOrOriginOne` |
| Rotation limits (rad) | [0.0000, 6.2832] |

#### 🔧 Joint: `Revolute_29` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | revolute (enum=1) |
| Axis | (0.0862, -0.9963, 0.0000) |
| **Connections** | |
| Parent (occ2) | `Elbow_Connector_Passive` |
| Parent path | `Elbow Connector Passive:1` |
| Child (occ1) | `Elbow_Belt_Sensorless` |
| Child path | `Elbow Belt Sensorless:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (11.3497, 0.2066, 21.5314) |
| geometryOrOriginTwo | (11.3497, 0.2066, 21.5314) |
| occ1.transform | (7.4382, -3.4945, 28.7390) ctx_depth=0 |
| occ1.global (assembled) | (7.4382, -3.4945, 28.7390) |
| occ2.transform | (11.1341, 2.6973, 21.5314) ctx_depth=0 |
| occ2.global (assembled) | (11.1341, 2.6973, 21.5314) |
| **Picked origin (m)** | (0.113497, 0.002066, 0.215314) via `geometryOrOriginOne` |
| Rotation limits (rad) | [0.0000, 6.2832] |

#### 🔧 Joint: `Revolute_37` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | revolute (enum=1) |
| Axis | (-0.9140, -0.0791, -0.3979) |
| **Connections** | |
| Parent (occ2) | `Component58` |
| Parent path | `Shaft Connector:1+Component58:1` |
| Child (occ1) | `Motor_Housing_Roll` |
| Child path | `Motor Housing Roll:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (4.1569, -3.7785, 27.3105) |
| geometryOrOriginTwo | (4.1569, -3.7785, 27.3105) |
| occ1.transform | (4.1569, -3.7785, 27.3105) ctx_depth=0 |
| occ1.global (assembled) | (4.1569, -3.7785, 27.3105) |
| occ2.transform | (6.7809, -17.0134, 20.0085) ctx_depth=1 |
| occ2.global (assembled) | (5.1623, -3.6915, 27.7482) |
| **Picked origin (m)** | (0.041569, -0.037785, 0.273105) via `geometryOrOriginOne` |
| Rotation limits (rad) | [0.0000, 6.2832] |

#### 🔧 Joint: `Revolute_43` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | revolute (enum=1) |
| Axis | (-0.0698, 0.9968, -0.0380) |
| **Connections** | |
| Parent (occ2) | `Passive_Cap` |
| Parent path | `Passive Cap:1` |
| Child (occ1) | `Motor_Housing_Yaw` |
| Child path | `Motor Housing Yaw:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-6.7108, -7.4771, 22.6003) |
| geometryOrOriginTwo | (-6.7108, -7.4771, 22.6003) |
| occ1.transform | (-9.7266, -4.8455, 24.8058) ctx_depth=0 |
| occ1.global (assembled) | (-9.7266, -4.8455, 24.8058) |
| occ2.transform | (-6.7108, -7.4771, 22.6003) ctx_depth=0 |
| occ2.global (assembled) | (-6.7108, -7.4771, 22.6003) |
| **Picked origin (m)** | (-0.067108, -0.074771, 0.226003) via `geometryOrOriginOne` |
| Rotation limits (rad) | [0.0000, 6.2832] |

#### 🔧 Joint: `Revolute_46` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | revolute (enum=1) |
| Axis | (-0.7737, -0.0300, 0.6329) |
| **Connections** | |
| Parent (occ2) | `HR32906J_Inner_ring` |
| Parent path | `Roll Bearing 2:7+HR32906J Inner ring:1` |
| Child (occ1) | `Gripper_Shaft` |
| Child path | `Gripper Shaft:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-11.2740, -4.9055, 26.0715) |
| geometryOrOriginTwo | (-11.2740, -4.9055, 26.0715) |
| occ1.transform | (-9.8040, -4.8485, 24.8691) ctx_depth=0 |
| occ1.global (assembled) | (-9.8040, -4.8485, 24.8691) |
| occ2.transform | (-1.9669, 12.9914, 17.7007) ctx_depth=1 |
| occ2.global (assembled) | (-11.2740, -4.9055, 26.0715) |
| **Picked origin (m)** | (-0.112740, -0.049055, 0.260715) via `geometryOrOriginOne` |

#### 🔧 Joint: `Revolute_5` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | revolute (enum=1) |
| Axis | (-0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Shoulder_Bearing_2_Upper` |
| Parent path | `Shoulder Bearing 2 Upper:1` |
| Child (occ1) | `Base_Connector_Shaft_V2` |
| Child path | `Base Connector + Shaft V2:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (0.0000, 0.0000, -0.0600) |
| geometryOrOriginTwo | (0.0000, -0.0000, -0.0600) |
| occ1.transform | (7.4721, 0.6468, 2.5400) ctx_depth=0 |
| occ1.global (assembled) | (7.4721, 0.6468, 2.5400) |
| occ2.transform | (0.0000, 0.0000, -0.0600) ctx_depth=0 |
| occ2.global (assembled) | (0.0000, 0.0000, -0.0600) |
| **Picked origin (m)** | (0.000000, 0.000000, -0.000600) via `geometryOrOriginOne` |
| Rotation limits (rad) | [0.0000, 6.2832] |

#### 🔧 Joint: `Rigid_1` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `base_link` |
| Parent path | `base_link:1` |
| Child (occ1) | `Shoulder_Bearing_2_Lower` |
| Child path | `Shoulder Bearing 2 Lower:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-0.0000, -0.0000, -1.5000) |
| geometryOrOriginTwo | (0.0000, 0.0000, -1.5000) |
| occ1.transform | (0.0000, 0.0000, 0.0000) ctx_depth=0 |
| occ1.global (assembled) | (0.0000, 0.0000, 0.0000) |
| occ2.transform | (0.0000, 0.0000, 0.0000) ctx_depth=0 |
| occ2.global (assembled) | (0.0000, 0.0000, 0.0000) |
| **Picked origin (m)** | (-0.000000, -0.000000, -0.015000) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_10` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Shoulder_Bearing_2_Lower` |
| Parent path | `Shoulder Bearing 2 Lower:2` |
| Child (occ1) | `Shoulder_Bearing_2_Upper` |
| Child path | `Shoulder Bearing 2 Upper:2` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-0.9946, -11.7023, 6.0400) |
| geometryOrOriginTwo | (-0.9946, -11.7023, 6.0400) |
| occ1.transform | (-1.1239, -10.2079, 6.0400) ctx_depth=0 |
| occ1.global (assembled) | (-1.1239, -10.2079, 6.0400) |
| occ2.transform | (-1.1239, -10.2079, 6.0400) ctx_depth=0 |
| occ2.global (assembled) | (-1.1239, -10.2079, 6.0400) |
| **Picked origin (m)** | (-0.009946, -0.117023, 0.060400) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_11` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Bearing_Housing_Shoulder_V2` |
| Parent path | `Bearing Housing Shoulder V2:1` |
| Child (occ1) | `Shoulder_Bearing_2_Lower` |
| Child path | `Shoulder Bearing 2 Lower:3` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-0.8825, -12.9974, 6.0400) |
| geometryOrOriginTwo | (-0.8825, -12.9974, 6.0400) |
| occ1.transform | (-0.7531, -14.4918, 6.0400) ctx_depth=0 |
| occ1.global (assembled) | (-0.7531, -14.4918, 6.0400) |
| occ2.transform | (-0.9385, -12.3499, 6.0400) ctx_depth=0 |
| occ2.global (assembled) | (-0.9385, -12.3499, 6.0400) |
| **Picked origin (m)** | (-0.008825, -0.129974, 0.060400) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_12` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Bearing_Housing_Shoulder_V2` |
| Parent path | `Bearing Housing Shoulder V2:1` |
| Child (occ1) | `Shoulder_Bearing_2_Upper` |
| Child path | `Shoulder Bearing 2 Upper:3` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-0.8825, -12.9974, 6.0400) |
| geometryOrOriginTwo | (-0.8825, -12.9974, 6.0400) |
| occ1.transform | (-0.7531, -14.4918, 6.0400) ctx_depth=0 |
| occ1.global (assembled) | (-0.7531, -14.4918, 6.0400) |
| occ2.transform | (-0.9385, -12.3499, 6.0400) ctx_depth=0 |
| occ2.global (assembled) | (-0.9385, -12.3499, 6.0400) |
| **Picked origin (m)** | (-0.008825, -0.129974, 0.060400) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_14` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Upper_arm` |
| Parent path | `Upper arm:1` |
| Child (occ1) | `Shoulder_Cap` |
| Child path | `Shoulder Cap:2` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-0.7531, -14.4918, 6.0400) |
| geometryOrOriginTwo | (-0.7531, -14.4918, 6.0400) |
| occ1.transform | (-0.7531, -14.4918, 6.0400) ctx_depth=0 |
| occ1.global (assembled) | (-0.7531, -14.4918, 6.0400) |
| occ2.transform | (-1.9690, -0.4444, 6.0400) ctx_depth=0 |
| occ2.global (assembled) | (-1.9690, -0.4444, 6.0400) |
| **Picked origin (m)** | (-0.007531, -0.144918, 0.060400) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_15` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Upper_arm` |
| Parent path | `Upper arm:1` |
| Child (occ1) | `Connector` |
| Child path | `UA Shaft COupler:1+Connector:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-1.3730, 1.6147, 6.9593) |
| geometryOrOriginTwo | (-1.3730, 1.6147, 6.9593) |
| occ1.transform | (8.8628, -24.5162, 7.3113) ctx_depth=1 |
| occ1.global (assembled) | (-2.1415, 1.5482, 6.0400) |
| occ2.transform | (-1.9690, -0.4444, 6.0400) ctx_depth=0 |
| occ2.global (assembled) | (-1.9690, -0.4444, 6.0400) |
| **Picked origin (m)** | (-0.013730, 0.016147, 0.069593) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_16` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Upper_arm` |
| Parent path | `Upper arm:1` |
| Child (occ1) | `HR32906J_Outer_ring` |
| Child path | `Roll Bearing 2:1+HR32906J Outer ring:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (12.0395, -7.7636, 21.5314) |
| geometryOrOriginTwo | (12.0395, -7.7636, 21.5314) |
| occ1.transform | (-17.4175, -3.9359, 4.6736) ctx_depth=1 |
| occ1.global (assembled) | (12.1430, -8.9591, 21.5314) |
| occ2.transform | (-1.9690, -0.4444, 6.0400) ctx_depth=0 |
| occ2.global (assembled) | (-1.9690, -0.4444, 6.0400) |
| **Picked origin (m)** | (0.120395, -0.077636, 0.215314) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_17` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Upper_arm` |
| Parent path | `Upper arm:1` |
| Child (occ1) | `HR32906J_Inner_ring` |
| Child path | `Roll Bearing 2:1+HR32906J Inner ring:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (12.0395, -7.7636, 21.5314) |
| geometryOrOriginTwo | (12.0395, -7.7636, 21.5314) |
| occ1.transform | (-17.4175, -3.9359, 4.6736) ctx_depth=1 |
| occ1.global (assembled) | (12.1430, -8.9591, 21.5314) |
| occ2.transform | (-1.9690, -0.4444, 6.0400) ctx_depth=0 |
| occ2.global (assembled) | (-1.9690, -0.4444, 6.0400) |
| **Picked origin (m)** | (0.120395, -0.077636, 0.215314) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_18` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Upper_arm` |
| Parent path | `Upper arm:1` |
| Child (occ1) | `HR32906J_Outer_ring` |
| Child path | `Roll Bearing 2:2+HR32906J Outer ring:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (11.2376, 1.5017, 21.5314) |
| geometryOrOriginTwo | (11.2376, 1.5017, 21.5314) |
| occ1.transform | (-19.9680, 2.7226, 0.8620) ctx_depth=1 |
| occ1.global (assembled) | (11.1341, 2.6973, 21.5314) |
| occ2.transform | (-1.9690, -0.4444, 6.0400) ctx_depth=0 |
| occ2.global (assembled) | (-1.9690, -0.4444, 6.0400) |
| **Picked origin (m)** | (0.112376, 0.015017, 0.215314) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_19` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Upper_arm` |
| Parent path | `Upper arm:1` |
| Child (occ1) | `HR32906J_Inner_ring` |
| Child path | `Roll Bearing 2:2+HR32906J Inner ring:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (11.2376, 1.5017, 21.5314) |
| geometryOrOriginTwo | (11.2376, 1.5017, 21.5314) |
| occ1.transform | (-19.9680, 2.7226, 0.8620) ctx_depth=1 |
| occ1.global (assembled) | (11.1341, 2.6973, 21.5314) |
| occ2.transform | (-1.9690, -0.4444, 6.0400) ctx_depth=0 |
| occ2.global (assembled) | (-1.9690, -0.4444, 6.0400) |
| **Picked origin (m)** | (0.112376, 0.015017, 0.215314) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_2` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `base_link` |
| Parent path | `base_link:1` |
| Child (occ1) | `Shoulder_Bearing_2_Upper` |
| Child path | `Shoulder Bearing 2 Upper:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (0.0000, 0.0000, -1.5000) |
| geometryOrOriginTwo | (0.0000, 0.0000, -1.5000) |
| occ1.transform | (0.0000, 0.0000, -0.0600) ctx_depth=0 |
| occ1.global (assembled) | (0.0000, 0.0000, -0.0600) |
| occ2.transform | (0.0000, 0.0000, 0.0000) ctx_depth=0 |
| occ2.global (assembled) | (0.0000, 0.0000, 0.0000) |
| **Picked origin (m)** | (0.000000, 0.000000, -0.015000) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_20` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Base_Connector_Shaft_V2` |
| Parent path | `Base Connector + Shaft V2:1` |
| Child (occ1) | `Base_Motor` |
| Child path | `Base Motor:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (5.8777, -11.2580, 0.7400) |
| geometryOrOriginTwo | (5.8777, -11.2580, 0.7400) |
| occ1.transform | (5.8777, -11.2580, 6.7400) ctx_depth=0 |
| occ1.global (assembled) | (5.8777, -11.2580, 6.7400) |
| occ2.transform | (7.4721, 0.6468, 2.5400) ctx_depth=0 |
| occ2.global (assembled) | (7.4721, 0.6468, 2.5400) |
| **Picked origin (m)** | (0.058777, -0.112580, 0.007400) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_21` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Motor_Connector_Shoulder` |
| Parent path | `Motor Connector Shoulder:1` |
| Child (occ1) | `EG17_shaft_2` |
| Child path | `EG17-G50:1+EG17 shaft-2:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-2.3398, 3.8396, 6.0400) |
| geometryOrOriginTwo | (-2.3398, 3.8396, 6.0400) |
| occ1.transform | (-0.2088, 0.2647, 4.1250) ctx_depth=1 |
| occ1.global (assembled) | (-2.4261, 4.8359, 6.0400) |
| occ2.transform | (-2.2708, 3.0426, 6.0400) ctx_depth=0 |
| occ2.global (assembled) | (-2.2708, 3.0426, 6.0400) |
| **Picked origin (m)** | (-0.023398, 0.038396, 0.060400) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_22` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `nema17input_flange` |
| Parent path | `EG17-G50:1+nema17input flange:1` |
| Child (occ1) | `Shoulder_Motor` |
| Child path | `Shoulder Motor:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-2.9133, 10.4648, 6.0400) |
| geometryOrOriginTwo | (-2.9133, 10.4648, 6.0400) |
| occ1.transform | (-3.4307, 16.4425, 6.0400) ctx_depth=0 |
| occ1.global (assembled) | (-3.4307, 16.4425, 6.0400) |
| occ2.transform | (-0.2088, 0.2647, 0.4750) ctx_depth=1 |
| occ2.global (assembled) | (-2.7408, 8.4723, 6.0400) |
| **Picked origin (m)** | (-0.029133, 0.104648, 0.060400) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_23` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Upper_arm` |
| Parent path | `Upper arm:1` |
| Child (occ1) | `EG17_shaft` |
| Child path | `EG17-G10:1+EG17 shaft:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (5.6566, -7.5131, 13.5897) |
| geometryOrOriginTwo | (5.6566, -7.5131, 13.5897) |
| occ1.transform | (-0.2088, 0.2647, 4.1250) ctx_depth=1 |
| occ1.global (assembled) | (5.5703, -6.5168, 13.5897) |
| occ2.transform | (-1.9690, -0.4444, 6.0400) ctx_depth=0 |
| occ2.global (assembled) | (-1.9690, -0.4444, 6.0400) |
| **Picked origin (m)** | (0.056566, -0.075131, 0.135897) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_24` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `nema17input_flange_1` |
| Parent path | `EG17-G10:1+nema17input flange (1):1` |
| Child (occ1) | `UA_Motor` |
| Child path | `UA Motor:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (5.1780, -1.9838, 13.5897) |
| geometryOrOriginTwo | (5.1780, -1.9838, 13.5897) |
| occ1.transform | (5.1780, -1.9838, 13.5897) ctx_depth=0 |
| occ1.global (assembled) | (5.1780, -1.9838, 13.5897) |
| occ2.transform | (-0.2088, 0.2647, 1.5750) ctx_depth=1 |
| occ2.global (assembled) | (5.3504, -3.9763, 13.5897) |
| **Picked origin (m)** | (0.051780, -0.019838, 0.135897) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_25` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `HR32906J_Inner_ring` |
| Parent path | `Roll Bearing 2:2+HR32906J Inner ring:1` |
| Child (occ1) | `Elbow_Connector_Passive` |
| Child path | `Elbow Connector Passive:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (11.1341, 2.6973, 21.5314) |
| geometryOrOriginTwo | (11.1341, 2.6973, 21.5314) |
| occ1.transform | (11.1341, 2.6973, 21.5314) ctx_depth=0 |
| occ1.global (assembled) | (11.1341, 2.6973, 21.5314) |
| occ2.transform | (-19.9680, 2.7226, 0.8620) ctx_depth=1 |
| occ2.global (assembled) | (11.1341, 2.6973, 21.5314) |
| **Picked origin (m)** | (0.111341, 0.026973, 0.215314) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_26` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `HR32906J_Inner_ring` |
| Parent path | `Roll Bearing 2:1+HR32906J Inner ring:1` |
| Child (occ1) | `Component52` |
| Child path | `GT2 Elbow Connector:1+Component52:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (12.1430, -8.9591, 21.5314) |
| geometryOrOriginTwo | (12.1430, -8.9591, 21.5314) |
| occ1.transform | (1.2160, -2.2339, 10.2417) ctx_depth=1 |
| occ1.global (assembled) | (12.2551, -10.2543, 21.5314) |
| occ2.transform | (-17.4175, -3.9359, 4.6736) ctx_depth=1 |
| occ2.global (assembled) | (12.1430, -8.9591, 21.5314) |
| **Picked origin (m)** | (0.121430, -0.089591, 0.215314) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_27` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Upper_arm` |
| Parent path | `Upper arm:1` |
| Child (occ1) | `Component54` |
| Child path | `GT2 400mm Motor Connector:1+Component54:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (5.8290, -9.5057, 13.5897) |
| geometryOrOriginTwo | (5.8290, -9.5057, 13.5897) |
| occ1.transform | (19.6298, -2.9961, 3.5361) ctx_depth=1 |
| occ1.global (assembled) | (5.9153, -10.5019, 13.5897) |
| occ2.transform | (-1.9690, -0.4444, 6.0400) ctx_depth=0 |
| occ2.global (assembled) | (-1.9690, -0.4444, 6.0400) |
| **Picked origin (m)** | (0.058290, -0.095057, 0.135897) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_28` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Component54` |
| Parent path | `GT2 400mm Motor Connector:1+Component54:1` |
| Child (occ1) | `Connector_1` |
| Child path | `UA Shaft Coupler:1+Connector (1):1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (5.8290, -9.5057, 13.5897) |
| geometryOrOriginTwo | (5.8290, -9.5057, 13.5897) |
| occ1.transform | (11.1366, -8.3918, 6.9752) ctx_depth=1 |
| occ1.global (assembled) | (5.8290, -9.5057, 13.5897) |
| occ2.transform | (19.6298, -2.9961, 3.5361) ctx_depth=1 |
| occ2.global (assembled) | (5.9153, -10.5019, 13.5897) |
| **Picked origin (m)** | (0.058290, -0.095057, 0.135897) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_3` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `base_link` |
| Parent path | `base_link:1` |
| Child (occ1) | `Lower_Bottom_Base_Bearing_Ring` |
| Child path | `Lower Bottom Base Bearing Ring:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (0.0000, -0.0000, -3.6000) |
| geometryOrOriginTwo | (0.0000, 0.0000, -3.6000) |
| occ1.transform | (-2.7200, -5.6181, 7.0740) ctx_depth=0 |
| occ1.global (assembled) | (-2.7200, -5.6181, 7.0740) |
| occ2.transform | (0.0000, 0.0000, 0.0000) ctx_depth=0 |
| occ2.global (assembled) | (0.0000, 0.0000, 0.0000) |
| **Picked origin (m)** | (0.000000, -0.000000, -0.036000) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_30` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Elbow_Belt_Sensorless` |
| Parent path | `Elbow Belt Sensorless:1` |
| Child (occ1) | `Elbow_Motor` |
| Child path | `Elbow Motor:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (9.3689, -3.3274, 19.9984) |
| geometryOrOriginTwo | (9.3689, -3.3274, 19.9984) |
| occ1.transform | (9.3689, -3.3274, 19.9984) ctx_depth=0 |
| occ1.global (assembled) | (9.3689, -3.3274, 19.9984) |
| occ2.transform | (7.4382, -3.4945, 28.7390) ctx_depth=0 |
| occ2.global (assembled) | (7.4382, -3.4945, 28.7390) |
| **Picked origin (m)** | (0.093689, -0.033274, 0.199984) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_31` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Elbow_Belt_Sensorless` |
| Parent path | `Elbow Belt Sensorless:1` |
| Child (occ1) | `HR32906J_Outer_ring` |
| Child path | `Roll Bearing 2:3+HR32906J Outer ring:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (6.2591, -3.5966, 28.2257) |
| geometryOrOriginTwo | (6.2591, -3.5966, 28.2257) |
| occ1.transform | (1.9321, -13.2700, 11.5647) ctx_depth=1 |
| occ1.global (assembled) | (5.1623, -3.6915, 27.7482) |
| occ2.transform | (7.4382, -3.4945, 28.7390) ctx_depth=0 |
| occ2.global (assembled) | (7.4382, -3.4945, 28.7390) |
| **Picked origin (m)** | (0.062591, -0.035966, 0.282257) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_32` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Elbow_Belt_Sensorless` |
| Parent path | `Elbow Belt Sensorless:1` |
| Child (occ1) | `HR32906J_Inner_ring` |
| Child path | `Roll Bearing 2:3+HR32906J Inner ring:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (6.2591, -3.5966, 28.2257) |
| geometryOrOriginTwo | (6.2591, -3.5966, 28.2257) |
| occ1.transform | (1.9321, -13.2700, 11.5647) ctx_depth=1 |
| occ1.global (assembled) | (5.1623, -3.6915, 27.7482) |
| occ2.transform | (7.4382, -3.4945, 28.7390) ctx_depth=0 |
| occ2.global (assembled) | (7.4382, -3.4945, 28.7390) |
| **Picked origin (m)** | (0.062591, -0.035966, 0.282257) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_33` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Elbow_Belt_Sensorless` |
| Parent path | `Elbow Belt Sensorless:1` |
| Child (occ1) | `HR32906J_Outer_ring` |
| Child path | `Roll Bearing 2:4+HR32906J Outer ring:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (8.6173, -3.3924, 29.2523) |
| geometryOrOriginTwo | (8.6173, -3.3924, 29.2523) |
| occ1.transform | (17.5460, -8.1187, 2.5209) ctx_depth=1 |
| occ1.global (assembled) | (9.7141, -3.2975, 29.7298) |
| occ2.transform | (7.4382, -3.4945, 28.7390) ctx_depth=0 |
| occ2.global (assembled) | (7.4382, -3.4945, 28.7390) |
| **Picked origin (m)** | (0.086173, -0.033924, 0.292523) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_34` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Elbow_Belt_Sensorless` |
| Parent path | `Elbow Belt Sensorless:1` |
| Child (occ1) | `HR32906J_Inner_ring` |
| Child path | `Roll Bearing 2:4+HR32906J Inner ring:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (8.6173, -3.3924, 29.2523) |
| geometryOrOriginTwo | (8.6173, -3.3924, 29.2523) |
| occ1.transform | (17.5460, -8.1187, 2.5209) ctx_depth=1 |
| occ1.global (assembled) | (9.7141, -3.2975, 29.7298) |
| occ2.transform | (7.4382, -3.4945, 28.7390) ctx_depth=0 |
| occ2.global (assembled) | (7.4382, -3.4945, 28.7390) |
| **Picked origin (m)** | (0.086173, -0.033924, 0.292523) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_35` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `HR32906J_Inner_ring` |
| Parent path | `Roll Bearing 2:3+HR32906J Inner ring:1` |
| Child (occ1) | `Component58` |
| Child path | `Shaft Connector:1+Component58:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (5.1623, -3.6915, 27.7482) |
| geometryOrOriginTwo | (5.1623, -3.6915, 27.7482) |
| occ1.transform | (6.7809, -17.0134, 20.0085) ctx_depth=1 |
| occ1.global (assembled) | (5.1623, -3.6915, 27.7482) |
| occ2.transform | (1.9321, -13.2700, 11.5647) ctx_depth=1 |
| occ2.global (assembled) | (5.1623, -3.6915, 27.7482) |
| **Picked origin (m)** | (0.051623, -0.036915, 0.277482) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_36` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Component58` |
| Parent path | `Shaft Connector:1+Component58:1` |
| Child (occ1) | `Elbow_Cap` |
| Child path | `Elbow Cap:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (9.7324, -3.2959, 29.7377) |
| geometryOrOriginTwo | (9.7324, -3.2959, 29.7377) |
| occ1.transform | (10.0980, -3.2643, 29.8969) ctx_depth=0 |
| occ1.global (assembled) | (10.0980, -3.2643, 29.8969) |
| occ2.transform | (6.7809, -17.0134, 20.0085) ctx_depth=1 |
| occ2.global (assembled) | (5.1623, -3.6915, 27.7482) |
| **Picked origin (m)** | (0.097324, -0.032959, 0.297377) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_38` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Motor_Housing_Roll` |
| Parent path | `Motor Housing Roll:1` |
| Child (occ1) | `Roll_Motor` |
| Child path | `Roll Motor:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (0.8721, -0.2018, 25.8513) |
| geometryOrOriginTwo | (0.8721, -0.2018, 25.8513) |
| occ1.transform | (0.8721, -0.2018, 25.8513) ctx_depth=0 |
| occ1.global (assembled) | (0.8721, -0.2018, 25.8513) |
| occ2.transform | (4.1569, -3.7785, 27.3105) ctx_depth=0 |
| occ2.global (assembled) | (4.1569, -3.7785, 27.3105) |
| **Picked origin (m)** | (0.008721, -0.002018, 0.258513) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_39` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Motor_Housing_Roll` |
| Parent path | `Motor Housing Roll:1` |
| Child (occ1) | `HR32906J_Outer_ring` |
| Child path | `Roll Bearing 2:5+HR32906J Outer ring:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-6.6689, -8.0752, 22.6231) |
| geometryOrOriginTwo | (-6.6689, -8.0752, 22.6231) |
| occ1.transform | (-9.0522, 14.9792, 8.6004) ctx_depth=1 |
| occ1.global (assembled) | (-6.5852, -9.2714, 22.6686) |
| occ2.transform | (4.1569, -3.7785, 27.3105) ctx_depth=0 |
| occ2.global (assembled) | (4.1569, -3.7785, 27.3105) |
| **Picked origin (m)** | (-0.066689, -0.080752, 0.226231) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_4` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `base_link` |
| Parent path | `base_link:1` |
| Child (occ1) | `Lower_Upper_Base_Bearing_Ring` |
| Child path | `Lower Upper Base Bearing Ring:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (0.0000, 0.0000, -3.6000) |
| geometryOrOriginTwo | (0.0000, 0.0000, -3.6000) |
| occ1.transform | (-2.7200, -5.6181, 7.0740) ctx_depth=0 |
| occ1.global (assembled) | (-2.7200, -5.6181, 7.0740) |
| occ2.transform | (0.0000, 0.0000, 0.0000) ctx_depth=0 |
| occ2.global (assembled) | (0.0000, 0.0000, 0.0000) |
| **Picked origin (m)** | (0.000000, 0.000000, -0.036000) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_40` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Motor_Housing_Roll` |
| Parent path | `Motor Housing Roll:1` |
| Child (occ1) | `HR32906J_Outer_ring` |
| Child path | `Roll Bearing 2:6+HR32906J Outer ring:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-7.1363, -1.3964, 22.3688) |
| geometryOrOriginTwo | (-7.1363, -1.3964, 22.3688) |
| occ1.transform | (-13.3560, 29.4910, 7.3869) ctx_depth=1 |
| occ1.global (assembled) | (-7.2200, -0.2002, 22.3232) |
| occ2.transform | (4.1569, -3.7785, 27.3105) ctx_depth=0 |
| occ2.global (assembled) | (4.1569, -3.7785, 27.3105) |
| **Picked origin (m)** | (-0.071363, -0.013964, 0.223688) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_41` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `HR32906J_Inner_ring` |
| Parent path | `Roll Bearing 2:5+HR32906J Inner ring:1` |
| Child (occ1) | `Passive_Cap` |
| Child path | `Passive Cap:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-6.5852, -9.2714, 22.6686) |
| geometryOrOriginTwo | (-6.5852, -9.2714, 22.6686) |
| occ1.transform | (-6.7108, -7.4771, 22.6003) ctx_depth=0 |
| occ1.global (assembled) | (-6.7108, -7.4771, 22.6003) |
| occ2.transform | (-9.0522, 14.9792, 8.6004) ctx_depth=1 |
| occ2.global (assembled) | (-6.5852, -9.2714, 22.6686) |
| **Picked origin (m)** | (-0.065852, -0.092714, 0.226686) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_42` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `HR32906J_Inner_ring` |
| Parent path | `Roll Bearing 2:6+HR32906J Inner ring:1` |
| Child (occ1) | `Component64` |
| Child path | `Belt Shaft:1+Component64:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-7.2200, -0.2002, 22.3232) |
| geometryOrOriginTwo | (-7.2200, -0.2002, 22.3232) |
| occ1.transform | (0.0000, 0.0000, 0.0000) ctx_depth=1 |
| occ1.global (assembled) | (-7.3037, 0.9960, 22.2777) |
| occ2.transform | (-13.3560, 29.4910, 7.3869) ctx_depth=1 |
| occ2.global (assembled) | (-7.2200, -0.2002, 22.3232) |
| **Picked origin (m)** | (-0.072200, -0.002002, 0.223232) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_44` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Motor_Housing_Yaw` |
| Parent path | `Motor Housing Yaw:1` |
| Child (occ1) | `HR32906J_Outer_ring` |
| Child path | `Roll Bearing 2:7+HR32906J Outer ring:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-10.3455, -4.8695, 25.3121) |
| geometryOrOriginTwo | (-10.3455, -4.8695, 25.3121) |
| occ1.transform | (-1.9669, 12.9914, 17.7007) ctx_depth=1 |
| occ1.global (assembled) | (-11.2740, -4.9055, 26.0715) |
| occ2.transform | (-9.7266, -4.8455, 24.8058) ctx_depth=0 |
| occ2.global (assembled) | (-9.7266, -4.8455, 24.8058) |
| **Picked origin (m)** | (-0.103455, -0.048695, 0.253121) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_45` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Motor_Housing_Yaw` |
| Parent path | `Motor Housing Yaw:1` |
| Child (occ1) | `Yaw_Motor` |
| Child path | `Yaw Motor:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-8.0631, -4.7809, 23.4452) |
| geometryOrOriginTwo | (-8.0631, -4.7809, 23.4452) |
| occ1.transform | (-6.4771, -4.7193, 22.1479) ctx_depth=0 |
| occ1.global (assembled) | (-6.4771, -4.7193, 22.1479) |
| occ2.transform | (-9.7266, -4.8455, 24.8058) ctx_depth=0 |
| occ2.global (assembled) | (-9.7266, -4.8455, 24.8058) |
| **Picked origin (m)** | (-0.080631, -0.047809, 0.234452) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_54` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Shoulder_Cap` |
| Parent path | `Shoulder Cap:2` |
| Child (occ1) | `ua` |
| Child path | `!frame_ua:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-0.7100, -14.9900, 6.0400) |
| geometryOrOriginTwo | (-0.7100, -14.9900, 6.0400) |
| occ1.transform | (-0.7100, -14.9900, 6.0400) ctx_depth=0 |
| occ1.global (assembled) | (-0.7100, -14.9900, 6.0400) |
| occ2.transform | (-0.7531, -14.4918, 6.0400) ctx_depth=0 |
| occ2.global (assembled) | (-0.7531, -14.4918, 6.0400) |
| **Picked origin (m)** | (-0.007100, -0.149900, 0.060400) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_55` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Component52` |
| Parent path | `GT2 Elbow Connector:1+Component52:1` |
| Child (occ1) | `elbow` |
| Child path | `!frame_elbow:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (12.2551, -10.2543, 21.5314) |
| geometryOrOriginTwo | (12.2551, -10.2543, 21.5314) |
| occ1.transform | (12.2551, -10.2543, 21.5314) ctx_depth=0 |
| occ1.global (assembled) | (12.2551, -10.2543, 21.5314) |
| occ2.transform | (1.2160, -2.2339, 10.2417) ctx_depth=1 |
| occ2.global (assembled) | (12.2551, -10.2543, 21.5314) |
| **Picked origin (m)** | (0.122551, -0.102543, 0.215314) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_56` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Elbow_Cap` |
| Parent path | `Elbow Cap:1` |
| Child (occ1) | `roll` |
| Child path | `!frame_roll:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (10.0980, -3.2643, 29.8969) |
| geometryOrOriginTwo | (10.0980, -3.2643, 29.8969) |
| occ1.transform | (10.0980, -3.2643, 29.8969) ctx_depth=0 |
| occ1.global (assembled) | (10.0980, -3.2643, 29.8969) |
| occ2.transform | (10.0980, -3.2643, 29.8969) ctx_depth=0 |
| occ2.global (assembled) | (10.0980, -3.2643, 29.8969) |
| **Picked origin (m)** | (0.100980, -0.032643, 0.298969) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_57` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Passive_Cap` |
| Parent path | `Passive Cap:1` |
| Child (occ1) | `yaw` |
| Child path | `!frame_yaw:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-6.5503, -9.7698, 22.6876) |
| geometryOrOriginTwo | (-6.5503, -9.7698, 22.6876) |
| occ1.transform | (-6.5503, -9.7698, 22.6876) ctx_depth=0 |
| occ1.global (assembled) | (-6.5503, -9.7698, 22.6876) |
| occ2.transform | (-6.7108, -7.4771, 22.6003) ctx_depth=0 |
| occ2.global (assembled) | (-6.7108, -7.4771, 22.6003) |
| **Picked origin (m)** | (-0.065503, -0.097698, 0.226876) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_58` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Gripper_Shaft` |
| Parent path | `Gripper Shaft:1` |
| Child (occ1) | `gripper` |
| Child path | `!frame_gripper:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-12.4345, -4.9506, 27.0208) |
| geometryOrOriginTwo | (-12.4345, -4.9506, 27.0208) |
| occ1.transform | (-12.4345, -4.9506, 27.0208) ctx_depth=0 |
| occ1.global (assembled) | (-12.4345, -4.9506, 27.0208) |
| occ2.transform | (-9.8040, -4.8485, 24.8691) ctx_depth=0 |
| occ2.global (assembled) | (-9.8040, -4.8485, 24.8691) |
| **Picked origin (m)** | (-0.124345, -0.049506, 0.270208) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_59` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Base_Connector_Shaft_V2` |
| Parent path | `Base Connector + Shaft V2:1` |
| Child (occ1) | `shoulder` |
| Child path | `!frame_shoulder:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (0.0000, 0.0000, -5.1500) |
| geometryOrOriginTwo | (0.0000, 0.0000, -5.1500) |
| occ1.transform | (0.0000, 0.0000, -5.1500) ctx_depth=0 |
| occ1.global (assembled) | (0.0000, 0.0000, -5.1500) |
| occ2.transform | (7.4721, 0.6468, 2.5400) ctx_depth=0 |
| occ2.global (assembled) | (7.4721, 0.6468, 2.5400) |
| **Picked origin (m)** | (0.000000, 0.000000, -0.051500) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_7` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Base_Connector_Shaft_V2` |
| Parent path | `Base Connector + Shaft V2:1` |
| Child (occ1) | `Motor_Connector_Shoulder` |
| Child path | `Motor Connector Shoulder:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (0.1681, 3.8559, 2.5400) |
| geometryOrOriginTwo | (0.1681, 3.8559, 2.5400) |
| occ1.transform | (-2.2708, 3.0426, 6.0400) ctx_depth=0 |
| occ1.global (assembled) | (-2.2708, 3.0426, 6.0400) |
| occ2.transform | (7.4721, 0.6468, 2.5400) ctx_depth=0 |
| occ2.global (assembled) | (7.4721, 0.6468, 2.5400) |
| **Picked origin (m)** | (0.001681, 0.038559, 0.025400) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_8` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Base_Connector_Shaft_V2` |
| Parent path | `Base Connector + Shaft V2:1` |
| Child (occ1) | `Bearing_Housing_Shoulder_V2` |
| Child path | `Bearing Housing Shoulder V2:1` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (1.1522, -10.4123, 2.5400) |
| geometryOrOriginTwo | (1.1522, -10.4123, 2.5400) |
| occ1.transform | (-0.9385, -12.3499, 6.0400) ctx_depth=0 |
| occ1.global (assembled) | (-0.9385, -12.3499, 6.0400) |
| occ2.transform | (7.4721, 0.6468, 2.5400) ctx_depth=0 |
| occ2.global (assembled) | (7.4721, 0.6468, 2.5400) |
| **Picked origin (m)** | (0.011522, -0.104123, 0.025400) via `geometryOrOriginOne` |

#### 🔧 Joint: `Rigid_9` (regular)

| Property | Value |
|----------|-------|
| Defining component | 6DOF_URDF (6DOF URDF) |
| Suppressed | False |
| Motion type | rigid (enum=0) |
| Axis | (0.0000, 0.0000, 1.0000) |
| **Connections** | |
| Parent (occ2) | `Bearing_Housing_Shoulder_V2` |
| Parent path | `Bearing Housing Shoulder V2:1` |
| Child (occ1) | `Shoulder_Bearing_2_Lower` |
| Child path | `Shoulder Bearing 2 Lower:2` |
| **Geometry (all sources, raw cm)** | |
| geometryOrOriginOne | (-0.9946, -11.7023, 6.0400) |
| geometryOrOriginTwo | (-0.9946, -11.7023, 6.0400) |
| occ1.transform | (-1.1239, -10.2079, 6.0400) ctx_depth=0 |
| occ1.global (assembled) | (-1.1239, -10.2079, 6.0400) |
| occ2.transform | (-0.9385, -12.3499, 6.0400) ctx_depth=0 |
| occ2.global (assembled) | (-0.9385, -12.3499, 6.0400) |
| **Picked origin (m)** | (-0.009946, -0.117023, 0.060400) via `geometryOrOriginOne` |

## Quick Comparison Table

Compare these values with Fusion 360 Properties panel (right-click → Properties).

| Component | Mass (g) | World X,Y,Z (mm) | CoM X,Y,Z (mm) | Material |
|-----------|----------|-------------------|-----------------|----------|
| elbow | 0.000 | (122.55, -102.54, 215.31) | (0.00, 0.00, 0.00) |  |
| gripper | 0.000 | (-124.35, -49.51, 270.21) | (0.00, 0.00, 0.00) |  |
| roll | 0.000 | (100.98, -32.64, 298.97) | (0.00, 0.00, 0.00) |  |
| shoulder | 0.000 | (0.00, 0.00, -51.50) | (0.00, 0.00, 0.00) |  |
| ua | 0.000 | (-7.10, -149.90, 60.40) | (0.00, 0.00, 0.00) |  |
| yaw | 0.000 | (-65.50, -97.70, 226.88) | (0.00, 0.00, 0.00) |  |
| Base_Connector_Shaft_V2 | 315.930 | (74.72, 6.47, 25.40) | (151.22, 43.42, 10.50) | PETG_25_Gyroid |
| Base_Motor | 498.902 | (58.78, -112.58, 67.40) | (58.78, -112.60, 97.73) | Base_Motor |
| Bearing_Housing_Shoulder_V2 | 39.267 | (-9.39, -123.50, 60.40) | (-9.39, -131.39, 60.46) | PETG_20_CH_BSH |
| Component64 | 14.791 | (-73.04, 9.96, 222.78) | (-73.04, 9.96, 233.45) | Active_Cap_Roll |
| 6801_1 | 4.629 | (53.89, -44.25, 135.90) | (53.89, -44.25, 138.40) | Steel |
| EG17_shaft | 157.168 | (55.70, -65.17, 135.90) | (55.70, -65.17, 133.00) | Steel |
| M3hexagon_socket_head_cap_screw_1 | 0.191 | (40.31, -72.52, 127.59) | (41.70, -72.52, 127.58) | Steel |
| M3hexagon_socket_head_cap_screw_1 | 0.191 | (64.50, -70.43, 119.93) | (65.89, -70.43, 119.93) | Steel |
| M3hexagon_socket_head_cap_screw_1 | 0.191 | (72.13, -69.77, 144.21) | (73.51, -69.77, 144.21) | Steel |
| M3hexagon_socket_head_cap_screw_1 | 0.191 | (47.94, -71.86, 151.86) | (49.33, -71.86, 151.86) | Steel |
| M3hexagon_socket_head_cap_screw_1 | 0.191 | (68.07, -22.94, 144.21) | (69.46, -22.94, 144.21) | Steel |
| M3hexagon_socket_head_cap_screw_1 | 0.191 | (60.45, -23.60, 119.93) | (61.83, -23.60, 119.93) | Steel |
| M3hexagon_socket_head_cap_screw_1 | 0.191 | (36.26, -25.70, 127.59) | (37.65, -25.70, 127.58) | Steel |
| M3hexagon_socket_head_cap_screw_1 | 0.191 | (43.89, -25.04, 151.86) | (45.27, -25.04, 151.86) | Steel |
| input_shaft_1 | 5.764 | (54.41, -50.22, 135.90) | (60.85, -50.22, 135.90) | Steel |
| nema17input_flange_1 | 126.704 | (53.50, -39.76, 135.90) | (53.50, -39.76, 129.90) | Steel |
| 10circlip_1 | 0.179 | (56.67, -76.33, 135.90) | (56.67, -76.83, 137.07) | Steel |
| 6801 | 5.041 | (-27.02, 80.24, 60.40) | (-27.02, 80.24, 62.90) | Steel |
| EG17_shaft_2 | 239.584 | (-24.26, 48.36, 60.40) | (-24.26, 48.35, 51.91) | Steel |
| M3hexagon_socket_head_cap_screw | 0.208 | (-30.61, 41.79, 43.77) | (-29.22, 41.79, 43.77) | Steel |
| M3hexagon_socket_head_cap_screw | 0.208 | (-7.18, 43.82, 53.51) | (-5.79, 43.82, 53.51) | Steel |
| M3hexagon_socket_head_cap_screw | 0.208 | (-16.88, 42.98, 77.03) | (-15.50, 42.98, 77.03) | Steel |
| M3hexagon_socket_head_cap_screw | 0.208 | (-40.31, 40.95, 67.29) | (-38.93, 40.95, 67.29) | Steel |
| M3hexagon_socket_head_cap_screw | 0.208 | (-21.88, 100.76, 77.03) | (-20.50, 100.76, 77.03) | Steel |
| M3hexagon_socket_head_cap_screw | 0.208 | (-12.18, 101.60, 53.51) | (-10.79, 101.60, 53.51) | Steel |
| M3hexagon_socket_head_cap_screw | 0.208 | (-35.61, 99.57, 43.77) | (-34.22, 99.57, 43.77) | Steel |
| M3hexagon_socket_head_cap_screw | 0.208 | (-45.31, 98.73, 67.29) | (-43.93, 98.73, 67.29) | Steel |
| input_shaft | 6.277 | (-26.50, 74.26, 60.40) | (-20.07, 74.26, 60.40) | Steel |
| nema17input_flange | 137.982 | (-27.41, 84.72, 60.40) | (-27.41, 84.72, 54.40) | Steel |
| 10circlip | 0.195 | (-23.29, 37.20, 60.40) | (-23.29, 36.70, 61.58) | Steel |
| Elbow_Belt_Sensorless | 138.434 | (74.38, -34.95, 287.39) | (74.38, -77.06, 284.54) | PETG_25_Gyroid_EH |
| Elbow_Cap | 0.970 | (100.98, -32.64, 298.97) | (100.98, -32.64, 300.97) | PETG_15_Gyroid |
| Elbow_Connector_Passive | 10.964 | (111.34, 26.97, 215.31) | (111.34, 26.97, 224.58) | PETG_30_Gyroid_ECP |
| Elbow_Motor | 390.226 | (93.69, -33.27, 199.98) | (93.69, -33.30, 223.64) | Iron_Wrought |
| Component54 | 12.921 | (59.15, -105.02, 135.90) | (59.15, -105.02, 140.88) | PETG_10_Grid_UA_Gear |
| Component52 | 25.855 | (122.55, -102.54, 215.31) | (122.55, -102.54, 227.11) | PETG_25_Gryoid_ECA |
| Gripper_Shaft | 11.203 | (-98.04, -48.48, 248.69) | (-98.04, -48.48, 268.00) | Yaw_Shaft |
| Lower_Bottom_Base_Bearing_Ring | 62.154 | (-27.20, -56.18, 70.74) | (84.84, 0.00, 97.94) | NSK_32908 |
| Lower_Upper_Base_Bearing_Ring | 98.851 | (-27.20, -56.18, 70.74) | (87.57, 0.00, 97.94) | NSK_32908 |
| Motor_Connector_Shoulder | 28.380 | (-22.71, 30.43, 60.40) | (-23.16, 16.57, 72.96) | PETG_30_Gyroid_SMH |
| Motor_Housing_Roll | 120.881 | (41.57, -37.79, 273.11) | (43.67, -38.34, 349.54) | PETG_30_Gyroid_RH |
| Motor_Housing_Yaw | 45.446 | (-97.27, -48.45, 248.06) | (-98.82, -48.45, 227.40) | Yaw_Housing |
| Passive_Cap | 7.373 | (-67.11, -74.77, 226.00) | (-67.11, -74.77, 238.45) | PC_Roll_Housing |
| HR32906J_Inner_ring | 45.132 | (121.43, -89.59, 215.31) | (116.00, -89.59, 215.31) | Bearing_Steel |
| HR32906J_Outer_ring | 29.417 | (121.43, -89.59, 215.31) | (113.44, -89.59, 215.31) | Bearing_Steel |
| HR32906J_Inner_ring | 45.132 | (111.34, 26.97, 215.31) | (105.91, 26.97, 215.31) | Bearing_Steel |
| HR32906J_Outer_ring | 29.417 | (111.34, 26.97, 215.31) | (103.35, 26.97, 215.31) | Bearing_Steel |
| HR32906J_Inner_ring | 45.132 | (51.62, -36.91, 277.48) | (46.19, -36.91, 277.48) | Bearing_Steel |
| HR32906J_Outer_ring | 29.417 | (51.62, -36.91, 277.48) | (43.63, -36.91, 277.48) | Bearing_Steel |
| HR32906J_Inner_ring | 45.132 | (97.14, -32.98, 297.30) | (91.71, -32.98, 297.30) | Bearing_Steel |
| HR32906J_Outer_ring | 29.417 | (97.14, -32.98, 297.30) | (89.15, -32.98, 297.30) | Bearing_Steel |
| HR32906J_Inner_ring | 45.132 | (-65.85, -92.71, 226.69) | (-71.29, -92.71, 226.69) | Bearing_Steel |
| HR32906J_Outer_ring | 29.417 | (-65.85, -92.71, 226.69) | (-73.85, -92.71, 226.69) | Bearing_Steel |
| HR32906J_Inner_ring | 45.132 | (-72.20, -2.00, 223.23) | (-77.63, -2.00, 223.23) | Bearing_Steel |
| HR32906J_Outer_ring | 29.417 | (-72.20, -2.00, 223.23) | (-80.19, -2.00, 223.23) | Bearing_Steel |
| HR32906J_Inner_ring | 45.132 | (-112.74, -49.06, 260.72) | (-118.17, -49.06, 260.72) | Bearing_Steel |
| HR32906J_Outer_ring | 29.417 | (-112.74, -49.06, 260.72) | (-120.73, -49.06, 260.72) | Bearing_Steel |
| Roll_Motor | 390.226 | (8.72, -2.02, 258.51) | (8.72, -2.04, 282.17) | Iron_Wrought |
| Component58 | 28.892 | (51.62, -36.91, 277.48) | (51.62, -36.91, 263.81) | PET_Plastic |
| Shoulder_Bearing_2_Lower | 62.154 | (0.00, 0.00, 0.00) | (-9.70, -0.00, -0.00) | NSK_32908 |
| Shoulder_Bearing_2_Lower | 62.154 | (-11.24, -102.08, 60.40) | (-20.94, -102.08, 60.40) | NSK_32908 |
| Shoulder_Bearing_2_Lower | 62.154 | (-7.53, -144.92, 60.40) | (-17.23, -144.92, 60.40) | NSK_32908 |
| Shoulder_Bearing_2_Upper | 98.851 | (0.00, 0.00, -0.60) | (-6.97, 0.00, -0.60) | NSK_32908 |
| Shoulder_Bearing_2_Upper | 98.851 | (-11.24, -102.08, 60.40) | (-18.21, -102.08, 60.40) | NSK_32908 |
| Shoulder_Bearing_2_Upper | 98.851 | (-7.53, -144.92, 60.40) | (-14.50, -144.92, 60.40) | NSK_32908 |
| Shoulder_Cap | 4.930 | (-7.53, -144.92, 60.40) | (-7.53, -144.92, 62.68) | PETG_30_Gyroid |
| Shoulder_Motor | 498.902 | (-34.31, 164.42, 60.40) | (-34.31, 164.41, 90.73) | Steel |
| UA_Motor | 390.226 | (51.78, -19.84, 135.90) | (51.78, -19.86, 159.55) | UA_Motor |
| 92605A009 | 0.000 | (88.71, -229.09, -6.70) | (0.00, 0.00, 0.00) |  |
| 92605A009 | 0.000 | (82.73, -229.61, -12.71) | (0.00, 0.00, 0.00) |  |
| Connector | 27.734 | (-21.41, 15.48, 60.40) | (-21.48, 19.58, 60.34) | Steel |
| 92605A009_1 | 0.000 | (177.17, -177.03, 72.15) | (0.00, 0.00, 0.00) |  |
| 92605A009_1 | 0.000 | (171.18, -177.55, 66.14) | (0.00, 0.00, 0.00) |  |
| Connector_1 | 27.734 | (58.29, -95.06, 135.90) | (58.23, -90.96, 135.83) | Steel |
| Upper_arm | 290.872 | (-19.69, -4.44, 60.40) | (-18.00, 55.33, 107.84) | PETG_30_Gryoid_UA |
| Yaw_Motor | 139.847 | (-64.77, -47.19, 221.48) | (-64.77, -47.24, 232.02) | Yaw_Motor |
| base_link | 274.677 | (0.00, 0.00, 0.00) | (0.00, 0.00, -39.15) | PETG_15_Gyroid |

## Joint Origins Comparison

All origins shown in multiple coordinate systems for debugging.

| Joint | Source | Origin (cm, raw) | Origin (m, picked) | Motion | Axis |
|-------|--------|------------------|-------------------|--------|------|
| Revolute_13 | geometryOrOriginOne | goo1(-0.75, -14.49, 6.04) | (-0.0075, -0.1449, 0.0604) | revolute | (0.1, -1.0, -0.0) |
| Revolute_29 | geometryOrOriginOne | goo1(11.35, 0.21, 21.53) | (0.1135, 0.0021, 0.2153) | revolute | (0.1, -1.0, 0.0) |
| Revolute_37 | geometryOrOriginOne | goo1(4.16, -3.78, 27.31) | (0.0416, -0.0378, 0.2731) | revolute | (-0.9, -0.1, -0.4) |
| Revolute_43 | geometryOrOriginOne | goo1(-6.71, -7.48, 22.60) | (-0.0671, -0.0748, 0.2260) | revolute | (-0.1, 1.0, -0.0) |
| Revolute_46 | geometryOrOriginOne | goo1(-11.27, -4.91, 26.07) | (-0.1127, -0.0491, 0.2607) | revolute | (-0.8, -0.0, 0.6) |
| Revolute_5 | geometryOrOriginOne | goo1(0.00, 0.00, -0.06) | (0.0000, 0.0000, -0.0006) | revolute | (-0.0, 0.0, 1.0) |
| Rigid_1 | geometryOrOriginOne | goo1(-0.00, -0.00, -1.50) | (-0.0000, -0.0000, -0.0150) | rigid | (0.0, 0.0, 1.0) |
| Rigid_10 | geometryOrOriginOne | goo1(-0.99, -11.70, 6.04) | (-0.0099, -0.1170, 0.0604) | rigid | (0.0, 0.0, 1.0) |
| Rigid_11 | geometryOrOriginOne | goo1(-0.88, -13.00, 6.04) | (-0.0088, -0.1300, 0.0604) | rigid | (0.0, 0.0, 1.0) |
| Rigid_12 | geometryOrOriginOne | goo1(-0.88, -13.00, 6.04) | (-0.0088, -0.1300, 0.0604) | rigid | (0.0, 0.0, 1.0) |
| Rigid_14 | geometryOrOriginOne | goo1(-0.75, -14.49, 6.04) | (-0.0075, -0.1449, 0.0604) | rigid | (0.0, 0.0, 1.0) |
| Rigid_15 | geometryOrOriginOne | goo1(-1.37, 1.61, 6.96) | (-0.0137, 0.0161, 0.0696) | rigid | (0.0, 0.0, 1.0) |
| Rigid_16 | geometryOrOriginOne | goo1(12.04, -7.76, 21.53) | (0.1204, -0.0776, 0.2153) | rigid | (0.0, 0.0, 1.0) |
| Rigid_17 | geometryOrOriginOne | goo1(12.04, -7.76, 21.53) | (0.1204, -0.0776, 0.2153) | rigid | (0.0, 0.0, 1.0) |
| Rigid_18 | geometryOrOriginOne | goo1(11.24, 1.50, 21.53) | (0.1124, 0.0150, 0.2153) | rigid | (0.0, 0.0, 1.0) |
| Rigid_19 | geometryOrOriginOne | goo1(11.24, 1.50, 21.53) | (0.1124, 0.0150, 0.2153) | rigid | (0.0, 0.0, 1.0) |
| Rigid_2 | geometryOrOriginOne | goo1(0.00, 0.00, -1.50) | (0.0000, 0.0000, -0.0150) | rigid | (0.0, 0.0, 1.0) |
| Rigid_20 | geometryOrOriginOne | goo1(5.88, -11.26, 0.74) | (0.0588, -0.1126, 0.0074) | rigid | (0.0, 0.0, 1.0) |
| Rigid_21 | geometryOrOriginOne | goo1(-2.34, 3.84, 6.04) | (-0.0234, 0.0384, 0.0604) | rigid | (0.0, 0.0, 1.0) |
| Rigid_22 | geometryOrOriginOne | goo1(-2.91, 10.46, 6.04) | (-0.0291, 0.1046, 0.0604) | rigid | (0.0, 0.0, 1.0) |
| Rigid_23 | geometryOrOriginOne | goo1(5.66, -7.51, 13.59) | (0.0566, -0.0751, 0.1359) | rigid | (0.0, 0.0, 1.0) |
| Rigid_24 | geometryOrOriginOne | goo1(5.18, -1.98, 13.59) | (0.0518, -0.0198, 0.1359) | rigid | (0.0, 0.0, 1.0) |
| Rigid_25 | geometryOrOriginOne | goo1(11.13, 2.70, 21.53) | (0.1113, 0.0270, 0.2153) | rigid | (0.0, 0.0, 1.0) |
| Rigid_26 | geometryOrOriginOne | goo1(12.14, -8.96, 21.53) | (0.1214, -0.0896, 0.2153) | rigid | (0.0, 0.0, 1.0) |
| Rigid_27 | geometryOrOriginOne | goo1(5.83, -9.51, 13.59) | (0.0583, -0.0951, 0.1359) | rigid | (0.0, 0.0, 1.0) |
| Rigid_28 | geometryOrOriginOne | goo1(5.83, -9.51, 13.59) | (0.0583, -0.0951, 0.1359) | rigid | (0.0, 0.0, 1.0) |
| Rigid_3 | geometryOrOriginOne | goo1(0.00, -0.00, -3.60) | (0.0000, -0.0000, -0.0360) | rigid | (0.0, 0.0, 1.0) |
| Rigid_30 | geometryOrOriginOne | goo1(9.37, -3.33, 20.00) | (0.0937, -0.0333, 0.2000) | rigid | (0.0, 0.0, 1.0) |
| Rigid_31 | geometryOrOriginOne | goo1(6.26, -3.60, 28.23) | (0.0626, -0.0360, 0.2823) | rigid | (0.0, 0.0, 1.0) |
| Rigid_32 | geometryOrOriginOne | goo1(6.26, -3.60, 28.23) | (0.0626, -0.0360, 0.2823) | rigid | (0.0, 0.0, 1.0) |
| Rigid_33 | geometryOrOriginOne | goo1(8.62, -3.39, 29.25) | (0.0862, -0.0339, 0.2925) | rigid | (0.0, 0.0, 1.0) |
| Rigid_34 | geometryOrOriginOne | goo1(8.62, -3.39, 29.25) | (0.0862, -0.0339, 0.2925) | rigid | (0.0, 0.0, 1.0) |
| Rigid_35 | geometryOrOriginOne | goo1(5.16, -3.69, 27.75) | (0.0516, -0.0369, 0.2775) | rigid | (0.0, 0.0, 1.0) |
| Rigid_36 | geometryOrOriginOne | goo1(9.73, -3.30, 29.74) | (0.0973, -0.0330, 0.2974) | rigid | (0.0, 0.0, 1.0) |
| Rigid_38 | geometryOrOriginOne | goo1(0.87, -0.20, 25.85) | (0.0087, -0.0020, 0.2585) | rigid | (0.0, 0.0, 1.0) |
| Rigid_39 | geometryOrOriginOne | goo1(-6.67, -8.08, 22.62) | (-0.0667, -0.0808, 0.2262) | rigid | (0.0, 0.0, 1.0) |
| Rigid_4 | geometryOrOriginOne | goo1(0.00, 0.00, -3.60) | (0.0000, 0.0000, -0.0360) | rigid | (0.0, 0.0, 1.0) |
| Rigid_40 | geometryOrOriginOne | goo1(-7.14, -1.40, 22.37) | (-0.0714, -0.0140, 0.2237) | rigid | (0.0, 0.0, 1.0) |
| Rigid_41 | geometryOrOriginOne | goo1(-6.59, -9.27, 22.67) | (-0.0659, -0.0927, 0.2267) | rigid | (0.0, 0.0, 1.0) |
| Rigid_42 | geometryOrOriginOne | goo1(-7.22, -0.20, 22.32) | (-0.0722, -0.0020, 0.2232) | rigid | (0.0, 0.0, 1.0) |
| Rigid_44 | geometryOrOriginOne | goo1(-10.35, -4.87, 25.31) | (-0.1035, -0.0487, 0.2531) | rigid | (0.0, 0.0, 1.0) |
| Rigid_45 | geometryOrOriginOne | goo1(-8.06, -4.78, 23.45) | (-0.0806, -0.0478, 0.2345) | rigid | (0.0, 0.0, 1.0) |
| Rigid_54 | geometryOrOriginOne | goo1(-0.71, -14.99, 6.04) | (-0.0071, -0.1499, 0.0604) | rigid | (0.0, 0.0, 1.0) |
| Rigid_55 | geometryOrOriginOne | goo1(12.26, -10.25, 21.53) | (0.1226, -0.1025, 0.2153) | rigid | (0.0, 0.0, 1.0) |
| Rigid_56 | geometryOrOriginOne | goo1(10.10, -3.26, 29.90) | (0.1010, -0.0326, 0.2990) | rigid | (0.0, 0.0, 1.0) |
| Rigid_57 | geometryOrOriginOne | goo1(-6.55, -9.77, 22.69) | (-0.0655, -0.0977, 0.2269) | rigid | (0.0, 0.0, 1.0) |
| Rigid_58 | geometryOrOriginOne | goo1(-12.43, -4.95, 27.02) | (-0.1243, -0.0495, 0.2702) | rigid | (0.0, 0.0, 1.0) |
| Rigid_59 | geometryOrOriginOne | goo1(0.00, 0.00, -5.15) | (0.0000, 0.0000, -0.0515) | rigid | (0.0, 0.0, 1.0) |
| Rigid_7 | geometryOrOriginOne | goo1(0.17, 3.86, 2.54) | (0.0017, 0.0386, 0.0254) | rigid | (0.0, 0.0, 1.0) |
| Rigid_8 | geometryOrOriginOne | goo1(1.15, -10.41, 2.54) | (0.0115, -0.1041, 0.0254) | rigid | (0.0, 0.0, 1.0) |
| Rigid_9 | geometryOrOriginOne | goo1(-0.99, -11.70, 6.04) | (-0.0099, -0.1170, 0.0604) | rigid | (0.0, 0.0, 1.0) |
