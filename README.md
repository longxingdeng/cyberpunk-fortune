# 赛博论命 - Cyber Fortune

一个充满科技感的现代化命理分析网站，融合传统八字命理学与现代AI技术。

## 🌟 功能特色

### 🔮 赛博知命
- **八字排盘**：精确计算年月日时四柱
- **紫薇斗数**：传统紫薇斗数星盘分析
- **真太阳时修正**：根据出生地进行时间修正
- **AI命理分析**：生成详细的命理分析提示词
- **十神分析**：深入解读十神关系
- **大运流年**：预测人生各阶段运势

### ✨ 赛博起名
- **八字五行分析**：根据生辰八字分析五行需求
- **智能起名算法**：结合三才五格和五行理论
- **自定义用字**：支持指定喜欢的字进行起名
- **多重评分**：综合考虑音韵、寓意、五行配置
- **性别适配**：针对男女不同性别优化推荐

### 📊 赛博测名
- **五格数理**：计算天格、人格、地格、外格、总格
- **三才配置**：分析天人地三才五行关系
- **综合评分**：多维度评估姓名质量
- **详细分析**：提供改进建议和优化方向
- **八字匹配**：结合生辰八字分析姓名适配度

### 💕 赛博合婚
- **生肖配对**：传统十二生肖相配分析
- **八字合婚**：深度分析双方八字匹配度
- **五行互补**：分析双方五行相生相克关系
- **十神配对**：解读双方十神关系和谐度
- **年龄匹配**：考虑年龄差异对感情的影响
- **改进建议**：提供具体的关系改善建议

## 🎨 设计特色

### 科技感UI
- **赛博朋克风格**：深色主题配合霓虹色彩
- **粒子背景**：动态粒子效果营造科技氛围
- **发光动画**：文字和按钮的发光效果
- **流畅过渡**：页面切换和元素动画

### 响应式设计
- **移动端适配**：完美支持手机和平板设备
- **自适应布局**：根据屏幕尺寸自动调整
- **触摸友好**：优化移动端交互体验

## 🛠️ 技术架构

### 前端技术
- **HTML5**：语义化标签和现代Web标准
- **CSS3**：Flexbox/Grid布局，动画效果
- **JavaScript ES6+**：模块化编程，面向对象设计
- **Particles.js**：粒子背景效果库

### 核心算法
- **八字计算**：传统干支历法计算
- **紫薇斗数**：星曜排盘和宫位分析
- **姓名学**：三才五格数理计算
- **合婚算法**：多维度匹配度分析

## 📁 项目结构

```
Cyberpunk Fortune/
├── index.html              # 主页面
├── css/
│   ├── style.css          # 主样式文件
│   └── animations.css     # 动画效果
├── js/
│   ├── main.js            # 主交互逻辑
│   ├── bazi-calculator.js # 八字计算模块
│   ├── ziwei-calculator.js# 紫薇斗数模块
│   ├── name-calculator.js # 起名测名模块
│   ├── marriage-calculator.js # 合婚模块
│   └── particles-config.js# 粒子效果配置
└── README.md              # 项目说明
```

## 🚀 快速开始

1. **克隆项目**
   ```bash
   git clone https://github.com/longxingdeng/cyber-fortune.git
   cd Cyberpunk Fortune
   ```

2. **启动服务**
   - 直接用浏览器打开 `index.html`
   - 或使用本地服务器（推荐）：
   ```bash
   # 使用Python
   python -m http.server 8000
   
   # 使用Node.js
   npx serve .
   ```

3. **访问网站**
   打开浏览器访问 `http://localhost:8000`

## 🌐 部署到Cloudflare Pages

### 方法一：GitHub自动部署（推荐）

1. **准备GitHub仓库**
   ```bash
   # 确保代码已推送到GitHub
   git add .
   git commit -m "准备部署到Cloudflare Pages"
   git push origin main
   ```

