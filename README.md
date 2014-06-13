#Passo utilizados para criação do repositorio no github
1. Criando o arquivo luvett em /var/www/html/
   mkdir estudo_git
2. Iniciando o repositorio dentra da pasta criada
	git init	
3. Colocando as credenciais do autor no repositorio
	git config --global user.name "Luis Alberto Concha Curay"
	git config --global user.email "luvett11@gmail.com"
4. Criando 1º arquivo para teste
	touch arquivo_01.txt
5. Adicionando conteudo no arquivo criado
	vim arquivo_01.txt
6. Verificando arquivo no "Untracked files"
	git status
7. Adicionando arquivo para iniciar versionamento:
	git add arquivo_01.txt	
8. Fazendo commit:
	git commit arquivo_01.txt -m "fazendo o primeiro commit do documento"
9. Verificando log criado:
	git log -p
10. Criando arquivo 
	touch README.md
11. Adicionando arquivo para versionamento: 
	git add README.md
12. Comitando arquivo
	git commit README.md -m "adicionando arquivo readme"
13. Preparando arquivo para enviar para o github
    git remote add origin https://github.com/luvett/estudo_git.git	
14. Fazendo 1º push
	git push -u origin master    
