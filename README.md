# BlazePrompter

Windows上的轻量级软件提词器

**注意：该项目已停止支持。您将不会再收到更新，程序的漏洞也不会得到修复！**

## 如何使用

在Releases中下载BlazePrompterBuild.7z，解压后得BlazePrompterBuild文件夹，双击里BlazePrompter-<版本>.exe即可。

若提示缺少DLL或PrompterEdge插件启动后无反应（长时间白屏），请在Releases中下载runtime.7z，解压后运行文件夹下的VC_redist.x86.exe与MicrosoftEdgeWebview2Setup.exe（需要网络连接）

注：BlazePrompter不支持Windows 10以下版本的Windows系统

## 如何编译

1. 下载并安装[易语言](http://dywt.com.cn/pdown.htm)（建议5.95版本），推荐使用正版

2. 下载并配置好[VC2017静态编译链接器](https://d.125.la/thread-317-1-1.html)

3. clone本仓库到本地（需要安装Git）
   
   GitHub源：`git clone https://github.com/SBLZTech/BlazePrompter.git`

4. 解压项目根目录中的module.7z，得到module文件夹

5. 安装module文件夹中的编码转换支持库Ex、多线程支持库Ex、拖放支持库Ex

6. （如您要编译PDF插件）将module文件夹中的WebView2_Caller.dll移到项目的根目录中

7. 打开项目文件（如提示缺少模块，请在module文件夹中寻找到对应的模块）

8. 点击菜单栏上的编译-静态编译，选择要将编译出来的程序保存到的目录

## 版权信息

### 关于BlazePrompter

BlazePrompter 是自由软件, 在 AGPLv3 开源协议下发布, 同时附有附加条款.

    Copyright (C) 2020-2025 Soul-Blaze rod Studios.
    
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

附加条款 (依据 AGPLv3 开源协议第七条)
1.当您分发该程序的修改版本时, 您必须以一种合理的方式修改该程序的名称或版本号, 以示其与原始版本不同. (依据 AGPLv3, 7(c))
2.您不得移除该程序所显示的版权声明. (依据 AGPLv3, 7(b))

### 第三方组件

我们在遵守相关开源协议的情况下使用了下列第三方组件

1. 精易模块（[官网](https://ec.125.la)）

2. WebView2Caller（[GitHub开源地址](https://github.com/Admenri/WebView2Caller)）（[发布页](https://bbs.125.la/thread-14756782-1-2.html)）（[下载页](https://www.eyuyan.la/post/20925.html)）
   
        Copyright (C) 2022 Admenri.
        Licenced under Apache License 2.0