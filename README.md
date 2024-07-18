# Git/Github
![NPM](https://img.shields.io/npm/l/react)

# Descrição

Git é um sistema de controle de versão distribuído que permite a rastrear mudanças no código-fonte durante o desenvolvimento de software. Criado por Linus Torvalds, Git facilita a colaboração entre desenvolvedores, o gerenciamento de versões e a recuperação de histórico de alterações. 

GitHub é uma plataforma de hospedagem de código baseada na web que usa Git para controle de versão. Oferece uma série de recursos para colaboração e gerenciamento de projetos.

## Principais Características do Git
- Controle de Versão Distribuído: Cada desenvolvedor possui uma cópia completa do repositório, incluindo seu histórico, o que possibilita trabalhar offline e colaborar de forma descentralizada.
- Branching e Merging: Permite criar ramificações (branches) para desenvolver funcionalidades separadas e depois mesclá-las (merge) ao branch principal.
- Registro de Histórico: Armazena um histórico detalhado de todas as alterações feitas no código, facilitando a revisão e a recuperação de versões anteriores.
- Eficiência e Performance: Proporciona um desempenho rápido e eficiente para operações de controle de versão, mesmo em grandes projetos.

## Principais Características do GitHub
- Repositórios Remotos: Hospeda repositórios Git na nuvem, permitindo o acesso e a colaboração em projetos de qualquer lugar.
- Interface Web: Oferece uma interface gráfica para gerenciar repositórios, visualizar o histórico de commits, revisar pull requests e mais.
- Colaboração: Facilita a colaboração por meio de pull requests, issues (questões), e discussões, permitindo que os desenvolvedores revisem e discutam alterações antes de integrá-las.
- Integração e Automação: Suporta integração com ferramentas de CI/CD (Integração Contínua e Entrega Contínua) e outras plataformas para automação de testes e deploys.

Git e GitHub são amplamente utilizados no desenvolvimento de software para gerenciamento de código, colaboração eficiente e controle de versões, tornando o processo de desenvolvimento mais organizado e ágil.


### Iniciar novo packet com GIT na máquina 
```bash
git init
```

### Definir as configurações do usuário
```bash
git config --local user.name Diego
```
```bash
git config --local user.email diego@email.com.br
```

### Baixar os arquivos do Git
```bash
git clone --branch <branch_name> <repository_url>
```
```bash
git clone --branch 1.0 [url]
```

### Verificar a branch
```bash
git branch 
```

### Baixar as atualizações
```bash
git pull
```

### Adicionar o arquivo criado, adicionar arquivo ao índice de preparação (staging area). 
### O índice de preparação é uma área intermediária entre o diretório de trabalho (working directory) e o repositório Git
```bash
git add <file>
```
```bash
git add README.md
```

### Adicionar todos os arquivos modificados
```bash
git add .
```

### Verificar o status do arquivo no repositório
```bash
git status
```

### Representa um conjunto de alterações em um ponto específico da história do seu projeto, registra apenas as alterações adicionadas ao índice de preparação.
### O comando -m permite que insira a mensagem de commit diretamente na linha de comando
```bash
git commit -m "Criar o arquivo readme"
```

### Enviar os commits locais, para um repositório remoto.
```bash
git push <remote> <branch>
```
```bash
git push origin 1.0
```

### Criar nova branch no PC
```bash
git checkout -b <branch>
```
```bash
git checkout -b desenvolvimento
```

### Adicionar todos os arquivos modificados no staging area - área de preparação
```bash
git add .
```

### Verificar em qual branch está
```bash
git branch
```

### Enviar os commits locais, para um repositório remoto.
```bash
git push <remote> <branch>
```
```bash
git push origin desenvolvimento
```

### Mudar de branch
```bash
git switch <branch>
```
```bash
git switch 1.0
```

### Mesclar o histórico de commits de um branch em outra branch
```bash
git merge <branch_name>
```
```bash
git merge desenvolvimento
```

### Fazer o push dessas alterações
```bash
git push origin <branch_name>
```
```bash
git push origin 1.0
```

### Retirar o arquivo do staging area
```bash
git restore --staged <file_path>
```
```bash
git restore --staged index.html
```

<hr>

# Autor

Prof. Diego Max da Silva<br>
https://lattes.cnpq.br/4370663836049458
