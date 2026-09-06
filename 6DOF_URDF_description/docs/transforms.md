# Transformation Matrices - 6DOF_URDF

Homogeneous transformation matrices between consecutive frames.
Convention: URDF RPY (XYZ extrinsic / ZYX intrinsic).

## Notation

### Frames

| Index | Link |
|-------|------|
| $L_{0}$ | base_link |
| $L_{1}$ | Shoulder |
| $L_{2}$ | UA |
| $L_{3}$ | Elbow |
| $L_{4}$ | Roll |
| $L_{5}$ | Yaw |
| $L_{6}$ | Gripper |

### Joint Variables

| Variable | Joint | Type | From | To |
|----------|-------|------|------|----|
| $q_{1}$ | Revolute_5 | revolute (rad) | $L_{0}$ | $L_{1}$ |
| $q_{2}$ | Revolute_13 | revolute (rad) | $L_{1}$ | $L_{2}$ |
| $q_{3}$ | Revolute_29 | revolute (rad) | $L_{2}$ | $L_{3}$ |
| $q_{4}$ | Revolute_37 | revolute (rad) | $L_{3}$ | $L_{4}$ |
| $q_{5}$ | Revolute_43 | revolute (rad) | $L_{4}$ | $L_{5}$ |
| $q_{6}$ | Revolute_46 | continuous (rad) | $L_{5}$ | $L_{6}$ |

Shorthand: $c_i = \cos(q_i)$, $s_i = \sin(q_i)$

### Kinematic Tree

```
L0: base_link
  +-- [revolute] Revolute_5 (q1)
      L1: Shoulder
        +-- [revolute] Revolute_13 (q2)
            L2: UA
              +-- [revolute] Revolute_29 (q3)
                  L3: Elbow
                    +-- [revolute] Revolute_37 (q4)
                        L4: Roll
                          +-- [revolute] Revolute_43 (q5)
                              L5: Yaw
                                +-- [continuous] Revolute_46 (q6)
                                    L6: Gripper
```

## Transforms

## Revolute_5

$L_{0}$ **base_link** -> $L_{1}$ **Shoulder** (revolute)
  Variable: $q_{1}$

- **origin xyz**: (0, 0, -0.0515) m
- **origin rpy**: (0, 0, 0) rad
- **axis**: (0, 0, 1)
- **limits**: [0, 6.283185] rad ([0deg, 360deg])

### Local Transform

$$
T^{0}_{1}(q_{1}) = \begin{bmatrix}
c_{1} & -s_{1} & 0 & 0 \\
s_{1} & c_{1} & 0 & 0 \\
0 & 0 & 1 & -0.0515 \\
0 & 0 & 0 & 1 \\
\end{bmatrix}
$$

---

## Revolute_13

$L_{1}$ **Shoulder** -> $L_{2}$ **UA** (revolute)
  Variable: $q_{2}$

- **origin xyz**: (-0.0071, -0.1499, 0.1119) m
- **origin rpy**: (1.570796, 0, 0.086342) rad
- **axis**: (0, 0, 1)
- **limits**: [0, 6.283185] rad ([0deg, 360deg])

### Local Transform

$T^{1}_{2}(q_{2}) = T_{fixed} \cdot R_{axis}(q_{2})$ where:

$$
T_{fixed} = \begin{bmatrix}
0.996275 & 0 & 0.086234 & -0.0071 \\
0.086234 & 0 & -0.996275 & -0.1499 \\
0 & 1 & 0 & 0.1119 \\
0 & 0 & 0 & 1 \\
\end{bmatrix}
$$

$$
R_{axis}(q_{2}) = \begin{bmatrix}
c_{2} & -s_{2} & 0 & 0 \\
s_{2} & c_{2} & 0 & 0 \\
0 & 0 & 1 & 0 \\
0 & 0 & 0 & 1 \\
\end{bmatrix}
$$

---

## Revolute_29

$L_{2}$ **UA** -> $L_{3}$ **Elbow** (revolute)
  Variable: $q_{3}$

- **origin xyz**: (0.133252, 0.154914, -0.036) m
- **origin rpy**: (0, 0, 0) rad
- **axis**: (0, 0, 1)
- **limits**: [0, 6.283185] rad ([0deg, 360deg])

### Local Transform

$$
T^{2}_{3}(q_{3}) = \begin{bmatrix}
c_{3} & -s_{3} & 0 & 0.133252 \\
s_{3} & c_{3} & 0 & 0.154914 \\
0 & 0 & 1 & -0.036 \\
0 & 0 & 0 & 1 \\
\end{bmatrix}
$$

---

## Revolute_37

$L_{3}$ **Elbow** -> $L_{4}$ **Roll** (revolute)
  Variable: $q_{4}$

