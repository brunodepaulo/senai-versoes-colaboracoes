# senai-versoes-colaboracoes
Principais comandos para trabalhabarmos com versionamento:

git config - usei para configurar minha conta
Exemplo
git config --global user.email exemplo@google.com

git init - comando criar um novo repositório.

git add - usado para adicionar arquivos.
Exemplo
git add readme.txt

git clone - usado para copiar um respositório.

git commit - usado para confirmar alterações enviadas pelo git add.
Exemplo:
git commit –m “mensagem aqui do envio”

git status - Exive a lista de arquivos alterados e que ainda não foram adicionados ou confirmados.

git push - Envia alterações do ramo ao diretório.
Exemplo:
git push origin master

git checkout - Usado para altenar entre ramo ou ramos principal.
Exemplo de criar ramo:
command git checkout -b <nome-ramo>

Para simplesmente mudar de um ramo para outro, use:
Exemplo:
git checkout <nome-ramo>

git merge - Usado para mesclar uma ramificação no ramo ativo.
Exemplo:
git merge <nome-ramo>

git tag - Usado para colocar tag ou versões no git.
Exemplo:
git tag 1.1.0 <coloque-o-comentário>

git log - Exibe uma lista de compromissos em uma ramificação, juntamente com os detalhes pertinentes. Um exemplo de saída pode ser: