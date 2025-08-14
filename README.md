# Comandos-para-reparar-Windows
Comandos destinados a reparação do Windows 


 ### Em todos os passos você precisa digitar no Prompt de Comando ou pelo PowerShell ou no Windows Terminal em modo com privilégios elevados para concluir estas tarefas, ou seja, em modo Administrador.

 ### COMANDOS DISM:

 #### DISM /Online /Cleanup-Image /CheckHealth 

 #### DISM /Online /Cleanup-Image /ScanHealth

 #### DISM /Online /Cleanup-Image /RestoreHealth

 ##### Após concluído reiniciar a máquina para aplicar as correções.

 ## COMANDO SCANNOW:

 #### SFC /scannow

 ##### Após concluído reiniciar a máquina para aplicar as correções.

 ## COMANDO DE VERIFICAÇÃO DE PARTIÇÃO:

 #### chkdsk /f /r

##### Confirme com “S” e em seguida “Enter” para agendar uma verificação de disco. Reinicie o equipamento e assim que concluir verifique se ficou de acordo



# Comandos para Baixar via winget 

## programas:
### 7zip
### Adobe Reader
### Google Chrome
### Mozila firefox
### Java 
### drive booster 12
winget install --id 7zip.7zip -e --accept-source-agreements --accept-package-agreements

winget install --id Google.Chrome -e --accept-source-agreements --accept-package-agreements

winget install --id Mozilla.Firefox -e --accept-source-agreements --accept-package-agreements

winget install --id Oracle.JavaRuntimeEnvironment -e --accept-source-agreements --accept-package-agreements

winget install --id Adobe.Acrobat.Reader.64-bit -e --accept-source-agreements --accept-package-agreements

winget install --id=IObit.DriverBooster -e




# Auto complit 

## ....





# Tabela Comandos Win + R

## .....


