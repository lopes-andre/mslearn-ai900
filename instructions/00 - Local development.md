## Desenvolvimento Local

Se você estiver trabalhando no seu computador local, você pode seguir estes passos abaixos para configurar o seu ambiente de desenvolvimento para trabalhar com os laboratórios.

### C++ Redistributable 
1. Baixa e instale o [Visual C++ Redistributable (x64)](https://aka.ms/vs/16/release/vc_redist.x64.exe) 

### Python e seus pacotes necessários 
1. Instale o [Python](https://www.python.org/downloads/)  
   - **Importante**: Selecione a opção de adicionar o Python como variável PATH e registrar a instalação como ambiente padrão de Python.
2. Após a instalação, abra o *Prompt de Comando* e entre o comando a seguir para instalar os pacotes necessários:

> pip install ipython jupyter matplotlib pillow requests azure-cognitiveservices-vision-computervision azure-cognitiveservices-vision-customvision azure-cognitiveservices-vision-face azure-cognitiveservices-language-textanalytics azure.cognitiveservices.speech azure_ai_formrecognizer 

### Visual Studio Code 
1. Se você ainda não tem o Visual Studio Code, [baixe aqui](https://code.visualstudio.com/Download). Após a instalação, inicie o Visual Studio Code e abra a aba de Extensões (CTRL+SHIFT+X), pesquise e instale a extensão **Python** da Microsoft.

2. No Visual Studio Code, abra um novo Terminal, digite **git clone https://github.com/lopes-andre/mslearn-ai900.git** e aperte *enter* para clonar este repositório. Se preferir clonar o repositório oficial da Microsoft (em Inglês), digite  **git clone https://github.com/MicrosoftLearning/mslearn-ai900** e *enter*.

