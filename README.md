[![Actions Status](https://github.com/sxdxyxy/ctguthesis/workflows/build/badge.svg)](https://github.com/sxdxyxy/ctguthesis/actions)
[![Join the chat at https://gitter.im/ctguthesis/Lobby](https://badges.gitter.im/ctguthesis/Lobby.svg)](https://gitter.im/ctguthesis/Lobby)
[![GitHub downloads](https://img.shields.io/github/downloads/sxdxyxy/ctguthesis/total)](https://github.com/sxdxyxy/ctguthesis/releases)
[![GitHub commits](https://img.shields.io/github/commits-since/sxdxyxy/ctguthesis/latest)](https://github.com/sxdxyxy/ctguthesis/commits/master)
[![GitHub release](https://img.shields.io/github/v/release/sxdxyxy/ctguthesis)](https://github.com/sxdxyxy/ctguthesis/releases/latest)
[![CTAN](https://img.shields.io/ctan/v/ctguthesis)](https://www.ctan.org/pkg/ctguthesis)

# What's Ctguthesis?
**Ctguthesis** is an abbreviation of **C**hinas**T**hree**G**orges  **U**niversity **Thesis** LaTeX Template.

This package establishes a simple and easy-to-use LaTeX template for China Three Gorges dissertations, including general undergraduate research papers, masters theses, doctoral dissertations, and postdoctoral reports. An English translation of this README follows the Chinese below.

It includes a org template and manual to guide write in Emacs org-mode and plan their doctoral life.


# ctguthesis 是什么？
**Ctguthesis** 是 **China Three Gorges University **Thesis** LaTeX Template 的缩写。

此宏包旨在建立一个简单易用的三峡大学学位论文 LaTeX 模板，包括本科综合论文训练、硕士论文、博士论文以及博士后出站报告。

同时还包含一个Emacs org 的论文模版，和论文工作计划。(ctguthesissetup.org, ctguthesis.org)

# 文档
请[下载](https://github.com/sxdxyxy/ctguthesis/releases)模板，里面包括具体使用说明以及示例文档：

* 模板使用说明 (ctguthesis.pdf)
* 示例文档 (main.pdf)

# 下载
* 开发版：[GitHub](https://github.com/sxdxyxy/ctguthesis)

# 升级

## 手动更新
从 [GitHub](https://github.com/sxdxyxy/ctguthesis) 下载放入论文目录，执行命令（Windows 用户在文件夹空白处按 `Shift + 鼠标右键`，点击“在此处打开命令行窗口”）：

```shell
xetex ctguthesis.ins
```

即可得到 `ctguthesis.cls` 等模板文件。

# 提问
按推荐顺序排序：

* 先到 [FAQ](https://github.com/sxdxyxy/ctguthesis/wiki/FAQ) 看看常见问题
* [GitHub Issues](https://github.com/sxdxyxy/ctguthesis/issues)

# Makefile的用法

```shell
make [{all|thesis|spine|doc|clean|cleanall|distclean}]
```

## 目标
* `make thesis`    生成论文 main.pdf；
* `make spine`     生成书脊 spine.pdf；
* `make doc`       生成模板使用说明书 ctguthesis.pdf；
* `make all`       生成论文和书籍，相当于 `make thesis && make spine`；
* `make clean`     删除示例文件的中间文件（不含 main.pdf）；
* `make cleanall`  删除示例文件的中间文件和 main.pdf；
* `make distclean` 删除示例文件和模板的所有中间文件和 PDF。

---

# Documentation
Download and unzip the template. Specific usage documentation and examples can be found in the files below. At present, these documents are <b>only available in Chinese</b>:
* Template usage (ctguthesis.pdf)
* Template example (main.pdf)

# Downloads
* Developer version: [GitHub](https://github.com/sxdxyxy/ctguthesis)

# Updates

## Manual
Download the package from [GitHub](https://github.com/sxdxyxy/ctguthesis) to the root directory of your thesis, then execute the command (Windows users `Shift + right click` white area in the file window and click "Open command line window here" from the popup menu):

```shell
xetex ctguthesis.ins
```

You'll get `ctguthesis.cls` along with other template files.

# Reporting Issues
Please follow the procedure below:

* Check the [FAQ](https://github.com/sxdxyxy/ctguthesis/wiki/FAQ)
* [GitHub Issues](https://github.com/sxdxyxy/ctguthesis/issues)

# Makefile Usage

```shell
make [{all|thesis|spine|doc|clean|cleanall|distclean}]
```

## Targets
* `make thesis`    generate thesis main.pdf;
* `make spine`     generate book spine for printing spine.pdf;
* `make doc`       generate template documentation ctguthesis.pdf;
* `make all`       generate thesis and spine, same as `make thesis && make spine`;
* `make clean`     delete all examples' files (excluding main.pdf);
* `make cleanall`  delete all examples' files and main.pdf;
* `make distclean` delete all examples' and templates' files and PDFs.
