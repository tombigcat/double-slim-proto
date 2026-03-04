# 双人减脂 - 原型部署说明

## 📦 项目文件已准备好

文件位置：`/Users/tom/.openclaw/workspace/projects/减肥挑战/prototype/`

包含文件：
- `index.html` - 原型主文件（5个完整页面）
- `vercel.json` - Vercel配置文件

## 🚀 部署方案（二选一）

### 方案A：手动上传部署（最简单，2分钟）

1. 打开 https://vercel.com/tombigcats-projects
2. 点击 "Add New..." → "Project"
3. 选择 "Import Git Repository" 或 "Upload"
4. 如果选Upload：
   - 把 `prototype` 文件夹压缩成 zip
   - 直接拖拽上传
5. 点击 Deploy

### 方案B：GitHub自动部署（推荐，后续更新方便）

1. 在GitHub创建新仓库（如 `double-slim-proto`）
2. 把 `prototype` 文件夹内容push到仓库
3. 在Vercel选择 "Import Git Repository"
4. 选择刚创建的仓库，点击 Deploy

### 方案C：命令行部署（如果你会）

```bash
cd /Users/tom/.openclaw/workspace/projects/减肥挑战/prototype
vercel login
vercel --prod
```

---

## 📝 部署后访问地址

部署成功后会得到类似：
`https://double-slim-proto-xxxxx.vercel.app`

如果你想绑定到已有的域名 `fruitree-prototype-vsbv.vercel.app`，在Vercel项目设置里可以配置Domain。

---

## 🎯 原型包含的页面

访问原型后可以体验：
1. **首页** - 查看进行中的挑战
2. **发起挑战** - 创建新挑战
3. **挑战详情** - PK对比、进度条、曲线图
4. **每日打卡** - 记录体重、饮食、运动
5. **结果页** - 胜负判定、成就徽章
6. **个人页** - 战绩统计

所有页面都可以点击交互！
