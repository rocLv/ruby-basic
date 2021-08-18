# Install

首先安装conda：

教程参见：
[conda 安装教程](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)

下面以Mac OS为例：

直接下载PKG包安装最方便，我安装的是miniconda3.
[下载](https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.pkg)

安装后，默认的安装目录是`/opt/miniconda3`

在`.bashrc` 或者`.zshrc` 里面把以上路径加入PATH

`export PATH=$PATH:/opt/miniconda3/bin`

接下来安装`jupyter-notebook`:

```terminal
$ conda install -c conda-forge jupyterlab
```

安装后还需要安装Ruby内核：

`$ gem install iruby`

安装后注册：
`$ iruby register --force`

切换至工作目录, 然后启动`jupyter-notebook`:

`$ jupytor-lab`

命令行会自动打开浏览器。

添加了代码后，可以按`SHIFT + ENTER` 执行。
