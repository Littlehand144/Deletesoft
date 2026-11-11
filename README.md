Esse projeto foi feito pensando em você, isso mesmo, você usuário de windows que já não aguenta mais o consumo de memória RAM desnecessário e toda a invasão de privacidade (Ex. os prints de tela para o Windows Recovery), esse XML roda automaticamente durante a intalação do Winidows 10/11 e modifica o sistema removendo a maioria dos seviços microsoft desnecessários para o funcionamento do sistema, apenas o essencial, mas ainda terá a Microsoft Store caso queira baixar algum aplicativo Microsoft.

Automação e personalização da instalação do Windows 10/11 utilizando um arquivo XML. Inclui instalação automatizada, otimizações de desempenho, remoção de aplicativos pré-instalados (bloatware), configurações de privacidade, personalização visual e ajustes avançados do sistema por meio de scripts XML, Batch e PowerShell. Melhores detalhes das modificações abaixo:

Modificações do sistema:

- O Windows não enviará dados de diagnóstico, entrada personalizada ou localização para a Microsoft
- Contorne a verificação de requisitos do Windows 11 (TPM, Secure Boot, etc.)
- Usuario Local (conta Microsoft não necessária)
- Opção de Finalizar Tarefa direto na barra de tarefas
- Widgets desativados
- Windows Update pausado por tempo ilimitado
- Windows Update não reinicia o computador automaticamente
- Controle Inteligente de aplicativos desativado
- SmartScreen do Windows desativado
- System Recovery desativado
- Criptografia BitLocker desativado
- Startup Boost desativado
- Edge desinstalavel
- Teclas de Aderência desativadas


Serviços Microsoft Removidos:

- 3D Viewer
- Bing Search
- Clipchamp
- Copilot 
- Cortana
- Game Assist
- Internet Explorer
- Math Input Panel
- Mixed Reality
- Notepad
- OneNote
- Outlook
- People
- Recall
- Sniping Tool
- Steps Recorder
- Tips
- Wallet
- Windows Hello
- Windows Media Player
- Xbox Apps
- Family
- Get Help
- Mail and Calendar
- Media Features
- Movies and TV
- Office 365
- OneSync
- Paint
- Solitare Collection
- Sticky Notes
- To Do
- Weather
- Your Phone
- Dev Home
- Feedback Hub
- Handwriting (all languages)
- Speech (all languages)
- Maps
- News
- OneDrive
- Paint 3D
- Power Automate
- Quick Assist
- Skype
- Teams
- Voice Recorder
- WordPad


Serviços Microsoft Instalados:

- Camera
- Photos
- PowerShell 2.0
- PowerShell ISE
- Microsoft Terminal 

Atenção: O script formata automaticamente o disco 0 e desativa determinados recursos de segurança.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~# T U T O R I A L #~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
1. Antes de começar, você precisará de:

- Um pendrive com pelo menos 8 GB de capacidade.
- Uma imagem ISO oficial do Windows 10/11, **edição Pro**.
- O arquivo autounattend.xml disponível neste repositório.
- Um programa para criar o pendrive bootável: Rufus ( Recomendável ) ou Ventoy.
- Um computador compatível com inicialização UEFI.

2. Crie um pendrive bootável e baixe o Windows 10/11. Após finalizar, copie o arquivo autounattend.xml para a raiz do pendrive ( não coloque o arquivo XML dentro de uma pasta e não altere seu nome )
3. Reinicie o computador.
4. Acesse o menu de inicialização (Boot Menu), geralmente utilizando F12, F11, F8 ou Esc ( dependendo do fabricante ), selecione o pendrive em modo UEFI.
5. Aguarde o carregamento do instalador. Se o arquivo autounattend.xml for reconhecido corretamente, a instalação automatizada será iniciada.
6. Durante o processo, o Deletesoft executará as configurações definidas no arquivo XML, incluindo:

- Preparação e particionamento automático do disco.
- Instalação do Windows 10/11 Pro.
- Aplicação de configurações regionais (Brasil, PT-BR ABNT2, UTC-03:00).
- Remoção de aplicativos pré-instalados (bloatware).
- Ajustes de desempenho.
- Personalização da aparência do Windows.
- Configurações de privacidade e serviços.
- Execução de scripts PowerShell e Batch.

O computador poderá reiniciar automaticamente durante a instalação. Não remova o pendrive enquanto os arquivos de instalação ainda estiverem sendo utilizados.
