# 低维非线性晶格系统的热输运研究

本项目主要对简谐晶格、FPU-beta晶格、phi^4晶格、Couple Rotator晶格和Toda晶格中的反常输运过程进行了研究，特别对各晶格系统的扩散行为进行了计算。我们主要采用能量扩散方法计算晶格系统的扩散系数。通过平衡方法模拟计算能量载流子的概率分布函数，求出系统均方位移，我们可以得到晶格系统的扩散系数。模拟计算中，我们采用高阶辛算法以减小误差。本项目中，我们使用周期性边界条件。我们模拟计算了不同晶格能量-动量相关函数和FPU-beta晶格的声子速度，同时研究比较了温度对FPU-beta晶格、phi^4晶格、Couple Rotator晶格的能量-动量相关函数的影响。

`FPU-beta.f90`: 使用Fortran语言，以FPU-β晶格为例（其他四种晶格的程序可以在此基础上进行修改)。

Thermal Transportation in Low Dimensional Nonlinear Lattice System

In this project, we investigated the anomalous energy transport behavior in different lattice systems, such as harmonic lattice, FPU-beta lattice, phi^4 lattice, couple rotator and Toda lattice. We use energy transport method to calculate the thermal conductivity in different type of lattice systems with periodic boundary condition. And we use equilibrium method to get the probability distribution function of energy carriers and then deduce the thermal conductibvity of lattice system using the mean square displacement. The errors are reduced using the high order symplectic algorithm. We also investigated the impact of temperature on the energy-momentum functions of different lattices.
