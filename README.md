# Taro MSParis

基于 Taro 框架构建的时装衣橱项目演示。

> 原项目地址: [EasyTuan/taro-msparis](https://github.com/EasyTuan/taro-msparis)  
> 国内镜像: [easytuan/taro-msparis](https://gitee.com/easytuan/taro-msparis)

## 如何编译

### 环境要求

- Node.js >= 8.x
- npm 或 yarn

### 安装依赖

```bash
# 全局安装 Taro CLI（项目使用 1.2.2 版本）
npm install -g @tarojs/cli@1.2.2

# 安装项目依赖
npm install
```

### 开发模式

```bash
# 微信小程序开发
npm run dev:weapp

# 支付宝小程序开发
npm run dev:alipay

# 百度小程序开发
npm run dev:swan

# 字节跳动小程序开发
npm run dev:tt

# H5 开发
npm run dev:h5

# React Native 开发
npm run dev:rn
```

### 生产构建

```bash
# 微信小程序构建
npm run build:weapp

# 支付宝小程序构建
npm run build:alipay

# 百度小程序构建
npm run build:swan

# 字节跳动小程序构建
npm run build:tt

# H5 构建
npm run build:h5

# React Native 构建
npm run build:rn
```

### 其他命令

```bash
# 快速生成页面模板
npm run tep <文件名>
```

## Git 提交

### 初始化 Git 仓库（如果还没有）

```bash
# 初始化 Git 仓库
git init

# 添加远程仓库（请替换为你的仓库地址）
git remote add origin <your-repository-url>
```

### 提交代码

```bash
# 查看修改状态
git status

# 添加所有修改
git add .

# 或者添加指定文件
git add <file-path>

# 提交代码（请使用有意义的提交信息）
git commit -m "你的提交信息"

# 推送到远程仓库
git push origin <branch-name>
```

### 常用 Git 操作

```bash
# 查看提交历史
git log

# 创建新分支
git checkout -b <branch-name>

# 切换分支
git checkout <branch-name>

# 查看当前分支
git branch

# 合并分支
git merge <branch-name>

# 拉取远程更新
git pull origin <branch-name>
```

### 提交规范建议

建议使用清晰的提交信息格式：

- `feat: 添加新功能`
- `fix: 修复 bug`
- `docs: 更新文档`
- `style: 代码格式调整`
- `refactor: 代码重构`
- `test: 添加测试`
- `chore: 构建/工具变更`

## License

[MIT](LICENSE)
