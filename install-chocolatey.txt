

powershell Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"



choco install -y fastcopy
choco install -y 7zip
choco install -y winrar
choco install -y explorerplusplus
choco install -y notepadplusplus
choco install -y sysinternals
choco install -y treesizefree
choco install -y crystaldiskinfo.portable


choco install -y anydesk-install
choco install -y googlechrome
choco install -y firefox

choco install -y adobereader
choco install -y pdfcreator
choco install -y javaruntime
choco install -y softether-vpn-client
choco install -y office365business

choco install -y reflect-free