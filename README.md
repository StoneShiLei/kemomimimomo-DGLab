# VRChat 触摸反馈系统

[English](./README_EN.md)

通过 VRChat 的触摸交互实现真实的触觉反馈体验。

## 功能特点

- 支持通过触摸 Avatar 特定部位触发触觉反馈
- 支持多个郊狼设备同时连接，实现多人互动
- 完全兼容 MA 预制件
- 可自定义触发区域位置

## 系统要求

- 郊狼 3.0 设备
- VRChat 账号
- 支持 MA 的 Avatar
- Python 3.8 或更高版本

## 程序安装

1. 克隆仓库到本地：
```bash
git clone https://github.com/你的用户名/项目名.git
```
2. 安装依赖包：
```bash
pip install -r requirements.txt
```
3. 运行主程序：
```bash
python main.py
```

## Avatar 安装说明

1. 下载最新版本的预制件
2. 将预制件导入到你的 Avatar 项目中
3. 将触发器组件放置到需要触觉反馈的位置
4. 确保所有变量名与预制件保持一致

## 使用方法

1. 启动 VRChat 并进入游戏
2. 连接郊狼设备到 WebSocket
3. 按下设备 A 通道的圆形按钮开始接收信号
4. 当其他玩家触摸到触发区域时，将会产生相应的触觉反馈

## 注意事项

- 当前版本仍在开发中，可能存在一些已知问题
- 建议在使用前检查设备连接状态
- 如遇到问题请提交 Issue

## 贡献指南

欢迎提交 Pull Request 或 Issue 来帮助改进项目。

## 许可证

[许可证类型]

