** RELAÇÃO DE COMANDOS ÚTEIS **

* COMANDO: `sudo dnf up --ref`
<br> O QUE FAZ: Atualiza os metadados dos repositórios de programas e mostra os que podem ser atualizados, se prosseguir com o comando (confirmando com "S") todos os pacotes que foram apresentados na saída do comando serão atualizados.

* COMANDO: `dnf list installed kernel` ou `dnf list kernel installed`
<br> O QUE FAZ: Mostra quais versões de kernel estão instalados.

* COMANDO: `cat /etc/os-release`
<br> O QUE FAZ: Mostra a auto-identificação do sistema operacional.

* COMANDO: `hostnamectl`
<br> O QUE FAZ: Mostra também informações do sistema instalado.

* COMANDO: `uname-a`
<br> O QUE FAZ: Mostra detalhes do kernel ativo no momento.

* COMANDO: `sudo dnf info nome-do-pacote` 
<br> O QUE FAZ: Revela detalhes do pacote em específico, incluindo repositório de origem.

* COMANDO: `dnf repolist`
<br> O QUE FAZ: Retorna uma lista dos repositórios habilitados.

* COMANDO: `dnf repolist --all`
<br> O QUE FAZ: Retorna uma lista completa dos repositórios disponíveis, e destaca quais são os habilitados e os não habilitados.

* COMANDO: `journalctl -f` 
<br> O QUE FAZ: Abre no terminal o log do sistema, ao vivo, para você acompanhar tudo o que está sendo registrado. Muito útil para ajudar a descobrir o que pode estar acontecendo quando algum programa dá problemas ao ser executado.

* COMANDO: `journalctl -r`
<br> O QUE FAZ: Abre no terminal o log do sistema em ordem inversa, do registro mais recente ao registro mais antigo.
