# Mac 电脑删除自带英文，只保留一个输入法

1. 打开 `~/Library/Preferences/` 路径，找到 `com.apple.HIToolbox.plist` 文件并用 Xcode 软件打开。
2. 找到 `AppleEnabledInputSources`，删除 `KeyboardLayout Name U.S.` 这一项，然后保存。
![](https://i.imgur.com/oBdCPiO.png)

3. 重启电脑。
![I](https://i.imgur.com/8w2kib2.png)
