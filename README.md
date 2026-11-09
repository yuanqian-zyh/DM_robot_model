# DM_robot_model
达妙轮腿机加工版本_urdf_已经完成闭链处理

# 五连杆轮腿机器人 URDF 模型
## 项目概述
本仓库包含一套五连杆平行轮腿机器人 URDF 模型文件，模型由 SolidWorks 导出，用于机器人可视化、动力学仿真与控制算法开发（Isaac Lab / Legged Gym / MuJoCo）。
机构为左右两组对称闭链五连杆结构，每组包含摆杆、连杆与驱动轮，属于闭链轮腿构型。

> ⚠️ 重要说明：原生URDF标准不支持 `<loop_joint>`，闭环约束为扩展标签，仅适配自定义闭链解析器/MuJoCo，RViz、robotsfan等标准URDF查看器会忽略闭环约束，仅渲染开链树形结构。

## 建议通过Robot Viewer网站直接阅览
