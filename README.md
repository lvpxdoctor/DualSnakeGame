# DualSnakeGame

这是一个基于HTML5 Canvas实现的双人贪吃蛇游戏，适合两个玩家在同一台设备上通过键盘控制进行对战。游戏具有可调节速度、生命系统、不同得分的食物以及得分兑换生命等特色功能。

<img src="https://github.com/user-attachments/assets/e3c66f75-ce15-4772-8258-f814cc24b68b" alt="游戏截图" width="200" height="300" />

## 特性
- **双人模式**：玩家1使用WASD键，玩家2使用箭头键控制各自的蛇。
- **可调节速度**：通过滑块调整游戏速度（1-10级）。
- **生命系统**：每个玩家初始有5条命，碰撞时减少，生命耗尽时游戏结束。
- **两种食物**：红色食物（10分）和黄色食物（20分）。
- **得分兑换生命**：每获得100分自动转换为1条额外生命，并显示醒目提示。
- **起始画面**：游戏开始前显示静态的初始蛇和食物。

## 如何使用
1. **在线体验**：直接打开 [GitHub Pages 链接](#)（若部署后替换此链接）。
2. **本地运行**：
   - 克隆仓库到本地：
     ```bash
     git clone https://github.com/lvpxdoctor/DualSnakeGame.git
     ```
   - 进入项目目录：
     ```bash
     cd DualSnakeGame
     ```
   - 使用浏览器打开 `index.html` 文件。

3. **游戏操作**：
   - 点击“开始游戏”按钮启动游戏。
   - **玩家1**（绿色蛇）：W（上）、S（下）、A（左）、D（右）。
   - **玩家2**（蓝色蛇）：↑（上）、↓（下）、←（左）、→（右）。
   - 调整速度滑块控制游戏节奏。
   - 吃食物得分，撞到自己或对方减命，100分换1命。


## 安装与部署
无需额外安装依赖，直接在浏览器中运行即可。若想部署到GitHub Pages：
1. 将项目推送到GitHub仓库。
2. 在GitHub仓库设置中启用GitHub Pages，选择`main`分支。
3. 访问生成的链接即可在线游玩。

## 贡献
欢迎提交Issue或Pull Request改进游戏！可能的改进方向：
- 添加音效
- 优化食物生成算法（避免重叠）
- 支持移动端触控操作
- 美化界面样式

## 许可证
本项目采用 [MIT License](LICENSE) 开源。

## 致谢
- 由 [Grok](https://xai.com)（xAI团队）协助生成代码。
- 灵感来源于经典贪吃蛇游戏。
