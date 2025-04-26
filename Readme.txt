Instruções:
Clone o repositório na sua máquina, abra o mesmo com o VSCode, depois, vá em configurações, digite settings.json e cole o conteúdo do arquivo settings lá.
Após isso abra o terminal e execute o comando abaixo:
#Para Instalar as Extensões:
Get-Content extensions.txt | ForEach-Object { code --install-extension $_ }
