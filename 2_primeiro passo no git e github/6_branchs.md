
# lista

git checkout (utilizada para alternar entre branches, Criar um novo branch e alternar para ele, Descartar mudanças em arquivos, Visualizar uma versão específica de um arquivo, Alternar entre diferentes estados (commits)) 
	- git checkout -b "nome da nova branch" : (permite criar uma nova branch)
	- git checkout -b (nome branch): (passa o ponteiro do histórico comandos git para outra branch)

git clone (URL):  (clona um repositório)


git branch: (lista as branches)

git branch -d (nome branch): (exclui uma branch)

git branch -M (nome da branch): (renomeia a branch)

git push --set-upstream origin (nome da branch): (define a branch que vai ser mandada pro repositório)

git merge (nome da branch): mescla duas branches

git remote add origin (URL) : ("conecta" o seu git com um repositório remoto)

git remote get-url origin: (descobrir o endereço do repositório)

git remote add outro-nome (URL do outro repositoria) : (adicionar um segundo controle remoto para o outro repositório que deseja copiar arquivos. Isso não afetará o controle remoto existente.)

git pull  -> git fetch + git merge: (no caso o git pull serve para trazer alterações do repositório remoto para o local)



# Aula 6 

o que veremos?
	Modelos de controle de versão
	Branches de State, Release e Feature
	Branches únicas
	GitHub Flow
	Gitflow
	Fluxo de ações: git checkout


 o que são branches?
	Branches são trilhas de commits, como se fosse uma arvore
		-		Pode ser distinta entre Branches de state, Release e Feature.
		-		Branches: Diferentes para propósitos distintos
		-		Diferentes modelos/fluxos, dependendo da empresa/projeto 
			Geralmente o projeto vai ser entregue dentro de uma esteira de produção de contínuos integration/ contínuos delivery (CI/CD) (obs: nesse momento importante apenas perceber como vamos utilizar linhas de publicações distintas para funções distintas)
	Diferenciando as branches:
		Branches "long-running":  main e develop	
			Refletem os estágios do ciclo de desenvolvimento	
		 	Geralmente não se faz commits diretamente, a verdade:
				 Pull Request Merges
		Branches "short-lived": Feature e fixes
			Focadas em novas funcionalidades, correção, refatoramento, provas de conceitos, etc
			utilizada para implementas features(Funcionalidades)
			Geralmente deletada após integração

 Modelos de branches:
	Branches únicas 
		Poucas ou únicas branch com commits pequenos
		O modelo mais simples: geralmente utilizado quanto tem-se uma unica pessoa mexendo no código
		Muito comuns em projetos pessoais
	GitHub flow
		Apenas uma branch "long-running", não é tão enxuta como o modelo brunch unica Sem restrições para branches de fix, features, etc:
			Vamos ter apenas uma branch de longa prazo, quando implementarmos uma nova feature ou quando formos corrigir algum bug, abrimos uma nova branch a partir da branch de longo prazo, então implementamos o que precisarmos na nova branch e após implementarmos o que precisávamos mesclamos a branch "short-live" com a branch de longo prazo('long-running branch') 
	GitFlow:
		O modelo mais estruturado com duas ou mais branches "long-running"
		A branch mais importante seria a main uma branch que NÃO DEVE TER BUGS
		A segunda branch log ruining seria uma branch similar a branch principal mas que será utilizada para receber as atualizações dos desenvolvedores  