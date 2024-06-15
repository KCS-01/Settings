# Chocolatey

## Install with PowerShell

### 정책 변경설정

```sh
Get-ExecutionPolicy

# If Restrited

Set-ExecutionPolicy AllSigned
Set-ExecutionPolicy Bypass -Scope Process
```

### 설치

```sh
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

### 확인

```sh
choco
```
