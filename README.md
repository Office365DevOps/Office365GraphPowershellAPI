# Office365 Graph API PowerShell Module
> 作者：陈希章 时间：2017年7月1日

## 概述

这是我在写 [Office 365 开发概览](https://aka.ms/office365devguide) 时整理的一个 PowerShell 模块，它的主要用途是简化在 PowerShell 脚本中调用 Microsoft Graph API 的步骤，并且同时支持国际版和国内版Office 365。

## 如何使用

这个模块已经发布到微软官方的 Gallery 中，所以安装和使用它其实很简单，就跟其他的模块是没有区别的

首先，你需要安装它
> Install-Module -Name Office365GraphAPI

其次，这个模块带了两个主要的函数，分别是Get-Office365Token 和 Invoke-Office365GraphRequest，前者用来获取访问 Microsoft Graph 的令牌，后者用来执行真正的查询。

这两个函数的具体帮助，请使用 Get-Help Get-Office365Token 这样的方式了解详情。

我这里还写了一个专门的 PowerShell QuickStart，请参考
<https://github.com/Office365DevOps/PowerShellQuickStart>


## 源代码
这个模块的源代码，可以通过下面的地址访问到，如果大家遇到问题，也欢迎跟我联系
<https://github.com/chenxizhang/office365dev/tree/master/samples/graph-api-powershellmodule>
