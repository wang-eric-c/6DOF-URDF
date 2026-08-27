# Transformation Matrices - 6DOF_URDF

Homogeneous transformation matrices between consecutive frames.
Convention: URDF RPY (XYZ extrinsic / ZYX intrinsic).

## Notation

### Frames

| Index | Link |
|-------|------|
| $L_{0}$ | base_link |
| $L_{1}$ | Base_Motor |
| $L_{2}$ | UA_Motor |
| $L_{3}$ | Elbow_Connector_Passive |
| $L_{4}$ | Roll_Housing |
| $L_{5}$ | 20mm |

### Joint Variables

| Variable | Joint | Type | From | To |
|----------|-------|------|------|----|
| $q_{1}$ | Revolute_5 | revolute (rad) | $L_{0}$ | $L_{1}$ |
| $q_{2}$ | Revolute_13 | revolute (rad) | $L_{1}$ | $L_{2}$ |
| $q_{3}$ | Revolute_37 | revolute (rad) | $L_{3}$ | $L_{4}$ |
| $q_{4}$ | Revolute_43 | revolute (rad) | $L_{4}$ | $L_{5}$ |

Shorthand: $c_i = \cos(q_i)$, $s_i = \sin(q_i)$

### Kinematic Tree

```
L0: base_link
  +-- [revolute] Revolute_5 (q1)
      L1: Base_Motor
        +-- [revolute] Revolute_13 (q2)
            L2: UA_Motor
              +-- [fixed] Rigid_25
                  L3: Elbow_Connector_Passive
                    +-- [revolute] Revolute_37 (q3)
                        L4: Roll_Housing
                          +-- [revolute] Revolute_43 (q4)
                              L5: 20mm
```

## Transforms

## Revolute_5

$L_{0}$ **base_link** -> $L_{1}$ **Base_Motor** (revolute)
  Variable: $q_{1}$

- **origin xyz**: (-0.04885, 0.117229, 0.068) m
- **origin rpy**: (0, 0, 0) rad
- **axis**: (0, 0, 1)
- **limits**: [0, 6.283185] rad ([0deg, 360deg])

### Local Transform

$$
T^{0}_{1}(q_{1}) = \begin{bmatrix}
c_{1} & -s_{1} & 0 & -0.04885 \\
s_{1} & c_{1} & 0 & 0.117229 \\
0 & 0 & 1 & 0.068 \\
0 & 0 & 0 & 1 \\
\end{bmatrix}
$$

---

## Revolute_13

$L_{1}$ **Base_Motor** -> $L_{2}$ **UA_Motor** (revolute)
  Variable: $q_{2}$

- **origin xyz**: (0.07604, -0.1534, -0.055062) m
- **origin rpy**: (-1.570796, 0, 0) rad
- **axis**: (0, 0, 1)
- **limits**: [0, 6.283185] rad ([0deg, 360deg])

### Local Transform

$T^{1}_{2}(q_{2}) = T_{fixed} \cdot R_{axis}(q_{2})$ where:

$$
T_{fixed} = \begin{bmatrix}
1 & 0 & 0 & 0.07604 \\
0 & 0 & 1 & -0.1534 \\
0 & -1 & 0 & -0.055062 \\
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

## Rigid_25

$L_{2}$ **UA_Motor** -> $L_{3}$ **Elbow_Connector_Passive** (fixed)

- **origin xyz**: (-0.140442, -0.202376, 0.0189) m
- **origin rpy**: (0, 0, -0.698132) rad

### Local Transform

$$
T^{2}_{3} = \begin{bmatrix}
0.766044 & 0.642788 & 0 & -0.140442 \\
-0.642788 & 0.766044 & 0 & -0.202376 \\
0 & 0 & 1 & 0.0189 \\
0 & 0 & 0 & 1 \\
\end{bmatrix}
$$

---

## Revolute_37

$L_{3}$ **Elbow_Connector_Passive** -> $L_{4}$ **Roll_Housing** (revolute)
  Variable: $q_{3}$

- **origin xyz**: (0.106612, 0.079606, -0.18651) m
- **origin rpy**: (-1.570796, 0, -0.610865) rad
- **axis**: (0, 0, 1)
- **limits**: [0, 6.283185] rad ([0deg, 360deg])

### Local Transform

$T^{3}_{4}(q_{3}) = T_{fixed} \cdot R_{axis}(q_{3})$ where:

$$
T_{fixed} = \begin{bmatrix}
0.819152 & 0 & 0.573576 & 0.106612 \\
-0.573576 & 0 & 0.819152 & 0.079606 \\
0 & -1 & 0 & -0.18651 \\
0 & 0 & 0 & 1 \\
\end{bmatrix}
$$

$$
R_{axis}(q_{3}) = \begin{bmatrix}
c_{3} & -s_{3} & 0 & 0 \\
s_{3} & c_{3} & 0 & 0 \\
0 & 0 & 1 & 0 \\
0 & 0 & 0 & 1 \\
\end{bmatrix}
$$

---

## Revolute_43

$L_{4}$ **Roll_Housing** -> $L_{5}$ **20mm** (revolute)
  Variable: $q_{4}$

- **origin xyz**: (0.251183, -0.314427, 0.170791) m
- **origin rpy**: (1.570796, -1.308997, 0) rad
- **axis**: (0, 0, 1)
- **limits**: [0, 6.283185] rad ([0deg, 360deg])

### Local Transform

$T^{4}_{5}(q_{4}) = T_{fixed} \cdot R_{axis}(q_{4})$ where:

$$
T_{fixed} = \begin{bmatrix}
0.258819 & -0.965926 & 0 & 0.251183 \\
0 & 0 & -1 & -0.314427 \\
0.965926 & 0.258819 & 0 & 0.170791 \\
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

## Global Transform Chains

Transform from root $L_0$ to any link, as product of local transforms along the kinematic chain.

$$T^{0}_{2} = T^{0}_{1}(q_{1}) \cdot T^{1}_{2}(q_{2})\quad (L_0 \to L_{2}: \text{UA_Motor})$$

$$T^{0}_{3} = T^{0}_{1}(q_{1}) \cdot T^{1}_{2}(q_{2}) \cdot T^{2}_{3}\quad (L_0 \to L_{3}: \text{Elbow_Connector_Passive})$$

$$T^{0}_{4} = T^{0}_{1}(q_{1}) \cdot T^{1}_{2}(q_{2}) \cdot T^{2}_{3} \cdot T^{3}_{4}(q_{3})\quad (L_0 \to L_{4}: \text{Roll_Housing})$$

$$T^{0}_{5} = T^{0}_{1}(q_{1}) \cdot T^{1}_{2}(q_{2}) \cdot T^{2}_{3} \cdot T^{3}_{4}(q_{3}) \cdot T^{4}_{5}(q_{4})\quad (L_0 \to L_{5}: \text{20mm})$$

