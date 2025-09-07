# E志者协会维修手册

## 概览

这是E志者协会正在筹划的维修手册。

当前使用[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)构建。

当前，手册分为[电脑软件](docs/software/)、[电脑硬件](docs/hardware/)、[电器维修](docs/appliance/)三个部分。设想中，前两个部分由电脑部维护，第三个部分由电器部维护。

~~手册尚未部署到网站上。如果想要临时查看本文档，或者需要为本文档编写文章，可以遵循以下步骤。~~

现在可以使用[GitHub Pages](https://zjjncsn.github.io/EVA-manual/)预览本手册

## 编写指南

如果你是文章编写者，请遵循以下步骤以在本地启用预览。

1. 在电脑上部署Python环境，确保安装了`pip`，且已经添加进环境变量中

2. 运行以下命令：
```shell
pip install mkdocs-material
```
3. 下载本仓库，在仓库路径运行
```shell
mkdocs serve
```
4. 访问[localhost:8000](localhost:8000)即可看到文档的预览。

## 编写规范

请在对应部分的文件夹中新建文件，文件标题为`title.md`，请使用简洁的英文。

如果需要写内容相近的系列文章，可在对应部分中再新建文件夹。

用到次数较多的图片可以放置在[docs/assets/images/](docs/assets/images/)文件夹中。

如果一篇文章有较多图片需要插入，可在对应位置新建一个名为`title`的文件夹，里面新建一个名为`index.md`的文件，同时新建一个`images`文件夹。将需要插入的图片放在里面。（示例：[购机指南](docs/purchasing-guide/2025-1/)）

在编写完成后，你可以将文章添加至索引中。索引的具体位置：

根目录下的[mkdocs.yml](mkdocs.yml)文件中的`nav`字段。

如果你没有添加索引，可在Pull Requests时说明。

## 版权声明

© 2025 [E志者协会](https://zjueva.net). 本作品采用 CC BY-NC-SA 4.0 许可。