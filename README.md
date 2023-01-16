
# Windows Initial Setup
## Install Cocolatey
Copy everything from the below window and paste into Command Prompt (run as administrator)

```
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```

## Install Git
Run the following command in Command Prompt (run as administrator)
```
choco install git
```
you may need to restart Command Prompt after the git installation

## Clone the repo
Clone the repo into your favorite subfolder

```
cd <path_to_favorite_folder> (e.g. cd C:\Users\Oliver\Documents)
```
Then
```
git clone https://github.com/OliverDJ/windows-initial-setup.git
```

## Install Packages
Install all packages
```
choco install Packages.config
```
