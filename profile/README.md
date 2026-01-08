# SZU视觉所1009 实验室 · 项目与代码平台

欢迎来到 **1009实验室 GitHub Organization**。  
本组织用于集中管理实验室课程实验、科研项目与技术 Demo。
管理员：陈劲铧 电话：13662644116 邮箱：1005741898@qq.com

ddd
## 📂 项目总目录

👉 **所有项目的统一入口在此：**  
🔗 https://github.com/ORG_NAME/lab-project-index

> 项目目录由管理员维护，请勿在本页面直接添加学生项目。

---
## 📌 使用说明（请所有成员阅读）

- 每位同学 **仅维护一个或多个属于自己的仓库**
- ❌ 禁止修改、提交他人仓库代码
- ✅ 每个项目必须包含：
  - `README.md`（项目说明）
  - 可运行代码或 Demo
- 项目成果请通过 **Release / Demo 文件 / Pages** 方式展示
- 未录取及需要保密的工作请不要上传。
---
## 项目提交说明
- Step 1：查收邀请邮件（最常见方式）
  - 向管理员提出申请，让他邀请你进入组织。
  - 打开你的注册邮箱。
  - 找到一封来自 GitHub 的邮件
  - 标题类似：You’ve been invited to join the SZUCV1009 organization
  - 点击 Join @SZUCV1009。
- Step 2：创建属于你自己的仓库
  - 在https://github.com/orgs/SZUCV1009/repositories 这个页面中，点击New repository
  - 填写 仓库名称 Description
  - Visibility：选 Public。勾选✅ Add a README file。
- Step 3：上传文件
  - 网页上传：进入仓库，点击 Add file，点击 Upload files，拖拽你的代码文件 / 文件夹，点击 Commit changes。
  - 使用 Git:
```cmd
git clone https://github.com/SZUCV1009/你的仓库名.git
cd 你的项目文件夹
# 放入代码文件
git add .
git commit -m "Initial commit"
git push
```


## 🧑‍💻 项目规范（摘要）

每个项目仓库建议包含以下结构：

```text
project-name/
├── README.md        # 项目说明（必需）
├── src/             # 源代码
├── demo/            # 演示文件（视频 / 图片 / 可执行文件）
└── docs/            # 相关文档（可选）

