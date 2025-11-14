# FanImeHelpCode

Helpcodes for [MetasequoiaImeTsf](https://github.com/fanlumaster/MetasequoiaImeTsf).

For debug:

```shell
git clone https://github.com/fanlumaster/MetasequoiaImeHelpCode.git
Remove-Item "C:\Users\<username>\AppData\Local\MetasequoiaImeTsf\helpcode.txt" -Force
New-Item -ItemType SymbolicLink -Path "C:\Users\<username>\AppData\Local\MetasequoiaImeTsf\helpcode.txt" -Target ".\MetasequoiaImeHelpCode\helpcode.txt"
```

e.g.

```shell
git clone https://github.com/fanlumaster/MetasequoiaImeHelpCode.git
Remove-Item "C:\Users\SonnyCalcr\AppData\Local\MetasequoiaImeTsf\helpcode.txt" -Force
New-Item -ItemType SymbolicLink -Path "C:\Users\SonnyCalcr\AppData\Local\MetasequoiaImeTsf\helpcode.txt" -Target "C:\Users\SonnyCalcr\EDisk\CppCodes\IMECodes\MetasequoiaImeHelpCode\helpcode.txt"
```
