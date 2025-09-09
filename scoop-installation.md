```powershell
iwr -useb get.scoop.sh | iex
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
scoop install hugo
hugo version