# Mac 电脑删除自带英文，只保留一个输入法

[![](https://img.shields.io/badge/Twitter-%E6%8E%A8%E7%89%B9-%231BA1F3)](https://twitter.com/qingmail) [![](https://img.shields.io/badge/Telegram-%E8%AE%A8%E8%AE%BA%E7%BE%A4-%2323A5E4)](https://t.me/V2EXPro) 

1. 打开 `~/Library/Preferences/` 路径，找到 `com.apple.HIToolbox.plist` 文件并用 Xcode 软件打开。
2. 找到 `AppleEnabledInputSources`，删除 `KeyboardLayout Name U.S.` 这一项，然后保存。
![](https://i.imgur.com/oBdCPiO.png)

3. 重启电脑。
![I](https://i.imgur.com/8w2kib2.png)
