# Anotações do estudo de versionamento de código


### visão geral do conteudo estudado

- introduzir o versionamento de ódigo com git e github: git, comit, branch para o arquivamento de projetos e conteudos estudados com o objetivo de registra ao máximo minha evolução nessa jornada de desenvolvimento

- saber o suficiente para criar o próprio repositório e estar sabendo fazer brunches 

- aprender instalação, configuração e Autenticação

#### Versionamento de código:
	
sistemas de controle de versão (softwares que controlam as versões de um arquivo ao longo do tempo, registram um histórico detalhado de cada alteração feita)
- Gerencia as alterações data e hora 

- tipos de sistema de controle de versão VCS centralizados(CVCS):
	- mercúrio, nele temos apenas um servidor que contem todos os arquivos de controle de versão
	EX: cvs, subversion
- sistema de controle de versão distribuidos(DVCS):
	-GIT
	-nele cada repositório é dublicado localmente
	-cada clone é como um backup	

#### Git, alguns dos comandos mais usados:
	git clone (URL)(Nomedesejadoopcional): clonar um repositorio git existente para uma nova pasta 
	git commit m'descrição do commit':  grava alterações no repositorio local
	git pull: puxa alterações do repositorio remoto para o repositorio local(busca e mescla)
	git push: empurra as alterações do repositorio local para o remoto
	git remote add origin (url): vincula seu repositório local com um repositório remoto
	git status: responsável por mostrar o estatuas da arvore de trabalho e da área de preparação(staging area) , e o estado dos arquivo
	git add: adiciona um arquivo novo eu modificações de um arquivo existene na nossa ária de preparação para um comit

#### GitHub

Plataforma de hospedaria de código para o controle de versão com git

o git atua na parte onde vai esta fazendo o gerenciamento das versões e o gitbub vai atura como o repositório remoto
