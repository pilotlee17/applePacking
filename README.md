# 球形水果智能分拣包装机

## 操作演示

> **主要功能:** 分拣机构采用计算机视觉技术对球形水果表面品质进行检测，并剔除次品。检测合格的水果进行包装机构，包装机构模拟人手实现水果网套包装的过程。

> **包装机构:** 为模拟人工网套包装时的动作，设计了一套包括曲柄摇杆机构、丝杆螺母副和曲柄滑块机构在内的组合机构，并利用Arduino进行电机控制，实现“推苹果、拉网套、割网套”的一整套动作。并巧妙利用了曲柄摇杆机构死点实现了“死点增力”，保证推苹果时的稳定性。

![Thumbnail Image](demo_all.gif?raw=true)

> **倾斜式传送带:** 倾斜式传送带使苹果翻转直至根蒂部位朝下，保证视觉系统只拍摄到苹果侧面，消除根蒂对视觉检测的影响。

![Thumbnail Image](demo_tiltedBelt.gif?raw=true)

## 海报展示

![Thumbnail Image](poster_2.jpg?raw=true)
![Thumbnail Image](poster_3.jpg?raw=true)
![Thumbnail Image](poster_4.jpg?raw=true)


