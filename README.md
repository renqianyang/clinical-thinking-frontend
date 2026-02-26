# 临床思维训练系统 - 前端

纯静态 HTML 前端页面，无需构建。

## 文件说明

- `index.html` - 登录页面
- `teacher-dashboard.html` - 教师工作台
- `student-dashboard.html` - 学生中心

## 本地运行

```bash
# 使用任意静态服务器
npx serve . -p 3000

# 或使用 Python
python3 -m http.server 3000
```

然后访问 http://localhost:3000

## 部署到 Render

1. 创建 GitHub 仓库
2. 上传这些文件
3. 在 Render 创建 Static Site
4. 设置发布目录为根目录

## 默认账号

- 教师: teacher / teacher123
- 学生: student / student123
