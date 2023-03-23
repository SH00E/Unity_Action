动画
  通过Rigid Body和Root Motion实现基本的人物动作
  通过调整动画播放速度来防止脚步打滑
  出招、大位移动作交给Root Motion来实现
  行走等动作不交给Root Motion避免引起各种各样的问题
输入
  使用New Input System
  实现手柄/鼠标行走和奔跑功能
  多设备出输入输出，通过PlayerInput的currentControlScheme就可以知道是那个设备在工作了
人物
  使用了avatar骨骼系统、动作复用，同时使用了衣物模拟
缺点
  暂时不包含转身动画，后续改进
  感觉使用第三人称控制器会比较好一些
  
