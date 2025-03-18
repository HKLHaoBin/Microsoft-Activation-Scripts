<p align="center"><img src="https://massgrave.dev/img/logo_small.png" alt="MAS Logo"></p>

<h1 align="center">微软激活脚本 (MAS)</h1>

<p align="center">开源的 Windows 和 Office 激活工具，包含 HWID、Ohook、TSforge、KMS38 和在线 KMS 激活方法，以及高级故障排除功能。</p>

<hr>

## 下载 / 如何使用？

### 方法 1 - PowerShell (Windows 8 及更高版本) ❤️

1. 打开 PowerShell（而不是 CMD）。为此，右键点击 Windows 开始菜单并选择 PowerShell 或 Terminal。
2. 复制并粘贴下面的代码，然后按回车键
请提供需要翻译的文本内容
irm https://get.activated.win | iex
请直接提供需要翻译的文本内容，我将按照要求进行翻译
或者，你可以使用以下方法（它将在未来被弃用。）
请提供需要翻译的文本内容
irm https://massgrave.dev/get | iex
请提供需要翻译的文本内容
3.   你会看到激活选项。选择 (1) HWID 进行 Windows 激活。选择 (2) Ohook 进行 Office 激活。
4. 这就是全部了。

---

### 方法 2 - 传统方式（适用于 Windows 7 及更高版本）

<details>
<summary>点击这里获取信息</summary>

1. 使用下方提供的链接下载文件。
`https://github.com/massgravel/Microsoft-Activation-Scripts/archive/refs/heads/master.zip`
或
`https://git.activated.win/massgrave/Microsoft-Activation-Scripts/archive/master.zip`
2.   右键点击下载的 zip 文件并解压
3. 在解压文件夹中，找到名为 `All-In-One-Version` 的文件夹
4.   运行名为 `MAS_AIO.cmd` 的文件
5.   您会看到激活选项，请按照屏幕上的指示进行操作。
6. 这就是全部了。

</details>

---

### 无法工作 ❓

- 如果您无法通过 PowerShell 方法启动 MAS，请参考上面列出的**方法 2**。
- 如果启动 MAS 时脚本显示任何错误，请检查以蓝色显示的任何故障排除步骤，并尝试遵循这些步骤。
- 如果您有任何问题，请随时通过 [here](https://massgrave.dev/troubleshoot) 与我们联系。

---

> [! 注意]
>
> - PowerShell 中的 IRM 命令从指定的 URL 下载脚本，IEX 命令则执行该脚本。
> - 在执行命令前务必双重检查 URL，并在手动下载文件时验证来源。
> - 请谨慎，因为有些人通过在 IRM 命令中使用不同的 URL 来传播伪装成 MAS 的恶意软件。
