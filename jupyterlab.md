# Jupyterlab

我写《自学是门手艺》的时候，就是用 Jupyterlab 写的 —— 因为在写作的过程中要确保所有的代码都是真正能够正确执行的。在没有 Jupyterlab 之前，写一本编程书籍出版之后，读者们几乎必然会遇到「压根就无法正确执行」的代码 —— 读者苦恼，作者其实更苦恼，谁想写出来卖出去的是垃圾呢？

用 Jupyterlab 还可以极方便地编写一些短程序，测试并使用 —— 不仅仅是 Python…… 不过，我在 Jupyterlab 上还真的基本上只用 Python。

-----
**⚠️ 注意**：[Jupyter-Desktop](https://github.com/jupyterlab/jupyterlab-desktop) 已经发行一段时间了，有人觉得它不稳定，我用了一段时间觉得没什么问题。

```bash
brew install --cask jupyterlab
```
手动安装的话，到官网 [Jupyter-Desktop](https://github.com/jupyterlab/jupyterlab-desktop) 下载相应操作系统的版本。以下以 MacOS 版本为例。

将下载文件解压缩，而后将 `JupyterLab.app` 拖入 `Applicatoins` 目录。

双击 `JupyterLab.app` 的图标打开程序，第一次打开的时候，程序界面底部有一行字：

![](images/jd-first-open.png)

在随后的对话框里，有一个 `Install` 按钮：

![](images/jd-install-bundled-environment.png)

Python 环境安装完毕之后，点击 `Apply & Restart` 重启 `JupyterLab`:

![](images/jd-be-installed.png)

再次打开的 `JupyterLab` 的首屏底部那行字就没有了…… 有必要的话，以后可以再 `Settings`（设置）里做更改：

![](images/jd-reopen.png)

比如，我可能回去设置 `Working directory`（默认的工作目录），以方便地管理我的 notebook 文件：

![](images/jd-settings-server.png)

至此，JupyterLab Desktop 就安装完了，开发环境安装彻底傻瓜化了，一键完成。

