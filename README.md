# 🎮 Splicing - Pixel Art Puzzle Game

A multi-level pixel art style game project, with each level using a different color theme and gameplay mechanics.

## 📂 Project Structure

This project adopts**Branching development**，Each level is independent of the other two branches:

### 🎯 Level Branches

| Branches | Theme | State | Code volume | Describe |
|------|------|------|--------|------|
| **Level-1** | A SIMPLE JOURNEY | ✅ Finish | 1,334 lines | A word collection game where you memorize words to solve puzzles. |
| **Level-2** | I AM THE MOST MAGICAL CAT | ✅ Finish | 1,005 lines | Jumping adventure game, collect coins and avoid obstacles |
| **level-3** | Fingertip Magic | ✅ Finish | 1,771 lines | Gesture tracking collection game using AI technology |

## 🌐 Game Overview

- 🎮 [Level-1: A SIMPLE JOURNEY](https://mckenzieaaa.github.io/Splicing/level-1/) - Text collection decryption
  <img width="1400" height="802" alt="b32f07f0f8b89c661027ca6f0b1d9544" src="https://github.com/user-attachments/assets/51f7b4d0-2703-4f59-bc91-225444a0e8fa" />

- 🐱 [Level-2: I AM THE MOST MAGICAL CAT](https://mckenzieaaa.github.io/Splicing/level-2/) - Jump Collection Game
  <img width="1402" height="810" alt="45758c3cb77e180fc4c4653cf271855e" src="https://github.com/user-attachments/assets/568570d4-dd6d-4078-8d2e-ff23587aa644" />

- 👆 [Level-3: Fingertip Magic](https://mckenzieaaa.github.io/Splicing/level-3/) - AI gesture recognition game
  <img width="1404" height="812" alt="f960291294f0b0d9c9d7ea74f8106dbc" src="https://github.com/user-attachments/assets/220cc6ad-9fc2-468e-a700-f38398848c46" />


## 📊 技术栈

- **纯 HTML5 Canvas** - 游戏渲染
- **原生 JavaScript** - 游戏逻辑
- **CSS3** - 样式和动画
- **MediaPipe (Level-3)** - AI手势识别
- **像素字体** - 复古游戏风格

## 🎨 关卡详情

### Level-1: 黑白世界 (Level-1 分支)

**特性：**
- ✨ 完整的平台跳跃游戏
- 🏃‍♂️ 角色动画系统（走路、跑步、跳跃）
- 🌄 多层背景视差滚动
- 🪙 收集品系统
- 🔊 音效系统
- 📱 响应式设计

**主要文件：**
- `level1.html` (1,334 行, 57 KB)
- `assets/` - 游戏资源
- 完成密码: `1030`

### Level-2: 魔法猫咪 (Level-2 分支)

**特性：**
- 🐱 可爱的猫咪主角
- 🎯 收集 30 个金币获胜
- 🚧 动态障碍物系统
- 🎈 滑翔机制
- 🏆 胜利动画

**主要文件：**
- `eeeeee/game.js` (739 行)
- `eeeeee/index.html` (31 行)
- `eeeeee/style.css` (235 行)
- 完成密码: `1218`

### level-3: 手势追踪游戏 (level-3 分支)

**特性：**
- � 摄像头手势追踪
- 🎯 手部动作收集金币
- 🤖 MediaPipe AI 技术
- 🎨 暖色调像素艺术
- 📸 实时视频处理
- 🏅 创新交互体验

**主要文件：**
- `team-work/web_game/game.js` (842 行)
- `team-work/web_game/index.html` (151 行)
- `team-work/web_game/styles.css` (778 行)
- 完成密码: `0218`

## 🔑 游戏密码系统

每个关卡完成后会显示一个密码，用于解锁下一关：

- Level 1 → `1030`
- Level 2 → `1218`  
- Level 3 → `0218`

## 👥 团队协作

本项目采用分支式开发，每个团队成员负责一个关卡：

1. **成员 A** - Level-1 (黑白关卡) ✅ 完成
2. **成员 B** - Level-2 (猫咪游戏) ✅ 完成
3. **成员 C** - level-3 (手势追踪游戏) ✅ 完成

## 📝 开发说明

### 本地开发

```bash
# 克隆仓库
git clone https://github.com/mckenzieaaa/Splicing.git
cd Splicing

# 切换到你要开发的分支
git checkout Level-1  # 或 Level-2, level-3

# 使用本地服务器运行（推荐）
# Python 3
python -m http.server 8000

# 或使用 VS Code Live Server 插件
```

### 提交代码

```bash
# 在你的分支上开发
git add .
git commit -m "Update game features"
git push origin <your-branch-name>
```

## 🌐 在线预览

访问 [GitHub Pages](https://mckenzieaaa.github.io/Splicing/) 查看主页面（如果已部署）

或访问各分支：
- [Level-1 分支](https://github.com/mckenzieaaa/Splicing/tree/Level-1)
- [Level-2 分支](https://github.com/mckenzieaaa/Splicing/tree/Level-2)
- [level-3 分支](https://github.com/mckenzieaaa/Splicing/tree/level-3)

## 📄 许可证

本项目仅用于学习和展示目的。

## 🙏 致谢

- 像素艺术资源来自 CraftPix
- 字体和其他开源资源

---

**最后更新：** 2025年11月13日
