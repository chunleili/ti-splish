# 本项目的目的

使用太极语言重构splishsplash这一开源库。splishsplash库为SPH法流体仿真的C++库。故而取名ti-splish。
    

splishsplash项目：https://github.com/InteractiveComputerGraphics/SPlisHSPlasH
taichi项目：https://github.com/taichi-dev/taichi
    

为什么要这么做？

  1. splishsplash对于SPH的算法很全很新，适合图形学研究人员做算法开发。
  2. taichi的可移植性很好，且会自动调用GPU并行，python风格的代码简短，很适合开发新图形学算法。
  3. 为了学习两者。

# 项目计划

1. 使用pybind库暴露splishsplash的API给python，这一点splishsplash已经做到了。
2. 使用taichi混合编程，调用暴露的splishsplash类中的API。

故而关键在于各种类的接口。为此，我们需要将splishsplash主要的类和其接口详细地列出来。为此，我们需要分析它的架构。



splishsplash架构分析：[splishArch](./doc/splishArch.md)



# 项目设计实例









