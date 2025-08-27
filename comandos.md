# Comandos GIT
Neste arquivo será apresentado os comandos Git para uso futuro.

## No primeiro uso em um pc
Para que o git avise e saiba quem fez as alterações é necessário
confugurar o usuário nas config globais do git.
```bash
git config --global user.name "Natasha Mendes"

git config --global user.email "minnatty01@gmail.com"
```

### Gestão de git
Para que o git inicialize pastas do repositório no terminal (Prompt de Comando)
 usamos o comando init, apenas uma vez.
```bash
git init
```
Para ver a situação do repositório usando o comando status.
Pode ser executado a qualquer momento para saber situação da pasta.
Se vermelho precisa adicionar arquivo, se verde estão pronto para save (commit)
Se não aparecer nada, ou arquivo não está salvo ou ja ta tudo certo.
```bash
git status
```
Abre e cria uma pasta diretamente no visual studio code.
```bash
code ./comandos.md
```

ver a situação.
```bash
git status
```

Adicionara arquivos para serem salvos.
```bash
git add .
```

Para descrever o que foi feito e deixar uma mensagem para o futuro, para lembrar e explicar o que foi feito.
```bash
git commit -m "mensagem"
```