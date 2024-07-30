
# Criando e Clonando Repositórios locais e remotos:
Falando sobre a criação de repositórios locais existem duas formas de obter repositórios Git na nossa máquina:
	- 1º: transformando um diretório local em um repositório local com git init:
		- abra um diretório e escreva
		- git init (transforma o diretório em um repositório)
		- cat config (mostra configurações do repositório local)
	- 2º: clonando um repositório existente em um repositório local com o comando git clone
		- git clone (o repositório que deseja clonar)
			- permite clonar branches específicas do repositório
			- git clone (URL) -branch (nome branch) --single-branch
		- git remote add origin (diretório URL): vincula seu repositório local com um repositório remoto



# Configurando o Git

- git config --global user.name "nome"
- git config --global user.email "email"
- git remote set-url origin (url_repositório): Altera a referência para um repositório remoto, ou seja, um repositório hospedado em um servidor externo