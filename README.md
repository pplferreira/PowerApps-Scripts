# PowerApps-cmdlets
Scripts desenvolvidos em PowerShell para facilitar a administração na Power Platform

Antes de executar verifique se as suas politicas estão aderentes:

#Verificar politicas
Get-ExecutionPolicy -List

#Setar Politicas
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser


Após essa verificação, você deverá instalar os módulos do PowerApps, recomendo que instale no escopo de usuário atual.

#verfificar modulos a instalar:

Install-Module -Name Microsoft.PowerApps.Administration.PowerShell -Scope CurrentUser

Install-Module -Name Microsoft.PowerApps.PowerShell -AllowClobber -Scope CurrentUser
