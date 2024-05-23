# Typora + PicGo + GitHub 图床

本仓库用于存储 Typora 笔记中的图片，旨在提高图片管理和加载效率。通过 Typora、PicGo 和 GitHub 的结合，实现快速、高效的图片上传和引用。

## 功能特点

- **快速上传**：使用 PicGo 实现图片的快速上传和管理。
- **免费托管**：利用 GitHub 免费存储和托管图片。
- **版本控制**：GitHub 提供版本控制，方便图片的管理和回溯。

## 安装和配置指南

### 1. 安装 Typora

请访问 [Typora 官网](https://typora.io/) 下载并安装适用于你的操作系统的 Typora。

### 2. 安装 PicGo

请访问 [PicGo GitHub 仓库](https://github.com/Molunerfinn/PicGo) 下载并安装 PicGo。

### 3. 配置 PicGo

1. **打开 PicGo**：
   - 启动 PicGo 应用程序。

2. **设置 GitHub 图床**：
   - 进入设置页面，选择“图床设置”。
   - 选择“GitHub”作为图床类型，并填写以下信息：
     - **仓库名**：`yourusername/your-repository`
     - **分支名**：`main`或其他默认分支名
     - **Token**：你的 GitHub 个人访问令牌（PAT），请参考 [创建 GitHub Token](https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token) 获取你的令牌。

3. **测试上传**：
   - 在 PicGo 中测试上传图片，确保配置正确。

### 4. 配置 Typora

1. **打开 Typora**：
   - 启动 Typora 应用程序。

2. **设置图片上传服务**：
   - 进入 `偏好设置` -> `图像` 选项卡。
   - 勾选 `上传图片`，选择 `PicGo (app)` 作为上传服务。

## 使用方法

1. **上传图片**：
   - 在 Typora 中插入图片时，图片会自动通过 PicGo 上传到你的 GitHub 仓库。

2. **访问图片**：
   - 上传的图片将存储在 GitHub 仓库中，可以通过如下 URL 访问：
     ```
     https://raw.githubusercontent.com/yourusername/your-repository/main/path/to/your/image.png
     ```
   - 示例：
     ```markdown
     ![示例图片](https://raw.githubusercontent.com/yourusername/your-repository/main/images/example.png)
     ```

## 安全性建议

- **最小权限**：为你的 GitHub Token 设置最小必要权限，只勾选 `repo` 权限。
- **不要公开 Token**：不要将你的 GitHub Token 公开在任何地方，尤其是代码仓库中。
- **定期更新**：定期更新你的 GitHub Token，确保安全。

## 许可证

本仓库使用 MIT 许可证。详细信息请参见 [LICENSE](LICENSE) 文件。

## 贡献

如果你有任何建议或改进，欢迎提交 Issue 或 Pull Request。

## 联系方式

如有问题或需要帮助，请在本仓库提交 Issue。