2. **登录Cloudflare Dashboard**
   - 访问 [Cloudflare Dashboard](https://dash.cloudflare.com/)
   - 登录您的Cloudflare账户

3. **创建Pages项目**
   - 在左侧菜单中点击 "Pages"
   - 点击 "Create a project"
   - 选择 "Connect to Git"

4. **连接GitHub仓库**
   - 选择 "GitHub"
   - 授权Cloudflare访问您的GitHub账户
   - 选择仓库：`longxingdeng/cyber-fortune`

5. **配置构建设置**
   - **项目名称**：`cyber-fortune`（或自定义名称）
   - **生产分支**：`main`
   - **构建命令**：留空（纯静态网站）
   - **构建输出目录**：`/`（根目录）
   - **根目录**：`/`（根目录）

6. **完成部署**
   - 点击 "Save and Deploy"
   - 等待部署完成（通常1-3分钟）
   - 获得您的网站URL：`https://your-project-name.pages.dev`

### 方法二：手动上传

1. **准备部署文件**
   - 确保项目包含 `_headers` 和 `_redirects` 配置文件
   - 这些文件已包含在项目中，用于优化性能和SEO

2. **手动部署**
   - 在Cloudflare Pages中选择 "Upload assets"
   - 将整个项目文件夹拖拽上传
   - 等待部署完成

### 部署后配置

1. **自定义域名**（可选）
   - 在Pages项目设置中添加自定义域名
   - 配置DNS记录指向Cloudflare

2. **环境变量**（如需要）
   - 在项目设置中添加环境变量
   - 当前项目为纯前端，暂不需要

3. **自动部署**
   - 每次推送到GitHub main分支会自动触发部署
   - 可在Cloudflare Dashboard中查看部署状态

### 部署优势

- ✅ **全球CDN**：快速访问速度
- ✅ **免费SSL**：自动HTTPS证书
- ✅ **自动部署**：GitHub集成，推送即部署
- ✅ **版本管理**：支持回滚到历史版本
- ✅ **预览部署**：分支预览功能
- ✅ **无限带宽**：免费计划包含无限带宽

## 💡 使用说明

### 赛博知命使用流程
1. 选择性别
2. 输入出生年月日时
3. 选择出生地区（用于真太阳时修正）
4. 点击"开始分析"
5. 查看八字排盘和大运信息
6. 复制AI分析提示词到ChatGPT等AI助手获取详细分析

### 赛博起名使用流程
1. 输入姓氏
2. 选择性别和出生信息
3. 可选：输入自定义用字
4. 点击"智能起名"
5. 查看推荐姓名列表和评分

### 赛博测名使用流程
1. 输入完整姓名
2. 选择性别和出生信息
3. 点击"开始测名"
4. 查看综合评分和详细分析

### 赛博合婚使用流程
1. 分别输入男女双方信息
2. 点击"开始合婚"
3. 查看匹配度分析和改进建议

## 🔧 自定义配置

### 修改主题色彩
在 `css/style.css` 中修改CSS变量：
```css
:root {
    --primary-color: #00d4ff;    /* 主色调 */
    --secondary-color: #ff0080;  /* 辅助色 */
    --accent-color: #00ff88;     /* 强调色 */
}
```

### 调整粒子效果
在 `js/particles-config.js` 中修改粒子参数：
```javascript
"particles": {
    "number": {
        "value": 80,  // 粒子数量
        "density": {
            "enable": true,
            "value_area": 800
        }
    }
}
```

## 📝 注意事项

1. **算法精度**：本项目中的命理算法为简化版本，仅供娱乐和学习使用
2. **AI分析**：需要配合ChatGPT等AI助手使用生成的提示词获取详细分析
3. **浏览器兼容**：建议使用现代浏览器（Chrome、Firefox、Safari、Edge）
4. **移动端**：在移动设备上使用时建议横屏操作以获得更好体验

## 🤝 贡献指南

欢迎提交Issue和Pull Request来改进项目：

1. Fork 项目
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 🙏 致谢

- 感谢传统命理学文化的传承
- 感谢开源社区的技术支持
- 感谢所有贡献者的努力

---

**免责声明**：本项目仅供娱乐和学习使用，不构成任何形式的人生指导建议。请理性对待命理分析结果。
