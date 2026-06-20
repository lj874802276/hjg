# 惠家沟村官网

## 项目简介

陕西省宝鸡市千阳县城关镇惠家沟村官方静态展示网站，纯前端静态页面（HTML + CSS + JavaScript），无后端依赖，部署于 Cloudflare Pages，用于村庄风貌展示、村务公示、乡村介绍等内容展示。

## 项目架构

- **前端技术**：原生 HTML5 / CSS3 / JavaScript
- **部署方式**：Cloudflare Pages 静态网页托管
- **仓库分支**：main
- **访问地址**：（部署后填写）

## 本地运行方式

1. 克隆仓库到本地

```bash
git clone <你的仓库地址>.git
```

2. 进入项目文件夹，直接双击打开 `index.html` 即可本地预览页面

3. 修改页面文件后，执行命令同步至远端仓库

```bash
git add .
git commit -m "更新页面内容"
git push origin main
```

## Cloudflare Pages 部署说明

1. 登录 [Cloudflare Dashboard](https://dash.cloudflare.com/)，进入 **Pages**
2. 点击【创建项目】→【连接到 Git】
3. 选择你的 Git 提供商（GitHub / GitLab），授权并选择本仓库
4. 配置构建设置：
   - **框架预设**：None
   - **构建命令**：（留空，纯静态站点无需构建）
   - **构建输出目录**：`/`
5. 点击【保存并部署】，等待部署完成
6. 后续代码推送到仓库后，Cloudflare Pages 会自动重新部署

## 目录说明

```
hjg/
├── index.html        # 网站首页入口
├── css/
│   └── style.css     # 页面样式文件
├── js/
│   └── main.js       # 交互脚本文件
├── assets/           # 村庄图片、素材资源
└── README.md         # 项目说明文档
```

## 功能模块

1. 村庄基础概况介绍
2. 乡村风光图片展示
3. 村务信息公示板块
4. 便民服务指引
5. 联系我们板块

## 补充说明

1. 本项目为纯静态页面，仅支持展示功能，无留言、后台管理等交互后端功能；
2. Cloudflare Pages 支持自动部署，代码推送到仓库后会自动重新构建并发布；
3. 内容仅用于乡村公益展示，禁止用于商业营销、违规资讯发布。
