CRIANDO REPOSITÓRIO E DEPOIS IMPORTANDO A PASTA PARA O LOCAL DESEJADO
 1. Cria o repositório no GitHub
 2. Abre a pasta na qual vc quer deixar o repositório
 3. Dentro da pasta, abre o Git Bash
 4. 'git clone "url" '
 5. Pasta importada e já conectada com o repositório do GitHub

TENHO A PASTA E QUERO CONECTAR COM UM REPOSITÓRIO NO GITHUB
 1. Cria o repositório no GitHub
 2. Copia o link html
 3. Entra na pasta que vc quer fazer a conexão
 4. Abre o Git Bash
 5. 'git remote add origin "url do repositório"
 6. 'git remote -v' para verificar se foi adicionado
 7. 'git status' para ver se encontrou os arquivos presentes
 8. 'git add *' para adicionar todos os arquivos
 9. 'git commit -m "texto" ' para commitar os arquivos
 10. 'git push -u origin 'main ou master'