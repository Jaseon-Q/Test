|                  | 优势                                                         | 劣势                                                         | 硬件要求                                                     | 支持的接口                                      |
| ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------------------------------------- |
| PyBullet         | 完全开源，社区大文档多，上手容易；<br />基于Python；<br />能够基于Docker容器，实时调整配置；<br />机器狗有关的开源案例较多；<br />界面较toolbox美观；<br /> | （相比Toolbox基本无劣势）；<br />单核情况下Real Time Factor相对Gazebo和MuJoCo较低 | 相对低于Gazebo，相似于MuJoCo；<br />以多个无人机仿真项目为例，Lenovo P52 (i7-8850H/Quadro P2000)和2020 MacBook Pro (i7-1068NG7)够用 | 文件格式支持SDA, URDF, MJCF<br />Python接口广泛 |
| Robotics Toolbox | 代码成熟（但bullet同样成熟）；<br />代码开源                 | 要基于Matlab，收费且有EAR风险<br />界面不够美观<br />(Real Time Factor对比未知) | 参考matlab本身的requirements                                 | （待考察）                                      |

# Reference

* Comparing  Popular  Simulation  Environments  in the  Scope  of  Robotics  and  Reinforcement  Learning，arXiv:2103.04616v1 ，各个经典环境的RTF参数和CPU使用程度比较（本篇没有Toolbox的）
* https://petercorke.com/toolboxes/robotics-toolbox/，Toolbox官网介绍它的优点
* https://github.com/Derek-TH-Wang/quadruped_ctrl，PyBullet仿真MIT Cheetah
* https://zhuanlan.zhihu.com/p/347078711，PyBullet和Gazebo试用，Pybullet更适合直接实现和验证算法
* https://github.com/utiasDSL/gym-pybullet-drones，PyBullet无人机项目例子
