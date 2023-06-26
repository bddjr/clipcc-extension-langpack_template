# clipcc extension langpack template

Translate by <https://fanyi.baidu.com> , some content has been modified.  

> The author is not related to ClipTeam.  
> Only for scenarios that only require language files.  

***

## Implementation principle

Compress the code folder into a zip file.  
Main.js is only used to ensure that the language pack extension is successfully loaded.

***
## Packaging extensions in Windows 

Please pre install [bandizip](https://en.bandisoft.com/bandizip/),  
Then run the following command using powershell in this folder:  
```
./packaging.ps1
```

If you are unable to use this script because the system prohibits it from running, please open powershell with administrator privileges and run this command to allow the execution of the PS1 script:  
```powershell
set-ExecutionPolicy RemoteSigned
```

If you have already installed Python and Bandizip, you can also use this command to package:  
```
python packaging.py
```

***
## Packaging extensions in Linux

(To be verified for feasibility)  

Please pre install zip and Python3,  
Then run the following command in this folder:  
```
python3 packaging.py
```

***
## Test extension

Upload your own extension on the preview site to test it:  
<https://codingclip.com/editor/stable/>  
