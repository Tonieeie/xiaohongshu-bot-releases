<div align="center">

[English](#english) | [简体中文](#chinese)

# XHS Growth Pro

The ultimate automation and analytics tool for Xiaohongshu creators.

[![Official Website](https://img.shields.io/badge/Official_Website-Visit_Now-red?style=for-the-badge&logo=googlechrome&logoColor=white)](https://xiaohongshu-bot-server.onrender.com)
[![Download App](https://img.shields.io/badge/Download_App-Latest_Release-blue?style=for-the-badge&logo=github)](https://github.com/Tonieeee/xiaohongshu-bot-releases/releases)

</div>

---

<a name="english"></a>

## English Guide

### Table of Contents

- [Installation](#installation)
- [Getting Started](#getting-started)
- [Features](#features)
  - [Auto Warm-Up Engine](#1-auto-warm-up-engine)
  - [Analytics Dashboard](#2-analytics-dashboard)
  - [Industry Analysis & Viral Content Generation](#3-industry-analysis--viral-content-generation)
  - [Sensitive Word Detection](#4-sensitive-word-detection)
  - [My Membership](#5-my-membership)
  - [Settings](#6-settings)
- [Troubleshooting](#troubleshooting)

---

### Installation

#### Step 1: Create Your Account

1. Navigate to our official website: **[https://xiaohongshu-bot-server.onrender.com](https://xiaohongshu-bot-server.onrender.com)**.
2. Click **"Register"** (立即注册) or **"Start Growth"** (立即开始增长) on the homepage.
3. Fill in your **Email**, **Username**, and **Password**, then submit the form.
4. Open your email inbox and find the verification email from us. Click the verification link to activate your account.

> [!IMPORTANT]
> Remember your username and password. You will need them to log in to the desktop application.

#### Step 2: Download the Application

1. Navigate to the **Download Center** on our website, or go directly to our [GitHub Releases](https://github.com/Tonieeee/xiaohongshu-bot-releases/releases) page.
2. Choose the executable file compatible with your device:

| Platform | Download File | Notes |
| :--- | :--- | :--- |
| **Windows** | `xhs-bot-desktop-setup.exe` | Standard Windows installer. |
| **Mac (M1/M2/M3/M4)** | `xhs-bot-desktop-mac-arm64.dmg` | For Apple Silicon Macs. |
| **Mac (Intel)** | `xhs-bot-desktop-mac-x64.dmg` | For older Intel-based Macs. |

3. Once the download is complete, run the installer and follow the on-screen instructions.
4. Make sure you have **Google Chrome** or **Microsoft Edge** installed on your computer, as the application requires a browser engine to operate.

---

### Getting Started

#### Step 1: Log In to the Application

1. Open the **XHS Growth Pro** application.
2. Enter the **Username** and **Password** you created during registration.
3. Click **"Initialize Session"** to connect to the server.

#### Step 2: Connect Your Xiaohongshu Account

Before the bot can interact on your behalf, you need to link your Xiaohongshu account via QR code login.

1. On the dashboard, click **"Login Now"** or **"Check Auth"**.
2. A browser window will open displaying the **first QR code**.
3. Open the **Xiaohongshu app** on your phone and scan the QR code to log in.
4. Wait for the page to automatically redirect to the **Creator Center**.
5. A **second QR code** will appear. Scan this code as well to complete Creator Center authentication.
6. Wait for the application to confirm success and close the browser window automatically.

> [!WARNING]
> Do not close the automated browser window during the login process. Let it complete on its own.

---

### Features

#### 1. Auto Warm-Up Engine

**Tab Name:** 自动养号

The core feature of XHS Growth Pro. The Auto Warm-Up Engine automates account nurturing by intelligently browsing, liking, bookmarking, and commenting on posts related to your target topic. This builds your account's weight and visibility on the platform.

**How to Use:**

1. **Enter a Target Topic** — Type a keyword that represents your niche (e.g., "Skincare", "Travel", "Fashion") into the main input field.
2. **Configure Behaviors** — Toggle and adjust the probability for each automated action:
   - **Auto Like** — Adjust the probability (0–100%) of liking posts.
   - **Auto Bookmark** — Adjust the probability (0–100%) of bookmarking posts.
   - **Auto Comment** — Adjust the probability (0–100%) of leaving comments.
3. **Choose a Comment Style** — Select how the AI writes comments on your behalf:
   - **Friendly** — Natural, casual comments with emojis.
   - **Professional** — Insightful, expert-toned comments.
   - **Casual** — Humorous and relaxed comments.
   - **Custom** *(VIP only)* — Write your own prompt to control exactly how comments are generated. Free users receive 1 trial.
4. **Start the Mission** — Click **"Commence Mission"** to launch the bot.
5. **Monitor Progress** — Watch real-time activity in the **Live Activity Terminal** and track total posts viewed via the counter in the header bar.
6. **Stop Anytime** — Click **"Abort Mission"** to safely stop the bot.

> [!WARNING]
> Do not close the automated browser window while the bot is running.

---

#### 2. Analytics Dashboard

**Tab Name:** 数据中心

A comprehensive data dashboard that pulls your account's performance metrics directly from the Xiaohongshu Creator Center. Visualize your growth and content performance at a glance.

**How to Use:**

1. Navigate to the **Analytics** tab from the sidebar.
2. Click **"Refresh"** to fetch the latest data. The system will:
   - Launch a headless browser
   - Securely log in to the Creator Center
   - Intercept and process your analytics data
3. View your performance across four sections:

   - **Funnel of Truth** — Tracks your traffic funnel from Exposure → Views → Interactions, showing drop-off and engagement rates at each stage.
   - **Viral Potential Gauge** — Displays key performance indicators including Click-Through Rate (CTR), Completion Rate, and Engagement Rate.
   - **Growth Engine** — Monitors account growth metrics such as Profile Visits, Follower Conversion Rate, and Net Follower Growth.
   - **Production Consistency** — Tracks your content output including Average Views Per Post, Total Posts Published, and the Video vs. Image ratio.

4. Use the **Period Selector** to switch between 7-day and 30-day views.
5. Optionally view the **Raw JSON** data for advanced analysis.

**Tracked Metrics (12 total):** Exposure, Views, Likes, Comments, Bookmarks, Shares, Unfollows, Net Growth, New Followers, Cover CTR, Video Completion Rate, and Home Profile Visits.

---

#### 3. Industry Analysis & Viral Content Generation

**Tab Name:** 行业分析 & 爆款生成

A powerful research and content creation tool. Enter any keyword and the system will analyze top-performing posts in that niche, then generate an in-depth industry report and ready-to-publish viral content notes using AI.

**How to Use:**

1. Navigate to the **Industry Analysis** tab from the sidebar.
2. **Enter a keyword** related to your industry or niche (e.g., "Skincare", "Fitness", "Home Decor").
3. Click **"Start Analysis"** to begin. The system will scrape top-performing posts filtered by most likes within the past week.
4. Once complete, two outputs are generated:

   **Industry Report** — A comprehensive market analysis covering:
   - Industry Overview (行业概况)
   - Trending Topics (热门趋势)
   - User Persona (用户画像)
   - Viral Content Formulas (爆款公式)
   - Competitive Landscape (竞争格局)
   - Actionable Tips (温馨提示)

   **Viral Content Notes** — 3 AI-generated posts modeled after real top-performing content, complete with:
   - Optimized titles
   - Full post content
   - Relevant hashtags
   - One-click copy to clipboard

> [!NOTE]
> Free users receive **3 free analysis trials**. VIP members enjoy **unlimited** analyses.

---

#### 4. Sensitive Word Detection

**Tab Name:** 敏感词检测

Before publishing any content on Xiaohongshu, run it through the Sensitive Word Detector to identify and remove banned words, advertising violations, and platform-restricted terms. This helps protect your account from penalties or content removal.

**How to Use:**

1. Navigate to the **Content Check** tab from the sidebar.
2. **Paste or type your content** into the text input area.
3. Click **"Scan"** to analyze the text. The system checks against 500+ sensitive words across 12 categories.
4. Review the results:
   - Each detected word is highlighted and categorized by risk level:
     - **High Risk** (Red) — Likely to trigger content removal.
     - **Medium Risk** (Amber) — May limit content visibility.
     - **Low Risk** (Blue) — Minor concerns, worth reviewing.
   - A detailed table shows each word's category, risk level, and suggested replacement.
5. **Fix issues** using the available actions:
   - **Replace** — Swap a word with a suggested safe alternative.
   - **Convert to Traditional Chinese** — A common workaround for borderline terms.
   - **Delete** — Remove the word entirely.
   - **Custom Replacement** — Enter your own replacement text.
6. Use **Bulk Actions** for efficiency:
   - Replace All Matches
   - Convert All to Traditional Chinese
   - Delete All Sensitive Words
   - Clear Text
7. Once the text shows **"All Clear"**, click **Copy** to copy the cleaned text and publish with confidence.

---

#### 5. My Membership

**Tab Name:** 我的会员

View your current membership tier and understand what features are available to you.

**Membership Tiers:**

| Feature | Basic (Free) | VIP Premium |
| :--- | :---: | :---: |
| Auto Warm-Up Engine | Available | Available |
| Comment Styles (Friendly, Professional, Casual) | Available | Available |
| Custom Comment Style | 1 Trial | Unlimited |
| Industry Analysis & Viral Content | 3 Trials | Unlimited |
| Analytics Dashboard | Available | Available |
| Sensitive Word Detection | Available | Available |
| Professional Prompt Engineering Support | — | Available |

To upgrade to VIP, navigate to the **My Membership** tab and follow the upgrade instructions.

---

#### 6. Settings

**Tab Name:** 系统设置

Configure your application preferences.

**Available Settings:**

- **Language** — Switch between English and Chinese (中文).
- **Browser Engine** — Select which browser the bot uses for automation:
  - **Microsoft Edge** (Default on Windows) — Built-in on all Windows machines.
  - **Google Chrome** (Recommended for stability) — Requires Chrome to be installed.
- Click **"Save"** to apply your changes.

---

### Troubleshooting

| Problem | Solution |
| :--- | :--- |
| Browser won't open | Make sure **Google Chrome** or **Microsoft Edge** is installed on your computer. |
| Bot shows logout notification | Click **"Log Out"** in the bottom-left corner and log in again to refresh your session. |
| Application freezes | Close the application completely and restart it. |
| Connection error | Check your internet connection and server status. |
| QR code not loading | Ensure you have a stable internet connection and try again. |
| Session expired during Industry Analysis | Re-scan the QR code to refresh your Xiaohongshu session. |

> [!TIP]
> If you encounter persistent issues, try logging out and logging back in. This refreshes both your app session and Xiaohongshu authentication.

---

<br>

<a name="chinese"></a>

## 中文指南

### 目录

- [安装指南](#安装指南)
- [快速开始](#快速开始)
- [功能介绍](#功能介绍)
  - [自动养号引擎](#1-自动养号引擎)
  - [数据中心](#2-数据中心)
  - [行业分析与爆款生成](#3-行业分析与爆款生成)
  - [敏感词检测](#4-敏感词检测)
  - [我的会员](#5-我的会员)
  - [系统设置](#6-系统设置)
- [常见问题](#常见问题)

---

### 安装指南

#### 第一步：创建账户

1. 访问我们的官方网站：**[https://xiaohongshu-bot-server.onrender.com](https://xiaohongshu-bot-server.onrender.com)**。
2. 点击首页上的 **"立即注册"** 或 **"立即开始增长"** 按钮。
3. 填写您的 **电子邮箱**、**用户名** 和 **密码**，然后提交注册表单。
4. 打开您的电子邮箱，找到我们发送的验证邮件，点击验证链接以激活您的账户。

> [!IMPORTANT]
> 请牢记您的用户名和密码，登录桌面应用程序时需要使用。

#### 第二步：下载应用程序

1. 前往我们网站的 **下载中心**，或直接访问 [GitHub Releases](https://github.com/Tonieeee/xiaohongshu-bot-releases/releases) 页面。
2. 选择与您设备兼容的安装文件：

| 平台 | 下载文件 | 说明 |
| :--- | :--- | :--- |
| **Windows** | `xhs-bot-desktop-setup.exe` | 标准 Windows 安装程序。 |
| **Mac (M1/M2/M3/M4)** | `xhs-bot-desktop-mac-arm64.dmg` | 适用于 Apple Silicon 芯片的 Mac。 |
| **Mac (Intel)** | `xhs-bot-desktop-mac-x64.dmg` | 适用于旧款 Intel 芯片的 Mac。 |

3. 下载完成后，运行安装程序并按照屏幕提示完成安装。
4. 请确保您的电脑已安装 **Google Chrome** 或 **Microsoft Edge** 浏览器，应用程序需要浏览器引擎才能运行。

---

### 快速开始

#### 第一步：登录应用程序

1. 打开 **XHS Growth Pro** 应用程序。
2. 输入您注册时创建的 **用户名** 和 **密码**。
3. 点击 **"Initialize Session"** 连接服务器。

#### 第二步：连接您的小红书账户

在机器人开始工作之前，您需要通过扫码登录来关联您的小红书账户。

1. 在主界面上，点击 **"Login Now"** 或 **"Check Auth"** 按钮。
2. 系统将打开一个浏览器窗口，显示 **第一个二维码**。
3. 打开手机上的 **小红书 App**，扫描该二维码完成登录。
4. 等待页面自动跳转至 **创作中心**。
5. 屏幕上将出现 **第二个二维码**，请再次扫描以完成创作中心认证。
6. 等待应用程序确认成功后，浏览器窗口会自动关闭。

> [!WARNING]
> 登录过程中请勿关闭自动打开的浏览器窗口，请让流程自行完成。

---

### 功能介绍

#### 1. 自动养号引擎

**标签名称：** 自动养号

XHS Growth Pro 的核心功能。自动养号引擎通过智能浏览、点赞、收藏和评论与您目标话题相关的笔记，来自动培养您的账号权重和平台可见度。

**使用方法：**

1. **输入目标话题** — 在主输入框中输入代表您领域的关键词（例如："护肤"、"旅游"、"穿搭"）。
2. **配置自动行为** — 开关并调节每种自动操作的触发概率：
   - **自动点赞** — 调节点赞概率（0–100%）。
   - **自动收藏** — 调节收藏概率（0–100%）。
   - **自动评论** — 调节评论概率（0–100%）。
3. **选择评论风格** — 选择 AI 代替您撰写评论的风格：
   - **友好风格** — 自然随意，带表情符号。
   - **专业风格** — 有见地的专家评论。
   - **轻松风格** — 幽默轻松的评论。
   - **自定义风格** *（仅限 VIP）* — 自己编写提示词，精确控制评论生成方式。免费用户可试用 1 次。
4. **启动任务** — 点击 **"Commence Mission"** 启动机器人。
5. **监控进度** — 在 **实时活动终端** 中查看实时操作日志，并通过顶部栏的计数器追踪已浏览的笔记数量。
6. **随时停止** — 点击 **"Abort Mission"** 安全停止机器人。

> [!WARNING]
> 机器人运行期间，请勿关闭自动打开的浏览器窗口。

---

#### 2. 数据中心

**标签名称：** 数据中心

一个全面的数据面板，直接从小红书创作中心获取您的账户表现数据，让您一目了然地了解增长情况和内容表现。

**使用方法：**

1. 在侧边栏中点击 **数据中心** 标签。
2. 点击 **"刷新"** 获取最新数据。系统将自动：
   - 启动无头浏览器
   - 安全登录创作中心
   - 截取并处理您的分析数据
3. 通过四个板块查看您的表现：

   - **流量漏斗 (Funnel of Truth)** — 追踪您的流量漏斗：曝光 → 阅读 → 互动，展示各阶段的流失率和互动率。
   - **爆款潜力指标 (Viral Potential)** — 展示关键指标，包括点击率 (CTR)、完播率和互动率。
   - **增长引擎 (Growth Engine)** — 监控账号增长数据，包括主页访问量、粉丝转化率和净增粉丝数。
   - **创作稳定性 (Production Consistency)** — 追踪内容产出，包括篇均阅读量、已发布笔记总数、视频与图文比例。

4. 使用 **时间选择器** 切换 7 天或 30 天视图。
5. 可选查看 **原始 JSON 数据** 进行高级分析。

**追踪的指标（共 12 项）：** 曝光数、阅读数、点赞数、评论数、收藏数、分享数、取关数、净增长、新增粉丝、封面点击率、视频完播率、主页访问量。

---

#### 3. 行业分析与爆款生成

**标签名称：** 行业分析 & 爆款生成

一款强大的调研和内容创作工具。输入任意关键词，系统将分析该领域中表现最佳的笔记，然后利用 AI 生成深度行业报告和可直接发布的爆款笔记。

**使用方法：**

1. 在侧边栏中点击 **行业分析** 标签。
2. **输入关键词**（例如："护肤"、"健身"、"家居装饰"）。
3. 点击 **"开始分析"**。系统将抓取近一周内按点赞数排序的热门笔记。
4. 分析完成后，将生成两部分内容：

   **行业报告** — 全面的市场分析，涵盖：
   - 行业概况
   - 热门趋势
   - 用户画像
   - 爆款公式
   - 竞争格局
   - 温馨提示（实用建议）

   **爆款笔记** — 3 篇 AI 生成的笔记，以真实爆款内容为模板，包含：
   - 优化后的标题
   - 完整的笔记内容
   - 相关话题标签
   - 一键复制功能

> [!NOTE]
> 免费用户可使用 **3 次免费分析**，VIP 会员享受 **无限次** 分析。

---

#### 4. 敏感词检测

**标签名称：** 敏感词检测

在小红书发布内容之前，使用敏感词检测工具扫描您的文案，识别并移除违禁词、广告违规用语和平台限制词汇。这有助于保护您的账号免受处罚或内容下架。

**使用方法：**

1. 在侧边栏中点击 **敏感词检测** 标签。
2. **粘贴或输入您的文案** 到文本输入区域。
3. 点击 **"扫描"** 分析文本。系统将对照 500+ 敏感词、涵盖 12 个类别进行检测。
4. 查看检测结果：
   - 每个检测到的词语都会高亮显示，并按风险等级分类：
     - **高风险**（红色）— 极有可能导致内容被删除。
     - **中风险**（橙色）— 可能导致内容限流。
     - **低风险**（蓝色）— 轻微问题，建议检查。
   - 详细表格展示每个词语的类别、风险等级和建议替换词。
5. 使用以下操作 **修复问题**：
   - **替换** — 用建议的安全词替换敏感词。
   - **转换为繁体字** — 对边界词汇的常见规避方法。
   - **删除** — 直接移除该词。
   - **自定义替换** — 输入您自己的替换文本。
6. 使用 **批量操作** 提高效率：
   - 替换所有匹配项
   - 全部转换为繁体字
   - 删除所有敏感词
   - 清空文本
7. 当文本显示 **"全部通过"** 后，点击 **复制** 即可复制清理后的文案并放心发布。

---

#### 5. 我的会员

**标签名称：** 我的会员

查看您当前的会员等级以及可用功能。

**会员等级对比：**

| 功能 | 基础版（免费） | VIP 高级版 |
| :--- | :---: | :---: |
| 自动养号引擎 | 可用 | 可用 |
| 评论风格（友好、专业、轻松） | 可用 | 可用 |
| 自定义评论风格 | 1 次试用 | 无限次 |
| 行业分析与爆款生成 | 3 次试用 | 无限次 |
| 数据中心 | 可用 | 可用 |
| 敏感词检测 | 可用 | 可用 |
| 专业提示词工程支持 | — | 可用 |

如需升级 VIP，请前往 **我的会员** 标签页，按照升级指引操作。

---

#### 6. 系统设置

**标签名称：** 系统设置

配置您的应用程序偏好设置。

**可用设置项：**

- **语言** — 在 English（英文）和 中文 之间切换。
- **浏览器引擎** — 选择机器人用于自动化操作的浏览器：
  - **Microsoft Edge**（Windows 默认）— Windows 系统自带浏览器。
  - **Google Chrome**（推荐，稳定性更好）— 需要提前安装 Chrome。
- 点击 **"保存"** 应用您的更改。

---

### 常见问题

| 问题 | 解决方案 |
| :--- | :--- |
| 浏览器无法打开 | 请确保电脑已安装 **Google Chrome** 或 **Microsoft Edge**。 |
| 机器人显示登出通知 | 点击左下角的 **"Log Out"** 按钮，重新登录以刷新会话。 |
| 应用程序卡死 | 完全关闭应用程序后重新启动。 |
| 连接错误 | 检查您的网络连接和服务器状态。 |
| 二维码无法加载 | 确保网络连接稳定，然后重试。 |
| 行业分析时提示会话过期 | 重新扫描二维码以刷新您的小红书会话。 |

> [!TIP]
> 如果遇到持续性问题，请尝试退出登录后重新登录，这将同时刷新应用会话和小红书认证。

---

<div align="center">
  <p>Need more help? Contact your system administrator for support.</p>
  <p>需要更多帮助？请联系系统管理员获取支持。</p>
</div>
