# 三年级语文大冒险

一个可直接部署到 GitHub + Render 的手机端纯静态语文闯关游戏。

## 项目结构

```text
chinese-game-grade3-final/
├── index.html
├── README.md
└── assets/
    └── icon.svg
```

## GitHub 上传

1. 在 GitHub 新建仓库，例如 `chinese-game-grade3`。
2. 将项目中的全部文件上传到仓库。
3. 确认 `index.html` 位于仓库根目录。

## Render 部署

创建 **Static Site**：

- Branch：`main`
- Build Command：留空
- Publish Directory：`.`
- Start Command：留空

不需要 Node.js、数据库、环境变量或后端服务器。

## 功能

- 8 个语文主题关卡
- 每关 8 道选择题
- 生字词、课文理解、词语搭配、寓言、科普、传统文化、阅读理解
- 星星与金币奖励
- 关卡逐步解锁
- 错题本
- 每日挑战
- 浏览器自动保存学习记录
- 手机端自适应
- 无真实支付、无提现功能

## 本地打开

使用 Chrome 或 Edge 打开 `index.html` 即可运行。
