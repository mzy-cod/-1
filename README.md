# 万有引力粒子群的仿真测试
我们基于经典的src布局，结合Taichi编程语言，利用其强大的GPU并行计算能力，完成一个万有引力粒子群的仿真测试  
<img width="366" height="349" alt="image" src="https://github.com/user-attachments/assets/c184372f-342d-42d4-aee2-e4e4bc013a2a" />

通过这次实验，我理解了现代 Python 项目级环境隔离的原理，掌握使用 uv 包管理器进行局部虚拟环境（.venv）的配置与无感管理，避免全局环境污染  
也理解了图形学项目中的现代工程规范与解耦思想，通过构建标准的 src 布局（Source Layout）物理分离参数配置、底层计算与前端视图，解决路径混淆并提升代码可维护性；  
以及理解图形学底层的硬件加速机制，通过 Taichi 框架实现与 GPU 的连通，运用并行计算驱动大规模粒子群的物理模拟。  
**代码基于 Taichi 框架实现的GPU 并行化粒子物理系统，核心功能是让大量粒子受鼠标位置的引力影响，并在边界内反弹**  
核心参数：GRAVITY_STRENGTH、DRAG_COEF、BOUNCE_COEF是控制粒子行为的关键常量。
<video 
  src="[https://raw.githubusercontent.com/你的用户名/仓库名/main/videos/demo.mp4](https://github.com/mzy-cod/-1/raw/refs/heads/main/%E5%AE%9E%E9%AA%8C1.mp4)"  
  width="800"        
  controls          
  preload="metadata"
>
![实验1gif版](https://github.com/user-attachments/assets/580204e2-ea8f-408b-bc6f-bd335d30af9e)




