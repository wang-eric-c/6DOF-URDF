# Export Log: 6DOF URDF

**Generated:** 2026-09-06T12:15:45.272301

```
[12:14:45] fusion2URDF v3.1.0
[12:14:45] Time: 2026-09-06T12:14:45.346960
[12:14:45] Design: 6DOF URDF
[12:14:45] Components: 61
[12:14:45] 
=== PHASE 1: EXTRACTION ===
[12:14:45]   Document unit: mm
[12:14:45] 
=== EXTRACTION: OCCURRENCES ===
[12:14:45]   [LEAF] d=0 base_link
[12:14:45]     path: base_link:1
[12:14:45]     global_pos: (0.000000, 0.000000, 0.000000) m
[12:14:45]     mass: 0.274677 kg, bodies: 1
[12:14:45]     com_global: (0.000000, 0.000000, -0.039151) m
[12:14:45]     com_component_local: (0.000000, 0.000000, -0.039151) m
[12:14:45]     inertia@origin: ixx=1.046247e-03 iyy=1.046247e-03 izz=1.017214e-03 kg·m²
[12:14:45]     inertia@com:    ixx=6.252186e-04 iyy=6.252186e-04 izz=1.017214e-03 kg·m²
[12:14:45]     material: PETG_15_Gyroid
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.1750 x 0.1750 x 0.0710) m
[12:14:45]   [LEAF] d=0 Shoulder_Bearing_2_Upper
[12:14:45]     path: Shoulder Bearing 2 Upper:1
[12:14:45]     global_pos: (0.000000, 0.000000, -0.000600) m
[12:14:45]     mass: 0.098851 kg, bodies: 1
[12:14:45]     com_global: (-0.006970, 0.000000, -0.000600) m
[12:14:45]     com_component_local: (-0.006970, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=5.363167e-05 iyy=3.324533e-05 izz=3.324622e-05 kg·m²
[12:14:45]     inertia@com:    ixx=5.363167e-05 iyy=2.844369e-05 izz=2.844458e-05 kg·m²
[12:14:45]     material: NSK_32908
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0150 x 0.0577 x 0.0577) m
[12:14:45]   [LEAF] d=0 Shoulder_Bearing_2_Lower
[12:14:45]     path: Shoulder Bearing 2 Lower:1
[12:14:45]     global_pos: (0.000000, 0.000000, 0.000000) m
[12:14:45]     mass: 0.062154 kg, bodies: 1
[12:14:45]     com_global: (-0.009700, -0.000000, -0.000000) m
[12:14:45]     com_component_local: (-0.009700, -0.000000, -0.000000) m
[12:14:45]     inertia@origin: ixx=5.372853e-05 iyy=3.342072e-05 izz=3.342072e-05 kg·m²
[12:14:45]     inertia@com:    ixx=5.372853e-05 iyy=2.757216e-05 izz=2.757216e-05 kg·m²
[12:14:45]     material: NSK_32908
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0120 x 0.0620 x 0.0620) m
[12:14:45]   [LEAF] d=0 Lower_Upper_Base_Bearing_Ring
[12:14:45]     path: Lower Upper Base Bearing Ring:1
[12:14:45]     global_pos: (-0.027200, -0.056181, 0.070740) m
[12:14:45]     mass: 0.098851 kg, bodies: 1
[12:14:45]     com_global: (0.087571, 0.000000, 0.097939) m
[12:14:45]     com_component_local: (0.114770, 0.056181, 0.027200) m
[12:14:45]     inertia@origin: ixx=4.387634e-04 iyy=1.403665e-03 izz=1.642534e-03 kg·m²
[12:14:45]     inertia@com:    ixx=5.363167e-05 iyy=2.844369e-05 izz=2.844458e-05 kg·m²
[12:14:45]     material: NSK_32908
[12:14:45]     color: RGB(0.50, 0.50, 0.50) [Opaque_128_128_128]
[12:14:45]     bbox: (0.0150 x 0.0577 x 0.0577) m
[12:14:45]   [LEAF] d=0 Lower_Bottom_Base_Bearing_Ring
[12:14:45]     path: Lower Bottom Base Bearing Ring:1
[12:14:45]     global_pos: (-0.027200, -0.056181, 0.070740) m
[12:14:45]     mass: 0.062154 kg, bodies: 1
[12:14:45]     com_global: (0.084840, 0.000000, 0.097939) m
[12:14:45]     com_component_local: (0.112039, 0.056181, 0.027200) m
[12:14:45]     inertia@origin: ixx=2.958846e-04 iyy=8.537613e-04 izz=1.003952e-03 kg·m²
[12:14:45]     inertia@com:    ixx=5.372853e-05 iyy=2.757216e-05 izz=2.757216e-05 kg·m²
[12:14:45]     material: NSK_32908
[12:14:45]     color: RGB(0.50, 0.50, 0.50) [Opaque_128_128_128]
[12:14:45]     bbox: (0.0120 x 0.0620 x 0.0620) m
[12:14:45]   [LEAF] d=1 Base_Connector_Shaft_V2
[12:14:45]     path: Base Connector + Shaft V2:1
[12:14:45]     global_pos: (0.074721, 0.006468, 0.025400) m
[12:14:45]     mass: 0.315930 kg, bodies: 1
[12:14:45]     com_global: (0.151224, 0.043419, 0.010500) m
[12:14:45]     com_component_local: (0.076504, 0.036952, -0.014900) m
[12:14:45]     inertia@origin: ixx=1.777431e-03 iyy=2.584179e-03 izz=4.104951e-03 kg·m²
[12:14:45]     inertia@com:    ixx=1.275902e-03 iyy=6.649494e-04 izz=1.824480e-03 kg·m²
[12:14:45]     material: PETG_25_Gyroid
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.1600 x 0.2300 x 0.0769) m
[12:14:45]   [LEAF] d=0 Motor_Connector_Shoulder
[12:14:45]     path: Motor Connector Shoulder:1
[12:14:45]     global_pos: (-0.022708, 0.030426, 0.060400) m
[12:14:45]     mass: 0.028380 kg, bodies: 1
[12:14:45]     com_global: (-0.023159, 0.016568, 0.072956) m
[12:14:45]     com_component_local: (-0.000450, -0.013858, 0.012556) m
[12:14:45]     inertia@origin: ixx=2.500451e-05 iyy=1.765981e-05 izz=2.520169e-05 kg·m²
[12:14:45]     inertia@com:    ixx=1.508019e-05 iyy=1.318010e-05 izz=1.974555e-05 kg·m²
[12:14:45]     material: PETG_30_Gyroid_SMH
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.0700 x 0.0700 x 0.0457) m
[12:14:45]   [LEAF] d=0 Bearing_Housing_Shoulder_V2
[12:14:45]     path: Bearing Housing Shoulder V2:1
[12:14:45]     global_pos: (-0.009385, -0.123499, 0.060400) m
[12:14:45]     mass: 0.039267 kg, bodies: 1
[12:14:45]     com_global: (-0.009385, -0.131386, 0.060464) m
[12:14:45]     com_component_local: (0.000000, -0.007887, 0.000064) m
[12:14:45]     inertia@origin: ixx=2.687388e-05 iyy=2.698548e-05 izz=4.476358e-05 kg·m²
[12:14:45]     inertia@com:    ixx=2.443108e-05 iyy=2.698532e-05 izz=4.232093e-05 kg·m²
[12:14:45]     material: PETG_20_CH_BSH
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.0700 x 0.0700 x 0.0430) m
[12:14:45]   [LEAF] d=0 Shoulder_Bearing_2_Upper
[12:14:45]     path: Shoulder Bearing 2 Upper:2
[12:14:45]     global_pos: (-0.011239, -0.102079, 0.060400) m
[12:14:45]     mass: 0.098851 kg, bodies: 1
[12:14:45]     com_global: (-0.018209, -0.102079, 0.060400) m
[12:14:45]     com_component_local: (-0.006970, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=5.363167e-05 iyy=3.324533e-05 izz=3.324622e-05 kg·m²
[12:14:45]     inertia@com:    ixx=5.363167e-05 iyy=2.844369e-05 izz=2.844458e-05 kg·m²
[12:14:45]     material: NSK_32908
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0150 x 0.0577 x 0.0577) m
[12:14:45]   [LEAF] d=0 Shoulder_Bearing_2_Lower
[12:14:45]     path: Shoulder Bearing 2 Lower:2
[12:14:45]     global_pos: (-0.011239, -0.102079, 0.060400) m
[12:14:45]     mass: 0.062154 kg, bodies: 1
[12:14:45]     com_global: (-0.020940, -0.102079, 0.060400) m
[12:14:45]     com_component_local: (-0.009700, -0.000000, -0.000000) m
[12:14:45]     inertia@origin: ixx=5.372853e-05 iyy=3.342072e-05 izz=3.342072e-05 kg·m²
[12:14:45]     inertia@com:    ixx=5.372853e-05 iyy=2.757216e-05 izz=2.757216e-05 kg·m²
[12:14:45]     material: NSK_32908
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0120 x 0.0620 x 0.0620) m
[12:14:45]   [LEAF] d=0 Shoulder_Bearing_2_Upper
[12:14:45]     path: Shoulder Bearing 2 Upper:3
[12:14:45]     global_pos: (-0.007531, -0.144918, 0.060400) m
[12:14:45]     mass: 0.098851 kg, bodies: 1
[12:14:45]     com_global: (-0.014501, -0.144918, 0.060400) m
[12:14:45]     com_component_local: (-0.006970, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=5.363167e-05 iyy=3.324533e-05 izz=3.324622e-05 kg·m²
[12:14:45]     inertia@com:    ixx=5.363167e-05 iyy=2.844369e-05 izz=2.844458e-05 kg·m²
[12:14:45]     material: NSK_32908
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0150 x 0.0577 x 0.0577) m
[12:14:45]   [LEAF] d=0 Shoulder_Bearing_2_Lower
[12:14:45]     path: Shoulder Bearing 2 Lower:3
[12:14:45]     global_pos: (-0.007531, -0.144918, 0.060400) m
[12:14:45]     mass: 0.062154 kg, bodies: 1
[12:14:45]     com_global: (-0.017232, -0.144918, 0.060400) m
[12:14:45]     com_component_local: (-0.009700, -0.000000, -0.000000) m
[12:14:45]     inertia@origin: ixx=5.372853e-05 iyy=3.342072e-05 izz=3.342072e-05 kg·m²
[12:14:45]     inertia@com:    ixx=5.372853e-05 iyy=2.757216e-05 izz=2.757216e-05 kg·m²
[12:14:45]     material: NSK_32908
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0120 x 0.0620 x 0.0620) m
[12:14:45]   [LEAF] d=0 Upper_arm
[12:14:45]     path: Upper arm:1
[12:14:45]     global_pos: (-0.019690, -0.004444, 0.060400) m
[12:14:45]     mass: 0.290872 kg, bodies: 1
[12:14:45]     com_global: (-0.017999, 0.055325, 0.107843) m
[12:14:45]     com_component_local: (0.001691, 0.059769, 0.047443) m
[12:14:45]     inertia@origin: ixx=3.859039e-03 iyy=1.386153e-03 izz=2.632012e-03 kg·m²
[12:14:45]     inertia@com:    ixx=2.165246e-03 iyy=7.306094e-04 izz=1.592100e-03 kg·m²
[12:14:45]     material: PETG_30_Gryoid_UA
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.0600 x 0.2618 x 0.1610) m
[12:14:45]   [LEAF] d=0 Shoulder_Cap
[12:14:45]     path: Shoulder Cap:2
[12:14:45]     global_pos: (-0.007531, -0.144918, 0.060400) m
[12:14:45]     mass: 0.004930 kg, bodies: 1
[12:14:45]     com_global: (-0.007531, -0.144918, 0.062682) m
[12:14:45]     com_component_local: (0.000000, -0.000000, 0.002282) m
[12:14:45]     inertia@origin: ixx=5.490462e-07 iyy=5.490463e-07 izz=1.026583e-06 kg·m²
[12:14:45]     inertia@com:    ixx=5.233730e-07 iyy=5.233731e-07 izz=1.026583e-06 kg·m²
[12:14:45]     material: PETG_30_Gyroid
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.0450 x 0.0450 x 0.0050) m
[12:14:45]   [LEAF] d=1 92605A009
[12:14:45]     path: UA Shaft COupler:1+92605A009:1
[12:14:45]     global_pos: (0.088714, -0.229094, -0.006704) m
[12:14:45]   [LEAF] d=1 Connector
[12:14:45]     path: UA Shaft COupler:1+Connector:1
[12:14:45]     global_pos: (-0.021415, 0.015482, 0.060400) m
[12:14:45]     mass: 0.027734 kg, bodies: 1
[12:14:45]     com_global: (-0.021477, 0.019578, 0.060338) m
[12:14:45]     com_component_local: (-0.000062, 0.004096, -0.000062) m
[12:14:45]     inertia@origin: ixx=2.196173e-06 iyy=2.689968e-06 izz=2.196171e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.730749e-06 iyy=2.689752e-06 izz=1.730747e-06 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.98, 0.98, 0.96) [Silver_Polished]
[12:14:45]     bbox: (0.0320 x 0.0130 x 0.0320) m
[12:14:45]   [LEAF] d=1 92605A009
[12:14:45]     path: UA Shaft COupler:1+92605A009:2
[12:14:45]     global_pos: (0.082728, -0.229612, -0.012713) m
[12:14:45]   [SUBASM] d=0 UA_Shaft_COupler
[12:14:45]     path: UA Shaft COupler:1
[12:14:45]     global_pos: (0.088024, -0.221124, -0.012713) m
[12:14:45]   [LEAF] d=1 HR32906J_Inner_ring
[12:14:45]     path: Roll Bearing 2:1+HR32906J Inner ring:1
[12:14:45]     global_pos: (0.121430, -0.089591, 0.215314) m
[12:14:45]     mass: 0.045132 kg, bodies: 1
[12:14:45]     com_global: (0.115996, -0.089591, 0.215314) m
[12:14:45]     com_component_local: (-0.005434, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=1.370829e-05 iyy=8.686935e-06 izz=8.686846e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.370829e-05 iyy=7.354228e-06 izz=7.354139e-06 kg·m²
[12:14:45]     material: Bearing_Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0120 x 0.0432 x 0.0432) m
[12:14:45]   [LEAF] d=1 HR32906J_Outer_ring
[12:14:45]     path: Roll Bearing 2:1+HR32906J Outer ring:1
[12:14:45]     global_pos: (0.121430, -0.089591, 0.215314) m
[12:14:45]     mass: 0.029417 kg, bodies: 1
[12:14:45]     com_global: (0.113436, -0.089591, 0.215314) m
[12:14:45]     com_component_local: (-0.007994, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=1.440246e-05 iyy=9.271567e-06 izz=9.271567e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.440246e-05 iyy=7.391575e-06 izz=7.391575e-06 kg·m²
[12:14:45]     material: Bearing_Steel
[12:14:45]     color: RGB(0.98, 0.98, 0.96) [Silver_Polished]
[12:14:45]     bbox: (0.0090 x 0.0470 x 0.0470) m
[12:14:45]   [SUBASM] d=0 Roll_Bearing_2
[12:14:45]     path: Roll Bearing 2:1
[12:14:45]     global_pos: (-0.048702, -0.143824, 0.168578) m
[12:14:45]   [LEAF] d=1 HR32906J_Inner_ring
[12:14:45]     path: Roll Bearing 2:2+HR32906J Inner ring:1
[12:14:45]     global_pos: (0.111341, 0.026973, 0.215314) m
[12:14:45]     mass: 0.045132 kg, bodies: 1
[12:14:45]     com_global: (0.105907, 0.026973, 0.215314) m
[12:14:45]     com_component_local: (-0.005434, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=1.370829e-05 iyy=8.686935e-06 izz=8.686846e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.370829e-05 iyy=7.354228e-06 izz=7.354139e-06 kg·m²
[12:14:45]     material: Bearing_Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0120 x 0.0432 x 0.0432) m
[12:14:45]   [LEAF] d=1 HR32906J_Outer_ring
[12:14:45]     path: Roll Bearing 2:2+HR32906J Outer ring:1
[12:14:45]     global_pos: (0.111341, 0.026973, 0.215314) m
[12:14:45]     mass: 0.029417 kg, bodies: 1
[12:14:45]     com_global: (0.103346, 0.026973, 0.215314) m
[12:14:45]     com_component_local: (-0.007994, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=1.440246e-05 iyy=9.271567e-06 izz=9.271567e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.440246e-05 iyy=7.391575e-06 izz=7.391575e-06 kg·m²
[12:14:45]     material: Bearing_Steel
[12:14:45]     color: RGB(0.98, 0.98, 0.96) [Silver_Polished]
[12:14:45]     bbox: (0.0090 x 0.0470 x 0.0470) m
[12:14:45]   [SUBASM] d=0 Roll_Bearing_2
[12:14:45]     path: Roll Bearing 2:2
[12:14:45]     global_pos: (-0.089943, 0.036878, 0.206694) m
[12:14:45]   [LEAF] d=0 Base_Motor
[12:14:45]     path: Base Motor:1
[12:14:45]     global_pos: (0.058777, -0.112580, 0.067400) m
[12:14:45]     mass: 0.498902 kg, bodies: 1
[12:14:45]     com_global: (0.058777, -0.112596, 0.097732) m
[12:14:45]     com_component_local: (-0.000000, -0.000017, 0.030332) m
[12:14:45]     inertia@origin: ixx=6.837719e-04 iyy=6.834972e-04 izz=1.375650e-04 kg·m²
[12:14:45]     inertia@com:    ixx=2.247628e-04 iyy=2.244883e-04 izz=1.375649e-04 kg·m²
[12:14:45]     material: Base_Motor
[12:14:45]     color: RGB(1.00, 1.00, 1.00) [Opaque_255_255_255]
[12:14:45]     bbox: (0.0423 x 0.0603 x 0.0840) m
[12:14:45]   [LEAF] d=1 EG17_shaft_2
[12:14:45]     path: EG17-G50:1+EG17 shaft-2:1
[12:14:45]     global_pos: (-0.024261, 0.048359, 0.060400) m
[12:14:45]     mass: 0.239584 kg, bodies: 1
[12:14:45]     com_global: (-0.024261, 0.048355, 0.051905) m
[12:14:45]     com_component_local: (0.000000, -0.000004, -0.008495) m
[12:14:45]     inertia@origin: ixx=7.519585e-05 iyy=7.519859e-05 izz=5.113149e-05 kg·m²
[12:14:45]     inertia@com:    ixx=5.790806e-05 iyy=5.791080e-05 izz=5.113149e-05 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.98, 0.98, 0.96) [Silver_Polished]
[12:14:45]     bbox: (0.0420 x 0.0420 x 0.0595) m
[12:14:45]   [LEAF] d=1 nema17input_flange
[12:14:45]     path: EG17-G50:1+nema17input flange:1
[12:14:45]     global_pos: (-0.027408, 0.084723, 0.060400) m
[12:14:45]     mass: 0.137982 kg, bodies: 1
[12:14:45]     com_global: (-0.027408, 0.084723, 0.054399) m
[12:14:45]     com_component_local: (-0.000000, 0.000000, -0.006001) m
[12:14:45]     inertia@origin: ixx=3.607631e-05 iyy=3.548888e-05 izz=4.126629e-05 kg·m²
[12:14:45]     inertia@com:    ixx=3.110692e-05 iyy=3.051949e-05 izz=4.126629e-05 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0420 x 0.0420 x 0.0305) m
[12:14:45]   [LEAF] d=1 input_shaft
[12:14:45]     path: EG17-G50:1+input shaft:1
[12:14:45]     global_pos: (-0.026503, 0.074262, 0.060400) m
[12:14:45]     mass: 0.006277 kg, bodies: 1
[12:14:45]     com_global: (-0.020066, 0.074262, 0.060400) m
[12:14:45]     com_component_local: (0.006437, 0.000000, -0.000000) m
[12:14:45]     inertia@origin: ixx=1.623796e-07 iyy=4.251059e-07 izz=4.341520e-07 kg·m²
[12:14:45]     inertia@com:    ixx=1.623796e-07 iyy=1.650219e-07 izz=1.740679e-07 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0125 x 0.0160 x 0.0160) m
[12:14:45]   [LEAF] d=1 10circlip
[12:14:45]     path: EG17-G50:1+¦µ10circlip:1
[12:14:45]     global_pos: (-0.023295, 0.037201, 0.060400) m
[12:14:45]     mass: 0.000195 kg, bodies: 1
[12:14:45]     com_global: (-0.023295, 0.036701, 0.061576) m
[12:14:45]     com_component_local: (-0.000000, -0.000500, 0.001176) m
[12:14:45]     inertia@origin: ixx=4.399643e-09 iyy=6.714820e-09 izz=2.445089e-09 kg·m²
[12:14:45]     inertia@com:    ixx=4.081458e-09 iyy=6.445352e-09 izz=2.396372e-09 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0115 x 0.0010 x 0.0144) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw
[12:14:45]     path: EG17-G50:1+M3hexagon socket head cap screw:1
[12:14:45]     global_pos: (-0.030606, 0.041787, 0.043770) m
[12:14:45]     mass: 0.000208 kg, bodies: 1
[12:14:45]     com_global: (-0.029221, 0.041788, 0.043770) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=9.241345e-10 iyy=1.027628e-09 izz=1.027688e-09 kg·m²
[12:14:45]     inertia@com:    ixx=9.241342e-10 iyy=6.281692e-10 izz=6.282287e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [LEAF] d=1 6801
[12:14:45]     path: EG17-G50:1+6801:1
[12:14:45]     global_pos: (-0.027020, 0.080240, 0.060400) m
[12:14:45]     mass: 0.005041 kg, bodies: 1
[12:14:45]     com_global: (-0.027020, 0.080240, 0.062900) m
[12:14:45]     com_component_local: (0.000000, -0.000000, 0.002500) m
[12:14:45]     inertia@origin: ixx=2.259990e-07 iyy=2.259990e-07 izz=3.694159e-07 kg·m²
[12:14:45]     inertia@com:    ixx=1.944911e-07 iyy=1.944911e-07 izz=3.694159e-07 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0210 x 0.0210 x 0.0050) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw
[12:14:45]     path: EG17-G50:1+M3hexagon socket head cap screw:2
[12:14:45]     global_pos: (-0.007175, 0.043815, 0.053512) m
[12:14:45]     mass: 0.000208 kg, bodies: 1
[12:14:45]     com_global: (-0.005790, 0.043816, 0.053511) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=9.241345e-10 iyy=1.027628e-09 izz=1.027688e-09 kg·m²
[12:14:45]     inertia@com:    ixx=9.241342e-10 iyy=6.281692e-10 izz=6.282287e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw
[12:14:45]     path: EG17-G50:1+M3hexagon socket head cap screw:3
[12:14:45]     global_pos: (-0.016881, 0.042975, 0.077030) m
[12:14:45]     mass: 0.000208 kg, bodies: 1
[12:14:45]     com_global: (-0.015495, 0.042976, 0.077029) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=9.241345e-10 iyy=1.027628e-09 izz=1.027688e-09 kg·m²
[12:14:45]     inertia@com:    ixx=9.241342e-10 iyy=6.281692e-10 izz=6.282287e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw
[12:14:45]     path: EG17-G50:1+M3hexagon socket head cap screw:4
[12:14:45]     global_pos: (-0.040311, 0.040947, 0.067288) m
[12:14:45]     mass: 0.000208 kg, bodies: 1
[12:14:45]     com_global: (-0.038926, 0.040948, 0.067288) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=9.241345e-10 iyy=1.027628e-09 izz=1.027688e-09 kg·m²
[12:14:45]     inertia@com:    ixx=9.241342e-10 iyy=6.281692e-10 izz=6.282287e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw
[12:14:45]     path: EG17-G50:1+M3hexagon socket head cap screw:5
[12:14:45]     global_pos: (-0.021882, 0.100759, 0.077030) m
[12:14:45]     mass: 0.000208 kg, bodies: 1
[12:14:45]     com_global: (-0.020497, 0.100760, 0.077029) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=9.241345e-10 iyy=1.027628e-09 izz=1.027688e-09 kg·m²
[12:14:45]     inertia@com:    ixx=9.241342e-10 iyy=6.281692e-10 izz=6.282287e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw
[12:14:45]     path: EG17-G50:1+M3hexagon socket head cap screw:6
[12:14:45]     global_pos: (-0.012177, 0.101599, 0.053512) m
[12:14:45]     mass: 0.000208 kg, bodies: 1
[12:14:45]     com_global: (-0.010792, 0.101600, 0.053511) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=9.241345e-10 iyy=1.027628e-09 izz=1.027688e-09 kg·m²
[12:14:45]     inertia@com:    ixx=9.241342e-10 iyy=6.281692e-10 izz=6.282287e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw
[12:14:45]     path: EG17-G50:1+M3hexagon socket head cap screw:7
[12:14:45]     global_pos: (-0.035607, 0.099571, 0.043770) m
[12:14:45]     mass: 0.000208 kg, bodies: 1
[12:14:45]     com_global: (-0.034222, 0.099572, 0.043770) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=9.241345e-10 iyy=1.027628e-09 izz=1.027688e-09 kg·m²
[12:14:45]     inertia@com:    ixx=9.241342e-10 iyy=6.281692e-10 izz=6.282287e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw
[12:14:45]     path: EG17-G50:1+M3hexagon socket head cap screw:8
[12:14:45]     global_pos: (-0.045313, 0.098731, 0.067288) m
[12:14:45]     mass: 0.000208 kg, bodies: 1
[12:14:45]     com_global: (-0.043927, 0.098732, 0.067288) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=9.241345e-10 iyy=1.027628e-09 izz=1.027688e-09 kg·m²
[12:14:45]     inertia@com:    ixx=9.241342e-10 iyy=6.281692e-10 izz=6.282287e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [SUBASM] d=0 EG17_G50
[12:14:45]     path: EG17-G50:1
[12:14:45]     global_pos: (-0.029898, 0.089275, 0.063047) m
[12:14:45]   [LEAF] d=0 Shoulder_Motor
[12:14:45]     path: Shoulder Motor:1
[12:14:45]     global_pos: (-0.034307, 0.164425, 0.060400) m
[12:14:45]     mass: 0.498902 kg, bodies: 1
[12:14:45]     com_global: (-0.034307, 0.164408, 0.090732) m
[12:14:45]     com_component_local: (-0.000000, -0.000017, 0.030332) m
[12:14:45]     inertia@origin: ixx=6.837719e-04 iyy=6.834972e-04 izz=1.375650e-04 kg·m²
[12:14:45]     inertia@com:    ixx=2.247628e-04 iyy=2.244883e-04 izz=1.375649e-04 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(1.00, 1.00, 1.00) [Opaque_255_255_255]
[12:14:45]     bbox: (0.0423 x 0.0603 x 0.0840) m
[12:14:45]   [LEAF] d=1 EG17_shaft
[12:14:45]     path: EG17-G10:1+EG17 shaft:1
[12:14:45]     global_pos: (0.055703, -0.065168, 0.135897) m
[12:14:45]     mass: 0.157168 kg, bodies: 1
[12:14:45]     com_global: (0.055703, -0.065174, 0.133000) m
[12:14:45]     com_component_local: (-0.000000, -0.000005, -0.002897) m
[12:14:45]     inertia@origin: ixx=2.969085e-05 iyy=2.969336e-05 izz=3.309726e-05 kg·m²
[12:14:45]     inertia@com:    ixx=2.837178e-05 iyy=2.837429e-05 izz=3.309726e-05 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.98, 0.98, 0.96) [Silver_Polished]
[12:14:45]     bbox: (0.0420 x 0.0420 x 0.0485) m
[12:14:45]   [LEAF] d=1 nema17input_flange_1
[12:14:45]     path: EG17-G10:1+nema17input flange (1):1
[12:14:45]     global_pos: (0.053504, -0.039763, 0.135897) m
[12:14:45]     mass: 0.126704 kg, bodies: 1
[12:14:45]     com_global: (0.053504, -0.039763, 0.129895) m
[12:14:45]     com_component_local: (-0.000000, 0.000000, -0.006001) m
[12:14:45]     inertia@origin: ixx=3.312754e-05 iyy=3.258812e-05 izz=3.789330e-05 kg·m²
[12:14:45]     inertia@com:    ixx=2.856433e-05 iyy=2.802491e-05 izz=3.789330e-05 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0420 x 0.0420 x 0.0305) m
[12:14:45]   [LEAF] d=1 input_shaft_1
[12:14:45]     path: EG17-G10:1+input shaft (1):1
[12:14:45]     global_pos: (0.054410, -0.050224, 0.135897) m
[12:14:45]     mass: 0.005764 kg, bodies: 1
[12:14:45]     com_global: (0.060847, -0.050224, 0.135897) m
[12:14:45]     com_component_local: (0.006437, 0.000000, -0.000000) m
[12:14:45]     inertia@origin: ixx=1.491071e-07 iyy=3.903589e-07 izz=3.986656e-07 kg·m²
[12:14:45]     inertia@com:    ixx=1.491071e-07 iyy=1.515334e-07 izz=1.598401e-07 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0125 x 0.0160 x 0.0160) m
[12:14:45]   [LEAF] d=1 10circlip_1
[12:14:45]     path: EG17-G10:1+¦µ10circlip (1):1
[12:14:45]     global_pos: (0.056669, -0.076327, 0.135897) m
[12:14:45]     mass: 0.000179 kg, bodies: 1
[12:14:45]     com_global: (0.056669, -0.076827, 0.137073) m
[12:14:45]     com_component_local: (-0.000000, -0.000500, 0.001176) m
[12:14:45]     inertia@origin: ixx=4.040028e-09 iyy=6.165970e-09 izz=2.245234e-09 kg·m²
[12:14:45]     inertia@com:    ixx=3.747851e-09 iyy=5.918527e-09 izz=2.200499e-09 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0115 x 0.0010 x 0.0144) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw_1
[12:14:45]     path: EG17-G10:1+M3hexagon socket head cap screw (1):1
[12:14:45]     global_pos: (0.040314, -0.072523, 0.127585) m
[12:14:45]     mass: 0.000191 kg, bodies: 1
[12:14:45]     com_global: (0.041699, -0.072522, 0.127584) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=8.485983e-10 iyy=9.436327e-10 izz=9.436874e-10 kg·m²
[12:14:45]     inertia@com:    ixx=8.485981e-10 iyy=5.768244e-10 izz=5.768791e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [LEAF] d=1 6801_1
[12:14:45]     path: EG17-G10:1+6801 (1):1
[12:14:45]     global_pos: (0.053893, -0.044247, 0.135897) m
[12:14:45]     mass: 0.004629 kg, bodies: 1
[12:14:45]     com_global: (0.053893, -0.044247, 0.138397) m
[12:14:45]     com_component_local: (0.000000, -0.000000, 0.002500) m
[12:14:45]     inertia@origin: ixx=2.075264e-07 iyy=2.075264e-07 izz=3.392209e-07 kg·m²
[12:14:45]     inertia@com:    ixx=1.785940e-07 iyy=1.785940e-07 izz=3.392209e-07 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0210 x 0.0210 x 0.0050) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw_1
[12:14:45]     path: EG17-G10:1+M3hexagon socket head cap screw (1):2
[12:14:45]     global_pos: (0.064501, -0.070429, 0.119930) m
[12:14:45]     mass: 0.000191 kg, bodies: 1
[12:14:45]     com_global: (0.065887, -0.070428, 0.119930) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=8.485983e-10 iyy=9.436327e-10 izz=9.436874e-10 kg·m²
[12:14:45]     inertia@com:    ixx=8.485981e-10 iyy=5.768244e-10 izz=5.768791e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw_1
[12:14:45]     path: EG17-G10:1+M3hexagon socket head cap screw (1):3
[12:14:45]     global_pos: (0.072128, -0.069769, 0.144208) m
[12:14:45]     mass: 0.000191 kg, bodies: 1
[12:14:45]     com_global: (0.073513, -0.069768, 0.144207) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=8.485983e-10 iyy=9.436327e-10 izz=9.436874e-10 kg·m²
[12:14:45]     inertia@com:    ixx=8.485981e-10 iyy=5.768244e-10 izz=5.768791e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw_1
[12:14:45]     path: EG17-G10:1+M3hexagon socket head cap screw (1):4
[12:14:45]     global_pos: (0.047940, -0.071863, 0.151863) m
[12:14:45]     mass: 0.000191 kg, bodies: 1
[12:14:45]     com_global: (0.049326, -0.071862, 0.151862) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=8.485983e-10 iyy=9.436327e-10 izz=9.436874e-10 kg·m²
[12:14:45]     inertia@com:    ixx=8.485981e-10 iyy=5.768244e-10 izz=5.768791e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw_1
[12:14:45]     path: EG17-G10:1+M3hexagon socket head cap screw (1):5
[12:14:45]     global_pos: (0.068075, -0.022944, 0.144208) m
[12:14:45]     mass: 0.000191 kg, bodies: 1
[12:14:45]     com_global: (0.069460, -0.022943, 0.144207) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=8.485983e-10 iyy=9.436327e-10 izz=9.436874e-10 kg·m²
[12:14:45]     inertia@com:    ixx=8.485981e-10 iyy=5.768244e-10 izz=5.768791e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw_1
[12:14:45]     path: EG17-G10:1+M3hexagon socket head cap screw (1):6
[12:14:45]     global_pos: (0.060448, -0.023604, 0.119930) m
[12:14:45]     mass: 0.000191 kg, bodies: 1
[12:14:45]     com_global: (0.061834, -0.023604, 0.119930) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=8.485983e-10 iyy=9.436327e-10 izz=9.436874e-10 kg·m²
[12:14:45]     inertia@com:    ixx=8.485981e-10 iyy=5.768244e-10 izz=5.768791e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw_1
[12:14:45]     path: EG17-G10:1+M3hexagon socket head cap screw (1):7
[12:14:45]     global_pos: (0.036261, -0.025698, 0.127585) m
[12:14:45]     mass: 0.000191 kg, bodies: 1
[12:14:45]     com_global: (0.037646, -0.025697, 0.127584) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=8.485983e-10 iyy=9.436327e-10 izz=9.436874e-10 kg·m²
[12:14:45]     inertia@com:    ixx=8.485981e-10 iyy=5.768244e-10 izz=5.768791e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [LEAF] d=1 M3hexagon_socket_head_cap_screw_1
[12:14:45]     path: EG17-G10:1+M3hexagon socket head cap screw (1):8
[12:14:45]     global_pos: (0.043887, -0.025038, 0.151863) m
[12:14:45]     mass: 0.000191 kg, bodies: 1
[12:14:45]     com_global: (0.045273, -0.025037, 0.151862) m
[12:14:45]     com_component_local: (0.001385, 0.000001, -0.000001) m
[12:14:45]     inertia@origin: ixx=8.485983e-10 iyy=9.436327e-10 izz=9.436874e-10 kg·m²
[12:14:45]     inertia@com:    ixx=8.485981e-10 iyy=5.768244e-10 izz=5.768791e-10 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0030 x 0.0053 x 0.0053) m
[12:14:45]   [SUBASM] d=0 EG17_G10
[12:14:45]     path: EG17-G10:1
[12:14:45]     global_pos: (0.052248, -0.024063, 0.139266) m
[12:14:45]   [LEAF] d=0 UA_Motor
[12:14:45]     path: UA Motor:1
[12:14:45]     global_pos: (0.051780, -0.019838, 0.135897) m
[12:14:45]     mass: 0.390226 kg, bodies: 1
[12:14:45]     com_global: (0.051780, -0.019860, 0.159549) m
[12:14:45]     com_component_local: (0.000000, -0.000022, 0.023653) m
[12:14:45]     inertia@origin: ixx=3.513838e-04 iyy=3.510934e-04 izz=1.078761e-04 kg·m²
[12:14:45]     inertia@com:    ixx=1.330715e-04 iyy=1.327813e-04 izz=1.078759e-04 kg·m²
[12:14:45]     material: UA_Motor
[12:14:45]     color: RGB(1.00, 1.00, 1.00) [Opaque_255_255_255]
[12:14:45]     bbox: (0.0423 x 0.0603 x 0.0720) m
[12:14:45]   [LEAF] d=1 92605A009_1
[12:14:45]     path: UA Shaft Coupler:1+92605A009 (1):1
[12:14:45]     global_pos: (0.177168, -0.177029, 0.072153) m
[12:14:45]   [LEAF] d=1 Connector_1
[12:14:45]     path: UA Shaft Coupler:1+Connector (1):1
[12:14:45]     global_pos: (0.058290, -0.095057, 0.135897) m
[12:14:45]     mass: 0.027734 kg, bodies: 1
[12:14:45]     com_global: (0.058228, -0.090961, 0.135834) m
[12:14:45]     com_component_local: (-0.000062, 0.004096, -0.000062) m
[12:14:45]     inertia@origin: ixx=2.196173e-06 iyy=2.689968e-06 izz=2.196171e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.730749e-06 iyy=2.689752e-06 izz=1.730747e-06 kg·m²
[12:14:45]     material: Steel
[12:14:45]     color: RGB(0.98, 0.98, 0.96) [Silver_Polished]
[12:14:45]     bbox: (0.0320 x 0.0130 x 0.0320) m
[12:14:45]   [LEAF] d=1 92605A009_1
[12:14:45]     path: UA Shaft Coupler:1+92605A009 (1):2
[12:14:45]     global_pos: (0.171182, -0.177547, 0.066145) m
[12:14:45]   [SUBASM] d=0 UA_Shaft_Coupler
[12:14:45]     path: UA Shaft Coupler:1
[12:14:45]     global_pos: (0.176478, -0.169058, 0.066145) m
[12:14:45]   [LEAF] d=0 Elbow_Connector_Passive
[12:14:45]     path: Elbow Connector Passive:1
[12:14:45]     global_pos: (0.111341, 0.026973, 0.215314) m
[12:14:45]     mass: 0.010964 kg, bodies: 1
[12:14:45]     com_global: (0.111341, 0.026973, 0.224577) m
[12:14:45]     com_component_local: (0.000000, 0.000000, 0.009262) m
[12:14:45]     inertia@origin: ixx=2.372988e-06 iyy=2.372988e-06 izz=1.275592e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.432402e-06 iyy=1.432403e-06 izz=1.275592e-06 kg·m²
[12:14:45]     material: PETG_30_Gyroid_ECP
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.0350 x 0.0350 x 0.0300) m
[12:14:45]   [LEAF] d=1 Component52
[12:14:45]     path: GT2 Elbow Connector:1+Component52:1
[12:14:45]     global_pos: (0.122551, -0.102543, 0.215314) m
[12:14:45]     mass: 0.025855 kg, bodies: 1
[12:14:45]     com_global: (0.122551, -0.102543, 0.227107) m
[12:14:45]     com_component_local: (0.000000, 0.000000, 0.011793) m
[12:14:45]     inertia@origin: ixx=1.098370e-05 iyy=1.098370e-05 izz=9.494729e-06 kg·m²
[12:14:45]     inertia@com:    ixx=7.388056e-06 iyy=7.388056e-06 izz=9.494729e-06 kg·m²
[12:14:45]     material: PETG_25_Gryoid_ECA
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.0652 x 0.0652 x 0.0380) m
[12:14:45]   [SUBASM] d=0 GT2_Elbow_Connector
[12:14:45]     path: GT2 Elbow Connector:1
[12:14:45]     global_pos: (0.136592, -0.123750, 0.112897) m
[12:14:45]   [LEAF] d=1 Component54
[12:14:45]     path: GT2 400mm Motor Connector:1+Component54:1
[12:14:45]     global_pos: (0.059153, -0.105019, 0.135897) m
[12:14:45]     mass: 0.012921 kg, bodies: 1
[12:14:45]     com_global: (0.059153, -0.105019, 0.140879) m
[12:14:45]     com_component_local: (0.000000, 0.000000, 0.004983) m
[12:14:45]     inertia@origin: ixx=3.799688e-06 iyy=3.799688e-06 izz=6.735600e-06 kg·m²
[12:14:45]     inertia@com:    ixx=3.478883e-06 iyy=3.478883e-06 izz=6.735600e-06 kg·m²
[12:14:45]     material: PETG_10_Grid_UA_Gear
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.0652 x 0.0652 x 0.0100) m
[12:14:45]   [SUBASM] d=0 GT2_400mm_Motor_Connector
[12:14:45]     path: GT2 400mm Motor Connector:1
[12:14:45]     global_pos: (0.257304, -0.117941, 0.100536) m
[12:14:45]   [LEAF] d=0 Elbow_Belt_Sensorless
[12:14:45]     path: Elbow Belt Sensorless:1
[12:14:45]     global_pos: (0.074382, -0.034945, 0.287390) m
[12:14:45]     mass: 0.138434 kg, bodies: 1
[12:14:45]     com_global: (0.074382, -0.077056, 0.284535) m
[12:14:45]     com_component_local: (-0.000000, -0.042111, -0.002854) m
[12:14:45]     inertia@origin: ixx=5.281802e-04 iyy=1.299795e-04 izz=5.580865e-04 kg·m²
[12:14:45]     inertia@com:    ixx=2.815608e-04 iyy=1.288516e-04 izz=3.125951e-04 kg·m²
[12:14:45]     material: PETG_25_Gyroid_EH
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.0670 x 0.1464 x 0.0700) m
[12:14:45]   [LEAF] d=0 Elbow_Motor
[12:14:45]     path: Elbow Motor:1
[12:14:45]     global_pos: (0.093689, -0.033274, 0.199984) m
[12:14:45]     mass: 0.390226 kg, bodies: 1
[12:14:45]     com_global: (0.093689, -0.033296, 0.223636) m
[12:14:45]     com_component_local: (0.000000, -0.000022, 0.023653) m
[12:14:45]     inertia@origin: ixx=3.513838e-04 iyy=3.510934e-04 izz=1.078761e-04 kg·m²
[12:14:45]     inertia@com:    ixx=1.330715e-04 iyy=1.327813e-04 izz=1.078759e-04 kg·m²
[12:14:45]     material: Iron_Wrought
[12:14:45]     color: RGB(1.00, 1.00, 1.00) [Opaque_255_255_255]
[12:14:45]     bbox: (0.0423 x 0.0603 x 0.0720) m
[12:14:45]   [LEAF] d=1 HR32906J_Inner_ring
[12:14:45]     path: Roll Bearing 2:3+HR32906J Inner ring:1
[12:14:45]     global_pos: (0.051623, -0.036915, 0.277482) m
[12:14:45]     mass: 0.045132 kg, bodies: 1
[12:14:45]     com_global: (0.046189, -0.036915, 0.277482) m
[12:14:45]     com_component_local: (-0.005434, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=1.370829e-05 iyy=8.686935e-06 izz=8.686846e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.370829e-05 iyy=7.354228e-06 izz=7.354139e-06 kg·m²
[12:14:45]     material: Bearing_Steel
[12:14:45]     color: RGB(0.98, 0.98, 0.96) [Silver_Polished]
[12:14:45]     bbox: (0.0120 x 0.0432 x 0.0432) m
[12:14:45]   [LEAF] d=1 HR32906J_Outer_ring
[12:14:45]     path: Roll Bearing 2:3+HR32906J Outer ring:1
[12:14:45]     global_pos: (0.051623, -0.036915, 0.277482) m
[12:14:45]     mass: 0.029417 kg, bodies: 1
[12:14:45]     com_global: (0.043629, -0.036915, 0.277482) m
[12:14:45]     com_component_local: (-0.007994, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=1.440246e-05 iyy=9.271567e-06 izz=9.271567e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.440246e-05 iyy=7.391575e-06 izz=7.391575e-06 kg·m²
[12:14:45]     material: Bearing_Steel
[12:14:45]     color: RGB(0.98, 0.98, 0.96) [Silver_Polished]
[12:14:45]     bbox: (0.0090 x 0.0470 x 0.0470) m
[12:14:45]   [SUBASM] d=0 Roll_Bearing_2
[12:14:45]     path: Roll Bearing 2:3
[12:14:45]     global_pos: (0.099032, -0.166007, 0.165928) m
[12:14:45]   [LEAF] d=1 HR32906J_Inner_ring
[12:14:45]     path: Roll Bearing 2:4+HR32906J Inner ring:1
[12:14:45]     global_pos: (0.097141, -0.032975, 0.297298) m
[12:14:45]     mass: 0.045132 kg, bodies: 1
[12:14:45]     com_global: (0.091707, -0.032975, 0.297298) m
[12:14:45]     com_component_local: (-0.005434, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=1.370829e-05 iyy=8.686935e-06 izz=8.686846e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.370829e-05 iyy=7.354228e-06 izz=7.354139e-06 kg·m²
[12:14:45]     material: Bearing_Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0120 x 0.0432 x 0.0432) m
[12:14:45]   [LEAF] d=1 HR32906J_Outer_ring
[12:14:45]     path: Roll Bearing 2:4+HR32906J Outer ring:1
[12:14:45]     global_pos: (0.097141, -0.032975, 0.297298) m
[12:14:45]     mass: 0.029417 kg, bodies: 1
[12:14:45]     com_global: (0.089147, -0.032975, 0.297298) m
[12:14:45]     com_component_local: (-0.007994, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=1.440246e-05 iyy=9.271567e-06 izz=9.271567e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.440246e-05 iyy=7.391575e-06 izz=7.391575e-06 kg·m²
[12:14:45]     material: Bearing_Steel
[12:14:45]     color: RGB(0.98, 0.98, 0.96) [Silver_Polished]
[12:14:45]     bbox: (0.0090 x 0.0470 x 0.0470) m
[12:14:45]   [SUBASM] d=0 Roll_Bearing_2
[12:14:45]     path: Roll Bearing 2:4
[12:14:45]     global_pos: (0.280742, -0.098574, 0.298136) m
[12:14:45]   [LEAF] d=1 Component58
[12:14:45]     path: Shaft Connector:1+Component58:1
[12:14:45]     global_pos: (0.051623, -0.036915, 0.277482) m
[12:14:45]     mass: 0.028892 kg, bodies: 1
[12:14:45]     com_global: (0.051623, -0.036915, 0.263810) m
[12:14:45]     com_component_local: (-0.000000, -0.000000, -0.013672) m
[12:14:45]     inertia@origin: ixx=1.830279e-05 iyy=1.830279e-05 izz=5.505948e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.290215e-05 iyy=1.290215e-05 izz=5.505948e-06 kg·m²
[12:14:45]     material: PET_Plastic
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.0524 x 0.0524 x 0.0610) m
[12:14:45]   [SUBASM] d=0 Shaft_Connector
[12:14:45]     path: Shaft Connector:1
[12:14:45]     global_pos: (0.162400, -0.198097, 0.089529) m
[12:14:45]   [LEAF] d=0 Elbow_Cap
[12:14:45]     path: Elbow Cap:1
[12:14:45]     global_pos: (0.100980, -0.032643, 0.298969) m
[12:14:45]     mass: 0.000970 kg, bodies: 1
[12:14:45]     com_global: (0.100980, -0.032643, 0.300969) m
[12:14:45]     com_component_local: (0.000000, 0.000000, 0.002000) m
[12:14:45]     inertia@origin: ixx=8.066178e-08 iyy=8.066180e-08 izz=1.509807e-07 kg·m²
[12:14:45]     inertia@com:    ixx=7.678318e-08 iyy=7.678320e-08 izz=1.509807e-07 kg·m²
[12:14:45]     material: PETG_15_Gyroid
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.0350 x 0.0350 x 0.0040) m
[12:14:45]   [LEAF] d=0 Motor_Housing_Roll
[12:14:45]     path: Motor Housing Roll:1
[12:14:45]     global_pos: (0.041569, -0.037785, 0.273105) m
[12:14:45]     mass: 0.120881 kg, bodies: 1
[12:14:45]     com_global: (0.043666, -0.038337, 0.349536) m
[12:14:45]     com_component_local: (0.002097, -0.000552, 0.076431) m
[12:14:45]     inertia@origin: ixx=1.022640e-03 iyy=1.131636e-03 izz=1.730749e-04 kg·m²
[12:14:45]     inertia@com:    ixx=3.164606e-04 iyy=4.249617e-04 izz=1.725064e-04 kg·m²
[12:14:45]     material: PETG_30_Gyroid_RH
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.0910 x 0.0500 x 0.1640) m
[12:14:45]   [LEAF] d=0 Roll_Motor
[12:14:45]     path: Roll Motor:1
[12:14:45]     global_pos: (0.008721, -0.002018, 0.258513) m
[12:14:45]     mass: 0.390226 kg, bodies: 1
[12:14:45]     com_global: (0.008721, -0.002040, 0.282166) m
[12:14:45]     com_component_local: (0.000000, -0.000022, 0.023653) m
[12:14:45]     inertia@origin: ixx=3.513838e-04 iyy=3.510934e-04 izz=1.078761e-04 kg·m²
[12:14:45]     inertia@com:    ixx=1.330715e-04 iyy=1.327813e-04 izz=1.078759e-04 kg·m²
[12:14:45]     material: Iron_Wrought
[12:14:45]     color: RGB(1.00, 1.00, 1.00) [Opaque_255_255_255]
[12:14:45]     bbox: (0.0423 x 0.0603 x 0.0720) m
[12:14:45]   [LEAF] d=0 Passive_Cap
[12:14:45]     path: Passive Cap:1
[12:14:45]     global_pos: (-0.067108, -0.074771, 0.226003) m
[12:14:45]     mass: 0.007373 kg, bodies: 1
[12:14:45]     com_global: (-0.067108, -0.074771, 0.238450) m
[12:14:45]     com_component_local: (-0.000000, 0.000000, 0.012447) m
[12:14:45]     inertia@origin: ixx=1.906025e-06 iyy=1.906025e-06 izz=8.856442e-07 kg·m²
[12:14:45]     inertia@com:    ixx=7.637444e-07 iyy=7.637445e-07 izz=8.856442e-07 kg·m²
[12:14:45]     material: PC_Roll_Housing
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.0350 x 0.0350 x 0.0230) m
[12:14:45]   [LEAF] d=1 HR32906J_Inner_ring
[12:14:45]     path: Roll Bearing 2:5+HR32906J Inner ring:1
[12:14:45]     global_pos: (-0.065852, -0.092714, 0.226686) m
[12:14:45]     mass: 0.045132 kg, bodies: 1
[12:14:45]     com_global: (-0.071286, -0.092714, 0.226687) m
[12:14:45]     com_component_local: (-0.005434, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=1.370829e-05 iyy=8.686935e-06 izz=8.686846e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.370829e-05 iyy=7.354228e-06 izz=7.354139e-06 kg·m²
[12:14:45]     material: Bearing_Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0120 x 0.0432 x 0.0432) m
[12:14:45]   [LEAF] d=1 HR32906J_Outer_ring
[12:14:45]     path: Roll Bearing 2:5+HR32906J Outer ring:1
[12:14:45]     global_pos: (-0.065852, -0.092714, 0.226686) m
[12:14:45]     mass: 0.029417 kg, bodies: 1
[12:14:45]     com_global: (-0.073846, -0.092714, 0.226686) m
[12:14:45]     com_component_local: (-0.007994, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=1.440246e-05 iyy=9.271567e-06 izz=9.271567e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.440246e-05 iyy=7.391575e-06 izz=7.391575e-06 kg·m²
[12:14:45]     material: Bearing_Steel
[12:14:45]     color: RGB(0.98, 0.98, 0.96) [Silver_Polished]
[12:14:45]     bbox: (0.0090 x 0.0470 x 0.0470) m
[12:14:45]   [SUBASM] d=0 Roll_Bearing_2
[12:14:45]     path: Roll Bearing 2:5
[12:14:45]     global_pos: (-0.179504, -0.250298, 0.243397) m
[12:14:45]   [LEAF] d=1 HR32906J_Inner_ring
[12:14:45]     path: Roll Bearing 2:6+HR32906J Inner ring:1
[12:14:45]     global_pos: (-0.072200, -0.002002, 0.223232) m
[12:14:45]     mass: 0.045132 kg, bodies: 1
[12:14:45]     com_global: (-0.077634, -0.002002, 0.223232) m
[12:14:45]     com_component_local: (-0.005434, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=1.370829e-05 iyy=8.686935e-06 izz=8.686846e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.370829e-05 iyy=7.354228e-06 izz=7.354139e-06 kg·m²
[12:14:45]     material: Bearing_Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0120 x 0.0432 x 0.0432) m
[12:14:45]   [LEAF] d=1 HR32906J_Outer_ring
[12:14:45]     path: Roll Bearing 2:6+HR32906J Outer ring:1
[12:14:45]     global_pos: (-0.072200, -0.002002, 0.223232) m
[12:14:45]     mass: 0.029417 kg, bodies: 1
[12:14:45]     com_global: (-0.080194, -0.002002, 0.223232) m
[12:14:45]     com_component_local: (-0.007994, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=1.440246e-05 iyy=9.271567e-06 izz=9.271567e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.440246e-05 iyy=7.391575e-06 izz=7.391575e-06 kg·m²
[12:14:45]     material: Bearing_Steel
[12:14:45]     color: RGB(0.98, 0.98, 0.96) [Silver_Polished]
[12:14:45]     bbox: (0.0090 x 0.0470 x 0.0470) m
[12:14:45]   [SUBASM] d=0 Roll_Bearing_2
[12:14:45]     path: Roll Bearing 2:6
[12:14:45]     global_pos: (-0.201719, -0.307444, 0.209205) m
[12:14:45]   [LEAF] d=1 Component64
[12:14:45]     path: Belt Shaft:1+Component64:1
[12:14:45]     global_pos: (-0.073037, 0.009960, 0.222777) m
[12:14:45]     mass: 0.014791 kg, bodies: 1
[12:14:45]     com_global: (-0.073037, 0.009960, 0.233452) m
[12:14:45]     com_component_local: (0.000000, 0.000000, 0.010675) m
[12:14:45]     inertia@origin: ixx=4.468267e-06 iyy=4.468267e-06 izz=3.638875e-06 kg·m²
[12:14:45]     inertia@com:    ixx=2.782782e-06 iyy=2.782782e-06 izz=3.638875e-06 kg·m²
[12:14:45]     material: Active_Cap_Roll
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.0524 x 0.0524 x 0.0300) m
[12:14:45]   [SUBASM] d=0 Belt_Shaft
[12:14:45]     path: Belt Shaft:1
[12:14:45]     global_pos: (-0.073037, 0.009960, 0.222777) m
[12:14:45]   [LEAF] d=0 Motor_Housing_Yaw
[12:14:45]     path: Motor Housing Yaw:1
[12:14:45]     global_pos: (-0.097266, -0.048455, 0.248058) m
[12:14:45]     mass: 0.045446 kg, bodies: 1
[12:14:45]     com_global: (-0.098816, -0.048455, 0.227398) m
[12:14:45]     com_component_local: (-0.001550, -0.000000, -0.020661) m
[12:14:45]     inertia@origin: ixx=5.439205e-05 iyy=5.339116e-05 izz=3.126589e-05 kg·m²
[12:14:45]     inertia@com:    ixx=3.499295e-05 iyy=3.388287e-05 izz=3.115670e-05 kg·m²
[12:14:45]     material: Yaw_Housing
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.0550 x 0.0550 x 0.0765) m
[12:14:45]   [LEAF] d=1 HR32906J_Inner_ring
[12:14:45]     path: Roll Bearing 2:7+HR32906J Inner ring:1
[12:14:45]     global_pos: (-0.112740, -0.049055, 0.260715) m
[12:14:45]     mass: 0.045132 kg, bodies: 1
[12:14:45]     com_global: (-0.118174, -0.049055, 0.260715) m
[12:14:45]     com_component_local: (-0.005434, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=1.370829e-05 iyy=8.686935e-06 izz=8.686846e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.370829e-05 iyy=7.354228e-06 izz=7.354139e-06 kg·m²
[12:14:45]     material: Bearing_Steel
[12:14:45]     color: RGB(0.63, 0.63, 0.63) [Steel_Satin]
[12:14:45]     bbox: (0.0120 x 0.0432 x 0.0432) m
[12:14:45]   [LEAF] d=1 HR32906J_Outer_ring
[12:14:45]     path: Roll Bearing 2:7+HR32906J Outer ring:1
[12:14:45]     global_pos: (-0.112740, -0.049055, 0.260715) m
[12:14:45]     mass: 0.029417 kg, bodies: 1
[12:14:45]     com_global: (-0.120734, -0.049055, 0.260715) m
[12:14:45]     com_component_local: (-0.007994, 0.000000, 0.000000) m
[12:14:45]     inertia@origin: ixx=1.440246e-05 iyy=9.271567e-06 izz=9.271567e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.440246e-05 iyy=7.391575e-06 izz=7.391575e-06 kg·m²
[12:14:45]     material: Bearing_Steel
[12:14:45]     color: RGB(0.98, 0.98, 0.96) [Silver_Polished]
[12:14:45]     bbox: (0.0090 x 0.0470 x 0.0470) m
[12:14:45]   [SUBASM] d=0 Roll_Bearing_2
[12:14:45]     path: Roll Bearing 2:7
[12:14:45]     global_pos: (0.066042, -0.164696, 0.317817) m
[12:14:45]   [LEAF] d=0 Yaw_Motor
[12:14:45]     path: Yaw Motor:1
[12:14:45]     global_pos: (-0.064771, -0.047193, 0.221479) m
[12:14:45]     mass: 0.139847 kg, bodies: 1
[12:14:45]     com_global: (-0.064771, -0.047240, 0.232019) m
[12:14:45]     com_component_local: (-0.000000, -0.000047, 0.010540) m
[12:14:45]     inertia@origin: ixx=4.024218e-05 iyy=4.001974e-05 izz=3.845672e-05 kg·m²
[12:14:45]     inertia@com:    ixx=2.470563e-05 iyy=2.448351e-05 izz=3.845641e-05 kg·m²
[12:14:45]     material: Yaw_Motor
[12:14:45]     color: RGB(1.00, 1.00, 1.00) [Opaque_255_255_255]
[12:14:45]     bbox: (0.0423 x 0.0603 x 0.0400) m
[12:14:45]   [LEAF] d=0 Gripper_Shaft
[12:14:45]     path: Gripper Shaft:1
[12:14:45]     global_pos: (-0.098040, -0.048485, 0.248691) m
[12:14:45]     mass: 0.011203 kg, bodies: 1
[12:14:45]     com_global: (-0.098040, -0.048485, 0.267999) m
[12:14:45]     com_component_local: (0.000000, -0.000000, 0.019308) m
[12:14:45]     inertia@origin: ixx=6.111915e-06 iyy=6.111915e-06 izz=1.864791e-06 kg·m²
[12:14:45]     inertia@com:    ixx=1.935595e-06 iyy=1.935595e-06 izz=1.864791e-06 kg·m²
[12:14:45]     material: Yaw_Shaft
[12:14:45]     color: RGB(0.10, 0.10, 0.10) [Plastic_Matte_Black]
[12:14:45]     bbox: (0.0400 x 0.0400 x 0.0340) m
[12:14:45]   [FRAME] d=0 ua
[12:14:45]     path: !frame_ua:1
[12:14:45]     global_pos: (-0.007100, -0.149900, 0.060400) m
[12:14:45]   [FRAME] d=0 elbow
[12:14:45]     path: !frame_elbow:1
[12:14:45]     global_pos: (0.122551, -0.102543, 0.215314) m
[12:14:45]   [FRAME] d=0 roll
[12:14:45]     path: !frame_roll:1
[12:14:45]     global_pos: (0.100980, -0.032643, 0.298969) m
[12:14:45]   [FRAME] d=0 yaw
[12:14:45]     path: !frame_yaw:1
[12:14:45]     global_pos: (-0.065503, -0.097698, 0.226876) m
[12:14:45]   [FRAME] d=0 gripper
[12:14:45]     path: !frame_gripper:1
[12:14:45]     global_pos: (-0.124345, -0.049506, 0.270208) m
[12:14:45]   [FRAME] d=0 shoulder
[12:14:45]     path: !frame_shoulder:1
[12:14:45]     global_pos: (0.000000, 0.000000, -0.051500) m
[12:14:45]   Extracted 98 occurrences
[12:14:45] 
=== EXTRACTION: JOINTS ===
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_1
[12:14:45]     parent(occ2): base_link path=base_link:1
[12:14:45]     child(occ1):  Shoulder_Bearing_2_Lower path=Shoulder Bearing 2 Lower:1
[12:14:45]     geometryOrOriginOne: (-0.0000, -0.0000, -1.5000) cm
[12:14:45]     geometryOrOriginTwo: (0.0000, 0.0000, -1.5000) cm
[12:14:45]     occ1.transform: (0.0000, 0.0000, 0.0000) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (0.0000, 0.0000, 0.0000) cm
[12:14:45]     occ2.transform: (0.0000, 0.0000, 0.0000) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (0.0000, 0.0000, 0.0000) cm
[12:14:45]  -> origin_global: (-0.000000, -0.000000, -0.015000) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_2
[12:14:45]     parent(occ2): base_link path=base_link:1
[12:14:45]     child(occ1):  Shoulder_Bearing_2_Upper path=Shoulder Bearing 2 Upper:1
[12:14:45]     geometryOrOriginOne: (0.0000, 0.0000, -1.5000) cm
[12:14:45]     geometryOrOriginTwo: (0.0000, 0.0000, -1.5000) cm
[12:14:45]     occ1.transform: (0.0000, 0.0000, -0.0600) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (0.0000, 0.0000, -0.0600) cm
[12:14:45]     occ2.transform: (0.0000, 0.0000, 0.0000) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (0.0000, 0.0000, 0.0000) cm
[12:14:45]  -> origin_global: (0.000000, 0.000000, -0.015000) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_3
[12:14:45]     parent(occ2): base_link path=base_link:1
[12:14:45]     child(occ1):  Lower_Bottom_Base_Bearing_Ring path=Lower Bottom Base Bearing Ring:1
[12:14:45]     geometryOrOriginOne: (0.0000, -0.0000, -3.6000) cm
[12:14:45]     geometryOrOriginTwo: (0.0000, 0.0000, -3.6000) cm
[12:14:45]     occ1.transform: (-2.7200, -5.6181, 7.0740) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-2.7200, -5.6181, 7.0740) cm
[12:14:45]     occ2.transform: (0.0000, 0.0000, 0.0000) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (0.0000, 0.0000, 0.0000) cm
[12:14:45]  -> origin_global: (0.000000, -0.000000, -0.036000) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_4
[12:14:45]     parent(occ2): base_link path=base_link:1
[12:14:45]     child(occ1):  Lower_Upper_Base_Bearing_Ring path=Lower Upper Base Bearing Ring:1
[12:14:45]     geometryOrOriginOne: (0.0000, 0.0000, -3.6000) cm
[12:14:45]     geometryOrOriginTwo: (0.0000, 0.0000, -3.6000) cm
[12:14:45]     occ1.transform: (-2.7200, -5.6181, 7.0740) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-2.7200, -5.6181, 7.0740) cm
[12:14:45]     occ2.transform: (0.0000, 0.0000, 0.0000) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (0.0000, 0.0000, 0.0000) cm
[12:14:45]  -> origin_global: (0.000000, 0.000000, -0.036000) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Revolute_5
[12:14:45]     parent(occ2): Shoulder_Bearing_2_Upper path=Shoulder Bearing 2 Upper:1
[12:14:45]     child(occ1):  Base_Connector_Shaft_V2 path=Base Connector + Shaft V2:1
[12:14:45]     geometryOrOriginOne: (0.0000, 0.0000, -0.0600) cm
[12:14:45]     geometryOrOriginTwo: (0.0000, -0.0000, -0.0600) cm
[12:14:45]     occ1.transform: (7.4721, 0.6468, 2.5400) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (7.4721, 0.6468, 2.5400) cm
[12:14:45]     occ2.transform: (0.0000, 0.0000, -0.0600) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (0.0000, 0.0000, -0.0600) cm
[12:14:45]  -> origin_global: (0.000000, 0.000000, -0.000600) m [via geometryOrOriginOne]
[12:14:45]     motion: revolute, axis: (-0.000, 0.000, 1.000)
[12:14:45]     rotation limits: [0.0000, 6.2832] rad
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_7
[12:14:45]     parent(occ2): Base_Connector_Shaft_V2 path=Base Connector + Shaft V2:1
[12:14:45]     child(occ1):  Motor_Connector_Shoulder path=Motor Connector Shoulder:1
[12:14:45]     geometryOrOriginOne: (0.1681, 3.8559, 2.5400) cm
[12:14:45]     geometryOrOriginTwo: (0.1681, 3.8559, 2.5400) cm
[12:14:45]     occ1.transform: (-2.2708, 3.0426, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-2.2708, 3.0426, 6.0400) cm
[12:14:45]     occ2.transform: (7.4721, 0.6468, 2.5400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (7.4721, 0.6468, 2.5400) cm
[12:14:45]  -> origin_global: (0.001681, 0.038559, 0.025400) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_8
[12:14:45]     parent(occ2): Base_Connector_Shaft_V2 path=Base Connector + Shaft V2:1
[12:14:45]     child(occ1):  Bearing_Housing_Shoulder_V2 path=Bearing Housing Shoulder V2:1
[12:14:45]     geometryOrOriginOne: (1.1522, -10.4123, 2.5400) cm
[12:14:45]     geometryOrOriginTwo: (1.1522, -10.4123, 2.5400) cm
[12:14:45]     occ1.transform: (-0.9385, -12.3499, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-0.9385, -12.3499, 6.0400) cm
[12:14:45]     occ2.transform: (7.4721, 0.6468, 2.5400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (7.4721, 0.6468, 2.5400) cm
[12:14:45]  -> origin_global: (0.011522, -0.104123, 0.025400) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_9
[12:14:45]     parent(occ2): Bearing_Housing_Shoulder_V2 path=Bearing Housing Shoulder V2:1
[12:14:45]     child(occ1):  Shoulder_Bearing_2_Lower path=Shoulder Bearing 2 Lower:2
[12:14:45]     geometryOrOriginOne: (-0.9946, -11.7023, 6.0400) cm
[12:14:45]     geometryOrOriginTwo: (-0.9946, -11.7023, 6.0400) cm
[12:14:45]     occ1.transform: (-1.1239, -10.2079, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-1.1239, -10.2079, 6.0400) cm
[12:14:45]     occ2.transform: (-0.9385, -12.3499, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-0.9385, -12.3499, 6.0400) cm
[12:14:45]  -> origin_global: (-0.009946, -0.117023, 0.060400) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_10
[12:14:45]     parent(occ2): Shoulder_Bearing_2_Lower path=Shoulder Bearing 2 Lower:2
[12:14:45]     child(occ1):  Shoulder_Bearing_2_Upper path=Shoulder Bearing 2 Upper:2
[12:14:45]     geometryOrOriginOne: (-0.9946, -11.7023, 6.0400) cm
[12:14:45]     geometryOrOriginTwo: (-0.9946, -11.7023, 6.0400) cm
[12:14:45]     occ1.transform: (-1.1239, -10.2079, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-1.1239, -10.2079, 6.0400) cm
[12:14:45]     occ2.transform: (-1.1239, -10.2079, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-1.1239, -10.2079, 6.0400) cm
[12:14:45]  -> origin_global: (-0.009946, -0.117023, 0.060400) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_11
[12:14:45]     parent(occ2): Bearing_Housing_Shoulder_V2 path=Bearing Housing Shoulder V2:1
[12:14:45]     child(occ1):  Shoulder_Bearing_2_Lower path=Shoulder Bearing 2 Lower:3
[12:14:45]     geometryOrOriginOne: (-0.8825, -12.9974, 6.0400) cm
[12:14:45]     geometryOrOriginTwo: (-0.8825, -12.9974, 6.0400) cm
[12:14:45]     occ1.transform: (-0.7531, -14.4918, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-0.7531, -14.4918, 6.0400) cm
[12:14:45]     occ2.transform: (-0.9385, -12.3499, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-0.9385, -12.3499, 6.0400) cm
[12:14:45]  -> origin_global: (-0.008825, -0.129974, 0.060400) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_12
[12:14:45]     parent(occ2): Bearing_Housing_Shoulder_V2 path=Bearing Housing Shoulder V2:1
[12:14:45]     child(occ1):  Shoulder_Bearing_2_Upper path=Shoulder Bearing 2 Upper:3
[12:14:45]     geometryOrOriginOne: (-0.8825, -12.9974, 6.0400) cm
[12:14:45]     geometryOrOriginTwo: (-0.8825, -12.9974, 6.0400) cm
[12:14:45]     occ1.transform: (-0.7531, -14.4918, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-0.7531, -14.4918, 6.0400) cm
[12:14:45]     occ2.transform: (-0.9385, -12.3499, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-0.9385, -12.3499, 6.0400) cm
[12:14:45]  -> origin_global: (-0.008825, -0.129974, 0.060400) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Revolute_13
[12:14:45]     parent(occ2): Shoulder_Bearing_2_Upper path=Shoulder Bearing 2 Upper:3
[12:14:45]     child(occ1):  Upper_arm path=Upper arm:1
[12:14:45]     geometryOrOriginOne: (-0.7531, -14.4918, 6.0400) cm
[12:14:45]     geometryOrOriginTwo: (-0.7531, -14.4918, 6.0400) cm
[12:14:45]     occ1.transform: (-1.9690, -0.4444, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-1.9690, -0.4444, 6.0400) cm
[12:14:45]     occ2.transform: (-0.7531, -14.4918, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-0.7531, -14.4918, 6.0400) cm
[12:14:45]  -> origin_global: (-0.007531, -0.144918, 0.060400) m [via geometryOrOriginOne]
[12:14:45]     motion: revolute, axis: (0.086, -0.996, -0.000)
[12:14:45]     rotation limits: [0.0000, 6.2832] rad
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_14
[12:14:45]     parent(occ2): Upper_arm path=Upper arm:1
[12:14:45]     child(occ1):  Shoulder_Cap path=Shoulder Cap:2
[12:14:45]     geometryOrOriginOne: (-0.7531, -14.4918, 6.0400) cm
[12:14:45]     geometryOrOriginTwo: (-0.7531, -14.4918, 6.0400) cm
[12:14:45]     occ1.transform: (-0.7531, -14.4918, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-0.7531, -14.4918, 6.0400) cm
[12:14:45]     occ2.transform: (-1.9690, -0.4444, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-1.9690, -0.4444, 6.0400) cm
[12:14:45]  -> origin_global: (-0.007531, -0.144918, 0.060400) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_15
[12:14:45]     parent(occ2): Upper_arm path=Upper arm:1
[12:14:45]     child(occ1):  Connector path=UA Shaft COupler:1+Connector:1
[12:14:45]     geometryOrOriginOne: (-1.3730, 1.6147, 6.9593) cm
[12:14:45]     geometryOrOriginTwo: (-1.3730, 1.6147, 6.9593) cm
[12:14:45]     occ1.transform: (8.8628, -24.5162, 7.3113) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (-2.1415, 1.5482, 6.0400) cm
[12:14:45]     occ2.transform: (-1.9690, -0.4444, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-1.9690, -0.4444, 6.0400) cm
[12:14:45]  -> origin_global: (-0.013730, 0.016147, 0.069593) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_16
[12:14:45]     parent(occ2): Upper_arm path=Upper arm:1
[12:14:45]     child(occ1):  HR32906J_Outer_ring path=Roll Bearing 2:1+HR32906J Outer ring:1
[12:14:45]     geometryOrOriginOne: (12.0395, -7.7636, 21.5314) cm
[12:14:45]     geometryOrOriginTwo: (12.0395, -7.7636, 21.5314) cm
[12:14:45]     occ1.transform: (-17.4175, -3.9359, 4.6736) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (12.1430, -8.9591, 21.5314) cm
[12:14:45]     occ2.transform: (-1.9690, -0.4444, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-1.9690, -0.4444, 6.0400) cm
[12:14:45]  -> origin_global: (0.120395, -0.077636, 0.215314) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_17
[12:14:45]     parent(occ2): Upper_arm path=Upper arm:1
[12:14:45]     child(occ1):  HR32906J_Inner_ring path=Roll Bearing 2:1+HR32906J Inner ring:1
[12:14:45]     geometryOrOriginOne: (12.0395, -7.7636, 21.5314) cm
[12:14:45]     geometryOrOriginTwo: (12.0395, -7.7636, 21.5314) cm
[12:14:45]     occ1.transform: (-17.4175, -3.9359, 4.6736) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (12.1430, -8.9591, 21.5314) cm
[12:14:45]     occ2.transform: (-1.9690, -0.4444, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-1.9690, -0.4444, 6.0400) cm
[12:14:45]  -> origin_global: (0.120395, -0.077636, 0.215314) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_18
[12:14:45]     parent(occ2): Upper_arm path=Upper arm:1
[12:14:45]     child(occ1):  HR32906J_Outer_ring path=Roll Bearing 2:2+HR32906J Outer ring:1
[12:14:45]     geometryOrOriginOne: (11.2376, 1.5017, 21.5314) cm
[12:14:45]     geometryOrOriginTwo: (11.2376, 1.5017, 21.5314) cm
[12:14:45]     occ1.transform: (-19.9680, 2.7226, 0.8620) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (11.1341, 2.6973, 21.5314) cm
[12:14:45]     occ2.transform: (-1.9690, -0.4444, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-1.9690, -0.4444, 6.0400) cm
[12:14:45]  -> origin_global: (0.112376, 0.015017, 0.215314) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_19
[12:14:45]     parent(occ2): Upper_arm path=Upper arm:1
[12:14:45]     child(occ1):  HR32906J_Inner_ring path=Roll Bearing 2:2+HR32906J Inner ring:1
[12:14:45]     geometryOrOriginOne: (11.2376, 1.5017, 21.5314) cm
[12:14:45]     geometryOrOriginTwo: (11.2376, 1.5017, 21.5314) cm
[12:14:45]     occ1.transform: (-19.9680, 2.7226, 0.8620) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (11.1341, 2.6973, 21.5314) cm
[12:14:45]     occ2.transform: (-1.9690, -0.4444, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-1.9690, -0.4444, 6.0400) cm
[12:14:45]  -> origin_global: (0.112376, 0.015017, 0.215314) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_20
[12:14:45]     parent(occ2): Base_Connector_Shaft_V2 path=Base Connector + Shaft V2:1
[12:14:45]     child(occ1):  Base_Motor path=Base Motor:1
[12:14:45]     geometryOrOriginOne: (5.8777, -11.2580, 0.7400) cm
[12:14:45]     geometryOrOriginTwo: (5.8777, -11.2580, 0.7400) cm
[12:14:45]     occ1.transform: (5.8777, -11.2580, 6.7400) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (5.8777, -11.2580, 6.7400) cm
[12:14:45]     occ2.transform: (7.4721, 0.6468, 2.5400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (7.4721, 0.6468, 2.5400) cm
[12:14:45]  -> origin_global: (0.058777, -0.112580, 0.007400) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_21
[12:14:45]     parent(occ2): Motor_Connector_Shoulder path=Motor Connector Shoulder:1
[12:14:45]     child(occ1):  EG17_shaft_2 path=EG17-G50:1+EG17 shaft-2:1
[12:14:45]     geometryOrOriginOne: (-2.3398, 3.8396, 6.0400) cm
[12:14:45]     geometryOrOriginTwo: (-2.3398, 3.8396, 6.0400) cm
[12:14:45]     occ1.transform: (-0.2088, 0.2647, 4.1250) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (-2.4261, 4.8359, 6.0400) cm
[12:14:45]     occ2.transform: (-2.2708, 3.0426, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-2.2708, 3.0426, 6.0400) cm
[12:14:45]  -> origin_global: (-0.023398, 0.038396, 0.060400) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_22
[12:14:45]     parent(occ2): nema17input_flange path=EG17-G50:1+nema17input flange:1
[12:14:45]     child(occ1):  Shoulder_Motor path=Shoulder Motor:1
[12:14:45]     geometryOrOriginOne: (-2.9133, 10.4648, 6.0400) cm
[12:14:45]     geometryOrOriginTwo: (-2.9133, 10.4648, 6.0400) cm
[12:14:45]     occ1.transform: (-3.4307, 16.4425, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-3.4307, 16.4425, 6.0400) cm
[12:14:45]     occ2.transform: (-0.2088, 0.2647, 0.4750) cm (ctx_depth=1)
[12:14:45]     occ2.global:    (-2.7408, 8.4723, 6.0400) cm
[12:14:45]  -> origin_global: (-0.029133, 0.104648, 0.060400) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_23
[12:14:45]     parent(occ2): Upper_arm path=Upper arm:1
[12:14:45]     child(occ1):  EG17_shaft path=EG17-G10:1+EG17 shaft:1
[12:14:45]     geometryOrOriginOne: (5.6566, -7.5131, 13.5897) cm
[12:14:45]     geometryOrOriginTwo: (5.6566, -7.5131, 13.5897) cm
[12:14:45]     occ1.transform: (-0.2088, 0.2647, 4.1250) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (5.5703, -6.5168, 13.5897) cm
[12:14:45]     occ2.transform: (-1.9690, -0.4444, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-1.9690, -0.4444, 6.0400) cm
[12:14:45]  -> origin_global: (0.056566, -0.075131, 0.135897) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_24
[12:14:45]     parent(occ2): nema17input_flange_1 path=EG17-G10:1+nema17input flange (1):1
[12:14:45]     child(occ1):  UA_Motor path=UA Motor:1
[12:14:45]     geometryOrOriginOne: (5.1780, -1.9838, 13.5897) cm
[12:14:45]     geometryOrOriginTwo: (5.1780, -1.9838, 13.5897) cm
[12:14:45]     occ1.transform: (5.1780, -1.9838, 13.5897) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (5.1780, -1.9838, 13.5897) cm
[12:14:45]     occ2.transform: (-0.2088, 0.2647, 1.5750) cm (ctx_depth=1)
[12:14:45]     occ2.global:    (5.3504, -3.9763, 13.5897) cm
[12:14:45]  -> origin_global: (0.051780, -0.019838, 0.135897) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_25
[12:14:45]     parent(occ2): HR32906J_Inner_ring path=Roll Bearing 2:2+HR32906J Inner ring:1
[12:14:45]     child(occ1):  Elbow_Connector_Passive path=Elbow Connector Passive:1
[12:14:45]     geometryOrOriginOne: (11.1341, 2.6973, 21.5314) cm
[12:14:45]     geometryOrOriginTwo: (11.1341, 2.6973, 21.5314) cm
[12:14:45]     occ1.transform: (11.1341, 2.6973, 21.5314) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (11.1341, 2.6973, 21.5314) cm
[12:14:45]     occ2.transform: (-19.9680, 2.7226, 0.8620) cm (ctx_depth=1)
[12:14:45]     occ2.global:    (11.1341, 2.6973, 21.5314) cm
[12:14:45]  -> origin_global: (0.111341, 0.026973, 0.215314) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_26
[12:14:45]     parent(occ2): HR32906J_Inner_ring path=Roll Bearing 2:1+HR32906J Inner ring:1
[12:14:45]     child(occ1):  Component52 path=GT2 Elbow Connector:1+Component52:1
[12:14:45]     geometryOrOriginOne: (12.1430, -8.9591, 21.5314) cm
[12:14:45]     geometryOrOriginTwo: (12.1430, -8.9591, 21.5314) cm
[12:14:45]     occ1.transform: (1.2160, -2.2339, 10.2417) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (12.2551, -10.2543, 21.5314) cm
[12:14:45]     occ2.transform: (-17.4175, -3.9359, 4.6736) cm (ctx_depth=1)
[12:14:45]     occ2.global:    (12.1430, -8.9591, 21.5314) cm
[12:14:45]  -> origin_global: (0.121430, -0.089591, 0.215314) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_27
[12:14:45]     parent(occ2): Upper_arm path=Upper arm:1
[12:14:45]     child(occ1):  Component54 path=GT2 400mm Motor Connector:1+Component54:1
[12:14:45]     geometryOrOriginOne: (5.8290, -9.5057, 13.5897) cm
[12:14:45]     geometryOrOriginTwo: (5.8290, -9.5057, 13.5897) cm
[12:14:45]     occ1.transform: (19.6298, -2.9961, 3.5361) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (5.9153, -10.5019, 13.5897) cm
[12:14:45]     occ2.transform: (-1.9690, -0.4444, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-1.9690, -0.4444, 6.0400) cm
[12:14:45]  -> origin_global: (0.058290, -0.095057, 0.135897) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_28
[12:14:45]     parent(occ2): Component54 path=GT2 400mm Motor Connector:1+Component54:1
[12:14:45]     child(occ1):  Connector_1 path=UA Shaft Coupler:1+Connector (1):1
[12:14:45]     geometryOrOriginOne: (5.8290, -9.5057, 13.5897) cm
[12:14:45]     geometryOrOriginTwo: (5.8290, -9.5057, 13.5897) cm
[12:14:45]     occ1.transform: (11.1366, -8.3918, 6.9752) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (5.8290, -9.5057, 13.5897) cm
[12:14:45]     occ2.transform: (19.6298, -2.9961, 3.5361) cm (ctx_depth=1)
[12:14:45]     occ2.global:    (5.9153, -10.5019, 13.5897) cm
[12:14:45]  -> origin_global: (0.058290, -0.095057, 0.135897) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Revolute_29
[12:14:45]     parent(occ2): Elbow_Connector_Passive path=Elbow Connector Passive:1
[12:14:45]     child(occ1):  Elbow_Belt_Sensorless path=Elbow Belt Sensorless:1
[12:14:45]     geometryOrOriginOne: (11.3497, 0.2066, 21.5314) cm
[12:14:45]     geometryOrOriginTwo: (11.3497, 0.2066, 21.5314) cm
[12:14:45]     occ1.transform: (7.4382, -3.4945, 28.7390) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (7.4382, -3.4945, 28.7390) cm
[12:14:45]     occ2.transform: (11.1341, 2.6973, 21.5314) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (11.1341, 2.6973, 21.5314) cm
[12:14:45]  -> origin_global: (0.113497, 0.002066, 0.215314) m [via geometryOrOriginOne]
[12:14:45]     motion: revolute, axis: (0.086, -0.996, 0.000)
[12:14:45]     rotation limits: [0.0000, 6.2832] rad
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_30
[12:14:45]     parent(occ2): Elbow_Belt_Sensorless path=Elbow Belt Sensorless:1
[12:14:45]     child(occ1):  Elbow_Motor path=Elbow Motor:1
[12:14:45]     geometryOrOriginOne: (9.3689, -3.3274, 19.9984) cm
[12:14:45]     geometryOrOriginTwo: (9.3689, -3.3274, 19.9984) cm
[12:14:45]     occ1.transform: (9.3689, -3.3274, 19.9984) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (9.3689, -3.3274, 19.9984) cm
[12:14:45]     occ2.transform: (7.4382, -3.4945, 28.7390) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (7.4382, -3.4945, 28.7390) cm
[12:14:45]  -> origin_global: (0.093689, -0.033274, 0.199984) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_31
[12:14:45]     parent(occ2): Elbow_Belt_Sensorless path=Elbow Belt Sensorless:1
[12:14:45]     child(occ1):  HR32906J_Outer_ring path=Roll Bearing 2:3+HR32906J Outer ring:1
[12:14:45]     geometryOrOriginOne: (6.2591, -3.5966, 28.2257) cm
[12:14:45]     geometryOrOriginTwo: (6.2591, -3.5966, 28.2257) cm
[12:14:45]     occ1.transform: (1.9321, -13.2700, 11.5647) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (5.1623, -3.6915, 27.7482) cm
[12:14:45]     occ2.transform: (7.4382, -3.4945, 28.7390) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (7.4382, -3.4945, 28.7390) cm
[12:14:45]  -> origin_global: (0.062591, -0.035966, 0.282257) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_32
[12:14:45]     parent(occ2): Elbow_Belt_Sensorless path=Elbow Belt Sensorless:1
[12:14:45]     child(occ1):  HR32906J_Inner_ring path=Roll Bearing 2:3+HR32906J Inner ring:1
[12:14:45]     geometryOrOriginOne: (6.2591, -3.5966, 28.2257) cm
[12:14:45]     geometryOrOriginTwo: (6.2591, -3.5966, 28.2257) cm
[12:14:45]     occ1.transform: (1.9321, -13.2700, 11.5647) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (5.1623, -3.6915, 27.7482) cm
[12:14:45]     occ2.transform: (7.4382, -3.4945, 28.7390) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (7.4382, -3.4945, 28.7390) cm
[12:14:45]  -> origin_global: (0.062591, -0.035966, 0.282257) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_33
[12:14:45]     parent(occ2): Elbow_Belt_Sensorless path=Elbow Belt Sensorless:1
[12:14:45]     child(occ1):  HR32906J_Outer_ring path=Roll Bearing 2:4+HR32906J Outer ring:1
[12:14:45]     geometryOrOriginOne: (8.6173, -3.3924, 29.2523) cm
[12:14:45]     geometryOrOriginTwo: (8.6173, -3.3924, 29.2523) cm
[12:14:45]     occ1.transform: (17.5460, -8.1187, 2.5209) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (9.7141, -3.2975, 29.7298) cm
[12:14:45]     occ2.transform: (7.4382, -3.4945, 28.7390) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (7.4382, -3.4945, 28.7390) cm
[12:14:45]  -> origin_global: (0.086173, -0.033924, 0.292523) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_34
[12:14:45]     parent(occ2): Elbow_Belt_Sensorless path=Elbow Belt Sensorless:1
[12:14:45]     child(occ1):  HR32906J_Inner_ring path=Roll Bearing 2:4+HR32906J Inner ring:1
[12:14:45]     geometryOrOriginOne: (8.6173, -3.3924, 29.2523) cm
[12:14:45]     geometryOrOriginTwo: (8.6173, -3.3924, 29.2523) cm
[12:14:45]     occ1.transform: (17.5460, -8.1187, 2.5209) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (9.7141, -3.2975, 29.7298) cm
[12:14:45]     occ2.transform: (7.4382, -3.4945, 28.7390) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (7.4382, -3.4945, 28.7390) cm
[12:14:45]  -> origin_global: (0.086173, -0.033924, 0.292523) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_35
[12:14:45]     parent(occ2): HR32906J_Inner_ring path=Roll Bearing 2:3+HR32906J Inner ring:1
[12:14:45]     child(occ1):  Component58 path=Shaft Connector:1+Component58:1
[12:14:45]     geometryOrOriginOne: (5.1623, -3.6915, 27.7482) cm
[12:14:45]     geometryOrOriginTwo: (5.1623, -3.6915, 27.7482) cm
[12:14:45]     occ1.transform: (6.7809, -17.0134, 20.0085) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (5.1623, -3.6915, 27.7482) cm
[12:14:45]     occ2.transform: (1.9321, -13.2700, 11.5647) cm (ctx_depth=1)
[12:14:45]     occ2.global:    (5.1623, -3.6915, 27.7482) cm
[12:14:45]  -> origin_global: (0.051623, -0.036915, 0.277482) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_36
[12:14:45]     parent(occ2): Component58 path=Shaft Connector:1+Component58:1
[12:14:45]     child(occ1):  Elbow_Cap path=Elbow Cap:1
[12:14:45]     geometryOrOriginOne: (9.7324, -3.2959, 29.7377) cm
[12:14:45]     geometryOrOriginTwo: (9.7324, -3.2959, 29.7377) cm
[12:14:45]     occ1.transform: (10.0980, -3.2643, 29.8969) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (10.0980, -3.2643, 29.8969) cm
[12:14:45]     occ2.transform: (6.7809, -17.0134, 20.0085) cm (ctx_depth=1)
[12:14:45]     occ2.global:    (5.1623, -3.6915, 27.7482) cm
[12:14:45]  -> origin_global: (0.097324, -0.032959, 0.297377) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Revolute_37
[12:14:45]     parent(occ2): Component58 path=Shaft Connector:1+Component58:1
[12:14:45]     child(occ1):  Motor_Housing_Roll path=Motor Housing Roll:1
[12:14:45]     geometryOrOriginOne: (4.1569, -3.7785, 27.3105) cm
[12:14:45]     geometryOrOriginTwo: (4.1569, -3.7785, 27.3105) cm
[12:14:45]     occ1.transform: (4.1569, -3.7785, 27.3105) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (4.1569, -3.7785, 27.3105) cm
[12:14:45]     occ2.transform: (6.7809, -17.0134, 20.0085) cm (ctx_depth=1)
[12:14:45]     occ2.global:    (5.1623, -3.6915, 27.7482) cm
[12:14:45]  -> origin_global: (0.041569, -0.037785, 0.273105) m [via geometryOrOriginOne]
[12:14:45]     motion: revolute, axis: (-0.914, -0.079, -0.398)
[12:14:45]     rotation limits: [0.0000, 6.2832] rad
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_38
[12:14:45]     parent(occ2): Motor_Housing_Roll path=Motor Housing Roll:1
[12:14:45]     child(occ1):  Roll_Motor path=Roll Motor:1
[12:14:45]     geometryOrOriginOne: (0.8721, -0.2018, 25.8513) cm
[12:14:45]     geometryOrOriginTwo: (0.8721, -0.2018, 25.8513) cm
[12:14:45]     occ1.transform: (0.8721, -0.2018, 25.8513) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (0.8721, -0.2018, 25.8513) cm
[12:14:45]     occ2.transform: (4.1569, -3.7785, 27.3105) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (4.1569, -3.7785, 27.3105) cm
[12:14:45]  -> origin_global: (0.008721, -0.002018, 0.258513) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_39
[12:14:45]     parent(occ2): Motor_Housing_Roll path=Motor Housing Roll:1
[12:14:45]     child(occ1):  HR32906J_Outer_ring path=Roll Bearing 2:5+HR32906J Outer ring:1
[12:14:45]     geometryOrOriginOne: (-6.6689, -8.0752, 22.6231) cm
[12:14:45]     geometryOrOriginTwo: (-6.6689, -8.0752, 22.6231) cm
[12:14:45]     occ1.transform: (-9.0522, 14.9792, 8.6004) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (-6.5852, -9.2714, 22.6686) cm
[12:14:45]     occ2.transform: (4.1569, -3.7785, 27.3105) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (4.1569, -3.7785, 27.3105) cm
[12:14:45]  -> origin_global: (-0.066689, -0.080752, 0.226231) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_40
[12:14:45]     parent(occ2): Motor_Housing_Roll path=Motor Housing Roll:1
[12:14:45]     child(occ1):  HR32906J_Outer_ring path=Roll Bearing 2:6+HR32906J Outer ring:1
[12:14:45]     geometryOrOriginOne: (-7.1363, -1.3964, 22.3688) cm
[12:14:45]     geometryOrOriginTwo: (-7.1363, -1.3964, 22.3688) cm
[12:14:45]     occ1.transform: (-13.3560, 29.4910, 7.3869) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (-7.2200, -0.2002, 22.3232) cm
[12:14:45]     occ2.transform: (4.1569, -3.7785, 27.3105) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (4.1569, -3.7785, 27.3105) cm
[12:14:45]  -> origin_global: (-0.071363, -0.013964, 0.223688) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_41
[12:14:45]     parent(occ2): HR32906J_Inner_ring path=Roll Bearing 2:5+HR32906J Inner ring:1
[12:14:45]     child(occ1):  Passive_Cap path=Passive Cap:1
[12:14:45]     geometryOrOriginOne: (-6.5852, -9.2714, 22.6686) cm
[12:14:45]     geometryOrOriginTwo: (-6.5852, -9.2714, 22.6686) cm
[12:14:45]     occ1.transform: (-6.7108, -7.4771, 22.6003) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-6.7108, -7.4771, 22.6003) cm
[12:14:45]     occ2.transform: (-9.0522, 14.9792, 8.6004) cm (ctx_depth=1)
[12:14:45]     occ2.global:    (-6.5852, -9.2714, 22.6686) cm
[12:14:45]  -> origin_global: (-0.065852, -0.092714, 0.226686) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_42
[12:14:45]     parent(occ2): HR32906J_Inner_ring path=Roll Bearing 2:6+HR32906J Inner ring:1
[12:14:45]     child(occ1):  Component64 path=Belt Shaft:1+Component64:1
[12:14:45]     geometryOrOriginOne: (-7.2200, -0.2002, 22.3232) cm
[12:14:45]     geometryOrOriginTwo: (-7.2200, -0.2002, 22.3232) cm
[12:14:45]     occ1.transform: (0.0000, 0.0000, 0.0000) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (-7.3037, 0.9960, 22.2777) cm
[12:14:45]     occ2.transform: (-13.3560, 29.4910, 7.3869) cm (ctx_depth=1)
[12:14:45]     occ2.global:    (-7.2200, -0.2002, 22.3232) cm
[12:14:45]  -> origin_global: (-0.072200, -0.002002, 0.223232) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Revolute_43
[12:14:45]     parent(occ2): Passive_Cap path=Passive Cap:1
[12:14:45]     child(occ1):  Motor_Housing_Yaw path=Motor Housing Yaw:1
[12:14:45]     geometryOrOriginOne: (-6.7108, -7.4771, 22.6003) cm
[12:14:45]     geometryOrOriginTwo: (-6.7108, -7.4771, 22.6003) cm
[12:14:45]     occ1.transform: (-9.7266, -4.8455, 24.8058) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-9.7266, -4.8455, 24.8058) cm
[12:14:45]     occ2.transform: (-6.7108, -7.4771, 22.6003) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-6.7108, -7.4771, 22.6003) cm
[12:14:45]  -> origin_global: (-0.067108, -0.074771, 0.226003) m [via geometryOrOriginOne]
[12:14:45]     motion: revolute, axis: (-0.070, 0.997, -0.038)
[12:14:45]     rotation limits: [0.0000, 6.2832] rad
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_44
[12:14:45]     parent(occ2): Motor_Housing_Yaw path=Motor Housing Yaw:1
[12:14:45]     child(occ1):  HR32906J_Outer_ring path=Roll Bearing 2:7+HR32906J Outer ring:1
[12:14:45]     geometryOrOriginOne: (-10.3455, -4.8695, 25.3121) cm
[12:14:45]     geometryOrOriginTwo: (-10.3455, -4.8695, 25.3121) cm
[12:14:45]     occ1.transform: (-1.9669, 12.9914, 17.7007) cm (ctx_depth=1)
[12:14:45]     occ1.global:    (-11.2740, -4.9055, 26.0715) cm
[12:14:45]     occ2.transform: (-9.7266, -4.8455, 24.8058) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-9.7266, -4.8455, 24.8058) cm
[12:14:45]  -> origin_global: (-0.103455, -0.048695, 0.253121) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_45
[12:14:45]     parent(occ2): Motor_Housing_Yaw path=Motor Housing Yaw:1
[12:14:45]     child(occ1):  Yaw_Motor path=Yaw Motor:1
[12:14:45]     geometryOrOriginOne: (-8.0631, -4.7809, 23.4452) cm
[12:14:45]     geometryOrOriginTwo: (-8.0631, -4.7809, 23.4452) cm
[12:14:45]     occ1.transform: (-6.4771, -4.7193, 22.1479) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-6.4771, -4.7193, 22.1479) cm
[12:14:45]     occ2.transform: (-9.7266, -4.8455, 24.8058) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-9.7266, -4.8455, 24.8058) cm
[12:14:45]  -> origin_global: (-0.080631, -0.047809, 0.234452) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Revolute_46
[12:14:45]     parent(occ2): HR32906J_Inner_ring path=Roll Bearing 2:7+HR32906J Inner ring:1
[12:14:45]     child(occ1):  Gripper_Shaft path=Gripper Shaft:1
[12:14:45]     geometryOrOriginOne: (-11.2740, -4.9055, 26.0715) cm
[12:14:45]     geometryOrOriginTwo: (-11.2740, -4.9055, 26.0715) cm
[12:14:45]     occ1.transform: (-9.8040, -4.8485, 24.8691) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-9.8040, -4.8485, 24.8691) cm
[12:14:45]     occ2.transform: (-1.9669, 12.9914, 17.7007) cm (ctx_depth=1)
[12:14:45]     occ2.global:    (-11.2740, -4.9055, 26.0715) cm
[12:14:45]  -> origin_global: (-0.112740, -0.049055, 0.260715) m [via geometryOrOriginOne]
[12:14:45]     motion: revolute, axis: (-0.774, -0.030, 0.633)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_54
[12:14:45]     parent(occ2): Shoulder_Cap path=Shoulder Cap:2
[12:14:45]     child(occ1):  ua path=!frame_ua:1
[12:14:45]     geometryOrOriginOne: (-0.7100, -14.9900, 6.0400) cm
[12:14:45]     geometryOrOriginTwo: (-0.7100, -14.9900, 6.0400) cm
[12:14:45]     occ1.transform: (-0.7100, -14.9900, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-0.7100, -14.9900, 6.0400) cm
[12:14:45]     occ2.transform: (-0.7531, -14.4918, 6.0400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-0.7531, -14.4918, 6.0400) cm
[12:14:45]  -> origin_global: (-0.007100, -0.149900, 0.060400) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_55
[12:14:45]     parent(occ2): Component52 path=GT2 Elbow Connector:1+Component52:1
[12:14:45]     child(occ1):  elbow path=!frame_elbow:1
[12:14:45]     geometryOrOriginOne: (12.2551, -10.2543, 21.5314) cm
[12:14:45]     geometryOrOriginTwo: (12.2551, -10.2543, 21.5314) cm
[12:14:45]     occ1.transform: (12.2551, -10.2543, 21.5314) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (12.2551, -10.2543, 21.5314) cm
[12:14:45]     occ2.transform: (1.2160, -2.2339, 10.2417) cm (ctx_depth=1)
[12:14:45]     occ2.global:    (12.2551, -10.2543, 21.5314) cm
[12:14:45]  -> origin_global: (0.122551, -0.102543, 0.215314) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_56
[12:14:45]     parent(occ2): Elbow_Cap path=Elbow Cap:1
[12:14:45]     child(occ1):  roll path=!frame_roll:1
[12:14:45]     geometryOrOriginOne: (10.0980, -3.2643, 29.8969) cm
[12:14:45]     geometryOrOriginTwo: (10.0980, -3.2643, 29.8969) cm
[12:14:45]     occ1.transform: (10.0980, -3.2643, 29.8969) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (10.0980, -3.2643, 29.8969) cm
[12:14:45]     occ2.transform: (10.0980, -3.2643, 29.8969) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (10.0980, -3.2643, 29.8969) cm
[12:14:45]  -> origin_global: (0.100980, -0.032643, 0.298969) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_57
[12:14:45]     parent(occ2): Passive_Cap path=Passive Cap:1
[12:14:45]     child(occ1):  yaw path=!frame_yaw:1
[12:14:45]     geometryOrOriginOne: (-6.5503, -9.7698, 22.6876) cm
[12:14:45]     geometryOrOriginTwo: (-6.5503, -9.7698, 22.6876) cm
[12:14:45]     occ1.transform: (-6.5503, -9.7698, 22.6876) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-6.5503, -9.7698, 22.6876) cm
[12:14:45]     occ2.transform: (-6.7108, -7.4771, 22.6003) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-6.7108, -7.4771, 22.6003) cm
[12:14:45]  -> origin_global: (-0.065503, -0.097698, 0.226876) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_58
[12:14:45]     parent(occ2): Gripper_Shaft path=Gripper Shaft:1
[12:14:45]     child(occ1):  gripper path=!frame_gripper:1
[12:14:45]     geometryOrOriginOne: (-12.4345, -4.9506, 27.0208) cm
[12:14:45]     geometryOrOriginTwo: (-12.4345, -4.9506, 27.0208) cm
[12:14:45]     occ1.transform: (-12.4345, -4.9506, 27.0208) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (-12.4345, -4.9506, 27.0208) cm
[12:14:45]     occ2.transform: (-9.8040, -4.8485, 24.8691) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (-9.8040, -4.8485, 24.8691) cm
[12:14:45]  -> origin_global: (-0.124345, -0.049506, 0.270208) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   regular joint in component '6DOF URDF': failed to read geometry: 'Joint' object has no attribute 'geometry'
[12:14:45]   [REGULAR in 6DOF_URDF] Rigid_59
[12:14:45]     parent(occ2): Base_Connector_Shaft_V2 path=Base Connector + Shaft V2:1
[12:14:45]     child(occ1):  shoulder path=!frame_shoulder:1
[12:14:45]     geometryOrOriginOne: (0.0000, 0.0000, -5.1500) cm
[12:14:45]     geometryOrOriginTwo: (0.0000, 0.0000, -5.1500) cm
[12:14:45]     occ1.transform: (0.0000, 0.0000, -5.1500) cm (ctx_depth=0)
[12:14:45]     occ1.global:    (0.0000, 0.0000, -5.1500) cm
[12:14:45]     occ2.transform: (7.4721, 0.6468, 2.5400) cm (ctx_depth=0)
[12:14:45]     occ2.global:    (7.4721, 0.6468, 2.5400) cm
[12:14:45]  -> origin_global: (0.000000, 0.000000, -0.051500) m [via geometryOrOriginOne]
[12:14:45]     motion: rigid, axis: (0.000, 0.000, 1.000)
[12:14:45]   WARNING:   Skipping regular joint in component 'Base Connector + Shaft V2' 'Rigid 1': missing/unreadable endpoint (occurrenceOne=False, occurrenceTwo=True)
[12:14:45]   WARNING:   Skipping regular joint in component 'Base Connector + Shaft V2' 'Rigid 2': missing/unreadable endpoint (occurrenceOne=False, occurrenceTwo=True)
[12:14:45]   Extracted 51 unique joints
[12:14:45]   WARNING:   Skipped 2 joint(s) that Fusion reported as invalid or unreadable
[12:14:45] 
=== EXTRACTION: RIGID GROUPS ===
[12:14:45]   Base: ['base_link', 'Shoulder_Bearing_2_Upper', 'Shoulder_Bearing_2_Lower', 'Lower_Upper_Base_Bearing_Ring', 'Lower_Bottom_Base_Bearing_Ring']
[12:14:45]   Shoulder: ['Base_Connector_Shaft_V2', 'Motor_Connector_Shoulder', 'Bearing_Housing_Shoulder_V2', 'Shoulder_Bearing_2_Upper', 'Shoulder_Bearing_2_Lower', 'Shoulder_Bearing_2_Upper', 'Shoulder_Bearing_2_Lower', 'Base_Motor', 'EG17_shaft_2', 'nema17input_flange', 'input_shaft', '10circlip', 'M3hexagon_socket_head_cap_screw', '6801', 'M3hexagon_socket_head_cap_screw', 'M3hexagon_socket_head_cap_screw', 'M3hexagon_socket_head_cap_screw', 'M3hexagon_socket_head_cap_screw', 'M3hexagon_socket_head_cap_screw', 'M3hexagon_socket_head_cap_screw', 'M3hexagon_socket_head_cap_screw', 'Shoulder_Motor', 'shoulder'] (expanded 24→23)
[12:14:45]   UA: ['Upper_arm', 'Shoulder_Cap', '92605A009', 'Connector', '92605A009', 'HR32906J_Inner_ring', 'HR32906J_Outer_ring', 'HR32906J_Inner_ring', 'HR32906J_Outer_ring', 'EG17_shaft', 'nema17input_flange_1', 'input_shaft_1', '10circlip_1', 'M3hexagon_socket_head_cap_screw_1', '6801_1', 'M3hexagon_socket_head_cap_screw_1', 'M3hexagon_socket_head_cap_screw_1', 'M3hexagon_socket_head_cap_screw_1', 'M3hexagon_socket_head_cap_screw_1', 'M3hexagon_socket_head_cap_screw_1', 'M3hexagon_socket_head_cap_screw_1', 'M3hexagon_socket_head_cap_screw_1', 'UA_Motor', '92605A009_1', 'Connector_1', '92605A009_1', 'Component54', 'ua', 'Elbow_Connector_Passive', 'Component52'] (expanded 32→30)
[12:14:45]   Elbow: ['Elbow_Belt_Sensorless', 'Elbow_Motor', 'HR32906J_Inner_ring', 'HR32906J_Outer_ring', 'HR32906J_Inner_ring', 'HR32906J_Outer_ring', 'elbow', 'Component52', 'Component58', 'Elbow_Cap'] (expanded 12→10)
[12:14:45]   Gripper: ['gripper', 'Gripper_Shaft']
[12:14:45]   Roll: ['Motor_Housing_Roll', 'Roll_Motor', 'Passive_Cap', 'HR32906J_Inner_ring', 'HR32906J_Outer_ring', 'HR32906J_Inner_ring', 'HR32906J_Outer_ring', 'Component64', 'roll'] (expanded 12→9)
[12:14:45]   Yaw: ['yaw', 'Yaw_Motor', 'HR32906J_Inner_ring', 'HR32906J_Outer_ring', 'Motor_Housing_Yaw'] (expanded 6→5)
[12:14:45]   Rigid Group 1: ['HR32906J_Inner_ring', 'HR32906J_Outer_ring']
[12:14:45]   Rigid Group 1: ['HR32906J_Inner_ring', 'HR32906J_Outer_ring']
[12:14:45]   Rigid Group 1: ['EG17_shaft_2', 'nema17input_flange', 'input_shaft', '10circlip', 'M3hexagon_socket_head_cap_screw', '6801', 'M3hexagon_socket_head_cap_screw', 'M3hexagon_socket_head_cap_screw', 'M3hexagon_socket_head_cap_screw', 'M3hexagon_socket_head_cap_screw', 'M3hexagon_socket_head_cap_screw', 'M3hexagon_socket_head_cap_screw', 'M3hexagon_socket_head_cap_screw'] (expanded 14→13)
[12:14:45]   Rigid Group 1: ['EG17_shaft', 'nema17input_flange_1', 'input_shaft_1', '10circlip_1', 'M3hexagon_socket_head_cap_screw_1', '6801_1', 'M3hexagon_socket_head_cap_screw_1', 'M3hexagon_socket_head_cap_screw_1', 'M3hexagon_socket_head_cap_screw_1', 'M3hexagon_socket_head_cap_screw_1', 'M3hexagon_socket_head_cap_screw_1', 'M3hexagon_socket_head_cap_screw_1', 'M3hexagon_socket_head_cap_screw_1'] (expanded 14→13)
[12:14:45]   Rigid Group 1: ['HR32906J_Inner_ring', 'HR32906J_Outer_ring']
[12:14:45]   Rigid Group 1: ['HR32906J_Inner_ring', 'HR32906J_Outer_ring']
[12:14:45]   Rigid Group 1: ['HR32906J_Inner_ring', 'HR32906J_Outer_ring']
[12:14:45]   Rigid Group 1: ['HR32906J_Inner_ring', 'HR32906J_Outer_ring']
[12:14:45]   Rigid Group 1: ['HR32906J_Inner_ring', 'HR32906J_Outer_ring']
[12:14:45]   Extracted 16 rigid groups
[12:14:45] 
=== EXTRACTION SUMMARY ===
[12:14:45]   Occurrences: 98 (15 subassemblies, 83 leaf components)
[12:14:45]   Joints: 51 (0 as-built, 51 regular)
[12:14:45]   Max nesting depth: 1
[12:14:55]   Loaded config: C:\Users\wange\Documents\fusion2URDF\xacro_export.toml
[12:14:55]     config: verbosity=verbose: all optional outputs ON
[12:14:55]     config: include_debug = True
[12:14:55]     config: include_docs = True
[12:14:55]     config: include_robot_data_yaml = True
[12:14:55]     config: include_screenshot = True
[12:14:55]     config: include_launch = True
[12:14:55]     config: include_rviz = True
[12:14:55]     config: include_readme = True
[12:14:55]     config: include_ros2_control = True
[12:14:55]     config: zip_output = False
[12:14:55]     config: visual_format = dae
[12:14:55]     config: collision_method = convex_hull
[12:14:55]     config: mesh_refinement = medium
[12:14:55]     config: frames.convention = ros
[12:14:55]     config: frames.overrides_file = frame_overrides.csv
[12:14:55]     config: ros2_control.hardware_plugin = mock_components/GenericSystem
[12:14:55]     config: ros2_control.update_rate = 100
[12:14:55]     config: ros2_control.command_interfaces = position,velocity
[12:14:55] 
=== PHASE 1: DEBUG DATA ===
[12:14:55]   extraction_report.md
[12:14:55]   snapshot.json
[12:14:55]   fusion_transforms.json
[12:14:55] 
=== PHASE 2: BUILD ROBOT MODEL ===
[12:14:55] 
=== MODEL: ASSEMBLY HIERARCHY ===
[12:14:55]   Assembly: UA_Shaft_COupler d=0 offset=(88.0, -221.1, -12.7) mm
[12:14:55]   Assembly: Roll_Bearing_2 d=0 offset=(-48.7, -143.8, 168.6) mm
[12:14:55]   Assembly: Roll_Bearing_2 d=0 offset=(-89.9, 36.9, 206.7) mm
[12:14:55]   Assembly: EG17_G50 d=0 offset=(-29.9, 89.3, 63.0) mm
[12:14:55]   Assembly: EG17_G10 d=0 offset=(52.2, -24.1, 139.3) mm
[12:14:55]   Assembly: UA_Shaft_Coupler d=0 offset=(176.5, -169.1, 66.1) mm
[12:14:55]   Assembly: GT2_Elbow_Connector d=0 offset=(136.6, -123.7, 112.9) mm
[12:14:55]   Assembly: GT2_400mm_Motor_Connector d=0 offset=(257.3, -117.9, 100.5) mm
[12:14:55]   Assembly: Roll_Bearing_2 d=0 offset=(99.0, -166.0, 165.9) mm
[12:14:55]   Assembly: Roll_Bearing_2 d=0 offset=(280.7, -98.6, 298.1) mm
[12:14:55]   Assembly: Shaft_Connector d=0 offset=(162.4, -198.1, 89.5) mm
[12:14:55]   Assembly: Roll_Bearing_2 d=0 offset=(-179.5, -250.3, 243.4) mm
[12:14:55]   Assembly: Roll_Bearing_2 d=0 offset=(-201.7, -307.4, 209.2) mm
[12:14:55]   Assembly: Belt_Shaft d=0 offset=(-73.0, 10.0, 222.8) mm
[12:14:55]   Assembly: Roll_Bearing_2 d=0 offset=(66.0, -164.7, 317.8) mm
[12:14:55]   Assembly: 6DOF_URDF (synthetic root, wraps design-root leaves so phase 2 has a macro to xacro:include)
[12:14:55]   base_link → 6DOF_URDF
[12:14:55]   Shoulder_Bearing_2_Upper → 6DOF_URDF
[12:14:55]   Shoulder_Bearing_2_Lower → 6DOF_URDF
[12:14:55]   Lower_Upper_Base_Bearing_Ring → 6DOF_URDF
[12:14:55]   Lower_Bottom_Base_Bearing_Ring → 6DOF_URDF
[12:14:55]   Base_Connector_Shaft_V2 → Base_Connector
[12:14:55]   Motor_Connector_Shoulder → 6DOF_URDF
[12:14:55]   Bearing_Housing_Shoulder_V2 → 6DOF_URDF
[12:14:55]   Shoulder_Bearing_2_Upper → 6DOF_URDF
[12:14:55]   Shoulder_Bearing_2_Lower → 6DOF_URDF
[12:14:55]   Shoulder_Bearing_2_Upper → 6DOF_URDF
[12:14:55]   Shoulder_Bearing_2_Lower → 6DOF_URDF
[12:14:55]   Upper_arm → 6DOF_URDF
[12:14:55]   Shoulder_Cap → 6DOF_URDF
[12:14:55]   92605A009 → UA_Shaft_COupler
[12:14:55]   Connector → UA_Shaft_COupler
[12:14:55]   92605A009 → UA_Shaft_COupler
[12:14:55]   HR32906J_Inner_ring → Roll_Bearing_2
[12:14:55]   HR32906J_Outer_ring → Roll_Bearing_2
[12:14:55]   HR32906J_Inner_ring → Roll_Bearing_2
[12:14:55]   HR32906J_Outer_ring → Roll_Bearing_2
[12:14:55]   Base_Motor → 6DOF_URDF
[12:14:55]   EG17_shaft_2 → EG17_G50
[12:14:55]   nema17input_flange → EG17_G50
[12:14:55]   input_shaft → EG17_G50
[12:14:55]   10circlip → EG17_G50
[12:14:55]   M3hexagon_socket_head_cap_screw → EG17_G50
[12:14:55]   6801 → EG17_G50
[12:14:55]   M3hexagon_socket_head_cap_screw → EG17_G50
[12:14:55]   M3hexagon_socket_head_cap_screw → EG17_G50
[12:14:55]   M3hexagon_socket_head_cap_screw → EG17_G50
[12:14:55]   M3hexagon_socket_head_cap_screw → EG17_G50
[12:14:55]   M3hexagon_socket_head_cap_screw → EG17_G50
[12:14:55]   M3hexagon_socket_head_cap_screw → EG17_G50
[12:14:55]   M3hexagon_socket_head_cap_screw → EG17_G50
[12:14:55]   Shoulder_Motor → 6DOF_URDF
[12:14:55]   EG17_shaft → EG17_G10
[12:14:55]   nema17input_flange_1 → EG17_G10
[12:14:55]   input_shaft_1 → EG17_G10
[12:14:55]   10circlip_1 → EG17_G10
[12:14:55]   M3hexagon_socket_head_cap_screw_1 → EG17_G10
[12:14:55]   6801_1 → EG17_G10
[12:14:55]   M3hexagon_socket_head_cap_screw_1 → EG17_G10
[12:14:55]   M3hexagon_socket_head_cap_screw_1 → EG17_G10
[12:14:55]   M3hexagon_socket_head_cap_screw_1 → EG17_G10
[12:14:55]   M3hexagon_socket_head_cap_screw_1 → EG17_G10
[12:14:55]   M3hexagon_socket_head_cap_screw_1 → EG17_G10
[12:14:55]   M3hexagon_socket_head_cap_screw_1 → EG17_G10
[12:14:55]   M3hexagon_socket_head_cap_screw_1 → EG17_G10
[12:14:55]   UA_Motor → 6DOF_URDF
[12:14:55]   92605A009_1 → UA_Shaft_Coupler
[12:14:55]   Connector_1 → UA_Shaft_Coupler
[12:14:55]   92605A009_1 → UA_Shaft_Coupler
[12:14:55]   Elbow_Connector_Passive → 6DOF_URDF
[12:14:55]   Component52 → GT2_Elbow_Connector
[12:14:55]   Component54 → GT2_400mm_Motor_Connector
[12:14:55]   Elbow_Belt_Sensorless → 6DOF_URDF
[12:14:55]   Elbow_Motor → 6DOF_URDF
[12:14:55]   HR32906J_Inner_ring → Roll_Bearing_2
[12:14:55]   HR32906J_Outer_ring → Roll_Bearing_2
[12:14:55]   HR32906J_Inner_ring → Roll_Bearing_2
[12:14:55]   HR32906J_Outer_ring → Roll_Bearing_2
[12:14:55]   Component58 → Shaft_Connector
[12:14:55]   Elbow_Cap → 6DOF_URDF
[12:14:55]   Motor_Housing_Roll → 6DOF_URDF
[12:14:55]   Roll_Motor → 6DOF_URDF
[12:14:55]   Passive_Cap → 6DOF_URDF
[12:14:55]   HR32906J_Inner_ring → Roll_Bearing_2
[12:14:55]   HR32906J_Outer_ring → Roll_Bearing_2
[12:14:55]   HR32906J_Inner_ring → Roll_Bearing_2
[12:14:55]   HR32906J_Outer_ring → Roll_Bearing_2
[12:14:55]   Component64 → Belt_Shaft
[12:14:55]   Motor_Housing_Yaw → 6DOF_URDF
[12:14:55]   HR32906J_Inner_ring → Roll_Bearing_2
[12:14:55]   HR32906J_Outer_ring → Roll_Bearing_2
[12:14:55]   Yaw_Motor → 6DOF_URDF
[12:14:55]   Gripper_Shaft → 6DOF_URDF
[12:14:55]   ua → 6DOF_URDF
[12:14:55]   elbow → 6DOF_URDF
[12:14:55]   roll → 6DOF_URDF
[12:14:55]   yaw → 6DOF_URDF
[12:14:55]   gripper → 6DOF_URDF
[12:14:55]   shoulder → 6DOF_URDF
[12:14:55] 
=== MODEL: RIGID GROUP MERGE ===
[12:14:55]   Base: anchor=base_link merged_name=Base members=5 mass=596.69 g bbox=(175.0 × 175.0 × 71.0) mm
[12:14:55]   Base: dropped 6DOF_URDF/Shoulder_Bearing_2_Upper (Shoulder Bearing 2 Upper:1) -> 6DOF_URDF/base_link
[12:14:55]   Base: dropped 6DOF_URDF/Shoulder_Bearing_2_Lower (Shoulder Bearing 2 Lower:1) -> 6DOF_URDF/base_link
[12:14:55]   Base: dropped 6DOF_URDF/Lower_Upper_Base_Bearing_Ring (Lower Upper Base Bearing Ring:1) -> 6DOF_URDF/base_link
[12:14:55]   Base: dropped 6DOF_URDF/Lower_Bottom_Base_Bearing_Ring (Lower Bottom Base Bearing Ring:1) -> 6DOF_URDF/base_link
[12:14:55]   Shoulder: anchor=shoulder merged_name=Shoulder members=23 mass=2094.14 g bbox=(160.0 × 323.2 × 151.1) mm
[12:14:55]   Shoulder: dropped Base_Connector/Base_Connector_Shaft_V2 (Base Connector + Shaft V2:1) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped 6DOF_URDF/Motor_Connector_Shoulder (Motor Connector Shoulder:1) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped 6DOF_URDF/Bearing_Housing_Shoulder_V2 (Bearing Housing Shoulder V2:1) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped 6DOF_URDF/Shoulder_Bearing_2_Upper (Shoulder Bearing 2 Upper:2) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped 6DOF_URDF/Shoulder_Bearing_2_Lower (Shoulder Bearing 2 Lower:2) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped 6DOF_URDF/Shoulder_Bearing_2_Upper (Shoulder Bearing 2 Upper:3) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped 6DOF_URDF/Shoulder_Bearing_2_Lower (Shoulder Bearing 2 Lower:3) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped 6DOF_URDF/Base_Motor (Base Motor:1) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped EG17_G50/EG17_shaft_2 (EG17-G50:1+EG17 shaft-2:1) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped EG17_G50/nema17input_flange (EG17-G50:1+nema17input flange:1) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped EG17_G50/input_shaft (EG17-G50:1+input shaft:1) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped EG17_G50/10circlip (EG17-G50:1+¦µ10circlip:1) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped EG17_G50/M3hexagon_socket_head_cap_screw (EG17-G50:1+M3hexagon socket head cap screw:1) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped EG17_G50/6801 (EG17-G50:1+6801:1) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped EG17_G50/M3hexagon_socket_head_cap_screw (EG17-G50:1+M3hexagon socket head cap screw:2) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped EG17_G50/M3hexagon_socket_head_cap_screw (EG17-G50:1+M3hexagon socket head cap screw:3) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped EG17_G50/M3hexagon_socket_head_cap_screw (EG17-G50:1+M3hexagon socket head cap screw:4) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped EG17_G50/M3hexagon_socket_head_cap_screw (EG17-G50:1+M3hexagon socket head cap screw:5) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped EG17_G50/M3hexagon_socket_head_cap_screw (EG17-G50:1+M3hexagon socket head cap screw:6) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped EG17_G50/M3hexagon_socket_head_cap_screw (EG17-G50:1+M3hexagon socket head cap screw:7) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped EG17_G50/M3hexagon_socket_head_cap_screw (EG17-G50:1+M3hexagon socket head cap screw:8) -> 6DOF_URDF/shoulder
[12:14:55]   Shoulder: dropped 6DOF_URDF/Shoulder_Motor (Shoulder Motor:1) -> 6DOF_URDF/shoulder
[12:14:55]   UA: anchor=ua merged_name=UA members=30 mass=1236.31 g bbox=(161.4 × 266.9 × 266.2) mm
[12:14:55]   UA: dropped 6DOF_URDF/Upper_arm (Upper arm:1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped 6DOF_URDF/Shoulder_Cap (Shoulder Cap:2) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped UA_Shaft_COupler/92605A009 (UA Shaft COupler:1+92605A009:1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped UA_Shaft_COupler/Connector (UA Shaft COupler:1+Connector:1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped UA_Shaft_COupler/92605A009 (UA Shaft COupler:1+92605A009:2) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped Roll_Bearing_2/HR32906J_Inner_ring (Roll Bearing 2:1+HR32906J Inner ring:1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped Roll_Bearing_2/HR32906J_Outer_ring (Roll Bearing 2:1+HR32906J Outer ring:1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped Roll_Bearing_2/HR32906J_Inner_ring (Roll Bearing 2:2+HR32906J Inner ring:1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped Roll_Bearing_2/HR32906J_Outer_ring (Roll Bearing 2:2+HR32906J Outer ring:1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped EG17_G10/EG17_shaft (EG17-G10:1+EG17 shaft:1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped EG17_G10/nema17input_flange_1 (EG17-G10:1+nema17input flange (1):1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped EG17_G10/input_shaft_1 (EG17-G10:1+input shaft (1):1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped EG17_G10/10circlip_1 (EG17-G10:1+¦µ10circlip (1):1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped EG17_G10/M3hexagon_socket_head_cap_screw_1 (EG17-G10:1+M3hexagon socket head cap screw (1):1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped EG17_G10/6801_1 (EG17-G10:1+6801 (1):1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped EG17_G10/M3hexagon_socket_head_cap_screw_1 (EG17-G10:1+M3hexagon socket head cap screw (1):2) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped EG17_G10/M3hexagon_socket_head_cap_screw_1 (EG17-G10:1+M3hexagon socket head cap screw (1):3) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped EG17_G10/M3hexagon_socket_head_cap_screw_1 (EG17-G10:1+M3hexagon socket head cap screw (1):4) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped EG17_G10/M3hexagon_socket_head_cap_screw_1 (EG17-G10:1+M3hexagon socket head cap screw (1):5) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped EG17_G10/M3hexagon_socket_head_cap_screw_1 (EG17-G10:1+M3hexagon socket head cap screw (1):6) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped EG17_G10/M3hexagon_socket_head_cap_screw_1 (EG17-G10:1+M3hexagon socket head cap screw (1):7) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped EG17_G10/M3hexagon_socket_head_cap_screw_1 (EG17-G10:1+M3hexagon socket head cap screw (1):8) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped 6DOF_URDF/UA_Motor (UA Motor:1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped UA_Shaft_Coupler/92605A009_1 (UA Shaft Coupler:1+92605A009 (1):1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped UA_Shaft_Coupler/Connector_1 (UA Shaft Coupler:1+Connector (1):1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped UA_Shaft_Coupler/92605A009_1 (UA Shaft Coupler:1+92605A009 (1):2) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped GT2_400mm_Motor_Connector/Component54 (GT2 400mm Motor Connector:1+Component54:1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped 6DOF_URDF/Elbow_Connector_Passive (Elbow Connector Passive:1) -> 6DOF_URDF/ua
[12:14:55]   UA: dropped GT2_Elbow_Connector/Component52 (GT2 Elbow Connector:1+Component52:1) -> 6DOF_URDF/ua
[12:14:55]   Elbow: anchor=elbow merged_name=Elbow members=10 mass=733.48 g bbox=(168.6 × 148.7 × 105.0) mm
[12:14:55]   Elbow: dropped 6DOF_URDF/Elbow_Belt_Sensorless (Elbow Belt Sensorless:1) -> 6DOF_URDF/elbow
[12:14:55]   Elbow: dropped 6DOF_URDF/Elbow_Motor (Elbow Motor:1) -> 6DOF_URDF/elbow
[12:14:55]   Elbow: dropped Roll_Bearing_2/HR32906J_Inner_ring (Roll Bearing 2:3+HR32906J Inner ring:1) -> 6DOF_URDF/elbow
[12:14:55]   Elbow: dropped Roll_Bearing_2/HR32906J_Outer_ring (Roll Bearing 2:3+HR32906J Outer ring:1) -> 6DOF_URDF/elbow
[12:14:55]   Elbow: dropped Roll_Bearing_2/HR32906J_Inner_ring (Roll Bearing 2:4+HR32906J Inner ring:1) -> 6DOF_URDF/elbow
[12:14:55]   Elbow: dropped Roll_Bearing_2/HR32906J_Outer_ring (Roll Bearing 2:4+HR32906J Outer ring:1) -> 6DOF_URDF/elbow
[12:14:55]   Elbow: dropped Shaft_Connector/Component58 (Shaft Connector:1+Component58:1) -> 6DOF_URDF/elbow
[12:14:55]   Elbow: dropped 6DOF_URDF/Elbow_Cap (Elbow Cap:1) -> 6DOF_URDF/elbow
[12:14:55]   Gripper: anchor=gripper merged_name=Gripper members=2 mass=11.20 g bbox=(40.0 × 40.0 × 34.0) mm
[12:14:55]   Gripper: dropped 6DOF_URDF/Gripper_Shaft (Gripper Shaft:1) -> 6DOF_URDF/gripper
[12:14:55]   Roll: anchor=roll merged_name=Roll members=9 mass=682.37 g bbox=(68.6 × 114.5 × 164.0) mm
[12:14:55]   Roll: dropped 6DOF_URDF/Motor_Housing_Roll (Motor Housing Roll:1) -> 6DOF_URDF/roll
[12:14:55]   Roll: dropped 6DOF_URDF/Roll_Motor (Roll Motor:1) -> 6DOF_URDF/roll
[12:14:55]   Roll: dropped 6DOF_URDF/Passive_Cap (Passive Cap:1) -> 6DOF_URDF/roll
[12:14:55]   Roll: dropped Roll_Bearing_2/HR32906J_Inner_ring (Roll Bearing 2:5+HR32906J Inner ring:1) -> 6DOF_URDF/roll
[12:14:55]   Roll: dropped Roll_Bearing_2/HR32906J_Outer_ring (Roll Bearing 2:5+HR32906J Outer ring:1) -> 6DOF_URDF/roll
[12:14:55]   Roll: dropped Roll_Bearing_2/HR32906J_Inner_ring (Roll Bearing 2:6+HR32906J Inner ring:1) -> 6DOF_URDF/roll
[12:14:55]   Roll: dropped Roll_Bearing_2/HR32906J_Outer_ring (Roll Bearing 2:6+HR32906J Outer ring:1) -> 6DOF_URDF/roll
[12:14:55]   Roll: dropped Belt_Shaft/Component64 (Belt Shaft:1+Component64:1) -> 6DOF_URDF/roll
[12:14:55]   Yaw: anchor=yaw merged_name=Yaw members=5 mass=259.84 g bbox=(87.6 × 93.2 × 55.0) mm
[12:14:55]   Yaw: dropped 6DOF_URDF/Yaw_Motor (Yaw Motor:1) -> 6DOF_URDF/yaw
[12:14:55]   Yaw: dropped Roll_Bearing_2/HR32906J_Inner_ring (Roll Bearing 2:7+HR32906J Inner ring:1) -> 6DOF_URDF/yaw
[12:14:55]   Yaw: dropped Roll_Bearing_2/HR32906J_Outer_ring (Roll Bearing 2:7+HR32906J Outer ring:1) -> 6DOF_URDF/yaw
[12:14:55]   Yaw: dropped 6DOF_URDF/Motor_Housing_Yaw (Motor Housing Yaw:1) -> 6DOF_URDF/yaw
[12:14:55]   Rigid Group 1: anchor=HR32906J_Inner_ring merged_name=HR32906J_Inner_ring members=2 mass=74.55 g bbox=(12.0 × 47.0 × 47.0) mm
[12:14:55]   WARNING:   Rigid group 'Rigid Group 1': anchor 'HR32906J_Inner_ring' not in occ_to_asm - skipping merge
[12:14:55]   Rigid Group 1: anchor=HR32906J_Inner_ring merged_name=HR32906J_Inner_ring members=2 mass=74.55 g bbox=(12.0 × 47.0 × 47.0) mm
[12:14:55]   WARNING:   Rigid group 'Rigid Group 1': anchor 'HR32906J_Inner_ring' not in occ_to_asm - skipping merge
[12:14:55]   Rigid Group 1: anchor=EG17_shaft_2 merged_name=EG17_shaft_2 members=13 mass=390.74 g bbox=(42.0 × 42.0 × 88.0) mm
[12:14:55]   WARNING:   Rigid group 'Rigid Group 1': anchor 'EG17_shaft_2' not in occ_to_asm - skipping merge
[12:14:55]   Rigid Group 1: anchor=EG17_shaft merged_name=EG17_shaft members=13 mass=295.97 g bbox=(42.0 × 42.0 × 77.0) mm
[12:14:55]   WARNING:   Rigid group 'Rigid Group 1': anchor 'EG17_shaft' not in occ_to_asm - skipping merge
[12:14:55]   Rigid Group 1: anchor=HR32906J_Inner_ring merged_name=HR32906J_Inner_ring members=2 mass=74.55 g bbox=(12.0 × 47.0 × 47.0) mm
[12:14:55]   WARNING:   Rigid group 'Rigid Group 1': anchor 'HR32906J_Inner_ring' not in occ_to_asm - skipping merge
[12:14:55]   Rigid Group 1: anchor=HR32906J_Inner_ring merged_name=HR32906J_Inner_ring members=2 mass=74.55 g bbox=(12.0 × 47.0 × 47.0) mm
[12:14:55]   WARNING:   Rigid group 'Rigid Group 1': anchor 'HR32906J_Inner_ring' not in occ_to_asm - skipping merge
[12:14:55]   Rigid Group 1: anchor=HR32906J_Inner_ring merged_name=HR32906J_Inner_ring members=2 mass=74.55 g bbox=(12.0 × 47.0 × 47.0) mm
[12:14:55]   WARNING:   Rigid group 'Rigid Group 1': anchor 'HR32906J_Inner_ring' not in occ_to_asm - skipping merge
[12:14:55]   Rigid Group 1: anchor=HR32906J_Inner_ring merged_name=HR32906J_Inner_ring members=2 mass=74.55 g bbox=(12.0 × 47.0 × 47.0) mm
[12:14:55]   WARNING:   Rigid group 'Rigid Group 1': anchor 'HR32906J_Inner_ring' not in occ_to_asm - skipping merge
[12:14:55]   Rigid Group 1: anchor=HR32906J_Inner_ring merged_name=HR32906J_Inner_ring members=2 mass=74.55 g bbox=(12.0 × 47.0 × 47.0) mm
[12:14:55]   WARNING:   Rigid group 'Rigid Group 1': anchor 'HR32906J_Inner_ring' not in occ_to_asm - skipping merge
[12:14:55]   No auto rigid islands found
[12:14:55] 
=== MODEL: RESOLVE JOINT PATHS ===
[12:14:55]   Rigid_1: internal rigid joint inside rigid group 6DOF_URDF/base_link; dropped as redundant
[12:14:55]   Rigid_2: internal rigid joint inside rigid group 6DOF_URDF/base_link; dropped as redundant
[12:14:55]   Rigid_3: internal rigid joint inside rigid group 6DOF_URDF/base_link; dropped as redundant
[12:14:55]   Rigid_4: internal rigid joint inside rigid group 6DOF_URDF/base_link; dropped as redundant
[12:14:55]   Revolute_5           6DOF_URDF/base_link → 6DOF_URDF/shoulder  [revolute] internal
[12:14:55]   Rigid_7: internal rigid joint inside rigid group 6DOF_URDF/shoulder; dropped as redundant
[12:14:55]   Rigid_8: internal rigid joint inside rigid group 6DOF_URDF/shoulder; dropped as redundant
[12:14:55]   Rigid_9: internal rigid joint inside rigid group 6DOF_URDF/shoulder; dropped as redundant
[12:14:55]   Rigid_10: internal rigid joint inside rigid group 6DOF_URDF/shoulder; dropped as redundant
[12:14:55]   Rigid_11: internal rigid joint inside rigid group 6DOF_URDF/shoulder; dropped as redundant
[12:14:55]   Rigid_12: internal rigid joint inside rigid group 6DOF_URDF/shoulder; dropped as redundant
[12:14:55]   Revolute_13          6DOF_URDF/shoulder → 6DOF_URDF/ua  [revolute] internal
[12:14:55]   Rigid_14: internal rigid joint inside rigid group 6DOF_URDF/ua; dropped as redundant
[12:14:55]   Rigid_15: internal rigid joint inside rigid group 6DOF_URDF/ua; dropped as redundant
[12:14:55]   Rigid_16: internal rigid joint inside rigid group 6DOF_URDF/ua; dropped as redundant
[12:14:55]   Rigid_17: internal rigid joint inside rigid group 6DOF_URDF/ua; dropped as redundant
[12:14:55]   Rigid_18: internal rigid joint inside rigid group 6DOF_URDF/ua; dropped as redundant
[12:14:55]   Rigid_19: internal rigid joint inside rigid group 6DOF_URDF/ua; dropped as redundant
[12:14:55]   Rigid_20: internal rigid joint inside rigid group 6DOF_URDF/shoulder; dropped as redundant
[12:14:55]   Rigid_21: internal rigid joint inside rigid group 6DOF_URDF/shoulder; dropped as redundant
[12:14:55]   Rigid_22: internal rigid joint inside rigid group 6DOF_URDF/shoulder; dropped as redundant
[12:14:55]   Rigid_23: internal rigid joint inside rigid group 6DOF_URDF/ua; dropped as redundant
[12:14:55]   Rigid_24: internal rigid joint inside rigid group 6DOF_URDF/ua; dropped as redundant
[12:14:55]   Rigid_25: internal rigid joint inside rigid group 6DOF_URDF/ua; dropped as redundant
[12:14:55]   Rigid_26: internal rigid joint inside rigid group 6DOF_URDF/ua; dropped as redundant
[12:14:55]   Rigid_27: internal rigid joint inside rigid group 6DOF_URDF/ua; dropped as redundant
[12:14:55]   Rigid_28: internal rigid joint inside rigid group 6DOF_URDF/ua; dropped as redundant
[12:14:55]   Revolute_29          6DOF_URDF/ua → 6DOF_URDF/elbow  [revolute] internal
[12:14:55]   Rigid_30: internal rigid joint inside rigid group 6DOF_URDF/elbow; dropped as redundant
[12:14:55]   Rigid_31: internal rigid joint inside rigid group 6DOF_URDF/elbow; dropped as redundant
[12:14:55]   Rigid_32: internal rigid joint inside rigid group 6DOF_URDF/elbow; dropped as redundant
[12:14:55]   Rigid_33: internal rigid joint inside rigid group 6DOF_URDF/elbow; dropped as redundant
[12:14:55]   Rigid_34: internal rigid joint inside rigid group 6DOF_URDF/elbow; dropped as redundant
[12:14:55]   Rigid_35: internal rigid joint inside rigid group 6DOF_URDF/elbow; dropped as redundant
[12:14:55]   Rigid_36: internal rigid joint inside rigid group 6DOF_URDF/elbow; dropped as redundant
[12:14:55]   Revolute_37          6DOF_URDF/elbow → 6DOF_URDF/roll  [revolute] internal
[12:14:55]   Rigid_38: internal rigid joint inside rigid group 6DOF_URDF/roll; dropped as redundant
[12:14:55]   Rigid_39: internal rigid joint inside rigid group 6DOF_URDF/roll; dropped as redundant
[12:14:55]   Rigid_40: internal rigid joint inside rigid group 6DOF_URDF/roll; dropped as redundant
[12:14:55]   Rigid_41: internal rigid joint inside rigid group 6DOF_URDF/roll; dropped as redundant
[12:14:55]   Rigid_42: internal rigid joint inside rigid group 6DOF_URDF/roll; dropped as redundant
[12:14:55]   Revolute_43          6DOF_URDF/roll → 6DOF_URDF/yaw  [revolute] internal
[12:14:55]   Rigid_44: internal rigid joint inside rigid group 6DOF_URDF/yaw; dropped as redundant
[12:14:55]   Rigid_45: internal rigid joint inside rigid group 6DOF_URDF/yaw; dropped as redundant
[12:14:55]   Revolute_46          6DOF_URDF/yaw → 6DOF_URDF/gripper  [revolute] internal
[12:14:55]   Rigid_54: internal rigid joint inside rigid group 6DOF_URDF/ua; dropped as redundant
[12:14:55]   Rigid_55             6DOF_URDF/ua → 6DOF_URDF/elbow  [rigid] internal
[12:14:55]   Rigid_56             6DOF_URDF/elbow → 6DOF_URDF/roll  [rigid] internal
[12:14:55]   Rigid_57             6DOF_URDF/roll → 6DOF_URDF/yaw  [rigid] internal
[12:14:55]   Rigid_58: internal rigid joint inside rigid group 6DOF_URDF/gripper; dropped as redundant
[12:14:55]   Rigid_59: internal rigid joint inside rigid group 6DOF_URDF/shoulder; dropped as redundant
[12:14:55]   WARNING:   CLOSING(auto): Multi-parent link detected (child=!frame_elbow:1): keeping 'Revolute_29' as the URDF tree parent; routing ['Rigid_55'] to ``closing_joints`` (sidecar) — closed kinematic loop.  Tag the loop-closing joint(s) with prefix ``!closing_*`` in Fusion to make the choice explicit and avoid this warning.
[12:14:55]   WARNING:   CLOSING(auto): Multi-parent link detected (child=!frame_roll:1): keeping 'Revolute_37' as the URDF tree parent; routing ['Rigid_56'] to ``closing_joints`` (sidecar) — closed kinematic loop.  Tag the loop-closing joint(s) with prefix ``!closing_*`` in Fusion to make the choice explicit and avoid this warning.
[12:14:55]   WARNING:   CLOSING(auto): Multi-parent link detected (child=!frame_yaw:1): keeping 'Revolute_43' as the URDF tree parent; routing ['Rigid_57'] to ``closing_joints`` (sidecar) — closed kinematic loop.  Tag the loop-closing joint(s) with prefix ``!closing_*`` in Fusion to make the choice explicit and avoid this warning.
[12:14:55] 
=== MODEL: DETECT ROOT ===
[12:14:55]   Parent-only nodes: 1
[12:14:55]     6DOF_URDF/base_link
[12:14:55]   → Root: 6DOF_URDF/base_link
[12:14:55] 
=== MODEL: RESOLVE NAMES ===
[12:14:55]   Elbow (6DOF_URDF) → Elbow
[12:14:55]   Gripper (6DOF_URDF) → Gripper
[12:14:55]   Roll (6DOF_URDF) → Roll
[12:14:55]   Shoulder (6DOF_URDF) → Shoulder
[12:14:55]   UA (6DOF_URDF) → UA
[12:14:55]   Yaw (6DOF_URDF) → Yaw
[12:14:55]   WARNING: Root link renamed: 'Base' → 'base_link'
[12:14:55]   Base (6DOF_URDF) → base_link
[12:14:55]   Root link URDF name: base_link
[12:14:55] 
=== MODEL: BUILD LINKS ===
[12:14:55]   base_link: MERGED (5 members) mass=596.69 g
[12:14:55]   UA: MERGED (30 members) mass=1236.31 g
[12:14:55]   Elbow: MERGED (10 members) mass=733.48 g
[12:14:55]   Roll: MERGED (9 members) mass=682.37 g
[12:14:55]   Yaw: MERGED (5 members) mass=259.84 g
[12:14:55]   Gripper: MERGED (2 members) mass=11.20 g
[12:14:55]   Shoulder: MERGED (23 members) mass=2094.14 g
[12:14:55]   Built 7 links
[12:14:55] 
=== MODEL: BUILD JOINTS ===
[12:14:55]   NOTE: joint origin rpy derived from child occurrence's transform2 rotation (was hardcoded 0,0,0 pre-2026-04-13)
[12:14:55]   Revolute_5: using frame-only rigid-group anchor 'Shoulder' as movable joint origin
[12:14:55]   Revolute_5: joint origin rpy = (-0.000000, 0.000000, 0.086342) rad (-0.00°, +0.00°, +4.95°) [from child transform2 rotation]
[12:14:55]   Revolute_5: base_link → Shoulder [revolute]
[12:14:55]     origin_xyz: (0.000000, 0.000000, -0.051500) m [frame_anchor_minus_parent]
[12:14:55]     origin_global: (0.000000, 0.000000, -0.051500) m
[12:14:55]   Revolute_13: using frame-only rigid-group anchor 'UA' as movable joint origin
[12:14:55]   Revolute_13: joint origin rpy = (1.570796, 0.698132, -0.000000) rad (+90.00°, +40.00°, -0.00°) [from child transform2 rotation]
[12:14:55]   Revolute_13: origin_xyz rotated into parent-local frame: (-0.007100, -0.149900, 0.111900) → (-0.020000, -0.148729, 0.111900) m
[12:14:55]  Revolute_13: axis remapped world -> joint/child frame: (0.086, -0.996, -0.000) -> (0.000, -0.000, 1.000)
[12:14:55]   Revolute_13: Shoulder → UA [revolute]
[12:14:55]     origin_xyz: (-0.020000, -0.148729, 0.111900) m [frame_anchor_minus_parent]
[12:14:55]     origin_global: (-0.007100, -0.149900, 0.060400) m
[12:14:55]   Revolute_29: using frame-only rigid-group anchor 'Elbow' as movable joint origin
[12:14:55]   Revolute_29: origin_xyz rotated into parent-local frame: (0.129651, 0.047357, 0.154914) → (0.002500, 0.204324, -0.036000) m
[12:14:55]  Revolute_29: axis remapped world -> joint/child frame: (0.086, -0.996, 0.000) -> (-0.000, -0.000, 1.000)
[12:14:55]   Revolute_29: UA → Elbow [revolute]
[12:14:55]     origin_xyz: (0.002500, 0.204324, -0.036000) m [frame_anchor_minus_parent]
[12:14:55]     origin_global: (0.122551, -0.102543, 0.215314) m
[12:14:55]   Rigid_55: origin_xyz rotated into parent-local frame: (0.129651, 0.047357, 0.154914) → (0.002500, 0.204324, -0.036000) m
[12:14:55]   Rigid_55: UA → Elbow [fixed] [closing/auto_detected]
[12:14:55]     origin_xyz: (0.002500, 0.204324, -0.036000) m [child_minus_parent]
[12:14:55]     origin_global: (0.168981, -0.314643, 0.057987) m
[12:14:55]   Revolute_37: using frame-only rigid-group anchor 'Roll' as movable joint origin
[12:14:55]   Revolute_37: joint origin rpy = (-1.570796, -0.000000, -0.463437) rad (-90.00°, -0.00°, -26.55°) [from child transform2 rotation]
[12:14:55]   Revolute_37: origin_xyz rotated into parent-local frame: (-0.021571, 0.069900, 0.083655) → (-0.065618, 0.054144, -0.071500) m
[12:14:55]  Revolute_37: axis remapped world -> joint/child frame: (-0.914, -0.079, -0.398) -> (0.000, 0.000, -1.000)
[12:14:55]   Revolute_37: Elbow → Roll [revolute]
[12:14:55]     origin_xyz: (-0.065618, 0.054144, -0.071500) m [frame_anchor_minus_parent]
[12:14:55]     origin_global: (0.100980, -0.032643, 0.298969) m
[12:14:55]   Rigid_56: joint origin rpy = (-1.570796, -0.000000, -0.463437) rad (-90.00°, -0.00°, -26.55°) [from child transform2 rotation]
[12:14:55]   Rigid_56: origin_xyz rotated into parent-local frame: (-0.021571, 0.069900, 0.083655) → (-0.065618, 0.054144, -0.071500) m
[12:14:55]   Rigid_56: Elbow → Roll [fixed] [closing/auto_detected]
[12:14:55]     origin_xyz: (-0.065618, 0.054144, -0.071500) m [child_minus_parent]
[12:14:55]     origin_global: (0.417086, -0.038047, 0.325287) m
[12:14:55]   Revolute_43: using frame-only rigid-group anchor 'Yaw' as movable joint origin
[12:14:55]   Revolute_43: joint origin rpy = (2.715881, -1.570796, -1.069818) rad (+155.61°, -90.00°, -61.30°) [from child transform2 rotation]
[12:14:55]   Revolute_43: origin_xyz rotated into parent-local frame: (-0.166483, -0.065056, -0.072093) → (-0.002090, -0.050457, -0.186000) m
[12:14:55]  Revolute_43: axis remapped world -> joint/child frame: (-0.070, 0.997, -0.038) -> (0.000, -0.000, -1.000)
[12:14:55]   Revolute_43: Roll → Yaw [revolute]
[12:14:55]     origin_xyz: (-0.002090, -0.050457, -0.186000) m [frame_anchor_minus_parent]
[12:14:55]     origin_global: (-0.065503, -0.097698, 0.226876) m
[12:14:55]   Rigid_57: joint origin rpy = (2.715881, -1.570796, -1.069818) rad (+155.61°, -90.00°, -61.30°) [from child transform2 rotation]
[12:14:55]   Rigid_57: origin_xyz rotated into parent-local frame: (-0.166483, -0.065056, -0.072093) → (-0.002090, -0.050457, -0.186000) m
[12:14:55]   Rigid_57: Roll → Yaw [fixed] [closing/auto_detected]
[12:14:55]     origin_xyz: (-0.002090, -0.050457, -0.186000) m [child_minus_parent]
[12:14:55]     origin_global: (-0.070503, -0.329718, 0.119870) m
[12:14:55]   Revolute_46: using frame-only rigid-group anchor 'Gripper' as movable joint origin
[12:14:55]   Revolute_46: joint origin rpy = (-1.570796, -0.718221, 0.475437) rad (-90.00°, -41.15°, +27.24°) [from child transform2 rotation]
[12:14:55]   Revolute_46: origin_xyz rotated into parent-local frame: (-0.058842, 0.048192, 0.043332) → (-0.032727, 0.063570, -0.050500) m
[12:14:55]  Revolute_46: axis remapped world -> joint/child frame: (-0.774, -0.030, 0.633) -> (0.000, 0.000, 1.000)
[12:14:55]   Revolute_46: Yaw → Gripper [continuous]
[12:14:55]     origin_xyz: (-0.032727, 0.063570, -0.050500) m [frame_anchor_minus_parent]
[12:14:55]     origin_global: (-0.124345, -0.049506, 0.270208) m
[12:14:55]   Built 6 joints
[12:14:55] 
=== MODEL: VALIDATE ===
[12:14:55]   Validation passed (4 warnings)
[12:14:55] 
[12:14:55] Kinematic tree:
[12:14:55]   base_link (597g) [MERGED]
[12:14:55]     ─⟳─ Revolute_5 [revolute]
[12:14:55]       Shoulder (2094g) [MERGED]
[12:14:55]         ─⟳─ Revolute_13 [revolute]
[12:14:55]           UA (1236g) [MERGED]
[12:14:55]             ─⟳─ Revolute_29 [revolute]
[12:14:55]               Elbow (733g) [MERGED]
[12:14:55]                 ─⟳─ Revolute_37 [revolute]
[12:14:55]                   Roll (682g) [MERGED]
[12:14:55]                     ─⟳─ Revolute_43 [revolute]
[12:14:55]                       Yaw (260g) [MERGED]
[12:14:55]                         ─⟳─ Revolute_46 [continuous]
[12:14:55]                           Gripper (11g) [MERGED]
[12:14:55]   
[12:14:55]   Closed-loop joints (sidecar) — emitted to robot_data.yaml,
[12:14:55]   re-applied by downstream URDF→USD pipelines as USD physics joints:
[12:14:55]       ─── Rigid_55 [fixed] [auto_detected]: UA → Elbow
[12:14:55]       ─── Rigid_56 [fixed] [auto_detected]: Elbow → Roll
[12:14:55]       ─── Rigid_57 [fixed] [auto_detected]: Roll → Yaw
[12:14:55] 
=== MODEL SUMMARY ===
[12:14:55]   Robot: 6DOF_URDF
[12:14:55]   Root link: base_link
[12:14:55]   Links: 7
[12:14:55]   Joints: 6
[12:14:55]   Assemblies: 10
[12:14:55]   Warnings: 4
[12:14:55]   Errors: 0
[12:14:55]   collision_method from config: convex_hull
[12:14:55]   visual_format from config: dae
[12:14:56] 
=== MESH EXPORT ===
[12:14:56]   base_link:
[12:14:56]     base_link: rigid group has shared-component member(s) — using per-member export to avoid sibling-geometry leak
[12:14:59]     Merged rigid group (5 members, 45488 verts, 90992 faces)
[12:15:00]     DAE written → meshes/6DOF_URDF/base_link.dae (OBJ retained for collision fit)
[12:15:00]   UA:
[12:15:00]     UA: rigid group uses frame-only anchor/member - using per-member export
[12:15:00]   WARNING:     member 92605A009: OBJ export failed
[12:15:01]   WARNING:     member 92605A009: OBJ export failed
[12:15:06]   WARNING:     member 92605A009_1: OBJ export failed
[12:15:06]   WARNING:     member 92605A009_1: OBJ export failed
[12:15:10]     Merged rigid group (25 members, 78261 verts, 156626 faces)
[12:15:11]     DAE written → meshes/6DOF_URDF/UA.dae (OBJ retained for collision fit)
[12:15:11]   Elbow:
[12:15:11]     Elbow: rigid group uses frame-only anchor/member - using per-member export
[12:15:17]     Merged rigid group (9 members, 52484 verts, 105024 faces)
[12:15:18]     DAE written → meshes/6DOF_URDF/Elbow.dae (OBJ retained for collision fit)
[12:15:18]   Roll:
[12:15:18]     Roll: rigid group uses frame-only anchor/member - using per-member export
[12:15:22]     Merged rigid group (8 members, 34022 verts, 68104 faces)
[12:15:22]     DAE written → meshes/6DOF_URDF/Roll.dae (OBJ retained for collision fit)
[12:15:22]   Yaw:
[12:15:22]     Yaw: rigid group uses frame-only anchor/member - using per-member export
[12:15:24]     Merged rigid group (4 members, 13527 verts, 27154 faces)
[12:15:24]     DAE written → meshes/6DOF_URDF/Yaw.dae (OBJ retained for collision fit)
[12:15:24]   Gripper:
[12:15:24]     Gripper: rigid group uses frame-only anchor/member - using per-member export
[12:15:25]     Merged rigid group (1 members, 1518 verts, 3032 faces)
[12:15:25]     DAE written → meshes/6DOF_URDF/Gripper.dae (OBJ retained for collision fit)
[12:15:25]   Shoulder:
[12:15:25]     Shoulder: rigid group uses frame-only anchor/member - using per-member export
[12:15:32]     Merged rigid group (22 members, 43679 verts, 87426 faces)
[12:15:33]     DAE written → meshes/6DOF_URDF/Shoulder.dae (OBJ retained for collision fit)
[12:15:33] 
  Mesh export summary:
[12:15:33]     Visual (OBJ+MTL):              7
[12:15:33]     Collision sub-component (STL):  0
[12:15:33]     Collision body + warning (STL): 0
[12:15:33]     Skipped (no Fusion ref):        0
[12:15:33] 
=== PHASE 3: SCREENSHOT ===
[12:15:34]   → images/robot.png
[12:15:34] 
=== PACKAGE: GENERATE ===
[12:15:34]   Package: 6DOF_URDF_description
[12:15:34]   Output:  C:/EE Projects/6DOF/URDF/URDF8\6DOF_URDF_description
[12:15:34] 
=== COLLISION: RESOLVE ===
[12:15:34]   base_link: convex hull
[12:15:34]   UA: convex hull
[12:15:34]   Elbow: convex hull
[12:15:34]   Roll: convex hull
[12:15:34]   Yaw: convex hull
[12:15:34]   Gripper: convex hull
[12:15:34]   Shoulder: convex hull
[12:15:34] 
  Collision summary:
[12:15:34]     Explicit:        0
[12:15:34]     Primitive (STL): 0
[12:15:34]     Convex hull STL: 7
[12:15:34]     Visual reuse:    0
[12:15:34]     Visual fallback: 0
[12:15:34] 
=== COLLISION: GENERATE STL ===
[12:15:36]   base_link: convex hull -> 78 tris (3.9 KB)
[12:15:39]   UA: convex hull -> 254 tris (12.5 KB)
[12:15:40]   Elbow: convex hull -> 180 tris (8.9 KB)
[12:15:41]   Roll: convex hull -> 102 tris (5.1 KB)
[12:15:42]   Yaw: convex hull -> 340 tris (16.7 KB)
[12:15:43]   Gripper: convex hull -> 460 tris (22.5 KB)
[12:15:45]   Shoulder: convex hull -> 216 tris (10.6 KB)
[12:15:45] 
  Generated 7 collision STL files
[12:15:45] 
=== PACKAGE: FRAMES ===
[12:15:45]   -> debug/frame_model.json (pre-frame cache)
[12:15:45]   Frame convention: ros
[12:15:45]   Frame overrides:  config/frame_overrides.csv
[12:15:45]   Rebased links:    6/7
[12:15:45] 
=== PACKAGE: XACRO ===
[12:15:45]   → urdf/6DOF_URDF.urdf.xacro
[12:15:45]   → urdf/assemblies/6DOF_URDF.urdf.xacro
[12:15:45] 
=== PACKAGE: URDF (flat, for validation) ===
[12:15:45]   → urdf/6DOF_URDF.urdf
[12:15:45] 
=== PACKAGE: ROS2 FILES ===
[12:15:45]   → package.xml
[12:15:45]   → CMakeLists.txt
[12:15:45]   → launch/display.launch.py
[12:15:45]   → rviz/display.rviz
[12:15:45]   → config/joint_state.yaml
[12:15:45]   → config/ros2_controllers.yaml
[12:15:45] 
=== PACKAGE: SUPPLEMENTARY DATA ===
[12:15:45]   → robot_data.yaml
[12:15:45]   -> docs/transforms.md
[12:15:45] 
=== PACKAGE: README ===
[12:15:45]   → README.md
[12:15:45]   Cleaned up 14 retained OBJ/MTL files
[12:15:45]   Removed 8 empty generated directories
[12:15:45] 
=== PACKAGE: COMPLETE ===
[12:15:45]   Package generated: C:/EE Projects/6DOF/URDF/URDF8\6DOF_URDF_description
[12:15:45]   Xacro: urdf/6DOF_URDF.urdf.xacro (+ 1 assembly macros)
[12:15:45]   URDF:  urdf/6DOF_URDF.urdf (flat, for validation)
[12:15:45]   Launch: ros2 launch 6DOF_URDF_description display.launch.py
[12:15:45] 
=== EXPORT COMPLETE ===
```
