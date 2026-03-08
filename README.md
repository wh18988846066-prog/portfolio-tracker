# 📊 马克老王策略组合跟踪

一个实时跟踪富途牛牛组合持仓的网页应用。

## 🌐 在线访问

部署后访问地址：`https://你的用户名.github.io/portfolio-tracker/`

## 📁 文件说明

- `index.html` - 主页面文件
- `README.md` - 项目说明

## 🚀 部署步骤

### 1. 创建 GitHub 仓库

1. 登录 GitHub
2. 点击右上角 **+** → **New repository**
3. 仓库名称填：`portfolio-tracker`
4. 选择 **Public**（公开）
5. 点击 **Create repository**

### 2. 上传文件

在仓库页面：
1. 点击 **uploading an existing file**
2. 拖拽或选择 `index.html` 文件上传
3. 点击 **Commit changes**

### 3. 开启 GitHub Pages

1. 进入仓库的 **Settings** 标签
2. 左侧菜单点击 **Pages**
3. **Source** 选择 **Deploy from a branch**
4. **Branch** 选择 **main** / **master**，文件夹选 **/(root)**
5. 点击 **Save**
6. 等待几分钟，页面会显示访问链接

## 📈 功能特性

- ✅ 实时展示5个策略组合持仓
- ✅ 美股多头趋势策略
- ✅ A股多头趋势策略  
- ✅ 美股对冲策略
- ✅ 港股多头趋势策略
- ✅ A股ETF策略
- ✅ 调仓变化自动提醒
- ✅ 本地存储历史数据对比
- ✅ 自动刷新（每30秒）
- ✅ 响应式设计，支持手机访问

## 🔄 更新数据

点击页面底部的 **刷新数据** 按钮可手动更新持仓数据。

## 📝 注意事项

- 当前使用模拟数据展示
- 如需连接真实富途API，需要修改 `refreshData()` 函数中的 API 调用部分
- 由于浏览器跨域限制，直接调用富途API可能需要代理服务器

## 📱 预览

![预览图](screenshot.png)

---

Made with ❤️ by 马克老王
