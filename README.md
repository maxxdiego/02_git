# 02_git
### Iniciar novo packet com GIT na máquina 
```bash
git init
```

### Definir as configurações do usuário
```bash
git config --local user.name Diego
```
```bash
git config --local user.email diego@celke.com.br
```

### Baixar os arquivos do Git
```bash
git clone --branch <branch_name> <repository_url>
```
```bash
git clone --branch 1.0 https://github.com/celkecursos/celke_como_usar_github.git
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
