本书的这个版本已转换为 LaTeX。
为了构建它，请确保您有一个 TeX 发行版，其中包含
`xelatex` 命令。 有了这个，你应该能够构建这本书
通过运行 `make`，它将克隆操作系统本身并构建这本书
到主目录中的 `book.pdf`。

图形是使用 `inkscape` 绘制的。

# 项目来源
[xv6-riscv-book](https://github.com/mit-pdos/xv6-riscv-book.git)

# 翻译工具
[MathTranslate](https://github.com/SUSYUSTC/MathTranslate.git)

# 项目编译
## 环境准备
### LaTeX 本地环境
#### mac

``` bash
brew install --cask mactex
```
#### other

[TeX Live](https://www.tug.org/texlive/quickinstall.html)

### Overleaf LaTeX 在线环境

[Overleaf](https://www.overleaf.com)


## 编译

``` bash
make
```

如果 LaTeX 本地环境已经准备好，会直接生成 book.pdf

使用在线环境 执行完 make 后打包上传到 overleaf，然后再编译即可

# contribution
由于是机器翻译，人工校对，难免有疏漏，大家可以在 github 项目下提 issue or pr ，只能说会尽快解决。

