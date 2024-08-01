
# Comandos:
	- git revert  (Hash) --no--edit
	- git reset (hash) --modo(soft, mixed,hard)
# Aula git revert e git reset

- Reverter ou desfazer alterações no código fonte



# Aula 

- git revert: Comando utilizado para desfazer alterações em um repositório
	- o comando git reverse cria um commit que inverte todas as alterações desejadas 
	- git revert
- git reset: desfaz as alterações salvas e coloca o repositório no estado que se encontrava anteriormente
	- tipos de git reset 
		- --soft: (reset apenas o commit history)
		- --mixed: reseta o (commit  history e os arquivos staged)
		- --hard: reseta tudo (commit history, staged e arquivos salvos "not staged")