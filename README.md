## STATUS

application.yml -> resolver questão de senhas conforme dockerfile.
docker-compose.yml -> base zoada, não loga mesmo com senha certa.

Os erros acima foram resolvidos. Faltava adicionar uma linha em environment, no docker-compose.yml, MYSQL_TCP_PORT.

Parou de dar merda.
