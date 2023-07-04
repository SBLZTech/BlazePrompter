# EasyPrompter

一个轻量级的软件提词器

## 如何使用

在Releases中下载EasyPrompterBuild.7z，解压后得到EasyPrompterBuild文件夹，双击里面的EasyPrompter-<版本>.exe即可

若使用PDF插件时长时间白屏，请运行文件夹下的MicrosoftEdgeWebview2Setup.exe（需要网络连接）

## 如何编译

1. 下载并安装[易语言](http://dywt.com.cn/pdown.htm)（建议5.93版本），推荐使用正版

2. （可选）下载并安装[易IDE视觉库](https://bbs.125.la/thread-14672340-1-1.html)，并启用助手中的“智能编译”插件，启用插件的“手动执行静态编译后执行下方配置”、“优化编译程序”、“突破内存限制”，并在“编译后执行命令行”中填入`{p}upx.exe --lzma {f}{h}`（可选） 

3. 下载并配置好[静态编译链接器](https://bbs.125.la/thread-25-1-1.html)（推荐使用VC6链接器）

4. clone本仓库到本地（需要安装Git）
   
   GitHub源：`git clone https://github.com/SBLZsoft/EasyPrompter.git`
   
   GitLab源：`git clone https://gitlab.com/SBLZsoft/EasyPrompter.git`

5. 解压项目根目录中的module.7z，得到modules文件夹

6. （如您要编译PDF插件）将module文件夹中的WebView2_Caller.dll移到项目的根目录中

7. 打开项目文件（如提示缺少模块，请在moudle文件夹中寻找到对应的模块）
   
   对应的文件名：
   
   EasyPrompter本体：EasyPrompter.e
   
   PDF插件：EasyPrompter-PDFPlugin.e
   
   屏幕标注插件非我方开发，您可到[Ink-Canvas仓库](https://github.com/WXRIW/Ink-Canvas)中了解详情

8. 点击菜单栏上的编译-静态编译，选择要将编译出来的程序保存到的目录

## 如何参与贡献

Issues、Discussion请到GitHub中提出

Merge Requests请到GitLab中提出，我们不接受GitHub的Pull Requests

注意：对GitHub平台的代码所做的任何更改都将在与GitLab仓库下一次同步时被清空！

## 版权信息

### 关于EasyPrompter

EasyPrompter 是自由软件, 在 AGPLv3 开源协议下发布, 同时附有附加条款.

附加条款 (依据 AGPLv3 开源协议第七条)
1.当您分发该程序的修改版本时, 您必须以一种合理的方式修改该程序的名称或版本号, 以示其与原始版本不同. (依据 AGPLv3, 7(c))
2.您不得移除该程序所显示的版权声明. (依据 AGPLv3, 7(b))

    Copyright (C) 2020-2023 Soul-Blaze rod Studios.
    
    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    any later version.
    
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU Affero General Public License for more details.
    
    You should have received a copy of the GNU Affero General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.

### 第三方组件

我们在遵守相关开源协议的情况下使用了下列第三方组件

1. Ink-Canvas（[GitHub开源地址](https://github.com/WXRIW/Ink-Canvas)）
   
        Licensed under GPLv3

2. 精易模块（[官网](https://ec.125.la)）

3. WebView2Caller（[GitHub开源地址](https://github.com/Admenri/WebView2Caller)）（[发布页](https://bbs.125.la/thread-14756782-1-2.html)）（[下载页](https://www.eyuyan.la/post/20925.html)）
   
        Copyright (C) 2022 Admenri.
        Licenced under Apache License 2.0