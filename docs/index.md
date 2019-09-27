
pagetime:
title: EDA Wiki

# 欢迎来到 **EDA Wiki** ！ [![GitHub watchers](https://img.shields.io/github/watchers/pkuzjx/EDA-wiki.svg?style=social&label=Watch)](https://github.com/pkuzjx/EDA-wiki)  [![GitHub stars](https://img.shields.io/github/stars/pkuzjx/EDA-wiki.svg?style=social&label=Stars)](https://github.com/pkuzjx/EDA-wiki) 

**EDA wiki** 是关于EDA算法和开源工具的协作文档。

本项目受 [OI Wiki](https://OI-wiki.github.io/OI-wiki/) 的启发，在编写过程中参考了诸多资料，在此一并致谢。

本项目文档内容托管于 [GitHub](https://github.com/pkuzjx/EDA-wiki) 和 阿里云[CODE](https://code.aliyun.com/openbelt/eda-wiki)，主要使用 [GitHub Issues](https://github.com/pkuzjx/EDA-wiki/issues) / [CODE Issues](https://code.aliyun.com/openbelt/eda-wiki/issues) / [QQ](https://jq.qq.com/?_wv=1027&k=5MJhIUr) 进行交流沟通，期待你的加入。
Email: zhangjiaxi@pku.edu.cn, daitoto3@gmail.com, gluo@pku.edu.cn.

## Material color palette 颜色主题

### Primary colors 主色

> 默认为 `white` 

点击色块可更换主题的主色

<div id="color-button">
<button data-md-color-primary="red">Red</button>
<button data-md-color-primary="pink">Pink</button>
<button data-md-color-primary="purple">Purple</button>
<button data-md-color-primary="deep-purple">Deep Purple</button>
<button data-md-color-primary="indigo">Indigo</button>
<button data-md-color-primary="blue">Blue</button>
<button data-md-color-primary="light-blue">Light Blue</button>
<button data-md-color-primary="cyan">Cyan</button>
<button data-md-color-primary="teal">Teal</button>
<button data-md-color-primary="green">Green</button>
<button data-md-color-primary="light-green">Light Green</button>
<button data-md-color-primary="lime">Lime</button>
<button data-md-color-primary="yellow">Yellow</button>
<button data-md-color-primary="amber">Amber</button>
<button data-md-color-primary="orange">Orange</button>
<button data-md-color-primary="deep-orange">Deep Orange</button>
<button data-md-color-primary="brown">Brown</button>
<button data-md-color-primary="grey">Grey</button>
<button data-md-color-primary="blue-grey">Blue Grey</button>
<button data-md-color-primary="white">White</button>
</div>

<script>
  var buttons = document.querySelectorAll("button[data-md-color-primary]");
  Array.prototype.forEach.call(buttons, function(button) {
    button.addEventListener("click", function() {
      document.body.dataset.mdColorPrimary = this.dataset.mdColorPrimary;
      localStorage.setItem("data-md-color-primary",this.dataset.mdColorPrimary);
    })
  })
</script>

### Accent colors 辅助色

> 默认为 `red` 

点击色块更换主题的辅助色

<div id="color-button">
<button data-md-color-accent="red">Red</button>
<button data-md-color-accent="pink">Pink</button>
<button data-md-color-accent="purple">Purple</button>
<button data-md-color-accent="deep-purple">Deep Purple</button>
<button data-md-color-accent="indigo">Indigo</button>
<button data-md-color-accent="blue">Blue</button>
<button data-md-color-accent="light-blue">Light Blue</button>
<button data-md-color-accent="cyan">Cyan</button>
<button data-md-color-accent="teal">Teal</button>
<button data-md-color-accent="green">Green</button>
<button data-md-color-accent="light-green">Light Green</button>
<button data-md-color-accent="lime">Lime</button>
<button data-md-color-accent="yellow">Yellow</button>
<button data-md-color-accent="amber">Amber</button>
<button data-md-color-accent="orange">Orange</button>
<button data-md-color-accent="deep-orange">Deep Orange</button>
</div>

<script>
  var buttons = document.querySelectorAll("button[data-md-color-accent]");
  Array.prototype.forEach.call(buttons, function(button) {
    button.addEventListener("click", function() {
      document.body.dataset.mdColorAccent = this.dataset.mdColorAccent;
      localStorage.setItem("data-md-color-accent",this.dataset.mdColorAccent);
    })
  })

  // #758
  document.getElementsByClassName('md-nav__title')[1].click()
</script>
