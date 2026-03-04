# Paylincoffee 网站结构说明

## 网站概述
这是一个仿制 stumptowncoffee.com 的静态 HTML 网站，品牌名称为 Paylincoffee，域名为 paylin.top。

## 文件结构

```
paylin/
├── index.html          # 主页
├── coffee.html         # 产品页面
├── subscribe.html      # 订阅页面
├── about.html          # 关于我们页面
├── quiz.html           # 咖啡测验页面
├── styles.css          # 共享样式表
├── paylin-logo.PNG     # Logo 图片
└── WEBSITE_INFO.md     # 本说明文件
```

## 页面说明

### 1. index.html - 主页
- Hero 横幅区域（Worth Repeating 主题）
- 特色功能展示（免费送货、道德采购等）
- 精选产品推荐（3 个主打产品）
- 订阅优惠信息
- 咖啡测验引导
- 品牌故事简介
- 完整页脚导航

### 2. coffee.html - 产品页面
- 产品筛选功能（全部、混合、单一产地、低因、限量版）
- 9 款产品展示：
  * Peru TIMBUYACU MARAGOGYPE（最佳销售）
  * Hair Bender®
  * Holler Mountain
  * Ethiopia Yirgacheffe（新品）
  * Colombia Huila
  * Guatemala Antigua
  * Sumatra Mandheling
  * Decaf Colombia
  * Kenya AA（限量版）
- 每款产品包含：名称、风味描述、价格、加入购物车按钮

### 3. subscribe.html - 订阅页面
- 订阅优惠信息（20% 折扣）
- 运作流程说明（4 步骤）
- 三种订阅方案：
  * Starter - $18/月（1 袋/月）
  * Regular - $34/月（2 袋/月，最受欢迎）
  * Premium - $65/月（4 袋/月）
- 优惠套装：
  * Starter Bundle - $40（2 袋）
  * Premium Bundle - $76（4 袋）
  * Gift Bundle - $50（礼品装）
- 订阅优势说明

### 4. about.html - 关于我们
- 品牌故事
- 数据统计（50+ 合作农场、20+ 国家、100% 道德贸易、10K+ 客户）
- 核心价值观（直接贸易、可持续发展、质量第一、社区）
- 合作农民介绍（3 位农民）
- 领导团队（4 位成员）
- 行动号召

### 5. quiz.html - 咖啡测验
- 交互式 5 问测验
- 问题包括：
  1. 冲泡方式
  2. 风味偏好
  3. 咖啡浓度
  4. 单一产地 vs 混合
  5. 饮用频率
- 进度条显示
- 个性化产品推荐
- 15% 折扣优惠
- 重测功能

### 6. styles.css - 共享样式
- 全局样式定义
- 响应式设计（适配移动端）
- 统一的配色方案（咖啡色系：#c49a6c）
- 可复用组件样式

## 设计特点

### 配色方案
- 主色：#1a1a1a（深黑）
- 强调色：#c49a6c（咖啡金）
- 背景色：#f9f9f9（浅灰）
- 渐变：#f5f0eb → #e8e0d5（暖色调）

### 品牌元素
- Logo: https://cf.aibomart.com/paylin/paylin-logo.PNG
- 网站名称：Paylincoffee
- 域名：paylin.top

### 响应式设计
- 适配桌面、平板、手机
- 移动端汉堡菜单（简化版）
- 灵活的网格布局
- 触摸友好的按钮大小

### 交互效果
- 悬停动画
- 平滑过渡
- 购物车图标
- 动态按钮状态

## 导航结构

```
首页 (index.html)
├── Coffee (coffee.html)
├── Subscribe (subscribe.html)
├── Quiz (quiz.html)
└── About (about.html)
```

所有页面的导航栏保持一致，确保用户体验统一。

## 页脚链接

### Shop
- All Coffee → coffee.html
- Subscriptions → subscribe.html
- Bundles → subscribe.html
- Merchandise → #

### Learn
- Brewing Guides → #
- Coffee 101 → #
- Our Farmers → about.html
- Sustainability → #

### About
- Our Story → about.html
- Cafés → #
- Careers → #
- Contact → #

### Support
- FAQ → #
- Shipping → #
- Returns → #
- Wholesale → #

## 使用说明

1. 直接在浏览器中打开 `index.html` 查看网站
2. 所有页面都已链接，可以点击导航浏览
3. 测验页面包含完整的 JavaScript 交互功能
4. 图片使用 emoji 和渐变色块代替（可后续替换为真实产品图片）

## 后续优化建议

1. 添加真实产品图片
2. 集成购物车功能（需要 JavaScript/后端）
3. 添加联系表单
4. 集成社交媒体链接
5. 添加 SEO 元标签
6. 优化加载速度
7. 添加分析代码

## 技术栈
- HTML5
- CSS3（Flexbox、Grid）
- 原生 JavaScript（quiz 页面）
- 无外部依赖，纯静态网站