- **origin xyz**: (-0.015463, 0.083655, -0.0715) m
- **origin rpy**: (1.570796, -0.214197, -1.161568) rad
- **axis**: (0, 0, 1)
- **limits**: [0, 6.283185] rad ([0deg, 360deg])

### Local Transform

$T^{3}_{4}(q_{4}) = T_{fixed} \cdot R_{axis}(q_{4})$ where:

$$
T_{fixed} = \begin{bmatrix}
0.388808 & -0.084579 & -0.917428 & -0.015463 \\
-0.896463 & 0.195011 & -0.397901 & 0.083655 \\
0.212562 & 0.977148 & 0 & -0.0715 \\
0 & 0 & 0 & 1 \\
\end{bmatrix}
$$

$$
R_{axis}(q_{4}) = \begin{bmatrix}
c_{4} & -s_{4} & 0 & 0 \\
s_{4} & c_{4} & 0 & 0 \\
0 & 0 & 1 & 0 \\
0 & 0 & 0 & 1 \\
\end{bmatrix}
$$

---

## Revolute_43

$L_{4}$ **Roll** -> $L_{5}$ **Yaw** (revolute)
  Variable: $q_{5}$

- **origin xyz**: (0.008683, 0.049748, 0.186) m
- **origin rpy**: (1.570796, 1.158599, -0.289463) rad
- **axis**: (0, 0, 1)
- **limits**: [0, 6.283185] rad ([0deg, 360deg])

### Local Transform

$T^{4}_{5}(q_{5}) = T_{fixed} \cdot R_{axis}(q_{5})$ where:

$$
T_{fixed} = \begin{bmatrix}
0.383956 & 0.878125 & -0.285437 & 0.008683 \\
-0.114353 & -0.26153 & -0.958397 & 0.049748 \\
-0.916243 & 0.400623 & 0 & 0.186 \\
0 & 0 & 0 & 1 \\
\end{bmatrix}
$$

$$
R_{axis}(q_{5}) = \begin{bmatrix}
c_{5} & -s_{5} & 0 & 0 \\
s_{5} & c_{5} & 0 & 0 \\
0 & 0 & 1 & 0 \\
0 & 0 & 0 & 1 \\
\end{bmatrix}
$$

---

## Revolute_46

$L_{5}$ **Yaw** -> $L_{6}$ **Gripper** (continuous)
  Variable: $q_{6}$

- **origin xyz**: (-0.055454, -0.045134, 0.0505) m
- **origin rpy**: (1.570796, 0.110328, -0.887634) rad
- **axis**: (0, 0, 1)

### Local Transform

$T^{5}_{6}(q_{6}) = T_{fixed} \cdot R_{axis}(q_{6})$ where:

$$
T_{fixed} = \begin{bmatrix}
0.627411 & 0.069503 & -0.77558 & -0.055454 \\
-0.770865 & -0.085395 & -0.631249 & -0.045134 \\
-0.110104 & 0.99392 & 0 & 0.0505 \\
0 & 0 & 0 & 1 \\
\end{bmatrix}
$$

$$
R_{axis}(q_{6}) = \begin{bmatrix}
c_{6} & -s_{6} & 0 & 0 \\
s_{6} & c_{6} & 0 & 0 \\
0 & 0 & 1 & 0 \\
0 & 0 & 0 & 1 \\
\end{bmatrix}
$$

---

## Global Transform Chains

Transform from root $L_0$ to any link, as product of local transforms along the kinematic chain.

$$T^{0}_{2} = T^{0}_{1}(q_{1}) \cdot T^{1}_{2}(q_{2})\quad (L_0 \to L_{2}: \text{UA})$$

$$T^{0}_{3} = T^{0}_{1}(q_{1}) \cdot T^{1}_{2}(q_{2}) \cdot T^{2}_{3}(q_{3})\quad (L_0 \to L_{3}: \text{Elbow})$$

$$T^{0}_{4} = T^{0}_{1}(q_{1}) \cdot T^{1}_{2}(q_{2}) \cdot T^{2}_{3}(q_{3}) \cdot T^{3}_{4}(q_{4})\quad (L_0 \to L_{4}: \text{Roll})$$

$$T^{0}_{5} = T^{0}_{1}(q_{1}) \cdot T^{1}_{2}(q_{2}) \cdot T^{2}_{3}(q_{3}) \cdot T^{3}_{4}(q_{4}) \cdot T^{4}_{5}(q_{5})\quad (L_0 \to L_{5}: \text{Yaw})$$

$$T^{0}_{6} = T^{0}_{1}(q_{1}) \cdot T^{1}_{2}(q_{2}) \cdot T^{2}_{3}(q_{3}) \cdot T^{3}_{4}(q_{4}) \cdot T^{4}_{5}(q_{5}) \cdot T^{5}_{6}(q_{6})\quad (L_0 \to L_{6}: \text{Gripper})$$

