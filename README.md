
## Init Cocolatey and Git
Copy everything from the below window and paste into Command Promp (run as administrator)

```
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
choco install git

```


## Clone the repo
Clone the repo into your favorite subfolder 
```
git clone https://github.com/OliverDJ/windows-initial-setup.git
```

## Install

Install all packages
`choco install Packages.config`