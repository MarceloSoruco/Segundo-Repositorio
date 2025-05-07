# Segundo-Repositorio
# RESUMO #
# Atividade 1 #
## Criar um repositório e transformar em um repositório Git ##
[É o HTTPS que é pego do https://github.com/](https://github.com/)

## 1) Pelo site <github.com> cria um repositório ##
Existem 2 formas de inicializar o repositório:

## A) git init - Inicializando um repositório ##
É o mais simples, já inicializa o repositório, mas depois tem de conectar
cd .git -Entra para testar o diretório git
Depois tem de conectar o repositório local com o remoto:
git add remote origin <end-da-URL>

## B) git clone - Clonando um repositório Existente ##
git clone <end-da-URL> <Novo nome (opcional)>

Explicação das diferenças:

[Vídeo do Youtube](https://www.youtube.com/watch?v=28g7mwU-hGI)
Tempo:6:30

git remote -v -> Mostra os repositórios remotos que estão conectados

## 2) Mandar atualizações do repositório ##

git add .
git commit -m”<texto de apresentação>” (É como criar uma nova versão)
git log -> mostra o commit criado

## 3) Agora mandar atualizações para o diretório remoto ##
git remote add origin <end-da-URL>
git push -u oringin main -> Envia as atualizações do repositório local para o remoto

## 4)Enviando e Baixando Alterações com o Repositório Remoto ##
[Vídeo do Youtube](https://www.youtube.com/watch?v=bEW2VH3or1I)

## 4.1) testa se o arquivo é reconhecido ##
git status – Ver se os arquivos estão “rastreados” reconhecidos
Se a arvore esta livre – OK
Se untrack, então:

## 4.2) Editando arquivos no repositório remoto ##
[Vídeo do Youtube](https://www.youtube.com/watch?v=bEW2VH3or1I)
TEmpo:3:00
Simples, edita no lápis mesmo, depois CHANGE COMMIT
Cria um commit a mais... É como se fosse uma versão... cada commit uma “versão” nova

Da para editar pela ferramenta web browser também

Agora baixar as alterações do remoto para o local
Git Bash
Git pull

Trabalhando com Branches - Criando, Mesclando, Deletando e Tratando Conflitos
[Vídeo do Youtube](https://www.youtube.com/watch?v=D1RC51ywEmQ)

 Branch  – É como uma linha de desenvolvimento.
Pode ser tema de um projet, ou vários, como desenvolvedores trabalhando em paralelo.


## Comando de navegação ##
mkdir- cria um diretório
cd - muda de diterório
cd .. - sobre um diretório
CTRL+L - Limpa a tela
ls - lista os arquivo que estão dentro do diretório
cat - abre o arquivo. É tipo um editor, mostra o conteudo


