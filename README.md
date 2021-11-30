# Mac 电脑删除自带英文，只保留一个输入法

使用第三方输入法时，常遇到中文状态时却输出英文，来回切换多次很麻烦。

* 方法一：禁用第三方输入法切换英文，例如搜狗设置按键 - 状态切换 - 中英文 - 禁用快捷键，搜狗只输出中文，英文交给系统自带。
* 方法二：将自带的英文删除（步骤如下）。

[![](https://img.shields.io/badge/Telegram-%E8%AE%A8%E8%AE%BA%E7%BE%A4-%2323A5E4)](https://t.me/V2EXPro) 

1. 前往 `~/Library/Preferences/` 文件夹，找到 `com.apple.HIToolbox.plist` 文件并用 [Xcode](https://apps.apple.com/cn/app/xcode/id497799835?mt=12) 软件打开。
2. 找到 `AppleEnabledInputSources`，删除 `KeyboardLayout Name U.S.` 并保存。

![](https://i.imgur.com/oBdCPiO.png)

3. 重启电脑。

    > 注：如果删除失败，重复上面步骤，分别打开每个文件，删除所有包含 `KeyboardLayout Name U.S.` 的文件。

![I](https://i.imgur.com/JvzQHNH.png)
