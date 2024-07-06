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
## O índice de preparação é uma área intermediária entre o diretório de trabalho (working directory) e o repositório Git
```bash
git add <file>
```
```bash
git add README.md
```
