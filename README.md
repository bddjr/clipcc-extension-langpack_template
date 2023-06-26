# clipcc extension langpack template

[If you want to read the English document, click here.](./README_EN.md)  

别针扩展语言包模板  

> 该作者与 ClipTeam 无关。  
> 仅用于只需要语言文件的场景。  

***

## 实现原理

将 code 文件夹压缩为 zip 文件。  
main.js 仅用于确保语言包扩展被成功加载。

***
## 在 Windows 操作系统打包扩展
请预先安装 [bandizip](https://cn.bandisoft.com/bandizip/) ，  
再在这个文件夹下使用 powershell 运行如下命令：  
```
./packaging.ps1
```

如果你因为系统禁止运行此脚本而无法使用，请以管理员权限打开 powershell ，然后运行这个命令以允许执行ps1脚本：
```powershell
set-ExecutionPolicy RemoteSigned
```

如果你已经安装了 python 与 bandizip ，那么也可以使用这个命令打包：
```
python packaging.py
```

***
## 在 Linux 操作系统打包扩展
（待验证可行性）  
请预先安装 zip 和 python3 ，  
再在这个文件夹下运行如下命令：  
```
python3 packaging.py
```

***
## 测试扩展
在预览站上传自己的扩展（不提交扩展审核），以测试自己的扩展：  
<https://codingclip.com/editor/stable/>  
