# Get my setup

## Scoop

```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
irm get.scoop.sh | iex
git clone https://github.com/jessiejs/sysconfig
cd sysconfig
scoop import export.json
```
