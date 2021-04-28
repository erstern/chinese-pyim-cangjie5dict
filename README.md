Note: this file is auto converted from pyim-cangjie5dict.el by [el2org](https://github.com/tumashu/el2org), please do not edit it by hand!!!


# &#30446;&#24405;

1.  [pyim-cangjie5dict README](#orgd80525c)
    1.  [简介](#org726aae6)
    2.  [安装和使用](#orgf140b73)


<a id="orgd80525c"></a>

# pyim-cangjie5dict README


<a id="org726aae6"></a>

## 简介

pyim-cangjie5dict 是 pyim 的一个倉頡五代词库，修改自 RIME 项目。源于《五倉世紀》。


<a id="orgf140b73"></a>

## 安装和使用

1.  配置melpa源，参考：<http://melpa.org/#/getting-started>
2.  M-x package-install RET pyim-cangjie5dict RET
3.  在emacs配置文件中（比如: ~/.emacs）添加如下代码：
    
        (require 'pyim-cangjie5dict)
        (pyim-cangjie5dict-enable)
        (setq pyim-default-scheme 'cangjie)

