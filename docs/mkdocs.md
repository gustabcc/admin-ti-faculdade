# MKDocs

MkDocs é um gerador de sites estáticos rápido, simples e absolutamente lindo, voltado para a construção de documentação de projetos. Os arquivos de origem da documentação são escritos em Markdown e configurados com um único arquivo de configuração YAML.

## Instalação do MKDocs

Para instalar o MKDocs é necessário ter instalado em sua máquina Python e Pip, caso queira saber se em sua máquina tem os dois itens citados anteriormente, basta abrir o terminal e executar os seguintes comandos:

- Para Python: `python --version`
- Para Pip: `pip --version`

Caso apareça as versões dos elementos, significa que você já os possui instalados, caso aconteca o contrário, basta instala-los.

### Instalação Para Usuários Windows

- Acesse o site oficial do [Python](https://www.python.org/downloads/).
- Baixe o instalador específico para o seu sistema.
- Execute o instalador e clique em install now quando finalizar o download.
- A partir da versão 3.4 do Python, o pip já vem instalado.

### Instalação Para Usuário Linux

- Abra o terminal e execute
  `sudo apt update`
  `sudo apt upgrade`
- Instale o python e o pip
  `sudo apt install python3 python3-pip`
- Agora você tem ambos instalados no seu sistema.

### Próximos Passos

Agora que você já tem o necessário para utilizar o mkdocs, crie um diretório para utilizar como projeto.

#### Primeiro Passo

Execute como administrador o PowerShell e execute o seguinte comando: `pip install mkdocs`. Após instalar o mkdocs, entre no seu diretório usando o vscode ou uma IDE de seu gosto e abra o terminal da IDE.

#### Segundo Passo

No terminal, execute o seguinte comando `mkdocs new **"nome do programa"**`, isso criará a pasta executável do projeto, após isso, entre na pasta criada.

#### Terceiro Passo

Use o comando `mkdocs serve` para inicializar um servidor local da aplicação, se inicializar, significa que está tudo certo

### Caso Queira Saber Mais Sobre Outras Coisas do MKDocs

Caso queira saber mais sobre MKDocs e estilização, basta entrar no site oficial do [MKDocs](https://www.mkdocs.org/) e pesquisa sobre. É possível achar maneiras de estilizar o MKDocs e criar algumas funcionalidades a mais usando toda a documentação disponível no site.
