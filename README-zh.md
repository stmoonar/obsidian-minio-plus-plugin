# Obsidian Minio Plus Plugin

### [English](./README.md) | 中文

这个仓库是从 [Obsidian Minio Uploader Plugin](https://github.com/seebin/obsidian-minio-uploader-plugin) fork 过来的，并添加了一些新功能。
- 支持基础路径
- 支持自定义域名

在未来，我会为这个插件添加更多功能。
- 支持删除文件

---

以下是 README.md 文件的原始内容。

将图片、视频、音频、PDF等文件上传到 Minio OSS 中，而不是复制到本地。减少本地磁盘占用大小，提高多设备之间同步的效率。

## 演示

![演示](./minio-uploader-demo.gif)

可以搭配 [Editing ToolBar](https://github.com/PKM-er/obsidian-editing-toolbar) 插件使用，将 minio 命令添加到操作栏中，可以点击选择文件后上传并添加到 Obsidian 文档中.

## 特性

- 支持拖拽文件到编辑器后直接上传到 Minio
- 支持粘贴文件到编辑器后直接上传到 Minio
- 支持命令选择文件后上传到 Minio, 配合 Editing ToolBar 插件使用更便捷

## 设置

首先，Minio 相关得配置都必须先正确配置后才可以正常使用：

> 提示：端口号为 Minio 的API数据访问端口号

- accessKey
- secretKey
- bucket
- endpoint
- port
- SSL

其次，需要在 Minio 控制台的 Bucket 设置中开启文件匿名访问能力，即通过URL可直接访问文件。

![设置](./minio-bucket-setting.png)

## 感谢

本项目从 [S3 image uploader](https://github.com/jvsteiner/s3-image-uploader) \ [Editing ToolBar](https://github.com/PKM-er/obsidian-editing-toolbar) 插件中获得灵感.
