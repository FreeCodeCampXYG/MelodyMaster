# 🎵 MelodyMaster | 专业音乐识谱训练工具

```
![alt text](https://img.shields.io/badge/License-MIT-yellow.svg)
```


[`![alt text](https://img.shields.io/badge/Made%20with-Vanilla%20JS-F7DF1E.svg)`](https://www.google.com/url?sa=E&q=https%3A%2F%2Fdeveloper.mozilla.org%2Fen-US%2Fdocs%2FWeb%2FJavaScript)



[`![alt text](https://img.shields.io/badge/Styling-Tailwind%20CSS-38B2AC.svg)`](https://www.google.com/url?sa=E&q=https%3A%2F%2Ftailwindcss.com%2F)



> **「15分钟高效训练 ≈ 2小时传统刷题」**
> MelodyMaster 是一款专为音乐学习者设计的纯前端识谱强化工具。通过游戏化机制，解决高低音谱号混淆、记忆枯燥等痛点，助力快速建立音名与五线谱位置的直觉联系。

------



## ✨ 项目亮点 (Core Features)

- **🎮 游戏化学习系统**：引入连击（Combo）加分机制，连续答对获得额外分数奖励。
- **🎼 双谱号覆盖**：支持高音谱号（G Clef）与低音谱号（F Clef）切换，精准覆盖从中央C到高/低加线的常用音域。
- **🧠 错题强化算法**：系统自动记录错误频次较高的音符，并在后续练习中以更高概率（约40%）出现，精准击破弱点。
- **📊 数据可视化**：集成 Chart.js，实时展示学习进度、正确率趋势与错题分布。
- **🎨 成人向审美**：采用深海蓝与金色的专业配色方案，拒绝低幼化，专为高效专注而设计。
- **📱 响应式布局**：完美适配 PC、平板与手机端，随时随地开启训练。

------



## 🛠️ 技术栈 (Tech Stack)

- **HTML5 & SVG**: 动态生成五线谱及音符图形。
- **Tailwind CSS**: 现代化的响应式界面布局。
- **Vanilla JavaScript (ES6+)**: 模块化开发，无外部框架依赖，极致加载速度。
- **Chart.js**: 学习数据统计图表展示。
- **LocalStorage API**: 实现本地化的练习记录与持久化配置。

------



## 📂 项目结构 (Project Structure)

codeText

```
/MelodyMaster
├── index.html              # 主页面入口
└── README.md
```

------



## 🚀 快速启动 (Quick Start)

由于本项目使用了浏览器原生的 **JavaScript Modules**，直接双击打开 .html 文件可能会触发浏览器的跨域安全限制（CORS）。建议通过以下方式运行：

### 方法 1：使用 VS Code Live Server (推荐)

1. 在 VS Code 中打开项目文件夹。
2. 安装 **Live Server** 插件。
3. 点击右下角的 Go Live 按钮。

### 方法 2：使用 Python 快速启动

在项目根目录下运行：

codeBash

```
python -m http.server 8000
```

然后在浏览器访问 http://localhost:8000。

------



## 🎹 核心规则说明 (Game Rules)

1. **评分机制**：
   - 正确：+10 分（进阶关卡 +15 分）。
   - 错误：-5 分（最低为 0 分）。
   - **连击奖励**：连续正确 5 次以上，触发阶梯式加分：20 + (连击数 - 5) * 5。
2. **解锁逻辑**：
   - 每关包含 10 道题目。
   - 得分达到 **80分** 即可解锁下一难度关卡。
3. **音理基准**：
   - 高音谱号：第二线 = G4 (中央 Sol)。
   - 低音谱号：第四线 = F3 (大字组 Fa)。

------



## 📈 后续规划 (Roadmap)

- 

- **Web MIDI 支持**：连接真实的电子琴键盘进行识谱对位。

- 

- **音频采样**：接入高保真钢琴音色库，实现听觉与视觉同步强化。

- 

- **自定义练习**：允许用户自定义音域范围进行专项突破。

- 

- **成就系统**：解锁“高音谱号大师”、“识谱王者”等勋章。

------



## 📝 开源协议 (License)

本项目采用 [MIT License](https://www.google.com/url?sa=E&q=LICENSE) 协议。您可以自由地使用、修改和分发。

------
## 项目图：
### 主界面
<img width="2139" height="1157" alt="image" src="https://github.com/user-attachments/assets/93fc5529-4e5c-4495-af8f-abe8a63856d7" />
### 已知五线谱音符选音名
<img width="1936" height="1134" alt="image" src="https://github.com/user-attachments/assets/fd1e148e-2ba2-4c9f-ad94-64984bbb2ae1" />
### 已知五线谱音名字选音符
<img width="2037" height="1167" alt="image" src="https://github.com/user-attachments/assets/81a3e2af-643f-418b-86d5-0473223ab242" />

**如果你觉得这个工具有帮助，欢迎给一个 ⭐️ Star！**
**如有任何建议，欢迎提交 Issue 或 Pull Request。**
