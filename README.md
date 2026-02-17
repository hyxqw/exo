# GitHub 仓库创建与使用说明

## 一、注册 GitHub 账号

1. 访问 <a href="https://github.com/">https://github.com/</a>
2. 注册并登录你的账号

## 二、创建新仓库

1. 登录后，点击页面右上角的"+"号，选择 **New repository**。
2. 填写仓库名称（Repository name），例如：`my-first-repo`。
3. 可以填写描述（Description，选填）。
4. 选择公开（Public）或私有（Private）。
5. **建议勾选** Initialize this repository with a README。
6. 点击 **Create repository**。

## 三、使用仓库

### 方式一：使用网页界面操作
你可以直接在 GitHub 网页里添加文件、编辑、上传、删除等。

### 方式二：使用 Git 工具管理代码

1. **安装 Git**  
   参考：<a href="https://git-scm.com/">Git 官网下载</a>
2. **克隆仓库到本地**
   ```bash
   git clone https://github.com/你的用户名/仓库名.git
   ```
   例如：
   ```bash
   git clone https://github.com/hyxqw/my-first-repo.git
   ```
3. **在本地对文件进行修改后提交到远程仓库：**
   ```bash
   cd my-first-repo         # 进入仓库文件夹
   # 添加新文件并保存（如：echo "Hello World" > hello.txt）

   git add hello.txt        # 添加新文件到暂存区
   git commit -m "添加 hello.txt"   # 提交更改
   git push                 # 推送到GitHub远程仓库
   ```
4. **同步远程仓库的最新代码：**
   ```bash
   git pull
   ```

## 四、常见操作总结

- 查看仓库/管理成员/设置权限：在仓库右上角点击 Settings。
- Issues、Pull Requests 用于协作管理：适合团队开发。
- Actions 可以自动化构建、测试、部署。

## 五、仓库常见用途

- 个人代码管理与备份
- 参与开源项目
- 版本控制与分支管理
- 团队协作开发

---

如需详细图文操作步骤，请告知我你的具体需求或遇到的问题，我可以进一步指导！
