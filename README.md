# 欢迎来到 **EDA Wiki**！


# to-do list
## 内容
- [x] 简介(intro/)
- [ ] 设计综合(synthesis/)
- [ ] 测试与验证(verification/)
- [ ] 分析与建模(analysis/)
- [ ] 硅智权(sip/)

## 其他

- [ ] 服务器、域名
- [ ] 评论功能
- [ ] 开源协议
- [ ] Google Analysis功能
- [ ] logo图片

# 部署
本项目目前采用 [MkDocs](https://github.com/mkdocs/mkdocs) 部署。

```bash
git clone https://github.com/daitoto/EDA-wiki.git --depth=1
cd EDA-wiki
# 安装 mkdocs
pip3 install -U -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple/
# 使用OI-wiki的自定义主题（不是必须执行）
chmod +x ./scripts/build.sh && ./scripts/build.sh

# 两种方法（选其一即可）：
# 1. 运行一个本地服务器，访问 http://127.0.0.1:8000 可以查看效果
mkdocs serve -v

# 2. 在 site 文件夹下得到静态页面
mkdocs build -v

# 获取 mkdocs 的命令行工具的说明（解释了命令和参数的含义）
mkdocs --help

```

* * *

## 版权声明

<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />
除特别注明外，项目中除了代码部分均采用<a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/deed.zh"> (Creative Commons BY-SA 4.0) 知识共享署名 - 相同方式共享 4.0 国际许可协议</a> 及附加的 [The Star And Thank Author License](https://github.com/zTrix/sata-license) 进行许可。

换言之，使用过程中您可以自由地共享、演绎，但是必须署名、以相同方式共享、分享时没有附加限制，  
而且需要为 GitHub 仓库点赞（Star）。

而如果你想要引用这个 GitHub 仓库，可以使用如下的 bibtex：

```
@misc{edawiki,
  author = {EDA Wiki Team},
  title = {EDA Wiki},
  year = {2019},
  publisher = {GitHub},
  journal = {GitHub Repository},
  howpublished = {\url{https://github.com/daitoto/EDA-wiki}},
}
```

* * *

## 鸣谢

本项目受 [OI Wiki](https://OI-wiki.github.io/OI-wiki/) 的启发，在编写过程中参考了诸多资料，在此一并致谢。


