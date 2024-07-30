
- permite a gente a atualizar e definir variáveis de configuração do nosso git que ficam armazenados em três lugares:
	global: configurações de usuario
	system: que serve para lermos as configurações do sistema como um todo
	local: configurações de um repositório


# Autentificando via chave ssh

Uma chave SSH(secure shell) é  uma outra forma de estar autentificando operações GIIT na nossa conta do GitHub :
- é um protocolo de rede que possibilita que o computador local e o servidor remoto se conectem de forma segura e criptografada por meio da internet 
- esse protocolo trabalha com um par de chaves(publica e privada):
	- privada: ao se conectar por meio do SSH nos autentificamos por meio de um arquivo da chave privada presente no computador
	- chave publica:  usar  para estar inserindo no GitHub
	- github/setting/SSH and GPG Keys