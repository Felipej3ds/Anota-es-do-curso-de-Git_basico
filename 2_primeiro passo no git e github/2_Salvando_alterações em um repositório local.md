- Como salvar alterações no repositório local e como passar essas alterações para um repositório remoto 

# Comando:

- git status: responsável por mostrar o estatuas da arvore de trabalho e da área de preparação(staging area) 
- git add (nome arquivo ou .): adiciona um arquivo novo eu modificações de um arquivo existente na nossa area de preparação para um commit
	- echo arquivo/ > .gitignore: (exclui um arquivo/modificação da area de  preparação)
	- echo > .gitignore (remove arquivos do gitignore)
	- .gitkeep(padrão para o git reconhecer repositórios vazios)
- git commit -m"comentários" (O commit)
	- git commit -am"comentario" (O commit sem a necessidade de um git add)
	- git log (mostra os commits feitos o autor e o email)
- git diff (Ver as modificações)
- git restore --staged (Arquivo):  (remove um arquivo da arvore de trabalho)