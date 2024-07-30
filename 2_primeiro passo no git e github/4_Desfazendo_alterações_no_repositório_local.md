
- caso tenhamos dado git init na pasta errada e queiramos fazer o versionamento dela, basta removermos o diretório .git
	(pode ser feito pelo terminal com o comando ) rm -rf .git

- Caso queiramos restaurar um arquivo na nossa arvore de trabalho
	- git restore (NOME_ARQUIVO) : restaura o arquivo para o ultimo commit
- Como alterar a mensagem do ultimo commit
	- git commit --amend -m"NOVA_MENSAGEM"
	- git commit --amend
- desfazer o utimo comit
	- git reset --(soft, mixed or hard) (rest do commit)
	- o git reset também pode ser utilizado para remover arquivos da área de preparação 
- ter um histórico mais detalha
	- git reflog (exibe um histórico detalhado das ações que modificaram o estado do repositório)