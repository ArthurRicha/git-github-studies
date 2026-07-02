# Curso Git TMW 2025

O foco desse curso foi **aprender versionamento de código com comandos Git e repositórios remotos com o GitHub**. 

O **curso do Téo é grátis** e tem o intuito de emancipar o conhecimento da área de Dados **sem gastar uma fortuna**. Confira o material no **canal do youtube** dele:
[Curso Git 2025 - Téo Me Why](https://www.youtube.com/watch?v=84FhNXNWoig&list=PLvlkVRRKOYFQyKmdrassLNxkzSMM6tcSL)

Além do YouTube, ele tem um **site** que disponibiliza outros **materiais gratuitos com diversos conteúdos e projetos da área de Dados**. Conheça o **site de cursos** dele:
[Site de cursos](https://cursos.teomewhy.org/)

**Espero que ele possa te ajudar, assim como me ajudou!!!**

## Comandos Git

Alguns dos **comandos git** apresentados no curso:

**ls** → lista todas as pastas e arquivos da onde você está.

**cd** → muda o diretório.

**pwd** → mostra o caminho do diretório que você se encontra.

**ls -a** → exibe os arquivos ocultos.

**cd ..** → volta para a pasta anterior.

**clear ou ctrl l** → limpa o terminal.

**mkdir** → cria um diretório novo.

**cat** → mostra o que tem dentro do arquivo.

**rm** → remove arquivo ou diretório.

**rm -rf** → remove de forma recursiva e forçada todos os diretórios. 

**git init .** → inicializa o repositório git vazio podendo versionar os arquivos.

**git status** → mostra como está o diretório.

**git add** → adiciona o que vai para o commit.

**git commit -m “msg”** → salva a sua tarefa.

**nano** → editor de texto no terminal.

**git log** → mostra todos os commits.

**.** → aponta para o diretório atual

**..** → volta ao diretório anterior

* → pega todos os arquivos.

**git diff** → visualiza o que foi modificado (diferença do estado atual para o anterior)

**git reset** → retira o que vai para commit/retorna o que vai para o stage.

**git checkout** → muda de branch.

**git checkout -b** → cria uma nova branch.

**git merge** → copia os arquivos commitados de uma branch para a branch do diretório em que você se encontra.

**git branch** → visualiza a branch que você se encontra e as branchs do projeto.

**git branch -D** → apaga a branch. (Tem que estar em outra branch para deletar a que você quer).

**git push** → envia as alterações/commits de um repositório local para um repositório remoto.

**pull request** → propõe a alteração de códigos de uma ramificação (branch) para a ramificação principal.

**git pull** → envia as alterações/commits de um repositório remoto para um repositório local.

**git clone** → cria uma cópia local completa de um repositório Git existente.

## Fluxo de Trabalho Git Local

1. git checkout -b
2. cria ou atualiza arquivos
3. git status
4. git add arquivos
5. git status
6. git commit -m "minha mensagem"
7. git checkout main
8. git merge nova_branch

## Fluxo de Trabalho Github <> Local (projeto próprio ou da sua empresa)

1. git clone
2. git checkout -b <nova_branch>
3. alterações de arquivos
4. git status
5. git add arquivos
6. git status
7. git commit -m "nova mensagem"
8. git push origin <nova_branch>
9. abrir Pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>

## Fluxo de trabalho GitHub <> Local (projetos open-source)

1. Fork do projeto para seu próprio github
2. git clone
3. git checkout -b <nova_branch>
4. alterações de arquivos
5. git status
6. git add arquivos
7. git status
8. git commit -m "nova mensagem"
9. git push origin <nova_branch>
10. abrir Pull request no GitHub da branch fork para a main do projeto original
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -D <nova_branch>