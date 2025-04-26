📥 1. Clone o repositório
Abra seu terminal e execute:
https://github.com/jonathan-beskow/configs-ide.git

🖥️ 2. Abra o projeto no VSCode
Inicie o Visual Studio Code.

Vá em Arquivo → Abrir Pasta... e selecione a pasta clonada.

⚙️ 3. Configure o settings.json
No VSCode, pressione Ctrl + Shift + P para abrir a paleta de comandos.

Digite "Preferences: Open Settings (JSON)" e selecione a opção.

Copie o conteúdo do arquivo settings.json do repositório.

Cole dentro do arquivo de configurações que foi aberto.

✅ Pronto! Suas configurações estarão aplicadas.

🛠️ 4. Instale as extensões recomendadas
No terminal do VSCode, execute o comando abaixo para instalar todas as extensões necessárias:

Get-Content extensions.txt | ForEach-Object { code --install-extension $_ }

Isso garantirá que seu ambiente esteja completo, padronizado e otimizado para o desenvolvimento!