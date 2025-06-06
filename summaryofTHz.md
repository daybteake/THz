| **分类**       | **技术原理**                                                                | **代表技术/材料**                                | **输出特性**                                  | **优势与局限性**                                                 |
| -------------------- | --------------------------------------------------------------------------------- | ------------------------------------------------------ | --------------------------------------------------- | ---------------------------------------------------------------------- |
| **激光激发**   |                                                                                   |                                                        |                                                     |                                                                        |
| 1. 光电导天线        | 超短激光脉冲激发半导体材料（如低温砷化镓），瞬态光电流辐射THz波                   | 低温砷化镓（LT-GaAs）光电导天线                        | 脉宽<0.6 ps，频宽0.1-10 THz，平均功率>60 mW         | 高功率、超宽带，但需高能激光驱动和强电场偏置                           |
| 2. 光整流            | 飞秒激光通过非线性晶体（如铌酸锂、GaP）的二阶差频效应产生THz波                    | 铌酸锂（LiNbO₃）、磷化镓（GaP）晶体                   | 峰值功率达200 mW，调谐范围0.5-5.7 THz               | 宽频可调，但晶体损伤阈值低，需低温优化（如13.9 mJ单脉冲输出）          |
| 3. 等离子体相互作用  | 强激光与固体靶等离子体作用，通过渡越辐射、鞘层加速等机制产生THz波                 | 金属靶（如铜箔）、金属丝靶（LWGU模型）                 | 单脉冲能量达2.3 mJ（反射方向收集），宽频覆盖>10 THz | 能量密度高，但系统复杂（如需200 TW激光装置）                           |
| 4. 双色激光丝化      | 双色飞秒激光在气体（如氩气）中形成等离子体细丝，通过四波混频等非线性效应产生THz波 | 氩气中双色激光丝化                                     | 能量转换效率0.35%，单脉冲能量21 μJ                 | 无衍射损耗，适合远程传输，但需精密控制激光参数（如时空重叠、偏振匹配） |
| **非激光激发** |                                                                                   |                                                        |                                                     |                                                                        |
| 1. 量子级联激光器    | 基于半导体量子阱的带内跃迁，电子级联释放光子                                      | 砷化镓/铝镓砷（GaAs/AlGaAs）异质结构                   | 输出功率1 mW~1 W，调谐范围1-5 THz                   | 紧凑、可室温工作（部分需低温），但带宽较窄                             |
| 2. 气体激光器        | CO₂激光泵浦气体（如CH₄、HCN）分子转动能级跃迁                                   | 甲烷（CH₄）、氰化氢（HCN）气体腔                      | 输出功率百毫瓦级，已商业化（如NASA卫星观测）        | 高功率、稳定，但需缓冲气体优化振动瓶颈效应                             |
| 3. 肖特基二极管      | 电子隧穿势垒产生高频振荡                                                          | 肖特基势垒二极管                                       | 输出功率μW~mW级，带宽<3 THz                        | 低成本、易集成，但功率低                                               |
| 4. 自旋电子学源      | 铁磁材料中超快退磁、反常霍尔/能斯特效应产生THz波                                  | 铁磁薄膜（如CoFeB）、二维范德瓦尔斯磁性晶体（如CrI₃） | 单频可调（如0.9 THz），零阈值、高Q值                | 固态稳定、频谱纯净，但机理复杂（需磁场调控自旋-晶格耦合）              |
| 5. 热电子学源        | 塞贝克效应/能斯特效应驱动的超快热电流辐射THz波                                    | 金属-半导体异质结（如Bi₂Te₃/Si）                     | 功率较低，频带依赖材料特性                          | 无激光依赖，但效率受限                                                 |

### **分类说明与补充**

1. **激光激发类**：依赖高能飞秒/皮秒激光驱动，通过光电导、光整流、等离子体相互作用等非线性过程产生高功率THz辐射，适用于实验室和工业高需求场景（如6G通信、强场物理）。
2. **非激光激发类**：基于电子学或热力学机制，包括量子级联激光器、气体激光器等，优势在于便携性和低功耗，适合集成化设备（如安检仪、可穿戴传感器）。
3. **新兴技术**：
   - **自旋电子学源**：利用磁性材料中的自旋-晶格耦合，实现单频可调谐THz辐射，为新型太赫兹元器件开发提供策略。
   - **声子单频源**：基于玻色子特性的二维磁性半导体晶体，具有零阈值和高辐射效率，拓展了低维材料在THz领域的应用。

### **未来发展方向**

- **激光激发**：提升效率（如超表面增强非线性效应）、降低成本（紧凑型激光器）。
- **非激光激发**：开发高损伤阈值材料（如二维异质结）、优化热管理（微流控散热）。
